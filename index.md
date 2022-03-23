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



Last Updated: 2022-03-23 09:12:49 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/argentina/interest-rate </td>
   <td style="text-align:left;"> 2022-03-23 09:01:00 </td>
   <td style="text-align:left;"> Argentina Raises Interest Rate to 44.5% </td>
   <td style="text-align:left;"> The central bank of Argentina raised its “Leliq” interest rate by 200 bps to 44.5% from 42.5% on March 17th, the third hike this year, amid rising inflation and a global supply shock. The central bank said it would look to put the benchmark rate on a path toward “positive real returns on investments in local currency and to preserve the monetary and exchange stability,” hinting at more rate hikes to come with inflation at over 52%. The global backdrop of rising grains and energy prices was impacting domestic inflation. Argentina, recently struck a USD 45 billion staff-level agreement with the International Monetary Fund, with economic targets attached including shifting toward positive real interest rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 08:35:00 </td>
   <td style="text-align:left;"> Australia Shares Climb Higher on Tech Boost </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index climbed 0.4% to around 7,370 on Wednesday, scaling two-month highs on the back of strong gains from technology stocks which tracked an overnight rally on Wall Street. Investors also continued to assess recent hawkish comments from the Federal Reserve and the potential speed and size of future US rate hikes. Block Inc jumped 8.5%, priming the US payments behemoth for its highest closing level since listing on the Australian exchange two months ago. Other gainers among tech stocks include Fineos Corp (3.7%), Xero (2.2%), Wisetech Global (2.1%), Electro Optic Systems (5.7%) and Pointsbet Holdings (5.3%). Financial stocks also advanced on higher global bond yields, with the “Big Four” bank rising between 0.4%to 1.2%. Meanwhile, energy and mining firms retreated as the rally in commodity prices took a breather. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 08:08:50 </td>
   <td style="text-align:left;"> US Futures Steady After Tech-Led Gains </td>
   <td style="text-align:left;"> US stock futures were steady in Asian trade on Wednesday after a technology-led rally on Wall Street, as investors continued to assess the potential speed and size of future rate hikes. Futures contracts tied to the three major indexes swung between small gains and losses. In regular trading on Tuesday, the Dow rose 0.7% and the S&amp;P 500 climbed 1.1%. The Nasdaq Composite was the relative outperformer, rallying 2% as giant tech names including Apple (2.1%), Amazon (2.1%) and Meta Platforms (2.4%) pushed the index higher. Tesla also jumped 7.9% after delivering its first German-made cars to customers at its Gruenheide gigafactory. Meanwhile, investors digested recent comments from Federal Reserve Chair Jerome Powell, who hinted at bigger rate hikes than the traditional quarter-point increases to rein in inflation. Last week, the Fed raised interest rates for the first time since 2018 and signaled six more hikes this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60840467?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-23 08:03:55 </td>
   <td style="text-align:left;"> P&amp;O Ferries offers £100,000 to some sacked staff </td>
   <td style="text-align:left;"> P&amp;O Ferries has said 800 redundant staff will be offered £36.5m in total - with around 40 getting more than £100,000 each.                                                                                                                                                           , The firm has also denied that it broke the law when it sacked the workers without warning last week.                                                                                                                                                                                 , However, unions said the compensation package being offered was "pure blackmail and threats".                                                                                                                                                                                        , Ministers had questioned whether the move was legal - but P&amp;O said those affected were employed outside the UK.                                                                                                                                                                      , The video message in which the company sacked workers last Thursday prompted widespread outrage, with unions claiming some staff would be replaced by Indian seafarers on £1.81 an hour.                                                                                             , Ministers had threatened the firm with "unlimited fines" but in a letter to Business Secretary Kwasi Kwarteng, its chief executive Peter Hebblethwaite said the 786 sacked workers were employed by three Jersey-based arms of P&amp;O Ferries.                                          , The eight ships they worked on, which service routes including Dover-Calais and Larne-Ciarnryan, are all registered in either Cyprus or the Bahamas.                                                                                                                                 , Sacked staff had told the BBC about their experience of being "treated like criminals" - but in the letter Mr Hebblethwaite denied "rumours" that security staff who boarded vessels to manage the situation wore balaclavas or were directed to use handcuffs or force.             , "The teams accompanying the seafarers off our vessels were totally professional in handling this difficult task," he said.                                                                                                                                                           , The company said its settlement with its workers is believed to be "the largest compensation package in the British marine sector," and more than 40 staff would get severance packages of more than £100,000 each.                                                                  , P&amp;O Ferries said some employees are set to get 91 weeks' pay and the chance of new employment, and no employee would receive less than £15,000.                                                                                                                                      , The transport and freight company said 575 seafarers affected were in discussions to progress with the severance offers.                                                                                                                                                             , However, the RMT union, which has been organising protests over the redundancies said "the pay in lieu of notice is not compensation".                                                                                                                                               , "If staff do not sign up and give away their jobs and their legal right to take the company to an employment tribunal they will receive a fraction of the amount put to them," general secretary Mick Lynch said.                                                                    , P&amp;O Ferries had until Tuesday at 17:00 to respond to the letter from Mr Kwarteng - in which he said that P&amp;O Ferries "appears to have failed" to follow the correct process for making large-scale redundancies, by not consulting with unions and notifying the government in time. , Mr Kwarteng pointed out that failure to notify is "a criminal offence and can lead to an unlimited fine".                                                                                                                                                                            , Government officials will now review Mr Hebblethwaite's latest response.                                                                                                                                                                                                             , Separately, Business Minister Paul Scully said the government was reviewing all of its contracts with P&amp;O ferries and its owner DP World, including a £25 million subsidy to DP World to help develop London Gateway as a freeport.                                                  , An astonishing story of deadly bacteria, government tests, and a shady protest group...                                                                                                                                                                                              , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                               , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                                                                                          , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/belarus-economy-what-to-know </td>
   <td style="text-align:left;"> 2022-03-23 07:52:57 </td>
   <td style="text-align:left;"> Belarus Economy: What to Know </td>
   <td style="text-align:left;"> FOX Business' Ashley Webster reports from Poland on the protest held in an effort to halt trade with Russia.                                                                                                                                                                                                                                        , Ukraine’s Ministry of Dense warned this week that there were signs suggesting the Belarusian military was preparing for a "direct invasion" of Ukraine as the conflict neared its fifth week.                                                                                                                                                       , Belarus, which lies just to the north of Ukraine, has been targeted by sanctions for its participation in Russia’s invasion of Ukraine. Russia stationed thousands of its troops in Belarus for military exercises weeks ahead of the Feb. 24 invasion.                                                                                             , People walk along a street in Minsk, Belarus December 20, 2021. (REUTERS/Maxim Shemetov)                                                                                                                                                                                                                                                            , As the world watches "White Russia" for its next moves, here are some things to know about Belarus and its economy.                                                                                                                                                                                                                                 , RUSSIA INVADES: LIVE UPDATES                                                                                                                                                                                                                                                                                                                        , Ruled by authoritarian President Alexander Lukashenko for nearly 30 years, Belarus has been dubbed "Europe’s last dictatorship" over accusations that he has engaged in public corruption.                                                                                                                                                          , The country gained independence from the Soviet Union in 1991. But unlike other former Soviet countries that grew closer to the west, Belarus has cultivated ties with Moscow, with some regarding it as a puppet regime.                                                                                                                           , Russian President Vladimir Putin, right, and Belarusian President Alexander Lukashenko pose for a photo during their meeting in Moscow, Russia, Friday, March 11, 2022.  (Mikhail Klimentyev, Sputnik, Kremlin Pool Photo via AP)                                                                                                                   , Since independence, Belarus has pursued a gradual transition path, with limited structural reforms and a modest expansion of the private sector.                                                                                                                                                                                                    , A 2022 index of economic freedom from the Heritage Foundation ranked Belarus as 45th in a list of 45 countries in the European region.                                                                                                                                                                                                              , Belarus’ main industrial sectors include energy, agriculture and forestry, construction, and the services sector, which accounted for nearly half of the country’s GDP in 2019.                                                                                                                                                                     , REP SMITH MOVES TO BLOCK CHINA FROM NORMAL TRADE RELATIONS WITH US                                                                                                                                                                                                                                                                                  , To be sure, the country’s trade in energy commodities has contributed to GDP growth and a reduction in poverty. The years 2003 to 2013 saw poverty levels decreasing and household income rise among the bottom 40%, according to the World Bank. Despite these modest improvements, however, average income remains lower than its regional peers. , Belarus’ population has been declining since the fall of the Soviet Union. In the earliest 1990s, the country reached a peak of more than 10.2 million people.                                                                                                                                                                                      , Today, the country has a population of fewer than 10 million people with a GDP of $60 billion – roughly on par with a small U.S. state like South Dakota or Rhode Island. Its GDP has since fallen from a high of nearly $80 billion in 2014.                                                                                                       , Belarusian President Alexander Lukashenko chairs a meeting with military officials in Minsk, Belarus February 24, 2022. (Nikolay Petrov/BelTA/Handout via REUTERS)                                                                                                                                                                                  , Life expectancy, meanwhile, has improved significantly in the last 20 years. It began to decline after the fall of the Soviet Union, dropping from 71 in 1989 to 68 in 2002. Today the average life expectancy is around 74.                                                                                                                        , The economy’s strong exports in 2021 helped create a cyclical upturn, but the country’s economy is expected to take a hit in 2022 given its military’s collaboration with Russia in the invasion of Ukraine.                                                                                                                                        , CLICK HERE TO READ FOX BUSINESS ON THE GO                                                                                                                                                                                                                                                                                                           , In 2020, the country was beset by widespread protests over what many deemed a rigged election. The protests were met with a brutal crackdown and accusations from Lukashenko that the west had orchestrated the dissent.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-23 07:20:59 </td>
   <td style="text-align:left;"> Australia 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Australia 10 Year Government Bond Yeld increased to a 3-year high of 2.77% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60839343?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-23 07:11:30 </td>
   <td style="text-align:left;"> US rolls back Trump-era tariffs on UK steel </td>
   <td style="text-align:left;"> The US has agreed to ease Trump-era tariffs on UK steel and aluminium shipments, resolving an issue that had strained relations between the allies.                                                                                                                                      , The move follows earlier deals with the European Union and Japan over the controversial taxes, which were imposed by former President Donald Trump in 2018 in the name of national security.                                                                                             , In exchange, the UK will suspend extra taxes it had put on US products such as bourbon and Levi's jeans.                                                                                                                                                                                 , Business groups welcomed the decision.                                                                                                                                                                                                                                                   , Under the agreement, the US will replace the 25% tariffs on steel with a quota system. The policy will let UK metal imports into the country duty-free up to a certain level - the quota - before taxes kick in again.                                                                   , The deal will go into effect 1 June.                                                                                                                                                                                                                                                     , International Trade Secretary Anne-Marie Trevelyan said the deal had removed a "very frustrating irritant", calling the agreement "good news for the steel and aluminium sectors, which support the jobs of over 80,000 people across the UK".                                           , "It means our manufacturers can now enjoy a high level of tariff-free access to the US market once again," she said.                                                                                                                                                                     , "Hopefully we can now move forward and focus on deepening our thriving trading relationship with the US".                                                                                                                                                                                , US officials also welcomed the suspension of the UK retaliatory tariffs, which they said affected about $500m (£377m) worth in annual trade.                                                                                                                                             , "The historical deal announced today delivers on President Biden's vision to repair relationships with our allies while also helping to ensure the long-term viability of our steel and aluminium industries," said Ambassador Katherine Tai.                                            , However, in an interview with the BBC, Ms Tai, the top US trade negotiator, refused to be drawn as to when or if discussions for a formal free trade agreement might start.                                                                                                              , "I think the issue is what kind of collaboration is going to be fit for the purpose of addressing the challenges that we have today," she said. "I'm not going to exclude any options."                                                                                                  , The Biden administration has prioritised domestic goals ahead of trade, said economist Chad Bown, senior fellow at the Peterson Institute for International Economics.                                                                                                                   , While that could change as the US seeks stronger relations with allies in the context of Russia's invasion of Ukraine, he said there's no evidence of that happening yet.                                                                                                                , "The US administration has not made any signs that they want to do trade agreements with anybody anytime soon," he said. "That would be a big change."                                                                                                                                   , The Biden administration's low prioritisation of trade matters marks a major shift from former president Donald Trump, who made it a signature area of focus, using tariffs as bargaining chips in diplomacy.                                                                            , He set off a firestorm of criticism in the US and abroad when he announced the 25% tax on foreign steel shipments and 15% tax on foreign aluminium, citing a need to preserve America's manufacturing base and rejecting concerns that tariffs raise prices.                             , After allies, including the UK, hit US products such as Harley-Davidson motorcycles in retaliation, Mr Trump backed off the duties for certain countries, including Canada, opting for quotas instead.                                                                                   , US President Joe Biden later reached similar deals with the European Union and Japan.                                                                                                                                                                                                    , The approach has won praise in the US, including from groups like United Steel Workers for responding to the concerns of allies while still providing protection for US manufacturers.                                                                                                   , With many steel plants located in key election states, maintaining support from those workers is important for Mr Biden.                                                                                                                                                                 , On Tuesday the union praised the new deal for measures it said would help safeguard against unfairly subsidised steel production, such as mandatory annual audits of British Steel, which has a Chinese parent company.                                                                  , Business lobby UK Steel also praised the deal, saying it would be "felt by steel companies and their employees right across the UK and is immensely welcome".                                                                                                                            , But with the quotas in place, consumers are unlikely to see benefits like lower prices, said Phil Levy, economist for Flexport.                                                                                                                                                          , "Replacing tariffs with a system of quotas is actually moving away from transparency on these things and it does not get you the benefits of free trade," he said.                                                                                                                       , The US and UK traded more than $260bn worth of goods last year, of which the majority were exports from the US such as metals, aircraft parts, oil and gas.                                                                                                                              , While America accounts for nearly one fifth of total UK trade, the UK market represents just 5% of US exports.                                                                                                                                                                           , Mr Bown said the US imports too little British steel for a deal to have significant impact on prices. For UK consumers of American products, the impact on prices is also likely to be marginal, he said.                                                                                , "It can't hurt the consumer, so it will make them better off, but by how much is I think unclear," he said.                                                                                                                                                                              , With America buying £1 in every £6 of British exports, the cooling of tensions over steel has raised hopes of a reheating of the wider transatlantic trade relationship.                                                                                                                 , Levi's jeans, Harley Davidson motorbikes, steel bars and bourbon whiskey became unlikely weapons in a painful battle that has waged since 2018, with their producers and consumers paying a hefty price. For them this ceasefire will be welcome, if overdue.                            , At the heart of the dispute was the protection of American jobs. And if - and it's by no means certain - these developments are the first step towards the resumption of wider free-trade talks, that theme will continue to loom large, even if the man in the White House has changed. , The Biden administration struck a deal with the EU over steel almost five months ago. There's been speculations that the UK was made to wait due to unease over the way Boris Johnson's government has handled post-Brexit trading arrangements in Ireland.                              , The UK is keen to demonstrate its Brexit-era agility by notching up more trade agreements - but the US will be keen to continue showing it's calling the shots .                                                                                                                         , An astonishing story of deadly bacteria, government tests, and a shady protest group...                                                                                                                                                                                                  , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                                   , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/22/business/us-britain-trade.html </td>
   <td style="text-align:left;"> 2022-03-23 06:35:45 </td>
   <td style="text-align:left;"> U.S. and Britain Reach Trade Deal on Metals, Whiskey, Jeans and More - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The step, announced as U.S. and British officials met in Baltimore, removed trade barriers erected under former President Donald J. Trump.                                                                                                                                                                                                                                                                                                                                                               , By Ana Swanson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The Biden administration said on Tuesday that it would roll back Trump-era tariffs on British steel and aluminum, moving to resolve a trans-Atlantic trade clash that had soured relations with a key ally.                                                                                                                                                                                                                                                                                              , Under the agreement, the United States will allow a certain volume of metals from the United Kingdom to be imported duty-free starting June 1. In return, Britain agreed to lift tariffs on more than $500 million worth of American whiskey, blue jeans, motorcycles and other products, removing barriers imposed on U.S. exports during the trade spats of the Trump administration.                                                                                                                  , The announcement, which came at the conclusion of two days of trade talks between British and American officials, removed some of the last remaining vestiges of the trans-Atlantic trade clashes of the last few years.                                                                                                                                                                                                                                                                                 , The European Union — which included the United Kingdom until 2020 — imposed the tariffs on American products as retaliation for the levies that former President Donald J. Trump placed on foreign steel and aluminum in 2018. Post-Brexit, the United Kingdom maintained many of those tariffs on American goods.                                                                                                                                                                                       , Biden administration officials, particularly Katherine Tai, the United States trade representative, and Gina Raimondo, the commerce secretary, have worked over the last year to scale back many of those barriers, believing that the United States should focus its energy on countering economic rivals, not fighting with allies.                                                                                                                                                                    , During two days of meetings in Baltimore that kicked off a new trade dialogue, American and British officials pledged to advance policies that would deepen their partnership and would benefit workers and the environment. Officials also said they would continue to cooperate on measures to penalize President Vladimir V. Putin of Russia for that country’s invasion of Ukraine.                                                                                                                  , Under the agreement, British steel and aluminum that is imported into the United States must be entirely smelted and cast in the United Kingdom to escape tariffs, to prevent cheap steel from China and other countries from finding a backdoor into the U.S. market. In addition, any British steel company owned by a Chinese entity must audit their financial records to assess influence from the Chinese government and share those results with the United States, the Biden administration said., American and British officials also said semifinished products containing aluminum from China, Russia or Belarus would not be allowed to come into the United States duty-free.                                                                                                                                                                                                                                                                                                                          , Restrictions still apply: If shipments of steel and aluminum from Britain exceed certain levels, they will be taxed at the existing tariffs of 25 percent on steel and 10 percent on aluminum.                                                                                                                                                                                                                                                                                                           , As part of the agreement, the United States and Britain will also continue to confer on “market-distorting influence or ownership” in the steel and aluminum industries.                                                                                                                                                                                                                                                                                                                                 , The United States said it would send a trade delegation to Britain for further talks soon.                                                                                                                                                                                                                                                                                                                                                                                                               , The deal “delivers on President Biden’s vision to repair relationships with our allies while also helping to ensure the long-term viability of our steel and aluminum industries, the communities they support, and most importantly, the workers in these industries on both sides of the Atlantic,” Ms. Tai said in a statement.                                                                                                                                                                       , Rising concerns. Russia’s invasion on Ukraine has had a ripple effect across the globe, adding to the stock market’s woes and spooking investors. The conflict has already caused​​ dizzying spikes in energy prices, and could severely affect various countries and industries.                                                                                                                                                                                                                          , The cost of energy. Oil prices already were the highest since 2014, and they have continued to rise since the invasion.  Russia is the third-largest producer of oil, so more price increases are inevitable.                                                                                                                                                                                                                                                                                            , Gas supplies. Europe gets nearly 40 percent of its natural gas from Russia, and it is likely to be walloped with higher heating bills. Natural gas reserves are running low, and European leaders worry that Moscow could cut flows in response to the region’s support of Ukraine.                                                                                                                                                                                                                      , Food prices. Russia is the world’s largest supplier of wheat; together, it and Ukraine account for nearly a quarter of total global exports. Countries like Egypt, which relies heavily on Russian wheat imports, are already looking for alternative suppliers.                                                                                                                                                                                                                                         , Shortages of essential metals. The price of palladium, used in automotive exhaust systems and mobile phones, has been soaring amid fears that Russia, the world’s largest exporter of the metal, could be cut off from global markets. The price of nickel, another key Russian export, has also been rising.                                                                                                                                                                                            , Financial turmoil. Global banks are bracing for the effects of sanctions intended to restrict Russia’s access to foreign capital and limit its ability to process payments in dollars, euros and other currencies crucial for trade. Banks are also on alert for retaliatory cyberattacks by Russia.                                                                                                                                                                                                     , Thomas M. Conway, the international president of United Steelworkers, said the union supported the agreement and that it was “an important step in addressing systemic problems like illegal dumping and global overcapacity that threaten the vitality and future of our steel and aluminum industries.”                                                                                                                                                                                                , Chris Swonger, the chief executive of the Distilled Spirits Council, said that American distillers were “cheering the end of this long tariff nightmare.” According to the group, American whiskey exports to Britain had declined by 42 percent since 2018, when the tariffs were imposed.                                                                                                                                                                                                              , “With the removal of the U.K.’s debilitating retaliatory tariffs on American Whiskey exports, U.S. distillers are ready to fire up the stills,” he added.                                                                                                                                                                                                                                                                                                                                                , The two countries did not profess their intention to complete negotiations that began during the Trump administration for a free-trade agreement. British leaders had lauded the potential deal as an independent step for their economy after departing the European Union and have pushed the Biden administration to take up negotiations.                                                                                                                                                            , But the Biden administration has shown little appetite for adopting the Trump administration’s goals, saying instead that the trade dialogue with the United Kingdom should explore “mutual international trade priorities rooted in our shared values, while promoting innovation and inclusive economic growth.”                                                                                                                                                                                       , The coming dialogue will address issues like trade and investment involving small businesses, the digital economy, durable supply chains, and protecting labor rights and the environment, the Biden administration said.                                                                                                                                                                                                                                                                                , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/22/ryan-cohen-scoops-up-100000-more-shares-of-gamestop.html </td>
   <td style="text-align:left;"> 2022-03-23 06:35:07 </td>
   <td style="text-align:left;"> Ryan Cohen scoops up 100,000 more shares of GameStop, meme stock soars as much as 20% after hours </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                  , GameStop chairman Ryan Cohen just bought another 100,000 shares of the video game retailer on Tuesday, bringing his ownership to 11.9% as the activist investor tries to push the company into e-commerce.                                                                                                                       , The meme stock jumped as high as about 20% in after-hours trading Tuesday after a 30% rally during the regular trading session.                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                  , Cohen purchased these shares through his investment company RC Ventures at a cost as low as $96.81 and as high as $108.82 apiece, according to a regulatory filing. Now he owns a total of 9,101,000 GameStop shares.                                                                                                            , Cohen cofounded pet-supply retailer Chewy and managed to turn it into a booming business. The investor was tapped by GameStop early last year to serve as chairman of a special committee formed by its board to help its transformation.                                                                                        , Soon after his appointment, GameStop experienced a jaw-dropping short squeeze that sent shockwaves across Wall Street. A band of retail investors came together in online chatrooms, encouraging one another to pile into GameStop's stock and call options to squeeze out short sellers. The stock ended 2021 up more than 680%., Just two weeks ago, Cohen revealed a big stake in Bed Bath &amp; Beyond and pushed for a turnaround. He wrote a letter to the company board, saying the housewares retailer is struggling to reverse market share losses and navigate supply chain woes.                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/paraguay/interest-rate </td>
   <td style="text-align:left;"> 2022-03-23 06:06:12 </td>
   <td style="text-align:left;"> Paraguay Raises Interest Rate by 50bps </td>
   <td style="text-align:left;"> The central bank of Paraguay raised its benchmark interest rate by 50 bps to 6.25% on March 22nd 2022, the highest since 2015 and the eighth consecutive hike since the monetary authority started the normalization process in August. The annual inflation rate in Paraguay accelerated to 9.3% in February, the highest since May of 2011. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/22/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-03-23 06:01:57 </td>
   <td style="text-align:left;"> Stock futures are steady as investors juggle Fed comments and policy </td>
   <td style="text-align:left;"> , U.S. stock futures were little changed in overnight trading on Tuesday as investors continue to digest revelations from the Federal Reserve on inflation and interest rates.                                                                                                                                             , Dow futures rose just 30 points. S&amp;P 500 futures advanced 0.1% and Nasdaq 100 futures were flat.                                                                                                                                                                                                                         , On Tuesday, the major averages rose as investors evaluated recent comments from Federal Reserve chief Jerome Powell. Last week, the Fed raised interest rates for the first time since 2018 and forecast a plan to hike rates by a quarter point at each of the remaining six meetings of 2022.                          , But then Powell appeared to up the rhetoric even more on Monday, when he promised to take tough action on inflation.                                                                                                                                                                                                     , "The labor market is very strong, and inflation is much too high," the central bank chief told the National Association for Business Economics. "If we conclude that it is appropriate to move more aggressively by raising the federal funds rate by more than 25 basis points at a meeting or meetings, we will do so.", The Dow Jones Industrial Average rose more than 250 points on Tuesday, helped by a 2.2% jump in Nike's stock from strong earnings. The S&amp;P 500 climbed 1.1%.                                                                                                                                                             , The Nasdaq Composite was the relative outperformer, rising 2% as Meta Platforms, Amazon, Apple, Netflix and Google-parent Alphabet all closed higher.                                                                                                                                                                    , Here's how Carl Icahn is positioning for a possible recession in America                                                                                                                                                                                                                                                 , Buffett is paying a relatively cheap price for his biggest takeover in six years, analyst says                                                                                                                                                                                                                           , Europe's moving away from Russian energy — That could boost these electric vehicle charging stocks                                                                                                                                                                                                                       , The benchmark 10-year U.S. Treasury yield on Tuesday hit 2.39% at the highs of the session, its highest level since May 2019.                                                                                                                                                                                            , "Investor attitudes are being bolstered by the fact that the stock market seems little concerned about bond yields surging higher or a Federal Reserve which is getting more hawkish by the day," said Jim Paulsen, chief investment strategist for the Leuthold Group.                                                  , The S&amp;P 500 is only 5% off its record and has surpassed both its 50-day and 200-day moving averages.                                                                                                                                                                                                                     , Still, famed activist investor Carl Icahn said Tuesday an economic downturn could be coming.                                                                                                                                                                                                                             , "I think there could very well could be a recession or even worse," Icahn, founder and chairman of Icahn Enterprises, said on CNBC's "Closing Bell Overtime" to Scott Wapner.                                                                                                                                            , On the economic front, new homes sales data from February will be released at 10 a.m. on Wednesday.                                                                                                                                                                                                                      , Generals Mills, Cintas and Tencent Holdings will report quarterly earnings before the bell on Wednesday. KB Home reports after the bell.                                                                                                                                                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/producer-prices-change </td>
   <td style="text-align:left;"> 2022-03-23 05:15:24 </td>
   <td style="text-align:left;"> South Korea Producer Inflation at 5-Month Low </td>
   <td style="text-align:left;"> Producer prices in South Korea rose 8.4 percent year-on-year in February of 2022, easing from an upwardly revised 8.9 percent advance in the previous month. It was the lowest producer inflation since September 2021, as cost slowed for manufacturing products (14 percent vs 14.2 percent in February), electric power, gas, water &amp; waste (12.4 percent vs 13.3 percent) and services (2.5 percent vs 2.7 percent). Also, prices of agriculture, forestry &amp; marine products went down 6.6 percent, after a 1.5 percent increase in January. On a monthly basis, prices went up 0.4 percent, after a 1.1 percent rise in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 05:02:00 </td>
   <td style="text-align:left;"> Brazilian Shares Rise to 6-Month High </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Ibovespa, rose almost 1% to around 117,272 on Tuesday, its highest since September 6th 2021 and extending gains for the fifth straight session. According to the economy ministry's bimonthly revenue and expenditure report, Brazil is set to post a smaller primary budget deficit this year on the back of higher revenues, especially from oil royalties.  Meanwhile, investors digested more hawkish comments from US Federal Reserve Chairman Powell and minutes from the latest Brazil's central bank monetary policy meeting signaling another 100 basis points hike at the next meeting in May. Still, caution persists because the ongoing peace talks between Moscow and Kyiv are not moving forward. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/api-data-reportedly-show-weekly/story.aspx?guid={1C832901-8384-4D4F-A754-6C97BC072D67}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-23 04:43:59 </td>
   <td style="text-align:left;"> API data reportedly show weekly U.S. crude supplies down by more than 4 million barrels - MarketWatch </td>
   <td style="text-align:left;"> The American Petroleum Institute reported late Tuesday that U.S. crude supplies fell by 4.3 million barrels for the week ended March 18, according to sources. The API also reportedly showed weekly inventory declines of 626,000 barrels for gasoline and 826,000 barrels for distillates. Crude stocks at the Cushing, Okla., delivery hub were up by 646,000 barrels last week, sources said. Inventory data from the Energy Information Administration will be released Wednesday. On average, the EIA is expected to show crude inventories unchanged for the week, according to analysts polled by S&amp;P Global Commodity Insights. The survey also showed expectations for weekly supply declines of 1.7 million barrels for gasoline and 1.4 million barrels for distillates. Oil prices extended their losses in the electronic trading session after the API data. May West Texas Intermediate crude 
        CLK22,
        -0.15%
       was at $108.44 a barrel in electronic trading, after settling Tuesday at $109.27 on the New York Mercantile.                                          , Alibaba Group Holding Ltd. undefined announced late Monday that it was upsizing its share-buyback program. The Chinese e-commerce giant is now authorized to repurchase up to $25 billion in shares, whereas the prior authorization was for $15 billion. The program will be effective for a two-year period that ends in March 2024. Alibaba disclosed that it bought back about $9.2 billion in American depositary shares as of March 18 through its previously announced repurchase program. The upsized program represents "a sign of confidence about the company's continued growth in the future," Alibaba said in a press release. Further, the company announced that Weijian Shan, the executive chairman of investment-management group PAG, has been appointed an independent director to the company's board of directors. The appointment will be effective March 31, at which time Börje Ekholm, the chief executive of the Ericsson Group, will retire from Alibaba's board after having served on it since June 2015. Shares of Alibaba have fallen about 16% over the past three months. , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/api-crude-oil-stock-change </td>
   <td style="text-align:left;"> 2022-03-23 04:35:14 </td>
   <td style="text-align:left;"> US Crude Oil Inventories Unexpectedly Fall: API </td>
   <td style="text-align:left;"> Stocks of crude oil in the United States declined 4.28 million barrels in the week ended March 18th, 2022, after a 3.754 million barrels rise in the previous week and compared to market expectations of a 0.0250 million increase, data from the American Petroleum Institute showed. It was the first drop in US crude stocks in a month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/03/22/dmitry-peskov-alexey-navalny-amanpour-sot-intl-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-23 04:30:53 </td>
   <td style="text-align:left;"> 'No one is afraid of Alexey Navalny': Kremlin spokesman Dmitry Peskov to CNN's Christiane Amanpour - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 04:24:55 </td>
   <td style="text-align:left;"> Toronto Shares Hit Fresh Record </td>
   <td style="text-align:left;"> The S&amp;P/TSX composite index extended gains into a fifth session on Tuesday to close at a fresh record high above the 22,080 mark underpinned by gains in banks and tech stocks. Meanwhile, heavyweight energy stocks edged down as the oil rally faltered. On corporate news, Canadian Pacific Railway, the country’s 2nd largest rail company, agreed to binding arbitration with the workers’ union to help resolve a labor dispute, allowing operations to resume. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-23 04:19:00 </td>
   <td style="text-align:left;"> New Zealand 10Y Bond Yield Hits 5-year High </td>
   <td style="text-align:left;"> The yield on New Zealand's 10-year government bond skyrocketed to above 3.3%, a level not seen since March of 2017, on expectations of higher interest rates as inflation is expected to remain elevated due to the war in Ukraine. The RBNZ is widely expected to raise its benchmark rate by 25bps six more times this year. Kiwibank said in a research note the Reserve Bank of New Zealand will not resort to bigger rate hikes because the risk of recession has increased. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/adbe:us </td>
   <td style="text-align:left;"> 2022-03-23 04:17:11 </td>
   <td style="text-align:left;"> Adobe Systems earnings above expectations at 3.37 USD </td>
   <td style="text-align:left;"> Adobe Systems (ADBE) released earnings per share at 3.37 USD, compared to market expectations of 3.34 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/22/carl-icahn-says-there-very-well-could-be-a-recession-or-even-worse.html </td>
   <td style="text-align:left;"> 2022-03-23 04:12:35 </td>
   <td style="text-align:left;"> Carl Icahn says there 'very well could be a recession or even worse' </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                       , Famed investor Carl Icahn said Tuesday an economic downturn could be on the horizon and he is loaded on protection against a steep sell-off in the market.                                                                                                                                                                                            , "I think there very well could be a recession or even worse," Icahn said on CNBC's "Closing Bell Overtime" to Scott Wapner. "I have kept everything hedged for the last few years. We have a strong hedge on against the long positions and we try to be activist to get that edge... I am negative as you can hear. Short term I don't even predict.", The founder and chairman of Icahn Enterprises said surging inflation is a major threat to the economy, while the Russia-Ukraine war only added more uncertainty to his outlook.                                                                                                                                                                       , The Federal Reserve raised interest rates for the first time in more than three years in an attempt to battle inflation that is running at its highest level in 40 years. Fed Chairman Jerome Powell this week vowed tough action on soaring prices, indicating he's open to rate hikes more than the traditional 25 basis points.                    , "I really don't know if they can engineer a soft landing," Icahn said. "I think there is going to be a rough landing... Inflation is a terrible thing when it gets going."                                                                                                                                                                            , Icahn, a longtime activist investor and so-called corporate raider, said he believes the system of company boards needs to be fixed and weak management could lead to disasters.                                                                                                                                                                      , "There's no accountability in Corporate America. You have some very fine companies, some very fine CEOs, but far too many that are not up to the task," the longtime activist investor said.                                                                                                                                                          , To position for a recession in America, Icahn said he's betting against malls and commercial real estate.                                                                                                                                                                                                                                             , Here's how Carl Icahn is positioning for a possible recession in America                                                                                                                                                                                                                                                                              , Buffett is paying a relatively cheap price for his biggest takeover in six years, analyst says                                                                                                                                                                                                                                                        , Europe's moving away from Russian energy — That could boost these electric vehicle charging stocks                                                                                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                      , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                      , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                    , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 04:09:00 </td>
   <td style="text-align:left;"> US Stocks Rebound </td>
   <td style="text-align:left;"> US stocks rebound on Tuesday, with the Dow up more than 250 points, the S&amp;P 500 rising 1.1% and the Nasdaq advancing almost 2% led by technology stocks as investors returned to faster-growing companies. Shares of banks and other financials also rose on prospects of higher long-term interest rates. Among single stocks, Nike gained 2.2% after it beat quarterly estimates for profit and revenue; and Tesla jumped about 8% after delivering its first German-made cars to customers at its Gruenheide gigafactory. On Monday, Fed Chair Powell said that the US central bank could move more aggressively by raising the interest rates by more than 25 basis points at a meeting or meetings to bring inflation, which is now running at 40 years highs, under control. Meanwhile, Russia and Ukraine failed to make progress on the ceasefire, and the shelling of Ukrainian cities continues. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/politics/2022/03/22/ketanji-brown-jackson-ted-cruz-critical-race-theory-abby-phillip-nr-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-23 04:08:57 </td>
   <td style="text-align:left;"> Her pause 'really said it all': Abby Phillip breaks down Cruz-Jackson exchange - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stocks-end-higher-investors-shake/story.aspx?guid={20171F76-EF50-4405-9015-C066483FDFA1}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-23 04:05:20 </td>
   <td style="text-align:left;"> Stocks end higher as investors shake off hawkish Fed comments - MarketWatch </td>
   <td style="text-align:left;"> Stocks ended higher Tuesday, finding their footing a day after the Dow Jones Industrial Average snapped a five-day winning streak following hawkish comments by Federal Reserve Chairman Jerome Powell. The Dow Jones Industrial Average 
        DJIA,
        +0.74%
       finished around 255 points higher, up 0.7%, near 34,807, according to preliminary figures, while the S&amp;P 500 
        SPX,
        +1.13%
       rose around 50 points, or 1.1%, to close near 4,512. The Nasdaq Composite 
        COMP,
        +1.95%
       ended near 14,109, jumping 2%. Powell on Monday said the Fed could hike rates in half-point increments at future meetings if deemed necessary to rein in inflation., The spread between the 2- and 10-year yield is around 22 basis points after Monday's remarks by Federal Reserve Chair Powell --- as gaps between 3- and 10-year yields, 5s/10s, 7s/10s, and 20s/30s all invert.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-03-23 03:58:50 </td>
   <td style="text-align:left;"> DXY Pauses 3-Day Gain </td>
   <td style="text-align:left;"> The dollar index stabilized around the 98.50 level, pausing a three day rally as investors returned to equity markets denting some of the safe-haven appeal of the greenback. On Monday, Federal Reserve Chair Jerome Powell said rates could increase more than the previously approved 25 basis points to bring too-high inflation under control, which pushed bets for a 50-basis-point hike at the Fed's May meeting higher. Traders are pricing in a 61.6% chance of a 50-basis-point hike at the Fed's May meeting, according to CME's FedWatch Tool, up from slightly more than 50% a week ago. The Fed delivered a quarter-point rate hike last week in a measured move to tame inflation, which is now running at 40 years highs. Meanwhile, investors continued to monitor the Russia-Ukraine war as ongoing peace talks failed to progress. Analysts warned that the Ukraine conflict would likely continue, exacerbating supply disruptions and adding to inflationary pressures that would support haven bids for the dolla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/rep-smith-isolate-block-trade </td>
   <td style="text-align:left;"> 2022-03-23 03:58:00 </td>
   <td style="text-align:left;"> Rep Smith moves to block China from normal trade relations with US </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines for March 22.                                                                                                                                                                                                                                              , FIRST ON FOX: New Jersey Republican Rep. Chris Smith introduced legislation this week to block China from engaging in normal trade relations with the U.S. as "punishment" for its human rights abuses in Xinjiang.                                                                                       , The bill, which was co-sponsored by New York Democrat Rep. Tom Suozzi and Wisconsin Republican Tom Tiffany, would transform the U.S. trade with one of its top business partners.                                                                                                                         , STATE DEPT REFUSES TO DETAIL 'RED LINE' IF CHINA PROVIDES SUPPORT TO RUSSIA AMID WAR IN UKRAINE                                                                                                                                                                                                           , Chinese President Xi Jinping and President Biden in an undated file photo.  (Tim Rue/Corbis via Getty Images / Getty Images)                                                                                                                                                                              , "The Chinese Communist Party has gotten a pass for its gross human rights violations while benefiting tremendously by stealing American jobs and growing into the economic superpower it is today," Smith said in a Tuesday statement to Fox News Digital.                                                , It is unclear how exactly the U.S.-China trade partnership would be impacted, but in 2020 China stood as the U.S.’s largest goods trading partner with more than $559 billion exchanged, according to the Office of the U.S. Trade Representative.                                                        , The U.S. exported more than $124 billion in goods to Beijing in 2020, while it imported nearly $435 billion.                                                                                                                                                                                              , The bipartisan legislation would also require the president to approve whether China has taken steps to "significantly progress" and improve its human rights record and stop its oppressive behavior against all Chinese nationals before it could again receive permanent normal trade relations (PNTR)., HOUSE VOTES OVERWHELMINGLY TO SUSPEND NORMAL TRADE RELATIONS WITH RUSSIA, BELARUS                                                                                                                                                                                                                         , Custom officials check documents with a man at a container port in Yantai in eastern China's Shandong province on Tuesday. (AP/Chinatopix / Associated Press)                                                                                                                                             , Smith repeatedly condemned the International Olympic Committee’s decision to hold the Winter Games in Beijing and argued corporations that refused to pull their support for the games were financing the CCP’s abusive regime.                                                                           ,  "Tragically, American corporations—from Nike to the NBA—still look the other way while Xi Jinping’s communist regime is committing systematic genocide and crushing religious freedom," said Smith. "What will it take?"                                                                                 , Smith’s legislation is similar to a bill that overwhelmingly passed the House last week, which called for Russia’s normalized trade ties with the U.S. to be stripped over its deadly invasion of Ukraine.                                                                                                , China has received wide criticism for its refusal to condemn Russia over its illegal invasion and insistence that the U.S. and NATO need to discuss Moscow’s security concerns.                                                                                                                           , Russian President Vladimir Putin greets Chinese President Xi Jinping during their bilateral meeting on Nov. 13, 2019 in Brasilia, Brazil. ( Mikhail Svetlov/Getty Images / Getty Images)                                                                                                                  , CLICK HERE TO GET THE FOX NEWS APP                                                                                                                                                                                                                                                                        , "China’s support for Russia — which itself is likely to lose PNTR status due to Putin's aggression against Ukraine — has made this reappraisal of granting China preferential trade treatment especially timely," Smith said.                                                                             , "Many if not most business and political leaders have long bought into the ‘China Fantasy’ that overlooks human rights abuses while asserting that increased trade will make China more like us," the congressman added. "It was not true then and it's not true now." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/22/europe/amanpour-peskov-interview-ukraine-intl/index.html </td>
   <td style="text-align:left;"> 2022-03-23 03:17:23 </td>
   <td style="text-align:left;"> Dmitry Peskov, Putin spokesman refuses to rule out use of nuclear weapons if Russia faced an 'existential threat' - CNN </td>
   <td style="text-align:left;"> (CNN)Russian President Vladimir Putin's chief spokesman has conceded that Russia has yet to achieve any of its military goals in Ukraine and refused to deny that Moscow could resort to the use of nuclear weapons.                                                                                                                                                                                                           , In an interview with CNN's Christiane Amanpour on Tuesday, Dmitry Peskov repeatedly refused to rule out that Russia would consider using nuclear weapons against what Moscow saw as an "existential threat." When asked under what conditions Putin would use Russia's nuclear capability, Peskov replied, "if it is an existential threat for our country, then it can be."                                                    , Putin has previously hinted at using nuclear weapons against nations that he saw as a threat to Russia. Back in February, the Russian President said in a televised statement, "No matter who tries to stand in our way or all the more so create threats for our country and our people, they must know that Russia will respond immediately, and the consequences will be such as you have never seen in your entire history.", He then said in a televised meeting with Russian defense officials that "officials in leading NATO countries have allowed themselves to make aggressive comments about our country, therefore I hereby order the Minister of Defense and the chief of the General Staff to place the Russian Army Deterrence Force on combat alert."                                                                                            , When asked what Putin thought he had achieved in Ukraine so far, Peskov answered: "Well, first of all, not yet. He hasn't achieved yet."                                                                                                                                                                                                                                                                                        , The spokesman also claimed that the "special military operation" -- the Kremlin's official euphemism for Russia's invasion in Ukraine -- was "going on strictly in accordance with the plans and the purposes that were established before hand."                                                                                                                                                                               , Peskov also repeated Putin's demands, saying that the "main goals of the operation" are to "get rid of the military potential of Ukraine," to ensure Ukraine is a "neutral country," to get rid of "nationalist battalions," for Ukraine to accept that Crimea -- annexed by Russia in 2014 -- is part of Russia and to accept that the breakaway statelets of Luhansk and Donetsk "are already independent states."            ,                                                                                                                                                                                                                                                                                                                                                                                                                                 , He also claimed that Russia has only attacked military targets, despite numerous reports of Russian airstrikes against civilian targets sheltering ordinary Ukrainians.                                                                                                                                                                                                                                                         , The interview comes as Western intelligence has reported that Russia's operations have stalled in parts of Ukraine.                                                                                                                                                                                                                                                                                                             , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/argentina/current-account </td>
   <td style="text-align:left;"> 2022-03-23 03:15:07 </td>
   <td style="text-align:left;"> Argentina Current Account Balance Swings to Surplus in Q4 </td>
   <td style="text-align:left;"> Argentina recorded a current account surplus of USD 373 million in the fourth quarter of 2022, switching from a USD 1.235 million deficit in the corresponding period of the previous year. The goods surplus widened to USD 3.627 million from USD 1.295 million a year earlier and the secondary income account surplus rose to USD 408 million from USD 179 million. Meanwhile, the services gap advanced to USD 1.308 million from USD 618 million and the primary income shortfall went up to USD 2.355 million from USD 2.091 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/22/crypto-investor-katie-haun-raises-1point5-billion-for-haun-ventures.html </td>
   <td style="text-align:left;"> 2022-03-23 03:00:01 </td>
   <td style="text-align:left;"> Crypto investor Katie Haun raises $1.5 billion, the largest debut fund ever by a female VC </td>
   <td style="text-align:left;"> , Crypto investor Katie Haun has raised $1.5 billion for her new fund after leaving Andreessen Horowitz, and shattered a record in the process.                                                                                                                                                                                                                                                                                                                                                                                                           , Haun Ventures' kickoff marks the largest debut venture fund ever raised by a solo female founding partner, according to Pitchbook. Former investment banker Mary Meeker held the prior record with a $1.3 billion fund after spinning out from Kleiner Perkins.                                                                                                                                                                                                                                                                                         , "It feels, honestly, like a lot of pressure. But I think that motivates everyone on the team," Haun told CNBC in her first broadcast interview since leaving Andreessen Horowitz. "Web3 is the new era of the internet, and it deserves a new era of investors."                                                                                                                                                                                                                                                                                        , The term Web3, or Web 3.0, loosely refers to general computing applications built on the blockchain — the same technology underlying bitcoin and other cryptocurrencies. Examples include NFTs, which are traceable ownership certificates attached to digital files such as art pieces or videos, and decentralized finance applications, in which self-executing "smart" contracts can be used to replace middlemen like lawyers and bankers in certain types of transactions. But overall, the space is still in a very early and experimental phase., Haun Ventures will invest in both start-up equity, and in some cases the cryptocurrencies issued by those start-ups, also known as tokens.                                                                                                                                                                                                                                                                                                                                                                                                              , "That's something I've learned through being involved in deploying three other crypto funds: there's still a ton of potential in crypto and Web3 equity business models, but also token business models," she said. "I don't think that you can really be a crypto investor without holding tokens."                                                                                                                                                                                                                                                    , Haun's fund will be divvied up into two segments: $500 million for early-stage companies and protocols, and $1 billion for "acceleration," or later-stage projects.                                                                                                                                                                                                                                                                                                                                                                                     , Haun, a former federal prosecutor, became Andreessen's first female general partner in 2018 where she co-led its multiple cryptocurrency funds alongside Chris Dixon. Andreessen Horowitz will be a limited partner in Haun's newest fund, while Marc Andreessen, the firm's founder, and Dixon all personally contributed to her new endeavor.                                                                                                                                                                                                         , Her exit caught many in Silicon Valley off guard. While it was a "dream job," Haun said the departure was about taking more of a risk, and "stepping out of her comfort zone."                                                                                                                                                                                                                                                                                                                                                                          , "Obviously there's a relationship there, and there are friendships there. We still intend to collaborate closely with Andreessen Horowitz," she said. "One of the unique things about our fund size makes it so that we don't have to lead every deal, we can play well with a lot of other crypto investors -- founders don't want a single investor on their cap table, even in the early rounds."                                                                                                                                                    , Haun Ventures' nine-person team includes Chris Lehane, a former Airbnb executive and Clinton administration official, Tomicah Tillemann, a former staffer for President Joe Biden, and Rachael Horwitz, who led communications teams at Twitter, Google, Facebook and Coinbase. Multiple employees left Andreessen Horowitz with Haun for the new fund. She said the smaller team allows the firm to be more "nimble," and act as "venture contributors" in addition to venture capitalists.                                                            , "Gone are the days where founders just want capital," she said. "One of the things that Haun Ventures will do for our founders is really actively contribute to the projects in which we invest."                                                                                                                                                                                                                                                                                                                                                       , The launch comes during a bear market for bitcoin. The world's largest cryptocurrency is down roughly 40% from its peak in November, with smaller cryptocurrencies like ether seeing deeper losses. Haun, who has invested through past downturns or "crypto winters", said there's still plenty of developer activity and upside.                                                                                                                                                                                                                      , "When I think back to deploying the first two crypto funds, that was during a period of immense volatility -- it was definitely a crypto winter with prices down 70% and projects were still born that during that cycle," she said, highlighting Solana and NFT exchange OpenSea. "One of the things I've learned as an investor with a long term view of the space, is that great products are going to be built and great protocols are going to be built, no matter what the prices are."                                                           , Crypto exchange Coinbase, which Haun is on the board of, has seen roughly 58% from drop its high last year. Still, Haun said private start-up valuations aren't being affected, yet.                                                                                                                                                                                                                                                                                                                                                                    , "There's a bit of a lag. We're still seeing very high valuations in crypto projects. Last time this happened, with macro market corrections, it took a while for that to translate over into crypto. I think the same could be true here," she said.                                                                                                                                                                                                                                                                                                    , While cryptocurrencies may be struggling to regain momentum, dollars flowing into private companies is at all-time highs. Blockchain start-ups brought in a record $25 billion in venture capital dollars last year, according to recent data from CB Insights. That figure is up eightfold from a year earlier.                                                                                                                                                                                                                                        , That flood of venture dollars has sparked some controversy on Twitter.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Tesla CEO Elon Musk and Twitter co-founder Jack Dorsey ⁠— two of the world's best-known tech billionaires ⁠— have been among those questioning "Web3." Dorsey argues VCs and their limited partners are the ones who will ultimately end up owning Web3 and it "will never escape their incentives," he tweeted, calling it a "centralized entity with a different label."                                                                                                                                                                                , "I look at it as Web3 finally getting some of the critics it deserves in the space," Haun said. "If I could have the choice between Jack Dorsey offering some critiques versus some of the myths that we've heard perpetrated for so long in the space, I would certainly choose the former. So I think that debate is healthy."                                                                                                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-finish-lower/story.aspx?guid={AB8DB1C1-60F6-40EF-9528-DF525A16CF9A}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-23 02:40:53 </td>
   <td style="text-align:left;"> U.S. oil futures finish lower after a more than 7% climb at the start of the week - MarketWatch </td>
   <td style="text-align:left;"> U.S. oil futures finished lower on Tuesday, easing back after posting a gain of more than 7% in the previous session. Traders continued to weigh the likelihood of a European Union ban on imports of Russian oil. A meeting of NATO on Thursday "could yield tougher measures against Moscow, potentially confirming the anticipated supply risks to Russian upstream oil" in the short term, said Louise Dickson, senior oil market analyst at Rystad Energy. West Texas Intermediate crude for April delivery 
        CLJ22,
        -0.73%
       fell 36 cents, or 0.3%, to settle at $111.76 a barrel on the New York Mercantile Exchange. The contract expired at the end of the session. The new front-month May WTI contract 
        CLK22,
        -0.15%
       lost 70 cents, or 0.6%, to $109.27., The BA.2 subvariant of the omicron variant of the coronavirus that causes COVID-19 will probably cause an uptick in U.S. cases similar to the one currently occurring in Europe, according to Dr. Anthony Fauci, President Joe Biden's chief medical adviser.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-us-allies-unveil-more/story.aspx?guid={81FDDF27-EC82-43A6-9187-9BD9883BCACB}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-23 02:07:02 </td>
   <td style="text-align:left;"> Biden, U.S. allies to unveil more sanctions on Russia, White House says - MarketWatch </td>
   <td style="text-align:left;"> During his trip to Europe later this week, President Joe Biden will "join our partners in imposing further sanctions on Russia and tightening the existing sanctions to crack down on evasion and to ensure robust enforcement," said Jake Sullivan, Biden's national security adviser, during a Tuesday briefing for reporters. When asked for details, Sullivan said he would not "get ahead of an announcement, which will be rolled out in conjunction with our allies on Thursday, when the president has the opportunity to speak with them ... on a further package of sanctions.", Tuesday is Day 2 of Judge Ketanji Brown Jackson's confirmation hearing before the Senate Judiciary Committee. It's the first hearing day in which the nominee is facing questions from the committee's Democratic and Republican senators.                                                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-end-lower-us/story.aspx?guid={F897FFEA-D92E-4B89-B279-9AC85E1A1E0C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-23 01:53:44 </td>
   <td style="text-align:left;"> Gold futures end lower as U.S. Treasury yields rise - MarketWatch </td>
   <td style="text-align:left;"> Gold futures finished lower on Tuesday, pressured by strength in Treasury yields in the wake of comments from Federal Reserve officials on interest-rate hikes. Fed Chairman Jerome Powell on Monday said policy makers could delivery half percentage point rate hikes at future meetings and St. Louis Fed President James Bullard said Tuesday that the central bank needs to move aggressively on rates. Gold looks like it is "on the ropes" on surging Treasury yields, growing stagflation risks, and with a potential pivotal moment in West's response in the Ukraine war coming up with the NATO summit set for Thursday, said Edward Moya, senior market analyst at OANDA. "Gold should have decent support ahead of the $1,900 level, but if that breaks, bearish momentum could get ugly fast." April gold 
        GCJ22,
        -0.05%
       declined by $8, or 0.4%, to settle at $1,921.50 an ounce. , The yield on the 10-year U.S. Treasury note was at its highest since May 2019, up to above 2.35%.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/white-house-press-secretary-psaki/story.aspx?guid={52BA0402-7F52-4422-B20D-260E6E6F110C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-23 01:49:10 </td>
   <td style="text-align:left;"> White House press secretary Psaki tests positive for COVID, says no close contact with Biden - MarketWatch </td>
   <td style="text-align:left;"> White House press secretary Jen Psaki said in a statement Tuesday that she tested positive for COVID-19, so she won't be joining President Joe Biden on his trip to Europe this week. Psaki said she had "two socially-distanced meetings" with Biden on Monday, and the president is "not considered a close contact as defined by CDC guidance" and has tested negative on Tuesday. Psaki, who said she has only mild symptoms, previously had COVID in October., The Biden administration on Monday says it gave classified briefings last week to companies and sectors about the potential for Russian cyberattacks, as President Joe Bidan and other officials offer fresh warnings about such assaults.                                                                                                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/22/europe/ukraine-new-phase-analysis-cmd-intl/index.html </td>
   <td style="text-align:left;"> 2022-03-23 01:46:27 </td>
   <td style="text-align:left;"> Ukraine has denied Russia a victory for four weeks. A grim new phase could be coming. - CNN </td>
   <td style="text-align:left;"> (CNN)On Monday, after intense fighting, Ukrainian forces regained control of Makariv, a town west of Kyiv that had been battered by Russian airstrikes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , It's tempting to view this small victory for Ukrainian forces as a shift of momentum in the battle for Kyiv: In better times, this suburb would be only an hour's drive to Khreshchatyk, the capital's central boulevard.                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Kyiv once appeared to be the primary objective of what the Kremlin must have envisioned as a swift regime-change operation. The capital has been rocked by explosions in recent days, but it is far from encircled.                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , On the Azov Sea, the besieged southeastern city of Mariupol -- despite being surrounded and mercilessly pummeled, block by block, by Russian firepower -- still eludes Russian control. Its defenders rejected an ultimatum to surrender by Monday morning, thwarting a Russian effort to finalize a land bridge linking Crimea with the separatist republics of the eastern Donbas region.                                                                                                                                                                                                                                                                                               , Nearly a month after Russia launched its invasion of Ukraine, the Ukrainian military has perceptibly shifted its messaging. The Russian military's advances have been stymied, the Ukrainians say, forcing a shift in Russian tactics.                                                                                                                                                                                                                                                                                                                                                                                                                                                    , "Due to the lack of success of the ground phase of the operation, the enemy continues to actively launch missile and bomb strikes on important military and civilian infrastructure using operational and tactical aircraft, high-precision missile weapons and indiscriminate munitions," the General Staff of the Armed Forces of Ukraine said in a statement Tuesday.                                                                                                                                                                                                                                                                                                                  , There's plenty of evidence to suggest that the Russians are taking more of a standoff approach, launching salvos of missiles from outside of Ukrainian airspace.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , In a statement released Sunday, Russia's defense ministry said warships in the Caspian sea launched Kalibr cruise missiles and aircraft launched Kinzhal hypersonic missile systems from the airspace over Crimea. Those missiles targeted what the Russians described as a large storage base for fuels and lubricants of the Ukrainian military near the settlement of Kostyantynivka, in the southern Mykolaiv region.                                                                                                                                                                                                                                                                 , Separately, the Russian military said Kalibr cruise missiles were fired from the Black Sea, targeting a workshop for the repair of Ukrainian armored vehicles. Russian precision missiles also targeted what Russia described as a Ukrainian military training center near the settlement of Ovruch, in the northern Zhytomyr region.                                                                                                                                                                                                                                                                                                                                                     , There is an element of PR to such costly displays of firepower: Russia is keen to export a version of the Kalibr and it has touted the Kinzhal as being able to elude missile-defense systems.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The UK defense ministry, for one, was dismissive of Russian claims about the Kinzhal's combat debut, saying its use was "highly likely intended to detract from a lack of progress in Russia's ground campaign. Deployment of Kinzhal is highly unlikely to materially affect the outcome of Russia's campaign in Ukraine."                                                                                                                                                                                                                                                                                                                                                               , Such assessments, however, give little solace to anyone on the receiving end of Russian firepower. Dozens were killed Friday in a missile strike on a barracks housing soldiers in Mykolaiv, and Russian long-distance strikes have struck areas far away from the front lines: At least 35 people were killed in strikes on March 13 against the Yavoriv military training ground in the Lviv region of western Ukraine, not far from the Polish border. More than 30 missiles fired from warplanes over the Black and Azov seas hit the base.                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Still, Russia has thus far not captured any major Ukrainian city in the offensive: neither Kharkiv in the northeast, nor Odesa in the southwest. Even Sumy and Chernihiv in the north, both of which are just across the border from major military staging areas inside Russia, remain under Ukrainian control. And in Kherson, a medium-sized city in the south under Russian control, Russian forces have faced another protracted problem: Angry locals who gather daily in the central square to tell Russian troops go home. One of those rallies ended Monday with one man seriously injured after Russian troops used gunfire and apparent stun grenades to disperse the crowd.   , Military analysts worry about another consequence of this emerging phase of the war: As Russian ground forces become bogged down and make little new progress, their leaders resort more to the indiscriminate and punitive use of firepower against Ukrainian cities.                                                                                                                                                                                                                                                                                                                                                                                                                    , A March 19 assessment by the Institute for the Study of War gave precisely that grim prognosis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , "If the war in Ukraine settles into a stalemate condition, Russian forces will continue to bomb and bombard Ukrainian cities, devastating them and killing civilians, even as Ukrainian forces impose losses on Russian attackers and conduct counter-attacks of their own," the assessment read.                                                                                                                                                                                                                                                                                                                                                                                         , "The Russians could hope to break Ukrainians' will to continue fighting under such circumstances by demonstrating Kyiv's inability to expel Russian forces or stop their attacks even if the Russians are demonstrably unable to take Ukraine's cities. Ukraine's defeat of the initial Russian campaign may therefore set conditions for a devastating protraction of the conflict and a dangerous new period testing the resolve of Ukraine and the West."                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Adding to that gloomy forecast, Ukrainian officials have begun warning of a potential new front in the war, with the country's General Staff saying Sunday the threat of an offensive from Belarus in the direction of northwestern Ukraine was "high," without giving further specifics.                                                                                                                                                                                                                                                                                                                                                                                                 , Ukraine's northwestern Volyn region borders Belarus to the north and Poland, a NATO ally, to the west. It could -- theoretically -- serve as a gateway for attacking forces from the north to approach Lviv, a strategic city in western Ukraine that is a hub for both government logistics and relief efforts, as well as a transit point for many civilians looking to flee fighting in other parts of the country.                                                                                                                                                                                                                                                                    , Russia has already used Belarusian territory as a launching pad for its invasion, with Russian forces staging an offensive push toward Kyiv and central Ukraine from southern Belarus.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , It's unclear if Belarus would actively join the war. But the Ukrainian General Staff is already warning that Russia is now looking to bring in reserve forces to the borders of Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , If true, that speaks volumes. It attests to the high cost the Russian military has already paid in terms of lives -- even though the Kremlin has not disclosed casualty totals since March 2. And it speaks to the political will of one person -- Russian President Vladimir Putin -- to continue expending blood and treasure in Ukraine.                                                                                                                                                                                                                                                                                                                                               , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 01:37:00 </td>
   <td style="text-align:left;"> Wall Street Rebound Accelerates </td>
   <td style="text-align:left;"> US stocks extended their rebound in afternoon trading on Tuesday, with the Dow up more than 250 points, the S&amp;P 500 rising 1% and the Nasdaq advancing 1.7% as investors reassessed the monetary policy outlook following surprisingly hawkish comments from Fed Chair Powell while watching the war in Ukraine. Powell noted that the US central bank could move more aggressively by raising the interest rates by more than 25 basis points at a meeting or meetings to bring inflation, which is now running at 40 years highs, under control. Meanwhile, Russia and Ukraine failed to make progress on the ceasefire, and the shelling of Ukrainian cities continues. On the corporate side, Nike shares climbed 3% as the world's biggest sportswear maker beat quarterly estimates for profit and revenue. Procter &amp; Gamble was 0.5% higher after Truist upgraded the stock to a buy rating. Also, banks continued to outperform along with interest rates with JPMorgan up more than 2%, and Bank of America rising around 3%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/22/5-money-saving-tips-from-a-tiktok-lawyer-who-reads-the-fine-print.html </td>
   <td style="text-align:left;"> 2022-03-23 01:20:09 </td>
   <td style="text-align:left;"> 5 money-saving tips from a TikTok lawyer who reads the fine print </td>
   <td style="text-align:left;"> , Reading the fine print means you could be saving money that you might not have otherwise known about, according to Erika Kullberg, lawyer and founder of Plug and Law, a legal tech start-up for small businesses and entrepreneurs., Kullberg found that you could be eligible for compensation for everything from getting bumped from your flight to having a package arrive after its guaranteed delivery date.                                                       , "Almost every transaction in your life involves a contract whether you're flying with an airline or buying a pair of shoes," she said.                                                                                              , Kullberg has more than 11 million followers across TikTok, Instagram and YouTube.                                                                                                                                                   , Check out this video to learn more about how to save money by reading the fine print.                                                                                                                                               , More from Invest in You:American dream of the middle class isn't what it used to beRetiring with $1 million may leave you less than $2,800 a month to spendYour income tax bill may be cheaper if you live in one of these 5 states , SIGN UP: Money 101 is an eight-week learning course to financial freedom, delivered weekly to your inbox. For the Spanish version Dinero 101, click here.                                                                           , CHECK OUT: How a single mom in Atlanta makes $10,000/month on Outschool while only teaching a few hours a week with Acorns+CNBC                                                                                                     , Disclosure: NBCUniversal and Comcast Ventures are investors in Acorns.                                                                                                                                                              , Got a confidential news tip? We want to hear from you.                                                                                                                                                                              , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                              , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                    , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                    , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                  , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/22/business/economy/ukraine-russia-europe-energy.html </td>
   <td style="text-align:left;"> 2022-03-23 01:17:02 </td>
   <td style="text-align:left;"> Will War Make Europe’s Switch to Clean Energy Even Harder? - The New York Times </td>
   <td style="text-align:left;"> , A wind turbine factory in Denmark and a coal mine in Poland illustrate the painful policy choices after Russia’s aggression in Ukraine added urgency to the transition to greener energy.                                                                                                                                                                                                                                                                                                                                                                , Wind turbine blades built in Denmark by Siemens Gamesa were en route to Taiwan.Credit...Carsten Snejbjerg for The New York Times                                                                                                                                                                                                                                                                                                                                                                                                                         , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                           , By Patricia Cohen and Stanley Reed                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Patricia Cohen, an economics correspondent, and Stanley Reed, who covers energy, reported from Denmark’s Jutland peninsula. Cohen also traveled to Upper Silesia, Poland.                                                                                                                                                                                                                                                                                                                                                                                , At the Siemens Gamesa factory in Aalborg, Denmark, where the next generation of offshore wind turbines is being built, workers are on their hands and knees inside a shallow, canoe-shaped pod that stretches the length of a football field. It is a mold used to produce one half of a single propeller blade. Guided by laser markings, the crew is lining the sides with panels of balsa wood.                                                                                                                                                       , The gargantuan blades offer a glimpse of the energy future that Europe is racing toward with sudden urgency. The invasion of Ukraine by Russia — the European Union’s largest supplier of natural gas and oil — has spurred governments to accelerate plans to reduce their dependence on climate-changing fossil fuels. Armed conflict has prompted policymaking pledges that the more distant threat of an uninhabitable planet has not.                                                                                                               , Smoothly managing Europe’s energy switch was always going to be difficult. Now, as economies stagger back from the second year of the pandemic, Russia’s attack on Ukraine grinds on and energy prices soar, the painful trade-offs have crystallized like never before.                                                                                                                                                                                                                                                                                 , Moving investments away from oil, gas and coal to sustainable sources like wind and solar, limiting and taxing carbon emissions, and building a new energy infrastructure to transmit electricity are crucial to weaning Europe off fossil fuels. But they are all likely to raise costs during the transition, an extremely difficult pill for the public and politicians to swallow.                                                                                                                                                                   , The crisis that has inspired Europe to more quickly reach toward clean energy sources like wind and solar also risks pitching it backward by unwinding efforts to shut coal mines and stop drilling new oil and gas wells to replace Russian fuel and bring prices down.                                                                                                                                                                                                                                                                                 , In Germany, Europe’s largest economy, leaders are planning to have several coal-fired power plants that were recently taken off the grid placed in reserve, so that they could be quickly fired up if needed. After years of dithering about investing so much in the natural gas infrastructure, Germany is also accelerating plans to build its own terminals for receiving liquefied natural gas, another fossil fuel.                                                                                                                                , “Security of our energy supply stands above everything else at the moment,” said Robert Habeck, the country’s economy minister and a Green party leader in the coalition government.                                                                                                                                                                                                                                                                                                                                                                     , Local officials are taking similar steps. Last week, the Munich government decided to extend the life of one of the city’s coal-fired power plants, scrapping plans to convert it to burn natural gas in spring 2023.                                                                                                                                                                                                                                                                                                                                    , And that’s in a country that has helped spearhead Europe’s efforts to shift to renewable energy.                                                                                                                                                                                                                                                                                                                                                                                                                                                         , In Poland, which gets 70 percent of its energy from coal and has been at loggerheads with the European Union over the climate agenda, the sudden energy shortage is being used by critics as evidence that the push to shut mines was a mistake.                                                                                                                                                                                                                                                                                                         , Dominik Kolorz, head of the Silesian region of Solidarity Trade Union, said through a translator that “the so-called E.U. climate policy” was leading to a “huge economic crisis” and “total energy dependence on the Russian Federation.”                                                                                                                                                                                                                                                                                                               , In many ways, Europe has been a leading laboratory for the decades-long transition. It started establishing taxes on carbon emissions more than 20 years ago. The European Union pioneered an emissions trading system, which capped the amount of greenhouse gases companies produced and created a marketplace where licenses for those emissions could be bought and sold. Polluting industries like steel were gradually pushed to clean up. Last year, members proposed a carbon tax on imports from carbon-producing sectors like steel and cement., And it has led the way in generating wind power, especially from ocean-based turbines. Siemens Gamesa Renewable Energy, for example, has been instrumental in planting rows of colossal whirligigs at sea that can generate enough green energy to light up cities.                                                                                                                                                                                                                                                                                      , Europe, too, is on the verge of investing billions in hydrogen, potentially the multipurpose clean fuel of the future, which might be generated by wind turbines.                                                                                                                                                                                                                                                                                                                                                                                        , Such exhilarating innovation, though, sits next to despair-inducing obstacles.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Even before the invasion of Ukraine, a tight natural gas market, exacerbated by Russia’s restraining of supplies, had pushed gas and electricity prices to record levels, leading to shutdowns of fertilizer plants and other factories because of high costs. Household energy bills are set to rise by about 50 percent in Britain and drivers across Europe faced shock at the pump.                                                                                                                                                                  , European countries, most notably Germany, had mapped out strategies that relied on increasing dependence on Russian gas and oil in the medium term. That is no longer an option.                                                                                                                                                                                                                                                                                                                                                                         , After the invasion, Olaf Scholz, the chancellor of Germany, halted approval of Nord Stream 2, an $11 billion gas pipeline under the Baltic Sea that directly links Russia to northeastern Germany.                                                                                                                                                                                                                                                                                                                                                       , As Ursula von der Leyen, the European Commission president, said when she announced a plan on March 8 to make Europe independent of Russian fossil fuels: “We simply cannot rely on a supplier who explicitly threatens us.” The proposal calls for member nations to reduce Russian natural gas imports by two-thirds by next winter and to end them altogether by 2027 — a very tall order.                                                                                                                                                            , This week, European Union leaders are again meeting to discuss the next phase of proposals, but deep divisions remain over how to manage the current price increases amid anxieties that Europe could face a double whammy of inflation and recession.                                                                                                                                                                                                                                                                                                   , On Monday, United Nations Secretary General António Guterres warned that intense focus on quickly replacing Russian oil could mean that major economies “neglect or kneecap policies to cut fossil fuel use.”                                                                                                                                                                                                                                                                                                                                            , There are other technological, financial, regulatory and political hurdles. The ability to cheaply generate, transport and store a clean replacement fuel like hydrogen to power trucks, cars and airplanes remains years away.                                                                                                                                                                                                                                                                                                                          , And there is the need to find a better business model.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Siemens Gamesa is the world’s leading maker of offshore wind turbines, a key vehicle for achieving climate targets. The company is also working on a giant turbine that would be dedicated solely to producing green hydrogen.                                                                                                                                                                                                                                                                                                                           , Yet, at the company’s offshore design center in Brande, a two-hour drive from Aalborg, the conversations focus on worries as much as bright prospects. The company just replaced its chief executive because of poor financial performance.                                                                                                                                                                                                                                                                                                              , Industry executives say that despite the huge climate ambitions of many countries, Siemens Gamesa and its competitors are struggling to make a profit and keep the orders coming in fast enough to finance their factories. It doesn’t help that building plants is often a condition for breaking into new markets like the United States, where Siemens Gamesa agreed to erect a facility in Virginia.                                                                                                                                                 , Morten Pilgaard Rasmussen, chief technology officer of the offshore wind unit at Siemens Gamesa, said that companies like his “are now forced to do investments based on the prosperous future that we are all waiting for.”                                                                                                                                                                                                                                                                                                                             , Rising concerns. Russia’s invasion on Ukraine has had a ripple effect across the globe, adding to the stock market’s woes and spooking investors. The conflict has already caused​​ dizzying spikes in energy prices, and could severely affect various countries and industries.                                                                                                                                                                                                                                                                          , The cost of energy. Oil prices already were the highest since 2014, and they have continued to rise since the invasion.  Russia is the third-largest producer of oil, so more price increases are inevitable.                                                                                                                                                                                                                                                                                                                                            , Gas supplies. Europe gets nearly 40 percent of its natural gas from Russia, and it is likely to be walloped with higher heating bills. Natural gas reserves are running low, and European leaders worry that Moscow could cut flows in response to the region’s support of Ukraine.                                                                                                                                                                                                                                                                      , Food prices. Russia is the world’s largest supplier of wheat; together, it and Ukraine account for nearly a quarter of total global exports. Countries like Egypt, which relies heavily on Russian wheat imports, are already looking for alternative suppliers.                                                                                                                                                                                                                                                                                         , Shortages of essential metals. The price of palladium, used in automotive exhaust systems and mobile phones, has been soaring amid fears that Russia, the world’s largest exporter of the metal, could be cut off from global markets. The price of nickel, another key Russian export, has also been rising.                                                                                                                                                                                                                                            , Financial turmoil. Global banks are bracing for the effects of sanctions intended to restrict Russia’s access to foreign capital and limit its ability to process payments in dollars, euros and other currencies crucial for trade. Banks are also on alert for retaliatory cyberattacks by Russia.                                                                                                                                                                                                                                                     , Mr. Rasmussen and other executives added that identifying suitable areas for wind turbines and obtaining permits required for construction take “far too long.” Challenges are based on worries that the vast arrays of turbines will interfere with fishing, obstruct naval exercises and blight views from summer houses.                                                                                                                                                                                                                              , To Kadri Simson, Europe’s commissioner for energy, renewable energy projects should be treated as an “overriding public interest,” and Europe should consider changing laws to facilitate them.                                                                                                                                                                                                                                                                                                                                                          , “We cannot talk about a renewables revolution if getting a permit for a wind farm takes seven years,” Ms. Simson said.                                                                                                                                                                                                                                                                                                                                                                                                                                   , Still, environmental regulations and other rules relating to large infrastructure installations are usually the province of countries rather than European Union officials in Brussels.                                                                                                                                                                                                                                                                                                                                                                  , And steadfast opposition from communities and industries invested in fossil fuels make it hard for political leaders to fast-track energy transition policies.                                                                                                                                                                                                                                                                                                                                                                                           , In Upper Silesia, Poland’s coal basin, bright yellow buses display signs that boast they run on 100 percent electric, courtesy of a grant from the European Union. But along the road, large billboards mounted before the invasion of Ukraine by state-owned utilities — erroneously — blame Brussels for 60 percent of the rise in energy prices.                                                                                                                                                                                                      , Down in the Wujek coal mine, veterans worry if their jobs will last long enough for them to log the 25 years needed to retire with a lifelong pension. Closing mines not only threatens to devastate the economy, several miners said, but also a way of life built on generations of coal mining.                                                                                                                                                                                                                                                       , “Pushing through the climate policy forcefully may lead to a drastic decrease in the standard of living here,” said Mr. Kolorz at Solidarity’s headquarters in Katowice. “And when people do not have something to put on the plate, they can turn to extreme populism.”                                                                                                                                                                                                                                                                                 , Climate pressures are pushing at least some governments to consider steps they might not have before.                                                                                                                                                                                                                                                                                                                                                                                                                                                    , German officials have determined that it is too costly to keep the country’s last three remaining nuclear power generators online past the end of the year. But the quest for energy with lower emissions is leading to a revival of nuclear energy elsewhere.                                                                                                                                                                                                                                                                                           , Britain and France say they plan to invest in smaller nuclear reactors that can be produced in larger numbers to bring down costs.                                                                                                                                                                                                                                                                                                                                                                                                                       , Britain might even build a series of small nuclear fusion reactors, a promising but still unproven technology. Ian Chapman, chief executive of the U.K. Atomic Energy Authority, said every route to clean energy must be tried if there is to be any hope of reaching net zero emissions in three decades, the deadline for avoiding catastrophic climate change. “We’ve got to do everything we possibly can,” he said.                                                                                                                                , In the short term, much of what the European Union is proposing involves switching the source of fossil fuels, and, in particular, natural gas, from Russia to other suppliers like the United States, Qatar and Azerbaijan, and filling up storage facilities as a buffer. The risk is that Europe’s actions will further raise prices, which are already about five times higher than a year ago, in a market where supplies are short in part because companies are wary of investing in a fuel that the world ultimately wants to phase out.         , Over the longer term, Europe and Britain seem likely to accelerate their world-leading rollout in renewable energy and other efforts to cut emissions despite the enormous costs and intense disruptions.                                                                                                                                                                                                                                                                                                                                                , “The E.U. will almost certainly throw hundreds of billions of euros at this,” said Henning Gloystein, a director for energy and climate at Eurasia Group, a political risk firm. “Once the trains have left the station, they can’t be reversed.”                                                                                                                                                                                                                                                                                                        , Melissa Eddy contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/currency </td>
   <td style="text-align:left;"> 2022-03-23 01:16:00 </td>
   <td style="text-align:left;"> Russian Ruble Strengthens Slightly </td>
   <td style="text-align:left;"> The Russian ruble was slightly higher at the 99 per USD level, as investors weighed the recovery in Russian bond markets. The Central Bank of Russia said it would purchase OFZ bonds to limit volatility that was recently pressured Russian assets, even though it has not disclosed the size of its interventions that helped stabilize prices and provided extra liquidity to the financial system. Markets also sighed relief after Russia paid a coupon on its Eurobond due in 2029, marking the second successful debt payment in the past week. The ruble tumbled to as low as 150 per dollar in offshore markets earlier in March amid an unprecedented barrage of Western sanctions for the invasion of Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 01:00:00 </td>
   <td style="text-align:left;"> South African Stocks Close at Near 3-Week High </td>
   <td style="text-align:left;"> The JSE FTSE All Share index rose about 1.2% to finish at 75,751 on Tuesday, its highest since March 3rd, mainly driven by banks after Fed Chairman Jerome Powell reiterated the central bank’s commitment to controlling inflation through a rapid series of interest-rate increases if appropriate. At the same time, traders continued to monitor the war in Ukraine and possible new sanctions against Russia. Domestically, traders will closely watch inflation data and the monetary policy decision later in the week. The South African Reserve Bank is likely to hike interest rates by a further 25 basis points this week to 4.25% in an attempt to slow inflation, and likely adopt a more hawkish tone. On the earnings front, a major coal exporter, Thungela Resources, posted stellar results for the year ended in December thanks to greater demand and strong coal prices, and declared a dividend payout on its first full-year result as a listed company. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 00:54:57 </td>
   <td style="text-align:left;"> Madrid Stocks End at 1-Month High </td>
   <td style="text-align:left;"> The Ibex 35 extended gains to close 1.2% higher at 8,487 on Tuesday, its highest since February 22, mainly supported by banks following hawkish remarks by US Fed Chairman Jerome Powell, suggesting interest rates would have to rise much faster than previously anticipated. Meanwhile, investors continued to monitor the situation in Ukraine and inflationary risks including rising energy costs stemming from a prolonged war and possible new sanctions against Russia. Locally, Spain has pledged 500 million euros in aid to lower fuel costs for truckers in a bid to end a week-long protest disrupting trade. Spanish Prime Minister Pedro Sanchez said that the measures will be approved at a cabinet meeting on March 29th. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 00:51:22 </td>
   <td style="text-align:left;"> UK Stocks Rise to Nearly 4-Week High </td>
   <td style="text-align:left;"> The FTSE 100 added more than 0.5% to above 7,480 on Tuesday, the highest since February 25th, as energy stocks continued to climb amid the rally in crude oil futures, offsetting concerns about the war in Ukraine, which is nearing its fourth week. The slow progress in cease-fire talks, as well as the ongoing bombing of urban areas, are pressuring Prime Minister Borish Johnson to take tougher sanctions against Russia, which could send the economy into a recession. On the earnings front, British DIY retailer Kingfisher saw adjusted earnings climb 20.9% to £949M in FY 2021-22, in line with analyst forecasts, benefiting from a DIY pandemic trend. Now, traders look forward to the Spring budget speech by the UK’s Finance Minister Sunak on Wednesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/22/stocks-making-the-biggest-moves-midday-nike-pfizer-alibaba-carnival-and-more.html </td>
   <td style="text-align:left;"> 2022-03-23 00:49:24 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Nike, Pfizer, Alibaba, Carnival, GameStop and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                             , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                 , Nike — Shares of Nike jumped 2.2% after the company reported a beat on the top and bottom lines in the third quarter. The retailer reported earnings of 87 cents per share on revenues of $10.87 billion, topping analysts' estimates of 71 cents per share on revenues of $10.59 billion. Nike delayed giving its outlook for the year.                    , GameStop – Shares of the video-game retailer jumped 30.7%. There was no clear reason behind the move. The firm reported quarterly results last week, posting a per-share loss of $1.86 compared to expected earnings of 85 cents per share, according to FactSet's StreetAccount. Shares of AMC Entertainment, a fellow meme-stock favorite, also leapt 11%., Datadog — Shares of the software company jumped 6% after investment firm BTIG initiated coverage of the stock with a buy rating. BTIG said in a note to clients that Datadog is set up for near- and long-term success.                                                                                                                                     , Alibaba — Shares of the China-based e-commerce giant jumped 11% after the company increased its share buyback program to $25 billion from $15 billion, effective for a two-year period through March 2024. Alibaba also appointed Weijian Shan, executive chairman of Hong Kong-headquartered investment group PAG, to its board as an independent director., Goldman now sees the Fed hiking by a half point at the next two meetingsRetail investors just posted the longest streak of buying bank stocks since 2008, BofA saysBuffett's buying spree may continue — Here's what Wall Street analysts say about the Alleghany deal                                                                                      , Tencent Music Entertainment — The entertainment services company saw its shares jump 9.6% after it reported better-than-expected earnings for the most recent quarter. Tencent Music also said it would pursue a secondary listing on the Hong Kong Stock Exchange.                                                                                         , Pfizer — The biopharmaceutical giant's stock price slipped 2.1% after the company said it will distribute up to four million treatment courses of its oral Covid pill to dozens of poorer nations in a partnership with the United Nations Children's Fund.                                                                                                 , Okta — Shares of the authentication and identity management firm fell 1.7% on news of a potential breach from a hacking group. Okta said it had "detected an attempt to compromise the account of a third party customer support engineer working for one of our subprocessors" but found no new evidence of an attack.                                     , Alphabet — The tech giant's stock price spiked 2.7% after Google's parent company spun off Sandbox AQ, a quantum computing start-up that includes former Google CEO Eric Schmidt as investor and chairman of the board.                                                                                                                                     , Sherwin-Williams — The paint company's shares gained 1.7% after Bank of America upgraded the stock to a buy from neutral. Analyst Steve Byrne said the issues facing the chemicals sector are already accounted for in the stock price and that the shares could be a way to bet on the U.S. economy over Europe.                                           , Carnival — The cruise company slipped less than 1% after it provided a business update for the first quarter that includes a net loss of $1.9 billion, compared with estimates of $1.36 billion, according to FactSet's StreetAccount. Carnival also reported revenues of $1.62 billion, compared to estimates of $2.26 billion.                            , Energy stocks — Several energy stocks were lower on Tuesday and were the top decliners in the S&amp;P 500 after jumping in the previous session, as investors paused to take profits. Hess and Occidental declined more than 2%. EOG, Diamondback and Marathon declined more than 1%. Energy is the only sector in the green so far in 2022.                    , — CNBC's Samantha Subin, Sarah Min and Jesse Pound contributed reporting                                                                                                                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 00:48:00 </td>
   <td style="text-align:left;"> Italian Stocks Extend Gains on Tuesday </td>
   <td style="text-align:left;"> The FTSE MIB index closed 1% up at the three-week high of 24,534 on Tuesday, extending last week’s rally. Banking shares edged higher on the prospect of more aggressive monetary tightening by the Federal Reserve. Chairman Powell said the central bank does not exclude the possibility of hiking the funds rate by more than 25bps, prompting the financial sector in Milan to jump over 1.3%, led by Intesa Sanpaolo (1.7%). Investors also welcomed Russia’s latest interest payment on sovereign bonds, further easing concerns of sovereign default. Atlantia shares (3.2%) continued to rally, uplifted by its increased guidance and the approval of the sale of its unit, Autostrade, by the Italian audit court. At the same time, Leonardo (0.4%) extended its rally after announcing it will sell its subsidiary Global Enterprise Solutions from USD 450 millions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/goldman-warns-markets-risks-russia-ukraine-war </td>
   <td style="text-align:left;"> 2022-03-23 00:47:15 </td>
   <td style="text-align:left;"> Goldman warns markets too relaxed on Russia-Ukraine war risks </td>
   <td style="text-align:left;"> BMO Capital Markets chief investment strategist Brian Belski weighs in on the February jobs report and market volatility.                                                                                                                                                                                                                                                                                 , Global markets may be underestimating the downside risks posed to stocks by the ongoing war between Russia and Ukraine, according to Goldman Sachs strategists.                                                                                                                                                                                                                                           , Although the Russian invasion of Ukraine in late February initially triggered a sharp market correction, many major stock indexes have since rebounded: The S&amp;P 500, Nasdaq Composite and Dow Jones Industrial Average have all erased their initial losses and eclipsed levels recorded before the conflict began, and similar trends have been recorded in Europe.                                      , RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                                                      , But in a Thursday analyst note, the Goldman strategists led by Dominic Wilson and Vickie Chang said the recent trends indicate the market is not braced for the war to worsen, with the fallout potentially rippling throughout the global economy.                                                                                                                                                       , People walk past a currency exchange office screen displaying the exchange rates of U.S. Dollar and Euro to Russian Rubles in Moscow's downtown. (AP Photo/Pavel Golovkin / AP Newsroom)                                                                                                                                                                                                                  , "Our downside case is no longer well reflected in many areas and it is now easier to identify potential hedges than it has been for several weeks," the strategists wrote. "This points to a significant relaxation in the market’s assessment of the global implications of the Ukraine invasion."                                                                                                       , The analysts said that because of easing concerns among investors, assets could prove even more vulnerable if Ukraine and Russia are unable to find a peaceful resolution to the worsening conflict humanitarian crisis.                                                                                                                                                                                  , "While many assets could shift further to our upside case, they are now more vulnerable if progress toward a resolution proves fleeting or if energy supplies are disrupted more severely," they wrote.                                                                                                                                                                                                   , The U.S. economy's growth is likely slowing as 2020 comes to a close, but a growing number of economists expect it to claw back to its pre-pandemic strength by the second half of next year (AP Photo/Mark Lennihan / AP Newsroom)                                                                                                                                                                       , Under Goldman's downside scenario, a severe disruption in gas flowing from Russia could trim 2.5 percentage points from European economic output and 0.25 points from the U.S. gross domestic product this year. And if the war continues to deteriorate, it could shave about 10% from the S&amp;P 500's level on Tuesday afternoon (from 4,504 to 4,059).                                                   , Economists at Goldman already trimmed their forecast for economic growth this year to 1.75% from 2.0% and noted that such an outlook means there is a "higher risk" of about 20% to 35% that the U.S. enters a recession over the next year.                                                                                                                                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                               , A car burns at the side of a maternity hospital that was damaged by shelling in Mariupol, Ukraine, on March 9, 2022. (AP Photo/Evgeniy Maloletka / AP Newsroom)                                                                                                                                                                                                                                           , "While our baseline forecast assumes that further service sector reopening and spending from excess savings will keep real GDP growth positive in the coming quarters, uncertainty around the outlook is higher than normal," a different analyst note said. "We view the risks of a recession as broadly in line with the 20-35% odds currently implied by models based on the slope of the yield curve." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 00:47:00 </td>
   <td style="text-align:left;"> European Stocks Regain Ground </td>
   <td style="text-align:left;"> Major European stock indices finished Tuesday's session on a high note, with the benchmark DAX 30 climbing over 1% and the STOXX 600 rising 0.7%, with financial stocks leading the gains. Federal Reserve Chair Powell said the US central bank could raise rates more than its usual 25bps in May to tame inflation. Meanwhile, investors continued to worry that dragging on of the fighting in Ukraine could result in new sanctions on Russia, targeting its energy sector and adding to inflationary pressures. On the corporate side, German software maker Nemetschek jumped more than 11% after posting full-year solid results and an upbeat outlook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-03-23 00:46:00 </td>
   <td style="text-align:left;"> French Stocks End at 3-Week High </td>
   <td style="text-align:left;"> The CAC 40 ended 1.17% higher to close at 6659.41 on Tuesday, the highest since February 25th, boosted by banking stocks amid bigger than expected rate hike prospects by the US Fed. At the same time, investors continued to monitor the war situation in Ukraine as Russia and Ukraine failed to make any progress in their peace talks and the European Union considers new trade sanctions on Russia. Among the individual stocks, 26 out of 30 stocks ended in the green with gains coming particularly from WFD Unibail Rodamco (+3.58%), Airbus Group (+2.79%),Veolia Environment (+2.55%), Loreal (2.31%), ArcelorMittal (+2.11%) and Engie(2.04%). On the other hand, shares of Air Liquide dragged by 0.34% as investors were disappointed with its 2025 strategic plan,which did not include share buyback options. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/poland-protesters-stop-trucks-from-entering-belarus-in-effort-to-halt-trade-with-russia </td>
   <td style="text-align:left;"> 2022-03-23 00:44:06 </td>
   <td style="text-align:left;"> Ukrainian anti-war activists at Poland-Belarus border stop trucks in effort to halt trade with Russia </td>
   <td style="text-align:left;"> FOX Business' Ashley Webster reports from Poland on the protest held in an effort to halt trade with Russia.                                                                                                                                                                                                                                                                                                             , Poland protesters have been disrupting a major trade route between the country and Belarus by stopping trucks from entering, in an effort to halt trade with Russia as the war in Ukraine rages on.                                                                                                                                                                                                                      , A group of protesters blocked the road at the Koroszczyn border point, calling for a ban on trade with Russia and its ally Belarus.                                                                                                                                                                                                                                                                                      , FOX Business’ Ashley Webster reported on the protest from Koroszczyn where he noted on "Varney &amp; Co." that because Ukrainian anti-war activists blocked the entrance for trucks at the border of Poland and Belarus, traffic was backed up for 30 miles and included more than 1500 trucks on Tuesday.                                                                                                                   , He also reported that many of the demonstrators are displaced Ukrainian refugees and that the backup has been going for several weeks.                                                                                                                                                                                                                                                                                   , Webster noted that "tempers flared" earlier on Tuesday as angry drivers confronted the protesters.                                                                                                                                                                                                                                                                                                                       , BIDEN CALLS FOR END TO NORMAL RUSSIA TRADE RELATIONS, BAN ON SEAFOOD, VODKA, DIAMOND IMPORTS                                                                                                                                                                                                                                                                                                                             , Protesters reportedly argued that the trucks shouldn’t be allowed to cross the border because they will generate trade, which, in turn, will generate money for Russia’s invasion of Ukraine. The protestors also reportedly stressed that the trade route is a way for Russian President Vladimir Putin to circumvent sanctions and bring in goods through the freight lines and, therefore, it should not be allowed.  , Hermitage Capital Management CEO Bill Browder argues that 'by the time the West is done, we will have totally blockaded Russia economically.'                                                                                                                                                                                                                                                                            , The United States and its Western allies have imposed crippling sanctions against Russia over its invasion of Ukraine, which include those on Russian banks, oligarchs, and President Vladimir Putin himself. The Western sanctions are dealing a severe blow to Russia’s economy.                                                                                                                                       , Webster reported that as of Tuesday, the trucks are allowed to cross the border, however, protesters are appealing to the European Union to cut off the trade route between Poland into Belarus and to Russia.                                                                                                                                                                                                           , Poland’s Prime Minister Mateusz Morawiecki called on the EU to halt all land and sea trade with Russia as he commented on the protest on Saturday.                                                                                                                                                                                                                                                                       , The former assistant secretary of defense joined 'Kudlow' to discuss sanctioning Russia as Putin's war on Ukraine continues.                                                                                                                                                                                                                                                                                             , Webster said he spoke with one Russian truck driver named Alexander, who was transporting a shipment of frozen potatoes.  The driver said that he has nothing to do with the war, but is merely trying to make a living to support his family.                                                                                                                                                                           , "It’s not for the war, it is only for our family," he said, adding that "we [are] doing this work for people, not for Russia."                                                                                                                                                                                                                                                                                           , The latest round of the protest, which has been on and off for about two weeks in eastern Poland, began early Saturday.                                                                                                                                                                                                                                                                                                  , FOX Business’ Ashley Webster reported from live the border between Poland and Belarus as protesters disrupt a major shipping route.                                                                                                                                                                                                                                                                                      , Early Sunday, about 950 trucks were waiting to cross into Belarus, according to a spokesman for the local tax office, who noted that the wait time was 32 hours.                                                                                                                                                                                                                                                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                              , Police were called to the scene as they separated protesters from the trucks and drivers, road infrastructure authorities said.                                                                                                                                                                                                                                                                                          , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                  , FOX Business’ Bradford Betz and The Associated Press contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/gas-prices-average-6-los-angeles-california </td>
   <td style="text-align:left;"> 2022-03-23 00:39:09 </td>
   <td style="text-align:left;"> Los Angeles gas prices hit average of $6 </td>
   <td style="text-align:left;"> GasBuddy.com head of petroleum analysis Patrick De Haan provides money tips amid record-high gas prices.                                                                                                                                                                                                                                                                                                                                                 , Gas prices in Los Angeles have hit a new record, making it the first major city in the country to reach an average of $6 for a regular gallon of gasoline, according to Patrick De Haan, head of petroleum analysis for GasBuddy.                                                                                                                                                                                                                        , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                  , This comes after the city reached an average of $5 per gallon just a few weeks ago, according to De Haan.                                                                                                                                                                                                                                                                                                                                                , Gas prices are advertised at over six dollars a gallon Monday, March 7, 2022, in Los Angeles.  ((AP Photo/Marcio Jose Sanchez) / AP Newsroom)                                                                                                                                                                                                                                                                                                            , Prices in California are still the highest in the country and have far surpassed the national average which has fallen slightly from its highs earlier this month.                                                                                                                                                                                                                                                                                       , Currently, the national average for a gallon of regular gasoline slipped 9 cents from a week ago and stands at $4.24, according to AAA. By comparison, the average in California is sitting at $5.866 per gallon.                                                                                                                                                                                                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                              , Lawmakers in California have been under pressure to offset this surge. Recently, California Democrats unveiled a new proposal that would send a $400 rebate to every taxpayer in the state.                                                                                                                                                                                                                                                              , The money would go to all California taxpayers – not just motorists.                                                                                                                                                                                                                                                                                                                                                                                     , GAS PRICES COULD CONTINUE TO FALL, BUT CALIFORNIA WON'T SEE MUCH RELIEF: EXPERT                                                                                                                                                                                                                                                                                                                                                                          , Gas prices are displayed at a gas station in Long Beach, Calif., Wednesday, March 9, 2022.  (AP Photo/Ashley Landis / AP Newsroom)                                                                                                                                                                                                                                                                                                                       , "This proposed $400 rebate would cover the current 51 cents-per-gallon gas tax for one full year, 52 trips to the pump for most vehicles," the lawmakers wrote in a letter addressed to Gov. Gavin Newsom. "Notably, we believe a rebate is a better approach than suspending the gas tax – which would severely impact funding for important transportation projects and offers no guarantee that oil companies would pass on the savings to consumers.", FOX Business' Megan Henney contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/tesla-stock-up-elon-musk/story.aspx?guid={BD2E643F-2CC2-4408-AE6A-D6ED9E10AAAD}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-23 00:37:02 </td>
   <td style="text-align:left;"> Tesla stock up as Elon Musk cuts ribbon on Berlin Gigafactory expected to produce 500,000 vehicles a year - MarketWatch </td>
   <td style="text-align:left;"> Tesla Inc. shares 
        TSLA,
        +7.91%
       rose 2% Tuesday, as Chief Executive Elon Musk cut the ribbon on the company's first manufacturing facility in Europe, its 5.5 billion euro ($5.5 billion) Gigafactory in Berlin. The plant is based in Gruenheide, a coal town that sits within commuting distance of the German capital. Musk did a dance as he oversaw the delivery of the first German-made Tesla vehicles to 30 clients and their families, CNBC reported. The ceremony was also attended by protesters, who are concerned at the high amount of water it will use and the number of trees that were felled to build it. The factory is expected to produce up to 500,000 electric cars a year. Wedbush analyst Dan Ives, a Tesla bull, said the Berlin plant is "one of the biggest strategic endeavors for Tesla over the last decade and should further vault its market share within Europe over the coming years as more consumers aggressively head down the EV path." In a note to clients published Monday, Ives said the decision by the German authorities to clear the plant to start production removes a major overhang on the stock for the past few months. "We cannot stress the production importance of Giga Berlin to the overall success of Tesla's footprint in Europe and globally, as the current Rubik's Cube logistics of producing cars in China at Giga Shanghai and delivering to customers throughout Europe was not a sustainable trend," the analyst wrote. Wedbush has an outperform rating on Tesla stock and a 12-month price target of $1,400 that is about 58% above its current price. Tesla shares have gained 40% in the last 12 months, but are down about 11% in 2022 to date, while the S&amp;P 500 
        SPX,
        +1.13%
       has fallen 6%. , Alibaba Group Holding Ltd. undefined announced late Monday that it was upsizing its share-buyback program. The Chinese e-commerce giant is now authorized to repurchase up to $25 billion in shares, whereas the prior authorization was for $15 billion. The program will be effective for a two-year period that ends in March 2024. Alibaba disclosed that it bought back about $9.2 billion in American depositary shares as of March 18 through its previously announced repurchase program. The upsized program represents "a sign of confidence about the company's continued growth in the future," Alibaba said in a press release. Further, the company announced that Weijian Shan, the executive chairman of investment-management group PAG, has been appointed an independent director to the company's board of directors. The appointment will be effective March 31, at which time Börje Ekholm, the chief executive of the Ericsson Group, will retire from Alibaba's board after having served on it since June 2015. Shares of Alibaba have fallen about 16% over the past three months.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Ciara Linnane is MarketWatch's investing- and corporate-news editor. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/cdc-ba2-subvariant-makes-up/story.aspx?guid={356D1884-35D3-477C-B2DC-D097E03204E6}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-23 00:32:50 </td>
   <td style="text-align:left;"> CDC: BA.2 subvariant makes up one-third of COVID-19 cases in the U.S.  - MarketWatch </td>
   <td style="text-align:left;"> The BA.2 subvariant now makes up an estimated 34.9% of COVID-19 cases in the U.S., according to the most recent data from the Centers for Disease Control and Prevention. That's up from the estimated 23.1% of new cases reported a week ago. BA.2 is a subvariant of omicron and is more transmissible than omicron. The number of new cases in the U.S. continues to decline; the seven-day moving average was 27,786, as of Sunday, according to the CDC. However, cases are rising in many parts of the world, including China and several European countries., A new surge in parts of Europe is increasing worries that yet another bump in cases could hit the U.S. this spring.                                                                                                                                                                                                                                                                                                                                                                                                                                                ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-03-23 00:26:52 </td>
   <td style="text-align:left;"> Gasoline Futures Snap 3-Day Rally </td>
   <td style="text-align:left;"> Gasoline futures eased to $3.3 a gallon, after rallying more than 12% in the previous three sessions, as EU countries were divided over slapping a ban on Russian oil imports. Lithuania and Ireland’s foreign ministers said the EU should toughen its stance on Russia and target the lucrative energy sector, but countries that are more reliant on Russian oil, such as Germany, were less inclined to do so. However, should Kyiv be heavily bombarded, or Russia use chemical weapons, EU officials said there would be no taboos. Meanwhile, OPEC+ output still lags behind agreed quotas and Houthi attacks on Saudi’s oil industry infrastructures added to the upside risks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/coffee </td>
   <td style="text-align:left;"> 2022-03-23 00:13:00 </td>
   <td style="text-align:left;"> Arabica Coffee at Near 2-Week High </td>
   <td style="text-align:left;"> Arabica coffee futures on ICE rose to around $2.3, its highest since March 9th, amid a stronger real, signs of tight supply due to unfavorable weather in top producer Brazil and supply chain disruptions. The latest provisional outlook of the International Coffee Organization (ICO) for total coffee production in 2021/22 was 167.2 million bags, a 2.1% decrease from 170.83 million bags a year ago. Arabica production only is expected to decline by 7.1% to 93.97 million bags, from 101.16 million bags in 2020/21. Meanwhile, total coffee consumption is projected to grow by 3.3%, to an all-time high of 170.3 million bags in 2021/22 as compared to 164.9 million in 2020/21. This will cause a deficit of 3.128 million bags following a surplus of almost 6 million bags in 2020/21. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/22/europe/belarus-ukraine/index.html </td>
   <td style="text-align:left;"> 2022-03-22 23:53:46 </td>
   <td style="text-align:left;"> Belarusian military could 'soon' join war in Ukraine, US and NATO officials say - CNN </td>
   <td style="text-align:left;"> Washington (CNN)The US and NATO believe that Belarus could "soon" join Russia in its war against Ukraine, US and NATO officials tell CNN, and that the country is already taking steps to do so.                                                                                                                                                                                                               , It is increasingly "likely" that Belarus will enter the conflict, a NATO military official said on Monday. "(Russian President Vladimir) Putin needs support. Anything would help," the official explained.                                                                                                                                                                                                    , A Belarusian opposition source said that Belarusian combat units are ready to go into Ukraine as soon as in the next few days, with thousands of forces prepared to deploy. In this source's view, this would have less of an impact militarily than it will geopolitically, given the implications of another country joining the war.                                                                        , A senior NATO intelligence official said separately that the alliance assesses that the Belarusian government "is preparing the environment to justify a Belarusian offensive against Ukraine."                                                                                                                                                                                                                , Russia has launched its attack on Ukraine in part from Belarus' territory, and thousands of Russian troops amassed in Belarus ahead of the Kremlin's invasion of Ukraine last month, which the two countries had claimed was for training exercises. US and European sanctions in response to the war have targeted both Russian and Belarusian officials, including Belarusian President Alexander Lukashenko., Belarus moved to change its constitution last month to allow the country to host both Russian forces and nuclear weapons permanently, though US officials have emphasized to CNN that they have not yet seen any evidence of Russia moving nuclear weapons or preparing to.                                                                                                                                    , The sources emphasized that there have been no indications to date that Belarus is currently participating in the fighting in Ukraine, and a senior US defense official said the Pentagon had not seen "any indications that the Belarusians are preparing to move in -- into Ukraine or that they have made any agreements to do that."                                                                       , The NATO military official said that a final decision for Belarus' involvement in the war still has to be made in Moscow, as of yet there has been no indication that Belarusian forces are participating in the fighting in Ukraine.                                                                                                                                                                          , "It is not about what Lukashenko wants," the official explained. "The question is: does Putin want another unstable country in the region?"                                                                                                                                                                                                                                                                    , "Involvement would destabilize Belarus," the official said.                                                                                                                                                                                                                                                                                                                                                    , The official wouldn't elaborate on how Belarus could intervene in the war, but said it made sense for Russia to try and cut off NATO military aid coming into Ukraine from its Western border.                                                                                                                                                                                                                 , CNN's Jennifer Hansler and Jeremy Herb contributed reporting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/22/great-resignation-continues-as-44percent-of-workers-seek-a-new-job.html </td>
   <td style="text-align:left;"> 2022-03-22 23:31:25 </td>
   <td style="text-align:left;"> The Great Resignation continues, as 44% of workers look for a new job </td>
   <td style="text-align:left;"> , Almost half of employees are looking for a new job or plan to soon, according to a survey, suggesting the pandemic-era phenomenon known as the Great Resignation is continuing into 2022.                                                                                                                                                                                       , To that point, 44% of employees are "job seekers," according to Willis Towers Watson's 2022 Global Benefits Attitudes Survey. Of them, 33% are active job hunters who looked for new work in the fourth quarter of 2021, and 11% planned to look in the first quarter of 2022.                                                                                                  , "The data shows employees are prepared and open to go somewhere else," according to Tracey Malcolm, global leader of the future of work and risk at the consulting firm.                                                                                                                                                                                                        , The survey polled 9,658 U.S. employees from large and midsize private employers across a broad range of industries in December 2021 and January 2022.                                                                                                                                                                                                                           , The Great Resignation, also known as the Great Reshuffle, has been a hallmark of the U.S. labor market since spring 2021, when the economy began emerging from its pandemic hibernation and demand for workers grew among businesses.                                                                                                                                           , Job openings and quits swelled to historic highs, and layoff rates fell to record lows. Wages grew at a fast clip as businesses competed for talent.                                                                                                                                                                                                                            , Nearly 4.3 million people quit their jobs in January, just shy of a monthly record set in November, according to most recent federal data. Almost 48 million people quit in 2021, an annual record.                                                                                                                                                                             , Data suggests most aren't quitting to sit on the sidelines — a strong job market with ample opportunities and higher pay are luring them to find work elsewhere, according to economists. Some are reinventing their careers altogether.                                                                                                                                        , Over half of workers (56%) said pay is a top reason they'd look for a job with a different employer, according to the survey. Forty-one percent would leave for a 5% increase.                                                                                                                                                                                                  , Households have been battling persistently high inflation, which has eaten into budgets and outstripped raises for the average worker.                                                                                                                                                                                                                                          , But almost 20% said they'd take a new job for the same pay — suggesting factors other than wages are important, too. Health benefits, job security, flexible work arrangements and retirement benefits were behind pay, respectively, as the top five reasons employees would move elsewhere.                                                                                   , "Some are leaving for a nudge up in pay, but some aren't," Malcolm said.                                                                                                                                                                                                                                                                                                        , One of the biggest disconnects between workers and employers is around remote work, Malcom said. Employees want more remote work than they expect their current employer to allow.                                                                                                                                                                                              , More from Personal Finance:Odds are, you're better off buying an index fund. Here's whyThere are 4 weeks until the tax deadlineWhat to do when your monthly Social Security check isn't enough                                                                                                                                                                                  , Currently, 26% of survey respondents are always or mostly working from home, and 15% have an equal split between home and the office; but higher shares (36% and 22%, respectively) would prefer remote work.                                                                                                                                                                   , "[Employers] are revving up a return to onsite [work]," Malcolm said. "I think companies need to be careful what they're revving up; it may not be the model employees want."                                                                                                                                                                                                   , Less time commuting, lower costs associated with going to the office and better management of household commitments are the three biggest benefits workers see with remote work, according to the survey. They see disadvantages, too: lack of social interactions at work, feeling disconnected and greater challenge to build relationships round out the top three drawbacks., Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                          , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                          , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                              , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60835389?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-22 23:30:48 </td>
   <td style="text-align:left;"> Tesla: Elon Musk opens delayed 'gigafactory' in Berlin </td>
   <td style="text-align:left;"> Tesla boss Elon Musk has opened a huge electric car "gigafactory" near Berlin which is the first European hub for the firm.                                                                                       , The plant was delayed for eight months after local authority licensing problems.                                                                                                                                  , The more than €5bn (£4bn) factory is the biggest investment in a German car plant in recent history.                                                                                                              , Tesla said more than 3,000 of the factory's expected 12,000 workers had been hired so far.                                                                                                                        , Mr Musk said: "This is a great day for the factory," describing it as "another step in the direction of a sustainable future".                                                                                    , German Chancellor Olaf Scholz said the plant was a sign of progress and the future of the car industry.                                                                                                           , But outside, environmental groups protested over concerns ranging from the plant's water use to the trees felled to build it.                                                                                     , Tesla will deliver its first 30 German-made Model Y Performance cars on Tuesday. The firm says the cars have a 514km (320 mile) range and cost €63,990 (£53,000).                                                 , At full capacity, the plant will produce 500,000 cars annually - more than the 450,000 battery-electric vehicles that German rival Volkswagen sold globally in 2021.                                              , It will also generate 50 gigawatt hours (GWh) of battery power.                                                                                                                                                   , For now, Volkswagen still holds the upper hand in Europe's electric vehicle market, with a 25% market share to Tesla's 13%.                                                                                       , Mr Musk has said ramping up production will take longer than the two years it took to build the plant.                                                                                                            , Tesla received the final go-ahead from local authorities on 4 March to begin production, provided it met several conditions, covering issues such as water use and air pollution control.                         , The carmaker had come close to losing its water supply contract when local environmental groups filed a complaint against the environmental ministry challenging the licence it granted to Tesla's water supplier., An astonishing story of deadly bacteria, government tests, and a shady protest group...                                                                                                                           , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                            , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/22/health/omicron-covid-variant-wellness/index.html </td>
   <td style="text-align:left;"> 2022-03-22 23:25:06 </td>
   <td style="text-align:left;"> Could the new BA.2 variant cause another surge? A medical expert explains - CNN </td>
   <td style="text-align:left;"> (CNN)A subvariant of Omicron, BA.2, is leading to a new wave of Covid-19 infections across Europe. Cases in the United Kingdom, Germany, the Netherlands and other countries are going up, driven by this very contagious coronavirus strain.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The proportion of Covid-19 cases due to BA.2 is rising in the United States, too. The US Centers for Disease Control and Prevention now estimates that 35% of new coronavirus cases are due to this subvariant. At the same time, restrictions are being lifted, and not a single US state requires mask mandates anymore (though masks are still required in some settings, including airports, public transportation, hospitals, nursing homes, and some schools and workplaces).                                                                                                                                                                                                                                                                                                                                                                                                                           , How worried should people be about the BA.2 variant? Will vaccines protect against it? What if someone contracted a previous variant -- could they become reinfected? Is BA.2 milder than previous versions, and if so, should people try to get it? Could BA.2 cause another surge in the US, and is it time for restrictions to be put back into place?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , To help us with these questions, I spoke with CNN Medical Analyst Dr. Leana Wen, an emergency physician and professor of health policy and management at the George Washington University Milken Institute School of Public Health. She is also author of "Lifelines: A Doctor's Journey in the Fight for Public Health."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , CNN: What do we know about BA.2, and how worried should we be about it?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Dr. Leana Wen: With any new variant or subvariant, we need to ask three questions: Is it more contagious? Does it cause more severe disease? And does it evade the protection of our vaccines?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , BA.2 is related to BA.1, which is the original Omicron subvariant that led to the huge surge in cases over the winter here in the United States and across Europe. BA.1 swept through communities because of how contagious it is. BA.2 appears to be even more contagious than BA.1. The UK Health Security Agency estimates that BA.2 is growing 80% faster than BA.1. Here in the US as well, BA.2 appears to be on its way to overtaking BA.1 to become the dominant variant.                                                                                                                                                                                                                                                                                                                                                                                                                             , The good news is that BA.2 does not seem to cause more severe illness than BA.1. Researchers from the UK and Denmark have found BA.2 causes a level of hospitalization that's comparable to that of BA.1, which is less likely to result in severe illness than the previously dominant Delta variant.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , In addition, the vaccines we have are still effective. While vaccination may not protect as well against infection with BA.1 and BA.2, the effectiveness in that regard is partially restored with a booster dose, and the vaccines continue to provide very good protection against severe illness due to both Omicron subvariants.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , What all of this says to me is that public health experts should follow the rise of BA.2 in the US closely, but that most people should not be worried. It's likely that the US will see an increase in Covid-19 cases in the coming weeks, as this is the pattern we've seen before -- that we lag behind the UK and Europe by a few weeks, so the increase they are seeing could be mirrored here. However, most people who are vaccinated, and in particular if they are boosted, are unlikely to become severely ill due to BA.2. Our government officials should prepare for what could be coming and increase the availability of tests and treatments, and continue to urge people to get vaccines and boosters. But I don't think this is something that the general public should be overly concerned about at this time.                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , CNN: Does that mean people can proceed with spring break and other travel plans, or do they need to postpone them?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Wen: I don't think travel plans need to be put on hold. To be sure, there is uncertainty, as some places might have low rates of Covid-19 now but may have increased rates when you travel. However, that may be the case for the foreseeable future. Very few activities that we do have no risk. Traveling certainly entails risk, but you can reduce that risk by making sure you are vaccinated and boosted. Wearing a mask in crowded indoor settings further reduces risk. In the United States, follow the CDC guidance and make sure to wear a mask in areas that have high Covid-19 community levels. If you are planning international travel, know the rules, including whether you have to have proof of vaccination or a recent negative test.                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , CNN: Are there certain people who should be concerned about BA.2?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Wen: Individuals who are very vulnerable to severe illness from Covid-19 despite vaccination should be concerned about the coronavirus in general, as they are about other infectious pathogens. For most people, Covid-19 infection will result in mild illness, but in some people --those who are moderately or severely immunocompromised or with multiple underlying medical conditions -- the infection still could result in hospitalization. BA.2 may not cause more severe disease than BA.1, but because of how contagious it is, people who are particularly vulnerable will want to keep taking additional precautions. That includes wearing a high-quality mask (N95, KN95 or KF94) in all indoor public settings, avoiding large crowds and traveling for essential reasons only. Before getting together with other people, they may wish to request that the others are tested for Covid-19. , CNN: If someone previously had Omicron, are they protected against BA.2?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Wen: The World Health Organization has said that infection with BA.1 continues to provide protection against BA.2. Reinfection with BA.2 after having BA.1 is rare.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Most people don't find out what variant they had, though this could be estimated based on when they got infected. If someone found out that they had Covid-19 during the initial Omicron surge, it's likely they had BA.1. In that case, especially if they are vaccinated too, they are very unlikely to contract BA.2.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , However, if someone was previously infected during another wave, for example, while Delta was predominant, they could still contract BA.1 or BA.2. This is another reason why vaccination is so crucial, because the combination of vaccination and prior infection provides more consistent and more durable protection than prior infection alone.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , CNN: Omicron is a milder variant than previous variants. In that case, should people try to contract BA.2 just to get it over with?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Wen: In general, it is not a good strategy to try to contract an illness. Omicron is less likely to result in severe disease compared with Delta, but it still causes severe illness in some people. In addition, even mild illness may be very unpleasant and result in feeling unwell, missing work and being unable to care for family members for days. You could also infect other people, and there is the possibility of long-haul symptoms as well. A better strategy is to make sure to get the vaccine and booster so that if you were to encounter BA.2 (or another variant of Covid-19), you are as well protected as possible.                                                                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , CNN: Could BA.2 cause another surge in the US, and if so, should restrictions come back now?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Wen: BA.2 could certainly lead to another uptick in Covid-19 infections in the US. There are already some signs that the sharp decline in new cases is leveling out, and if the US follows Europe, as it has before, a rise in cases could be weeks away.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , That said, I don't think it means we need to reinstate restrictions. The goal of vaccination is to decouple infections from hospitalizations and severe illness. If there is a surge in infections but hospitalizations don't rise to the point that our health care system becomes overwhelmed, then I think government-imposed mandates are not warranted. Here, the new CDC guidelines are very helpful, as they take into account severe illness -- severe enough to cause hospitalizations -- as the metric for masking, not just any infection.                                                                                                                                                                                                                                                                                                                                                         , Of course, just because the government isn't requiring masks doesn't mean that individuals shouldn't mask or take other precautions. At this point in the pandemic, people should make decisions based on their own medical circumstances and tolerance of risk.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/stock-market </td>
   <td style="text-align:left;"> 2022-03-22 23:24:00 </td>
   <td style="text-align:left;"> Stocks in Mexico Hit All-time High </td>
   <td style="text-align:left;"> Mexico's main stock index rose for the fifth session on Tuesday, with the S&amp;P/BMV IPC breaking above the 55,800 level for the first time ever after preliminary data showed the country's economy likely expanded by 0.3% in February compared with the previous month. Meanwhile, investors continue to assess the impact of Russia's invasion of Ukraine particularly on growth and inflation, as well as hawkish comments from Fed Chair Powell. Main gainers were Bolsa Mexicana de Valores, Inbursa, Alfa, Grupo Aeroportuario del Pacifico and Grupo Lala, all up more than 2.5%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/mcdonalds-bringing-back-szechuan-sauce/story.aspx?guid={679F8DFD-EE7E-4064-BC50-DFA88AF453D5}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-22 23:02:35 </td>
   <td style="text-align:left;"> McDonald's bringing back Szechuan sauce on its app for a limited time starting March 31 - MarketWatch </td>
   <td style="text-align:left;"> McDonald's Corp. 
        MCD,
        +1.19%
       says it will bring its Szechuan dipping sauce back on March 31, but only for a few days and only on the fast-food giant's app. Over the past 24 years, the sauce has only been available three times. The sauce can be paired with an order of Chicken McNuggets or purchased on its own. Customers can only purchase five packets at a time. The sauce mixes sweet and savory with the flavors of garlic, ginger, soy and vinegar. McDonald's stock has slumped 11.3% for the year to date, and is up 5.7% over the last year., Highlights include new seasons of 'The Flight Attendant,' 'Barry' and 'Made for Love,' and new crime series like 'Tokyo Vice' and 'We Own This City'                                                                                                                                                                                                                                                                                                                                                                                                                                   , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-03-22 22:56:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index at 2-Week Low </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index fell 1.7% to 2,546 on Tuesday, its lowest since March 8th, extending losses for a second day, as weakness in the larger capesize segment offset gains in the smaller ones. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes slipped 12% to 2,175; while the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, rose 5.4% to 3,111. Among smaller vessels, the supramax index added 34 points to 2,983 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60832112?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-22 22:55:41 </td>
   <td style="text-align:left;"> UK to fully compensate postmasters who exposed scandal </td>
   <td style="text-align:left;"> Subpostmasters who helped uncover the Post Office IT scandal but missed out on full compensation are to get payouts under a new government scheme.                                                                                                                                                                                                                                                                                                            , The 555 workers won a landmark civil case against the Post Office in 2019, but saw most of their settlements swallowed up by legal fees.                                                                                                                                                                                                                                                                                                                      , They will now get the same level of compensation as other subpostmasters who were wrongly convicted.                                                                                                                                                                                                                                                                                                                                                          , The announcement comes as a public inquiry into the scandal continues.                                                                                                                                                                                                                                                                                                                                                                                        , Between 2000 and 2014, hundreds of subpostmasters and mistresses were wrongly accused of theft, fraud and false accounting due to faults in the Horizon computer software being used at branches across the UK.                                                                                                                                                                                                                                               , In 2019, a group of 555 subpostmasters and mistresses successfully challenged the Post Office over the accusations in the High Court.                                                                                                                                                                                                                                                                                                                         , That case set a legal precedent and paved the way for a series of cases in which 72 people had criminal convictions overturned.                                                                                                                                                                                                                                                                                                                               , The Post Office opened a historic shortfall scheme to compensate more than 700 wrongfully convicted former branch managers who had personally covered shortfalls in branch accounts caused by the Horizon software.                                                                                                                                                                                                                                           , But the 555 people who won the High Court case could not participate in the scheme, and despite winning nearly £43m in compensation in 2019, the group's funds were swallowed up due to a "no win, no fee" agreement with Therium, the company which funded the litigation.                                                                                                                                                                                   , The group only got a "small fraction" of the settlement equating to around £20,000 each, the Treasury said.                                                                                                                                                                                                                                                                                                                                                   , Therium has agreed to waive its rights to any claim on the new pot of compensation.                                                                                                                                                                                                                                                                                                                                                                           , Business minister Paul Scully told the BBC's Today programme that the compensation paid to the 555 people would be "absolutely parallel" to the other Post Office workers who had been compensated through the historic shortfall scheme.                                                                                                                                                                                                                     , He said the group were "pioneers" and had "broken open" the scandal.                                                                                                                                                                                                                                                                                                                                                                                          , "I want to make sure they get that full compensation," he said. "It is a massive scandal and it's something I am absolutely determined to put right."                                                                                                                                                                                                                                                                                                         , Asked if the families of 32 out of the 555 people who have since died would be able to receive the compensation, Mr Scully said he would look into it.                                                                                                                                                                                                                                                                                                        , This video can not be played                                                                                                                                                                                                                                                                                                                                                                                                                                  , Speaking in the House of Commons on Thursday, Mr Scully said he envisaged the compensation scheme as running alongside the historic shortfall scheme "on the basis of losses, and looking at ongoing losses as well".                                                                                                                                                                                                                                         , "I'd love to say I've got a blank cheque from the Treasury, but that's clearly not going to happen from this place - but the Treasury know that we need to sort it out.                                                                                                                                                                                                                                                                                       , "I want to make sure that the scheme has the confidence of [subpostmasters]," he added.                                                                                                                                                                                                                                                                                                                                                                       , Following the government's announcement, the Post Office said it welcomed the move.                                                                                                                                                                                                                                                                                                                                                                           , "Since it came to light through media reports that around £46m of the compensation provided to group litigation claimants was directed to the funders of their case, we have continually urged the government to address this unfairness," a statement said.                                                                                                                                                                                                  , It's hard to overstate the importance of the legal precedent set by the victory of 555 subpostmasters two and a half years ago. That was the moment that evidence came into the public domain about the flaws with the Post Office's Horizon system, and back-end access to the software.                                                                                                                                                                     , The judge did not hold back in his opinion of the Post Office, saying the system was not remotely robust, but that getting that information out of the Post Office had taken subpostmasters years, and many tens of millions of pounds in costs.                                                                                                                                                                                                              , It was the moment where the tables turned against a crown institution which had been wrongly convicting, bankrupting, and sacking its own employees for decades.                                                                                                                                                                                                                                                                                              , Their David v. Goliath legal battle has proved the ammunition needed for 706 branch managers who were convicted or sent to prison have been able to get those convictions quashed. It also forced the Post Office to agree to refund 2,500 others for huge financial losses they suffered as result, although most still haven't received a penny of that money.                                                                                              , The 555 original legal trailblazers stood and cheered as their legal victory snowballed, but were left with very little in compensation themselves. This new scheme is promising to set that right. Full details of how to claim have not yet been published, and there's still a lot of nervousness from those who had to fight the Post Office and the government at every turn, but this is the clearest statement yet that a fairer payment is on the way., The new compensation scheme comes as High Court judge Sir Wyn Williams leads a public inquiry into the Post Office scandal, which has heard testimonies from Post Office staff, some of which were wrongly accused or convicted of crimes they didn't commit.                                                                                                                                                                                                 , A total of 72 have had their names cleared so far.                                                                                                                                                                                                                                                                                                                                                                                                            , The inquiry - which is expected to run for the rest of this year - is examining whether the Post Office knew about faults in the IT system, Horizon, which was developed by Japanese company Fujitsu.                                                                                                                                                                                                                                                         , It will also ask how and why they were left to shoulder the blame.                                                                                                                                                                                                                                                                                                                                                                                            , The Post Office has previously said it is "sincerely sorry for the impact of the Horizon scandal on the lives of victims and their families and we are in no doubt about the human cost".                                                                                                                                                                                                                                                                     , "In addressing the past, our first priority is that full, fair and final compensation is provided and we are making good progress," it added.                                                                                                                                                                                                                                                                                                                 , The Department for Business has previously said it is "eager to see all Horizon-related issues resolved fairly and quickly, including for the 555, who played a crucial role in bringing this scandal to light".                                                                                                                                                                                                                                              , An astonishing story of deadly bacteria, government tests, and a shady protest group...                                                                                                                                                                                                                                                                                                                                                                       , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                                                                                                                                                                                                        , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                                                                                                                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/canola </td>
   <td style="text-align:left;"> 2022-03-22 22:53:00 </td>
   <td style="text-align:left;"> Canola Hits All-Time High </td>
   <td style="text-align:left;"> Canola futures skyrocketed to a new record peak near the CAD 1,150 region, now up more than 10% since the beginning of 2022, supported by supply disruptions due to extreme spring rains and flooding in NSW and northern NSW that affected production and quality. On top of that, the war in Ukraine sent shockwaves through global agricultural markets, with higher production costs putting further upside pressure on prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lithium </td>
   <td style="text-align:left;"> 2022-03-22 22:52:22 </td>
   <td style="text-align:left;"> Lithium Carbonate Prices Extend Rise </td>
   <td style="text-align:left;"> Lithium carbonate prices in China were at 497,500 yuan/tonne in late March, marking an 80% gain so far in 2022 amid soaring global demand and supply scarcity. Surging energy prices due to Russia’s invasion of Ukraine strengthened the appeal to transition away from fossil fuels, adding to the booming demand of electric vehicles. After rising 157% to 3.2 million units in 2021, electric vehicle sales in China are expected to cross 5 million in 2022. Also, Deloitte forecasts a 29% compound annual growth in electric vehicle sales, totalling 32% of new car sales by 2030. At the same time, reports from Mineral Benchmark Intelligence indicate that Chinese lithium inventories remain low. The difficulty for miners to find new sources or develop new technologies to source lithium from brines make producers unable to match higher demand. Lithium’s supply deficit is estimated to expand to 26,000 in 2022 and 300,000 by 2030. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/disney-employees-are-walking-out-to-demand-more-lgbtq-support </td>
   <td style="text-align:left;"> 2022-03-22 22:32:14 </td>
   <td style="text-align:left;"> Disney employees are walking out to demand more LGBTQ support </td>
   <td style="text-align:left;"> CFRA Research senior analyst Tuna Amobi and Slated co-founder Stephan Paternot discuss Disney's streaming platform on 'The Claman Countdown                                                                                                                                                                                                                                                                                                                 , A group of Disney employees staged a walkout on Tuesday at locations across the country, demanding the company do more to protect LGBTQ people and protesting that CEO Bob Chapek waited too long to condemn a bill passed by the Florida legislature.                                                                                                                                                                                                      , Disney CEO Bob Chapek talks during the opening ceremony of the Invictus Games at ESPN Wide World of Sports on May 8, 2016, in Orlando, Florida. (Chris Jackson/Getty Images for Invictus / Getty Images)                                                                                                                                                                                                                                                    , The legislation that sparked the outcry is the Parents Rights in Education bill, which has been dubbed the "Don't Say Gay" bill by critics. If signed by Republican Gov. Ron DeSantis, it would prohibit Florida educators from teaching sexual orientation or gender identity in kindergarten through third grade.                                                                                                                                         , Disney has been under fire from both sides of the political aisle over its response to the bill. It has also come under fire for its operations in China. The National Legal and Policy Center, an ethics watchdog and shareholder, accused the media giant of "complicity in China genocide" at the recent shareholders meeting.                                                                                                                           , DISNEY ACCUSED BY ACTIVIST SHAREHOLDER OF ‘COMPLICITY IN CHINA GENOCIDE’                                                                                                                                                                                                                                                                                                                                                                                    , Initially, the company did not take a public position on the bill, drawing the ire of those opposed to it. Chapek then spoke out against it at a shareholders meeting following its passage, announced a pause on political donations in Florida, and vowed Disney would contribute millions of dollars more to LGBTQ causes. The CEO also said he would meet with DeSantis to express his and Disney's opposition to the legislation.                      , Florida Governor, Ron DeSantis speaks at a press conference at the Eau Gallie High School aviation hangar on March 22, 2021. (Paul Hennessy/SOPA Images/LightRocket via Getty Images / Getty Images)                                                                                                                                                                                                                                                        , DeSantis fired back in a speech the next day, telling a group of supporters, "You have companies, like Disney, that are going to … criticize parents' rights, they're going to criticize the fact that we don't want trangenderism in kindergarten, in first-grade classrooms."                                                                                                                                                                             , The governor went on to slam Disney for refusing to condemn human rights abuses in China, where the entertainment giant does substantial business, before adding, "in Florida, our policies got to be based on the best interest of Florida citizens, not on the musings of woke corporations."                                                                                                                                                             , DISNEY SHANGHAI TEMPORARILY CLOSES AS CHINA BATTLES ANOTHER COVID SURGE                                                                                                                                                                                                                                                                                                                                                                                     , Now, organizers of Tuesday's protest say Disney's pause on donations to Florida politicians is not enough, and that the company has to do more for the LGBTQ community.                                                                                                                                                                                                                                                                                     , The group published a list of demands for the company, ordering Disney to cease all campaign donations to politicians that voted for the "Don't Say Gay" bill indefinitely, end all investment in Florida until the bill is repealed, make "substantial contributions" to human rights advocacy groups, and expand the company's LGBTQ content.                                                                                                             , Disney cast member Nicholas Maldonado protests his company's stance on LGBTQ issues, while participating in an employee walkout at Walt Disney World, Tuesday, March 22, 2022, in Lake Buena Vista, Florida. (AP Photo/Phelan M. Ebenhack)                                                                                                                                                                                                                  , It is unclear how many Disney employees participated in the walkout.                                                                                                                                                                                                                                                                                                                                                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                 , Disney did not immediately respond to FOX Business' request for comment, but Disney+ issued a statement Tuesday morning saying, in part, that the streaming service "stands by our LGBTQIA+ employees, colleagues, families, storytellers, and fans, and we strongly denounce all legislation that infringes on the basic human rights of people in the LGBTQIA+ community – especially legislation that targets and harms young people and their families." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-22 22:29:00 </td>
   <td style="text-align:left;"> Brazilian Stocks at Over 6-Month High </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Ibovespa, rose over 1% to around 117,355 on Tuesday, its highest since September 6th 2021, extending gains for the fifth straight session, driven by companies such as Locaweb, Positivo and Méliuz. Meanwhile, investors digested more hawkish comments from US Federal Reserve Chairman Powell and minutes from the latest Brazil's central bank monetary policy meeting signaling another 100 basis points hike at the next meeting in May. Still, caution persists because the ongoing peace talks between Moscow and Kiev are not moving forward. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/richmond-fed-manufacturing-index </td>
   <td style="text-align:left;"> 2022-03-22 22:18:00 </td>
   <td style="text-align:left;"> Manufacturing Activity in 5th District Expands Faster </td>
   <td style="text-align:left;"> The Richmond Fed composite manufacturing index increased to 13 in March of 2022 from 1 in February, pointing to an improvement in Fifth District manufacturing activity. Increases were seen in all components: shipments (9 vs -11), volume of new orders (10 vs -3), and number of employees (23 vs 20). The order backlogs index turned positive again (7 vs -4). The vendor lead time index continued to be high, indicating that most firms were still reporting growing lead times. The index for both finished goods (-15 vs -14) and raw materials inventories (-15 vs -22) remained low, and firms expected that to persist for the foreseeable future. In general, firms continued to report increased hiring and rising wages. The average growth rate of prices paid remained elevated (11.05 vs 12.27) but continued a three-month downward progression. However, average growth in prices received inched up (9.16 vs 8.77). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lumber </td>
   <td style="text-align:left;"> 2022-03-22 22:10:00 </td>
   <td style="text-align:left;"> Lumber Hits 6-Week Low </td>
   <td style="text-align:left;"> Chicago lumber futures tumbled to below $1,100 per thousand board feet, a level not seen in six weeks, as the National Association of Home Builders urged the US to increase domestic production and work with Canada on a new softwood lumber agreement that will eliminate tariffs. Still, demand is expected to stay strong as the large US home builders make their purchases necessary for the looming spring construction season. US housing starts in February were up, reaching highs not seen since mid-2006. However, building permits were down compared to the previous month. Markets have also been facing shortages as Canada, a leading lumber supplier to the US, was hit by fire, flood and infestations of wood-boring beetles last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/money/irs-tax-refund-mid-march-average-size </td>
   <td style="text-align:left;"> 2022-03-22 22:06:23 </td>
   <td style="text-align:left;"> The IRS has delivered 45M tax refunds so far. This is the average amount </td>
   <td style="text-align:left;"> Sponsor Content: Tax advice for recently married couples and new parents filing in 2022                                                                                                                                                                                                                                                                                                                          , With just one month remaining in the 2022 tax season, and the IRS has delivered millions of refunds to taxpayers, a major influx of money to households that many Americans depend on.                                                                                                                                                                                                                           , The tax-collecting agency said last week that it has issued more than 45 million refunds worth a collective $152 billion as of March 11. The average payment so far is worth $3,352 – much larger than last year's average of about $2,800 – though it may change by the April 18 deadline.                                                                                                                      , TAX SEASON BEGINS: WHAT YOU NEED TO KNOW BEFORE FILING                                                                                                                                                                                                                                                                                                                                                           , The latest filing statistics come as the IRS warns of a "challenging" tax season for filers as the agency works through a massive backlog of unprocessed tax returns.                                                                                                                                                                                                                                            , WASHINGTON, DC - JUNE 08: Internal Revenue Service (IRS) Commissioner Charles Rettig testifies during a Senate Finance Committee hearing June 8, 2021 on Capitol Hill in Washington, D.C.  (Photo by Tom Williams-Pool/Getty Images / Getty Images)                                                                                                                                                              , There are some steps that taxpayers can take in order to get their money back faster. Experts have urged taxpayers to file their tax returns as soon as possible, noting that individuals do not need previous returns in order to submit their 2021 returns. Americans are encouraged to file electronically with direct deposit in order to avoid potential delays and receive their return within 21 days.    , Taxpayers will also have to reflect the monthly child tax credit payments and the stimulus checks they received in 2021 on their returns, further complicating matters and increasing the likelihood of errors and delays in processing returns.                                                                                                                                                                 , "We urge extra attention to those who received an economic impact payment or an advance child tax credit last year," IRS Commissioner Chuck Rettig said in a statement. "People should make sure they report the correct amount on their tax return to avoid delays."                                                                                                                                            , Families that received monthly installments of the boosted child tax credit last year will receive a letter – called Letter 6419 – from the IRS informing them of the total amount of the advanced payment they received and the number of qualifying children used to calculate the payments.                                                                                                                   , Income tax numbers at the accountants office                                                                                                                                                                                                                                                                                                                                                                     , Because at least half of the enhanced credit will be paid out as a lump sum when parents receive their 2021 tax return, recipients should keep the letter and use it to accurately reconcile the credit they already received when filing their taxes this year. The information is pertinent to determining how much more money families receive from the credit when they fill out Schedule 8812 and Form 1040., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                      , If taxpayers file an electronic return with no issues and opt to receive the refund via direct deposit, the IRS anticipates the money will arrive within 21 days. You can start tracking the status of your tax refund within 24 hours of filing using the IRS' Where’s My Refund tool.                                                                                                                          , The tax-filing season will end on April 18 this year for most individuals, rather than the usual deadline of April 15, because that's when Emancipation Day will be observed in Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/finland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-22 22:05:32 </td>
   <td style="text-align:left;"> Finland 10Y Bond Yield Hits 6-year High </td>
   <td style="text-align:left;"> Finland 10 Year Government Bond Yeld increased to a 6-year high of 0.904% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/silver </td>
   <td style="text-align:left;"> 2022-03-22 21:58:18 </td>
   <td style="text-align:left;"> Silver Falls to 1-Week Low </td>
   <td style="text-align:left;"> Silver came under renewed selling pressure on Tuesday, falling to a one-week low of $24.70/oz amid a slightly stronger dollar and soaring US Treasury yields. Market moves came in the aftermath of surprisingly hawkish comments from Fed Chair Jerome Powell during a speech before the National Association for Business Economics. Powell noted that the US central bank could move more aggressively by raising the interest rates by more than 25 basis points at a meeting or meetings to bring inflation, which is now running at 40 years highs, under control. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60837074?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-22 21:54:50 </td>
   <td style="text-align:left;"> Inquiry urged amid fears people of colour pay more for car insurance </td>
   <td style="text-align:left;"> A charity has called on regulators to investigate following concern that people from ethnic minority backgrounds could pay more for car insurance.                                                                                                                                                                                                      , Citizens Advice claims its own investigation found people faced a £280 a year "ethnicity penalty".                                                                                                                                                                                                                                                      , Insurers say ethnicity is never a factor when setting premiums, as such discrimination would be illegal.                                                                                                                                                                                                                                                , But the City regulator said the investigation raised challenging questions for insurers.                                                                                                                                                                                                                                                                , The charity analysed 18,000 car insurance costs reported by people across England and Wales who came to Citizens Advice for debt help last year.                                                                                                                                                                                                        , It concluded that, on average, people from ethnic minority backgrounds paid £250 a year more than white people - regardless of gender, age and income.                                                                                                                                                                                                  , Using a mystery shopping exercise, it also said that in postcodes where more than 50% of the population were from ethnic minority backgrounds, there was a penalty of at least £280 a year.                                                                                                                                                             , The charity claimed that local risk factors such as the crime rate, deprivation, road traffic accidents and population density could not account for the price differences.                                                                                                                                                                             , The Association of British Insurers (ABI) said insurers never use ethnicity as a factor when setting prices, to comply with the law.                                                                                                                                                                                                                    , James Dalton, its director of general insurance policy, said: "All other rating factors being the same, two people of different ethnicities who live in the same postcode will pay the same premium for their car insurance.                                                                                                                            , "Insurance is priced on individual risk levels and there are many different risk-related factors that are used to calculate the price of a car insurance policy which, as Citizens Advice recognise, should not be looked at in isolation but ethnicity is not one of them. However, we recognise this report raises an important public policy debate.", Citizens Advice said it was concerned that alternative data could be used as a proxy for the ethnicity of customers.                                                                                                                                                                                                                                    , Data is processed through complex algorithms which were hard to examine, it said.                                                                                                                                                                                                                                                                       , It called on the City watchdog, the Financial Conduct Authority (FCA), to investigate.                                                                                                                                                                                                                                                                  , "It is time for the FCA to lift the bonnet on insurance firms' pricing decisions and ensure no one is paying more because of protected characteristics like race," said its chief executive, Clare Moriarty.                                                                                                                                            , "The use of algorithms has real-world implications for real people. They must be applied with caution, under the careful scrutiny of regulators."                                                                                                                                                                                                       , An FCA spokesman said: "We welcome Citizens Advice's work on this important issue. Their analysis highlights a risk of discrimination based on race and raises some potentially challenging questions for insurers.                                                                                                                                     , "Firms must also be able to assure themselves, and us, that any risk factors they include also do not result in discrimination. We will continue to consider any evidence we receive of concerns around pricing."                                                                                                                                       , An astonishing story of deadly bacteria, government tests, and a shady protest group...                                                                                                                                                                                                                                                                 , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                                                                                                  , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                                                                                                                                                             , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-22 21:53:00 </td>
   <td style="text-align:left;"> Japan 10Y Bond Yield Hits 6-Year High </td>
   <td style="text-align:left;"> The yield on the benchmark Japan 10-year JGB hit a six-year high of 0.235% amid a global bond sell-off after hawkish remarks by US Fed Chairman Powell, where he left the door open for a 50 basis point hike. Following these comments, the Bank of Japan Governor Kuroda reiterated his ultra-accommodative stance, warning it was premature to debate tightening due to the impact that the current cost-push inflation could have on growth. Governor Kuroda said that cost-push inflationary pressures could lift headline inflation to target from April, but it would lead to lower price-adjusted wages and hurt corporate profits. Earlier, the BoJ had decided to keep monetary policy ultra-easy, as widely expected, and lagging further behind from its North American counterpart, which delivered an expected 25 bps rate hike. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-22 21:45:00 </td>
   <td style="text-align:left;"> Toronto Stocks Hit Fresh All-Time High </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, traded higher on Tuesday, setting fresh record highs above the 22,000 mark, underpinned by gains in banks and tech stocks, while heavyweight energy stocks hovered around the flatline, as the oil rally faltered. On corporate news, Canadian Pacific Railway, the country’s 2nd largest rail company, agreed to binding arbitration with the workers’ union to help resolve a labor dispute, allowing operations to resume. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-22 21:35:00 </td>
   <td style="text-align:left;"> Wall Street Regains Some Momentum </td>
   <td style="text-align:left;"> The Dow added over 100 points at the opening bell Tuesday, while the S&amp;P 500 and the Nasdaq rose 0.4% and 0.3%, respectively, as investors reassessed the outlook for tightening monetary policy following surprisingly hawkish comments from Fed Chair Powell while watching the situation in Eastern Europe. Powell noted that the US central bank could move more aggressively by raising the interest rates by more than 25 basis points at a meeting or meetings to bring inflation, which is now running at 40 years highs, under control. Meanwhile, Russia and Ukraine failed to make progress, and Ukraine refused to surrender the port city of Mariupol to Russian forces. On the corporate side, Nike shares jumped over 6% as the world's biggest sportswear maker beat quarterly estimates for profit and revenue. Procter &amp; Gamble added nearly 1% after Truist upgraded the stock to a buy rating. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hungary/interest-rate </td>
   <td style="text-align:left;"> 2022-03-22 21:24:00 </td>
   <td style="text-align:left;"> Hungary Hikes Key Interest Rate More than Expected </td>
   <td style="text-align:left;"> The National Bank of Hungary raised its benchmark base rate by 100bps to 4.4 percent on March 22nd, while signaling that rate hikes in the future will continue in larger steps than previously thought as inflationary pressures pose a threat to the economy. The figure stands as the highest since May of 2013 and above market expectations of a 75bps increase. It was the tenth consecutive rate hike, as the central bank attempts to curb strong inflationary pressure and a weakening forint after the currency's selloff due to the war in Ukraine. Consumer inflation rose to the 14-year high of 8.3 percent in February, driven by higher prices for energy and agricultural goods and well above the central bank’s target of 2%-4%. Also, the forint fell 4% compared to the dollar this year after touching an all-time low in the beginning of March. Meanwhile, the MNB expects the GDP to grow by 2.5-4.5% in 2022, down from earlier estimates of 5% due to economic effects of the war in Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-03-22 21:12:00 </td>
   <td style="text-align:left;"> US Natural Gas Hits 16-Week High </td>
   <td style="text-align:left;"> US natural gas futures hit $5.19 per million British thermal units, the highest since November 29th, on strong overseas demand as Europe struggles to replace energy imports from Russia. European gas prices remain seven times over US futures and crude oil has been trading above $110 per barrel putting additional pressure on the energy market. Meanwhile, the number of US LNG tankers sailing to Europe reached a record 164 in January and February and the US is already producing LNG near full capacity. Adding to woes, in the US inventories shrank more than expected in the week ending March 11th, but expectations of the incoming spring weather are set to limit the bullish momentum. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60825983?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-22 21:00:04 </td>
   <td style="text-align:left;"> Alisher Usmanov: Oligarch says he ditched mansions before sanctions </td>
   <td style="text-align:left;"> A Russian billionaire sanctioned by the UK says he no longer owns many former properties, potentially putting them beyond the reach of the law.                                                                                                                                                                                                                                                                     , Ex-Arsenal shareholder Alisher Usmanov's £82m London home and Surrey mansion were put into trusts linked to the oligarch.                                                                                                                                                                                                                                                                                           , This raises questions over the effectiveness of sanctions imposed since the invasion of Ukraine began.                                                                                                                                                                                                                                                                                                              , The UK government says Mr Usmanov "cannot access his assets".                                                                                                                                                                                                                                                                                                                                                       , On 3 March, seven days after Russia’s invasion of Ukraine, Alisher Usmanov was added to the list of sanctioned Russian businessmen.                                                                                                                                                                                                                                                                                 , His assets were frozen, he was banned from visiting the UK, and British citizens and businesses were banned from dealing with him.                                                                                                                                                                                                                                                                                  , Foreign Secretary Liz Truss said: “We will hit oligarchs and individuals closely associated with the Putin regime and his barbarous war.”                                                                                                                                                                                                                                                                           , The government said sanctions would cut him off from “significant UK interests including mansions worth tens of millions”.                                                                                                                                                                                                                                                                                          , But this is now in doubt because Mr Usmanov’s spokesman says he is no longer the legal owner of many of those assets.                                                                                                                                                                                                                                                                                               , Born in Uzbekistan in the Soviet Union, Alisher Usmanov, 68, owns USM Holdings, a huge conglomerate involved in mining and telecoms, including Russia's second biggest mobile network MegaFon.                                                                                                                                                                                                                      , His wealth has been estimated at $18.4bn (£14bn), including "Beechwood House in Highgate… and the 16th Century Sutton Place estate in Surrey”, the UK government said.                                                                                                                                                                                                                                              , BBC research estimates that Beechwood House could now be worth about £82m.                                                                                                                                                                                                                                                                                                                                          , But a spokesman for Mr Usmanov said that most of the billionaire’s UK property, as well as his yacht, had already been “transferred into irrevocable trusts”.                                                                                                                                                                                                                                                       , Those are trusts which cannot usually be amended, modified, or revoked after they’re created.                                                                                                                                                                                                                                                                                                                       , When the assets were transferred, Mr Usmanov no longer owned them, his spokesman said. “Nor was he able to manage them or deal with their sale, but could only use them on a rental basis.”                                                                                                                                                                                                                         , “Mr Usmanov withdrew from the beneficiaries of the trusts, donating his beneficial rights to his family," he said.                                                                                                                                                                                                                                                                                                  , The spokesman was answering questions about Mr Usmanov’s wealth put to him as part of an investigation into the assets of 35 oligarchs close to Putin.                                                                                                                                                                                                                                                              , The Russian Asset Tracker is a global partnership involving 27 media organisations including the Guardian, the Organized Crime and Corruption Reporting Project (OCCRP) and BBC Panorama.                                                                                                                                                                                                                           , The project identified $3.4bn (£2.6bn) worth of specific assets which it says belong to Mr Usmanov.                                                                                                                                                                                                                                                                                                                 , But if Mr Usmanov is not the beneficial owner of much of this property, it could be beyond the reach of UK sanctions. And the same could be true for other oligarchs.                                                                                                                                                                                                                                               , According to lawyer and sanctions expert Michael O’Kane, “it’s very common for high net worth individuals… to structure both their commercial enterprises and their personal wealth in a way that gives them maximum tax efficiency. Quite often that results in structures whereby they release ownership and control in return for more tax efficiency.”                                                          , “In order for an entity to be designated under sanctions it needs to be owned or controlled by a sanctioned person. The more opaque and complex the structures of ownership the more difficult that is to establish.”                                                                                                                                                                                               , Tracing the ownership of the two houses targeted by the UK government is extremely difficult. They have been held through a complex web of trusts and companies registered in places like the British Virgin Islands, which have until recently not required the ultimate owner to be disclosed. This illustrates the difficulty investigators will have in working out which assets should be subject to sanctions., Despite offshore secrecy the BBC has been able to identify two trusts that have owned the properties, and the involvement of one of Mr Usmanov’s closest business associates.                                                                                                                                                                                                                                       , They involve a long-time associate of Mr Usmanov, Farhad Moshiri, the owner of Everton football club, who is not subject to sanctions. He’s a shareholder in Mr Usmanov’s company USM, which sponsored Everton until the club terminated the relationship in the wake of the Ukraine invasion.                                                                                                                      , Leaked documents obtained by the International Consortium of Investigative Journalists and other corporate records show Mr Moshiri was the shareholder of a company in the British Virgin Islands called Coney Holdings Limited.                                                                                                                                                                                    , Until 2014 it owned the shares of the corporate trustees of the Sutton Place Property Unit Trust, which owns the Surrey Mansion, drawing a direct link between Mr Moshiri and the house.                                                                                                                                                                                                                            , After Sutton Place Property Unit Trust was set up in 2005, Mr Usmanov was given a £6m loan facility secured against the trust.                                                                                                                                                                                                                                                                                      , Mr Usmanov was also the beneficiary of the Pauillac Trust, the owner of Hanley Limited, the Isle of Man company that owns Beechwood, the other property targeted by the government.                                                                                                                                                                                                                                 , Once again, Mr Moshiri was involved, this time as a director of Pauillac Properties Limited, a company owned by the trust, that held shares in Hanley Limited.                                                                                                                                                                                                                                                      , Mr Usmanov declined to respond to questions about his relationship with the two trusts, or whether he had ceased to have a beneficial interest in them. While the evidence confirms he was once involved, exactly who stands behind the two trusts now, and therefore owns the properties, is a mystery.                                                                                                            , A spokesman for Mr Moshiri told the BBC that he “ceased to be a director of Pauillac in 2016” and that Mr Moshiri “has never been nor is he now involved in the management and/or control of the Sutton Place Property Unit Trust”.                                                                                                                                                                                 , In relation to USM, Mr Moshiri's spokesman said he had sold 50% of his stake in the company but is prevented from selling the rest by the Russian government. He has resigned from the board.                                                                                                                                                                                                                       , Mr Moshiri owns another property identified by our investigation.                                                                                                                                                                                                                                                                                                                                                   , Mr Usmanov bought a luxury property in north London for £15.8m in 2011.                                                                                                                                                                                                                                                                                                                                             , In 2014 Russia invaded Crimea. In March that year Western sanctions targeting those closest to President Putin were imposed, and calls were made for Mr Usmanov’s UK assets to be frozen.                                                                                                                                                                                                                           , A month later shares in the company that owned the property, Oakhill Avenue Limited, were transferred to a company owned by Mr Moshiri, for what his spokesman said was "north of £18m."                                                                                                                                                                                                                            , He told the BBC Oakhill Avenue "is 100% owned by Mr Moshiri and has been since 2014 when Mr Moshiri acquired the house."                                                                                                                                                                                                                                                                                            , He said “Neither Mr Usmanov, nor any entities related to him, have any current connection to the house or indeed the company that owns the house.”                                                                                                                                                                                                                                                                  , But that’s not the only property Mr Moshiri obtained from Mr Usmanov.                                                                                                                                                                                                                                                                                                                                               , In 2004 Mr Usmanov had bought another property in north London for £2 million.                                                                                                                                                                                                                                                                                                                                      , Five years later the property, on Tercelet Terrace in Hampstead, was transferred to Mr Moshiri “not for money”.                                                                                                                                                                                                                                                                                                     , In June 2010, it was transferred, again “not for money”, this time to Mr Moshiri’s sister.                                                                                                                                                                                                                                                                                                                          , It’s not the first time Mr Moshiri has faced questions over his complex financial relationship with Mr Usmanov, such as his investments in Arsenal and Everton FC.                                                                                                                                                                                                                                                  , Asked why Mr Usmanov had handed the property to Mr Moshiri “not for money” Mr Moshiri’s spokesman declined to comment.                                                                                                                                                                                                                                                                                              , The use of offshore entities makes it hard for governments to build a clear picture of what someone they have sanctioned actually owns.                                                                                                                                                                                                                                                                             , “Britain’s offshore financial centres, such as the British Virgin Islands, have long been a destination of choice for Kremlin cronies and kleptocrats,” says Steve Goodrich, Head of Research and Investigations at Transparency International UK (TIUK).                                                                                                                                                           , “Complex networks of secretive shell companies in these jurisdictions means the UK government is attempting to enforce these sanctions with one arm tied behind its back.“                                                                                                                                                                                                                                          , TIUK says the UK government should work with the Overseas Territories and Crown Dependencies to increase the pace of their own transparency reforms.                                                                                                                                                                                                                                                                ,  A spokesman for Mr Usmanov said that “to characterise the source of his money as ‘non-transparent’ is inherently incorrect and damages Mr Usmanov’s reputation as an honest entrepreneur and philanthropist.”                                                                                                                                                                                                      , “The entirety of Mr Usmanov’s capital was built through successful, sometimes risky investments, as well as through the effective management of his assets.”                                                                                                                                                                                                                                                        , The government says its sanctions are having an impact with $250bn (£189bn) wiped off the Russian stock market.                                                                                                                                                                                                                                                                                                     , “The sanctions against Alisher Usmanov were enacted with immediate effect” said a spokesperson for the Foreign Office. “It is now illegal for any person or company in the UK to do business with him.”                                                                                                                                                                                                             , Additional reporting: Ben King and Will Dahlgreen                                                                                                                                                                                                                                                                                                                                                                   , An astonishing story of deadly bacteria, government tests, and a shady protest group...                                                                                                                                                                                                                                                                                                                             , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                                                                                                                                                              , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                                                                                                                                                                                                                         , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2022-03-22 20:49:00 </td>
   <td style="text-align:left;"> Dutch TTF Futures Rebound </td>
   <td style="text-align:left;"> EU front-month natural gas futures firmed to €101.5 per megawatt-hour, recovering slightly from an over three-week low of €94.95 hit earlier in the session amid reports that Norway’s giant Troll natural gas field suffered an unplanned outage. The network operator Gassco said the duration of the shutdown, which was caused by a compressor failure, was unclear. Earlier, futures were subdued by forecasts pointing to warmer weather and news that Germany was making progress in its energy diversification goal, securing long-term LNG deals with Qatar and discussing a hydrogen pipeline with Norway. Meanwhile, Gazprom said it has continued gas supplies to Europe via Ukraine in line with requests from European consumers, calming concerns over Russian supplies. Still, upside risks limited the downfall, as EU countries mull joining the US in banning imports of Russian crude, although Russian oil purchases account for roughly 30% of total EU crude imports, compared to just 3% in the US. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/currency </td>
   <td style="text-align:left;"> 2022-03-22 20:45:00 </td>
   <td style="text-align:left;"> Aussie Hits 19-Week High </td>
   <td style="text-align:left;"> The Australian dollar hit a near five-month high of $0.7443 before settling around $0.744 on Tuesday, as investors weighed chances of the Reserve Bank of Australia catching up to the pace of the Federal Reserve tightening cycle. Earlier hawkish remarks by Fed Chair Jerome Powell had pressured the Aussie, as Powell hinted at bigger US rate hikes to curb high inflation. Meanwhile, investors now see the Reserve Bank of Australia raising interest rates up to 1.5% this year, compared with 1.25% in earlier projections. The first hike should come as early as June, as the central bank said it was open to tightening monetary policy if the economy continued to surprise with its strength. The case for a rate hike strengthened after upbeat labor market data for February showed Australia’s jobless rate declining to a 14-year low of 4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/uk-60820705?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-22 20:42:18 </td>
   <td style="text-align:left;"> Cost of living: 'It feels like I'm being priced out of existence' </td>
   <td style="text-align:left;"> Sitting in her specially adapted bedroom, 15-year-old Ruby Walsh breathes slowly through a nebuliser, which covers her nose and mouth.                                                                                                                                                                   , The teenager, who is deaf and blind, has cerebral palsy, and this is just one of the pieces of medical equipment needed to keep her alive.                                                                                                                                                               , But her need for a nebuliser, along with a ventilator and an oxygen concentrator, is pushing up her family's energy bills at a time when money is already tight.                                                                                                                                         , The cost of living squeeze means the family, who live in Basildon, Essex, have already seen their energy bills rise from £175 to £225 a month. They are reimbursed for the oxygen concentrator, but everything else comes out of the household budget.                                                   , Energy bills are set to rise even further after the energy cap rises on 1 April.                                                                                                                                                                                                                         , Ruby is terminally ill and her mum, Charlotte Huzzey, wants to ensure they can still enjoy time together.                                                                                                                                                                                                , "She shouldn't be unable to go out because we're having to pay for a machine to be on," Charlotte says. "That's not something a 15-year-old girl that's probably not going to be here for too much longer should be dealing with.                                                                        , "We just want a simple life, so that we can enjoy Ruby and she can enjoy the outside world."                                                                                                                                                                                                             , In 2019 a survey conducted by the charity Scope suggested one in three disabled people found their condition had a significant impact on their energy bills, contributing towards an overall £583 in extra costs each month.                                                                             , That was before typical energy prices rose in October 2021 by 12%, with a further 54% increase set for next month. There is no targeted support to help people with disabilities and long-term health conditions cope with higher energy needs.                                                          , The government says financial support is available to disabled people and their carers. It is urging people to check whether they are receiving all of the benefits they are entitled to, alongside wider support such as help with transport, broadband or prescription costs.                          , Dialysis patient Phoenix Halliwell says he feels like he is being "priced out of existence".                                                                                                                                                                                                             , The 46-year-old father from Coventry, in the West Midlands, uses a kidney dialysis machine for nine hours a night, five nights a week, to help him stay alive.                                                                                                                                           , His family switched off their heating at the end of January to make ends meet. Despite this drastic measure, their energy bills have increased by 50% since July, and are set to rise by a third next month.                                                                                             , Phoenix is reimbursed for about half of his electricity bill, but estimates this will fall to a third if the prices go up again in October.                                                                                                                                                              , He is now considering going in to hospital for dialysis to further cut costs. But a single nine-hour dialysis session at home can work out the same as a week's treatment at the hospital (three separate three-hour sessions), and he fears the move could damage his physical and mental health.       , "We've done everything we can to cut back at home on outgoings and use of energy." he says. "As a disabled person with a long-term condition, it feels like I am being priced out of existence. Everybody's fed up with being cold. Ensuring our daughter is safe and warm and fed is our top priority." , Home dialysis already costs people between £590 and £1,450 per year due to increased water and electricity usage, Kidney Care UK says.                                                                                                                                                                   , The charity says about half of all dialysis patients are financially deprived, and demand for its £300 hardship fund has increased by 47% over the past 12 months.                                                                                                                                       , "We are hearing from increasing numbers of dialysis patients that they are having to choose between dialysing and putting food on the table," says policy director Fiona Loud.                                                                                                                           , "We are expecting a significant increase in requests for hardship support this year. Many patients have raised concerns about how they will be able to cope."                                                                                                                                            , Some people with a disability qualify for Personal Independence Payments (PIP), or its predecessor the Disability Living Allowance.                                                                                                                                                                      , But campaigners argue it is insufficient to cover the soaring energy costs that many disabled people are currently facing.                                                                                                                                                                               , A petition has been launched urging the government to provide a grant to people with long-term health needs so they can afford to run their equipment.                                                                                                                                                   , Dan White, from Disability Rights UK, is calling for energy prices to be capped for disabled people, and planned benefit increases to be doubled to 6% in April.                                                                                                                                         , "People are having to use their benefits, which were put aside to pay for their social care and for their independence, into paying for food and bills, and it is still not enough.                                                                                                                      , "People are turning off power, and parents and carers are turning off essential equipment for their children's health to save money," Mr White added. "This is a humanitarian crisis and it's only going to get worse."                                                                                  , The Government says it is taking "decisive action" to help more than 27 million households with rising energy costs, with a £200 reduction on bills this autumn and a £150 reduction in Council Tax bills.                                                                                               , It says the energy price cap will insulate millions of customers from volatile global gas prices.                                                                                                                                                                                                        , An astonishing story of deadly bacteria, government tests, and a shady protest group...                                                                                                                                                                                                                  , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                                                   , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2022-03-22 20:42:00 </td>
   <td style="text-align:left;"> UK Gas Recoups Early Losses </td>
   <td style="text-align:left;"> UK natural gas prices recouped early losses to trade at 236 pence a therm, still close to three-week lows and roughly 70% below a record high of 800 pence hit on March 7th, as the looming spring weather weakened heating demand prospects. Also, natural gas flows through pipelines in Ukraine continued to meet client orders, according to Gazprom, calming concerns about supply disruptions. In the UK, Gazprom’s British retail unit, which supplies natural gas to a fifth of British businesses, will be temporarily nationalized to save the company from collapse. Meanwhile, cease-fire negotiations seemed to have stalled, as the war approached a stalemate. Earlier, the US Department of Energy issued approvals allowing more LNG exports to countries without free trade agreements, which includes countries in Europe, as the region remained the top importer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60832115?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-22 20:38:12 </td>
   <td style="text-align:left;"> Petrol prices stabilise after weeks at record highs </td>
   <td style="text-align:left;"> Fuel prices have stabilised for the first time this month after Russia's invasion of Ukraine caused a surge.                                                                                                             , Average fuel prices slipped from record highs on Monday, with petrol at nearly £1.67 a litre and diesel at £1.79.                                                                                                        , Crude oil surged to $139 per barrel in the first week of March, then slid back the following week.                                                                                                                       , The RAC said the settling of prices could be an indication that retailers may have "finished" passing on their higher wholesale costs to customers.                                                                      , However, it is unclear if and when the cost of fuel will go down.                                                                                                                                                        , Simon Williams, fuel spokesman for the RAC, said Monday's prices had "steadied with very slight reductions in both petrol and diesel".                                                                                   , UK fuel prices have increased at the fastest rate on record in recent weeks, with petrol rising 13p since the start of the month and diesel increasing by nearly 21p.                                                    , Fuel prices, which were already rising as global economies recovered from the coronavirus pandemic, surged after the war in Ukraine pushed up oil prices.                                                                , Changes in prices at the pump are mainly determined by crude oil prices and the dollar exchange rate, because crude oil is traded in dollars.                                                                            , Russia is one of the world's major oil exporters and it is being targeted by economic and trading sanctions.                                                                                                             , After Brent crude oil - a global benchmark for prices - hit a near 14-year high of $139 a barrel during the early stages of the conflict, prices fell back to around $100, but have since risen again to $115 on Tuesday., The most recent increase was driven by the European Union discussing a ban on the purchase of Russian oil, which countries in the bloc rely heavily on.                                                                  , Some countries, such as the US and Canada, have already banned on Russian oil imports, but the EU has so far stopped short of that action.                                                                               , Meanwhile, the UK government has vowed to phase out imports of Russian oil by the end of the year.                                                                                                                       , The UK only imports about 6% of its crude oil from Russia, but is affected by the global shifts in price.                                                                                                                , Mr Williams said the wholesale price of petrol for retailers currently stands at £1.30 a litre for petrol and £1.48 for diesel.                                                                                          , "With prices this high before retailer margin and 20% VAT are added it's clear we are in a tough place when it comes to being able to afford to drive," he said.                                                         , "This is why it's crucial the chancellor takes decisive and meaningful action in his Spring Statement that helps hard-pressed drivers and businesses."                                                                   , More than 50 Conservative MPs have called for a cut in fuel duty, which is currently 57.95p per litre, and has VAT of 20% applied on top.                                                                                , Several newspapers have also reported that Chancellor Rishi Sunak is considering a temporary cut of as much as 5p per litre, but some opposition MPs have questioned whether this would go far enough.                   , Following Russia's invasion of Ukraine, there were warnings of potential global oil supply problems.                                                                                                                     , The International Energy Agency (IEA) has said high commodity prices and sanctions against Russia were "threatening to create a global oil supply shock".                                                                , It estimated three million barrels per day of Russian oil could be taken out of the global market as a result of international sanctions.                                                                                , The agency warned only Saudi Arabia and the United Arab Emirates have enough spare production capacity to offset the shortfall in Russian output.                                                                        , An astonishing story of deadly bacteria, government tests, and a shady protest group...                                                                                                                                  , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                   , A journey to understand the impact alcohol addiction has on young women in Northern Ireland                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/producer-price-inflation-mom </td>
   <td style="text-align:left;"> 2022-03-22 20:38:00 </td>
   <td style="text-align:left;"> Canada Producer Prices Rise the Most since 1980 </td>
   <td style="text-align:left;"> Producer prices in Canada jumped 3.1% month-over-month in February of 2022, the sixth consecutive monthly increase, and the largest monthly gain since January of 1980. Prices for energy and petroleum products rose 8.5%, with cost of motor gasoline exiting refineries in Canada up 8% and diesel fuel 9.2%. Prices for primary non-ferrous metal products rose 5.7%, led mainly by higher prices for unwrought aluminum and aluminum alloys (10.6%). Also, the price of softwood lumber jumped 8.3% and cost of intermediate food products rose 3.3%. Year-on-year, producer prices increased 16.4%, slightly higher than 16.3% in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/serbia/current-account </td>
   <td style="text-align:left;"> 2022-03-22 20:36:00 </td>
   <td style="text-align:left;"> Serbia Current Account Switches to Deficit in January </td>
   <td style="text-align:left;"> Serbia’s current account swung to a deficit of USD 164 million in January of 2022 compared to a surplus of USD 304 million in the corresponding month of the previous year. The goods and services gap rose to USD 360 million from USD 7 million. At the same time, the primary income shortfall widened to USD 115 million from USD 95 million and the secondary income surplus narrowed to USD 311 million from USD 406 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/morocco/interest-rate </td>
   <td style="text-align:left;"> 2022-03-22 20:23:00 </td>
   <td style="text-align:left;"> Morocco Interest Rate Unchanged at 1.5% </td>
   <td style="text-align:left;"> The National bank of Morocco held its benchmark interest rate at 1.5% at its March 2022 meeting, citing strong uncertainties surrounding the geopolitical developments relating to the war in Ukraine and their implications both internationally and domestically. Policymakers said that new projections show a substantial decline in agricultural value-added and some consolidation of non-agricultural activities, boosted by the significant progress in the vaccination campaign, the easing of sanitary restrictions, and the continuation of monetary stimulus and sectoral support measures. The bank revised down its 2022 growth forecast to 0.7% from an earlier 2.9%, citing a severe drought that lowered prospects for this year's cereals harvest. Meanwhile, inflation is seen accelerating to 4.7% in 2022 from 1.4% in 2021, driven by external pressures related to the surge of energy and food products prices, before returning to 1.9% in 2023. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bosnia-and-herzegovina/producer-prices-change </td>
   <td style="text-align:left;"> 2022-03-22 20:19:00 </td>
   <td style="text-align:left;"> Bosnia and Herzegovina Producer Inflation at Over 13-Year High </td>
   <td style="text-align:left;"> Producer prices in Bosnia and Herzegovina jumped by 10.6 percent from a year earlier in January of 2022, following a 8.5 percent rise in the previous month. It was the highest producer inflation rate since August of 2008, driven by higher inflation in manufacturing (13.5 percent vs 12 percent in December); mining and quarrying (6.1 percent vs 0.2 percent); and electricity, gas, steam &amp; air conditioning supply (4.7 percent vs 1.9 percent). Meanwhile, producer prices went up by 2.1 percent, following a 1 percent rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/current-account </td>
   <td style="text-align:left;"> 2022-03-22 20:18:43 </td>
   <td style="text-align:left;"> Euro Area Posts 1st Current Account Deficit since 2020 </td>
   <td style="text-align:left;"> The Euro Area recorded a current account gap of EUR 1.7 billion in January of 2022, the first deficit since May of 2020, as surging energy imports weighed on the goods balance (EUR -5.3 billion). The secondary income account also recorded a deficit (EUR -15.9 billion), while the services surplus was EUR 11.7 billion and the primary income account showed a EUR 7.9 billion surplus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/22/uk-watchdog-puts-50-crypto-firms-on-notice-over-misleading-ads.html </td>
   <td style="text-align:left;"> 2022-03-22 20:14:23 </td>
   <td style="text-align:left;"> UK watchdog puts 50 crypto companies on notice over 'misleading' ads </td>
   <td style="text-align:left;"> , LONDON — Over 50 cryptocurrency companies have been sent enforcement notices by the U.K.'s advertising watchdog as part of a regulatory crackdown on promotions in the industry.                                                                                                                 , The Advertising Standards Authority said Tuesday it has told the firms to review their ads and make sure they are in compliance with the rules. It also threatened firms with targeted sanctions if "problem ads" persist after May 2.                                                           , This would include reporting non-compliant advertisers to another regulator, the Financial Conduct Authority.                                                                                                                                                                                    , In its notice to the companies, the regulator gave guidance stating advertisers must make clear digital assets are unregulated in the U.K. Firms must not urge people to buy bitcoin or another cryptocurrency in their ads, or create the "fear of missing out" on an investment, the ASA added., The ASA didn't name the companies it has contacted, but said it has previously banned ads from the likes of crypto platform Coinbase and pizza chain Papa John's over concerns they misled consumers.                                                                                            , "This is a 'red alert' priority issue for us and we've recently banned several crypto ads for misleading consumers and for being socially irresponsible," the ASA said in a statement Tuesday.                                                                                                   , It comes as Britain takes a tougher line on the crypto industry. The government in January said it would bring crypto ads under the same rules for financial promotions, a move that would require advertisers in the industry to be authorized by regulators.                                   , Regulators have also proposed limiting crypto ads in such a way that consumers may only respond to them if they qualify as high-net-worth individuals or sophisticated investors, a move that has been criticized by industry representatives.                                                   , A consultation from the Financial Conduct Authority with the industry on regulation of crypto ads is set to expire on Wednesday.                                                                                                                                                                 , Global Digital Finance, an industry body that includes crypto exchanges Coinbase and Bitfinex, said it has sent a letter to U.K. Finance Minister Rishi Sunak expressing some concerns.                                                                                                          , "Rather than attempting to broaden the scope of existing legislation, stifling the market and attracting unintended consequences, a new bespoke regime should be implemented," Lavan Thasarathakumar, Global Digital Finance's director of government and regulatory affairs, said in the letter., "This regime would include obligations for how cryptoasset promotions should be communicated and more generally would provide clarity on how cryptoasset firms should conduct themselves and how regulators should supervise them."                                                              , Separately, a deadline for crypto firms to be registered with the FCA is set to elapse on Mar. 13. A number of companies, including Revolut and Copper, face the prospect of having to wind down their crypto operations in the U.K. if their application is not approved in time.               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-22 20:08:18 </td>
   <td style="text-align:left;"> Australia 10Y Bond Yield Climbs Over 3-Year Highs </td>
   <td style="text-align:left;"> The benchmark 10-year Australian bond yield extended gains to 2.72%, the highest in over three years, following global bond yields higher on prospects of a more hawkish US Fed. The Chairman of the US central bank signaled a 50bps hike was possible, after the Federal Reserve raised its funds rate by an expected 25 bps at its last meeting. Also, investors now see the Reserve Bank of Australia raising interest rates up to 1.5% this year, compared with 1.25% in earlier projections. The first hike should come as early as June, as the central bank said it was open to tightening monetary policy if the economy continued to surprise with its strength. The case for a rate hike strengthened after upbeat labor market data for February showed Australia’s jobless rate declining to a 14-year low of 4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/stock-market </td>
   <td style="text-align:left;"> 2022-03-22 19:55:46 </td>
   <td style="text-align:left;"> Hong Kong Shares Surge 3.2% </td>
   <td style="text-align:left;"> The Hang Seng ended 3.2% higher at 21890 on Tuesday, the highest level in three weeks, with shares of Alibaba soaring 11.2% after the company said it will increase the size of its share buyback program from $15 billion to $25 billion. Tech shares were also higher, with the Hang Seng Tech Index adding 5.4%, led by gains in stocks of JD.com, Tencent and Meituan. Traders were also upbeat as the case for monetary stimulus in China was building amid mounting external risks to an already slowing economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/22/health/measuring-immunity-correlates-of-protection/index.html </td>
   <td style="text-align:left;"> 2022-03-22 19:44:46 </td>
   <td style="text-align:left;"> How protected are we against Covid-19? Scientists search for a test to measure immunity - CNN </td>
   <td style="text-align:left;"> (CNN)In 2010, doctors told Ben Sobieck, now 37, that his kidneys were inexplicably failing. Shortly after, he had a kidney transplant and started on the lifelong medications that weaken his immune system to keep his body from rejecting the donor organ. They never figured out what caused Sobieck's kidney failure. But a decade later, he confronted another threat to his health: the Covid-19 pandemic., "I am on immunosuppressants that make me more vulnerable for serious Covid complications," said Sobieck, 37, who lives in Minnesota. "If you're immunocompromised, you may not have a very good response to the [Covid-19] vaccine."                                                                                                                                                                             , Seeking evidence that his immune system was working the way it should, Sobieck made an unusual request: He asked his nephrologist to do a blood test that gives a rough measure of antibodies, a type of protein the body creates in response to an infection or vaccine. Antibody titers reveal the concentration of a specific antibody found in someone's blood.                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                  , Millions of Americans -- not just those with weakened immune systems -- are wondering about their protection after a winter of booster shots and Omicron infections. As mask mandates are lifted and restrictions removed in a step toward normalcy, a test to measure immunity would be a powerful tool to measure individual risk.                                                                             , "The biggest reason I wanted to get my antibody titer checked is because I don't know how to assess risk," Sobieck said. "Anyone who is immunocompromised, from the beginning of this pandemic right through today, has very few tools to assess risk: if they're going to leave the house, when they're going to leave the house, how to interact with other people, which situations are OK."                  , Sobieck had his antibody levels checked after his second, third and fourth doses of the Moderna Covid-19 vaccine. Each result showed that he had more than the maximum number of antibodies the test could detect, indicating a robust immune response.                                                                                                                                                          , Although there is no specific guidance on how to interpret these results to figure out the level of protection against infection or disease, Sobieck felt reassured that his immune system was doing its job.                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                                                                                  , "More than 50% of transplant patients don't have enough immune response to be protected, even if they get not two but three doses of the vaccine that we use in the general population," said Dr. Dorry Segev, professor of surgery at New York University Langone Health. "For them, [an antibody titer] is a particularly poignant indicator of whether they have any protection at all."                      , Segev, a transplant surgeon, advocates using tests that measure antibodies as a way to check immune protection in people who are immunocompromised.                                                                                                                                                                                                                                                              , Sobieck says the test results allowed him to make decisions for himself and his family.                                                                                                                                                                                                                                                                                                                          , "Knowing that I had the antibody response that I had meant that my son could go to in-person school. That's huge," he said.                                                                                                                                                                                                                                                                                      , Correlates of protection                                                                                                                                                                                                                                                                                                                                                                                         , About 95% of Americans 16 and older have antibodies against Covid-19 as of December, the most recent date that data is available, according to US Centers for Disease Control and Prevention estimates that use information from blood donors.                                                                                                                                                                   , But it's one thing to measure antibody levels. It's another to measure how much they protect you against Covid-19.                                                                                                                                                                                                                                                                                               , The US Federal Drug Administration recommends against checking antibody levels at all because there's no agreed-upon way to calculate how any given antibody level protects you from infection or severe disease. It may also give a false sense of security, the agency says.                                                                                                                                   , "There aren't good correlates of protection -- something that says that this is the measurement that one needs to know how well they are protected," Emory University virologist Mehul Suthar said.                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                  , Scientists are trying to fill the knowledge gap. Studies measure average antibody levels across a population to check vaccine efficacy, often using antibody levels months after vaccination to determine the need for a booster. One study in people who got the Moderna vaccine found that higher antibody levels after vaccination were associated with lower risk of Covid-19 infection.                     , But not all antibodies are created the same. Of all the antibodies that the body may make after infection or vaccination, only a fraction are considered "neutralizing antibodies," meaning they can actively prevent infection.                                                                                                                                                                                 , Tests to measure antibodies can be either quantitative or qualitative. Quantitative tests provide a specific number, up to a certain point, of antibodies in the blood. Qualitative tests will indicate only whether certain antibodies were detected. Results of qualitative tests are either positive, negative or indeterminate for neutralizing antibodies.                                                  , When it comes to  measuring neutralizing antibodies specifically, there is only one type of test that has been given emergency FDA authorization to detect them, and it is qualitative.                                                                                                                                                                                                                          ,                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                  , Several studies have demonstrated that neutralizing antibodies are a strong correlate for protection against symptomatic infection with Covid-19 and its variants, with boosters enhancing neutralization.                                                                                                                                                                                                       , Peter Gilbert, professor of vaccine and infectious diseases at the Fred Hutchinson Cancer Research Center and lead author of the Moderna study, says these correlates are useful to apply to large groups. For example, scientists can use data from larger studies about the correlation between antibody levels and vaccine efficacy in adults to make a prediction about vaccine efficacy in children.        , However, reaching conclusions based on one person's antibody levels is far more limited. Gilbert compares individual antibody titers with a dipstick for oil in a car.                                                                                                                                                                                                                                           , "Is the oil in a particular car low? Therefore, you need to go out and get some new oil," or in this case, "get another shot of the vaccine," he said. "For that purpose, the markers aren't as good."                                                                                                                                                                                                           , This is largely due to how antibody levels vary from person to person. That correlate of protection also changes over time and with different coronavirus variants, which makes it hard to define a cutoff for antibody levels above which scientists can confidently say that someone is protected against Covid-19.                                                                                            , Natural vs. vaccine-acquired immunity                                                                                                                                                                                                                                                                                                                                                                            , There's a key difference in how antibody levels compare in people who have been vaccinated against Covid-19 versus those who have been infected with the coronavirus.                                                                                                                                                                                                                                            , "Whereas a vaccine response, you may have all individuals that got the vaccine have high antibodies and sort of wane over time. ... With infection, it's remarkably heterogeneous. You'll have lots of individuals that have very low and individuals that have very high antibody responses," Suthar said.                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                                                  , According to Marion Pepper, an associate professor of immunology at the University of Washington, location matters, especially for the immune system.                                                                                                                                                                                                                                                            , "There are different immunological environments that make up your body. ... When you see an immune response in your arm, it's going to be a different cast of characters than if you see an immune response in your lungs," Pepper said.                                                                                                                                                                         , The immune system "is like lots of different neighborhoods, and each one has a different flavor," depending on how an individual gets exposed to the coronavirus, whether it's through a vaccine injected into the upper arm or through an infection to the respiratory system.                                                                                                                                  , The CDC cites one study, which is in preprint and has not been peer-reviewed, that found antibody titers waned more quickly in vaccinated people than in people who had been infected. This may help explain the growing evidence of stronger and more durable vaccine efficacy in people who have immunity through both illness and vaccination, called hybrid immunity.                                        ,                                                                                                                                                                                                                                                                                                                                                                                                                  , Although they may not provide the best way to tell how protected someone is, antibodies are useful to understanding how we compare people with natural immunity with those with vaccine-acquired immunity.                                                                                                                                                                                                       , "We know that people who have this hybrid immunity are better protected. ... So it also really begs the question, 'which of these parameters is associated with that protection?' " said Pepper, who leads a lab that is studying hybrid immunity.                                                                                                                                                               , Observing levels of immune cells and antibodies as they change over time in different groups of people can help scientists learn how to create vaccines and time vaccinations to replicate the strength of hybrid immunity without the actual infections.                                                                                                                                                        , Just one piece of the immunity puzzle                                                                                                                                                                                                                                                                                                                                                                            , Antibody levels are only one part of the immunity story. There are also T cells, a type of white blood cell that helps fight infection by killing cells that have been infected with a virus or by helping another type of white blood cell, the B cell, create antibodies.                                                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                                                  , So why do we focus so much on antibodies? "One aspect is that antibodies are probably one of the easiest to measure in the laboratory," Suthar said.                                                                                                                                                                                                                                                             , "I think when you go to the T-cell-based assays, they're much more challenging," he explained. "Each individual has different what are called H.L.A. types that make it a bit more challenging to understand how well one's T-cell responses are against this virus."                                                                                                                                            , Unlike antibodies, which are responsible for preventing an infection, T cells are responsible for destroying cells that are already infected. T cells may play a big role in vaccine efficacy against serious disease from more transmissible coronavirus variants, such as Omicron.                                                                                                                             , One study showed that while the highly mutated Omicron could evade previously neutralizing antibodies, T cells preserved a strong response.                                                                                                                                                                                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                                                  , "A memory B cell is a B cell that can get reactivated to make antibodies. It generally doesn't do that unless a T cell tells it to go, so studying the T cells is going to be really important for understanding this immune protection," Pepper said.                                                                                                                                                           , However, she said that the complexity of measuring T cells means there isn't going to be a rapid test to measure them any time soon.                                                                                                                                                                                                                                                                             , The Omicron surge has demonstrated that infection rates can still be high even after a vaccine or a prior infection. With the possibility of more variants forming, Covid-19 has become a moving target requiring a constantly evolving understanding of these correlates of protection.                                                                                                                         , "The biggest question I have and I think everyone else has is: What level of antibody equals protection from serious complications from Covid?" Sobieck said.                                                                                                                                                                                                                                                    , CNN Chief Medical Correspondent Dr. Sanjay Gupta and Michael Nedelman contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/currency </td>
   <td style="text-align:left;"> 2022-03-22 19:40:00 </td>
   <td style="text-align:left;"> Indian Rupee Gains Slightly </td>
   <td style="text-align:left;"> The Indian rupee strengthened towards 76.2 tracking a jump in domestic equities and high dollar sales by the exporters. However, gains were limited by surging crude oil prices as the European Union considers an embargo on Russian oil imports as Russia continues to bombard the Ukrainian cities. Oil prices impact India’s current account deficit and trade balance significantly as India imports more than 80% of its oil needs. Meanwhile, India’s GDP grew at a slower 5.4% during the September-December period of 2021 while its inflation rose for the fifth consecutive month, at a higher than expected rate of 6.07% in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/22/stocks-making-the-biggest-moves-in-the-premarket-nike-okta-alibaba-and-more.html </td>
   <td style="text-align:left;"> 2022-03-22 19:36:59 </td>
   <td style="text-align:left;"> Stocks making the biggest moves in the premarket: Nike, Okta, Alibaba and more </td>
   <td style="text-align:left;"> , Take a look at some of the biggest movers in the premarket:                                                                                                                                                                                                                                                                                                , Nike (NKE) – Nike reported quarterly profit of 87 cents per share, 16 cents a share above estimates. Revenue beat estimates as well, helped by an increase in digital sales and its ability to successfully navigate supply chain issues. Nike jumped 6.3% in the premarket, and its results also boosted shares of rival Foot Locker (FL) by 1.4%.        , Okta (OKTA) – Okta is investigating reports of a digital breach, with the authentication services provider saying it would provide more information when it becomes available. Okta shares slid 6.3% in premarket trading.                                                                                                                                 , Alibaba (BABA) – Alibaba increased its share buyback program to $25 billion, the largest ever for the China-based e-commerce giant. The move follows a slump in the stock's price on regulatory and growth concerns. Alibaba surged 8% in premarket action.                                                                                                , Altria (MO) – The tobacco producer's shares rose 1.2% in the premarket after Goldman upgraded Altria to "buy" from "neutral." Goldman pointed to Altria's strong cash flow, high profit margins and attractive dividend amid a current "risk-off" environment.                                                                                             , Tencent Music (TME) – Tencent Music rallied 4.5% in premarket trading after the entertainment services company reported better-than-expected quarterly earnings and said it would pursue a secondary listing on the Hong Kong Stock Exchange.                                                                                                              , Switch (SWCH) – Switch remains on watch following a Bloomberg report that the data center operator was exploring options including a possible sale of the company. Switch has risen for the past five trading sessions, gaining 11% over that stretch.                                                                                                     , Upstart Holdings (UPST) – The cloud-based lending platform operator was downgraded to "underperform" from "neutral" at Wedbush, which cited Upstart's dependence on third-party funding as well as macroeconomic risks. Upstart slid 3.6% in premarket action.                                                                                             , Canadian Pacific Railway (CP) – Canadian Pacific and its workers agreed to binding arbitration to resolve their labor dispute, allowing operations to resume after a weekend lockout.                                                                                                                                                                      , Paramount (PGRE) – The office-centered real estate investment trust saw its shares rise 1.9% in the premarket after it rejected a takeover offer from asset management firm Monarch Alternative Capital. Paramount said the $12 per share offer significantly undervalues the company but said it remains open to any ideas that enhance shareholder value., Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                     , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                     , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                           , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                           , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                         , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/live/2022/03/22/business/stocks-oil-inflation-ukraine </td>
   <td style="text-align:left;"> 2022-03-22 19:33:37 </td>
   <td style="text-align:left;"> Stocks, Oil and Businesses React to Ukraine-Russia War: Live News - The New York Times </td>
   <td style="text-align:left;"> The step, announced as U.S. and British officials met in Baltimore, removed trade barriers erected under former President Donald J. Trump.                                                                                                                                                                                                                                                                                                                                                                                  , S&amp;P 500                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , %                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Dow                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , %                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Nasdaq                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , %                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , As of                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Data delayed at least 15 minutes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Source: FactSet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , By Ana Swanson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The Biden administration said on Tuesday that it would roll back Trump-era tariffs on British steel and aluminum, moving to resolve a trans-Atlantic trade clash that had soured relations with a key ally.                                                                                                                                                                                                                                                                                                                 , Under the agreement, the United States will allow a certain volume of metals from the United Kingdom to be imported duty-free starting June 1. In return, Britain agreed to lift tariffs on more than $500 million worth of American whiskey, blue jeans, motorcycles and other products, removing barriers imposed on U.S. exports during the trade spats of the Trump administration.                                                                                                                                     , The announcement, which came at the conclusion of two days of trade talks between British and American officials, removed some of the last remaining vestiges of the trans-Atlantic trade clashes of the last few years.                                                                                                                                                                                                                                                                                                    , The European Union — which included the United Kingdom until 2020 — imposed the tariffs on American products as retaliation for the levies that former President Donald J. Trump placed on foreign steel and aluminum in 2018. Post-Brexit, the United Kingdom maintained many of those tariffs on American goods.                                                                                                                                                                                                          , Biden administration officials, particularly Katherine Tai, the United States trade representative, and Gina Raimondo, the commerce secretary, have worked over the last year to scale back many of those barriers, believing that the United States should focus its energy on countering economic rivals, not fighting with allies.                                                                                                                                                                                       , During two days of meetings in Baltimore that kicked off a new trade dialogue, American and British officials pledged to advance policies that would deepen their partnership and would benefit workers and the environment. Officials also said they would continue to cooperate on measures to penalize President Vladimir V. Putin of Russia for that country’s invasion of Ukraine.                                                                                                                                     , Under the agreement, British steel and aluminum that is imported into the United States must be entirely smelted and cast in the United Kingdom to escape tariffs, to prevent cheap steel from China and other countries from finding a backdoor into the U.S. market. In addition, any British steel company owned by a Chinese entity must audit their financial records to assess influence from the Chinese government and share those results with the United States, the Biden administration said.                   , American and British officials also said semifinished products containing aluminum from China, Russia or Belarus would not be allowed to come into the United States duty-free.                                                                                                                                                                                                                                                                                                                                             , Restrictions still apply: If shipments of steel and aluminum from Britain exceed certain levels, they will be taxed at the existing tariffs of 25 percent on steel and 10 percent on aluminum.                                                                                                                                                                                                                                                                                                                              , As part of the agreement, the United States and Britain will also continue to confer on “market-distorting influence or ownership” in the steel and aluminum industries.                                                                                                                                                                                                                                                                                                                                                    , The United States said it would send a trade delegation to Britain for further talks soon.                                                                                                                                                                                                                                                                                                                                                                                                                                  , The deal “delivers on President Biden’s vision to repair relationships with our allies while also helping to ensure the long-term viability of our steel and aluminum industries, the communities they support, and most importantly, the workers in these industries on both sides of the Atlantic,” Ms. Tai said in a statement.                                                                                                                                                                                          , Thomas M. Conway, the international president of United Steelworkers, said the union supported the agreement and that it was “an important step in addressing systemic problems like illegal dumping and global overcapacity that threaten the vitality and future of our steel and aluminum industries.”                                                                                                                                                                                                                   , Chris Swonger, the chief executive of the Distilled Spirits Council, said that American distillers were “cheering the end of this long tariff nightmare.” According to the group, American whiskey exports to Britain had declined by 42 percent since 2018, when the tariffs were imposed.                                                                                                                                                                                                                                 , “With the removal of the U.K.’s debilitating retaliatory tariffs on American Whiskey exports, U.S. distillers are ready to fire up the stills,” he added.                                                                                                                                                                                                                                                                                                                                                                   , The two countries did not profess their intention to complete negotiations that began during the Trump administration for a free-trade agreement. British leaders had lauded the potential deal as an independent step for their economy after departing the European Union and have pushed the Biden administration to take up negotiations.                                                                                                                                                                               , But the Biden administration has shown little appetite for adopting the Trump administration’s goals, saying instead that the trade dialogue with the United Kingdom should explore “mutual international trade priorities rooted in our shared values, while promoting innovation and inclusive economic growth.”                                                                                                                                                                                                          , The coming dialogue will address issues like trade and investment involving small businesses, the digital economy, durable supply chains, and protecting labor rights and the environment, the Biden administration said.                                                                                                                                                                                                                                                                                                   , By Peter Eavis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Employees at a Starbucks store in Seattle have voted to unionize, the latest group to do so in a union push that appears to be gaining steam.                                                                                                                                                                                                                                                                                                                                                                               , The result, announced by the National Labor Relations Board after a count on Tuesday, takes the number of unionized company-owned U.S. stores to seven, out of nearly 9,000. Since Seattle is Starbucks’s hometown and birthplace, the result represents a big gain for Workers United, an affiliate of the Service Employees International Union.                                                                                                                                                                          , The tally was 9 to 0, and one ballot was uncounted after the company challenged it.                                                                                                                                                                                                                                                                                                                                                                                                                                         , Starbucks’s chief executive, Kevin Johnson, is leaving his post, the company said last week. The company has performed well financially during the pandemic, but management has had to contend with an upswell of criticism from employees — and its stock price is down 30 percent from its peak. Howard Schultz, who oversaw Starbucks’s growth into a global coffee giant, is returning as chief executive on an interim basis, effective April 4.                                                                       , The company’s leadership has long pursued a union-free model. But after two stores in the Buffalo area voted to unionize in December, more than 100 Starbucks stores in more than 25 states have filed for union elections.                                                                                                                                                                                                                                                                                                 , Two employees from the Seattle store spoke at a news conference organized by Workers United after the results were announced. Asked if she had a message for Mr. Schultz, Sydney Durkin, a shift supervisor at the store, said, “If he’s going to come in, expecting his old tactics to work, he’s going to find a whole new reality that is extremely different.”                                                                                                                                                          , The other employee, Rachel Ybarra, a barista, said, “We were able to show Starbucks this is a nationwide issue and we are all going to stand for each other.”                                                                                                                                                                                                                                                                                                                                                               , Starbucks did not respond to requests for comment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , In November, on a visit to Buffalo, Mr. Schultz sought to respond to the discontent among Starbucks’s partners, the term it uses for its employees. “No partner has ever needed to have a representative seek to obtain things we all have as partners at Starbucks,” he wrote in a letter titled “From Buffalo With Love” that coincided with his visit. “And I am saddened and concerned to hear anyone thinks that is needed now.”                                                                                       , The unionization efforts gained ground as employees cited concerns about understaffing and workplace safety during the pandemic. Starbucks’s legal response suffered a defeat in February, when the National Labor Relations Board in effect ruled that employees could unionize store by store.                                                                                                                                                                                                                            , The union victories at Starbucks come as inflation is eroding the purchasing power of wages and as economists expect workers to press for higher pay. In its annual report, released in November, Starbucks warned, “If a significant portion of our employees were to become unionized, our labor costs could increase and our business could be negatively affected by other requirements and expectations that could increase our costs, change our employee culture, decrease our flexibility and disrupt our business.”, By Stanley Reed                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , TotalEnergies, the French oil and gas company, said on Tuesday that it would stop buying Russian oil by the end of the year and halt further investment in projects in the country.                                                                                                                                                                                                                                                                                                                                         , At the same time, the company warned of the risks and potential negative consequences — for itself and Europe — of a headlong flight from Russia in the wake of Moscow’s invasion of Ukraine.                                                                                                                                                                                                                                                                                                                               , The Paris-based company said it had “initiated the gradual suspension of its activities in Russia, while assuring its teams’ safety.” TotalEnergies had said on March 1 that it would halt new Russian investment.                                                                                                                                                                                                                                                                                                          , Tuesday’s announcement expanded on that initial statement, describing how the company would no longer enter into or renew contracts to purchase Russian oil and petroleum products, and saying that would it would halt all such purchases by the end of this year. TotalEnergies also said it would stop providing capital for new projects in Russia, including a large planned liquefied natural gas installation called Arctic LNG 2.                                                                                   , The energy company’s actions since the invasion illustrate the challenges for European businesses and policymakers. Europe is dependent on energy from Russia, which is one of the world’s largest suppliers of oil and gas.                                                                                                                                                                                                                                                                                                , TotalEnergies itself is in a difficult position. The company said in its statement on Tuesday that it had been accused of “complicity in war crimes” for continuing to work in Russia. At the same time, its Russian business, especially liquefied natural gas investments, has been an important part of the company’s future strategy and something it has been reluctant to completely renounce.                                                                                                                        , TotalEnergies “is far more entrenched” in Russia than rivals like BP and Shell, which have made commitments to completely extricate themselves, said Biraj Borkhataria, an analyst at RBC Capital Markets, an investment bank.                                                                                                                                                                                                                                                                                              , Buying energy from Russia is also an established practice that will be difficult to abandon. TotalEnergies appears to have been one of the larger buyers of shiploads of Russian crude in 2021, averaging 186,000 barrels a day, according to data from Kpler, a research firm.                                                                                                                                                                                                                                             , TotalEnergies has contracts to import Russian oil  that comes by pipeline to its Leuna refinery in eastern Germany. The company said that it would terminate these deals by the end of 2022 and substitute supplies brought through Poland.                                                                                                                                                                                                                                                                                 , But the company warned that such moves could have an impact on the availability of an ingredient for diesel fuel that is already in short supply globally.                                                                                                                                                                                                                                                                                                                                                                  , The company said it was continuing to supply liquefied natural gas to Europe through a facility that it owns in part called Yamal LNG, as long as governments “consider that Russian gas is necessary.”                                                                                                                                                                                                                                                                                                                     , The company noted a dilemma that complicated efforts to liquidate its holdings. Russian law, it said, barred it from selling its various minority interests to non-Russian buyers.                                                                                                                                                                                                                                                                                                                                          , “Abandoning these interests without consideration would enrich Russian investors, in contradiction with the sanctions’ purpose,” TotalEnergies said.                                                                                                                                                                                                                                                                                                                                                                        , By Emma Goldberg                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Virginia’s workplace safety board voted on Monday to withdraw the state’s emergency rules for protecting workers from Covid-19, leaving employers to follow looser guidelines to prevent the spread of the coronavirus in the workplace.                                                                                                                                                                                                                                                                                    , Virginia, which has its own workplace safety agency, was the first state in the country to put in place emergency standards to protect workers from the virus. Under those standards, which were enacted in July 2020 under Governor Ralph Northam, a Democrat, employers had to require indoor masking in higher-risk areas, as well as report Covid outbreaks to the state’s Department of Health.                                                                                                                        , The current governor, Glenn Youngkin, a Republican, instructed the state health board to re-evaluate the standards earlier this year, arguing that they presented a burden to businesses.                                                                                                                                                                                                                                                                                                                                   , “The Virginia Covid-19 permanent standard became out of step with current C.D.C. guidance as well as what a lot of other states were doing to address the current state of the pandemic,” said Nathaniel M. Glasser, a lawyer at Epstein Becker &amp; Green, who specializes in Covid-19 and employment law, adding that nothing prevents employers from going above and beyond the state guidelines.                                                                                                                           , The rules will be replaced by guidelines for employers recommending that they promote vaccination, encourage employees with symptoms to stay home and require those infected with coronavirus not to come to work.                                                                                                                                                                                                                                                                                                          , Governor Youngkin said in a statement that “it is undeniable that Virginia is open for business.” The president of the Virginia A.F.L.-C.I.O., Doris Crouse-Mays, said the state had “opted to abandon safety protections for working people” and that “the Covid-19 crisis is still a pandemic.”                                                                                                                                                                                                                           , States with their own workplace safety agencies must have rules that are at least as effective as those set by the federal Occupational Safety and Health Administration. OSHA, under President Biden, tried to enact a sweeping rule requiring Covid vaccines or regular testing for some 84 million American workers. But the rule was withdrawn in January after being blocked by the Supreme Court, leaving workers and their employers across the country to confront a patchwork of state and local regulations.      , By Michael M. Grynbaum                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Justin Smith and Ben Smith, co-proprietors of a new media start-up that has captured the attention of the online news world, revealed on Tuesday the name for their venture: Semafor.                                                                                                                                                                                                                                                                                                                                       , The name is a variation on the word “semaphore,” a visual signaling apparatus often involving flags, lights and arm gestures, and often used in a nautical context.                                                                                                                                                                                                                                                                                                                                                         , At an appearance last week, Justin Smith said he and his partner had selected a brand name “that is the same word in 25 or 35 different languages,” a reflection of the company’s global ambitions. “It is very intentionally going to be able to live in Asia or Europe or the Middle East or America,” Mr. Smith said.                                                                                                                                                                                                    , The choice of Semafor was revealed on Tuesday by Axios, a news site that also began life as a high-profile start-up with an unusual name derived from a Greek word.                                                                                                                                                                                                                                                                                                                                                         , “It was really important for us to have a name that had the same meaning regardless of your native tongue,” Justin Smith, a former chief executive of Bloomberg Media, told the site.                                                                                                                                                                                                                                                                                                                                       , This is not the first time Justin Smith has expressed interest in a brand name derived from ancient Greek.                                                                                                                                                                                                                                                                                                                                                                                                                  , On at least one previous media project, Mr. Smith strongly considered using the word “Atlas,” a person familiar with his brainstorming said. His idea for The Atlas did not ultimately go forward.                                                                                                                                                                                                                                                                                                                          , Justin Smith and Ben Smith, who is a former media columnist for The New York Times, intend to recruit English-speaking journalists in many countries to compete with international news organizations like Reuters and The Associated Press. The Smiths, who are not related, said they expected the site to debut in the second half of the year.                                                                                                                                                                          , A federal trademark registration for Semafor, filed on Jan. 16, refers to “an interactive website featuring news and information in the fields of general interest news.” Along with “providing news and information,” the registration cites a number of business purposes, including “talent agency and booking services,” “literary agency services, namely, representation of journalistic talent,” and “arranging personal appearances by persons working in the field of news journalism and public affairs.”         , Only a handful of English words are the same or similar in many foreign languages, including taxi, chai, pajama and soup.                                                                                                                                                                                                                                                                                                                                                                                                   , Kitty Bennett contributed research.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , By Christopher F. Schuetze                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , BERLIN — Tesla officially began making cars in Europe on Tuesday, opening an assembly plant in a critical market where Elon Musk, the chief executive, plans to build 500,000 electric vehicles a year.                                                                                                                                                                                                                                                                                                                     , Mr. Musk escorted Chancellor Olaf Scholz of Germany and other officials on a tour of the huge, low-slung $7 billion plant just outside Berlin. It was constructed in a little more than two years, a speed that amazed German officials and commentators.                                                                                                                                                                                                                                                                   , “Electromobility will shape the mobility of the future,” Mr. Scholz said after the tour.                                                                                                                                                                                                                                                                                                                                                                                                                                    , Robert Habeck, the German vice chancellor and the country’s economy minister, said it was “a special day for the region, a special day also for Germany and a special day for the mobility transformation in Germany.”                                                                                                                                                                                                                                                                                                      , Mr. Musk wrote on Twitter: “Danke Deutschland!!”                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , He celebrated the day by handing over the first 30 European-built Teslas to customers who had ordered them and been invited to the event. Tesla will build its Model Y sport utility vehicle at the plant.                                                                                                                                                                                                                                                                                                                  , The plan for the factory, called Gigafactory Berlin-Brandenburg, was first revealed in a surprise announcement by Mr. Musk a little over two years ago, and it overcame a number of legal and political challenges to attain its production certification.                                                                                                                                                                                                                                                                  , Tesla raced to build the factory, and was allowed to proceed after securing only preliminary approvals from government authorities — on the condition that Mr. Musk agreed to tear down the plant and leave the site as he found it if state boards ultimately refused the project. It was a gamble that the carmaker won this month when the authorities approved the production site.                                                                                                                                     , A battery production plant on the property still requires state approval before going live.                                                                                                                                                                                                                                                                                                                                                                                                                                 , The speed with which Tesla built the factory in a country known for its rigid bureaucracy and deliberate planning was a theme during the opening speeches. Just a few miles away sits Berlin’s new airport, which opened two years ago after nearly a decade of delays.                                                                                                                                                                                                                                                     , Mr. Habeck started using the phrase “Tesla speed” some weeks ago, and Mr. Scholz said the short construction time would promote Germany as a place to invest.                                                                                                                                                                                                                                                                                                                                                               , “Germany can be quick,” he said in his speech.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The project also represents a significant financial investment in the former East German states that since reunification have attracted less major business than the traditional powerhouse states of the former West Germany. Jörg Steinbach, the Brandenburg state economics minister, who helped lure Tesla to the region, said: “All of the sudden we’re known. All of the sudden people are making enquiries.”                                                                                                         , The 2.4 million-square-foot plant places Tesla in one of the most important electric car markets in the world. European countries have passed laws to phase out internal combustion engines.                                                                                                                                                                                                                                                                                                                                , And electric cars are increasingly joining the mainstream. More than 20 percent of new cars sold in Europe and Britain in December were powered solely by electricity, data from government agencies showed. Europeans also bought more electric cars than diesels in December; diesels were once the most popular engine option in Europe.                                                                                                                                                                                 , The German site is Tesla’s third major plant, after factories in Fremont, Calif., and Shanghai. Another plant, outside Austin, Texas, is expected to open soon. The new plants are expected to double the company’s production capacity to about two million vehicles a year, according to analysts at Wedbush Securities.                                                                                                                                                                                                  , Once it is fully operational, the German plant will employ 12,000 people. Some 3,000 employees already work there, according to Tesla.                                                                                                                                                                                                                                                                                                                                                                                      , Built just 130 miles east of Volkswagen’s headquarters in Wolfsburg, on an old East German Army training site, the plant was also a direct challenge to German carmakers that had been trying to make E.V. inroads.                                                                                                                                                                                                                                                                                                         , Stefan Bratzel, director of the Center of Automotive Management in Bergisch Gladbach, Germany, said that while Tesla was a “thorn in the flesh of German automakers,” its presence in the country could ultimately help lift the entire sector.                                                                                                                                                                                                                                                                             , “On the one hand, this is the strongest competitor sitting right on the doorstep, but it can also have a motivating and stimulating effect,” he said.                                                                                                                                                                                                                                                                                                                                                                       , While state and federal governments supported the construction, a number of environmental and civic groups have criticized the factory, especially for its projected water use. Protesters on Tuesday walked around the Tesla site with handwritten signs criticizing Mr. Musk and Tesla. The police blocked an adjacent autobahn after activists climbed onto a road sign and plastered it with their own message: “Cars out.”                                                                                             , By Katie Robertson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The head of BuzzFeed News and two other top editors are departing the company ahead of cuts to the newsroom.                                                                                                                                                                                                                                                                                                                                                                                                                , Mark Schoofs, who became the editor in chief in 2020, said in a staff email on Tuesday that he would be stepping down. He said Tom Namako, the deputy editor in chief, and Ariel Kaminer, the executive editor of investigations, would also leave the company. Mr. Namako said on Twitter that he was joining NBC Digital as executive editor.                                                                                                                                                                             , Mr. Schoofs said in the email that BuzzFeed had subsidized the news division for many years and that the “next phase” for BuzzFeed News was to reach profitability in its own right.                                                                                                                                                                                                                                                                                                                                        , “That will require BuzzFeed News to once again shrink in size,” he said, adding that the company hoped to achieve this through voluntary buyouts rather than layoffs. He said the buyouts would be available to those on the investigations, science, politics and inequality desks.                                                                                                                                                                                                                                        , Samantha Henig, BuzzFeed News’s executive editor of strategy, will act as the interim editor in chief while a search for his successor is underway, Mr. Schoofs added.                                                                                                                                                                                                                                                                                                                                                      , Jonah Peretti, BuzzFeed’s chief executive, said in a separate email to the staff on Tuesday that BuzzFeed News would need to “prioritize the areas of coverage our audience connects with the most.” He also announced further job cuts across the company, including on the BuzzFeed video team and the editorial team at Complex Networks, a lifestyle publisher that BuzzFeed acquired last year, as well as the business and administrative teams.                                                                      , “The cuts impact around 1.7 percent of our total work force today,” Mr. Peretti wrote, “and we do not take that lightly.”                                                                                                                                                                                                                                                                                                                                                                                                   , The resignations and cuts are a major setback for BuzzFeed News, one of the scrappiest and most successful digital news operations in the country. The newsroom, started in 2011, made a name for itself with innovative storytelling and investigative reporting, winning a Pulitzer Prize in 2021 for a series that revealed the scale of China’s internment of Uyghurs.                                                                                                                                                  , But it has struggled financially and contracted at various times. In 2019, BuzzFeed cut 15 percent of its entire work force. In 2020, BuzzFeed News ended its operations in Australia and Britain. Late last year, the news division’s parent company, BuzzFeed, started trading on the stock market, adding pressure for better financial results.                                                                                                                                                                         , On Tuesday, BuzzFeed reported its financial results for the first time as a public company. It reported revenue in the most recent quarter of about $145 million, up 18 percent from a year earlier. Its profit rose 29 percent to $41.6 million, though this was bolstered by tax provisions and other accounting items.                                                                                                                                                                                                   , The company said it expected revenue to fall by “a low single-digit percentage” in the current quarter and record an adjusted loss between $15 million and $20 million.                                                                                                                                                                                                                                                                                                                                                     , BuzzFeed stock closed on Tuesday up more than 6 percent, at around $5.                                                                                                                                                                                                                                                                                                                                                                                                                                                      , BuzzFeed went public in December by merging with a special purpose acquisition company, or SPAC, in a deal that valued the company at $1.5 billion. The company is now worth about $660 million. Before the merger, investors in the SPAC withdrew about 94 percent of the money raised, leaving BuzzFeed with only $16 million.                                                                                                                                                                                            , Last week, nearly 80 former and current BuzzFeed employees filed mass arbitration actions against the company, accusing it of illegally preventing them from trading their shares because of administrative errors. The claims are asking for compensatory damages estimated at over $8.7 million. BuzzFeed said there was no merit to the claims.                                                                                                                                                                          , On an earnings call on Tuesday, Mr. Peretti said that short-form vertical videos, like those on TikTok, were emerging as the “preferred content format” for young people and that the company would accelerate its investment in them.                                                                                                                                                                                                                                                                                      , He said the changes at BuzzFeed News would accelerate its profitability.                                                                                                                                                                                                                                                                                                                                                                                                                                                    , “We will prioritize investments around coverage of the biggest news of the day, culture and entertainment, celebrity and life on the internet,” Mr. Peretti said.                                                                                                                                                                                                                                                                                                                                                           , By Alexandra Stevenson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , China Evergrande, the giant embattled property developer, will not be able to publish its annual financial results on time, the company said on Tuesday.                                                                                                                                                                                                                                                                                                                                                                    , The real estate giant blamed “drastic changes” to its business last year for the delay, adding that it would take its auditor a longer time to sift through the paperwork. The annual statement had been due by March 31.                                                                                                                                                                                                                                                                                                   , The news is the latest setback for the world’s most indebted property developer, whose troubles sent shock waves through global markets last September as the company teetered on the edge of collapse. Investors feared the collapse of Evergrande would trigger a “Lehman moment” in China, recalling the 2008 collapse of Lehman Brothers, which heralded the global financial crisis.                                                                                                                                   , Evergrande was once China’s biggest real estate developer, and its projects in hundreds of cities across China created millions of jobs for builders, painters, plumbers and other contractors. Now it is struggling to pay down a mountain of debt worth more than $300 billion to creditors, leaving contractors with unpaid bills and as many as one million home buyers with unfinished apartments.                                                                                                                     , For months last year, Evergrande swung from one loan to another, barely making the deadline on payments to lenders and foreign investors. In December, the government took a more hands-on role in helping the company manage its worsening financial situation. Later that month, global ratings agencies declared Evergrande to be in default, meaning it could no longer meet its financial obligations.                                                                                                                 , On Tuesday, the property developer also said banks had claimed $2.1 billion of cash from one of its subsidiaries, Evergrande Property Services. Evergrande tried to sell a $2.6 billion stake in the property management unit in October to raise cash for its mounting bills, but the deal fell through.                                                                                                                                                                                                                   , Evergrande suspended trading in its shares on Monday. A spokesperson for the company did not respond to a request for comment.                                                                                                                                                                                                                                                                                                                                                                                              , China Eastern Airlines Flight 5735, a Boeing 737-800 plane, was making a short trip between two cities in southern China on Monday, cruising at an altitude of more than 29,000 feet, when it violently plunged to the ground. Emergency crews continued to search the crash area on Tuesday for any sign of survivors among the 132 people on board. But it could be weeks or even months before investigators identify what caused the Boeing plane operated by China Eastern Airlines to drop from the sky.              , The Times’s Austin Ramzy and Niraj Chokshi reported on what we know so far about the crash.                                                                                                                                                                                                                                                                                                                                                                                                                                 , Flight 5735 took off at 1:16 p.m., according to data from Flightradar24, a tracking platform. The first hour of the flight proceeded as normal, with the plane cruising at 29,100 feet until, at about 2:20 p.m., it began to plunge, losing more than 20,000 feet in just over a minute. The plane’s sudden dive occurred near a point in the route where it would normally begin its initial descent, according to Flightradar24’s records.                                                                               , The Boeing 737-800 had flown for nearly seven years. It was not a 737 Max, the model that was grounded worldwide after two fatal crashes in 2018 and 2019. The Boeing 737-800 has a good safety record, according to the Aviation Safety Network database.                                                                                                                                                                                                                                                                  , China Eastern Airlines, the country’s second largest carrier, had a checkered record in its early years, and in the 1990s China was considered one of the most dangerous places to fly in the world. But officials carried out a regulatory overhaul in the 2000s, and the country has maintained an admirable safety record since. Its last major crash before Monday was in 2010.                                                                                                                                         , The initial investigation will focus on information from the flight data recorders, which has yet to be recovered. Experts will also study video records that have emerged, including security footage from a mining company that appeared to show a plane crash. Official reports on a crash’s cause can take months, or longer, to complete.                                                                                                                                                                              , READ THE FULL ARTICLE →                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , By Daisuke Wakabayashi                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Google has agreed to settle a National Labor Relations Board case filed by six former and current employees who said the company had illegally fired or disciplined them because of their unionization efforts.                                                                                                                                                                                                                                                                                                             , As part of the settlement, which was agreed upon on Friday, the former and current Google employees also agreed to dismiss a related court case in California. The settlement terms are bound by a nondisclosure agreement, said Laurie M. Burgess, a lawyer representing the former and current employees.                                                                                                                                                                                                                 , The settlement was reached after a ruling in the labor board case forced Google to hand over more documents. The complaint, which the labor agency brought in December 2020, said the search giant had illegally dismissed or disciplined and surveilled employees who were active in labor organizing.                                                                                                                                                                                                                     , Google has repeatedly said that its actions had nothing to do with trying to combat unionization efforts and that the employees breached security protocols. A spokeswoman said on Monday that it was “pleased for all sides to avoid years of legal proceedings.”                                                                                                                                                                                                                                                          , “We’ve always supported our employees’ right to speak about working conditions, and we stand by our policies that protect the security of our systems,” the spokeswoman added.                                                                                                                                                                                                                                                                                                                                              , Ms. Burgess said the settlement was not a loss. Her clients had devoted two years to fighting Google and needed to move on with their lives, she said.                                                                                                                                                                                                                                                                                                                                                                      , “My clients moved that process of exposing the underbelly of what Google has been doing in terms of trying to quell union and organizing activities farther than anyone else,” Ms. Burgess said.                                                                                                                                                                                                                                                                                                                            , The case brought to light Google’s extensive efforts to fend off a nascent unionization push. In documents pertaining to Google’s hiring of IRI Consultants, a firm known for its anti-union work, a Google lawyer said he wanted the consultants to help convince employees that “unions suck.”                                                                                                                                                                                                                            , In January, an administrative law judge ordered Google to hand over even more documents, which the company had withheld citing attorney-client privilege. In addition, Kent Walker, Google’s chief legal officer, was scheduled to testify in the N.L.R.B. trial.                                                                                                                                                                                                                                                           , Four of the people who brought the case were dismissed by the company, and two others were disciplined but not dismissed. One of those two remains at Google. As part of the settlement, the four fired employees waived their requests to be reinstated.                                                                                                                                                                                                                                                                   , By Emily Flitter                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , A Black homeowner who recently sought to refinance his mortgage with a new loan from Wells Fargo is suing the bank, claiming racial discrimination.                                                                                                                                                                                                                                                                                                                                                                         , The customer, Aaron Braxton, is tying his complaint to a news report this month that the bank denied more than half of all Black refinancing applicants in 2020 — a far higher rate than other banks, according to a lawsuit filed late Friday in federal court in the Northern District of California.                                                                                                                                                                                                                     , In the lawsuit, Mr. Braxton claims that the bank’s lending algorithms have amplified the U.S. financial system’s historically racist treatment of Black customers. Wells Fargo’s decisions to place its branches predominantly in white neighborhoods have also added to the harm, Mr. Braxton said in the suit.                                                                                                                                                                                                            , “The disparity between Wells Fargo’s treatment of Black American applicants and non-Black American applicants is significant and shocking,” lawyers for Mr. Braxton wrote in the complaint, which includes a request that the lawsuit be certified as a class action so that any similarly harmed people can be covered by its outcome.                                                                                                                                                                                     , “Mr. Braxton was given the runaround to such an extent that it took him over nine months to refinance his federally backed mortgage loan.”                                                                                                                                                                                                                                                                                                                                                                                  , Paul Turner, a Wells Fargo spokesman, said the bank used the same underwriting practices for all customers, regardless of their race or ethnicity.                                                                                                                                                                                                                                                                                                                                                                          , “In 2020, Wells Fargo helped more Black homeowners refinance their mortgage than any other large bank,” Mr. Turner said in a statement emailed to the The New York Times. He declined to comment on Mr. Braxton’s lawsuit.                                                                                                                                                                                                                                                                                                  , The lawsuit cites a recent analysis by Bloomberg of data that banks regularly report to the federal government. Under the Home Mortgage Disclosure Act, banks have to report the details of every home loan application they receive, including the borrower’s race, gender and ZIP code, and whether the loan was approved or denied. Bloomberg’s analysis, which was published this month, showed that Wells Fargo had approved a much lower percentage of refinancing applications than its peers.                       , It found that the bank had accepted just 47 percent of all Black borrowers’ applications, while other lenders had approved a combined 71 percent of their Black customers’ applications. By contrast, 72 percent of Wells Fargo’s white customers had their applications approved.                                                                                                                                                                                                                                          , Mr. Turner said Wells Fargo had done its own analysis of its lending practices using the same data that Bloomberg had used as well as data that is privately held by the bank.                                                                                                                                                                                                                                                                                                                                              , “Our analysis shows that additional, legitimate, credit-related factors that are not available in H.M.D.A. data were responsible for the differences in our refinance approval rate for Black homeowners.”                                                                                                                                                                                                                                                                                                                  , By Rebecca Robbins                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Pfizer said on Tuesday that it has agreed to sell up to four million treatment courses of its Covid-19 pills for use in 95 lower-income countries that are home to about four billion people, with the first supplies expected to become available next month.                                                                                                                                                                                                                                                              , The company’s supply agreement with UNICEF, the arm of the United Nations, covers all countries classified as low- or lower-middle-income, as well as some upper-middle-income countries in sub-Saharan Africa and other parts of the world.                                                                                                                                                                                                                                                                                , The pills will most likely be the first Covid drugs available in some of the poorest parts of the world. But they are enough for only a small fraction of the patients who could benefit.                                                                                                                                                                                                                                                                                                                                   , Pfizer has said it can make 120 million treatment courses of Paxlovid this year. Wealthy countries have locked up much of Pfizer’s early supplies.                                                                                                                                                                                                                                                                                                                                                                          , Pfizer’s treatment, known as Paxlovid, has been found to be highly effective in staving off severe disease in Covid patients when given early in the course of an infection. It is seen as having promise in lower-income countries because it is given in pill form, taken at home and easily stored at room temperature.                                                                                                                                                                                                  , But there are also significant hurdles to widespread use in low-resource settings, including a lack of testing and shortage of health care providers needed to prescribe the pills.                                                                                                                                                                                                                                                                                                                                         , Covid treatments that became available in wealthy countries earlier in the pandemic, such as monoclonal antibodies and the infused antiviral drug remdesivir, have not been used on  this scale in low-income countries because they are expensive and difficult to administer.                                                                                                                                                                                                                                             , A spokeswoman for the supply division of UNICEF described Tuesday’s deal as an agreement in anticipation of orders, which will be placed in response to demand from countries. She said there are several possible funding mechanisms for the orders, including money from recipient governments and UNICEF’s pooled fund for Covid therapeutics and other supplies.                                                                                                                                                        , Pfizer said it would sell its pills to low- and lower-middle-income countries at a nonprofit price that it has not disclosed. The company said it would charge more for pills supplied to upper-middle-income countries. The United States, paying a still higher price for wealthy countries, is being charged about $530 per treatment course.                                                                                                                                                                            , Manufacturers around the world are also gearing up to produce generic versions of the drug through a deal negotiated between Pfizer and the Medicines Patent Pool, a U.N.-backed nonprofit. Last week, the M.P.P. said that 35 companies had signed up to produce Paxlovid and sell the pills inexpensively in lower-income countries. But those supplies are not expected to be ready for many months, not nearly as quickly as the pills made by Pfizer.                                                                  , Many lower-income countries haven’t authorized Paxlovid and must do so before the pills can be used there. The World Health Organization, which lower-income countries look to for guidance on how to use Covid drugs, has not yet made a recommendation on Paxlovid, though it says the drug is one of several “currently under consideration.”                                                                                                                                                                            , Stephanie Nolen contributed reporting                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Today in the On Tech newsletter, Shira Ovide talks to the inventor Steve Perlman to mine lessons from the long marriage of technology and imagination in Hollywood and beyond. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/israel/industrial-production </td>
   <td style="text-align:left;"> 2022-03-22 19:33:00 </td>
   <td style="text-align:left;"> Israel Industrial Output Rises the Most in 3 Months </td>
   <td style="text-align:left;"> Industrial production in Israel climbed 9.9 percent year-on-year in January of 2022, quickening from an upwardly revised 4.6 percent rise in the previous month. It was the steepest rise in industrial output since last October, underpinned by robust momentum in manufacturing activities (9.4 percent vs 3.1 percent in December); and in mining &amp; quarrying (12.3 percent vs 13.2 percent). On a seasonally adjusted monthly basis, industrial output advanced 1.8 percent, compared to an upwardly revised 5.7 percent increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-22 19:27:00 </td>
   <td style="text-align:left;"> South Africa Government Bond 10Y at 1-Week High </td>
   <td style="text-align:left;"> South Africa 10-Year Government Bond Yield was at 9.8%, its highest since March 15th, with markets expecting the South African Reserve Bank to hike the benchmark rate by 25 basis points for a third straight meeting on March 24th to avoid higher inflation becoming entrenched. Meanwhile, Federal Reserve Chairman Jerome Powell said the central bank was prepared to raise interest rates by a half-percentage-point at its next meeting and high enough if it concluded such steps were warranted to bring down inflation. Locally, President Ramaphosa said that South Africa risks being rocked by strong economic headwinds in the coming months as the “conflict between Russia and Ukraine” impacts the global economy. The country's outlook is also growing cloudier due to domestic structural issues, in particular recurrent load shedding, corruption, and lack of progress in economic reforms. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ivory-coast/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-22 19:23:00 </td>
   <td style="text-align:left;"> Ivory Coast Inflation Rate Slows to 4.6% in February </td>
   <td style="text-align:left;"> The annual inflation rate in the Ivory Coast eased to 4.6% in February of 2022, from an over 10-1/2-year high of 5.6% in January. Prices slowed down mostly for food &amp; non-alcoholic beverages (8.8% vs 11.9% in January); housing &amp; utilities (5.7% vs 6.4%); communications (2.7% vs 3.1%) and furnishings (1.2% vs 1.6%). Furthermore, costs fell for health (-0.7% vs 0.3%) and recreation &amp; culture (-0.8% vs -1.2%). On a monthly basis, consumer prices were up 0.3%, after increasing 0.2% in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-22 19:21:00 </td>
   <td style="text-align:left;"> Indian 10-Year Bond Yield Edges Higher </td>
   <td style="text-align:left;"> Indian 10-year government bond yield edged up to 6.83%, not far from its 2-½-year high of 6.89% hit on February 3rd, tracking a rise in global bond yields after the Fed chairman backed a 0.5% hike in interest rate in May to clamp down on the surging inflation. On the contrary, the Reserve Bank of India (RBI) maintained a more dovish stance than expected in February and continued to keep the interest rate at 4% since March 2020 to support economic recovery from the pandemic induced slump. The domestic inflation rose to 6.07% in February, slightly higher than the central bank’s upper limit in the wake of surging crude oil prices caused by the Russia-Ukraine war. Meanwhile, the central bank conducted a debt auction last month after canceling previous two sales, which aligns with the Indian government’s record borrowing plan of USD 200 billion from April as proposed in the Union budget. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/factory-orders </td>
   <td style="text-align:left;"> 2022-03-22 19:20:29 </td>
   <td style="text-align:left;"> UK Factory Orders at Record Levels </td>
   <td style="text-align:left;"> The Confederation of British Industry's order book balance increased to 26 in March of 2022, matching November's all-time high of 26 and beating market forecasts of 16, as manufacturers reported higher order books. "This survey highlights strong order books and output growth, but the cost pressures facing manufacturers have been amplified by the conflict in Ukraine," said Anna Leach, CBI deputy chief economist. The proportion of British manufacturers expecting to raise prices over the next three months hit its highest since records began in 1975. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/producer-prices-change </td>
   <td style="text-align:left;"> 2022-03-22 19:12:04 </td>
   <td style="text-align:left;"> Irish Wholesale Price Inflation Eases in February </td>
   <td style="text-align:left;"> Ireland’s wholesale prices rose by 2.8 percent from a year earlier in February of 2022, easing from the 3.5 percent rise in the prior month. Prices rose at a slower rate for both exports sales (2.6 percent vs 3.3 percent in January) and domestic sales (6.2 percent vs 7.9 percent). On a monthly basis, wholesale prices advanced by 0.1 percent, growing at a constant rate from the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-22 18:58:55 </td>
   <td style="text-align:left;"> China 10Y Bond Yield at Near 2-Week High </td>
   <td style="text-align:left;"> China’s 10-Year Government Bond Yield climbed to a near two-week high of 2.84%, amid a global bond rout hawkish signals by US Fed Chairman Powell, suggesting a 50 bps hike would be in the playbook. Meanwhile, the People’s Bank of China decided to keep its Loan Prime Rate unchanged, in line with its move with the medium-term lending facility rate, surprising bets that the central bank would further cut interest rates. Still, analysts expect the PBOC to resume its loosening monetary policy in April, as the economy remains under significant downside risks from the fast-spreading omicron subvariant BA.2 and the elevated global commodity prices, as well as the war in Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/currency </td>
   <td style="text-align:left;"> 2022-03-22 18:47:06 </td>
   <td style="text-align:left;"> Swiss Franc Weakens </td>
   <td style="text-align:left;"> The Swiss franc weakened to 0.936 per USD, inching closer to the 17-month low of 0.94 hit on March 16th amid a stronger dollar after Fed Chair Powell suggested a 50bps rate hike in May could be necessary to control inflation. Domestically, investors await the Swiss National Bank’s meeting this week, expecting policymakers to hold rates unchanged and continuing its ultra-loose monetary environment. The SNB has already pledged to intervene in currency markets to curb the rise in the franc, which is a danger to Switzerland’s export-dominated economy. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-03-23 09:13:14 UTC +8

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
   <td style="text-align:left;"> 2022-03-23 09:12:42 </td>
   <td style="text-align:left;"> $SPY I want lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:12:41 </td>
   <td style="text-align:left;"> $SPY $DIA Watch the futures be red as heck then after the Fed talk the market shoots up Green 200pts....they playing games. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:12:41 </td>
   <td style="text-align:left;"> $SPY  even though I think overbought and bought sqqq against nastaq today ; this pos futures still too strong !!! 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:12:36 </td>
   <td style="text-align:left;"> $SPY  give me $4610 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:12:35 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:12:26 </td>
   <td style="text-align:left;"> $SPY  $4555.  New world order </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:12:09 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F 

Okay, what’s the consensus # on where this

Gets liquidated ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:12:08 </td>
   <td style="text-align:left;"> $SPY flat futes at night pirates delight...just need 447 🤏🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:11:49 </td>
   <td style="text-align:left;"> $SPY 320 will be resistance soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:11:32 </td>
   <td style="text-align:left;"> $SPY pulling back over night to open at like 445 446 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:10:58 </td>
   <td style="text-align:left;"> $SPY Whales have been able to steal enough money from bears to continue buying long. Possibly ATH’s soon…up and up fools </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:10:54 </td>
   <td style="text-align:left;"> $SPY ok it&amp;#39;s time to stop pumping this trash..down we go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:10:46 </td>
   <td style="text-align:left;"> $SPY student loan payments restart soon another boogeyman us bulls will have to consider but who cares pump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:10:46 </td>
   <td style="text-align:left;"> $SPY 🔪🐖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:10:44 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s the fed meetings usually later in the day 8 am is early </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:10:42 </td>
   <td style="text-align:left;"> $SPY so let’s get this straight,

1HR has some intense bearish divergence on the MACD, today discussion about nuclear war officially became something world leaders are bringing up, memes are running (remember meme hype usually correlated with red indeces)

And with 0 pullbacks SPY ran from 413 straight to 450. And people are bullish? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:10:19 </td>
   <td style="text-align:left;"> $SPY limit down and ima have my custom ordered m5 delivered to my front door </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:10:19 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ when I open up my trading app after a long day. A long red day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:10:17 </td>
   <td style="text-align:left;"> $SPY people who switched to lentils were fine tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:09:58 </td>
   <td style="text-align:left;"> $SPY   Drop this piece of shit $100 at least </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:09:53 </td>
   <td style="text-align:left;"> $SPY Most tickers are still in a P/E bubble at this price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:09:49 </td>
   <td style="text-align:left;"> $SPY 10yr going to hit 2.5% by the morning 😂😂😂 2 weeks ago it was below 1.7% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:09:35 </td>
   <td style="text-align:left;"> $SPY take your clot shots $MRNA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:09:33 </td>
   <td style="text-align:left;"> $SPY   Calling tops </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:09:23 </td>
   <td style="text-align:left;"> $SPY   -$300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:09:13 </td>
   <td style="text-align:left;"> $SPY $DWAC $QQQ  
 
If Joe Biden got 81m votes and has 56% disapproval rating that means around 10m Americans will vote for GOP that voted for Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:09:11 </td>
   <td style="text-align:left;"> $SPY One of the dangers of historically low interest rates is that they can inflate asset prices. As a result, things such as stocks, bonds, and real estate trade at higher valuations than they would otherwise support. For stocks, one result can be higher-than-normal price-to-earnings ratios, PEG ratios, dividend-adjusted PEG ratios, price-to-book-value ratios, price-to-cash-flow ratios, price-to-sales ratios, and lower-than-normal earnings yields and dividend yields.  
 
All of this can seem fantastic if you bought stocks prior to the decline in interest rates, allowing you to experience the boom all the way to the top. It&amp;#39;s not so great for those without many assets put aside, who want to begin saving, such as young adults who are just out of high school or college. 
 
The opposite is also true, however. When interest rates rise, asset prices can decline below what they would normally be worth. 
 
https://www.thebalance.com/why-do-asset-prices-fall-when-interest-rates-increase-357150 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:09:09 </td>
   <td style="text-align:left;"> $SPY Icahn calling for recession OR worse. We headed for some dark days America. Thank the Biden supporters. They voted for this shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:08:51 </td>
   <td style="text-align:left;"> $SPY at least another week of gamma squeezing coming $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:08:38 </td>
   <td style="text-align:left;"> $SPY 

I love when they start pulling their hair back. IYKYK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:08:36 </td>
   <td style="text-align:left;"> $SPY futs rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:08:28 </td>
   <td style="text-align:left;"> latexbc9caa30b71ca37d8c071dc4a8eefde1$ JPM can lick my b@lls and anybody who wants to bring the pain to shorts buy $CLEU  WE’RE SQUEEZING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:08:26 </td>
   <td style="text-align:left;"> $SPY The thing about when prices start to pump and go up like this, is that you gotta start looking at the Fundamentals again.   
 
The Valuations, Earnings, P/E, Growth factors etc all do not do good when Interest rates go up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:08:05 </td>
   <td style="text-align:left;"> $SPY 🔥😏 Bro so wen Taiwan invasion? Hope it happens tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:07:58 </td>
   <td style="text-align:left;"> $SPY SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:07:41 </td>
   <td style="text-align:left;"> $SPY everything will pump at midnight … text book mass manipulation FED Hail Mary program launched 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:07:40 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $SQ $SNOW 
Rug Pull starts tomorrow 👻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:07:24 </td>
   <td style="text-align:left;"> $SPY new world order. $2800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:07:20 </td>
   <td style="text-align:left;"> $SPY a lot of imbalance in the market. this needs a small correction at least to fill some of those demand zones for the last 5days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:07:19 </td>
   <td style="text-align:left;"> $SPY give me 12 consecutive red hourly closes overnight please and thank you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:07:14 </td>
   <td style="text-align:left;"> $BTC.X If we go into a recession, this will nearly go to zero $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:07:07 </td>
   <td style="text-align:left;"> $SPY Dont be a chart Snob if you are the loser. Its a bad look. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:07:03 </td>
   <td style="text-align:left;"> $BTC.X if this POS breaks 40k before open tomorrow. GOOD FUCKIN RIDDANCE $AAPL $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:06:38 </td>
   <td style="text-align:left;"> $SPY 😂 BTC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:06:28 </td>
   <td style="text-align:left;"> $SPY memeSTONKS taking over again baby it’s2020-2021 frenzy gamma squeeze all over again !!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:06:10 </td>
   <td style="text-align:left;"> $SPY everything priced in..market on steroids at this point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:06:01 </td>
   <td style="text-align:left;"> $SPY  now.   NWO.   $3900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:05:58 </td>
   <td style="text-align:left;"> $SPY Nuke all tops </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:05:46 </td>
   <td style="text-align:left;"> $SPY If Biden, Pelosi, and AOC said they intend to do mandatory daily covid injections for all citizens, and then shoot nuclear missiles at Russia and Africa, and then mandate that every corporation has a tranny on their board of directors, what percentage of American liberals would support all this?  99% or 100%? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:05:41 </td>
   <td style="text-align:left;"> $SPY half the country tested positive and never got VAXXED and survived what retard 😂 

https://mobile.twitter.com/PressSec/status/1506324580960452608?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1506324580960452608%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fwww.infowars.com%2F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:05:28 </td>
   <td style="text-align:left;"> $SPY why are piece of shit worthless meme stonks trending again wtf is this 2021 all over again? We are heading to hyperinflation with this idiot fed that wont raise rates fast enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:05:27 </td>
   <td style="text-align:left;"> #LIVESTREAM ALERT🚨 
🔥WE ARE NOW LIVE 
I&amp;#39;m going to breakdown 👇 
📈trade ideas 
🔫triggers  
🎯targets  
click👉 https://us02web.zoom.us/j/84650646657  $SPY  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:04:14 </td>
   <td style="text-align:left;"> $SPY $QQQ  
Are we really surprised they all fell for the plandemic? . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:04:00 </td>
   <td style="text-align:left;"> $SPY buying any unwanted poots for 5Lbs of Lentils a piece and don&amp;#39;t try to Native Israeli me down it&amp;#39;s a fair offer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:03:58 </td>
   <td style="text-align:left;"> $QQQ when the market is back MEMEing you know they think the Feds is a joke, I really don’t blame bulls tho. The fed has been behind this situation for a long time now and they still behind and wanna raise .25. Why are they gonna keep waiting and waiting when employment been at target and they just not gonna address price stability. The Feds really have one job and that’s control prices, they can’t really control the job market. That’s just a function of the economy. They can always control inflation tho. At this point no matter what they do the Feds are fucked $spy $dia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:03:43 </td>
   <td style="text-align:left;"> $SPY Substantiate what your saying,  don&amp;#39;t just scream fire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:03:36 </td>
   <td style="text-align:left;"> $SPY no more sellers because they already sold and are hiding in their bunkers before nukes fire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:03:09 </td>
   <td style="text-align:left;"> $SPY we have the perfect mix of everything for this shit to crash.
But I kid you not, if this crashes it’s going to be for a totally stupid different thing🤦🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:03:07 </td>
   <td style="text-align:left;"> $SPY I bought calls at the top of every waterfall mid Jan through mid March and now bought puts at each new high since 415. 
I like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:03:03 </td>
   <td style="text-align:left;"> $SPY so what happens when there’s a new world order? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:03:03 </td>
   <td style="text-align:left;"> $SPY everyone on here says it&amp;#39;s going to tank when it hits 454 so I assume it will rocket to 461 when it touches 454. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:02:50 </td>
   <td style="text-align:left;"> $SPY 

What a surprise.   Hannity pounding war drums again!!  🙄. CNN might be recruiting him soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:02:43 </td>
   <td style="text-align:left;"> $SPY creepto wants to go down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:02:20 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ve been tryna fight my demons, I&amp;#39;ve been tryna fight my cup
I always tell her she my therapy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:02:17 </td>
   <td style="text-align:left;"> $SPY rates flying and just ignore. Yep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:02:15 </td>
   <td style="text-align:left;"> latex1b8f21ed05453a5774b9c51a080c27cb$

You’ve been warned. Have fun at the rigged casino which will only pay BULLZZZZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:01:17 </td>
   <td style="text-align:left;"> $SPY $DWAC WASHINGTON, D.C.—After over a year of courtship, Fox News correspondent Peter Doocy and White House Press Secretary Jen Psaki have announced they are finally tying the knot. 

&amp;quot;Um, on a personal note, I would like to announce that I will soon be stepping down to marry Peter Doocy,&amp;quot; said Psaki at the end of a recent press conference. &amp;quot;I believe, and the President agrees, that this is the best course of action for me at this point in time.&amp;quot;

Doocy then jumped up from his seat in the press pool and then did a fist pump before aggressively questioning the Press Secretary. &amp;quot;Excuse me,&amp;quot; he said, &amp;quot;don&amp;#39;t you think it&amp;#39;s a little hypocritical to host a lavish wedding ceremony to me in D.C. when so many people are struggling? And don&amp;#39;t you think it&amp;#39;s a conflict of interest to marry someone in the press?&amp;quot;

&amp;quot;No further questions,&amp;quot; said Psaki with a twinkle in her eye and a shy smile before exiting the stage. 

https://babylonbee.com/news/finally-peter-doocy-and-jen-psaki-announce-their-engagement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:01:14 </td>
   <td style="text-align:left;"> $SPY touch 446 tm then Yal could rocket over 452 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:01:10 </td>
   <td style="text-align:left;"> $SPY Bears are so mad,   Don’t you see the trend?   Tip:  Go with the wave not against it lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:01:08 </td>
   <td style="text-align:left;"> $SPY China’s top Russia envoy urged Chinese business people in Moscow to seize economic opportunities created by the crisis, a strategy that could help soften the blow from international sanctions.  
 
 https://www.msn.com/en-us/news/world/beijing-tells-chinese-in-russia-to-help-fill-economic-void/ar-AAVm1PQ?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:01:07 </td>
   <td style="text-align:left;"> $SPY BofA |  Equity Client Flow Trends

~ Inflows last week were corporate buyback driven

~ Hedge funds (3rd straight week), Institutional (1st time in 4 weeks) and Retail (1st time this year) were all net sellers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:00:43 </td>
   <td style="text-align:left;"> $SPY Spy futures crashing and VIX on a rampage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:00:39 </td>
   <td style="text-align:left;"> $SPY JPOW TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:00:36 </td>
   <td style="text-align:left;"> $SPY I have never seen a wedge with so much big dick energy in my life ahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 09:00:16 </td>
   <td style="text-align:left;"> $SPY Black Wednesday, MUHAHAHA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:59:53 </td>
   <td style="text-align:left;"> $SPY $TSLA

Are you that guy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:59:38 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:59:32 </td>
   <td style="text-align:left;"> $SPY Easy money here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:59:23 </td>
   <td style="text-align:left;"> $DWAC $SPY $QQQ  
 
Covid is still here and democrats want to drop mask mandates 
 
Don&amp;#39;t they care about Americans??? What about the science?!?!?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:59:13 </td>
   <td style="text-align:left;"> $SPY  U.S. President Joe Biden’s warning of unspecified consequences if China supports Russia has smaller Asian nations worried they’ll be subject to similar penalties for maintaining neutrality over Vladimir Putin’s war. 
 
 https://www.msn.com/en-us/news/world/u-s-threat-to-sanction-china-is-spooking-other-nations-in-asia/ar-AAVmrKt?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:58 </td>
   <td style="text-align:left;"> $SPY Nothing says bullish like the 10 year at 2.4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:51 </td>
   <td style="text-align:left;"> $SPY memes ripping… risk on… sorry bears… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:49 </td>
   <td style="text-align:left;"> $SPY when we can&amp;#39;t run we SCOOT to ATH we got thus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:43 </td>
   <td style="text-align:left;"> $SPY 🔥😏 anyone down to go all in on 0dte PUTS tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:31 </td>
   <td style="text-align:left;"> $SPY pumping rest of this week with small
Pull back Friday then pump again next week.. Don’t see this going all
The way back Down again. Bottoms in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:24 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:22 </td>
   <td style="text-align:left;"> $SPY with Biden in house it has to continue down!!! As much as we all don&amp;#39;t want it to happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:13 </td>
   <td style="text-align:left;"> $SPY You know all is well when meme stocks are moving like a rocket. Yawn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:13 </td>
   <td style="text-align:left;"> $SPY oh boy red futes .. game over BuLLzzz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:10 </td>
   <td style="text-align:left;"> $SPY Lots of bulls, we will crash 🔪🐖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:09 </td>
   <td style="text-align:left;"> $SPY $QQQ change my mind you should join 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:05 </td>
   <td style="text-align:left;"> $SPY The air war over Ukraine appears to have entered a new phase, with the Russian air force boosting the number of flights it makes per day by 50 percent and deploying an increasing array of Russian drones and munitions over the battlefield, according to U.S. defense officials and military analysts. 
 
https://www.msn.com/en-us/news/world/russian-air-force-action-increases-despite-flood-of-antiaircraft-missiles-into-ukraine/ar-AAVo7Lx?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:02 </td>
   <td style="text-align:left;"> $SPY 10 year at 2.412 and rising… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:58:00 </td>
   <td style="text-align:left;"> $SPY $VIX nice confirmation under 24 , still think market can run until 20 support on VIX. Feels like we are moving fast but still in downtrend, could see a fake out where we break 460 resistance but it doesn’t confirm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:57:56 </td>
   <td style="text-align:left;"> $SPY we had a big run before 2008 crash lol 😂 $AMC $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:57:24 </td>
   <td style="text-align:left;"> $SPY lotta bears here.. but markets up like crazy ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:57:18 </td>
   <td style="text-align:left;"> $SPY Not only do meme stocks exists, they are mooning!
Powell is a idiot that says things to calm you and make him look like he knows what he&amp;#39;s doing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:57:13 </td>
   <td style="text-align:left;"> $SPY does stocktwits have a family subscription? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:57:11 </td>
   <td style="text-align:left;"> $SPY Russia is officially going to sanction Hillary Clinton, won&amp;#39;t sell her anymore 80s pants suits or man-cankle bracelets. NATO protests </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:56:56 </td>
   <td style="text-align:left;"> $SPY 🔥😵 fking got intense nasal congestion from doing lines... this is GG, fking ruined. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:56:48 </td>
   <td style="text-align:left;"> $SPY Putin, OPEX, Evergrande,  Deathcross, Inflation,  Rate hikes, 10 yr rising, Supersonic nukes. 

None of those matters in a melt up mode.
Enjoy the ride !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:56:38 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $NDX $DIA 

The dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:56:36 </td>
   <td style="text-align:left;"> $QQQ $SPY and the 10 Yr continues… my question is are these just gonna keep going up when the 10 Yr finally decides to pullback? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:56:26 </td>
   <td style="text-align:left;"> $SPY the future doesn’t want to go down. Maybe more up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:56:18 </td>
   <td style="text-align:left;"> $QQQ $SPY Nikkei up 2%...Q&amp;#39;s/SPY going to rip so hard tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:56:18 </td>
   <td style="text-align:left;"> $SPY https://twitter.com/jsolomonreports/status/1506422785467465731?s=21 Get cash Get food and water . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:56:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA Which one of you lost the most and who gained the most today? Retail traders only </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:56:05 </td>
   <td style="text-align:left;"> $SPY “this is a stock exchange, there’s no money you can steal”

Bane: “really?! Then Why are you people here.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:55:35 </td>
   <td style="text-align:left;"> $SPY  $GAYMF and LGBTQ,s are welcome in Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:55:11 </td>
   <td style="text-align:left;"> $SPY $QQQ  CLINTON TESTS POSITIVE FOR COVID-19 -AXIOS

covid doesn’t stand a chance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:54:53 </td>
   <td style="text-align:left;"> $SPY if hang seng Keeps going up 3% a day I think it’s gonna be Hard for Nasdaq or spy to go down at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:54:52 </td>
   <td style="text-align:left;"> $SPY bane is coming to the market soon. 

https://youtu.be/nppON29OZ_4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:54:34 </td>
   <td style="text-align:left;"> $SPY this is really fucked up but does anyone else kinda sorta want Russia to do something so their prints will print again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:54:25 </td>
   <td style="text-align:left;"> $SPY this thing tanked AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:54:10 </td>
   <td style="text-align:left;"> $SPY 3/23/2022 Black Wednesday, one of the worst stock market crashes in history. Trillions of dollars were dumped on high oil, inflation, interest rate hikes, and Russia threatening to use nuclear weapons. Just your friendly neighborhood time traveler. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:53:52 </td>
   <td style="text-align:left;"> $SPY oil in a tight coil, obviously waiting on the EU clowns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:53:31 </td>
   <td style="text-align:left;"> $AABB $SPY $GOLD $BTC.X $ETH.X We should think about our money while it still has value. 
Because everything speaks for a new world order. 
The world reserve currency is in trouble. 
The only thing that can slow down inflation and the collapse of our currency is gold. 
That over a thousand years. 
The solution to our problems is a cryptocurrency backed by physical gold.   
AABB has such a system and is expanding it so that we can pay with gold tokens at every supermarket checkout in the future.  
1. NWO https://www.youtube.com/watch?v=xguam0TKMw8 
2. monetary order is coming https://www.kitco.com/news/2022-03-21/New-global-commodity-based-monetary-order-is-coming-Credit-Suisse.html 
3. Oil in Yuan/Saudis https://frontline.thehindu.com/dispatches/saudi-arabia-and-china-new-best-friends/article38460105.ece 
4. Oil in Rupee/Ruble https://www.ft.com/content/a5ee2d6b-693f-475d-80c6-0036c2657ef1 
5. Fear of inflation https://www.total-croatia-news.com/lifestyle/61350-croatian-exchange-offices 
and etc..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:53:24 </td>
   <td style="text-align:left;"> $SPY Lil bear tail is tingling my Frens came home......soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:53:20 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ 

Pump and dump Ponzi scheme </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:53:14 </td>
   <td style="text-align:left;"> $SPY who even wants to trade in this market when the bond market aint lining up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:52:41 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA 

Gas will cause massive drag on economy 7 dollars in LA , New York 8 per gallon , biggest rip-off’s in history . People don’t expect this but FED QT will cause big drag lower in stocks . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:52:37 </td>
   <td style="text-align:left;"> $SPY y&amp;#39;all knew those puts were dead as soon as you heard Brady was not retiring </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:52:33 </td>
   <td style="text-align:left;"> $SPY Everyone including their mother, father, sister and brother fomo today? Ready for rug pull tomorrow? Lol 😂 $AMC $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:52:25 </td>
   <td style="text-align:left;"> $SPY so help me god if they flatline this the next 3 days. I’d rather get completely annihilated on a pump, than be throat fucked by the theta cucks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:52:08 </td>
   <td style="text-align:left;"> $SPY Ingredients for October 2021 style grind higher..  🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:51:14 </td>
   <td style="text-align:left;"> $SPY $DWAC &amp;quot;It says here in my notes that you&amp;#39;re a woman of color, but we need to make sure,&amp;quot; said Senator Whitehouse solemnly. &amp;quot;Now—we can&amp;#39;t verify you&amp;#39;re a woman because no one knows what a woman is anymore, but we would be remiss if we didn&amp;#39;t at least verify your blackness.&amp;quot; 

https://babylonbee.com/news/senate-pulls-out-skin-color-chart-to-make-sure-ketanji-brown-is-black </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:50:55 </td>
   <td style="text-align:left;"> $SPY Just dump already you POS, stop hanging on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:50:48 </td>
   <td style="text-align:left;"> Economists expect elevated inflation as projected U.S. GDP plummets

https://newspress.com/economists-expect-elevated-inflation-as-projected-u-s-gdp-plummets/

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:50:37 </td>
   <td style="text-align:left;"> $SPY memes mooning in this environment was the short signal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:50:25 </td>
   <td style="text-align:left;"> $SPY this is fuckin unbelievable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:50:25 </td>
   <td style="text-align:left;"> $SPY  @LiLduckboi_realbruh Hey bro. I&amp;#39;m bearish too. Let&amp;#39;s dump this ponzi Thursday and retrace to 468. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:50:24 </td>
   <td style="text-align:left;"> $SPY  Dump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:50:15 </td>
   <td style="text-align:left;"> Will US inflation get worse if Russia defaults on its debt?

https://abcnews.go.com/Business/us-inflation-worse-russia-defaults-debt/story?id=83369860

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:50:14 </td>
   <td style="text-align:left;"> $SPY  btw don’t join my chat 💬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:50:13 </td>
   <td style="text-align:left;"> $SPY $GME new theory just in from my imagination. some massively short funds got margin called and it ran up the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:50:12 </td>
   <td style="text-align:left;"> $SPY Caution is warranted when &amp;quot;Meme&amp;quot; stocks are pushing, yields are inverting, and the tax rate increases are happening. US isn&amp;#39;t affected by Ukraine/Russia. This is a bail out rally.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:50:05 </td>
   <td style="text-align:left;"> $SPY Powell will say &amp;#39;economy is fine&amp;#39; 50 times now so spy can go another 10% :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:49:54 </td>
   <td style="text-align:left;"> $SPY Emergency rate hike tomorrow what r the chances? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:49:43 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F definitely makes sense why stonks are mooning 
rising yields means a growing economy… 👀😑 especially at this rate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:49:31 </td>
   <td style="text-align:left;"> $SPY $QQQ  10 yr at 2.41, bonds still selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:49:29 </td>
   <td style="text-align:left;"> $SPY  if you have kids then now you know why I have to trade so damn much 🤭😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:48:53 </td>
   <td style="text-align:left;"> $SPY 10 year steeper than a hooker on my cack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:48:49 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:48:45 </td>
   <td style="text-align:left;"> GME options: +2000% move today 
$TSLA options +600%  $QQQ $SPY $AAPL $BABA 
CLICK HERE to learn how to trade options profitably 
https://goldentrading.website/work-from-home-jobs-stock-trading-courses-for-beginners-learn-how-to-trade-stocks-and-make-1000-a-day-from-home/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:48:33 </td>
   <td style="text-align:left;"> $SPY cmon russia do something stupid....er </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:48:17 </td>
   <td style="text-align:left;"> $SPY rug pull coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:48:13 </td>
   <td style="text-align:left;"> $SPY it’s almost as if they didn’t learn from the first meme pump and dump. what a bunch of degenerates. ok, let’s do it again. it should turn out differently this time. everything to mo-ass! lfg! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:48:02 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m extremely fearful for these degenerate gambling addicts buying back into speculative nonsense like meme stocks and unprofitable companies.

I do believe we&amp;#39;re in Complacency stage and these Apes don&amp;#39;t care if market crash or we have worst recession or sideways lost decade market.

These people are going to get permanently wiped out and ruined indefinitely. Then r/WSB will cry about manipulation and try to Occupy Wallstreet v2 like we had in 2009. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:47:55 </td>
   <td style="text-align:left;"> $SPY Bulls don&amp;#39;t have a reason behind that rally, why would bear have a reason to drop? 
 
The market is irrational... simple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:47:41 </td>
   <td style="text-align:left;"> $Ba $ge $spy https://twitter.com/buzzpatterson/status/1506071174496735235?s=12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:47:38 </td>
   <td style="text-align:left;"> $SPY dear god, it’s me, Margaret. 

Any other poor soul forced to read that book in grade school? 
 
Anyways, Bears are fuqed tmrw! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:47:34 </td>
   <td style="text-align:left;"> $SPY 
SPY above $450.59 for a potential run up.
SPY below $448.39 for a potential drop.
#scalp
Watchlist 3/23/22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:47:20 </td>
   <td style="text-align:left;"> $SPY I drink light beer to stay hydrated that shit is water. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:47:08 </td>
   <td style="text-align:left;"> $SPY   the under $350  *limit down* gang where y&amp;#39;all at </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:46:56 </td>
   <td style="text-align:left;"> $SPY who thinks this will drop -25 points tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:46:27 </td>
   <td style="text-align:left;"> $SPY ohhh geeze grey goose was so 20s, costco might be ought </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:46:13 </td>
   <td style="text-align:left;"> $SPY Icahn: “Recession is coming and there’s no accountability in corporate American…”

Powell: “Recession is not coming. The same way he stated inflation is transitory…”

⬇️⬇️⬇️⬇️🔜🔜🔜🔜🔜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:45:47 </td>
   <td style="text-align:left;"> $SPY 454-460, put accumulation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:45:32 </td>
   <td style="text-align:left;"> $QQQ $SPY Judge for yourself. SPY from 15 Sep 2018 in blue and SPY from Jan 1st up until now. Both periods coincide with the FED talking about rate hikes. I have also added rate hikes on google trends in the comments. The difference is that last time the FED canceled it in December fearing a market crash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:45:19 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F sshhheeeesshhh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:45:13 </td>
   <td style="text-align:left;"> $SPY  Hope you got your moon suit on! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:45:00 </td>
   <td style="text-align:left;"> $SPY 🔥😏 Pig </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:44:55 </td>
   <td style="text-align:left;"> $SPY dear god, tomorrow is the day we see employment start trending up in future reports because every single bear will have no choice but to apply to Wendy’s after their accounts get annihilated. 

Come back around now y’all; next time you get enough money to play, pick the right side! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:44:32 </td>
   <td style="text-align:left;"> $SPY 454 on deck before this pulls back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:43:33 </td>
   <td style="text-align:left;"> $SPY  will go down as worse administration in history .  The liberal left will need a attitude adjustment . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:43:30 </td>
   <td style="text-align:left;"> $SPY what could Powell comment tomorrow morning that would make the markets tank 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:43:23 </td>
   <td style="text-align:left;"> $SPY bears hoping tonight is the night it tanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:43:08 </td>
   <td style="text-align:left;"> $SPY $QQQ “I got a feelin’ that tomorrow is gonna be a good red day, tomorrow is gonna be a red red day, I got a feelin’ yeah yeah” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:42:57 </td>
   <td style="text-align:left;"> $SPY oh noooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:42:37 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F 
https://m.theepochtimes.com/us-admiral-says-china-fully-militarized-islands_4349581.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:42:35 </td>
   <td style="text-align:left;"> $SPY futures not looking good for bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:42:32 </td>
   <td style="text-align:left;"> $SPY As bullish as I&amp;#39;ve obviously turned in my posts, the Vix has completed a 9-count buy signal and we had gluttonous buying of low quality stocks today on no merit. You know what that means. Short term dump on us euphoric retailers coming soon. Hope you didn&amp;#39;t hold your $6.45 buy on Tilray. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:42:31 </td>
   <td style="text-align:left;"> $SPY 10Y=3% by sunrise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:42:30 </td>
   <td style="text-align:left;"> $SPY Tomorrow is Wednesday….Powell Hour </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:42:00 </td>
   <td style="text-align:left;"> $SPY like my bros trying to get me to drink grey goose. Fck that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:42:00 </td>
   <td style="text-align:left;"> $SPY: The long term trend is still neutral, but the short term trend is positive. Better times ahead? https://www.chartmill.com/stock/quote/SPY/technical-analysis?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:41:51 </td>
   <td style="text-align:left;"> $SPY feeling good feelin fine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:41:25 </td>
   <td style="text-align:left;"> $SPY when you think you are in a bull market just zoom out a little and think again….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:41:10 </td>
   <td style="text-align:left;"> $SPY @rustystonkelford I feel like Thursday may be  the day amd tomorrow chops. 451 or 458 I&amp;#39;m yoloing my life in puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:41:01 </td>
   <td style="text-align:left;"> $SPY it was a face ripper rally but it&amp;#39;s still a bear market. This was a great gift to sell into IMO. I think this will be at 430 mid April </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:40:52 </td>
   <td style="text-align:left;"> $SPY can oil rally 40 bucks overnight please thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:40:51 </td>
   <td style="text-align:left;"> $SPY that pussy has to break above this resistance tonight, otherwise it will be rejected for sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:40:49 </td>
   <td style="text-align:left;"> $SPY so the monkeys are “back” huh lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:40:48 </td>
   <td style="text-align:left;"> $SPY i.might be premature , won&amp;#39;t be the first time.. but </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:40:44 </td>
   <td style="text-align:left;"> $SPY anyone know some good manganese stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:40:33 </td>
   <td style="text-align:left;"> $SPY wen R/S? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:40:27 </td>
   <td style="text-align:left;"> $SPY man I hate clear liquor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:40:25 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F 
I still can’t believe the degenerate bull was the winning outcome 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:40:25 </td>
   <td style="text-align:left;"> $SPY Lol looks awfully similar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:40:15 </td>
   <td style="text-align:left;"> $SPY going to skyrocket tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:40:11 </td>
   <td style="text-align:left;"> $SPY wen 5OO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:39:59 </td>
   <td style="text-align:left;"> $SPY money flow bottomed on 15 min … PAMP it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:39:55 </td>
   <td style="text-align:left;"> $SPY 

If a “guru” tells you this market is difficult for day traders, they are absolutely “clueless”
If anything this is the best market we are in for making daily consistent profits! 🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:39:27 </td>
   <td style="text-align:left;"> $SPY my cheeseburger meal costs $7 now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:39:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $SQQQ $TQQQ View 2 of 2, daily chart. The blue line was the projection I posted this past weekend, now expecting a high of $457 this week. Support at $446 tomorrow. I’m still very bearish on the macro but this chart don’t give a fuck about that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:39:12 </td>
   <td style="text-align:left;"> $SPY $480 ez tomorrow. Amirite bulls😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:39:07 </td>
   <td style="text-align:left;"> $SPY $BTC.X fed talks digital currency world tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:39:05 </td>
   <td style="text-align:left;"> $SPY it want drop very much </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:39:01 </td>
   <td style="text-align:left;"> $SPY either this or bonds gotta give </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:38:32 </td>
   <td style="text-align:left;"> $SPY Powell is merely having a discussion with a panel of international banks. He’s not even going to be speaking about rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:38:27 </td>
   <td style="text-align:left;"> $SPY $NDX $DJIA - MARKET CRASH COMING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:38:27 </td>
   <td style="text-align:left;"> $SPY 10Y got a boner like me at 6am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:38:14 </td>
   <td style="text-align:left;"> $SPY 10 year T-Bond yield at 2.399% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:38:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $UVXY - The 5YR (as of now) vs 10YR has inverted. The 2YR isn&amp;#39;t far behind. It&amp;#39;s a bit shocking how yields are moving all to a measly 25 basis point hike. So, what&amp;#39;ll happen if Powell bumps 50 basis points? This summer isn&amp;#39;t looking great thus far. Short term there is some positivity in the markets, but, it&amp;#39;s nothing more than the rally of early February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:38:02 </td>
   <td style="text-align:left;"> $GME $SPY $BBBY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:38:00 </td>
   <td style="text-align:left;"> $SPY Day 25 - Zelensky still a...  
 
Novel peace prize 
$20 billion of taxpayers money from Merica  
Has no chance to win this 
Upsetting Isreal by not being a team player  
Complicit in destroying global supply chains,   
 
Oh and still is a Failed comedian/ actor now turned Marvel character for Biden sun Hunter 🌞   🤷‍♂️🙃🚮🚨 $QQQ $XLF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:37:53 </td>
   <td style="text-align:left;"> $SPY like this if your gonna short amc if it goes any higher 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:37:52 </td>
   <td style="text-align:left;"> $SPY &amp;quot;It&amp;#39;s easier to be irresponsible when your Commie&amp;quot;.  
 The Thing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:37:52 </td>
   <td style="text-align:left;"> $SPY Looks similar and bearish divergence is forming again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:37:51 </td>
   <td style="text-align:left;"> $SPY limit up is in play tomorrow 539 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:37:36 </td>
   <td style="text-align:left;"> $SPY @PeteinSD Hey dude that one chart where you said you wouldn&amp;#39;t be bearish until it looks like that chart. Kinda looks like that chart. This is probably out of context but this is 5 months ago lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:37:11 </td>
   <td style="text-align:left;"> $SPY stupid pigs are about to get baconized </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:37:07 </td>
   <td style="text-align:left;"> $AMZN $GOOGL $SPY $QQQ Actual footage of BEAR minded people, waiting on that pullback Versus getting MONEY on the rips... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:36:48 </td>
   <td style="text-align:left;"> $SPY oscillator at +85…bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:36:48 </td>
   <td style="text-align:left;"> $SPY BEars thought 4500 was resistance now it becomes support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:36:45 </td>
   <td style="text-align:left;"> $SPY $DWAC This large bill is designed to withstand soaring inflation rates for the foreseeable future.

“Inflation has been a real problem for hard-working Americans. At the treasury, we print money every day to try and make it go away but our printers can only go so fast,&amp;quot; said Jerome.

&amp;quot;Look at me on this money,&amp;quot; said President Biden. &amp;quot;You can see my face. Amazing. I did that!&amp;quot;

&amp;quot;Anyways,&amp;quot; he said after an excruciating pause. &amp;quot;Look, here&amp;#39;s the deal, Jack. This trillion-million-hundo dollar is going to save our country. Americans can&amp;#39;t afford to put food on the table but this currency will change all that. Now you can afford bananas!&amp;quot;

&amp;quot;President Harris tells me that money can be used to trade for goods and services,&amp;quot; he added.

Dr. Jill Biden quickly pulled her husband away from the microphone, a skill she has almost perfected.

At publishing time, the nation plunged deeper into debt after Biden lost a bill between his couch cushions.

https://babylonbee.com/news/biden-to-get-face-on-new-trillion-dollar-bill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:36:42 </td>
   <td style="text-align:left;"> $SPY tomorrow morning looks very bearish….whata you bear think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:36:38 </td>
   <td style="text-align:left;"> $SPY bears about to get nuked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:36:32 </td>
   <td style="text-align:left;"> $SPY futes flatting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:35:49 </td>
   <td style="text-align:left;"> $SPY future&amp;#39;s down, oh boi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:35:46 </td>
   <td style="text-align:left;"> $SPY I legit feel terrible for my bear frenz. Guys you getting murdered this week. I think it’s called a genocide Lmfao. .. anything red on ES before midnight is super bullish. FED algo kicks in around midnight… it’s a replay of yesterday and everyday last week starting Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:35:37 </td>
   <td style="text-align:left;"> $SPY tell bri nobody cares im watching ja </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:35:12 </td>
   <td style="text-align:left;"> $SPY fairly slightly extended but gap should be filled by morning $QQQ A large extension which may see some pull back in tech early on. $VI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:35:02 </td>
   <td style="text-align:left;"> $SPY Especially as we approach 451 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:34:39 </td>
   <td style="text-align:left;"> $SPY Bears are now all excited about 50 points FUD.  Bullard barking again since he is loosing on his puts but his boss will put him in place again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:34:36 </td>
   <td style="text-align:left;"> $SPY Very fucking bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:34:25 </td>
   <td style="text-align:left;"> $SPY Wardemiclafation 3 ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:34:21 </td>
   <td style="text-align:left;"> $SPY where do you think most $$$ will go when this goes down again? Bonds, Gold? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:34:19 </td>
   <td style="text-align:left;"> $SPY when I say Rug, you say Pull…
RUG! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:34:09 </td>
   <td style="text-align:left;"> $SPY  
 
Green bars, tho 
 
https://youtu.be/dn3j6-yQKWQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:33:58 </td>
   <td style="text-align:left;"> Trade ideas and live stream unlocked 💯🚀 thank you guys for your support #PRESSIT  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:33:38 </td>
   <td style="text-align:left;"> $AMC $GME WSB back? Lol 😂 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:33:35 </td>
   <td style="text-align:left;"> $SPY ES 4520 is saying hell no </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:33:30 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:33:08 </td>
   <td style="text-align:left;"> $SPY Futures  blood red… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:33:07 </td>
   <td style="text-align:left;"> $SPY &amp;quot;Among the shortages that have persisted since last year, the worldwide paper shortage has made a significant impact. Businesses and consumers around the world have been shifting to digital documentation in recent years, but paper is still a major necessity for operations. Why is there a paper shortage, and is there an end in sight?&amp;quot; 
Powell printer knows the answer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:32:59 </td>
   <td style="text-align:left;"> $SPY Rip bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:32:55 </td>
   <td style="text-align:left;"> $SPY HEHE? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:32:52 </td>
   <td style="text-align:left;"> $SPY we will get -.001% tomorrow so bulls can say bears had a red day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:32:51 </td>
   <td style="text-align:left;"> $SPY saudi Arabia – perpetrator of bombing, famine and genocide in Yemen, weaponized by U.S., UK and EU – is advancing the coming of the petroyuan. 
 
India – third largest importer of oil in the world – is about to sign a mega-contract to buy oil from Russia with a huge discount and using a ruble-rupee mechanism. 
 
Tthe days of the American petro-dollar are numbered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:32:48 </td>
   <td style="text-align:left;"> $SPY How did American liberals evolve from being anti-war and pro-environment to ultra pro-transgender, pro-government tyranny, pro-military industrial complex, pro-medical tyranny, etc.?  Are they all a bunch of brain-dead morons in a state of hypnosis? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:32:30 </td>
   <td style="text-align:left;"> $SPY Last time I front loaded something I found out I was gonna be a daddy 2 months later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:32:23 </td>
   <td style="text-align:left;"> $SPY we waiting for our friend powell to whisper sweet nothings into our ears tomorrow ..we love you papa J </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:32:13 </td>
   <td style="text-align:left;"> $SPY NIKKEI will drop like 75% this year guaranfuckinteed dying population negative growth Kuroda ponzi scheme will blow up as will China, US, all make-believe markets backed by horse ass excrement, if they would at least print real money but they just generate digits 10010000101010101010000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:32:08 </td>
   <td style="text-align:left;"> $SPY SPY 2022-03-22 Chart Analysis Video: 
https://www.youtube.com/watch?v=gSimK9F2pEE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:31:56 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F 
Its difficult to live in a world where everyone is right. 
Bears are right 
Bulls are right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:31:52 </td>
   <td style="text-align:left;"> $SPY the homie moon looking crusty. Slaughtered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:31:51 </td>
   <td style="text-align:left;"> $tlt $spy the time has come for bond yields to break their epic multi decade channel $vix </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:31:46 </td>
   <td style="text-align:left;"> $SPY Carl Icahn starting to agree with many of us. So much to lose, and so little to gain, by being bullish at these levels. https://twitter.com/trader_winter/status/1506423524172316672?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:30:51 </td>
   <td style="text-align:left;"> $SPY 25bps rate hike ain&amp;#39;t gonna solve anything, heck even 50bps won&amp;#39;t cut it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:30:44 </td>
   <td style="text-align:left;"> $SPY this is mentally exhausting and tiring but somehow we always see each other 9:30 sharp daily is it? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:30:25 </td>
   <td style="text-align:left;"> $SPY if powell does emergency rate hike this is going to 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:30:23 </td>
   <td style="text-align:left;"> $ASAN usually not a good sign when $SPY and $QQQ absolutely rip green all day and this stock ends red. Just saying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:30:20 </td>
   <td style="text-align:left;"> $SPY i swear if futes turn red imma be a bear with calls tomorrow and i dont want thatc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:30:10 </td>
   <td style="text-align:left;"> $SPY $SQQQ $QQQ $TQQQ View 1 of 2, 4 hr chart. Looks to be heading to the middle blue line using the middle yellow line for support over the next 2 weeks. In this chart they intersect at $466. After that I expect the downtrend to resume. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:29:57 </td>
   <td style="text-align:left;"> $DWAC $spy I&amp;#39;ve seen some internet chatter about Biden using the Patriot Act to unlawfully detain his political rivals. First of all they would have to be charged with terrorist planning or Acts .. anywho ..The thing about conspiracy theorist is they&amp;#39;re usually ignorant to the facts on the ground. Patriot Act has expired.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:29:48 </td>
   <td style="text-align:left;"> $SPY Powell surprise .50 hike
Tomorrow, clearly the market can handle it, prob limit circuit breaker up to 480 on the news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:29:41 </td>
   <td style="text-align:left;"> $SPY money everywhere. Fuck the Fed. The people run this shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:29:25 </td>
   <td style="text-align:left;"> $SPY keep an eye on futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:29:16 </td>
   <td style="text-align:left;"> Good ol days when we had to do DD on companies and  then get PR stocks run. 
 $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:29:13 </td>
   <td style="text-align:left;"> $SPY guys 500 by the EOM .. not by the summer… y’all need to dumb up your game! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:29:11 </td>
   <td style="text-align:left;"> $SPY Large American military presence on Ukraine border in Poland….FOX… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:28:55 </td>
   <td style="text-align:left;"> $SPY $445 Put expires tomorrow, and the other $445 Put expires Friday.

SPY has not had 7+ green days in a row in the last 365 days.

One or both these Puts going to print.

Unless SPY has 10 green days in a row and closes green on a Friday before the weekend with a war ongoing.

We&amp;#39;re gonna find out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:28:52 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:28:23 </td>
   <td style="text-align:left;"> $SPY Ten year treasury went from 1.67% on March 7th to 2.4% right now. Up 44% in 2 weeks...everything is fine here...there is nothing to worry about. uhhhh...sure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:28:21 </td>
   <td style="text-align:left;"> $SPY Why am I getting October 2021 vibes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:28:19 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:28:10 </td>
   <td style="text-align:left;"> $SPY I told you the Fed was doing the right thing in 2020 and the fat is doing the right thing in 2022

You’re still at the lows of the year losers, you missed the 415 only last week five trading days ago.. Buy it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:28:00 </td>
   <td style="text-align:left;"> $SPY Margin calls are already happening.  SPY to $458 and it&amp;#39;s gonna get squeezy everywhere.  Shorts are in trouble.  $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:28:00 </td>
   <td style="text-align:left;"> $SPY futures were -3% at one point last night so as a bear I don’t feel confident unless futures get to -1% tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:27:50 </td>
   <td style="text-align:left;"> $SPY when we heard about covid for the first time, WS crooks pumped markets to new highs. Same now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:27:39 </td>
   <td style="text-align:left;"> $SPY  
 
Remember when you thought </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:27:37 </td>
   <td style="text-align:left;"> $SPY looks good but they probably cna only. Make 25 a year amirite or amirite </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:26:58 </td>
   <td style="text-align:left;"> $SPY nikkei with its giant friggin gaps in its daily chart, totally natural and organic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:26:57 </td>
   <td style="text-align:left;"> $SPY $500 by summer, the market will turn when the bears get margin calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:26:44 </td>
   <td style="text-align:left;"> $SPY the rent isn’t going to get paid with red futures rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:26:29 </td>
   <td style="text-align:left;"> $SPY feeling good feeling fine..buying moar tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:26:22 </td>
   <td style="text-align:left;"> $SPY remember when this was going down and the only posts you read were people complaining about how shitty the market is? 😂😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:26:08 </td>
   <td style="text-align:left;"> $SPY junk over bought but the meme stocks running might push this higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:26:08 </td>
   <td style="text-align:left;"> $SPY Not much support here. Could easily see 447 or lower at the open tomorrow with no news or just a little bump higher in oil prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:26:07 </td>
   <td style="text-align:left;"> $SPY for the record Mt Lil snack puts are toast @LiLduckboi_realbruh unless we open at 447 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:26:02 </td>
   <td style="text-align:left;"> $SPY never ever ever listen to the losers here they missed the bottom in 2020 and they missed the bottom this year at around $415 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:25:37 </td>
   <td style="text-align:left;"> $SPY remember when you thought the FED wasn’t a political tool? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:24:56 </td>
   <td style="text-align:left;"> $SPY they sold you a bridge bulls… it leads to a pit of hell and your bridge isn’t long enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:24:14 </td>
   <td style="text-align:left;"> $SPY bought a butt plug and I still feel like I have to poop, rip off of a product imho $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:24:03 </td>
   <td style="text-align:left;"> $spy $tlt

Time to phase out gov debt as an investable asset class. Millennials certainly don’t want that trash. FIAT endgame. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:24:02 </td>
   <td style="text-align:left;"> $SPY they made my homie moo a hamburger today 😔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:23:53 </td>
   <td style="text-align:left;"> $SPY data and charts ect ect ect ....lmfao

Count on this 👏 🙌 💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:23:53 </td>
   <td style="text-align:left;"> $SPY guys the apes have taken over .. the printer is going to go nuts! Watch the insanity unfold! Close your puts and load calls first thing tomorrow.. same fuking message I posted yesterday and today jeezus christos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:23:50 </td>
   <td style="text-align:left;"> $SPY overbought </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:23:42 </td>
   <td style="text-align:left;"> $SPY shooting star is bullish😂🩸🪓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:23:29 </td>
   <td style="text-align:left;"> $SPY what a run. The next few months is going to be interesting. The fed did say no more easy money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:23:28 </td>
   <td style="text-align:left;"> $Spy well at least this time they filled all the micro gaps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:23:25 </td>
   <td style="text-align:left;"> $SPY if you didn’t yeet into meme stock calls today you ain’t black </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-23 08:23:24 </td>
   <td style="text-align:left;"> $SPY rug pull on any war news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 09:10:19 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ when I open up my trading app after a long day. A long red day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 09:09:58 </td>
   <td style="text-align:left;"> $QQQ MMs can only deny Fundamental economics for so long. Run it up again, and I’ll just by more for a greater gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 09:09:20 </td>
   <td style="text-align:left;"> $QQQ Does anyone have a legitimate bull case that actually supports these rallies? 
 
Or do we all just agree this is the parabolic topping phase of the market before we have a long term top lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 09:09:13 </td>
   <td style="text-align:left;"> $SPY $DWAC $QQQ  
 
If Joe Biden got 81m votes and has 56% disapproval rating that means around 10m Americans will vote for GOP that voted for Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 09:09:00 </td>
   <td style="text-align:left;"> In the last month $QQQ has a been trading in the 317.45 - 357.85 range, which is quite wide. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 09:08:19 </td>
   <td style="text-align:left;"> $QQQ if you were born after 1982 you&amp;#39;ve never seen 18% mortgage rates... Don&amp;#39;t worry, they&amp;#39;re coming back. Enjoy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 09:07:37 </td>
   <td style="text-align:left;"> $QQQ futures and stock market movement the next day have not been in sync at all. Don’t become happy or sad looking at futures. Not worth it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 09:04:14 </td>
   <td style="text-align:left;"> $SPY $QQQ  
Are we really surprised they all fell for the plandemic? . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 09:03:58 </td>
   <td style="text-align:left;"> $QQQ when the market is back MEMEing you know they think the Feds is a joke, I really don’t blame bulls tho. The fed has been behind this situation for a long time now and they still behind and wanna raise .25. Why are they gonna keep waiting and waiting when employment been at target and they just not gonna address price stability. The Feds really have one job and that’s control prices, they can’t really control the job market. That’s just a function of the economy. They can always control inflation tho. At this point no matter what they do the Feds are fucked $spy $dia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 09:02:31 </td>
   <td style="text-align:left;"> $QQQ Futes starting to bleed nicely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:59:23 </td>
   <td style="text-align:left;"> $DWAC $SPY $QQQ  
 
Covid is still here and democrats want to drop mask mandates 
 
Don&amp;#39;t they care about Americans??? What about the science?!?!?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:58:09 </td>
   <td style="text-align:left;"> $SPY $QQQ change my mind you should join 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:57:40 </td>
   <td style="text-align:left;"> $QQQ $8.54 Trillion on the balance sheet as of 3/16/22. This Thursday the fed will post their balance sheet again

Let’s see how much it gets reduced </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:56:38 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $NDX $DIA 

The dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:56:36 </td>
   <td style="text-align:left;"> $QQQ $SPY and the 10 Yr continues… my question is are these just gonna keep going up when the 10 Yr finally decides to pullback? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:56:18 </td>
   <td style="text-align:left;"> $QQQ $SPY Nikkei up 2%...Q&amp;#39;s/SPY going to rip so hard tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:56:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA Which one of you lost the most and who gained the most today? Retail traders only </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:55:11 </td>
   <td style="text-align:left;"> $SPY $QQQ  CLINTON TESTS POSITIVE FOR COVID-19 -AXIOS

covid doesn’t stand a chance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:54:15 </td>
   <td style="text-align:left;"> $QQQ How long can these criminals sustain the run!? 🤬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:53:20 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ 

Pump and dump Ponzi scheme </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:52:41 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA 

Gas will cause massive drag on economy 7 dollars in LA , New York 8 per gallon , biggest rip-off’s in history . People don’t expect this but FED QT will cause big drag lower in stocks . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:50:48 </td>
   <td style="text-align:left;"> Economists expect elevated inflation as projected U.S. GDP plummets

https://newspress.com/economists-expect-elevated-inflation-as-projected-u-s-gdp-plummets/

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:50:33 </td>
   <td style="text-align:left;"> $QQQ 
QQQ above $357.81 for a potential run up.
QQQ below $355.38 for a potential drop.
#scalp
Watchlist 3/23/22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:50:15 </td>
   <td style="text-align:left;"> Will US inflation get worse if Russia defaults on its debt?

https://abcnews.go.com/Business/us-inflation-worse-russia-defaults-debt/story?id=83369860

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:49:31 </td>
   <td style="text-align:left;"> $SPY $QQQ  10 yr at 2.41, bonds still selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:48:45 </td>
   <td style="text-align:left;"> GME options: +2000% move today 
$TSLA options +600%  $QQQ $SPY $AAPL $BABA 
CLICK HERE to learn how to trade options profitably 
https://goldentrading.website/work-from-home-jobs-stock-trading-courses-for-beginners-learn-how-to-trade-stocks-and-make-1000-a-day-from-home/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:47:01 </td>
   <td style="text-align:left;"> $amc $gme $qqq $tsla $btc.x https://www.youtube.com/watch?v=TDnkmlk8ngo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:46:08 </td>
   <td style="text-align:left;"> $QQQ 10 yr 🚀 🌝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:45:32 </td>
   <td style="text-align:left;"> $QQQ $SPY Judge for yourself. SPY from 15 Sep 2018 in blue and SPY from Jan 1st up until now. Both periods coincide with the FED talking about rate hikes. I have also added rate hikes on google trends in the comments. The difference is that last time the FED canceled it in December fearing a market crash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:43:08 </td>
   <td style="text-align:left;"> $SPY $QQQ “I got a feelin’ that tomorrow is gonna be a good red day, tomorrow is gonna be a red red day, I got a feelin’ yeah yeah” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:41:25 </td>
   <td style="text-align:left;"> $QQQ go ck put/call vol, oi ratio.  chop chop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:40:11 </td>
   <td style="text-align:left;"> $GME An institution/(s) will lose their GME shares tomorrow and will not be able to recover them if this stock doesn&amp;#39;t go under 120 by 4/14/22 (pic in tweet). 
 
They never learn... 
 
https://twitter.com/MeisaBonelli/status/1506429920003641344?s=20&amp;amp;t=n6qbIZHsLndjPcgq6grWLA 
 
$TSLA $QQQ $AMC $MULN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:39:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $SQQQ $TQQQ View 2 of 2, daily chart. The blue line was the projection I posted this past weekend, now expecting a high of $457 this week. Support at $446 tomorrow. I’m still very bearish on the macro but this chart don’t give a fuck about that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:38:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $UVXY - The 5YR (as of now) vs 10YR has inverted. The 2YR isn&amp;#39;t far behind. It&amp;#39;s a bit shocking how yields are moving all to a measly 25 basis point hike. So, what&amp;#39;ll happen if Powell bumps 50 basis points? This summer isn&amp;#39;t looking great thus far. Short term there is some positivity in the markets, but, it&amp;#39;s nothing more than the rally of early February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:38:00 </td>
   <td style="text-align:left;"> $SPY Day 25 - Zelensky still a...  
 
Novel peace prize 
$20 billion of taxpayers money from Merica  
Has no chance to win this 
Upsetting Isreal by not being a team player  
Complicit in destroying global supply chains,   
 
Oh and still is a Failed comedian/ actor now turned Marvel character for Biden sun Hunter 🌞   🤷‍♂️🙃🚮🚨 $QQQ $XLF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:37:07 </td>
   <td style="text-align:left;"> $AMZN $GOOGL $SPY $QQQ Actual footage of BEAR minded people, waiting on that pullback Versus getting MONEY on the rips... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:36:00 </td>
   <td style="text-align:left;"> $QQQ way overbought. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:35:12 </td>
   <td style="text-align:left;"> $SPY fairly slightly extended but gap should be filled by morning $QQQ A large extension which may see some pull back in tech early on. $VI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:32:14 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-03-22 Chart Analysis Video: 
https://www.youtube.com/watch?v=W55KGAo0m5o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:30:26 </td>
   <td style="text-align:left;"> $SQQQ Well, damn...  down 3% over-all on the day.   Up 13% YTD, but still.  How I see it, if we hold $35, great, if not, it seems like there is quite a bit of air down to below $31.00.  Conversely, looks like $464 is resistance in the $QQQ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:30:23 </td>
   <td style="text-align:left;"> $ASAN usually not a good sign when $SPY and $QQQ absolutely rip green all day and this stock ends red. Just saying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:30:10 </td>
   <td style="text-align:left;"> $SPY $SQQQ $QQQ $TQQQ View 1 of 2, 4 hr chart. Looks to be heading to the middle blue line using the middle yellow line for support over the next 2 weeks. In this chart they intersect at $466. After that I expect the downtrend to resume. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:29:16 </td>
   <td style="text-align:left;"> Good ol days when we had to do DD on companies and  then get PR stocks run. 
 $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:25:21 </td>
   <td style="text-align:left;"> $QQQ Lol this steaming pile of shit is bleeding in the futes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:24:21 </td>
   <td style="text-align:left;"> $QQQ my Call Spread is killing it🤑🤑🤑🤑, IMHO we should see a really until the beginning of April, I’m looking at 90 to 95 % of gain. Look my Bio for entry✌🏻✌🏻✌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:23:02 </td>
   <td style="text-align:left;"> $QQQ this chart, a screenshot from the first week of February points to a likelihood direction for this index tomorrow considering multiple factors. Let&amp;#39;s see how it actually turns out. My prediction, below $354 by close and a touch near $350 more likely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:21:46 </td>
   <td style="text-align:left;"> $QQQ waiting for one last dip after this rally. Then depending if it finds a base I’ll turn bullish. Short term bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:21:25 </td>
   <td style="text-align:left;"> $SPY $QQQ

Betting on continuation of this crackhead energy is not wise. YMMV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:20:17 </td>
   <td style="text-align:left;"> $QQQ If you have started mining Pi crypto on your phone, you could really be missing out.  Try it out, its free!  
 
 minepi.com/KingBootz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:19:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA  https://youtu.be/-2Era4FZ_Gc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:19:34 </td>
   <td style="text-align:left;"> $SPY $QQQ

look at the stuff that is pumping and then tell me retail is not being baited to dump more money into this shit.

Yep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:19:18 </td>
   <td style="text-align:left;"> The Anti Plunge Protection Team in Asia is manipulating crypto and memes. Covid + Market Psyop almost fully complete. New world order soon. 🤣😂 $SPY $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:16:44 </td>
   <td style="text-align:left;"> $QQQ Holdings - Upside from recent lows 
 
Chinese ADRs flying on indications of stability measures applied by the China&amp;#39;s financial stability and development committee/Alibaba&amp;#39;s big share buyback program boosting Chinese stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:15:54 </td>
   <td style="text-align:left;"> $QQQ $SPY majority of traders and analyst still seem to be doubting this rally which seems like more fuel for the fire. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:15:24 </td>
   <td style="text-align:left;"> $SPY $QQQ Powell at 8am…hopefully😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:15:04 </td>
   <td style="text-align:left;"> $QQQ Market clearly thinks Powell is a joke - will he change that tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:12:17 </td>
   <td style="text-align:left;"> $QQQ Up 10-20% the rest of the week or 20-30% ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:11:37 </td>
   <td style="text-align:left;"> $SPY $QQQ it has begun. 401 SPY golden cross fail.  see vix daily. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:10:57 </td>
   <td style="text-align:left;"> Listen, honestly, ask ANY business person and they will tell you business is the strongest it’s ever been - yes their are supply chain challenges but the demand is just crazy!!!! Expnomy can handle highest rates not seen in generations no problem!!! Economy so strong fed has to try and slow it!!’ These are GOOD PROBLEMS no the BEST PROBLEMS to have!!!! 
 
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:08:38 </td>
   <td style="text-align:left;"> $NASDAQ $QQQ 

Geometrics are so much fun. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:08:13 </td>
   <td style="text-align:left;"> $QQQ adbe should help with the puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:06:11 </td>
   <td style="text-align:left;"> $QQQ Why do people think QQQ is a Bubble but $BRK.B is conservative and should outperform QQQ. I don’t get it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:03:32 </td>
   <td style="text-align:left;"> $LMT  $NOC $SPY  $QQQ  $SQQQ  
 
With the time adjustment for Brussels, hope Prez Joe doesn&amp;#39;t nod off with head against the big red button. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:01:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK As mentioned previously, good luck trying to trade these markets. Lots of hedges were put back on yesterday, after getting destroyed last week. Now they’ve been crunched again. If you’re carbon-based, you don’t have an edge, none. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:01:02 </td>
   <td style="text-align:left;"> $QQQ bought puts for Monday hmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 08:00:21 </td>
   <td style="text-align:left;"> $QQQ Nasdaq 100 ETF has big day +2% while breaking above 50-day MA.  200-day next?  #IBDpartner  
 
@InvestorsBusinessDaily @MarketSmith </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:59:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN so many put gamblers driving stocks up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:55:11 </td>
   <td style="text-align:left;"> $QQQ $SPY

So will you be upset if the portfolio I posted as -9% today actually advances to a 200% gain from the baseline trade level in the next month? Probably </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:52:50 </td>
   <td style="text-align:left;"> $QQQ hoping for a leg dow tomorrow.. 🤞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:49:57 </td>
   <td style="text-align:left;"> $QQQ not sure how this going to go. Confident the market is overbought but timing euphoria is difficult. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:48:59 </td>
   <td style="text-align:left;"> $QQQ chart turning bullish with reversal up through the 20 and 50dma.  RSI and MACD positive. Targeting $365 to $389 area... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:47:54 </td>
   <td style="text-align:left;"> $QQQ $SPY 

I&amp;#39;m just posting this to screenshot later and mock bulls for being gullible probably repost it several times w different memes and gifs.

I really hope they don&amp;#39;t lose so much that they quit trading and leave twits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:47:27 </td>
   <td style="text-align:left;"> $QQQ we might have finally found a bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:46:28 </td>
   <td style="text-align:left;"> $SPY - $TSLA Merica the Bootyful! 💀🙋‍♂️ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:44:39 </td>
   <td style="text-align:left;"> $SPY The Gaines on put contracts we have collected  over the last few days far will exceed and outperform the calls you bought recently.    $QQQ $SPX $ES_F $NDX  

🧞‍♂️💎💎💎💎💎💎💎💎💎💎💎🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:44:16 </td>
   <td style="text-align:left;"> $QQQ last time interest rates were raised the market went on to be up 30% on the year. Recession is looming but im bullish in the short term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:42:17 </td>
   <td style="text-align:left;"> $QQQ - J Powell makes a surprise 25 bp rate hike tomorrow 😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:39:34 </td>
   <td style="text-align:left;"> $SPY I tell ya it was t easy to survive 

But we did it guys $QQQ $DIA $SPX   💎 

Diamond hand </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:37:16 </td>
   <td style="text-align:left;"> I don&amp;#39;t chase the Markets when they either Rally or Plunge-- I follow my STRAT

This Week I excluded myself from placing a Trade so I missed the rally.

Can&amp;#39;t force a Trade if I didn&amp;#39;t see any

Broke my STRAT last Week, so here I am, with no plan for this Week.

But I am working on a Trade for the upcoming Weeks. 

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:35:31 </td>
   <td style="text-align:left;"> $QQQ Well, I will wait.. holding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:33:02 </td>
   <td style="text-align:left;"> $QQQ no down ticks, just straight to $500 from here.  Your lord and savior nancy pelosi has spoken. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:32:20 </td>
   <td style="text-align:left;"> $qqq $SPY the resemblance to q4 2018 is remarkable. Stay tuned, I will post some DD soon. I expect at most one more green day and then a big drop or a big drop starting as early as tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:31:59 </td>
   <td style="text-align:left;"> $SPY   $4005 

. $DIA $DJIA $NASDAQ $QQQ   

Calling Top’s.   It’s over bought.    Haha   🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:30:19 </td>
   <td style="text-align:left;"> $QQQ $SPY 

They try to cut me down
When they say I&amp;#39;m too low (turn me up)
I said turn me up, I cannot hear my flow (whoa)

Does Jerome Powell just bump uzi all day? Holy shit. Uzi understands that liquidity issue </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:28:38 </td>
   <td style="text-align:left;"> $QQQ $SPY Ukraine is castrating the Russian prisoners! This is very bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:28:30 </td>
   <td style="text-align:left;"> $SPY  $SPX  $QQQ   It’s. A.  Top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:28:24 </td>
   <td style="text-align:left;"> $AMC $TLRY $QQQ The bull is back and you know it or maybe you don&amp;#39;t.  
 Could be temporary but who cares now, the money has been made.  Maybe you saw the signals 2 weeks ago and the confirmation of those signs on Wednesday. When you have been trading long enough you see the subtle changes in the market environment.  When those subtleties are  accompanied  by VWAP validation it&amp;#39;s an impossible setup to ignore and profit from.  At this moment you are witnessing something you see when the Bull is back.  Aftermarket buying with plenty of liquidity has been absent for months, its back for the last 5 days.   $AMC $TLRY been awful to own but a few sessions like today and this aftermarket makes up for months if not years of loss.  Investing is dead. Trade for the day, win the day and live forever.   Why own when you do better with no overnight risk? #liquidandlovingit    Join us and prosper or get caught up in the next bubble or worse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:28:16 </td>
   <td style="text-align:left;"> $SPY $QQQ This move does not seem to care about resistances. May be this one is different? We have the upper trendline of the channel coinciding with the resistance at 4595 (see pic). We will probably get  a pullback to 4380 at the end of the week, then a push up resulting either in the yellow move or the red one (see pic). IMO the yellow move has more chances, because I am bullish long term.  
Raised some cash, hedged the remaining positions, hope for the best. GL. 
 
https://www.tradingview.com/x/RWLABLJ7/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:26:58 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
8% inflation 
 
0.25% interest rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:23:11 </td>
   <td style="text-align:left;"> $SPY I don’t want to hear about $3800 again 

$spx $qqq $ndx LIMIT THIS DOWN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:22:03 </td>
   <td style="text-align:left;"> $AAPL Just be careful this week my friends, Wall Is pushing things that can suck in Retail but we are set up for them to run &amp;amp; sell so stay alert &amp;amp; dont chase  
 
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:21:23 </td>
   <td style="text-align:left;"> $NQ_F $QQQ that does not look bearish at all and with the amount of chart patterns setting up underneath i think we blow right through the 200SMA, as well as, this would be our third attempt at it since this chaos began. Pivot 15065 in the 4hour chart above (daily 200SMA at 15106. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:18:02 </td>
   <td style="text-align:left;"> Daily Market Recap for Tuesday 3/22/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/ncL-c8v3PQQ

$SPY $QQQ $IWM $TLT $UUP

Included is the bond trade update </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:17:34 </td>
   <td style="text-align:left;"> $spy $qqq $cqqq $tsla $arkk https://www.youtube.com/watch?v=xAAeLHUWyMk&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:15:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $DWAC HUNTER BIDENS LAPTOP IS REAL. THE BIDENS ARE SUPPORTING UKRAINE TO COVER UP THE BURISMA DIRT ON THE BIDEN FAMILY AND DEMOCRAT PARTY. DONT LET THIS MONUMENTAL STORY GET BURIED LIKE THEY WANT: 

https://www.nytimes.com/2022/03/16/us/politics/hunter-biden-tax-bill-investigation.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:15:04 </td>
   <td style="text-align:left;"> $QQQ if wage is not further increase, it’s impossible for companies to transfer the burden to consumers… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:14:53 </td>
   <td style="text-align:left;"> $QQQ October low all I care about at moment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:13:52 </td>
   <td style="text-align:left;"> $SPY $QQQ fed officials are trying to throw cold water on all markets and the economy with rhetoric to no avail so far. Let&amp;#39;s see if he gets even more hawkish tomorrow.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:13:27 </td>
   <td style="text-align:left;"> $QQQ $SPY

LOL apparently this is the person or one of them those AMC people are all against. Personally I think they are adorable. I’d let them leverage short my own portfolio no problem 🤣

Anyway, hope those futes are ripping or whatever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:12:57 </td>
   <td style="text-align:left;"> $SPY $QQQ getting tight. Real nice and snug. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:11:53 </td>
   <td style="text-align:left;"> $SPY $QQQ all we need now for the time travel machine back to 2021 is for Elon to tweet #STONKS $GME $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:11:47 </td>
   <td style="text-align:left;"> Keeping it simple … mostly how I have leaned to invest over the decades … finally 

$qqq $spy  https://avc.com/2022/03/keeping-it-simple/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:11:23 </td>
   <td style="text-align:left;"> $QQQ The amount of euphoria in the market right now is kinda crazy. What the hell is everyone so optimistic about? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:11:09 </td>
   <td style="text-align:left;"> $SPY gets over bought soon. $QQQ $SPX 

I think it’s over bought now $DIA $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:07:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM 
Bears I would definitely be happy for tomorrow if I were you… just go to sleep and let the bulls party with the futes …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:06:44 </td>
   <td style="text-align:left;"> $AMC $GME $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:06:08 </td>
   <td style="text-align:left;"> $spy $qqq weird the market was freaked out about a 25 basis hike, but not at all concerned about the next two meetings being 50 pts, followed by several more this year.  Fed may as well do 100 pts at a time since market has no fear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:05:51 </td>
   <td style="text-align:left;"> $QQQ guess those puts haven’t been printing lately 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:05:43 </td>
   <td style="text-align:left;"> $SPY $QQQ Bottom line, the market won&amp;#39;t enter into a prolonged bear market unless we have a recession and we aren&amp;#39;t going to have a recession here in the US within the next few years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:05:00 </td>
   <td style="text-align:left;"> In the last month $QQQ has a been trading in the 317.45 - 357.85 range, which is quite wide. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:03:12 </td>
   <td style="text-align:left;"> $SPY $QQQ we resume to new ATH as scheduled! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:03:10 </td>
   <td style="text-align:left;"> $QQQ $SPY Bloomberg TV just reporting that Russia has declared war on USA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:02:39 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
8% inflation 
 
FED sets interest rate at 0.25% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:01:38 </td>
   <td style="text-align:left;"> $QQQ $SPY so $tsla gained ~$300 bil in market cap within 6 days… but the squeeze is just starting? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 07:01:17 </td>
   <td style="text-align:left;"> $QQQ what is going on? I am hanging on but this won’t end pretty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:59:29 </td>
   <td style="text-align:left;"> $QQQ all stonks going back to all-time highs and the dow will hit 50k.  All will hail Sleepy Joe as the greatest dead President in history. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:59:28 </td>
   <td style="text-align:left;"> $QQQ $SPY

MARRIED TO THE MONEY
INTRODUCED HER TO MY STOVE

LOL kitchen appliances from $HD are being purchased tomorrow. Those guys are awesome, great customer service and very inclusive company. I’m actually buying my shit from a non binary person. They knew their shit, how can I argue with that? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:58:59 </td>
   <td style="text-align:left;"> $QQQ what a joke this guy is! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:58:51 </td>
   <td style="text-align:left;"> $QQQ am going to leave this here. If you wish to follow on twitter @optionboys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:58:35 </td>
   <td style="text-align:left;"> $QQQ test of the 50 day and the 351 fib level both held today, easily. No reason we can&amp;#39;t test 364 before a 50 day re-test.

Trade the chart, not the news.

Sorry bears. $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:57:54 </td>
   <td style="text-align:left;"> $QQQ everyone living there life normal tryna make a quick buck in the market, meanwhile society is breaking down and there is about to he a historic economic collapse🤣🤣, hope you are stocking up $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:57:18 </td>
   <td style="text-align:left;"> $QQQ maybe Congress is funding their printer with all these “bills” they’re passing for infrastructure and to help Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:55:14 </td>
   <td style="text-align:left;"> $QQQ $SPY Nancy thanks you for holding her bags. ❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:54:59 </td>
   <td style="text-align:left;"> $QQQ $SPY $BTC.X $NVDA $AAPL https://www.forbes.com/sites/sergeiklebnikov/2022/03/22/history-shows-investors-who-buy-during-bear-markets-will-likely-see-huge-gains/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:54:06 </td>
   <td style="text-align:left;"> $QQQ 450 next month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:51:04 </td>
   <td style="text-align:left;"> $QQQ max pain is 348, if the markets are manipulated, which they are, looking for a 2.25% drop tomorrow… keep buying calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:49:57 </td>
   <td style="text-align:left;"> $QQQ $400 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:49:37 </td>
   <td style="text-align:left;"> $SPY $QQQ The clown market is back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:49:29 </td>
   <td style="text-align:left;"> $QQQ $SPY anyone else starting to realize most tickers are back or nearly back to where they were before the January dipping? Peep tsla, Msft, sq, aapl, amzn… shit even GME now 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:49:24 </td>
   <td style="text-align:left;"> $SPY $QQQ  Anybody have one single good explanation why we’re pumping ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:48:28 </td>
   <td style="text-align:left;"> *****GAMMA SQUEEEEEZE***** 
 
$SPY $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:47:36 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Pelosi Exercises Tesla Stock Options To Buy $2 Million In Shares stck.pro/news/TSLA/24861456 $QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:47:16 </td>
   <td style="text-align:left;"> $QQQ $SPY Recession Priced In, move on and continue to buy ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:45:11 </td>
   <td style="text-align:left;"> $QQQ $SPY the Fed will announce recession soon. This is the final run before the ultimate drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:44:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM technical analysis for tomorrow. 
 
https://youtu.be/484mD9OcLKY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:43:59 </td>
   <td style="text-align:left;"> $QQQ LOL up 13% in six days and can&amp;#39;t sell off for more than ten minutes at a time before dip buyers step in.  I guess a lot of people missed this move.  FOMO is powerful. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:43:34 </td>
   <td style="text-align:left;"> $NQ_F $QQQ #NASDAQ #stockmarket #equities #Futures #Trading #marketforecast  
Recap: Today&amp;#39;s trading reports bias+1 bullish sent 3/22/22 8:13 AM 
$NQ DUT+5 breached at $14,536 
Daily Notes: Buy weakness. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:43:31 </td>
   <td style="text-align:left;"> FUTURES RIP RIP RIIPPIINNGGGG 
 
Most powerful rally in mankind history  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:42:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $ETC.X $TSLA 
 
There are still currently around ~17.2 million active cases in the US, out of a total of ~81.5 million since the start of the pandemic. 
 
The previous two waves peaked at around ~8.5 million and ~9.1 million respectively, so remains roughly twice as high as it&amp;#39;s ever been prior to Omicron and ~20% of total cases since the pandemic started. 
 
Given how mild Omicron was I&amp;#39;m not too worried about this figure, more concerned with BA.2 (roughly twice as infectious as Omicron, risks less known) and Deltacron (a &amp;quot;recombinant virus&amp;quot; taking genetic code from both Delta and Omicron mutations) spreading in the US. 
 
More info about BA.2 in my post below where I&amp;#39;ve been tracking its spread in South Korea, Deltacron is newer but I&amp;#39;m still keeping a close eye on new research about it. 
 
https://stocktwits.com/Fundy_OracleOfAlpha/message/445469326 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:42:42 </td>
   <td style="text-align:left;"> $QQQ $SPY what in the perma bull fuck is happening?!😂🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:42:19 </td>
   <td style="text-align:left;"> $SPY RISK VS REWARD is on Bears side now🙋‍♂️💰📈📉.. $450 (even $454 topside *extreme bull case $457 DBL TOP) RES - obvious Pivot 🧱👀 
 
I BOUGHT NO🚫 PUTS TODAY! however spent the day charting for my next gang of PUTS 🤙  (APRIL 14 $420 PUTS are the OI warehouse of late) 🛅    
 
Tomorrow we should get some notable PUT ACTION 🔛 (BULLS ENTIRE YEARLY GAINS =  this recent fraud rally bounce! 🤷‍♂️ NO NEW ATH - nope 🤡🙃 $qqq $tsla $ba </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:40:50 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 
. 
 
#liarfed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:40:30 </td>
   <td style="text-align:left;"> $SPY $QQQ one or two green days after 8 weeks of red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:38:55 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
QE &amp;quot;over&amp;quot; but FED still increasing the balance sheet. 
 
#liarfed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:36:37 </td>
   <td style="text-align:left;"> S&amp;amp;P 500 sits above the 200-DMA as dip buyers reclaim 4500 https://www.billionaireclubcollc.com/sp-500-sits-above-the-200-dma-as-dip-buyers-reclaim-4500/ $SPY $DJIA $DXY $VIX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:34:23 </td>
   <td style="text-align:left;"> $QQQ $SPY maybe amc and GME will crash the market again after this perma bull dream </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:33:26 </td>
   <td style="text-align:left;"> $QQQ volume has been on a downtrend since the 16th. There’s your projection outlook. You can only shit in a toilet so many times before you have to flush. 

This fake run will require 4 flushes, a plunger, and then septic support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:33:18 </td>
   <td style="text-align:left;"> $QQQ  It appears the old adage that &amp;quot;the markets hate uncertainty&amp;quot; has now completely flipped to &amp;quot;the markets love uncertainty.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:31:02 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:28:34 </td>
   <td style="text-align:left;"> $QQQ I already printed $ our kids futures down the drain and nobody can stop me! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:28:27 </td>
   <td style="text-align:left;"> $SQQQ $QQQ $SPY $UVXY indeed... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:28:18 </td>
   <td style="text-align:left;"> $SPY $QQQ 🤷‍♂️🤷‍♂️🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:28:05 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
8% inflation 
 
FED still increasing balance sheet 
 
#liarfed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:26:47 </td>
   <td style="text-align:left;"> $QQQ I think even if Putin drop a nuclear bomb tonight the market will still open green. Priced in you know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:24:54 </td>
   <td style="text-align:left;"> $QQQ futures bounty to fip. Can’t wait to look down on everyone when I’m on the moon . LFG $TSLA $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:24:04 </td>
   <td style="text-align:left;"> $MULN Investor Places Luke Lango thinks this is next big opportunity stock like Amazon and Tesla. Stated the company could have the “forever battery” he called it. Life changing gains are coming people $AMC $GME $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:23:39 </td>
   <td style="text-align:left;"> $QQQ futures ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:22:45 </td>
   <td style="text-align:left;"> $QQQ I sold a massive call credit spread at the close.  I’ll take a choppy week from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:22:17 </td>
   <td style="text-align:left;"> SweepCast tracked an out of the ordinary activity: $QQQ with our scanner on $325 CALL Expiring: 04-01-2022 worth 33K🐂  Learn more on our website or Join Premium Room! #stockmarket #stockstowatch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:21:23 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
8% inflation and rising 
 
FED still increasing balance sheet! 
 
#liarfed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:20:49 </td>
   <td style="text-align:left;"> $SPY What&amp;#39;s the point in Putin dropping nukes in Ukraine rending the land useless for decades?  There&amp;#39;s no winning outcome afterwards.  $qqq $uvxy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:20:14 </td>
   <td style="text-align:left;"> BLESSED TO BE ABLE TO BUY $spy $qqq those lows last week were just IINNCCRREEDDIIBBLLEE missed the first V day but quickly corrected and LSAUGHTERED MARKET </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:15:54 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ bought this morning , sold today , that’s how you do it ya chooches. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:15:29 </td>
   <td style="text-align:left;"> $QQQ 14% in less than two weeks this is something else I&amp;#39;ve never seen this even not after the covid-19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:14:53 </td>
   <td style="text-align:left;"> $SPY . $DIA . $QQQ . $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:12:11 </td>
   <td style="text-align:left;"> $SPY $QQQ I&amp;#39;m definitely not having dinner at Dorsia tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:11:35 </td>
   <td style="text-align:left;"> $QQQ Fake rally head fake 👎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:11:11 </td>
   <td style="text-align:left;"> $QQQ I&amp;#39;m all in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:10:29 </td>
   <td style="text-align:left;"> $QQQ $SPY when this ends it won’t be as nice as buy the dip. It will wipe out every bull’s account </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:10:26 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK Trading Livestream @ 7pm Central to cover:  
 
📉 General Market Outlook 📈 
👀 Stocks on my Watchlist 
🙋‍♂️ Chart requests from YOU! 
@InvestorsBusinessDaily #IBDPartner 
 
See you there! 👇 
https://youtu.be/JmGINFI-bLc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:09:59 </td>
   <td style="text-align:left;"> $QQQ trying to be stuck with a 1 sided track mind will get you burned in the stock market. Rules no longer apply 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:08:00 </td>
   <td style="text-align:left;"> $ARVL $SPY $QQQ 

It is very dangerous to short it or not own ARVL at this time. Any day they will announce Certification in London session &amp;amp; we here in USA will be at sleep when this will open  at $10 premarket. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:07:53 </td>
   <td style="text-align:left;"> $QQQ today’s gain will be gone before tomorrow’s market open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:07:15 </td>
   <td style="text-align:left;"> $AABB $SPY $GME $QQQ $AMC get in $AABB AABBG.X  Exchange 365 24/7 crypto exchange  revenues also 5 GOLD Mines and NFT&amp;#39;s. the stock will have a massive run. BUY and GO LONG massive ROI coming LONG https://investorshub.advfn.com/boards/read_msg.aspx?message_id=145999225   https://twitter.com/wsbconsensus/status/1453816683420950528?s=21  https://finance.yahoo.com/news/asia-broadband-launches-mobile-app-120000163.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:06:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
Feels like stocks is just gonna go up everyday, cuz investors don’t care about a recession until it actually happens…. So until that happens, get what you can get out of it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:03:26 </td>
   <td style="text-align:left;"> $SPY $QQQ Let&amp;#39;s talk stock https://youtu.be/_ahu17_v97c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:02:36 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ll bet everyone now thinking &amp;quot;back to buy the dip&amp;quot; and I don&amp;#39;t blame you.  Good luck with that strategy.  $uvxy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 06:01:23 </td>
   <td style="text-align:left;"> $SPY Biden warned everyone that Russia might invade Ukraine.   Biden now warning everyone in case Putin drops nukes.. on who?  who knows.  $uvxy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:59:34 </td>
   <td style="text-align:left;"> $SPY $QQQ bullish on global crop shortages, $200 oil and 40 year high inflation. Fucking clown stock market what a shit show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:57:03 </td>
   <td style="text-align:left;"> $SPY   1 Bear Left Standing alert.  $NDX $QQQ 

   . $SPX                                               . $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:55:48 </td>
   <td style="text-align:left;"> $SPY from @Jaytrader153 im reposting. Anyone know what this is? Look at the right and the amount. Time was 4:10pm $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:55:31 </td>
   <td style="text-align:left;"> $MULN 23$ target this year $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:55:02 </td>
   <td style="text-align:left;"> $SPY  There’s a lot of pressure to perform here bulls. 

Don’t drop the balls. It will be worst decision you made in the last few days   $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:54:20 </td>
   <td style="text-align:left;"> $SPY $QQQ

$AMC

DAMNIT! I saw this glitch and though we might have actually figured out how to get rid of them. All of them. At once 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:54:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY market crash until April 6th, and then rebound like crazy until end of April. Watch it happen bitches screenshot this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:53:48 </td>
   <td style="text-align:left;"> $QQQ I see nothing changed again today. your Pelosi  cheered her husbands investments to the public, clap clap clap, and like a bunch of sheep lots bought, instead of questioning insider knowledge. 
Must be cool be treated like a rock star after announce a investment. 
No reality, cartoon time still running. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:50:51 </td>
   <td style="text-align:left;"> $SPY  Nice day for a extended turn around 

$spx $dia $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:50:00 </td>
   <td style="text-align:left;"> $AMC 👀AH Runner $SPY $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:49:08 </td>
   <td style="text-align:left;"> $QQQ Puts in the morning 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:48:57 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
fucking lying piece of shit 
 
this is America asshole! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:41:55 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Fed-backed inflation is great! 
 
If you are rich. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:41:15 </td>
   <td style="text-align:left;"> $SPY $QQQ  Wali the Canadian Sniper is in Ukraine Shooting for peace 😇🧤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:40:57 </td>
   <td style="text-align:left;"> I want all to realize, $QQQ closed above its 10/20/40 day resistance. The 250/500 day resistance is at 366. 
Just putting that in the air </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:39:27 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $ARKK 10yr yield looks overextended. that&amp;#39;s bullish for equities, especially tech, going forward in high inflation environment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:39:03 </td>
   <td style="text-align:left;"> Crazy to think Fed isn’t buying any bonds and we still V rally like this eh? 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:38:18 </td>
   <td style="text-align:left;"> $SPY PLACE YOUR BETS - GAP UP📈OR GAP DOWN 📉FUTURES?? 
 
$450 PIVOT hit and profit taking ensued! Bulls what&amp;#39;s your narrative to go higher from here?🤷‍♂️👀 
 
$tsla $aapl $qqq $tnx  
 
time to go vegan🍛 - Bulls diseased and too expensive🥩 (INFLATION💀🙃) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:35:55 </td>
   <td style="text-align:left;"> $BABA Just so we&amp;#39;re clear, the People on CNBC who told you Chinese stocks were uninvestable  2 weeks ago &amp;amp; then told you to Sell a week ago on the 1st pop are still giving advice on these?  
 
Hmmm, I wonder if we should listen :o) 
 
$jd $didi $kweb $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:35:25 </td>
   <td style="text-align:left;"> Market has bottomed, the only unknown is Ukraine. This has been a historic rally the last few days, a pullback seems extremely likely, though it still hasn’t came. I bought $QQQ puts and positioned for a drop. If not, I’m long moving forward. Growth stocks are about to squeeze. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:32:57 </td>
   <td style="text-align:left;"> Live updates: Votes near for UN humanitarian resolutions https://www.billionaireclubcollc.com/live-updates-votes-near-for-un-humanitarian-resolutions/ $SPY $DJIA $QQQ $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:32:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:31:58 </td>
   <td style="text-align:left;"> $AMZN September of 2012 Amazon had a 6000 plus P/E ratio, if I hear one more word about Tesla’s 200 PE ratio 
being a lot i will bitchslap your ass, did you forget last year it had a 1300 p/e ratio, after the next earnings ga release it will be a lot lower because of increased revenues $TSLA $ARKK $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:30:46 </td>
   <td style="text-align:left;"> $QQQ casino is back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:30:19 </td>
   <td style="text-align:left;"> $QQQ  
Would Russia using tactical nukes be considered bullish or bearish?  Asking for a friend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:28:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $TQQQ $AAPL $TSLA 
Well don’t mind if I do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:28:37 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 
 
8% inflation 
0.25% rates 
 
FED is an absolute joke of an organization at this point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:27:28 </td>
   <td style="text-align:left;"> $QQQ last week Cramer talked about his new &amp;quot;FANG&amp;quot; on CNBC morning: MAGSSS, which is Microsoft, Apple, Google (Alphabet), Salesforce, ServiceNow, and Snowflake...can some one confirm please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:26:39 </td>
   <td style="text-align:left;"> $QQQ Michael Safran&amp;#39;s PT is out . $298 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:26:33 </td>
   <td style="text-align:left;"> Remember when BONDS and STOCKS couldn&amp;#39;t rally together?-- Yeah, me neither $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:24:25 </td>
   <td style="text-align:left;"> $QQQ Imo, In my own echo chamber. We are in the midst/beginning of a recession. The FED could care less about core inflation, and they&amp;#39;re more worried about equity deflation. 
I have no idea where people get the phrase &amp;quot;balancing act.&amp;quot;
 70% of GDP is consumer spending.
Core inflation is up, consumer spending goes down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:24:19 </td>
   <td style="text-align:left;"> Bulls are back baby! $SPY $DIA $QQQ $FB $SMH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:23:58 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $QQQ $NDX  just out 

Biden warn Putin “ Back Is Against The Wall” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:23:03 </td>
   <td style="text-align:left;"> $SPY NO LIES DETECTED ... ⚖️🔍 
 
$qqq $tnx $dxy $XLF  
 
Merica needs to be turned upside down from top to bottom 🙃👀🚮📉🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:22:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA

Toot it and boot it &amp;lt;&amp;gt; pump it and dump it 

$WEN I’ll take my job back whenever you want to throw me a fat offer. Thx 

https://m.youtube.com/watch?v=A2giKJcy-YA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:22:10 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:22:04 </td>
   <td style="text-align:left;"> NASDAQ $QQQ Top Gainers during today $PDD $TSLA $NTES $MRNA 
  
Learn more: https://www.finscreener.org/screener/top-gainers/stocks/nq100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:21:25 </td>
   <td style="text-align:left;"> $QQQ I had to temporarily go long last few few days by selling naked puts. 

Now that moo is probably long - repositioning for a big drop again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:21:18 </td>
   <td style="text-align:left;"> $ES_F $SPY $NQ_F $QQQ several bull cycles running strong new higher highs heading into midweek - bullish week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:21:18 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
8%+ inflation 
$100+/barrel oil 
0.25% interest rates 
 
indexes trading like penny stonks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:21:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Well no shit!! Ever try to put toothpaste back in the tube?🤡😂🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:20:33 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 3/22/2022 $SPY $QQQ $CCJ $TSLA $MSOS https://www.chartguys.com/daily-market-videos/4199/fomo-creeping-back-in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:20:30 </td>
   <td style="text-align:left;"> $QQQ $SPY

I see the impact of Russian business exit has been priced in effectively. Wait, you guys know that happened abruptly during q1 right? Are we time traveling to determine the impact? 🤣

I am ok being totally wrong about this bear case </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:20:03 </td>
   <td style="text-align:left;"> $QQQ We made money again! Those
who have been following me have been
making money consistently. Haters
spread hate but I have helped retailers
make money for free during past few
weeks when most were losing
If you missed my daily plans follow my
twitter @optionboys or if you want to
join my private group message me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:19:42 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:19:16 </td>
   <td style="text-align:left;"> $QQQ now that we are expecting a pullback it won’t cuz that’s how it rolls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:16:35 </td>
   <td style="text-align:left;"> $QQQ $SPY  I knew the rally would be wild but i didn&amp;#39;t expect it to be  this EPIC. I usually don&amp;#39;t like buying puts but bought end of day as a hedge for the rest of this week. Downside&amp;gt;Upside here IMO. You gotta be really brave to still be holding calls here IMO. How many 1-2% more consecutive days can we really get? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:14:42 </td>
   <td style="text-align:left;"> $QQQ $SPY pigs get slaughtered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:10:13 </td>
   <td style="text-align:left;"> $QQQ $TSLA breaking into 1k land. April 1st mark it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:10:06 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $DJIA  read 👓 

https://fortune.com/2022/03/20/us-credible-information-russians-creating-lists-ukrainians-to-be-killed-or-sent-to-camps-ambassador-united-nations-concentration-filtration-camps-batsheba-nell-crocker-michelle-bachelet/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:09:39 </td>
   <td style="text-align:left;"> $QQQ $SPY  bears gona stay up overnight thinking of new excuses for the big crash tommorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:08:00 </td>
   <td style="text-align:left;"> $SPY $qqq $djia  y&amp;#39;all can&amp;#39;t chart this market but you just keep trying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:07:21 </td>
   <td style="text-align:left;"> $QQQ anyone buying long here salute to you for having absolute balls of steel 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:06:47 </td>
   <td style="text-align:left;"> How is the Delta on 3/25 345C .86 
But the delta on a 4/20 345C .61
🤔

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:06:41 </td>
   <td style="text-align:left;"> $QQQ i am down a lot on my puts, not many people would acknowledge the loss , but i made good money on tesla calls today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:06:22 </td>
   <td style="text-align:left;"> $SPY Concentration Camp’s 

$qqq $dia $djia $spx  Russia placing Ukrainians on train’s sending them to concentration camp’s. 

Tv News 📰. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:04:44 </td>
   <td style="text-align:left;"> $QQQ CCI daily is at 147.89. high af.  short it to 0 at minimum. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:03:46 </td>
   <td style="text-align:left;"> $QQQ it’s kind of a fun market. One day I’m a genius and the next day I’m about to blow up my entire account! What a rush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:03:40 </td>
   <td style="text-align:left;"> FED&amp;#39;S MESTER: THE UPSIDE RISKS TO INFLATION FROM THE UKRAINE CONFLICT OUTWEIGH THE DOWNSIDE RISKS TO US GROWTH. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:03:23 </td>
   <td style="text-align:left;"> $SPX $QQQ $SPY . $DIA $DJIA  💣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:03:06 </td>
   <td style="text-align:left;"> $SPY $QQQ Powell talks tomorrow at 8 am.  His hawkish tilt didn’t have the intended effect.  He has no credibility. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:02:35 </td>
   <td style="text-align:left;"> $AFI 🚨🚨🚨🚨🚨🚨🚨🚨🚨 
 
Soooo…..how has no one mentioned that the current CEO of Armstrong Flooring worked at Mohawk for 20 years? Michel Vermette…..look it up.  
 
$MHK $SPY #buyout $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:02:28 </td>
   <td style="text-align:left;"> $QQQ $SPY Fed members coming out daily to try and take the market down, but it won&amp;#39;t stop going up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:01:36 </td>
   <td style="text-align:left;"> $SPY $QQQ  for the bulls, what kind of news is still not priced in? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:01:15 </td>
   <td style="text-align:left;"> US Monitoring For ‘Potential Contingency’ On Nuclear Weapon Use, White House Says https://www.billionaireclubcollc.com/us-monitoring-for-potential-contingency-on-nuclear-weapon-use-white-house-says/ $SPY $QQQ $DJIA $VIX $DXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:01:02 </td>
   <td style="text-align:left;"> $QQQ this feels
Like slots fuck a casino </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:00:56 </td>
   <td style="text-align:left;"> Mester: To Quell Inflation, Will Need to Raise Funds Rate to 2.5% in 2022 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:00:25 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-03-22 Chart Analysis Video: 
https://www.youtube.com/watch?v=W55KGAo0m5o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:00:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Staying liquid (cash) will hurt you in times of inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 05:00:00 </td>
   <td style="text-align:left;"> $SPY  $QQQ Watch The BULLARD tomorrow @3pm for volatile and shake the market 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:58:59 </td>
   <td style="text-align:left;"> $SPY $QQQ Whelp, they aren&amp;#39;t going to announce when the music stops... flow still showing that this up move has likely come to an end today with maybe some sideways action tomorrow: 
 
1/2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:58:57 </td>
   <td style="text-align:left;"> $QQQ So let me get this straight....now we&amp;#39;re at or above pre-war, pre-$110 oil, pre-likely-50bps-hike levels again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:58:45 </td>
   <td style="text-align:left;"> $QQQ bulls confused bears confused. At least we’re all confused together! Just do the opposite of what people think I guess the type of market we in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:58:30 </td>
   <td style="text-align:left;"> $QQQ clearly 90% of the bear posts here are fud.   
 
if you were a bear 3 weeks ago, you’re broke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:56:38 </td>
   <td style="text-align:left;"> $QQQ Your confused ?! I’m confused we’re all confused! Take me back to trump bulk market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:56:20 </td>
   <td style="text-align:left;"> CARL ICAHN SAYS &amp;quot;I THINK THERE VERY WELL COULD BE A RECESSION, OR EVEN WORSE&amp;quot; - CNBC 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:56:02 </td>
   <td style="text-align:left;"> $QQQ I can&amp;#39;t simply understand why people are shorting. Wtf? It&amp;#39;s like lotto play.

Buy stock hold on to it for years, add every month. See shorters burn and cry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:55:58 </td>
   <td style="text-align:left;"> $TSLA this garbage is going to puke with $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:55:29 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM Worth repeating when the market is this one sided  
1 ) AT ANY MOMENT IN TIME, you can always construct a bullish OR bearish thesis. 
2) The market DOESN&amp;#39;T give a flying f*ck about your great research or your bullish/bearish sentiments.  ONLY PRICE PAYS! 
3) So when you&amp;#39;re wrong, the market is NOT stupid.  The people who took the opposite side of your trades (and making $$$), they&amp;#39;re NOT stupid either. 
4) Put your ego and stubbornness away.  Take your lumps by using stop loss, and move on! 
5) The market will ALWAYS fluctuate.  Thus, there will ALWAYS be future opportunities. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:55:26 </td>
   <td style="text-align:left;"> $SPY .... 🦖The market is straight up hiding from a Tyrannosaurus Rex 🦖 right now...If I don&amp;#39;t move from where I am it won&amp;#39;t see me... I can just keep going if they can&amp;#39;t see me move right now just wait until futures trading and then we can do whatever we want😂 $UVXY $QQQ $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:53:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $NVDA $LCID save my month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:53:22 </td>
   <td style="text-align:left;"> $QQQ this is getting quite comical… feds just warned they are going to accelerate rate increases </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:51:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AMZN keep your patience </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:51:32 </td>
   <td style="text-align:left;"> (correcting) Asset Classes ranked by price strength and momentum re Mar. 22 close: $QQQ $DIA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:51:31 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : Everything Advisors Need to Know About Upcoming Rate Hikes https://www.stck.pro/news/QQQ/24861638 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:51:22 </td>
   <td style="text-align:left;"> $QQQ still holding puts. April exp. pray for me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:50:51 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 1.1M options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:49:51 </td>
   <td style="text-align:left;"> $SPY $SQQQ $TQQQ $QQQ No reason to sell before it breaks under whatever the lowest green line is below current price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:49:03 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 86148800. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:48:48 </td>
   <td style="text-align:left;"> $SPY $QQQ I must be living in the past or something cuz we still have WW3 on the table with 40 year sky high inflation and an idiot Fed not doing anything about it. but nasdaq up 13% in a week is totally normal keep buying the dip right? WTF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:48:24 </td>
   <td style="text-align:left;"> Asset Classes ranked by price strength and momentum re Mar. 22 close: $QQQ $DIA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:46:59 </td>
   <td style="text-align:left;"> $SPY $QQQ Geeesh How ‘wee’ are these Russian/Ukrainian dudes?

 PUTPoleon vs ZELCruise 

?????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:46:22 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL  wow CRAZY SHIT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:45:47 </td>
   <td style="text-align:left;"> $SPY $QQQ Fed not inflating to serve as buyer of last resort for all US gov debt = BK. They cannot stop inflating as a consequence. 🤑📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:45:17 </td>
   <td style="text-align:left;"> $AAPL negative news cycle now coming on cue $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:45:12 </td>
   <td style="text-align:left;"> $TSLA $QQQ $ARKK $SPY $VOO Despite TSLA’s stunning +30% run the past 6 days in a row (NDX +12%) Tesla is still very cheap at &amp;lt;50x my 2023 EPS of $20, and 18x my 2026 EPS of $55. There are no megacaps likely to post 50% annual Vol &amp;amp; EPS growth between 2021-26, and none that trade at 1x 2023 P/E-to-future 5yr growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:44:40 </td>
   <td style="text-align:left;"> $SPY double breakout. Tomorrow would make the most sense for a pull back but we might be entering mania phase again. Who knows how long that’ll last $QQQ $TSLA $GOOG $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:43:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Buy the dips and you will always make money. It is the best time to buy when people are fearful and selling on panic and it was just like that before last week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:43:17 </td>
   <td style="text-align:left;"> $QQQ Lentils? Bus ride? WT........fish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:41:59 </td>
   <td style="text-align:left;"> $QQQ well apparently this week was the wrong week to bet short on reality. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:40:50 </td>
   <td style="text-align:left;"> $QQQ It is very weird, every pro is talking about recession and bear market still market does not care. that&amp;#39;s why they say market can be irrational at times </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:40:34 </td>
   <td style="text-align:left;"> $QQQ bullish when there is a nuclear war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:39:58 </td>
   <td style="text-align:left;"> $AMZN  I just opened the weekly on Amazon after hours to check it out and found this😂 Lines were already there $SPY $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:39:49 </td>
   <td style="text-align:left;"> Live updates: France’s Macron speaks with Putin, Zelenskyy  $SPY $QQQ $DJIA $DXY $VIX https://www.billionaireclubcollc.com/live-updates-frances-macron-speaks-with-putin-zelenskyy/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:39:41 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Unless they KNOW Fed is pumping, they cannot possibly be this reckless in the last minute, for 6 days, under THIS circumstance! 
Criminal… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:39:33 </td>
   <td style="text-align:left;"> $BA $SPY $QQQ You can predict recession all you want…. I’m a TRUMPian economist… all that matters is JOBS. UNEMPLOYMENT at 3% with job openings at 12MM…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:39:21 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM Another strong day (happy because I&amp;#39;m long).  Being a contrarian, I&amp;#39;m feeling a little uneasy when the market is this one directional.  Perma-bulls, watch your profits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:38:39 </td>
   <td style="text-align:left;"> $SPY $QQQ damn the rate we going by end of this month we will be back to ATH. We love rate hikes. Nothing can stop powellllll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:38:36 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG $QQQ load up what else you need!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:38:26 </td>
   <td style="text-align:left;"> $QQQ went up 9% in 5 days lol. The return of the futures usually the same for one year lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:36:00 </td>
   <td style="text-align:left;"> $QQQ All the chaos and uncertainty in the world, and the markets go up. So just imagine how high the stock market would skyrocket if there actually was a nuclear war. The first nuke Russia sends and the markets will go up 2000 points???  Then 80% of the population of the world destroyed, and the markets go up another 3000 points?? Then when there is virtually no human life left on the planet, the markets will go up anther 5000 points?Totally bizarre what is going on now in the stock market. People buying into an absolute shitstorm as if nothing is wrong in the world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:33:27 </td>
   <td style="text-align:left;"> $TSLA we have Giga Austin TX day and stock split day total of $250 more upside coming soon $QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:32:36 </td>
   <td style="text-align:left;"> $SPY uh oh BULLS nervous😱 - big money coming out again in disdain of the fed and this market bubble more and ... RECESSION INEVITABLE! ✔  
 
🚨CHEAP MONEY - DRYING UP 
RATE HIKES - ROCKETING HIGHER 
ECONOMY - SLOWING 
WAR - CHINESE DRIP TORTURE IN GLOBAL MARKETS 
HOUSING - WAITING TO COLLAPSE  
PRESIDENT - STILL USING TAXPAYERS TO PAY OFF HIS FAMILY PERSONAL DEBT ABROAD etc.  
 
Bulls - Still LOW IQ and going ALL IN at the top of PIVOTS 😁🤡 
 
$TSLA $BA $QQQ $TNX  
Beach ⛱️  day! 🙋‍♂️💦☀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:31:49 </td>
   <td style="text-align:left;"> $QQQ surprise hike tomorrow would be epic 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:31:19 </td>
   <td style="text-align:left;"> $QQQ this rally is transitory, please take advantage of the huge discount on puts I would really be torn up if you regretted missing out on the easiest money so far this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:31:09 </td>
   <td style="text-align:left;"> $AABB $SPY $QQQ $TSLA $AAPL The massive MOASS is coming to $AABB get ready for a MOASS https://shockertrades.blogspot.com/2012/04/bashers-handbook.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:28:50 </td>
   <td style="text-align:left;"> $QQQ $MSFT $AAPL $NIO $F  
 
Carl Icahn says there ‘very well could be a recession or even worse’ .. Is time to short every Rallies ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:26:58 </td>
   <td style="text-align:left;"> $SPY Stocks stage comeback a day after Powell hints at more aggressive rate hikes.   Market completely ignoring JPOW until he actually does anything meaningful.. like a 75 point hike.  $uvxy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:26:20 </td>
   <td style="text-align:left;"> $SPY $QQQ VIX just hit the 200ma on the daily, will we see a volatility spike here soon? 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:24:50 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA 
ENTIRE portfolio (470k) on short/puts. 2022 will make me a millionaire. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:24:44 </td>
   <td style="text-align:left;"> $QQQ chop chop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-23 04:24:35 </td>
   <td style="text-align:left;"> $qqq seriously though, it’s about to rally twice as hard as this rally the past 6-7 days was. this rally was 12.5% the next five days will be a 25% gain to $470 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 09:12:45 </td>
   <td style="text-align:left;"> $MULN 🤝🍎 $AAPL $LUCD $TLSA 
 https://carbuzz.com/features/mullen-is-making-performance-evs-to-get-excited-about </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 09:10:35 </td>
   <td style="text-align:left;"> $AAPL 150 to 169 in few days! Bout time for pooots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 09:07:40 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $SQ $SNOW 
Rug Pull starts tomorrow 👻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 09:07:19 </td>
   <td style="text-align:left;"> $AAPL  🙏 . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 09:07:14 </td>
   <td style="text-align:left;"> $BTC.X If we go into a recession, this will nearly go to zero $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 09:07:03 </td>
   <td style="text-align:left;"> $BTC.X if this POS breaks 40k before open tomorrow. GOOD FUCKIN RIDDANCE $AAPL $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 09:06:06 </td>
   <td style="text-align:left;"> $AAPL 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 09:05:27 </td>
   <td style="text-align:left;"> #LIVESTREAM ALERT🚨 
🔥WE ARE NOW LIVE 
I&amp;#39;m going to breakdown 👇 
📈trade ideas 
🔫triggers  
🎯targets  
click👉 https://us02web.zoom.us/j/84650646657  $SPY  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:48:45 </td>
   <td style="text-align:left;"> GME options: +2000% move today 
$TSLA options +600%  $QQQ $SPY $AAPL $BABA 
CLICK HERE to learn how to trade options profitably 
https://goldentrading.website/work-from-home-jobs-stock-trading-courses-for-beginners-learn-how-to-trade-stocks-and-make-1000-a-day-from-home/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:40:04 </td>
   <td style="text-align:left;"> $AAPL 173.30 is max gain pain folks. I hope it hits this so I can LOAD my puttss.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:36:40 </td>
   <td style="text-align:left;"> $AAPL I agree🍏💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:28:49 </td>
   <td style="text-align:left;"> $AAPL Why do I get a  sense there are a lot of baffled bears on here? 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:25:20 </td>
   <td style="text-align:left;"> $AAPL grabbed and goed minus 200 and 170 puts x55. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:22:38 </td>
   <td style="text-align:left;"> $AAPL will hit $170 then downwards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:21:49 </td>
   <td style="text-align:left;"> $AAPL will apple go green 6 days in arow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:21:18 </td>
   <td style="text-align:left;"> $AAPL stock analysis based on today&amp;#39;s closing price 

https://youtu.be/mScbZFzWfY8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:19:51 </td>
   <td style="text-align:left;"> $AAPL https://www.zdnet.com/article/apples-russia-exit-estimated-to-cost-the-company-3-million-a-day-in-iphone-sales/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:16:40 </td>
   <td style="text-align:left;"> $AAPL  tomorrow what time Powell is speaking.? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:07:54 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $BTC.X calling it now, starting tomorrow till the end of the month the market will know pain. But will rebound and break ATHs there after. better start hedging your portfolio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:03:14 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-22 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=nadqjIc2A-M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 08:02:38 </td>
   <td style="text-align:left;"> $AAPL getting it&amp;#39;s mojo back.. trending up, RSI and MACD positive, a continued move above $170 targets $176- ATH+. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:58:19 </td>
   <td style="text-align:left;"> $AAPL $COIN $HOOD stocktwits should add how many idiots you’ve had to block 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:56:27 </td>
   <td style="text-align:left;"> $AAPL Bears are depositing $ in my account daily. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:56:15 </td>
   <td style="text-align:left;"> $SPY oh NANCY!!! you wicked witch of the DEMORATS  
 
She fights harder to DAYTRADE than for the Merican ppl she was elected to serve!  $XLF $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:45:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Services Experience Outage for Second Day in a Row https://www.stck.pro/news/AAPL/24869263 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:45:05 </td>
   <td style="text-align:left;"> $AAPL it has support at 150 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:39:50 </td>
   <td style="text-align:left;"> $MULN someone investigate. Find the $AAPL connection </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:29:57 </td>
   <td style="text-align:left;"> $SPY $AAPL latex2500e088bb802861f8e278f556efa49bBABA - 64% call flow 
$NVDA - 69% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:27:54 </td>
   <td style="text-align:left;"> $AAPL I am praying,  I have 52 contracts at 90 cents </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:24:54 </td>
   <td style="text-align:left;"> $AAPL $180 in one week.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:22:03 </td>
   <td style="text-align:left;"> latexa4a4a8120d117c9939c684cb438efd18qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:20:08 </td>
   <td style="text-align:left;"> Daily Market Recap for Tuesday 3/22/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/ncL-c8v3PQQ

$AAPL $AMD $TSLA $RBLX

Tech pop sustainable?   Tough to know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:19:44 </td>
   <td style="text-align:left;"> $AAPL I am praying for it   to go down to $165 as i bought puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:12:58 </td>
   <td style="text-align:left;"> $DKNG $AAPL $DJIA Start trading over 4 month ago and I lost all of money,,, Now I&amp;#39;ve made over $236K+ profits after join their chat room and using their alerts,,. Highly recommended/!!!  🚀 livestktrading.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 07:00:48 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Pelosi Exercises Tesla Stock Options To Buy $2 Million In Shares stck.pro/news/TSLA/24861456 .. $FB $NFLX $AAPL $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:58:06 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple (AAPL) Received its Third Buy in a Row https://www.stck.pro/news/AAPL/24867448 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:56:49 </td>
   <td style="text-align:left;"> $FSR $AAPL 

https://youtu.be/UF8uR6Z6KLc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:55:16 </td>
   <td style="text-align:left;"> $AAPL  kids writing articles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:54:59 </td>
   <td style="text-align:left;"> $QQQ $SPY $BTC.X $NVDA $AAPL https://www.forbes.com/sites/sergeiklebnikov/2022/03/22/history-shows-investors-who-buy-during-bear-markets-will-likely-see-huge-gains/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:53:31 </td>
   <td style="text-align:left;"> $AAPL is another 2%+ possible tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:50:56 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 91.5K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:50:31 </td>
   <td style="text-align:left;"> $AAPL Apple generally updates investors on its shareholder return plans in April alongside its second-quarter financial results. Citi analysts expect Apple to announce another $90 billion in buybacks and to raise its dividend by 10%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:49:47 </td>
   <td style="text-align:left;"> $DPRO stock analysis!

$aapl $tsla $amc $gme </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:48:57 </td>
   <td style="text-align:left;"> $AAPL Daily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:45:41 </td>
   <td style="text-align:left;"> $AAPL is going to the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:44:14 </td>
   <td style="text-align:left;"> SweepCast tracked an out of the ordinary activity: $AAPL with our scanner on $170 CALL Expiring: 03-25-2022 worth 64K🐂  Learn more on our website or Join Premium Room! #stockmarket #stockstowatch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:38:58 </td>
   <td style="text-align:left;"> $AAPL good lord my September 2023 $150 covered calls I sold are crying. How does it keep going up… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:35:13 </td>
   <td style="text-align:left;"> $AAPL war is not a reason for this stock to go down. It&amp;#39;s going down because it&amp;#39;s been straight up for a week. Apple is overbought and due for a correction back into the channel. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:34:39 </td>
   <td style="text-align:left;"> $SPY guaranteed red tomorrow. Book it $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:33:22 </td>
   <td style="text-align:left;"> $AAPL bought puts. This still has upside, but I&amp;#39;m inching into being net short. I shorted $TSLA stock as well. I think the next leg down will come soon enough and  the current rally is rather overbought in the near term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:33:12 </td>
   <td style="text-align:left;"> $AAPL    🍏👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:32:36 </td>
   <td style="text-align:left;"> $AAPL glad I didn&amp;#39;t short this. I thought the split was supposed to put downward pressure on the share price short term, or am I making that up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:32:24 </td>
   <td style="text-align:left;"> $AAPL using war as a “scare tactic” is tasteless as fuck. People is losing their lives. FUCK YOUR PUTS. fucking idiots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:27:55 </td>
   <td style="text-align:left;"> $AAPL Moron Bears up voting Moron Bear&amp;#39;s posts.  They are more like cockroaches. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:25:55 </td>
   <td style="text-align:left;"> @GoodieGoodStockOptions 

Is independence even possible with Russian oil strong holds and Chinese lithium strong holds “without a fight”?!
$aapl $amzn $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:24:46 </td>
   <td style="text-align:left;"> $AAPL going down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:23:54 </td>
   <td style="text-align:left;"> @GoodieGoodStockOptions 
Can $Tsla save the transportation and petro power consumption dependency in “the big switch” from petroleum dominance?! $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:19:59 </td>
   <td style="text-align:left;"> $AAPL https://www.barrons.com/amp/articles/apple-stock-price-winning-streak-51647950582 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:16:31 </td>
   <td style="text-align:left;"> $AAPL Tomorrow GME will pass APPLE WTF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:13:08 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple services including Music, Mac App store facing outages https://www.stck.pro/news/AAPL/24865493 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:11:33 </td>
   <td style="text-align:left;"> $AAPL can we hit $175 this week or just $170 tomorrow before a red Friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:09:21 </td>
   <td style="text-align:left;"> $AAPL new member kickin some butt 🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:08:36 </td>
   <td style="text-align:left;"> $AAPL 275 this year here we come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 06:03:28 </td>
   <td style="text-align:left;"> $AAPL $TSLA Which one will get the short trade tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:57:50 </td>
   <td style="text-align:left;"> $AAPL how much money would b a good investment long term right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:53:50 </td>
   <td style="text-align:left;"> $SPY April&amp;amp;May could be volatile like last year. And probably more so without the fed 

$AAPL $AMZN $AMD $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:53:36 </td>
   <td style="text-align:left;"> $AAPL dumped these bad boys at 3:57 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:52:52 </td>
   <td style="text-align:left;"> $AAPL nice Green Day my entire portfolio up…… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:52:36 </td>
   <td style="text-align:left;"> $AAPL go up up north </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:50:20 </td>
   <td style="text-align:left;"> $AABB $AAPL $AMD $NFLX $HD get in $AABB Now at a bottom for the Long Term. Massive gains are coming with the AABBG.X Crypto exchange 365 24/7 revenues plus 5 Gold Mines and NFT&amp;#39;s. Get in NOW at a bottom and GO LONG https://investorshub.advfn.com/boards/read_msg.aspx?message_id=145999225 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:48:14 </td>
   <td style="text-align:left;"> $AAPL I short aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:46:34 </td>
   <td style="text-align:left;"> $AAPL going lower rest of the week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:44:24 </td>
   <td style="text-align:left;"> $AAPL 116 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:43:20 </td>
   <td style="text-align:left;"> $AAPL $NILE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:42:31 </td>
   <td style="text-align:left;"> $AAPL what&amp;#39;s with these outages </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:41:45 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL USA and Russia launching nukes at each other MAD style would just be a dip buying opportunity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:39:32 </td>
   <td style="text-align:left;"> $AAPL I told 
you 230 by next earnings 350 eoy, 1000 eoy next year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:38:40 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Check out my easy way to post memes on stocktwits video and don’t forget to also learn how to do proper due diligence by watching that video I made as well. #KansasCashGivesBack #TuesdayLearnin  https://youtu.be/S7NXbt7UHnA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:38:18 </td>
   <td style="text-align:left;"> $SPY PLACE YOUR BETS - GAP UP📈OR GAP DOWN 📉FUTURES?? 
 
$450 PIVOT hit and profit taking ensued! Bulls what&amp;#39;s your narrative to go higher from here?🤷‍♂️👀 
 
$tsla $aapl $qqq $tnx  
 
time to go vegan🍛 - Bulls diseased and too expensive🥩 (INFLATION💀🙃) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:38:06 </td>
   <td style="text-align:left;"> How do you like them apples?! $AAPL Breakout on the daily following RSI Bullish divergence and up +12% with the move off support 🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:34:53 </td>
   <td style="text-align:left;"> $AAPL old billionaires dream of recession. Old brain = fear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:32:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:28:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $TQQQ $AAPL $TSLA 
Well don’t mind if I do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:21:18 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
8%+ inflation 
$100+/barrel oil 
0.25% interest rates 
 
indexes trading like penny stonks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:19:49 </td>
   <td style="text-align:left;"> $AAPL France says there is no agreement in sight for a ceasefire in Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:18:25 </td>
   <td style="text-align:left;"> $BABA $BIDU $JD $AAPL Alibaba (NYSE:BABA), TENCENT HOLDINGS ADR (TCEHY) – Here’s How Alibaba’s Buyback Boost Could Win Back Investors In China’s Internet Sector

https://news.alertsandnews.com/alibaba-nysebaba-tencent-holdings-adr-tcehy-heres-how-alibabas-buyback-boost-could-win-back-investors-in-chinas-internet-sector/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:17:28 </td>
   <td style="text-align:left;"> $AAPL 18.7 dollars in six days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:15:13 </td>
   <td style="text-align:left;"> $aapl on a six session tear… more to come https://youtu.be/Kpt6TP-PaB0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:15:00 </td>
   <td style="text-align:left;"> $AAPL: The EPS has grown by an impressive 63.57% over the past year. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:12:42 </td>
   <td style="text-align:left;"> $AAPL can&amp;#39;t understand why anyone would be willing to buy this after it went straight up for a week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:10:15 </td>
   <td style="text-align:left;"> $AAPL funny how the kids here all
Laughed at me when AAPL was $151 and I alerted calls - now they are laughed at me again cause I’m calling for puts after our pop
You kids are a day late - dollar short 
Get educated and save yourself money and embarrassment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 05:03:42 </td>
   <td style="text-align:left;"> $AAPL comments on the action from Monday. i meant to release this earlier but ran out of time. https://youtu.be/RxMTqzhdLRo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:59:38 </td>
   <td style="text-align:left;"> $AAPL well I trimmed most of my short positions mid morning. But I doubled down here before the close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:59:25 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:56:32 </td>
   <td style="text-align:left;"> $AAPL inflation interest rates 10 year treasury yields 2.4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:55:39 </td>
   <td style="text-align:left;"> $FB $aapl has crippled Ad revenue, unfortunately its only going to get worse.

Over bought going much lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:54:40 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Hang in there bear family. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:52:07 </td>
   <td style="text-align:left;"> $AAPL great Trade idea </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:47:47 </td>
   <td style="text-align:left;"> $AAPL View @ www.elliottwave-forecast.com can still rally a little bit higher before turning back down.  We do not like to chase the rally off the lows, and are still favouring more downside to take place once this bounce is complete, we do NOT like to short sell technology without a blue box.   #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:46:42 </td>
   <td style="text-align:left;"> $AAPL mACD and stochastic VERY BEARISH here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:46:22 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL  wow CRAZY SHIT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:45:17 </td>
   <td style="text-align:left;"> $AAPL negative news cycle now coming on cue $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:41:32 </td>
   <td style="text-align:left;"> $AAPL very overpriced, pe should be 18 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:39:39 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT 🤙🤮💰💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:39:22 </td>
   <td style="text-align:left;"> $AAPL #1 company ever created, most well known company across the world… shows absolutely no sign of slowing down… I meeeeeeeaannnnn come on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:38:36 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG $QQQ load up what else you need!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:36:10 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 403.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:33:30 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-22 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=nadqjIc2A-M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:32:50 </td>
   <td style="text-align:left;"> $AAPL chart says it&amp;#39;s going down the rest of the week. Lets see some downward pressure in the am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:31:09 </td>
   <td style="text-align:left;"> $AABB $SPY $QQQ $TSLA $AAPL The massive MOASS is coming to $AABB get ready for a MOASS https://shockertrades.blogspot.com/2012/04/bashers-handbook.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:28:50 </td>
   <td style="text-align:left;"> $QQQ $MSFT $AAPL $NIO $F  
 
Carl Icahn says there ‘very well could be a recession or even worse’ .. Is time to short every Rallies ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:21:06 </td>
   <td style="text-align:left;"> $AAPL  
J.P. Morgan analyst Samik Chatterjee raised his target for the stock price from $180 to.......... $210.       
      
Morgan Stanley raises PT from $164  to............ $200.    
    
Citi raises target to............ $200.    
    
Maybe go with the anonymous BEAR trolls instead?......Hey you do you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:20:43 </td>
   <td style="text-align:left;"> $BKKT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:17:51 </td>
   <td style="text-align:left;"> $AAPL So where are all the clown bears from 2 or 3 weeks ago proclaiming we were idiots and they would be buyers at $120? Show yourselves you 6 million dollar man wannabees... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:17:15 </td>
   <td style="text-align:left;"> $AAPL 🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:11:23 </td>
   <td style="text-align:left;"> $AAPL Moron Bears counting their last penny. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:11:07 </td>
   <td style="text-align:left;"> $AAPL  ......“Our analysis suggests that Apple is likely to be able to CONTINUE REPURCHASING ~ 3-4% of its shares PER YEAR UNTIL THE END OF 2026 while GROWING IT&amp;#39;S DIVIDEND per share by 10% annually.... without taking on net debt on its balance sheet,” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:09:21 </td>
   <td style="text-align:left;"> https://www.youtube.com/watch?v=xAAeLHUWyMk&amp;amp;ab_channel=UnlimitedOptionsInvesting  $spy $qqq $aapl $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:06:49 </td>
   <td style="text-align:left;"> + 7 rate hikes in 2022  
+ 5 rate hikers in 2023  
+ (bonus) Fed Tightening will be announced in May (nearly $9 trillion will be sold, which will push treasury rates even higher and squeeze stock market lower) $SPY $AAPL $TSLA $MSFT $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:06:32 </td>
   <td style="text-align:left;"> $AAPL 

It’s clear the run will continue on after neg YTD is cleaned up, it will rise another 15% after neg YTD is cleared. 

Good luck this is a very strong momentum to push up higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:05:37 </td>
   <td style="text-align:left;"> $AAPL as long as the vix stays down it’ll be good for the bulls. This is a bear market rally. Tread carefully </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:03:46 </td>
   <td style="text-align:left;"> $AAPL Great job bears! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:02:34 </td>
   <td style="text-align:left;"> $AAPL can we get to $200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:02:19 </td>
   <td style="text-align:left;"> $AAPL everything hit HOD by the close but aapls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:02:17 </td>
   <td style="text-align:left;"> $AAPL below avg vol, looking weak for a continued run. short term bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:01:07 </td>
   <td style="text-align:left;"> $AAPL lots of payment plans arranged for bears today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:00:50 </td>
   <td style="text-align:left;"> $AAPL Wall Street’s biggest weapon is FEAR. Fear in the face of an uncertain future.  
  
If you sell, THEY win. .........If you hold, YOU win......CATCH UP! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 04:00:21 </td>
   <td style="text-align:left;"> $AAPL $QQQ watch the tape after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:59:51 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MSFT now that everyone went short time to go long some more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:59:23 </td>
   <td style="text-align:left;"> $AAPL letting shorties load up on borrowed shares at day end....you think the stock is too high now, just wait till next week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:58:27 </td>
   <td style="text-align:left;"> Here&amp;#39;s How Alibaba&amp;#39;s Buyback Boost Could Win Back Investors In China&amp;#39;s Internet Sector  $BABA $BIDU $JD $AAPL $FB 

https://newsfilter.io/a/ce320a624e19e23233d4e763b671deba </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:57:43 </td>
   <td style="text-align:left;"> $AAPL Shorty.......DECISION TIME 
https://www.youtube.com/watch?v=g1CLe7kIWMo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:56:33 </td>
   <td style="text-align:left;"> $AAPL well, we know it&amp;#39;s finally over.  There will be a sharp selloff again in the morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:55:08 </td>
   <td style="text-align:left;"> $AAPL $QQQ not good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:55:03 </td>
   <td style="text-align:left;"> $AAPL So aggravating seeing such a criminal pump be held up so strongly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:52:56 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:51:39 </td>
   <td style="text-align:left;"> $AAPL big green coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:51:19 </td>
   <td style="text-align:left;"> $AAPL $100-120 would be my buy point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:51:05 </td>
   <td style="text-align:left;"> $AAPL let&amp;#39;s get over $169.10. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:50:30 </td>
   <td style="text-align:left;"> $AAPL .....Mr PUTZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:49:42 </td>
   <td style="text-align:left;"> $AAPL  just  finished another game </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:49:22 </td>
   <td style="text-align:left;"> $TSLA ruling today. $SPY $QQQ $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:49:21 </td>
   <td style="text-align:left;"> $AAPL any reason for the pump? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:49:10 </td>
   <td style="text-align:left;"> $FSR Over here at Fisker there is a small portion of individuals whom believe we have the Apple car in the bag. What does the $AAPL  board think of this?  
   My reasoning. Besides the obvious partnership with Foxconn And The name of the vehicle ( the Pear). Fisker is pulling a page out of Apple and not revealing the vehicle  the Pear until two months before start of production. Apple is known to be secretive with its products. But, in the car world this is unheard of. Especially for a new company.  Exposure and brand awareness is key. Henrik Fisker expects to sell 250k Pears year one…the only way to achieve this imo, w out revealing the vehicle sooner,  is to be the Apple car. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:48:30 </td>
   <td style="text-align:left;"> “Nvidia $NVDA’s CFO Colette Kress just said there isn&amp;#39;t any update to the financial guidance it issued when it last reported earlier this year.”

$AMD ↗️ ➕ $TSLA   $AAPL | $INTC 

Nvidia unveils Grace, an Arm-based server chip - Protocol

 https://www.protocol.com/bulletins/nvidia-grace-server-chip-arm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:48:25 </td>
   <td style="text-align:left;"> $aapl stocks rebound from a 12% gain to a 14% gain! Will their be a relief rally? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:47:21 </td>
   <td style="text-align:left;"> $AAPL oh nooooooooooooo..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:47:02 </td>
   <td style="text-align:left;"> $AAPL by the time it DOES dip, your reserves will be depleted 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:46:22 </td>
   <td style="text-align:left;"> $AAPL so bears, how long do you hold and lose until you realize the errors in your ways? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:46:10 </td>
   <td style="text-align:left;"> $AAPL Geee how are those $150s looking? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:45:39 </td>
   <td style="text-align:left;"> $AAPL if you see a selloff in the last few minutes, know it&amp;#39;s just the beginning of an ugly multiday downtrend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:45:03 </td>
   <td style="text-align:left;"> $SPY $QQQ  sold $nvda pots but holding qqq and $AAPL  puts. This is getting ridiculous. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:44:51 </td>
   <td style="text-align:left;"> $AAPL easy money, BUY! $$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:44:26 </td>
   <td style="text-align:left;"> $AAPL Dude haven&amp;#39;t we seen this movie already....GL with all that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:44:05 </td>
   <td style="text-align:left;"> $aapl i think all 
these guys like Powell , Biden, trump, pelosi ( who just turned 82) , Tim Cook, bezos, Elon, Buffett, etc. are much smarter now that they may have Alzheimer’s. Thats why apples p/e is so much higher. They finally realized how worth it is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:43:58 </td>
   <td style="text-align:left;"> $AAPL last 20 mins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:43:10 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:42:48 </td>
   <td style="text-align:left;"> $GOOGL to recoooerate losses you know that moneys gonna pump into the stock market  🦍🚀🚀  lfg $SPY   $AAPL $TSLA $SPY  
 
https://www.marketwatch.com/amp/story/the-housing-market-is-in-the-early-stages-of-a-substantial-downshift-home-sales-may-drop-25-by-the-end-of-summer-according-to-this-analyst-11647884229 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:42:05 </td>
   <td style="text-align:left;"> $AAPL man you bears are desperate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:41:33 </td>
   <td style="text-align:left;"> $AAPL closing under 168 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:41:14 </td>
   <td style="text-align:left;"> $AAPL If it cant get through $169 after so many attempts, the selloff is going to be monumental. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:38:57 </td>
   <td style="text-align:left;"> $AAPL can we get little end of day power hour pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:38:01 </td>
   <td style="text-align:left;"> $AAPL They&amp;#39;re BAAAAAAAACK........ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:37:15 </td>
   <td style="text-align:left;"> $aapl stocks rebound off the 15% rally 😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:36:19 </td>
   <td style="text-align:left;"> $AAPL EZ profits, $180 by summer time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:35:30 </td>
   <td style="text-align:left;"> $AAPL rejecting 169 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:34:25 </td>
   <td style="text-align:left;"> $AAPL -10% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:34:19 </td>
   <td style="text-align:left;"> $AAPL They said $75!  🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:33:31 </td>
   <td style="text-align:left;"> $AAPL common 169.10! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:32:41 </td>
   <td style="text-align:left;"> $AAPL them bears waiting for a drop to say “I told you so!”😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:31:56 </td>
   <td style="text-align:left;"> Play the Tech-Stock Bottoming Process With Apple Stock -- article I wrote for @investorplace https://investorplace.com/2022/03/aapl-stock-play-the-tech-stock-bottoming-process-with-apple/ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:30:48 </td>
   <td style="text-align:left;"> $AAPL $TQQQ  $TSLA  gets me excited in my undies to see a reversal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:30:37 </td>
   <td style="text-align:left;"> $AAPL 
Long on apple, took some of my profits and moved them into #recaf gonna blow up by June. Moon shot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:29:47 </td>
   <td style="text-align:left;"> $ORIC in at 4.61 $SPY $AAPL $SCYX $SELB GL TO ME BULLS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:29:40 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

Easy short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:28:12 </td>
   <td style="text-align:left;"> $AAPL $170.08 &amp;amp; $176.65/176.95 are the next key resistance levels that it needs to take out. This is trading above all key MAs. Very bullish. Long and Strong 💪. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:27:59 </td>
   <td style="text-align:left;"> $AAPL double top. Apple signaling short term top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:27:41 </td>
   <td style="text-align:left;"> $SPY $AAPL last year I lost a ton of money on these two. Buying weekly spreads. This year I started too. Last week Was epic. But I said I will never touch them again.  Iv moved on and couldn’t be happier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:26:43 </td>
   <td style="text-align:left;"> $AAPL I’m not trusting this move, looks like a bear market rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:26:07 </td>
   <td style="text-align:left;"> $AAPL Putin spokesman refuses to rule out use of nuclear weapons if Russia faced an &amp;#39;existential threat&amp;#39; https://www.cnn.com/2022/03/22/europe/amanpour-peskov-interview-ukraine-intl/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:25:51 </td>
   <td style="text-align:left;"> $AMZN $AAPL $GOOGL $FB 
I can only imagine how far we will fly once Russia Conflict comes to an agreement. Load up now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:25:51 </td>
   <td style="text-align:left;"> $AAPL Only 8% away from all time highs, any doubters? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:24:37 </td>
   <td style="text-align:left;"> $TSLA latexe8909b709822f89c46c53280186bd0feSPY  Long@ 449.47  Target 452.10 Stop Loss 439.00 
Sold on 449.50 
$TSLA Long@ 949.90  Target 980.22 Stop Loss 902.11 
Sold on 991.26 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:24:30 </td>
   <td style="text-align:left;"> $AAPL wait till they announce the I Car $8T evaluation in 3 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:23:56 </td>
   <td style="text-align:left;"> $MULN apple need a new team for the apple car 🤔 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:23:00 </td>
   <td style="text-align:left;"> $AAPL H&amp;amp;S setup on daily for a dump towards close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:19:54 </td>
   <td style="text-align:left;"> @JCBinaryAnomaly ….oh hey 👋 it’s me again, I’m killing it.  Just a reminder thank you for all the money you and your boyfriends are giving me. $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:19:03 </td>
   <td style="text-align:left;"> $AAPL a drop is going to come. This can&amp;#39;t sustain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:18:38 </td>
   <td style="text-align:left;"> $AAPL buy buy buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:17:07 </td>
   <td style="text-align:left;"> $AAPL Bears can have their -0.25% day tomorrow and we march towards 175 by end of week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:16:48 </td>
   <td style="text-align:left;"> $AAPL 160 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:16:34 </td>
   <td style="text-align:left;"> $AAPL poor bears! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:16:17 </td>
   <td style="text-align:left;"> $AAPL 4T here we come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:15:02 </td>
   <td style="text-align:left;"> $AAPL $AMZN $QQQ Why is the market up? Things don’t seem great </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:14:15 </td>
   <td style="text-align:left;"> $LCID - y’all $NVDA partnership for ADS is HUUUUUUUGE!!! Far bigger than with $AAPL which is still in developmental phase AND that’s IF it happens at all. Plus, if $AAPL does halt their ADS project and still intend to produce an Apple car, which I think they will, they announcement of the Foxconn facility in  Saudi Arabia could be a great indicator that Lucid will BUILD the Apple car 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:14:11 </td>
   <td style="text-align:left;"> Unbelievable Video of a 
Truck 🛻💨+tornado🌪 

How’s your day going?!

Be grateful 🤜🏼⚡️🤛🏽

🤔 … 🙏🏼…..🇺🇦 

✌🏼

$AAPL  $AMD ↗️ $BTC.x $ETH.x $TSLA 
 https://twitter.com/brianemfinger/status/1506105724929286152?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1506105724929286152%7Ctwgr%5E%7Ctwcon%5Es1_c10&amp;amp;ref_url=https%3A%2F%2Fwww.southernliving.com%2Fnews%2Ftornado-outbreak-texas-severe-weather-forecast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:14:00 </td>
   <td style="text-align:left;"> The industry average ROE is 17.76%. $AAPL outperforms 94% of its industry peers. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:13:42 </td>
   <td style="text-align:left;"> $AAPL long here but buying a couple o Pootz just for fun tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:13:42 </td>
   <td style="text-align:left;"> Some top tech sector flow coming in above ask 
 
$QCOM - $1.1M put sweep 
$AAPL - $1.1M call sweep 
$AMD - $811K call sweep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:13:12 </td>
   <td style="text-align:left;"> latex55f34a9c074c5f02b5c7feb0f5dc6b34AMD 554k (72% call/28% put)
$BABA 517k (69% call/31% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:12:18 </td>
   <td style="text-align:left;"> $SPY $AAPL $F  mr moose says buy ford calls and puts on oil. But only if you are tired of working behind Wendy’s dumpster doing gig work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:10:39 </td>
   <td style="text-align:left;"> $AAPL dont you dare rollover. Theres too much invested! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:07:53 </td>
   <td style="text-align:left;"> $AAPL I ALMOST took my profits from calls. I think I’ll ride it out another day 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:07:48 </td>
   <td style="text-align:left;"> $AAPL at some point it&amp;#39;s going to go back down. I may be insolvent by then! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:07:23 </td>
   <td style="text-align:left;"> $AAPL 170 close tomorrow opens 171 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:07:16 </td>
   <td style="text-align:left;"> $AAPL ignore the noise. It’s gonna hit $180 in no time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:06:57 </td>
   <td style="text-align:left;"> $AAPL  &amp;quot;And by it&amp;#39;s fruits you shall know them.&amp;quot; As this Apple tree continues to bare wonderful fruit year round. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:06:54 </td>
   <td style="text-align:left;"> $AAPL will be the bill payer for covering all these options  Now sitting on cash with inflated market prices once again and inflation at historic levels.  I expect a big sell off toward the end of the day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:06:13 </td>
   <td style="text-align:left;"> $AAPL those puts aren’t looking so great </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:05:46 </td>
   <td style="text-align:left;"> $AAPL anyone else thinks it’s not breaking down (like it should)? This has been very resilient today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:05:27 </td>
   <td style="text-align:left;"> $SNDL $BBIG $AAPL $MULN  don’t miss out on this AH play at $AVCT this will run AH on this volume!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:05:14 </td>
   <td style="text-align:left;"> $AAPL final pump to 170 EOD! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:05:11 </td>
   <td style="text-align:left;"> $AAPL do we close at high of the day today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:04:58 </td>
   <td style="text-align:left;"> $DJIA $SPY  $QQQ  $BTC.X $AAPL  if Trump was still in office headline would read “ Parents praise teacher…” 

https://apple.news/AWE-qkHUmQSWlp8ukGtamOQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:02:22 </td>
   <td style="text-align:left;"> $AAPL give me 160 I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:01:14 </td>
   <td style="text-align:left;"> MSFT, AAPL, AMZN, FB, NVDA: Why Are Tech Stocks Up Today?

$MSFT $NVDA $AAPL $FB $AMZN  

https://investorplace.com/2022/03/msft-aapl-amzn-fb-nvda-why-are-tech-stocks-up-today/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 03:00:09 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple (AAPL) Resolves Massive Service Outage https://www.stck.pro/news/AAPL/24855736 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:58:49 </td>
   <td style="text-align:left;"> $AAPL time to go short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:57:34 </td>
   <td style="text-align:left;"> $AAPL If this pulls to 164 and below I&amp;#39;m the GOAT... If not, I have ALOT to learn. Got till Friday. Game on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:57:31 </td>
   <td style="text-align:left;"> $AAPL let&amp;#39;s see 160 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:54:00 </td>
   <td style="text-align:left;"> Way too high right here. I smell a crash coming $aapl $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:53:16 </td>
   <td style="text-align:left;"> $AAPL 168.30 will break this down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:51:11 </td>
   <td style="text-align:left;"> $AAPL C’mon Apple stock holders!  This bad boy should be hovering near $200.00. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:49:48 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I’VE GOT THIS PIG IN MY CROSSHAIR!🐖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:49:42 </td>
   <td style="text-align:left;"> $SPY hard to take this down if everyone refuses to stop buying $AAPL $MSFT and $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:48:15 </td>
   <td style="text-align:left;"> $BKKT will be interesting to see once $AAPL partnership announced </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:47:35 </td>
   <td style="text-align:left;"> $aapl if it came to it we could just nuke China and send poor people and prisoners to work there in factories in areas of high radiation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:46:58 </td>
   <td style="text-align:left;"> $AAPL $170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:46:51 </td>
   <td style="text-align:left;"> $AAPL power hour rocket coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:46:07 </td>
   <td style="text-align:left;"> $SPY nuke talks are bullish $TSLA $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:44:34 </td>
   <td style="text-align:left;"> $GOOGL once we split we’ll enter the Dow soon after and we’re going to rocket past $AAPL in market cap easily . Google will dominate marketing , cybersecurity, autonomy , and phone technology … $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:44:25 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL), Bank of America Corporation (NYSE: $BAC) – All The Stocks That Moved Tuesday From CNBC’s ‘Fast Money: Halftime Report’ $NKE $NVDA $PARA https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-bank-of-america-corporation-nysebac-all-the-stocks-that-moved-tuesday-from-cnbcs-fast-money-halftime-report/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:41:32 </td>
   <td style="text-align:left;"> $SPY $TSLA $BTC.X $AAPL $QQQ pause, what&amp;#39;s that headline say?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:40:58 </td>
   <td style="text-align:left;"> $AABB $SPY $QQQ $TSLA $AAPL If your not aware of $AABB  AABBG.X Exchange than you should be and quickly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:38:54 </td>
   <td style="text-align:left;"> $AAPL #TradeIdea-44496 [Apr-08 170 Calls] at $2.61 
  https://sleekoptions.com/st.aspx?ald=579f7f95-52a2-4fbb-b786-19fb609360d5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:38:17 </td>
   <td style="text-align:left;"> $GSAT $AAPL Are we on the cusp of Stewie news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:37:26 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-22 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=nadqjIc2A-M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:37:23 </td>
   <td style="text-align:left;"> $aapl buying this here could be like buying Amazon in 1995. If you don’t buy immediately you’ll miss out on 60,000% returns. Don’t wait for tomorrow it will be too late then! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:37:09 </td>
   <td style="text-align:left;"> $SPY latex4b199d0cfd90f09cde7aeefd18a114e3BABA 72% call vs 28% put 
$HYG  0% call vs 100% put </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:35:35 </td>
   <td style="text-align:left;"> $AAPL likely will simmer here for the hour and catapult to 170 before or close to closing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:35:16 </td>
   <td style="text-align:left;"> $AAPL 
-boner to 170$+? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:35:16 </td>
   <td style="text-align:left;"> $AAPL 4trillion cap in sight!!. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:34:23 </td>
   <td style="text-align:left;"> $AAPL $AMC $GME Buy at Close and Sell at Open EVERYDAY. It’s one of our top producing systems with proven Indicators to make it a no emotions trade!
See the comments to get a feel for how it works and then message us for details 

https://youtu.be/Q_oKrUdFsNM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:34:06 </td>
   <td style="text-align:left;"> latex2f1eac05944fa72d99b2c3d3f94da6c1NVDA 73% call vs 27% put 
$BABA 72% call vs 28% put </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:33:15 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m not getting shaken out. Avg is 167.

Sl is 165. Let&amp;#39;s go 200!

Easy monies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:32:53 </td>
   <td style="text-align:left;"> $AAPL dip  buying is insane! Watch for a break below 168.3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:32:01 </td>
   <td style="text-align:left;"> $SPY $AAPL  not only did i sell at the hod i bet i sold at the high of the entire bear market pump 🙃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:31:27 </td>
   <td style="text-align:left;"> $SPY SPY is 6% away from ALL TIME HIGH’s… this is just silly… 😂
bought some $SPXS  at $18.02 to hedge my longs…. 

🚨 $QQQ $SQQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:31:11 </td>
   <td style="text-align:left;"> $AAPL show time 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:30:40 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

LOAD THE POOOOOOTS!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:28:37 </td>
   <td style="text-align:left;"> $SPY $AAPL It&amp;#39;s all good, I heard the next iPhone has EMP shielding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:28:22 </td>
   <td style="text-align:left;"> $AAPL Wasn&amp;#39;t that a perfect rejection at the trend line resistance? Bears still at risk unless this closes under 50 MA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:27:37 </td>
   <td style="text-align:left;"> $AAPL $SPY I HATE MYSELF 😭😭 mark the previous post when this dips 5% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:23:46 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Here comes the final pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:23:31 </td>
   <td style="text-align:left;"> $AAPL for those LONG in AAPL; we expected this big rally, come through link in my BIO for latest updates and discussions with 18300+ other AAPL holders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:22:42 </td>
   <td style="text-align:left;"> $SPY $AAPL $OXY i can’t tell you how to be a bad bitch, but if you wanna try, buy calls now on Ford before it goes to 20.  Calls are 14.00.  Every 10c movement is 20.00 ish. And April is a good month for stocks, and down or sideways for oil.  In April I’m betting oil will go down to 70-80 a barrel.  Oxy will most likely go back to 30ish. My Personal opinion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:22:30 </td>
   <td style="text-align:left;"> $AAPL ok taking a big short positions here , who’s with me? Let do puts .. loading and avg down. It ran over 20$ to much and extended, , it won’t hold up.. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:19:57 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : XLK: Apple And Microsoft Likely To Weigh The Index Down https://www.stck.pro/news/AAPL/24854465 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:18:37 </td>
   <td style="text-align:left;"> $AAPL new all time higher highs in focus ahead of next QU/EPS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:17:57 </td>
   <td style="text-align:left;"> $AAPL hey look.. ANOTHER ANOTHER PUMP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:16:49 </td>
   <td style="text-align:left;"> $DKNG $SPY $AAPL $NVDA the only losers in the end are the hard working people of the World. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:14:45 </td>
   <td style="text-align:left;"> $AAPL winners gotta win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:14:19 </td>
   <td style="text-align:left;"> $SPY $AAPL  just warning the world i just sold all of my puts. i am the best indicator of a crash sorry if youre holding calls right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:12:33 </td>
   <td style="text-align:left;"> $AAPL just a reminder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:12:20 </td>
   <td style="text-align:left;"> $AAPL 180 before ER? and then the same old story of gradually coming down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:11:57 </td>
   <td style="text-align:left;"> $AAPL odds this gets to 180 eow? I’d be a millionaire if that happens with my 1000 contracts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:11:14 </td>
   <td style="text-align:left;"> $AAPL bunch of bologna .. $160 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:10:09 </td>
   <td style="text-align:left;"> $aapl guys dont worry China is only sending diapers to Russia . They will stop there and not send anything sharper than a baby’s spoon per the foreign minister </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:07:26 </td>
   <td style="text-align:left;"> $AAPL those technical traders probably sold their calls at 12-17% profit thinking they have won the grand prize, meanwhile I’m up over 50% and counting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:05:44 </td>
   <td style="text-align:left;"> $AAPL feeling toppy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:03:11 </td>
   <td style="text-align:left;"> $AAPL oh yeaaa

Got 500 shares at 167. This is easy money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:03:06 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #1 stock that institutions are trading with 71.6K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:02:42 </td>
   <td style="text-align:left;"> $aapl can you imagine the relief rally if China sends troops to Ukraine? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:01:33 </td>
   <td style="text-align:left;"> $AAPL 165p and $TSLA 900p if you have a brain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:01:28 </td>
   <td style="text-align:left;"> $AAPL While this is a bear market rally for the indexes, Apple should have one more new ATH to be complete. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:01:04 </td>
   <td style="text-align:left;"> $AAPL This is my favorite stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:00:58 </td>
   <td style="text-align:left;"> $AAPL Who closed out their 172.5 calls this morning at .13? This guy. Scared money.. 🤦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:00:56 </td>
   <td style="text-align:left;"> On 3/14 $AAPL hit weekly demand. I bought the 4/14 160 calls in the 2.00s and sold for a loss same day as I expected market to go lower. Well, that was the bottom. Those calls are now at 11.00 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:00:46 </td>
   <td style="text-align:left;"> $AAPL 160. Give me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 02:00:42 </td>
   <td style="text-align:left;"> @DiscountBounce Tappin dat App $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:59:57 </td>
   <td style="text-align:left;"> $AAPL C&amp;#39;mon $170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:59:20 </td>
   <td style="text-align:left;"> $AAPL biden voters should be deported </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:58:53 </td>
   <td style="text-align:left;"> $AAPL erupt already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:58:33 </td>
   <td style="text-align:left;"> $AAPL Crazy market, easy money, LOAD UP! $$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:58:23 </td>
   <td style="text-align:left;"> $LCID - from a “tech” standpoint $NVDA is a WAAAAAAAAY better option. From a name brand recognition, $AAPL is better; but that doesn’t mean they don’t still partner to build. Can you imagine $NVDA AND $AAPL 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:57:02 </td>
   <td style="text-align:left;"> $AAPL sold my calls a way to early 😑 
now my only choice is to catch a overnight put or just wait for drop an buy calls again. 😪🤦🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:56:53 </td>
   <td style="text-align:left;"> $AAPL 200 by Thursday 🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:56:38 </td>
   <td style="text-align:left;"> $AAPL there will be good news out of Ukraine any day now. Just keep going up 3% a day to beyond the record high and eventually you will catch the half percent ceasefire relief rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:55:36 </td>
   <td style="text-align:left;"> $UVXY $SPY $GME $AAPL new strategy is to just short the Vix above $30-35 on steep market drops and buy long cheap calls all the way down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:55:10 </td>
   <td style="text-align:left;"> $AAPL  RSI is only 57 &amp;amp; this is in a lovely cup that will breakout as this is in an Elliott wave 1 with plenty of room to run with the McClellan pulling back nicely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:55:08 </td>
   <td style="text-align:left;"> $AAPL hey look.... ANOTHER PUMP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-23 01:54:08 </td>
   <td style="text-align:left;"> $AAPL Chinese and Russian people should do their part and buy the newest iPhone this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:12:05 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!!  Simulated Weekly $995.0 CALLS for Wednesday&amp;#39;s open on StockOrbit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:10:48 </td>
   <td style="text-align:left;"> $TSLA 

Up today massively across all my accounts - all my peeps got fed today as well !! 

🙏🏻🐉🦅🕺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:10:46 </td>
   <td style="text-align:left;"> $ALB IT´s a great Company but if you are interested in an European Lithium Project check this out $EULIF i am already invested. Any relevent news are in the Discussion. Because of $TSLA Opening in Berlin the Focus is more and more on Lithium Battery Projects in Central Europe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:09:58 </td>
   <td style="text-align:left;"> $TSLA TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:09:12 </td>
   <td style="text-align:left;"> $amc $gme $wish $negg latexb97e966ec903710f267bce91b120722dNVDA
$COIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:07:40 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $SQ $SNOW 
Rug Pull starts tomorrow 👻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:07:14 </td>
   <td style="text-align:left;"> $BTC.X If we go into a recession, this will nearly go to zero $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:07:03 </td>
   <td style="text-align:left;"> $BTC.X if this POS breaks 40k before open tomorrow. GOOD FUCKIN RIDDANCE $AAPL $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:06:50 </td>
   <td style="text-align:left;"> $TSLA sorry I meant 965 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:05:11 </td>
   <td style="text-align:left;"> $TSLA About 11% untill next resistance, i think its possible we test it this week 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:04:12 </td>
   <td style="text-align:left;"> Is there any decent electric car company besides $TSLA ??? $CENN is a contender for a top spot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:03:47 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:03:36 </td>
   <td style="text-align:left;"> $TSLA DRUNK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:01:00 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 09:00:44 </td>
   <td style="text-align:left;"> $TSLA mildly hilarious that this company is back up to a 1T valuation despite all the headwinds on the horizon. Just plow more cash in this pig. I’m sure it will end well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:59:53 </td>
   <td style="text-align:left;"> $SPY $TSLA

Are you that guy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:58:35 </td>
   <td style="text-align:left;"> $TSLA you charmin clean shit bears are awfully quite lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:56:08 </td>
   <td style="text-align:left;"> $TSLA Pari Strategy in the last few days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:55:31 </td>
   <td style="text-align:left;"> $TSLA 1000 is just right around the corner. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:54:43 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/bmyvjzBGc1M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:51:38 </td>
   <td style="text-align:left;"> $TSLA I know everyone would love another day tomorrow to be like today but it’s gonna be mild day, we have to go down in order to go higher 865 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:50:33 </td>
   <td style="text-align:left;"> $TSLA definitely seeing $1050 before ER. Tomorrow could be that day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:49:00 </td>
   <td style="text-align:left;"> $TSLA is one of the better performing stocks in the Automobiles industry. https://www.chartmill.com/stock/quote/TSLA/technical-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:48:45 </td>
   <td style="text-align:left;"> GME options: +2000% move today 
$TSLA options +600%  $QQQ $SPY $AAPL $BABA 
CLICK HERE to learn how to trade options profitably 
https://goldentrading.website/work-from-home-jobs-stock-trading-courses-for-beginners-learn-how-to-trade-stocks-and-make-1000-a-day-from-home/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:48:42 </td>
   <td style="text-align:left;"> $TSLA From a technical perspective, I&amp;#39;m curious why you wouldn&amp;#39;t be a buyer of puts near 1000. It&amp;#39;s been a great run, but I&amp;#39;m curious from a technical perspective why you believe it&amp;#39;s better to be in calls then puts when we&amp;#39;re right near an area of resistance. I love Tesla, just interested in hearing more about the technical analysis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:48:42 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/INVSTRSTrading/status/1506432220021501956?s=20&amp;amp;t=zB35NTVvw6exAFvrlWv65g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:47:01 </td>
   <td style="text-align:left;"> $amc $gme $qqq $tsla $btc.x https://www.youtube.com/watch?v=TDnkmlk8ngo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:44:37 </td>
   <td style="text-align:left;"> $TSLA looks like another green day tomorrow wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:40:11 </td>
   <td style="text-align:left;"> $GME An institution/(s) will lose their GME shares tomorrow and will not be able to recover them if this stock doesn&amp;#39;t go under 120 by 4/14/22 (pic in tweet). 
 
They never learn... 
 
https://twitter.com/MeisaBonelli/status/1506429920003641344?s=20&amp;amp;t=n6qbIZHsLndjPcgq6grWLA 
 
$TSLA $QQQ $AMC $MULN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:36:32 </td>
   <td style="text-align:left;"> $TSLA $1,030 premarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:35:58 </td>
   <td style="text-align:left;"> $TSLA this type of history is legendary https://twitter.com/teslahistorian/status/1506407368824958979?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:35:53 </td>
   <td style="text-align:left;"> $TSLA 52 week low.
Tomorrow.

🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:34:40 </td>
   <td style="text-align:left;"> $TSLA bulls tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:34:37 </td>
   <td style="text-align:left;"> $TSLA so wtf price we goin to tmrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:33:47 </td>
   <td style="text-align:left;"> $TSLA bears tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:33:17 </td>
   <td style="text-align:left;"> $TSLA - This was an incredible move here today on Tesla. Chart was primed for a run up. But let me tell you the best part it&amp;#39;s not done yet. We may see a continuation heading into the close of March month. 

Btw bulls here who follow Elon, better follow
https://www.sweepcast.com/ as the flow on the unusal options activity alerted was pretty much on spot. Fall-o for more, lync in bayu 😉 #stockstowatch #options #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:32:26 </td>
   <td style="text-align:left;"> $TSLA Bleeding Bears spilling bile after hours after being slaughtered 3 days in a row. Understandable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:32:05 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-22 Chart Analysis Video: 
https://www.youtube.com/watch?v=zSHfYlymq_c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:32:04 </td>
   <td style="text-align:left;"> $TSLA I guess Yahoo finance will have to retract their gleefull story about how Elon was no longer a $200 billionaire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:29:56 </td>
   <td style="text-align:left;"> $TSLA inflation is a byproduct of a rapidly growing economy in which demand outweighs supply!! Its like me buying 40.00 a pound dry-age steaks at union market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:29:23 </td>
   <td style="text-align:left;"> $TSLA 

Slow &amp;amp; steady is the name of the game!
Thats how its done! 🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:28:56 </td>
   <td style="text-align:left;"> $TSLA
 https://www.forbes.com/sites/jonathanponciano/2022/03/22/pelosi-exercises-tesla-stock-options-to-buy-2-million-in-shares/amp/

Lord dumpinginton to 950 tomorrow then bounce😘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:22:36 </td>
   <td style="text-align:left;"> $TSLA any one holding puts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:22:19 </td>
   <td style="text-align:left;"> $TSLA  bears once a bitch always a bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:21:14 </td>
   <td style="text-align:left;"> $TSLA TOMORROW IS GONNA BE LIKE AN ORGY FILLED WITH TACOS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:17:29 </td>
   <td style="text-align:left;"> $TSLA stock analysis based on today&amp;#39;s closing price 

https://youtu.be/Ljw5wvskVIc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:17:12 </td>
   <td style="text-align:left;"> $TSLA SMR says 1700 base case by EOY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:17:04 </td>
   <td style="text-align:left;"> $TSLA anyone notice a difference with regen braking with latest update? It mentions regen efficiency with AP but I’m noticing it when I’m not on AP also it’s just not as harsh and seems smoother and more efficient </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:16:00 </td>
   <td style="text-align:left;"> $TSLA 

Wall Street analysts expect the European facility will produce 100,000 vehicles this year, and Tesla says it will make up to 500,000 vehicles and millions of battery cells in future years. Wall Street now expects Tesla to deliver 1.5 million units in 2022, up from 936,000 last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:13:19 </td>
   <td style="text-align:left;"> $TSLA I just need 10000 shares and I can stop working for the man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:12:28 </td>
   <td style="text-align:left;"> $TSLA 

Incredible day in my Small Account Challenge discord today! I am sure ya’ll banked hard on TESLA today! What a beast!🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:12:13 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:11:46 </td>
   <td style="text-align:left;"> $TSLA TESLA Stock Price  Prediction and Analysis for Tomorrow Wednesday March 23
https://youtu.be/OpE3HOwckUQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:08:56 </td>
   <td style="text-align:left;"> $TSLA 
Yo yo yo!!!!
What a Day ☺️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:08:34 </td>
   <td style="text-align:left;"> $TSLA Here is the unusual activity on sweepcast.com/ as I mentioned in my previous post. #options #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:08:30 </td>
   <td style="text-align:left;"> $TSLA https://ftx.com/intl/trade/TSLA/USD

You bears are fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:07:54 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $BTC.X calling it now, starting tomorrow till the end of the month the market will know pain. But will rebound and break ATHs there after. better start hedging your portfolio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:07:35 </td>
   <td style="text-align:left;"> $TSLA I keep having visions of that model S flying through the air today 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:07:32 </td>
   <td style="text-align:left;"> $TSLA so market is back to normal all of the sudden? What happened to the war and inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:06:56 </td>
   <td style="text-align:left;"> $TSLA Great Bullish Setup!! Channel Breakout!! Looking at the daily chart, the stock has broken descending channel pattern trend with a huge volume. The stock is close above the 20D,50D, and 200D  SMA  levels. RSI is in the sweet spot...The stock is starting to bounce. sweepcast.com/ #stockstowatch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:06:16 </td>
   <td style="text-align:left;"> $LLKKF  so cool how many people came over to $EULIF it will have the same story like LAKE  but it has a mine and is in the heart of CENTRAL EUROPE if you have any questions feel free to ask. Since $TSLA openend their GIGA Factory yesterday Lithum Stocks in Europe are skyrocketing.... i thought i should mention that as a german and i love Dragon Ball Z </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:05:37 </td>
   <td style="text-align:left;"> $TSLA figurehead management Chinese government planning buyout within 10yrs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 08:02:21 </td>
   <td style="text-align:left;"> latexe2073a4c3a0a0d0e5e582335228cab9fNIO
$F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:59:04 </td>
   <td style="text-align:left;"> $TSLA company wasn&amp;#39;t built to last </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:58:20 </td>
   <td style="text-align:left;"> $TSLA https://www.forbes.com/sites/jonathanponciano/2022/03/22/pelosi-exercises-tesla-stock-options-to-buy-2-million-in-shares/
😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:57:36 </td>
   <td style="text-align:left;"> $TSLA today action is because of Berlin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:57:34 </td>
   <td style="text-align:left;"> $ALLG Wednesdays been bullish. New highs tomorrow for $allg and $BRK.B .  should see 4 digits tomorrow for $tsla.  It is possible to see $allg touch $20 tomorrow. Open 12.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:56:22 </td>
   <td style="text-align:left;"> $TSLA I hate short sellers and I love my model Y performance.  I hope they all lose a crap ton of capital. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:56:15 </td>
   <td style="text-align:left;"> $SPY oh NANCY!!! you wicked witch of the DEMORATS  
 
She fights harder to DAYTRADE than for the Merican ppl she was elected to serve!  $XLF $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:56:07 </td>
   <td style="text-align:left;"> $TSLA congrats bulls from a broke bear 😢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:56:01 </td>
   <td style="text-align:left;"> $TSLA will see how tomorrow goes… holding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:55:22 </td>
   <td style="text-align:left;"> $TSLA
😎😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:54:30 </td>
   <td style="text-align:left;"> $TSLA this run is long long time coming. So no it’s not going to stop till 1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:53:46 </td>
   <td style="text-align:left;"> $TSLA MMs will run the market when they want and tank it according to their timeline all the media FUD is just an excuse for them to use for their fairy tale story .. what makes you think all of a sudden Ukraine news died down/disappeared before there was constant daily updates..  seems like the big boys want the market to run for now.. so will buy any dips to take advantage of this window if we get any ☺️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:53:15 </td>
   <td style="text-align:left;"> $TSLA pull back to 950 will be healthy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:50:44 </td>
   <td style="text-align:left;"> $TSLA long time waiting. It comes at the right time... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:50:05 </td>
   <td style="text-align:left;"> $TMC Deep sea mining is the future. There will be many people in denial betting against it just like there was people betting against $TSLA for years until they caved into the inevitable. In the meantime, the bears tried to scare away investors . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:49:48 </td>
   <td style="text-align:left;"> $TSLA Cramer just said this will have a big run. Pelosi just exercised her calls. Sounds like Pelosi dumping tomorrow and the Cramer curse continues. Puts at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:49:25 </td>
   <td style="text-align:left;"> $TSLA What do you call a Tesla Bear? 

A broke bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:48:21 </td>
   <td style="text-align:left;"> $TSLA stairs down, elevators up bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:48:03 </td>
   <td style="text-align:left;"> $TSLA $SPY 

WTF I haven’t gotten a single update, paid over a year ago, and they already jacking the price up and blaming it on “inflation.”  GTFOH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:46:58 </td>
   <td style="text-align:left;"> $TSLA Time to burn shorties. Like you always do </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:46:28 </td>
   <td style="text-align:left;"> $SPY - $TSLA Merica the Bootyful! 💀🙋‍♂️ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:45:27 </td>
   <td style="text-align:left;"> $TSLA wen moon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:44:40 </td>
   <td style="text-align:left;"> $TSLA $1000 tomorrow PM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:43:48 </td>
   <td style="text-align:left;"> $TSLA it’s going to go up, 🤔🤧 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:43:48 </td>
   <td style="text-align:left;"> $TSLA $1040 by open and $1160 by Thursday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:43:34 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:43:22 </td>
   <td style="text-align:left;"> $TSLA pull back tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:42:37 </td>
   <td style="text-align:left;"> $TSLA 1150 tomorrow?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:40:41 </td>
   <td style="text-align:left;"> $TSLA once I seen Elon dancing in front of that car today I bought more shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:40:26 </td>
   <td style="text-align:left;"> $TSLA if it turns green right before close I&amp;#39;ll bust out laughing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:38:00 </td>
   <td style="text-align:left;"> $TSLA, $ALB and $MRNA are the top gainers in the S&amp;amp;P500 for the day. https://www.chartmill.com/stock/stock-screener?v=3&amp;amp;f=ind_22&amp;amp;s=pt&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_top_S&amp;amp;P500_gainers&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:37:48 </td>
   <td style="text-align:left;"> $TSLA Wen Giga Austin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:37:23 </td>
   <td style="text-align:left;"> $TSLA  Break above 996 we&amp;#39;ll see 1108 quick. It&amp;#39;s tesla we can run 100 dollars with a short squeeze and zero problem </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:37:01 </td>
   <td style="text-align:left;"> $TSLA has this ever had 6 straight green days in history? damn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:36:43 </td>
   <td style="text-align:left;"> $TSLA 
Wedbush analyst Daniel Ives on Monday maintained an Outperform rating and $1,400 price target on Tesla shares.

https://www.benzinga.com/markets/cryptocurrency/22/03/26246566/whats-going-on-with-tesla-shares-on-tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:35:01 </td>
   <td style="text-align:left;"> $TSLA   
SEC says it has authority to subpoena $TSLA  and Elon Musk about his tweets, and that Musk’s move to throw out a 2018 court agreement that his tweets be preapproved is not valid.  
https://www.washingtonpost.com/business/economy/sec-says-it-has-authority-to-subpoena-tesla-and-musk/2022/03/22/10c717be-a9e7-11ec-8cd0-235f7b9ebf4f_story.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:34:11 </td>
   <td style="text-align:left;"> $TSLA 1040 tomorrow for fun! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:32:11 </td>
   <td style="text-align:left;"> Musk sees $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:31:32 </td>
   <td style="text-align:left;"> $TSLA  
$800 4/1 putters gone print like WOAH...  #GlobalMoneyTraders #aka #GMT #bihhhhhhhhhh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:30:43 </td>
   <td style="text-align:left;"> $RCKTF $EULIF are German Austrian Lithium Producer Companies close to $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:29:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $AMZN $FB 
👇 When you buy the RIP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:29:17 </td>
   <td style="text-align:left;"> $TSLA 

I hope the SEC goes after Elon with the harshest penalties and never stops.

He WILL pay his fair share. In taxes or fines to the SEC. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:29:13 </td>
   <td style="text-align:left;"> latex2bd00fe7304ce516195df921174b980cBABA - 64% call flow 
$NVDA - 69% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:27:18 </td>
   <td style="text-align:left;"> $TSLA did elon give hints about master plan in his speech at giga factory? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:25:31 </td>
   <td style="text-align:left;"> $TSLA  confused what&amp;#39;s this Mulan nonsense. Is this like that other one that was suppose to rival Tesla and they showed a truck plugged in at the car show. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:24:05 </td>
   <td style="text-align:left;"> $TSLA $SPY 
 Buy SQQQ instead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:21:35 </td>
   <td style="text-align:left;"> $TSLA Will Tesla try to acquire $MULN who knows but thier 600 hr power technology is getting peoples attention and Tesla has not made any buyouts and should start thinking about taking out competition before they get to big. 
https://www.reddit.com/r/wallstreetfools/comments/tivr11/just_remember_what_carbuzz_said_when_your/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:20:14 </td>
   <td style="text-align:left;"> $TSLA https://www.tradingview.com/chart/TSLA/C6UGBPSa-Tesla-breakout-well-above-50-and-200-MA/ 
If we break $1000 resistance wall, it is over for bears. I am not even joking. I personally think, we will see a small pull back then shot through that resistance . Chart speak for itself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:20:08 </td>
   <td style="text-align:left;"> Daily Market Recap for Tuesday 3/22/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/ncL-c8v3PQQ

$AAPL $AMD $TSLA $RBLX

Tech pop sustainable?   Tough to know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:20:01 </td>
   <td style="text-align:left;"> $TSLA rsi over 70 bears?

See you when the rsi hits 99 again and the stock still keeps going

New age of investors put their money where money is being maxe. Not where fundamentals say it might make money. 

Follow the trend don’t fight it. Simple as that. 

Earnings coming in hot too as well as giga texas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:19:53 </td>
   <td style="text-align:left;"> $TSLA does it breathe tomorrow or blow through $1k?? 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:19:51 </td>
   <td style="text-align:left;"> $TSLA bought 880 puts April 16 plz baby Jesus drop it just to 950 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:19:43 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m So Happy right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:19:37 </td>
   <td style="text-align:left;"> $TSLA autistic british man whose family owns large emerald mine stutters his way through interviews and excites the normies. He is totally not a government agent meant to happily roll out the digital control over our movements. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:18:25 </td>
   <td style="text-align:left;"> $TSLA took tsla 24-26 days to lose $300 billion in market cap… but only 6 days to gain that $300 billion back and bulls still complain it’s not enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:18:24 </td>
   <td style="text-align:left;"> $TSLA that’s only the beggining. We are still early in EV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:18:08 </td>
   <td style="text-align:left;"> $TSLA I would like 10000 shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:17:50 </td>
   <td style="text-align:left;"> $TSLA Tesla has about 38 stores in Germany, 31 stores in China, 29 stores in the United Kingdom, 19 stores in France, 19 stores in Switzerland, 12 stores in the Netherlands, 14 stores in Canada, and about 16 stores in Norway. Should be pumping out $3,000 per share. Someone is holding this beast back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:17:34 </td>
   <td style="text-align:left;"> $spy $qqq $cqqq $tsla $arkk https://www.youtube.com/watch?v=xAAeLHUWyMk&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:17:07 </td>
   <td style="text-align:left;"> $ADBE $TSLA $BABA  
 
                                   $$$ 
Start trading over 4 month ago and i lost all of money, Now I&amp;#39;ve made over $236K+ profits after join their chat room and using their alerts. Highly recommended///:-   livestktrading.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:16:54 </td>
   <td style="text-align:left;"> $TSLA 5000 a share, jesus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:15:21 </td>
   <td style="text-align:left;"> $TSLA still so much fear - kind of feel sorry for those who are missing out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:12:35 </td>
   <td style="text-align:left;"> $TSLA the market is getting irrationally exuberant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:12:34 </td>
   <td style="text-align:left;"> $TSLA is this a sell the news  situation or not? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:12:09 </td>
   <td style="text-align:left;"> $TSLA https://j.gifs.com/Vv5MAW.gif </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:11:53 </td>
   <td style="text-align:left;"> $SPY $QQQ all we need now for the time travel machine back to 2021 is for Elon to tweet #STONKS $GME $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:10:42 </td>
   <td style="text-align:left;"> $GAN $TSLA $PAGS Start trading over 4 month ago and i lost all of money,, Now I&amp;#39;ve made over $147K+ profits after join their chat room and using their alerts... Highly recommended!!  🚀 livestktrading.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:10:02 </td>
   <td style="text-align:left;"> $TSLA was this a surprise I thought this would be priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:09:28 </td>
   <td style="text-align:left;"> $TSLA $MULN $RIVN $LCID $FSR NEW ARTICLE : Pelosi Exercises Tesla Stock Options To Buy $2 Million In Shares  ….. stck.pro/news/TSLA/24861456 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:09:18 </td>
   <td style="text-align:left;"> $TSLA Opens a factory 3 years late = +100 bln market cap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:08:18 </td>
   <td style="text-align:left;"> $TSLA even if u sell price will go up lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:07:38 </td>
   <td style="text-align:left;"> $TSLA thinking this should push over a thousand yay or nay oh, I think it&amp;#39;s been green for 8 days in a row🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:07:30 </td>
   <td style="text-align:left;"> $TSLA any news as to why this blew up today? Glad to see this come back up bought in at 1k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:06:22 </td>
   <td style="text-align:left;"> $TSLA imagine running Tesla in this Macro environment and your Margins are going up, next level management, easy buy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:06:00 </td>
   <td style="text-align:left;"> $PLUG Power Todd on existing deals… 
 
EUROPE SHOULD TRIPLE!!!! 
 
$tsla $arkk $msft $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:05:40 </td>
   <td style="text-align:left;"> $TSLA $CSCO $INTC $AMD $BA NEW ARTICLE : Pelosi Exercises Tesla Stock Options To Buy $2 Million In Shares stck.pro/news/TSLA/24861456 ….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:04:39 </td>
   <td style="text-align:left;"> $TSLA $1200? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:04:12 </td>
   <td style="text-align:left;"> $TSLA Remember when this moved +33% in 6 days? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:04:09 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Pelosi Exercises Tesla Stock Options To Buy $2 Million In Shares stck.pro/news/TSLA/24861456 … $PYPL $ZM $CRWD $CMG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:02:07 </td>
   <td style="text-align:left;"> $AEI  $TSLA     AEI ,,,,Alset eHomes builds houses,,,  Tesla Solar... And a Tesla vehicle included </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:01:54 </td>
   <td style="text-align:left;"> $TSLA today was awesome </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:01:53 </td>
   <td style="text-align:left;"> $TSLA Knocking on the $1000 door! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:01:40 </td>
   <td style="text-align:left;"> $TSLA the up channel on weekly and daily shows that $1400 -$1600 could come in play. Not tomorrow but 1-3 months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:01:38 </td>
   <td style="text-align:left;"> $QQQ $SPY so $tsla gained ~$300 bil in market cap within 6 days… but the squeeze is just starting? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:01:29 </td>
   <td style="text-align:left;"> Does World’s Richest Man Elon Musk Live Frugally? https://www.billionaireclubcollc.com/does-worlds-richest-man-elon-musk-live-frugally/ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:01:29 </td>
   <td style="text-align:left;"> $TSLA Does World&amp;#39;s Richest Man Elon Musk Live Frugally? 

https://newsfilter.io/a/edf2308cc067e91ab889edf0e17674f6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:00:48 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Pelosi Exercises Tesla Stock Options To Buy $2 Million In Shares stck.pro/news/TSLA/24861456 .. $FB $NFLX $AAPL $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:00:29 </td>
   <td style="text-align:left;"> $GME $KOSS $TSLA $$HYMC $$AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:00:24 </td>
   <td style="text-align:left;"> $TSLA 🚀🚀🦇⏰🧸🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:00:19 </td>
   <td style="text-align:left;"> $TSLA am going to leave this here. 

If you wish to follow on twitter @optionboys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:00:17 </td>
   <td style="text-align:left;"> $TSLA things not gona stop til 1045 , woof </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 07:00:03 </td>
   <td style="text-align:left;"> $TSLA Yep 👍 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:59:48 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Pelosi Exercises Tesla Stock Options To Buy $2 Million In Shares . stck.pro/news/TSLA/24861456 $AMZN $SHOP $NVDA $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:59:37 </td>
   <td style="text-align:left;"> $TSLA 🚀⏰🦇🤑😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:59:14 </td>
   <td style="text-align:left;"> $TSLA 🚀⏰🦇🧸🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:59:14 </td>
   <td style="text-align:left;"> Elon Musk announces Tesla is working on new manganese battery cell - Electrek $TSLA  https://apple.news/AChptOhlASp-y2A-4w071lw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:59:09 </td>
   <td style="text-align:left;"> $GME $AMC $BABA $TSLA While the market is closed let&amp;#39;s pump up that doge? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:59:02 </td>
   <td style="text-align:left;"> $TSLA definite pullback tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:58:58 </td>
   <td style="text-align:left;"> $TSLA oversold tomorrow ($1K+) then a retrace (down) Thursday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:58:15 </td>
   <td style="text-align:left;"> $Tsla $CGC  $amc $gme $Tlry. Great Start for TLRY looks like the WSB boys are at it again back to $10 we go. 🚀🚀🚀🚀🚀🚀🚀 right @WSBChairman @pac0369 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:57:55 </td>
   <td style="text-align:left;"> $CENN  $TSLA $RIVN $MULN  
CENN Running AH huge up 0.14  
 
Two investors conferences 13D filings coming or bigger news of Jax facility opening PR !!  
 
https://www.bakersfield.com/ap/news/cenntro-to-participate-at-upcoming-investor-conferences/article_50b60518-9332-54f3-9dc6-f0d340477390.html 
https://finance.yahoo.com/news/cenntro-electric-acquires-majority-interest-133100188.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:57:43 </td>
   <td style="text-align:left;"> $TSLA 

It’s the AH cup for me 😆 

I love this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:56:44 </td>
   <td style="text-align:left;"> $LULU $AMC $TSLA Lululemon released their first shoes today and it got 0 attention. Some sizes already sold out online. ER Friday. Perfect setup. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:56:23 </td>
   <td style="text-align:left;"> $TSLA Bears luv covering over $1050+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:56:10 </td>
   <td style="text-align:left;"> $TSLA SUCK IT BEARS

Told you MFS 

No lube tomorrow. This 800-950 puts go to zero. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:55:53 </td>
   <td style="text-align:left;"> $TSLA 
I stand firm that tesla will see 1200+ soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:55:50 </td>
   <td style="text-align:left;"> $TSLA  YAAAAAAAS!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:55:25 </td>
   <td style="text-align:left;"> $TSLA $SPY 

We’re rich </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:55:00 </td>
   <td style="text-align:left;"> $TSLA 🔒 https://finance.yahoo.com/news/tesla-place-time-stock-investors-205907015.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:54:54 </td>
   <td style="text-align:left;"> $TSLA 950 &amp;amp; under tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:54:49 </td>
   <td style="text-align:left;"> $TSLA damn I should have sold my calls. This is probably going to continue tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:54:40 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #2 ticker with sweep activity where institutions are trading options urgently with 47.4K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:54:39 </td>
   <td style="text-align:left;"> $TSLA I took call profits n bought 2k worth puts 2 weeks out. rip my puts but had to yolo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:54:23 </td>
   <td style="text-align:left;"> $TSLA crazy gains just off 2 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:54:21 </td>
   <td style="text-align:left;"> $TSLA Down 98 cents, bears ”cRaShInG” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:53:42 </td>
   <td style="text-align:left;"> $TSLA So is tesla accepting doge again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:53:38 </td>
   <td style="text-align:left;"> $GME $TSLA I knew something crazy was stirring in the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:53:12 </td>
   <td style="text-align:left;"> $TSLA almost green🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:53:11 </td>
   <td style="text-align:left;"> $TSLA ⚡️🔌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:53:02 </td>
   <td style="text-align:left;"> $TSLA what puts u bought for memes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:52:35 </td>
   <td style="text-align:left;"> $TSLA lmfaooooooooooo my 1200 lottos (2) might actually rip wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:52:10 </td>
   <td style="text-align:left;"> $MULN  
BATTERY TECHNOLOGY 
&amp;quot;Elon Musk says batteries will be a limiting factor for $TSLA  in 2-3 years&amp;quot; 
https://twitter.com/MarketRebels/status/1506387724877635596?t=AhmE7zyClR9bF62tlbFbMg&amp;amp;s=19 
NOT FOR MULLEN TECHNOLOGIES !!! 
#INVESTMENT #DOTHERESEARCH #BUYANDHOLD 
NEWSROOM Feb. 28, 2022– via InvestorWire 
EV Manufacturer Mullen Announces Progress on Solid-State Polymer Battery Pack Development 
https://news.mullenusa.com/ev-manufacturer-mullen-announces-progress-on-solid-state-polymer-battery-pack-development </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:52:06 </td>
   <td style="text-align:left;"> $TSLA over 1000 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:50:10 </td>
   <td style="text-align:left;"> $TSLA must watch.  Gordon knows exactly what the deal is.  Seems like a very smart guy.  

https://twitter.com/squawkcnbc/status/1506224604024557571?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:50:09 </td>
   <td style="text-align:left;"> $TSLA 
Cup on the daily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:50:01 </td>
   <td style="text-align:left;"> $TSLA undervalued should be higher then amazon share price $3,000+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:49:47 </td>
   <td style="text-align:left;"> $DPRO stock analysis!

$aapl $tsla $amc $gme </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:48:28 </td>
   <td style="text-align:left;"> *****GAMMA SQUEEEEEZE***** 
 
$SPY $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:48:03 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:47:36 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Pelosi Exercises Tesla Stock Options To Buy $2 Million In Shares stck.pro/news/TSLA/24861456 $QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:47:05 </td>
   <td style="text-align:left;"> Tesla to provide Megapacks for 300MWh project with Australia&amp;#39;s Edify Energy - TESLARATI $TSLA  https://apple.news/AnnPdc1jBR6--_VaTbC4qUQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:47:00 </td>
   <td style="text-align:left;"> $TSLA was analyzed by 49 analysts. The buy consensus is at 71%. So analysts seem to be mildly confident about $TSLA. https://www.chartmill.com/stock/quote/TSLA/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:46:45 </td>
   <td style="text-align:left;"> Tesla stock up as Elon Musk cuts ribbon on Berlin Gigafactory expected to produce 500,000 vehicles a year - MarketWatch $TSLA https://apple.news/ASabzqMAoRZuhomZYUdna_Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:46:17 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Pelosi Exercises Tesla Stock Options To Buy $2 Million In Shares https://www.stck.pro/news/TSLA/24861456 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:45:25 </td>
   <td style="text-align:left;"> $TSLA join the party. $HYMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:44:18 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;ve always wanted to learn more about US stocks. Can you private message me to share information with each other? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:44:12 </td>
   <td style="text-align:left;"> $TSLA about to go 
oositive afterhours 💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:44:06 </td>
   <td style="text-align:left;"> $TSLA y’all ready to go green AH

I’ll laugh so hard 😂 

🐻 pathetic AF today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:43:43 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow. 
 
https://youtu.be/lOBaOeEyFkI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:43:31 </td>
   <td style="text-align:left;"> $TSLA  looks like Tesla is about to have another Green Day tomorrow. That’s what? 7 in row? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:43:06 </td>
   <td style="text-align:left;"> $TSLA NEWS - TSLA Opens German Gigafactory For Production: 
https://www.youtube.com/watch?v=trcIVo8t_cs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:42:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $ETC.X $TSLA 
 
There are still currently around ~17.2 million active cases in the US, out of a total of ~81.5 million since the start of the pandemic. 
 
The previous two waves peaked at around ~8.5 million and ~9.1 million respectively, so remains roughly twice as high as it&amp;#39;s ever been prior to Omicron and ~20% of total cases since the pandemic started. 
 
Given how mild Omicron was I&amp;#39;m not too worried about this figure, more concerned with BA.2 (roughly twice as infectious as Omicron, risks less known) and Deltacron (a &amp;quot;recombinant virus&amp;quot; taking genetic code from both Delta and Omicron mutations) spreading in the US. 
 
More info about BA.2 in my post below where I&amp;#39;ve been tracking its spread in South Korea, Deltacron is newer but I&amp;#39;m still keeping a close eye on new research about it. 
 
https://stocktwits.com/Fundy_OracleOfAlpha/message/445469326 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:42:31 </td>
   <td style="text-align:left;"> $MNSEF $TSLA  https://twitter.com/deitaone/status/1506387557369749511?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:42:27 </td>
   <td style="text-align:left;"> $TSLA 1160👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:42:19 </td>
   <td style="text-align:left;"> $SPY RISK VS REWARD is on Bears side now🙋‍♂️💰📈📉.. $450 (even $454 topside *extreme bull case $457 DBL TOP) RES - obvious Pivot 🧱👀 
 
I BOUGHT NO🚫 PUTS TODAY! however spent the day charting for my next gang of PUTS 🤙  (APRIL 14 $420 PUTS are the OI warehouse of late) 🛅    
 
Tomorrow we should get some notable PUT ACTION 🔛 (BULLS ENTIRE YEARLY GAINS =  this recent fraud rally bounce! 🤷‍♂️ NO NEW ATH - nope 🤡🙃 $qqq $tsla $ba </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:41:31 </td>
   <td style="text-align:left;"> $SPY oh boy market is running meme stocks are running I guess we all eat fuck the bears $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:40:09 </td>
   <td style="text-align:left;"> $TSLA You’ll have one flat day this week to reload😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:39:59 </td>
   <td style="text-align:left;"> $TSLA https://youtube.com/channel/UCk5bqszYhFxRGddE6SAC3SA

Tomorrow crossing $1000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:39:30 </td>
   <td style="text-align:left;"> $TSLA oh this is about to hold and continue in the am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:39:12 </td>
   <td style="text-align:left;"> $TSLA holding strong in AH. Might be a lot of put and shorts jump this Friday if it continues to go up and hold tommoror </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:39:09 </td>
   <td style="text-align:left;"> $TSLA 
Vibe today🤠 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:37:44 </td>
   <td style="text-align:left;"> $TSLA $HTZWW jumping rented Teslas bullish af </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:37:42 </td>
   <td style="text-align:left;"> $TSLA $1600 please :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:37:25 </td>
   <td style="text-align:left;"> $TSLA Trending Heart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:37:18 </td>
   <td style="text-align:left;"> $TSLA drop this for at least 1 day so we reload lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:37:14 </td>
   <td style="text-align:left;"> $TSLA $1000+ PRE Market at the latest 10AM🚀….charts are irrelevant at this point! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:36:34 </td>
   <td style="text-align:left;"> $TSLA  this is just the start imo. Seems it will keep running for a little while with a few red days here and there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:35:39 </td>
   <td style="text-align:left;"> $TSLA (  GGPI  )Before the opportunity does not go, and before the merger and explosion, and for a quick comparison, look at rivn and lcid as sales and prices for Polestar, meaning or what I mean, you expect the price to be 40 and 35 dollars first, and thank you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:35:29 </td>
   <td style="text-align:left;"> $TSLA AGAIN. EACH LIKE IS 1 $TSLA I BUY 🚀🌙💸 WE BANKING TMR BOYS🙏😭 (currently holding 34 shares) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:35:23 </td>
   <td style="text-align:left;"> $TSLA you bears really thought a $7 drop scare would make aretracement?🤣🤣😂 keep dreaming, expect a possible $20 gap up tmmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:35:21 </td>
   <td style="text-align:left;"> $TSLA  GONA BE INSANE TOMORROW 🤞🤞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:34:29 </td>
   <td style="text-align:left;"> $TSLA another run tmr? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:34:03 </td>
   <td style="text-align:left;"> $MULN this isn’t good enough, I need $TSLA numbers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:33:56 </td>
   <td style="text-align:left;"> $SPY $TSLA 
BEARS you have my respect but unfortunately your species are becoming extinct, ever since 2008, you have lost over 60% of your population. The zoos have now changed your status from threaten to endangered…… 

All I can say is “ GOOD LUCK” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:33:49 </td>
   <td style="text-align:left;"> $TSLA lmfaooo yeah okay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:33:22 </td>
   <td style="text-align:left;"> $AAPL bought puts. This still has upside, but I&amp;#39;m inching into being net short. I shorted $TSLA stock as well. I think the next leg down will come soon enough and  the current rally is rather overbought in the near term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:32:54 </td>
   <td style="text-align:left;"> $GME $AMC $TSLA $PIK $FSR 🚨🚨🚨🚨💯💯💯 See this!!! https://vm.tiktok.com/ZTd5L7vmn/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:32:53 </td>
   <td style="text-align:left;"> $TSLA epic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:32:38 </td>
   <td style="text-align:left;"> $TSLA is anybody else seeing the next leg up after 1000 for resistance around 1030? I am seeing 990 was also a resistance but if it gaps up goes over 1k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:32:24 </td>
   <td style="text-align:left;"> $GME $TSLA Funny Elon gets in trouble over these types of tweet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:31:42 </td>
   <td style="text-align:left;"> $TSLA  Electric cars are now three to six times cheaper to drive in the US as gas prices rise 
 
https://electrek.co/2022/03/22/electric-cars-3-to-6-times-cheaper-to-drive-us-high-gas-prices/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:31:26 </td>
   <td style="text-align:left;"> $TSLA up $142 a share from $852 member entry alerted 3 days ago!  +17% (+393% options) 
 
Try our trading group free for the next 7 days: https://linktr.ee/ChartTrader 
 
#swingtrading #stocks #stockmarket #daytrading #stockstobuy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:31:07 </td>
   <td style="text-align:left;"> $TSLA 995call made 500% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:30:57 </td>
   <td style="text-align:left;"> $GME $AMC $TSLA $SAVA fill those gaps and Kenny’s and companies holes... go longs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:30:09 </td>
   <td style="text-align:left;"> $TSLA Holy shit pal I made some good bank today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:29:53 </td>
   <td style="text-align:left;"> $TSLA never going to have red day again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:29:16 </td>
   <td style="text-align:left;"> $TSLA  Elon Musk announces Tesla is working on new manganese battery cell 
https://electrek.co/2022/03/22/elon-musk-tesla-working-new-manganese-battery-cell/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:28:56 </td>
   <td style="text-align:left;"> $TSLA BREAKING: Jim Cramer TALKS TSLA (Tesla) Stock | Is he BUYING NOW?
https://youtu.be/19FFXnbRa50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:28:39 </td>
   <td style="text-align:left;"> $TSLA tomorrow we fly past 1000 lmfao this ain&amp;#39;t no sucker rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:28:32 </td>
   <td style="text-align:left;"> $TSLA Waiting $1200 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:28:20 </td>
   <td style="text-align:left;"> $TSLA Buy the rumor &amp;amp; the news 📰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:27:07 </td>
   <td style="text-align:left;"> $TSLA wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:26:22 </td>
   <td style="text-align:left;"> $TSLA huge win for tsla shareholders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:25:55 </td>
   <td style="text-align:left;"> @GoodieGoodStockOptions 

Is independence even possible with Russian oil strong holds and Chinese lithium strong holds “without a fight”?!
$aapl $amzn $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:25:43 </td>
   <td style="text-align:left;"> $TSLA 
Bad karma opening plant in Germany </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:24:54 </td>
   <td style="text-align:left;"> $QQQ futures bounty to fip. Can’t wait to look down on everyone when I’m on the moon . LFG $TSLA $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:24:32 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/Q6VpbrQO6y4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:24:04 </td>
   <td style="text-align:left;"> $MULN Investor Places Luke Lango thinks this is next big opportunity stock like Amazon and Tesla. Stated the company could have the “forever battery” he called it. Life changing gains are coming people $AMC $GME $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:23:54 </td>
   <td style="text-align:left;"> @GoodieGoodStockOptions 
Can $Tsla save the transportation and petro power consumption dependency in “the big switch” from petroleum dominance?! $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:23:44 </td>
   <td style="text-align:left;"> $RIDE $TSLA woof! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:23:19 </td>
   <td style="text-align:left;"> $TSLA gap up tomorrow and fly AGAIN😂😂🥳🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:22:53 </td>
   <td style="text-align:left;"> $TSLA TESLA Stock Price  Prediction and Analysis for Tomorrow Wednesday March 23
https://youtu.be/OpE3HOwckUQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:22:50 </td>
   <td style="text-align:left;"> $TSLA Raise your hand if you lost money shorting tesla today. Oh, I forgot you don&amp;#39;t talk about such stuff. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:22:36 </td>
   <td style="text-align:left;"> $tsla will be a 100 trillion dollar company. Meaning if you invested today you would make 100x your money by 2025 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:22:22 </td>
   <td style="text-align:left;"> $TSLA 

A psychic I’ve known for yrs (expensive one) down in LA area - I paid for a session (north of3k) for 45mins ! One of the questions I asked her is about the world instability and Russian War- she says this Putin guy not stupid knows what he’s doing and has it all planned out for a long time, he’s got a lot under his sleeve we don’t know yet and sadly others are paying for our mistakes ! 

I know you may all find it weird n laughable . This one I go to every time I fly my jet to LA and she’s got it 9 out of 10 for me ! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:22:09 </td>
   <td style="text-align:left;"> $TSLA $AMC MY account manager at TD just emailed me a high five </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:21:48 </td>
   <td style="text-align:left;"> $AMC $TSLA $ADBE $ALLG Real price will come out soon; Follow price targets...! If you really want to make a huge profit on trading: :&amp;quot;:&amp;quot;::-   stocksus.topstockstrading.net/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:21:13 </td>
   <td style="text-align:left;"> $SNDL hope everyone got in on those dips last week. Know what you hold ⏰ $TSLA $MULN  $IMPP https://www.prnewswire.com/news-releases/sundial-growers-to-announce-year-end-and-fourth-quarter-2021-financial-results-on-march-29-2022-301499864.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:20:39 </td>
   <td style="text-align:left;"> $TSLA ” Troy Teslike, an independent Tesla researcher, tweeted that the firm is then hoping that vehicle output will hit 1,000 per week at the six week-mark following the start of commercial production, and then 5,000 per week by the end of 2022.“ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:20:00 </td>
   <td style="text-align:left;"> $TSLA I believe I can fly!

Honestly. anyone betting on tesla not going over 1000$ tomorrow is total noob.

enjoy the free cash boys and girls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:19:53 </td>
   <td style="text-align:left;"> $TSLA Bigger bounce Back for tomorrow, gents.  
squeeze Fomo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:19:23 </td>
   <td style="text-align:left;"> $TSLA futes crashing hard AF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:18:53 </td>
   <td style="text-align:left;"> $TSLA  on the way to $1200!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:18:39 </td>
   <td style="text-align:left;"> $TSLA 
Feel like tomorrow gonna play both sides </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:18:17 </td>
   <td style="text-align:left;"> $TSLA should dump puts for close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:18:16 </td>
   <td style="text-align:left;"> $TSLA 995p loaded. Bought when it was at 992.

Rsi over 70 signaling sell. Expecting higher lows then launch back up past 1000.

Possible 950 retrace tmrw. Which I plan on selling until reversal signal before going calls. Stop loss if this triggers 1000 tmrw. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:17:45 </td>
   <td style="text-align:left;"> $GME Form 13D filed with SEC.  RC increased position by 100k shares.  $TSLA $BTC.X $AMC $SNDL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:16:47 </td>
   <td style="text-align:left;"> $PLTR 🤤🤤🤑🤓 $TSLA 

https://www.dailypalantir.com/post/the-odd-similarities-between-tesla-palantir?fbclid=IwAR0DCJsG3yUvQZS0luYNuN5RHJ54aCZtU9ilTtSmrm7m1Od2VLluSyM-J5g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:16:32 </td>
   <td style="text-align:left;"> $TSLA bears fu </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:16:30 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:16:29 </td>
   <td style="text-align:left;"> $MULN competition with $TSLA stick price seems very low. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:15:54 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ bought this morning , sold today , that’s how you do it ya chooches. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:15:24 </td>
   <td style="text-align:left;"> $GME Runner runner! LOOK AT THIS ACTIVITY from SweepCast... all MORNING it kept coming in and alerting that there was something cooking, similar to $AMC and $TSLA activity we observed on the platform. Don&amp;#39;t miss these runners! #stocktips #stockmarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:15:23 </td>
   <td style="text-align:left;"> $TSLA cmon Tessy follow GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:15:07 </td>
   <td style="text-align:left;"> $TSLA should be interesting. Just finished a 9 count with a reversal signal on the Vix and this.. what do you guys think? Every reversal signal on the vix has been a new leg down further in the next weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:14:48 </td>
   <td style="text-align:left;"> $TSLA Buy the news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:14:11 </td>
   <td style="text-align:left;"> $TSLA sell the news

hahjahahahahajajajajahjajajajhahahahhahahahahahahhahhahaha

Y’all are hilarious. Some of y’all acting like the factory in Germany news came out AH 😂 we all knew about this. No one is selling shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:12:48 </td>
   <td style="text-align:left;"> $TSLA winner today is BigNews, that is all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:11:44 </td>
   <td style="text-align:left;"> @Rosenhedge  $HUSA $TSLA $HUSA $AFRM $LCID$TSLA  
I am confused! 
you challenge someone to compare their portfolio which they accept and you don&amp;#39;t respond and block and insult them 
Are you a Coward? I wanted to see your reply </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:11:43 </td>
   <td style="text-align:left;"> $TSLA $750 mid April </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:11:28 </td>
   <td style="text-align:left;"> $TSLA 
Bears are a sundowner, I&amp;#39;m happy whenever they don&amp;#39;t prevail </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:10:49 </td>
   <td style="text-align:left;"> $TSLA proud shorts that have not covered one share ? so who got tsla into a mini squeeze today ? bigfreakingfoot ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:10:39 </td>
   <td style="text-align:left;"> $GME sold $128 calls, bought some $TSLA calls, some $160 GME calls, let&amp;#39;s go tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:10:33 </td>
   <td style="text-align:left;"> $TSLA one of our admins turned 20k into 100k this week, join the premium to find out the next big plays 💪🏻💪🏻🔌🔌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:10:30 </td>
   <td style="text-align:left;"> $TSLA anyone know if short interest is still the same? If it is, we are bound for a nice short squeeze. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:09:36 </td>
   <td style="text-align:left;"> $TSLA anyone having issues with Interactive Brokers $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:08:54 </td>
   <td style="text-align:left;"> $TSLA in case if you’re wondering who caught the whole move🌪💨 $SPY $AMZN $SHOP $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:08:28 </td>
   <td style="text-align:left;"> $TSLA Bears, just fold. 1005c3/25 opened 6.25, closed 3.50. Opened 4.00, closed 20.00. Stay Sucker Free </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-23 06:08:26 </td>
   <td style="text-align:left;"> $TSLA stop shilling your garbage muln here. Long-term TSLA investors aren&amp;#39;t interested </td>
  </tr>
</tbody>
</table></div>

---
