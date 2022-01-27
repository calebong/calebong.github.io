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



Last Updated: 2022-01-27 08:44:01 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/australia/export-prices </td>
   <td style="text-align:left;"> 2022-01-27 08:40:57 </td>
   <td style="text-align:left;"> Australia Export Prices Rise the Least in 7 Quarters </td>
   <td style="text-align:left;"> Australia's export prices increased by 3.5% on quarter in Q4 2021, easing from a 6.2% growth in Q3. This was the fifth straight quarter of rises. Main contributors to the rise were: coal, coke, and briquettes (51.9%), driven by surging global demand for thermal and coking coals; gas, natural and manufactured (36.1%), due to the rise in oil-linked contracts capturing the continued oil price rises in 2021;non-ferrous metals (9.5%), through increased manufacturing demand as pandemic restrictions ease and economic activity increases; meat and meat preparations (4.5%), due to strong demand for beef and constrained global supply, and petroleum, petroleum products and related materials (8.7%), driven by strong global oil demand outpacing growth in global supply. Meanwhile, the main offsetting contributor was metalliferous ores and metal scrap (-29.4%), dragged down by the fall in demand for iron ore from China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/import-prices </td>
   <td style="text-align:left;"> 2022-01-27 08:33:00 </td>
   <td style="text-align:left;"> Australia Q4 Import Prices Rise the Most in 9 Years </td>
   <td style="text-align:left;"> Australia's import prices rose by 5.8 percent quarter-on-quarter in Q4 2021, after a 5.4 percent gain in Q3. This was the fourth straight quarter of growth in import prices and the steepest pace since Q4 2008, amid a faster recovery in the economy from the COVID-19 and soaring energy prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60149374?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-27 08:12:24 </td>
   <td style="text-align:left;"> Tesla expects 50% growth despite supply chain woes </td>
   <td style="text-align:left;"> Tesla sales will grow by more than 50% in 2022 compared with last year despite supply chain problems, chief executive Elon Musk has said.                                                         , The electric carmaker recorded a record $5.5bn (£4bn) earnings last year.                                                                                                                         , Sales at the firm rocketed 71% to $53.8bn in 2021, as it delivered more than 936,000 vehicles to customers.                                                                                       , But the firm warned growth would slow, as supply chain issues affecting carmakers continue to limit its manufacturing capacity.                                                                   , Mr Musk said that 2021 was "a breakthrough year for Tesla, and for electric vehicles in general".                                                                                                 , "While we battled, and everyone did, with supply chain challenges through the year, we managed to grow our volumes by nearly 90% last year," he said.                                             , The company said its supply chain was "the main limiting factor" to growth, "which is likely to continue through 2022".                                                                           , He said he expected growth "comfortably above 50%" in 2022.                                                                                                                                       , Carmakers around the world are grappling with a shortage of microchips, among other production and supply chain snarls, though Tesla had been seen as faring better than most.                    , It uses chips that are less scarce and quickly re-writes software, while competitors slow production.                                                                                             , The firm, which started in California, now has factories in China and Texas, with another under construction in Berlin.                                                                           , The plants are expected to help Tesla dramatically expand its production, even as it faces new competition from established carmakers turning their attention to electric vehicles.               , It has the challenge of opening two factories this year with chips and other parts in short supply and new batteries and technologies to be introduced.                                           , But Mr Musk said the firm was looking at building new factories in new locations in the future.                                                                                                   , Looking ahead, Mr Musk said he expected fully self-driving cars "will become the most important source of profitability for Tesla".                                                               , "The cars in the fleet essentially becoming self-driving via a software update might end up being the biggest increase in asset value of any asset class in history, we shall see," Mr Musk added., He has downplayed concerns that other firms might pose a threat, noting on Twitter that companies like GM have "some room for improvement".                                                       , Dan Ives, analyst at Wedbush Securities, said he thought Tesla would have been able to deliver 10% to 20% more cars in the last three months of the year without the supply issues.               , But despite that cloud he said, "these delivery numbers combined with this 'impressive earnings beat' speaks to an EV demand trajectory that looks quite robust for Tesla heading into 2022".     , Can they keep their progress hidden from their loved ones?                                                                                                                                        , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                  , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-27/eli-manning-backed-brand-velocity-spac-pulls-plans-for-an-ipo?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-27 08:07:02 </td>
   <td style="text-align:left;"> Eli Manning-Backed Brand Velocity SPAC Pulls Plans for an IPO </td>
   <td style="text-align:left;"> Eli Manning                                                                                                                                                                                                                                                                                                                               , Photographer: Sarah Stier/Getty Images                                                                                                                                                                                                                                                                                                    , Dan Reichl                                                                                                                                                                                                                                                                                                                                , Brand Velocity Acquisition Corp., the blank-check firm whose advisers include former National Football League quarterback Eli Manning, dropped its plans for an initial public offering.                                                                                                                                                  , The special purpose acquisition company, or SPAC, asked to withdraw its registration for an IPO in a filing Wednesday with the U.S. Securities and Exchange Commission. The company filed last March to raise $200 million to seek a merger target, saying it planned to focus on “a branded consumer-facing businesses in North America.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-27/red-hot-rally-in-palm-oil-reveals-dirty-jobs-that-no-one-wants?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-27 08:00:00 </td>
   <td style="text-align:left;"> Red-Hot Rally in Palm Oil Reveals Dirty Jobs That No One Wants </td>
   <td style="text-align:left;"> Anuradha Raghu                                                                                                                                                                                                                           , Oil palm planters in Malaysia are confronting a hard truth -- behind the red-hot rally in prices are thousands of jobs that nobody wants.                                                                                                , While high prices typically encourage planting and production of crops, output in No. 2 grower Malaysia slumped to a five-year low last year and planters say the main reason for that is the industry’s worst-ever shortage of workers.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-26/commodities-index-hits-fresh-record-as-inflation-concerns-spread?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-27 07:39:15 </td>
   <td style="text-align:left;"> Commodities Index Hits Fresh Record as Inflation Concerns Spread </td>
   <td style="text-align:left;"> Carlos Caminada                                                                                                                                                                                                      , A gauge of commodities soared to an all-time high as geopolitical tensions boosted energy prices, worsening fears of inflation around the world.                                                                     , The Bloomberg Commodity Spot Index, which tracks 23 energy, metals and crop futures contracts, rose 1% on Wednesday, topping an October record. The index has doubled since sinking to a four-year low in March 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/26/us/politics/democrats-china-competitiveness-bill.html </td>
   <td style="text-align:left;"> 2022-01-27 07:22:34 </td>
   <td style="text-align:left;"> Democrats Renew Push for Industrial Policy Bill Aimed at China - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , A major competitiveness bill passed the Senate last year with bipartisan support, only to stall. Democrats hope to revive it in the House, but first they will have to bridge big differences.                                                                                                                                                                                                                                                                                                                                                                                                            , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , By Catie Edmondson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , WASHINGTON — Biden administration officials and Democrats in Congress are pushing to revive stalled legislation that would pour billions of dollars into scientific research and development and shore up domestic manufacturing, amid deep differences on Capitol Hill about the best way to counter China and confront persistent supply chain woes.                                                                                                                                                                                                                                                    , House Democrats unveiled a 2,900-page bill on Tuesday evening that would authorize $45 billion in grants and loans to support supply chain resilience and American manufacturing, along with providing billions of dollars in new funding for scientific research. Speaker Nancy Pelosi said in a statement that she hoped lawmakers would quickly begin negotiations with the Senate, which passed its own version of the bill last June, to settle on compromise legislation that could be sent to President Biden for his signature.                                                                   , But the effort faces obstacles in Congress, where attempts to sink significant federal resources into scientific research and development to bolster competitiveness with China and combat a shortage of semiconductors have faltered. The Senate-passed measure fizzled last year amid ideological disputes with the House and a focus on efforts to pass Mr. Biden’s infrastructure and social policy bills. For months, the competitiveness measure was rarely even mentioned, except perhaps by Senator Chuck Schumer, Democrat of New York and the majority leader, who has personally championed it., But facing a disruptive semiconductor shortage that has broken down supply chains and helped fuel inflation, Democrats are now vigorously pressing ahead on the bill. With Mr. Biden’s domestic agenda sputtering, the party is eager for a legislative victory, and top administration officials and lawmakers have said they hope to send a compromise bill to the president’s desk in a matter of months.                                                                                                                                                                                              , “We have no time to waste in improving American competitiveness, strengthening our lead in global innovation and addressing supply chain challenges, including in the semiconductor industry,” Mr. Schumer said.                                                                                                                                                                                                                                                                                                                                                                                          , Both the House bill and the one that passed the Senate last year would send a lifeline to the semiconductor industry during a global chip shortage that has shut auto plants and rippled through the economy. The bills would offer chip companies $52 billion in grants and subsidies with few restrictions.                                                                                                                                                                                                                                                                                             , The measures would also pour billions more into scientific research and development pipelines in the United States, create grants and foster agreements between companies and research universities to encourage breakthroughs in new technologies, and establish new manufacturing jobs and apprenticeships.                                                                                                                                                                                                                                                                                             , “The proposals laid out by the House and Senate represent the sort of transformational investments in our industrial base and research and development that helped power the United States to lead the global economy in the 20th century,” Mr. Biden said in a statement. “They’ll help bring manufacturing jobs back to the United States, and they’re squarely focused on easing the sort of supply chain bottlenecks like semiconductors that have led to higher prices for the middle class.”                                                                                                        , Lawmakers will still need to overcome differing views in the House and Senate over how best to take on China and, perhaps more crucially, how to fund the nation’s scientific research.                                                                                                                                                                                                                                                                                                                                                                                                                   , “There are disagreements, legitimate disagreements,” Gina Raimondo, the commerce secretary, said in an interview. “How do we do this? How do we get it right? There doesn’t seem to be much disagreement over the core $52 billion appropriation for chips. There is disagreement around how we make investments in research and development in basic science.”                                                                                                                                                                                                                                           , One major difference is that while the Senate bill invests heavily in specific fields of cutting-edge technology, such as artificial intelligence and quantum computing, the House bill places few stipulations on the new round of funding, other than to say that it should go toward fundamental research.                                                                                                                                                                                                                                                                                             , In a memo on the legislation, House aides wrote that their measure was “focusing on solutions first, not tech buzzwords.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Some experts argue that approach lacks urgency. Stephen Ezell, the vice president for global innovation policy at the Information Technology and Innovation Foundation, a policy group that receives funding from telecommunications and tech companies, called the House bill “not sufficient to enable the United States to win the advanced technology competition with China.” He argued that the focus on advanced technology in the Senate-passed bill would do more to increase American competitiveness.                                                                                          , The pandemic sparked the problem. The highly intricate and interconnected global supply chain is in upheaval. Much of the crisis can be traced to the outbreak of Covid-19, which triggered an economic slowdown, mass layoffs and a halt to production. Here’s what happened next:                                                                                                                                                                                                                                                                                                                       , A reduction in shipping. With fewer goods being made and fewer people with paychecks to spend at the start of the pandemic, manufacturers and shipping companies assumed that demand would drop sharply. But that proved to be a mistake, as demand for some items would surge.                                                                                                                                                                                                                                                                                                                           , Demand for protective gear spiked. In early 2020, the entire planet suddenly needed surgical masks and gowns. Most of these goods were made in China. As Chinese factories ramped up production, cargo vessels began delivering gear around the globe.                                                                                                                                                                                                                                                                                                                                                    , Then, a shipping container shortage. Shipping containers piled up in many parts of the world after they were emptied. The result was a shortage of containers in the one country that needed them the most: China, where factories would begin pumping out goods in record volumes                                                                                                                                                                                                                                                                                                                        , Demand for durable goods increased. The pandemic shifted Americans’ spending from eating out and attending events to office furniture, electronics and kitchen appliances – mostly purchased online. The spending was also encouraged by government stimulus programs.                                                                                                                                                                                                                                                                                                                                    , Strained supply chains. Factory goods swiftly overwhelmed U.S. ports. Swelling orders further outstripped the availability of shipping containers, and the cost of shipping a container from Shanghai to Los Angeles skyrocketed tenfold.                                                                                                                                                                                                                                                                                                                                                                 , Labor shortages. Businesses across the economy, meanwhile, struggled to hire workers, including the truck drivers needed to haul cargo to warehouses. Even as employers resorted to lifting wages, labor shortages persisted, worsening the scarcity of goods.                                                                                                                                                                                                                                                                                                                                            , Component shortages. Shortages of one thing turned into shortages of others. A dearth of computer chips, for example, forced major automakers to slash production, while even delaying the manufacture of medical devices.                                                                                                                                                                                                                                                                                                                                                                                , A lasting problem. Businesses and consumers reacted to shortages by ordering earlier and extra, especially ahead of the holidays, but that has placed more strain on the system. These issues are a key factor in rising inflation and are likely to last for months — if not longer.                                                                                                                                                                                                                                                                                                                     , In addition, as lawmakers debate how to counter Beijing’s rising influence, efforts to compromise on the foreign policy components of the legislation will most likely create tensions between the chambers and between Democrats and Republicans. In the Senate, for example, lawmakers included stricter requirements for when universities must report foreign funding to the Education Department.                                                                                                                                                                                                    , Democrats in the House have resisted the Senate’s proposed foreign policy provisions, complaining that the chamber focused too narrowly on countering China rather than investing in domestic manufacturing. Much of the foreign policy legislation added by Democrats to the House bill is focused on climate change; the House measure would also authorize $225 million over five years to bolster the State Department’s military training and education programs in the Indo-Pacific region.                                                                                                         , Few Republicans are expected to support the House bill, though some of the measures included in the legislation have previously garnered bipartisan support.                                                                                                                                                                                                                                                                                                                                                                                                                                              , “It reflects virtually no Republican input and — to be frank — will be dead on arrival in the U.S. Senate,” said Representative Michael McCaul of Texas, the top Republican on the Foreign Affairs Committee, who said the bill did not take a hard enough line against China.                                                                                                                                                                                                                                                                                                                            , The House bill would ease immigration restrictions on high-level workers and entrepreneurs, allowing individuals with doctoral degrees in science, technology, engineering and mathematics to receive green cards even if the United States has already hit its visa quota. It would also allow a noncitizen to petition for a green card as an “immigrant entrepreneur.”                                                                                                                                                                                                                                 , There were signs that the House proposal could ignite a lobbying skirmish on other technology issues as well. It includes measures aimed at large online retail marketplaces like Amazon, eBay and Etsy, which critics say can be conduits for counterfeits, stolen goods and dangerous products. Some of the language in the bill would make sites like Amazon liable for trademark infringement lawsuits if they did not take steps to prevent counterfeits from moving across their virtual shelves.                                                                                                   , House lawmakers had privately derided the Senate bill as riddled with pet projects, citing provisions as diverse as a new round of funding for NASA and a ban on the sale of shark fins. But the House bill also includes a slew of measures that appear to have little to do with manufacturing and global competitiveness, including provisions authorizing marine mammal research, efforts to conserve coral reefs and a $4 billion contribution to the United Nations-led Green Climate Fund.                                                                                                         , David McCabe contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/26/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-01-27 07:09:05 </td>
   <td style="text-align:left;"> Stock futures rise as investors assess Fed update </td>
   <td style="text-align:left;"> , Stock futures rose on Wednesday night after the Dow Jones Industrial Average and S&amp;P 500 turned lower following a Federal Reserve update by chair Jerome Powell, at the conclusion of its two-day meeting.                                                                                                                                                                                                                                                                                        , Futures tied to the Dow rose 128 points, or 0.3%. S&amp;P 500 futures and Nasdaq 100 futures gained 0.5% and 0.8%, respectively.                                                                                                                                                                                                                                                                                                                                                                      , Some tech shares were higher in extended trading, after continued swings in the regular session. Netflix jumped more than 4% on news that Pershing's Bill Ackman bought 3.1 million shares. Tesla gained almost 3% following a strong earnings report. Meanwhile, Intel lost 2%, despite strong earnings.                                                                                                                                                                                         , In regular trading, the Dow ended the day down 129 points, after gaining more than 500 points at one point, following the Fed update. The S&amp;P 500 lost 0.2% and the Nasdaq Composite was little changed, with a boost from Microsoft's post-earnings gain.                                                                                                                                                                                                                                        , The week's volatility continued on Wednesday and stocks took a turn lower after the Fed concluded its two-day meeting and signaled the central bank would hikes rates to fight persistent inflation. Powell said there's "quite a bit of room" to do so before hurting the labor market. The benchmark 10-year Treasury yield climbed above 1.8% following his remarks.                                                                                                                           , "While offering some clarity on how the Fed would begin the process of removing policy accommodation, the outcome of the meeting fell short in providing the needed guidance on the timing and magnitude of the shift in policy," said Charlie Ripley, senior investment strategist for Allianz Investment Management.                                                                                                                                                                            , Some investors have started to bet on as many as five rate hikes this year, following Powell's press conference. Uncertainty about the timing and magnitude of the Fed's plans to tighten monetary policy had been building since the December meeting.                                                                                                                                                                                                                                           , "Today's meeting has market participants fully convinced that a March hike is certain, but with Chairman Powell not making any timing commitments, the door is slightly open for a slower moving Fed," Ripley added.                                                                                                                                                                                                                                                                              , Mohamed El-Erian says Fed missed a 'golden opportunity' to address inflation concerns                                                                                                                                                                                                                                                                                                                                                                                                             , Goldman says buy these beaten-up innovative stocks, with some down 50%                                                                                                                                                                                                                                                                                                                                                                                                                            , David Einhorn predicts inflation will cause a recession, adds new positions                                                                                                                                                                                                                                                                                                                                                                                                                       , Upholdings' Robert Cantwell said the markets experienced a relief rally following Microsoft's strong earnings report Tuesday night, which appeared to be a "good bellwether" for social media, gaming, software and other Nasdaq categories before the Fed update.                                                                                                                                                                                                                                , "The market in our view is totally overshooting and losing its mind, creating great opportunities for long term growth investors to snap up lots of great shares because, interestingly, it hasn't really affected companies that actually carry debt," Cantwell said of the Fed rates. "Since the end of last year the market has been most aggressively discounting companies that are going to generate more cash in the future than they're generating today… We're a little upside down now.", Thursday is a packed morning for earnings, with Mastercard, Deutsche Bank, Blackstone, Southwest Air and JetBlue all scheduled to report quarterly results before the bell. Danaher, Valero and Northrop Grumman are also set to report.                                                                                                                                                                                                                                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/bill-ackman-says-his-hedge/story.aspx?guid={4B6438AC-503F-4355-BD13-4C654D1C89FB}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-27 06:39:23 </td>
   <td style="text-align:left;"> Bill Ackman says his hedge fund just bought 3.1 million shares of Netflix - MarketWatch </td>
   <td style="text-align:left;"> Billionaire hedge fund manager Bill Ackman on Wednesday said his firm has purchased more than 3.1 million shares of Netflix Inc. 
        NFLX,
        -1.83%,
       making it a top-20 holder. "The opportunity to acquire Netflix at an attractive valuation emerged when investors reacted negatively to the recent quarter's subscriber growth and management's short-term guidance. Netflix's substantial stock price decline was further exacerbated by recent market volatility," said Ackman, who is chief executive of Pershing Square Capital Management. He announced the investment on his Twitter account and in a press release. Netflix was not immediately available for comment. , Some Canadian retailers are now requiring proof of vaccination due to local regulations, resulting in some critics calling to boycott Walmart in response                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gap-leave-sp-500-next/story.aspx?guid={6C554428-8CEB-4845-A0E8-827904CB0EF3}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-27 06:33:37 </td>
   <td style="text-align:left;"> Gap to leave S&amp;P 500 next week, moving to midcap index  - MarketWatch </td>
   <td style="text-align:left;"> Gap Inc. 
        GPS,
        -0.85%
       is leaving the S&amp;P 500 index 
        SPX,
        -0.15%,
       index provider S&amp;P Dow Jones Indices said late Wednesday, underscoring the challenges faced by retailers in recent years. Constellation Energy Corp. 
        CEG,
        +50.00%
       will replace Gap in the key equity index, with the retailer, parent to Banana Republic, Old Navy and Athleta in addition to the namesake store brand and others, replacing fast-food chain Jack in the Box Inc. 
        JACK,
        +0.47%
       in the S&amp;P MidCap 400. Jack in the Box will replace Spectrum Pharmaceuticals Inc. 
        SPPI,
        -4.40%
       in the S&amp;P SmallCap 600, S&amp;P Dow Jones said. The changes take effect on Feb. 3. Exelon Corp. 
        EXC,
        +0.43%
       is spinning off Constellation Energy in a transaction expected to close Feb. 2. , Tesla Inc.  reports quarterly earnings and sales above expectations, but says its factories have been running below capacity for several months thanks to supply-chain constraints.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-26/pershing-square-now-among-netflix-s-top-20-holders-ackman-says?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-27 06:32:33 </td>
   <td style="text-align:left;"> Netflix Secures Endorsement From Bill Ackman After Stock Decline </td>
   <td style="text-align:left;"> Bill Ackman                                                                                                                                                                                                                       , Lucas Shaw                                                                                                                                                                                                                        ,  and Jessica Park                                                                                                                                                                                                                 , Hedge fund magnate Bill Ackman has acquired more than 3.1 million shares in Netflix Inc., offering a vote of confidence in the streaming giant after the stock collapsed in recent days.                                          , Ackman’s firm, Pershing Square Capital Management, is now among Netflix’s top 20 shareholders, the investor said in a tweet on Wednesday. Netflix climbed as much as 6.2% in after-market trading following Ackman’s announcement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-26/bond-slide-dollar-jump-on-fed-pressures-asia-open-markets-wrap </td>
   <td style="text-align:left;"> 2022-01-27 06:32:27 </td>
   <td style="text-align:left;"> Asia Stocks Mixed, Treasuries Trim Drop After Fed: Markets Wrap </td>
   <td style="text-align:left;"> Sunil Jagtiani                                                                                                                                                                                                                       , Asian stocks were mixed and Treasuries trimmed a drop Thursday as investors evaluated Federal Reserve Chair Jerome Powell’s signal of a March interest-rate liftoff and the possibility of hikes at each policy meeting.             , Equities fluctuated in Japan and slipped in Australia and South Korea, where Samsung Electronics Co. missed profit estimates. U.S. contracts edged higher after the fallout from the Fed wiped out a Wall Street rally on Wednesday.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/26/stocks-making-the-biggest-moves-after-the-bell-tesla-netflix-lendingclub-and-more.html </td>
   <td style="text-align:left;"> 2022-01-27 06:28:35 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after the bell: Tesla, Netflix, LendingClub and more </td>
   <td style="text-align:left;"> , Check out the companies making headlines after the bell Wednesday:                                                                                                                                                                                                , Netflix — Shares of Netflix jumped more than 5% after hours after Pershing Square's Bill Ackman said his firm "recently" purchased more than 3.1 million Netflix shares, making it a top-20 holder of the stock.                                                  , LendingClub — Shares of LendingClub slid 14.7% despite reporting strong earnings and revenue for the most recent quarter. The fintech company's first-quarter income and revenue guidance were both lower than analysts had expected, according to Refinitiv.     , Intel — The tech company saw its shares fall 2% after hours despite reporting better-than-expected results and delivering upbeat guidance. The company's gross margin forecast or 52% in the first quarter missed estimates of almost 53%.                        , Tesla — Shares of the electric vehicle maker fell 2.6% after the company said its supply chain issues could persist throughout 2022, in its quarterly earnings report. Tesla beat analysts' expectations on both earnings and revenue for the most recent quarter., Levi Strauss — The apparel retailer's shares gained 2.6% after the company reported its quarterly results. It reported earnings of 41 cents per share, beating estimates by 1 cent. Revenue beat expectations as well.                                            , ServiceNow — Cloud company ServiceNow jumped 8.5% after it named Chirantan "CJ" Desai, its chief product and engineering officer, its new chief operating officer. It also reported earnings excluding items that beat Wall Street forecasts.                     , Lam Research — The semiconductor company's shares fell 4.9% after Lam reported a revenue miss in its most recent quarter's results. It logged $4.23 billion in revenue for the quarter, compared to expectations of $4.42 billion, according to FactSet.          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/26/politics/china-tariffs-biden-policy/index.html </td>
   <td style="text-align:left;"> 2022-01-27 06:14:16 </td>
   <td style="text-align:left;"> Why Biden is keeping Trump's China tariffs in place - CNNPolitics </td>
   <td style="text-align:left;"> Washington (CNN)President Joe Biden reversed a number of the Trump administration's policies during his first year in office -- but he has left tariffs in place on $350 billion of Chinese goods that were imposed by his predecessor.                                                                                                                                                                               , Some of those tariffs, which are paid by American importers, have been in place for nearly four years. Former President Donald Trump's controversial trade war with China began in 2018 when he slapped tariffs on $50 billion of Chinese-made goods. Over the next year, he added duties to more items after Beijing retaliated with tariffs on some American-made products.                                         , After months of escalation, Trump and Chinese President Xi Jinping came to a truce at the beginning of 2020, signing what's known as the Phase One agreement. It reduced the rate of some of the tariffs, but left them in place, and China agreed to increase its purchases of US goods and agricultural products -- setting an ambitious target of buying $200 billion more than it did before the trade war began. , But it's becoming clear that China has failed to meet those targets. It's on track to purchase only 60% of the goods it committed to buy, according to Chad Bown, a senior fellow at the Peterson Institute for International Economics who tracks China's purchases.                                                                                                                                                 , Biden suggested recently that's the reason he's leaving the tariffs in place, despite pressure from the American business community to remove them as companies struggle with inflation and supply chain disruptions. US importers have paid nearly $123 billion to cover the cost of the China tariffs since 2018, according to US Customs and Border Protection.                                                    , "It's uncertain," Biden said last week at a news conference when asked if it's time to begin lifting some of the tariffs.                                                                                                                                                                                                                                                                                             , "I'd like to be able to be in a position where I can say they're meeting the commitments, or more of their commitments, and be able to lift some of it. But we're not there yet," he added.                                                                                                                                                                                                                           , China falls short of Phase One commitments                                                                                                                                                                                                                                                                                                                                                                            , Under the terms of the deal, China committed to ramp up its purchases of US goods and agricultural projects, setting specific amounts for different categories to be bought over the next two years.                                                                                                                                                                                                                  , Even at the time the agreement was signed, experts were skeptical China would be able to meet its pledge. When the Covid-19 pandemic slowed trade around the globe just weeks after the deal was signed, it made it even harder for Beijing to meet the targets.                                                                                                                                                      , While China is importing more from the United States than it did before the tariffs were put in place, it has fallen short of its commitments.                                                                                                                                                                                                                                                                        , Exports of US-manufactured goods, including aircraft and autos, have yet to recover to pre-trade-war levels. China has come closer to meeting its pledge when it comes to US agricultural exports, increasing its purchases of soybeans, wheat and corn. Those exports came to a near standstill in 2018.                                                                                                             , But the Phase One agreement doesn't dictate any repercussions in the event that China misses its goals. It's up to Biden to decide whether to keep the tariffs in place.                                                                                                                                                                                                                                              , Biden faces pressure from the business community                                                                                                                                                                                                                                                                                                                                                                      , The tariffs hit a wide range of Chinese-made goods, including baseball hats, luggage, bicycles, TVs and sneakers. The duties make it more expensive for American businesses to import these goods from China, many of which are not manufactured in the US at a pace that meets the demand.                                                                                                                           , As inflation rises and supply chain disruptions continue, pressure from the business community is ramping up on the Biden administration to lift the tariffs. The move wouldn't solve the supply chain problems, but it could help alleviate some of the inflationary pressure facing importers.                                                                                                                      , "It's never been a good time for these tariffs, and now is a particularly bad time for them," said Steve Lamar, president and CEO of the American Apparel and Footwear Association.                                                                                                                                                                                                                                   , The new year is "really a continuation of the worst of the problems we've seen," Lamar added, noting that supply chain disruptions are still causing shipping delays, some holiday goods still haven't arrived on store shelves, and the Omicron variant of the coronavirus caused some factories and retail stores to temporarily close.                                                                             , Biden moves 'slow' on trade policy                                                                                                                                                                                                                                                                                                                                                                                    , At the start of Biden's tenure, a large part of his focus was on domestic policy, successfully pushing an economic pandemic relief bill and eventually an infrastructure investment package through Congress.                                                                                                                                                                                                         , But in October, the Biden administration made some trade policy changes. It reached an agreement with the European Union to ease Trump-era sanctions on aluminum and steel. As part of the deal, the EU also agreed to drop retaliatory tariffs against American products including Harley-Davidson motorcycles and Kentucky bourbon.                                                                                 , The Biden administration also announced in October that it would reinstate some China tariff waivers that US importers had previously received. The process to apply for a reinstatement of expired waivers launched in the fall, but the requests are still under review. More than 2,000 exclusions were granted under the Trump administration but only 549 are eligible for another extension.                    , Meanwhile, Congress allowed two longstanding trade programs to expire at the end of 2020 -- effectively raising tariffs on a range of goods from various countries. Legislation has been introduced to renew the programs, but has yet to pass both chambers of Congress.                                                                                                                                             , "When it comes to trade policy, the administration is moving very slowly," Lamar said.                                                                                                                                                                                                                                                                                                                                , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-26/europe-lng-thirst-will-get-some-relief-from-brazil-s-hydro-boost?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-27 06:07:44 </td>
   <td style="text-align:left;"> Europe LNG Thirst Will Get Some Relief From Brazil’s Hydro Boost </td>
   <td style="text-align:left;"> Sergio Chapa                                                                                                                                                                                                                                          , , Peter Millard                                                                                                                                                                                                                                       , , and Gerson Freitas Jr                                                                                                                                                                                                                               , Europe, which has been luring liquefied natural gas cargoes away from Asia, will now have less competition from Brazil as rains are refilling the South American country’s hydroelectric dams.                                                        , Brazil’s hydro power generation is up nearly 25% from a year ago after a historic drought last year depleted reservoirs and led the nation to import a record 135 LNG cargoes, pulling supplies that would have traditionally gone to Europe or Asia.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 06:03:38 </td>
   <td style="text-align:left;"> Toronto Stocks Little Changed on Wednesday </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, was around the flatline on Wednesday, as gains on consumer discretionary, consumer staples, and financials stocks were offset by losses on mining and healthcare stocks. After trading most of the session above the redline, the Canadian stocks gave up the gains with Powell remarks. Fed’s Chair Powell said during the regular press conference after the FOMC decision that there is quite a bit of room to raise interest rates without dampening employment. Meanwhile, Canada’s central bank decided to leave unchanged both its interest rates and the forward guidance, which sees a rate hike in the middle quarters of 2022. Policymakers noted that inflation rates are expected to moderate to the target 2% in the latter half of the year, while one of the major upside risks, gasoline prices, saw recent declines. On corporate updates, NBC analysts raised the target on Canadian National Railway Co. to C$172 from a prior C$170 per share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/01/26/russia-ukraine-citizen-by-cnn-marquardt-chance-ctzn-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-27 06:02:41 </td>
   <td style="text-align:left;"> These outcomes in Ukraine would surprise CNN reporter - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-26/hair-trigger-stocks-run-into-ground-by-powell-s-hawkish-harping?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-27 05:59:27 </td>
   <td style="text-align:left;"> Jittery Markets Buckle as Powell Signals They Must Go It Alone </td>
   <td style="text-align:left;"> Jerome Powell                                                                                                                                                                                                                                                                                                                                                                                                                               , Photographer: Brendan Smialowski/AFP/Bloomberg                                                                                                                                                                                                                                                                                                                                                                                              , Lu Wang                                                                                                                                                                                                                                                                                                                                                                                                                                     ,  and Vildana Hajric                                                                                                                                                                                                                                                                                                                                                                                                                         , Jerome Powell stuck to one message Wednesday, that the economy is strong and inflation must come down. Harried stock traders thought they heard another one: you’re on your own.                                                                                                                                                                                                                                                            , The result was another heart-rending turnaround in financial assets, with the S&amp;P 500 giving up a gain of 2% for its biggest downward reversal in almost two years. Two-year Treasury yields notched the biggest one-day jump since March 2020 with a 13 basis-point surge. It was the third day of volatility as the Federal Reserve concluded its meeting with warring economic narratives playing out across increasingly thin liquidity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/hilsenrath-jerome-powells-press-conference-triggered-market-volatility-for-2022 </td>
   <td style="text-align:left;"> 2022-01-27 05:54:11 </td>
   <td style="text-align:left;"> Jon Hilsenrath: Jerome Powell's press conference triggered market volatility for 2022 </td>
   <td style="text-align:left;"> Wall Street Journal senior writer Jon Hilsenrath joins ‘The Claman Countdown’ with reaction to the news conference.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Wall Street Journal senior writer Jon Hilsenrath joined "The Claman Countdown" Wednesday with reaction to the economic "uncertainty" in Federal Reserve Chair Jerome Powell's news conference.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , FED SIGNALS INTEREST RATE HIKE COULD COME ‘SOON’ AS INFLATION RAGES                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , JON HILSENRATH: Because I think that's really the story that comes out of this press conference – is market volatility. When you put together everything that Jay Powell said, he said, 'Look this, this recovery is not going to look anything, it hasn't looked anything like the recovery last time around.' Therefore, the plan that they had last time around, after the ‘08 - ’09 crisis, has to be torn up and thrown out. The last crisis, they came out, they raised rates very gradually. They took a long time to do it. They had a very slow unwind of the balance sheet. He says they're tearing that up, and they're going to be having discussions meeting by meeting. , So the Fed is uncertain about how this is going to play out in terms of how fast they're going to have to raise interest rates, how far they're going to have to raise interest rates, and what they're going to have to do to the balance sheet. There it is, the volatility index. And because of the Fed's uncertainty, I think the market is digesting that its uncertain. And I think that the watchword we're going to have for the year 2022 is going to be volatility, which really isn't great news for market values… I think it's going to be a volatile year for the market, and that's what Jay Powell triggered today.                                                  , WATCH THE FULL INTERVIEW BELOW:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Wall Street Journal senior writer Jon Hilsenrath and Nuveen chief investment strategist Brian Nick break down Federal Revere Chair Jerome Powell’s news conference </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-26/chevron-hikes-dividend-6-as-oil-prices-surge-near-90-a-barrel?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-27 05:48:42 </td>
   <td style="text-align:left;"> Chevron Hikes Dividend 6% as Oil Prices Surge Near $90 a Barrel </td>
   <td style="text-align:left;"> The Kobe Chouest platform supply vessel sits anchored next to the Chevron Jack/St. Malo deep water oil platform in the Gulf of Mexico.                      , Kevin Crowley                                                                                                                                               , Chevron Corp. raised its quarterly dividend 6% as the company attempts to share the benefits of rising oil prices with shareholders.                        , Chevron will pay $1.42 a share, up 8 cents from the previous payout, the California-based company said in a statement. The dividend is payable on March 10.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/qualtrics-reports-first-1-billion/story.aspx?guid={12898122-ECFE-4265-9E61-9554467C273C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-27 05:40:31 </td>
   <td style="text-align:left;"> Qualtrics reports first $1 billion fiscal year, driving up shares 10% - MarketWatch </td>
   <td style="text-align:left;"> Shares of Qualtrics International Inc. 
        XM,
        -1.22%
       spiked 10% in extended trading Wednesday after the experience-management technology company reported fiscal fourth-quarter results. Qualtrics reported a net loss of $309.8 million, or 56 cents a share, compared with a net loss of $14.5 million, or 3 cents a share, in the year-ago quarter. The company reported an adjusted net loss of $39.4 million, or 7 cents a share. Revenue soared 48% to $316 million from $213.6 million a year ago. For the fiscal year, Qualtrics topped $1 billion for the first time. "Every company is becoming a digital company seeking a deeper connection with customers and employees," Qualtrics Chief Executive Zig Serafin told MarketWatch. Analysts surveyed by FactSet had expected a net loss of 2 cents a share on revenue of $298 million. Qualtrics' stock has plunged 31.5% this year, while the broader S&amp;P 500 index 
        SPX,
        -0.15%
       has slid 9%., Tesla Inc.  reports quarterly earnings and sales above expectations, but says its factories have been running below capacity for several months thanks to supply-chain constraints.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/xlnx:us </td>
   <td style="text-align:left;"> 2022-01-27 05:33:32 </td>
   <td style="text-align:left;"> Xilinx earnings above expectations at 1.29 USD </td>
   <td style="text-align:left;"> Xilinx (XLNX) released earnings per share at 1.29 USD, compared to market expectations of 0.98 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/vrtx:us </td>
   <td style="text-align:left;"> 2022-01-27 05:32:25 </td>
   <td style="text-align:left;"> Vertex Pharmaceuticals earnings above expectations at 3.37 USD </td>
   <td style="text-align:left;"> Vertex Pharmaceuticals (VRTX) released earnings per share at 3.37 USD, compared to market expectations of 3.29 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ew:us </td>
   <td style="text-align:left;"> 2022-01-27 05:31:57 </td>
   <td style="text-align:left;"> Edwards Lifesciences earnings below expectations at 0.51 USD </td>
   <td style="text-align:left;"> Edwards Lifesciences (EW) released earnings per share at 0.51 USD, compared to market expectations of 0.55 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cci:us </td>
   <td style="text-align:left;"> 2022-01-27 05:31:43 </td>
   <td style="text-align:left;"> Crown Castle International earnings above expectations at 0.81 USD </td>
   <td style="text-align:left;"> Crown Castle International (CCI) released earnings per share at 0.81 USD, compared to market expectations of 0.77 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/lrcx:us </td>
   <td style="text-align:left;"> 2022-01-27 05:31:26 </td>
   <td style="text-align:left;"> Lam Research earnings above expectations at 8.53 USD </td>
   <td style="text-align:left;"> Lam Research (LRCX) released earnings per share at 8.53 USD, compared to market expectations of 8.51 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/now:us </td>
   <td style="text-align:left;"> 2022-01-27 05:31:08 </td>
   <td style="text-align:left;"> ServiceNow earnings above expectations at 1.46 USD </td>
   <td style="text-align:left;"> ServiceNow (NOW) released earnings per share at 1.46 USD, compared to market expectations of 1.43 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/tsla:us </td>
   <td style="text-align:left;"> 2022-01-27 05:30:16 </td>
   <td style="text-align:left;"> Tesla earnings above expectations at 2.54 USD </td>
   <td style="text-align:left;"> Tesla (TSLA) released earnings per share at 2.54 USD, compared to market expectations of 2.33 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-26/credit-risk-gauge-surges-to-14-month-high-on-powell-comments?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-27 05:28:27 </td>
   <td style="text-align:left;"> Credit Risk Gauge Surges to 14-Month High on Powell Comments </td>
   <td style="text-align:left;"> Jack Pitcher                                                                                                                                                                                                                                                                                                                                                                              , A measure of credit risk rose on Wednesday to the highest level since November 2020 after Federal Reserve Chairman Jerome Powell said the central bank was ready to raise interest rates in March and may continue to hike to tackle inflation.                                                                                                                                           , The cost of guaranteeing the debt of a basket of investment-grade companies against default jumped as much as 1.9 basis points to 60.9 basis points in the market for CDX.NA.IG credit derivatives. In the high yield market, a basket of junk credits saw its price decline to about 106.9 cents on the dollar, the lowest level since November 2020, according to the CDX.NA.HY index.   </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/intc:us </td>
   <td style="text-align:left;"> 2022-01-27 05:27:09 </td>
   <td style="text-align:left;"> Intel earnings above expectations at 1.09 USD </td>
   <td style="text-align:left;"> Intel (INTC) released earnings per share at 1.09 USD, compared to market expectations of 0.90 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/chile/interest-rate </td>
   <td style="text-align:left;"> 2022-01-27 05:26:52 </td>
   <td style="text-align:left;"> Chile Hikes Policy Interest Rate to 5.5% Above Expectations </td>
   <td style="text-align:left;"> Chile's central bank lifted its monetary policy interest rate by 150 bps to 5.5% during its January 2022 meeting, above market estimates of 5.25%. The decision was unanimous and follows two 125 bps increases and another 75 bps as the economy strongly rebounded from the Covid-19 pandemic and faces rising inflation. The inflation rate ended 2021 at 7.2%, above market expectations and the central bank’s target of 3%. Also, the core inflation rose 5.2% boosted by both an increase in goods and services prices. The future path of inflation continues to be surrounded by upside risks, while expectations for 2 years ahead remained above the 3% level. The board considered that the borrowing costs need to be above the neutral level in the short term, so the inflation should converge sustainably to the target of 3%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/elon-musk-tesla-earnings </td>
   <td style="text-align:left;"> 2022-01-27 05:07:11 </td>
   <td style="text-align:left;"> Tesla posts record profits, expects supply chain woes to persist </td>
   <td style="text-align:left;"> 'Mornings with Maria' panel discusses Fed policy and the SEC's call for transparency from private companies.                                                                                                                                                                                                                                                                              , Tesla hit new record annual and fourth-quarter profits Tuesday, in spite of supply chain challenges that the firm says it expects to continue throughout 2022.                                                                                                                                                                                                                            , SpaceX founder and Tesla CEO Elon Musk looks on as he visits the construction site of Tesla's gigafactory in Gruenheide, near Berlin, Germany, May 17, 2021. REUTERS/Michele Tantussi/File Photo (REUTERS/Michele Tantussi/File Photo / Reuters Photos)                                                                                                                                   , The Texas-based company headed by Elon Musk posted a record annual profit of $5.5 billion, up from the previous record of $3.47 billion in 2020, which was its first profitable year. It also had a record fourth-quarter profit of $2.32 billion in 2021 according to its earnings report, but still saw its stock take a downward turn after the closing bell before it made a recovery., TESLA OWNER MINES CRYPTO WITH CAR: IT'S ‘REALLY SIMPLE’                                                                                                                                                                                                                                                                                                                                   , In its outlook, Tesla reported that it plans to ramp up production capacity as quickly as possible but noted, "Our own factories have been running below capacity for several quarters as supply chains became the main limiting factor, which is likely to continue through 2022."                                                                                                       , The electric vehicle giant delivered more than 936,000 electric vehicles globally in 2021, up 87% from the year before.                                                                                                                                                                                                                                                                   , Musk was expected to give a product update during an investor call following the report, during which the CEO said the company was focused on ramping up production on current vehicle models right now and would not be introducing new ones this year.                                                                                                                                  , Tesla is on track to post its fastest annual production growth since 2018 despite parts shortages.  (Michael Reynolds/Shutterstock)                                                                                                                                                                                                                                                       , HOW ELON MUSK'S SOFTWARE FOCUS HELPED TESLA NAVIGATE CHIP SHORTAGE                                                                                                                                                                                                                                                                                                                        , After specifically being asked about whether progress was being made on the prospect of a $25,000 compact model Musk had teased in the past, he replied that Tesla was not working on such a vehicle currently and that the company "had enough on its plate" at the present.                                                                                                             , He also did not mention models that were listed on Tesla's Q4 financials as being "in development," including a Tesla Semi, Roadster, and a "Future Product." Musk said the firm was working on getting its Cybertruck, which is also in the development phase, to the point that it is affordable.                                                                                       , Musk did say that he expects in 2022 that Tesla's self-driving technology will get to the point that it is safer than a human operator, and said the company could possibly announce new factory locations by the end of the year.                                                                                                                                                        , Tesla holds AI Day and introduces Tesla Bot (Tesla)                                                                                                                                                                                                                                                                                                                                       , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                               , As for his vision for Tesla over the long haul, Musk said he sees the company's humanoid robot prototype, internally dubbed Optimus, eventually becoming more significant than its car business. Musk said the robots will first operate in Tesla factories, "doing things like moving parts around." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/politics/2022/01/26/breyer-retire-supreme-court-black-woman-nominee-biden-promise-nr-dovere-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-27 05:00:24 </td>
   <td style="text-align:left;"> This is why Biden vowed to nominate a Black woman to the Supreme Court - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/26/politics/january-6-judge-unconvinced-donald-trump-testify/index.html </td>
   <td style="text-align:left;"> 2022-01-27 04:43:08 </td>
   <td style="text-align:left;"> Judge casts doubt on January 6 defense strategy of calling Trump to the stand  - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)A federal judge appeared unconvinced on Wednesday that Donald Trump should be allowed to testify at a trial of a US Capitol riot defendant who is arguing the former President could be a helpful witness.                                                                                                                                                                                     , Judge Reggie Walton said that having Trump and his allies testify would not necessarily help Dustin Thompson's defense, which plans to argue that Trump and others goaded his supporters to storm the Capitol. Thompson is accused of entering the Capitol and stealing a coat rack.                                                                                                                 , "I just (didn't) see what more you get having them come into court to testify," Walton said during the hearing, pointing out the defense could play videos of what Trump and others said at a rally that preceded the attack.                                                                                                                                                                        , A Justice Department prosecutor agreed with Walton during the hearing.                                                                                                                                                                                                                                                                                                                               , Many of the defendants facing criminal charges for their role in the January 6 insurrection have tried to share blame with Trump or shift blame to him. While some federal judges have lambasted the former President, often not by name, and suggested he bears some responsibility for what happened that day, they also have said the defendants should be held responsible for their own actions., Yet now, judges must confront the possibility that defendants may try to use Trump's gravity -- and strong political condemnation of him in the nation's capital -- before juries.                                                                                                                                                                                                                   , Federal trials against alleged January 6 rioters are scheduled to begin at the end of next month.                                                                                                                                                                                                                                                                                                    , Thompson's attorney, Samuel Shamansky, previously asked Walton if the US Marshals Service could be used to deliver subpoenas to Trump and several others, including Rudy Giuliani, Steve Bannon and Sidney Powell. That opened up the conversation on Wednesday about Trump and his associates.                                                                                                      , Shamansky said he doesn't dispute what Thompson did that day but argued that "the question is how and why he gets there." He said that rioters were "whipped up into a frenzy" by Trump and his allies.                                                                                                                                                                                              , In another case headed to trial, the Justice Department has argued to block the possible defense that Trump gave permission for the attack on the Capitol.                                                                                                                                                                                                                                           , The judge in the case -- for riot defendant Aaron Mostofsky -- has not yet resolved whether it will be allowed.                                                                                                                                                                                                                                                                                      , A third judge in the court, Beryl Howell, has already rejected the legal argument that a defendant could have been entrapped into crime because of Trump's words on January 6, prosecutors have noted. The President doesn't have the power to allow crime and waive laws at will, Howell wrote nearly a year ago when she decided to keep in jail a January 6 defendant awaiting trial.             , Walton put it more bluntly on Wednesday.                                                                                                                                                                                                                                                                                                                                                             , "Just because the Pope says it," doesn't mean a Catholic can commit a crime, he said in court. "I'm not convinced."                                                                                                                                                                                                                                                                                  , Walton is set to issue a written order in response to Thompson's request in the coming days. His trial is set to begin in April.                                                                                                                                                                                                                                                                     , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60148208?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-27 04:34:05 </td>
   <td style="text-align:left;"> US Federal Reserve says rate rise 'appropriate' soon </td>
   <td style="text-align:left;"> The US central bank is poised to raise interest rates as it unwinds the support it has provided the world's largest economy since the start of the pandemic.                                                                                                                                              , The Federal Reserve did not raise interest rates on Wednesday, but said such a move "will soon be appropriate".                                                                                                                                                                                           , The bank is under pressure to rein in inflation as prices in the US rise at the fastest rate in almost 40 years.                                                                                                                                                                                          , Analysts expect a rate hike in March, which would be the first since 2018.                                                                                                                                                                                                                                , At a press conference following Wednesday's meeting of Fed officials, Federal Reserve chair Jerome Powell did not say how fast or how high US interest rates would rise.                                                                                                                                  , But Mr Powell said officials were "of a mind" to raise the bank's key rate in March, adding that he was confident the bank could take action without hurting the recovery.                                                                                                                                , He also suggested that officials are willing to move faster than they did the last time the Fed was raising rates, noting that the economy is "much stronger" than it was in 2015 - as is inflation.                                                                                                      , "We're well aware that this is a different economy than existed during the last tightening cycle," he said. "Our policy is going to reflect those differences."                                                                                                                                           , Higher borrowing costs help combat price rises by reducing demand for items such as cars and homes - key drivers of US inflation, which has persisted far longer than Fed officials initially expected.                                                                                                   , But the Fed risks chilling economic activity more than intended. Investors in the stock market are also worried about how share prices will respond to the Fed's moves, as higher interest rates make other investments more attractive.                                                                  , Jittery markets in the US have seen three consecutive weeks of declines.                                                                                                                                                                                                                                  , The three major US stock indexes pared gains during Mr Powell's remarks.                                                                                                                                                                                                                                  , Beth Ann Bovino, chief US economist at S&amp;P Global Ratings said, the Fed's statement confirmed that the bank will rise interest rates in March.                                                                                                                                                            , "It's not just a question of 'lift off' in interest rates, it's now more a question of how high they want to fly their monetary tool - how fast and how many they launch," she said. "Our reading of their statement suggests that the Fed is aiming for the stars in this cycle of monetary tightening." , Analysis: Michelle Fleury, BBC News North America business correspondent                                                                                                                                                                                                                                  , Having done his bit to support faltering growth during the pandemic, Jerome Powell, head of the Federal Reserve, began the arguably harder task: telegraphing to Main Street and Wall Street how the US central bank intends to tame inflation, currently at levels not seen since the 1980s.             , There are already grumblings that the Fed is behind the curve. That it should be acting faster to curb rising prices.                                                                                                                                                                                     , By signalling the bank's intention to raise interest rates gradually starting in March, the message from officials is that they don't see any urgency to play catch up.                                                                                                                                   , They are sticking to their guns: that higher prices will begin to fade later this year.                                                                                                                                                                                                                   ,  Still there are plenty who wonder whether waiting until March to raise rates is risking the Fed's credibility.                                                                                                                                                                                           , The Fed is not alone in its plans to raise interest rates from their current levels near zero. The Bank of England raised interest rates for the first time in more than three years in December and is expected to do so again in February.                                                              , Forecasters say the Fed could raise rates at least three times this year. The bank is also scaling back other programmes it put in place to support the economy at the start of the pandemic.                                                                                                             , It said it would end the pandemic-era bond purchases in March, as planned, and is moving forward with plans for "significantly reducing" the assets that it holds, which have ballooned since 2020.                                                                                                       , But Mr Powell said the bank would look to interest rates first, not shrinking its balance sheet, in its fight against inflation.                                                                                                                                                                          , Mr Powell said making policy required "humility" and pledged to be nimble in responding to economic conditions, noting uncertainty, including new virus variants and military tensions over Ukraine.                                                                                                      , "There's plenty of risk out there," he said.                                                                                                                                                                                                                                                              , Can they keep their progress hidden from their loved ones?                                                                                                                                                                                                                                                , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                                                                                                                          , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-01-27 04:05:25 </td>
   <td style="text-align:left;"> Dollar at One-Month High after Fed Decision </td>
   <td style="text-align:left;"> The dollar index extended gains to a one-month high of 96.4 on Wednesday after Fed Chair Powell said during the regular press conference after the FOMC decision that there is quite a bit of room to raise interest rates without dampening employment. In its first monetary policy decision this year, the Fed said it would be appropriate to raise borrowing costs soon to tame inflation amid a strong labor market, signalling a rate hike will happen next meeting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.marketwatch.com/story/fed-rate-hikes-are-coming-how-to-tackle-your-savings-mortgage-car-payments-and-credit-card-debt-in-advance-11643227349 </td>
   <td style="text-align:left;"> 2022-01-27 04:02:00 </td>
   <td style="text-align:left;"> Fed rate hikes are coming —  how to tackle your savings, mortgage, car payments and credit-card debt in advance - MarketWatch </td>
   <td style="text-align:left;"> Wall Street investors and Washington D.C. lawmakers are closely listening to what Federal Reserve Chairman Jerome Powell says Wednesday about the central bank’s next steps in its fight against decades-high inflation.                                                                                                                                           , “In light of the remarkable progress we’ve seen in the labor market and inflation that is well above our 2% longer run goal, the economy no longer needs sustained high levels of monetary-policy support,” Powell said.                                                                                                                                           , “I would say that the committee is of a mind to raise the federal funds rate at the March meeting, assuming that conditions are appropriate for doing so,” he added.                                                                                                                                                                                               , About that volatility: Investors are, among other things, rattled by an expected increase for the critically influential federal funds rate is widely anticipated to happen in March, ushering in a series of potential rate hikes through 2022.                                                                                                                   , When Federal Open Market Committee (FOMC) increases rates, borrowing costs increase throughout the economy — and come back to haunt consumers who need to factor those higher borrowing costs in their financial decisions.                                                                                                                                        , 
        “As Jerome Powell charts a course for rate hikes, Americans will need to plan the next steps for their finances in the coming months.”
                                                                                                                                                                                                                 , “With inflation well above 2% and a strong labor market, the FOMC expects it will soon be appropriate to raise the target range for the federal funds rate,” the Fed said in its policy statement released Wednesday afternoon.                                                                                                                                    , It did not commit to a rate hike at its meeting scheduled for mid-March.                                                                                                                                                                                                                                                                                           , The federal funds rate is the interest rate that banks charge each other for short, overnight loans and use as a baseline for other lending rates. The rate is now essentially 0%, a basement level that was initially meant to aid the economy in the pandemic’s earlier phase of lockdowns and sky-high unemployment rates.                                      , The Fed has good reason to mull a rate hike: Jobless rates are far lower, lockdowns are gone and price inflation gnaws household budgets. The pace of inflation in December hit 7%, a nearly 40-year high.                                                                                                                                                         , As Powell charts a course for rate hikes during this recovering economy, here’s how people can plan their own next financial steps for the coming months:                                                                                                                                                                                                          , Anyone who’s been in the market for a mortgage — either to buy a home or to refinance their loan — has no doubt born witness to the stunning rise in interest rates for these products.                                                                                                                                                                            , As of Thursday, mortgage rates were at a pandemic-era high, with the benchmark rate for the 30-year fixed-rate mortgage averaging 3.56%. In the span of four weeks, the rate on the 30-year loan has risen more than 50 basis points, or half a percent.                                                                                                           , Here’s the good news: The Fed’s upcoming rate hike has already been baked into mortgage rates — the Fed manipulates short-term interest rates, while mortgage rates are long term. Consequently, expectations of the Fed’s actions are already being factored into the rates lenders offer applicants.                                                             , Plus, the Federal Reserve has reduced the amount of mortgage-backed securities it is purchasing, while has reduced liquidity in the mortgage market. That, too, may be having an effect on interest rates.                                                                                                                                                         , 
        “In the span of four weeks, the rate on the 30-year loan has risen to 3.56%, or more than 50 basis points.”
                                                                                                                                                                                                                                            , Another positive: It’s getting easier to qualify for a mortgage in one sense. As rates rise, refinance volumes dwindle. It’s easier for lenders to attract refinancing customer, but they have to compete more for home buyers.                                                                                                                                    , “Lenders are thirsty for volume as refinancing traffic wanes and the investors that buy mortgage debt are still very much in a ‘risk-on’ mode,” Greg McBride, chief financial analyst at Bankrate, told MarketWatch in December. “Until either of those changes, there isn’t an obvious catalyst for a tightening of mortgage credit.”                             , At the same time, higher rates could make it harder for some buyers to qualify, since it’s a more onerous financial commitment.                                                                                                                                                                                                                                    , Economists expect that the rise in mortgage rates in recent weeks has already triggered an unseasonable rush to purchase homes well ahead of the typical peak spring home-buying season. These buyers are aiming to lock in cheap financing while they still can. Real-estate experts believe that mortgage rates will continue to rise throughout the year.       , Any home buyer looking to join that rush should be mindful of their timing. Mortgage pre-approvals typically last for 90 days, but some lenders offer shorter windows, according to Bankrate. Mortgage rate locks, meanwhile, are generally good for 15 to 60 days, according to Rocket Mortgage.                                                                  , In both cases, you can typically ask your lender for an extension, though sometimes that will involve another credit check or an additional fee.                                                                                                                                                                                                                   , The spring home-buying season is just around the corner, and that will be a time when more properties will come to market. Nevertheless, today’s buyers should be prepared for a tough market. The inventory of homes for sale hovers around record lows, meaning the properties that are on the market will likely fetch multiple offers and attract bidding wars., Chances are many buyers won’t succeed on their first bid, so it’s important to keep that in mind when seeking pre-approval. If a family isn’t ready to close a deal quickly, they may be shooting themselves in the foot by getting pre-approved prematurely.                                                                                                      , Some blunt advice: Pay off as much as possible before rate hikes push up credit card’s APR (annual percentage rate), experts say.                                                                                                                                                                                                                                  , Lenders come up with their APRs by factoring in the so-called “prime rate” — which is closely tied to the Fed’s rate — with other components like credit scores and a person’s risk of defaulting.                                                                                                                                                                 , When the Fed’s rate goes up, APRs closely follow and the cost of carrying a balance goes up, Matt Schulz, LendingTree’s chief credit analyst, previously said. After a rate increase, it can take up to two months for APRs to increase, he said. The average APR is now 19.55%, unchanged from December, according to LendingTree.                                , “If you have a credit card and you are carrying month to month, interest rates should be of some importance to you,” said Bruce McClary, spokesman for the National Foundation for Credit Counseling.                                                                                                                                                              , 
        “‘If you have a credit card and you are carrying month to month, interest rates should be of some importance to you.’”
                                                                                                                                                                                                                                 , That’s a large number of people, because 38% of consumers are carrying some sort of credit-card debt month to month, according to the organization’s recent survey. That’s down from 43% in 2020.                                                                                                                                                                  , However, McClary noted roughly 30% are spending more than a year ago and approximately one-fifth say they are saving less. “A lot of people are living close to the edge” and even a small APR increase may have an outsized impact, he said.                                                                                                                      , When paying off a balance is not possible, McClary said there are other things people can do. One idea is looking now for a new credit card where people can make a balance transfer for a lower rate and fees. APRs on 0% balance-transfer cards now stand at 18.09%, LendingTree date showed.                                                                    , Another often overlooked idea is negotiating with the credit-card lender to get a lower APR, or find another card from the issuer that offers lower rates, McClary said.                                                                                                                                                                                           , These strategies are best for people with good credit scores, McClary noted. But the scores for many people have climbed during the pandemic and they might not even realize it, he said.                                                                                                                                                                          , To begin with, cars aren’t much of a bargain these days — thanks to the ongoing chip shortage which is limiting supply of both new and used cars.                                                                                                                                                                                                                  , Over the past year, prices for used cars and trucks have jumped by 37%. While prices for new vehicles increased nearly 12% over the past year, according to the December Consumer Price Index.                                                                                                                                                                     , If you’re looking to take out an auto loan to finance your new car, you don’t need to rush to seal the deal to save money before the Fed’s rate hike goes into effect, said McBride at Bankrate.com.                                                                                                                                                               , 
        “‘The difference of one-quarter percentage point amounts to a difference of $3 per month for a car buyer borrowing $25,000.’”
                                                                                                                                                                                                                          , “A rise in interest rates has a minimal impact on auto loan rate affordability,” he told MarketWatch. “The difference of one-quarter percentage point amounts to a difference of $3 per month for a car buyer borrowing $25,000.”                                                                                                                                  , The interest rate on your car payment is more sensitive to factors such as your credit score, credit history, and debt-to-income ratio “than a marginal increase in the federal funds rate,” said Shannon Bradley, an auto loans expert at NerdWallet 
        NRDS,
        +0.51%.
                                                                           , If you put off purchasing a car right now, you’re probably going to pay a higher interest rate on an auto loan but you “may also be in a position to buy at a better price,” Bradley said. But that depends on whether the supply of cars recovers, or not.                                                                                                        , Savings accounts and certificates of deposit are not the place to make eye-popping returns on investment, but they can be a conservative way to bring in a little bit extra while still maintaining a rainy day fund.                                                                                                                                              , Because the annual percentage yields (APY) for these accounts closely hinge on the Fed rate, upcoming rate hikes will make those returns slightly more generous, said Ken Tumin, founder and editor of DepositAccounts.com.                                                                                                                                        , That’s especially true for the savings accounts and CDs offered by online banks instead of legacy, brick and mortar banks,Tumin said.                                                                                                                                                                                                                              , For example, the average savings account rate for all banks is 0.06% in January, but for online banks, the average rate is 0.46%, Tumin said. Brick and mortar banks are “flush with deposits,” so they have less incentive to quickly bump up rates in a race for accounts, Tumin said.                                                                           , It could take years and multiple rate hikes for brick and mortar banks to increase the average rate to 0.09%, Tumin said. But if history is any guide, the rates at online banks will closely match the federal funds rate, and at a much quicker pace.                                                                                                            , In December 2018, the target rate for the federal funds rate was 2.25%-2.25%, he noted. At that time, online savings accounts offered an average 2.23% APY, he said. It was an average 2.72% for a one-year CD from an online bank, he said.                                                                                                                       , The rates for CDs have been rising and Tumin says the upward trend will continue. The APY on all one-year CDs is now 0.13% and it’s 0.51% for online banks.                                                                                                                                                                                                        , Keep in mind CDs have lockup periods and penalties on early withdrawals. When it comes to financial strategies in the current environment, CDs are “not replacing stocks and bonds,” Tumin said. “I see it supplementing a savings account.”                                                                                                                       , In the meantime, Powell said there’s a long way for the pandemic-era recovery to go. “The economic outlook remains highly uncertain,” he said Wednesday. “Making appropriate monetary policy in this environment requires humility, recognizing [that] the economy evolves in unexpected ways.”                                                                    , 'He only lived in the house for the first four years.'                                                                                                                                                                                                                                                                                                             , Jacob Passy is a personal-finance reporter for MarketWatch and is based in New York.                                                                                                                                                                                                                                                                               , Elisabeth Buchwald is a personal finance reporter at MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 04:01:00 </td>
   <td style="text-align:left;"> Wall Street Gives Up Gains After Powell Remarks </td>
   <td style="text-align:left;"> US stocks trimmed gains on Wednesday after Powell mentioned that there is plenty of room to raise interest rates before harming the economy. Earlier, as expected, the Fed announced it could soon hike the rates for the first time in more than three years and will continue to reduce its ultra-easy pandemic support. The Dow Jones closed down almost 130 points after adding more than 400 points earlier in the session, the S&amp;P 500 shed almost 0.3%, and the Nasdaq Composite was little changed after surging more than 3.3%. On the corporate front, bank stocks were boosted by higher yields, with Morgan Stanley and JP Morgan up around 1%. Meanwhile, Microsoft rose 2.3% after the company's earnings, revenues, and sales forecasts topped estimates. Results from AT&amp;T and Abbott also beat on the upside but stocks failed to rise and Boeing shares declined more than 5% after the company reported a much bigger-than-expected loss of $7.69 per share for the fourth quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/26/heres-why-new-parents-may-qualify-for-another-1400-stimulus-check.html </td>
   <td style="text-align:left;"> 2022-01-27 03:57:42 </td>
   <td style="text-align:left;"> Here's why new parents may qualify for another $1,400 stimulus check </td>
   <td style="text-align:left;"> , The IRS has issued all third-round stimulus payments to eligible Americans, the agency said Wednesday. However, new parents and other recipients who added dependents in 2021 may still qualify for additional money.                                                                               , The payments, up to $1,400 a person, were authorized by the American Rescue Plan Act, a pandemic-relief bill Democrats passed in March.                                                                                                                                                             , The IRS also issued two other Economic Impact Payments (of up to $1,200 and $600) that were authorized by earlier, bipartisan relief packages.                                                                                                                                                      , Eligibility and total funds received by households were based on income and other requirements.                                                                                                                                                                                                     , Some $1,400 payments may still be in the mail, but the IRS is no longer issuing funds from the first, second or third rounds, the agency said. The IRS issued more than 175 million third-round payments to households worth over $400 billion through Dec. 31.                                     , Some households will qualify for additional third-round funds when they file their 2021 income tax return this year, however. This is true for those whose circumstances changed in 2021 relative to 2020.                                                                                          , For example, children born in 2021 qualify for an additional payment of up to $1,400, which parents didn't receive last year.                                                                                                                                                                       , Families who added a dependent (like a parent, nephew, niece or grandchild) on their 2021 tax return and who was not listed as a dependent on their 2020 return may also qualify, the IRS said.                                                                                                     , Most other eligible people already received the full third-round amount and won't qualify for more, the agency said.                                                                                                                                                                                , More from Invest in You:Here's how to invest like billionaire Warren Buffett during a volatile marketOne-third of Americans admit that they financially cheat on a partnerThe ultimate retirement planning guide for 2022                                                                           , Families can recover additional stimulus payments on their tax return by claiming the 2021 Recovery Rebate Credit. (Stimulus checks are technically an advanced payment of the Recovery Rebate Credit.)                                                                                             , The tax season started Monday and runs through April 18 for most people.                                                                                                                                                                                                                            , To claim the 2021 Recovery Rebate Credit, individuals must know how much money they received in total third-round stimulus payments.                                                                                                                                                                , That information is available through their online IRS account or via Letter 6475, which the agency is mailing through March to those who were issued third-round payments. (Married individuals filing a joint tax return will need to determine their individual information and add it together.), The IRS is urging taxpayers to file an accurate, electronic return to speed up processing and get a faster refund. Errors or incomplete returns require further review, which might cause delays, the agency warned.                                                                                , SIGN UP: Money 101 is an 8-week learning course to financial freedom, delivered weekly to your inbox. For the Spanish version Dinero 101, click here.                                                                                                                                               , CHECK OUT: The 'old convention' for saving in retirement won't work anymore, expert says: Here's how to shift your strategy with Acorns+CNBC                                                                                                                                                        , Disclosure: NBCUniversal and Comcast Ventures are investors in Acorns.                                                                                                                                                                                                                              , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                              , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                              , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                    , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                    , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                  , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-27 03:53:29 </td>
   <td style="text-align:left;"> Canada 10Y Bond Yield Rebounds After Central Banks Decisions </td>
   <td style="text-align:left;"> The yield on the Canadian 10-year government bond crossed above 1.80% again at the end of January, not far from a near 3-year high of 1.89% hit on January 18th, tracking higher US Treasury yields after the Fed decision came as expected. The Fed announced it could soon hike the rates for the first time in more than three years and will continue to reduce its ultra-easy pandemic support. Meanwhile, the BoC dashed some investors after leaving the interest rate steady in its first 2022 meeting. The central bank, however, signaled a rise in interest rates will happen soon, probably during the next meeting on March 2nd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-27 03:48:00 </td>
   <td style="text-align:left;"> UK 10Y Bond Yield Rebounds to 1.2% </td>
   <td style="text-align:left;"> The yield on the UK 10-year government bond rose back to 1.2%, moving closer to a near three-year high of 1.3% hit earlier this month, amid prospects of faster monetary policy tightening due to stubbornly high inflation. The Bank of England will likely be raising interest rates again next week, a move that is expected to be followed by multiple rate hikes this year, as Britain's consumer price inflation hit a near 30-year high against a backdrop of solid economic growth and strong jobs data. Also, the US Federal Reserve signaled at its January meeting it would start raising rates as early as March. Elsewhere, British Prime Minister Boris Johnson is braced for the publication of an official investigation into Downing Street parties during lockdowns. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/currency </td>
   <td style="text-align:left;"> 2022-01-27 03:43:58 </td>
   <td style="text-align:left;"> Kiwi Dollar Remains Under Pressure </td>
   <td style="text-align:left;"> The New Zealand dollar hovered 14-month lows past $0.67 on Wednesday, as risk currencies remained under pressure from geopolitical risks while the US dollar continued to strength after the Federal Reserve signalled interest rates will soon start to increase. Meanwhile, the Reserve Bank of New Zealand has already hiked interest rates twice to 0.75% last year and is widely expected to move it to 1.0% at its February meeting amid persistent inflation and record low unemployment. Investors also await Q4 inflation data in New Zealand due for release on Thursday, which is expected to accelerate at its fastest pace since 1990 at 5.7%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-27 03:43:29 </td>
   <td style="text-align:left;"> Australia 10Y Bond Yield Hits 12-week High </td>
   <td style="text-align:left;"> Australia 10 Year Government Bond Yeld increased to a 12-week high of 2.018% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-prices-settle-fresh/story.aspx?guid={01AD58B2-0E24-4E99-8AEC-03EB64144590}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-27 03:41:41 </td>
   <td style="text-align:left;"> U.S. oil prices settle at a fresh multiyear high  - MarketWatch </td>
   <td style="text-align:left;"> Oil futures climbed on Wednesday, with growing concerns over the Russia-Ukraine situation prompting U.S. benchmark prices to settle at their highest since October 2014. "The market remains extremely tight and geopolitical concerns -- namely the standoff between the West and Russia over Ukraine - will be the real drivers of markets in the short term," said Matthew Sherwood, global economist at the Economist Intelligence Unit. March West Texas Intermediate crude 
        CLH22,
        -0.13%
       rose $1.75, or 2%, to settle at $87.35 a barrel on the New York Mercantile Exchange. , Tesla's earnings-per-share beat for the fourth quarter is about 8%, which is solid, but below the average of 25%. It might not be enough to counter recent market turmoil.                                                                                                                                                                                                                                                                                                                                                                                                                                     , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/silver </td>
   <td style="text-align:left;"> 2022-01-27 03:41:00 </td>
   <td style="text-align:left;"> Silver Remains Subdued After Powell Remarks </td>
   <td style="text-align:left;"> Silver traded around $23.6 per troy ounce at the end of January, the lowest since January 18th, amid a stronger dollar after Fed Chair Powell said during the regular press conference after the FOMC decision that there is quite a bit of room to raise interest rates without dampening employment. The metal has been recently driven by a combination of profit-taking after reaching recent highs and concerns on the next steps of the US central bank as rates hikes raise the opportunity cost of holding the bullion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/currency </td>
   <td style="text-align:left;"> 2022-01-27 03:37:29 </td>
   <td style="text-align:left;"> Aussie Falls Below $0.715 after FOMC Statement </td>
   <td style="text-align:left;"> The Australian dollar extended losses to $0.715 on Wednesday, amid a general dollar strength after the Federal Reserve signalled a rate hike will be appropriate in March. The Aussie also struggled to build momentum despite higher-than-expected inflation data released a day before. Investors weighed the prospects of earlier rate hikes in Australia after the country’s core inflation accelerated to 2.6% in the fourth quarter of 2021, faster than the 2.3% forecast and registering in the middle of the Reserve Bank of Australia’s 2-3% target range. The latest inflation figures posed a challenge to the RBA as it has repeatedly insisted that a hike in domestic rates is not likely until 2023, or until inflation pushes sustainably within its 2-3% target range. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/currency </td>
   <td style="text-align:left;"> 2022-01-27 03:37:00 </td>
   <td style="text-align:left;"> Sterling Weakens to 4-Week Low </td>
   <td style="text-align:left;"> The British pound depreciated below $1.35 during the fourth week of January, hovering around its weakest level since the end of December, as investors turned to the US dollar after the Federal Reserve announced a March interest-rate hike to combat inflation. At the same time, geopolitical tensions between Western leaders and Russia over Ukraine continued to weigh on sentiment, as well as rising political uncertainty in the UK as Prime Minister Boris Johnson faces a crunch week for his leadership as he braces for the outcome of an investigation into Downing Street parties during the 2020 lockdowns. Elsewhere, markets see a high chance that the Bank of England will be raising rates again in February, after data showed last week the UK consumer inflation rose more than expected to 5.4% in December, its highest since March 1992, and the core index, which excludes volatile items, rose by a record 4.2%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-27 03:35:48 </td>
   <td style="text-align:left;"> Crude Oil is up by 2.01% </td>
   <td style="text-align:left;"> Crude Oil WTI increased 2.01% to 87.31 USD/Bbl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-01-27 03:34:12 </td>
   <td style="text-align:left;"> Brazilian Real at Over 2-Month High </td>
   <td style="text-align:left;"> The Brazilian Real traded around 5.40, the highest since November 11th, amid hotter-than-expected inflation data outweighing a stronger dollar. The dollar index traded above 96.1, near a three-week high, after the Fed decision came as expected. The Fed announced it could soon hike the rates for the first time in more than three years and will continue to reduce its ultra-easy pandemic support. Domestically, mid-month consumer price data showed that inflation rose 10.2% YoY, above market expectations, but easing from a 10.42% increase in the previous period. Still, inflation remained well above the central bank’s target of 3.5% strengthening the case for the central bank to keep its monetary policy tightening stance. Since the Brazilian central bank started to hike, it has raised the borrowing costs by 725 bps and is expected to deliver at least one more hike of 150 bps during its next monetary policy meeting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/currency </td>
   <td style="text-align:left;"> 2022-01-27 03:31:24 </td>
   <td style="text-align:left;"> Mexican Peso at Near 4-Week Low </td>
   <td style="text-align:left;"> The Mexican peso traded around 2.6 per USD, the lowest since December 28th, amid a stronger dollar after the Fed decision came as expected. The Fed announced it could soon hike the rates for the first time in more than three years and will continue to reduce its ultra-easy pandemic support. Meanwhile, domestically, preliminary data showed that the economy likely contracted 0.2% in December, suggesting a sluggish performance in the final quarter of last year. At the same time, JP Morgan said in a recent report, the Mexican economy is facing a potential credit rating downgrade in the medium term due to political developments, including the likely passage of a controversial energy bill. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/rivian-stock-jumps-after-report/story.aspx?guid={C0F3AFF4-72E9-49EC-B358-2C470CBFC4A4}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-27 03:30:49 </td>
   <td style="text-align:left;"> Rivian stock jumps after report saying factory is ramping production - MarketWatch </td>
   <td style="text-align:left;"> Shares of Rivian Automotive Inc. 
        RIVN,
        +1.11%
       rose more than 8% Wednesday, poised to end at their highest since Dec. 27. Bloomberg earlier Wednesday reported that Rivian is picking up the pace at its Normal, Ill., plant following a week-long production halt earlier this month. According to report, which cited people familiar with the issue, Rivian is working toward having almost 200 delivery-ready units a week after going through the production snags. Rivian stock is off 38% this month, compared with losses of around 7% for the S&amp;P 500 index. 
        SPX,
        -0.15%
       Rivian priced its upsized initial public offering in November at $78 a share, and the stock is off about 19% from the IPO price. , Tesla's earnings-per-share beat for the fourth quarter is about 8%, which is solid, but below the average of 25%. It might not be enough to counter recent market turmoil.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2022-01-27 03:30:00 </td>
   <td style="text-align:left;"> Euro Depreciates to 1-Month Low </td>
   <td style="text-align:left;"> The euro weakened further below $1.13 during the fourth week of January, hovering around its lowest level in one month, as investors turned to the US dollar after Fed officials signaled they would raise borrowing costs in March, their first interest-rate hike since 2018, to combat inflation. At the same time, the single currency was under pressure amid worries about a potential military conflict in Ukraine and as PMI data pointed to a sharp slowdown in the Eurozone's business activity growth. Elsewhere, the European Central Bank, is seen slower than other major central banks in tightening monetary policy, with markets pricing in a 10 basis-point rate hike from the ECB in September and betting on a second rate hike by December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/currency </td>
   <td style="text-align:left;"> 2022-01-27 03:29:00 </td>
   <td style="text-align:left;"> Yen Weakens as Fed Tightening Supports the Dollar </td>
   <td style="text-align:left;"> The Japanese yen inched lower toward 114 per dollar on Wednesday after hitting a 5-week high of 113.47 early in the week, amid a broad USD strength after the Federal Reserve signalled a rate hike will be appropriate in March, in line with market forecasts. Still, the yen remains supported by heightened geopolitical tensions between NATO and Russia over Ukraine. Meanwhile, the Bank of Japan is in no rush to change its ultra-loose monetary policy but flagged broadening inflationary pressures in its latest quarterly outlook report, projecting core consumer prices to hit 1.1% for the fiscal year to March 2023 and warned that inflation may accelerate faster than expected if raw materials costs continue to spike. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-01-27 03:28:50 </td>
   <td style="text-align:left;"> Canadian Dollar Rebounds From Near 2-Week Low </td>
   <td style="text-align:left;"> The Canadian dollar traded around 1.26 per USD, after hitting a near 2-week low of 1.263 on January 24th, as the Fed’s decision came as expected with the monetary authority announcing it could soon hike the rates for the first time in more than three years and will continue to reduce its ultra-easy pandemic support. Meanwhile, the BoC dashed some investors after leaving the interest rate steady in its first 2022 meeting. The central bank, however, signaled a rise in interest rates will happen soon, probably during the next meeting on March 2nd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-settles-lower-little-changed/story.aspx?guid={7A7DA77B-64A7-449A-BB9A-09904643A69D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-27 03:20:01 </td>
   <td style="text-align:left;"> Gold settles lower, little changed after Fed statement - MarketWatch </td>
   <td style="text-align:left;"> Gold futures settled lower on Wednesday, then traded little changed in electronic trading after Federal Reserve officials said they expect it "will soon be appropriate to raise" interest rates. Worries about the effects rising interest rates could have on nonyielding bullion have been among the key bearish near-term drivers for gold. February gold 
        GCG22,
        -0.61%
       was at $1,830.70 an ounce in electronic trading, following a settlement at $1,829.70, down $22.80, or 1.2%, for Wednesday's session, the lowest finish since Jan. 18, FactSet data show. Prices had settled Tuesday at their highest since Nov. 18., Some Canadian retailers are now requiring proof of vaccination due to local regulations, resulting in some critics calling to boycott Walmart in response                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-01-27 03:14:00 </td>
   <td style="text-align:left;"> Gold Remains Subdued After Powell Remarks </td>
   <td style="text-align:left;"> Gold prices traded below $1,820 an ounce on Wednesday, the lowest since January 18th, amid a stronger dollar after after Fed Chair Powell said during the regular press conference after the FOMC decision that there is quite a bit of room to raise interest rates without dampening employment. The yellow metal has been recently driven by a combination of profit-taking after reaching recent highs and concerns on the next steps of the US central bank as rates hikes raise the opportunity cost of holding the bullion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-27 03:10:00 </td>
   <td style="text-align:left;"> US 10-Year Bond Yield Rises Above 1.8% </td>
   <td style="text-align:left;"> The yield on the benchmark 10-year Treasury note extended gains above 1.8%, moving further away from the two-week lows touched earlier this week, after Federal Reserve Chairman Jerome Powell suggested there was plenty of room to raise borrowing costs before it would harm the US economy. The Fed left monetary policy unchanged on Wednesday, but signaled that a rate hike may be coming in March as inflation remains well above the 2% target against a backdrop of strong labor market. In addition, policymakers reaffirmed plans to end the central bank's massive bond buying program that month, and agreed on a set of principles for "significantly reducing" the size of its asset holdings after the liftoff in interest rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 03:07:00 </td>
   <td style="text-align:left;"> Wall Street Accelerates Gains After Fed Decision </td>
   <td style="text-align:left;"> US stocks extended gains on Wednesday after the Fed announced it could soon hike the rates for the first time in more than three years and will continue to reduce its ultra-easy pandemic support. The Dow Jones added more than 400 points, the S&amp;P 500 rose almost 2.1%, and the Nasdaq Composite soared nearly 3.4%. Earlier, Microsoft was among the top gainers rising 5% after the company's earnings, revenues, and sales forecasts topped estimates. Results from AT&amp;T and Abbott also beat on the upside but stocks failed to rise and Boeing shares declined almost 3% after the company reported a much bigger-than-expected loss of $7.69 per share for the fourth quarter. Tesla and Intel are due to report quarterly results after markets close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/republicans-slam-pelosi-china-bill-proposal </td>
   <td style="text-align:left;"> 2022-01-27 03:06:22 </td>
   <td style="text-align:left;"> Republicans slam Pelosi over China bill proposal: 'Not serious about confronting the CCP' </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                            , Top Republicans in the House are taking issue with a bill introduced in the lower chamber that aims to curb competition with China and accused Democrats of not being "serious about confronting the [Chinese Communist Party]."                                                             , The bill, known as the America COMPETES Act of 2022, was unveiled in the House Tuesday by Democratic leaders in an attempt to bolster U.S. semiconductor production, address supply chain issues and invest in scientific and technological advancements.                                    , Speaker of the House Nancy Pelosi, D-Calif., meets with reporters at U.S. Capitol.  (AP Photo/J. Scott Applewhite / AP Newsroom)                                                                                                                                                             , SENATORS PUSH BIPARTISAN BILL TO BOLSTER DOMESTIC SEMICONDUCTOR PRODUCTION AS SHORTAGES LOOM                                                                                                                                                                                                 , But what Democrats and the White House have championed as a bipartisan bill in response to the Senate-passed $250 billion U.S. Innovation and Competition Act (USICA), House Republicans have claimed is a stockpile of partisan issues.                                                     , "We have been in talks with House and Senate committees of jurisdiction for weeks, trying to put together a bipartisan bill that could pass Congress," Ranking Member of the Foreign Affairs Committee Rep. Michael McCaul, R-Texas, told Fox News Digital.                                  , "I would strongly urge Speaker Pelosi and other House Democrats to scrap their weak, partisan bill and work with Republicans on comprehensive legislation that will actually counter CCP aggression and that has the ability to pass both Houses of Congress."                               , McCaul warned that the COMPETES Act could be dead on arrival in the Senate, even if it clears the Democratic-led House, so long as it contains partisan-heavy legislation like the EAGLE Act.                                                                                                , SEMICONDUCTORS 101: COMPUTER CHIPS SHORTAGES LEAD TO NATIONAL SECURITY CONCERNS                                                                                                                                                                                                              , Rep. Mike McCaul, R-Texas, talks about China during a news conference with House Republicans. (Chip Somodevilla/Getty Images / Getty Images)                                                                                                                                                 , The House bill substantially cut funding allocated in the Senate USICA bill by dropping the $190 billion allocated for technology and research, as first reported Reuters. The bill instead includes $45 billion to bolster supply chains and the domestic production of critical goods.     , The 2,900-page House bill does still include $52 billion to fund the manufacturing of U.S. semiconductors.                                                                                                                                                                                   , Despite the drop in price, Ranking Member Rep. Cathy McMorris Rodgers of the Energy and Commerce Committee has rejected the idea that additional funding will solve the U.S.'s supply chain issues.                                                                                          , A staffer for McMorris Rodgers told Fox News Digital that the bill "will not solve this supply chain crisis or secure America’s competitive edge against China."                                                                                                                             , "We cannot beat China at their own game with expansive government subsidies," they added.                                                                                                                                                                                                    , A technician holds a central processor microchip known as a semiconductor over a circuit board at Bonn Proton Ltd. (Photo illustration by Ulrich Baumgarten via Getty Images / Getty Images)                                                                                                 ,  CLICK HERE TO GET THE FOX NEWS APP                                                                                                                                                                                                                                                          , "Approaches like USICA or the America COMPETES Act — both massive expansions of government subsidies and federal control — are not how we beat China," McMorris Rodgers said in a statement Wednesday.                                                                                       , "From what I’ve seen so far in Speaker Pelosi’s bill, it’s another attempt to outspend the CCP with duplicative, multibillion-dollar command and control programs that will diminish our global competitiveness, fail to solve the supply chain crisis and make inflation worse," she added. , Minority Leader Kevin McCarthy echoed these sentiments by calling the legislation "toothless" and claimed it would waste "billions of dollars on unrelated matters."                                                                                                                         , "The COMPETES Act isn’t serious legislation – it is a façade to cover up the Democrats’ reluctance to actually do anything to hold China accountable and their desperation to do something to distract from their domestic crises," he added. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-01-27 03:06:00 </td>
   <td style="text-align:left;"> Dollar at 3-Week High as Fed Hints at March Rate Hike </td>
   <td style="text-align:left;"> The dollar index held above 96 against a basket of currencies, having touched a three-week high of 96.2, after the Federal Reserve left monetary policy unchanged, but said it would be appropriate to raise borrowing costs soon to tame inflation amid a strong labor market. The central bank also said it would be ending its bond purchases that month as well as start reducing its asset holdings significantly after the liftoff in interest rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/26/federal-reserve-statement-january-2022-heres-what-changed.html </td>
   <td style="text-align:left;"> 2022-01-27 03:05:49 </td>
   <td style="text-align:left;"> Here's what changed in the new Fed statement </td>
   <td style="text-align:left;"> , This is a comparison of Wednesday's Federal Open Market Committee statement with the one issued after the Fed's previous policymaking meeting on Dec. 15., Text removed from the December statement is in red with a horizontal line through the middle.                                                            , Text appearing for the first time in the new statement is in red and underlined.                                                                         , Black text appears in both statements.                                                                                                                   , Got a confidential news tip? We want to hear from you.                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/26/diversity-among-financial-planners-improved-in-2021-but-it-still-lags.html </td>
   <td style="text-align:left;"> 2022-01-27 03:04:04 </td>
   <td style="text-align:left;"> Diversity among financial planners improved in 2021 — but it still remains overwhelmingly white and male </td>
   <td style="text-align:left;"> , Diversity among financial planners improved in 2021 though the industry remains one that leans heavily toward white men, according to statistics issued Wednesday by the Certified Financial Planner Board of Standards.                                                                                                     , The group, which issues the certified financial planner designation, saw a pronounced uptick in female, Black and Hispanic practitioners last year. The number of Black financial planners grew by more than 10% from 2020; the growth rate was 15% for Hispanic CFPs and 4.2% for women.                                    , More from Personal Finance:Watchdog signals broad crackdown on hidden fees at banksMillions still waiting on last year's tax refundSEC chair eyes tougher cyber rules to protect against hacks                                                                                                                               , All exceeded the growth rate of CFPs overall, which hit an all-time high of 92,055, an increase of 3.8% from 2020.                                                                                                                                                                                                           , "2021 is the largest and most diverse class in the CFP Board's history," according to Kamila Elliott, chair of the group's board of directors.                                                                                                                                                                               , Despite last year's improvements, officials recognize that the current metrics still fall short.                                                                                                                                                                                                                             , There were 76,435 white financial planners in 2021, about 83% of the total — dwarfing the other racial and ethnic groups.                                                                                                                                                                                                    , About 4%, or just over 3,600, of CFPs are Asian or Pacific Islanders; almost 3% (about 2,500) are Hispanic or Latino, and over 1,600 (nearly 2%) are Black or African American.                                                                                                                                              , By comparison, the U.S. population is about 76% white, 19% Hispanic or Latino, 13% Black or African American, and 6% Asian, according to Census Bureau data.                                                                                                                                                                 , Meanwhile, almost 77% of CFPs are male and 23% are female, according to the CFP Board. (Females make up about 51% of the overall U.S. population.)                                                                                                                                                                           , "Our goal is that the number of CFP professionals represent the demographics of the U.S.," said Elliott, who in 2022 became the first African American to serve as the CFP Board's chair. "I'd love a day when we see 13% of CFP professionals be Black, and 19% be Hispanic."                                               , Diversity among financial planners isn't just important for the industry, but also for the broader American population — it may encourage more minority households to seek financial advice if that advice is more readily available from someone who looks like them, Elliott said.                                         , The CFP Board has tried raising awareness and availability of the financial-planning profession, via scholarships for preparation courses for individuals taking the CFP exam, as well as encouraging mentorship and internship programs among advisors, and hosting an annual diversity summit, for example, officials said., Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                       , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                       , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                             , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                             , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                           , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/interest-rate </td>
   <td style="text-align:left;"> 2022-01-27 03:04:00 </td>
   <td style="text-align:left;"> Fed Signals Rate Hike in March </td>
   <td style="text-align:left;"> The Federal Reserve expects it will soon be appropriate to raise the target range for the federal funds rate as inflation is well above 2 percent and the labor market is strong. Beginning in February, the central bank will increase its holdings of Treasury securities by at least $20 billion per month and of agency mortgage-backed securities by at least $10 billion per month. The reduction of the $8.9 trillion balance sheet will start after the interest rates hike and the central bank intends to reduce its securities holdings over time by adjusting the amounts reinvested of principal payments received from securities held in the System Open Market Account (SOMA), a separate statement showed. Meanwhile, during a virtual press conference, Powell said “The committee is of a mind to raise the Fed funds rate at the March meeting” if conditions are there to do so, while noting that officials have not made any decisions about the path of policy because it needs to be “nimble.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/26/business/economy/fed-interest-rates-inflation.html </td>
   <td style="text-align:left;"> 2022-01-27 03:00:36 </td>
   <td style="text-align:left;"> Fed Signals Rate Increase in March, Citing Inflation and Strong Job Market - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Jerome H. Powell, the Fed chair, said the central bank could raise rates imminently as officials cut back help for the economy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , transcript                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The committee left the target range for the federal funds rate unchanged, and reaffirmed our plan announced in December to end asset purchases in early March. In light of the remarkable progress we’ve seen in the labor market and inflation that is well above our 2 percent longer-run goal, the economy no longer needs sustained high levels of monetary policy support. That is why we are phasing out our asset purchases, and why we expect it will soon be appropriate to raise the target range for the federal funds rate. Of course, the economic outlook remains highly uncertain. Making appropriate monetary policy in this environment requires humility, recognizing that the economy evolves in unexpected ways. We’ll need to be nimble so that we can respond to the full range of plausible outcomes., By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Federal Reserve officials signaled on Wednesday that they were on track to raise interest rates in March, given that inflation has been running far above policymakers’ target and that labor market data suggests employees are in short supply.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Central bankers left rates unchanged at near-zero — where they have been set since March 2020 — but the statement after their two-day policy meeting laid the groundwork for higher borrowing costs “soon.” Jerome H. Powell, the Fed chair, said officials no longer thought America’s rapidly healing economy needed so much support, and he confirmed that a rate increase was likely at the central bank’s next meeting.                                                                                                                                                                                                                                                                                                                                                                                                , “I would say that the committee is of a mind to raise the federal funds rate at the March meeting, assuming that the conditions are appropriate for doing so,” Mr. Powell said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , While he declined to say how many rate increases officials expected to make this year, he noted that this economic expansion was very different from past ones, with “higher inflation, higher growth, a much stronger economy — and I think those differences are likely to be reflected in the policy that we implement.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The Fed was already slowing a bond-buying program it had been using to bolster the economy, and that program remains on track to end in March. The Fed’s post-meeting statements and Mr. Powell’s remarks signaled that central bankers could begin to shrink their balance sheet holdings of government-backed debt soon after they begin to raise interest rates, a move that would further remove support from markets and the economy.                                                                                                                                                                                                                                                                                                                                                                                  , Investors have been nervously eyeing the Fed’s next steps, worried that its policy changes will hurt stock and other asset prices and rapidly slow down the economy. Stocks on Wall Street gave up their gains and yields on government bonds rose as Mr. Powell spoke. The S&amp;P 500 ended with a loss of 0.2 percent after earlier rising as much as 2.2 percent. The yield on 10-year Treasury notes, a proxy for investor expectations for interest rates, jumped as high as 1.87 percent.                                                                                                                                                                                                                                                                                                                                , The Fed has pivoted sharply from boosting growth to preparing to cool it down as businesses report widespread labor shortages and as prices across the economy — for rent, cars and couches — soar. Consumer prices are rising at the fastest pace since 1982, eating away at paychecks and creating a political liability for President Biden and Democrats. It is the Fed’s job to keep inflation under control and to set the stage for a strong job market.                                                                                                                                                                                                                                                                                                                                                             , “The Fed has completed its pivot from being patient to panicked on inflation,” Diane Swonk, the chief economist at Grant Thornton, wrote in a research note to clients after the meeting. “Its next move will be to raise rates.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The Fed’s withdrawal of policy support could temper consumer and corporate demand as borrowing money to buy a car, a boat, a house or a business becomes more expensive. Slower demand could give supply chains, which have fallen behind during the pandemic, room to catch up. By slowing down hiring, the Fed’s moves could also limit wage growth, which might otherwise feed into inflation if employers raised prices to cover higher labor costs.                                                                                                                                                                                                                                                                                                                                                                    , Investors nudged up their expectations for rate increases following the meeting and now project the Fed to raise rates five times this year, based on market pricing, and for the Fed’s policy rate to end the year between 1.25 and 1.5 percent. And economists increasingly warn that it is possible central bankers could move quickly — perhaps lifting borrowing costs at each consecutive meeting instead of leaving gaps, or in half-percentage point increases instead of the quarter-point moves that are more typical.                                                                                                                                                                                                                                                                                            , But Mr. Powell demurred when asked about the pace of rate increases, saying that it was important to be “humble and nimble” and that “we’re going to be led by the incoming data and the evolving outlook.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , “He went out of his way not to commit to a preset course,” said Subadra Rajappa, the head of U.S. rates strategy at Société Générale. The lack of clarity over what happens next “is a setup for a volatile market.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , While interest rates are expected to rise over the coming years, most economists and investors do not expect them to return to anything like the double-digit levels that prevailed in the early 1980s. The Fed anticipates that its longer-run interest rate might hover around 2.5 percent.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Investors also have been eagerly watching to see how quickly the Fed will shrink its balance sheet of asset holdings. The Fed’s policy committee released a statement of principles for that process on Wednesday, setting out plans to “significantly” reduce its holdings “in a predictable manner” and “primarily” by adjusting how much it reinvests as assets expire.                                                                                                                                                                                                                                                                                                                                                                                                                                                  , “They are trying, I think, to reduce market uncertainty around the balance sheet — but they’re telling us it’s happening,” said Priya Misra, the global head of rates strategy at TD Securities, adding that the release suggested that the process would begin within a few months.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Mr. Powell noted during his news conference that both of the areas the Fed is responsible for — fostering price stability and maximum employment — had prodded the central bank to “move steadily away” from helping the economy so much.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , “There are many millions more job openings than there are unemployed people,” Mr. Powell said. “I think there’s quite a bit of room to raise interest rates without threatening the labor market.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The unemployment rate has fallen to 3.9 percent, down from its peak of 14.7 percent at the worst economic point in the pandemic and near its February 2020 level of 3.5 percent. Wages are growing at the fastest pace in decades.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , What is inflation? Inflation is a loss of purchasing power over time, meaning your dollar will not go as far tomorrow as it did today. It is typically expressed as the annual change in prices for everyday goods and services such as food, furniture, apparel, transportation and toys.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , What causes inflation? It can be the result of rising consumer demand. But inflation can also rise and fall based on developments that have little to do with economic conditions, such as limited oil production and supply chain problems.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Where is inflation headed? Officials say they do not yet see evidence that rapid inflation is turning into a permanent feature of the economic landscape, even as prices rise very quickly. There are plenty of reasons to believe that the inflationary burst will fade, but some concerning signs suggest it may last.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Is inflation bad? It depends on the circumstances. Fast price increases spell trouble, but moderate price gains can lead to higher wages and job growth.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , How does inflation affect the poor? Inflation can be especially hard to shoulder for poor households because they spend a bigger chunk of their budgets on necessities like food, housing and gas.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Can inflation affect the stock market? Rapid inflation typically spells trouble for stocks. Financial assets in general have historically fared badly during inflation booms, while tangible assets like houses have held their value better.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , At the same time, Mr. Powell said, the problems pushing inflation up have been “larger and longer lasting” than officials expected, and he noted that the Fed was “attentive to the risk” that rapid wage growth could further fuel price gains.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The Fed’s preferred inflation gauge is expected to show that prices picked up by 5.8 percent in the year through December when the latest report is released on Friday, more than double the 2 percent pace the Fed aims for annually and on average.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Prices are high partly because global supply chains are struggling to produce and transport enough lumber, computer chips and clothing to keep pace with booming demand for goods. The pandemic changed consumption patterns, and households have money in their pockets thanks to long months at home and repeated government relief.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , If the virus fades, that will help things get back to normal by allowing factories to operate at full speed without rolling shutdowns and by enabling consumers to spend their money on trips to the nail salon or Disney World instead of on new kitchen tables and bathroom renovations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Fed officials — and many economists — spent much of 2021 forecasting that conditions would stabilize and that inflation would go away on its own. That didn’t happen.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Central bankers have continued to estimate that the price pickup will fade substantially by late this year, but they have also guided policy into a position from which it can fight against any lasting inflation pressures. By making it more expensive to buy a lawn mower on credit or a car with an auto loan, Fed rate increases might help to cool off America’s spending spree.                                                                                                                                                                                                                                                                                                                                                                                                                                     , At their meeting in December, policymakers projected that they would raise interest rates three times this year. They did not release a fresh set of economic projections with this policy statement. The next quarterly estimates will come in March.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , “Since the December meeting, I would say that the inflation situation is about the same but probably slightly worse,” Mr. Powell said when asked about the Fed’s previous expectations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , While presidential administrations typically do not like rate increases — they slow the economy — inflation has become a major concern for voters and a thorny political barrier for Mr. Biden as he tries to pass his legislative agenda. The White House has no say on Fed policy, but it has signaled acceptance of the central bank’s recent decisions to pull back on economic help.                                                                                                                                                                                                                                                                                                                                                                                                                                   , “Obviously the Fed is independent,” Jen Psaki, the White House press secretary, said on Wednesday after the Fed’s release and news conference. “Chairman Powell has indicated his plans to recalibrate in the past, and the president spoke last week to his support for that.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/26/fed-decision-january-2022-.html </td>
   <td style="text-align:left;"> 2022-01-27 03:00:00 </td>
   <td style="text-align:left;"> Federal Reserve points to interest rate hike coming in March </td>
   <td style="text-align:left;"> , Facing both turbulent financial markets and raging inflation, the Federal Reserve on Wednesday indicated it could soon raise interest rates for the first time in more than three years as part of a broader tightening of historically easy monetary policy.                                                                                                                                                                                , In a move that came as little surprise, the Fed's policymaking group said a quarter-percentage point increase to its benchmark short-term borrowing rate is likely forthcoming. It would be the first rise since December 2018.                                                                                                                                                                                                              , Chairman Jerome Powell added that the Fed could move on an aggressive path.                                                                                                                                                                                                                                                                                                                                                                  , "I think there's quite a bit of room to raise interest rates without threatening the labor market," Powell said at his post-meeting news conference. After being up strongly earlier, the major stock market averages turned negative shortly following Powell's pronouncement.                                                                                                                                                              , The committee's statement came in response to inflation running at its hottest level in nearly 40 years. Though the move toward less accommodative policy has been well telegraphed over the past several weeks, markets in recent days have been remarkably choppy as investors worried that the Fed might tighten policy even more than expected.                                                                                          , The post-meeting statement from the Federal Open Market Committee did not provide a specific time for when the increase will come, though indications are that it could happen as soon as the March meeting. The statement was adopted without dissent.                                                                                                                                                                                      , "With inflation well above 2 percent and a strong labor market, the Committee expects it will soon be appropriate to raise the target range for the federal funds rate," the statement said. The Fed does not meet in February.                                                                                                                                                                                                              , In addition, the committee noted the central bank's monthly bond-buying will proceed at just $30 billion in February, indicating that program is expected to end in March as well at the same time that rates increase.                                                                                                                                                                                                                      , There were no specific indications Wednesday when the Fed might start to reduce bond holdings that have bloated its balance sheet to nearly $9 trillion.                                                                                                                                                                                                                                                                                     , However, the committee released a statement outlining "principles for reducing the size of the balance sheet." The statement is prefaced with the notion that the Fed is preparing for "significantly reducing" the level of asset holdings.                                                                                                                                                                                                 , That policy sheet noted that the benchmark funds rate is the "primary means of adjusting the stance of monetary policy." The committee further noted that the balance sheet reduction would happen after rate hikes start and would be "in a predictable manner" by adjusting how much of the bank's proceeds from its bond holdings would be reinvested and how much would be allowed to roll off.                                          , "The Fed's announcement that it will 'soon be appropriate' to raise interest rates is a clear sign that a March rate hike is coming," noted Michael Pearce, senior U.S. economist at Capital Economics. "The Fed's plans to begin running down its balance sheet once rates begin to rise suggests an announcement on that could also come as soon as the next meeting, which would be slightly more hawkish than we expected."              , Mohamed El-Erian says Fed missed a 'golden opportunity' to address inflation concerns                                                                                                                                                                                                                                                                                                                                                        , Goldman says buy these beaten-up innovative stocks, with some down 50%                                                                                                                                                                                                                                                                                                                                                                       , David Einhorn predicts inflation will cause a recession, adds new positions                                                                                                                                                                                                                                                                                                                                                                  , Markets had been anxiously awaiting the Fed's decision.                                                                                                                                                                                                                                                                                                                                                                                      , Investors had been expecting the Fed to tee up the first of multiple rate hikes, and in fact are pricing in a more aggressive schedule this year than FOMC officials indicated in their December outlook. At that time, the committee penciled in three 25 basis point moves this year, while the market is pricing in four hikes, according to the CME's FedWatch tool that computes the probabilities through the fed funds futures market., Traders are anticipating a funds rate by the end of the year of about 1%, from the near-zero range where it's currently pegged.                                                                                                                                                                                                                                                                                                              , Fed officials have been expressing concern lately about persistent inflation, following months of insisting that the price increases were "transitory." Consumer prices are up 7% from a year ago, the fastest 12-month pace since the summer of 1982.                                                                                                                                                                                       , The durability of inflation has caused officials to rethink a strategy that has produced the easiest monetary policy in Fed history. The central bank slashed its benchmark rate to a target of 0%-0.25% in the early days of the Covid pandemic and has been buying billions of dollars in Treasurys and mortgage-backed securities each month.                                                                                             , "Part of this will be the Fed moving away from very high accommodative policy to substantially less accommodative policy and over time to a policy that's not accommodative," Powell said.                                                                                                                                                                                                                                                   , The bond-buying program, sometimes called quantitative easing, has brought the Fed's total assets on its balance sheet to nearly $9 trillion. Powell said the Fed will wait a few months then probably start allowing some of the proceeds from its bond holdings to run off each month while reinvesting the rest. As things stand now, the Fed reinvests all of those proceeds.                                                            , "The balance sheet is substantially larger than it needs to be," Powell said. "There's a substantial amount of shrinkage in the balance sheet to be done. That's going to take some time. We want that process to be orderly and predictable."                                                                                                                                                                                               , Goldman Sachs said a few days ago that it expects the balance sheet reduction to start in June at a pace of $100 billion a month, about double the pace of the previous move of a runoff several years ago.                                                                                                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                       , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                       , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                             , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                             , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                           , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/clorox-downgraded-covid-driven-growth-slows/story.aspx?guid={43C91626-9B2C-489B-845F-9098CA3076A6}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-27 02:54:15 </td>
   <td style="text-align:left;"> Clorox downgraded as COVID-driven growth slows  - MarketWatch </td>
   <td style="text-align:left;"> Clorox Co. 
        CLX,
        -5.62%
       shares fell 4.2% in Wednesday trading after the consumer cleaning products company was downgraded to underperform from neutral at Credit Suisse based on concern that the skyrocketing growth from early in the pandemic has started to wane. Analysts maintained their $160 target price. Sales for fiscal year ending June 2021 reached $7.34 billion, up from $6.72 billion for the fiscal year ending June 2020. Sales for the fiscal first quarter fell to $1.81 billion from $1.92 billion the previous year. "Nearly two years into the pandemic, Clorox is a larger company that can grow faster," the note said. "If consumption continues to revert toward pre-pandemic levels, $500 million in company sales may still be at risk." Analysts also highlight pricing uncertainty and the impact on margins. "If consumption weakens further amid high input cost inflation, a drop in volumes could result in material deleverage to margins," the note said. Clorox is scheduled to report fiscal second-quarter results on Feb. 3, according to a FactSet calendar. Clorox stock has tumbled 21.7% over the past year while the S&amp;P 500 index 
        SPX,
        -0.15%
       has gained nearly 15%., The central bank intends to begin outlining plans to reduce its $9 trillion securities holdings after rate increases have started.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/avis-budget-stock-bounces-erasing/story.aspx?guid={B5792CBC-995F-441A-B0DA-D14376B69E00}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-27 02:48:54 </td>
   <td style="text-align:left;"> Avis Budget stock bounces, as erasing all of the November 'short squeeze' surge triggers upgrade at JPMorgan - MarketWatch </td>
   <td style="text-align:left;"> Shares of Avis Budget Group Inc. 
        CAR,
        +1.20%
       charged up 6.7% in afternoon trading Wednesday, enough to pace the Dow Jones Transportation Average's 
        DJT,
        -1.01%
       gainers, after J.P. Morgan analyst Ryan Brinkman backed away from bearish call after the selloff to a three-month low. The stock closed Tuesday at $169.52, at the lowest price since Oct. 27, meaning it had erased more than everything it gained during the "meme"-like, short-squeeze-induced 108.3% rocket ride on Nov. 2 after the car rental company reported record third-quarter earnings. On Wednesday, J.P. Morgan's Brinkman raised his rating to neutral, after double downgrading it on Nov. 3 to underweight from overweight. "While we expected some normalization lower in CAR [Avis] shares on unwind of the technical reasons underpinning the short squeeze (our prior price target of $225 today moves to $205), from our conversations, CAR shares have come under fire for their leverage to travel amid the COVID-19 omicron variant surge, although experts predict this wave is now or may soon recede, and the variant seems so far to cause more mild symptoms and to have had less of an effect on bookings, etc., than earlier variants," Brinkman wrote in a note to clients. The stock has dropped 12.8% year to date, while the Dow transports has lost 6.9% and the Dow Jones Industrial Average 
        DJIA,
        -0.38%
       has slipped 4.8%., Tesla's earnings-per-share beat for the fourth quarter is about 8%, which is solid, but below the average of 25%. It might not be enough to counter recent market turmoil.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/palladium-futures-rally-highest-finish/story.aspx?guid={61DC8B61-553E-41B4-8698-0AE8AAFA083C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-27 02:45:28 </td>
   <td style="text-align:left;"> Palladium futures rally to highest finish since September on threat to global supplies - MarketWatch </td>
   <td style="text-align:left;"> Palladium futures climbed sharply on Wednesday, with prices settling at their highest since September, with rising tensions over Ukraine prompting concerns of a possible disruption to supplies of the metal from Russia, which is the world's largest producer. "An all-out conflict with Russia would exasperate an already critical supply issue in the palladium space," said Chris Blasi, president of Neptune Global. March palladium 
        PAH22,
        -1.30%
       climbed $161.70, or 7.4%, to settle at $2,350.60 an ounce on Comex, the highest most-active contract finish since Sept. 7, according to FactSet data., Some Canadian retailers are now requiring proof of vaccination due to local regulations, resulting in some critics calling to boycott Walmart in response                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-tight-lipped-breyer-retirement-ill/story.aspx?guid={ABE15441-308B-43DD-86CA-8D5147D3CE0B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-27 02:35:19 </td>
   <td style="text-align:left;"> Biden tight-lipped on Breyer retirement: 'I'll be happy to talk about it later' - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden on Wednesday declined to speak at length about reports that said liberal Supreme Court Justice Stephen Breyer is retiring, though he joked about nominating Cummins 
        CMI,
        -0.36%
       CEO Tom Linebarger. "There has been no announcement from Justice Breyer. Let him make whatever statement he's going to make, and I'll be happy to talk about it later," Biden told reporters, as the president hosted a meeting about his Build Back Better plan with 10 private-sector executives. "Want to go to the Supreme Court, Tom?" Biden added. Linebarger laughed and then said, "I'm just going to demur on that one.", In the ongoing conflict between Russia and Ukraine, Russian President Vladimir Putin's eyes are on a bigger prize, a top expert on the Russian leader and his country says.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/federal-reserve-signals-interest-rate-hike-january-2022 </td>
   <td style="text-align:left;"> 2022-01-27 02:02:06 </td>
   <td style="text-align:left;"> Fed signals interest rate hike could come 'soon' as inflation rages </td>
   <td style="text-align:left;"> Penn Mutual Asset Management CIO Mark Heppenstall argues there’s ‘a lot of pressure’ on Federal Reserve Chairman Jerome Powell ahead of his press conference.                                                                                                                                                                                                                                                                                                           , The Federal Reserve on Wednesday signaled it could "soon" raise interest rates for the first time in three years, paving the way for a March liftoff as policymakers seek to keep prices under control and combat the hottest inflation in nearly four decades.                                                                                                                                                                                                         , Although central bank officials have left rates unchanged since March 2020, they indicated broad support this week during a two-day, policy-setting meeting to begin aggressively normalizing policy, including raising rates amid growing concern over the rapid increase in consumer prices.                                                                                                                                                                          , A rate increase would mark the first since December 2018.                                                                                                                                                                                                                                                                                                                                                                                                               , FED STATEMENT, INFLATION UPDATE AND POWELL PRESSER: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                                                                                        , "With inflation well above 2% and a strong labor market, the committee expects it will soon be appropriate to raise the target range for the federal funds rate," the Fed said in its post-meeting statement. The central bank's next meeting is scheduled for March 15-16.                                                                                                                                                                                             , In this Jan. 29, 2020, file photo, Federal Reserve Chair Jerome Powell pauses during a news conference in Washington.  (AP Photo/Manuel Balce Ceneta, File / AP Newsroom)                                                                                                                                                                                                                                                                                               , The Fed already began slowing its bond purchases last year and is on track to conclude the program in early March, allowing policymakers to begin hiking interest rates and reducing a $9 trillion balance sheet. It is unclear when the central bank will begin shrinking its bond holdings, although officials said in the statement that they would start "in a predictable manner" primarily by adjusting how much they will reinvest as their bond holdings expire., "The committee is prepared to adjust any of the details of its approach to reducing the size of the balance sheet in light of economic and financial developments," the Fed said in a separate statement outlining "principles for reducing the size of the balance sheet."                                                                                                                                                                                             , For months, the Fed has been wrestling with its dual mandate of stable prices and full employment. But the nation's jobless rate plunged to 3.9% in December, down from a pandemic high of 14.7%, while consumer prices surged 7.1% from a year ago, marking the fastest pace for inflation since 1982 as consumer demand confronts a shortage of goods caused by congested ports and other pandemic-induced disruptions in the supply chain.                           , "I would say, and this view is widely held on the committee, both sides of the mandate are calling for us to move steadily away from the very highly accommodative policies we put in place during the challenging conditions that the economy faced earlier in the pandemic," Chairman Jerome Powell told reporters during a post-meeting press conference. "Most FOMC participants agree that labor market conditions are consistent with maximum employment."        , This May 4, 2021, file photo shows the Federal Reserve building in Washington.  (Associated Press)                                                                                                                                                                                                                                                                                                                                                                      , Most economists expect the Fed to raise rates four times this year. Traders are already pricing in a more than 90% chance of a rate increase during the Fed's mid-March meeting, and a roughly 65% chance of four hikes over the course of the year, according to the CME Group, which tracks trading.                                                                                                                                                                  , Some economists believe the Fed waited too long to confront the burst in inflation, while others have expressed concerns that moving too quickly to stabilize prices risks slowing hiring and potentially leaving many workers, particularly lower-income Americans, without a job. Hiking interest rates tends to create higher rates on consumers and business loans, which slows the economy by forcing employers to cut back on spending.                           , Powell said that it's difficult to determine what pace of rate increases is needed to cool inflation without strangling the economy but said it's important to be "humble and nimble."                                                                                                                                                                                                                                                                                  , "We’re going to be led by the incoming data and the evolving outlook," he said.                                                                                                                                                                                                                                                                                                                                                                                         , A security guard walks in front of an image of the Federal Reserve following the two-day Federal Open Market Committee (FOMC) policy meeting in Washington, D.C., March 16, 2016.  (REUTERS/Kevin Lamarque/File Photo)                                                                                                                                                                                                                                                  , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                             , The central bank has been gradually setting the scene for at least one rate hike in 2022 as it unwinds the ultra-easy policies put in place to prop up the economy in 2020 after the coronavirus pandemic began. The prospect of multiple rate hikes this year, however, has rattled financial markets, with the Dow Jones Industrial Average whipsawing more than 1,000 points this week.                                                                              , "From here forward, investors should expect each FOMC meeting to be considered 'live' from the perspective that rate hikes are now on the table," said Jason Pride, chief investment officer of private wealth at Glenmede. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/pgr:us </td>
   <td style="text-align:left;"> 2022-01-27 01:50:41 </td>
   <td style="text-align:left;"> Progressive earnings below expectations at 0.90 USD </td>
   <td style="text-align:left;"> Progressive (PGR) released earnings per share at 0.90 USD, compared to market expectations of 0.99 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/26/stocks-making-the-biggest-moves-midday-microsoft-mattel-f5-draftkings-clorox-and-more.html </td>
   <td style="text-align:left;"> 2022-01-27 01:48:24 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Microsoft, Mattel, F5, DraftKings, Clorox and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                   , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                       , Corning — Shares of the tech and specialty glass company rallied 11.1% after beating on the top and bottom lines of its quarterly results. Corning earned 54 cents per share on revenue of $3.71 billion. Wall Street expected earnings of 52 cents per share on revenue of $3.59 billion, according to Refinitiv., DraftKings — The sports-betting stock jumped 5.2% following an upgrade to overweight from equal weight from Morgan Stanley. The firm said in a note that DraftKings was likely to be one of the long-term winners in the competitive online gambling space.                                                       , F5 — Shares of the cloud security company slid 8.4% following current quarter guidance issued by F5 that fell below analysts' expectations. The company also cut its full-year outlook, citing supply chain issues.                                                                                               , Mattel — The toy stock jumped 4.3% after Mattel announced that it had won back the license to make toys based on the Walt Disney princess lineup. The company had lost the license to rival Hasbro in 2016.                                                                                                       , Microsoft — Shares of Microsoft climbed 2.8% after the company gave an upbeat forecast for the current quarter on continued growth in cloud services revenue. It also reported a quarterly profit of $2.48 per share, beating analysts' estimates by 17 cents, as well as revenue that beat forecasts.            , Automatic Data Processing — Shares of ADP dropped 8.9% despite the payroll firm reporting better-than-expected fiscal second-quarter earnings. The company earned $1.65 per share, topping estimates of $1.63 per share, according to Refinitiv. ADP also beat Wall Street's revenue forecasts.                   , Kimberly-Clark Corporation — The consumer products maker's shares fell 3.3% after issuing weaker-than-expected guidance on earnings and revenue. The company beat expectations for per-share earnings and revenue for the fourth quarter, however.                                                                , Boeing — The aerospace company's shares dropped 4.8% after it reported a much wider-than-expected fourth-quarter loss and missed on revenue. It also said it took a $3.5 billion pretax charge on its 787 Dreamliners after production issues delayed its delivery of the planes for the last 15 months.          , Moderna — Moderna shares added 1.5% after Deutsche Bank upgraded the stock to hold from sell, mainly on valuation. Deutsche noted the shares "now both through our prior price target and discounted cash flow and at a more reasonable c$65bn valuation."                                                        , Rollins — Rollins' shares fell 4.9% after the company reported quarterly earnings or 13 cents per share. That was slightly lower than analysts' expectations of 15 cents per share, according to FactSet. The pest control company also reported a revenue beat for the quarter.                                  , Clorox — Shares of the cleaning products company fell 5.6% after Credit Suisse downgraded the stock to underperform, noting that pandemic-era sales growth may reverse. The firm said that if growth slows, Clorox could have difficulty navigating inflation in its supply chain.                                ,  — CNBC's Maggie Fitzgerald and Jesse Pound contributed reporting.                                                                                                                                                                                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bangladesh/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-27 01:45:36 </td>
   <td style="text-align:left;"> Bangladesh December Inflation Rate Rises to 15-Month High </td>
   <td style="text-align:left;"> The annual inflation rate in Bangladesh rose for the fifth consecutive month to 6.05 percent in December of 2021 from 5.98 percent in the previous month. It was the highest inflation rate since October of 2020, as prices advanced faster for both food (5.46 percent vs 5.43 percent in November) and non-food (7 percent vs 6.87 percent) items. On a monthly basis, consumer prices fell 0.38 percent, down from a 0.49 percent decline in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/workers-leave-jobs-for-trucking-industry-six-figure-salaries </td>
   <td style="text-align:left;"> 2022-01-27 01:39:27 </td>
   <td style="text-align:left;"> Workers leaving jobs for trucking industry, six-figure salaries </td>
   <td style="text-align:left;"> Metro South Community Improvement District Vice Chair Wayne Smith says some workers are changing careers for the chance to make six figures as a truck driver.                                                                                            , As everyday prices and inflation concerns continue to surge across America, the trucking industry is ramping up efforts to attract the needed 80,000 drivers that will alleviate supply chain pressures.                                                  , The trucker shortage created an opportunity for Roadmaster Drivers School to open 20 locations nationwide, telling and teaching prospective drivers about the six figure starting point.                                                                  , According to Metro South Community Improvement District Vice Chair Wayne Smith, drivers can earn well over $100,000 in just a few years.                                                                                                                  , "We got two applicants applying for a driving position, both in the same week… both [with] four-year degrees," Smith told FOX Business’ Connell McShane. "I asked them, ‘Why aren't you in the field that you studied?’"                                  , "They said, ‘Because we can't make the money we want to make,’" he continued.                                                                                                                                                                             , TRUCKING COMPANY ENACTS LARGEST PAY INCREASE IN HISTORY                                                                                                                                                                                                   , Smith’s comments come after a U.S. trucking firm enacted a major pay increase for its drivers – the largest in the decades-old company's history.                                                                                                         , Recent Roadmaster graduate and former Amazon employee Jahmiah Smith explained she left her job and became a truck driver to complete a life goal.                                                                                                         , American Trucking Associations CEO Chris Spear argues the supply chain issue is being exacerbated by the labor shortage.                                                                                                                                  , "I want to travel to all 48 states," Smith said. "See it for what it is."                                                                                                                                                                                 , In a move that also aims to expedite the supply chain rebound, 18 to 20-year-old truck drivers can soon cross state lines thanks to a new federal program from the U.S. Department of Transportation and Department of Labor announced earlier this month., The Safe Driver Apprenticeship Pilot (SDAP) program is an under-21 pilot program for truck drivers mandated in the Bipartisan Infrastructure Law, according to a press release, creating apprenticeships for 3,000 young drivers.                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                               , FOX Business’ Connell McShane reports from Conley, Georgia, where Roadmaster Drivers School has doubled its number of locations over the last two years.                                                                                                  , Labor Secretary Marty Walsh previously stated it was exploring the option of lowering the driver age for interstate commerce on "Varney &amp; Co." last month.                                                                                                , "One of the things we have to do is really train and prepare more truck drivers," he said.                                                                                                                                                                , READ MORE FROM FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/palladium </td>
   <td style="text-align:left;"> 2022-01-27 01:20:00 </td>
   <td style="text-align:left;"> Palladium Soars to 4-Month High Amid Supply Concerns </td>
   <td style="text-align:left;"> Palladium futures extended gains to near $2350 an ounce, the highest since September 7th and up more than 25% from the start of the year amid concerns over supply disruptions from Russia, the metal’s top producer as tension between Russia and the West intensified. Furthermore, exports from Russia may be hampered if Russia invades Ukraine, as the US and EU have been weighing further sanctions on Russia’s biggest banks and are considering restricting the country’s ability to convert rubles for dollars. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/fed-statement-inflation-update-and-powell-press-conference-live-updates </td>
   <td style="text-align:left;"> 2022-01-27 01:16:53 </td>
   <td style="text-align:left;"> Fed statement, inflation update and Powell press conference: RECAP </td>
   <td style="text-align:left;"> FOX Business’ Cheryl Casone reports on the Federal Reserve’s first policy-setting meeting of the year, where the Federal Open Market Committee also reaffirmed its commitment to withdrawing its asset purchase program., The Federal Reserve on Wednesday laid the groundwork for a rate hike in March, while also reiterating supply chain issues are contributing to red-hot inflation.                                                        , During Fed Chairman Jerome Powell's press conference stocks lost momentum, with all three of the major averages falling.                                                                                                , WHERE INFLATION IS HITTING CONSUMERS THE HARDEST                                                                                                                                                                        , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                 , Find a recap of Powell's Q&amp;A here on the FOX Business Blog. Mobile users click here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-01-27 01:16:00 </td>
   <td style="text-align:left;"> Brazilian Real Rebounds From 1-Week Low </td>
   <td style="text-align:left;"> The Brazilian Real traded below 5.45, after hitting a one-week low of 5.48 on January 24th, amid hotter-than-expected inflation data outweighing a stronger dollar. The dollar index rose to above 96.1, near a three-week high, as traders await the Fed monetary policy decision for more clues on how much and how quickly interest rates will be raised. Domestically, mid-month consumer price data showed that inflation rose 10.2% YoY, above market expectations, and easing from a 10.42% increase in the previous period. Still, inflation remained well above the central bank’s target of 3.5% strengthening the case for the central bank to keep its monetary policy tightening stance. Since the Brazilian central bank started to hike, it has raised the borrowing costs by 725 bps and is expected to deliver at least one more hike of 150 bps during its next monetary policy meeting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 01:01:00 </td>
   <td style="text-align:left;"> UK Stocks Extend Gains for 2nd Straight Session </td>
   <td style="text-align:left;"> The FTSE 100 jumped 1.3%% to close at 7,470 on Wednesday, in line with its European peers, and extending gains for a second straight session, as heavyweight mining, energy, and bank stocks lead the gains. Investors are cautiously waiting for the highly anticipated Federal Reserve monetary policy meeting, where policymakers are expected to signal a more aggressive tightening. At the same time, traders continued to monitor the evolving Russia-Ukraine tensions, with President Biden saying he would mull sanctioning President Putin in a rare move, while the UK’s Foreign Secretary said that option was not ruled out. Meanwhile, the pressure on the UK's Prime Minister has eased slightly, as Tory MPs said the party will wait for the result of the policy inquiry into the illegal parties held at the Prime Minister’s residence. On the earnings front, Wizz Air reported a Q3 operating loss of €213.6 million and warned results in Q4 could be worse before improving in the spring of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 01:00:00 </td>
   <td style="text-align:left;"> South African Stocks Jump on Wednesday </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index jumped 2.1% to close at 73,797 on Wednesday, in line with global peers, lifted by commodity and mining companies. Petrochemicals giant Sasol was one of the top performers with the company's shares rising by over 7%, helped by a rally in oil prices. Meanwhile, investors focus their attention on the US Federal Reserve policy announcement later and wait for more corporate reports in the US. Also, geopolitical tension in Eastern Europe remains in the spotlight. Domestically, traders wait for the outcome of South African Reserve Bank's first policy meeting of 2022 on Thursday, at which policymakers are widely expected to lift the repo rate to 4% to curb inflationary pressures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/platinum </td>
   <td style="text-align:left;"> 2022-01-27 00:51:00 </td>
   <td style="text-align:left;"> Platinum Rebounds to 9-Week High </td>
   <td style="text-align:left;"> Platinum futures reached a 2-month high to trade close to $1,050 per troy ounce, tracking recent gains in other precious metals amid inflation and geopolitical worries. At the same time, the supply remains tight and demand is seen increasing as the economies continue to recover and manufacturers start to handle better the ship shortage and start producing more vehicles. Also, both the major producers, Sibanye-Stillwater and Anglo American Platinum, have revised their outlook for their production, their mining supply, over the next few years, according to World Platinum Investment Council director of research Trevor Raymond. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-01-27 00:49:00 </td>
   <td style="text-align:left;"> Gold Slips on Strong Dollar </td>
   <td style="text-align:left;"> Gold prices slipped to around $1,830 an ounce on Wednesday, after hitting a 2-month high of $1,854 in the previous session, as the dollar strengthened ahead of the Fed meeting. The dollar index rose to above 96.1 near a three-week high as traders await the Fed monetary policy decision later in the day for more clues on how much and how quickly interest rates will be raised. The yellow metal has been recently driven by a combination of profit-taking after reaching recent highs and concerns on the next steps of the US central bank as rates hikes raise the opportunity cost of holding the bullion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Extend Rebound on Wednesday </td>
   <td style="text-align:left;"> The FTSE MIB Index jumped 2.3% to close at 26,619 on Wednesday after slightly rebounding 0.2% in the last session, supported by the industrial and technology sectors, as investors traded with expectations that Federal Reserve policy statement would confirm interest rate hikes in March after the session’s close. In the corporate front, industrial stocks rose 2.7%, lifted by the steel pipe manufacturing sector and auto makers, while tech stocks jumped 3.2%. Both UniCredit (3.6%) and STMicroelecronics (3.1%) closed in the green as traders positioned themselves ahead of the firms’ results publication on Friday. At the same time, Tod’s gained 15.8% after announcing it returned to pre-pandemic sales levels in European retailers and in online sales. Meanwhile, Italian lawmakers discuss possible compromises and candidates for the for the fourth round of elections tomorrow, where a simple majority starts being enough to guarantee victory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 00:47:00 </td>
   <td style="text-align:left;"> European Shares Gain Ahead of Fed Statement </td>
   <td style="text-align:left;"> European shares booked the largest gain in seven weeks on Wednesday, with Frankfurt's DAX 30 adding 2.2% at 15,459 and other major bourses gaining between 1.4% and 2.5%, led by travel and mining stocks. Investors awaited the outcome of the Fed's monetary policy meeting due today, with US officials expected to signal an interest rate hike as early as March, followed by three more quarter-point increases by year-end, amid a surging inflation and a solid economic recovery. On the corporate front, Italian fashion group Tod's 2021 sales beat market expectations, while debt recovery firm doValue said it would aim to keep the amount of loans it manages stable at €160 billion euros to the end of 2024. BioNTech shares gained after the company and Pfizer said that they had started a clinical trial to test a new version of their vaccine specifically designed to target the COVID-19 Omicron variant. Meanwhile, hygiene products group Essity posted a bigger-than-expected fall in quarterly profit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/soybeans </td>
   <td style="text-align:left;"> 2022-01-27 00:46:03 </td>
   <td style="text-align:left;"> Soybeans Hits 24-week High </td>
   <td style="text-align:left;"> Soybeans increased to a 24-week high of 1430 USd/Bu </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 00:46:00 </td>
   <td style="text-align:left;"> French Shares Extend Gains on Wednesday </td>
   <td style="text-align:left;"> The CAC 40 Index jumped 2.1% to close at 6,981 on Wednesday, the second consecutive session in the green, lifted by industrials and commodity backed stocks, as investors expected Federal Reserve policymakers to confirm higher interest rates in March in their statement after market close. Renault gained 5.8% ahead of its press conference regarding the alliance formed with Nissan and Mitsubishi Motor to develop electric vehicles. The auto manufacturers are expected to elaborate over the investment plan of more than USD 23 billion over five years. At the same time, Airbus rose 5.5% after the manufacturer said its helicopters division recorded 414 orders and 388 deliveries in 2021, confirming the rebound of demand after its disruption in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 00:45:12 </td>
   <td style="text-align:left;"> The FTSE 100 Index increased 1.50% </td>
   <td style="text-align:left;"> United Kingdom Stock Market went up by 111 points. The rise was driven by IAG (6.83%), Carnival (5.66%) and Glencore (4.31%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/senate-democrats-biden-expired-child-tax-credit </td>
   <td style="text-align:left;"> 2022-01-27 00:42:50 </td>
   <td style="text-align:left;"> Senate Democrats urge Biden to revive expired child tax credit </td>
   <td style="text-align:left;"> Kentucky Senator Rand Paul discusses on ‘Kudlow’ Putin and Biden’s video call and the electric vehicle incentives in Biden’s spending bill.                                                                                                                                                                                                                                                                                                                            , Top Senate Democrats on Wednesday urged President Biden to keep the expanded child tax credit payment as the "centerpiece" of a stalled tax and spending package as the White House looks to revive a narrower version of the Build Back Better bill.                                                                                                                                                                                                                  , In a letter to Biden, the senators – led by Michael Bennet of Colorado – credited the monthly cash bursts to families with reducing child poverty by more than 40% and keeping an estimated 3.7 million children out of poverty. Other signatories included Sens. Ron Wyden of Oregon, Sherrod Brown of Ohio, Raphael Warnock of Georgia and Cory Booker of New Jersey.                                                                                                , BIDEN TO MEET WITH CEOS IN PUSH TO SALVAGE MEGA SPENDING BILL                                                                                                                                                                                                                                                                                                                                                                                                          , "Without the expanded credit, nearly 10 million children will be thrown back into or deeper into poverty this winter, increasing the monthly child poverty rate from roughly 12% to at least 17%," the lawmakers wrote. "Raising taxes on working families is the last thing we should do during a pandemic."                                                                                                                                                          , President Biden listens to reporter's questions during a meeting on efforts to lower prices for working families, in the East Room of the White House in Washington, Monday, Jan. 24, 2022. (AP Photo/Andrew Harnik / AP Newsroom)                                                                                                                                                                                                                                     , Democrats temporarily expanded the child tax credit in early 2021 as part of a sweeping coronavirus relief package, but the program expired at the end of the year. Under the expansion, low- and middle-income parents could receive up to $3,000 for every child ages 6 to 17 and $3,600 for every child under age 6. The payments were income-based and began to phase out for individuals earning more than $75,000 and married couples earning more than $150,000., The first half was delivered in monthly payments from July to December with $300 for children under the age of six and $250 for those ages 6 to 17, but the last check was mailed out in December. The second half will be delivered as a lump sum when families file their 2021 tax returns in the spring. The IRS said that 36 million families received the payments each month, or about 60 million children.                                                      , Without the enhanced tax credit, an estimated 10 million children are at risk of falling below the poverty line, according to an analysis from the progressive think tank Center on Budget and Policy Priorities.                                                                                                                                                                                                                                                      , Although Biden and most congressional Democrats hoped to extend the boosted program for at least another year with the passage of the $1.7 trillion Build Back Better plan, momentum for the massive social spending and climate bill crumbled after moderate Sen. Joe Manchin, D-W.Va., abruptly withdrew his support last month, citing concerns over inflation and the growing federal debt.                                                                        , This May 4, 2021 image shows teacher Graciela Olague-Barrios working with two infants at Cuidando Los Ninos in Albuquerque, N.M.  ((AP Photo/Susan Montoya Bryan) / AP Newsroom)                                                                                                                                                                                                                                                                                       , "I cannot vote to continue with this piece of legislation. I just can't. I tried everything humanly possible. I can't get there," Manchin said during an interview on "Fox News Sunday" in December. "This is a 'no' on this legislation."                                                                                                                                                                                                                             , One of Manchin's biggest hang-ups over the spending bill was the child tax credit program, which he insisted needed to have work requirements as well as means-testing so that anyone earning more than $200,000 is not eligible for the money. Manchin also expressed concerns that the money could trigger a workforce exodus – an argument that has also been pushed by Republican lawmakers.                                                                       , A Census Bureau survey of spending patterns among recipients in September and October shows that nearly one-third used the money to pay for school expenses, while about one-quarter of families with young children used the monthly payment to help cover child care. Another 40% said they put the money toward paying off debt.                                                                                                                                    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                            , Republicans on the House Ways and Means Committee in December accused Democrats of turning the child tax credit into the "largest welfare-without-work program in existence" and have cited a University of Chicago research paper that found the expanded credit would trigger a workforce exodus of about 1.5 million employees.                                                                                                                                     , Night falls at the Capitol in Washington, Thursday, Dec. 2, 2021, with the deadline to fund the government approaching. ( (AP Photo/J. Scott Applewhite) / AP Newsroom)                                                                                                                                                                                                                                                                                                , "Paying parents not to work and creating more barriers for the jobless to reconnect to a job harms families and the economy," the GOP lawmakers wrote. "Instead of making the worker shortage worse and driving up inflation, Democrats in Congress should join with Republicans to make the 2017 expansion permanent – including rewarding work by preserving the earnings requirement." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cape-verde/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-27 00:33:00 </td>
   <td style="text-align:left;"> Cape Verde December Inflation Rate Highest since 2009 </td>
   <td style="text-align:left;"> The annual inflation rate in Cape Verde accelerated for an eighth straight month to 5.4% in December of 2021, from 4.8% in November. That was the highest rate since February of 2009, pushed up by prices of clothing &amp; footwear (13.4% vs 9.6% in November); transport (10.5% vs 12%); food &amp; non-alcoholic beverages (6.9% vs 5.2%) and alcoholic beverages &amp; tobacco (5.7% vs 5.9%). On a monthly basis, consumer prices were up 0.4%, decelerating from a 0.8% rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bosnia-and-herzegovina/industrial-production </td>
   <td style="text-align:left;"> 2022-01-27 00:27:00 </td>
   <td style="text-align:left;"> Bosnia and Herzegovina Industrial Output Gains Momentum </td>
   <td style="text-align:left;"> Industrial production in Bosnia and Herzegovina rose 7.2 percent year-on-year in December of 2021, following a 6.7 percent gain in November. The strongest contribution came from manufacturing activities (8.8 percent vs 9.9 percent in November), with sharp increases in other transport equipment (47.0 percent vs -22.8 percent) and rubber &amp; plastic products (24.8 percent vs 19.4 percent); and, to a lesser extent, utilities (8.1 percent vs 2.1 percent). On the other hand, mining &amp; quarrying output extended losses (-9.0 percent vs -9.1 percent), weighed down by metal ores (-22.8 percent vs 4.7 percent) and coal &amp; lignite (-7.9 percent vs -13.7 percent). On a seasonally adjusted monthly basis, industrial production rose 2.0 percent, after an upwardly revised 0.4 percent gain in November. Considering the full year, industrial output advanced 10.7 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/producer-prices-change </td>
   <td style="text-align:left;"> 2022-01-27 00:08:00 </td>
   <td style="text-align:left;"> Russia Producer Inflation Eases From 5-Month High </td>
   <td style="text-align:left;"> Russia's producer inflation eased to 28.5 percent year-on-year in December of 2021 from a 5-month high of 29.2 percent hit in the previous month. Costs rose at a slower pace for mining (59.2 percent vs 62.3 percent) and manufacturing (23.5 percent vs 23.7 percent). Meanwhile, the prices of utilities rose at a faster pace (5.8 percent vs 2.9 percent). On a monthly basis, producer prices rose 0.8 percent, accelerating from a 0.4 percent increase one month earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/26/politics/mitch-mcconnell-donald-trump-gop/index.html </td>
   <td style="text-align:left;"> 2022-01-26 23:57:23 </td>
   <td style="text-align:left;"> Mitch McConnell is trying to save Republicans from Donald Trump. It's not working. - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Mitch McConnell is a very careful politician. He rarely acts rashly or speaks without thinking first. Which means that when he does talk, it's usually worth paying very close attention to what he says.                                                                                                                                                                                            , Which brings me to an interview CNN's Manu Raju and Alex Rogers conducted with McConnell, the Senate minority leader, about Republican prospects in the 2022 midterms -- and, in particular, former President Donald Trump's ongoing insistence that the 2020 presidential election was stolen from him.                                                                                                   , "It's important for candidates to remember we need to respect the results of our democratic process unless the court system demonstrates that some significant fraud occurred that would change the outcome," McConnell said.                                                                                                                                                                              , Which is 100% correct. There is simply no evidence -- at the state or national level -- that suggests that the results of the 2020 election were fraudulent. None.                                                                                                                                                                                                                                         , And McConnell is right that focusing on the idea of a stolen past election is the surest way to lose a future election. Elections are usually decided by a candidate's vision for what comes next, not by dwelling on what has already happened.                                                                                                                                                           , The problem? Lots of Republican Senate candidates are willingly accepting Trump's Big Lie about the 2020 election as a way to curry favor with the GOP base.                                                                                                                                                                                                                                               , "I need to say something that I get attacked by the media for saying this, I get attacked by my opponents for saying this, but I believe it very strongly and so I want to say it up here: I believe the election was stolen from Donald J. Trump," Josh Mandel, the Republican front-runner in the Ohio Senate race, said at a debate last year.                                                          , J.D. Vance, an author who is competing against Mandel for the GOP Senate nomination in Ohio, said last year that "there were certainly people voting illegally on a large-scale basis." In that same race, wealthy businessman Bernie Moreno ran an ad in which he says: "President Trump says the election was stolen, and he's right."                                                                   , Eric Greitens, the current leader of a crowded Republican field in the Missouri Senate race, traveled to Arizona twice as that state conducted a phony audit of the presidential vote. "We need to have audits across the country because we must get election integrity back," Greitens said.                                                                                                             , Rep. Billy Long, who is running in that same Missouri GOP primary, recently released a new ad in which he says this: "Democrats rigged the election. Now we have Biden and the far-left crazies letting inflation rise faster than an auctioneer rattling off numbers," Long says. "I'm running for Senate to stop the insanity, stop the wokeness, and stop the Democrats from stealing another election.", Rep. Ted Budd, the Trump-endorsed candidate in the North Carolina Senate race, voted against certifying the Electoral College results on January 6, 2021. As did Alabama Rep. Mo Brooks, another Trump-backed candidate in the state's open Senate contest.                                                                                                                                                , There's more. Lots more. But you get the idea: Supporting the Big Lie has become a sort of litmus test within the Republican Party.  If you say the 2020 election was stolen, you are immediately identified as a Trumpist. If you side with facts and reject the stolen election narrative, you risk being labeled a RINO ("Republican in Name Only") who will be targeted by the former president.       , That's the harsh political reality McConnell is up against. He can talk all day about the need to "respect the results of our democratic process" but the truth is that a whole lot of Republican Senate candidates have already gone all in on the Big Lie. And McConnell isn't changing any of their minds.                                                                                              , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-01-26 23:54:00 </td>
   <td style="text-align:left;"> Dollar Edges Higher Ahead of Fed </td>
   <td style="text-align:left;"> The dollar index strengthened to a 3-week high of 96.2 on Wednesday as traders await the Fed monetary policy decision later in the day for more clues on how much and how quickly interest rates will be raised. The odds are rising the Fed will need to tight monetary policy faster than anticipated, while other central banks around the world seem more reluctant in raising borrowing costs. Meanwhile, rising geopolitical tensions also buoyed the safe-haven dollar, with US president Joe Biden threatening to sanction Vladimir Putin if he orders an invasion of Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/fcx:us </td>
   <td style="text-align:left;"> 2022-01-26 23:52:23 </td>
   <td style="text-align:left;"> Freeport-McMoran earnings below expectations at 0.96 USD </td>
   <td style="text-align:left;"> Freeport-McMoran (FCX) released earnings per share at 0.96 USD, compared to market expectations of 0.97 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-26 23:50:00 </td>
   <td style="text-align:left;"> Oil Surges to 2014 Highs </td>
   <td style="text-align:left;"> WTI crude futures extended gains to above $87 a barrel on Wednesday, the highest since October 2014 in line with a broader market recovery and as investors remain concerned about supply and possible energy disruptions if Russia invades Ukraine. In the US, EIA data showed US crude inventories unexpectedly increased for a second straight week but crude stocks at the Cushing, Oklahoma delivery hub edged down. Meanwhile, OPEC+ is likely to stick with the existing policy and raise the March crude output by 400K bpd when it meets next week, Reuters reported. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/26/cfpb-signals-crackdown-on-hidden-fees-for-banks-credit-cards.html </td>
   <td style="text-align:left;"> 2022-01-26 23:41:44 </td>
   <td style="text-align:left;"> Consumer watchdog signals broad crackdown on hidden fees for banks, credit cards </td>
   <td style="text-align:left;"> , The Consumer Financial Protection Bureau on Wednesday signaled a broad crackdown on hidden and excessive fees charged by banks, mortgage lenders and other financial entities.                                                                                                                                             , The federal agency, created in the wake of the 2008 financial crisis, is seeking consumers' input on so-called junk fees associated with their bank, credit union, prepaid or credit card account, mortgage, loan or payment transfers.                                                                                    , Such experiences related to a product or service include: Fees people thought were covered by its baseline price; unexpected fees; fees that seemed too high; and fees where it was unclear why they were charged, according to the agency's announcement Wednesday.                                                       , More from Personal Finance:Millions of taxpayers still waiting on last year's tax refundSEC chair eyes tougher cyber rules to protect investors against hackersAid Americans may get from a smaller Build Back Better                                                                                                      , There's been an "explosion" in junk fees, such as overdraft fees charged by banks, late fees levied by credit-card companies, and closing fees when buying a home, CFPB Director Rohit Chopra said during a press call Wednesday morning.                                                                                  , "In many cases, junk fees act like penalties" instead of compensation for a legitimate service, according to Chopra, who was appointed by President Joe Biden. They also make it difficult for consumers to choose a product or service since they're unaware of its true cost upfront, Chopra said.                       , The CFPB will use public comments to target new rules, issue guidance to firms, and focus its supervisory and enforcement resources, the agency said. The comment period ends March 31.                                                                                                                                    , "Today, with our request for public comment on junk fees, we are beginning the process of ending banks' reliance on these exploitative income streams," making costs more transparent and perhaps saving American consumers billions of dollars, Chopra said.                                                              , Richard Hunt, the president and CEO of the Consumer Bankers Association, a trade group representing retail lenders, said the CFPB's initiative was an attempt to "fearmonger," calling it "fuzzy math at its best and political theater at its worst."                                                                     , "The reality is, despite their claims to the contrary, overdraft fees as a percent of total revenue across the industry made up less than 2% in 2019," Hunt said in an emailed statement. "The Bureau has a responsibility to communicate with clarity and precision — not with overblown rhetoric to attack one industry.", Credit card companies earned $14 billion in "punitive" late fees in 2019, while banks earned $15 billion in overdraft and non-sufficient-funds fees, the CFPB estimates.                                                                                                                                                   , The initiative is also a response to Biden's call to spur more competition in the U.S. economy, according to Chopra, who framed high, inflated fees as an anti-competitive practice that has grown with industry consolidation.                                                                                            , "Capitalism without competition is — is not capitalism; it's exploitation," Biden said Monday at a meeting with the White House Competition Council.                                                                                                                                                                       , Hunt pushed back on the notion of the banking industry being anti-competitive.                                                                                                                                                                                                                                             , "The well-regulated, well-supervised banking industry is also among the most competitive in the world," he said. "Consumers benefit from the ability choose one of the nation's nearly 5,000 banks to meet their financial needs."                                                                                         , Some banks like Bank of America and Capital One have recently moved to eliminate or reduce overdraft fees on their own.                                                                                                                                                                                                    , "This is progress, but it is not enough," Chopra said of some large banks adopting more consumer-friendly policies.                                                                                                                                                                                                        , It's also somewhat unclear as to how effectively the CFPB will be able to regulate the fees that lenders charge. The public input will better help the agency target its efforts, according to a senior CFPB official speaking on background.                                                                              , "We do have substantial authorities, rulemaking," the official said. "We're going to use our authorities as best we can."                                                                                                                                                                                                  , The CFPB is also soliciting public feedback from small business owners, non-profit organizations, legal aid attorneys, academics and researchers, state and local government officials, and financial institutions, including small banks and credit unions, it said.                                                      , The agency also maintains a separate complaint database related to all financial products and services.                                                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                     , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                     , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                           , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                           , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                         , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kenya/interest-rate </td>
   <td style="text-align:left;"> 2022-01-26 23:39:00 </td>
   <td style="text-align:left;"> Kenya Holds Key Interest Rate Steady at 7% </td>
   <td style="text-align:left;"> The central bank of Kenya retained its benchmark interest rate at 7% during its January 2022 meeting, as expected, to continue supporting the domestic recovery as inflation expectations remain well anchored. Policymakers noted that inflation eased to an 11-month low of 5.7% in December from 5.8% in November, mainly due to lower food prices, and it is expected to remain within the central bank’s target range of 2.5%-7.5%. Meanwhile, the recently released GDP data for the third quarter together with leading indicators confirm that the Kenyan economy rebounded strongly in 2021, following the easing of COVID-19 restrictions and the impact of government interventions. The economy is expected to remain strong in 2022, supported by the continued strong performance of the services sector, recovery in agriculture, and an improvement in global demand. The bank's Monetary Policy Committee, however, warned that there were elevated global risks with the potential to impact the domestic economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/crude-oil-stocks-change </td>
   <td style="text-align:left;"> 2022-01-26 23:34:05 </td>
   <td style="text-align:left;"> US Crude Stocks Unexpectedly Increase </td>
   <td style="text-align:left;"> US crude oil inventories unexpectedly expanded by 2.377 million barrels in the week ending January 21st, the largest increase since late October and compared to market forecasts of a 0.728 million barrel draw, data from the EIA Petroleum Status Report showed. Meanwhile, gasoline inventories rose by 1.297 million barrels, missing market expectations of a 2.548 million barrel increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-01-26 23:34:00 </td>
   <td style="text-align:left;"> Loonie Falls Slightly after BoC </td>
   <td style="text-align:left;"> The Canadian dollar weakened slightly to a 2-week low of 1.26 per USD, prompted by a strong US dollar as the Fed is expected to tight monetary policy faster than anticipated while the Bank of Canada disappointed some investors by leaving interest rates steady in its first 2022 meeting. The central bank however, signalled a rise in interest rates will happen soon, probably during the next meeting on March 2nd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/26/weather/noreaster-bomb-cyclone-weekend-storm/index.html </td>
   <td style="text-align:left;"> 2022-01-26 23:16:30 </td>
   <td style="text-align:left;"> Nor'easter forecast: A bomb cyclone with hurricane power will unleash snow this weekend - CNN </td>
   <td style="text-align:left;"> (CNN)Confidence is growing that a winter storm with the intensity of a hurricane, snow measured in feet and blizzard-like conditions will impact major Northeast cities this weekend.                                                                                                                                                                        , "The models continue to show a nor'easter with blockbuster potential for the weekend, mainly late Friday through Saturday," CNN meteorologist Brandon Miller says.                                                                                                                                                                                            , There are still questions about how much snow will pile up and how extreme winds will get.                                                                                                                                                                                                                                                                    , "Heavy snow is most likely in parts of New England," the Weather Prediction Center said Wednesday morning. "Heavy snow is still possible farther south along the East Coast, including the major I-95 metropolitan areas from New York City to Washington DC, but that is more uncertain at this time."                                                       , The National Weather Service in Boston on Wednesday afternoon issued a winter storm watch for eastern Massachusetts and Rhode Island, from Friday night until Saturday evening. Expected snowfall ranges from 8 to 16 inches, with wind gusts up to 60 mph.                                                                                                   , Other NWS offices have yet to issue watches due to the uncertainty.                                                                                                                                                                                                                                                                                           , Sign up for weather email alerts                                                                                                                                                                                                                                                                                                                              , The storm is expected to form in the Atlantic Ocean just off the coast of Georgia, then rapidly strengthen -- a process known as bombogenesis -- overnight Friday and track Saturday up the East Coast.                                                                                                                                                       , "Guidance indicates potential for this storm to undergo bombogenesis, meaning its central pressure drops at least 24 mb in 24 hours," the Boston weather service office said earlier, referring to the unit of pressure known as millibars. "This creates a very tight pressure gradient, meaning strong, potentially damaging winds will accompany the snow.", "This storm is likely to strengthen at a rate, and to an intensity, equivalent to only the most powerful hurricanes, so the high-end potential of this storm cannot be overstated. But with nor'easters, like in real estate, it will all come down to location, location, location," Miller said.                                                            , Bookmark this page for National Weather Service snow forecasts                                                                                                                                                                                                                                                                                                , Uncertainty in the forecast is pretty common more than 48 hours before a storm even has formed, as the Boston National Weather Service office noted Wednesday on Twitter.                                                                                                                                                                                     , "Well, the average model error at this time range (3 days out) is over 150 miles! For example, where will the rain/#snow line setup? 150 miles could range from Cape Cod, MA to New Haven, CT. Hence, still too early."                                                                                                                                       , Both forecast models predict this strengthening, but their storm tracks up the East Coast are different, changing what people could expect from Washington, DC, to Boston.                                                                                                                                                                                    , Compare forecast models and delay information                                                                                                                                                                                                                                                                                                                 , "For those that have been following along, I know you've heard it repeated to death, but the key message continues to be the same: guidance is trending favorably for a big storm, but the exact track remains uncertain," the Boston office said. "This track is what will tell us exactly where the greatest snow, wind, and coastal flooding concerns are.", A "farther offshore track of the low will decrease snow amounts while a track closer to shore will increase snow amounts and if the low gets close enough to the coast, a wintry mix will be possible for some eastern coastal sections (This is looking less and less likely)," said the New York office of the National Weather Service.                    , Blizzard conditions, coastal flooding are on the table                                                                                                                                                                                                                                                                                                        , While it's too early to pinpoint exact totals, it looks like the storm will hit all metro areas along Interstate 95 from Virginia to Maine starting Friday and through the day Saturday. Philadelphia, New York and Boston could get a foot of snow -- or much more.                                                                                          , Winds of 50 mph or more are likely throughout the Northeast, with even higher gusts possible, especially along the eastern coastlines. These strong winds combined with snow will create blizzard conditions.                                                                                                                                                 , "A closer track would also mean higher winds and potential for blizzard conditions near the coast," the weather service office in Philadelphia said.                                                                                                                                                                                                          , How to survive a blizzard                                                                                                                                                                                                                                                                                                                                     , A blizzard happens when snow combines with winds gusting over 35 mph for more than three hours and creates visibility of less than a quarter of a mile.                                                                                                                                                                                                       , "Significant coastal impacts are possible in the Northeast, including coastal flooding and beach erosion," the prediction center said.                                                                                                                                                                                                                        , The stronger the storm, the greater the surge of water along the coast will be. Timing also matters a lot.                                                                                                                                                                                                                                                    , "Coastal flooding is a concern thanks to astronomically high tides on Saturday," the Boston weather service office said. "The combination of strong northeast winds and high seas will bring storm surges that, if coinciding with high tide, would lead to minor or moderate coastal flooding."                                                              , The difference in storm timing -- even as few as six hours -- would make a massive difference in impact on coastal flooding and erosion concerns.                                                                                                                                                                                                             , One thing is sure: Meteorologists will be glued to computer forecast model runs all day Wednesday.                                                                                                                                                                                                                                                            , "Today's trends will certainly be important," the weather office in Philadelphia said. "Sampling will be steadily improving, and 'big picture' model solutions should start converging in the next 12 to 24 hours."                                                                                                                                           , In layman's terms: We will know more details Thursday.                                                                                                                                                                                                                                                                                                        , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lumber </td>
   <td style="text-align:left;"> 2022-01-26 23:15:00 </td>
   <td style="text-align:left;"> Lumber at 5-Week Low </td>
   <td style="text-align:left;"> Chicago lumber futures traded near $1,000 per thousand board feet, the lowest since December 21st, as demand collapsed amid soaring costs and transports bottlenecks. Since the beginning of the year, the wood prices have been buoyed by supply disruptions and a hot housing market, however, as the prices have touched multi-week highs an index of framing composite has more than tripled which represented an additional $20,000 of an average new home price, according to the National Association of Home Builders. Also, labor shortage and transportation woes are making it harder to get building supplies, negatively impacting the demand as it is prompting builders to postpone or cancel projects. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-01-27 08:44:15 UTC +8

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
   <td style="text-align:left;"> 2022-01-27 08:43:51 </td>
   <td style="text-align:left;"> $SPY Gap down tomorrow at the open and buy the pivots.. thats the hope </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:43:14 </td>
   <td style="text-align:left;"> $SPY So what? Do we just keep selling every day until the next fed meeting because they are going to raise rates by .25 lol This is a joke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:43:09 </td>
   <td style="text-align:left;"> $SPY funny if red all the bears are so loud.  If green all bulls are so noisy . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:54 </td>
   <td style="text-align:left;"> $SPY / $QQQ Was that the bottom in the market? Heres some evidence that points strongly to &amp;gt; not yet! 
 
Trade ideas also in $AMD $SBUX  
 
https://youtu.be/LEox6uuMhdc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:52 </td>
   <td style="text-align:left;"> $SPY the markets gonna drop 15 percent for sure to crazy matter of weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:45 </td>
   <td style="text-align:left;"> $SPY loves bouncing off vwap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:38 </td>
   <td style="text-align:left;"> $SPY  
We know Biden is no fan of the stock market, from his comments I think he sees it as a rich mans playground and from JPOW&amp;#39;S comments today I think there&amp;#39;s a policy change from the top. No more accommodation from the FED. No more free money. I guess Biden doesn&amp;#39;t stock market money because he and Hunter get theirs from China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:37 </td>
   <td style="text-align:left;"> $SPY VIX is about to start an uptrend ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:21 </td>
   <td style="text-align:left;"> $SPY every hour I check on here and it&amp;#39;s either we&amp;#39;re going to zero or going to the moon. Make up your god dang minds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:20 </td>
   <td style="text-align:left;"> $SPY few black swan events pending. Als you have to expect the big boys to throw tantrum until Fed turns dovish again. Hawkish Fed was the last thing they wanted, and will keep market fucking volatile until end of March. 380PT by February. $tsla is focusing on fucking robots for year 2022. We know everything now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:19 </td>
   <td style="text-align:left;"> $SPY To face unlikely market events? What this actually says is Robinhood is ready if investors start getting liquidated. 
They even know. 🎯🧑‍🎓😊✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:13 </td>
   <td style="text-align:left;"> $SPY real chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:11 </td>
   <td style="text-align:left;"> $SPY Does the word consolidation still mean anything 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:07 </td>
   <td style="text-align:left;"> $SPY No more Fed shit now it is 🆙 🆙 🆙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:42:02 </td>
   <td style="text-align:left;"> $SPY I have a newbie question here seeing as though I only have 21 years of trading experience: 
What does it mean when the S &amp;amp; P drops below the 200MA and gets firmly rejected at the retest? 
should I BTMFD? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:41:59 </td>
   <td style="text-align:left;"> $SPY feb/March we see the blow off top. Then correction through summer with Christmas rally into the end of the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:41:38 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m getting my sea legs back. 
https://www.youtube.com/watch?v=_fcPfaMpSeE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:41:28 </td>
   <td style="text-align:left;"> $SPY F the Spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:41:26 </td>
   <td style="text-align:left;"> $SPY 
government supplement chip foundry in USA
same turds that off shored the technology for 40 years ..pay .70 cents a hour
now we pay up again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:41:16 </td>
   <td style="text-align:left;"> $SPY is this the future? We are reading tea leaves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:40:58 </td>
   <td style="text-align:left;"> $SPY well maybe if u wait a year u can be up another 12 percent like last year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:40:54 </td>
   <td style="text-align:left;"> $SPY oh no </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:40:34 </td>
   <td style="text-align:left;"> $SPY more red tomorrow, and more red all the way down to $400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:40:31 </td>
   <td style="text-align:left;"> $SPY tesla did not rip , Microsoft never ripped. I would be very  careful. If Apple doesn’t rip that’s 3 of the major holdings here in the spy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:39:58 </td>
   <td style="text-align:left;"> $SPY Take another look at that RSI. Giddy bears finally made a couple bucks, but you are seriously pressing your luck now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:39:57 </td>
   <td style="text-align:left;"> $SPY 

I mean like what in the literal fuck are you guys doing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:39:53 </td>
   <td style="text-align:left;"> $SPY to the losers spouting their opinions about what the market will do (seriously just dollar cost average and keep cash ready if you’re that scared) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:39:47 </td>
   <td style="text-align:left;"> $SPX $SPY should have alot more clarity in the next few sessions. unsure if we get a backtest of white </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:39:43 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX Now all we need is netflix to stop being stubborn and cmon down to join the party 🔪🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:39:42 </td>
   <td style="text-align:left;"> $SPY  Good times ahead 
https://www.labelsoftwaredirect.com/2022/01/27/let-the-good-times-roll/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:39:29 </td>
   <td style="text-align:left;"> $SPY living on small fry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:39:27 </td>
   <td style="text-align:left;"> $SPY I’m just so happy there’s still ways to make money when economy is collapsing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:59 </td>
   <td style="text-align:left;"> $SPY 
economic boom
still have 2009 crutches not unwound
Will unwind ..trust me.transitory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:59 </td>
   <td style="text-align:left;"> $SPY 
This market is sick and can’t find its way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:58 </td>
   <td style="text-align:left;"> $SPY the accumulation of big techs ah of earnings has to be a signal to somebody else </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:58 </td>
   <td style="text-align:left;"> $SPY Boom. End of discussion. @PelkTwo @MikeTython @TraderLeibniz @DoomerStonks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:45 </td>
   <td style="text-align:left;"> $SPY hold cash till 350 folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:36 </td>
   <td style="text-align:left;"> $SPY 350 !!! Keep your cash will be much cheaper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:36 </td>
   <td style="text-align:left;"> $SPY $DJI $QQQ thought I would share… this demonrat along with Yellen and JP need to goooooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:19 </td>
   <td style="text-align:left;"> $SPY Honest question. Who would want to fight a war for Senile Biden or these politicians? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:18 </td>
   <td style="text-align:left;"> $SPY BTC clawing it’s way back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:16 </td>
   <td style="text-align:left;"> $SPY I am only bullish for short term swings...obviously it will correct as they attempt deflation...but earnings will kick the ball a little up so i can collect that premium </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:08 </td>
   <td style="text-align:left;"> $SHOP  WILL TOUCH 1,000  BY fRIDAY  🔥🔥🚀🚀🚀 
. 
$SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:38:04 </td>
   <td style="text-align:left;"> $SPY Why did the markets fall today?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:37:41 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:37:19 </td>
   <td style="text-align:left;"> $SPY bears are going to be very quiet tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:36:55 </td>
   <td style="text-align:left;"> $SPY We don&amp;#39;t even have a leader who can handle his own country.. Thanks Joe.  Market is toast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:36:54 </td>
   <td style="text-align:left;"> $SPY World War 3 coming.. Thanks biden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:36:53 </td>
   <td style="text-align:left;"> $SPY rug pull&amp;#39;s green, I mean futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:36:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $JD $AMZN  
$BABA KIDDOS, keeping money for real deals  
$75 next stop…Delisting news will take it sub $ 50 … 
….corruption punishment 20-30% intraday drop…  
..ANT IPO pennies on dollar 30-40% drop…  
 …National security investigation conclusion 20-35% unless punishment is direct delisting…  
…china market crash 25-45% down… 
…Taiwan aggression…20-40% in matter of few days… 
 
KIDDOS, keeping money for real deals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:36:39 </td>
   <td style="text-align:left;"> $SPY Listen to Sherry... 200 soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:36:26 </td>
   <td style="text-align:left;"> $SPY now-a-days nobody cares about N.Korea’s missile drama. Gold didn’t even notice it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:36:21 </td>
   <td style="text-align:left;"> $SPY Why did the markets tank? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:36:03 </td>
   <td style="text-align:left;"> $SPY I suspect Gme begins to siphon from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:35:58 </td>
   <td style="text-align:left;"> $SPY $qqq $labu latex6a20c0038cadea45cd95f10184cf7068$$7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:35:43 </td>
   <td style="text-align:left;"> $SPY bulls are delusional 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:35:35 </td>
   <td style="text-align:left;"> $SPY Market killed Hollywood and OFF apparently. Dam, miss them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:35:34 </td>
   <td style="text-align:left;"> $TSLA you got Hawkish Fed. Massive geo political tension with NK, China, and Russia... supply chain constraints everywhere, and only just covered omicron variant with 500 more potent variants to come. Bond is surging and only pussy boy Ackman thought he bought the best Netflix dip after crying world end. $nflx $SPY $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:35:30 </td>
   <td style="text-align:left;"> $SPY imagine being bullish right now.. Nothing at all is signaling a bottom in sight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:35:00 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $TSLA $BA 
👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:34:50 </td>
   <td style="text-align:left;"> $SPY  gotta love rug pull powell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:34:47 </td>
   <td style="text-align:left;"> $SPY damn got quiet in here LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:34:43 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ Rumor has it....Market is fixed 
$AMZN $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:34:38 </td>
   <td style="text-align:left;"> $SPY Stop it already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:34:36 </td>
   <td style="text-align:left;"> I know he was hawkish today but there was a key point…”priced in” this was his answer to market and rate hikes. Most bullish I’ve been in months. Markets usually price out 6-9 months in advance. This lines up with how badly growth has been sold off $QQQ $IWM $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:34:34 </td>
   <td style="text-align:left;"> $SPY tomorrow we reclaim $420 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:34:03 </td>
   <td style="text-align:left;"> OH MY😲 I still can&amp;#39;t believe how perfectly I caught this trade $SPY
Traders will understand the feeling. Also gains are not bad $34k 🔥🤭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:34:02 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:33:54 </td>
   <td style="text-align:left;"> $SPY this is so unpredictable lately. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:33:51 </td>
   <td style="text-align:left;"> $SPY Yep. There’s a jungle cat in the bathroom. @im_back_bois @MikeTython </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:33:50 </td>
   <td style="text-align:left;"> $SPY good evening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:33:40 </td>
   <td style="text-align:left;"> $SPY bulls 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:33:18 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:33:17 </td>
   <td style="text-align:left;"> $SPY Ukraine tensions, fed moving along with cuts; 50/50 we limit down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:33:03 </td>
   <td style="text-align:left;"> $SPY Fuck it, I&amp;#39;m buying puts for $appl earnings..... because I hate Appl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:33:02 </td>
   <td style="text-align:left;"> $SPY was about to sell calls but it.dropped now I&amp;#39;m waiting to sell some.puts still not sure how market is reacting to the dip sht  powell that said cya in March what an idiot he is he should of just said qe 4ever which is what I heard but idk what market thinks yet just gambling 🎰 in this casino cuz I&amp;#39;m addicted to gambling  almost seems like they are pinning it around 4350 because it keeps.finding it&amp;#39;s way back there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:32:56 </td>
   <td style="text-align:left;"> $SPY how those futes going for y’all bulls hmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:32:56 </td>
   <td style="text-align:left;"> $SPY does a restaurant think you can put more cheese on pasta to hide the fact that you didn&amp;#39;t cook it al dente? Gtfoh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:32:53 </td>
   <td style="text-align:left;"> $SPY 😂😂 @im_back_bois @MikeTython </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:32:53 </td>
   <td style="text-align:left;"> $SPY everyone got out on those quick pumps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:31:57 </td>
   <td style="text-align:left;"> $spy with the vix where it is , you should expect wild swings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:31:55 </td>
   <td style="text-align:left;"> $SPY shorting WMT TGT USFD CNI MRTN SYY LOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:31:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES SLIPPIN DIPPIN AND DRIPPIN SCOTTIE PIPPEN 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:31:04 </td>
   <td style="text-align:left;"> $AAPL ...$150...Is quite possible if rejection continues $QQQ $TQQQ $SPY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:31:01 </td>
   <td style="text-align:left;"> $SPY yesterday might’ve been green, today might’ve green and perhaps tomorrow, but you Bulls like I know, your fucked!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:30:56 </td>
   <td style="text-align:left;"> $SPY  Ending these mandates could save us from higher inflation due to supply constraints 🧐

https://www.yahoo.com/finance/m/798b8e50-bc76-3556-a4a6-0bc37cdcead3/biden-administration.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:30:44 </td>
   <td style="text-align:left;"> $QQQ $SPY netflix dump gives me confidence that bubble is bursting and dump is coming. It was the first to crack and soon the others will too. They can’t dump them all at once or it’ll look fishy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:30:35 </td>
   <td style="text-align:left;"> $SPY they should make a 10x ETF for the major indexes. 

That way you can make legit gains if you play it right. 

The options on that would move nicely. 10% gains on stock price movement on a 200$ etf... Juicy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:30:31 </td>
   <td style="text-align:left;"> $SPY massive short squeeze if we go up in morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:30:15 </td>
   <td style="text-align:left;"> $SPY bye bye green. there is not a bullish case for a fucking thing rn! pay me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:30:03 </td>
   <td style="text-align:left;"> $SPY  the biggest experiment in the history of America has gone very badly . The largest fed balance sheet in history . The biggest inflation in 40 years . The bubble and the fake market has caught up to reality . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:29:55 </td>
   <td style="text-align:left;"> $SPY vix monthly. Peace out bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:29:54 </td>
   <td style="text-align:left;"> $SPY commodities up, eastern markets up. we Gucci. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:29:54 </td>
   <td style="text-align:left;"> $QQQ $SPY $MSFT $AMZN  
 
$BABA $75 next stop…Delisting news will take it sub $ 50 
….corruption punishment 20-30% intraday drop… 
..ANT IPO pennies on dollar 30-40% drop… 
 …National security investigation conclusion 20-35% unless punishment is direct delisting… 
…china market crash 25-45% down… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:29:41 </td>
   <td style="text-align:left;"> $SPY  park your money in and ETF and wait it out. 2022 is going to be nightmarish for stock pickers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:29:31 </td>
   <td style="text-align:left;"> $SPY $DWAC Failing Kamala hates her white house job, racist and sexist Biden will probably make her a supreme court justice to give her a graceful exit from the VP job and discriminate against all men and white women while he’s at it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:29:30 </td>
   <td style="text-align:left;"> Slight dip in futures $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:29:24 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:29:09 </td>
   <td style="text-align:left;"> $SPY   Tomorrow will make TWO DAYS IN A ROW - the bears got phucked, holding PUTS overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:29:02 </td>
   <td style="text-align:left;"> $SPY yeah im experienced trader. rune scimmy 25k each </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:28:57 </td>
   <td style="text-align:left;"> $SPY Fed Chair Jerome Powell: Inflation has persisted longer than we thought https://youtu.be/uvd6vEttDK0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:28:53 </td>
   <td style="text-align:left;"> $SPY I called the 20% down today and was accurate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:28:44 </td>
   <td style="text-align:left;"> $SPY futes rippin.. no .. no no they’re not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:28:39 </td>
   <td style="text-align:left;"> $SPY bears thinking futes gonna be red , lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:28:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL tsla failed to amaze the crowd. Rate hike coming! Aapl er drops as usual. Hahaha bears will linger. Daddy joe and daddy jpow wont spoil you anymore. 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:28:38 </td>
   <td style="text-align:left;"> $SPY $420 EOW dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:28:23 </td>
   <td style="text-align:left;"> $SPY okay bears added the jet fuel today, we’re ready. 🤝🖨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:28:21 </td>
   <td style="text-align:left;"> $SPY Bears are delayed just like everyone from tesla in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:28:09 </td>
   <td style="text-align:left;"> $SPY Karma now it’s the bears turn to eat… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:28:04 </td>
   <td style="text-align:left;"> $SPY Just need another higher high to continue the uptrend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:55 </td>
   <td style="text-align:left;"> $SPY higher we go! Doomsday no more..recession cancelled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:52 </td>
   <td style="text-align:left;"> $SPY Every time I see a bull say the word long-term I lose a couple of brain cells </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:48 </td>
   <td style="text-align:left;"> $SPY your money😂😂😂 my money now!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:46 </td>
   <td style="text-align:left;"> $SPY them tax cuts would have been very useful right about now, wouldn’t they. Good thing we had them when the economy was already on fire. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:41 </td>
   <td style="text-align:left;"> $SPY I’ve seen all I needed to see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:40 </td>
   <td style="text-align:left;"> $SPY 
Dr.Powell noted omnicron
what is that??
a chip company?? I bet his crew is buying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:35 </td>
   <td style="text-align:left;"> $SPY I hope you bought the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:34 </td>
   <td style="text-align:left;"> $QQQ $SPY everyone would be rich if we all agreed to keep buying forever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:33 </td>
   <td style="text-align:left;"> $SPY #rejected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:24 </td>
   <td style="text-align:left;"> $SPY Fuck you bears quit stealing our money motherfuckers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:11 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Look at this prediction 🤷🏼‍♂️ I don&amp;#39;t remember if any of the indexes hit 3% but I was close ..... tomorrow we jump off a clif </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:03 </td>
   <td style="text-align:left;"> $MSFT is this a bullflag? $SPY 🤪 LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:02 </td>
   <td style="text-align:left;"> $SPY new variant of omicron? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:27:01 </td>
   <td style="text-align:left;"> $SPY I think bears are very fucking real and bulls are mad they bought the top of decades of market📉📉📉📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:26:53 </td>
   <td style="text-align:left;"> $SPY Lots of bulls hating on Biden, blaming Biden for the market etc. Why are you bullish and buying the &amp;quot;Biden market&amp;quot; then? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:26:51 </td>
   <td style="text-align:left;"> $SPY Higher Lows People lower Highs pay attention. In a bear market there can be the most bullish swings for the fences but it’s still getting walked down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:26:36 </td>
   <td style="text-align:left;"> $GOLD $SPY now-a-days nobody cares about N.Korea’s missile drama. Gold didn’t even notice it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:26:26 </td>
   <td style="text-align:left;"> $SPY thank you pig </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:26:21 </td>
   <td style="text-align:left;"> $SPY How is this market going to go higher without any stimulus?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:26:15 </td>
   <td style="text-align:left;"> $SPY Premarket pump and flush after open as usual. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:26:09 </td>
   <td style="text-align:left;"> $SPY let’s bounce tomorrow and continue the bs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:26:02 </td>
   <td style="text-align:left;"> $SPY it’s getting close to time, they’re almost drunk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:25:39 </td>
   <td style="text-align:left;"> $SPY $SHIB.X $$BTC.X  Bears here on these chatrooms are not actually real people. Cause Bears are not that stupid.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:25:21 </td>
   <td style="text-align:left;"> $SPY 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:25:10 </td>
   <td style="text-align:left;"> $SPY so much blood will spilled in this market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:25:03 </td>
   <td style="text-align:left;"> $SPY They bought the dip in futes. Holy fartballs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:25:02 </td>
   <td style="text-align:left;"> $DKNG $SPY $LRN $LCID 

The team is doing pretty well in times of uncertainty. Are you?

This weeks gains made using premium data at our fingertips! Come see for yourself! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:25:00 </td>
   <td style="text-align:left;"> $SOFI what a wild day in the markets $SPY $QQQ $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:24:52 </td>
   <td style="text-align:left;"> $SPY $DJI $QQQ What&amp;#39;s up with all these bots with no followers , no DD, and no TA  if u make a bearish stance on a security they call u every name in the book? There is a winner and a loser on every side of the trade. Straight fukin inexperienced bent bag holders... do they not know if u r an emotional trader they will lose their whole unemployment check? Anyways call me what u want... IDGAF... my money not theirs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:24:51 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:24:40 </td>
   <td style="text-align:left;"> $SPY punch the bears! pow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:57 </td>
   <td style="text-align:left;"> $VIX $SPY Going back to 2000, the highest avg. reading in the VIX = 40.83. Translation: A VIX above 40.83 in any given year = long term opportunity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:57 </td>
   <td style="text-align:left;"> $SPY flat again? Great they kill put premium and call premium 🤙wonder if they will crash it on Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:55 </td>
   <td style="text-align:left;"> $SPY did we fill the gap yet?
I live easy money slam dunk trades!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:54 </td>
   <td style="text-align:left;"> $SPY lucky number $420 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:47 </td>
   <td style="text-align:left;"> $SPY  Depending on tomorrow I may take more of those lottos. Jan 31 type ish $460 C’s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:45 </td>
   <td style="text-align:left;"> $SPY futures are up but what the fuck are they buying lol. Tesla couldn’t even rip with a good beat. If Apple doesn’t rip its a wrap on this index  for awhile. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:44 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA Jerome is 1000% Ari Spyros </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:42 </td>
   <td style="text-align:left;"> $QQQ $SPY just got off the phone with Powell. His exact words were “I’m gonna bankrupt the bulls” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:39 </td>
   <td style="text-align:left;"> $SPY truly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:33 </td>
   <td style="text-align:left;"> $SPY My game plan for tomorrow, take a strangle position of +$6 calls and -$6.00 puts if it goes to up 1% then exit and add accordingly. Happy hunting y&amp;#39;all. Have a great night. 🎯😊✌️🧑‍🎓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:32 </td>
   <td style="text-align:left;"> $SPY we’re green in AM, gonna be red in PM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:32 </td>
   <td style="text-align:left;"> $SPY how are my 436s for Friday looking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:26 </td>
   <td style="text-align:left;"> $SPY close the fucking market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:16 </td>
   <td style="text-align:left;"> $SPY any bulls that watched Powell speak on inflation, I implore you to watch this. The mandate JUST started the 22nd. This has always been what worried me most. More than rates, more than russia, more than anything (for the market) and it seems Powell agreed. This hasnt even begun to affect us yet and inflation was already getting worse. https://youtu.be/-LlDGV1JtA8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:13 </td>
   <td style="text-align:left;"> $SPY strongest labor market possibly ever. So much demand it’s driving up inflation, but yet we drop like a ton of bricks on some bullshit speculation of interest rate hikes?!  tHe EnD iS nEaR… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:11 </td>
   <td style="text-align:left;"> $SPY should have bought that dip today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:08 </td>
   <td style="text-align:left;"> $SPY futures sellin off all night certainly… sleep well folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:06 </td>
   <td style="text-align:left;"> $SPY how is this up lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:06 </td>
   <td style="text-align:left;"> $SPY news flash inflation aunt gonna fix itself...(neither will Ukraine) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:03 </td>
   <td style="text-align:left;"> $SPY looks good to me! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:23:01 </td>
   <td style="text-align:left;"> $SPY bears r fuk because they gambles their life savings on worthless poots lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:22:53 </td>
   <td style="text-align:left;"> $SPY $HYG  the difference, between 80s inflation and now, in the 80s we had the coming of age of Silicon Valley and 40 years of technological innovation that changed economies around the word, now we just have inflation to support an economy that stopped growing on its own. Mortgage rates in the early 80s nearly 18% but inflation was high so people could afford them if their wage grows 15% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:22:47 </td>
   <td style="text-align:left;"> $SPY if I bought 10 $400 put contracts and it drops to $400 tomorrow how much will I make? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:22:47 </td>
   <td style="text-align:left;"> $SPY market going to hell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:22:40 </td>
   <td style="text-align:left;"> $SPY best place to be short is IWM. Second best is everywhere else </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:22:40 </td>
   <td style="text-align:left;"> $QQQ when the sell will stop $SPY $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:22:35 </td>
   <td style="text-align:left;"> $SPY yes range bound between 250-480 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:22:29 </td>
   <td style="text-align:left;"> $SPY oh boo hoo we might see 15 percent returns in instead of 30 this year 🤠🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:22:07 </td>
   <td style="text-align:left;"> $SPY Bears are so mad that Powell won&amp;#39;t crash the market.  
 
Better that idiot gambling bears lose their money than investors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:22:02 </td>
   <td style="text-align:left;"> $SPY market still listens to JPow? Liar exposed. Yet market still listens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:21:45 </td>
   <td style="text-align:left;"> $SPY bulls fell for it again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:21:38 </td>
   <td style="text-align:left;"> $SPY FUTES (insert here) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:21:32 </td>
   <td style="text-align:left;"> $SPY They bulls say they still want more🤣🤣🤣 I wonder what the greed gauge read!!🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:21:31 </td>
   <td style="text-align:left;"> $SPY did the exact same think last night futures are meaningless people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:21:30 </td>
   <td style="text-align:left;"> $QQQ $SPY OH GOD HIDE YOUR MONEY IN YOUR MATTRESS WE GOING DOWN 🐻🎪🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:21:28 </td>
   <td style="text-align:left;"> $SPY rangebound </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:21:25 </td>
   <td style="text-align:left;"> $SPY now I’m praying for gap ups to load more cheap poooots lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:21:17 </td>
   <td style="text-align:left;"> $SPY im dark pooling don’t mind me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:21:07 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL  Bought puts! Dont see going up after earnings. Why Elon sold if he had confidence? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:21:00 </td>
   <td style="text-align:left;"> $SPY 420.69 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:20:58 </td>
   <td style="text-align:left;"> $SPY Futes messing with you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:20:54 </td>
   <td style="text-align:left;"> $TSLA approximately 42 minutes to gtfo. Super hawkish Fed in awhile. Analyst PT downgrades, macro dumps, and north Korea shooting projectiles while Russia is ready to fuck up Ukraine. China waiting to swallow up Taiwan. 

And Biden said son of a bitch on live TV. Senile. $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:20:54 </td>
   <td style="text-align:left;"> $SPY Wow bulltrap ah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:20:52 </td>
   <td style="text-align:left;"> $SPY  Ready for any and every. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:20:48 </td>
   <td style="text-align:left;"> $SPY BULLS: FUTURES ARE UP .56% WHERE ARE THE BEARS!?!?

BEARS: FUTURES ARE DROPPING WHERE ARE THE BULLS?!?!

None of it matters this far before market open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:20:44 </td>
   <td style="text-align:left;"> $SPY c’mon bears , -10% correction is over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:20:13 </td>
   <td style="text-align:left;"> $QQQ $SPY nobody even wanted the fed. Just a bunch of rich people established themselves and figured out a way to have unlimited money and rob others </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:20:04 </td>
   <td style="text-align:left;"> $SPY the day candle looks very beary </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:20:02 </td>
   <td style="text-align:left;"> $AAPL $SPY gold down. we ripping tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:19:55 </td>
   <td style="text-align:left;"> $SPY people used to worried about identifying with Trump . Now I’m going to blast out all my friends who are Biden supporters. So embarrassing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:19:51 </td>
   <td style="text-align:left;"> They love to walk the market lower on Powell&amp;#39;s comments  
 
$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:19:42 </td>
   <td style="text-align:left;"> $SPY Bulls lost their legs and still going. Stop dip-buying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:19:27 </td>
   <td style="text-align:left;"> $SPY just remember IF this is the beginning of the bear; we will have wild swings that will make it seem like its a bull...very common; nothing just crashes....the cycle can take 2 yrs if they choose to walk this market down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:19:24 </td>
   <td style="text-align:left;"> $TSLA $spy no confidence </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:19:21 </td>
   <td style="text-align:left;"> 2022 Tax Refund Dates (chart)... $TQQQ $QQQ $SPY $IWM 

https://www.cpapracticeadvisor.com/tax-compliance/news/21123177/2022-irs-income-tax-refund-chart-shows-refund-dates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:19:21 </td>
   <td style="text-align:left;"> $SPY https://www.youtube.com/watch?v=Qxxum5ungsA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:19:20 </td>
   <td style="text-align:left;"> $SPY Why are the futures green again? What the &amp;quot;good&amp;quot; news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:19:17 </td>
   <td style="text-align:left;"> $SPY anther sell off tomorrow ?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:19:16 </td>
   <td style="text-align:left;"> $SPY this pos is going bleed and then keep on bleeding … PPT phaggots can only slow it down… will be below 400 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:19:04 </td>
   <td style="text-align:left;"> $SPY short term this is bearish as fuck. I want 420 EOW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:18:53 </td>
   <td style="text-align:left;"> $SPY  our biggest PUT option play this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:18:45 </td>
   <td style="text-align:left;"> $SPY reversal? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:18:38 </td>
   <td style="text-align:left;"> $SPX $SPY $VIX $VXX  
 
If you been taught to trade vol properly, you relish markets like this.    
  
They don&amp;#39;t happen with this much delta velocity very often, so play it aggressively. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:18:31 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:18:22 </td>
   <td style="text-align:left;"> Join my Telegram for real time alerts
1/26 swing trade DELAYED
COMPLETELY IN

$SPY 455c 1/31
0.33-&amp;gt;
We want $440 at opening

$JD 75C 1/28
0.43-&amp;gt;
We want $73 at opening

$TTD 70C 1/28
0.16-&amp;gt;
We want $65 at opening

KWEB 36.92C 1/28
$0.17-&amp;gt;
We want $35.5 at opening 

Lotto Play
$JD 80C 1/28 
0.10-&amp;gt;
We want $73 at opening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:18:17 </td>
   <td style="text-align:left;"> $SPY  Our biggest Call options play of the week (so far) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:18:15 </td>
   <td style="text-align:left;"> $SPY All gains been wiped out fairly quickly ah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:18:09 </td>
   <td style="text-align:left;"> $SPY ...climbed a mountain and then I turned around. 
https://www.youtube.com/watch?v=x--yddOolRQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:18:03 </td>
   <td style="text-align:left;"> The best return $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:17:51 </td>
   <td style="text-align:left;"> Largest stocks $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:17:47 </td>
   <td style="text-align:left;"> $SPY macro says gtfo and stay away. But what do those guys know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:17:44 </td>
   <td style="text-align:left;"> $SPY give it to america, we need this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:17:39 </td>
   <td style="text-align:left;"> $SPY sell da rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:17:35 </td>
   <td style="text-align:left;"> $SPY my first fed meme. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:17:11 </td>
   <td style="text-align:left;"> $SPY bears pushin P </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:17:10 </td>
   <td style="text-align:left;"> $SPY 436 is key. if market gifts us a divergent low sub 420 you know what to do </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:16:54 </td>
   <td style="text-align:left;"> $SPY The kids aren&amp;#39;t okay.  

School district denies litter boxes for students identifying as &amp;#39;furries&amp;#39; https://nypost.com/2022/01/26/school-boss-debunks-rumor-that-they-provided-kitty-litter-for-furries/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:16:46 </td>
   <td style="text-align:left;"> $QQQ $SPY qqq going to 15,000 tomorrow spy going to 5,000
retail bulls so delusional!!
retail bulls - “you know why we going to hit those targets tomorrow? cuz microsoft did well, tesla did well! they saved us!” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:16:46 </td>
   <td style="text-align:left;"> $SPY bull r poor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:16:38 </td>
   <td style="text-align:left;"> $SPY powel threaded the needle if u ask me - s and p higher!!! (Until that RUS/UKR thing gets going...) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:16:26 </td>
   <td style="text-align:left;"> $SPY don’t tell the bears we’re starting a new trend here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:16:21 </td>
   <td style="text-align:left;"> $SPY have a felling tomorrow is the big crash. With the FOMC meeting and Russia and Ukraine saga it’s coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:16:18 </td>
   <td style="text-align:left;"> $SPY Jerome was like Biden up there Taking questions 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:16:17 </td>
   <td style="text-align:left;"> $SPY tell me again about dark pool DIX?  Anything over 47% and it’s how likely to be how green in how many days after 47%? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:16:14 </td>
   <td style="text-align:left;"> $SPY yes typing here effects the price so much yall some degens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:16:01 </td>
   <td style="text-align:left;"> $SPY There only seems to be 2 opinions here today, 400 eow or ath by next week. Hmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:15:53 </td>
   <td style="text-align:left;"> $QQQ $spy $IWM inflation will fuck the market. .look at oil..rents..user cars...supply chain...mfr jpow is too late </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:15:50 </td>
   <td style="text-align:left;"> $ROKU $NFLX $QQQ $SPY Ackman is very bad news for shorts. He is famous for squeezing the short money managers and getting them bankrupt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:15:40 </td>
   <td style="text-align:left;"> $SPY $QQQ time to bend over for bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:15:32 </td>
   <td style="text-align:left;"> $SPY Futes dripping! 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:15:29 </td>
   <td style="text-align:left;"> $SPY 300z next week don’t @ me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:15:23 </td>
   <td style="text-align:left;"> $SPY dropping again. Every time Powell speaks nothing but pain. Just like when Biden speaks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:15:11 </td>
   <td style="text-align:left;"> $SPY 

Every dip will be replaced by bigger dips. This market is toast for the foreseeable future. Yes, this time is different! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:15:04 </td>
   <td style="text-align:left;"> $SPY I think bears are done here. Am I reading the room! I said am I reading the room! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:59 </td>
   <td style="text-align:left;"> $SPY futes ripping? Asking for a friend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:57 </td>
   <td style="text-align:left;"> $SPY easy 400$ this week or by next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES HEADING FOR THE DUMPSTER HIDE YO CANOES MOVE TO CANADA LEARN FRENCH AWWWWWWW LAWWWWWD 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:54 </td>
   <td style="text-align:left;"> $SPY $UVXY $QQQ $SBUX $AMD 

The SPX 1982 Analogue:

- Decennial years
-Midterm years
- Year 2 Presidential cycles
- YoY CPI achieves 7%
- Post recessions
- Down January
- Bearish TOY Barometer signals
- Fed hikes 3 times in Q1
- Snap back rally to end January? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:54 </td>
   <td style="text-align:left;"> $SPY btd bro stocks only go.up bro </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:26 </td>
   <td style="text-align:left;"> $SPY I love seeing a Bear trap that’s actually a Bull trap pretending to be a Bear trap but it’s sorta a Bull trap…🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:24 </td>
   <td style="text-align:left;"> Daytrading the /ES is where it&amp;#39;s at for me now. Who&amp;#39;s trading Futures out here? New look: swing stocks, HODL crypto, and day trades future (/ES). +400% this week. $SPY 🚀🌕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:09 </td>
   <td style="text-align:left;"> $SPY Whales are having fun buying the dip... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:08 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/lK5Sdj08Lco </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:04 </td>
   <td style="text-align:left;"> $SPY $QQQ who would in a fight? Jay Powell or Gary Gensler? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:01 </td>
   <td style="text-align:left;"> $FAMI that after hours earnings report was a game changer.  I believe we will see much higher prices tomorrow.  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:00 </td>
   <td style="text-align:left;"> $SPY 400 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:00 </td>
   <td style="text-align:left;"> $spy $qqq after hours gains fading fast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:14:00 </td>
   <td style="text-align:left;"> $SPY ES working on the daily cross. Big momentum if it does, will gap spy up with a daily cross as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:13:53 </td>
   <td style="text-align:left;"> $SPY 

Inflation report tomorrow.  Can’t wait to see what a monthly increase of 20% in crude does to that.  Jesus Christ the FED is blind to inflation at best and completely corrupt at worst.  Probably a lot of both. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:13:37 </td>
   <td style="text-align:left;"> $SPY ..... what bull strap ........ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:13:26 </td>
   <td style="text-align:left;"> $SPY imagine all of us predict the crash at the same time...crazy times... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:13:24 </td>
   <td style="text-align:left;"> $SPY meanwhile Canada is about to be freed by truckers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:13:15 </td>
   <td style="text-align:left;"> $SPY this is like a copy of last night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:12:52 </td>
   <td style="text-align:left;"> $SPY Nobody does the market better than Team Muppets.  Nobody.
This has been proven* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:12:49 </td>
   <td style="text-align:left;"> $SPY pushin puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:12:43 </td>
   <td style="text-align:left;"> $SPY $QQQ i suspect 1-2% drop tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:12:42 </td>
   <td style="text-align:left;"> $SPY worst tech annual start?  Apple w nearly the most money on hand... Over $200 B.... Down nearly 10% ytd .. Not for long.... Other companies have super amounts of cash on hand... F.... Jpm.... many more... 

Market will bid!   🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:12:39 </td>
   <td style="text-align:left;"> $SPY the only way to fight inflation is to crash your portfolios. Awesome system we have </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:12:35 </td>
   <td style="text-align:left;"> $SPY no point in talking to them anymore, pet them learn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:12:34 </td>
   <td style="text-align:left;"> $SPY puts printed, might buy more tomorrow.. i know yall see that bear flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:12:12 </td>
   <td style="text-align:left;"> $SPY played $TSLA earnings for the first time 🤷🏼‍♂️ picked up 1,000 calls and  900$ puts..... and this POS traded flat after earnings lol I&amp;#39;m a bear 🐻  but now I&amp;#39;m hoping for a total financial crisis 😅 since the market maker going to kill my premium tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:12:05 </td>
   <td style="text-align:left;"> $SPY  
OK just a thought, if JPOW wanted to push the market down just how much more hawkish could he have been? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:11:57 </td>
   <td style="text-align:left;"> $SPY yikes I had A bad read EOD my puts probably gonna be toast 😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:11:55 </td>
   <td style="text-align:left;"> $SPY my god it’s gonna get ugly fast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:11:46 </td>
   <td style="text-align:left;"> $SPY How do I become Nancy Pelosi&amp;#39;s husband? Does she and her current husband have what you would call a &amp;quot;solid foundation&amp;quot;? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:11:43 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMC Aww shit Powell is loaded in puts. The man is clearly pushin Ps. Will  $TSLA be the opening salvo in a bear market?? https://youtu.be/9g08kucPQtE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:11:33 </td>
   <td style="text-align:left;"> $SPY Fact is I got like 2000 followers for making live option trades here. I made tons of people rich. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:11:18 </td>
   <td style="text-align:left;"> $SPY tsla and apple will take us to Kepler-186f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:11:06 </td>
   <td style="text-align:left;"> $SPY Powell basicly said he&amp;#39;s going to raise rates quicker than usual. Strong job market. High inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:10:46 </td>
   <td style="text-align:left;"> $SPY can you imagine the US trying to go to war with Russia in ukraine, and ukraine is like, no thanks we are russian now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:10:36 </td>
   <td style="text-align:left;"> $SPY Eating Thai. 
Thai after Thai.😂

https://music.apple.com/us/album/time-after-time/400603643?i=400603695 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:10:08 </td>
   <td style="text-align:left;"> $SPY just looks like covering AH.. still waiting to end of week to see if buyers really step in. still concerned about Russia/Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:09:48 </td>
   <td style="text-align:left;"> $AAPL will apple save the markets next? $SPY $QQQ 
microsoft.. now tesla… apple will be the lord savior! right?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:09:48 </td>
   <td style="text-align:left;"> $SPY $QQQ With the way the futures are going, the bears are gonna have a long sleepless night tonight lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:09:44 </td>
   <td style="text-align:left;"> $SPY high low and go. Do we get a return of the W, will bears hold puts again over the weekend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:09:42 </td>
   <td style="text-align:left;"> $SPY pump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:09:39 </td>
   <td style="text-align:left;"> $SPY honest question… the idea of Putin deployed 260k soldiers to Ukraine doesn’t bother any bulls? I just feel the risk at this point is so not worth the reward but that’s just me. And don’t try to tell me a fucking war is “already priced in” because that’s just comical </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:09:33 </td>
   <td style="text-align:left;"> $SPY futes ripping wow new ATH to celebrate Russia by eow 

Для Родины </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:09:29 </td>
   <td style="text-align:left;"> $SPY you’re welcome </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:09:26 </td>
   <td style="text-align:left;"> $SPY Is it safe to leave my bunker yet? Please advise… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:09:22 </td>
   <td style="text-align:left;"> $spy $qqq $tqqq it should all reverse by morning 
Cramer is pushing Dell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:09:08 </td>
   <td style="text-align:left;"> $SPY until $AAPL show it cards tomorrow, don’t do anything. I think big news tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:09:04 </td>
   <td style="text-align:left;"> $QQQ $SPY bull trap after trap after trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:08:45 </td>
   <td style="text-align:left;"> $SPY The next trend worldwide will be to relocate production back home. Whatever label you want to place on that. 
https://www.youtube.com/watch?v=Jn0VQjCbx10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:08:30 </td>
   <td style="text-align:left;"> $SPY Ugly? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:08:08 </td>
   <td style="text-align:left;"> $SPY not buying until i get shown otherwise. still showing bearish signs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:07:47 </td>
   <td style="text-align:left;"> $SPY short crude oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:07:44 </td>
   <td style="text-align:left;"> $QQQ $SPY don’t trust futures.  Powell confirmed today to all he is not looking to soothe the market.  Fed put is good as dead.  He was a lot more hawkish that I thought he’d be.  I flipped to short again, because why fight the Fed.  Market will need to suffer a lot more pain before it finds a floor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:07:35 </td>
   <td style="text-align:left;"> $SPY   Puts must print!    PMP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:07:31 </td>
   <td style="text-align:left;"> $SPY 450 minimum tomorrow then dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:07:05 </td>
   <td style="text-align:left;"> $SPY up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:07:05 </td>
   <td style="text-align:left;"> My &amp;quot;panic sell&amp;quot; breadth indicator reached an extreme last week only seen on late october 2020, covid crash and late december 2018. Before that readings were never that high. Market returns were very strong going forward after such high readings. $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:06:54 </td>
   <td style="text-align:left;"> $SPY $QQQ  we better test that monday low again or im going to be pissed  🩸🥵🤠 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:06:50 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:06:49 </td>
   <td style="text-align:left;"> $SPY fine.  6% green day TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:06:33 </td>
   <td style="text-align:left;"> $SPY Now watch BOND sell down to BUY stocks, Yields are going much better in long run in Equities. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:06:27 </td>
   <td style="text-align:left;"> $SPY Looks bullish, but very volatile. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:06:05 </td>
   <td style="text-align:left;"> $SPY Guys the Spy is telling us to be very be careful.  Another good catch  are the Pre-IPOs There is one called &amp;#39;&amp;#39;ADDEPAR&amp;#39;&amp;#39; They are in Fintech, It&amp;#39;s a Pre-IPO.  They just signed a huge contract.  I placed a  video below i will also place a link for Pre-IPO access.   

Pre-IPO access
https://investors.be4ipo.net/get-access2/

Video
https://youtu.be/fWOvNJC1chA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-27 08:06:01 </td>
   <td style="text-align:left;"> $SPY up up up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:43:53 </td>
   <td style="text-align:left;"> $QQQ Probably see a bounce going into Friday. Crazy amount of fear out there, they will burn the puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:43:37 </td>
   <td style="text-align:left;"> $QQQ futes diiiiipppppinnng </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:42:55 </td>
   <td style="text-align:left;"> $QQQ My $330 puts 😻😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:42:54 </td>
   <td style="text-align:left;"> $SPY / $QQQ Was that the bottom in the market? Heres some evidence that points strongly to &amp;gt; not yet! 
 
Trade ideas also in $AMD $SBUX  
 
https://youtu.be/LEox6uuMhdc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:42:26 </td>
   <td style="text-align:left;"> $QQQ - JP Giveth and JP taketh away 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:38:36 </td>
   <td style="text-align:left;"> $SPY $DJI $QQQ thought I would share… this demonrat along with Yellen and JP need to goooooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:38:08 </td>
   <td style="text-align:left;"> $SHOP  WILL TOUCH 1,000  BY fRIDAY  🔥🔥🚀🚀🚀 
. 
$SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:36:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $JD $AMZN  
$BABA KIDDOS, keeping money for real deals  
$75 next stop…Delisting news will take it sub $ 50 … 
….corruption punishment 20-30% intraday drop…  
..ANT IPO pennies on dollar 30-40% drop…  
 …National security investigation conclusion 20-35% unless punishment is direct delisting…  
…china market crash 25-45% down… 
…Taiwan aggression…20-40% in matter of few days… 
 
KIDDOS, keeping money for real deals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:35:58 </td>
   <td style="text-align:left;"> $SPY $qqq $labu latex6a20c0038cadea45cd95f10184cf7068$$7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:35:34 </td>
   <td style="text-align:left;"> $TSLA you got Hawkish Fed. Massive geo political tension with NK, China, and Russia... supply chain constraints everywhere, and only just covered omicron variant with 500 more potent variants to come. Bond is surging and only pussy boy Ackman thought he bought the best Netflix dip after crying world end. $nflx $SPY $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:35:07 </td>
   <td style="text-align:left;"> $QQQ fed has turned the market into a bag of nerves. just a couple words and stocks go bonkos. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:34:51 </td>
   <td style="text-align:left;"> $QQQ  I’m glad I kept my $iau contract I believe the market set up a nice bear trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:34:43 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ Rumor has it....Market is fixed 
$AMZN $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:34:36 </td>
   <td style="text-align:left;"> I know he was hawkish today but there was a key point…”priced in” this was his answer to market and rate hikes. Most bullish I’ve been in months. Markets usually price out 6-9 months in advance. This lines up with how badly growth has been sold off $QQQ $IWM $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:33:50 </td>
   <td style="text-align:left;"> $QQQ watch it...you know what this looks like surely? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:31:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES SLIPPIN DIPPIN AND DRIPPIN SCOTTIE PIPPEN 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:31:04 </td>
   <td style="text-align:left;"> $AAPL ...$150...Is quite possible if rejection continues $QQQ $TQQQ $SPY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:30:44 </td>
   <td style="text-align:left;"> $QQQ Up overnight but the over chart still bearish. No faith in a turn around just yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:30:44 </td>
   <td style="text-align:left;"> $QQQ $SPY netflix dump gives me confidence that bubble is bursting and dump is coming. It was the first to crack and soon the others will too. They can’t dump them all at once or it’ll look fishy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:29:54 </td>
   <td style="text-align:left;"> $QQQ $SPY $MSFT $AMZN  
 
$BABA $75 next stop…Delisting news will take it sub $ 50 
….corruption punishment 20-30% intraday drop… 
..ANT IPO pennies on dollar 30-40% drop… 
 …National security investigation conclusion 20-35% unless punishment is direct delisting… 
…china market crash 25-45% down… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:29:24 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:27:34 </td>
   <td style="text-align:left;"> $QQQ $SPY everyone would be rich if we all agreed to keep buying forever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:27:11 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Look at this prediction 🤷🏼‍♂️ I don&amp;#39;t remember if any of the indexes hit 3% but I was close ..... tomorrow we jump off a clif </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:25:53 </td>
   <td style="text-align:left;"> $QQQ future will swing like March 2020. Don’t worry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:25:00 </td>
   <td style="text-align:left;"> $SOFI what a wild day in the markets $SPY $QQQ $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:24:52 </td>
   <td style="text-align:left;"> $SPY $DJI $QQQ What&amp;#39;s up with all these bots with no followers , no DD, and no TA  if u make a bearish stance on a security they call u every name in the book? There is a winner and a loser on every side of the trade. Straight fukin inexperienced bent bag holders... do they not know if u r an emotional trader they will lose their whole unemployment check? Anyways call me what u want... IDGAF... my money not theirs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:24:10 </td>
   <td style="text-align:left;"> $QQQ Cramer said a bounce is coming so does that mean it&amp;#39;s going to drop? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:23:44 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA Jerome is 1000% Ari Spyros </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:23:42 </td>
   <td style="text-align:left;"> $QQQ $SPY just got off the phone with Powell. His exact words were “I’m gonna bankrupt the bulls” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:23:24 </td>
   <td style="text-align:left;"> $QQQ thank god i add a lot of stuffs on Papa Powell pull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:22:40 </td>
   <td style="text-align:left;"> $QQQ when the sell will stop $SPY $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:21:30 </td>
   <td style="text-align:left;"> $QQQ $SPY OH GOD HIDE YOUR MONEY IN YOUR MATTRESS WE GOING DOWN 🐻🎪🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:20:13 </td>
   <td style="text-align:left;"> $QQQ $SPY nobody even wanted the fed. Just a bunch of rich people established themselves and figured out a way to have unlimited money and rob others </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:19:55 </td>
   <td style="text-align:left;"> $TSLA IMO the only thing that will keep the call buying program at bay tomorrow morning is if NASDAQ (/NQ) sees some volatility overnight and $TSLA gaps under 900. $NDX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:19:54 </td>
   <td style="text-align:left;"> $QQQ 🚨 North Korea fires missile at S.Korea 🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:19:51 </td>
   <td style="text-align:left;"> They love to walk the market lower on Powell&amp;#39;s comments  
 
$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:19:21 </td>
   <td style="text-align:left;"> 2022 Tax Refund Dates (chart)... $TQQQ $QQQ $SPY $IWM 

https://www.cpapracticeadvisor.com/tax-compliance/news/21123177/2022-irs-income-tax-refund-chart-shows-refund-dates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:17:37 </td>
   <td style="text-align:left;"> $QQQ I like how even with 2%+ moves everyone is still hesitant to call green or red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:16:50 </td>
   <td style="text-align:left;"> $QQQ bears on a copium drip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:16:46 </td>
   <td style="text-align:left;"> $QQQ $SPY qqq going to 15,000 tomorrow spy going to 5,000
retail bulls so delusional!!
retail bulls - “you know why we going to hit those targets tomorrow? cuz microsoft did well, tesla did well! they saved us!” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:15:53 </td>
   <td style="text-align:left;"> $QQQ $spy $IWM inflation will fuck the market. .look at oil..rents..user cars...supply chain...mfr jpow is too late </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:15:50 </td>
   <td style="text-align:left;"> $ROKU $NFLX $QQQ $SPY Ackman is very bad news for shorts. He is famous for squeezing the short money managers and getting them bankrupt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:15:45 </td>
   <td style="text-align:left;"> $QQQ the futures fell so fast they gapped midday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:15:40 </td>
   <td style="text-align:left;"> $SPY $QQQ time to bend over for bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:14:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES HEADING FOR THE DUMPSTER HIDE YO CANOES MOVE TO CANADA LEARN FRENCH AWWWWWWW LAWWWWWD 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:14:54 </td>
   <td style="text-align:left;"> $SPY $UVXY $QQQ $SBUX $AMD 

The SPX 1982 Analogue:

- Decennial years
-Midterm years
- Year 2 Presidential cycles
- YoY CPI achieves 7%
- Post recessions
- Down January
- Bearish TOY Barometer signals
- Fed hikes 3 times in Q1
- Snap back rally to end January? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:14:04 </td>
   <td style="text-align:left;"> $SPY $QQQ who would in a fight? Jay Powell or Gary Gensler? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:14:00 </td>
   <td style="text-align:left;"> $spy $qqq after hours gains fading fast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:13:50 </td>
   <td style="text-align:left;"> latex236982d076e18944da44e4a9feffc82earkk), then Fintech, next is EV’s.  One of the few sectors where the leaders still sport insane multiples ($tsla $rivn $lcid). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:12:43 </td>
   <td style="text-align:left;"> $SPY $QQQ i suspect 1-2% drop tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:11:23 </td>
   <td style="text-align:left;"> $QQQ feel like i should have kept my puts. A win is a win. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:09:48 </td>
   <td style="text-align:left;"> $AAPL will apple save the markets next? $SPY $QQQ 
microsoft.. now tesla… apple will be the lord savior! right?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:09:48 </td>
   <td style="text-align:left;"> $SPY $QQQ With the way the futures are going, the bears are gonna have a long sleepless night tonight lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:09:22 </td>
   <td style="text-align:left;"> $spy $qqq $tqqq it should all reverse by morning 
Cramer is pushing Dell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:09:04 </td>
   <td style="text-align:left;"> $QQQ $SPY bull trap after trap after trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:07:44 </td>
   <td style="text-align:left;"> $QQQ $SPY don’t trust futures.  Powell confirmed today to all he is not looking to soothe the market.  Fed put is good as dead.  He was a lot more hawkish that I thought he’d be.  I flipped to short again, because why fight the Fed.  Market will need to suffer a lot more pain before it finds a floor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:07:05 </td>
   <td style="text-align:left;"> My &amp;quot;panic sell&amp;quot; breadth indicator reached an extreme last week only seen on late october 2020, covid crash and late december 2018. Before that readings were never that high. Market returns were very strong going forward after such high readings. $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:06:54 </td>
   <td style="text-align:left;"> $SPY $QQQ  we better test that monday low again or im going to be pissed  🩸🥵🤠 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:05:46 </td>
   <td style="text-align:left;"> $QQQ OH no the stock market never does well if yields are above 1.8% !!

lolwut? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:04:42 </td>
   <td style="text-align:left;"> $SHOP $SPY $QQQ $IWM  how are futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:04:23 </td>
   <td style="text-align:left;"> $QQQ bears clinging on bearily to what?  Yields which don’t indicate a down trend?  There’s nothing left to be bearish about.  Y’all over reacted and you know it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:03:30 </td>
   <td style="text-align:left;"> $spy $qqq stay short 
Market hasn’t found a footing yet 
$tsla $intc
Not the best earnings reactions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:03:02 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Hope everyone bought the dip and make money once again. 
 
We have a deal with JPOW...BTMFD and get paid! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:02:51 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM one more flush and that’s all she wrote folks 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:02:20 </td>
   <td style="text-align:left;"> $SPY $QQQ BULLISH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 08:01:08 </td>
   <td style="text-align:left;"> $NASDAQ $QQQ got sooo close to backtesting LT channel. puzzle piece that monday was the bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:59:35 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
We are God. 

In the beginning God was infinitely power despite being in the simplest form. Infinitely powerful because, well… God was all that was. But also infinitely lonely, hateful, loving, intelligent, etc. 

Anytime God created (which the only material God had was.. well.. God/itself) an entity it would immediately know every possible choice that entity could make. Back to being alone again. 

God, in order to break out of this infinite loneliness. Created a certain spin/equation. Capable of evolving towards a higher state while perfectly encapsulating the previous state. Thus losing nothing but gaining everything. A “trick” to forget about being alone while still progressing. 

When we “pray” we are literally praying to a higher version of ourselves “God”. God can infinitely improve. 

The light of God shines from a flat surface spanning infinitely far in all directions. The light beams create infinitely more patterns and connections, thus more to explore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:56:20 </td>
   <td style="text-align:left;"> $T $F $QQQ $AMD $MMM  
 
SPY is forming a reversal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:56:15 </td>
   <td style="text-align:left;"> $QQQ , $IWM, $SPY
Powell wants to tame inflation without hiking, since will hurt the economy, nobody can forecast the unintended consequences of a move like that , so what do you do?
You threaten! you crash the over exuberant markets, people lose the trillions he pumped into the system, feel poor, won’t spend, no inflation,
He’s thinking: Let’s leave the interest rates emo. at bay for harder times, when we really need it…
So he is being vague and threatening,
in chess we say: it’s good to take opponent piece, it’s even better to threaten the piece, and the best is to let your opponent know that you can threaten the piece, so here you have it,
He’s not as dumb as we think, words are like bullets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:55:39 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:55:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA 

Less than two days from premiering 🚨

https://youtu.be/Gt6msRGykCw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:54:58 </td>
   <td style="text-align:left;"> $QQQ $SPY today we saw a sharp intra-day reversal down, yields spiking, VIX up, Powell more hawkish and saying he expects inflation higher and possibly more rate hikes, Tesla beating on earnings and revenue but pointing to supply problems in 2022, Russia/Ukraine simmering, oil and natural gas through the roof... what am I missing? Why are futes ripping? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:54:34 </td>
   <td style="text-align:left;"> $QQQ  The ten year yeild was spiking out of control into the close, should weigh heavily on tech tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:54:31 </td>
   <td style="text-align:left;"> $QQQ failed to close above the reversal hammer&amp;#39;s OPEN 2 days in a row, and then closed below yesterday&amp;#39;s low today...futures are on crack looking bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:54:27 </td>
   <td style="text-align:left;"> My take after today&amp;#39;s Fed reaction: DrStoxxTrading Room  
 
$QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:53:07 </td>
   <td style="text-align:left;"> $QQQ will we ever see new all time highs again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:52:58 </td>
   <td style="text-align:left;"> $QQQ Tomorrow boom 💥 😛 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:52:27 </td>
   <td style="text-align:left;"> $QQQ why is this trending? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:52:15 </td>
   <td style="text-align:left;"> $QQQ why is futures up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:51:03 </td>
   <td style="text-align:left;"> $QQQ hold onto your dicks or Coochies cus once inflation is done with us it’s all we can afford. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:50:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $ETH.X basically what I see happening for the year is we get a bear cycle continuing into late q1 before new highs by May. June to October is going to be nasty for markets as we approach midterms. Oct to Dec will truly be UpOnly. Survive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:50:35 </td>
   <td style="text-align:left;"> $SPY $NDX $IWM $QQQ $VIX 

Trap set! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:50:11 </td>
   <td style="text-align:left;"> $SPY I could see tomorrow being green..I also  could see maybe few day pause in volatility.  Till another event...$DIA $QQQ $UVXY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:50:06 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:47:27 </td>
   <td style="text-align:left;"> $DIS $SPY $QQQ  bears aren’t ready for the awakening of the Disney conglomerate beast tomorrow. Been quiet for too long 😤😤😤😤 📈📈📈📈📈📈📈📈📈📈📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:47:04 </td>
   <td style="text-align:left;"> $QQQ all stocks going to 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:46:23 </td>
   <td style="text-align:left;"> $QQQ futes are tripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:45:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY Firing people for not being vaccinated during a nationwide labor shortage? Let&amp;#39;s Go Brandon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:44:52 </td>
   <td style="text-align:left;"> $SPY $QQQ Question to more experienced traders: I used unsettled cash to make a couple day trades today from the proceeds of a stock sale I made today… I used almost all my options buying power and now all the cash in my account is unsettled… Stocks are T+2 and options are T+1, so will I have to wait until Friday to trade or will it be settled tomorrow? I know I got one of my 3 GFV strikes… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:44:50 </td>
   <td style="text-align:left;"> $BTC.X  $SPY $QQQ if the breaking of 200MA and that big red candle of today doesnt make you bearish.. 
You definitly are permabull... no one can stop u any more...  
death row </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:43:58 </td>
   <td style="text-align:left;"> $SPY $QQQ  The Market speaks, let’s see a continuation into the EOW. 🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:43:30 </td>
   <td style="text-align:left;"> $SPY $QQQ both bears and bulls fully confident rn 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:43:28 </td>
   <td style="text-align:left;"> $SPY, $QQQ, $DIA, $TSLA tomorrow will go back and test today’s highs!  Intraday scalps are real! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:43:09 </td>
   <td style="text-align:left;"> $QQQ $SPY Jobless claims might be interesting since companies like $NKE are laying people off for not being vaccinated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:42:57 </td>
   <td style="text-align:left;"> $SPY $QQQ big red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:42:36 </td>
   <td style="text-align:left;"> $SPY $QQQ I canceled all my streaming platform subscriptions and I just read the DWAC board now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:41:55 </td>
   <td style="text-align:left;"> $QQQ bottom line it comes downs to $AAPL do they blow it out tomorrow ..chart looks like shit but everyone owns it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:41:23 </td>
   <td style="text-align:left;"> $QQQ This could actually lift the market, if only by helping to steer FAANG sentiment up.

NFLX is 0.77% of $SPY but 2.03% of QQQ! &amp;lt;https://www.zacks.com/funds/etf/qqq/holding&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:40:37 </td>
   <td style="text-align:left;"> $QQQ if you don&amp;#39;t see the triple bottom then that&amp;#39;s your fault  📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:40:30 </td>
   <td style="text-align:left;"> $SPY $QQQ Holy Rip 🙏 🧎‍♀️🧎🧎‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:40:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA REMEMBER THAT TIME FUTES WERE UP BIG AND THE BULLS WERE EXCITED 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:40:08 </td>
   <td style="text-align:left;"> $SPY $QQQ Looks like we have bottomed today. The market got the clarity that it wants from the FED on the future rate hikes and a lot of the uncertainty before the announcement are going away, that’s why futures are rallying hard now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:39:57 </td>
   <td style="text-align:left;"> $TQQQ ....Just a $STUDY ....&amp;quot;V&amp;quot;...$SPY $QQQ 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:39:46 </td>
   <td style="text-align:left;"> $QQQ literally goes the opposite way of close everyday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:39:14 </td>
   <td style="text-align:left;"> $QQQ well below it’s 200 day moving average still, with multiple closes below as well. Low 340s seem like a pretty solid support for now. Just like the S&amp;amp;P, I think this consolidates for a while before making another move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:38:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Could someone tell me the deal with the Fed meeting today?  
 
Did he say anything that will crash the market more or make the market go up?  
 
Anyone know or want to comment? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:38:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB $AMD $TSLA 

FUTURES  UPDATE FOR THE BEARS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:37:09 </td>
   <td style="text-align:left;"> $QQQ I think the party is over.  No way these levels can hold.  The Fed is showing their panic now that this is the case.  Look closely at the situation, very closely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:36:33 </td>
   <td style="text-align:left;"> $QQQ jobless claims tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:36:24 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ super v taking shape! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:35:56 </td>
   <td style="text-align:left;"> $QQQ we got a pow pow today. But we will survive 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:33:55 </td>
   <td style="text-align:left;"> $QQQ $SPY — Really happy I discovered this guy’s videos https://youtu.be/Xv2yDQDVyIY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:33:33 </td>
   <td style="text-align:left;"> DIX with a rare massive print, here all the times DIX was greater than 50 $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:31:36 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 1/26/2022 $SPY $XLF $QQQ $TSLA $CMPS https://www.chartguys.com/daily-market-videos/4116/bears-dominate-fomc-reaction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:31:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK  
 
VERY rare to see some good content on CNBC, but this guy nails it. 
 
“The market in our view is totally overshooting and losing its mind, creating great opportunities for long term growth investors to snap up lots of great shares because, interestingly, it hasn’t really affected companies that actually carry debt,” Cantwell said of the Fed rates. “Since the end of last year the market has been most aggressively discounting companies that are going to generate more cash in the future than they’re generating today… We’re a little upside down now.” 
 
Robert Cantwell 
 
https://www.cnbc.com/2022/01/26/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:29:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures rising strongly, the bears are in big time trouble tomorrow lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:29:45 </td>
   <td style="text-align:left;"> $SPY $QQQ you&amp;#39;re next level dumb if you think Putin is having 150k troops chill outside in the cold for shits and giggles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:29:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

FUTURES UPDATE FOR THE SHORTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:29:17 </td>
   <td style="text-align:left;"> $QQQ So what I understood Powel to say is market is fucked and we are on our own? I mean highly volatile until March and then more selling before FED meeting in March? Then huge sell off after JPow tells everyone what they already know, 1 extra rate hike. End of year, they realize they made a policy mistake and have to pull a 1980 move and increase rates to 20%, then the market really takes a shit for a couple of years. Then finally relief by year 2025. WE ARE ALL FUCKED!!!! Buy puts and save yourself the embarrassment of this fucking market screwing all of us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:26:34 </td>
   <td style="text-align:left;"> Trade alert on $SQQQ delivered today at 9:36AM CDT on 1/26/2022 🎯

Server link in the bio for winning alerts and for those eager to learn. $TQQQ $QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:26:32 </td>
   <td style="text-align:left;"> $SPY $QQQ this market is trash… you get chopped to bits both ways… too much up and down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:26:15 </td>
   <td style="text-align:left;"> Guess what stock moooned while insiders been selling since Dec to present?  $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:26:14 </td>
   <td style="text-align:left;"> $QQQ prolly red by AM.  Broken market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:25:57 </td>
   <td style="text-align:left;"> Top 3 things that aren’t real:

1. Boogeyman
2. Loch Ness Monster 
3. Inflation

Who are we kidding the first two are real… #Stocks #Powell #FederalReserve 

$SPY $QQQ $ARKK $DIA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:25:54 </td>
   <td style="text-align:left;"> $SQQQ  Current levels of liquidity. $TQQQ $QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:24:55 </td>
   <td style="text-align:left;"> $QQQ this is no bottom 
Their not going to allow another tech bubble. Companies are still way over valued. And new debt service has even started 

Every billion borrowed can equate to 10 million off the bottom line.  1 billion ain’t shit for these big companies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:24:35 </td>
   <td style="text-align:left;"> $QQQ oh we’re guna gap up and then crash again tomorrow? Ok cool…… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:24:32 </td>
   <td style="text-align:left;"> $QQQ testing $355 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:24:21 </td>
   <td style="text-align:left;"> $QQQ let me guess, they pumped it to trap, dumped it to close yesterday gap, now that Netflix news and TSLA beat eating. We go back to 350+ tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:24:13 </td>
   <td style="text-align:left;"> $QQQ - Buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:24:01 </td>
   <td style="text-align:left;"> $QQQ buy on major dip and sale when the market is high for the next 6 weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:23:54 </td>
   <td style="text-align:left;"> $QQQ $ARKK $SPY $TLT $VXX This could very well mark the end of an era in the equity markets.. Fed tightening / hawkishness… the kind a generation of traders and investors haven’t seen. Inverse ETFs, your time to shine!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:23:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA Nick Timoraos of WSJ asked Powell today:  &amp;quot;The balance sheet today calls for significantly reducing your holdings.   What does that mean?...&amp;quot;   Powell couldn&amp;#39;t answer it.  WTF?  How much more basic of a question is that?   They have already started unwinding assets and he said today that they would hit target reduction by early March.  How can they not have a plan for doing that if they are already doing it?   
Here is the clip.  Listen to Powell&amp;#39;s complete non-answer on all of the questions that were asked by Timoraos:  https://www.youtube.com/watch?v=DK0TFrZ7jCM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:23:07 </td>
   <td style="text-align:left;"> @Alpha_Capital $PLTR $SQ $QQQ $AAPL $TSLA 

New profile! Closed old one! 

Start following to get how to’s and value information! 

Position Sizing by Van Tharp

https://youtu.be/QjFRVPWpEuY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:21:51 </td>
   <td style="text-align:left;"> $QQQ shit Tesla mentioned supply chain issues for the upcoming year 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:21:40 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM Another good day!! Be a bear and a bull. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:21:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA it&amp;#39;s very bullish if Bill Ackman is buying, because as anyone who suffered through his &amp;quot;we&amp;#39;re headed for hell&amp;quot; song and dance knows, it&amp;#39;s that Bill Ackman doesn&amp;#39;t call bottoms;  he creates them by shamefully abusing his position.  Still, I&amp;#39;ll take the bottom :)  $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:19:30 </td>
   <td style="text-align:left;"> $QQQ Fed’s wording was hawkish, action is very dovish.  Powell Tortures the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:19:09 </td>
   <td style="text-align:left;"> $QQQ selloff going into 8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:18:58 </td>
   <td style="text-align:left;"> $SPY $QQQ It&amp;#39;s about time rates went up to cool the housing market down, prices are ridiculous! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:18:13 </td>
   <td style="text-align:left;"> $SQQQ adding this for the next 1-2 years. $QQQ will pull back to $225 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:18:03 </td>
   <td style="text-align:left;"> $QQQ scary to jump in and buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:16:51 </td>
   <td style="text-align:left;"> $RUN if this isn’t up 6% at some point tomorrow I’m calling the cops $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:16:14 </td>
   <td style="text-align:left;"> $QQQ I foresee a 3 week pump, 1 week trickle, then the shoulder falls off our epic H&amp;amp;S when rates actually get raised. Enjoy the next couple weeks, doubt it lasts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:16:02 </td>
   <td style="text-align:left;"> The technical rating of $QQQ is bad and it also does not present a quality setup at the moment. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:15:50 </td>
   <td style="text-align:left;"> $SPY $QQQ how market ended should be a warning we are still headed south. Very possible futures turn gory red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:15:23 </td>
   <td style="text-align:left;"> $QQQ bearish engulfing candlestick formed today. Probably not good for tomorrow, especially with the VIX trend intact </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:15:22 </td>
   <td style="text-align:left;"> $QQQ roll off balance sheet not sales.  Bears need to learn to read the room.  Not the catalyst you thought it would be.  Even the god Jamie Dimon says so. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:13:41 </td>
   <td style="text-align:left;"> $spy $qqq $iwm after hours traders ignoring what’s happening in the bond market.  These next few days should be interesting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:12:05 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ okay the fed is possibly doing 4 rate hikes + tapering of QE (both are old news), so why the market is reacting likes it is breaking news !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:12:00 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:11pm)

⦿ $QQQ is down 0.2% in the last 5 mins. 

⦿ There are 12 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 9.0% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:11:31 </td>
   <td style="text-align:left;"> $QQQ ackman sees this as a buying opportunity. Then that means other hedgies have been too or will be. Today  was just an over reaction to something that was already priced in. Up we go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:10:58 </td>
   <td style="text-align:left;"> $BABA even J Pow said it well, &amp;#39;buy the LEAPS&amp;#39; for $BABA . And practice rolling but not selling. $QQQ $KWEB https://finance.yahoo.com/news/fed-suggests-balance-sheet-shrink-200734996.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:10:29 </td>
   <td style="text-align:left;"> $SPY $QQQ mr puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:09:37 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-01-26 Daily Forecast Video: 
https://www.youtube.com/watch?v=4o6EFvab1Po </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:09:23 </td>
   <td style="text-align:left;"> $QQQ holding risk overnight so you better behave </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:09:01 </td>
   <td style="text-align:left;"> $QQQ gone are the days where 1% was considered a large daily movement. This thing rips 0.6% three minutes into futures! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:08:24 </td>
   <td style="text-align:left;"> $SPY $QQQ You wanted drama and we got drama.. Now time to go up and kill the bears who got too comfy 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:07:51 </td>
   <td style="text-align:left;"> $SPY $QQQ clearly bulls don’t give a shit about rates at 2% in the morning? Did you guys forget about the move in the 10Y at close? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:07:40 </td>
   <td style="text-align:left;"> $SPY $QQQ time for bears to die though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:06:49 </td>
   <td style="text-align:left;"> $QQQ 
My put misses $340! Come on back in these AH&amp;#39;s $340 👍⤵ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:06:02 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ll bet people bought tons of puts for Friday.  So, what does wall street do?  expire them all.  $UVXY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:05:54 </td>
   <td style="text-align:left;"> $QQQ tech earnings have been great… measly incremental  rate hikes are of little importance to be honest.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:04:21 </td>
   <td style="text-align:left;"> $SPY $QQQ looks like it might get sucked back up to the highs over the night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:02:54 </td>
   <td style="text-align:left;"> CHIP SHORTAGE IS OVER!!!!Intel reports better-than-expected results and delivers upbeat guidance $spy $qqq $dia $iwm  https://www.cnbc.com/2022/01/26/intel-intc-earnings-q4-2021.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:02:28 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:02:26 </td>
   <td style="text-align:left;"> What a waste of Elon jawboning tonight ... it was fun while it lasted ... bring out the TESLA short trade daggers $tsla ... they are in trouble in tandem with the ev market being so overrated fad with tremendous competition, government subsidies cuts, et al, as well as ridiculous p/e ratios, supply problems, socioeconomic concerns, Coronavirus, and more ... tilt ... game over ... so fake the stock markets have been since 2009 and prior.  Enjoy the Armageddon Depression 🐻❤😈☠ thank dog that I am here to help ✔ $f $gm $spy $qqq and more 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:01:33 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY $SVXY $VXX  
Yolo the Yoyo ↕️ 😃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:00:44 </td>
   <td style="text-align:left;"> $qqq I am irresponsibly long $MSFT. Others $TSLA. Others more $AAPL. one thing in common, they PRINT MONEY. 
 
where are you going to go? BONDS? Lmao. 
 
there is a time for shorting companies. there is time for shorting tech. Not now. bears will lose it all.  
 
MELT. UP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 07:00:29 </td>
   <td style="text-align:left;"> $CPNG chart is technically ready for massive PR/pump from the company.   This is due for a 5% to 28% pop on the upside back over $30.  $QQQ SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:58:54 </td>
   <td style="text-align:left;"> $QQQ $SPY $ROKU $TSLA 🐻s might be goats tomorrow. 🐐🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:58:51 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AARK 

no $25k car.... easiest short of my life... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:58:10 </td>
   <td style="text-align:left;"> $UVXY I&amp;#39;m going to laugh of JPOW crushes VIX overnight to &amp;quot;stabilize&amp;quot; the market.  $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:57:12 </td>
   <td style="text-align:left;"> $QQQ open casino! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:55:33 </td>
   <td style="text-align:left;"> $QQQ So was Monday the bottom? Seems like FED was about as hawkish as it could be and not much harm done. 
 
That being said, may not get to ATH this year, may just be a lame year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:54:55 </td>
   <td style="text-align:left;"> $SPY Did you see that #DIX print? 51.4 The last time it was this high was June of 2020. #GEX is still negetive for 5th consecutive day at 2.2B. The market was brought down for the dark pools to load up today. $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:54:54 </td>
   <td style="text-align:left;"> $QQQ looking good for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:54:46 </td>
   <td style="text-align:left;"> $QQQ $SPY $ETH.X i feel like it’s up from here. Fed is holding the course. That’s been priced in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:52:05 </td>
   <td style="text-align:left;"> $SPY $QQQ — No matter what the bear argument, your answer is: “Priced in.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:51:12 </td>
   <td style="text-align:left;"> It’s frightening when the biggest bubble (Tesla) is keeping markets green.
 $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:50:03 </td>
   <td style="text-align:left;"> Stocks Melt On January 26 Following The Fed https://mottcapitalmanagement.com/stocks-see-melt-on-january-26-following-the-fed/ $MSFT $SPY $QQQ, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:49:08 </td>
   <td style="text-align:left;"> $SLS official short interest 8.09 days to cover as volume completely dries up. 
 
Days to cover has never been this high! 
 
Insane low float and massive days to cover, the setup is there as float has been absorbed. 
 
https://www.nasdaq.com/market-activity/stocks/sls/short-interest 
 
$xbi $labu $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:49:06 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:48:51 </td>
   <td style="text-align:left;"> Bad breadth 
$SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:48:18 </td>
   <td style="text-align:left;"> $TSLA has stimulated a $QQQ move to green +0.57% for the entire day (reg. plus aftermarket) from pink prior to the close... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:47:29 </td>
   <td style="text-align:left;"> $SPY that’s some big DIX right there

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:46:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $ROKU low volume pumps while futures isn’t trading. Let’s goo bulls. Fuck them up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:45:37 </td>
   <td style="text-align:left;"> $SPY ...Lots of greed going on... I&amp;#39;m torn here because she rejected off previous support but the indicators are just Dangerously wanting some come back at this level...Trade Safe...🍀 $STUDY $QQQ $IWM $UVXY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:45:13 </td>
   <td style="text-align:left;"> Today $QQQ shows SELL signal (TA) for short term. Technical analysis source: https://stockinvest.us/stock/QQQ?utm_source=stocktwits&amp;amp;utm_medium=autopost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:43:27 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ $DIA Nice bear trap set at end if day… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:42:54 </td>
   <td style="text-align:left;"> $QQQ Bull run cometh. Nothing can stop &amp;quot;T&amp;#39;FAANG. &amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:42:52 </td>
   <td style="text-align:left;"> $TSLA this is dragging $QQQ up, like $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:41:32 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $TQQQ $SQQQ — Pour one out for shorts… it was a tough call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:41:11 </td>
   <td style="text-align:left;"> $QQQ trying their hardest to pump tech because of max pain 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:40:49 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ $DIA The correction is over! Time to fly… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:39:25 </td>
   <td style="text-align:left;"> $SPY $QQQ While I don&amp;#39;t really like $TSLA as a stock, looks like it will need the tech shares and the overall market to rebound tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:39:13 </td>
   <td style="text-align:left;"> $QQQ lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:38:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $TSLA $AAPL  Oooh my god…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:38:24 </td>
   <td style="text-align:left;"> $RUN hopeful for $TSLA win is being good for solar $SEDG $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:38:15 </td>
   <td style="text-align:left;"> $QQQ exactly what we needed, now slow rise up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:37:42 </td>
   <td style="text-align:left;"> $QQQ TSLA fanboys really going bizzonkers -- hope the bears are ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:36:56 </td>
   <td style="text-align:left;"> $QQQ small cap run coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:36:45 </td>
   <td style="text-align:left;"> $SPY WHO BOUGHT CALLS RUBHT BEFORE JPOWS PRESSER?  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:36:16 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ $DIA No more Fed uncertainty… market going to be bullish! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:36:00 </td>
   <td style="text-align:left;"> $QQQ what a day, sold  363 strike 0 DTE calls and collected the full premium </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:35:57 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:35:35 </td>
   <td style="text-align:left;"> $QQQ I got 2 shares of qqq and a rabbi walks into the bar with me he hass 200 now an italian guy has 50 . the hebrew says to me what is your price. Get it whats your price? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:35:08 </td>
   <td style="text-align:left;"> $NFLX $ROKU $QQQ $SPY $ARKK official article https://www.cnbc.com/2022/01/26/bill-ackman-buys-3-million-shares-of-netflix-after-recent-sell-off-becomes-a-top-20-shareholder.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:34:34 </td>
   <td style="text-align:left;"> $QQQ TSLA goes red after hours  and AAPL gives less than spectacular forward guidance. Just a hunch.

GDP goes lower than last q and the Q’s go red to around 387 level by Friday…. Just a hunch 

I did buy 380 puts expiring 1/28 &amp;amp; 2/4 so I am a little bias 🤣💵💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:34:06 </td>
   <td style="text-align:left;"> $QQQ tech gonna fly tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:33:23 </td>
   <td style="text-align:left;"> $QQQ musk fanboys going nutso with that move from 885 to 945 LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:32:59 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:31:49 </td>
   <td style="text-align:left;"> $QQQ. I gotz to drunk the cheep stuf tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:31:02 </td>
   <td style="text-align:left;"> if market breaks out yesterdays highs we could be off to the races from here $spy $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:30:03 </td>
   <td style="text-align:left;"> $SQQQ $QQQ $SPY just an FYI, both Tesla and Intel had better than expected earnings after the bell today. Just something to consider for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:29:45 </td>
   <td style="text-align:left;"> $QQQ it will drop another 15 percent this week. Wo decrees his holy father beet of juice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:29:17 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ great results but I’m weary of this market I feel like it’s just drawing out the downside letting rsi cool off and such after earnings what the hype - something to think about ¯\_(ツ)_/¯ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:29:10 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Market is green after hours because some penny flippers are trying to risk their whole portfolio for a .1% gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:28:21 </td>
   <td style="text-align:left;"> $SPY $QQQ Futes- ah crap you know the rest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:27:29 </td>
   <td style="text-align:left;"> $SPY $QQQ  Good earnings for the big companies while inflation is rampant. How&amp;#39;s that possible? They&amp;#39;re gouging prices on consumers... Fers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:27:21 </td>
   <td style="text-align:left;"> $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:26:29 </td>
   <td style="text-align:left;"> $NFLX If Ackmans buying the dip then market correction is probably over $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:26:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA BEFORE I GOT MY FANGS…🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:26:11 </td>
   <td style="text-align:left;"> $QQQ Tesla leads the way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:25:58 </td>
   <td style="text-align:left;"> $QQQ the indices just closed the yesterday gap.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:25:20 </td>
   <td style="text-align:left;"> $SPY, $QQQ, $TSLA - don’t fight, it’s going green!  Rally time! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:24:47 </td>
   <td style="text-align:left;"> $SPY $QQQ This market is trying to crash. Still pumping money in like it won’t, and enough in reserve to take advantage if it does, but she is trying!  
 
Still super bullish for the future, both US and world.  See through the noise, use your eyes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:24:07 </td>
   <td style="text-align:left;"> $QQQ $TSLA Powell decided to subsidize the Americans Poors meals and living expenses by crashing the market . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:24:05 </td>
   <td style="text-align:left;"> $QQQ well it’s official, this has become a penny stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:22:54 </td>
   <td style="text-align:left;"> $SPY $QQQ 
The market has been on a downtrend since December 2021. The FEDS saying they&amp;#39;re not doing anything about it means more downtrend Bulltards. It doesn&amp;#39;t matter if it rallies tomorrow, Bulls are fucked until the next FEDS Meeting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:22:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $NDX it didn’t pierce Monday’s lows. What if Monday was the bottom of this entire multi month sell off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:22:13 </td>
   <td style="text-align:left;"> All these $QQQ put buyers now make me laugh, u are gonna get smoked tomorrow ! 

Ackman took a big stake in $NFLX and that&amp;#39;s what happens when a great company gets cut in half

Same with $ATVI that got so cheap it got a takeover offer 

🐻 with no brain not paying attention to valuation are no better then fomo bulls on $ZM and $PTON or any spac lol 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:20:49 </td>
   <td style="text-align:left;"> $QQQ interest rates are zero, even with hikes they at historically low levels. It would take years for these companies to be effected. This is just a hedge job scam. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:20:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:20:37 </td>
   <td style="text-align:left;"> $qqq would agree that volatility will continue in techs because they were more hawkish (said there&amp;#39;s plenty of room to absorb rate hikes and inflation has upside risk). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:20:26 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM Powell didn&amp;#39;t say anything surprising (good or bad)...thus, the down move was more than I expected.   
I&amp;#39;m still long...feeling less optimistic post-FOMC than before. 
Anyone went long today?  Which stocks/ETFs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:20:20 </td>
   <td style="text-align:left;"> $QQQ these are going to fly tmrw. NFLX, TSLA, NVDA, AAPL... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:20:01 </td>
   <td style="text-align:left;"> $QQQ $SPY WE KNOW ALL THE BAD NEWS! What’s left that we don’t know?!?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:19:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA MAN I LOVE BEING A BEAR 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:18:40 </td>
   <td style="text-align:left;"> $QQQ banks crushed now tech is crushing. Exactly what is the reason for this extraordinarly over sold market? Broader market is 80% down. Some trading under market caps in entire cash. StitchFix trading at 1x sales. This is just stupid. It&amp;#39;s priced for world war 3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:18:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $BTC.X all bad news are known... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:18:33 </td>
   <td style="text-align:left;"> $TSLA Earning was way less than expected! Dump this pos whales! $AAPL $QQQ $SPY $UPST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:18:06 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ Permabears hate money, fun, sex, and most all they hate America </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:17:53 </td>
   <td style="text-align:left;"> $NFLX $ROKU $QQQ $ARKK $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:17:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA 🥤🐻🍿 https://www.cnbc.com/amp/2022/01/23/inflation-surge-could-push-the-fed-into-more-than-four-rate-hikes-this-year-goldman-sachs-says.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:16:51 </td>
   <td style="text-align:left;"> $QQQ $SPY my daughter is selling cookies get them before they&amp;#39;re all gone.https://app.abcsmartcookies.com/#/social-link-landing/06a8da32-b94f-410f-94d8-9dba637d5b6d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:16:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA 🥤🐻🍿

https://www.cnbc.com/amp/2022/01/23/inflation-surge-could-push-the-fed-into-more-than-four-rate-hikes-this-year-goldman-sachs-says.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:15:57 </td>
   <td style="text-align:left;"> $QQQ bears are fucked because they wrong. Companies are crushing. Starting to look extremely foolish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:15:13 </td>
   <td style="text-align:left;"> $QQQ $MSFT $AAPL Apple earnings tomorrow. Let’s. Go. Apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:14:39 </td>
   <td style="text-align:left;"> $NFLX Bill Ackman is the reason why Netflix crashed.  They covered their short position and went long on 3.1 million shares.  $SPY $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:14:15 </td>
   <td style="text-align:left;"> $TQQQ $qqq market can’t bottom if $amzn gets cut in half and other FANGMANT by 25% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:14:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA  Everyone gangsta till the 10Y goes to 3% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:13:34 </td>
   <td style="text-align:left;"> $QQQ what’s next catalyst in sight after Big tech earnings? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:13:09 </td>
   <td style="text-align:left;"> $QQQ omg so bullish after today… lol the only reason it would pop is max pain and these market makers 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:12:34 </td>
   <td style="text-align:left;"> $SPY hey all!!  Bill Ackman bought 3.1 million shares of $NFLX.  Get onboard before the pop!   $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:11:55 </td>
   <td style="text-align:left;"> $TSLA Todays Market should you a clue what will happen tomorrow $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:08:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $TLT 
Daily market recap. Check it out!
https://www.youtube.com/watch?v=IK19y7GVGts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:07:29 </td>
   <td style="text-align:left;"> $UVXY $VIX $SPY $QQQ  
 
Another quick short $VXX after hours. You can trade with repeatable profits, skill and a defined process. You know how we do! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:06:59 </td>
   <td style="text-align:left;"> Powell kept saying they are flexible, nothing is fixed regarding rate hike plan, balance sheet reduction. They will be data driven and data should continue to disappoint in the short term. $SPY $QQQ $DIA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:06:56 </td>
   <td style="text-align:left;"> $IWM $SPY $QQQ - on days like today all you have to do is straddle the same day IWM/SPY/QQQ options. Paid nicely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:06:23 </td>
   <td style="text-align:left;"> $QQQ $SPY welp my insurance calls got clapped but looking like my puts gonna print even more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:05:51 </td>
   <td style="text-align:left;"> mega caps earnings are the tiniest hope keeping markets temporarily afloat because Fed just confirmed the party is over.  $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:05:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA looks like rare steak tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:05:09 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:04:55 </td>
   <td style="text-align:left;"> $QQQ $BTC.X $GME $AMC $MVIS  The fed essentially released relatively doveish info about not adjusting anything this meeting and sticking the course (relative compared to what was priced in)  
  
But then basically projected their intent to remain hawkish and reactive and leaving the markets with uncertainty and no expectations on any concrete actions.  
  
Basically they have shook the market to kill off the froth, without even having to adjust rates or do anything concrete with sheer indecision. 4d chess.  
  
Also, the message was clear: unemployment is tight but the labor force participation is lean. Some may have exited the market for early retirement and have not returned to work.  
  
Is the Fed shaking the money tree to try and force people out of early retirement back to the office? I think so.  
  
The Fed wants this year to kill speculation and retail with how they are allowing FUD to remain unchecked but without slamming on the breaks by keeping the market risk-off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:04:55 </td>
   <td style="text-align:left;"> Not gonna happen. As always market did front running and overshot before the start of tightening cycle. Macro data recently is weak, job market numbers next week should be bad. Bad macro = dovish Fed and good for stocks and opposite. $SPY $QQQ $DIA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:04:39 </td>
   <td style="text-align:left;"> $QQQ 10 year yields ripping back to highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:04:36 </td>
   <td style="text-align:left;"> $QQQ major support around 340, this is the 3rd time we bounced there.. looking like a inverse h&amp;amp;s to me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:03:52 </td>
   <td style="text-align:left;"> $QQQ wow those bonds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:03:43 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY  
FED news sold out like we got hyper inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:03:05 </td>
   <td style="text-align:left;"> $QQQ looking at selling the March 320p over coming days, breakeven of $311 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:02:55 </td>
   <td style="text-align:left;"> $SPY $QQQ honestly expected a bigger crash, but oh well. Going long from here - earnings are pretty good for tech sectors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:01:32 </td>
   <td style="text-align:left;"> $ARKK $NDX $SPY $QQQ major innovation in growth names… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:01:15 </td>
   <td style="text-align:left;"> $SPY $QQQ ”when reporters asked Powell if the Fed would consider raising rates at every meeting, which would mean more than four times this year, he didn’t say they wouldn’t, which indicates a flexibility to raise rates much more quickly (if necessary) than anyone was expecting,” 

This is why….market priced in 4 raise but daddy Powell came off aggressive today 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 06:00:43 </td>
   <td style="text-align:left;"> $QQQ feds robbed the bears for years now its time for the bulls.... about time CB were scrapped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:59:24 </td>
   <td style="text-align:left;"> $SPY $QQQ for real tho, can it really drill lower. Like didn’t bears print enough. Or are market makers complicit? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:58:31 </td>
   <td style="text-align:left;"> $QQQ I bought more calls. I just buy calls and I can’t stop. These swings are incredible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:58:30 </td>
   <td style="text-align:left;"> $QQQ In fact, lets not trade in the stock market, it&amp;#39;s a very silly place. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:58:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM how is $VIX looking? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:58:17 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX - </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:57:24 </td>
   <td style="text-align:left;"> $SPY $QQQ I&amp;#39;m expecting volatility to go way down now and markets to gradually climb.  
 
My thesis is that a bunch of people believe stonks go up because money printer goes brrr; they&amp;#39;ve exited the market and are largely waiting on the sidelines with cash. Reddit traders. Some of them came back in this morning; when JPow went full hawk they jumped back out again. That narrative cycle is over, at least for February. 
 
Some Reddit traders expecting a further drop will wait through March--the money printer&amp;#39;s not even fully off yet. But the other big lesson of COVID was to buy the dip, and they&amp;#39;ll follow price action higher. 
 
I&amp;#39;m long now, with room to average in if the thesis plays out. If the Nasdaq goes under yesterday&amp;#39;s lows around 13900 and doesn&amp;#39;t immediately double bottom my thesis is wrong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:57:10 </td>
   <td style="text-align:left;"> We are currently seeing a repeat of yesterday - a sell off into the close - a big stock tank on earnings then conduct a red to green face ripper  
 
let’s see how we rally overnight $spy $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:57:04 </td>
   <td style="text-align:left;"> $fb $aapl $spy $qqq https://www.youtube.com/watch?v=4MuAo3sPDuE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:56:25 </td>
   <td style="text-align:left;"> $SPX vs. $RUT  The US Index Matrix is skewed greatly toward large caps today.  At close: $SPY -0.25%.  $IWM -1.44%.  That&amp;#39;s a 5.76 X underperformance by small vs. large in daily change terms...  Still IWM is above the low for yest. and that low was above the low of the day before.  Large caps with lots of tech: $QQQ was -0.16%.  Buyers need to step in, yes, but so far we have a consolidation at the low after a Fed meeting.... see pr comments </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:56:23 </td>
   <td style="text-align:left;"> $AAPL $WMT $UVXY  
 
Healthy Reminder:  
 
Month-end flows hit PBs desk starting tomorrow  
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:56:06 </td>
   <td style="text-align:left;"> $QQQ best thing that could happen for me and my stock watching habit was to watch that confusion and subsequent market flux… so many variables at play … retailers can’t predict anything… nor should they try… out of our control …don’t bother. Go long on companies/stocks you like and relax … since that is only thing left to do. The alternative is too annoying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:55:53 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:55:23 </td>
   <td style="text-align:left;"> $QQQ 
The markets rallied b4 the Fed said they&amp;#39;re leaving interest rates were they are ... then sold off after the news release ! Hence: Nothing is holding the markets up ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:55:12 </td>
   <td style="text-align:left;"> $QQQ $TSLA the quality of Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:55:03 </td>
   <td style="text-align:left;"> $SPY $QQQ  Powell likes to talk big like the fed will do what&amp;#39;s necessary. There choices are to cause a recession and then a housing market crash or a housing market crash then a recession. Or do nothing and print more money. I say in the end after a bunch of gum flapping they do nothing. lol They could not unwind the balance sheet in the strongest 10 year bull market and they think they will be able to do it now that it is way bigger. Not to mention that if interest rates go up the federal government will not be able to service its debt payment. The Total income of the entire Federal US income tax we all pay right now is not even able to cover our annual interest payment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:53:51 </td>
   <td style="text-align:left;"> $QQQ $IWM $SPY - Powell actually said he doesn&amp;#39;t care about Wall St. only cares about Main St. Even if he is managing policy that way does he have to come out and say it. He knows everyone&amp;#39;s retirement is in the stock market. That and saying lotsa room to raise interest rates is what tanked the markets today. Other then that he was more dovish then I expected. Not likely more then 3 rate hikes, market expecting 4-7 hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:53:05 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $ROKU 2021 style markets pls. every time I lose like this and max leverage, we limit up. pls one more time for us bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:52:46 </td>
   <td style="text-align:left;"> $QQQ I am just tired after watching that… and now don’t care about day to day… going long on everything and truly don’t care what it does… will be way up in 5 years… moving on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:51:56 </td>
   <td style="text-align:left;"> $SPY deltas flat, $QQQ deltas flat. 
market flat. 
That event vol crush never happened
event vol never took off 
put holders...anxious.
paraphrasing @spotgamma </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:51:27 </td>
   <td style="text-align:left;"> $QQQ Earnings beats across the board carving the way out for tech to be inflation hedge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:51:09 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 966.9K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:50:36 </td>
   <td style="text-align:left;"> $AMD ok
Maybe we are near a bottoming process . Maybe not . It’s not stock related , it is general market related 

If we lose ma200 will be bad . Everything I see is below ma200 , even $qqq 

I will be cautious adding now 
Cash is a position , already got plenty selling other stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:50:30 </td>
   <td style="text-align:left;"> $QQQ mooove!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:50:15 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY Damn, it&amp;#39;s like yesterday and $MSFT all over again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-27 05:49:29 </td>
   <td style="text-align:left;"> $QQQ really down 18% in like 4 weeks that&amp;#39;s amazing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:41:42 </td>
   <td style="text-align:left;"> $AAPL right side is bullish on higher time frames.  We only like to buy it in 3, 7 or 11 swing at the blue boxes.   We have been forecasting AAPL to decline for the past week and it has already reached the area where a bounce can take place.  We don’t like to sell it short but further declines first are still favoured to complete the sequence from the 1/04 peak .    #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:41:38 </td>
   <td style="text-align:left;"> $AAPL why anyone would short this stock after m1 chips is pretty baffling to me. m2 on the horizon. iPhone 14 on the horizon. eventual house made modems on the horizon. graphics chips on the horizon. this is like buying $NVDA, $INTC, $TSLA, and AAPL all in one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:40:23 </td>
   <td style="text-align:left;"> $AAPL Look at 10 yrs yield - Might gap down tomorrow !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:40:18 </td>
   <td style="text-align:left;"> $AAPL apple to the 🌙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:39:56 </td>
   <td style="text-align:left;"> $AAPL 
The only thing that makes sense here is twits being a hedge sponsored web site that hires people to make bearish comments. I refuse to believe we have sunk so low as a society that people would want the economy and markets to tank as well as retirement accounts wiped out so they can make $50 on their puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:39:10 </td>
   <td style="text-align:left;"> $AAPL People saying this is going down.  Where 150? 160?  0?  Yes I have seen that too.  Apple is where everyone goes when everything else makes you nuts.  Would like to see a dividend increase this time around.  Good luck all!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:38:55 </td>
   <td style="text-align:left;"> $AAPL last 5 days BILLIONS BEING sold now tell me why everyone is bullish ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:37:40 </td>
   <td style="text-align:left;"> $AAPL started my short today.  Appl about to take a long watt back down.  Overvalued right now bear market coming and appl first in line </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:36:31 </td>
   <td style="text-align:left;"> $AAPL use all the charts and trickery you want, we aren’t falling for it. I can’t wait to see you losers covering your asses when you feel the true power of investor sentiment 
❤️🍎👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:35:00 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $TSLA $BA 
👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:34:11 </td>
   <td style="text-align:left;"> $AAPL bear asses are about to get FUCKED! No lube </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:34:05 </td>
   <td style="text-align:left;"> $AAPL Carve out your little den in the world by shutting out everyone you disagree with. See where that gets you in life. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:33:14 </td>
   <td style="text-align:left;"> $LCID $TSLA $aapl market is far far away from reality numbers right now. Nobody cares about catalysts, earning beats, nothing. Now rate hike in march which means fear market till march then a fukin sell off on that day because of hike. This year will be similar to last year... flippers making money... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:32:40 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m buying at 150 and I&amp;#39;ll miss the bottom by a mile. Block me if I hurt your feelings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:32:08 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-26 Technical Analysis Video: 
https://www.youtube.com/watch?v=YWGGn9Hjbwo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:31:50 </td>
   <td style="text-align:left;"> $UVXY $aapl gonna miss and miss large. way too many variables that all point red... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:31:04 </td>
   <td style="text-align:left;"> $AAPL ...$150...Is quite possible if rejection continues $QQQ $TQQQ $SPY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:28:48 </td>
   <td style="text-align:left;"> $AAPL - Apple should test its 200MA of $147 area. It has already broke the 50-100MA and the 1W and 1M has plenty of room to come down. We may see a little recovery these days but it should hit its 200MA within 2-weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:28:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL tsla failed to amaze the crowd. Rate hike coming! Aapl er drops as usual. Hahaha bears will linger. Daddy joe and daddy jpow wont spoil you anymore. 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:24:04 </td>
   <td style="text-align:left;"> $AAPL 

$170 Friday
$180 Valentine’s Day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:22:25 </td>
   <td style="text-align:left;"> $AAPL Categories No. 1 and No. 2: Rolled-up trips and three cards to a low straight flush. ~ Richard Wise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:22:21 </td>
   <td style="text-align:left;"> $NFLX FOMC meeting is done, TSLA and MSFT is done too and it’s holding. Tomorrow we have $AAPL earning which per estimates will be good. So I think it’s a good time to buy NFLX which  is had nice price correction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:21:16 </td>
   <td style="text-align:left;"> $FB $AAPL $TSLA $GOOG  
 
$F  
 
Edward Jones: $21.77 &amp;quot;Hold&amp;quot; January 3rd, 2022. 
https://www.edwardjones.com/us-en/media/3641 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:21:07 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL  Bought puts! Dont see going up after earnings. Why Elon sold if he had confidence? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:20:47 </td>
   <td style="text-align:left;"> $AAPL should we break the news to her? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:20:20 </td>
   <td style="text-align:left;"> $AABB $TSLA $AAPL $MSFT $GOOGL  If Q1 2022 is even near as similar to Q1 2021 in small caps set it and forget it ASAP https://www.marketscreener.com/news/latest/U-S-small-cap-stocks-may-be-signalling-market-bottom--37649996/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:20:02 </td>
   <td style="text-align:left;"> $AAPL $SPY gold down. we ripping tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:18:45 </td>
   <td style="text-align:left;"> $AFRM
 $V $MA and $AAPL ER tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:17:16 </td>
   <td style="text-align:left;"> $AAPL 20 Feb $148 puts almost $4,000 gamble. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:16:50 </td>
   <td style="text-align:left;"> Seems like a super bad day for $AAPL!! I feel really sad! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:16:08 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m pretty much all for poetry in public places - poetry on buses, poetry on subways, on billboards, on cereal boxes. ~ Tracy Owens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:11:43 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMC Aww shit Powell is loaded in puts. The man is clearly pushin Ps. Will  $TSLA be the opening salvo in a bear market?? https://youtu.be/9g08kucPQtE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:11:33 </td>
   <td style="text-align:left;"> $AAPL I’ll be back tomorrow, and if Tim pivots to a faceless robot I’m buying an island far, far away from all this.

Good luck to bears. Better luck to bulls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:09:48 </td>
   <td style="text-align:left;"> $AAPL will apple save the markets next? $SPY $QQQ 
microsoft.. now tesla… apple will be the lord savior! right?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:09:08 </td>
   <td style="text-align:left;"> $SPY until $AAPL show it cards tomorrow, don’t do anything. I think big news tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:08:51 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m calling my shot. $SAM Truly&amp;#39;s kind of earnings beat. $2.25+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:08:45 </td>
   <td style="text-align:left;"> $AAPL 

Hey, idiot Bulls, market is going RED again. Hahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:06:34 </td>
   <td style="text-align:left;"> $AAPL the earnings are going to be huge we should get back to 185 easily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:06:00 </td>
   <td style="text-align:left;"> $AAPL 

Let’s see; Biden, inflation, Powell, Kamala, Pelosi, great resignation, Putin, Ukraine conflict.

It all sums up to market sell off. Short everything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:04:30 </td>
   <td style="text-align:left;"> $AAPL Skyworks reported record earnings - they are Apple&amp;#39;s biggest supplier.  Did anyone see this? 
https://investors.skyworksinc.com/news-releases/news-release-details/skyworks-reports-q4-and-full-year-fy21-results </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 08:01:12 </td>
   <td style="text-align:left;"> $AMZN $tqqq $GOOGL $AAPL 
I’ve been fading all these pops last few weeks 
Don’t catch falling knives in faangs
Msft pierced 270 yesterday in AH
Tsla pierced $880
It’s gonna get much uglier than Monday 
All bounces 🏀 
Are dead ☠️ cat 🐈 bounces 🏀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:59:47 </td>
   <td style="text-align:left;"> $AAPL bears are scumbags. They want to short innovation , vision , execution and customer delight indirectly . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:59:35 </td>
   <td style="text-align:left;"> $AAPL  
Wouldn&amp;#39;t be shocked if this comes down another 30%. 
Not trading, but looking to reload longs 100-140 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:59:20 </td>
   <td style="text-align:left;"> $AAPL 
Sorry to brag.. my son developed an App that Steve Jobs displayed on one of his conferences. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:56:22 </td>
   <td style="text-align:left;"> $AAPL millions of Apple customers got new MacBook Pros last quarter. best MacBook Pro ever made. load the hecking boat! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:56:14 </td>
   <td style="text-align:left;"> latex9bb0449abe1b69bd368e398e49145317$ Guidance update.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:55:25 </td>
   <td style="text-align:left;"> $AAPL cats out of bag here... blowout #&amp;#39;s why is tech ripping? Tesla nah msft naw its right here ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:55:07 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #2 ticker with sweep activity where institutions are trading options urgently with 58.9K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:53:28 </td>
   <td style="text-align:left;"> $AAPL guys this is REALLYYYYY green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:50:19 </td>
   <td style="text-align:left;"> $AAPL $MSFT load the hell up!!! J powell can say whatever means nothing rates can go 1.75% still low as F!!! Stop being scared </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:50:06 </td>
   <td style="text-align:left;"> $AAPL I still can’t believe I bought $158 shares today. I can only hope the IPhone will someday become the #1 phone in China… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:47:59 </td>
   <td style="text-align:left;"> $AAPL what’s the news here? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:47:31 </td>
   <td style="text-align:left;"> $SPY I paid $9000 for a 10-strip of SPY $435P Feb4’s yesterday. 
I was down like $3500ish today. Rather than sell I bought a ten pack of $AAPL calls to hedge bcuz If your puts are gonna get fuk then Apple probably went up that day. I held both positions. I never feel bad about an Apple hedge. My Spy puts are up, apple calls down. I still like both positions. This is what I do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:47:27 </td>
   <td style="text-align:left;"> $AAPL raise your hand if you bought leaps in that dip in the $158 area today during J Powel?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:47:16 </td>
   <td style="text-align:left;"> $AAPL A ton of metrics are pointing toward 3TRILLION MARKET CAP. .BEARS BEWARE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:43:20 </td>
   <td style="text-align:left;"> $AAPL and I stood arrow straight .. encumbered by the weight… of all these hustlers and their dreams… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:42:48 </td>
   <td style="text-align:left;"> $NFLX can we close over 380+ please. 

I’ll
Need to take some melatonin tonight. $aapl earninfs tomorrow as well.

Is FANG back?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:41:55 </td>
   <td style="text-align:left;"> $QQQ bottom line it comes downs to $AAPL do they blow it out tomorrow ..chart looks like shit but everyone owns it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:40:38 </td>
   <td style="text-align:left;"> $AAPL Tanking the market once iPhone sales are down bad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:39:36 </td>
   <td style="text-align:left;"> $AAPL what do you guys do when your shares get called away with covered calls?  Do a wheel or set a buy limit order? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:37:44 </td>
   <td style="text-align:left;"> $AAPL if it beats it should dip on earnings and rebound like $MSFT and $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:36:23 </td>
   <td style="text-align:left;"> $AAPL 

Now it is up to Apple… it will be fine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:35:23 </td>
   <td style="text-align:left;"> $AAPL this is the best company in the world. The only other company that comes close to quality is Tesla because they also control their entire manufacturing process on their product line. However Apple is going to get hit with some of these economic headwinds as well. But you can believe that I’ll be putting my money into both Apple and Tesla when I start to see a significant drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:34:30 </td>
   <td style="text-align:left;"> $AAPL take a look at AAPL and Microsoft charts, almost identical movement… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:32:53 </td>
   <td style="text-align:left;"> $AAPL don’t forget about the MacBook Pro M1’s. Hottest laptop on the street Q4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:31:36 </td>
   <td style="text-align:left;"> $AAPL $SPY $INTC 

After today fed speech,only way the market is gonna be up its standing against a wall. Hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:29:33 </td>
   <td style="text-align:left;"> $SPY $AAPL anticipation may keep this afloat for another day. Idk, we will see. Gl traders.  Oh ya FUCK JOE BIDEN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:29:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

FUTURES UPDATE FOR THE SHORTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:29:16 </td>
   <td style="text-align:left;"> $INTC i knew my boi powell wouldn’t let me down 😀 Interest rates going up up up! And $AAPL is shtting on intel chips 🤪🤣😂 keeeeep oooonnnn shorting 🌈🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:26:41 </td>
   <td style="text-align:left;"> $AAPL Long bull here, but the last few earnings we have dumped AH  no matter how great the ER was. What will it take for that to not happen this time? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:25:23 </td>
   <td style="text-align:left;"> $MSFT I think the market is waiting for $AAPL earnings before the next big sell off. Why sell now when there’s one last major earnings to report. But then, after Apple reports, it’s back to rising rates and Russia/Ukraine. The bulls are almost out of gas but I need that one last pump so I can load up more puts 😸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:25:08 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT $AAPL $NFLX another good day on the day trades. Hit the follow for some plays or join the team and trade during the live session. Market is up and down so best to control the day than swing for now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:23:48 </td>
   <td style="text-align:left;"> $SPY Most macro data is done for the week. Tomorrow comes down to $AAPL. Stay vigilant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:23:07 </td>
   <td style="text-align:left;"> @Alpha_Capital $PLTR $SQ $QQQ $AAPL $TSLA 

New profile! Closed old one! 

Start following to get how to’s and value information! 

Position Sizing by Van Tharp

https://youtu.be/QjFRVPWpEuY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:22:36 </td>
   <td style="text-align:left;"> $AAPL We are Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:22:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 49 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:20:51 </td>
   <td style="text-align:left;"> $AAPL where did those cocky bears go? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:18:20 </td>
   <td style="text-align:left;"> $FAMI it’s cooking over here... 

$AMC $NIO $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:18:09 </td>
   <td style="text-align:left;"> $AAPL The most money to be made for the MM will be obliterating those $150 puts tomorrow. Sorry, bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:17:54 </td>
   <td style="text-align:left;"> $AAPL $AMZN $FB $PYPL we’ve had time to digest the pow speech, it was exactly what we expected… let’s get back to making money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:17:49 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT $GOOG $AMZN 

Keep investing, keep compounding !!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:15:20 </td>
   <td style="text-align:left;"> $AAPL LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:13:32 </td>
   <td style="text-align:left;"> $AAPL let&amp;#39;s go 🍎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:13:22 </td>
   <td style="text-align:left;"> SweepCast alerted: $AAPL with Unusual Options Activity Alerted on $157.5 CALL Expiring: 01-28-2022 worth 40K🐂 |🥇 Check out SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:13:00 </td>
   <td style="text-align:left;"> $SPY $UVXY $VXX all noise doesn&amp;#39;t matter. What does matter, is 30B instead of 60B in Jan. And 0-0.25% rate. 
 
Short $AAPL and $TSLA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:12:52 </td>
   <td style="text-align:left;"> $SPY 

“Ah yes but have you heard of $aapl pump” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:12:29 </td>
   <td style="text-align:left;"> $AAPL can someone say “rising wedge” or “failed breakout” or “down trend still intact”? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:12:29 </td>
   <td style="text-align:left;"> $AAPL call full loaded </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:12:27 </td>
   <td style="text-align:left;"> $AAPL 

It’s going back to $154 tomorrow. Hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:10:37 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:10pm)

⦿ $AAPL is down 0.1% in the last 5 mins. 

⦿ There are 15 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 9.0% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:10:23 </td>
   <td style="text-align:left;"> $AAPL will confirm world dominance tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:10:04 </td>
   <td style="text-align:left;"> $AAPL back to $200 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:09:46 </td>
   <td style="text-align:left;"> $FAMI record backing earnings for farmmi just came out and it is running hard. $AAPL $NIO $F $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:09:31 </td>
   <td style="text-align:left;"> $AAPL max pain looks like 167 big open interest on $170 calls, so I doubt the MM let those print. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:09:22 </td>
   <td style="text-align:left;"> $AAPL Nice AH movement.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:06:05 </td>
   <td style="text-align:left;"> $AAPL are you buying LMC? Someone spill the beans at er tomorrow 🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:06:03 </td>
   <td style="text-align:left;"> $TSLA I think investors are slowly realizing earning wasn&amp;#39;t good after reading it completely like I did.  sub 900 tomorrow. sorry bulls. $UPST $AAPL $MSFT $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:05:26 </td>
   <td style="text-align:left;"> $AAPL calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:02:11 </td>
   <td style="text-align:left;"> $AAPL how to play? buy the morning dip or wait for bears to do their post ER attack after smashing earnings like they did to $TSLA and $MSFT? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:02:05 </td>
   <td style="text-align:left;"> $AAPL Pete Najarian on 
CNBC, just said that Apple will have a grrat quarter tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:01:17 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/p_ferragu/status/1486454652128399360?s=21 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:00:44 </td>
   <td style="text-align:left;"> $qqq I am irresponsibly long $MSFT. Others $TSLA. Others more $AAPL. one thing in common, they PRINT MONEY. 
 
where are you going to go? BONDS? Lmao. 
 
there is a time for shorting companies. there is time for shorting tech. Not now. bears will lose it all.  
 
MELT. UP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 07:00:28 </td>
   <td style="text-align:left;"> $AAPL $SPY Pete Najarian says Apple will report a big quarter tomorrow. RIP puts. 🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:57:42 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:56:53 </td>
   <td style="text-align:left;"> $AAPL 10 yr reaching highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:54:55 </td>
   <td style="text-align:left;"> $SPY Did you see that #DIX print? 51.4 The last time it was this high was June of 2020. #GEX is still negetive for 5th consecutive day at 2.2B. The market was brought down for the dark pools to load up today. $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:53:54 </td>
   <td style="text-align:left;"> $AAPL just remember the red for Microsoft and then green.  It’s a wacky market and Wall st is enjoying jerking the retail around </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:51:37 </td>
   <td style="text-align:left;"> $AAPL ◢ Follow The Movement https://bit.ly/3slupxs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:50:11 </td>
   <td style="text-align:left;"> $AAPL Apple Option Alert: Feb 4 $172.5 Puts Sweep (8) below Bid!: 124 vs 7434 OI; Earnings 1/27 After Close 🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:50:08 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple’s Q1 Numbers Should Be Fine — But the Stock Is Still Not a Buy, Warns Goldman Sachs https://www.stck.pro/news/AAPL/22011683 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:50:04 </td>
   <td style="text-align:left;"> $AAPL Apple’s Q1 Numbers Should Be Fine — But the Stock Is Still Not a Buy, Warns Goldman Sachs https://www.tipranks.com/news/article/apples-q1-numbers-should-be-fine-but-its-still-not-a-buy-warns-goldman-sachs/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:48:09 </td>
   <td style="text-align:left;"> $AAPL AHAHAHAHAH IM SO HAPPY A WHOLE PERCENT AFTER HOURS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:47:49 </td>
   <td style="text-align:left;"> $AAPL gotta love the knee jerk reaction to good earnings. Now TSLA is up!!!  Haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:46:05 </td>
   <td style="text-align:left;"> $AAPL beats ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:43:48 </td>
   <td style="text-align:left;"> $AAPL why she taking citadal side🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:42:52 </td>
   <td style="text-align:left;"> $AAPL offers solutions for managing transactions 🧐 something is going on with apple Foxconn and lordstown but what the Fk is it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:41:47 </td>
   <td style="text-align:left;"> $TSLA bears getting their asses torn inside out  🚀🦍🤣 $SPY $AAPL thank papa Elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:41:26 </td>
   <td style="text-align:left;"> $AAPL this is the company that comes up at the listed address where Foxconn apple and lordstown ev all show up so what do you apple guys make of this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:41:00 </td>
   <td style="text-align:left;"> $AAPL gap up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:40:46 </td>
   <td style="text-align:left;"> $AAPL $150 is the destination. We all know tech will be slaughtered, even utilities get slaughtered when rates rise. All calls, load up now! Keep em coming and feed the HFs! 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:38:52 </td>
   <td style="text-align:left;"> $AAPL fill that gal in the $95 area? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:38:41 </td>
   <td style="text-align:left;"> $NFLX $GOOG $AAPL $FB $AMZN https://www.cnbc.com/2022/01/26/bill-ackman-buys-3-million-shares-of-netflix-after-recent-sell-off-becomes-a-top-20-shareholder.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:38:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $TSLA $AAPL  Oooh my god…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:38:20 </td>
   <td style="text-align:left;"> $AAPL $MSFT $COIN midbyear I do expect another crash but short term I see an aggressive bounce incoming. I expect heavy green and red daily days. Won’t be surprised the indexes open down 400 and close up 100. Vice versa, and this is ideal day trading galore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:37:26 </td>
   <td style="text-align:left;"> $AAPL   With the middle class getting financially pinched maybe some people will push off a new latex3983086004d5a70b8a7a555f10f194c9T 833k (66% call/34% put)
$NVDA 706k (64% call/36% put)

Lynk in bayo for option trading ideas and alerts ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:35:02 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/p_ferragu/status/1486457777342066689?s=21 $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:33:26 </td>
   <td style="text-align:left;"> $AAPL to all the haters trying to influence fear to get us to sell. I can’t wait to watch you all run to cover your asses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:31:45 </td>
   <td style="text-align:left;"> $aapl $tsla $msft $arkk https://www.youtube.com/watch?v=sXhBREuDPiE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:30:10 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-26 Largest Trades Data: 
https://www.youtube.com/watch?v=EZZMuhWHts4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:29:25 </td>
   <td style="text-align:left;"> $AAPL we will get back out 3T Very soon ...this Year apple should do 30% performance that will take us somewhere around 230 bucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:29:18 </td>
   <td style="text-align:left;"> $AAPL They&amp;#39;ll sell the news EOD tomorrow, regardless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:29:07 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMD $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:28:40 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:28:34 </td>
   <td style="text-align:left;"> $AAPL 

Double top AF on $AAPL. Hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:26:27 </td>
   <td style="text-align:left;"> $AAPL 

Hammer on the $VIX. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:26:26 </td>
   <td style="text-align:left;"> $AAPL Apple will save us all as usual 👊💎🤲🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:25:49 </td>
   <td style="text-align:left;"> $AAPL Be careful, you never know what this will do with earnings. The way the market is right now they are going to have to blow away earnings to go up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:25:35 </td>
   <td style="text-align:left;"> $TSLA t minus 5 minutes #fuckjeromepowell  $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:25:00 </td>
   <td style="text-align:left;"> $FCEL $AAPL $BAC $ALLY $TWTR  
 
Reversal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:24:18 </td>
   <td style="text-align:left;"> $MRNA $TSLA $AAPL ….get into mRNA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:19:53 </td>
   <td style="text-align:left;"> $NFLX $SPY $TSLA $AAPL $FB 

Netflix pumping hard after hours... I love you Bill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:18:33 </td>
   <td style="text-align:left;"> $TSLA Earning was way less than expected! Dump this pos whales! $AAPL $QQQ $SPY $UPST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:15:13 </td>
   <td style="text-align:left;"> $QQQ $MSFT $AAPL Apple earnings tomorrow. Let’s. Go. Apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:13:15 </td>
   <td style="text-align:left;"> $AAPL with $MSFT and $TSLA out and safe post earnings. I am really hoping we pull through! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:12:48 </td>
   <td style="text-align:left;"> $AAPL it depends for msft their forecast for overall rev is smaller than last q so there is a slowdown (from 51 bln to 48.5 bln or so). there was a bit of relief on cloud but overall rev forecast is smaller. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:11:29 </td>
   <td style="text-align:left;"> $AAPL Two week ago this board was screaming 3TRILLION market Cap, Now what?SMFH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:09:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : More Competition Ought to Help Apple Stock, Not Hurt It https://www.stck.pro/news/AAPL/22009791 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:09:03 </td>
   <td style="text-align:left;"> $AAPL bears have no fear ammo 
IV dropping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:07:58 </td>
   <td style="text-align:left;"> $FIVN Serious insider buying at these levels $TSLA $MSFT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:07:17 </td>
   <td style="text-align:left;"> $AAPL   🍏 Massive Volume surge into the Close, 107.7 Million.  In the “ final second” of the Close, 9.5 Million AAPL Shares traded to the “Buy Side”.  AfterHours Volume is strong, 5.2 Million Shares on an uptick. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:06:30 </td>
   <td style="text-align:left;"> $AAPL - Tomorrow, the market will be all about Apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:03:45 </td>
   <td style="text-align:left;"> latex680848896b4581e4ea58fb0e5d6d667aTSLA earnings -&amp;gt; Great 
$AAPL earnings -&amp;gt; just claimed largest market share in China, how do you think the earnings will be? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:03:13 </td>
   <td style="text-align:left;"> $XELA Excellent new for investors 
$AAPL $MSFT $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:02:05 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $TSLA $NVDA 
👇 Bonds are spiking to moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:01:04 </td>
   <td style="text-align:left;"> $AAPL i would certainly only be short going into Tomm if you are playing this. Last EC was tell tale that Apple is lost
Affected by supply chain more so than Tesla. Tesla just reported supply chain was limited factor, and LAM just confirmed it. Short is the only way to go with this into earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:00:28 </td>
   <td style="text-align:left;"> $AAPL 120P Exp:19-Jan-24 ↓  🔥 Total(Day): $47,705 
$AAPL 135P Exp:20-Jan-23 ↓  🔥 Total(Day): $47,500 
$AAPL 145P Exp:18-Feb-22 ↑  🔥 Total(Day): $38,110 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:00:24 </td>
   <td style="text-align:left;"> $AAPL 195C Exp:17-Jun-22 ↑  🚀 Total(Day): $46,360 
$AAPL 205C Exp:19-Jan-24 ↓  🚀 Total(Day): $27,710 
$AAPL 220C Exp:19-Jan-24 ↓  🚀 Total(Day): $26,100 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:00:21 </td>
   <td style="text-align:left;"> $AAPL 185C Exp:20-Jan-23 ↓  🚀 Total(Day): $121,000 
$AAPL 185C Exp:20-May-22 ↑  🚀 &amp;lt;R&amp;gt; Total(Day): $6,194,775 
$AAPL 195C Exp:19-Jan-24 ↓  🚀 &amp;lt;R&amp;gt; Total(Day): $73,820 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 06:00:17 </td>
   <td style="text-align:left;"> $AAPL 175C Exp:15-Jul-22 --  🚀 Total(Day): $29,260 
$AAPL 175C Exp:17-Mar-23 ↑  🚀 Total(Day): $145,690 
$AAPL 185C Exp:14-Apr-22 --  🚀 Total(Day): $39,176 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:59:59 </td>
   <td style="text-align:left;"> $AAPL staying away from future guidance is the new thing, $IBM started the trend JPowell used it today and $AAPL should follow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:59:08 </td>
   <td style="text-align:left;"> $TSLA Is making cellphones now?! Watch out $AAPL 🥵🥵🥵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:58:56 </td>
   <td style="text-align:left;"> $AAPL Stock: More Competition Ought To Help, Not Hurt Apple https://investorplace.com/2022/01/aapl-stock-more-competition-ought-to-help-not-hurt-apple/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:58:46 </td>
   <td style="text-align:left;"> $AAPL back to $200 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:58:25 </td>
   <td style="text-align:left;"> $AAPL  show us who is really king in market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:58:04 </td>
   <td style="text-align:left;"> $TSLA beat and j POW said markets have already priced in these hikes. I’m not as bearish as most people $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:57:53 </td>
   <td style="text-align:left;"> $AAPL Just looking at the Stocktwits chart on all.  Striking similarity to the rise of the Nasdaq from 1996-2000.  Starting from 2017 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:57:31 </td>
   <td style="text-align:left;"> $AAPL nothing can go wrong 
              - spectacular iphone 13 sales 
              - vastly expanding m1 popularity 
              - iphone 14, m2 macbook air, airpods pro 2 on the horizon 
              - huge expectation for ar glasses in two years max 
              - also some speculations around apple car </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:57:04 </td>
   <td style="text-align:left;"> $fb $aapl $spy $qqq https://www.youtube.com/watch?v=4MuAo3sPDuE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:56:46 </td>
   <td style="text-align:left;"> $AAPL all this was is a shake out when Jpow spoke lol market will be back up PM  to easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:56:23 </td>
   <td style="text-align:left;"> $AAPL $WMT $UVXY  
 
Healthy Reminder:  
 
Month-end flows hit PBs desk starting tomorrow  
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:55:52 </td>
   <td style="text-align:left;"> $AAPL Bought a few more today. Now rise my precious! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:53:31 </td>
   <td style="text-align:left;"> $TSLA 1k lotto pays off 3 times in a week lol $AMZN $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:52:57 </td>
   <td style="text-align:left;"> $AAPL back to 170+ tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:52:19 </td>
   <td style="text-align:left;"> $AAPL 💰 💰….🍎👀♥️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:52:14 </td>
   <td style="text-align:left;"> $AAPL glorious day Mañana night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:51:43 </td>
   <td style="text-align:left;"> $NOW in the money . pay out in huge . 5k to 40k in just 3 weeks. $NFLX $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:51:26 </td>
   <td style="text-align:left;"> $AAPL what time is earnings tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:47:59 </td>
   <td style="text-align:left;"> $AAPL stock is ALWAYS a buy! There are harsh conditions around us, but Apple is rock solid! It was and it will be!⚡️🤷🏻‍♀️🤟 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:46:41 </td>
   <td style="text-align:left;"> $AAPL In what country is the labor market strong, Powell is a f—king jackass. Participation rate low, that’s why rate is low. Another libtard schmuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:46:38 </td>
   <td style="text-align:left;"> $AAPL tomorrow the king will jump back To his throne!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:45:44 </td>
   <td style="text-align:left;"> $AAPL https://invescohood.com/stock-market-apple-stock-analysis/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:45:37 </td>
   <td style="text-align:left;"> $AAPL 

Gimme a Friday pop to 167.

F interest rates.
F the Fed Balance Sheet.
F the supply chain.

Apple is #1 in China phone sales and they should but won’t lead with stock buyback and cash in hand.

Just please… keep Luca Maestri, the Doom Mumbler, off the forecast call with his negative spin of death. 

Phones &amp;amp; Services. 

I want 175 next week and of course the usual suspect race track touts like Dan Izvestia will go to $250 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:43:04 </td>
   <td style="text-align:left;"> $AAPL Company &amp;amp; Stock is strong theres no better place to be invested than with AAPL around the World. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:42:39 </td>
   <td style="text-align:left;"> $AAPL   It’s not possible for guidance to be sexy. 2 + 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:41:58 </td>
   <td style="text-align:left;"> $AAPL I guess they are tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:39:48 </td>
   <td style="text-align:left;"> $AAPL bought 165c at like 430 thinking earnings was today. woops lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:37:06 </td>
   <td style="text-align:left;"> $AAPL earnings is tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:36:51 </td>
   <td style="text-align:left;"> $AAPL not even trending. What’s going on here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:36:49 </td>
   <td style="text-align:left;"> $SPY Next up to the IV crush plate is $AAPL. Batting at an implied move of $6.35. You’re on deck options gamblers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:36:29 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 338.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:35:20 </td>
   <td style="text-align:left;"> $AAPL correction apple, Foxconn and lordstown would delete previous post if I could. Anyways about that apple car 🚗🔥🔥🔥🔥🚀 when 🌚 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:34:30 </td>
   <td style="text-align:left;"> $AAPL what time is the earnings? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:34:30 </td>
   <td style="text-align:left;"> $TSLA could save the market- they won’t. $AAPL will </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:33:04 </td>
   <td style="text-align:left;"> $AAPL like $TSLA the big danger both companies have is reliance on China centered global supply chain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:31:23 </td>
   <td style="text-align:left;"> $AAPL Do flowers shrivel up and die when Powell walks by them? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:26:32 </td>
   <td style="text-align:left;"> $TSLA 2B profit for a 1T 
$AAPL  posted 21b profit in Q3 2021 and it’s a 3T company…

Either Apple should be 10T or Tesla should be 300b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:25:53 </td>
   <td style="text-align:left;"> $AAPL Look at $TSLA and $MSFT  🟢🟢🟢 
 
Imagine $AAPL 💚💚💚 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:23:31 </td>
   <td style="text-align:left;"> $AAPL seems like 160 is new base here.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:23:19 </td>
   <td style="text-align:left;"> $AAPL pillow C loaded up on calls 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:22:51 </td>
   <td style="text-align:left;"> $AAPL I kinda have the feeling that $MSFT led the way, best earnings - immediate downtrend, then skyrockets... $TSLA will follow. Then $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:22:37 </td>
   <td style="text-align:left;"> $AAPL when rip? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:22:24 </td>
   <td style="text-align:left;"> $AAPL lordstown motors and apple sharing the same space but why 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:21:58 </td>
   <td style="text-align:left;"> $AAPL $TSLA getting hit hard AH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:21:03 </td>
   <td style="text-align:left;"> $AAPL is it me or is this still a steal at $159 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:20:58 </td>
   <td style="text-align:left;"> $AAPL I’m so ready for this stock to fall to the ground. I’m done reading all the articles on how a company that makes pocket computers is the best thing to buy during economic uncertainty. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:20:23 </td>
   <td style="text-align:left;"> $TSLA $Spy $AAPL $NVDA $Lmt
Guidance coming should be noice  going up we hit rock bottom today now we go up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:20:00 </td>
   <td style="text-align:left;"> $AAPL has a good Piotroski-F score of 7.00. This indicates a good health and profitability. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:19:16 </td>
   <td style="text-align:left;"> $AAPL after all of that it still didn’t create a new low For the week. Let’s see what tomorrow looks like though… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:18:17 </td>
   <td style="text-align:left;"> $AAPL see you at below $140 after the earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:17:24 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT $NFLX $AMZN 
Next is Apple (tomorrow), 
then Amazon (Feb 3). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:17:14 </td>
   <td style="text-align:left;"> $AAPL what&amp;#39;s the range for earnings? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:15:44 </td>
   <td style="text-align:left;"> $AAPL nothing new. oversold. aapl er should revive the market soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:15:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL just to make the market &amp;quot;seem&amp;quot; bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:15:15 </td>
   <td style="text-align:left;"> $AAPL 

Did apple end Green or is it ST error?! Just want to make sure this stock ends green today !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:14:45 </td>
   <td style="text-align:left;"> $AMZN  still very bullish my price target still $3500 hopefully soon but I have time in my calls. Support $2775 held strong at the close for the past 3 days. Let’s all focus on $2900 and above closing price to open the $3000 level technically. Patience is the key. The worst is now behind time to gradually move forward… $AAPL $SQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:12:29 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:12:12 </td>
   <td style="text-align:left;"> $AAPL tomorrow is apples turn to get rekt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:11:59 </td>
   <td style="text-align:left;"> $AAPL $TSLA Beat top and bottom line expectations.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:11:28 </td>
   <td style="text-align:left;"> $AAPL where the dumb bulls at? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:10:56 </td>
   <td style="text-align:left;"> $AAPL better deliver </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:10:23 </td>
   <td style="text-align:left;"> $AAPL mother fucker $AMZN i hate Wall Street and this fake money shit the USA created </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:10:22 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:10:20 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:10:09 </td>
   <td style="text-align:left;"> TL Private Wealth,has filed Form 13F for Q4 2021.Opened NEW positions in $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:10:00 </td>
   <td style="text-align:left;"> $AAPL tomorrow this will be below 150 after ER . Tsla will pull mkt down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:09:00 </td>
   <td style="text-align:left;"> $AAPL please save the market tomorrow🙏🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:08:29 </td>
   <td style="text-align:left;"> $MSFT $BTC.X $AAPL if y’all want to see true retards. Go to $BYND it’s seriously the best board to read for a good laugh. A vegan company partnering with fast food chains and people are all about it 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:08:27 </td>
   <td style="text-align:left;"> $AAPL the bar is set so high for ER do you really expect a beat? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:07:23 </td>
   <td style="text-align:left;"> $AAPL this may fall hardon earnings fk........ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:05:45 </td>
   <td style="text-align:left;"> $SPY skyrocketing after hours fuvk your puts sons of ****!!!  #fuckjeromepowell 
 
$SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:05:18 </td>
   <td style="text-align:left;"> $AAPL having a  hard time meeting Macbook Pro and iPhone 13 demand. Massive upgrade across businesses. I’m expecting a rather large beat on earnings. Curious how this market will accept it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:04:47 </td>
   <td style="text-align:left;"> $AAPL this is absolutely disgusting to watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:04:29 </td>
   <td style="text-align:left;"> $AMZN $AAPL 

I should of been a politician.. this crap has been going for 2 years. No real answers no real plan just beating around the questions with the same answer in different words. Makes a fortune. It’s a joke honestly. This meeting has been planned and the best Powell can say is we’re not sure yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:03:53 </td>
   <td style="text-align:left;"> $AAPL I’m glad I bought insurance put at +1.8%, closed flat but still gained 5.61% today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:03:17 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-26 Technical Analysis Video: 
https://www.youtube.com/watch?v=YWGGn9Hjbwo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:03:00 </td>
   <td style="text-align:left;"> $AAPL I hope you enjoyed your 2 days of green. No one is going to hold this over weekend with Russia and Ukraine situation. Expecting selloff tomorrow. Buy $LMT instead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:02:54 </td>
   <td style="text-align:left;"> $AAPL nothing changed… we are moving up to new ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:02:39 </td>
   <td style="text-align:left;"> $AAPL o well       👊🏻 🕶      🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:02:06 </td>
   <td style="text-align:left;"> $AMZN honestly it&amp;#39;s over folks will be hard to trade now moving forward market won&amp;#39;t drop drop until retailers are out or less options traders.......lots of fkry will happen before crashing market......charts mean shit 1000% news base........$TSLA $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:02:01 </td>
   <td style="text-align:left;"> $AAPL Closed slightly down. −0.090 (0.056%)  ST not correct. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:01:44 </td>
   <td style="text-align:left;"> $AAPL 

$VIX to 30 tomorrow. Bye bye $AAPL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:01:18 </td>
   <td style="text-align:left;"> $AAPL sub 120 AH prediction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:00:45 </td>
   <td style="text-align:left;"> $AAPL well at least we close green! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 05:00:40 </td>
   <td style="text-align:left;"> $TSLA all eyes on this and $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:59:58 </td>
   <td style="text-align:left;"> $AAPL Back to slightly Green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:59:24 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m all up for free markets and trade but this shit needs to be looked / investigated by the FTC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:59:08 </td>
   <td style="text-align:left;"> $SPY YOU JUST CAN&amp;#39;T WRITE A BERRER SCRIPT FOR BEARS.

APPL ER PROVED IRRELEVANT $AAPL $QQQ 

$TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:59:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT

SELL IT ALL, YOU’LL THANK ME LATER... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:58:59 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMD $NVDA $AAPL 
What we need is ; 
Bears buy hell lotta puts looking at today’s price action and go sleep then Tesla Beats big time and JP morgan turn the market super green and kill all puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:58:52 </td>
   <td style="text-align:left;"> $AAPL Gimme that Green homie.  BIG TIM up in this piece today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:58:00 </td>
   <td style="text-align:left;"> $AAPL please provide strong guidance Tim 🌈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:57:46 </td>
   <td style="text-align:left;"> $AAPL yield high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:57:40 </td>
   <td style="text-align:left;"> $AAPL At least be green today. Jeez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:57:33 </td>
   <td style="text-align:left;"> $AAPL seems like a safe place to park my money at this level. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:57:30 </td>
   <td style="text-align:left;"> $AAPL Too many manipulaters!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:57:27 </td>
   <td style="text-align:left;"> Shorting /VX at 27.85 

$SPY $BTC.X $TQQQ $UVXY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:56:52 </td>
   <td style="text-align:left;"> $AAPL Didn&amp;#39;t last. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:56:28 </td>
   <td style="text-align:left;"> $AAPL You have to be fucking kidding me it literally just changed a dollar while I was butting a trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:55:52 </td>
   <td style="text-align:left;"> $AAPL Slightly Green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:55:12 </td>
   <td style="text-align:left;"> $AAPL Hims &amp;amp; Hers Stock ( $HIMS ) Im Still Buying More !!!
https://youtu.be/IOqTA1sSKWg jhjbm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:54:39 </td>
   <td style="text-align:left;"> $aapl damn i am so sleepy. Can the market flash dip for a second or two so i can buy the dip at my desired pricr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:54:19 </td>
   <td style="text-align:left;"> $AAPL 😲😲😲😲😲😲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:54:16 </td>
   <td style="text-align:left;"> $SPY $BTC.X $QQQ $AAPL $TSLA 
 
Who is JDADDY gonna get to invest in his MASSIVELY INFLATED, PONZI SCHEME, ASSET BUBBLE now that the Boomers have cashed out at all time high prices and valuations? 
 
JDADDY need more suckas!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:54:10 </td>
   <td style="text-align:left;"> $TSLA watch this hit ath after hours $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:53:21 </td>
   <td style="text-align:left;"> $AAPL Powell and his crew should answer what lead to inflation at first instead of way to tackle it. If they were asleep past couple of years. ...m.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:53:12 </td>
   <td style="text-align:left;"> $AAPL earnings will be absoluteLy scorching tomorrow.  May not matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:52:45 </td>
   <td style="text-align:left;"> $AAPL holding thru earnings at this point doesn’t seem bad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:52:17 </td>
   <td style="text-align:left;"> $AAPL thoughts on earnings? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:52:01 </td>
   <td style="text-align:left;"> $AAPL The struggle is real. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:51:31 </td>
   <td style="text-align:left;"> $AAPL I feel lucky to be in at 158, tomorrow is rip city. I will always own $AAPL, but this is a unique opportunity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:51:00 </td>
   <td style="text-align:left;"> $AAPL BEAR BEAR BIDEN MARKET </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:50:11 </td>
   <td style="text-align:left;"> Added some apples like a true sheep $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:50:08 </td>
   <td style="text-align:left;"> $MSFT $AAPL $QQQ heavy sell vol… bigger players involved… staying away! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:49:46 </td>
   <td style="text-align:left;"> $QQQ $TSLA $AAPL bought more Friday calls..... lets take a risk on ER... $MSFT made me money today just take your profits at the top and enjoy the decline for more calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:49:35 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $TSLA $AAPL  
 
Truth! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:49:01 </td>
   <td style="text-align:left;"> $AAPL For anyone trading AAPL, come THROUGH freely YO! Latest 2022 Updates and Discussions here 
https://twitter.com/Thorismyfav/status/1486440993788665856 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:49:00 </td>
   <td style="text-align:left;"> $TSLA after $NFLX crash .. next in line $TSLA $AMZN and $AAPL $GOOGL  will save the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:48:26 </td>
   <td style="text-align:left;"> $AAPL 02/18 180c for .60 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:48:26 </td>
   <td style="text-align:left;"> $TSLA is the new safe haven, not $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:48:17 </td>
   <td style="text-align:left;"> Unusual Option Alert on $AAPL $1,674,030 call sweep traded with $120.0 strike expiring on 2024-01-19. Via: https://www.stockgrid.io/optionsflowcumulativestats/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:48:17 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:47:49 </td>
   <td style="text-align:left;"> $AAPL 

Let’s break this and end the day with green!

Have had enough of this red shits! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:47:39 </td>
   <td style="text-align:left;"> $AAPL  
This is driving people nuts, fuck J the dog powell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:47:26 </td>
   <td style="text-align:left;"> $AAPL oh cmon just fill.. i want this dip so i can sell tomorrows rip! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:47:20 </td>
   <td style="text-align:left;"> $TSLA earnings at 5:30 for noobs asking link below $AAPL $SPY  
#fuckjeromepowell 
 
https://ir.tesla.com/#tab-quarterly-disclosure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:46:02 </td>
   <td style="text-align:left;"> $TSLA $AAPL these can save markets, else fasak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:45:40 </td>
   <td style="text-align:left;"> $AAPL 

What a shit show , money managers are crooks. I feel sorry for those forced to sell. Hang in their </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:45:33 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMZN $MSFT next time, please vote for the better candidate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:44:23 </td>
   <td style="text-align:left;"> $AAPL 155 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:44:08 </td>
   <td style="text-align:left;"> $AAPL hold over night? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:44:06 </td>
   <td style="text-align:left;"> $AAPL should be green to lead the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:42:43 </td>
   <td style="text-align:left;"> $AAPL earnings will predict the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:42:27 </td>
   <td style="text-align:left;"> $AAPL 😳😳😳😳 never forget </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:41:58 </td>
   <td style="text-align:left;"> $AMD $INTC $AAPL $TSLA all the dickheads around the world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:41:53 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:41:39 </td>
   <td style="text-align:left;"> $AAPL there trying to get your calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:41:33 </td>
   <td style="text-align:left;"> $AAPL elevator back up to $161??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-27 04:41:27 </td>
   <td style="text-align:left;"> $AAPL scary tomrrow will be worse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:43:58 </td>
   <td style="text-align:left;"> $TSLA hate musk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:43:55 </td>
   <td style="text-align:left;"> $TSLA TSLA will fix supply issues for those too lazy and want stay home </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:43:53 </td>
   <td style="text-align:left;"> $TSLA the HUGE CRASH continues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:43:50 </td>
   <td style="text-align:left;"> $TSLA fuck powell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:43:38 </td>
   <td style="text-align:left;"> $TSLA when will it go to $1500? 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:43:22 </td>
   <td style="text-align:left;"> $TSLA  all a mirage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:43:07 </td>
   <td style="text-align:left;"> $TSLA without $25k car how would they sell 3mil cars per year by 2025? FSD is pipe dream, governments never allow to 100% FSD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:57 </td>
   <td style="text-align:left;"> $TSLA Will go to 860 before going up! This is where 1100 point swing started 2 days ago! Whole market goes back to dow low like 33000 n change then up trend I know Im fucked and an idiot why thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:57 </td>
   <td style="text-align:left;"> $TSLA 100% success rate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:55 </td>
   <td style="text-align:left;"> $TSLA always dangerous to short this monster…see a lot of bearish posters about to be down big </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:43 </td>
   <td style="text-align:left;"> $TSLA Optimus humanoid robot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:41 </td>
   <td style="text-align:left;"> $DWAC $twtr $t $tsla what if the side affect of jabbed and boosted is sterility and the only people that can reproduce voted for Trump? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:38 </td>
   <td style="text-align:left;"> $TSLA record profits and this shit tanks wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:20 </td>
   <td style="text-align:left;"> $SPY few black swan events pending. Als you have to expect the big boys to throw tantrum until Fed turns dovish again. Hawkish Fed was the last thing they wanted, and will keep market fucking volatile until end of March. 380PT by February. $tsla is focusing on fucking robots for year 2022. We know everything now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:16 </td>
   <td style="text-align:left;"> $TSLA 1/3 of my port in TSLA calls. COME ON ELON TWEET SOME DUMB SHIT THAT MAKES THIS MOOOOOON 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:15 </td>
   <td style="text-align:left;"> $TSLA I thought $1100 after cc? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:10 </td>
   <td style="text-align:left;"> $TSLA Lots of gaps to fill on the $500’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:10 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:42:03 </td>
   <td style="text-align:left;"> $TSLA Remarkable that the bears think they’re winning here😂! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:41:38 </td>
   <td style="text-align:left;"> $AAPL why anyone would short this stock after m1 chips is pretty baffling to me. m2 on the horizon. iPhone 14 on the horizon. eventual house made modems on the horizon. graphics chips on the horizon. this is like buying $NVDA, $INTC, $TSLA, and AAPL all in one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:41:38 </td>
   <td style="text-align:left;"> $TSLA how low will this overhyped piece of junk go ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:41:27 </td>
   <td style="text-align:left;"> $TSLA makes no sense to make a 25k car in this market.  Same labor cost, same logistics and supply chain. Issues and costs. Probably negative margins but can make it up in software. Not worth it now. Maybe some place where low cost of living is like India and China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:41:23 </td>
   <td style="text-align:left;"> $TSLA 20 mins until futures fly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:41:16 </td>
   <td style="text-align:left;"> $TSLA gap pre market? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:41:12 </td>
   <td style="text-align:left;"> $TSLA taxation is theft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:40:54 </td>
   <td style="text-align:left;"> $TSLA Elon more focused on robotics and space, its time it consolidates! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:40:48 </td>
   <td style="text-align:left;"> $TSLA way to go you greedy Joe Biden  
 
destroying American business by taxing them to death </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:40:47 </td>
   <td style="text-align:left;"> You can peek inside Tesla&amp;#39;s Texas Gigafactory using the Snap Map - Mashable $TSLA  https://apple.news/AKvk6IsA7Ry-e48a2mBFrBg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:40:27 </td>
   <td style="text-align:left;"> Tesla confirms Model Y production started at Gigafactory Texas, now working on final certification - Electrek $TSLA  https://apple.news/AAdcSVgJeQuun4jGmfOJH-A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:40:17 </td>
   <td style="text-align:left;"> $TSLA bears can’t see the world around them developing. disruptive tech, and especially Tesla’s products will transform the way humans live. and for the better 🔐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:40:05 </td>
   <td style="text-align:left;"> $TSLA premium burner for tomorrow 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:40:01 </td>
   <td style="text-align:left;"> $TSLA incoming 600 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:39:55 </td>
   <td style="text-align:left;"> $TSLA 
Have to wonder what reaction will be pre-market to a very lack luster Report.
AH Down to $929.00
I don’t think that bodes well for tomorrow.
I don’t know why we should expect any large pop tomorrow.
Mention of expenditures for factories etc. was like a wet blanket. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:39:55 </td>
   <td style="text-align:left;"> $TSLA Today was gayer than my sleepover party with my step dad last night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:39:53 </td>
   <td style="text-align:left;"> $TSLA g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:39:51 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #14 ticker with sweep activity where institutions are trading options urgently with 9.8K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:39:43 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX Now all we need is netflix to stop being stubborn and cmon down to join the party 🔪🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:39:12 </td>
   <td style="text-align:left;"> $TSLA Got to blame someone or something for massive correction incoming! Tesla n Apple scape goats my Twits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:38:53 </td>
   <td style="text-align:left;"> $MSFT beats, and no one cares, $TSLA beats, and no one cares. No one cares right now and that is bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:38:51 </td>
   <td style="text-align:left;"> $TSLA  I feel a little dumb for not going more YOLO a few years ago and making this like 80% of my portfolio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:38:41 </td>
   <td style="text-align:left;"> $TSLA f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:38:17 </td>
   <td style="text-align:left;"> $TSLA The Austin, Texas, company made $5.5 billion last year compared with the previous record year of $3.47 billion in net income posted in 2020. It was the electric vehicle and solar panel maker’s third straight profitable year. Back to 1000&amp;#39;s within a few days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:38:14 </td>
   <td style="text-align:left;"> Who the hell makes $7.50/share in one day on a stock then turns around and makes $65/share the same day on another stock?! Seriously, WHO DOES THAT?? 
 
His free webinars are right here: http://bit.ly/GSPandDTW 
 
The answer is @DayTraderWayne today on $SRRA and $TSLA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:38:12 </td>
   <td style="text-align:left;"> $TSLA  this stock might hang around these levels for a bit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:38:08 </td>
   <td style="text-align:left;"> $TSLA if you are not whale then never short this stock! 
Let them play and you enjoy ride and don’t forget to add more if it dip. And right now it’s dip!!!🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:37:51 </td>
   <td style="text-align:left;"> $TSLA 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:37:47 </td>
   <td style="text-align:left;"> $TSLA Elon is the sexiest man in the game right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:37:39 </td>
   <td style="text-align:left;"> $TSLA this is going to be the thread that unravels the entire market very soon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:37:39 </td>
   <td style="text-align:left;"> $TSLA Crooked mms Boy I hate those Guys lol lmao easy$ kiddos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:37:38 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:37:35 </td>
   <td style="text-align:left;"> $TSLA  is about 29% of my portfolio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:37:27 </td>
   <td style="text-align:left;"> $TSLA.. never short Tesla. Bears lesson learned </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:37:25 </td>
   <td style="text-align:left;"> $TSLA The Austin, Texas, company made $5.5 billion last year compared with the previous record year of $3.47 billion in net income posted in 2020. It was the electric vehicle and solar panel maker’s third straight profitable year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:37:23 </td>
   <td style="text-align:left;"> $TSLA 
That’s all folks.
Nothing but headwinds ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:37:12 </td>
   <td style="text-align:left;"> $TSLA damn meet Kevin isn’t stupid lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:36:55 </td>
   <td style="text-align:left;"> $TSLA Red wave or green light? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:36:55 </td>
   <td style="text-align:left;"> $TSLA 1100 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:36:47 </td>
   <td style="text-align:left;"> $TSLA never short this stock! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:36:46 </td>
   <td style="text-align:left;"> $TSLA ): </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:36:31 </td>
   <td style="text-align:left;"> $TSLA This is a picture of all bears and bulls today that went back-and-forth with a 1200 PT and a 700 PT.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:36:29 </td>
   <td style="text-align:left;"> $TSLA Drop in AM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:36:18 </td>
   <td style="text-align:left;"> $TSLA  the longer you own this stock the more you realize you are the only one who has any idea what&amp;#39;s going on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:36:16 </td>
   <td style="text-align:left;"> $TSLA With IVX falling off the cliff tomorrow, this was the short term play to pick up 50% overnight with about a 90% POP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:36:07 </td>
   <td style="text-align:left;"> $TSLA 1300 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:36:00 </td>
   <td style="text-align:left;"> $TSLA https://apnews.com/article/business-austin-texas-earnings-tesla-inc-097d412de884a4bb61efb49300ecf2e7 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:35:47 </td>
   <td style="text-align:left;"> $TSLA bulls, please, I beg you, give this one last pump in the am so that I can load up on cheap puts! If this opens green then I’m buying puts!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:35:44 </td>
   <td style="text-align:left;"> $TSLA the drop tomorrow will be pretty epic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:35:40 </td>
   <td style="text-align:left;"> $TSLA literally no response, and you got a more hostile fed, with supply chain problems, and you sitting here with a 300 p/e. This pos might finally fall. 💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:35:34 </td>
   <td style="text-align:left;"> $TSLA you got Hawkish Fed. Massive geo political tension with NK, China, and Russia... supply chain constraints everywhere, and only just covered omicron variant with 500 more potent variants to come. Bond is surging and only pussy boy Ackman thought he bought the best Netflix dip after crying world end. $nflx $SPY $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:35:24 </td>
   <td style="text-align:left;"> $TSLA Based on record breaking results, why wouldn&amp;#39;t TSLA be surging higher? Three times TSLA made it to $1200 and beyond, each time crashing to as low as $850. One would think that with this kind of performance that it would have at minimum recouped half of the difference between $940 and its $1200 highs to right about $1070 in the after hour market. Sadly, it hasn&amp;#39;t been able to make it to $1000, let alone its highs of the day, that is, $986. Whereas this day trader extraordinaire thought with this ER that it would surge out of reach, could it be rather that I will get another crack at it tomorrow at these levels and quite possibly lower? Seeing as how lackluster it is tonight, for whatever reason, I very well might. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:35:21 </td>
   <td style="text-align:left;"> $TSLA got 10 more shrs @ 930.75 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:35:21 </td>
   <td style="text-align:left;"> $TSLA can we stop with the 500 and 1300 price targets over the next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:35:12 </td>
   <td style="text-align:left;"> $TSLA is having a fire sale! 🚨 We are </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:35:01 </td>
   <td style="text-align:left;"> $TSLA easiest stock to own when you ae long the share! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:35:00 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $TSLA $BA 
👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:34:44 </td>
   <td style="text-align:left;"> $TSLA 👀👀👀 current action in this forum 🤪🤪😎😎😮‍💨😮‍💨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:34:43 </td>
   <td style="text-align:left;"> $TSLA if you think FSD is here in 2022 you are nuts. Also I’ve been saying see you at $450 for a while now, I’m changing that to $400. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:34:43 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ Rumor has it....Market is fixed 
$AMZN $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:34:40 </td>
   <td style="text-align:left;"> $NIO $TSLA fan boy has had enough of the line up to go charge so, he decided to try out NIO’s battery swap 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:34:36 </td>
   <td style="text-align:left;"> $TSLA I bet there won’t be one Tesla car on the road in 59 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:34:26 </td>
   <td style="text-align:left;"> $TSLA bulls can you pamp this over 1k for me or not..i need to do something to it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:34:24 </td>
   <td style="text-align:left;"> $TSLA if this gets hammered I will be going all in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:34:17 </td>
   <td style="text-align:left;"> $TSLA Robots to do jobs we don’t want to do?!! What is this.. Black Mirror? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:34:02 </td>
   <td style="text-align:left;"> $TSLA if history teaches you anything, never short this stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:34:02 </td>
   <td style="text-align:left;"> $TSLA Musk isn’t doing shareholders any favors by being on these conference calls. Hire some PR people for the love of Christ. It’s embarrassing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:33:58 </td>
   <td style="text-align:left;"> $TSLA -55 AH to +37 to -10. Makes sense! Manipulater af </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:33:34 </td>
   <td style="text-align:left;"> $TSLA big red tsunami on this turd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:33:33 </td>
   <td style="text-align:left;"> $TSLA NO ONES COMING GET OUT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:33:20 </td>
   <td style="text-align:left;"> $TSLA wow red..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:33:16 </td>
   <td style="text-align:left;"> $TSLA  by 2032 there will be no humans on the earnings calls.  Just robots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:33:14 </td>
   <td style="text-align:left;"> $LCID $TSLA $aapl market is far far away from reality numbers right now. Nobody cares about catalysts, earning beats, nothing. Now rate hike in march which means fear market till march then a fukin sell off on that day because of hike. This year will be similar to last year... flippers making money... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:33:07 </td>
   <td style="text-align:left;"> $TSLA I don’t really know how there are any AH buyers now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:32:52 </td>
   <td style="text-align:left;"> $TSLA oh somethings happening, someone just stepped in with a sell wall at 933 so it doesn’t go back up. Not the arca specialist </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:32:26 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-26 Technical Analysis Video: 
https://www.youtube.com/watch?v=9KbLoIavutI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:32:13 </td>
   <td style="text-align:left;"> $TSLA whipsaw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:32:03 </td>
   <td style="text-align:left;"> $TSLA (Wed 01-26 WS recap)  
 
Wall Street gains evaporate, S&amp;amp;P 500 ends lower on FOMC QT tightening timeline http://www.streetinsider.com/ETFs/Wall+Street+gains+evaporate%2C+S%26P+500+ends+lower+on+Fed+tightening+timeline/19504684.html via @Street_Insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:32:01 </td>
   <td style="text-align:left;"> $TSLA So basically no new products besides the absurd fake robot, no split, another promise about FSD that people aren’t buying into anymore, and more supply chain constraints. Obviously the stock didn’t go higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:32:00 </td>
   <td style="text-align:left;"> $TSLA Star Trek isn&amp;#39;t Communism come true, it&amp;#39;s Scarcity Eliminated. Could the Tesla Bot be the path to eliminating scarcity? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:31:58 </td>
   <td style="text-align:left;"> $TSLA gonna be red big tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:31:36 </td>
   <td style="text-align:left;"> $TSLA drop it like it&amp;#39;s hot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:31:34 </td>
   <td style="text-align:left;"> $TSLA $550 pt before 10/1/21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:31:30 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:31:14 </td>
   <td style="text-align:left;"> $TSLA panic selling, before day close, in 3..... 2......... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:31:10 </td>
   <td style="text-align:left;"> $TSLA am moving to Switzerland </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:31:10 </td>
   <td style="text-align:left;"> $TSLA what is Elon Musk doing with quarterly 2 billion in profit? 

Focusing on fucking robot Japanese high school students make in their sleep. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:30:40 </td>
   <td style="text-align:left;"> $TSLA  when you can forget a company is making a robot that everyone laughs at, that&amp;#39;s a company that will grow forever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:30:39 </td>
   <td style="text-align:left;"> $TSLA Betting against a Rocket Scientist, Profits were up 700% over last year and Elon said they would grow by %50 this year with supply chain issues still present.  If you are short you better get out soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:30:37 </td>
   <td style="text-align:left;"> $TSLA Option killa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:30:33 </td>
   <td style="text-align:left;"> $TSLA can&amp;#39;t be too greedy I&amp;#39;m good with $1100 on the open tomorrow and a gradual increase to $1300 EOD Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:30:21 </td>
   <td style="text-align:left;"> $TSLA thanks for buying my covered calls bulls. Now get the fuck outta here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:30:18 </td>
   <td style="text-align:left;"> $TSLA Down -$40 tomorrow 
Mr pie hole does it again 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:30:14 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:30:10 </td>
   <td style="text-align:left;"> $TSLA puts and calls are worthless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:30:08 </td>
   <td style="text-align:left;"> $TSLA 
Meet Kevin bought. Run away.

https://youtu.be/zY1dy6sOjzQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:30:06 </td>
   <td style="text-align:left;"> $TSLA will this print tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:29:48 </td>
   <td style="text-align:left;"> $TSLA  I had completely forgotten about the robot but now I believe.  The robot will come true </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:29:37 </td>
   <td style="text-align:left;"> $TSLA is there any place where I can check what options will be worth after the iv crush? 

I’m not sure if options profit calculator works for an er or not 

I have TOS as well. 

Any ideas to get some sort of idea? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:29:18 </td>
   <td style="text-align:left;"> $TSLA this specialist on the arca is straight up hustling people lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:29:09 </td>
   <td style="text-align:left;"> $TSLA  this is the most aggressive company.  They will try anything and don&amp;#39;t care if people laugh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:28:49 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/fKVRrlN7U5I thing yhuuuuuuge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:28:43 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:28:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL tsla failed to amaze the crowd. Rate hike coming! Aapl er drops as usual. Hahaha bears will linger. Daddy joe and daddy jpow wont spoil you anymore. 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:28:37 </td>
   <td style="text-align:left;"> $TSLA This AH price action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:28:34 </td>
   <td style="text-align:left;"> $TSLA  I bought at 970 in AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:28:33 </td>
   <td style="text-align:left;"> $TSLA Sometimes u have to sift through the bullshit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:28:23 </td>
   <td style="text-align:left;"> $TSLA 
“Tesla (TSLA) releases Q4 2021 financial results: beat expectations with over $2 billion in profit”

By Fred Lambert 

https://electrek.co/2022/01/26/tesla-tsla-q4-2021-financial-results/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:28:18 </td>
   <td style="text-align:left;"> $TSLA yes after hours tells a story personally I think with the whole  fed thing and rates The momentum is not there if it was this should hit 1k or more with these earnings but there bigger issues and big whales don’t want pump somthing that’s going get sold off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:28:14 </td>
   <td style="text-align:left;"> $TSLA Aisan markets are ready to dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:28:07 </td>
   <td style="text-align:left;"> $TSLA  we wake up to $1050! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:27:40 </td>
   <td style="text-align:left;"> $TSLA I think it will gap up tomorrow. Buy back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:27:39 </td>
   <td style="text-align:left;"> $TSLA the bears thank you Mr. Powell bears 🐻 go brrrr🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:27:35 </td>
   <td style="text-align:left;"> $TSLA Question for both classroom A and classroom B: What is the price tomorrow??!!😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:27:33 </td>
   <td style="text-align:left;"> $TSLA https://teslanorth.com/2022/01/26/tesla-insurance-set-for-europe-next-after-wider-u-s-rollout/ 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:27:33 </td>
   <td style="text-align:left;"> $TSLA You nuts have outdone yourselves on this one today.  Such a demonstration of solid investing.  875 to 975 to 925? Just a bunch of kindergartners at the controls alternating between uncontrollable FOMO and diaper soiling fear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:27:26 </td>
   <td style="text-align:left;"> $TSLA nice sell off. $850 pt is generous for tomorrow.’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:27:19 </td>
   <td style="text-align:left;"> $TSLA the same clown suggested nuking the poles of Mars, which is ridiculous. No intelligent scientist would have said something so retarded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:27:15 </td>
   <td style="text-align:left;"> $TSLA exit in first 30 mins tomorrow it will tank hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:27:12 </td>
   <td style="text-align:left;"> $TSLA Wow it’s up 61 cents AH. Stellar earnings! 👍🏽🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:27:05 </td>
   <td style="text-align:left;"> $TSLA good lord shorts took this down from 970s…expecting pop back up soon or tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:27:01 </td>
   <td style="text-align:left;"> $TSLA The last 5-10 minutes should make it clear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:26:59 </td>
   <td style="text-align:left;"> $TSLA The retards are out fucking desperate thinking posting on a message boards going to help their position boy nothing but a bunch of fucking dopes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:26:54 </td>
   <td style="text-align:left;"> $TSLA why is this still showing green rn? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:26:44 </td>
   <td style="text-align:left;"> $TSLA stock split confused the idiots, this is worth less than 187 even elon took some profits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:26:33 </td>
   <td style="text-align:left;"> $TSLA lucid makes a better car </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:26:26 </td>
   <td style="text-align:left;"> $TSLA Short this stock. It will come down. Look at the Monthly chart and Nasdaq is also down in Monthly chart. Big money is on the way. Sell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:26:18 </td>
   <td style="text-align:left;"> $TSLA Elon didn&amp;#39;t announce that he was going to personally jerk off every shareholder that&amp;#39;s why it&amp;#39;s going down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:26:17 </td>
   <td style="text-align:left;"> $TSLA  got my ass kicked in TSLA after hours but still came out green on the day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:26:13 </td>
   <td style="text-align:left;"> $TSLA look like 600-650$ on the way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:26:09 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla posts record profits, expects supply chain woes to persist https://www.stck.pro/news/TSLA/22015202 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:26:03 </td>
   <td style="text-align:left;"> $TSLA Elon will give guidance on El Salvador in 30 minutes,,,he has to take of doggie coin first,,,,Elon is asking Prince Andrew to move to El Salvador and be the face of doggie style coin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:25:58 </td>
   <td style="text-align:left;"> $TSLA long here 😎😎 enjoying all the comments tonight.. 🙃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:25:49 </td>
   <td style="text-align:left;"> $TSLA  somebody said fuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:25:46 </td>
   <td style="text-align:left;"> $TSLA will be in the 300’s before you know it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:25:26 </td>
   <td style="text-align:left;"> Tesla – Starting to Look Safe to Short $TSLA https://skr.ma/hJ5DxynkGLwa4zAN9 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:25:24 </td>
   <td style="text-align:left;"> $TSLA Damn my straddle done got straddled.  I&amp;#39;ll be lucky to retain 50%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:25:22 </td>
   <td style="text-align:left;"> $TSLA this stock is whack. From 965 to 928…. Good gosh. My little 50 shares will do nothing when I sell. The damn ER was about as good as it could be but evidently good ER don’t mean anything in this market. Wow. Heck I’m better off with AAL and MAR. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:25:14 </td>
   <td style="text-align:left;"> $TSLA Smart investors understand how bearish that CC was in 2022 no QE market. Elon Musk sold at top and sniffing Mars dust. The dude sounded off.

The world knew tesla would easily beat watered down earnings expectation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:56 </td>
   <td style="text-align:left;"> $TSLA 1 dolla make me holla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:55 </td>
   <td style="text-align:left;"> $TSLA will wait to buy it under 80$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:50 </td>
   <td style="text-align:left;"> $TSLA this shit about to get NETFLIXED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:49 </td>
   <td style="text-align:left;"> $TSLA  managed to beat earnings like you expected. However, they’ll be limiting 2022 production due to supply chain issues &amp;amp; will not introduce new vehicles.

@gvstocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:44 </td>
   <td style="text-align:left;"> $TSLA I’m not a bear (own two cars and solar), but if this doesn’t rip higher, the chart could fail, changing the long term trend. Look: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:35 </td>
   <td style="text-align:left;"> $TSLA If this can burn to $750 by next Friday…that works </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:28 </td>
   <td style="text-align:left;"> $TSLA same cars, new and growing competition, no new products. To many production issues to make new products doesn’t seem good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:23 </td>
   <td style="text-align:left;"> $TSLA hold on guys, tomorrow is the day when we blow the shorts to the hell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:16 </td>
   <td style="text-align:left;"> $TSLA 🤣🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:11 </td>
   <td style="text-align:left;"> $TSLA this will continue to rise for no reason but I’ll take it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:03 </td>
   <td style="text-align:left;"> $TSLA Futures is green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:24:03 </td>
   <td style="text-align:left;"> $TSLA options don’t get paid earnings week, a move will come next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:23:57 </td>
   <td style="text-align:left;"> $TSLA wait for Cramer to upgrade this. Then you know for sure you should definitely put all your money into it at this level. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:23:27 </td>
   <td style="text-align:left;"> $TSLA came to see bears come out for a second lolol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:23:22 </td>
   <td style="text-align:left;"> $TSLA 800s definitely in play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:23:21 </td>
   <td style="text-align:left;"> $TSLA the winner will be in tomorrow morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:23:07 </td>
   <td style="text-align:left;"> $TSLA yeszzzzz Down she goes finally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:23:07 </td>
   <td style="text-align:left;"> $TSLA updated PE? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:23:00 </td>
   <td style="text-align:left;"> does $RIVN have a structural battery in the works? $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:22:57 </td>
   <td style="text-align:left;"> $TSLA A great earnings report and it’s basically flat in after hours with a joke the stock has become </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:22:56 </td>
   <td style="text-align:left;"> $TSLA open price tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:22:52 </td>
   <td style="text-align:left;"> $TSLA why is this not back to $1000 ???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:22:40 </td>
   <td style="text-align:left;"> $TSLA futures fading.. tesla fading.. down $60 already from days high. 😬 Not good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:22:33 </td>
   <td style="text-align:left;"> $TSLA Elon said fsd will be better than human drivers this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:22:32 </td>
   <td style="text-align:left;"> $TSLA will close $930 as expected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:22:30 </td>
   <td style="text-align:left;"> $TSLA why’s this falling now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:22:19 </td>
   <td style="text-align:left;"> $TSLA having fun with these crazy wild swings. Get it retail! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:22:14 </td>
   <td style="text-align:left;"> $TSLA I don’t know it’s Tesla really want to pump it would have done it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:22:05 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s close out in the 800s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:22:04 </td>
   <td style="text-align:left;"> $TSLA Scary to think that the average Elon fan is probably also a Kardashian fan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:21:53 </td>
   <td style="text-align:left;"> $TSLA how’d I do in the fan art </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:21:47 </td>
   <td style="text-align:left;"> $TSLA lol they are off the hook with this price action .. manipulation at its finest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:21:45 </td>
   <td style="text-align:left;"> $TSLA mostly down to 860 tomorrow and then up may be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:21:39 </td>
   <td style="text-align:left;"> $TSLA 

Lovely day in paradise! Nailed this trade in my Small Account Challenge discord today! Totally crushed it! 💸💸💸💰💰💰💥💥💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:21:29 </td>
   <td style="text-align:left;"> $TSLA 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:21:22 </td>
   <td style="text-align:left;"> $TSLA Put day traders and call day traders gained today. $800 put 3 weeks out changed from $17-32.. quick win.. hey .. its on my WL. My ass scared of buying puts on Tesla.. coz its not a stock.. it is the mommy of MEME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:21:20 </td>
   <td style="text-align:left;"> $TSLA joke am out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:21:16 </td>
   <td style="text-align:left;"> $FB $AAPL $TSLA $GOOG  
 
$F  
 
Edward Jones: $21.77 &amp;quot;Hold&amp;quot; January 3rd, 2022. 
https://www.edwardjones.com/us-en/media/3641 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:21:07 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL  Bought puts! Dont see going up after earnings. Why Elon sold if he had confidence? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:20:54 </td>
   <td style="text-align:left;"> $TSLA approximately 42 minutes to gtfo. Super hawkish Fed in awhile. Analyst PT downgrades, macro dumps, and north Korea shooting projectiles while Russia is ready to fuck up Ukraine. China waiting to swallow up Taiwan. 

And Biden said son of a bitch on live TV. Senile. $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:20:46 </td>
   <td style="text-align:left;"> $TSLA upgrades coming...you&amp;#39;ll see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:20:40 </td>
   <td style="text-align:left;"> $TSLA guidance sounded extremely uncertain and every time they deferred to robots for what is exciting and the future hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:20:38 </td>
   <td style="text-align:left;"> $TSLA me and my Optimus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:20:38 </td>
   <td style="text-align:left;"> $TSLA futs gapping down! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:20:20 </td>
   <td style="text-align:left;"> $AABB $TSLA $AAPL $MSFT $GOOGL  If Q1 2022 is even near as similar to Q1 2021 in small caps set it and forget it ASAP https://www.marketscreener.com/news/latest/U-S-small-cap-stocks-may-be-signalling-market-bottom--37649996/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:20:08 </td>
   <td style="text-align:left;"> $INDI Tesla call was informative they are not launching new models just loading up on existing lineup supply constrained buying all the chips they can get!  We supply $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:20:01 </td>
   <td style="text-align:left;"> $TSLA call and puts in action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:19:55 </td>
   <td style="text-align:left;"> $TSLA IMO the only thing that will keep the call buying program at bay tomorrow morning is if NASDAQ (/NQ) sees some volatility overnight and $TSLA gaps under 900. $NDX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:19:50 </td>
   <td style="text-align:left;"> $TSLA very boolish for tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:19:39 </td>
   <td style="text-align:left;"> $TSLA SS1983 come out and face the music. According to you the expert in digesting corporation earnings and profit reports, TESLA was a fraud and made no money. Come out and play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:19:24 </td>
   <td style="text-align:left;"> $TSLA $spy no confidence </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:19:20 </td>
   <td style="text-align:left;"> $TSLA 

The was not a good call. Numbers were ok. Really nothing impressive. 

red day tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:19:13 </td>
   <td style="text-align:left;"> $TSLA regardless of if you are a bull or bear, if you are holding options like me that expire Friday....we are all fked by this manipulated piece of garbage from the MM, HF, Fed. Embrace that for once we are all on the same side getting our asses pounded by the same criminal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:19:09 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:19:05 </td>
   <td style="text-align:left;"> $TSLA no new cars, delayed cyber til 2023 and sounded like a lot of issues with costs to make the truck. There focus is now on robots and taxi’s during a time there competition is getting the most fierce. Doesn’t seem like this will work </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:18:52 </td>
   <td style="text-align:left;"> $TSLA pretty much unchanged there, interesting move on a higher p/e tech name, gives a little insight into what we can expect going further </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:18:38 </td>
   <td style="text-align:left;"> $TSLA Will try that $700 put again soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:18:36 </td>
   <td style="text-align:left;"> $TSLA see you guys at 870 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:18:24 </td>
   <td style="text-align:left;"> $TSLA Premium Room Real-Time Notes- 
- additional details at itsallaboutheoptions.com Private Chat or ST Premium Room https://stocktwits.com/r/itsallaboutheoptions is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:18:21 </td>
   <td style="text-align:left;"> $TSLA Ppl talking about cyber truck...how many people will use cyber truck than passenger car...Elon is smart business man and he wants  
 to utilize the market well  and he don&amp;#39;t want to introduce new vehicles since he is generating more revenue here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:18:15 </td>
   <td style="text-align:left;"> $TSLA Teslas next gigafactory should be in Turkey and Florida </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:18:08 </td>
   <td style="text-align:left;"> $TSLA understands the Osborne Effect.  They are going to maximize sales of the S 3 X Y  Models while at the same time secretly maximizing design of CT, Semi, Roadster, 25K model (35K for inflation 😂)  They are not dumb and are students of tech history.  
 
https://en.wikipedia.org/wiki/Osborne_effect </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:18:07 </td>
   <td style="text-align:left;"> $TSLA Why is this down after beating earnings? wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:18:06 </td>
   <td style="text-align:left;"> $TSLA snagged 100 at 890, out at 930… that’s how this game works 💪🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:18:03 </td>
   <td style="text-align:left;"> $TSLA no new models released this year + no $25k car = 🚀 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:17:44 </td>
   <td style="text-align:left;"> $TSLA stonksla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:17:34 </td>
   <td style="text-align:left;"> $TSLA there is still a gap in the 200s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:17:22 </td>
   <td style="text-align:left;"> $TSLA everyone that played weekly overnight screwed this is going sideways for the week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:17:21 </td>
   <td style="text-align:left;"> $TSLA it’s extremely cold and windy on mars maybe tesla could do better there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:17:20 </td>
   <td style="text-align:left;"> $TSLA going to $550-$600 by summer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:17:18 </td>
   <td style="text-align:left;"> $TSLA $NVDA  I am so confused why do people attack someone that is on the other side of your opinion about a stock price. I am bearish on tsla at the moment probably b a bull in a week. People calling me names trolling me if I am wrong I will shack you hand and say congrats. This is the problem with society it takes two sides to make a market but can we all b professionals. After tsla earning saw the most obnoxious post on both sides. Been doing this since 2013 post show so much anger. I am comfortable with being wrong fortunately for me more right then wrong. Respect stop the anger. Nobody is right all the time. 2022 learn some compassion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:17:10 </td>
   <td style="text-align:left;"> $TSLA just gap up to $8,000 and get it over with </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:17:08 </td>
   <td style="text-align:left;"> $TSLA the day after the last two ERs we saw the call buying program go in overdrive mode. I would say there is a decent chance this happens again tomorrow. The stock is exactly unchanged right now AH. They need to restart the momo engine. Watch the 940C 950C 960C calls tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:16:53 </td>
   <td style="text-align:left;"> $TSLA rinse and repeat anyone. 💥💥💰💰💰 under 850 again for another round. 💥💥good LT AS WELL this ain’t going anywhere if you got the ⌚️&amp;amp;💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:16:35 </td>
   <td style="text-align:left;"> $TSLA Start trading over 4 month ago and I lost all of money, Now I have made over $147K+ profits after join their chat room and using their alerts..,, Highly recommended,.!  🚀 discord.io/stock-wining-chat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:16:18 </td>
   <td style="text-align:left;"> $TSLA where’s my $1,000 bulls at???? 🤦🏼‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:16:05 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:15:35 </td>
   <td style="text-align:left;"> $TSLA guess we got IV crushed again 🤕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:15:34 </td>
   <td style="text-align:left;"> $TSLA  are they making cars with structural battery already in Austin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:15:28 </td>
   <td style="text-align:left;"> $TSLA probably the flattest earnings I&amp;#39;ve ever seen lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:15:11 </td>
   <td style="text-align:left;"> $TSLA  
 
Sell Tesla and buy Ford. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:15:11 </td>
   <td style="text-align:left;"> $TSLA I’m not in this but GLTA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:15:04 </td>
   <td style="text-align:left;"> $TSLA premium wrecked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:15:03 </td>
   <td style="text-align:left;"> $DWAC $GME $AMC $TSLA $TWTR Trump 47th! https://www.youtube.com/watch?v=9e8CMcDRboE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:14:55 </td>
   <td style="text-align:left;"> $TSLA did they give guidance?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:14:46 </td>
   <td style="text-align:left;"> $NIO $TSLA 
Wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:14:41 </td>
   <td style="text-align:left;"> $TSLA News is nice. But has to break and retest $963.5-$964ish. Watching. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:14:34 </td>
   <td style="text-align:left;"> That $TSLA earnings call was the most pathetic thing I&amp;#39;ve ever heard. It&amp;#39;s over for the stock being anywhere near $1,000. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:14:28 </td>
   <td style="text-align:left;"> $TSLA Dude where&amp;#39;s my Solar Roof, Interlink, Cyber Trick I mean Truck? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:14:20 </td>
   <td style="text-align:left;"> $TSLA 

$MS The cash machine #Tesla 

2.7B !! With just 2 factories and 2 Models - Incredible 

🙏🏻🐉🦅👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:14:14 </td>
   <td style="text-align:left;"> $TSLA A lot of y’all have never gone through an actual recession and it shows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:14:13 </td>
   <td style="text-align:left;"> $TSLA here comes the FUD with &amp;quot;Loom&amp;quot; guidance. Show me any other company that grows margins like Tesla does. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:14:11 </td>
   <td style="text-align:left;"> $TSLA Options writers banking heavily tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:14:09 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:14:03 </td>
   <td style="text-align:left;"> $TSLA “Tesla unveils fleet of new ‘Tesla Semi’ electric trucks”

 By Fred Lambert. 

https://electrek.co/2022/01/26/tesla-semi-fleet-electric-trucks-unveiled/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:13:58 </td>
   <td style="text-align:left;"> $TSLA Morgan Stanley analyst Adam Jonas has released a new $TSLA note: An EV &amp;quot;Cash Machine&amp;quot; (And This With Just 2 Cars and 2 Plants).

“How many 50% multi-year top line growers on your screen actually generate cash?”

Source: Sawyer Merritt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:13:56 </td>
   <td style="text-align:left;"> $TSLA Gonna have a good pop up tomorrow 💥💥💥💥💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:13:50 </td>
   <td style="text-align:left;"> latex236982d076e18944da44e4a9feffc82earkk), then Fintech, next is EV’s.  One of the few sectors where the leaders still sport insane multiples ($tsla $rivn $lcid). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:13:39 </td>
   <td style="text-align:left;"> $TSLA We are Tesla Apes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:13:12 </td>
   <td style="text-align:left;"> $TSLA all that drama for a flat AH lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:13:06 </td>
   <td style="text-align:left;"> $TSLA if can’t get through todays high I would be careful going long in the short run. Watch NQ’s too and see if go green to red like today. Gotta hold 14000 level. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:13:05 </td>
   <td style="text-align:left;"> $TSLA pusssshin puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:12:41 </td>
   <td style="text-align:left;"> $TSLA I never root for people to lose money but to all the greedy degenerates who did earnings options plays….I hope IV crush fucks you with no lube </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:12:34 </td>
   <td style="text-align:left;"> $TSLA I decided to go long, even though I was scalping long shares the last several days, I think a good trade is to $1030. But I still think at some point it will see it’s 200 day and that could go below $800. However earnings were good and entire market needs a big bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:12:12 </td>
   <td style="text-align:left;"> $SPY played $TSLA earnings for the first time 🤷🏼‍♂️ picked up 1,000 calls and  900$ puts..... and this POS traded flat after earnings lol I&amp;#39;m a bear 🐻  but now I&amp;#39;m hoping for a total financial crisis 😅 since the market maker going to kill my premium tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:12:11 </td>
   <td style="text-align:left;"> $TSLA is the new thing to kill options both ways after earning? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:11:57 </td>
   <td style="text-align:left;"> $TSLA how come it is not moving up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:11:43 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMC Aww shit Powell is loaded in puts. The man is clearly pushin Ps. Will  $TSLA be the opening salvo in a bear market?? https://youtu.be/9g08kucPQtE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:11:33 </td>
   <td style="text-align:left;"> $TSLA Bullish - I see this running for the next few weeks. Get in and ride the wave. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:11:05 </td>
   <td style="text-align:left;"> $TSLA this is only ah price movement where majority of people dont participate. Wait until tomorrow on open to see the 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:10:52 </td>
   <td style="text-align:left;"> $TSLA that&amp;#39;s more like it.... red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:10:46 </td>
   <td style="text-align:left;"> $TSLA wait for the market to absorb the interest hike. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:10:28 </td>
   <td style="text-align:left;"> $TSLA 

Bulls are like “it’s not just a car company” anyway lemme justify this price by how many cars they sold.

GTFO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:10:17 </td>
   <td style="text-align:left;"> $TSLA are the rewards even worth shorting elon? Could add 10-20% in a day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:10:00 </td>
   <td style="text-align:left;"> #Tesla&amp;#39;s ( $TSLA ) earnings call was quite amazing! 
 
It was like being a fly-on-the-wall listening to Elon Musk and team brainstorming new ideas then putting in the (blood, sweat, &amp;amp; tears!) work to get the idea to mass production. 
 
WATCH: https://youtu.be/JlOmvWBPTkw?t=1218 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:09:56 </td>
   <td style="text-align:left;"> $TSLA  did I hear them say they are making lots of cars with 4680 right now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:09:54 </td>
   <td style="text-align:left;"> $TSLA.. don’t try to bet against Him… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:09:32 </td>
   <td style="text-align:left;"> $TSLA bulls are annoyed that this did not add another trillion in market cap. smh. pure greed. too many pumpers.  only like 1/10 bulls has actually provided me with a decent argument. all the other moonboys just came up with some hogwash and bs price targets. this is not about bulls vs bears, but on this ticker, bears have provided better arguments. bulls meanwhile provide the most disgusting arguments ever: &amp;quot;Elon is richer than you. stfu. Elon this...Elon that...&amp;quot; Clowns. Branson is also richer than me, and look how he fleeced all the pumpers on the SPCE page. Dumb arguments here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:09:15 </td>
   <td style="text-align:left;"> $TSLA elon was correct about PayPal.. he was correct again about electric cars .. if he looking at robotics I wouldn&amp;#39;t bet against him at this point.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:09:15 </td>
   <td style="text-align:left;"> $TSLA sideway tmr. Both call &amp;amp; put lose </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:59 </td>
   <td style="text-align:left;"> $TSLA going to Ford </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:58 </td>
   <td style="text-align:left;"> $TSLA market is about to teach these young Tesla Fanboys a life lesson. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:57 </td>
   <td style="text-align:left;"> $TSLA . Bears are holding bag forever.

They are waiting to buy at $600…

Never going to happen that 

Bullshit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:49 </td>
   <td style="text-align:left;"> $TSLA  Model Y is the company.  Everything else is &amp;quot;other bets&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:34 </td>
   <td style="text-align:left;"> $TSLA  and suker of the year award goes to all option buyers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:32 </td>
   <td style="text-align:left;"> $TSLA as soon as people realize tesla is more than a car company…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:27 </td>
   <td style="text-align:left;"> $TSLA time to short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:18 </td>
   <td style="text-align:left;"> $TSLA This old Geaser is out of gas!. Guys look into The Pre-IPO market.
There is one called Addepar, They just signed a huge contract. RBC Wealth management.  RBC will be using Addepar’s platform in their largest full integration ever! Watch the video below i also placed a link for Pre-IPO access.   This one looks promising.  

Pre-IPO access
https://investors.be4ipo.net/get-access2/

Video
https://youtu.be/fWOvNJC1chA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:15 </td>
   <td style="text-align:left;"> $TSLA THESE MM’s JUST WANTED TO BURN THETA TO STEAL MONEY!! IV CRUSHED. DO NOT PASS GO…DONT COLLECT $200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:15 </td>
   <td style="text-align:left;"> $TSLA me holding March puts this evening👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:04 </td>
   <td style="text-align:left;"> $TSLA no amount of kool aid can sustain this valuation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:08:04 </td>
   <td style="text-align:left;"> $TSLA Listen UP! $TKLF ipo’d last week and was bludgeoned to death. Shorts and institutes dumped and shorted after the iPo went from $4 to $43. Borrow rate 67%, float 6 million, short percentage around 50%. THIS IS A JAPANESE COMPANY AND IS PROFITABLE! REVENUE IS DOUBLE THEIR MARKET CAP! Let’s squeeze the shorts together! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:07:43 </td>
   <td style="text-align:left;"> $TSLA hype is over. Lots of better value for cheaper EV’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:07:37 </td>
   <td style="text-align:left;"> $TSLA no more intresting catylyst a for some time unless wallstreet big players btd, who&amp;#39;s ready for a volitle 3 months? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:07:28 </td>
   <td style="text-align:left;"> $TSLA you must not have seen the Tesla&amp;#39;s being delivered by the hundreds on semis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:07:09 </td>
   <td style="text-align:left;"> $TSLA tomorrow 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:06:40 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s see that beautiful 850 open and close the day at 680. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:06:38 </td>
   <td style="text-align:left;"> $TSLA Tesla is bringing up all these other stocks that don’t make any money. Really. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:06:38 </td>
   <td style="text-align:left;"> $TSLA wish there was more innovation and talk on the electric cars you know the one that makes them almost all there revenue. Instead it was about his robots and Taxi’s. No new cars, no cyber truck, no 25k car. You could tell he is focused on the robots and taxi’s he tried to convince people that’s what we should focus on as it seems the car biz is not really what matters anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:06:32 </td>
   <td style="text-align:left;"> $TSLA show ain’t over. 800 eod tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:06:30 </td>
   <td style="text-align:left;"> $TSLA flat as a pancake, unbelievable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:06:30 </td>
   <td style="text-align:left;"> $TSLA where’s the pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-27 08:06:14 </td>
   <td style="text-align:left;"> $TSLA surprise. It’s green. </td>
  </tr>
</tbody>
</table></div>

---
