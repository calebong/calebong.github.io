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

[View the latest Economic Forecasts](/pdf/Monthly-Market-Outlook--Apr-2022-.pdf)

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



Last Updated: 2022-04-21 09:38:45 UTC +8

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
   <td style="text-align:left;"> 2022-04-21 09:28:00 </td>
   <td style="text-align:left;"> Australia Shares Edge Up as Industrials Lift </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index edged up 0.2% to around 7,584 on Thursday, moving within 1% of a fresh record high, as gains in industrial stocks outweighed losses in the technology and mining sectors. Brambles (7%) led the industrial sector higher as the company upgraded its annual sales and profit guidance after raising North American prices. Other gainers in the sector were Amcor PLC (2%), APA Group (1%) and Orica Ltd (1%). Financial, healthcare and energy stocks also advanced, including Westpac Banking (1.1%), Ramsay Health Care (2.2%) and Santos Ltd (1.3%). Meanwhile, technology firms tracked losses on Wall Street, while the mining sector was dragged down by BHP Group’s 2.5% plunge. The heavyweight miner fell short of estimates for iron ore production in the first quarter, as a pandemic-related labor crunch weighed on the firm’s efforts to boost production in the mineral-rich Pilbara region of Western Australia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/consumer-confidence </td>
   <td style="text-align:left;"> 2022-04-21 08:59:00 </td>
   <td style="text-align:left;"> Irish Consumer Sentiment Falls to 1-1/2-Year Low </td>
   <td style="text-align:left;"> The KBC Bank consumer sentiment index in Ireland tumbled to 57.7 in April of 2022 from 67.0 in the prior month. This was the weakest reading since October 2020 and the second successive sharp monthly drop as concerns about living costs that hurt the macroeconomic outlook in March spread into a weakening of spending plans in April. The index stands significantly below the long-term average of 86.6 and the cumulative 24 point decline since Irish inflation began climbing sharply over the last three months was the second largest in the 26-year history of the survey, mainly due to a surge in energy costs and rising food prices. “A more threatening development was a marked pull-back in consumer spending plans. The April ’22 purchasing climate is the weakest since the COVID-closedown related results for April and May 2020 and among the lowest on record for this component,” KBC Ireland chief economist Austin Hughes said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61171529?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-21 08:57:55 </td>
   <td style="text-align:left;"> Ukraine war: World Bank warns of 'human catastrophe' food crisis </td>
   <td style="text-align:left;"> The world is facing a "human catastrophe" from a food crisis arising from Russia's invasion of Ukraine, according to the President of the World Bank, David Malpass.                                                                                                                                                       , In an interview with BBC economics editor Faisal Islam, Mr Malpass, who leads the institution charged with global alleviation of poverty, warned that record rises in food prices would push hundreds of millions people into poverty and lower nutrition, if the crisis continues.                                        , "It's a human catastrophe, meaning nutrition goes down. But then it also becomes a political challenge for governments who can't do anything about it, they didn't cause it and they see the prices going up," he said on the sidelines of the IMF-World Bank meetings in Washington.                                      , The World Bank calculates there could be a "huge" 37% increase in food prices, which is "magnified for [the] poor", who will "eat less and have less money for anything else such as schooling. And so that means that it's really an unfair kind of crisis. It hits the poorest the hardest. That was true also of Covid"., The price rises are broad and deep, he said: "it's affecting food of all different kinds oils, grains, and then it gets into other crops, corn crops, because they go up when wheat goes up".                                                                                                                              , There was enough food in the world to feed everybody, he said, and global stockpiles are large by historical standards, but there will have to be a sharing or sales process to get the food to where it is needed.                                                                                                        , Mr Malpass also discouraged countries from subsidising production or capping prices.                                                                                                                                                                                                                                       , Instead, he said, the focus needed to be on increasing supplies across the world of fertilisers and food, alongside targeted assistance for the very poorest people.                                                                                                                                                       , The World Bank chief also warned of a knock on "crisis within a crisis" arising from the inability of developing countries to service their large pandemic debts, amid rising food and energy prices.                                                                                                                      , "This is a very real prospect. It's happening for some countries, we don't know how far it'll go. As many as 60% of the poorest countries right now are either in debt distress or at high risk of being in debt distress," he said.                                                                                       , "We have to be worried about a debt crisis, the best thing to do is to start early to act early on finding ways to reduce the debt burden for countries that are on have unsustainable debt, the longer you put it off, the worse it is," he added.                                                                        , The acknowledgement by the World Bank president that we have to be worried about a developing country debt crisis, is very significant.                                                                                                                                                                                    , The combination of massive pandemic debts with rising interest rates, and rising prices is truly toxic.                                                                                                                                                                                                                    , The talk on the sidelines here at the IMF and World Bank meetings is that the rich countries told emerging economies not to worry about borrowing in order to spend to help suppress the pandemic.                                                                                                                         , Now those countries are wondering if these record debts will be written off.                                                                                                                                                                                                                                               , Campaigning groups are preparing mobilisations over a pandemic debt jubilee. But there is silence from the rich country lenders, so far.                                                                                                                                                                                   , And there is a very new dynamic these days. The bankers to whom these sums are owed are no longer just in the West.                                                                                                                                                                                                        , China is now, very broadly, owed as much as the entire collection of Western creditors known as the Paris Club.                                                                                                                                                                                                            , How will it respond to calls for leniency on the repayment of loans?                                                                                                                                                                                                                                                       , Mr Malpass says of China: "they have different rules, for example, contracts that have non-disclosure clauses, meaning you can't share the terms with other people that makes it very hard to restructure those debts".                                                                                                    , China has also secured its lending against ports and natural resources. Sri Lanka is a case in point right now.                                                                                                                                                                                                            , The unwinding of all of this might not be orderly, and could have significant geopolitical consequences.                                                                                                                                                                                                                   , Earlier this month, the United Nations said that the Ukraine war had led to a "giant leap" in food prices, as they hit a new record high in March.                                                                                                                                                                         , It came as the war cut off supplies from the world's biggest exporter of sunflower oil and the cost of alternatives climbed.                                                                                                                                                                                               , Ukraine is also a major producer of cereals such as maize and wheat which have risen sharply in price too.                                                                                                                                                                                                                 , The UN said "war in the Black Sea region spread shocks through markets for staple grains and vegetable oils".                                                                                                                                                                                                              , The UN Food Prices Index tracks the world's most-traded food commodities - measuring the average prices of cereal, vegetable oil, dairy, meat, and sugar.                                                                                                                                                                  , Food prices are at their highest since records began 60 years ago, according to the index, after they jumped nearly 13% in March, following February's record high.                                                                                                                                                        , Food commodity prices were already at 10-year highs before the war in Ukraine, according to the index, because of global harvest issues.                                                                                                                                                                                   , This video can not be played                                                                                                                                                                                                                                                                                               , Bill Bailey on Eurovision and the inspiration for his new show                                                                                                                                                                                                                                                             , Incredible new drama Life After Life                                                                                                                                                                                                                                                                                       , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                                                                                                            , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/20/trading-the-winners-and-losers-from-the-dollar-at-two-year-highs-.html </td>
   <td style="text-align:left;"> 2022-04-21 08:29:57 </td>
   <td style="text-align:left;"> As the dollar jumps to two-year highs, the 'Fast Money' traders deliver winners and losers </td>
   <td style="text-align:left;"> , Wall Street may be underestimating the dollar's jump to two year highs.                                                                                                                                                                                                                                                                   , "With each passing day the dollar goes higher. That creates more of a headwind for the multinationals in the market in general," "Fast Money" trader Guy Adami said on Tuesday. "A stronger dollar, as counterintuitive as it may be, is not good for the market."                                                                        , On Wednesday, the dollar index hit its highest level since March 25, 2020. The index is up 10% over the last year. The timing comes in conjunction with fourth quarter earnings season.                                                                                                                                                   , The greenback's move is also notable against the Japanese yen (JPY), where it's also at a two decade high.                                                                                                                                                                                                                                , "If you repatriate that money and you get fewer dollars for whatever the currency you're repatriating," said trader Karen Finerman. "To me, that would be McDonald's which actually at this point now has a little more than half of their business outside of the U.S. So, they would not be the beneficiary. They would be the victim." , But some groups may thrive. Trader Steve Grasso experts some pockets including utilities to weather a stronger dollar.                                                                                                                                                                                                                    , "They have a predictable demand and with them predictable earnings as well. No one likes the lights going off in your house once you have lights in our house," he said. 'Whether it's the yield play or whether it's the predictability nature of it, those things are usually bought going into recession or a rising rate environment.", The Utilities Select Sector SPDR fund, which tracks the sector,  is up more than 7% so far this year.                                                                                                                                                                                                                                     , Grasso also sees retailers benefitting from budget shopping performing well.                                                                                                                                                                                                                                                              , "The old standbys: Dollar Gen [and] Dollar Tree. Both of those names have a history of splitting stocks. Both of those names have been outperforming. Both of those names have skyrocketed in stock price," he added.                                                                                                                     , For all trader disclosures, go to cnbc.com/fast-money/.                                                                                                                                                                                                                                                                                   , Disclaimer                                                                                                                                                                                                                                                                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-21 08:22:16 </td>
   <td style="text-align:left;"> US Futures Rise as More Earnings Mulled </td>
   <td style="text-align:left;"> US stock futures rose on Thursday after a mixed session on Wall Street, as investors digested more quarterly reports against a backdrop of elevated inflation and further monetary tightening. Dow futures edged up 0.3%, S&amp;P 500 futures gained 0.4% and Nasdaq 100 futures jumped 0.6%. Strong Q1 reports drove after-hours moves, with Tesla rising 5.6% on an expectation-beating record quarterly profit, while United Airlines surged 7.6% after the company forecasted a return to profit in 2022. In regular trading on Wednesday, the Dow rose 0.7%, boosted by strong earnings from Procter &amp; Gamble. The tech-heavy Nasdaq Composite, meanwhile, was dragged down 1.2% by Netflix’s post-earnings plunge, while the S&amp;P 500 ended slightly negative. Investors await more quarterly reports from companies like AT&amp;T, American Airlines and Snap on Thursday. Weekly jobless claims are also slated for release Thursday Morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-21 08:15:00 </td>
   <td style="text-align:left;"> Ireland 10Y Bond Yield Hits Near 7-year High </td>
   <td style="text-align:left;"> Ireland 10 Year Government Bond Yield increased to a near 7-year high of 1.618%, as US Treasury yields hovered near multi-year highs. Traders also concerns of declining Ireland’s consumer confidence and rising inflation, amid worries over higher energy prices. Consumer sentiment index in Ireland fell to 57.7 in April of 2022 from 67 in the prior month, pointing to the weakest reading since October 2020 and second successive sharp monthly drop as concerns about living costs that hurt the macroeconomic outlook in March spread into a weakening of spending plans in April. Meanwhile, the annual inflation accelerated to 6.7 percent in March of 2022, the highest since November of 2000, mainly due to higher in energy prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/world-asia-61160207?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-21 08:13:17 </td>
   <td style="text-align:left;"> Working with assertive China a must - New Zealand PM Jacinda Ardern </td>
   <td style="text-align:left;"> This video can not be played                                                                                                                                                                                                                                                                                                             , New Zealand has been aware for some time now of a "growing assertiveness" and a "growing interest" in its region - explicitly from China, according to Prime Minister Jacinda Ardern.                                                                                                                                                    , But Ms Ardern also spoke of the need to work together with China, on areas of "natural mutual interest".                                                                                                                                                                                                                                 , Speaking to the BBC in an exclusive broadcast interview, she stood by what she called her country's "mature relationship" with Beijing, but still expressed her "disappointment" that the Solomon Islands had cemented a security deal with China, fuelling fears Beijing could set up a military base on the island.                    , There is already an agreement signed by Pacific Island forum members called the "Biketawa" declaration, she said  - which sets an expectation these countries provide for their own security needs together as a region.                                                                                                                 , "One of the reasons we've expressed this disappointment [is]... Australia and New Zealand both have heeded the call of the Solomons for support during recent disruption," she said.                                                                                                                                                     , "And we've again highlighted that should any extended need exist, we are there to help and support. So… what gap remains that requires such an agreement with China?"                                                                                                                                                                    , Despite her reservations however, Ms Ardern rejected the idea that it was time for New Zealand to join the US, UK, and Australia in the Aukus security alliance to help ward off China's influence in the region.                                                                                                                        , "Our call on Aukus is simply that yes, it is to our benefit when we have greater engagement," she said.                                                                                                                                                                                                                                  , "We've asked the US to take an interest in the economic architecture of our region, it can't just be about defence and security arrangements," she said.                                                                                                                                                                                 , "It should be about the wellbeing of the region as a whole. And you're starting to see a response from the US on that front."                                                                                                                                                                                                            , New Zealand has been criticised for not taking a harder line on China.                                                                                                                                                                                                                                                                   , Ms Adern's administration's position has been that New Zealand will form its own bilateral relationship with China - which critics say is because of economic dependence.                                                                                                                                                                , Most recently the government came under fire for agreeing to extradite Kyung Yup Kim, a New Zealand permanent resident accused of murdering a young woman in Shanghai in 2009.                                                                                                                                                           , But Ms Ardern defended Wellington's relationship with Beijing.                                                                                                                                                                                                                                                                           , "China is a very important trading partner for us, but it's also a mature relationship for us. Where there are areas we can work together, we will - but there will always be areas in which we will not necessarily agree and when those areas arise, we are very forthright and clear on our position."                                , One of the areas where New Zealand has been particularly vocal internationally has been the war in Ukraine.                                                                                                                                                                                                                              , It has sent military and financial aid, and imposed sanctions on Russia.                                                                                                                                                                                                                                                                 , Ms Ardern says that's because small nations need to rely on the international order to be upheld, and that when the international order is threatened - it "threatens everyone, including New Zealand".                                                                                                                                  , But it isn't useful to turn this into a war of ideology, she said - refusing to frame it as a conflict between autocracies and democracies.                                                                                                                                                                                              , "Let's not be quick to create a binary situation between two differing schisms in the world. It is Russia, who has perpetrated this, it is Russia who must be spoken firmly against, and let's do everything we can diplomatically to ensure that that doesn't grow beyond Russia."                                                      , Separately the prime minister also defended New Zealand's Covid response, saying that it was the "best possible health response" at the time - given that New Zealand has had some of the lowest death rates amongst developed OECD economies.                                                                                           , But Ms Ardern has been criticised by her political opponents - her policies have been called "bumbling" and her government has accused of being "asleep at the wheel" - for failing to move the country out of lockdown faster.                                                                                                          , That's led in recent surveys to her lowest approval ratings since she was elected.                                                                                                                                                                                                                                                       , Ms Ardern was non-plussed - saying that the lower ratings were perhaps a price she had to pay, to keep New Zealanders safe, "to ultimately make sure that we've made the right decisions along the way, and that we can sleep at night".                                                                                                 , Ms Ardern's leadership style has been the subject of much debate - her fans say she is the real deal, authentic and empathetic, just what a politician should and can be. Her critics however, say it's more talk than action, more style than substance - and that she struggles to manifest the commitments she's made to her people.  , The New Zealand leader's response was characteristically straightforward.                                                                                                                                                                                                                                                                , "I'm just being myself," she said. "I want to the best of my ability, model the traits that I consider important enough to teach my own daughter… like kindness, gratitude."                                                                                                                                                             , "I would like to think that we can see a new range of leadership traits being modelled where kindness isn't seen as weakness, where empathy is actually how we understand our decisions impact on our people. And when we start to model those, I hope then that within the public, they see a little bit more of themselves."           , And what about wedding bells?                                                                                                                                                                                                                                                                                                            , As a world leader grappling with the pandemic, she's had to put off her wedding because of her job.                                                                                                                                                                                                                                      , Ms Ardern is honest about the pressures of public life.                                                                                                                                                                                                                                                                                  , "Travelling again, doesn't mean there's a lot of time for wedding planning," she said. "So, no set date. Just intention. And that's, I think, when you live together, have a child together - just intention is enough."                                                                                                                 , Bill Bailey on Eurovision and the inspiration for his new show                                                                                                                                                                                                                                                                           , Incredible new drama Life After Life                                                                                                                                                                                                                                                                                                     , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                                                                                                                          , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/20/politics/citizens-funnel-supplies-ukrainian-soldiers/index.html </td>
   <td style="text-align:left;"> 2022-04-21 08:00:58 </td>
   <td style="text-align:left;"> Ukrainian American helps funnel supplies to Ukrainian soldiers - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Tetiana Poudel's father, a deputy commander in Ukraine's Territorial Defense Forces, needed combat boots.                                                                                                                                                                                                                                                                                                                                                                                                     , Russia had just invaded Ukraine, and his unit was desperately lacking basic protective gear and medical supplies.                                                                                                                                                                                                                                                                                                                                                                                                   , So Poudel, a 31-year-old Ukrainian American citizen -- who's on leave from her California day job as an attorney for the music-streaming service Spotify -- packed up her life in Silicon Valley, moved to Poland and raised $13,000 for around 100 pairs of boots for her dad and members of his unit.                                                                                                                                                                                                             , "I like to tell people I'm a lawyer by day and a boot smuggler by night," she said earlier this month in an interview with CNN. A photo she shared with CNN shows her father and another soldier beaming next to new boots stacked on top of cardboard boxes.                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Poudel's initiative is a microcosm of a much larger network of private citizens, many of them veterans, from around the world who are working to provide Ukrainian soldiers with additional equipment they say they need to continue effectively fighting off the Russians.                                                                                                                                                                                                                                         , In some cases, Poudel and Western officials told CNN, efforts by private citizens to funnel gear and supplies to Ukrainian soldiers have been faster and more direct -- albeit on a much smaller scale -- than the government-led initiatives. The boots are just one need among many -- including firearms, ammunition and body armor -- that volunteers and private citizens from around the world are trying to fulfill for the Ukrainian army, which has ballooned in size since Russia invaded two months ago. , The Biden administration is preparing to announce that it is sending another $800 million worth of military assistance to Ukraine, CNN reported Tuesday. If approved, the latest package would mean the US has committed about $3.4 billion in assistance to Ukraine since Russia's invasion began on February 24.                                                                                                                                                                                                  , But for Poudel and others on the ground, the aid being provided by Western countries is still "too slow and it's not enough," she said.                                                                                                                                                                                                                                                                                                                                                                             , Poudel said she has been able to crowdsource enough money -- through her contacts on LinkedIn, WhatsApp and volunteer organizations like UkraineNow -- to buy the boots and obtain about a dozen tactical vests for her father and members of his unit. She delivered T-shirts to them last week, and the soldiers repaid her with pizza.                                                                                                                                                                           , "These guys are just so grateful," she said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Poudel's godmother had to pick up the boots in Poland and drive them over the border in multiple trips, since Ukrainian men aged 18 to 60 aren't allowed to leave the country.                                                                                                                                                                                                                                                                                                                                      , At the time, Poudel stayed in Poland with her mother and sister, who had fled Ukraine in the early days of the war. But underscoring how decisive Russia's defeat has been in northern Ukraine, Poudel and her family felt secure enough in recent weeks to move back to their hometown of Lutsk in northwestern Ukraine, as Russia shifted its focus to the east of the country.                                                                                                                                   , In a statement to CNN, Serhiy Sobko, a deputy commander and chief of staff for Ukraine's Territorial Defense Forces, said the troops are thankful for all of the help from volunteers.                                                                                                                                                                                                                                                                                                                              , "Within a few weeks, the TDF expanded to over 100,000 people ready to protect their country from the enemy," Sobko said, which led to a shortage in equipment.                                                                                                                                                                                                                                                                                                                                                      , "The Ukrainian government, our international partners, (and) prominent Ukrainian charitable foundations immediately involved their efforts to provide TDF with all needed equipment," Sobko said. "And TDF command makes sure that those brigades and battalions that are on the front line get the protection first. Therefore we are grateful to those volunteers from Ukraine and abroad who contribute to equipping our soldiers."                                                                              , More is needed, soldiers say                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , A US official told CNN that in terms of equipment and gear, the US has so far provided Ukraine with tactical secure communications systems, night vision devices, thermal imagery systems, optics, laser range finders, explosive ordnance disposal protective gear, chemical, biological, radiological and nuclear protective equipment, and medical supplies, including first aid kits.                                                                                                                           , The official did not detail how much of that gear has been delivered so far. But the Ukrainian soldiers need much more of all of it, they said, particularly thermal imaging cameras, night vision devices and quadcopters. They also need extremely basic gear, like seat belts, backpacks, flashlights and gloves, according to a list compiled by the soldiers and obtained by CNN.                                                                                                                              , When it comes to shipping in heavier protective gear like body armor, Poudel and other volunteers, including two US Marine veterans she met in Poland, have run into considerable hurdles: Level III and IV body armor is regulated by the US and requires special authorization by the State Department, contracts frequently fall through and any equipment that does get in is often backed up at airports.                                                                                                      , Level III armor provides protection against rifle rounds and level IV provides the most ballistic protection, according to the National Institute of Justice.                                                                                                                                                                                                                                                                                                                                                       , "One of the issues is, obviously, we're just getting through Covid. So you have all kinds of supply conditions that are difficult just on day one," Trey Sharpe, one of the Marine veterans helping Poudel, told CNN. "And then two, anytime you're trying to procure items that are in intense demand, it becomes hard."                                                                                                                                                                                           , Bureaucracy is another challenge, he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , "So if I want to ship a level IV (body armor) plate out of the United States, for example, I have to deal with American bureaucracy, Polish bureaucracy, Ukrainian bureaucracy, and then I have to get the money too, and I'm trying to do all of this from a cell phone, often in the middle of nowhere," he said, referring to his travels throughout western Ukraine. "It's, you know, it's not like shopping on Amazon. And I don't need just one (plate), I need thousands."                                   , Poudel said the situation is often demoralizing.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , "Sometimes I do get very depressed and sad about how much I'm not able to do," she said. "We have pretty much nothing and it's not like it's over just because Russia is refocusing on eastern Ukraine. They are still here" in the country.                                                                                                                                                                                                                                                                        , It is worth the effort, though, despite the difficulties, she said.                                                                                                                                                                                                                                                                                                                                                                                                                                                 , "Doing whatever I can on the ground here feels more meaningful than just sitting in the (United) States, even if it's just like, buying them vests and raincoats," she told CNN. "It's like, OK, I'm doing something real. I really see where it gets delivered."                                                                                                                                                                                                                                                   , Poudel added that while humanitarian aid is clearly needed, it is little more than a short-term solution to the widespread suffering Russia is inflicting upon civilians -- if that aid even gets delivered at all.                                                                                                                                                                                                                                                                                                 , "I support humanitarian aid," Poudel said. "But I think that is just a Band-Aid. The most important thing right now is to support the Ukrainian armed forces, because in most cases that humanitarian aid isn't even getting into the places that need it."                                                                                                                                                                                                                                                         , Poudel's father, Volodymyr Danyliuk, told CNN in a video interview that what is "most needed are helmets, transport vehicles and air defense systems. Because most of the time they are attacking from the air, and we can't protect ourselves against it."                                                                                                                                                                                                                                                         , Ukrainian officials have told the US that to keep Russia from controlling the skies over the country, Ukrainian forces need 500 anti-aircraft Stinger missiles per day. The Pentagon plans to speed up production of the weapons; the shipments have so far not kept up with the Ukrainians' demand.                                                                                                                                                                                                                , Medicines are similarly hard to come by. Poudel explained that because so many pharmacies have been destroyed, Ukrainian women, including herself, have begun driving into Poland to pick up medications and deliver them back over the border.                                                                                                                                                                                                                                                                     , Private citizens stepping up                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Poudel said she is grateful to Spotify for allowing her to take leave to be with her family, because she can't imagine leaving her mom and sister to fend for themselves in Ukraine while her father is serving in the Territorial Defense Forces. Spotify declined to comment.                                                                                                                                                                                                                                     , "I'm basically the sole provider for my family right now," she said.                                                                                                                                                                                                                                                                                                                                                                                                                                                , But when it comes to working to supply the Ukrainian forces, Poudel is far from alone.                                                                                                                                                                                                                                                                                                                                                                                                                              , "There are thousands and thousands of guys just like me, hundreds of groups just like the group that I started, doing the same thing," said another American veteran running a private effort to deliver medical equipment to Ukrainian soldiers and civilians, who requested anonymity to discuss his efforts freely. He said he'd raised enough money for 30 military-grade trauma kits, which he was able to deliver to Ukrainian soldiers earlier this month, according to photos he provided to CNN.           , A nonprofit organization called the Ukrainian Freedom Fund has also been working to procure defense materials for Ukrainian troops, and it has already provided thousands of bulletproof vests, helmets, vehicles and field first aid kits to Ukraine's Territorial Defense Forces, CNN previously reported. Kyiv's deputy mayor on Monday requested 200,000 gas masks from the organization to protect troops and civilians against potential chemical weapons attacks.                                            , Police departments across the US have joined the effort, too. The governors of Iowa and Nebraska, for example, announced earlier this month that their states would send police protective gear to Ukraine, including military-grade helmets and vests.                                                                                                                                                                                                                                                             , Poudel, for her part, says she began working with US Marine veterans to try to leverage their connections to companies that can source essential equipment like body armor, helmets and tourniquets.                                                                                                                                                                                                                                                                                                                , In many cases, the volunteers working to get equipment into Ukraine are making sure US government agencies are aware of their efforts, particularly to ensure that they don't run afoul of any export control laws. Sharpe, one of the Marine veterans, told CNN he had been given preliminary guidance by officials at the Justice and State departments on remaining in compliance as he worked to import supplies.                                                                                               , The State and Justice departments declined to comment, but a spokesperson for the Commerce Department told CNN that "numerous communities around the United States have sought to assist the Ukrainian government and its resistance to Russia's invasion by donating firearms, ammunition, helmets, bulletproof vests and related equipment."                                                                                                                                                                      , The spokesperson added that the Commerce Department "has been processing requests rapidly for the export of firearms and ammunition to Ukraine under its existing processes and authorities."                                                                                                                                                                                                                                                                                                                       , There are a number of things the department has advised Americans to consider if they do try to send equipment, the spokesperson said, including how they intend to transport it to Ukraine and whether or not* the sender has been authorized by the Ukrainian government to import the supplies.                                                                                                                                                                                                                  , There are also tighter restrictions on exports to the Donetsk and Luhansk regions, where the war has shifted in recent weeks, the spokesperson said.                                                                                                                                                                                                                                                                                                                                                                , "We owe them every bit of support that we can give, because they're fighting our fight too," Sharpe said of the Ukrainians. "And all we need to do is get them more materials and expertise and supply. I think it's our duty, every single person in the United States, in the world. They deserve our help."                                                                                                                                                                                                      , Danyliuk, Poudel's father, said the next major challenge for the Ukrainian forces will be to liberate the south from Russia, particularly the Kherson region. There is also a "constant threat of danger" from Belarus, he said, and he does not believe the threat posed by Russian President Vladimir Putin will ever really end.                                                                                                                                                                                 , But he still believes Ukraine will succeed, not least because of the sheer determination of its people. In peacetime, Danyliuk is a writer and historian, and recently had a book published in coordination with the Polish consulate in Lutsk. It's about the late President John F. Kennedy's connections to Poland and Ukraine.                                                                                                                                                                                  , Danyliuk misses journalism. "But there are times when the journalist needs to carry not the camera, but the gun," he told CNN, in a loose translation of a Ukrainian saying.                                                                                                                                                                                                                                                                                                                                        , "We weren't surprised by how well Ukrainians have fought," he said. "Everybody is a volunteer. They stepped onto the front line. That is why I'm convinced we will win."                                                                                                                                                                                                                                                                                                                                            , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61166381?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-21 07:45:36 </td>
   <td style="text-align:left;"> Pandemic lockdowns boosted trend to use less make-up </td>
   <td style="text-align:left;"> "Before, you wouldn't have caught me picking up a pint of milk without my face on," says Charlie, who works for a training business.                                                                                                                                              , But then the pandemic struck and now she just doesn't wear as much as she used to, even to work.                                                                                                                                                                                  , "I was stuck at home furloughed with two kids, my husband was away, so I spent a lot of time outside without make-up on, and realised no one cares," she explains.                                                                                                                , Charlie feels the pandemic has given her the confidence to embrace a more natural look. And it seems she's not alone.                                                                                                                                                             , The use of cosmetics was already declining before 2020, but a survey of 10,000 British women by market research firm Kantar has revealed big changes to post-lockdown beauty routines.                                                                                            , Make-up purchases and frequency of wearing products has dropped steeply in the last two years, by almost a third, it suggests.                                                                                                                                                    , Colleagues of Charlie's at Rhino Safety, on the outskirts of Sandbach in Cheshire, agree.                                                                                                                                                                                         , Director Cate Walter admits she splurges on getting her nails and eyebrows done. But her daily regime is minimal; a bit of blusher and maybe mascara for a day in the office.                                                                                                     , "I just don't want to look ill," she jokes.                                                                                                                                                                                                                                       , Although the business has a relaxed feel, Cate says she has definitely noticed a change since staff started working remotely.                                                                                                                                                     , "You do not need to spend as much time on your appearance, especially as you're potentially only seen from the waist up anyway," she says, adding that being fully made-up is not something she, nor many clients, expect.                                                        , "I'm not going to expect you to be in a full face of make-up and a suit when you're essentially sat at your kitchen table," she says.                                                                                                                                             , Kantar surveyed 300,000 women worldwide, as well as looking at spending data, and found that British women have made the biggest change in their grooming habits in recent years.                                                                                                 , "Manufacturers are going to struggle and they're really going to have to work harder to get our money from us," said Kantar analyst Maya Zawislak.                                                                                                                                , Their research shows a 19% fall in make-up sales since 2019, but the pandemic is only part of the story.                                                                                                                                                                          , Ms Zawislak adds that a looming cost-of-living crisis could also affect what consumers buy.                                                                                                                                                                                       , The cosmetics industry is struggling on two fronts. As the squeeze on all our budgets really starts to bite people are looking for ways to cut their spending.                                                                                                                    , But the pandemic has also given some women the self-confidence to try going make-up free, or to let their hair go grey.                                                                                                                                                           , Skin care products have not seen the same decline as cosmetics though, as we've moisturised with enthusiasm after all the anti-bac gel. And self-care has become an important buzz word in these difficult times.                                                                 , Overall it seems people are reluctant to spend on what might be seen as frivolous, but happier to splurge on something that feels like it's doing them good.                                                                                                                      , Historically, economists would say that lipstick sales thrive during difficult economic times. Typically, this little luxury might have been a way for cash-strapped consumers to treat themselves.                                                                               , But this time the use of masks and remote working has seen the sale of red lip products fall by 40%.                                                                                                                                                                              , On the other hand, rather than just buying less, some people have switched to different products.                                                                                                                                                                                 , "I probably buy less now, but maybe higher-end price products," says Charlie's colleague, Julie Hopwood.                                                                                                                                                                          , Julie uses a tinted moisturiser plus a bit of eye-shadow. "I think eyes did become more important when we were all wearing masks," she explains, adding that she has felt inspired to try new things, watching tutorials online during lockdown.                                  , Both Julie and Charlie spend about half an hour getting ready for work and maybe an hour at the weekend. Changes to their morning routine mean they can spend time going to the gym or with family instead.                                                                       , The relaxation of what we wear to work started long before the pandemic for many sectors. But it appears to have accelerated during the pandemic, so much so that last month the Office for National Statistics removed men's suits from their "typical" basket of consumer goods., The question for the cosmetic industry, and for related areas such as workwear, is whether these new habits will stay or fade as fashions and behaviours shift.                                                                                                                   , Sarah Finn, for one, hopes they stick.                                                                                                                                                                                                                                            , "I used to be the odd one out, because I didn't wear make-up," she says. "I get up, get showered and I'm out of the door."                                                                                                                                                        , Now, no-one else seems to be wearing make-up either, says Sarah, and possibly, like her, they'll decide they'd rather keep the morning lie-in.                                                                                                                                    , Bill Bailey on Eurovision and the inspiration for his new show                                                                                                                                                                                                                    , Incredible new drama Life After Life                                                                                                                                                                                                                                              , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61170691?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-21 07:45:33 </td>
   <td style="text-align:left;"> Tesla profits soar as customers pay more </td>
   <td style="text-align:left;"> Tesla has been raising prices - but that hasn't seemed to dent demand for its electric cars.                                                                                                                                           , Despite the firm facing higher costs, profits at Elon Musk's electric car company soared to $3.3bn (£2.5bn) in the first three months of the year, as customers proved willing to pay more.                                            , The firm's deliveries were up 68% - and would have been higher if not for supply chain shortages, the firm said.                                                                                                                       , Its Shanghai factory was also recently forced shut due to Covid restrictions.                                                                                                                                                          , As the plant reopens this month, staff will be required to sleep at the factory in an effort to avoid further lockdowns, Bloomberg has reported.                                                                                       , "Although limited production has recently restarted, we continue to monitor the situation closely," Tesla said as it shared quarterly results with investors.                                                                          , Tesla has been pushing to expand, opening new factories in Texas and Germany in recent weeks.                                                                                                                                          , The firm delivered more than 310,000 cars in the first three months of the year and in a conference call, chief executive Elon Musk predicted the company would produce 60% more cars during the year as a whole compared to last year., Tesla doesn't advertise its products, but attracts frequent headlines, often related to controversial comments made by Mr Musk.                                                                                                        , But the firm said that it had also seen spikes in orders following increased marketing from rival electric car makers.                                                                                                                 , Mr Musk said Tesla expects to mass produce a robotaxi with no steering wheel or pedals by 2024.                                                                                                                                        , While Tesla shares rose more than 5% in after-hours trade, following the strong results, some investors worry Mr Musk may be distracted from his focus on the electric carmaker as it expands.                                         , Mr Musk, known for his sometimes erratic musings on Twitter, recently made an unsolicited offer to buy the social media platform for $43bn.                                                                                            , The rise in Tesla's stock market value in recent years has made Mr Musk the world's richest man, with an estimated net worth of more than $260bn.                                                                                      , That is nearly $100bn more than his closest rival, Amazon founder Jeff Bezos.                                                                                                                                                          , This video can not be played                                                                                                                                                                                                           , Bill Bailey on Eurovision and the inspiration for his new show                                                                                                                                                                         , Incredible new drama Life After Life                                                                                                                                                                                                   , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-61166272?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-21 07:21:43 </td>
   <td style="text-align:left;"> Actors launch campaign against AI 'show stealers' </td>
   <td style="text-align:left;"> Actors' livelihoods are at risk from artificial intelligence (AI) unless the law changes, a union warns.                                                                                                                                                                                 , Equity, the performing arts workers union, has launched a new campaign, "Stop AI Stealing the Show".                                                                                                                                                                                     , AI can use samples of an actor's voice or face, to generate content including so-called "deep fakes".                                                                                                                                                                                    , "From automated audiobooks to digital avatars, AI systems are now replacing skilled professional performers" the union says.                                                                                                                                                             , It warns of "dystopian" consequences unless copyright law adapts.                                                                                                                                                                                                                        , Equity highlights a number of different ways actors' voices and likenesses may be used.                                                                                                                                                                                                  , For example actors may work with AI firms to create systems that can generate artificial voice-overs or to help them create digital "avatars".                                                                                                                                           , And "synthetic" performances can be created using AI, in some cases even allowing deceased actors to appear in films.                                                                                                                                                                    , While AI-generated performances can be a useful creative tool, the union is concerned that actors may not always be able to control the use of their likeness, or their likeness may be used without consent or adequate remuneration.                                                   , AI generated "deep fake" videos of celebrities have become increasingly popular online.                                                                                                                                                                                                  , Actor Talulah Riley who supports the campaign told the union "As a performer, it is vital that my voice and my image are my own, no matter how easily and cheaply those things can be digitally replicated. I believe that performers must be rewarded fairly for the content we create.", Where actors work with AI companies, most do not know their rights, and many are required to sign non-disclosure agreements the union says.                                                                                                                                              , In a survey of 430 of its members the union found that 93% of audio artists felt that AI posed a threat to their employment opportunities.                                                                                                                                               , One respondent to the survey told the union: "In the last six months, my voice has been used in huge marketing campaigns by global companies. I don't receive a penny, even though I believe my contract does not allow for third party advertising."                                    , Equity said: "AI's increasing capacity to clone human voices presents a substantial risk that the voice owner will either be under-compensated or not paid at all .                                                                                                                      , Equity says it is particularly concerned about the development of digital voice technology for automated audiobook creation.                                                                                                                                                             , The campaign is backed by Bev Standing who sued TikTok over the use of her voice.                                                                                                                                                                                                        , The Canadian voiceover artist recorded about 10,000 sentences of audio for the state-backed Chinese Institute of Acoustics research body to use in translations, in 2018.                                                                                                                , But her voice, Ms Standing alleged, was later used by TikTok in a feature which converted writing into speech, which could then be played over videos uploaded to the app, often for comedic effect.                                                                                     , This included, Ms Standing claimed, videos where the synthetic voice repeated profanities.                                                                                                                                                                                               , TikTok settled the lawsuit.                                                                                                                                                                                                                                                              , Ms Standing told equity "I now only work with companies where I have control over where my voice gets licensed".                                                                                                                                                                         , The union argues existing copyright law does not give performers sufficient protection, because AI "reproduces performances without generating a recording or a copy".                                                                                                                   , Equity wants the government to take action to protect performers' rights and wants reform of copyright laws to "keep pace with technological development".                                                                                                                               , However there may be concerns that changes to copyright law could have a negative impact on free speech or stifle innovation.                                                                                                                                                            , The government told the BBC it wanted to ensure AI was regulated in a way that encouraged innovation "while protecting people and our fundamental values".                                                                                                                               , "Our national AI strategy has a ten-year vision for seizing the opportunities of the technology and we will set out our approach to its governance in due course" a government statement said.                                                                                           , Bill Bailey on Eurovision and the inspiration for his new show                                                                                                                                                                                                                           , Incredible new drama Life After Life                                                                                                                                                                                                                                                     , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                                                                          , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/20/politics/us-ukraine-weapons-what-matters/index.html </td>
   <td style="text-align:left;"> 2022-04-21 07:02:48 </td>
   <td style="text-align:left;"> An important shift in Ukraine -- and the US hopes more weapons will help - CNNPolitics </td>
   <td style="text-align:left;"> A version of this story appeared in CNN's What Matters newsletter. To get it in your inbox, sign up for free here.                                                                                                                                                                                                                                                                                                                    ,  (CNN)The war in Ukraine may be entering a new and critical stage with a fresh focus by Russia's military, a last stand in a key Ukrainian city and the promise of additional firepower from the US to help Ukraine fight back.                                                                                                                                                                                                       , New focus. Russia's military is now focused on the disputed eastern portion of Ukraine that was thought to be its objective before the invasion began. British intelligence suggests Ukrainian forces have repelled numerous attempted advances by Russian forces in the area -- but US officials warn the Russians may be preparing for a larger assault across southeast Ukraine.                                                   , Ukraine's Alamo. Advances by Russians in the south against besieged defenders in the surrounded city of Mariupol, a key supply hub, are dimming hope for Ukraine's military there after the commander issued a desperate plea for help. Ukraine's government says women and children are also seeking refuge at a steel plant that is the military's redoubt.                                                                         , More weapons coming. A new injection of weapons is being considered by the US to help Ukraine adapt to a different stage of the conflict.                                                                                                                                                                                                                                                                                             , The Biden administration believes the war is in a critical stage and is looking for ways to prop up Ukraine's military.                                                                                                                                                                                                                                                                                                               , Another $800 million in assistance? CNN's White House and Pentagon teams report the Biden administration may send another $800 million military assistance package to Ukraine -- on top of the $800 million announced last week. The size and details could change. One senior administration official told CNN Tuesday the package could come within 36 hours, but another administration official said the timing isn't locked down., Separately, spare parts have helped Ukraine add about 20 airplanes to its air force, a senior US defense official said Wednesday, although it's not clear where the parts came from.                                                                                                                                                                                                                                                  , Grand total: It would add up to $3.4 billion in US assistance to Ukraine since the invasion began, if the second $800 million package is approved.                                                                                                                                                                                                                                                                                    , What's being sent to help in the East? Artillery and long-range systems could be more helpful in the more open terrain. This is the same contested Donbas region where Russian-backed forces have been fighting with the Ukrainian military for years.                                                                                                                                                                                , What happens with all this firepower? It's not entirely clear. An interesting CNN report focused on how the US loses track of the weaponry it sends to Ukraine.                                                                                                                                                                                                                                                                       , From CNN's report: In making the decision to send billions of dollars of weapons and equipment into Ukraine, the Biden administration factored in the risk that some of the shipments may ultimately end up in unexpected places, a defense official said. But right now, the official said, the administration views a failure to adequately arm Ukraine as a greater risk.                                                          , I asked CNN's Oren Liebermann, who helped write both of the stories about American military aid, what to make of all these additional weapons likely headed from the US to Ukraine.                                                                                                                                                                                                                                                   , Pay attention to the importance of artillery, he told me. It is expected to be a big part of the next shipment, and it was an important (though far smaller) part of the last $800 million package.                                                                                                                                                                                                                                   , Why wasn't more artillery sent to this point?                                                                                                                                                                                                                                                                                                                                                                                         , LIEBERMANN: Because artillery was not the type of weapon needed to defend Kyiv. In the swamps and forests of northern Ukraine, not to mention the Chernobyl exclusion zone, artillery was not a critical part of the fight. With the focus now in Southeast Ukraine, artillery and other long-range weaponry absolutely is critical.                                                                                                  , Is this new technology or a game-changer in the fight?                                                                                                                                                                                                                                                                                                                                                                                , LIEBERMANN: Let's be clear -- artillery isn't new tech. Maybe the systems are newer and offer a bit more precision or more firepower, but artillery isn't some newfangled piece of military hardware that's never been seen before. Quite the contrary -- it's been an integral part of wars for many, many decades, if not a couple centuries at this point.                                                                         , And yet it's viewed by the US and its partners/allies as one of the most important pieces of weaponry to get to Ukraine ... and fast. Ukraine can burn through artillery ammo quickly, so it's important to get them a very large supply ASAP.                                                                                                                                                                                        , How does the Pentagon view its responsibility for these weapons once they're in Ukraine?                                                                                                                                                                                                                                                                                                                                              , LIEBERMANN: That's not viewed as critical. It's DoD's job to get it to the border, then Ukraine takes it from there to wherever they believe it's needed. Ukraine has a nearly insatiable appetite right now for more weaponry, and that's what the US is trying to meet, along with the help of other countries.                                                                                                                     , What do we know about what's been sent so far? Per CNN's Ellie Kaufman, a senior US defense official told reporters Wednesday that the first of 40,000 Howitzer rounds, a type of artillery ammunition, have arrived in Europe to be sent to Ukraine. These are a part of the most recent $800 million package.                                                                                                                       , The US is training about 50 Ukrainians in a country outside of Ukraine (it's not clear which one) on how to use the Howitzer rounds.                                                                                                                                                                                                                                                                                                  , "This is to train the trainers; it's a smallish number of Ukrainians, little bit more than 50 -- they will get trained on how to use the Howitzers and then they'll be able to go back into Ukraine and train their colleagues," the official said.                                                                                                                                                                                   , The NATO question looms. Finland and Sweden are both now actively considering joining NATO, so if Russian President Vladimir Putin's plan was to stop the growth of the alliance, it has officially backfired. Russia has warned such moves could lead to a more aggressive stance with regard to its hypersonic or nuclear weapons.                                                                                                  , Saber-rattling. An intercontinental ballistic missile test by Russia on Wednesday is a message to countries that try to threaten it, according to Putin.                                                                                                                                                                                                                                                                              , Walkout. Russia was further isolated from the world community after Western finance officials, including the US Treasury secretary, walked out of a closed-door meeting of the Group of 20 industrialized nations in Washington rather than hear a Russian presentation.                                                                                                                                                              , What is the nuclear threat in Ukraine? CNN's Barbara Starr and Zachary Cohen report the US military is keeping a constant watch on Russia's nuclear arsenal.                                                                                                                                                                                                                                                                          , The US has not seen any indication Russia has moved to prepare its nuclear arsenal for use, and Starr and Cohen report that US officials still feel there is only a very remote likelihood Putin would cross that line.                                                                                                                                                                                                               , But Ukrainian President Volodymyr Zelensky warned last week the world should prepare for the possibility Putin could use nuclear weapons.                                                                                                                                                                                                                                                                                             , From Starr and Cohen: Highly classified US military plans continue to be updated about what everyone believes is an almost unthinkable scenario: the use of a nuclear weapon. The US military "has planned all this out," a senior defense official said.                                                                                                                                                                             , Endnote: Life on the front lines in the Russian army. CNN's Phil Black went to an abandoned Russian military camp outside Kyiv. When the soldiers failed to take Ukraine's capital, they were left to live in primitively dug fox holes. Black talks to civilians who were captured and tortured by the Russians as well as a priest who was asked to bury people they killed. See his video report here.                             , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/inflation-cpi </td>
   <td style="text-align:left;"> 2022-04-21 07:00:43 </td>
   <td style="text-align:left;"> New Zealand Inflation Rises to 30-Year Peak </td>
   <td style="text-align:left;"> The annual inflation rate in New Zealand increased 6.9% in the first quarter of 2022, following a 5.9 percent gain in the previous period but below forecasts of 7.1%. It was the highest since the second quarter of 1990, as prices advanced faster for housing &amp; utilities (8.6 percent vs 7.6 percent in Q4 2021), food &amp; non-alcoholic beverages (6.7 percent vs 4.1 percent), recreation &amp; culture (4.8 percent vs 4.7 percent), miscellaneous good &amp; services (5.6 percent vs 4.9 percent) and alcoholic beverages and tobacco (2.9 percent vs 1.8 percent). On the other hand, transport prices rose at a softer pace (14.3 percent vs 15.0 percent). Compared to the previous quarter, inflation increased to 1.8 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/04/20/russian-icbm-test-tsr-starr-pkg-vpx.cnn </td>
   <td style="text-align:left;"> 2022-04-21 06:51:10 </td>
   <td style="text-align:left;"> Putin issues warning to West as Russia test launches ICBM - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/20/business/united-airlines-earnings-flights.html </td>
   <td style="text-align:left;"> 2022-04-21 06:33:58 </td>
   <td style="text-align:left;"> United Airlines Foresees Record Revenues After a Big Quarterly Loss - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The carrier’s chief predicted a “historic inflection point for our business,” with strong demand despite fare increases fed by rising fuel prices.                                                                                                                                                                                                                                                                                                                                        , By Niraj Chokshi                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , United Airlines, while announcing a big first-quarter loss, said Wednesday that it expected record revenue in the coming months, suggesting it had reached a pandemic turning point.                                                                                                                                                                                                                                                                                                      , “The demand environment is the strongest it’s been in my 30 years in the industry,” the airline’s chief executive, Scott Kirby, said in a statement. “We’re now seeing clear evidence that the second quarter will be an historic inflection point for our business.”                                                                                                                                                                                                                     , The airline reported a nearly $1.4 billion loss for the first three months of the year. But it said it expected to collect 17 percent more revenue on a per-seat, per-mile basis from April to June than it did in the same period in 2019. The company also said it expected a healthy profit in the second quarter, despite high fuel prices.                                                                                                                                           , United’s outlook, which it described as “bullish,” drove the airline’s shares up more than 7 percent in after-hours trading. The airline cited a handful of reasons for its rosy projection, including strong consumer demand, operating margins that are nearly back to 2019 levels, rapidly rebounding business travel and the carrier’s expectation of a similar upturn in international travel. United said it expected a profit not only in the second quarter but for the full year., The optimism comes as little surprise given the industry’s momentum this year. Last week, Delta Air Lines reported that March was its best sales month ever, beating a record set in 2019 despite having 10 percent fewer seats available.                                                                                                                                                                                                                                                , The spread of the Omicron variant of the coronavirus slowed demand at the start of the year, but airlines quickly recovered as consumers began booking flights in greater numbers. Searches for flights within the United States are up about 63 percent from last year, while searches for flights abroad are up more than 100 percent, according to Kayak, the travel booking site.                                                                                                     , The number of people screened at airport security checkpoints over the past month was down only 10 percent from the same period in 2019, according to Transportation Security Administration data.                                                                                                                                                                                                                                                                                        , The appetite for travel has so far been unaffected by skyrocketing fares, which have been driven in large part by the cost of fuel. The price of an average round-trip domestic flight has risen 40 percent this year, to $330 from $235, according to Hopper, an airfare-tracking app. The company said it expected fares to rise another 10 percent by June.                                                                                                                            , It is not yet clear whether the end of the mask requirement on planes this week will affect demand.                                                                                                                                                                                                                                                                                                                                                                                       , If United’s forecast for the next few months is borne out, the carrier would make up for its performance over the first three months of the year, when revenue was down about 21 percent and flight capacity was down about 19 percent from the same quarter in 2019.                                                                                                                                                                                                                     , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/20/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-04-21 06:05:35 </td>
   <td style="text-align:left;"> Stock futures rise as investors digest more earnings reports </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                     , Stock futures rose in overnight trading as investors digested more quarterly reports from the likes of Tesla and United Airlines.                                                                                                                                                                                                   , Futures on the Dow Jones Industrial Average added about 70 points, or 0.2%. S&amp;P 500 futures ticked up 0.3% and Nasdaq 100 futures gained 0.5%.                                                                                                                                                                                      , First-quarter reports drove after-hours moves Wednesday. Tesla rose about 5% after better-than-expected earnings, while United added more than 7% after the airline forecasted a profit in 2022.                                                                                                                                    , Stocks are coming off a mixed regular trading session Wednesday. The Dow rose 280 points, or 0.8%, boosted by strong earnings from Procter &amp; Gamble, while the technology-heavy Nasdaq Composite was dragged down 1% by Netflix's post-report plunge. The S&amp;P 500 finished flat.                                                    , Netflix shares on Wednesday posted the biggest one-day decline since 2004 after the streamer reported its first subscriber loss in more than a decade. Other streaming companies like Disney and Roku also fell, and other tech stocks were lower.                                                                                  , "It continues to be a pretty bifurcated market," said Dave Grecsek, managing director in investment strategy and research at wealth management firm Aspiriant. "Some of the more defensive, value-style companies are enjoying good returns. The flipside is some of those more growth-style tech names are going to be struggling.", Investors are awaiting quarterly reports from companies like AT&amp;T, American Airlines and Snap on Thursday.                                                                                                                                                                                                                          , Weekly jobless claims are also slated for release Thursday morning.                                                                                                                                                                                                                                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                              , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                              , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                    , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                    , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                  , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/20/business/media/netflix-streaming-warning-sign.html </td>
   <td style="text-align:left;"> 2022-04-21 05:49:34 </td>
   <td style="text-align:left;"> Netflix’s Stumble Could Be a Warning Sign for Streaming Industry - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The company faces a number of challenges, but its problems may be an indication that its competitors are racing toward an unstable future.                                                                                                                                                                                                                                                                                                                                                            , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                        , By John Koblin and Nicole Sperling                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Many entertainment executives, tired of playing catch-up to a Silicon Valley interloper, have been waiting for the comeuppance of Netflix. But this may not have been the way they hoped it would happen.                                                                                                                                                                                                                                                                                             , Netflix said this week that it lost more subscribers than it signed up in the first three months of the year, reversing a decade of steady growth. The company’s shares nose-dived 35 percent on Wednesday while it shed about $50 billion in market capitalization. The pain was shared across the industry as the stock of companies like Disney, Warner Bros. Discovery and Paramount also declined.                                                                                               , Netflix blamed a number of issues, ranging from increased competition to its decision to drop all its subscribers in Russia because of the war in Ukraine. To entertainment executives and analysts, the moment felt decisive in the so-called streaming wars. After years of trying, they may see a chance to gain ground on their giant rival.                                                                                                                                                      , But Netflix’s stunning reversal also raised a number of questions that will have to be answered in the coming months as more traditional media companies race toward subscription businesses largely modeled after what Netflix created. Is there such a thing as too many streaming options? How many people are really willing to pay for them? And could this business be less profitable and far less reliable than what the industry has been doing for years?                                   , “They switched from a sound business model to an unsound one,” the veteran entertainment executive Barry Diller said in an interview on Wednesday, referring to many legacy companies that have recently debuted streaming options. “I would guess today they’re saying, ‘Maybe trees don’t grow to the skies.’”                                                                                                                                                                                      , The media industry, worried about declining movie theater ticket sales and broadcast television ratings, has been reshaping itself on the fly to go all-in on streaming and compete with Netflix. Disney has invested billions. Discovery Inc. and WarnerMedia completed a merger this month to better compete with streaming behemoths. CNN even introduced a streaming version of itself, which has so far drawn underwhelming interest from subscribers.                                           , But Netflix’s sudden problems show that those investments come with a lot of risk. The streaming market may still be a giant one over the long term, but the next few years could be difficult, said Rich Greenfield, an analyst at LightShed Partners and a longtime streaming booster.                                                                                                                                                                                                              , “No matter what, it looks far less profitable, and that’s a problem for everybody,” he said. Fewer subscribers coupled with increased costs because of fiercer competition to create original content mean less profit for everyone.                                                                                                                                                                                                                                                                  , Another concern, some analysts say, is the so-called churn rate. Consumers are growing warier of rising prices for streaming services and becoming more likely to cancel a service when a favorite show comes to an end, said Kevin Westcott, vice chairman of the consulting firm Deloitte. According to Deloitte, 25 percent of U.S. customers have canceled a streaming service only to resubscribe to it within a year.                                                                           , “They’re frustrated that they have to have so many subscriptions to get all the content they want,” Mr. Westcott said.                                                                                                                                                                                                                                                                                                                                                                                , Netflix’s issues increase pressure on Disney, which will report subscriber numbers on May 11. If Disney’s figures fail to live up to expectations, the distress signals surrounding the streaming business will grow louder.                                                                                                                                                                                                                                                                          , There was also fear among Hollywood talent agents on Wednesday that the Netflix gravy train could slow and that the company’s willingness to pay whatever it took for scripts and talent deals could vanish. The same went for producers. Netflix has spent hundreds of millions of dollars over the past five years in pursuit of Academy Awards. It has yet to nab a best picture Oscar, but its commitment to prestige filmmaking has been praised.                                                , “The effect on us will be if the new reality forces them to cut back on their $17 billion-a-year programming budget,” said Michael Shamberg, whose four-part documentary on the Three Mile Island nuclear plant crisis will debut on Netflix next month. “As a producer, I always think of them as a first stop for pitching original ideas. If their subscriber growth levels off and it forces them to cut back on programming, will they stop taking risks on innovative TV shows and Oscar films?”, Netflix acknowledged that ferocious competition was partly a reason that growth had stalled. The company used to say its primary competition was not from other streaming services but from diversions like sleep and reading.                                                                                                                                                                                                                                                                        , Now there is a question about whether Netflix’s original content is strong enough to set it apart, as even deeper-pocketed companies like Apple and Amazon continue to increase their spending on critically acclaimed shows like “Severance,” which is carried on Apple TV+, and the upcoming first season of a “Lord of the Rings” prequel, for which Amazon is said to be spending more than $450 million.                                                                                         , “The reality is with so much alternative content out there, where is the new stuff that is just crushing it? Where are the new franchises?” asked Mr. Greenfield, the analyst. He noted that popular shows like “Ozark,” “Stranger Things” and “The Crown” would soon be ending their runs.                                                                                                                                                                                                           , Indeed, interest in Netflix’s vast library has been showing signs of plateauing.                                                                                                                                                                                                                                                                                                                                                                                                                      , “For every single title on the Netflix catalog, the demand is pretty much flat,” said Alejandro Rojas, the vice president of applied analytics at Parrot Analytics, a research firm. “The catalog for HBO Max and Disney+ is growing double digits. That’s a big difference.”                                                                                                                                                                                                                         , Netflix’s performance could also cause rivals to reconsider their own international expansion plans, potentially making more targeted efforts overseas. Netflix’s subscriptions declined not just in the United States and Canada but also in Europe and Latin America.                                                                                                                                                                                                                               , “Netflix has thrown the kitchen sink at this,” the industry analyst Michael Nathanson said. “They were a first mover, they spent a ton on content, and they are making more localized content. They’ve done the right things, and yet they’ve hit a wall.”                                                                                                                                                                                                                                            , Netflix executives, normally self-assured, seemed notably unsteady on Tuesday, when the first-quarter results were released. The co-chief executive Reed Hastings, who once swore there would never be ads on Netflix, said the company would consider introducing a lower-priced, advertising-supported tier in the next year or two. Netflix also said it would crack down on password sharing, a practice that in the past it said it had no problem with.                                         , “We’ve been thinking about that for a couple of years, but when we were growing fast it wasn’t a high priority to work on,” Mr. Hastings said. “And now, we’re working superhard on it.”                                                                                                                                                                                                                                                                                                              , Netflix has no advertising sales experience, while rivals like Disney, Warner Bros. Discovery and Paramount have vast advertising infrastructure. And the password crackdown led some analysts to wonder whether Netflix has already reached market saturation in the United States.                                                                                                                                                                                                                  , Mr. Hastings tried to reassure everyone that Netflix had been through tough times before and that it would solve its problems. He said the company was now “superfocused” on “getting back into our investors’ good graces.”                                                                                                                                                                                                                                                                          , Brooks Barnes contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/producer-prices-change </td>
   <td style="text-align:left;"> 2022-04-21 05:18:43 </td>
   <td style="text-align:left;"> South Korea Producer Prices Climb 8.8% YoY in March </td>
   <td style="text-align:left;"> Producer prices in South Korea rose 8.8 percent year-on-year in March of 2022, accelerating from an upwardly revised 8.5 percent advance in the previous month. Prices advanced faster for manufacturing products (14.6 percent vs 14.3 percent in February) and services (2.7 percent vs 2.5 percent), while they dropped at a softer pace for agriculture, forestry &amp; marine products (-13.7 percent vs -14.2 percent). In contrast, electricity, gas, water &amp; waste prices eased (11.6 percent vs 12.4 percent). On a monthly basis, prices went up 1.3 percent, after a revised 0.5 percent gain in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/20/business/economy/apple-store-union-atlanta.html </td>
   <td style="text-align:left;"> 2022-04-21 05:17:05 </td>
   <td style="text-align:left;"> Atlanta Apple Store Workers Are the First to Formally Seek a Union - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                 , The petition for a union vote continues a trend of organizing at service-sector employers like Starbucks and Amazon.                                                                                                                                                                                                                                                                                                          , By Noam Scheiber and Kellen Browning                                                                                                                                                                                                                                                                                                                                                                                          , Employees at an Apple store in Atlanta filed a petition on Wednesday to hold a union election. If successful, the workers could form the first union at an Apple retail store in the United States.                                                                                                                                                                                                                           , The move continues a recent trend of service-sector unionization in which unions have won elections at Starbucks, Amazon and REI locations.                                                                                                                                                                                                                                                                                   , The workers are hoping to join the Communications Workers of America, which represents workers at companies like AT&amp;T Mobility and Verizon, and has made a concerted push into the tech sector in recent years.                                                                                                                                                                                                               , The union says that about 100 workers at the store — at Cumberland Mall, in northwest Atlanta — are eligible to vote, including salespeople and repair technicians, and that over 70 percent of them have signed authorization cards indicating their support.                                                                                                                                                                , In a statement, the union said Apple, like other tech employers, had effectively created a tiered work force that denied retail workers the pay, benefits and respect that workers earned at its corporate offices.                                                                                                                                                                                                           , Workers said they loved working at Apple but sometimes felt they were treated like second-class employees. “We want equal to what corporate actually gets,” said Sydney Rhodes, an employee at the store who is involved in the union campaign.                                                                                                                                                                               , Ms. Rhodes, who has worked at Apple for four years, said that she and many of her co-workers hoped to continue working for Apple for years to come but that it was often unclear how they could progress within the company. “Another reason why we're working toward this union is for a more clear and concise way to grow, especially internally,” she added.                                                              , An Apple spokesman said the company offered strong benefits, including health care coverage, tuition reimbursement and paid family leave, and a minimum pay rate of $20 per hour for retail workers.                                                                                                                                                                                                                          , “We are fortunate to have incredible retail team members, and we deeply value everything they bring to Apple,” the spokesman said, but declined to comment on the union effort. The company would not say whether it would recognize the union voluntarily.                                                                                                                                                                   , Officials at the National Labor Relations Board will next determine whether there is sufficient interest among workers to hold an election — the bar is officially 30 percent — and set the terms for a potential vote. Both the union and the employer will have an opportunity to weigh in on the details, including the universe of employees eligible to take part and whether the vote should occur by mail or in person., Other unions, most notably Workers United, an affiliate of the giant Service Employees International Union that has led the organizing campaign at Starbucks, are also seeking to unionize Apple retail workers, of which there are tens of thousands in the United States.                                                                                                                                                   , Workers at an Apple Store at Grand Central Terminal in New York City have begun to sign authorization cards that could lead to a filing for a union vote that would allow them to join Workers United. The move was reported over the weekend by The Washington Post.                                                                                                                                                         , Activism and labor organizing at Apple have been building since last summer, when discontent over the company’s plan to require employees to return to the office snowballed into a broader movement, called #AppleToo. That movement aimed to highlight workplace problems like harassment, unequal pay and what workers described as a culture of secrecy that pervaded the company.                                        , “Apple workers across every line of business and around the world are using their voices to demand better treatment,” Janneke Parrish, one of the #AppleToo leaders, said of the union effort. Ms. Parrish has said Apple fired her in retaliation for her organizing. “I’m so happy to see workers taking this big step to stand up for their rights,” she said. Apple has disputed Ms. Parrish’s accusations.               , The #AppleToo movement included retail workers, who have said throughout the pandemic that Apple did not do enough to keep them safe from the coronavirus.                                                                                                                                                                                                                                                                    , Retail workers’ complaints escalated late last year when the Omicron variant spread rapidly throughout the country and at least 20 Apple stores had to close temporarily as a precaution or because so many of their workers had become infected that the stores could no longer operate. On Christmas Eve, several dozen Apple workers walked off their jobs to demand better pay and working conditions.                    , Ms. Rhodes said that the effort at her store began in earnest last fall, and that her co-workers had taken encouragement from the union campaigns at companies like Starbucks and Amazon.                                                                                                                                                                                                                                     , Beyond its overtures at Apple, the communications workers union has had a presence at Google in recent years, helping workers form a so-called solidarity or minority union that enables them to coordinate actions without holding a union election and seeking certification from the labor board. Companies are not required to bargain with minority unions, as they are with more formal unions.                         , The union also recently won a vote to represent about one dozen retail employees at Google Fiber stores in Kansas City, Mo., who are formally employed by a Google contractor. It is seeking to represent a few dozen Wisconsin-based quality assurance workers at the video-game maker Activision Blizzard, which Microsoft is acquiring, pending approval from regulators.                                                  , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/20/stocks-making-the-biggest-moves-after-hours-tesla-united-carvana-and-more.html </td>
   <td style="text-align:left;"> 2022-04-21 05:03:06 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Tesla, United, Carvana and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                   , Check out the companies making headlines after the bell:                                                                                                                                                                                                                                                                                                                                                                          , Tesla — Shares of the electric vehicle maker rose 4% in extended trading after a better-than-expected earnings report. Tesla posted earnings of $3.22 per share on revenue of $18.76 billion. Analysts expected a profit of $2.26 per share on revenue of $17.8 billion, according to Refinitiv.                                                                                                                                  , United Airlines — The airline stock rose 5.6% after hours despite first-quarter results missing estimates. United reported an adjusted first-quarter loss of $4.24 per share on revenue of $7.57 billion. Analysts surveyed by Refinitiv had expected a loss per share of $4.22 on revenue of $7.68 billion. However, United issued its strongest second-quarter guidance in history and said it expects to be profitable in 2022., CSX — Shares of the rail transportation company added 2.2% in extended trading after a quarterly revenue beat. CSX posted revenue of $3.41 billion versus $3.3 billion expected, according to Refinitiv.                                                                                                                                                                                                                          , Carvana — Shares sunk about 24% after hours following a wider-than-expected loss per share. Carvana posted a loss of $2.89 per share versus the Refinitiv consensus estimate of $1.44 per share.                                                                                                                                                                                                                                  , Lam Research — The semiconductor stock fell 1.8% in extended trading after a weak quarterly report. Lam Research reported adjusted third-quarter earnings of $7.40 per share on revenue of $4.06 billion. Analysts had expected a profit of $7.51 per share on revenue of $4.25 billion, according to Refinitiv.                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/20/politics/service-member-dead-hawaii/index.html </td>
   <td style="text-align:left;"> 2022-04-21 04:55:14 </td>
   <td style="text-align:left;"> US service member dies during training event in Hawaii  - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)A US service member died while participating in a training event at the Marine Corps base in Kaneohe Bay, Hawaii, on Sunday, a statement from the Navy Expeditionary Combat Command Public Affairs said.                                                                                                                                                                                                                                                  , The service member, Lt. j.g. Aaron Fowler, became unresponsive during the training event and was pronounced dead at the hospital, the release said. He was 29 years old.                                                                                                                                                                                                                                                                                        , Fowler, a US Navy service member, joined in 2012 and became a commissioned officer after graduating from the Naval Academy in May 2018. He reported to the Navy's Explosive Ordnance Disposal Mobile Unit in January 2022.                                                                                                                                                                                                                                      , The incident is "under investigation" by the Naval Criminal Investigative Service and local authorities, the release said. The US Navy did not say what Fowler was doing when he became unresponsive during the training event or provide details about the training event.                                                                                                                                                                                     , The unit of the Navy that Fowler was part of, based in San Diego, clears "explosive hazards to provide access to denied areas," and also secures "the undersea domain for freedom of maneuver, building and fostering relationships with capable partners and protecting" the US, the release said.                                                                                                                                                             , "Our deepest sympathies go out to Aaron's family and friends, and we join them in remembering and mourning this brave warrior," Rear Adm. Joseph Diguardo Jr., commander of the Navy Expeditionary Combat Command, said in the release. "His decision to join this elite special operations community was a testament to the dedicated and selfless character he embodied and his legacy will endure in our ranks through those he inspired by his service."    , CORRECTION: An earlier version of this story gave the wrong branch of the service that Lt. j.g. Aaron Fowler was a member of. He was in the Navy.                                                                                                                                                                                                                                                                                                               , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-04-21 04:55:00 </td>
   <td style="text-align:left;"> US Natural Gas Extends Decline </td>
   <td style="text-align:left;"> US natural gas futures extended losses below $6.9 per million British thermal units, almost 15% down from an over thirteen-year high of $8.065 hit at the start of the week, as forecasts indicating a turn to slightly warmer weather spooked investors. Still, the contract is up roughly 90% this year, as harsh wintry weather extended well into spring, causing domestic inventories to shrink well below the five-year average. Earlier this week, an unexpected blizzard dropped more than a foot of snow in the northeast of the US, cutting power to hundreds of households and boosting heating demand, which should further pressure the replenishment of natural gas stocks. At the same time, the US is exporting LNG cargoes at record levels, mainly to Europe, as the region scrambles to replace Russian gas. On the downside, natural gas output in China is soaring after Beijing pressured state-owned producers to ramp up production to cut LNG imports, which have already fallen 11% over the first quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61164894?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-21 04:40:51 </td>
   <td style="text-align:left;"> Germany rules out immediate end to Russian oil imports </td>
   <td style="text-align:left;"> Germany is moving "as fast as possible" to end its reliance on Russian energy, but it will take time, the country's finance minister has said.                                                                                                                                      , "We have to be patient," Christian Lindner told the BBC.                                                                                                                                                                                                                            , By contrast, Foreign Minister Annalena Baerbock had earlier said Germany would end oil imports by the end of the year, with gas following.                                                                                                                                          , Ukraine's president Volodymyr Zelensky has criticised Germany for failing to curb Russian energy imports.                                                                                                                                                                           , He described energy payments as "blood money".                                                                                                                                                                                                                                      , Proceeds from the sale of Russian oil and gas amount to around $1bn (£770m) a day, undermining international efforts to put economic pressure on President Vladimir Putin to end the war.                                                                                           , The US has already banned Russian oil imports and the UK plans to phase them out by the end of the year.                                                                                                                                                                            , But EU countries are more heavily dependent on Russian energy, with Germany currently buying around 25% of its oil and 40% of its gas from Russia.                                                                                                                                  , Mr Lindner told the BBC that his country was working to implement an embargo on Russian energy but that he preferred using sanctions which "hurt [Putin] more than us".                                                                                                             , He said a sudden halt to Russian energy imports could see the physical shutdown of German producers such as manufacturers and carmakers.                                                                                                                                            , Earlier this week, German economic institutes warned that immediately halting Russian imports would spark a sharp recession in Europe's biggest economy by 2023.                                                                                                                    , "We are willing to stop all energy imports from Russia, it's just a matter of time," said Mr Lindner, who is leader of the liberal Free Democrats, one constituent of Germany's coalition government.                                                                               , He insisted that any calculation on Vladimir Putin's part that Germany would continue to rely on Russian energy was "wrong".                                                                                                                                                        , "In the end, we don't want to have any further business with Putin," he said.                                                                                                                                                                                                       , However his stance was at odds with statements made by Germany's foreign minister, Ms Baerbock, who is Green Party co-leader.                                                                                                                                                       , Ms Baerbock said Germany would halve Russian oil imports by the summer and eliminate them altogether by the end of the year, to be followed quickly by a reduction in Russian gas imports.                                                                                          , Germany's finance minister was keen to sound tough on Russia and appears acutely aware of the criticism levelled at his country for dragging its feet over a full energy embargo on the Kremlin.                                                                                    , His basic message was - it is coming, but not quite yet, because it is impossible to enact immediately and would probably lead to shutdowns of large swathes of the German economy.                                                                                                 , President Zelensky used a BBC interview last week to demand an immediate embargo on Russia's lucrative oil trade, accusing those sending euros and dollars to Kremlin-controlled oil giants of "trading in blood". He singled out Germany alongside Hungary for blocking EU action. , Mr Lindner said Germany would move as fast as possible, but did not confirm that would be within a year.                                                                                                                                                                            , In Berlin this issue appears to be putting some stress on the three-party governing coalition. Mr Lindner leads the free market FDP, not the normal bedfellows for the Social Democrats and Greens.                                                                                 , Meanwhile Green Party leader Annalena Baerbock, also the foreign minister, said dependence on Russian oil would definitely finish by the end of the year. The Chancellery under Olaf Scholz appears to be the most cautious on this issue.                                          , Germany has already called off the opening of Russia's Nord Stream 2 gas pipeline in response to the war, a project pursued by previous governments of different political stripes.                                                                                                 , But Mr Lindner said he was concerned about the macroeconomic effects an overnight shut-off of Russian energy would cause.                                                                                                                                                           , "I don't fear [the] economic costs [of buying less Russian energy]. I fear the physical scenario, if you have to stop the supply, for a complete production line, this causes more than economic costs," Mr Lindner told the BBC.                                                   , "I think it's preferable to have sanctions, which we can stand for months, for years," he said.                                                                                                                                                                                     , Mr Lindner said Russia's invasion of Ukraine was the root cause of growing geopolitical and economic risks including inflation, food shortages and a debt crisis for low income countries.                                                                                          , But he also criticised the approach of previous Berlin governments of relying on Russia for oil and gas.                                                                                                                                                                            , "It was a strategic miscalculation from German governments, over the last two decades, and now we have to work on energy diversification," he said.                                                                                                                                 , Bill Bailey on Eurovision and the inspiration for his new show                                                                                                                                                                                                                      , Incredible new drama Life After Life                                                                                                                                                                                                                                                , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                                                                     , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ual:us </td>
   <td style="text-align:left;"> 2022-04-21 04:36:45 </td>
   <td style="text-align:left;"> United Airlines Holdings earnings below expectations at -4.24 USD </td>
   <td style="text-align:left;"> United Airlines Holdings (UAL) released earnings per share at -4.24 USD, compared to market expectations of -4.14 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/aa:us </td>
   <td style="text-align:left;"> 2022-04-21 04:36:38 </td>
   <td style="text-align:left;"> Alcoa earnings above expectations at 3.06 USD </td>
   <td style="text-align:left;"> Alcoa (AA) released earnings per share at 3.06 USD, compared to market expectations of 2.79 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/stld:us </td>
   <td style="text-align:left;"> 2022-04-21 04:36:28 </td>
   <td style="text-align:left;"> Steel Dynamics earnings above expectations at 5.71 USD </td>
   <td style="text-align:left;"> Steel Dynamics (STLD) released earnings per share at 5.71 USD, compared to market expectations of 5.42 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/efx:us </td>
   <td style="text-align:left;"> 2022-04-21 04:36:19 </td>
   <td style="text-align:left;"> Equifax earnings above expectations at 2.22 USD </td>
   <td style="text-align:left;"> Equifax (EFX) released earnings per share at 2.22 USD, compared to market expectations of 2.16 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kmi:us </td>
   <td style="text-align:left;"> 2022-04-21 04:36:13 </td>
   <td style="text-align:left;"> Kinder Morgan earnings above expectations at 0.32 USD </td>
   <td style="text-align:left;"> Kinder Morgan (KMI) released earnings per share at 0.32 USD, compared to market expectations of 0.28 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/lrcx:us </td>
   <td style="text-align:left;"> 2022-04-21 04:36:06 </td>
   <td style="text-align:left;"> Lam Research earnings below expectations at 7.40 USD </td>
   <td style="text-align:left;"> Lam Research (LRCX) released earnings per share at 7.40 USD, compared to market expectations of 7.56 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cci:us </td>
   <td style="text-align:left;"> 2022-04-21 04:35:59 </td>
   <td style="text-align:left;"> Crown Castle International earnings above expectations at 0.97 USD </td>
   <td style="text-align:left;"> Crown Castle International (CCI) released earnings per share at 0.97 USD, compared to market expectations of 0.94 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/tsla:us </td>
   <td style="text-align:left;"> 2022-04-21 04:35:45 </td>
   <td style="text-align:left;"> Tesla earnings above expectations at 3.22 USD </td>
   <td style="text-align:left;"> Tesla (TSLA) released earnings per share at 3.22 USD, compared to market expectations of 2.24 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/20/business/tesla-first-quarter-earnings.html </td>
   <td style="text-align:left;"> 2022-04-21 04:34:10 </td>
   <td style="text-align:left;"> Tesla’s Profits Jumped in the First Quarter but Challenges Loom - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                  , The electric carmaker had to close an important factory in Shanghai because of China’s efforts to stamp out a coronavirus outbreak.                                                                                                                                                                                                                            , By Jack Ewing                                                                                                                                                                                                                                                                                                                                                  , Tesla said on Wednesday that it made a $3.3 billion profit in the first three months of the year, up from $438 million a year earlier and the biggest quarterly profit since the company’s creation. But Tesla also said it expected its factories to run below capacity for the rest of 2022.                                                                 , The electric carmaker said its revenue in the first quarter totaled $18.8 billion, up from $10.4 billion a year earlier. The profit significantly exceeded investor expectations.                                                                                                                                                                              , Tesla was the fastest-growing major carmaker last year, nearly doubling sales to almost one million vehicles while the industry as a whole slumped. New factories near Austin, Texas, and Berlin position the company to repeat that growth this year — if it can overcome some serious challenges.                                                            , These include a semiconductor shortage that has plagued automakers for more than a year. Tesla has also had to shut down its factory in Shanghai because of China’s draconian attempts to contain the coronavirus. China accounted for one-quarter of Tesla sales last year, and the plant in Shanghai also exports cars to other countries in Asia and Europe., Tesla said on Wednesday that it had resumed “limited production” in Shanghai after a three-week shutdown. But it warned that it continued to face “persistent” supply-chain problems as well as rising costs for raw materials.                                                                                                                                , “Our own factories have been running below capacity for several quarters as supply chain became the main limiting factor, which is likely to continue through the rest of 2022,” Tesla said in a statement.                                                                                                                                                    , Tesla’s chief executive, Elon Musk, said on a conference call with investors and analysts on Wednesday that his “best guess” was that Tesla would produce 1.5 million cars this year, meeting the company’s goal of achieving sales growth of 50 percent a year.                                                                                               , Analysts are worried that supply-chain and production problems, which Tesla did a better job of avoiding last year than other automakers did, could hamper the company’s growth this year.                                                                                                                                                                     , “A robust demand story for Tesla is being overshadowed by brutal production issues in China as well as a Rubik’s cube supply chain, which continues to haunt Tesla as well as the rest of the auto/tech industry,” analysts at Wedbush Securities said in a note to clients ahead of Tesla’s first-quarter earnings announcement.                              , Mr. Musk said soaring prices for lithium were forcing the company to raise prices, potentially slowing the pace at which people switch to electric vehicles. Some lithium producers are enjoying 90 percent profit margins, he added.                                                                                                                          , The offer. Elon Musk, the world’s wealthiest man, made an unsolicited bid worth more than $43 billion for the social media company. Mr. Musk said that he wanted to make Twitter a private company and that he wanted people to be able to speak more freely on the service.                                                                                   , Twitter’s response. The social media company countered the offer with a defense mechanism known as a “poison pill.” This well-worn corporate tactic makes a company less palatable to a potential acquirer by making it more expensive for them to buy shares above a certain threshold.                                                                       , What’s next? Major questions remain about Mr. Musk’s bid for Twitter, including whether he will pursue a hostile takeover. While Mr. Musk races to secure funding for his offer, Apollo Global Management is considering offering debt financing in a bid for Twitter.                                                                                         , “Can more people please get into the lithium business?” he said. “Do you like minting money? Then the lithium business is for you.”                                                                                                                                                                                                                            , Mr. Musk hinted that Tesla could get more involved in the supply chain for raw materials but did not say whether it would expand into mining metals like lithium directly. “We are looking at all the raw materials and looking carefully,” he said. “We think we will have some exciting announcements in the months to come.”                                , Tesla remains the largest manufacturer of battery-powered cars by far. During the first three months of 2022, it sold 310,000 vehicles, an increase of almost 70 percent from a year earlier. But traditional automakers like Volkswagen, Ford Motor and Hyundai Motor have woken up to the threat and begun selling models that challenge Tesla’s dominance.  , There is also a risk that Mr. Musk could alienate some car buyers with his high-profile offer to buy Twitter. Some potential customers may applaud Mr. Musk as a champion of free speech, but others may fear he will open up Twitter to hate speech and misinformation.                                                                                       , Mr. Musk did not discuss and was not asked about his proposed acquisition of Twitter on the call.                                                                                                                                                                                                                                                              , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-04-21 04:23:34 </td>
   <td style="text-align:left;"> Bovespa Falls for Fourth Day </td>
   <td style="text-align:left;"> Brazil's main stock extended losses for the fourth straight session on Wednesday, with the benchmark Bovespa finishing around the 114,250 level, dragged by heavyweight Vale amid lower iron ore production. Meanwhile, investors await the release of some economic data after central bank employees approve the suspension of a strike that began earlier this month over wage demands. Natura &amp; Co Holding plunged more than 15%, the most on the index, and the second biggest loser was Cogna Educacao, down 7.7%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-04-21 04:07:00 </td>
   <td style="text-align:left;"> TSX Ends Virtually Flat </td>
   <td style="text-align:left;"> Canadian shares finished virtually flat on Wednesday, with the benchmark S&amp;P/TSX composite hovering around the 22,000 level as gains in the heavyweight energy sector offset losses in technology and healthcare. On the data front, Canada's consumer prices jumped 6.7% over a year earlier in March, the quickest advance since January of 1991, which further strengthened the case for monetary policy tightening by the Bank of Canada. At its April meeting, the central bank raised its interest rates in a rare 50 bps hike, and policymakers warned of further rate hikes if inflationary pressures persisted well above target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/csx:us </td>
   <td style="text-align:left;"> 2022-04-21 04:04:27 </td>
   <td style="text-align:left;"> CSX earnings above expectations at 0.39 USD </td>
   <td style="text-align:left;"> CSX (CSX) released earnings per share at 0.39 USD, compared to market expectations of 0.38 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-21 04:02:00 </td>
   <td style="text-align:left;"> Wall Street Ends Mixed as Netflix Drags on Tech </td>
   <td style="text-align:left;"> The Dow finished Wednesday's session up 0.7%, while the S&amp;P 500 and the Nasdaq underperformed by falling 0.1% and 1.2%, respectively, as investors digested a slew of earnings reports. Procter &amp; Gamble and IBM earnings beat forecasts, while P&amp;G saw its sharpest year-over-year sales gain in two decades, and IBM beat estimates on both earnings and revenue. On the flip side, Netflix sank almost 40% after reporting it lost 200K subscribers during the first quarter. That was its sharpest decline since 2004, and the streaming company is now the worst-performing stock in the S&amp;P 500 this year. Also, both earnings and revenues from Baker Hughes missed expectations. Aside from one of the busiest weeks in the US earnings season, investors have been digesting hawkish comments from several Fed policymakers, signalling that the central bank heads for a more aggressive tightening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-ends-higher-second-day/story.aspx?guid={2B6D329C-BB52-43B0-934E-124B8D71F7B1}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-21 04:01:32 </td>
   <td style="text-align:left;"> Dow ends higher for second day, but S&amp;P 500 and Nasdaq fall - MarketWatch </td>
   <td style="text-align:left;"> Major U.S. stock indexes finished mostly lower on Wednesday, with the Nasdaq Composite pulled down by tumbling shares of Netflix 
        NFLX,
        -35.12%
       a day after the streaming service reported a net loss of 200,000 paid subscribers in the first quarter. The Dow Jones Industrial Average 
        DJIA,
        +0.71%
       gained about 250 points, or 0.7%, ending a second day in a row higher near 35,160. The S&amp;P 500 index 
        SPX,
        -0.06%
       shed 0.1%, while the Nasdaq 
        COMP,
        -1.22%
       closed 1.2% lower. Investors remain focused on quarterly earnings season, looking for hints as to how big companies and consumers have been managing inflation at a 40-year high. San Francisco Federal Reserve president Mary Daly said Wednesday the central bank should act quickly to move its policy rate to neutral levels, or 2.5% according to most forecasts. The Fed's Beige Book report also showed expectations for inflation to continue running hot in the coming months., ​"As momentous as Russia's invasion of Ukraine is, the most strategically important event in recent weeks was the global economic war between Russia and the U.S. and its allies. Russia, however, has been preparing to confront the West and challenge the Western socio-economic model for a long time,"  Antonia Colibasanu writes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Joy Wiltermuth is a news editor and senior markets reporter based in San Francisco. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/sanders-hasnt-ruled-out-another/story.aspx?guid={2ECB5487-E0CE-4420-A4F2-2A63E9180FC0}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-21 03:55:18 </td>
   <td style="text-align:left;"> Sanders hasn't ruled out another White House run if Biden doesn't: report  - MarketWatch </td>
   <td style="text-align:left;"> Sen. Bernie Sanders, a Vermont independent, is open to running for president in 2024 if President Joe Biden declines to seek reelection, the Washington Post reported Wednesday, citing a campaign memo. "In the event of an open 2024 Democratic presidential primary, Sen. Sanders has not ruled out another run for president, so we advise that you answer any questions about 2024 with that in mind," says the memo from Faiz Shakir, a close Sanders adviser who was his campaign manager when he ran in 2020. The Post said the memo was shared with the newspaper but that Shakir did not respond to a request for comment. Biden has said he intends to run for reelection, but as the Post writes, he cautioned last year that he had "never been able to plan 31/2, four years ahead, for certain."   , The Russian Defense Ministry reported the first launch of its new Sarmat intercontinental ballistic missile. President Vladimir Putin said this weapon is unique and will make those who threaten Russia “think twice.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/natural-gas-crisis-coming </td>
   <td style="text-align:left;"> 2022-04-21 03:51:43 </td>
   <td style="text-align:left;"> Is a natural gas crisis coming? </td>
   <td style="text-align:left;"> Lipow Oil Associates President Andy Lipow says the industry actually wants five times what President Biden is offering.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Along with spiking gas prices, President Biden can add natural gas to the trouble list.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The cleanest burning fossil fuel is in short supply around the globe, driving U.S. prices up 86% so far this year, flirting with levels we have not seen since 2008.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , As the world's largest producer, U.S. supplies hit a three-year low and are 18% below the average for this time of year, adding fuel to the inflation fire and creating a new energy headwind for President Biden.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , ENERGY INDEPENDENCE: WHERE DOES THE US GO FROM HERE?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , A Freeway Propane facility in Springville, Utah, on Oct. 20, 2021. (George Frey/Bloomberg via Getty Images)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Shoulder season in natural gas is the typically low-demand period, March through April, when people rely less on natural gas to heat and cool their homes. Yet, this year with winter hanging on, demand is staying unseasonably strong.  Now if we flip to a hot streak when we use more natural gas to create electricity to power our air conditioners, we are starting to make a tight market even worse. This is normally a time when we can build natural gas inventories, but winter has other ideas.                                                                                                                                                                                        , IS THE US IN A HOUSING BUBBLE?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Biden came into office trying everything he could to discourage natural gas production on federal lands that supply 15% of the U.S. natural gas supply, which has only caused the situation to get worse because the decline rate of existing wells is leading to lower production.                                                                                                                                                                                                                                                                                                                                                                                                                 , Adding to the crunch, Biden took it upon himself to pledge an additional 15 billion cubic feet (bcf) of liquefied natural gas (LNG) to Europe through the remainder of 2022 as the Russia, Ukraine conflict rages on. The agreement additionally promises to increase that supply to Europe to 50 bcf through 2030.                                                                                                                                                                                                                                                                                                                                                                                 , RUSSIA, UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Yet again here comes a contradiction in America’s energy policy. How can you continue to discourage natural gas production at home yet promise more supply to Europe?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Is this not only going to add to the cost for the U.S. consumer? Believe me, I am all for LNG exports, but that should be met with more investment in U.S. production and infrastructure so we can help supply the world. The U.S. has been blessed with abundant natural gas supply that we could use to help supply the world and lead the fight against climate change by supplying the world with cleaner-burning natural gas.                                                                                                                                                                                                                                                                  , Natural gas can replace coal and dirty oil, something that Europe has had to rely more on because of its over-reliance on Russia for gas. By the end of 2022, the U.S. will have the largest LNG export capacity in the world with the completion of the Sabine Pass and Calcasieu Pass facilities in Louisiana, as well as upgrades to increase production at several existing facilities. Yet we could do more if President Biden allows the U.S. energy industry to do its job.                                                                                                                                                                                                                  ,  If you can't lead, then at least get out of the way.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , READ MORE ON FOX BUSINESS BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Phil Flynn is senior energy analyst at The PRICE Futures Group and a Fox Business Network contributor. He is one of the world's leading market analysts, providing individual investors, professional traders, and institutions with up-to-the-minute investment and risk management insight into global petroleum, gasoline, and energy markets. His precise and timely forecasts have come to be in great demand by industry and media worldwide and his impressive career goes back almost three decades, gaining attention with his market calls and energetic personality as writer of The Energy Report. You can contact Phil by phone at (888) 264-5665 or by email at pflynn@pricegroup.com. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-21 03:47:00 </td>
   <td style="text-align:left;"> Canada 10Y Bond Yield Hits 10-year High </td>
   <td style="text-align:left;"> Canada's 10-year government bond yield topped 2.83% in April, a level not seen since June 2011, as markets move to price in more aggressive monetary policy tightening following a hotter-than-expected inflation reading. Canada's consumer prices jumped 6.7% over a year earlier in March, the quickest advance since January 1991. Earlier this month, the Bank of Canada increased its target for the overnight rate by 50bps to 1% in its April meeting, a move not seen since May 2000 and pushing borrowing costs to the highest level since the coronavirus pandemic started. Policymakers added that interest rates would need to rise further as the economy moves into excess demand and inflation persists well above target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/has-inflation-peaked-in-the-us </td>
   <td style="text-align:left;"> 2022-04-21 03:25:17 </td>
   <td style="text-align:left;"> Has inflation peaked in the US? </td>
   <td style="text-align:left;"> Economist Geoffrey Okamoto weighs in on the IMF cutting global growth forecasts on the Russia-Ukraine war.                                                                                                                                                                                                                                                                                                                    , Inflation is running at the hottest pace in more than four decades, and consumer prices could march even higher before they begin to subside.                                                                                                                                                                                                                                                                                 , The Labor Department reported last week that the consumer price index, which measures a bevy of goods including gasoline, health care, groceries and rents, rose 8.5% in March from a year ago, the fastest pace since December 1981. Prices jumped 1.2% in the one-month period from February, the largest month-to-month jump since 2005.                                                                                   , INFLATION THREATENS TO UNDERCUT BIDEN'S INFLATION PLAN                                                                                                                                                                                                                                                                                                                                                                        , The reading elicited some hope among economists that inflation may have peaked: That's because the largest driver of higher inflation last month was higher energy costs — a reflection of the Russian war in Ukraine, which sent gas prices in the U.S. to the highest since 2008.                                                                                                                                           , Energy prices rose a stunning 11% in March from the previous month, and are up 32% from last year. Gasoline, on average, costs 48% more than it did last year after rising 18.3% in March on a monthly basis as the Russian war in Ukraine fueled a rapid increase in oil prices.                                                                                                                                             , "Inflation likely peaked in March, with the biggest contributions coming from gasoline and food prices, which could stabilize in the next few months," said Robert Frick, a corporate economist at the Navy Federal Credit Union. "But high inflation will be with us at least through the summer because increases in other prices, especially shelter and services, will be sticky."                                        , By stripping out gas and food prices, which are more volatile, so-called core prices climbed 6.5% in March from the previous year — up from the 6.4% increase recorded in February. It was the steepest 12-month increase since August 1982. However, on a month-over-month basis, prices rose just 0.3% in March, compared it 0.5% in February. It marked the lowest increase since September 2021.                          , People shop for groceries at a supermarket in Glendale, California Jan. 12, 2022.  (ROBYN BECK/AFP via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                           , Others are more skeptical that rising prices are beginning to subside: RSM chief economist Joe Brusuelas told FOX Business that he thinks the inflation wave has "probably not" crested yet, though the end could soon be in sight.                                                                                                                                                                                           , "If the status quo holds, we're almost certain to observe a peak of inflation this quarter," Brusuelas said. "The topline number should drop rather sharply in coming months."                                                                                                                                                                                                                                                , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                   , There are three major risks to the inflation outlook right now, all of which are external to the workings of the U.S. economy, he said: a wider conflict breaking out in Eastern Europe, the European Union cutting off imports of oil and natural gas — which would send oil prices higher and drag gas prices with them — and persistent COVID-19 lockdowns in China that further exacerbate already snarled supply chains. , "Inflation should ease here," Brusuelas said. "But it will probably be two to three years before we’re back towards anywhere near 2%," which is the Federal Reserve's preferred target for inflation.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/argentina/balance-of-trade </td>
   <td style="text-align:left;"> 2022-04-21 03:23:09 </td>
   <td style="text-align:left;"> Argentina Trade Surplus Narrows in March </td>
   <td style="text-align:left;"> Argentina's trade surplus narrowed to USD 279 million in March of 2022 from USD 400 million in the corresponding month of the previous year. Exports rose 28.5 percent from a year earlier to USD 7,352 million, due to higher sales of agricultural manufactures (10.5 percent), primary goods (36.8 percent); industrial manufacturing (32.3 percent) and fuels &amp; energy (118.1 percent). Meanwhile, imports advanced 33.0 percent to USD 7,073 million, boosted by purchases of intermediate products (18.5 percent), capital goods (37.8 percent), parts &amp; accessories for capital goods (20.3 percent), and fuels &amp; lubricants (195.7 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/rite-aids-stock-rockets-after/story.aspx?guid={7BC040CC-CC01-4DC2-8414-BF2947F320A7}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-21 03:21:05 </td>
   <td style="text-align:left;"> Rite Aid's stock rockets after the New York Post reported it rejected a buyout bid at a hefty premium - MarketWatch </td>
   <td style="text-align:left;"> Shares of Rite Aid Corp. 
        RAD,
        +10.81%
       rocketed as much as 38.5% intraday before paring gains to be up 18.7% in very active afternoon trading Wednesday, after the New York Post reported that the drugstore chain rejected earlier this month a buyout bid that valued the company at more than $800 million. Trading volume swelled to about 16 million share, compared with the full-day average of about 4.3 million shares. On March 30, private-equity firm Spear Point Capital Management said it would pay $14.60 for each Rite Aid shares outstanding, the New York Post reported, citing Spear Point co-Founder Ron Bienvenu. That represents a 56.0% premium to the March 30 closing price of $9.36, and a 97.3% premium to Tuesday's closing price of $7.40. After Rite Aid followed by rejecting the bid, Spear Point's Bienvenu told the NYP that the firm is considering a hostile tender offer directly to shareholders. The company's market capitalization is currently about $489.8 million. Rite Aid's stock had closed at a 2 1/2-year low of $6.99 on April 7, which was a week before the company reported a wider-than-expected fiscal fourth-quarter loss. The stock has tumbled 40.2% year to date, while the S&amp;P 500 
        SPX,
        -0.06%
       has slipped 6.3%. , Hulu, Disney+, Amazon Prime and a host of other streamers are playing hard ball.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/just-eat-takeaway-grubhub-sale </td>
   <td style="text-align:left;"> 2022-04-21 03:13:49 </td>
   <td style="text-align:left;"> GrubHub owner exploring full or partial sale </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.                                                                                                                                                                                                                                                                                                                                                                                                                                   , Less than a year after completing its $7.3 billion acquisition of Grubhub, Just Eat Takeaway is considering selling the platform following a decline in online food orders.                                                                                                                                                                                                                                                                                                     , A food delivery courier for Grubhub Inc. wears a protective mask in New York on April 6, 2020. (Jeenah Moon/Bloomberg via Getty Images)                                                                                                                                                                                                                                                                                                                                         , A spokesperson for Just Eat Takeaway told FOX Business that there is interest for a "full or partial sale," but declined to disclose specific potential buyers.                                                                                                                                                                                                                                                                                                                 , "Just Eat Takeaway.com has always stated that we are open to exploring opportunities to further strengthen Grubhub’s position," the spokesperson added. "We have been in discussions with parties regarding strategic partners and have looked at all options on the table in order to explore full value for our shareholders."                                                                                                                                                , AZ BREWERY HAD TO PAY $12K EXTRA TO GET A PRODUCT SHIPPED AMID SUPPLY CHAIN CRISIS                                                                                                                                                                                                                                                                                                                                                                                              , Just Eat Takeaway has benefited from a rapidly increasing consumer base as a result of the COVID-19 pandemic, adding more than 20 million active consumers since April 2020. However, the company says it is experiencing a "higher-than-normal absolute churn level in the first half of 2022."                                                                                                                                                                                , The company reported 264.1 million orders across the globe and 89.6 million orders in North America in the first quarter of 2022, representing declines of 1% and 4%, respectively, compared to 267.1 million global orders and 94.7 million North American orders during the same period a year ago. Gross transaction volume amounted to €7.2 billion in the first quarter of 2022, up 4% compared with the same period of 2021, driven by a higher average transaction value., "Our North American division has continued to perform well in spite of the impact of fee caps, which had a €192 million EBITDA impact over the last year," the spokesperson added. "Grubhub at its core is a very healthy, and growing, business which is near to profitability, and would be, despite the impact of fee caps."                                                                                                                                                 , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                         , Going forward, the company is focused on enhancing profitability by increasing revenue per order, improving courier costs per order and reducing over and operating expenses. While the company warned that second quarter growth will "remain challenging," it expects average monthly order frequency and returning customers to be above both pre-pandemic and pandemic levels.                                                                                              , Just Eat Takeaway expects year-over-year gross transaction volume growth in the mid-single digits in 2022, compared to previous guidance of GTV growth in the mid-teens, and an adjusted EBITDA margin in the range of -0.5% to -0.7% of GTV, compared to previous guidance of -0.6% to -0.8%.                                                                                                                                                                                  , Management expects to reach positive adjusted EBITDA for the full year 2023. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/20/feds-daly-says-the-economy-can-handle-rate-hikes-but-a-mild-recession-is-possible.html </td>
   <td style="text-align:left;"> 2022-04-21 03:12:04 </td>
   <td style="text-align:left;"> Fed's Daly says the economy can handle rate hikes, but a mild recession is possible </td>
   <td style="text-align:left;"> , San Francisco Federal Reserve President Mary Daly acknowledged Wednesday that a near-certain series of interest rate hikes over the coming months could tip the economy into a shallow recession, though she noted that isn't her expectation.                                                                                                                                          , Responding to the worst inflation the U.S. has seen in more than 40 years, the central bank official said she foresees "an expeditious march" through the year toward benchmark interest rates that would neither stimulate nor repress growth — the "neutral" rate, in Fed parlance.                                                                                                   , "Accounting for the risks of being too fast or too slow, I see an expeditious march to neutral by the end of the year as a prudent path," she said.                                                                                                                                                                                                                                     , The moves, Daly said, would help slow down an overheated economy that now has consumer price inflation running at an 8.5% annual pace.                                                                                                                                                                                                                                                  , She cited research from Princeton economist and former Fed vice chair Alan Blinder, who asserted that in 11 previous Fed hiking cycles, seven "were followed by a mild recession or none at all — basically a smooth landing," she said in remarks at the University of Nevada Las Vegas. "Now, since I'm in Las Vegas, I will offer that I think those are pretty good odds."          , Asked later whether she considered a mild recession to be the equivalent of a soft landing or acceptable outcome, Daly said her outlook is for the economy to slow to "something that looks like below-trend growth, but not tip into negative territory, but could potentially tick into negative territory."                                                                          , That likely would mean a shallow recession, unlike those associated with, for instance, the financial crisis of 2008 or the stagflation days of the late 1970s and early '80s, when then-Chairman Paul Volcker jacked up rates so much that the economy fell into a double-dip recession.                                                                                               , Some Wall Street economists see recession risks rising. Deutsche Bank recently said it sees a near-certainty of negative growth, while Goldman Sachs indicated about a 35% chance over the next two years.                                                                                                                                                                              , "Recession is one word, but it describes a whole range of outcomes," Daly said in response to a CNBC question. "It can be a couple of quarters of a tiny bit below zero. That's a very different beast than something like the financial crisis or the Volcker disinflation period."                                                                                                    , "That's not something that I'm forecasting or something I think would derail the long-run expansion," she added.                                                                                                                                                                                                                                                                        , Markets currently expect the Fed to enact a series of aggressive interest rate hikes between now and the end of the year. Following a 25 basis point, or quarter percentage point, increase in March, the expectation is a series of 50 basis point moves then a slowdown that will take the benchmark fed funds rate to about 2.5% by the end of the year, according to CME Group data., Earlier in the day, Chicago Fed President Charles Evans said "I'm open to doing 50 basis point increases in order to front-load this a little bit." St. Louis Fed President James Bullard on Monday said he'd like to move even faster and thinks a 75 basis point move next month would be appropriate, though traders are pricing in no chance of that happening.                     , For her part, Daly said she doesn't want the Fed to slam on the brakes too quickly as that could endanger the pandemic-era recovery, which has been strong outside of the historic inflation move.                                                                                                                                                                                      , "If we ease on the brakes by methodically removing accommodation and regularly assessing how much more is needed, we have a good chance of transitioning smoothly and gliding the economy to its long-run sustainable path," she said.                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-settle-modest/story.aspx?guid={16B466CE-80B2-477A-8E3F-0F4BF8C7C424}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-21 02:38:58 </td>
   <td style="text-align:left;"> U.S. oil futures settle with a modest gain as traders weigh demand prospects, drop in U.S. supplies  - MarketWatch </td>
   <td style="text-align:left;"> U.S. oil prices posted a modest gain on Wednesday, finding some support following data from the Energy Information Administration, which showed a weekly drop of 8 million barrels in U.S. crude supplies. Prices, however, also saw pressure from worries about the demand outlook, and as Europe appeared reluctant to implement any sort of ban on Russian oil anytime soon. Germany, which gets about a quarter of its oil from Russia, said Wednesday that it will stop imports of Russian oil by the end of the year, according to a BBC News report. West Texas Intermediate crude for May delivery 
        CLK22,
        
       rose 19 cents, or 0.2%, to end at $102.75 a barrel on the contract's expiration day on the New York Mercantile Exchange. The new front month June contract 
        CLM22,
        +0.54%
       settled at $102.19, up 14 cents, or 0.1%., A new band of Wall Street analysts rushed to cut price targets and ratings on Netflix in response to deeply disappointing results, though shares of the pioneering streaming service have been under pressure for months.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/arizona-brewery-12k-shipped-supply-chain </td>
   <td style="text-align:left;"> 2022-04-21 02:21:18 </td>
   <td style="text-align:left;"> AZ brewery had to pay $12K extra to get a product shipped amid supply chain crisis </td>
   <td style="text-align:left;"> Brewery director for PHX Beer Co., Adam Wojcik, joined 'Fox &amp; Friends' to discuss the impacts of the supply chain shortages on the company.                                                                              , An Arizona brewery has taken a pricey hit as the global supply chain crisis continues.                                                                                                                                   , PHX Beer Co. brewery director Adam Wojcik shared with "Fox &amp; Friends" on Wednesday that a brewing tank he ordered back in May 2021 from China finally arrived — but that he was forced to pay an extra $12,000 to get it., Wojcik said that after standing by for a spot on a shipping boat that was "never guaranteed," his number was finally called.                                                                                             , Additional roadblocks due to supply chain issues pushed the delivery time to almost a year from the time of order.                                                                                                       , But the company warned him about a potential 10% increase in cost, due to shipping bottlenecks in Long Beach, Calif.                                                                                                     , RESTAURANTS USING PRE-MADE INGREDIENTS TO COMBAT LABOR SHORTAGES, SUPPLY ISSUES                                                                                                                                          , The "incredibly time-consuming" order and delivery process normally would have taken eight to 12 weeks.                                                                                                                  , But the additional roadblocks due to supply chain issues pushed the delivery time to almost a year from the time of order.                                                                                               , PHX Beer Co. brewery director Adam Wojcik joined "Fox &amp; Friends" on April 20, 2022, to share his company's story. (Christian Houda, PHX Beer Co.)                                                                        , Wojcik said the brewery had been excited to circumvent the oncoming shipping delays when it first placed the order for the tank — but it was thwarted nonetheless.                                                       , Even though President Joe Biden has echoed efforts to mend the global supply chain, Wojcik agreed the issue still is not fixed.                                                                                          , A PHX Beer Co. brewery tank in Arizona, as seen on "Fox and Friends" on April 20, 2022. (Christian Houda, PHX Beer Co.)                                                                                                  , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                  , The director admitted that the brewery is "starting to sweat a little" now as an increase in orders have come flowing in from a variety of customers.                                                                    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                              , "We’ve done a pretty good job of maintaining our inventories and getting beer to our customers," he said.                                                                                                                , "Right now is kind of the thick of it, as far as sales go in Arizona." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/elevated-inflation-supply-chain-snarls-us-businesses-federal-reserve-beige-book </td>
   <td style="text-align:left;"> 2022-04-21 02:10:33 </td>
   <td style="text-align:left;"> Elevated inflation, supply chain snarls weighing on US businesses, Fed's Beige Book says </td>
   <td style="text-align:left;"> Morgan Creek Capital Management's Mark Yusko weighs in on the markets and inflation.                                                                                                                                                                                                                                                                                                                                                                                                            , Supply chain bottlenecks, the highest inflation in decades and a persisting labor shortage are weighing on businesses across the country, according to a new Federal Reserve report.                                                                                                                                                                                                                                                                                                            , In its region-by-region roundup of anecdotal information known as the Beige Book, the Fed reported that while economic activity increased at a "moderate pace" in most of its 12 districts during the February through mid-April period that the report covers, firms continued to struggle with rising prices and a lack of available workers.                                                                                                                                                 , FED RAISES INTEREST RATES FOR FIRST TIME IN 3 YEARS, PROJECTS 6 MORE HIKES AS INFLATION SURGES                                                                                                                                                                                                                                                                                                                                                                                                  , Inflationary pressure remained "strong" over the past few months, the Beige Book reported, with widespread price increases in manufacturing, including steeper costs for raw materials, transportation and labor. Several districts also reported spikes in prices for energy, metals and agricultural commodities following the Russian invasion of Ukraine Feb. 24, while others noted the COVID-19 lockdown in China had exacerbated pandemic-induced disruptions in the global supply chain., Workers unload shipments of food at Union Market in Washington, D.C, Feb. 9, 2022.  (Stefani Reynolds/AFP via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                      , Many businesses said they were passing along the higher costs to customers.                                                                                                                                                                                                                                                                                                                                                                                                                     , "Strong demand generally allowed firms to pass through input cost increases to customers, for example, via fuel surcharges for freight and airline fares," the report said. "However, contacts in a few districts noted negative sales impacts from rising prices. Firms in most districts expected inflationary pressures to continue over the coming months."                                                                                                                                 , Businesses also said that hiring was held back by a lack of available workers, though firms in several districts reported signs of modest improvement in labor availability. It's a broader trend known as the "Great Resignation." Newly empowered workers are quitting their jobs in favor of better wages, working conditions and hours as businesses lure new workers with higher salaries.                                                                                                 , As a result, Americans' incomes are rising across the board as employers have ramped up hiring to offset the losses. However, some firms said the tight labor market and growing wages have worsened inflationary pressures.                                                                                                                                                                                                                                                                    , A man wearing a mask walks past the U.S. Federal Reserve building in Washington D.C., April 29, 2020.  (Xinhua/Liu Jie via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                         , "Many firms reported significant turnover as workers left for higher wages and more flexible job schedules," the report said. "Persistent labor demand continued to fuel strong wage growth, particularly for footloose workers willing to change jobs. Firms reported that inflationary pressures were also contributing to higher wages, and that higher wages were doing little to alleviate widespread job vacancies."                                                                      , The report comes as American consumers grapple with the hottest inflation in four decades, with the consumer price index soaring by 8.5% in March from the previous year.                                                                                                                                                                                                                                                                                                                       , Gasoline prices hover around $4 per gallon for the least expensive grade at several gas stations in the nation's capital April 11, 2022, in Washington, D.C.  (Chip Somodevilla/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Rapidly rising prices have forced the Federal Reserve to take a more hawkish approach to fighting inflation. Policymakers raised rates by a quarter-percentage point in March and have since signaled support for a faster, half-percentage point increase at their May meeting.                                                                                                                                                                                                                , Traders are now pricing in more than a 95% chance of a hefty half-point rate jump when policymakers meet next month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/tesla-stock-option-straddle-priced-post-earnings/story.aspx?guid={7E37E31D-FB32-4F8E-99F1-B7ECDFA76445}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-21 01:57:04 </td>
   <td style="text-align:left;"> Tesla stock-option 'straddle' priced for post-earnings move of more than $66 - MarketWatch </td>
   <td style="text-align:left;"> A stock-options strategy known as a "straddle" on Tesla Inc.'s stock 
        TSLA,
        -4.96%
       is priced Wednesday for a one-day, post-earnings move of $66.56, according to data provided by Option Research &amp; Technology Services (ORATS) Principal Matt Amberson. That's slightly less than average price move over the past 12 quarters of $67.27, ORATS data show. A straddle is a pure volatility play in which bullish (calls) and bearish (puts) with at-the-money strikes, with expirations at the end of the week, are purchased simultaneously. The pricing indicates that straddle buyers will profit from the purchase if the stock moves more than $66.56 in either direction on Thursday, which at current prices would imply a percentage move of about 6.8%. Tesla is scheduled to report first-quarter results after Wednesday's closing bell. The stock, which was down 4.2% in afternoon trading Thursday, has lost 6.8% year to date, while the S&amp;P 500 
        SPX,
        -0.06%
       has declined 6.1%., Experts were dismayed Tuesday at the response to a federal judge ruling that struck down the U.S. face mask mandate covering airlines and other public transportation, leading some airlines to immediately drop their requirements -- in some cases mid-flight -- and sow confusion among travelers.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/germany-will-end-oil-imports-from-russia-by-year-end-says-minister </td>
   <td style="text-align:left;"> 2022-04-21 01:53:10 </td>
   <td style="text-align:left;"> Germany will end oil imports from Russia by year end, says minister </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.                                                                                                                                                                                , Germany will stop importing oil from Russia by the end of the year, said German Foreign Minister Annalena Baerbock after a meeting with her Baltic counterparts on Wednesday.                                                , OIL PRICES RISE 1% AFTER FALLING IN PREVIOUS SESSION                                                                                                                                                                         , "I therefore say here clearly and unequivocally yes, Germany is also completely phasing out Russian energy imports," said Baerbock.                                                                                          , Annalena Baerbock, after being confirmed as the Green Party's candidate for chancellor on June 12, 2021. (Sean Gallup/Getty Images)                                                                                          , "We will halve oil by the summer and will be at zero by the end of the year, and then gas will follow, in a joint European roadmap, because our joint exit, the complete exit of the European Union, is our common strength.", GET FOX BUSINESS ON THE GO BY CLICKING HERE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/few-starbucks-customers-stop-visiting/story.aspx?guid={AB1107B7-0E5A-4E14-85A3-438D9F7E9D81}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-21 01:50:47 </td>
   <td style="text-align:left;"> Few Starbucks customers will stop visiting if union efforts fail, analyst survey shows - MarketWatch </td>
   <td style="text-align:left;"> BTIG analysts surveyed 1,000 Starbucks Corp 
        SBUX,
        -1.29%
       customers and found that only 4% planned to stop visiting the coffee purveyor if negotiations with unions fail to result in an agreement. More than two-thirds (68%) said the effort would have no effect on their visitation habits, 15% said they would visit less often and 13% said they would visit more often. BTIG notes that Starbucks is required by law to negotiate with unions, but a contract isn't guaranteed. Nearly 200 of Starbucks' 9,000 U.S. locations have petitioned for union elections with eight locations receiving certification from the National Labor Relations Board. Workers in Buffalo voted to unionize in December 2021 and have a year to execute a contract or could possibly have to dissolve the union, according to BTIG. "Given the industry-leading average hourly earnings of $17 per hour (this summer) for Starbucks employees, in addition to healthcare benefits, tuition reimbursement, paid-time-off, we are unsure what concrete resolution the unionization effort seeks to achieve," analysts said. "Our understanding is that employees are frustrated by issues that are plaguing the entire industry right now including staffing shortages, scheduling, poor training, and high turnover, issues that could be tempered with menu simplification, but not resolved with a contract." Howard Schultz, Starbucks' interim/returning chief executive said recently that new employee benefits may not include unionized workers, reports The Wall Street Journal. Schultz has also suspended share buybacks in order to invest in workers and stores. BTIG rates Starbucks stock buy with a $110 price target, down from $130. "We believe that prior momentum is returning as coronavirus disruption fades and customer mobility returns, setting up a strong sales and earnings recovery outlook over the coming quarters," analysts led by Peter Saleh wrote. Starbucks stock is down nearly 31% for the year to date., ​"As momentous as Russia's invasion of Ukraine is, the most strategically important event in recent weeks was the global economic war between Russia and the U.S. and its allies. Russia, however, has been preparing to confront the West and challenge the Western socio-economic model for a long time,"  Antonia Colibasanu writes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-tally-second-straight/story.aspx?guid={CC134048-3EB2-4341-9C7C-B4D0B2F76700}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-21 01:37:54 </td>
   <td style="text-align:left;"> Gold futures tally a second straight session loss - MarketWatch </td>
   <td style="text-align:left;"> Gold futures declined Wednesday for a second consecutive session to mark another settlement at their lowest since April 11. Prices for the precious metal went into "freefall" on Tuesday and now appear to have stabilized around $1,950, said Craig Erlam, senior market analyst at OANDA. "This could potentially mark the new range support after a period of trading broadly between $1,900 and $1,950." High inflation is prompting "more aggressive [Fed] tightening and traders may be fearing more to come, not to mention the economic consequences of such policy moves," he said. June gold 
        GCM22,
        +0.10%
       fell $3.40, or 0.2%, to settle at $1,955.60 an ounce after losing 1.4% on Tuesday., Experts were dismayed Tuesday at the response to a federal judge ruling that struck down the U.S. face mask mandate covering airlines and other public transportation, leading some airlines to immediately drop their requirements -- in some cases mid-flight -- and sow confusion among travelers.                                                                                                                                                                                                                                                                                                                                                                                                                              , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/raymond-james-analyst-doesnt-expect/story.aspx?guid={6BF29F7E-044E-47CC-8BF1-3D706E7F3DEC}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-21 01:09:33 </td>
   <td style="text-align:left;"> Raymond James analyst doesn't expect Arcturus' COVID-19 vaccine to be authorized in the U.S.  - MarketWatch </td>
   <td style="text-align:left;"> Shares of Acturus Therapeutics Holdings Inc. 
        ARCT,
        -3.13%
       were down 2.3% in trading on Wednesday after the company said two doses of its experimental COVID-19 vaccine had an efficacy rate of 55% against infection. The Phase 3 clinical trial evaluated the vaccine in 19,000 people in Vietnam; it also found that the investigational shot had an efficacy rate of 95% against severe disease. The "results are net positive given they appear to meet FDA's minimum requirement for EUA...in a population that was likely primarily exposed to the omicron variant," Raymond James analyst Steven Seedhouse told investors on Wednesday. However, he said he doesn't expect the vaccine to be authorized by the Food and Drug Administration because the trial wasn't conducted in the U.S. Arcturus shares are down 33.3% this year, while S&amp;P 500 
        SPX,
        -0.06%
       has declined 6.4%. , Tesla's first quarter earnings report ticked all the boxes. The EV company earned $3.22 a share. Analysts were looking for closer to $2.30 a share. The stock is rising.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/20/stocks-making-the-biggest-moves-midday-netflix-mt-bank-baker-hughes-ibm-more.html </td>
   <td style="text-align:left;"> 2022-04-21 01:04:52 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Netflix, M&amp;T Bank, Baker Hughes, IBM and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                             , Check out the companies making headlines in midday trading Wednesday:                                                                                                                                                                                                                                                                                                                                                       , Netflix — Shares of the streaming giant sank 35% after Netflix reported a loss of 200,000 subscribers in the most recent quarter. Netflix cited increasing competition, password sharing and the situation in Ukraine among the reasons for the dip. The news led to a wave of downgrades from major Wall Street firms.                                                                                                     , Disney, Paramount — Shares of streaming video companies fell after Netflix reported a loss in subscribers for the first time in more than a decade. Disney dropped 5.6%, Roku fell 6.2%, and HBO Max owner Warner Bros. Discovery was off about 6%.Paramount (formerly ViacomCBS) declined 8.6%.                                                                                                                            , M&amp;T Bank — Shares for the regional bank surged 8.8% after M&amp;T Bank exceeded earnings expectations. M&amp;T Bank reported earnings of $2.73 per share, which was above $2.19 per share expected by analysts surveyed by Refinitiv.                                                                                                                                                                                               , Procter &amp; Gamble — Shares of the Procter &amp; Gamble rose 2.7% after the consumer packaged goods company reported better-than-expected results for its fiscal third-quarter and hiked its full-year revenue guidance.                                                                                                                                                                                                          , IBM — IBM surged 7.1% after beating on revenue and earnings in the recent quarter. The company reported an adjusted quarterly profit of $1.40 per share, 2 cents above a Refinitiv estimate. Revenue rose 7.7% over the year-ago quarter, with sales to Kyndryl lifting revenue growth by 5 percentage points.                                                                                                              , Omnicom Group — Shares for the advertising company spiked 4.5% after Omnicom topped earnings expectations on Tuesday despite taking a hit to its investment in Russian businesses. Omnicom reported earnings of $1.39 per share and revenues of $3.41 billion. In comparison, analysts surveyed by FactSet were forecasting earnings of 1.30 per share and $3.286 billion.                                                  , Baker Hughes — The oilfield services stock slid 3.8% after Baker Hughes missed estimates for the first quarter. The company reported 15 cents in adjusted earnings per share on $4.84 billion of revenue. Analysts surveyed by Refinitiv were expecting 20 cents per share and $5.02 billion in revenue. CEO Lorenzo Simonelli said in a release that the results "reflect operating in a very volatile market environment.", ASML — Shares for the semiconductor equipment maker jumped 2.7% after ASML reported an earnings beat for its most recent quarter. Strong demand from chip makers to boost production supported the company.                                                                                                                                                                                                                 , — CNBC's Tanaya Macheel, Hannah Miao, Jesse Pound and Samantha Subin contributed reporting.                                                                                                                                                                                                                                                                                                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/20/politics/janet-yellen-g20-finance-ministerial-protest/index.html </td>
   <td style="text-align:left;"> 2022-04-21 01:04:47 </td>
   <td style="text-align:left;"> US Treasury secretary and other finance ministers walk out of G20 meeting with Russia - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Finance ministers from multiple nations walked out of a closed-door G20 session in Washington on Wednesday when the Russian delegate began his prepared remarks, a show of protest against Moscow for its invasion of Ukraine.                                                                                                                                                          , US Treasury Secretary Janet Yellen participated in the walkout, as did European and other Western officials who were participating in the meeting.                                                                                                                                                                                                                                            , Canada's finance minister Chrystia Freeland wrote on Twitter, "The world's democracies will not stand idly by in the face of continued Russian aggression and war crimes." She tweeted a photo of officials who left meeting, including Yellen, US Federal Reserve Chairman Jerome Powell and European Central Bank President Christine Lagarde.                                              ,                                                                                                                                                                                                                                                                                                                                                                                               , Ahead of the meeting, US officials had said Yellen would not participate in certain sessions of the gathering that included Russia.                                                                                                                                                                                                                                                           , Ukrainian officials also spoke at the session as invited guests, and also walked out during Russia's presentation. Yellen and other officials attended the session during those remarks, but departed when Russian Finance Minister Anton Siluanov began speaking virtually.                                                                                                                  , A separate official said finance ministers had discussed plans to boycott Russia's participation ahead of time.                                                                                                                                                                                                                                                                               , Yellen said earlier this month she had informed this year's G20 host, Indonesia, that she wouldn't participate in sessions that included Russia. The G20 finance ministers are gathered in Washington this week to coincide with the annual meetings of the World Bank and International Monetary Fund.                                                                                       , Ahead of Wednesday's walkout, Treasury officials made clear it would not be business as usual when it came to Yellen's interactions with Russian officials during this week's big gathering of global economic leaders.                                                                                                                                                                       , While Yellen will attend some sessions of the G20 Finance Ministers and Central Bank Governor meeting with Russian officials present, including the opening session, she will not be participating in all of them if the Russians are there, according to a senior US Treasury Official.                                                                                                      , "President Biden's made clear and I certainly agree with him that it cannot be business as usual for Russia in any of the financial institutions," Yellen told the House Financial Services Committee. "He's asked that Russia be removed from the G20 and I've made clear to my colleagues in Indonesia that we will not be participating in a number of meetings if the Russians are there.", While President Biden has said Russia should no longer be in the G20, ejecting Moscow would require the support of all members. That is considered unlikely, as China has said it would not back kicking Russia out.                                                                                                                                                                          , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/dr-mehmet-oz-bidens-policies-inflation </td>
   <td style="text-align:left;"> 2022-04-21 00:35:47 </td>
   <td style="text-align:left;"> Dr. Oz rips Biden’s policies as inflation rages forward </td>
   <td style="text-align:left;"> Pennsylvania Republican Senate candidate Dr. Mehmet Oz argues people ‘are angry’ with Biden’s energy and economic policies.                                                                                                                                                          , Pennsylvania Republican Senate candidate Dr. Mehmet Oz torched Biden’s policies and argued that people "are angry," as "inflation rates rage forward."                                                                                                                               , "People here are really angry," Oz said on "Varney &amp; Co.," Wednesday. "They're saying, my goodness, we're not able to make money to make ends meet."                                                                                                                                 , Oz’s comments come on the heels of former President Trump endorsing the celebrity doctor in Pennsylvania’s Senate primary race. Oz expressed he’s "proud" to be in this position and believes he will "do well," running in the Keystone State.                                      , US ECONOMY FACING 'MODEST' RECESSION NEXT YEAR, FANNIE MAE SAYS                                                                                                                                                                                                                      , "There [are] a lot of voters who are animated in part by what happened when they contrast Joe Biden's performance to President Trump's performance… if you, interestingly, look at and compare them in an energy state like Pennsylvania, people here are really angry" he remarked. , Pennsylvania Republican Senate candidate Dr. Mehmet Oz discusses taking a ‘tough stance’ on campaign issues.                                                                                                                                                                         , The celebrity doctor continued to say that he doesn’t agree with Biden’s energy policies and believes that the inflation surge is caused by America not being "energy independent," making it difficult to "help our allies overseas."                                               , "We can't harvest natural gas under our feet that we know would make this country energy independent, even dominant," Oz noted.                                                                                                                                                      , Pennsylvania Republican Senate candidate Dr. Mehmet Oz told FOX Business that people ‘are angry’ with Biden’s energy and economic policies.  (Fox News)                                                                                                                              , Earlier this month, a tweet from Trump’s spokesperson stated that "President Donald J. Trump announced his endorsement of Dr. Oz."                                                                                                                                                   , Oz said he reached out to the former president for his support for the U.S. Senate seat in Pennsylvania.                                                                                                                                                                             , "Every candidate for the Senate in Pennsylvania went to President Trump," Oz explained. "All of us were evaluated by him carefully, and he chose me… I'll quote him, he said I was ‘smart, tough and will never let us down.’"                                                       , Celebrity Dr. Oz compares Biden's policies to former president Trump's on FOX Business. (AP Photo)                                                                                                                                                                                   , He said he will take a "tough stance" on campaign issues such as health, energy, and economic policies.                                                                                                                                                                              , Meanwhile, Philadelphia announced indoor mask mandates are returning to the city. Oz said "folks are livid," and that the "hypocrisy is so thick you can cut through it."                                                                                                            , In addition, Oz continued to rip Biden’s energy policies and said the "Green New Deal is a lie." He believes the proposal "cannot happen in the way it’s described in the timeline articulated."                                                                                     , "America's gotten cleaner and protected our environment because we have natural gas. Let’s not hide from that scientific reality," he emphasized.                                                                                                                                    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                          , Oz vowed to "fight back" and use his voice to articulate against left-wing policies in his campaign.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/sonoco-products-raises-dividend-boosting/story.aspx?guid={C84DA656-81C7-4CBB-BE69-C164F1E16D01}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-21 00:34:51 </td>
   <td style="text-align:left;"> Sonoco Products raises dividend, boosting yield to more than double that of the S&amp;P 500 - MarketWatch </td>
   <td style="text-align:left;"> Shares of Sonoco Products Co. 
        SON,
        +2.04%
       rose 1.2% in midday trading Wednesday, after the protective packaging company said it raised its quarterly dividend by 8.8%, to 49 cents a share from 45 cents. The new dividend is payable Jun 10 to shareholders of record on May 10. Based on current stock prices, the new annual dividend rates implies a dividend yield of 3.00%, compared with the implied yield for the S&amp;P 500 
        SPX,
        -0.06%
       of 1.42%. The company said the next dividend payment will be the 388th-consecutive quarter, going back to 1925, that it has paid a dividend, and will mark the 40th-straight year that the dividend was raised. The stock has rallied 12.9% year to date, while the S&amp;P 500 has lost 6.2%., Experts were dismayed Tuesday at the response to a federal judge ruling that struck down the U.S. face mask mandate covering airlines and other public transportation, leading some airlines to immediately drop their requirements -- in some cases mid-flight -- and sow confusion among travelers.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-04-21 00:34:50 </td>
   <td style="text-align:left;"> South African Stocks End Marginally Down </td>
   <td style="text-align:left;"> The JSE FTSE All-Share Index reversed early gains and closed marginally lower at 73,783 on Wednesday, with investors digesting US corporate results and assessing the implications of Russia’s new offensive in Ukraine. Locally, concerns mounted over load-shedding and the fallout from floods in KwaZulu-Natal and the Eastern Cape. On the data front, South Africa's annual inflation accelerated to 5.9% in March, slightly below market estimates of 6%, underpinned by prices of fuels and food products.On the corporate, miners and tech stocks were among the worst performers. At the same time, insurer Old Mutual lost almost 2% after it announced a Black economic empowerment transaction that would likely hit profits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-04-21 00:32:51 </td>
   <td style="text-align:left;"> Brent Falls Nearly 2% </td>
   <td style="text-align:left;"> Brent crude futures tumbled to around $105 per barrel, pressured by a weak global economic outlook and concerns about subdued demand in top consumer China. The IMF and the Global Bank slashed their forecast for world economic growth following Russia’s invasion of Ukraine. At the same time, renewed coronavirus-induced lockdowns in China clouded the demand outlook in the world’s top crude importer. Putting a floor under prices were supplies disruptions from Libya because of a wave of protests and the potential for an EU ban on Russian oil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/stock-market </td>
   <td style="text-align:left;"> 2022-04-21 00:29:35 </td>
   <td style="text-align:left;"> Russian Stocks Pare Losses </td>
   <td style="text-align:left;"> The MOEX Russia Index erased earlier losses to close 0.6% higher at 2,330 on Wednesday, with rebounds from the financial sector and mining stocks as investors continue to digest risks with the prospect of additional sanctions from the West. VTB led the gains to end 3.2% higher, while Sberbank closed 1% up. Severstal outperformed the mining sector to gain 4.1%, extending its rebound to three consecutive sessions in the green. Meanwhile, the European Union said it is considering an oil embargo on Russia, with EU Commission members in talks with oil companies to negotiate alternative suppliers. The move pressured Lukoil shares to close 4% down, while Gazprom dropped 0.9%. The sixth package of sanctions from the EU could also include harsh penalties on lending giant Sberbank and a ban on nuclear fuel. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/20/europe/russia-ukraine-strategy-donbas-analysis-cmd-intl/index.html </td>
   <td style="text-align:left;"> 2022-04-21 00:27:18 </td>
   <td style="text-align:left;"> Analysis: Pushed back from Kyiv, what's Russia's military strategy now? - CNN </td>
   <td style="text-align:left;"> (CNN)Phase two of Russia's invasion of Ukraine -- an offensive in the eastern Donbas region -- is underway. The question is whether it will be any more successful and competent than phase one, and whether Ukraine will have enough troops and weapons to impede or even block it.                                                                                                                                 , Russian Foreign Minister Sergey Lavrov said Tuesday that the operation in the Donbas is "a very important moment of this entire special operation."                                                                                                                                                                                                                                                                   , The Russian goal is clear and publicly stated: to secure all of Ukraine's eastern regions of Donetsk and Luhansk -- parts of which Russian-backed separatists have controlled since 2014. A second aim is to crush the remaining resistance in the port city of Mariupol to consolidate a land bridge linking the Russian region of Rostov with Crimea, which Russia seized from Ukraine eight years ago.             , To those ends, Russian forces that were deployed to the north and east of Kyiv have been redeployed and in some cases reconstituted after suffering heavy losses.                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                       , Now they -- and fresher units -- are piling into Ukraine from the northeast. US officials estimate that Russia has mobilized some 78 battalion tactical groups in eastern Ukraine -- probably about 75,000 troops. Still more are being assembled in Russian border regions.                                                                                                                                          , So far, their tactics have been straight out of the Russian playbook: massive use of artillery, rocket systems and missiles followed by armor advancing. Cities in Luhansk such as Severodonetsk, Popasna and Rubizhne have been reduced to rubble, with power, gas and water supplies destroyed.                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                       , But Russian progress on the ground has been modest. That may be a result of not taking time to regroup after the battering they took in February and March.                                                                                                                                                                                                                                                           , The Institute for the Study of War (ISW) says that "Russian forces did not take the operational pause that was likely necessary to reconstitute and properly integrate damaged units withdrawn from northeastern Ukraine into operations in eastern Ukraine."                                                                                                                                                         , US officials have assessed that Russia has lost up to 25% of the combat firepower it had before the invasion.                                                                                                                                                                                                                                                                                                         , Boxing the Donbas in                                                                                                                                                                                                                                                                                                                                                                                                  , CNN analysis of satellite imagery, dozens of social media videos and the statements of both sides suggest the Russians are now trying to advance on three axes.                                                                                                                                                                                                                                                       , Imagine the Donbas as a square: Russian forces are already on three sides -- leaving only the west open to the Ukrainians for reinforcements and, if necessary, retreat.                                                                                                                                                                                                                                              , From the south and the east, forward Russian units have advanced a few kilometers at best this month. In the south they had already made progress eating into Zaporizhzhia region, which neighbors Donetsk. This week, they began shelling villages well inside Zaporizhzhia.                                                                                                                                         , From the north, after taking the city of Izium at the beginning of this month, they have made little further progress.                                                                                                                                                                                                                                                                                                ,                                                                                                                                                                                                                                                                                                                                                                                                                       , What's unclear at this stage is whether the Russians can and will change gear, and a better-coordinated offensive is around the corner. The report card from the Kyiv campaign suggests otherwise, but US officials believe that for now Russia is still conducting "shaping operations ... to make sure they have logistics and sustainment in place."                                                               , Even so, the ISW assesses that "The Russian military is unlikely to have addressed the root causes -- poor coordination, the inability to conduct cross-country operations, and low morale -- that impeded prior offensives."                                                                                                                                                                                         ,                                                                                                                                                                                                                                                                                                                                                                                                                       , Ukrainian tactics                                                                                                                                                                                                                                                                                                                                                                                                     , The Ukrainians have shown themselves to be canny tacticians in this conflict, ceding territory to preserve resources but using their knowledge of the land and their mobility to inflict losses on Russian units.                                                                                                                                                                                                     , This week Ukrainian units withdrew from the town of Kreminna in Luhansk region when confronted with overwhelming firepower.                                                                                                                                                                                                                                                                                           , Now they have to decide if they will mount static defenses, which could lead to units being destroyed or surrounded in the face of Russia's artillery, rockets and armored assault. The alternative is mobile defense -- fighting and withdrawing from less vital terrain, hitting the Russians as they fall back and then holding their lines in terrain of their choosing.                                          , Simultaneously the Ukrainians will look to disrupt Russian supply lines -- sowing confusion while challenging Russian logistics and morale. And morale in some Russian units -- redeployed for their second offensive in as many months -- may be brittle.                                                                                                                                                            , One of the Russian targets is the city of Sloviansk, but the surrounding territory includes forests, rivers and marshes -- difficult to transit and requiring specialist bridging equipment. Where the Russians are confined to roads, as became clear north of Kyiv, they are more vulnerable to both Ukrainian drones and light anti-tank missiles.                                                                 , Nor are the Ukrainians playing defense only; in recent days small units have made modest gains east and south of Kharkiv, potentially threatening Russian supply lines. If they can sustain this, the Russians would have to dedicate units to protecting these lines.                                                                                                                                                ,                                                                                                                                                                                                                                                                                                                                                                                                                       , There are already signs that Ukrainian special forces are operating behind Russian lines: last week a road bridge on a main route in from Russia was blown up. There was also unexplained damage to a railway bridge inside Russia, on the edge of Belgorod. The Russian military relies on railways for much of its logistics. In this aspect of the battle, Western intelligence support may play a critical role.  , Another important aspect of the fight to come is cultural. Ukrainian units enjoy some autonomy and are encouraged to exploit opportunities on the battlefield. Even in the absence of clear direction or orders, they have the motivation to fight. By contrast, the Russian command chain is rigid and the culture does not encourage enterprise.                                                                    , Even so the Ukrainians also face considerable risks. They are fighting -- essentially -- within a box that could close if the Russians were successful in one or more directions. They will have to maneuver smartly as they did around Kyiv, constantly alert for the risk of being surrounded.                                                                                                                      , When Mariupol falls, the Russians can redirect the forces that were dedicated to that assault, but they have been degraded and exhausted by nearly two months of urban combat.                                                                                                                                                                                                                                        , Above all, in a race against time, Ukraine needs a constant resupply of weapons and ammunition, much of which must now come from outside the country through a lengthy supply line vulnerable to being interdicted. They need more anti-tank weapons and mobile air defenses.                                                                                                                                         , Counterattacks to disrupt the Russian offensive would need to be protected from the air.                                                                                                                                                                                                                                                                                                                              , On Tuesday, a senior US official said Washington was working "around the clock" to get weapons to Ukraine at "unprecedented" speed. The United States has already authorized $2.3 billion in shipments of weapons and equipment to Ukraine since the invasion.                                                                                                                                                        , "What is unprecedented here is the amount of successive drawdowns that we are moving at this speed," the official said.                                                                                                                                                                                                                                                                                               ,  Aiming for Victory Day                                                                                                                                                                                                                                                                                                                                                                                               , There's been some talk of the Kremlin wanting tangible progress by May 9, when Russia celebrates Victory Day marking the defeat of Nazi Germany in World War II. At the current rate of progress, that looks unlikely. The much bigger question is whether this conflict stretches into the summer, in a grim war of attrition.                                                                                       ,  The Russian military would have to rotate units, drawing on limited reserves, to sustain a conflict that has already battered its ground forces. Its calculation (and the Kremlin's political strategy) will be affected by the effectiveness of Ukrainian resistance and the ability of Western governments to supply Ukraine with more and better equipment.                                                       , Writing in War on the Rocks, Jack Watling of the Royal United Services Institute in London said: "Ukraine's defiance has bought time and an opportunity not only to stave off further Russian gains in the Donbas, but also to shape the battle beyond it. If Ukraine's allies act today, they may deter or at least prepare for a summer offensive."                                                                 , There is an urgency about resupply. Last week, the Biden administration authorized another $800 million security package, which included artillery and anti-artillery radars. On Tuesday, the President indicated more is to come.                                                                                                                                                                                    , Ukraine will require offensive hardware if it's to punish any vulnerability in Russian lines, and that includes heavy armor (such as battle-ready tanks) as well as a host of other systems.                                                                                                                                                                                                                          , Watling says there's no time to lose. "Providing Ukraine with tactical mobile air-defense systems such as the National would allow Ukraine to maneuver near the Russian border and retake towns while raiding Russian supply lines."                                                                                                                                                                                  , The National -- or NASAMS -- is an advanced and mobile surface-to-air missile system.                                                                                                                                                                                                                                                                                                                                 , Western governments understand that this is a critical moment: raising the cost of Russia's "special military operation" to the point where it is unaffordable. The Ukrainians are crying out for even more and better weaponry, especially as they try to keep their air force flying.                                                                                                                               , Still outnumbered and outgunned, they will need agility, determination and reinforcements to stave off phase two of Vladimir Putin's war on Ukraine.                                                                                                                                                                                                                                                                  , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/asml:us </td>
   <td style="text-align:left;"> 2022-04-21 00:21:05 </td>
   <td style="text-align:left;"> ASML earnings below expectations at 1.87 USD </td>
   <td style="text-align:left;"> ASML (ASML) released earnings per share at 1.87 USD, compared to market expectations of 1.94 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-04-21 00:17:00 </td>
   <td style="text-align:left;"> Madrid Stocks Close at Over 2-Month High </td>
   <td style="text-align:left;"> The Ibex 35 rose 0.9% to end at 8,770 on Wednesday, the highest since February 11th, tracking its European peers, as positive earnings reports in the US and Europe helped to offset concerns over global growth and inflation. Among single stocks, banks were leading the gains. At the same time, Siemens Gamesa jumped over 5%, reversing early sharp losses, even after disappointing preliminary Q2 results prompted the Spanish turbine maker and its parent Siemens Energy to review their 2022 outlook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-04-21 00:05:00 </td>
   <td style="text-align:left;"> Oil Turns Negative in Volatile Session </td>
   <td style="text-align:left;"> WTI crude futures bottomed around $101 per barrel, a dramatic reversal from its daily highs of $104 as investors weighted a weakening global economic outlook and concerns about subdued demand in top consumer China against tighter supplies from Russia and Libya. The IMF and the Global Bank slashed their forecast for world economic growth following Russia’s invasion of Ukraine. At the same time, renewed coronavirus-induced lockdowns in China clouded the demand outlook in the world’s top crude importer. Putting a floor under prices were supplies disruptions from Libya because of a wave of protests and the potential for an EU ban on Russian oil. Meanwhile, EIA data showed that the US crude oil inventories tumbled 8.02 million barrels to 413.7 million barrels last week, the most since January 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-04-21 00:03:00 </td>
   <td style="text-align:left;"> French Stocks End at Over 2-Week High </td>
   <td style="text-align:left;"> The CAC 40 index closed 1.4% up at 6,625 on Wednesday, the highest since April 5th, amid optimism around corporate earnings despite mounting uncertainties around the global economy. The business services group Teleperformance was the top performer, gaining 5.8% after announcing EUR 1.96 billion in revenue for the first quarter, meeting ambitious targets. At the same time, Danone shares surged about 5.8% after the group announced a 7.1% increase in turnover during the first quarter and maintained its 2022 financial targets, despite the difficult environment in the food industry due to soaring inflation. On the political front, all eyes turn to a potentially decisive debate later in the evening between French President Emmanuel Macron and far-right challenger Marine Le Pen ahead of Sunday’s runoff presidential vote. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/existing-home-sales-drop-prices-hit-new-record </td>
   <td style="text-align:left;"> 2022-04-20 23:59:14 </td>
   <td style="text-align:left;"> Existing home sales drop as prices hit new record </td>
   <td style="text-align:left;"> Macro Trends Advisors founding partner Mitch Roschelle discusses the housing market amid rising inflation and home builders starting to favor selling to investors.                                                                                                                                                           , Existing home sales fell by 2.7% in March as demand slowed while prices climbed to a new record.                                                                                                                                                                                                                              , The latest data from the National Association of Realtors shows 5.77 million previously occupied homes sold last month, which is the lowest seasonally adjusted annual rate since June 2020. Existing home sales have fallen in three of the last four months.                                                                , A for sale sign is posted in front of a home for sale on March 18, 2022 in San Rafael, California.  (Photo by Justin Sullivan/Getty Images / Getty Images)                                                                                                                                                                    , Year over year, the median price of existing homes soared 15% to $375,300 in March, the highest on record. This marks 121 months of year-over-year price increases, the longest stretch on record.                                                                                                                            , IS THE U.S. ALREADY IN A HOUSING BUBBLE?                                                                                                                                                                                                                                                                                      , "The housing market is starting to feel the impact of sharply rising mortgage rates and higher inflation taking a hit on purchasing power," said Lawrence Yun, NAR's chief economist. "Still, homes are selling rapidly, and home price gains remain in the double-digits."                                                   , Waning demand also resulted in an increase in inventory, leaving 950,000 unsold homes on the market by the end of the month. That's up 11.8% from February and down 9.5% from a year ago.                                                                                                                                     , A "Sale Pending" sign outside a house in Discovery Bay, California, U.S., on Thursday, March 31, 2022.  (Photographer: David Paul Morris/Bloomberg via Getty Images / Getty Images)                                                                                                                                           , "Home prices have consistently moved upward as supply remains tight," Yun said. "However, sellers should not expect the easy-profit gains and should look for multiple offers to fade as demand continues to subside."                                                                                                        , HOMEBUILDER CONFIDENCE FALLS FOR FOURTH STRAIGHT MONTH                                                                                                                                                                                                                                                                        , First-time homebuyers accounted for 30% of home sales in March, up a percentage point from the month before. According to Yun, "It appears first-time homebuyers are still looking to lock in at current mortgage rates before they inevitably increase."                                                                     , A broken "For Sale" sign is seen outside a home in the Queens borough of New York (REUTERS/Shannon Stapleton / Reuters Photos)                                                                                                                                                                                                , The average rate for a 30-year fixed-rate mortgage was 4.17% last month. Now, the average rate is at 5% and expected to climb as the Federal Reserve has signaled it will make further interest rate increases in 2022 after raising them a quarter percent in March to combat soaring inflation, which is at a 40-year-high. , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                   , Amid the rising interest rates, there was also a higher share of cash sales in March, making up 28% of transactions – the highest since 2014. That is up from 25% in February and 23% from a year ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stericycle-pay-90-million-resolve/story.aspx?guid={D7580173-0B75-4F21-814D-D6169E3B95EA}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-20 23:57:51 </td>
   <td style="text-align:left;"> Stericycle to pay $90 million to resolve anti-corruption investigations with U.S., Brazil authorities - MarketWatch </td>
   <td style="text-align:left;"> Shares of Stericycle Inc. 
        SRCL,
        -0.02%
       rose 1.1% in midday trading Wednesday, after the waste management services company agreed to pay $90 million to resolve anti-corruption investigations with U.S. and Brazilian regulators. The investigations, by the U.S. Department of Justice (DOJ), the U.S. Securities and Exchange Commission and Brazil's Comptroller General's Office (CGU) and Attorney General's Office (AGU), began in 2017 and were focused on conduct by employees in its Latin America businesses, including those in Argentina, Mexico and Brazil; the company has since sold its operations in Argentina and Mexico. As part of the resolution, the company entered into a Deferred Prosecution Agreement with the DOJ and agreed to an administrative order with the SEC. The company will engage an independent compliance monitor for two years, after which it will self-report to the U.S. agencies on its compliance for another year. Separately, the SEC said it charged Stericycle for violations of the Foreign Corrupt Practices Act (FCPA), in which the company paid "millions of dollars in bribes" for business with government customers in Brazil, Mexico and Argentina. ""Resolving this legacy matter represents another important milestone in Stericycle's business transformation journey," said Stericycle Chief Executive Cindy Miller. The stock has lost 16.4% over the past 12 months, while the S&amp;P 500 
        SPX,
        -0.06%
       has gained 8.2%., A new band of Wall Street analysts rushed to cut price targets and ratings on Netflix in response to deeply disappointing results, though shares of the pioneering streaming service have been under pressure for months.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-04-20 23:49:39 </td>
   <td style="text-align:left;"> Italian Stocks Rebound on Wednesday </td>
   <td style="text-align:left;"> The FTSE MIB index closed 1% higher at 24,878 on Wednesday, recovering from yesterday’s losses amid strong performances in the financial sector, while investors continued to digest the IMF’s cut in growth estimates and monitor the war in Ukraine. Banco Bpm rose 4.5% and led the gains among banks amid renewed speculation that the bank seeks new M&amp;A opportunities. Bper Banca closed 3.5% higher, also outperforming other Italian banks in the session. At the same time, STMicroelectronics ended up 3.2%, tracking other chip producers due to strong results from the Dutch ASML. Meanwhile, Leonardo rose 1.7% amid reports that the defense group is once again considering a merger with shipbuilder Fincantieri, which in turn dropped 0.6%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-04-20 23:33:28 </td>
   <td style="text-align:left;"> European Shares Rebound Sharply </td>
   <td style="text-align:left;"> The DAX 30 index ended Wednesday’s session more than 1% higher at 14,340, while the regional STOXX 600 index added 0.9% as optimism over upbeat corporate earnings offset concerns over inflation and economic growth. Heineken gained over 5% after Q1 beer sales beat expectations, aided by lifting restrictions. Also, multinational Danone said Q1 net sales jumped 10.2% y-o-y, reflecting a 2.2% increase in volumes and higher prices, with strong results from North America. Finally, ASML, a key supplier to the semiconductor industry, announced first-quarter sales hit the €3.5 billion mark, and income stood at €0.695 billion, both beating market expectations, whilst leaving its full-year guidance unchanged and forecasting up to €5.3 billion in Q2 sales. On the data front, producer prices inflation in Germany hit a record 30.9% in March, and car sales in the EU slumped 20.5% from a year earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-20 22:57:00 </td>
   <td style="text-align:left;"> US Bond Selloff Pauses for Breath </td>
   <td style="text-align:left;"> The yield on the 10-year US Treasury note, which sets the tone for corporate and household borrowing costs worldwide, bottomed around 2.84% as investors took a breather after a recent selloff that sent yields above 2.94% for the first time since December 2018, with investors pricing chances of an increasingly hawkish Federal Reserve stance. Cementing such a view were increased inflationary pressures as annual inflation hit 8.5% in March, a new 40-year high. Earlier this week, Louis Fed President James Bullard echoed the Fed's intention to tighter monetary policy, saying that hikes of 75bps could be necessary to tame inflation. Along with runaway inflation, the job market has been showing signs of being extremely tight, which, in turn, brought forward the expectations of sharper interest-rate hikes to cool an overheating economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/inflation-threaten-biden-infrastructure-plans </td>
   <td style="text-align:left;"> 2022-04-20 22:55:03 </td>
   <td style="text-align:left;"> Inflation threatens to undercut Biden's infrastructure plans </td>
   <td style="text-align:left;"> Kingsview Wealth Management CIO Scott Martin weighs in as global leaders shift blame as inflation spreads on 'Kennedy.'                                                                                                                                                                                                                                                                                                                            , Soaring inflation and supply chain woes are poised to diminish the impact of President Biden's signature $1.2 trillion infrastructure package that Congress passed with bipartisan support last year.                                                                                                                                                                                                                                              , With the 2022 midterm elections looming, Biden is selling the infrastructure law as a success that overcame partisan divides and will improve the country with substantial investments in things like roads and bridges as well as clean drinking water, high-speed internet, public transit and airports.                                                                                                                                         , WHAT'S IN THE $1.2T INFRASTRUCTURE BILL?                                                                                                                                                                                                                                                                                                                                                                                                           , "There’s so much more in this law. I’m not going to bore you with the rest of it, but it's significant," Biden said on Tuesday during his second trip to New Hampshire as president.                                                                                                                                                                                                                                                               , But the hottest inflation in four decades is threatening to limit how much can actually be fixed or built under the law, with elevated costs for materials causing contractors to charge more for construction projects, according to a new analyst note from economists at S&amp;P Global.                                                                                                                                                            , President Biden visits the NH 175 bridge over the Pemigewasset River to promote infrastructure spending on Nov. 16, 2021, in Woodstock, New Hampshire. (AP Photo/Evan Vucci / AP Newsroom)                                                                                                                                                                                                                                                         , The cost of construction projects for the government rose 14.1% in March compared with a year earlier, according to whole price information released by the Labor Department last week. The producer price index, which measures inflation at the supplier level before it reaches consumers, surged 11.2% in March from the year-ago period. On a monthly basis, prices grew by 1.4% – an uptick from February, when the gauge increased by 0.9%. , What's more, average hourly wages in the construction industry rose about 5.6% in March compared with last year, according to Labor Department data.                                                                                                                                                                                                                                                                                               , "As construction input inflation increases or remains elevated, the purchasing power of federal investment – as well as other funding sources – is eroded," the note, authored by S&amp;P analysts Kurt Forsgren, Geoffrey Buswick and Joseph Pezzimenti, said.                                                                                                                                                                                        , The bill includes more than $500 billion in new spending that will be invested in "core" infrastructure projects such as roads, broadband internet and electric utilities over the next eight years. The White House has billed the measure as a "once-in-a-generation investment" and has projected that it will create 2 million new jobs.                                                                                                       , Steel beams sit outside Arena de Sao Paulo in Sao Paulo, Brazil. (AP Photo/Ferdinand Ostrop, File / AP Newsroom)                                                                                                                                                                                                                                                                                                                                   , That $1.2 trillion investment, however, could yield far less if sky-high inflation continues.                                                                                                                                                                                                                                                                                                                                                      , "The longer more elevated inflationary conditions persist, the more likely it is that public project sponsors will face the dilemma of reducing or delaying the promised overall program project scope or tapping other sources of program funding, including increased debt," the note said.                                                                                                                                                      , The White House has also directed federal agencies to ensure the new construction projects funded by the infrastructure law are built with U.S.-made materials, including iron and steel.                                                                                                                                                                                                                                                          , "This means all manufacturing processes, from the initial melting stage through the application of coatings, occurred in the United States," the Office of Management and Budget said in 17-pages of guidance on Monday.                                                                                                                                                                                                                           , Biden is betting that increasing domestic production will ultimately reduce price pressures as the supply chains remained tangled, but U.S.-made steel is far more expensive than that produced in other countries. The price of iron and steel scrap is up 29.2% in March from the previous year, according to the Labor Department, while steel mill products are up 42.9%.                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                        , It's possible that state and local governments could step in and contribute to the infrastructure projects by tapping their general funds, which have been boosted over the past two years by generous COVID-19 stimulus funds.                                                                                                                                                                                                                    , "The longer more elevated inflationary conditions persist, the more likely it is that public project sponsors will face the dilemma of reducing or delaying the promised overall program project scope or tapping other sources of program funding, including increased debt," the analyst note said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/billionaire-entrepreneur-stuck-in-supply-chain-backlog-jam </td>
   <td style="text-align:left;"> 2022-04-20 22:51:58 </td>
   <td style="text-align:left;"> Billionaire entrepreneur stuck in supply chain ‘backlog jam’ </td>
   <td style="text-align:left;"> Paul Mitchell, Patrón Spirits and ROK Group co-founder John Paul DeJoria says his companies are still stuck in the ‘backlog jam.’                                                                                                                                                                                                  , Self-made entrepreneur and co-founder of Paul Mitchell, Patrón Spirits and ROK Group John Paul DeJoria cautioned that China’s latest COVID-19 lockdowns could worsen supply chain backlogs as his billion-dollar companies still face disruptions and delays.                                                                      , "We see in all businesses what is coming from China, any ingredients... hard goods that come from China, really backordered big time," DeJoria said on "Mornings with Maria" Wednesday.                                                                                                                                            , "At first, we thought we would just start, 'Let's order 50 percent more,' like most companies did," he told FOX Business’ Dagen McDowell. "But all of a sudden, we were still in the backlog jam."                                                                                                                                 , DeJoria joins the group of retail experts and port executives warning that lockdowns and closures in China amid its largest COVID outbreak since the pandemic began could cause another wave of serious supply chain disruptions.                                                                                                  , U.S. ECONOMY IS ‘PROBABLY’ ALREADY IN A RECESSION, SAYS MARKET EXPERT                                                                                                                                                                                                                                                              , "In all the businesses, whether they're bringing things in from foreign countries or bringing things across the United States, all areas of the supply chain, whether it's bottling, whether it's ingredients and things of that nature, and little components, are backordered," DeJoria explained, "and we've been through this.", John Paul DeJoria attends an event presented by Paul Mitchell. (Getty Images)                                                                                                                                                                                                                                                      , When the entrepreneur started his career in the early 1980s, he had to overcome inflation, unemployment and interest rates that were "a little worse than they are now." DeJoria then described how business tactics used decades ago can help relieve supply chain pressure today.                                                , "We went to a second source and then to a third source. We started broadening our horizon," the billionaire said.                                                                                                                                                                                                                  , According to DeJoria, Paul Mitchell had $40 million worth of product backordered in the last six months, "so we went to other suppliers."                                                                                                                                                                                          , "We diversify out on where we got our ingredients from. But more important, we don't take away from what we believe in," DeJoria said of the hair brand’s cruelty-free promise.                                                                                                                                                    , Still stuck in the backlog situation, DeJoria said he’s been exploring switching to strictly "Made in America" operations.                                                                                                                                                                                                         , "We're looking now at sourcing in the United States of America," the entrepreneur confirmed. "Now, a lot of our vendors are not equipped to do that, so we're helping them do that in any way we can."                                                                                                                             , Paul Mitchell, Patrón Spirits and ROK Group co-founder John Paul DeJoria on how his companies overcame inflation in the 1980s.                                                                                                                                                                                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                        , Despite increased costs, DeJoria is optimistic about the switch to an American-only supply chain.                                                                                                                                                                                                                                  , "We may pay a little bit more, but we have the product," he said, "and we create more jobs for Americans."                                                                                                                                                                                                                         , READ MORE FROM FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-04-20 22:51:00 </td>
   <td style="text-align:left;"> WTI Crude Rises after Tuesday Selloff </td>
   <td style="text-align:left;"> WTI crude futures rebounded 1% to above $103 per barrel on Wednesday, after falling over 5% in the previous session, lifted by declining US oil inventories and supply disruptions from Russia and Libya. The EIA report showed US crude oil inventories tumbled 8.02 million barrels to 413.7 million barrels last week, the most since January 2021 and against market expectations for a 2.471 million increase. Also, OPEC+ produced 1.45 million barrels per day below its production target in March as Russian output began to decline after sanctions imposed by the West. OPEC member Libya has been forced to shut down a number of oil facilities including the 300,000 bpd Sharara oilfield because of a wave of protests. However, a softer global economic outlook following Russia’s invasion of Ukraine and renewed virus lockdowns in China are weighing on prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/crude-oil-stocks-change </td>
   <td style="text-align:left;"> 2022-04-20 22:37:00 </td>
   <td style="text-align:left;"> US Crude Inventories Fall the Most in 16 Months </td>
   <td style="text-align:left;"> US crude oil inventories tumbled 8.02 million barrels to 413.7 million barrels in the week ended April 15th, the most since January of 2021 and compared with market expectations for a 2.471 million increase. Crude stocks at the Cushing, Oklahoma, went down by 0.185 million barrels. Also, gasoline stocks fell by 0.761 million barrels to 232.4 million barrels, less than forecasts for a 0.976 million drop; and distillate stockpiles which include diesel and heating oil declined by 2.664 million barrels to 108.7 million barrels, compared to expectations for a 0.829 million barrel fall. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-04-20 22:21:39 </td>
   <td style="text-align:left;"> Canadian Dollar Regains Traction </td>
   <td style="text-align:left;"> The Canadian dollar strengthened to its highest level in two weeks against the dollar, testing the $1.25 region after domestic inflation data cemented the narrative that the Bank of Canada will have to tighten more aggressively to tame broad price pressures. Canada's annual inflation rate accelerated faster than expected in March, hitting a 31-year high of 6.7%. Last week, Canadian policymakers said the central bank would stop reinvesting maturing assets in April and raised interest rates by 50 basis points to 1%, the most in two decades. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-04-20 22:15:28 </td>
   <td style="text-align:left;"> Canada Stocks Edge Lower </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, was little changed on Wednesday after closing at a two-week high just above the 22,000 mark, as gains in financials failed to offset declines in most other sectors, following hotter-than-expected inflation data. Consumer prices in Canada jumped 6.7% over a year earlier in March, the quickest advance since January of 1991, which further strengthened the case for monetary policy tightening by the Bank of Canada. The central bank already raised its interest rates in a rare 50 bps hike at its April meeting, and policymakers had warned of further rate hikes if inflationary pressures persisted well above target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/existing-home-sales </td>
   <td style="text-align:left;"> 2022-04-20 22:07:37 </td>
   <td style="text-align:left;"> US Existing Home Sales Fall for 2nd Month </td>
   <td style="text-align:left;"> Existing home sales in the US fell 2.7% mom to a seasonally adjusted annualized rate of 5.77 million in March of 2022, the lowest since June of 2020 and compared to forecasts of 5.8 million. It is the second consecutive month of falls in home sales as the housing market starts to feel the impact of rising mortgage rates and inflation on the purchasing power although median existing house price hit an all-time high of $375,300. Sales fell in the Northeast, South and Midwest but were unchanged in the South. The inventory of unsold existing homes increased to 950,000. That would support 2.0 months at the monthly sales pace. February figures were also revised lower to 5.93 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-04-20 22:04:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index at Over 2-Week High </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index rose 1.3% to 2,142 on Wednesday, its highest since April 5th, supported by gains across all its vessel segments. "Ports in one of Brazil's biggest farming states are handling an unusual amount of fertilizer after importers rushed to secure supplies amid fears that sanctions on Belarus and Russia would curtail trade", the Parana port authority said.The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, increased 1.6% to 1,363 points; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, went up 0.3% to 3,087 points. Among smaller vessels, the supramax index added 55 points to its highest in two weeks at 2,596 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/20/politics/biden-mask-mandate-approval-rating/index.html </td>
   <td style="text-align:left;"> 2022-04-20 22:02:27 </td>
   <td style="text-align:left;"> With low approval rating, Biden faces mask mandate dilemma - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Joe Biden would probably like to forget the last few days.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , They've been filled with confusing messages on critical topics, projecting an image of a directionless White House led by a President whose tendency to veer off message is only adding to his problems.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Consider:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , * A federal judge in Florida struck down the administration's federal travel mask mandate on Monday. In response to that ruling, the Biden administration first didn't make clear what its next steps would be. Then late in the day on Tuesday, the administration said it would appeal the ruling -- if the US Centers for Disease Control and Prevention determines the mandate is still needed. In the midst of all of that, Biden added to the confusion, telling reporters during a trip to New Hampshire Tuesday that it was "up to them" when it came to people wearing masks on public transportation.                                                                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , * The administration has a revolt on its hands over its previously announced decision to rescind Title 42, a public health measure put in place in March 2020 -- in the early days of the Covid-19 pandemic -- that allowed border patrol officials to turn away migrants seeking asylum. Earlier this week, Michigan Sen. Gary Peters, who runs the Democrats' Senate campaign committee, said of Title 42 that "unless we have a well thought out plan, I think it is something that should be revisited and perhaps delayed." That follows questions raised by a number of Democrats on the ballot this year, concerned that rescinding Title 42 will lead to a flood of undocumented immigrants at the border. In the face of all of that, Axios reported Tuesday that the administration is considering "delaying the repeal of Title 42 border restrictions.", * Massachusetts Sen. Elizabeth Warren, one of the leading liberal voices in the country, wrote an op-ed in the New York Times suggesting that Biden and the Democrats need to start playing offense, legislatively speaking. "Despite pandemic relief, infrastructure investments and the historic Supreme Court confirmation of Ketanji Brown Jackson, we promised more — and voters remember those promises," wrote Warren. And this bit of frank talk: "To put it bluntly: if we fail to use the months remaining before the elections to deliver on more of our agenda, Democrats are headed toward big losses in the midterms."                                                                                                                                                                                                                               , All of this comes as Biden is at or near his low ebb in terms of job approval during his term. In CNN's latest poll of polls -- an average of the last four national polls -- Biden's approval rating is at just 39% among Americans, with his disapproval at 55%.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , In short: Biden didn't have a lot of goodwill left with the public before this week. But the conflicting messages coming out of the White House -- and the broader Democratic Party -- make it look like there is no plan to turn things around in advance of the midterm elections, which are now just over 200 days off.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Perhaps in an attempt to address this sense of a lack of direction, Biden put out a series of tweets Wednesday morning blaming inflation on Covid-19 and the Russian invasion of Ukraine and urging Congress to take action. "I've called on Congress to move immediately to lower the cost of families' utility bills, prescription drugs, and more — while lowering the deficit to reduce inflationary pressure," Biden tweeted.                                                                                                                                                                                                                                                                                                                                                                                                                                 , It's not clear that there is much desire among Democrats -- many of whom are eager to get home and campaign before the midterm elections -- to follow through on Biden's push.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , It's all a mess for Democrats. And a mess without any clear -- or easy -- solutions.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-04-20 21:55:00 </td>
   <td style="text-align:left;"> Brazilian Equities Fall for 4th Day </td>
   <td style="text-align:left;"> Brazil's main stock extended losses for the fourth straight session on Wednesday, with the benchmark Bovespa trading around the 114,750 level, the lowest since March 17th. Investors were digesting operational data from miner Vale and quarterly results from Usiminas, while also expecting a decision on the privatization of Eletrobras. On the global, the focus remained on the earnings season in the US and developments around the war in Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/netflix-wall-street-downgrades </td>
   <td style="text-align:left;"> 2022-04-20 21:47:22 </td>
   <td style="text-align:left;"> Netflix shares sink as Wall Street bails </td>
   <td style="text-align:left;"> Lead Edge Capital founding and managing partner Mitchell Green told ‘Varney &amp; Co.’ that Netflix lost subscribers after an ‘acceleration’ during the COVID-19 pandemic due to people now spending time and money on in-person activities and travel.                                                                                                                                                                                                                                                                                                                                                                                                                , Shares of Netflix are on track for their worst day in over a decade after at least nine Wall Street analysts downgraded the stock following the streaming behemoth's disappointing earnings results. As of the time of publication, the stock is down more than 36% on Wednesday.                                                                                                                                                                                                                                                                                                                                                                                  , FOX Business surveyed what Wall Street is saying in the following roundup.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , MORE ‘BLEEDING’ TO COME FROM NETFLIX'S STOCK AND BUSINESS, WARNS TECH EXPERT                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Wedbush Securities analyst Michael Pachter has maintained a neutral rating for Netflix and lowered the firm's price target for Netflix from $342 to $280.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Pachter wrote in a note to clients that Netflix faces five major headwinds, including market saturation in the U.S. and Canada; competition for content and wallet share; inflation, and "the effects of a pull-forward to 2020 from shelter-in-place that are only now reversing." He added that the situation between Russia and Ukraine will continue to be a drain on revenues but noted that the impact on subscribers will be more modest.                                                                                                                                                                                                                   , When it comes to password sharing, Pachter expects Netflix will likely change its plan to accommodate legitimate sharing. As for an ad-supported tier, Wedbush expects Netflix to continue to test the concept for "at least several quarters" before making a major change, but it emphasizes that both new and existing subscribers would be receptive to the offering.                                                                                                                                                                                                                                                                                          , Stifel analyst Scott Devine has downgraded Netflix from "buy" to "hold" and cut its price target from $460 to $300.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Thought Stifel believes that some headwinds such as a weaker macro environment and inflation should "prove to be transitory," the firm argues that Netflix will still need to address more secular issues weighing on growth, such as heightened competition, potential maturity in core markets and the prevalence of password sharing.                                                                                                                                                                                                                                                                                                                           , Though Devine acknowledges that ad-supported subscriptions and improved monetization of shared accounts could possibly reinvigorate growth, he notes that both offerings are in early stages of development and are unlikely to materialize in results until the second half of 2023 or 2024.                                                                                                                                                                                                                                                                                                                                                                      , 'BRIDGERTON' SEASON 2 PASSES SEASON 1 IN NETFLIX'S ALL-TIME TV SERIES RANKINGS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Benchmark analyst Matthew Harrigan, who has a "hold" rating on Netflix, told clients in a note on Wednesday that the firm does "not expect much of a rebound from Netflix’s ~90 point/26% aftermarket freefall."                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Benchmark maintains that a "still plausible recovery depends more on much better creative execution and enhanced international production and growth rather than initiatives aimed at addressing password sharing or launching AVOD alternatives."                                                                                                                                                                                                                                                                                                                                                                                                                 , Harrigan also expressed skepticism on Netflix's "add an extra member" strategy being a growth game changer, arguing it "likely cannibalizes full ride member growth." He estimates that a crackdown on password sharing would provide a less than 6% incremental revenue benefit.                                                                                                                                                                                                                                                                                                                                                                                  , In addition, Benchmark does not believe that Netflix's scripted shows, especially when binged viewed, are "conducive to toleration of advertising." Harrigan also argues that Netflix's entry into gaming is unlikely to provide "anything more than an indiscernible reduction in monthly churn" despite its recent acquisitions of studios, including Boss Fight Entertainment.                                                                                                                                                                                                                                                                                  , NETFLIX SAYS MORE THAN 100M HOUSEHOLDS SHARING PASSWORDS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Piper Sandler analyst Thomas Champion has downgraded Netflix from "overweight" to "neutral" and cut its price target from $562 to $293, adding that the firm struggles to see a return to a "preCOVID net add cadence."                                                                                                                                                                                                                                                                                                                                                                                                                                            , "Management tone was subdued and comments point to a host of issues impacting the go-forward sub trajectory, including macro, CTV adoption, password sharing and competition," Champion told clients. "Sub losses continue into 2Q and revenue growth will be lower, likely into '23. While password sharing is being addressed and a new ad-supported tier sounds viable, we substantially lowered sub adds forecasts for '22/'23."                                                                                                                                                                                                                               , A survey conducted by the firm suggests a positive response to an ad-supported offering, with 23% of respondents willing to use an ad-supported tier and 12% willing to unsubscribe and watch ad-supported. About 49% of respondents said they would be willing to keep paying for their subscription, compared to 17% who were unsure because they use someone else’s account. Just 10% of respondents noted using an account outside their household.                                                                                                                                                                                                            , Needham analyst Laura Martin has upgraded Netflix from "underperform" to "hold".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , She argues that Netflix will not be a streaming wars winner unless it adds sports and news content, buys a deep film and TV library and enhances its bundling opportunities to lower churn. In addition, Martin said Netflix's single pricing tier is "much too expensive" compared to its competitors and that subscriber growth will not return unless it adds an ad-driven tier priced at $5 to $7 per month.                                                                                                                                                                                                                                                   , Pivotal analyst Jeffrey Wlodarczak has downgraded the stock from "buy" to "sell" and reduced its price target by nearly 60% from $550 to $235.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Wlodarczak believes that going after the 100 million households who share Netflix accounts is "a real opportunity to boost ARPU (and to lesser extent subscriber) growth in the medium term offset by the potential for a pushback from existing subscribers."                                                                                                                                                                                                                                                                                                                                                                                                     , Meanwhile, Pivotal believes an ad-supported tier "cheapens the brand and the product vs. the current great consumer experience and introduces ad volatility to results."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Wlodarczak warned that Amazon represents "the largest competitive threat" to Netflix moving forward, while Disney+ is seen as "complementary" given its focus on children.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Barclays has maintained an "equal weight" rating on Netflix, but lowered its price target from $380 to $275.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , "Overall, Netflix is now starting to show signs of maturity consistently, which raises bigger questions about actual streaming TAM as well as steady state streaming margins," Barclays analyst Ross Sandler wrote in a note to clients. "Also, we believe the company is starting to fall behind others on strategic growth initiatives as evident in the fact that it is one of the last services to move into ad supported streaming despite years of lead time and evidence of opportunity due to services such as Hulu. The company’s move to monetize password sharing also appears to be reactive due to slowdown in growth, rather than a proactive move." , Barclays warns that Netflix's investments in gaming may potentially slow down as the company has to manage costs more tightly as subscriber growth slows. While the firm believes gaming and advertising can be significant revenue drivers, it predicts that they will not contribute to Netflix in a meaningful way until 2024.                                                                                                                                                                                                                                                                                                                                  , "Consequently, we believe Netflix may need to explore larger strategic partnerships more actively to accelerate its ramp in new growth areas," Sandler adds.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , In addition, the Barclays warns that Netflix's slowdown highlights similar challenges for other streaming competitors, especially Disney.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , "If Netflix is struggling to grow subs at an overall base of ~220mm, it's tough for us to see how Disney+ gets to its goal of 240mm subs at the mid-point of its growth guidance range by 2024," Sandler explains. "In an environment where Netflix is likely to add 5-10mm subs annually, Disney would need to add 44mm in order to get to its long-term sub growth guidance." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61153252?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-20 21:41:32 </td>
   <td style="text-align:left;"> Netflix hints at password sharing crackdown as subscribers fall </td>
   <td style="text-align:left;"> Netflix has hinted it will crack down on households sharing passwords as it seeks to sign up new members following a sharp fall in subscribers.                                                                                                                             , The number of households using the streaming service fell by 200,000 in the first three months of the year as it faced stiff competition from rivals.                                                                                                                       , It was also hit after it raised prices in some countries and left Russia.                                                                                                                                                                                                   , Netflix warned shareholders another two million subscribers were likely to leave in the three months to July.                                                                                                                                                               , "Our revenue growth has slowed considerably," the firm told shareholders on Tuesday after publishing its first quarter results.                                                                                                                                             , "Our relatively high household penetration - when including the large number of households sharing accounts - combined with competition, is creating revenue growth headwinds."                                                                                             , The streaming giant estimates more than 100 million households are breaking its rules by sharing passwords.                                                                                                                                                                 , Boss Reed Hastings previously described the practice as "something you have to learn to live with", adding that much of it is "legitimate" between family members. The firm also said account sharing had probably fuelled its growth by getting more people using Netflix. , But on Tuesday, Mr Hastings said it was making it hard to attract new subscribers in some countries.                                                                                                                                                                        , "When we were growing fast, it wasn't a high priority to work on [account sharing]. And now we're working super hard on it," he told shareholders.                                                                                                                          , The firm said payment plans it is testing to curb password sharing in Latin America could be rolled out to other countries.                                                                                                                                                 , Since last month, account holders in Chile, Costa Rica and Peru must pay to add user profiles for people outside their household (the company currently allows people who live together to share their Netflix account).                                                    , Users can add up to two extra profiles for $2-$3 (£1.53-£2.30) a month each, on top of their regular fee.                                                                                                                                                                   , Netflix - which did not say how it would enforce the rule - said it was seeking a "customer centric" solution.                                                                                                                                                              , "The principle way we have is asking our members to pay a bit more to share the service outside their homes," said Greg Peters, Netflix's chief product officer.                                                                                                            , Dominic Sunnebo, an analyst at research firm Kantar, warned the plan could backfire at a time when consumers were looking for ways to save money.                                                                                                                           , "If the schemes to counter password sharing move too fast and too aggressively, it also risks alienating a potential future audience - many who password-share beyond the household are not actually aware they're breaking the terms of their subscription."               , Netflix said that pulling out of Russia in March in response to the Ukraine war had cost it 700,000 subscribers.                                                                                                                                                            , And another 600,000 people stopped using its service in the US and Canada after it put up prices in January.                                                                                                                                                                , The firm raised prices across all of its US plans, with a basic plan increasing from $9 to $10 per month, and a standard from $14 to $15.50.                                                                                                                                , In the UK, basic and standard plans have both increased by £1 a month to £6.99 and £10.99 respectively.                                                                                                                                                                     , Netflix said the price rises would yield more money for the firm, despite the cancellations. But analysts say the rising cost of streaming services is wearing on households as the cost of living rises.                                                                   , In the UK, households cancelled more than 1.5 million streaming subscriptions in the first three months of the year, with 38% saying they wanted to save money.                                                                                                             , Seeming to acknowledge this, Mr Hastings said Netflix was looking at launching a free ad-supported service like its rivals Disney and HBO.                                                                                                                                  , Analysts say it could open a significant new revenue stream for the company, which has so far shunned advertising.                                                                                                                                                          , "Those who have followed Netflix know that I've been against the complexity of advertising, and a big fan of the simplicity of subscription," he said. "But, as much as I'm a fan of that, I'm a bigger fan of consumer choice."                                            , Netflix's biggest threat is intense competition from firms such as Amazon, Apple and Disney, which are pouring money into their online streaming services, according to experts.                                                                                            , Paolo Pescatore, an analyst at PP Foresight, said Netflix's subscriber loss was a "reality check", as it tries to balance retaining subscribers with raising its revenue.                                                                                                   , Tell us how you have been affected by the issues raised in this story.                                                                                                                                                                                                      , "While Netflix and other services were key in lockdown, users are now thinking twice about their purchasing behaviour based upon changing habits," he said.                                                                                                                 , North America especially is "now awash with too many services chasing too few dollars", he added.                                                                                                                                                                           , Shares in the streaming giant plunged in early trade in New York on Wednesday, dropping more than 30% off the back of the update.                                                                                                                                           , The firm - which remains the world's leading streaming service with more than 220 million subscribers - had enjoyed uninterrupted quarterly growth in subscribers since October 2011.                                                                                       , However, it said a surge in sign-ups during the pandemic had "obscured" the real picture around its growth.                                                                                                                                                                 , It made revenue of $7.8bn (£6bn) in the first three months of the year, up 9.8% compared with the same period last year.                                                                                                                                                    , That marked a slowdown from earlier quarters, while profits fell more than 6% to roughly $1.6bn                                                                                                                                                                             , Bill Bailey on Eurovision and the inspiration for his new show                                                                                                                                                                                                              , Incredible new drama Life After Life                                                                                                                                                                                                                                        , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                                                             , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-04-20 21:36:09 </td>
   <td style="text-align:left;"> Heating Oil Futures Near Six-Week High </td>
   <td style="text-align:left;"> Heating oil futures traded above $3.9 per barrel, recouping losses from the previous session and getting closer to a near six-week high of $3.999 hit at the start of the week, as supply concerns and signs of robust demand in the near-term offset downbeat global growth forecasts. Industry figures showed inventory levels of distillates, which include heating oil, fell by 1.65 million barrels last week, following a larger 4.96 million barrel draw in the previous period. At the same time, daily oil output from OPEC nations and allies stood at 1.45 million barrels last month, as sanctions hit Russian production. Elsewhere, major oil fields in Libya were forced to shut down amid protests. Still, concerns over IMF downgrades to global growth forecasts and virus outbreaks in China capped gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-20 21:35:00 </td>
   <td style="text-align:left;"> Dow Rises, Netflix Drags On S&amp;P 500, Nasdaq </td>
   <td style="text-align:left;"> The Dow added over 300 points in midday trading on Wednesday, while the S&amp;P 500 was up 0.3% and the Nasdaq underperformed by falling 1%, as investors digested a slew of earnings reports. Procter &amp; Gamble and IBM earnings beat forecasts, while P&amp;G saw its sharpest year-over-year sales gain in two decades. On the flip side, Netflix sank almost 40% after reporting it lost 200K subscribers during the first quarter. Also, both earnings and revenues from Baker Hughes missed expectations. Tesla and United Airlines are among the companies due to report later today. Aside from a busy week of corporate earnings, investors are looking ahead to speeches by Fed policymakers and the release of the Fed's Beige Book for new clues on the central bank's policy outlook. Markets have been pricing in that the Fed will speed up the interest rate hike, and it may also shrink its balance sheet in May. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/real-estate/rent-prices-surge-march-housing-market </td>
   <td style="text-align:left;"> 2022-04-20 21:34:25 </td>
   <td style="text-align:left;"> US rent prices reach record highs as buyers pushed out of market </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.                                                                                                                                                                                                                                                 , Rent prices across the U.S. climbed to record highs in March largely because an increasing number of potential buyers are being pushed out of the market, according to a new report.                                                                                                          , The median monthly asking rent increased 17% compared with a year ago, to latex36e5ab6d32bfcaee2476610ff34f517c , compared to market expectations of 0.83 C$ . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/rcib:cn </td>
   <td style="text-align:left;"> 2022-04-20 21:21:35 </td>
   <td style="text-align:left;"> Rogers Communications earnings above expectations at 0.91 CAD </td>
   <td style="text-align:left;"> Rogers Communications (RCIb) released earnings per share at 0.91 CAD, compared to market expectations of 0.83 CAD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-04-20 21:08:24 </td>
   <td style="text-align:left;"> US Natural Gas Futures See Correction </td>
   <td style="text-align:left;"> US natural gas futures extended losses below $7.1 per million British thermal units, more than 12% down from an over thirteen-year high of $8.065 hit at the start of the week, as traders booked some profits following the recent rally. The contract is up roughly 90% so far this year, as harsh wintry weather extended well into spring, causing domestic inventories to shrink well below the five-year average. Earlier this week, an unexpected blizzard dropped more than a foot of snow in the northeast of the US, cutting power to hundreds of households but also boosting heating demand, which should further pressure the replenishment of natural gas stocks. At the same time, the US is exporting LNG cargoes at record levels, mostly to Europe, as the region scrambles to replace Russian gas. On the downside, natural gas output in China is soaring after Beijing pressured state-owned producers to ramp up production, in a bid to cut LNG imports, which have already fallen 11% over the first quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/20/goldman-exec-dustin-cohn-leaves-for-real-estate-investing-start-up-cadre.html </td>
   <td style="text-align:left;"> 2022-04-20 21:05:46 </td>
   <td style="text-align:left;"> Goldman executive who helped create Marcus brand leaves for real estate investing start-up Cadre </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                , Goldman Sachs consumer bank branding chief Dustin Cohn has joined real estate investing start-up Cadre as chief marketing officer, CNBC has learned.                                                                                                                                                                                                                                                           , The departure of Cohn, who is credited with helping name the firm's consumer division Marcus in 2016, is the latest in a wave of exits from the New York-based bank in the past 14 months.                                                                                                                                                                                                                     , Cohn joins other former executives including Omer Ismail and David Stark in leaving Goldman amid plans to scale its retail banking business. Some left to help direct competitors, as was the case of Ismail and Stark, who took flight to assist Walmart in the creation of a fintech start-up. Others, like former Marcus chief Harit Talwar, have stepped down to make way for a new generation of leaders. , Cohn, who called his departure from Goldman "completely amicable," is joining an 8-year-old start-up at a critical juncture, according to Cohn and Cadre co-founder Ryan Williams.                                                                                                                                                                                                                             , Cadre, which allows individuals to take stakes in commercial real estate, is one of the more prominent players in a group of start-ups seeking to broaden access to asset classes once considered the domain of institutional investors or rich families.                                                                                                                                                      , The start-ups hope to achieve what Robinhood did for stocks and what Coinbase did for crypto — tapping the potential of millions of ordinary Americans to create or widen a retail investing category.                                                                                                                                                                                                         , "My goal for Marcus was creating awareness that this new consumer business even existed for this mass affluent audience," Cohn said Tuesday in an interview. "For me, Cadre is a very similar opportunity in the world of commercial real estate, where the average investor really doesn't know much about it to begin with, let alone that they actually have access at these low fees and low entry points.", After poaching Cohn from Goldman — which is both an investor and partner in Cadre — the start-up will begin to ramp up marketing and introduce new products aimed at smaller investors, Williams said.                                                                                                                                                                                                         , While it might be simpler to focus only on big-money investors like family offices or endowments, that wouldn't align with Cadre's mission, said Williams, who had stints in the financial industry before co-founding Cadre in 2014.                                                                                                                                                                          , "I grew up working class in Baton Rouge, Louisiana," Williams said. "I never had access to the asset class but through my experiences at Goldman and Blackstone more recently, I just saw how lucrative the space was, but how inaccessible it was for most individuals."                                                                                                                                      , Cadre initially began with bigger investors and required a $250,000 minimum stake; after taking that down to $25,000, the company hopes to lower minimums closer to $2,500, according to the CEO.                                                                                                                                                                                                              , The company's investment committee focuses on three categories of real estate in roughly 15 U.S. markets: multifamily apartment buildings, industrial properties like warehouses, and niche office space like suburban buildings, Williams said.                                                                                                                                                               , Cadre said it has closed more than $4.5 billion in real estate deals and produced returns of more than 18% across property sales. Unlike some of the competitors in the space, Cadre hasn't lost investor money yet, Williams said.                                                                                                                                                                            , "We're not taking crazy risks like others do, and we think that's the right way for people to get access to the asset class," Williams said. "We've never lost investor principle or capital."                                                                                                                                                                                                                 , An IPO could be 12 to 18 months away, after the company introduces new products including ways to invest in real estate debt or even new categories like timber farms, Williams said. Cadre commissioned a study of 1,181 consumers, finding that almost three-quarters were interested in investing in commercial real estate, but that nearly all had never done so.                                         , Cadre has raised funding from investors including Andreessen Horowitz and Jared and Josh Kushner, who are also co-founders of the start-up. While the Kushners remain investors, Cadre has said that Jared Kushner hasn't been involved in operations since Kushner joined the Trump administration as an advisor.                                                                                             , Meanwhile, Cohn's departure also comes at a crucial point for the Marcus brand.                                                                                                                                                                                                                                                                                                                                , Starting with personal loans and deposits, Goldman has added credit cards and home renovation loans to its portfolio and is working on a digital checking account for the masses. Then, late last year, the company announced it was tweaking its branding to more prominently display the Goldman name, calling it Goldman Sachs Marcus.                                                                      , Cohn, who said that he "personally named Marcus," called the change a validation of his tenure at the bank. Back in the 2015 timeframe, the Goldman name "conjured up some of the negativity that people have towards Goldman Sachs," he said.                                                                                                                                                                 , "Here we are, almost seven years later, and the Goldman Sachs brand is at an all-time high with these consumers," Cohn said. "A big part of that is because we gave them valuable products to help them achieve their goals."                                                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/antm:us </td>
   <td style="text-align:left;"> 2022-04-20 20:45:40 </td>
   <td style="text-align:left;"> Anthem earnings above expectations at 8.25 USD </td>
   <td style="text-align:left;"> Anthem (ANTM) released earnings per share at 8.25 USD, compared to market expectations of 7.85 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/stock-market </td>
   <td style="text-align:left;"> 2022-04-20 20:45:32 </td>
   <td style="text-align:left;"> Stocks in Turkey Hit All-time High </td>
   <td style="text-align:left;"> BIST 100 increased to an all-time high of 2533 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/copper </td>
   <td style="text-align:left;"> 2022-04-20 20:45:00 </td>
   <td style="text-align:left;"> Copper Hits 4-week Low </td>
   <td style="text-align:left;"> Copper futures bottomed around the $4.6-per-tonne mark, a level not seen in a month, as coronavirus-induced lockdowns in top consumer China sparked concerns about demand. China's COVID-19 outbreak already has hit economic activity and triggered government pledges for more stimulus to support the world's second-largest economy. Pressuring prices further were recent data showing that copper inventories in LME-approved warehouses rose to the highest level since October, up 12,275 tonnes to 128,775 tonnes. Meanwhile, those in the Shanghai Futures Exchange fell to a two-month low of 88,682 tonnes. Elsewhere, MMG Ltd said its Las Bambas copper mine in Peru would suspend operations from April 20 after the Fuerabamba community invaded the property as part of a protest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ivory-coast/inflation-cpi </td>
   <td style="text-align:left;"> 2022-04-20 20:42:00 </td>
   <td style="text-align:left;"> Ivory Coast March Inflation Rate Hits 5-Month Low </td>
   <td style="text-align:left;"> The annual inflation rate in the Ivory Coast eased for the second straight month to 4.5% in March of 2022, from 4.6% in the previous month. It was the lowest reading since October last year, amid a slowdown in prices of food &amp; non-alcoholic beverages (8.5% vs 8.8% in February), namely fresh vegetables (14.4% vs 30.4%) and unprocessed cereals (6.4% vs 9%). Costs also rose at a softer pace for communications (2.1% vs 2.7%), while inflation remained steady for transportation (at 3.6%) and housing &amp; utilities (at 5.7%). On a monthly basis, consumer prices were up 0.1%, slowing from a 0.3% rise in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/house-price-index-mom </td>
   <td style="text-align:left;"> 2022-04-20 20:38:00 </td>
   <td style="text-align:left;"> Canada New Home Prices Rise Faster in March </td>
   <td style="text-align:left;"> New home prices for Canada rose 1.2 percent from a month earlier in March of 2022, the fastest advance since last May and following a 1.1 percent increase in the prior month. Prices were up in 18 of the 27 census metropolitan areas surveyed and unchanged in 9, with most home builders citing rising construction costs as the main inflationary factor. For the third month in a row, Calgary led gains with a 4.1 percent increase, as it recorded the highest amount of sales ever. Year-on-year, new home prices climbed 11.0 percent, quickening from a 10.9 percent rise in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/inflation-cpi </td>
   <td style="text-align:left;"> 2022-04-20 20:38:00 </td>
   <td style="text-align:left;"> Canada Inflation Rate Climbs to 31-Year High </td>
   <td style="text-align:left;"> Canada’s annual inflation rate quickened to 6.7% in March of 2022, the highest since January of 1991 and well above market expectations of 6.1%, against the backdrop of sustained housing prices, substantial supply constraints, and geopolitical conflict that lifted prices for energy and agricultural markets. Prices rose faster for all eight major components, notably for transportation (11.2% vs 8.7% in February), largely due to surging prices for gasoline (39.8% vs 32.3%). Significant pressure also came from shelter (6.8% vs 6.6%), due to homeowners’ replacement cost (12.9%) and rent (4.1%), and food (7.7% vs 6.6%), as the prices in grocery stores increased at the fastest rate in 13 years. Excluding gasoline, the CPI rose at a fresh record pace of 5.5%. On a monthly basis, consumer prices rose 1.4%, surpassing forecasts of a 1% increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/20/business/media/new-york-times-managing-editors.html </td>
   <td style="text-align:left;"> 2022-04-20 20:35:02 </td>
   <td style="text-align:left;"> New York Times Names Marc Lacey and Carolyn Ryan as Managing Editors - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                         , Supported by                                                                                                                                                                                                                                                                                                          , A pair of veteran Times journalists will serve in the newsroom’s No. 2 position under the new executive editor, Joe Kahn.                                                                                                                                                                                             , Send any friend a story                                                                                                                                                                                                                                                                                               , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                        , By Michael M. Grynbaum                                                                                                                                                                                                                                                                                                , Joseph F. Kahn, newly appointed as the next executive editor of The New York Times, announced his leadership team on Wednesday in a memo that urged his colleagues “to produce the most ambitious, consequential and creative work of our careers.”                                                                   , Two veteran Times journalists, Marc Lacey and Carolyn Ryan, are to serve as managing editors, the newsroom’s No. 2 role, starting on June 14.                                                                                                                                                                         , “Both will share with me responsibility for overseeing the breadth of our coverage and news operation,” Mr. Kahn wrote in the memo, as well as “advancing major priorities like independence and trust, digital excellence and cultural transformation.”                                                              , Mr. Lacey, 56, is an assistant managing editor who previously oversaw The Times’s national coverage; before that, he was a Times correspondent in Mexico City; Nairobi, Kenya; Phoenix; and Washington.                                                                                                               , Ms. Ryan, 57, is a deputy managing editor who most recently led recruiting for The Times, overseeing the hiring of more than 400 journalists, and she helped lead its diversity, equity and inclusion efforts. Before that, she was the paper’s political editor, Washington bureau chief and metropolitan editor.    , Ms. Ryan will be the first openly gay journalist to serve as managing editor of The Times. Mr. Lacey is the third Black journalist to serve in the role, after Gerald Boyd and Dean Baquet, the current executive editor.                                                                                             , Mr. Kahn also announced four deputy managing editors.                                                                                                                                                                                                                                                                 , Rebecca Blumenstein, currently the deputy editor in the publisher’s office and a deputy managing editor, will lead recruitment and operations. Sam Dolnick, currently an assistant managing editor, will continue to spearhead The Times’s expansion into audio, video, email newsletters and televised documentaries., Steve Duenes and Clifford Levy will remain deputy managing editors. Mr. Duenes will oversee The Times’s visual and multimedia journalism. Mr. Levy will focus on ethical standards and journalistic independence, as well as training for editors throughout the newsroom.                                            , Matthew Purdy, currently a deputy managing editor and a force behind many of The Times’s major investigative projects, will take on a senior, as-yet-undefined role, Mr. Kahn wrote.                                                                                                                                  , In a joint interview, Mr. Lacey and Ms. Ryan said they intended to reimagine the role of a managing editor — once preoccupied with duties like selecting stories for the printed front page — given The Times’s growing digital footprint.                                                                            , “It’s such a big, sprawling place,” Mr. Lacey said. “We produce more than 150 pieces of journalism every single day in all sorts of forms, and we want all of those to be excellent.”                                                                                                                                 , Ms. Ryan added: “We are essentially and fundamentally driven by rigorous and original reporting, on-the-ground reporting. That has to be at the heart of everything that we do.”                                                                                                                                      , Born in Flushing, Queens, Mr. Lacey grew up on the island of Jamaica and in Buffalo. At Cornell, he majored in biology and edited The Cornell Daily Sun around the same time that Mr. Kahn led The Harvard Crimson. He worked at The Buffalo News and The Los Angeles Times before joining The Times in 1999.         , Ms. Ryan grew up outside Boston and attended Bates College in Maine, where she studied English literature. Her first job in journalism was at The Patriot Ledger in Quincy, Mass.; she was later metro editor and deputy managing editor at The Boston Globe, before joining The Times in 2007.                       , Mr. Lacey and Ms. Ryan collaborated in 2019 when The Times and CNN sponsored a Democratic presidential primary debate in Ohio. Mr. Lacey served as one of the moderators, and Ms. Ryan, a political junkie, worked alongside him during several weeks of planning sessions.                                           , “We do happen to get along very well,” Mr. Lacey said, although he added, to Ms. Ryan’s laughter, that the two of them were fierce opponents at the Ping-Pong table.                                                                                                                                                  , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sand:ss </td>
   <td style="text-align:left;"> 2022-04-20 20:23:05 </td>
   <td style="text-align:left;"> Sandvik earnings below expectations at 2.70 SEK </td>
   <td style="text-align:left;"> Sandvik (SAND) released earnings per share at 2.70 SEK, compared to market expectations of 3.14 SEK. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-20 20:22:00 </td>
   <td style="text-align:left;"> South African 10-Year Bond Yield Rises on Fiscal Woes </td>
   <td style="text-align:left;"> The yield on the South African 10-year bond was around 9.9%, the highest since March 10th, as fiscal concerns resurfaced after the government said it will ask parliament for additional funding after allocating 1 billion rand to repair damages caused by widespread floods. At the same time, signs of a resurgence of Covid-pandemic and severe power cuts implemented by state-owned power utility Eskom added to concerns over the country's economic recovery. Meanwhile, investors braced for more aggressive monetary policy tightening by major central banks, especially the Fed. Domestically, South Africa’s central bank lifted its benchmark interest rate for a third straight meeting on March 24th and signaled it will raise borrowing costs more aggressively through 2024. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/600048:ch </td>
   <td style="text-align:left;"> 2022-04-20 20:20:46 </td>
   <td style="text-align:left;"> Poly Real Estate earnings below expectations at 1.22 CNY </td>
   <td style="text-align:left;"> Poly Real Estate (600048) released earnings per share at 1.22 CNY, compared to market expectations of 1.27 CNY. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-04-21 09:38:59 UTC +8

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
   <td style="text-align:left;"> 2022-04-21 09:37:27 </td>
   <td style="text-align:left;"> $SPY guys.  No drugs for a while </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:36:18 </td>
   <td style="text-align:left;"> $SPY I don’t know what’s out there to hold up SPY tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:36:14 </td>
   <td style="text-align:left;"> $SPY Go Bulls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:35:31 </td>
   <td style="text-align:left;"> $SPY always was curious why the guy with progressing dementia becomes a president. 
&amp;quot;Former BlackRock investment executive Brian Deese leads Biden&amp;#39;s National Economic Council, effectively serving as his top advisor on economic matters. Biden also tapped Adewale &amp;quot;Wally&amp;quot; Adeyemo, a former chief of staff to BlackRock chief executive and longtime Democrat Larry Fink, to serve as a top official at the Treasury Department.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:35:18 </td>
   <td style="text-align:left;"> $SPY $DJIA  … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:35:09 </td>
   <td style="text-align:left;"> New Analysis: Why Wednesday’s price action was bullish, plus what the next 12 months in $NFLX will look like: https://cracked.market/2022/04/why-wednesdays-price-action-was-bullish-plus-what-the-next-12-months-in-nflx-will-look-like/ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:35:07 </td>
   <td style="text-align:left;"> $SPY  Powell. When will you stop pumping this garbage?! I&amp;#39;m here to try to earn a living. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:34:24 </td>
   <td style="text-align:left;"> $SPY Stonks still have the woke mind virus.  F your pronouns. 💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:34:10 </td>
   <td style="text-align:left;"> $SPY SPY 2022-04-20 Daily Forecast Video: 
https://www.youtube.com/watch?v=j4PR86MCdUM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:33:49 </td>
   <td style="text-align:left;"> $SPY $QQQ how we gonna react to Powell tomorrow? Any predicitions? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:33:23 </td>
   <td style="text-align:left;"> $SPY Cramer already give out another stocks he his bullish on. I really like his due diligence 🤣🤣🤣🤣 Anyway, I’m making banks tomorrow/Friday, God’s willing $QQQ 

🤐 🤐🤐🤐🤐🤐🤐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:32:52 </td>
   <td style="text-align:left;"> $SPY roughly 1.4 million Adults in the United States currently Identify as Transgender. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:31:49 </td>
   <td style="text-align:left;"> $SPY there’s a big move coming on Friday. More certain if we close flat tomorrow. Downside more likely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:31:34 </td>
   <td style="text-align:left;"> $SPY yes bulltards .....great buying opportunity lol 😆 😋 🤣 😄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:30:55 </td>
   <td style="text-align:left;"> $SPY Nobody ever covers the elephant in the room. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:29:55 </td>
   <td style="text-align:left;"> $SPY last year around this time, Apple tanked for 2 weeks after earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:29:02 </td>
   <td style="text-align:left;"> $SPY Can’t wait till next cpi data is even higher and market pumps because they say no this has to be peak inflation if it was worse then March and they never let this thing come down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:28:56 </td>
   <td style="text-align:left;"> $SPY 

This is for @sonicmerlin 

And the bear cub traders 
Enjoy moron moo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:28:55 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:28:39 </td>
   <td style="text-align:left;"> $SPY celts brooklyn game just awesome- never seen Durant look so helpless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:28:38 </td>
   <td style="text-align:left;"> $SPY I spy with my little eye NLST 10X after taking down Google in a patent infringement trial that made Google a top company that is all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:28:22 </td>
   <td style="text-align:left;"> $NFLX
Transgender population is almost hitting 5,71 Billion this year. Netflix has definitely seized this opportunity.

$SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:26:59 </td>
   <td style="text-align:left;"> $SNAP crap chat $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:26:58 </td>
   <td style="text-align:left;"> 🚨WE ARE NOW LIVE🚨 
🔥GAINZ STREAMZ TRADE IDEAS🔥 
IM GOING TO BREAKDOWN 👇 
📈TRADE IDEAS 
🔫TRIGGERS 
🎯TARGETS 
CLICK&amp;gt;https://us02web.zoom.us/j/86761922065 $SPY  $AMC  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:25:55 </td>
   <td style="text-align:left;"> $SPY could get a face ripper tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:25:49 </td>
   <td style="text-align:left;"> $SPY for the degenerates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:25:48 </td>
   <td style="text-align:left;"> $SPY 450-455-460 easy money 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:24:52 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:24:29 </td>
   <td style="text-align:left;"> $SPY soo tired 💤  going to sleep for real </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:24:02 </td>
   <td style="text-align:left;"> $SPY how are there bears that survived? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:23:45 </td>
   <td style="text-align:left;"> $SPY why Japan decided to buy so many $$$ everyday??? Does Fed force BoJ to buy $$ to make $ strong?? In that case what happens to other currencies like Chinese yuan and bunch of others get weaken too.. not just yen..? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:23:24 </td>
   <td style="text-align:left;"> $SPY lol red box trippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:23:08 </td>
   <td style="text-align:left;"> $SPY &amp;quot;It&amp;#39;s priced in&amp;quot; goes both ways. Remember that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:22:57 </td>
   <td style="text-align:left;"> $SPY my girls ex blocked my number on her phone #classic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:22:33 </td>
   <td style="text-align:left;"> $SPY There has to be some hedge funds imploding right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:21:32 </td>
   <td style="text-align:left;"> $SPY British soldier captured and explains the atrocities UKRAINIAN forces have perpetrated $DWAC 

https://battleplan.news/watch?id=62606c5aba40861bbed21690 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:21:02 </td>
   <td style="text-align:left;"> $SPY When I think about Ackman I think about the Wall St game &amp;amp; how he gets to play it. 
A $400m loss on $nflx, an almost $4b loss in Valeant &amp;amp; yet he still gets to run a HF &amp;amp; people still give him money. 
 
Amazing isn&amp;#39;t it? 
 
https://www.yahoo.com/news/3-lessons-from-bill-ackmans-4b-trading-loss-in-valeant-182037105.html 
 
$baba $aapl $bb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:20:45 </td>
   <td style="text-align:left;"> Daily Market Update for 4/20 
$NASDAQ $COMPQ $IXIC $SPY $DJIA $RUT 
https://www.drewby.com/2022/04/20/daily-market-update-for-4-20-2/ 
Yields on longer-term treasuries dropped sharply today as did the US Dollar index . Growth stocks led the Nasdaq lower while the Dow Jones Industrial Average closed higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:20:44 </td>
   <td style="text-align:left;"> $SPY buying all dips on discount today. mofos boutta rip. honestly saw netflix drop coming from a mile away. ARKK double bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:17:56 </td>
   <td style="text-align:left;"> $SPY $SPX500 $QQQ Here&amp;#39;s a weekly trend channel chart of SPX500 with a couple of scenario&amp;#39;s and key activity levels for the next 6-12 months.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:17:12 </td>
   <td style="text-align:left;"> $SPY “the market tends to do what hurts the most people” 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:15:54 </td>
   <td style="text-align:left;"> $SPY What a baby and sore loser. SAD!  
https://www.rawstory.com/piers-morgan-trump/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:15:51 </td>
   <td style="text-align:left;"> $SPY $MRNA Clot shot being exposed

https://battleplan.news/watch?id=626062a7ba40861bbecf4c8b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:15:47 </td>
   <td style="text-align:left;"> $SPY are we sure the Russians are the bad guys? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:15:20 </td>
   <td style="text-align:left;"> $SPY going down eod tomorrow will be a blood bath!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:15:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $ETH.X This is what Elon had to say about the &amp;#39;woke&amp;#39; Left, and I agree with him one-hundred! 
 
“Generally, I think we should be aiming for a positive society and it should be okay to be humorous. Wokeness basically wants to make comedy illegal which is not cool. 
 
&amp;quot;At its heart wokeness is divisive, exclusionary and hateful. It basically gives mean people a shield to be cruel, armored in false virtue.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:14:59 </td>
   <td style="text-align:left;"> $DWAC $SPY  I wonder what these woke dummies think when they see such smart person squash them like the fleas they are....   https://www.msn.com/en-us/money/companies/why-elon-musk-believes-woke-mind-virus-and-wokeness-are-threats-to-modern-civilization/ar-AAWqkcA?ocid=msedgntp&amp;amp;cvid=e21ad95d140140cdb51fa1785ce3dd13 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:14:54 </td>
   <td style="text-align:left;"> $SPY . $NDX . $NASDAQ . $QQQ 

Russia Putin Threatens The West Directly right now. 

Firing off a test Intercontinental ballistic missile. 

Breaking news 📰 CNN.    …  …. …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:14:32 </td>
   <td style="text-align:left;"> $SPY inverse ackman </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:14:29 </td>
   <td style="text-align:left;"> $SPY . $NDX . $NASDAQ . $QQQ 

Russia Putin Threatens The West Directly right now. 

Firing off a test Intercontinental ballistic missile. 

Breaking news 📰 CNN. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:13:55 </td>
   <td style="text-align:left;"> $AAPL i&amp;#39;m dead, ackman shorts market runs higher, he capitulates short the market drops. ackman buys netlfix it tanks,  capitulates shares, so rocket up now $NFLX $GME $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:12:50 </td>
   <td style="text-align:left;"> $SPY Happy Holiday everyone!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:12:40 </td>
   <td style="text-align:left;"> $SPY  Russia test launches  intercontinental missle just now.    

Putin warns the “WEST”

 Breaking News CNN.  . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:12:27 </td>
   <td style="text-align:left;"> $NFLX such strong EPS and its dropping to lows.. definitely wanted ackman to capitulate, i can&amp;#39;t believe he actually did lol $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:11:13 </td>
   <td style="text-align:left;"> $QQQ considering the market hasn&amp;#39;t crashed yet $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:11:09 </td>
   <td style="text-align:left;"> Reducing Inequality, Hiking Minimum Wage Could Boost U.S. Economy: White House

https://amp.insurancejournal.com/news/national/2022/04/20/663466.htm

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:11:05 </td>
   <td style="text-align:left;"> $SPY end of war is near boys!! then we are back on track for a girthy 2022 $IWM $QQQ $NFLX $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:11:04 </td>
   <td style="text-align:left;"> $SPY the most I&amp;#39;ve paid for one option contract is like 40k.  Is that crazy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:10:37 </td>
   <td style="text-align:left;"> $TSLA bulls probably think food grows in the super market. Keep buying the bubble. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:10:31 </td>
   <td style="text-align:left;"> $SPY This market is like a spider that wont die, were gonna have to burn the whole house down to kill it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:10:12 </td>
   <td style="text-align:left;"> $TSLA $SPY 

Elon in his bag. Flexin on em </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:10:05 </td>
   <td style="text-align:left;"> $SPY ackman capitulated $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:09:56 </td>
   <td style="text-align:left;"> $SPY there’s no sellers.  Oh well.  Time for dinner. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:09:47 </td>
   <td style="text-align:left;"> $SPY $NFLX Little Billy lost $400 Million on his bet, market has become ruthless. That’s what happens when they kept pumping crap to sky high valuations </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:09:46 </td>
   <td style="text-align:left;"> $SPY i sold my NFLX as soon as i saw 600 bucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:09:43 </td>
   <td style="text-align:left;"> $SPY lol ackman capitulated $NFLX gonna run right back up, they must have wanted him out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:09:42 </td>
   <td style="text-align:left;"> $SPY all this drama over the past 6 months and here we are, still at nearly 450! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:09:32 </td>
   <td style="text-align:left;"> $SPY Getting close to going away in May. Look out below!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:09:21 </td>
   <td style="text-align:left;"> $spy Everyone giving my man Billy Ackman a hard time with his 500 million dollar $NFLX loss. With his capital…it only dropped his YTD by 4 %…Pfft…I’ve dropped that much in one trading session. The guys an amateur… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:09:01 </td>
   <td style="text-align:left;"> $SPY 

But but but NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:08:05 </td>
   <td style="text-align:left;"> $SPY 438 by Friday. Might see 453 first. At 438 I’m loading 460c. Good luck 👍🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:07:49 </td>
   <td style="text-align:left;"> $SPY 

Load up leaps for spy what’s the zone ???

Currently calculated at roughly 

390 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:07:21 </td>
   <td style="text-align:left;"> $SPY $TSLA  Tesla we played it well today. Puts printed. All cash EOD watching for fresh entries tomorrow $QQQ $SHOP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:07:18 </td>
   <td style="text-align:left;"> $SPY when is the last time JPow spoke and didn’t pump the market within an hour of completion? Long time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:07:17 </td>
   <td style="text-align:left;"> $SPY $DXY does it pull back and form a handle, or just keep going </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:07:02 </td>
   <td style="text-align:left;"> $SPY there are turds on here still complaining about Fauchi?? 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:07:01 </td>
   <td style="text-align:left;"> $SPY $NFLX muh dude </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:06:49 </td>
   <td style="text-align:left;"> $SPY wow... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:06:37 </td>
   <td style="text-align:left;"> $SPY Cathie will jump on NFLX band wagon... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:06:35 </td>
   <td style="text-align:left;"> $SPY Tesla...priced in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:05:34 </td>
   <td style="text-align:left;"> $SPY Apr 20               
Sell               
◆ Search for 10 day stock forecast by pretiming A.I               
http://www.google.com/search?q=10+day+stock+forecast               
◆ Forecast of Upper~Lower price range band for the next 10 days               
Price: 433.54   ~ 444.71            
% Change: -2.51%  ~ 0.00%           
The Buy-Sell strength is suitable for the current trend and it&amp;#39;s about to begin a downward trend as a rebounding trend gradually gives way to increasing limited rises and strong falls in the falling section. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:05:33 </td>
   <td style="text-align:left;"> $SPY Copping the milgauss flooded what do y’all think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:05:29 </td>
   <td style="text-align:left;"> $SPY $QQQ fintwit is going crazy for this chart, but my hot take is that where we’re at in this cycle is the green arrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:05:22 </td>
   <td style="text-align:left;"> $AAPL $AMZN $GOOG  
 
Now which one of you is going to fall on earnings? 🤔 
 
$SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:05:02 </td>
   <td style="text-align:left;"> $SPY 

Vix spike to 40 buy more

Duh 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:04:55 </td>
   <td style="text-align:left;"> $SPY $442 retest now that the gap is filled RESISTANCE $447 could touch both tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:04:41 </td>
   <td style="text-align:left;"> $SPY Another $15B printing spotted by Powell printer again. Don’t worry, powell is fighting inflation by printing more money 💰 $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:04:32 </td>
   <td style="text-align:left;"> $TSLA $TWTR elon musk trying to save the world or create new world order to enslave humanity? He is a former World Economic Forum Young Global Leader,  Klaus Schwab with great reset. $SPY $PFE 
 
https://www.bloomberg.com/news/articles/2008-03-17/young-global-leaders-anderson-cooper-and-leonardo-dicaprio-are-in-the-most-exclusive-private-social-network-in-the-world-dot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:04:23 </td>
   <td style="text-align:left;"> $SPY 

If spy is 450 or 350

We continue to buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:04:22 </td>
   <td style="text-align:left;"> $SPY Remember...it&amp;#39;s priced in... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:03:56 </td>
   <td style="text-align:left;"> $SPY fraudchi muahaha... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:03:22 </td>
   <td style="text-align:left;"> $SPY $QQQ AT 9:45AM, BIDEN WILL GIVE AN UPDATE ON THE SITUATION IN UKRAINE AND RUSSIA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:03:17 </td>
   <td style="text-align:left;"> $SPY Anyone else get the idea that Powell sees the unenthusiasm and virtually boring stock market &amp;amp; just finally tells it to Wall Street straight that inflation is going to go nuts if we don&amp;#39;t high consider a 0.75% hike like Bullard just stated he wanted to do &amp;amp; then we need to really reduce the balance sheet in May, rapidly, like Lael wants to do.

Anyone else think Powell just goes ultra-aggressive suddenly because he realizes that&amp;#39;s the proper QE toolbox move &amp;amp; &amp;quot;maybe I shouldn&amp;#39;t say this but I&amp;#39;ve been influenced by Biden &amp;amp; other members to vote unlike I really should so economy not crash &amp;amp; cause recession quickly but maybe it&amp;#39;s what we need now to restart growth. Pain now, gain later. Otherwise, I don&amp;#39;t do it, we could see 17% real inflation &amp;amp; 12-14% CPI jump by the 4th (of July).&amp;quot; 

Wouldn&amp;#39;t that be some kind of rabbit pulled out of the hat, bulls? 

Baboooom $TSLA $QQQ $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:03:10 </td>
   <td style="text-align:left;"> $SPY is that war for the USSR over? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:02:23 </td>
   <td style="text-align:left;"> $SPY $ARKK $TSLA  Cathie as usual doubling down on her losers and selling the winners. Surprised she didn’t buy any Netflix today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:01:37 </td>
   <td style="text-align:left;"> $SPY 

The second is goes down a little. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:01:32 </td>
   <td style="text-align:left;"> $SPY god dang stop printing.  Jesus Christ whatever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:01:30 </td>
   <td style="text-align:left;"> $SPY Happy 🕠 420 ☝️ to the coolest 😎 stoners 💯 and pot 🗿 heads out ☮ there. Blaze 🔥 🆙️ ⬆️ those 🌴 trees and 🖕 fuck the 👮‍♂️🚔 po po❗ Make sure 🙊 to have 🌮🍕🍖🍗 munchies 🍝🍦🎂🍩 ready because 🚬 this 420 😤 comes once 🎈 every 💯 thousand 🗓♻️ years! So cheef 😱 the 💪 fattest 🤜🤛 doofers 🌬 and keep 🙈 those 👀 eyes blazed 😲 and 😑 barely 🛒 open! 🤙 Namaste 🕉 Blaze 🇨🇬 🚼 Babies! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:01:21 </td>
   <td style="text-align:left;"> $SPY spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:00:59 </td>
   <td style="text-align:left;"> $SPY idk bulltards, based on my TA I see this going down every tick until 11am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:00:39 </td>
   <td style="text-align:left;"> POTUS $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 09:00:30 </td>
   <td style="text-align:left;"> $SPY VIX below 20 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:59:41 </td>
   <td style="text-align:left;"> $SPY Fauci ouchi all over growth stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:59:33 </td>
   <td style="text-align:left;"> $SPY my favorite report comes out tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:59:27 </td>
   <td style="text-align:left;"> $SPY Good set up for a big run tomorrow. Buying calls at open, still too much bearish sentiment and puts opened. This will rally with tesla tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:59:09 </td>
   <td style="text-align:left;"> $ES_F $SPY looks like bear explosion 4 hr bull run hold onnnn 🏃‍♀️ 🏃‍♀️ 🏃‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:59:05 </td>
   <td style="text-align:left;"> $SPY Market was doing fine until we stopped wearing masks. Fauci and his Illuminati angry and getting revenge? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:58:30 </td>
   <td style="text-align:left;"> $SPY I have a new method that works quite well for running money/cash. Take some of my winnings from IBKR everyday and buy $ETC.X in Coinbase and set my bonus purchase  % to XLM. I put gas on company card but the Coinbase card works for cash and anything in between and yields better than a MM. 
Still pay my bills straight out of IBKR but the Crypto cash thing is just another level of exposure….
Thought it worth sharing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:58:07 </td>
   <td style="text-align:left;"> $TSLA $SPY $TWTR 

Elon seems to have  his funding secured to buy $TWTR AH based on Tesla stock UP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:58:07 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F  going back to $4360 overnight. 

Goodnight 💤 it’s been a long choppy day 

 . $QQQ                                                         $DJIA  🧞‍♂️. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:57:53 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Market so fked up I&amp;#39;ll take my crack pipe now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:57:27 </td>
   <td style="text-align:left;"> $SPY $DWAC $TWTR  
 
I bIame Trump for masks 
 
If he forced it on IiberaIs first they wouId have been against it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:57:23 </td>
   <td style="text-align:left;"> $SPY real estate market slowing down. Lockbox indicator down 19% in the past two weeks. Real estate sales numbers we are seeing now we’re from contracts signed two months ago. Get ready for pain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:57:18 </td>
   <td style="text-align:left;"> $SPY futures dying already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:57:09 </td>
   <td style="text-align:left;"> $SPY hey guys! Anyone INVEST in solar? Which are the big players? Value guys with potential? Idk anything you got really thanks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:56:51 </td>
   <td style="text-align:left;"> $SPY TSLA recovered what it lost today so it&amp;#39;s a non-event </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:55:39 </td>
   <td style="text-align:left;"> $SPY foreign currencies used to disturb markets. Now TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:55:27 </td>
   <td style="text-align:left;"> $SPY one is guarenteed to expire worthless, twos a given, three tho sir? There&amp;#39;s a saying in Tennessee I know it&amp;#39;s in Texas probably same in Tennessee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:55:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  * posted this China manufacturing warning April 01 when China contracted 1st time in 2 years since Covid started.   
 
now the GDP  forecast drop..  another big caution.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:55:11 </td>
   <td style="text-align:left;"> $SPY $VIX VIXXXXXXX DUMPPPPPP!!!!! 😁😁😁😁😁😁😁😁😁😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:54:52 </td>
   <td style="text-align:left;"> $SPY musk boning depps wife. What does this guy not do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:54:09 </td>
   <td style="text-align:left;"> $SPY Powell at 11:00 am &amp;amp; 1:00 pm tomorrow... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:53:36 </td>
   <td style="text-align:left;"> $ZIM Finally, somebody is recognizing the technology advantages that ZIM has against its competitors!  Maybe now they&amp;#39;ll trade more like a technology stock and get more than a 1.6X P/E (industry average is 4) 
 
$ZIM $SPY $TSLA $TWTR 
 
https://www.youtube.com/watch?v=LMyinaRKNiE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:53:26 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F  Spy sucks when you wake up and your calls drop more than 60 % in value    🧞‍♂️.   It’s true 

It’s true happens to the best of everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:52:52 </td>
   <td style="text-align:left;"> $BABA closed under 90 today. No one else gives you precise targets with deadlines… for free. $TSLA $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:51:38 </td>
   <td style="text-align:left;"> $SPY 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:51:01 </td>
   <td style="text-align:left;"> $UVXY $SPY jp will crash the market tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:49:33 </td>
   <td style="text-align:left;"> Happy pointy clover day. Bless each of you and all others dear to you ♥️ $sndl $hexo $acb $tlry $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:49:29 </td>
   <td style="text-align:left;"> $SPY $ES_F $SPX  Spy Sucks when you end up on the wrong side like now   🧞‍♂️

Bye bye 👋. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:49:15 </td>
   <td style="text-align:left;"> $MP: Still like this swing. Having a tough time under the daily downtrend line, but once that breaks, this should run. Found support at the 100 sma today, which is where we added more. Still confident this swing pays nicely. 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:48:49 </td>
   <td style="text-align:left;"> $SPY most likely another resistance test before a reversal, lower into tomorrow. Eyes on volume and price action into open and intraday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:48:17 </td>
   <td style="text-align:left;"> $NFLX open up below $100.   $QQQ $SPY 

 . $DIA                                                     $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:47:02 </td>
   <td style="text-align:left;"> S&amp;amp;P Futures 
4,474.25 
+18.75(+0.42%) 
Dow Futures 
35,182.00 
+103.00(+0.29%) 
Nasdaq Futures 
14,103.00 
+98.25(+0.70%) 
Russell 2000 Futures 
2,043.70 
+7.00(+0.34%) 
 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:47:01 </td>
   <td style="text-align:left;"> $SPY meh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:46:59 </td>
   <td style="text-align:left;"> $SPY if nikkei breaks out then target is 28000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:46:53 </td>
   <td style="text-align:left;"> $SPY this just the beginning of massive sell off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:46:47 </td>
   <td style="text-align:left;"> $SPY We gapping up after TSLA huge er beat tomorrow on indexes especially Qs and SPY
Target here @447plus that closes the gap left above on the weekly chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:45:57 </td>
   <td style="text-align:left;"> $SPY $3800.      $SPX $ES_F $QQQ $NDX 

Tech.nical    Breaks down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:45:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA Huge squeeze incoming tomorrow? Bigly bull gains to be made, poor shorts/bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:45:47 </td>
   <td style="text-align:left;"> $SPY they really dried the algo powder lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:45:36 </td>
   <td style="text-align:left;"> $SPY 460 easy money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:45:11 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY green futures likely red by morning just like deep red yesterday was green by open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:45:10 </td>
   <td style="text-align:left;"> $SPY SOMEONES getting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:45:07 </td>
   <td style="text-align:left;"> $SPY nq probably breakout to 14200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:44:45 </td>
   <td style="text-align:left;"> $SPY This is pretty much dead meat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:44:08 </td>
   <td style="text-align:left;"> $SPY  There you have it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:43:47 </td>
   <td style="text-align:left;"> $SPY bill ackman </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:43:14 </td>
   <td style="text-align:left;"> $SPY Does BoJ post or update everyday how many $$ it bought on daily basis and projected buying as well?? @sonicmerlin  because this thing doesn’t seem like stops anytime soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:43:08 </td>
   <td style="text-align:left;"> $SPY going up from here $TSLA  beat earning 🍾🍾🍾🍾.  Tomorrow we rip!!! 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:42:57 </td>
   <td style="text-align:left;"> $SPY limited down tomorrow morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:42:52 </td>
   <td style="text-align:left;"> $SPY max pain has changed from 447 to 445 for fridays expiration.

Max pain was set for 443 todays expiration and moved to 440 intraday.

Will most likely move lower tomorrow. I feel good about a 445 area close for the week depending on tomorrows volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:42:29 </td>
   <td style="text-align:left;"> $SPY $TWTR $DWAC  
 
 
Ever notice IiberaIs want you to wear a mask and if you say no they want you to die from covid? 
 
How does someone rationalize with this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:42:09 </td>
   <td style="text-align:left;"> $SPY Spy sucks now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:42:00 </td>
   <td style="text-align:left;"> $SPY $415 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:41:00 </td>
   <td style="text-align:left;"> $SPY 

A proud moment for the TWOWS family!
$5k turned $650k in my Small Account Challenge discord!❤️❤️❤️
All trades verified!✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:40:20 </td>
   <td style="text-align:left;"> $SPY Bears are progressive liberals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:40:02 </td>
   <td style="text-align:left;"> $SPY 440 on deck as Fear returns tomorrow. FED needs to sell 85 billions in bills and tips. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:39:59 </td>
   <td style="text-align:left;"> $SPY $TSLA https://www.cnbc.com/2022/04/20/elon-musk-inflation-worse-than-reported-likely-to-last-through-2022.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:39:30 </td>
   <td style="text-align:left;"> $SPY $400 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:39:29 </td>
   <td style="text-align:left;"> $SPY $DWAC $TWTR  
 
 
IiberaI - Everyone shouId wear 2 masks Biden said so! 
Me - Biden doesn&amp;#39;t have the right to force me to wear a mask 
IiberaI - You are an idiot wear a mask! 
Me - No thank you, The constitution says I don&amp;#39;t have to 
IiberaI but doctors said to wear it! 
Me - No thanks! 
IiberaI - I hope you die from covid idiot! 
 
Where to start with this converstation? 
 
First,  doctors nor the president has he right to override the constitution 
 
Second, Why does a conversation with a IiberaI aIways end with them wishing me to die yet they want me to wear a mask </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:39:10 </td>
   <td style="text-align:left;"> $SPY This time last night permabears were dancing about futures market. It’s permabulls turn this night about futures. Anyway, futures or AH price don’t matter until cash market opens. $TSLA permabulls will be surprised tomorrow when red take over $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:39:08 </td>
   <td style="text-align:left;"> $SPY why Biden is shaking hands with thin air? Is it part of save environment and green crap? You have to shake hands and talk and smile at nobody? 
I love that concept.  Have you seen it? It’s hilarious but be serious. Cmon.  2024 .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:37:50 </td>
   <td style="text-align:left;"> $SPY looking for a sugar mama ! Anyone out there?!?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:37:28 </td>
   <td style="text-align:left;"> $SPY I had a short waiting at 27500, just got filled. I kinda need a nap though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:36:53 </td>
   <td style="text-align:left;"> $SPY bouncing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:36:51 </td>
   <td style="text-align:left;"> $SPY 🖖🏽🧑🏽‍🚀💨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:36:32 </td>
   <td style="text-align:left;"> $SPY rug pull when you wake up, futures will be red 2% Fed day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:35:59 </td>
   <td style="text-align:left;"> $SPY cancel my subscription </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:35:24 </td>
   <td style="text-align:left;"> $SPY i&amp;#39;m riiiiiidin with Biden!!!!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:35:18 </td>
   <td style="text-align:left;"> $SPY COST now looks like CSCO at its peak in 2000....LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:35:18 </td>
   <td style="text-align:left;"> $spy i don’t want to watch a pre staged movie.  What’s the fun in that?  Life is exciting because it’s random, it ebbs and flows unexpectedly.  Some old corrupt geezer’s idea of “stability” meanwhile is disgustingly stale and boring </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:35:13 </td>
   <td style="text-align:left;"> $SPY 🤣🤣🤣🤣https://www.cbsnews.com/news/cdc-appeal-mask-mandate-end-justice-department/?dc_data=4165335_samsung-carnival-us-att&amp;amp;utm_source=taboola&amp;amp;utm_medium=taboola_news&amp;amp;ui=ed426ec488020edac8bdb3bd44b706da2a3920ecf577c53606743343161dfee7#app </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:35:03 </td>
   <td style="text-align:left;"> $SPY $QQQ market has gotten overly-bearish. earnings have been strong and unwavering during an uncertain quarter that was supposed to be weak. it has not been that way so far $MSFT $NFLX $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:34:48 </td>
   <td style="text-align:left;"> $SPY 

Bear cub so broke didn’t even hit the 3k tax loss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:34:45 </td>
   <td style="text-align:left;"> $SPY 

There are basically 4 big holdouts left in need of a deeper correction to 100wk MAs:

AAPL
MSFT
GOOG
NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:34:41 </td>
   <td style="text-align:left;"> $qqq $SPY the US is a mess, I’d definitely make a better president than a guy who can’t walk up stairs, shakes hand w ghosts, and gets interrupted by a Easter bunny so he doesn’t say anything retarded. What kind of world do we live in fr 😂😂 now these losers are trying to appeal the mask mandate like fuck outta here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:34:23 </td>
   <td style="text-align:left;"> $SPY another awesome example of the power Linear Regression Channels. SPY 1min, 200 period linreg channel w/ 50 period linreg as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:34:05 </td>
   <td style="text-align:left;"> $SPY $QQQ upside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:32:57 </td>
   <td style="text-align:left;"> $SPY I think most ppl can’t understand how depressing it is for someone who trades on instinct to watch a giant foreign entity step in and inject money for their personal gain, interrupting the flow of the market.  Market has waves of momentum, and someone randomly dumps bajillions of dollars into it to halt that momentum. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:32:13 </td>
   <td style="text-align:left;"> $SPY https://www.bitchute.com/video/Uw81Cnp72RAI/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:31:44 </td>
   <td style="text-align:left;"> $SPY 

Consistent gains is what I strive for!
Will take accidental home runs but consistency is the key! 🔥🔥🔥
All trades verified in my Small Account Challenge discord!✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:31:39 </td>
   <td style="text-align:left;"> $SPY wanted to show this chart for how well it demonstrates the use of Linear Regression Channels. SPY 1min, 50 period lin reg. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:31:38 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:31:29 </td>
   <td style="text-align:left;"> $NFLX Netflix doesn&amp;#39;t have subscriber loss problem, they have paying vs unpaying subscriber problem.  The -200k subscriber loss came from paying subscribers, but unpaying subscribers have grown by the millions.  Turn those unpaying subscribers into ad-supported platform and Netflix suddenly has 210 million paying + 100 million *NEW* ad-supported paying subscribers for a total of 310 million.   Now, THAT&amp;#39;s GROWTH.      
 
Hey Bill, you messed up with your math.   $DIS $AMZN $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:31:20 </td>
   <td style="text-align:left;"> $SPY Cathie again day trading averaging looser and selling winner $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:30:11 </td>
   <td style="text-align:left;"> $SPY $NFLX Bill Ackman? More like Bill Assman! IYKYK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:30:06 </td>
   <td style="text-align:left;"> $SPY ppl keep telling me a bunch of small caps are getting wrecked then why is the Russell doing so well? Meanwhile high yield bonds barely barely bouncing and yet iwm was up big </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:30:04 </td>
   <td style="text-align:left;"> $SPY good close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:29:54 </td>
   <td style="text-align:left;"> $SPY where my bears 🐻 at </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:29:30 </td>
   <td style="text-align:left;"> $SPY $QQQ  Was watching QQQ and SPY yesterday, tracking the same, bought QQQ calls by mistake, QQQ tanks, SPY holds.  Just my luck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:29:08 </td>
   <td style="text-align:left;"> $SPY if Tesla has a back lot of cars to deliver, how can there be a recession or stock market crashing? There’s a lot of demand for goods. Lots of things sold out. Economy is booming. Am I $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:28:52 </td>
   <td style="text-align:left;"> $SPY $TWTR $DJIA OH GOD ! This is scary and fuked up ! First they remove God from school next They go full pedo - AND NOW THIS 😳🤬👎🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:28:33 </td>
   <td style="text-align:left;"> $SPY 

Most bear cub made less than minimum wage trying to trade 

Sad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:28:28 </td>
   <td style="text-align:left;"> $ES_F $SPY  let&amp;#39;s give it 2 more hours before bears get raped from the front </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:27:51 </td>
   <td style="text-align:left;"> $SPY if you bought netlfix right now, when you&amp;#39;re looking at 2025 it will be the biggest gainer of all large cap stocks. Its a long term buy and hold. A reliable winner that has massive potential upsides, that they will release effectively $NFLX $AMD $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:27:39 </td>
   <td style="text-align:left;"> $NFLX When is Hastings going to learn to present earnings materials CORRECTLY?   If subscribers are sharing their accounts, he could&amp;#39;ve easily spun that off as &amp;quot;we have 221 million paying subscribers and we grew 100 million *NEW* unpaying subscribers. &amp;quot;  How difficult is that to say?   $SPY $DIS $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:27:07 </td>
   <td style="text-align:left;"> $SPY the knockout is coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:27:01 </td>
   <td style="text-align:left;"> $SPY #ArmUkraineNow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:26:30 </td>
   <td style="text-align:left;"> $spy example of a foreign market.  Giant dump then nonstop grindup for 2 days.  They just refuse to stop printing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:26:24 </td>
   <td style="text-align:left;"> $SPY idk fellas should I take a long here tonight or naw I feel a little fomo and almost positive we&amp;#39;re going up tonight 🤔 but I also don&amp;#39;t really like it here all that much but ots still not too bad just for a overnight scalp  or do I just wait for something better 
I&amp;#39;m fighting that fomo feeling now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:25:56 </td>
   <td style="text-align:left;"> $SPY well, I feel better about my day now....   https://www.bloomberg.com/news/articles/2022-04-20/ackman-loses-more-than-430-million-on-three-month-netflix-bet?srnd=premium </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:25:16 </td>
   <td style="text-align:left;"> $SPY The market just transferred $40 billion from Netflix to Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:25:08 </td>
   <td style="text-align:left;"> $SPY Going to be green tomorrow because of TSLA just like how it was down today because of NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:24:37 </td>
   <td style="text-align:left;"> $NFLX buy it back up to 300 in a week $SPY $FB $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:23:49 </td>
   <td style="text-align:left;"> $SPY How does anyone not realize the masks are useless by now?  How are people mentally retarded enough to desire masks?  You see all the people who don’t use them continuously and they’re fine for years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:23:28 </td>
   <td style="text-align:left;"> $SPY just updated the app and now I want to break my phone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:23:14 </td>
   <td style="text-align:left;"> $SPY nasdaq should move up 1,000 points </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:22:55 </td>
   <td style="text-align:left;"> $SPY netflix has perfected pricing, gonna have good additions the next quarters. don&amp;#39;t be so hyper focused quarter to quarter subscriber fluctuations $NFLX $SPOT $FB $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:22:51 </td>
   <td style="text-align:left;"> $SPY Small caps getting destroyed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:22:33 </td>
   <td style="text-align:left;"> $DWAC $SPY   FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:21:47 </td>
   <td style="text-align:left;"> $SPY hey everyone! You can now lose on crypto through Stocktwits! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:21:27 </td>
   <td style="text-align:left;"> $TSLA trading range for this quarter should be $1000-$1500 stock much cheaper now on a P/e ratio basis $QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:21:23 </td>
   <td style="text-align:left;"> $SPY $SPX I don&amp;#39;t usually say much about futures and I guess it&amp;#39;s $TSLA driven but tonight there ripping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:21:18 </td>
   <td style="text-align:left;"> $SPY Always get the cream of the crop....at the top....on these boards.....LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:20:48 </td>
   <td style="text-align:left;"> $CVE: Expecting an explosive move out of this one. 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:20:42 </td>
   <td style="text-align:left;"> $SPY Might actually close the week strong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:20:26 </td>
   <td style="text-align:left;"> $SPY well anyway it might be easier to wait a couple of weeks for QT to start, assuming powell didn’t lie about that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:20:02 </td>
   <td style="text-align:left;"> $SPY $QQQ Bill Ackman Dumps Entire Netflix Stake, Loses $430 Million In 4 Months

Are he and Auntie Cathie secretly dating? Lolllll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:19:31 </td>
   <td style="text-align:left;"> $SPY imagine thinking spy is in a bear market... fucking idiots 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:19:25 </td>
   <td style="text-align:left;"> $SPY US Capitol issued alert: &amp;quot;Evacuate now: aircraft intrusion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:19:20 </td>
   <td style="text-align:left;"> Futures slowly higher $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:19:12 </td>
   <td style="text-align:left;"> $SPY I’m expecting a 10 to 15 point ES injection pump soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:18:15 </td>
   <td style="text-align:left;"> $HTZ: Breaking out on the daily. Nice call flow for 25 and 30 calls 5/20 exp. Watch for retest of 23.9 level for entry or a break above today&amp;#39;s high (24.29). 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:17:04 </td>
   <td style="text-align:left;"> $SPY Think of how much fuking money these people spend on defense and they can&amp;#39;t even tell it&amp;#39;s people parachuting in for a baseball game miles away what a farce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:16:44 </td>
   <td style="text-align:left;"> $NVAX $CVNA $SPY 

These two are poster children for selling their investors on dreams of grandeur and serving up a cow pie sandwich. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:16:32 </td>
   <td style="text-align:left;"> $SPY 460 calls printing tomorrow 

🙂👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:15:34 </td>
   <td style="text-align:left;"> $SPY short squeeze will happen tomorrow - eagerly waiting for 450 calls to print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:15:33 </td>
   <td style="text-align:left;"> $SPY ES +50 gang? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:15:30 </td>
   <td style="text-align:left;"> $SPY sonic stop saving China with your paper account we&amp;#39;re either doing this or not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:15:21 </td>
   <td style="text-align:left;"> $SPY Man i’m just sitting here… licking my 🧸paws🍯…waiting for this POS to come down. 🥱🥱🥱i’m almost ready to attack a bool. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:14:23 </td>
   <td style="text-align:left;"> $SPY $TWTR $DJIA LMFAO 🤣 she didn’t like the answers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:14:22 </td>
   <td style="text-align:left;"> $SPY $tsla just saved tech stocks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:14:22 </td>
   <td style="text-align:left;"> $SPY pump it to 447 one more time this week. Please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:14:21 </td>
   <td style="text-align:left;"> $ES_F: The saying goes, &amp;quot;Never short a dull market.&amp;quot; All we did today was consolidate yesterday&amp;#39;s gains. As long as we continue to hold 4445, we should see 4490 and then 4507 (100 sma) this week. Under 4445, we will most likely retest 4410 level.  
$SPY $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:14:13 </td>
   <td style="text-align:left;"> $SPY finally we will get a limit up day tomorrow - have been waiting for so long - 453 here we come 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:14:04 </td>
   <td style="text-align:left;"> $SPY $QQQ  Sell all Tech stocks because the economy is going down ie: inflation, supply chain …But buy $TSLA stock because the economy is so good everyone is buying a $50 thousand to $100 thousand dollar car </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:13:22 </td>
   <td style="text-align:left;"> $SPY I don’t feel like trading tonight.  Technically the momentum is bearish but I know they’re just gonna inject money at some point so who cares why bother </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:13:02 </td>
   <td style="text-align:left;"> $SPY Please pump a bit longer, I&amp;#39;m trying to sell my 401k 😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:12:02 </td>
   <td style="text-align:left;"> $SPY travel.booming! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:11:36 </td>
   <td style="text-align:left;"> $SPY Biden fighting those masks. Need them ON YOU. NEED CONTROL! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:11:17 </td>
   <td style="text-align:left;"> $SPY told y’all about the travel stocks tho. Shits are hot hot. Perfect place to go if tech is down. What else is everyone going to do? $UAL $DAL $RCL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:11:07 </td>
   <td style="text-align:left;"> $SPY Just checking in on this Terd 😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:10:49 </td>
   <td style="text-align:left;"> $SPY stock analysis based on today&amp;#39;s closing price 

https://youtu.be/oLAxmUUGjJU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:10:33 </td>
   <td style="text-align:left;"> $SPY 

Tellin’ ya folks! Charts dont lie to me! 
When you start understanding these breakouts &amp;amp; reversals, you will start understanding my trades &amp;amp; why I took them. 
Its extremely simple yet the most powerful strategy in day trading! Nailed it in my Small Account Challenge discord today!🔥🔥🔥
All trades verified!✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:10:27 </td>
   <td style="text-align:left;"> $SPY could see limit oop

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:09:31 </td>
   <td style="text-align:left;"> $TSLA $TWTR $DWAC $SPY 
If you need any more proof this market is a clown show, literal joke, look no further! 
 
this post was a joke but we all know what went down shortly after… priceless 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:08:39 </td>
   <td style="text-align:left;"> $SPY $DWAC $TWTR $TSLA  
If you haven&amp;#39;t watched this you must 
 
Your Iife depends on it 
 
https://www.youtube.com/watch?v=rVdjjaPqWIE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:08:21 </td>
   <td style="text-align:left;"> $SPY $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:08:21 </td>
   <td style="text-align:left;"> $SPY the banks never saw a support they didn’t like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:08:13 </td>
   <td style="text-align:left;"> Can you believe this rslly. 
 
CAN YOU BELIEVE THIS RSLLY  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:07:34 </td>
   <td style="text-align:left;"> $SPY no sellers hey lol 😆 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:07:12 </td>
   <td style="text-align:left;"> $SPY Binging GOT. This was much needed after today 😶‍🌫️🌳🍪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:06:49 </td>
   <td style="text-align:left;"> $SPY today was such a beautiful chart. Within minutes of open we knew what the top and bottom would be. Options gift from heaven. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:06:35 </td>
   <td style="text-align:left;"> $NFLX I give credit to Ackman for not holding on to losers like Cathie.  $ARKK is a collection of losers.  $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:06:00 </td>
   <td style="text-align:left;"> $SPY give me this scenario ole crap pants. PLEASE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:05:10 </td>
   <td style="text-align:left;"> $SPY tomorrow setting up to be a perfect sell the news day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:04:54 </td>
   <td style="text-align:left;"> $SPY  how many of you still have $420 Puts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:04:44 </td>
   <td style="text-align:left;"> $SPY right now it seems like the banks are trying very hard to orchestrate a rally.  It seems like there’s no one to stop them even if it causes dire inflationary consequences </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:04:39 </td>
   <td style="text-align:left;"> $SPY $DWAC 
 AYE do y&amp;#39;all stock twits  Republicans actually agree with Republican monetary policies? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:04:31 </td>
   <td style="text-align:left;"> $SPY Groom them bulls , sharpen them horns, we about to go on a rampage!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:04:24 </td>
   <td style="text-align:left;"> $spy can we break out of downtrend?  Only the algos know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:03:35 </td>
   <td style="text-align:left;"> $SPY why the fuck is this board jumping at 8pm on Wednesday wtf is going on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:03:28 </td>
   <td style="text-align:left;"> $TSLA 7-8% move tomorrow? ☕️🐸

$SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:03:13 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:02:42 </td>
   <td style="text-align:left;"> $SPY short any rally tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:02:13 </td>
   <td style="text-align:left;"> $SPY  $4380    Over-night  🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:02:00 </td>
   <td style="text-align:left;"> $SPY $460 coming next week? 😱😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:01:49 </td>
   <td style="text-align:left;"> $SPY netflix going under 100. Streaming is dead becuase content is dead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:01:32 </td>
   <td style="text-align:left;"> $TSLA $SPY 

Tesla saved the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:01:00 </td>
   <td style="text-align:left;"> $SPY let the bulls kill each other 

That will be the best part of this trip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 08:00:06 </td>
   <td style="text-align:left;"> $SPY because so many are waiting and wanting the crash they are stopping it from happening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:59:47 </td>
   <td style="text-align:left;"> $SPY cup and handle break down

Don’t try to fight this Fed 

Your girl tomorrow when she opens here account. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:59:42 </td>
   <td style="text-align:left;"> $SPY 450 calls tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:59:38 </td>
   <td style="text-align:left;"> $NFLX Buffet sold $AAL and $WFC at the bottom.  So did Ackman with $NFLX.  Fund managers make mistakes all the time.  Bill just didn&amp;#39;t have enough shares to play activist games with Netflix, so he gave in and sold for loss.  Other fund managers looking at this going.. great price to buy here at 2018 price!  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:59:37 </td>
   <td style="text-align:left;"> $SPY big green dildos coming soon compliments of a short squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:59:31 </td>
   <td style="text-align:left;"> $SPY Johnny Deep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:59:27 </td>
   <td style="text-align:left;"> $SPY Feedback loops create consciousness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:58:55 </td>
   <td style="text-align:left;"> $SPY 

Asssssss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:58:48 </td>
   <td style="text-align:left;"> $AAL $UAL $SPY $TSLA a lot of fear is going away. Expecting a big green candle tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:58:36 </td>
   <td style="text-align:left;"> $SPY Johnny depp will crash the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:58:28 </td>
   <td style="text-align:left;"> $SPY imagine a world where the only 2 things that matter in the market is price action and volume.  where the news, media and ST comments were just white noise.  wouldnt that be so easy to trade?!  its be almost criminal….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:57:47 </td>
   <td style="text-align:left;"> $SPY why is J Pow speaking tmr 😭. Twice!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:57:44 </td>
   <td style="text-align:left;"> $SPY it’s probably impossible for this to go down with the way they’ve been injecting money into futures, like this morning.  I guess we’ll see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:57:32 </td>
   <td style="text-align:left;"> $SPY $QQQ inverse HnS on multiple time frames. Spy dragged down by QQQ today. A tech comeback tomorrow will push spy over 450 then 453 test by Friday. If we don’t get over todays high tomorrow, Spy is digging even lower. I don’t see that happening with April being a bullish month. I’m ready to print some calls. Powell don’t fk it up!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:57:32 </td>
   <td style="text-align:left;"> $SPY Wipe me down, soon as the light hit you can’t lie the ice sick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:57:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $XLE $XLU $TQQQ 

Utilities and Energy will drop nicely and tech will lead this market higher.

You heard it here first, mofos! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:56:56 </td>
   <td style="text-align:left;"> $SPY look at this chart. What a beauty. Make money both ways all day long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:56:33 </td>
   <td style="text-align:left;"> $SPY anyone trade the spy on a tick chart ? If so how many ticks ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:56:30 </td>
   <td style="text-align:left;"> $SPY never crashes when I run my script, just traps me in puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:56:24 </td>
   <td style="text-align:left;"> $SQQQ “40 or bust” still in full effect… $QQQ $SPY $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:56:22 </td>
   <td style="text-align:left;"> $SPY This whole “recession is looming” talk seems like shitposting from the fed. I’m convinced they will keep using QE indefinitely. Rules have been bent to fit what they want </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:56:12 </td>
   <td style="text-align:left;"> $SPY I see it a bit cleaner with the lines </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:55:51 </td>
   <td style="text-align:left;"> $SPY thats what bill azzmann gets for ruining chipotle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:55:37 </td>
   <td style="text-align:left;"> $SPY Jeyromy talks at 10am i think </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:55:29 </td>
   <td style="text-align:left;"> $TSLA Yup, less than 1% daily move when all said and done,  we&amp;#39;ll get back to our regularly scheduled Tesla programming tomorrow, &amp;quot;Crash.&amp;quot; 

$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:55:27 </td>
   <td style="text-align:left;"> $SPY &amp;quot;But I am in a game that you don’t need — you probably need 120 points of IQ. But 170 doesn’t do any better than 120. It may do worse — probably do worse. But you don’t really need brains.”

- Warren Buffet. 😄 And bears lose constantly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:55:25 </td>
   <td style="text-align:left;"> $QQQ $SPY Going remain here or dip slightly in fear of Powell speech, and then rip, like it’s done everytime for the last month, what am I missing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:54:42 </td>
   <td style="text-align:left;"> $SPY so TSLA&amp;#39;s fuzzy math warrant a big AH pump for the markets? Right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:54:25 </td>
   <td style="text-align:left;"> $SPY keep murdering big tech every day. Sell sell sell! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-21 07:53:59 </td>
   <td style="text-align:left;"> $SPY what time does Jerome talk tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:35:09 </td>
   <td style="text-align:left;"> New Analysis: Why Wednesday’s price action was bullish, plus what the next 12 months in $NFLX will look like: https://cracked.market/2022/04/why-wednesdays-price-action-was-bullish-plus-what-the-next-12-months-in-nflx-will-look-like/ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:34:45 </td>
   <td style="text-align:left;"> $QQQ #QQQ  Just saying...Bullish price action does not look like this.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:33:49 </td>
   <td style="text-align:left;"> $SPY $QQQ how we gonna react to Powell tomorrow? Any predicitions? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:33:23 </td>
   <td style="text-align:left;"> $SPY Cramer already give out another stocks he his bullish on. I really like his due diligence 🤣🤣🤣🤣 Anyway, I’m making banks tomorrow/Friday, God’s willing $QQQ 

🤐 🤐🤐🤐🤐🤐🤐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:33:11 </td>
   <td style="text-align:left;"> $QQQ Netflix has gone woke and now is going broke (kinda reminds of the last movie venue that turned their back on their customers...a former company that used to be called Blockbuster... didn&amp;#39;t invest in the QQQs for that sort of nonsense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:28:22 </td>
   <td style="text-align:left;"> $NFLX
Transgender population is almost hitting 5,71 Billion this year. Netflix has definitely seized this opportunity.

$SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:26:58 </td>
   <td style="text-align:left;"> 🚨WE ARE NOW LIVE🚨 
🔥GAINZ STREAMZ TRADE IDEAS🔥 
IM GOING TO BREAKDOWN 👇 
📈TRADE IDEAS 
🔫TRIGGERS 
🎯TARGETS 
CLICK&amp;gt;https://us02web.zoom.us/j/86761922065 $SPY  $AMC  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:26:13 </td>
   <td style="text-align:left;"> $QQQ This market is nuts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:24:58 </td>
   <td style="text-align:left;"> $QQQ what a joke lol 
Trillion in buybacks dividends 
Market is confused </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:17:56 </td>
   <td style="text-align:left;"> $SPY $SPX500 $QQQ Here&amp;#39;s a weekly trend channel chart of SPX500 with a couple of scenario&amp;#39;s and key activity levels for the next 6-12 months.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:15:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $ETH.X This is what Elon had to say about the &amp;#39;woke&amp;#39; Left, and I agree with him one-hundred! 
 
“Generally, I think we should be aiming for a positive society and it should be okay to be humorous. Wokeness basically wants to make comedy illegal which is not cool. 
 
&amp;quot;At its heart wokeness is divisive, exclusionary and hateful. It basically gives mean people a shield to be cruel, armored in false virtue.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:14:54 </td>
   <td style="text-align:left;"> $SPY . $NDX . $NASDAQ . $QQQ 

Russia Putin Threatens The West Directly right now. 

Firing off a test Intercontinental ballistic missile. 

Breaking news 📰 CNN.    …  …. …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:14:29 </td>
   <td style="text-align:left;"> $SPY . $NDX . $NASDAQ . $QQQ 

Russia Putin Threatens The West Directly right now. 

Firing off a test Intercontinental ballistic missile. 

Breaking news 📰 CNN. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:13:41 </td>
   <td style="text-align:left;"> $QQQ - Putin is testing intercontinental ballistic missiles 
Biden doesn’t know which end is up 
Inflation is out of control
Billions of dollars are heading  out of the stock market and into the bond market
Powell is raising rates at an  unprecedented rate and wants the stock market down to help elevate further inflation 
And retail is still all in🤫😳🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:11:57 </td>
   <td style="text-align:left;"> $PLTR https://www.reddit.com/r/PLTR/comments/u7uid2/new_us_government_contract_to_support_the_faa/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf $QQQ $VZ $T $TMUS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:11:27 </td>
   <td style="text-align:left;"> $PLTR FAA 5G rollout contract $QQQ $VZ $T $TMUS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:11:13 </td>
   <td style="text-align:left;"> $QQQ considering the market hasn&amp;#39;t crashed yet $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:11:09 </td>
   <td style="text-align:left;"> Reducing Inequality, Hiking Minimum Wage Could Boost U.S. Economy: White House

https://amp.insurancejournal.com/news/national/2022/04/20/663466.htm

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:11:05 </td>
   <td style="text-align:left;"> $SPY end of war is near boys!! then we are back on track for a girthy 2022 $IWM $QQQ $NFLX $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:11:03 </td>
   <td style="text-align:left;"> $ES_F .. $QQQ .. $DIA .. $SPX mm

Russia Test Launches Missile  intercontinental ballistic Putin Issues Warning ⛔️ To The “WEST”.  

Breaking news 📰 CNN International. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:07:21 </td>
   <td style="text-align:left;"> $SPY $TSLA  Tesla we played it well today. Puts printed. All cash EOD watching for fresh entries tomorrow $QQQ $SHOP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:06:50 </td>
   <td style="text-align:left;"> $QQQ Apr 20               
Sell               
◆ Search for 10 day stock forecast by pretiming A.I               
http://www.google.com/search?q=10+day+stock+forecast               
◆ Forecast of Upper~Lower price range band for the next 10 days               
Price: 321.30   ~ 341.21            
% Change: -5.84%  ~ 0.00%           
The Buy-Sell strength is suitable for the current trend and it&amp;#39;s about to begin a downward trend as a rebounding trend gradually gives way to increasing limited rises and strong falls in the falling section. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:05:29 </td>
   <td style="text-align:left;"> $SPY $QQQ fintwit is going crazy for this chart, but my hot take is that where we’re at in this cycle is the green arrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:04:41 </td>
   <td style="text-align:left;"> $SPY Another $15B printing spotted by Powell printer again. Don’t worry, powell is fighting inflation by printing more money 💰 $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:03:22 </td>
   <td style="text-align:left;"> $SPY $QQQ AT 9:45AM, BIDEN WILL GIVE AN UPDATE ON THE SITUATION IN UKRAINE AND RUSSIA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 09:03:17 </td>
   <td style="text-align:left;"> $SPY Anyone else get the idea that Powell sees the unenthusiasm and virtually boring stock market &amp;amp; just finally tells it to Wall Street straight that inflation is going to go nuts if we don&amp;#39;t high consider a 0.75% hike like Bullard just stated he wanted to do &amp;amp; then we need to really reduce the balance sheet in May, rapidly, like Lael wants to do.

Anyone else think Powell just goes ultra-aggressive suddenly because he realizes that&amp;#39;s the proper QE toolbox move &amp;amp; &amp;quot;maybe I shouldn&amp;#39;t say this but I&amp;#39;ve been influenced by Biden &amp;amp; other members to vote unlike I really should so economy not crash &amp;amp; cause recession quickly but maybe it&amp;#39;s what we need now to restart growth. Pain now, gain later. Otherwise, I don&amp;#39;t do it, we could see 17% real inflation &amp;amp; 12-14% CPI jump by the 4th (of July).&amp;quot; 

Wouldn&amp;#39;t that be some kind of rabbit pulled out of the hat, bulls? 

Baboooom $TSLA $QQQ $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:58:07 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F  going back to $4360 overnight. 

Goodnight 💤 it’s been a long choppy day 

 . $QQQ                                                         $DJIA  🧞‍♂️. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:57:53 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Market so fked up I&amp;#39;ll take my crack pipe now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:57:15 </td>
   <td style="text-align:left;"> God save the QQQueen

$QQQ $NQ_F $NDAQ $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:55:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  * posted this China manufacturing warning April 01 when China contracted 1st time in 2 years since Covid started.   
 
now the GDP  forecast drop..  another big caution.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:54:41 </td>
   <td style="text-align:left;"> $QQQ When you forget to close your QQQ puts and Tesla crushes…🤦‍♂️🤦‍♂️🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:52:01 </td>
   <td style="text-align:left;"> $SQQQ  $QQQ  $TQQQ   
if you are short you are early but eventually you&amp;#39;ll be right. 
if you are long you got balls. 
https://www.tradingview.com/x/cbbrDLSP/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:52:01 </td>
   <td style="text-align:left;"> $QQQ went heavy short at 7:59 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:50:04 </td>
   <td style="text-align:left;"> $QQQ Powell is speaking which keeps the Q’s in a tight trading range 

Powell wants the stock market to give up 20% in gains along with 3- 50 bp rate hikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:49:52 </td>
   <td style="text-align:left;"> $QQQ 375+ next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:48:17 </td>
   <td style="text-align:left;"> $NFLX open up below $100.   $QQQ $SPY 

 . $DIA                                                     $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:47:22 </td>
   <td style="text-align:left;"> $QQQ We gapping up after TSLA huge er beat tomorrow on indexes especially Qs and SPY
Target here @350plus that closes the gap left above on the weekly chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:45:57 </td>
   <td style="text-align:left;"> $SPY $3800.      $SPX $ES_F $QQQ $NDX 

Tech.nical    Breaks down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:45:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA Huge squeeze incoming tomorrow? Bigly bull gains to be made, poor shorts/bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:45:11 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY green futures likely red by morning just like deep red yesterday was green by open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:44:32 </td>
   <td style="text-align:left;"> $QQQ NLFX dip to TSLA rip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:42:41 </td>
   <td style="text-align:left;"> $NFLX $QQQ Netflix is selling off because in the earnings call leadership sounded clueless and confused. They had no answers and just kept saying we didn&amp;#39;t anticipate we don&amp;#39;t know and tons of competition. They&amp;#39;re looking like Blockbuster real fast!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:39:10 </td>
   <td style="text-align:left;"> $SPY This time last night permabears were dancing about futures market. It’s permabulls turn this night about futures. Anyway, futures or AH price don’t matter until cash market opens. $TSLA permabulls will be surprised tomorrow when red take over $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:37:28 </td>
   <td style="text-align:left;"> $QQQ ouch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:35:03 </td>
   <td style="text-align:left;"> $SPY $QQQ market has gotten overly-bearish. earnings have been strong and unwavering during an uncertain quarter that was supposed to be weak. it has not been that way so far $MSFT $NFLX $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:34:41 </td>
   <td style="text-align:left;"> $qqq $SPY the US is a mess, I’d definitely make a better president than a guy who can’t walk up stairs, shakes hand w ghosts, and gets interrupted by a Easter bunny so he doesn’t say anything retarded. What kind of world do we live in fr 😂😂 now these losers are trying to appeal the mask mandate like fuck outta here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:34:08 </td>
   <td style="text-align:left;"> $QQQ Tommorrow Powell speaks. Nothing else to know or think about. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:34:05 </td>
   <td style="text-align:left;"> $SPY $QQQ upside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:32:08 </td>
   <td style="text-align:left;"> $QQQ https://rumble.com/v11pdkz-4.20.22-full-panic-hits-the-enemy-elections-masks-spies-jabs-cancer-coming-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:30:46 </td>
   <td style="text-align:left;"> $TSLA  Earnings Release after hours trading. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:29:30 </td>
   <td style="text-align:left;"> $SPY $QQQ  Was watching QQQ and SPY yesterday, tracking the same, bought QQQ calls by mistake, QQQ tanks, SPY holds.  Just my luck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:29:08 </td>
   <td style="text-align:left;"> $SPY if Tesla has a back lot of cars to deliver, how can there be a recession or stock market crashing? There’s a lot of demand for goods. Lots of things sold out. Economy is booming. Am I $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:27:51 </td>
   <td style="text-align:left;"> $SPY if you bought netlfix right now, when you&amp;#39;re looking at 2025 it will be the biggest gainer of all large cap stocks. Its a long term buy and hold. A reliable winner that has massive potential upsides, that they will release effectively $NFLX $AMD $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:23:48 </td>
   <td style="text-align:left;"> $QQQ futures are a mother fing liar, another 1% down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:21:27 </td>
   <td style="text-align:left;"> $TSLA trading range for this quarter should be $1000-$1500 stock much cheaper now on a P/e ratio basis $QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:20:02 </td>
   <td style="text-align:left;"> $SPY $QQQ Bill Ackman Dumps Entire Netflix Stake, Loses $430 Million In 4 Months

Are he and Auntie Cathie secretly dating? Lolllll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:17:56 </td>
   <td style="text-align:left;"> $QQQ cautiously optimistic for reversal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:14:04 </td>
   <td style="text-align:left;"> $SPY $QQQ  Sell all Tech stocks because the economy is going down ie: inflation, supply chain …But buy $TSLA stock because the economy is so good everyone is buying a $50 thousand to $100 thousand dollar car </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:11:07 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/QfEjjAQW-6U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:08:23 </td>
   <td style="text-align:left;"> $QQQ Tesla is ominous.  
 
Fantastic report. Barely got back to its opening price of the day. The market is not in the mood at the moment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:08:13 </td>
   <td style="text-align:left;"> Can you believe this rslly. 
 
CAN YOU BELIEVE THIS RSLLY  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:03:28 </td>
   <td style="text-align:left;"> $TSLA 7-8% move tomorrow? ☕️🐸

$SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 08:03:19 </td>
   <td style="text-align:left;"> $QQQ the Dow is so overbought, there are some really good growth stocks down 60-80% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:59:30 </td>
   <td style="text-align:left;"> $QQQ Kamala found root cause of this bear market, its JOE BIDEN, lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:58:36 </td>
   <td style="text-align:left;"> $AAPL 100 price target look at Chinese stocks $BABA $BIDU $TENCENT , apple is about to crash it trades with China …. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:57:32 </td>
   <td style="text-align:left;"> $SPY $QQQ inverse HnS on multiple time frames. Spy dragged down by QQQ today. A tech comeback tomorrow will push spy over 450 then 453 test by Friday. If we don’t get over todays high tomorrow, Spy is digging even lower. I don’t see that happening with April being a bullish month. I’m ready to print some calls. Powell don’t fk it up!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:57:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $XLE $XLU $TQQQ 

Utilities and Energy will drop nicely and tech will lead this market higher.

You heard it here first, mofos! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:56:24 </td>
   <td style="text-align:left;"> $SQQQ “40 or bust” still in full effect… $QQQ $SPY $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:55:25 </td>
   <td style="text-align:left;"> $QQQ $SPY Going remain here or dip slightly in fear of Powell speech, and then rip, like it’s done everytime for the last month, what am I missing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:55:00 </td>
   <td style="text-align:left;"> $QQQ 1 step forward..3 steps back…this is the market and it Will continue to trend this way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:54:48 </td>
   <td style="text-align:left;"> $QQQ looks like a inverse head &amp;amp; shoulders on the daily. $338 first before we go higher. Looking for all this to complete tomorrow. Hopefully the gap fills too lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:52:15 </td>
   <td style="text-align:left;"> Ran across this tweet today about trading $SPX $SPY $QQQ $IWM    
  
Matt Petrallia, CMT - &amp;quot;If you don&amp;#39;t see people posting losses - or even acknowledging losses - you&amp;#39;re not seeing real trading. I have a 50% win rate. There&amp;#39;s no room for ego when you&amp;#39;re wrong half the time - it&amp;#39;s simple math. Winners need to be larger than your losers and losers must never be big.&amp;quot;   
  
Life/Trading Lesson = beware of PAPER tigers and fake FURU&amp;#39;s 
  
The REAL traders will have NO problem telling you their entries, exits, and holdings...IN REAL TIME or EOD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:52:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 72983400. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:50:32 </td>
   <td style="text-align:left;"> $QQQ tomarrow I&amp;#39;m expecting either a sell-off until the powell speech is over or maybe a small rally at the open followed by a selloff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:50:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $ND_F 

AAPL 
MSFT
FB
AMZN
GOOGL

er’s next week… 
tech rally has begun with TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:48:04 </td>
   <td style="text-align:left;"> $QQQ fake pump bear market rally mode is back on, riding with TQQQ again, let’s see how this fickle bitchs plays out. Looking for 50-51 zone to sell for quick 10% less gooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:47:08 </td>
   <td style="text-align:left;"> Bulls definitely have an edge as of now 
 
$SPY $QQQ $DIA $XLK $XLF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:46:33 </td>
   <td style="text-align:left;"> $SPY $QQQ  $AAPL  
 
 important spot here at cloud bottom support but closing under red white line with bearish cross..  risk of  linguini with clam sauce ...... med-high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:45:20 </td>
   <td style="text-align:left;"> S&amp;amp;P Sectors: Median mkt UP 
 
As expected, Strength continue to build around -23.6% retracement levels for median mkt. 
 
Bullishness: 50% 
 
Concerns: None. 
 
$SPY $QQQ $DIA $XLK $XLF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:39:38 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY $DIA $BTC.X

quit playin’ and get the dice rollin’ on the island reversal 🎲🏝📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:38:06 </td>
   <td style="text-align:left;"> $QQQ $SPY $NFLX $TSLA I think today marks the end of FAANG and the birth of FAAGT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:36:20 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
PAY YOUR RESPECTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:27:57 </td>
   <td style="text-align:left;"> $SPY $QQQ Small cap Chinese stocks aren&amp;#39;t good for portfolios </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:24:44 </td>
   <td style="text-align:left;"> $TSLA $QQQ $UVXY Down day tomorrow so headwinds will stabilize price in the 1050-1100 band in the near future. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:13:41 </td>
   <td style="text-align:left;"> over 75+ earning report tomorrow but I like $PINE = GL 
$SPY $QQQ $NASDAQ  
 
https://qr.ae/pGBmwP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:13:03 </td>
   <td style="text-align:left;"> $QQQ $320? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:12:19 </td>
   <td style="text-align:left;"> Stocks Drop On April 20 As Stay-At-home Names Get Crushed $DIS $QQQ $NFLX $SHOP $ARKK https://talkmarkets.com/content/stocks--equities/stocks-drop-on-april-20-as-stay-at-home-names-get-crushed?post=352213 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:11:40 </td>
   <td style="text-align:left;"> $TSLA $qqq this was a very solid quarter and guide, however, this will need market support and Q&amp;#39;s surging to make any difference rest of week (for weekly option buyers). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:10:44 </td>
   <td style="text-align:left;"> $QQQ pretty ugly candle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:09:57 </td>
   <td style="text-align:left;"> $QQQ is this thing going to fill the gap at 348 or just keep messing with us </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:04:45 </td>
   <td style="text-align:left;"> $QQQ I would like to see this fill that gap up above </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:03:25 </td>
   <td style="text-align:left;"> $SPY I sometimes wonder if we&amp;#39;ll look back at Elon &amp;amp; $tsla the way we did w/ Enron.  We all knew he was going to beat, he needs the cash now but its stating to be a little too convenient,  
 
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:02:49 </td>
   <td style="text-align:left;"> $QQQ Honestly this TSLA pump is looking weak. No matter how good earnings are market corrections for P/E, MC, and forward revenues are happening. Cost to borrow, inflation and Fed monetary policy will all eat most company&amp;#39;s bottom line and growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:02:11 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-04-20 Trade Analysis Video: 
https://www.youtube.com/watch?v=zq8hKheW5fg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 07:01:54 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX  BREAKING 🗞 
https://on.mktw.net/38bpjM8 Check out this article from MarketWatch - U.S. Capitol evacuated, citing ‘probable threat’ from aircraft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:55:38 </td>
   <td style="text-align:left;"> $TSLA  As of now Tesla is being held below previous channel resistance it needs to break out from...$QQQ $SPY $AAPL $UVXY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:48:44 </td>
   <td style="text-align:left;"> $QQQ tomorrow’s looking like 348 to 350… and 356 area could be the next potential battleground $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:46:12 </td>
   <td style="text-align:left;"> $SPY what did I say? NOVEMBER - DECEMBER pattern in full effect. As long as we hold above 4380 I am long with a few hedged puts. 

$QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:45:43 </td>
   <td style="text-align:left;"> $SHOP $SPY $QQQ  Already feeling really good about my shop calls. Adding end of day is how you do it kiddoes. Patience is how you play the market. Otherwise it eats you alive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:44:42 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
MM trying once again to move price higher in low volume overnight session. 
 
They too weak to move price higher in cash session. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:44:16 </td>
   <td style="text-align:left;"> $PYPL We do you buy under short term 
5 EMA or 8 EMA or even longer under 200 MA 
You are wasting your money 😂 
$QQQ $AAPL $NVDA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:41:58 </td>
   <td style="text-align:left;"> $QQQ 425 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:39:09 </td>
   <td style="text-align:left;"> $NFLX ad sales are a pivot point to $700 considering facebook makes billions from  ads, that will be more than just clickbait. Depending how they do the ads, some people might like seeing them. Different world we are living in, things have changed for better $SPY $QQQ $TSLA $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:38:38 </td>
   <td style="text-align:left;"> $QQQ 🚨🚨 
WARNING.. 
 
 YOU ARE SURROUNDED BY BLOOD SUCKING SHORT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:37:00 </td>
   <td style="text-align:left;"> $SPY   $QQQ  
 
#Caution for $TSLA supply chain issues &amp;#39;rest of 2022&amp;#39;..  
 
 this #Tesla #Martini chart from October 2021.  now at the same price as then..  people likely want their money back at this same level.. watch for sellers for a while! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:36:36 </td>
   <td style="text-align:left;"> Tesla Rocks but NASDAQ Drops https://theotrade.com/tesla-rocks-but-nasdaq-drops/ $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:35:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Be very CAREFUL!!! Technically and Fundamentally Indices are looking very weak. We could see significant GAP DOWN to 3% or more on SPY almost every day like we saw in March of 2020!!! THIS IS JUST THE BEGINNING!!! BLOOD BATH IS YET TO COME!!! 🩸 🩸 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:34:43 </td>
   <td style="text-align:left;"> $NFLX So the 37% plunge came from Bill Ackman selling out their entire position.  Good.  One less fund to worry about.   He was wrong buying 370+ and he is wrong selling today.   Seriously, what kind of investor holds for one quarter and gives up?   He lost his activist fund plays.  $spy $qqq $arkk  https://nz.finance.yahoo.com/news/pershing-square-holdings-ltd-releases-222000915.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:34:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $RUT big STORM is coming! Be CAREFUL!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:33:32 </td>
   <td style="text-align:left;"> $CVNA $NFLX $SPY $TSLA $QQQ 

Holy shit. caravana : reports.   Holy Shit 

      Q1 2022 Miss  -82.78% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:31:59 </td>
   <td style="text-align:left;"> $QQQ seems like TSLA is having minimal impact on QQQ.  Interesting trend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:29:24 </td>
   <td style="text-align:left;"> $SPY $qqq calls r puts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:29:18 </td>
   <td style="text-align:left;"> $SPY Cramer calling bull market, pushing for $TSLA $QQQ and telling you to buy is the signal needed 🤣🤣🤣🤣

See you tomorrow permabulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:24:48 </td>
   <td style="text-align:left;"> Happy 420  
 
$TSLA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:23:05 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures up, looks like the market is ready to bounce tomorrow after some very strong earnings reports after the closing bell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:21:28 </td>
   <td style="text-align:left;"> 20 beats today and 65 misses 

Not what I like to see surely market is not going to be fond either. Likewise 

    🧞‍♂️🔥 $SPY $SPX $ES_F $QQQ $DIA 🔥🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:21:27 </td>
   <td style="text-align:left;"> $SPY $TSLA bulls tomorrow when $900 is tested again. $SPY will die a naturally death and Powell wouldn’t be able to resurrect it and $QQQ can be buried inflames with the help of $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:19:29 </td>
   <td style="text-align:left;"> $SPY o they try to squeeze every last bit when they do it like this  

There will be a drop in the future at any time 

That no one will recover from. Just saying 

It’s close fyi sel in May and go away is real close     $QQQ $DIA $SPX $NDX  and we setting up for that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:16:27 </td>
   <td style="text-align:left;"> $SPY 420 crew got massacred today sorry 

Guys after looking at the account balances 

  🧞‍♂️🔥 $QQQ $NDX $DIA $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:16:12 </td>
   <td style="text-align:left;"> $TQQQ $QQQ $SQQQ $QID $QLD https://youtu.be/qL_LBPL2ZQY
Back the truck up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:14:41 </td>
   <td style="text-align:left;"> $QQQ $TSLA rolling over, this move AH is gonna turn red if TSLA dosn&amp;#39;t stop giving up its move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:12:47 </td>
   <td style="text-align:left;"> $QQQ $TSLA earning euphoria wearing off. Nothing will stop market cap and forward revenue corrections. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:10:45 </td>
   <td style="text-align:left;"> $TSLA Futes and TSLA gonna have shorts begging for their lives in the morning. 
 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:10:25 </td>
   <td style="text-align:left;"> $NETFLTGILT.NSE 👀

$SPY $TSLA $AMC $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:08:46 </td>
   <td style="text-align:left;"> $SPY Another fed officials said she wouldn’t take off 75 BPS off the table 🤔🤔🤔🤔

Bullard 
Kashkari 
Daly

All favors 75 BPS $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:05:45 </td>
   <td style="text-align:left;"> $QQQ  and $SPY coming back to 15 year trend line, so about another 25% lower,  will probably take a year to do it.  pick up a hobby  check back in a year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:03:56 </td>
   <td style="text-align:left;"> $SPY $QQQ You voted for the clown

CDC asks Justice Department to appeal ruling that lifted travel mask mandate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:03:52 </td>
   <td style="text-align:left;"> $FB  buy when $QQQ is 248 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 06:00:25 </td>
   <td style="text-align:left;"> $TSLA  Sometimes I wonder if Tesla shareholders, yes, plus your boss, just are naive or worse. we are in a down market, inflation not close to peaking until July 4, probably Ocyober, have tobded how vehicle and house sales do summer buy I&amp;#39;m picking up still until 7% rates w/ 11% inflation deteriorates their personal spending .
Income don&amp;#39;t care so much about except it buoys them to keep living and spending. And, yes, as housebjying goes down July report because inflation winning war Tesla going too. 
But Tesla could quit churning June too, if vehicle sales down before him home sales, quite possible too.
PLus,PLUS, and scarcity supply don&amp;#39;t forget 

Oh, and getting nowhere for 3/4 of Smetica, gee, ain&amp;#39;t inflation great.

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:57:29 </td>
   <td style="text-align:left;"> Hey Team, Todays PnL GREEN $33,000. Was a solid day trading $NFLX $TSLA $IBM $QQQ $CVNA. I focused on large caps today given the craziness and volatility in the markets. I had small size, probably left a good $30-$50k on the table for NFLX puts, but is what it is. Solid bounce back day from yesterday&amp;#39;s red session. Hope folks crushed the volatility. This is when I trade best when things are crazy in the market. I LOVE VOLATILITY. Learn to embrace it, it&amp;#39;s a day traders dream up or down! Cheers team </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:56:47 </td>
   <td style="text-align:left;"> $SPY Powell speaking tomorrow is the focus of attention not $TSLA unverified earnings. Buying this in the range of $550 is better than buying this at $1200. Even Elon wouldn’t buy at this price. Anyway he always overpromise and under deliver $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:55:41 </td>
   <td style="text-align:left;"> $TSLA  ==&amp;gt; MY WEEKLY $1000 CALLS IN THE MORNING THO!   .. 
I JUST KNOW SOME SHIT... LMAOOOOO  🤑🤑😆😂🤑🤑 
. 
$SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:55:29 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ $NASDAQ 

DESPITE INFLATION, DEMAND FOR TRAVEL SOARS AS RESTRICTIONS ARE LIFTED

https://thebusinessjournal.com/despite-inflation-demand-for-travel-soars-as-restrictions-are-lifted/?utm_source=rss&amp;amp;utm_medium=rss&amp;amp;utm_campaign=despite-inflation-demand-for-travel-soars-as-restrictions-are-lifted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:54:30 </td>
   <td style="text-align:left;"> $TSLA  tesla is not Down 20% so that’s  relief 

   🧞‍♂️ $SPX   $QQQ    $SPY   $NDX  🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:54:17 </td>
   <td style="text-align:left;"> $Spy Do futures contract charge margin? $dia $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:51:20 </td>
   <td style="text-align:left;"> Uranium is the new FANG 

$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:51:07 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 4/20/2022 $SPY $IWM $XLF $QQQ $GDX https://www.chartguys.com/daily-market-videos/4217/a-market-for-everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:50:43 </td>
   <td style="text-align:left;"> $QQQ check the rep😉
Be ready😶

https://youtu.be/59Q27Xo2hr0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:48:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 72983400. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:47:50 </td>
   <td style="text-align:left;"> $SPY $QQQ Looking back at historical charts seems like we are going to hover in this area another five or six months before the market will start to move upward again. I don’t see it crashing though….look back at 2007-2009 and the amount of volatility and volume that was being pushed through the market was insane….idk just my take </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:47:27 </td>
   <td style="text-align:left;"> $SPY Most $TSLA permabulls will be disappointed tomorrow. Do you know Tesla per share is almost $4K without split, and with PE of 202 🤣🤣🤣🤣

You’re better off buying a lottery ticket than buying inflated $TSLA shares with insane valuations. Time to deflate all this bubble $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:45:23 </td>
   <td style="text-align:left;"> $QQQ surely we will be green tomorrow right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:41:59 </td>
   <td style="text-align:left;"> $DJIA $SPY $QQQ high frequency traded assets have 2 day settlement😂cool story, bro. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:39:55 </td>
   <td style="text-align:left;"> If you sell your stock some whale willl buy it and hold it forever and get rich so just never sell $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:38:51 </td>
   <td style="text-align:left;"> $QQQ be ready😶😬

https://youtu.be/59Q27Xo2hr0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:38:31 </td>
   <td style="text-align:left;"> $NFLX Someone placed A $22 million bet then Netflix goes under $215.00

  $qqq $dia $SPY $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:32:50 </td>
   <td style="text-align:left;"> $QQQ once the $TSLA euphoria wears off, back to reality. Lots of uncertainty and issues in the market right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:20:30 </td>
   <td style="text-align:left;"> $QQQ nasdaq down -20% on the year, i think we will break even this year. could be at a bottom here, but we shall see $SPY $IWM $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:19:51 </td>
   <td style="text-align:left;"> $tsla is huge part of $spy and $qqq so market going to rip for a while now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:19:48 </td>
   <td style="text-align:left;"> $SPY $qqq could easily recover a bit with the FAAG stocks rebounding. Tesla beat sure doesn&amp;#39;t hurt.  Gap up squeeze? 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:17:33 </td>
   <td style="text-align:left;"> $QQQ $SPY Turns out it was just Netflix that stinks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:15:29 </td>
   <td style="text-align:left;"> Many Death crosses: Stocks &amp;amp;Sector ETFs@Market👀possibly verge to🐻Mkt $AMD $QQQ $SPY $AAPL $PYPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:15:05 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA not sure how great it is that a company trading at 22x sales, Tesla, is propping up the entire market it seems. 😳

And they sell cars.  🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:14:59 </td>
   <td style="text-align:left;"> Definitive materials https://www.conferencecalltranscripts.com/summary/?id=10726899 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:13:50 </td>
   <td style="text-align:left;"> $TSLA $QQQ  isn’t buying this fake pump. Neither am I. Have fun getting screwed even more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:13:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
Yeah I’m done chasing growth at 52-week lows to watch it dip to new 52-week lows.  Sitting fat dumb and happy mostly in SPY and cash and selling premium. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:12:34 </td>
   <td style="text-align:left;"> $QQQ 📜 SEC Form 497 filed by Invesco QQQ Trust, Series 1

https://quantisnow.com/i/2745578?utm_source=stocktwits

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:11:48 </td>
   <td style="text-align:left;"> $QQQ Form 497 (definitive materials) filed with the SEC 

https://newsfilter.io/a/b6fe2811abafcdf6b5aae509983322cf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:10:50 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM  
 
TAKE A BOW 
ITS KINDA HARD 
YOU ON THE GROUND 
TWITCHIN’ 
 
$NFLX  
 
See yah tomorrow 😉 
 
https://m.youtube.com/watch?v=x9y2IWPHTVQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:08:38 </td>
   <td style="text-align:left;"> $QQQ what if Tesla goes up 100 tomorrow -- americans love tech stocks LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:08:33 </td>
   <td style="text-align:left;"> $ND_F on the 4 hr chart, not really showing any support here except an upward trend line I’ve been tracking since Apr-18. Not in a robust situation given all this volatility. Could still see lower numbers before the pump occurs. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:06:39 </td>
   <td style="text-align:left;"> This market is going to rally fvckin insane nobody cares about $nflx anymore now the story is skyrocketing $tsla now the story is $lrcx flying despite a miss it’s stocks shrugging off hikes and war it’s it’s euphoria it’s animal spirits it’s insanity proce is all that matters  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:06:01 </td>
   <td style="text-align:left;"> $QQQ $SOFI Send it all to zero and start over…. For fucks sake make it stop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:05:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $NFLX bears when they find out an online streaming service does not measure the GDP of America 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:05:44 </td>
   <td style="text-align:left;"> $UPST Tomorrow is shaping up to be a big green day. Bond yield futures are dropping, Tesla killed earnings, Nasdaq futures climbing. Let&amp;#39;s make some money bulls! $QQQ $TSLA $PYPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:05:15 </td>
   <td style="text-align:left;"> $TSLA this markets fucked. $SPY $QQQ $IWM Shouldn’t have covered my growth shorts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:04:16 </td>
   <td style="text-align:left;"> $QQQ today was the toughest hold I ever had — happy af rn 🥃 $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:02:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 05:01:41 </td>
   <td style="text-align:left;"> $SPY $QQQ   
 
https://www.cnbc.com/2022/04/19/us-housing-starts-unexpectedly-rise-in-march-building-permits-increase.html 
 
What slowdown? The US economy is strong and people will continue to buy houses even rates are rising since they make enjoying bigger paychecks at work </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:59:10 </td>
   <td style="text-align:left;"> $QQQ market sentiment improving. QQQ will seek big rebound tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:59:04 </td>
   <td style="text-align:left;"> $SPY bearz big mad ... Thats what happens when u dont listen n follow the clam 👍😬 $tsla $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:58:02 </td>
   <td style="text-align:left;"> $LUNA.X $DOT.X showing their metal. Not intimidated by all this recent ruckus with $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:56:29 </td>
   <td style="text-align:left;"> Let’s see if the $QQQ continues to pull the $SPY down by end off week 
$NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:56:13 </td>
   <td style="text-align:left;"> $SPY $QQQ The market is still looking very good here. The US economy is red hot and showing absolutely zero sign of slowing down anytime soon. The jobs market is tight and wages are rising rapidly for most American workers. Earnings are also at record highs and should continue to rise in the coming years thanks to the strong US economy. If you are confident in the outlooks of the US economy then you should be buying stocks now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:53:21 </td>
   <td style="text-align:left;"> $SPY Tesla stock&amp;#39;s down over 4% on the day and bull&amp;#39;s thinking earnings taking it to 🌙

😒

$TSLA  Sooo, this is what&amp;#39;s wrong with America .

It&amp;#39;s a bad stock, I get accused of saying,  REV was bad, no &amp;amp; no.

It&amp;#39;s a good stock but by stock so high so beat needs even HIGHER but in a fierce EV coming climate + economically depressive enviro, no hope.
TSLA Asia HQs in lockdown that shows no end in sight. 20,000 vehicles/week lost. 

Inflation, rates, changing consumer sentiment, it all is, slowly, changing and eroding their thought processes and buying power and buying ability, even, as Dollar Store items now 1.25 each, everything else.

Telling ya, telling ya, telling ya, world economy sinking--and fast, as, consumer is spending its massive $150 trillion household wealth all summer but noticeably digging own grave every shovelful of buys.
IMF just slashed world growth. 
March Core CPI inflation no more than less spending cuz of war in infancy early March, people concerned 
$QQQ $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:53:12 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:52:38 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM still 100% long (see my 4/11 tweet) 
 
QQQ (my favorite child aka The Chosen One) is misbehaving 
His ugly siblings (SPY, IWW) are looking OK since the 4/18 bottom retest (my longs = approx 25% SPY, 25% IWM, 50% QQQ) 
 
Anyone long/short today?  Which stocks, ETFs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:51:13 </td>
   <td style="text-align:left;"> $QQQ it was 348 pre market, I’d love to see it retest it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:51:09 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 540.4K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:50:43 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $VIX $TLT  
Economic Calendar -J Powell speaking tomorrow- 
https://www.financegreater.com/economic-calendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:50:17 </td>
   <td style="text-align:left;"> This certainly is not aging well. I thought in investing you are not trying to catch a falling knife but buying breakouts from bullish setups where stop losses can be placed for minimal losses and prudent money management. He should of just put money into oil, natgas, silver or gold. Ackman has many enemies on wall street so i am sure they are popping the champagne tonight enjoying this massive failure of common sense. $NFLX $DIS $TSLA $ARKK $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:50:04 </td>
   <td style="text-align:left;"> $QQQ 346 🔥 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:49:51 </td>
   <td style="text-align:left;"> $SPY not very promising tho 

  . $QQQ  . $NDX  . $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:49:34 </td>
   <td style="text-align:left;"> $QQQ when stocks goes down , they go 30-40 percent like Netflix and when it goes up, it’s goes up only 2-5 percent, like Tesla.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:49:09 </td>
   <td style="text-align:left;"> $SPY . $DIA . $NDX . $QQQ 

Let’s see if we can close this week green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:48:47 </td>
   <td style="text-align:left;"> $QQQ $TSLA save the market? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:48:46 </td>
   <td style="text-align:left;"> $TSLA Great job $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:47:22 </td>
   <td style="text-align:left;"> $SPY $QQQ the real bag holders are going to be car dealerships with a bunch of over priced used cars lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:46:59 </td>
   <td style="text-align:left;"> $TSLA puts were up 1,000%!!!

that’s how you know something was up and it got pumped $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:46:01 </td>
   <td style="text-align:left;"> $QQQ Tesla up 4%. We will also rally 4% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:45:13 </td>
   <td style="text-align:left;"> $TSLA at $1540 Tesla would have a 201 p/e ratio like we had earlier today, gents we are extremely cheap for a mega growth stock $QQQ $ARKK $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:43:55 </td>
   <td style="text-align:left;"> $RBLX $SPY $QQQ 

MM in collusion with investment firms used Covid to trap 3 million new retail traders , during the run analysts which are beyond corrupt were PAID to have ridiculous price targets giving a false sense of security to retail . You have witnessed one of the largest ORGANIZED thefts in history and yes all the others happened on the markets as well. Algos, tv personalities , MM , dark pools , institutions were all in on it and pumped the markets through the roof , then rigged pulled and stole trillions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:43:40 </td>
   <td style="text-align:left;"> $ES_F . $SPX . $SPY . $QQQ . $NDX 

Just a quick end of day earnings update for today pre market and after market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:42:48 </td>
   <td style="text-align:left;"> $TSLA love that number and growing margins and customer demand even in this kind of inflated market. Finalt lot in 300/300 for now $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:42:35 </td>
   <td style="text-align:left;"> $TSLA could go up over 50% and we would have pre  earnings P/e ratio of earlier today of 201 $QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:42:11 </td>
   <td style="text-align:left;"> $QQQ $IWM $SPY

Wonder how Bullard and Powell both speaking tomorrow will impact markets 😁
BEARISH 🐻 🐼 🐨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:38:29 </td>
   <td style="text-align:left;"> $TSLA exceeded my expectations and the PE ratio is now 133 keeps going down with explosive earnings $QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:35:01 </td>
   <td style="text-align:left;"> $QQQ eeesh... TSLA has a blowout qtr, and bears already getting too bearish before the actual ER call. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:34:26 </td>
   <td style="text-align:left;"> $TSLA $QQQ once the earnings euphoria wears off it&amp;#39;s going to tank. Absolutely nothing wrong with the company, it had an amazing earnings. Market is going to correct all valuations of companies across the board due to the environment we are in. Easy money policy is done, cost to borrow will increase, inflation a worldwide issue, supply constraints, etc will cut forward projected revenue for all companies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:31:24 </td>
   <td style="text-align:left;"> $QQQ 

MULN ✈️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:30:00 </td>
   <td style="text-align:left;"> $QQQ Tesla still red for the day. Problem is not with company performance, it&amp;#39;s about valuations coming back down to earth. Easy money policy is done, costs to borrow rising, and supply constraints, inflation is cutting forward revenues. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:24:33 </td>
   <td style="text-align:left;"> $TSLA will lift market ...positive sentiment  
 
 
$DIA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:24:04 </td>
   <td style="text-align:left;"> $TSLA I swear if this goes down or end up being where it started I  kill my pc and burn my ratchet trailer . I’m just trying to gtfo my shit hole trailer  , living rough with roach and some rats .  $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:23:42 </td>
   <td style="text-align:left;"> $SPY $QQQ Non event (?) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:22:27 </td>
   <td style="text-align:left;"> $TSLA $QQQ $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:22:19 </td>
   <td style="text-align:left;"> $QQQ interesting to see Tesla great earnings do fuck all to the market whilst Netflix crashed it lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:21:50 </td>
   <td style="text-align:left;"> $QQQ - Elon sinks the ship after he runs his pie hole today. 333-336 on the Q’s by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:21:28 </td>
   <td style="text-align:left;"> $QQQ Powell again tmr 😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:21:17 </td>
   <td style="text-align:left;"> $QQQ  Told you TSLA about to go red, this market is fucked, NVDA did beat last time and the stock dropped! Nothing will save this market, it’s heading way lower than February lows!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:21:07 </td>
   <td style="text-align:left;"> $QQQ sorry, not even papa Elon can save this train wreck.  Down the hatch tomorrow!  (Or should I say down the toilet bowl) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:20:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $NFLX 
 
TOMORROW MARKET GOING TO BE GREEN THANK TO TSLA after  
STUPID NFLX FUCK IT UP!!! 
 
they should not name it FAANG 
 
SHOULD BE GMAAT  
GOOGLE 
META 
AAPLE 
AMAZN 
TSLA! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:19:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:18:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:18:36 </td>
   <td style="text-align:left;"> $QQQ $SPY So the market is dumping as it focuses on shitty Netflix...Which produces nothing but shitty content...No real GDP.  While companies like IBM, Tesla, etc are blowing numbers away.  Record number of stocks are 50%+ down off their highs, record number of stocks hitting 52 weeks lows.... 
 
The big money is robbing retail blind (again) and loading up down here.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:18:33 </td>
   <td style="text-align:left;"> Markets Close Mixed Amid Netflix Plunge, Onset Of Earnings Season  $QQQ $SPY $DIA $MTB $IBM 

https://newsfilter.io/a/9e30009ca76fa1f75793601404493018 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:18:12 </td>
   <td style="text-align:left;"> $NFLX misses and while market instantly crashes. $TSLA just had a massive beat and nothing else in $QQQ moving. Huh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:18:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:17:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 4/21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:17:06 </td>
   <td style="text-align:left;"> $SPY Average ER for Tesla, stock is waaaaaay overvalued, surprised didn&amp;#39;t surprise everyone and pop down 10% at #s

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:16:22 </td>
   <td style="text-align:left;"> $QQQ $TSLA $SPY Just when the “electric vehicle experts” came out today to say that Elon was comparable to Netflix. Reverse H/S on the Spy and QQQ still in play. Bury Michael Burry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:15:41 </td>
   <td style="text-align:left;"> $TWTR I repeat… do not fuck with Elon. $TSLA $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:15:13 </td>
   <td style="text-align:left;"> $PYPL $QQQ wow. r u serious..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:14:55 </td>
   <td style="text-align:left;"> $QQQ I don&amp;#39;t think people understand it&amp;#39;s about lowering guidance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:14:24 </td>
   <td style="text-align:left;"> $QQQ looks like TSLA did it and qqq will rally tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:14:21 </td>
   <td style="text-align:left;"> $TSLA lick 👅 our bulls butt hole bears 🐻 lmao at Michael burry . Noob Michael.. he legendary short !!? Lmao make me 😂 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:13:56 </td>
   <td style="text-align:left;"> $QQQ Begin the $TSLA &amp;quot;Musk Rally&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:12:59 </td>
   <td style="text-align:left;"> Market wrap: 
🔷 US indices closed mixed on the day:  
$DJIA +0.7%, $SPX -0.1%, $QQQ -1.2% 
🔷 #Gold (+0.1%) and #WTI (+0.0%) were flat. 
🔷 #AUD was the day&amp;#39;s strongest major currency; #USD was the weakest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:12:45 </td>
   <td style="text-align:left;"> $WMT Nice move with a BID /ASK SPREAD of a  $1.20  Keep those suckas rolling in ,PUTS ARE starting to PRINT $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:11:59 </td>
   <td style="text-align:left;"> $TSLA  they beat it $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:11:45 </td>
   <td style="text-align:left;"> $SPY And don’t forget Powell is speaking tomorrow $TSLA $QQQ $IWM 

Options market says ⬇️⬇️⬇️⬇️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:11:21 </td>
   <td style="text-align:left;"> $QQQ Netflix put the brakes on the NASDAQ rebound, Tesla beat so looking good for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:10:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA ELON IS KILLING IT!!!!!!!!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:10:16 </td>
   <td style="text-align:left;"> $QQQ This will be the start of our run to ATH $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:10:03 </td>
   <td style="text-align:left;"> $QQQ Tesla record number s, may save us tommorow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:09:34 </td>
   <td style="text-align:left;"> $TSLA big beat 🚀🚀🚀 $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:09:24 </td>
   <td style="text-align:left;"> $QQQ big pump tomorrow with the Tesla beat unless there’s unexpected news on the call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:09:14 </td>
   <td style="text-align:left;"> $QQQ Tesla will prop this up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:08:49 </td>
   <td style="text-align:left;"> $QQQ $spy $tsla just said tomorrow is money Thursday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:08:20 </td>
   <td style="text-align:left;"> $TSLA the most profitable &amp;quot;philanthropic&amp;quot; company around, lol $SPY $QQQ  
 
(for all you blow hards eager to instantly defend Musk making hundreds of billions, yes I believe in Capitalism, but don&amp;#39;t call it Philanthropy) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:07:38 </td>
   <td style="text-align:left;"> $SPY Amazon all over again (and how did that, ultimately,  end a few days after ER, bulls).

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:06:51 </td>
   <td style="text-align:left;"> $QQQ tomorrow this rips. Who gives a fuck about Netflix </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:06:40 </td>
   <td style="text-align:left;"> $QQQ lmao this movement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:06:14 </td>
   <td style="text-align:left;"> $QQQ wild moves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:05:57 </td>
   <td style="text-align:left;"> $QQQ $tsla let’s go 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:05:54 </td>
   <td style="text-align:left;"> $NFLX Wow.. Crazy drop today.. $QQQ $MSFT $AAPL  
 
I am getting out of Tech and Fang Stocks . Can&amp;#39;t handle the Pain  
  
Moving my money to Oil / Energy / Utilities / material stocks as War / Inflation / Higher rates has fuxxed the shxt out of tech stocks now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:05:40 </td>
   <td style="text-align:left;"> $QQQ $SPY 

sooooo yuuge bigly pumpe tomorrow? $TSLA 

Lolololololllll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:05:13 </td>
   <td style="text-align:left;"> $QQQ FUCK YES DUDE $TSLA holy shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:04:44 </td>
   <td style="text-align:left;"> $SPY $QQQ I guess Tesla might have short term impact to the market depending on how it does on earnings. I don&amp;#39;t like Tesla, I think the stock is way overvalued and EV is way overhyped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:04:12 </td>
   <td style="text-align:left;"> UKRAINIAN NEGOTIATOR DAVID ARAKHAMIA SAYS HE AND PODOLYAK ARE READY TO GO TO MARIUPOL TO NEGOTIATE WITH RUSSIA &amp;#39;ON THE EVACUATION OF OUR MILITARY GARRISION AND CIVILIANS&amp;#39; $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:03:06 </td>
   <td style="text-align:left;"> Gov. Greg Abbott&amp;#39;s slowdown of trucks at Texas border cost U.S. economy $9 billion, economist says

https://www.sacurrent.com/news/gov-greg-abbotts-slowdown-of-trucks-at-texas-border-cost-us-economy-9-billion-economist-says-28701805?media=AMP+HTML

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:00:43 </td>
   <td style="text-align:left;"> $QQQ looks like the pub covering is over. If you are a bull waiting till tomorrow to buy is a safer bet because of the potential Tesla issues. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 04:00:12 </td>
   <td style="text-align:left;"> $QQQ $TQQQ Reverse Head &amp;amp; Shoulders? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:59:18 </td>
   <td style="text-align:left;"> $SPY  $QQQ  something gona break... or  melt up again like yesterday ? 😅🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:58:26 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ  
 
Tesla misses and this market is done! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:57:52 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Not my kinda day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:56:54 </td>
   <td style="text-align:left;"> $QQQ 

I am convinced that QQQ will test $315 area again by 4/29 when Apple reports. Or not. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:56:49 </td>
   <td style="text-align:left;"> $QQQ i am all cash. Holding on the sidelines........ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:56:24 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ oh shit Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:56:12 </td>
   <td style="text-align:left;"> $QQQ $FB  both fckd up pos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:55:46 </td>
   <td style="text-align:left;"> $SPY Jesus told the disciples, the hours has come… $TSLA $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:55:42 </td>
   <td style="text-align:left;"> $NFLX Time to trap all the shorts today and squeeze after the bell $uvxy $qqq $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:55:15 </td>
   <td style="text-align:left;"> $QQQ $TSLA  ready? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:54:59 </td>
   <td style="text-align:left;"> $TSLA Hope you bulls are ready. They are going to drop this like a rock to get the $QQQ under 340. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:54:55 </td>
   <td style="text-align:left;"> $QQQ $SPY Markets didn&amp;#39;t seem to care much about Ukraine negotiation headline. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:54:38 </td>
   <td style="text-align:left;"> $NFLX 

Is this an inverse $Qqq etf rn? JFC what the fu*k is going on here lmfaooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:54:19 </td>
   <td style="text-align:left;"> $QQQ $SPY you can almost always rely on quick option plays in the last 10 min of 0dte in the opposite direction it’s going before 10 min left </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:53:11 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ Folks: A Tesla disappointed along with one more from the Microsoft&amp;#39;s of the world will expedite the trip down to lower lows. Capitilize on it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:53:03 </td>
   <td style="text-align:left;"> $SPY  
nasdaq to 17k 

dow 40k 
spy 10k 
iwm 5k 

$IWM $NVDA $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:52:49 </td>
   <td style="text-align:left;"> $NFLX it wasn&amp;#39;t but 20 years ago when a male could get pregnant and then be elected Republican Governor.  Now people are willing to cancel streaming subscriptions b/c the idea is too &amp;quot;Woke&amp;quot;   
 
We have to really question who or what has changed in this equation... $SPY $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:52:39 </td>
   <td style="text-align:left;"> $QQQ hourly.   Wall st pinning it until Tesla and others come out with their surprises </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:51:53 </td>
   <td style="text-align:left;"> $QQQ nasdaq sucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:51:49 </td>
   <td style="text-align:left;"> $QQQ need to hold 348 topside ..then short with futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:51:18 </td>
   <td style="text-align:left;"> $QQQ $SPY they always be trying hard in the last 10 because of 0dte 🤦‍♂️ kinda annoying tbh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:50:38 </td>
   <td style="text-align:left;"> $spy $qqq it depends, the netflix weakness may be partly from weakening discretionary spendg. could be a canary in the coalmine for discretionary techs so not necessarily good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:49:32 </td>
   <td style="text-align:left;"> $SPY $QQQ I was reading the news about theta burn, then I became part of the story. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:48:52 </td>
   <td style="text-align:left;"> $QQQ  lets close green and ride the fake pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:48:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA Tesla earnings are on deck for after the closing bell! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:48:25 </td>
   <td style="text-align:left;"> $QQQ I honestly want to join the plunge protection team </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:48:22 </td>
   <td style="text-align:left;"> $QQQ Apple drives everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:48:02 </td>
   <td style="text-align:left;"> $QQQ let’s do that close green thing again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:47:08 </td>
   <td style="text-align:left;"> $QQQ Bulls putting in that work defending 342. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:47:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 72860500. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:46:33 </td>
   <td style="text-align:left;"> The DOW is up +340 points and my entire screen is red....LOL 
 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:45:34 </td>
   <td style="text-align:left;"> $QQQ only matter of time when we get the capitulation flush … no more stimulus slowing economy. Nothing looking good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:43:33 </td>
   <td style="text-align:left;"> $SPY $QQQ Worth watching 
 
https://www.youtube.com/watch?v=8VaLErSf9Xk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:42:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA GL this afternoon hodlers. If TSLA fails to impress this afternoon the market&amp;#39;s probably going to chop or worse for the next week until AAPL reports. -Good times! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:42:41 </td>
   <td style="text-align:left;"> $QQQ $SPY really want $TSLA earnings to be good for the sole reason that they might start turning FAANG into FAGGT… could you imagine the articles?😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:42:38 </td>
   <td style="text-align:left;"> $QQQ 

Close it above 342 for super funzies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:42:20 </td>
   <td style="text-align:left;"> $QQQ $SPY Up one day, down the next. People think they are winning, your not. This crash will be epic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:42:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA
Lights, Cameras…. ACTION!!  🎥 🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:41:13 </td>
   <td style="text-align:left;"> $SPY $QQQ Dragonflies are out on the hourly candles. ✝️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:40:08 </td>
   <td style="text-align:left;"> $NVDA . $AMZN . $AMD . $SPY . $QQQ 

It’s a sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:39:44 </td>
   <td style="text-align:left;"> $XLF Is a buy $QQQ Is a sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:38:46 </td>
   <td style="text-align:left;"> $SPY $QQQ Buying beaten high growth names here is just as good as buying travel in Mar 2020 - change my mind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:36:06 </td>
   <td style="text-align:left;"> $QQQ if TSLA shits the bed too…. We gonna see some real panic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:36:05 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:35:06 </td>
   <td style="text-align:left;"> $QQQ today the day $TSLA replaces $NFLX and it becomes FAAGT? Lol😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:34:43 </td>
   <td style="text-align:left;"> $ALZN nice 25k share buy popped it 4 cents. Looking for million share buys soon and quarter/dollar pops. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:34:39 </td>
   <td style="text-align:left;"> $QQQ Totally being propped up artificially 
Big sell off coming into the close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-21 03:34:16 </td>
   <td style="text-align:left;"> $QQQ gearing for the 3:45 pump mega pump like yesterday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:35:08 </td>
   <td style="text-align:left;"> $NFLX oh hell is coming -“Ackman” or Conman … fooled common man in his last stint when he said on primetime that hell is coming…. got dinged himself after buying nflx after last ER. $MSFT $GOOG  $AAPL stay with low beta garp stocks! 

 Ackman sells Netflix stake after post-earnings plunge https://www.cnbc.com/2022/04/20/bill-ackman-sells-netflix-stake-after-post-earnings-plunge.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:30:25 </td>
   <td style="text-align:left;"> $AAPL $170 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:29:57 </td>
   <td style="text-align:left;"> $AAPL we fly tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:28:22 </td>
   <td style="text-align:left;"> $NFLX
Transgender population is almost hitting 5,71 Billion this year. Netflix has definitely seized this opportunity.

$SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:21:02 </td>
   <td style="text-align:left;"> $SPY When I think about Ackman I think about the Wall St game &amp;amp; how he gets to play it. 
A $400m loss on $nflx, an almost $4b loss in Valeant &amp;amp; yet he still gets to run a HF &amp;amp; people still give him money. 
 
Amazing isn&amp;#39;t it? 
 
https://www.yahoo.com/news/3-lessons-from-bill-ackmans-4b-trading-loss-in-valeant-182037105.html 
 
$baba $aapl $bb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:16:22 </td>
   <td style="text-align:left;"> $AAPL up 30% on the Apr 29 $172.5 CALL bought yesterday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:13:55 </td>
   <td style="text-align:left;"> $AAPL i&amp;#39;m dead, ackman shorts market runs higher, he capitulates short the market drops. ackman buys netlfix it tanks,  capitulates shares, so rocket up now $NFLX $GME $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:06:38 </td>
   <td style="text-align:left;"> $AAPL Channel here. If we breakout we can get a nice move to $175. https://share.trendspider.com/chart/AAPL/81308awbum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:05:22 </td>
   <td style="text-align:left;"> $AAPL $AMZN $GOOG  
 
Now which one of you is going to fall on earnings? 🤔 
 
$SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:04:56 </td>
   <td style="text-align:left;"> $AAPL Apr 20               
Sell               
◆ Search for 10 day stock forecast by pretiming A.I               
http://www.google.com/search?q=10+day+stock+forecast               
◆ Forecast of Upper~Lower price range band for the next 10 days               
Price: 157.45   ~ 170.57            
% Change: -5.85%  ~ 2.00%           
The Buy-Sell strength is suitable for the current trend and it&amp;#39;s about to begin a downward trend as a rebounding trend gradually gives way to increasing limited rises and strong falls in the falling section. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:04:41 </td>
   <td style="text-align:left;"> $SPY Another $15B printing spotted by Powell printer again. Don’t worry, powell is fighting inflation by printing more money 💰 $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 09:01:48 </td>
   <td style="text-align:left;"> $AAPL Check the level.
https://www.tradingmain.com/2022/03/apple.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:55:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  * posted this China manufacturing warning April 01 when China contracted 1st time in 2 years since Covid started.   
 
now the GDP  forecast drop..  another big caution.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:54:23 </td>
   <td style="text-align:left;"> $AAPL Do you think we&amp;#39;ll see $170 tomorrow or Friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:52:52 </td>
   <td style="text-align:left;"> $BABA closed under 90 today. No one else gives you precise targets with deadlines… for free. $TSLA $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:47:48 </td>
   <td style="text-align:left;"> $AAPL lol every week the same optimistic people saying apple is going up.  Tomm maybe up to 171.00 pm  but like always,  it will fall back to 165.00. Mr.Money Printer Jerome will be speaking so you already know that’s gonna tank all stocks. Any chance hedges can they will tank the stock. Now if eveyone bought put at 170 or 171….maybe it will go up…$spy $NVDA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:45:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA Huge squeeze incoming tomorrow? Bigly bull gains to be made, poor shorts/bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:45:22 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Store employees in Atlanta file for union election https://www.stck.pro/news/AAPL/26468527 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:45:11 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY green futures likely red by morning just like deep red yesterday was green by open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:44:33 </td>
   <td style="text-align:left;"> $AAPL tomorrow we 🚀🚀🚀🚀🚀 tesla bears earning !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:40:50 </td>
   <td style="text-align:left;"> What To Expect from Camera When iPhone 14 Comes Out $AAPL https://www.billionaireclubcollc.com/what-to-expect-from-camera-when-iphone-14-comes-out/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:38:43 </td>
   <td style="text-align:left;"> $MULN $AMZN $AAPL $TSLA $NIO 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:32:44 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-20 Chart Analysis Video: 
https://www.youtube.com/watch?v=oXCASgpAZWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:18:35 </td>
   <td style="text-align:left;"> $NFLX so $AAPL or $AMZN wouldn&amp;#39;t pay a premium to own this company? Pretty compelling price for an acquisition and thus a floor under stock price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:17:25 </td>
   <td style="text-align:left;"> $AAPL who bought those 170$ calls for 40 cents, we will rocket tomorrow - looking for atleast $1.2 on those contracts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:05:27 </td>
   <td style="text-align:left;"> Apple union organizers in Georgia say they were inspired by Amazon warehouse workers

$AAPL $AMZN

https://www.cnbc.com/2022/04/20/apple-union-organizers-in-georgia-inspired-by-amazon-warehouse-workers.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:05:03 </td>
   <td style="text-align:left;"> $AAPL NO JOKE…JUST READ, “EACH ILLEGAL IMMIGRANT GIVEN $15,000”.   A FAMILY OF 4 MEANS $60,000 ???  WTH ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:00:06 </td>
   <td style="text-align:left;"> $AAPL Option to look at... 👀 👀  $167.50 Call for Friday, April 22, 2022. Roughly 1 Million dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:00:05 </td>
   <td style="text-align:left;"> $AAPL $GOOG $GOOGL $MSFT $AVGO safest technology plays in the entire market imo. everything else has literally being obliterated. if these starts to rollover, especially $AAPL so does the overall markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 08:00:00 </td>
   <td style="text-align:left;"> $AAPL shows a strong growth in Revenue. In the last year, the Revenue has grown by 28.62%. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:58:36 </td>
   <td style="text-align:left;"> $AAPL 100 price target look at Chinese stocks $BABA $BIDU $TENCENT , apple is about to crash it trades with China …. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:47:44 </td>
   <td style="text-align:left;"> $AAPL 170 call next week👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:47:41 </td>
   <td style="text-align:left;"> $NFLX all bets are off, this is no mans land for a while... 
I say a year and 1.2 minimum to work out their social problems, stupid shit has a price I guess...   
 
By the way, this dumb fool in the picture is chugging a lot of beer from where I come from... $AAPL and $DIS are on notice... look at today&amp;#39;s price action... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:47:08 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple union organizers in Georgia say they were inspired by Amazon warehouse workers https://www.stck.pro/news/AAPL/26466409 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:46:33 </td>
   <td style="text-align:left;"> $SPY latex7ca228c18bcef94f1c72369318d67ec7BTC.X  
$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:43:26 </td>
   <td style="text-align:left;"> $AAPL 
220 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:43:25 </td>
   <td style="text-align:left;"> $AAPL last 4 candles form an ugly morning star. Reclaim the 50ema and back to 175 by Friday?

Go Irish! 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:36:02 </td>
   <td style="text-align:left;"> $AAPL BIDEN ADMINISTRATION MOST CONFUSED IN AMERICAN HISTORY…😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:31:11 </td>
   <td style="text-align:left;"> $AAPL ah 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:28:43 </td>
   <td style="text-align:left;"> $AAPL y’all are buying this straight up vertical line??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:28:25 </td>
   <td style="text-align:left;"> $SPY It is really baffling that permabulls want ATH in all these over leverages companies with little or no fundamentals especially this bubbles here and there. Within 2 years $TSLA doing 2 stock splits with no shareholders dividend, many buybacks with fat check of corporate bonuses while regular employees’ get screwed. Well, time will tells…

Don’t worry $AAPL will produce another iPhone for you to buy and curb inflations </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:25:56 </td>
   <td style="text-align:left;"> $TSLA megacaps the next correction $AAPL $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:20:45 </td>
   <td style="text-align:left;"> Should $AAPL take out $NFLX now?  Pocket change. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:18:13 </td>
   <td style="text-align:left;"> $NFLX what kinda paper handed shit is this 

https://www.google.com/amp/s/www.hollywoodreporter.com/business/business-news/hedge-fund-titan-bill-ackman-sells-all-netflix-stock-as-billion-dollar-bet-flops-1235133055/amp/

$tsla $dis $aapl $fb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:15:21 </td>
   <td style="text-align:left;"> $AAPL I’m wondering how the stupid inexperienced traders that sold $AAPL, $MSFT after Netflix earnings feel today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:10:07 </td>
   <td style="text-align:left;"> $CVNA . $DKNG . $CRM . $DIS . $AAPL   
https://on.mktw.net/38bpjM8 Check out this article from MarketWatch - U.S. Capitol evacuated, citing ‘probable threat’ from aircraft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 07:04:02 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG load the hell uppppp earnings all will be great!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:57:15 </td>
   <td style="text-align:left;"> $AAPL how is a phone salesman going to be paid $30 an hour when they don’t even pay the U.S. troops that much who protect our country everyday.
Come the F on..

Let’s get real, they barely know how to troubleshoot phone issues when you go in with one. They have to call support 95% of the time or ask a manager to assist them.
Now the store managers, I can see them making $30 an hour. Not your average, barely graduated high school, weed smoking, mouthy attitude having kid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:56:56 </td>
   <td style="text-align:left;"> $TSLA huge upside here imo..Elon is always straightforward and transparent, yet delivers almost every quarter to plan..other than Tim at $AAPL or Jensen at $NVDA…Elon/Tesla probably the most impressive ceo/company on the planet..hate all you want, it’s true </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:55:40 </td>
   <td style="text-align:left;"> $AAPL over sold here..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:55:38 </td>
   <td style="text-align:left;"> $TSLA  As of now Tesla is being held below previous channel resistance it needs to break out from...$QQQ $SPY $AAPL $UVXY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:55:16 </td>
   <td style="text-align:left;"> $AAPL $GOOG $FB $AMZN No so Bueno today! Leading indicator for tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:52:29 </td>
   <td style="text-align:left;"> $AAPL   🍏 Tapped, a “Stochastic Buy Signal”.  Oversold, on multiple frames. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:50:55 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 42.4K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:47:35 </td>
   <td style="text-align:left;"> $AAPL  🍏 Wayyyyy early…but: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:47:24 </td>
   <td style="text-align:left;"> $AAPL $170 BY EOW IMHO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:44:16 </td>
   <td style="text-align:left;"> $PYPL We do you buy under short term 
5 EMA or 8 EMA or even longer under 200 MA 
You are wasting your money 😂 
$QQQ $AAPL $NVDA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:30:18 </td>
   <td style="text-align:left;"> $AAPL View @ www.elliottwave-forecast.com Is favoured to have peaked against the March 2022 cycle low and is now pulling back.  It has declined in 5 waves from recent peak, a bounce in 7 waves is now favoured before resuming lower.  It is in the middle, we do not prefer to trade it. #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:26:35 </td>
   <td style="text-align:left;"> $AAPL How’s my number 1 domino doing today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:23:47 </td>
   <td style="text-align:left;"> Apple store workers in Atlanta file for the company’s first union election 
 
70% of workers at an Apple store in Atlanta want to join the CWA 
 
$AAPL 
 
https://www.theverge.com/2022/4/20/23034175/apple-store-workers-atlanta-union-retail-amazon-google </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:17:10 </td>
   <td style="text-align:left;"> $AAPL I don’t think people here will be happy tommorow at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 06:12:12 </td>
   <td style="text-align:left;"> These 9 Million People are going to be very happy they can download the app on $GOOG  latex8dd0dea57350bb28908c764f532534adAMD ↗️

$AAPL  $BTC.x $MSFT  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:59:19 </td>
   <td style="text-align:left;"> $AAPL poots for ER next week. You&amp;#39;re welcome

https://techcrunch.com/2022/03/28/apple-said-to-be-cutting-iphone-se-production-20-over-ukraine-inflation-concerns/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:58:14 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Atlanta Apple Store Workers Are the First to Formally Seek a Union https://www.stck.pro/news/AAPL/26460963 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:58:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 26.38%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:56:47 </td>
   <td style="text-align:left;"> $SPY Powell speaking tomorrow is the focus of attention not $TSLA unverified earnings. Buying this in the range of $550 is better than buying this at $1200. Even Elon wouldn’t buy at this price. Anyway he always overpromise and under deliver $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:50:33 </td>
   <td style="text-align:left;"> $AAPL tomorrow upgrades and expect fucking squeeze $175.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:48:13 </td>
   <td style="text-align:left;"> $AAPL Apple Might Have a Wage War on Its Hands

https://www.thestreet.com/technology/apple-might-have-a-wage-war-on-its-hands </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:44:18 </td>
   <td style="text-align:left;"> Wells Fargo price rating for $AAPL at $205 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:41:04 </td>
   <td style="text-align:left;"> $AAPL primed to get back to year high🚀🚀🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:38:55 </td>
   <td style="text-align:left;"> $AMD 
$NFLX should set their Q2 ER date to be behind the big hitters $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:38:45 </td>
   <td style="text-align:left;"> $AAPL tsla just killed all my put premiums for the rest of the week 💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:25:47 </td>
   <td style="text-align:left;"> $AAPL $TSLA are not the same by any means! Tech sector is still dead! EV company with Elon Musk in as CEO not quite. Not yet anyways! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:25:23 </td>
   <td style="text-align:left;"> $AAPL $TSLA $DIS We are broadcasting live tonight and y’all know we will be covering what you need to know to make the drip for the rest of the week. Make sure you are subscribed to our channel or catch it later on the YEA Network!

https://m.youtube.com/c/OptionsPlayerscom/videos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:24:03 </td>
   <td style="text-align:left;"> ✅(8-1) so far this week on signals❌
(CLOSED TODAY) 
🟢 $SPY PUTS 50% (risky)
🟢 $AAPL 18% (risky)
(4/20/22 RECAP)
Some nice plays today with some pretty wild market action. Markets all over the place but we riding out the storm well. Let’s keep it up y’all. Happy 420 live it up with some of those profits 💨

Join us today with the link below! 

https://discord.com/invite/aEvNt6mvyU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:23:47 </td>
   <td style="text-align:left;"> $TSLA $ETH.X $AAPL passing these down to my kids </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:21:16 </td>
   <td style="text-align:left;"> $DIS $TSLA $AAPL Tech bounce tomorrow- get ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:20:58 </td>
   <td style="text-align:left;"> $AAPL thank you tesla, 170$ calls will print tmrw $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:20:30 </td>
   <td style="text-align:left;"> $QQQ nasdaq down -20% on the year, i think we will break even this year. could be at a bottom here, but we shall see $SPY $IWM $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:18:41 </td>
   <td style="text-align:left;"> $TSLA $AAPL $NVDA $AMD $SPY 
Labor abuse right there  😑

https://www.google.com/amp/s/observer.com/2022/04/tesla-shanghai-gigafactory-resume-production-amid-covid-lockdown/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:17:16 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : From Tesla To Apple, Should You Buy The Same Stock Picks Favored By Millennials https://www.stck.pro/news/AAPL/26460095 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:15:56 </td>
   <td style="text-align:left;"> $AAPL NO JOKE…BIDEN SAID, “LEGAL IMMIGRATION IS DEAD, KEEP SOUTHERN BORDER OPEN”.  ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:15:29 </td>
   <td style="text-align:left;"> Many Death crosses: Stocks &amp;amp;Sector ETFs@Market👀possibly verge to🐻Mkt $AMD $QQQ $SPY $AAPL $PYPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:14:00 </td>
   <td style="text-align:left;"> $AAPL better cover shorties 🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:13:47 </td>
   <td style="text-align:left;"> $AAPL rip tomorrow higher on tesla 🚀🚀🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:12:18 </td>
   <td style="text-align:left;"> $AAPL Thank you Elon Musk!  🇺🇸❤️🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:11:24 </td>
   <td style="text-align:left;"> $TSLA  $AAPL $NIO 
Elon is worse than Putin.

In Shanghai, Tesla Workers Are Forced to Sleep on Factory Floors But Tesla Owners Don’t Seem To Mind
https://www.google.com/amp/s/observer.com/2022/04/tesla-shanghai-gigafactory-resume-production-amid-covid-lockdown/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:07:51 </td>
   <td style="text-align:left;"> $TSLA $AAPL $NVDA $AMD $SOXL 
Same issues for all devices companies.

&amp;quot;Recent Covid-19 outbreaks have been weighing on our supply chain and factory operations,&amp;quot; Tesla said. &amp;quot;Furthermore, prices of some raw materials have increased multiple-fold in recent months. The inflationary impact on our cost structure has contributed to adjustments in our product pricing.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:01:23 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-20 Chart Analysis Video: 
https://www.youtube.com/watch?v=oXCASgpAZWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 05:01:12 </td>
   <td style="text-align:left;"> $AAPL got in on some puts today . Small position. 30 puts .. Strike $165 exp 10/21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:55:21 </td>
   <td style="text-align:left;"> $AAPL 175 by the EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:53:15 </td>
   <td style="text-align:left;"> $AAPL who would ever sell their holdings in this company? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:50:43 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $VIX $TLT  
Economic Calendar -J Powell speaking tomorrow- 
https://www.financegreater.com/economic-calendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:36:28 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 201.7K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:34:14 </td>
   <td style="text-align:left;"> $AAPL they are literally giving handjobs to whoever helps them keep Apple under 170. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:26:13 </td>
   <td style="text-align:left;"> $AAPL But those $TSLA numbers! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:24:09 </td>
   <td style="text-align:left;"> $AAPL Powell tomorrow 💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:18:50 </td>
   <td style="text-align:left;"> $AAPL 
The Xiden administration is destroying the American economy and all the libturds can do is blame Putin. Gas has more than doubled in a year, inflation continues to rise and interest rates are only go higher. Remove the fraud and America will prosper again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:12:35 </td>
   <td style="text-align:left;"> $AAPL over $170 tomorrow 🚀🚀🤑😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:11:53 </td>
   <td style="text-align:left;"> $AAPL tomorrow close $175.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:11:24 </td>
   <td style="text-align:left;"> $AAPL 

Tesla big beats .. this shows that the economy still remain bullish … 

Look GDP expanded very strong .. despite inflation numbers!

So you should be afraid many other industries benefited from strong GDP growth! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:10:54 </td>
   <td style="text-align:left;"> $AAPL mother duckers cover or squeeze $170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:09:25 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Again dull battle in range. Leaving all overnight! Moment of silence for Bulls whos acc was wiped out. Maybe they will have chance to join us. We will be happy to see with us. Bears its not over yet. Cya tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:06:31 </td>
   <td style="text-align:left;"> $AAPL just follow the pattern📈📉📉📈📉📉📉📈📉📉📈📉📉📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:05:54 </td>
   <td style="text-align:left;"> $NFLX Wow.. Crazy drop today.. $QQQ $MSFT $AAPL  
 
I am getting out of Tech and Fang Stocks . Can&amp;#39;t handle the Pain  
  
Moving my money to Oil / Energy / Utilities / material stocks as War / Inflation / Higher rates has fuxxed the shxt out of tech stocks now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:03:33 </td>
   <td style="text-align:left;"> Wells Fargo Take on Apple, Qualcomm, MaxLinear Ahead Of Quarterly Earnings  $AAPL $QCOM $MXL 

https://newsfilter.io/a/28194f69ecb69aff99bcc5380a2aab0f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 04:02:38 </td>
   <td style="text-align:left;"> $AAPL    🍏 These are the “Wix &amp;amp; Stix” of panic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:58:05 </td>
   <td style="text-align:left;"> $AAPL Key News Update 
Apple retail workers in Atlanta file for a union election 
https://www.cnbc.com/2022/04/20/atlanta-apple-store-is-the-first-to-file-for-union-election-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:57:41 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Atlanta Apple store is the first to file for union election https://www.stck.pro/news/AAPL/26456337 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:57:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 26.38%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:56:54 </td>
   <td style="text-align:left;"> $AAPL up about 12% today so far on May $135 puts looking for multi hundred percent gain here 🍺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:56:51 </td>
   <td style="text-align:left;"> $AAPL 

You see massive shorting attack on NASD wide index ..

But Apple and Microsoft withstood better than the rest of NASD listed stock 

This shows that they are safe haven in wake of rising interest rates! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:51:06 </td>
   <td style="text-align:left;"> $AAPL Why would Buffett Invest $4B in a Printer company when he only spent $1B for Apple? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:50:49 </td>
   <td style="text-align:left;"> $AAPL that was quite the red candle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:49:56 </td>
   <td style="text-align:left;"> $AAPL 

See that’s why AAPL is winning market share on Phone category

https://www.tomsguide.com/opinion/i-just-switched-from-android-to-iphone-after-9-years-and-im-never-going-back?utm_content=tomsguide&amp;amp;utm_campaign=socialflow&amp;amp;utm_medium=social&amp;amp;utm_source=facebook.com&amp;amp;fbclid=IwAR1bu6-wkPOAh2CL6Zwg4m1WtdaYtO47FYBWtDFznXuwWx9aNCqa7u4gJrE#l27znj5adedbqox1e8u </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:49:43 </td>
   <td style="text-align:left;"> $AAPL  $170 🚀🚀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:49:40 </td>
   <td style="text-align:left;"> $AAPL ALL IN ON AAPL CALLS! long term PT $250! 

180 by the end of the month! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:49:20 </td>
   <td style="text-align:left;"> $aapl nice hold today while the rest of tech got killed lol! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:49:20 </td>
   <td style="text-align:left;"> $AAPL whole day it’s just been rejecting $168 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:48:42 </td>
   <td style="text-align:left;"> $AAPL News:Apple doesn&amp;#39;t make Printers Anymore!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:47:53 </td>
   <td style="text-align:left;"> $AAPL   🍏 Bears:  AAPL “diverged”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:44:00 </td>
   <td style="text-align:left;"> $SPY choppy day tryna flip options. Made money but my gut said $AAPL. Should have listened. Would have been a less stressful day. Lol

Go Irish! 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:41:56 </td>
   <td style="text-align:left;"> Apple Store Workers In Atlanta File For First Union Election 
 
Mastercard Shares Quiet Amid Report Apple Says Mastercard Cardholders May Not Be Able To Add To Apple Pay 
 
Amazon Europe Could Get Away With No Taxes In 2021 Despite $55B Sales: Bloomberg 
 
$AAPL $AMZN $MA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:38:18 </td>
   <td style="text-align:left;"> $ESSC inks a deal with ICONIQ MOTORS/W MOTORS via SPAC deal that brings $MSFT as a partner into the EV SECTOR. $AAPL APPLE CAR...???...pfff...watch out ELON...watch out $TSLA ... ICONIQ $ESSC &amp;amp; MICROSOFT $MSFT have just entered the race to the TOP OF THE EV SPACE. We knew good Ol&amp;#39; BILL GATES wasn&amp;#39;t gonna let Ol&amp;#39; BOY ELON keep that EV PIE all to himself. No wonder he had those latexd7f68149b612f36a51b349023bc3f80bESSC ⏰🚨 🎬📽🛫🛩✈🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:33:34 </td>
   <td style="text-align:left;"> latex9300ef86729c5e71e5608d24c0373f3cGOOGL  
$ORGN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:29:30 </td>
   <td style="text-align:left;"> $TSLA $AAPL $SPY sugar we&amp;#39;re going down swingin&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:29:06 </td>
   <td style="text-align:left;"> $AAPL theta killing these 170 calls. An hour ago, same price, it was .53 and barely cracking .44 at the same price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:26:57 </td>
   <td style="text-align:left;"> $AAPL the buy back is strong with this one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:26:13 </td>
   <td style="text-align:left;"> $AAPL hmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:23:26 </td>
   <td style="text-align:left;"> $AAPL June 165 puts. Going to run some diagonals on this through may opex </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:23:13 </td>
   <td style="text-align:left;"> $SPY are unions bullish $AAPL ????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:19:48 </td>
   <td style="text-align:left;"> $AAPL crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:18:50 </td>
   <td style="text-align:left;"> $AAPL  Timber $DIS $NFLX $FB $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:18:02 </td>
   <td style="text-align:left;"> $AAPL  Does $AAPL  need to get added to the inverse woke etf ? $DIS $FB  $TWTR  $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:17:31 </td>
   <td style="text-align:left;"> $AAPL $SPY standing with running thesis that market doesn&amp;#39;t bottom until AAPL tags its 100wk MA or deeper - 120 level is very realistic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:17:25 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple retail workers in Atlanta file for a union election, a first https://www.stck.pro/news/AAPL/26454592 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:16:10 </td>
   <td style="text-align:left;"> $AMD Tried to get on board buttttt..... $NVDA 

$AAPL $MSFT Cramer speaking this morning so presumptuous  didn&amp;#39;t help either </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:14:40 </td>
   <td style="text-align:left;"> $T LAST FORTY MINUTES BEFORE EARNINGS TMRW MORNING $AMC $GME $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:12:35 </td>
   <td style="text-align:left;"> $AAPL 170 call 📞 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:12:09 </td>
   <td style="text-align:left;"> $AAPL they’re just milking these 167.5 puts/calls huh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:11:09 </td>
   <td style="text-align:left;"> $AAPL I dont post much in here anymore but thank goodness apple is a staple in my portfolio. Other trash like arkk is in the gutter and apple is the slow and steady winner that you know will grow. So shout out to those that know what they own. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:09:31 </td>
   <td style="text-align:left;"> $AAPL all hail apple, the last hope in a sea of darkness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:06:30 </td>
   <td style="text-align:left;"> $SPY $AAPL is the best stock ever, no need to diversify </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:06:28 </td>
   <td style="text-align:left;"> $AAPL  This will hit back 170 in a few days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:03:46 </td>
   <td style="text-align:left;"> $AAPL 130k 170 strike expire Friday.  Hahaha suckers.  😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 03:00:06 </td>
   <td style="text-align:left;"> $AAPL I can’t believe Netflix is killing the market today. Never belonged with the FAANG group since it’s not even close to the kind of companies those all are. People really thought Netflix would never stop growing? It’s plain stupid. Netflix reminds me of Blockbuster Video years ago. It was the end all beat all until tech advancement and worthy competition killed it. Come on really? Netflix?  🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:59:49 </td>
   <td style="text-align:left;"> $QQQ this would be down 3% if it wasn&amp;#39;t for $AAPL and $MSFT keeping it buoyed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:58:31 </td>
   <td style="text-align:left;"> $SPY Sounds like Covid both killing more and spreading more from epicenter out as Wuhu, a city in neighboring Shanghai province Anhui in northwest just starting lockdowns. 

This could soon just emanate in a cloud burst to all 31 provinces, a domino infectious disease reaction.... 
Guangdong, the biggest seaport &amp;amp; 3rd biggest city (18M people) already hamstrung at ports w/ ships goods loaded stranded at sea.....

Folks, this is going to get worse before better.

O% chance Shanghai stops lockdown anytime soon with deaths now rising daily 

Tesla &amp;amp; Apple factories shut down indefinitely 
$QQQ $SOXX $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:58:24 </td>
   <td style="text-align:left;"> Investors Bailing on PayPal heading lower $PYPL possible new 52wk lows $AMD $QQQ $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:56:58 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Let the fall of rome begin.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:55:30 </td>
   <td style="text-align:left;"> $AAPL Is it  power hour or poorer hour??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:53:17 </td>
   <td style="text-align:left;"> $AAPL employees want to join a union for $30hr to sit on their ass and bullshit with ppl, just like McDonald’s wants $15hr to flip a burger 🤦🏻‍♂️ and y’all wonder why inflation is soaring. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:52:46 </td>
   <td style="text-align:left;"> $TSLA $AAPL need correction. . Hope both will be get healthy correction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:52:22 </td>
   <td style="text-align:left;"> $AAPL this is running like it’s on index, so much overvalued need to drop back to 120s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:51:48 </td>
   <td style="text-align:left;"> $AMD $NVDA $TSLA $AAPL $MSFT all the stocks looks cheap today after Netflix, everyone is dumping money buying short term calls options.  But they will bring the market down again tomorrow regardless if Tesla beats or not. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:47:05 </td>
   <td style="text-align:left;"> $AAPL $164 coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:47:04 </td>
   <td style="text-align:left;"> $AMD $NVDA $AAPL $TSLA $TWTR 

HERE COMES THE BOOOOOM 🚀📈🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:46:21 </td>
   <td style="text-align:left;"> $AAPL surprisingly holding up well compared to everything else </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:45:54 </td>
   <td style="text-align:left;"> $SPY When corporate world is making good profits and middle class getting screwed, that’s when fed killed this economy. Printing money to help Wall Street greeds which makes fundamentals less important $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:43:27 </td>
   <td style="text-align:left;"> $AAPL omg the new iPhones have better cameras wow I haven’t heard that one before … same old shit. Consumers are getting tired of paying 1k for the same phone 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:42:58 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMC $AAPL I am on fucking fire today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:42:03 </td>
   <td style="text-align:left;"> $AAPL 
Hello </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:41:38 </td>
   <td style="text-align:left;"> $aapl being weighed down by $fb $nflx $dis $tsla and other mega and large caps being down over 5% 
$nflx basically is 35 points on Nasdaqs 100 point fall today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:38:07 </td>
   <td style="text-align:left;"> $AAPL

One of the last to peak and likely one of the last to fall.

Needs the 100w reset like every other name in the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:37:16 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple store workers in Atlanta file for first union election - Bloomberg News https://www.stck.pro/news/AAPL/26453113 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:35:09 </td>
   <td style="text-align:left;"> $SPY $AAPL  *most option sweeps were short term..   
 now  see the #MAY PUT buyer showed up..   
Darkpool print, caution under level 167.  
 
crunchy crunchy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:34:49 </td>
   <td style="text-align:left;"> $AAPL If Tesla gets fucked apple going to pay for it too. Same china issues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:33:36 </td>
   <td style="text-align:left;"> $AAPL h&amp;amp;s on the 5min. Buy puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:29:35 </td>
   <td style="text-align:left;"> $AAPL this will be the last to fall but this is a huge consumer staple … how many new iPhones will people keep buying? Shits getting expensive this needs to compress another 20% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:23:28 </td>
   <td style="text-align:left;"> $AAPL what a joke of a stock. No returns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:23:11 </td>
   <td style="text-align:left;"> $FB Even $AAPL is not being affected with this dump(?). What’s wrong with this picture?  They are the real monopoly! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:22:40 </td>
   <td style="text-align:left;"> $AAPL  
 
6 Trading Days and way below 167.50  before EPS and huge underestimation of Services revenue? 
 
Stores packed? 
 
Seems like BS related to NFLX Bubble? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:22:39 </td>
   <td style="text-align:left;"> $AAPL FFS, just run up to where you were PM. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:20:39 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-20 Chart Analysis Video: 
https://www.youtube.com/watch?v=oXCASgpAZWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:20:05 </td>
   <td style="text-align:left;"> $AAPL $200 in no time watch and earn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:18:09 </td>
   <td style="text-align:left;"> $AAPL 83.75 would be fair </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:16:48 </td>
   <td style="text-align:left;"> $BAND Getting closer for 2022 revenue to be greater than entire market cap of company, makes you wonder 🤔 Usually any company with decent growth in revenue in this scenario would be a screaming BUY. $TWLO $TQQQ $AAPL $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:16:11 </td>
   <td style="text-align:left;"> $SPY $AAPL THANK U POTUS 😎😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:08:18 </td>
   <td style="text-align:left;"> $AAPL calls are burning up and decaying fast. Especially those Friday 170 calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:04:48 </td>
   <td style="text-align:left;"> $AAPL short this trash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:03:33 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #1 stock that institutions are trading with 36.6K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:03:24 </td>
   <td style="text-align:left;"> $AABB tradersgraghics showed up over a year ago spamming $AABB  2-3 months prior to ATH run from .025-.659 in only 4 trading days. When I looked tradersgraghics was spamming $TSLA $AAPL $GOOGL $MSFT and Blue Chips $AABB was the ONLY OTC and the run from .025-.659 was very TELLING!! Huggy Bear on (ihub) has a track record going back YEARS of bashing stocks OTC that all go parabolic eventually. The RSI is 19 with 3-4 Billion Uncovered &amp;#39;&amp;#39;naked short&amp;#39;&amp;#39; shares. LOADING ZONE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:02:46 </td>
   <td style="text-align:left;"> $AAPL did Mr. Chairman talk already? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:01:18 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 02:01:15 </td>
   <td style="text-align:left;"> $AAPL going back to $158 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:56:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:55:58 </td>
   <td style="text-align:left;"> $AAPL looking for a NFLX type move here for my latex5e8a391d918f44eb739042abdeaa66a0AAPL failed 168 
$MSFT failed VWAP 
 
 
watch these levels </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:50:53 </td>
   <td style="text-align:left;"> $AAPL this one is up and down like a roll a coaster today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:48:31 </td>
   <td style="text-align:left;"> leftover $AAPL 2 hours left. I&amp;#39;d rather be a bull. Its firming up nicely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:47:06 </td>
   <td style="text-align:left;"> $AAPL I don&amp;#39;t care how bearish anything is you just don&amp;#39;t short apple. Ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:46:36 </td>
   <td style="text-align:left;"> $NVDA $AAPL $TSLA $SPY All eyes on Tesla earnings today for tech, and really the market as a whole...meanwhile...I&amp;#39;m chilling with my $CDEV fam. 😎🍻 
 
We all know the TSLA Shanghai factory has been hit by the China lockdown, should be priced in...TSLA in red rn...but thicc green AH. TSLA won&amp;#39;t disappoint like NFLX did...at least not as much!🤣 
 
Tesla theme song: 
 
https://www.youtube.com/watch?v=H1HdZFgR-aA&amp;amp;ab_channel=SevenHip-Hop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:46:15 </td>
   <td style="text-align:left;"> $AABB $GOOG $AMZN $NFLX $AAPL $AABB RSI (19) with 2021 EPS +300% 107M in assets-Global cryptocurrency exchange- 5 Gold mines-3-4 Billion UNCOVERED &amp;#39;&amp;#39;naked short&amp;#39;&amp;#39; shares LOADING ZONE ROI  https://payaabb.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:45:29 </td>
   <td style="text-align:left;"> $SPY all they need to do is to prop ip $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:45:18 </td>
   <td style="text-align:left;"> $AAPL this is annoying. Just stay red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:44:51 </td>
   <td style="text-align:left;"> Do you agree with the A.I. prediction? $AAPL in Downtrend: Stochastic indicator is remaining in oversold zone for 6 days. View odds for this and other indicators: https://srnk.us/go/3596331 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:44:28 </td>
   <td style="text-align:left;"> As Netflix hemorrhages subscribers amid increased competition from Disney, Hulu, HBO, Amazon Prime and Apple — have we finally reached peak streaming?

$NFLX $DIS $AMZN $AAPL 

https://www.marketwatch.com/story/as-netflix-hemorrhages-subscribers-amid-increased-competition-from-disney-hulu-hbo-amazon-prime-and-apple-have-we-finally-reached-peak-streaming-11650475681?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:43:06 </td>
   <td style="text-align:left;"> $AAPL Apple Might Have a Wage War on Its Hands

https://www.thestreet.com/technology/apple-might-have-a-wage-war-on-its-hands </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:40:14 </td>
   <td style="text-align:left;"> $AAPL CHECK OUT (WHSI)!!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:38:22 </td>
   <td style="text-align:left;"> $SPY $MSFT latexcdfa9c0c736773351011635cfe08c919TSLA 566k (53% call/47% put)
$NVDA 432k (61% call/39% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:36:03 </td>
   <td style="text-align:left;"> $MSFT $TWTR $AAPL 
Pregnant Man Emoji </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:35:12 </td>
   <td style="text-align:left;"> $AAPL  $170🤑🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:33:03 </td>
   <td style="text-align:left;"> $AAPL 😆 🤣 

$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:31:30 </td>
   <td style="text-align:left;"> $AAPL is one of the top trending stocks on Stocktwits and Twitter, here are the latest numbers: 
 
 
11.59M Twitter Impressions 
1.57M Stocktwits Impressions 
 
 
LINK IN BIO to see real-time social sentiment trends, don&amp;#39;t miss out! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:29:08 </td>
   <td style="text-align:left;"> Peloton&amp;#39;s Latest Strategy to Save the Company Is the 1 Thing No Company Should Ever Do - Inc.

Does PLANET FITNESS still only charge $10.- per month for a membership including cardio and strength equipment? 

What monthly subscription fee for #ConnectedFitness  🖥 is actually SUSTAINABLE?

#mHealth
#RunToDaylight
#WalkwithWisdom
#BrainWarriorsWAY 
🌞🌎🌳🌻🤑🧠⚡️💓🚴🏻💨 
&amp;gt;https://gfycat.com/gifs/detail/SlipperyDangerousKouprey

$AAPL $LTH $PLNT $PTON $XPOF  https://apple.news/ALG0uyDWWTSCoWk_JtDAD9A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:28:46 </td>
   <td style="text-align:left;"> $SPY Hmm looking at the technicals.

I have the spy going to  444 EOD and potentially lower.

This market is being propped up with $JNJ and $AAPL atm to support the bond sell off on Netflix </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:27:55 </td>
   <td style="text-align:left;"> $SPY  Lazy bear volume flow $STUDY  is Breakout at the moment on the Daily 👍 This is just a study to see if there is follow through in correlation with the chart... $TSLA $AAPL $ARKK 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:27:40 </td>
   <td style="text-align:left;"> $QQQ latexe87f7411a78313d8defe24e83996cf7fTSLA 566k (53% call/47% put)
$NVDA 432k (61% call/39% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:20:29 </td>
   <td style="text-align:left;"> $AAPL $TSLA $NFLX Make sure you are subscribed to the OptionsPlayers YOUTUBE channel (click on link here)

 https://m.youtube.com/c/OptionsPlayerscom/videos  

Be sure to click the NOTIFY bell so you dont miss these episodes as they drop. They provide timely valuable info that you wont want to miss.
See you tonight 6:30pm with WNW! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:20:23 </td>
   <td style="text-align:left;"> $SPY $AAPL is pushing the market w/ a PE of 27 and YOY Growth Shrinking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:19:12 </td>
   <td style="text-align:left;"> $AAPL where do you thing the NFLX sale cash is going...funds are loading up on AAPL into the earnings news...Will pint 170+ very soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:17:03 </td>
   <td style="text-align:left;"> $AAPL clear 168 resistance and AAPL will print 170+ before the close today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:17:01 </td>
   <td style="text-align:left;"> $NFLX Here we go boys. . . ...    ok. ok.  $TSLA Here we go boys! Carry comming! $AAPL $DIS $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:16:42 </td>
   <td style="text-align:left;"> $AAPL get the Vaseline ready for the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:13:54 </td>
   <td style="text-align:left;"> $AAPL $SSNLF $COST stop investing in these risky small companies and invest in a much safer, much more promising $CLEU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:12:01 </td>
   <td style="text-align:left;"> $AAPL head and shoulders all over the place on different time increments.  This things F’D </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:11:42 </td>
   <td style="text-align:left;"> $NFLX $SPY 

Hedge funds rebalanced the spy here

Selling off Tesla $TSLA 
buying $NFLX 
selling $JNJ 
Buying $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:10:56 </td>
   <td style="text-align:left;"> $COIN its only 5x its p/e so it isnt a huge deal to not buy up here, vs buying those other very over priced stocks trading at 40x+ their p/e. But hey what do i know, not like fb and $msft and $aapl and $FB didnt have the same downturn from ipo and now look at their prices... keep chasing chidren and day traders :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:08:50 </td>
   <td style="text-align:left;"> $AAPL $MSFT $AMZN So which of these raging bubbles is going to pull a $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:07:07 </td>
   <td style="text-align:left;"> MAGA for $QQQ

$MSFT $AAPL $GOOG $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:07:01 </td>
   <td style="text-align:left;"> $AAPL 153 is the time to renter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:04:14 </td>
   <td style="text-align:left;"> $AAPL This stock is out of control and needs at least a 50% retracement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:03:52 </td>
   <td style="text-align:left;"> $AAPL https://originaltraders.io/ &amp;gt;check this out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:01:32 </td>
   <td style="text-align:left;"> $AAPL Here&amp;#39;s How Morgan Stanley Previews Apple Ahead Of Q2 

https://newsfilter.io/a/0a619b9d97b411eb3d42b0e8757ca46a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:01:32 </td>
   <td style="text-align:left;"> Here&amp;#39;s Why Citi Added Amazon To Focus List  $AMZN $SNAP $ABNB $DASH $AAPL 

https://newsfilter.io/a/1a139f2fd5c0d23f4ba745f57eed2c26 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 01:00:07 </td>
   <td style="text-align:left;"> $AAPL dollar gonna collapse soon or later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:59:30 </td>
   <td style="text-align:left;"> $NFLX $AAPL looks like Apple should make an acquisition. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:56:50 </td>
   <td style="text-align:left;"> $NFLX if a company of this size can drop 35% on earnings where the revenue and eps weren’t even that bad compared to the estimates, we are in trouble $SPY $AAPL $TSLA  inflation about to crush consumerism in so many industries when it doesn’t let up 

https://amp.cnn.com/cnn/2022/04/20/investing/premarket-stocks-trading/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:55:48 </td>
   <td style="text-align:left;"> $aapl $nflx    the time has come for all great companies to come together.   I have taken a position and looking for it to be bought out in &amp;lt; 2 years by apple  NFLX has the subscription based business the content and customers pieces that fit nicely  into the apple pie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:54:43 </td>
   <td style="text-align:left;"> $SPY $AAPL Apple heading towards green, melt up rest of day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:52:47 </td>
   <td style="text-align:left;"> $AAPL will be the next to fall. Yall getting too comfortable thinking this will keep going straight up forever. Imagine buying a $1200 wokeism telephone every year, when groceries are becoming a struggle for most. Reality will set in here too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:51:17 </td>
   <td style="text-align:left;"> $AABB $NFLX $DIS $AAPL $TSLA $AABB 2021 EPS +300% PRE (5) Gold mine acquisitions PRE Global cryptocurrency exchange (mobile app) with future NFT&amp;#39;s &amp;amp; Geothermal mining in El Salvador. Plans to up list on a Major Exchange with the estimation of 3-4 Billion UNCOVERED &amp;#39;&amp;#39;naked short&amp;#39;&amp;#39; shares https://payaabb.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:49:55 </td>
   <td style="text-align:left;"> $SPY I think $aapl will put out the worst numbers since Jobs not kiddin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:49:00 </td>
   <td style="text-align:left;"> $TSLA $BTC.X $QQQ $SPY $AAPL  
 all eyes on tsla after hours to move the whole market 
if that musk mofo even sneezes on Twitter, the market will move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:47:54 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:46:51 </td>
   <td style="text-align:left;"> $AAPL will apple and google be the next captains to fall?  I have substantial position in apple 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:46:51 </td>
   <td style="text-align:left;"> $SPY $tsla printed me $70/share from yesterday, I think $aapl is the dark horse forget $tsla. $aapl is in everyones fckn portfolio even if you don’t own any securities, it all ends with $aapl. OVER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:46:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA Risk back on in the market. Struggling VIX, wrong reading on netflix earnings. Pandemic stock coming back to normal is extremely bullish, as we are going back to normal. They are clearing our paper hand call holders today, risk is back on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:46:25 </td>
   <td style="text-align:left;"> $AAPL you want to sell before earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:45:40 </td>
   <td style="text-align:left;"> $AAPL how is cnbc today spinning the all doom and gloom , cnbc love that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:45:14 </td>
   <td style="text-align:left;"> NFLX down 35%+ $FB down 7%+  $TSLA down 4%+ $AMZN down 2%+ $AAPL down .5%+ 

HOW IN THE WORLD IS THE $SPY going red to green 🤦🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:42:14 </td>
   <td style="text-align:left;"> $AAPL $QQQ $NASDAQ 

LOL so dumb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:37:02 </td>
   <td style="text-align:left;"> $AAPL  Apr-29-22 172.5 Calls @ 1.45  
 
... trailing stop set near 166 (30 min candle) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:36:45 </td>
   <td style="text-align:left;"> $AAPL this is my trend line, with a chance of a death drop, of course, but less of a chance now with the drop to 150 already. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:34:07 </td>
   <td style="text-align:left;"> $NFLX cheap enough to be a buyout opportunity for someone like $AAPL or $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:33:59 </td>
   <td style="text-align:left;"> $AAPL
Does anyone know how to delete this stoopid pregnant man emoji ? I’m seriously going with Samsung when it comes time to upgrade. They don’t even recognize this emoji. Go woke go broke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:31:30 </td>
   <td style="text-align:left;"> $AAPL personally I think this was meant to be 170-175 going into thurs earnings, but is being drug down by Netflix. So I am buying calls until this pivots that way next couple days. all these little fudwhackers out today are about to be fucked. Buy calls for er runup and switch to puts mid next week against the grain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:31:15 </td>
   <td style="text-align:left;"> Some top bearish flow: $NFLX $NVDA $FB $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:30:30 </td>
   <td style="text-align:left;"> $AAPL market is dog shit!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:30:13 </td>
   <td style="text-align:left;"> Top Bullish Flow (a/o12:27pmEST): $AAPL $W $TSLA $CCJ $HD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:22:26 </td>
   <td style="text-align:left;"> $AAPL every chart looks like crap now. Wth aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:21:31 </td>
   <td style="text-align:left;"> $AAPL please buy calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:19:36 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:19:28 </td>
   <td style="text-align:left;"> $NFLX Who bought the dip yesterday? I cashed out all my stocks a few weeks ago, before the slow bleed. I knew any negative report would send stocks crashing, including $AAPL and $AMD and $NVDA . This will be PayPal 2.0. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:16:37 </td>
   <td style="text-align:left;"> $AAPL recession is coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:14:18 </td>
   <td style="text-align:left;"> $AAPL pregnant man emoji </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:13:49 </td>
   <td style="text-align:left;"> $AAPL is 20% decline in sells bullish? 

$SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:12:56 </td>
   <td style="text-align:left;"> $SPY inflation was just pent up demand with not everyone working ,, and russia &amp;quot;situation&amp;quot; just added to it.. inflation will come down on its own and fed will switch to a dovish tone to end the year $AAPL $NFLX $AMD $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:12:31 </td>
   <td style="text-align:left;"> $NFLX $AAPL $GOOG $FB 
Looks like FANG is now FAG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:12:15 </td>
   <td style="text-align:left;"> $T.CA offering a video bundle to its mobile customers for $25 per month. 
 
The bundle, dubbed Stream+, is available to new &amp;amp; existing Telus mobility customers and includes $NFLX Premium, $AAPL TV+ and $WBD Discovery+ on one monthly bill.  
 
Telus commissioned a survey that found almost half of Canadians use 3 or more streaming platforms and that 90% of Canadians would bundle if they could. 
 
At YE21 Telus had 9.29M mobile subs. The operator also sells internet service &amp;amp; its own pay TV services, finishing the year with 1.27M TV subs &amp;amp; 2.27M internet subs. Telus added 367K mobile phone subscribers in FY21, during which it gained just 50K TV subs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:11:45 </td>
   <td style="text-align:left;"> $AAPL  is a sell ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:11:40 </td>
   <td style="text-align:left;"> $AAPL They are suppressing the prices because they know everybody wants in here, AMD, NVDA, and PYPL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:11:15 </td>
   <td style="text-align:left;"> $AAPL yikes my 4/29 $175c not looking so hot rn 😮‍💨 who else is in on these </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:10:44 </td>
   <td style="text-align:left;"> $AAPL we want you. $GOOGL and you. Annnnddd $AMZN no more fake EPS growth with $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:10:32 </td>
   <td style="text-align:left;"> $AAPL 265 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:10:16 </td>
   <td style="text-align:left;"> $NFLX 5x your money with my call outs 😇🙏💯🚀 $TSLA $AAPL $AMD $NVDA https://youtu.be/wYsFluJbBAg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:10:10 </td>
   <td style="text-align:left;"> Chance to Score $1 Million 💰with latexe7da222ba3c33f1b8da76f2dcffbe227AMD ↗️ 

$AAPL $BTC.x $ETH.x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:10:07 </td>
   <td style="text-align:left;"> $WTRH short squeeze will happen💎💎🚀🚀 fair value much over 3 $

$AMC  $GME $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:07:32 </td>
   <td style="text-align:left;"> $SPY and $AAPL tracking each other pretty closely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:06:59 </td>
   <td style="text-align:left;"> $SPY people gonna be upgrading netflix like crazy in two quarters. stay ahead of the big money moves retail $NFLX $AAPL $AMD $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:05:40 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMZN $UNH $BRK.A if these go down then we are all screwed except the shorties </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:05:20 </td>
   <td style="text-align:left;"> $AAPL $97 to bring this back to PE16 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:04:56 </td>
   <td style="text-align:left;"> $AAPL I’m waiting for the one time they say what’s actually happening with the synchronous market movement across all sectors and indices, obviously not rates, yields or war…those are all baked in…just wanna see
Them say, “well, we just wanted to set the algo’s down and squeeze everyone out or into margin calls” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:04:49 </td>
   <td style="text-align:left;"> $NFLX come on over $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:04:43 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:02:03 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Berkshire Hathaway: Top Stock For A High Inflation Environment https://www.stck.pro/news/AAPL/26446599 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:01:45 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 29.6K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-21 00:00:39 </td>
   <td style="text-align:left;"> $AAPL Option to look at today.. 👀 👀  $170 Put for Friday, April 29, 2022. Roughly 631 Thousand dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-20 23:59:22 </td>
   <td style="text-align:left;"> $SPY I don&amp;#39;t think I&amp;#39;ve ever seen SPY green when $TSLA and $AAPL are both red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-20 23:58:43 </td>
   <td style="text-align:left;"> $NFLX $AAPL 
If yoy invest to these companies.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-20 23:57:39 </td>
   <td style="text-align:left;"> $GOOG  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-20 23:56:08 </td>
   <td style="text-align:left;"> $AAPL is less money bullish? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-20 23:56:06 </td>
   <td style="text-align:left;"> $AAPL nice,  666 lucky number </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-20 23:55:09 </td>
   <td style="text-align:left;"> $AAPL Looks like a Dog till next week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-20 23:55:00 </td>
   <td style="text-align:left;"> The industry average Profit Margin is 5.30%. $AAPL outperforms 90% of its industry peers. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-20 23:54:47 </td>
   <td style="text-align:left;"> $SPY this being green while $TSLA and $AAPL in the red. It could mean only one thing. Tesla’s ER will be terrible 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-20 23:54:16 </td>
   <td style="text-align:left;"> Kantar: There are 109.4M US households with subscriptions, as of December 2021 (85% penetration). The average household now uses 4.7 services on average. 
 
Video streaming quarter-on-quarter penetration growth is primarily coming from Free Ad-Supported TV (FAST) and Advertising-based Video On Demand (AVoD) tiers, with FAST growing 4.9 percentage points, AVoD 3.6 percentage points, and SVoD 1.8 percentage points quarter on quarter. 
 
18% of US households now use a FAST service, as of 4Q21. This has more than doubled year on year: household penetration was 8% in 4Q20. Within FAST, Peacock, IMDB TV, Tubi, and Roku Channel account for the greatest share of new users in 4Q21, collectively making up 79% of all new FAST users this quarter. 
 
$NFLX $DIS $PARA $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-20 23:54:15 </td>
   <td style="text-align:left;"> $AAPL what a shit show this morning, glad I doubled up on my puts. They be printing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:37:27 </td>
   <td style="text-align:left;"> $TSLA +$4.30 for the day. Would have expected better, but hopefully will calm parts of the market down tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:37:24 </td>
   <td style="text-align:left;"> $TSLA Don&amp;#39;t forget if bitcoin really is gonna be digital gold im sure that is gonna look real nice on Tesla&amp;#39;s balance sheet too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:37:11 </td>
   <td style="text-align:left;"> $TSLA not even up 1% for the day all that hype </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:37:01 </td>
   <td style="text-align:left;"> $TSLA AH 
https://share.trendspider.com/chart/TSLA/66828c0911 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:36:43 </td>
   <td style="text-align:left;"> $TSLA tomorrow when weeklies are printing and stocks keep falling this maybe the best savings account to avoid the pre-Fed meeting market wide sell off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:36:29 </td>
   <td style="text-align:left;"> $TSLA imagine the volume when giga Texas and Berlin start jumping out cars this year. The next 5 years going to be insane. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:36:16 </td>
   <td style="text-align:left;"> $TSLA buy as much as u can now..  car&amp;lt; fsd/robotaxi &amp;lt; Optimus.   Car will get us 10x.  Fsd/robotaxi another 10x.  Then Optimus another 10x. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:36:12 </td>
   <td style="text-align:left;"> $TSLA 

😱 😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:36:04 </td>
   <td style="text-align:left;"> $SHOP Cathie sold $TSLA to buy more of her losers. Woman’s lost her mind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:35:55 </td>
   <td style="text-align:left;"> Still short?! 
😂😂😂😂😂
$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:35:41 </td>
   <td style="text-align:left;"> $TSLA bears gonna be liquidated! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:35:10 </td>
   <td style="text-align:left;"> $TSLA 4/20 earnings report be like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:35:09 </td>
   <td style="text-align:left;"> $TSLA it beats top and bottom why it didn’t rally..? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:34:48 </td>
   <td style="text-align:left;"> $NIO Couple things to think about $TSLA the current price is still way above the COVID (Mar&amp;#39;2020) lows, and well above the Late February low. But is has been struggling to break over the VWAP from April 5th high, and remained below it. In the past 5 days it has been essentially zigzaging above/below the 5-day VWAP. It aligns with the Fib retracement from Feb 24 to Apr 5 . So for the past 3 weeks the price has been consolidating within a channel after a 16% drop in price. In the short time frame, it looks like a bear flag, but on the longer timeframe it looks like a bullflag. The worrying fact here is that the price did not break out of the last 6 day consolidation channel. Will wait to hear what tomorrow brings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:34:42 </td>
   <td style="text-align:left;"> $TSLA wow, some of these bears are in such denial. I&amp;#39;ll certainly be looking to buy some more tomorrow, but will probably jump up again in PM before I get the chance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:34:04 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-20 Daily Forecast Video: 
https://www.youtube.com/watch?v=6lW9LuG2p4U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:34:01 </td>
   <td style="text-align:left;"> Today $TSLA shows BUY signal (TA) for short term. Technical analysis source: https://stockinvest.us/stock/TSLA?utm_source=stocktwits&amp;amp;utm_medium=autopost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:33:22 </td>
   <td style="text-align:left;"> $TSLA lol is covid over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:33:21 </td>
   <td style="text-align:left;"> $TSLA Elon does what he says and believes in. Imagine if Bot and Robotaxi come true in couple years, these prices gonna look like bargain of century </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:32:49 </td>
   <td style="text-align:left;"> $TSLA Head and shoulders forming on the dma </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:32:47 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/udrZ0VVobDQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:31:26 </td>
   <td style="text-align:left;"> $TSLA 1200 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:31:10 </td>
   <td style="text-align:left;"> $TSLA This don&amp;#39;t look good for the beartards among us! Do it! 
https://finance.yahoo.com/news/tesla-notches-record-profit-sees-000529793.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:30:35 </td>
   <td style="text-align:left;"> $TSLA 30% plus margin in auto industry is crazy, zero $$ spent on advertising, ability to increase prices when conditions required. CEO is himself advertising machine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:30:31 </td>
   <td style="text-align:left;"> $TSLA Nuff said </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:30:30 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:30:29 </td>
   <td style="text-align:left;"> $TSLA Earnings only proves that this is still not a trillion dollar company. Pretty weak pump ah on earning beat(only erased the days loss). Kinda easy to beat earning when you don&amp;#39;t offer guidance. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:28:48 </td>
   <td style="text-align:left;"> $TSLA Biden be like « You led Mary, and it matters » </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:27:31 </td>
   <td style="text-align:left;"> $TSLA TESLA SAYS FACTORIES LIKELY TO CONTINUE TO RUN BELOW CAPACITY THROUGH REST OF 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:26:28 </td>
   <td style="text-align:left;"> $TSLA Better to have small shares of a winner than 1,000 shares of a penny/loser stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:25:48 </td>
   <td style="text-align:left;"> $TSLA $VENAR Don&amp;#39;t know what to do, just follow the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:25:17 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:25:10 </td>
   <td style="text-align:left;"> $TSLA FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:24:54 </td>
   <td style="text-align:left;"> $TSLA i hope you all your calls have an intrinsic value of at least the premium you paid by open tomorrow.else just cut the loses before IV crush in the first hour </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:24:38 </td>
   <td style="text-align:left;"> $TSLA Tesla will tank tomorrow. Profit taking for sure. Elon needs the liquidity to buy $TWTR 

You know Elon likes to disclose transactions after the check clears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:24:12 </td>
   <td style="text-align:left;"> $TSLA Imagine what this company will do in non pandemic and normal conditions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:24:07 </td>
   <td style="text-align:left;"> $TSLA 1050 OTM call strike should hold for now. sell the 1050/1055 call spread at the open for a trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:23:33 </td>
   <td style="text-align:left;"> $NIO The production and deliveries at $TSLA has been known since April 2nd. A healthy head could have calculated the revenue close enough to what was reported today. Therefore, people were counting on the guidance and forecast from Elon and company. The Q2 has been stated to be expected low. Depends where you read, its going to be between 40k to 90k lower, which translates to 13 to 29% lowered production counts. Q3 and Q4 are expected to be strong. The current price of $TSLA is based on future forecast, not past performance. With Q2 expected to be lower, but possibly not as low as 2021Q2. Be diligent with tomorrow&amp;#39;s trading, as the price can go either way, depends on how the market will factor in these figures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:23:19 </td>
   <td style="text-align:left;"> $TSLA pump this to $1200 tomorrow. I will thank you. 

“Challenges around supply chain have remained persistent, and our team has been navigating through them for over a year. In addition to chip shortages, recent COVID-19 outbreaks have been weighing on our supply chain and factory operations. Furthermore, prices of some raw materials have increased multiple-fold in recent months.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:23:15 </td>
   <td style="text-align:left;"> $TSLA if you got puts you got cooked so stop hating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:22:57 </td>
   <td style="text-align:left;"> Elon Musk has scored $23 billion in new compensation from a strong quarterly report $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:22:55 </td>
   <td style="text-align:left;"> $TSLA any hope for puts tomorrow :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:22:40 </td>
   <td style="text-align:left;"> $TSLA  China and Russia will team up  for battery raw materials its the future Biden better get his ass in gear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:22:04 </td>
   <td style="text-align:left;"> $TSLA  so guidance is for  over 50 percent growth for the next 5 years ! 
 
no other company is this strong with this much forecasted  growth ! 
 
 
🚀 🌝 tomorrow….best prices in the AM ad usual </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:21:58 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:21:49 </td>
   <td style="text-align:left;"> $AMD Don&amp;#39;t forget ya&amp;#39;ll... 
 
&amp;quot;Last year it was announced, and subsequently confirmed through model numbers, that the Tesla infotainment systems in the Model X and Model S are using AMD’s embedded platform to drive the display and graphics in those vehicles. Our understanding is that the first versions of that silicon in those vehicles are based on Zen plus Vega, so I asked Dr Su about what she meant by RDNA2 being in automotive solutions. Beyond that, I also asked about the AMD and Tesla relationship.&amp;quot; 
 
https://www.anandtech.com/show/17198/amd-expanding-into-tesla-model-3-and-model-y 
 
$TSLA  
 
#BULLISHAF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:21:49 </td>
   <td style="text-align:left;"> $TSLA SHE GOT A DONKKKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:21:47 </td>
   <td style="text-align:left;"> $TSLA Despite Economic conditions and shortages.. Tesla’s earnings were freaken fantastic,and again …those profit margins !!OMG!..Makes me want to sell all my other stocks and just add more Tesla.. as I did today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:21:38 </td>
   <td style="text-align:left;"> $ARKK $ARKW Just a reminder: Whenever you see a trade, it’s T+2 meaning it “could have” been 1-2 days ago the trade SETTLED. $TSLA spiked to $1031 earlier this week and it exceeded 11% weight in ARKK. Rules are Rules. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:21:36 </td>
   <td style="text-align:left;"> $TSLA you guys realize u made a round trip on spectacular er beat? This may mark the top in an odd way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:21:36 </td>
   <td style="text-align:left;"> $TSLA at 50% yoy growth takes 5 years of perfect execution to catch GM sales numbers. 

GM Marketcap is $0.06T
TSLA Marketcap is $1.00T

That&amp;#39;s 166x more expensive and 5 years behind!

Lol, reality matter sooner or later. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:21:22 </td>
   <td style="text-align:left;"> $TSLA I am getting bored of Tesla especially the Car </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:20:51 </td>
   <td style="text-align:left;"> $TSLA I am looking at $1100 break and $1150. PM should be interesting. Futures is green as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:20:45 </td>
   <td style="text-align:left;"> $TSLA riding the 50ma… didn’t explode after hours, providing opportunity for mutual/index funds to support and load tomorrow AM, should be a healthy 7% day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:18:56 </td>
   <td style="text-align:left;"> $TSLA When Cathie sells, I buy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:18:45 </td>
   <td style="text-align:left;"> $TSLA pm squeeze this to $1200 no mercy for shorts now!🤡🐻💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:18:32 </td>
   <td style="text-align:left;"> $TSLA MM to retail </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:18:24 </td>
   <td style="text-align:left;"> $TSLA the value of net worth increases your self worth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:18:09 </td>
   <td style="text-align:left;"> $TSLA Tokenized at $1043 should print $1100 tomorrow after that blowout. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:17:59 </td>
   <td style="text-align:left;"> $SNAP $NFLX $TSLA  
 
Its a &amp;quot;Sell the News&amp;quot; earnings season so far. You have a Rev - MISS &amp;amp; loss of subs / EPS - BEAT  with Netflix&amp;#39;s stock price plummeting -35%. 
 
Whereas Tesla has a massive EPS - BEAT / Rev - BEAT and the stock price jumps only +4% in AH?  
 
What does that tell you...? 
 
It tells me at least right now WS has already priced in any sort of positive ER and any sort of MISS whatsoever will most likely send the stock price absolutely plummeting. You also have the overall S&amp;amp;P 500 in a downtrend at the moment.  
 
Retail most likely loading CALLS on this SNAP earnings call because &amp;quot;it went up +60% last quarter so it&amp;#39;ll happen again&amp;quot;.  
 
That gives us a lot of ammo to decide most likely to go with &amp;quot;PUTS&amp;quot;. Also, the trend of SNAP is absolutely water falling just like Netflix. Literally the same chart essentially. Yes, (2) different businesses, but the technicals are both there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:17:32 </td>
   <td style="text-align:left;"> $TSLA did he say 20-30% cost increase in raw materials? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:17:06 </td>
   <td style="text-align:left;"> $TSLA  still think they need a dating app for the super chargers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:17:03 </td>
   <td style="text-align:left;"> $TSLA 1 trillion in valuation and not one dollar spend on advertisement nobody talks about that.  #musktakeover </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:16:51 </td>
   <td style="text-align:left;"> latex682b2d5369d1ed03264c997597e75fd6 tomorrow in pre market, i&amp;#39;m 100% convinced it squeezes UTTERLY HARD. like im thinking almost an instant 3$... just my opinion... tooooo much hype behind $MULN and EV!!!! $EVGO $NIO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:16:47 </td>
   <td style="text-align:left;"> $TSLA I think MUSK is cooking the books to hold up the stock price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:16:04 </td>
   <td style="text-align:left;"> $TSLA Any news on self driving? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:15:39 </td>
   <td style="text-align:left;"> $TSLA DOESN’T even have to spend money on advertising. The product sells itself. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:15:28 </td>
   <td style="text-align:left;"> $TSLA DAF bears gonna be liquidated when the margin calls hit their accounts on Fry Day!

SIKE!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:15:06 </td>
   <td style="text-align:left;"> $TSLA so where does this go by tomorrow/next week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:14:28 </td>
   <td style="text-align:left;"> $TSLA Okay bears. We ended the day green after all. Wanna try again tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:14:18 </td>
   <td style="text-align:left;"> $TSLA 80% INCREASE ON SALES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:13:49 </td>
   <td style="text-align:left;"> Kill all that noise about $TSLA having competition. They’ll all fail </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:12:46 </td>
   <td style="text-align:left;"> $TSLA Tesla has raised their car prices to reflect where they see inflation affecting their costs 2years into the future  
 
what other manufacturers is thinking past next quarter? 
 
 
ATH coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:12:08 </td>
   <td style="text-align:left;"> $TSLA to many bulls.. we know what that means </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:11:54 </td>
   <td style="text-align:left;"> $TSLA For a limited time, we are opening our trading chat-room to the public.  http://besttradeplace.epizy.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:11:52 </td>
   <td style="text-align:left;"> $TSLA my portfolio went from red to green real fast... Thank you Tesla. 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:11:37 </td>
   <td style="text-align:left;"> $TSLA Tesla perma bull is saying 2.5m cars delivered next year.  They have capacity for 2m.  🤷‍♂️.  Where are the other 500k cars coming from.   😂

2024 deliveries of 4m…they would need 4 more factories to come online in the next 18 months to hit that.  Are you fn kidding me….😂

The biggest pump of all time…wake up idiots. 

https://twitter.com/garyblack00/status/1516943383809474561?s=21&amp;amp;t=azr9WzyAUAzI1p09lPnjJg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:10:37 </td>
   <td style="text-align:left;"> $TSLA bulls probably think food grows in the super market. Keep buying the bubble. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:10:33 </td>
   <td style="text-align:left;"> $TSLA is it safe to say that 4/29 otm options will gain value, I’m certain that 4/22 options will probably expire worthless but the theta doesn’t outweight delta so, shouldn’t they be green? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:10:25 </td>
   <td style="text-align:left;"> $TSLA  musk says they have included Inflationary pressures on their inputs  and that Teslas selling prices are inflation proof  2 years into the future  
 
💥 ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:10:12 </td>
   <td style="text-align:left;"> $TSLA $SPY 

Elon in his bag. Flexin on em </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:10:08 </td>
   <td style="text-align:left;"> $TSLA Anyone else have a price target 🎯 to become a Teslaire? Mine is $1,525.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:08:58 </td>
   <td style="text-align:left;"> $TSLA 

https://m.youtube.com/watch?v=rPw1hh-CQzg&amp;amp;feature=youtu.be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:08:35 </td>
   <td style="text-align:left;"> $TSLA best advice to someone trying to build funds to make options plays on bigger stocks like this one? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:08:19 </td>
   <td style="text-align:left;"> $TSLA post market earnings reaction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:08:13 </td>
   <td style="text-align:left;"> $TSLA I have 1100 strike call next week...will it be in profit...should I close at open or wait for few days..I&amp;#39;m confused..please help me.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:07:54 </td>
   <td style="text-align:left;"> $TSLA and yet margins are up.  What the fck is going on.   This some shady ass shxt.  🤷‍♂️🤡

https://twitter.com/marketrebels/status/1516903863906930688?s=21&amp;amp;t=azr9WzyAUAzI1p09lPnjJg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:07:47 </td>
   <td style="text-align:left;"> $TSLA re-do tweet/post -- now that board is quiet &amp;amp; many gone zzz 
 
 
 
$TSLA 
 so far no 126+/- -- AH ended up being a nothing burger. down 51 &amp;amp; up around 50 AH. lol -- don&amp;#39;t like playing earnings on this one -- forgot it was today. lol  
  
anyhow -- LEARN to S.Q.U.A.R.E. Price and +/- 0.325 &amp;amp; +/- 0.625 and RE-square &amp;amp; you get the major supports/resistance by using 0.325 &amp;amp; 0.625 levels.  
it&amp;#39;s good to write down in your own handwriting -- every day data on any stock &amp;amp; then calculate the next days levels squaring price and +/- 0.325 &amp;amp; +/- 0.625 and then re-squaring. you&amp;#39;d be surprised how easy it is :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:07:40 </td>
   <td style="text-align:left;"> $TSLA short squeeze to the moon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:07:34 </td>
   <td style="text-align:left;"> $TSLA Elon Musk Says Tesla Likely To Make Over 1.5M Cars This Year 

https://newsfilter.io/a/3598d6687002297cb580cc2e929e6735 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:07:21 </td>
   <td style="text-align:left;"> $SPY $TSLA  Tesla we played it well today. Puts printed. All cash EOD watching for fresh entries tomorrow $QQQ $SHOP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:07:13 </td>
   <td style="text-align:left;"> $TSLA FK, out of stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:07:08 </td>
   <td style="text-align:left;"> $TSLA if the volatily crushed to 60 percent tomorrow. Here is what i am getting for 1150 calls. It needs to go over 1120 to start printing. 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:07:01 </td>
   <td style="text-align:left;"> $TSLA I have 1100 strike call next week...will it be in profit...should I close at open or wait for few days..I&amp;#39;m confused..please help me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:06:14 </td>
   <td style="text-align:left;"> $TSLA get the duck out bears! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:06:09 </td>
   <td style="text-align:left;"> $TSLA imagine the feeling of owning yolo puts 😂 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:05:22 </td>
   <td style="text-align:left;"> $AAPL $AMZN $GOOG  
 
Now which one of you is going to fall on earnings? 🤔 
 
$SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:05:17 </td>
   <td style="text-align:left;"> $TSLA Apr 20               
Sell               
◆ Search for 10 day stock forecast by pretiming A.I               
http://www.google.com/search?q=10+day+stock+forecast               
◆ Forecast of Upper~Lower price range band for the next 10 days               
Price: 891.27   ~ 980.34            
% Change: -8.79%  ~ 0.32%           
The Buy-Sell strength has changed from a strong buying flow to a suddenly strengthening selling flow and it&amp;#39;s about to begin a downward trend as a rebounding trend gradually gives way to increasing limited rises and strong falls in the falling section. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:04:56 </td>
   <td style="text-align:left;"> $TSLA iron condors was the move here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:04:32 </td>
   <td style="text-align:left;"> $TSLA $TWTR elon musk trying to save the world or create new world order to enslave humanity? He is a former World Economic Forum Young Global Leader,  Klaus Schwab with great reset. $SPY $PFE 
 
https://www.bloomberg.com/news/articles/2008-03-17/young-global-leaders-anderson-cooper-and-leonardo-dicaprio-are-in-the-most-exclusive-private-social-network-in-the-world-dot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:04:21 </td>
   <td style="text-align:left;"> $TSLA red tomorrow. Bet your life on it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:04:16 </td>
   <td style="text-align:left;"> $NFLX If it is true that Bill Ackmann&amp;#39;s Pershing Square sold all his  
$NFLX position, then hats off to him. It takes a lot of courage to admit being wrong as they often say &amp;quot;First lost might be the best lost.&amp;quot;  But then again, he might have learned a thing or two from David M. Einhorn for being stubborn shorting $TSLA and becoming a millionaire from a billionaire. GLTA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:03:45 </td>
   <td style="text-align:left;"> $TWTR $TSLA Funding secured </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:03:43 </td>
   <td style="text-align:left;"> $TSLA how much we going up tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:03:38 </td>
   <td style="text-align:left;"> $TSLA the return will be real </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:03:36 </td>
   <td style="text-align:left;"> $TSLA red close tomorrow guaranteed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:03:17 </td>
   <td style="text-align:left;"> $SPY Anyone else get the idea that Powell sees the unenthusiasm and virtually boring stock market &amp;amp; just finally tells it to Wall Street straight that inflation is going to go nuts if we don&amp;#39;t high consider a 0.75% hike like Bullard just stated he wanted to do &amp;amp; then we need to really reduce the balance sheet in May, rapidly, like Lael wants to do.

Anyone else think Powell just goes ultra-aggressive suddenly because he realizes that&amp;#39;s the proper QE toolbox move &amp;amp; &amp;quot;maybe I shouldn&amp;#39;t say this but I&amp;#39;ve been influenced by Biden &amp;amp; other members to vote unlike I really should so economy not crash &amp;amp; cause recession quickly but maybe it&amp;#39;s what we need now to restart growth. Pain now, gain later. Otherwise, I don&amp;#39;t do it, we could see 17% real inflation &amp;amp; 12-14% CPI jump by the 4th (of July).&amp;quot; 

Wouldn&amp;#39;t that be some kind of rabbit pulled out of the hat, bulls? 

Baboooom $TSLA $QQQ $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:03:14 </td>
   <td style="text-align:left;"> $TSLA when do we get to Know price targets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:03:05 </td>
   <td style="text-align:left;"> $TSLA thoughts on tomorrow? sideways type of day its looking like? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:02:55 </td>
   <td style="text-align:left;"> $TSLA yall ate that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:02:48 </td>
   <td style="text-align:left;"> $TSLA https://www.teslarati.com/tesla-robotaxi-specs-details-elon-musk/ 🏎🚀🤖🔋📡🛰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:02:23 </td>
   <td style="text-align:left;"> $SPY $ARKK $TSLA  Cathie as usual doubling down on her losers and selling the winners. Surprised she didn’t buy any Netflix today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:02:04 </td>
   <td style="text-align:left;"> $TSLA don’t bet agains Elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:01:54 </td>
   <td style="text-align:left;"> $TSLA calls and puts destroyed glad I sold my 800puts before close. Now that’s how u play Tsla earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:01:53 </td>
   <td style="text-align:left;"> $TSLA 2 Electric Vehicle Stocks You Can Buy and Hold for the Next Decade✨✨💎💎🚀🚀
https://www.fool.com/investing/2022/04/20/2-electric-vehicles-stocks-you-can-buy-and-hold-fo/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:01:42 </td>
   <td style="text-align:left;"> $TSLA 🤮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:01:34 </td>
   <td style="text-align:left;"> $TSLA I was hoping for a Netflix day on these poots 💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:01:23 </td>
   <td style="text-align:left;"> Tesla announces earnings. $3.22 EPS. Beats estimates. $18.76b revenue.  https://www.marketbeat.com/s/559054 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:00:29 </td>
   <td style="text-align:left;"> $TSLA got a 1200 call now i am Stressing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:00:16 </td>
   <td style="text-align:left;"> $TSLA garbage.   I will never own an overpriced piece of crap.   BMW or if a truck then Ford.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 09:00:15 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla&amp;#39;s Earnings Crushed Expectations Despite Inflation. The Stock Is Up. https://www.stck.pro/news/TSLA/26463761 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:59:38 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/teslapodcast/status/1516883905038716929?s=21&amp;amp;t=ymIUC7ut5AOw4V6jF4GmBA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:59:35 </td>
   <td style="text-align:left;"> $TSLA 1500 opening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:59:23 </td>
   <td style="text-align:left;"> $TSLA I’m so confused right now about the fn stock market 😂 go 📈 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:59:10 </td>
   <td style="text-align:left;"> $TSLA look at bitcoin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:58:24 </td>
   <td style="text-align:left;"> $TSLA did hackman buy tesla or what </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:58:23 </td>
   <td style="text-align:left;"> $TSLA okay y’all had your little fomo deadcat bounce time to bring her down to reality tech analysis is king end of day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:58:09 </td>
   <td style="text-align:left;"> $TSLA once again carrying the market on its back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:58:07 </td>
   <td style="text-align:left;"> $TSLA $SPY $TWTR 

Elon seems to have  his funding secured to buy $TWTR AH based on Tesla stock UP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:57:54 </td>
   <td style="text-align:left;"> $TSLA Could be lookin to fill the gap at $1086 tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:57:45 </td>
   <td style="text-align:left;"> $TSLA $SNAP $NFLX Tesla has a fcking mega BEAT and the stock price moves + 4% in AH bahahah. 

What happens to every other tech company that beats mildly or misses…?

Anyone care to guess what WS is going to do to those companies…? Look no further then Netflix.

This earnings season so far is a “Sell the News” event. Yikes! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:57:10 </td>
   <td style="text-align:left;"> $TSLA  unless we see an 8-9% day - all calls between 1050 and 1080 will barely breakeven. And calls above that will be losing quite some value.

I have couple of 980c 4/22 and 50 1200c 4/29 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:56:25 </td>
   <td style="text-align:left;"> $TSLA wonder what that opening is going to look like 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:56:14 </td>
   <td style="text-align:left;"> $TSLA Beautiful results, Tesla! Question: which will 3x sooner, $TSLA or $FGI? If the goal is maximal profit, investing in toilets is an interesting play... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:54:39 </td>
   <td style="text-align:left;"> $TSLA All time high incoming 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:54:16 </td>
   <td style="text-align:left;"> $TSLA 

So they shorted 10+M shares at $1031 covered only 3M n SP is at $1031 so 7M+ shares are still shorted !  

Let’s do a little math how these dumb clowns will try to cover then re-open another short position to recover losses! 

If y’all hold -their losses can be north of 400M at least and this can squeeze initially to $1092-$1100 !! Big dogs won’t come in right away may be next week !! 

Either way they discounted these shares with the assumption Tesla is just another busted growth story competition already killing them ! Yep a lie they fabricated and believed !! Dumb! Very! 

Stay tuned for my final market report on their losses! 🤣🤣

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:53:36 </td>
   <td style="text-align:left;"> $ZIM Finally, somebody is recognizing the technology advantages that ZIM has against its competitors!  Maybe now they&amp;#39;ll trade more like a technology stock and get more than a 1.6X P/E (industry average is 4) 
 
$ZIM $SPY $TSLA $TWTR 
 
https://www.youtube.com/watch?v=LMyinaRKNiE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:52:52 </td>
   <td style="text-align:left;"> $BABA closed under 90 today. No one else gives you precise targets with deadlines… for free. $TSLA $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:52:31 </td>
   <td style="text-align:left;"> $TSLA buy after retest you dummies!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:52:24 </td>
   <td style="text-align:left;"> News $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:50:48 </td>
   <td style="text-align:left;"> $TSLA Clearly beating on margin and revenue. Bullish for sure. But its solar is now 1/10 the deployments SolarCity did. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:50:33 </td>
   <td style="text-align:left;"> $TSLA is the future of vehicles. $1200 coming very fast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:50:30 </td>
   <td style="text-align:left;"> $TSLA you see how small is the gains just 5% absolute joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:50:23 </td>
   <td style="text-align:left;"> $TSLA  is the split still on the table? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:49:50 </td>
   <td style="text-align:left;"> $TSLA really fken crushed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:49:46 </td>
   <td style="text-align:left;"> We are supposed to believe a downgrade for $AMD is justified for an alleged slowdown in pc sales $TSLA 
https://www.anandtech.com/show/17198/amd-expanding-into-tesla-model-3-and-model-y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:48:13 </td>
   <td style="text-align:left;"> $TSLA 

... Can&amp;#39;t wait to
Buy them IV crushed calls
So they can just pump
Them back up!!!

WATCH!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:47:48 </td>
   <td style="text-align:left;"> $AAPL lol every week the same optimistic people saying apple is going up.  Tomm maybe up to 171.00 pm  but like always,  it will fall back to 165.00. Mr.Money Printer Jerome will be speaking so you already know that’s gonna tank all stocks. Any chance hedges can they will tank the stock. Now if eveyone bought put at 170 or 171….maybe it will go up…$spy $NVDA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:47:45 </td>
   <td style="text-align:left;"> $TSLA this should make me money tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:47:38 </td>
   <td style="text-align:left;"> $TSLA Tesla about to crush ICE to dust, so much room to grow while the Dinosaurs at GM etc end up extinct from not being able to adapt fast enough… supercharger network alone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:47:25 </td>
   <td style="text-align:left;"> $TSLA Shorts claiming everything from fraud to alien abductions as necessary. Pathetic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:47:08 </td>
   <td style="text-align:left;"> IV Crush tomorrow&amp;#39;s EOD $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:47:00 </td>
   <td style="text-align:left;"> $TSLA from what i remember, when cathy sells tsla it usually pumps the next day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:46:51 </td>
   <td style="text-align:left;"> $TSLA 😏https://youtu.be/aXj7YZcsank </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:46:27 </td>
   <td style="text-align:left;"> $TSLA forever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:46:21 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:46:13 </td>
   <td style="text-align:left;"> $TSLA Life changing and world changing company and stock. Long! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:45:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA Huge squeeze incoming tomorrow? Bigly bull gains to be made, poor shorts/bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:44:59 </td>
   <td style="text-align:left;"> $TSLA the fact these earnings where beyond great and it barley broke daily high worries me greatly. If spy futures dump 1+%; it’s goin to be trouble . They might let’s this bitch chop to kill both calls and puts. Wel see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:44:27 </td>
   <td style="text-align:left;"> $MULN  🚀🚀🚀🚀🚀🚀🚀🚀 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:44:16 </td>
   <td style="text-align:left;"> $TSLA $1500 end of the summer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:43:59 </td>
   <td style="text-align:left;"> That means stay long $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:43:56 </td>
   <td style="text-align:left;"> $TSLA bears if we clear 1055 tomorrow you bitches are really over and I’ll definitely be screwing the fuck out of your wives. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:43:36 </td>
   <td style="text-align:left;"> $TSLA Elon is one of the best leaders in our generation, idk who would bet against him. Great job Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:43:16 </td>
   <td style="text-align:left;"> $TSLA  1200 at bell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:43:15 </td>
   <td style="text-align:left;"> $TSLA ATH tomorrow 
Any split news ?? 
10-1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:43:10 </td>
   <td style="text-align:left;"> $ARKK: &amp;quot;We believe $TSLA will be a $5 Trillion Company by 2026&amp;quot;

Also $ARKK: *Sells 64000 Shares&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:43:08 </td>
   <td style="text-align:left;"> $SPY going up from here $TSLA  beat earning 🍾🍾🍾🍾.  Tomorrow we rip!!! 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:42:44 </td>
   <td style="text-align:left;"> $TSLA $TSLA  Next up: stock split announcement (proxy statement by end of April). To the Mars! ⚡️⚡️💫

https://twitter.com/garyblack00/status/1516920533975240706?s=12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:42:24 </td>
   <td style="text-align:left;"> $TSLA does anybody know how high 1150 calls expiry 22 april will go? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:42:17 </td>
   <td style="text-align:left;"> $TSLA retail is getting smarter. MMS could be in trouble soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:41:56 </td>
   <td style="text-align:left;"> $TSLA I’m retiring early on my island </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:41:32 </td>
   <td style="text-align:left;"> $TSLA Institutions will bail tomorrow. No clear guidance, cost pressures will remain in the coming quarters, and lack of upcoming catalysts in the wake of further market deterioration. 
 
Expect this to behave like Q4 earnings, in which there was a massive red candle after blowout ER. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:41:31 </td>
   <td style="text-align:left;"> $TSLA 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:40:46 </td>
   <td style="text-align:left;"> $TSLA how high can 1150 can go tomorrow any idea? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:39:59 </td>
   <td style="text-align:left;"> $SPY $TSLA https://www.cnbc.com/2022/04/20/elon-musk-inflation-worse-than-reported-likely-to-last-through-2022.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:39:58 </td>
   <td style="text-align:left;"> $TSLA ouch how sad options are getting crushed regardless of what side you chose  
 
very impressive for this just to return back to yesterdays closing price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:39:49 </td>
   <td style="text-align:left;"> $TSLA this is me looking at my account: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:39:29 </td>
   <td style="text-align:left;"> $TSLA barely green. Don’t know why bulls have been so crazy today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:39:14 </td>
   <td style="text-align:left;"> $TSLA 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:39:10 </td>
   <td style="text-align:left;"> $SPY This time last night permabears were dancing about futures market. It’s permabulls turn this night about futures. Anyway, futures or AH price don’t matter until cash market opens. $TSLA permabulls will be surprised tomorrow when red take over $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:38:46 </td>
   <td style="text-align:left;"> $TSLA something isn’t adding up.  QoQ deliveries were flat but they realized $1B more in revenue with increased gross margins.  They mentioned increased costs but cars are cheaper to build.  🤷‍♂️. 

This is one shady company.  It’s going to implode one of these days.  They can only raise prices by so much and hide the truth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:38:43 </td>
   <td style="text-align:left;"> $MULN $AMZN $AAPL $TSLA $NIO 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:38:24 </td>
   <td style="text-align:left;"> $TSLA oh hey bears…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:38:22 </td>
   <td style="text-align:left;"> $TSLA it’s funny how many have ignored fraud. I owned Tesla stock from 2018 until 2021. Something is not right. But of course I am not your financial advisor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:38:05 </td>
   <td style="text-align:left;"> $TSLA this is def going down tomorrow right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:37:37 </td>
   <td style="text-align:left;"> $TSLA it’s like this reporter doesn’t understand supply and demand… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:37:33 </td>
   <td style="text-align:left;"> OK, I want to hear every Bear best explanation on why they continue to be bearish on $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:37:31 </td>
   <td style="text-align:left;"> $TSLA 

Keep buying the top people. And I mean the top in EVERYTHING not this future $50 stock dream maker. Even food is in a bubble. I stopped eating. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:37:20 </td>
   <td style="text-align:left;"> $AMD guess who makes the computer chips for Tesla computers and graphics…ITS AMD!!! $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:37:09 </td>
   <td style="text-align:left;"> $TSLA weak.. where was the STONK!?👎🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:37:04 </td>
   <td style="text-align:left;"> $NVDA going up big, just in due time $AMD $TSLA $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:36:16 </td>
   <td style="text-align:left;"> $TSLA in January on earnings day it went up day after it flushed down this time it went down i knew it was a bear trap so I bought calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:35:50 </td>
   <td style="text-align:left;"> $NILE  6$ price target! 

 $MULN $RMO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:35:37 </td>
   <td style="text-align:left;"> $TSLA can we go to 1200 tomorrow. Thank you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:35:20 </td>
   <td style="text-align:left;"> $TSLA futes mooning = tesla mooning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:35:20 </td>
   <td style="text-align:left;"> $TSLA so many nerds wanna suck elons chode </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:35:05 </td>
   <td style="text-align:left;"> $TSLA there&amp;#39;s nothing left to digest. More promises about deadlines that he won&amp;#39;t be held accountable for. Oh well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:35:03 </td>
   <td style="text-align:left;"> $SPY $QQQ market has gotten overly-bearish. earnings have been strong and unwavering during an uncertain quarter that was supposed to be weak. it has not been that way so far $MSFT $NFLX $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:35:01 </td>
   <td style="text-align:left;"> $TSLA hyper growth beast of a company, but how much more upside does the stock really have  😲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:34:54 </td>
   <td style="text-align:left;"> $TSLA  $GLBS  $PXS  are making crazy money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:34:51 </td>
   <td style="text-align:left;"> $TSLA tomorrow Nasdaq will be green and Dow red pulling back some good bull run for Tesla. It sucks we can’t have a wild green day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:34:48 </td>
   <td style="text-align:left;"> $TSLA on this episode of still in a bear flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:34:26 </td>
   <td style="text-align:left;"> $TSLA 1200 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:34:05 </td>
   <td style="text-align:left;"> $TSLA picked up a 5/6 $1120 call for $1280 at the bell.  Price of Tesla was $979 when I got it.  Worth letting it ride to see what happens?  Will it be worth much more than what I paid? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:33:59 </td>
   <td style="text-align:left;"> $tsla https://www.torquenews.com/14335/tesla-growing-faster-any-large-cap-company-history </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:33:21 </td>
   <td style="text-align:left;"> $TSLA this morning opened at 1031 and closed at 1031. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:33:14 </td>
   <td style="text-align:left;"> $TSLA 2000000000 tomorrow  . I can play too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:33:11 </td>
   <td style="text-align:left;"> $TSLA MY THOUGHTS https://youtu.be/zTbSM1GWPaw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:32:36 </td>
   <td style="text-align:left;"> $TSLA 🤑 and back over $1k. AGAIN. 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:32:20 </td>
   <td style="text-align:left;"> $TSLA $EULIF its the potential Berlin Grünheide supplier for TESLA in Germany. I hope you are right about these spike tomorrow:) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:32:17 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-20 Chart Analysis Video: 
https://www.youtube.com/watch?v=ArjkHIn4ECc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:32:12 </td>
   <td style="text-align:left;"> $TSLA so glad I sold my puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:32:05 </td>
   <td style="text-align:left;"> $TSLA whoever designed their truck needs to be shot. It will not sell in Texas. No way in hell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:31:43 </td>
   <td style="text-align:left;"> $TSLA closes red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:31:15 </td>
   <td style="text-align:left;"> $TSLA bears ded </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:31:08 </td>
   <td style="text-align:left;"> $TSLA these dumb bears in 2030: Easiest short of all time- 15,000/share coming tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:31:01 </td>
   <td style="text-align:left;"> $TSLA so apparently Lexus announced their first BEV today… cant’t figure out what may have inspired them to design this… hmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:30:56 </td>
   <td style="text-align:left;"> $TSLA only down from here folks. PRICED IN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:30:46 </td>
   <td style="text-align:left;"> $TSLA  Earnings Release after hours trading. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:30:28 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:29:40 </td>
   <td style="text-align:left;"> $TSLA https://www.teslarati.com/tesla-model-3-police-cruiser-dallas-county-texas/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:29:20 </td>
   <td style="text-align:left;"> $MULN was this a run from $TSLA killlng earnings? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:28:23 </td>
   <td style="text-align:left;"> $TSLA lmao this morning I put 900$put and 1100 call down .woke up at 2:30 and my put was up 400% .sold that big and held onto the call 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:28:20 </td>
   <td style="text-align:left;"> $TSLA what happens if we break 1150? Time to fly? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:28:03 </td>
   <td style="text-align:left;"> $TSLA     Good recap    https://youtu.be/WDIebKZ_qEc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:28:03 </td>
   <td style="text-align:left;"> @B_INV3STED TOP SETUPS FOR TOMORROW $CRWD $TSLA $BABA $COIN &amp;amp; MORE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:27:53 </td>
   <td style="text-align:left;"> $TSLA computer programmers will work all night to setup tomorrow algorithms.

Algo power will win the day imo. 2% short interest!?

Bears have $970B of fire power

Imo take the win bulls. Bears are hungry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:27:31 </td>
   <td style="text-align:left;"> $MULN $TSLA thanks Elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:27:15 </td>
   <td style="text-align:left;"> $TSLA   Tomorrow NFLX and TSLA.   NFLX is fantastic buy with all the hot money is gone and TSLA just getting started </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:27:12 </td>
   <td style="text-align:left;"> $TSLA should have bought that 974... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:27:01 </td>
   <td style="text-align:left;"> $TSLA  Maybe it&amp;#39;s been posted maybe not. This morning,  Dallas announce they bought some teslas to test them out. May be small potatoes maybe not. Could spread out city to city maybe not. Good luck. Go Mr. Musk ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:26:56 </td>
   <td style="text-align:left;"> $TSLA Did good trade here. Sold 850 puts nakes for 6.15 profit 20 contracts. Nailed 12k. Ill take it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:26:46 </td>
   <td style="text-align:left;"> $TSLA I said it. Congrats bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:26:46 </td>
   <td style="text-align:left;"> $TSLA $1350…, my bitches. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:26:19 </td>
   <td style="text-align:left;"> $TSLA Europe will hit buy button in 4 hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:26:13 </td>
   <td style="text-align:left;"> $TSLA nice margins and nice growth but I’m going to pass for now.  Mostly because of the Twitter issue — going to be a headwind for the stock until that’s resolved </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:26:11 </td>
   <td style="text-align:left;"> $SNAP $TSLA tesla BEAT in a massive way and the stock is essentially gonna open tomorrow FLAT 😂. If this misses at all it will fcking tank. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:26:05 </td>
   <td style="text-align:left;"> $TSLA tomorrow or by Friday 950 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:25:56 </td>
   <td style="text-align:left;"> $TSLA 😄https://youtu.be/udrZ0VVobDQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:25:44 </td>
   <td style="text-align:left;"> $TSLA  $100Bil revenue this year. Once in the call he said they could do 60% growth this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:25:40 </td>
   <td style="text-align:left;"> $TSLA Oops looks like Im FKD CALLS GONNA GO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:25:04 </td>
   <td style="text-align:left;"> $TSLA can $1050 ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:24:52 </td>
   <td style="text-align:left;"> $TSLA  The price action makes Me think that the market realized the earnings beat was Already priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:24:50 </td>
   <td style="text-align:left;"> $TSLA Stunning quarter. Credit where it’s due </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:24:49 </td>
   <td style="text-align:left;"> Cathie Wood sold 67,884 shares of Tesla today $TSLA

She bought today $GOOG $SHOP $COIN $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:24:37 </td>
   <td style="text-align:left;"> $NFLX buy it back up to 300 in a week $SPY $FB $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:24:35 </td>
   <td style="text-align:left;"> $TSLA bears actually thought they had a chance ahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:24:13 </td>
   <td style="text-align:left;"> $TSLA 👍https://youtu.be/WDIebKZ_qEc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:24:03 </td>
   <td style="text-align:left;"> $TSLA Tesla bears still exist? Would hate to be with that group of retards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:24:00 </td>
   <td style="text-align:left;"> $TSLA pang pong tsla the new appl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:23:59 </td>
   <td style="text-align:left;"> $TSLA We will print a all time high tomorrow. $1240.  20% move coming up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:23:37 </td>
   <td style="text-align:left;"> $TSLA oddly all the poot buyers are gone? 
 
what happened? 
 
all bears here are fake… no one is that stupid.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:23:34 </td>
   <td style="text-align:left;"> $PYPL the market is a joke..no one will I vest in any long position anymore $nflx $coin $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:23:30 </td>
   <td style="text-align:left;"> $TSLA Grandma 👵 Cathie dumped $60 million in Tesla today to buy crap like: $roku  $shop $zm . What a fucking joke. Tesla just posted it’s best earnings yet &amp;amp; is getting ready for a hard run. All the crap 💩 she bought today will tank after their earnings reports </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:23:30 </td>
   <td style="text-align:left;"> $TSLA too the moon tomorrow 1100$ incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:22:37 </td>
   <td style="text-align:left;"> $TSLA now they need to do a FS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:22:18 </td>
   <td style="text-align:left;"> Elon Musk’s performance as CEO in the first quarter earned him the right to purchase 25.2 million shares of Tesla for $70.01 each

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:21:57 </td>
   <td style="text-align:left;"> $TSLA short this Thang tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:21:32 </td>
   <td style="text-align:left;"> $TSLA another 680 million for the biggest welfare queen on them all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:21:29 </td>
   <td style="text-align:left;"> $TSLA $2000 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:21:27 </td>
   <td style="text-align:left;"> $TSLA trading range for this quarter should be $1000-$1500 stock much cheaper now on a P/e ratio basis $QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:21:23 </td>
   <td style="text-align:left;"> $SPY $SPX I don&amp;#39;t usually say much about futures and I guess it&amp;#39;s $TSLA driven but tonight there ripping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:20:52 </td>
   <td style="text-align:left;"> $TSLA Hey Bears.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:20:48 </td>
   <td style="text-align:left;"> $TSLA Be ready to see Tesla drops 50% or 40% like Netflix or FB.  
one or two quarters Tesla will be around $200-300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:20:46 </td>
   <td style="text-align:left;"> $TSLA  
Thinking it has further to fall, unfortunately. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:20:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla Should Take a Cue From Netflix. Competition Matters. https://www.stck.pro/news/TSLA/26467360 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:19:54 </td>
   <td style="text-align:left;"> Watch list for tomorrow part 1: $MULN $TSLA $LCID $NFLX $BLBX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:19:23 </td>
   <td style="text-align:left;"> $TSLA This gonna fly tomorrow. Don&amp;#39;t worry bears....Well say hello from the moon 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:19:01 </td>
   <td style="text-align:left;"> $TSLA wait so crooked elon just got 20b lmao and what were profits? not revenue but profits? no wonder he&amp;#39;s got the Chinese sleeping on the floor. prolly being built by enslaved Muslims </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:18:36 </td>
   <td style="text-align:left;"> Played $TSLA both ways $800 puts at $0.56 to $1.07 (went to $3.85) and added the calls to swing. So far so good 🤌🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:17:13 </td>
   <td style="text-align:left;"> $TSLA my 850$ puts are fuckedddd cashapp donations $husham78755 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:16:20 </td>
   <td style="text-align:left;"> $TSLA dont buy fucking high prices dont be stupid fakkers! Remember BUY low and SELL high, stop making fucking same mistakes over and over again!!! Havent you learned fucking anything!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:15:33 </td>
   <td style="text-align:left;"> $TSLA if we hit 1150 tomorrow or Friday I’ll make 10k please just do it lmfao 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:14:51 </td>
   <td style="text-align:left;"> $TSLA $1420.69 at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:14:50 </td>
   <td style="text-align:left;"> $TSLA In the morning what will happen to my Puts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:14:47 </td>
   <td style="text-align:left;"> $TSLA flat on the day after record earnings? Unreal market. Democrats are a disease. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:14:47 </td>
   <td style="text-align:left;"> $TSLA just got a nice bj from the cafeteria lady in my Tesla. Autopilot is amazing!!! 🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:14:44 </td>
   <td style="text-align:left;"> $TSLA Updated fundamentals after their 22Q1 Earnings  
 
📈 EPS +248% 
📈 Sales +81% 
📈 Profit Margin +20% 
 
$TSLA up +5.5% after hours #IBDPartner @InvestorsBusinessDaily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:14:23 </td>
   <td style="text-align:left;"> $TSLA 1100 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:14:22 </td>
   <td style="text-align:left;"> $SPY $tsla just saved tech stocks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:14:04 </td>
   <td style="text-align:left;"> $SPY $QQQ  Sell all Tech stocks because the economy is going down ie: inflation, supply chain …But buy $TSLA stock because the economy is so good everyone is buying a $50 thousand to $100 thousand dollar car </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:13:59 </td>
   <td style="text-align:left;"> $TSLA heavy resistance at 1037 it may leap passed that but flash dump incoming no question about that! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:13:54 </td>
   <td style="text-align:left;"> $TSLA 1085 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:13:47 </td>
   <td style="text-align:left;"> $TSLA 

Cathie wood say she don’t want this overpriced garbage . Boss moves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:13:46 </td>
   <td style="text-align:left;"> $TSLA Good bye price $1K 😝🪤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:13:42 </td>
   <td style="text-align:left;"> $TSLA hopefully this opens above 1050 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:13:15 </td>
   <td style="text-align:left;"> $TSLA put the charts in overbought condition and keep buying buy my bags on high! Love to see it !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:13:10 </td>
   <td style="text-align:left;"> $TSLA so yesterday $NFLX holding everyone back and today Tesla making some more breathing room… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:12:58 </td>
   <td style="text-align:left;"> $TSLA way to go Tesla. Run hard. Will be scalping sark again shortly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:12:33 </td>
   <td style="text-align:left;"> $TSLA $1150 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:11:52 </td>
   <td style="text-align:left;"> $TSLA easily cross $1100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:11:24 </td>
   <td style="text-align:left;"> $TSLA if we do a 5% tomorrow I’ll suck a fart outta someone’s butt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:11:14 </td>
   <td style="text-align:left;"> $TSLA bull market full steam ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:11:11 </td>
   <td style="text-align:left;"> $TSLA up $3.45 on the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:11:00 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s hit all time highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:10:58 </td>
   <td style="text-align:left;"> $TSLA I can&amp;#39;t imagine how much money they are going to collect on otm call premiums </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:10:56 </td>
   <td style="text-align:left;"> $TSLA …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:10:33 </td>
   <td style="text-align:left;"> $TSLA futures are up. Let’s goooo moon rocket tomorrow ladies and gents </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-21 08:10:20 </td>
   <td style="text-align:left;"> $TSLA Nice smooth finish this thing is going to the moon tomorrow </td>
  </tr>
</tbody>
</table></div>

---
