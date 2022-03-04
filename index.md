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



Last Updated: 2022-03-04 09:26:34 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 09:16:31 </td>
   <td style="text-align:left;"> Nikkei 225 Hits 15-month Low </td>
   <td style="text-align:left;"> JP225 decreased to a 15-month low of 25774 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-04 09:05:10 </td>
   <td style="text-align:left;"> South Korea 10Y Bond Yield Hits 4-week Low </td>
   <td style="text-align:left;"> South Korea 10 Year Government Bond Yeld decreased to a 4-week low of 2.6% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 09:00:00 </td>
   <td style="text-align:left;"> US Futures Fall on Possible Attack at Ukraine Nuclear Plant </td>
   <td style="text-align:left;"> US stock futures fell in Asian trade on Friday following reports that smoke was visible from a nuclear power plant in Ukraine, the largest in Europe, after Russian troops attacked. Futures tied to the three major averages were each down more than 1%. The moves also come in advance of the February jobs report which is expected to show 400,000 additional jobs and for the annual wage growth to log at 5.8%. This is the last jobs report before the Federal Reserve’s next meeting where it is expected to begin hiking rates, with Fed chair Jerome Powell leaning toward a smaller 25 basis point increase in March, while leaving the door open for moving more aggressively down the line should inflation persist. He also said the Russia-Ukraine conflict added uncertainty to the outlook. In regular trading on Thursday, the Dow fell 0.29%, the S&amp;P 500 lost 0.53% and the Nasdaq Composite dropped 1.56%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/iron-ore </td>
   <td style="text-align:left;"> 2022-03-04 09:00:00 </td>
   <td style="text-align:left;"> Iron Ore Hits 26-week High </td>
   <td style="text-align:left;"> Iron Ore increased to a 26-week high of 151 USD/T, amid expectations of increased demand in China. The world's top consumer said it would renew its stimulus package for the infrastructure sector in the face of slowing economic growth. Also, the latest data showed manufacturing activity in China expanded slightly in February, despite downward pressure and global uncertainty amid the Russia-Ukraine conflict. Still, Beijing has been signalling it would focus on stabilising prices after the state planner warned about iron ore trading speculation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-03-04/los-angeles-mega-mansion-draws-126-million-top-bid-at-auction?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-03-04 08:42:45 </td>
   <td style="text-align:left;"> Los Angeles Mega-Mansion Draws $126 Million Top Bid at Auction </td>
   <td style="text-align:left;"> John Gittelsohn                                                                                                                                                                                                                                               , The highest offer for the biggest U.S. mega-mansion ever to go on the auction block was $126 million when bidding closed Thursday.                                                                                                                            , The 21-bedroom, 49-bath hilltop Los Angeles estate -- dubbed “The One” -- had a list price of $295 million. Developer Nile Niami said in 2015 that he would ask $500 million for the Bel Air property, which also has five swimming pools and a 30-car garage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-03-04/gold-s-surge-on-war-headlines-may-be-fleeting-as-past-shows?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-03-04 08:42:34 </td>
   <td style="text-align:left;"> Gold’s Surge on War Headlines May Be Fleeting as Past Shows </td>
   <td style="text-align:left;"> Ranjeetha Pakiam                                                                                                                                                                                                                                                                                                                                                                                                                                     , Gold’s surge on the back of Russia’s invasion of Ukraine may be short-lived, if history is anything to go by.                                                                                                                                                                                                                                                                                                                                        , From the Falkland Islands War in 1982 to the Sept. 11 attacks, price spikes in gold resulting from crises that include military action or terrorist strikes tend to be temporary, according to Citigroup Inc. The traditional haven asset jumped as much as 3.4% on Feb. 24 when Russia launched a full-scale attack on its neighbor, but prices have since consolidated, even as other commodities such as oil, wheat and aluminum have accelerated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/retail-sales </td>
   <td style="text-align:left;"> 2022-03-04 08:38:00 </td>
   <td style="text-align:left;"> Australia Retail Sales Grow 1.8% MoM in January </td>
   <td style="text-align:left;"> Retail sales in Australia increased by 1.8% month-on-month in January 2022, unrevised from the flash figure and after a final 4.4% slump a month earlier. Food retailing  (2.2% vs 2.2% in December) had the largest rise in sales, which is the biggest monthly rise since July 2021 with sales remaining elevated at their fourth highest level in the series. This went alongside a fall in cafes, restaurants, and takeaway food services (-0.8% vs -0.7%) as some consumers opted to stay home. Other industries which saw rises include other retailing (4.5% vs -4%), department stores (4.9% vs -21.3%), and household goods retailing (0.6% vs -9.2%), while clothing, footwear and personal accessory retailing fell (-1% vs -17.3%) as the only other industry to fall. Sales across the states and territories all rose this month with Victoria, up 2.5% experiencing the largest rise, followed by Western Australia (4.7%), New South Wales (1%), South Australia (3.1%) and Queensland (0.4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 08:36:00 </td>
   <td style="text-align:left;"> Nikkei 225 is down by 2.01% </td>
   <td style="text-align:left;"> Nikkei 225 decreased 2.01% to 26043, dragged down by a pullback in Wall Street overnight after Fed Chair Jerome Powell warned Thursday that Russia’s invasion of Ukraine, which has already driven up oil prices, will likely further worsen the high inflation in the US. Powell added that he is committed to doing whatever it will take to slow inflation. Traders were also downbeat following reports that  Toyota Motor had decided to halt vehicle production at its plant in St. Petersburg, the second-largest city in Russia, citing supply chain disruptions, starting Friday. On the pandemic side, Japanese Prime Minister Fumio Kishida said Thursday that the government will extend its COVID-19 pre-emergency designations for 18 prefectures, set to run out Sunday, until March 21st. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-04 08:16:00 </td>
   <td style="text-align:left;"> US 10Y traded above 1.8 percent </td>
   <td style="text-align:left;"> US 10 Year Note Bond Yield rose above 1.8, according to over-the-counter interbank yield quotes for this government bond maturity. The yield rebounded sharply from a two-month low of 1.68% hit early in the week after Fed Chair Jerome Powell told US lawmakers the US economy no longer needs such an accommodative policy stance, signalling a 25 basis point rate hike in March. Aside from Powell's remarks, investors continued to follow developments around the Russia-Ukraine war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60610537?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-04 08:01:02 </td>
   <td style="text-align:left;"> World Bank warns Ukraine war will cut global growth </td>
   <td style="text-align:left;"> The president of the World Bank has told the BBC that the war in Ukraine is a catastrophe for the world which will cut global economic growth.                                                                                                                                                                                        , "The war in Ukraine comes at a bad time for the world because inflation was already rising,", said David Malpass.                                                                                                                                                                                                                     , He stressed his biggest concern is "about the pure human loss of lives" that is occurring.                                                                                                                                                                                                                                            , Thousands of civilians and soldiers are thought to have been killed by the fighting.                                                                                                                                                                                                                                                  , Mr Malpass said the economic impact of the war stretches beyond Ukraine's borders, and the rises in global energy prices in particular "hit the poor the most, as does inflation."                                                                                                                                                    , Food prices have also been pushed up by the war, and "are a very real consideration and problem for people in poor countries".                                                                                                                                                                                                        , Mr Malpass points out that both Russia and Ukraine are big food producers. Ukraine is the world's biggest producer of sunflower oil, with Russia number two, according to S&amp;P Global Platts. Between them they account for 60% of global production.                                                                                  , The two countries also account for 28.9% of global wheat exports according to JP Morgan. Wheat prices on the Chicago future exchange have been trading at 14-year highs.                                                                                                                                                              , Russian supplies of these commodities are being restricted because of the widespread sanctions which make it hard for the rest of the world to buy its products. Ukrainian supplies have been stopped because fighting has closed the country's ports.                                                                                , "There's no way to adjust quickly enough to the loss of supply from Ukraine and from Russia, and so that adds to prices" said Mr Malpass.                                                                                                                                                                                             , He says the same is true of Russian energy supplies, and it is particularly damaging for western Europe, where governments have "neglected other aspects of how to have enough electricity". About 39% of the EU's electricity comes from power stations that burn fossil fuels, and Russia is the biggest source of that oil and gas., As the EU looks to accelerate its transition to other energy sources, Vladimir Putin's government "may permanently lose some of their markets", said Mr Malpass. Such a loss of income is just one way this war will dent living standards in Russia, so too will the fall in the value of the rouble and the inflation that brings.  , The World Bank has committed $7.9bn to help develop Ukraine's economy since the 2014 revolution. That money has helped the country institute wide-ranging economic reforms including privatisations in the energy and banking sectors, as well as efforts to make its farmland more productive.                                       , Less than a month before the Russian invasion Ukraine's independent central bank forecast that the $180bn economy would grow 3.4% this year, after the difficulties of the pandemic.                                                                                                                                                  , However, war means "a catastrophic impact for our economy for the region overall", according to Alexander Rodnyansky, who is an economic advisor to President Zelensky.                                                                                                                                                               , He adds: "We've already seen massive destructions of roads and bridges and infrastructure. So that is something that will have to be rebuilt over the years when the war is over.                                                                                                                                                     , "It's hard to put a number on that right now. But we can already see that we've given up percentages and GDP growth just because of what happened already."                                                                                                                                                                           , With hundreds of thousands of Ukrainians fleeing the country or joining the fight against Russia the workforce has shrunk dramatically, which is making it difficult to keep the war time economy going.                                                                                                                              , "Production is just collapsing", says Mr Rodnyansky, who says there are disruptions to vital food and energy supplies.                                                                                                                                                                                                                , Big western companies, such as food manufacturer Nestle and brewer Carlsberg, have big operations in Ukraine that have been disrupted by the war.                                                                                                                                                                                     , A surge of foreign investment in recent years helped to reshape the Ukrainian economy amid a corruption crackdown that was part of a deal for development support from the International Monetary Fund and World Bank.                                                                                                                , Mr Rodnyansky said that shift "absolutely reflects the people's desire in Ukraine to integrate with the European Union, to be part of the European family, and to just have a democratic, strong, economically free country that's flourishing.                                                                                       , He says there has been a drive to digitisation that has made it easier to do business in the country: "It stands in stark contrast to what happens in Russia… and that's perhaps another reason why the Russian leader just so blatantly hates everything about Ukraine and what Ukraine stands for."                                 , This video can not be played                                                                                                                                                                                                                                                                                                          , Mr Malpass is concerned that the war will do long term damage to those changes that Ukraine's economy and people have benefitted from.                                                                                                                                                                                                , A desire to stop them unravelling is one reason why the World Bank is in the process of putting together a $350m aid package for Ukraine which is expected to be approved within the next few days.                                                                                                                                   , "It will help fund the budget of Ukraine", said Mr Malpass. With tax revenues collapsing because of the war it will help pay for things such as government salaries, social welfare and emergency supplies.                                                                                                                           , He is conscious that as well as the risk to the lives of millions of Ukrainian, the war could "be a lasting [economic] setback, where Russia pulls them toward Russia, under the ideas, the goals of an individual leader."                                                                                                           , "Their per capita income has fallen below China's because in part because of economic mismanagement, and because they really have maintained such a centralised system of decision making under Putin for now, ever since 2000."                                                                                                      , He adds: "The risk is that Ukraine is controlled by that."                                                                                                                                                                                                                                                                            , You can watch David Malpass' full interview on "Talking Business with Aaron Heslehurst" this weekend on BBC World News at Saturday 23:30 GMT, Sunday 05:30 and 16:30 GMT and Monday at 08:30 GMT                                                                                                                                      , The obsession continues with the final series of Killing Eve...                                                                                                                                                                                                                                                                       , Incredible technology takes you on an emotional journey deep inside!                                                                                                                                                                                                                                                                  , The very best from around the world including Beck and The Bridge                                                                                                                                                                                                                                                                     , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-03-03/wall-street-is-already-pouncing-on-russia-s-cheap-corporate-debt?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-03-04 07:59:15 </td>
   <td style="text-align:left;"> Wall Street Is Already Pouncing on Russia’s Cheap Corporate Debt </td>
   <td style="text-align:left;"> Laura Benitez,                                                                                                                                                                                                                                                                      , Sridhar Natarajan, and                                                                                                                                                                                                                                                              , Katia Porzecanski                                                                                                                                                                                                                                                                   , As the U.S. and allies tighten sanctions on Russia and choke off investor demand for its assets, parts of Wall Street are jumping on the buying opportunity that it’s creating.                                                                                                     , Goldman Sachs Group Inc. and JPMorgan Chase &amp; Co. have been purchasing beaten-down company bonds tied to Russia in recent days, as hedge funds that specialize in buying cheap credit look to load up on the assets, according to people with knowledge of the private transactions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-03-03/oil-extends-wild-week-s-gain-as-ukraine-invasion-rattles-markets?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-03-04 07:52:13 </td>
   <td style="text-align:left;"> Oil Extends Wild Week’s Gain as Ukraine Invasion Rattles Markets </td>
   <td style="text-align:left;"> Ben Sharples                                                                                                                                                                                                                                                                                                                                                                                       , Oil headed for the biggest weekly surge in almost two years after Russia’s invasion of Ukraine roiled global markets and fueled fears of a supply crunch, driving prices to their highest since 2008.                                                                                                                                                                                              , Futures in New York resumed gains Friday after swinging through a $10 range and closing below $108 a barrel in the previous session on signs that a Iranian nuclear deal may be near. Prices are up 22% this week after financial sanctions were slapped on Russia, prompting buyers to shun its crude. Russia escalated its assault by attacking a Ukrainian nuclear plant, the biggest in Europe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/unemployment-rate </td>
   <td style="text-align:left;"> 2022-03-04 07:48:19 </td>
   <td style="text-align:left;"> Japan Jobless Rate Rises to 2.8% in January </td>
   <td style="text-align:left;"> Japan’s unemployment rate increased to 2.8% in January 2022, compared with 2.7% in December and missed expectations for no change. The data reflected the impact of the fast-spreading omicron variant on the labor market during the period. Meanwhile, the jobs-to applications ratio posted at a 21-month high of 1.20 in January, meaning that there were 120 job openings for every 100 job seekers. The figure was up 0.03 point from the previous month’s 1.17 and higher than consensus forecast of 1.16. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/republicans-energy-experts-keystone-xl-cancelled-biden-lessen-need-russian-oil </td>
   <td style="text-align:left;"> 2022-03-04 07:46:29 </td>
   <td style="text-align:left;"> Republicans, energy experts say Keystone XL cancelled by Biden would have helped lessen need for Russian oil </td>
   <td style="text-align:left;"> Former Deputy National Security Advisor KT McFarland criticizes Biden and Germany’s roles in the Russia-Ukraine war on ‘Fox Business Tonight.’                                                                                                                                                                                                                                                                                                                                                                                        , The Keystone XL pipeline was halted by the administrations of both President Obama and President Biden which critics, including one expert who spoke with Fox Business, say only exacerbated the current predicament the United States faces as it continues to purchase oil from Russia as it invades Ukraine, a U.S. ally.                                                                                                                                                                                                          , Several news outlets including the Washington Post and CNBC have posted headlines admonishing those who invoke Biden’s cancellation of the Keystone XL pipeline as the United States continues to buy oil from Russia while the country’s military wreaks havoc in Ukraine.                                                                                                                                                                                                                                                           , MIKE PENCE CALLS ON BIDEN TO HIT RUSSIA HARDER, RESTART KEYSTONE PIPELINE: 'PUTIN ONLY UNDERSTANDS STRENGTH'                                                                                                                                                                                                                                                                                                                                                                                                                          , Several Republicans across the country have disagreed with that assessment including South Carolina Sen. Tim Scott.                                                                                                                                                                                                                                                                                                                                                                                                                   , Russian President Vladimir Putin  (Yuri Kochetkov/Pool Photo via AP / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                                                                                                                    , "The United States imports nearly 600,000 barrels of oil a day from Russia—an amount that could have been made up for by the more than 800,000 barrels of oil the Keystone XL pipeline is capable of delivering each day if the Biden administration hadn’t stood in the way," Republican Sen. Tim Scott wrote on Fox News this week. "As Vladimir Putin conducts his evil and unprovoked attack on Ukraine, now more than ever, we must cut off our energy dependence on Russia while turning up our energy production here at home.", White House Press Secretary Jen Psaki shot down a question about the potential impact of the Keystone XL pipeline, which Biden halted in 2021, and said the pipeline has never been operational and would therefore take "years" to have an impact. Had it not been canceled twice, though, during the Obama and Biden administrations, it would likely be near completion.                                                                                                                                                           , RICK PERRY: BIDEN ADMIN. GAVE PUTIN 'LEVERAGE' BY BLOCKING AMERICAN PIPELINES AND DRILLING                                                                                                                                                                                                                                                                                                                                                                                                                                            , A woman cries outside houses damaged by a Russian airstrike (AP Photo/Vadim Ghirda / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                                                                                                     , Jason Modglin, President of the Texas Alliance of Energy Producers, told Fox Business on Thursday that the Keystone XL pipeline along with other pipelines would in fact make a difference in the short and long term.                                                                                                                                                                                                                                                                                                                , "Keystone would have absolutely made a difference because it would have lowered the cost of Canadian crude to get to the markets that it needs to get to in order to be refined and shipped to be utilized here in the United States," Modglin said. "And so by canceling Keystone, it artificially raises the price of Canadian oil and allows for the Russians to undercut that."                                                                                                                                                   , Modglin added that the current energy crisis represents an "opportunity" for the president.                                                                                                                                                                                                                                                                                                                                                                                                                                           , "This is an opportunity for the president to express a long-term vision for energy security for the United States and our allies around the world," Modglin said. "That starts with accelerating pipeline development here in the United States, accelerating LNG export terminals and trade agreements with our allies and, frankly, partners who are not fully free-trade partners with us. That’s the best way to compete against Russian oil around the world is to unleash American innovation and production."                  , Quill Robinson, government affairs vice president at the American Conservation Coalition, told FOX Business last week that Biden handicapped the ability of the United States to combat the current energy crisis caused by Putin's war in Ukraine.                                                                                                                                                                                                                                                                                   , "President Biden started off his administration by kneecapping America's ability to produce energy, and I think that that's a huge problem," Robinson said. "And we're seeing the consequences of that now."                                                                                                                                                                                                                                                                                                                          , On Thursday, House Speaker Nancy Pelosi voiced support for banning all Russian oil imports into the United States in order to cut off the revenue stream for Putin’s aggression in Ukraine.                                                                                                                                                                                                                                                                                                                                           , "I'm all for that. Ban it," Pelosi said Thursday at a press conference at the Capitol.                                                                                                                                                                                                                                                                                                                                                                                                                                                , FILE PHOTO: A general view shows an oil treatment plant in the Yarakta Oil Field, owned by Irkutsk Oil Company (INK), in Irkutsk Region, Russia March 10, 2019. Picture taken March 10, 2019. REUTERS/Vasily Fedosenko (REUTERS/Vasily Fedosenko / Reuters Photos)                                                                                                                                                                                                                                                                    , CLICK HERE TO GET THE FOX NEWS APP                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Politicians on both sides of the aisle have called in recent days for the United States to halt its purchases of oil from Russia in order to avoid financing Putin’s war in Ukraine.                                                                                                                                                                                                                                                                                                                                                  , "To put up barriers to natural gas projects &amp; the benefits they provide while Putin is actively &amp; effectively weaponizing energy against our allies is absurd," Democrat Sen. Joe Manchin posted on Twitter Thursday. "We need to instead increase access &amp; strengthen our ability to use energy to fight for our values &amp; support our partners."                                                                                                                                                                                     , When asked about whether the United States was financing Russia’s war with Ukraine by purchasing oil from the country, White House Press Secretary downplayed that idea.                                                                                                                                                                                                                                                                                                                                                              , "It’s only about 10% of what we are importing," Psaki said, adding that she urges Republicans to join the Biden administration’s call to invest in green energy to help the United States move away from fossil fuels, missing the fact that US purchases of Russian oil fund Putin's government and war machine. Additionally, green energy tech such as solar panels and lithium batteries rely heavily on Chinese mining and manufacturing.                                                                                        , Russia is the producer of one out of every 10 barrels of oil consumed by the world, according to the New York Times, making it the third-largest oil producer in the world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/rating </td>
   <td style="text-align:left;"> 2022-03-04 07:26:00 </td>
   <td style="text-align:left;"> S&amp;P Cuts Russia’s Credit Rating Further </td>
   <td style="text-align:left;"> S&amp;P cut Russia's rating to "CCC-" from "BB+", on March 3rd, pushing it further into "junk" territory as fresh international sanctions and the nation's own protective measures ramped up default risk. Earlier, Moody's Credit Rating lowered Russia’s long-term issuer and senior unsecured debt ratings to B3 from Baa3, citing as main trigger behind the change pressures on severe sanctions that Western countries have imposed on Russia. The agency said that it remain on review for further downgrade. Fitch credit rating for Russia was last set at B with negative watch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-04 07:23:30 </td>
   <td style="text-align:left;"> South Korea Inflation Remains Above Expectations </td>
   <td style="text-align:left;"> Consumer prices in South Korea rose 3.7% in February 2022 from a year earlier, accelerating from a 3.6% gain in the previous month and posted higher than market expectations for a 3.5% increase. The latest figure remained close to a decade-high of 3.8% registered in November 2021 as energy costs spiked on tight supplies and tensions over Russia’s invasion of Ukraine. South Korea’s inflation also held above 3% since October, well in excess of the central bank’s 2% target, keeping the pressure on the Bank of Korea despite having raised interest rates three times since August to 1.25%. Meanwhile, the central bank decided to keep interest rates steady at its February policy meeting as surging coronavirus cases and escalating tensions in Ukraine clouded the economic outlook. The bank also raised its inflation forecast for this year to 3.1% from 2%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/cisco-systems-latest-american-company/story.aspx?guid={CFAAB8FB-A6FC-43AD-8C8B-83D41D71F8E0}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-04 07:20:01 </td>
   <td style="text-align:left;"> Cisco Systems is latest American company to stop business operations in Russia - MarketWatch </td>
   <td style="text-align:left;"> Cisco Systems Inc. 
        CSCO,
        -0.14%
       is the latest major U.S. company to pause business operations in Russia because of its invasion of Ukraine. Cisco Chief Executive Chuck Robbins told staff in an letter Thursday that "Cisco is stopping all business operations in Russia and Belarus and will continue to focus on supporting our Ukrainian employees, customers and partners while providing humanitarian aid and accelerating our efforts to protect organizations in Ukraine from cyber threats. We stand with Ukraine and condemn this unjustified war." Cisco joins a long list of companies that have paused business operations in Russia that include Apple Inc. 
        AAPL,
        -0.20%,
       Oracle Corp. 
        ORCL,
        -0.04%,
       Boeing Co. 
        BA,
        -4.53%,
       Exxon Mobile Corp. 
        XOM,
        +0.63%
       and Walt Disney Co. 
        DIS,
        -1.20%.
       , Elon Musk invites the United Auto Workers union to hold a vote at the electric-vehicle company's plant in California, and 'Tesla will do nothing to stop them.'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/03/business/media/new-york-times-tech-union.html </td>
   <td style="text-align:left;"> 2022-03-04 07:13:35 </td>
   <td style="text-align:left;"> New York Times Tech Workers Vote to Certify Union - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                          , The ratification, with about 80 percent of ballots in favor, makes it the largest tech union in the United States with collective bargaining rights.                                                                                                                                                                   , By Katie Robertson                                                                                                                                                                                                                                                                                                     , Tech workers at The New York Times on Thursday voted in favor of certifying their union in a National Labor Relations Board election, making it one of the biggest tech unions in America.                                                                                                                             , The workers voted in favor, 404 to 88, easily reaching the needed majority of the ballots that were cast. A win means the union, the Times Tech Guild, can begin negotiations for a contract with management.                                                                                                          , “We’re just elated and really soaking in what this means, not only for us as tech workers at The Times and for The New York Times but also for the tech industry as a whole,” said Nozlee Samadzadeh, a senior software engineer. “I think this is going to be the start of a wave of organizing in the tech industry.”, Ms. Samadzadeh said the union was eager to bargain a contract around issues “similar to what the newsroom unit has been fighting for — issues around pay, diversity and equity, a strong contract to make our workplace more fair.”                                                                                    , Danielle Rhoades Ha, a Times spokeswoman, said The Times looked forward to working with the union to establish a contract.                                                                                                                                                                                             , “We continue to believe this election process was critical so our colleagues could learn more about the union, hear both sides of the argument and, ultimately, make an informed decision,” she said.                                                                                                                  , The Times Tech Guild, which represents about 600 software engineers, product managers, designers, data analysts and other workers, asked The Times for voluntary recognition in April. The Times declined, so the matter went to a formal election through the labor board.                                            , The labor board alleged in a complaint in January that The Times’s management had violated federal workplace law by preventing some employees from showing support for the union. A Times spokeswoman said at the time that the company disagreed with the allegations.                                                , The Times Tech Guild is represented by the NewsGuild of New York, which also represents editorial workers at The New York Times and at Wirecutter, the company’s product-review website. In 2019, The Times voluntarily recognized the Wirecutter union.                                                               , The group is the biggest tech union with bargaining rights in America. Hundreds of Google employees announced a union in January 2021, but it is not registered with the N.L.R.B. and cannot engage in collective bargaining.                                                                                          , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/03/03/south-ukraine-resist-russia-pkg-lead-walsh-intl-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-04 07:06:35 </td>
   <td style="text-align:left;"> 'We know the danger': Ukrainians keep resisting the Russian invasion - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-03-03/australia-outshines-developed-global-peers-on-profit-outlook?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-03-04 06:45:03 </td>
   <td style="text-align:left;"> Australia Outshines Developed Global Peers on Profit Outlook </td>
   <td style="text-align:left;"> Excavators move iron ore at the port in Port Hedland, Australia.                                                                                                                                                                                                                                              , Jackie Edwards and                                                                                                                                                                                                                                                                                            , Keira Wright                                                                                                                                                                                                                                                                                                  , A strong corporate results season has boosted Australia’s profit outlook, with the commodity-rich nation’s stock benchmark outpacing its developed global peers when it comes to earnings upgrades.                                                                                                           , Analysts’ profit estimates for the S&amp;P/ASX 200 Index have jumped nearly 10% this year, about triple the increases for the S&amp;P 500 Index and Japan’s Topix. The improvement follows blockbuster results from market stalwarts including mining giant Rio Tinto Group and lender Commonwealth Bank of Australia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/russias-war-spurs-corporate-exodus-exposes-business-risks </td>
   <td style="text-align:left;"> 2022-03-04 06:43:07 </td>
   <td style="text-align:left;"> Russia’s war spurs corporate exodus, exposes business risks </td>
   <td style="text-align:left;"> Former Gulf Oil CEO Joe Petrowski weighs in on prices for the commodity soaring as the Russia-Ukraine crisis rages on.                                                                                                                                                                                                                                                      , Car factories idled, beer stopped flowing, furniture and fashion orders ceased, and energy companies fled oil and gas projects.                                                                                                                                                                                                                                             , Russia’s invasion of Ukraine has thrown business plans into disarray and forced a growing number of the world’s best known brands — from Apple to Mercedes-Benz and BP — to pull out of a country that’s become a global outcast as companies seek to maintain their reputations and live up to corporate responsibility standards.                                         , A truck drives past cases of beer at the Budejovicky Budvar brewery in Ceske Budejovice, Czech Republic  (AP Photo/Petr David Josek, File / AP Newsroom)                                                                                                                                                                                                                    , Investors were drawn to Russia in search of lucrative profits they thought were worth the geopolitical risks. That calculation has changed after Russia’s war triggered a wave of global sanctions and export restrictions that have thrown its economy into turmoil and disrupted the operations of multinational corporations there.                                      , Russian President Vladimir Putin, left, meets with CEO of Royal Dutch Shell Ben van Beurden in Moscow, Russia, June 21, 2017.  (Sergei Karpukhin/Pool Photo via AP, File / AP Newsroom)                                                                                                                                                                                     , "You basically have Russia becoming a commercial pariah," said economist Mary Lovely, a senior fellow at the Peterson Institute for International Economics in Washington. "Pretty much no company, no multinational, wants to be caught on the wrong side of U.S. and Western sanctions."                                                                                  , They’re also expressing concern about the plight of Ukrainians, showing how they want to be seen coming out on the right side of history.                                                                                                                                                                                                                                   , Complicating companies’ push to flee is an order from Moscow temporarily restricting foreign investors from selling Russian assets. Prime Minister Mikhail Mishustin said Tuesday that it would help investors make "a considered decision" rather than succumb to the political pressure of sanctions. It’s not clear how that may affect corporate efforts to exit Russia., Oil and gas companies, already feeling the heat from climate activists to invest in renewable energy, were among the companies that announced the most rapid and dramatic exits.                                                                                                                                                                                            , Energy firm BP said Sunday that it would abandon its $14 billion stake in Russian state-owned oil and gas company Rosneft. The next day, Shell said it was leaving its joint venture with state-owned Gazprom and its involvement in the now-suspended Nord Stream 2 pipeline built to carry natural gas to Western Europe.                                                 , ExxonMobil said it will pull out of a key oil and gas project and halt any new investment in Russia. All their chief executives said they were shocked and saddened by the increasingly bloody conflict. Smaller energy firms have followed suit.                                                                                                                           , Companies in other industries, including automakers, signaled they’re staying out of the Russian market either out of concern for Ukraine or to comply with Western sanctions.                                                                                                                                                                                              , Toyota is halting production at its St. Petersburg plant that makes RAV4 and Camry models starting Friday because of supply chain disruptions, saying it was watching events "with great concern for the safety of the people of Ukraine."                                                                                                                                  , Mercedes-Benz suspended vehicle exports to Russia and manufacturing there. Volkswagen Group, which also owns Porsche and Audi, did the same, saying it believes a "sustainable solution to the conflict can only be found on the basis of international law."                                                                                                               , Volvo Cars said it stopped deliveries because of "potential risks associated with trading material with Russia," citing Western sanctions. Ford suspended operations.                                                                                                                                                                                                       , A Volvo XC 90 is displayed at Volvo Cars Showroom in Stockholm (Jonas Ekstromer/TT via AP, file / AP Newsroom)                                                                                                                                                                                                                                                              , Harley-Davidson halted motorcycle shipments to Russia, saying its thoughts "continue for the safety of the people of Ukraine." Putin famously rode a three-wheeled Harley on a visit to Ukraine in 2010.                                                                                                                                                                    , Russia's Prime Minister Vladimir Putin, foreground, rides a Harley-Davidson Lehman Trike as he arrives for the meeting with Russian and Ukrainian bikers. (Sergei Karpukhin/Pool Photo via AP, File / AP Newsroom)                                                                                                                                                          , Others with more at stake in Russia might find it harder to navigate the crisis.                                                                                                                                                                                                                                                                                            , French automaker Renault, whose second-biggest market is Russia, said only that it’s temporarily suspending production at its Moscow plant through Saturday "due to some logistics issues," without being more specific.                                                                                                                                                    , Danish brewery group Carlsberg suspended production at its three breweries in Ukraine but indicated operations in Russia, where it owns St. Petersburg-based Baltika Breweries and employs 8,400 people, would continue.                                                                                                                                                    , MANCHIN BLASTS ANTI-FOSSIL FUEL AGENDA AMID RUSSIA-UKRAINE WAR: 'BEYOND THE PALE'                                                                                                                                                                                                                                                                                           , "Millions of lives are being impacted and we strongly condemn the acts of violence and aggression we are witnessing," Vice President of Corporate Affairs Christian Wulff Sondergaard said by email. Carlsberg is obligated to "protect the livelihood of all our employees" in Russia as the economy is increasingly pressured by sanctions, he said.                      , Czech brewer Budvar, which counts Russia as one of its five major markets, halted beer deliveries to the country, saying business is not the top priority and that it’s looking for ways to help, including finding accommodations for Ukrainian refugees.                                                                                                                  , "It’s really tough to do business in Russia under the best of conditions. Now it’s become just crazy. So getting out is a smart business proposal," said James O’Rourke, a professor at the University of Notre Dame’s Mendoza College of Business specializing in reputation management.                                                                                   , Companies will have to chalk up any losses as the cost of doing business.                                                                                                                                                                                                                                                                                                   , "This is like going into business with the Manson family," O’Rourke said, referring to the followers of cult leader Charles Manson. "You honestly do not want your name associated with those people, and it’s probably not going to cost you that much to disinvest."                                                                                                      , Ikea suspended operations at its 17 Russian stores and paused exports and imports. The Swedish furniture giant said, "The war has had a huge human impact" and resulted "in serious disruptions to supply chain and trading conditions."                                                                                                                                    , Fast fashion brand H&amp;M paused sales in Russian stores, expressing concern about the "tragic developments." Nike said on its Russian website it can’t guarantee deliveries.                                                                                                                                                                                                  , Airplane makers Boeing and Airbus stopped supplying parts and service support for Russian carriers.                                                                                                                                                                                                                                                                         , Even Hollywood studios are delaying the release of new films in Russia, which isn’t a leading movie market but typically ranks in the top dozen countries for box office revenue. Warner Bros., the Walt Disney Co. and Sony Pictures cited the "humanitarian crisis."                                                                                                      , The Walt Disney Co. logo appears on a screen above the floor of the New York Stock Exchange  (AP Photo/Richard Drew, File / AP Newsroom)                                                                                                                                                                                                                                    , Netflix is pausing all future projects and acquisitions from Russia. The streaming service reportedly had four Russian projects in the pipeline.                                                                                                                                                                                                                            , Tech companies also headed for the door.                                                                                                                                                                                                                                                                                                                                    , The logo of Apple is illuminated at a store in the city center in Munich, Germany.  (AP Photo/Matthias Schrader, file / AP Newsroom)                                                                                                                                                                                                                                        , Apple stopped selling iPhones and other devices inside Russia, while computer maker Dell Technologies suspended sales in Ukraine and Russia.                                                                                                                                                                                                                                , Google and TikTok blocked Russian state media channels from their platforms after a plea from the European Union. Apple blocked RT News and Sputnik News downloads from its App Store outside Russia.                                                                                                                                                                       , US EXPANDS LIST OF RUSSIAN OLIGARCHS WHO WILL FACE SANCTIONS                                                                                                                                                                                                                                                                                                                , It’s not just sanctions but public sentiment that companies have to respond to as the human costs of the war grow.                                                                                                                                                                                                                                                          , Company commitments to environmental, social and corporate governance, known as ESG, are being put to the test. ESG has become a buzzy acronym that’s increasingly seen as an important way for corporations to tout responsible business credentials.                                                                                                                      , The exterior of the new Warner Bros. Studio Tour Hollywood building  (AP Photo/Chris Pizzello, File / AP Newsroom)                                                                                                                                                                                                                                                          , "But there can also be an element of greenwashing," where companies say things that make it seem like they hold certain values or are on the right side of ESG issues while their practices and behavior suggest otherwise, Columbia Business School associate professor Vanessa Burbano said.                                                                              , "Stakeholders like employees and consumers will want to see if companies’ actions and behaviors are consistent with the communicated support that companies are expressing for Ukrainians," she said.                                                                                                                                                                       , Some companies went beyond halting deliveries or operations.                                                                                                                                                                                                                                                                                                                , READ MORE ON FOX BUSINESS BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                  , Lego, Ford and Volkswagen Group said they would make millions of dollars in charitable donations to support Ukrainian refugees. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-03-03/stocks-set-to-fall-amid-growth-inflation-worries-markets-wrap </td>
   <td style="text-align:left;"> 2022-03-04 06:42:16 </td>
   <td style="text-align:left;"> Stocks Sink Amid Fire at Ukraine Nuclear Plant: Markets Wrap </td>
   <td style="text-align:left;"> Sunil Jagtiani                                                                                                                                                                                                                            , Stocks and equity futures sank Friday and havens including sovereign bonds jumped on reports that a major nuclear power plant is on fire in Ukraine after shelling by Russian troops.                                                     , Japan led losses in an Asian equity gauge, S&amp;P 500 and Nasdaq 100 futures shed more than 1% and European contracts dropped about 3%. Treasuries rallied, with the 10-year yield falling below 1.80%. Gold and the dollar rose. Oil soared. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-03-03/rice-soars-as-ukraine-war-starts-scramble-for-any-and-all-grains?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-03-04 06:36:04 </td>
   <td style="text-align:left;"> Rice Soars as Ukraine War Starts Scramble for Any and All Grains </td>
   <td style="text-align:left;"> Allison Nicole Smith and                                                                                                                                                                                                                                                                                                                , Michael Hirtzer                                                                                                                                                                                                                                                                                                                         , Rice is the latest commodity to get swept up in the turmoil of Russia’s invasion of Ukraine.                                                                                                                                                                                                                                            , Prices for rice are surging because traders are betting it will be an alternative for wheat, which is becoming prohibitively expensive. Exports of wheat from Russia and Ukraine account for more than a quarter of the crop’s trade worldwide and a fifth of corn sales. Shipping in the Black Sea region is already engulfed in chaos. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/uk-politics-60611683?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-04 06:35:44 </td>
   <td style="text-align:left;"> Ukraine: UK sanctions oligarchs Alisher Usmanov and Igor Shuvalov </td>
   <td style="text-align:left;"> The UK has announced sanctions on two more Russian oligarchs - Alisher Usmanov and Igor Shuvalov following Russia's invasion of Ukraine.                                                                                                                                                        , Mr Usmanov's company USM previously had sponsorship ties with Arsenal and - until this week - Everton.                                                                                                                                                                                          , Mr Shuvalov was formerly Russian President Vladimir Putin's deputy prime minister and is currently chairman of the management board of a Russian bank.                                                                                                                                          , The BBC has contacted the two men for their response.                                                                                                                                                                                                                                           , Under the UK government's new restrictions, their assets will be frozen and they will be banned from travelling to the UK.                                                                                                                                                                      , British citizens and businesses will not be allowed to deal with them.                                                                                                                                                                                                                          , Boris Johnson said: "For as long as Putin continues his barbaric attack on innocent Ukrainians we will continue to exert every power we have to inflict maximum economic pain on Putin and his war machine."                                                                                    , And his Foreign Secretary Liz Truss said: "We won't stop here - our aim is to cripple the Russian economy and starve Putin's war machine."                                                                                                                                                      , The government said the two men had "significant interests in the UK and close links to the Kremlin".                                                                                                                                                                                           , Mr Usmanov founded USM Holding company, an investment group that owns iron, steel and copper suppliers and the Megafon telecommunications company.                                                                                                                                              , The company, in which Mr Usmanov holds a 49% stake, sponsored Everton's training ground and had a naming-rights option for Everton's new stadium, due to open in 2024.                                                                                                                          , However, on Wednesday, Everton suspended the company's sponsorship arrangements, saying the club was "shocked and saddened by the appalling events unfolding in Ukraine".                                                                                                                       , Mr Usmanov's business partner Farhad Moshiri - the owner and main investor at Everton - has since stepped down from his role as chairman of USM and announced that he had severed all business links with the Russian.                                                                          , At the club's FA cup match against Boreham Wood on Thursday evening, Everton's players walked out draped in Ukrainian flags, behind 22-year-old Ukrainian defender Vitaliy Mykolenko who has been made captain on just his fourth appearance for his new club.                                  , Mr Usmanov's previous ties with Arsenal ended in 2018 when he sold his 30% stake. At the time he was the second largest shareholder in the north London club.                                                                                                                                   , In addition to connections with Premier League clubs, the government said Mr Usmanov owned Beechwood House in Highgate, worth an estimated £48m, and the 16th century Sutton Place estate in Surrey.                                                                                            , Mr Shuvalov is less well-known in the UK but the Foreign Office said he owned "two luxury apartments in central London worth an estimated £11m".                                                                                                                                                , The Foreign Office also said it had established an Oligarch Taskforce to co-ordinate work to sanction further oligarchs.                                                                                                                                                                        , Earlier this week, the EU froze the assets of the Mr Usmanov, saying he was "a pro-Kremlin oligarch with particularly close ties to Russian president Vladimir Putin".                                                                                                                          , At the time, Mr Usmanov issued a statement calling the EU's decision "unfair" and adding that he would "use all legal means to protect my honour and reputation".                                                                                                                               , Mr Shuvalov, the other man to be sanctioned, has worked in the Russian government as first deputy minister and government chief of staff, as well as acting as an aide to President Putin.                                                                                                      , Since 2018 he has been the chairman of the management board of VEB, one of the Russian banks recently sanctioned by the government.                                                                                                                                                             , On Wednesday, Labour leader Sir Keir Starmer had urged the prime minister to take action against Mr Shuvalov and accused the prime minister of being slow to target other individuals connected with the Putin government.                                                                      , Government sources have told the BBC it could take weeks to put together sanctions against such people.                                                                                                                                                                                         , Labour, and some senior Conservative figures have said the UK should seize oligarchs' UK assets.                                                                                                                                                                                                , Conservative MP Tom Tugendhat, the chairman of the Commons foreign affairs committee, said: "We should be looking immediately to seize those assets linked to those who are profiting from Putin's war machine, holding it in trust and returning it to the Russian people as soon as possible.", Elsewhere, the US has announced fresh sanctions on Russian oligarchs including Mr Usmanov, Mr Shuvalov and Mr Putin's press secretary Dmitry Peskov.                                                                                                                                            , Authorities in France and Germany have seized yachts owned by Mr Usmanov.                                                                                                                                                                                                                       , Meanwhile, Justice Secretary Dominic Raab says the government will look at ways to stop lawsuits being used by wealthy individuals to intimidate journalists and organisations covering their wealth and financial interests.                                                                   , The government is expected to set out a number of options to alter the system, including procedural changes in courts and potential legislation.                                                                                                                                                , Mr Raab told the Telegraph: "We will not have people close to Putin coming here to try and bankrupt people who shine a light on his excesses."                                                                                                                                                  , The obsession continues with the final series of Killing Eve...                                                                                                                                                                                                                                 , Incredible technology takes you on an emotional journey deep inside!                                                                                                                                                                                                                            , The very best from around the world including Beck and The Bridge                                                                                                                                                                                                                               , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-03-03/new-zealand-finance-minister-faces-less-growth-faster-inflation?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-03-04 06:32:08 </td>
   <td style="text-align:left;"> New Zealand Finance Minister Faces Less Growth, Faster Inflation </td>
   <td style="text-align:left;"> Grant Robertson                                                                                                                                                                                                                      , Tracy Withers                                                                                                                                                                                                                        , New Zealand Finance Minister Grant Robertson is bracing for slower-than-expected economic growth and faster inflation as he prepares his annual budget.                                                                              , The country’s surging omicron outbreak will have an impact on the economy this year, although evidence from overseas is that demand bounces back quickly, Robertson said in an interview with Bloomberg late Thursday in Wellington.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 06:15:05 </td>
   <td style="text-align:left;"> Bovespa Ends Near 115,160 </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, ended virtually flat, around 115,160 on Thursday, still near levels not seen since September last year as soaring commodities prices have been lifting the heavyweight industrial sector. Meantime, Federal Reserve Chair Jerome Powell signalled the central bank would likely raise interest rates less than some investors had feared. Investors also continued to monitor developments around the Ukraine conflict and mounting sanctions against Russia. On the domestic data front, the IHS Markit Brazil Manufacturing PMI rose to 49.6 in February of 2022, from a 20-month low of 47.8 in January, pointing to a stabilization of the sector. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/energy/nj-city-council-revoke-licenses-gas-stations-russia-ties </td>
   <td style="text-align:left;"> 2022-03-04 06:13:05 </td>
   <td style="text-align:left;"> NJ city council votes to revoke licenses of gas stations over Russian ties </td>
   <td style="text-align:left;"> Lipow Oil Associates President Andy Lipow weighs in on how Russian sanctions will impact the oil and gas markets and Biden shifting the blame to big oil and Saudi Arabia as prices soar.                                                                                                                                                                                                                                                                                 , The city council of Newark, New Jersey, has voted unanimously to suspend the business licenses of Russian oil company franchises within its community, specifically two Lukoil stations along one of its highways.                                                                                                                                                                                                                                                        , The council voted Wednesday to request that the city administrator freeze Lukoil franchises' ability to do business in Newark.                                                                                                                                                                                                                                                                                                                                            , The move was criticized by the business owner, who said at a press conference that he was against the Russian invasion and was an American citizen. However, North Ward Council Member Anibal Ramos, who sponsored the legislation, said that the temporary decision was not intended to harm local residents, and local companies are stepping up to offer employment as the war in Ukraine rages.                                                                       , "We recognize that Lukoil PJSC is the second-largest oil producer in Russia," Ramos told Fox News Digital in an exclusive interview. "There are definitely ties between Lukoil and the Russian government … And a number of oligarchs are involved in the ownership. Since 2014, the U.S. has been imposing very targeted sanctions against Lukoil."                                                                                                                      , JEN PSAKI TELLS FOX NEWS RUSSIAN ENERGY SANCTIONS NOT 'OFF THE TABLE' AS PUTIN'S ASSAULT ON UKRAINE CONTINUES                                                                                                                                                                                                                                                                                                                                                             , "What we did is we passed a resolution asking the city's administrator to suspend the business license for Lukoil gas stations in Newark," the councilman explained. "We currently have two of those doing business in our city that in operation requires a municipal license."                                                                                                                                                                                          , The logo of Russia's oil company Lukoil is pictured at one of its petrol stations in Moscow April 16, 2021.  (Kirill Kudryavtsev/AFP)                                                                                                                                                                                                                                                                                                                                     , "I stand with Ukraine, and I'm full in support of Russian sanctions, however I am baffled and confused how shutting down an American-based small business owner is sending a message to support," station owner Roger Verma told a local CBS affiliate.                                                                                                                                                                                                                   , Lukoil is the second-largest oil producer in Russia and is privately held by a collection of Russian oligarchs with direct ties to Russian President Vladimir Putin. The Lukoil stations in Newark are franchised, meaning they are owned by Lukoil North America, which is directly owned by the larger international corporation.                                                                                                                                       , While the gas pumps at these locations are reportedly filled with American oil products, the property itself is property of Lukoil, according to Ramos.                                                                                                                                                                                                                                                                                                                   , "The franchise owner himself, when he showed up at the press conference yesterday, acknowledged that the property where his franchise actually is located is owned by Lukoil directly," Ramos said.                                                                                                                                                                                                                                                                       , Fox News attempted to contact the two Newark stations owned by Lukoil but were unable to get through.                                                                                                                                                                                                                                                                                                                                                                     , "For us, it's within our purview to grant business licenses within the city," Ramos said. "We recognize that Lukoil has direct ties to Russia, and Russia is right now leading the charge on this invasion of Ukraine and threatening the lives and actually resulting in the deaths of thousands of Ukrainians. This is the city of Newark standing in solidarity with the people of Ukraine in fighting for democracy."                                                 , CLICK HERE TO GET THE FOX NEWS APP                                                                                                                                                                                                                                                                                                                                                                                                                                        , "It doesn't hurt Lukoil, and it doesn't hurt Russia," Sal Risalvato, executive director of the New Jersey Gasoline, Convenience Store and Automotive Association, told the local CBS outlet. "All Lukoil does is purchase gasoline from the Phillips 66 Refinery, the Bayway Refinery in Linden, they mark it up a couple of pennies and they sell it to the franchise small business owner that is leasing that property from them and purchasing the product from them.", However, the city is trying its best not to leave Lukoil employees within their community high and dry.                                                                                                                                                                                                                                                                                                                                                                   , "We've had businesses within our city – Paramount Bakery is one of them, which is a large bakery located in Newark – that reached out to us prior to yesterday's council meeting and made an offer of employment to anyone who was displaced if the city did follow through," Ramos told Fox.                                                                                                                                                                             , "Our intentions here are not to punish anyone locally. I think Newark stands in solidarity with a number of democratic countries around the world that have imposed different sanctions on the Russian Federation in hopes that this conflict ends."                                                                                                                                                                                                                      , "Collectively, we can definitely ensure … that we have things in place to support local residents who could be affected. Today we got a call from a second employer who I haven't had a chance to follow up with," Ramos added.                                                                                                                                                                                                                                           , Cars at a Lukoil petrol station in the city of Rostov-on-Don, southwest Russia, March 12, 2020. (Valery Matytsin/TASS via Getty Images)                                                                                                                                                                                                                                                                                                                                   , Ramos says that Paramount Bakery and any other local employers helping to find work for Newark residents displaced by the sanctions are an example of community responsibility and willingness to stand united.                                                                                                                                                                                                                                                           , "I think the images that we see on a daily basis are horrific to all of us," Ramos said. "And Paramount Bakery is reaching out to a municipal official offering support during an action that the city is considering.                                                                                                                                                                                                                                                    , "The intentions of these actions is definitely not to harm people locally, but it's to send a unified message to the Russian Federation that we're not going to stand idly by while a million Ukrainians have to find refuge in other countries and people are dying every single day." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/03/03/ukraine-refugee-crisis-poland-border-sidner-pkg-lead-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-04 06:12:32 </td>
   <td style="text-align:left;"> 'We were shielding our children with our bodies': Ukrainian parents on evacuating Kyiv - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/sweetgreen-stock-rallies-more-20/story.aspx?guid={35E9C66F-0748-43BC-A5A3-7E852D165277}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-04 06:00:32 </td>
   <td style="text-align:left;"> Sweetgreen stock rallies more than 20% after Q4 sales beat - MarketWatch </td>
   <td style="text-align:left;"> Sweetgreen Inc. 
        SG,
        -11.34%
       reported mixed quarterly results late Thursday, and the stock rallied more than 20% after the fast-casual restaurant said it demonstrated "continued recovery from the pandemic" and benefited from higher prices for its salads and other health-minded meals. Sweetgreen said it lost $66.2 million, or $1.14 a share, in the fourth quarter, compared with a loss of $41.1 million, or $2.49 a share, in the year-ago period. Revenue rose 63% to $96.4 million, the company said. Analysts polled by FactSet expected a loss of 66 cents a share on sales of $84.7 million. Same-store sales rose 36%, benefiting from an increase in the number of transactions in addition to the menu price increases, the company said. Sweetgreen, which had its successful initial public offering in November, guided for 2022 sales between $515 million and $535 million and "at least" 35 net new restaurant openings, barring "no additional COVID headwinds," it said. The company also issued a one-time quarterly guidance for its first quarter, saying it expects seven net new restaurant openings and revenue between $100 million and $102 million. Sweetgreen became a public company in November, with the stock opening nearly 90% above its upsized IPO price. The company is "proud of our financial performance following a successful IPO and remain laser focused on executing," co-founder and Chief Executive Jonathan Neman said in a statement. Shares of Sweetgreen ended the regular trading day down 11%. 
, The data-software firm projected fiscal 2023 results that were below Wall Street’s estimates. CEO Frank Slootman explains why.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-03-03/stock-trader-s-guide-to-china-s-weeklong-political-meeting?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-03-04 06:00:00 </td>
   <td style="text-align:left;"> Stock Trader’s Guide to China’s Weeklong Political Meeting </td>
   <td style="text-align:left;"> Flags fly at the Great Hall of the People in Beijing, China.                                                                                                                                                                                                                , Any policy signals on China’s battered property and tech sectors will be keenly watched by equity investors as they turn their focus to the nation’s top political meeting that starts Saturday.                                                                            , Relief for the real estate sector, which has been dragged by slumping sales and an unprecedented cash squeeze, will be on the top of the agenda for traders. They’ll also be on the lookout for any further fallout from the yearlong crackdown on the nation’s tech sector. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/avgo:us </td>
   <td style="text-align:left;"> 2022-03-04 05:44:20 </td>
   <td style="text-align:left;"> Broadcom Inc earnings above expectations at 8.39 USD </td>
   <td style="text-align:left;"> Broadcom Inc (AVGO) released earnings per share at 8.39 USD, compared to market expectations of 8.13 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 05:39:20 </td>
   <td style="text-align:left;"> TSX Ends Virtually Flat </td>
   <td style="text-align:left;"> Canadian shares gave up early gains to end virtually flat on Thursday, with benchmark S&amp;P/TSX bottoming around 21,250 highs as losses in healthcare and cyclicals shares offset gains in materials. On the earnings front, Canadian Natural Resources increased dividends as Q4 profits surged, as the global recovery and tight supplies fueled a rally in oil prices to multi-year highs. Also, Toronto-Dominion Bank reported higher quarterly profits, underpinned by revenues from its Canadian and American retail banking units, which more than offset higher costs at its wholesale banking unit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cost:us </td>
   <td style="text-align:left;"> 2022-03-04 05:38:50 </td>
   <td style="text-align:left;"> Costco Wholesale earnings above expectations at 2.92 USD </td>
   <td style="text-align:left;"> Costco Wholesale (COST) released earnings per share at 2.92 USD, compared to market expectations of 2.69 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/amazon-gives-ftc-deadline-mid-march/story.aspx?guid={92023E76-5228-4EEB-A3CE-8FE1850330BE}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-04 05:14:01 </td>
   <td style="text-align:left;"> Amazon gives FTC deadline in mid-March to act on MGM acquisition: report - MarketWatch </td>
   <td style="text-align:left;"> Amazon.com Inc. 
        AMZN,
        -2.73%
       has given the Federal Trade Commission a mid-March deadline to rule on Amazon's proposed $6.5 billion purchase of the MGM movie and television studio, according to a Wall Street Journal report on Thursday. The ultimatum came after the e-commerce giant certified to the FTC that it provided all the information requested by antitrust investigators, the Journal reported, citing people familiar with the matter. If the FTC doesn't file a legal challenge before the deadline, Amazon could be free to consummate the deal. However, the commission may continue to review a deal even if it closes. Amazon was not immediately available for comment., Costco Wholesale Corp. late Thursday reported quarterly results and sales that topped Wall Street expectations, but the stock headed lower as same-store sales growth slowed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mrvl:us </td>
   <td style="text-align:left;"> 2022-03-04 05:12:51 </td>
   <td style="text-align:left;"> Marvell Technology earnings above expectations at 0.50 USD </td>
   <td style="text-align:left;"> Marvell Technology (MRVL) released earnings per share at 0.50 USD, compared to market expectations of 0.48 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 05:06:00 </td>
   <td style="text-align:left;"> Wall Street Closes Down </td>
   <td style="text-align:left;"> The Dow Jones lost around 0.3%, while the S&amp;P 500 and the tech-heavy Nasdaq underperformed, falling 0.5% and 1.6%, respectively, as investors remained focused on the Russia-Ukraine conflict and Federal Reserve Chairman Jerome Powell’s Senate testimony. Technology shares were among the worst performers, with the prospect of higher interest rates threatening to undermine the valuations of those companies, whose profits lie further in the future. Powell confirmed that a 25 basis point rate would come in March while opening the door for a more aggressive move if inflation does not abate as expected. Meanwhile, initial jobless claims fell way more than anticipated to an eight-week low of 215K, and the Challenger report showed job cuts were the lowest in three months. Snowflake plunged over 15% after the company issued weaker-than-expected sales guidance. Kroger climbed over 11%, while Best Buy added over 9% following upbeat earnings reports. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/world-us-canada-60607790?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-04 04:52:18 </td>
   <td style="text-align:left;"> Biden imposes sanctions on Russian oligarchs, 'Putin's cronies' </td>
   <td style="text-align:left;"> The US has announced fresh sanctions on Russian oligarchs - the latest attempt to squeeze President Vladimir Putin as his invasion of Ukraine continues.                                                                                                                               , The new penalties will target members of the Russian elite, their families and close associates, cutting them off from the US financial system.                                                                                                                                        , "The goal is to maximise the impact on Putin," US President Joe Biden said.                                                                                                                                                                                                            , Dmitry Peskov, Mr Putin's press secretary, is among those targeted in the latest blockade.                                                                                                                                                                                             , Mr Peskov, 54, is already sanctioned by the European Union, and now joins a list of eight oligarchs and nearly two dozen of their family members and associates whose assets in the US will be frozen, and have their American properties blocked from use.                            , Another 19 oligarchs - including Putin ally Alisher Burhanovich - and 47 of their family members will face US visa restrictions.                                                                                                                                                       , "These individuals have enriched themselves at the expense of the Russian people," the White House said on Thursday. "We will continue to work with our allies and partners to hold accountable the Russian oligarchs and corrupt leaders who are profiting from this violent regime." , Earlier this week, Mr Biden had promised to go after Russian oligarchs who have "bilked [stolen] billions of dollars off this violent regime" when speaking of the Ukraine crisis at his State of the Union address.                                                                   , On Thursday, Mr Biden said the existing sanctions carried out with Western allies, such as blocking Moscow from the Swift international payments system and restrictions against the Russian central bank, were already having a "profound" impact.                                    , "Our interest is maintaining the strongest unified economic impact campaign on Putin in all history and I think we're well on the way to doing that," he said.                                                                                                                         , The UK also announced further sanctions against two Russian oligarchs on Thursday.                                                                                                                                                                                                     , The obsession continues with the final series of Killing Eve...                                                                                                                                                                                                                        , Incredible technology takes you on an emotional journey deep inside!                                                                                                                                                                                                                   , The very best from around the world including Beck and The Bridge                                                                                                                                                                                                                      , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/tv/2022/03/03/amanpour-andrei-kozyrev-russia-ukraine-putin-lavrov.cnn </td>
   <td style="text-align:left;"> 2022-03-04 04:02:26 </td>
   <td style="text-align:left;"> Fmr. Russian Foreign Minister: Ukraine war 'a barbaric act' - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/sp-500-could-fall-below/story.aspx?guid={9048A297-3B8F-4618-AA5D-CE40593D0560}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-04 03:39:47 </td>
   <td style="text-align:left;"> S&amp;P 500 could fall below 4,000 before downtrend runs its course, BTIG chart watcher says - MarketWatch </td>
   <td style="text-align:left;"> BTIG technical analyst Jonathan Krinsky said that while the S&amp;P 500 
        SPX,
        -0.53%
       has room to rally further without breaking out of its current downtrend channel, but he remains "cautious" on stocks given that market internals have been "struggling." In particular, Krinsky noted that the percentage of S&amp;P 500 components that have been trading below their 200-day moving average (DMA), which many view as a dividing line between longer-term uptrends and downtrends, ahs been below 55% for most of the days for the past six weeks. "This needs to change for the trend to change," Krinsky wrote in a note to clients. Currently, 230 S&amp;P 500 components, or 45.5%, are trading below their 200-DMA. "While select pockets of strength persist, the surge in commodity prices along with widening credit spreads and lack of breadth improvement suggest we have yet to see a final capitulation event," Krinsky wrote. He believes the S&amp;P 500 could fall below 4,000 before the correction runs its course. The top of the downtrend channel Krinsky referred to is about 1.8% above current levels, while 4,000 is about 8.8% below. , "As towering skyscrapers rose in Moscow atop a pile of oil cash, Putin’s government became more backward-looking and more isolated," Lukas I. Alpert writes in a commentary piece.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/par-pacific-suspend-russian-oil/story.aspx?guid={DD2DF6C1-67B0-49DC-AAF0-3274A8F7E428}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-04 03:29:19 </td>
   <td style="text-align:left;"> Par Pacific to suspend Russian oil purchases for its Hawaii refinery - MarketWatch </td>
   <td style="text-align:left;"> Par Pacific Holdings Inc. 
        PARR,
        -5.10%
       said Thursday that is will suspend purchases of Russian crude oil for its Hawaii refinery. "We will continually monitor and evaluate our posture on Russian crude over the coming weeks and months," the energy infrastructure company said in a statement. "In the meantime, we are turning to other grades of crude, principally from North and South America, to meet fuel production requirements." The company said it will work closely with its customers and partners to make future decisions to support "energy assurance" for Hawaii. The stock dropped 3.2% in afternoon trading toward the lowest close since Dec. 1, 2020. It has shed 10.2% over the past three months, while continuous crude oil futures 
        CL00,
        +3.70%
       have run up 65.1% and the S&amp;P 500 
        SPX,
        -0.53%
       has lost 3.2%., Costco Wholesale Corp. late Thursday reported quarterly results and sales that topped Wall Street expectations, but the stock headed lower as same-store sales growth slowed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/copper </td>
   <td style="text-align:left;"> 2022-03-04 03:03:46 </td>
   <td style="text-align:left;"> Copper Prices Approach All-Time High </td>
   <td style="text-align:left;"> Copper surged to above $4.75 per pound in the first week of March, closing on the record high of $4.9 hit in May 2021 on concerns of supply disruptions due to war in Ukraine and low global stockpiles. Copper stocks held by LME, Shanghai Futures Exchange and Comex fell to just 200,000 tonnes in February, enough to cover only 3 days of global consumption. Suppliers are especially low in Europe and although Russia accounts only for 4% of global production Europe is the main export market. Adding to woes, the biggest producer Chile, recorded its lowest January output since 2011 with production sinking 15% compared to December and 7.5% from January 2021. On the other side, copper usage is surging, especially in developed countries, with increasing demand for electric vehicles and wind farms, solar panels, and the power grid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-targets-more-russian-oligarchs/story.aspx?guid={C4D47C68-E726-473E-8C0B-516978D664EA}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-04 03:00:17 </td>
   <td style="text-align:left;"> U.S. targets more Russian oligarchs with sanctions - MarketWatch </td>
   <td style="text-align:left;"> The Biden administration on Thursday announced that it's coordinating with U.S. allies to sanction additional Russian oligarchs and their family members, as part of the Western response to Russia's invasion of Ukraine. "These individuals and their family members will be cut off from the U.S. financial system, their assets in the United States will be frozen and their property will be blocked from use," the White House said in a statement. The individuals who are facing "full blocking sanctions" include Dmitry Peskov, press secretary for Russian President Vladimir Putin, as well as Alisher Usmanov, whose megayacht was recently seized by Germany. "The United States will also impose visa restrictions on 19 oligarchs and 47 of their family members and close associates," the White House said.  , The House committee investigating the U.S. Capitol insurrection subpoenaed Kimberly Guilfoyle, the fiancée of former President Donald Trump’s eldest son, on Thursday after she abruptly ended a voluntary interview with lawmakers last week.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/energy/fmr-gulf-oil-ceo-on-prices-surging-as-russia-ukraine-crisis-rages-on </td>
   <td style="text-align:left;"> 2022-03-04 02:57:38 </td>
   <td style="text-align:left;"> Fmr. Gulf Oil CEO on prices surging as Russia-Ukraine crisis rages on: US 'shooting ourselves in the foot' </td>
   <td style="text-align:left;"> Former Gulf Oil CEO Joe Petrowski weighs in on prices for the commodity soaring as the Russia-Ukraine crisis rages on.                                                                                                                                                                                                 , Former Gulf Oil CEO Joe Petrowski weighed in on prices for the commodity surging as the Russia-Ukraine crisis rages on, arguing that the U.S. is "shooting ourselves in the foot" with respect energy.                                                                                                                 , He warned Thursday that the Chinese are building oil stocks, which he argued nations typically do "before they go into a military operation." Petrowski made the comments as fears mount that a Chinese invasion of Taiwan could be next if Beijing becomes emboldened by the Russian invasion of Ukraine.             , Petrowski also pointed out, while the Chinese build oil stocks, United States is reducing them.                                                                                                                                                                                                                        , He provided the insight on "Cavuto: Coast to Coast" as oil prices had continued to climb on Thursday with shipping and supply concerns brewing over Russia's invasion of Ukraine.                                                                                                                                      , U.S. crude hit $113.06 per barrel in electronic trading on the New York Mercantile Exchange early Thursday and later dropped to $109.84. Brent, the price basis for international oils, moved to $115.08 per barrel in London and later fell to around $113.                                                           , Russia's full-blown attack on Ukraine, which started last Thursday, could push energy prices even higher with many NATO countries such as Germany dependent on Russian oil to fuel their countries.                                                                                                                    , That dependence has limited the international response to Russia's invasion, with sanctions being specifically designed not to target Russian fuel exports amid fears such a move could send energy prices soaring in Europe.                                                                                          , The Schork Group principal Stephen Schork initially predicted Brent crude will hit $116 per barrel this month and notes it only took a few days to hit that mark.                                                                                                                                                      , Petrowski argued on Thursday that reducing U.S. oil production and exports drives up world oil prices, offering this as an explanation for why Brent Crude is "going higher, which is how most U.S. gasoline is priced."                                                                                               , In a series of orders aimed at combating climate change, President Biden temporarily suspended the issuance of oil and gas permits on federal lands and waters and canceled the Keystone XL oil pipeline project.                                                                                                      , President Biden revoked the permit for the 1,700-mile pipeline on his first day in office, ending a project that was expected to employ more than 11,000 Americans last year.                                                                                                                                          , RUSSIA-UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                           , Biden has come under increasing pressure to walk back resistance to domestic oil production in the wake of Russia's invasion of Ukraine, with Rep. August Pfluger, R-Texas, arguing such a move would help the U.S. "regain our dominance on the world stage."                                                         , The 31 members of the International Energy Agency, the club of major oil consumers, agreed Tuesday to release 60 million barrels of crude from stockpiles.                                                                                                                                                             , "America will lead that effort, releasing 30 million barrels of oil Strategic Petroleum Reserve. We are prepared to do more united with our allies," President Biden said during the State of the Union address on Tuesday night. "These steps will help blunt gas prices here at home."                               , In an all-encompassing interview with 'Mornings with Maria,' former President Trump reacts to President Biden's State of the Union address, discusses oil prices and the Russia-Ukraine conflict.                                                                                                                      , The announcement to release crude from stockpiles failed to calm concern about disruption in supplies from Russia, the second-biggest exporter behind Saudi Arabia.                                                                                                                                                    , Also, as President Biden and Europeans avoid removing Russian banks that deal in oil from the international SWIFT banking system, Republicans and Democrats in Congress are calling for an even more drastic move to ban Russian oil.                                                                                  , RUSSIA'S ECONOMY GETS NAILED: WHAT'S BEEN DONE                                                                                                                                                                                                                                                                         , Republicans have been making similar comments for weeks. But some Democrats are now urging the administration to consider that course of action too, as Russian President Vladimir Putin's brutal assault on Ukraine intensifies.                                                                                      , Sen. Joe Manchin, D-W.Va., Thursday said he has "many" co-sponsors from both parties on a bill he's introducing with Sen. Lisa Murkowski, R-Alaska, to ban Russian oil imports. He also upbraided administration officials for blocking increases in domestic energy production, including on natural gas in his state., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                            , The Biden administration has resisted calls both to increase domestic energy production and to block Russian oil. White House deputy press secretary Karine Jean-Pierre told reporters Wednesday, "Given high oil and gas prices… cutting off Russian oil/gas will drive prices up to Putin’s benefit."                , Former Gulf Oil CEO Joe Petrowski says the Chinese are building oil stocks, while the U.S. is reducing them, a move that he warns happens before a military operation.                                                                                                                                                 , President Biden said Wednesday that "all options are on the table" when it comes to a Russian oil ban.                                                                                                                                                                                                                 , Some progressive Democrats are even open to the idea. Rep. Ro Khanna, D-Calif., told Fox News in a phone interview Thursday that the president should consider banning Russian oil.                                                                                                                                    , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                , FOX Business’ Ken Martin, Tyler Olson and Fox News' Kristina Biddle contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/03/how-the-ukraine-russia-conflict-may-hit-your-wallet.html </td>
   <td style="text-align:left;"> 2022-03-04 02:44:42 </td>
   <td style="text-align:left;"> How the Ukraine-Russia conflict may push up prices for Americans </td>
   <td style="text-align:left;"> , The economic effects of Russia's invasion of Ukraine a week ago have reverberated around the globe — leaving many households to wonder how the conflict might hit their wallet.                                                                                                                              , The short answer: Prices may be going up, especially for gasoline (and indeed already have). Costs for food and goods like smartphones may also rise, according to economists.                                                                                                                               , Inflation would largely result from shortages and rising costs of raw materials like oil, wheat and metals like palladium — all of which Russia is a major producer.                                                                                                                                         , It would also come at a time when consumer prices are already rising at their fastest annual pace in 40 years.                                                                                                                                                                                               , Yet some of the inflation (if it comes to pass) will likely take months to appear, economists said. The timing and scale are hard to predict given the fluidity of the military conflict, novelty of Western sanctions against Russia and possibility of yet harsher ones.                                   , "What makes projecting this stuff so difficult is, all these measures are so new and so unprecedented as a model," according to Julia Friedlander, a senior fellow at the Atlantic Council and a former advisor on sanctions policy at the U.S. Treasury Department.                                         , "What's it like to take the 11th largest economy offline in the course of days?" she said.                                                                                                                                                                                                                   , The Federal Reserve is also expected to start raising interest rates this month to fight inflation.                                                                                                                                                                                                          , The price of gasoline is how consumers are most likely to feel the war's inflationary impact in the short term, according to economists. Indeed, gas prices have risen since Russia's saber-rattling started, even before the Feb. 24 invasion.                                                              , Crude oil is the main component of gasoline.                                                                                                                                                                                                                                                                 , It accounts for 56% of what Americans pay at the pump, according to the Energy Information Administration. That's why higher oil prices often translate to higher gas prices.                                                                                                                                , The Ukraine-Russia conflict pushed U.S. oil prices on Thursday to their highest level since 2008, at well over $100 a barrel. The global price jumped to a high unseen since 2012.                                                                                                                           , More from Personal Finance:Have buyer's remorse? Inflation may be to blameHow to qualify for in-state college tuitionA 4-day workweek doesn't mean less work                                                                                                                                                 , Gasoline prices, in turn, edged up to $3.61 a gallon, on average, as of Monday — a jump of 33 cents a gallon since the beginning of 2022, according to federal data.                                                                                                                                         , If high oil prices are sustained, the average cost may soon breach $4 a gallon, according to Andrew Hunter, a senior U.S. economist at Capital Economics.                                                                                                                                                    , That price would translate to an additional $75 billion of annual spending for households to fill up their gas tanks (relative to prices of $3.40 a gallon at the end of January), Hunter wrote in a research note Tuesday. The dynamic could cut households' disposable income by 0.5%, he said.            , "The single biggest issue is definitely what's happening to oil prices," Hunter said of the crisis' consumer impact. "It looks like there's more pain to come, unfortunately."                                                                                                                               , President Joe Biden acknowledged the likely financial sting in his State of the Union speech Tuesday night. The U.S. and 30 other countries are releasing 60 million barrels of oil from strategic stockpiles, only the fourth time such a coordinated release has occurred, to try diluting the price surge., "A Russian dictator, invading a foreign country, has costs around the world," Biden said. "These steps will help blunt gas prices here at home."                                                                                                                                                             , The Russia-Ukraine conflict has the potential to impact food prices — though the effects will likely be felt most acutely overseas, economists said.                                                                                                                                                         , Russia is the world's largest wheat exporter. Ukraine and Russia together account for almost 30% of global wheat exports.                                                                                                                                                                                    , Wheat prices on Wednesday surged to their highest level in 14 years. That could impact prices for bread, pasta, cereal, baked goods and other wheat-reliant foods, if producers pass higher costs on to consumers.                                                                                           , Russia and Ukraine are also major exporters of other food products like barley, sunflower seed oil and corn.                                                                                                                                                                                                 , However, the U.S. is a net exporter of agricultural commodities, particularly wheat, corn and soybeans, which will likely dilute any impact, according to Hunter.                                                                                                                                            , "I wouldn't expect grocery prices to suddenly start rising now because of these moves," he said. "If they're sustained, it's something you could potentially start to see over the coming months."                                                                                                           , Higher food prices are much more of an issue for the developing world, Friedlander said. Turkey, Egypt and Kazakhstan are the three biggest buyers of Russian wheat, respectively, for example.                                                                                                              , "I don't think it will affect the price of bread in Ohio," Friedlander said.                                                                                                                                                                                                                                 , Russia is the world's largest producer of palladium, supplying about a third of global demand.                                                                                                                                                                                                               , Palladium is a metal used to manufacture semiconductor chips, also known as microchips, which are found in a range of consumer electronic products like smartphones, computers, TVs and digital cameras. Ukraine and Russia also account for the bulk of U.S. neon supply, also used for chip production.    , Palladium is also a key metal used in catalytic converters, which control tailpipe emissions from cars.                                                                                                                                                                                                      , "[That] will trickle down to production of high-end technology that relies on the Russian market," Friedlander said of Russia's palladium exports.                                                                                                                                                           , "It'll take a while for the price to rise in the iPhone you buy, but eventually that could [happen]," she added.                                                                                                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                       , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                       , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                             , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                             , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                           , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/white-house-says-theres-no/story.aspx?guid={8B503548-7AE8-43FA-BA4F-5118E60B15BA}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-04 02:43:35 </td>
   <td style="text-align:left;"> White House says there's no 'strategic interest' in reducing oil supplies as Pelosi calls for Russian ban - MarketWatch </td>
   <td style="text-align:left;"> The Biden administration on Thursday poured cold water on banning oil 
        CL.1,
        +3.62%
       imports from Russia, a move that some in Congress including House Speaker Nancy Pelosi are calling for. "We don't have a strategic interest in reducing the global supply of energy," White House press secretary Jen Psaki told reporters at a daily briefing. "Less supply raises prices," she said. Psaki did not completely close the door to a future ban, however, saying "I don't have any assessment of that for you," when directly asked if the administration is moving closer to a ban. Pelosi earlier on Thursday threw her support behind a Senate bill that aims to ban the import of Russian oil into the U.S., as part of the Western response to Russia's invasion of Ukraine. "I'm all for that. Ban it," the California Democrat told reporters., Russian markets have been closed for four straight days after the country's invasion of Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/balance-of-trade </td>
   <td style="text-align:left;"> 2022-03-04 02:23:36 </td>
   <td style="text-align:left;"> Brazil Trade Surplus Widens in February </td>
   <td style="text-align:left;"> Brazil recorded a trade surplus of $4 billion in February of 2022 from a $1.8 billion surplus in the corresponding month of the previous and compared with market expectations of a $3.55 billion surplus. Exports jumped 32.6 percent to $22.9 billion amid higher sales of agricultural products (114.2 percent) and manufactured products (29.0 percent). Among major trading partners, shipments advanced to China, Hong Kong and Macau, the EU, the US, and Argentina. Meanwhile, imports rose 22.9 percent to $18.8 billion, led by purchases of mining products (142.3 percent) and manufactured products (19.3 percent). Imports went up mainly from China, Hong Kong and Macau, the US and the EU. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/tj-maxx-parent-divest-stake/story.aspx?guid={DFF120F3-DBBE-4B1B-A429-01AA09462454}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-04 02:20:31 </td>
   <td style="text-align:left;"> TJ Maxx parent to divest stake in overseas off-price retailer with 400 stores in Russia - MarketWatch </td>
   <td style="text-align:left;"> TJX Cos. 
        TJX,
        -0.62%
       said in a Thursday filing that it will divest its equity ownership in Familia, a Luxembourg-based off-price retailer with 400 stores in Russia. TJX, which is parent company to HomeGoods and TJ Maxx, says it is taking the step "in support of the people of Ukraine." In addition to the divestiture, the company has pulled two of its executives, Group President Doug Mizzi and Chief Financial Officer Scott Goldenberg, from the Familia board, effective immediately. TJX took a $225 million, 25% non-controlling, minority interest in Familia in November 2019. As of January 29, 2022, the carrying value of TJX's investment was $186 million. TJX may have to record an impairment charge from the sale. TJX missed profit and sales expectations in its most recent earnings report. The company's stock is up 3.1% for the past year while the S&amp;P 500 index 
        SPX,
        -0.53%
       has gained nearly 15%., The World Health Organization is updating its guidelines on COVID-19 treatments to include molnupiravir, the antiviral developed by Merck &amp; Co., the first such oral therapy to be added to the agency's arsenal.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/verizon-tmobile-waiving-calling-texting-fees </td>
   <td style="text-align:left;"> 2022-03-04 02:17:27 </td>
   <td style="text-align:left;"> Ukraine latest: Verizon, T-Mobile waive international call and texting charges </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines.                                                                                                                                                                                                                                                                                                       , Cell phone carriers Verizon and T-Mobile are making it easier for customers to stay connected with their loved ones in Eastern Europe by waiving international call and texting charges.                                                                                                                                                              , Verizon's international calling, texting and in-country data charges will be waived for customers in several countries through March 10, according to the carrier. This impacts consumer and business wireless customers making calls and sending messages to and from Hungary, Moldova, Poland, Romania, Slovakia and Ukraine, according to Verizon. , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                               , Residential landline customers will also have international charges waived to those countries, the company said, adding that "customers do not have to take any action to take advantage of these offers."                                                                                                                                            , Local militiaman Valery, 37, carries a child as he helps a fleeing family across a bridge destroyed by artillery on the outskirts of Kyiv, Ukraine, Wednesday, March 2. 2022. (AP Photo/Emilio Morenatti / AP Newsroom)                                                                                                                               , "Given the ongoing situation in Eastern Europe, Verizon is expanding its relief offer in order to keep its customers connected to friends and loved ones in the affected areas," the company said.                                                                                                                                                    , Likewise, T-Mobile announced that it waived international long-distance and international roaming charges for calls and text messages that are being made to and from the United States, Ukraine, Belarus, Hungary, Moldova, Poland, Romania and Slovakia.                                                                                            , This applies to all T-Mobile and Sprint postpaid consumer and business customers as well as T-Mobile prepaid and Metro customers through March 9, according to T-Mobile.                                                                                                                                                                              , A woman cries outside houses damaged by a Russian airstrike, according to locals in Gorenka, outside the capital of Kyiv, Ukraine, Wednesday, March 2, 2022.  (AP Photo/Vadim Ghirda / AP Newsroom)                                                                                                                                                   , "We recognize that many T-Mobile customers and their loved ones may be impacted by the events taking place in Ukraine," the company said last week right after Russian forces invaded Ukraine. "As this situation evolves and the need for reliable connectivity increases, we are offering support to those who need it."                            , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                           , Both carriers have also launched a text-to-donate campaign to help customers donate to causes supporting those impacted by the war on Ukraine.                                                                                                                                                                                                        , Verizon customers can text UKRAINE to 80100 to make a one-time $10 donation to UNICEF, which will help fund "trucking safe water to conflict-affected areas, prepositioning health and hygiene supplies and working with municipalities to ensure help for children and families in need," Verizon said.                                              , The donation will also help "provide psychosocial support, learning services and emergency cash assistance," according to the company.                                                                                                                                                                                                                , A Polish border guard assists refugees from Ukraine as they arrive to Poland at the Korczowa border crossing Feb. 26, 2022. (AP Photo/Czarek Sokolowski / AP Newsroom)                                                                                                                                                                                , Texting UKRAINE to 52000 will issue a one-time $10 donation to the Salvation Army National Corporation.                                                                                                                                                                                                                                               , "Your donation will provide food, clothes, blankets, shelter and spiritual care to the affected families and individuals who have been displaced from their homes and are seeking refuge," Verizon said.                                                                                                                                              , Additionally, texting UKRAINE to 25383 will issue a one-time $25 donation to the International Rescue Committee, which is working to provide food, medical care and emergency supplies to refugee families in Ukraine, Verizon said.                                                                                                                  , Similarly, T-Mobile said its customers can also text UKRAINE to 25383 to make a one-time $25 donation to the International Rescue Committee and UKRAINE to 80100 to make a one-time $10 donation to support UNICEF.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/corn </td>
   <td style="text-align:left;"> 2022-03-04 02:14:00 </td>
   <td style="text-align:left;"> Corn Hits 8-1/2-year High </td>
   <td style="text-align:left;"> Chicago corn futures traded above $7.75 a bushel, the highest since June 2013, as Russia's invasion of Ukraine has limited supplies from one of the world's biggest exporting regions. Ukraine has suspended commercial shipping at its ports after Russian forces invaded the country, while grain trade from Russia paused as the West imposed fresh sanctions on Moscow. With the conflict likely to continue and workers delegated into the army, transport and logistics in chaos, prices have room for further upside momentum. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/apple-china-russia </td>
   <td style="text-align:left;"> 2022-03-04 02:07:20 </td>
   <td style="text-align:left;"> Is Apple ready to get tough on China or only Russia? </td>
   <td style="text-align:left;"> Former Sen. Joe Lieberman, D-Conn., discusses Russian President Vladimir Putin's nuclear threat and whether NATO should take a more hands-on approach with regard to Ukraine, arguing the conflict will 'define how secure the world is' in the future.                                                                                                                   , The same U.S. companies rushing to sever ties with Russia amid its invasion of Ukraine have had little to say about China’s posturing against Taiwan or its persecution of Uyghurs.                                                                                                                                                                                       , Apple on Tuesday announced it has halted sales and other services like Apple Pay in Russia, saying it was "deeply concerned about the Russian invasion of Ukraine" and stands with "all of the people who are suffering as a result of the violence."                                                                                                                     , APPLE HALTS SALES IN RUSSIA OVER UKRAINE INVASION                                                                                                                                                                                                                                                                                                                         , Apple also said that state-owned Russian media outlets like RT News and Sputnik News are no longer available for download from the App Store outside Russia.                                                                                                                                                                                                              , A woman cries outside houses damaged by a Russian airstrike, according to locals in Gorenka, outside the capital of Kyiv, Ukraine, Wednesday, March 2, 2022.  (AP Newsroom)                                                                                                                                                                                               , Apple has not made similar moves against China, which has been increasing its presence near Taiwan, an island that the communist country claims is part of its own territory despite the island’s claims of independence since 1949. The U.S. does not formally recognize Taiwan but maintains an unofficial relationship and is supportive of its democratic government. , China has been sending dozens of warplanes toward Taiwan’s air defense zone, coinciding with calls by Chinese President Xi Jinping for the island to be brought into China as part of a "peaceful reunification." Taiwan said it had to warn away nine Chinese aircraft that entered its defense zone Feb. 24, the same day that Russia invaded Ukraine.                  , Uyghur, Tibetan and Hong Kong communities rally outside the Chinese Embassy in London Oct. 1, 2021.  (Hasan Esen/Anadolu Agency via Getty Images / Getty Images)                                                                                                                                                                                                          , Despite Apple taking a stand against Russia and its state media, Chinese state media outlets such as Xinhua News Agency, China Central Television (CCTV) and People's Daily are still available for download from the App Store.                                                                                                                                          , Apple has also been silent about China’s human rights abuses against Muslims, particularly Uyghurs, in Xinjiang, which the U.S. has declared a genocide. In fact, the company removed a Quran app from its App Store in October following demands from the Chinese government.                                                                                            , Apple CEO Tim Cook gestures from an elevator as he arrives to speak during a weeks-long antitrust trial in federal court in Oakland, Calif., May 21, 2021. (Reuters)                                                                                                                                                                                                      , In March of last year, Apple complied with the Chinese government’s demands to remove H&amp;M stores from Apple Maps in the country, after the Swedish-based retailer spoke out against the Chinese Communist Party’s human rights abuses.                                                                                                                                    , "We're required to comply with local laws, and at times there are complex issues about which we may disagree with governments," Apple’s human rights policy states.                                                                                                                                                                                                       , CLICK HERE TO GET THE FOX NEWS APP                                                                                                                                                                                                                                                                                                                                        , Apple did not respond to Fox News Digital’s request for comment regarding the genocide of Uyghurs or whether it will take similar action against China that it did with Russia in the event of an invasion of Taiwan.                                                                                                                                                     , Similar requests for comment from multiple other companies that have moved to sever ties with Russia but not China, including Twitter, Google, Nike, Disney and Meta, the parent-company of Facebook and Instagram, went unreturned. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/03/stocks-making-the-biggest-moves-midday-best-buy-kroger-burlington-and-more.html </td>
   <td style="text-align:left;"> 2022-03-04 01:41:43 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Best Buy, Kroger, Burlington and more </td>
   <td style="text-align:left;"> , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                       , Best Buy — The retail stock jumped 9.2% after the company announced it was raising its quarterly dividend by 26%. The move comes despite Best Buy reporting adjusted earnings just matching the Refinitiv consensus estimate.                                                                                                     , Kroger — The grocery chain saw its shares jump 11.6% after it beat Wall Street expectations for earnings. The company reported fourth-quarter adjusted earnings of 91 cents per share on revenue of $33.05 billion. Analysts were looking for a profit of 74 cents per share on revenue of $32.86 billion, according to Refinitiv., BJ's Wholesale — Shares fell 13.2% after the wholesale retailer missed Wall Street expectations for quarterly revenue. BJ's posted $4.36 billion in revenue, compared with $4.4 billion expected by analysts, according to StreetAccount.                                                                                         , Big Lots — Shares dropped 1.2% following a poor earnings report. The company posted earnings of $1.75 per share versus the Refinitiv consensus estimate of $1.89 per share.                                                                                                                                                       , Burlington — The stock tumbled about 13% in midday trading, after missing consensus estimates in its holiday earnings report. Burlington reported quarterly adjusted earnings of $2.53 per share on revenue of $2.6 billion, falling short of Refinitiv consensus estimates of $3.25 per share on $2.78 billion in sales.         , Snowflake  —  Shares plummeted 15.4% after the software company reported earnings that indicated the slowest sales growth since at least 2019. Revenue for the fourth quarter came in above analysts' estimates and grew by 101% year over year. The company reported an adjusted loss of 43 cents per share.                     , Box Inc. — Shares gained 2.2% after the company reported better-than-expected results for the fourth quarter. The company earned 24 cents per share excluding items on $233 million in revenue. Analysts expected earnings of 23 cents per share on $229 million in revenue.                                                      , American Eagle Outfitters — The stock sunk 9.3% after the retailer reported quarterly results. American Eagle warned higher freight costs would weigh on earnings in the first half of 2022.                                                                                                                                      , Intel — Shares dipped 1.9% after Morgan Stanley downgraded the stock from equal-weight to underweight. "Downgrades of value stocks ... will let us focus on more actionable situations that offer relatively more attractive risk-reward going forward," Morgan Stanley's Ethan Puritz said.                                      , Southwest — Shares gained 1.5% after Evercore ISI upgraded the airline stock to outperform from in-line. "Greater relative financial strength + margin focused planning lead us to raise our rating on Southwest," the firm said.                                                                                                 , Citigroup — The bank's stock fell 3.3% after downgrades from two firms. Analysts were underwhelmed by Citi's medium-term target for return on tangible common equity, a key industry metric.                                                                                                                                      , — CNBC's Samantha Subin and Sarah Min contributed reporting.                                                                                                                                                                                                                                                                      , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biogen-lay-off-some-us/story.aspx?guid={65234EBB-3804-44A0-8D49-DC37CAB94055}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-04 01:17:36 </td>
   <td style="text-align:left;"> Biogen to lay off some U.S. employees - MarketWatch </td>
   <td style="text-align:left;"> Shares of Biogen Inc. 
        BIIB,
        +1.66%
       were up 1.0% in trading on Thursday after the company confirmed to media outlets that it is laying off some U.S. employees as part of an effort to secure $500 million in annual cost savings. Stat first reported the layoffs, saying the company plans to cut 1,000 jobs, citing anonymous sources. The company had 9,610 employees, as of Dec. 31, according to its most recent 10-K. A Biogen spokesperson confirmed the layoffs but said it is not providing additional details. "The $500 million cost-savings will not be entirely driven by headcount," the spokesperson said in an email. "As part of our headcount reductions, we've prioritized not fulfilling open positions...Some employees will be able to apply for the open positions we are filling." Biogen has been betting that its Aduhelm, its new Alzheimer's disease drug, would be a boon for the company; however, there have been questions about the approval process and the therapy's effectiveness. Aduhelm generated $3 million in 2021. Biogen's stock is down 21.3% over the past year, while the broader S&amp;P 500 
        SPX,
        -0.53%
       has gained 13.3%., Elon Musk invites the United Auto Workers union to hold a vote at the electric-vehicle company's plant in California, and 'Tesla will do nothing to stop them.'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/paraguay/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-04 01:17:16 </td>
   <td style="text-align:left;"> Paraguay Inflation Rate Hit Highest Since 2011 </td>
   <td style="text-align:left;"> The annual inflation rate in Paraguay accelerated to 9.3 percent in February of 2022 from 7.9 percent in the previous month and marking the highest inflation rate since May of 2011 when consumer prices jumped over 10 percent. Prices rose faster for food &amp; non-alcoholic beverages (15.7 percent vs 14.1 percent in January), transport (17.2 percent vs 14.0 percent) and housing &amp; utilities (4.2 percent vs 4.1 percent). On a monthly basis, consumer prices jumped 1.4 percent following a 1.5 percent gain in the prior period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60565784?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-04 01:16:40 </td>
   <td style="text-align:left;"> Ukraine energy giant tells world 'don't buy Russian oil' </td>
   <td style="text-align:left;"> This video can not be played                                                                                                                                                                                                                                                        , Ukraine's largest energy firm has told the BBC the West should stop buying gas and oil from Russia.                                                                                                                                                                                 , Yuriy Vitrenko, who runs Naftogaz, said Russian sanctions should be stronger and targeted directly at energy.                                                                                                                                                                       , To stop the war from spreading "it should make this very clear choice to get rid of this dependency on Russian gas and oil," he said.                                                                                                                                               , With economic sanctions "you have to believe as if you were at war with Russia," he added.                                                                                                                                                                                          , Russian oil and gas exports are exempted from Western sanctions for now. But on Thursday, Russia's second largest oil Lukoil called for an end to the conflict, stating that it was concerned by the "tragic events in Ukraine".                                                    , Mr Vitrenko said that everything should be done to stop the Putin regime  - which he described as Russia's "killing machine" - from receiving any revenues.                                                                                                                         , He accused the Russian President of using the revenue from oil "to kill innocent people".                                                                                                                                                                                           , Mr Vitrenko said Russia should be treated like a rogue nation similar to the way the West treats Iran and that the sanctions against Russia should reflect that.                                                                                                                    , The boss of the state-owned oil and gas company added that energy sanctions should be longer-lasting.                                                                                                                                                                               , "I would say that it's not a short-term measure, because I believe that the in the longer term, you can reach climate change targets without Russian gas, so it's just a matter of choice."                                                                                         , He added that he thought the oil and gas pipelines have been a deterrent from attack and he had seen evidence that Russian special forces had marked them out.                                                                                                                      , Mr Vitrenko welcomed Germany's move to shut down the Nord Stream 2 gas project, which was designed to double the amount of Russian gas that flowed directly into Germany.                                                                                                           , Even though he thought the move came too late he said it was "better late than never".                                                                                                                                                                                              , It was a shock "not just to us, but also to the Germans" that Putin took the actions he did, Mr Vitrenko said.                                                                                                                                                                      , He said it a was "pleasant surprise that finally Europe, and Germany in particular, are serious about making sure that Putin stops getting a revenue stream".                                                                                                                       , Mr Vitrenko's voice adds to a growing chorus that is pressuring policymakers in the US and Europe to sanction Russian oil and gas.                                                                                                                                                  , On Thursday, the International Energy Agency (IEA) presented a plan for the European Union to cut Russian imports by a third within a year and urged the European Union to sign no new supply contracts with Russia's Gazprom.                                                      , "Nobody is under any illusions anymore. Russia's use of its natural gas resources as an economic and political weapon show Europe needs to act quickly to be ready to face considerable uncertainty over Russian gas supplies next winter," said IEA executive director Fatih Birol., Meanwhile in Washington, top Democrat Nancy Pelosi said she supported a ban on Russian energy, while US Senator John Kennedy, a Republican, said Western sanctions have left a big hole by leaving energy transactions exempt.                                                      , "How are we going to throw Russia out of the international community and global markets if we don't attack their oil?" he said at a hearing with the head of America's central bank.                                                                                                , Sanctions against Russia have already disrupted energy markets, including by pushing Western companies, including ExxonMobil, Shell and BP, to take steps to quit their investments in the country.                                                                                 , The obsession continues with the final series of Killing Eve...                                                                                                                                                                                                                     , Incredible technology takes you on an emotional journey deep inside!                                                                                                                                                                                                                , The very best from around the world including Beck and The Bridge                                                                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 01:12:00 </td>
   <td style="text-align:left;"> Spanish Stocks Lead Losses in Europe, IBEX 35 Hits 13-Month Low </td>
   <td style="text-align:left;"> Spain's IBEX 35 was the worst performer among major bourses in Europe on Thursday by falling 3.7% to just a tad above the 8,000 level, the lowest since January last year amid worries over the war in Ukraine, inflation and monetary policy changes. Despite the highly uncertain economic outlook to the European region due to the current conflict in Ukraine, expectations of tighter policy by the ECB strengthened after fresh figures showed consumer prices in the bloc accelerated more than expected to a record high in February. Ence Energia y Celulosa, Siemens Gamesa, Melia and Grifols were down between 7-10% to lead losses and heavyweight stocks such as Inditex and Iberdrola declined more than 5%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/03/for-warren-buffett-apple-is-his-new-cola-cola-as-the-investing-icon-reaps-100-billion-in-six-years.html </td>
   <td style="text-align:left;"> 2022-03-04 01:11:17 </td>
   <td style="text-align:left;"> For Warren Buffett, Apple is his new Cola-Cola as the investing icon reaps $100 billion in six years </td>
   <td style="text-align:left;"> , Warren Buffett's recent success from his massive Apple bet is spurring comparisons with the legend's greatest investment of all time — Coca-Cola.                                                                                                                                                                                                                                                              , Berkshire Hathaway began buying Apple's stock in 2016 and amassed a 5% ownership of the iPhone maker by mid-2018 with a cost of $36 billion. As the tech giant's share price skyrocketed, the value of Buffett's bet has ballooned to more than $160 billion, bringing his return well over $100 billion on paper in just six years.                                                                           , The highly lucrative investment reminded some Buffett watchers of Coca-Cola, the Oracle of Omaha's oldest and longest stock position. The consumer juggernaut's stock has soared over 2,000% since Buffett started buying in 1988, and it's still Berkshire's fourth largest equity position with 400 million shares.                                                                                          , "Buffett is having his Coca-Cola moment on Apple," said Bill Smead, chief investment officer at Smead Capital Management and a Berkshire shareholder. "They both went way up the first five to seven years he's owned them."                                                                                                                                                                                   , Investing in high-flyers such as Apple seemingly defies Buffett's well-known value investing principles, but the out-of-character move turned out to be his best investment over the last decade. Apple's stake also played a crucial role in helping Berkshire weather the coronavirus pandemic as other pillars of its business, including insurance and energy, took a huge hit.                            , The 91-year-old investor has become such a big fan of Apple that he now considers the tech giant as one of the "four giants" driving his conglomerate of mostly old-economy businesses he's assembled over the last five decades.                                                                                                                                                                              , Apple "has been a home run for Berkshire, no doubt," said James Shanahan, Berkshire analyst at Edward Jones. "Buffett acquired most of the position at an average cost of about one fourth of the current market price."                                                                                                                                                                                       , Apple's stock repurchase strategy also allows the conglomerate's ownership to increase with each dollar of the iPhone maker's earnings. Berkshire has trimmed the position, but its ownership still crept up from 5.27% at the end of 2020 to 5.43% at the end of last year.                                                                                                                                   , The conglomerate has also enjoyed regular dividends from the tech giant over the years, averaging about $775 million annually.                                                                                                                                                                                                                                                                                 , If one were to take cues from what Buffett said when he first purchased Coca-Cola shares, it wouldn't be a far-off guess that the investor is in Apple for the long haul.                                                                                                                                                                                                                                      , "In 1988 we made major purchases of Federal Home Loan Mortgage and Coca Cola. We expect to hold these securities for a long time," Buffett wrote in his 1988 annual letter. "In fact, when we own portions of outstanding businesses with outstanding managements, out favorite holding period is forever. We are just the opposite of those who hurry to sell and book profits when companies perform well...", Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/pelosi-says-she-supports-senate/story.aspx?guid={4318FCA6-F03A-4082-B734-F774D90F9A7B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-04 01:04:55 </td>
   <td style="text-align:left;"> Pelosi says she supports Senate bill that would ban imports of Russian oil - MarketWatch </td>
   <td style="text-align:left;"> House Speaker Nancy Pelosi on Thursday threw her support behind a Senate bill that aims to ban the import of Russian oil 
        CL00,
        +3.59%
       into the U.S., as part of the Western response to Russia's invasion of Ukraine. "I'm all for that. Ban it," the California Democrat told reporters during her weekly press briefing, when asked about the measure, which is backed by Republican Sen. Lisa Murkowski of Alaska and Democratic Sen. Joe Manchin of West Virginia., Why Russia can't access its stockpile of money, and why freezing the ruble will also give China second thoughts about its own territorial and economic ambitions                                                                                                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 01:01:00 </td>
   <td style="text-align:left;"> FTSE 100 Ends Session 2% Lower </td>
   <td style="text-align:left;"> The FTSE 100 tumbled more than 2% to finish around 7,230 points Thursday, driven by sharp declines among Russian-linked companies. Polymetal International PLC fell almost 40%, the most on the FTSE 100, while the largest lender Sberbank and energy giant Gazprom also ended deep in negative territory. Major Ukrainian cities remain under heavy shelling, while Russian forces are surrounding Kyiv. Putting a floor under prices was an almost 10% jump in London Stock Exchange Group shares after it increased dividends as the 2022 outlook looked upbeat and said the integration of Refinitiv was on track. Meanwhile, UK services and composite PMI readings rose less than flash estimates had pointed out in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/03/russia-oil-disruption-will-lead-to-significantly-higher-prices-says-exxon-ceo.html </td>
   <td style="text-align:left;"> 2022-03-04 00:56:22 </td>
   <td style="text-align:left;"> Russia oil disruption would lead to 'significantly higher prices,' says Exxon CEO </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                  , U.S. oil surged to the highest level since 2008 on Thursday, and Exxon CEO Darren Woods said prices could be heading much higher.                                                                                                                                                                                                                                                , "If there is a significant supply disruption with respect to Russian crude ... that will be very difficult for the market to make up and therefore that will lead to, I think, significantly higher prices," he told CNBC's "Squawk on the Street."                                                                                                                              , Oil prices surged above $100 per barrel last week as Russia invaded Ukraine, prompting supply fears in what was an already very tight market ahead of the invasion. Prices have kept climbing as the fighting intensifies.                                                                                                                                                       , West Texas Intermediate crude futures, the U.S. oil benchmark, hit $116.57 per barrel on Thursday, the highest level since September 2008. International benchmark Brent crude rose to $119.84, a price last seen in May 2012.                                                                                                                                                   , So far, the sanctions imposed by the U.S. and its allies have not targeted Russia's energy complex directly, but the ripple effects are being felt. International buyers are shunning Russian oil to avoid potentially violating the financial sanctions.                                                                                                                        , Additionally, companies, including Exxon, are pulling Russian operations.                                                                                                                                                                                                                                                                                                        , The oil giant announced Tuesday evening that it was halting operations in the country and would make no further investments. The announcement came after BP and Shell said they would divest from their assets in Russia.                                                                                                                                                        , "Our business engages significantly with the government, the host governments where we operate. We felt like the decisions that were being made by the Russian government with respect to its incursion in Ukraine were inconsistent with our philosophies and how we run our business," Woods told CNBC.                                                                        , He said Russia's invasion was a "tipping point" in terms of working with the country, but left open the possibility of re-entering it at a later date.                                                                                                                                                                                                                           , "We'll keep an open mind," he said, before adding that "things would have to change pretty significantly, frankly."                                                                                                                                                                                                                                                              , Prior to Russia's invasion, oil prices were at multiyear highs. Demand has bounced back since the depths of the pandemic, and producers have kept supply in check. OPEC and its allies, which includes Russia, met Wednesday and said they would keep output steady. In April, they will raise production by 400,000 barrels per day, sticking with a previously agreed schedule., Producers in the U.S. also have kept supply in check. As energy companies emerge from the pandemic, shareholders are demanding stricter capital discipline with an emphasis on capital return in the form of dividends and buybacks. So while in prior years prices above $100 would have led to an uptick in drilling, it hasn't happened this time around.                     , Still, Woods said Exxon is "maximizing production" and expanding its operations in the Permian Basin.                                                                                                                                                                                                                                                                            , He added that the market signals are working, which should ultimately bring more production online across the industry.                                                                                                                                                                                                                                                          , "That price response that we're seeing is the outcome of a tight supply-demand balance. Marginal sources of supply ...come into the marketplace and so I think you'll see that price draw more resources," Woods said.                                                                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 00:48:00 </td>
   <td style="text-align:left;"> Italian Stocks Close at 7-Month Low </td>
   <td style="text-align:left;"> The FTSE MIB Index fell 2.4% to close at 23,959 on Thursday, declining to a seven-month low as investors continued to follow the Russian assaults on major Ukrainian cities amid projections of tighter policy by major central banks. Higher inflation readings and lower unemployment figures across the currency block, including domestically, led to expectations of lower monetary accommodation by the ECB, while Fed Chair Powell signaled that the Federal Reserve will raise the benchmark rate by 25bps this month. On the corporate front, energy companies and utility providers extended yesterday’s sharp decline, while banks also traded lower. Telecom Italia (-14%) led the losses after reporting a record EUR 8.7 billion loss in 2021 and rejected KKR’s acquisition bid of EUR 10.8 billion, as it prepares to spin-off its its landline network assets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/03/whats-stopping-black-owned-banks-from-thriving.html </td>
   <td style="text-align:left;"> 2022-03-04 00:47:23 </td>
   <td style="text-align:left;"> Less than 1% of all FDIC-insured banks are Black-owned, according to the FDIC </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                   , Big banks and corporations like Yelp, Netflix, and Microsoft have announced major investments in Black-owned banks.                                                                                                                                                                                                                               , Yet Black banks are far from thriving. Americans who identify solely as Black or African American make up 13.4% of the U.S. population today, but less than 1% of all FDIC-insured banks are considered Black-owned.                                                                                                                              , The number of Black-owned banks has dwindled immensely over the years. Between 1888 and 1934, there were 134 Black-owned banks to help the Black community. Today, there are only 20 Black-owned banks that qualify as Minority Depository Institutions, according to the Federal Deposit Insurance Corporation.                                  , "I think part of it has to do with the broader trend in the banking community," said Michael Neal, senior research associate at the Urban Institute. "We're seeing the number of banks overall declining and assets being concentrated, particularly in your larger global and more complex financial institutions."                              , Black-owned banks lack the assets needed to compete against major players. For example, one of the biggest Black-owned banks in the U.S., OneUnited Bank, manages over $650 million in assets. By comparison, JPMorgan and Bank of America each manage assets worth well over $2 trillion dollars.                                                , "Whatever the struggles are of the community, the banks have the same struggle because they're enmeshed in that community," said Mehrsa Baradaran, professor of Law at the University of California Irvine. "They cannot change it unless the community itself has more wealth and has more access, and we have less discrimination as a society.", Watch the video to find out more about why Black-owned banks are so important to achieving financial equality and what's stopping them from thriving.                                                                                                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cnq:cn </td>
   <td style="text-align:left;"> 2022-03-04 00:46:10 </td>
   <td style="text-align:left;"> Canadian Natural Resources earnings above expectations at 2.21 CAD </td>
   <td style="text-align:left;"> Canadian Natural Resources (CNQ) released earnings per share at 2.21 CAD, compared to market expectations of 2.05 CAD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 00:46:00 </td>
   <td style="text-align:left;"> French Shares Retreat on Thursday </td>
   <td style="text-align:left;"> The CAC 40 Index closed 1.8% lower at 6,378 on Thursday, as investors continued to monitor the ongoing Russian attacks in Ukraine, while digesting prospects of scaled back monetary accommodation by the ECB and Fed Chair Powell’s strong indication of an interest rate hike this month. Utility shares led the losses, driven by Engie (-6.1%) as the firm said it was exposed to EUR 987 million in the Nord Stream 2 pipeline project. The French utility is down over 25% since Monday, when the Swiss-based company Nord Stream 2 AG responsible for the pipeline project stated it is considering filing for insolvency. Renault (-5.9%) also booked losses on its exposure to Russia. At the same time, TotalEnergies closed 3.5% lower amid a volatile session for oil price. Meanwhile, Societe Generale (-0.8%) closed lower, having lost roughly 30% on the past month, as the bank claimed to be able to absorb the consequences of an extreme scenario on its ownership of banking assets in Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-03-04 00:40:00 </td>
   <td style="text-align:left;"> Dollar Rally Gains Momentum </td>
   <td style="text-align:left;"> The dollar index gained further ground Thursday, breaking above the 97.93 level for the first time since June of 2020. Market moves came as investors reacted to an expected looming policy tightening cycle. During a Senate hearing on Thursday, Fed Chair Powell once again pointed to a 25 basis point rate hike in March but opened the door for a more aggressive move if inflation does not abate as anticipated. The most pronounced buying activity was against the euro, with inflation in Europe surging to a record high of 5.8% in February, putting the ECB policymakers in a tough spot next week when they meet to set policy amid the fog of war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/ukraine-russia-congress-republicans-democrats-oil-russia-biden </td>
   <td style="text-align:left;"> 2022-03-04 00:36:00 </td>
   <td style="text-align:left;"> Bipartisan pressure to ban Russian energy imports grows on Biden </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines.                                                                                                                                                                                                                                                                                                                                                                                                              , As President Biden and Europeans avoid removing Russian banks that deal in oil from the international SWIFT banking system, Republicans and Democrats in Congress are calling for an even more drastic move to ban Russian oil.                                                                                                                                                                                                                              , Republicans have been making similar comments for weeks. But some Democrats are now urging the administration to consider that course of action too, as Russian President Vladimir Putin's brutal assault on Ukraine intensifies.                                                                                                                                                                                                                            , Sen. Joe Manchin, D-W.Va., Thursday said he has "many" co-sponsors from both parties on a bill he's introducing with Sen. Lisa Murkowski, R-Alaska, to ban Russian oil imports. He also upbraided administration officials for blocking increases in domestic energy production, including on natural gas in his state.                                                                                                                                      , PUTIN HAS A HUGE APPETITE FOR RISK: REP. FITZPATRICK                                                                                                                                                                                                                                                                                                                                                                                                         , "This bill will prohibit importation of Russian crude oil, petroleum, petroleum products, LNG and coal during this emergency," Manchin said. "I stood by the new administration when they called for a pause on the federal leasing programs last year. But the time for pausing has come and gone and despite a court ruling saying the same the administration continues to drag its feet when it comes to leasing on federal lands and in federal waters.", Sen. Joe Manchin defends the Senate's 60-vote filibuster on Jan. 19, 2022. (Senate)                                                                                                                                                                                                                                                                                                                                                                          , Manchin added: "Given Russia's invasion of Ukraine… this is in many ways an energy war and we need to treat it with that kind of gravity. We can't bring a knife to a gunfight. I tell you in my lifetime the only other time I've been more concerned … is as a teenager during the Cuban Missile Crisis."                                                                                                                                                  , The Biden administration has resisted calls both to increase domestic energy production and to block Russian oil. White House deputy press secretary Karine Jean-Pierre told reporters Wednesday, "Given high oil and gas prices, cutting – cutting off Russian oil/gas will drive prices up to Putin’s benefit."                                                                                                                                            , UKRAINE NATIVE PLEADS FOR US, WEST TO GO AFTER PUTIN'S OIL, LUMBER TO STOP ‘INSANITY’                                                                                                                                                                                                                                                                                                                                                                        , President Biden said Wednesday that "all options are on the table" when it comes to a Russian oil ban.                                                                                                                                                                                                                                                                                                                                                       , President Biden waves as he and first lady Jill Biden board Air Force One, Wednesday, March 2, 2022, at Andrews Air Force Base, Maryland. (AP Photo/Patrick Semansky / AP Newsroom)                                                                                                                                                                                                                                                                          , Some progressive Democrats are even open to the idea. Rep. Ro Khanna, D-Calif., told Fox News in a phone interview Thursday that the president should consider banning Russian oil.                                                                                                                                                                                                                                                                          , "I'm open to the SWIFT sanctions, I think they're necessary to de-SWIFT the Russian banks. And I'm open to banning Russian oil. I think the president really needs to look at that as a serious consideration," Khanna said.                                                                                                                                                                                                                                 , "The lesson from this should be what John McCain was trying to teach us a decade ago, which is that Russia is an oil and gas state," Khanna said. "That Europe and America should have never been as dependent on Russian oil and gas and it should make an investment in renewable energy, in nuclear, in batteries a national security imperative."                                                                                                        , Sen. Ed Markey, D-Mass., this week released his own bill to ban Russian oil imports.                                                                                                                                                                                                                                                                                                                                                                         , Sen. Ed Markey holds a news conference outside the Supreme Court to announce legislation to expand the number of seats on the high court, on Capitol Hill on April 15, 2021. (AP Photo/J. Scott Applewhite / AP Newsroom)                                                                                                                                                                                                                                    , "American fossil fuel companies helped fuel Putin’s despicable war on Ukraine to the tune of billions, propping up the oil-garchs and cronies that keep him in power," Markey said of the legislation. "There is no separating Russian oil from the corruption and human rights abuses of the Putin regime. We cannot criticize Europe for its reliance on Russian energy, as we pour dirty oil money into Russia."                                          , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                  , A staunch environmentalist, Markey has a radically different solution to getting the U.S. off of Russian oil than Manchin and his fellow moderates. Rather that increasing domestic production, the Massachusetts senator wants to increase American use of other energy sources.                                                                                                                                                                            , "If we just deploy 15 million all-electric vehicles, we back out all the oil from Russia," Markey said on the Senate floor this week. He was objecting to a move from Sen. Tom Cotton, R-Ark., to encourage domestic energy production.                                                                                                                                                                                                                      , "The next 15 million backs out all of the Saudi oil. The next 15 million backs out all the oil from the Middle East," Markey said. "You want to do something? You want to terrify them? You want to destroy their business model in Russia or the Middle East? That's what you should be doing."                                                                                                                                                             , Even without a U.S. ban, U.S. companies and traders are "not touching Russian barrels," one New York trader told Reuters. U.S. companies imported no crude oil from Russia last week, according to preliminary data released Wednesday by the U.S. Energy Information Administration.                                                                                                                                                                        , Fox News' Kristina Biddle contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/russia-ukraine-war-south-korean-vaccine-manufacturer-complications </td>
   <td style="text-align:left;"> 2022-03-04 00:33:49 </td>
   <td style="text-align:left;"> Russia-Ukraine war: South Korean vaccine manufacturer braces for complications </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines.                                                                                                                                                                                                                                                                                                                                                 , A South Korean pharmaceutical company manufacturing Russia’s COVID-19 vaccine said it is bracing for business complications following the West's sanctions against Russia over the invasion of Ukraine.                                                                                                                                                                                         , Kim Gi-young, an official from Seoul-based biotech firm GL Rapha, said the sanctions won’t directly obstruct its production of the shots.                                                                                                                                                                                                                                                       , MODERNA CEO ON RUSSIA INVADING UKRAINE, NEW COVID VARIANT                                                                                                                                                                                                                                                                                                                                       , "Right now, we are watching how the situation develops," Kim said.                                                                                                                                                                                                                                                                                                                              , The company is concerned about problems on the financial side as South Korea joins the U.S. and other European countries to cut off key Russian banks from global payment systems.                                                                                                                                                                                                              , Thus far, GL Rapha has produced 5 million shots of the single-dose Sputnik Light vaccine.                                                                                                                                                                                                                                                                                                       , A woman cries outside houses damaged by a Russian airstrike, according to locals, in Gorenka, outside the capital Kyiv, Ukraine, Wednesday, March 2, 2022.  (AP Photo/Vadim Ghirda)                                                                                                                                                                                                             , Kim said none of those have been used as Russia continues to push back rollout plans.                                                                                                                                                                                                                                                                                                           , The company also has an agreement with the Russian Direct Investment Fund (RDIF) – a wealth fund run by a close ally of President Vladimir Putin that globally markets the Sputnik vaccines – to produce 150 million shots of the two-dose Sputnik V and is participating in a consortium of South Korean companies that has been contracted to produce another 500 million doses of Sputnik V. , Those shots have yet to be produced and recently expanded U.S. sanctions include targeted measures against the fund.                                                                                                                                                                                                                                                                            , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                         , RDIF has reportedly criticized the sanctions and said the measures would slow its promotion of Sputnik V.                                                                                                                                                                                                                                                                                       , On Saturday, the U.S. and European nations agreed to impose the most potentially crippling financial penalties yet, aiming to send the ruble into "free fall" and promote soaring inflation in the Russian economy.                                                                                                                                                                             , Former Ambassador to Cyprus Richard Boucher provides insight into Russia’s invasion of Ukraine.                                                                                                                                                                                                                                                                                                 , It includes cutting key banks out of the SWIFT financial messaging system, which moves countless billions of dollars around more than 11,000 banks and other financial institutions around the globe each day.                                                                                                                                                                                  , "Putin embarked on a path aiming to destroy Ukraine, but what he is also doing, in fact, is destroying the future of his own country," European Union (EU) Commission President Ursula von der Leyen said in a statement.                                                                                                                                                                       , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                     , Dozens of foreign and international companies have pulled their business out of Russia.                                                                                                                                                                                                                                                                                                         , World Health Organization (WHO) officials warned Wednesday that the ongoing invasion of Russian forces in Ukraine will allow COVID-19 to spread easily.                                                                                                                                                                                                                                         , The Associated Press contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 00:32:00 </td>
   <td style="text-align:left;"> South African Stocks Drop </td>
   <td style="text-align:left;"> The JSE FTSE All Share index reversed early gains and closed marginally lower at 77,391, as sharp losses in shares of gold and oil producers more than offset gains in those of iron ore producers. Meanwhile, investors kept an eye on developments in Ukraine and mounting sanctions against Russia, while welcoming US Federal Reserve chair Jerome Powell's less hawkish stance. On the domestic data front, a Markit PMI survey showed South Africa's factory activity growth was steady at a three-month high in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/03/tech-private-equity-investor-orlando-bravo-says-the-mantra-of-growth-at-all-costs-is-over-.html </td>
   <td style="text-align:left;"> 2022-03-04 00:24:45 </td>
   <td style="text-align:left;"> Tech private equity investor Orlando Bravo says the mantra of 'growth at all costs' is over </td>
   <td style="text-align:left;"> , (Click here to subscribe to the Delivering Alpha newsletter.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Software has been one of the worst-performing sectors this year amid a rising rate environment and geopolitical tensions overseas.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , This comes as no shock to Orlando Bravo who helms tech-focused private equity firm Thoma Bravo. He says the mantra of 'growth at all costs' is over and that investors are slowly shifting their focus from momentum to fundamentals and profitability.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Bravo sat down with the Delivering Alpha newsletter to discuss what he thinks are structural problems in the software industry, the revaluation in tech, and the growing cybersecurity risk emanating from Europe.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,  (The below has been edited for length and clarity. See above for full video.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Leslie Picker: There has been a massive shift in 2022, there's just this macro change afoot. How does that impact what you do and what do you make of the recent revaluation in the [tech] sector?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Orlando Bravo: It was just a long time coming. I mean, we've been on a decade of tailwinds not only in the software industry, but in multiples. And what happened recently is that multiples of these growth stocks went from 20x to 10x. They got cut in half. Now why is that? Our theme and our thesis on it in talking to the big investors, sovereign wealth funds, big state pension plans, the original sources of capital, is that people are getting tired of being money-losing operations. They're finally digging into the business models, looking at when profitability is going to come and discounting assets that have high growth, but no near-term prospects for profitability. So that correction is here and it's happened and it's in effect today. Now how does that affect our business? That is phenomenal on the buy side for our business because we are focused on buying the entire company, not in buying pieces of paper where you're dependent on what others think. So it gives us an opportunity to do the one thing that we do really well and focus on which is to take these high-growth, innovative companies and put together an operating framework that allows them to be profitable as well and create profitable growth engines.                                                                                                                                                                         , Picker: Would you say at this point in time that the sell-off is really priced in or do you think that valuations still have further to go before they're at their intrinsic value, in your estimation?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Bravo: As a business owner, and as a participant in the private equity industry, it's looking extremely attractive for groups like us, because once again, you can partner with companies and change their operational makeup by inspiring leadership. And these assets can produce big cash flow, not 20 EBIT/EBITDA margins, but 50% at growth and scale. So if you can price in your improvements, it looks extremely attractive. Now for the public markets, the problem is that once again, you don't have control. So what is the bottom price on a revenue multiple when you're unprofitable, especially when you miss your numbers? And now even more so if companies don't beat and raise enough to surprise the street positively and they don't have profitability to hold up your valuation, they are usually getting big negative surprises in terms of their share price.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Picker: What's that tell you in terms of exits, though? Obviously on the buy side you mentioned tremendous opportunity. But what about the portfolio companies? You've been a massive dealmaker over the past few years, one of the most prolific dealmakers over the past few years, in all of private equity, not just tech. But what does that mean for the portfolio companies that you're holding right now? Do you kind of wait a while for things to settle down before you look to do an IPO or to sell it? Or are you still seeing opportunities out there?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Bravo: What we do is we buy multiples of revenue, but we sell them on multiples of EBITDA. So we're a fundamental seller as well and that's how we model our investment cases in our companies. So if you have high cash flow, and you don't get the right multiple on that cash flow, you can wait because you're going to keep adding equity value, and you're going to keep building a balance sheet that you can use for acquisitions. We are really not dependent on the market that we call 'buy high and sell higher.' We're not in the momentum business, we're in the fundamental business. What we're seeing in private equity is private equity has not slowed down yet, in terms of buying companies on an EBITDA basis. And strategic buyers are sitting on their cash. And when they combine the number one player in a given sector in software, and that company does not have to be fixed, it does not have to be turned around, it's highly profitable and can operate even as an independent business unit, that is still attractive to these corporate buyers.                                                                                                                                                                                                                                                                                                                                                                  , The IPO is certainly a problem. And if you look at our industry, one of the challenges of private equity that the community doesn't really talk about too much, is remember private equity needs to buy these public companies at a premium, call it 30% premium, and then you're taking them public at a discount to the comps, call it a 20% discount. So the value that you have to create in between has to be so large for you to make your investment case work if you're planning on taking it public later.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Picker: So if I'm understanding this correctly, then you are very hyper focused once you acquire a company on ensuring that it becomes profitable before you exit or at least close to that level of profitability before you do seek to exit. How do you do that, especially in this current environment with inflation and all sorts of labor issues in terms of acquiring and maintaining talent? It seems like it would be a tough job right now.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Bravo: I really appreciate that. We feel like we earn it and when you own a whole company, which is what we do, you own all the problems. You can't outsource the problems. People change their minds. People want to change jobs. You need to inspire your leadership. Customers change their point of view. Their product problems, their sales problems, distribution problems. We live those every single day. The way we do it, we do it in a unique way in private equity, in software, which is we make big positive changes in the companies we buy but we look to do that only with the existing management team. And that's the secret sauce of our firm…we have a way of talking to leaders and inspiring them to continue to do the great innovative things that they're doing that are going very well and not interrupt the growth curves of these companies, while implementing an approach where of discipline and operational cadence that allows the company or those businesses to produce more margin while they grow faster.                                                                                                                                                                                                                                                                                                                                                                                                   , We are different than most of the world. We do not subscribe to the view that in order to grow, you need to lose money or invest negatively in your P&amp;L. These companies, once you have over $100 billion of ARR - annual recurring revenue - the more profitable you are, the faster you should grow, because you have more money built in from your operation to invest in sales, which is tactical and more money to invest in R&amp;D, which is more long-term and strategic. And we really work with our leaders to put this motion in place and understand that and embrace it so that they can build these long term profitable engines. And what that does, is it de-risks innovation. That way that companies can continue to innovate for a long period of time without having big disruptions to their business models. Or if capital dries up, they're not dependent on outside capital to continue to grow, grow their business.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Picker: So the mantra 'growth at all costs,' do you think that's not the way the world is right now?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Bravo: That is over. 'Growth at all costs' has ended and whoever is still investing and operating in this way, is going to be surprised. It's changed and it finally has come after a long period of time of just investing behind a total available market and around momentum growth. People are now finally looking at the business economics. And think about it, it's so basic. How could you create a company, and a large company over time, where the societal resources that you use for production way exceed the output? It just, it cannot last and that's a bit of a structural problem the software industry has now and groups like us look to fix that.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Picker: How does [the geopolitical situation in Russia and Ukraine] affect the technology sector? Are you seeing a value that technology can provide as we assess what's going on overseas?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Bravo: The world has become digital and that is now, talking about technology, that is an irreversible trend. And we are at the beginning of that trend. In the last two years when we all had to work from home, when companies needed to do business differently, communicate with their customers differently, transact differently, people began - business leaders in society as a whole began -  to use technology that has existed for a long time. But their minds were opened to actually absorb that technology and use it differently. And that created another step function in the world of quote-unquote going digital. Now you see industrial companies trying to go digital, either acquiring and or changing their businesses. Financial institutions, some of them call themselves a technology company with a financial services business model, and that is the trend. Therefore the world is a lot more exposed to cybersecurity risks. And now we are in - yesterday, some news came out starting to talk about it - that we're also in a technology war. And the importance of cybersecurity as the world goes digital, and especially now, given the geopolitical environment and in essence of war, the importance of cybersecurity is huge.                                                                                                                                                                               , Picker: You own a plethora of cybersecurity companies. You do have a good sense of the pulse of the technology as well as the premium that investors are paying here for these types of assets, especially as their value-add becomes ever more present. What would you say about just the ability to defend our organizations here in the U.S. and in the West against foreign actors that may be seeking to harm, whether it's banks or other entities here, our defense organizations here in the U.S.?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Bravo: Thoma Bravo has been in cybersecurity since 2008. We were the first private equity group from a control standpoint to develop a large portfolio in cybersecurity, and today we have $6 billion in revenue. If you put all of our cybersecurity companies together, which make us in total, the largest cybersecurity company in the world. One of the things we saw is three months before the invasion, a huge spike in DDoS attacks - denials of service - mainly coming from Russia. And of course now you see a 10x increase in DDoS attacks emanating from Russia. These attacks are at scale, they are complicated, and even the best cybersecurity technology experts in the U.S. don't quite know how they pull them off at this scale. So it is so important now that corporations all over the world, and especially in the United States, have a strong, what we call, cybersecurity posture, which is difficult to have because it requires a big investment. It requires pulling a number of products together and it's also really important that these corporations of any size - you can be a large company or you can be a very small company - buy the best product in each cybersecurity area. Do not buy free product. Free product is worth what it is, it's free, and that is what it's meant to be. You do not want to be in a bad cybersecurity posture when you did not invest in your infrastructure appropriately., Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/dccc-gas-costs-tweet-worse </td>
   <td style="text-align:left;"> 2022-03-04 00:24:01 </td>
   <td style="text-align:left;"> FLASHBACK: DCCC's panned gas prices tweet looking worse as prices skyrocket due to Russia-Ukraine war </td>
   <td style="text-align:left;"> The Schork Group principal Stephen Schork argues the U.S. and Europe will ikely face rising oil and gas costs due to their energy policies amid the Russia-Ukraine conflict.                                                                                                                                                                                 , The Democratic Congressional Campaign Committee's (DCCC) panned tweet from three months ago, which used a misleading graph showing gas prices going down 2 cents per gallon and credited President Biden, is looking worse as gas prices continue to skyrocket during the Russia-Ukraine war.                                                                , Twitter users criticized the December tweet for its misleading Y axis, which had no start date and showed gas prices only dropping, ignoring the previous spike in prices during Biden's presidency.                                                                                                                                                         , WASHINGTON POST MOCKS DCCC’S TWEET ON GAS PRICES: ‘MIGHT BE THE WORST DEFENSE OF THE BIDEN ADMINISTRATION YET’                                                                                                                                                                                                                                               , "Thanks, [President Biden]," the DCCC’s official account posted along with a graph that had no start date showing gas prices going down by two cents from Nov. 22 to Nov. 29.                                                                                                                                                                                , The DCCC post came after Biden opened the U.S. Strategic Petroleum Reserve — government-stockpiled fuel reserved for wartime and national emergencies — to offset the then-spiking cost of gas.                                                                                                                                                              , The chart was so misleading that even The Washington Post mocked the tweet as possibly "the worst defense of the Biden administration yet."                                                                                                                                                                                                                  , With White House chief of staff Ron Klain and other members of the Biden administration amplifying the tweet at the time, today's gas prices pour cold water on the narrative that the White House was pushing.                                                                                                                                              , Rep. August Pfluger, R-Texas, during a hearing March 10, 2021 on Capitol Hill.  (Ting Shen-Pool/Getty Images / Getty Images)                                                                                                                                                                                                                                 , Republicans have long pushed for U.S. energy independence and Russia's invasion of Ukraine has only amplified those calls.                                                                                                                                                                                                                                   , Several members have introduced legislation taking aim at Russia’s primary market and Achilles’ heel: the energy sector.                                                                                                                                                                                                                                     , Rep. August Pfluger, R-Texas, introduced the Republican Study Committee-backed Midland Over Moscow Act last month that would require Biden to create a plan to beef up U.S. energy security while pushing back on Russia, reapply sanctions onto the Russian Nord Stream II pipeline, and make it easier for American companies to export liquid natural gas., CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                      , "If President Biden is serious about buying American products—he should start with oil &amp; gas from the Permian Basin," Pfluger told Fox News Digital. "The U.S. and her allies should not be reliant on our enemies for energy."                                                                                                                              , President Joe Biden on Saturday urged major G20 energy producing countries with spare capacity to boost production to ensure a stronger global economic recovery as part of a broad effort to pressure OPEC and its partners to increase oil supply.  (AP Photo/Evan Vucci / AP Newsroom)                                                                    , "President Biden must vocally commit to unleashing American energy producers to secure our country and our allies. We must put Midland over Moscow."                                                                                                                                                                                                         , Gas prices shot up overnight across the U.S., with the national average rising to $3.728 from $3.656 the day before — a 2% increase.                                                                                                                                                                                                                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                  , Additionally, on average gas today costs over 30 cents more than February’s monthly average of $3.413.                                                                                                                                                                                                                                                       , The cost of gas is likely to keep increasing as the war in Ukraine rages on and U.S. energy companies continue to cut ties with Russia.                                                                                                                                                                                                                      , Fox News Digital’s Yael Halon contributed reporting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 00:13:00 </td>
   <td style="text-align:left;"> European Shares Fall Sharply, DAX Hits 13-Month Low </td>
   <td style="text-align:left;"> European equity markets fell sharply on Thursday, with Germany’s DAX down more than 2% to a 13-month low as the war in Ukraine enters its second week and investors worry over how the current surge in commodity prices will impact inflation and therefore monetary policy decisions. Across sectors, travel and retail stocks were the worst performers while mining shares gained. Also, the energy sector tumbled almost 4%, as oil whipsawed. Meanwhile, banks declined about 1.5%, extending losses from earlier in the week amid concerns about their exposure to Russia, as well as receding expectations of rate hikes from the ECB. On the data front, services PMIs for the Euro Area, Germany and France were revised lower while fresh figures for Italy and Spain topped forecasts. Elsewhere, growth in the US services sector slowed unexpectedly in February to a one-year low. On the earnings front, Lufthansa said it could not provide a detailed outlook for 2022 due to the war in Ukraine and the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-04 00:13:00 </td>
   <td style="text-align:left;"> US Stocks Fail to Hold Gains </td>
   <td style="text-align:left;"> Wall Street opened Thursday's session on a steady note but failed to find support as investors remained focused on the Russia-Ukraine conflict and Fed Chair Jerome Powell's Senate testimony. Powell confirmed that a 25 basis point rate would come in March while opening the door for a more aggressive move if inflation does not abate as expected. Meanwhile, initial jobless claims fell way more than anticipated to an eight-week low of 215K, and the Challenger report showed job cuts were the lowest in three months. Investors now await the highly-anticipated jobs report due tomorrow for clues about the labour market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/03/cleveland-fed-president-mester-says-ukraine-war-accelerates-the-need-for-interest-rate-hikes.html </td>
   <td style="text-align:left;"> 2022-03-04 00:05:34 </td>
   <td style="text-align:left;"> Cleveland Fed President Mester says Ukraine war accelerates the need for interest rate hikes </td>
   <td style="text-align:left;"> , War in Ukraine only heightens the need for higher interest rates to get inflation under control, Cleveland Fed President Loretta Mester said Thursday.                                                                                                                                                                                                                                                        , The Russian invasion has pushed commodity prices higher, particularly for grains and energy, coming at a time when U.S. consumer prices are rising at the fastest annual rate in about 40 years.                                                                                                                                                                                                              , Mester told CNBC that the conflict, while posing broader downside risks to the economic growth picture, is making inflation worse and necessitating monetary-policy tightening from the central bank.                                                                                                                                                                                                         , "The situation in Ukraine adds uncertainty to the economic outlook," she told CNBC's Steve Liesman during a live "Squawk on the Street" interview. "The uncertainty about the outlook doesn't change the need to get inflation under control in the U.S. In fact, it actually adds upside risk that high inflation might continue, and that makes it more important to take action."                          , That action is likely to include a quarter-percentage-point increase in the Fed's benchmark short-term borrowing rate at the Federal Open Market Committee meeting in less than two weeks.                                                                                                                                                                                                                    , While Mester has been a backer of aggressive Fed tightening, she did not endorse making that first move even stronger, such as a 50-basis-point, or half-percentage-point, increase. She said that decision can be made later in the year after seeing how the initial rate hikes affect inflation.                                                                                                           , "We'll have more information in the second half of the year about the effect of the situation in Ukraine for the medium-run outlook in the U.S. It certainly poses some downside risks for growth," she said. "Those assessments might be a consideration in determining the appropriate pace at which to remove accommodation later in the year, but it certainly doesn't change the need for taking action.", Inflation as measured by the Fed's preferred personal consumption expenditures gauge rose 5.2% in January, well ahead of the central bank's 2% target and at the fastest pace since 1983. Other measures show inflation at an even higher level — the PCE index including volatile food and energy prices, for instance, rose 6.1% and the consumer price index was up 7.5%, both the highest since 1982.     , Energy prices have jumped, with West Texas Intermediate crude up about 20% since Feb. 25. Grains also have risen sharply, as wheat prices are up about 25% over the same period.                                                                                                                                                                                                                              , "We have to take action," Mester said. "We can't just say, oh, inflation is going to come down on its own. We've seen that isn't going to happen."                                                                                                                                                                                                                                                            , Mester spoke as Fed Chair Jerome Powell testified to Congress this week that he expects inflation to come back down as supply chain pressures abate and other pandemic-related stresses ease. Markets expect the Fed to enact the equivalent of six 25-basis-point increases this year.                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60571133?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-04 00:05:14 </td>
   <td style="text-align:left;"> Ukraine conflict: Growing numbers of firms pull back from Russia </td>
   <td style="text-align:left;"> Thirty years ago when communism collapsed in the Soviet Union, Western firms jostled to be first through the door.                                                                                                                                                                                          , The arrival of brands such as Coca-Cola and McDonald's symbolised the start of a new era, closely followed by retailers, miners, lawyers and advisers. And Russians became eager consumers of Levi jeans and luxury goods.                                                                                  , Now, in the wake of President Putin's military aggression in Ukraine, some firms, including Apple, Jaguar Land Rover, H&amp;M and Burberry, have announced they are pausing activities in Russia.                                                                                                               , So which firms, in which sectors, are exiting fastest and why have others remained silent?                                                                                                                                                                                                                  , When the conflict in Ukraine broke out, energy firm BP came under immediate pressure. The company owns a large stake in Russian energy giant Rosneft, but within days it had announced the operation would be hived off.                                                                                    , That was closely followed by pledges from Shell, ExxonMobil and Equinor to cut their Russian investments following pressure from shareholders, as well as from governments and the public.                                                                                                                  , Those energy stakes are valuable. BP's Rosneft stake accounted for a fifth of the firm's most recent profits. Shell could be sacrificing up to $3bn (£2.2bn) for exiting its ventures with Gazprom.                                                                                                         , But firms want to be seen to be doing the "right thing", says Russ Mould, investment director at AJ Bell.                                                                                                                                                                                                   , Meanwhile, Total Energies, another big player in Russia, has said it won't fund new projects in the country, but unlike its peers does not plan to sell existing investments.                                                                                                                               , It is still far from clear what will happen to those investments - whether they can eventually be sold, recouping some of their value, or if they will simply be written off.                                                                                                                               , Film fans in Russia wanting to go and see Warner Bros' new blockbuster The Batman won't be able to after the company suspended new film releases in the country.                                                                                                                                            , The US movie-maker was joined by Disney and Sony, with premieres of animation Turning Red and Marvel adaptation Morbius also being withdrawn.                                                                                                                                                               , Netflix is suspending all "future projects" in the country too while it assesses "the impact of current events".                                                                                                                                                                                            , All companies said their decisions were based on the "humanitarian crisis" in Ukraine, rather than as a result of sanctions that have been imposed.                                                                                                                                                         , But the decision will send a similar message. Being left out "in the cultural cold" will increase Russia's sense of isolation, says Susannah Streeter, senior investment and markets analyst at Hargreaves Lansdown.                                                                                        , Apple has halted all product sales in Russia, and limited other services such as Apple Pay and Apple Maps. Its shops have closed as well.                                                                                                                                                                   , For a firm like Apple selling imported items, that's a relatively straightforward decision to take, suggests Chris Weafer, chief executive of consulting firm Macro-advisory Limited. He has worked in Moscow for the past 24 years.                                                                        , "Companies do not want to be associated with the Russian regime and what's happening in Ukraine," he says. Their Russian business may be profitable, but "the rest of the world is more important" when it comes to a reputational risk like this.                                                          , On top of that, some tech companies, flooded by misinformation, are restricting Kremlin-linked media outlets posting on their platforms.                                                                                                                                                                    , Facebook, for example, was restricted in Russia after it said it had refused to stop fact-checking and labelling content from state-owned news organisations.                                                                                                                                               , Swedish furniture giant Ikea has become the latest retailer to halt its operations in Russia, affecting 17 stores, although Ikea's parent company is keeping its Mega shopping centres open.                                                                                                                , Another Swedish giant, fashion giant H&amp;M, has already suspended sales in Russia, and many more brands are likely to follow suit, according to Maureen Hinton of retail consultancy GlobalData. UK fashion firm Boohoo has also suspended its sales to Russia as well as closing its websites in the country., But while H&amp;M cited "tragic developments" in Ukraine, other brands including Nike have simply said they can't currently guarantee delivery of goods to customers in Russia.                                                                                                                                 , Burberry, which has a flagship store on Moscow's Red Square, said it was pausing all shipments because it had become "difficult to fulfil orders in Russia".                                                                                                                                                , Russia was the fifth largest European retail market in 2021, valued at £337.2bn. Some brands may not want to burn their bridges, if there's a chance of returning at some later date.                                                                                                                       , That is why many firms simply say they are "reconsidering" or "suspending" sales rather than withdrawing altogether, says Chris Weafer.                                                                                                                                                                     , And with sanctions limiting forms of payment, restrictions on taking foreign exchange out of the country and huge uncertainty over future prices and consumer appetite, the business climate is "extremely challenging" he adds, making the decision to hit pause easier.                                   , Jaguar Land Rover (JLR), General Motors, Aston Martin and Rolls-Royce are among the car-makers that have halted deliveries of vehicles to Russia due to the conflict, while construction equipment manufacturer JCB has paused all operations.                                                              , Cars are the biggest UK export to Russia, but still only 1% of UK cars went to Russia last year.                                                                                                                                                                                                            , So any decision to stop exporting won't be particularly costly, and will have been made easier by nagging concerns over whether or not payments will arrive, says investment analyst, Russ Mould.                                                                                                           , Transporting cars to Russia could prove difficult anyway, with the world's two largest cargo shipping companies, MSC and Maersk, suspending routes to and from Russia, except for food, medical and humanitarian supply deliveries.                                                                         , Some car manufacturers, such as Volkswagen and BMW have had to pause production at some European plants because of a lack of parts from Ukraine.                                                                                                                                                            , Large consultancy and law firms were some of the first to set up a presence in Russia after the fall of communism, but mostly operate out of the spotlight.                                                                                                                                                 , Most have so far remained tight-lipped over their plans, following Russia's invasion of Ukraine, but Jonathan Holt, the UK boss of KPMG, said it was reviewing its clients in line with the sanctions. He added that would mean ending some relationships both in the UK and across the world.              , EY said it would comply with sanctions, but has not confirmed whether or not it intends to sever ties with any clients.                                                                                                                                                                                     , Some legal and consulting firms also say they are reviewing their client base and Russian links.                                                                                                                                                                                                            , A senior executive for consultancy firm McKinsey, for example, wrote in a social media post that the company would "no longer serve any government entity in Russia."                                                                                                                                       , But according to reports in the Wall Street Journal, McKinsey would not comment on whether that ban would apply to state-controlled companies like Rosneft. According to McKinsey's website, it serves 21 of the 30 biggest Russian companies.                                                              , Tamzen Isacsson, chief executive of the Management Consultancies Association, said its members were "strictly abiding by the updated changes to sanction rules".                                                                                                                                            , That would inevitably mean "ending some work and supporting clients in adapting to making rapid changes to their operations in light of the new rules", she added.                                                                                                                                          , While the flood of announcements from firms stepping back from Russia goes on, there are calls for more to join them - especially some of the biggest consumer brands.                                                                                                                                      , But some will find it a lot harder to extricate themselves, even if pressure mounts in the coming days and weeks.                                                                                                                                                                                           , In retaliation against Western sanctions, the Russian government has banned the sale of Russian assets. So firms that, in recent years, have been encouraged to establish a presence in Russia, to make breakfast cereals or detergents, are "locked in" with local businesses, staff and supply chains.    , Mr Weafer believes it is likely that large consumer brands may express concerns over the military conflict, but try to "ride it out".                                                                                                                                                                       , "They'll leave the door open for an improvement that will allow them to stay," he predicts.                                                                                                                                                                                                                 , The obsession continues with the final series of Killing Eve...                                                                                                                                                                                                                                             , Incredible technology takes you on an emotional journey deep inside!                                                                                                                                                                                                                                        , The very best from around the world including Beck and The Bridge                                                                                                                                                                                                                                           , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-03-04 00:00:00 </td>
   <td style="text-align:left;"> Brent Crude Erases Sharp Gains </td>
   <td style="text-align:left;"> Brent crude futures slipped from their highest level since 2013 on Thursday in a choppy session that saw the UK benchmark dive from an intraday high of almost $120/barrel to around $110/barrel. The shift in sentiment came amid a report of a deal with Iran that could allow it to export more oil. Iran can reach the maximum oil production capacity in less than one or two months if sanctions are lifted, according to Oil Minister Javad Owji. Earlier today, the UK oil benchmark surged more than 5% to $119.7, a level not since 2013, on fears of further supply disruptions from Russian sanctions over its invasion of Ukraine. The US took aim on Wednesday at Russia’s oil refining sector with sweeping new export restrictions but has so far fallen short of targeting Russia’s oil and gas exports amid concerns over surging energy prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/stock-market </td>
   <td style="text-align:left;"> 2022-03-03 23:59:46 </td>
   <td style="text-align:left;"> Stocks in Ireland Hit 12-month Low </td>
   <td style="text-align:left;"> ISEQ decreased to a 12-month low of 7291 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-03 23:45:00 </td>
   <td style="text-align:left;"> Oil Prices Remain Volatile </td>
   <td style="text-align:left;"> WTI crude futures slipped from their highest level since 2008 on Thursday in a choppy session that saw the US benchmark dive from an intraday high of $116/barrel to below $110/barrel. The shift in sentiment came amid a report of a deal with Iran that could allow it to export more oil. Iran can reach the maximum oil production capacity in less than one or two months if sanctions are lifted, according to Oil Minister Javad Owji. Earlier today, the US oil benchmark surged more than 5% to $116, a level not since September 2008, on fears of further supply disruptions from Russian sanctions over its invasion of Ukraine. The US took aim on Wednesday at Russia’s oil refining sector with sweeping new export restrictions but has so far fallen short of targeting Russia’s oil and gas exports amid concerns over surging energy prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-03-03 23:43:41 </td>
   <td style="text-align:left;"> IBEX 35 Hits 12-month Low </td>
   <td style="text-align:left;"> ES35 decreased to a 12-month low of 8011 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-03-03 23:40:53 </td>
   <td style="text-align:left;"> FTSE 100 is down by 2% </td>
   <td style="text-align:left;"> FTSE 100 decreased 2% to 7281 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/03/technology/ukraine-war-misinfo.html </td>
   <td style="text-align:left;"> 2022-03-03 23:36:40 </td>
   <td style="text-align:left;"> In Ukraine’s Information War, a Blend of Fact and Fiction - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Experts say stories like the Ghost of Kyiv and Snake Island, both of questionable veracity, are propaganda or morale boosters, or perhaps both.                                                                                                                                                                                                                                                                                                                                                                                                                                            , By Stuart A. Thompson and Davey Alba                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Stuart Thompson and Davey Alba, tech reporters based in New York, report on online information flows.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Just days into the Russian invasion of Ukraine, a pilot with a mysterious nickname was quickly becoming the conflict’s first wartime hero. Named the Ghost of Kyiv, the ace fighter had apparently single-handedly shot down several Russian fighter jets.                                                                                                                                                                                                                                                                                                                                 , The story was shared by the official Ukraine Twitter account on Sunday in a thrilling montage video set to thumping music, showing the fighter swooping through the Ukrainian skies as enemy planes exploded around him. The Security Service of Ukraine, the country’s main security agency, also relayed the tale on its official Telegram channel, which has over 700,000 subscribers.                                                                                                                                                                                                  , The story of a single pilot’s beating the superior Russian air force found wide appeal online, thanks to the official Ukraine accounts and many others. Videos of the so-called Ghost of Kyiv had more than 9.3 million views on Twitter, and the flier was mentioned in thousands of Facebook groups reaching up to 717 million followers. On YouTube, videos promoting the Ukrainian fighter collected 6.5 million views, while TikTok videos with the hashtag #ghostofkyiv reached 200 million views.                                                                                   , People call him the Ghost of Kyiv. And rightly so — this UAF ace dominates the skies over our capital and country, and has already become a nightmare for invading Russian aircrafts. pic.twitter.com/lngfaMN01I                                                                                                                                                                                                                                                                                                                                                                           , There was just one problem: The Ghost of Kyiv may be a myth.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , While there are reports of some Russian planes that were destroyed in combat, there is no information linking them to a single Ukrainian pilot. One of the first videos that went viral, which was included in the montage shared by the official Ukraine Twitter account, was a computer rendering from a combat flight simulator originally uploaded by a YouTube user with just 3,000 subscribers. And a photo supposedly confirming the fighter’s existence, shared by a former president of Ukraine, Petro Poroshenko, was from a 2019 Twitter post by the Ukrainian defense ministry., When the fact-checking website Snopes published an article debunking the video, some social media users pushed back.                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , “Why can’t we just let people believe some things?” one Twitter user replied. “If the Russians believe it, it brings fear. If the Ukrainians believe it, it gives them hope.”                                                                                                                                                                                                                                                                                                                                                                                                              , In the information war over the invasion of Ukraine, some of the country’s official accounts have pushed stories with questionable veracity, spreading anecdotes, gripping on-the-ground accounts and even some unverified information that was later proved false, in a rapid jumble of fact and myth.                                                                                                                                                                                                                                                                                    , The claims by Ukraine do not compare to the falsehoods being spread by Russia, which laid the groundwork for a “false flag” operation in the lead-up to the invasion, which the Biden administration sought to derail. As the invasion neared, Russia falsely claimed that it was responding to Ukrainian aggression and liberating citizens from fascists and neo-Nazis. And since the assault began, Russia made baseless claims that Ukrainians had indiscriminately bombed hospitals and killed civilians.                                                                             , Instead, Ukraine’s online propaganda is largely focused on its heroes and martyrs, characters who help dramatize tales of Ukrainian fortitude and Russian aggression.                                                                                                                                                                                                                                                                                                                                                                                                                      , But the Ukrainian claims on social media have also raised thorny questions about how false and unproven content should be handled during war — when lives are at stake and a Western ally is fighting for its survival against a powerful invading force.                                                                                                                                                                                                                                                                                                                                  , “Ukraine is involved in pretty classic propaganda,” said Laura Edelson, a computer scientist studying misinformation at New York University. “They are telling stories that support their narrative. Sometimes false information is making its way in there, too, and more of it is getting through because of the overall environment.”                                                                                                                                                                                                                                                   , Anecdotes detailing Ukrainian bravery or Russian brutality are crucial to the country’s war plan, according to experts, and they are part of established war doctrine that values winning not just individual skirmishes but also the hearts and minds of citizens and international observers.                                                                                                                                                                                                                                                                                            , That is especially important during this conflict, as Ukrainians try to keep morale high among the fighters and marshal global support for their cause.                                                                                                                                                                                                                                                                                                                                                                                                                                    , “If Ukraine had no messages of the righteousness of its cause, the popularity of its cause, the valor of its heroes, the suffering of its populace, then it would lose,” said Peter W. Singer, a strategist and senior fellow at New America, a think tank in Washington. “Not just the information war, but it would lose the overall war.”                                                                                                                                                                                                                                               , In previous wars, combatants would try to sabotage enemy communication and limit the spread of wartime propaganda, even cutting physical communication lines like telegraph cables. But there are fewer such cables in the internet age, so in addition to downing communication towers and disrupting pockets of internet access, the modern strategy involves flooding the internet with viral messages that drown out opposing narratives.                                                                                                                                              , That digital battle moved at startling speed, experts noted, using an array of social media accounts, official websites and news conferences streamed online to spread Ukraine’s message.                                                                                                                                                                                                                                                                                                                                                                                                  , “You have to have the message that goes the most viral,” Mr. Singer said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , That was the case with another report from Ukraine involving a remarkable confrontation on Snake Island, an outpost in the Black Sea. According to an audio recording released by Pravda, a Ukrainian newspaper, and later verified by Ukraine officials, 13 border guards were offered a frightening ultimatum by an advancing Russian military unit: Surrender or face an attack. The Ukrainians responded instead with an expletive, before apparently being killed.                                                                                                                    , Audio of the exchange went viral on social media, and the clip posted on Feb. 24 by Pravda received more than 3.5 million views on YouTube. President Volodymyr Zelensky of Ukraine personally announced the deaths in a video, saying each guard would be awarded the title Hero of Ukraine.                                                                                                                                                                                                                                                                                              , But just days later, Ukrainian officials confirmed in a Facebook post that the men were still alive, taken prisoner by Russian forces.                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Social media has become the main conduit for pushing the information, verified or not, giving tech companies a role in the information war, too. The fake Ghost of Kyiv video, for instance, was flagged as “out of context” by Twitter, but the montage posted to Ukraine’s official Twitter account received no such flag. The false photo posted by Mr. Poroshenko, the former Ukrainian president, also had no flag.                                                                                                                                                                   , While Twitter monitors its service for harmful content, including manipulated or mislabeled videos, it said tweets simply mentioning the Ghost of Kyiv did not violate its rules.                                                                                                                                                                                                                                                                                                                                                                                                          , “When we identify content and accounts that violate the Twitter Rules, we’ll take enforcement action,” the company said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , In exercising discretion over how unverified or false content is moderated, social media companies have decided to “pick a side,” said Alex Stamos, the director of the Stanford Internet Observatory and a former head of security at Facebook.                                                                                                                                                                                                                                                                                                                                           , “I think this demonstrates the limits of ‘fact-checking’ in a fast-moving battle with real lives at stake,” Mr. Stamos said. He added that technology platforms never created rules against misinformation overall, instead targeting specific behaviors, actors and content.                                                                                                                                                                                                                                                                                                              , A Ukrainian city falls. Russian troops gained control of Kherson, the first city to be overcome during the war. The overtaking of Kherson is significant as it allows the Russians to control more of Ukraine’s southern coastline and to push west toward the city of Odessa.                                                                                                                                                                                                                                                                                                             , Russia’s advance. Russian troops encircled the strategic port city of Mariupol. A military convoy that has come within 20 miles of Kyiv appeared to have stalled in place, stymied by what British officials described as “staunch Ukrainian resistance, mechanical breakdown and congestion.”                                                                                                                                                                                                                                                                                             , The conflict and Beijing 2022. A Western intelligence report said that China told Russian officials not to invade Ukraine before the end of the Beijing Olympics, indicating it had some knowledge about Russia’s intentions. Separately, in a quick reversal, the organizers of the Paralympic Winter Games barred athletes from Russia and Belarus from competing.                                                                                                                                                                                                                       , A symbolic vote. The United Nations General Assembly adopted a resolution condemning Russia’s invasion of Ukraine, with the support of 141 countries out of 193. The vote, which is not legally binding, reflected Russia’s growing isolation on the international stage.                                                                                                                                                                                                                                                                                                                  , That leaves the truth behind some wartime narratives, like an apparent assassination plot against Mr. Zelensky or simply the number of troops killed in battle, fairly elusive, even as official accounts and news media share the information.                                                                                                                                                                                                                                                                                                                                            , Those narratives have continued as the war marches on, revealing the contours of an information war aimed not just at Western audiences but also at Russian citizens. At the United Nations on Monday, the Ukrainian ambassador, Sergiy Kyslytsya, shared a series of text messages that he said had been retrieved from the phone of a dead Russian soldier.                                                                                                                                                                                                                              , “Mama, I’m in Ukraine. There is a real war raging here. I’m afraid,” the Russian soldier apparently wrote, according to Mr. Kyslytsya’s account, which he read in Russian. The tale seemed to evoke a narrative advanced by officials and shared extensively on social media that Russian soldiers are poorly trained and too young, and don’t want to be fighting their Ukrainian neighbors. “We are bombing all of the cities together, even targeting civilians.”                                                                                                                       , The story, whether true or not, appears tailor-made for Russian civilians — particularly parents fretting over the fate of their enlisted children, experts said.                                                                                                                                                                                                                                                                                                                                                                                                                          , “This is an age-old tactic that the Ukrainians are trying to use, and that is to draw the attention of the mothers and the families in Russia away from the more grandiose aims for war onto, instead, the human costs of war,” said Ian Garner, a historian focusing on Russia who has followed Russian-language propaganda during the conflict. “We know that this is really effective.”                                                                                                                                                                                                 , Official Ukrainian accounts have also uploaded dozens of videos purportedly showing Russian prisoners of war, some with bloody bandages covering their arms or face. In the videos, the prisoners are heard denouncing the invasion. The videos may raise questions about whether Ukraine is violating the Geneva Conventions, which has rules about sharing images of war prisoners.                                                                                                                                                                                                      , Russia has also engaged in its own form of mythmaking, but experts say it has been far less effective. Rather than targeting international observers with emotional appeals, Russia has focused on swaying its own population to build support for the battle, Dr. Garner said.                                                                                                                                                                                                                                                                                                            , Since Russian state media is still calling the conflict a “special military operation” and not a war — in line with the description used by President Vladimir V. Putin — state broadcasters are left “trying to talk about a war that is apparently not happening,” Dr. Garner said.                                                                                                                                                                                                                                                                                                      , The Russian government “can’t play to its strongest narratives of individual sacrifice,” he added, instead relying on stories of Ukrainians bombing hospitals and civilians, providing no evidence.                                                                                                                                                                                                                                                                                                                                                                                        , Ukraine’s efforts to amplify its own messages also leave little room for Russia to dominate the conversation, said Mr. Singer, the strategist from New America.                                                                                                                                                                                                                                                                                                                                                                                                                            , “A key to information warfare in the age of social media is to recognize that the audience is both target of and participant in it,” he said. He added that social media users were “hopefully sharing out those messages, which makes them combatants of a sort as well.”                                                                                                                                                                                                                                                                                                                 , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/03/citigroup-ceo-jane-fraser-sees-tremendous-upside-in-stock-after-tepid-investor-day-response.html </td>
   <td style="text-align:left;"> 2022-03-03 23:34:02 </td>
   <td style="text-align:left;"> Citigroup CEO Jane Fraser sees 'tremendous upside' in stock after tepid Investor Day response </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                        , Citigroup CEO Jane Fraser called her first Investor Day conference a success despite lingering skepticism and an underwhelming reaction from analysts covering the bank.                                                                                                                                               , Fraser told CNBC's David Faber on Thursday in an interview that while it will "take a few years" to achieve her targets for returns, investors will see revenue growth from her efforts "sooner rather than later." The interview aired on "Squawk on the Street."                                                     , When asked how long Citigroup would continue to trade well below its book value, Fraser had this response: "I think there's tremendous upside in our stock, and I'm looking forward to doing the job needed to get the execution done so that it gets realized," she said.                                             , Fraser, who started as CEO of Citigroup a year ago, held her inaugural investor conference on Wednesday. It was a nearly full-day affair in which Fraser and her deputies pitched their vision of a simpler, more profitable institution centered around the bank's strengths in global corporate banking and payments., But some analysts were disappointed that Fraser set a medium-term return target of 11% to 12%, arguing that it is hard to recommend Citigroup's stock because it will take several years to even accomplish that modest level. Two analysts downgraded the bank after the event.                                       , "The uninspiring medium-term ROTCE target of 11-12% is simply not high enough to merit an Overweight recommendation in the near term," Atlantic Equities' John Heagerty said in a note Thursday.                                                                                                                       , Citigroup, which has traditionally been the most global of big U.S. banks, has 200 employees continuing to toil in Ukraine despite the Russian-led war there, Fraser said. They are helping clients with payroll, supply chains and food, she said.                                                                    , "I don't think anybody knows how long they can keep going," she said.                                                                                                                                                                                                                                                  , Meanwhile, both Citigroup and its clients are working to unwind their financial exposures to Russia, she said.                                                                                                                                                                                                         , "There is a big unwind going," she said.                                                                                                                                                                                                                                                                               , This story is developing. Please check back for updates.                                                                                                                                                                                                                                                               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                 , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                 , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                       , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                       , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                     , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/currency </td>
   <td style="text-align:left;"> 2022-03-03 23:27:56 </td>
   <td style="text-align:left;"> Russian Ruble Pares Losses as Talks Begin </td>
   <td style="text-align:left;"> The Russian ruble pared steep losses to regroup at 105 per USD, as Russia and Ukraine commenced talks in Belarus. The rebound came after the ruble fell to fresh lows of 118 on Thursday, as Russia's invasion of Ukraine and consequent Western sanctions continue to pressure Russian assets. Rating agencies Fitch and Moody’s downgraded Russian sovereign bonds by six notches to “junk” status, while sell-offs led the LSE to suspend Russian securities from trading. Western allies largely limited Russian entities' ability to transact internationally after agreeing to remove key Russian banks from the SWIFT interbank system and freezing the assets of the central bank. The tumble came despite strong efforts of stabilization by the CBR, as the bank raised its key policy rate to 20% from 9.5%, banned foreigners from selling Russian securities, and mandated Russian brokers to charge 30% in commission to individuals for the purchase of foreign currencies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-03 23:27:00 </td>
   <td style="text-align:left;"> Canada Stocks at 2-Week Highs </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, rose to levels not seen in two weeks on Thursday, consolidating a 1.2% gain in the previous session, as higher gold and oil prices boosted heavyweight energy and mining stocks. On the earnings front, Canadian Natural Resources increased dividends as Q4 profits surged, as the global recovery and tight supplies fueled a rally in oil prices to multi-year highs. Also, Toronto-Dominion Bank reported higher quarterly profits, underpinned by revenues from its Canadian and American retail banking units, which more than offset higher costs at its wholesale banking unit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/zinc </td>
   <td style="text-align:left;"> 2022-03-03 23:11:19 </td>
   <td style="text-align:left;"> Zinc Price Tops $4,000 </td>
   <td style="text-align:left;"> Zinc futures skyrocketed to above $4,000 a tonne in the first trading week of March, a level not seen since May of 2007, on lingering concerns of further supply disruptions due to prolonged high energy prices. Mounting sanctions on Russia for invading Ukraine led to an international energy crunch, which, in turn, could spark additional supply disruptions of energy-intensive zinc if European smelters decide electricity prices are too high to keep smelters running. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/first-us-city-breaches-5-a-gallon </td>
   <td style="text-align:left;"> 2022-03-03 23:06:37 </td>
   <td style="text-align:left;"> Oil surge has gas breach $5 a gallon in first US city </td>
   <td style="text-align:left;"> The Schork Group principal Stephen Schork initially predicted Brent crude will hit $116 per barrel this month and notes it only took a few days to hit that mark.                                                                                           , San Francisco has become the first city in the United States to breach an average of $5 a gallon, according to an industry expert as the Russia-Ukraine conflict juices oil prices, which topped $113 in trading Thursday.                                  , "It's been quite ugly as gas prices rise nationally, but nowhere has the pain been more significant than California, where prices have breached the $5 gallon mark," Patrick De Haan, head of petroleum analysis for GasBuddy, told FOX Business Thursday.  , OIL PRICES SURGE TOWARD $110 PER BARREL DESPITE RELEASE OF SUPPLIES                                                                                                                                                                                         , Currently, the state average for a gallon of regular gasoline in California is $4.940, according to AAA. It's a significant leap from the national average of about $3.728, according to AAA data.                                                          , RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                                                        , De Haan wanred that prices "will continue to head north" and could even reach $5.35 per gallon by the end of March.                                                                                                                                         , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                     , For several weeks, there have been widespread fears that sanctions placed on Russia would threaten the global oil market, already facing a tight supply, and eventually drive up gas prices for U.S. motorists.                                             , This week, the United States and other major governments agreed to release 60 million barrels of crude from stockpiles to stabilize supplies, but it failed to calm anxiety over Russia’s attack on Ukraine as oil prices still rose.                       , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                 , The loss of 10 million barrels a day of oil production "can't be offset by meager releases of oil," De Haan said pointing to the 60 million barrels of crude from stockpiles                                                                                , "It would likely need to be more like 100-200 million barrels to have much effect," he added.                                                                                                                                                               , The Associated Press contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/non-manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-03-03 23:03:00 </td>
   <td style="text-align:left;"> US Services Growth Unexpectedly Eases: ISM </td>
   <td style="text-align:left;"> The ISM Services PMI for the US fell for a third month to 56.5 in February of 2022 from 59.9 in January, below market forecasts of 61. The reading pointed to the slowest growth in the services sector in a year, although a robust and above long-run average. A slowdown was seen in business activity (55.1 vs 59.9), new orders (56.1 vs 61.7) and supplier deliveries (66.2 vs 65.7) while employment contracted (48.5 vs 52.3) and price pressures intensified (83.1 vs 82.3). Service providers "continue to be impacted by supply chain disruptions, capacity constraints, inflation, logistical challenges and labor shortages. These conditions have affected the ability of businesses to meet demand, leading to a cooling in business activity and economic growth", said  Anthony Nieves, Chair of the ISM Services Business Survey Committee. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/factory-orders </td>
   <td style="text-align:left;"> 2022-03-03 23:02:00 </td>
   <td style="text-align:left;"> US Factory Orders Rise More than Expected </td>
   <td style="text-align:left;"> New orders for US manufactured goods went up 1.4 percent from a month earlier in January of 2022, quickening from a revised 0.7 percent increase in December and above market expectations of 0.7 percent. Orders rose faster in industries producing both durables (1.6 percent vs 1.2 percent in December) and nondurable goods (1.2 percent vs 0.1 percent). Among durable goods, main upward pressure came from transportation equipment (3.4 percent vs 1.7 percent), mainly driven by orders for nondefense aircraft and parts; followed by machinery (2.6 percent vs 1.3 percent), boosted by material handling equipment and ventilation, heating, air conditioning &amp; refrigeration equipment. Meanwhile, factory orders excluding transportation equipment rose 1.0 percent, faster than an upwardly revised 0.5 percent gain in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-03-03 22:58:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Snaps 2-Session Winning Streak </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index fell 1.5% to 2,104 on Wednesday, following two consecutive sessions of gains, as the capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, slumped 10.9% to 1,639. Meanwhile, the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, was up 65 points to 2,699; and the supramax index rose 49 points to 2,520. "For the moment, we are seeing vessels, primarily the medium-sized Panamax types that tend to carry the bulk of the grain exports from Black Sea, being diverted towards the Atlantic basin. However, this can lead to a build up of tonnage in South America and the U.S. Gulf and can potentially pressure rates downward.", Athens-based EastGate Shipbrokers said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/composite-pmi </td>
   <td style="text-align:left;"> 2022-03-03 22:53:23 </td>
   <td style="text-align:left;"> US Composite PMI Remains Strong: Markit </td>
   <td style="text-align:left;"> The IHS Markit US Composite PMI was revised slightly lower to 55.9 in February of 2021 from a preliminary of 56, still way better than January's Omicron-induced low of 51.1. Growth regained momentum at manufacturers (57.3) and service providers (56.5). Stronger demand conditions at private sector firms led to the fastest upturn in new business since July 2021. Greater new sales were supported by increased foreign client demand, as new export orders rose solidly. Inflationary pressures remained elevated, despite manufacturers recording a slight slowdown in hikes in supplier costs. The rate of charge inflation quickened to a four-month high amid the sharpest rise in service sector output prices on record. Further expansions in backlogs of work at private sector firms led to a greater impetus to hire new staff. Despite ongoing reports of labor shortages, firms were able to increase workforce numbers at the steepest pace since May 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/services-pmi </td>
   <td style="text-align:left;"> 2022-03-03 22:48:12 </td>
   <td style="text-align:left;"> US Services PMI Revised Slightly Lower: Markit </td>
   <td style="text-align:left;"> The IHS Markit US Services PMI was revised slightly lower to 56.5 in February of 2021 from a preliminary of 56.7, but sill pointed to a strong growth in the services sector, following the easing of COVID-19 restrictions. The faster rise in output was supported by the steepest upturn in new sales for seven months. Total new orders were also aided by a solid increase in foreign client demand. In line with improved demand conditions, firms expanded their workforce numbers at the fastest pace since last May. At the same time, business confidence was buoyed by new opportunities for growth, with the degree of optimism reaching the strongest since November 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/nickel </td>
   <td style="text-align:left;"> 2022-03-03 22:45:52 </td>
   <td style="text-align:left;"> Nickel Hits Highest Since 2011 </td>
   <td style="text-align:left;"> Nickel futures surged above the $26,400 per tonne level for the first time since May of 2011, as Western sanctions against Russia over its invasion of Ukraine sparked renewed concerns over the metal supply. Along with prospects for loss of supply from the world's third-larges, robust demand from the stainless steel and battery and dwindling inventories lent further optimism to the metal bulls. Nickel stocks in LME-registered warehouses have dropped almost 70% since April last year to 83,328 tonnes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-03 22:42:01 </td>
   <td style="text-align:left;"> Swiss 10Y Bond Bounces Back from 4-Week Low </td>
   <td style="text-align:left;"> The yield on the Swiss 10-year government bond rose above the 0.2% mark, bouncing back from the four-week low of 0.08% touched on March 1st amid prospects of tighter monetary policy by major central banks. Fed Chair Powell told US lawmakers that the US economy no longer needs such an accommodative policy stance and that he supports a 25bps increase in the Fed’s benchmark interest rate this month. At the same time, ECB officials said that the inflation narrative in the bloc needs to be adjusted while monetary accommodation should be scaled back. Domestically, the Swiss National Bank remains committed to its ultra-loose monetary policy, despite February’s consumer inflation coming at a 13-year high, as the bank attempts to avoid the excessive appreciation of the franc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/03/watch-federal-reserve-chair-powell-speak-live.html </td>
   <td style="text-align:left;"> 2022-03-03 22:38:06 </td>
   <td style="text-align:left;"> Watch Federal Reserve Chair Powell speak live on policy before Senate committee </td>
   <td style="text-align:left;"> , [The stream is slated to start at 10 a.m. ET. Please refresh the page if you do not see a player above at that time.]                                                                                                                                                                                                                                                  , Federal Reserve Chair Jerome Powell speaks Thursday before the U.S. Senate Committee on Banking, Housing and Urban Affairs in day two of his congressionally mandated semiannual testimony on monetary policy.                                                                                                                                                         , In remarks Wednesday before the House Financial Services Committee, the central bank leader said the war in Ukraine had "highly uncertain" potential impacts on the economy. But he said the Fed is still prepared to move forward with interest rate increases aimed at taming runaway inflation.                                                                     , Powell noted that the lookout otherwise is solid, with an "extremely tight" labor market and price pressures that he still expects to recede later in the year. He expects the Fed to raise its benchmark borrowing rate a quarter-percentage point at the March policy meeting, but added that he will consider potentially larger increases if inflation remains hot., "I think it's appropriate for us to move ahead. Inflation is high. The committee is committed to using our tools to bring it back down to levels of price stability, which is to say 2% inflation," he said Wednesday. "I would also say that given the current situation, we need to move carefully and we will. We need to be nimble."                               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                 , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                 , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                       , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                       , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                     , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-03 22:35:00 </td>
   <td style="text-align:left;"> Dow and S&amp;P Rise for 2nd Day </td>
   <td style="text-align:left;"> Both the Dow Jones and the S&amp;P 500 were slightly higher on Thursday, extending the rally from the day before, while the Nasdaq failed to hold early gains and traded in the red, as investors continue to monitor Russia’s invasion of Ukraine and as crude oil prices eased slightly on a potential deal with Iran. Yesterday, Chair Fed Powell said he remains committed to easing cost pressures through rate hikes despite the uncertainty around Ukraine, pointing to a 25 basis point rate hike this month. Meanwhile, initial jobless claims fell way more than anticipated to an 8-week low of 215K and the Challenger report showed job cuts were the lowest in 3 months. Traders now await the highly-anticipated jobs report due tomorrow for an update on the labour market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/td:cn </td>
   <td style="text-align:left;"> 2022-03-03 22:23:54 </td>
   <td style="text-align:left;"> TD Bank earnings above expectations at 2.08 CAD </td>
   <td style="text-align:left;"> TD Bank (TD) released earnings per share at 2.08 CAD, compared to market expectations of 2.05 CAD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-03 22:23:00 </td>
   <td style="text-align:left;"> Brazilian Equities Rise for 3rd Session </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, was up 0.5% to around 115,763 on Thursday, its highest level so far this year and extending gains for a third straight session, mainly pushed up by heavyweight miner Vale and steel companies, tracking rising iron ore prices. At the same time, Federal Reserve Chair Jerome Powell signaled the central bank would likely raise interest rates less than some investors had feared. Meanwhile, traders continued to monitor developments around the Ukraine conflict and mounting sanctions against Russia. On the domestic data front, the IHS Markit Brazil Manufacturing PMI rose to 49.6 in February of 2022, from a 20-month low of 47.8 in January, pointing to a near stabilization of the sector. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-03 22:16:41 </td>
   <td style="text-align:left;"> US Stocks Set to Open Higher </td>
   <td style="text-align:left;"> US stocks futures erased early losses to add around 0.7% on Thursday, following a big rally the day before, as investors continue to monitor Russia’s invasion of Ukraine although news of an allegedly deal with Iran that could allow the country to export more oil offered a momentarily relief to soaring energy costs. Meanwhile, initial jobless claims fell way more than anticipated to an 8-week low of 215K and the Challenger report showed job cuts were the lowest in 3 months. Traders now await the highly-anticipated jobs report due tomorrow for an update on the labour market. Early this week, Powell said he remains committed to easing cost pressures through rate hikes despite the uncertainty around Ukraine, pointing to a 25 basis point rate hike this month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-03-03 22:09:00 </td>
   <td style="text-align:left;"> Brent Crude Falls from 2014-High </td>
   <td style="text-align:left;"> Brent crude futures traded around $112 per barrel on Thursday, after briefly breaching the $119 level earlier in the session on news of a deal with Iran that could allow it to export more oil. Iran can reach the maximum oil production capacity in less than one or two months if sanctions are lifted, according to Reuters news citing Oil Minister Javad Owji. The UK oil benchmark has been surging to levels not since 2013, on fears of further supply disruptions from Russian sanctions over its invasion of Ukraine. The US took aim on Wednesday at Russia’s oil refining sector with new export curbs and targeted Belarus with sweeping new export restrictions, but has so far stopped short of targeting Russia’s oil and gas exports amid concerns over energy prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/03/stocks-making-the-biggest-moves-in-the-premarket-best-buy-bjs-snowflake-and-more.html </td>
   <td style="text-align:left;"> 2022-03-03 22:08:24 </td>
   <td style="text-align:left;"> Stocks making the biggest moves in the premarket: Best Buy, BJ's, Snowflake and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                           , Take a look at some of the biggest movers in the premarket:                                                                                                                                                                                                                                                                               , Best Buy — Shares of the retailer climbed 5% in premarket trading after the company announced it was raising its quarterly dividend by 26%. The move comes despite an underwhelming fourth-quarter report from Best Buy, with adjusted earnings just matching analyst expectations, according to Refinitiv.                               , BJ's Wholesale — The wholesale retailer saw shares sink 13.8% premarket after missing Wall Street expectations for quarterly revenue. BJ's reported revenue of $4.36 billion, compared with $4.4 billion expected by analysts, according to StreetAccount.                                                                                , Big Lots — Big Lots shares fell 6.4% in premarket trading after a weaker-than-expected earnings report. The retailer posted earnings of $1.75 per share versus the Refinitiv consensus estimate of $1.89 per share.                                                                                                                       , Burlington Stores — Shares of the off-price retailer sunk 12.1% premarket after Burlington missed Wall Street estimates on the top and bottom line. Burlington reported quarterly adjusted earnings of $2.53 per share on revenue of $2.60 billion. The Refinitiv consensus estimate was $3.25 per share earned on $2.78 billion in sales., Kroger — Kroger shares gained 5.8% in premarket trading after the grocery chain beat on earnings. The company reported fourth-quarter adjusted earnings of 91 cents per share on revenue of $33.05 billion. Analysts had expected a profit of 74 cents per share on revenue of $32.86 billion, according to Refinitiv.                    , Snowflake — Shares of Snowflake are down more than 18% premarket after the data-analytics software company forecasted slowing product revenue growth. The company reported an adjusted loss of 43 cents per share. Revenue came in at $383.8 million, beating analyst estimates of $372.6 million.                                        , Box Inc. — Shares of Box gained 5.7% premarket after the company reported better-than-expected quarterly results. The company earned 24 cents per share excluding items on $233 million in revenue. Analysts surveyed by Refinitiv were expecting the company to earn 23 cents on $229 million in revenue.                                , American Eagle Outfitters — Shares of the retailer declined 4.6% premarket after American Eagle's quarterly report. The company warned higher freight costs would weigh on earnings in the first half of 2022.                                                                                                                            , Intel — Shares of Intel fell 1.3% in early morning trading after Morgan Stanley downgraded the stock from equal-weight to underweight. "Downgrades of value stocks ... will let us focus on more actionable situations that offer relatively more attractive risk-reward going forward," Morgan Stanley's Ethan Puritz said.              , Southwest — Southwest shares gained 1.9% premarket after Evercore ISI upgraded the airline stock to outperform from in-line. "Greater relative financial strength + margin focused planning lead us to raise our rating on Southwest," the firm said.                                                                                     , —CNBC's Jesse Pound and Samantha Subin contributed to this report.                                                                                                                                                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-03 22:01:00 </td>
   <td style="text-align:left;"> Oil Falls from 2008-High </td>
   <td style="text-align:left;"> WTI crude futures fell more than 2% to below $108 per barrel on Thursday, after rising as much as 5% earlier in the session on news of a deal with Iran that could allow it to export more oil. Iran can reach the maximum oil production capacity in less than one or two months if sanctions are lifted, according to Oil Minister Javad Owji. Earlier today, the US oil benchmark surged to $116, a level not since September 2008, on fears of further supply disruptions from Russian sanctions over its invasion of Ukraine. The US took aim on Wednesday at Russia’s oil refining sector with sweeping new export restrictions but has so far fallen short of targeting Russia’s oil and gas exports amid concerns over surging energy prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-03-03 21:59:00 </td>
   <td style="text-align:left;"> US Natural Gas Erases Gains </td>
   <td style="text-align:left;"> US natural gas futures fell more than 2% to almost $4.6 erasing earlier gains on Thursday, tracking high volatility in EU and UK contracts and lower crude oil prices as traders continued to assess risks posed by sanctions against Russia on the back of strong demand abroad. Europe is scrambling to refill its historically low inventory levels and reduce its dependency on Russian gas following the Russian invasion of Ukraine. Europe remained the top destination for US LNG shipments for the third month in a row in February, while Asia, the second most important destination, was also boosting efforts to refill inventory levels, with China striving to shift to cleaner energy sources. Also, the White House said it was open to sanctioning Russia’s energy exports after days of speculation. Elsewhere, crude oil prices fell from over 13-year highs after news that Iran could reach maximum production in less than two months after nuclear deal is reached. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-03-04 09:26:45 UTC +8

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
   <td style="text-align:left;"> 2022-03-04 09:26:36 </td>
   <td style="text-align:left;"> $SPY 🤡 market dropped for nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:33 </td>
   <td style="text-align:left;"> $SPY now that all the bots have finished selling. Fuck this market! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:30 </td>
   <td style="text-align:left;"> $SPY I thought this was at 429 3mins ago? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:29 </td>
   <td style="text-align:left;"> $SPY Hopefully that power plant doesn’t blow up that would be pretty devastating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:28 </td>
   <td style="text-align:left;"> $SPY if this thing dont blow up ... Gonna be a F u candle tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:22 </td>
   <td style="text-align:left;"> $SPY $QQQ They are pushing to 4330 then it will flush again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:19 </td>
   <td style="text-align:left;"> $SPY our hero will save the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:17 </td>
   <td style="text-align:left;"> $SPY I still wanna know how the hell the price teleported to 436 to 428 and back to 436.  Some game genie shit at work here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:13 </td>
   <td style="text-align:left;"> $SPY I hate when every stock drops 3% but spy is still green and I have spy puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:10 </td>
   <td style="text-align:left;"> $SPY turn out it wasnt a nuke. $TSLA calm down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:08 </td>
   <td style="text-align:left;"> $SPY Well the fire is in the administrative building and the reactor has been shut off. What a wild ride. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:07 </td>
   <td style="text-align:left;"> $SPY ☢️ ATTENTION ALL: THE 2022 NUCLEAR BULL MARKET HAS OFFICIALLY BEGUN ☢️ CLOSE ALL SHORTS AND PREPARE FOR GREEN CANDLES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:06 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY 
The everything dump cometh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:06 </td>
   <td style="text-align:left;"> $SPY Definitely another over exaggerated news piece that’s nothing new that tanks the spy. This will really be the down fall to the stock market if this doesn’t stop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:26:04 </td>
   <td style="text-align:left;"> $SPY 4300 now resistance instead of support.  Ooof  I think we open 428 on the spy ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:57 </td>
   <td style="text-align:left;"> $SPY 

All good guys, I invested in digital art that belongs to only me. Safest WWWIII asset. People are going to be kicking down doors to get them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:57 </td>
   <td style="text-align:left;"> $SPY wanna fix the unemployment issue tomorrow Biden. Anyone not working will be sent to war. Problem solved </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:48 </td>
   <td style="text-align:left;"> $QQQ $SPY hmm... seems like no one whould be able to stop Russia even if they shoot at the nuclear plant. Lol what a joke. It&amp;#39;s like the whole world is imposing sanctions to Russia and praying so hard they will stop by themselves. Serious? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:47 </td>
   <td style="text-align:left;"> $SPY I was going to sell at lunch today after all of my stock were green premarket.  I went to lunch and they were all down so I didn’t.  Now they’re down even more.  I’ll fight Putin right now.  Sup bro? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:40 </td>
   <td style="text-align:left;"> $SPY .:: have the pool conversion into bunker project going well … about 50%!?  Lid is poured;  takes 28-days for concrete to cure before can pull forms; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:39 </td>
   <td style="text-align:left;"> $SPY Putin got played by Xi. &amp;quot;Yes, go take it. Everything will be fine.&amp;quot; I&amp;#39;ll buy the Ruble when it is at Zero. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:39 </td>
   <td style="text-align:left;"> $SPY YALL POSTING TOO FAST LMAO CHILL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:38 </td>
   <td style="text-align:left;"> $SPY LMAO, Cramer telling investors to be buying just hours ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:38 </td>
   <td style="text-align:left;"> $SPY Bulls receive their judgement day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DJIA $XLE

🚨🚨🚨PANIC PANIC SELL ALL RISK ASSETS 😂

BREAKING: Firefighters gain access to nuclear power plant in Ukraine, where an administrative building is on fire - ZN

❗️According to Andrey Tuz, spokesman of the press service of the nuclear power plant, there is no threat of radiation spread.

Seriously what purpose does it serve Russia to cause an explosion 10x bigger than chernobyl and cause an absolute disaster! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:34 </td>
   <td style="text-align:left;"> $SPY a bunch of stocks went down 2-3% during the last 15 minutes of ah due to fire at nuclear plant news.  At least it occurred AH, market no longer behaves like a mature 40 year old, it now behaves like a 16 year old teen.

Firefighters are  on putting out fire, should be green before open.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:33 </td>
   <td style="text-align:left;"> $SPY Putin please nuke wall st and put me out of misery of reading posts here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:31 </td>
   <td style="text-align:left;"> $SPY the real war is Powell vs Putin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:28 </td>
   <td style="text-align:left;"> $SPY honestly, what’s more likley…we wake up to nuclear Disaster or they put fire out and the non-operational power plant didn’t suffer any radiation leaks?   This is a giant bear trap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:25 </td>
   <td style="text-align:left;"> $SPY 
Think about it these AH Biden and Kerry sacrificed our national security and the worlds bec they bowed down to these climate change frauds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:24 </td>
   <td style="text-align:left;"> $SPY nuclear war isn’t  programmed into algos, stocks being pumped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:22 </td>
   <td style="text-align:left;"> $SPY $JPM JPMORGAN: “…almost 70% of Russian oil is struggling to find buyers... nine cargoes of 100,000 tons each for March loading failed to find buyers on Wednesday.. Russian benchmark Urals oil is being offered at a record $20 discount to international benchmark, with no bids.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:21 </td>
   <td style="text-align:left;"> $SPY bears buying the fake news lmao hope this helps my fellow bulls 🇺🇸

Admin building on fire, not the reactor which is MILES underground.

No radiation 

Meltdown UNLIKELY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:20 </td>
   <td style="text-align:left;"> $SPY 
For the really ignorant here. 
Ukraine has power, gas, sewer, water, internet and cellular communications.

If Russia wanted Ukraine in the dark they would have done it a week ago when they took out their entire air defense system in the first 3 hours.

This is a low IQ bunch on here.🤦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:18 </td>
   <td style="text-align:left;"> $SPY look at that beautiful fake out, many bears trapped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:18 </td>
   <td style="text-align:left;"> $SPY MAYBE A SUB 400 OPEN TMR IDK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:13 </td>
   <td style="text-align:left;"> $SPY 

Futes starting to rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:11 </td>
   <td style="text-align:left;"> $SPY Biden is sleeping since 25 mins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:11 </td>
   <td style="text-align:left;"> $SPY NATO countries will be severely affected by this. If you&amp;#39;re young and capable get ready to be enlisted for WW3. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:10 </td>
   <td style="text-align:left;"> $SPY FAKE NEWS. AMAZING..PURE FUD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:10 </td>
   <td style="text-align:left;"> $SPY @blancobull thats not your tesla on fire is it😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:05 </td>
   <td style="text-align:left;"> $SPY If they really are attacking the nuclear power plant, the U.S. and the world really needs to let Russia just do it. Ukraine is a sacrificial lamb. 

We can&amp;#39;t let Ukraine be the end of the world due to NUCLEAR WAR. 

Ukraine will be end of the world if somebody else gets involved </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:04 </td>
   <td style="text-align:left;"> $SPY Powell can buy anytime </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:02 </td>
   <td style="text-align:left;"> $SPY 

OFG unlocked at spy 460

Moron moo unlocked at 380 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:25:00 </td>
   <td style="text-align:left;"> $SPY I just hope we die quick from the nukes.  And not fallout.  No one gonna need money after the button are pressed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:58 </td>
   <td style="text-align:left;"> $SPY $VXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:52 </td>
   <td style="text-align:left;"> $SPY Biden has launched nukes on longs portfolios. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:51 </td>
   <td style="text-align:left;"> $SPY are u guys aware what&amp;#39;s going on around nuclear reactor in ukraine ? Futures in Europe and here bleeding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:49 </td>
   <td style="text-align:left;"> $SPY for now it doesn&amp;#39;t seem like a real threat, likely just another excuse for WS to dump the markets. And obviously markets will go down in such case. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA and it’s disgusting that the US/EU and media should lead Ukrainians  to believe that fighting tanks w Molotov cocktails is some kind of strategy that will end well. It’s the height of irresponsibility. If Biden and the rest of them weren’t going to send troops, we should have pressed Zelensky to surrender immediately. Be realistic. Don’t tell them to fight tanks w these pathetic weapons and get themselves killed. I’m disgusted. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:45 </td>
   <td style="text-align:left;"> $SPY down $6.48 or up .68?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:44 </td>
   <td style="text-align:left;"> $SPY here come the thirsty bulls who cant wait more then 5 minutes without throwing their life savings at spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:36 </td>
   <td style="text-align:left;"> $SPY special place for Pootin boy somewhere next to Hitler and a few of their mutual friends. Can&amp;#39;t wait to hear that someone had the real strength to take that sick dude out of commission - the world would certainly rally, though there is a very long lasting overhang from this totally unnecessary destruction of human life and properties. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:35 </td>
   <td style="text-align:left;"> $SPY Wow this looks really bad. That cannot be the only news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:31 </td>
   <td style="text-align:left;"> $SPY 
Cmon  on Wall Street this is pocket change .. End this now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:31 </td>
   <td style="text-align:left;"> $SPY $429 is the actual price after hours not $436, I added this wedge today but didn’t think the price would fall out of it today. That was fast, and the Stoch RSI &amp;amp; MACD is implying it will fall much lower… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:31 </td>
   <td style="text-align:left;"> $SPY https://twitter.com/i/spaces/1LyxBowlNzoKN?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:31 </td>
   <td style="text-align:left;"> $SPY how are people not expecting this… and worse to come. With the heavy heavy penalties his country is going through for the invasion, he won’t stop until he has something worth incurring those penalties… hate to break it to you, but it won’t be capturing Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:27 </td>
   <td style="text-align:left;"> $SPY it will magically be green by the morn. Sigh... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:27 </td>
   <td style="text-align:left;"> $SPY  
It is a banger of a jam tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:26 </td>
   <td style="text-align:left;"> $SPY Futed already RIPPING MUCH HIGHER NOW !!!!

😲😲📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:24 </td>
   <td style="text-align:left;"> $SPY $NQ_F got two trades off the bottom..  yeehaw ; )   this is the moment of no bull no bear just pure price reaction.    
figure out nuclear Chernobyl later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:24 </td>
   <td style="text-align:left;"> $SPY Fuck Putin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:24 </td>
   <td style="text-align:left;"> $SPY MAYBE ITS FAKE NEWS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:20 </td>
   <td style="text-align:left;"> $SPY if you’re bullish right now you are bullish on slow painful radioactive death </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:19 </td>
   <td style="text-align:left;"> $SPY 

THANK YOU QE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:17 </td>
   <td style="text-align:left;"> $SPY they’re keeping u from panic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:16 </td>
   <td style="text-align:left;"> $SPY lol omg.  Putin is crazy.  Wtf. There is already 1mill bounty on his head from Russian peeps. What the end game? Take over a country that’s blown to pieces and rubble? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:14 </td>
   <td style="text-align:left;"> Second $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:12 </td>
   <td style="text-align:left;"> $SPY Fake news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:12 </td>
   <td style="text-align:left;"> $SPY FAKE FUD🐻🔫👽✌️🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:09 </td>
   <td style="text-align:left;"> $SPY EU open tonight will be nasty 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:08 </td>
   <td style="text-align:left;"> $SPY fud or real? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:07 </td>
   <td style="text-align:left;"> $SPY - UKRAINE&amp;#39;S FOREIGN MINISTER SAYS FIRE HAS ALREADY BROKE OUT. IF IT BLOWS UP, IT WILL BE 10 TIMES LARGER THAN CHORNOBYL! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:07 </td>
   <td style="text-align:left;"> $SPY Putin attacks nuclear plant not with nuclear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:06 </td>
   <td style="text-align:left;"> $SPY Russia attacking their nuclear power plant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:06 </td>
   <td style="text-align:left;"> $SPY  
 
SPY what a choppy day and week of trading. Fed and Russia/Ukraine war. It was tough, but I think things will rebound next week... unless we see some major event over the next few days. What are your thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:06 </td>
   <td style="text-align:left;"> $SPY dang covered 22 435 puts this morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:02 </td>
   <td style="text-align:left;"> $SPY bulls hoping for priced in😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:24:01 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:58 </td>
   <td style="text-align:left;"> $SPY alright Putin I’m sick of it by tomorrow you’ll be dead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:57 </td>
   <td style="text-align:left;"> $SPY 

If no nuclear explosion by premarket, this may open very GREEN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:56 </td>
   <td style="text-align:left;"> $SPY Yeah just become an Oligarc and invade stuff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:52 </td>
   <td style="text-align:left;"> $SPY futs recovering. Bears never learn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:50 </td>
   <td style="text-align:left;"> $SPY this isn’t Putin, it’s Zelensky attacking his own people. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:49 </td>
   <td style="text-align:left;"> $SPY 4hr🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:47 </td>
   <td style="text-align:left;"> $SPY my phone got hacked it says AH finished green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:46 </td>
   <td style="text-align:left;"> $SPY the move up will be much more violent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:45 </td>
   <td style="text-align:left;"> $SPY 

Save the drama for your mama.   There won&amp;#39;t be a nuclear Holocaust here ok? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:42 </td>
   <td style="text-align:left;"> $SPY I never thought I&amp;#39;d see the day where idiot shorts are wishing for the destruction of the planet just to make a few hundred on their puts. WOW what have we come to!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:37 </td>
   <td style="text-align:left;"> The s&amp;amp;p500 all time p/e chart $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:35 </td>
   <td style="text-align:left;"> $SPY losing faith in humanity this touches  250 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:35 </td>
   <td style="text-align:left;"> $SPY WWW3 won&amp;#39;t be til all nations rise against Israel... jus sayin.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $ES_F $NQ_F We&amp;#39;re certainly a long way from knowing exactly what is going on with the Ukrainian nuke plant reportedly under seige.  If there were a radioactive release, the fallout would initially head south and southeast in the prevailing wind field, both at the surface and roughly 1 mile up in the atmosphere (850 mb).  That would bring the immediate fallout initially over the Black Sea and toward the countries of Georgia and Azerbaijan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:33 </td>
   <td style="text-align:left;"> $SPY literally can&amp;#39;t stay down for more than 5 minutes. We&amp;#39;re so screwed. Biggest bubble in modern times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:33 </td>
   <td style="text-align:left;"> $SPY .55% rip in less than 5 minutes. Overreaction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:33 </td>
   <td style="text-align:left;"> $SPY Everyones bored time to go long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:30 </td>
   <td style="text-align:left;"> $SPY @ this point we need to take Putin out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:28 </td>
   <td style="text-align:left;"> $SPY that can’t be right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:27 </td>
   <td style="text-align:left;"> $SPY $IWM $XLF $QQQ  Gapping Down at the Open, Not filling the gap either throughout the day..just going down. It’s going down now. Volatile aggressive and fast. Don’t buy the fake dips along the way down unless your day trading. It’s going down prepare for a big sell off Friday. RIP to any overnight Call Holders You Will Wake up -50% on them. Good luck to tha Bears 🐻🤪🎊🎉🥳🍿🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:27 </td>
   <td style="text-align:left;"> $SPY no country in the right mind would cause a nuclear meltdown. It would hurt their own people as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:25 </td>
   <td style="text-align:left;"> $SPY We are good guys!!!. Firefighters have the fire under control 🚨🚨🚨🚨🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:24 </td>
   <td style="text-align:left;"> $SPY NUCLEAR BLAST GOING WELL ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:22 </td>
   <td style="text-align:left;"> $SPY Probably not happening on opex with a million puts held. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:21 </td>
   <td style="text-align:left;"> $SPY bearish sentiment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:18 </td>
   <td style="text-align:left;"> $SPY so when are they going to overthrow hitler. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:17 </td>
   <td style="text-align:left;"> $SPY Bulls trying to price in the largest nuclear plant in Europe being on fire 😐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:17 </td>
   <td style="text-align:left;"> $SPY Possible explosion priced in already. Opens green tomorrow. 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:16 </td>
   <td style="text-align:left;"> $SPY good night everyone. Popped my ambien. If nukes go off I&amp;#39;ll die peacefully. If not ill be awake at 4 am buying the fuck out of this dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:14 </td>
   <td style="text-align:left;"> $SPY lookslike $UVXY will win the hedge of the year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:13 </td>
   <td style="text-align:left;"> I will keep adding over the long haul $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:11 </td>
   <td style="text-align:left;"> $spy good job to the paper hands who panic sold just now on FUD. They will put out the fire and futures will be relatively flat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:10 </td>
   <td style="text-align:left;"> $SPY epic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:09 </td>
   <td style="text-align:left;"> $SPY 444 tomorrow. Over reaction to a nonevent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:09 </td>
   <td style="text-align:left;"> $NQ_F nice. Expect a bounce at 13700-1307

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:08 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ I think I want to be an oligarch when I grow up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:07 </td>
   <td style="text-align:left;"> $SPY ok that was fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:05 </td>
   <td style="text-align:left;"> $SPY what happened??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:02 </td>
   <td style="text-align:left;"> $SPY payday tomorrow! Sadly I’m not the one getting paid.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:01 </td>
   <td style="text-align:left;"> $SPY Bears are so dramatic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:00 </td>
   <td style="text-align:left;"> $SPY It doesn&amp;#39;t say which part of the power plant is on fire. A fire in a non-critical part could easily lead to a non event. Humans like to assume the worst, for all you know news coukd break that it went out and all that after market fear evaporates. Just saying 👊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:00 </td>
   <td style="text-align:left;"> $SPY we might have bigger things on our mind tomorrow than stupid stock market…..my fate in humanity is being tested like never before… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:23:00 </td>
   <td style="text-align:left;"> $SPY if this plant explodes and spy rips because of it. I’m calling Thanks to snap us out.  We done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:59 </td>
   <td style="text-align:left;"> $SPY Everyday something worse happens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:50 </td>
   <td style="text-align:left;"> $SPY spy went off a cliff a hour ago. Who bought it back up? Rigged </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:49 </td>
   <td style="text-align:left;"> $SPY $SPX #WS_F
INCREASED RADIATION LEVELS HAVE BEEN RECORDED AT THE ZAPORIZHZHIA NUCLEAR POWER STATION IN UKRAINE - AP.
https://www.youtube.com/embed/fYUT36YGOh8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:46 </td>
   <td style="text-align:left;"> $SPY green by open, as usual. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:40 </td>
   <td style="text-align:left;"> $SPY putin is insulted that all Biden can come up with is sanctions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:36 </td>
   <td style="text-align:left;"> $SPY if there’s a nuclear war, does the big guy still get 10%? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:35 </td>
   <td style="text-align:left;"> $SPY bulls so desperate rn hopefully there lies are true, don’t need a nuclear disaster on our hands </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:33 </td>
   <td style="text-align:left;"> $SPY calls on metaverse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:32 </td>
   <td style="text-align:left;"> $SPY Putin is going to do something so stupid that even china and North Korea will eliminate him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:31 </td>
   <td style="text-align:left;"> $SPY Readings are fine sofar only 3.6 roentgen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:29 </td>
   <td style="text-align:left;"> $SPY Shocked at how fast modern humans destroyed the world.
pride, greed, wrath, envy, lust, gluttony, sloth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:28 </td>
   <td style="text-align:left;"> $SPY can someone confirm which is right?
1. ST is showing this closed around $436
2. My TDA showing the same however 
3. Chart in same TDA is showing this closed at $429.20 in AH trading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:27 </td>
   <td style="text-align:left;"> $SPY futes already recovering ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:25 </td>
   <td style="text-align:left;"> $SPY why is stocktwits showing 436? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:24 </td>
   <td style="text-align:left;"> $SPY No circuit breaker in Afterhours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:24 </td>
   <td style="text-align:left;"> $SPY gonna have to grab some calls. I think.    I think.  Gonna sleep on it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:22 </td>
   <td style="text-align:left;"> $SPY do we need keep masks on because of nuclear radiation 😷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:21 </td>
   <td style="text-align:left;"> $SPY futes going back up.  nuclear explosion must be priced in.  how silly of me not to know this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:19 </td>
   <td style="text-align:left;"> $SPY what a show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:19 </td>
   <td style="text-align:left;"> $SPY Hmm oh well, tomorrow is pay day, when we get margin calls it will be all good, am i right bullz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:12 </td>
   <td style="text-align:left;"> $SPY $QQQ The Russian troops are crazy, guess they want to get exposure to radiation and get cancer 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:11 </td>
   <td style="text-align:left;"> $SPY If this drop holds though, I&amp;#39;m already eyeing some interesting plays for tomorrow

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:09 </td>
   <td style="text-align:left;"> $SPY nuke wouldn’t stop this ticker </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:09 </td>
   <td style="text-align:left;"> $SPY 

Sleepy Joe says that all fires in Iran must be out out immediately </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:06 </td>
   <td style="text-align:left;"> $SPY No concerning radiation. I don&amp;#39;t see any benefit of destroying a nuclear plant. doesn&amp;#39;t make any sense. I see a lot of fake shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:22:04 </td>
   <td style="text-align:left;"> $SPY over reaction - small fire in admin building at plant, nothing gonna explode relax. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:59 </td>
   <td style="text-align:left;"> $SPY FUTES recovery. It was can burners and dudes warming their hands. Green in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:58 </td>
   <td style="text-align:left;"> $SPY I am selling everything I have.  World is coming to an end 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:57 </td>
   <td style="text-align:left;"> $SPY As someone who plays RTS’s from time to time. It is a good strategy to take out the enemy’s power supply. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:53 </td>
   <td style="text-align:left;"> $SPY THey are buying the dip in futes. Up .34% in a matter of seconds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:52 </td>
   <td style="text-align:left;"> $SPY Trade based in Fud is not good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:52 </td>
   <td style="text-align:left;"> $SPY bulls trying to kink shame my puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:48 </td>
   <td style="text-align:left;"> $SPY moooood </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:45 </td>
   <td style="text-align:left;"> $SPY gap already $430.00 to $430.11 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:42 </td>
   <td style="text-align:left;"> $SPY so warlier i posted es and oil was both at 30 min crosses and a big price action was coming. One up through and one dump. The cross is golden. Its all glory or burnt toast though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:41 </td>
   <td style="text-align:left;"> $SPY $lmt $uvxy if putin has any brains he will call off the attacks.  
He&amp;#39;ll have no troops left if they all get wiped out from a nuclear meltdown.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:41 </td>
   <td style="text-align:left;"> US $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:41 </td>
   <td style="text-align:left;"> $SPY $QQQ russia on crack let the firefighters put the fire out holy shit! Learn from your mistakes not make bigger ones omfg $DKNG $NVDA $ZSAN 

Citizens of ukraine should evacuate far from this site - so horrific to see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:37 </td>
   <td style="text-align:left;"> $SPY $QQQ 
NATO about to step in. Can’t have something 10X worse than Chernobyl and just sit around and let it happen. Shits about to get cra cra. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:35 </td>
   <td style="text-align:left;"> $QQQ $SPY I thought nuclear explosions were priced in? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

https://twitter.com/DmytroKuleba/status/1499543775240196099?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1499543775240196099%7Ctwgr%5E%7Ctwcon%5Es1_c10&amp;amp;ref_url=https%3A%2F%2Fsg.news.yahoo.com%2Frussian-troops-shell-ukrainian-nuclear-plant-010757408.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:30 </td>
   <td style="text-align:left;"> Breaking $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:27 </td>
   <td style="text-align:left;"> $SPY Putin has gone mad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:26 </td>
   <td style="text-align:left;"> $SPY fuck now I miss Covid times 
Staying at home watching Fauci </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:26 </td>
   <td style="text-align:left;"> $SPY .:: some believe … Russian still mad about Reagan jokes about off mic comments!?  And they want their curtains back; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:21 </td>
   <td style="text-align:left;"> Background $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:20 </td>
   <td style="text-align:left;"> $SPY just a heads up guys the feds won’t be pumping any money into the markets tomorrow so don’t expect any upwards movement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:20 </td>
   <td style="text-align:left;"> $SPY we are battling a rate hike and potential WWIII .  Only 1-2 years after covid.  Markets are strong AF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:18 </td>
   <td style="text-align:left;"> $SPY new world order war . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:17 </td>
   <td style="text-align:left;"> $SPY When President Biden deploys the Dominion voting machines to Russia... that&amp;#39;s when the sh*t really hits the fan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:13 </td>
   <td style="text-align:left;"> $SPY $NQ_F should have already reversed up hard... but the fishy algo,  once fishy seller is gone, then price should be popping a few percent ; ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:13 </td>
   <td style="text-align:left;"> $SPY  
 
Whoda thunk electric 6 could have foretold nuclear bears on the SPY board, SPY board, SPY board 
 
 
 
https://youtu.be/-XNFokmDKrE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:06 </td>
   <td style="text-align:left;"> $SPY anyone cheering because of this is a disgusting human </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:06 </td>
   <td style="text-align:left;"> $SPY actually today it was at 440 major resistance level, so no wonder it happily goes down now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:21:02 </td>
   <td style="text-align:left;"> $SPY I might just throw my money in gold cuz man…… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:59 </td>
   <td style="text-align:left;"> $COST you down with 0dte? yeah you know me! Lol, good night everyone $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:58 </td>
   <td style="text-align:left;"> $SPY they r bombing a nuclear power station?  ok now it&amp;#39;s time to send... $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:58 </td>
   <td style="text-align:left;"> $SPY 99 problems holding a call overnight ain&amp;#39;t one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:56 </td>
   <td style="text-align:left;"> $SPY live cam of the nuclear plant in Ukrainian  https://m.youtube.com/watch?v=OGKoEHK19nY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:54 </td>
   <td style="text-align:left;"> $SPY I don’t invest for tomorrow, I invest for ten years from today. I hedge as needed. Lots of times my hedges lose money and that is ok. If America and Russia are a glass wasteland in 10 years and if I’m dead othat’s fine too but I won’t be broke unless literally everyone is broke and we get taken back 2000 years. But this board is tripping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:51 </td>
   <td style="text-align:left;"> $SPY 380 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:48 </td>
   <td style="text-align:left;"> $SPY Fairly irresponsible reporting by the media there. Panic inducers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:43 </td>
   <td style="text-align:left;"> $SPY  You think RUSKIES are dumb enough to expose themselves to radiation. let alone render a large portion of their *potential conquest* &amp;gt;&amp;gt;UNINHABITABLE&amp;lt;&amp;lt;  ???   NO WAY this is another *CHERNOBYL* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:41 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Tomorrow: Hazardous waste ohhh fuhhh
Monday: debt ceiling oh lawd
Wednesday: interest rates shi cuhh
Friday: Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:41 </td>
   <td style="text-align:left;"> $SPY I am done, I am moving to Somalia 😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:41 </td>
   <td style="text-align:left;"> $SPY 
.
Bears hoping they can&amp;#39;t put out a fire.    Hmmm. Unlikely. Sorry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:38 </td>
   <td style="text-align:left;"> $SPY 2020 sucked ass. 2022: Hold my beer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:34 </td>
   <td style="text-align:left;"> $DWAC $SPY $BTC.X   Careful listening to these fake news MF&amp;#39;rs... They&amp;#39;ve been doing it for decades!!   Until i see it blow up i don&amp;#39;t believe a word they say... and Even then i question it, LOL  https://youtu.be/6F6g5WMoZ3Q?t=89 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:34 </td>
   <td style="text-align:left;"> $QQQ $SPY great, gonna be up 2% with being this red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:32 </td>
   <td style="text-align:left;"> $SPY if the Nuke plant is hit and there is a meltdown nato goes in by Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:31 </td>
   <td style="text-align:left;"> $SPY Honest opinions only please... Is this news big enough to tank the market tomorrow? Like 410-420? Idk. What if they put out the fire lol. And nothing happens? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:29 </td>
   <td style="text-align:left;"> $SPY - Ukraine says Russia &amp;#39;shelling&amp;#39; Europe&amp;#39;s largest nuclear power plant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:26 </td>
   <td style="text-align:left;"> $SPY btw futures do mean a lot of you analyze the price action. I saw this coming. Many did. But sucks for the PUT holders that can’t cash out now, because once that gap is closed it will run to 446. Then either keep going or come back down again. Depends. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:26 </td>
   <td style="text-align:left;"> $SPY do I eat all of the acid in my freezer tonight or what? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:25 </td>
   <td style="text-align:left;"> $SPY Yesterday: &amp;quot;We need to switch to nuclear so we don&amp;#39;t have to rely on Russian gas. Nuclear energy is safe!&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:22 </td>
   <td style="text-align:left;"> $SPY was the fed right on transitory inflation? And you think they will be right on only a .25 rate hike? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:20 </td>
   <td style="text-align:left;"> $SPY shit futures traders doing their thing. We will open below 410 tomorrow. Maybe 380. Not a simple headline go overcome via technical. Vix 35 on open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:20 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s time like this where you uninstall Twitter and Stocktwits. Nothing beneficial comes out of reading all of this nonstop fear mongering </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:19 </td>
   <td style="text-align:left;"> $SPY puts be bankin tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:19 </td>
   <td style="text-align:left;"> $SPY 

RECESSION 2022 for sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:12 </td>
   <td style="text-align:left;"> $SPY i was only bullish cuz i thought the market would manipulate if i did puts 🥺😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:12 </td>
   <td style="text-align:left;"> $SPY said it before, I’ll say it again. I love trading futures! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:05 </td>
   <td style="text-align:left;"> $SPY hey MOO did you buy that dip? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:05 </td>
   <td style="text-align:left;"> $SPY the internet has created a lot of sick spineless people hiding behind a keyboard. Be glad there are real men and women able to handle true  conflict. Some of you need to check yourself.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:04 </td>
   <td style="text-align:left;"> $SPY 
If Wall Street would throw that pocket change over it would be over in 24 hrs.Old West Style ☠️☠️☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:20:01 </td>
   <td style="text-align:left;"> $SPY all I wanna know is when Biden pullin up cuz this radiation don’t need to be leaking NOWHERE…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:57 </td>
   <td style="text-align:left;"> $SPY Wouldn&amp;#39;t you think they would have shut down the reactors days ago?  Certainly as Russian troops moved closer?  You know, considering the country was being invaded and many installations were being bombed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:57 </td>
   <td style="text-align:left;"> $ES_F my position earlier today. Yes I’m short futures. $SPY $SPX 🤑💰📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:55 </td>
   <td style="text-align:left;"> $SPY unsourced* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:54 </td>
   <td style="text-align:left;"> $SPY just so happened 80% of my $ is in puts overnight. Like a chess game. Surely I&amp;#39;ll take profits but I&amp;#39;ll still have 20% minimum in puts over weekend and the rest cash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:50 </td>
   <td style="text-align:left;"> $SPY no alcohol for me tonight. WE BE ALL NIGHT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:49 </td>
   <td style="text-align:left;"> $SPY $QQQ HBO’s Chernobyl season 2 is something I’d rather not see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:45 </td>
   <td style="text-align:left;"> $SPY Powell: OMG a nuclear plant under attack in Ukraine! Activate the printers!  My retirement is at stake!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:43 </td>
   <td style="text-align:left;"> $SPY the plant will more than likely be fine. But the potential unseen and real consequences will rattle the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:43 </td>
   <td style="text-align:left;"> $SPY putin will wiped like guddafi if he hit nuclear plant!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:42 </td>
   <td style="text-align:left;"> $SPY unsorted like a mf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:42 </td>
   <td style="text-align:left;"> $SPY Putin nuke them yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:41 </td>
   <td style="text-align:left;"> $SPY nikkei getting hammered over the news…maybe we get a bounce for the jobs report and then sell off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:40 </td>
   <td style="text-align:left;"> $SPY lol. Spy broke Stocktwits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:38 </td>
   <td style="text-align:left;"> $SPY $QQQ Putin is playing around with nuclear, this guy has gone crazy and I think it is time for Europe and the US to send troops there to beat the Russian troops up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:37 </td>
   <td style="text-align:left;"> $SPY look at Nikkei futures they know what nuke leak is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:36 </td>
   <td style="text-align:left;"> $SPY uncertainty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:33 </td>
   <td style="text-align:left;"> $SPY better get some cash cyber attacks are next . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:31 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:29 </td>
   <td style="text-align:left;"> $SPY We are already in the war unfortunately 
https://www.zerohedge.com/geopolitical/germany-sends-2700-anti-aircraft-missiles-ukraine-despite-moscows-warning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:27 </td>
   <td style="text-align:left;"> $SPY I hope the market opens tomorrow, a few puts expiring </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:27 </td>
   <td style="text-align:left;"> $SPY like even moo would buy this dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:22 </td>
   <td style="text-align:left;"> $SPY prevailing winds are back towards Georgia. Any potential fallout, at this moment, wouldnt impact NATO countries- Turkey is the wildcard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:20 </td>
   <td style="text-align:left;"> $SPY most likely you panic sold. Putin is not a mad man like the media tries to portray him. He is not blowing up a nuclear plant which is right next to Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:19 </td>
   <td style="text-align:left;"> $SPY so what if it explodes overnight? Circuit breaker? 100,000 dead? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X The media in the US and EU is obnoxious w their propaganda. If you read these articles or watched the news over the past few days you would think Russia is demoralized, defeated, that the Ukrainians have them on the run. That’s all bullshit. These idiots have no idea what Putin’s long-game looks like. In reality nothing has changed since a week ago. Ukraine will fall, only it will take longer, cause more loss of life as well as economic damage than initially expected. All the media has accomplished is to make Putin more vicious. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:18 </td>
   <td style="text-align:left;"> $SPY remember when mean tweets were the biggest concerns, instead of mushroom clouds? Pepperidge Farms remembers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:13 </td>
   <td style="text-align:left;"> $SPY let’s c if this holds.  People r greedy buying basement prices </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:10 </td>
   <td style="text-align:left;"> $SPY FED balance sheet 9 trillion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:07 </td>
   <td style="text-align:left;"> $SPY strippers and stripers, i kind of would love that fishing trip. Maybe that is my new business. Franchise it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:06 </td>
   <td style="text-align:left;"> $SPY reactor not on fire administration building…but Russians will probably just shut down everyone’s power in the middle of winter 🥶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:01 </td>
   <td style="text-align:left;"> $SPY reactors have a kill switch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:19:00 </td>
   <td style="text-align:left;"> $SPY damn that’s how fucked up the world is. People here celebrating the explosion . Shit!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM  
Russian army ‘firing from all sides’ at blazing nuclear plant. 
Experts: Nuclear plant should be safe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:53 </td>
   <td style="text-align:left;"> $SPY how can anyone be bullish in this kind of market, so much safer to hold puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:50 </td>
   <td style="text-align:left;"> $SPY where will the markets be in 20 years? Probably up, so just hold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:48 </td>
   <td style="text-align:left;"> $SPY here we go double bottom printing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:47 </td>
   <td style="text-align:left;"> $QQQ $SPY  Definition of cold war
wolf growling looking own reflection in swamp. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:46 </td>
   <td style="text-align:left;"> $SPY this shit always happens after i go all in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:42 </td>
   <td style="text-align:left;"> $SPY no lie this crash might be bigger that 08’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:42 </td>
   <td style="text-align:left;"> $SPY seems like ukrainian army is hiding in every hole: nuclear plant, school or residential area. that explains such issues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:41 </td>
   <td style="text-align:left;"> $SPY In an alternate reality the US lost the cold war and Uncle JoJo is bombing Texas to rebuild the empire. I&amp;#39;m going to sell it to Amazon this is my intellectual property. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:35 </td>
   <td style="text-align:left;"> $SPY pos holding unreal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:34 </td>
   <td style="text-align:left;"> $SPY so bizarre.   That thing blows up. Basically if you want to talk about markets.   Forget it.   Crash beyond ..  cause of the other countries not far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:33 </td>
   <td style="text-align:left;"> $SPY please slap a liberal today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:32 </td>
   <td style="text-align:left;"> $SPY $441- $429 how is that bullish? $426 better hold tomorrow… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:32 </td>
   <td style="text-align:left;"> $SPY idk though

Honestly I think we retrace most of this drop by morning

Probably a close-to-doji candle tomorrow

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:28 </td>
   <td style="text-align:left;"> $SPY close puts, buy calls on the open if this holds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:27 </td>
   <td style="text-align:left;"> $SPY they let the fire fighters in JUST NOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:26 </td>
   <td style="text-align:left;"> $SPY GG bulls 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:25 </td>
   <td style="text-align:left;"> $XOS TA:  currently stuck between the SMA20 and SMA50, trading below the $SPY on the 6 month daily chart.  Good news is on the 3M we are getting SPY support and are holding retracement between 2.23 and 2.42.  If we can break and hold 2.42 our next resistance is at 2.55. I expect we filled the gap at 2.28 today and since we had some nice volume at close I expect tomorrow to retest 2.42 and hopefully we see a clean break so we can move north to that 2.55 mark.  RSI near the oversold region on the 5 day as well so I’m bullish for the next couple trading days.  Good time to load up and fingers crossed we get some help from the SPY to do that tomorrow.  All IMHO of course.  GLTA! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:21 </td>
   <td style="text-align:left;"> $SPY Literally not my war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:21 </td>
   <td style="text-align:left;"> $SPY fyi, nuclear radiation spreading across Europe is a bit catastrophic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:20 </td>
   <td style="text-align:left;"> $QQQ $SPY sad truth. This is a war that Ukraine can never win. Either surrender n salvage what’s left or get completely destroyed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:19 </td>
   <td style="text-align:left;"> $SPY  let&amp;#39;s all pray that this is not a nuclear leak or reactor on fire. people don&amp;#39;t seem to understand what would happen if the reactor core is exposed: we are all fukd. all of us. not only will radiation contaminate Europe and lead to mutations, birth defects and loss of life, but the land will become uninhabitable... ww3 could ensue. let&amp;#39;s not wish for nukes and these types of disasters. once you are dead, who cares about your trading account. money comes and goes, but you only live once. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:14 </td>
   <td style="text-align:left;"> $SPY bulls rn: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:13 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ $IWM - And then when the Dow closes up 800 points they’ll say “investors shake off nuclear fall out and death”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:11 </td>
   <td style="text-align:left;"> $SPY stop people good lord !!  Why half you lose your money . 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:10 </td>
   <td style="text-align:left;"> $BTC.X $DIA $SPY https://twitter.com/sentdefender/status/1499553300089298945?s=21 
I&amp;#39;m not sure how good the source is but this is said </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:07 </td>
   <td style="text-align:left;"> $SPY 

So……have you liberals seen yet what an incompetent, idiotic, senile old fool you voted into office?  Do you all like going to war? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:07 </td>
   <td style="text-align:left;"> $SPY

Yoo wow wtf is going on, the market is sooooo fucked up lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:04 </td>
   <td style="text-align:left;"> $SPY not touching options for a while. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:03 </td>
   <td style="text-align:left;"> $SPY Dont get frightened bull buy these calls imma sell you tomorrow on the dip. You are definitely not gonna be catching falling knives. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:18:01 </td>
   <td style="text-align:left;"> $SPY lol I was about to say……AINT NO WAY 

But Stocktwits with the little pump fake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:59 </td>
   <td style="text-align:left;"> $SPY Japan down 3% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:59 </td>
   <td style="text-align:left;"> $SPY what did I tell you? Nearly every move with deadly accuracy and even alerted u before it ran up. I hope everyone else u follow sees each move just as clearly so u can bank with precision. “Russian Forces shelling Europe’s largest nuclear facility”  is the news that dropped this. If u listened at 477 u bought inverse as I told u it would go to 419 which it hit exactly. If u listened after that u bought spy as I told u it would head up and if u listened when I told u it would then hit 380-412 you banked big as it hit 408. I then specifically told u it was time to buy bullish spy and it ran up where i quarterbacked every move and explained why and which situations to look for. Today I posted this if u read the snapshot below and I even reiterated at end of day not to fall for buying calls yet and to add big to $UVXY and inverse on any spy pop. I do this for free folks if u are subscribed for free to my alerts and listening you should be in position yet again to bank big✊🏼👇🏼👇🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:56 </td>
   <td style="text-align:left;"> $QQQ $SPY price will continue to head lower.

SPY 410.65

QQQ 318.26 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:55 </td>
   <td style="text-align:left;"> $SPY this was down like 9 now up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:54 </td>
   <td style="text-align:left;"> $SPY https://twitter.com/zerohedge/status/1499549687656980482?s=20&amp;amp;t=84xCUCGHC1zwFpcsenkDfg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:53 </td>
   <td style="text-align:left;"> $SPY let’s see which euro country gets involved first in this war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:52 </td>
   <td style="text-align:left;"> $SPY yo stocktwits chill 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:50 </td>
   <td style="text-align:left;"> $SPY so index&amp;#39;s and blue chips stocks tank after hours but growth stocks barely drop lol rightttttt, false alarm people. Index&amp;#39;s will slowly go back up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:49 </td>
   <td style="text-align:left;"> $SPY take out Putin now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:45 </td>
   <td style="text-align:left;"> $SPY didn&amp;#39;t tom lee say the bottom was in ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:43 </td>
   <td style="text-align:left;"> $SPY waking up at 4 am to place my buys. Time to pop an ambien so I can actually wake up in time for it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:42 </td>
   <td style="text-align:left;"> $SPY ahh 436.39… the number I saw when I looked when about to walk to the car… 15 minutes later at a red light I looked and it was 430 and not done yet lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:42 </td>
   <td style="text-align:left;"> $SPY $NQ_F some fishy algo came in... that&amp;#39;s why. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:41 </td>
   <td style="text-align:left;"> $SPY bulls are f’d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:37 </td>
   <td style="text-align:left;"> $SPY $420 tomorrow at open please 🙏🙏🙏🩸🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:37 </td>
   <td style="text-align:left;"> $SPY Don’t worry America, these idiots are in charge . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:36 </td>
   <td style="text-align:left;"> $BTC.X if you can accept a 99% loss in a single day when the world bans bitcoin keep buying.  They are going to outlaw Russias last source of income $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:36 </td>
   <td style="text-align:left;"> $SPY  Holy smokes I&amp;#39;m glad I loaded up on puts At 438 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:33 </td>
   <td style="text-align:left;"> $SPY holy shit is this thread crowded🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Europe&amp;#39;s biggest nuclear plant shelled

https://www.9news.com.au/world/russia-ukraine-war-crisis-live-updates-latest-breaking-news-headlines-march-4-2022/0d8f5035-2fda-448e-9613-1c37876d11d9 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:30 </td>
   <td style="text-align:left;"> $SPY btw this is how u get scammed by ppl other than the clown crew , stock twits loves resetting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:27 </td>
   <td style="text-align:left;"> $SPY $uvxy yoooo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:26 </td>
   <td style="text-align:left;"> $SPY who bought wheat contracts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:26 </td>
   <td style="text-align:left;"> $SPY ci vediamo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:22 </td>
   <td style="text-align:left;"> $SPY Some puts will be worthless at open. Especially 430 and 435s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:16 </td>
   <td style="text-align:left;"> $SPY 
I’ll by dinner </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:15 </td>
   <td style="text-align:left;"> $SPY Can I still plan my summer cruise to Siberia and Kiev?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-04 09:17:15 </td>
   <td style="text-align:left;"> $SPY lol stocktwits pumped the price to reduce panic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:26:22 </td>
   <td style="text-align:left;"> $SPY $QQQ They are pushing to 4330 then it will flush again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:26:11 </td>
   <td style="text-align:left;"> $QQQ my lotto calls are toasted tomorrow 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:26:09 </td>
   <td style="text-align:left;"> $QQQ rest of the world is impotent as Russia destroys Ukraine. If only Ukraine had oil or gas, we&amp;#39;d be there in a heartbeat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:26:06 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY 
The everything dump cometh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:25:48 </td>
   <td style="text-align:left;"> $QQQ $SPY hmm... seems like no one whould be able to stop Russia even if they shoot at the nuclear plant. Lol what a joke. It&amp;#39;s like the whole world is imposing sanctions to Russia and praying so hard they will stop by themselves. Serious? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:25:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DJIA $XLE

🚨🚨🚨PANIC PANIC SELL ALL RISK ASSETS 😂

BREAKING: Firefighters gain access to nuclear power plant in Ukraine, where an administrative building is on fire - ZN

❗️According to Andrey Tuz, spokesman of the press service of the nuclear power plant, there is no threat of radiation spread.

Seriously what purpose does it serve Russia to cause an explosion 10x bigger than chernobyl and cause an absolute disaster! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:25:25 </td>
   <td style="text-align:left;"> $QQQ wyd happened?? Lmaoo 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:25:21 </td>
   <td style="text-align:left;"> $QQQ $SPY.X $BTC.X 
We are not talking about money anymore.
I don’t feel safe living in Europe.

My mother asked me to go to her house to sleep. 

This many is crazy.

Fuck war 

Buy your puts assholes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:25:18 </td>
   <td style="text-align:left;"> $QQQ Relax folks, there is not going to be a nuclear meltdown. Nuclear power plants are built to withstand way more than a fire. You could crash a plane into one and it wouldn&amp;#39;t cause a meltdown, many many fail safes in place. Chernobyl was a way different scenario. Moreover firefighters are able to combat fire now. The fire is contained. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:25:07 </td>
   <td style="text-align:left;"> $QQQ we should go to war with Russia because this will affect all of our lives </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:24:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA and it’s disgusting that the US/EU and media should lead Ukrainians  to believe that fighting tanks w Molotov cocktails is some kind of strategy that will end well. It’s the height of irresponsibility. If Biden and the rest of them weren’t going to send troops, we should have pressed Zelensky to surrender immediately. Be realistic. Don’t tell them to fight tanks w these pathetic weapons and get themselves killed. I’m disgusted. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:24:01 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:23:59 </td>
   <td style="text-align:left;"> $QQQ notice Volume got higher when it was lower and stabilized - that is higher volume BUYING fear. Lower volume tanked it. Classic tactics to move the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:23:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $ES_F $NQ_F We&amp;#39;re certainly a long way from knowing exactly what is going on with the Ukrainian nuke plant reportedly under seige.  If there were a radioactive release, the fallout would initially head south and southeast in the prevailing wind field, both at the surface and roughly 1 mile up in the atmosphere (850 mb).  That would bring the immediate fallout initially over the Black Sea and toward the countries of Georgia and Azerbaijan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:23:27 </td>
   <td style="text-align:left;"> $SPY $IWM $XLF $QQQ  Gapping Down at the Open, Not filling the gap either throughout the day..just going down. It’s going down now. Volatile aggressive and fast. Don’t buy the fake dips along the way down unless your day trading. It’s going down prepare for a big sell off Friday. RIP to any overnight Call Holders You Will Wake up -50% on them. Good luck to tha Bears 🐻🤪🎊🎉🥳🍿🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:23:09 </td>
   <td style="text-align:left;"> $NQ_F nice. Expect a bounce at 13700-1307

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:23:08 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ I think I want to be an oligarch when I grow up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:22:48 </td>
   <td style="text-align:left;"> $QQQ why is everyone talking like the war is the reason the market is down? Don&amp;#39;t get it twisted.  After two years of the stock market nearly doubling, it&amp;#39;s cooling off because it has to.  People love to put a speculative narrative on why stocks move a certain way.  Yeah, it could be a catalyst, but stocks were bound to go down like this long before recent events of Ukraine and Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:22:12 </td>
   <td style="text-align:left;"> $SPY $QQQ The Russian troops are crazy, guess they want to get exposure to radiation and get cancer 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:22:10 </td>
   <td style="text-align:left;"> $QQQ if you know much about modern nuclear fired generating plants you&amp;#39;d realize that a repeat of chernobyl level issue is gonna take a lot more than a fire..

the soviets built cheap shitty reactors, and didn&amp;#39;t train the operators well.

please relax with the fud </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:22:05 </td>
   <td style="text-align:left;"> $QQQ I understood the assignment! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:21:41 </td>
   <td style="text-align:left;"> $SPY $QQQ russia on crack let the firefighters put the fire out holy shit! Learn from your mistakes not make bigger ones omfg $DKNG $NVDA $ZSAN 

Citizens of ukraine should evacuate far from this site - so horrific to see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:21:40 </td>
   <td style="text-align:left;"> $QQQ now that everyone sold, it moves back up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:21:37 </td>
   <td style="text-align:left;"> $SPY $QQQ 
NATO about to step in. Can’t have something 10X worse than Chernobyl and just sit around and let it happen. Shits about to get cra cra. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:21:35 </td>
   <td style="text-align:left;"> $QQQ $SPY I thought nuclear explosions were priced in? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:21:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

https://twitter.com/DmytroKuleba/status/1499543775240196099?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1499543775240196099%7Ctwgr%5E%7Ctwcon%5Es1_c10&amp;amp;ref_url=https%3A%2F%2Fsg.news.yahoo.com%2Frussian-troops-shell-ukrainian-nuclear-plant-010757408.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:21:03 </td>
   <td style="text-align:left;"> $QQQ 5x your money with my call outs 👍😁💵❤️ $XAU.CA $CLF 👍 $FB 👍 $GILD 👍 https://youtu.be/XEJvGiNMkHQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:21:01 </td>
   <td style="text-align:left;"> $QQQ God needs help humans to get ride of Putin….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:20:41 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Tomorrow: Hazardous waste ohhh fuhhh
Monday: debt ceiling oh lawd
Wednesday: interest rates shi cuhh
Friday: Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:20:39 </td>
   <td style="text-align:left;"> $QQQ https://www.youtube.com/watch?v=5P6eidg59ek </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:20:34 </td>
   <td style="text-align:left;"> $QQQ $SPY great, gonna be up 2% with being this red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:19:49 </td>
   <td style="text-align:left;"> $SPY $QQQ HBO’s Chernobyl season 2 is something I’d rather not see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:19:38 </td>
   <td style="text-align:left;"> $SPY $QQQ Putin is playing around with nuclear, this guy has gone crazy and I think it is time for Europe and the US to send troops there to beat the Russian troops up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:19:25 </td>
   <td style="text-align:left;"> $QQQ Stock market crash 3/4/22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:19:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X The media in the US and EU is obnoxious w their propaganda. If you read these articles or watched the news over the past few days you would think Russia is demoralized, defeated, that the Ukrainians have them on the run. That’s all bullshit. These idiots have no idea what Putin’s long-game looks like. In reality nothing has changed since a week ago. Ukraine will fall, only it will take longer, cause more loss of life as well as economic damage than initially expected. All the media has accomplished is to make Putin more vicious. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:19:13 </td>
   <td style="text-align:left;"> $QQQ So the market just fucking crashed!!??!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:18:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM  
Russian army ‘firing from all sides’ at blazing nuclear plant. 
Experts: Nuclear plant should be safe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:18:47 </td>
   <td style="text-align:left;"> $QQQ $SPY  Definition of cold war
wolf growling looking own reflection in swamp. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:18:20 </td>
   <td style="text-align:left;"> $QQQ $SPY sad truth. This is a war that Ukraine can never win. Either surrender n salvage what’s left or get completely destroyed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:18:20 </td>
   <td style="text-align:left;"> $QQQ 10% green tomorrow most likely now 😮‍💨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:18:13 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ $IWM - And then when the Dow closes up 800 points they’ll say “investors shake off nuclear fall out and death”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:17:56 </td>
   <td style="text-align:left;"> $QQQ $SPY price will continue to head lower.

SPY 410.65

QQQ 318.26 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:17:55 </td>
   <td style="text-align:left;"> $QQQ /NQ 13,600 bring it! Ready to buy there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:17:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Europe&amp;#39;s biggest nuclear plant shelled

https://www.9news.com.au/world/russia-ukraine-war-crisis-live-updates-latest-breaking-news-headlines-march-4-2022/0d8f5035-2fda-448e-9613-1c37876d11d9 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:17:28 </td>
   <td style="text-align:left;"> $QQQ fuck.... everyone’s selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:17:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $NQ_F closed longs off the bottom... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:16:59 </td>
   <td style="text-align:left;"> $QQQ nuclear disaster = recession = fed reinstates QE = bullish! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:16:55 </td>
   <td style="text-align:left;"> $QQQ if I can’t have it, nobody can
-Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:15:59 </td>
   <td style="text-align:left;"> $QQQ $SPY Will Russia not want Ukraine if there is a nuclear disaster there? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:15:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $FDX $NKE Beautiful! Please share! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:15:33 </td>
   <td style="text-align:left;"> $QQQ wild prediction...
 Putin ends this to save face... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:15:05 </td>
   <td style="text-align:left;"> $QQQ disasters and war is still good for american tech, buy the fear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:15:05 </td>
   <td style="text-align:left;"> $TSLA you idiots make it too easy. Welcome to the new market

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:14:56 </td>
   <td style="text-align:left;"> $QQQ $SPY Putin needs to stop, if that powerplant explodes its mutual destruction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:14:54 </td>
   <td style="text-align:left;"> $QQQ fu•• me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:14:44 </td>
   <td style="text-align:left;"> $QQQ $SPY well, seems like it&amp;#39;s not bears vs bulls anymore... 

https://twitter.com/Worldsource24/status/1499551067146579970?t=bB9zCXSlV9K705XqVao5dw&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:14:34 </td>
   <td style="text-align:left;"> Russia-Ukraine latest news: Warning of ‘Chernobyl times 10’ disaster as nuclear plant ‘under attack’ | The Independent

$SPY $QQQ $XLF  https://www.independent.co.uk/news/world/europe/russia-ukraine-news-putin-war-b2028080.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:14:32 </td>
   <td style="text-align:left;"> High levels of radiation are being detected at the Zaporizhia nuclear plant $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:14:24 </td>
   <td style="text-align:left;"> $SPY $QQQ are these going to rally 5% tomorrow when the fire gets put out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:14:21 </td>
   <td style="text-align:left;"> $QQQ this dude Putin gotta go you can tell he doesn’t care about shit anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:14:18 </td>
   <td style="text-align:left;"> $ES $SPY $QQQ Supply dump coming in hot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:14:06 </td>
   <td style="text-align:left;"> $QQQ Fuq Putin costing me $$$ big time on QQQ calls fuqqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:13:47 </td>
   <td style="text-align:left;"> $QQQ $spy $btc.x Putin’s repulsive crimes continue. Fuck everyone who apologize for Putin and Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:13:47 </td>
   <td style="text-align:left;"> $QQQ fuck it I say nato fucks em up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:12:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY You do understand that the largest plant in Europe built with the help of Russia was designed to take a little more damage than AK rounds and mortars can do right?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:12:30 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ how bad is tomorrow going to be? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:12:12 </td>
   <td style="text-align:left;"> $QQQ the chart will turn bullish again bulls. No worries.  Just have to wait on the date it’s programed for that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:12:06 </td>
   <td style="text-align:left;"> $QQQ the market is going wild </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:11:19 </td>
   <td style="text-align:left;"> $QQQ Who the fuck attacks a nuclear power plant ? What an idiot does that ?Putin is fucking delusional. I stand again on the fund raise for his head in BTC . If we can raise a couple of millions I’ll bet someone is going to kill that fucker piece of shit . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:10:57 </td>
   <td style="text-align:left;"> $QQQ zelensky, poor guy looks beyond exhausted … what f up situation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:10:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Looks like the bull run is over. Sub 400 by EOM. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:10:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 

Putin apologists can suck a dick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:10:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Nuclear disaster 10 x Chernobyl already priced in, 2% green day tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:09:51 </td>
   <td style="text-align:left;"> $QQQ $SPY not gonna lie surprised the market isn’t ripping o this news… lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:09:45 </td>
   <td style="text-align:left;"> $SPY $QQQ Finally! Cathie Wood is buying Cyber security stocks $CRWD $OKTA! What took her so long? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:09:33 </td>
   <td style="text-align:left;"> $SPY shud up. just put out the fires. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:09:18 </td>
   <td style="text-align:left;"> Freaking Russians are so damn stupid that they fired on one of Europe’s largest Nuclear Power plants and it’s now on fire causing the markets to tank in afterhours. But they is nothing compared to a nuclear fallout potential.

$QQQ $SPY $XLF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:08:35 </td>
   <td style="text-align:left;"> $QQQ $SPY Putin will be executed by a Russian army General. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:08:18 </td>
   <td style="text-align:left;"> $QQQ fire already contained.... you dumbasses 
 
https://www.youtube.com/watch?v=fYUT36YGOh8 
 
LOL puts are gonna burn :D :D </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:08:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL The only impact sanctions will have is to damage European GDP and make inflation worse. They won’t deter anything as you can see tonight. The time for sanctions as deterrence was several months ago, not now. Biden and the EU are fools. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:08:01 </td>
   <td style="text-align:left;"> $QQQ $SPY  REPORTS UNNAMED UKRAINIAN GOVERNMENT OFFICIAL SAYING ELEVATED RADIATION LEVELS DETECTED AT ZAPORIZHZHIA NUCLEAR PLANT

green by open right bulltards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:07:57 </td>
   <td style="text-align:left;"> $QQQ $SPY lets be real though Putin know how the market and TA works and is literally attacking our market lol at least it seems that way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:07:12 </td>
   <td style="text-align:left;"> $QQQ I have deployed 1/3 of my funds. still holding 2/3.  
 
bring it down baby. I will add more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:07:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY I just want to personally thank Putin for making me so much money I can now retire from working the rest of my life.  Any further bloodshed and nuclear fallout will start making me money I would have to try to spend it all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:07:09 </td>
   <td style="text-align:left;"> $QQQ buying before a nuclear disaster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:07:01 </td>
   <td style="text-align:left;"> $QQQ watch this hole assault end tomorrow as a draw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:06:04 </td>
   <td style="text-align:left;"> $QQQ $NDX The downtrend sadly continues for $NQ_F. We re-entered a PUT position today at the minor downtrend line (resistance) targeting 1300-1350. Futures tonight are confirming the weakness with Ukraine news worsening by the day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:05:57 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Nuclear power plant in Ukraine the largest in Europe is on fire and if it blows up will be 10 times worse then Chernobyl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:05:50 </td>
   <td style="text-align:left;"> $SPY $QQQ posting one more time because this is the best feed you can likely find without media bias BS. Live feed of power plant in Ukraine. Have seen shots fired in last 15 min or so. 

https://youtu.be/X14cRHLb-bU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:05:46 </td>
   <td style="text-align:left;"> $QQQ $SPY here comes the green by open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:05:40 </td>
   <td style="text-align:left;"> UKRAINE FOREIGN MINISTER: REAL THREAT OF NUCLEAR DISASTER

That is messed up, chernobyl 2.0 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:05:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Below 4270 will open doors to more volatility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:05:17 </td>
   <td style="text-align:left;"> $QQQ wtf why is Russia attacking the largest nuclear plant in Ukraine, a meltdown would only blow radioactivity directly into Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:05:15 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:05:07 </td>
   <td style="text-align:left;"> $QQQ this is fin …. Nvmd😔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:05:03 </td>
   <td style="text-align:left;"> $QQQ buy the panic you faggots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:04:51 </td>
   <td style="text-align:left;"> $SPY $QQQ well I just panic sold most of my positions at 7:59pm.  Sick of this fn market.  

Let’s just hope for everyone’s sake Russia backs the fck off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:04:50 </td>
   <td style="text-align:left;"> $QQQ that fucker didn’t even have to drop a bomb, just blow up their nuclear plant and you get the same effect…. You know he planned this all out, max punishment… Jesus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:04:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA  
 nuclear physicist  Galen Winsor swam in nuclear cooling water, ate plutonium, and didnt die of cancer or radiation. 
https://youtu.be/IZgu8jAkEPY?t=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:04:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA There will be no negotiations between Russia and Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:03:56 </td>
   <td style="text-align:left;"> $QQQ oh shit I bought $330 puts expiring tmrw how do they look? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:03:29 </td>
   <td style="text-align:left;"> $QQQ god bless all 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:03:08 </td>
   <td style="text-align:left;"> $QQQ should have left this market when Trump left </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:03:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 77024000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:02:43 </td>
   <td style="text-align:left;"> $QQQ damn ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:02:18 </td>
   <td style="text-align:left;"> $QQQ too many unwarranted +750pt days let’s see that -900pt day for once </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:02:17 </td>
   <td style="text-align:left;"> $QQQ huge dump on what volume? Absolute trash. That’s exactly what shouldn’t be allowed. 

Fear pumping to steal shares with low volume so they pump it back up. It’s disgusting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:02:15 </td>
   <td style="text-align:left;"> $SPY $QQQ no one ever back-tested an explosion ten times the size of Chernobyl?  here is your forward test. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:02:02 </td>
   <td style="text-align:left;"> $SPY can’t wait to get these in the money $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:01:58 </td>
   <td style="text-align:left;"> $QQQ WEVE BEEN THROUGH ALL OF THIS BEFORE, DUCKIN FROM THE WAR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:01:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Poots tomorrow 🔥 
UKRAINE&amp;#39;S FOREIGN MINISTER SAYS FIRE HAS ALREADY BROKE OUT. IF IT BLOWS UP, IT WILL BE 10 TIMES LARGER THAN CHORNOBYL! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:01:15 </td>
   <td style="text-align:left;"> $SPY $QQQ Holy hit 🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:01:01 </td>
   <td style="text-align:left;"> HUGE DUMP AH

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:00:59 </td>
   <td style="text-align:left;"> $LMT $spy $qqq $uvxy $gld damn bro, time to bring in your tomato plants. 🍅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:00:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA A whole generation of investors will walk away from the market if this continues much longer. Nobody wants to invest in this kind of world, with bullies running the show and feckless leaders afraid to stand up to them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:00:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM “To many puts” “Follow the trend” 🐻🩸📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:00:29 </td>
   <td style="text-align:left;"> $SPY $QQQ congrats bears, you win. Your prize? End of humanity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 09:00:02 </td>
   <td style="text-align:left;"> $IWM $SPY $QQQ I guess there is deal on talk w/ Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:59:56 </td>
   <td style="text-align:left;"> $SPY $QQQ BREAKING: Ukraine&amp;#39;s energy ministry claims firefighters have been fired at while trying to put out fire at Zaporizhzhia nuclear power plant </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:59:54 </td>
   <td style="text-align:left;"> $SPY $QQQ The best outcome would be the west asks Russia to destroy all of the nuclear weapons in exchange of lifting the economic sanctions against Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:59:48 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA 🙃🔪☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:59:22 </td>
   <td style="text-align:left;"> The One Trade You Can&amp;#39;t Afford To Miss On Friday $QQQ $USO $SPX https://talkmarkets.com/content/commodities/the-one-trade-you-cant-afford-to-miss-on-friday?post=346774 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:59:22 </td>
   <td style="text-align:left;"> $QQQ I’ve seen eworse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:59:22 </td>
   <td style="text-align:left;"> $SPY $QQQ Russian troops are shelling Europe&amp;#39;s largest nuclear power station in Ukraine - AP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:58:51 </td>
   <td style="text-align:left;"> $QQQ $SPY do any other bears feel bad even though your making money? Like it’s literal catalyst are blood shed and destroying our planet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:58:46 </td>
   <td style="text-align:left;"> $QQQ remember that phantom drop on 2/24 to 329.95? 😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:58:26 </td>
   <td style="text-align:left;"> $QQQ $SPY  $AAPL Rip all calls lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:58:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB putin just saved the bears ASS this is annoying😒😒 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:58:11 </td>
   <td style="text-align:left;"> It May Be Time For Stocks To Worry About A Recession https://mottcapitalmanagement.com/it-may-be-time-for-stocks-to-worry-about-a-recession/ $TSLA, $ZM $qqq $spy $ief </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:58:06 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA &amp;quot;Russian army is firing from all sides upon Zaporizhzhia NPP, the largest nuclear power plant in Europe. Fire has already broke out. If it blows up, it will be 10 times larger than Chornobyl.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:58:04 </td>
   <td style="text-align:left;"> $QQQ $SPY Russia be holding back the whole ass world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:58:04 </td>
   <td style="text-align:left;"> $QQQ guess we’re not opening green. Watch us still rocket above 350 tomorrow.! Fucking feds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:58:00 </td>
   <td style="text-align:left;"> $DUOL good report.  But may not matter $SPY $QQQ futes getting wrecked

GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:57:39 </td>
   <td style="text-align:left;"> $QQQ - Puts were the choice today👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:57:36 </td>
   <td style="text-align:left;"> $SPY $QQQ 
I don’t like what’s happening in Ukraine by the way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:57:30 </td>
   <td style="text-align:left;"> Ukraine&amp;#39;s energy ministry says firefighters at nuclear power plant have been fired at by Russian troops and are unable to get to the blaze - RIA/REU

Attacking the biggest Nuclear Plant $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:56:36 </td>
   <td style="text-align:left;"> $QQQ Indexes are toast. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:56:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Goodbye markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:55:55 </td>
   <td style="text-align:left;"> $QQQ $spy world war 3 has begun. very sad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:55:55 </td>
   <td style="text-align:left;"> $QQQ nuclear power plant burning in Ukraine as we speak . Fucking Putin what an idiot . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:55:49 </td>
   <td style="text-align:left;"> $QQQ nuclear plant... Can&amp;#39;t be a war if there&amp;#39;s no more Ukraine..
(I really would like to think there won&amp;#39;t be a nuclear meltdown) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:55:46 </td>
   <td style="text-align:left;"> $QQQ crashing in after hours...Russia is shelling Ukraine&amp;#39;s working nuclear power plant </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:55:45 </td>
   <td style="text-align:left;"> $SPY $QQQ ...and now even the WWE 
https://www.msn.com/en-us/entertainment/news/breaking-wwe-makes-decision-on-russia-partnership/ar-AAUz5cJ?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:55:45 </td>
   <td style="text-align:left;"> $SPY that moment when you have spotty internet connection and futures just dumps 100. RIP. NASDAQ to $12k soon. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:55:43 </td>
   <td style="text-align:left;"> $spy $qqq Russia bout to freaking blow up that nuclear power plant. Like are you fucking serious. Shelling a nuclear plant.! WTF Putin. What balls or stupidity actually. Even Russians are calling home saying I didn’t sign up for killing Ukraine’s.! He’s bout to go all in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:55:37 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:55:11 </td>
   <td style="text-align:left;"> $QQQ thought 335p would be itm Monday Tuesday looks like we’re getting it before the weekend even better no need to deal with theta </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:55:04 </td>
   <td style="text-align:left;"> $SPY $QQQ 
 
https://sports.yahoo.com/biden-administration-studying-whether-biofuel-214631354.html 
 
Guessing oil refiners might benefit from this news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:54:02 </td>
   <td style="text-align:left;"> $QQQ what did I say. Haters will hate as usual. I post technicals daily. If you guys want more join my telegram group have a sale going on. No need to hate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:53:59 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ “The market doesn’t care about the war in Ukraine” I’ve been reading this over and over the past few weeks, and thinking how shortsighted the market must be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:53:47 </td>
   <td style="text-align:left;"> $SPY do fires in Ukraine stop everything else in the entire world and even space from using chips? 🧐🤔 $SOXL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:53:47 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA WTF IS PUTIN DOING??? Out of his mind bombing a nuke plant. A fire is breaking out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:53:45 </td>
   <td style="text-align:left;"> $QQQ price actions is genius.  The way it unfolds, the nuisances. You can know the date and levels of your choice play but the how always feels so fresh and new.  Looking forward to the day the how doesn’t phase me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:53:18 </td>
   <td style="text-align:left;"> $QQQ how is shelling a nuclear power plant not a war crime/and/or synonymous as declaring war on any other country in the radioactive zone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:53:17 </td>
   <td style="text-align:left;"> $SPY $QQQ WHEN I HIT THE SCENE ITS HOMICIDE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:53:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA WELL THAT ESCALATED QUICKLY BING BONG 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:53:04 </td>
   <td style="text-align:left;"> $QQQ Futures are ripping! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:52:46 </td>
   <td style="text-align:left;"> $QQQ look at the low volume on this panic sell. 

Market manipulators. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:52:20 </td>
   <td style="text-align:left;"> $BA $FB $SPY $QQQ $DIS 

🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:52:17 </td>
   <td style="text-align:left;"> $QQQ lmao wow $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:52:04 </td>
   <td style="text-align:left;"> $QQQ if nuclear fallout spreads outside Ukraine, US has no choice but to get more hands on. I hope we don’t. This can only get worse. Facking Putin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:51:26 </td>
   <td style="text-align:left;"> $QQQ 
every ticker that’s in this ETF is 40$ in the red yet some how this mofo hasn’t broken below 336 yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:51:22 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ 

More conspiracy, Look back on when Russia took Crimea in 2014. 

I’m going to get assassinated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:51:20 </td>
   <td style="text-align:left;"> $QQQ Holy shit looks like i was smart in holding my 335 and 330 puts after bitching all day i wasn&amp;#39;t green.. damn wtf just happened here. Watch it be 350 by open of course right! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:51:12 </td>
   <td style="text-align:left;"> hrm.. Putin attacking Nuclear plant in Ukraine now..  apparently this is the biggest nuclear plant in EU.    
 
Apparently it is now detected that surrounding area&amp;#39;s radiation level is increasing.. 
 
Putin is getting more desperate?! 
 
$SPY $QQQ $VIX $XOP $SPG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:50:46 </td>
   <td style="text-align:left;"> $QQQ taka it easy. The fed will pump everything back up by the morning like nothing happened. Just add more to the existing debt...no worries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:50:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM  I&amp;#39;m clearly bearish on this market for so many reasons.  But damn this escalation of war is starting to make me nervous, regardless of how it helps my portfolio.  Thought we&amp;#39;d collapse under fed policies and ridiculous valuations, which I could celebrate, but this is messed up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:50:32 </td>
   <td style="text-align:left;"> $QQQ US is enters always late intp world wars, as it does not want to escelate things. 
We should not let thi gs happen for things to precipitate into WW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:50:23 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX  
 
Hell no! 
https://www.zerohedge.com/markets/futures-tumble-report-ukraine-nuclear-power-plant-europes-largest-fire-after-shelling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:50:17 </td>
   <td style="text-align:left;"> $SPY Limit down and gap down if nuclear power plant containment blows up.  Putin is at war against ALL of Europe and ALL of humanity on earth.  $sqqq $qqq $uvxy $arkk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:50:09 </td>
   <td style="text-align:left;"> $QQQ either the reactor blows and we could limit down. Or, they get it under control and we reverse hard (imo per my crystal ball lol) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:50:08 </td>
   <td style="text-align:left;"> $SPY $QQQ 200k just today traded the 430 puts that expire tomorrow.

If this shits the bed then it is real panic and fear because usually they would never pay these.

Wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:50:07 </td>
   <td style="text-align:left;"> $QQQ $SPY can we say “capitulation moment”? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:49:50 </td>
   <td style="text-align:left;"> $QQQ $SPY lets thank Brandon. At least he gave a &amp;quot;strong&amp;quot; SOTU speech. 
 
How did we allow this to happen? Are we really that pathetic as a country that we coulnt elect better candidates and get a decent human being elected president? Fkin sad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:49:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB $NFLX 
Why just happened to futures? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:48:58 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ 

Conspiracy time, look at 2008 after the summer Beijing olympics. What just happened? Beijing Winter Olympics. 

History does tend to repeat itself. 

Technical correction or deep state?!?!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:48:43 </td>
   <td style="text-align:left;"> $QQQ went from 343.3 straight to 336 AH 😅😂. Looks like 330 tomorrow is very possible. My portfolio 🩸 but puts 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:48:25 </td>
   <td style="text-align:left;"> $SPY $QQQ 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:48:01 </td>
   <td style="text-align:left;"> $SPY $QQQ  $BTC.X Ooooof </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:47:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $NQ_F  powell is awake now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:47:26 </td>
   <td style="text-align:left;"> $SPY $QQQ some of you think - no worries . we are far away ... NEWSFLASH  - YOU ARE NOT FAR AWAY AT ALL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:47:13 </td>
   <td style="text-align:left;"> $QQQ what happened? This thing started dropping like a rock. Wth!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:47:03 </td>
   <td style="text-align:left;"> $SPY $QQQ 🚨🚨🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:47:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $NQ_F  (nuclear plant) sadly  it&amp;#39;s gonna explode, situation is fubar. 
 
the target was 427 today - i think that&amp;#39;s a wrap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:46:23 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Japan absolutely has nightmarish fear about nuclear anything…

If we have another “Chernobyl” in Ukraine overnight, I believe Japan will be down 10 to 20%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:46:22 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/Os67dNpO5pM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:46:13 </td>
   <td style="text-align:left;"> $QQQ buy the dip!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:46:11 </td>
   <td style="text-align:left;"> $QQQ $SPY tomorrow we will close green .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:45:50 </td>
   <td style="text-align:left;"> $QQQ 

⚠️CALLS ⚠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:45:34 </td>
   <td style="text-align:left;"> $SPY $qqq I don&amp;#39;t want to see no bears getting excited to see people die so they can make money.  
That&amp;#39;s sad. 
Anything else ok go for it but nuclear plant under attack.. come on 🤦‍♂️🤦‍♂️🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:45:29 </td>
   <td style="text-align:left;"> $SPY $qqq $spx finally … 👁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:45:28 </td>
   <td style="text-align:left;"> $QQQ buy the dip!  Hahaha never gets old.   You bulls bleed ur accounts 50%? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:45:23 </td>
   <td style="text-align:left;"> $QQQ KILL PUTIN 💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:45:13 </td>
   <td style="text-align:left;"> $QQQ 

This war is a waste of time. I hope Putin gets his ass wiped off planet earth. 

My bigger concern is how recession has followed every major spike in oil prices.

That’s when we are really fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:44:33 </td>
   <td style="text-align:left;"> $SPY $QQQ 336 was posted as target before close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:44:12 </td>
   <td style="text-align:left;"> $QQQ 

10 X 

Larger than Chernobyl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:44:04 </td>
   <td style="text-align:left;"> $SPY Only thing that matters right now is US oil and transportation of oil $TOPS $USWS $HUSA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:43:55 </td>
   <td style="text-align:left;"> $QQQ the 21st century will be purely a global context...the constant shock and fear will be pervasive.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:43:47 </td>
   <td style="text-align:left;"> $spy $qqq $NQ_F  UKRAINE: Fire has already erupted. If it explodes, it will be ten times the size of Chernobyl. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:43:31 </td>
   <td style="text-align:left;"> $QQQ 

Lol last week Thursday was when war started. Futures were down 400 and 700 points daq+dow 

Turned green next day. 😂😀.

Maybe it was Wednesday but really who cares. We’ll be fine by morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:43:19 </td>
   <td style="text-align:left;"> $QQQ Ukraine&amp;#39;s Foreign Minister Kuleba also confirms that the Zaporizhzhia nuclear power plant has caught fire and says Russian army is firing from all sides upon the nuclear plant and that if it blows up, it will be 10 times larger than Chernobyl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:42:58 </td>
   <td style="text-align:left;"> Powell &amp;amp; his incompetent board simply ignored data &amp;amp; warning from economists and now he has no answers but keeps throwing BS. Shameless should be fired 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:42:54 </td>
   <td style="text-align:left;"> $SPY $QQQ UKRAINE&amp;#39;S FOREIGN MINISTER SAYS FIRE HAS ALREADY BROKE OUT. IF IT BLOWS UP, IT WILL BE 10 TIMES LARGER THAN CHORNOBYL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:42:45 </td>
   <td style="text-align:left;"> $QQQ Q’s will probably be down 3.5-4% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:41:56 </td>
   <td style="text-align:left;"> $SPY Russia starting nuclear disaster.  This is NOT going to end well for neighboring countries - Germany, France, Spain, etc.  $sqqq $qqq $uvxy $arkk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:41:54 </td>
   <td style="text-align:left;"> $SPY $QQQ told ya limit down day.  ALL ON /NQ SIGNALS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:41:06 </td>
   <td style="text-align:left;"> $SPY $QQQ Lets go 7% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:40:47 </td>
   <td style="text-align:left;"> $QQQ 330
Russia attacking the largest nuclear power plant in the EU, located in Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:40:32 </td>
   <td style="text-align:left;"> $QQQ Livestream of the nuclear plant https://www.youtube.com/watch?v=fYUT36YGOh8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:40:30 </td>
   <td style="text-align:left;"> $QQQ but but it is just a correction...bottoms and stuff...sniffle sniffle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:40:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA ☢️☢️☢️☢️☢️☢️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:40:17 </td>
   <td style="text-align:left;"> $SPY $QQQ Not a nuclear attack, but an attack on nuclear 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:40:15 </td>
   <td style="text-align:left;"> $SPY Russian military is blowing up Ukraine&amp;#39;s largest nuclear power plant.  $uvxy $sqqq $qqq $arkk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:39:37 </td>
   <td style="text-align:left;"> $AMD $SPY $QQQ $GOOGL $TSLA 
I have to be the investor of the year 
Puts printing. I called it 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:39:28 </td>
   <td style="text-align:left;"> $SPY $QQQ russia now shelling europe&amp;#39;s largest nuclear power plant. well thats gonna piss off a whole bunch of countries </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:39:24 </td>
   <td style="text-align:left;"> $QQQ I warned you guys 2 days ago that the QQQ was about to dump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:39:08 </td>
   <td style="text-align:left;"> $SPY  whats happening ? $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:39:01 </td>
   <td style="text-align:left;"> $QQQ $SPY  FUTES down because of a nuclear power plant issue in Ukraine.  Really? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:38:58 </td>
   <td style="text-align:left;"> $SPY $QQQ some shits kicking off tonight. Any idea what it is? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:38:44 </td>
   <td style="text-align:left;"> $QQQ it’s not even after 5 yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:38:36 </td>
   <td style="text-align:left;"> $QQQ capitulation?🤕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:38:18 </td>
   <td style="text-align:left;"> $QQQ oh dayum still dropping hard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:38:09 </td>
   <td style="text-align:left;"> $SPY This is what&amp;#39;s going on right now.  $uvxy $sqqq $qqq $arkk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:37:57 </td>
   <td style="text-align:left;"> $SPY $QQQ https://www.bloomberg.com/news/articles/2022-03-03/live-updates-fitch-downgrades-russia-s-credit-rating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:37:53 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:37:51 </td>
   <td style="text-align:left;"> $QQQ about to save my $MRVL gamble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:37:39 </td>
   <td style="text-align:left;"> $QQQ $SPY 

I wonder how the Trump cultists are feeling after hearing the news of this nuclear plant bombing.

Do they still support Putin’s actions? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:37:36 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:37:30 </td>
   <td style="text-align:left;"> $QQQ $SPY Did a nuke go off or something lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:37:29 </td>
   <td style="text-align:left;"> $SPY $QQQ flush the futures! There it is! 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:37:24 </td>
   <td style="text-align:left;"> $QQQ oh baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:37:17 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures tanking on nuclear reactor news... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:37:06 </td>
   <td style="text-align:left;"> $QQQ whats the news driving it down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:36:52 </td>
   <td style="text-align:left;"> $SPY well, if you didn&amp;#39;t exit your 401k or IRA positions, then you&amp;#39;re stuck until tomorrow.  Back to grinding 410?  $uvxy $sqqq $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:36:49 </td>
   <td style="text-align:left;"> $QQQ wow just wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:36:26 </td>
   <td style="text-align:left;"> $QQQ oh no, red futures on the evening mean super ripper next day :/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:36:10 </td>
   <td style="text-align:left;"> $QQQ magically up 5% tomorrow.  Sounds a little crazy so it&amp;#39;ll probably happen.😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:36:03 </td>
   <td style="text-align:left;"> $QQQ Death cross is confirmed today and blood bath starts now? 
 
Futures couldn&amp;#39;t hold it till 8 ET as they usually dump right after the retailers get out but it looks like they are giving them another chance to get out? 
 
And, crude is jumping 3% and I take it Russia hit some oil reserves or an oil embargo or is that the Russian troops shelling near the nuclear plant?  Which is it?  I am not finding any news for this drop AH. 
 
$SPY $USO $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:35:53 </td>
   <td style="text-align:left;"> $QQQ $SPY The biggest manipulation with futures I’ve ever seen!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:35:45 </td>
   <td style="text-align:left;"> $QQQ So what is the new FUD in the market today ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:34:47 </td>
   <td style="text-align:left;"> $SPY $QQQ Doesn&amp;#39;t look good ☢️☢️☢️☢️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:34:05 </td>
   <td style="text-align:left;"> $QQQ futures dropping all of sudden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:33:43 </td>
   <td style="text-align:left;"> $QQQ $SPY it was all a relief rally from oversold conditions. More pain ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:33:26 </td>
   <td style="text-align:left;"> $SPY technical rejection and breakdown RIGHT NOW $uvxy $sqqq $qqq $arkk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:33:23 </td>
   <td style="text-align:left;"> $DJIA $IWM $QQQ $SPY Looking scary </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:33:23 </td>
   <td style="text-align:left;"> $QQQ $SPY 

I believe Putin has some sort of mental disability. Something definitely is not clicking right in his mind. He is quite old.

I do hope the people close to him  become aware of his mental state before something very very bad happens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:32:28 </td>
   <td style="text-align:left;"> $SPY $QQQ circuit breakers might be active tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:32:25 </td>
   <td style="text-align:left;"> Live updates: Russian troops shelling nuclear power station $SPY $DJIA $QQQ $VIX https://www.billionaireclubcollc.com/live-updates-russian-troops-shelling-nuclear-power-station/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:32:07 </td>
   <td style="text-align:left;"> $SPY $QQQ This guy only pulls and shows live feeds in Ukraine and he’s showing the power plant now. 

https://youtu.be/X14cRHLb-bU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:31:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA AWWWWWWW LAWWWWWD BING BONG 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:31:57 </td>
   <td style="text-align:left;"> $SPY $QQQ IM BOOKIN TOUR DATES, THE MONEY IN THE SUITCASE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:31:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Any news came out? Futures diving all of the sudden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:30:43 </td>
   <td style="text-align:left;"> $SPY $QQQ Putin&amp;#39;s intentions are becoming clear, negative price action from this should subside. I&amp;#39;m more worried about jpow testimony today saying Volcker is his idol. Let&amp;#39;s hope inflation eases soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:29:59 </td>
   <td style="text-align:left;"> $AAPL $SPY $GOOGL $QQQ 
It’s bullshit like this that make investors burn their accounts.
“NOT TODAY SATAN” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:29:46 </td>
   <td style="text-align:left;"> $QQQ overreaction.   Green by am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:29:41 </td>
   <td style="text-align:left;"> $USO WTI should be more expensive than Brent, I’m just the only one to come out and say it 🤷‍♂️ $SPY $QQQ $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:29:21 </td>
   <td style="text-align:left;"> $QQQ wake me up when this correction ends 😪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:28:54 </td>
   <td style="text-align:left;"> $QQQ if that plan stabilizes then this will shoot higher than before yhe news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:28:00 </td>
   <td style="text-align:left;"> $QQQ all that bulkish activity only to be taken in 20 minutes. Fk putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:28:00 </td>
   <td style="text-align:left;"> $QQQ $SPY futrs gonna rip when this plant blows up? Just like when they invaded </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:27:55 </td>
   <td style="text-align:left;"> $QQQ do the futures really matter now days? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:27:52 </td>
   <td style="text-align:left;"> $QQQ $SPY whats the f ing news that caused this AH sell off?  F ing BS!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:27:49 </td>
   <td style="text-align:left;"> $SPY $QQQ drink if you said limit down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:27:29 </td>
   <td style="text-align:left;"> $QQQ moon tmrw hit $350 again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:27:02 </td>
   <td style="text-align:left;"> $QQQ blood here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:26:20 </td>
   <td style="text-align:left;"> $SPY @StateOfCapitalism you might be onto something. Just did a quick look at $MSCI (Morgan Stanley Capital International- Fund) and it doesn’t look good. 
1929 Europe Market Collapse. Is anyone paying attention? Bubble popped $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:26:15 </td>
   <td style="text-align:left;"> $QQQ $SPY 

At least it’s not a nuclear missile though right 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:25:49 </td>
   <td style="text-align:left;"> $SPY bear trap intra 7:00 when most retail can’t trade and job report in the morning. Don’t be fooled $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:25:03 </td>
   <td style="text-align:left;"> $QQQ 292 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:25:03 </td>
   <td style="text-align:left;"> $QQQ $SPY attention all  - THERE MIGHT NOT BE A STOCK MARKET TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:24:42 </td>
   <td style="text-align:left;"> $SPY $QQQ Is there news, or…? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:24:30 </td>
   <td style="text-align:left;"> $QQQ $SPY crashing already. the insiders know something about the jobs report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:23:48 </td>
   <td style="text-align:left;"> $ARKK $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:23:31 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Holy shit we crashing….! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:23:23 </td>
   <td style="text-align:left;"> $QQQ 3% drop tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:23:12 </td>
   <td style="text-align:left;"> $QQQ Was $350 this morning, now it will have to go up $8 - 10 from todays closing price to close above todays high. Chances of that happening are unlikely. So now we see what the tape reads after the open, rejections at resistance or a run to the high and price holds above. Not too many ways it could play out really… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:22:13 </td>
   <td style="text-align:left;"> $SPY $QQQ Its pretty hilarious.  I look at my account AH and it’s up.  I check here and people posting futes rippin and then I refresh ONE MINUTE later and I see posts wondering what’s up?  Why down?  This shit has been happening all year long!  Up some then down big!!  Every f ing night!! F this BS!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:21:50 </td>
   <td style="text-align:left;"> $SPY $430 $qqq $340 these are magnets for these two </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:20:53 </td>
   <td style="text-align:left;"> $SPY $QQQ The ultimate Florida Man articles are near </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:20:44 </td>
   <td style="text-align:left;"> $QQQ Looks like the lower highs every week trend continues! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:20:42 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:20:04 </td>
   <td style="text-align:left;"> $SPY $QQQ Looks like somebody forgot to switch the algos back to retarded mode. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:19:40 </td>
   <td style="text-align:left;"> $QQQ what a dump today. Bearish engulfing pattern. I sold my puts for peanuts yesterday and switched to calls only to get slapped by QQQ again. FFS. I had the right idea with my 310 post but I let the noise from bulls persuade me to make the wrong move on this. Again. I&amp;#39;m going to take a break from playing options on this it&amp;#39;s a drain on my account lol. I make gains trading stocks then waste them on options 🤦 I give up for a while. Ill stick to equities where I actually make money (other than the Chuck Hughes setups that seem to work like a champ but don&amp;#39;t come around often). 

I&amp;#39;ll continue to track what this does and how it behaves. I got strategies to backtest. Perhaps if I find something with a 60%+ win rate I&amp;#39;ll post what I find. But I&amp;#39;m done giving up gains here for now. Today really pissed me off. 

Cheers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:19:11 </td>
   <td style="text-align:left;"> $QQQ Green Light days ago to Kick this Pig!! We&amp;#39;re going to be swimming in Oil. $5 a barrel here we come. 🤣😊 
 https://www.wsj.com/livecoverage/russia-ukraine-latest-news-2022-03-03/card/congress-introduces-bill-to-ban-russian-crude-seeking-to-squeeze-putin-revenue-source-ppUZbgVfQZTbpGTa6fN8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:17:53 </td>
   <td style="text-align:left;"> $QQQ Ukraine&amp;#39;s Zaporizhzhia plant spokesman says Russian troops are shelling the plant which Europe&amp;#39;s largest nuclear power plant </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:17:17 </td>
   <td style="text-align:left;"> $TMC $DJIA $QQQ $IWM $SPY 

At full scale, TMC will replace Russia’s Nornickel as the worlds top producer of battery-grade nickel. TMC will produce the cheapest and most sustainable nickel in the world. Definitely a 100x commodity play with the skyrocketing prices of nickel, cobalt and copper.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:16:50 </td>
   <td style="text-align:left;"> $SPY BTFD!!!!!!!  Let’s do this bulls!  My ass wants it!! $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:16:02 </td>
   <td style="text-align:left;"> $QQQ f this BS .  Bulls lets take this shit over!  BUY BUY BUY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:15:59 </td>
   <td style="text-align:left;"> $SPY $QQQ the world is shutting Russia down.  VW group https://carbuzz.com/news/volkswagen-sends-a-message-to-russia-by-suspending-production

Take note China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:14:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $ERUS lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:13:54 </td>
   <td style="text-align:left;"> Stock futures rise slightly as investors brace for February jobs report, Russia-Ukraine updates

$SPY $QQQ $DJIA

https://www.cnbc.com/2022/03/03/stock-futures-rise-slightly-as-investors-brace-for-february-jobs-report-russia-ukraine-updates.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:13:34 </td>
   <td style="text-align:left;"> $QQQ $SPY  I said this last week. We hit 350 as predicted. Now we are going to 310 and it will be very rollercoaster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:13:20 </td>
   <td style="text-align:left;"> Notable bonds spread move, now hit the .20’s..

Current spread: .296

$NASDAQ $SPY $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:13:05 </td>
   <td style="text-align:left;"> $QQQ “hurry, hurry, everyone scream that we’re crashing 

We might be able to make a few innocent people sell to us early!”😏

Don’t let the loud mouth apocalyptic paid bashers scare you.

We’re in an uptrend. If we break the trend, then we can reevaluate. 
📈🖍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:13:01 </td>
   <td style="text-align:left;"> $QQQ Lets break that 340 before ink replacement is done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:12:55 </td>
   <td style="text-align:left;"> $QQQ $SPY What&amp;#39;s happening? All of a sudden, a big drop AH? 
 
This is one crazy messed up market! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:12:37 </td>
   <td style="text-align:left;"> $QQQ Good night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:12:36 </td>
   <td style="text-align:left;"> $QQQ $SPY I’M MOONWALKIN ON THE SUN HOT 😆💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:11:29 </td>
   <td style="text-align:left;"> $QQQ ok. Here we go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-04 08:11:17 </td>
   <td style="text-align:left;"> $SPY $QQQ 

LOL.. short lived “ripping” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:24:17 </td>
   <td style="text-align:left;"> $PYPL $SQ $BA $MSFT $AAPL  has been a long and painful year and we are only in March…things have to get better right? I’ll be an alcoholic by April at this rate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:22:39 </td>
   <td style="text-align:left;"> $LCID just imagining what if the news of  $AAPL partnership comes out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:21:14 </td>
   <td style="text-align:left;"> $AAPL 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:20:46 </td>
   <td style="text-align:left;"> $AAPL there gonna spank this son bitch to $150 in a NY minute. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:20:15 </td>
   <td style="text-align:left;"> $AAPL what this world going in to a nuclear  war now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:18:35 </td>
   <td style="text-align:left;"> $AAPL what happened that the market dropped been out of the loop because of work </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:18:29 </td>
   <td style="text-align:left;"> $AAPL what are the fudders on CNBC saying? Can anyone share? Its not working for me and i am in India </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:18:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:15:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $FDX $NKE Beautiful! Please share! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:15:36 </td>
   <td style="text-align:left;"> $AAPL $MSFT https://www.benzinga.com/amp/content/25754909 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:15:30 </td>
   <td style="text-align:left;"> $AMC what’s the latest news ? $GME $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:14:01 </td>
   <td style="text-align:left;"> $AAPL my 170c got toast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:11:55 </td>
   <td style="text-align:left;"> $AAPL new daily low on futures. Sheesh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:11:32 </td>
   <td style="text-align:left;"> $AAPL I should’ve held my 3/4 160 puts😅 jeez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:10:47 </td>
   <td style="text-align:left;"> $GOOGL no one gives a fuck about Ukraine !! Stop with this bs fud!!!! So fucking retarded $TSLA $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:09:48 </td>
   <td style="text-align:left;"> $AMZN $AAPL $GOOG $NVDA  
It is largest Nuke plant in Europe. Plant is still burning 
 
not sure but i think that might be the point, false flag?  
 
&amp;quot;A government official tells The Associated Press elevated levels of radiation are being detected near the site of the Zaporizhzhia nuclear plant, which provides about 25% of the country’s power generation&amp;quot; 
 
Watch what the dollar does next? Don&amp;#39;t look @ futures right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:09:37 </td>
   <td style="text-align:left;"> $AAPL So what does ukraine nuke plant have to do with aapl? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:08:36 </td>
   <td style="text-align:left;"> $AAPL $TWTR $FB All just got banned in Russia. This is going to destroy the market tomorrow from the $SPY being dragged down. Bright side is Lomotif just lost some competition over there 🤣 
 
 
 
$BBIG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:08:27 </td>
   <td style="text-align:left;"> $AAPL Firefighters unable to reach fire at Zaporizhzhia nuclear plant </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:08:20 </td>
   <td style="text-align:left;"> $AAPL I think my puts for tomm on $SPY and  apple are gonna hit. I’m always optimistic. But Iv seen crazier moments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:08:01 </td>
   <td style="text-align:left;"> latex49a321060d32ff1d32c9e69c5faf3a69 
 
Short latexd2b36131b4a66f5c6550fa869ef4c21d 
Short latexcba03dc1757d69488addbcb945919c22 
 
$SPY $TSLA $BTC.X are being 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:05:57 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Nuclear power plant in Ukraine the largest in Europe is on fire and if it blows up will be 10 times worse then Chernobyl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:05:56 </td>
   <td style="text-align:left;"> $AAPL at least we will have a nice gap to the upside to play once we hit some bottom support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:05:34 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB $BTC.X $TSLA Fighting near Nuclear plant knight king watching. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:04:27 </td>
   <td style="text-align:left;"> $AAPL doesnt make sense in the slightest way lmao. in Comparison, 4.4 million shares traded for a $1 drop in open hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:02:05 </td>
   <td style="text-align:left;"> $AAPL so, anyways, like I said yesterday, broadening formations are mostly bearish. 

It is AH though, so it really doesn’t mean shit until 9:30, right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:01:59 </td>
   <td style="text-align:left;"> $AAPL sooooo I went away I come back to major price drop. Either biggest bear trap I’ve seen or my calls are totally screwed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:01:57 </td>
   <td style="text-align:left;"> $AAPL I will be a buyer at $80-$90, still needs to capitulate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:01:34 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 09:01:27 </td>
   <td style="text-align:left;"> $AAPL Most of those countries around Ukraine must feel a big relieve now being part of the OTAN, otherwise Russians would have crashed them all already. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:59:18 </td>
   <td style="text-align:left;"> $AAPL crazy they’re allowed to manipulate the bid/ask like this…no volume just small share laddering </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:59:15 </td>
   <td style="text-align:left;"> $AAPL yay my covered calls are getting safer 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:59:12 </td>
   <td style="text-align:left;"> $AAPL we might finally get the mass selling tomorrow , maybe -5% day anyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:58:56 </td>
   <td style="text-align:left;"> $aapl Suppose it does cause a radiation leak, why should it affect Apple&amp;#39;s price lmao?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:58:26 </td>
   <td style="text-align:left;"> $QQQ $SPY  $AAPL Rip all calls lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:57:21 </td>
   <td style="text-align:left;"> $AAPL The burning plant will make Chernobyl look like firecracker </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:56:31 </td>
   <td style="text-align:left;"> $AAPL BS price action i swear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:56:31 </td>
   <td style="text-align:left;"> $AAPL  NEW PT$250. 🍏🆙🔜🔝

AAPL : Loup&amp;#39;s Gene Munster sees Apple shares headed to $250 - STCK.PRO. 

https://www.stck.pro/news/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:56:07 </td>
   <td style="text-align:left;"> $AAPL Nuclear plant is burning...Explosion possible! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:53:28 </td>
   <td style="text-align:left;"> $AAPL $ABNB Airbnb rent  houses  ,Apple sell electronics..both took a dive at the same time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:52:26 </td>
   <td style="text-align:left;"> $aapl 114000 shares traded which caused this 164 point dip. This is insane lmao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:52:19 </td>
   <td style="text-align:left;"> $SPY Wait Tom Lee said we had bottomed, lol the guy has been wrong every single prediction he&amp;#39;s had this year $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:52:14 </td>
   <td style="text-align:left;"> $AAPL Putin has got to go. Now ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:51:48 </td>
   <td style="text-align:left;"> $AAPL Stocktwits is definitely not real time quotes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:51:22 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ 

More conspiracy, Look back on when Russia took Crimea in 2014. 

I’m going to get assassinated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:51:22 </td>
   <td style="text-align:left;"> $AAPL bloodbath tomorrow morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:50:53 </td>
   <td style="text-align:left;"> $COST $AAPL $TSLA  European nuclear plant on fire https://www.independent.co.uk/news/world/europe/russia-ukraine-news-putin-war-b2028080.html?amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:50:26 </td>
   <td style="text-align:left;"> $AAPL  🍏Ukraine:  Breaking News:  Fire at Nuclear Power Plant…Russians attacking Plant, will not let Ukrainian Firefighters put fire out…radiation leak detected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:50:25 </td>
   <td style="text-align:left;"> $AAPL keep buying that dip, only 90 dollars from the real bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:50:23 </td>
   <td style="text-align:left;"> $aapl nuclear plant in attack so they sell it off? Sounds gay. Like wtf is that gonna do? This so such BS FUD lmao. Things shall be clear by the tine market closes. Sheesh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:48:58 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ 

Conspiracy time, look at 2008 after the summer Beijing olympics. What just happened? Beijing Winter Olympics. 

History does tend to repeat itself. 

Technical correction or deep state?!?!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:48:52 </td>
   <td style="text-align:left;"> $AAPL 145.00 pre market tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:46:50 </td>
   <td style="text-align:left;"> $AAPL wtf just happen. Market just dump . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:45:29 </td>
   <td style="text-align:left;"> $AAPL ok wtf happened? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:43:28 </td>
   <td style="text-align:left;"> $AAPL stock analysis based on today&amp;#39;s closing price 

https://youtu.be/euifPTen240 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:39:49 </td>
   <td style="text-align:left;"> $AAPL my printer going brrrrrrrrrrrrrr tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:39:03 </td>
   <td style="text-align:left;"> $AAPL smoke seen coming out of Europe’s largest nuclear plant , that’s the reason fires are bleeding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:38:17 </td>
   <td style="text-align:left;"> $AAPL I’ve seen this before. Apple will open premarket -3$ but be up green by market open. That’s how rigged this BS is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:36:10 </td>
   <td style="text-align:left;"> $AAPL why are futures bleeding right now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:36:03 </td>
   <td style="text-align:left;"> $QQQ Death cross is confirmed today and blood bath starts now? 
 
Futures couldn&amp;#39;t hold it till 8 ET as they usually dump right after the retailers get out but it looks like they are giving them another chance to get out? 
 
And, crude is jumping 3% and I take it Russia hit some oil reserves or an oil embargo or is that the Russian troops shelling near the nuclear plant?  Which is it?  I am not finding any news for this drop AH. 
 
$SPY $USO $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:31:20 </td>
   <td style="text-align:left;"> $AAPL help Ukraine by shorting the stock market, buy doge and send it to them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:30:35 </td>
   <td style="text-align:left;"> $AAPL Futures crashing again. Now what !?!??!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:30:09 </td>
   <td style="text-align:left;"> $AAPL I like the Risk vs Reward ratio here. Make sure you guys are applying the RvR to your trades so you don&amp;#39;t blow up your account. Here&amp;#39;s a quick tutorial I pulled together for those that may find it useful: https://youtu.be/CytzoL2ec14 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:29:59 </td>
   <td style="text-align:left;"> $AAPL $SPY $GOOGL $QQQ 
It’s bullshit like this that make investors burn their accounts.
“NOT TODAY SATAN” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:29:41 </td>
   <td style="text-align:left;"> $USO WTI should be more expensive than Brent, I’m just the only one to come out and say it 🤷‍♂️ $SPY $QQQ $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:28:35 </td>
   <td style="text-align:left;"> $AAPL 🆘🆘🆘help Ukrainians any way you can!🆘🆘🆘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:27:41 </td>
   <td style="text-align:left;"> $AAPL I sold off everything when Russia started moving into Ukraine.  Decided to buy call and spreads on Apple today.  Lol glad I bought that last minute in the money put. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:25:53 </td>
   <td style="text-align:left;"> $AAPL $SPY $BTC.X  Someone should start a Go Fund Me account for a bounty on Putin. I bet there would be multimillions $$$ in worldwide donations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:25:17 </td>
   <td style="text-align:left;"> $AABB $AMZN $AAPL $TSLA $MSFT $AABB Gold/Global Exchange/NFT&amp;#39;s! https://www.fool.com/ext-content/amazon-ceo-says-his-company-will-go-bankrupt/?utm_source=investingchannel&amp;amp;utm_medium=contentmarketing&amp;amp;utm_campaign=ai-ceobankrupt&amp;amp;aid=8976&amp;amp;paid=8976&amp;amp;waid=8976&amp;amp;source=esaiclwdg0500004&amp;amp;psource=esaiclwdg0500004&amp;amp;wsource=esaiclwdg0500004&amp;amp;utm_content=IM0101&amp;amp;testId=ai-ceobankrupt&amp;amp;cellId=2&amp;amp;campaign=sa-ai </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:20:30 </td>
   <td style="text-align:left;"> $SPY Market way underestimating the Cold War will have on the economy. Shelling nuclear power plants or not $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:11:40 </td>
   <td style="text-align:left;"> What just happened $spy $spx?   $aapl $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:08:17 </td>
   <td style="text-align:left;"> $SPY $SPX $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:03:43 </td>
   <td style="text-align:left;"> $AAPL Tomorrow $175. I see no reason for this foolishness. If Putin fires the nukes it&amp;#39;s all over anyway and nothing you did will matter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 08:00:59 </td>
   <td style="text-align:left;"> $SPY $SPX  $AAPL   
 
 
the choppy day retested white line 26 day candle average support and bounced.. not much darkpool or option flow today..  
 the Ants ate big slices of cake below ichimoku cloud and now ready to head back up fast to cloud equilibirum levels..! its price average levels formed from past months price averages.. (ichimoku cloud formula) 
 
Didi you enjoy the Cake?  wave riders did..  
 
likely happens fast!..  
also,  that oil drop was big.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:59:26 </td>
   <td style="text-align:left;"> $AAPL    🍏👍   “All aboard”…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:58:58 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:58:24 </td>
   <td style="text-align:left;"> $AAPL damn son! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:55:46 </td>
   <td style="text-align:left;"> $AAPL like I said…https://www.thestreet.com/apple/.amp/news/how-important-is-russia-to-apples-business </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:54:24 </td>
   <td style="text-align:left;"> $AAPL     🍏 The March 8 “Apple Event”, is alive and well!  “Invitation”, on the Apple Website:  Now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:52:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA 🥲🥲 just me? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:50:48 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 127.1K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:44:57 </td>
   <td style="text-align:left;"> $AAPL anyone else seeing bullish and bearish divergence? Man… which path is it going to take tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:41:16 </td>
   <td style="text-align:left;"> $AMZN $TSLA $TLT $AAPL $QQQ  
Economic Events Calendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:38:06 </td>
   <td style="text-align:left;"> $AAPL triple topped. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:31:17 </td>
   <td style="text-align:left;"> $AAPL $FSR https://www.apple.com/apple-events/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:30:48 </td>
   <td style="text-align:left;"> $AMZN $SPY $AMD $AAPL $MSFT  My dad said that Taiwan invasion likely to happen very soon😮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:26:34 </td>
   <td style="text-align:left;"> $AAPL https://www.ped30.com/2022/03/03/apple-munster-lead-times-halved/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:22:10 </td>
   <td style="text-align:left;"> $aapl was going through my YTD trades, so turns out $schw has made about $766 from me based on the options traded alone. I already have the rate negotiated from $0.65 to $0.5 per trade. You think i could get it lower ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:20:01 </td>
   <td style="text-align:left;"> $AAPL not gonna crack 170 eow.. needed to hold 168 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:19:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Loup&amp;#39;s Gene Munster sees Apple shares headed to $250 https://www.stck.pro/news/AAPL/23791406 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:18:05 </td>
   <td style="text-align:left;"> $KR the fact that this shit hole doesn’t take $AAPL pay or $GOOGL $GOOG  pay makes this a $0 stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:17:08 </td>
   <td style="text-align:left;"> Why Apple $AAPL , Microsoft $MSFT And Other Big Buyback Stocks Are Crushing The S&amp;amp;P 500’s Returns $GOOG $SPY $FB https://www.billionaireclubcollc.com/why-apple-microsoft-and-other-big-buyback-stocks-are-crushing-the-sp-500s-returns/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:17:00 </td>
   <td style="text-align:left;"> The industry average Profit Margin is 6.11%. $AAPL outperforms 93% of its industry peers. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:15:37 </td>
   <td style="text-align:left;"> $AAPL Option Alert.. 👀 👀  $170 Call for Friday, March 4. Roughly $2 Million dollars 🔥🔥🔥 Learn more on StockOrbit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:13:43 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL), Gamestop Corporation (NYSE: $GME) – ‘Astonishing And Completely Nontransparent’: Former SEC Commisioner Talks Regulation With Jon Stewart..  https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-gamestop-corporation-nysegme-astonishing-and-completely-nontransparent-former-sec-commisioner-talks-regulation-with-jon-stewart/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:10:28 </td>
   <td style="text-align:left;"> $AAPL NEW PRICE TARGET 250$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:09:58 </td>
   <td style="text-align:left;"> $VXX $UVXY $SPY $AAPL  🙋‍♀️  my only catch of the week lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:06:42 </td>
   <td style="text-align:left;"> $AAPL Unbelievable CNBC Fast Money, no more content or what?? Always going after Apple?? CROOKS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:04:17 </td>
   <td style="text-align:left;"> $AAPL Only CNBC would take appl&amp;#39;s high relative strength and try to spin it into a negative. Also talks about Appl&amp;#39;s valuations being to expensive than recommends to buy pure speculation in etherium - CNBC clowns 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 07:03:10 </td>
   <td style="text-align:left;"> Why Apple, Microsoft And Other Big Buyback Stocks Are Crushing The S&amp;amp;P 500&amp;#39;s Returns $PKW $SPY $AAPL $MSFT $JPM https://www.benzinga.com/trading-ideas/long-ideas/22/03/25754909/why-apple-microsoft-and-other-big-buyback-stocks-are-crushing-the-s-p-500s-returns#.YiFIt-G_CxI.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:56:50 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $TSLA $AAPL  
 
You knew the top was in when all the scoundrels at the FED were cashing out and retiring! 
 
They ain&amp;#39;t no dummies!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:52:07 </td>
   <td style="text-align:left;"> $AAPL this the double top they warned about!! Probably triple top!! Get at me about to get f&amp;#39;d!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:48:21 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $NASDAQ $NVDA 
Market is down by lazy Americans 🤦🏻‍♀️

Economy likely added 440,000 jobs in February – but labor shortage persists
https://www.marketwatch.com/story/economy-likely-added-440-000-jobs-in-february-but-labor-shortage-persists-11646317194 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:45:46 </td>
   <td style="text-align:left;"> $AAPL algos targeting 175 within 2 weeks. Congrats to everyone who bought in the 150s huge success. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:42:54 </td>
   <td style="text-align:left;"> Fast Money must need a ratings boost so that’s why the $AAPL hate is back. F them! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:36:21 </td>
   <td style="text-align:left;"> $spy $qqq $aapl $msft

Guys what are expecting for tomorrow job report?

What number suppose to be good?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:35:34 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:31:33 </td>
   <td style="text-align:left;"> $ESTC this supposed to be at $120 minimum.. what an excellent earning . $COST $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:31:19 </td>
   <td style="text-align:left;"> $AAPL screw 🍎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:29:06 </td>
   <td style="text-align:left;"> $AAPL wala magic wala magic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:26:54 </td>
   <td style="text-align:left;"> $AAPL NATO (USA) know that Ukrainian people and it’s foreign civilian helpers don’t have a chance against Russia. It is a total hypocrisy what NATO USA is doing by only watching. It should tell everyone in Ukraine to move to NATO countries to save their life. Civilian attacking Russia will cause more casualties. Without NATO troops there is no chance to defeat Russia. It is mind blogging that NATO is not putting out this information. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:25:03 </td>
   <td style="text-align:left;"> $AAPL 
Biden needs to send every refugee an iPhone and Covid test kit. 

Until then….. 
🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:24:54 </td>
   <td style="text-align:left;"> #SP500 Today &amp;#39;s HeatMap of  market stocks: $GOOG 
$GOOGL $AMZN $TSLA $AAPL 
  
finscreener.org/map/map </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:24:32 </td>
   <td style="text-align:left;"> $GME $AAPL &amp;#39;Astonishing And Completely Nontransparent&amp;#39;: Former SEC Commisioner Talks Regulation With Jon Stewart 

https://newsfilter.io/a/6255f51e828811ce4bcda6859aa351f7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:23:06 </td>
   <td style="text-align:left;"> Today &amp;#39;s  #DOW30 HeatMap of  #large  market stocks: $AAPL 
 $MSFT $UNH $JNJ $JPM 
   
finscreener.org/map/map </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:22:15 </td>
   <td style="text-align:left;"> $BA $AAPL $AMD 🙋‍♂️💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:22:00 </td>
   <td style="text-align:left;"> $HRL Watch this Everyone WATCH CLOSELY , $TSLA $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:20:15 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL), Google Inc. (NASDAQ: $GOOG) – Lawmakers Question Apple, FBI Over NSO Group Spyware https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-google-inc-nasdaqgoog-lawmakers-question-apple-fbi-over-nso-group-spyware/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:19:52 </td>
   <td style="text-align:left;"> $AAPL turnoff all your phones. Just do it. Set the world free of the crack covaine that’s is the smart phones. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:18:27 </td>
   <td style="text-align:left;"> $AAPL help Ukraine 
Please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:18:25 </td>
   <td style="text-align:left;"> $AAPL JFC, who paid CNBC to slam Apple on Fast Money today? Really out of the blue! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:17:22 </td>
   <td style="text-align:left;"> My trading &amp;quot;wrap sheet&amp;quot; for the day was quite robust again. 
 
-4 short $VXX scalps 
-3 long $TQQQ scalps and recapture lower 
- sold some $WMT that was acquired below $135 
- sold some $AAPL at the open and recaptured lower 
-2 long $AMZN scalps again today  
- sold some VZ that was purchased below $52 last year.  
 
You can trade/invest with me at Finom Group 1/2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:16:27 </td>
   <td style="text-align:left;"> $EAR and what happens if $AAPL, $AMZN or SAMSUNG were to make a move to acquire EARGO at these prices? Food for thought? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:13:15 </td>
   <td style="text-align:left;"> $AAPL my shirt position has been locked and loaded..new lows coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:12:35 </td>
   <td style="text-align:left;"> Wow, nothing is off the sanctions list... even cats?  lol 
 
Western powers are united as ever and thank you so much Putin for making this happen although it pains me to see that the poor Ukrainians are suffering because of this... Just sick and sad at the same time! 
 
Well, Putin needs to be replaced for sure and tried for war crimes but who is going to do that?  Hopefully, all these sanctions will make it happen and I am not sure how long can the Russians put up with this crazy lunatic?   
 
$SPY $QQQ $AMD $AAPL $SOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:10:24 </td>
   <td style="text-align:left;"> $ESTC Monster earning and guidance.. best entry ever for low float stock after beating on earning and didn’t shoot up…tomorrow is when this will rocket 🚀 parabolic.. chance to run another 30-40%.. $SOFI $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:09:01 </td>
   <td style="text-align:left;"> $MULN   $TSLA $AAPL $LCID $GME join here, MULN its oversold tomorrow big squeeze. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:08:17 </td>
   <td style="text-align:left;"> $AAPL CNBC bashing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:06:20 </td>
   <td style="text-align:left;"> $AMD $AAPL $MSTR $RIVN $RBLX  
Tech seems to keep lagging?  
 
https://www.youtube.com/watch?v=TMAj6kq7ngo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:05:14 </td>
   <td style="text-align:left;"> $AAPL I feel 168-169 will c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:02:15 </td>
   <td style="text-align:left;"> $SOS $SPY $BTC.X $ETH.X $AAPL 

This vid made my day 🤣. 
https://youtube.com/shorts/tJ_suUQOqAc?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:01:50 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-03 Options Analysis Video: 
https://www.youtube.com/watch?v=fPYDkF394hA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:00:44 </td>
   <td style="text-align:left;"> A Bullish Sign For Apple $AAPL, Meta $FB  Platforms And PayPal $PYPL Stocks: What The Charts Are Saying https://www.billionaireclubcollc.com/a-bullish-sign-for-apple-meta-platforms-and-paypal-stocks-what-the-charts-are-saying/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 06:00:02 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:59:27 </td>
   <td style="text-align:left;"> $AAPL think it’s going to seek a bottom or will we move out of this broadening formation? Seems like a lot of indecision on price. 

Anyone have any other theories?

Yes, phone TA 🤫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:57:29 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL), Amazoncom, Inc. (NASDAQ: $AMZN) – 10 Things That Are Surprisingly Cheaper Than A Barrel Of Crude Oil Right Now  $DWAC  $FB $TWTR https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-amazon-com-inc-nasdaqamzn-10-things-that-are-surprisingly-cheaper-than-a-barrel-of-crude-oil-right-now/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:50:06 </td>
   <td style="text-align:left;"> $SPY $AAPL same shit different smell. Inflation fears ease, inflation fears rise. 😂same headlines every other day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:46:34 </td>
   <td style="text-align:left;"> $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:42:48 </td>
   <td style="text-align:left;"> $aapl Can&amp;#39;t wait to get a new phone..same features....different color. Massive innovation...with no head winds!!! Just ignore the news and turn the chart upside down..you will see what I see !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:41:33 </td>
   <td style="text-align:left;"> $AAPL Callout today made gains!🤑🎉🔥
Free discord in bio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:40:51 </td>
   <td style="text-align:left;"> $AAPL 04-Mar-22 ATM Implied Vol Climbs +5.1% to 27.3. Straddle Implies a Move of ±1.4% https://tinyurl.com/yysafcy6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:40:39 </td>
   <td style="text-align:left;"> Nasdaq Death Cross Market&amp;lt;250 MA
Is this imaginary? No! 
Why are people not more cautious? 

$AMD $AAPL $QQQ $NVDA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:40:02 </td>
   <td style="text-align:left;"> $AAPL wtfffff nothing holds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:36:24 </td>
   <td style="text-align:left;"> $SPY Based on what Powell said, looks like they kicked the can down the road for 6 months or so. The rest of the year and possibly first quarter of 2023 will be ugly for bulls. Crazy to think that this war actually saved the market. Tells you how fk up things are. This was going to be below 400 by the end of March if Russia didn&amp;#39;t invade 100% guaranteed. Now, that just got pushed back, but you better believe is coming.
$QQQ $AAPL $AMD $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:36:07 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 308.2K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:35:14 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Low-Priced iPhone Will Help AAPL Stock Heat Up After ‘Peak Performance&amp;#39; Apple Event https://www.stck.pro/news/AAPL/23786416 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:35:06 </td>
   <td style="text-align:left;"> $AAPL https://finance.yahoo.com/amphtml/news/how-tech-companies-benefit-from-taking-on-russia-204734487.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:33:25 </td>
   <td style="text-align:left;"> $AVGO Broadcom pops as Q1 results, guidance beat expectations
 https://seekingalpha.com/news/3809234?source=ansh $AVGO, $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:33:11 </td>
   <td style="text-align:left;"> $AAPL everything dumped but apple wow strong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:28:44 </td>
   <td style="text-align:left;"> Low-Priced iPhone Will Help $AAPL Stock Heat Up After &amp;#39;Peak Performance&amp;#39; Apple Event 
 
https://investorplace.com/2022/03/low-priced-iphone-will-help-aapl-stock-heat-up-after-peak-performance-apple-event/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:22:43 </td>
   <td style="text-align:left;"> $AAPL Took the Jan 24 low last week.  We like looking for a decline further down after minor more upside, where buyers can enter at the blue box for a bounce.  We don’t like to sell it short this close to the blue box though, but we do like to buy it lower at the extreme 100% area.  #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:21:53 </td>
   <td style="text-align:left;"> $AAPL my covered call premiums are so nice. Let&amp;#39;s stay in range  next week too! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:20:57 </td>
   <td style="text-align:left;"> Broadcom Non-GAAP EPS of $8.39 beats by $0.26, revenue of $7.71B beats by $100M $AVGO $QQQ $AAPL $SMH https://bit.ly/3C9uWWm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:16:07 </td>
   <td style="text-align:left;"> Why buy the Market here 
Market could minimally drop another -10-12%  from here 🤦‍♂️ SMH 

Russia Ukraine War getting worse and it could get worse for Western Europe 

$AAPL $AMD $NVDA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:15:09 </td>
   <td style="text-align:left;"> Algorithmic trade idea: Signal generated on $AAPL as a top ticker for sweep activity.

See recent trends and the options contracts institutions are trading in screenshot from https://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:15:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:12:58 </td>
   <td style="text-align:left;"> $AAPL other sectors of economy getting screwed eventually impacting everything else...WS is very generous with this Market! $$$$$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:09:09 </td>
   <td style="text-align:left;"> $AAPL https://twitter.com/thelitigator247/status/1499486237983391751?s=20&amp;amp;t=f4yaVWuzRkgitsBYftBqbA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:08:37 </td>
   <td style="text-align:left;"> $SPY $AAPL why listen to a guest that has “the” Ukraine at least three times </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:08:37 </td>
   <td style="text-align:left;"> This isn&amp;#39;t just about the Russia/Ukraine war. Think bigger picture. This is Russia/Ukraine + Biggest inflation since the 1970&amp;#39;s + FED needing to raise interest rates to fight inflation + Household allocation to stocks being at its highest percentage ever + Ripple effects from sanctions + Everyone in the world being long the same stocks/etfs ( $AAPL $SPY $QQQ ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:04:46 </td>
   <td style="text-align:left;"> $AAPL buying back 3% of shares when trading at 30x earnings estimates is actually dumb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:03:26 </td>
   <td style="text-align:left;"> $AAPL I know exactly what happened. Algos monitor human behavior, humans, retail thought it was going to do a drop like 2/24 started buying the dip probably using margin. Algos selling Tutes &amp;amp; hedges got puts &amp;amp; shorted, going to force retail to sell &amp;amp; get margin calls. The market is not free retail pays &amp;amp; tutes get paid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 05:02:43 </td>
   <td style="text-align:left;"> $SOFI I’m a massive bag holder here. But if I wasn’t I would be scared as F to buy this shit.  Literally once retail buys, that money instantly disappears by someone selling it.  It’s a vicious circle. The only way to make money is to buy shit like $AAPL which is too powerful to b controlled.  

I’m in this at 19+. My advice to anyone thinking of buying this. Don’t do it. This is the most trash stock I’ve ever bought and I was in Tesla pre split   Apple b4 the iPhone. I’ve been early in many stocks. None of them is as bad as this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:56:39 </td>
   <td style="text-align:left;"> $AAPL bloodbath tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:55:10 </td>
   <td style="text-align:left;"> $SPY $AMD $AAPL it blows my mind when people think their stock pick shouldn’t go down with the market. People need to pay their bills. The market is overall confidence. Just because an investment is sound and the products valuable doesn’t mean majority of people can afford to wait for gains over paying bills. Economics 101 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:54:38 </td>
   <td style="text-align:left;"> If you got in $aapl calls yesterday 170- 172 u should of came out with decent Gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:54:25 </td>
   <td style="text-align:left;"> $AAPL BIDEN IS SOFT…😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:53:23 </td>
   <td style="text-align:left;"> $AAPL     🍏 Perspective!  Enough, with the Bearish Posts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:51:52 </td>
   <td style="text-align:left;"> $KHC heading much higher. $WEAT 
$KR $AAPL $TSLA the amount of Durum for noodles that will be consumed will be massive long shelf life </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:51:28 </td>
   <td style="text-align:left;"> $AAPL shorts covering, BUY! $$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:51:27 </td>
   <td style="text-align:left;"> $MSFT - $AAPL  - $NVDA 

Adding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:50:03 </td>
   <td style="text-align:left;"> $MULN $TSLA $AAPL $V $GOOGL starting to get fed up with this market may just sell everything and come back in 2 years to buy, this +3000 -$6000  is not worth it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:49:23 </td>
   <td style="text-align:left;"> $AAPL Messages apps on iOS 15 and iPadOS 15 allow you to collaborate with others, share interesting finds, play games, and decorate your chat with stickers. Here&amp;#39;s what you need to know to get started using them. 
 
https://appleinsider.com/articles/21/11/10/how-to-install-and-manage-apps-for-messages-on-ios-15-and-ipados-15 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:48:40 </td>
   <td style="text-align:left;"> $AAPL i’ll just wait until $1.00 to average down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:48:30 </td>
   <td style="text-align:left;"> $AAPL It only took 1 hour  to complete the cycle of turning RED.. Timmy Cook buy back worked.. $SPY PUTS ARE PRINTING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:46:11 </td>
   <td style="text-align:left;"> $AAPL i would take credit for being right all week but it was kinda predictable tbh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:45:25 </td>
   <td style="text-align:left;"> $AAPL Ukraine is toast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:45:22 </td>
   <td style="text-align:left;"> $AAPL can&amp;#39;t wait to upgrade my phone this year...same features different color.. its all I look forward to. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:44:46 </td>
   <td style="text-align:left;"> $AAPL if Kiev falls , that will be the crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:43:24 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $NVDA $MSFT 
SPY so far. Only 5.3% down from ATH.
- Jan 27: $431
- Feb 23: $416
- Next dip: $407 this month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:42:21 </td>
   <td style="text-align:left;"> Watch $amzn and $tsla drag $spy down .. once $aapl gives up 165 rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:40:29 </td>
   <td style="text-align:left;"> $AAPL Pump premarket, sell and short at open...rinse and repeat! $$$$$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:39:42 </td>
   <td style="text-align:left;"> $AAPL Low of the Day is coming..what a Joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:39:30 </td>
   <td style="text-align:left;"> $AAPL ….   Have a great day everyone!!! Peace! 2 Chronicles 7:14
If my people, which are called by my name, shall humble themselves, and pray, and seek my face, and turn from their wicked ways; then will I hear from heaven, and will forgive their sin, and will heal their land. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:38:41 </td>
   <td style="text-align:left;"> $AAPL don’t hold your breath bears. Just let it go. Pump incoming as usual </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:38:05 </td>
   <td style="text-align:left;"> $AAPL Nice green open tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:35:39 </td>
   <td style="text-align:left;"> $AAPL Nearing $166 there are more buyers than sellers today.  $168 by EOD as bears cover to close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:34:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $AAPL ... 
Joe Biden + Nancy Pelosi + the Squad = $10/gallon gas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:33:52 </td>
   <td style="text-align:left;"> $AAPL And he said economy is great on national tv. Fake news inventor. FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:33:40 </td>
   <td style="text-align:left;"> $AAPL tank hoe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:32:35 </td>
   <td style="text-align:left;"> $SPY Easy 100% play in less than an hour.
$TSLA $BA $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:32:07 </td>
   <td style="text-align:left;"> $AAPL Closing RED ,   In a red hot economy, 🇲🇽  🇨🇳   🌐 I feel sorry for your CALLS.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:31:58 </td>
   <td style="text-align:left;"> $TSLA $NVDA $QQQ $AAPL The truth is there hasn’t been a major technological development since the smart phone like 15 years ago. Tech was pumped on hype hype hype and now there is no longer any belief that significant new products will be unveiled. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:31:54 </td>
   <td style="text-align:left;"> $AMZN $BKNG $AMD $AAPL.  Not gonna be greedy.  Done. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:31:03 </td>
   <td style="text-align:left;"> $LABU $AAPL $TSLA $NFLX I decided not to watch the market today and you guys screwed it, I told you “don’t let me down” and hold the price😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:31:02 </td>
   <td style="text-align:left;"> $SPY $AAPL Can’t hold this forever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:31:01 </td>
   <td style="text-align:left;"> $SPY 

Look where $aapl rejected. Cloud EMAs 👌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:30:44 </td>
   <td style="text-align:left;"> $AAPL C’mon Apple finish strong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:30:00 </td>
   <td style="text-align:left;"> $AAPL 4hr view from the 2/27 weekend update. Calling for a move lower towards another blue box area where buyers are expected to appear #elliottwave #trading #apple #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:29:45 </td>
   <td style="text-align:left;"> $AMD vs $MSFT $AAPL.. notice the charts on some of these are diverging. Tech now that is holding is the biggest most liquid. $AMD is big but many semis rolling back down. $AMD is at the low for the week.  $AMAT $MU middle range. Stuff is bifurcated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:29:09 </td>
   <td style="text-align:left;"> $AAPL probably going to end up at 120-35 range by summer now. I may buy some there. Mayyybbeeee haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:28:36 </td>
   <td style="text-align:left;"> $AAPL Iphone SE 5G $$$$$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:28:15 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL) – Apple Analyst: Russian Sales Ban Signals Industrywide Trend https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-apple-analyst-russian-sales-ban-signals-industrywide-trend/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:27:55 </td>
   <td style="text-align:left;"> $AAPL historical market data for iPhone launches. Trying to find a similar one for “apple events”. Might have to plug it in myself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:27:42 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 2/20 weekend update presented to members at elliottwave-forecast.com/ called for a double correction lower to take place #elliottwave #trading #apple #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:26:42 </td>
   <td style="text-align:left;"> $AAPL RT no more! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:22:19 </td>
   <td style="text-align:left;"> $AAPL More sanctions on the way, Wall Street loves sanctions! $$$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:21:15 </td>
   <td style="text-align:left;"> $AAPL where’s the guy that said iPhone TA is useless ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:21:01 </td>
   <td style="text-align:left;"> $AAPL I would get out or sell calls tommorow we in $150s!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:20:51 </td>
   <td style="text-align:left;"> $AAPL A beacon of hope, till it isn&amp;#39;t </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:19:33 </td>
   <td style="text-align:left;"> $AAPL Only two stocks are green on mywatch list. AI and SPLK $$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:19:04 </td>
   <td style="text-align:left;"> $AAPL That&amp;#39;s right.  I don&amp;#39;t blame all you Russian sympathizers from selling AAPL short.  Russians can&amp;#39;t buy AAPL products. What&amp;#39;s a ruble worth today anyway. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:18:38 </td>
   <td style="text-align:left;"> $AAPL Option Alert.. 👀 👀  $170 Call for Friday, March 4. Roughly $5 Million dollars 🔥🔥🔥Learn more on StockOrbit!!! https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:17:51 </td>
   <td style="text-align:left;"> $AAPL #ABNB headed up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:17:49 </td>
   <td style="text-align:left;"> $AAPL Way too overpriced. Warren buffet should be selling. Old head doesn’t realize his own stock is too much. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:17:42 </td>
   <td style="text-align:left;"> $AAPL let’s go 165.5 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:17:41 </td>
   <td style="text-align:left;"> $AAPL LOAD UP! $$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:17:28 </td>
   <td style="text-align:left;"> $TSLA already breaking yesterdays low, $aapl near LOD, $spy should do a big red leg into final hour </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:16:09 </td>
   <td style="text-align:left;"> $AAPL Nothing going to stop this market! $$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:14:26 </td>
   <td style="text-align:left;"> $AAPL $SPY  Power hour.. brought to you directly from the Capital . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:14:13 </td>
   <td style="text-align:left;"> $AAPL horrible headwinds...sold everything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:14:11 </td>
   <td style="text-align:left;"> $AAPL this is the next Enron </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:12:34 </td>
   <td style="text-align:left;"> $AAPL just destroyed all weekly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:10:56 </td>
   <td style="text-align:left;"> $AAPL fall. There was no reason at all for it to be green in the first place lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:10:44 </td>
   <td style="text-align:left;"> $KHC I believe in this more than $AAPL $MSFT etc food is way more important than tech. From time to time people need a reminder. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:09:22 </td>
   <td style="text-align:left;"> Started a 100,000$ paper trading account that I’m going to practice micro technicals on. Using the Elliot Wave Theory only I am using apple to be my launchpad for this adventure. According to the theory $AAPL will be going down. You can always make money regardless of a stock going up or down. Next post is my position 
 
$AAPL $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:06:25 </td>
   <td style="text-align:left;"> $AAPL we had four years of worldwide calm, thx libtards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:05:04 </td>
   <td style="text-align:left;"> There are just no Buyers yet, the Sellers are dumping into a void, $AAPL  just 55m shares, $babab just 16m,  so there are just no Bids,.. Any Buying would give these a life but right now smart Buyers are letting the sales come to them 
 
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:04:31 </td>
   <td style="text-align:left;"> $AAPL When there is good news, this manipulated market always tanks and vice versa 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:04:07 </td>
   <td style="text-align:left;"> $AAPL in for a another swing. Looks like a bull setup if I&amp;#39;ve ever seen one 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:03:43 </td>
   <td style="text-align:left;"> $AAPL 
They waited until 166 to cover, that’s some balls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:03:03 </td>
   <td style="text-align:left;"> $AAPL 8th march event lmao. Besides, max pain running this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:02:33 </td>
   <td style="text-align:left;"> We will hit the third peak on this mystery stock soon. Easy right? Next post is the reveal. 
 
#ElliotWavesTheory  
 
Skip ahead to the results on my story only account here: 
www.Instagram.com/excellencecycle  
 
$BTC.X $SPY $AAPL $SOS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:02:10 </td>
   <td style="text-align:left;"> $aapl 165 put </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:01:08 </td>
   <td style="text-align:left;"> $AAPL $172.5 lottos only $0.04! If they pop tomorrow…🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 04:00:12 </td>
   <td style="text-align:left;"> $SPY gtfo bulls .. chart is self explanatory.  See y’all at lower 431 so $AAPL sell and leave before u lose money on calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:58:21 </td>
   <td style="text-align:left;"> In 2007 I used to have my kids pick stocks for me... 
 
https://www.youtube.com/watch?v=KCpIGUyWY-4&amp;amp;ab_channel=wallstrip 
 
$aapl $cmg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:58:18 </td>
   <td style="text-align:left;"> $AAPL 
Expecting a small covering rally here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:58:01 </td>
   <td style="text-align:left;"> $AAPL took 10 minutes  to dump $1.10 per share  but 6 hours to gain  a dollar 💵 THE  algos favor the BEARS 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:57:02 </td>
   <td style="text-align:left;"> $AAPL $MSFT knew my puts would print. Patience 🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:55:44 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Going to DROP hard over the next hour and few days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:55:41 </td>
   <td style="text-align:left;"> $AAPL Estonia ship hit ! Russia is trying to wage 3 WW!! Fuck Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:53:29 </td>
   <td style="text-align:left;"> $AAPL hey friends, use Honeygain to share your unused broadband DATA for BTC, proven payments below  updated 3/3/2022 check screenshot!!  
  
r.honeygain.me/DJYUJ4BA01 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:52:21 </td>
   <td style="text-align:left;"> $AAPL why did the Nasdaq decide to take a shit all of a sudden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:51:16 </td>
   <td style="text-align:left;"> $AAPL Am I the only one who actually dislikes this company?

Don&amp;#39;t get me wrong - I&amp;#39;m a bull and a philanthropist, and I hope everybody wins monetarily, so this isn&amp;#39;t meant to be spreading doubt.

But I ask the question again... Does anybody else actually LIKE their Apple products, or do they just use them because they&amp;#39;re expensive and provide a status symbol?

Genuine question coming from a place in the industry with sour sentiment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:50:48 </td>
   <td style="text-align:left;"> $AAPL 
Dumped my puts, bought mar 18 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:50:44 </td>
   <td style="text-align:left;"> $AAPL Cease fires </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:50:26 </td>
   <td style="text-align:left;"> $VOO $BTC.X $AAPL $TSLA https://youtu.be/fgcM-sm-b3g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:50:25 </td>
   <td style="text-align:left;"> $AAPL oversold . Long term holding is key and adding on dips is what I do 🖖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:49:48 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $SPY $QQQ Shit is about to get real. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:48:36 </td>
   <td style="text-align:left;"> $AAPL 
This dump came much earlier than I thought </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:48:13 </td>
   <td style="text-align:left;"> $AAPL Going to rip before close! $$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:48:01 </td>
   <td style="text-align:left;"> $AAPL hey friends, use Honeygain to share your unused broadband DATA for BTC, proven payments below  updated 3/3/2022 check screenshot! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:47:50 </td>
   <td style="text-align:left;"> I’ll be using apple as my launching pad of learning micro to match my  big picture skills. Join the adventure by throwing me a follow here or on www.instagram.com/excellencecycle where you can skip ahead. I’ve already posted the rest of todays lesson. 👌 
 
I’m starting simple with the #ElliotWavesTheory while I wait for $SOS to die $BTC.X. 
 
$AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:46:52 </td>
   <td style="text-align:left;"> $AAPL go red already apple need to close my puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:46:52 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:46:15 </td>
   <td style="text-align:left;"> $AAPL I refuse to believe there&amp;#39;s real people buying this so expensive.  You&amp;#39;re BOTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:45:32 </td>
   <td style="text-align:left;"> $SPY 

$aapl was late but they’re joining the party now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:45:29 </td>
   <td style="text-align:left;"> $AAPL Can&amp;#39;t hold it&amp;#39;s water, $168.00 should be a support level  ,but its a resistance level.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:45:28 </td>
   <td style="text-align:left;"> $AAPL calls have been wrung out through the ringer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:45:27 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Getting ready for Meower Hour ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:45:18 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:44:15 </td>
   <td style="text-align:left;"> Looks like Funds are selling?

$AMD $NVDA $QQQ $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:42:30 </td>
   <td style="text-align:left;"> $CCL $RCL $NCLH  
$AAPL $TSLA  
Fuel cost should not effect the Cruise industry until August, as all fuel was contractually bought on prices last November.   
I don’t think most stock holders know this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:42:16 </td>
   <td style="text-align:left;"> $AAPL Last hour is going to be interesting strap in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:40:32 </td>
   <td style="text-align:left;"> $AAPL this is next support ima add more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:40:03 </td>
   <td style="text-align:left;"> $AAPL 🤡: if we break price X then we’re going to price Y !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:38:43 </td>
   <td style="text-align:left;"> $AAPL I had latex0fbb6e7f404cb0f1368b10d3bc196b42AMD 552k (66% call/34% put)
$NVDA 299k (62% call/38% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:36:27 </td>
   <td style="text-align:left;"> $AAPL I’m ready for the meeting! 👩🏼‍💻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:35:43 </td>
   <td style="text-align:left;"> $AAPL 160 Friday ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:35:31 </td>
   <td style="text-align:left;"> $AAPL hmm, not looking too likely that it could cross 168 again this session. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:35:16 </td>
   <td style="text-align:left;"> $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:34:07 </td>
   <td style="text-align:left;"> $AAPL trying to form double bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:32:50 </td>
   <td style="text-align:left;"> $AAPL buying shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:31:58 </td>
   <td style="text-align:left;"> $AAPL 167.9 breaks and this sees 175 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:31:15 </td>
   <td style="text-align:left;"> $AAPL making support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:30:01 </td>
   <td style="text-align:left;"> $AAPL don&amp;#39;t get trap can&amp;#39;t even get a daily closing price at 166.50 resistance know your risk!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:29:53 </td>
   <td style="text-align:left;"> $AAPL 03/04/2022 CALLS WILL EXPIRE WORTHLESS. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:28:06 </td>
   <td style="text-align:left;"> $AAPL upside isn’t that great unless you have short term calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:27:29 </td>
   <td style="text-align:left;"> $AAPL should buy $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:27:04 </td>
   <td style="text-align:left;"> $AAPL breaking up adding to more longs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:26:41 </td>
   <td style="text-align:left;"> $GSAT Laughing at any naysayers, gonna be awesome when the $AAPL deal becomes public. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:26:12 </td>
   <td style="text-align:left;"> $AAPL - Short term move up to $169-171 before falling a bit lower... but then again, whatever the market makers decide. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:26:03 </td>
   <td style="text-align:left;"> $SPY $QQQ do my eyes deceive me or is this just $AAPL carrying the whole damn thing today 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:25:52 </td>
   <td style="text-align:left;"> $AAPL $MSFT Carrying such a load. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:25:45 </td>
   <td style="text-align:left;"> $AAPL Once my favorite stock, now a top short...How things change lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:24:45 </td>
   <td style="text-align:left;"> $AAPL $175 tomorrow. Momentum is your friend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:23:51 </td>
   <td style="text-align:left;"> $AAPL adding more shares here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:23:42 </td>
   <td style="text-align:left;"> $AAPL bullish above  anchored #VWAP - looking for a pop with all those 170c trading today for this Friday and next - note just went on a RAF buy signal &amp;gt;&amp;gt;  https://bit.ly/3qkmLjh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:23:41 </td>
   <td style="text-align:left;"> $ARKK you could have got a better return just holding $SPY and $AAPL and not even thinking about it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:23:38 </td>
   <td style="text-align:left;"> A Bullish Sign For Apple $AAPL, Meta $FB Platforms And PayPal  $PYPL Stocks: What The Charts Are Saying https://www.billionaireclubcollc.com/a-bullish-sign-for-apple-meta-platforms-and-paypal-stocks-what-the-charts-are-saying/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:21:59 </td>
   <td style="text-align:left;"> $AAPL If we break $168, sorry to all the PUTAS! Just pray we don’t break that level! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:21:43 </td>
   <td style="text-align:left;"> $AAPL 167.9 breaking next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:21:30 </td>
   <td style="text-align:left;"> $AAPL Apple Analyst: Russian Sales Ban Signals Industrywide Trend 

https://newsfilter.io/a/a49b32bbc1b1e9d8a8673c53f3b51a3c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-04 03:21:22 </td>
   <td style="text-align:left;"> $AAPL beast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:26:29 </td>
   <td style="text-align:left;"> $TSLA radiation levels just reported as normal at Ukraine nuclear plant... it&amp;#39;s all fear mongering guys...use the dip tomorrow to buy...fire was actually in an administrative building away from the reactors...dont let them scare you.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:26:11 </td>
   <td style="text-align:left;"> $TSLA 
Soon Tesla has to abandoned china factory. If  China plays 🤪.  Tesla below 500-.🎲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:26:10 </td>
   <td style="text-align:left;"> $SPY turn out it wasnt a nuke. $TSLA calm down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:25:56 </td>
   <td style="text-align:left;"> $TSLA with this shitty market I have decided to stop trading everyday.
I literally waited out the whole week just to bought 850 put 3/11 this morning for
2k/1ct. Same thing when tsla was below 800 and I added calls last Thursday. 
Be patient and wait for the right setup is the key I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:25:20 </td>
   <td style="text-align:left;"> $TSLA Joe hasn&amp;#39;t done jack shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:25:14 </td>
   <td style="text-align:left;"> $TSLA bankrupt by Easter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:25:13 </td>
   <td style="text-align:left;"> $TSLA buckle up. It’s going to get weird </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:24:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA and it’s disgusting that the US/EU and media should lead Ukrainians  to believe that fighting tanks w Molotov cocktails is some kind of strategy that will end well. It’s the height of irresponsibility. If Biden and the rest of them weren’t going to send troops, we should have pressed Zelensky to surrender immediately. Be realistic. Don’t tell them to fight tanks w these pathetic weapons and get themselves killed. I’m disgusted. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:23:49 </td>
   <td style="text-align:left;"> $TSLA 
I posted on different stock.🎲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:23:44 </td>
   <td style="text-align:left;"> $TSLA lmao at all the bulls crying 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:23:23 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:22:35 </td>
   <td style="text-align:left;"> $TSLA human beings.........the most intelligent and innovative species....Also the most self-destructive. 🙏 for sanity to return. Regardless of news, unless this breaks out over 925, they are merely seducing you with bull traps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:21:58 </td>
   <td style="text-align:left;"> $TSLA - Here’s the news for everyone that is clueless right now - 👇

https://www.zerohedge.com/markets/futures-tumble-report-ukraine-nuclear-power-plant-europes-largest-fire-after-shelling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:21:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

https://twitter.com/DmytroKuleba/status/1499543775240196099?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1499543775240196099%7Ctwgr%5E%7Ctwcon%5Es1_c10&amp;amp;ref_url=https%3A%2F%2Fsg.news.yahoo.com%2Frussian-troops-shell-ukrainian-nuclear-plant-010757408.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:21:28 </td>
   <td style="text-align:left;"> $TSLA damn 100 down tomorrow but definitely buying opportunity under 700 🦾🦾🦾.. Nuclear plant under fire.. bad for people there.. god bless them all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:20:58 </td>
   <td style="text-align:left;"> $TSLA any news on why it tanked? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:20:58 </td>
   <td style="text-align:left;"> $SPY they r bombing a nuclear power station?  ok now it&amp;#39;s time to send... $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:20:37 </td>
   <td style="text-align:left;"> $TSLA wtf happened here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:20:14 </td>
   <td style="text-align:left;"> $TSLA If we can take down the ISIS president, I think we can take down the Russian president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:19:19 </td>
   <td style="text-align:left;"> $TSLA nuclear plant on fire in Ukraine! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:19:07 </td>
   <td style="text-align:left;"> $TSLA whos still a bull here you had 10 years to be bullish 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:19:02 </td>
   <td style="text-align:left;"> $TSLA Musk was right, we need to GTFO this planet LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:18:41 </td>
   <td style="text-align:left;"> $TSLA how much down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:18:40 </td>
   <td style="text-align:left;"> $TSLA why it went down what news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:18:37 </td>
   <td style="text-align:left;"> $TSLA  My portfolio down 5% after market. They could have hold this nuclear news till market close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:18:33 </td>
   <td style="text-align:left;"> $TSLA bloody Friday tomorrow. You can thank mad Fock Putin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:18:31 </td>
   <td style="text-align:left;"> $TSLA people must really be in denial with what&amp;#39;s happening in this world. Tesla is the least of our problems </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:18:25 </td>
   <td style="text-align:left;"> $TSLA 🤘 You&amp;#39;d think he was one of our leaders with as much as he&amp;#39;s helped.  Much respect to the man. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:18:22 </td>
   <td style="text-align:left;"> $TSLA I saw 3, $100k+ yolo sweeps on 3/4/22 calls all at 870-890… if this breaks this low tomorow that’s ALOT of money gettin evaporated … damnn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:18:17 </td>
   <td style="text-align:left;"> $TSLA $SOFI $HOOD f*cking Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:18:01 </td>
   <td style="text-align:left;"> $TSLA sorry for those who bought 900 calls, they were sheap for a reason, 700/ 680 . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:17:54 </td>
   <td style="text-align:left;"> $BTC.X 5x your money with my call outs 😁💵💯👍 $XAU.CA $TSLA $SHIB.X $ETH.X https://youtu.be/XEJvGiNMkHQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:17:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Europe&amp;#39;s biggest nuclear plant shelled

https://www.9news.com.au/world/russia-ukraine-war-crisis-live-updates-latest-breaking-news-headlines-march-4-2022/0d8f5035-2fda-448e-9613-1c37876d11d9 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:17:10 </td>
   <td style="text-align:left;"> $TSLA if everyone buys puts, we all make $ right? LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:17:04 </td>
   <td style="text-align:left;"> $TSLA 680.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:16:56 </td>
   <td style="text-align:left;"> $TSLA  when this war started  
stock price crashed over night AH  
People bought puts  only to wake  to a green day  
just saying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:16:44 </td>
   <td style="text-align:left;"> $TSLA $SPY  are you buying calls in this market. Cmon fam 🤦🏼‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:15:50 </td>
   <td style="text-align:left;"> $TSLA which one is hiroshima, which Tokyo? No crater, no radiation problem, undamged buildings , unburned trees at groundzero, while miles from center concrete buildings blown away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:15:05 </td>
   <td style="text-align:left;"> $TSLA you idiots make it too easy. Welcome to the new market

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:14:21 </td>
   <td style="text-align:left;"> $TSLA fuck this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:14:17 </td>
   <td style="text-align:left;"> $TSLA These stupid Germans! If Tesla is gonna fack VE in Europe, then it&amp;#39;s gonna fack VW in Europe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:14:17 </td>
   <td style="text-align:left;"> $TSLA rip my calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:14:11 </td>
   <td style="text-align:left;"> $TSLA 😒https://youtu.be/K3ed7Sibgrk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:14:06 </td>
   <td style="text-align:left;"> $TSLA overreaction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:13:58 </td>
   <td style="text-align:left;"> $TSLA im not pissed coz i lost on calls for tomorrow. im pissed coz i ignored those puts i was looking at early today😑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:13:53 </td>
   <td style="text-align:left;"> $TSLA at this rate don&amp;#39;t even want to know what 2023 has in store </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:13:43 </td>
   <td style="text-align:left;"> $TSLA 750 tomorrow morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:13:37 </td>
   <td style="text-align:left;"> $SPY I’d like to take this time to thank…. Absolutely fucking nobody that’s who. I bought these puts all by myself and you can have them from me tomorrow at a pretty premium.

$TSLA $UPST $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:13:25 </td>
   <td style="text-align:left;"> $TSLA world in a chaos and bulls are chasing previous highs... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:13:18 </td>
   <td style="text-align:left;"> $TSLA 

Bears new job soon......

$5 is $5. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:13:05 </td>
   <td style="text-align:left;"> $TSLA low $700s tomorrow. It’s an EV company with a really good spokesperson. Dump it before it goes to $200 or less imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:12:46 </td>
   <td style="text-align:left;"> $TSLA hope they put the fire out. Doesn&amp;#39;t feel right making money on puts as the result of people dieing. 

The tesla bubble will burst regardless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:12:36 </td>
   <td style="text-align:left;"> $TSLA when I guarantee you something, you better fcking LISTEN. 🤑🤑🤑🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:12:20 </td>
   <td style="text-align:left;"> $AAL just FYI analysts recommending PTs know shit all. Buy low and sell high.

$GME $TSLA $MRIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:11:55 </td>
   <td style="text-align:left;"> $TSLA so no 900 tomorrow then ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:11:38 </td>
   <td style="text-align:left;"> $NCLH $MU $AMD $TSLA This is when everyone who is just worried about making money needs to get slapped upside the head, with what is now developing. You thought toilet paper was tough to find...The liberal woke white house was so worried about which bathroom to use and  staying out of ANY conflict that low and behold, a crazy man is about to nuke Europe... Integrity and character allows one to make very tough decisions in the face of chaos. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:11:13 </td>
   <td style="text-align:left;"> $TSLA public execution of Putin please! This cockroach needs to die! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:10:47 </td>
   <td style="text-align:left;"> $GOOGL no one gives a fuck about Ukraine !! Stop with this bs fud!!!! So fucking retarded $TSLA $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:10:39 </td>
   <td style="text-align:left;"> $TSLA 

Show me $1k already❤️❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:09:48 </td>
   <td style="text-align:left;"> I hate war ; does not matter who is right or wrong !!! Peace ☮️ to all world  
 
$spy $sofi $tsla $upst $pypl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:09:44 </td>
   <td style="text-align:left;"> $TSLA bulls ignored all current events and were greedy begging for more😗🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:09:32 </td>
   <td style="text-align:left;"> $TSLA to think i was literally looking at those lotto 820 puts. but i had to buy calls🤦🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:09:08 </td>
   <td style="text-align:left;"> $TSLA When russia/ukraine announced the war everything dropped hard that night and people did puts the next morning and lost $ lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:09:04 </td>
   <td style="text-align:left;"> $TSLA 

I like it when Sandy gets excited....

https://youtu.be/9z9xl8knLAk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:08:24 </td>
   <td style="text-align:left;"> latex7921f008e633e4d254e55c794b119eb4 
 
Short latexd2b36131b4a66f5c6550fa869ef4c21d 
Short latexcba03dc1757d69488addbcb945919c22 
 
$SPY $TSLA $BTC.X are being 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:06:07 </td>
   <td style="text-align:left;"> $TSLA went down to 819 after hours 😥😥😥😥😥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:05:57 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Nuclear power plant in Ukraine the largest in Europe is on fire and if it blows up will be 10 times worse then Chernobyl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:05:36 </td>
   <td style="text-align:left;"> $TSLA putin carpet bombing your calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:05:34 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB $BTC.X $TSLA Fighting near Nuclear plant knight king watching. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:05:33 </td>
   <td style="text-align:left;"> $TSLA I have puts here, but praying Ukraine doesn&amp;#39;t experience radiations from this nonsense. The entire war is just not right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:04:57 </td>
   <td style="text-align:left;"> $TSLA shit... they are detecting high levels of radiation coming from the Nuclear power plant. Europe maybe fucked depending on the wind </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:04:45 </td>
   <td style="text-align:left;"> $TSLA I got til March 25th with these calls 👀👀👀 lord be with me 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:04:39 </td>
   <td style="text-align:left;"> $TSLA 819$ in AM … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:04:35 </td>
   <td style="text-align:left;"> $TSLA why can’t we kill Putin? He needs to die and now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:04:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA  
 nuclear physicist  Galen Winsor swam in nuclear cooling water, ate plutonium, and didnt die of cancer or radiation. 
https://youtu.be/IZgu8jAkEPY?t=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:04:31 </td>
   <td style="text-align:left;"> $TSLA terrible company to hold at the current valuation levels.. you’re just asking for pain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:04:20 </td>
   <td style="text-align:left;"> $TSLA this is fucked &amp;amp; im bullish lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:03:28 </td>
   <td style="text-align:left;"> $TSLA It’s after hours 900 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:03:24 </td>
   <td style="text-align:left;"> $TSLA this so fucking ignorant. Down almost 10 percent today for bullshit headlines. So done with this idiotic market. Literally every little headline is a pump or dump. Mostly dump though of course. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:03:08 </td>
   <td style="text-align:left;"> $TSLA sheet. NQ futs may trigger a circuit breaker tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:03:07 </td>
   <td style="text-align:left;"> $COST $BA $TSLA $MSFT You just don’t put out a fire at a nuclear plant it’s not a simple house fire it may take hours if not days to put out and if you think Putin cares well I wouldn’t bank on it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:02:43 </td>
   <td style="text-align:left;"> $TSLA of course the first time I sell a put in my life the stock goes down 7% in one day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:02:01 </td>
   <td style="text-align:left;"> $TSLA when Russia announced official war about a week and a half ago, Tesla bounced back quickly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:01:45 </td>
   <td style="text-align:left;"> $TSLA WWW lll bout to jump off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:01:38 </td>
   <td style="text-align:left;"> $TSLA I legit got a 820 put for 1.90 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:01:27 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $840.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:00:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA A whole generation of investors will walk away from the market if this continues much longer. Nobody wants to invest in this kind of world, with bullies running the show and feckless leaders afraid to stand up to them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:00:39 </td>
   <td style="text-align:left;"> $TSLA if it is a reactor meltdown, well..... be prepared to see this dropping $250 premarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 09:00:38 </td>
   <td style="text-align:left;"> $TSLA i would’ve been fcked bigtime had i sold 840 puts😰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:59:48 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA 🙃🔪☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:58:55 </td>
   <td style="text-align:left;"> $TSLA It&amp;#39;s almost getting back to my buy zone. Maybe another 20% haircut. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:58:38 </td>
   <td style="text-align:left;"> $TSLA we may see 720 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:58:16 </td>
   <td style="text-align:left;"> $TSLA what’s the bell happened ????? Anyone any idea.. am holding shares no puts no calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:58:11 </td>
   <td style="text-align:left;"> It May Be Time For Stocks To Worry About A Recession https://mottcapitalmanagement.com/it-may-be-time-for-stocks-to-worry-about-a-recession/ $TSLA, $ZM $qqq $spy $ief </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:57:39 </td>
   <td style="text-align:left;"> $TSLA capitulation starting right before 8pm close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:57:36 </td>
   <td style="text-align:left;"> $TSLA why any of you guys purchase calls and hold overnight during these times is truly baffling. Be defensive and at the very least hedge your positions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:57:33 </td>
   <td style="text-align:left;"> $TSLA Markets AH crashing cus of attack on Nuclear Power Station in Ukraine - The building on fire is actually an office block and NOT the reactor - But i guess the market will use this BS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:57:16 </td>
   <td style="text-align:left;"> $TSLA whoever bought puts I give you hella credit wow just WOW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:57:11 </td>
   <td style="text-align:left;"> $TSLA https://www.cnn.com/2022/03/03/tech/spacex-starlink-ukraine-internet-security-risks-scn/index.html SpaceX sent Starlink internet terminals to Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:56:57 </td>
   <td style="text-align:left;"> $TSLA judging by how futes are reacting the nuclear plant that was shelled and on fire maybe a serious matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:56:49 </td>
   <td style="text-align:left;"> $TSLA guess he’s retesting 800 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:56:32 </td>
   <td style="text-align:left;"> $TSLA fill the gap to $800 after that explode to $1000🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:56:23 </td>
   <td style="text-align:left;"> $TSLA This world is going to shit exponentially quick. SMH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:56:02 </td>
   <td style="text-align:left;"> $TSLA why is it dropping hard? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:55:55 </td>
   <td style="text-align:left;"> $TSLA wow I got too greedy NGL bought the dip and getting burned 😓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:55:27 </td>
   <td style="text-align:left;"> $TSLA did a Tesla go off in Ukraine? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:54:59 </td>
   <td style="text-align:left;"> $TSLA  https://apnews.com/article/russia-ukraine-war-a3092d8e476949ed7c55607a645a9154 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:54:24 </td>
   <td style="text-align:left;"> $TSLA a question for the smart nerdy tesla traders here? Why we need a market maker? Bid and ask is enough from the participants. Why we need a third party who just pullss money from the market? Everything is done by computers, why would we need these market makers? W </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:54:24 </td>
   <td style="text-align:left;"> $TSLA https://www.teslarati.com/tesla-giga-fest-gigafactory-texas-travis-county-fire-marshal-review/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:54:11 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m going to die rich comrades, Ukainians should have listened to Putin while they had the chance instead of their NATO puppets.  
 
Now get ready for Chernobyl 2.0. Nuclear holocaust. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:54:07 </td>
   <td style="text-align:left;"> $TSLA This Russia BS is getting old. Someone needs to donkey kick the shit out of Putin&amp;#39;s sorry ass 🤬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:54:06 </td>
   <td style="text-align:left;"> $TSLA LMAO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:54:00 </td>
   <td style="text-align:left;"> Measured over the past 5 years, $TSLA shows a very strong growth in EPS. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:53:43 </td>
   <td style="text-align:left;"> $TSLA do you Guys know why after hours is dropping? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:53:43 </td>
   <td style="text-align:left;"> $TSLA fuvking manipulated hunk of shit lately! Same shit happened last year after hittin ath. Almost time to cash these casino chips in and call it a day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:53:30 </td>
   <td style="text-align:left;"> $TSLA US is screwed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:53:26 </td>
   <td style="text-align:left;"> $TSLA just be 8 already so I don’t have to see this destroy my calls til 4 am 😂😵‍💫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:52:56 </td>
   <td style="text-align:left;"> $TSLA $SOFI $PLTR 
Times like these when this matters: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:52:55 </td>
   <td style="text-align:left;"> $SPY no worries 😉 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:52:46 </td>
   <td style="text-align:left;"> $TSLA $SPX $VIX fire at nuk plant in Ukraine after bombing 

https://edition.cnn.com/europe/live-news/ukraine-russia-putin-news-03-03-22/h_a5e70ac737edac9e23afda01b8f50dd6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:52:21 </td>
   <td style="text-align:left;"> $TSLA go to $800 fuck it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:50:53 </td>
   <td style="text-align:left;"> $COST $AAPL $TSLA  European nuclear plant on fire https://www.independent.co.uk/news/world/europe/russia-ukraine-news-putin-war-b2028080.html?amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:49:47 </td>
   <td style="text-align:left;"> $TSLA 700 tomorrow Russians bowing up largest nuclear plant in Europe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:47:54 </td>
   <td style="text-align:left;"> $TSLA maybe those 830 puts weren’t so bad after all😔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:47:33 </td>
   <td style="text-align:left;"> $TSLA so I never let my call expire OTM but has anyone tried doing it with Tesla … just curious.. I’m just thinking it’ll expire worthless right cause right now I’m down bad but never tried letting it expire to see what will happen .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:47:23 </td>
   <td style="text-align:left;"> $TSLA why this have to sell off more than the overall market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:46:53 </td>
   <td style="text-align:left;"> $TSLA anytime you want to bring back the orange man I’d be happy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:46:41 </td>
   <td style="text-align:left;"> $RIVN $TSLA $GGPI $MRVL $GPS Watch as 10+Year Tesla Bull Ross Gerber discusses the Problems with Rivian’s Production Strategy &amp;amp; Compares and Contrasts Rivian’s Production Strategy to that of Tesla’s Early Year Production &amp;amp; Ramping! “MASSIVELY OVERVALUED! WARNING To Investors!”👇👀✅

WATCH NOW: https://youtu.be/sgU5BMMTfa4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:46:18 </td>
   <td style="text-align:left;"> $TSLA If a nuclear plant explodes, it still won&amp;#39;t be as big of an explosion as this Tesla bubble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:45:51 </td>
   <td style="text-align:left;"> $TSLA why TF is anyone surprised? Tomorrow is a Friday.. Tesla is red on Friday’s. Literally every Friday. Are y’all that stupid? My puts left for tomorrow are gonna be JUICY AF. 🤑🤑🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:45:30 </td>
   <td style="text-align:left;"> $TSLA not looking good. $750 maybe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:44:46 </td>
   <td style="text-align:left;"> $TSLA $830 😱 it’s going back to $700! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:44:44 </td>
   <td style="text-align:left;"> $TSLA why market down after hour? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:43:53 </td>
   <td style="text-align:left;"> $TSLA 

Nothing new ! Tesla is the most innovative company of the century, the stock is the most shorted one !  One would think such an amazing company investors want to be part of Investing in the future looking forward yet this has been under Biden &amp;amp; followers siege bashed discredited and massively shorted !! 

For those who argue “well Biden likes Union “ I say fine but just because you got so much money n support from Union that doesn’t mean to go ahead and write off half of American ppl ! You have fiduciary duty to all !! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:42:18 </td>
   <td style="text-align:left;"> $TSLA ignorant bastards they&amp;#39;re shooting at nuclear plant </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:41:21 </td>
   <td style="text-align:left;"> $VLD $TSLA  &amp;quot;Does Elon Musk text or email me?
No, he just calls me directly.&amp;quot;
Benjamin Buller, Velo3D CEO

https://cheddar.com/media/metal-3d-printing-spacex-vendor-velo3d-ceo-on-q4-revenue-jump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:40:47 </td>
   <td style="text-align:left;"> $TSLA pt 8869 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:39:37 </td>
   <td style="text-align:left;"> $AMD $SPY $QQQ $GOOGL $TSLA 
I have to be the investor of the year 
Puts printing. I called it 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:38:45 </td>
   <td style="text-align:left;"> $TSLA i just bought wti futures and already up 1200$. Damn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:37:57 </td>
   <td style="text-align:left;"> $TSLA Who&amp;#39;s ready for a Chernobyl 2.0? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:37:41 </td>
   <td style="text-align:left;"> $TSLA you know it’s fuct when the disillusioned permabulls start talking about their 2025 price targets 🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:36:31 </td>
   <td style="text-align:left;"> $TSLA what F just happen at 7? future down almost 100. LOL, today i bought calls for tomorrow and will be f*ked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:35:00 </td>
   <td style="text-align:left;"> $TSLA tomorrow be like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:34:19 </td>
   <td style="text-align:left;"> $TSLA if they lose the water contract tomorrow i expect a -10% day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:32:05 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-03 Technical Analysis Video: 
https://www.youtube.com/watch?v=7nSXlbo-Xcw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:31:43 </td>
   <td style="text-align:left;"> $TSLA https://electrek.co/2022/03/03/panasoni-large-battery-cell-factory-in-us-supply-tesla-demand-repor/ 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:30:43 </td>
   <td style="text-align:left;"> $TSLA https://www.nbcnews.com/news/world/volunteers-cross-polish-border-ukraine-fight-russian-forces-rcna18619 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:29:46 </td>
   <td style="text-align:left;"> $TSLA muskrat called for recession. Self fulfilling prophecy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:26:47 </td>
   <td style="text-align:left;"> $TSLA Rouge is such a nice color for this stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:25:33 </td>
   <td style="text-align:left;"> $TSLA Union f*** no. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:25:17 </td>
   <td style="text-align:left;"> $AABB $AMZN $AAPL $TSLA $MSFT $AABB Gold/Global Exchange/NFT&amp;#39;s! https://www.fool.com/ext-content/amazon-ceo-says-his-company-will-go-bankrupt/?utm_source=investingchannel&amp;amp;utm_medium=contentmarketing&amp;amp;utm_campaign=ai-ceobankrupt&amp;amp;aid=8976&amp;amp;paid=8976&amp;amp;waid=8976&amp;amp;source=esaiclwdg0500004&amp;amp;psource=esaiclwdg0500004&amp;amp;wsource=esaiclwdg0500004&amp;amp;utm_content=IM0101&amp;amp;testId=ai-ceobankrupt&amp;amp;cellId=2&amp;amp;campaign=sa-ai </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:25:03 </td>
   <td style="text-align:left;"> $TSLA me and my girl after I buy more tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:24:26 </td>
   <td style="text-align:left;"> $TSLA so now Europe is facing the potential of a nuclear meltdown.  So much for GigaBerlin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:22:58 </td>
   <td style="text-align:left;"> $TSLA leave it to the Russians to start bombing a nuclear plant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:22:57 </td>
   <td style="text-align:left;"> $TSLA ZAPORIZHZHIA NUCLEAR POWER PLANT IN UKRAINE IS ON FIRE AFTER ATTACK BY RUSSIAN TROOPS, MAYOR OF LOCAL TOWN SAYS -RTRS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:21:40 </td>
   <td style="text-align:left;"> $ELON.X holding 1.5 bil coins and counting. Easy 100x from here by at least 2023, musk owns this thing he&amp;#39;ll make it the interplanetary space currency. $TSLA $SPCE $ASTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:21:21 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/ZekeJMiller/status/1499536918115147783?s=20&amp;amp;t=mg71e9xDkT-VAimXqsH6xg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:19:51 </td>
   <td style="text-align:left;"> $TSLA this gonna open bloody below 823 ain’t it time to buy more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:19:38 </td>
   <td style="text-align:left;"> $MULN HOLD THE FLOAT BOIS! WE COMING FOR U ELON $TSLA $GME $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:18:52 </td>
   <td style="text-align:left;"> $TSLA face ripper tomorrow..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:15:46 </td>
   <td style="text-align:left;"> $TSLA Tesla Fanboys you are about to be left in shambles... want a light? Party is over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:13:59 </td>
   <td style="text-align:left;"> $TSLA the whales are buying the dip probably that&amp;#39;s why it&amp;#39;s up AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:13:28 </td>
   <td style="text-align:left;"> $TSLA Saw it coming…🩸😈
Free discord in bio! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:11:34 </td>
   <td style="text-align:left;"> Rivian Drops Unpopular Move That Could Benefit Tesla, GM and Ford

$RIVN $TSLA $GM $F

https://www.thestreet.com/technology/rivian-drops-unpopular-move-that-could-benefit-tesla-gm-and-ford </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:11:05 </td>
   <td style="text-align:left;"> $TSLA Elon Musk Sends an Important Warning to Ukrainians

https://www.thestreet.com/technology/elon-musk-sends-an-important-warning-to-ukrainians </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:10:28 </td>
   <td style="text-align:left;"> $TSLA going to lose my virginity again when this finally passes 900, god remember the world when our biggest problem was Elon blowing the quarterly call?!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:10:09 </td>
   <td style="text-align:left;"> $TSLA think of Tesla worth in 2025. It will be at least around 4K. doesn&amp;#39;t matter if it&amp;#39;s 800 or 1200 now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:05:39 </td>
   <td style="text-align:left;"> $TSLA oh meant to post bearish

Forgot I dont like this stock anymore

🙂🙂📉👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:05:28 </td>
   <td style="text-align:left;"> $DWAC  $TSLA since Reagan let all our biz outsource. we can&amp;#39;t build anything but Tesla at home&amp;gt; 
 
&amp;quot;Russia says it will no longer send rocket engines to U.S.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:04:47 </td>
   <td style="text-align:left;"> $TSLA that 850 breakdown was so sweet

Except im an idiot and only scalped 4 pts from the 17 pt move

😢😢📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:03:23 </td>
   <td style="text-align:left;"> $TSLA 750 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:03:19 </td>
   <td style="text-align:left;"> $TSLA $900 open tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:01:55 </td>
   <td style="text-align:left;"> $TSLA long over/short under 850 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:01:31 </td>
   <td style="text-align:left;"> $TSLA please get this over 900 please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 08:01:28 </td>
   <td style="text-align:left;"> $TSLA futures ripping, Tesla dripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:59:48 </td>
   <td style="text-align:left;"> $TSLA bears be ready to get anal raped tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:59:25 </td>
   <td style="text-align:left;"> $TSLA Tesla stock is acting incredibly weak and pathetic, much like Joe Biden $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:59:11 </td>
   <td style="text-align:left;"> $TSLA 810 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:58:53 </td>
   <td style="text-align:left;"> $TSLA  cuz bears want 800 we moon to 900 tomorrow 🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:58:52 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $840.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:58:17 </td>
   <td style="text-align:left;"> $TSLA dead money.. interest is gone. No forward looking catalyst. Probably time to dump and run imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:58:16 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #3 ticker with sweep activity where institutions are trading options urgently with 35.2K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:57:02 </td>
   <td style="text-align:left;"> $tsla this pig is going to bring down the whole market...*insert Titanic theme song* never let go jack.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:55:46 </td>
   <td style="text-align:left;"> $TSLA wow now a union lmfao 

https://www.reuters.com/business/autos-transportation/tesla-chief-musk-invites-union-uaw-hold-vote-california-factory-2022-03-03/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:55:34 </td>
   <td style="text-align:left;"> $TSLA wen moon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:54:54 </td>
   <td style="text-align:left;"> $TSLA 500k calls above the ask at the close 🚀 . Nobody would risk that much for no reason 🏎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:53:21 </td>
   <td style="text-align:left;"> $TSLA will wake up to news giga Berlin delayed because of water provider. 

Elon usually gets in on the pumping via liking tweets of rumoured openings he hasn&amp;#39;t this time because he knows it will be delayed further. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:53:21 </td>
   <td style="text-align:left;"> $TSLA $TSLA - welp Bulls - double bottom thesis was invalidated today as prev day low of $844 was broken with a move lower - however I&amp;#39;m still bullish near term - this is why I open starter positions to begin &amp;amp; then scale in - never all in - futes are green &amp;amp; price is slowly climbing in AH - lets see how were holding up in pre market 🔎 
 
https://discord.com/invite/uQ5UXZW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:52:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA 🥲🥲 just me? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:49:40 </td>
   <td style="text-align:left;"> latex28b43c27f0f0e52e4778585fcd48f408$HOLE. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:48:58 </td>
   <td style="text-align:left;"> $TSLA watch this. https://youtu.be/nvocqyRBiRc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:48:39 </td>
   <td style="text-align:left;"> $TSLA What a horrible day it has been across the entire market. When will we be able to stop bleeding? I&amp;#39;m completely fed up with this. This market is so bad that I&amp;#39;m almost ready to sell all of my fucken stock and get out of it. Everyday we bought in dip and MF stock dipping again. Omg. I&amp;#39;m completely speechless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:48:07 </td>
   <td style="text-align:left;"> $TSLA why would the Germans hold a news conference just to announce set backs and additional conditions? This must be a bold statement to its citizens about the reliance on foreign oil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:44:44 </td>
   <td style="text-align:left;"> $TSLA  
Latest episode of the Rise of Tesla series now available. 
 
See how Tesla did the impossible yet again in 2020 a year with many challenges. 
 
https://www.youtube.com/watch?v=vxFRzkC9Vz0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:44:36 </td>
   <td style="text-align:left;"> $TSLA $50-60 push upwards tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:44:23 </td>
   <td style="text-align:left;"> $SPY bull until 430 is broken to downside. Growth still getting hammered. Keep an eye on $NVDA abd $TSLA ..further downside on those names likely gets us back to retest last weeks low </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:44:02 </td>
   <td style="text-align:left;"> $TSLA this is gonna fly tomorrow 🚀 big flow exactly at 3:59PM 500k calls for $950 strike 5/20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:42:30 </td>
   <td style="text-align:left;"> $TSLA Relative weakness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:41:30 </td>
   <td style="text-align:left;"> $TSLA dead money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:41:16 </td>
   <td style="text-align:left;"> $AMZN $TSLA $TLT $AAPL $QQQ  
Economic Events Calendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:38:46 </td>
   <td style="text-align:left;"> $TSLA TSLA Stock Price Prediction and Analysis for Tomorrow Friday March 4th
https://youtu.be/6WERPLdtsME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:38:19 </td>
   <td style="text-align:left;"> EV technical analysis for tomorrow. 
 
$TSLA $LCID $NIO $RIVN  
 
https://youtu.be/azKNxtrOv4w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:34:52 </td>
   <td style="text-align:left;"> $TSLA 700 won&amp;#39;t hold next time, 
when tesla bulls sees oil-price as something positive, thats how you know what bubble this is. There is a bigger picture than just tesla-world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:34:31 </td>
   <td style="text-align:left;"> $TSLA did the bears come out the woodwork today ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:34:28 </td>
   <td style="text-align:left;"> $ARKK $TSLA $SPY $NASDAQ Literally the same pattern every day for stocks. They crash them all during the day, then buy them up at the last 30 minutes to make people think the next day will be green, and use the shares that they bought to dump massively at open and create a ripple effect of selling throughout the day, which makes their puts print! 
 
Let’s play the same game they are playing ! PUTS TO THE MOOOON! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:33:43 </td>
   <td style="text-align:left;"> $SPY $TSLA  today sucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:31:22 </td>
   <td style="text-align:left;"> $TSLA long term investor are buying this up like hot cake. Tesla bot 🤖 coming soon end of the year prototype </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:29:19 </td>
   <td style="text-align:left;"> $TSLA wait till Elon announces a dividend 📈📈📈🙆‍♂️🙆‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:28:47 </td>
   <td style="text-align:left;"> $TSLA tomorrow 9:30 Berlin press conference. 

This might be the last approval they are talking of. This also has the decision tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:27:37 </td>
   <td style="text-align:left;"> $TSLA 🚨🚨 someone tell me it’s going to $1000 tmr 📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:24:38 </td>
   <td style="text-align:left;"> $TSLA 

Corrupt Cramer is a part of this big Corruption our country is suffering from !! 

Huge set back for the United State of America on all levels !! 

Hitting the foundation from  innovation to growth Tech by attacking these companies, shorting their stocks and becoming so hostile not business friendly -is nothing short of 
UN-AMERICAN  ! Bad consequences awaiting !! 

Sadly 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:24:32 </td>
   <td style="text-align:left;"> $TSLA These stupid germans. What additional evidence do they require? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:23:38 </td>
   <td style="text-align:left;"> $TSLA Oil going up up up…TSLA will follow. Buy buy buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:23:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla&amp;#39;s Musk Invites UAW to Hold Vote in California https://www.stck.pro/news/TSLA/23791583 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:21:50 </td>
   <td style="text-align:left;"> $TSLA The retail 🤡s believe this runs much higher than $1200+ where Elon was selling billions.  Okee-dokee. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:20:14 </td>
   <td style="text-align:left;"> $AMZN $TSLA $SPY

ONLY SOLUTION IS UKRAINE SHD NOT SUCK UP TO WEST ESPECIALLY USA WHICH IS WHAT THREATENS RUSSIA AND EVEN CHINA. TRUSTWORTHY NEIGHBORS ARE IMPORTANT FOR YOUR GROWTH. 

We always HEAR one sided MSM.

https://twitter.com/wandererali/status/1499466227240271872?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:19:34 </td>
   <td style="text-align:left;"> $TSLA not sure if my 850 callls would print. but got it before EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:19:17 </td>
   <td style="text-align:left;"> $TSLA Guys want to know why there was so many calls bought for $900 strike 😌 
https://insideevs.com/news/571198/tesla-final-approval-german-factory/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:17:29 </td>
   <td style="text-align:left;"> I stand with Russia. Elon Musk is too concerned with interjecting himself into politics. This is why $FSR will outpace $TSLA by a large margin in the long term! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:17:21 </td>
   <td style="text-align:left;"> $TSLA looks like TSLA received final approval - https://insideevs.com/news/571198/tesla-final-approval-german-factory/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:13:22 </td>
   <td style="text-align:left;"> $TSLA 🔻🔻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:12:23 </td>
   <td style="text-align:left;"> $TSLA if giga is 100% approved. We will open 890-900 1000% tmrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:11:57 </td>
   <td style="text-align:left;"> $TSLA 

So do fanboys just sit around swallowing tide pods while waiting 12 hrs for their vehicle to charge?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:10:19 </td>
   <td style="text-align:left;"> $TSLA everything crashed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:09:16 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-03 Daily Forecast Video: 
https://www.youtube.com/watch?v=U74RRaUUkeo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:08:35 </td>
   <td style="text-align:left;"> $TSLA fuck you tesla what a piece of trash stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:07:59 </td>
   <td style="text-align:left;"> $ROKU $TSLA $SHOP it&amp;#39;s all down hill from here... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:07:45 </td>
   <td style="text-align:left;"> $MULN $AMC $GME $TSLA  
https://youtu.be/nvocqyRBiRc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:06:58 </td>
   <td style="text-align:left;"> $TSLA who the Fck said dark wall at $830? Lmfaoo… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:04:13 </td>
   <td style="text-align:left;"> $TSLA Tesla Fanboys.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:03:38 </td>
   <td style="text-align:left;"> Panasonic planning massive battery plant in U.S. to supply Tesla

It’s not going to be Oklahoma with that dumb law they just passed. 

$TSLA $SPY

https://financialpost.com/pmn/business-pmn/panasonic-planning-massive-battery-plant-in-u-s-to-supply-tesla-nhk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:03:23 </td>
   <td style="text-align:left;"> $TSLA all this does is go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:02:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK

No tide pod swallowing fanboy or liberal will ever convince me to go electric. It’s gasoline all day for me babe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 07:02:00 </td>
   <td style="text-align:left;"> $TSLA stupidest shit in the world here. “950 eod” is said everyday. Garbage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:59:55 </td>
   <td style="text-align:left;"> $TSLA you are missing the FOASS on Muln stock. Look how much the stock is shorted.
https://nakedshortreport.com/company/MULN

Outstanding shares 34.94 million
https://finance.yahoo.com/quote/MULN/key-statistics/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:57:28 </td>
   <td style="text-align:left;"> $TSLA $AMD tomorrow should be fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:57:22 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ Can someone ask the twitter bot that tracks Elon&amp;#39;s plane, to create a twitter account to track Pelosi&amp;#39;s trades. That would be helpful :-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:56:50 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $TSLA $AAPL  
 
You knew the top was in when all the scoundrels at the FED were cashing out and retiring! 
 
They ain&amp;#39;t no dummies!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:56:14 </td>
   <td style="text-align:left;"> $TSLA $1200 by July </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:54:09 </td>
   <td style="text-align:left;"> $TSLA In this market I don’t see how Tesla gets back to $1200! IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:53:00 </td>
   <td style="text-align:left;"> The Altman-Z score of $TSLA is much better than the industry average of 2.55. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:52:44 </td>
   <td style="text-align:left;"> $TSLA 

I’m downgrading this market to sub junk rating equivalent to UAW-UNION !!  

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:51:46 </td>
   <td style="text-align:left;"> $TSLA the more batteries the merrier 😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:50:36 </td>
   <td style="text-align:left;"> $TSLA As a high iQ Individual, I can tell you that Tesla valuation has peaked. Only lower from here. Don’t shoot the messenger $DWAC $RSX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:50:08 </td>
   <td style="text-align:left;"> $TSLA love the company. don&amp;#39;t love the stock at the moment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:50:07 </td>
   <td style="text-align:left;"> $TSLA MULN has the most blatant market manipulation ever seen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:48:21 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $NASDAQ $NVDA 
Market is down by lazy Americans 🤦🏻‍♀️

Economy likely added 440,000 jobs in February – but labor shortage persists
https://www.marketwatch.com/story/economy-likely-added-440-000-jobs-in-february-but-labor-shortage-persists-11646317194 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:45:07 </td>
   <td style="text-align:left;"> $TSLA So, where do we close tomorrow? Lots of calls opened at $900...Do we get there tomorrow? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:43:26 </td>
   <td style="text-align:left;"> $TSLA 

&amp;quot;If an adversary has a specialized plane aloft, it can detect [a satellite] signal and home in on it,&amp;quot; Nicholas Weaver, a security researcher at the University of California at Berkeley, said via email. &amp;quot;It isn&amp;#39;t necessarily easy, but the Russians have a lot of practice on tracking various signal emitters in Syria and responding. Starlink may work for the moment, but anyone setting a [Starlink] dish up in Ukraine needs to consider it as a potential giant target.&amp;quot;

https://edition.cnn.com/2022/03/03/tech/spacex-starlink-ukraine-internet-security-risks-scn/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:43:16 </td>
   <td style="text-align:left;"> $TSLA should be so much cheaper I hate this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:41:55 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:41:26 </td>
   <td style="text-align:left;"> $TSLA do you think we can get into the 860 range tomorrow ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:41:18 </td>
   <td style="text-align:left;"> $SPY we might get black Friday sake tomorrow and also cyber Monday aswll... $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:40:01 </td>
   <td style="text-align:left;"> $TSLA unseen footage from Tuesday night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:38:22 </td>
   <td style="text-align:left;"> $TSLA this price may be your last chance to buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:37:24 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:37:16 </td>
   <td style="text-align:left;"> $TSLA 🐻🐻🐻🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:35:17 </td>
   <td style="text-align:left;"> $TSLA Watch us all get face f**ked tomorrow ... It&amp;#39;s going to most likely spike to 865 tomorrow morning and then drop to 840. Its going to burn all 820&amp;#39;s(P) and 880&amp;#39;s (C). Cut your loses/gains when you can..lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:34:57 </td>
   <td style="text-align:left;"> $TSLA Lets Go Brandon!! You are doing great. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:34:04 </td>
   <td style="text-align:left;"> $TSLA reverse split incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:33:37 </td>
   <td style="text-align:left;"> $TSLA GIGA BERLIN approved ~!~!~!~!~!!~! announcement tomorrow market open time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:33:34 </td>
   <td style="text-align:left;"> $TSLA be careful it’s going back to $700!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:32:35 </td>
   <td style="text-align:left;"> I get excited when I see a $lcid air or $rivn truck on the road now. I don’t even think twice when I see a $tsla. 
 
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:32:25 </td>
   <td style="text-align:left;"> $TSLA mm playing games as usual. drop it $50 to go back up $10 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:32:14 </td>
   <td style="text-align:left;"> $TSLA The reason the President never mentions Tesla is because they are not union.....No need to get upset.....Just keep doing what you do.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:32:05 </td>
   <td style="text-align:left;"> $TSLA fuck berlin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:32:05 </td>
   <td style="text-align:left;"> $TSLA Giga Berlin tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:32:01 </td>
   <td style="text-align:left;"> Panasonic $PCRFY will reportedly construct a US battery factory to supply Tesla $TSLA according to Bloomberg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:31:45 </td>
   <td style="text-align:left;"> $TSLA Giga Berlin tomorrow :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:31:26 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:30:58 </td>
   <td style="text-align:left;"> $TSLA foreign markets fleeing to US market. Great buying opp today especially for Uber lyft airlines oil sofi chase afFirm tesla upstart and Deutsche bank (not American but still good grab). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:30:14 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-03 Largest Trades Data: 
https://www.youtube.com/watch?v=U9XdqMo1HpA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:29:21 </td>
   <td style="text-align:left;"> $TSLA 🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:29:09 </td>
   <td style="text-align:left;"> $TSLA I’m bak! Who still saying “$900 eod” 🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:28:58 </td>
   <td style="text-align:left;"> $TSLA 
To the moon!🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:28:33 </td>
   <td style="text-align:left;"> $TSLA is that administration now going to buy oil from Iran ………… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:28:25 </td>
   <td style="text-align:left;"> $TSLA it’s just an EV company </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:28:15 </td>
   <td style="text-align:left;"> $TSLA NATO (USA) know that Ukrainian people and it’s foreign civilian helpers don’t have a chance against Russia. It is a total hypocrisy what NATO USA is doing by only watching. It should tell everyone in Ukraine to move to NATO countries to save their life. Civilian attacking Russia will cause more casualties. Without NATO troops there is no chance to defeat Russia. It is mind blogging that NATO is not putting out this information . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:28:04 </td>
   <td style="text-align:left;"> $TSLA if Tesla was just an EV company I would sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:26:49 </td>
   <td style="text-align:left;"> $TSLA did some of y&amp;#39;all load up on some Friday calls right before close? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:26:07 </td>
   <td style="text-align:left;"> $TSLA 870 close tm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:25:41 </td>
   <td style="text-align:left;"> $TSLA Jobs report Friday (400K + Feb-Consesnsus) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:24:54 </td>
   <td style="text-align:left;"> #SP500 Today &amp;#39;s HeatMap of  market stocks: $GOOG 
$GOOGL $AMZN $TSLA $AAPL 
  
finscreener.org/map/map </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:24:50 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING!! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:22:00 </td>
   <td style="text-align:left;"> $HRL Watch this Everyone WATCH CLOSELY , $TSLA $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:21:39 </td>
   <td style="text-align:left;"> $TSLA | Panasonic&amp;#39;s New US EV Battery Factory Likely To Be Large-Scale, Cost A Few Billion Dollars And Supply Tesla - NHK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:19:40 </td>
   <td style="text-align:left;"> $TSLA with inflation running hot and the Fed tightening, who the fuck is going to spend $60k-$70k on these shit boxes when you can buy something substantially better for the same price? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:17:37 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:17:17 </td>
   <td style="text-align:left;"> $TSLA I got a few CALLs up and down the 850-880 range expiring tomorrow. They&amp;#39;re like four figure lottery tickets at this point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:16:14 </td>
   <td style="text-align:left;"> $TSLA honest pt tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:15:52 </td>
   <td style="text-align:left;"> $ESTC this is fucking too good for low float .. $SOFI $AMC $TSLA .. $100

 Revenue of $223.9M, +43% YoY &amp;amp; beats consensus by $14.2M
Non-GAAP EPS of $0.12 &amp;amp; beats consensus by $0.08
Net dollar retention rate up QoQ &amp;amp; just below 130%
Adj FCF of $15.8M
Guiding next quarter revenue growth +30.1% YoY at midpoint </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:15:45 </td>
   <td style="text-align:left;"> $TSLA - Panasonic to build U.S. battery plant to supply TESLA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:14:34 </td>
   <td style="text-align:left;"> $TSLA tesla will be in big trouble if they unionize. nothing worse than lazy unionized employees. they destroy every company they work for. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:13:29 </td>
   <td style="text-align:left;"> $TSLA 700s tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:12:08 </td>
   <td style="text-align:left;"> $MULN 
$TSLA $RIVN $LCID check this out, future ay right here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:10:38 </td>
   <td style="text-align:left;"> $TSLA The descending triangle seems to be holding.  This year is going to be miserable for the overall market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-04 06:10:24 </td>
   <td style="text-align:left;"> $ESTC Monster earning and guidance.. best entry ever for low float stock after beating on earning and didn’t shoot up…tomorrow is when this will rocket 🚀 parabolic.. chance to run another 30-40%.. $SOFI $AAPL $TSLA </td>
  </tr>
</tbody>
</table></div>

---
