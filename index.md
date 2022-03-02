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

[View the latest Economic Forecasts](/pdf/Monthly-Market-Outlook--Mar-2022-.pdf)

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



Last Updated: 2022-03-02 11:02:14 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gsci </td>
   <td style="text-align:left;"> 2022-03-02 11:00:39 </td>
   <td style="text-align:left;"> S&amp;P GSCI Hits 7-year High </td>
   <td style="text-align:left;"> S&amp;P GSCI increased to a 7-year high of 3558 Index Points </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/nickel </td>
   <td style="text-align:left;"> 2022-03-02 11:00:34 </td>
   <td style="text-align:left;"> Nickel Hits Near 11-year High </td>
   <td style="text-align:left;"> Nickel increased to a near 11-year high of 25557 USD/T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.marketwatch.com/story/biden-to-use-state-of-the-union-to-renew-push-for-15-minimum-wage-11646188913 </td>
   <td style="text-align:left;"> 2022-03-02 10:41:00 </td>
   <td style="text-align:left;"> Biden uses State of the Union to renew push for $15-an-hour minimum wage - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden on Tuesday night used his first State of the Union address to renew a push to increase the federal minimum wage, a proposal Democrats tried but failed to enact last year.                                                                                                                                                                                                       , “Raise the minimum wage to $15 an hour,” Biden said before an audience of lawmakers.                                                                                                                                                                                                                                                                                                                 , Biden last March signed the $1.9 trillion COVID relief bill, also called the American Rescue Plan — but the minimum wage-hike had been previously ruled out of the measure by an official known as the Senate parliamentarian. While popular with many Democrats, the parliamentarian said the wage increase didn’t pass muster for the budget process that Biden’s party used to advance the bill.  , Polling has shown that about 60% of adults say they favor raising the minimum wage to $15 an hour from the current rate of $7.25. The president’s plea comes as his party is facing an uphill battle to retain control of the House of Representatives, and perhaps the Senate, in next fall’s midterm election.                                                                                     , While the issue may be politically popular, getting a $15 minimum wage through the closely divided Senate could be a tall order. Two Senate Democrats, Joe Manchin of West Virginia and Kyrsten Sinema of Arizona, last year rejected putting the increase in Biden’s COVID package. But lawmakers have floated other ideas — such as raising it to $11 or $12 an hour instead.                      , Also read: $15 minimum wage won’t make it into Biden’s $1.9-trillion COVID-19 relief bill — lawmakers have other ideas                                                                                                                                                                                                                                                                               , The much-anticipated address will be carried across a wide array of broadcast and cable networks, plus on the White House website.                                                                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                                                      , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60557077?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-02 10:37:43 </td>
   <td style="text-align:left;"> Ukraine conflict: Oil hits $110 a barrel despite emergency measures </td>
   <td style="text-align:left;"> Oil prices have surged despite new measures aimed at calming markets worried by the invasion of Ukraine.                                                                                                                          , Brent crude - the international benchmark for oil prices - has hit $110 a barrel, marking the highest level seen in more than seven years.                                                                                        , It rose after the International Energy Agency's members agreed to release 60 million barrels of oil from emergency stockpiles.                                                                                                    , Russia is one of the biggest energy producers in the world.                                                                                                                                                                       , As a result, concerns about Russia's invasion of Ukraine have sparked concerns among investors that oil or gas supplies could be affected.                                                                                        , Meanwhile, the price of US oil - West Texas Intermediate crude - rose to almost $109 a barrel.                                                                                                                                    , The United States and 30 other member countries of the International Energy Agency (IEA) agreed to release the oil in a bid to stabilize energy markets worldwide.                                                                , "We are prepared to use every tool available to us to limit disruption to global energy supply as a result of President Vladimir Putin's actions," White House spokeswoman Jen Psaki said on Tuesday.                             , She added that Washington would carry on looking at how to speed up moving energy supplies away from Russia.                                                                                                                      , Another statement by the IEA noted that the invasion of Ukraine came against a "backdrop of already tight global oil markets, heightened price volatility, commercial inventories that are at their lowest level since 2014".     , Petrol price movements in the UK are mainly determined by the price of crude oil, which is the raw material for fuel, and the exchange rate between the dollar and the pound, because oil is traded in dollars.                   , On Monday, the RAC said the average price of petrol had jumped to a record high of £1.51 a litre on Sunday, while diesel increased to £1.55.                                                                                      , Jay Hatfield, chief investment officer at ICAP, said the "dramatic" price increases seen globally were unlikely to persist though if the situation in Ukraine becomes more stable.                                                , Share prices across Europe and the US also fell further on Tuesday as attacks on cities in Ukraine continued.                                                                                                                     , Markets in US, Europe and UK fell amid fears about the impact of the ongoing conflict.                                                                                                                                            , Having been up in early trading, the FTSE 100 turned negative amid the warnings of the consequences of Western sanctions on Moscow and signs that Russia was stepping up its invasion of Ukraine.                                 , Western countries have imposed punishing sanctions against Moscow, with another raft of companies winding down Russian operations and halting investment, such as BP and Shell.                                                   , Italian energy giant Eni also said it planned to sell its stake in the Blue Stream pipeline. Eni co-owns the pipeline, which carries Russian gas to Turkey, with Russian energy firm Gazprom.                                     , Meanwhile, French oil and gas group TotalEnergies said it would no longer provide capital for new projects in Russia on Tuesday.                                                                                                  , Frankfurt saw steeper losses, which analysts suggested could be linked to Germany's reliance on Russian energy imports.                                                                                                           , Russia's currency was stable, however, having collapsed 30% on Monday to record lows against major currencies. One rouble was worth less than one US cent in trading on Tuesday.                                                  , The rouble's fall cuts its buying power and hits savings of ordinary Russians. The decline was only halted when Russia's central bank doubled interest rates to make the currency more attractive to investors.                   , The sanctions' stranglehold on Moscow's finances has hit the central bank's access to a lot of Russia's huge reserves of money held in the form of foreign currencies.                                                            , Sophie Lund-Yates, equity analyst at Hargreaves Lansdown, said: "This is a fast-moving situation and investors should be mindful of potential share price volatility in the short to medium term."                                , Russia's invasion of Ukraine has investors on edge.                                                                                                                                                                               , There is a huge amount of uncertainty about what is likely to happen next, and you can see that in the volatility on markets.                                                                                                     , Western sanctions on Russia have caused turmoil in the global banking sector, with firms scrambling to ensure they're not doing business with any sanctioned individual or company.                                               , European and US asset managers who are keen to offload their Russian investments may find it difficult to do so with the Moscow stock exchange currently closed and talk that the Kremlin will prevent foreigners from selling up., That - together with the lack of revenue from Russian customers - could mean lower profits for western companies, from energy giants to carmakers to investment funds.                                                            , Sanctions can hurt both sides, not just the sanctioned.                                                                                                                                                                           , But many company bosses are clear - decisions are being made, not simply about money, but on moral grounds too.                                                                                                                   , Meanwhile, the war continues to unsettle the energy markets, with the price of oil now well over $100 a barrel.                                                                                                                   , An announcement that large stockpiles of crude will be released would ordinarily send prices lower.                                                                                                                               , Today's news, however, has done nothing to ease market concerns about the potential for shortages of oil from Russia.                                                                                                             , Watch the final series of Killing Eve on BBC iPlayer                                                                                                                                                                              , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                                       , The unlikely Olympian talks to Colin Murray about how fear gives him focus                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-03-02 10:36:00 </td>
   <td style="text-align:left;"> Brent Extends Rally as IEA Warns of Crisis </td>
   <td style="text-align:left;"> Brent crude futures crossed $110 per barrel on Wednesday, extending a 7% rally in the previous session as the IEA warned that global energy security is under threat following Russia’s invasion of Ukraine, while investors await fresh announcements from the OPEC+ meeting later today. IEA executive director Fatih Birol said Tuesday that the current situation in energy markets is “very serious and demands our full attention,” following a decision by its members including the US and Japan to release 60 million barrels of crude from emergency reserves. The move did little to tame soaring oil prices, which scaled fresh 7-year highs as the worsening crisis in Ukraine and broadening sanctions against Russia stoked fears of further supply disruptions. Meanwhile, OPEC+ will meet on Wednesday to discuss output policy, where it is expected to stick to its plan of moderate supply increases despite the market turmoil brought by the invasion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-02 10:32:00 </td>
   <td style="text-align:left;"> Oil Extends Rally as IEA Warns of Crisis </td>
   <td style="text-align:left;"> WTI crude futures surpassed $107 per barrel on Wednesday, extending an 8% rally in the previous session as the IEA warned that global energy security is under threat following Russia’s invasion of Ukraine, while investors await fresh announcements from the OPEC+ meeting later today. IEA executive director Fatih Birol said Tuesday that the current situation in energy markets is “very serious and demands our full attention,”  following a decision by its members including the US and Japan to release 60 million barrels of crude from emergency reserves. The move did little to tame soaring oil prices, which scaled fresh 7-year highs as the worsening crisis in Ukraine and broadening sanctions against Russia stoked fears of further supply disruptions. Meanwhile, OPEC+ will meet on Wednesday to discuss output policy, where it is expected to stick to its plan of moderate supply increases despite the market turmoil brought by the invasion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/canola </td>
   <td style="text-align:left;"> 2022-03-02 10:28:16 </td>
   <td style="text-align:left;"> Canola Hits All-time High </td>
   <td style="text-align:left;"> Canola increased to an all-time high of 1109 CAD/T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-says-us-close-off/story.aspx?guid={602E4320-B2E7-4A2E-9E48-BB26BA74DCE6}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-02 10:18:52 </td>
   <td style="text-align:left;"> Biden says U.S. will close off airspace to all Russian flights - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden said the U.S. government is closing off American air space to all Russian flights -- "further isolating Russia and adding an additional squeeze on their economy." The announcement had been expected following reports earlier Tuesday, and it came as Biden delivered a State of the Union address on Tuesday night., The much-anticipated address will be carried across a wide array of broadcast and cable networks, plus on the White House website.                                                                                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                                           , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-begins-state-union-speech/story.aspx?guid={A947E4AA-824D-4A53-A3F0-EC8A04C681E4}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-02 10:10:07 </td>
   <td style="text-align:left;"> Biden begins State of the Union speech with Russia, inflation in focus  - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden has kicked off his first State of the Union speech, beginning an address that is expected to focus heavily on the Russian invasion of Ukraine and the president's plan to fight inflation. Biden is expected to say that the U.S. will close its airspace to Russian airlines in a bid to further punish Russian President Vladimir Putin. And the president will describe a plan to make more products in the U.S. instead of relying on overseas supply chains. "Economists call it 'increasing the productive capacity of our economy,'" he will say, according to excerpts released by the White House. "I call it building a better America."  

, The much-anticipated address will be carried across a wide array of broadcast and cable networks, plus on the White House website.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/methanol </td>
   <td style="text-align:left;"> 2022-03-02 09:57:46 </td>
   <td style="text-align:left;"> Methanol Hits 18-week High </td>
   <td style="text-align:left;"> Methanol increased to a 18-week high of 2926 CNY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/01/business/boeing-ford-russia.html </td>
   <td style="text-align:left;"> 2022-03-02 09:38:57 </td>
   <td style="text-align:left;"> Boeing and Ford Suspend Operations in Russia - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                     , The U.S. manufacturing companies are the latest to shut down offices and factories since Russia invaded Ukraine.                                                                                                                                                                                                                                                                                                                                  , By Niraj Chokshi and Neal E. Boudette                                                                                                                                                                                                                                                                                                                                                                                                             , Two major U.S. manufacturers, Boeing and Ford Motor, suspended their business activities in Russia as the country escalated its war in Ukraine.                                                                                                                                                                                                                                                                                                   , Boeing said on Tuesday that it had halted major operations in its Moscow office and temporarily closed another office in Kyiv, Ukraine. The company also said that it had ceased providing parts, maintenance and technical support services to Russian airlines. In recent days, countries around the world have imposed sanctions on Russian carriers, limiting their ability to use leased planes; fly over Western Europe; or buy spare parts., Boeing employs several thousand people in Russia, Ukraine and a handful of former Soviet states, an operation that includes a major design center in Moscow. The company also runs a flight training campus and research and technology center in the city and has a joint venture in Russia with VSMPO-AVISMA, Boeing’s largest titanium supplier.                                                                                               , Boeing has also been trying to diversify its titanium supply in recent years and it said it had enough of the metal on hand to keep making commercial aircraft in the near term.                                                                                                                                                                                                                                                                  , Ford, which once had three plants in Russia, is suspending its remaining operations in the country indefinitely because of the invasion. The automaker is part of a joint venture that makes small delivery vans at a plant in Yelabuga, more than 600 miles east of Moscow. It also works with a distributor that sells imported Ford vehicles.                                                                                                  , “Ford is deeply concerned about the invasion of Ukraine and the resultant threats to peace and stability,” the company said in a statement. “The situation has compelled us to reassess our operations in Russia.”                                                                                                                                                                                                                                , Ford shut down its three plants in Russia in 2019 as part of an effort to turn around its struggling European operation.                                                                                                                                                                                                                                                                                                                          , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 09:24:41 </td>
   <td style="text-align:left;"> Japanese Shares Track Wall Street Lower </td>
   <td style="text-align:left;"> The Nikkei 225 Index dropped 1.3% to around 26,500 while the broader Topix Index lost 1.5% to 1,867 on Wednesday, as Japanese shares tracked sharp overnight losses on Wall Street, with investors weighing the economic ramifications of surging oil prices spurred by the ongoing conflict between Russia and Ukraine. US crude futures hit its highest level in seven years as Russia continued its assault on Ukraine, stoking market volatility and clouding the outlook for inflation and monetary policy. Japanese technology stocks led the declines, with losses from Lasertec (-1.6%), Tokyo Electron (-1.2%), Keyence (-1.8%), Monex Group (-5.8%) and Fronteo (-3.6%). Consumer-related, manufacturing and financial  firms also slumped. Meanwhile, resource-related stocks gained on stronger commodity prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 08:57:27 </td>
   <td style="text-align:left;"> Australia Shares Wobble as Bank Stocks Weigh </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index wobbled around the previous session’s close of 7,097 on Wednesday, as losses in financial firms offset gains in commodity-linked stocks, while investor sentiment remained weak amid the ongoing conflict between Russia and Ukraine. Energy prices surged overnight as Russia continued its assault on Ukraine, stoking market volatility and clouding the outlook for inflation and monetary policy. Australian banks slumped as global yields fell, with losses from ANZ Bank (-1.5%), National Australia Bank (-1%) and Westpac Banking (-1.3%). Meanwhile, energy stocks jumped on higher oil and coal prices, with gains from Woodside Petroleum (3.5%), Santos Ltd (3%) and Whitehaven Coal (3%). Australian miners also advanced on stronger metal prices including BHP Group (3%), Fortescue Metals (3.9%) and Newcrest Mining (1.9%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-60579641?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-02 08:53:38 </td>
   <td style="text-align:left;"> Apple to halt sales and limit services in Russia </td>
   <td style="text-align:left;"> Apple has become the latest major firm to halt all product sales in Russia, in a widening corporate backlash to the country's invasion of Ukraine.                                                                                                , The iPhone giant said it was "deeply concerned" about the Russian invasion and stands with those "suffering as a result of the violence".                                                                                                         , Apple Pay and other services such as Apple Maps have also been limited.                                                                                                                                                                           , Google has also removed Russian state-funded publishers such as RT from its features.                                                                                                                                                             , Mobile banking apps in Russian, such as Russia's VTB Bank's app, may soon not function fully on devices using Apple's iOS operating system, according to news agency RIA.                                                                         , Apple said in a statement that the firm had disabled both traffic and live incidents in Apple Maps in Ukraine as a "safety and precautionary measure for Ukrainian citizens".                                                                     , Last week, Ukrainian Vice Prime Minister Mykhailo Fedorov published an open letter to Apple on Twitter, in which he asked Apple to cut Russia off from its products, services, and App Store.                                                     , Earlier, Google restricted news firms funded by the Russian government from advertising tools and some features on YouTube.                                                                                                                       , "We are committed to complying with all sanctions requirements and we continue to monitor the latest guidance," the company wrote in a blog post.                                                                                                 , The company also told the BBC that Google Pay had been limited in the country - for those using sanctioned banks. Google has not, however, blocked Google Pay in Russia.                                                                          , Google also said "most of our services (like Search, Maps and YouTube) currently remain available in Russia, continuing to provide access to global information and perspectives."                                                                , Apple is generally fairly good at keeping its head down when it comes to global affairs.                                                                                                                                                          , For example, it has faced criticism for not standing up to China over its treatment of Uyghurs.                                                                                                                                                   , This move then is significant, and unusual, by the iPhone maker.                                                                                                                                                                                  , One by one global brands have been moving to distance themselves from Russia - making the country look more and more isolated.                                                                                                                    , But it was by no means certain that Apple would make this move. The company had started to receive criticism for its relative silence on Ukraine.                                                                                                 , The BBC had reached out to Apple for comment, but had not received a reply until this announcement.                                                                                                                                               , There are many phone companies in Russia, and plenty of alternatives to Apple products.                                                                                                                                                           , People with iPhones will also still be able to use the App Store - the pause in sales will not have a huge immediate impact.                                                                                                                      , But as brands desert Russia, its citizens will begin to notice that products they used to buy, simply aren't available anymore.                                                                                                                   , Meanwhile, the Finnish network equipment maker Nokia said it would stop deliveries to Russia to comply with sanctions imposed on the country following the invasion of Ukraine.                                                                   , On Monday, Netflix also said it had "no plans" to add state-run channels to its Russian service. Russian regulations had required it to carry 20 free-to-air news, sports and entertainment channels in the country.                              , US sportswear giant Nike has also paused sales in Russia. An update to the company's website showed that purchases online and on the app were unavailable in Russia because the firm said it could not guarantee delivery of goods to the country., The biggest shipping firms in the world, Danish Maersk and Geneva-based MSC, also suspended container shipping to and from the country on Tuesday. The UK has also banned ships from Russia in its updated sanctions.                             , Russia supplies a sixth of the world's commodities so will now be cut off from a significant part of shipping trade.                                                                                                                              , Motorbike firm Harley-Davidson also suspended business and shipments of its bikes to Russia.                                                                                                                                                      , And US plane manufacturer Boeing Co said on Tuesday it was suspending parts, maintenance and technical support for Russian airlines -  as well as major operations in Moscow after Russia's invasion of Ukraine.                                  , Watch the final series of Killing Eve on BBC iPlayer                                                                                                                                                                                              , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                                                       , The unlikely Olympian talks to Colin Murray about how fear gives him focus                                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-03-02 08:48:00 </td>
   <td style="text-align:left;"> South Korea Factory Growth at 8-Month High </td>
   <td style="text-align:left;"> The IHS Markit South Korea Manufacturing PMI rose to an 8-month high of 52.8 in February 2022 from 52.8 in January, marking the 17th straight month of growth in factory activity. Output expanded at the fastest pace in 7 months boosted by car production and semiconductors. Also, new orders rose the most since last June, and export growth was at a 10-month high with demand from the US, Europe, and China strengthening. Buying levels were up for the 19th month running, reflecting efforts to protect against supplier delays and further price rises. Employment rose for the 3rd straight month, growing the most in 11 months; while backlogs of work gained further. On prices, input cost inflation accelerated for the first time in three months while rising for the 20th straight month. Factory gate inflation, meantime, hit its highest since the survey began. Finally, sentiment was at a 12-month high, boosted by hopes that the end of the pandemic would trigger a recovery in the global economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/u-s-expected-ban-russian-aircraft-american-airspace-report </td>
   <td style="text-align:left;"> 2022-03-02 08:46:03 </td>
   <td style="text-align:left;"> Biden announces ban on Russian aircraft from American airspace in State of the Union </td>
   <td style="text-align:left;"> Hermitage Capital Management CEO discusses if Russia is about to plunge into a financial crisis.                                                                                                                     , President Biden announced a ban on all Russian aircraft from American airspace during the State of the Union on Tuesday evening.                                                                                     , "We will join our allies in closing off American airspace to all Russian flights, further isolating Russia and adding an additional squeeze on their economy," Biden said to applause from the assembled lawmakers.  , The move comes after Europe and Canada closed their airspace to Russian airlines over the weekend as part of widening sanctions imposed on the country after its invasion of Ukraine.                                , European Commission President Ursula von der Leyen said the European Union is banning all Russian airlines as well as "the private jets of oligarchs."                                                               , "There is no room in Dutch airspace for a regime that applies unnecessary and brutal violence," Mark Harbers, the Minister of Infrastructure for the Netherlands, tweeted Saturday.                                  , An Aeroflot - Russian Airlines Airbus A320 aircraft as seen on final approach landing on the runway at Amsterdam Schiphol Airport from Moscow.  (Photo by Nicolas Economou/NurPhoto via Getty Images)                , Canadian Minister of Transport Omar Alghabra said Saturday that the ban was put into place to "hold Russia accountable for its unprovoked attacks against Ukraine."                                                  , RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                 , The White House said Monday that it was still making a decision about a ban on Russian aircraft.                                                                                                                     , "There are a lot of flights that U.S. airlines fly over Russia to go to Asia and other parts of the world and we factor in a range of factors," White House Press Secretary Jen Psaki said Monday.                   , Aeroflot Russian Airlines Airbus A320 civil jet aircrafts at Moscow-Sheremetyevo International Airport.  (Photo by Leonid Faerberg/SOPA Images/LightRocket via Getty Images)                                         , In response to the sanctions, Russia announced that it was banning aircraft from 36 countries, including all of the European Union, from entering their airspace.                                                    , American Airlines, Delta Airlines, United Airlines, and others had already announced that they were temporarily suspended flights into Russian airspace.                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                          , Delta also said it was ending its codesharing service with the Russian airline Aeroflot, which allowed customers to book flights on both airlines.                                                                   , The ban on Russian aircraft adds to a growing list of crippling sanctions that threaten to economically isolate Russia.                                                                                              , The Associated Press contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/gdp-growth </td>
   <td style="text-align:left;"> 2022-03-02 08:44:00 </td>
   <td style="text-align:left;"> Australia Q4 GDP Growth Rate Beats Estimates </td>
   <td style="text-align:left;"> The Australian economy expanded 3.4% qoq in Q4, exceeding market forecasts of 3.0% and shifting from a 1.9% fall in Q3. This was the strongest pace of growth since Q3 2020, boosted by a sharp rebound in household spending as the economy emerged from COVID-19 lockdowns. Household consumption bounced back strongly, rising the most in 5 quarters (6.3% vs -4.8% in Q3), buoyed by spending on both goods and services with recreation and culture, cafes and restaurants and clothing experiencing strong rises. At the same time, government spending growth eased sharply (0.1% vs 3.8%); while private investment fell for 1st time in 6 quarters (-1.4% vs 0.7%), amid shortages of labor and construction materials. Also, net external demand contributed negatively, with exports falling 1.5%, due to mining commodities and travel services; while imports dropped 0.9%, driven by consumption and capital goods. On a yearly basis, the economy grew 4.2%, after a 3.9% rise in Q3 and above consensus of 3.7%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 08:07:00 </td>
   <td style="text-align:left;"> US Futures Inch Up Amid Oil Price Spike </td>
   <td style="text-align:left;"> US stock futures inched higher in Asian trade on Wednesday after Wall Street tumbled overnight, as investors weighed the economic ramifications of surging oil prices spurred by the ongoing conflict between Russia and Ukraine. Futures tied to the three major indexes each gained about 0.2%. In regular trading on Tuesday, the Dow fell 1.76%, while the S&amp;P 500 and Nasdaq Composite dropped 1.55% and 1.59%, respectively. Bank stocks took a hit amid a sharp decline in Treasury yields, while energy stocks advanced. Oil prices pushed higher overnight as Russia continued its assault on Ukraine, with WTI crude futures hitting its highest level in seven years, clouding the outlook for inflation and monetary policy. Meanwhile, investors look ahead to employment data from ADP due out Wednesday, as well as to Fed chair Powell’s appearance in Congress to give his semiannual monetary policy update. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/construction-output </td>
   <td style="text-align:left;"> 2022-03-02 07:44:36 </td>
   <td style="text-align:left;"> South Korea Construction Output Rises Further in January </td>
   <td style="text-align:left;"> Construction output in South Korea rose 6.8 percent year-on-year in January of 2022, following a revised 0.5 percent gain in the previous month. Output increased for a second straight month as both civil engineering (1.0 percent vs -9.1 percent in December) and building activity (8.8 percent vs 5.6 percent) expanded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-03-02 07:20:00 </td>
   <td style="text-align:left;"> South Korea Retail Sales Grows For the 12th Consecutive Month </td>
   <td style="text-align:left;"> Retail sales in South Korea increased 4.5 percent year-on-year in January of 2022, accelerating from a revised 6.8 percent rise in the prior month, and marking the twelfth straight month of gains in retail trade. On a monthly basis, retail sales plunged 1.9 percent, after increasing 2.2 percent in the previous period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/industrial-production </td>
   <td style="text-align:left;"> 2022-03-02 07:16:00 </td>
   <td style="text-align:left;"> South Korea Industrial Production Loses Steam </td>
   <td style="text-align:left;"> Industrial production in South Korea grew 4.3 percent year-on-year in January of 2022, after an upwardly revised 7.4 percent advance in the previous month and compared with market expectations of a 6.5 percent increase. On a monthly basis, industrial output expanded 0.2 percent following a revised 3.7 percent gain in December, compared to market expectations of a 0.6 percent decrease. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/01/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-03-02 07:07:17 </td>
   <td style="text-align:left;"> Stock futures rise amid surge in oil prices, ongoing conflict in Ukraine </td>
   <td style="text-align:left;"> , Stock futures inched higher on Tuesday night as oil prices surged amid the ongoing conflict between Russia and Ukraine.                                                                                                                                                                                      , Futures tied to the Dow Jones Industrial Average rose 109 points, or 3%. S&amp;P 500 and Nasdaq 100 futures also added 0.3%.                                                                                                                                                                                     , Earnings boosted several stocks in extended trading. Nordstrom spiked by more than 35% on strong earnings while SoFi surged about 20%.                                                                                                                                                                       , In regular trading, the Dow fell 597 points, or 1.76%. The S&amp;P 500 lost 1.55% and the Nasdaq Composite slid 1.59%.                                                                                                                                                                                           , Energy prices pushed higher Tuesday as Russia continued its assault on Ukraine. West Texas Intermediate crude futures broke above $107 per barrel Tuesday evening, after hitting its highest level in seven years earlier in the day.                                                                        , "This dramatic dislocation is due to a flight to safety where U.S. production is viewed as more reliable than other global sources," Jay Hatfield, founder and CEO of Infrastructure Capital Advisors, said of the spike in WTI. "However, it is unlikely to persist after the Ukraine situation stabilizes.", Goldman says stock pickers are buying the dip in growth stocks. Here are their favorites                                                                                                                                                                                                                     , Defense stocks may see long-term lift as Russia's actions spur big jump in spending by U.S. allies                                                                                                                                                                                                           , These stocks have direct exposure to Russia, says Bank of America                                                                                                                                                                                                                                            , Investors are keeping a close eye on oil prices, which could drive inflation, choke the economy and create challenges for the Federal Reserve when shaping policy.                                                                                                                                           , Energy stocks were a bright spot in the market Tuesday, while bank stocks took a hit, dragged down by a sharp decline in Treasury yields, representing a rush into safe-haven bonds amid the stock market turmoil.                                                                                           , The benchmark 10-year note dropped below 1.7% at several points during Tuesday's session.                                                                                                                                                                                                                    , Fed Chair Jerome Powell will testify before Congress on Wednesday to give his semiannual monetary policy update. With fears over the Russian invasion of Ukraine causing turmoil in the financial world, Wall Street has quietly dialed down its expectations for Fed action.                                , Powell is now tasked with telling Congress this week that the central bank will be doing more to control inflation at a time when markets expect it will be doing less.                                                                                                                                      , Goldman says stock pickers are buying the dip in growth stocks. Here are their favorites                                                                                                                                                                                                                     , Defense stocks may see long-term lift as Russia's actions spur big jump in spending by U.S. allies                                                                                                                                                                                                           , These stocks have direct exposure to Russia, says Bank of America                                                                                                                                                                                                                                            , Investors are also looking forward to employment data from ADP due out Wednesday, as well as mortgage application numbers.                                                                                                                                                                                   , President Joe Biden will deliver his first State of the Union address on Tuesday evening. Investors may be listening for updates on his economic agenda, though the global response to the conflict in Ukraine is likely to dominate instead.                                                                , Earnings season continues with several tech companies set to report on Wednesday. Okta, Pure Storage and C3 AI will report after the market closes. ChargePoint is also scheduled to report after the bell.                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                       , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                       , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                             , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                             , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                           , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/building-permits </td>
   <td style="text-align:left;"> 2022-03-02 06:32:56 </td>
   <td style="text-align:left;"> New Zealand Building Consents Falls in January </td>
   <td style="text-align:left;"> The number of building consents issued for new dwellings in New Zealand dropped 9.2 percent month-over-month to a seasonally adjusted 3,810 in January of 2022, losing steam from a revised 0.4 percent increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-call-putin-wrong-tout/story.aspx?guid={808E5AAB-9ACE-416E-8C20-D4792C15D63F}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-02 06:30:39 </td>
   <td style="text-align:left;"> Biden to call Putin 'wrong' and tout his inflation-fighting plans in State of the Union - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden on Tuesday night will slam Russian President Vladimir Putin over his invasion of Ukraine and lay out plans to fight inflation during his State of the Union address, according to excerpts released by the White House. "Putin's war was premeditated and unprovoked," Biden will say, according to his prepared remarks. "He rejected efforts at diplomacy. He thought the West and NATO wouldn't respond. And, he thought he could divide us here at home. Putin was wrong. We were ready," Biden will say. On inflation, the president will say: "We have a choice. One way to fight inflation is to drive down wages and make Americans poorer. I have a better plan to fight inflation. Lower your costs, not your wages. Make more cars and semiconductors in America," among other steps. Biden's speech is scheduled to begin at 9 p.m. Eastern Tuesday.  
, Ukrainian president makes appeal to European Parliament.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/01/politics/sotu-biden-2022/index.html </td>
   <td style="text-align:left;"> 2022-03-02 06:30:15 </td>
   <td style="text-align:left;"> Biden uses State of the Union to send a warning to Putin and pitch his stalled domestic agenda  - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)President Joe Biden warned Russian President Vladimir Putin and his inner circle of oligarchs that harsh punishments are still coming in response to Russia's invasion of Ukraine. But the President also used his first State of the Union address to renew his pitch for a domestic agenda recently overshadowed by that international crisis.                                                                                                                                                                                                                                                                                  , Speaking to political leaders in Washington, Biden started his State of the Union address by sending a resounding message to the world: The West is united in its response to Russia's invasion of Ukraine and condemns the Russian leader for his aggression. Near the beginning of the speech, Biden encouraged all in the chamber to show that support with a resounding standing ovation and said the US and its allies have "an unwavering resolve that freedom will always triumph over tyranny."                                                                                                                                 , Biden noted that Putin's aggression had only made the world's democracies strengthen their resolve to counter rising autocracies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , "Six days ago, Russia's Vladimir Putin sought to shake the foundations of the free world, thinking he could make it bend to his menacing ways. But he badly miscalculated," Biden said. "He thought he could roll into Ukraine and the world would roll over. Instead he met a wall of strength he never imagined. He met the Ukrainian people."                                                                                                                                                                                                                                                                                        , He added, "Let each of us here tonight in this chamber send an unmistakable signal to Ukraine and to the world. Please rise if you are able and show that, yes, we the United States of America stand with the Ukrainian people."                                                                                                                                                                                                                                                                                                                                                                                                       , The President also touted the West's unanimity in the face of Russia's aggression, saying their united front is "inflicting pain on Russia and supporting the people of Ukraine" and "choking off Russia's access to technology that will sap its economic strength and weaken its military for years to come."                                                                                                                                                                                                                                                                                                                         , "Putin's latest attack on Ukraine was premeditated and unprovoked. He rejected  repeated, repeated, efforts at diplomacy. He thought the West and NATO wouldn't respond. He thought he could divide us at home, in this chamber and in this nation. Putin was wrong. We were ready," Biden said.                                                                                                                                                                                                                                                                                                                                        , "We spent months building a coalition of other freedom-loving nations from Europe and the Americas to Asia and Africa to confront Putin. I spent countless hours unifying our European allies. We shared with the world in advance what we knew Putin was planning and precisely how he would try to falsely justify his aggression. We countered Russia's lies with truth. And now that he has acted the free world is holding him accountable."                                                                                                                                                                                       , The President celebrated the impact actions will have on "Russian oligarchs and corrupt leaders who have bilked billions of dollars off this violent regime no more."                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , "We are joining with our European allies to find and seize your yachts, your luxury apartments, your private jets. We are coming for your ill-begotten gains," he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , He also asserted that "Russia's economy is reeling and Putin alone is to blame."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Putin, for his part, was not expected to watch the speech, according to Kremlin spokesperson Dmitry Peskov. "The President usually does not watch TV addresses," Peskov said in response to a question from CNN.                                                                                                                                                                                                                                                                                                                                                                                                                        , As Tuesday unfolded, the President, his administration and its allies have made it clear that Ukraine has been top of mind.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The US and its allies announced early Tuesday that they have agreed to a release of 60 million barrels from their reserves, the White House and International Energy Agency, as leaders seek to dampen the effect of Russia's invasion of Ukraine on gas prices at home. Vice President Kamala Harris held five separate calls with European leaders and Biden held a half-hour call with Ukrainian President Volodymyr Zelensky.                                                                                                                                                                                                       , Biden acknowledged that many Americans are worried about how gas prices are being affected by the war.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , "I know the news about what's happening can seem alarming. But I want you to know that we are going to be OK," he said. "When the history of this era is written Putin's war on Ukraine will have left Russia weaker and the rest of the world stronger."                                                                                                                                                                                                                                                                                                                                                                               , A return to domestic concerns                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The speech has evolved in recent days as a result of invasion of Ukraine. The annual speech also marked an opportunity for Biden to speak directly to the American people about his vision to build a better country, demonstrating how he'll lead America out of the Covid-19 pandemic, into an economic recovery and through the ramifications of a war between Ukraine and Russia. A source tells CNN Commerce Secretary Gina Raimondo is the designated survivor for Tuesday's address, meaning she's the member of the Cabinet assigned to remain outside the House chamber during the State of the Union in case disaster strikes., Despite the initial focus on the war in Ukraine, Biden pivoted for much of the rest of the speech to a more traditional State of the Union address -- pitching his domestic agenda for the upcoming year and renewing his call for economic fairness for all Americans.                                                                                                                                                                                                                                                                                                                                                                 , Biden laid out a plan to fight inflation, saying in excerpts released by the White House ahead of time that the nation has "a choice. One way to fight inflation is to drive down wages and make Americans poorer. I have a better plan to fight inflation."                                                                                                                                                                                                                                                                                                                                                                            , "Lower your costs, not your wages. Make more cars and semiconductors in America. More infrastructure and innovation in America. More goods moving faster and cheaper in America. More jobs where you can earn a good living in America. And, instead of relying on foreign supply chains -- let's make it in America," Biden will say, according to the excerpts. "Economists call it 'increasing the productive capacity of our economy.' I call it building a better America. My plan to fight inflation will lower your costs and lower the deficit."                                                                                , Biden announced new efforts to combat identity theft and criminal fraud in pandemic relief programs, including the appointment of a Justice Department prosecutor tasked with identifying and prosecuting pandemic fraud. He'll also announce higher penalties and more resources to prosecute fraud in the Paycheck Protection Program (PPP) and Unemployment Insurance (UI). Biden, the White House says, will sign an executive order in the coming weeks tasking federal agencies to address fraud and theft in their respective purviews.                                                                                          , The President also called on Congress to send him legislation combating climate change, arguing that some of the tax credits he has petitioned for would lower costs for families.                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Biden is also expected to highlight efforts his administration has taken to reduce gun violence, reiterate his call on Congress to pass "common-sense gun violence legislation that will save lives," and urge Congress to pass his proposed budget, which includes hundreds of millions in funding for community violence intervention programs and community policing, according to a White House official.                                                                                                                                                                                                                           , As is tradition, first lady Jill Biden has invited guests that represent policies and themes the President will talk about during the speech, her office said. This year's invitations included Ukraine Ambassador to the US Oksana Markarova, along with educators, a union representative, members of the tech community, an organizer of Native American causes, a health care worker and a military spouse have also been invited to sit with the first lady in her box above the dais.                                                                                                                                             , Biden's primetime speech about the state of the nation and where the country is headed comes after a sharp decline in the President's' approval rating since he last spoke in front of the joint session of Congress last year. With all eyes on Biden Tuesday night, the White House has made clear that they're keenly aware of the pressure on him to deliver a successful message -- especially as Democrats head into the 2022 midterm elections.                                                                                                                                                                                  , Polling shows Americans don't trust Biden when it comes to Russia's invasion of Ukraine. Biden also has one of the worst approval ratings going into his first inaugural address of any American president in the polling era.                                                                                                                                                                                                                                                                                                                                                                                                          , Democrats have relayed in recent weeks that the White House appears hopeful that the address will boost the President's polling by demonstrating leadership on national security and by showing empathy for Americans frustrated with Covid-19 and inflation.                                                                                                                                                                                                                                                                                                                                                                           , This is a breaking story and will be updated.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , CNN's Kate Bennett, Kevin Liptak, Jake Tapper, Donald Judd and Harry Enten contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/terms-of-trade </td>
   <td style="text-align:left;"> 2022-03-02 06:22:46 </td>
   <td style="text-align:left;"> New Zealand Terms of Trade Falls More than Expected in Q4 </td>
   <td style="text-align:left;"> The merchandise (goods) terms of trade in New Zealand decreased 1.0 percent on quarter in the three months to December of 2021, following a downwardly revised 0.4 percent gain in the previous period, and compared with market expectations of a 0.8 percent drop. Export prices rose 2.7 percent, easing from a 4.6percent gain in the prior period, while import prices went up 3.8 after a revised 4.1 percent increase in the previous quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/api-crude-oil-stock-change </td>
   <td style="text-align:left;"> 2022-03-02 06:18:42 </td>
   <td style="text-align:left;"> US Crude Oil Inventories Unexpectedly Fall: API </td>
   <td style="text-align:left;"> Stocks of crude oil in the United States decreased by 6.058 million barrels in the week ended February 25th of 2022, following a 5.983 million barrels fall in the previous week and compared with market expectations of a 2.796 million rise, data from the American Petroleum Institute showed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rice </td>
   <td style="text-align:left;"> 2022-03-02 06:16:27 </td>
   <td style="text-align:left;"> Rice Hits 19-Month High </td>
   <td style="text-align:left;"> Chicago rough rice futures skyrocketed to around $15.9 per hundredweight in the first week of March, a level not seen since July of 2020, as the ban on imports of fertilizers by Sri Lanka's imposed last year contributed to a decline in crop output. Also, investors expect that farmers will substitute the crops less dependent upon fertilizers, such as soybeans, for others with more favourable financial returns, such as corn. Moreover, prices increased on the back of logistic bottlenecks limiting rice exports from India, the world's biggest rice exporter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/01/stocks-making-the-biggest-moves-after-hours-nordstrom-sofi-hewlett-packard-and-more.html </td>
   <td style="text-align:left;"> 2022-03-02 06:06:38 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Nordstrom, SoFi, Hewlett Packard and more </td>
   <td style="text-align:left;"> , Check out the companies making headlines after hours.                                                                                                                                                                                                                                                                                                                                                  , Nordstrom — Shares of the retailer spiked 30% after hours after the company reported a beat on quarterly earnings and revenue and issued guidance for fiscal 2022 projecting revenue up 5% to 7% compared with 2021 levels. Analysts were looking for growth of 3.7%. Nordstrom also highlighted improvements in its off-price business, Nordstrom Rack, following underperformance in recent quarters., SoFi — The fintech company's shares surged by about 16% following its quarterly earnings report. The digital financial services company reported a quarterly loss of 15 cents per share, which was narrower than the consensus estimate of a 17 cent per share loss. Revenue came in at $278.8 million, slightly beating estimates of $279.3 million.                                                  , Salesforce — The software company got a roughly 3% boost in extended trading after it reported better-than-expected earnings and revenue for its most recent quarter. It also issued upbeat guidance for the 2023 fiscal year projecting between $32 billion and $32.1 billion in revenue. Analysts surveyed by Refinitiv had been looking for $31.78 billion in revenue.                              , Hewlett Packard Enterprise — Shares of Hewlett Packard added 1.5% after the company reported a slight earnings beat for the most recent quarter, but a quarterly revenue miss. Earnings of 53 cents per share for the quarter beat analysts estimates by 7 cents. Revenue of $6.96 billion was below the consensus estimate of $7.03 billion.                                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                 , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                 , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                       , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                       , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                     , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/first-solar-stock-falls-after/story.aspx?guid={7D7EC265-3366-4017-97DC-B4AD0CDE8E6E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-02 06:02:57 </td>
   <td style="text-align:left;"> First Solar stock falls after mixed Q4, lower guidance - MarketWatch </td>
   <td style="text-align:left;"> Shares of First Solar Inc. 
        FSLR,
        +0.44%
       fell more than 11% in the extended session Tuesday after the solar-panel maker reported a mixed quarter, with sales falling short of Wall Street expectations, and 2022 sales guidance was lower than estimates. First Solar said it earned $131 million, or $1.23 a share, in the fourth quarter, compared with $45 million, or 42 cents a share, in the year-ago quarter. Sales rose to $907 million from $584 million a year ago. Analysts polled by FactSet expected the company to report adjusted profit of $1.06 a share on sales of $918 million. The industry faced "supply chain, logistics, cost, and pandemic-related challenges," Chief Executive Mark Widmar said in a statement, and continues to navigate near-term headwinds. The year is "pivotal" and will revolve around "continued significant investment in R&amp;D, new products, manufacturing expansion, and employing new contracting strategies," he said. First Solar guided for 2022 net sales between $2.4 billion and $2.6 billion, and 2022 EPS between breakeven and 60 cents a share. That compares with 2022 sales expectations around $2.8 billion, according to FactSet.  , Shares of EPAM Systems Inc. suffered a record selloff in very volatile trading Monday, after the provider of digital transformation services pulled its financial guidance given "heightened uncertainties" resulting from Russia's invasion of Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/is-putin-playing-checkers-in-a-chess-world </td>
   <td style="text-align:left;"> 2022-03-02 05:56:34 </td>
   <td style="text-align:left;"> Is Putin playing checkers in a chess world? </td>
   <td style="text-align:left;"> Former Bush 43 Chief of Staff Andy Card provides insight into Russia’s invasion of Ukraine ahead of Biden’s State of the Union address.                                                                                                                                                                                                                                                                                                                                           , Some of the best chess masters in the world have come from Russia, and Putin is frequently compared to one. Is this Ukrainian gambit simply a feint to commit the U.S. and Europe to a NATO-free zone in Ukraine? Or does Putin want to grab back all of what was once a locus of industrial might for the old Soviet Union as well as a key global breadbasket?                                                                                                                  , RUSSIA-UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                                                                                                                                      , It is impossible for anybody to know other than Putin himself. This, however, we do know.                                                                                                                                                                                                                                                                                                                                                                                         , As Russia continues its aggression, the Biden regime will impose ever-harsher financial sanctions. From my days in the White House, I can say this is a losing "short term pain" strategy that will simply allow Putin to digest and consolidate his long-term gains.                                                                                                                                                                                                             , MEET PUTIN'S INNER OLIGARCH CIRCLE AS US SANCTIONS FLY                                                                                                                                                                                                                                                                                                                                                                                                                            , In the Trump White House, the more we imposed sanctions, the more China and Russia pursued evasive "de-dollarization" and import substitution strategies. Today, more and more of China’s massive trade — including with Russia — is yuan-based. Russia has aggressively substituted dollars with euros, gold and yuan in its National Wealth Fund.                                                                                                                               , In truth, the ubiquity of sanctions during the Trump years merely — and perversely — hastened China’s and Russia’s moves to liberate themselves from U.S. sanctions coercion, and both countries now rightly view digital currency as a powerful — perhaps the ultimate — de-dollarization tool.                                                                                                                                                                                  , SHELL KISSES RUSSIA- GASPROM GOODBYE                                                                                                                                                                                                                                                                                                                                                                                                                                              , Second, in a world of realpolitik, tough sanctions talk is rarely reflected in a real sanctions walk. The financial stakes are so high that globalist politics inevitably lead to slack in both coverage and enforcement.                                                                                                                                                                                                                                                         , In Europe, too many countries are too dependent on Russian natural gas to risk a cutoff by truly tough sanctions. Germany, Italy and France fall into this category.                                                                                                                                                                                                                                                                                                              , In the US, when I was in the White House, I watched Treasury Secretary Steven Mnuchin — the Neville Chamberlain of our time — repeatedly weaken President Trump’s sanctions strategy on behalf of Wall Street and corporate interests through unnecessary bureaucratic delays and numerous exemptions. I have little doubt such globalist interests have penetrated the Biden’s Treasury just as effectively — so don’t look for even the U.S. to walk its tough sanctions talk.  ,   ( REUTERS/Evgenia Novozhenina/Pool / Reuters Photos)                                                                                                                                                                                                                                                                                                                                                                                                                            , If Putin succeeds in Ukraine, look for Xi Jinping to make a move on Taiwan. Communist China will support Russia’s efforts to return Ukraine to "Mother Russia." Russia will return the favor when Xi makes his move to crush "sacred" Taiwan. As Xi sat with Putin watching the opening ceremony of Beijing’s Genocide Olympics, this had to be at the top of their revanchist agenda.                                                                                            , There is some hope Putin may be playing checkers in a chess world. He has shot himself in both feet by putting an end to a new Nord Stream 2 pipeline to Germany. Putin is also pushing every country anywhere near Russia’s expansive borders into the arms of the West. And Russia’s fragile economy can ill afford a prolonged guerrilla war in Ukraine, which it will surely get if he tries to take all of Ukraine.                                                          , Russia has already also bolstered its pariah status around the world and therefore must become ever more dependent on Communist China, which, not without irony, has its own hungry, expansionist eye on Siberia and its massive natural resource wealth. Here, I have always thought the U.S. is a far more natural ally for Russia than China, but neither the U.S. nor Putin have been playing that hand well.                                                                 , Russia’s revanchism might even bring a woke America Left back to its senses. Under Trump, we achieved energy dominance. With the right market and government signals, we could quickly achieve such dominance again and thereby help Europe wean itself from Russian gas. Fracking is dead; long live fracking.                                                                                                                                                                   , Stripped of rhetoric, a dictator has invaded a democracy in Europe, and Putin is now the odds-on favorite to get away with it without provoking World War III. Yet, the sum of my own worst fears is this:                                                                                                                                                                                                                                                                        , We are now in a post-nuclear age where cyber warfare can bring any nation to its knees without resort to the incineration of millions and a long nuclear winter. In this age of what Communist China calls "unrestricted warfare," cyber soldiers can now readily destroy the transportation, food and energy systems of target countries even as they use sophisticated blockchain technologies to cripple and loot financial institutions.                                      , Of those countries most skilled in such unrestricted warfare, Russia and China stand head and shoulders above all other nations, including the United States. If things spiral out of control in a Sarajevo redux scenario, we could all soon be cut off from each other, freezing and starving in the dark.                                                                                                                                                                      , As the boss used to tell me in the White House, let’s see what happens. In the meantime, world financial markets will remain in turmoil. Along with a pending stagflation, supply chain fragily and pandemic uncertainties, the Russia Bear is but one of a number of bears stalking Wall Street.                                                                                                                                                                                 , If we have learned nothing else, it is that elections have consequences.                                                                                                                                                                                                                                                                                                                                                                                                          , Peter Navarro is the former Assistant to the President for Trade and Manufacturing the Trump White House and author of In Trump Time: A Journal of America’s Late Year.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/api-data-reportedly-show-weekly/story.aspx?guid={CD7B7BB2-DB12-4AED-B123-08AD9FBB10E7}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-02 05:56:19 </td>
   <td style="text-align:left;"> API data reportedly show a weekly drop in U.S. crude supplies - MarketWatch </td>
   <td style="text-align:left;"> The American Petroleum Institute reported late Tuesday that U.S. crude supplies fell by 6.1 million barrels for the week ended Feb. 25, according to sources. The API also reportedly showed a weekly inventory decline of 2.5 million barrels for gasoline, while distillate stockpiles edged up by 400,000 barrels. Crude stocks at the Cushing, Okla., delivery hub were down by 1 million barrels last week, sources said. Inventory data from the Energy Information Administration will be released Wednesday. On average, the EIA is expected to show crude inventories up by 2.3 million barrels, according to analysts surveyed by Platts of S&amp;P Global Commodity Insights. The survey also showed expectations for weekly supply declines of 1.8 million barrels for gasoline and 2 million barrels for distillates. Oil prices extended their gain in the electronic trading session after the API data. April West Texas Intermediate crude 
        CLJ22,
        +5.36%
       was at $106.38 a barrel in electronic trading, after settling Tuesday at $103.41 on the New York Mercantile -- the highest finish for a front-month contract, with prices buoyed by Russia-Ukraine crisis supply risks. , Shares of SoFi Technologies Inc. were soaring 14% in after-hours trading Tuesday after the financial-technology company exceeded expectations with its earnings outlook.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/ross-stock-rallies-more-7/story.aspx?guid={CF8B90D5-3FBE-4684-A249-1513CE256AAB}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-02 05:47:25 </td>
   <td style="text-align:left;"> Ross stock rallies more than 7% after Q4 beat, plan to open more stores - MarketWatch </td>
   <td style="text-align:left;"> Ross Stores Inc. 
        ROST,
        -2.01%
       shares rose more than 7% in the extended session Tuesday after the retailer topped Wall Street expectations for its fourth quarter, said it plans to open more stores, and announced a dividend increase. Ross said it earned $367 million, or $1.04 a share, in the quarter, compared with $456 million, or $1.28 a share, in the year-ago period. Sales rose to $5 billion, from $4.4 billion a year ago, Ross said. FactSet consensus called for EPS of 95 cents on sales of $4.95 billion. "We achieved strong sales results in the fourth quarter despite the negative impact from both the surge in omicron cases during the peak holiday selling period and continued supply-chain congestion," Chief Executive Barbara Rentler said in a statement. Ross also said its board authorized a $1.9 billion share buyback program and increased the company's dividend by 9% to 31 cents a share. The dividend is payable March 31 to stockholders of record March 15. Rentler said that 2022 is "extremely difficult to predict," and not only because of the ongoing pandemic: Ross will be "up against last year's record government stimulus and the lifting of COVID restrictions that led to unprecedented consumer demand which fueled extraordinary sales gains in the Spring of 2021," she said. Consumers remain focused on "value and convenience," however, and Ross has seen favorable sales trends, leading it to plan a store expansion to 2,900 locations, up from a prior target of 2,400. For 2023 and beyond, it targeted a return to double-digit EPS growth., We screened for companies that are 30% to 50% off their highs and that now sport more reasonable price/earnings ratios.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/currency </td>
   <td style="text-align:left;"> 2022-03-02 05:37:01 </td>
   <td style="text-align:left;"> South Korean Won Hits 4-week Low </td>
   <td style="text-align:left;"> USDKRW increased to a 4-week high of 1209 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 05:24:00 </td>
   <td style="text-align:left;"> TSX Snaps Three-Day Rally </td>
   <td style="text-align:left;"> Canadian shares snapped three days of gains Tuesday, with the benchmark S&amp;P/TSX composite pulling back from an almost two-week high to end around the 21,000-level. The sentiment was rattled by increasing fears over the impact of aggressive sanctions against Russia after its invasion of Ukraine. Putting a floor under prices were soaring commodities prices, which, in turn, pushed heavyweight energy and materials stocks sharply higher. On the data front, the latest GDP figures showed that the Canadian economy expanded an annualized 6.70% on quarter at the end of 2021, slightly beating market forecasts. Magna International fell almost 8%, the most on the index, and the second biggest loser was Bombardier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/apple-halts-sales-russia-bans-state-owned-media-app-store </td>
   <td style="text-align:left;"> 2022-03-02 05:17:36 </td>
   <td style="text-align:left;"> Apple halts sales in Russia over Ukraine invasion </td>
   <td style="text-align:left;"> Business and economics professor Brian Brenberg breaks down how world powers are decimating Russia's economy as a response to violence in Ukraine.                                                                                                                                                                                                                                                                                                                                                                   , Apple on Tuesday announced it has halted sales of its products in Russia in response to the country's invasion of Ukraine.                                                                                                                                                                                                                                                                                                                                                                                           , An Apple logo hangs above the entrance to the Apple store on 5th Avenue in the Manhattan borough of New York City, U.S., December 5, 2016. (REUTERS/Brendan McDermid / Reuters Photos)                                                                                                                                                                                                                                                                                                                               , "We are deeply concerned about the Russian invasion of Ukraine and stand with all of the people who are suffering as a result of the violence," the company said in a statement, noting that they are providing aid for those impacted by the crisis."We have taken a number of actions in response to the invasion," the statement continued. "We have paused all product sales in Russia. Last week, we stopped all exports into our sales channel in the country. Apple Pay and other services have been limited.", An RT News logo seen displayed on a smartphone screen with a flag of Ukraine in the background (Photo illustration by Nikolas Kokovlis/NurPhoto via Getty Images) (Photo illustration by Nikolas Kokovlis/NurPhoto via Getty Images / Getty Images)                                                                                                                                                                                                                                                                  , AS RUSSIA-UKRAINE WAR RAGES, DIRECTV NIXES RT AMERICA FROM PROGRAM LINEUP                                                                                                                                                                                                                                                                                                                                                                                                                                            , Apple went on to say that state-owned Russian media outlets "RT News and Sputnik News are no longer available for download from the App Store outside Russia," and that the tech giant has "disabled both traffic and live incidents in Apple Maps in Ukraine as a safety and precautionary measure for Ukrainian citizens."                                                                                                                                                                                         , The company added that it is "in communication with relevant governments on the actions we're taking."                                                                                                                                                                                                                                                                                                                                                                                                               , The announcement comes as tech companies face increasing pressure to join in cracking down on Russia over its aggression.                                                                                                                                                                                                                                                                                                                                                                                            , MOUNTAIN VIEW, CA - OCTOBER 28: Google headquarters is seen in Mountain View, California, United States on October 28, 2021. (Photo by Tayfun Coskun/Anadolu Agency via Getty Images) (Tayfun Coskun/Anadolu Agency via Getty Images / Getty Images)                                                                                                                                                                                                                                                                 , Also on Tuesday, Google confirmed to Reuters that it had scrubbed RT News and other state-run Russian media from its news-related features, after earlier restricting them from advertising tools and other features on YouTube.                                                                                                                                                                                                                                                                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , RT News deputy editor-in-chief Anna Belkina hit out at the firms over the actions, telling Reuters that the tech companies that have restricted her outlets have not pointed to "a single grain of evidence that what RT has reported over these days, and continues to report, is not true."                                                                                                                                                                                                                        , "This collective ‘establishment’ seems to be terrified of a mere presence of any outside voice for the fear of losing their historically captive audience, if that audience encounters a different perspective," she added. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/crm:us </td>
   <td style="text-align:left;"> 2022-03-02 05:08:04 </td>
   <td style="text-align:left;"> Salesforce.com earnings above expectations at 0.84 USD </td>
   <td style="text-align:left;"> Salesforce.com (CRM) released earnings per share at 0.84 USD, compared to market expectations of 0.75 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 05:03:00 </td>
   <td style="text-align:left;"> US Stocks Kicked Off March on Sour Note </td>
   <td style="text-align:left;"> Wall Street ended the first trading day of March sharply down, with the Dow Jones tumbling almost 700 points and the S&amp;P 500 and the tech-heavy Nasdaq declining 2% each. Market sentiment remains dominated by war headlines, with Russian troops bombing cities and enclosing the capital city of Kyiv. On top of that, energy prices have skyrocketed since the Russian invasion began, adding to the headache for Central Banks trying to tame the highest inflation in decades. Falls are the most pronounced in financial stocks, which may be the most impacted by sanctions, with American Express down over 8% and Bank of America, JP Morgan, and Goldman Sachs shedding more than 3%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/01/us/politics/inflation-biden-state-of-the-union.html </td>
   <td style="text-align:left;"> 2022-03-02 04:41:08 </td>
   <td style="text-align:left;"> Biden Says Fighting Inflation Is ‘Top Priority’ as Prices Bite Consumers - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Timing is not in the president’s favor as elections that could cost his party control of Congress approach, and inflation has yet to fade.                                                                                                                                                                                                                                                                                                                                           , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , [Follow for live updates on Biden’s 2022 State of the Union address.]                                                                                                                                                                                                                                                                                                                                                                                                                , President Biden used his State of the Union address to refocus the nation on how far the economy has come since the pandemic recession. But he also highlighted his plans to help slow rapid price gains, underscoring the challenge Democrats face ahead of the midterm elections: Inflation is painfully high, voters are unhappy, and the tried and true way to cool price increases is by hurting growth and the labor market.                                                   , Mr. Biden acknowledged the toll that inflation was taking on everyday Americans, saying “my top priority is getting prices under control.”                                                                                                                                                                                                                                                                                                                                           , “Too many families are struggling to keep up with the bills. Inflation is robbing them of the gains they thought otherwise they would be able to feel. I get it,” Mr. Biden said.                                                                                                                                                                                                                                                                                                    , The president outlined a rough plan for beating back rapid price increases, including encouraging corporate competition and strengthening a supply chain that has struggled to keep up with consumer demand. He said his administration would begin a “crackdown” on ocean shipping costs, which have soared during the pandemic.                                                                                                                                                    , “My plan to fight inflation will lower your costs and lower the deficit,” he said.                                                                                                                                                                                                                                                                                                                                                                                                   , But White House policies have historically served as a backup line of defense when it comes to containing inflation, which is primarily the Federal Reserve’s job. The central bank is prepared to move swiftly in the coming months to raise interest rates, making money more expensive to borrow and spend. Higher rates are meant to slow hiring, wage growth and demand enough to tamp down price increases.                                                                    , It is possible that inflation could cool so much on its own this year that the Fed will be able to gently slow the economy toward a sustainable path. But if price gains remain rapid, the Fed’s playbook for combating overheating is by inflicting economic pain.                                                                                                                                                                                                                  , That is why inflation — which is running at the fastest pace in 40 years — is a major liability for the Biden administration, one that Mr. Biden could hardly avoid addressing Tuesday night. It is undermining consumer confidence by chipping away at paychecks and causing sticker shock for consumers trying to buy groceries, couches or used cars. And the cure could slow a solid economic rebound just as Democrats are trying to make their pitch for re-election to voters., “The biggest problem for President Biden is that there’s no good way to message inflation,” said Jason Furman, a Harvard economist and former White House economic official during the Obama administration. “There’s not a lot that he can do about it, but he can’t get up there and say: The only solution here is patience and the Federal Reserve.”                                                                                                                             , Mr. Biden argued that his administration’s policies could help to cool down inflation at less of a cost to the economy, by expanding its capacity to produce goods and services.                                                                                                                                                                                                                                                                                                     , “One way to fight inflation is to drive down wages and make Americans poorer,” he said, referencing the way that central bank policy works. “I think I have a better plan to fight inflation. Lower your costs and not your wages.”                                                                                                                                                                                                                                                  , Mr. Furman said that while the sort of solutions the president laid out — ideas to improve supply chains and expand work force opportunities — were “the right things” for the administration to do, the nation should not be “under any illusion that it is going to add up to a lot” in terms of cooling rapid price gains.                                                                                                                                                        , The president also tried to underline the economic wins of his presidency, which has seen the labor market strengthen markedly.                                                                                                                                                                                                                                                                                                                                                      , The economy has added 6.6 million jobs back since Mr. Biden took office, unemployment is poised to fall below 4 percent and growth has been more rapid than in many other advanced economies. The strength and scope of the rebound has surprised economists and policymakers, who often credit relief packages rolled out under the Trump and Biden administrations for fomenting such a quick recovery.                                                                            , But some economists warned last year that the $1.9 trillion legislation the administration ushered through Congress in March 2021 was too big and too poorly targeted, and that it would stoke demand and help to fuel rapid price gains. While fiscal policy was not the only reason inflation popped last year, it does seem to have contributed to high prices by encouraging more consumption.                                                                                   , As flush consumers spent strongly in 2020 and last year, and as homebound shoppers bought more goods like easy chairs and computers rather than services like manicures and meals out, supply chains struggled to keep up.                                                                                                                                                                                                                                                           , Virus outbreaks continued to shut down factories, ports became clogged, and there were not enough ships to go around. The perfect storm of strong buying and limited supply pushed car prices in particular sharply higher, left consumers waiting months on end for new dining room sets, and meant that fancy bicycles were harder to find and afford.                                                                                                                             , And now, inflation has moved past just those goods affected by the pandemic.                                                                                                                                                                                                                                                                                                                                                                                                         , The cost of food, fuel, housing, vacations, and furniture are all rising rapidly — and as conflict in Russia threatens to further push up gas prices in the coming months, the situation is likely to get worse before it gets better.                                                                                                                                                                                                                                               , While the White House spent last year downplaying popping prices, arguing that they would fade with the pandemic as roiled global supply chains righted themselves, nearly a full year of high inflation readings have proved too much to ignore. Climbing costs are eating away at paychecks and helping to drive Mr. Biden’s poll numbers to the lowest point so far in his presidency.                                                                                            , “I don’t think that it is going to go away in a way that is going to save the incumbent party by November,” said Neil Dutta, an economist at Renaissance Macro Research. “Even though the labor market is quite strong, it’s not enough to keep pace with the shock people are feeling with respect to inflation.”                                                                                                                                                                   , The Fed is expected to raise interest rates from near-zero at its meeting this month and officials have signaled that they will then make a series of increases throughout the year as they try to put a lid on inflation.                                                                                                                                                                                                                                                           , The central bank sets policy independently of the White House, and the Biden administration avoids talking about monetary policy out of respect for that tradition. But the timing could be politically tricky. The Fed could prompt an economic pullback that coincides with this autumn’s election season, creating a double whammy for the Democrats in which central bank policy is slowing down job market progress even as inflation has yet to fully fade.                    , That might be especially true if conflict in Ukraine sends fuel prices higher, further stoking inflation and making consumers expect rapid price increases to continue, some economists said.                                                                                                                                                                                                                                                                                        , “The Fed has to be more aggressive on inflation,” said Diane Swonk, the chief economist at Grant Thornton. “It could bleed into the unemployment rate by the end of the year.”                                                                                                                                                                                                                                                                                                       , Mr. Furman said that he thought it was more likely that the Fed’s actions would not inflict too much pain this year, though they might begin to squeeze the job market in 2023. And Mr. Dutta speculated that the Russian invasion of Ukraine could slow the central bank down somewhat, at least in the near-term.                                                                                                                                                                  , “The Fed basically has a choice — they can sink the economy into a recession, or they can let inflation run a little bit,” Mr. Dutta said. “They’re not going to risk a recession with the geopolitical situation we’re in.”                                                                                                                                                                                                                                                         , The conflict overseas may also give Mr. Biden and Democrats a moment of patriotism to capitalize on. So far, Mr. Biden’s sanctions have been well-received by voters, based on the results of an ABC/Washington Post poll.                                                                                                                                                                                                                                                           , At the same time, higher gas pump prices resulting from the conflict could further dent consumer confidence. Sentiment has swooned as price increases have climbed, and tends to be very responsive to fuel costs. The price of a barrel of gas climbed above $100 on Tuesday, the highest since 2014, based on a popular benchmark.                                                                                                                                                 , The question is whether, in the face of rising costs, the administration will be able to turn bright spots — international cooperation and the pace of recent job gains — into something salient for consumers and voters.                                                                                                                                                                                                                                                           , The answer may hinge on what happens next.                                                                                                                                                                                                                                                                                                                                                                                                                                           , Annual price gains are expected to slow down in the coming months as they are measured against relatively high readings from last year, and as supply chain delays ease somewhat. They could moderate even more later this year if the current elevated goods prices come back down, in the most hopeful scenario.                                                                                                                                                                   , If inflation moderates on its own and a relatively small response from the Fed is enough to nudge it down further, the economy could be left with strong growth, a booming labor market and a positive outlook headed into 2023.                                                                                                                                                                                                                                                     , But increasingly, inflation is expected to fade more slowly.                                                                                                                                                                                                                                                                                                                                                                                                                         , Economists at Goldman Sachs think consumer price inflation could end 2022 at 4.6 percent, more than twice the level it hovered around before the pandemic. That would mark a slowdown — the measure now stands at 7.5 percent — but it would be much higher than what the Fed normally aims for.                                                                                                                                                                                     , That would allow the administration to talk about a moderation in price gains, but it might not feel like a significant improvement to consumers as they head to the polls.                                                                                                                                                                                                                                                                                                          , “Inflation is always political, because it burns, even in a good economy,” Ms. Swonk said. “It creates a sensation of chasing a moving target, which no one likes.”                                                                                                                                                                                                                                                                                                                  , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 04:30:17 </td>
   <td style="text-align:left;"> The Dow Jones Index decreasing 1.87% </td>
   <td style="text-align:left;"> United States Stock Market is falling 635 points. Losses were driven by American Express (-8.20%), Boeing (-5.16%) and JPMorgan (-4.33%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60579640?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-02 04:19:22 </td>
   <td style="text-align:left;"> Ship carrying 4,000 luxury cars sinks off the Azores </td>
   <td style="text-align:left;"> A cargo ship that was carrying thousands of luxury cars has sunk off the Portuguese Azores archipelago, nearly two weeks after it caught fire.                                                                                                                                                   , The ship, named Felicity Ace, was transporting around 4,000 cars such as Porsches and Bentleys.                                                                                                                                                                                                  , The vessel was on its way to Rhode Island in the United States from the German port of Emden when the fire broke out.                                                                                                                                                                            , All of its crew members were evacuated when the fire broke out on February 16.                                                                                                                                                                                                                   , Joao Mendes Cabecas, the captain of the nearest port on the island of Faial, told Reuters that no oil leak had been reported so far but said there were fears the fuel tanks could be damaged while the vessel lies at the bottom of the Atlantic at a depth of around 3,500 metres (2.17 miles)., Portugal's navy said no one was hurt by the fire and that the 22 crew members were taken to a hotel after the navy, four merchant ships sailing in the area and the Portuguese Air Force completed the evacuation.                                                                               , Volkswagen said the damage to the vehicles was covered by insurance which could cost around $155m (£116m) according to Reuters.                                                                                                                                                                  , Bentley confirmed that 189 of its cars were onboard the ship and Porsche said it had about 1,100 of its models onboard.                                                                                                                                                                          , One customer tweeted to say his Porsche was on board the abandoned ship.                                                                                                                                                                                                                         , Another tweeted that his had been reordered.                                                                                                                                                                                                                                                     , Watch the final series of Killing Eve on BBC iPlayer                                                                                                                                                                                                                                             , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                                                                                                      , The unlikely Olympian talks to Colin Murray about how fear gives him focus                                                                                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/uk-sanctions-belarus-russia-invasion-ukraine </td>
   <td style="text-align:left;"> 2022-03-02 04:09:21 </td>
   <td style="text-align:left;"> UK sanctions Belarus over its role in Russia’s invasion of Ukraine </td>
   <td style="text-align:left;"> Former Bush 43 Chief of Staff Andy Card provides insight into Russia’s invasion of Ukraine ahead of Biden’s State of the Union address.                                                                                                                                                          , The United Kingdom on Tuesday slapped Belarus with sanctions for supporting Russia in its invasion of Ukraine.                                                                                                                                                                                   , The sanctions target Belarus' Chief of the General Staff and three deputy defense ministers as well as two military enterprises.                                                                                                                                                                 , In this handout photo provided by UK Parliament, Britain's Foreign Secretary Liz Truss speaks in the House of Commons, London, Monday Feb. 28, 2022, as she announced new sanctions against Russia.  (Jessica Taylor/UK Parliament via AP)                                                       , "We are inflicting economic pain on Putin and those closest to him," U.K. Foreign Secretary Liz Truss said in a statement. "We will not rest until Ukraine’s sovereignty and territorial integrity is restored."                                                                                 , Moscow deployed forces to Belarusian territory under the pretext of joint military drills weeks before Russian troops rolled into Ukraine and began attacking.                                                                                                                                   , RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                             , Truss accused Belarusian President Alexander Lukashenko of aiding and abetting Russia’s "illegal invasion."                                                                                                                                                                                      , "There will be nowhere to hide. Nothing – and no one – is off the table," she said.                                                                                                                                                                                                              , The U.K. government says Major General Victor Gulevich "supported and enabled" the Russian invasion of Ukraine by directing joint military exercises with Russia and consenting to the deployment of Russian troops along the border with Belarus with Ukraine.                                  , A Belarusian national flag flutters over a street in Minsk, Belarus, Wednesday, Feb. 16, 2022. (AP Photo/Alexander Zemlianichenko Jr)                                                                                                                                                            , The other sanctioned individuals include military generals Andrei Burdyko, Sergei Simonenko, and Andrey Zhuk. State enterprises JSC 558 Aircraft Repair Plant and military semiconductor manufacturer JSC Integral are included in the sanctions.                                                , The U.K. government says JSC 558 provides maintenance and service to military aircraft at Baranovichi air base, from which Russian aircraft operated as part of the invasion.                                                                                                                    , MEET THE RUSSIAN OLIGARCHS GETTING SLAMMED BY US SANCTIONS                                                                                                                                                                                                                                       , The latest sanctions from the U.K. follow Prime Minister Boris Johnson’s announcement last week that the U.K. will freeze assets of all major Russian banks and block Russian entities from raising money on U.K. markets as part of the international response to Russia’s invasion of Ukraine. , An overview of troops at the Lesnovsky training area, near Baranovichi, Belarus, is seen in this Maxar satellite image taken on January 29, 2022.  (Courtesy of Satellite image ©2022 Maxar Technologies/Handout via REUTERS)                                                                    , Hundreds of Belarusians took to the streets Sunday in 15 cities across the country, protesting Russia’s invasion of Ukraine in the biggest show of defiance since mass demonstrations in 2020.                                                                                                   , CLICK HERE TO READ FOX BUSINESS ON THE GO                                                                                                                                                                                                                                                        , According to Viasna human rights center, 726 people were detained over the demonstrations. Some of them were apprehended overnight in their homes.                                                                                                                                               , Fox News’ Adam Shaw and The Associated Press contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60557081?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-02 04:01:31 </td>
   <td style="text-align:left;"> Russian oligarch Fridman warns sanctions will not stop war </td>
   <td style="text-align:left;"> This video can not be played                                                                                                                                                                                                                                                                                                            , One of Russia's richest men has said imposing sanctions on oligarchs would have no impact on Moscow's decision to launch a war in Ukraine.                                                                                                                                                                                              , Billionaire banker Mikhail Fridman told a press conference in London the war was a tragedy for both sides.                                                                                                                                                                                                                              , But he stopped short of direct criticism, saying personal remarks could be a risk not just to himself but also staff and colleagues.                                                                                                                                                                                                    , He joins another businessman, Oleg Deripaska, in calls for peace.                                                                                                                                                                                                                                                                       , The two men are the most prominent oligarchs to speak out against Russia's invasion, now in its sixth day.                                                                                                                                                                                                                              , The UK also sanctioned Belarusian military chiefs on Tuesday for their role in "abetting" the Russian invasion of Ukraine.                                                                                                                                                                                                              , The Foreign Office said the Belarusian military has "supported and enabled the Russian invasion of Ukraine" and has also sanctioned some of its state manufacturing firms.                                                                                                                                                              , The Belarus sanctions are on top of those already applied on Minsk by the UK since 2020 when over 100 people and organisations were targeted in response to the fraudulent elections in Belarus.                                                                                                                                        , Born in Ukraine before the break-up of the Soviet Union, Mr Fridman was the founder of Russia's biggest private bank, Alfa, and runs investment firm LetterOne which has extensive interests in oil and retailing.                                                                                                                      , The billionaire said the sanctions, which freeze some assets and impose a travel ban, were unjustified and he would fight them.                                                                                                                                                                                                         , But he added the sanctions would, in any case, not have the desired effect of helping to rein in the Kremlin.                                                                                                                                                                                                                           , He said: "My parents always told me: you know, because you are a Jew, you could not be in this position or that position, in this university or this job.                                                                                                                                                                               , "Now, I'm facing the same situation here in the West, because you are Russian."                                                                                                                                                                                                                                                         , On Monday, the European Union slapped sanctions on Mr Fridman, who lives in London, and long-time partner Pyotr Aven.                                                                                                                                                                                                                   , The EU statement described Mr Fridman as "a top Russian financier and enabler of Putin's inner circle".                                                                                                                                                                                                                                 , Mr Fridman said the conflict in Ukraine should end as soon as possible, but avoided questions about outright condemnation of President Vladimir Putin's actions.                                                                                                                                                                        , "Please, don't push me to comment," he said, adding it would be not just "my personal risk, but also a risk for my colleagues and staff".                                                                                                                                                                                               , He said his companies had tens of thousands of staff in Russia, Ukraine and the UK. "It's a very sensitive issue. We have a dozens of partners and I do not have a right to put all of them at risk."                                                                                                                                   , Mr Deripaska, who founded one of Russia's largest industrial groups, has also pleaded for peace in a post on the messaging app Telegram.                                                                                                                                                                                                , Russian billionaire oligarchs do not give many press conferences.                                                                                                                                                                                                                                                                       , In some Western circles, the mere sight of banker and industrialist Mikhail Fridman defending himself after being sanctioned by the EU, shows the strategy of squeezing Russia financially is having the desired impact.                                                                                                                , Mr Fridman, who was born in Ukraine, said sanctions were having a drastic impact on the Russian economy, and called for an end to the conflict - but said he had no influence over the actions of President Putin.                                                                                                                      , The founder of Alfabank said when asked if there was a bank run in Russia, that there was huge pressure on the Russian currency the rouble. He said many Russians were going to banks to withdraw roubles to convert into dollars because of dramatic moves in value, to keep hard currency "under the mattress".                       , But he feels the EU is treating him unfairly and without due process, that he should be sent back to Russia, for having been born in the former Soviet Union. And tellingly, while wishing for the war to end, he said journalists could not expect him to criticize President Putin, given the risk to his staff in Russia and Ukraine., Watch the final series of Killing Eve on BBC iPlayer                                                                                                                                                                                                                                                                                    , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                                                                                                                                             , The unlikely Olympian talks to Colin Murray about how fear gives him focus                                                                                                                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/canola </td>
   <td style="text-align:left;"> 2022-03-02 03:48:16 </td>
   <td style="text-align:left;"> Canola is up by 6.19% </td>
   <td style="text-align:left;"> Canola increased 6.19% to 1097 CAD/T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-log-highest/story.aspx?guid={7E9300B5-8DB7-4D4A-9630-FA7E2ABED032}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-02 03:39:46 </td>
   <td style="text-align:left;"> U.S. oil futures log highest finish since July 2014 on Russia-Ukraine crisis supply concerns - MarketWatch </td>
   <td style="text-align:left;"> Oil futures rallied on Tuesday, with U.S. prices ending at their highest since July 2014, supported by the ongoing threat to global supplies from the Russia-Ukraine crisis. Prices continued higher even after the International Energy Agency said its members agreed to release 60 million barrels from their emergency oil reserves to ease concerns over a potential global shortage. The biggest impact of the IEA's oil reserve release is "on market sentiment, given the delay and staggered nature between an announcement and the barrels hitting the physical market," said Matt Smith, lead oil analyst, Americas, at Kpler. West Texas Intermediate crude for April delivery 
        CLJ22,
        +5.36%
       rose $7.69, or 8%, to settle at $103.41 a barrel on the New York Mercantile Exchange. That was the highest front-month finish since July 22, 2014, according to FactSet data., Get ready for more 'Upload,' an animated spinoff of 'The Boys,' 'Lucy &amp; Desi' and Lizzo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/epam-stock-bounces-after-bullish/story.aspx?guid={F2F917DF-5904-4E65-B88F-7A3E3F8A6A74}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-02 03:36:18 </td>
   <td style="text-align:left;"> EPAM stock bounces after bullish Stifel analyst suggests record selloff may have created an opportunity - MarketWatch </td>
   <td style="text-align:left;"> Shares of EPAM Systems Inc. 
        EPAM,
        +1.67%
       bounced 8.5% in afternoon trading Tuesday, after Stifel Nicolaus analyst David Grossman said he was still bullish on the provider of digital transformation services company, as the record selloff in the wake of Russia's invasion of Ukraine may have created a buying opportunity. The stock had plunged 45.7% on Monday, and has now plummeted 46.1% in the four days since the full invasion started last Thursday (418.23), while the S&amp;P 500 
        SPX,
        -1.55%
       has gained 2.0% over the past four sessions. "While we acknowledge ongoing uncertainty/risk, EPAM is a bellwether at the high-end of the technology stack, the heart of digital transformation, and we have high confidence they can pivot and resume industry leading growth once things stabilize," Grossman wrote in a note to clients. He reiterated the buy rating he's had on the stock for at least the past three years. He slashed his stock price target to $385 from $630, but his new target still implies 70.8% upside from current levels. , Semiconductor companies are banning sales to Russia following the company's invasion of Ukraine, but an analyst says the companies shouldn't feel much of an effect.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/directv-pull-rt-channel-its/story.aspx?guid={92BD1DB1-E781-4FD6-995D-33E0DDD57A1D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-02 03:30:09 </td>
   <td style="text-align:left;"> DirecTV will pull RT channel from its lineup - MarketWatch </td>
   <td style="text-align:left;"> DirecTV will stop offering RT America, the Russian state-owned media channel, the telecommunications company said Monday. "In line with our previous agreement with RT America, we are accelerating this year's contract expiration timeline and will no longer offer their programming effective immediately," the spokesman told MarketWatch. DirecTV had already been in the process of evaluating whether RT America was valuable to its subscriber base and sped up the timeline for expiration due to the events in Ukraine, according to the spokesperson. DirecTV became its own company in August after it separated from AT&amp;T Inc. 
        T,
        -0.68%,
       which now has a 70% interest in the new company. Private-equity company TPG Capital has a 30% interest in the satellite-TV company. , We screened for companies that are 30% to 50% off their highs and that now sport more reasonable price/earnings ratios.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Emily Bary is a MarketWatch reporter based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/01/europe/ukraine-russia-kyiv-war-zone-intl/index.html </td>
   <td style="text-align:left;"> 2022-03-02 02:53:49 </td>
   <td style="text-align:left;"> 40-mile-long Russian convoy: Kyiv residents brace for arrival of huge military convoy - CNN </td>
   <td style="text-align:left;"> Kyiv, Ukraine (CNN)A drive through central Kyiv leaves no room for doubt. This is a city preparing for a major Russian attack.                                                                                                                                         , Rows of concrete panels arranged in maze-like formations. Anti-tank road blocks. Piles of sandbags. Improvised barriers built of random pieces of metal, wood, old tires or anything that was at hand.                                                                 , And everywhere you look, there are blue and yellow Ukrainian flags.                                                                                                                                                                                                    , The city is uncannily quiet. Many people have fled in recent days. Those who have stayed are hunkered down in bomb shelters, basements and subway stations.                                                                                                            , The checkpoints dotted along the city's entry points are manned by ordinary Ukrainians. These are not soldiers. A week ago, many of these men would have been at work, or enjoying time off with their friends and families.                                           , Now, they are ready to defend their country's capital.                                                                                                                                                                                                                 , Oleksiy Goncharenko was guarding one of the checkpoints in Kyiv on Tuesday, armed with the rifle he picked up last week after answering the call from Ukrainian authorities to prepare to defend the country.                                                          , It was bitterly cold, and Goncharenko was working in shifts, with other volunteers. When not at the checkpoint, he says he is at the base, helping wherever he can: "Humanitarian help, helping people to get [to places], organizing transport, sharing information." , Goncharenko is not — and has never been — a military man. He is a member of Verkhovna Rada, the Ukrainian parliament,                                                                                                                                                  , "I'm not a professional soldier at all, but I can try and I can do my best and I will do it if Russian forces enter Kyiv," he told CNN.                                                                                                                                ,                                                                                                                                                                                                                                                                        , Most of the men at the checkpoints are smiling. When a car passes through, they greet its passengers, wave and wish them a safe journey, wherever they are going.                                                                                                      , A man wearing glasses, a camouflage hat and woolly gloves with six of their 10 fingertips cut off flashes a quick V-sign and waves.                                                                                                                                    , The men here are trying to keep morale high, though they know only too well that the enemy they are facing is much better equipped.                                                                                                                                    , Russia has amassed a 40-mile-long (64-kilometer) military convoy -- made up of armored vehicles, tanks, towed artillery and other logistical vehicles -- that is approaching the outskirts of Kyiv.                                                                    , Most -- but not all -- of the men in the capital's streets are equipped with rifles. They are stationed alongside the road that connects Kyiv's city center with its suburbs.                                                                                          ,                                                                                                                                                                                                                                                                        , Armbands fashioned from a piece of yellow tape indicate they are part of the Territorial Defense Forces, a branch of Ukraine's armed forces that is comprised mostly of volunteers. Tens of thousands have joined up in recent days.                                   , Some look very, very young, wearing tracksuit bottoms and sneakers. In freezing cold weather, the city's defenders -- along with everyone else in Kyiv -- await whatever is yet to come.                                                                               , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/01/europe/russia-opposition-putin-media-intl/index.html </td>
   <td style="text-align:left;"> 2022-03-02 02:52:30 </td>
   <td style="text-align:left;"> Opposition to Putin's war is alive on Moscow's streets. But no trace of it is covered on Russian TV - CNN </td>
   <td style="text-align:left;"> Moscow (CNN)More than 6,400 Russians have been arrested in anti-war protests since President Vladimir Putin's troops invaded Ukraine, but not one bone-crunching detention has made state TV.                                                                                                                                                                        , Navigating the paradoxes of Putin's authoritarian rule is a way of life here. Intuition nourished by a lifetime of state-fed lies gets most people through. And for many it consists of a quiet life with a steady income.                                                                                                                                           , But what's happening now may be challenging some to push out of the old boundaries of the 'see but don't question orthodoxy' that historically reinforced Putin's grip on power.                                                                                                                                                                                     , By Tuesday morning in Moscow, more than 1 million signatures had been added to a Russian-language Change.org petition against the war in Ukraine.                                                                                                                                                                                                                    , On Moscow's streets police vans loiter at most major intersections, riot-ready cops menace the sidewalks, and the city's fabled Pushkin Square -- a once-popular protesters' haunt -- is surrounded by a vast metal barricade.                                                                                                                                       , What's going on is an all too obvious, overt opposition to Putin's rule. The cost of joining, the government warns, could be "arrest" and a "criminal record" that "leaves a mark on the person's future."                                                                                                                                                           , Protests are only considered for approval if requested no more than 15 days in advance and no less than 10, and even then there is no guarantee it will get the nod.                                                                                                                                                                                                 , Putin has no reason to publicize the anger at his rule and every reason to snuff it out.                                                                                                                                                                                                                                                                             , Instead of anti-war protests, the Kremlin's vast constellation of newspapers, magazines, websites and TV stations keep up a steady drumbeat of anti-Ukrainian propaganda that tries to rationalize the reasons their brothers, sons and husbands have been sent to war, and possibly their deaths, hundreds of miles away.                                           , The Kremlin has all but crushed Russia's independent media, and is gagging what's left of them. Ten publications got a letter late last week from the country's communications watchdog warning them not to use the words "invasion," "attack" and "declaration of war" under threat of having access to their publications "restricted."                            , The same letter said that correct information about the "Special Military Operation" -- as the Kremlin calls the war -- was freely available on government websites.                                                                                                                                                                                                 , But Putin doesn't control all the narratives all the time. A generation here has grown up willfully ignorant of state disinformation, weaned instead on social media, so are impervious to the lies that cowed their parents. They are, however, still contained by the massive state security infrastructure that is the real muscle behind state media's messaging., In short, they think for themselves, want the freedoms that come with that awareness but are bound by the brutality they meet when they protest.                                                                                                                                                                                                                     , One young woman CNN met on the margins of the first night of protest on Thursday was near tears explaining she loves Russia, but not her leader, so has concluded she must leave the country.                                                                                                                                                                        , There is a real frustration in that generation, but they are a minority -- less than 10% of the nation.                                                                                                                                                                                                                                                              , ​Indeed, the latest polling by the Russian Public Opinion Research Center (VCIOM), a state-owned but nevertheless internationally respected organization, found that 68% of people say they support the decision to carry out the "Special Military Operation," 22% oppose it and 10% had difficulty answering.                                                       , It is a sobering assessment that when Putin puts his finger in the wind of public opinion he can be reasonably sure it is blowing in the direction he instructed his state organs to set it.                                                                                                                                                                         , CNN's Nathan Hodge and Jill Dougherty contributed reporting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/ukraine-russia-shipping-companies-suspend-bookings </td>
   <td style="text-align:left;"> 2022-03-02 02:43:10 </td>
   <td style="text-align:left;"> Russia-Ukraine war: Global shipping titans suspend bookings to, from Russia </td>
   <td style="text-align:left;"> Alba Wheels Up International founder and Chairman Salvatore Stile discusses the U.S. supply chain issues as problems continue to stifle progress.                                                                                                                                                                         , Several global shipping giants have suspended bookings to and from Russia amid the country's invasion of Ukraine.                                                                                                                                                                                                         , Ocean Network Express (ONE), Maersk, MSC and Hapag-Lloyd all suspended operations in the country this week, as Bloomberg first reported.                                                                                                                                                                                  , ONE — the world's sixth-largest container carrier and Asia's second-largest — announced Tuesday that due to the ongoing conflict, it has suspended bookings to and from Odesa, Ukraine; Novorossiysk, Russia; and St. Petersberg, Russia, effective immediately.                                                          , Shipping containers sit on the deck of cargo ship One Crane, operated by Ocean Network Express Holdings Ltd., docked at ECT Delta terminal in the Port of Rotterdam, in Rotterdam, Netherlands. (Peter Boer/Bloomberg)                                                                                                    , "The ongoing safety and wellbeing of ONE’s employees &amp; associates in the region is of great importance and concern. Currently ONE’s representatives in the region are safe and continue to work remotely," Singapore-based ONE said.                                                                                      , MOSCOW SUSPENDS STOCK TRADING UNTIL MARCH 5                                                                                                                                                                                                                                                                               , MSC and Maersk — the first and second-largest shipping companies in the world, respectively — made similar announcements on Tuesday.                                                                                                                                                                                      , "We are deeply concerned by the crisis in Ukraine. We closely follow governments posing new sanctions on Russia, impacting operations from direct &amp; indirect restrictions. New Maersk bookings to/from Russia will be temporarily suspended except food, medical &amp; humanitarian supplies," Maersk said in a Tuesday tweet., The Danish company added that its decision to make food and humanitarian supplies exceptions "is to underline that our company is focusing on the social responsibility."                                                                                                                                                 , MSC said it is issuing "a temporary stoppage on all cargo bookings to/from Russia, covering all access areas including Baltics, Black Sea and Far East Russia," effective immediately, with the exception of food and humanitarian supplies.                                                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                               , MSC is "closely monitoring the advice from governments about new sanctions, following the February 2022 conflict in Ukraine, and has been operating shipping and inland services to and from Russia in full compliance with international sanctions measures, applicable to it," the company said.                        , Shipping containers sit aboard a Maersk container ship at the Port of Los Angeles on Feb. 9, 2022 in San Pedro, California. (Mario Tama/Getty Images) (Getty Images)                                                                                                                                                      , Hapag-Lloyd announced its suspension on bookings to and from Russia on Sunday, according to Bloomberg.                                                                                                                                                                                                                    , The temporary stoppages come as American credit card company MasterCard blocked services to multiple Russian financial institutions. Additionally, Harley-Davidson, Volvo and General Motors are suspending vehicle exports to Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/coal </td>
   <td style="text-align:left;"> 2022-03-02 02:32:00 </td>
   <td style="text-align:left;"> Coal Prices Hit Fresh Record High </td>
   <td style="text-align:left;"> Newcastle coal futures skyrocketed to a record high of $300 per tonne in early March and are now up almost 90% since the beginning of 2022, as mounting sanctions on Russia for invading Ukraine led to an international energy crunch and exacerbated concerns over the commodity's supply. Germany is poised to create coal reserves for electricity power plant operators, while Italy announced it could reopen some shuttered coal plants. Asian customers have also been scrambling to find alternative supplies to replace Russian coal. Such concerns about disruptions to Russian energy supplies drove oil well above $100 per barrel while natural gas in Europe soared nearly 30% to above €125 per megawatt-hour. Aside from Ukraine headlines, investors were already bullish on coal since early 2022 amid supply disruptions in top exporting countries such as Indonesia and Australia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-02 02:12:48 </td>
   <td style="text-align:left;"> US 10-Year Yield Falls Towards 1.7% </td>
   <td style="text-align:left;"> The benchmark 10-year Treasury note yield fell to almost 1.7% on Tuesday, the lowest in nearly seven weeks as demand for safe-haven assets surged as the situation in Ukraine is deteriorating by the hour and concerns are mounting over the impact of war on the global economy. Russia intensified the shelling of several cities and a huge Russian convoy heads towards Kyiv while cease-fire talks on Monday end nowhere. As a result, investors continue to scale back aggressive rate hike bets across major developed economies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/01/with-inflation-and-ukraine-powell-must-thread-a-needle-on-capitol-hill-this-week-to-calm-markets.html </td>
   <td style="text-align:left;"> 2022-03-02 02:12:26 </td>
   <td style="text-align:left;"> With inflation and Ukraine, Powell must thread a needle on Capitol Hill this week to calm markets </td>
   <td style="text-align:left;"> , Federal Reserve Chairman Jerome Powell is tasked with telling Congress this week that the central bank will be doing more to control inflation at a time when markets expect it will be doing less.                                                                                                                                                                                                                                                                       , With fears over the Russian invasion of Ukraine causing turmoil in the financial world, Wall Street has quietly dialed down its expectations for Fed action.                                                                                                                                                                                                                                                                                                              , Where markets had been expecting the Fed to raise interest rates up to seven times in 2022, recent pricing now indicates just five moves. That would be the equivalent of bringing the Fed's benchmark short-term borrowing rate up about 125 basis points, or to a range between 1.25%-1.5%.                                                                                                                                                                             , The shifting winds mean Powell has a tightrope to walk as he explains during two days of congressional testimony that his institution is committed to taming inflation while also being mindful of the geopolitical turmoil.                                                                                                                                                                                                                                              , "He has to thread a pretty thin needle. The balancing act is going to be difficult," said Mark Zandi, chief economist at Moody's Analytics. "My sense is he leads with the uncertainty that this all creates given that the Russian invasion could take many different paths, each one darker than the other. He'll reinforce the point that in a period of such heightened uncertainty, it might make sense for the Fed to be a little more cautious in enacting policy.", Up until a week or so ago, markets had been expecting the policymaking Federal Open Market Committee to approve 25 basis point hikes at each of its remaining seven meetings this year. There even was a strong lean to the first move, at the March 15-16 meeting, being 50 basis points.                                                                                                                                                                                , Russia's attack has taken that off the table, at least for now.                                                                                                                                                                                                                                                                                                                                                                                                           , "Play it by ear would be his best message," said Peter Boockvar, chief investment officer at Bleakley Advisory Group. "That would allow him to sort of skate around the very difficult position that he's currently in. We're going to deal with inflation, but — and that 'but' is let's see how the economy goes from here."                                                                                                                                            , Economists largely expect growth to be solid this year if a bit less than in 2021, which was the strongest since 1984. Fed officials in December projected GDP to accelerate at a 4% pace in 2022.                                                                                                                                                                                                                                                                        , However, unrelenting inflation, at its fastest level in 40 years, along with the prospects that the Russia-Ukraine situation could add to inflation and further complicate supply chains puts another wrinkle in the Fed policy outlook.                                                                                                                                                                                                                                  , Goldman says stock pickers are buying the dip in growth stocks. Here are their favorites                                                                                                                                                                                                                                                                                                                                                                                  , Defense stocks may see long-term lift as Russia's actions spur big jump in spending by U.S. allies                                                                                                                                                                                                                                                                                                                                                                        , These stocks have direct exposure to Russia, says Bank of America                                                                                                                                                                                                                                                                                                                                                                                                         , "We're entering a period of stagflation," Boockvar said, referring to higher inflation and low growth. "The question is, does [Powell] focus more on the 'stag' or does he focus more on the 'flation'? Just based on the history of the post-Volcker way of running monetary policy, the Fed focuses on growth."                                                                                                                                                         , Other economists, though, disagree.                                                                                                                                                                                                                                                                                                                                                                                                                                       , In a note to clients Sunday, Goldman Sachs said "very high inflation" this year "should make an easy case" for seven rate hikes this year. Bank of America also has not relented from its forecast of seven moves, and Citigroup economist Andrew Hollenhorst wrote Tuesday that "the market has been a bit too quick to price-out the potential for a 50 [basis point" hike at this month's FOMC meeting.                                                                , Nonetheless, as of Tuesday noontime, the market had completely taken a half-percentage-point hike off the table and in fact assigned a tiny possibility to no move at all, according to the CME Group. Futures pricing can be volatile, so the probabilities could swing back if inflation slows or the Ukraine situation is resolved.                                                                                                                                    , Powell, delivering his mandated semiannual update to a House panel Wednesday and then to a Senate committee Thursday, will have to address a wide range of views on where it should be at a critical time for monetary policy.                                                                                                                                                                                                                                            , "We think Powell will emphasize that amid heightened geopolitical uncertainty the Fed remains focused on its macro objectives and will continue to move ahead with policy normalization with a view to bringing inflation back towards target while sustaining employment," Krishna Guha, head of central bank policy strategy for Evercore ISI.                                                                                                                          , "We think he will acknowledge that the Russia Ukraine crisis and its stagflationary impulse from higher energy prices (inflation higher, growth lower) creates additional challenges for policy," Guha added.                                                                                                                                                                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/01/stocks-making-the-biggest-moves-midday-target-kroger-foot-locker-and-more.html </td>
   <td style="text-align:left;"> 2022-03-02 01:55:29 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Target, Kroger, Foot Locker and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                   , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                       , Target – Shares of the retailer jumped 9.9% after the company reported 9% sales growth in the fiscal fourth quarter, despite supply chain pressures, and said it's poised to keep that momentum going. Target also issued revenue guidance with growth in the low to mid- single digits and projected adjusted earnings per share to rise by high single digits in the year ahead., Kroger — Shares of Kroger rose 3.3% after Telsey upgraded the grocery store chain ahead of its earnings report. "We believe we have higher visibility and confidence into Kroger's multiyear omni-channel growth runway," Telsey's Joseph Feldman said.                                                                                                                           , Foot Locker – The athletic retailer saw shares fall 7.6% after Goldman Sachs downgraded the stock to neutral from buy, saying it sees too much near-term pressure on the stock. The downgrade follows Foot Locker's announcement that it will sell fewer Nike products.                                                                                                           , AutoZone – The retail stock dipped 2.5% despite AutoZone beating expectations for earnings and revenues for its fiscal second quarter. The company's same-store sales jumped 13.8% year over year.                                                                                                                                                                                , Workday — Shares of Workday popped 4.9% after beating on the top and bottom lines of its quarterly earnings results. The company also raised guidance for its fiscal year 2023 subscription revenue to be in a range of $5.53 billion to $5.55 billion, reflecting year-over-year growth of 22%.                                                                                  , Lucid Group — Shares of the electric carmaker plunged 13.8% in midday trading after reporting a wider-than-expected loss of 64 cents per share, while analysts expected a loss of 25 cents per share, according to Refinitiv. Revenue came in at $26.4 million, below the forecast $36.7 million.                                                                                 , Zoom Video — Zoom shares fell 7.4% after the video conferencing platform issued a weaker-than-expected first quarter and full-year guidance. The company beat earnings and revenue expectations for the fourth quarter.                                                                                                                                                           , Novavax — Shares of Novavax rose 2.7% midday, then closed up 0.4%. The biotech company reported a miss on the top and bottom line in the fourth quarter, but said it expects revenue between $4 billion and $5 billion in 2022. Novavax is also working on an omicron-specific vaccine.                                                                                           , J.M. Smucker — J.M. Smucker shares fell 6.3% despite the company's better-than-expected earnings report. The company reduced its fiscal-year sales growth guidance and reduced the high end of its fiscal-year earnings guidance.                                                                                                                                                 , Hormel Foods — Shares of Hormel rose 4% after the company beat revenue estimates in its latest quarterly report. Hormel earnings matched Wall Street expectations.                                                                                                                                                                                                                , Rivian — Shares of Rivian sunk 8.4% after Wells Fargo reiterated its equal-weight rating on the stock. The firm said it sees too many "near-term headwinds."                                                                                                                                                                                                                      , Chevron — Chevron shares rose 4% after Bank of America reiterated its buy rating on the stock. The call came after Chevron said it was close to acquiring Renewable Energy Group.                                                                                                                                                                                                 , Wells Fargo, Bank of America — Financial stocks were among the biggest losers Tuesday. Bank of America was down 3.9%, while Wells Fargo eased 5.8%. Falling Treasury yields could potentially take a bite out of bank profits, while the conflict in Eastern Europe and sanctions on Russia have some traders worried about disruption in credit markets.                         , Occidental Petroleum, APA Corp — Energy stocks got a lift as oil prices spiked, with U.S. crude hitting its highest level since June 2014. Occidental Petroleum added 7% and APA Corp rose 4.6%.                                                                                                                                                                                  , Lockheed Martin, Northrop Grumman — Defense stocks gained as investors monitored increasing tension in the Russia-Ukraine conflict. Lockheed Martin rose 5.3% while Northrop Grumman added 3.2%.                                                                                                                                                                                  , — CNBC's Maggie Fitzgerald, Jesse Pound and Samantha Subin contributed reporting.                                                                                                                                                                                                                                                                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 01:39:30 </td>
   <td style="text-align:left;"> Madrid Stocks Close at 1-Year Low </td>
   <td style="text-align:left;"> The Ibex 35 Index sunk 3.4% to close at 8,118 on Tuesday, the lowest level in one year, as violent Russian attacks in Ukraine’s largest cities and harsher sanctions from western states triggered a global equity sell-off. Banks continued to lead the losses after western allies limited Russian entities' ability to transact internationally as key Russian lenders were to be removed from the Swift global system. Banco Sabadell (-6.9%) and Bankinter (-6.3%) were among the banks with steepest losses in Madrid. Utility suppliers also declined, falling form significant gains in the last session, as investors assess the prospects of transitioning the European economy to less dependent on Russian energy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ukraine/current-account </td>
   <td style="text-align:left;"> 2022-03-02 01:35:00 </td>
   <td style="text-align:left;"> Ukraine Current Account Surplus Widens in January </td>
   <td style="text-align:left;"> Ukraine’s current account surplus widened to USD 609 million in January of 2022 from USD 159 million in the corresponding month of the previous year. The services surplus rose to USD 583 million from USD 322 million and the secondary income surplus went up to USD 339 million from USD 333 million. In addition, the primary income account recorded a USD 117 million surplus, switching from a USD 100 million deficit; while the goods deficit advanced to USD 430 million from USD 396 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2022-03-02 01:34:00 </td>
   <td style="text-align:left;"> EU Natural Gas Surges Almost 30% </td>
   <td style="text-align:left;"> EU natural gas prices surged almost 30% on Tuesday to above €125 per megawatt-hour rebounding from a 30% decline last Friday, as energy crises intensified. Concerns grew about supply disruption from Russia, a key exporter of gas and oil after fights in Ukraine intensified with the Russian army closing on Kyiv. Although Russia has said it will keep exporting natural gas, around one-third of Europe’s imports pass through Ukraine, where the conflict could cause damage to vital pipelines and additional sanctions may be imposed banning the purchases of Russian commodities. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-03-02 01:16:00 </td>
   <td style="text-align:left;"> Natural Gas Prices Rise 4% </td>
   <td style="text-align:left;"> US natural gas futures rose more than 4% to almost reach $4.6 per million British thermal units, approaching a three-week peak of $4.94 hit on February 24th, as traders eyed stronger overseas demand as energy crises intensified. Crude oil surged to above $107 per barrel and gas prices in Europe surged more than 25% as concerns grew about supply disruption from key exporter Russia after fights in Ukraine intensified with the Russian army closing on Kyiv. Meanwhile, the latest forecasts pointed to milder weather in March, lowering demand for heating. Also, domestic natural gas inventory levels declined by 129 billion cubic feet last week, less than market forecasts of a 134 bcf draw. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2022-03-02 01:15:00 </td>
   <td style="text-align:left;"> Euro Hits Nearly Two-Year Low </td>
   <td style="text-align:left;"> The euro hit its lowest level since June 2020 against its US counterpart, bottoming around the critical support level at $1.11 as the war in Ukraine clouded the outlook for the economy just as inflation was taking hold in the eurozone. Governments worldwide have imposed an unprecedented array of economic and other sanctions on Russia, targeting its finance, energy and military-industrial sectors. Money market futures dated to the ECB's meetings this year now price in a total of 25 basis points by year-end, from roughly 30 bps on Monday and 40bps late last week. With investors now cutting back their bets for European Central Bank rate hikes this year, it seems to be making it difficult for the euro to attract fresh buying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 01:14:00 </td>
   <td style="text-align:left;"> South African Stocks End at New Record High </td>
   <td style="text-align:left;"> The JSE FTSE All Share index closed 1.3% firmer at a fresh record high of 77,110 on Tuesday, mainly supported by commodity-linked stocks on rising prices of oil and gold. However, coal miner Exxaro was the top performer, rising 8.81% after it flagged an up to 64% increase in annual profits. By contrast, miner Impala Platinum lost 0.8% after reporting a profit drop for the first half of the fiscal year, as it faced safety stoppages, industrial action and power-supply interruptions, and lowered full-year production guidance. Regarding domestic economic data, the Absa report showed South Africa's manufacturing activity expanded for the 7th straight month in February of 2022 and at the strongest pace since March of 2007. Meanwhile, investors continued to assess the Ukraine crisis and sanctions against Russia's economy and wealthy individuals. Russian forces are getting closer to the Ukrainian capital Kyiv after high-level talks failed to produce ceasefire. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 01:01:00 </td>
   <td style="text-align:left;"> Dow Jones Sinks More Than 600 Points </td>
   <td style="text-align:left;"> The selloff on Wall Street accelerated with the Dow Jones tumbling more than 600 points and the S&amp;P 500 and the Nasdaq down more than 1.5% as concerns mounted over the impact of war in Ukraine on the global economy. The situation in Ukraine is becoming more difficult by the hour with Russian troops bombing cities and enclosing the capital city of Kyiv. Falls are the most pronounced in financial stocks which may be the most impacted by sanctions, with Bank of America, JP Morgan, Wells Fargo, Visa and Charles Schwab tumbling more than 4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 01:01:00 </td>
   <td style="text-align:left;"> UK Stocks Extend Losses </td>
   <td style="text-align:left;"> The FTSE 100 fell 1.7% to close at 7,330 on Tuesday, extending losses for a second straight session, dragged down by tumbling Russian-listed mining stocks Polymetal and Evraz following intense sanctions on the country and its economy. At the same time, gambling company Flutter plunged 12.4% after showing an 11% slump in 2021 earnings. Also, energy giant Shell fell 1.1% after the company said it would exit all its Russian operations, including the Sakhalin 2 LNG project, which could lead to billions in impairments. On the opposite side, pharmaceutical companies and mining stocks were among the gainers. AstraZeneca said it agreed to develop a therapy for a rare condition that leads to heart failure in a deal with Swiss Neurimmune valued up to $760M. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/01/russian-backed-investment-fund-tied-to-influential-us-corporate-consulting-firm.html </td>
   <td style="text-align:left;"> 2022-03-02 00:55:33 </td>
   <td style="text-align:left;"> Russian-backed investment fund tied to influential U.S. corporate consulting firm Teneo </td>
   <td style="text-align:left;"> , An investment fund backed by Russian oligarchs sanctioned by the European Union following the invasion of Ukraine has ties to Teneo, an influential corporate-advisory firm based in the United States.                                                                                                                                                                                                                                                                                                    , The public relations and strategy giant was hired in 2020 by LetterOne, a private equity firm based out of Luxembourg that counts sanctioned billionaires Mikhail Fridman, who is a native of Ukraine, and Petr Aven among its cofounders. The contract, which was viewed by CNBC, appears to have paid Teneo more than $3.6 million to line up interviews and consult on media strategy in the U.S.                                                                                                       , LetterOne was founded by Fridman, Aven, Alexei Kuzmichev, Andrei Kosogov and German Khan — all of whom are some of the wealthiest business leaders with interests in Russia. All five founders have been on LetterOne's board, with Fridman as the chairman, according to data from PitchBook reviewed by CNBC. The executives launched the firm in 2013 after establishing Alfa Group, one of the largest conglomerates in Russia.                                                                        , Fridman and Aven have been sanctioned by the EU, and accused of having ties to Russian President Vladimir Putin, claims that were denied in an emailed statement to CNBC. The statement did not answer any of CNBC's questions on LetterOne's work with Teneo or how the investment fund is planning to move ahead now that two of its founders have been sanctioned. Fridman's bank, Alfa Bank, has also been sanctioned by the United States. He's called for an end to the Russian invasion of Ukraine. , After CNBC asked a LetterOne representative on Monday about their business, including their relationship with Teneo, several pages of their website, including the "our people" section, appear to have been wiped as of Tuesday morning. An error message now appears on that section which listed the founders and executives at the firm. The LetterOne board section is still active, but it no longer shows Fridman and Aven as members of the board.                                                 , Joshua Hardie, a spokesman for LetterOne, said Fridman and Aven resigned from the board on Tuesday. CNBC first contacted the private equity firm on Monday.                                                                                                                                                                                                                                                                                                                                                , Though emails to Teneo were not returned, Kathleen Lacey, a company senior managing director who was listed in a document as working the LetterOne account, told CNBC in a brief phone call on Monday that LetterOne was no longer one of her clients and she believed her firm wasn't representing it anymore.                                                                                                                                                                                            , The Department of Justice's FARA Unit, which monitors U.S. lobbying and consulting work for foreign representatives, told CNBC on Tuesday that it believes the contract between Teneo and LetterOne "remains active."                                                                                                                                                                                                                                                                                      , LetterOne has multiple links to Teneo, which was founded by two Democratic consultants who worked for former Presidents Bill Clinton, Barack Obama and former Secretary of State Hillary Clinton. The private equity firm has been involved in almost a dozen deals estimated to be worth over $1 billion, according to PitchBook. Uber, for example, saw a $200 million investment from LetterOne in 2016.                                                                                                , Teneo has since grown into a consulting giant, with past clients including Dow Chemical and Coca-Cola. Foreign clients have included Neom, a company backed the juggernaut Public Investment Fund with the goal of creating a megacity in Saudi Arabia, and a foundation led by an Emirati princess.                                                                                                                                                                                                       , Their listed senior advisors is a who's who of political and business leaders including former Republican House Speaker Paul Ryan, former IBM CEO Ginni Rometty, former Dow Chemical CEO Andrew Liveris and Harvey Pitt, a former chairman of the Securities and Exchange Commission.                                                                                                                                                                                                                      , Doug Band, who was once one of Bill Clinton's closest aides, founded Teneo with Declan Kelly and Paul Keary. Kelly worked as the special envoy to Northern Ireland in the Obama administration and helped Hillary Clinton run for president in 2008. Band and Kelly have since left the firm, with the latter resigning from being Teneo's CEO after reports of him drunk and acting inappropriately at an event organized by the Global Citizen nonprofit. Keary became the CEO after Kelly's resignation., A contract between Teneo and LetterOne reviewed by CNBC shows that the consulting firm was hired in 2020 for a retainer of $150,000 per month to advise the fund on their media strategy. Teneo, according to the contract, was expected to "provide strategic counsel and stakeholder engagement advice to the company and its board members (including, without limitation, scheduling media interviews, assisting with media briefings, coordinating stakeholder engagements and related activities)."  , Under the contract, LetterOne was on track to pay Teneo more than $3.6 million since September 2020. There were at least four Teneo representatives who worked the account, according to other documents filed to the DOJ.                                                                                                                                                                                                                                                                                 , Further documents show that through last year, Teneo took credit for trying to set up interviews for LetterOne leaders with producers and television anchors, including those at CNBC, Bloomberg and Fox Business. A document shows that a Bloomberg representative was contacted almost a dozen times to see whether LetterOne could sponsor one of their Bloomberg Invest events.                                                                                                                        , There are other ties between Teneo and LetterOne.                                                                                                                                                                                                                                                                                                                                                                                                                                                          , LetterOne's nonexecutive chairman is Evan Davies, a British businessman who was once the U.K. minister of state for trade, investment and small business. He's also a senior advisor at Teneo.                                                                                                                                                                                                                                                                                                             , VEON, a telecommunications company operating in Russia and Ukraine is listed on LetterOne's website as one of its active investments. Ursula Burns was chairman of the VEON board for almost three years before stepping down in 2020. She later became the chairwoman of Teneo.                                                                                                                                                                                                                           , Meanwhile, VEON announced on Tuesday that Mikhail Fridman resigned from their board.                                                                                                                                                                                                                                                                                                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                     , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                           , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                           , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                         , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/01/europe/volodymyr-zelensky-ukraine-cnn-interview-intl/index.html </td>
   <td style="text-align:left;"> 2022-03-02 00:51:39 </td>
   <td style="text-align:left;"> Zelensky urges Biden to send strong message on Russia and says: 'I'm not iconic. Ukraine is iconic' - CNN </td>
   <td style="text-align:left;"> Kyiv, Ukraine (CNN)Ukrainian President Volodymyr Zelensky has urged US counterpart Joe Biden to deliver a strong and "useful" message about the Russian invasion at his State of the Union speech on Tuesday, in an exclusive interview with CNN and Reuters from the bunker in Kyiv in which he is leading his military's response.                                   , In the rare interview on Tuesday afternoon, Zelensky said that as long as Moscow's attacks on Ukrainian cities continued, little progress could be made in talks between the two nations.                                                                                                                                                                              , "You have to speak first of all. Everybody has to stop fighting and to go [back] to that point from where it began five, six days ago," Zelensky said. "It's important to stop bombing people and then we can move on and sit at the negotiation table."                                                                                                               , Asked if he felt Ukraine was wasting its time by talking with Russia, he said: "We'll see." Officials from the two countries met for the first time on Monday since Russia's invasion began last week.                                                                                                                                                                 , Ahead of Biden's speech in Congress on Tuesday, Zelensky urged the President to impress upon Americans the urgency and implications of Russia's invasion.                                                                                                                                                                                                              , "He is one of the leaders of the world and it is very important that the people of the United States understand (that) despite the fact that the war is in Ukraine ... it is [a] war for the values of democracy, freedom," Zelensky said.                                                                                                                             , Zelensky reiterated calls for the US and NATO to establish a no-fly zone over Ukraine or put boots on the ground. "I've already addressed and (spoken) to some Western leaders with this request, because I do believe that leaders do have to support democratic countries and they have to help them."                                                               , "When we talk about no-fly (zones), we're looking back into history ... and that doesn't mean that we need to draw another country into the war. And, frankly, you know, everyone is drawn into the war now."                                                                                                                                                          , "I've spoken to Biden many times," Zelensky said. "And I've told them many times that Ukraine will resist and fight stronger than anyone else but on our own against Russia we won't manage it."                                                                                                                                                                       , "That's why if somebody wants to help us, everybody has to act swiftly," Zelensky added. "This is the moment."                                                                                                                                                                                                                                                         , The US and NATO allies have aided Ukraine by sharing arms, military equipment and intelligence, while also imposing dramatic sanctions on Russia. But the alliance has thus far made clear it has no plans to send soldiers into Ukraine, which is not a NATO member.                                                                                                  , Zelensky also predicted troubles in NATO member states if Russia seizes control of his country. "If Ukraine fails, then all these troops will be at your borders, Poland, Lithuania ... and you'll be facing greater issues. There'll be other provocations there," he said.                                                                                           , 'The world can't lose Ukraine'                                                                                                                                                                                                                                                                                                                                         , As CNN and Reuters met with Zelensky inside his Kyiv bunker, the capital -- along with cities across Ukraine -- braced for a renewed and intensified assault by Russian forces.                                                                                                                                                                                        , Rockets were fired near a TV tower on Tuesday afternoon, hours after Russia warned of "high-precision" strikes on other facilities linked to Ukrainian security agencies. The rocket attack took out broadcasting hardware, raising fears that Russia is attempting to knock out the city's communications infrastructure, Ukraine's Ministry of Internal Affairs said., Zelensky told CNN on Tuesday that Russia was indiscriminately attacking Ukrainian citizens and historical landmarks.                                                                                                                                                                                                                                                   , "As you can see, no one is being very careful about the targets. We see the children are being killed ... We are defending our right for life," he said, adding that Moscow is "launching their missiles against the ancient old Kyiv, the heart of Kyiv."                                                                                                             , He spoke triumphantly of Ukraine's resistance, and said of Russian soldiers: "They have no idea what they [are] doing.  They don't know our streets. They don't know this people. They don't understand our philosophy. Our mentality, our aspirations, what kind of  people here they have, they know nothing.                                                        , "They're just sent to kill and die," Zelensky said.                                                                                                                                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                                        , As the rockets hit Kyiv on Tuesday, a 40-mile Russian convoy of tanks, armored vehicles and towed artillery was headed toward the Ukrainian capital, according to satellite images from Maxar Technologies, while the military beefed up its attacks on other key cities.                                                                                              , Attacks have also hit Ukraine's second city, Kharkiv. More than 20 people were injured, including a child, in an explosion at a government building there, Ukraine's State Emergency Service said in a Telegram post Tuesday.                                                                                                                                          , Russia's actions on Tuesday mark a far less restrained bombing campaign, raising concerns that more civilians could be hit in strikes. The UN says that at least 102 civilians have been killed across the country and 304 injured, though those figures are likely to underestimate the true toll.                                                                    , Zelensky has drawn global praise for his response to the invasion, having refused offers to evacuate and instead delivering frequent messages to Ukrainians as Kyiv comes under Russian assault.                                                                                                                                                                       , Earlier on Tuesday he received a standing ovation for an emotional address to the European Parliament via video link, telling delegates: "We are fighting for our life."                                                                                                                                                                                               , Asked by CNN about his transformation from comic actor to world-famous wartime leader, Zelensky responded: "It's very serious, it's not a movie ... I'm not iconic, I think Ukraine is iconic."                                                                                                                                                                        , "Ukraine is the heart of Europe, and now I think Europe sees Ukraine is something special for this world," he added. "That's why [the] world can't lose this something special."                                                                                                                                                                                       , The Ukrainian leader appeared tired and stressed but was friendly with crews from CNN and Reuters. He said he hadn't seen his family for three days; asked what his typical days are like, he said: "Work and sleep."                                                                                                                                                  , Matthew Chance reported from Kyiv; Rob Picheta wrote from London. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/01/business/economy/ukraine-russia-supply-chains.html </td>
   <td style="text-align:left;"> 2022-03-02 00:49:00 </td>
   <td style="text-align:left;"> Ukrainian Invasion Adds to Chaos for Global Supply Chains - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Russia’s military incursion is severing key supply chains and setting off a scramble among global companies to comply with new sanctions.                                                                                                                                                                                                                                                                                                                    , By Ana Swanson                                                                                                                                                                                                                                                                                                                                                                                                                                               , WASHINGTON — The Russian invasion of Ukraine has rattled global supply chains that are still in disarray from the pandemic, adding to surging costs, prolonged deliveries and other challenges for companies trying to move goods around the world.                                                                                                                                                                                                          , The clash in Ukraine, a large country at the nexus of Europe and Asia, has caused some flights to be canceled or rerouted, putting pressure on cargo capacity and raising concerns about further supply chain disruptions. It is putting at risk global supplies of products like platinum, aluminum, sunflower oil and steel, and shuttering factories in Europe, Ukraine and Russia. And it has sent energy prices soaring, further raising shipping costs., The conflict is also setting off a scramble among global companies as they cut off trade with Russia to comply with the most far-reaching sanctions imposed on a major economic power since the end of the Cold War.                                                                                                                                                                                                                                         , The new challenges follow more than two years of disruptions, delays and higher prices for beleaguered companies that use global supply chains to move products around the world. And while the economic implications of the war and sweeping sanctions on Russia are not yet clear, many industries are bracing for a bad situation to get worse.                                                                                                           , “Global supply chains are already hurting and stressed because of the pandemic,” said Laura Rabinowitz, a trade lawyer at Greenberg Traurig. She said the effects would vary for specific industries and depend on the length of the invasion, but the impacts would be magnified because of an already-vulnerable supply chain.                                                                                                                             , “There’s still tremendous port congestion in the United States. Freight costs are very high. Factory closures in Asia are still an issue,” she said.                                                                                                                                                                                                                                                                                                         , Companies with complex global supply chains, like automakers, are already feeling the effects. Volkswagen, which had already announced it was suspending production at its main factory for electric cars, said Tuesday that it would also be forced to shut down production at several other factories, including its main factory in Wolfsburg, Germany, in coming weeks because of parts shortages.                                                       , Automakers could see shortages of other key materials. Ukraine and Russia are both substantial sources for palladium and platinum, used in catalytic converters, as well as aluminum, steel and chrome.                                                                                                                                                                                                                                                      , Semiconductor manufacturers are warily eyeing global stocks of neon, xenon and palladium, necessary to manufacture their products. Makers of potato chips and cosmetics could face shortages of sunflower oil, the bulk of which is produced in Russia and Ukraine.                                                                                                                                                                                          , And if the conflict is prolonged, it could threaten the summer wheat harvest, which flows into bread, pasta and packaged food for vast numbers of people, especially in Europe, North Africa and the Middle East. Food prices have already skyrocketed because of disruptions in the global supply chain, increasing the risk of social unrest in poorer countries.                                                                                          , On Tuesday, the global shipping giant Maersk announced that it would temporarily suspend all shipments to and from Russia by ocean, air and rail, with the exception of food and medicine. Ocean Network Express, Hapag-Lloyd and MSC, the world’s other major ocean carriers, have announced similar suspensions.                                                                                                                                           , “The war just makes the worldwide situation for commodities more dire,” said Christopher F. Graham, a partner at White and Williams.                                                                                                                                                                                                                                                                                                                         , Jennifer McKeown, the head of global economics service at Capital Economics, said the global economy appeared relatively insulated from the conflict. But she said shortages of materials like palladium and xenon, used in semiconductor and auto production, could add to current difficulties for those industries. Semiconductor shortages have halted production at car plants and other facilities, fueling price increases and weighing on sales.     , “That could add to the shortages that we’re already seeing, exacerbate those shortages, and end up causing further damage to global growth,” she said.                                                                                                                                                                                                                                                                                                       , International companies are also trying to comply with sweeping financial sanctions and export controls imposed by Europe, the United States and a number of other countries that have clamped down on flows of goods and money in and out of Russia.                                                                                                                                                                                                        , In just a few days, Western governments moved to exclude certain Russian banks from using the SWIFT messaging system, limit the Russian central bank’s ability to prop up the ruble, cut off shipments of high-tech goods and freeze the global assets of Russian oligarchs.                                                                                                                                                                                 , The Biden administration said the technology restrictions alone would stop about a fifth of Russian imports. But the impact on trade from the financial curbs is likely to be even larger, cutting off Russia’s imports from and exports to nearly all of its major trading partners, said Eswar Prasad, a professor of trade policy at Cornell University.                                                                                                  , “Even when trade flows may take place directly between Russia and its trading partners, the reality is that payments often have to go through a Western-dominated financial system, and usually have to go through a Western currency,” he said.                                                                                                                                                                                                             , In a statement on Saturday, the president of the European Commission, Ursula von der Leyen, said that Europe and its allies were “resolved to continue imposing massive costs on Russia” and that disconnecting Russian banks from SWIFT would also halt Russian trade.                                                                                                                                                                                      , “Cutting banks off will stop them from conducting most of their financial transactions worldwide and effectively block Russian exports and imports,” she said.                                                                                                                                                                                                                                                                                               , The economic consequences of these moves are not yet entirely clear. Russia accounts for less than 2 percent of global domestic product, so the implications for other countries may be somewhat limited.                                                                                                                                                                                                                                                    , But for the Russian government and the economy, both of which are heavily dependent on trade to generate revenue, the impact could be catastrophic. Capitol Economics has estimated Russian gross domestic product could contract by 5 percent this year, a change that in isolation would knock just 0.2 percentage points off global growth.                                                                                                               , Caroline Bain, chief commodities economist at Capitol Economics, said financial sanctions were halting the trade of metals and agricultural commodities, likely exacerbating strains in global supply chains.                                                                                                                                                                                                                                                , Credit Suisse and Société Generale have suspended financing for commodity trading with Russia, as has the Industrial and Commercial Bank of China, she said.                                                                                                                                                                                                                                                                                                 , A rising concern. Russia’s attack on Ukraine could cause dizzying spikes in prices for energy and food and could spook investors. The economic damage from supply disruptions and economic sanctions would be severe in some countries and industries and unnoticed in others.                                                                                                                                                                               , The cost of energy. Oil prices already are the highest since 2014, and they have risen as the conflict has escalated. Russia is the third-largest producer of oil, providing roughly one of every 10 barrels the global economy consumes.                                                                                                                                                                                                                    , Gas supplies. Europe gets nearly 40 percent of its natural gas from Russia, and it is likely to be walloped with higher heating bills. Natural gas reserves are running low, and European leaders have accused Russia’s president, Vladimir V. Putin, of reducing supplies to gain a political edge.                                                                                                                                                         , Food prices. Russia is the world’s largest supplier of wheat and, together with Ukraine, accounts for nearly a quarter of total global exports. In countries like Egypt and Turkey, that flow of grain makes up more than 70 percent of wheat imports.                                                                                                                                                                                                       , Shortages of essential metals. The price of palladium, used in automotive exhaust systems and mobile phones, has been soaring amid fears that Russia, the world’s largest exporter of the metal, could be cut off from global markets. The price of nickel, another key Russian export, has also been rising.                                                                                                                                                , Financial turmoil. Global banks are bracing for the effects of sanctions designed to restrict Russia’s access to foreign capital and limit its ability to process payments in dollars, euros and other currencies crucial for trade. Banks are also on alert for retaliatory cyberattacks by Russia.                                                                                                                                                         , “There could be quite a bit of self-sanctioning going on. Obviously people are quite nervous about taking up contracts on Russian commodities when everything is so uncertain,” Ms. Bain said. While governments haven’t released many specifics on what kind of trades will be allowed, she added, “our understanding is that all trade apart from energy is being targeted.”                                                                               , The conflict may also ripple through some industries by disrupting the flight networks that companies use to deliver goods globally.                                                                                                                                                                                                                                                                                                                         , Shipping ports around the Black Sea have closed, halting dozens of cargo vessels. But the more immediate effects are likely to be felt in air shipments between Asia and Europe, which now have to divert around Russian airspace, said Eytan Buchman, the chief marketing officer of the Freightos Group, a digital freight booking platform.                                                                                                               , Western Europe and Russia have imposed reciprocal flight bans, bringing travel between the two regions to a halt. On Monday, Jen Psaki, the White House press secretary, said a U.S. ban on Russian flights was “not off the table.”                                                                                                                                                                                                                         , As shipping planes divert around Russian airspace, they will take longer and spend more on fuel, and they may opt for smaller and lighter loads as a result, Mr. Buchman said. “Especially on the air cargo side, it will have a big impact.”                                                                                                                                                                                                                , Already, flights along major trade routes have slowed somewhat, according to an analysis by Flexport, a logistics company. Flights between New Delhi and London, for example, were about 8 percent longer on average between Wednesday and Sunday than similar flights three months prior, data from Flightradar24, an aviation tracking firm, showed.                                                                                                       , Longer trip times could create cascading delays and backlogs for industries that depend on airfreight, including electronics, semiconductors and fast fashion.                                                                                                                                                                                                                                                                                               , So far, though, the effects of the flight bans have been limited. For passenger airlines, there were already relatively few tourists traveling between Europe and Asia, where many countries have strict coronavirus policies.                                                                                                                                                                                                                               , Cargo carriers are nimble, said John Grant, a senior consultant with OAG, an aviation advisory and data firm. “They can move with demand, so I suspect there will be limited immediate impact.”                                                                                                                                                                                                                                                              , Niraj Chokshi, Jack Ewing and Jeanna Smialek contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                          , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 00:49:00 </td>
   <td style="text-align:left;"> European Stocks Tumble, DAX at 1-Year Low </td>
   <td style="text-align:left;"> European equity markets tumbled on Tuesday, with Germany’s DAX down 3.5% to a 1-year low below the 14,000 level, as the Russia-Ukraine crisis deepened on the sixth day of the invasion. In the latest developments, Russian troops are enclosing the capital city of Kyiv, after Russia's defense minister said Moscow will continue its attack until its goals are met. Across sectors, travel and leisure shares slumped 7% dragged down by airlines; and banks lost 6.8% as traders scaled down their expectations of monetary tightening from the European Central Bank and the yield of Germany's Bund went back to negative territory. On the other hand, defense stocks extended gains from the previous session, led by German defense company Rheinmetall after the German government’s vow to boost defense spending. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 00:48:00 </td>
   <td style="text-align:left;"> Italian Stocks Plunge over 4% on Tuesday </td>
   <td style="text-align:left;"> The FTSE MIB Index plunged 4.1% to close at 24,636 on Tuesday, a seven-month low, as violent Russian attacks in Ukraine’s main cities furthered concerns of the war’s impact in the global economy amid harsher sanctions by western states. Banks continued to lead the losses, driven by Intesa Sanpaolo (-7.7%) and UniCredit (-7%), as both lenders have significant exposure to Russian capital. Utilities also booked losses, after significant gains in the previous session, amid high volatility in the European utility market as countries pledge to move away from Russian dependency. Also, Telecom Italia fell 9% as the firm will set out an alternative to KKR's EUR 10.8 billion takeover bid ahead of its bleak corporate earnings announcement. On the economic data front, Italy’s consumer inflation for February accelerated to a 26-year high of 5.7%, while the country’s economy expanded 6.6% during the full 2021 and the country’s government posted a budget deficit of 7.2% of the GDP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Sink Nearly 4% to 7-Month Low </td>
   <td style="text-align:left;"> The CAC 40 Index sank 3.9% to close at 6,396 on Tuesday, the lowest since July of 2021 as violent Russian attacks in Ukraine’s largest cities and harsher sanctions from western states triggered a global equity sell-off. Engie (-13.9%) and TotalEnergies (-2.7%) booked significant losses after French Economic Minister Bruno Le Maire said he would hold talks with both firms regarding their ties to Russia, as France attempts to move away from Russian energy sources amid the “economic war” declared in the French Parliament. At the same time, Societe Generale (-9.4%) continues to decline from Russian exposure due to its subsidiary Rosbank. The lender has lost over 31% on the month due to Russia’s invasion of Ukraine. On the earnings front, Atos fell over 20% after posting a loss of EUR 2.96 billion for 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 00:45:37 </td>
   <td style="text-align:left;"> The FTSE 100 Index decreased 1.44% </td>
   <td style="text-align:left;"> United Kingdom Stock Market decreased 107 points. Losses were driven by Evraz (-27.74%), Polymetal International (-26.54%) and Flutter Entertainment (-11.92%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bonds </td>
   <td style="text-align:left;"> 2022-03-02 00:44:00 </td>
   <td style="text-align:left;"> Government Bond Rally Intensifies </td>
   <td style="text-align:left;"> Bond yields in US and Europe rallied on Tuesday as investors rushed into safe-haven assets after the invasion of Ukraine by Russian forces continued, and Western nations ramped up new sanctions on Moscow in response. In the latest developments, Russia's defence ministry warned residents in Kyiv to leave their homes as it plans to strike targets in the Ukrainian capital. The US yield on the 10-year note, which sets the tone for corporate and household borrowing costs worldwide, bottomed around 1.71%, a level not seen since early January. Germany's 10-year Bund yield, the benchmark for the region, tumbled below 0%. Italy's 10-year spread, an influential gauge of risk in eurozone bond markets owing to the vast scale of Italian debt, narrowed to more than 1.404%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/stock-market </td>
   <td style="text-align:left;"> 2022-03-02 00:34:24 </td>
   <td style="text-align:left;"> Euro Stoxx 50 Hits 51-week Low </td>
   <td style="text-align:left;"> EU50 decreased to a 51-week low of 3765 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-03-02 00:29:21 </td>
   <td style="text-align:left;"> DXY Strengthens Above 97.3 </td>
   <td style="text-align:left;"> The dollar index rose as much as 0.7% to cross 97.3 on Tuesday, closing in on the strongest level since July 2020 as market participants rush to safety as the Russian military offensive moves closer to Kyiv. Investors worry that inflationary risks and supply disruptions resulting from the conflict could dampen global growth, clouding the outlook for monetary policy. Meanwhile, currency traders look ahead to Federal Reserve chair Jerome Powell's appearance in Congress on Wednesday for fresh clues on the timing and magnitude of interest rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/03/01/tv-tower-hit-strikes-russia-ukraine-ward-newsroom-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-02 00:29:11 </td>
   <td style="text-align:left;"> Watch: Video shows Russian military strike on TV tower near Kyiv - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-02 00:27:00 </td>
   <td style="text-align:left;"> Swiss 10Y Bond Yield at 4-Week Low </td>
   <td style="text-align:left;"> The yield on the Swiss 10-year government bond was below 0.1% in the start of March, the lowest in four weeks, as investors fled to safe-haven assets amid intensified Russian attacks on Ukrainian cities and sanctions from Switzerland and western allies. Elsewhere, the Swiss National Bank remains committed to its ultra-loose monetary policy, as the latest labor data indicated that unemployment did not increase, while inflation continues to moderate. In its latest survey economic survey of Switzerland, the OECD noted that the Swiss economy proved to be very resilient to the ongoing health crisis and should be in no rush to tighten monetary policy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-02 00:25:00 </td>
   <td style="text-align:left;"> Canada 10Y Bond Yield Hits 6-week Low </td>
   <td style="text-align:left;"> Canada's 10-year government bond yield tumbled to a six-week low of 1.726%, as heightened tensions between Russia and Ukraine reignited a rush to safer investments such as government bonds. Still, the latest GDP data is expected to show that the economy rebounded strongly in the last quarter of 2021, showing resilience in the face of the Omicron variant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/chile/leading-economic-index </td>
   <td style="text-align:left;"> 2022-03-02 00:23:50 </td>
   <td style="text-align:left;"> Chile Economic Activity Misses Forecasts in January </td>
   <td style="text-align:left;"> The Leading Economic Index Chile increased 9 percent in January of 2022 over the same month in the previous year, missing market expectations of an 11.3 percent jump and slowing from a 10.1 percent rise in December of 2021. It was the slowest growth rate since March of last year amid stronger headwinds from the mining sector (-6.0 percent). Still, services activities saw double-digit growth (17.0 percent) and growth in the trade sector remained robust (8.4 percent). To a lesser extent, upward pressure also came from industrial activities (2.4 percent). On a seasonally adjusted basis, economic activity contracted by 1.0 percent over the prior month in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/steel </td>
   <td style="text-align:left;"> 2022-03-02 00:22:57 </td>
   <td style="text-align:left;"> Steel Bounces Off One-Month Low </td>
   <td style="text-align:left;"> Steel Rebar futures have climbed above CNY 4,800 per tonne in early March, bouncing off an over one-month low of CNY 4,600 after the Western allies ramping up more sanctions on Russia over its invasion of Ukraine raised worries of supply disruptions. European Union imposed fresh sanctions against two Russian metals magnates, Alisher Usmanov, a majority shareholder in steelmaking and mining group Metalloinvest, and Severstal chairman Alexei Mordasho, to prevent a full-scale invasion of Kyiv. On top of that, February and March constitute the traditional peak season for the steel industry in China, with demand likely to improve, supported by China’s government infrastructure investment plans. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/currency </td>
   <td style="text-align:left;"> 2022-03-02 00:17:14 </td>
   <td style="text-align:left;"> Sterling Approaches 2-Month Low </td>
   <td style="text-align:left;"> The British pound depreciated to $1.33, nearing its lowest level in ten weeks as investors sought shelter in safe-haven currencies amid escalating conflict in Ukraine. Russian troops are approaching the capital Kyiv on the sixth day of Russia’s invasion of its neighbor. Currency traders are trying to assess how the escalation of tensions and its economic impact might alter the Bank of England’s rate hike path in the near term, with money markets currently pricing in a 25 basis point rate increase from the BoE in March. Elsewhere, energy company BP, the biggest foreign investor in Russia, said it was abandoning its stake in the state oil company Rosneft. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-03-02 00:09:00 </td>
   <td style="text-align:left;"> Brent Crude Soars by Almost 10% to Above $106 </td>
   <td style="text-align:left;"> Brent crude futures rose soared almost 10% to above $106 a barrel on Tuesday, a fresh high since 2014 as concerns grew about supply disruption from key exporter Russia after fights in Ukraine intensified with the Russian army closing on Kyiv. The traders are becoming increasingly reluctant to buy Russian oil, and are facing payment and delivery difficulties. Meanwhile, a possible release of between 60 million and 70 million barrels of reserves being considered by the US and others failed to calm the energy market. Elsewhere, OPEC+ will meet on Wednesday to discuss output policy, where it is expected to stick to its plan of moderate supply increases despite the market turmoil brought by the invasion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/times-square-billboard-biden-russian-oil </td>
   <td style="text-align:left;"> 2022-03-02 00:08:30 </td>
   <td style="text-align:left;"> Times Square billboard urges Biden to reject Russian oil amid war with Ukraine </td>
   <td style="text-align:left;"> FOX Business host Stuart Varney argues Biden 'has an ideal opportunity to pile on the pressure' as Russian invasion continues.                                                                                                                                                                                                                                                                                                                 , FIRST ON FOX: A conservative nonprofit on Tuesday announced a new billboard ad in New York City's Times Square, urging President Biden to reject oil from Russia amid the country's invasion in Ukraine.                                                                                                                                                                                                                                       , "Hey Vlad. Screw You!" the billboard states. "Nyet to Russian Oil. Time for American oil. Drill more, pay less. C’mon Joe. This ain’t hard."                                                                                                                                                                                                                                                                                                   , Job Creators Network Times Square ad (JCN)                                                                                                                                                                                                                                                                                                                                                                                                     , Biden has received criticism for his decisions to cancel construction of the Keystone XL pipeline, which would have delivered oil from Canada into the United States, and for his later decision to waive sanctions of Russia's Nord Stream 2 pipeline, which would deliver gas from Russia to Germany.                                                                                                                                        , BIDEN ANNOUNCES SANCTIONS AGAINST NORD STREAM 2 OWNER, REVERSING 2021 DECISION                                                                                                                                                                                                                                                                                                                                                                 , Biden announced new sanctions against the pipeline's owners last week amid the Ukraine crisis.                                                                                                                                                                                                                                                                                                                                                 , E.ON, Europe's largest operator of energy networks, rejected demands to shut down the Nord Stream 1 gas pipeline as part of sanctions against Russia for invading Ukraine, the company told Rheinische Post newspaper on Monday. (AP Photo/Dmitry Lovetsky (AP Newsroom)                                                                                                                                                                       , The ad comes from the Job Creators Network (JCN), a nonprofit organized by Home Depot co-founder and billionaire Bernard Marcus, that describes itself as the "voice of Main Street," arguing that government red tape gets "in the way of the economic freedom that helped make this country prosperous."                                                                                                                                     , US ENERGY DEPENDENCE THREATENS NATIONAL SECURITY, EXPERTS WARN, AS GOP CALLS ON BIDEN TO REOPEN KEYSTONE XL                                                                                                                                                                                                                                                                                                                                    , Many Republicans have argued that Biden's decisions have made the U.S. more dependent on foreign oil, which has played a role in higher prices at the gas pump and in the grocery store.                                                                                                                                                                                                                                                       , Alfredo Ortiz, JCN president and CEO, told FOX Business that the billboard is "part of an ongoing [seven]-figure campaign to call out Joe Biden for his failed policies and leadership."                                                                                                                                                                                                                                                       , RUSSIAN OLIGARCHS LOSE $32B AS UKRAINE CRISIS ESCALATES                                                                                                                                                                                                                                                                                                                                                                                        , "[W]ith each drop of oil, we buy from the Russians, we are helping to finance Putin’s war on the Ukraine, and his march to crush freedom and democracy in Europe," Ortiz said in a statement. "We must declare the radical left's ‘Green New Deal’ thinking dead here in the U.S. once and for all. Brent crude oil prices have gone from $20 per barrel in April 2020, to just shy of $100 per barrel, two years later – a fivefold increase.", A depot used to store pipes for Transcanada Corp's planned Keystone XL oil pipeline in Gascoyne, North Dakota, Jan. 25, 2017. (Reuters/Terray Sylvester)                                                                                                                                                                                                                                                                                       , He added that rising gas prices have "created havoc on the U.S. economy leading to the highest inflation numbers we have seen in 40 years," hurting average Americans and "30 million small business owners that have had to endure ineffective lockdowns and mandates, labor shortages and supply chain issues."                                                                                                                              ,  GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                   , "In order to start reversing the damage done, we urge Biden to reverse course on his socialist energy policies that have put us in this mess we are facing today," Ortiz said. "…Produce more, pay less." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-02 00:03:00 </td>
   <td style="text-align:left;"> Crude Oil Surges 10% to Above $104 </td>
   <td style="text-align:left;"> WTI crude futures surged more than 10% to above $105 per barrel on Tuesday, a fresh high since 2014 as concerns grew about supply disruption from key exporter Russia after fights in Ukraine intensified with the Russian army closing on Kyiv. The traders are becoming increasingly reluctant to buy Russian oil, and are facing payment and delivery difficulties. Meanwhile, a possible release of between 60 million and 70 million barrels of reserves being considered by the US and others failed to calm the energy market. Meanwhile, OPEC+ will meet on Wednesday to discuss output policy, where it is expected to stick to its plan of moderate supply increases despite the market turmoil brought by the invasion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/01/taking-a-pay-cut-heres-how-to-revise-your-budget-for-a-lower-salary-.html </td>
   <td style="text-align:left;"> 2022-03-02 00:02:53 </td>
   <td style="text-align:left;"> More than half of Americans who switched jobs in 2021 took a pay cut. How to budget for a lower salary </td>
   <td style="text-align:left;"> , About 47 million workers left their jobs in 2021 amid the Great Resignation.                                                                                                                                                                                                                                        , Many of them did so for less pay.                                                                                                                                                                                                                                                                                   , Last year, 53% of workers who left their jobs said they made less money in their new roles, according to a January online survey of 1,000 adults by Real Estate Witch.                                                                                                                                              , The average pay cut was around $8,000 per year, according to the survey, but some workers indicated they would be willing to take an even bigger reduction. What's more, those who quit in 2021 but have yet to find another job said they would take an average $23,000 pay cut, the survey found.                 , The catalyst for taking that lower-paying job? Overall satisfaction and work/life balance. More than 60% of those surveyed said they were happy in their new roles, and those who said they were very satisfied compared to their previous position jumped nearly 50%.                                              , An earlier survey of workers from Paro, which provides accounting and finance solutions for businesses, focused on workers who do mental tasks for a living — such as programmers, pharmacists and lawyers. The survey found the group also prioritized their work/life balance over making more money.             , "The pandemic and experiences they have had have shifted their values," said Anita Samojednik, CEO of Paro. "Right now, the salary is just not enough."                                                                                                                                                             , To be sure, many people who switched jobs have seen increases in take-home pay. A survey from The Conference Board found that about one-third of workers who left jobs during the pandemic are making 30% more in new roles. However, about 27% who switched jobs said pay was the same or less in their new job.   , Of course, taking a pay cut will directly affect your finances and may not be advisable right away, according to Tania Brown, an Atlanta-based certified financial planner and founder of FinanciallyConfidentMom.com.                                                                                              , If you're considering taking a job where you will make less money, there are a few things you need to consider before you do so, she said.                                                                                                                                                                          , First, ask yourself why you want to leave your current job, she said. Are you burned out? Will a different job or career be more fulfilling? Are you planning to move?                                                                                                                                              , Contemplating the answers to these questions will help ensure that you don't make a rash decision you'll later regret, said Brown.                                                                                                                                                                                  , "Emotions have no logic, and you're trying to make a math decision based on emotion," Brown said. "It's just not going to turn out."                                                                                                                                                                                , More from Invest in You:Want to buy a new home? How to set yourself up for successWhat to know before filing business taxes for the first time66% of employers plan to address pay equity this year, survey finds                                                                                                   , Additionally, if you're only a few months from paying off debts or hitting a similar financial goal, you may want to hold off.                                                                                                                                                                                      , Plus, you may realize you don't want to leave your job, but instead would like more flexibility or a change in your role. If that is the case, now is a great time to ask for a different schedule, to take on different responsibilities or to try to introduce other flexibilities into your job, Samojednik said., She said she's seen many people dip their toes into freelancing in addition to a full-time job to test the waters of a new gig or becoming their own boss.                                                                                                                                                          , If you discover that switching jobs is truly what you want, then you have some important math to do, Brown said.                                                                                                                                                                                                    , That includes doing a deep dive into your current budget needs and financial goals and seeing if you can achieve your objectives on a smaller income.                                                                                                                                                               , Brown suggests you should over a trial period of a few months, say, try to see if you can meet your goals on  smaller take-home pay. That test run could help you decide if a pay cut is right for you.                                                                                                             , You should also think about how making less will affect your long-term goals, Brown said. If you're saving up for a house or plan on having a baby, how will your new income change the timelines on those milestones? If it will take longer, is it worth it for you to wait?                                      , If you're part of a family, you should also consult the other members in your household before making your move. That means talking with your spouse and children about what changes would take place, such as fewer trips or less money for extra activities — and deciding if it works for everyone.              , "This has to be a family decision because your decision is impacting everyone in the household," said Brown.                                                                                                                                                                                                        , SIGN UP: Money 101 is an 8-week learning course to financial freedom, delivered weekly to your inbox. For the Spanish version Dinero 101, click here.                                                                                                                                                               , CHECK OUT: The 'old convention' for saving in retirement won't work anymore, expert says: Here's how to shift your strategy with Acorns+CNBC                                                                                                                                                                        , Disclosure: NBCUniversal and Comcast Ventures are investors in Acorns.                                                                                                                                                                                                                                              , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                              , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                              , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                    , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                    , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                  , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/01/business/ukraine-russia-markets.html </td>
   <td style="text-align:left;"> 2022-03-01 23:59:41 </td>
   <td style="text-align:left;"> War in Ukraine Has Investors Thinking About a Second Cold War - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Military conflicts have not been a major factor in market movements for decades. But Russia’s invasion of Ukraine has put global relations back on investors’ minds.                                                                                                                                                                                                                                                                                                                                                                                                                     , By Lananh Nguyen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Since the fall of the Soviet Union, investors have enjoyed decades of global economic stability in which military conflicts and foreign diplomacy played a diminished role in the movements of markets.                                                                                                                                                                                                                                                                                                                                                                                  , But Russia’s invasion of Ukraine is the most overt sign of a recent change in that dynamic as increased jostling among powerful nations will have sweeping consequences for investors.                                                                                                                                                                                                                                                                                                                                                                                                   , The largest military conflict in Europe since World War II — combined with simmering tensions between the United States and China — has investors watching shifts in international power dynamics more closely than they have in a long time.                                                                                                                                                                                                                                                                                                                                            , “There has been more global geopolitical tension now for the last several years — frictions between China and the rest of the world, China and the U.S. in particular, are not going away,” said Daniel J. Ivascyn, the chief investment officer at PIMCO, a fund manager that oversees $2.2 trillion in assets. “This Russia situation further complicates some of these broad global relationships, and it absolutely is an increased topic of conversation with our investors.”                                                                                                       , Financial markets have long been sensitive to geopolitical events — elections, supply disruptions and trade tensions — that can move prices. And in just a few days, the invasion of Ukraine has prompted a series of economic maneuvers that can quickly transform the way countries raise money, where they buy raw materials and with whom they do business.                                                                                                                                                                                                                          , The United States and its European allies said they would freeze any Russian Central Bank assets held by U.S. financial institutions, making it harder for the central bank to support the ruble. Fresh sanctions have essentially barred some Russian banks from international transactions. The British oil giant BP said it would “exit” its almost 20 percent stake in Rosneft, the Russian state-controlled oil company, which was valued at $14 billion last year. And Norway’s sovereign wealth fund, the world’s largest, said it would divest itself of its Russian investments., These and other moves — along with Russia’s status as the world’s third-largest oil producer, behind the United States and Saudi Arabia — have shaken up markets around the world. Commodities traders are figuring out how to reroute the global flow of oil, natural gas, metals and grains. And stock traders who already faced uncertainty as governments and central banks grappled with the fallout from the pandemic now must deal with an armed conflict that could hamper any business that relies on those materials.                                                          , On Tuesday, the S&amp;P 500 fell 1.6 percent, the latest in a series of rapid swings and a drop to start March after two consecutive down months. Oil prices rose sharply, with Brent crude trading at more than $106 a barrel, as more than two dozen countries announced plans to release emergency reserves.                                                                                                                                                                                                                                                                              , Jason Schenker, president of Prestige Economics, a forecaster in Austin, Texas, described the revival of tensions between Western nations and Russia as a second Cold War.                                                                                                                                                                                                                                                                                                                                                                                                               , “There’s this competition for global influence and global power, but now the stakes have been raised,” Mr. Schenker said. “We might be in for a protracted battle of sanctions and soft-power diplomacy. And we could see cascading risks of further military action.”                                                                                                                                                                                                                                                                                                                   , That risk was clear on Tuesday when former Prime Minister Dmitri Medvedev of Russia warned that economic wars “quite often turned into real ones,” prompting the French finance minister, Bruno Le Maire, to backpedal from an earlier statement that Europe was ready for “total economic and financial war against Russia.” Mr. Le Maire said his use of the word “war” had been inappropriate.                                                                                                                                                                                        , Although the incursion into Ukraine is a tangible and overt example of the way geopolitical events are increasingly affecting markets, the shift was already well underway.                                                                                                                                                                                                                                                                                                                                                                                                              , Tensions have been escalating between the United States and China, its largest trading partner in goods, for years, most notably with the trade war during President Donald J. Trump’s administration, which included tariffs on a broad swath of Chinese products in 2018. But the jockeying has continued since then: Beijing has moved to rein in companies that list their shares in the United States while also giving Wall Street banks a freer hand to operate within its borders, meaning that business that investors conduct there is on Chinese terms.                       , Russia’s attack on Ukraine and the moves to isolate it could push Russia even closer to China, which has been more circumspect than other countries about the offensive. It has also prompted increased unease about China’s relationship with Taiwan, the self-governed island that is claimed by Beijing. Although there is no sign that an invasion of the island is imminent, China regularly sends warplanes toward Taiwan, and analysts have said Beijing is making it clear that it would not rule out military action to absorb the island.                                      , Taiwan plays a crucial role in the global supply chain for semiconductor chips that power things as diverse as iPhones and cars, and it is an important trading partner with the United States, which imports billions of dollars in electrical machinery from the island.                                                                                                                                                                                                                                                                                                               , A rising concern. Russia’s attack on Ukraine could cause dizzying spikes in prices for energy and food and could spook investors. The economic damage from supply disruptions and economic sanctions would be severe in some countries and industries and unnoticed in others.                                                                                                                                                                                                                                                                                                           , The cost of energy. Oil prices already are the highest since 2014, and they have risen as the conflict has escalated. Russia is the third-largest producer of oil, providing roughly one of every 10 barrels the global economy consumes.                                                                                                                                                                                                                                                                                                                                                , Gas supplies. Europe gets nearly 40 percent of its natural gas from Russia, and it is likely to be walloped with higher heating bills. Natural gas reserves are running low, and European leaders have accused Russia’s president, Vladimir V. Putin, of reducing supplies to gain a political edge.                                                                                                                                                                                                                                                                                     , Food prices. Russia is the world’s largest supplier of wheat and, together with Ukraine, accounts for nearly a quarter of total global exports. In countries like Egypt and Turkey, that flow of grain makes up more than 70 percent of wheat imports.                                                                                                                                                                                                                                                                                                                                   , Shortages of essential metals. The price of palladium, used in automotive exhaust systems and mobile phones, has been soaring amid fears that Russia, the world’s largest exporter of the metal, could be cut off from global markets. The price of nickel, another key Russian export, has also been rising.                                                                                                                                                                                                                                                                            , Financial turmoil. Global banks are bracing for the effects of sanctions designed to restrict Russia’s access to foreign capital and limit its ability to process payments in dollars, euros and other currencies crucial for trade. Banks are also on alert for retaliatory cyberattacks by Russia.                                                                                                                                                                                                                                                                                     , Any military move on Taiwan would cause a seismic shift for the global economy, and investors and businesses are closely watching the global economic effects of the sanctions on Russia as a test case, said Karl Schamotta, chief market strategist at Corpay, a global payments company.                                                                                                                                                                                                                                                                                              , The sanctions against Russia resemble old-school capital controls, signaling a renewed willingness by governments to use economic tools to achieve foreign policy aims, said Mr. Schamotta, who is based in Toronto. That may come as a shock to companies and traders who have become accustomed to moving hundreds of millions of dollars across borders quickly and easily.                                                                                                                                                                                                           , “There’s going to be sand put into the gears of the global economic machine, on purpose,” he said. “Governments are going to try to slow how things move across borders and how much money can move from one place to the next, and that’s a completely different world if you’re a large multinational corporation — it makes business much more difficult.”                                                                                                                                                                                                                            , Fighting, by itself, has not impeded the growth of financial markets. After the Sept. 11 attacks, for example, the stock market stayed closed for four days and reopened to a sharp sell-off. But the effect was temporary, and equity markets marched steadily higher even as the United States waged wars in Iraq and Afghanistan in the decades that followed. The most severe interruption was a financial, not military, crisis in 2008.                                                                                                                                            , After analyzing the performance of the S&amp;P 500 since 1945, UBS Global Wealth Management found that markets usually fell during the first week of key military conflicts. But in 14 of 18 cases, they rose within three months.                                                                                                                                                                                                                                                                                                                                                           , “Valuations have dropped, so some of the risks have already been priced in,” Solita Marcelli, chief investment officer for the Americas at UBS Global Wealth Management, wrote in a note. “We continue to expect above-trend global growth as countries lift Covid-19-related restrictions.”                                                                                                                                                                                                                                                                                             , Kristina Hooper, the chief global market strategist at Invesco, which manages $1.6 trillion for clients including pension funds, insurance companies and individual investors, said the fighting in Ukraine was more worrisome because of its human toll. She expected small gains for the U.S. stock market this year, but for those gains to come with increased volatility; geopolitical considerations are only adding to the cloudy conditions already facing investors as the Federal Reserve plans interest rate increases to tamp down inflation.                                , “There’s an awful lot of uncertainty out there,” she said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , In the short term, Mr. Schamotta said, investors will probably continue to buy safe-haven assets like the U.S. dollar or Japanese yen and shun risky assets like stocks as Russian forces continue to press into Ukraine. But even if there is a quick and peaceful resolution, the conflict will have lasting effects, he said.                                                                                                                                                                                                                                                         , “In the long run, investors are not going to forget about this episode,” he said. “It’s very, very clear that economic warfare is underway, and as such, I think investors are going to tread more carefully for years to come.”                                                                                                                                                                                                                                                                                                                                                         , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-01 23:50:00 </td>
   <td style="text-align:left;"> Italian 10-year Bond Yield Falls on Geopolitical Risk </td>
   <td style="text-align:left;"> The yield on the Italian 10-year BTP fell to 1.4% in the beginning of March, the lowest in one month, as continued reports of Russian attacks in Ukrainian cities and sanctions from the West led investors to safer assets. Concerns over the Eurozone’s economic growth amid harsher retaliatory measures on Russia and surging commodity prices lowered expectations of faster monetary tightening by the ECB. Still, the lack of consensus displayed by Italian lawmakers during the vote on energy subsidies last month and presidential elections last month raised concerns over the government’s ability to efficiently implement reforms with EU funds amid higher borrowing costs. On the macroeconomic front, Italy’s economy grew by 6.6% during 2021, recovering from the 9% contraction in 2020, while the Italian government recorded a budget deficit of 7.2% in 2021, easing from 9.6% the previous year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-01 23:45:45 </td>
   <td style="text-align:left;"> UK 10-Year Gilt Falls Further to 5-Week Low </td>
   <td style="text-align:left;"> The yield on Britain's 10-year gilt fell to below 1.2%, the lowest in near five weeks, as Russia’s attack on Ukraine intensified boosting demand for safe-haven debt. Also, investors rethink expectations on how aggressive the Bank of England will be in raising interest rates as the Ukraine conflict continues. Before the war, the BoE had forecast inflation will peak at a 30-year high of 7.25% in April, well above the 2% target, when energy bills and taxes are due to go up. Money markets are currently pricing in 25 basis point rate increase from the BoE in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-03-01 23:42:00 </td>
   <td style="text-align:left;"> US Natural Gas Gains Momentum </td>
   <td style="text-align:left;"> US natural gas futures firmed at around $4.5 per million British thermal units, approaching a three-week peak of $4.94 hit on February 24th, as traders eyed stronger overseas demand against forecasts of milder weather. Prospects of tougher sanctions against Russia or fears that major pipelines could go offline during the Ukraine war stoked jitters of supply disruptions from one of the world’s largest producers of oil and gas producers and boosted prospects for stronger demand for LNG from the US. Meanwhile, the latest forecasts pointed to milder weather in March, lowering demand for heating. Also, domestic natural gas inventory levels declined by 129 billion cubic feet last week, less than market forecasts of a 134 bcf draw. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-03-01 23:39:00 </td>
   <td style="text-align:left;"> Mexico Factory Activity Downturn Eases </td>
   <td style="text-align:left;"> The IHS Markit Mexico Manufacturing PMI rose to 48 in February of 2022 from 46.1 in the prior month. The latest reading pointed to the 24th consecutive month of contraction in factory activity but at a softer pace. Output continued to contract, owing to a lack of raw material availability, troubles in the automotive sector and subdued sales poor sales, but the rate of reduction softened. Also, new orders, export sales, input buying and employment fell further, although at slower rates. Meanwhile, inventories of both inputs and finished items decreased faster, as firms reported a reluctance to stockpile products in light of elevated price pressures and subdued demand conditions. Encouragingly, business confidence improved considerably from January's one-year low, while inflationary pressures retreated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-03-01 23:29:39 </td>
   <td style="text-align:left;"> Colombia Manufacturing PMI Eases To 8-Month Low in February </td>
   <td style="text-align:left;"> The Davivienda Colombia Manufacturing PMI eased to an eight-month low of 52 in February of 2022 from 52.6 in the previous month, as production and new orders rose at a softer pace, while the expansion in employment also moderated. Lingering supply chain bottlenecks meant factories could not keep up, and the backlogs of work rose at a record pace while inflationary pressures remained elevated. Finally, businesses remained strongly optimistic about future production levels in February amid prospects of robust demand conditions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60566286?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-01 23:25:57 </td>
   <td style="text-align:left;"> Ukraine conflict: Disney, Warner, Sony halt release of films in Russia </td>
   <td style="text-align:left;"> Warner Bros, Disney and Sony have halted the release of films in Russian cinemas, after the invasion of Ukraine.                                                                                                                           , The announcements mean the releases of major movies The Batman, Turning Red and Morbius will now not go ahead as scheduled in the country.                                                                                                 , They come as governments around the world have been ramping up their sanctions against Moscow.                                                                                                                                             , In recent days global corporations, including car makers and energy giants, have cut business ties with Russia.                                                                                                                            , Warner Bros blockbuster The Batman was due to be released in Russia on Friday.                                                                                                                                                             , "In light of the humanitarian crisis in Ukraine, WarnerMedia is pausing the release of its feature film 'The Batman' in Russia," a spokesperson said.                                                                                      , Meanwhile, Disney has delayed the Russian release of the Pixar animated film, Turning Red.                                                                                                                                                 , "Given the unprovoked invasion of Ukraine and the tragic humanitarian crisis, we are pausing the theatrical release of films in Russia," Disney said in a statement.                                                                       , The entertainment giant added that it would work with non-governmental organisations to provide "urgent aid and other humanitarian assistance to refugees".                                                                                , Sony has also halted the release of its Marvel adaptation Morbius in the country.                                                                                                                                                          , "Given the ongoing military action in Ukraine and the resulting uncertainty and humanitarian crisis unfolding in that region, we will be pausing our planned theatrical releases in Russia," a spokesperson told the BBC.                  , Meanwhile, Netflix has said that it will not comply with new Russian rules to carry state-backed channels.                                                                                                                                 , "Given the current situation, we have no plans to add these channels to our service," a Netflix spokesperson said.                                                                                                                         , Tech platforms Twitter and Facebook have also moved to limit the presence of Russian state-backed news outlet information on their platforms as these have been accused of spreading misinformation about the Russian invasion of Ukraine. , Meta, which owns Facebook, said it would restrict access in the European Union to state-owned media outlets RT and Sputnik.                                                                                                                , Twitter also said it would add warnings to tweets that share links to Russian state-affiliated media.                                                                                                                                      , Twitter's head of site integrity, Yoel Roth, said the platform has seen more than 45,000 tweets per day that were sharing links to these media outlets.                                                                                    , Google said it would block YouTube channels connected to Russian broadcasters RT and Sputnick across Europe.                                                                                                                               , The moves come as many companies try to distance themselves from Russia. Among the actions taken are:                                                                                                                                      , Big investors have also started to either ditch Russian investments or put new investments on hold.                                                                                                                                        , The UK's biggest private pension fund, the British Universities Superannuation Scheme (USS), said on Tuesday that it was "looking to sell" its Russian assets.                                                                             , "We think there's a clear financial as well as a moral case for divestment with respect to our Russian holdings," USS chief executive Simon Pilcher told the BBC's Today programme.                                                        , "There's very little appetite for anyone to trade with Russia under these circumstances, and therefore, in that context, it's very hard to see how Russian investments are a sound financial investment."                                  , Mr Pilcher also said the moral case "was fairly compelling that one should have nothing to do with Russia in the current environment".                                                                                                     , Lucy Coutts, investment director at JM Finn, said: "Russia is un-investable at the present time. The Russian economy has been absolutely slammed by a broadside of crushing Western sanctions.                                             , "Its economy is seizing up, the rouble is worth less than one US cent, inflation is soaring, mortgage rates have gone from 7.5% to 18.6% overnight, and the Russian people are being forced to pay."                                       , Credit rating agencies have said the likelihood of defaults on Russian debt has gone up, so bond markets have seized up, she added.                                                                                                        , This video can not be played                                                                                                                                                                                                               , Watch the final series of Killing Eve on BBC iPlayer                                                                                                                                                                                       , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                                                , The unlikely Olympian talks to Colin Murray about how fear gives him focus                                                                                                                                                                 , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/target-shares-soar-dodging-inflation-boosting-2022-outlook </td>
   <td style="text-align:left;"> 2022-03-01 23:23:12 </td>
   <td style="text-align:left;"> Target shares soar after dodging inflation, boosting 2022 outlook </td>
   <td style="text-align:left;"> National Retail Federation CEO Matt Shay discusses the surge in retail sales and weighs in on inflation and labor shortages.                                                                                                                                                                   , Target shares jumped more than 12% Tuesday morning after the retailer lifted its outlook for 2022 despite surging inflation.                                                                                                                                                                   , Employees restock toys at a Target Corp. store on Black Friday in Dallas, Texas (Photographer: Laura Buckman/Bloomberg via Getty Images) (Laura Buckman/Bloomberg via Getty Images / Getty Images)                                                                                             , The retailer has seen demand surge during the pandemic, reporting $106 billion in total revenue for 2021 and showing growth of nearly $28 billion, or more than 35%, over the past two years.                                                                                                  , Target posted an 8.9% jump in comparable sales for the holiday quarter and beat on earnings, posting adjusted earnings per share of $3.19, up from Wall Street's expectations of $2.85. Traffic surged too, with more than 95% of Target's sales taking place in its stores, the company noted., A Target store is shown in Philadelphia on Wednesday, Nov. 17, 2021.  (AP Photo/Matt Rourke / AP Newsroom)                                                                                                                                                                                     , TARGET HIKES PAY TO $24 PER HOUR FOR SOME EMPLOYEES                                                                                                                                                                                                                                            , "Our strong fourth-quarter performance capped off a year of record growth in 2021, reinforcing the durability of our business model and our confidence in long-term profitable growth," Target CEO Brian Cornell said in a statement.                                                          , Looking ahead, the retailer said it expects low- to mid-single-digit revenue growth this fiscal year, low-single-digit growth in operating margin dollars, and adjusted earnings per share growth in the high single digits.                                                                   , This file photo shows the entrance to a Walmart in Pittsburgh. (AP Photo/Gene J. Puskar, File) (AP Photo/Gene J. Puskar, File / AP Newsroom)                                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                    , Target's results for the quarter ending Jan. 29 follow Walmart's solid forecast last month, when consumers accelerated their retail spending despite an 11-year low in consumer confidence. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-01 23:22:00 </td>
   <td style="text-align:left;"> China 10Y Bond Yield Firms on Upbeat PMI Data </td>
   <td style="text-align:left;"> China’s 10-Year Government Bond Yield traded around 2.8%, not far from a near 2-month high of 2.84% hit on February 22nd, as traders digested upbeat factory activity figures against lingering geopolitical concerns. Two manufacturing PMI readings showed an unexpected expansion in the sector in February, lifting optimism about the impact of the government’s efforts to support the economy. Still, losses were limited by lingering risk-aversion over the Ukraine crisis, after the Kremlin warned Kyiv residents to leave the city and threatened with high-precision strikes, following cease-fire talks on February 28th. In February, the PBOC decided to keep the key loan prime rate unchanged at 3.7%, after cutting rates in the previous two meetings, as expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/construction-spending </td>
   <td style="text-align:left;"> 2022-03-01 23:06:31 </td>
   <td style="text-align:left;"> US Construction Spending Rises the Most in a Year </td>
   <td style="text-align:left;"> Construction spending in the US rose 1.3 percent from the previous month to a seasonally adjusted annual rate of USD 1.677 trillion in January of 2022, the most since in a year, following an upwardly revised 0.8 percent advance in December and easily beating market expectations of a 0.2 percent gain. Spending on private construction rose 1.5 percent, mostly new single family residential construction (1.2 percent), transportation (1.5 percent), power (2.7 percent) and manufacturing (8.5 percent). Also, public construction outlays went up 0.6 percent, boosted by spending on both residential (3.6 percent) and nonresidential (0.5 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-01 23:04:00 </td>
   <td style="text-align:left;"> France 10Y Bond Yield Falls to 1-Month Low </td>
   <td style="text-align:left;"> The yield on the French 10-year OAT fell below 0.4% in the beginning of March, the lowest in over four weeks, as investors rushed to safe-haven assets as economic consequences of harsher sanctions from European states increased the demand of safe-have assets, while investors scaled back on bets of faster monetary tightening by the ECB. At the same time, French Finance Minister Bruno Le Maire said that sanctions have been effective, and that the country has declared an “all out economic war” against Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/business-confidence </td>
   <td style="text-align:left;"> 2022-03-01 23:01:00 </td>
   <td style="text-align:left;"> ISM Manufacturing PMI Tops Forecasts </td>
   <td style="text-align:left;"> The ISM Manufacturing PMI for the US rose for a second straight month to 58.6 in February of 2022 from 57.6 in January and compared to market forecasts of 58. This latest reading showed that the overall economy expanded for the 21st consecutive month. New orders and production continued to increase at a solid pace as COVID-19 infections subsided, though hiring at factories slowed, contributing to keeping supply chains snarled and prices for inputs high. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/coal </td>
   <td style="text-align:left;"> 2022-03-01 23:00:00 </td>
   <td style="text-align:left;"> Coal Hits All-time High </td>
   <td style="text-align:left;"> Newcastle coal futures broke above $300 per tonne for the first time, boosted by soaring demand for electricity and power, mainly from European countries and tight supplies amidst the ongoing Russia-Ukraine war. Germany is set to create coal reserves for electricity power plant operators, while Italy announced it could reopen some shuttered coal plants. Berlin is also considering an incentive plan to revive some troubled liquid natural gas terminal projects. The European Union's coal imports rose by 55.8% in January from a year ago, to 10.8 million tonnes, of which Russia supplied 43%, the data based on ship tracking found. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/propane </td>
   <td style="text-align:left;"> 2022-03-01 22:59:56 </td>
   <td style="text-align:left;"> Propane Hits 17-week High </td>
   <td style="text-align:left;"> Propane increased to a 17-week high of 1.44 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 22:53:05 </td>
   <td style="text-align:left;"> European Stocks Sharply Lower in Afternoon Trades </td>
   <td style="text-align:left;"> European stocks retreated on Tuesday after showing slight gains in early trading, with the German DAX falling 2% and the pan-European Stoxx 600 down by 1%, as investors monitored earnings and the Ukraine crisis. The Kremlin warned Kyiv residents to leave the city and threatened with high-precision strikes, after satellite imagery showed a long Russian armored convoy was headed towards the capital. The developments follow cease-fire talks on Monday. Across sectors, basic resources were 0.9% higher as fears of supply disruptions boosted commodity prices but gains were offset by 5.6% losses in the travel &amp; leisure sector. On the earnings front, German pharma group Bayer posted Q4 net income of €1.17B, compared to €0.31B a year earlier, resulting in EPS €1.18, up from €0.32 last year, and expects 2022 sales to increase by 5% on a FX adjusted basis. Chemicals maker Covestro more than doubled its 2021 core earnings and was upbeat about 2022 profits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 22:51:52 </td>
   <td style="text-align:left;"> TSX Rises for Fourth Day </td>
   <td style="text-align:left;"> Canadian shares advanced for a fourth consecutive day on Tuesday, with the benchmark S&amp;P/TSX climbing towards the 21,200-mark driven by gains among heavyweight energy and mining stocks. Adding to the chipper mood were upbeat GDP figures, with the Canadian economy expanding an annualized 6.70% on quarter at the end of 2021, slightly beating market forecasts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hungary/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-01 22:51:14 </td>
   <td style="text-align:left;"> Hungary 10Y Bond Yield Hits Near 8-year High </td>
   <td style="text-align:left;"> Hungary 10 Year Government Bond Yeld increased to a near 8-year high of 5.35% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-03-01 22:49:00 </td>
   <td style="text-align:left;"> US Manufacturing PMI Revised Lower: Markit </td>
   <td style="text-align:left;"> The IHS Markit US Manufacturing PMI was revised lower to 57.3 in February of 2022, from a preliminary estimate of 57.5 but above the previous month's final reading of 55.5. The headline figure was below the peaks seen in 2021, but signalled a stronger upturn in the health of the manufacturing sector, with sharper output and new order expansions contributing to overall growth. Stronger new sales growth spurred manufacturers to increase staffing numbers and boost stocks of purchases. Pressure on capacity softened as backlogs rose at the slowest pace in a year as material shortages eased. Although input costs increased at the slowest pace for nine months, selling prices ticked higher at the sharpest rate since last November. Finally, output expectations for the coming year were the strongest since November 2020, as firms were buoyed by hopes of a reduction in supply-chain disruption and a greater ability to retain employees. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-03-02 11:02:28 UTC +8

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
   <td style="text-align:left;"> 2022-03-02 11:02:19 </td>
   <td style="text-align:left;"> $SPY really can anyone understand this asshat? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:19 </td>
   <td style="text-align:left;"> $SPY Infrastructure stocks should spike $DE $CAT $VMC $CHPT 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:19 </td>
   <td style="text-align:left;"> $SPY smoke weed — beat opioid epidemic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:18 </td>
   <td style="text-align:left;"> $SPY We can take out Putin by sending the Dominion voting machines to Russia and holding a &amp;#39;vote&amp;#39;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:18 </td>
   <td style="text-align:left;"> $SPY woah who was that guy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:18 </td>
   <td style="text-align:left;"> $SPY Dude wants to help Americans with drug addiction… he couldn’t even keep his son off of crack. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:16 </td>
   <td style="text-align:left;"> $SPY joe Biden supports your gambling addiction 

Be proud </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:16 </td>
   <td style="text-align:left;"> $SPY Circuit breakers to the upside tmrw 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:15 </td>
   <td style="text-align:left;"> $SPY The Dems could definitely use money for mental health services.  Crazy f--kers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:15 </td>
   <td style="text-align:left;"> $spy stop doctors from prescribing treatments? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:14 </td>
   <td style="text-align:left;"> $SPY sign up to be a tutor or a mentor 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:12 </td>
   <td style="text-align:left;"> $SPY was that just a vampire?!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:12 </td>
   <td style="text-align:left;"> $SPY The disconnect between politicians with average people is staggering. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:08 </td>
   <td style="text-align:left;"> $SPY he&amp;#39;s got a little something for everybody. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:08 </td>
   <td style="text-align:left;"> $SPY all these bears will wake up tomorrow and say….. $AFRM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:07 </td>
   <td style="text-align:left;"> $OCGN $4 tomorrow and $spy $420 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:06 </td>
   <td style="text-align:left;"> $SPY he got your back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:05 </td>
   <td style="text-align:left;"> $SPY If he breaks the record on how long he talks today too, that&amp;#39;s guaranteed ATH tomorrow 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:03 </td>
   <td style="text-align:left;"> $SPY give him a few more mins, i swesr he&amp;#39;ll say that he will make America great again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:03 </td>
   <td style="text-align:left;"> $SPY everyone’s legs after the speech 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:02 </td>
   <td style="text-align:left;"> $SPY Slow Joe says its a constitutional right to sexually abuse underage family members. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:01 </td>
   <td style="text-align:left;"> $SPY bunch over crazy’s in that room </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:01 </td>
   <td style="text-align:left;"> $SPY futes are ripping! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:01 </td>
   <td style="text-align:left;"> $SPY Brandon says if you are suffering from addiction, at least you can get free crack pipes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:02:01 </td>
   <td style="text-align:left;"> $SPY are we bearish or bullish tomorrow? It seems like a bunch of weirdos in one room standing and clapping over every little blank statement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:58 </td>
   <td style="text-align:left;"> $SPY 

AOC looks great… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:56 </td>
   <td style="text-align:left;"> $SPY Sounds like he took a lot of notes from Trump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:54 </td>
   <td style="text-align:left;"> $SPY oh man he is starting to lose focus now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:51 </td>
   <td style="text-align:left;"> $SPY Stop doctors from prescribing treatments.

-Joe Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:51 </td>
   <td style="text-align:left;"> $spy amazing speech. Proud to be an American . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:50 </td>
   <td style="text-align:left;"> $SPY Futes Ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:49 </td>
   <td style="text-align:left;"> $SPY  Biden said-“And stop doctrs an st st st stop dctors from prewscribing”!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:48 </td>
   <td style="text-align:left;"> $SPY America hate America hahahah. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:48 </td>
   <td style="text-align:left;"> $SPY $DWAC I tune back in and he&amp;#39;s speed talking through immigration.... Not sure what he was even saying TBH, but here&amp;#39;s the reality of it... Here goes 14 jobs in 1 GIF... Dems america </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:47 </td>
   <td style="text-align:left;"> $SPY BIDEN will create a limit down scenario </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:46 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Folks we have totally lost it 

Stop  picking on  our kids you 

Y’all need Jesus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:46 </td>
   <td style="text-align:left;"> $SPY Give the people in recovery more pills. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:45 </td>
   <td style="text-align:left;"> $SPY free needles!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:42 </td>
   <td style="text-align:left;"> $SPY joe wants transgenders to have opportunity to live up to their god given potential.. god gave them a penis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:42 </td>
   <td style="text-align:left;"> $SPY 😆 🤣 😂 😹 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:41 </td>
   <td style="text-align:left;"> $BBIG $SPY $QQQ  it sounds like Joey took his adderall this evening! Hopefully he shares his low cost drugs with J-pow for his big day tomorrow! 🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:41 </td>
   <td style="text-align:left;"> $SPY cool my aunt cam die in pain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:39 </td>
   <td style="text-align:left;"> $SPY legalize cannabis! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:38 </td>
   <td style="text-align:left;"> $SPY has hunter recovered? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:36 </td>
   <td style="text-align:left;"> $SPY nanci telling kamala which calls to buy tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:36 </td>
   <td style="text-align:left;"> $SPY snap back down to $400 tomorrow ? This overpriced index is retracing back to sub 400. 
The stupid low IQ sleepy joe has no clue what to do.  He&amp;#39;s being controlled by media and mentally ill. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:36 </td>
   <td style="text-align:left;"> $SPY ladyboys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:34 </td>
   <td style="text-align:left;"> $SPY Are they doing squats? Standing up every two seconds to clap. Tools </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:34 </td>
   <td style="text-align:left;"> $SPY TRANNYS &amp;gt; IRANIANS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:33 </td>
   <td style="text-align:left;"> $SPY can only imagine how high libs are on hopium right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:33 </td>
   <td style="text-align:left;"> $SPY Pelosis little sexy ass up there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:31 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:29 </td>
   <td style="text-align:left;"> $SPY his speech was so bad it was used as a bear trap 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:29 </td>
   <td style="text-align:left;"> $SPY Get the hook </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:28 </td>
   <td style="text-align:left;"> $SPY Get help for Hunter!  Buy a painting to help him end the scourge! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:27 </td>
   <td style="text-align:left;"> $SPY oil must be mooning. What a jackass. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:26 </td>
   <td style="text-align:left;"> $SPY I need a 435-438 open to reopen my puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:25 </td>
   <td style="text-align:left;"> $SPY $QQQ Wheres Hunter? He’s talking about taking drugs away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:25 </td>
   <td style="text-align:left;"> $SPY Hunter is going to be pissed Joe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:25 </td>
   <td style="text-align:left;"> $SPY state of the union workout.  Up clap sit down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:24 </td>
   <td style="text-align:left;"> $SPY let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:23 </td>
   <td style="text-align:left;"> $SPY President says he&amp;#39;s going to &amp;quot;Inflict Pain&amp;quot; on putin, lol what&amp;#39;s the deal $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:22 </td>
   <td style="text-align:left;"> $SPY I’m bet AOC pegs her femboi boyfriend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:22 </td>
   <td style="text-align:left;"> $SPY Biden flip flops on his positions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:21 </td>
   <td style="text-align:left;"> $SPY Were all fooked! Take time and VOTE SMART NEXT TIME PLEASE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:20 </td>
   <td style="text-align:left;"> $SPY  Kamala looking impatient like she&amp;#39;s ready to get to Waffle House </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:20 </td>
   <td style="text-align:left;"> $SPY Trans pump - then pump you dont think you want but enjoy anyway </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:16 </td>
   <td style="text-align:left;"> $SPY $QQQ the people that sold you those options today are laughing. Hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:15 </td>
   <td style="text-align:left;"> $SPY bidens doing a good job tonight. Other then the fact that he sounds like he&amp;#39;d had about 12 shots of whiskey. I still think he&amp;#39;s a shit president but this sou isn&amp;#39;t a bad job. (Remeber everything he says is just talk) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:14 </td>
   <td style="text-align:left;"> $SPY  
Blieden  
moving the us below ⬇️ the 13th ranking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:13 </td>
   <td style="text-align:left;"> $SPY get your son off of it first... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:12 </td>
   <td style="text-align:left;"> $SPY Stop doctors from prescribing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:11 </td>
   <td style="text-align:left;"> $SPY that’s over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:11 </td>
   <td style="text-align:left;"> $SPY now the speech becoming diluted —- too much cum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:11 </td>
   <td style="text-align:left;"> $SPY trumpies dead. Hope you sick fucks has some sunflower seeds in ur pockets! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:10 </td>
   <td style="text-align:left;"> $SPY Building a Better America. BABA vs MAGA? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:09 </td>
   <td style="text-align:left;"> $SPY we call them LMNOP’s now Joe get on board </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:07 </td>
   <td style="text-align:left;"> $SPY MAYDAY!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:06 </td>
   <td style="text-align:left;"> $SPY Did he seriously just say that taking 3 decades to pass something was a success...? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:01 </td>
   <td style="text-align:left;"> $SPY don&amp;#39;t know whether to laugh or cry at this speech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:01 </td>
   <td style="text-align:left;"> $spy social justice is our new economy. RIP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:01 </td>
   <td style="text-align:left;"> $SPY Trannies? Seriously?  THEY ARE MENTALLY ILL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:01:00 </td>
   <td style="text-align:left;"> $SPY Everyone just relax, he&amp;#39;s the most popular president in history. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:59 </td>
   <td style="text-align:left;"> $SPY This guy has below room temp IQ for sure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:58 </td>
   <td style="text-align:left;"> $SPY more free crack pipes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:57 </td>
   <td style="text-align:left;"> $SPY biden bro, ypu better end this with putting a hit on oil dude. Ppl go to the gas station every week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:55 </td>
   <td style="text-align:left;"> $SPY PUTs it is for the next 3 years lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:55 </td>
   <td style="text-align:left;"> $SPY $BTC.X 

Bruh, this is painful….

What a bunch of absolute hypocrites </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:54 </td>
   <td style="text-align:left;"> $SPY damp these futures. Otherwise end me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:52 </td>
   <td style="text-align:left;"> $SPY Democrats and Republicans can work together. Its POSSIBLE. America can be stronger! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:50 </td>
   <td style="text-align:left;"> $SPY yea America&amp;#39;s done. In going to bed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:50 </td>
   <td style="text-align:left;"> $SPY Those two behind him asking: “wtf is he talking about?” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:43 </td>
   <td style="text-align:left;"> $SPY Obviously this guy is trying to play both sides. Pure politician through and through </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:43 </td>
   <td style="text-align:left;"> $SPY 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:42 </td>
   <td style="text-align:left;"> $SPY cl @ 109 whoa. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:38 </td>
   <td style="text-align:left;"> $SPY  Good thing the people with money are gonna suck this up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:36 </td>
   <td style="text-align:left;"> $SPY who cares about lgbtq when Ukraine is being blown the fuck up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:35 </td>
   <td style="text-align:left;"> $SPY 

If Nancy gets another facelift, she’ll be farting out of her nose </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:33 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ll always have your back transgenders so that you can reach your GOD GIVEN potential. 

DA FUCK HE JUST SAY. 

I don&amp;#39;t think I can vote blue for another 10 years just off that sentence </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:32 </td>
   <td style="text-align:left;"> $SPY wrap it up joe...lakers game bout to start </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:32 </td>
   <td style="text-align:left;"> $SPY foots rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:30 </td>
   <td style="text-align:left;"> $SPY NOTHING to do with Ukraine ... poor people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:30 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:29 </td>
   <td style="text-align:left;"> $SPY 

lgbtquxbanfkepaifj+ community </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:28 </td>
   <td style="text-align:left;"> $SPY Give Joe a break! His first language is Russian and they&amp;#39;re very different languages!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:28 </td>
   <td style="text-align:left;"> $SPY all dems losing their sanity? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:27 </td>
   <td style="text-align:left;"> $SPY tranny bill top priority. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:27 </td>
   <td style="text-align:left;"> $SPY - </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:25 </td>
   <td style="text-align:left;"> $FB $SPY $NIO $AMD They have helped me to grow my account to almost 2.5 million. 100% recommend joining!! 
 
It&amp;#39;s free joining ~~~~🚀 discord.io/7GPFADBFK5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:25 </td>
   <td style="text-align:left;"> $SPY 

Trumpies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:24 </td>
   <td style="text-align:left;"> $SPY You can be yourself just dont for yourself on me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:23 </td>
   <td style="text-align:left;"> $SPY futures ripping .. see y’all at 4a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:21 </td>
   <td style="text-align:left;"> $SPY Who the fuck shoots a deer with a 556? My dear hunting rifle is a 6.5mm Creedmoor and I’m pretty sure it would rip right trough body armor. Call Lee shit is fucking clowns have no idea what they’re talking about! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:20 </td>
   <td style="text-align:left;"> $SPY clapping getting slow, they tired </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:17 </td>
   <td style="text-align:left;"> $SPY Time to take off lets go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:15 </td>
   <td style="text-align:left;"> $SPY so fuck this guy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:13 </td>
   <td style="text-align:left;"> $SPY futures dropping a little but my brain cells tanking hard after reading these comments… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:13 </td>
   <td style="text-align:left;"> $SPY &amp;quot;Biden sought to rebrand his spending package, formerly known as “Build Back Better,” into a proposal he’s calling “Building a Better America.” It’s pretty much the ideas he proposed before - only messaged as more about deficit reduction and reducing inflation.&amp;quot; - Bloomberg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:12 </td>
   <td style="text-align:left;"> $SPY BIDEN IS A BULL !!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:12 </td>
   <td style="text-align:left;"> $SPY I want to hear about Ukraine, NATO expansion, Yemen, the economic impact of sanctions, and inflation stance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:12 </td>
   <td style="text-align:left;"> $SPY until VIX is back under a 20 and the market moves back over the monthly 10 SMA. I have no reason to believe the market is back to full bull. For now it&amp;#39;s full bullshit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:12 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:09 </td>
   <td style="text-align:left;"> $SPY sweet, baby jesus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:09 </td>
   <td style="text-align:left;"> $SPY trannys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:08 </td>
   <td style="text-align:left;"> $SPY Target is already paying $24 / hour because of your hyperinflation Joe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:07 </td>
   <td style="text-align:left;"> $SPY hope all you libtards are happy with you choice!.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:06 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:05 </td>
   <td style="text-align:left;"> $SPY haha!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:05 </td>
   <td style="text-align:left;"> $SPY you can vote if you had a dick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:04 </td>
   <td style="text-align:left;"> $spy folks, folks... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:02 </td>
   <td style="text-align:left;"> $SPY lgbtq issues &amp;gt; inflation issues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:02 </td>
   <td style="text-align:left;"> $SPY look at all these people looking at him like he is crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:02 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:01 </td>
   <td style="text-align:left;"> $SPY get what done? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:01 </td>
   <td style="text-align:left;"> $SPY I foresaw this dumping tomorrow, but did not expect this speech to be so entertaining and terrible at the same time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 11:00:01 </td>
   <td style="text-align:left;"> $SPY LGBTQ+? THERE’S A + NOW? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:57 </td>
   <td style="text-align:left;"> $SPY someone give Susan Collins a jacket she looks cold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:56 </td>
   <td style="text-align:left;"> $SPY Welp that&amp;#39;s all the people wanted to hear. We don&amp;#39;t need our troops in a fight that&amp;#39;s not ours like Afghanistan.Now back to our original program and this tax inflation. My condolences to those who have lost loved one in this war between Ukraine and Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:56 </td>
   <td style="text-align:left;"> $SPY Zelenskyy for US President </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:56 </td>
   <td style="text-align:left;"> $SPY The speech must be over. Futures are going back up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:55 </td>
   <td style="text-align:left;"> $SPY wait… did he just say fund the police and tighten the border? With a straight face? Pelosi cheering? Oh man, let the gas lighting begin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:53 </td>
   <td style="text-align:left;"> $SPY is Kamala Harris human, there’s just something off about her. Idk..... she’s creepy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:53 </td>
   <td style="text-align:left;"> $SPY TRANS PUMP LETS GO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:53 </td>
   <td style="text-align:left;"> $SPY secure borders fund the police lower drug costs and everyone gets a pony! $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:49 </td>
   <td style="text-align:left;"> $SPY 

Abortion is healthcare?   Hmmm ok. 

Some might disagree but that&amp;#39;s ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:48 </td>
   <td style="text-align:left;"> $SPY futes slippin …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:48 </td>
   <td style="text-align:left;"> $SPY $BTC.X $TSLA 

Where they just clapping at him saying build a wall and fund the police?!?!?!?! 

I can’t even, the eft seriously believe the people have the memory of goldfish 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:46 </td>
   <td style="text-align:left;"> $SPY  rip America. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:45 </td>
   <td style="text-align:left;"> $SPY $QQQ This is an absolute whitehouse 180. They are dropping their failed Covid policies, are wanting to fund the police, and want to address the border. Only took the midterms coming up to change the narrative. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:45 </td>
   <td style="text-align:left;"> $SPY he is literally admitting to every scam they pulled to get him elected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:45 </td>
   <td style="text-align:left;"> $SPY Biden MAGA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:44 </td>
   <td style="text-align:left;"> $SPY 
Option trades, Tuesday recap 3/1 🅿️
📆😤🙏🏽
QQQ 340P +12%
QQQ 355C +27%
AAPL 162.5P +15%
AAPL 170C -20%
BAC 45C +20% 
QQQ 330P +30% still swinging these. 

Quick scalps ftw on a choppy Tuesday 
🎯💯

https://twitter.com/q_alerts/status/1498775899189268480?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:42 </td>
   <td style="text-align:left;"> $SPY 

THIS CLOWN HAS BEEN DEPOSITING ILLEGALS ALL OVER THE US.

KAMALTOE IS THE CZAR

LMFAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:41 </td>
   <td style="text-align:left;"> $SPY did he just flip flop on everything he ran on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:40 </td>
   <td style="text-align:left;"> $SPY If Pelosi and Harris had a baby. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:39 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
In a way I’m sort of glad the population is going to collapse. Only then can liberalism die when things start to really unravel due to no one having kids. Until then enjoy the decline. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:39 </td>
   <td style="text-align:left;"> $SPY Mike Pence’s fly says this speech is garbage. 
 
Democrats were all about defunding the police and rioting when Trump was president, lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:38 </td>
   <td style="text-align:left;"> $SPY my President. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:37 </td>
   <td style="text-align:left;"> $SPY fled cruz really vibin&amp;#39; with the border control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:36 </td>
   <td style="text-align:left;"> $SPY joe is also passing a bill to crackdown on the fucking shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:35 </td>
   <td style="text-align:left;"> $SPY $QQQ Gas prices going up? Let’s just drain our oil reserves and keep buying from Russia! That’ll show Putin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:33 </td>
   <td style="text-align:left;"> $SPY “everything Trump was gonna do I’m gonna do, because that’s possible. I’m gonna do the democrat shit too. This way when Trump runs I’ll just accuse him of stealing my platform because most voters have like a 2 week memory”

Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:33 </td>
   <td style="text-align:left;"> $SPY Half of them are looking as if they are about to cry lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:32 </td>
   <td style="text-align:left;"> $SPY Calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:30 </td>
   <td style="text-align:left;"> $SPY A wise man once said… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:30 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:30 </td>
   <td style="text-align:left;"> $SPY where&amp;#39;s AOC ❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:29 </td>
   <td style="text-align:left;"> $SPY open keystone pipeline jackass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:23 </td>
   <td style="text-align:left;"> $SPY I don&amp;#39;t believe in choosing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:23 </td>
   <td style="text-align:left;"> $SPY Americans going hungry but let’s worry about masks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:20 </td>
   <td style="text-align:left;"> $SPY  I don&amp;#39;t know if I missed that part. but I&amp;#39;m rooting for Millenials and GEN X to have their student debt cancelled by Joe tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:20 </td>
   <td style="text-align:left;"> $SPY border crisis? More like boreder crisis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:20 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm
“Secure the border and fund the police” finally some common sense and leaning to the centre. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:19 </td>
   <td style="text-align:left;"> $SPY all girls the same 
Only thing different is their name </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:17 </td>
   <td style="text-align:left;"> $SPY Hypocrites the Dems are! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:15 </td>
   <td style="text-align:left;"> $SPY biden slurring…meds wearing off. Past bedtime. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:10 </td>
   <td style="text-align:left;"> $SPY wow — he is jumping all over the place. Is Ron burgundy in charge of the teleprompter? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:08 </td>
   <td style="text-align:left;"> $SPY shite i forgot aboit my ramen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:07 </td>
   <td style="text-align:left;"> $SPY Too loud. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:07 </td>
   <td style="text-align:left;"> $SPY 400 tomorrow inevitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:07 </td>
   <td style="text-align:left;"> $SPY Did he really just say we need to stop immigration? 🤣😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:07 </td>
   <td style="text-align:left;"> $SPY pretty sure thats just an animated flesh suit robot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:04 </td>
   <td style="text-align:left;"> $SPY his drugs must be wearing off.. he is starting to slur </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:02 </td>
   <td style="text-align:left;"> $SPY guess what. Trump lost.... And he has tiny hands $IWM $DIA $QQQ $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:02 </td>
   <td style="text-align:left;"> $SPY sleepy joe is making threats. Putin won’t like it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:59:01 </td>
   <td style="text-align:left;"> $SPY watch this and listen to him talk… shit flows 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:58 </td>
   <td style="text-align:left;"> $SPY ted was so mad that he had to stand and clap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:56 </td>
   <td style="text-align:left;"> $SPY Get what done, exactly? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:56 </td>
   <td style="text-align:left;"> $SPY he is trying to get trumps votes now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:56 </td>
   <td style="text-align:left;"> $SPY it would be nice if the camera wasn’t zoomed in on Nancy moving her dentures around non stop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:56 </td>
   <td style="text-align:left;"> $SPY Biden looks hot tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:55 </td>
   <td style="text-align:left;"> $SPY futes r literally gettin fckd.. Hell red tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:53 </td>
   <td style="text-align:left;"> $SPY the FEDS  trying to fight the Bears in the morning 😳😳🤣🤣🤣👀👀👀☠️☠️☠️☠️🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:53 </td>
   <td style="text-align:left;"> $SPY This guy wonders why we need guns when Ukraine is happening LOL.  How clueless can a potato corpse get. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:49 </td>
   <td style="text-align:left;"> $SPY Lol the chick the camera just panned on was sleeping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:48 </td>
   <td style="text-align:left;"> $SPY 
My proposal- inflation control.

1-A 25,000 $ credit debt forgiveness for individuals or 40gs fir couples . Fk the banks. But if they take the credit, they can only use 25% of new credit for each yr for 4 years.
2-minimum wage $25 in tier 1 cities
$20 tier 2
$17 tier 3
3- raise rates 4 points this yr.
4-offer a $5000 incentive for people who work from home to work on site must drive minimum 10 miles daily.

I bet you inflation disappears fast! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:48 </td>
   <td style="text-align:left;"> $SPY pull the plug on this robot !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:47 </td>
   <td style="text-align:left;"> $SPY $PFE 

Imagine we did that with the vaccine manufacturers 😦🤯😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:47 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:47 </td>
   <td style="text-align:left;"> $SPY No No No!! TRUMP2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:45 </td>
   <td style="text-align:left;"> $SPY Biden trying to remember how he got in this position in the first place </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:45 </td>
   <td style="text-align:left;"> $SPY This assemble at home ghost gun has my attention thanks Joe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:44 </td>
   <td style="text-align:left;"> $SPY  vaccine manufacturers can’t be sued either </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:42 </td>
   <td style="text-align:left;"> $SPY so biden is reinstating so much trump policy that he called racist. Remember folks its not racist if a democrat does it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:42 </td>
   <td style="text-align:left;"> $SPY 

LEGAL immigrants, dummy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:41 </td>
   <td style="text-align:left;"> $SPY Futes rippin again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:40 </td>
   <td style="text-align:left;"> $SPY biden been living under a rock, minimum wage is already 15$ an hour 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:39 </td>
   <td style="text-align:left;"> $SPY 100 round mags not fundamental to the 2nd amendment. Meanwhile in Ukraine….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:38 </td>
   <td style="text-align:left;"> $SPY Biden: bshjjsheg sjjebeve skejebehd kdidujcjr oejehsndkoe3 

Clap clap clap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:38 </td>
   <td style="text-align:left;"> $SPY secure borders? What lmao magamagamagamaga </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:37 </td>
   <td style="text-align:left;"> $SPY the extra clapping is to keep him awake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:30 </td>
   <td style="text-align:left;"> $SPY we are funding police and securing our border now 💀 these liberal whores will do anything for a vote. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:29 </td>
   <td style="text-align:left;"> $SPY so take away the guns from the citizens, fuck Black Lives Matter they did their part, more police and more state powers weeeee!!

Thx to all the stupid lemmings who do the work of these corrupt assholes for the promise of a handful of bird seed and then get turned into chicken dinners. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:29 </td>
   <td style="text-align:left;"> $SPY Biden starting to slur. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:28 </td>
   <td style="text-align:left;"> $SPY sure glad we have forgotten about all those veterans who fought in the forever wars…. Fuckem, who needs to pass the Major Richard Star Act anyway. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:24 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s going off the rails.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:24 </td>
   <td style="text-align:left;"> $SPY oil is $110 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:23 </td>
   <td style="text-align:left;"> $SPY americans - instead of fixing their own problems they prefer to fix other peoples problems. 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:22 </td>
   <td style="text-align:left;"> $SPY Aunt Jemima </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:22 </td>
   <td style="text-align:left;"> $QQQ $SPY Ted Cruz woke up lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:22 </td>
   <td style="text-align:left;"> $SPY stunt on these hoes joe! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:21 </td>
   <td style="text-align:left;"> $SPY Now this asshole has the nerve to say we need to secure the border. Dude 2 million people have crossed this year...... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:19 </td>
   <td style="text-align:left;"> $SPY Border crisis Done lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:16 </td>
   <td style="text-align:left;"> $SPY who chanted build the wall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:16 </td>
   <td style="text-align:left;"> $SPY I’m getting bored. Nancy is starting to look sexy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:14 </td>
   <td style="text-align:left;"> $SPY 

CLOWN IS FLYING ILLEGALS ALL OVER THE US </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:14 </td>
   <td style="text-align:left;"> $SPY Democrats have a missing chromosome </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:13 </td>
   <td style="text-align:left;"> $SPY Oh the lies.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:12 </td>
   <td style="text-align:left;"> $SPY 

LMAO. Mitch and Ted look like they have hemorrhoids…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:11 </td>
   <td style="text-align:left;"> $SPY lololll!!!! Now secure the border 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:11 </td>
   <td style="text-align:left;"> $SPY secure our border!  😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:09 </td>
   <td style="text-align:left;"> $SPY build the wall!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:08 </td>
   <td style="text-align:left;"> $SPY Send your ghost gun to Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:07 </td>
   <td style="text-align:left;"> $SPY the same people applauding Ukrainians handing out guns to anyone who wants it…breathtaking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:05 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:04 </td>
   <td style="text-align:left;"> $SPY is biden first language English? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:03 </td>
   <td style="text-align:left;"> $SPY vote red never forget </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:58:02 </td>
   <td style="text-align:left;"> $SPY This dude want too be like  Trump in the worst way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:59 </td>
   <td style="text-align:left;"> $SPY The more I stare at this guy, the more he looks and acts like a parallel universe Bush. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:58 </td>
   <td style="text-align:left;"> $SPY theres no such thing as equitable in our justice system. They certainly say they want just and equitable outcomes, but the laws never achieve that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:58 </td>
   <td style="text-align:left;"> $SPY now you wanna secure the border </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:57 </td>
   <td style="text-align:left;"> $SPY THIS GUY JUST SAID SECURE OUR BORDER DID HE JUST SAY BUILD A WALL? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:57 </td>
   <td style="text-align:left;"> $SPY 

DID HE SAY SECURE OUR BORDER?!??! LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:56 </td>
   <td style="text-align:left;"> $SPY lets see how many haters hate on the first black woman on the supreme court. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:56 </td>
   <td style="text-align:left;"> $SPY 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:56 </td>
   <td style="text-align:left;"> $SPY this sounds like a Trump speech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:56 </td>
   <td style="text-align:left;"> $SPY BUILD THE WALL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:55 </td>
   <td style="text-align:left;"> $SPY Ted jumped up for that one that’s what trump has been doing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:50 </td>
   <td style="text-align:left;"> $SPY all you bidón voters are as stupid as he is! Lol💯💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:49 </td>
   <td style="text-align:left;"> $SPY 

The border!   Hmmm.  You&amp;#39;re a joke! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:49 </td>
   <td style="text-align:left;"> $SPY where my golf cart @ boy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:49 </td>
   <td style="text-align:left;"> $SPY TAX the RICH!!!!   
tax the shit out of the top 1%!!!!  the top 1% steal from all of us!!! 
  
TAX the RICH and build a strong middle class   
   
STOP paying CEO millions of $$$, they don&amp;#39;t deserve it!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:48 </td>
   <td style="text-align:left;"> $SPY hate to admit it but I now generally think Stocktwits retail traders know more about the economy then biden does.... that&amp;#39;s sad..really sad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:47 </td>
   <td style="text-align:left;"> $SPY Biden: brave people of Ukraine protecting themselves with automatic weapons

Also Biden: we must ban high capacity mags because deer don&amp;#39;t wear bulletproof vests. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:47 </td>
   <td style="text-align:left;"> $SPY “do you think the deer 🦌 is wearing bulletproof vest?” Biden 

Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:47 </td>
   <td style="text-align:left;"> $SPY Brandon found somebody who meets all the qualifications for the SCOTUS. Black, check. Identifies as female, check. Good enough. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:46 </td>
   <td style="text-align:left;"> $SPY secure the border </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:45 </td>
   <td style="text-align:left;"> $SPY..... he say fix Border ....... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:44 </td>
   <td style="text-align:left;"> $SPY He is So Ironic Right now eh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:44 </td>
   <td style="text-align:left;"> $SPY OH FUCK, BIDEN SAID BORDER, BEARS ON SUICIDE WATCH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:42 </td>
   <td style="text-align:left;"> $SPY Moon tomrrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:41 </td>
   <td style="text-align:left;"> $SPY 
Didn’t Trump say that????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:40 </td>
   <td style="text-align:left;"> $SPY Cancun Cruz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:40 </td>
   <td style="text-align:left;"> $SPY oil loves it. Go oil go oil! Gas will be 8.00 by summer! We will build american but products will somehow be cheaper. We will take care of inflation but we will not raise rates! We will help Ukraine but we will be doing nothing and watching teachers and normal citizens fight Russian soldiers. Oh Vaccines cannot be stopped by a wall. Call 9/11 please this wild </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:39 </td>
   <td style="text-align:left;"> $SPY Cops are dicks until you need one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:36 </td>
   <td style="text-align:left;"> listening to bidens sotu makes me bearish af $SPY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:35 </td>
   <td style="text-align:left;"> $SPY ted Cruz is a rino </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:34 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:32 </td>
   <td style="text-align:left;"> $SPY Glad I stopped and got gas before Biden started yapping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:30 </td>
   <td style="text-align:left;"> $SPY Guns for Ukrainians, but not for Americans. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:30 </td>
   <td style="text-align:left;"> $SPY Paul is preparing for Pelosi&amp;#39;s after party. I can&amp;#39;t get past her mouth moving like a typewriter. Forget stocks for a min. We have a sitting speaker of the house clearly searching her mouth for a crumb. LMFAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:27 </td>
   <td style="text-align:left;"> $SPY I’m entertained when congressmen and women get caught on camera on their smartphone 

They are clearly sending dick picks on Snapchat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:26 </td>
   <td style="text-align:left;"> $SPY What does PELOSI have in her mouth... She had a piece of steak trapped in her throat? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:23 </td>
   <td style="text-align:left;"> $SPY No!! Like I’m trying to put his words together </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:23 </td>
   <td style="text-align:left;"> $SPY 

She&amp;#39;s a black woman.  You said that&amp;#39;s all that matters right ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:22 </td>
   <td style="text-align:left;"> $SPY Kamala prepping for the NFL combine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:21 </td>
   <td style="text-align:left;"> $SPY wen moon?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:19 </td>
   <td style="text-align:left;"> $SPY Hilarious tho......this board isnt even talking about stocks 🤣😂😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:19 </td>
   <td style="text-align:left;"> $SPY if the deers are wearing vests can we get tanks, bullish ones civilian tanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:18 </td>
   <td style="text-align:left;"> $SPY guns blah blah pills blah blah jobs blah blah infrastructure blah blah assault weapons blah blah Community College blah blah Deez Nuts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:16 </td>
   <td style="text-align:left;"> $SPY he pronounced her name. I&amp;#39;m surprised. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:16 </td>
   <td style="text-align:left;"> $SPY puts on deer kevlar vest companies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:16 </td>
   <td style="text-align:left;"> $SPY Katangee Jackson </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:15 </td>
   <td style="text-align:left;"> $SPY Put me in coach I have a statement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:14 </td>
   <td style="text-align:left;"> $SPY Fuckin’ justices can’t even stand? Punk ass bitches… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:13 </td>
   <td style="text-align:left;"> $SPY Fuck the police. Don&amp;#39;t fund those bastards. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:11 </td>
   <td style="text-align:left;"> $SPY stand up you spring chicken you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:09 </td>
   <td style="text-align:left;"> $SPY this nigga has two feet already in the grave 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:08 </td>
   <td style="text-align:left;"> $SPY The only industry that can’t be sued?  Lol. How bout them vaccine injuries? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:08 </td>
   <td style="text-align:left;"> $BTC.X $SPY
Joe Biden: “No one making less than $400,000/year will pay more taxes.”
By the end of his term, you might need to make $400,000/year just to survive.. and then he’ll make you pay taxes 😂

So maybe his plan was right all along 💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:08 </td>
   <td style="text-align:left;"> $SPY smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:07 </td>
   <td style="text-align:left;"> $SPY thanks dawg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:06 </td>
   <td style="text-align:left;"> $SPY yea even though almost all gun related homicides are with hand guns but ban assault weapons and high capacity mags… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:06 </td>
   <td style="text-align:left;"> $SPY You notice all these ACTS but no Anti Lynching ACT smh! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:05 </td>
   <td style="text-align:left;"> $SPY this gun argument doesn&amp;#39;t speak well atm as we spend millions to arm ukraine, but I did notice he isn&amp;#39;t trying to disarm the population, I&amp;#39;m not conspiracy theorist but I wonder if that&amp;#39;s a pivot due to ukraine, maybe it&amp;#39;s good that a civilian population has firearms in the modern New world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:03 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm 
Minor fuck ups, overall bullish speech, so far. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:02 </td>
   <td style="text-align:left;"> $SPY How about that voter ID? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:01 </td>
   <td style="text-align:left;"> $SPY ironically he took all points from trump.. all opposite of what they do, wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:00 </td>
   <td style="text-align:left;"> $SPY govern me hard daddy! Please read this bills and acts. The wording and open-ended rights black holes and funding loopholes will remain until noticed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-02 10:57:00 </td>
   <td style="text-align:left;"> $SPY we all know.... that the market is going to listen to the federal reserve chair more than this idiot,. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 11:02:12 </td>
   <td style="text-align:left;"> $QQQ stop doctors Rx treatments 🍺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 11:02:00 </td>
   <td style="text-align:left;"> $QQQ free crack pipes and fight opioid epidemic? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 11:01:47 </td>
   <td style="text-align:left;"> $QQQ never heard someone talk so much about a bunch of shit that doesn&amp;#39;t matter. Does he live in the same country I do? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 11:01:46 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Folks we have totally lost it 

Stop  picking on  our kids you 

Y’all need Jesus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 11:01:41 </td>
   <td style="text-align:left;"> $BBIG $SPY $QQQ  it sounds like Joey took his adderall this evening! Hopefully he shares his low cost drugs with J-pow for his big day tomorrow! 🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 11:01:25 </td>
   <td style="text-align:left;"> $SPY $QQQ Wheres Hunter? He’s talking about taking drugs away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 11:01:16 </td>
   <td style="text-align:left;"> $SPY $QQQ the people that sold you those options today are laughing. Hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 11:00:53 </td>
   <td style="text-align:left;"> $QQQ what a shit show, markets are sure to drop 600 points at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 11:00:44 </td>
   <td style="text-align:left;"> $QQQ I’m going to fight inflation with this trillion dollar bill!!!! Okay Sleepy Joe. Just tell the public the Federal Reserve has this country by the balls. End the Fed and fire the whole shit White House. That’s how we end the Plandemic and live freely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 11:00:37 </td>
   <td style="text-align:left;"> $QQQ &amp;quot;FOLKS, I have 2 LGBTQ&amp;#39;s sitting behind me now&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 11:00:24 </td>
   <td style="text-align:left;"> $QQQ wonder how many companies will leave the us on higher taxes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:59:53 </td>
   <td style="text-align:left;"> $QQQ the 2 LGBTQ&amp;#39;s are sitting behind Brandon now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:59:53 </td>
   <td style="text-align:left;"> $SPY secure borders fund the police lower drug costs and everyone gets a pony! $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:59:45 </td>
   <td style="text-align:left;"> $SPY $QQQ This is an absolute whitehouse 180. They are dropping their failed Covid policies, are wanting to fund the police, and want to address the border. Only took the midterms coming up to change the narrative. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:59:42 </td>
   <td style="text-align:left;"> $MMAT $TSLA $QQQ Real price will come out soon, Follow price target; chatx.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:59:39 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
In a way I’m sort of glad the population is going to collapse. Only then can liberalism die when things start to really unravel due to no one having kids. Until then enjoy the decline. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:59:35 </td>
   <td style="text-align:left;"> $SPY $QQQ Gas prices going up? Let’s just drain our oil reserves and keep buying from Russia! That’ll show Putin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:59:20 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm
“Secure the border and fund the police” finally some common sense and leaning to the centre. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:59:14 </td>
   <td style="text-align:left;"> $QQQ FOLKS? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:59:02 </td>
   <td style="text-align:left;"> $SPY guess what. Trump lost.... And he has tiny hands $IWM $DIA $QQQ $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:58:22 </td>
   <td style="text-align:left;"> $QQQ $SPY Ted Cruz woke up lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:58:05 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:57:26 </td>
   <td style="text-align:left;"> $QQQ ooooooof let&amp;#39;s fund ICE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:57:18 </td>
   <td style="text-align:left;"> $QQQ State of the Union address is causing futures to become flat. More bearish tomorrow. The speech didn’t work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:57:13 </td>
   <td style="text-align:left;"> $QQQ looking like Biden in that suit 🤤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:57:03 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm 
Minor fuck ups, overall bullish speech, so far. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:56:57 </td>
   <td style="text-align:left;"> $SPY $QQQ Why the markets would all of a sudden turn bullish is beyond my understanding. Inflation is still rampant. If interest rates aren&amp;#39;t raised its only going to get worse and the US is at risk of losing market share in the currency wars. Real Estate is in a bubble. People have record debt. Prices on everything right down to producers is rising at record rates daily. The market makes no sense. 

I&amp;#39;m saying we just made a lower high. But we&amp;#39;ll find out. 

So far futures have been red 3 days in a row and markets been green. Perhaps green futures tonight for a red market tomorrow. 

Oil, gold and materials are the top market movers right now. This is usually end of bull cycle type of movement. Same thing occurred before the 2008 crash. I&amp;#39;m staying bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:56:53 </td>
   <td style="text-align:left;"> $QQQ This is hard to watch.  Watch the old state of the union from FDR, Reagan etc.  They were 100x better than this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:56:52 </td>
   <td style="text-align:left;"> $QQQ funny no mention about the southern border or inflation. Weird. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:56:45 </td>
   <td style="text-align:left;"> $QQQ this is the most fake thing I have ever seen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:56:31 </td>
   <td style="text-align:left;"> $SPY $QQQ MOST DIVISIVE PRESIDENT of our time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:56:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $AXON “ do you think deer wear Kevlar vests”  - Joe Biden SOTU 2022 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:55:55 </td>
   <td style="text-align:left;"> &amp;quot;Tonight, I’m announcing a crackdown on these companies overcharging American businesses and consumers.&amp;quot;

Sounds close to what China did $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:55:51 </td>
   <td style="text-align:left;"> $QQQ $SPY $AMC $BBIG a better way ?? Wtf

I have a better way to fight inflation - lower your costs ,  not your wages - Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:55:48 </td>
   <td style="text-align:left;"> $MMAT $TSLA $QQQ Real price will come out soon, Follow price target.. chatx.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:55:38 </td>
   <td style="text-align:left;"> $QQQ Boebert with a fat chick so she looks pretty.  ugly ass bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:55:36 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:54:52 </td>
   <td style="text-align:left;"> $SPY $QQQ theyre not defund the police anymore? They were for funding the police before they were against it before they were for it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:54:40 </td>
   <td style="text-align:left;"> $QQQ fund the police … AOC … will ligjt up your white male ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:54:31 </td>
   <td style="text-align:left;"> $SPY people don&amp;#39;t forget biden just spewing dogshit $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:54:23 </td>
   <td style="text-align:left;"> $SPY $QQQ ♿️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:53:34 </td>
   <td style="text-align:left;"> $SPY $QQQ 
 
He boasted that, “Unlike the $2 Trillion tax cut passed in the previous administration that benefitted the top 1% of Americans, the American Rescue Plan — the American Rescue Plan helped working people — and left no one behind.” 
 
That&amp;#39;s why I almost always vote for the Dems. The Republicans help the top 1% only and their policies don&amp;#39;t benefit me, the Dems help the middle class and people with lower income much more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:53:27 </td>
   <td style="text-align:left;"> $SPY $QQQ he’s starting to slur and stumble. Quick, someone get him a kid to sniff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:53:25 </td>
   <td style="text-align:left;"> $QQQ responding to a 9/11 call? 🤦🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:53:15 </td>
   <td style="text-align:left;"> $QQQ hes talking like gas is $.75 a gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:52:28 </td>
   <td style="text-align:left;"> $QQQ he is wearing a dirty diaper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:52:19 </td>
   <td style="text-align:left;"> $SPY $QQQ Biden - “let’s use this moment to reset”.   
 
klaus is grinning from ear to ear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:52:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 77150100. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:51:56 </td>
   <td style="text-align:left;"> $QQQ No I still say fuck Democrats. No getting along </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:51:38 </td>
   <td style="text-align:left;"> $DOGE.X $BTC.X $QQQ $SPY EVERYTHING IS FREE BABY!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:51:15 </td>
   <td style="text-align:left;"> $QQQ we gonna rip to the moon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:51:11 </td>
   <td style="text-align:left;"> $SPY $djia $QQQ Bring back the Donald Pump.  He sucked but he at least pumped the market not dump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:51:02 </td>
   <td style="text-align:left;"> $QQQ BREAKING NEWS!

PARENTS ARE EAGER TO HAVE THEIR CHILDREN UNDER 5 VACCINATED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:50:54 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AMZN 

Big corporations will get taxed 15%.

Entities earning less than $400k won&amp;#39;t get taxed further.

Biden now pushing vaccines and boosters. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:50:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Most people need to admit that President Biden did a way better job on COVID than Trump did. Under Trump, COVID was out of control. Under Biden, COVID was being contained quickly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:50:07 </td>
   <td style="text-align:left;"> $QQQ new vaccines in 100 days 😂🤣😅 group study of 10 pts control 1 … no p value calculation, who needs that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:49:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA CONTACTS OUT SOCKS OFF BING BONG 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:49:50 </td>
   <td style="text-align:left;"> $QQQ Hospitalizations down by 77% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:49:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA literally anytime this man opens his mouth  indices turn red 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:49:12 </td>
   <td style="text-align:left;"> $QQQ nobody cares about COVID democrat stooge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:49:11 </td>
   <td style="text-align:left;"> $QQQ &amp;quot;I&amp;#39;m going to fight big pharma&amp;quot; 5 minutes later,&amp;quot; I&amp;#39;m ordering more pills than anyone&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:49:06 </td>
   <td style="text-align:left;"> $SPY $QQQ Nadler the only one in the room with a mask on and that fat slob can’t even stand up. Pelosi with that shithead grin on her face the whole time. That’s it guys I can’t watch anymore of this shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:48:50 </td>
   <td style="text-align:left;"> $QQQ forced tax on companies (even tho rate is 21% now they use tax code intelligently to reduce, like they should) and increase wages. A perfect storm for market sell off amongst inflation, raising rates, and fear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:48:43 </td>
   <td style="text-align:left;"> $SPY $QQQ
Watched for one minute and saw a Kamala fake hyena laugh and Pelosi botox smile and that was all I could take.  Switched off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:48:40 </td>
   <td style="text-align:left;"> $QQQ 

Companies getting higher taxes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:48:30 </td>
   <td style="text-align:left;"> $QQQ if Ukraine had a vax mandate, Russia wouldn’t invade… but for real though, explain why Moderna had patented covid strain 3 years ago </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:48:25 </td>
   <td style="text-align:left;"> $SPY $QQQ 
F Pfizer and fuck Covid 
And fuck your calls on Pfizer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:48:15 </td>
   <td style="text-align:left;"> $QQQ the free test are from China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:48:03 </td>
   <td style="text-align:left;"> $QQQ Covid over gg shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:47:56 </td>
   <td style="text-align:left;"> $QQQ poo poo time . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:47:26 </td>
   <td style="text-align:left;"> $QQQ he sounds like a drug salesman </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:47:19 </td>
   <td style="text-align:left;"> $SPY futures green because they know congress is flipping red during midterms and none of this speech is grounded in reality.. slimmest majority since grover cleveland $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:47:06 </td>
   <td style="text-align:left;"> $SPY $QQQ WE DONT WANT ANYMORE VACCINES JOE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:46:53 </td>
   <td style="text-align:left;"> $QQQ pelosi is long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:46:34 </td>
   <td style="text-align:left;"> $SQQQ $QQQ holysht. Raise minimum wage to 15 an hour?? Prices gonna go sky high. Biden also pushing for higher corporate taxes. Market ain&amp;#39;t gonna like this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:46:31 </td>
   <td style="text-align:left;"> $QQQ  
 
As much as Trump sucked ass, this guy sucks just as much.  
 
Middle finger to both parties because  both hate black people any way. 
 
FBA/B1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:46:26 </td>
   <td style="text-align:left;"> $QQQ this state of the union sounds like corporate America is expected to pay for all of Joe&amp;#39;s promises.

manufacturers should be buying American materials, paying American wages, paying more taxes, and be making more money BY CUTTING COSTS.

Do we expect the executives to cut their own pay to make this happen? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:46:26 </td>
   <td style="text-align:left;"> $SPY $QQQ i agree with Joe here. Why don’t we just raise the minimum wage to $100, why stop at $15. Shit let’s do it at $200 so we don’t have to have this conversation again until next year. We’re Americans, we can afford to at least do $300/hr as the min wage! Yeah Biden…problem solver in chief </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:46:15 </td>
   <td style="text-align:left;"> $SPY don&amp;#39;t worry congress flippingudring midterm .. this is a dog and pony show $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:45:50 </td>
   <td style="text-align:left;"> $QQQ ok so  lowering all costs by forcing companies to charge less, making companies pay higher salaries, then lowering their profits, then taxing companies more, then those companies will be investing more money in America then ever. Huh??? If your not confused then your one of the idiots. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:45:40 </td>
   <td style="text-align:left;"> $SPY $QQQ Typical democrat strategy - throw trillions of US taxpayer dollars into government shithole programs, bleed them dry while lining the pockets of Congress and the elite, and keep fucking over the working class Americans. Fuck these guys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:45:40 </td>
   <td style="text-align:left;"> $SPY $QQQ 
 
President Biden said he wants to fight inflation by lowering costs to make goods, not lowering wages for Americans. 
 
Sounds good, hopefully we can enjoy an economic boom while wages will keep surging under President Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:45:33 </td>
   <td style="text-align:left;"> $QQQ $SPY he is so bad at this. He doesnt even feel the crowd and let the speech flow. They start clapping he just rushes through. Cant even get a speech right how can he run our country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:45:22 </td>
   <td style="text-align:left;"> $QQQ let&amp;#39;s increase spending and tax everyone more. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:45:14 </td>
   <td style="text-align:left;"> $SPY Biden wants to crack down companies overcharging consumers.  Let&amp;#39;s start with the US Congress and the US Tax code.    Oh, and Biden&amp;#39;s spending problem.  $uvxy $qqq $sqqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:45:13 </td>
   <td style="text-align:left;"> $SPY $QQQ lol Biden dumping futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:45:10 </td>
   <td style="text-align:left;"> $QQQ Different President, same meaningless words! Donkey and Pony show!🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:45:02 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Kamala Harris looks like a dude!! 😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:45:01 </td>
   <td style="text-align:left;"> $QQQ so we&amp;#39;re raising minimum wage of $15 an hour on a federal level </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:45:00 </td>
   <td style="text-align:left;"> $QQQ imagine being bullish.. yikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:44:55 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:44:46 </td>
   <td style="text-align:left;"> $SPY $QQQ https://www.youtube.com/watch?v=5MvFf6nMWGY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:44:38 </td>
   <td style="text-align:left;"> $QQQ hell, let’s buy everyone a house! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:44:33 </td>
   <td style="text-align:left;"> $IWM Uninspiring nonsense. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:44:31 </td>
   <td style="text-align:left;"> $SPY $QQQ did I hear right..? Biden Proposing 50% tax on corporations. .Wow .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:44:06 </td>
   <td style="text-align:left;"> $QQQ $SPY Joe Biden actually called Ukrainians &amp;quot;Iranians&amp;quot; toward the beginning of his speech. He trips over his words and mispronounces what should be easy things to say every few sentences. Even with a teleprompter in his face, he can&amp;#39;t get it right. It&amp;#39;s embarrassing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:43:52 </td>
   <td style="text-align:left;"> Putin Prepared to Invade Ukraine months ago last year by moving military forces to border in March 2021  after Joe Biden  became President  Biden did nothing and ignored it.  

Putin Russia and Xi Jiping China perception of American Leadership Joe Biden is weak👀

China will be planning moves to take 
Taiwan 🇹🇼

$AAPL $QQQ $SPY $AMD $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:43:49 </td>
   <td style="text-align:left;"> $QQQ 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:43:44 </td>
   <td style="text-align:left;"> $QQQ he contradicts everything he says lol wtf is he talking about </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:43:41 </td>
   <td style="text-align:left;"> $QQQ if you believe anything this clown says, you are either poor or will be soon, you don’t have to listen to me, but mark this post and see what happens, hit me up later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:43:38 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA hehehehehehe 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:43:38 </td>
   <td style="text-align:left;"> $QQQ I don&amp;#39;t think Joe understands supply/ demand and how inflation works and did he say Iranian? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:43:26 </td>
   <td style="text-align:left;"> $QQQ if Mconnel didn&amp;#39;t blink you would swear he&amp;#39;s dead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:43:17 </td>
   <td style="text-align:left;"> $QQQ tomorrow will not be a boring day in the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:42:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Pandemic fraud - dang it&amp;#39;s time for a crackdown $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:42:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD 

Calls gonna go parabolica tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:42:21 </td>
   <td style="text-align:left;"> $SPY $QQQ Has anyone told Joe Uraine people dont exist? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:42:19 </td>
   <td style="text-align:left;"> $SPY $QQQ What about Ukraine/Russia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:42:17 </td>
   <td style="text-align:left;"> $QQQ 50% tax rate why would companies stay here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:42:11 </td>
   <td style="text-align:left;"> Look at Pelosi&amp;#39;s face-- she happy her Stocks will print $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:42:07 </td>
   <td style="text-align:left;"> $QQQ Kamala has the most judgmental looks I have seen yet.  Entertaining. Every new word gets a new look. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:41:27 </td>
   <td style="text-align:left;"> $QQQ FOLKS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:41:08 </td>
   <td style="text-align:left;"> $QQQ What a snooze fest in Washington </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:40:56 </td>
   <td style="text-align:left;"> $QQQ 15% min tax rate GG stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:40:27 </td>
   <td style="text-align:left;"> $QQQ and taxes, I paid more this year than any other year, middle class, you are being lied too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:40:22 </td>
   <td style="text-align:left;"> $QQQ will that’s bearish, there goes earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:39:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $IWN 

THIS LADY 2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:39:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $INTC Not gonna lie, Biden rallying everyone but where tf is all this money coming from. I love my country but sounds too good to be true. Oh well. FU Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:39:50 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA lol biden talking about raising taxes on the rich in a room full of millionaires </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:39:35 </td>
   <td style="text-align:left;"> $SPY $QQQ All these idiots saying AOC is sexy, you&amp;#39;ve never dealt with a crazy latina before. That right there is looney tunes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:39:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $BTC.X I mean if all the craziness that&amp;#39;s happened over the last couple of years would&amp;#39;ve happened even just 5 years ago, man oh man, would I have been going nuts.  Fortunately, when we come to Him, He promises us a peace that only He can provide (John 14:27).   🙏✝️🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:39:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 
Yeah cut all the costs. But we dont know who pays for it! Probably retail investors!! Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:39:18 </td>
   <td style="text-align:left;"> $QQQ $SPY sounds expensive.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:39:16 </td>
   <td style="text-align:left;"> $QQQ affordable healthcare only for himself, and his elderly needs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:39:14 </td>
   <td style="text-align:left;"> $QQQ I’m feeling dumber watching this 🤡 . Clearly he failed economics 101 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:39:02 </td>
   <td style="text-align:left;"> $QQQ electric cars? Paid 85k for a new Tesla, can’t get a single cent in tax break from government, check it out, liar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:39:01 </td>
   <td style="text-align:left;"> $QQQ $SPY   to cut inflation ....help producer to help consumer...cut the fucking tax on producers of essential goods..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:38:37 </td>
   <td style="text-align:left;"> $QQQ all the people upset about the speech must know what&amp;#39;s gonna happen to their puts tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:38:15 </td>
   <td style="text-align:left;"> $TLT $UUP $SPY $QQQ $TNX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:37:48 </td>
   <td style="text-align:left;"> $QQQ three clowns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:37:32 </td>
   <td style="text-align:left;"> $SPY $QQQ I didn’t know you could kill inflation by blaming high prices on the companies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:36:57 </td>
   <td style="text-align:left;"> $QQQ is he plagiarizing Trump? MAGA. Hey Biden just became a nationalist. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:36:56 </td>
   <td style="text-align:left;"> $QQQ Maybe all you Biden haters will chill for a bit...probably not though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:36:41 </td>
   <td style="text-align:left;"> $QQQ $SPY $TLT $VIX $GLD Watch As Macrostrategist David Hunter discusses the possibility of a Secular Market Top following the coming Melt Up &amp;amp; the MASSIVE Global Economic Bust Coming!👇👀👇❗️

WATCH NOW: https://youtu.be/bRZhrSJgcaw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:36:10 </td>
   <td style="text-align:left;"> $SPY $QQQ 
M
A
G
A
Say it stop copying say it 
Say </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:36:00 </td>
   <td style="text-align:left;"> $QQQ lower your costs? Mfer, who raised taxes and printed so much money that companies have to raise cost to do business? Who tha fook voted for this loser? Fook all you guys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:35:39 </td>
   <td style="text-align:left;"> Ticker: $QQQ 
 
Buy: March 04, 2022 $342.00 Calls 
 
Entry Price: $5.12 - $5.13 
 
Exit Price: $6.25 
 
Stop Loss: $4.51 
 
Potential ROI: 22% 
 
Estimated Hold Time: 89 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:35:26 </td>
   <td style="text-align:left;"> $QQQ this fucking kid is advocating for diabetes… what an asshole </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:35:16 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DIA popping off bigly tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:35:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM 
https://youtu.be/FPYWxxZ_NrY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:34:36 </td>
   <td style="text-align:left;"> &amp;quot;I have a better way to fight inflation-- lower your costs, not your wages&amp;quot;- Biden  $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:34:24 </td>
   <td style="text-align:left;"> $SPY $QQQ So refreshing to hear a real leader to speak in the SOTU, Trump didn&amp;#39;t speak like a President and acted like a clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:34:03 </td>
   <td style="text-align:left;"> $QQQ he’s so out of touch it’s not even funny. Has no idea about anything substantive. Couldn’t even explain the things he’s saying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:33:53 </td>
   <td style="text-align:left;"> $SPY $QQQ  LOOOOL Biden tells companies “lower your costs” HAHAHAH WHAT?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:33:45 </td>
   <td style="text-align:left;"> $QQQ soooo my calls will look great tomorrow you say!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:33:19 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA awwwwh grampie bidens stim shot is wearing off quicker than they thought, quick! Race him out before he starts stuttering and drooling too much. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:33:09 </td>
   <td style="text-align:left;"> $SPY $QQQ President Biden mentioned $INTC, Intel shares likely will soar tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:33:08 </td>
   <td style="text-align:left;"> $SPY $QQQ he literally constantly advertises that he knows nothing about economics or inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:33:05 </td>
   <td style="text-align:left;"> $SPY $QQQ Folks, America is doing great! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:32:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X 

Ah jeez he’s fading end it quick…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:32:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA just because Biden talking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:32:08 </td>
   <td style="text-align:left;"> $QQQ r r r r r r r rust belt! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:32:02 </td>
   <td style="text-align:left;"> $QQQ $SPY YOU BE FUCKIN STANK HOES I BE COUNTIN BANKROLLS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:32:01 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm lol traitorous Putin loving commie trumptards 🍊🍊🍊🍊🍊are throwing a fit with Biden promising to bring jobs and tech back to America 🇺🇸🇺🇸🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:31:44 </td>
   <td style="text-align:left;"> $QQQ this country is fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:31:22 </td>
   <td style="text-align:left;"> $QQQ if you want this country to go forward, ask him what CI means? Yeah if he can’t, he can’t lead this country </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:30:54 </td>
   <td style="text-align:left;"> I&amp;#39;m sorry but using tax payer money to help $INTC build a plant? That&amp;#39;s the dumbest ****ing thing I&amp;#39;ve heard yet. Make them do it themselves $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:30:26 </td>
   <td style="text-align:left;"> $QQQ intel calls now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:30:24 </td>
   <td style="text-align:left;"> $QQQ even with 100 billion dollars and 20 years intel will never catch Taiwan Semi. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:30:24 </td>
   <td style="text-align:left;"> $QQQ 10 semoconductor factories … by by taiwan … 1 month after he gavw green light to russia … he gives green light to china … by by taiwan it was good while it lasted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:30:00 </td>
   <td style="text-align:left;"> $QQQ You seen that smile on Nancy&amp;#39;s face when Biden talking about semiconductors lol she&amp;#39;s thinking about her MU Call Options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:29:56 </td>
   <td style="text-align:left;"> Biden (celebrating): &amp;quot;The Russian market is down 40%!&amp;quot; 
Me: &amp;quot;$QQQ is down 20% too Joe.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:29:39 </td>
   <td style="text-align:left;"> $QQQ $BTC.X How many Rubles is one Bitcoin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:29:33 </td>
   <td style="text-align:left;"> $AMD $QQQ bidens new middle out economy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:29:32 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm
I am not a fan, but so far, it’s a good speech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:29:18 </td>
   <td style="text-align:left;"> $SPY  $QQQ  Run ass holes bears run..... My husband is all in on calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:29:17 </td>
   <td style="text-align:left;"> $QQQ computer chips the size of a finger tip? Lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:29:12 </td>
   <td style="text-align:left;"> $QQQ intel to the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:28:40 </td>
   <td style="text-align:left;"> $QQQ Brandon speaks, this drops 🤦🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:28:34 </td>
   <td style="text-align:left;"> $QQQ   attention Bears   $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:28:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
Wasted the last year in the stock market.  Should have been trading commodities.  My word. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:27:52 </td>
   <td style="text-align:left;"> $SPY $QQQ This is so funny. Is he bragging about made in America when him and his son literally make millions outsourcing to other countries </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:27:47 </td>
   <td style="text-align:left;"> $QQQ Yes people we are going to buy America.  That way we won&amp;#39;t owe payments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:27:41 </td>
   <td style="text-align:left;"> $QQQ $DWAC $ATXI  
All that you need to know. Shorts haven&amp;#39;t covered a single share; Check it out below, highly recommend everyone to follow them: profit.stocktradingchat.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:27:30 </td>
   <td style="text-align:left;"> $QQQ , $IWM, $SPY
Not bothered to watch the senile with diapers give a useless speech, we don’t have a president, accept it, this country is headless right now, 1st step to take it back is in November when democrats are going to the crapper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:27:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $VOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:27:19 </td>
   <td style="text-align:left;"> $QQQ I shit my pants, but I did on the backs of Americans, hard working Americans! 👏👏👏👏👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:27:12 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Biden got  mofos in the benches like…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:26:47 </td>
   <td style="text-align:left;"> $SPY $QQQ damn the Internet is so quick. Iranian already trending on Twitter LMAOOOOOOO!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:26:20 </td>
   <td style="text-align:left;"> $QQQ $SPY Joe&amp;#39;s a 🤡 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:26:17 </td>
   <td style="text-align:left;"> $SPY $BTC.X $QQQ 

Those damn Uranium’s ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:26:11 </td>
   <td style="text-align:left;"> $QQQ this plan of his will never happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:26:01 </td>
   <td style="text-align:left;"> $QQQ bears are done 4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:25:50 </td>
   <td style="text-align:left;"> $QQQ tjats the most squats those fat bellies have ever done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:25:13 </td>
   <td style="text-align:left;"> $SPY $QQQ Did Joe Biden single hand-idly build America? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:25:10 </td>
   <td style="text-align:left;"> $QQQ damnit stop. I want to buyback at 330 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:24:36 </td>
   <td style="text-align:left;"> $QQQ Holy hell  Bears are so fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:24:03 </td>
   <td style="text-align:left;"> Biden: I can announce the United States has worked with 30 other countries to release 60 million barrels of oil from reserves around the world..we stand ready to do more if necessary. United with our allies. These steps will help blunt gas prices here at home. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:54 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:51 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $DJIA $QQQ --- 
 
The #1 reason for personal bankruptcy in this country is Medical Debt.   Sleepy Joe was elected on the promise that he would reduce the cost of healthcare by implementing a public option,  a measure supported by the MAJORITY of the country, including Republicans and Democrats working-class Americans (yes, Americans,  Not Ukrainians).   Sleepy Joe has broken his promise, and he hopes that Americans will forget about it by distracting them with all that bullshit 6,000 miles away.  I hope that this November Americans don’t forget and don’t forgive  this fucken liar. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X 

Wow this is embarrassing to the 10000th degree….I can’t even…

I can’t wait for the memes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:40 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F $QQQ $DIA  🧞‍♂️🤑

Pump it up Joe.   $5000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:40 </td>
   <td style="text-align:left;"> $QQQ Mconnel looking terrified as usual.  Why is he always scared? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:40 </td>
   <td style="text-align:left;"> $QQQ okay guys we are going to go back to all the highs. I&amp;#39;m selling my puts at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:35 </td>
   <td style="text-align:left;"> $QQQ how could someone so out of touch get elected as president? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:33 </td>
   <td style="text-align:left;"> $QQQ lol we tax the rich … Pelosi stands and clap paying zero taxes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:29 </td>
   <td style="text-align:left;"> $QQQ the Iranian people we are here for you! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:25 </td>
   <td style="text-align:left;"> $QQQ dude created 6.5 million jobs? Name one company you starter or invest in? 🤣🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:22 </td>
   <td style="text-align:left;"> $QQQ Putin deciding to take some entertainment out of sleepy joe&amp;#39;s old, boring speech soon...mark this post. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:17 </td>
   <td style="text-align:left;"> $QQQ gave people a little breathimg room … you know who has a lpt of breathing room?! Those people in there … i wander if papa biden told him that too? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:23:03 </td>
   <td style="text-align:left;"> $SPY $QQQ 
wait what the hell just happened, he stood up to early, the applause light didn’t come on yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:22:42 </td>
   <td style="text-align:left;"> $SPY $QQQ Democrats are fake as fuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:22:30 </td>
   <td style="text-align:left;"> Here comes the PPT to boost the futures on the premise of nothing $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:22:05 </td>
   <td style="text-align:left;"> BIDEN: BRINGING PRICING UNDER CONTROL IS HIS TOP GOAL.

Does he know how Money actually works? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:21:55 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:21:51 </td>
   <td style="text-align:left;"> $QQQ LMFAOOOOOOOOOO 🤡🤡🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:21:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X 

Did he just call Ukrainians people Iranian?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:21:48 </td>
   <td style="text-align:left;"> $QQQ FUTES GREEN! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:21:48 </td>
   <td style="text-align:left;"> $SPY $QQQ kamala&amp;#39;s shocked face when he said &amp;quot;Iranian&amp;quot; that was priceless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:21:48 </td>
   <td style="text-align:left;"> $CL_F $USO If this rally in oil keeps up, it will start breaking things... 
$QQQ $XLE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:21:35 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Heart of who!!? 😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:21:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Futes are green, it looks like people like what they&amp;#39;re hearing from Joe Biden as he reads off the teleprompter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:21:25 </td>
   <td style="text-align:left;"> BIDEN: I WILL FILE A REQUEST TO CONGRESS FOR MORE PANDEMIC-RELATED FUNDS SOON.

Inflation to 10% by the end of the year $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:21:21 </td>
   <td style="text-align:left;"> $QQQ iranian people baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:21:20 </td>
   <td style="text-align:left;"> $QQQ Joe’s dad sounds like a lowlife </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:20:11 </td>
   <td style="text-align:left;"> $SPY $BTC.X $QQQ 

Soooooooo what about the United States? 

I’m so confused, this isn’t the State of Ukraine… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:19:13 </td>
   <td style="text-align:left;"> $QQQ Don’t piss off the Swiss. They will cut you, then open your bottle for you and file your nails. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:19:07 </td>
   <td style="text-align:left;"> $QQQ tech poopin $SPY $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:19:06 </td>
   <td style="text-align:left;"> $QQQ Lmao your hate for Biden won’t change the fact that Trump lost 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:18:54 </td>
   <td style="text-align:left;"> $SPY nancy might have loaded hell of PUTS $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:18:49 </td>
   <td style="text-align:left;"> U.S. bans Russian aircraft from American airspace 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:18:14 </td>
   <td style="text-align:left;"> U.S. bans Russian aircraft from American airspace $SPY $VIX $DIA $QQQ https://www.cnbc.com/2022/03/01/us-bans-russian-aircraft-from-american-airspace.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:18:06 </td>
   <td style="text-align:left;"> $SPY $QQQ Am I the only one who literally can’t even watch this shit or am I crazy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:18:05 </td>
   <td style="text-align:left;"> $QQQ Russian Economy is rucked up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:17:46 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA Mama Pelosi🥰🤩😮‍💨😮‍💨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:17:42 </td>
   <td style="text-align:left;"> $SPY $QQQ 
what happen to the feed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:17:21 </td>
   <td style="text-align:left;"> $QQQ how much is this going to cost, Joe? We live in 🇺🇸 shithead! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:16:50 </td>
   <td style="text-align:left;"> $QQQ why are these whores in the background </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:16:46 </td>
   <td style="text-align:left;"> $SPY welp Futes are red 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:16:41 </td>
   <td style="text-align:left;"> $QQQ keep kicking the bear.  Hope he doesn’t bite. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:16:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY bang those democratic war drums </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:16:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA  Pretty sure Putin is not going to take this well...🤕🤒 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:15:39 </td>
   <td style="text-align:left;"> $QQQ $SPY is it just me or is Biden moving things along because he is tired/about to start gaffing the crap out of this speech? LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:15:30 </td>
   <td style="text-align:left;"> $SPY $QQQ Take a shot every time they get up and start clapping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:15:29 </td>
   <td style="text-align:left;"> $QQQ Futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:15:24 </td>
   <td style="text-align:left;"> $QQQ holy shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:15:21 </td>
   <td style="text-align:left;"> $SPY $QQQ he said rugles lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:14:39 </td>
   <td style="text-align:left;"> $SPY $qqq isn’t Joe Biden talking about leading in Ukraine like an arsonist coming back to the scene of the crime while the firefighters are there and then telling them that he actually helped them and is leading them by starting the fire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:14:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY Go Switzerland! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:13:59 </td>
   <td style="text-align:left;"> $QQQ $SPY $NIO $TSLA 

Putin as he listens to Biden’s speech… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:13:57 </td>
   <td style="text-align:left;"> $SPY $QQQ I don’t care what party you’re for - we need an age limit on presidency. 60 is the cutoff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:13:47 </td>
   <td style="text-align:left;"> BIDEN: PUTIN MAY GAIN ON THE BATTLEFIELD, BUT HE WILL PAY A HIGH PRICE IN THE LONG RUN.

Red Flag $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:12:44 </td>
   <td style="text-align:left;"> $SPY futures crashing. $QQQ just went Red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:12:02 </td>
   <td style="text-align:left;"> $SPY $QQQ audience clapping for biden rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:11:59 </td>
   <td style="text-align:left;"> $QQQ &amp;quot;thank you thank you thank you&amp;quot; --&amp;gt; you elected this sleepyhead only for him to say two words all the time! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:11:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X 

THAT LOOK HE GIVES THE AUDIENCE AFTER HE PUTS A SENTENCE TOGETHER….😂😂😂😂😂😂😂😂😂😂😂

I’ve never laughed so hard in my life! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:10:00 </td>
   <td style="text-align:left;"> $SPY $QQQ 

How many miss this y’all 
I know I do </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:09:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

At least they aren’t wearing white like a bunch of cultish losers… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:09:24 </td>
   <td style="text-align:left;"> $QQQ $SPY can&amp;#39;t wait to see how Biden spins everything to seem like America is in great shape </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:09:12 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:09:12 </td>
   <td style="text-align:left;"> $SPY $QQQ Pelosi gonna make bank tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:09:00 </td>
   <td style="text-align:left;"> $QQQ brandon out of his nursing home and about to speak soon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:08:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $ARKK

BIDEN’S WEAK!!!... LIKE A BULL!!...📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:08:29 </td>
   <td style="text-align:left;"> $SPY I love how Chuck Todd says he&amp;#39;ll be discussing Ukraine and all the issues. How about the absurd levels of inflation we are all dealing with. SMH @NBCNewsBusiness $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:08:05 </td>
   <td style="text-align:left;"> $QQQ 

Option trades, Tuesday recap 3/1 🅿️

QQQ 340P +12%
QQQ 355C +27%
AAPL 162.5P +15%
AAPL 170C -20%
BAC 45C +20% 
QQQ 330P +30% still swinging these. 

Quick scalps ftw on a choppy Tuesday 
🎯💯

https://twitter.com/q_alerts/status/1498775899189268480?s=21🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:08:03 </td>
   <td style="text-align:left;"> $SPY $QQQ how much adder all is he on? 9pm on a school night? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:07:09 </td>
   <td style="text-align:left;"> Russian forces appear to have seized control of Kherson, a city in southern Ukraine. No word from local officials $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:06:50 </td>
   <td style="text-align:left;"> $QQQ lmaoooo futures dropping as king autist walks out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:06:47 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY president ready for a his bib and a nap and he just walked in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:06:23 </td>
   <td style="text-align:left;"> $QQQ 120 to 140 oil....get ready for a 100 bucks burger also </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:05:40 </td>
   <td style="text-align:left;"> $QQQ State of the union about to start.  Biden coming out upside down like 50 cent with his shirt off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:05:20 </td>
   <td style="text-align:left;"> $SPY $QQQ Where the fuck is he?!? 9.05pm. Did he fall asleep again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:05:04 </td>
   <td style="text-align:left;"> $QQQ Current support and resistance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:04:28 </td>
   <td style="text-align:left;"> $QQQ why oil 110 here we come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:03:59 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
fk Biden idc  
 
what time does jflation speak tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:03:18 </td>
   <td style="text-align:left;"> $SPY $QQQ i think as the first mentally handicapped president, Joe Biden has shown the heights that mentally challenged individuals can attain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:02:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $DWAC Biden and the Democrats are pushing the made in American theme... Wasn&amp;#39;t that what Trump was pushing? And the Dems opposed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:02:28 </td>
   <td style="text-align:left;"> $QQQ just dump it to 12900 I call the correction done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:01:47 </td>
   <td style="text-align:left;"> $QQQ $SPY how do these people even show their faces. Either they are responsible for the mess were in or make excuses that they have no impact/arent responsible for anything. Completely useless and worthless freeloaders walking through. How they are proud of the work they do is beyond me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:00:56 </td>
   <td style="text-align:left;"> $QQQ $SPY @LongBacon i hope you have some canoes left on deck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:00:53 </td>
   <td style="text-align:left;"> $spy $QQQ comrade Biden is about to speak. I am sure futures will soar as the markets take comfort in the most brilliant orator who ever lived </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:00:34 </td>
   <td style="text-align:left;"> $QQQ satoshi 2024🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 10:00:16 </td>
   <td style="text-align:left;"> $SPY $QQQ They’re turning up at the SOTU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:59:53 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Supreme pizza rolled out like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:59:20 </td>
   <td style="text-align:left;"> $QQQ here we go! We about to rip up or dump 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:59:19 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY joey biden speaking tonight like... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:58:33 </td>
   <td style="text-align:left;"> $QQQ I just wanna say, I love this group chat. You guys are the best, keep it up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:57:26 </td>
   <td style="text-align:left;"> $QQQ $Just a couple  pennies  short of $7 a gallon  up here in Canada.  Don&amp;#39;t  even ask for our oil. We going to sell it to Europe.  You Dumb fcks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:56:48 </td>
   <td style="text-align:left;"> $QQQ when you realize Putin lied to you, what do you do? brilliant!

https://twitter.com/jpdoctor/status/1497954040386187267?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:56:25 </td>
   <td style="text-align:left;"> $QQQ after a drop...perhaps a bounce at rooster time... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:56:16 </td>
   <td style="text-align:left;"> $SPX     $QQQ     $DIA     $SPY     $DJIA 

         G O O D           L U C K </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:55:55 </td>
   <td style="text-align:left;"> $QQQ market really good for swingers...but even the best will get caught with pants down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:55:23 </td>
   <td style="text-align:left;"> $QQQ YOU thought you would vote for the  second  oldest person in America  Because  Why. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:54:58 </td>
   <td style="text-align:left;"> Oil keeps MOONING-- Tomorrow those Oil Changes will start at $100 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:53:28 </td>
   <td style="text-align:left;"> Market will follow $CENX, stocks set for stunning rally $SPY $QQQ $DIA $XLK  https://www.thestockmarketacademy.com/p/what-to-look-for-this-week?s=w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:53:21 </td>
   <td style="text-align:left;"> $SPY $QQQ Things are about to turn up at the SOTU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:52:39 </td>
   <td style="text-align:left;"> $SPY $QQQ IM GOING TO SLEEP SO PEACEFULLY, WAKE UP RESTED. IMMEDIATE EDGE TO YOU ASSHOLES FOR TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:52:05 </td>
   <td style="text-align:left;"> Stage is set for an insane rally.

$SNAP $SPY $QQQ $DIA $XLK  https://www.thestockmarketacademy.com/p/what-to-look-for-this-week?s=w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:51:24 </td>
   <td style="text-align:left;"> $SPY $QQQ ONE HUNDO PERCENT CASH GANG.. WE AVOID THETA / IV / GAP ISSUES AND ENTER YOUR MARKET WITH A CLEAN SLATE. FUCK YOUR SHIT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:50:26 </td>
   <td style="text-align:left;"> $QQQ ukrain is a smaller county next to a country called Eussia which is a bigger country. So they invade a smaller country which is Ukrain and its wrong! 
By : Kamala Harris 
3rd grade teacher.  

Me: and people are actually stupid enough to vote for this administration? 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:49:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $XLK  https://www.thestockmarketacademy.com/p/what-to-look-for-this-week?s=w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:49:00 </td>
   <td style="text-align:left;"> $QQQ  Biden  once again set to address the Sky rocket  price of Hamburger. CAUSE he knows  that&amp;#39;s all  Middle  Class  can afford  now.  Just need to go siphon some gas,to get me there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:48:48 </td>
   <td style="text-align:left;"> $SPY $QQQ listening to this hot mic on cspan for stock picks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:46:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA WHEN ONE DOOR CLOSES, ANOTHER OPENS AND GOES BING BONG 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:44:58 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ  THIS IS BIG! My Friend just texted me -  US has cancelled all the flights going via Russian Airspace! His flight got cancelled until further notice🚨🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:44:44 </td>
   <td style="text-align:left;"> $SPY $QQQ 100% CASH OVERNIGHTS BECAUSE FUCK YOU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:44:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:43:39 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL Breaking

Putin nuclear warning as unhinged Russian leader tipped to drop bomb near Britain

VLADIMIR PUTIN could be planning to drop a nuclear bomb near Britain in a show of force against the West.

 https://www.express.co.uk/news/world/1573848/nuclear-war-uk-Russia-Vladimir-Putin-Ukraine-latest-news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:42:03 </td>
   <td style="text-align:left;"> $Spy $qqq 20 mins before the gibberish start! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-02 09:41:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA IT IS I, YOUR HOST, LONG BACON HERE TO PROVIDE YOUR STATE OF THE BACON. THE STATE OF THE BACON IS BING BONG 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 11:01:23 </td>
   <td style="text-align:left;"> $SPY President says he&amp;#39;s going to &amp;quot;Inflict Pain&amp;quot; on putin, lol what&amp;#39;s the deal $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 11:01:22 </td>
   <td style="text-align:left;"> $PTON 35 end of March 2022, back up truck here - $AMZN $aapl $NKE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 11:01:05 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $165.0 CALLS for Wednesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:56:03 </td>
   <td style="text-align:left;"> $AAPL 

Wow…Biden is a disaster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:55:27 </td>
   <td style="text-align:left;"> $AAPL joe.  Stfu already.   Ure killing futures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:47:42 </td>
   <td style="text-align:left;"> latex0fa28ff43c006120af171c66285368acAAPL 968k (57% call/43% put)
$AMD 722k (64% call/36% put)

Lynk in bayo for option trading ideas and alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:43:58 </td>
   <td style="text-align:left;"> $SOFI $TSLA $AAPL $GOOG  does the market turn after the speech? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:43:52 </td>
   <td style="text-align:left;"> Putin Prepared to Invade Ukraine months ago last year by moving military forces to border in March 2021  after Joe Biden  became President  Biden did nothing and ignored it.  

Putin Russia and Xi Jiping China perception of American Leadership Joe Biden is weak👀

China will be planning moves to take 
Taiwan 🇹🇼

$AAPL $QQQ $SPY $AMD $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:43:27 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB $TSLA  

I’d be embarrassed and feel like a wimp being 2nd gentleman </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:42:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Pandemic fraud - dang it&amp;#39;s time for a crackdown $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:39:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 
Yeah cut all the costs. But we dont know who pays for it! Probably retail investors!! Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:38:43 </td>
   <td style="text-align:left;"> $SPY BIDEN IS PUMPING THE WHOLE MARKET MORE THAN THE FAANG STOCKS IN ONE SPEECH!!! THAT IS MY PRESIDENT!  $AMZN $MSFT $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:35:05 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB $FB 

Oh but when trump says make in America it’s racist </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:34:49 </td>
   <td style="text-align:left;"> $SOFI BIDEN CARRYING FUTURES!!  USA USA USA USA!!!! $SPY $UVXY $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:24:58 </td>
   <td style="text-align:left;"> $VERB 
U ever see a lil stock, like the 1 that $TSLA  Ceo Elon mentioned that went up like 2000% in 1 day for being associated with tesla?
That&amp;#39;s what i think may happen when Verbs producer streaming content David Meltzer starts for $AAPL &amp;amp; mentions Verbtv being shoppable or maybe by the reading on this pr that Meltzer uses Verbteck on Apple&amp;#39;s streaming to make it all shoppable. Of course apple wants their streaming shoppable &amp;amp; tbey never heard of Verb until now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:19:48 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:19:37 </td>
   <td style="text-align:left;"> $VERB 
Who cares if David Meltzer wants to issue a pr reminding people of his show 2 min drill shown on $AMZN $AAPL tv, Bloomberg tv &amp;amp; will utilize Verbtv. 

https://www.prnewswire.com/news-releases/season-three-of-david-meltzers-2-minute-drill-premieres-on-apple-tv-301487896.html

It is probably just to male the show shoppable. That&amp;#39;s all who cares. Verb is a young company with Mr.Meltzer as their producer to provide original content that Verb will make shoppable utilizing its proprietary technology.  Verb has also just hired Kate Eckman the Qvc star, to be a brand hunter &amp;amp; probably a host for Verb&amp;#39;s new live stream ecommerce website 
Market.live 
Soon to launch
You want Verb to make u a store. One of my froends just made a store a couple weeks ago . Holding her 1st event next week. It is currently in soft launch so u need a password to attend. Not to too much longer. Soon it will be Live open to the public
https://marketplace.vidnt.com/studio/login </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:19:25 </td>
   <td style="text-align:left;"> $AAPL hope the market drops 10% tomorrow and goes back to the covid numbers. for all the morons who voted for Biden. 5$ gas, $200 wk groceries, 401k’s decimated.  The jokes on you clowns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:18:54 </td>
   <td style="text-align:left;"> $SPY nancy might have loaded hell of PUTS $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:18:41 </td>
   <td style="text-align:left;"> $SPY $AMZN $FB $AAPL To be clear, wall street does not want US-Russia clashes at all.
His speech is provoking Putin and more market volatility🤥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:16:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA  Pretty sure Putin is not going to take this well...🤕🤒 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:15:56 </td>
   <td style="text-align:left;"> $AAPL see it under 150 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:15:48 </td>
   <td style="text-align:left;"> TRADE IDEA ⚔️#PRESSIT  
TICKER 📈 $AAPL  
LONG TRIGGER 🔫 166.63 
LONG PT🎯170.47 
SHORT TRIGGER🔫 161.96 
SHORT PT🎯158.19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:13:31 </td>
   <td style="text-align:left;"> $SPY $TSLA $FB $AAPL US - Russia Head to head now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:12:26 </td>
   <td style="text-align:left;"> $AMD $GOOGL $AAPL $TSLA look at Pelosi. She didn&amp;#39;t look this happy when Trump was giving SOTU speech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:08:29 </td>
   <td style="text-align:left;"> $DWAC $SPY $AAPL this is going to be FUNNY 😂🙈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:03:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Stops Selling Its Products In Russia In Response To Invasion Of Ukraine https://www.stck.pro/news/AAPL/23681991 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:01:27 </td>
   <td style="text-align:left;"> $SPY madam speaker the Presidents cabinet 🙋‍♂️💯🤡 $tsla $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 10:00:20 </td>
   <td style="text-align:left;"> $SPY $AAPL $GOOG who is ready for the manufactured pump after the puppet gives his first SOTU? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:51:35 </td>
   <td style="text-align:left;"> $AAPL has more cash than $RSX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:50:29 </td>
   <td style="text-align:left;"> We love to help traders win consistently!
We crush it both ways on $AAPL $AMZN and $TSLA as you may notice on our feed! Let’s get you stacking gains too! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:47:48 </td>
   <td style="text-align:left;"> $AAPL  russian apple sales stopped by apple is the headline,the actual fact is the &amp;quot;russian ruble&amp;quot; sunk so much that it would cost an arm and a leg to by anything apple with rubles, unless the products are priced in rubles apple wouldtake a currency hit  https://finance.yahoo.com/news/apple-suspends-product-sales-russia-212013717.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:47:21 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m hoping green for tmw but just know it is a buy for long term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:44:58 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ  THIS IS BIG! My Friend just texted me -  US has cancelled all the flights going via Russian Airspace! His flight got cancelled until further notice🚨🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:43:39 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL Breaking

Putin nuclear warning as unhinged Russian leader tipped to drop bomb near Britain

VLADIMIR PUTIN could be planning to drop a nuclear bomb near Britain in a show of force against the West.

 https://www.express.co.uk/news/world/1573848/nuclear-war-uk-Russia-Vladimir-Putin-Ukraine-latest-news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:39:31 </td>
   <td style="text-align:left;"> $AAPL RMED📈ROAD TO $100
Only RMED related. 
Do not shill other tickers ♦️
https://t.me/RMEDinvestor......... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:38:10 </td>
   <td style="text-align:left;"> $AAPL $TSLA  tinyurl.com/2p9e489k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:34:51 </td>
   <td style="text-align:left;"> $AAPL 

$200 so that I can pay my bills🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:32:23 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-01 Options Analysis Video: 
https://www.youtube.com/watch?v=DzRvr4kFcqY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:31:36 </td>
   <td style="text-align:left;"> $VERB you&amp;#39;d think David Meltzer&amp;#39;s involvement with both Verb, and $AAPL would have had this article show up under the Apple section of the news feed... Maybe they trying to keep it hush hush? I guess people watching a TV show might be blown away when they can use the mouse, or tv remove to buy from right on the TV show. 😎

https://www.prnewswire.com/news-releases/season-three-of-david-meltzers-2-minute-drill-premieres-on-apple-tv-301487896.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:29:58 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $FB $NVDA 
Bearish until he stops 😞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:27:00 </td>
   <td style="text-align:left;"> The industry average Profit Margin is 6.11%. $AAPL outperforms 93% of its industry peers. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:24:26 </td>
   <td style="text-align:left;"> $SPY $JPM $AAPL $MSFT $NVDA 
OMG. 20% interest rate? 😱
🤞 Hope Russia has fixed rate like we do. 

😒 Hawkish Bullard will definitely hike 0.75-1% on March. Weak earnings for growth tech stocks expected , SPY down. 

https://www.cnbc.com/2022/02/28/russia-central-bank-hikes-interest-rates-to-20percent-from-9point5percent-to-bolster-ruble.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:22:31 </td>
   <td style="text-align:left;"> $AAPL  How low is this going to dive tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:22:25 </td>
   <td style="text-align:left;"> $SPY Doesn&amp;#39;t bottom till $AAPL does. Mark it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:20:05 </td>
   <td style="text-align:left;"> $spy $AAPL $QQQ $GS https://www.cnbc.com/2022/02/23/cramer-expects-stock-rally-if-inflation-or-russian-aggression-resolve.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:18:39 </td>
   <td style="text-align:left;"> $AAPL Good news today is that the FED reassess its stand on interest rates. As I posted many times before, it will not rise rates this year more than once or two, and even this is not sure. The economy is not great, inflation is not as high as it shows in the last few months, and although it may go higher because of oil, the FED is not going to kill the economy just to lower inflation. 

Powell must thread a needle on Capitol Hill this week to calm markets https://www.cnbc.com/2022/03/01/with-inflation-and-ukraine-powell-must-thread-a-needle-on-capitol-hill-this-week-to-calm-markets.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:06:19 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $FB Watching Biden speech and futures at the same time on a drink😂! It&amp;#39;s gonna be fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:04:04 </td>
   <td style="text-align:left;"> $AAPL just, says it all: https://hackaday.com/2022/02/27/neon-ukraine-and-the-global-semiconductor-industry/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:03:04 </td>
   <td style="text-align:left;"> $AAPL uglyyyy. Bought puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 09:01:19 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $165.0 CALLS for Wednesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:53:09 </td>
   <td style="text-align:left;"> $AAPL this can’t break .80 ah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:50:45 </td>
   <td style="text-align:left;"> $AAPL 
Joe Xiden fkn blows !!! 
Get that clown out of there. We the People need a pro American businessman. Not a 45 yr corrupt swamp rat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:49:16 </td>
   <td style="text-align:left;"> $AAPL going to 150 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:47:31 </td>
   <td style="text-align:left;"> $AAPL .,. have a great night everyone!!!! Peace!  Isaiah 40:28-31
Do you not know? Have you not heard? The LORD is the everlasting God, the Creator of the ends of the earth. He will not grow tired or weary, and his understanding no one can fathom. He gives strength to the weary and increases the power of the weak. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:45:29 </td>
   <td style="text-align:left;"> $AAPL annual revenue from Russia is estimated around $2.5 billion, less than 1% of Apple’s total sales </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:39:46 </td>
   <td style="text-align:left;"> $AMZN $AAPL $GOOG $NVDA 
🌬🧨💣... 
&amp;quot;The Chinese people are firmly determined to defend national sovereignty and territorial integrity,&amp;quot; Chinese Foreign Ministry spokesman Wang Wenbin told a media briefing here when asked about the American officials visit. 
 
&amp;quot;I wonder what is the US intention behind this high part of this passage of USS Johnson. If it intends to embolden Taiwan&amp;#39;s independent separatist forces, then it will only accelerate the fall of Taiwan independence forces and the US will pay a heavy price for his adventurous acts, Wang said. 
 
If the US intends to intimidate China by this, then, in front of the 1.4 billion Chinese people united in their steely determination, the so-called military deterrence will be nothing but scrap metal, he said. 
 
&amp;quot;Such US tricks involving sailing across the Taiwan Strait will better leave the show to those obsessed with hegemony, Wang said. 
 
https://www.business-standard.com/article/international/china-warns-us-of-heavy-price-for-backing-taiwan-s-independence-122030100948_1.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:35:54 </td>
   <td style="text-align:left;"> $AAPL $AMZN $BA This rings true with folks on Stocktwits… why would you follow and take trades from fly by night account holders here with no proven track record? 🥸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:35:21 </td>
   <td style="text-align:left;"> $AAPL Just now China to tell Russia to end war in Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:34:17 </td>
   <td style="text-align:left;"> $AAPL $GBTC $hood $BAC  $LCID  🤷‍♂️📈🤯🤯🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:32:50 </td>
   <td style="text-align:left;"> $SPY where is my state of union pump? $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:32:10 </td>
   <td style="text-align:left;"> $INTC $SOFI $TSLA $AAPL $AMD Holy buys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:23:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple, Ford other big American brands join corporate wave shunning Russia https://www.stck.pro/news/AAPL/23678865 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:22:37 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:16:12 </td>
   <td style="text-align:left;"> $AAPL - Exercise or conversion by Albert Gore of 1986… https://www.macroaxis.com/invest/story/AAPL/23347935/Exercise-or-conversion-by-Albert-Gore-of-1986-shares-of-Apple-subject-to-Rule-16b-3 #insidertrading #stocks #fintechnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:03:10 </td>
   <td style="text-align:left;"> Portfolio prediction for next week: Apple( $AAPL ),… https://www.macroaxis.com/invest/stock-buy-or-sell?s=AAPL,ASPS,AES,FE,FHN,AN,INTU,ISOLF,LNC,DUK,BAC,WMB #canada #canadian_equities #CA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 08:00:49 </td>
   <td style="text-align:left;"> $AAPL thank u 💎🇺🇦🍏🇺🇦💎🙏🏻 

https://www.cnn.com/2022/03/01/tech/apple-russia/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:59:31 </td>
   <td style="text-align:left;"> Silver approaching the Stage 2 breakout level &amp;amp; US Stocks Watchlist - 1 March 2022 
 
There were 20 stocks for the US stocks watchlist today. $AAPL, $PANW, $TSLA, $WPM + 16 more... 
 
➜ Members login to view the full post 
 
#stocks #trading #investing #money 
 
https://www.stageanalysis.net/blog/113025/us-stocks-watchlist-1-march-2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:54:50 </td>
   <td style="text-align:left;"> $AAPL ... I hope every &amp;quot;Chicken-Shit&amp;quot; bought this dip!... $175  is commin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:52:36 </td>
   <td style="text-align:left;"> $AAPL nevef thought I’d see Apple care. Must be an angle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:51:38 </td>
   <td style="text-align:left;"> $AAPL so my 4/1 $190c gonna pay or what? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:51:25 </td>
   <td style="text-align:left;"> $AAPL absolutely pointless movements ah. Pumps to .51 to only drop back down to .31 nearly immediately. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:51:00 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 48.4K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:44:39 </td>
   <td style="text-align:left;"> $AAPL $MSFT $BAC $DIS $T  top 5 stocks held by congress </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:42:23 </td>
   <td style="text-align:left;"> the top weighted  holdings of the S&amp;amp;P 500 that are also in the Dow Jones   
$AAPL $MSFT $UNH $JNJ  $JPM  are the top 5. The algos are programmed to where if one of these stocks sell off another one will go up just enough in order to counter the sell off in the overall  index/dow jones. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:40:35 </td>
   <td style="text-align:left;"> $AAPL 155-150 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:37:06 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Pauses All Product Sales in Russia https://www.stck.pro/news/AAPL/23677047 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:36:14 </td>
   <td style="text-align:left;"> $AAPL Last couple weeks have been rough, but I&amp;#39;m very optimistic overall.  Perhaps the boogieman/interest rate hike effects won&amp;#39;t be as bad as anticipated. Here&amp;#39;s some data from how the market has reacted during previous rate hikes: https://youtu.be/ePBe3zNy50A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:34:26 </td>
   <td style="text-align:left;"> Just getting in &amp;amp; looking at the day, Not bad.  
I had the financial media on in the car but hadn&amp;#39;t looked at the Markets since noon, 
The way the made it sound I was expecting $baba to be at $30, $aapl at $40 &amp;amp; the Market  down 6000 points.  
 
They&amp;#39;re so full of drama </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:33:03 </td>
   <td style="text-align:left;"> $V $MA $AAPL all 3 today reported taking Russia out of the mix today .  Should be some continued selling pressure in the coming days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:29:47 </td>
   <td style="text-align:left;"> $AAPL Apple raised iPhone production to 85.5M in Q4 2021
https://appleinsider.com/articles/22/03/01/apple-raised-iphone-production-to-855m-in-q4-2021 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:29:03 </td>
   <td style="text-align:left;"> $SOFI ON CNBC after earning. &amp;quot;This is not just a strong quarter earning.  I never seen anything like this in the history of fintech.&amp;quot; $MSFT $AAPL $AMZN $FB  
https://www.youtube.com/watch?v=Nv6hLXSk44s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:28:31 </td>
   <td style="text-align:left;"> $AAPL   Several Russian Subs can be seen surfaced while the sailors are fishing so they can eat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:26:44 </td>
   <td style="text-align:left;"> $AAPL $SPY bearish opening and ending possibly bullish. Depends on headlines overnight and what Powell may say tomorrow given the predicament but likely opening red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:26:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:25:08 </td>
   <td style="text-align:left;"> $AAPL I think Apple should buy the Makers of VALVE STEAM DECK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:21:44 </td>
   <td style="text-align:left;"> $AAPL Between Powell and Russia our financial portfolio is screwed for years to recoup. Always a sad story. Shameful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:21:32 </td>
   <td style="text-align:left;"> $SPY $AAPL $NVDA $USO $DRIP 
👇 Tomorrow 🥶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:20:41 </td>
   <td style="text-align:left;"> Apple Halts Sales in Russia, Restricts Russian News Sites  $AAPL $BP $UPS $FDX $DIS 

https://newsfilter.io/a/a6ae0f7a4ff59179bb75b29ac2f74bec </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:16:55 </td>
   <td style="text-align:left;"> $AAPL I think Putin and Biden need to put on some boxing gloves and make it a pay-per-view worldwide can you imagine how much money they would make for that event I would pay up to $500 just to watch this.

$TSLA $AMZN $FB $XOM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:16:16 </td>
   <td style="text-align:left;"> $AAPL Well done Apple. Slava Ukraini! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:05:47 </td>
   <td style="text-align:left;"> $DPRO $NVDA $SPY $AAPL People get scared when there is a dip of stocks in the market. But this is the moment you&amp;#39;ve been waiting for  years. Buy all you can and hold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 07:02:51 </td>
   <td style="text-align:left;"> $AAPL futuesss are green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:57:44 </td>
   <td style="text-align:left;"> $AAPL 
Hahahha, took you long enough Tim Commie.  https://www.cnbc.com/2022/03/01/apple-halts-product-sales-in-russia-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:57:01 </td>
   <td style="text-align:left;"> $AAPL so is Apple halting sales with a big ass country a good thing here? 😅😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:56:57 </td>
   <td style="text-align:left;"> :) 
 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:50:58 </td>
   <td style="text-align:left;"> $AAPL 

https://www.cnbc.com/2022/03/01/apple-halts-product-sales-in-russia-.html?utm_content=Main&amp;amp;utm_medium=Social&amp;amp;utm_source=Facebook&amp;amp;fbclid=IwAR18LlKeB4c0IB2c87MsD4AbZw14-LqvQylglX711VxSvIRRBxD8s_5Crv4#Echobox=1646168235 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:46:30 </td>
   <td style="text-align:left;"> $AAPL all sales suspended in Russia
I’m proud of🍏 I’m all in
U did good👍👍👍👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:45:46 </td>
   <td style="text-align:left;"> $SPY $XBI $NKE $AAPL $AKBA 

The international union finally started to sanction russia.

No more symbolic sanctions anymore.

It already hit the russian banks and the rubels.
Many russians start to withdraw much money.

Many nations even start to freeze trillions of russians assets.

With the SWIFT ban several russian banks which have subsidaries in europe are close to be bankrupt like Sberbank.

The impact is higher than if Evergrande would be bk. 

When the margin calls will hit a chain reaction will even hit the european market.

Apple and Nike stop to sell in russia. The news are bad but on the bright side how can they sell their products if a currency fell so sharp +heavy sanctions. It is good for them to stop to sell till they can adjust a new price when war stops.

Maybe FED will delay rates or the goverment will support the population because of the energy prices.

The war did not evolve like how Putin predicted. Even China and several Oligarch stopped their support slowly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:44:30 </td>
   <td style="text-align:left;"> $AMD $AAPL $TSLA $RIVN  
Tech continues to lag on the pops. 
 
https://www.youtube.com/watch?v=KCQByITCXbA&amp;amp;feature=youtu.be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:44:05 </td>
   <td style="text-align:left;"> $VERB that $AAPL Apple pr that came out about David Meltzer being Apple&amp;#39;s producer for live stream content, did anyone find out the name of David Meltzers company.

Is it David Meltzer&amp;#39;s shoppable streaming content powered by Verb? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:41:32 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL), Google Inc. (NASDAQ: $GOOG) – Wish You Could Have Invested In Fidget Toys A Year Ago? This Startup’s High-Tech Gadget May Be Your Second Chance https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-google-inc-nasdaqgoog-wish-you-could-have-invested-in-fidget-toys-a-year-ago-this-startups-high-tech-gadget-may-be-your-second-chance/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:39:28 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple: It had suspended all product sales in Russia https://www.stck.pro/news/AAPL/23674455 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:38:46 </td>
   <td style="text-align:left;"> 10 Information Technology Stocks Whale Activity In Today’s Session $AAPL $INTC $CRM $KD $MSFT https://www.billionaireclubcollc.com/10-information-technology-stocks-whale-activity-in-todays-session-5/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:31:45 </td>
   <td style="text-align:left;"> $SOFI Hey shorts , Marge is calling for you! Pick up the ☎️ $AAPL $MSFT $GOOG $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:30:41 </td>
   <td style="text-align:left;"> $AAPL no blue iMessage for Russia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:27:50 </td>
   <td style="text-align:left;"> $PLTR $AAPL $TSLA $UBER 

https://www.fool.com/investing/2022/03/01/lockheed-and-palantir-popped-boeing-stock-dropped/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:27:48 </td>
   <td style="text-align:left;"> $AAPL - - -  SHHssshhhhh! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:26:12 </td>
   <td style="text-align:left;"> $AAPL Just buy the dip in this dead market or just hold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:25:50 </td>
   <td style="text-align:left;"> $OZON $FB $AAPL Do you guys remember this? https://youtu.be/MNxEDomUlXw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:25:46 </td>
   <td style="text-align:left;"> $AAPL Gonna rise in the long run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:24:09 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/f8uA-7jBBN0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:21:05 </td>
   <td style="text-align:left;"> $SPY $AAPL has had no real pullback yet. Makes me nervous to go building larger LT positions until we see something a lil more organic, well I&amp;#39;d even take all natural at this point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:18:10 </td>
   <td style="text-align:left;"> $VUZI $FB $AAPL $GOOGL 
 M&amp;amp;A in the offing? 

Remember Paul the strongest word in sales is NO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:14:01 </td>
   <td style="text-align:left;"> Apple $AAPL stops product sales in Russia, adding to pressure from shippers, carmakers 
 
https://www.futuresandoptions.gr/en/market-moving-news/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:13:24 </td>
   <td style="text-align:left;"> $AAPL tbf, i am pretty sure we stopped sales in Russia because of the Currency BS 😂 🤣 and its being painted as a moral effort. Calls on Apple!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:11:32 </td>
   <td style="text-align:left;"> $AAPL apple 🍏 more like lemon 🍋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:09:07 </td>
   <td style="text-align:left;"> $aapl still a bull flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:07:28 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Mutually Assured Destruction Money!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:06:50 </td>
   <td style="text-align:left;"> $AAPL Big day tomorrow for stocks!! I can feel it! Just my 2 cents </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:04:46 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL C&amp;#39;mon Doc!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:03:04 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $HOOD Don&amp;#39;t sweat it fam! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:01:28 </td>
   <td style="text-align:left;"> $AAPL 165 tomorrow but will it hold? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:00:39 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-01 Options Analysis Video: 
https://www.youtube.com/watch?v=DzRvr4kFcqY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 06:00:25 </td>
   <td style="text-align:left;"> …Now for some fresh air. The sun will come up tomorrow. 🌞 
$AMD $AAPL $F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:59:48 </td>
   <td style="text-align:left;"> $AAPL will it go down and drag $SPY ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:59:45 </td>
   <td style="text-align:left;"> $AAPL Headed back to 175$ plus they are giving us a nice little dividend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:58:56 </td>
   <td style="text-align:left;"> $NDX Ok so 1/4 of a year down 14 3/4 years to go.  $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:58:14 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple halts all product sales in Russia and blocks state media outlets from the App Store https://www.stck.pro/news/AAPL/23672480 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:57:51 </td>
   <td style="text-align:left;"> $TSLA $AAPL $SPY $AMZN $AMC  
 
Whose else is tired of this dead market so far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:56:17 </td>
   <td style="text-align:left;"> $SOFI safe haven in SOFI should be worth $40+ 

$PTRA $JWN $FB $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:55:53 </td>
   <td style="text-align:left;"> $AAPL GIMMIE DAT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:54:21 </td>
   <td style="text-align:left;"> $AAPL $AMZN $BA Ever wonder how we are so accurate with our plays on here since 2015? This is one way right here!
Make sure you subscribe and like for all of our valuable videos 

https://youtu.be/-OUC1pVTzf4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:53:06 </td>
   <td style="text-align:left;"> $AAPL 9to5Mac: Apple halts all sales in Russian online store as Ukraine invasion continues.
https://9to5mac.com/2022/03/01/apple-halts-all-sales-in-russian-online-store-as-ukraine-invasion-continues/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:52:40 </td>
   <td style="text-align:left;"> $AAPL YEEZUS SEASONS APPROACHING F WHATEVER YALL BEEN HEARIN THE MONSTA BOUT TO COME ALIVE AGAIN!!!!!!!!! ON SIGHT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:52:13 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/PtFYrui3UEk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:51:34 </td>
   <td style="text-align:left;"> $AAPL Negative catalyst. Should be down by 20%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:50:59 </td>
   <td style="text-align:left;"> $AAPL $FB the US is paying Russia $70m dollars a day to purchase oil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:50:34 </td>
   <td style="text-align:left;"> $AAPL the halt in Russia may be bad news for Russia, but the rest of the world will see this as good news.

Anyways 3/11 155 puts

If there’s one day Joe Byron can bring bulls pain it might be tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:49:55 </td>
   <td style="text-align:left;"> $AAPL Russian have their Android devices, they don&amp;#39;t hypocrat corporations from America. I see this stock plunges below 100$ sooner than later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:48:32 </td>
   <td style="text-align:left;"> $AAPL March 18 : 167.50 : CALLS is the play here 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:47:40 </td>
   <td style="text-align:left;"> $AAPL I bought my first share today it feels good too being 18 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:47:05 </td>
   <td style="text-align:left;"> $XCUR $TSLA $AAPL come check the party at XCUR! Still not too late. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:46:33 </td>
   <td style="text-align:left;"> ‘Undisguised terror’: Russia’s Kharkiv strike chills Ukraine $SPY $QQQ $DJIA $TSLA $AAPL https://www.billionaireclubcollc.com/undisguised-terror-russias-kharkiv-strike-chills-ukraine/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:46:28 </td>
   <td style="text-align:left;"> $AAPL hey can someone tell me the annual average return on apple please? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:45:35 </td>
   <td style="text-align:left;"> $AAPL Well that sucks. May as well go back to work, or not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:45:00 </td>
   <td style="text-align:left;"> $AAPL going to $150 and lower! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:39:23 </td>
   <td style="text-align:left;"> $AAPL Apple is making a sacrifice by not selling products in Russia. Investors should reward them with a higher P/E, accounting for the drop in expected earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:36:56 </td>
   <td style="text-align:left;"> $AAPL so can someone eplain how a company that is seeing falling sales post pandemic is going to increase sales by stopping sales? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:36:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $AAPL $JPM  
 
Wish I could say that things get better post State of the Union, but history suggest to otherwise. Always know the data! 
 
S&amp;amp;P 500 and 10-year Treasury Yield performance 1 month before and after State of the Union since 1950, and... 
 
When the S&amp;amp;P 500 had traded down &amp;gt; 5% in the month leading into the SOTU! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:36:04 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 314.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:35:40 </td>
   <td style="text-align:left;"> $AAPL everyone should understand the halt situation is actually bullish as this is just a cause for a reaction and as you see the price of the Russian Currency right now should indicate no one is buying Apple products right now and hoarding cash. This has a neutral effect if anything but most definitely not a bearish one. So 167 by March 4th </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:35:37 </td>
   <td style="text-align:left;"> $AAPL Apple halts product sales in Russia, only after Ukraine requested it. Would have been nice if Tim Cook took the initiative. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:34:42 </td>
   <td style="text-align:left;"> $AAPL you wanna bully other people and be assholes, then we&amp;#39;ll take all our toys out the sandbox. All you&amp;#39;ll have left is your shitty vodka. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:34:25 </td>
   <td style="text-align:left;"> $AAPL $AMZN $DIS Love seeing our traders STACK!
No BS clown excuses here at OP! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:34:24 </td>
   <td style="text-align:left;"> My guess is $AMD will outperform all tech tomorrow and be up to $125+

$NVDA $AAPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:34:09 </td>
   <td style="text-align:left;"> $AAPL 

Wow I am impressed that’s very humanitarian super I mean humanitarian like thank you Apple.    🍏 $SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:34:03 </td>
   <td style="text-align:left;"> $AAPL Took the Jan 24 low last week.  We like looking for a decline further down still where buyers can enter at the blue box for a bounce.  We don’t like to sell it short this close to the blue box though, but we do like to buy it lower at the extreme 100% area.  #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:33:32 </td>
   <td style="text-align:left;"> $AAPL Apple halts product sales in Russia   https://www.cnbc.com/2022/03/01/apple-halts-product-sales-in-russia-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:32:47 </td>
   <td style="text-align:left;"> $AAPL cuts Russia off from products and services $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:31:38 </td>
   <td style="text-align:left;"> $AAPL Apple standing with Ukraine is bullish. Apple making a statement. Let&amp;#39;s go! Gap up tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:31:03 </td>
   <td style="text-align:left;"> $AAPL - Apple is suspending all online sales in Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:29:41 </td>
   <td style="text-align:left;"> $AAPL  well .. Apple halting import to Russia and sales to Russia ... that&amp;#39;s expected .. due to Rouble devaluation and ongoing geopolitical tension .. plus protect the company from hefty penalities when sanction hits. It will  be harder to get money transfered if sold in Russia territory due to SWIFT plan. This is smart move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:29:26 </td>
   <td style="text-align:left;"> $AAPL Apple cuts of Russia, but still has lots of work to do.  Cut off all services, support, Apple store, Apple pay. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:28:06 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA 
 
hey, who&amp;#39;s ready to hear pappa Joe speak again! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:28:00 </td>
   <td style="text-align:left;"> The entire stock market history in 10 minutes: 
 
$SPY $SPX $DJIA $AAPL $AMZN  
 
https://youtu.be/EraN5AEY0Ow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:27:14 </td>
   <td style="text-align:left;"> $AAPL the Russian apple prohibition has begun. There will be movies in the future of Russian gangsters trapping apple products </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:26:11 </td>
   <td style="text-align:left;"> $AAPL am I the only one swinging my short position I opened this AM ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:25:24 </td>
   <td style="text-align:left;"> $AAPL

Punishing the citizens of Russia for something their government is doing? Not cool apple. Not cool. https://finance.yahoo.com/news/apple-cuts-russia-off-from-its-products-and-services-211438593.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:25:14 </td>
   <td style="text-align:left;"> $AAPL and the other FAANG stock are using Mental chart gymnastics to make you believe the price is going up.. but in reality it&amp;#39;s Mud in your Face.. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:25:04 </td>
   <td style="text-align:left;"> $AAPL 

Russians will find a way to get Apple products </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:25:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 8.00, indicating great health for $AAPL. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:24:54 </td>
   <td style="text-align:left;"> $AAPL Regular &amp;amp; Hidden Bearish Divergence 2hr Chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:24:47 </td>
   <td style="text-align:left;"> $AAPL Cutting off Russia from their  Products and Services?-- Thats it, the people will overthrow the Government $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:24:44 </td>
   <td style="text-align:left;"> $SOFI THE EPS IS INSANE. 

Growth of SOFI is like no other fintech

This is like buying AMD when it used to be $5

Folks, THIS IS YOUR OPPORTUNITY. SEIZE IT!

$AMD $AAPL $MSFT $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:24:44 </td>
   <td style="text-align:left;"> $AAPL No, you can&amp;#39;t buy Apple Putin 😯😯 That&amp;#39;s a serious punishment! 
***Apple cuts off online sales and product exports to Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:24:14 </td>
   <td style="text-align:left;"> $AAPL Apple halting products in Russia , will this impact Apple and market ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:23:45 </td>
   <td style="text-align:left;"> $AAPL 

The next ER will be interesting… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:23:41 </td>
   <td style="text-align:left;"> $AAPL 
No way Cook does this in China if Xi invades ANYONE.
Apple and Cook the apex of hypocrisy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:22:44 </td>
   <td style="text-align:left;"> Market Bearish Engulfing Candle - Outside Day 

Market is very likely to retest lows and break lower 

$AAPL $QQQ $SPY $NVDA $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:22:36 </td>
   <td style="text-align:left;"> $AAPL I knew it lol. 😆Posted on 22nd Feb.  Easy prediction. Only morons are keep buying this overvalued stock and pumping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:22:28 </td>
   <td style="text-align:left;"> $AAPL are we going to have a war with Russia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:21:06 </td>
   <td style="text-align:left;"> $ARLO is and will continue to be an amazing company on their own, but I bet $AAPL and $GOOGL are taking notice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:20:04 </td>
   <td style="text-align:left;"> $AAPL Key News Update 
Apple halts product sales in Russia 
https://techcrunch.com/2022/03/01/apple-halts-product-sales-in-russia-following-ukraine-invasion/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:19:13 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPL Choppy day in the markets -  How are you feeling? I&amp;#39;ve been saying, this type of environment is driven by news and sentiment. At the end of the day a lot the the market is driven by the price  people are willing to buy and sell  - it&amp;#39;s human nature. 
 
Want to stay on top of real-time social momentum and sentiment? Check this out - happy to answer any questions  https://utradea.com/pricing?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220301 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:19:09 </td>
   <td style="text-align:left;"> $AAPL we are here now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:18:32 </td>
   <td style="text-align:left;"> Most Traded Contracts

$VALE March $20 Call
$VALE March $17 Put
$AAPL 04 March $167.50 Call
$VALE March $15 Put
$AAPL 04 March $165 Call
$AAPL 04 March $170 Call
$AAPL 04 March $165 Put
$AAPL 04 March $160 Put
$AMD 04 March $125 Call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:18:19 </td>
   <td style="text-align:left;"> $SPY $AAPL Beartivities update🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:18:10 </td>
   <td style="text-align:left;"> $AAPL How much are we going to get hurt from this paused production sales in Russia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:15:54 </td>
   <td style="text-align:left;"> $SPY $AAPL Apple stops selling all equipment on it&amp;#39;s online store in Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:14:50 </td>
   <td style="text-align:left;"> $AAPL $SPY get ready for bloody future. Biden speech later tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:14:23 </td>
   <td style="text-align:left;"> $AAPL bulls got in at the right time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:13:34 </td>
   <td style="text-align:left;"> $AAPL we should see $167 in the coming days and hold strong Shareholder Annual Meeting is March 4th 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:13:33 </td>
   <td style="text-align:left;"> $AAPL Apple halt sales in Russia. Now, existing users of Russia may throw all the iPhones/iPad/MacBook in the garbages. 😬 Overvalued stock. $150. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:12:04 </td>
   <td style="text-align:left;"> $AAPL $DIS $AMZN I’m seeing folks lose all their hard earned money saying/doing the most idiotic things these days while calling it trading- PEOPLE- STOP!!! Take a break and get educated… you are squandering money and being stupid! The market doesn’t care what you think. The market does what it wants - not what you want! Learn how to read the market! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:11:50 </td>
   <td style="text-align:left;"> $AAPL everyone should understand the halt situation is actually bullish as this is just a cause for a reaction and as you see the price of the Russian Currency right now should indicate no one is buying Apple products right now and hoarding cash. This has a neutral effect if anything but most definitely not a bearish one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:11:44 </td>
   <td style="text-align:left;"> $AAPL Apple pauses sales in Russia, adding to other actions related to Ukraine invasion https://www.marketwatch.com/story/apple-pauses-sales-in-russia-adding-to-other-actions-related-to-ukraine-invasion-11646169051?mod=mw_latestnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:09:58 </td>
   <td style="text-align:left;"> Recent Pelosi financial disclosure shows exercises of millions of dollars in call options in $PYPL, $AAPL, $DIS, and more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:09:33 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:08:43 </td>
   <td style="text-align:left;"> $NIO $AAPL $SPY 

https://news.sky.com/story/apple-stops-all-product-sales-in-russia-as-rt-and-sputnik-removed-from-app-store-12555128 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:06:51 </td>
   <td style="text-align:left;"> $AAPL Stopping all dealing with Russia: ~1%. Sticking it to a puffy-faced pariah dictator? PRICELESS 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:06:41 </td>
   <td style="text-align:left;"> $AAPL  They halted products sales in Russia just because the ruble is crashing and will become totally worthless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:05:39 </td>
   <td style="text-align:left;"> $AAPL $150’tomorrow. Apple halt sales in Russia minimum $500 Billion loss. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:04:37 </td>
   <td style="text-align:left;"> $AAPL Russian currency is worth next to nothing coupled
with it being nearly banned from all
exchanges, they would lose money by still
selling to them. It&amp;#39;s not a political statement
but purely economic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:04:25 </td>
   <td style="text-align:left;"> $AAPL just holddddd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:02:39 </td>
   <td style="text-align:left;"> $AAPL Halting product sales in dictatorship Russia - Is that bearish or bullish? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:02:32 </td>
   <td style="text-align:left;"> Want to see a nice clean fall overnight, down to support, then bounce!  
 
$SPY $NVDA $AAPL  
 
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:02:17 </td>
   <td style="text-align:left;"> $AAPL No FaceTime for you Putin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:02:08 </td>
   <td style="text-align:left;"> $SPY $AAPL even Apple halted sales in Russia. Damn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:01:55 </td>
   <td style="text-align:left;"> $AAPL Got a nice order in right at the close ... bounce bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:01:45 </td>
   <td style="text-align:left;"> Play what you know best... 
 
$TSLA $AMZN $AAPL  
 
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:01:35 </td>
   <td style="text-align:left;"> $AAPL desperation not a good look </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:01:16 </td>
   <td style="text-align:left;"> No more $AAPL products in Russia. Don’t drop your iPhone 📱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:01:09 </td>
   <td style="text-align:left;"> $AAPL BREAKING: APPLE HALTED ALL PRODUCT SALES IN RUSSIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:00:46 </td>
   <td style="text-align:left;"> $AAPL pretty big dump last second from 163.48 to 163.15 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:00:09 </td>
   <td style="text-align:left;"> $AAPL Let&amp;#39;s try that again - If it&amp;#39;s worth this much with revenue from Russia coming in, how much more/less will it be worth without that revenue? Well once some options expire, we&amp;#39;ll get to find out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 05:00:02 </td>
   <td style="text-align:left;"> $AAPL Closing RED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:59:27 </td>
   <td style="text-align:left;"> Apple latex99feed5c063e25aa12bf3657146f97c9AMD ↗️ 

$MSFT $INTC $NVDA   https://www.cnbc.com/2022/03/01/apple-halts-product-sales-in-russia-.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:59:23 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple halts product sales in Russia https://www.stck.pro/news/AAPL/23669667 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:59:19 </td>
   <td style="text-align:left;"> $AAPL: not the most bullish chart I&amp;#39;ve seen, tbh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:59:15 </td>
   <td style="text-align:left;"> $AMZN $AAPL $AMD Dont forget! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:58:12 </td>
   <td style="text-align:left;"> $AAPL No iPhones for u, vlad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:58:08 </td>
   <td style="text-align:left;"> $AAPL thanks for fucking my puts in the last 5 min! Hopefully opens red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:58:02 </td>
   <td style="text-align:left;"> $AAPL not bad given the news today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:56:38 </td>
   <td style="text-align:left;"> $AAPL Even Rats live in 90210 $SNES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:55:37 </td>
   <td style="text-align:left;"> $AAPL product sales in Russia halted. USA 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:54:47 </td>
   <td style="text-align:left;"> $AAPL 

Putin is kaput.

Better give Putin a way out of sanctions and a ceasefire. Putin knows he lost.

Russia is a political, social and economic shithole now.

Give Putin an easy out. Never know what he might attack or do next?

Putin is more of a danger now that ever in defeat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:54:24 </td>
   <td style="text-align:left;"> $AAPL What happens if Tim has to stop product sales in China? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:53:24 </td>
   <td style="text-align:left;"> $AAPL Wall Street likes sanctions: UK imposes sanctions on Belarusian people and organizations over Ukraine invasion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:52:53 </td>
   <td style="text-align:left;"> $CVX, $AAPL, $COIN , $DWAC  
 Biden speaking tonight! Hope you sold! Haha just kidding!  
Unless... 😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:52:40 </td>
   <td style="text-align:left;"> $AAPL $ABNB Mother Russia is CRASHING the NATION STOCK market..the opposite is suppose to happening..LET&amp;#39;S GO BRANDON $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:52:29 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $AMZN Putin has gone full throttle. The ending won&amp;#39;t be good for anyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:52:22 </td>
   <td style="text-align:left;"> $AAPL One of the big companies putting pressure on Russia and douchebag Putin. Smart move, Apple. The business community, along with the arts and sports, are standing with our NATO alliance. If you&amp;#39;re defending Putin and think he&amp;#39;s a smart genius, your priorities are severely misguided, you&amp;#39;re in an extremist cult, and you&amp;#39;re captured in un-American thinking. FUCK Putin 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:51:46 </td>
   <td style="text-align:left;"> $AAPL Very important objective observation
Apple goes so does the Market 
Look: Monthly Apple is Bearish TopDragonfly
Level of lower support on Fibonacci 
38.2%  133.35
50% is  118.00 👀

$AAPL $AMD $QQQ $NVDA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:51:32 </td>
   <td style="text-align:left;"> $AAPL Sell and save your money for bread </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:51:32 </td>
   <td style="text-align:left;"> “Russia may be using bombs to drop on innocent people, but Anonymous uses lasers to kill Russian government websites.”

🌎 Stand with 🇺🇦
$AMD ↗️ $AAPL 
$BTC.x $ETH.x $BNB.X 

🤜🏼💥Get onboard-Global hacking group Anonymous launches ‘cyber war’ against Russia 🇷🇺

&amp;gt;https://www.cnbc.com/2022/03/01/how-is-anonymous-attacking-russia-disabling-and-hacking-websites-.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:51:24 </td>
   <td style="text-align:left;"> $AAPL had to get a pump and dump in before the big speech tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:50:32 </td>
   <td style="text-align:left;"> $AAPL I told you guys this is nothing worse is coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:50:24 </td>
   <td style="text-align:left;"> $aapl bout to fall off a clif </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:50:18 </td>
   <td style="text-align:left;"> $AAPL sun 162 close it is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:50:01 </td>
   <td style="text-align:left;"> $AAPL what a joke. they are a business now philanthropists. what a sick move to shareholders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:49:41 </td>
   <td style="text-align:left;"> $GOOGL trump 2024 who gives a fuck about shithole Ukraine old news … time to rally 🦍📈🚀 $TSLA $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:49:15 </td>
   <td style="text-align:left;"> $AAPL Apple stops all services and sales in Russia $SPY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:49:09 </td>
   <td style="text-align:left;"> $AAPL Russia business gone $SBUX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:49:03 </td>
   <td style="text-align:left;"> $AAPL $SPY Tim Apple&amp;#39;s Russian sales stop will probably hurt Russians more than the sanctions by the U.S. govt 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:48:51 </td>
   <td style="text-align:left;"> $AAPL more info </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:47:43 </td>
   <td style="text-align:left;"> $TSLA $SPY $AAPL $FB Tomorrow - Powell to speak, Russia to attack aggressively with military convoy, Biden&amp;#39;s address to Russia today evening. Hell yeah I&amp;#39;m short ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:47:12 </td>
   <td style="text-align:left;"> $AAPL Russia equals approx .09% of sales </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:46:19 </td>
   <td style="text-align:left;"> $SPY apple stopped all product sales to Russia!!!! $AAPL 

Get the F* sell off going </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:46:09 </td>
   <td style="text-align:left;"> $AAPL bandwagon = engaged </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:44:43 </td>
   <td style="text-align:left;"> $AAPL lacking the push it had yesterday. This may barely finish at 163 or close closer to under 162. Not seeing any push this last 20 minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:44:13 </td>
   <td style="text-align:left;"> $AAPL Don&amp;#39;t ban iphones in Russia. Ban vodka. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:40:36 </td>
   <td style="text-align:left;"> $BAND $TWLO $TQQQ $AAPL $FB  State of Union tonight, goodness for all the Trump haters/supporters, why in the heck did anybody think Biden was the answer? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:39:56 </td>
   <td style="text-align:left;"> $AAPL Since the Putin has cleared Chernobyl which is already a toxic zone, he could launch a small tactical nuke on the site in a way that does not damage it further.  That would fucking freak the West and the World out and they will negotiate ASAP.  $QQQ $SPY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:38:56 </td>
   <td style="text-align:left;"> $SPX $SPY $AAPL to stop selling all the products in their Russian stores. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:38:45 </td>
   <td style="text-align:left;"> $AAPL sub 162 possible. Keeps creeping downward </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:38:06 </td>
   <td style="text-align:left;"> $SPY NEWS: Apple Halts All Sales From Online Store in Russia  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:36:41 </td>
   <td style="text-align:left;"> Eat sh*t pathetic Putin!

Global hacking group Anonymous launches ‘cyber war’ against Russia 🇷🇺 

🌎 Stand with 🇺🇦🙏🏼✌🏼

$AAPL $AMD ↗️ $AMZN $MSFT $TSLA  https://www.cnbc.com/2022/03/01/how-is-anonymous-attacking-russia-disabling-and-hacking-websites-.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:36:16 </td>
   <td style="text-align:left;"> $AAPL Back to normal progamming tonight on QVC. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:36:13 </td>
   <td style="text-align:left;"> $AAPL Any thoughts on which company apple is working with for the car?  Any guesses? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:34:45 </td>
   <td style="text-align:left;"> $qqq $SPY $AAPL $GLD Every night brings the possibility of a tactical nuke shoved up Ukraine’s ass.   What better time than state of the union </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:34:09 </td>
   <td style="text-align:left;"> APPLE $AAPL HAS STOPPED SELLING ALL EQUIPMENT ON ITS OFFICIAL ONLINE STORE IN RUSSIA… http://dlvr.it/SKtmQq #NEWS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:34:09 </td>
   <td style="text-align:left;"> $AAPL What&amp;#39;s more scary that FED and war? Brandon on TV. Hope he can stand up that late in the night without falling. Tear that up biatch aka fck Pelosi. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:33:54 </td>
   <td style="text-align:left;"> $AAPL  LFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:32:36 </td>
   <td style="text-align:left;"> Some top tech sector flow coming in above ask 
 
$AMD - $1.7M call sweep 
$BIDU - $433K call sweep 
$AAPL - $332K call sweep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:30:36 </td>
   <td style="text-align:left;"> $SPY whoa $AAPL stopped selling online in Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:28:45 </td>
   <td style="text-align:left;"> $SPY March 1st... Looks the FED finally turn the printers off.
$AAPL $AMD $QQQ $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:28:28 </td>
   <td style="text-align:left;"> $AAPL $ABNB   C NBC and FOXX KEEP TALKING) ABOUT THE SELLOFFS....}
YOU WOULD THINK THERE NO END TO THIS DOCUDRAMA.. UKRAINE\RUSSIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:28:13 </td>
   <td style="text-align:left;"> $AAPL come on, just give it to me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:27:57 </td>
   <td style="text-align:left;"> Short position in $AAPL reported by SMSAX - SIMT Multi-Strategy Alternative Fund Class F -&amp;gt; https://fintel.io/sosh/us/aapl?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=sosh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:24:42 </td>
   <td style="text-align:left;"> $TSLA a strong Green Day will push $TSLA $AMZN $AAPL and other tech stock much higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:16:46 </td>
   <td style="text-align:left;"> $AAPL while holding up really good, has lost its momentum for now. Break that declining trend-line off of the January highs, and it should spark some renewed interest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:13:16 </td>
   <td style="text-align:left;"> $AAPL Wish AAPL would announce they were moving production out of China </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:12:37 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

FLUSH IT!!!!
                       FLUSH IT!!!!!
                                                FLUSH IT!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:11:39 </td>
   <td style="text-align:left;"> $AAPL jerkin ya chain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:11:28 </td>
   <td style="text-align:left;"> $AAPL lol, rug pull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:11:09 </td>
   <td style="text-align:left;"> $AAPL news jus came out apple suspending all sales in russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:09:22 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

Oh man, not sure what fud is left in the tank for the fud backed bear to use as ammunition. Looks like the fed backed bull is stronger than ever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:08:58 </td>
   <td style="text-align:left;"> $BTC.X $AAPL $QQQ $DPRO I&amp;#39;m in, dangled my feet a little too long in the water...but I&amp;#39;m in...and I don&amp;#39;t think I&amp;#39;ll regret it, imo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:08:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $AAPL $IWM  
SPY Year to date by sector </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:08:01 </td>
   <td style="text-align:left;"> $AAPL why anyone would short apple with the company having a catalyst in a couple days is beyond me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:08:00 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:06:59 </td>
   <td style="text-align:left;"> $AAPL wow only took all day to make that 50% on my puts and 5 minutes to lose it all. Wow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:04:23 </td>
   <td style="text-align:left;"> $AAPL one of the best stocks, don’t judge it by fake news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:04:05 </td>
   <td style="text-align:left;"> Is Pathetic Putin a 🧨💣💥

The walls are closing in.. what will he do..  🙏🏼✌🏼
&amp;gt;https://www.sbnation.com/2022/2/25/22950663/sports-addressing-russia-ukraine-uefa-fifa-f1

$AAPL $AMD ↗️ $AMZN $MSFT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:04:00 </td>
   <td style="text-align:left;"> $AAPL classic 3pm frantic buying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:03:55 </td>
   <td style="text-align:left;"> $AAPL let’s end positive! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:03:41 </td>
   <td style="text-align:left;"> $AAPL Looks like China willing to assist in diplomatic talks to end the war...is a big deal! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:01:48 </td>
   <td style="text-align:left;"> $AAPL kamala
Harris is worse then biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:01:07 </td>
   <td style="text-align:left;"> $AAPL Brandon hates BULLS
😀 Here&amp;#39;s the proof. Aplle a 3Trillion MC and can&amp;#39;t hold it&amp;#39;s daily gains ..$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 04:00:23 </td>
   <td style="text-align:left;"> $AAPL not many sanctions left. Putin not backing down. Likely war time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 03:59:58 </td>
   <td style="text-align:left;"> $AAPL Ukraine’s Foreign Minister Dmytro Kuleba said on Tuesday that the Chinese are “ready to seek a peaceful solution” in diplomatic talks to end the war Russia has launched on Ukraine.  
 
Earlier on Tuesday, Kuleba had a phone call with his Chinese counterpart Wang Yi. Without calling Russia’s military act in Ukraine an “invasion,” Wang had said that China respects every country’s sovereignty and territorial integrity, and he urged Ukraine and Russia to solve the crisis through negotiations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 03:59:24 </td>
   <td style="text-align:left;"> $AAPL Beijing is &amp;quot;ready to seek peaceful solution&amp;quot; to Ukraine-Russia conflict, Ukrainian foreign minister says </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 03:54:58 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Looks like puts came with an astronaut suit. 🧑‍🚀 🌙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 03:51:45 </td>
   <td style="text-align:left;"> $SPY Alerted at 11.10 hit 78.00 today
600% percent swing trade.
$LMT $TSLA $POWW $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 03:48:14 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 03:47:55 </td>
   <td style="text-align:left;"> $AAPL 

No ceasefire and way out of sanctions for sputum and Russian convoy attacks, market tanks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-02 03:47:54 </td>
   <td style="text-align:left;"> $xop Oil at $100 means higher gas prices, higher shipping rates, higher airfare and higher event-dining costs (bc of $UBER taxi).  
All of this is a tax on the consumer and consumer spending is 2/3 of the US economy. Also, I have been adding to crypto on dips for longer term  ing with profits made from oil/energy trades as well as $msft $aapl $fb longer term holds (still think another dip could come for those as well though so still mostly cash and margin).  @meghantay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 11:02:11 </td>
   <td style="text-align:left;"> $TSLA Biden - Beat the opiod epidemic! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 11:02:10 </td>
   <td style="text-align:left;"> $TSLA no love for Tesla once again by Biden. He’s making sure GM and Ford beat the brakes off Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 11:01:48 </td>
   <td style="text-align:left;"> $TSLA charlie brown&amp;#39;s teacher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 11:01:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $TSLA is 7.00. This indicates good health for $TSLA. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 11:00:50 </td>
   <td style="text-align:left;"> $TSLA Biden on transgender rights </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 11:00:26 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $865.0 CALLS for Wednesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:59:48 </td>
   <td style="text-align:left;"> $SPY $BTC.X $TSLA 

Where they just clapping at him saying build a wall and fund the police?!?!?!?! 

I can’t even, the eft seriously believe the people have the memory of goldfish 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:59:42 </td>
   <td style="text-align:left;"> $MMAT $TSLA $QQQ Real price will come out soon, Follow price target; chatx.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:59:40 </td>
   <td style="text-align:left;"> $TSLA war is bullish for Tesla right?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:58:44 </td>
   <td style="text-align:left;"> $TSLA Biden on immigration </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:58:28 </td>
   <td style="text-align:left;"> $BABA $BTC.X $TSLA $TWTR They have helped me to grow my account to almost 2.5 million.... 100% recommend joining! 
 
It&amp;#39;s free joining ~~~~🚀 discord.io/7GPFADBFK5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:57:25 </td>
   <td style="text-align:left;"> $TSLA POOF..  Just Like That.. Not ONE PERSON with a MASK in that room .. In One Day..  We were Played People....  Go Elon..!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:56:23 </td>
   <td style="text-align:left;"> $SPY $TSLA $BTC.X 

“Assault weapons” aka semi auto rifles…

Wow he really wants all of Washington to turn red doesn’t he? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:56:06 </td>
   <td style="text-align:left;"> $TSLA 

Here goes your second amendment!! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:55:48 </td>
   <td style="text-align:left;"> $MMAT $TSLA $QQQ Real price will come out soon, Follow price target.. chatx.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:55:11 </td>
   <td style="text-align:left;"> $TSLA Answer not to defund the Police, but to Fund them -Keep communities safe- Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:54:26 </td>
   <td style="text-align:left;"> $TSLA $FSR $RIVN lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:54:17 </td>
   <td style="text-align:left;"> $TSLA once we tap Natl. This opening at $950 tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:53:59 </td>
   <td style="text-align:left;"> $TSLA so are my calls ok? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:53:51 </td>
   <td style="text-align:left;"> $TSLA Biden on COPS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:53:32 </td>
   <td style="text-align:left;"> $TSLA Why should there be a minimum wage of $15? Just curious. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:52:37 </td>
   <td style="text-align:left;"> $TSLA nap time.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:52:07 </td>
   <td style="text-align:left;"> $TSLA  tomorrow interest goes up , potus told make in america not reduce pay JMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:51:53 </td>
   <td style="text-align:left;"> $TSLA he ready to nap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:51:19 </td>
   <td style="text-align:left;"> $TSLA the battery is drained. 
 Wait.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:51:03 </td>
   <td style="text-align:left;"> $TSLA  7 hundo soon yea? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:50:56 </td>
   <td style="text-align:left;"> $RIVN musk going after $RIVN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:50:54 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AMZN 

Big corporations will get taxed 15%.

Entities earning less than $400k won&amp;#39;t get taxed further.

Biden now pushing vaccines and boosters. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:50:07 </td>
   <td style="text-align:left;"> $TSLA WE will be ready for anyy new Covid variant!- Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:49:20 </td>
   <td style="text-align:left;"> $TSLA hurry.. Wow.. run out battery.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:49:11 </td>
   <td style="text-align:left;"> $SPY $TSLA $BTC.X 

I may have laughed more then I have the past month…but in all honesty this is the worst state of the union in my lifetime. 

Hopefully the Uranium’s aren’t watching… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:48:20 </td>
   <td style="text-align:left;"> $TSLA Biden on Covid and vaccinations! 
 
Get a booster! -Biden 
 
Pfizer pill! - Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:47:40 </td>
   <td style="text-align:left;"> $TSLA $AMZN

SMALL RESISTANCE FORCE WILL TURN INTO WAR. DONT listen to PUMPERS. WAITING A MONTH TO GO LONG IS NOT GONNA HURT IF U R READY TO HOLD FOR 1-2+ years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:47:17 </td>
   <td style="text-align:left;"> $TSLA Worst short candidate in humanoid history. RIP bears. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:47:15 </td>
   <td style="text-align:left;"> $TSLA Biden sucks - he’s pumping F and GM for what ??? TSLA is king of EV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:47:15 </td>
   <td style="text-align:left;"> $TSLA bots here again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:47:11 </td>
   <td style="text-align:left;"> $TSLA  throwing that paper like u just won the lotto </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:47:08 </td>
   <td style="text-align:left;"> $TSLA 

Elon vs Biden 
Boxing match 🥊🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:46:53 </td>
   <td style="text-align:left;"> latex19de2a02fac6e6afb76b3ac0db1fd43cAAPL 968k (57% call/43% put)
$AMD 722k (64% call/36% put)

Lynk in bayo for option trading ideas and alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:46:00 </td>
   <td style="text-align:left;"> $TSLA MInmimum Wage to $15.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:45:25 </td>
   <td style="text-align:left;"> $TSLA has secured a lithium supply agreement with Core Lithium for 2023-2026 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:45:25 </td>
   <td style="text-align:left;"> $TSLA We will be lit tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:45:16 </td>
   <td style="text-align:left;"> $TSLA Biden said that Tesla beats every EV! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:44:17 </td>
   <td style="text-align:left;"> $VOLT.INU.X 100x + 
Ask Elon the $TSLA $waymo #technokinga Im off to space </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:44:09 </td>
   <td style="text-align:left;"> $TSLA biden just said he loves tesla wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:43:58 </td>
   <td style="text-align:left;"> $SOFI $TSLA $AAPL $GOOG  does the market turn after the speech? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:43:39 </td>
   <td style="text-align:left;"> $TSLA damn…potus really hates Tezzy huh? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:43:27 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB $TSLA  

I’d be embarrassed and feel like a wimp being 2nd gentleman </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:43:18 </td>
   <td style="text-align:left;"> $TSLA GM and F hahahha. Cause Sleepy Jose can&amp;#39;t says TSLA not in script.  Hahahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:41:51 </td>
   <td style="text-align:left;"> $TSLA Everyone making &amp;lt; $400,000 will not pay a single penny 
 
But wealthy and corporations need to pay &amp;quot;their fair share&amp;quot; of taxes  
15% min imum tax rate for corporate entities - Global minimum Tax rate (Section 61 Title USC (Tax Code)) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:41:04 </td>
   <td style="text-align:left;"> $TSLA $SPY THANKS BIDEN FOR INCREASING TAXES ON CORPORATIONS, this should crash the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:40:22 </td>
   <td style="text-align:left;"> $TSLA sound like communist..  listen .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:40:21 </td>
   <td style="text-align:left;"> $TSLA That&amp;#39;s why Tesla stock is a no touch here, President Biden clearly prefer Ford and GM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:40:18 </td>
   <td style="text-align:left;"> &amp;quot;Lower the price of EV vehicles.&amp;quot; Biden quoted. $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:39:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 
Yeah cut all the costs. But we dont know who pays for it! Probably retail investors!! Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:38:43 </td>
   <td style="text-align:left;"> $SPY BIDEN IS PUMPING THE WHOLE MARKET MORE THAN THE FAANG STOCKS IN ONE SPEECH!!! THAT IS MY PRESIDENT!  $AMZN $MSFT $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:38:39 </td>
   <td style="text-align:left;"> $TSLA  opening a plant in detroit BABA (bring america back again) JMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:38:36 </td>
   <td style="text-align:left;"> $TSLA Why can’t AOC just do an only fans. She is a good looking Latina </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:38:31 </td>
   <td style="text-align:left;"> $TSLA The stupid ass in charge says Ford and Gm will be investing 10 billion in EV&amp;#39;s , ahahahahahahah,  what a dumb fuck ignoring the company who paved the way and is light years ahead. .. And fuck off bears,  Tesla doesn&amp;#39;t need advertising!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:38:25 </td>
   <td style="text-align:left;"> $TSLA 

This President has just repeated the same mistake !

Saluted $F $GM (make EVs in Mexico ) for billions of dollars investment in EVs in US not even thanking Tesla that  had billions of dollars investment 14yrs ago and Just finished the biggest EV factory GF Austin in the world !! 

Sad ! Seriously n 

I’m so sorry Elon Tesla !! @elonmusk 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:38:04 </td>
   <td style="text-align:left;"> $TSLA I heard you’re not gunna have to pay at the pump. Teslas for everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:38:04 </td>
   <td style="text-align:left;"> $TSLA Biden  just talked about electric vehicles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:37:59 </td>
   <td style="text-align:left;"> $TSLA why isn&amp;#39;t he wearing a tesla hat at the sotu? Smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:37:29 </td>
   <td style="text-align:left;"> $TSLA No one wants to drive a pos ford joe, cmon man! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:37:01 </td>
   <td style="text-align:left;"> $TSLA Buy American* (*except for Tesla) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:36:42 </td>
   <td style="text-align:left;"> $TSLA Brandon is a full blown fucking ass clown 🤡🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:36:40 </td>
   <td style="text-align:left;"> $TSLA y&amp;#39;all need ti calm the hell down.  Market is up 100+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:36:21 </td>
   <td style="text-align:left;"> $TSLA F and GM is American brand.. Tesla is communism.  Hahahhaha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:35:43 </td>
   <td style="text-align:left;"> State of Union update: Joe Biden mentioned $F and $GM for his EV picks. Sorry $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:35:21 </td>
   <td style="text-align:left;"> $TSLA I can&amp;#39;t believe biden didn&amp;#39;t invite elon to the sotu. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:35:14 </td>
   <td style="text-align:left;"> $SPY Biden mentioned $F and $GM again at the State of the Union address. No mentioning of $TSLA.

Tesla lives matter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:34:41 </td>
   <td style="text-align:left;"> $TSLA back to sleep. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:34:28 </td>
   <td style="text-align:left;"> $TSLA sit down grandpa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:34:26 </td>
   <td style="text-align:left;"> $TSLA BIDEN MENTION TESLA! why do you not mention the best EV company in America! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:34:12 </td>
   <td style="text-align:left;"> $TSLA hahahahha..  old sleepy using back .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:34:10 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-01 Daily Forecast Video: 
https://www.youtube.com/watch?v=fBe2X098rRY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:34:10 </td>
   <td style="text-align:left;"> $TSLA only way to show the president whose boss, is only buy TSLA cars. Fords and GM are pieces of shits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:34:10 </td>
   <td style="text-align:left;"> $TSLA this guy talkin bout lower your cost while he raises corp taxes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:34:08 </td>
   <td style="text-align:left;"> $TSLA the funny thing is Elon probably has more power than the president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:34:02 </td>
   <td style="text-align:left;"> $TSLA Biden hates puppies and kittens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:33:51 </td>
   <td style="text-align:left;"> $TSLA Forgetting Tesla &amp;amp; Elon is like mentioning Bing/Yahoo search instead of Google.
It&amp;#39;s laughable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:33:51 </td>
   <td style="text-align:left;"> $TSLA is #1 ev that originated in US and Biden still talking about Ford GM lol the hec </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:33:35 </td>
   <td style="text-align:left;"> $TSLA Biden lower costs to beat inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:33:30 </td>
   <td style="text-align:left;"> $TSLA this president dont give a rats ass about Tesla .  Why would we want to associate quality with this admin anyway? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:33:28 </td>
   <td style="text-align:left;"> $TSLA Go Brandon what a puppet hate this president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:33:21 </td>
   <td style="text-align:left;"> $TSLA  watching Biden talk EV. Cringe AF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:58 </td>
   <td style="text-align:left;"> $TSLA no one cares 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:49 </td>
   <td style="text-align:left;"> $TSLA stop forcing Biden to talk about Tesla, I have calls and I understand why He&amp;#39;s ignoring Tesla. He&amp;#39;s a union guy. Plus Elon Musk cannot just push everyone around, period </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:46 </td>
   <td style="text-align:left;"> $TSLA Not a good sign for tomorrow. He skipped Elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:44 </td>
   <td style="text-align:left;"> $TSLA wow. Sleepy gangs in White house.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:34 </td>
   <td style="text-align:left;"> $TSLA I know he was going to forget Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:30 </td>
   <td style="text-align:left;"> $TSLA biden will never mention Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:30 </td>
   <td style="text-align:left;"> $SPY $TSLA it sickens me at this point. This WH admin will never acknowledge Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:26 </td>
   <td style="text-align:left;"> $TSLA is there a set amount of times they&amp;#39;re supposed to stand and sir6 then stand again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:22 </td>
   <td style="text-align:left;"> $TSLA lol omg he&amp;#39;s broken $BTC.X $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:22 </td>
   <td style="text-align:left;"> $TSLA  we screwed tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:11 </td>
   <td style="text-align:left;"> $TSLA Thank fuck he skipped it lol loaded puts at closing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:32:11 </td>
   <td style="text-align:left;"> $TSLA joe really doesn’t give a flying fuck about Tesla does he lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:55 </td>
   <td style="text-align:left;"> $TSLA this fucker never mentions tsla, go brandon! What a hater </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:53 </td>
   <td style="text-align:left;"> Biden mentioned $F &amp;amp; $GM for Electric Vehicles-- forgot $TSLA, but how? Is the EV King wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:52 </td>
   <td style="text-align:left;"> $TSLA I feel Elon pain now.. hahah. All sleepy companies cheer by sleepy Jose. Wow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:51 </td>
   <td style="text-align:left;"> $TSLA lol Biden literally said GM created so many jobs but No ELON lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:40 </td>
   <td style="text-align:left;"> $TSLA Classic union shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:37 </td>
   <td style="text-align:left;"> $TSLA Biden talking about EVs and ignoring Tesla again 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:36 </td>
   <td style="text-align:left;"> $TSLA  Biden on GM and Foord- Electric Vehices </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:34 </td>
   <td style="text-align:left;"> $TSLA who are those two old cheerleaders behind him? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:28 </td>
   <td style="text-align:left;"> $TSLA Fucking hell, GM, really? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:14 </td>
   <td style="text-align:left;"> $TSLA No Elon wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:03 </td>
   <td style="text-align:left;"> $SPY no Tesla mention $TSLA ??? Hate this president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:03 </td>
   <td style="text-align:left;"> $TSLA Lmaoooo no Tesla.mentioned </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:31:01 </td>
   <td style="text-align:left;"> $TSLA Biden said ev </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:30:47 </td>
   <td style="text-align:left;"> $TSLA Biden on Ford, GM -EV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:30:45 </td>
   <td style="text-align:left;"> $TSLA say it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:30:27 </td>
   <td style="text-align:left;"> $TSLA oh my god. It’s called TESLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:30:13 </td>
   <td style="text-align:left;"> $TSLA calls/puts at what price level by Friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:29:57 </td>
   <td style="text-align:left;"> $TSLA 

I don’t understand why these clowns 🤡 are clapping 👏 when there’s a country called Ukraine getting slaughtered by the Evil killing machines of these KGBs with thousands of ppl lost homes hundreds killed and massive humanitarian crisis !! 

Seriously why ?! Just watching Ukraine getting crushed while  we  &amp;amp; NATO get bullied by this SOB rootless godless Criminal Putin ?! 

What a shame ! Messed up ! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:29:18 </td>
   <td style="text-align:left;"> $FSR $LCID $RIVN $TSLA $NKLA 
Have you met the 2024 Fisker Pear model starting at $22,500 after EV tax incentive 🤔🙋🍐
Fiskerinc.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:29:03 </td>
   <td style="text-align:left;"> $TSLA Biden on Intel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:29:03 </td>
   <td style="text-align:left;"> $LCID $TSLA $BAC why are they doing situps? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:28:35 </td>
   <td style="text-align:left;"> $SPY $BTC.X $TSLA 

Say what you want about Kamala….but she has a very handsome jaw line. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:28:25 </td>
   <td style="text-align:left;"> $TSLA 900 call by friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:28:00 </td>
   <td style="text-align:left;"> $TSLA you would think this thing should fly tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:27:49 </td>
   <td style="text-align:left;"> $TSLA ⚡️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:27:37 </td>
   <td style="text-align:left;"> $TSLA hope this would take off tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:26:25 </td>
   <td style="text-align:left;"> $TSLA 500,000 EV chargers -per Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:25:37 </td>
   <td style="text-align:left;"> $TSLA Biden on &amp;quot;Infastructure decade&amp;quot; (EVS included) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:25:03 </td>
   <td style="text-align:left;"> $TSLA futes takin a hit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:24:58 </td>
   <td style="text-align:left;"> $SOFI BIDEN SHOUTING OUT SOFI 

$CRM $SNOW $TSLA $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:24:58 </td>
   <td style="text-align:left;"> $VERB 
U ever see a lil stock, like the 1 that $TSLA  Ceo Elon mentioned that went up like 2000% in 1 day for being associated with tesla?
That&amp;#39;s what i think may happen when Verbs producer streaming content David Meltzer starts for $AAPL &amp;amp; mentions Verbtv being shoppable or maybe by the reading on this pr that Meltzer uses Verbteck on Apple&amp;#39;s streaming to make it all shoppable. Of course apple wants their streaming shoppable &amp;amp; tbey never heard of Verb until now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:24:14 </td>
   <td style="text-align:left;"> $LCID $MMAT $TSLA  
All that you need to know. Shorts haven&amp;#39;t covered a single share; Check it out below, highly recommend everyone to follow them,,,,,: profit.stocktradingchat.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:23:45 </td>
   <td style="text-align:left;"> $TSLA cool seeing the cybertrucks out on the track. 🤘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:23:16 </td>
   <td style="text-align:left;"> $TSLA U.S. bans Russian aircraft from American airspace https://cnb.cx/36VtlI8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:21:48 </td>
   <td style="text-align:left;"> $TSLA Biden now on inflation! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:21:17 </td>
   <td style="text-align:left;"> $TSLA go Joe 🦾🦾🦾🦾🦾.. America 🇺🇸 is with you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:21:02 </td>
   <td style="text-align:left;"> $TSLA &amp;quot;we stand ith you (Ukranians&amp;quot;) -Biden SOTU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:20:12 </td>
   <td style="text-align:left;"> $SPY $TSLA  We&amp;#39;re going to be okay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:19:29 </td>
   <td style="text-align:left;"> $TSLA 60 million barrels of oil to be released Biden  
 
WE are going to be OK -Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:18:07 </td>
   <td style="text-align:left;"> $TSLA Our Forces to defend NATO, Not Ukraine -Biden- Every inch of Nato ground per Biden 
 
 
Next few days hard for Ukraine- Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:17:56 </td>
   <td style="text-align:left;"> BIDEN URGES TO LOWER THE PRICE OF ELECTRIC VEHICLES #SOTU $TSLA  $LCID $GGPI $GM $F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:17:17 </td>
   <td style="text-align:left;"> $TSLA $SPY  The more Joe speaks, the redder market gets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:17:17 </td>
   <td style="text-align:left;"> $SPY BULLS you bought SWING CALLS for this 🤷‍♂️😆🤡📉🙃 $tsla $mrna $rsx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:16:43 </td>
   <td style="text-align:left;"> $TSLA Futes not futin&amp;#39; yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:16:30 </td>
   <td style="text-align:left;"> $SPY $BTC.X $TSLA 

Is this a press conference on Ukraine or the STATE OF THE UNION? 

I’m so confused, isn’t this supposed to be about the US? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:16:25 </td>
   <td style="text-align:left;"> $TSLA Closing US airspace to Russia- Russia n stock market -40% on a Halt! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:16:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA  Pretty sure Putin is not going to take this well...🤕🤒 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:15:23 </td>
   <td style="text-align:left;"> $TSLA Biden to Russia &amp;quot;No More&amp;quot;!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:13:59 </td>
   <td style="text-align:left;"> $QQQ $SPY $NIO $TSLA 

Putin as he listens to Biden’s speech… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:13:31 </td>
   <td style="text-align:left;"> $SPY $TSLA $FB $AAPL US - Russia Head to head now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:12:41 </td>
   <td style="text-align:left;"> $TSLA Biden on Ukraine! Tyranny speech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:12:26 </td>
   <td style="text-align:left;"> $AMD $GOOGL $AAPL $TSLA look at Pelosi. She didn&amp;#39;t look this happy when Trump was giving SOTU speech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:11:27 </td>
   <td style="text-align:left;"> $TSLA paid clappers on biden&amp;#39;s speech XD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:11:12 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:09:52 </td>
   <td style="text-align:left;"> $TSLA 
💵📆🔥
Option trades, Tuesday recap 3/1 🅿️

QQQ 340P +12%
QQQ 355C +27%
AAPL 162.5P +15%
AAPL 170C -20%
BAC 45C +20% 
QQQ 330P +30% still swinging these. 

Quick scalps ftw on a choppy Tuesday 
🎯💯

https://twitter.com/q_alerts/status/1498775899189268480?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:09:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

At least they aren’t wearing white like a bunch of cultish losers… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:08:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $ARKK

BIDEN’S WEAK!!!... LIKE A BULL!!...📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:08:45 </td>
   <td style="text-align:left;"> $SOFI should see $17s tomorrow

$AMC $JWN $TSLA $SPY

tomorrow SOFI will soar to new heights.

Fully expecting a 45-50% premarket with the great ER and raised guidance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:05:56 </td>
   <td style="text-align:left;"> $TSLA Watch Live: Biden to deliver first State of the Union in the shadow of Russia&amp;#39;s attack on Ukraine https://cnb.cx/3hrC3jo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:05:12 </td>
   <td style="text-align:left;"> $TSLA Biden at any moment! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:01:27 </td>
   <td style="text-align:left;"> $SPY madam speaker the Presidents cabinet 🙋‍♂️💯🤡 $tsla $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:01:18 </td>
   <td style="text-align:left;"> $TSLA Damn that’s an empty House Chamber Biden time I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 10:00:36 </td>
   <td style="text-align:left;"> $TSLA Biden now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:59:04 </td>
   <td style="text-align:left;"> $TSLA --&amp;gt;Watch live: Biden delivers State of the Union address https://thehill.com/video/in-the-news/596257-watch-live-biden-delivers-state-of-the-union-address </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:58:35 </td>
   <td style="text-align:left;"> $TSLA 2 MInutes to Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:54:53 </td>
   <td style="text-align:left;"> $TSLA check this before tomorrow https://youtu.be/XV8Ota3TQvg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:53:23 </td>
   <td style="text-align:left;"> $TSLA Live from the retirement home in 7 minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:52:09 </td>
   <td style="text-align:left;"> $SPY $TSLA $BTC.X 

Say what you want about Biden and Kamala, but Nancy takes the cake when it comes to the most annoying person to hear speak in Washington…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:51:46 </td>
   <td style="text-align:left;"> $TSLA check Meet Kevin&amp;#39;s last video.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:51:00 </td>
   <td style="text-align:left;"> $TSLA signed a 4 year agreement to buy lithium from $CXOXF which currently at $0.61 PS. 

Whaaaaaaaaaaaat?!?!?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:50:29 </td>
   <td style="text-align:left;"> We love to help traders win consistently!
We crush it both ways on $AAPL $AMZN and $TSLA as you may notice on our feed! Let’s get you stacking gains too! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:49:55 </td>
   <td style="text-align:left;"> $TSLA big feeling 900 EOW or possibly tomorrow . Biden will pump the markets after tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:49:45 </td>
   <td style="text-align:left;"> $TSLA Watch live: Biden delivers State of the Union address https://thehill.com/video/in-the-news/596257-watch-live-biden-delivers-state-of-the-union-address </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:49:16 </td>
   <td style="text-align:left;"> $TSLA 10 minutes to biden - I am playing Chess now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:44:58 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ  THIS IS BIG! My Friend just texted me -  US has cancelled all the flights going via Russian Airspace! His flight got cancelled until further notice🚨🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:43:39 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL Breaking

Putin nuclear warning as unhinged Russian leader tipped to drop bomb near Britain

VLADIMIR PUTIN could be planning to drop a nuclear bomb near Britain in a show of force against the West.

 https://www.express.co.uk/news/world/1573848/nuclear-war-uk-Russia-Vladimir-Putin-Ukraine-latest-news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:43:01 </td>
   <td style="text-align:left;"> $TSLA TSLA Stock Price  Prediction and Analysis for Tomorrow wednesday March 2nd
https://youtu.be/Vb1NHfEbdPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:41:47 </td>
   <td style="text-align:left;"> $TSLA feel like the market will pump after Biden’s speech tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:39:52 </td>
   <td style="text-align:left;"> $TSLA We could hit $950 tomorrow, don’t be surprised!! 🤩🙏🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:38:10 </td>
   <td style="text-align:left;"> $AAPL $TSLA  tinyurl.com/2p9e489k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:37:59 </td>
   <td style="text-align:left;"> $TSLA RMED📈ROAD TO $100
Only RMED related. 
Do not shill other tickers ♦️
https://t.me/RMEDinvestor .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:34:23 </td>
   <td style="text-align:left;"> $TSLA 

Show me $2000 already❤️❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:32:26 </td>
   <td style="text-align:left;"> $TSLA U.S. expected to soon ban Russian airlines from its airspace https://www.marketwatch.com/story/u-s-expected-to-soon-ban-russian-airlines-from-its-airspace-11646180110?reflink=mw_share_twitter Move would follow similar actions by EU, Canada </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:32:06 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-01 Options Analysis Video: 
https://www.youtube.com/watch?v=WUyRoYzp5bU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:29:58 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $FB $NVDA 
Bearish until he stops 😞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:29:52 </td>
   <td style="text-align:left;"> $TSLA  the inflation will end soon the way every business is banning their business with russia USA will be left with a lot of surplus items, reaulting into no inflation JMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:27:36 </td>
   <td style="text-align:left;"> $TSLA 

$F says its EV money losing business will split from its barely money making 🧊 ICE business - an announcement will be made publicly soon !! - unnamed sources ! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:27:14 </td>
   <td style="text-align:left;"> $TSLA The Market should watch Beijing Bidens SOTU and realize that we have no president, just a dementia puppet. But the market will probably find the one quasi positive statement that falls out of his mouth and run with it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:25:04 </td>
   <td style="text-align:left;"> $TSLA Watch live: Biden delivers State of the Union address 9:00 PM ET  in 35 Minutes https://thehill.com/video/in-the-news/596257-watch-live-biden-delivers-state-of-the-union-address </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:24:39 </td>
   <td style="text-align:left;"> $TSLA idk I think this goes back to 800 tomorrow. Shoulda put up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:23:38 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ $TSLA

So what will be worth more in a year from today Bitcoin or Ruble lol... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:21:29 </td>
   <td style="text-align:left;"> $TSLA Worth watching LONG over $875... Breakout at $885 can push to $892-$900 if it clears todays high at $889.8 🟢 
 
Puts can work under $855.. Flush below $850 can see $884.5 -&amp;gt; $836 if market sells. 🔴 
 
https://discord.com/invite/Ur4e5Vc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:20:52 </td>
   <td style="text-align:left;"> $TSLA Live look at Sleepy Joe in about 40 minutes as he&amp;#39;s thinking he was showing up for a pot luck dinner at the retirement home just as the cameras go live 😵‍💫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:19:46 </td>
   <td style="text-align:left;"> $TSLA &amp;quot;Musk vows to save ISS,&amp;quot; 
&amp;quot;Musk activates Ukraine&amp;#39;s internet,&amp;quot; 
tesla commie lies = drain on society </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:18:29 </td>
   <td style="text-align:left;"> $TSLA $LCID $NVAX does a bear $hit in the woods? Yes because he’s too poor to buy a house. I smell fear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:17:36 </td>
   <td style="text-align:left;"> $TSLA US to ban Russian flights from American airspace: report https://thehill.com/policy/international/596423-us-to-ban-russian-flights-from-american-airspace-report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:16:53 </td>
   <td style="text-align:left;"> $TSLA Will Biden say “Tesla” during the State of the Union? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:16:53 </td>
   <td style="text-align:left;"> $TSLA Wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:15:26 </td>
   <td style="text-align:left;"> $TSLA bullish cup and handle for my technical traders! What will be the catalyst? Guess we’ll tune in to the State of the Union! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:14:46 </td>
   <td style="text-align:left;"> $GGPI $LCID $RIVN $FSR $TSLA  
Rumored Polestar O2 Concept Car. &amp;quot;“Polestar O2 is our vision of a new era for sports cars,” says Maximilian Missoni, Polestar’s head of design. “By mixing the joy of open top driving with the purity of electric mobility, it unlocks a new mix of emotions in a car. But as with all our cars, we are about more than just straight-line sprints. It’s when you turn the steering wheel that the true fun begins.” 
https://www.bnd.com/living/article258937723.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:14:09 </td>
   <td style="text-align:left;"> $TSLA Biden sotu speech 9:00 PM ET -45 Minutes! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:13:35 </td>
   <td style="text-align:left;"> $TSLA gap and go tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:12:18 </td>
   <td style="text-align:left;"> Two mobile Tesla Cybertruck prototypes spotted testing together for the first time - TESLARATI $TSLA  https://apple.news/A0trgnsJ8S9eSkiSEpM1EMg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:12:05 </td>
   <td style="text-align:left;"> $TSLA Biden banning Russia from US airspace because of Ukraine https://news.yahoo.com/biden-steps-state-union-lectern-050839797.html?soc_src=social-sh&amp;amp;soc_trk=tw&amp;amp;tsrc=twtr via @Yahoo Biden planned to announce that the U.S. is following Canada and the European Union in banning Russian planes from its airspace </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:11:55 </td>
   <td style="text-align:left;"> $TSLA ❗️&amp;quot;This is a disaster&amp;quot; - Moscow deputies called on Putin to stop the war

The Council of Deputies of the Gagarinsky Municipal District in #Moscow condemned the military actions on the territory of #Ukraine and called on Vladimir Putin to immediately withdraw his troops from there - @nexta_tv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:11:32 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/gomjN1nzDrY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:09:40 </td>
   <td style="text-align:left;"> $TSLA who is is in those weeklies holding deep in the monies they bought last week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:08:39 </td>
   <td style="text-align:left;"> $TSLA I am getting my Tesla this week. Yay! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:06:19 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $FB Watching Biden speech and futures at the same time on a drink😂! It&amp;#39;s gonna be fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:04:50 </td>
   <td style="text-align:left;"> $SPY Biden going to mention EV tonight and send $TSLA &amp;amp; $F flying tomorrow. TSLA looks like it’s about to nut right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:00:58 </td>
   <td style="text-align:left;"> $TSLA anybody who bought today lost so if you bought today you are a loser </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 09:00:35 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $865.0 CALLS for Wednesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:59:14 </td>
   <td style="text-align:left;"> $TSLA Rivian announced a 20% price increase resulting in many reservations being cancelled. 

Meanwhile at Tesla, quality upgrades are being constantly added for no extra charge: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:57:00 </td>
   <td style="text-align:left;"> An Altman-Z score of 17.09 indicates that $TSLA is not in any danger for bankruptcy at the moment. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:56:36 </td>
   <td style="text-align:left;"> $TSLA https://jalopnik.com/washington-police-dont-want-teslas-as-patrol-cars-becau-1848602730 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:53:07 </td>
   <td style="text-align:left;"> $SPY I don&amp;#39;t like $TSLA anymore

I want SPY at 600 and TSLA at 10

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:52:38 </td>
   <td style="text-align:left;"> $TSLA stock analysis based on today&amp;#39;s closing price 

https://youtu.be/7n1hCRi4sTQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:46:52 </td>
   <td style="text-align:left;"> $TSLA by june next year china alone will have a run rate of around 2 million ev&amp;#39;s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:46:28 </td>
   <td style="text-align:left;"> $TSLA always a bunch of opportunities for plays on this stock in the morning. Premiums move well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:45:13 </td>
   <td style="text-align:left;"> $TSLA has secured a lithium supply agreement with Core Lithium for 2023-2026 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:44:10 </td>
   <td style="text-align:left;"> $NIO $TSLA what a 💩y situation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:42:53 </td>
   <td style="text-align:left;"> $TSLA Elon Musk and brother Kimbal face insider trading probe from SEC: report. https://nypost.com/2022/02/24/elon-musk-and-brother-kimball-face-insider-trading-probe-from-sec-report/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:41:22 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING! 
@elonmusk 

Coming soon, if you want your car to make a loud farting sound from the external speaker, just say “Fart in their general direction!”

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:40:59 </td>
   <td style="text-align:left;"> $TSLA TSLA Stock Price  Prediction and Analysis for Tomorrow wednesday March 2nd
https://youtu.be/Vb1NHfEbdPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:40:00 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK

I CAN’T SEE THESE PUMPERS WITH MY 

GOLD &amp;amp; WOOD SUNGLASSES 😎 

🧸 HAVE 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:38:40 </td>
   <td style="text-align:left;"> $SPY PUMP &amp;amp; DUMPS are for fun.... &amp;quot;wake up wake up wake up🎶🎼🔊!!! 😂🙋‍♂️📉👀 $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:37:15 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Core Lithium, Tesla ink binding lithium supply term sheet https://www.stck.pro/news/TSLA/23677899 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:36:04 </td>
   <td style="text-align:left;"> $TSLA holding up insanely well. Time to load shares if you haven’t </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:32:10 </td>
   <td style="text-align:left;"> $INTC $SOFI $TSLA $AAPL $AMD Holy buys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:30:31 </td>
   <td style="text-align:left;"> Core Lithium&amp;#39;s Supply To Tesla Is Scheduled To Commence In H2 2023; First Lithium Concentrate Production Scheduled For Q4 2022 From Finniss Project 
 
Core Lithium, Tesla Execute Binding Term Sheet For Lithium Supply; Co To Supply Tesla Up To 110KT Of Spodumene Concentrate To Tesla Over 4 Years; Tesla To Support Core With Planned Development Of Lithium Chemical Processing Capacity 
 
$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:28:07 </td>
   <td style="text-align:left;"> $AMZN $TSLA

 State of Union:

Tough measures..Sanctions.. US Military now joining forces in Germany.. calling themselves “Resistance”.  

Biden Grandpa will pump market again n again tonight address. His whole aim is showbiz. .. Hope he doesn’t start the WW3. 

Russians are going IN. There will be questions and world will look differently now if US has to invade or bomb any country for whatever reason.   $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:27:09 </td>
   <td style="text-align:left;"> $TSLA fair value $400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:26:04 </td>
   <td style="text-align:left;"> $TSLA any price predictions for tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:24:49 </td>
   <td style="text-align:left;"> $SPY Soon as &amp;quot;LET&amp;#39;S GO BRANDON&amp;quot; APPROACHS THE PODIUM TO SPEAK - oops! chiclets will fall! 😁😆📉👀🙃 $tsla $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:23:59 </td>
   <td style="text-align:left;"> $LCID “ain’t no $TSLA”and it’s valuation is absurd….. rather own $MULN in speculation, $FSR in sympathy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:23:54 </td>
   <td style="text-align:left;"> $TSLA So Musky, I just need you to  be above $1,000 by the time tax deadline comes around because I’m planning to use half my 20 shares to pay my capital gains tax.  So, come on man, throw a brotha a bone!!! 🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:23:19 </td>
   <td style="text-align:left;"> Tesla unveils Supercharger station built in only 8 days thanks to new pre-fabricated system - Electrek $TSLA  https://apple.news/AibCrOp6SQImFjR728ba6Cw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:21:12 </td>
   <td style="text-align:left;"> $SPY $TSLA $BA $CRM $IBM  
Interesting day tomorrow  
Traders&amp;#39; Guide For Tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:20:54 </td>
   <td style="text-align:left;"> $TSLA this board wreaks of desperation lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:17:53 </td>
   <td style="text-align:left;"> $TSLA 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:17:13 </td>
   <td style="text-align:left;"> $TSLA loading tesla calls and bitcoin&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:15:07 </td>
   <td style="text-align:left;"> $TSLA Hey at least he&amp;#39;s doing something for the stock.🙈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:11:04 </td>
   <td style="text-align:left;"> Don’t look now but we are days away from a new {Death Cross} sell signal in the nasdaq for the first time since i can’t remember when. $QQQ $TSLA $BTC.X $ARKK $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:10:09 </td>
   <td style="text-align:left;"> $TSLA China has zero bureaucracy.  Even though Giga Berlin is expected to (and I expect) go production next month after getting approval from the German authorities this week, I’d like to see them odds of a setback in that resulting in the new Shanghai factory opening and producing Model 3’s before Giga Berlin is allowed to produce Model Ys.  Either way I bet the new China factory is producing cars in 2023…amazing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:04:56 </td>
   <td style="text-align:left;"> $TSLA $crm $ zm $NFLX I&amp;#39;m Giving you Guys a Heads up $bby with Drop $20 Ah They will Miss Big on Earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:03:42 </td>
   <td style="text-align:left;"> Tesla has secured a lithium supply agreement with Core Lithium for 2023-2026

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:03:29 </td>
   <td style="text-align:left;"> $TSLA https://fox4kc.com/news/one-person-dead-after-tesla-hit-by-two-vehicles-in-independence/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:03:18 </td>
   <td style="text-align:left;"> $TSLA price targets for tomorrow?let’s here em bois! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:03:01 </td>
   <td style="text-align:left;"> $tsla Earnings reports today before the markets open -~!   chat.stockmarketwatcher.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 08:02:11 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #4 ticker with sweep activity where institutions are trading options urgently with 37.4K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:59:31 </td>
   <td style="text-align:left;"> Silver approaching the Stage 2 breakout level &amp;amp; US Stocks Watchlist - 1 March 2022 
 
There were 20 stocks for the US stocks watchlist today. $AAPL, $PANW, $TSLA, $WPM + 16 more... 
 
➜ Members login to view the full post 
 
#stocks #trading #investing #money 
 
https://www.stageanalysis.net/blog/113025/us-stocks-watchlist-1-march-2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:57:49 </td>
   <td style="text-align:left;"> $tsla  Earnings reports today before the markets open -;;;  
 
chat.stockmarketwatcher.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:57:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Australia&amp;#39;s Core Lithium enters into supply deal with Tesla, shares jump https://www.stck.pro/news/TSLA/23677904 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:52:15 </td>
   <td style="text-align:left;"> $TSLA held up great considering the index’s today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:46:06 </td>
   <td style="text-align:left;"> $TSLA +640 left to go💪💪💪💪💯🦅🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:45:24 </td>
   <td style="text-align:left;"> $TSLA any Q&amp;amp;A for Sleepy Jose tonight.. oh! We need Climate changes.. hahahh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:44:29 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m Single Again Free at Last !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:43:24 </td>
   <td style="text-align:left;"> $TSLA NEWS - TSLA Expands Shanghai Production: 
https://www.youtube.com/watch?v=Dnm3uAGtCU4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:42:39 </td>
   <td style="text-align:left;"> $BTC.X $PYR.X $ETH.X $TSLA 

PYR going back to 20+ your heard here first 👀👀👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:42:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $ARKK

BULLARD BOUGHT POOOTS HEADING 

INTO TOMORROW!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:38:46 </td>
   <td style="text-align:left;"> $TSLA 

Little butter, ( 🐄) sizzling pan, 4mins each side !!  Enjoy 😉 

🙏🏻🐉🦅 
(Ribeye) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:35:02 </td>
   <td style="text-align:left;"> $ES_F $SPX $SPY $VIX $TSLA #trading When you have a defined and constrained market range coupled with an very inflated IVX, the set up is a delight for HI POP trades, which we have used exclusively since Jan1. E.g:  A short strangle on TSLA gave us $4200 credit per contract in our accounts. It expired worthless, letting us keep the full credit per contract.  
 
If you are unfamiliar with HI POP credit spread trades, let us know. (it essentilly puts you on the market maker&amp;#39;s side of the trade, with all the adjustments that go with it). Happy to walk anyone thru how to put one on. Over the period of 12mos trading you should be seeing about a 88-94% win rate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:33:09 </td>
   <td style="text-align:left;"> $PLTR $ROKU $OPEN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:31:24 </td>
   <td style="text-align:left;"> $SPY $TSLA Biden is going to say the n word and crash the market (nuclear) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:29:31 </td>
   <td style="text-align:left;"> $TSLA lets go MF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:28:15 </td>
   <td style="text-align:left;"> Called out a $TSLA 3/4 850 put at 12.90 and it ran to 21.50. For 66% return. We bank like this all the times. In the free discord . Easy money. $GBS $SPY $CTK $IMPP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:27:30 </td>
   <td style="text-align:left;"> $TSLA Well, instead of tearing up speech copies, or sneers, or condescending applause, the toxic cow will be all glowing and light tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:26:50 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:24:54 </td>
   <td style="text-align:left;"> $SPY $TSLA ...—... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:20:57 </td>
   <td style="text-align:left;"> $TSLA Big long green American cox </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:16:55 </td>
   <td style="text-align:left;"> $AAPL I think Putin and Biden need to put on some boxing gloves and make it a pay-per-view worldwide can you imagine how much money they would make for that event I would pay up to $500 just to watch this.

$TSLA $AMZN $FB $XOM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:14:10 </td>
   <td style="text-align:left;"> $SOFI this is minimum $25 stock.. anything under is dirt cheap .. $SQ $TSLA $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:14:02 </td>
   <td style="text-align:left;"> $TSLA remember Tesla bears. Berlin approval set for this week. If that news comes premarket; Tesla will absolutely rocket. Be ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:13:47 </td>
   <td style="text-align:left;"> $ELBMF honestly just a matter of time before this thing takes off. Continuing to add to my position on the dips. $TLOFF ties us with $TSLA. Additionally I have a suspicion of a Britishvolt partnership for their proposed giga factory in Quebec. Our property sits right on the Ont./Que border, and both companies have been in communications with the same lobbyist. Could be big. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:12:49 </td>
   <td style="text-align:left;"> $TSLA   Tesla deploys big 37-Megapack project in Alaska to replace gas turbines 
Tesla has now deployed and unveiled a big 37-Megapack project in Alaska that will help replace gas turbines with a more sustainable solution. 
 
Homer Electric, a member-owned electric utility cooperative based in Alaska, announced the project based in Kenai Peninsula back in 2019 – shortly after Tesla first unveiled the Megapack. 
 
https://electrek.co/2022/03/01/tesla-deploys-big-37-megapack-project-alaska-replace-gas-turbines/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:12:13 </td>
   <td style="text-align:left;"> $TSLA is very strong today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:10:07 </td>
   <td style="text-align:left;"> $TSLA $F $BTC.X $ETH.X 😩😩😩No one can hide now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:09:11 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-01 Daily Forecast Video: 
https://www.youtube.com/watch?v=fBe2X098rRY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:08:58 </td>
   <td style="text-align:left;"> $TSLA  why so many non TSLA posts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:08:31 </td>
   <td style="text-align:left;"> $TSLA Brandon, putin and Powell will make tsla close tomorrow at $780 imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:06:51 </td>
   <td style="text-align:left;"> $SPY I actually hope Powell doesn&amp;#39;t hold back and raise the damn rates. Buying opportunity the way I see it and get the damn inflation under control $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:05:56 </td>
   <td style="text-align:left;"> $TSLA  $XOM  
Wealthy TEXANS are starting a &amp;quot;go fund me&amp;quot; for any traitors who cheerlead for Putin.  We will buy your airfare OW to send you to your homeland to be with Putin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:05:24 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SPCE $FB I’m starting to dislike these billionaire cocksuckers.  I’m mixed on the stocks though.  I do like Buffet and Munger for some reason.  They’re from an era that uses their power a little more responsibly.   And they’re not trying to scam us into buying $DOGE.X.  I’d be willing to wager all are in cahoots on some level with the Russian oligarchs and the evil Chinese empire.   The world gets weirder by the minute </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:02:02 </td>
   <td style="text-align:left;"> $TSLA totally missed the train down here today lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 07:00:47 </td>
   <td style="text-align:left;"> $TSLA Shooting Star Candlestick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:59:47 </td>
   <td style="text-align:left;"> Get the Ukrainian president to negotiate and stay neutral instead of sucking up to west because u just hate Russia.  Applied for EU, applied tor NATO while saying we want peace.

$TSLA $AMZN $SPY 

Russia 1st ask is Ukraine neutrality and can get everything back. The Ukraine president, now a hero is making Ukrainians lives at stake nobody gonna fight your war. If you had Oil like Iraq 🇮🇶, America would have but cant fight d*** head with 10000 Nheads.  

“The move, which would be unprecedented, could spur Russia, China and other governments to move away from ICANN and spur the balkanization of the internet”. India and UAE will join this mess.

https://www.cnbc.com/2022/03/01/ukraine-asked-icann-to-revoke-russian-domains-shut-dns-servers.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:59:30 </td>
   <td style="text-align:left;"> $SOFI we pregnant! $PLTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:56:57 </td>
   <td style="text-align:left;"> :) 
 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:56:30 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $DJIA 

https://nypost.com/2022/02/26/putin-played-powell-and-us-pays-the-price/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:56:01 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow. 
 
https://youtu.be/jiwxNdffJ1Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:55:00 </td>
   <td style="text-align:left;"> $TSLA has a good Piotroski-F score of 7.00. This indicates a good health and profitability. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:54:54 </td>
   <td style="text-align:left;"> $TSLA https://m.investing.com/news/commodities-news/iea-meets-on-potential-oil-stocks-release-after-russia-invasion-2775063 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:54:45 </td>
   <td style="text-align:left;"> $TSLA when Taiwan receives SpaceX Starlink terminals? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:54:38 </td>
   <td style="text-align:left;"> 10 Consumer Discretionary Stocks With Whale Alerts In Today’s Session $TSLA $RIVN $WISH $BABA $AMZN https://www.billionaireclubcollc.com/10-consumer-discretionary-stocks-with-whale-alerts-in-todays-session-6/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:48:31 </td>
   <td style="text-align:left;"> $TSLA new lithium supplier $CXOXF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:48:09 </td>
   <td style="text-align:left;"> $SOFI folks Dont be surprised if we hit +45% tomorrow at open

20% shorted float ALL must squeeze

$JWN $PLTR $TSLA $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:46:45 </td>
   <td style="text-align:left;"> $SOFI $PLTR $TSLA $METV $SVOL.....good plays. Lets remember... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:46:30 </td>
   <td style="text-align:left;"> $RIVN Wow new and existing reservations hit with price increase. At least you lock in prices with $TSLA. A lot of people are going to be pissed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:46:20 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s go! Incoming tax credits from state of the union? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-02 06:45:20 </td>
   <td style="text-align:left;"> $MULN can you imagine $TSLA interested. Very cheap price for the product they been looking for </td>
  </tr>
</tbody>
</table></div>

---
