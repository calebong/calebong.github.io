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



Last Updated: 2022-02-21 08:49:22 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/japan/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-21 08:48:44 </td>
   <td style="text-align:left;"> Japan Manufacturing PMI Falls to 5-Month Low </td>
   <td style="text-align:left;"> The au Jibun Bank Japan Manufacturing PMI dropped to 52.9 in February 2022, after a final 54.3 a month earlier, a preliminary reading showed. This was the weakest growth in factory activity since last September, amid renewed covid-19 restrictions and ongoing supply chains disruptions. Output shrank for the first time in five months, while new orders growth eased to the softest in the current sequence expansion, with slowing in new exports orders growth. The rate of job creation slowed with declining in backlogs of work accumulation. On the price front, input prices inflation accelerated, amid raw material shortages, while output cost inflation eased. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/composite-pmi </td>
   <td style="text-align:left;"> 2022-02-21 08:37:00 </td>
   <td style="text-align:left;"> Japan Composite PMI Lowest in 20 Months </td>
   <td style="text-align:left;"> The au Jibun Bank Japan Composite PMI dropped sharply to 44.6 in February 2022 from 48.8 a month earlier, pointing to the second straight month of decline as the Omicron variant of COVID-19 led to record case numbers and renewed curbs,  a flash reading showed. The latest reading also marked the sharpest fall in private sector activity in 20 months, coming amid the steepest downturn in the services sector since the first wave of the pandemic in May 2020. Further, manufacturers signaled a reduction in output for the first time in five months, though the rate of contraction was considerably softer than that seen in the dominant services sector. New orders fell for the first time since September, driven by
domestic drop while new export orders broadly stagnated. Firms continued to report that rising input prices and material shortages, notably in fuel and metals continued to dampen the private sector. On the cost side, February saw the strongest rise in cost burdens since August 2008. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2022-02-21 08:04:17 </td>
   <td style="text-align:left;"> Nikkei 225 is down by 2% </td>
   <td style="text-align:left;"> Nikkei 225 decreased 2% to 26579 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/20/business/oil-prices-russia-ukraine-iran.html </td>
   <td style="text-align:left;"> 2022-02-21 07:57:12 </td>
   <td style="text-align:left;"> Oil Prices Climb as Russia Menaces Ukraine - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , By Clifford Krauss                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Uncertainty drove oil prices higher on Sunday as more Russians troops massed on Ukraine’s borders.                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Oil prices were essentially flat over the last week as traders anticipated a potential nuclear deal with Iran that could allow the country to bring millions of gallons of oil to the market. But with tensions ratcheting up along the Russia-Ukraine border, oil markets opened in evening trading more than a dollar a barrel higher.                                                                                                                                                                                                                      , President Biden and other senior American officials have said that President Vladimir V. Putin of Russia has already decided to invade Ukraine despite the threat of crippling sanctions. Any invasion would most likely interrupt Russian natural gas and oil shipments to parts of Europe and then be followed by a decline in purchases of Russian energy by the West. Nevertheless, negotiations continued on several fronts.                                                                                                                             , The United States and many other industrialized countries will most likely release millions of barrels of oil from their strategic reserves as soon as a significant invasion occurs. There is also talk in Washington of suspending federal taxes on gasoline. Such measures could help restrain prices at the pump, at least for a short time.                                                                                                                                                                                                              , The average national price of a gallon of gasoline rose nearly 4 cents over the last week to $3.53, roughly 90 cents higher than a year ago. Gasoline prices at the pump usually follow global oil price trends by a week or two.                                                                                                                                                                                                                                                                                                                             , Despite the growing likelihood of conflict, the American benchmark oil price fell nearly 2 percent last week while the global benchmark price rose by less than a dollar a barrel. Both benchmarks remain above $90 a barrel, the highest level since 2014.                                                                                                                                                                                                                                                                                                   , On Sunday evening the American oil benchmark, West Texas Intermediate, rose nearly 2 percent to $92.73 a barrel, while the global Brent benchmark was up 1.3 percent to $94.76 a barrel.                                                                                                                                                                                                                                                                                                                                                                      , The United States is not a big importer of Russian oil, but Russia provides roughly one of every 10 barrels the global economy consumes as the third largest producer after the United States and Saudi Arabia. Russian oil exports go mostly to Europe and Asia, and global markets remain tight as production has not kept up with the economic rebound from the Covid-19 pandemic.                                                                                                                                                                         , American oil production has gradually increased in recent months, and Saudi Arabia and the United Arab Emirates are believed to have spare production capacity. But it would take a nuclear deal with Iran to quickly send new barrels onto global markets. Iran has as much as 80 million barrels in storage it could sell relatively quickly and it could ramp up its production to 1.2 million barrels a day within eight months. But in a 100-million-barrel-a-day market, that would not resolve shortages if there is a prolonged war in Eastern Europe., Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-02-21 07:01:00 </td>
   <td style="text-align:left;"> Gold Hits 36-week High </td>
   <td style="text-align:left;"> Gold increased to a 36-week high of 1903 USD/t.oz, amid escalating tensions in Eastern Europe. Russia reportedly will extend military drills in Belarus that were due to end on Sunday, the Belarusian defense ministry announced. Meanwhile, the White House said President Joe Biden was canceling a trip to Delaware and staying in Washington after a meeting of his National Security Council. At the same time, concerns lingered about the next Fed steps after St. Louis Fed President Bullard repeated his call for Fed's strong action and Cleveland Fed President Mester said she supports hiking rates faster if needed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/services-sentiment </td>
   <td style="text-align:left;"> 2022-02-21 06:18:00 </td>
   <td style="text-align:left;"> Australia Services Sector Growth at 8-Month High </td>
   <td style="text-align:left;"> The IHS Markit Australia Services PMI jumped to 56.4 in February of 2022 from 46.6 in January, marking a return to growth and the fastest expansion in eight months, flash estimates showed. The receding of the COVID-19 Omicron wave from the peak in January enabled new business and activity to expand though foreign demand remained subdued. As a result of higher overall demand, hiring activity picked up as firms expanded operating capacity accordingly. Price pressures meanwhile persisted with selling prices rising at a survey record rate. Input price inflation eased from the January record but remained steep by historical standards. Overall optimism nevertheless improved as service providers were hopeful for continued growth in demand as the economy recovers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/industrial-sentiment </td>
   <td style="text-align:left;"> 2022-02-21 06:14:00 </td>
   <td style="text-align:left;"> Australia Factory Growth Expands in February </td>
   <td style="text-align:left;"> The IHS Markit Australia Manufacturing PMI rose to 57.6 in February of 2022 from 55.1 in January, pointing to the fastest growth in factory activity in 2 months, flash estimates showed. Manufacturing output returned to expansion following a brief month of contraction at the start of 2022 while new order growth accelerated. Firms reported higher demand coupled with an easing of COVID-19 disruptions enabling output to return to growth. Employment levels likewise rose to meet the growth in demand. That said, suppliers' delivery times lengthened at a more severe rate due to shipping delays, manpower constraints and COVID-19 disruptions, leading to the accumulation of backlogged work. As a result, price pressures worsened with both input costs and output prices rising at faster rates. That said, business confidence amongst manufacturers improved on hopes of recovery from the latest COVID-19 wave. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/composite-pmi </td>
   <td style="text-align:left;"> 2022-02-21 06:10:00 </td>
   <td style="text-align:left;"> Australia Markit Composite PMI at 8-Month High </td>
   <td style="text-align:left;"> The IHS Markit Australia Composite PMI rose to a 8-month high of 55.9 in February of 2022 from 46.7 in January due to the easing of the COVID-19Omicron wave, flash estimates showed. The services sector expanded to a 8-month high (56.4 vs 46.6 in January) and manufacturing growth advanced to a 2-month high (57.6 vs 55.1). Private sector output and demand both expanded after shrinking at the start of the year, leading to higher employment levels. Supply constraints nevertheless persisted, causing the accumulation of backlogged work and the worsening of price pressures with output price inflation rising to a record. Overall business optimism remained positive with the level of confidence rising to a two-month high as the Australian economy recovers from the COVID-19 Omicron wave. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/20/business/dealbook/mcdonalds-pork-carl-icahn.html </td>
   <td style="text-align:left;"> 2022-02-21 05:10:48 </td>
   <td style="text-align:left;"> Carl Icahn Pushes McDonald’s to Change Way It Sources Its Pork - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                         , The billionaire investor has proposed two candidates for the company’s board. The company argues that his demands are unreasonable given the current U.S. pork supply.                                                                                                                                                                                                                                                               , By Lauren Hirsch                                                                                                                                                                                                                                                                                                                                                                                                                     , The billionaire investor Carl Icahn began his battle with McDonald’s in his usual fashion — buying a small stake in the company and then pushing his own candidates for its board. But what’s different this time is the issue — better treatment for the pigs whose meat goes into McDonald’s sausage patties and other pork products.                                                                                              , On Sunday, McDonald’s confirmed that Mr. Icahn, who it says owns 200 shares in the restaurant chain, had nominated two people to its board over the matter — in what is likely to be the start of a bitter, and peculiar, contest.                                                                                                                                                                                                   , Unlike the typical target of corporate agitators, McDonald’s has done well, with its shares climbing more than 18 percent over the past 12 months to give it a market capitalization of $187 billion. And while Mr. Icahn’s stake in the company is small, activist investors with social causes have had recent success on small stakes, like Engine Capital’s board victory at Exxon Mobil last year over its climate strategy.    , Mr. Icahn’s two board candidates are Leslie Samuelrich and Maisie Ganzler, according to McDonald’s. Ms. Samuelrich is the president of Green Century Capital Management, an investment fund with a sustainable energy focus, according to her LinkedIn profile. Ms. Ganzler is chief strategy and brand officer at Bon Appétit Management Company, according to her LinkedIn profile.                                                , Mr. Icahn is arguing that McDonald’s has not fully lived up to its commitment to change the way in sources its pork. McDonald’s in 2012 pledged to phase out the use of so-called gestational crates, the tiny stalls in which sows are housed while pregnant. Animal rights advocates have singled out the crates, known as sow stalls, as inhumane.                                                                                , Mr. Icahn told The Wall Street Journal this month that the company’s pork producers were moving sows only once they are four to six weeks into their 16-week pregnancies. He said his campaign was inspired by his daughter, a vegetarian animal lover.                                                                                                                                                                              , A press officer for Icahn Enterprises did not immediately respond to a request for comment.                                                                                                                                                                                                                                                                                                                                          , “Mr. Icahn’s stated focus in making this nomination relates to a narrow issue regarding the company’s pork commitment, which the Humane Society U.S. has already introduced through a shareholder proposal,” McDonald’s said in a statement on Sunday. “This is an issue on which McDonald’s has been a leader.”                                                                                                                     , McDonald’s contends that Mr. Icahn’s demands are unreasonable given the current pork supply in the United States. And it cited what it said were inconsistencies with Mr. Icahn’s other investments, pointing to his majority ownership in a pork and poultry packer and supplier, Viskase, through his holding company Icahn Enterprises.                                                                                           , “Mr. Icahn’s ownership provides him with unique exposure to the industrywide challenges and opportunities in migrating away from gestation crates,” McDonald’s said.                                                                                                                                                                                                                                                                 , “Thus, it’s noteworthy that Mr. Icahn has not publicly called on Viskase to adopt commitments similar to those of McDonald’s 2012 commitment.”                                                                                                                                                                                                                                                                                       , McDonald’s sources roughly 1 percent of all U.S. pork production, it said, and does not own any sows, or produce or package pork in the country. By the end of this year, McDonald’s said, it expects to source 85 to 90 percent of its U.S. pork from sows not housed in gestation crates during pregnancy. By the end of 2024, it said, it expects that all of its U.S. pork will come from sows housed in groups during pregnancy., Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60456196?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-21 04:26:43 </td>
   <td style="text-align:left;"> Credit Suisse denies wrongdoing after big banking data leak </td>
   <td style="text-align:left;"> Credit Suisse has hit out after a massive data leak has brought to light the hidden wealth of several clients of the bank.                                                                                                                               , Data on more than 18,000 bank accounts, holding more than $100bn (£73.6bn), was leaked to German newspaper Süddeutsche Zeitung by a whistleblower.                                                                                                       , It includes personal, shared and corporate accounts, as well as those opened as far back as the 1940s.                                                                                                                                                   , Nearly 50 media organisations have spent months poring over the data.                                                                                                                                                                                    , In their investigations, they suggest they have found evidence Credit Suisse accounts had been used by clients involved in serious crimes such as money laundering or drug trafficking.                                                                  , But the Swiss bank rejected the allegations in a statement on Sunday, saying it strongly rejected the allegations and insinuations about the bank's alleged business practices or lack of due diligence carried out.                                     , "The matters presented are predominantly historical, in some cases dating back as far as the 1940s, and the accounts of these matters are based on partial, inaccurate, or selective information taken out of context", it said.                         , In reports published by media organisations such as The Guardian and the New York Times, it has been claimed the bank opened or maintained accounts for high-risk clients, including criminals and individuals involved in human trafficking.            , Holding a Swiss account is not illegal and the leak also reportedly contained data of clients who had done nothing wrong.                                                                                                                                , The data was shared with more than 40 media organisations around the world by non-profit journalism group, the Organized Crime and Corruption Reporting Project.                                                                                         , It includes bank accounts dating back decades. The majority were opened from 2000 onwards, although the bank's current operations are not included.                                                                                                      , Credit Suisse also said on Sunday that it had reviewed a large volume of accounts potentially associated with the matters raised.                                                                                                                        , "Approximately 90% of the reviewed accounts are today closed or were in the process of closure prior to receipt of the press inquiries, of which over 60% were closed before 2015," it said, although it would not comment on specific clients mentioned., The bank added it was "deeply aware of its responsibility to clients and the financial system as a whole to ensure that the highest standards of conduct are upheld".                                                                                    , "These media allegations appear to be a concerted effort to discredit not only the bank but the Swiss financial market-place as a whole, which has undergone significant changes over the last several years," it said.                                  , In a statement published by German newspaper Süddeutsche Zeitung, the anonymous source explained their motivation for leaking the records more than a year ago.                                                                                          , "I believe that Swiss banking secrecy laws are immoral. The pretext of protecting financial privacy is merely a fig leaf covering the shameful role of Swiss banks as collaborators of tax evaders," they wrote.                                         , It is not known if the whistleblower is an individual or a group.                                                                                                                                                                                        , They also acknowledged "having an offshore Swiss bank account does not necessarily imply tax evasion or any other financial crime".                                                                                                                      , Credit Suisse pointed out it had taken "significant additional measures over the last decade, including considerable further investments in combating financial crime".                                                                                  , It follows other scandals for the Swiss bank, including the departure of two of its top executives after allegedly breaking Covid regulations and spying on former staff.                                                                                , Richard Osman on life as a broadcaster and writer                                                                                                                                                                                                        , Behind the faces leading US far right political movements online                                                                                                                                                                                         , Six gruelling days at the world’s toughest mountain race                                                                                                                                                                                                 , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60451934?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-21 03:39:32 </td>
   <td style="text-align:left;"> Lufthansa and Swiss Air to suspend flights to Ukraine capital </td>
   <td style="text-align:left;"> Lufthansa and Swiss Air will suspend flights to the Ukraine capital Kyiv from Monday amid growing fears of a Russian invasion.                                                                                                                , The German airline Lufthansa said it would also stop flights to Odessa, a key port on the Black Sea.                                                                                                                                          , "The safety of our passengers and crew members is our top priority at all times," said Lufthansa.                                                                                                                                             , UK Prime Minister Boris Johnson warned on Sunday that Russia is planning "the biggest war in Europe since 1945".                                                                                                                              , Last week, the Dutch airline KLM said that it was suspending flights to Kyiv.                                                                                                                                                                 , The Lufthansa suspension is expected to remain in place until the end of February.                                                                                                                                                            , Swiss Air said on Sunday that it would suspend its flights to Kyiv from Monday up to and including 28 February.                                                                                                                               , Both Lufthansa and Swiss say they will continue to monitor the situation closely and that they are in close contact with national and international authorities.                                                                              , Swiss added: "The safety of our passengers and crew members has top priority at all times... The affected customers will be informed accordingly."                                                                                            , A spokesperson for Lufthansa said: "Affected guests will be informed and rebooked on alternative flight connections."                                                                                                                         , The airline usually operates 74 flights to Ukraine every week under its Lufthansa banner or the other carriers it owns which include Austrian Airlines, Eurowings and Swiss.                                                                  , Lufthansa said it would continue to fly to Lviv in Western Ukraine.                                                                                                                                                                           , Mr Johnson told the BBC that evidence suggests that Russia intends to launch an invasion that will encircle Kyiv.                                                                                                                             , "All the signs are that the plan has already in some senses begun," he said.                                                                                                                                                                  , Ryanair and Wizz Air also operate flights to Ukraine and last week said they would continue to fly to the country. Ryanair is the largest airline which flies between Europe and Ukraine, followed by Wizz Air.                               , In a statement on Sunday, Wizz Air said it was monitoring the situation closely and reminded passengers to check their inboxes regularly for further information about booked flights.                                                        , A Wizz Air spokesperson said: "Currently, we have not made any changes to our schedule and all of our flights to/from Ukraine continue to operate as normal."                                                                                 , Ryanair's chief executive Michael O'Leary said last week: "It is important not to panic.                                                                                                                                                      , "Is it our duty and obligation to support the people of Ukraine as long as there is no war or missiles flying there."                                                                                                                         , The UK's Foreign Office has advised that British nationals "should leave while commercial options remain".                                                                                                                                    , "In the event of a military incursion, it is likely that commercial routes out of Ukraine will be severely disrupted and roads across Ukraine could be closed," it said.                                                                      , Last week, the Ukrainian government pledged to keep the country's airspace open. It said it was ready to assume financial obligations for flight safety amid concerns of rising insurance costs for airlines to keep flying into the region.  , In July 2014, Malaysia Airlines flight MH17 was shot down while flying near eastern Ukraine's conflict zone. All 298 passengers and crew on board the flight between Amsterdam and Kuala Lumpur were killed. The victims included 80 children., An investigation by the Dutch Safety Board found that the plane crashed after being hit by a Russian-made Buk missile.                                                                                                                        , Richard Osman on life as a broadcaster and writer                                                                                                                                                                                             , Behind the faces leading US far right political movements online                                                                                                                                                                              , Six gruelling days at the world’s toughest mountain race                                                                                                                                                                                      , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/20/massive-credit-suisse-leak-reportedly-reveals-possible-criminal-ties-among-18000-accounts.html </td>
   <td style="text-align:left;"> 2022-02-21 03:14:17 </td>
   <td style="text-align:left;"> Massive Credit Suisse leak reportedly reveals possible criminal ties among 18,000 accounts </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                               , Credit Suisse was scrambling Sunday to contain the fallout from its latest scandal after several newspapers reported that more than 18,000 leaked accounts showed that criminals, alleged human rights abusers and sanctioned individuals including dictators had been clients of the Swiss bank.                                                                                                                                             , The leaked information, which covered accounts holding more than $100 billion, came from a whistle-blower who shared his findings with German newspaper Süddeutsche Zeitung, according to a press release. The newspaper then involved an anti-corruption group and 46 other media outlets around the world, including The New York Times, Guardian, Le Monde and others.                                                                     , Clients of the second-biggest Swiss bank included an international cast of unsavory characters, according to the media reports. Account holders included a Yemeni spy chief implicated in torture, Venezuelan officials involved in a corruption scandal, and the sons of former Egyptian dictator Hosni Mubarak.                                                                                                                             , The accounts had been opened from the 1940s into the 2010s, according to the Sunday release from the Organized Crime and Corruption Reporting Project.                                                                                                                                                                                                                                                                                        , "I've too often seen criminals and corrupt politicians who can afford to keep on doing business as usual, no matter what the circumstances, because they have the certainty that their ill-gotten gains will be kept safe," Paul Radu, co-founder of the OCCRP, said in the statement. "Our investigation exposes how these people can bypass regulation despite their crimes, to the detriment of democracies and people all over the world.", While Swiss banks, world-renowned for the country's strict secrecy laws protecting clients, aren't supposed to accept money linked to criminal activity, the law is mostly unenforced, according to The New York Times, which cited a former head of Switzerland's anti-money laundering agency.                                                                                                                                              , Credit Suisse said in a nearly 400-word statement on Sunday that it "strongly rejects" the accusations made about its business practices.                                                                                                                                                                                                                                                                                                     , "The matters presented are predominantly historical, in some cases dating back as far as the 1940s, and the accounts of these matters are based on partial, inaccurate, or selective information taken out of context, resulting in tendentious interpretations of the bank's business conduct," the bank said.                                                                                                                               , About 90% of the accounts in the leak had been closed or were in the process of being closed before media inquiries began, the bank said. It is "comfortable" that the remaining accounts were vetted properly. Credit Suisse added that it couldn't comment on individual clients and that it's already taken action "at the relevant times" to address improper clients.                                                                    , For much of the past decade, the Zurich-based financial giant has moved from one crisis to another as it came to terms with its role in helping clients launder ill-gotten funds, shelter assets from taxation and aid in corruption.                                                                                                                                                                                                         , In 2014, the bank plead guilty to helping Americans file false tax returns and agreed to pay $2.6 billion in fines and restitution. Last year, it agreed to pay $475 million for its role in a bribery scheme in Mozambique.                                                                                                                                                                                                                  , The firm had to replace both its CEO and chairman within the past two years and was ensnared in the collapse of the supply chain finance firm Greensill as well as the U.S. hedge fund Archegos.                                                                                                                                                                                                                                              , "The pretext of protecting financial privacy is merely a fig leaf covering the shameful role of Swiss banks as collaborators of tax evaders," said the Credit Suisse whistleblower, according to the OCCRP statement. "This situation enables corruption and starves developing countries of much-needed tax revenue."                                                                                                                        , This story is developing. Please check back for updates.                                                                                                                                                                                                                                                                                                                                                                                      , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/20/business/credit-suisse-leak-swiss-bank.html </td>
   <td style="text-align:left;"> 2022-02-21 01:00:10 </td>
   <td style="text-align:left;"> Data Leak Exposes How a Swiss Bank Served Strongmen and Spies - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Leaked data on more than 18,000 accounts shows that the Swiss bank missed or ignored red flags.                                                                                                                                                                                                                                                                                                                                                                                                                      , By Jesse Drucker and Ben Hubbard                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The client rosters of Swiss banks are among the world’s most closely guarded secrets, protecting the identities of some of the planet’s richest people and clues into how they accumulated their fortunes.                                                                                                                                                                                                                                                                                                           , Now, an extraordinary leak of data from Credit Suisse, one of the world’s most iconic banks, is exposing how the bank held hundreds of millions of dollars for heads of state, intelligence officials, sanctioned businessmen and human rights abusers, among many others.                                                                                                                                                                                                                                           , A self-described whistle-blower leaked data on more than 18,000 bank accounts, collectively holding more than $100 billion, to the German newspaper Süddeutsche Zeitung. The newspaper shared the data with a nonprofit journalism group, the Organized Crime and Corruption Reporting Project, and 46 other news organizations around the world, including The New York Times.                                                                                                                                      , The data covers accounts that were open from the 1940s until well into the 2010s but not the bank’s current operations.                                                                                                                                                                                                                                                                                                                                                                                              , Among the people listed as holding amounts worth millions of dollars in Credit Suisse accounts were King Abdullah II of Jordan and the two sons of the former Egyptian strongman Hosni Mubarak. Other account holders included sons of a Pakistani intelligence chief who helped funnel billions of dollars from the United States and other countries to the mujahedeen in Afghanistan in the 1980s and Venezuelan officials ensnared in a long-running corruption scandal.                                         , The leak shows that Credit Suisse opened accounts for and continued to serve not only the ultrawealthy but also people whose problematic backgrounds would have been obvious to anyone who ran their names through a search engine.                                                                                                                                                                                                                                                                                  , Swiss banks have long faced legal prohibitions on taking money linked to criminal activity, said Daniel Thelesklaf, the former head of Switzerland’s anti-money laundering agency. But, he said, the law generally hasn’t been enforced.                                                                                                                                                                                                                                                                             , Candice Sun, a spokeswoman for the bank, said in a statement that “Credit Suisse strongly rejects the allegations and inferences about the bank’s purported business practices.” She said many of the accounts in the leak date back decades to “a time where laws, practices and expectations of financial institutions were very different from where they are now.”                                                                                                                                               , Ms. Sun said that while Credit Suisse can’t comment on specific clients, many of the accounts identified in the leaked database have already been closed. “Of the remaining active accounts, we are comfortable that appropriate due diligence, reviews and other control related steps were taken, including pending account closures,” she said.                                                                                                                                                                   , Ms. Sun added that the leak appears to be part of “a concerted effort to discredit the bank and the Swiss financial marketplace, which has undergone significant changes over the last several years.”                                                                                                                                                                                                                                                                                                               , The leak follows the so-called Panama Papers in 2016, the Paradise Papers in 2017 and the Pandora Papers last year. They all shed light on the secretive workings of banks, law firms and offshore financial-services providers that allow wealthy people and institutions — including those accused of crimes — to move huge sums of money, largely outside the purview of tax collectors or law enforcement.                                                                                                       , The new disclosures are likely to intensify legal and political scrutiny of the Swiss banking industry and, in particular, Credit Suisse. The bank is already reeling from the abrupt ousters of its two top executives.                                                                                                                                                                                                                                                                                             , With its ironclad bank-secrecy laws, Switzerland has long been a haven for people who are looking to hide money. In the past decade, that has made the country’s largest banks — especially its two giants, Credit Suisse and UBS — a target for the authorities in the United States and elsewhere who are trying to crack down on tax evasion, money laundering and other crimes.                                                                                                                                  , In 2014, Credit Suisse pleaded guilty to conspiring to help Americans file false tax returns and agreed to pay fines, penalties and restitution totaling $2.6 billion.                                                                                                                                                                                                                                                                                                                                               , Three years later, the bank paid the Justice Department $5.3 billion to settle allegations about its marketing of mortgage-backed securities. Last fall, it agreed to pay $475 million to U.S. and British authorities to resolve an investigation into a kickback and bribery scheme in Mozambique. And this month, a trial got underway in Switzerland in which Credit Suisse is accused of allowing drug traffickers to launder millions of euros through the bank.                                               , The Justice Department and the Senate Finance Committee are also looking into whether U.S. citizens continue to hold undeclared accounts at the bank.                                                                                                                                                                                                                                                                                                                                                                , Several former Credit Suisse employees told federal prosecutors late last year that the bank continued to hide hundreds of millions of dollars for clients long after its 2014 guilty plea, according to a whistle-blower lawsuit filed last year by a former bank official and a lawyer for other former employees. (The suit was dismissed after the Justice Department said it “threatens to interfere with ongoing discussions with Credit Suisse” about dealing with Swiss bank accounts held by U.S. citizens.), The media consortium has nicknamed the latest leak “Suisse Secrets.” Of the more than 18,000 bank accounts involved, roughly 100 U.S. citizens held accounts, but none are public figures.                                                                                                                                                                                                                                                                                                                           , Among the biggest revelations is that Credit Suisse continued to do business with customers even after bank officials flagged suspicious activity involving their finances.                                                                                                                                                                                                                                                                                                                                          , One account holder was Venezuela’s former vice minister of energy, Nervis Villalobos.                                                                                                                                                                                                                                                                                                                                                                                                                                , Employees in Credit Suisse’s compliance department had reason to be wary of doing business with him. The bank had a 2008 report by an outside due-diligence firm detailing corruption allegations involving Mr. Villalobos and Venezuela’s state-owned oil company, Petróleos de Venezuela, according to a Spanish police report obtained by the media consortium. (The Times reviewed the report.)                                                                                                                  , Credit Suisse nonetheless opened an account for him in 2011, the leaked bank data shows. The account, which was closed in 2013, held as much as $10 million.                                                                                                                                                                                                                                                                                                                                                         , Lawyers for Mr. Villalobos, who was criminally charged by the Justice Department in 2017, didn’t respond to requests for comment.                                                                                                                                                                                                                                                                                                                                                                                    , All told, there were 25 Credit Suisse accounts, containing a total of about $270 million, that belonged to people accused of being involved in a wide-ranging conspiracy surrounding Venezuela’s oil company. The accounts remained open after the scandal started to become public, but were closed by the time criminal charges were filed.                                                                                                                                                                        , The bank also kept accounts open for a Zimbabwean businessman who was sanctioned by U.S. and European authorities for his ties to the government of the country’s longtime president, Robert Mugabe. The accounts stayed open for several months after the sanctions were imposed.                                                                                                                                                                                                                                   , The leaked bank information included many accounts linked to government officials across the Middle East and beyond. The data raises questions about how public officials and their relatives accumulated vast fortunes in a region rife with corruption.                                                                                                                                                                                                                                                            , The sons of former President Hosni Mubarak of Egypt, Alaa and Gamal Mubarak, held a total of six accounts at various points, including one in 2003 that was worth $196 million.                                                                                                                                                                                                                                                                                                                                      , In a statement to The New York Times, the Mubaraks’ lawyers declined to comment about specific accounts but said the suggestion that any of the Mubaraks’ assets had been “tainted by any illegality or a result of any favoritism or use of influence” would be “both unfounded and defamatory.”                                                                                                                                                                                                                    , Any assets they held, the statement said, were from their “successful professional business activities.”                                                                                                                                                                                                                                                                                                                                                                                                             , King Abdullah II of Jordan, one of the few officials in the leaks who remains in power, had six accounts, including one whose balance exceeded $224 million.                                                                                                                                                                                                                                                                                                                                                         , Jordan’s Royal Hashemite Court said in a statement that there had been no “unlawful or improper conduct” in relation to the bank accounts. They held portions of the king’s private wealth, which was used for personal expenses, royal projects to help Jordanians and the maintenance of Islamic holy sites in Jerusalem, of which he is the custodian.                                                                                                                                                            , Senior intelligence officials and their offspring from several countries that cooperated with the United States in the war on terrorism also had money stashed at Credit Suisse.                                                                                                                                                                                                                                                                                                                                     , As the head of the Pakistani intelligence agency, General Akhtar Abdur Rahman Khan helped funnel billions of dollars in cash and other aid from the United States and other countries to the mujahedeen in Afghanistan to support their fight against the Soviet Union.                                                                                                                                                                                                                                              , In 1985, the same year President Ronald Reagan called for more oversight of the aid going into Afghanistan, an account was opened in the name of three of General Khan’s sons. (The general never faced charges of stealing aid money.) Years later, the account would grow to hold $3.7 million, the leaked records show.                                                                                                                                                                                           , Two of the general’s sons, Akbar and Haroon Khan, did not respond to requests for comment from the reporting project. In a text message, a third son, Ghazi Khan, called information about the accounts “not correct,” adding, “The content is conjectural.”                                                                                                                                                                                                                                                         , In 2003, the year that the United States invaded Iraq to topple Saddam Hussein, Saad Kheir, the head of Jordan’s intelligence agency, opened an account that would eventually hold $21.6 million.                                                                                                                                                                                                                                                                                                                    , The account was closed after Mr. Kheir’s death in 2009.                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The family of Mr. Mubarak’s long-serving and brutal spymaster, Omar Suleiman, had an account, too. Mr. Suleiman died in 2012. Efforts by the reporting project to reach his family were unsuccessful.                                                                                                                                                                                                                                                                                                                , The leaked records were provided to Germany’s Süddeutsche Zeitung more than a year ago by an unidentified whistle-blower. Of the dozens of news organizations collaborating on the project, none were based in Switzerland, where a 2015 law restricted journalists from writing articles based on internal bank data.                                                                                                                                                                                               , The whistle-blower said in a statement to the media consortium that Swiss bank-secrecy laws were “immoral.”                                                                                                                                                                                                                                                                                                                                                                                                          , “The pretext of protecting financial privacy is merely a fig leaf covering the shameful role of Swiss banks as collaborators of tax evaders,” the whistle-blower said.                                                                                                                                                                                                                                                                                                                                               , Katie Benner contributed reporting and Kitty Bennett contributed research.                                                                                                                                                                                                                                                                                                                                                                                                                                           , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/20/us/philadelphia-larry-miller-edward-white/index.html </td>
   <td style="text-align:left;"> 2022-02-20 22:05:36 </td>
   <td style="text-align:left;"> At 16, Larry Miller killed another teen. At 72, the Nike executive is ready to apologize  - CNN </td>
   <td style="text-align:left;"> Philadelphia (CNN)Two chance encounters at the same West Philadelphia street corner show the remarkable arc of Larry Miller's life. The first, as a drunk and angry 16-year-old, ended with him murdering another teen. The second, 56 years later as a lauded business executive, brand visionary and friend of Michael Jordan, gave him a new chance to seek redemption.                                                                                                                                                                                              , The intervening decades were clouded by Miller keeping his criminal past secret as he rose far up the corporate ladder, mostly notably leading the Jordan Brand at Nike, as well as heading up the Portland Trail Blazers NBA franchise.                                                                                                                                                                                                                                                                                                                                , He says he suffered debilitating migraines and nightmares until he decided to open up about his whole life, not just that part lived in the public eye.                                                                                                                                                                                                                                                                                                                                                                                                                 , "I had nightmares on a regular basis about going back to jail," he tells CNN. "I had incredible migraine headaches and I'm certain that that was all from just trying to hold all this in and being concerned that it might come out. There was always this tension and this fear that somehow this is going to come out and it's going to ruin everything I've built up to this point."                                                                                                                                                                                , The tension lifted when he wrote a book on his remarkable life story, and he hopes that his talking about his redemption will offer a fresh way to look at formerly incarcerated people.                                                                                                                                                                                                                                                                                                                                                                                , That's why he's at the corner of 53rd and Locust, where he committed the worst act of his life -- taking the life of another. By telling his story to media and in the new book "Jump: My Secret Journey from the Streets to the Boardroom" maybe he can reach a kid today to stop him doing something he will regret, or show an incarcerated person there is life after prison, he says.                                                                                                                                                                              , Miller doesn't remember all that much about the first encounter -- cheap wine didn't have him thinking clearly and time has dulled memories, he acknowledges. But he knows he'd been lured by the streets, been involved with gang life for several years and was mad that one of his crew had recently been killed. He and some others went into the rival gang's turf on the night of September 30, 1965, when they saw another teen, a complete stranger. Miller walked up to him. Accused him of being in the rival gang. He shot him in the chest and walked away. , Miller and his friends were caught by police a short distance away, before they could do any more damage.                                                                                                                                                                                                                                                                                                                                                                                                                                                               , But if Miller doesn't remember all that much, his story has become well known in West Philly and the presence of CNN cameras one cold January morning attracts some hollers and hoots from passersby and a wave from an old friend.                                                                                                                                                                                                                                                                                                                                     , Then one man stops and calls out of his car. "Is this about Larry Miller and my uncle?" he asked the CNN crew. "I'm Edward White's nephew."                                                                                                                                                                                                                                                                                                                                                                                                                             , Edward David White was Miller's victim. He was 18, father of an 8-month-old and there was another baby on the way. He was going home from work, his family said, and had no gang ties.                                                                                                                                                                                                                                                                                                                                                                                  , Tyrone Kegler never met his great uncle -- he'd been born long after the murder. He still lived in the neighborhood but was surprised to find himself suddenly about to meet the man who had caused his family so much pain, so much turmoil, for so long.                                                                                                                                                                                                                                                                                                              , "Whoa I'm shaking," he tells CNN as he gets out of the car. "This story has just opened up a whole can of worms for us, we weren't expecting this," he says, his voice fading to a whisper.                                                                                                                                                                                                                                                                                                                                                                             , Miller wasn't expecting it either. But he takes the second chance. He greets Kegler with a handshake and talks for a few minutes. They part with a hug.                                                                                                                                                                                                                                                                                                                                                                                                                 , It's one of many second chances Miller has had and made work after mistakes in his life.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , He says he has thought about killing White every day of his life since it happened. It was not lost on Miller that White was a Black teenager, just like him. But Miller failed to name him in the book. He also failed to reach out to the dead man's family before he went public with his secret.                                                                                                                                                                                                                                                                    , He says he thought he was protecting their privacy, but now owns his mistake. Miller acknowledges that he should have been in touch earlier. And he wants to keep making amends.                                                                                                                                                                                                                                                                                                                                                                                        , "We are definitely in the process of trying to connect with them and make sure that they feel some healing out of this as well," he says. "You know, to me, if we can come up with a way to memorialize Mr. White, so that he isn't someone that's just forgotten, then this would be a positive."                                                                                                                                                                                                                                                                      , Miller has met White's relatives twice, according to Ronald Marrero, an attorney representing the White family who hosted the meetings at his office. Marrero said Miller apologized for not reaching out prior to publishing the book. Barbara Mack, White's sister, said she forgave him, explaining, "I must forgive in order to be forgiven," the attorney said.                                                                                                                                                                                                    , Miller co-wrote his book with his daughter Laila Lacy, who gave him a second chance after he hurt her. When Lacy was in college, her mother died. Miller did not show up for the funeral to be by his daughter's side.                                                                                                                                                                                                                                                                                                                                                  , "I can't justify it," he says of his absence. "I can only say that the reason I didn't go is because I just I couldn't deal with it. I couldn't deal with the fact of what was happening. I was just trying not to not to deal with it at all."                                                                                                                                                                                                                                                                                                                         , "He told me he just couldn't face it," Lacy says. "Once he said it, I understood that it was just too painful for him to come to grips with the fact that she was gone."                                                                                                                                                                                                                                                                                                                                                                                                , Miller says he believes Lacy now has some understanding of why he let her down, even as she needed him there. She not only stands by him now, she says she is proud of the man he has become.                                                                                                                                                                                                                                                                                                                                                                           , And much of the theme of the book is the second chances he was given -- and made the most of -- after going to prison for the murder of White.                                                                                                                                                                                                                                                                                                                                                                                                                          , His redemption was far from immediate. While prosecuted as an adult, he served only 4½ years before his release. He says he found a new purpose with the Nation of Islam. But he was sent back to prison when he tried to get money for the organization through armed robbery, extortion and selling drugs, even though all of that is against Islamic teachings.                                                                                                                                                                                                      , He got breaks then, too -- he calls them "blessings." He was penalized with just nine months' incarceration for violating his parole for White's murder. And his sentences for the robberies were ordered to run at the same time rather than one after another, so he served a total of another 4½ years for those.                                                                                                                                                                                                                                                    , He was also able to resume his education, first inside the prison using Pell grants available to inmates and then on a day-release program to attend college.                                                                                                                                                                                                                                                                                                                                                                                                           , "That's what really made me start to believe that I could actually change my life," he tells CNN.                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , "I was going to learn my way out of the lifestyle that I was living in the things that I was doing and that I was going to give education and opportunity to change my life."                                                                                                                                                                                                                                                                                                                                                                                           , Miller was smart, driven and had a goal of working for one of the top accounting firms. He was a handshake away from that, an offer ready in the inside pocket of a hiring manager for a major firm, when he says he shared the story of his murder conviction.                                                                                                                                                                                                                                                                                                         , The offer never made it to Miller's hand because of what he revealed about his criminal past he says. So Miller decided his past should fade away, too. He wouldn't lie, but he wouldn't be fully open either.                                                                                                                                                                                                                                                                                                                                                          , It worked. He says the Campbell Soup Company application simply asked if he had been convicted of a crime in the last five years, so he could truthfully say no.                                                                                                                                                                                                                                                                                                                                                                                                        , Many of his jobs after that didn't involve application forms, they were agreed with a handshake.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , But there were moments of abject fear over his secret, followed by temporary relief, he says, like when he underwent a background check to accept a dinner invitation from the Clinton White House.  Somehow he passed, and found himself sitting next to first lady Hillary Clinton discussing Chinese labor issues.                                                                                                                                                                                                                                                   , Miller's night terrors about his past hit a high when he became president of the Portland Trail Blazers, then often called the Jail Blazers for the run-ins players were having with the law. But still, his criminal past stayed private, something that he acknowledges is unlikely to happen for anyone today in the age of Google and electronic records.                                                                                                                                                                                                           , "I was concerned all the time that it could come out. And that's what I'm certain was causing the headaches and the nightmares because once I started sharing with my daughter, and started talking to her about all of this, and kind of getting it out, the nightmares stopped, the migraines stopped. And I know that was just letting this out," he says.                                                                                                                                                                                                           , It turns out that he may not have needed to worry once he had reached those heights. While preparing to break his silence, he turned to those he knew from leading the Jordan brand at Nike -- Nike co-founder Phil Knight, NBA Commissioner Adam Silver and Michael Jordan himself. To a man, he says, they supported him and his decision to speak now in the hope of stopping another teen heading into criminality, or encouraging someone in or who had left prison to turn their life around, and to encourage employers to look beyond a rap sheet.              , Miller says he thought every day of the young man he killed but had to push it to the back of his mind, afraid it would paralyze him, and concentrate on himself and his belief in his own intelligence and ability to get by and get ahead.                                                                                                                                                                                                                                                                                                                            , "It would always pop up. But I was able to always put it in the back of my mind and try to do some positive things to help offset it," he says.                                                                                                                                                                                                                                                                                                                                                                                                                         , Miller has said he would like to honor White in some way. He has had decades of success, but had never reached out to those he left devastated until now. White's family have asked him to establish a scholarship for students at West Philadelphia High School, where White once went.                                                                                                                                                                                                                                                                                , The White family said in a statement provided by their attorney, "The family hopes that Mr. Miller is truly remorseful. The family expects that Mr. Miller's actions will further exemplify that remorse by following through with the scholarship in honor of Edward David White."                                                                                                                                                                                                                                                                                     , Asked what the essence of his life's memoir was, the first thing Miller says is "redemption." A story that offers not only hope, but a pathway out of a cycle of violence.                                                                                                                                                                                                                                                                                                                                                                                              , As for making it up to the family of the man he gunned down, Miller has met with White's family twice. And there was that chance meeting with White's great nephew that ended in a hug. There's still a lot to be done, but on that West Philadelphia corner on a day in January, his life had come full circle.                                                                                                                                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/20/business/dealbook/the-class-of-2022-prepares-to-enter-a-work-world-in-flux.html </td>
   <td style="text-align:left;"> 2022-02-20 21:00:05 </td>
   <td style="text-align:left;"> College Seniors Prepare to Enter a Work World in Flux - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , DealBook newsletter                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , As workplaces transformed by the pandemic negotiate a “new normal,” DealBook asked college seniors across the country what they hope it will look like.                                                                                                                                                                                                                                                                                                                                                                                                                              , By Corinne Purtill                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The DealBook newsletter delves into a single topic or theme every weekend, providing reporting and analysis that offers a better understanding of an important issue in business. If you don’t already receive the daily newsletter, sign up here.                                                                                                                                                                                                                                                                                                                                   , The white-collar workplace has changed a lot over the last two years. Remote work has gone from a quirky perk to a common experience. Workers all the way up to the C-suite have reassessed what they want from a job. And expectations for when and where work must be done have evolved.                                                                                                                                                                                                                                                                                           , As executives scramble to merge remnants of the “before times” with pandemic-propelled work shifts, graduating college seniors are preparing to enter the work force for the first time. The new normal will be their first normal.                                                                                                                                                                                                                                                                                                                                                  , With nearly every aspect of their college experience upended, this year’s graduates are more accustomed than most to living alongside uncertainty. The roughly two million people who will earn a bachelor’s degree from a U.S. college or university this year pursued academic and professional ambitions amid campus closures, online classes and remote internships.                                                                                                                                                                                                             , For better or for worse, they are entering the new work landscape without the memory of prepandemic life to guide or sway their choices.                                                                                                                                                                                                                                                                                                                                                                                                                                             , DealBook spoke to 10 seniors who are graduating from universities across the U.S. about how they envision the trajectory of their careers — where they’ll work, how they’ll work and what factors might influence their choices. Their goals, interests and outlooks vary, but nearly all anticipate careers that are less linear and more dynamic than those of generations prior.                                                                                                                                                                                                  , And they’re ready for it. “I don’t care too much about change. It happens,” said Austin Rosas, 23, a Texas A&amp;M University economics major with a minor in mathematics. “Adaptation is what matters.”                                                                                                                                                                                                                                                                                                                                                                                 , Salaries and benefits are important. But for a growing number of younger workers, a company’s culture and values are at least as important as individual compensation.                                                                                                                                                                                                                                                                                                                                                                                                               , In a survey commissioned last year by the software firm Atlassian, 61 percent of millennial workers in the U.S. — currently the largest generation in the work force — said they preferred companies that take a stand on social issues, and 49 percent said they would quit a job that did not align with their values, both significant increases from the year before.                                                                                                                                                                                                            , Chief among those values are diversity and inclusiveness. The National Association of Colleges and Employers surveys graduates every year about what they’re looking for in an employer. The percentage of respondents who say that a company’s diversity is important or extremely important to them has grown every year since 2015, with 71.8 percent of this year’s students calling it a top priority, Andrea Koncz, the association’s research manager, said.                                                                                                                  , “In addition to values, the impact that an organization has will make or break my decision to begin and remain working in a particular place.”— Citlali Blanco, 22, human biology major at Stanford University                                                                                                                                                                                                                                                                                                                                                                       , “I hope my future workplace is an environment that is collaborative, inclusive and values their employees. I want a workplace where I feel safe and comfortable to share my voice, as well as a place where I will be able to continue and grow in the field I want to succeed in.”— Rebecca Hart, 22, public relations and strategic communications major at American University                                                                                                                                                                                                    , “My workplace will likely be within either a hospital or medical office, where I hope to see even greater equity between men and women in positions of leadership. I also hope that my workplace will be wholly inclusive and represent a diverse array of individuals, both among my colleagues and with the patients we serve each day.”— Selena Zhang, 21, computational biology major at Brown University                                                                                                                                                                        , The sort of knowledge-based tasks referred to as “office work” no longer must be done in an office. In the next few years, the number of people in the U.S. who do most or all of their job from a remote location is expected to surpass 36 million, said Johnny C. Taylor, chief executive officer at the Society for Human Resource Management — double the prepandemic number.                                                                                                                                                                                                   , What that looks like for every industry, company and team is in flux, often driven by employees who want to continue some of the benefits of the remote schedules imposed at the start of the pandemic. Hybrid schedules, flex schedules and work-where-you-want policies will play a much larger role in this generation’s careers.                                                                                                                                                                                                                                                 , “While I am really hoping to work in an office, I want it to be a fun one, an office where they expect me to show up on time and get my work done but allow me the freedom to be creative in my work and work space. I definitely want to work full-time. I love being almost too busy.”— Sidney Stull, 21, communications major at Boise State University                                                                                                                                                                                                                           , “As someone who works in tech, I’ve largely accepted that most of my work will be done at a desk in front of a screen. On one hand, I’m excited to see all the valuable serendipitous ideas and eureka moments that have long been promised to me. On the other, I find creative work to be quite a vulnerable process, and often appreciate being at home to explore whatever I’m thinking about.”— Oliver Feuerhahn, 21, business and social science major at Minerva University                                                                                                   , “Since I will be starting as an investment banking analyst, I expect that I will be in an office working full-time as per the industry standards. While this work setting may have fallen out of favor with other members of my generation, I honestly am looking forward to the opportunity.”— Costa Kosmidis, 22, finance major at Fordham University                                                                                                                                                                                                                              , With pay lagging behind inflation, making ends meet is harder today than it was a generation ago. The percentage of U.S. workers holding more than one job at a time has grown steadily over the last decade, according to census data. Less-formal surveys have found that younger workers are more likely than older colleagues to have a side hustle or second job. Nearly half of millennial respondents to a 2018 survey by the financial services company Bankrate said they worked a paid second gig at least some of the time. (Those surveys don’t count unpaid caregiving.), But a full-time job is just that. Some industries — notably finance — still put early-career employees on schedules that leave hardly enough time to shower and sleep, let alone to clock in somewhere else.                                                                                                                                                                                                                                                                                                                                                                         , “I see myself maybe doing consulting on the side. It is increasingly difficult nowadays to sustain one’s desired lifestyle without multiple streams of income, so that is something I have in the back of my mind.”— Sidney Stull                                                                                                                                                                                                                                                                                                                                                    , “I don’t expect to hold more than one job at a time. I’d rather hold a single full-time job that I’m super invested in.”— Abby Mapes, 22, computer science major at Duke University                                                                                                                                                                                                                                                                                                                                                                                                  , “I can’t imagine that I could stand that. I really care about time away from work and being able to spend time with people that I care about. Most importantly I want a work environment that will give me flexible hours to spend with my family, whenever that happens down the line.”— Wylie Greeson, 21, environmental geoscience and English major at The College of Wooster                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The accelerating pace of technological change gives birth to new fields and industries as fast as it demolishes old ones. A company or industry that’s thriving at graduation time may barely exist 20 years later. Couple that with longer life spans, and the likelihood that a current graduate will go through multiple careers in a lifetime is even higher.                                                                                                                                                                                                                    , “I really hope to have multiple careers. Realistically, I know I’ll work in a traditional-ish job until 30. Hopefully, I can shift my meaning of ‘work’ into something more project-based by 40. And by 50, start focusing on other enjoyable things in life. I think I’ll always want to contribute to interesting businesses as long as I can, but also don’t feel the need to absorb too much stress in the process.”— Oliver Feuerhahn                                                                                                                                           , “Even deciding what I wanted to pursue after graduation was difficult for me, so I don’t expect to work in the same field for the entirety of my career. Being able to learn and grow by doing is what drives me, and moving forward for me is about adapting and embracing new challenges through creative thinking.”— Amy Liu, 21, economics major at the University of California, Los Angeles                                                                                                                                                                                    , “I certainly hope I don’t! I think one of the great opportunities of life is to be able to go out and do so many things and gain so many experiences. I feel like I wouldn’t be living my life to its fullest if I did one job my entire career.”— Wylie Greeson                                                                                                                                                                                                                                                                                                                     , This generation likely won’t retire in the way their grandparents or great-grandparents did, both by need and by choice. Though many older workers have been pushed to retire prematurely during the pandemic, the trend toward longer life spans and the decline of cushy pensions will likely lengthen working lives.                                                                                                                                                                                                                                                              , This doesn’t have to be an arduous slog. A report released by the Stanford Center on Longevity last year called for careers to be paced differently, so that people work for more years, but with fewer work days in the week and fewer hours in the day.                                                                                                                                                                                                                                                                                                                            , “I expect to work until my mid-50s. I think I’ll always want to have something to do, but I see myself moving away from working full-time in an office in my mid-50s or early 60s.”— Abby Mapes                                                                                                                                                                                                                                                                                                                                                                                      , “I genuinely believe that if I’m still able to produce up-to-par work that supports my team and my career brings me happiness, then I’ll keep working past the golden years of retirement.”— Amy Liu                                                                                                                                                                                                                                                                                                                                                                                 , “I expect to work as long as I am stimulated from my work. If it lasts 10 years or the rest of my life, then so be it.”— Austin Rosas                                                                                                                                                                                                                                                                                                                                                                                                                                                , This year’s new hires have seen firsthand how quickly the world can change. It’s no surprise that most of them expect to see major shifts in companies during their careers.                                                                                                                                                                                                                                                                                                                                                                                                         , Some of these are already underway. As burnout and exhaustion have pushed workers to resign in droves, more companies are accelerating efforts to factor employee well-being into organizational productivity. Experiments around the world in a four-day workweek have proved both popular with workers and profitable for employers.                                                                                                                                                                                                                                               , “I’m excited for employees to be viewed more holistically, with mental, social, and physical needs that affect performance. It would be great to see workplaces promote community-building, adequate nutrition, environmental sustainability, fitness, and stress reduction. This would markedly improve the lives of so many people.”— Citlali Blanco                                                                                                                                                                                                                               , “I hope a four-day workweek becomes standard, and I hope that putting more of an emphasis on mental, emotional, and social health starts to prevail in the work force.”— Wylie Greeson                                                                                                                                                                                                                                                                                                                                                                                               , “I see the workplace becoming a lot more collaborative as the years go on. I see a breakdown of hierarchy that leads to a more team based organizational structure. I think this will be beneficial, not only for the work at hand but for the people doing the work.”— Sidney Stull                                                                                                                                                                                                                                                                                                 , What do you think? Let us know: dealbook@nytimes.com.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/20/uk/queen-elizabeth-coronavirus-intl-gbr/index.html </td>
   <td style="text-align:left;"> 2022-02-20 19:56:48 </td>
   <td style="text-align:left;"> Queen Elizabeth tests positive for Covid-19  - CNN </td>
   <td style="text-align:left;"> London (CNN)Britain's Queen Elizabeth II has tested positive for coronavirus, Buckingham Palace announced Sunday.                                                                                                                                                                                                                          , The 95-year-old sovereign -- who is celebrating her 70th year on the throne -- is experiencing mild cold-like symptoms but expects to continue light duties at Windsor over the coming week, the palace said.                                                                                                                              , "She will continue to receive medical attention and will follow all appropriate guidelines," it added.                                                                                                                                                                                                                                     , UK media have reported that the Queen is fully vaccinated. Buckingham Palace previously confirmed both the monarch and her late husband, Prince Philip, had received their first doses of a Covid-19 vaccine in January 2021. But the palace has declined to reveal any information about subsequent vaccinations, citing medical privacy. , The Queen is not the only person in her circle to test positive for Covid-19, a royal source said on Sunday.                                                                                                                                                                                                                               , "A number of cases have been diagnosed in the Windsor Castle team," the source told CNN, without specifying who else had tested positive.                                                                                                                                                                                                  , The Queen's health has been closely scrutinized since late last year when she retreated from public events on advice from doctors to rest after an overnight hospital stay for an undisclosed reason. Fresh concern was renewed in the past few days as multiple family members self-isolated after testing positive for the virus.        , Prince Charles, heir to the British throne, tested positive for Covid-19 for a second time 10 days ago while his wife, Camilla, Duchess of Cornwall, confirmed she too had the virus on Monday.                                                                                                                                            , A royal source confirmed at the time that the Queen had "recently" met her eldest son, but the source did not elaborate on exactly when the interaction had taken place.                                                                                                                                                                   , The Prince of Wales previously contracted coronavirus in March 2020, as countries around the world were first feeling the effects of the pandemic. Charles said at the time that he was first infected that he had been lucky only to experience mild symptoms, adding that he'd "got away with it quite lightly."                         , Prince William also tested positive for Covid-19 in 2020, though his infection wasn't revealed until months later.                                                                                                                                                                                                                         , The Queen's diagnosis comes days after she completed her first in-person engagement since returning to Windsor from Sandringham where she had marked the 70th anniversary of her accession to the throne and the death of her father, King George VI.                                                                                      , On Wednesday, the monarch held an audience with the outgoing Defence Services Secretary, Rear Admiral James Macleod, and his successor, Major General Eldon Millar, during which she appeared in good spirits.                                                                                                                             , On her return to Windsor, a royal source had told CNN the Queen was resuming her regular duties of audiences, credentials and privy council meetings.                                                                                                                                                                                      , She has made plans to appear at a number of major engagements next month: a diplomatic reception at Windsor Castle on March 2, the annual Commonwealth Service at Westminster Abbey on March 14; and a service of thanksgiving for Prince Philip at the same venue on March 29.                                                            , While all are still a few weeks away, the Queen's positive Covid-19 test may put her attendance in doubt.                                                                                                                                                                                                                                  , On Sunday, British Prime Minister Boris Johnson wished the Queen a "swift recovery" in a post on Twitter.                                                                                                                                                                                                                                  , "I'm sure I speak for everyone in wishing Her Majesty The Queen a swift recovery from Covid and a rapid return to vibrant good health," wrote Johnson, who contracted Covid-19 himself in March 2020, at the height of the first wave in the UK, spending three nights in ICU.                                                             , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/20/politics/fiona-hill-donald-trump-joe-biden/index.html </td>
   <td style="text-align:left;"> 2022-02-20 19:02:21 </td>
   <td style="text-align:left;"> Former top Trump Russia adviser details the sharp contrast between the former President and Biden  - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Fiona Hill doesn't know whether President Joe Biden can lead Western allies to ward off Russia's threat to Ukraine. But unlike his predecessor, he's trying.                                                                                                                                                                                                                                                                      , Hill has a special vantage point on this slow-rolling crisis that US officials say could bring war in Europe at any moment. As a White House national security aide, she advised then-President Donald Trump on Russia and Ukraine -- and became a star witness in impeachment proceedings that resulted from his conduct.                                                                                                              , Now, outside the government as a Brookings Institution senior fellow, she's among the Russia specialists Biden has consulted as he revives foreign policy priorities shared by every president since World War II except Trump.                                                                                                                                                                                                         , After Trump derided and weakened the North Atlantic Treaty Organization, Biden has rallied NATO on Ukraine's behalf.                                                                                                                                                                                                                                                                                                                    , After Trump pressured Russia's beleaguered neighbor for his personal benefit, Biden has steeled Americans for shared sacrifice in defense of Ukraine's right of self-determination.                                                                                                                                                                                                                                                     , After Trump deferred to Russian President Vladimir Putin over the US government's own intelligence agencies, Biden has deployed those agencies' tradecraft in a multi-pronged transatlantic effort to deter Russian aggression.                                                                                                                                                                                                         , "You couldn't get a sharper contrast," Hill observed in an interview.                                                                                                                                                                                                                                                                                                                                                                   , For the moment, at least, she sees Biden's approach paying some dividends.                                                                                                                                                                                                                                                                                                                                                              , As described in her recent memoir, There Is Nothing For You Here, Hill followed an unusual path to becoming one of America's leading experts on Russia. Raised in a working-class family in Britain, she parlayed academic scholarships into advanced degrees from Harvard and an analyst's job at the National Intelligence Council beginning in 2006 during President George W. Bush's administration.                                , Witnessing Britain's industrial decline helped her understand the populist appeals Trump rode to the White House. But the celebrity real-estate developer's handling of foreign policy in the Oval Office -- driven not by expertise or the national interest but by his personal experiences, impulses and interests -- was like nothing Hill or her national security colleagues had ever seen.                                       , "There's no Team America for Trump," Hill recalled. "Not once did I see him do anything to put America first. Not once. Not for a single second."                                                                                                                                                                                                                                                                                       , It showed in Trump's praise for the authoritarian leader of Russia, an American adversary that had boosted his finances as a business executive. It showed in his reluctance to embrace America's mutual defense commitments to European allies, which for decades have constrained Russian behavior; instead, Trump treated NATO as what Hill called a "protection racket."                                                            , Most notoriously, it showed in Trump's attempt to squeeze Ukraine's President for manufactured dirt on Biden to help his 2020 election campaign. He held up American military aid as a political lever as Ukraine faced the long-running Russian military threat that now has the entire world on edge.                                                                                                                                 , "All this did was say to Russia that Ukraine was a playground," Hill said.                                                                                                                                                                                                                                                                                                                                                              , At home, Trump softened Republicans' once-hawkish approach to Russia. Today, the leading Fox News hosts and other conservative voices -- "the ultimate stooges," as Hill calls them -- buttress Russian arguments as armed conflict looms.                                                                                                                                                                                              , Yet even friendly foreign counterparts found limitations in Trump's scattershot style, which for Hill evokes the old saw about "playing chess with a pigeon." Russia's bid to upend the post-Cold War security order in Europe, beginning in 2008 with its invasion of Georgia and continuing with its 2014 seizure of Crimea -- requires a steadier negotiating partner.                                                               , "Ultimately Putin wants some kind of deal," Hill said. "They think Biden is the kind of president who could actually make a deal. Trump never could."                                                                                                                                                                                                                                                                                   , So far, Biden has held NATO allies together in rejecting Russia's core demands, bolstering their forces in Europe and threatening punishing sanctions even though they guarantee domestic economic blowback. Steeped in decades of bipartisan foreign policy consensus, the Democratic President has also drawn support from top Republicans such as Senate Minority Leader Mitch McConnell who have shunned Trump's embrace of Putin.  , That demonstration of resolve has at minimum made Putin stop and think. Biden has warned for weeks that Russia could launch a new invasion of Ukraine at any time. It hasn't yet.                                                                                                                                                                                                                                                       , "They might have thought we were going to crumble, and we didn't," said Hill, who became an American citizen twenty years ago. "It might have deterred a full-scale invasion. Now (Putin) is basically recalibrating, recalculating."                                                                                                                                                                                                   , But durable success for Biden and European allies will depend on staying power. Even if Russian tanks don't roll across the border, Hill envisions an extended "boa constrictor" siege in which Putin applies escalating pressure in hopes of bending Ukraine to Russia's will.                                                                                                                                                         , "The real challenge is keeping everyone together for a considerable period," Hill concluded. "It's going to go on a long time."                                                                                                                                                                                                                                                                                                         , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/20/business/economy/spokane-housing-expensive-cities.html </td>
   <td style="text-align:left;"> 2022-02-20 16:00:12 </td>
   <td style="text-align:left;"> Spokane was the Next Affordable City. Now, It's Too Expensive. - The New York Times </td>
   <td style="text-align:left;"> The Great Read                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , In Spokane, Wash., home prices jumped 60 percent in the past two years. The increase is fueled by buyers fleeing the boom in cities like Austin. Who will have to flee next?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Credit...Rajah Bose for The New York Times                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , By Conor Dougherty                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Maybe it was the date night when he and his wife spent two hours driving 19 miles to dinner, or the homeless encampment down the street, or the fact that homes were so expensive that his children could never afford to live near him.                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Whatever the reasons, and there were many, Steve MacDonald decided he was done with Los Angeles. He wanted a city that was smaller and cheaper, big enough that he could find a decent restaurant but not so much that its problems felt unsolvable and every little task like an odyssey. After the pandemic hit and he and his wife went through a grand reprioritizing, they centered on Spokane, where their son went to college. They had always liked visiting and decided it would be a nice place to move.                                                                                                                                                                                                  , Eastern Washington was of course much colder. Until this winter, Mr. MacDonald, a native Southern Californian, had never shoveled snow. But their new house is twice as big as their Los Angeles home, cost less than half as much and is a five-minute commute from City Hall, where Mr. MacDonald works as Spokane’s director of community and economic development.                                                                                                                                                                                                                                                                                                                                              , He arrives each day to tackle a familiar conundrum: how to prevent Spokane from developing the same kinds of problems that people like him are moving there to escape.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , “I’m realizing more and more how important the future prosperity of this city is about getting housing right,” he said. “If we don’t, it’s going to track more closely with what happened in Los Angeles.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Mr. MacDonald knows the pattern, and so does everyone else who has been following the frenetic U.S. housing market for the past decade. The story plays out locally but is national in scope. It is the story of people leaving high-cost cities because they’ve been priced out or become fed up with how impossible the housing problem seems. Then it becomes the story of a city trying to tame prices by building more housing, followed by the story of neighbors fighting to prevent it, followed by the story of less expensive cities being deluged with buyers from more expensive cities, followed by the less expensive cities descending into the same problems and struggling with the same solutions., It’s easier to change where we live than it is to change how we live.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Whether it’s Boise or Reno or Portland or Austin, the American housing market is caught in a vicious cycle of broken expectations that operates like a food chain: The sharks flee New York and Los Angeles and gobble up the housing in Austin and Portland, whose priced-out home buyers swim to the cheaper feeding grounds of places like Spokane. The cycle brings bitterness and “Don’t Move Here” bumper stickers — and in Spokane it has been supercharged during the pandemic and companies’ shift to remote work.                                                                                                                                                                                         , No matter how many times it happens, no matter how many cities and states try to blunt it with recommendations to build more housing and provide subsidies for those who can’t afford the new stuff, no matter how many zoning battles are fought or homeless camps lamented, no next city, as of yet, seems better prepared than the last one was.                                                                                                                                                                                                                                                                                                                                                                 , Just a few years ago, a Spokane household that made the median income could afford about two-thirds of the homes on the market, according to Zillow. Now home prices are up 60 percent over the past two years, pricing out broad swaths of the populace and fomenting an escalating housing crisis marked by resentment, zoning fights and tents.                                                                                                                                                                                                                                                                                                                                                                  , Being an “it” place was something Spokane’s leaders had long hoped for. The city and its metropolitan region have spent decades trying to convince out-of-town professionals and businesses that it would be a great place to move. Now their wish has been granted, and the city is grappling with the consequences.                                                                                                                                                                                                                                                                                                                                                                                               , Growth is never perfect, and Spokane’s influx has been accompanied by a booming employment market that has increased wages, turned abandoned warehouses into offices and helped the city recover jobs lost during the pandemic. This is normally called progress. But for people who already lived in and around Spokane or the suburbs just across the border in north Idaho, the shift from living in a place that was broadly affordable to broadly not has come on with the suddenness of a car crash. Now many workers are wondering what the point of growth is if it only makes it harder to keep a roof over their head.                                                                                    , Even the mayor isn’t immune. In an interview, Nadine Woodward, a Republican who was elected in 2019, noted that her son and daughter-in-law, newlyweds who moved home during the pandemic, were living with her and her husband while they figured out where they could afford to settle. They came back to Spokane from Seattle, where they were long ago priced out. Austin was the next city on their list, but then its home prices shot up to about where Seattle’s were when they left. At this point, even Spokane is seeming pricey.                                                                                                                                                                        , “I never thought I’d see the day where my adult children couldn’t afford a home in Spokane,” Ms. Woodward said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Standing by a snow-covered lawn on an overcast afternoon, Steve Silbar, a local real estate agent who has been selling homes for five years, explained Spokane’s transformation in terms of a six-inch screen. When he thinks of a typical buyer, Mr. Silbar said, he imagines a couple thousands of miles away, perhaps on a beach, looking at their phones. They’re considering moving to a cheaper city, and do a search for homes.                                                                                                                                                                                                                                                                              , Clients like this are why Mr. Silbar invested $3,000 in a camera that allows him to create three-dimensional tours of his listings, and why the exterior of every home he sells is showcased with an aerial video shot by a drone. In a market that attracts so many outsiders, a virtual walk through the interior and bird’s-eye flight over the street can be the nudge buyers need to bid on a home they’ve never entered, in a city they’ve never seen.                                                                                                                                                                                                                                                        , “I have to assume that the person that is looking at my listing has never been to Spokane, does not know about Spokane, has no clue,” Mr. Silbar said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Spokane is the largest city on the road from Seattle to Minneapolis. This fact is frequently cited as the logic behind its economy: It’s between things. The city was incorporated in 1881 and grew into a transportation hub for the surrounding mining and logging industries. It remains a hub, only instead of shipping out timber and silver, businesses revolve around Fairchild Air Force Base and a collection of hospitals and universities that draw from the rural towns that stretch from eastern Washington to northern Idaho and into western Montana.                                                                                                                                                , The transition from past to present plays out across a skyline in which the usual collection of anonymous bank and hotel towers is broken up by historic brick buildings that seem to be either in a state of abandonment or rehabilitation or occupied by low-rent tenants while waiting for redevelopment. The current boom has already made its mark in the form of new apartment towers, warehouses turned office buildings and an empty lot that will soon contain a 22-story building that will be the city’s tallest.                                                                                                                                                                                        , Driving around town, Michael Sharapata, a commercial real estate broker who moved to Spokane from the Bay Area in 2017, gave a staccato accounting of new leases, such as the millions of square feet that Amazon occupies out by the airport, or the satellite offices rented by various regional accounting and building firms.                                                                                                                                                                                                                                                                                                                                                                                   , His family is coming, too. After Mr. Sharapata and his wife moved north, they were followed, in rapid succession, by his brother-in-law in Austin, another brother-in-law in the Bay Area and his sister-in-law in Salt Lake City.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , “We were looking for an affordable community that had an opportunity to accommodate all of us,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , As in most of urban America, much of the growth in the Spokane area is on the fringes, where heavy equipment and the skeletal outlines of new subdivisions unfold in every direction and into Idaho. Building permits have surged, and the cadre of mostly local builders who had the market more or less to themselves now grumble that the rapid growth has attracted big national builders like D.R. Horton and Toll Brothers.                                                                                                                                                                                                                                                                                   , All of this happened fairly recently. In the years after the Great Recession, when homebuilders were in bankruptcy or hibernation, migration to the Spokane region plunged. That pattern shifted in 2014 when, as if a switch had been flipped, waves of migrants started arriving as already high-cost cities like Seattle and San Francisco saw their housing markets go into a tech-fueled frenzy.                                                                                                                                                                                                                                                                                                               , By the end of 2014, migration to the Spokane region had jumped to more than 2,000 net new residents, compared with a net loss the year before, according to Equifax and Moody’s Analytics. Annual growth has only continued, rising further with the pandemic to more than 4,500 net new residents.                                                                                                                                                                                                                                                                                                                                                                                                                 , Sometimes they come for the chance to buy their first home. Other times it’s a bigger house or some land. Joel Sweeney, an academic adviser at Eastern Washington University, wanted the best of both: a single-family house on a quiet street that was close enough to downtown that he could walk to a good brewery. That sort of Goldilocks urbanity could cost a million in Austin, where he and his wife lived until last year. When they moved to Spokane they paid less than a third of that.                                                                                                                                                                                                                , “You could not get a house for $299,000 in Austin where you could walk to a bunch of different stuff,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The white house with the red door sits on a quiet block near Gonzaga University. It has two bedrooms, one bathroom and 1,500 square feet of living space.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Mr. Silbar, the real estate agent, has sold it twice in the past three years. The first time, in November 2019, he represented a buyer who offered $168,000 and got it with zero drama. This year it went back on the market, and Mr. Silbar listed it for $250,000. Fourteen offers and a bidding war later, it closed at $300,000.                                                                                                                                                                                                                                                                                                                                                                                , When Mr. Silbar got into the business, he said, his clients were “nurses and teachers,” and now they’re corporate managers, engineers and other professionals. “What you can afford in Spokane has completely changed,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The typical home in the Spokane area is worth $411,000, according to Zillow. That’s still vastly less expensive than markets like the San Francisco Bay Area ($1.4 million), Los Angeles ($878,000), Seattle ($734,000) and Portland ($550,000). But it’s dizzying (and enraging) to long-term residents.                                                                                                                                                                                                                                                                                                                                                                                                           , Five years ago, a little over half the homes in the Spokane area sold for less than $200,000, and about 70 percent of its employed population could afford to buy a home, according to a recent report commissioned by the Spokane Association of Realtors. Now fewer than 5 percent of homes — a few dozen a month — sell for less than $200,000, and less than 15 percent of the area’s employed population can afford a home. A recent survey by Redfin, the real estate brokerage, showed that home buyers moving to Spokane in 2021 had a budget 23 percent higher than what locals had.                                                                                                                       , One of Mr. Silbar’s clients, Lindsey Simler, a 38-year-old nurse who grew up in Spokane, wants to buy a home in the $300,000 range but keeps losing out because she doesn’t have enough cash to compete. Spokane isn’t so competitive that it’s awash in all-cash offers, as some higher-priced markets are. But prices have shot up so fast that many homes are appraising for less than their sale price, forcing buyers to put up higher down payments to cover the difference.                                                                                                                                                                                                                                  , A dozen failed offers later, Ms. Simler has decided to sit out the market for a while because the constant losing is so demoralizing. If prices don’t calm down, she said, she’s thinking about becoming a travel nurse. With the health care work force so depleted by Covid-19, travel nursing pays much better and, hopefully, will allow her to save more for a down payment.                                                                                                                                                                                                                                                                                                                                   , “I’m not at the point where I want to give up on living in Spokane, because I have family here and it feels like home,” she said. “But travel nursing is going to be my next step if I haven’t been able to land a house.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , From her seventh-floor office atop the Art Deco City Hall, Ms. Woodward, the mayor, looked out at the Spokane River, where in the warmer months a gondola glides past her window to a park built for the World’s Fair. Spokane hosted the fair in 1974 as a means of revitalizing its blighted downtown, and during the recent interview Ms. Woodward pointed out the window at cranes and construction sites that she calls “positive activity.”                                                                                                                                                                                                                                                                   , Spokane’s job market is among of the strongest in the nation, and the virtuous economic cycle — of people coming for housing, causing businesses to come for people, causing more people to come for jobs — is in full swing. And yet, as in Seattle and California before and increasingly across the nation, the scourge of rising prices, particularly for rent and housing, makes it feel less virtuous than advertised.                                                                                                                                                                                                                                                                                        , The recent Realtors report warned of “significant social implications” if the city doesn’t tackle housing. The issues included young families not being able to buy or taking on excessive debt, small businesses not being able to hire, difficulty keeping young college graduates in town.                                                                                                                                                                                                                                                                                                                                                                                                                       , In the dominoes of the housing market, the disappointments of aspiring buyers like Ms. Simler get magnified as they move down to lower-income households. With homes so hard to buy, rents have shot up, and the vacancy rate for apartments is close to zero.                                                                                                                                                                                                                                                                                                                                                                                                                                                      , All of this has compounded at the lowest end of the market, where the nonprofit Volunteers of America’s Eastern Washington and Northern Idaho affiliate, which runs three shelters and maintains 240 apartments for people who were formerly homeless, said it will lose a quarter of its units in the next fiscal year as more of its funding goes to higher rents.                                                                                                                                                                                                                                                                                                                                                , In December, as temperatures dropped and shelters filled, advocates and members of the homeless population protested by setting up several dozen tents on the City Hall steps. The encampment was gone two weeks later but has since been reconstructed on a patch of dirt on the other side of town. In the winter cold it smells like ash and soot from the open fires burning to keep people warm.                                                                                                                                                                                                                                                                                                               , Last year, Ms. Woodward declared a housing emergency, and her administration has put in place initiatives that mirror those of housing-troubled cities on the West Coast. The city has built new shelters, is encouraging developers to repurpose commercial buildings into apartments, is making it easier for residents to build backyard units and is rezoning the city to allow duplexes and other multiunit buildings in single-family neighborhoods.                                                                                                                                                                                                                                                          , Ms. Woodward pointed to Kendall Yards, one of the developments outside her City Hall window, as an example of what she wanted to see more of. The mixed-density project could be a postcard picture of what economists and planners say is needed to combat the nation’s housing shortage and sprawl. In defiance of the single-family zoning laws that dictate the look of most U.S. neighborhoods, Kendall Yards has houses next to townhomes next to apartments, with retail and office mixed in.                                                                                                                                                                                                                , People in town seem to love it, but are leery of there being more places like it, especially in their neighborhood.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , “I think it’s awesome — I have friends there, and we go down there to the farmers’ market and walk around,” said John Schram, a co-chair of the neighborhood council in Spokane’s Comstock neighborhood. “That’s just not my vision of what I want for me. My concern is that I move into a neighborhood because of the way that it was designed when I got there, and when somebody else comes in and wants to change that I’m going to be concerned.”                                                                                                                                                                                                                                                             , He added: “I have nothing against duplexes and triplexes, just not next to my house.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/02/19/cnn-team-mortar-fire-ukraine-nr-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-20 06:51:31 </td>
   <td style="text-align:left;"> CNN team in Ukraine comes under mortar fire - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/us/2022/02/19/helicopter-crashes-into-ocean-miami-sot-nr-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-20 05:46:38 </td>
   <td style="text-align:left;"> Video captures helicopter crashing into ocean near Miami Beach - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/technology/future-5g-development-wireless-companies-not-government </td>
   <td style="text-align:left;"> 2022-02-20 04:36:09 </td>
   <td style="text-align:left;"> Future of 5G development, rollout lies with wireless companies, not federal government: former official </td>
   <td style="text-align:left;"> Verizon Communications Chief Marketing Officer Diego Scotti argues that in order 'for people to be able to combine the real physical world with experiences that happen digitally,' 5G is needed.                                                                                                                                                                                                                                            , America needs to step up its 5G capabilities to keep pace with China, but the path forward lies in the hands of mobile carriers, according to a former FCC commissioner.                                                                                                                                                                                                                                                                     , Google’s former CEO Eric Schmidt wrote an op-ed in the Wall Street Journal that raised the alarm over America’s lagging 5G capabilities in comparison to China. America's average 5G mobile speed is roughly 75 megabits per second compared to China's average of 300 megabits per second in urban centers, and Schmidt claimed that 5G speeds in Boston, Chicago and New York City are at least 10% slower than that of 4G.                , An advantage in 5G provides fertile territory for developing new applications and stronger economic and national security potential. Schmidt argued that Washington must prioritize the development and rollout of 5G and commit greater resources to develop the "digital highway" the way it did the national highway system or face a future in which China dictates the use of 5G.                                                       , VERIZON EXEC SAYS 5G NETWORK DESIGNED ‘WITH THE METAVERSE IN MIND’                                                                                                                                                                                                                                                                                                                                                                           , But Robert McDowell, a former FCC commissioner and partner at Cooley LLP, argues that the success of developing 5G lays in the hands of mobile carriers, not the federal government.                                                                                                                                                                                                                                                         , Former Federal Communications Commissioner Robert McDowell (Reuters)                                                                                                                                                                                                                                                                                                                                                                         , "Let’s model what has worked in the past: The best predictor of future success is how you achieved previous success, and historically, success in the US in the American wireless sector came to be by government largely getting out of the way to let the private sector do its thing," McDowell, who served as a commissioner from 2006 to 2013, explained to FOX Business. "That’s how the U.S. built the best 4G networks in the world.", McDowell said the biggest issue is having "spectrum in the pipeline" – in other words, freeing up bandwidth for enterprise use.                                                                                                                                                                                                                                                                                                              , FORMER GOOGLE CEO COMMITS $125M TO LAUNCH AI INITIATIVE                                                                                                                                                                                                                                                                                                                                                                                      , "We were allocating spectrum for 4G in 2007, and the FCC had a watershed vote in July of 2007 to establish an auction for the 700 megahertz band," McDowell said. "Both Republicans and Democrats have come to love spectrum auctions as an efficient way to allocate spectrum and raise money for the Treasury without raising taxes."                                                                                                      , Schmidt in his op-ed explained that America’s 5G and 4G networks use the same spectrum bands, creating "4G with sprinkles on it." The FCC under Ajit Pai repurposed around 5000 megahertz of spectrum, with only some of that bandwidth allocated for 5G and next-gen WiFi use, according to Reuters.                                                                                                                                        , This year could see another auction, which McDowell called the 2.5 gigahertz auction, that would set up more bandwidth for use and hopefully expand the network.                                                                                                                                                                                                                                                                             , "But after that, there’s almost nothing – truly - in the spectrum pipeline," McDowell added. "Congress has to come together with FCC and Department of Commerce and other federal agencies to identify bands and set up more auctions. Also, the FCC’s authority to hold spectrum auctions expires on September 30, unless Congress acts."                                                                                                   , SMALL BUSINESSES INCORPORATING NEW TECHNOLOGY TO SURVIVE THE CORONAVIRUS PANDEMIC                                                                                                                                                                                                                                                                                                                                                            , Biden’s recent infrastructure spending bill included more than $62 billion outlays for wireless and broadband infrastructure, including everything from towers to fiber, antennas and gear to help carry signal farther.                                                                                                                                                                                                                     , The question that hangs over the development of 5G is the future of 6G: The standards for 6G remain in the early stages of design, and McDowell explained that it takes "the better part of a decade" from the time officials identify spectrum to the time they create an auction and sell it.                                                                                                                                              , Former Federal Communication Commission Chairman Ajit Pai testifies before the House Energy and Commerce Committee's Communications and Technology Subcommittee in the Rayburn House Office Building on Capitol Hill December 05, 2019 in Washington, DC.  (Photo by Chip Somodevilla/Getty Images / Getty Images)                                                                                                                           , But the potential that 6G represents could far outweigh what 5G is currently capable of.                                                                                                                                                                                                                                                                                                                                                     , "The standards for 6G are still in the very early stages of design," according to McDowell. "Going from 3G to 4G was a quantum leap and gave birth to the App economy. We can’t know exactly what innovation will come from 5G or certainly 6G."                                                                                                                                                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                  , "In 2007 when we were designating spectrum bands for 4G no one, not even the best and brightest, was predicting the App economy," he added. "So today we don’t know exactly what surprising innovations may be coming over the horizon or what’s coming up as the result of 5G or 6G.  And that’s exciting, and it can be frightening for some, in a way, all at the same time."  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/19/business/mexico-avocado-ban-lifted.html </td>
   <td style="text-align:left;"> 2022-02-20 03:04:50 </td>
   <td style="text-align:left;"> U.S. Lifts Temporary Ban on Avocados From Mexico - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                            , Supported by                                                                                                                                                                                                                                                                                                                             , The ban was issued last week after a U.S. inspector was verbally threatened in the state of Michoacán in Mexico.                                                                                                                                                                                                                         , By Eduardo Medina                                                                                                                                                                                                                                                                                                                        , The United States lifted a temporary ban on avocados from Mexico on Friday, allowing exports of the fruit to resume, the U.S. Department of Agriculture said.                                                                                                                                                                            , The ban had been issued on Feb. 11 after a verbal threat was made to a U.S. inspector working in the country. That prompted the U.S.D.A. to warn that the suspension would “remain in place for as long as necessary to ensure the appropriate actions are taken” to secure the safety of inspection service personnel working in Mexico., On Friday, the department said in a statement that it worked with agencies in Mexico to enact more safety measures for its inspectors. It did not elaborate on those measures.                                                                                                                                                           , “The safety of U.S.D.A. employees simply doing their jobs is of paramount importance,” the department said. “U.S.D.A. is appreciative of the positive, collaborative relationship between the United States and Mexico that made resolution of this issue possible in a timely manner.”                                                  , The ban had been expected to negatively affect the western state of Michoacán in Mexico, the only region approved in Mexico to send avocados to the United States.                                                                                                                                                                       , Annual exports there total nearly $3 billion, with the bulk going to the United States, where 80 percent of the avocados consumed come from Mexico and the average price of $1.43 an avocado was already nearly 11 percent higher than a year ago.                                                                                       , Details of the threat made to the employee were not made public. However, the avocado industry has attracted the interest in the past decade of drug cartels, which have become more fragmented and sought ways to diversify their illicit income streams.                                                                               , The Association of Avocado Exporting Producers and Packers of Mexico, which represents 29,000 avocado farmers and 65 packing houses in Michoacán, said in a statement on Friday that it proposed the creation of an “intelligence and security unit” within the association that would “support the export program.”                     , Both countries agreed to the proposal, which also included a security plan from the government of Michoacán, though specifics of that plan were not released.                                                                                                                                                                            , Armando López Orduña, the director general of the association, thanked Mexico and the United States, saying that their support had avoided, “to the extent possible, the impact on supply.”                                                                                                                                              , The export of Mexican avocados to the United States is set to resume on Monday.                                                                                                                                                                                                                                                          , The ban came just before one of the biggest events for the avocado industry, the Super Bowl. Concerns had been growing over whether the ban would affect the industry’s other big day in the year, Cinco de Mayo.                                                                                                                        , Mark Davidson, an administrator at the Animal and Plant Health Inspection Service’s plant protection and quarantine program, said in a statement that all parties were glad to see a resolution.                                                                                                                                         , “The popularity of Mexican avocados is undeniable,” he said.                                                                                                                                                                                                                                                                             , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/19/business/russia-has-been-laying-groundwork-online-for-a-false-flag-operation-misinformation-researchers-say.html </td>
   <td style="text-align:left;"> 2022-02-20 02:49:47 </td>
   <td style="text-align:left;"> Russia has been laying groundwork online for a ‘false flag’ operation, misinformation researchers say. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , By Davey Alba                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , At the White House this week, President Biden said the United States had “reason to believe” that Russia was “engaged in a false flag operation” to use as an excuse to invade Ukraine.                                                                                                                                                                                                                                                                                                                                                                          , A new report by the European Expert Association, a research group that focuses on security in Ukraine, and the technology watchdog group Reset Tech said that since October, misinformation researchers had observed rumors circulating widely online and in Russian news media that could be groundwork for such an operation, or to help justify a military buildup.                                                                                                                                                                                           , Many of the rumors first started circulating on anonymous Telegram channels, and were then repeated in televised statements by Russian officials, the report said. Others started with statements from Russian officials and were repeated on Telegram channels until they became talking points among ordinary citizens.                                                                                                                                                                                                                                        , “The rhetoric of the pro-Kremlin sources lately has become much more aggressive,” Maria Avdeeva, research director at the European Expert Association, said.                                                                                                                                                                                                                                                                                                                                                                                                     , At the request of The New York Times, the Global Disinformation Index, a nonprofit research group, independently evaluated the report and said the research appeared reliable.                                                                                                                                                                                                                                                                                                                                                                                   , Here are some of the unsupported claims the European Expert Association researchers found.                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , On Dec. 21, the Russian defense minister, Sergey Shoigu, alleged that the Ukrainian army was preparing to attack two separatist-held territories in Ukraine. The next day, the state-owned news agency RIA Novosti published a report that claimed, without proof, that a stash of chemical weapons had been given to Ukraine by the United States, according to the researchers.                                                                                                                                                                                , Throughout January and February, the researchers said, Russian-backed media spread the rumor, which was amplified on social media. “Chemical weapons are already present on the territory of Ukraine,” said a message in one anonymous Telegram channel with 24,500 followers. The post was viewed by 7,000 people.                                                                                                                                                                                                                                              , Russian state media has been spreading rumors that the Armed Forces of Ukraine are planning an attack on Donbas, the separatist region in eastern Ukraine, with the help of American, British and Polish mercenaries, according to the researchers.                                                                                                                                                                                                                                                                                                              , The rumor then spread on Facebook and YouTube. “The Ukrainian people are waiting for Mother Russia to free their younger sister from the Nazis and the State Department,” said one Facebook post that collected nearly 100 likes. On YouTube, a video spreading the same unproven claim collected more than 31,600 views.                                                                                                                                                                                                                                        , In this narrative, the Russians accuse the Ukrainians and Americans of planting a false flag.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Since Jan. 30, all 15 of Ukraine’s nuclear power plants have been generating electricity, marking the longest stretch of full utilization of nuclear energy in the country. That comes as Ukraine’s authorities decided to disconnect from the power grid with Belarus and the Russian Federation and implemented the plan to do so.                                                                                                                                                                                                                             , Russian state media began to spread the idea that Ukraine was overestimating its ability to keep up with its energy needs, and that the country’s nuclear facilities were in dire need of repair. The Russian media implied that Western countries could be organizing to attack the nuclear facilities and place the blame on Russia.                                                                                                                                                                                                                           , On Feb. 12, a Telegram channel with over 15,000 followers posted that the British Special Air Service was preparing an attack on one of Ukraine’s power plants.                                                                                                                                                                                                                                                                                                                                                                                                  , And on Feb. 15, the Telegram channel of a Russian war correspondent, Aleksander Kots, alleged that Ukraine had asked for special equipment from the United States to help mitigate a possible natural disaster, including to help with radiation and chemical fallout, according to the researchers. Mr. Kots added the unfounded accusation that the Ukrainians were devising a false-flag event — accusing Russia of preparing a terrorist attack against a nuclear power plant. His comments were seen by 83,900 people on Telegram, the researchers reported., Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/eni:im </td>
   <td style="text-align:left;"> 2022-02-19 20:41:20 </td>
   <td style="text-align:left;"> Eni Group earnings above expectations at 0.58 EUR </td>
   <td style="text-align:left;"> Eni Group (ENI) released earnings per share at 0.58 EUR, compared to market expectations of 0.57 EUR. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/politics/2022/02/19/trump-classified-documents-national-archives-ebof-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-19 20:26:35 </td>
   <td style="text-align:left;"> Could Trump face charges over classified docs? Hear what ex-prosecutor thinks - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/calendar?article=29134&amp;g=top&amp;importance=2&amp;startdate=2022-02-19 </td>
   <td style="text-align:left;"> 2022-02-19 20:01:00 </td>
   <td style="text-align:left;"> Investors Brace for Another Rollercoaster Week </td>
   <td style="text-align:left;"> A standoff between Russia and Ukraine will dominate again the markets with Moscow changing the rhetoric on a daily basis and Washington continuing to give warnings of an impending invasion. On the data front, Markit services and manufacturing PMI's from the US, UK, Germany, France, Euro Area and Japan will be in the spotlight. In the US, investors will again be looking for signs of whether the Federal Reserve would turn more hawkish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bhp:us </td>
   <td style="text-align:left;"> 2022-02-19 19:23:58 </td>
   <td style="text-align:left;"> Bhp Billiton Bhp earnings meet market expectations at 1.67 USD </td>
   <td style="text-align:left;"> Bhp Billiton Bhp (BHP) released earnings per share at 1.67 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/19/business/covid-economy.html </td>
   <td style="text-align:left;"> 2022-02-19 18:00:23 </td>
   <td style="text-align:left;"> Pandemic’s Economic Impact Is Easing, but Aftershocks May Linger - The New York Times </td>
   <td style="text-align:left;"> , States are lifting mask mandates, and demand is bouncing back quickly after Omicron. Supply constraints are proving harder to escape.                                                                                                                                                                                                                                                                                                                                                                                                        , Shoppers in New York. Job growth and retail spending have been strong recently, but Americans report feeling gloomier about the economy now than early in the crisis.Credit...Amir Hamja for The New York Times                                                                                                                                                                                                                                                                                                                              , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , By Ben Casselman                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The pandemic’s grip on the economy appears to be loosening. Job growth and retail spending were strong in January, even as coronavirus cases hit a record. New York, Massachusetts and other states have begun to lift indoor mask mandates. California on Thursday unveiled a public health approach that will treat the coronavirus as a manageable long-term risk.                                                                                                                                                                        , Yet the economy remains far from normal. Patterns of work, socializing and spending, disrupted by the pandemic, have been slow to readjust. Prices are rising at their fastest pace in four decades, and there are signs that inflation is creeping into a broader range of products and services. In surveys, Americans report feeling gloomier about the economy now than at the height of the lockdowns and job losses in the first weeks of the crisis.                                                                                  , In other words, it may no longer be that “the virus is the boss” — as Austan Goolsbee, a University of Chicago economist, has put it. But the changes that it set in motion have proved both more persistent and more pervasive than economists once expected.                                                                                                                                                                                                                                                                               , “I — totally naïvely — thought that once a vaccine was available, that we were six months away from a complete re-evaluation of the economy, and instead we’re just grinding it out,” said Wendy Edelberg, director of the Hamilton Project, an economic policy arm of the Brookings Institution. “A switch didn’t get flipped, and I thought it was going to.”                                                                                                                                                                              , The resulting limbo is a challenge for the Biden administration, which has so far failed to convince a skeptical public that its economic policies are working, despite falling unemployment and a recovery that has surpassed the most optimistic projections by most measures. And it is a challenge for policymakers at the Federal Reserve, who have struggled to assess how long the pandemic’s disruptions will last or the best way to mitigate their effects.                                                                        , It is also a challenge for business owners like Katherine Raz.                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Ms. Raz owns The Fernseed, a plant and flower shop with two locations in Tacoma, Wash. Like many retailers, the business has ridden the Covid-19 roller coaster: After closing for two and a half months at the beginning of the pandemic, Ms. Raz was able to reopen, and she even expanded the business in the summer of 2020. But a wave of cases later that year and a new round of government restrictions pushed the business to the brink and forced Ms. Raz to lay off one of her seven employees.                                   , In some ways, 2021 followed a similar pattern. Business boomed in the spring as falling case levels and rising vaccination rates fed optimism that the pandemic was nearing its end. Then the Delta and Omicron waves led to a drop-off in demand and created staffing challenges.                                                                                                                                                                                                                                                           , This time, though, Ms. Raz was ready. She had built up a financial buffer and had invested in product lines less likely to suffer when cases rose. She reduced employees’ hours when business slowed, but avoided layoffs.                                                                                                                                                                                                                                                                                                                   , “I have a list of things, little levers that we can pull to make those adjustments to make the business more resilient,” she said.                                                                                                                                                                                                                                                                                                                                                                                                           , While Ms. Raz is no longer concerned about the survival of her business, she remains cautious. She would like to open a third location, in Seattle, and to start offering classes and holding events. She wants to hire a general manager to run day-to-day operations.                                                                                                                                                                                                                                                                      , Those plans are on hold while Ms. Raz grapples with continuing disruptions. Supply chain problems have made it hard to get key products, like the terra cotta pots that she said were stuck somewhere in a shipping container. She has stocked up on inventory wherever possible, tying up capital for months longer than normal. And after two years of what she calls “emotional whiplash,” she is on constant guard for another setback.                                                                                                  , “I have stopped pinning my hopes on this being over, ever,” she said. “I’m just preparing for the worst all the time and not hoping for the best.”                                                                                                                                                                                                                                                                                                                                                                                           , Some economists remain optimistic that the economy will normalize as the pandemic recedes, even if the process takes longer than initially expected.                                                                                                                                                                                                                                                                                                                                                                                         , Mr. Goolsbee, who was chief economic adviser under President Barack Obama, was among those who argued early in the pandemic that the best way to revive the economy was to get the pandemic itself under control. Until that happened, he said, the recovery would be steered by the ebb and flow of case counts and hospital capacity, variants and countermeasures.                                                                                                                                                                        , He recently pointed to the relatively mild economic impact of the Omicron wave as evidence that consumers were becoming more comfortable.                                                                                                                                                                                                                                                                                                                                                                                                    , “The reason the virus was the boss is that people were afraid; they changed their behavior,” he said. “If this is a sign that the fear is easing, the virus will no longer be the boss, and the economic pandemic will be ending.”                                                                                                                                                                                                                                                                                                           , But others warn that the pandemic’s effects could outlive the pandemic itself, potentially resulting in a smaller work force and faster inflation.                                                                                                                                                                                                                                                                                                                                                                                           , “It is appropriate to start asking, are some of these shifts going to stick to at least some degree?” said Michael R. Strain, an economist at the American Enterprise Institute. “Things that happen over a two-year period, the chances of them sticking are larger than things that happen over a one-year period.”                                                                                                                                                                                                                        , Fear of the virus can still affect consumer demand. Spending at restaurants fell in December and January, as the most recent spike in coronavirus cases kept diners at home. Air travel, hotel bookings and other in-person services also suffered. And although employers added jobs in January, the total number of hours worked fell — partly because workers were home sick, and most likely also because of cutbacks in scheduling as demand declined.                                                                                  , But demand for services didn’t fall as far during the latest coronavirus wave as it did earlier in the pandemic, and preliminary data suggests that it has recovered more quickly. More comprehensive data through December shows that the crisis-induced shift in consumer spending away from goods and toward services is reversing, albeit slowly.                                                                                                                                                                                        , Supply disruptions have been harder to resolve. Shortages of computer chips, lumber and even garage doors have held up production of items from cars to houses, while a lack of shipping containers has led to delays in almost anything transported from overseas. Some bottlenecks have let up in recent months, but logistics experts expect it to take months if not years for supply chains to run smoothly again.                                                                                                                      , Then there is the labor shortage. The pandemic pushed millions of people out of the work force, and while many have returned, others — a disproportionate share of them women — have not.                                                                                                                                                                                                                                                                                                                                                    , Diahann Thomas was at work at a Brooklyn call center in January when she got a call from her son’s school: Her 11-year-old had been exposed to a classmate who had tested positive for Covid-19, and she needed to pick him up.                                                                                                                                                                                                                                                                                                              , Queen Elizabeth tests positive. The 95-year-old British monarch has been infected with the coronavirus and is “experiencing mild coldlike symptoms,” Buckingham Palace said. The announcement comes as Prime Minister Boris Johnson is poised to lift England’s remaining Covid restrictions.                                                                                                                                                                                                                                                , C.D.C. data. The Centers for Disease Control and Prevention has published only a tiny fraction of the Covid data it has collected, including critical data on boosters and hospitalizations, citing incomplete reports or fears of misinterpretation. Critics say the practice causes confusion.                                                                                                                                                                                                                                             , The virus in the U.S. Cases continue to drop nationwide, including in New York, where the latest data offered some optimism after a challenging year. Gov. Gavin Newsom of California and other U.S. governors are shifting to policies that accept living with uncertainty over possible new variants.                                                                                                                                                                                                                                      , “There are all these moving parts now with Covid — one moment, they’re at school, the next moment they’re at home,” she said.                                                                                                                                                                                                                                                                                                                                                                                                                , Ms. Thomas, 50, said her employer declined to provide flexibility while her son was in quarantine. So she quit — a decision she said was made easier by the knowledge that employers are eager to hire.                                                                                                                                                                                                                                                                                                                                      , “It did boost my confidence to know that at the end of this, it’s not going to be difficult for me to pick up the pieces, and I have more bargaining power now,” she said. “There is this whole entire shift in terms of employee-employer relationship.”                                                                                                                                                                                                                                                                                    , Ms. Thomas expects to return to work once school schedules become more reliable. But the pandemic has shown her the value of being at home with her three children, she said, and she wants a job where she can work from home.                                                                                                                                                                                                                                                                                                              , Whether and how people like Ms. Thomas return to work will be crucial to the economy’s path in coming months. If workers flood back to the job market as school and child care becomes more dependable and health risks recede, it will be easier for manufacturers and shipping companies to ramp up production and deliveries, giving supply a chance to catch up to demand. That in turn could allow inflation to cool without losing the economy’s progress over the past year.                                                          , “If you got the public health situation improved, you would see economic improvements in terms of increased work, increased output, increased functioning of the economy,” said Aaron Sojourner, a University of Minnesota economist who has studied the pandemic economy. “I do think that’s a real constraint.”                                                                                                                                                                                                                            , But people who retired early or left jobs to care for children may not go back to work right away, or may choose to work part time. And other changes may be similarly slow to reverse: Companies that were burned by shortages may maintain larger inventories or rely on shorter supply chains, driving up costs. Workers who enjoyed flexibility from employers during the pandemic may demand it in the future. Rates of entrepreneurship, automation and, of course, remote work all increased during the pandemic, perhaps permanently., Some of those changes could lead to higher inflation or slower growth. Others could make the economy more dynamic and productive. All make it harder for forecasters and policymakers to get a clear picture of the postpandemic economy.                                                                                                                                                                                                                                                                                                    , “In almost every respect, economic ripple effects that we might have expected to be temporary or short-lived are proving to be more long-lasting,” said Luke Pardue, an economist for Gusto, a payroll platform for small businesses. “The new normal is looking a lot different.”                                                                                                                                                                                                                                                           , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/19/us-listed-chinese-companies-need-beijings-approval-for-secondary-listings.html </td>
   <td style="text-align:left;"> 2022-02-19 15:39:28 </td>
   <td style="text-align:left;"> Some U.S.-listed Chinese stocks will need Beijing's approval to stay public in other overseas markets </td>
   <td style="text-align:left;"> , BEIJING — If U.S. regulation forces Chinese companies to delist from New York, new rules from Beijing further complicates their path to raising money in public markets abroad.                                                                                                                                                                                                                                  , Since Tuesday, new rules from the Cyberspace Administration of China require Chinese internet platform companies with personal data of more than 1 million users to get approval before listing overseas.                                                                                                                                                                                                        , While the rules do not apply to companies that have already gone public, those pursuing dual or secondary listings overseas must follow the CAC's new approval process, according to a CNBC translation of a Chinese article published Thursday on the regulator's website.                                                                                                                                      , It's yet another consideration for international investors looking at Chinese companies.                                                                                                                                                                                                                                                                                                                         , "The timetable for companies' overseas listings has become longer, and uncertainty has increased for listing," said Ming Liao, founding partner of Beijing-based Prospect Avenue Capital, according to a CNBC translation of the Chinese remarks.                                                                                                                                                                , As regulators and businesses figure out how the new measures will be implemented, institutional investors hope to better understand the government's thinking by seeing some approvals for overseas listings, he said.                                                                                                                                                                                           , Fallout from Chinese ride-hailing app Didi's U.S. IPO in late June prompted Beijing to increase regulatory scrutiny on what was a rush of Chinese companies looking to raise money in New York.                                                                                                                                                                                                                  , Chinese IPOs in the U.S. have essentially dried up in the months since, while existing U.S.-listed Chinese stocks face the threat of delisting in coming years from Washington's more stringent audit requirements.                                                                                                                                                                                              , Several of these Chinese companies, including Alibaba, have turned to Hong Kong for dual or secondary listings in the last few years. That way investors could swap their U.S. shares for ones in Hong Kong in the event of a delisting.                                                                                                                                                                         , Only about 80 of 250 U.S.-listed Chinese companies would be eligible for a secondary or dual primary listing in Hong Kong, according to China Renaissance analysis from Bruce Pang and his team in January. That's due to stringent requirements in Hong Kong for minimum market capitalization and other factors.                                                                                               , The remaining U.S.-listed Chinese companies would likely only have the choice of privatizing, and then attempting a listing in the mainland A share market, the report said. "In practice," the analysts said, "we think Hong Kong will not be exempted from the cybersecurity process – the door is still open, in our opinion, for Beijing to impose a cybersecurity review on proposed listings in Hong Kong.", The mainland market is less accessible to foreign investors and is dominated by more sentiment-driven retail investors.                                                                                                                                                                                                                                                                                          , Analysts also point out the Hong Kong stock market doesn't compare with New York when it comes to trading volume and the price tech companies can get for their shares.                                                                                                                                                                                                                                          , It remains to be seen to what extent cybersecurity scrutiny will apply to future Chinese stock offerings in Hong Kong.                                                                                                                                                                                                                                                                                           , Goldman says Chinese stocks are too big to ignore — and names some top picks with serious upside                                                                                                                                                                                                                                                                                                                 , These are the top stock picks in Asia to play rising interest rates, according to Bank of America                                                                                                                                                                                                                                                                                                                , HSBC picks Chinese stocks to play a rising U.S. 10-year Treasury yield                                                                                                                                                                                                                                                                                                                                           , U.S.-listed, China-based companies that pursue secondary or dual listings in Hong Kong only need the CAC's review if the regulator identifies a national security risk related to the companies' products or data processing, said Marcia Ellis, global chair of the private equity group at Morrison &amp; Forrester, Hong Kong.                                                                                    , That's "a different threshold" from the CAC review required for listings outside of China in markets such as London or Singapore, Ellis said. In these cases, companies with personal data on more than 1                                                                                                                                                                                                        , million users would need CAC approval before going public.                                                                                                                                                                                                                                                                                                                                                       , "Effectively CAC's latest statements just clarified a couple of matters and plugged up some potential loopholes," she said.                                                                                                                                                                                                                                                                                      , The latest CAC regulation does not mention Hong Kong.                                                                                                                                                                                                                                                                                                                                                            , However, in Thursday's article, the regulator said its new overseas listings regulation "does not mean operators in the process of listing in Hong Kong can ignore the relevant network security, data security and national security risks."                                                                                                                                                                    , Days after Didi's listing, the CAC ordered the company to suspend new user registrations and remove its app from app stores, while the regulator began a cybersecurity review over data privacy concerns.                                                                                                                                                                                                        , In December, Didi announced it planned to delist from New York and relist in Hong Kong. The company has yet to confirm when that transition would occur, and it's unclear whether the cybersecurity review has ended.                                                                                                                                                                                            , Shares are down more than 14% so far this year, after a drop of 64% in the roughly six months of 2021 trading.                                                                                                                                                                                                                                                                                                   , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cobalt </td>
   <td style="text-align:left;"> 2022-02-19 11:00:11 </td>
   <td style="text-align:left;"> Cobalt Hits 3-1/2-year High </td>
   <td style="text-align:left;"> Cobalt increased to a 3-1/2-year high of 72780 USD/T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/nickel </td>
   <td style="text-align:left;"> 2022-02-19 11:00:00 </td>
   <td style="text-align:left;"> Nickel Hits 10-1/2-year High </td>
   <td style="text-align:left;"> Nickel futures climbed above $24,600 per tonne, the highest since June of 2011, as investors are increasingly worried about supply disruptions. The situation on the Ukrainian border with Russia is deteriorating rapidly, highlighting fears that Russia will invade Ukraine and the Western countries will be forced to impose sanctions against Moscow which is the major producer of nickel. Meanwhile, nickel inventories in LME-registered warehouses have dropped 69% since April to 83,328 tonnes as the demand from the stainless steel and battery sectors remains strong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/nwg:ln </td>
   <td style="text-align:left;"> 2022-02-19 08:46:37 </td>
   <td style="text-align:left;"> Natwest Group PLC earnings above expectations at 0.04 USD </td>
   <td style="text-align:left;"> Natwest Group PLC (NWG) released earnings per share at 0.04 USD, compared to market expectations of 0.03 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/jamaica/interest-rate </td>
   <td style="text-align:left;"> 2022-02-19 07:28:00 </td>
   <td style="text-align:left;"> Jamaica Hikes Interest Rates by 150Bps </td>
   <td style="text-align:left;"> The central bank of Jamaica raised its benchmark interest rate by 150bps to 4% on February 18th of 2022, as well as stronger measures to contain liquidity expansion and ensure foreign exchange stability. Interest rates weren’t this high since June of 2017, as policymakers said that inflation continued to accelerate and stood well above target, while the prospects of faster tightening plans by major foreign central banks could precipitate capital outflows and pressure the Jamaican dollar. The bank also noted that underlying demand pressures may also begin to threaten the stability of foreign exchange rates and, with it, risking efforts to bring down inflation. Looking forward, the committee agreed to maintain or tighten monetary policy further in future meetings to ensure the medium-term inflation target, namely the annual inflation rate target range of 4 to 6%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-02-19 07:15:05 </td>
   <td style="text-align:left;"> Dollar Firms on Escalating Tensions in Ukraine </td>
   <td style="text-align:left;"> The dollar index firmed to 96.1 on Friday, ending the week unchanged, as traders monitored a series of headlines about the Russia-Ukraine standoff and prospects of a more aggressive monetary policy tightening by the Fed. US secretary of state Antony Blinken agreed to meet with Russian foreign minister Sergei Lavrov next week, while on the other hand, Russian media said a car exploded near a government building in separatist-controlled Donetsk, and civilians were ordered to evacuate the breakaway region, heightening fears that Russia is planning to invade Ukraine. Meanwhile, St. Louis Fed President James Bullard repeated his call for Fed's strong action and Fed Bank of Cleveland President Loretta Mester said she supports hiking rates faster if needed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-02-19 06:46:00 </td>
   <td style="text-align:left;"> Gasoline Futures End Week 2.2% Lower </td>
   <td style="text-align:left;"> US gasoline futures ended the week trading at $2.68 a gallon, slightly down from an over seven-year high of $2.79 reached earlier in the week, as worries over Iranian oil returning to markets offset upside risks from geopolitical tensions in Eastern Europe. Iran was reportedly close to a deal on its nuclear programme, which could mean the release of about 1.3 million barrels a day of crude supply and ease a tight global market. Meanwhile, Russian backed separatists started evacuating civilians from Donetsk amid heavy shelling with government forces, raising fears of an imminent war in the region, which could disrupt supplies from major oil producer Russia. On a weekly basis, gasoline ended 2.2% lower, snapping eight consecutive weeks of gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-02-19 06:39:00 </td>
   <td style="text-align:left;"> Natural Gas Futures Drop ahead of Weekend </td>
   <td style="text-align:left;"> US natural gas futures swung between gains and losses to close 1% lower at $4.4 per million British thermal units on Friday, with the volatility being mainly driven by slight changes in weather forecasts for early March. The two-week weather outlook points to colder-than-usual temperatures but reports painted a mixed picture for the first days of March, with some forecasts seeing slightly milder weather. Also, investors continued to reassess the latest EIA inventory data, which came 3 billion cubic feet short (bcf) of market expectations at 190 bcf. The shortfall between current storage levels and the five-year average widened to 11.6%. On a weekly basis, the contract jumped 12.7%, rebounding from a 13.8% fall last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 06:02:00 </td>
   <td style="text-align:left;"> Toronto Stocks End Week on Bitter Note </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, closed 0.8% lower at a three-week low of 21,008 on Friday, the third straight decline, amid a broad risk aversion due to escalating tensions in Ukraine. All sectors ended lower save for consumer cyclicals, with healthcare and energy leading losses. Reports that citizens in the self-proclaimed Donetsk People’s Republic were evacuating the region raised alarms about an imminent Russian invasion. Meanwhile, preliminary data for January pointed to a 2.4% rebound in retail trade, from a 1.8% decline in December. Also, Ottawa’s police arrested 21 protesters, including three organizers of the “Freedom Convoy” movement in the city center and began towing trucks out of the streets to put an end to a three-week blockade in front of the Prime Ministers’ office and the Parliament. On the earnings front, Air Canada reported a smaller quarterly loss on recovering holiday travel. On a weekly basis, the index shed 2.4%, snapping three consecutive weeks of gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/walmart-shoppers-inflation-rollbacks </td>
   <td style="text-align:left;"> 2022-02-19 05:53:38 </td>
   <td style="text-align:left;"> Walmart shoppers sidestep inflation </td>
   <td style="text-align:left;"> Former Chase Chief Economist Anthony Chan weighs in on the inflation crisis in America.                                                                                                                                                                                                                                              , For Walmart, the nation’s largest retailer, inflation has become a driver of business.                                                                                                                                                                                                                                               , With consumer inflation at a 40-year-high, most shoppers — rich or poor — will seek out the best prices, CEO Doug McMillon explained.                                                                                                                                                                                                , INFLATION IS CUTTING THE PAY OF MANY AMERICANS                                                                                                                                                                                                                                                                                       , "During periods of inflation like this, middle-income families, lower middle-income families, even wealthier families become more price sensitive. And that's to our advantage," McMillon said during the company’s earnings call Thursday.                                                                                          , "So we've been through this before. And we run with inflation around the world all the time. Inflation is a different environment in the U.S. right now than it has been in recent times for sure, but we’ve been dealing with inflation in South America and Mexico and other places."                                              , In January, consumer prices surged 7.5%, the highest since 1982, and producer prices rose by 9.6%, the highest on record.                                                                                                                                                                                                            , Walmart is managing to navigate soaring prices, which helped the retailer report solid earnings. Total revenue for the year was $572.8 billion, an increase of 2.4%. U.S. comp store sales rose 6.4% over the same period.                                                                                                           , Transactions rose 3.1% in the quarter, while the average ticket rose 2.4%. The company does not disclose average spending per customer.                                                                                                                                                                                              , Walmart (Source: Walmart)                                                                                                                                                                                                                                                                                                            , Not only is Walmart navigating inflation internally, John Furner, president and CEO of Walmart U.S., said his team has been able to "roll back" prices.                                                                                                                                                                              , "We're also seeing the opportunity to increase some of our rollbacks in stores. And we're really proud of the team. We're seeing about the same number of rollbacks now that we had at the end of Q1 last year," Furner said, noting prices for consumer electronics and dry groceries were areas in select stores seeing rollbacks. , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                          , Walmart and Sam's Club operate 5,342 stores in the U.S.                                                                                                                                                                                                                                                                              , Shares of Walmart are down 4.6% year-to-date as of Friday, less than the S&amp;P 500's 8.8% decline.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 05:38:00 </td>
   <td style="text-align:left;"> Brazil Stocks End Week Flat </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, erased early gains to close 0.6% lower at a 112,861 during a volatile session on Friday, as investors were spooked by reports of spiking tensions in eastern Ukraine. Early in the session, the benchmark index was trading above the 114,000 level, with hopes of a diplomatic solution to tensions in Ukraine, but the movement lost strength when authorities in the separatist-controlled city of Donetsk began evacuating civilians. The top loser of the session was logistics firm Rumo Logística (-8.8%), which saw Q4 net results switch to a BRL 384M loss from a BRL 3M profit a year earlier. In contrast, Cielo jumped 12% after the announcement that the company will sell a stake in Merchant e-Solutions for 1.5 billion reais. Quarterly net profits for utility Neoenergia fell 36% but jumped 15.9% for wind energy firm Aeris. On a weekly basis, the index ended flat, pausing five straight weeks of gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-ends-230-points-lower/story.aspx?guid={F22B8492-51D3-45EC-B00D-709618C296EF}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-19 05:01:35 </td>
   <td style="text-align:left;"> Dow ends 230 points lower Friday, stocks book second week in a row of declines - MarketWatch </td>
   <td style="text-align:left;"> U.S. stocks closed lower Friday and booked a second week in a row of declines, as investors kept an eye on Russia and Ukraine, fearing an outbreak of war. President Biden is due to speak shortly after the closing bell on Russia tensions, with a focus on "continued efforts to pursue deterrence and diplomacy, and Russia's buildup of military troops on the border of Ukraine," the White House said Friday. The Dow Jones Industrial Average 
        DJIA,
        -0.68%
       fell about 232 points Friday, or 0.7%, ending near 34,079, for a 1.9% weekly loss. The S&amp;P 500 index 
        SPX,
        -0.72%
       closed down about 31 points Friday, or 0.7%, near 4,348, narrowly avoiding a close in correction territory. It lost 1.6% for the week. The Nasdaq Composite Index 
        COMP,
        -1.23%
       shed 168 points, or 1.2% Friday, while shedding 1.8% for the week. , U.S. financial markets will be closed on Monday in observance of Presidents Day.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Joy Wiltermuth is a news editor and senior markets reporter based in San Francisco. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 04:32:00 </td>
   <td style="text-align:left;"> US Stocks Fall for 2nd Straight Week </td>
   <td style="text-align:left;"> US stocks closed lower for the third straight session on Friday, notching a second consecutive losing week as escalating tensions between Russia and Ukraine and concerns about the Fed's next steps dominated the session. Russian media said a car exploded near a government building in separatist-controlled Donetsk, and civilians were ordered to evacuate, heightening fears that Russia is planning to invade Ukraine. Meanwhile, St. Louis Fed Bullard warned that inflation could get out of control without rate hikes and Fed Bank of Cleveland President Loretta Mester said she supports hiking rates faster if needed. On corporate updates, BoA analysts reiterated their “underperform” rating on Intel’s stock, while Roku shares plunged 22% after quarterly revenues missed expectations and issued weak guidance. The Dow lost 234 points, S&amp;P 500 was down 0.7%, and Nasdaq ended 1.2% lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/e:us </td>
   <td style="text-align:left;"> 2022-02-19 04:17:17 </td>
   <td style="text-align:left;"> ENI earnings above expectations at 1.33 USD </td>
   <td style="text-align:left;"> ENI (E) released earnings per share at 1.33 USD, compared to market expectations of 1.30 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/white-house-says-russia-blame/story.aspx?guid={D9856C48-BAD2-45A3-B776-C0A6E0C930DE}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-19 03:56:07 </td>
   <td style="text-align:left;"> White House says Russia to blame for cyberattacks on Ukraine - MarketWatch </td>
   <td style="text-align:left;"> A Biden administration official on Friday put the blame on Russia for a cyberattack that hit Ukrainian banks earlier this week. "We believe that the Russian government is responsible for widescale cyberattacks on Ukrainian banks this week," Deputy National Security Advisor for Cyber and Emerging Technology Anne Neuberger told reporters., This raises questions about how personal politics influence medical decision making.                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                   , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-post-losses/story.aspx?guid={27AB5D94-5BD2-48D4-9F07-AFAB28DA424C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-19 03:53:32 </td>
   <td style="text-align:left;"> U.S. oil futures post losses for the session and week - MarketWatch </td>
   <td style="text-align:left;"> Oil futures declined on Friday, widening their weekly loss to more than 2%. A potential of Iranian crude to the market has led to some "nervousness ahead of the march towards $100 a barrel," leading oil prices to their first negative week since mid-December, said Michael Hewson, chief market analyst at CMC Markets UK. West Texas Intermediate crude for March delivery 
        CLH22,
        +1.86%
       fell 69 cents, or nearly 0.8%, to settle at $91.07 a barrel on the New York Mercantile Exchange. For the week, the front-month contract lost 2.2%, FactSet data show., Calstrs more than tripled holdings in Chinese EV firms NIO, XPeng, and Li Auto, and initiated a position in Rivian in the fourth quarter.                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-02-19 03:26:00 </td>
   <td style="text-align:left;"> Gold Heads for 3rd Weekly Advance </td>
   <td style="text-align:left;"> Gold prices remained near $1,900 on Friday, consolidating the third weekly advance in a row, as investors were monitoring the situation on the Russian Ukrainian border. In the morning the markets calmed down a bit after the US said it agreed to meet Russia next week for talks while in the afternoon news came that Moscow-backed separatists in Donbas have ordered the evacuation of civilians to Russia heightening fears that Russia is planning to invade Ukraine. At the same time, investors remained concerned about the next Fed steps after St. Louis Fed President Bullard repeated his call for Fed's strong action and Cleveland Fed President Mester said she supports hiking rates faster if needed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-19 03:24:00 </td>
   <td style="text-align:left;"> WTI Crude Futures See 1.7% Weekly Drop </td>
   <td style="text-align:left;"> WTI crude futures pared losses at 0.3%, trading around $91.5 a barrel on Friday, as escalating violence in Donetsk heightened concerns over supply disruptions from a possible Russia-Ukraine war, offsetting prospects of Iranian oil returning to global markets. The Donetsk People’s Republic started evacuating civilians from the region amid heavy shelling, while Russian media said a car exploded near a government building in Donetsk. Earlier, signs of advances in US-Iran nuclear talks pressured crude futures, as a potential deal could release about 1.3 million supply barrels. Oil is expected to hold in the $90 to $100 a barrel range despite the potential return of Iranian oil exports, as geopolitical uncertainties and a tight global market, driven by capacity constraints and demand recovery continue to keep energy prices elevated. For the week, WTI crude futures posted a 1.7% drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-02-19 03:21:00 </td>
   <td style="text-align:left;"> Brent Crude Rebounds, Ends Week on High Note </td>
   <td style="text-align:left;"> Brent crude futures rebounded from earlier losses to climb 0.7% to $93.6 a barrel on Friday, as escalating violence in Donetsk heightened concerns over supply disruptions from a possible Russia-Ukraine war, offsetting prospects of Iranian oil returning to global markets. The Donetsk People’s Republic started evacuating civilians from the region amid heavy shelling, while Russian media said a car exploded near a government building in Donetsk. Earlier, signs of advances in US-Iran nuclear talks pressured crude futures, as a potential deal could release about 1.3 million supply barrels. Oil is expected to hold in the $90 to $100 a barrel range despite the potential return of Iranian oil exports, as geopolitical uncertainties and a tight global market, driven by capacity constraints and demand recovery continue to keep energy prices elevated. For the week, Brent crude futures saw a 0.9% fall. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/warren-buffett-activision-stock </td>
   <td style="text-align:left;"> 2022-02-19 03:16:34 </td>
   <td style="text-align:left;"> Warren Buffett clears up Activision stock purchase speculation </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Berkshire Hathaway chairman Warren Buffett, is clearing up speculation related to the company's purchase of Activision Blizzard stock.                                                                                                                                                                                                                                                                                                                                                                                                                     , Buffett, in an unusual public move, clarified in a letter posted to Berkshire Hathaway's website that the company had "no prior knowledge" of the Activision-Microsoft deal.                                                                                                                                                                                                                                                                                                                                                                               , He confirmed that 85% of the position in Activision was acquired in October by one of two investment managers who operate independently of him, with the rest being purchased in November. The average cost of the purchase was $77 per share.                                                                                                                                                                                                                                                                                                             , WARREN BUFFETT'S BERKSHIRE HATHAWAY BUYS ACTIVISION STOCK                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , According to a 13F filing, Berkshire Hathaway bought approximately 14.66 million Activision Blizzard shares valued at around $975 million as of the end of 2021. Sources told the Wall Street Journal that the bulk of the Activision shares were purchased in October.                                                                                                                                                                                                                                                                                    , The move came prior to Microsoft's announcement in January that it planned to acquire the embattled video game publisher in a deal worth $68.7 billion.                                                                                                                                                                                                                                                                                                                                                                                                    , Warren Buffett (left) and Bill Gates (right) (Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Microsoft was co-founded by Buffett's long-time friend Bill Gates, who stepped down from the boards of the tech giant and Berkshire in 2020.                                                                                                                                                                                                                                                                                                                                                                                                               , MICROSOFT TO REOPEN WASHINGTON OFFICES AT END OF FEBRUARY                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , "When Microsoft files its proxy material on its proposed purchase of Activision, I would be surprised if they had even discussed a proposal with Activision early in October, although I do not know," Buffett added. "In any event, the investment manager's purchase could have been replicated after the Microsoft proposal was announced at a price of $78 per share or so. His purchase was no bonanza of any sort for him or Berkshire."                                                                                                             , The Journal initially reported that Berkshire paid an average of $66.53 per share for its Activision stake, but later corrected it after being contacted by the company.                                                                                                                                                                                                                                                                                                                                                                                   , BUFFETT'S BERKSHIRE HATHAWAY WILL HOS ANNUAL MEETING IN PERSON                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Activision Blizzard shares fell as low as $56.40 apiece last year following allegations from California's Department of Fair Employment and Housing (CDFEH) that the company paid its female employees less than their male counterparts, provided them with fewer opportunities to advance, fostered a "frat boy workplace culture" and ignored complaints of blatant harassment, discrimination and retaliation.                                                                                                                                         , This June 13, 2013 file photo shows the Activision Blizzard Booth during the Electronic Entertainment Expo in Los Angeles. (AP Photo/Jae C. Hong / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                                                            , In the months that have followed, Activision Blizzard employees have called for the firing of chief executive officer Bobby Kotick for failing to disclose his full knowledge of employee sexual harassment and discrimination complaints to the company's board of directors. They have also accused the company of worker intimidation and engaging in union-busting tactics.                                                                                                                                                                            , Robert "Bobby" Kotick, chief executive officer of Activision Blizzard Inc., smiles during the annual Milken Institute Global Conference in Beverly Hills, California, U.S., on Monday, May 2, 2016.  ( Patrick T. Fallon/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                        , In order to address employee concerns, Activision announced it would increase its hiring of women or non-binary employees, invest millions of dollars in accelerating and expanding opportunities for diverse talent and underrepresented communities, waive required arbitration of sexual harassment and discrimination claims and increase transparency related to pay equity. It also formed a workplace responsibility committee to oversee the workplace culture transformation and work in tandem with the Equal Employment Opportunity Commission. , Over 20 employees have exited the company, including former Blizzard President J. Allen Brack, and another 20 employees have faced other types of disciplinary action since CDFEH's lawsuit in July.                                                                                                                                                                                                                                                                                                                                                       , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The Microsoft-Activision deal is expected to close in fiscal year 2023, pending regulatory approval and completion of other customary closing conditions. Once the deal closes, the Activision Blizzard business will report to Microsoft Gaming CEO Phil Spencer.                                                                                                                                                                                                                                                                                         , Representatives for Microsoft and Activision did not immediately return FOX Business' request for comment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 02:44:00 </td>
   <td style="text-align:left;"> US Stocks Deepen Losses on Russia-Ukraine Tensions </td>
   <td style="text-align:left;"> US stocks were on a rout on Friday, extending last session's meltdown as investors continued to monitor escalating tensions between Russia and Ukraine and remained concerned about Fed's next steps. Russian media said a car exploded near a government building in Donetsk which is controlled by Moscow back separatists, and civilians were ordered to evacuate heightening fears that Russia is planning to invade Ukraine. Meanwhile, St. Louis Fed Bullard warned that inflation could get out of control without rate hikes and Fed Bank of Cleveland President Loretta Mester said she supports hiking rates faster if needed. On corporate updates, BoA analysts reiterated their “underperform” rating on Intel’s stock, while Roku shares plunged 24% after quarterly revenues missed expectations and issued weak guidance. On a weekly basis, all three indexes are set for a 2% drop, the second in a row. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-settle-below-1900/story.aspx?guid={F3ACE953-8EB5-455D-8C21-9CC3648A1813}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-19 02:39:55 </td>
   <td style="text-align:left;"> Gold futures settle below $1,900, but gain for the week - MarketWatch </td>
   <td style="text-align:left;"> Gold futures fell on Friday to settle below the $1,900 mark, but still gained just over 3% for the week. While "war fears dominate the headlines, I believe the main driving force behind this rally remains rising inflation," said Peter Spina, president and chief executive officer at GoldSeek.com, adding that there may be a $20 "war premium" already built into gold prices. Gold may "swing and pullback" from the $1,900 mark, but "as we have seen for the last weeks, pullbacks get bought and the price reverses higher," said Spina. "The trend is up, and the gold price can quickly continue climbing here to its next technical price target of $1,920." April gold 
        GCJ22,
        +0.52%
       fell $2.20, or 0.1%, to settle at $1,899.80 an ounce after touching a high at $1,905 - the highest intraday level for a most-active contract since June of last year, FactSet data show. For the week, prices were up 3.1%, FactSet data show., Intel Corp. disappointed analysts with its short- and medium-term goals in an investor day Thursday, and analysts collectively shook their head at an "absurdly bullish" long-term forecast for which "shares are pricing in little [to] no chance of success."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/baker-hughes-data-show-us/story.aspx?guid={FF8E9E8B-B9FB-43E1-AE5F-6DA2AD9019DF}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-19 02:10:55 </td>
   <td style="text-align:left;"> Baker Hughes data show U.S. oil-drilling rig count up a 4th straight week - MarketWatch </td>
   <td style="text-align:left;"> Baker Hughes 
        BKR,
        -1.09%
       on Friday reported that the number of active U.S. rigs drilling for oil was up by four to 520 this week. That followed a climb of 19 oil rigs the week before, Baker Hughes data show. The total active U.S. rig count, which includes those drilling for natural gas, climbed by 10 to 645, according to Baker Hughes. Oil prices continued to trade lower in Friday dealings as traders weighed progress toward an Iran nuclear agreement and the potential for a Russian invasion of Ukraine. March West Texas Intermediate crude 
        CLH22,
        +1.86%
       was down 43 cents, or 0.5%, at $91.33 a barrel on the New York Mercantile Exchange., The U.S. Coast Guard had been searching in the area where a woman jumped from her balcony into the sea, but called off its search after canvassing 2,514 square nautical miles.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-19 01:42:00 </td>
   <td style="text-align:left;"> US 10Y Treasury Note Yield Dips </td>
   <td style="text-align:left;"> The yield on the benchmark 10-year Treasury note fell to 1.92% on Friday, as fears of imminent war returned after reports that citizens in the self-proclaimed Donetsk People’s Republic were evacuating the region. Also, Russian media said a car exploded near a government building in Donetsk. Meanwhile, investors continued to digest the prospects of tightening Federal Reserve monetary policy. St. Louis Fed President James Bullard repeated his call for Fed's strong action and Fed Bank of Cleveland President Loretta Mester said she supports hiking rates faster if needed. On a weekly basis, the 10-year Treasury note is set to end flat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 01:38:00 </td>
   <td style="text-align:left;"> Madrid Stocks Close Lower </td>
   <td style="text-align:left;"> The Ibex 35 closed 0.9% lower at 8,590 on Friday, extending last session’s 0.9% loss as investors weighed on corporate news and renewed concerns of a Russian invasion. Claims of repeated ceasefire violations in eastern Ukraine led to reports of evacuation, while US and NATO authorities labeled the events as Moscow looking for a pretext for war. Ferrovial fell 2.8% after the group agreed to invest over EUR 1 billion into the Carlyle Group entity funding the redevelopment of JFK Airport’s Terminal 1. At the same time, Anea dropped 3.1% after the Spanish competition authority approved a 3.17% reduction in selected fees charged at the group’s airports. Lastly, Siemens Gamesa shares fell 4.2% after Siemens Energy CEO Christian Bruch emphasized that the market environment in the onshore wind turbine business will remain difficult in the near future. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/18/stocks-making-the-biggest-moves-midday-roku-draftkings-ford-more.html </td>
   <td style="text-align:left;"> 2022-02-19 01:37:47 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Roku, DraftKings, Shake Shack, Bloomin' Brands and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                    , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                                                                        , Roku — Roku shares were down 22.2% after the company reported revenue for the most recent quarter that fell short of analysts' forecasts. Roku also issued a weaker-than-expected outlook due to higher component prices and supply chain disruptions.                                                                                                                                                                                             , DraftKings — Sports betting company DraftKings saw shares tumble 21.6% after it reported a narrower-than-expected quarterly loss and issued guidance projecting a wider-than-expected adjusted loss for the full year.                                                                                                                                                                                                                             , Bloomin' Brands — Shares of the Outback Steakhouse parent jumped 7.5% after the company reported a quarterly earnings beat and a modest revenue beat. Bloomin' also reinstated its quarterly dividend and announced a new $125 million share buyback program.                                                                                                                                                                                      , Virgin Galactic – Shares of Virgin Galactic fell 6.7% following the announcement that Chairman Chamath Palihapitiya will be stepping down from the board of directors, effective immediately. His special purpose acquisition company took Virgin Galactic public in 2019. Palihapitiya said he's leaving "to focus on other existing and upcoming public board responsibilities."                                                                 , Dollar Tree — Shares of the discount retailer jumped 5.2% and was one of the top gainers in the S&amp;P 500, after the company announced executive chairman Bob Sasser will retire and be given the title of Chairman Emeritus.                                                                                                                                                                                                                        , Redfin — The real estate brokerage's shares tumbled by 20.1% after RBC Capital Markets downgraded the stock to sector perform from outperform, calling the bull case for the stock "broken." Redfin on Thursday reported a smaller-than-expected loss for the fourth quarter and beat on revenue. Real estate services unit and gross margins missed expectations.                                                                                 , Shake Shack — The restaurant chain's shares fell 4.1% after the company issued quarterly revenue guidance below estimates, noting that labor shortage challenges stemming from the omicron variant led the company to close restaurants. Shake Shack said it expects $196 million to $201.4 million in revenue for the first quarter, compared with estimates of $210.9 million.                                                                   , Pilgrim's Pride — Shares of the poultry producer sank 13.6% after the Brazilian meatpacker JBS withdrew from plans to buy the remaining 20% of the company it doesn't already own, saying the two sides couldn't agree on terms of a deal.                                                                                                                                                                                                         , Intel — Shares of Intel were down 5.3%, leading laggards on the Dow Jones Industrial Average. Bank of America reiterated an underperform rating on the stock.                                                                                                                                                                                                                                                                                      , Ford — The automaker's shares rose 2.8% following a report that CEO Jim Farley is evaluating options to separate the company's electric vehicle unit from its legacy internal combustion engine business, and could even be weighing a spinoff of one of them.                                                                                                                                                                                     , General Electric — The electric company saw its shares slide 5.8% after it provided a profit outlook for 2022 saying supply chain challenges continue to pressure its health care, renewable energy and aviation businesses and could remain through the first half of 2022. "As a result, supply chain headwinds may continue to partially mask the significant progress we are making across our businesses," the company said in an 8-K filing. ,  — CNBC's Hannah Miao contributed reporting                                                                                                                                                                                                                                                                                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                             , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                             , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                   , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                   , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                 , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/18/fed-approves-rules-banning-its-officials-from-trading-stocks-bonds-and-also-cryptocurrencies.html </td>
   <td style="text-align:left;"> 2022-02-19 01:30:10 </td>
   <td style="text-align:left;"> Fed approves rules banning its officials from trading stocks, bonds and also cryptocurrencies </td>
   <td style="text-align:left;"> , Federal Reserve officials won't be able to trade a slew of assets including stocks and bonds — as well as cryptocurrencies — under new rules that became formal Friday.                                                                                                                                                                                                                                                                                 , Following up on regulations announced in October, the policymaking Federal Open Market Committee announced that most of the restrictions will take effect May 1.                                                                                                                                                                                                                                                                                        , The rules will cover FOMC members, regional bank presidents and a raft of other officials including staff officers, bond desk managers and Fed employees who regularly attend board meetings. They also extend to spouses and minor children.                                                                                                                                                                                                           , "The Federal Reserve expects that additional staff will become subject to all or parts of these rules after the completion of further review and analysis," a release announcing the rules stated.                                                                                                                                                                                                                                                      , The rules "aim to support public confidence in the impartiality and integrity of the Committee's work by guarding against even the appearance of any conflict of interest," the statement also said.                                                                                                                                                                                                                                                    , Central bank officials acted after disclosures last year that several senior Fed officials had been trading individual stocks and stock funds just before the time the central bank adopted sweeping measures aimed at boosting the economy in the early days of the Covid spread.                                                                                                                                                                      , Bank of America’s chief investment strategist sees recession risk rising, is bearish on stocks                                                                                                                                                                                                                                                                                                                                                          , Why the variable dividend trend is growing, and how investors should play it                                                                                                                                                                                                                                                                                                                                                                            , Raymond James says buy the dip in Fastly, stock can rebound more than 80%                                                                                                                                                                                                                                                                                                                                                                               , Regional presidents Eric Rosengren of Boston and Robert Kaplan left their positions following the controversy.                                                                                                                                                                                                                                                                                                                                          , The announcement Friday extended the ban to cryptocurrencies like bitcoin, which were not mentioned in the original announcement in October.                                                                                                                                                                                                                                                                                                            , Under the regulations, officials still holding market positions will still have 12 months to shed prohibited positions. New Fed officials will have six months to do so.                                                                                                                                                                                                                                                                                , In the future, officials covered by the new rules must give 45 days' notice before making any permissible asset purchases, a restriction that will go into effect July 1. They then will have to hold those positions for at least a year and will be banned from any trading during "periods of heightened financial market stress." There is no set definition of the term, which will be determined by the Fed chair and the board's general counsel., Along with stocks, bonds and crypto, the ban extends to commodities, foreign currencies, sector index funds, derivatives, short positions and agency securities or using margin debt to buy assets.                                                                                                                                                                                                                                                     , Congress has been debating a measure that also will restrict its members from owning individual stocks, though it has not been adopted yet.                                                                                                                                                                                                                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/goldman-sachs-ceo-braces-above/story.aspx?guid={35FAC385-ADB4-4A4B-9C5F-68B5DE23D606}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-19 01:27:29 </td>
   <td style="text-align:left;"> Goldman Sachs CEO braces for above trend inflation - MarketWatch </td>
   <td style="text-align:left;"> This replaces an earlier item that incorrectly reported where the comments were made. It has been corrected.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Goldman Sachs Group Inc. 
        GS,
        -0.87%
       CEO David Solomon on Thursday said 2022 will mark a shift from low interest rates and tame inflation to tighter borrowing conditions and above-trend inflation. In his remarks at the Credit Suisse Financial Services Forum, Solomon updated financial targets the firm had laid out at its investor day in 2020. The bank now expects to book $350 billion in inflows in its asset management and wealth management by 2024, up from its earlier target of $250 billion. The firm is projecting 14% to 16% return on equity, up from its earlier target of greater than 13%. It's projecting $225 billion in gross alternatives fundraising by 2024 and greater than $10 billion in firmwide management fees. Shares of Goldman Sachs fell 0.4%., Uncertainty and the impending Fed rate hikes clobbered shares again this past week. Time to buy the dip? Or stay on the sidelines?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 01:03:59 </td>
   <td style="text-align:left;"> UK Stocks See Worst Week Since November </td>
   <td style="text-align:left;"> The FTSE 100 reversed course during the session to close 0.3% lower at a two-week low of 7,515 on Friday, in line with its European peers, as fears of imminent war returned after reports that citizens in the self-proclaimed Donetsk People’s Republic were evacuating the region. Also, Russian media said a car exploded near a government building in Donetsk. At the same time, storm Eunice triggered red warnings in England, with record gusts of wind in parts of the country that have ripped the roof of the O2 arena and left tens of thousands of homes without power. Losses were limited by upbeat retail sales in January and strong earnings from warehousing specialist Segro. Among the worst performers, NatWest Group shed 2.4% after the bank beat estimates but lowered its annual cost-cutting target for the next two years. On the week, the FTSE 100 lost 2%, its worst week since late November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 00:56:00 </td>
   <td style="text-align:left;"> South African Stocks End Higher </td>
   <td style="text-align:left;"> The JSE FTSE All Share index managed to close 0.3% up at 76,368 at the end of a volatile session on Friday, mainly lifted by a nearly 6% jump in shares of miner Gold Fields in the wake of strong corporate earnings. Meanwhile, concerns mounted over the possibility of war in Europe, after a separatist leader in eastern Ukraine announced the evacuation of civilians to Russia amid soaring tensions. On the domestic front, President Cyril Rampahosa has come under criticism for appointing yet another advisor and task team to do what some said should be done by his ministers. On the earnings front, South African retailer Massmart, the owner of Makro, Game and Builders, has flagged a more than 2 billion rand loss for its 2021 year, hit by the effects of July’s civil unrest as well as the timing of insurance payouts. For the week, the JSE was almost flat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 00:54:00 </td>
   <td style="text-align:left;"> France Stocks Cut Gains to Close Down </td>
   <td style="text-align:left;"> The CAC 40 reversed early gains to close 0.3% lower at 6,930 on Friday, its third consecutive session in the red amid negative corporate news and renewed concerns of a Russian invasion amid repeated ceasefire violations in eastern Ukraine. On the corporate front, Hermes dropped 4.6% from reporting slower sales growth during the fourth quarter of 2021, mostly due to capacity constraints on its leather goods and saddlery divisions. At the same time, EDF fell 2.3% after announcing a rights issue that will raise EUR 2.5 billion to improve its financial structure, as the group struggles with low availability of its nuclear plant fleets due to corrosion and safety issues. At the same time, Renault (unchanged) posted an operating margin of 3.6% for 2021, already exceeding its target set for 2023. Consequently, the group increased its margin target to 4% for 2022, despite the ongoing global shortage of semiconductors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 00:48:00 </td>
   <td style="text-align:left;"> Italian Stocks Close Lower </td>
   <td style="text-align:left;"> The FTSE MIB Index cut earlier gains to drop 0.6% and close at 26,507 on Friday, amid heightened fears of a Russian invasion due repeated ceasefire violations in eastern Ukraine ahead of next week’s meeting between the US Secretary of State and Russian Foreign Minister. On the corporate front, Buzzi Unicem (-2%) led the losses due to its large exposure to the Ukrainian economy. At the same time, tech and manufacturing stocks both traded in the red, driven by STMicroelectronics (-2.3%) and Nexi (-2.6%). On the other hand, Eni gained 1% after posting an adjusted net profit of EUR 4.74 billion in 2021 compared to the EUR 0.758 billion loss in 2020, marking its strongest year since 2012, largely due to the rise in oil and gas prices during 2021. Meanwhile, the Italian government finalized new measures to set aside EUR 6 billion to cap soaring energy costs in the country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 00:47:00 </td>
   <td style="text-align:left;"> European Stocks Reverse Gains to Close Lower </td>
   <td style="text-align:left;"> European equity markets reversed gains to close in the red on Friday, with Germany’s DAX down more than 1% amid renewed concerns over Russia-Ukraine tensions. The announcement of the evacuation of Donetsk People's Republic by Russian-backed separatist leader Denis Pushilin more than offset hopes the conflict in Ukraine could be resolved diplomatically after the US Secretary of State agreed to a meeting with Russia's foreign minister next week. On the corporate front, Allianz reported lower-than-expected earnings although its revenues topped estimates; Renault exceeded its 2021 targets, showing upbeat profits; Sika posted a jump in full-year net profit and proposed a 16% higher dividend; Norwegian Air also reported a profit for full 2021; and Hermes grew slightly below market expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-19 00:25:04 </td>
   <td style="text-align:left;"> Russian 10-Year Bond Yield Rebound </td>
   <td style="text-align:left;"> The yield of the 10-year OFZ treasury bond rebounded to 9.8% in mid-February as fears of war in Ukraine and economic consequences of sanctions continued to pressure Russian assets. Russia-backed separatists and Ukrainian forces blamed each other for violating ceasefire agreements in the Luhansk People’s Republic, an event labeled by the US and NATO as Moscow looking for a pretext for war amid the imminent threat of an invasion. Meanwhile, the Central Bank of Russia raised its interest rate to 9.5% on its February meeting while paving the way for future hikes this year. Tighter policy came after significant inflationary pressure led policymakers to upwardly revise inflation expectations to 5-6% by the end of 2022 and only returning to the bank’s target of 4% by mid 2023, erasing previous expectations that interest rates would ease in this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-speak-russia-ukraine-after/story.aspx?guid={705213D9-2C78-4135-8CD0-4B3D35C3892C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-19 00:20:13 </td>
   <td style="text-align:left;"> Biden to speak on Russia and Ukraine after call with Transatlantic leaders - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden will speak at 4 p.m. Eastern time on the U.S.'s "continued efforts to pursue deterrence and diplomacy, and Russia's buildup of military troops on the border of Ukraine," the White House said Friday. The speech is scheduled after a separate, 2:30 p.m. Eastern call with Transatlantic leaders, according to the White House. U.S. stock indexes 
        SPX,
        -0.72%
       were trading lower Friday as investors monitored developments between Russia and Ukraine, with investors harboring fears of a war breaking out.,  Russia on Sunday rescinded earlier pledges to pull tens of thousands of its troops back from Ukraine's northern border, in a move that U.S. leaders warned put Russia another step closer to launching an invasion of Ukraine. Russian President Vladimir Putin was silent on Ukraine's appeal for a cease-fire.                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 00:10:00 </td>
   <td style="text-align:left;"> Brazilian Equities Retreat </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, reversed course and was down 0.4% to around 113,120 during a volatile session on Friday, as investors were spooked by reports of spiking tensions in eastern Ukraine. Early in the session, the benchmark index was trading above the 114,000 level, with hopes of a diplomatic solution to tensions in Ukraine, but the movement lost strength. Market sentiment was tempered by an over 10% jump in Cielo shares after the announcement that the company will sell a stake in Merchant e-Solutions for 1.5 billion reais. Investors also keep an eye on corporate results from Neoenergia, Aeris, Rumo Logística and Cosan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/18/business/trumps-truth-social.html </td>
   <td style="text-align:left;"> 2022-02-19 00:03:23 </td>
   <td style="text-align:left;"> Trump’s Truth Social Is Poised to Join a Crowded Field - The New York Times </td>
   <td style="text-align:left;"> , Truth Social, the former president’s hard-right alternative to Twitter, could open its doors next month. But as businesses go, outrage may not be the best moneymaker.                                                                                                                                                                                                                                                                                                                                 , Credit...Matt Chase                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , By Matthew Goldstein and Ryan Mac                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , For months, former President Donald J. Trump has promoted Truth Social, the soon-to-be-released flagship app of his fledging social media company, as a platform where free speech can thrive without the constraints imposed by Big Tech.                                                                                                                                                                                                                                                             , At least seven other social media companies have promised to do the same.                                                                                                                                                                                                                                                                                                                                                                                                                              , Gettr, a right-wing alternative to Twitter founded last year by a former adviser to Mr. Trump, bills itself as a haven from censorship. That’s similar to Parler — essentially another Twitter clone backed by Rebekah Mercer, a big donor to the Republican Party. MeWe and CloutHub are similar to Facebook, but with the pitch that they promote speech without restraint.                                                                                                                          , Truth Social was supposed to go live on Presidents’ Day, but the start date was recently pushed to March, though a limited test version was unveiled recently. A full rollout could be hampered by a regulatory investigation into a proposed merger of its parent company, the Trump Media &amp; Technology Group, with a publicly traded blank-check company. (Reuters reported that the company still planned to have the app available for download from the Apple Store on Monday.)                   , If and when it does open its doors, Mr. Trump’s app will be the newest — and most conspicuous — entrant in the tightly packed universe of social media companies that have cropped up in recent years, promising to build a parallel internet after Twitter, Facebook, Google and other mainstream platforms began to crack down on hate speech.                                                                                                                                                       , Millions of users have signed up for these so-called alt-tech or alternative platforms, attracted by the promise of a space untethered by what they consider censorship of conservative voices. The business case for these companies, though, has already proved to be wobbly.                                                                                                                                                                                                                        , “There is an audience and a market, but it is not huge,” said Shannon McGregor, a professor of journalism and media at the University of North Carolina who has studied social media platforms. “Most people don’t want a version of the internet where anything goes.”                                                                                                                                                                                                                                , Most alt-tech start-ups are chasing the same pool of users, many of whom might spend just a fraction of their social media time on politically partisan causes. Also, right-wing pundits who draw big audiences already have large, well-established online fan bases on mainstream social media, making them unlikely to completely switch to a new platform unless they’ve been iced out.                                                                                                            , And since most traditional Silicon Valley investors aren’t rushing to fund alt-tech, these companies’ growth depends on the small group of financial backers who invest in partisan causes.                                                                                                                                                                                                                                                                                                            , Rumble, which was founded in 2013 to compete with YouTube and is the oldest of these alternative social media companies, recently reported that its revenue nearly tripled over the past year. Still, for the first nine months of 2021, its revenue was less than $7 million. By comparison, YouTube made close to $9 billion in advertising revenue in its most recent quarter.                                                                                                                      , Alternative platforms claim to have signed up tens of millions of users. User numbers for most of these companies — or how they define users — are hard to verify as they are not often independently tracked. But they are unlikely to pose a serious competitive challenge to mainstream social media platforms, which have billions of users, experts said. For instance, there are more than 1.9 billion daily active users of Facebook and 211 million daily active users on Twitter who see ads. , Many people who claim to crave a social network that caters to their political cause often aren’t ready to abandon Twitter or Facebook, said Weiai Xu, an assistant professor of communications at the University of Massachusetts-Amherst. So the big platforms remain important vehicles for “partisan users” to get their messages out, Mr. Xu said.                                                                                                                                                , Gettr, Parler and Rumble have relied on Twitter to announce the signing of a new right-wing personality or influencer. Parler, for instance, used Twitter to post a link to an announcement that Melania Trump, the former first lady, was making its platform her “social media home.”                                                                                                                                                                                                                , Alternative social media companies mainly thrive off politics, said Mark Weinstein, the founder of MeWe, a platform with 20 million registered users that has positioned itself as an option to Facebook.                                                                                                                                                                                                                                                                                              , “The problem with Truth Social, Gettr and Parler is these are Twitter competitors and they are echo chambers for a narrow political spectrum,” said Mr. Weinstein. “Echo chambers don’t have broad appeal.”                                                                                                                                                                                                                                                                                            , Rather than pursue users for their political beliefs, MeWe is aiming at people who want to protect the privacy of their online postings, Mr. Weinstein said. MeWe’s basic offering is free, but it charges for certain subscription services. His start-up has raised $24 million from 100 investors.                                                                                                                                                                                                  , But since political causes drive the most engagement for alternative social media, most other platforms are quick to embrace such opportunities. This month, CloutHub, which has just four million registered users, said its platform could be used to raise money for the protesting truckers of Ottawa.                                                                                                                                                                                             , Mr. Trump wasn’t far behind. “Facebook and Big Tech are seeking to destroy the Freedom Convoy of Truckers,” he said in a statement. (Meta, the parent company of Facebook, said it removed several groups associated with the convoy for violating their rules.)                                                                                                                                                                                                                                       , Trump Media, Mr. Trump added, would let the truckers “communicate freely on Truth Social when we launch — coming very soon!”                                                                                                                                                                                                                                                                                                                                                                           , Of all the alt-tech sites, Mr. Trump’s venture may have the best chance of success if it launches, not just because of the former president’s star power but also because of its financial heft. In September, Trump Media agreed to merge with Digital World Acquisition, a blank-check or special purpose acquisition company that raised $300 million. The two entities have raised $1 billion from 36 investors in a private placement.                                                            , But none of that money can be tapped until regulators wrap up their inquiry into whether Digital World flouted securities regulations in planning its merger with Trump Media. In the meantime, Trump Media, currently valued at more than $10 billion based on Digital World’s stock price, is trying to hire people to build its platform.                                                                                                                                                           , It has brought on recruiters to reach out to former employees of Parler, according to documents seen by The Times. In screening questions, the recruiters sought to learn more about “social media outlets pitched as alternatives to Facebook/Twitter, like Parler and Gab,” and asked candidates if they thought Truth Social would run into challenges making money or moderating content on its platform.                                                                                          , Devin Nunes, the former California Republican congressman whom Mr. Trump picked to serve as chief executive of his company, declined requests for an interview.                                                                                                                                                                                                                                                                                                                                        , Rumble, the Toronto-based YouTube rival, has raised a relatively large amount of money from investors, including Peter Thiel, the billionaire venture capitalist and Trump supporter, and the venture fund of Mr. Thiel’s protégé J.D. Vance, who is running for a Senate seat from Ohio.                                                                                                                                                                                                              , Rumble is also planning to go public through a merger with a special-purpose acquisition company. SPACs are shell companies created solely for the purpose of merging with an operating entity. The deal, arranged by the Wall Street firm Cantor Fitzgerald, will give Rumble $400 million in cash and a $2.1 billion valuation.                                                                                                                                                                      , The site said in January that it had 39 million monthly active users, up from two million two years ago. It has struck various content deals, including one to provide video and streaming services to Truth Social. Representatives for Rumble did not respond to requests for comment.                                                                                                                                                                                                               , At least one other social media start-up is hoping to ride the former president’s popularity among conservatives to build its business. Gettr, which began on July 4 and is led by Jason Miller, the former Trump adviser, had hoped to land Mr. Trump before he decided to open his own venture. In January, Gettr advertised that it was the “place to watch” recent rallies by Mr. Trump.                                                                                                           , In a written statement, Mr. Miller said the former president was welcome “to join GETTR whenever he is ready.” The site claims to have five million users and a cash pile of tens of millions of dollars. In a recent interview, Mr. Miller denied a previous claim that Gettr had raised $75 million.                                                                                                                                                                                                 , Parler, the platform popular with Trump supporters, is still reeling from its role after the violent protests at the U.S. Capitol in January 2021 by thousands of angry fans of Mr. Trump. Downloads of Parler’s app plummeted 88 percent last year after Apple and Google removed it from their app stores and Amazon cut off web services after the riot, according to SensorTower, a digital analytics company.                                                                                     , Parler, which said in January that it had raised $20 million from investors, has since returned to the Apple Store. However, internal turmoil has continued. Last year, Parler fired John Matze, one of its founders, from his position as chief executive. Mr. Matze has said he was dismissed after a dispute with Ms. Mercer — the daughter of a wealthy hedge fund executive who is Parler’s main backer — over how to deal with extreme content posted on the platform.                           , Christina Cravens, a spokeswoman for Parler,  said the company had always “prohibited violent and inciting content” and had invested in “content moderation best practices.”                                                                                                                                                                                                                                                                                                                           , Moderating content will also be a challenge for Truth Social, whose main star, Mr. Trump, has not been able to post messages since early 2021, when Twitter and Facebook kicked him off their platforms for inciting violence tied to the outcome of the 2020 presidential election.                                                                                                                                                                                                                   , With Mr. Trump as its main poster, it was unclear if Truth Social would grow past subscribers who sign up simply to read the former president’s missives, Mr. Matze said.                                                                                                                                                                                                                                                                                                                              , “Trump is building a community that will fight for something or whatever he stands for that day,” he said. “This is not social media for friends and family to share pictures.”                                                                                                                                                                                                                                                                                                                        , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/ge-stock-dives-red-after/story.aspx?guid={C32FBE15-C2F9-497C-AB34-E313E7589D76}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-18 23:54:31 </td>
   <td style="text-align:left;"> GE stock dives into the red after investor update on supply chain pressure - MarketWatch </td>
   <td style="text-align:left;"> Shares of General Electric Co. 
        GE,
        -5.86%
       took a dive in morning trading Friday, swinging from a slight gain to a 4.3% loss, after the industrial conglomerate disclosed that supply chain challenges will put pressure on growth, profit and free cash flow through the first half of 2022, more so than typical seasonality. "In light of recent commentary from other companies, a number of investors and analysts have been asking us for additional color about what we are seeing so far in the first quarter," the company said in investor newsletter. "While we are seeing progress on our strategic priorities, we continue to see supply chain pressure across most of our businesses as material and labor availability and inflation are affecting Healthcare, Renewable Energy and Aviation. Although varied by business, we expect these challenges to persist at least through the first half of the year." The company said the supply chain pressures are included in its previously provided full-year guidance for earnings per share of $2.80 to $3.50 and for free cash flow of $5.5 billion to $6.5 billion. The stock has shed 6.4% over the past three months, while the S&amp;P 500 
        SPX,
        -0.72%
       has lost 7.2%., The U.S. is heading out of the "full blown pandemic phase" of COVID-19 and moving toward a point where more decisions will be made at the local level and not by the federal government, allowing restrictions such as wearing face masks to be lifted over time.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-02-18 23:37:21 </td>
   <td style="text-align:left;"> Natural Gas Futures Gain Momentum </td>
   <td style="text-align:left;"> US natural gas futures gained some momentum to rise above the flatline on Friday, trading close to $4.6 per million British thermal units, as investors continued to digest the latest EIA inventory data. Although last week’s draw came 3 billion cubic feet short (bcf) of expectations at 190 bcf, the shortfall between current storage levels and the five-year average widened to 11.6%. At the same time, the two-week weather outlook points to colder-than-usual temperatures to as late as the first days of March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 23:15:35 </td>
   <td style="text-align:left;"> Toronto Stocks Down to 2-Week Low </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, extended losses for a third session in a row on Friday, to levels not seen in two weeks, as weakness in crude oil and gold prices pressured heavyweight energy and mining stocks. Concerns over the buildup of tensions between Ukraine and Russia also drove markets this session, while traders also monitored retail trade preliminary data for January, which pointed to a 2.4% rebound from a 1.8% decline in December. Meanwhile, Ottawa’s police began to arrest “Freedom Convoy” protesters in the city center to put an end to a three-week blockade. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/existing-home-sales </td>
   <td style="text-align:left;"> 2022-02-18 23:10:33 </td>
   <td style="text-align:left;"> US Existing Home Sales at 1-Year High </td>
   <td style="text-align:left;"> Existing home sales in the US which include completed transactions of single-family homes, town homes, condominiums and co-ops, jumped 6.7% mom to a seasonally adjusted annual rate of 6.5 million in January 2022, rebounding from a downwardly revised 3.8% fall in December. It is the highest level in a year, beating forecasts of 6.1 million. Total housing inventory fell to a new all-time low of 860K units and the median price for all housing types was $350,300. ""Buyers were likely anticipating further rate increases and locking-in at the low rates, and investors added to overall demand with all-cash offers. Consequently, housing prices continue to move solidly higher. There are more listings at the upper end – homes priced above $500,000 – compared to a year ago, which should lead to less hurried decisions by some buyers. Clearly, more supply is needed at the lower-end of the market in order to achieve more equitable distribution of housing wealth", said Yun, NAR's chief economist. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/existing-home-sales-defy-expectations-rising/story.aspx?guid={75557601-CF01-46AD-A547-D62C5C84E4CB}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-18 23:05:35 </td>
   <td style="text-align:left;"> Existing-home sales defy expectations, rising higher to kick off 2022 - MarketWatch </td>
   <td style="text-align:left;"> Existing-home sales increased by nearly 7% between December and January, hitting a seasonally-adjusted, annual rate of 6.5 million, the National Association of Realtors said Friday. Economists polled by MarketWatch expected the pace of home sales to come in at 6.1 million. Compared to a year ago, sales were down more than 2%. The inventory of homes for sale dropped to another record low, as the median price for an existing home rose by more than 15% on an annual basis.

, 'I've been disabled since age 13, when I almost died of an illness. My condition results in a bad immune system and very low energy. '                                                                                                                                                                                                                                                                                                                                                       , Jacob Passy is a personal-finance reporter for MarketWatch and is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/consumer-confidence </td>
   <td style="text-align:left;"> 2022-02-18 23:04:15 </td>
   <td style="text-align:left;"> Eurozone Consumer Morale Unexpectedly Weakens </td>
   <td style="text-align:left;"> The consumer confidence indicator in the Euro Area fell by 0.3 points from a month earlier to -8.8 in January 2022, the lowest level since last March and below market expectations of -8, a preliminary estimate showed. In the European Union as a whole, consumer sentiment dropped by 0.2 points to -10.2. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/consumer-confidence </td>
   <td style="text-align:left;"> 2022-02-18 22:59:21 </td>
   <td style="text-align:left;"> Colombia Consumer Morale Slumps to 7-Month Low </td>
   <td style="text-align:left;"> Colombia’s consumer confidence index plunged to -13.5 in January of 2022, from -7 in the previous month. It was the lowest reading since June amid a deterioration in both current economic conditions (-30 vs -20.6 in December), namely the propensity to buy durable goods (-51.8 vs -37.3); and future expectations (-2.4 vs 2.1), mainly for the country's economic situation and household position. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 22:48:30 </td>
   <td style="text-align:left;"> France Stocks Cut Gains </td>
   <td style="text-align:left;"> The CAC 40 erased early gains to trade 0.2% lower at the 6,930 level on Friday, on course to its third consecutive session in the red amid negative corporate news and renewed concerns of a Russian invasion amid repeated ceasefire violations in eastern Ukraine. On the corporate front, Hermes dropped 4.7% from reporting slower sales growth during the fourth quarter of 2021, mostly due to capacity constraints on its leather goods and saddlery divisions. At the same time, EDF fell 3.2% after announcing a rights issue that will raise EUR 2.5 billion to improve its financial structure, as the group struggles with low availability of its nuclear plant fleets due to corrosion and safety issues. On the other hand, Renault shares traded 2.6% higher after the automaker posted an operating margin of 3.6% for 2021, already exceeding its target set for 2023. Consequently, the group increased its margin target to 4% for 2022, despite the ongoing global shortage of semiconductors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 22:44:00 </td>
   <td style="text-align:left;"> Wall Street Lower, Poised for Weekly Decline </td>
   <td style="text-align:left;"> US stocks were mostly down in early trading Friday, following the last session's meltdown as investors reacted to conflicting headlines regarding the escalating tensions between Russia and Ukraine. In recent developments, Russian-backed rebels and Ukrainian forces traded fresh accusations of cease-fire violations at Ukraine's border. Meanwhile, the US secretary of state Antony Blinken agreed to meet with Russian foreign minister Sergei Lavrov next week, hoping for a diplomatic solution. Aside from Russia-Ukraine rhetoric, investors focused on less hawkish signals from US Federal Reserve's last meeting minutes. The central bank would not raise interest rates yet but strongly indicated a hike is on the way as soon as March, while it will start unwinding its nearly $9 trillion balance sheet. As a result, Wall Street is on track for its second weekly decline, with the Dow Jones down over 1% so far this week. The S&amp;P 500 and the tech-heavy Nasdaq 100 are almost 1% down each. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-02-18 22:39:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Snaps 3-Day Losing Run </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index rose 4.1% to 1,964 on Friday, after three consecutive sessions of losses, amid an uptick in demand for the capesize and panamax vessel segments. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, jumped 15.8% to 1,675; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, edged up 10 points to 2,375. On the other hand, the supramax index increased fell 1 point to 2,325. The Baltic Dry Index dropped 0.7% for the week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 22:19:30 </td>
   <td style="text-align:left;"> European Stocks Reverse Gains, DAX Down 1% </td>
   <td style="text-align:left;"> European equity markets reversed gains to trade lower in Friday’s afternoon trading, with Germany’s DAX losing 1% dragged down by renewed concerns over Russia-Ukraine tensions and led by an over 3% fall in Allianz shares after the company reported lower-than-expected earnings. The announcement of the evacuation of Donetsk People's Republic by Russian-backed separatist leader Denis Pushilin more than offset hopes the conflict in Ukraine could be resolved diplomatically after the US Secretary of State agreed to a meeting with Russia's foreign minister next week. On the corporate front, Renault exceeded its 2021 targets, showing upbeat profits; Sika posted a jump in full-year net profit and proposed a 16% higher dividend; Norwegian Air also reported a profit for full 2021; and Hermes grew slightly below market expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 22:04:00 </td>
   <td style="text-align:left;"> Brazilian Stocks Edge Up </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, was up 0.5% to around 114,100 on Friday, following a 1.4% loss in the previous session, driven by Cielo shares, which jumped more than 10% after the announcement that the company will sell a stake in Merchant e-Solutions for 1.5 billion reais. Market sentiment was also supported by the apparent easing of tensions in Ukraine, with a new meeting between Russia and the United States scheduled for the next week, although concerns peristed over separatist areas. Investors will also monitor corporate results from Neoenergia, Aeris, Rumo Logística and Cosan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/currency </td>
   <td style="text-align:left;"> 2022-02-18 21:56:46 </td>
   <td style="text-align:left;"> Swiss Franc Strengthens on Geopolitical Risk </td>
   <td style="text-align:left;"> The Swiss franc strengthened to a 2-week high of 0.92 per USD, after hovering at the 0.925 level in the first half of February, as investors fled to safer assets amid escalated geopolitical tensions between Russia and the West. Threats of an imminent Russian invasion in eastern Ukraine and the economic consequences of western retaliation were prevalent ahead of the meeting between the US Secretary of State and Russian Foreign Minister. On the monetary policy front, the Swiss National Bank remains committed to its ultra-loose monetary policy, as the latest labor data indicated that unemployment did not increase despite the Covid infection wave in January, while consumer inflation remains moderate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 21:51:00 </td>
   <td style="text-align:left;"> Wall Street Struggles for Traction </td>
   <td style="text-align:left;"> US stock index futures were mostly down in premarket trading Friday, following the last session's meltdown as investors reacted to conflicting headlines regarding the escalating tensions between Russia and Ukraine. In recent developments, Russian-backed rebels and Ukrainian forces traded fresh accusations of cease-fire violations at Ukraine's border. Meanwhile, the US secretary of state Antony Blinken agreed to meet with Russian foreign minister Sergei Lavrov next week, hoping for a diplomatic solution. Aside from Russia-Ukraine rhetoric, investors focused on less hawkish signals from US Federal Reserve's last meeting minutes. The central bank would not raise interest rates yet but strongly indicated a hike is on the way as soon as March, while it will start unwinding its nearly $9 trillion balance sheet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/house-price-index-mom </td>
   <td style="text-align:left;"> 2022-02-18 21:38:00 </td>
   <td style="text-align:left;"> Canada House Prices Rise Faster in January </td>
   <td style="text-align:left;"> New home prices for Canada grew by 0.9% from a month earlier in January of 2022, up from a 0.2%t increase in the previous month. Prices were up in 15 of the 27 census metropolitan areas surveyed and unchanged in 12, mainly attributed to persistently high construction costs and supply challenges. Year-on-year, new home prices advanced 11.8%, after a 11.6% rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/retail-sales </td>
   <td style="text-align:left;"> 2022-02-18 21:34:00 </td>
   <td style="text-align:left;"> Canada Retail Sales Set to Rebound in January </td>
   <td style="text-align:left;"> Retail sales in Canada likely rose 2.4 percent month-over-month in January of 2022, preliminary estimates showed. Considering December, retail sales decreased 1.8 percent over a month earlier, compared to an upwardly revised 0.8 percent increase in November and below preliminary estimates of a 2.1 percent decrease. Sales were down in 8 of the 11 subsectors, particularly in furniture and home furnishings stores (-11.3 percent), clothing and clothing accessories stores (-9.5 percent), and food and beverage stores (-0.7 percent). Across major Canadian provinces, losses took place in British Columbia (-1.4 percent), largely due to severe flooding in the area that affected 15% of respondents, while retail activity also dropped in Ontario (-1.8 percent). On the year, retail trade was up 8.6 percent in December, picking up from a 4.4 percent increase in November. Considering full 2021, retail sales increased by 11.6 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/moldova/industrial-production </td>
   <td style="text-align:left;"> 2022-02-18 20:58:16 </td>
   <td style="text-align:left;"> Moldova Industrial Output Growth Quickens in December </td>
   <td style="text-align:left;"> Industrial Production in Moldova advanced by 11.4 percent year-on-year in December of 2021, after an upwardly revised 7.5 percent rise in the previous month. It was the eleventh consecutive month of growth in industrial activity and at the fastest pace since last September. On a monthly basis, industrial production grew 5.7 percent. Considering the full year of 2021, industrial production grew 12.1 percent, recovering from a 5.5 percent contraction in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-18 20:58:00 </td>
   <td style="text-align:left;"> German 10-Year Bund Yield Falls from 3-Year High </td>
   <td style="text-align:left;"> Germany's benchmark Bund yield fell to 0.23% from a 3-year high reached earlier in the week at above 0.3%, as global sentiment bounced and investors returned again to riskier assets amid talks between the West and Russia. On the monetary policy front, several ECB officials have been calling for an end to the ECB's bond-buying programme, which is a precondition set by the ECB for raising rates. Still, ECB Chief Christine Lagarde reiterated that any change in the bank's policy will be gradual. On the data front, German investor sentiment rose in February, although less than forecast, on expectations that restrictions to contain Covid-19 will ease. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/18/stocks-making-the-biggest-moves-premarket-draftkings-roku-deere-and-others.html </td>
   <td style="text-align:left;"> 2022-02-18 20:52:00 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: DraftKings, Roku, Deere and others </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                             , Check out the companies making headlines before the bell:                                                                                                                                                                                                                                                                                                                                                                                                   , DraftKings (DKNG) – The sports betting company's stock tumbled 13.2% in the premarket, despite a narrower-than-expected quarterly loss and revenue that beat estimates. DraftKings projects a wider-than-expected adjusted loss for the full year as costs continue to rise.                                                                                                                                                                                , Roku (ROKU) – Roku shares were down 26% in the premarket, despite better-than-expected earnings for its latest quarter. The maker of video streaming devices' revenue fell short of analyst forecasts, and it issued a weaker-than-expected outlook due to higher component prices and supply chain disruptions.                                                                                                                                            , Bloomin' Brands (BLMN) – The restaurant operator beat estimates by 8 cents with an adjusted quarterly profit of 60 cents per share, with revenue slightly above consensus. The parent of Outback Steakhouse and other chains also reinstated its quarterly dividend and announced a new $125 million share buyback program. The stock surged 6.6% in premarket action.                                                                                      , Deere (DE) – The heavy equipment maker reported quarterly earnings of $2.92 per share, well above the $2.26 consensus estimate, with revenue also topping analyst forecasts. The company also raised its annual profit forecast amid solid demand and higher prices.                                                                                                                                                                                        , Shake Shack (SHAK) – Shake Shack reported an adjusted quarterly loss of 11 cents per share, narrower than the 11-cent loss analysts were anticipating, while the restaurant chain's revenue matched Wall Street forecasts. Shake Shack said the omicron variant kept customers away and led to some temporary restaurant closures. It also issued a downbeat current-quarter forecast amid increasing costs. Shake Shack plunged 15.5% in premarket trading., Dropbox (DBX) – Dropbox beat estimates by 4 cents with adjusted quarterly earnings of 41 cents per share, and the software company's revenue also topped Street projections. Paid user numbers and average revenue per user also came in above consensus, but the stock slid 6.3% in premarket action as its guidance for current-quarter profit margin was slightly lower than expected.                                                                   , DuPont (DD) – DuPont finalized a deal to sell the majority of its materials unit to specialty materials maker Celanese (CE) in an $11 billion deal. DuPont jumped 4.1% in the premarket while Celanese gained 3.8%.                                                                                                                                                                                                                                         , Pilgrim's Pride (PPC) – Pilgrim's Pride slumped 14.8% in premarket trading after Brazilian meatpacker JBS dropped plans to buy the portion of the poultry producer that it doesn't already own. JBS holds an 80% stake in Pilgrim's Pride, but the two sides could not agree on terms of a deal for the remaining 20%.                                                                                                                                      , Intel (INTC) – Intel Chief Executive Officer Pat Gelsinger told an investor gathering that the chipmaker is aiming to achieve double-digit annual revenue growth in three to four years. Gelsinger also said Intel may be interested in participating in a potential consortium if one is formed to buy British semiconductor company Arm Ltd. Intel fell 1% in premarket trading.                                                                          , NortonLifeLock (NLOK) – NortonLifeLock pushed back the expected completion date of its deal to buy rival cybersecurity company Avast to April 4 from Feb. 24, saying it was still waiting for regulatory approvals in the U.K. and Spain. NortonLifeLock fell 1% in the premarket.                                                                                                                                                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/senegal/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-18 20:40:00 </td>
   <td style="text-align:left;"> Senegal January Inflation Rate Steepest since 2008 </td>
   <td style="text-align:left;"> The annual inflation rate in Senegal accelerated to 5.5 percent in January of 2022, from 3.8 percent in the previous month. That was the highest rate since October of 2008, mainly pushed up by prices of food &amp; non-alcoholic beverages (9.1 percent vs 5.4 percent in December), of which fresh products (8.8 percent); and restaurants &amp; hotels (3.3 percent, the same pace as in December). On the other hand, costs fell further for communication (-7.2 percent vs -2.9 percent). On a monthly basis, consumer prices edged up 0.3 percent, following a 0.1 percent uptick in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/serbia/current-account </td>
   <td style="text-align:left;"> 2022-02-18 20:23:20 </td>
   <td style="text-align:left;"> Serbia Current Account Deficit Widens in December </td>
   <td style="text-align:left;"> Serbia’s current account deficit widened to USD 576 million in December of 2021 from USD 22 million in the corresponding month of the previous year. The goods and services gap rose to USD 666 million from USD 491 million. At the same time, the primary income shortfall widened to USD 460 million from USD 117 million and the secondary income surplus narrowed to USD 473 million from USD 586 million. Considering the January-December period of 2021, the current account deficit widened to USD 2.7 billion from USD 2.2 billion in the same period last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/de:us </td>
   <td style="text-align:left;"> 2022-02-18 20:17:08 </td>
   <td style="text-align:left;"> Deere &amp; Company earnings above expectations at 2.92 USD </td>
   <td style="text-align:left;"> Deere &amp; Company (DE) released earnings per share at 2.92 USD, compared to market expectations of 2.24 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60429584?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-18 20:09:07 </td>
   <td style="text-align:left;"> Luxury cars up in smoke after ship catches fire </td>
   <td style="text-align:left;"> Thousands of Porsche and Volkswagen cars have been abandoned on a cargo ship after it caught fire in the Atlantic Ocean en route to the US.                                                                                                 , The ship, named Felicity Ace, was travelling from Emden in Germany before it caught ablaze off the coast of Portugal's Azores islands.                                                                                                      , German newspaper Handelsblatt reported the vessel was carrying 3,965 vehicles, which also included Audis, Lamborghinis and a small number of Bentleys.                                                                                      , The ship's crew have been rescued.                                                                                                                                                                                                          , Portugal's navy said no one was hurt by the fire, which broke out on Wednesday, and the 22 crew members were taken to a hotel after the navy, four merchant ships sailing in the area and the Portuguese Air Force completed the evacuation., "The owner of the ship Felicity Ace is in contact with the logistic agent in order to draw up a plan for the towing of the ship," the navy said in a statement.                                                                             , "So far, no source of pollution has been recorded."                                                                                                                                                                                         , According to Handelsblatt, an internal email from Volkswagen USA stated that the ship was carrying 3,965 vehicles of the VW, Porsche, Audi and Lamborghini brands.                                                                          , Volkswagen did not confirm the number of cars on board, but Porsche said it had about 1,100 of its models on the ship.                                                                                                                      , The company said it was "aware of an incident involving a third-party cargo ship transporting Volkswagen Group vehicles across the Atlantic".                                                                                               , Bentley confirmed that 189 of its cars were also onboard the ship.                                                                                                                                                                          , "We are working with the shipping company to find out further information," said a spokesman.                                                                                                                                               , The ship was travelling to a Volkswagen factory in Davisville, Rhode Island, according to the website Marine Traffic.                                                                                                                       , One customer tweeted to say his Porsche was on board the abandoned ship.                                                                                                                                                                    , Richard Osman on life as a broadcaster and writer                                                                                                                                                                                           , Behind the faces leading US far right political movements online                                                                                                                                                                            , Six gruelling days at the world’s toughest mountain race                                                                                                                                                                                    , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/senegal/industrial-production </td>
   <td style="text-align:left;"> 2022-02-18 20:00:11 </td>
   <td style="text-align:left;"> Senegal’s Industrial Output Growth Contracts in December </td>
   <td style="text-align:left;"> Senegal’s industrial production fell by 5.5 percent year-on year in December of 2021, after a 7.1 percent expansion in the previous month. It was the first contraction in industrial output since June of 2020, dragged down by manufacturing (-11 percent) and mining &amp; quarrying (-8.9 percent). However, the output rose for environmental industries (126.9 percent) and electricity, gas &amp; water (13.6 percent). Considering full 2021, industrial production jumped 17.2%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 19:51:00 </td>
   <td style="text-align:left;"> South African Stocks Flat </td>
   <td style="text-align:left;"> The JSE FTSE All Share index erased gains to trade along the flatline around 76,130 on Friday afternoon, after a separatist leader in eastern Ukraine announced the evacuation of civilians to Russia amid soaring tensions. Meanwhile, the US secretary of state and Russia’s foreign minister are reportedly scheduled to meet next week to diffuse the Ukraine tension. On the domestic front, President Ramaphosa is dismissing accusations that it created a shadow cabinet within the presidency because it distrusts some of its ministers, saying the extra appointees will help the government to become more efficient and cohesive. On the earnings front, South African retailer Massmart, the owner of Makro, Game and Builders, has flagged a more than 2 billion rand loss for its 2021 year, hit by the effects of July’s civil unrest as well as the timing of insurance payouts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/croatia/unemployment-rate </td>
   <td style="text-align:left;"> 2022-02-18 19:40:50 </td>
   <td style="text-align:left;"> Croatia Jobless Rate Falls to 7.8% in January </td>
   <td style="text-align:left;"> The unemployment rate in Croatia declined to 7.8 percent in January of 2022 from 9.8 percent in the corresponding month of the previous year, amid the ongoing labor market recovery. The number of unemployed slumped 20.7 percent to 130.9 thousand people, while the number of employed rose 2.5 percent to 1,553 million people. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belgium/consumer-confidence </td>
   <td style="text-align:left;"> 2022-02-18 19:40:05 </td>
   <td style="text-align:left;"> Belgium Consumer Morale Rises Further in February </td>
   <td style="text-align:left;"> The consumer confidence indicator in Belgium rose to 1 in February of 2022 from -2 in the previous month, the highest since November 2021 and significantly above the long-term average. Consumers noted favorable developments in the labor market and appeared more optimistic about Belgium’s economic situation in the next twelve months. At the same time, respondents expect their savings to significantly increase, despite presuming deteriorated financial situation for households. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-02-18 19:11:57 </td>
   <td style="text-align:left;"> Heating Oil Extends Losses to 2-Week Low </td>
   <td style="text-align:left;"> Heating oil futures extended losses toward $2.7 per gallon, the lowest in near two weeks and are about 8% below a 7-1/2-year high of $2.96 hit on February 14th dragged down by the prospect of a return of Iranian oil to international markets. The US and Iran suggested that an agreement of the 2015 nuclear pact is closer than ever, raising expectations the US will remove sanctions on Iran's oil and shipping which could mean the release of an extra 1 million supply barrels of oil to markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/construction-output </td>
   <td style="text-align:left;"> 2022-02-18 19:10:42 </td>
   <td style="text-align:left;"> Italy Construction Output Growth at 7-Month High </td>
   <td style="text-align:left;"> Construction output in Italy jumped 19.3 percent year-on-year in December of 2021, the steepest growth rate since May and picking up from the upwardly revised 14.7 percent increase in the November. On a seasonally adjusted monthly basis, construction activity edged 0.3 percent higher, following an upwardly revised 1.9 percent in the prior month. Considering the annual growth rates, construction activity advanced 24.3 percent in 2021, largely due to limited construction output in 2020 during the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 19:07:00 </td>
   <td style="text-align:left;"> BSE Sensex Extends Declines, Books 0.5% Weekly Loss </td>
   <td style="text-align:left;"> The BSE Sensex ended 59.04 points or 0.1% lower to close at 57,833 on Friday, extending declines for the third straight session as investors remained cautious over the persistent Russia-Ukraine tensions. Moreover, domestic sentiment was slightly downbeat after the SBI in its Ecowrap research report estimated India’s GDP to grow by 5.8% during the October-December period of 2021 while it also revised lower the GDP growth rate to 8.8% for the full 2021-2022 fiscal year compared to its earlier estimate of 9.3%. Losses in capital goods and technology slightly outweighed the gains in banks and financials. Among the individual stocks, 17 out of 30 stocks on BSE Sensex ended in the red, with declines led by Ultra Cement Company (-1.88%), Mahindra and Mahindra (-1.36%), Infosys (-1.06%) and Reliance (-0.85%). On the week, the BSE booked a 0.55% loss. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/nickel </td>
   <td style="text-align:left;"> 2022-02-18 18:54:52 </td>
   <td style="text-align:left;"> Nickel Rally Gains Stream </td>
   <td style="text-align:left;"> Nickel futures climbed above the $24,200 per tonne level for the first time in a month, closing in on its highest level since 2011, amid robust demand from the stainless steel and battery sectors against the backdrop of dwindling inventories. On top of that, the prospect of sanctions on Russia, a major producer of the metal, deepened concerns of diminished supply. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 18:49:00 </td>
   <td style="text-align:left;"> Madrid Stocks Trade Muted on Friday </td>
   <td style="text-align:left;"> The Ibex 35 traded around the flatline at the 8,660 mark on Friday, as investors weighed on fresh corporate news while monitoring geopolitical developments between Russia and Ukraine, amid claims of ceasefire violations by both Kyiv and Russian-backed separatists ahead of next week’s meeting between the Russian Foreign Minister and US Secretary of State. Siemens Gamesa shares fell 2% after Siemens Energy CEO Christian Bruch emphasized that the market environment in the onshore wind turbine business will remain difficult in the near future. At the same time, Anea dropped 2.1% after the Spanish competition authorities approved a 3.17% reduction in selected fees charged at the group’s airports. On the other hand, Banco Sabadell gained 2.6% after UBS upgraded its recommendation on the lender. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/aluminum </td>
   <td style="text-align:left;"> 2022-02-18 18:41:00 </td>
   <td style="text-align:left;"> Aluminum Hits Fresh Record High </td>
   <td style="text-align:left;"> Aluminum hit a fresh all-time high of $3,313 amid dwindling inventories and concerns about further supply disruptions. The West's stand-off with Russia over Ukraine has raised prospects of sanctions on one of the world's largest metal suppliers, triggering a rush to aluminum stocks at LME warehouses, which currently sit at roughly 50% of March 2021 levels. Meantime, in China, the biggest producer and consumer of aluminum, the pandemic and pollution curbs amid the winter Olympics forced producers to halt production. As a result, the commodity rose more than 5% this week and is on track for its biggest weekly gain since early November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 18:24:00 </td>
   <td style="text-align:left;"> European Shares Rise, Allianz Weighs on the Dax </td>
   <td style="text-align:left;"> The Dax struggled to keep early gains and was little changed on Friday, with shares of Allianz among the worst performers (-1.4%) after the company reported lower-than-expected earnings although its revenues topped estimates. However, other major bourses in Europe extended gains to add around 0.4% each amid hopes the conflict in Ukraine could be resolved diplomatically after the US Secretary of State agreed to a meeting with Russia's foreign minister next week. Traders also digest fresh corporate results: Renault exceeded its 2021 targets, showing upbeat profits; Sika posted a jump in full-year net profit and proposed a 16% higher dividend; Norwegian Air also reported a profit for full 2021; and Hermes grew slightly below market expectations. On the week, stocks are set to lose around 1%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-02-18 18:20:39 </td>
   <td style="text-align:left;"> Brent Crude Falls to $91, Heads for 1st Weekly Drop in 2021 </td>
   <td style="text-align:left;"> Brent crude futures extended losses to more than 2% to around $91 per barrel on Friday and were headed for their first weekly decline since the second week of December, as the prospect of Iranian oil returning to the market outweighed fears of possible supply disruptions from a Russia-Ukraine conflict. Reuter reported that a deal to revive the 2015 Iran nuclear deal is taking shape, with a draft accord outlining a sequence of steps that would eventually lead to granting waivers on oil sanctions, and bring about 1 million barrels a day of oil back to the market. Meanwhile, investors remain at the mercy of a volatile and tense standoff in Ukraine. Analysts expect oil to hold in the $90 to $100 a barrel range despite the potential return of Iranian oil exports, as geopolitical uncertainties and a tight global market, driven by capacity constraints and demand recovery continue to keep energy prices elevated. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-02-21 08:49:38 UTC +8

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
   <td style="text-align:left;"> 2022-02-21 08:49:20 </td>
   <td style="text-align:left;"> $SPY 4 years of Trump.. mean tweets No war! 

1 year of Biden.. no tweets Radiation poisoning 🤦🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:49:12 </td>
   <td style="text-align:left;"> $SPY there you have it..no war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:49:02 </td>
   <td style="text-align:left;"> $SPY Hi. I’d like to order one order of “$425 open on Tuesday” with a large side of “Continuation down to $415 by EOD”.

Thanks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:49:02 </td>
   <td style="text-align:left;"> $SPY Nikkei down 600 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:48:58 </td>
   <td style="text-align:left;"> $SPY Here is what I want to know.. Will the Brandon administration try a last ditch effort to ease tensions with Russia, by deploying identity politics and calling Russia racist? It could be a winning tactic, you know! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:48:49 </td>
   <td style="text-align:left;"> $SPY War imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:48:33 </td>
   <td style="text-align:left;"> $SPY Yep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:48:31 </td>
   <td style="text-align:left;"> $SPY Wouldn&amp;#39;t it be great if Putin called Biden&amp;#39;s bluff and didn&amp;#39;t invade?  Then Old Joe wouldn&amp;#39;t have an excuse for the economic turmoil we are about to undergo.  I don&amp;#39;t think I&amp;#39;ve ever really been bearish on the market but things aren&amp;#39;t looking great economically. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:48:28 </td>
   <td style="text-align:left;"> $SPY Oh man....ugly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:48:23 </td>
   <td style="text-align:left;"> $GLD $SPY $BTC.X Stock market continues to crash, Bitcoin continues to crash, Gold is performing nicely as a store of value. Sweet! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:48:09 </td>
   <td style="text-align:left;"> $SPY Hey, can we stop the “bears are wishing for war” rhetoric on here? It’s fucking childish as well as not true. Most bears on here have been calling for a correction due to rate hikes, inflation numbers, QT, all kinds of relevant shit that had nothing to do with Russia/Ukraine. Bulls, take your L and stop trying to twist the narrative because you blew up your account again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:47:57 </td>
   <td style="text-align:left;"> $SPY why Biden dares to shake Putin&amp;#39;s hand and without mask during deadly pandemic? $PFE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:47:57 </td>
   <td style="text-align:left;"> $SPY Trump saved the world from radiation poisoning…… liberals think radiation is progressive 🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:47:53 </td>
   <td style="text-align:left;"> $SPY 🔥🔥🚬

Perma bears are smarter than perma bulls. This is a fact. BUT perma bulls make fuck load more money than perma bears. This is also a fact. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:47:18 </td>
   <td style="text-align:left;"> $SPY S&amp;amp;P Oil/fossil fuel assets top 32.04 Billion$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:47:11 </td>
   <td style="text-align:left;"> $SPY American media propaganda.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:46:56 </td>
   <td style="text-align:left;"> $SPY flash crash Tuesday tyvm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:46:54 </td>
   <td style="text-align:left;"> $SPY Nikkei dumping 2% down so far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:46:50 </td>
   <td style="text-align:left;"> $SPY Idk I dont trust the gold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:46:43 </td>
   <td style="text-align:left;"> $SPY Run! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:46:35 </td>
   <td style="text-align:left;"> $SPY ..,.- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:46:27 </td>
   <td style="text-align:left;"> $SPY why do we care about Ukraine it’s not a nato country fuck em </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:46:25 </td>
   <td style="text-align:left;"> $SPY who’s all gitty about their puts 😂😂😂  can’t get out can you! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:46:13 </td>
   <td style="text-align:left;"> $SPY As world leaders condemn Russian aggression, Trump says he and Putin &amp;#39;get along&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:45:56 </td>
   <td style="text-align:left;"> $SPY why was everyone jerking off over a low volume week? Next 3 weeks are gunna melt faces. Fuckn amateurs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:45:54 </td>
   <td style="text-align:left;"> $SPY Bulls cars puttin, while bears be &amp;quot;put in&amp;quot; thanks to Putin... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:45:35 </td>
   <td style="text-align:left;"> $SPY im telling u… we’ll see 390 before 450 smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:45:32 </td>
   <td style="text-align:left;"> $SPY please don&amp;#39;t spend 36 hours staring at futes. 

With that said, tanking heavy , but we got a lonnnnnnng way to go til 9:30 Tuesday; so, you SHOULD know there will be ebbs and flows between now and then. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:45:28 </td>
   <td style="text-align:left;"> $SPY ascending triangle gap fill imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:45:27 </td>
   <td style="text-align:left;"> $SPY Nikkei 225 drops 2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:45:21 </td>
   <td style="text-align:left;"> $SPY if futures were up even just .2% bulls would going wilddd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:45:16 </td>
   <td style="text-align:left;"> $SPY Nikkei falls 2%
Asia markets: Russia-Ukraine crisis, China&amp;#39;s benchmark lending rate https://www.cnbc.com/2022/02/21/asia-markets-russia-ukraine-tensions-china-loan-prime-rate-currencies-oil.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:45:08 </td>
   <td style="text-align:left;"> $SPY short sellers are absolutely spazzing out in the comments section of stocktwits. Fun to read :D </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:45:05 </td>
   <td style="text-align:left;"> $SPY that moment when you realize S&amp;amp;P is still weighted roughly 5.4% Oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:45:01 </td>
   <td style="text-align:left;"> $SPY so no war today?? Perhaps tomorrow if Biden gives a speech about invasion? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:44:42 </td>
   <td style="text-align:left;"> $SPY We pay for Trump&amp;#39;s treason. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:44:34 </td>
   <td style="text-align:left;"> $SPY degenerates gambling otm calls are going to be in tears coming Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:44:32 </td>
   <td style="text-align:left;"> $SPY .5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:44:23 </td>
   <td style="text-align:left;"> $SPY Bears out there feasting smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:44:15 </td>
   <td style="text-align:left;"> $SPY open 420 on Tuesday would be 👌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:43:38 </td>
   <td style="text-align:left;"> $SPY Is this the bottom? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:43:21 </td>
   <td style="text-align:left;"> $SPY &amp;quot;PUT&amp;quot;IN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:43:18 </td>
   <td style="text-align:left;"> $SPY why we are here: Straight from Trump’s own inner circle. (Trumptards won’t read it and will slam CNN, but it’s worth reading to the end.) 

https://stocktwits.com/onlyiknow/message/437958218 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:43:11 </td>
   <td style="text-align:left;"> $SPY Bitcoin is down. SPY going down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:43:01 </td>
   <td style="text-align:left;"> $SPY I thought market is close tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:43:00 </td>
   <td style="text-align:left;"> $SPY THE ONLY WAR I SEE IS IN THE STOCKTWITS COMMENT SECTION </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:59 </td>
   <td style="text-align:left;"> $SPY wow 🍄❄️🏂 Grand Targhee @CuloCapital feeling goooood 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:56 </td>
   <td style="text-align:left;"> $SPY 
Meantime in a alternate dimension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:45 </td>
   <td style="text-align:left;"> $SPY FUTURES RIPPIN!! $GLD futures that is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:38 </td>
   <td style="text-align:left;"> $SPY Shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:33 </td>
   <td style="text-align:left;"> $SPY Shorts are getting up in arms. WHERE IS THE WAR? WHERE IS THE INVASION?      LONG https://www.cbsnews.com/news/russia-ukraine-ambassador-anatoly-antonov-no-such-plans-invasion-face-the-nation/?intcid=CNI-00-10aaa3a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:23 </td>
   <td style="text-align:left;"> $SPY all of 2022, SPY and FED Balance sheet have been diverging… hodl puts. Calls are for gamblers now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:19 </td>
   <td style="text-align:left;"> $SPY Biden will not save your calls 
Oil to $100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:14 </td>
   <td style="text-align:left;"> $SPY Russia is not going to attack and never has intended to do so. The Democrats will use this as a victory for Biden, even though he never did anything other than say they are about to attack, knowing it isn’t happening. All a game folks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:12 </td>
   <td style="text-align:left;"> $SPY $DJIA  It’s worth a shot at this point 🤷‍♂️🤔🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:10 </td>
   <td style="text-align:left;"> $SPY I swear yall just get on here and say shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:08 </td>
   <td style="text-align:left;"> $SPY masks bring out eyes in girls 
That&amp;#39;s why they wear them more than men
It is a female clothing piece now
Virus has nothing to do with it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:42:07 </td>
   <td style="text-align:left;"> $SPY  $QQQ 

Are we open tomorrow?

Or we don’t celebrate this Presidents’ Day specially because of Brandon ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:41:53 </td>
   <td style="text-align:left;"> $SPY don’t think stupid and burn your hands bulls…ask is simple, investors are tensed with Inflation repercussions and Russia war and we will go down “no matter what”…. Why fight the trend? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:41:42 </td>
   <td style="text-align:left;"> $SPY Nikkei red 2% boyos. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:41:41 </td>
   <td style="text-align:left;"> $DWAC It not politics it is just business...there are going to be huge orders place for Tuesday&amp;#39;s pre-market. Get line, but how high do you chase? 
 
No matter what DW will hit a new high Tuesday morning, as long as there are no shenanigans.   
 
It will be fun, but if your RED/Blue/Left/right, only buy because you want green. $SPY  
 
oh, and Russia may invade Ukraine Tuesday, the Donald knows how to throw a party </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:41:11 </td>
   <td style="text-align:left;"> $SPY 2021 Fake Rally.  SPY back to 2020 Prices by EOW.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:40:48 </td>
   <td style="text-align:left;"> $SPY https://www.cnbc.com/2022/02/21/asia-markets-russia-ukraine-tensions-china-loan-prime-rate-currencies-oil.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:40:45 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
FED has lost control of the printer! 
 
They can&amp;#39;t turn it off!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:40:39 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.cnbc.com/2022/02/20/biden-abruptly-cancels-delaware-trip-after-top-level-calls-on-ukraine.html 
 
Exactly what a great leader should do during the unusual situation, if it were Trump he would be golfing on the golf courses right now 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:40:32 </td>
   <td style="text-align:left;"> $FB $SPY $QQQ all this bitching and whining about inflation and Russia-Ukraine and collapse. But really this is like 1992 and metaverse will change the world much like the internet did. OHHHHHHHH!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:40:10 </td>
   <td style="text-align:left;"> $SPY ugly looking head &amp;amp; shoulders pattern. Potential price target of $390 if the pattern completed, another 10% of downside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:40:06 </td>
   <td style="text-align:left;"> $SPY futes rippin… your lotto calls to shreds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:39:59 </td>
   <td style="text-align:left;"> $SPY how many times we seen this story. Futures tank on a meaningless Sunday because market is closed on Monday. 
 
and Monday nights futures which ACTUALLY matters is mighty green ?? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:39:23 </td>
   <td style="text-align:left;"> $SPY $SPX Hyperinfaltion, Possible war that can cause higher inflation numbers or recession(you chose one or the other, explained below), Fed policy error,  another large Chinese real estate company (Zhenro Properties) just announced they will not be able to make bond payments, nothing is looking good.  

 https://twitter.com/elerianm/status/1495439643235561474?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:39:19 </td>
   <td style="text-align:left;"> $SPY 👀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:39:06 </td>
   <td style="text-align:left;"> $SPY bears might be in for a surprise. I play both sides. Just looking at statistics here in a non bias way. Strategy here is don’t be a permanent bear or bull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:38:53 </td>
   <td style="text-align:left;"> $SPY 🤣

https://babylonbee.com/news/canadian-atms-now-asking-your-political-views-before-allowing-you-to-withdraw-money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:38:53 </td>
   <td style="text-align:left;"> $SPY futures are tanking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:38:48 </td>
   <td style="text-align:left;"> $SPY is looking bearish on the weekly chart. 9 EMA is going below 21 MA. Last time this happened was the COVID Crash in March 2020. Join public discord to learn technical analysis and make money with option trading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:38:40 </td>
   <td style="text-align:left;"> $SPY 🐻 before wishing for a war you might wanna do some research on how market performs during a war general trend has been up 😂 You bears are just so dumb lol😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:38:39 </td>
   <td style="text-align:left;"> $SPY 440 by tuesday morning, let&amp;#39;s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:38:37 </td>
   <td style="text-align:left;"> $SPY yeah futes ain’t ripping guys lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:38:22 </td>
   <td style="text-align:left;"> Consistency is key $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:38:13 </td>
   <td style="text-align:left;"> $SPY perfect three day weekend for MMs to dump their position regardless war or no war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:38:10 </td>
   <td style="text-align:left;"> $SPY Trump sold us out to Russia.  Now the price is being paid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:38:05 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:37:39 </td>
   <td style="text-align:left;"> $SPY sleepy joe. Fuck you if you voted for him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:37:28 </td>
   <td style="text-align:left;"> $SPY If I was a MM I&amp;#39;d either dump it really hard rn or pump since most retails can&amp;#39;t trade. Not looking good for the bulls though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:37:00 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
of course! 
 
you still printing BILLIONS, right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:36:54 </td>
   <td style="text-align:left;"> $SPY okay if it opens at 420ish what’s the plan? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:36:35 </td>
   <td style="text-align:left;"> $SPY nothing matters but price actions. “SHOW ME THE CHARTS AND ILL TELL YOU THE NEWS” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:36:30 </td>
   <td style="text-align:left;"> $SPY I bought puts on Friday even though Theta was bad on a 3-day weekend. 

Confident in a $425 open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:36:30 </td>
   <td style="text-align:left;"> $QQQ happy Presidents’ Day to my president! $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:36:18 </td>
   <td style="text-align:left;"> $SPY is fute rippin ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:36:17 </td>
   <td style="text-align:left;"> $SPY face down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:36:13 </td>
   <td style="text-align:left;"> $SPY two days of only futures trading is miserable with all this news driven stuff going on lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:36:08 </td>
   <td style="text-align:left;"> $SPY Just a little war. Give me $400 please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:35:49 </td>
   <td style="text-align:left;"> $SPY thank god Joe is our President </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:35:46 </td>
   <td style="text-align:left;"> $SPY https://apnews.com/article/russia-ukraine-russia-united-states-europe-black-sea-a4e14d1b12c119c81d07dd3876cb057b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:35:33 </td>
   <td style="text-align:left;"> $SPY I’m so freakin tired of losing money. Always a crazy reason </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:35:20 </td>
   <td style="text-align:left;"> $SPY There is no war yet bulls wanna be cocky about the market being green??? u kidding me?? lmao!!! why would u be bullish wen there is a “war” happening or not.. Thanks for your free money on my puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:35:08 </td>
   <td style="text-align:left;"> $SPY futures rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:35:06 </td>
   <td style="text-align:left;"> $SPY Asia down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:35:03 </td>
   <td style="text-align:left;"> $SPY $AMD $ROKU Earnings reports today before the markets open&amp;quot;  amazingroom.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:34:55 </td>
   <td style="text-align:left;"> $SPY watch it shoot up tomorrow for no reason just so the MMs can destroy your puts. Seen it happen many times. The news will just say something like &amp;quot;Market returns to risk on as buyers see opportunity after sell off&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:34:49 </td>
   <td style="text-align:left;"> $SPY bulls looking at the future lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:34:44 </td>
   <td style="text-align:left;"> $SPY going to be really fun spreading FUD all night tonight, all day tomorrow, and all night tomorrow!!! FUD rules!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:34:40 </td>
   <td style="text-align:left;"> $SPY so no invasion . Ok good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:34:38 </td>
   <td style="text-align:left;"> $SPY Biden going to bat for you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:34:27 </td>
   <td style="text-align:left;"> $SPY  
 
long  3 MES at 4320 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:34:24 </td>
   <td style="text-align:left;"> $SPY Missed the top will we stick the landing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:34:12 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m buying calls. Once I cash my puts at the lower 400s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:34:10 </td>
   <td style="text-align:left;"> $SPY Send Hilary to talk to Putin... lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:33:52 </td>
   <td style="text-align:left;"> $SPY I hope it stays red on Tuesday so I can load the boat before it reverses to green.  
 
If No war by Tuesday we all know 
no war at all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:33:51 </td>
   <td style="text-align:left;"> $SPY gold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:33:12 </td>
   <td style="text-align:left;"> $SPY War!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:33:10 </td>
   <td style="text-align:left;"> $SPY steady tanking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:32:41 </td>
   <td style="text-align:left;"> $SPY And here are the Bonds....✌️😊🧑‍🎓🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:32:35 </td>
   <td style="text-align:left;"> $SPY Even algos have stopped believing the bears fantasy fake war which is never gonna happen 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:32:35 </td>
   <td style="text-align:left;"> $SPY lord forgive me for I have sinned.. entered bull for a bounce play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:32:25 </td>
   <td style="text-align:left;"> $SPY yo... South Africa&amp;#39;s market just keeps going higher. Might park my money there lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:32:20 </td>
   <td style="text-align:left;"> $SPY War intensifying maybe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:32:04 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:32:00 </td>
   <td style="text-align:left;"> $SPY fed was more dovish than expected Friday. If Tues washes out I’ll buy some. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:31:48 </td>
   <td style="text-align:left;"> $SPY About to pop up here! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:31:47 </td>
   <td style="text-align:left;"> $SPY Everyone that knows me from this thread knows I&amp;#39;m bearish about current market conditions. This however never had anything to do with war. If you&amp;#39;re holding puts way out of the money, I wouldn&amp;#39;t be getting all giddy and excited. Why? Bonds are about flat, and the dollar is up fairly large at .32%. Have a great night y&amp;#39;all. ✌️😊🧑‍🎓🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:31:45 </td>
   <td style="text-align:left;"> $SPY  WHERE           IS          THE          WAR      MORONS????????     LONG  
 
https://www.cbsnews.com/news/russia-ukraine-ambassador-anatoly-antonov-no-such-plans-invasion-face-the-nation/?intcid=CNI-00-10aaa3a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:31:43 </td>
   <td style="text-align:left;"> $SPY you know invasion is near when BBW starts trending, along with........ Corn?!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:31:42 </td>
   <td style="text-align:left;"> $SPY https://twitter.com/chrismurphyct/status/1494428782823890944?s=21
Facts! Putin will play this invasion game for the next 6 months or for as long as oil stays over $90/barrel 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:31:38 </td>
   <td style="text-align:left;"> $SPY $QQQ  $VTI  the drop any newsboys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:31:17 </td>
   <td style="text-align:left;"> $QQQ $SPY $SQQQ  putin slaughtering bulls this week and trumpies are going to blame brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:31:11 </td>
   <td style="text-align:left;"> $SPY this is the question for some experts who understand market dynamics very well. 
 Let say when some hedge fund is buying a stock, and stock skyrockets, which means market makers go naked shorting to provide instant liquidity right..? 
How much time these market makers get to cover those naked short../ 
does SEC watch those numbers closely to make sure market makers absolutely cover when they go short to provide liquidity? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:31:07 </td>
   <td style="text-align:left;"> $SPY Elon is gonna buy the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:30:46 </td>
   <td style="text-align:left;"> $SPY Putin on the move! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:30:29 </td>
   <td style="text-align:left;"> $SPY Biden says war is imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:30:18 </td>
   <td style="text-align:left;"> $SPY I want futes to burn all the fuel it can to the downside. When we open on Tuesday, an exhausted sell algo will switch fast and hard to bullish! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:30:12 </td>
   <td style="text-align:left;"> $SPY $IWM $BTC.X $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:30:02 </td>
   <td style="text-align:left;"> $SPY  and $QQQ in peril for months. 
 
Losing Monday as a trading day is so nasty and we will all be lucky if we are not falling into the 420&amp;#39;s while the Holiday is celebrated and other markets implode. 
 
We must pray for stability into the Tuesday open. If you are religious...start praying soon.  If you fail, you may need to reassess the power of your faith and act accordingly. 
 
This is not good at all. Many will not escape the carnage. 
 
Nasty days ahead!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:29:57 </td>
   <td style="text-align:left;"> $SPY if this doesn&amp;#39;t get pumped up within the week, the support has been breached. Expect dumping by the whales. 

Who needs Putin or the incompetent Fed, when we have Biden&amp;#39;s FUD to tank the economy. Lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:29:46 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:29:45 </td>
   <td style="text-align:left;"> $SPY war would happen in pitch dark so Putin has a few hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:29:40 </td>
   <td style="text-align:left;"> $SPY $UVXY question. how has VIX not gone over 30 in the last couple months? So many stocks have taken over a 50% haircut since then. Will that only happen if the other blue chip mega caps go down? FB already jumped off a cliff. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:29:38 </td>
   <td style="text-align:left;"> $SPY how it feels right now. Can’t even run for cover 🤦🏻‍♂️ 😬😬😬😬😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:29:29 </td>
   <td style="text-align:left;"> $SPY 36 hours left of futures selling alone 🤤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:29:15 </td>
   <td style="text-align:left;"> $SPY i can hold out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:29:09 </td>
   <td style="text-align:left;"> $SPY yikes not looking good for bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:29:04 </td>
   <td style="text-align:left;"> $SPY Bulls saying where is the war are just asking for it… Already no war yet, Yet future’s ripppping down becareful wat u ask for 🤦🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:28:52 </td>
   <td style="text-align:left;"> $SPY need this next time i want to buy calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:28:39 </td>
   <td style="text-align:left;"> $SPY Sleepy creepy Joe is no match for Putin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:28:09 </td>
   <td style="text-align:left;"> $SPY $QQQ 🤡⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:27:59 </td>
   <td style="text-align:left;"> $SPY Let’s just open at $415? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:27:58 </td>
   <td style="text-align:left;"> $SPY all ponzis come to an end, usually with all the ponzi profits wiped out.  Hedge down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:27:57 </td>
   <td style="text-align:left;"> $SPY Buy  @  
 
Spx 500/  4280 
Nsdq 100 /13750 
 
Happy Trading. 😍🤞🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:27:55 </td>
   <td style="text-align:left;"> $SPY WHERE IS THE WAR, MORONS!!!??? WHERE IS IT???   WHERE     IS      THE     WAR!!!?????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:27:13 </td>
   <td style="text-align:left;"> $SPY Lovely futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:26:47 </td>
   <td style="text-align:left;"> $SPY Extremely bullish seeing so many retail 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:26:41 </td>
   <td style="text-align:left;"> $SPY  It&amp;#39;s so simple when the fed prints it goes up when the fed stops printing it goes down ignore everything else. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:26:35 </td>
   <td style="text-align:left;"> $SPY I officially hate 3 day weekends lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:26:29 </td>
   <td style="text-align:left;"> $SPY how is there earnings tomorrow? Markets closed 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:26:23 </td>
   <td style="text-align:left;"> $SPY I hate every single person that calls themselves a “citizen of the world”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:26:22 </td>
   <td style="text-align:left;"> $SPY very scary red candles showing up 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:26:19 </td>
   <td style="text-align:left;"> $SPY 420 breaks this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:26:11 </td>
   <td style="text-align:left;"> Time in the market not timing the market $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:26:08 </td>
   <td style="text-align:left;"> $SPY I’m all in on tech puts. OPEN THE CASINOOOOOO  🎰🎲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:26:04 </td>
   <td style="text-align:left;"> $SPY https://divergemedia.ca/2020/11/23/great-reset-has-almost-all-political-parties-working-together-canada/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:25:52 </td>
   <td style="text-align:left;"> $SPY honestly if you didn&amp;#39;t buy puts on Friday, or at all in the last 2 weeks, you need to quit and close your brokerage account. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:25:47 </td>
   <td style="text-align:left;"> $SPY If the tensions in Ukraine weren’t blamed for the bearishness then we still have rate hikes and inflation. You just can’t have a market keep running when people don’t have as much money to buy products and invest in stocks at the same rate. Remember, if sales were fantastic last year because people had stimulus/unemployment money and companies somehow manage to match those sales in the current economy that will be an earnings miss because there is no growth. Expect bearishness throughout the rate hikes for the next couple years, but that’s not a bad thing unless you’re retired or retiring soon. Everyone else will have a chance to add to their best positions at a good price and day/swing traders have a lot of volatility to play with. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:25:41 </td>
   <td style="text-align:left;"> $SPY $TQQQ $BABA $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:25:40 </td>
   <td style="text-align:left;"> $SPY War in Ukraine after Olympics are over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:25:32 </td>
   <td style="text-align:left;"> $SPY HELLO! The Market is closed tomorrow. 

Please don’t be that guy that posts “Halted?”. 

It has been done a billion times. Pls don’t. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:25:24 </td>
   <td style="text-align:left;"> $SPY Bears hoping for war and casualties, so your puts will print 
🤩📈👏🏻

My god you should look yourself in the mirror, and pray for karma. Trading and investing set aside: I have no respect whatsoever for each and everyone of you. 

Absolutely disgraceful. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:25:22 </td>
   <td style="text-align:left;"> $SPY market is closed tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:25:18 </td>
   <td style="text-align:left;"> $SPY the beauty of this is that very few understand everything that can unravel (either way) in 36 hours.
Let’s all take a break from blasting each other tomorrow (until 20:00)
GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:25:15 </td>
   <td style="text-align:left;"> $SPY Putin loaded up on calls on the dip you fools. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:25:11 </td>
   <td style="text-align:left;"> $SPY tensions high world wide 

https://www.businessinsider.com/australia-calls-china-reckless-for-pointing-laser-at-its-military-jet-2022-2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:25:01 </td>
   <td style="text-align:left;"> $SPY 🩸🩸🩸🩸

https://www.cnbc.com/2022/02/21/asia-markets-russia-ukraine-tensions-china-loan-prime-rate-currencies-oil.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:24:53 </td>
   <td style="text-align:left;"> $SPY  a gallon of milk $37 soon 
Very bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:24:43 </td>
   <td style="text-align:left;"> $SPY Rip your face rally inbound, always does, when everyone thinks it will keep  dropping 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:24:36 </td>
   <td style="text-align:left;"> $SPY japan down 2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:24:12 </td>
   <td style="text-align:left;"> $SPY  
WATCH Putin is going be like Papa Doc In 8TH MILE. The last second he’s going to back out LOL  
  
B rabbit all day  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:24:08 </td>
   <td style="text-align:left;"> $SPY Fellas... market not open tommorrow unless you are trading future this is pointless...till tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:23:57 </td>
   <td style="text-align:left;"> $SPY how’s futes looking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:23:56 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s 2:24am in Ukraine. Is war 9-5 M-F only </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:23:41 </td>
   <td style="text-align:left;"> $SPY bulls deserve this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:23:26 </td>
   <td style="text-align:left;"> Checking out the $SPY board to see &amp;quot;futes ripping&amp;quot; check said futes and down half a percent.

Never change StockTwits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:22:52 </td>
   <td style="text-align:left;"> $SPY resource for you

https://miningdataonline.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:22:50 </td>
   <td style="text-align:left;"> $SPY I suggest everyone watch CBS right now. &amp;quot;Targeting Americans&amp;quot; story. Extremely important and part of a bigger picture. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:22:09 </td>
   <td style="text-align:left;"> $SPY Bear’s winning this coming week just accept it… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:22:07 </td>
   <td style="text-align:left;"> $SPY $QQQ 
I&amp;#39;ve never thought I would have to start blocking Bulls. I always blocked Bears but it seems to be the reverse now where Bulls are trolling the forum and not the Bears anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:22:06 </td>
   <td style="text-align:left;"> $SPY It&amp;#39;s about rates....not war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:22:06 </td>
   <td style="text-align:left;"> $SPY Asian markets in disarray 🚨🚨🚨 Prepping my body for the limit down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:22:05 </td>
   <td style="text-align:left;"> $SPY How bout the futes bulls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:22:03 </td>
   <td style="text-align:left;"> $SPY I think most bulls realize by now that even if Russia withdrew their forces … Biden would say there’s an attack planned imminently 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:22:00 </td>
   <td style="text-align:left;"> $SPY 4297.5 is key 
Lets see if it gets by Tuesday. 1/28 low </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:21:47 </td>
   <td style="text-align:left;"> $SPY MARKETS IN TURMOIL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:21:46 </td>
   <td style="text-align:left;"> $SPY Well I mean futes aren&amp;#39;t even down much. Pretty much flat. It&amp;#39;s almost as if this is priced in already... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:21:34 </td>
   <td style="text-align:left;"> $SPY $QQQ Nice! Futures are already crashing more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:21:25 </td>
   <td style="text-align:left;"> $SPY Too many are retiring, demographics no longer favorable to Modern Monetary Theory, labor inflation, systemic, too few producers…At a point it was destined to fail </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:21:07 </td>
   <td style="text-align:left;"> $SPY anyone want to bet that we open green on Tuesday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:20:42 </td>
   <td style="text-align:left;"> $SPY Wen Lambo? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:19:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA ”US Intelligence” is an oxymoron. There’s no such thing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:19:14 </td>
   <td style="text-align:left;"> $SPY potato </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:19:05 </td>
   <td style="text-align:left;"> $SPY Its better they close market for few days until we know what really happens, once there is really a war it can react, but this useless reaction for nothing is not good, there is karma, all those media and politicians who are playing games definately get a big lesson from god. They are super rich but will get diseases that are not cured with money. Macron is assuring that Putin will be convinced and so far everything looks on diplomacy and no war, he conveyed this message to Biden, but Biden don’t talk about it nor the media. But the truth comes out definitely, let them play games but macron announces to the world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:18:49 </td>
   <td style="text-align:left;"> $SPY only 1/3 of my account in play right now and it expires all the way to Friday. Should’ve went all in for Tuesday 🤦🏼‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:18:39 </td>
   <td style="text-align:left;"> $SPY     stockmaster.in/gold.html  
 
$1906.00  / Per ounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:18:29 </td>
   <td style="text-align:left;"> $SPY FUTURE RIPPING!  NO WARS .  PUTIN WILL GET WHAT HE WANT WITHOUT NEEDING TO INVADE UKRAINE. SORRY BEARS!  YOU GUYS ROOTING FOR WARS ARE WORSE THAN THE TRAITORS THAT STAGED THE FAIL COUP ON 1/6!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:18:13 </td>
   <td style="text-align:left;"> $SPY bulls shitting bricks rn💀Tuesday will be very red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:18:12 </td>
   <td style="text-align:left;"> $SPY Why have I never gotten into futures.. easy easy money rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:18:11 </td>
   <td style="text-align:left;"> $SPY Tech is about to get absolutely butchered. It&amp;#39;s so 2020, 2021. 
 
It&amp;#39;s now 2022 which means OIL &amp;amp; Consumer staples will be where the boom is. If you are smart, sell tech and pivot into safe hedges. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:18:07 </td>
   <td style="text-align:left;"> $SPY Steel War Pennies and unchanged interest if there is a war.... that&amp;#39;s bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:17:52 </td>
   <td style="text-align:left;"> $SPY biden everyday the Russians are coming the Russians are coming any day now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:17:47 </td>
   <td style="text-align:left;"> $SPY  
 
Futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:17:46 </td>
   <td style="text-align:left;"> $SPY 

S.H.I.T… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:17:40 </td>
   <td style="text-align:left;"> $SPY $QQQ Sheeeesh! 📉📉📉📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:17:17 </td>
   <td style="text-align:left;"> $SPY $SPX $TLT $QQQ Watch As Macrostrategist David Hunter discusses the MASSIVE Global Economic Bust Coming!👇

WATCH NOW: https://youtu.be/T2iIidHU2s0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:16:52 </td>
   <td style="text-align:left;"> $SPY Bulls were all cocky this morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:16:26 </td>
   <td style="text-align:left;"> $SPY negative interest rates bullish..? 
when was last time we had them? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:16:26 </td>
   <td style="text-align:left;"> $SPY bears are rooting for wars?  you know russia can nuke the hell out of america and we all die right!?  $M $GOOG $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:16:23 </td>
   <td style="text-align:left;"> $SPY futes crippin 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:16:06 </td>
   <td style="text-align:left;"> $SPY Russian troops should just put on BLM T-shirt’s. That way they could invade Ukraine and the Biden administration would have to call it a “peaceful protest”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:16:03 </td>
   <td style="text-align:left;"> $SPY market closed tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:16:02 </td>
   <td style="text-align:left;"> $SPY if the market dips below 420 again the real panic begins.  we will see limit downs again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:15:41 </td>
   <td style="text-align:left;"> $SPY why is Yellen at the national security meeting regarding Ukraine? 

Brrrr needed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:15:35 </td>
   <td style="text-align:left;"> $SPY It’s so f meaningless drawing any conclusion from futee until market opens at 9:30 futee ripping comments as retarded as 🐻 playing cocky now 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:15:33 </td>
   <td style="text-align:left;"> $SPY hammer!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:15:30 </td>
   <td style="text-align:left;"> $SPY puts are golden.  Shit president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:15:27 </td>
   <td style="text-align:left;"> $SPY yikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:15:27 </td>
   <td style="text-align:left;"> $SPY holy futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:15:22 </td>
   <td style="text-align:left;"> $SPY I bought .7.   440 calls Friday with 28 strike price do I have a chance? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:15:21 </td>
   <td style="text-align:left;"> $SPY so many indian tech call scammers on here. Guess times are tough and they needed to downgrade to posting fud. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:15:13 </td>
   <td style="text-align:left;"> $SPY bears are rooting for wars?  you know russia can nuke the hell out of america and we all die right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:15:10 </td>
   <td style="text-align:left;"> $SPY yes bears that 2% is you 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:15:04 </td>
   <td style="text-align:left;"> $SPY why the drop? Any news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:14:50 </td>
   <td style="text-align:left;"> $SPY my VXX calls are sooooo happy right now! Excited for elevator down! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:14:49 </td>
   <td style="text-align:left;"> $SPY Part 1/2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:14:38 </td>
   <td style="text-align:left;"> $FB $SPY ok, time to address the elephant in the room,, are we all going back to MySpace now or what!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:14:29 </td>
   <td style="text-align:left;"> $SPY ITS OVER BEARS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:14:28 </td>
   <td style="text-align:left;"> $BTC.X $SPY $UVXY this is what you call financial oppression and enslavement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:14:27 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:14:26 </td>
   <td style="text-align:left;"> $SPY still to early </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:14:24 </td>
   <td style="text-align:left;"> $SPY you cannot trade both ways 98% accuracy 
I don’t gamble for a living sorry !!🤷🏿‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:14:11 </td>
   <td style="text-align:left;"> $spy $BTC  wooahh Putin speaks fucking English https://youtu.be/LambJJYiJbc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:14:07 </td>
   <td style="text-align:left;"> $SPY haha futures are flat as fk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:14:03 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:13:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA futures open lower this evening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:13:38 </td>
   <td style="text-align:left;"> $SPY is headed for a death cross.  Very well could lead to the next prolonged bear market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:13:25 </td>
   <td style="text-align:left;"> $SPY you bunch of SPOILED BRATS! None of you have traded through anything but the longest running bull market in history and you are all about to understand the bear! Enjoy your losses! I Trade to make money folks! Im a bull when it’s time and a bear when it’s time and right now y’all are giving out easy money! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:13:15 </td>
   <td style="text-align:left;"> $SPY my 440 calls are not going to print Tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:13:13 </td>
   <td style="text-align:left;"> $SPY bulls sleeping well? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:59 </td>
   <td style="text-align:left;"> $SPY negative interest rates are the only way to save us. I think. Actually I don’t know😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:48 </td>
   <td style="text-align:left;"> $SPY futures nice and red :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:45 </td>
   <td style="text-align:left;"> $SPY I don&amp;#39;t think you guys are understanding what you are seeing... spy futes is down by -21... its always down -20 + 20, it&amp;#39;s not alot for the big money to change it. They sold because they don&amp;#39;t want to risk that money if ukraine gets invaded. It&amp;#39;s just a fake drop. If it does invade then expect it to drop. But if it doesn&amp;#39;t this will blow up... so stop staring at futes and hope innocent people don&amp;#39;t die. Please. I am bullish because I want to wish for the best :/ Once the decision is out, you will see an instant +/- 100. So don&amp;#39;t count your chickens before they hatch. It just leads to disappointment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:44 </td>
   <td style="text-align:left;"> $SPY some of the trash here hate Biden more than putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:41 </td>
   <td style="text-align:left;"> $SPY FUD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:39 </td>
   <td style="text-align:left;"> $SPY buy it now big </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:39 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:30 </td>
   <td style="text-align:left;"> $SPY Investors RN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:25 </td>
   <td style="text-align:left;"> $SPY no more dead cat bounce? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:20 </td>
   <td style="text-align:left;"> $SPY gap up and higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:14 </td>
   <td style="text-align:left;"> $SPY what time is meeting with Putin? If 9am only 7 hours away. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $AAPL  
 
Wait until big apple falls, then QQQ will accelerate its drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:12:03 </td>
   <td style="text-align:left;"> $SPY wen spy reaches 390 and below thats wen i load up… cant be a bull right now.. Must be bearish play both sides make $$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:11:58 </td>
   <td style="text-align:left;"> $SPY 420 Tuesday, 415 Wed, 406 Thursday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:11:57 </td>
   <td style="text-align:left;"> $SPY haven’t seen the lows on futes yet 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:11:48 </td>
   <td style="text-align:left;"> $SPY all the stocks that have lost 50-80% in the last few months while the indices are still in nosebleed, crazy times </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:11:43 </td>
   <td style="text-align:left;"> $SPY All Biden has to do is restore Trump sanction on Russian pipeline to UK and restore XL Pipeline from Canada.   That will crash $USO $WTI and inflation will be under control within months as underlying transportation and material costs drop overall production costs.  $uvxy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:11:35 </td>
   <td style="text-align:left;"> $SPY Why the hell market is dumping ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:11:25 </td>
   <td style="text-align:left;"> $SPY we are going back to 420 probably a tad below to suck in the 400 put buyers and there will be a relief rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:11:23 </td>
   <td style="text-align:left;"> $SPY listen, Macron and Putin are talking tomorrow. They both agreed on a cease fire and a Normandy format meeting this week w/ Russia, Germany, France, and Ukraine involved. Point of the meeting to try and negotiate de escalation. Putin will accept nothing less than Ukraine agreeing to stay out of NATO. But the situation has intensified to such an extreme that Ukraine may just agree at this point. They need to, as Russia will bowl them over regardless. Putin would rather not go to war because the sanctions would be terrible for Russia, but more than willing to if Ukraine doesn’t play ball. We’ll see what transpires in the next couple days. Just one guy’s opinion... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:11:20 </td>
   <td style="text-align:left;"> $SPY Nikkei down 2% so far… Tuesday will be interesting. Blood bath. The 427 puts gonna be huge pay day for us </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:11:20 </td>
   <td style="text-align:left;"> $SPY What’s stopping Putin from calling Biden’s bluff? He’s got 200K troops locked and loaded. He could take Ukraine in a day then take the next county and the next… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:11:01 </td>
   <td style="text-align:left;"> $SPY what are futures doing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:10:47 </td>
   <td style="text-align:left;"> $SPY hahahahaha oh man, Tuesday is going to be beautiful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:10:33 </td>
   <td style="text-align:left;"> $SPY seems like Putin&amp;#39;s play is to instigate and provoke Nato, Ukraine and get Ukraine to make a move on Russia. Then say he&amp;#39;s defending the Russian federation. Will it happen? My guess is 75% yes 25% no. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:10:32 </td>
   <td style="text-align:left;"> $SPY $GOOGL $FB Around October and January we visited these lows. Next few weeks I think we make a run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:10:20 </td>
   <td style="text-align:left;"> $SPY Gold past $1905.00 / ounce 
 
Spy is red ink big time folks. Tuesday will be epic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:09:55 </td>
   <td style="text-align:left;"> $SPY lets see if futures hold till Tuesday🤞🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:09:49 </td>
   <td style="text-align:left;"> $SPY 445 open possible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:09:37 </td>
   <td style="text-align:left;"> $SPY “buy the dip” for a about a month now. how’s it going bulls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:09:29 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:09:25 </td>
   <td style="text-align:left;"> $SPY started a position in: $MNQ_F, $MES_F, and $ETH.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:09:24 </td>
   <td style="text-align:left;"> $SPY Bring the house of cards down to the ground waiting for 400 and I will load with my eyes closed any name with positive earnings in the tech sector preferable small cap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:09:16 </td>
   <td style="text-align:left;"> $SPY what hat hackers and black hat hackers all love the fbi  because the fbi stand for TRUTH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:09:14 </td>
   <td style="text-align:left;"> $SPY $GOLD makes you wonder how this war story came out exactly the time of the correction of the us markets and the breakout in gold 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:09:01 </td>
   <td style="text-align:left;"> $SPY Biden shall kneel to me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:08:44 </td>
   <td style="text-align:left;"> $SPY 420 eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:08:07 </td>
   <td style="text-align:left;"> $SPY Putin is the leader of the world.  Biden sure is acting very afraid.  $uvxy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:07:57 </td>
   <td style="text-align:left;"> Rootin&amp;#39; Tootin&amp;#39; Putin&amp;#39;????  Too funny! 
 
 
Yeah, well when all the Ukraine invasion frenzy is over, we will deal with a sobering $SPY in the $415- $425 area. 
 
We cannot avoid the selling that is taking place every day in our US markets. Putin matters not. A distraction but there are millions to be made in the oil pits due the media mania so why not bet heavy on the extreme moves.  Banque ahead! 
 
It is the extreme moves that are needed in the option pits. 
 
Enjoy! 
 
 
$QQQ   a short&amp;#39;s dream in 22&amp;#39;.  $$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:07:49 </td>
   <td style="text-align:left;"> $LMND who would’ve thought this would tank from $153 down to $20s..amazing $SPY $UVXY now that’s what you call smart money abandoning ship </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:07:41 </td>
   <td style="text-align:left;"> $SPY If Russia invades Ukraine, you can bet your ass it&amp;#39;ll crash harder than the covid crash.  In fact, everything since that crash until now will look like one GIANT bull trap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:07:37 </td>
   <td style="text-align:left;"> $SPY 4280💯💯💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:07:31 </td>
   <td style="text-align:left;"> $SPY 🤣🤣

https://www.tiktok.com/@andrei_adam94_romania/video/7066019719060458757?improve_sharing_social=v1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:07:27 </td>
   <td style="text-align:left;"> $SPY Evacuate!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:07:23 </td>
   <td style="text-align:left;"> $SPY @KansasCash 
150,000 bears stationed on the border of Stocktwitistan with their fingers poised on the put button…….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:07:10 </td>
   <td style="text-align:left;"> $SPY Puts.!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:07:05 </td>
   <td style="text-align:left;"> $SPY Central banks will pause rate hikes! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:06:55 </td>
   <td style="text-align:left;"> $SPY USA will fk Mexico next week 🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:06:46 </td>
   <td style="text-align:left;"> $BTC.X Buttcoin follows Indexes, better off saving $38,000 and just buy one $SPY share! Or 100! 🩸 🦟  💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:06:38 </td>
   <td style="text-align:left;"> $SPY 4300 is an important level , it must hold and I think it will but idk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:06:34 </td>
   <td style="text-align:left;"> $SPY usa will take Mexico next week 🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:06:31 </td>
   <td style="text-align:left;"> $SPY 🚬🚬🔥

Can&amp;#39;t believe I&amp;#39;m banking on Macron to rub Putin&amp;#39;s dick to save my CALLS. 😏😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:06:25 </td>
   <td style="text-align:left;"> $SPY “every war has a silverlining”…
Marko Kolanovic (JPMorgan) is bullish again: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:06:13 </td>
   <td style="text-align:left;"> $SPY For 74 years Progressive university professors, Artists, Hollywood and Liberal democrat politicians have been sucking off Karl Marx, Leon Trotsky￼, and Lenin’s Bolshevik Revolution! Now all of a sudden the progressive elitist democrats have become Operation Barbarosa￼…Mein Fuhrer￼!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-21 08:05:55 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s happening sad but it&amp;#39;s happening I wonder if sometime next week China does same with Taiwan...... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:45:09 </td>
   <td style="text-align:left;"> $QQQ Like the IWM, in the cloud now and the bearish force is strong there.  Flat cloud bottom is the magnet (lower blue line).  Might break below this week. $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:43:33 </td>
   <td style="text-align:left;"> $QQQ this will be blue tomorrow after UK markets open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:42:22 </td>
   <td style="text-align:left;"> $QQQ From a purely technical standpoint, how often are futures gaps left open? Seems like from past experience they close at some point fairly quickly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:42:07 </td>
   <td style="text-align:left;"> $SPY  $QQQ 

Are we open tomorrow?

Or we don’t celebrate this Presidents’ Day specially because of Brandon ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:40:51 </td>
   <td style="text-align:left;"> $QQQ $BABA $AMZN ,, Earnings reports today before the markets open&amp;quot;  amazingroom.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:40:45 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
FED has lost control of the printer! 
 
They can&amp;#39;t turn it off!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:40:39 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.cnbc.com/2022/02/20/biden-abruptly-cancels-delaware-trip-after-top-level-calls-on-ukraine.html 
 
Exactly what a great leader should do during the unusual situation, if it were Trump he would be golfing on the golf courses right now 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:40:32 </td>
   <td style="text-align:left;"> $FB $SPY $QQQ all this bitching and whining about inflation and Russia-Ukraine and collapse. But really this is like 1992 and metaverse will change the world much like the internet did. OHHHHHHHH!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:39:24 </td>
   <td style="text-align:left;"> $qqq 3 weeks of red to the first strike of Russia in 2014.  Then massive bull rally after first strike.  Hurry up Putin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:37:28 </td>
   <td style="text-align:left;"> $QQQ everything &amp;quot;priced in&amp;quot; and still dropping. So I guess that logic wasn&amp;#39;t true 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:37:00 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
of course! 
 
you still printing BILLIONS, right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:36:30 </td>
   <td style="text-align:left;"> $QQQ happy Presidents’ Day to my president! $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:32:36 </td>
   <td style="text-align:left;"> $QQQ Give it up for now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:31:38 </td>
   <td style="text-align:left;"> $SPY $QQQ  $VTI  the drop any newsboys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:31:17 </td>
   <td style="text-align:left;"> $QQQ $SPY $SQQQ  putin slaughtering bulls this week and trumpies are going to blame brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:30:36 </td>
   <td style="text-align:left;"> $QQQ happy Presidents’ Day comrades. Trump is Hitler or whatever the hell you chumps believed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:30:02 </td>
   <td style="text-align:left;"> $SPY  and $QQQ in peril for months. 
 
Losing Monday as a trading day is so nasty and we will all be lucky if we are not falling into the 420&amp;#39;s while the Holiday is celebrated and other markets implode. 
 
We must pray for stability into the Tuesday open. If you are religious...start praying soon.  If you fail, you may need to reassess the power of your faith and act accordingly. 
 
This is not good at all. Many will not escape the carnage. 
 
Nasty days ahead!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:28:09 </td>
   <td style="text-align:left;"> $SPY $QQQ 🤡⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:26:46 </td>
   <td style="text-align:left;"> $QQQ Sorry bears, the market opens Tuesday.  Another full day for Macron to secure his peace plan, outmanouvering Biden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:24:43 </td>
   <td style="text-align:left;"> $QQQ Future Buy 13750 they will go for it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:23:03 </td>
   <td style="text-align:left;"> $QQQ kinda feels like we gon get f’d real bad this wk.  btfd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:22:07 </td>
   <td style="text-align:left;"> $SPY $QQQ 
I&amp;#39;ve never thought I would have to start blocking Bulls. I always blocked Bears but it seems to be the reverse now where Bulls are trolling the forum and not the Bears anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:21:34 </td>
   <td style="text-align:left;"> $SPY $QQQ Nice! Futures are already crashing more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:21:02 </td>
   <td style="text-align:left;"> $QQQ Lol it only took a virus, inflation, a recession, and a fucking war for the market to be a bear market!!! Congrats bears!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:21:00 </td>
   <td style="text-align:left;"> $UVXY $qqq $SAVA $TSLA This is the reality of the market. &amp;quot;Indexes&amp;quot; are like a bunch of lottery winners put together and advertised as what you can expect playing the lottery any given day. Basically what scammers do making everyone feel like a millionaire except you have to pay a tiny little &amp;quot;fee&amp;quot;. The reality of steal street is 99% of all stocks since 1926 went to 0... The reality is for every winner in the stock market there are hundreds of losers and odds are you are one of them... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:19:51 </td>
   <td style="text-align:left;"> $QQQ That moment when people realize that the market is closed tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:19:37 </td>
   <td style="text-align:left;"> $QQQ isn’t the market close tomorrow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:19:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA ”US Intelligence” is an oxymoron. There’s no such thing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:17:40 </td>
   <td style="text-align:left;"> $SPY $QQQ Sheeeesh! 📉📉📉📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:17:17 </td>
   <td style="text-align:left;"> $SPY $SPX $TLT $QQQ Watch As Macrostrategist David Hunter discusses the MASSIVE Global Economic Bust Coming!👇

WATCH NOW: https://youtu.be/T2iIidHU2s0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:15:53 </td>
   <td style="text-align:left;"> $QQQ our money we play how we like why you getting rude with people.  Wa×××× </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:15:39 </td>
   <td style="text-align:left;"> $QQQ your calls are f@%%#^ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:15:34 </td>
   <td style="text-align:left;"> $QQQ 
Long end of note/bond market flattening- 10yr and 30yr being bought. Fed can’t raise too aggressively or the curve will invert. 
Geopolitical situation causing flight to safety.  Yes rates are going up, but more important is the velocity of the credit market moves. The flight to safety may act as a dampener to this velocity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:15:33 </td>
   <td style="text-align:left;"> $QQQ guys what time are futures open till today? Anyone know. Don&amp;#39;t really trade them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:14:42 </td>
   <td style="text-align:left;"> $QQQ why you being rude ass hole </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:13:58 </td>
   <td style="text-align:left;"> $QQQ keep buying the dip retards! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:13:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA futures open lower this evening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:12:25 </td>
   <td style="text-align:left;"> $QQQ my 355 calls are not going to print Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:12:24 </td>
   <td style="text-align:left;"> $QQQ the real bleeding BEGINS tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:12:20 </td>
   <td style="text-align:left;"> $QQQ am long and holding it will bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:12:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $AAPL  
 
Wait until big apple falls, then QQQ will accelerate its drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:10:12 </td>
   <td style="text-align:left;"> $QQQ @HungryMoney inlonged futures should I take a loss I’m down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:09:29 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:08:22 </td>
   <td style="text-align:left;"> $QQQ Macron just took a huge dump on Biden&amp;#39;s fake war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:07:57 </td>
   <td style="text-align:left;"> Rootin&amp;#39; Tootin&amp;#39; Putin&amp;#39;????  Too funny! 
 
 
Yeah, well when all the Ukraine invasion frenzy is over, we will deal with a sobering $SPY in the $415- $425 area. 
 
We cannot avoid the selling that is taking place every day in our US markets. Putin matters not. A distraction but there are millions to be made in the oil pits due the media mania so why not bet heavy on the extreme moves.  Banque ahead! 
 
It is the extreme moves that are needed in the option pits. 
 
Enjoy! 
 
 
$QQQ   a short&amp;#39;s dream in 22&amp;#39;.  $$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:07:18 </td>
   <td style="text-align:left;"> $QQQ good earnings dont matter in 2022 rip nasdaq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:06:06 </td>
   <td style="text-align:left;"> $QQQ going to start buying soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:05:01 </td>
   <td style="text-align:left;"> $SPY $QQQ both are going to plunge by Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:02:58 </td>
   <td style="text-align:left;"> $QQQ thanks dems </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:02:34 </td>
   <td style="text-align:left;"> $SPY $QQQ right on track. Still holding March puts on qqq since two weeks ago almost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:02:06 </td>
   <td style="text-align:left;"> $SQQQ $QQQ $TQQQ  Nasdaq very weak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 08:00:53 </td>
   <td style="text-align:left;"> $QQQ buy as it dips, sell as it rips how hard is that $SPY $IWD $IWF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:59:24 </td>
   <td style="text-align:left;"> Two Days Of Selling Threaten The January Lows $QQQ $IWM $SPX https://talkmarkets.com/content/stocks--equities/two-days-of-selling-threaten-the-january-lows?post=345457 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:59:06 </td>
   <td style="text-align:left;"> $QQQ Futes are wedging downwards....some reprieve soonish... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:58:22 </td>
   <td style="text-align:left;"> $QQQ Biden is Soros puppet they know  if the market is smoked elections go the other way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:58:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM $SOX You don’t need to be a futures trader to foresee what will happen when markets open. Global markets move on news and it can be seen in the advancement or the decline in the index futures as stocks trade around the world. European and China’s Hang Seng markets will be a good gauge at their close tomorrow to see weather the U.S. indices gap up or down on Tuesday … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:56:41 </td>
   <td style="text-align:left;"> $QQQ Seems like a long night for call holders....all on a lie by Fraud in Chief </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:55:03 </td>
   <td style="text-align:left;"> $QQQ futes ripin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:53:17 </td>
   <td style="text-align:left;"> $QQQ $SPY wow im seeing a lot of excuses from bulls. Where are all the futes ripping comments? All of a sudden I see futes don’t matter comments from the bulls 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:53:16 </td>
   <td style="text-align:left;"> $QQQ 1 year low coming soon, and then 5 year low hopefully </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:51:06 </td>
   <td style="text-align:left;"> $QQQ green Tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:50:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $QQQ 

Unfortunately all the news since my full scale invasion prediction yesterday has made it increasingly more likely.

All my posts related to the conflict are sourced with references to the last in each one, so feel free to crawl through them for additional recent developments.

1A. Russia withdrew it&amp;#39;s debunked claim of a withdrawal and has actually increased its presence, as US/NATO already confirmed.
1B. Ukrainian intelligence believes Russian forces are now fully mobilized for an attack, coinciding with previous US intelligence.
2A. Emergency meeting of National Security Council lasted two hours and left no comment.
2B. Biden abruptly canceled his planned trip to his home in Delaware immediately following the meeting.
3. Intelligence from US acknowledged Putin has ordered final preparations for a full scale war.

https://stocktwits.com/Fundy_OracleOfAlpha/message/437870327

1: https://bit.ly/34N6QVf
2: https://cnb.cx/3s2j9Wb
3: https://bit.ly/3gYOMK3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:48:46 </td>
   <td style="text-align:left;"> $QQQ chart falling knife, but thats bullish
 $SPY chart falling knife, but thats bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:48:09 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:47:42 </td>
   <td style="text-align:left;"> $QQQ  
 
Buy future 13750. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:46:30 </td>
   <td style="text-align:left;"> $QQQ is this going to pre pandemic levels or wut? 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:45:20 </td>
   <td style="text-align:left;"> $SPY $QQQ look at nas futures. Despite the red days, the money supply has been increasing. This is a leading indicator. Gives a better idea where the market is heading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:44:41 </td>
   <td style="text-align:left;"> $QQQ scared ass mofos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:43:35 </td>
   <td style="text-align:left;"> $SPY $QQQ was expecting more red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:43:13 </td>
   <td style="text-align:left;"> $QQQ futures up 3% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:42:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM $SPX  nasdaq has been in a correction for 84 days and a correction lasts 90 days . I most likely will be switching to short for this week as I think it’ll be the bloodiest we’ve seen . According to my calendar Friday feb 25th will be a -5% day and next week I will most likely be bullish again as I believe the correction will be coming to an end. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:42:31 </td>
   <td style="text-align:left;"> $QQQ $IWM $SPY  
 
Futures are typically meaningless to us but are folks seeing the same thing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:42:15 </td>
   <td style="text-align:left;"> $SPY Remember that SP futures only traded to 5pm EST on Friday. The market went down further when AH closed (use the $QQQ for example).. We are now about where we closed at that time... nothing to speak of moving markets so far. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:41:50 </td>
   <td style="text-align:left;"> $QQQ 
War: repricing continues.
No war: repricing continues. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:40:13 </td>
   <td style="text-align:left;"> $QQQ at what point do you load up on $TQQ? QQQ at sub 300? Sub 250? Sub 200? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:40:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA 
so what is there to be bullish with everything going on in our economy and the rest of the world? answer that?
i can give you many reasons why i am bearish NOW.
but why bullish NOW? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:38:50 </td>
   <td style="text-align:left;"> $QQQ $HOOD $SPY $IWM  
Missed the initial move?  NEVER chase.  WAIT for the next A+ entry to set up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:38:30 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ   
 
Bears 🤡 excited for that 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:36:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $DOW Night everyone! Sweet dreams :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:35:25 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:35:01 </td>
   <td style="text-align:left;"> $QQQ Fucking Biden pushing g futures down. Lock him up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:34:04 </td>
   <td style="text-align:left;"> #nq It&amp;#39;s 12am, the holiday continues due to the president&amp;#39;s day and I thought, &amp;quot;make a video before you crash&amp;quot;. Yup, I marked some levels on my chart as you can see. 
These are levels I&amp;#39;m looking at. The Nasdaq100 is currently at the end of both the daily and hour 4 channels and I don&amp;#39;t know what this means for the bulls. Two possible scenarios involves the market creating support and a possible divergence while bringing the bulls backs or it breaks and resistance is created whilst going for the 13k mark. 
What&amp;#39;s it going to be? Huh.. 
Levels: 
Toc-14700 
Moc-14300 
Eoc-14000 
Again, Happy president&amp;#39;s day. $NDX $QQQ  
Link: https://www.tradingview.com/chart/NAS100USD/hnnFiGxR-Ndx-Happy-President-s-Day/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:33:48 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM  
 
We might be looking at 320s on the Qs this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:33:00 </td>
   <td style="text-align:left;"> $QQQ has a bad technical rating, but it does show a decent setup pattern. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:32:52 </td>
   <td style="text-align:left;"> $QQQ I’m surprised the futures markets are trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:30:52 </td>
   <td style="text-align:left;"> $SPY $QQQ here we go with all the Tuesday morning predictions and bull vs. bear drama. Ya&amp;#39;ll gonna do this for the next day and a half? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:29:03 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DJIA    
 
           &amp;gt;&amp;gt; Bears will be FRIED by Tues  &amp;lt;&amp;lt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:27:49 </td>
   <td style="text-align:left;"> $QQQ UK Market is going up every thing will follow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:27:23 </td>
   <td style="text-align:left;"> Excellent,  I love it when a plan comes together as advised to all my friends, followers, haters, those on block for jawboning stupid and Seeking Alpha for not posting many of my bearish posts for profits yet other credible forums do. Thank dog that I am here to help. Carry on shorting the stock markets at large for profits. Rest assured severe stock market crashes in queue.  We ain&amp;#39;t seen nothing yet. 💣💥🐻❤😈✔ https://www.investing.com/indices/indices-futures  $djia $SPX $NDX $spy $qqq 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:21:44 </td>
   <td style="text-align:left;"> $QQQ no war so it should go up   they is no chance of war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:21:31 </td>
   <td style="text-align:left;"> $SPY we will see🤷🏽‍♂️ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:21:16 </td>
   <td style="text-align:left;"> $QQQ $SPY Reasons to be bearish- 1. Fed taper + hikes 2. Bubbles everywhere. Reasons to be bullish- buy the dip 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:20:53 </td>
   <td style="text-align:left;"> $QQQ wooooooow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:19:08 </td>
   <td style="text-align:left;"> $QQQ It’s funny that many HFs are panicking with too many people piling on indexes… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:17:56 </td>
   <td style="text-align:left;"> $QQQ here we go. 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:17:30 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DJIA   OHHHHHH what a huge crash. Futs down 72-20-138 such MASSIVE numbers LOLOLOL   
 
                   Watch it all turn GREEN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:17:06 </td>
   <td style="text-align:left;"> $BTC.X $SPY $ETH.X $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:16:01 </td>
   <td style="text-align:left;"> $QQQ $SPY at -50% people will still be thinking buy the dip 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:15:41 </td>
   <td style="text-align:left;"> $QQQ seems bear trap? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:15:01 </td>
   <td style="text-align:left;"> $QQQ - Is trending retracing? #stocks #earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:14:29 </td>
   <td style="text-align:left;"> Major Index Confirms Bearish Head and Shoulders Pattern! What&amp;#39;s Next!? $QQQ https://www.youtube.com/watch?v=t8ndA8qUAPs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:14:17 </td>
   <td style="text-align:left;"> $QQQ Biden = red futures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:14:09 </td>
   <td style="text-align:left;"> $QQQ Today’s future wouldn’t be consider for the Tuesday opening ….. please correct me if I am wrong 🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:14:05 </td>
   <td style="text-align:left;"> $QQQ $SPY will be such a slow staircase down that you won’t even know it’s a downturn till -40% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:14:02 </td>
   <td style="text-align:left;"> $SPY $QQQ I don’t blame the bears hoping for the rate hikes to tank the market but it is sad to see some of them hoping for war and blood in order for them to make some money and it is not like the money would be enough for them to get rich overnight 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:13:09 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  any folks from Canada can confirm arrival of UN troops to Canada to deal with protests? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:12:42 </td>
   <td style="text-align:left;"> $QQQ futes trippin $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:12:34 </td>
   <td style="text-align:left;"> $SPY world is ending. . Futures drop 1% in 5 minutes. . $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:12:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $WMT $UVXY $AMZN 

Anybody else getting 2011 European Debt Crisis impact deja vu? 

Subtract Debt Crisis and insert Ukraine/Russia and you still have a European Crisis, post a significant 18-20 month global equity rally.

Same tune, different record! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:12:04 </td>
   <td style="text-align:left;"> $SPY I guess I was expecting worse $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:08:35 </td>
   <td style="text-align:left;"> $QQQ Share your thoughts about Invesco  https://www.reddit.com/r/wallstreetfools/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:08:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
Too bad the markets close tomorrow…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:07:09 </td>
   <td style="text-align:left;"> $QQQ the fed hasnt tapered yet because they dont want it to crash lmao, they are letting it bleed slow. come on bulllllls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:05:23 </td>
   <td style="text-align:left;"> $QQQ there they go, big dump on the holiday short sesh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:04:37 </td>
   <td style="text-align:left;"> $QQQ am I blind? Where is the scary part? Just keep buying this discount. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:04:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures slightly lower, not too meaningful though since the US market is closed tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:03:38 </td>
   <td style="text-align:left;"> $QQQ futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:02:41 </td>
   <td style="text-align:left;"> $QQQ It won’t go down all at once.  There is opportunities to catch some short squeezes along the way.  If this truly is a bear market there will be years before it hits its low.  Bears don’t get to win all at once.  I think we see a pump before the next dump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:01:06 </td>
   <td style="text-align:left;"> $QQQ President Poutine on tuesday morning viewing the US stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 07:00:59 </td>
   <td style="text-align:left;"> $QQQ bye bye Bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:57:36 </td>
   <td style="text-align:left;"> $DJIA $SPY $$QQQ have you met my new friends $UVXY $VXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:56:23 </td>
   <td style="text-align:left;"> $QQQ $HOOD $SPY $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:55:19 </td>
   <td style="text-align:left;"> $QQQ when do futes open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:54:34 </td>
   <td style="text-align:left;"> $QQQ best opportunity in a lifetime if this falls another 10% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:54:28 </td>
   <td style="text-align:left;"> $QQQ looks bad cotton </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:54:01 </td>
   <td style="text-align:left;"> $QQQ $NQ_F  weekly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:52:54 </td>
   <td style="text-align:left;"> $QQQ waiting for ww3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:49:10 </td>
   <td style="text-align:left;"> $QQQ $DWAC $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:47:35 </td>
   <td style="text-align:left;"> $SPY $qqq is stocktwits the place where the world’s most uneducated traders gather? Holy crap some of these comments make my brain spaz out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:45:14 </td>
   <td style="text-align:left;"> $AMZN $QQQ $GLD 

Chart is from Larry Williams </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:44:28 </td>
   <td style="text-align:left;"> $TWLO Perspective: $TWLO is a $30B company just like Honda $HMC with the exact same figure which trades at $30 compared to TWLO&amp;#39;s current $158. Given the current inflation/stag/deflation-hedge debacle, pending interest rate hikes, war, etc .. it would suggest that TWLO and many other USA tech stocks have a long way to go ... DOWN $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:43:43 </td>
   <td style="text-align:left;"> $QQQ how gross are futures going to be ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:39:01 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY $SPX ,, More Bearish then Bullish , Sneaky Snake Trading Strategy  https://www.youtube.com/watch?v=jVMLwQP2C-E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:31:54 </td>
   <td style="text-align:left;"> $QQQ  Ukraine should drop a bomb on Russia first, teach them a lesson about being a bully. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:28:24 </td>
   <td style="text-align:left;"> $SPY $QQQ 

youtu.be/Sqz5dbs5zmo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:27:00 </td>
   <td style="text-align:left;"> $SPY $QQQ China‘s Ukrain remarks transpiled: Putin stop pumping oil and inflation in West, as it’s hurting our exports, you piece of shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:23:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $BTC.X 

“What patterns emerge from historical stock market performance during war times?”

It looks like we are still in the “pre-war phase” !?! hehe!
———— </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:23:01 </td>
   <td style="text-align:left;"> $QQQ 
All noise re Ukraine. 
The world will sacrifice Ukraine (sadly). 
This is all about a macro liquidity change. Fortunately, the economy is strong, earnings will continue to grow. Market probably over corrects to the downside, much like it did to the upside. Hedge any trades and also use stops. Risk management at the forefront. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:19:25 </td>
   <td style="text-align:left;"> $SPY $qqq prefuture Futures up 2.8% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:17:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA S&amp;amp;P 500 (SPY) Technical Analysis, Forecast, and Trade Ideas:  
https://www.youtube.com/watch?v=P__byTtxgrY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:17:27 </td>
   <td style="text-align:left;"> $SPY $DIA $IWM $QQQ How do we think futures will open/move? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:13:49 </td>
   <td style="text-align:left;"> $QQQ Death cross crystallizes in Nasdaq Composite on Friday for first time in 2 years, in a bearish sign for the stock market

https://www.marketwatch.com/story/death-cross-crystallizes-in-nasdaq-composite-on-friday-for-first-time-in-2-years-in-a-bearish-sign-for-the-stock-market-11645196858?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:13:32 </td>
   <td style="text-align:left;"> Momentum Monday – Bearish Market Environment https://ivanhoff.com/2022/02/20/momentum-monday-bearish-market-environment/ @MarketSmith @howardlindzon $QQQ $ARKK $EXPE $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:12:39 </td>
   <td style="text-align:left;"> $SPY $QQQ  French president is going to meet Biden to unconditionally surrender before any war starts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:11:57 </td>
   <td style="text-align:left;"> $QQQ All this bud and media crap y’all really do know that if Russia is going to invade they’re not going to announce it it’s just gonna happen it’s like when we were going to find bin Laden we didn’t post on social media hey buddy we’re coming for you tomorrow enough already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:10:23 </td>
   <td style="text-align:left;"> $QQQ This entire crisis should be resolved by a duel to the death between Biden and Putin. The world would win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:08:28 </td>
   <td style="text-align:left;"> $QQQ $SPY if we want a more free market… we need laws that bar politicians from engaging financially in the stock market. It’s as simple as that. 

If someone is willing to be of service to the American people, than they should be willing to forgo certain investment opportunities because of MAJOR conflicts of interest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:08:18 </td>
   <td style="text-align:left;"> $SPY $QQQ lol fuck your puts, lives matter more than money!  We gonna rip up with news of no war and you&amp;#39;ll be fuckdd! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:06:17 </td>
   <td style="text-align:left;"> $SPY $QQQ crazy how people are quick to spread misinformation, industrial complex is hungry! They not getting it russia is smarter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:06:15 </td>
   <td style="text-align:left;"> $QQQ $SPY  “Washington — Russian Ambassador to the United States Anatoly Antonov denied Sunday that the Kremlin is preparing for an invasion of neighboring Ukraine, despite a build-up of roughly 150,000 Russian forces and U.S. intelligence that Russian commanders have received orders to proceed.

&amp;quot;There is no invasion, and there [are] no such plans,&amp;quot; Antonov said in an interview with &amp;quot;Face the Nation.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:05:03 </td>
   <td style="text-align:left;"> $QQQ got a question, can I close a call credit spread before exp if it’s above my lines,? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:04:35 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-02-20 Daily Forecast Video: 
https://www.youtube.com/watch?v=s8O3DHN8jqM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:04:10 </td>
   <td style="text-align:left;"> $QQQ I am not afraid of a war between Russia and Ukraine. I am afraid of Biden, the FED, Powell, Yellen, Bullard and all the inept and irresponsible politicians who are ruining the retirement pensions of many citizens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:04:01 </td>
   <td style="text-align:left;"> $SPY $QQQ I think Russia hasn’t attacked yet because they are trying to prove the US intelligence wrong. Putin wants to attack badly but he is holding off for now and hopefully President Biden can talk Putin out of it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:00:48 </td>
   <td style="text-align:left;"> $QQQ $SPY Tuesday will be reddest of the reddest days. I’m excited lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 06:00:25 </td>
   <td style="text-align:left;"> $QQQ Remember that fear is sometimes irrational and much greater than real preserves. The media and inept Biden are destroying the US stock markets and doing much more damage to the US economy than a war would. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:59:30 </td>
   <td style="text-align:left;"> $SPY $QQQ I think many of you remember Trump calling Putin a great guy and a friend, that’s why Americans made an excellent choice by not to vote for that clown returning to the White House </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:57:02 </td>
   <td style="text-align:left;"> $QQQ A war between Russia and the Ukraine should not have too much of an impact on the US economy. The problem is the media spreading fear and anxiety. That is what tore the market apart last week beyond the real consequences that a war between Russia and Ukraine could have. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:56:21 </td>
   <td style="text-align:left;"> $SPX $SPY $NDX $QQQ https://youtu.be/CIrvSJwwJUE 👺🔥👺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:55:08 </td>
   <td style="text-align:left;"> $AABB $SPX $SPY $QQQ $DJIA AABBG.X 100% decentralized&amp;gt;anonymous&amp;gt;secure. Backed by Gold! https://cryptobriefing.com/kraken-ceo-warns-users-to-get-your-coins-out-of-centralized-exchanges/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:54:24 </td>
   <td style="text-align:left;"> $SPY $QQQ If we see gold going down during the Asian session then it would mean the war fears are slowly going away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:49:42 </td>
   <td style="text-align:left;"> $QQQ +2% move higher Tuesday, mark it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:48:43 </td>
   <td style="text-align:left;"> $QQQ $SPY very different news in Russia -  look up Tass.com to see what is being said in Russian </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:48:04 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DJIA $DIA 

Thank god for the democrats.

If Trump and cronies were still in power at the White House - we’d be smack in the middle of a recession right now. 

Thank god one of the the most cruel and worst leaders in Donald Trump is out after only one term, and Biden is in. 🙏

We are blessed 🇺🇸 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:47:45 </td>
   <td style="text-align:left;"> We may need the bearish sentiment to increase and to last a little while longer to find a truer bottom. 

It was all about the &amp;quot;calls&amp;quot; for 20 months. 
Now, it&amp;#39;s all about the &amp;quot;puts&amp;quot;. 
Lower-highs are evident.
Current $CPC  regime points higher interim

$VIX  $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:47:38 </td>
   <td style="text-align:left;"> $QQQ Putin says diplomacy must intensify and Brandon says he is about to kill everyone in Ukraine, who do we believe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:47:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X 
Also Johnson talking about a de-escalation while yesterday talking about a 1945 style war.

Only Biden, Kamala and Us Media pushing for an “imminent” attack
Their behavior is not constructive 

I think they got to justify something else making these statements at this point 
 
Time will tell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:45:00 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F ⭐️🧞‍♂️⭐️ $QQQ $DIA 

                      Unfortunately for some </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:44:11 </td>
   <td style="text-align:left;"> $SPY  $QQQ $IWM This where  pay the piper and it could potentially unravel. The biggest  buyer now leaves the building (120 billion per month). Who is going to step up and fill that void? The market is now going have to rely on 1)Fundamentals  and 2) Earnings. The trigger event happened already &amp;quot;inflation spike&amp;quot; , the Fed is so far behind the curve. on this. 
 
We are now in Phase3. If the Fed acts fast  can keep us here! 
 
1) The trigger phase  inflation spike :Check 
2) Endemic  Phase:  Inflation now broad based: check 
3) Adaptive Phase : Behavior Changes , workers are demanding wage increase, prices keep rising etc. 
4) Anticipatory Phase:  Businesses anticipate future inflation,  start increasing prices even more, recession looms. 
 
We are not in Phase 4 yet but we are getting closer and closer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:42:08 </td>
   <td style="text-align:left;"> $SPY $QQQ It would appear that the target this whole time was Belarus, which Putin is apparently militarily planning to occupy indefinitely. While Ukraine is still the ultimate target I believe Putin will instead work on installing a puppet there instead of a direct confrontation and continue to destabilize along the Belarus border. Genius. If this turns out to be true, the market will likely rally hard short term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:41:35 </td>
   <td style="text-align:left;"> $DJIA $DIA $QQQ $SPX $SPY 

It’s rare we see a President do so many things right this early on in his term. 

Biden , you magnificent beast.

Keep up the outstanding work, our economy is roaring.

Take notes - Conserva-Tards ✌️🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:40:40 </td>
   <td style="text-align:left;"> $QQQ I’m starting to think all the bull accounts are bots.  No way they could be that dumb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:40:23 </td>
   <td style="text-align:left;"> $QQQ $SPY the wild thing is - the majority of Americans don’t trust our media sources anymore.

Many might even believe Russian news over CNN and the like. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:39:55 </td>
   <td style="text-align:left;"> $QQQ BRING ON THE PAIN $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:39:04 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.msnbc.com/msnbc/amp/rcna15144 
 
If the jobs market remains strong then the Dems should do well in the midterm this November and President Biden can make a big push with his agendas again such as infrastructure and clean energy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:38:33 </td>
   <td style="text-align:left;"> $QQQ did you think holding over the weekend might turn out good??  Hahaha dumb money.   put ur sell orders in now for Tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:36:09 </td>
   <td style="text-align:left;"> $QQQ hahaha listen to the Dumb money, grasping at their only hope of no war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:35:53 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:33:54 </td>
   <td style="text-align:left;"> $QQQ has the war started yet ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:33:53 </td>
   <td style="text-align:left;"> This economic weapon could cut Russia off from &amp;#39;the 21st century economy&amp;#39;

https://finance.yahoo.com/news/this-economic-weapon-could-cut-russia-off-from-the-21st-century-economy-124135370.html

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:32:42 </td>
   <td style="text-align:left;"> How a Russian invasion of Ukraine could affect the U.S. economy

https://www.cbsnews.com/video/how-a-russian-invasion-of-ukraine-could-affect-the-us-economy/#app

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:31:49 </td>
   <td style="text-align:left;"> $QQQ $SPY 

STRONG JOE IS THE GREATEST PRESIDENT OF ALL TIME!

I WISH I WOULDVE VOTED FOR HIM 200 TIMES INSTEAD OF JUST 100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:31:43 </td>
   <td style="text-align:left;"> Hope for the bulls fromJPM Market Watch note Feb 19: 
 
“Typically, a few months around the first hike, equities have fallen in the single digits. Equities have tended to firm 3-4 months after the first hike,and make fresh all-time highs within 6-12 months.” 
 
$SPX $QQQ $TQQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:31:31 </td>
   <td style="text-align:left;"> $SPY $QQQ A perfect timing for a long weekend I guess, it gives investors more time to digest the Russian news and more and more people will realize that the war will have close to zero impact to the US economy. The US consumers would continue to spend as usual no matter what’s going on in Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:31:30 </td>
   <td style="text-align:left;"> $QQQ i like how leaders always say we’re not going to war but it happens anyways. 

We are not about to send American boys 9 or 10 thousand miles away from home to do what Asian boys ought to be doing for themselves. LBJ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:29:30 </td>
   <td style="text-align:left;"> $QQQ $SPY Take your shithole politics elsewhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:28:56 </td>
   <td style="text-align:left;"> $DJIA $DIA $QQQ $SPX $SPY 

Thank the lord for Biden , his amazing vaccines, containing/eradicating the virus with his well executed plan (something trump couldn’t do), his push to get conservative CEOs to fix their supply chain issues and his strong arm stance to JPOW, curbing inflation. Not only this, but he also was able to stand up too and scare off Putin. 

What a blessing that Biden is in and Trump is out. 

Not to mention he has the best VP in the history of this nation at his side in Kamala Harris.

No more Republicans please. 
🙏🙌🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:26:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $SQ If no war happens by today or tomorrow think its only fake news from media, because forst they said they are waiting for olympics to be finished, now they will say some other reason and extend it, everything is already priced in, we are not ukraine that we should react every second, we reacted enough one whole week and all indexes dropped 1000 points.Now this country people need relief rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:24:37 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ about to get UGLY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:24:27 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA Sloppy Joe and his admin are orchestrating mass destruction through collaboration. Everyone is in bed with everyone. Mind blowing they have the majority believing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:24:17 </td>
   <td style="text-align:left;"> $QQQ Joe Biden is the epitome of American strength!

Born to a poor family, he pulled himself up by the bootstraps straight to the very peak of our society.

Joe is fair, kind, and generous!

Joe has never been a racist, he LET Obama be president first.

Joe is a wonderful family man, a true and loyal patriot, and his mind and body are both as fit as the day he was 35

All global leaders fear and respect Strong Joe!

some actually swoon for him.

we as a country are certainly not fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:24:07 </td>
   <td style="text-align:left;"> $QQQ  I am in some QQQ $338 2/23/22 PUTs. I am planning a good size drop in the Market by Tuesday Open. The fact there is no Trading on Monday will just build the FEAR and desire to sell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:23:57 </td>
   <td style="text-align:left;"> $SPY $QQQ Olympics over.  Wen war? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:23:42 </td>
   <td style="text-align:left;"> $QQQ $SPY looks like the plan was to invade at 4am on 2.22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:23:23 </td>
   <td style="text-align:left;"> $QQQ $SPY $SPX $DJIA $IWM   Something is up. There will be no invasion and Biden will take the credit. And shorts are finished </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:21:25 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ I wish Putin will come out and tell the American people they’re presidents an asshole, I am withdrawing like I’ve been planning on! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:21:07 </td>
   <td style="text-align:left;"> $QQQ https://news.yahoo.com/growth-us-economy-under-trump-214116363.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:20:46 </td>
   <td style="text-align:left;"> $DJIA $SPX $SPY $QQQ $DIA 

The science behind the vaccines in Moderna’s , Pfizer’s and J&amp;amp;J’s Pipeline may just be some of the most ambitious and cutting edge processes we have ever seen in the history of the world. 

Incredible.

Thank god Trump is out, and Biden is in 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:20:31 </td>
   <td style="text-align:left;"> $QQQ I feel like everyone bought puts. So Tuesday could be bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:19:32 </td>
   <td style="text-align:left;"> FED and all world Country printed too much money &amp;amp; gave too much free $$ to people in pandemic.  
 
Many retail got rich in $btc.x cryptos ; Time for them to collect that money back from us. Russia stiuation is just an stupid excuse.  
No more easy trade / money !! $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:16:17 </td>
   <td style="text-align:left;"> $QQQ $SPY bitcoin down. Usually good sign stocks will have a bad week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:13:47 </td>
   <td style="text-align:left;"> $QQQ $SPY 
QQQ -&amp;gt; 280 by End of April
SPY-&amp;gt;390 by End of April </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:13:17 </td>
   <td style="text-align:left;"> $DJIA $DIA $QQQ $SPX $SPY 

Donald Trump could quite possibly be considered one of the WORST leaders in the history of the world. Let that sink in.

Thank the lord Biden is in, and Trump is out. Biden eradicated the virus with his beautiful executed plan, and now prevented a world war by scaring off Putin. Putin wanted no part of Joe’s Wraith so he decided to ride with Biden rather , instead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:12:20 </td>
   <td style="text-align:left;"> $SPY $QQQ   I wanna get the f out of stock twist when I see how manny dumb stupid people here .. Excuse my french!! Stock market is all about it FED and FED is f the market because too much free money printed !! Russia news is just an excuse and even peace does not mean bullish for a long term!!!  Too many dumbs here talk about just a Russia .. This market is overbought and needs to corrected that all … After I read ST even my self getting tempt from dumb pumpers !! Gezz .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:07:28 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:07:21 </td>
   <td style="text-align:left;"> $QQQ its huge shit sandwich and we’re all going to have to take a bite thanks biden and the dems </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:06:19 </td>
   <td style="text-align:left;"> $SPY $qqq the war has been cancelled! big rally Tuesday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:05:54 </td>
   <td style="text-align:left;"> $QQQ More fuckery tomorrow ?

Wait nevermind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:05:05 </td>
   <td style="text-align:left;"> https://youtube.com/watch?v=JStETvXu0vM&amp;amp;feature=share
Is russia going to crash the market? Let’s take a look at historical events with market reactions! $qqq $spy $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:04:08 </td>
   <td style="text-align:left;"> $IWM biggest short opportunity out of all the major index ETF’s $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:01:41 </td>
   <td style="text-align:left;"> $QQQ The biggest threat to this country is not President Biden, not Donald Trump, and not any foreign World Leader, it  is the lying, propagandist, far left, Marxist American Media. It makes me sick to my stomach to see how the media gaslight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:01:26 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:00:40 </td>
   <td style="text-align:left;"> $QQQ nato has fooled putin . although it was decided in 1990 that it would not move an inch to the east, it does. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 05:00:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:59:35 </td>
   <td style="text-align:left;"> $QQQ $SPY $VIX oval office primetime national televised message time??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:59:34 </td>
   <td style="text-align:left;"> $DJIA $DIA $SPX $SPY $QQQ 

It’s rare we see a President do so many things right this early on in his term. 

Biden , you magnificent beast.

Keep up the outstanding work, our economy is roaring.

Take notes - Conserva-Tards ✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:58:47 </td>
   <td style="text-align:left;"> $DJIA $DIA $QQQ $SPX $SPY 

Thank god for the democrats.

If Trump and cronies were still in power at the White House - we’d be smack in the middle of a recession right now. 

Thank god one of the the most cruel and worst leaders in Donald Trump is out after only one term, and Biden is in. 

We are blessed 🇺🇸 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:57:33 </td>
   <td style="text-align:left;"> $QQQ $SPY But the death cross also can be a lagging indicator. It showed up in April 2020, after the Nasdaq hit its trough the previous month. 🟢👍🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:56:56 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.wionews.com/world/russia-france-agree-to-work-for-an-east-ukraine-ceasefire-joe-biden-willing-to-meet-vladimir-putin-454881/amp 
 
Looks like the situation is getting slightly better there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:55:41 </td>
   <td style="text-align:left;"> $SPY $qqq sort of an interesting development in Belarus. Maybe putin just wants this country instead of Ukraine. Definitely an interesting way of going about it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:55:18 </td>
   <td style="text-align:left;"> $QQQ $SPY $SPX $DJIA $IWM   Bears will be FRIED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:55:00 </td>
   <td style="text-align:left;"> $DJIA $DIA $QQQ $SPX $SPY 

Thank the lord for Biden , his amazing vaccines, containing/eradicating the virus with his well executed plan (something trump couldn’t do), his push to get conservative CEOs to fix their supply chain issues and his strong arm stance to JPOW, curbing inflation. Not only this, but he also was able to stand up too and scare off Putin. 

What a blessing that Biden is in and Trump is out. 

Not to mention he has the best VP in the history of this nation at his side in Kamala Harris.

No more Republicans please. 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:54:06 </td>
   <td style="text-align:left;"> $SPY 39 spots left before closing the free invite. Link in bio ⚠️🌐🅿️ $QQQ $DIA $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:53:03 </td>
   <td style="text-align:left;"> $QQQ Watch how the corrupt, lying, propagandist media switch the Russia narrative mid stream to - &amp;quot;as we have reported might happen, Russia is now withdrawing their troops, and War has been averted thanks to our President&amp;#39;s astute and competent diplomatic handling of the situation.&amp;quot;  
 
This country is so totally fked because of the corrupt, lying, propagandist media that has now brainwashed at least half of America with their constant daily gaslighting lies, and their constant blacking out of stories that they don&amp;#39;t want the American people to see. The media blacks out news that does not fit into their left wing, marxist, propagandist, political agenda. What they do report, they spin and twist it to fit their agenda. America = you are being lied to every day by the media folks, either by what and how they report news, or what news they refuse to report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:52:05 </td>
   <td style="text-align:left;"> $QQQ bounce on Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:49:32 </td>
   <td style="text-align:left;"> $SPY $QQQ Prick your finger, it is done
The moon has now eclipsed the sun
The angel has spread its wings
The time has come for bitter things
Prick your finger, it is done
The moon has now eclipsed the sun
The angel has spread its wings
The time has come for bitter things </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:49:07 </td>
   <td style="text-align:left;"> $QQQ my question is, is futes open on Monday or no? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:48:16 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:47:00 </td>
   <td style="text-align:left;"> Although the technical rating is bad, $QQQ does present a nice setup opportunity. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:46:41 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA Midterms in November... desperate times call for desperate measures. All this bullsh%t, war, Covid, high oil, inflation, supply chain, mandates etc.. will disappear shortly. With a 30% approval rating, Biden and his cronies know its their only chance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:46:18 </td>
   <td style="text-align:left;"> $QQQ I don&amp;#39;t understand why Binden has too involve US with International Affairs. Simple solution don&amp;#39;t let Ukraine join Nato end of story. Just bc Ukraine isn&amp;#39;t part of Nato doesn&amp;#39;t mean we can&amp;#39;t have an alliance with them. I don&amp;#39;t trust Ukraine &amp;amp; Russian Gov this whole debacle could be chess move to undermine the US for all we know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:45:06 </td>
   <td style="text-align:left;"> Market Recap - Sunday, Feb. 20 $QQQ $EEM $IWM $JNK https://talkmarkets.com/content/global-markets/market-recap-sunday-feb-20?post=345440 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:44:50 </td>
   <td style="text-align:left;"> $PYPL $QQQ $SQQQ $BTC.X 

The markets didn’t drop because of the potential Russia conflict, they won’t rise if Russia decides not to invade

They dropped because of massively printing money with extremely low interest rates and debt OVERLOAD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:43:29 </td>
   <td style="text-align:left;"> $QQQ $SPY $SPX $DJIA $IWM  This is just the same sh*t    bears better not stay short too much longer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:43:22 </td>
   <td style="text-align:left;"> $QQQ you guys realize Ukraine has to say they aren’t concerned to not panic their people. If they panic the people everyone would evacuate and not defend the motherland </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:42:15 </td>
   <td style="text-align:left;"> $QQQ seems like bears and bulls both want war now 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:40:07 </td>
   <td style="text-align:left;"> $spy $qqq markets will be closed tomorrow but futures open as normal - watch kids jump in excitement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:38:38 </td>
   <td style="text-align:left;"> $SPY $QQQ  😆WTF !!! Everybody is bearish about the s&amp;amp;p and Nasdaq but very bullish for $AAPL $MSFT $AMZN   
 
Don’t trust anybody here!  
 
Be Long 🟢 DCA if dip more 🦾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:36:45 </td>
   <td style="text-align:left;"> $QQQ shits been worse than this for sentiment only 28 percent of time in the last 16 years…everyone trippin over a fake war and transitory inflation…as soon as the money people got for free is spent…everyone will go back to work </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:34:38 </td>
   <td style="text-align:left;"> $BTC.X  bros tawkin to $qqq growth stink bros congratulating each other over last 6 months +  performance.   🍿

https://youtu.be/v8du0OsRINU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:34:34 </td>
   <td style="text-align:left;"> $SPY $QQQ Long on war? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:32:02 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $TQQQ $AAPL The threat of war is just being used to hedge against interest rate hikes and deflation. Know the game and economics. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:30:37 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ 

Biden is a fucking idiot if Russia attacks right now how is it going to change the life of any American right now is Russia going to be invading the United States he’s such a fucking asshole he’s so shut the fuck up how would invasion of Russia by reminding us every three or four hours affect our day-to-day life can you tell me that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:29:28 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA Russia and Ukraine are going to war? Sure...  just like the Covid vaccine were 99% effective. The same crooked morons are pushing a war narrative because they are failing on ALL fronts. A collaborated distraction from incompetency. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:29:17 </td>
   <td style="text-align:left;"> Options Vs Futures: Should You Be Trading Futures?

$SPY $QQQ $IWM $ES_F $DIA

https://www.chartlearning.com/2021/10/stock-futures-versus-options-trading.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:28:54 </td>
   <td style="text-align:left;"> $QQQ no one knows what is gonna happen. Stop spreading 💩 and fear stupids. 1 month fucking with war news... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:27:17 </td>
   <td style="text-align:left;"> $BTC.X$SPY $QQQ historically from the start of interest rate hike until the end of rate hike stocks performed better than other times. ironically nasdaq even performed even better. Why ? Here my opinion. If fed anounces rate hike lets say nasdaq start dipping until rate hike. Because it will be priced in.after the rate hike it starts to rise stronger from the lowest point.that is why higher returns. so bears you should have shorted market months ago when it had ath not now dumbass bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:26:20 </td>
   <td style="text-align:left;"> Looks like the fed has a couple months to short the market and until May 2023 to cover? based on new ‘restrictions.’ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:23:17 </td>
   <td style="text-align:left;"> $SPY $AMD $AAPL $QQQ 
Is this good news ?    No!

Russia is closing the airspace over the Sea of Azov at midnight UTC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:22:50 </td>
   <td style="text-align:left;"> $QQQ $SPY $VIX meanwhile Bidens hiding in his basement in Delaware 😐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:18:58 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:18:55 </td>
   <td style="text-align:left;"> $SPY On  the 21st the Olympics are over and do you know what that means?  There is nothing stopping Russia from invading Ukraine.  Puts on $QQQ $SPY $IWM own the $VXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:18:19 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM  
 
Blame the fed, not the war, for the incoming deep market correction. Everything else is just a distraction to their failure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:18:12 </td>
   <td style="text-align:left;"> Damn, those Russia-Ukraine headlines are getting worse and worse holy-- $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:17:51 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:17:15 </td>
   <td style="text-align:left;"> $QQQ always do the opposite of what the news is preaching ;))) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:15:38 </td>
   <td style="text-align:left;"> $QQQ Been bearish, letting you all know still bearish.  Will have to roll over my Put options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:13:58 </td>
   <td style="text-align:left;"> 3-Minute Weekly Market Outlook &amp;amp; Weekly Plan:   
2.21.22 - 2.25.22 
 
$ES_F $NQ_F $SPY $QQQ $CL_F  
 
https://www.youtube.com/watch?v=2Y8qSBxi51E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:11:35 </td>
   <td style="text-align:left;"> $SPY  $DJIA  $TQQQ  $QQQ  $XBI  
It’s easy during the mainstream media’s breathless reporting of the: to be, or to not to be -warfare - to forget that there are a wide variety of deep downward pressures on the overall market outside of that narrative at present.  Not saying it will be the case, but if there is war that drives the market down, the same mainstream media will be quick to blame “Unavoidable external forces” for what have actually been poor, bubble-creating internal policies at the FED. Remain nimble with your capital and  look for a   change in  trend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:11:09 </td>
   <td style="text-align:left;"> $SPY U.S. Embassy In Russia Warns Americans To Think Of Plans On How To Leave Russia - $QQQ 
so like i said before i believe everything politically and globally is preplanned. 

everyone yelled at trump for calling the media and news, FAKE NEWS, but look at everything coming out every hour lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:07:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $VIX Market&amp;#39;s are going to sh*t the bed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:04:34 </td>
   <td style="text-align:left;"> $QQQ  BOTTOM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 04:02:28 </td>
   <td style="text-align:left;"> $SPY U.S. Embassy In Russia Warns Americans To Think Of Plans On How To Leave Russia $QQQ $DIA Link in bio for free Discord 40 spots left💨💨💨💨💨💨💨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:59:58 </td>
   <td style="text-align:left;"> $QQQ how can it deter an attack and Putin has made up his mind to attack at the same time? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:59:31 </td>
   <td style="text-align:left;"> $SPY $QQQ The US military has begun exercises in Poland near the Ukrainian border
bullish right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:58:54 </td>
   <td style="text-align:left;"> $QQQ $SPY how can she say 2 different things at The same time?  Sanctions will absolutely deter an attack and that Putin has made up his mind to attack? Wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:58:14 </td>
   <td style="text-align:left;"> $SPY $QQQ Lots of talk about Russia. Good track to listen to while you do: Moskau

https://youtu.be/mAz50pZn6Ys?t=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:56:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X 

So Biden leaving DC to Delaware so no war u fear mongering cunts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:56:09 </td>
   <td style="text-align:left;"> Market hasn’t been the simplest and easiest for all traders including professional ones. But let me ask you this, do you often find that you enter into options trade and get those base Hits in Options that are 10-40% per trade? If you do, go for them. Don’t just go for homeruns because even in professional sports, they go for base hits by base hits. Trading shouldn’t be any different. Just some food for thought

$STUDY $SPY $QQQ $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:50:33 </td>
   <td style="text-align:left;"> $QQQ bulls will believe anything lol war or no war rates are being cranked up nothing about this environment is bullish. And my friend in the Air Force already confirmed a conflict so it’s happening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:50:19 </td>
   <td style="text-align:left;"> $DJIA $QQQ $TLT We see nothing but upside coming into the summer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:43:48 </td>
   <td style="text-align:left;"> Biden to travel to Wilmington, Delaware on sunday - free Discord link in bio $SPY $QQQ $DIA $VIX $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:40:07 </td>
   <td style="text-align:left;"> $SPY $QQQ The US says the war is coming while Russia says no war, I guess it is easy for people to believe which country more. I would have to say a war is much more likely than no war despite I don’t want any war to happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:38:34 </td>
   <td style="text-align:left;"> $QQQ
https://thereformedbroker.com/2022/02/19/we-may-have-a-liquidity-problem/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:35:51 </td>
   <td style="text-align:left;"> $TSLA how big will gap down be for $QQQ on Tuesday before market bounce next week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:34:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $NASDAQ $SPXL $BROS 

I don’t post many interviews, but this is a particularly good one from a respected swing trader discussing everything from strategies and daily mindsets.

If you think traders are always right-they’re not. Its about WHEN to be right. Ryan discuses what to do when markets are this choppy and how to find ways in which making trading easier on your mind and personal life. Spoiler here- sometimes its better to do nothing and go for a walk!

Anyway, hope this helps some of you out, or at least entertains you. Have a good Sunday everyone 

https://youtu.be/tmS_er4mbrU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:30:57 </td>
   <td style="text-align:left;"> $QQQ $SPY Good news for the markets.  Now if Biden can stop crying wolf we might see some recovery. 
 
https://www.infowars.com/posts/putin-and-macron-agree-on-measures-to-halt-escalation-in-ukraine/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:29:51 </td>
   <td style="text-align:left;"> $SPY BIDEN IS LYING TO AMERICAN PEOPLE TO FAVOR HUNTER. ALL IS BS. $AMC $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:29:13 </td>
   <td style="text-align:left;"> $SPY $qqq $uvxy $tvix $gld game over, no war.
Word is in! 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:28:02 </td>
   <td style="text-align:left;"> $QQQ why are France and Russia talking when Putin has given the order to Charge ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:26:38 </td>
   <td style="text-align:left;"> $SPY $QQQ a perspective about damage under the surface. there were also more stocks listed in nasdaq in 1999 than now (1000 or so more). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:25:59 </td>
   <td style="text-align:left;"> $QQQ new bear markets will last 6 months to a year tops its 2022 this isnt a boomer market anymore hard vs down and up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:19:15 </td>
   <td style="text-align:left;"> $QQQ https://www.youtube.com/watch?v=BrF0TpcQh70 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:18:42 </td>
   <td style="text-align:left;"> $QQQ $TSLA 2/18 $835 P 4.10

ON THE BEAK OF $843.75

We can add you to premium channels once you sign up for $50 per month or give you discount for stock of option channels only.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:18:19 </td>
   <td style="text-align:left;"> $QQQ is 350 possibly for Tuesday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:15:04 </td>
   <td style="text-align:left;"> $AMD $QQQ $AAPL $SPY 

Market to retrace Lows possibly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:14:20 </td>
   <td style="text-align:left;"> $QQQ $SPY we are in correction territory close to bear market and the fed has yet to taper… let that sink in people… what do you think happens when they start the tapering…. ending purchasing assets… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:13:22 </td>
   <td style="text-align:left;"> $SPY for those that don’t know. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:12:04 </td>
   <td style="text-align:left;"> $QQQ clearly a lot of desperate bears here. If there was going to be a war Russia wouldn’t be giving months of prep time to their enemy. It would have happened already. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:11:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $PFE Good stuff. Can&amp;#39;t wait for my 4th and 5th jab. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:11:45 </td>
   <td style="text-align:left;"> $QQQ futes ripin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:11:00 </td>
   <td style="text-align:left;"> $QQQ is it Game Time?   Tomorrow morning do we wake up to an invasion? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:10:15 </td>
   <td style="text-align:left;"> Invest with an outcome based approach on $QQQ. Make up to 8.2% (9.5% annualized) and start to lose only if $QQQ drops by more than 20.6% through 12/30/2022.

Buy 1 $340 call
Sell 1 $362 call
Sell 1 $270 put
 12/30/22 expiration
https://o.oliveinvest.com/6g34cg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:07:03 </td>
   <td style="text-align:left;"> $QQQ market will fly if negotiations go well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 03:02:10 </td>
   <td style="text-align:left;"> Market Volume Barometer 2-18-2022 
Sentiment: EAGER 
Volume: 4% 
Real Feel: SWELTERING 
Cycle: BEARISH II 
Portfolio: LONG 
Next Day Move: SIDEWAYS DOWN 
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/ 
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 02:59:47 </td>
   <td style="text-align:left;"> $AMD $QQQ $AAPL $SPY 
SPY index is a barometer of the trend Bull or Bear in The Overall Market along with Nasdaq is also a Bearish Trend 

Look, Market close below the 76.4% Fibonacci retrace amd  Market closed below 
SPY is now below 250 Day Moving Ave </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 02:59:38 </td>
   <td style="text-align:left;"> $QQQ $su no war is coming! Putin agrees to diplomatic solutions. Monster rally Tuesday!! i give you my word </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 02:58:48 </td>
   <td style="text-align:left;"> $QQQ $SPY ngl this seems like the Iran crap when the market dumped and came back overnight and since this is a 3 day weekend Monday is probably gonna see a rebound in futures if we’re being real here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 02:58:46 </td>
   <td style="text-align:left;"> $SPY $QQQ NO WAR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-21 02:57:16 </td>
   <td style="text-align:left;"> $QQQ just need republicans to take house and Senate in November, and market will survive. Trump 2024! $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 08:49:01 </td>
   <td style="text-align:left;"> $FB $aapl $nvda  This bitch is still alive, she will live a luxury lifestyle and will not die for long years. After stealing from
India with the most luxurious jewels and live as a queen - they have also stolen from other areas as well, Fiji was given independence in 1971, I think 

Queen Elizabeth tests positive for Covid, her symptoms are mild https://www.cnbc.com/2022/02/20/queen-elizabeth-tests-positive-for-covid-her-symptoms-are-mild-and-she-is-vaccinated.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 08:48:36 </td>
   <td style="text-align:left;"> $AAPL how are futures down if the market is closed tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 08:36:24 </td>
   <td style="text-align:left;"> $AAPL everyday I get a message that the market is down or futures are down due to Russia-Ukraine tensions rising. This has been going on for 2-3 Fng weeks now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 08:22:38 </td>
   <td style="text-align:left;"> $AAPL Tuesday #stateoftheUnion gonnaz be epic failure #FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 08:20:31 </td>
   <td style="text-align:left;"> $DWAC $AAPL  I think Trump got so many pre orders on Apple they had to slow the rollout for a real Presidents’ Day ( not Brandon) not to worry libtards if you did not pre order you will get your chance to be on truth social too . https://www.foxbusiness.com/politics/trumps-truth-social-to-begin-welcoming-americans-who-pre-ordered-the-app-monday?cmpid=fb_fbn&amp;amp;fbclid=IwAR0n98fKw32szgcG8UiCTBEBmB0ERAAyf-qGEIev2g3zuA8ISorJatwhkLE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 08:16:02 </td>
   <td style="text-align:left;"> $AMZN $AAPL $FB $SNAP  is stock market closed trrw? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 08:12:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $AAPL  
 
Wait until big apple falls, then QQQ will accelerate its drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 08:03:12 </td>
   <td style="text-align:left;"> $AAPL oh no predications are showing downtrends from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 07:50:29 </td>
   <td style="text-align:left;"> $AAPL $NVDA $TSLA https://electrek.co/2022/01/20/gm-is-actually-making-evs-pre-production-cadillac-lyriq-rolls-off-assembly-line-deliveries-to-follow/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 07:47:54 </td>
   <td style="text-align:left;"> $AAPL Ponzi Schemer Bernie Madoff&amp;#39;s Sister, Husband Found Dead  https://www.bloomberg.com/news/articles/2022-02-20/ponzi-schemer-bernie-madoff-s-sister-husband-found-dead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 07:45:20 </td>
   <td style="text-align:left;"> As long as there is a bed. Biden can go anywhere. Our tired President visiting Putin. $SPY $BTC.X $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 07:37:16 </td>
   <td style="text-align:left;"> $NKLA  I hold these 5 stocks $AAPL $LCID $SLS $BB   to the moon 💪🏼🏹 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 07:25:21 </td>
   <td style="text-align:left;"> $AAPL expected to announce multiple products in 2022. The spotlight, however, is likely to be on the company&amp;#39;s Mac computers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 07:25:17 </td>
   <td style="text-align:left;"> $AMZN $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 07:22:59 </td>
   <td style="text-align:left;"> $SPY $AAPL $TQQQ $SOXL $NVDA 
Russian invasion of Ukraine could trigger &amp;#39;stagflationary wind&amp;#39;
“If it were to get worse — which is a big if — a very strong stagflationary wind would blow through the global economy,” 
Stagflation occurs when economic growth slows sharply and inflation rises.

https://ca.finance.yahoo.com/news/russian-invasion-of-ukraine-could-trigger-stagflationary-wind-mohamed-el-erian-201921702.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 07:22:38 </td>
   <td style="text-align:left;"> $AAPL Biden will destroy anyone who crosses him!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 07:14:52 </td>
   <td style="text-align:left;"> Equity Sentiment Weekly Recap: $AAPL is the #1 stock that institutions traded this week with 279.8K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 07:09:49 </td>
   <td style="text-align:left;"> $AAPL Share your thoughts about Apple https://www.reddit.com/r/wallstreetfools/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 06:55:13 </td>
   <td style="text-align:left;"> $SPY $TQQQ $AAPL $NVDA $BTC.X 
😨😱 Going Costco for toilet papers, waters, gas 😞
U.S. has intel that Russian commanders have orders to proceed with Ukraine invasion

https://www.cbsnews.com/news/russia-ukraine-invasion-us-intelligence-orders/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 06:55:06 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Reportedly Gears For Multiple Mac Launch Events; &amp;#39;Silicon Transition Will Shift Into High Gear In 2022&amp;#39; https://www.stck.pro/news/AAPL/23208079 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 06:52:20 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $AAPL $SQ Correction looks on the horizon; perhaps for next 3-5 weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 06:28:40 </td>
   <td style="text-align:left;"> $AAPL https://www.imore.com/editors-desk-tons-iphone-news-and-spatial-audio-may-be-hit-apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 06:24:56 </td>
   <td style="text-align:left;"> $AAPL hey if I’m 3 shares away from 100 shares, is it worth buying them on margin tomorrow and selling covered call to help pay the shares off? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 06:16:04 </td>
   <td style="text-align:left;"> Of course it&amp;#39;s difficult to predict the future of stocks especially during times like this and recently it&amp;#39;s looking like tech stocks having been going down these last few months. But I would like to hear others thoughts of other people in regards to the stocks below and their future: 
$MSFT $AAPL $FB $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 06:13:32 </td>
   <td style="text-align:left;"> Momentum Monday – Bearish Market Environment https://ivanhoff.com/2022/02/20/momentum-monday-bearish-market-environment/ @MarketSmith @howardlindzon $QQQ $ARKK $EXPE $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 06:12:02 </td>
   <td style="text-align:left;"> $AAPL outperforms 89% of all stocks! https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 06:00:10 </td>
   <td style="text-align:left;"> $SPY They all bought puts? $M $NVDA $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:53:36 </td>
   <td style="text-align:left;"> AMD has officially released its Ryzen 6000 processors. 
They come with a number of improvements, including twice the integrated graphics performance.

$AAPL | $INTC | $TSLA 

$AMD ↗️Ryzen 6000 integrated graphics rival $NVDA Nvidia&amp;#39;s discrete GPUs | Digital Trends

 https://www.digitaltrends.com/computing/amd-ryzen-6000-integrated-graphics-rival-nvidia-discrete-gpus/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:50:14 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL), Intel Corporation (NASDAQ: $INTC) – Apple Reportedly Gears For Multiple Mac Launch Events; ‘Silicon Transition Will Shift Into High Gear In 2022’ https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-intel-corporation-nasdaqintc-apple-reportedly-gears-for-multiple-mac-launch-events-silicon-transition-will-shift-into-high-gear-in-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:47:45 </td>
   <td style="text-align:left;"> We may need the bearish sentiment to increase and to last a little while longer to find a truer bottom. 

It was all about the &amp;quot;calls&amp;quot; for 20 months. 
Now, it&amp;#39;s all about the &amp;quot;puts&amp;quot;. 
Lower-highs are evident.
Current $CPC  regime points higher interim

$VIX  $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:47:24 </td>
   <td style="text-align:left;"> $AAPL China and Russia  disgrace to this world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:41:10 </td>
   <td style="text-align:left;"> $AAPL | $DWAC | $PHUN - Donald Trump’s TRUTH Social will launch in the Apple App Store tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:39:19 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL There hasn’t been this level of tension in the world since they were picking the name of the Royal Baby!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:31:46 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:30:05 </td>
   <td style="text-align:left;"> $AAPL $NVDA $FB $COST Russia hit back at the US embassy in Russia’s advice that Americans in the country should “have evacuation plans” amid media reports of “threats of attacks,” Reuters reports.
Russia’s foreign ministry spokeswoman, Maria Zakharova, questioned if the United States had passed on the information about possible attacks to Russia. “And if not, how is one to understand all of this?” Zakharova said, according to Reuters. 

&amp;quot;Whales and politicians are manipulating to buy cheaper shares in the USA, greedy people haven&amp;#39;t cashed in enough after the COVID profit where Nancy was worth $300 million is now $2.8 billion to $3.1 billion worth, Diane F ~ $9 billion to $11 billion and the list goes on and on&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:17:25 </td>
   <td style="text-align:left;"> $SQ $PYPL  
 
Hmm all the big company like $AMZN $AAPL are doing their own Fin-tech now. 
 
Weekly update: 
Is it a buying opportunity for Roblx &amp;amp; NVDA?  
https://youtu.be/JStETvXu0vM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:17:04 </td>
   <td style="text-align:left;"> $NASDAQ $AAPL $SPY $AMD $GOOGL  it’s very contradicting news coming out us govt keep saying invasion is imminent but eu and Russia singing diff song. Who’s to believe here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:15:05 </td>
   <td style="text-align:left;"> $AAPL Apple Hold long term safe but if your bored or tired of being on here 
 
take a Break and go see Uncharted the movie 
 
Its a GREAT FAMILY FILM I RECOMMEND TO EVERYONE ON HERE. 
sometimes 
yea 
https://www.indiewire.com/2022/02/tom-holland-channing-tatum-uncharted-dog-box-office-1234700909/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 05:09:47 </td>
   <td style="text-align:left;"> latexec5efb0cdfc6280552e1a78fbd6f1065HYG - 93% put flow 
$NVDA - 51% put flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:45:20 </td>
   <td style="text-align:left;"> #Levermann #Global #MegaCap #Sell WK7 $AAPL (2), $GOOGL (1), $AMZN (-4), $FB (0), $0700.HK (1), JPM (-1), UNH (2), JNJ (-1), BAC (0), WMT (-4) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:44:54 </td>
   <td style="text-align:left;"> $AAPL $TSLA https://europe.autonews.com/automakers/tesla-faces-scrutiny-german-regulator-over-autopilot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:44:30 </td>
   <td style="text-align:left;"> $AAPL $TSLA https://www.thedrive.com/news/44068/over-10-percent-of-tesla-model-s-evs-fail-germanys-strict-inspection-after-3-years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:43:43 </td>
   <td style="text-align:left;"> $AAPL https://interestingengineering.com/volkswagen-huawei-self-driving </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:41:41 </td>
   <td style="text-align:left;"> $AAPL 2.7T market cap. You gotta be out of your damn minds holding this garbage. Literally will burst 40% at any given time. Just one horrible guidance and you are all foooooooked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:40:13 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL who wants a chart analyzed? ANY stock. Please specify if short/long term. I charge a follow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:39:06 </td>
   <td style="text-align:left;"> $AAPL Russia aside, thoughts on unionization efforts?  Bad for sp? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:38:38 </td>
   <td style="text-align:left;"> $SPY $QQQ  😆WTF !!! Everybody is bearish about the s&amp;amp;p and Nasdaq but very bullish for $AAPL $MSFT $AMZN   
 
Don’t trust anybody here!  
 
Be Long 🟢 DCA if dip more 🦾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:37:36 </td>
   <td style="text-align:left;"> $AAPL Start the sanctions now! 
 
Putin is already killing Ukraine&amp;#39;s economy and reaping sky-high oil revenue. 
 
WHAT ARE WE WAITING FOR?!! 
 
MG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:35:05 </td>
   <td style="text-align:left;"> $AAPL on the real, either use Macs or you lack class. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:32:02 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $TQQQ $AAPL The threat of war is just being used to hedge against interest rate hikes and deflation. Know the game and economics. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:27:37 </td>
   <td style="text-align:left;"> $AABB $AAPL $MSFT $GOOG $TSLA This will be the breakout year for $AABB and it&amp;#39;s 100% decentralized anonymous AABBG.X Exchange. Stay ahead of the the news and CURVE @AheadoftheNews @ACInvestorBlog @AnalystWire @AnneMarieTrades @abnormalreturns @Forecastis @Benzinga @BidnessEtc @biggercapital @charliebilello @CharlesRAAII @CharlesSizemore @DiscipleOfTrend @charliegasparino https://cryptobriefing.com/kraken-ceo-warns-users-to-get-your-coins-out-of-centralized-exchanges/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:23:17 </td>
   <td style="text-align:left;"> $SPY $AMD $AAPL $QQQ 
Is this good news ?    No!

Russia is closing the airspace over the Sea of Azov at midnight UTC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:10:27 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPL Happy Sunday everyone! Hopefully you&amp;#39;re taking some time off to enjoy the weekend.  I like to use this time to step back, reset, and prepare for the week ahead (DD, news, rumors, etc.)  
 
One of the most important things to track is social momentum and social sentiment. When a ticker starts to gain traction, more people see it, and it can start to take off.  
 
This is why we built this social sentiment dashboard, so you can stay ahead of the trends an movements. It is one of the most useful indicators for investing and trading. Check it out - happy to answer any questions. https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220220 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:07:58 </td>
   <td style="text-align:left;"> $ARKK $ARKW 

How far are the companies away from positive EPS ? I mean look at $AAPL  and $AMZN among other back in the day , they almost went bankrupt . The idea of investing is simple yet so hard  do . Invest in companies that have huge revenue growth but also are projected to cross positive EPS in give or take 3-5 years , then ignore it . Do not daily check it don’t get caught up in the month to month good or bad action , this dip here in 3-5 years will be known as one of the best buying ops of all time , and there may be more who knows but long term a lot of these growth stocks will be the next wave of mega caps . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:07:28 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 04:05:07 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-20 Largest Trades Data: 
https://www.youtube.com/watch?v=2h5BxPQmOcM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 03:56:56 </td>
   <td style="text-align:left;"> $AAPL A lot can happen from now till Tuesday market open. I have my full ammos ready to buy massive calls up to 3 times if Russia invades Ukraine. Targeting AAPL MSFT FB SQ UPST AFRM ASO and taking small call positions on SQ, FUBO and JMIA for Thursday ER. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 03:52:48 </td>
   <td style="text-align:left;"> $SPY $AAPL  *** 
 
$AMZN did you see the $1.5 $Billion order Friday? at white 26 candle average support.. one person comes to mind who own $AMZN.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 03:40:16 </td>
   <td style="text-align:left;"> Taxable Income Definition $TSLA $AAPL $AMZN $FB $AMC ..  https://www.billionaireclubcollc.com/taxable-income-definition/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 03:15:04 </td>
   <td style="text-align:left;"> $AMD $QQQ $AAPL $SPY 

Market to retrace Lows possibly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 03:13:26 </td>
   <td style="text-align:left;"> $AAPL 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 03:09:39 </td>
   <td style="text-align:left;"> $tsla-$840-$830 gap filled looks strong in $850 sup calls -$950 res puts ranges.
$amzn - wants to fill 2900-2800 res gap. puts at res playing $100 increments.
$aapl-wants to fill $160 gap. Puts at res playing $2.50-$5.00 increments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 03:07:46 </td>
   <td style="text-align:left;"> Scalping vs. Swing Trading: What’s the Difference? $TSLA $AMZN $AAPL $F $ROKU https://www.billionaireclubcollc.com/scalping-vs-swing-trading-whats-the-difference/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 02:59:47 </td>
   <td style="text-align:left;"> $AMD $QQQ $AAPL $SPY 
SPY index is a barometer of the trend Bull or Bear in The Overall Market along with Nasdaq is also a Bearish Trend 

Look, Market close below the 76.4% Fibonacci retrace amd  Market closed below 
SPY is now below 250 Day Moving Ave </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 02:52:55 </td>
   <td style="text-align:left;"> $AAPL - Apple retail employees are reportedly using Android phones and encrypted chats to keep their unionization plans secret </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 02:50:44 </td>
   <td style="text-align:left;"> $AAPL BRANDON is doing what he’ll of a job , dragging the US into a European War , he can’t even protect our own border . Oh wait inflation he’s got that under control , just keep paying $5.50 gal for gas. Don’t worry about food prices as most criminals are just walking into stores and stealing what they want while u pay for it .
Don’t worry about all the crime in your city it will only get worst as people get more desperate,
Hmmmmm Civil War ?

GREAT JOB BRANDON $XOM  $TSLA  $AMZN $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 02:28:52 </td>
   <td style="text-align:left;"> $AAPL retail employees are reportedly using Android phones and encrypted chats to keep their unionization plans secret </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 02:28:28 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 02:26:42 </td>
   <td style="text-align:left;"> Sweep Options Activity Weekly Recap: $AAPL is the #1 ticker with sweep activity that institutions traded urgently this week options with 213.8K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 02:17:49 </td>
   <td style="text-align:left;"> $AAPL when ppl get their screen time report and it says your screen time is down 2 hours in the last 7 days. Do you tell yourself, I need to get my screen time back up 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 02:11:54 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 02:11:42 </td>
   <td style="text-align:left;"> $AAPL https://share.acorns.com/avileitman4?advocate.partner_share_id=3890132155574457569
You’ll make $5 and if you get 6 people referred you’ll make $1000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 02:01:45 </td>
   <td style="text-align:left;"> $AAPL U.S. has intel that Russian commanders have orders to proceed with invasion 
 
https://www.msn.com/en-us/news/world/u-s-has-intel-that-russian-commanders-have-orders-to-proceed-with-invasion/ar-AAU63l9?ocid=msedgdhp&amp;amp;pc=U531 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 01:47:01 </td>
   <td style="text-align:left;"> $TSLA $QQQ $AAPL $SPY 

I’m betting on this turning out to be a big nothing burger, but we shall see… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 01:28:11 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ  the white 26 candle average line getting another retest. cloud bottom support.. lots of $AAPL darkpool and Calls action.. Billions..  on watch for the ichimoku cloud top breakout for bees.. #Bzzzzzzzzzzzz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 01:27:52 </td>
   <td style="text-align:left;"> $TSLA Gary Black 
@garyblack00 
· 
2h 
... $TSLA is my largest position because TSLA is like $AAPL 2007 when it disrupted the communications industry forever. My $1,600 $TSLA PT assumes many EV players will have L4 AD in a few years, so it becomes a cost of EV entry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 01:26:13 </td>
   <td style="text-align:left;"> $SPY $SPX  after the #Hostess #HeadnSnowballs pattern  neckline at ichimoku flat cloud bottom breakdown,  , lots of ichimoku cloud resistance testing. at old support levels ,now looks ready to aim for bounce above thin cloud resistance to make new high at #Zingers. needs fast break above $447 ,the white 26 candle average line..  
lots of clues in call activity.. lots of unusual call activity in Cathy Woods names in  $ARKK and #ARKF . will post clues later.  
Billions in $AAPl  darkpool /block shares .will post chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 01:18:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $AAPL 
If NASDAQ QQQ breaks 335.00 then next level below is QQQ at     313.00 🐻Ish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 01:09:00 </td>
   <td style="text-align:left;"> The industry average Profit Margin is 6.11%. $AAPL outperforms 94% of its industry peers. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 01:07:12 </td>
   <td style="text-align:left;"> $FSR $AAPL FISKER IS A LIFESTYLE BRAND IN THE MAKING, JUST LIKE APPLE https://fiskerati.com/fisker-ocean/fisker-is-a-lifestyle-brand-in-the-making-just-like-apple/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 01:04:11 </td>
   <td style="text-align:left;"> $AAPL Apple Option Alert: Fri $170 Calls Sweep (17) near the Ask: 246 vs 46179 OI🐂 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 00:46:42 </td>
   <td style="text-align:left;"> Can Apple Succeed Where Amazon Has Struggled?

$AAPL $AMZN

https://www.thestreet.com/technology/can-apple-succeed-where-amazon-has-struggled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 00:29:23 </td>
   <td style="text-align:left;"> $SPY $USO $AAPL $FB $AMZN &amp;quot;A day later Russia’s defence ministry said that some of the 180,000 or so troops it has deployed at its borders with Ukraine&amp;quot; Now what ? a question for the experts on S.T how the market will react on Tuesday and how OIL will react ?   https://www.economist.com/leaders/2022/02/19/whether-he-invades-ukraine-or-backs-down-putin-has-harmed-russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 00:17:19 </td>
   <td style="text-align:left;"> $AAPL Putin played that puppet Biden. Miss you Trump. Need him to prop up the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-21 00:00:15 </td>
   <td style="text-align:left;"> $AAPL Apple Option Alert: Jun 17 $165 Puts Sweep (6) near the Ask: 180 vs 22668 OI🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 23:54:09 </td>
   <td style="text-align:left;"> latex2b907614592bd365f2189a1b932dc7e9SPX Futures will be up. 
 
$aapl $nvda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 23:36:26 </td>
   <td style="text-align:left;"> $spy $qqq $aapl $googl $msft No War 
Huge gap up https://www.reuters.com/world/europe/macron-putin-agree-take-action-preserve-peace-elysee-2022-02-20/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 23:34:36 </td>
   <td style="text-align:left;"> $AAPL on watch for upside, needs 177.18 break to re-test all time high.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 23:32:46 </td>
   <td style="text-align:left;"> $AAPL 👏👏👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 23:26:52 </td>
   <td style="text-align:left;"> $AAPL putins just putting us on. Lol. Playing chess while biden is still in diapers playing checkers. Nat gas and oil through the roof, western financial markets shook, no way Ukraine will be part of NATO. All in all putin wins. That would be cavalier and stupid and hes not a stupid man. We rally. Maybe test 4300. But then rip higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 23:18:17 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 23:07:42 </td>
   <td style="text-align:left;"> This is amazing! What do you think? $AAPL in Uptrend: RSI indicator exits oversold zone. View odds for this and other indicators: https://srnk.us/go/3431011 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 23:07:06 </td>
   <td style="text-align:left;"> $DIS $FB $AAPL Are the markets open tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 23:03:04 </td>
   <td style="text-align:left;"> The Three Major Financial Statements: How They’re Interconnected $AMZN $FB $AAPL $TWTR $DWAC https://www.billionaireclubcollc.com/the-three-major-financial-statements-how-theyre-interconnected/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 22:57:48 </td>
   <td style="text-align:left;"> What inspires you to continue to spin indoors~ 

#HIIT 
#KISS
#mHealth
#Sustainable
#Gamification 
#WearableTech
#WalkwithWisdom 
#ConnectedFitness
#CommuneWithNATURE

Peloton’s $PTON new CEO sees app store and overhauled #subscription model in its future - The Verge

$PLNT $LTH $XPOF  $AAPL 

 https://apple.news/AOp51pSbwTvW5E9f2zHydqQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 22:55:43 </td>
   <td style="text-align:left;"> $SPY Now here is the Nasdaq 100. This is what is keeping mkts up plus $OIL 
$AAPL $AMZN $TSLA . If the 10 majors really start to decline. It would be incredible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 22:53:46 </td>
   <td style="text-align:left;"> $SPY a few interesting charts. Nasdaq advance decline. Biggest drop since 2016. Bigger than Covid. $QQQ $AAPL $TSLA $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 22:51:10 </td>
   <td style="text-align:left;"> $AAPL is it time for Puts here? 🤔 
 
$SPY $GOOG $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 22:44:12 </td>
   <td style="text-align:left;"> $AAPL 
🍏🔜🆙🔝
Is An Apple Stock Split Likely In 2022? No, Not Without A Big Price Runup.

Feb. 18, 2022 11:53 AM ET

https://seekingalpha.com/article/4488351-is-apple-stock-split-likely-2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 22:40:21 </td>
   <td style="text-align:left;"> $AAPL $NVDA $AMD Have you watched this episode of Whats Next Wallstreet?
Be sure to like, subscribe, and click the notify button so you don’t miss any of our show drops

https://youtu.be/A0KjD8wo6Nw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 22:24:42 </td>
   <td style="text-align:left;"> $AAPL for those that missed the 20% gain on Delta airlines the past couple of months, you can have a mulligan (redo) by jumping on Air Canada. The heavy Covid restrictions north of the border are quickly lifting and the pent up demand for travel will send this stock flying high! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 22:12:45 </td>
   <td style="text-align:left;"> BEIJING NOTEBOOK: As Olympics ebb, smartphone synchronicity $AAPL $GOOG $TMUS $S $VZ https://www.billionaireclubcollc.com/beijing-notebook-as-olympics-ebb-smartphone-synchronicity/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 22:09:18 </td>
   <td style="text-align:left;"> Stock Patterns: Introduction to Technical Analysis $TSLA $AAPL $BAC $JPM $AMZN https://www.billionaireclubcollc.com/stock-patterns-introduction-to-technical-analysis/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 22:01:05 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 21:53:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Here&amp;#39;s Warren Buffett&amp;#39;s Favorite Metaverse Stock by Far https://www.stck.pro/news/AAPL/23192328 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 21:52:11 </td>
   <td style="text-align:left;"> $SPY is spy board at war with $AAPL board yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 21:38:05 </td>
   <td style="text-align:left;"> How to Profit From Solar Energy $TSLA $AMZN $AAPL https://www.billionaireclubcollc.com/how-to-profit-from-solar-energy/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 21:28:46 </td>
   <td style="text-align:left;"> Inside Facebook’s $10 Billion Breakup With Advertisers  $FB $GOOG $AMZN $AAPL $CMCSA 

https://newsfilter.io/a/582f512b2cd050e5cf88841632507a8f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 21:28:43 </td>
   <td style="text-align:left;"> Why Apple, Amazon and Google Are Uniting on Smart-Home Tech  $GOOG $AMZN $AAPL 

https://newsfilter.io/a/11aa515be76721e30b3e047c9eab2f8d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 21:28:42 </td>
   <td style="text-align:left;"> Apple Finds Itself Under Scrutiny in Washington’s Big Tech Clampdown  $AAPL $MSFT $AMZN $GOOG 

https://newsfilter.io/a/bca7b6ec6dfa3228e4471e2fb120cad6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 21:19:23 </td>
   <td style="text-align:left;"> $AAPL won’t be much money left to buy iPhones 

Thanks Biden 

https://www.live5news.com/2022/02/18/expert-warns-drivers-gas-prices-could-reach-7-per-gallon/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:58:49 </td>
   <td style="text-align:left;"> Industries That Will Never Go Away $AMZN $AAPL $MSFT $TGT $TSLA https://www.billionaireclubcollc.com/industries-that-will-never-go-away/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:48:06 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Shopify Gets Interesting At $500 https://www.stck.pro/news/AAPL/23190921 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:42:05 </td>
   <td style="text-align:left;"> How to Achieve Optimal Asset Allocation $AMZN $AAPL $TSLA $F https://www.billionaireclubcollc.com/how-to-achieve-optimal-asset-allocation/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:39:08 </td>
   <td style="text-align:left;"> How to Invest in Farming Without Owning a Farm $AAPL $TSLA $TSN $AMZN $WBA https://www.billionaireclubcollc.com/how-to-invest-in-farming-without-owning-a-farm/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:30:50 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 2/10 update presented to members at  http://elliottwave-forecast.com #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:25:25 </td>
   <td style="text-align:left;"> $AAPL trump speaks on Biden’s Great Depression </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:22:12 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 2/01 update. Showing further reaction higher taking place from the blue box area #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:16:35 </td>
   <td style="text-align:left;"> $AAPL https://www.cnn.com/2022/02/20/politics/fiona-hill-donald-trump-joe-biden/index.htmlhttps://www.cnn.com/2022/02/20/politics/fiona-hill-donald-trump-joe-biden/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:08:27 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 1/30 weekend update. Found buyers at the blue box area &amp;amp; showing reaction higher taking place from the blue box area. Longs should be risk free by now #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:07:00 </td>
   <td style="text-align:left;"> $AAPL is currently trading in the upper part of its 52 week range, outperforming the market. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:03:55 </td>
   <td style="text-align:left;"> Empirical Probability Definition $AAPL https://www.billionaireclubcollc.com/empirical-probability-definition/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:03:01 </td>
   <td style="text-align:left;"> $AAPL then managed to reach the blue box area from where buyers were expected to appear  #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 20:00:57 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 19:54:17 </td>
   <td style="text-align:left;"> $AAPL 1hr view from 1/23 Weekend update. Calling for more downside to take place #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 19:47:07 </td>
   <td style="text-align:left;"> $AAPL 1hr view from 1/14 Pre-Market update presented to members at http://elliottwave-forecast.com #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 19:42:54 </td>
   <td style="text-align:left;"> $AAPL Chart of The Day 1/12/2022 update. #Apple can see further downside https://elliottwave-forecast.com/stock-market/elliott-wave-view-apple/  #Elliottwave #Trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 19:42:13 </td>
   <td style="text-align:left;"> Invest with an outcome based approach on $AAPL. Make a fixed 12.9% (12.0% annualized) and start to lose only if $AAPL drops by more than 16.0% through 03/17/2023.

Buy 4 $135 puts
Sell 5 $145 puts
 3/17/23 expiration
https://o.oliveinvest.com/6xeifs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 19:20:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Week 8 MDA Breakout Stocks - February 2022: Short-Term Picks To Give You An Edge https://www.stck.pro/news/AAPL/23188381 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 18:29:44 </td>
   <td style="text-align:left;"> $AAPL below 150 if it dips then load 200C leaps! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 18:20:35 </td>
   <td style="text-align:left;"> $AAPL $TSLA $NFLX  
 
Account Challenge Update 
Start Date: Feb 2, 2022   
Starting Balance: $18,800   
Current Balance: $50,637   
Goal: $100,000 by end of February.   
Strategy: Swing Trade Options, Stocks   
   
Watch out for the next play! http://stock.coordinatetrading.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 17:39:41 </td>
   <td style="text-align:left;"> $AAPL what are some competitors of Stocktwits? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 17:02:59 </td>
   <td style="text-align:left;"> Contrasting My View With The Great #Puru Saxena $GOOGL $AAPL $GOOG $MSFT $FB https://talkmarkets.com/content/us-markets/contrasting-my-view-with-the-great-puru-saxena?post=345396 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 17:00:33 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 16:29:43 </td>
   <td style="text-align:left;"> $AAPL this is our AI’s take here last Monday, let’s see what Tuesday brings 🤔 

👉🏻 stocksignal.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 16:09:33 </td>
   <td style="text-align:left;"> $AAPL the Apple empire exist as its own world and country.  You can have wars, invasions, inflations, infections (covid), it’ll doesn’t give a sh!t.  And keeps doing it’s own thing.  PT will hit $200+ EOY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 15:54:25 </td>
   <td style="text-align:left;"> $FSR $AAPL Fisker is a Lifestyle Brand in the Making, Just Like Apple https://fiskerati.com/fisker-ocean/fisker-is-a-lifestyle-brand-in-the-making-just-like-apple/?swcfpc=1 #Fisker #EV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 15:26:37 </td>
   <td style="text-align:left;"> $AMD $AAPL $BTC.X  $TSLA  official Twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 14:48:56 </td>
   <td style="text-align:left;"> $AAPL PT...$154 !!!!🤑🤑🤑🤑🤑🤑🤑 $IWM PT...$188 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 14:44:04 </td>
   <td style="text-align:left;"> $AAPL https://indianexpress.com/article/world/russia-ukraine-news-live-updates-putin-military-nato-us-china-7779260/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 14:43:48 </td>
   <td style="text-align:left;"> $AAPL  Out of the 745 other times AAPL was down 1.4% during a trading day, 52% of the time it traded higher by the next day&amp;#39;s market close. #CoinFlip link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 14:40:56 </td>
   <td style="text-align:left;"> $AAPL think Russia should make up their mind to pull out or just take over Ukrainian and end this daily BS news on media and White House and In Europe politicians guessing game, will they attack or not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 14:36:33 </td>
   <td style="text-align:left;"> $AAPL https://www.foxnews.com/live-news/russia-ukraine-cyberattacks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 14:32:30 </td>
   <td style="text-align:left;"> $ASTS partnering with Vodafone while $GSAT partners with $QCOM and $AAPL  you tell me who the real winner will be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 14:20:39 </td>
   <td style="text-align:left;"> anyone heard the words “Covid” or “inflation” recently? VANISHED

 $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 14:08:58 </td>
   <td style="text-align:left;"> $SHOP $MELI $SE $TSLA $AAPL 
PE ratio 
Which company can sell their own products like Apple does with iPhone? 

Shop: 103
Meli: 642 😂
SE: over 1500?
Tesla: 129
Apple: 28 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 14:00:47 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 13:43:36 </td>
   <td style="text-align:left;"> $SPY $AMD $QQQ $AAPL 
Updated:
Russia could begin attack on Ukraine at any time . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 13:35:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 8.00, indicating great health for $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 13:33:27 </td>
   <td style="text-align:left;"> $AAPL you guys don’t think it’s USA stock market not Russian apple to up to 170 on Tuesday ⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 13:27:23 </td>
   <td style="text-align:left;"> $AAPL looks like it’s going to 154-157 zone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 13:24:50 </td>
   <td style="text-align:left;"> $IWM 🤑🤑🤑🤑🤑🤑🤑 $AAPL  
To trade/invest in the financial markets it is absolutely necessary to create your OWN plan based on your OWN analysis. A trade should be executed from a position of POWER and confidence not from UNCERTAINTY or based on FEELINGs. The OPINIONS of some EXPERTS somehow gets the message across that UNDERMINES your OBJECTIVE thinking, and it is ultimately the RECOMMENDATIONs as well as THEMSELVES (i.e. blame the market&amp;#39; FUD, MMs&amp;#39;, etc.) that is the trader’s/investor&amp;#39;s WORST ENEMY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 12:50:55 </td>
   <td style="text-align:left;"> $AAPL We’re done with all the liberal bullshit!!! https://rumble.com/vv97rh-parents-are-taking-back-the-wheel-father-gives-unforgettable-anti-crt-speec.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 12:47:53 </td>
   <td style="text-align:left;"> Everything coming together. Over 1000% gains this week. STUDY STUDY STUDY

 $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 12:42:41 </td>
   <td style="text-align:left;"> $AAPL INVASION INVASION SELL YOUR SHARES SELL THEM CHEAP TOO. SELL THEM ALL YOU EFFIN MASSIVE IDIOTS LOL. wow and when you wake up and realize you gave away profit to a fake news war thanks to a fake puppet president don&amp;#39;t get MAD. Just blame it on your own stupidity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 12:40:42 </td>
   <td style="text-align:left;"> $AAPL https://www.androidpolice.com/apple-employees-android-phones-unionization-plans-secret/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 12:38:25 </td>
   <td style="text-align:left;"> $AAPL the one thing that should have bears worried here us. Warren Buffet is bullish on AAPL. And he always has been. So what that means is basically AAPL will never and I mean NEVER stay in a bear trend for very long. Only an idiot would believe otherwise. If you are in puts or short. My advice to you is TAKE PROFIT IMMEDIATELY if this stock dips. Don&amp;#39;t flirt with Satan he will destroy you. This is ALWAYS BULLISH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 12:20:02 </td>
   <td style="text-align:left;"> $AAPL Tuesday we will see a rebound back to $175. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 11:27:47 </td>
   <td style="text-align:left;"> $AAPL  Berkshire  Hathaway places APPL as the Best Managed Co.  $200++ https://www.macrumors.com/2022/02/18/apple-is-ungodly-well-managed/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 11:00:53 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 10:42:47 </td>
   <td style="text-align:left;"> $WIMI 💎CORE Areas: Hologram has core intellectual property rights and is not restricted by overseas companies. WiMi Hologram has approximately 4600 AR holographic contents, 325 software copyrights and 195 registered patents.✨✨
 WiMi Hologram is committed to using holographic technology to meet the entertainment and business needs of customers and end users. 🔥🔥
Recent major breakthrough in Sensors. Holographic display, Augmented Reality $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 10:41:49 </td>
   <td style="text-align:left;"> $SPY Saturday night and this mfkr still hasn&amp;#39;t made a fkn move 🙄 I swear if Tuesday comes and he hasn&amp;#39;t invaded or gone the fk home....
I&amp;#39;m thinking he makes a move Monday. Is a holiday here in the US, plus the Olympics end tomorrow.
$QQQ $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 10:32:49 </td>
   <td style="text-align:left;"> $AAPL should invasion start can’t the US government create an emergency order to tell Apple and Google to disable all of its devices and operating systems in Russia? That would get Putin attention </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 10:26:16 </td>
   <td style="text-align:left;"> $AAPL $NVDA $FB Did you catch this latest episode of Whats Next Wallstreet? You won’t want to miss it… like, subscribe, and click the alerts tab to get all of our valuable content. Enjoy 

https://youtu.be/pZIpZkNo99w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 10:24:12 </td>
   <td style="text-align:left;"> $AAPL https://www.nbcnews.com/news/world/russia-ukraine-invasion-fears-separatists-military-mobilization-putin-rcna16937 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 10:23:52 </td>
   <td style="text-align:left;"> How to Start a Private Foundation $TSLA $AAPL https://www.billionaireclubcollc.com/how-to-start-a-private-foundation/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 10:20:52 </td>
   <td style="text-align:left;"> $AAPL I was going to keep holding this but you seriously have to be gullible to think that any tech stocks are going to do good by you this year lol. Wake up people... INFLATION. WAR. A PRESIDENT THAT LOOKS LIKE HE&amp;#39;S DEAD AND HAS NO IDEA WHAT YEAR IT IS...  
 
I&amp;#39;M BUYING GOLD AND SHORTING EVERYTHING. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 10:05:07 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-18 Largest Trades Data: 
https://www.youtube.com/watch?v=gmS_wGOpdhM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 09:58:24 </td>
   <td style="text-align:left;"> Mezzanine Financing Definition $AAPL https://www.billionaireclubcollc.com/mezzanine-financing-definition/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 09:56:48 </td>
   <td style="text-align:left;"> $AAPL can’t wait  🥶I want that pump and dump. Gonna hold weeklies starting Tuesday for that 1000% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 09:56:48 </td>
   <td style="text-align:left;"> $AAPL 160 next. Very technical. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 09:54:10 </td>
   <td style="text-align:left;"> Benzinga Bulls And Bears Of The Past Week: Xpeng $XPEV, Disney $DIS, Apple $AAPL, Meta $FB, Tesla $TSLA, Nvidia And More https://www.billionaireclubcollc.com/benzinga-bulls-and-bears-of-the-past-week-xpeng-disney-apple-meta-tesla-nvidia-and-more/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 09:35:03 </td>
   <td style="text-align:left;"> $AABB $TSLA $AAPL $MSFT $FB All started with a vision. Each vision were different from one another but the investors who each enveloped the visions of $TSLA $AAPL $MSFT $FB with investment dollars,especially during the infancy stages made massive ROI money. $AABB Vision for AABBG.X Gold becoming the new global standard of exchange backed by gold (mine to token) will take the world by storm in 2022. Gold will breakout and S.America will become the first hub for mass adoption for AABBG.X including  merchants accepting  AABBG.X gold backed cryptocurrency. $AABB has Record Profits/Record Gold/Gold Mines/No Debt/Global Exchange/share retirements/Dividends! The estimation is 4 Billion uncovered &amp;#39;&amp;#39;naked short&amp;#39;&amp;#39; shares. MOASS in 2022 BOOM TOWN https://www.benzinga.com/news/21/07/21884788/inflation-gold-crypto-is-asia-broadband-the-next-gamestop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 09:25:35 </td>
   <td style="text-align:left;"> $SPY  $AMD $QQQ $AAPL 
Market is worried about the possibility of Hyperinflation 
Most importantly
The Fed can’t fight it because of external factors
Supply Chain Constraints from China and Thanks to COVID and Omicron 

Yes Russia Ukraine  situation adds to the Market Anxiety </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 09:16:22 </td>
   <td style="text-align:left;"> $SPY Not sure if these bears even care about their puts, maybe they just want world war 3 to happen and we all die from nukes.   I wouldn&amp;#39;t put it past these greedy bears to wish harm to normal humans. you can&amp;#39;t make this up people!  $M $AMZN $GOOG $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 09:01:18 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:49:49 </td>
   <td style="text-align:left;"> $AAPL https://www.benzinga.com/node/25731437 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:48:15 </td>
   <td style="text-align:left;"> $FSR $AAPL Fisker is a Lifestyle Brand in the Making, Just Like Apple https://fiskerati.com/fisker-ocean/fisker-is-a-lifestyle-brand-in-the-making-just-like-apple/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:45:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

Hehe!

——— </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:45:08 </td>
   <td style="text-align:left;"> I really be catching so many Ls sometimes especially on options😳 but it’s okay I’ll never quit because I love trading and I even actually enjoy market drama way more than Netflix 🍿👀. I can do this for years. I know it will pay off in the end☺️

$spy $aapl $tsla $arkk $btc.x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:34:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 8.00, indicating great health for $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:31:06 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOGL …..my 3 trick pony that will take me to the top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:25:45 </td>
   <td style="text-align:left;"> $O Adding 5K more on Monday. This and $AAPL are the only stocks I will keep in my portfolio outside of $GOLD and $GLD during these economic conditions. The monthly dividend will pay my mortgage one day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:22:48 </td>
   <td style="text-align:left;"> $AAPL world war 3, Russia, China, Ukraine, Taiwan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:21:06 </td>
   <td style="text-align:left;"> $AAPL https://appleinsider.com/articles/22/02/19/apple-has-a-clear-path-to-1t-in-revenue-by-2030 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:14:34 </td>
   <td style="text-align:left;"> Market Risk Definition $AAPL $TSLA https://www.billionaireclubcollc.com/market-risk-definition/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:11:15 </td>
   <td style="text-align:left;"> Income-tax phaseout up for debate in long-poor Mississippi $SPY $AAPL $AMZN $LCID https://www.billionaireclubcollc.com/income-tax-phaseout-up-for-debate-in-long-poor-mississippi/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:09:47 </td>
   <td style="text-align:left;"> $AAPL 

Going much lower … time to sell apple .

Stocks going lower …: $SPY $QQQ $DJIA invasion will be in Taiwan , 

https://www.defensenews.com/global/asia-pacific/2022/02/08/us-approves-support-deal-with-taiwan-for-patriot-missiles/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 08:06:19 </td>
   <td style="text-align:left;"> What to look for in Buffett’s annual letter $AAPL $ATVI $MSFT https://www.billionaireclubcollc.com/what-to-look-for-in-buffetts-annual-letter/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:50:15 </td>
   <td style="text-align:left;"> $AAPL man I wish it was Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:34:36 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $ROKU 

https://twitter.com/fxhedgers/status/1495178584209592320?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:32:24 </td>
   <td style="text-align:left;"> $AAPL 150k troops and no pics or vids yet😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:30:41 </td>
   <td style="text-align:left;"> Opinion: This never-before-seen evidence shows value stocks have beaten growth stocks for a lot longer than we knew $AMC $GME $AAPL $ZMZN $NVDA https://www.billionaireclubcollc.com/opinion-this-never-before-seen-evidence-shows-value-stocks-have-beaten-growth-stocks-for-a-lot-longer-than-we-knew/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:24:11 </td>
   <td style="text-align:left;"> 2 week free trial 🤷🏾‍♂️ if your service is lackin, we’re not 🎯 especially in this market. This is day traders paradise 

$AAPL $QQQ $SPY $ROKU $MU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:22:50 </td>
   <td style="text-align:left;"> $AAPL     🍏👇👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:20:54 </td>
   <td style="text-align:left;"> $AAPL Hopefully just drills 🙏🙏🙏

https://www.reuters.com/world/europe/russia-belarus-end-drills-planned-officials-2022-02-17/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:16:47 </td>
   <td style="text-align:left;"> $AAPL $MSFT $AMZN An interesting date on Tuesday if written in the European format. 
Not sure what Putin will do on this date. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:14:20 </td>
   <td style="text-align:left;"> Equity Sentiment Weekly Recap: $AAPL is the #1 stock that institutions traded this week with 279.8K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:12:36 </td>
   <td style="text-align:left;"> Nobody finds it interesting that the SAME week of the “Germany Security Conference” where 30 of the top nations of the world gather, is the same days… Russia Putin mobilizes 150,000 troops around Ukraine to get their attention??? • Putin doesn’t want war &amp;amp; sanctions, he wants a deal… he won’t invade… all show.

💯🤡 $SPY $QQQ $TSLA $AAPL $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:11:27 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG biden got to goooo!!! Tag Trump back in!!! He knows how to make a economy shine!! Who ever voted for Biden is a retard and needs to leave America </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 07:00:06 </td>
   <td style="text-align:left;"> Swing Trading With Moving Averages $SPX $MSFT $FB $AAPL $AMZN https://talkmarkets.com/content/stocks--equities/swing-trading-with-moving-averages?post=345373 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 06:59:02 </td>
   <td style="text-align:left;"> $AMD $AAPL $QQQ $SPY
Paying higher fuel prices 4.30 per gallon 
for Premium 
Consumer Discretionary Income will go down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 06:49:24 </td>
   <td style="text-align:left;"> Intel $INTC needs help to compete against $AMD and Nvidia $NVDA?- Protocol

$AAPL | $TSLA 

Intel had a major shareholder meeting. It did not go smoothly.

 https://www.protocol.com/enterprise/intel-shareholder-meeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 06:47:32 </td>
   <td style="text-align:left;"> 222222 is coming, and it is the Tuesday when we will skyrocket  
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 06:36:23 </td>
   <td style="text-align:left;"> $GOOGL guys we had a good(actually bad for me these past few months) run…but I think Russias going to attack I’m pretty sure I’m pulling. My money out sometime next week it’s been fun to be here with you guys but Biden is just destroy in g everything no money to be Made in the market anymore $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 06:32:05 </td>
   <td style="text-align:left;"> $AAPL - Apple may outdo Gopro Inc (… https://www.macroaxis.com/invest/pair-correlation/AAPL/GPRO/Apple-vs-Gopro #portfolio_prospective #better_portfolio #diversify </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 06:10:45 </td>
   <td style="text-align:left;"> $AAPL $LOW$LMND $JMIA $RBC  
 
Most Anticipated Earnings Next Week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 05:55:33 </td>
   <td style="text-align:left;"> $PTON https://www.profgalloway.com/apple-thief/  
Bestselling author &amp;amp; Business Professor Scott Galloway tells why  #Apple $AAPL to own $HOOD #Robinhood &amp;amp; #Peloton #PTON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 05:50:37 </td>
   <td style="text-align:left;"> 🐻Thesis  for Stonks to go lower 

$AMD $AAPL $NVDA $QQQ $SPY 

Market FED training wheels come Off soon next Month 3/2022

No more liquidity from the FED

FED has a big problem dealing with the Highest Inflation in decades trending towards Hyper Inflation.
The FED has to put on the brakes to slow the US Economy down by raising Rates possibly 7 times in 2022 according to JP Morgan Chase.
Higher borrowing costs for personal loans and mortgages and consumer auto loans and commercial loans and corporations and small businesses.

Notice Head and Shoulders Pattern Development on SPY Weekly Chart

Is the Market Correction primarily about Russia Ukraine or is it about the concern of Hyper Inflation? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 05:47:15 </td>
   <td style="text-align:left;"> $AAPL systematic drop algorithms is the killer of good earnings 🤙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 05:27:54 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG forget stupid real estate!! Stocks the way to goooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 05:23:48 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 05:21:23 </td>
   <td style="text-align:left;"> $DCFC If you’re not too careful about what you pick, Tuts &amp;amp; 🤖 will eat you alive you damn fools. Pick only the best from the rest! $ABB $AAPL $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 05:13:49 </td>
   <td style="text-align:left;"> How to Avoid Outliving Your Reverse Mortgage $AAPL $WFC $C $JPM $BAC https://www.billionaireclubcollc.com/how-to-avoid-outliving-your-reverse-mortgage/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 05:11:33 </td>
   <td style="text-align:left;"> Be Fearful When Others Are Greedy  $KO $AAPL https://www.billionaireclubcollc.com/be-fearful-when-others-are-greedy/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 05:11:28 </td>
   <td style="text-align:left;"> $AAPL oversold and undervalued.  It should be over $200 by now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 05:03:30 </td>
   <td style="text-align:left;"> How does this affect your portfolio? $AAPL in Uptrend: RSI indicator exits oversold zone. View odds for this and other indicators: https://srnk.us/go/3429071 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:59:21 </td>
   <td style="text-align:left;"> $AAPL pretty sad that a country like Russia has full control over the American market. You people are pathetic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:54:20 </td>
   <td style="text-align:left;"> $SPY $AMD $AAPL $NVDA $QQQ 
Mkt FED training wheels come Off
Soon next Month 3/2022
Translation:    No More Liquidity from FED
Weekly Head and Shoulders development on $SPY =Lower Lows for the Market and Stonks go lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:52:07 </td>
   <td style="text-align:left;"> How did you finish last week ? Red or green ? Comment below 👇 $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:51:22 </td>
   <td style="text-align:left;"> Can Moving into a Higher Tax Bracket Cause Me to Have a Lower Net Income? $SPY $TSLA $AAPL $FB $SNAP https://www.billionaireclubcollc.com/can-moving-into-a-higher-tax-bracket-cause-me-to-have-a-lower-net-income/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:41:24 </td>
   <td style="text-align:left;"> $AAPL Business Insider 
Bill Gates says the chances of catching a severe infection from COVID-19 are dramatically lower but he believes another pandemic is likely …..n.   https://www.yahoo.com/news/bill-gates-says-chances-catching-124750817.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:29:57 </td>
   <td style="text-align:left;"> Rental Property Tax Deductions  $STAG $PBA $EXR $CUBE $AAPL https://www.billionaireclubcollc.com/rental-property-tax-deductions/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:26:40 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/UTAjOmBvaZE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:26:31 </td>
   <td style="text-align:left;"> $AAPL The Gramm-Leach-Bliley Act of 1999 (GLBA) https://www.billionaireclubcollc.com/the-gramm-leach-bliley-act-of-1999-glba/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:15:28 </td>
   <td style="text-align:left;"> $AMP.X on $AAPL NEWS this past week.

They will upgrade it this year “Flexa System”.
Link / SC👇🏻

https://apple.news/ADnSggx9jTnqHxsQctsVGWA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:13:45 </td>
   <td style="text-align:left;"> $AMD $NVDA $MRVL $AAPL in the same basket (Taiwan) Who wants to put all eggs in one basket? $INTC  buying more for only this reason </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:13:26 </td>
   <td style="text-align:left;"> $AMP.X $AAPL runs on the old payment system and charges fees. They have been looking to update there system. Flexa is up to date and the fee’s are only 1%, which would save companies millions to billions of money. Flexa is POWERED by the AMP TOKEN. 
Just started in late 2020, really cheap this is just the beginning!

Check the fee’s here for merchants from each card!👇🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:06:04 </td>
   <td style="text-align:left;"> $AABB $TSLA $AAPL $MSFT $GOOG Hedge funds have analysts able to do more DD than the average investor. The fact that hedge fund bashers have been bashing $AABB 365 24/7 is a HUGE tell and this has been going on for over a year since that the stock has gonu up 3,500% at one point it was up 22,500% since last February hedge funds like CDEL have been shorting the entire OTC market down after pumping them all to ATH&amp;#39;s! However $AABB OTC has Record Profits/Record Gold/No Debt/Global Exchange/Gold mines/Share retirements/Dividends/1st to market Global Gold currency system/ The estimation is 4 BILLION uncovered &amp;#39;&amp;#39;naked short&amp;#39;&amp;#39; shares which will be covered in 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:05:07 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-18 Largest Trades Data: 
https://www.youtube.com/watch?v=gmS_wGOpdhM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:04:12 </td>
   <td style="text-align:left;"> $AAPL  high inflations money is worth shiiiitttt now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 04:03:07 </td>
   <td style="text-align:left;"> $AAPL holy shiitttt, with high inflation rate of 20-30% this year and last year 167 is really worth 125 if you count on the freaking inflation rate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 03:51:46 </td>
   <td style="text-align:left;"> $AAPL 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 03:47:07 </td>
   <td style="text-align:left;"> Opinion: Apple stock will change an index fund’s performance, depending on this one crucial investment decision $AAPL https://www.billionaireclubcollc.com/opinion-apple-stock-will-change-an-index-funds-performance-depending-on-this-one-crucial-investment-decision/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 03:39:42 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPL Happy Saturday everyone! Hopefully you&amp;#39;re taking some time off to enjoy the weekend. It was a choppy week and we&amp;#39;ll wait and see how tensions in Russia/Ukraine play out. Do you think anything will happen before markets open on Tuesday? 
 
I like to use this time to step back, reset, and prepare for the week ahead (DD, news, rumors, etc.) 
 
One of the most important things to track is social momentum and social sentiment. When a ticker starts to gain traction, more people see it , and it can start to take off. When this happens it usually leads to increased price action and volume. Remember, at the end of the day the market is set by whatever price some is willing to buy and sell at.  
 
This is why we build this social sentiment dashboard, so you can stay ahead of the trends an movements. It is one of the most useful indicators for investing and trading. Check it out - happy to answer any questions. https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_202202019 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 03:38:12 </td>
   <td style="text-align:left;"> $UPST CEO interview:

- Buyback program: we’re a very profitable biz w/o a need of heavy balance sheet. Does it for economic benefit
- Higher interest rates: we aren’t very sensitive to it; not worried
- Innovations: like to be $AAPL-like w/ a mix of $GOOG 

https://www.thestreet.com/video/how-upstart-ceo-apple-google-examples-guide-company </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 03:34:29 </td>
   <td style="text-align:left;"> $spy $qqq $aapl $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 03:33:54 </td>
   <td style="text-align:left;"> $AABB $SPY $SPX $QQQ $AAPL Precious metals and Gold Miners are set to have breakouts watchlist $AABB jr Gold miner with Record Profits and the 1st to market Global Gold backed cryptocurrency coin (mine to token) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 03:32:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 03:20:48 </td>
   <td style="text-align:left;"> $AAPL trump has hundred’s of millions of dollars of loans coming due. With his house of cards about to come crashing down, now I realize why he illegally stole top secret classified documents from the White House. It wouldn’t surprise me if he uses those classified documents in exchange for loans from Putin or some other enemy of the American people. Folks, he’s a snake and will stop at nothing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 03:13:38 </td>
   <td style="text-align:left;"> $UAL  $JBLU $AAPL https://www.axios.com/zelensky-ukraine-munich-security-conference-russia-4f35590e-a9d2-46af-be0e-6bc849283b61.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 03:11:56 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 02:56:47 </td>
   <td style="text-align:left;"> $AAPL total bullshit the apple watch fitness doesn&amp;#39;t take in to account how hard I pound my wife and girlfriend for their fitness goals. Tim, get it together bro! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 02:53:44 </td>
   <td style="text-align:left;"> $AABB $DOGE.X Coin hit a 90B MC at .73 cents  $RIOT went from .51-$70 in 6 months in 2020 on 2.2M Gross profits. $AAPL &amp;amp; $MSFT started their infancy stages in tiny garages. $AABB AABBG.X  The right product (Gold backed cryptocurrency coin) (mine to token) at the right time. 2022 BOOM TOWN with Record Profits/Record Gold/No Debt/Gold Mines/Share retirements/Dividends/Global Exchange/4 BILLION estimated uncovered &amp;#39;&amp;#39;naked short&amp;#39;&amp;#39; shares the 2022 MOASS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 02:52:05 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 02:42:10 </td>
   <td style="text-align:left;"> $SPY $ARKK $AAPL $WMT $GOOG 

https://www.rt.com/russia/549692-invasion-fake-news-reputation/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 02:41:33 </td>
   <td style="text-align:left;"> $AAPL get ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 02:33:22 </td>
   <td style="text-align:left;"> $PLTR In $AAPL&amp;#39;s 40 years in the stock market it has 2000xed. How is this possible? Well, it has gone through so many phases of bullishness and bearishness. It&amp;#39;s seen a lot of drops and experienced a lot of naysayers who didn&amp;#39;t think it could achieve its vision. Palantir will very likely be a trillion dollar company eventually. In the meantime, it&amp;#39;s going to experience a lot of naysayers who don&amp;#39;t think the company can achieve its growth goals. I bought Palantir at $38. Does that make me an idiot? Maybe, but I bought it where I thought it was worth a lot more than its valuation. The general public now disagrees. One thing I&amp;#39;m certain about is that the general public is completely idiotic. Hence why 40 years ago shares of apple were selling for a penny on the $20. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 02:26:09 </td>
   <td style="text-align:left;"> Sweep Options Activity Weekly Recap: $AAPL is the #1 ticker with sweep activity that institutions traded urgently this week options with 213.8K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 02:15:37 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG balls deep!!! Like mandeepppppp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 02:05:42 </td>
   <td style="text-align:left;"> $GOOGL those wishing Google to tank will not only see their entire portfolio go to zero, they will also go bankrupt. If Google tanks, the entire market will go with it…..sorry to break the news to you but Google is the Government and it runs everything. Every Big Tech company uses Google to sell their products. Go ahead and Google a product, it will show the product listed on $AMZN or take your pick Big Tech company 😂 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 01:46:38 </td>
   <td style="text-align:left;"> $SPY Joe please stop the dramatics. We all know you are going to “swoop in and save the day” your numbers are so bad, you had to do something. No invasion is happening $UVXY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 01:40:58 </td>
   <td style="text-align:left;"> $QQQ $TSLA $AAPL 
Russia  is fake news. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 01:27:51 </td>
   <td style="text-align:left;"> Apple is Berkshire’s largest stock holding, but Buffett and Co. own a bigger share of these companies

$AAPL $KHC $MSFT

https://www.marketwatch.com/story/apple-is-berkshires-largest-stock-holding-but-buffett-and-co-own-a-bigger-share-of-these-companies-11644962524?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 01:11:27 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NVDA $UVXY 

My thoughts on the stock mkt next week ... 

When I  alerting everyone on ST back in early Feb 2020 of a mkt crash coming (SEE POST BELOW), the mkt was at all-time h8ghs. First day of 2022  I alerted subscribers of  an incoming mkt correction. 

The game plan hasn&amp;#39;t changed. Institutions still need retail investors to &amp;quot;btfd&amp;quot;. It&amp;#39;s the only way they can unload without crashing the mkt.  It is easy to do - prop up the mkt &amp;quot;Generals&amp;quot; - AAPL, MSFT, TSLA, NVDA, GOOGL, etc and create the illusion that the mkt is healthy. This game began long before January. 

Many still contunue to buy the rallies. They continue to fall into the same trap of early 2020

 I called the crash two years ago. I called the sharp correction to start 2022. My members know this and have benefited from this insight. When it&amp;#39;s time to get bullish from my standpoint, they will know as well. 

If interested in subscribing, email me at jessielivermore1929@gmail.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 01:01:31 </td>
   <td style="text-align:left;"> 🔥 CPU Retail Sales Week 7

$AMD ↗️: 1280 units sold, 53.44%, ASP: 308.3 (Euro)
Intel / $INTC: 1115, 46.56%, ASP: 281.78

AMD revenue: 394&amp;#39;623.5, 55.67%
Intel: 314&amp;#39;183.45, 44.33%

#AMD #AMDRyzen #Intel

$AAPL $NDVA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 00:50:41 </td>
   <td style="text-align:left;"> $AAPL Glad I bought aapl when it was cheap, held, and didn’t add as it went up. It’s the only thing keeping my portfolio afloat right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 00:38:50 </td>
   <td style="text-align:left;"> $QQQ NASDAQ death cross, last time it hit it was post covid reaction and it ran non-stop 1.5 years. Looks like a new bull run is about to start. $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 00:22:08 </td>
   <td style="text-align:left;"> Facebook is a steal at these levels, ignore the retarded brain dead bears! 
  
https://www.fool.com/investing/2022/02/19/3-reasons-to-buy-meta-platforms-stock-and-never-se/ 
  
$FB $MSFT $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 00:16:04 </td>
   <td style="text-align:left;"> $AAPL This should be down way more I want to load up 😝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-20 00:15:57 </td>
   <td style="text-align:left;"> 1 of 11 $AAPL $AMGN $AXP Daily and 30 min charts of the DJIA Components with the SSI indicator, a proprietary indicator based exclusively on the eSignal platform, are posted here weekends … see 2/11 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 23:39:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $GOOGL $MSFT No invasion over long weekend.. Markets Gaps up on tues .. Investors unloaded last 2 days coz to reduce risk.. .. Putin is not that dumb to crash his economy with inflation at 10%.. oil is 70% of his revenues.. plus killing Ukrainians is unpopular in Russia many of them have relatives </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 23:33:16 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 23:33:13 </td>
   <td style="text-align:left;"> $AAPL Tim Cook wants that 100 million for his hard…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 23:24:03 </td>
   <td style="text-align:left;"> $AMD ↗️ $AAPL $AMZN $BTC.x $TSLA 

“I have no doubt the Feds want &amp;quot;to get&amp;quot; @citsecurities since Ken Griffin is one of the biggest GOP fundraisers and the bane of @ewarren who is @GaryGensler&amp;#39;s master (1/3). BUT a few things to consider. Citadel&amp;#39;s hedge fund doesn&amp;#39;t do activist short selling. The things the Feds…
THREAD 🧵 &amp;gt;
 https://twitter.com/cgasparino/status/1495048357332635651?s=12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 23:07:39 </td>
   <td style="text-align:left;"> $AAPL 1.67% down since we posted the Short signal. Easy money on this play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 23:03:31 </td>
   <td style="text-align:left;"> $AMD $NVDA $AAPL $QQQ $SPY 
Again people be careful. 
NASDAQ WKLY🐻Outside Week 
LowerLows likely for Market and Nasdaq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 22:57:57 </td>
   <td style="text-align:left;"> $AAPL Many of these companies that enjoyed a huge runup in share price during the pandemic  just don&amp;#39;t seem to be a valued correctly anymore, but where else do these massive pensions, annuities, 401K funds, etc. have to put their money?  Can&amp;#39;t stuff it in the mattress. 
 
That said, AAPL as good a place as any, but I have to hold my nose every time I buy it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 22:36:32 </td>
   <td style="text-align:left;"> $AAPL $FB $SPY 

Since President Biden took office, Taliban is back and stronger then ever. China is backing away from trade deals and now  Russia is invading remaining Ukraine. Not to mention, Iran will soon be able to do as it pleases with trade and economic embargoes lifted. All so called US foreign &amp;quot;enemies&amp;quot; are making drastic  moves.  

Not necessarily saying it&amp;#39;s all Biden&amp;#39;s fault and that he has to interfere with activities on foreign soil as people are free to make their own choices, but the optics sure don&amp;#39;t look good for him.  Sadly things will get much worse, and we are still going through a pandemic. 

Never let a crisis go to waste... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 22:31:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 8.00, indicating great health for $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 22:23:16 </td>
   <td style="text-align:left;"> $AAPL once apple breaks it’s uptrend line all hell will break loose, only big name which hasn’t done it yet, expect a fb/shop waterfall and an overall bear market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 22:19:17 </td>
   <td style="text-align:left;"> Weekend Market Recap for Friday 2/18/2022 for trending #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/aEpoId9B8O4

$AAPL $AMD $TSLA $RBLX $RIVN
Tech needs to wake up soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 22:11:20 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $NVDA $ABNB 

US Defense Secretary Lloyd Austin says Russia is moving to conduct an attack on Ukraine.

https://edition.cnn.com/europe/live-news/ukraine-russia-news-02-19-22-intl/h_672cdcbb430f235abd3705d642b56b3b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 22:07:42 </td>
   <td style="text-align:left;"> $AAPL how’s it feel letting another country control our market? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 22:06:32 </td>
   <td style="text-align:left;"> $AAPL opening over $175 tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 22:03:06 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : How To Retire With A Million In 10 Years And Live Off Dividends https://www.stck.pro/news/AAPL/23142412 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 22:01:06 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 21:58:58 </td>
   <td style="text-align:left;"> $MSFT or $AAPL which one should I buy??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 21:43:42 </td>
   <td style="text-align:left;"> https://stocktwits.com/biotech99/message/437768636 $LMT $AAPL $BA $DIS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 21:41:54 </td>
   <td style="text-align:left;"> $SPY so, Olympics end tomorrow, Monday is presidents day in the US... Hum.... Nice symbolic day 🤔
$QQQ $AAPL $AMD $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 21:41:25 </td>
   <td style="text-align:left;"> $NLST Found a similar case where Apple had a patent infringement case with $VHC and $RPXC operated as a proxy... $RPXC was denied IPR because $AAPL was  found a &amp;quot;Real Party-In-Interest&amp;quot; 😃😃😃💪💪💪

https://www.ratnerprestia.com/2014/07/21/uspto-addresses-meaning-of-real-party-in-interest-for-inter-partes-review/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 21:34:14 </td>
   <td style="text-align:left;"> FAIL to go long-  
QNET- NASDAQ INTERNET INDEX PNQI is the etf- $NDX $QQQ   
  
look for a trendline break after months to get long- all the FANG FB $AAPL NFLX $GOOGL / software $IGV growth here to end the basing.  
  
tradingview.com/chart/QNET/... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 21:33:30 </td>
   <td style="text-align:left;"> $SPY $tsla $aapl $hood </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 21:22:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $AAPL $TSLA It&amp;#39;s funny how &amp;quot;woke&amp;quot; liberals in San Francisco think they somehow have a free pass to hijack school districts and displace education as the #1 priority with racial justice initiatives 
 
Changing the names of schools and eliminating merit-based admissions becuz &amp;quot;too many Asians are getting in&amp;quot; does NOT take priority over reopening the schools and helping parents get their kids back in school so they can go to work and earn a living! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 21:08:21 </td>
   <td style="text-align:left;"> SweepCast observed: $AAPL with Unusual Options Activity Alerted on $165 CALL Expiring: 02/18/2022 worth 764K🐂  Check out Premium Room or SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 20:57:19 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPL is a bloated, Ponzi induced, diabetic bull sugar coma. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 20:50:54 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 20:50:14 </td>
   <td style="text-align:left;"> $AAPL Who watched the new series on AppleTV “SEVERANCE” What an awesome show! I believe this is going to be a HUGE hit! 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 20:49:14 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Looking To Invest Like Warren Buffett? Here Are His Top 5 Holdings Now￼ https://www.stck.pro/news/AAPL/23140345 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 20:44:16 </td>
   <td style="text-align:left;"> $AAL Wow!  TSA Throughput yesterday was 2,241,123!!  326,749 more than the previous Friday!!  This thing is set to rip higher, will it be Tuesday?  New plane was very $AAPL I phone friendly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 20:29:20 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #2 stock that institutions are trading with 58.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 20:07:55 </td>
   <td style="text-align:left;"> $AAPL 24 of 100 StockTwits member requested charts in 60 minutes and in no particular order. No notes on charts, because the goal is not to lead you to a bullish or bearish conclusion, but to stimulate a technical conversation.   
   
Make sure to &amp;quot;LIKE&amp;quot; the charts that you want to see again next week.  The charts with the fewest number of &amp;quot;LIKES&amp;quot; will be removed from the 100 and replaced with other Stocktwits member requested charts.  
    
If you would like to request a chart for next week please follow this link and post it there. https://stocktwits.com/Troutter/message/437773489 
     
To view the entire list of this week&amp;#39;s 100 tickers visit my Stocktwits profile page.  
      
This Week&amp;#39;s Quote: &amp;quot;Amateurs think about how much money they can make. Professionals think about how much money they could lose.&amp;quot;  -Jack Schwager  
  
My comments and charts should NOT be construed as trading or investment advice. I&amp;#39;m not affiliated with Stocktwits and I do this just for fun.  
Let&amp;#39;s get the conversation started!    
Troutter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 19:17:02 </td>
   <td style="text-align:left;"> $SPY $BTC.X $FB $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 18:54:47 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #3 ticker with sweep activity where institutions are trading options urgently with 40.7K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 18:27:33 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB $AMZN $TSLA Till the End of the day 100,000 people will cross the border to Russia. War is over the corner ? &amp;quot;More than 25,000 people are already evacuated from Lugansk, and 6600 from Donetsk.&amp;quot; What will be on Monday with the market ? Please advice. https://armenpress.am/eng/news/1075959/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 18:06:48 </td>
   <td style="text-align:left;"> $AAPL Data suggest that the overall analyst sentiment for AAPL  is bullish. Simplify the way you research stocks with Invescent   
https://play.google.com/store/apps/details?id=org.invescent.invescent&amp;amp;hl=en_US&amp;amp;gl=US </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:48:51 </td>
   <td style="text-align:left;"> $TSLA A U.S. official said Sunday that Biden’s assertion that Putin has made the decision to roll Russian forces into Ukraine was based on intelligence that Russian front-line commanders have been given orders to begin final preparations for an attack. The official spoke on the condition of anonymity to describe the sensitive intelligence. 
 
The United States and many European countries have charged for weeks that Putin has built up the forces he needs to invade Ukraine — a westward-looking democracy that has sought to move out of Russia’s orbit — and is now trying to create pretexts to invade. 
 
Western nations have threatened massive sanctions if Putin does. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:48:11 </td>
   <td style="text-align:left;"> $TSLA &amp;quot;US claims Russia has ordered final preparations for invasion of Ukraine&amp;quot; https://www.marketwatch.com/story/russia-extends-troop-drills-ukraine-appeals-for-cease-fire-01645370231?reflink=mw_share_twitter US official said . that Putin made decision to roll.. into Ukraine based on intel that Russian  commanders have been given orders to begin preparations for an attack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:38:39 </td>
   <td style="text-align:left;"> $TSLA why future red? People can trade tomorrow then? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:37:30 </td>
   <td style="text-align:left;"> $MRNA $NVDA $TSLA , Earnings reports today before the markets open&amp;quot;  amazingroom.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:36:37 </td>
   <td style="text-align:left;"> $TSLA 🤣🥳🎉🍾🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:33:09 </td>
   <td style="text-align:left;"> $TSLA Japan&amp;#39;s Nikkei 225 drops 2% as investors continue watching Ukraine crisis https://cnb.cx/3BybulO Fears of a potential Russian invasion of Ukraine are likely to continue weighing on investor sentiment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:28:15 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s Monday morning in Ukraine, 2:27 AM, 32°F, cold enough if the tanks we&amp;#39;re going to roll. So, I guess they all were reporting false news. There is no attack. So the stock market open in Frankfurt this morning should be up! Tesla should be up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:28:13 </td>
   <td style="text-align:left;"> $TSLA U.S. stock futures fall, oil prices jump as U.S. says Russia has decided to invade Ukraine https://www.marketwatch.com/story/u-s-stock-futures-fall-oil-prices-jump-as-u-s-says-russia-has-decided-to-invade-ukraine-11645402290?reflink=mw_share_twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:24:43 </td>
   <td style="text-align:left;"> $TSLA real talk i have always been bullish on the market but this year there is no good news on the horizon with so many macro events that can tank this market; with the amount of negative news Russia, Interest rate hikes, supplier constraints, inflation, Fed tapering this will only go down till it finds a bottom then buyers will see it cheap enough to buy the dip.  Right now is not the time and this will go down further save your cash you will know when its a good dip buy. This stock is moving with overall market and nothing TSLA related news can prop this up for now until all the macro events are gone. 
 
I did not like trump, but also not a fan of Biden especially the way he&amp;#39; is handling TSLA/Unions, handling of Afghanistan, our borders and now Ukraine conflict.  We should handle things diplomatically with no threats, war is bad for the world with innocent lives that can be prevented. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:23:59 </td>
   <td style="text-align:left;"> $TSLA Don&amp;#39;t forget, without Lithium miners, Teslas don&amp;#39;t move, LAC, CYDVF, AMRZF... https://youtu.be/EZACRNczIIQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:22:58 </td>
   <td style="text-align:left;"> $TSLA  
zerohedge 
@zerohedge 
· 
19m 
French President Emmanuel Macron and Russian President Vladimir Putin spoke for an hour on Sunday evening in their second talk of the day: AFP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:22:58 </td>
   <td style="text-align:left;"> $TSLA And so the sell off back to $300 begins. A slow, steady bleed to the bottom. Bears about to make a lot of money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:22:58 </td>
   <td style="text-align:left;"> $TSLA been thinking of adding around 200 Tesla shares….watching price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:22:03 </td>
   <td style="text-align:left;"> $TSLA https://www.aljazeera.com/program/inside-story/2022/2/19/whos-telling-the-truth-on-the-ukraine-conflict </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:21:00 </td>
   <td style="text-align:left;"> $UVXY $qqq $SAVA $TSLA This is the reality of the market. &amp;quot;Indexes&amp;quot; are like a bunch of lottery winners put together and advertised as what you can expect playing the lottery any given day. Basically what scammers do making everyone feel like a millionaire except you have to pay a tiny little &amp;quot;fee&amp;quot;. The reality of steal street is 99% of all stocks since 1926 went to 0... The reality is for every winner in the stock market there are hundreds of losers and odds are you are one of them... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:19:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA ”US Intelligence” is an oxymoron. There’s no such thing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:18:03 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:17:52 </td>
   <td style="text-align:left;"> $TSLA Macron telling Putin to stop teasing Joe Biden today.  France takes a leadership role.  MAYBE FRANCE WILL BUY MORE TESLA&amp;#39;S </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:16:26 </td>
   <td style="text-align:left;"> $SPY bears are rooting for wars?  you know russia can nuke the hell out of america and we all die right!?  $M $GOOG $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:15:52 </td>
   <td style="text-align:left;"> $TSLA the silence will be deafening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:11:24 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:10:19 </td>
   <td style="text-align:left;"> $TSLA won’t be surprised to see 500 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 08:02:40 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-20 Trade Analysis Video: 
https://www.youtube.com/watch?v=GN2x7mXMzOk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:53:18 </td>
   <td style="text-align:left;"> $TSLA dip to $500 by end of April and then rebound to $1,500 by end of September so I can be a millionaire for my 30th bday 🥳🍾🎉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:50:58 </td>
   <td style="text-align:left;"> $TSLA true </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:50:29 </td>
   <td style="text-align:left;"> $AAPL $NVDA $TSLA https://electrek.co/2022/01/20/gm-is-actually-making-evs-pre-production-cadillac-lyriq-rolls-off-assembly-line-deliveries-to-follow/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:44:03 </td>
   <td style="text-align:left;"> $SPY $TSLA A world war always starts at the end of the week, not at the beginning of the week 
Like Friday, Saturday and Sunday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:43:38 </td>
   <td style="text-align:left;"> $TSLA Tesla (NASDAQ:TSLA)‘s stock had its “buy” rating reissued by research analysts at Morgan Stanley in a research note issued to investors on Friday, Price Targets.com reports. They presently have a $1,300.00 target price on the electric vehicle producer’s stock. Morgan Stanley’s target price would indicate a potential upside of 51.70% from the company’s current price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:40:45 </td>
   <td style="text-align:left;"> What To Watch On Ford&amp;#39;s Chart After The Automaker Files For A Tesla-Like Feature $F Also $TSLA https://talkmarkets.com/content/stocks--equities/what-to-watch-on-fords-chart-after-the-automaker-files-for-a-tesla-like-feature?post=345450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:39:54 </td>
   <td style="text-align:left;"> $TSLA wake up shareholders this is your chance to see the factory in Texas.

https://news.yahoo.com/tesla-elon-musk-plan-grand-190948421.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:39:14 </td>
   <td style="text-align:left;"> Tuesday Isn’t Even Here Yet And You Can Already See The ‘Russia-Ukraine’ Headlines Tanking/Chopping The Market 😴 

$HOOK $KPTI $KSCP $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:39:00 </td>
   <td style="text-align:left;"> $TSLA has an Altman-Z score of 18.00, meaning it is financially healthy with little risk of bankruptcy. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:36:40 </td>
   <td style="text-align:left;"> $RNDR.X I wonder if $TSLA would consider utilising Render? Surely they are going to enter a metaverse play? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:35:02 </td>
   <td style="text-align:left;"> $TSLA If I knew Tesla was $40 three years ago I would of emptied my bank account 😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:34:43 </td>
   <td style="text-align:left;"> Equity Sentiment Weekly Recap: $TSLA is the #5 stock that institutions traded this week with 118.1K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:31:58 </td>
   <td style="text-align:left;"> Welcome to the Autogeddon Depression.  $f $gm $TM $tsla $stla and more.  Excellent, I love it when a plan comes together as advised to all my friends, followers, haters, those on block for jawboning stupid and Seeking Alpha for not posting many of my bearish posts for profits yet other credible forums do. Thank dog that I am here to help. Carry on shorting the stock markets at large for profits. Rest assured severe stock market crashes in queue. We ain&amp;#39;t seen nothing yet. 💣💥🐻❤😈✔ https://www.investing.com/indices/indices-futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:30:48 </td>
   <td style="text-align:left;"> $TSLA https://www.carscoops.com/2022/02/elon-musks-tesla-roadster-has-traveled-almost-2-billion-miles-in-space/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:26:13 </td>
   <td style="text-align:left;"> $DWAC $tsla Thanks @elonmusk i just found my new #truthsocial handle! &amp;quot;HypocriticalMegaDouche&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:25:17 </td>
   <td style="text-align:left;"> $AMZN $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:25:10 </td>
   <td style="text-align:left;"> $TSLA kinda glad market closed tomorrow actually wish we could extend that a few more days 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:24:54 </td>
   <td style="text-align:left;"> $TSLA About time! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:23:09 </td>
   <td style="text-align:left;"> $TSLA if this can&amp;#39;t hold 850.. 780-790 next and with all the negative news it wont hold i will be waiting for 500s to go long maybe by the summer who knows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:19:36 </td>
   <td style="text-align:left;"> $TSLA mooooon! Pt = $86/share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:17:44 </td>
   <td style="text-align:left;"> $TSLA was the 14th most mentioned on twitch over the last 7 days

Via topstonks.com/stocks/TSLA?st_tsla

#tsla    #twitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:15:32 </td>
   <td style="text-align:left;"> $TSLA Biden stirring up war but war won&amp;#39;t happen. He will then take credit for avoiding war, winning midterms. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:13:13 </td>
   <td style="text-align:left;"> $TSLA all the Tesla Fanboys&amp;#39; call options about to go up in smoke!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:12:17 </td>
   <td style="text-align:left;"> $TSLA Elon, you monkey torturer, tweet something clever! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:09:06 </td>
   <td style="text-align:left;"> $TSLA futs looking super boolish! We should open about -30 Tuesday. To the moooooon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:08:30 </td>
   <td style="text-align:left;"> $TSLA dam! Bloody green! Sorry shorts! Have a good rest tonight and tomorrow, cos it’s gonna be tough for the rest of your week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:06:39 </td>
   <td style="text-align:left;"> $TSLA bloody…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:05:52 </td>
   <td style="text-align:left;"> $TSLA you guys are idiots being happy for no reason all the bad news is out on a closed market day and by Tuesday fear will subside it will be back to business lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 07:05:32 </td>
   <td style="text-align:left;"> $TSLA kids got a jump on this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:58:45 </td>
   <td style="text-align:left;"> $TSLA We&amp;#39;re going to protect our borders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:56:25 </td>
   <td style="text-align:left;"> $TSLA maybe Tsla will get on board with another split🤞🏻🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:56:23 </td>
   <td style="text-align:left;"> $TSLA If they steal the election you know what to do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:55:42 </td>
   <td style="text-align:left;"> $TSLA war in Russia call GI JOE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:53:14 </td>
   <td style="text-align:left;"> $TSLA why is Harris again in Europe ?
To discuss the root causes of Ukraine - Russia tension?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:52:43 </td>
   <td style="text-align:left;"> $TSLA I have a couple friends in Russia.  They tell me the invasion thing is just propaganda to cover up for Biden s lo approval ratings in U S of A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:50:26 </td>
   <td style="text-align:left;"> $TSLA Putin does it need to take out the entire USA with a nuke.  Just the Biden administration will do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:47:43 </td>
   <td style="text-align:left;"> $TSLA working its way into the top 20 most mentioned on twitch over the last 7 days

Via topstonks.com/stocks/TSLA?st_tsla

#tsla    #twitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:43:49 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s been rumored Putnin and trump got  together for drinks this weekend to celebrate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:42:00 </td>
   <td style="text-align:left;"> $TSLA - this news will not treat the stock with kindness- Elon Musk&amp;#39;s Neuralink brain chip tests kills 15 monkeys out of 23, company accused of causing &amp;#39;extreme suffering&amp;#39;. Musk&amp;#39;s Neuralink has been accused of subjecting its monkeys to illegal mistreatment and extreme suffering during chip implants tests.  
An animal-rights group, Physicians Committee for Responsible Medicine, has submitted an official complaint with the US Department of Agriculture on Thursday where they have claimed that monkeys experiences &amp;quot;extreme suffering as a result to inadequate animal care and the highly invasive experimental head implants during the experiments, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:41:32 </td>
   <td style="text-align:left;"> $TSLA $1,000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:40:10 </td>
   <td style="text-align:left;"> $TSLA Putin is laughing his ass off at Biden.  &amp;quot;What a fool&amp;quot; Biden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:35:52 </td>
   <td style="text-align:left;"> $TSLA Biden&amp;#39;s &amp;#39;war in 2 days&amp;#39;
is like Elon&amp;#39;s &amp;#39;2 weeks&amp;#39; for FSD. 

Don&amp;#39;t believe politicians.

Hopefully Elon will be right eventually and Biden wrong.

Bears hoping for war are sociopaths. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:34:37 </td>
   <td style="text-align:left;"> $SOFI $BTC.X $LCID $TSLA $ETH.X  
there wont be any attack. Biden is playing a game to hide his failure. Putin is just acting strong to get his demand filled. Ukraine also acting smart to get benefits from Nato and get back there land back from Russia. Everyone is playing political game and no body cares  about inflation.. this is what the leader wants to do. Hide the real issues!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:34:16 </td>
   <td style="text-align:left;"> $TSLA It is mind-boggling, that Elon continues to promote such people as Warren. They know everything very well about his taxes, it is not the point. They r populists and the reality doesn&amp;#39;t matter, they r talking to own voters, to that unededucted, lazy,  vicious and at the same time entitled to absolute moral authority leftist mob. 
 
Every comment from Elon is like a direct paycheck for Warren, a great bonus for her efforts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:33:28 </td>
   <td style="text-align:left;"> $TSLA friends fron China told me when everyone returned from visiting their families over Chinese new year they all caught COVID. Hospitals full, businesses shutdown,  no workers,  products sit with no pickups, worst supply chain issues. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:29:28 </td>
   <td style="text-align:left;"> Hi guys
For those of you who are bullish on $tsla

Besides buying the stock, why not do a bull put spread?

I’ve done up a quick YouTube tutorial on how to set it up

Here is the link if you are keen

How to Earn 50% on Tesla in 40 days #shorts
https://youtube.com/shorts/eV3Wf4YYd_k?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:27:05 </td>
   <td style="text-align:left;"> $TSLA https://www.bloomberg.com/news/articles/2022-02-20/stocks-set-to-slip-as-traders-assess-ukraine-risks-markets-wrap?sref=pHyhiApD   
 
Futures for Japan, Australia and Hong Kong lower after Wall Street shares slid Friday amid risk aversion (Political risks; and growing calls for FOMC QT normalization to fight inflation). US markets shut for a holiday Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:26:49 </td>
   <td style="text-align:left;"> $TSLA 

This lady needs to STFU ! Seriously - Americans are watching can’t wait for midterms 2024 ! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:16:54 </td>
   <td style="text-align:left;"> $TSLA  
*Walter Bloomberg 
@DeItaone 
· 
52s 
Explosion Heard In Centre Of Rebel-held City Of Donetsk In Eastern Ukraine - Reuters Witness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:12:35 </td>
   <td style="text-align:left;"> $TSLA $NVDA $MARA 
This week is gonna suck hard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:10:13 </td>
   <td style="text-align:left;"> $TSLA Elon&amp;#39;s future as an entrepreneur is very dim. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:08:27 </td>
   <td style="text-align:left;"> $TSLA Russia- Ukraine military comparison - Russia is at least 5 times stronger. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:08:23 </td>
   <td style="text-align:left;"> $TSLA  So, if you think there’s a chip shortage now, imagine if Russia kicks off, China follows suit and invades Taiwan…
 Just sold all my $tsm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:08:11 </td>
   <td style="text-align:left;"> $TSLA my friends and I were just talking about how to fix LA traffic, or major cities in general. The first answer was “self driving cars”. Autonomy is definitely the solution. Cars talking to each other, knowing each other’s speeds, direction, braking capabilities, and destination. Cars can pretty much within 1ft from each other and there would be no crash. Every single movement is predictable. 

I definitely think TSLA will be the leader of autonomy and will license their software across different companies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 06:07:49 </td>
   <td style="text-align:left;"> $TSLA Buddy from Kiev says everyone is lying about the state of war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:55:08 </td>
   <td style="text-align:left;"> $SPY $TSLA  🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:54:29 </td>
   <td style="text-align:left;"> $TSLA Biden said war this weekend on Friday and Thursday last week. The markets tanked… nothing has happened yet $AFRM other than a potential meeting with Putin and macron </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:53:43 </td>
   <td style="text-align:left;"> $TSLA so those monkeys thars escape from the truck and got caught were on their way to neurolink died anyway? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:53:36 </td>
   <td style="text-align:left;"> AMD has officially released its Ryzen 6000 processors. 
They come with a number of improvements, including twice the integrated graphics performance.

$AAPL | $INTC | $TSLA 

$AMD ↗️Ryzen 6000 integrated graphics rival $NVDA Nvidia&amp;#39;s discrete GPUs | Digital Trends

 https://www.digitaltrends.com/computing/amd-ryzen-6000-integrated-graphics-rival-nvidia-discrete-gpus/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:52:53 </td>
   <td style="text-align:left;"> $TSLA  
*Walter Bloomberg 
@DeItaone 
· 
56m 
White House Official Says President Biden Will Remain In Washington, DC Tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:52:51 </td>
   <td style="text-align:left;"> $TSLA  https://youtu.be/RSFbWObcT4A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:51:33 </td>
   <td style="text-align:left;"> $TSLA Nobody gives a fuck about covid anymore, but now they spread fear with war. Everyday, media and sleepy Joe only talk about how Russia &amp;quot;will&amp;quot; invade the Ukraine in one day or during the weekend and nothing happens. They just fucking move the shitty date forward and forward. They really want our money, fucking greedy fuckers. They want crypto and stock market to crash, so people would lose their money and forget their dreams of being millionaires of investing. They want them to go work and be slaves for the government. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:48:13 </td>
   <td style="text-align:left;"> $TSLA USA Canada China India Japan should stay away from European war. Keep North America and Asia safe. Let Britain and France fight against Russia on Europe dominance if they are desperate? 😆 They have European Union. No need to bring war in North America or in Asia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:46:41 </td>
   <td style="text-align:left;"> $TSLA worst case scenario ,
Russia invades Ukraine ,
Build alliance with china , Iran and n Korea , Nuclear war Starts Against US with weakest and dumbest commander and chief and VP , Market crash, deep depression and we All live on government payout , and another 10 trillion debt gets added ,
Our kids and their kids are
All fucked - and capitalist as we know it will diminish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:46:29 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/catl-officially-starts-building-440-million-factory-next-to-tesla-giga-shanghai 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:44:14 </td>
   <td style="text-align:left;"> $DWAC $tsla what a douche https://twitter.com/ddanpereira/status/1495442642364153860 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:39:19 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL There hasn’t been this level of tension in the world since they were picking the name of the Royal Baby!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:34:21 </td>
   <td style="text-align:left;"> $TSLA Chessmaster move by Sleepy Joe to distract US problems with war propaganda. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:25:35 </td>
   <td style="text-align:left;"> $TSLA Russian tanks are beginning to move closer to the Ukraine  border.   
https://www.pbs.org/newshour/show/russians-tanks-move-closer-to-ukraine-border </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:25:29 </td>
   <td style="text-align:left;"> $XELA 

Please do your own DD : this is not a financial advise.

My price prediction:
2022: $30
2023: $50 
2024: $100
2025: $500
2026: $1000

WHY? 👇🏼

1) 
Jan 26, 2022
Par Chadha, Exela’s Executive Chairman, noted, 
“After deploying more than $400 million of capital in 2021 to substantially reduce debt and extend maturities, we are now deploying capital to unlock shareholder value for our large and growing shareholder base.”

2) 
PAR might obtain his bonuses (see 8k exela 9/16/21) this year. 

https://investors.exelatech.com/static-files/9c592c47-58e9-46c3-a27a-0e445c401637

! PAR is 66 years old

3)
Par warned Shorts (see twit of Feb 15th👇🏼)

Par Chadha@par_chadha
43M+ $XELA shares borrowed by shorts; cost to borrow up 15x YTD (source: ORTEX). IMO huge risk to bet against the house with 90k+ shareholders. Reminds me of early days when shorts loved $TSLA for its debt etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:24:37 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ about to get UGLY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:21:53 </td>
   <td style="text-align:left;"> $TSLA starting midnight in Ukraine time, Russia will restrict all airspace over the black sea.  Told yah... watch for after midnight.  It is presently 11:21 p.m. in the Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:19:50 </td>
   <td style="text-align:left;"> $TSLA https://m.economictimes.com/magazines/panache/elon-musks-neuralink-brain-chip-tests-kills-15-monkeys-out-of-23-company-accused-of-causing-extreme-suffering-says-report/articleshow/89595290.cms

Something very serious is wrong with Elon, he should have planted the chip into his brain and his management teams </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:19:15 </td>
   <td style="text-align:left;"> 37 free seats left on Discord 💨✈️ $SPY $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:17:14 </td>
   <td style="text-align:left;"> $TSLA Russian Motto I guess - Better to die in wars than dying from Covid 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:16:43 </td>
   <td style="text-align:left;"> $TSLA Uncharted the movie take about Tesla 
 
hahaha how funny I went with the fam to see Uncharted in the movie theaters 🎥🍿 and I had a great time 
 
I recommend to all Tesla people watch Uncharted they talk about Tesla in the movie 
 
had me 😂😂 
 
Great movie to watch with the family 
Uncharted 
https://www.indiewire.com/2022/02/tom-holland-channing-tatum-uncharted-dog-box-office-1234700909/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:14:10 </td>
   <td style="text-align:left;"> https://youtube.com/watch?v=JStETvXu0vM&amp;amp;feature=share
$tsla $lcid $rivn
EV is still the future! Hope this video can help you with your investing next week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:13:42 </td>
   <td style="text-align:left;"> $SPY $BTC.X $TSLA 

Milk the cow with War Fear 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 05:04:39 </td>
   <td style="text-align:left;"> BYD CO LTD H SHS ( $BYDDF), Tesla Motors, Inc. (NASDAQ: latexd042bb20c42734b6e8e26ffca5c4d764HYG - 93% put flow 
$NVDA - 51% put flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:55:34 </td>
   <td style="text-align:left;"> $TSLA Tsla falls below support on the weekly chart for the first time this week. BLOOD BATH INCOMING. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:53:25 </td>
   <td style="text-align:left;"> $tsla GigaFest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:52:41 </td>
   <td style="text-align:left;"> #Levermann #Global #MegaCap #Buy WK7 $TSLA (6), $NVDA (4), $PG (4) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:52:31 </td>
   <td style="text-align:left;"> $SPY $TSLA $NIO cnbc&amp;#39;s (and others for sure) top article on homepage is always related to ukraine tension / possible (!) war. every f day. like there are no other news. 
thats how you create market fear and can easily manipulate the market. keep that in mind kids </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:51:33 </td>
   <td style="text-align:left;"> $TSLA this has to fight the current macro trend to play out which is why I don’t see it likely. However, to say it is impossible is also foolish as the pattern is currently

Run
Retreat
Run
Retreat
Run
Retreat &amp;lt;—— current state </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:48:58 </td>
   <td style="text-align:left;"> $TSLA Tesla is good but new Tesla : $BNGO is better! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:47:34 </td>
   <td style="text-align:left;"> $TSLA How many fake news articles we going to put on here about the FAKE war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:47:11 </td>
   <td style="text-align:left;"> Next disaster in the EU for $TSLA because the autopilot lane change assistant might be illegal in the EU (so in almost all countries in Europe)? 
 
Details are currently unknown but a investigation was started by the federal motor transportation authority in Germany. 
 
This is almost the only autopilot function that is available in EU because most others are not allowed in the EU.  
 
While Mercedes has a level 3 allowances for highways in Germany (up to 60 km/h), $TSLA cars might not use any autopilot function in the future and $TSLA might has to disable all. 
 
Is it because of missing hardware, e.g. no Lidar? $MVIS has the best lidar. 
 
https://www-focus-de.translate.goog/finanzen/boerse/moeglicherweise-nicht-zulaessig-geht-um-den-autopiloten-kraftfahr-bundesamt-ermittelt-gegen-tesla_id_56420463.html?_x_tr_sl=de&amp;amp;_x_tr_tl=en&amp;amp;_x_tr_hl=de&amp;amp;_x_tr_pto=wapp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:44:54 </td>
   <td style="text-align:left;"> $AAPL $TSLA https://europe.autonews.com/automakers/tesla-faces-scrutiny-german-regulator-over-autopilot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:44:30 </td>
   <td style="text-align:left;"> $AAPL $TSLA https://www.thedrive.com/news/44068/over-10-percent-of-tesla-model-s-evs-fail-germanys-strict-inspection-after-3-years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:44:12 </td>
   <td style="text-align:left;"> $TSLA VP Harris: &amp;#39;We are talking about the real possibility of war in Europe&amp;#39; https://thehill.com/homenews/administration/595078-harris-we-are-talking-about-the-real-possibility-of-war-in-europe The Hill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:41:46 </td>
   <td style="text-align:left;"> $TSLA Let&amp;#39;s talk about this... how TSLA whooped Lucid Dream and Porsche Taycan in all 3 races!!! Don&amp;#39;t hate... appreciate🤣

https://www.teslarati.com/tesla-model-s-plaid-vs-lucid-air-vs-porsche-taycan-drag-race-results-video/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:41:42 </td>
   <td style="text-align:left;"> $PFE $MRNA $TSLA 

https://m.economictimes.com/magazines/panache/elon-musks-neuralink-brain-chip-tests-kills-15-monkeys-out-of-23-company-accused-of-causing-extreme-suffering-says-report/articleshow/89595290.cms </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:41:21 </td>
   <td style="text-align:left;"> $TSLA 

⬛️🟨🟨⬛️⬛️
🟩🟩⬛️⬛️⬛️
🟩🟩🟩⬛️⬛️
🟩🟩🟩🟩🟩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:41:02 </td>
   <td style="text-align:left;"> $SPY $TSLA I think our puts will print BUT i have a feeling this will get pumped tue morning to screw options. Never fails. (Unless war) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:40:13 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL who wants a chart analyzed? ANY stock. Please specify if short/long term. I charge a follow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:29:00 </td>
   <td style="text-align:left;"> $TSLA and it wasn&amp;#39;t created by a racist anti-Semitic POS!

https://news.yahoo.com/ford-mustang-mach-e-replaces-100006642.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:28:53 </td>
   <td style="text-align:left;"> $TSLA I will admit, if I am wrong about Tesla falling to $450-$550, then I could be wrong about it NOT going to $2,000+ this year. With tesla, if you are wrong, you are usually wrong BIG. Hence my hedge leaps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:27:37 </td>
   <td style="text-align:left;"> $AABB $AAPL $MSFT $GOOG $TSLA This will be the breakout year for $AABB and it&amp;#39;s 100% decentralized anonymous AABBG.X Exchange. Stay ahead of the the news and CURVE @AheadoftheNews @ACInvestorBlog @AnalystWire @AnneMarieTrades @abnormalreturns @Forecastis @Benzinga @BidnessEtc @biggercapital @charliebilello @CharlesRAAII @CharlesSizemore @DiscipleOfTrend @charliegasparino https://cryptobriefing.com/kraken-ceo-warns-users-to-get-your-coins-out-of-centralized-exchanges/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:24:13 </td>
   <td style="text-align:left;"> $TSLA FXHedge 
@Fxhedgers 
RUSSIA ISSUES A NOTAM (Or Restricts airspace) OVER THE BLACK SEA, EFFECTIVE MIDNIGHT LOCAL TIME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:20:37 </td>
   <td style="text-align:left;"> $TSLA Warren Buffett-Backed BYD&amp;#39;s Export-Focused Yuan Plus Model Launched In China: What You Should Know 

https://newsfilter.io/a/3942c298bc9656ff88572691991ef372 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:19:35 </td>
   <td style="text-align:left;"> $TSLA  
*Walter Bloomberg 
@DeItaone 
· 
17m 
U.S. Embassy In Russia Warns Americans To Think Of Plans On How To Leave Russia - RIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:17:09 </td>
   <td style="text-align:left;"> $TSLA This drama queen little boy Putin 😤😤Branded by his people as thieve, fraud, rigged elections, and corruption, Putin has been all talk but action about invading Ukraine for the last ten years... and still talking about it. What a coward and thug! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:13:38 </td>
   <td style="text-align:left;"> Don’t be like this guy…This week is our week lads LET’S GET IT🔥💫 $SPY $TSLA $AMZN $SNAP $ISPO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:09:23 </td>
   <td style="text-align:left;"> $TSLA  
 
TSLA Happy Sunday everyone! Hopefully you&amp;#39;re taking some time off to enjoy the weekend.  I like to use this time to step back, reset, and prepare for the week ahead (DD, news, rumors, etc.)  
 
One of the most important things to track is social momentum and social sentiment. When a ticker starts to gain traction, more people see it, and it can start to take off.  
 
This is why we built this social sentiment dashboard, so you can stay ahead of the trends an movements. It is one of the most useful indicators for investing and trading. Check it out - happy to answer any questions. https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220220 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:08:00 </td>
   <td style="text-align:left;"> $TSLA has a good Piotroski-F score of 7.00. This indicates a good health and profitability. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:07:22 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $860.0 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:06:40 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-20 Largest Trades Data: 
https://www.youtube.com/watch?v=cc74tgjkv9E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:06:28 </td>
   <td style="text-align:left;"> $DWAC if u have a twitter account post #truthsocial has a stock! &amp;gt;&amp;gt; $dwac $phun $tsla $cfvi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:05:18 </td>
   <td style="text-align:left;"> $TSLA $900 pipe dream Tuesday 😂😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:03:33 </td>
   <td style="text-align:left;"> $TSLA  I forgot Monday is a lame holiday -_- 

Tuesday will be very interesting indeed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 04:00:19 </td>
   <td style="text-align:left;"> $TSLA 😔https://youtu.be/_le_IpQw4v8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:57:13 </td>
   <td style="text-align:left;"> $SPY $TSLA who wants a chart analyzed? ANY stock. I charge a follow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:49:44 </td>
   <td style="text-align:left;"> $TSLA 🤚https://youtu.be/TRTakARMODE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:47:15 </td>
   <td style="text-align:left;"> $SOFI $HOOD $TSLA Blinken said that even though Putin appears to be preparing for an invasion, “until the tanks are actually moving, the planes are actually flying, the bombs are actually dropping, we’re going to do everything we can, with diplomacy and with deterrence and dissuasion, to get Putin to reverse the decision that we that we believe he’s made,” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:43:41 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:42:59 </td>
   <td style="text-align:left;"> California gas prices! 🤔

$TSLA $F $GM $CEI $VKIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:40:25 </td>
   <td style="text-align:left;"> $TSLA free discord link in bayo, 42 free spots left $RIVN $LCID $NIO $XPEV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:40:21 </td>
   <td style="text-align:left;"> $TSLA Live update -  
Leaders spoke on the phone for 105 minutes and outcome suggests Russia might be willing to step back from brink of invasion of Ukraine 
https://www.theguardian.com/world/live/2022/feb/20/ukraine-crisis-russia-plans-biggest-war-since-1945-says-johnson-zelenskiy-calls-for-sanctions-now-live </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:40:16 </td>
   <td style="text-align:left;"> Taxable Income Definition $TSLA $AAPL $AMZN $FB $AMC ..  https://www.billionaireclubcollc.com/taxable-income-definition/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:36:57 </td>
   <td style="text-align:left;"> $TSLA still just mental fud. No real invasion. All just US stirring shit up lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:35:51 </td>
   <td style="text-align:left;"> $TSLA how big will gap down be for $QQQ on Tuesday before market bounce next week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:35:35 </td>
   <td style="text-align:left;"> $AFRM $TSLA so we were meant to be in a major war by Sunday and yet nothing really other than a few rebels. Not major bomb or aircraft attacks and now this 

https://www.theguardian.com/world/2022/feb/20/putin-and-macron-agree-to-try-and-secure-ceasefire-in-eastern-ukraine

🚀🚀role on diplomatic resolution and a huge recovery in the markets next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:28:23 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT This administration is transitory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:27:27 </td>
   <td style="text-align:left;"> $TSLA Biden Convenes National Security Council Meeting on Ukraine Situation  
 
https://www.marketwatch.com/articles/biden-convenes-national-security-council-meeting-on-ukraine-situation-51645380595?reflink=share_barrons_twitter  
 
Blinken said that even though Putin appears to be preparing for an invasion, “until the tanks are actually moving, the planes are actually flying, the bombs are actually dropping, we’re going to do everything we can, with diplomacy and with deterrence and dissuasion, to get Putin to reverse the decision that we that we believe he’s made,” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:26:26 </td>
   <td style="text-align:left;"> The $F Mustang Mach-E has unseated the $TSLA Model 3 for the #1 spot in this year’s Consumer Reports EV Top Picks survey. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:25:45 </td>
   <td style="text-align:left;"> $TSLA get ready for 780 on Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:18:42 </td>
   <td style="text-align:left;"> $QQQ $TSLA 2/18 $835 P 4.10

ON THE BEAK OF $843.75

We can add you to premium channels once you sign up for $50 per month or give you discount for stock of option channels only.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:17:01 </td>
   <td style="text-align:left;"> $TSLA 😏https://youtu.be/p5XI_7JLzbs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:14:29 </td>
   <td style="text-align:left;"> $TSLA Intelligence on Russia &amp;quot;intentions toward Ukraine &amp;amp; a potential invasion within days is solid&amp;quot;,   VP Harris said  
 
https://www.bloomberg.com/news/articles/2022-02-20/harris-says-u-s-convinced-putin-has-mind-made-up-on-ukraine?sref=pHyhiApD   
 
“Putin made his decision. Period,” Harris said,as she prepared to return to the U.S. from 2 days of meetings at Munich 
 
Bloomberg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:13:11 </td>
   <td style="text-align:left;"> $TSLA 😌https://youtu.be/-9smD823aE0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:11:25 </td>
   <td style="text-align:left;"> $TSLA $700 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:11:16 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:09:39 </td>
   <td style="text-align:left;"> $tsla-$840-$830 gap filled looks strong in $850 sup calls -$950 res puts ranges.
$amzn - wants to fill 2900-2800 res gap. puts at res playing $100 increments.
$aapl-wants to fill $160 gap. Puts at res playing $2.50-$5.00 increments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:07:46 </td>
   <td style="text-align:left;"> Scalping vs. Swing Trading: What’s the Difference? $TSLA $AMZN $AAPL $F $ROKU https://www.billionaireclubcollc.com/scalping-vs-swing-trading-whats-the-difference/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:07:12 </td>
   <td style="text-align:left;"> $TSLA Consumer Reports is corrupt.  The Ford Foundation is their number 1 contributor and they have 4 past Ford Foundation board members!!!!  Current chairman is a past Ford Foundation member.

Did this influence them to change their criteria to make a Ford model their #1 this year???   Sure appears that way.

https://youtu.be/s2zGjMkzLuM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:07:06 </td>
   <td style="text-align:left;"> $TSLA one of the most mentioned on twitch over the last 7 days

Via topstonks.com/stocks/TSLA?st_tsla

#tsla    #twitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:06:24 </td>
   <td style="text-align:left;"> $TSLA place your bets whose lying here with their own agenda for the markets both news came out today 😂🤷🏻‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:06:01 </td>
   <td style="text-align:left;"> $TSLA FSD getting worse with each passing update,

https://youtu.be/JfBuMc5vbO4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 03:03:43 </td>
   <td style="text-align:left;"> $ROKU Free 1 year membership for the 50 people that joins first 💨💨, Link in bio  
Future signals, exact entries and exits will be posted on Discord only. $FUBO $NFLX $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:55:46 </td>
   <td style="text-align:left;"> $TSLA 🤚https://youtu.be/0nU-w7VrgBA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:55:03 </td>
   <td style="text-align:left;"> $TSLA Fair value in 2025 is $400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:54:40 </td>
   <td style="text-align:left;"> $TSLA 

Ford Mustang Mach-E usurps Tesla Model 3 as Consumer Reports top EV pick of the year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:51:30 </td>
   <td style="text-align:left;"> Sweep Options Activity Weekly Recap: $TSLA is the #6 ticker with sweep activity that institutions traded urgently this week options with 88.4K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:50:44 </td>
   <td style="text-align:left;"> $AAPL BRANDON is doing what he’ll of a job , dragging the US into a European War , he can’t even protect our own border . Oh wait inflation he’s got that under control , just keep paying $5.50 gal for gas. Don’t worry about food prices as most criminals are just walking into stores and stealing what they want while u pay for it .
Don’t worry about all the crime in your city it will only get worst as people get more desperate,
Hmmmmm Civil War ?

GREAT JOB BRANDON $XOM  $TSLA  $AMZN $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:49:38 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SPY 
⚠️Link in bio for the invite, free access for first 50 people for 1 year💨💨💨💨💨💨
Join the real money team 👇🏻 $SHOP $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:44:32 </td>
   <td style="text-align:left;"> $dwac $tsla waiting on elon&amp;#39;s tweet about his first truth LOL #truthsocial https://twitter.com/RepMTG/status/1495407793624473603 $twtr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:41:52 </td>
   <td style="text-align:left;"> $TSLA Hopefully France&amp;#39;s Macron can get something done, our little retard doesn&amp;#39;t have a clue what&amp;#39;s going on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:39:05 </td>
   <td style="text-align:left;"> $TSLA Macron saving Ukraine is like Trudeau saving Taiwan 🤷‍♂️ yak ok got it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:31:04 </td>
   <td style="text-align:left;"> $TSLA has overtaken $PLTR to become the most mentioned ticker on WSB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:29:26 </td>
   <td style="text-align:left;"> ARK Invest Top Holdings

1. $TSLA $1.38b
2. $TDOC $1.26b
3. $COIN $1.01b
4. $PATH $959m </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:29:08 </td>
   <td style="text-align:left;"> New $TSLA Supercharger in Santa Monica accepts $DOGE.X  as payment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:28:28 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:28:11 </td>
   <td style="text-align:left;"> $TSLA France stepping in to shut down Brandon&amp;#39;s rhetoric... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:27:40 </td>
   <td style="text-align:left;"> $TSLA comes in at #23 in the Consumer Reports 2022 Best Car Brand rankings, down from #16 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:26:29 </td>
   <td style="text-align:left;"> $TSLA invasion about to start. T-minus 3 and half hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:26:19 </td>
   <td style="text-align:left;"> $DWAC so does truthsocial sue this scam lawfirm on tuesday? lol https://twitter.com/DashAttorneys $twtr $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:24:50 </td>
   <td style="text-align:left;"> $TSLA BIDEN MUST GO!!!!!
BIDEN MUST GO!!!!!!LETS GO BRANDON, #FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:23:21 </td>
   <td style="text-align:left;"> $TSLA why is this ass hole talking about Ukrainian b s. When we have real issues at home. USA.  Remember us ? 

Biden convenes National Security Council on Ukraine crisis https://www.cnbc.com/2022/02/20/biden-convenes-national-security-council-on-ukraine-crisis.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:22:34 </td>
   <td style="text-align:left;"> $TSLA 

What could happen when you have the wrong man in the wrong office ?!! 

This is just a repost (original 1 month ago) 

Will continue to repost as a reminder!

Thank you herds !! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:21:54 </td>
   <td style="text-align:left;"> $BBIG $TSLA $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:20:47 </td>
   <td style="text-align:left;"> $SPY $ARKK $GOOGL $SPX  $TSLA 
 
*big calls in SPX GOOGL,, $millions in CALLS for march 
 
some Unusual Call activity in many #ARKK  names and looks like unusual Option activity in Ark fund #ARKF. Put selling with positive Net Delta in Options.  several other names looks like Put selling..  watching for the move higher.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:17:22 </td>
   <td style="text-align:left;"> $TSLA Ukraine Russia conflict has all the hallmarks of a World War. Not what we need right now. Food for thought 🤔 remember this

https://www.reuters.com/markets/europe/exclusive-imf-10-countries-simulate-cyber-attack-global-financial-system-2021-12-09/

When this happens debit cards and banks won&amp;#39;t be giving you your money. Get ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:16:23 </td>
   <td style="text-align:left;"> $TSLA believe me when I say that I absolutely CANNOT wait to be fully long Tesla again. But I refuse to have my head in the sand. This DUMPS a lot more in the near future. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:14:07 </td>
   <td style="text-align:left;"> $TSLA $F $GM but but we thought we could just convert ICE factories into EV versions https://twitter.com/alex_avoigt/status/1495354877307936779?s=20&amp;amp;t=qIPPc0yi99tge44LeRDCEQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:09:00 </td>
   <td style="text-align:left;"> $TSLA Musk should lead by example and instead of using primates, he should have a neurolink implanted in his head. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:07:30 </td>
   <td style="text-align:left;"> $DWAC omfg crypto tips cloned my post and now it&amp;#39;s on twitter woot woot $cfvi $phun $tsla https://twitter.com/naik_dharmik/status/1495459823093108738 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:06:19 </td>
   <td style="text-align:left;"> $TSLA Musk’s Firm Neuralink Admits Monkey Death in Brain Chip Experiment, Disputes Animal Abuse Claims https://www.robinhoodnews.com/musks-firm-neuralink-admits-monkey-death-in-brain-chip-experiment-disputes-animal-abuse-claims/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:06:10 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-20 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=vzJM4Tc2vxM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:05:47 </td>
   <td style="text-align:left;"> $TSLA Macron of France is so incredibly naive. He really believes that Putin will withdraw after spending billions of dollars preparing to invade Ukraine? Durp, durp Wait until after midnight US Eastern standard time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:04:55 </td>
   <td style="text-align:left;"> $TSLA $QQQ $BTC.X $SHOP $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:02:42 </td>
   <td style="text-align:left;"> $TSLA They&amp;#39;re not leaving. Bloody markets next upcoming weeks. Bulltards got to stop chewing that high grade grass. You were warned ⚠️ https://www.reuters.com/world/europe/ukraine-temporarily-closes-checkpoint-donbass-due-shelling-2022-02-20/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 02:01:03 </td>
   <td style="text-align:left;"> $TSLA back to ramen or maybe a Mcdo menu next week ? 😆🙈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:57:43 </td>
   <td style="text-align:left;"> $TSLA https://www.theguardian.com/world/live/2022/feb/20/ukraine-crisis-russia-plans-biggest-war-since-1945-says-johnson-zelenskiy-calls-for-sanctions-now-live </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:56:49 </td>
   <td style="text-align:left;"> $TSLA https://www.euronews.com/2022/02/20/ukraine-crisis-macron-and-putin-to-speak-in-last-effort-to-avoid-major-conflict </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:56:33 </td>
   <td style="text-align:left;"> $SPY $tsla wow I see a lot of detailed war tactics and strategies from CIA analysts on stocktwits...Couch Intelligence Agents... awesome job people.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:55:24 </td>
   <td style="text-align:left;"> $TSLA 1000 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:55:22 </td>
   <td style="text-align:left;"> $TSLA https://www.aljazeera.com/news/2022/2/20/ukraines-zelenskyy-calls-on-putin-to-meet-as-tensions-soar-live </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:48:41 </td>
   <td style="text-align:left;"> $TSLA Macron, Putin call, agree to jointly push for ceasefire in eastern Ukraine

 2022/2/20 23:56 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:47:01 </td>
   <td style="text-align:left;"> $TSLA $QQQ $AAPL $SPY 

I’m betting on this turning out to be a big nothing burger, but we shall see… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:46:20 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Feb 25 $825 Puts Sweep (6) near the midpoint: 40 vs 1623 OI🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:37:58 </td>
   <td style="text-align:left;"> $TSLA Make Sleepy Joe sleep forever with his stupid sunglasses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:36:10 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Fri $900 Calls Sweep (5) near the Bid: 84 vs 13268 OI🐂 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:35:35 </td>
   <td style="text-align:left;"> $TSLA you notice this is sinking and guys like Sawyer Merritt, Dave Lee, Ross Gerber, Tesla Daily, etc... just continue to pump? No counterion thesis to their never-ending pumps. It&amp;#39;s like a pump bot that the owner has yet to turn off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:35:14 </td>
   <td style="text-align:left;"> $TSLA Even Stock Moe is getting scared 😂😂

https://youtu.be/kH7ely-gGYU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:32:20 </td>
   <td style="text-align:left;"> $TSLA It&amp;#39;s getting close to my buy limit. Buying soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:32:14 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Fri $900 Calls Sweep (4) near the Bid: 82 vs 13268 OI🐂 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:27:52 </td>
   <td style="text-align:left;"> $TSLA Gary Black 
@garyblack00 
· 
2h 
... $TSLA is my largest position because TSLA is like $AAPL 2007 when it disrupted the communications industry forever. My $1,600 $TSLA PT assumes many EV players will have L4 AD in a few years, so it becomes a cost of EV entry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:26:28 </td>
   <td style="text-align:left;"> $TSLA 1000 end of next week…—to da moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:24:57 </td>
   <td style="text-align:left;"> $TSLA Washington&amp;#39;s Birthday Monday, February 21  NYSE stock holiday (Add 1 day to any T+2 Cash-settlement time window) https://www.nyse.com/markets/hours-calendars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:22:03 </td>
   <td style="text-align:left;"> $AFRM $TSLA 🚀🚀🚀🚀weekend futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:19:52 </td>
   <td style="text-align:left;"> $TSLA based on the hammer we printed on the daily this past Friday.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:19:42 </td>
   <td style="text-align:left;"> $TSLA https://www.zerohedge.com/geopolitical/putin-macron-agree-hold-trilateral-talks-next-few-hours-halt-escalation-ukraine Putin, Macron Agree To Hold Trilateral Talks &amp;quot;In The Next Few Hours&amp;quot; To Halt Escalation In Ukraine 
 
(Zero Hedge) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:19:09 </td>
   <td style="text-align:left;"> $TSLA bears are just such sad, negative, unproductive members of society. 99% of you clowns will never get rich trying to make the quick buck. Go play the slots you degenerates. I’m absolutely shaking in my boots with my $680 average on my Tesla shares while studying the history of the company and stock price. I have so much more patience than you disgusting detractors from human advancement that it is laughable. Sorry bears but you’re going to have to do better than war mongering. If you want my shares, you’ll have to pry them from my cold dead hands. I catch Muskies bitch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:18:30 </td>
   <td style="text-align:left;"> $TSLA the war has started already guys.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:11:29 </td>
   <td style="text-align:left;"> $TSLA 

Elon Musk reportedly dating Aussie actor Natasha Bassett!! 

Good for you Elon — living the dream .. she’s beautiful (29yro ) !! 

🙏🏻🐉🦅

https://www.news.com.au/lifestyle/relationships/dating/elon-musk-reportedly-dating-aussie-actor-natasha-bassett/news-story/f2ab50e9f45c22aa284a60b4799f46b9 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:08:26 </td>
   <td style="text-align:left;"> $TSLA https://thehill.com/homenews/sunday-talk-shows/595091-nato-chief-russia-is-preparing-for-an-invasion-of-ukraine-cites NATO Secretary-General Stoltenberg on Sunday said “Russia preparing for invasion of Ukraine,” pointing to Moscow&amp;#39;s troop buildup on the Ukrainian border; &amp;amp; continuation of military exercises </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:08:25 </td>
   <td style="text-align:left;"> $TSLA bears celebrated all long weekend . Until Tuesday the market will be bright green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:04:12 </td>
   <td style="text-align:left;"> $SPY $tsla $spce No war to see here, go home folks... CNN is about to switch to talk about a cold wave never seen in human history thats going to sweep the country.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:03:14 </td>
   <td style="text-align:left;"> $TSLA all these idiots think TSLA and $QQQ will run next week. Look at $BTC.X since market closed Friday, that is your indicator. How dumb can you people be? Sentiment is declining over the weekend. Down 4.7% since market closed. BLOOD in the streets again next week. 🥳🥳🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:01:49 </td>
   <td style="text-align:left;"> $TSLA I was very surprised last night when I saw a snippet on the news comparing the Russian Army to the Ukraine.  I didn&amp;#39;t realize the Russian Army was down to 800k troops.  The vast majority have no actual combat experience aside from the few who were tested in Syria and maybe Chechnia.  People thinking this will be a cake walk by Russia might be in for a big surprise.  You better believe Ukrainian forces are being led by battle tested American Special Forces and British SAS.  This could turn out being a protracted conflict.  On a side note, it is affecting BTC at the moment which is in a free fall. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 01:01:28 </td>
   <td style="text-align:left;"> A few setups for the upcoming days http://ac-investor.blogspot.com/2022/02/a-few-setups-for-upcoming-days.html $HOOK $TSLA #bitcoin and many more. &amp;quot;Peace is the virtue of civilization. War is its crime&amp;quot; Victor Hugo. Have a peacefull Sunday !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:56:26 </td>
   <td style="text-align:left;"> $TSLA Other news-&amp;gt; Britain&amp;#39;s Queen Elizabeth II, world&amp;#39;s longest-serving monarch, tests positive for Covid; symptoms are mild https://cnb.cx/3p0Ue3I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:54:11 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Fri $900 Calls Sweep (4) near the Bid: 83 vs 13268 OI🐂 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:46:32 </td>
   <td style="text-align:left;"> $TSLA --&amp;gt; Blinken says all signs suggest Russia on the brink of invading Ukraine  Reuters Sunday 02-20 https://www.reuters.com/world/europe/blinken-says-all-signs-suggest-russia-brink-invading-ukraine-2022-02-20/ Washington (However) would use every opportunity until the last minute to see if diplomacy would dissuade Moscow from going ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:46:03 </td>
   <td style="text-align:left;"> latex0ea7704fc0ac09191568f9dfca104adaSPY  390p 
$TSLA  830p </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:41:13 </td>
   <td style="text-align:left;"> $TSLA &amp;quot;FXHedge 
@Fxhedgers 
· 
15m 
U.S. INTEL CONFIRMS, &amp;#39;RUSSIAN TROOPS HAVE ACTUALLY RECEIVED ORDERS NOW TO PROCEED WITH THE INVASION&amp;#39; OF UKRAINE -CBS NEWS&amp;quot;  (Unconfirmed-My Two Cents) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:37:33 </td>
   <td style="text-align:left;"> $TSLA they should put sanctions on Russia now until they remove themselves from the area </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:37:18 </td>
   <td style="text-align:left;"> $TSLA Elon, great job, very bullish for Tesla: $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:35:22 </td>
   <td style="text-align:left;"> $TSLA I guess he&amp;#39;s not done with putz yet .. https://twitter.com/FirstSquawk/status/1495436005939159040?t=CQhsd5xDMd1VJK_NM_s8DQ&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:33:23 </td>
   <td style="text-align:left;"> $TSLA War is Not Happening!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:32:33 </td>
   <td style="text-align:left;"> $NVDA $REE $SHOP $TSLA  
 
So True! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:31:49 </td>
   <td style="text-align:left;"> $TSLA  
zerohedge 
@zerohedge 
· 
1h 
*BLINKEN: WON&amp;#39;T DETAIL POTENTIAL RUSSIA SANCTIONS IN ADVANCE 
 
*BIDEN READY TO ENGAGE PUTIN ANY TIME, ANY FORMAT: BLINKEN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:31:10 </td>
   <td style="text-align:left;"> $TSLA 

So CBS NEW just put out a headline that US intel confirms that Russian troops have recorded order to proceed with the invasion ! 

Blinken says Invasion is happening anytime now ! 

All media are confirming invasion ! 

Do they know market is closed tomorrow ?!  

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:26:27 </td>
   <td style="text-align:left;"> $TSLA https://cnb.cx/3gXE0nm  
 
 
Biden will convene a meeting of National Security Council Sunday, amid the rapidly deteriorating security conditions in Ukraine.  
   
 
Friday Biden said US believes that Putin has decided to carry out an attack on Ukraine “in the coming days.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:25:14 </td>
   <td style="text-align:left;"> $TSLA to better show the price distribution. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:23:02 </td>
   <td style="text-align:left;"> Tesla Motors, Inc. (NASDAQ: $TSLA) – Elon Musk’s New Mystery Gal Has Been Identified And You May Have Seen Her Before https://www.billionaireclubcollc.com/tesla-motors-inc-nasdaqtsla-elon-musks-new-mystery-gal-has-been-identified-and-you-may-have-seen-her-before/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:10:04 </td>
   <td style="text-align:left;"> $spy $tsla wait for CNN to suddenly switch to some other super crisis and completely forget about war.... sometime middle of next week... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:09:14 </td>
   <td style="text-align:left;"> $APPS $NVDA $TSLA teslaPutin vs The Stock Market, this sums it all up! Hahaha https://www.instagram.com/tv/CaNFmcKlMv_/?utm_medium=share_sheet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:08:47 </td>
   <td style="text-align:left;"> $F $GM $TSLA New factories wont help until chip shortage is resolved or mitigated. Ford closed sone and Tesla not running at full capacity in all locations. If the companies meet expectations in 2nd Quarter, actually that’s a win. More service calls after the delivery .. new world for car companies 

https://www.cnbc.com/2022/02/20/the-chip-shortage-is-so-bad-gm-dropped-heated-seats-in-winter.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:08:10 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Fri $890 Calls Sweep (5) near the midpoint: 50 vs 2450 OI🐂 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:07:43 </td>
   <td style="text-align:left;"> $TSLA Tuesday morning shorters are going to be crucified </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:07:28 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-20 Options Analysis Video: 
https://www.youtube.com/watch?v=-Vp2Y7toDoY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:07:02 </td>
   <td style="text-align:left;"> $TSLA Elon has a lot of cash, he will support the stock ,and buy at profit.
Nothing to worry ,king of EV will do well.
The mega trend of growth has many more years to go.
Sell the Jan 2024  500 put. You can get $75.
Means you like to buy the stock for $425.
By Jan 2024 the stock will be way above 1000, and this option will be worthless. gives you  over 100% return at low risk expisure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:06:45 </td>
   <td style="text-align:left;"> $LCID $RIVN $TSLA $WKHS market will be back up at some point if ppl are doing this https://www.cnbc.com/2022/01/12/investors-are-paying-millions-for-virtual-land-in-the-metaverse.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:05:26 </td>
   <td style="text-align:left;"> $SPY $DWAC $TSLA made the mistake of looking for an old buddy in the gram.. bombarded by chicks introducing themselves with... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:03:13 </td>
   <td style="text-align:left;"> $TSLA 

NO WAR ! 

RUSSIA&amp;#39;S FOREIGN MINISTRY SAYS LAVROV AND HIS FRENCH COUNTERPART TO HOLD A PHONE CALL ON MONDAY -TASS

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:01:53 </td>
   <td style="text-align:left;"> Check out my last stock market recap video: we discuss $PLTR $NIO $RIVN $LCID $TSLA and millionaire YouTuber Meet Kevin!
https://youtu.be/e8zfFXxI6jY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:01:18 </td>
   <td style="text-align:left;"> $TSLA nothing against Tesla. I love the company but this is Economics which Elon has a degree in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:00:20 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Fri $900 Puts Sweep (9) near the Ask: 91 vs 18372 OI🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-21 00:00:13 </td>
   <td style="text-align:left;"> $TSLA it might go to $680&amp;#39;s till the war issue is solved out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:58:44 </td>
   <td style="text-align:left;"> $TSLA I will be shorting big time Tuesday morning. We are about to make &amp;quot;the great depression&amp;quot; not look so bad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:56:10 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Fri $900 Puts Sweep (3) near the Ask: 31 vs 18372 OI🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:54:51 </td>
   <td style="text-align:left;"> $TSLA next week back to $940 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:51:45 </td>
   <td style="text-align:left;"> $TSLA not falling for it “going up” anymore haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:46:13 </td>
   <td style="text-align:left;"> Stock Symbol (Ticker) Definition $SPY  $DJIA $QQQ $AMZN $TSLA https://www.billionaireclubcollc.com/stock-symbol-ticker-definition/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:42:08 </td>
   <td style="text-align:left;"> Best Technical Indicators for Rookie Traders $QQQ $AMZN $TSLA https://www.billionaireclubcollc.com/best-technical-indicators-for-rookie-traders/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:41:32 </td>
   <td style="text-align:left;"> $QQQ $spy $tsla $amzn We could see a big rally on Tuesday with the latest Putin news. any thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:38:35 </td>
   <td style="text-align:left;"> $TSLA Elon Musk&amp;#39;s New Mystery Gal Has Been Identified And You May Have Seen Her Before 

https://newsfilter.io/a/5a6af6862cb60c29152a1359ee959726 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:38:14 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Fri $900 Puts Sweep (10) near the Ask: 200 vs 18372 OI🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:38:05 </td>
   <td style="text-align:left;"> $FSR $TSLA $RIVN $NIO $LCID 
⚡👑💎🌊🍐🛸🔋📡🏎️🌴🧡🌎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:36:00 </td>
   <td style="text-align:left;"> $TSLA guys, so are we going back up or not? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:34:23 </td>
   <td style="text-align:left;"> $FSR $TSLA $LCID $RIVN $GGPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:33:42 </td>
   <td style="text-align:left;"> New car prices and even used car prices have soared to ridiculously highs. They blame Covid19 lingering affects and the chip shortage.. 

Their leaving out Tesla&amp;#39;s eating their lunch!!
Record sales are causing other OEM&amp;#39;S to mark their prices up... sucks! 🤷🏻‍♂️🤷🏾‍♂️

$TSLA $F $GM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:31:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA Big difference between wanting war and being realistic people. I keep seeing posts about Bears wanting war etc. Sure the market may pump short term but for how long? Smart money isn’t waiting for rate hikes and war to get out of overvalued stocks. Post covid times has created this “STONKS ONLY GO UP ERA”. Fed isn’t injecting money into the market anymore and several  25BP rate hikes are coming (Possibly 50BP in the future). Don’t let your confirmation biases and tendency to only see the bits that support your argument cause you to lose lots of money. What’s important is improving the economy for ourselves and future generations to come, not the short term effects on the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:29:44 </td>
   <td style="text-align:left;"> $NIO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:27:10 </td>
   <td style="text-align:left;"> $TSLA putins just putting us on. Lol. Playing chess while biden is still in diapers playing checkers. Nat gas and oil through the roof, western financial markets shook, no way Ukraine will be part of NATO. All in all putin wins. That would be cavalier and stupid and hes not a stupid man. We rally. Maybe test 4300. But then rip higher... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:26:15 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Fri $840 Puts Sweep (6) near the Bid: 242 vs 2653 OI🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:25:33 </td>
   <td style="text-align:left;"> $TSLA Last minute news... Macron and Putin agreed on diplomatic solution... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:23:56 </td>
   <td style="text-align:left;"> $TSLA hopefully putin cashed out his puts ..🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:21:44 </td>
   <td style="text-align:left;"> $TSLA war started already? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:19:42 </td>
   <td style="text-align:left;"> $TSLA weekly chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:19:07 </td>
   <td style="text-align:left;"> $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:18:31 </td>
   <td style="text-align:left;"> $TSLA &amp;quot;Russia and Belarus extend large military drills near Ukraine&amp;quot;

https://www.investing.com/news/world-news/russia-and-belarus-extend-military-drills-north-of-ukraine-2767917 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:14:54 </td>
   <td style="text-align:left;"> $SOXS $SQQQ $TQQQ $SOXl $TSLA 🤣forget all about Russia , now it’s the convoy to DC that’s going to make the market crash this week ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:13:28 </td>
   <td style="text-align:left;"> $TSLA  
Expect 200 day MA to be retested </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:11:50 </td>
   <td style="text-align:left;"> $TSLA 

Jordan Peterson meets @elonmusk !! 

🙏🏻🐉🦅

https://youtu.be/Io3RGr5mz70 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:10:58 </td>
   <td style="text-align:left;"> $TSLA there’s only 1 path forward. Disruption of oil/gas through batteries and electric transport. It’s inevitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:10:58 </td>
   <td style="text-align:left;"> $TSLA Now that the Olympics are over, bears hoping for Russian grenades to be thrown at nursing homes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:10:33 </td>
   <td style="text-align:left;"> $TSLA 
-☕️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:07:24 </td>
   <td style="text-align:left;"> When Stock Prices Drop, Where’s the Money? $LCID $AMC $TSLA $AMZN https://www.billionaireclubcollc.com/when-stock-prices-drop-wheres-the-money/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:07:00 </td>
   <td style="text-align:left;"> $TSLA shows a strong growth in EPS. Over the last 5 years, the EPS has been growing by 473.69% yearly. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:06:05 </td>
   <td style="text-align:left;"> $ARKK Where is it going possibly?  Watch $ZM 
$TSLA $SE $DOCU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:04:28 </td>
   <td style="text-align:left;"> $TSLA As bad as this market has been this is the only security I am confident in right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:01:38 </td>
   <td style="text-align:left;"> $TSLA so happy I have puts lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:01:25 </td>
   <td style="text-align:left;"> $TSLA $AFRM 🚀🚀🚀🚀🚀🚀🚀

ELYSEE: MACRON AND PUTIN AGREED TO TRY TO WORK IN THE COMING HOURS FOR A CEASEFIRE IN DONBASS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 23:00:28 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/FirstSquawk/status/1495412748515115012?t=asXcLLYASvVLuPLzsQwkLg&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 22:58:47 </td>
   <td style="text-align:left;"> What Is the Intrinsic Value of a Stock? $TSLA $AMZN $SHOP $SPOT https://www.billionaireclubcollc.com/what-is-the-intrinsic-value-of-a-stock/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 22:55:43 </td>
   <td style="text-align:left;"> $SPY Now here is the Nasdaq 100. This is what is keeping mkts up plus $OIL 
$AAPL $AMZN $TSLA . If the 10 majors really start to decline. It would be incredible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 22:53:46 </td>
   <td style="text-align:left;"> $SPY a few interesting charts. Nasdaq advance decline. Biggest drop since 2016. Bigger than Covid. $QQQ $AAPL $TSLA $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 22:52:48 </td>
   <td style="text-align:left;"> In the Money vs. Out of the Money for Options: What’s the Difference? $SPY $DJIA $QQQ $TSLA $AMZN https://www.billionaireclubcollc.com/in-the-money-vs-out-of-the-money-for-options-whats-the-difference/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 22:51:10 </td>
   <td style="text-align:left;"> $AAPL is it time for Puts here? 🤔 
 
$SPY $GOOG $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-20 22:50:23 </td>
   <td style="text-align:left;"> $NIO $TSLA $XPEV  
https://www.youtube.com/watch?v=GkGBqk_-WgI 
 
This video proves why NIO is a fucking beast </td>
  </tr>
</tbody>
</table></div>

---
