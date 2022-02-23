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



Last Updated: 2022-02-23 10:54:15 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/palm-oil </td>
   <td style="text-align:left;"> 2022-02-23 10:45:01 </td>
   <td style="text-align:left;"> Palm Oil Hits All-time High </td>
   <td style="text-align:left;"> Palm Oil increased to an all-time high of 5890 MYR/T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/currency </td>
   <td style="text-align:left;"> 2022-02-23 10:23:39 </td>
   <td style="text-align:left;"> NZ Dollar Jumps on Hawkish RBNZ </td>
   <td style="text-align:left;"> The New Zealand dollar jumped about 0.6% to trade firmly above $0.673 on Wednesday, after the Reserve Bank of New Zealand raised the official cash rate by 25 basis points to 1% and said it was willing to increase the cash rate in “larger increments if required over coming quarters.” The central bank also stated that it will commence the gradual reduction of its bond holdings under the Large Scale Asset Purchase program through both bond maturities and managed sales. The RBNZ has now raised interest rates for the third time since October as it tries to prevent decades-high inflation from becoming entrenched. Moreover, the central bank projected that the cash rate would reach 2.2% by the end of this year compared with previous forecast of 2.1%, and also projected that it will reach 3.3% in the last quarter of 2023, much higher than the November forecast of 2.6%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/construction-output </td>
   <td style="text-align:left;"> 2022-02-23 09:26:43 </td>
   <td style="text-align:left;"> Australia Q4 Construction Output Misses Expectations </td>
   <td style="text-align:left;"> Total construction work done in Australia fell by 0.4% on a quarter-on-quarter seasonally-adjusted terms in the three months to December 2021, missing expectations for a 2.5% gain and following a 0.3% decline in the third quarter. The fall was driven by a 1.3% decrease in building work done in the December quarter, which in turn resulted from a 2.9% drop in residential construction. Meanwhile, non-residential construction rose 1.3% and engineering work done increased 0.7%. On a geographical basis, total construction work done fell in Victoria, Queensland,  Western Australia, Tasmania and the Northern Territory, while all other states and territories rose. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/interest-rate </td>
   <td style="text-align:left;"> 2022-02-23 09:16:00 </td>
   <td style="text-align:left;"> RBNZ Hikes Cash Rate for 3rd Time, Flags Higher Peak </td>
   <td style="text-align:left;"> The Reserve Bank of New Zealand raised its official cash rate (OCR) by 25 basis points to 1.0% during the February meeting, as widely expected. This was the third consecutive rate hike that brings borrowing costs to pre-pandemic levels, amid soaring inflation and surging housing prices. The board mentioned that more monetary tightening was needed to cool a heated economy, saying the cash rate would reach  2.2% by the end of this year and 2.57% by March 2023, which is a more aggressive path than the 2.1% and 2.3% seen in November's projections. The committee also stated that it will commence the gradual reduction of its bond holdings under the Large Scale Asset Purchase (LSAP) programme through both bond maturities and managed sales. That said, policymakers acknowledged that the spread of the Omicron COVID-19 variant would further disrupt economic activity and weigh on consumer and investor confidence in the near term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/22/us/politics/us-russia-ukraine-sanctions.html </td>
   <td style="text-align:left;"> 2022-02-23 09:06:46 </td>
   <td style="text-align:left;"> U.S. and Allies Impose Sanctions on Russia as Biden Condemns ‘Invasion’ of Ukraine - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , President Biden warned President Vladimir V. Putin of Russia that more sanctions would follow if he did not withdraw his forces and engage in diplomatic efforts to resolve the crisis.                                                                                                                                                                                                                                                                                                                                                                                           , By Michael D. Shear, Richard Pérez-Peña, Zolan Kanno-Youngs and Anton Troianovski                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , WASHINGTON — The United States and its allies on Tuesday swiftly imposed economic sanctions on Russia for what President Biden denounced as the beginning of an “invasion of Ukraine,” unveiling a set of coordinated punishments as Western officials confirmed that Russian forces had begun crossing the Ukrainian border.                                                                                                                                                                                                                                                     , Speaking from the White House, Mr. Biden condemned President Vladimir V. Putin of Russia and said the immediate consequences for his aggression against Ukraine included the loss of a key natural gas pipeline and cutting off global financing to two Russian banks and a handful of the country’s elites.                                                                                                                                                                                                                                                                      , “Who in the Lord’s name does Putin think gives him the right to declare new so-called countries on territory that belonged to his neighbors?” Mr. Biden said on Tuesday afternoon, joining a cascade of criticism from global leaders earlier in the day. “This is a flagrant violation of international law and demands a firm response from the international community.”                                                                                                                                                                                                       , Mr. Biden warned Mr. Putin that more sanctions would follow if the Russian leader did not withdraw his forces and engage in diplomatic efforts to resolve the crisis.                                                                                                                                                                                                                                                                                                                                                                                                             , But that prospect remained dim by the end of the day, as Secretary of State Antony J. Blinken canceled plans to meet with the Russian foreign minister on Thursday, saying that it does not “make sense” to hold talks while Russian forces are on the move.                                                                                                                                                                                                                                                                                                                      , “To put it simply, Russia just announced that it is carving out a big chunk of Ukraine,” Mr. Biden said, adding, “He’s setting up a rationale to take more territory by force.”                                                                                                                                                                                                                                                                                                                                                                                                   , The global response began early on Tuesday, just hours after Mr. Putin recognized the self-declared separatist states in eastern Ukraine and Russian forces started rolling into their territory, according to NATO, European Union and White House officials. It was the first major deployment of Russian troops across the internationally recognized border since the current crisis began.                                                                                                                                                                                   , At a news conference in Moscow, Mr. Putin said that he had not decided to send in troops “right at this moment.” But officials said the invasion started overnight, just hours before Mr. Putin’s Parliament formally granted him the authority to deploy the military abroad. Ukrainians near the territory controlled by Kremlin-backed separatists have already endured days of shelling, and as Ukrainian troops hunkered down in their trenches and civilians took shelter in basements, the country’s military said that one soldier had been killed so far and six wounded., Financial markets around the world wobbled on Tuesday in the wake of the Russian actions and the response from Western governments. In the United States, the news pushed stocks lower, leaving the S&amp;P 500 in correction territory, more than 10 percent below its January peak. Oil prices, which had risen to nearly $100 a barrel in anticipation of a global disruption, settled at $96.84 a barrel, up 1.5 percent.                                                                                                                                                         , Mr. Biden and his counterparts in Germany, England and other European nations described the package of global sanctions as severe. They include financial directives by the United States to deny Russia the ability to borrow money in Western markets and to block financial transactions by two banks and the families of three wealthy Russian elites.                                                                                                                                                                                                                        , Chancellor Olaf Scholz of Germany put the Nord Stream 2 gas pipeline on hold. The $11 billion conduit from Russia to Germany — completed but not yet operational — is crucial to Moscow’s plans to increase energy sales to Europe. European Union foreign ministers and the British government approved sanctions against legislators in Moscow who voted to authorize the use of force, as well as Russian elites, companies and organizations.                                                                                                                                 , “It will hurt a lot,” said the E.U. foreign policy chief, Josep Borrell Fontelles.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The governments of Japan, Taiwan and Singapore also issued a joint statement saying they would limit technology exports to Russia in an effort to pressure Mr. Putin with damaging restrictions on his ambitions to compete in high-tech industries.                                                                                                                                                                                                                                                                                                                              , But the moves in Washington and other capitals around the world were limited in scope and fell short of the more sweeping economic warfare that some — including members of Congress and other supporters of Ukraine — have repeatedly demanded in recent weeks.                                                                                                                                                                                                                                                                                                                  , Mr. Biden and his counterparts have said they must balance the need to take swift and severe action with preserving the possibility of even greater sanctions on Russia if Mr. Putin escalates the conflict by trying to seize more territory claimed by the separatists, or even the entire country — a war that could kill tens of thousands of people.                                                                                                                                                                                                                         , “This is the beginning of a Russian invasion of Ukraine,” he said, adding that “we’ll continue to escalate sanctions if Russia escalates.”                                                                                                                                                                                                                                                                                                                                                                                                                                        , European leaders also vowed to get tougher if Mr. Putin’s forces continued to advance. Prime Minister Boris Johnson described British sanctions as just “the first tranche.”                                                                                                                                                                                                                                                                                                                                                                                                      , Mr. Biden’s use of the word “invasion” was significant. In the past, he had angered the Ukrainian leadership when he suggested that there might be lesser penalties for a “minor incursion.” Now that Mr. Putin has ordered forces into eastern Ukraine, Mr. Biden, in his choice of words, is making clear that there is nothing minor about the operation.                                                                                                                                                                                                                      , But that still leaves open the question of how to calibrate the sanctions — because so far there have been no mass casualties. John Finer, the president’s deputy national security adviser, said early Tuesday that the administration could hold back some of its promised punishments in the hopes of deterring further, far more violent aggression by Mr. Putin aimed at taking the rest of the country.                                                                                                                                                                     , “We’ve always envisioned waves of sanctions that would unfold over time in response to steps Russia actually takes, not just statements that they make,” Mr. Finer said on CNN. “We’ve always said we’re going to watch the situation on the ground and have a swift and severe response.”                                                                                                                                                                                                                                                                                        , Crucially, it remains unclear how far Mr. Putin — who has argued that Ukraine itself is a phony country, wrongly carved away from Russia — is prepared to go. On Tuesday, he said ominously that he recognized the so-called Donetsk and Luhansk republics’ sovereignty over not only the land they control, but also the much larger portion of Ukraine that they lay claim to, home to 2.5 million people.                                                                                                                                                                      , At a hastily called news conference on Tuesday, Mr. Putin demanded that Ukraine vow never to join NATO, give up the advanced weapons the West has delivered to it, recognize Russia’s annexation of Crimea and negotiate directly with the Luhansk and Donetsk separatists, who are seen in Kyiv and Western capitals as illegitimate Kremlin proxies.                                                                                                                                                                                                                            , “The most important point is a known degree of demilitarization of Ukraine today,” Mr. Putin said. “This is the only objectively controllable factor that can be observed and reacted to.”                                                                                                                                                                                                                                                                                                                                                                                        , A deputy Russian defense minister, Nikolai Pankov, claimed that Ukraine had gathered 60,000 troops to attack the Russia-backed separatist enclaves in the country’s east — a step that Ukraine denies having any plans to take. Mr. Pankov’s remarks offered little evidence that a peaceful end to the conflict between the two countries was in sight.                                                                                                                                                                                                                          , How it all began. Antagonism between Ukraine and Russia has been simmering since 2014, when the Russian military crossed into Ukrainian territory, after an uprising in Ukraine replaced their Russia-friendly president with a Western-facing government. Russia annexed Crimea and inspired a separatist movement in the east. A cease-fire was negotiated in 2015, but fighting continued.                                                                                                                                                                                     , Russia’s interests in Ukraine. Russia has been unnerved by NATO’s eastward expansion and Ukraine’s growing closeness with the West. While Ukraine is not part of the European Union or NATO, it receives financial and military aid from the United States and Europe.                                                                                                                                                                                                                                                                                                            , How the recent tensions began. In recent months Russia has built up a military presence near its border with Ukraine. U.S. officials say they have evidence of a Russian war plan that envisions an invasion force of 175,000 troops.                                                                                                                                                                                                                                                                                                                                             , Failed diplomatic efforts. The United States, NATO and Russia have been engaged in a whirlwind of diplomacy to prevent an escalation of the conflict. In December, Russia put forth a set of demands, including a guarantee that Ukraine would never join NATO. The West dismissed those demands and threatened economic consequences.                                                                                                                                                                                                                                            , The U.S.’s role. In February, the United States began warning that a full-scale invasion might be days away. Some 8,500 American troops have been placed on “high alert” for possible deployment to Eastern Europe, though President Biden has made clear that the United States would not send troops to fight for Ukraine.                                                                                                                                                                                                                                                      , Moscow asserts its power. On Feb. 21, President Vladimir V. Putin of Russia signed decrees recognizing two pro-Russian breakaway regions in eastern Ukraine and ordering troops to carry out “peacekeeping functions” in those areas. In an emotional speech announcing the move, the Russian president laid claim to all of Ukraine as a country “created by Russia.”                                                                                                                                                                                                            , What is next? Mr. Putin's actions appear to be laying the groundwork for wider intervention in Ukraine. But the economic damage of Western-imposed sanctions, and the death toll of a war, might be too great a cost for Moscow to stomach.                                                                                                                                                                                                                                                                                                                                       , “Negotiations have reached a dead end,” he said in a televised speech. “The Ukrainian leadership has taken the path of violence and bloodshed.”                                                                                                                                                                                                                                                                                                                                                                                                                                   , Mr. Biden’s announcement of the new sanctions was equally grim. He said the United States was imposing “full blocking” on two large Russian financial institutions and “comprehensive sanctions” on Russian debt.                                                                                                                                                                                                                                                                                                                                                                 , “That means we’ve cut off Russia’s government from Western finance,” he said. “It can no longer raise money from the West and cannot trade in its new debt on our markets or European markets, either.”                                                                                                                                                                                                                                                                                                                                                                           , He also said that the United States would impose sanctions on Russian elites and their families, an effort to ensure that those closest to Mr. Putin do not escape the financial pain that is expected to hit hard for average Russian citizens.                                                                                                                                                                                                                                                                                                                                  , Daleep Singh, a deputy national security adviser, called the sanctions announced on Tuesday “only the sharp edge of the pain we can inflict.”                                                                                                                                                                                                                                                                                                                                                                                                                                     , Mr. Singh described the two banks as a “glorified piggy bank of the Kremlin” and a financier “of the activities of the Russian military.” The banks will be prohibited from making transactions in the United States or Europe, and their assets in the U.S. will be frozen.                                                                                                                                                                                                                                                                                                      , Mr. Singh said the sanctions against the Russian elites and their families would punish those who “shared in the corrupt gains of the Kremlin, and they will now share in the pain.”                                                                                                                                                                                                                                                                                                                                                                                              , American officials have worried for weeks that imposing severe sanctions on Russia could also have consequences in the United States, including higher gas prices. Jen Psaki, the White House press secretary, said Americans should be prepared for the conflict with Russia to have that result.                                                                                                                                                                                                                                                                                , Asked about Mr. Biden’s proposed summit with Mr. Putin, Ms. Psaki said the administration was still open to diplomacy. “That remains an option,” she said of a potential meeting, but only if Russia de-escalates hostilities toward Ukraine.                                                                                                                                                                                                                                                                                                                                     , By day’s end in eastern Ukraine, there was no immediate sign of major military escalation, but fearful Ukrainians boarded buses out of the separatist areas as the country’s president, Volodymyr Zelensky, urged his nation to “keep a cool head” in the crisis.                                                                                                                                                                                                                                                                                                                 , Mr. Zelensky insisted that Ukraine would not yield territory, and his defense minister, Oleksiy Reznikov, appeared to be girding his country’s troops for battle.                                                                                                                                                                                                                                                                                                                                                                                                                 , “Ahead will be a difficult trial,” Mr. Reznikov said in a somber message released by the military. “There will be losses. You will have to go through pain and overcome fear and despondency.”                                                                                                                                                                                                                                                                                                                                                                                    , Michael D. Shear and Zolan Kanno-Youngs reported from Washington, Richard Pérez-Peña from New York and Anton Troianovski from Moscow.                                                                                                                                                                                                                                                                                                                                                                                                                                             , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 08:56:24 </td>
   <td style="text-align:left;"> Australia Shares Edge Higher on Tech Bounce </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index rose slightly by 0.3% to around 7,180 on Wednesday as beaten down Australian technology stocks attempted a rebound, while investors reassessed geopolitical risks. Global investor sentiment remained jittery after the US became the latest to sanction Russian elites after Moscow ordered troops into two separatist regions of Ukraine. Gains in technology shares were led by Wisetech Global (1%), Brainchip (5%), Seek Ltd (1.5%), Aristocrat Leisure (1.2%) and Appen Ltd (5%). Australia’s biggest supermarket operator Woolworths also jumped 2% on an earnings beat in the first-half and strong forward guidance for the second-half. Meanwhile, gold miners slid as bullion prices retreated from a recent high, with losses from Newcrest Mining (-3%) and Northern Star Resources (-1.7%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/wage-growth </td>
   <td style="text-align:left;"> 2022-02-23 08:42:00 </td>
   <td style="text-align:left;"> Australia Q4 Wage Prices Rise the Most in 2-1/2 Years </td>
   <td style="text-align:left;"> Australia's seasonally adjusted wage price index rose by 2.3% yoy in Q4 2021, compared with market forecasts of 2.4% and after a 2.2% increase in Q3. This was the highest reading since Q2 2019, amid improved business conditions in the wake of the COVID-19 pandemic. Public sector wages for the second straight quarter recorded an increasing rate of annual growth of 2.1% (vs 1.6% in Q3) after a series low of 1.3% in Q2. Meanwhile, growth in the private sector continued (2.4% vs 2.4%). Across industries, annual wage growth in the original term ranged from 1.3% for the utility sector to 3.5% for accommodation and food services. On a quarterly basis, the wage price index grew 0.7% in Q4, the most since Q1 2014 and matching consensus, driven by the implementation of the last phases of award updates and state-based public sector agreements. Industries that contributed most to growth were the health, care and social assistance, retail trade, and public administration and safety industries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/soybeans </td>
   <td style="text-align:left;"> 2022-02-23 08:37:00 </td>
   <td style="text-align:left;"> Soybeans Hits 40-week High </td>
   <td style="text-align:left;"> Soybeans increased to a 40-week high of 1633 USd/Bu, amid ongoing concerns about harvests in the world's largest producers and exporters of processed soy. Argentina and Brazil, have been facing abnormally dry conditions linked to the La Niña pattern, hitting the quality and quantity of crops. As a result, the latest USDA monthly crop report pegged Brazil's soy crop at 134 million tonnes, down from 139 million in January, and Argentina's soy crop at 45 million, down from 46.5 million. The report also pointed to smaller US soybean supplies amid rising demand from the crushing industry. Meanwhile, Brazil is expected to export 7.5 million tonnes of soybeans in February, down from 9.923 million tonnes projected the week prior by farm consultancy ANEC.

. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 08:28:48 </td>
   <td style="text-align:left;"> US Futures Recoup Some Losses </td>
   <td style="text-align:left;"> US stock futures rose on Wednesday after a broad market selloff in the previous session, as investors continued to grapple with escalating tensions between Russia and Ukraine. Dow futures edged up 0.5%, S&amp;P 500 futures gained 0.6% and Nasdaq 100 futures were up by 0.8%. President Joe Biden announced on Tuesday the first tranche of sanctions against Russia, targeting Russian banks, the country’s sovereign debt and three individuals. The Dow and Nasdaq closed 1.42% and 1.23% lower, respectively, on Tuesday for their fourth straight negative session. The S&amp;P 500 also fell 1.01% and is now 10.25% below its Jan. 3 record, entering correction territory. All 11 S&amp;P sectors declined, led by the consumer cyclical, technology and industrial sectors. Meanwhile, investors are also weighing the effects of geopolitical uncertainties and soaring energy costs on inflation and the outlook for monetary policy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/02/22/dmytro-kuleba-ukraine-foreign-minister-sot-lead-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-23 08:22:45 </td>
   <td style="text-align:left;"> Ukrainian foreign minister: No sanctions enough until Russian forces leave - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/nord-stream-2-pipeline-europe-germany-russia-explainer </td>
   <td style="text-align:left;"> 2022-02-23 07:20:47 </td>
   <td style="text-align:left;"> Nord Stream 2: What to know about the controversial gas pipeline connecting Russia with Europe </td>
   <td style="text-align:left;"> Former National Security Adviser Robert O'Brien provides insight on deterring Putin and not recognizing a new leader he could install in Ukraine on 'Kudlow.'                                                                                                                                                                  , With Russia’s renewed invasion of Ukraine, attention has turned once again to the controversial Nord Stream 2 gas pipeline linking Russia to Europe via Germany.                                                                                                                                                               , The undersea pipeline, which is complete but not yet operating, was an irritant in U.S.-German relations well before Russian President Vladimir Putin said he would recognize the independence of the Donetsk and Luhansk areas.                                                                                               , A Ukrainian serviceman smokes at a position on the front line with Russia-backed separatists near the settlement of Troitske in the Lugansk region on February 22, 2022, a day after Russia recognized east Ukraine's separatist republics and ordered the (Photo by ANATOLII STEPANOV/AFP via Getty Images)                   , Now it’s become a major target as Western governments try to exert leverage on Russia to deter further military moves against Ukraine.                                                                                                                                                                                         , THE RUNDOWN                                                                                                                                                                                                                                                                                                                    , Nord Stream 2 is a 764-mile-long natural gas pipeline under the Baltic Sea, running from Russia to Germany's Baltic coast.                                                                                                                                                                                                     , It runs parallel to an earlier Nord Stream pipeline and would double its capacity, to 110 billion cubic meters of gas a year. It means the Russian state-owned energy company Gazprom can send gas to Europe's pipeline system without using existing pipelines running through Ukraine and Poland.                            , WHY DOES RUSSIA WANT THE PIPELINE?                                                                                                                                                                                                                                                                                             , State-owned gas giant Gazprom says it will meet Europe's growing need for affordable natural gas and complement existing pipelines through Belarus and Ukraine.                                                                                                                                                                , Nord Stream 2 would offer an alternative to Ukraine's aging system that Gazprom says needs refurbishment, lower costs by saving transit fees paid to Ukraine, and avoid episodes like brief 2006 and 2009 gas cutoffs over price and payment disputes between Russia and Ukraine.                                              , Europe is a key market for Gazprom, whose sales support the Russian government budget. Europe needs gas because it's replacing decommissioned coal and nuclear plants before renewable energy sources such as wind and solar are sufficiently built up.                                                                        , GERMANY’S REACTION TO THE CRISIS                                                                                                                                                                                                                                                                                               , The pipeline has been filled with gas but had been awaiting approval by Germany and the European Commission.                                                                                                                                                                                                                   , GERMANY PULLS PLUG ON PIPELINE AS RUSSIAN TROOPS SIGHTED IN UKRAINE                                                                                                                                                                                                                                                            , On Tuesday, German Chancellor Olaf Scholz suspended the certification process for the Nord Stream 2 natural gas pipeline after Russia recognized separatist-held regions in eastern Ukraine.                                                                                                                                   , Germany's utility regulator was reviewing the pipeline for compliance with European regulations on fair competition. It's that approval process that Scholz said Tuesday that he was suspending.                                                                                                                               , U.S. President Joe Biden delivers remarks on developments in Ukraine and Russia, and announces sanctions against Russia, from the East Room of the White House February 22, 2022, in Washington, DC. (Photo by Drew Angerer/Getty Images)                                                                                      , Germany was required to submit a report on how the pipeline would affect energy security, and Scholz said that report was being withdrawn.                                                                                                                                                                                     , Though he initially backed the project, Scholz warned that Russia would face "severe consequences" and that sanctions must be ready ahead of time. Germany had agreed with the U.S. to act against Nord Stream 2 if Russia used gas as a weapon or attacked Ukraine.                                                           , THE U.S. POSITION ON NORD STREAM 2                                                                                                                                                                                                                                                                                             , Despite strenuous objections, Biden waived sanctions against the pipeline's operator when it was almost complete in return for an agreement from Germany to take action against Russia if it used gas as a weapon or attacks Ukraine.                                                                                          , RUSSIAN LEADER VOWS TO KEEP EUROPE'S GAS DESPITE PIPELINE SANCTIONS                                                                                                                                                                                                                                                            , Experts at the time warned that Germany’s deal would allow Russia to supply natural gas would be rewarding Russia for bad behavior after the 2014 annexation of Crimea.                                                                                                                                                        , FILE - Pipes at the landfall facilities of the "Nord Stream 2" gas pipline are pictured in Lubmin, northern Germany, on Feb. 15, 2022. (AP Photo/Michael Sohn, File)                                                                                                                                                           , European NATO allies and Ukraine, meanwhile, have opposed the project going back before the Biden administration, saying it increases Europe's dependence on Russian gas and gives Russia the possibility of using gas as a geopolitical weapon. Europe imports most of its gas and gets roughly 40% of its supply from Russia., STOCKS SINK, OIL NEARS $100 PER BARREL AS BIDEN STICKS RUSSIA WITH SANCTIONS                                                                                                                                                                                                                                                   , Republicans and Democrats in Congress — in a rare bit of agreement — have long objected to Nord Stream 2.                                                                                                                                                                                                                      , WILL SUSPENDING NORD STREAM 2 MAKE EUROPEANS FREEZE THIS WINTER?                                                                                                                                                                                                                                                               , The approval process was not going to be completed in the first half of 2022 which means it as not going to help meet heating and electricity needs this winter as Europe faces a gas shortage.                                                                                                                                , The winter shortage has continued to feed concerns about relying on Russian gas. Russia held back from short-term gas sales — even though it fulfilled long-term contracts with European customers — and failed to fill its underground storage in Europe.                                                                     , Russian President Vladimir Putin listens to a journalist's question during a joint news conference with Hungary's Prime Minister Viktor Orban following their talks in the Kremlin in Moscow, Russia, Tuesday, Feb. 1, 2022.  (Yuri Kochetkov/Pool Photo via AP)                                                               , Russian President Vladimir Putin has said the shortage underlines the need to quickly approve Nord Stream 2, increasing concerns about Russia using gas to gain leverage over Europe.                                                                                                                                          , COULD RUSSIA CUT OFF GAS TO EUROPE IN RETALIATION?                                                                                                                                                                                                                                                                             , Many analysts say it is unlikely that Russia would cut off supplies to Europe given the interdependence between the European market and Gazprom.                                                                                                                                                                               , CLICK HERE TO READ FOX BUSINESS ON THE GO                                                                                                                                                                                                                                                                                      , Meanwhile, the Ukraine crisis, on top of the winter shortage, has already given European governments more reason to find their gas somewhere else, such as through liquefied natural gas brought by ship from the U.S., Algeria, and other places.                                                                             , The Associated Press contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/22/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-02-23 07:07:02 </td>
   <td style="text-align:left;"> Stock futures inch higher after S&amp;P 500 closes in correction </td>
   <td style="text-align:left;"> , U.S. stock market futures were modestly higher in overnight trading Tuesday after the S&amp;P 500 closed in correction territory amid escalating tensions between Russia and Ukraine.                                                                                                                                                                                                         , Futures contracts tied to the Dow Jones Industrial Average advanced 85 points. S&amp;P 500 futures gained 0.35%, while Nasdaq 100 futures rose 0.5%.                                                                                                                                                                                                                                          , During regular trading the Dow fell 483 points, or 1.42%, for its fourth straight negative session. At one point the 30-stock benchmark had been down more than 700 points. The S&amp;P 500 shed 1.01%, and is now 10.25% below its Jan. 3 record close, putting the broad market index in correction territory. The Nasdaq Composite declined 1.23% for its fourth straight negative session., On Tuesday afternoon President Joe Biden announced a first tranche of sanctions against Russia. The measures target Russian banks, the country's sovereign debt and three individuals.                                                                                                                                                                                                    , "While uncertainties remain, our work shows that historically military/crisis events tend to inject volatility into markets and often cause a short-term dip, but stocks tend to eventually rebound unless the event pushes the economy into recession," Eylem Senyuz, senior global macro strategist at Truist wrote in a note to clients.                                               , "Investor sentiment also suggests the bar for positive surprises is low," the firm added.                                                                                                                                                                                                                                                                                                 , All 11 S&amp;P 500 sectors declined on Tuesday, led to the downside by consumer discretionary stocks, which fell 3%. Energy stocks moved lower despite a jump in oil prices. International benchmark Brent crude traded as high as $99.50 per barrel. West Texas Intermediate crude futures, the U.S. oil benchmark, hit a session high of $96, a price last seen in August 2014.             , These tech stocks may have bottomed after massive sell-off, Bank of America says                                                                                                                                                                                                                                                                                                          , Russia-Ukraine tension is a convenient excuse for the stock sell-off, but it's about more than that                                                                                                                                                                                                                                                                                       , These dividend growers have hefty and safe payouts                                                                                                                                                                                                                                                                                                                                        , Meta is the worst performing FAANG stock this year. Here’s where Wall Street sees it going next                                                                                                                                                                                                                                                                                           , "The contagion risk will completely feed into inflationary pressures as energy costs will skyrocket and that will derail large parts of the economic recovery coming out of Covid," said Oanda's Ed Moya.                                                                                                                                                                                 , "Geopolitical risks could lead to a slower growth cycle and that could remove the risk of a half-point Fed rate hike at the March 16th FOMC decision," he added.                                                                                                                                                                                                                          , Wall Street is betting that there's a 100% chance of a rate hike at the Federal Reserve's March meeting, according to the CME Group's FedWatch tool. With inflation running hot, calls for a 50-basis point hike at the March meeting had been accelerating.                                                                                                                              , As tensions build between Russia and Ukraine, yields have retreated, with the yield on the benchmark U.S. 10-year Treasury falling below 2% as investors seek out safe-haven assets.                                                                                                                                                                                                      , As of Friday 78% of S&amp;P 500 companies that have reported have topped earnings estimates, while 78% have exceeded revenue expectations, according to data from FactSet.                                                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-23 07:01:53 </td>
   <td style="text-align:left;"> Australia 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Australia 10 Year Government Bond Yeld increased to a 3-year high of 2.272% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/teladoc-stock-drops-after-another/story.aspx?guid={50DBB364-2D47-49F8-B592-4DF28A22B4F9}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-23 06:23:23 </td>
   <td style="text-align:left;"> Teladoc stock drops after another quarterly loss for telemedicine company - MarketWatch </td>
   <td style="text-align:left;"> Shares of Teladoc Health Inc. 
        TDOC,
        +0.46%
       fell more than 6% in the extended session Tuesday after investors looked past a narrower quarterly loss and sales that were above expectations. Teladoc said it lost $11 million, or 7 cents a share, in the fourth quarter, compared with a loss of $394 million, or $3.07 a share, in the year-ago period. Revenue rose 45% to $554.2 million, Teladoc said. Analysts polled by FactSet expected the company to report a loss of 57 cents a share on sales of  $547 million. Teladoc guided for full-year 2022 sales of between $2.55 billion and $2.65 billion, representing 25% to 30% growth and, at the top of the range, in line with expectations. The telemedicine company said it saw "meaningful growth and penetration across several key areas of our business," including mental health and primary care. "Healthcare has a 'new normal,'" Teladoc said. "We are proud of the role Teladoc Health has played in leading this transformation and are equally excited about our role in 2022 and beyond as we continue to innovate." Shares of Teladoc ended the regular trading day up 0.5%. , Calpers more than quadrupled holdings in meme stocks AMC and GameStop, and also loaded up on Berkshire Hathaway. It trimmed holdings in Palantir.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/22/stocks-making-the-biggest-moves-after-hours-palo-alto-networks-mosaic-more.html </td>
   <td style="text-align:left;"> 2022-02-23 06:13:47 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Palo Alto Networks, Virgin Galactic &amp; more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                             , Check out the companies making headlines in after-hours trading:                                                                                                                                                                                                                                                                                                                            , Palo Alto Networks — Shares of the cybersecurity company gained 6% during extended trading Tuesday following Palo Alto's second-quarter earnings report. The company earned $1.74 per share excluding items on $1.32 billion in revenue. Analysts surveyed by Refinitiv were expecting $1.65 per share on $1.28 billion in revenue.                                                         , Range Resources — Range Resources jumped more than 5% in the wake of the company's fourth-quarter results. The energy company earned 96 cents per share excluding items, on $1.57 billion in revenue. Analysts surveyed by StreetAccount were expecting the company to earn 97 cents per share.                                                                                             , Virgin Galactic — Shares of the space company gained more than 3% after Virgin Galactic reported a smaller-than-expected loss during the fourth quarter. The company lost 31 cents per share compared to the 35-cent loss analysts surveyed by Refinitiv were expecting. Revenue, however, missed estimates. The company posted sales of $141,000, while Wall Street was expecting $300,000., Mosaic — Mosaic shares slid more than 6% following the company's latest earnings report. Mosaic posted earnings of $1.95 per share excluding items on $3.84 billion in revenue. Analysts surveyed by StreetAccount were expecting the company to earn $1.97 per share on $3.9 billion in revenue.                                                                                           , Correction: This story was updated to reflect Virgin Galactic's correct revenue and its correct estimated revenue.                                                                                                                                                                                                                                                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/paraguay/interest-rate </td>
   <td style="text-align:left;"> 2022-02-23 06:06:18 </td>
   <td style="text-align:left;"> Paraguay Raises Interest Rate to 5.75% </td>
   <td style="text-align:left;"> The central bank of Paraguay raised its benchmark interest rate by 25 bps to 5.75% on February 22nd 2022, the seventh consecutive hike since the monetary authority started the normalization process in August. Policymakers noted the increase in the price of oil and other international commodities, as well as adverse climatic factors, could influence the dynamics of local prices. The annual inflation rate in Paraguay accelerated to 7.9% in January, the highest since May of 2011. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/fertilizer-producer-mosaic-says-demand/story.aspx?guid={EC6106CA-8BDD-4BCC-822E-FA15B91EB47E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-23 05:52:54 </td>
   <td style="text-align:left;"> Fertilizer producer Mosaic says demand strong, but stock falls on Q4 earnings miss - MarketWatch </td>
   <td style="text-align:left;"> Shares of Mosaic Co. 
        MOS,
        -1.80%
       dropped more than 6% in the extended session Tuesday after the fertilizer and feed producer missed fourth-quarter expectations and said rising agricultural commodity prices will be good for demand for its products this year. Mosaic said it earned $665 million, or $1.76 a share, in the quarter, compared with $828 million, or $2.17 a share, in the year-ago quarter. Adjusted for one-time items, the company earned $1.95 a share. Revenue rose to $3.8 billion from $2.5 billion a year ago Analysts polled by FactSet expected Mosaic to report adjusted earnings of $1.97 a share on sales of $3.9 billion. "Strong agricultural commodity pricing trends are expected to continue driving demand for fertilizers through 2022," the company said. "Global demand for grain and oilseeds remain high while stock-to-use ratios are at the lowest point in more than a decade," with food-security worries, rising biofuel consumption, and textiles are driving demand for corn, soybeans, and other agricultural commodities, it said. "As a result, strong global fertilizer demand in 2022 is expected as growers seek to maximize yields." Mosaic said its board authorized a dividend increase to 60 cents a share, from 45 cents a share, and a new share buyback of $1 billion. Shares of Mosaic ended the regular trading day down 1.8%. 
, "I'm beyond disappointed and will make every effort to self-reflect and learn from this," says the 51-year-old golf pro.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/hims-hers-shares-pop/story.aspx?guid={AF2AC8CE-E65F-4664-B643-20A0412CC62C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-23 05:52:22 </td>
   <td style="text-align:left;"> Hims &amp; Hers shares pop 13% on big sales jump - MarketWatch </td>
   <td style="text-align:left;"> Hims &amp; Hers Health Inc.'s 
        HIMS,
        -4.55%
       stock jumped 13% in extended trading Tuesday after the company reported fiscal fourth-quarter revenue that exceeded Wall Street analysts' forecasts. Hims &amp; Hers reported a net loss of $31.2 million, compared with a net loss of $5.2 million in the year-ago quarter. Revenue more than doubled to $84.7 million from $41.5 million a year ago. Analysts surveyed by FactSet had expected a net loss of 9 cents a share on revenue of $76.8 million. Hims &amp; Hers' stock has plunged 36% this year, while the broader S&amp;P 500 index 
        SPX,
        -1.01%
       has declined 10%.                                                                                                         , Shares of special purpose acquisition company (SPAC) Digital World Acquisition Corp. undefined shot up 17.4% toward a four-month high in premarket trading Tuesday, after former President Donald Trump's social media app Truth Social launched over the long weekend with glitches, but at the top of Apple Inc.'s undefined list of free apps downloaded. The SPAC had announced in October 2021 a plan to merge with Trump Media &amp; Technology Group, which launched Truth Social. The SPAC's stock is on track to open at the highest price seen during regular-session hours since Oct. 25, and above the SPAC's highest stock closing price of $94.20 on Oct. 22. The stock has rallied 88.0% over the past three months while the S&amp;P 500 undefined has lost 7.1%., Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60473233?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-23 05:51:05 </td>
   <td style="text-align:left;"> Ukraine-Russia tensions: Oil surges on supply fears </td>
   <td style="text-align:left;"> Oil and gas prices climbed on Tuesday on fears the Ukraine-Russia crisis will disrupt supplies across the world.                                                                                                                                             , The price of Brent crude oil, an international benchmark, touched a seven-year high of more than $99 (£73) a barrel after President Vladimir Putin ordered troops into Ukraine's east.                                                                       , But prices later moderated, despite Western countries responding with economic sanctions and moves to block a key Russian gas pipeline.                                                                                                                      , Shares also stemmed early losses.                                                                                                                                                                                                                            , After falling more than 1.5% in early trade on Tuesday, Wall Street turned up following remarks by US President Joe Biden outlining the US response. The Dow closed down 1.4%, however, while the wider S&amp;P 500 slumped 1% and the Nasdaq fell 1.2%.         , Earlier, Japan's Nikkei 225 index closed 1.7% lower, and the Shanghai Composite fell nearly 1%, but share indexes in Europe and the UK ended roughly flat, with the FTSE 100 closing up 0.1%.                                                                , "The West at the moment is treading fairly carefully," said Russ Mould, investment director at the brokers AJ Bell.                                                                                                                                          , Russia is the second-largest oil exporter after Saudi Arabia and the world's top producer of natural gas.                                                                                                                                                    , Measures forcing the country to supply less crude or natural gas would have "substantial implications" on oil prices and the global economy, said Sue Trinh of Manulife Investment Management.                                                               , The RAC warned the crisis would push up UK petrol prices further, after they hit a record 149.12p a litre on Sunday.                                                                                                                                         , "Russia's decision to invade Ukraine is already causing oil prices to rise and will undoubtedly send fuel prices inexorably higher towards the grim milestone of £1.50 a litre [of unleaded petrol]," said RAC fuel spokesman Simon Williams.                , "This spells bad news for drivers in the UK struggling to afford to put fuel in their cars."                                                                                                                                                                 , But the steps announced by the US, UK and Europe so far fall short of what had been threatened in the event of invasion.                                                                                                                                     , The sanctions target financial institutions, elites and other government entities in Russia, in part aiming to restrict the Russian government's ability to raise money on Western financial markets.                                                        , On Tuesday, German Chancellor Olaf Scholz also took the significant step of blocking the certification of the Nord Stream 2 pipeline that would have supplied gas directly from Russia to Germany.                                                           , "If Russian goes further with this invasion, we stand prepared to go further," US President Joe Biden said in remarks at the White House.                                                                                                                    , He also warned that defending Nato territory could come at a cost to the public in the form of higher energy prices.                                                                                                                                         , Since the start of February, already-rising oil prices have jumped more than 10% amid the tensions.                                                                                                                                                          , Maike Currie, an investment director at Fidelity International, said oil could go above $100 a barrel due to a combination of the Ukraine crisis, a cold winter in the US, and a lack of investment in oil and gas supplies around the world.                , "Russia accounts for one in every 10 barrels of oil consumed globally, so it is a major player when it comes to the price of oil, and of course, it's really going to hurt consumers at the petrol pumps," she said.                                         , Russia has spent years preparing for this moment.                                                                                                                                                                                                            , In 2014, when Russian troops moved into Crimea, annexing part of Ukraine, it provoked a first round of international sanctions. And that taught Moscow an important lesson.                                                                                  , Since then it's been setting up defences, moving away from relying on the dollar, and trying to sanction-proof the Russian economy.                                                                                                                          , President Putin may be betting that he can withstand sanctions for longer than the West assumes.                                                                                                                                                             , Read more                                                                                                                                                                                                                                                    , Most of the oil and gas that the UK imports does not come from Russia, but it would nonetheless be affected by a rise in global prices.                                                                                                                      , Average diesel prices in the UK hit 152.51p a litre on Monday, just below Sunday's record of 152.58p, the RAC said.                                                                                                                                          , UK wholesale gas prices have also jumped, with the UK price for April delivery up 9% and the cost for May up 10% to 191p per therm.                                                                                                                          , However, that remained lower than the highs seen in December last year, when it peaked at over 400p per therm.                                                                                                                                               , The economic inter-dependence between Russia and Europe is likely to limit Western actions going forward, said Shaistah Akhtar, an expert on sanctions law from the UK law firm Mishcon de Reya. But some of the restraint so far is deliberate, she added.  , "They needed to allow some room to manoeuvre," she said.                                                                                                                                                                                                     , Edward Gardner, commodities economist at Capital Economics said the tensions are likely to keep oil prices elevated, even if the West does not take more aggressive action.                                                                                  , "It is not in the economic interests of either Russia or the West to use trade in energy as a weapon against each other, but that is not to say it won't happen," he wrote in a note on Tuesday.                                                             , "Even if the West does not implement direct sanctions on Russia's energy exports, tensions with Russia could keep oil prices higher for longer."                                                                                                             , This video can not be played                                                                                                                                                                                                                                 , A fresh perspective on how Hitler brutally seized and kept power                                                                                                                                                                                             , The music that inspired the show, from Leonard Cohen to Joy Division                                                                                                                                                                                         , Why did a glamorous start up trick its own staff?                                                                                                                                                                                                            , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 05:32:00 </td>
   <td style="text-align:left;"> Brazilian Equities Snap 3-Day Losing Run </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, climbed 1% to around 112,892 on Tuesday, snapping a three-day losing streak, lifted by retailers after Economy Minister Paulo Guedes suggested reducing the tax on industrialized products (IPI) by 25%, in order to stimulate economic activity and alleviate consumers. Meanwhile, investors continued to monitor tensions between Russia and Ukraine and also the release of corporate earnings. Movida and wholesaler Assai posted strong results in 4Q21, while Banco Inter's profit declined. On the data front, Brazilian FGV consumer confidence strengthened to a six-month high in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cdns:us </td>
   <td style="text-align:left;"> 2022-02-23 05:30:05 </td>
   <td style="text-align:left;"> Cadence Design Systems earnings above expectations at 0.82 USD </td>
   <td style="text-align:left;"> Cadence Design Systems (CDNS) released earnings per share at 0.82 USD, compared to market expectations of 0.78 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/o:us </td>
   <td style="text-align:left;"> 2022-02-23 05:29:58 </td>
   <td style="text-align:left;"> Realty Income earnings below expectations at 0.01 USD </td>
   <td style="text-align:left;"> Realty Income (O) released earnings per share at 0.01 USD, compared to market expectations of 0.31 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/a:us </td>
   <td style="text-align:left;"> 2022-02-23 05:29:52 </td>
   <td style="text-align:left;"> Agilent earnings above expectations at 1.21 USD </td>
   <td style="text-align:left;"> Agilent (A) released earnings per share at 1.21 USD, compared to market expectations of 1.18 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/meli:us </td>
   <td style="text-align:left;"> 2022-02-23 05:29:45 </td>
   <td style="text-align:left;"> MercadoLibre earnings below expectations at -0.92 USD </td>
   <td style="text-align:left;"> MercadoLibre (MELI) released earnings per share at -0.92 USD, compared to market expectations of 1.00 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/panw:us </td>
   <td style="text-align:left;"> 2022-02-23 05:29:39 </td>
   <td style="text-align:left;"> Palo Alto Networks earnings above expectations at 1.74 USD </td>
   <td style="text-align:left;"> Palo Alto Networks (PANW) released earnings per share at 1.74 USD, compared to market expectations of 1.65 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/psa:us </td>
   <td style="text-align:left;"> 2022-02-23 05:29:33 </td>
   <td style="text-align:left;"> Public Storage earnings above expectations at 3.54 USD </td>
   <td style="text-align:left;"> Public Storage (PSA) released earnings per share at 3.54 USD, compared to market expectations of 2.18 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/business-confidence </td>
   <td style="text-align:left;"> 2022-02-23 05:18:24 </td>
   <td style="text-align:left;"> South Korea Business Confidence Improves </td>
   <td style="text-align:left;"> The Business Survey Index (BSI) on business conditions in the manufacturing sector in South Korea rose to 91 in February of 2022 from 90 in the previous month. Meantime, the index measuring the outlook for March increased by 3 points to 93. In the non-manufacturing sector, the BSI on business conditions fell by 2 points to 81 but that for the outlook edged up by 2 points to 84. The economic sentiment index, a composite of the Business Survey Index and the Consumer Survey Index edged up 0.1 points from the prior month to 105.7 in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/agilent-technologies-shares-up-1/story.aspx?guid={4AE1609A-FB48-4F06-9747-3B426EE3E58E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-23 05:16:15 </td>
   <td style="text-align:left;"> Agilent Technologies shares up 1% after it reports better-than-expected results - MarketWatch </td>
   <td style="text-align:left;"> Shares of Agilent Technologies Inc. 
        A,
        -1.18%
       initially were initially up 1% in extended trading Tuesday after the company reported fiscal first-quarter results that were slightly above Wall Street analysts' forecasts. Agilent posted net income of $283 million, or 93 cents a share, compared with net income of $288 million, or 93 cents a share, in the year-ago quarter. The company recorded an adjusted earnings of $1.21 a share. Net revenue soared 8% to $1.67 billion from $1.55 billion a year ago. Agilent also offered full-year net revenue guidance of between $6.67 billion and $6.73 billion, in line with analyst estimates. Analysts surveyed by FactSet had expected net income of $1.18 a share on revenue of $1.65 billion. Agilent's stock has slumped 18% so far this year, while the broader S&amp;P 500 index 
        SPX,
        -1.01%
       has tumbled 10%., Oil prices spiked after Russian President Vladimir Putin ordered troops into two breakaway regions of Ukraine, raising the threat of war in Eastern Europe.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 05:13:00 </td>
   <td style="text-align:left;"> Toronto Stocks Fall to Over 3-Week Low </td>
   <td style="text-align:left;"> Toronto Stock Exchange S&amp;P/TSX composite index fell more than 0.5% to levels not seen in over 3-weeks on Tuesday, after a long weekend, with aggravating tensions in Eastern Europe fueling higher commodity prices but also risk-aversion. The US and its allies announced sanctions against Russia after it recognized the independence of Ukraine’s breakaway regions and ordered to send more troops to Luhansk and Donetsk. Now, traders await the beginning of the banking earnings season in Canada, with analysts forecasting higher December quarter earnings after upbeat results in the September quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/new-york-nyse-parent-company-cryptocurrency-blockchain-digital-trading </td>
   <td style="text-align:left;"> 2022-02-23 05:06:08 </td>
   <td style="text-align:left;"> New York Stock Exchange parent company makes push into blockchain </td>
   <td style="text-align:left;"> Here are your FOX Business headlines.                                                                                                                                                                                                                                                                                                                                                                                           , The Intercontinental Exchange, parent company of the New York Stock Exchange, has launched a push into the digital trading space, announcing a "significant minority stake" in the blockchain-based trading platform tZERO.                                                                                                                                                                                                     , ICE also announced David Goone, its chief strategy officer, will become the new Chief Executive Officer of tZERO effective next month.                                                                                                                                                                                                                                                                                          , The move marks a significant milestone in the adoption of blockchain-based trading solutions in the capital markets and a commitment from main-stream Wall Street firms in the space. The news follows a report that the NYSE has filed a patent to trade non-fungible tokens, or NFTs, a piece of unique digital property that often involves artwork, music, and sports memorabilia.                                          , WALL STREET'S NEW HYBRID MODEL MAY SQUEEZE NEW YORK'S BUDGET                                                                                                                                                                                                                                                                                                                                                                    , FOX Business has learned that the deal was brokered in large part by veteran investor Marc Cohodes who has been an outspoken advocate for bringing transparency to the markets for both institutional and retail investors.                                                                                                                                                                                                     , New York Stock Exchange                                                                                                                                                                                                                                                                                                                                                                                                         , tZERO, a subsidiary of Overstock.com, is an alternative trading system and broker-dealer designed to give investors access to private and public assets such as stocks and bonds as well as cryptocurrencies and NFTs.                                                                                                                                                                                                          , As a blockchain-based platform, tZERO allows transactions and trades to be settled instantly, increasing transparency and efficiency for its users. Cohodes has recently taken up the cause of retail investors who believe big hedge funds are able to use the 3-day settlement time to illegally short stocks.                                                                                                                , In a short sale, an investor borrows shares, sells them and hopes to make a profit by settling the trade at some later date when the stock falls. An immediate settlement date would be a major impediment to short selling.                                                                                                                                                                                                    , YOUR NEXT CUP OF COFFEE IS GOING TO COST YOU                                                                                                                                                                                                                                                                                                                                                                                    , tZERO has also partnered with BOX Digital Markets LLC to launch the nation’s first regulated blockchain-enabled securities exchange, known as the Boston Security Token Exchange (BSTX). The Securities and Exchange Commission approved BTSX in January and tZERO plans to use proceeds from its recent funding round to help further build out this platform which it plans to launch in the 2nd or 3rd quarter of this year. , The New York Stock Exchange. (Colin Ziemer/New York Stock Exchange via AP)                                                                                                                                                                                                                                                                                                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                     , "We believe the new capital infusion will allow the company to scale and continue its innovation in leveraging blockchain technology to create a more efficient and transparent Wall Street, ultimately revolutionizing and democratizing capital markets," said Overstock.com CEO Jonathan Johnson. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/22/business/russia-ukraine-markets.html </td>
   <td style="text-align:left;"> 2022-02-23 05:03:27 </td>
   <td style="text-align:left;"> Russia-Ukraine Crisis Shakes Markets, but Long-Term Outlook Is Better - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                   , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                    , Strategies                                                                                                                                                                                                                                                                                                                                                                                                                      , Global markets typically rebound from war and disaster, and they are likely to do so this time, too. But Russia’s nuclear arsenal raises the risks beyond calculation.                                                                                                                                                                                                                                                          , By Jeff Sommer                                                                                                                                                                                                                                                                                                                                                                                                                  , Global markets usually weaken as wars approach, strengthen long before wars end and treat human calamity with breathtaking indifference.                                                                                                                                                                                                                                                                                        , That’s been a common historical pattern, anyway. And, with some important caveats, it seems to be playing out with Russia’s latest aggression toward Ukraine.                                                                                                                                                                                                                                                                   , President Vladimir V. Putin of Russia has already rattled stock, bond and commodity markets around the world. On Tuesday, U.S. stocks stumbled, with the S&amp;P 500 falling 1 percent, into what Wall Street calls a correction — a decline of least 10 percent from the most recent high.                                                                                                                                         , The escalating conflict has shifted the value of mutual funds and exchange-traded funds in millions of retirement accounts, even for people who have not thought deeply about Eastern Europe and who have never invested directly in oil, gas or other commodities.                                                                                                                                                             , Mr. Putin’s announcement on Sunday that he was recognizing the sovereignty of two Russian-dominated breakaway Ukrainian regions and ordering the dispatch of Russian troops represented a serious increase in the risks of a much wider war.                                                                                                                                                                                    , Where the conflict may be heading exactly isn’t clear, but the short-term market implications are. “The near-term consequences for markets are relatively simple,” said Claus Vistesen, chief eurozone economist for the research firm Pantheon Macroeconomics. “Energy prices will keep rising, and equities will keep falling.”                                                                                               , Not all stocks have been falling, of course. Rising oil and gas prices have bolstered the S&amp;P 500’s energy sector, the best performer this year, with a return of 21.8 percent through Monday. This came even as the overall index, which often serves as a proxy for the entire stock market, has fallen 8.8 percent.                                                                                                          , Energy companies like Halliburton, Occidental Petroleum and Schlumberger are leading the S&amp;P 500. And American investors have nearly $140 billion stashed in commodity E.T.F.s, mainly those focused on energy, like the $35 billion Energy Select SPDR Fund, which has returned 23.4 percent through Monday.                                                                                                                   , But the overall stock market has been afflicted by multiple troubles: fears of rising interest rates, sizzling inflation and continuing supply-chain bottlenecks. Russian threats to Ukraine are likely to whipsaw the market further.                                                                                                                                                                                          , Even so, long-term investors with well-diversified portfolios of stocks and high-quality bonds — whether held directly or through low-cost mutual funds and exchange-traded funds — will probably be able to ride out this crisis, as they have so many others.                                                                                                                                                                 , While stocks often fall amid global turmoil, U.S. Treasury bonds tend to rally as investors seek havens and drive up their prices. Bond prices and yields move in opposite directions, and because interest rates are rising, Treasuries have declined in value this year. But in a major stock downturn, they usually provide a short-term buffer for portfolios that contain them.                                            , Riding out a storm in the stock market has been a good strategy over the long term. One year after the 1941 bombing of Pearl Harbor, the S&amp;P 500 gained 15 percent. A year after the U.S. invasion of Iraq in 2003, it was up 35 percent. History shows that just one year after most stock-market-shattering crises, the S&amp;P 500 stock index has risen.                                                                        , The Russian hostilities in Ukraine could be the start of something much bigger: a geopolitical shift that plunges the world into a 21st-century version of the Cold War. But even if that’s the case, the hard numbers suggest that the financial implications for prudent, diversified investors who live far from immediate danger zones may not be all that severe.                                                          , The Cold War was destructive and debilitating for vast populations, but it was an excellent period for stock investors. Even during recessions and regional wars, the Dow Jones industrial average turned in an outstanding performance.                                                                                                                                                                                        , Here are the numbers, which I calculated over the long Presidents’ Day weekend:                                                                                                                                                                                                                                                                                                                                                 , From President Truman’s March 17, 1948, speech to Congress criticizing what he called the Soviet Union’s expansion of Communism in Eastern Europe, until Dec. 31, 1991, when the Soviet Union ceased to exist, the Dow returned 10.05 percent, annualized. In the roughly 30 years since then, through Friday, the Dow returned 10.77 percent, annualized, a bit better than during the Cold War, but not by much.              , The price of oil is already steep: approaching $100 a barrel, from about $65 a year ago. It is likely to soar higher, especially if Russia mounts a full-scale invasion and, in return, faces harsh financial sanctions by the United States and its allies.                                                                                                                                                                    , Oil prices are already painful for consumers. They are reflected in the most salient marker of inflation in the United States, the cost of gasoline, which already averages $3.53 a gallon, according to AAA. Inflation is already 7.5 percent, a 40-year high in the United States.                                                                                                                                            , As Caroline Bain, chief commodities economist for the research firm Capital Economics, wrote on Feb. 16: “Much would depend on whether Western sanctions are placed on Russian energy companies and/or Russia decides to withhold energy supply to the West.” In a worst-case outcome, she said, “oil and gas prices could easily double temporarily and the impact on gas prices could last for longer.”                       , That said, Capital Economics and many other analysts view so severe an outcome as unlikely. Even if energy prices continue to spike — largely because of speculation in financial markets — they are likely to decline quickly, based on fundamental supply and demand, said Edward L. Morse, global head of commodities research at Citigroup and a former deputy assistant secretary of state for international energy policy., He said it was unlikely that there would be a significant, long-term “disruption in supply of Russian oil or natural gas,” essentially because cutting off the flow of Russian exports is not in the interest of either Russia, European consumers or the United States.                                                                                                                                                        , How it all began. Antagonism between Ukraine and Russia has been simmering since 2014, when the Russian military crossed into Ukrainian territory, after an uprising in Ukraine replaced their Russia-friendly president with a Western-facing government. Russia annexed Crimea and inspired a separatist movement in the east. A cease-fire was negotiated in 2015, but fighting continued.                                   , Russia’s interests in Ukraine. Russia has been unnerved by NATO’s eastward expansion and Ukraine’s growing closeness with the West. While Ukraine is not part of the European Union or NATO, it receives financial and military aid from the United States and Europe.                                                                                                                                                          , How the recent tensions began. In recent months Russia has built up a military presence near its border with Ukraine. U.S. officials say they have evidence of a Russian war plan that envisions an invasion force of 175,000 troops.                                                                                                                                                                                           , Failed diplomatic efforts. The United States, NATO and Russia have been engaged in a whirlwind of diplomacy to prevent an escalation of the conflict. In December, Russia put forth a set of demands, including a guarantee that Ukraine would never join NATO. The West dismissed those demands and threatened economic consequences.                                                                                          , The U.S.’s role. In February, the United States began warning that a full-scale invasion might be days away. Some 8,500 American troops have been placed on “high alert” for possible deployment to Eastern Europe, though President Biden has made clear that the United States would not send troops to fight for Ukraine.                                                                                                    , Moscow asserts its power. On Feb. 21, President Vladimir V. Putin of Russia signed decrees recognizing two pro-Russian breakaway regions in eastern Ukraine and ordering troops to carry out “peacekeeping functions” in those areas. In an emotional speech announcing the move, the Russian president laid claim to all of Ukraine as a country “created by Russia.”                                                          , What is next? Mr. Putin's actions appear to be laying the groundwork for wider intervention in Ukraine. But the economic damage of Western-imposed sanctions, and the death toll of a war, might be too great a cost for Moscow to stomach.                                                                                                                                                                                     , Mr. Morse projects a decline in oil prices by the end of this year to less than $65 a barrel, with extra supplies probably coming from Iraq, Venezuela, the United States, Canada and Brazil. And a U.S.-Iran diplomatic deal could add more than one million gallons a day.                                                                                                                                                    , If the Federal Reserve and other central banks go ahead and tighten monetary policy to curb inflation, the economy will cool off, reducing demand for energy, all of which would add to the momentum of a reduction in energy prices, Mr. Morse said.                                                                                                                                                                           , The economic damage caused by the conflict could spiral in unexpected ways. “The biggest danger, of course, is the unintended consequences that we’re bound to see,” Mr. Morse said.                                                                                                                                                                                                                                            , Russia isn’t just a heavyweight in energy production, where it ranks third in petroleum (behind the United States and Saudi Arabia) and second in natural gas (behind the United States), according to the U.S. Energy Information Administration.                                                                                                                                                                              , It is also one of the world’s most important producers of minerals and metals like platinum, nickel, aluminum cobalt, copper and gold and diamonds. Prices of these commodities have been rising, but that’s the least of it. Shortages of Russian commodities could cause further supply-chain bottlenecks in the United States.                                                                                               , Russia ranks No. 1 in production of palladium, for example, a critical component of the catalytic converters required to reduce emissions in gasoline-powered cars, whose rising prices have already contributed to a surge in American inflation. Much of Russia’s palladium is mined by Norilsk Nickel, which could be included on Western sanctions lists.                                                                   , On Tuesday, Chancellor Olaf Scholz of Germany put a stop to the Nord Stream 2 natural gas pipeline linking Germany to Russia. But it will be challenging for policymakers to calibrate further sanctions and monetary policy in a manner that satisfies Western geopolitical objectives without damaging the global economy.                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                                                                                                 , Economics aside, Russia’s grievances with the West have already led to a partial rapprochement with China. If that evolves into a strong alliance, it would shift the balance of global power in a direction that generations of Western strategists have tried to prevent.                                                                                                                                                     , “This crisis is a trip back to the future,” Ian Bremmer, president and founder of the risk consultancy firm Eurasia Group, said in a video conversation from the Munich Security Conference last week. Russia’s actions have moved the world closer to a great-power military conflict than at any time since the end of the Soviet Union.                                                                                      , The possibility of a confrontation between NATO forces and Russia, with its nuclear arsenal, raises the risks of the Ukraine crisis beyond rational calculation.                                                                                                                                                                                                                                                                , Even so, the markets will perform those calculations anyway.                                                                                                                                                                                                                                                                                                                                                                    , History tells us that the worse things get, the more valuable cash and Treasuries seem. And it also says that Cold Warriors who stuck with the stock market ended up with big fat portfolios.                                                                                                                                                                                                                                   , That’s likely to be the case in the future, too. But it’s impossible to be certain of it.                                                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/22/consumers-lost-5point8-billion-to-fraud-last-year-up-70percent-over-2020.html </td>
   <td style="text-align:left;"> 2022-02-23 04:33:34 </td>
   <td style="text-align:left;"> Consumers lost $5.8 billion to fraud last year — up 70% over 2020 </td>
   <td style="text-align:left;"> , American consumers reported losing more than $5.8 billion to fraud last year, up from $3.4 billion in 2020 (an increase of more than 70%), the Federal Trade Commission said Tuesday.                                                                                                                                                                                                                                                                    , Almost 2.8 million consumers filed a fraud report to the agency in 2021 — the highest number on record dating back to 2001, according to the FTC. About 25% of those scams led to a financial loss, with the typical person losing $500.                                                                                                                                                                                                                 , The true toll is almost certainly higher since some incidents likely weren't reported to the agency.                                                                                                                                                                                                                                                                                                                                                     , More from Personal Finance:Parents face a surprise tax bill if kids are trading stocksGoing abroad? What it's like to self-test for your flight homeHow to keep emotions out of your investment decisions                                                                                                                                                                                                                                                , Those figures also don't include reports of identity theft and other categories. More than 1.4 million Americans also reported being a victim of identity theft in 2021; another 1.5 million filed complaints related to "other" categories (including credit reporting companies failing to investigate disputed information, or debt collectors falsely representing the amount or status of debt). Both sums are annual records, according to the FTC., Fraud has ballooned during the Covid-19 pandemic, as con artists have preyed on consumer fear and confusion. They peddled fake health products (such as hand sanitizer and masks) and used stolen data to file for unemployment and other benefits in victims' names, for example.                                                                                                                                                                       , Imposter scams were the most prevalent form of fraud in 2021, accounting for more than a third of reports, the FTC said. The typical victim lost $1,000.                                                                                                                                                                                                                                                                                                 , In such scams, criminals pretend to be someone else to steal money or sensitive personal information. They may include romance scams, as well as people falsely claiming to be a government official, a relative in distress, a well-known business or a technical support expert, for example, according to the FTC.                                                                                                                                    , However, other forms of fraud were costlier on a per-person basis — investment fraud cost $3,000 per victim in 2021, for example, the largest such sum. Business and job-opportunity scams cost the typical victim almost $2,000.                                                                                                                                                                                                                        , Younger Americans tended to be fraud targets most frequently, but those over age 70 reported losing more money. The typical person over age 80 lost $1,500, triple that of those in their 20s.                                                                                                                                                                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/02/22/borger-russia-ukraine-sanctions-biden-language-of-war-sot-vpx-nr.cnn </td>
   <td style="text-align:left;"> 2022-02-23 04:07:15 </td>
   <td style="text-align:left;"> Video: Borger says Biden's Urkaine speech 'contained language of war' - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/22/tech/cargo-ship-fire-update/index.html </td>
   <td style="text-align:left;"> 2022-02-23 04:01:00 </td>
   <td style="text-align:left;"> Fire that left cargo ship full of luxury cars stranded in the Atlantic may finally be going out - CNN </td>
   <td style="text-align:left;"> New York (CNN Business)The fire on board the large car-carrying cargo ship Felicity Ace could soon be extinguished because there might not be anything left to burn.                                                                                                                                                                                                                                                                                                                                                                                                 , The 656 foot-long Felicity Ace roll-on/roll-off car-carrying ship caught fire in the North Atlantic last Wednesday as it carried around 4,000 vehicles, including Porsches, Volkswagens, Lamborghinis, Bentleys and Audis from Emden, Germany to Davisville, Rhode Island. All 22 crew members on board safely abandoned ship after the fire began to spread.                                                                                                                                                                                                        , A full five days after the cargo ship and the luxury cars it was carrying on board began to burn 90 nautical miles southwest of Portugal's Azores islands, captain João Mendes Cabeças told the Portuguese news agency Lusa that "the fire had subsided in recent hours," thanks to a lack of materials left to blaze through.                                                                                                                                                                                                                                       , Two large tugboats arrived on the scene Tuesday from Gibraltar and are spraying the ship with water to cool it down, according to a statement from the owner of the Felicity Ace, Japanese ship operator Mitsui O.S.K. Lines (MOL). The tugboats will also help to position the Felicity Ace as safety conditions are assessed. Once approved, the initial salvage team will board and provide more insight on the damage as well as next steps. Two salvage boats are en route to the cargo ship to assist with firefighting and towing, according to the statement., Cabeças told Reuters over the weekend that the fire was being kept alive by the lithium-ion batteries of the electric cars on board, with flames edging closer and closer to the fuel tanks of the ship. A main concern of the Portuguese navy has been the potential environmental impact of the fire. Pollution is a high risk with the large amount of fuel and car batteries present.                                                                                                                                                                            , There is currently no oil leakage confirmed from the stable ship, according to the MOL statement Tuesday.                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The giant cargo ship has $334.5 million in burning cars on board, consulting firm Anderson Economic Group (AEG) estimated in a new report. The salvage cost alone is estimated to be $150 million - bringing the total loss for the ship to half a billion dollars, the group estimates.                                                                                                                                                                                                                                                                             , Porsche sent a letter to impacted car dealers that all lost cars would be rebuilt and delivered as soon as possible, according to journalist and television host Matt Farah, whose new 2022 Porsche Boxster Spyder was among those lost at sea. An estimated 1,100 Porsches and 189 Bentleys were lost on the ship, including many high-end, customized models that collectively would exceed $140 million in value, according to AEG and Reuters.                                                                                                                   , Volkswagen Group, which owns Lamborghini, Porsche and Audi, confirmed to CNN Business the ship was transporting its vehicles but has given no additional details.                                                                                                                                                                                                                                                                                                                                                                                                    , Once deemed safe, the Felicity Ace will be towed to another European country or the Bahamas, Cabecas told Reuters.                                                                                                                                                                                                                                                                                                                                                                                                                                                   , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/markets-telling-investors-we-are-in-a-very-fragile-moment-amid-russia-ukraine-tensions-former-nyse-ceo </td>
   <td style="text-align:left;"> 2022-02-23 03:48:47 </td>
   <td style="text-align:left;"> Markets telling investors 'we are in a very fragile moment' amid Russia-Ukraine tensions: Former NYSE CEO </td>
   <td style="text-align:left;"> Former New York Stock Exchange Chairman and CEO Dick Grasso argues the market is telling investors 'we are in a very fragile moment' amid rising tension between Russia and Ukraine and urges President Biden to issue strong sanctions.       , Former New York Stock Exchange Chairman and CEO Dick Grasso weighed in on recent market volatility amid rising tension between Russia and Ukraine on Tuesday, noting that markets are telling investors that "we are in a very fragile moment.", Speaking on "Cavuto: Coast to Coast," Grasso also stressed that it is important for President Biden to issue "strong sanctions" on Russia to send a strong message to other countries, including Iran and China.                               , Grasso made the comments shortly before Biden said Russia has begun an "invasion" of Ukraine Tuesday while announcing new sanctions aimed at deterring further aggression in Ukraine.                                                          , Biden called the sanctions "far beyond" those imposed on Russia during its 2014 annexation of Crimea in Ukraine, saying the U.S. was cutting off Russia's major financial institutions from the West.                                          , U.S. stocks, in a choppy session, took a leg down early afternoon as investors weighed Russian President Vladimir Putin's ordering of troops into separatist regions of eastern Ukraine against earnings from big retailers.                   , RUSSIA-UKRAINE CRISIS PROMPTS MARKETS TO BRACE FOR HEAVY FALLS                                                                                                                                                                                 , The Dow Jones Industrial Average fell over 500 points or 1.7%, while the S&amp;P 500 and Nasdaq Composite dipped by 1.7% and 1.5%, after briefly turning positive and then negative again.                                                         , Western powers fear that Russia might use skirmishes in Ukraine's eastern regions as a pretext for an attack on the democracy, which has defied Moscow’s attempts to pull it back into its orbit.                                              ,  Hudson Institute senior fellow Rebeccah Heinrichs gives her take Biden's response to the Russia-Ukraine tensions on 'Making Money.'                                                                                                           , Grasso warned Tuesday that if President Biden doesn’t issue "strong sanctions," "Russia, China, and indirectly Iran will say, ‘America speaks loudly and carries a small stick.’"                                                              , "We’ve got to send a very powerful message to [Russian] President Putin that we won’t stand for his aggressiveness and his desire to take the entire Ukraine," Grasso told host Neil Cavuto.                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                    , "If we allow Russia to go unfettered in terms of its quest for the Ukraine what does that say to China about its desire to reunify with Taiwan? What does it say to Iran about its pursuit of a nuclear device?" Grasso added.                 , "Strength is what our adversaries understand," he stressed, noting that "a very strong set of sanctions" will likely defer any further actions by the Russians, the Chinese, or the Iranians.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-end-higher/story.aspx?guid={03284E1A-F383-428F-85CC-9B8F3C5C5FCB}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-23 03:39:41 </td>
   <td style="text-align:left;"> U.S. oil futures end higher after Russia's move into Ukraine - MarketWatch </td>
   <td style="text-align:left;"> Oil futures climbed on Tuesday, buoyed by concerns over global supplies after Russia made a move into Ukraine. "The market has certainly already priced in some degree of Russian related oil and gas supply risk," said Troy Vincent, senior market analyst at DTN. However, "the lack of response in prices emphasizes that the market is not taking the threat of Russian oil and natural gas flows being sanctioned or cut off by war seriously," he said. "With energy price inflation already weighing on the global and European economy, severe sanctions on Russian oil and gas flows would prove mutually destructive for both Europe and Russia." West Texas Intermediate crude for March delivery 
        CLH22,
        +1.32%
       rose $1.28, or 1.4%, to end at $92.35 a barrel on the New York Mercantile Exchange on the contract's expiration day. The new front-month April contract 
        CLJ22,
        +0.02%
       rose $1.70, or 1.9%, to settle at $91.91., Shares of special purpose acquisition company (SPAC) Digital World Acquisition Corp. undefined shot up 17.4% toward a four-month high in premarket trading Tuesday, after former President Donald Trump's social media app Truth Social launched over the long weekend with glitches, but at the top of Apple Inc.'s undefined list of free apps downloaded. The SPAC had announced in October 2021 a plan to merge with Trump Media &amp; Technology Group, which launched Truth Social. The SPAC's stock is on track to open at the highest price seen during regular-session hours since Oct. 25, and above the SPAC's highest stock closing price of $94.20 on Oct. 22. The stock has rallied 88.0% over the past three months while the S&amp;P 500 undefined has lost 7.1%.                                                                                                                                                                                                                        , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 03:36:00 </td>
   <td style="text-align:left;"> US Stocks Sell-Off </td>
   <td style="text-align:left;"> All three major US stocks declined on Tuesday, as tensions between Russia and Ukraine dented risk appetite. Yesterday, President Putin ordered troops into two Moscow-backed separatist regions of eastern Ukraine after announcing that he would recognize their independence, triggering sanctions from Western nations. Today, US President Biden said he believes it is the beginning of Russia's invasion of Ukraine and announced the US is implementing sanctions on Russian financial firms, sovereign debt, and individuals. Biden also said sanctions will widen if Russia continues its aggression. On the economic front, the IHS Markit US Manufacturing PMI rose to 57.5 in February of 2022 from 55.5 in January, beating forecasts of 56, preliminary estimates showed. The Dow Jones fell for the 4th straight session by 483 points to 33,597; the S&amp;P 500 lost 1% to 4,305 and entered a technical correction, and the Nasdaq Composite slipped 1.2% to 13,382. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/new-york-gov-kathy-hochul/story.aspx?guid={D8AC8EDD-FD83-4B0D-A322-2AC7BAEBF482}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-23 03:28:00 </td>
   <td style="text-align:left;"> New York Gov. Kathy Hochul signs cannabis cultivation measure  - MarketWatch </td>
   <td style="text-align:left;"> New York Governor Kathy Hochul on Tuesday signed into law a measure that would allow the state's hemp farmers to begin growing adult use cannabis this season. The measure, which passed both houses of the state legislature last week, will provide conditional adult use cannabis cultivator licenses for existing hemp farmers. The measure also includes a social equity mentorship program. In a statement, Hochul said the bill "positions New York's farmers to be the first to grow cannabis and jumpstart the safe, equitable and inclusive new industry we are building." , Calpers more than quadrupled holdings in meme stocks AMC and GameStop, and also loaded up on Berkshire Hathaway. It trimmed holdings in Palantir.                                                                                                                                                                                                                                                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/argentina/balance-of-trade </td>
   <td style="text-align:left;"> 2022-02-23 03:13:00 </td>
   <td style="text-align:left;"> Argentina Trade Surplus Shrinks in January </td>
   <td style="text-align:left;"> Argentina's trade surplus narrowed to USD 296 million in January of 2022 from USD 1,068 million in the corresponding month of the previous year. Exports rose 12.9 percent from a year earlier to USD 5.547 million, due to higher sales of primary goods (79.6 percent); industrial manufacturing (32.2 percent) and fuels &amp; energy (2.5 percent). On the other hand, exports of agricultural manufactures declined 24.2 percent. Among major trading partners, exports rose to China (30.4 percent), Chile (48.1 percent) and the Netherlands (122.2 percent) while those to Brazil fell 14.1 percent. Meanwhile, imports advanced at a faster 36.6 percent to USD 5.251 million, boosted by purchases of intermediate products (46.6 percent); capital goods (37.7 percent); parts &amp; accessories for capital goods (+29.8 percent); consumer goods (36.1 percent) and fuels &amp; lubricants (+36.5 percent). Imports went up mainly from China (73.1 percent); Brazil (32.8 percent) and the US (4.3 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/morocco/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-23 03:07:06 </td>
   <td style="text-align:left;"> Morocco Inflation Rate Slows to 3.1% in January </td>
   <td style="text-align:left;"> The annual inflation rate in Morocco edged down to 3.1 percent in January of 2022 from 3.2 percent in the previous month, which was the highest since February of 2009. Prices slowed for transport (5.9 percent vs 6.2 percent in December), food &amp; non-alcoholic beverages (4.2 percent vs 4.5 percent) and recreation &amp; culture (2 percent vs 2.4 percent). Also, cost of communication decreased 0.2 percent, the same as in December. On a monthly basis, consumer prices were unchanged, after rising 0.1 percent in prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/ups-workforce-declined-9000-employees/story.aspx?guid={58C6BB58-23EB-4F6D-AEC0-C59A756E388E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-23 03:06:01 </td>
   <td style="text-align:left;"> UPS workforce declined by 9,000 employees in 2021, as losses in the U.S. offset gains internationally - MarketWatch </td>
   <td style="text-align:left;"> United Parcel Service Inc. 
        UPS,
        -0.19%
       disclosed Tuesday that its workforce was reduced by about 9,000 employees in 2021, as job cuts in the U.S. more than offset net hiring internationally. The package delivery giant said in its 10-K filing with the Securities and Exchange Commission that it had 534,000 global employees at the end of 2021, excluding seasonal employees, of which 444,000 were in the U.S. and 90 were located abroad. That compares with 543,000 global employees at the end of 2020, of which 458,000 were located in the U.S. and 85,000 were located internationally. The decline in workforce seems to jibe with the company's "better not bigger" strategy, which included the sale of some assets. Of the 2021 workforce, there were 89,000 management employees, which which 44% work part-time, and 445,000 hourly employees, of which 51% work part-time. In comparison, UPS had 495,000 global employees in pre-pandemic 2019, of which 413,000 were in the U.S. and 82,000 were internationally located. UPS's stock, which fell 1.1% in afternoon trading, has slipped 1.8% over the past three months, while the Dow Jones Transportation Average 
        DJT,
        -1.58%
       has given up 12.2% and the Dow Jones Industrial Average 
        DJIA,
        -1.42%
       has declined 6.1%., Shares of special purpose acquisition company (SPAC) Digital World Acquisition Corp. undefined shot up 17.4% toward a four-month high in premarket trading Tuesday, after former President Donald Trump's social media app Truth Social launched over the long weekend with glitches, but at the top of Apple Inc.'s undefined list of free apps downloaded. The SPAC had announced in October 2021 a plan to merge with Trump Media &amp; Technology Group, which launched Truth Social. The SPAC's stock is on track to open at the highest price seen during regular-session hours since Oct. 25, and above the SPAC's highest stock closing price of $94.20 on Oct. 22. The stock has rallied 88.0% over the past three months while the S&amp;P 500 undefined has lost 7.1%.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-settle-back-above/story.aspx?guid={5900BC67-A379-452A-9FFB-D6098A38EB5C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-23 02:56:02 </td>
   <td style="text-align:left;"> Gold futures settle back above $1,900, at highest since June - MarketWatch </td>
   <td style="text-align:left;"> Gold futures rose Tuesday to their highest finish since June, as Russia's move into Ukraine boosted haven demand for the precious metal. "Gold did move higher over the past couple weeks, rising from approximately $1,800 on February 1st to $1,900 today, in anticipation of Russia invading Ukraine and not pursuing any real diplomatic solution," said Jeff Wright, chief investment officer at Wolfpack Capital. "The safe-haven buying of gold has been real and substantial over this time." April gold 
        GCJ22,
        -0.33%
       rose $7.60, or 0.4%, to settle at $1,907.40 an ounce - the highest intraday level for a most-active contract since June 2, 2021, FactSet data show. , The U.K. announced its own sanctions on five Russian banks and three oligarchs with close links to Moscow.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/inflation-wages-lower-income-americans </td>
   <td style="text-align:left;"> 2022-02-23 02:55:38 </td>
   <td style="text-align:left;"> Did wages keep up with inflation in 2021? Only for the wealthy, analysis shows </td>
   <td style="text-align:left;"> Former Chase chief economist Anthony Chan weighs in on the inflation crisis in America.                                                                                                                                                                                                                                                                                                                                                         , The hottest inflation in four decades is inflicting financial pain on millions of Americans, but no one has been harder hit by rising consumer prices than the lowest-income households, according to a new analysis published on Tuesday.                                                                                                                                                                                                      , Findings from the Penn Wharton Budget Model, a nonpartisan group at the University of Pennsylvania's Wharton School, show that although increases in wage earnings last year offset the higher cost-of-living due to inflation for most households with incomes between $20,000 and $100,000, that was not the case for the poorest Americans.                                                                                                  , MOST SMALL BUSINESSES SINCE 1974 ARE HIKING PRICES TO OFFSET INFLATION                                                                                                                                                                                                                                                                                                                                                                          , The months-long inflation burst is disproportionately hurting lower-income households, largely because they collectively spend more on necessities like energy, food and transportation – which has seen some of the wildest price swings over the past year – while wealthy Americans spend more on services, which has seen a smaller inflation increase.                                                                                     , Shoppers are seen inside a supermarket in Chevy Chase, Maryland on February 17, 2022. ((Photo by Mandel Ngan/AFP via Getty Images) / Getty Images)                                                                                                                                                                                                                                                                                              , For instance, the rise in prices in 2021 produced a wide range of increases in the cost of living across the income spectrum: For the median household, prices rose 6.7% from the end of 2020 to the end of 2021. But for 20% of households, the increase exceeded 8%. For the 5% of households facing the most extreme price increases, inflation was 10% or higher.                                                                           , "These differences arise because consumption patterns vary widely across households," the analysis said. "Households that spend more on goods and services with faster-rising prices naturally face higher inflation. In 2021, a household’s inflation experience was closely linked to the share of its consumption spending accounted for by energy and transportation, items whose prices rose rapidly last year."                           , In all, the lowest-income households – those that earn less than $20,000 a year – saw their earnings rise by just one-third of their total increase in cost-of-living expenses.                                                                                                                                                                                                                                                                 , Billboard on the cruelties of inflation in Coon Rapids, Minnesota. (Universal Images Group via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                     , "Only households with incomes of $100,000 or more saw their annual wage income rise by significantly more than their consumption costs," the analysis said.                                                                                                                                                                                                                                                                                     , Although many workers experienced large wage gains last year, those increases were distributed unevenly across households, with the rise in wage growth concentrated among the lowest-paid 50% of workers. For the 25% of workers with the lowest wages, growth in hourly earnings increased from 4% at the end of 2020 to nearly 6.5% at the end of 2021. By comparison, hourly earnings growth for the highest-paid workers stagnated in 2021., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                     , The wage gains for lower-income households, however, were not enough to overcome the sharp inflation spike experienced by those individuals. For instance, working households with income below $40,000 saw their cost of living jump 6.9%. But inflation for higher-income households – those above $150,000 – was smaller at 6.1%, largely because energy accounts for a smaller share of higher-income households’ spending.                 , Based on 2020 spending data, the median working household saw the cost of their consumption expenditure increase to $3,750 per household. The increase ranged from $2,000 for the lowest-income working households to $5,800 for the wealthiest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malawi/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-23 02:54:17 </td>
   <td style="text-align:left;"> Malawi Inflation Rate Climbs to Over 3-Year High of 12.1% in January </td>
   <td style="text-align:left;"> The annual inflation rate in Malawi rose to 12.1 percent in January of 2022 from 11.5 percent in December. It was the highest inflation rate since November of 2018, boosted by both prices of food (14.2 percent vs 13.6 percent in December) and non-food products (9.6 percent vs 9.5 percent). On a monthly basis, consumer prices advanced 3.6 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/home-depots-stock-tumble-cutting/story.aspx?guid={05C375D7-E691-4495-AB93-85DCE14DE626}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-23 02:51:51 </td>
   <td style="text-align:left;"> Home Depot's stock tumble cutting more than 220 points off the Dow's price - MarketWatch </td>
   <td style="text-align:left;"> Shares of Home Depot Inc. 
        HD,
        -8.85%
       tumbled 9.8% in afternoon trading Tuesday, to pace the Dow Jones Industrial Average's decliners, after the home improvement retailer reported fiscal fourth-quarter results that beat expectations and raised its dividend, but reported gross margin that fell and provided a less than enthusiastic profit outlook. The stock's price decline of $33.84 was shaving about 223 points off the Dow's price, representing about 38% of the Dow's decline of 580 points, or 1.7%. The stock was headed for the biggest percentage decline since dropped 10.4% on March 18, 2020. Meanwhile, shares of Home Depot rival Lowe's Companies 
        LOW,
        -3.64%,
       which reports fiscal fourth-quarter results before Wednesday's open, dropped 4.4% in afternoon trading Tuesday., Former President Donald Trump's social media app that he hopes will rival Twitter launched Monday as he seeks a new digital stage to rally his supporters and fight Big Tech limits on speech a year after he was banned from Twitter, Facebook and YouTube.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spx:ind </td>
   <td style="text-align:left;"> 2022-02-23 02:39:14 </td>
   <td style="text-align:left;"> S&amp;P 500 Hits 4-week Low </td>
   <td style="text-align:left;"> US500 decreased to a 4-week low of 4292 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-23 02:30:37 </td>
   <td style="text-align:left;"> French 10Y Bond Yield Edges Higher </td>
   <td style="text-align:left;"> The yield on the French 10-year OAT rebounded to above 0.7% from the one-week low of 0.68%, as prospects of monetary policy tightening by the ECB, outweighed escalated geopolitical tension in Ukraine. Strong PMI data from Germany and France in addition to soaring inflation across the currency bloc strengthened the case for tighter policy from the central bank. At the same time, Bank of France Governor Francois de Galhau said that inflation and geopolitical risks mean that the ECB could end net asset purchases in the third quarter of 2022, a step that is deemed necessary before rate hikes begin. Meanwhile, preliminary data from INSEE suggests that French GDP growth will slow in the first quarter of 2022 due to restrictions brought by the new wave of coronavirus cases. Early estimates showed the French GDP will grow by 0.3% on the quarter during Q1, and is expected to grow by 0.6% during Q2. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/wheat </td>
   <td style="text-align:left;"> 2022-02-23 02:27:17 </td>
   <td style="text-align:left;"> Wheat Prices Approch 9-Year High </td>
   <td style="text-align:left;"> Wheat prices increased to $8.36 per bushel, approaching a 9-year high of 8.52 hit in November as supply concerns grew after tensions escalated on the Russia Ukraine border. Russian President Vladimir Putin ordered the deployment of troops to two pro-Moscow regions in eastern Ukraine after recognizing them as independent, reigniting fears of an imminent war between the biggest wheat exporters. Additionally, low inventories in Canada and in the US, the third and second-largest exporters globally, added to upside risks. Total stocks of wheat in Canada were 38% down on the year at the end of 2021, as yields were poor due to drought in farms in the Prairie region. Droughts also hampered US production with sales and exports in the week ending February 3rd totaling 17.3 million tonnes, 21% lower than USDA projections of 22.05 million tonnes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/rocket-companies-stock-drops-toward/story.aspx?guid={0474F58B-994D-4118-93C8-4179C24DAED1}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-23 01:48:39 </td>
   <td style="text-align:left;"> Rocket Companies stock drops toward record low after BofA analyst turns bearish - MarketWatch </td>
   <td style="text-align:left;"> Shares of Rocket Companies Inc. 
        RKT,
        -8.13%
       sank 7.3% toward a record low in midday trading Tuesday, after BofA Securities turned bearish on the mortgage financing company, citing concerns over the impact of a rising rate environment. Analyst Mihir Bhatia downgraded the stock to underperform from neutral and slashed the price target to $11 from $21. Bhatia said that while the company's "best-in-class" technology platform and strong retail franchise offers better margin protection than its peers, near-term results are likely to be hurt by the "hostile" market backdrop. Bhatia said refinancing of mortgages comprised 85% of origination volume during the first nine months of 2021, "and are likely headed meaningfully lower as higher rates dampen volumes." The yield on the 10-year Treasury note 
        TMUBMUSD10Y,
        1.944%,
       which influences mortgage rates and refinancings, was at 1.941% in midday trading, up from 1.529% at the end of September.  "Competition and mix-shift (towards partner) could impact margins in 2022 and we expect [Rocket] to continue to invest in marketing, technology and non-mortgage businesses, which could lead to higher-than-expected [operating expenditure] spending. The stock has tumbled 24.5% over the past three months while the S&amp;P 500 
        SPX,
        -1.01%
       has lost 8.1%., Calpers more than quadrupled holdings in meme stocks AMC and GameStop, and also loaded up on Berkshire Hathaway. It trimmed holdings in Palantir.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mdt:us </td>
   <td style="text-align:left;"> 2022-02-23 01:42:37 </td>
   <td style="text-align:left;"> Medtronic earnings meet market expectations at 1.37 USD </td>
   <td style="text-align:left;"> Medtronic (MDT) released earnings per share at 1.37 USD, in line with market expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/milk </td>
   <td style="text-align:left;"> 2022-02-23 01:42:16 </td>
   <td style="text-align:left;"> Milk Hits 14-month High </td>
   <td style="text-align:left;"> Milk increased to a 14-month high of 20.91 USD/CWT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/22/stocks-making-the-biggest-moves-midday-home-depot-tempur-sealy-sofi-houghton-mifflin-and-more.html </td>
   <td style="text-align:left;"> 2022-02-23 01:40:16 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Home Depot, Tempur Sealy, SoFi, Houghton Mifflin and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                           , Check out the companies making headlines in midday trading Tuesday.                                                                                                                                                                                                                                                                                                                                                                                       , Home Depot — Shares of the home improvement retailer fell 8.8% with the broader market sell-off, despite the company reporting a quarterly beat on profit, revenue and comparable store sales for the most recent quarter. Home Depot reported earnings of $3.21 per share and announced a 15% dividend increase.                                                                                                                                         , Medtronic — The medical device maker gained 3.1% after the company reported a mixed quarter, including a revenue miss and an adjusted profit beat. Medtronic said procedure volumes are improving and that strong demand for its heart devices helped drive the quarter.                                                                                                                                                                                  , Kraft Heinz — Shares of the food and beverage company added 5% after the company increased its long-term growth targets and reiterated its adjusted EBITDA guidance for 2022 of between $5.8 billion and $6 billion.                                                                                                                                                                                                                                      , Tempur Sealy — The mattress manufacturer's shares tumbled 19.4% after the company reported adjusted quarterly earnings that missed analysts' estimates by 8 cents per share, as well as revenue for the quarter that fell short of forecasts. The company said results were impacted by costs that outpaced sales.                                                                                                                                        , Houghton Mifflin Harcourt — The publishing company saw its shares jump 15.3% following news that private equity firm Veritas Capital would buy it for $21 per share in cash or about $2.8 billion.                                                                                                                                                                                                                                                        , SoFi — The digital financial services firm's shares fell 9.9% after the company announced it will buy Technisys, a maker of banking software, for about $1.1 billion in stock. SoFi said the deal will help it generate up to $800 million in additional revenue through 2025.                                                                                                                                                                            , Krispy Kreme — The donut company saw its shares rise 8.3% after it reported its first quarterly profit since becoming a public company, though earnings fell short of Wall Street's expectations. CEO Mike Tattersfield said Krispy Kreme is, like the broader restaurant industry, experiencing inflation. But, the company took it as an opportunity to raise prices, which it did twice in the quarter.                                                , DraftKings — Shares of the sports betting company gained 7.5% despite a downgrade by Wells Fargo to equal weight from overweight. The firm cut its price target on DraftKings to $19 per share from $41 per share, noting its concern about the company's path to profitability given its expense increases. Investors may have been buying the dip after the shares fell more than 21% on Friday on a higher than expected adjusted EBITDA loss for 2022., Ford — The automaker's shares fell 4.1% after Wells Fargo said in a note that a spin-off of the company's battery electric vehicle business is not compelling. Wells also reiterated the stock as overweight.                                                                                                                                                                                                                                             , McDonald's — Shares of the fast food chain gained 1.4% before pulling back, after billionaire investor Carl Icahn launched a proxy fight with the company over its treatment of pigs. Icahn is pushing for two board seats and for the chain to to require all its U.S. suppliers to move to "crate-free" pork.                                                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 01:39:05 </td>
   <td style="text-align:left;"> Madrid Stocks Close Slightly Higher </td>
   <td style="text-align:left;"> The Ibex 35 closed slightly higher at 8,493 on Tuesday, but not far from four-week lows amid a global risk-off sentiment due to intensified tensions between Russia and Ukraine. Fears of war in Europe intensified after Russian President Putin recognized the Donetsk and Luhansk separatist regions of the Donbass as independent states, before deploying troops into the territories. On the corporate front, Cellnex (4.6%) and ArcelorMittal (3.2%) led the gains. On the other hand, Enagas (-0.7%) booked losses after posting a net profit loss of EUR 404 million, compared to previous forecasts that the group would lose EUR 380 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 01:32:00 </td>
   <td style="text-align:left;"> Wall Street Sell-Off Resumes </td>
   <td style="text-align:left;"> All three major US stocks lost significant ground Tuesday, with the Dow falling more than 600 points, the S&amp;P 500 down to a 4-week low of below 4,280 and the tech-heavy Nasdaq 100 dropping more than 1.5%. Geopolitical tensions in Europe have roiled global equities as President Vladimir Putin ordered troops into two Moscow-backed separatist regions of eastern Ukraine after announcing that he would recognize their independence. Such a move already triggered sanctions from Western nations. On the economic front, the IHS Markit US Manufacturing PMI rose to 57.5 in February of 2022 from 55.5 in January, beating forecasts of 56, preliminary estimates showed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hd:us </td>
   <td style="text-align:left;"> 2022-02-23 01:26:55 </td>
   <td style="text-align:left;"> Home Depot earnings above expectations at 3.21 USD </td>
   <td style="text-align:left;"> Home Depot (HD) released earnings per share at 3.21 USD, compared to market expectations of 3.18 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hsba:ln </td>
   <td style="text-align:left;"> 2022-02-23 01:23:51 </td>
   <td style="text-align:left;"> HSBC Holdings earnings below expectations at 0.07 GBp </td>
   <td style="text-align:left;"> HSBC Holdings (HSBA) released earnings per share at 0.07 GBp, compared to market expectations of 0.10 GBp. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hsbc:us </td>
   <td style="text-align:left;"> 2022-02-23 01:23:30 </td>
   <td style="text-align:left;"> HSBC earnings below expectations at 0.45 USD </td>
   <td style="text-align:left;"> HSBC (HSBC) released earnings per share at 0.45 USD, compared to market expectations of 0.60 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/home-depot-earnings-lumber-prices </td>
   <td style="text-align:left;"> 2022-02-23 01:19:10 </td>
   <td style="text-align:left;"> Home Depot signals lumber prices will remain ‘volatile’ </td>
   <td style="text-align:left;">  Kevin Mahn, Hennion &amp; Walsh Asset Management president, analyzes the impact of Russia-Ukraine tensions on the economy and weighs in on easing inflation on 'Making Money.'                                                                                                                                                                                                                                                              , Home Depot signaled the swings in lumber prices plaguing builders are not going to abate anytime soon.                                                                                                                                                                                                                                                                                                                                   , "When lumber hit those extraordinary highs in the early part of last year, we saw a dramatic unit productivity fall off, and then we also saw a very quick fall off in lumber prices," Home Depot's chief operating officer and incoming CEO Ted Decker told analysts on the company's fourth quarter earnings call Tuesday. "As lumber prices have recovered through this quarter, we are starting to see some unit pressure on lumber.", According to Decker, prices for framing lumber in the fourth quarter alone ranged from approximately $585 to over $1,200 per thousand board feet, an increase of more than 100%. He emphasized that lumber prices "remain volatile."                                                                                                                                                                                                     , LABOR SHORTAGE HAS HOME DEPOT PUSHING ‘ACCELERATED HIRING PROCESS’                                                                                                                                                                                                                                                                                                                                                                       , Home Depot stock finished down nearly 9% at the end of Tuesday's trading session despite the home improvement retailer reporting strong quarterly sales growth.                                                                                                                                                                                                                                                                          , Fourth-quarter sales were $35.7 billion, an increase of $3.5 billion, or 10.7% year-over-year. Comparable sales for the quarter jumped 8.1%, with U.S. comparable sales climbing 7.6%. Home Depot posted a quarterly net profit $3.4 billion, or $3.21 per share, compared to $2.9 billion, or $2.65 per share, a year ago. Analysts surveyed by Refinitiv were expecting earnings per share of $3.18 and net sales of $34.87 billion.   , The home improvement retailer posted fourth quarter sales of $35.7 billion, an increase of $3.5 billion, or 10.7% year-over-year.  (Getty Images / Getty Images)                                                                                                                                                                                                                                                                         , Departments with above-average comps included plumbing, electrical, building materials, millwork, decor and storage and paint. Meanwhile, kitchen and bath was in line with the company average and hardware, tools, lumber, flooring, appliances and garden were positive but below the company average.                                                                                                                                , Home Depot’s total customer transactions during the quarter fell to 402.5 million from 416.8 million a year ago. However, the average ticket rose to $85.11, compared to $75.69 a year ago. Growth in its average ticket was driven primarily by inflation as the cost of lumber, building materials and copper rose.                                                                                                                    , Big-ticket comp transactions, which are those over $1,000, rose 18% compared to the same period last year. Sales growth from home professionals outpaced do-it-yourself customers during the three-month period ending Jan. 30.                                                                                                                                                                                                          , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                  , Looking ahead, Home Depot is anticipating sales growth and comparable sales growth to be "slightly positive" and diluted earnings-per-share-growth to be in the "low single digits." Home Depot chief financial officer Richard McPhail noted that the company has set a goal to reach $200 billion in annual sales, but did not disclose specific timing for reaching that goal.                                                        , "We intend to get there as soon as we can in a sustainable and profitable way," McPhail said.                                                                                                                                                                                                                                                                                                                                            , Along with its earnings results, Home Depot disclosed that its board of directors has approved a 15% increase in its quarterly dividend to $1.90 per share, which equates to an annual dividend of $7.60 per share. The dividend is payable on March 24 to shareholders of record as of the close of business on March 10. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/putin-trying-to-muddy-the-waters-says-former-deputy-secretary-general-of-nato </td>
   <td style="text-align:left;"> 2022-02-23 01:17:59 </td>
   <td style="text-align:left;"> Putin 'trying to muddy the waters,' says Former deputy secretary general of NATO </td>
   <td style="text-align:left;"> Former Deputy Secretary General of NATO Rose Gottemoeller argues 'Vladimir Putin really loves to stir the pot' amid Ukraine-Russia conflict.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Former Deputy Secretary General of NATO Rose Gottemoeller told FOX Business that Russian President Vladimir Putin is "trying to muddy the waters" as tensions boil over in Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                                                                          , ROSE GOTTEMOELLER: Vladimir Putin really loves to stir the pot and make things as murky as possible. Last night, we were hearing that Russia had already sent peacekeeping troops in. It was on that basis that, and he signed an agreement this morning with both the Donetsk and Luhansk leaders saying that they need that kind of security support, their friendship, so-called friendship agreements, that he will now be providing security support. So he's put in place his fig leaf of a legal measure to provide what he calls peacekeeping troops.                                                                                , RUSSIA-UKRAINE: GERMANY STOPPING NORD STREAM 2 PIPELINE APPROVAL                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , But this morning, I'm reading that what is happening is that the tanks that we see going in are unmarked. They're not marked clearly as Russian army vehicles. And that is exactly what has been happening in Donetsk and Luhansk over the past eight years since the invasion of Crimea. They have been destabilizing the Donbas, but doing so with some plausible deniability. The equipment there, the weapons systems, the uniforms. Nothing is attributable to the Russian armed forces, although we know where the support is coming from. So I fear that's a bit of what's going on now. He's trying to muddy the waters in this way. , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , WATCH THE FULL INTERVIEW BELOW:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Former Deputy Secretary General of NATO Rose Gottemoeller discusses the ongoing Ukraine-Russia conflict as U.S. prepares response to Putin's rising aggression. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 01:11:51 </td>
   <td style="text-align:left;"> Italian Shares Close at the Flatline </td>
   <td style="text-align:left;"> The FTSE MIB Index closed a choppy session at the flatline at 26,044 on Tuesday, remaining at four-week lows amid setbacks in the Ukraine crisis. Investors digested sanction announcements from the UK and the suspension of the certification of the Nord Stream 2 pipeline by Germany after President Putin recognized the Donetsk and Luhansk territories in eastern Ukraine as independent states, before deploying Russian troops into the region. Banks took the most losses on the corporate front, led by UniCredit (-2.1%), Banca Generali (-1.8%), and Bper Banca (-0.9%). On the other hand, Inwit gained 3.7% as investors welcomed the group’s approval of its greenhouse gas emissions reduction targets by 2025. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 01:11:00 </td>
   <td style="text-align:left;"> South African Stocks Recover </td>
   <td style="text-align:left;"> The JSE FTSE All Share index reverted early losses and closed 0.2% up at 75,654 on Tuesday, supported by miners and oil giant Sasol. Sentiment was also lifted by positive results from South African companies as the earnings season entered another week. Investors also monitored the Russia-Ukraine situation, while waiting for Russia's next move. Domestically, the highly anticipated 2022 budget speech set to be delivered on Wednesday by Finance Minister Enoch Godongwana should provide an update on government projections for the economy and the country's fiscal trajectory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/retail/consumer-demand-is-still-building-former-toys-r-us-ceo </td>
   <td style="text-align:left;"> 2022-02-23 01:00:37 </td>
   <td style="text-align:left;"> Consumer demand 'is still building' despite surging inflation: Former Toys 'R' Us CEO </td>
   <td style="text-align:left;"> Former Toys 'R' Us CEO Gerald Storch argues the Fed's intervention to curb inflation will eventually lead to a shift in consumer spending and warns it will end 'badly.'                                                                                                                                                                               , Storch Advisors CEO and former Toys 'R' Us CEO Gerald Storch argued on Tuesday that consumer demand "is still building" despite surging inflation.                                                                                                                                                                                                     , On "Mornings with Maria," Tuesday, Storch argued that, in the short term, the trend is going to continue - especially since "consumers are spending" and "retailers are buying like it’s never going to end."                                                                                                                                          , "But at some point, this thing comes down to Earth and when it does, the only way it ends is badly," he went on to warn.                                                                                                                                                                                                                               , U.S. consumers accelerated their retail spending in January as COVID-19 cases eased nationwide, even as they confronted the hottest inflation in four decades.                                                                                                                                                                                         , Retail sales, a measure of how much consumers spent on a basket of goods ranging from cars to food and gasoline, rose 3.8% from the prior month, the Commerce Department said last Wednesday. Economists surveyed by Refinitiv expected sales to rise 2%; it marked a sharp rebound from December, when sales unexpectedly dropped 2.5%.               , The data came as consumers face the worst inflation spike in 40 years: The government reported earlier this month that the consumer price index climbed 0.6% in January, bringing the year-over-year gain to 7.5%, the highest since June 1982. Wholesale prices also increased, rising 1% in January and 9.7% over a 12-month period.                 , Storch noted that the data shows "that consumer demand is building," which he argued is "driven by unprecedented government payments" and "liquidity from the Fed."                                                                                                                                                                                    , National Retail Federation CEO Matt Shay discusses the surge in retail sales and weighs in on inflation and labor shortages.                                                                                                                                                                                                                           , "People have a lot of money, and they are going to spend it until it stops," he continued.                                                                                                                                                                                                                                                             , Storch subsequently pointed out that "the Fed is going to try to change things" to curb inflation.                                                                                                                                                                                                                                                     , "So they are going to start tightening, raising rates, buying back bonds; the question is, can they get it right?" he posited.INFLATION PROBABLY COSTING MOST AMERICANS AN EXTRA $276 A MONTH                                                                                                                                                          , The Federal Reserve late last month signaled it could "soon" raise interest rates for the first time in three years, paving the way for a March liftoff as policymakers seek to keep prices under control and combat the hottest inflation in nearly four decades.                                                                                     , Storch predicted that consumers will continue to spend for at least the next six months, but warned that "eventually this won’t work anymore."                                                                                                                                                                                                         , He noted that "more money is going to gas" and argued that "there is no doubt, as oil approaches $100 a barrel, that’s going to happen."                                                                                                                                                                                                               , A gallon of gas, on average, cost $3.53 nationwide on Tuesday, according to AAA – up from $2.64 a year ago. In California, the average gas prices are nearly $5 per gallon. Prices are expected to climb higher as the country enters peak travel season and as heightened tensions between Russia and Ukraine threaten to further rattle the market.  , Storch also noted that, as more money goes to food amid surging inflation, "there’s less money for other things."                                                                                                                                                                                                                                      , Storch Advisors CEO and former Toys 'R' Us CEO Gerald Storch notes Americans keep investing in their homes and prices continue to go up, which is benefitting home improvement companies like Home Depot.                                                                                                                                              , Price increases in January were widespread: Although energy prices rose just 0.9% last month from the previous month, they're still up 27% from last year. Gasoline, on average, costs 40% than it did last year. Food prices have also climbed 7% higher over the year.                                                                               , Storch's analysis comes on the heels of retailers Home Depot and Macy’s reporting their quarterly earnings, surpassing analyst expectations for both revenue and profit.                                                                                                                                                                               , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                            , "All these companies can do is project forward what has happened so far," Storch told host Maria Bartiromo, noting that "in retail, we say ‘trend is your friend’ so they’re [retailers are] thinking it will keep going, and I think it will for quite some time."                                                                                    , "When I say ‘end badly’ eventually, as you tighten, tighten, tighten to bring inflation down - the whole purpose is to decrease this consumption, this excess liquidity - and as you do that, these numbers have to come down," he concluded.                                                                                                          , FOX Business’ Megan Henney contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 00:57:00 </td>
   <td style="text-align:left;"> UK Stocks End Higher after 3-Day Drop </td>
   <td style="text-align:left;"> The FTSE 100 closed slightly higher at above 7,500 on Tuesday, after three consecutive sessions of losses as traders continue to follow developments in Ukraine and assess corporate updates. Britain imposed sanctions on Gennady Timchenko and two other billionaires with close links to Vladimir Putin after Russian President Putin recognized the two self-proclaimed separatist republics in Ukraine and ordered troops to go into the regions. Meanwhile, the earnings season continues: HSBC profit doubled last year but the bank said it is battling challenges on several fronts in its key Chinese market. IHG profits came in line with expectations and the company said it will pay a dividend for the first time since 2019. On the other hand, stocks of Hargreaves Lansdown plunged around 14% after reporting a drop in half-year profit. Commodity companies were also lowed, especially those with exposure to either Russia or Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 00:50:00 </td>
   <td style="text-align:left;"> French Stocks Close Muted </td>
   <td style="text-align:left;"> The CAC 40 Index closed muted at 6,788 on Tuesday, remaining at its lowest level since December of 2021 as escalating geopolitical developments continue to weigh on sentiment. The United States and EU stated fresh sanctions will be announced after Russian President Putin officially recognized two separatist territories in the Donbass region as independent states. On the corporate front, Societe Generale fell 1% due to its exposure to Russia through its subsidiary Rosbank. At the same time, Renault fell 3.9% due to exposure through its subsidiary Avtovaz. On the other hand, Worldline jumped 9.7% after beating its fourth quarter expectations while confirming financial targets for 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/currency </td>
   <td style="text-align:left;"> 2022-02-23 00:48:00 </td>
   <td style="text-align:left;"> South African Rand Strengthens </td>
   <td style="text-align:left;"> The South African rand was trading around 15 against USD on Tuesday, after having touched an over one-week low of 15.2 early in the session, on hopes that a full-scale invasion of Ucrania could be averted, despite Russia's recent moves. The currency has been supported by rising prices of precious metals such as gold, which benefits the resource-rich South Africa, along with fresh reform pledges by President Ramaphosa in its pro-business state of the nation address. At the same time, the South African Reserve Bank is expected to hike its main lending rate by another 25 basis points next month, extending a tightening cycle that began in November to anchor inflation expectations. Meanwhile, the prospect of a more hawkish Fed limited further gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 00:43:00 </td>
   <td style="text-align:left;"> European Equities Remain Under Pressure </td>
   <td style="text-align:left;"> European stocks ended a roller-coaster session mostly lower, with the benchmark DAX 30 falling for a fifth consecutive day to its lowest closing level since March 2021. Fears of escalating tensions in Europe hit the mood across global markets. President Vladimir Putin ordered troops into two Moscow-backed separatist regions of eastern Ukraine after announcing that he would recognize their independence, a move that already triggered sanctions from Western nations. On the data front, Germany's Ifo Business Climate indicator jumped to 98.9 in February of 2022, the highest in five months, beating the market's forecast of 96.5. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/22/business/sephora-bloomingdales-sexual-wellness.html </td>
   <td style="text-align:left;"> 2022-02-23 00:38:54 </td>
   <td style="text-align:left;"> Sephora and Bloomingdale's Start to Embrace Sexual Wellness - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , With careful rebranding, word choice and packaging, products like vibrators and lubricants have become newly palatable to higher-end retailers.                                                                                                                                                                                                                                                                                                                                                                                                                                                         , By Sapna Maheshwari                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , A recent email from Sephora promoted the usual: mascaras, face masks and blush compacts. But tucked among those products was a promotion for “intimate care,” encouraging shoppers to try two brands that were new to the retailer — Maude and Dame Products.                                                                                                                                                                                                                                                                                                                                           , A click on a link revealed dozens of artistically styled vibrators, lubricants, oils for sensitive body parts and candles that burn down into massage oil.                                                                                                                                                                                                                                                                                                                                                                                                                                              , Sephora is the latest major retailer to embrace a category known as “sexual wellness,” following Bloomingdale’s and Nordstrom, which started carrying such products last year. With careful rebranding, word choice and packaging, products like vibrators and lubricants have become newly palatable to higher-end retailers that cater to women. It’s a significant evolution in the public acceptance of such products, helped in part by celebrity endorsements, and it comes amid a broader focus on wellness and self-care spurred by the pandemic.                                               , “People are spending more time, energy and disposable income on their own wellness, so it was natural that this expanded to sexual wellness,” said Elizabeth Miller, a vice president who oversees cosmetics at Bloomingdale’s. “It’s evolved so much from what it used to be maybe 10 or 15 years ago to be much more approachable.”                                                                                                                                                                                                                                                                   , Bloomingdale’s — which recently promoted “the ultimate sexual wellness picks” alongside bathrobes and David Yurman jewelry in a Valentine’s Day marketing email — introduced sexual wellness products in May, after an employee in its executive development program pitched the idea. Ms. Miller said some of the retailer’s comfort with the strategy could be traced to the actress Gwyneth Paltrow, whose Goop brand introduced a vibrator last year.                                                                                                                                               , “Seeing Gwyneth Paltrow and Goop take the lead in this category made it feel brand right for us, so I give her a lot of credit,” Ms. Miller said, noting that the products are seen as a draw for Generation Z and millennial shoppers. “Obviously, we reviewed it internally with management to make sure everyone felt comfortable, but the performance has been very strong.”                                                                                                                                                                                                                        , For the start-ups selling adult-oriented products, which often have difficulty navigating advertising guidelines, being promoted and bought alongside other beauty and luxury wares lends credibility.                                                                                                                                                                                                                                                                                                                                                                                                  , “Sephora and these other big beauty retailers are saying it’s just like everything else, you can buy it together,” said Éva Goicochea, founder and chief executive of Maude, which is carried at Bloomingdale’s and Sephora. “It’s impactful in this subtle way.”                                                                                                                                                                                                                                                                                                                                       , Or as Alexandra Fine, co-founder and chief executive of Dame, put it: “Each time somebody puts us in their store, especially a major player like Sephora, it makes it easier for other people to put in their store, easier for investors to invest in us and easier for customers to buy us.”                                                                                                                                                                                                                                                                                                          , Maude and Dame have several things in common. Both start-ups have their headquarters in Williamsburg, Brooklyn, and both are founded and led by women. Maude, which began selling products in 2018, has raised more than $10 million in funding, while Dame, founded in 2014, has raised more than $5 million.                                                                                                                                                                                                                                                                                          , For many years, products like vibrators have been associated with adult stores, often portrayed as seedy or male-oriented, or otherwise found in the fluorescent aisles of drugstores or chains like Walmart. Maude and Dame have sought to elevate the retail experience, incorporating more approachable language and design. Celebrities have also gotten involved: The actress Dakota Johnson works with Maude as an investor and co-creative director, while the singers Demi Lovato and Lily Allen have released sex toys with other big brands.                                                  , Lisa Finn, a brand manager and sex educator for Babeland, the decades-old feminist adult products emporium with stores in Seattle and New York, said conversations about sex toys became more “normalized” during the pandemic as people were suddenly isolated either alone or with their partners. She has increasingly seen them referred to as “pleasure products” or “sexual wellness tools.”                                                                                                                                                                                                      , “This takes some of this idea that sex toys are dirty or kinky,” she said. “And though they absolutely can be, for a lot of folks, these are tools.” That shift “does allow for them to exist in the mainstream,” she said.                                                                                                                                                                                                                                                                                                                                                                             , Tyler Aldridge, director of product at Maude, said the brand was “trying to blend this idea of beauty, wellness and sexual wellness.” Retailers have liked those terms, along with phrases like “sexual health” and “intimate care,” Ms. Goicochea said, adding that Maude was more about “intimacy and romance than explicit sex.” These terms have the benefit of both sounding healthy but stopping short of making any kind of medical claim.                                                                                                                                                       , So while Maude sells $49 vibrators in muted colors, it also sells amber-hued bottles of $25 aloe- and water-based lubricant, $35 unscented massage oil and $18 mineral bath salts. The products’ minimalist design and limited color palette are perhaps no surprise given that Ms. Goicochea previously worked at Everlane, the clothing brand that prioritizes a similar design aesthetic. Maude’s office in Williamsburg similarly boasts plenty of natural light, soaring ceilings, and light wooden shelves and desks, as well as lots of clean white text on dark backgrounds. Clean lines abound., While Dame is more focused on devices, it also carries a $30 “arousal serum,” an $18 aloe-based lubricant and a $95 adult-oriented pillow called, much in keeping with start-up parlance, “Pillo.”                                                                                                                                                                                                                                                                                                                                                                                                      , The companies tend to emphasize their products’ clean and natural ingredients. Descriptions like “aloe-infused” and “contains jojoba oil” are common.                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The styling of the products has caught some retailers by surprise. For example, Mr. Aldridge said Madewell, a clothing retailer, had initially balked at the idea of carrying Maude products on its website. But then a buyer saw the items on a colleague’s desk, marveled that they “looked like a beauty brand” and decided it was worth adding them to the company’s online marketplace.                                                                                                                                                                                                            , Cristina Nuñez, a co-founder of True Beauty Ventures, a venture firm that invested in Maude, said the products were crafted with an eye to the “shelfie,” meaning that people can feel proud and comfortable displaying the items in a photograph on social media.                                                                                                                                                                                                                                                                                                                                      , “We would joke around that the vibe was something that you could leave out on your night stand and not be embarrassed that you had a vibrator on your night stand,” she said. “There wouldn’t be that stigma around it because it wasn’t crass.”                                                                                                                                                                                                                                                                                                                                                        , It’s difficult to estimate the size of the sexual wellness industry, particularly because increasingly it can cross over into beauty products. Many of the key players are private companies, and both Maude and Dame were unwilling to share their sales figures. But Ms. Nuñez, who studied seven or eight similar brands before investing in Maude, said many of the companies her firm had looked at made in the “low single-digit millions” of dollars in revenue. She said she was optimistic about the path to tens of millions of dollars in revenue and beyond.                                , “The opening of retail to these brands will help them get there,” Ms. Nuñez said, “because historically, they really were only able to get to that point through direct-to-consumer, and now they’ve got multiple outlets, from mass, to prestige to luxury department store channels.”                                                                                                                                                                                                                                                                                                                 , Showing up in a major retailer’s emails also helps the brands with their advertising issues, which do still come up. Dame, for instance, recently settled a lawsuit with the Metropolitan Transportation Authority, which had rejected an ad campaign because it was a “sexually oriented business.” The M.T.A.’s move had raised an outcry, given other subway ads for things like erectile dysfunction medications and the Museum of Sex.                                                                                                                                                             , On social media, Facebook and Instagram prohibit ads that promote the sale or use of adult products or services, particularly those focused on sexual pleasure. That means brands have to get creative —  and the notion of “sexual wellness” helps. While Maude may not be able to advertise its devices on these platforms, it can promote its “massage candle,” which melts into massage oil, and its condoms.                                                                                                                                                                                       , “The reality is we’ll still see flags, we’ll still get our warnings,” Ms. Finn of Babeland said, but Babeland’s products are less likely “to be targeted as such if we’re not talking about them as vibrators but rather as ‘tools’ or ‘massagers.’”                                                                                                                                                                                                                                                                                                                                                    , Ms. Fine of Dame said it was an uphill battle. When she tried posting about Dame’s launch with Sephora on LinkedIn this month (“Somebody pinch me — after 5 years of pitching, we are in SEPHORA!”) her post was automatically removed multiple times for violating the professional site’s guidelines against “sexually explicit material or language.” That persisted even when she included a link to an article about the deal. Ms. Fine said she had a similar experience last year when she posted about Dame’s being at Bloomingdale’s.                                                          , “It does feel personal in some way — it’s my voice and me as an entrepreneur, making me feel like I’m inherently unprofessional because of what I do,” she said. But she said she hoped the partnership with Sephora and Bloomingdale’s would dull that perception.                                                                                                                                                                                                                                                                                                                                     , Retailers are largely offering sexual wellness products online — Ms. Miller of Bloomingdale’s pointed out that many customers probably prefer the privacy — though Ms. Goicochea and her team are hoping that Maude will make it to Sephora stores in 2023. One of her colleagues noted that logistics can be tricky at traditional specialty and department stores —  after all, does a vibrator go next to the hair stylers or by the beauty supplements?                                                                                                                                             , Nordstrom sold the products in some stores last year, putting vibrators and other items in 10 self-love-themed pop-up shops. While a company spokeswoman said that “the customer response was very strong,” the products have not become permanent fixtures. “Not all our customers are comfortable approaching the category openly, and we want to be thoughtful and sensitive in our approach,” the spokeswoman said in an email.                                                                                                                                                                     , Still, Ms. Fine, who noted that she had been in talks with Sephora for five years, said even the online presence was a major change from the reception she received when she was starting out. She had applied for an accelerator program that promised to help start-ups grow, where two judges offered feedback on each pitch.                                                                                                                                                                                                                                                                        , “One judge wrote, ‘Is this a joke?’ and that was his whole piece of feedback,” she said. “That is telling of what 2014 was like versus now.”                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-02-23 00:28:00 </td>
   <td style="text-align:left;"> Gold Rally Pauses </td>
   <td style="text-align:left;"> Gold eased to around the key $1,900/oz level on Tuesday after rising to as high as $1,913/oz earlier in the session, the highest in nearly 9 months as investors scooped up short-term profits while waiting for more developments in the Ukraine crisis. Russian President Vladimir Putin recognized on Monday the independence of two breakaway regions in eastern Ukraine and later ordered forces into the area. US president Joe Biden responded by ordering sanctions on the two separatist regions, with the European Union vowing to take additional measures. Oil jumped to a fresh 7-year high on fears that a major conflict could disrupt supply, adding to concerns of further inflationary pressures. Meanwhile, investors are also keeping an eye on the Federal Reserve, as it is expected to raise rates multiple times starting in March to tame rising inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/stock-market </td>
   <td style="text-align:left;"> 2022-02-23 00:21:00 </td>
   <td style="text-align:left;"> Russian Stocks Cut Losses </td>
   <td style="text-align:left;"> The ruble-backed MOEX Russia Index pared losses to close 1.6% higher at 3,084 on Tuesday, after dipping as much as 9% earlier in the session as investors hoped that the sanctions on Moscow will be limited as long as Russian troops do not advance beyond the parts of eastern Ukraine that Putin recognized as independent on Monday. After retreating over 7% each, Russia's main state-backed banks, Sberbank (4.9%) and VTB (4.5%), swung to positive territory following news that they were excluded from initial sanction targets. At the same time, Gazprom shares jumped 8.5%, despite Germany halting the certification of the Nord Stream 2 pipeline, as the Kremlin pledged that Russia would not interrupt any of its gas supplies. Still, investors await the statements from the US and the EU. The Moscow Stock Exchange will be closed on February 23rd amid celebrations of Defender of the Fatherland Day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/copper </td>
   <td style="text-align:left;"> 2022-02-23 00:18:12 </td>
   <td style="text-align:left;"> Copper Hovers at $4.5 </td>
   <td style="text-align:left;"> Copper futures traded around $4.5 per pound, as investors weigh robust demand and supply disruptions against concerns about the escalating crisis over Ukraine. The US and the EU are set to sanction Russia after President Vladimir Putin ordered the deployment of troops to two breakaway regions in eastern Ukraine. Looking to the supply-demand fundamentals, copper usage is surging especially in developed countries, with increasing demand for electric vehicles as well as wind farms, solar panels and the power grid. Also, a shift in politics across high producing countries Chile and Peru ignited civil protest against mining companies that often halt trucks from heading to and returning from the mines, exacerbating already supply tightness due to lack of investment by large miners for the past years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/wmb:us </td>
   <td style="text-align:left;"> 2022-02-23 00:15:45 </td>
   <td style="text-align:left;"> Williams Companies earnings above expectations at 0.39 USD </td>
   <td style="text-align:left;"> Williams Companies (WMB) released earnings per share at 0.39 USD, compared to market expectations of 0.34 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-02-22 23:49:03 </td>
   <td style="text-align:left;"> Loonie Firms Above 1-Year Low </td>
   <td style="text-align:left;"> The Canadian dollar has been trading around 1.27 per USD since late January, remaining stronger than a 1-year low of near $1.3 hit on December 20th, supported by surging oil prices and prospects of higher interest rates. WTI crude oil, a major Canadian export and a big driver of Lonnie’s performance, climbed to levels not seen since 2014 amid tight global oil supplies and as geopolitical risks in Eastern Europe lingered, with the US and its allies announcing sanctions against Russia after it recognized the independence of Ukraine’s breakaway regions and ordered to send more troops to Luhansk and Donetsk. Also, the latest data showed Canada’s annual inflation rate climbed to a 30-year high of 5.1% in January, adding more pressure on the Bank of Canada to hike interest rates during the next monetary policy meeting in March. Meanwhile, Canada's parliament has backed Prime Minister Justin Trudeau's decision to invoke emergency powers to end pandemic-related protests in the capital Ottawa. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/putin-uninterrupted-global-gas-supply-sanctions </td>
   <td style="text-align:left;"> 2022-02-22 23:37:12 </td>
   <td style="text-align:left;"> Putin pledges 'uninterrupted' global gas supply despite looming sanctions </td>
   <td style="text-align:left;"> Here are your FOX Business headlines.                                                                                                                                                                                                                                                                 , Russia President Vladimir Putin on Tuesday said Russia will continue to provide an "uninterrupted" supply of natural gas to global markets just hours after Germany halted the certification of the Nord Stream 2 pipeline.                                                                           , Gas prices hit a seven-year high this month as the threat of a Russian invasion into Ukraine appeared increasingly likely – a spike expected to worsen following Putin’s decision to order "peacekeeping" forces into Eastern Ukraine Monday night.                                                   , Russian President Vladimir Putin listens to a journalist's question during a joint news conference with Hungary Prime Minister Viktor Orban following their talks in the Kremlin in Moscow, Russia. (Yuri Kochetkov/Pool Photo via AP / AP Newsroom)                                                  , RUSSIA-UKRAINE: GERMANY STOPPING NORD STREAM 2 PIPELINE APPROVAL                                                                                                                                                                                                                                      , "Russia intends to continue uninterrupted gas deliveries, including [liquefied natural gas] LNG shipments, to global markets, to upgrade the available infrastructure and to invest more in the gas sector," he said in a letter to the Gas Exporting Countries Forum Tuesday.                        , Officials of the 11-member summit met in Qatar this week to address spiking gas prices as Europe looks to block oil exports from Russia – which supplies roughly 40% of the European market.                                                                                                          , NATO promised severe sanctions if Moscow invaded Ukraine, and nations like the U.S., U.K. and Germany have already taken steps to hit the Kremlin with economic repercussions.                                                                                                                        , "The past few years proved difficult for the global energy sector, which has experienced the dire economic consequences of the Covid-19 pandemic," Putin argued Tuesday.                                                                                                                              , A Russian construction worker speaks on a mobile phone during a ceremony marking the start of Nord Stream pipeline construction in Portovaya Bay some 170 kms (106 miles) northwest from St. Petersburg, Russia, on April 9, 2010.  (AP Photo/Dmitry Lovetsky, File / AP Newsroom)                    , RUSSIA-UKRAINE CRISIS PROMPTS MARKETS TO BRACE FOR HEAVY FALLS                                                                                                                                                                                                                                        , "We are convinced that it is in the interests of the global community to make sure that the energy transition does not become a means of promoting the political and economic interests of certain players. Moreover, it should not be accompanied by sanctions or any other restrictions," he added. , The U.K. announced Tuesday that it has taken steps to target "oligarchs at the heart of Putin’s inner circle" as well as banks that have "bankrolled the Russian occupation of Crimea."                                                                                                               , Tanks move during the Union Courage-2022 Russia-Belarus military drills at the Obuz-Lesnovsky training ground in Belarus, Saturday, Feb. 19, 2022.  (AP Photo/Alexander Zemlianichenko Jr. / AP Newsroom)                                                                                             , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                               , German Chancellor Olaf Scholz said Berlin would "reassess" the certification of the Nord Stream 2 pipeline that would funnel gas from Russia into Europe through its borders – a move the White House applauded.                                                                                      , "We have been in close consultations with Germany overnight and welcome their announcement," White House press secretary Jen Psaki said. "We will be following up with our own measures today." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-22 23:36:00 </td>
   <td style="text-align:left;"> US Stocks Roller-Coaster Continues </td>
   <td style="text-align:left;"> US stocks pared some of their heavy losses on Tuesday morning, with the Dow Jones index recovering from a four-week low of 33,732 to bottom around its 34,000 key psychological level. Investors reacted positively to new data showing an increase in industrial activity in the world’s largest economy. The IHS Markit US Manufacturing PMI rose to 57.5 in February of 2022 from 55.5 in January, beating forecasts of 56, preliminary estimates showed. Still, worries of escalating tensions in Ukraine kept sentiment gloomy. In the latest developments, President Vladimir Putin ordered troops into two Moscow-backed separatist regions of eastern Ukraine after announcing that he would recognize their independence, a move that already triggered sanctions from Western nations. The White House issued an executive order prohibiting economic activity between the two Ukrainian regions and US individuals, while Germany halted the approval of the Nord Stream 2 gas pipeline. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/home-prices-surge-nearly-19-fifth-largest-read-ever </td>
   <td style="text-align:left;"> 2022-02-22 23:32:53 </td>
   <td style="text-align:left;"> Home prices surged nearly 19% last year, marking highest read ever </td>
   <td style="text-align:left;"> Circle Squared Alternative Investments founder Jeff Sica weighs in on Disney’s real estate development and Wall Street’s involvement in the housing market.                                                                                                                                                                                                    , Home prices climbed at the highest pace on record in 2021, surging nearly 19% during the year of red-hot demand driven by low interest rates and low inventory.                                                                                                                                                                                                , Homes are seen for sale in the northwest area of Portland, Oregon. (REUTERS/Steve Dipaola/Files / Reuters Photos)                                                                                                                                                                                                                                              , The S&amp;P CoreLogic Case-Shiller National Home Price Index report released Tuesday showed December's year-over-year gain hit 18.8%, the largest annual price spike the index has seen since it was launched in 1987.                                                                                                                                             , RENTS REACH ‘INSANE’ LEVELS ACROSS US WITH NO END IN SIGHT                                                                                                                                                                                                                                                                                                     , "This is the highest calendar year increase in 34 years of data, and substantially ahead of 2020’s 10.4% gain," S&amp;P DJI managing director Craig Lazzara said in a statement.                                                                                                                                                                                   , "We have previously suggested that the strength in the U.S. housing market is being driven in part by a change in locational preferences as households react to the COVID pandemic," Lazzara noted.                                                                                                                                                            , A realty company's signs rest on several lawns in front of newly constructed houses in Brandon, Miss. (AP Photo/Rogelio V. Solis, File / AP Newsroom)                                                                                                                                                                                                          , "More data will be required to understand whether this demand surge simply represents an acceleration of purchases that would have occurred over the next several years rather than a more permanent secular change," he continued, adding, "In the short term, meanwhile, we should soon begin to see the impact of increasing mortgage rates on home prices.", HOUSING INFLATION, SUPPLY CHAIN CREATE BUILDERS' PERFECT STORM                                                                                                                                                                                                                                                                                                 , Competition in the housing market remains steep as prospective buyers become increasingly willing to shell out more to make a deal with interest rates on the rise. The average price for a 30-year fixed-rate mortgage is approaching 4%, according to Freddie Mac's latest numbers.                                                                          , Existing home sales declined in December but rebounded by 6.7% in January, leaving behind the lowest inventory on record according to the National Association of Realtors' latest data.                                                                                                                                                                       , A man walks past open house signs in front of condominiums for sale in Santa Monica, California. (REUTERS/Lucy Nicholson / Reuters Photos)                                                                                                                                                                                                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                    , Meanwhile, the trends are pushing more and more would-be buyers out of the market at lower price points. According to the NAR, the percentage of first-time buyers responsible for sales dropped to 27% last month, down from 30% in December.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-22 23:13:29 </td>
   <td style="text-align:left;"> Canada Stocks Open Flat after Long Weekend </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, started the week flat on Tuesday, after a long weekend, with aggravating tensions in Eastern Europe fueling higher commodity prices but also risk-aversion. Across sectors, commodity-linked stocks were at the top, with heavyweight energy companies rising on the back of higher oil prices, while health care stocks led losses. The US and its allies announced harsher sanctions against Russia after it recognized the independence of Ukraine’s breakaway regions and ordered to send more troops to Luhansk and Donetsk. Now, traders await the beginning of the banking earnings season in Canada, with analysts forecasting higher December quarter earnings after upbeat results in the September quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belgium/business-confidence </td>
   <td style="text-align:left;"> 2022-02-22 23:13:06 </td>
   <td style="text-align:left;"> Belgium Business Morale at 11-Month Low </td>
   <td style="text-align:left;"> The business confidence barometer in Belgium edged down to 2.3 points in February of 2022 from 2.7 in the previous month. It was the lowest level in business morale since March of 2021, as confidence deteriorated for business related services (13 vs 16.1 in January), largely due to lower market demand expectations, and for the manufacturing industry (0.3 vs 0.8), due to a lower assessment of total order books. On the other hand, improvements in morale took place for the building industry (2.3 vs 0.2), while pessimism eased for trade (-2.6 vs -4.8). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/richmond-fed-manufacturing-index </td>
   <td style="text-align:left;"> 2022-02-22 23:06:00 </td>
   <td style="text-align:left;"> US 5th District Factory Index at 5-Month Low </td>
   <td style="text-align:left;"> The Manufacturing Activity Index in the US fifth district decreased to a 5-month low of 1 in February of 2022 from 8 in the previous month, due to declines in the indexes for shipments (-11 vs 14 in January) and new orders (-3 vs 6). However, the third component in the composite index, employment, increased to 20 from 4 in January. Firms reported decreases in order backlogs, as the index became negative for the first time since June 2020. Vendor lead times increased for many firms as that index remained at near-historic highs. Firms’ perceptions about changes in local business conditions remained slightly negative; however, firms remained optimistic about future conditions. Firms continued to report increasing wages while also citing challenges finding workers with the necessary skills. Firms expect this challenge to last for at least the next six months as the expectations index remained in negative territory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-22 23:03:59 </td>
   <td style="text-align:left;"> Colombia 10Y Bond Yield Hits 12-1/2-year High </td>
   <td style="text-align:left;"> Colombia 10 Year Government Bond Yeld increased to a 12-1/2-year high of 9.165% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-02-22 23:02:00 </td>
   <td style="text-align:left;"> Dollar Little Changed as Traders Await Developments in Ukraine </td>
   <td style="text-align:left;"> The dollar index was around 96 on Tuesday, reversing from early gains, as investors track the crisis in Ukraine and the risks to growth and inflation. Russian president Vladimir Putin recognized on Monday the independence of two breakaway regions in eastern Ukraine and later ordered forces into the area. US president Joe Biden responded by ordering sanctions on the two separatist regions, with the European Union taking additional measures. Moreover, Federal Reserve governor Michelle Bowman suggested Monday that a 50 basis point rate hike at the March meeting could happen if PCE inflation to be released later in the week comes in above expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-22 22:57:00 </td>
   <td style="text-align:left;"> Oil Rises to Highest Since 2014 </td>
   <td style="text-align:left;"> WTI crude futures were changing hands around $93 per barrel on Tuesday morning, having surged more than 4% to an over seven-year high of almost $96 earlier this session on worries about possible supply disruptions amid escalating tensions in Europe. In the latest developments, President Vladimir Putin ordered troops into two Moscow-backed separatist regions of eastern Ukraine after announcing that he would recognize their independence, a move that already triggered sanctions from Western nations. Meanwhile, investors continued to monitor efforts to revive the 2015 Iran nuclear agreement. Analysts suggested that a potential deal could add more than 1 million barrels a day of Iranian crude to the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/currency </td>
   <td style="text-align:left;"> 2022-02-22 22:55:59 </td>
   <td style="text-align:left;"> Aussie Strengthens to Near 1-Month High </td>
   <td style="text-align:left;"> The Australian dollar gained some ground above $0.72 on Tuesday, nearing one-month highs, underpinned by rising commodity prices despite rising concerns over the Russia-Ukraine crisis. Russia ordered troops into breakaway parts in the east of Ukraine, after recognizing their independence, raising the risk of a major conflict. Now, traders await wage growth data for clues on the monetary policy outlook, with the Q4 reading expected to come at 0.7% over the September quarter. Still, analysts said the case for the Reserve Bank of Australia to raise interest rates this year would be strengthened if the reading came at 0.8% or higher. Money markets have fully priced in a move to 0.25% by June of this year, however, minutes of the RBA’s latest meeting showed its Board was yet to be convinced that the acceleration in inflation would be sustained and wanted to see wages respond before lifting rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/composite-pmi </td>
   <td style="text-align:left;"> 2022-02-22 22:53:00 </td>
   <td style="text-align:left;"> US Private Sector Growth Accelerates from 18-Month Low </td>
   <td style="text-align:left;"> The IHS Markit US Composite PMI rose to 56.0 in February 2022, from an 18-month low of 51.1 in the previous month, a preliminary estimate showed as companies reported a notable recovery in demand from COVID-related disruptions at the start of the year. Services firms led the rise, although manufacturers likewise registered a stronger increase in output, buoyed by a slight easing of supply bottlenecks. New business growth among private sector companies was the fastest in seven months and employment expanded further, taking the current sequence of job creation to 20 months and at the strongest pace since last May. On the price front, inflationary pressures across the private sector intensified, with the rate of input price inflation quickening from January’s ten-month low mainly due to higher raw material, transportation and wage costs. Prices charged for goods and services in the US rose at a record pace as companies continued to share additional cost burdens with their clients. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-22 22:49:48 </td>
   <td style="text-align:left;"> US Factory Growth Above Forecast: Markit </td>
   <td style="text-align:left;"> The IHS Markit US Manufacturing PMI increased to 57.5 in February of 2022 from 55.5 in January, beating forecasts of 56, preliminary estimates showed. Production rose at a quicker rate but was hampered by raw material scarcity, supply-chain disruptions and labour shortages. Factory orders increased at a sharp and accelerated pace, prompting firms to resume their hiring efforts after a blip in January. Export sales likewise expanded, with growth hitting a five-month high. Meanwhile, input cost inflation eased to a nine-month low midway through the quarter but additional cost burdens continued to be transferred to clients, as evidenced by another increase in factory gate charges. Manufacturers continued to purchase additional inputs for use in the production process, with the rate of input buying growth improving to a five-month high. Suppliers’ delivery times meanwhile lengthened to the least extent since last May. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/services-pmi </td>
   <td style="text-align:left;"> 2022-02-22 22:49:00 </td>
   <td style="text-align:left;"> US Services Sector Expands More than Expected: Markit </td>
   <td style="text-align:left;"> The IHS Markit US Services PMI rose to 56.7 in February 2022 from 51.2 in the previous month and above market consensus of 53.0, a preliminary estimate showed. Companies noted the strongest expansion in sales since last July. International demand for US services also strengthened in February. With demand conditions improving, service providers continued to hire extra staff. The increase was marked and the fastest in nine months. On the price front, there were sharper increases in both input costs and output prices. Notably, the rate of charge inflation hit a series peak. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cotton </td>
   <td style="text-align:left;"> 2022-02-22 22:47:00 </td>
   <td style="text-align:left;"> Cotton Hits 4-week Low </td>
   <td style="text-align:left;"> Cotton futures at ICE plunged to a four-week low of 120 USd/Lbs in the last week of February, moving away from a 10-year high of 129 USd/Lbs hit earlier this month as investors trimmed their long positions amid tepid demand at domestic spot markets. Still, COVID-19 Omicron variant disruptions and supply constraints have been limiting losses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/currency </td>
   <td style="text-align:left;"> 2022-02-22 22:45:32 </td>
   <td style="text-align:left;"> Turkish Lira Weakens on Geopolitical Tensions </td>
   <td style="text-align:left;"> The Turkish lira weakened to 13.9 per USD in the last week of February, after remaining relatively stable throughout the year, as heightened tensions in Ukraine threatened Turkey’s fragile macroeconomic stability. Fear of war in Europe escalated after the Kremlin deployed troops into Donbass territories recognized as independent states by Moscow, jeopardizing Ankara’s ability to maintain the narrow exchange rate range with its lira protection scheme. Further, prolonged conflict in the Black Sea could keep energy prices high and hamper Turkey’s important tourist inflows. Meanwhile, the Central Bank of Turkey held its key borrowing costs steady for the second time since September in its February meeting, while reviewing its policy framework to encourage more lira usage. The central bank had slashed its benchmark rate by 500bps in between September and December to support exports and growth, pressured by President Tayyip Erdogan pledges, despite a plunging lira and surging inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-02-22 22:40:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Rises for 3rd Day </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index advanced 5% to 2,148 on Tuesday, its highest level since January 11, extending gains for a third straight session, amid stronger demand across all its vessel segments. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, jumped almost 9% to 2,015, its highest level since January 12th; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, increased 155 points to 2,596. Among smaller vessels, the supramax index went up 17 points to 2,359. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/can-you-retire-a-millionaire-with-etfs-alone </td>
   <td style="text-align:left;"> 2022-02-22 22:37:28 </td>
   <td style="text-align:left;"> Can you retire a millionaire with ETFs alone? </td>
   <td style="text-align:left;"> FOX Business’ Lydia Hu reports on supply chain disruptions impacting Roku’s stock and discusses Apple testing technology to unlock iPhone using facial recognition while wearing a mask.                                                                                                                                                                                                                                                                                               , If you want to retire as a millionaire, you'd better get started on your journey soon. At a savings rate ordinary people might be able to afford, it's a process that's achievable, but it can take decades. Fortunately, ETFs serve as a superb investing tool that can make it easier for you to reach that target.                                                                                                                                                                  , Indeed, you can retire a millionaire with ETFs alone, as long as you manage your end to end financial plan appropriately. You'll need to start early enough, invest enough money in an aggressive enough strategy, and convert some money to higher certainty choices as your retirement approaches. In many ways, in fact, ETFs can make your investing job easier as you strive to become a millionaire by retirement.                                                               , REAL ESTATE TECHNOLOGY ETF TARGETS EVOLVING INDUSTRY                                                                                                                                                                                                                                                                                                                                                                                                                                   , Ultimately, an ETF is just a pre-designed collection of investments. The key advantage of any given ETF is that it offers a one-stop-shop to buy multiple investments within the framework of its underlying strategy, often with low overhead costs. That lets you as an investor focus on the overall strategy or strategies that you're interested in following, and then let the ETFs handle the work of picking the specific investments within that strategy.                    , Do you want to invest in the S&amp;P 500? There are several ETFs that will let you track that index. Do you want international exposure without having to become an expert in other countries' accounting rules? There are ETFs that will help there, too. Are you ready to start converting some of your assets to bonds to give you higher-certainty cash flows for your retirement? There are even ETFs that can help out on that front.                                                , If you want to get the long-term benefits of investing without the hassle or effort of scouring financial statements to try to separate winners from losers, ETFs can be a very powerful tool in your arsenal.                                                                                                                                                                                                                                                                         , All that said, there is still no such thing as a free lunch in investing, and ETFs are no exception to that rule. ETFs generally come with ongoing management fees that you'll pay every year for owning them. Still, those fees could be a bargain compared to the hassle of managing a diversified portfolio.                                                                                                                                                                        , In addition to the fees, since ETFs are frequently passively managed to match a strategy, chances are you'll perform somewhere in line with the average of following that strategy. You'll be less likely to wildly outperform, but at the same time, you'll be less likely to wildly trail it, too.                                                                                                                                                                                   , On top of that, since ETFs are simply collections of other assets, you'll need to dig into their holdings to have a clear understanding of what you own. If you want to pay attention to valuation or diversification, you'll need to investigate each of your ETFs to make sure you didn't wind up inadvertently over-invested in an asset you're not really comfortable holding.                                                                                                     , BITCOIN MINING ETF SEES STRONG START                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The following table shows how many years it will take to get to millionaire status starting from $0, depending on how much you can sock away each month and what rate of return you earn. As should be obvious from that table, the more you can sock away and the higher the rate of return you earn, the less time it will take for you to become a millionaire.                                                                                                                     , The following table shows how many years it will take to get to millionaire status starting from $0, depending on how much you can sock away each month and what rate of return you earn. (Data source: Author)                                                                                                                                                                                                                                                                        , Over long periods, the stock market has delivered annualized returns somewhere between the 8% and 10% levels, though those returns are neither guaranteed nor are they smooth. That makes market tracking ETFs a wonderful tool to use over the long run to attempt to reach millionaire status.                                                                                                                                                                                       , As for the monthly investment amounts in that table, those top amounts were not pulled out of thin air. They are based on maxing out 401(k) and IRA contributions for the year. In particular:                                                                                                                                                                                                                                                                                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                            , Of course, it is possible to reach millionaire status saving less than those amounts, but it will take longer to reach that target. Don't despair if you can't start from scratch and reach your savings goal right away. If you start with what you can and add to your investment amounts when you're able, it beats putting off investing until later. After all, the less time you have until you retire, the more you'll have to sock away each month to reach the same end state., So get started now, and give your ETFs the best chance they can of helping you reach retirement as a millionaire. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-22 22:33:00 </td>
   <td style="text-align:left;"> Dow Jones Hits 4-week Low </td>
   <td style="text-align:left;"> All three main US stock indexes opened lower on Tuesday, with the Dow Jones tumbling for a fourth straight session to below its 34,000 key psychological level as fears of escalating tensions in Ukraine rattled markets. In the latest developments, President Vladimir Putin ordered troops into two Moscow-backed separatist regions of eastern Ukraine after announcing that he would recognize their independence, a move that already triggered sanctions from Western nations. The White House issued an executive order prohibiting economic activity between the two Ukrainian regions and US individuals, while Germany halted the approval of the Nord Stream 2 gas pipeline.  Aside from Ukraine headlines, the latest FOMC showed the central bank would not raise interest rates yet but strongly indicated a hike is on the way as soon as March, while it will start unwinding its nearly $9 trillion balance sheet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-22 22:31:58 </td>
   <td style="text-align:left;"> China 10Y Bond Yield Nears Over 8-Week High </td>
   <td style="text-align:left;"> China’s 10-Year Government Bond Yield firmed above 2.8%, nearing levels not seen since December 31st of 2021, as traders digested the central bank’s decision to keep the key loan prime rate (LPR) unchanged, against a backdrop of caution due to the looming tightening cycle of the US Fed. The People’s Bank of China held the LPR steady at 3.7% at its last meeting on February 21st, after cutting rates in the previous two meetings, as expected. At the same time, the PBOC injected 90 billion yuan via reverse repos to address recent liquidity tightness, as growth woes in the world’s 2nd largest economy mount. The nation’s provincial governments said income from land sales will fall, slowing down overall tax income growth, adding fiscal pressure at a time when Beijing pledged more stimulus at the local level. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/case-shiller-home-price-index-yoy </td>
   <td style="text-align:left;"> 2022-02-22 22:08:00 </td>
   <td style="text-align:left;"> US House Prices Rise The Most on Record in 2021 </td>
   <td style="text-align:left;"> In 2021, both the 20-City Composite index (18.6%) and the National index (18.8%) increased at record rates, driven in part by a change in locational preferences as households reacted to the COVID pandemic, low inventory, fast turnaround, and high costs for raw materials. In December alone the S&amp;P CoreLogic Case-Shiller 20-city home price index went up 18.6% year-on-year, accelerating for the first time in 5 months and above market forecasts of 18%. Phoenix (32.5%), Tampa (29.4%), and Miami (27.3%) reported the highest annual gains among the 20 cities. The national index, covering all nine US census divisions, grew 18.8% year-on-year the same as in the previous month. Looking ahead, the impact of increasing mortgage rates should start to weigh on home prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/22/europe/ukraine-putin-reaction-kyiv-intl/index.html </td>
   <td style="text-align:left;"> 2022-02-22 22:05:49 </td>
   <td style="text-align:left;"> Putin's speech was shocking to many, but not to people in Kyiv - CNN </td>
   <td style="text-align:left;"> Kyiv, Ukraine (CNN)The morning after Russian President Vladimir Putin suggested that Ukraine had no right to exist as an independent state, many in the country's capital, Kyiv, appeared glad to see the world waking up to a reality they've been living for years.                                                                , "It's been like this for 15 years. He has always been lying. This is not diplomacy, it's just idiocy," Kyiv resident Nina Vasylenko told CNN.                                                                                                                                                                                        , Waiting for a bus with her friend and former classmate Ala Bovtun, Vasylenko, who said she was "60+" years old, said the fact Putin had officially recognized two breakaway territories in the Donbas region of eastern Ukraine as independent makes no difference.                                                                  , "The Russian army was there a long time ago," she said.                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                      , "Putin does not understand what democracy and diplomacy are, his idea is: 'This is mine and I have to take it.' He wants to take Ukraine, that's what he says -- 'My belle,'" Bovtun said, referring to Putin's crude remark about Ukraine last week.                                                                                , "But I think that most European countries and the US already knew what was going on," she added. "They didn't want to get into a conflict with Russia, they just wanted to get the oil and gas. The slogans about justice, they are just slogans."                                                                                   , While Ukraine's political leaders responded with strong words to the events of Monday night, the reaction on the streets of Kyiv was more muted.                                                                                                                                                                                     , A crowd of protesters gathered in front of the Russian embassy on Tuesday afternoon, waving Ukrainian flags and posters with anti-Russian messages.                                                                                                                                                                                  , In a park next to European Square in Kyiv, an impromptu performance by popular Ukrainian rock band Okean Elzy attracted a small crowd of people. Many joined in and sang along the chorus of one of their biggest hits: "Everything will be good."                                                                                   ,                                                                                                                                                                                                                                                                                                                                      , Kateryna Cherepanova, a 38-year-old from the Khmelnytskyi region of western Ukraine, said the speech Putin delivered on Monday was "disgusting."                                                                                                                                                                                     , "It was crazy, but we were not shocked, he repeated what he wrote before, his imaginary history. I just hope that Russian people were shocked if they were listening to him, because it was so crazy, so surreal," she said.                                                                                                         , Cherepanova said Putin's address, as "creepy" as it was, made little difference to her daily life.                                                                                                                                                                                                                                   , "We've had the war for eight years, now it's official," she added. One thing she is contemplating though is switching from speaking Russian to Ukrainian. Cherepanova grew up speaking Russian -- as many Ukrainians do. "It's a symbolic thing," she said.                                                                          , Cherepanova said she was hoping that listening to Putin's grievance-packed speech would inspire Western countries to send help to Ukraine.                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                      , "I think now is a good moment for [the West] to help us. Not by words, but by actions. But I don't think that it will be something more meaningful than just 'deep concerns' and all that stuff," she said.                                                                                                                          , Asked what she'd like the West to do, she replied: "They can invite Ukraine into NATO. Or [the] European Union. Or put really strict sanctions [on Russia] and stop trading with Russia and block the new gas pipeline," she added.                                                                                                  , Later Tuesday, German Chancellor Olaf Scholz announced that he had halted approval of the controversial Nord Stream 2 pipeline in response to Moscow's actions in eastern Ukraine.                                                                                                                                                   , In a cafe near Kyiv's Saint Sophia Cathedral, Ivan Dymchuk was enjoying a break in the midday sun. He said Putin's speech had made him a bit more worried.                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                      , "Based on his reaction to Ukraine acting as a sovereign country, we can expect anything from him," he said. Dymchuk, 33, has friends in the Vinnytsia region to the west of Kyiv and plans to send his family there if the capital becomes dangerous.                                                                                , Dymchuk added that he would stay in Kyiv, doing what he said was his duty as a member of Ukraine's Territorial Defense Forces, the reserve forces of Ukraine's military. His unit, like many across the country, has ramped up its training in recent weeks.                                                                         , "If anything happens, I will stay here and defend," he added.                                                                                                                                                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                                      , Olga Shevel came to Kyiv early on Tuesday morning from Fastiv, a town 50 miles southwest of the capital.                                                                                                                                                                                                                             , "We saw a lot of tanks moving, one after another, the whole column of military machinery moving towards Kyiv on the Zhytomyr highway. So that made me feel quite anxious," she said.                                                                                                                                                 , "I have two sons and grandchildren, I don't want them to go to war," she said. Shevel said her mother is originally from Russia and so she has relatives in the Altai region, near Russia's borders with Kazakhstan and Mongolia.                                                                                                    , "And then the young boys are being conscripted and they don't even know where they are going," she added. "I've seen a picture of the Russian soldiers, very young boys ... somewhere in Rostov region in some kind of a hut or a tent lying on the floor, just on the tiles, sleeping. As a mother I felt sorry for them," she said., Yulia Kesaieva in Kyiv contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/house-price-index-mom </td>
   <td style="text-align:left;"> 2022-02-22 22:01:00 </td>
   <td style="text-align:left;"> US Home Prices Rise 1.2% in December: FHFA </td>
   <td style="text-align:left;"> The average prices of single-family houses with mortgages guaranteed by Fannie Mae and Freddie Mac in the United States increased 1.2 percent from a month earlier in December 2021, the same pace as in November. Year-on-year, house prices jumped 17.6 percent in December, also at the same rate as in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/entertainment-arts-60476760?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-22 21:51:32 </td>
   <td style="text-align:left;"> National Portrait Gallery's BP sponsorship to end </td>
   <td style="text-align:left;"> Energy giant BP's sponsorship of the National Portrait Gallery is to end, following years of protests against the funding.                                                                                                                                                                                      , BP has backed the gallery's prestigious portrait prize for more than 30 years.                                                                                                                                                                                                                                  , In 2019, past winners were among the artists who called on the gallery to cut ties with the firm, and protesters covered themselves in oil at the venue.                                                                                                                                                        , Pressure group Culture Unstained called the news "a major win for the campaign against fossil fuel sponsorship".                                                                                                                                                                                                , National Portrait Gallery director Nicholas Cullinan said he was "hugely grateful to BP for its long-term support" of the award.                                                                                                                                                                                , The funding has "fostered creativity, encouraged portrait painting for over 30 years and given a platform to artists from around the world, as well as providing inspiration and enjoyment for audiences across the UK", he said.                                                                               , The BP Portrait Award is not being staged in 2021 and 2022 while the London gallery is closed for redevelopment. The funds are instead being used for the gallery's other work ahead of its re-opening next year.                                                                                               , The sponsorship will end in December, when the current contract expires. BP said it would look for "new ways to best use our talent, experience, and resources" as it tried to achieve its target of becoming net-zero by 2050.                                                                                 , It's not clear how the competition will be funded in the future, with arts organisations and corporations tightening their belts due to the pandemic.                                                                                                                                                           , The sponsorship came under scrutiny in 2019, when Gary Hume, an artist and judge of that year's portrait award, said it was time to look elsewhere for money. Hume told BBC Radio 4's Today programme that BP "was now a problem".                                                                              , Dozens of other artists, including Sir Antony Gormley, Anish Kapoor, Sarah Lucas and Rachel Whiteread, signed a letter asking the gallery to end the sponsorship deal because of "BP's role in furthering the climate crisis".                                                                                  , Semi-naked protestors also made their views clear when they drenched themselves in oil at the gallery in October 2019.                                                                                                                                                                                          , The Royal Shakespeare Company (RSC) and BP ended their partnership in 2019, while BP and The Tate cut ties in 2017. The firm still sponsors the British Museum and the Royal Opera House.                                                                                                                       , BP executive Louise Kingham said on Tuesday: "We are immensely proud of our role in championing British arts and culture for over 30 years, but the BP of today is a very different company from when we first started our partnership with the National Portrait Gallery."                                     , BP has pledged to reduce its reliance on fossil fuels and become an "integrated energy company".                                                                                                                                                                                                                , Culture Unstained co-director Jess Worth said: "While the gallery won't say it out loud, this is clearly a vote of no confidence in BP's business. The company spent 30 years painting a picture of itself as a responsible philanthropist but it is rapidly running out of places to clean up its toxic image.", The National Portrait Gallery's portrait award is arguably the world's most prestigious such prize.                                                                                                                                                                                                             , The last winner was Brighton-based artist Charlie Schaffer, who won 2019's £35,000 first prize for his portrait of a close friend, titled Imara In Her Winter Coat.                                                                                                                                             , A fresh perspective on how Hitler brutally seized and kept power                                                                                                                                                                                                                                                , The music that inspired the show, from Leonard Cohen to Joy Division                                                                                                                                                                                                                                            , Why did a glamorous start up trick its own staff?                                                                                                                                                                                                                                                               , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-22 21:34:00 </td>
   <td style="text-align:left;"> South African 10Y Bond Yield at 1-Week High </td>
   <td style="text-align:left;"> South Africa's benchmark 10-year bond yield was at 9.2%, its highest since February 15th, as investors focused on prospects of monetary policy tightening by the South African Reserve Bank, despite mounting concerns over the global impact of geopolitical tensions. South Africa’s central bank is expected to continue its hiking cycle next month, raising its main lending rate by another 25 points, as inflation dropped to 5.7% in January from 5.9% in December but remains close to the top of its target range of 3.6%. Burgeoning oil and food prices are expected to continue adding upward pressure on consumer prices in the coming months. Meanwhile, President Ramaphosa's pro-business state of the nation address emphasized the government remains committed to implementing structural reforms needed to boost the economy and attract investment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/22/64percent-of-unemployed-men-in-their-30s-have-criminal-records-a-barrier-to-landing-a-job.html </td>
   <td style="text-align:left;"> 2022-02-22 21:30:01 </td>
   <td style="text-align:left;"> 64% of unemployed men in their 30s have criminal records, a barrier to landing a job </td>
   <td style="text-align:left;"> , More than half of unemployed men in their 30s have criminal records — a dynamic with implications for hiring practices and ongoing challenges finding workers during the pandemic-era labor crunch, according to research published by economists at RAND Corp.                                                                                 , About 6% of men at age 35 are unemployed, according to the study. By that age, 64% of those jobless males had been arrested as adults. Forty-six percent had been convicted of a crime, and 27% had been incarcerated.                                                                                                                          , The study is the first to estimate the prevalence of a criminal record among the unemployed population, according to RAND.                                                                                                                                                                                                                      , More from Personal Finance:This HR manager took 3 months off with pay to hike in EuropeA petition for an $18 minimum wage is gaining signatures in CaliforniaDespite rising wages, 61% of Americans are still living paycheck to paycheck                                                                                                       , Many of these individuals have had difficulty finding employment despite arrests and convictions that happened years earlier, which suggests the stigma of a criminal record hurts job seekers for years, according to Shawn Bushway, lead author of the study and a senior policy researcher at RAND, a nonprofit research organization.       , That stigma hurts an applicant's chances and compounds issues such as lower levels of education that already diminish their likelihood of success, he said.                                                                                                                                                                                     , "These folks often ... have an additional barrier unrelated to job skill: the ability to get a job if there's a background check," said Bushway, who's also a professor of public administration and policy at the State University of New York at Albany.                                                                                      , "If you're an employer and have a background check that's very restrictive, you're going to not hire a lot of people," he added.                                                                                                                                                                                                                , Meanwhile, employers have had a tough time finding workers to fill vacancies. There have been record job openings and levels of quitting in recent months, trends linked to the "Great Resignation" or "Great Reshuffle."                                                                                                                       , Millions of Americans have stayed out of the workforce even as the U.S. economy has come out of hibernation — whether due to Covid-related health fears, child care duties, early retirements or other reasons — effectively shrinking the labor pool.                                                                                          , However, research suggests a criminal record reduces access to job opportunities.                                                                                                                                                                                                                                                               , Applicants without criminal records were 60% more likely to get a job callback from employers, even though the records of other applicants were minor (a single low-level, nonviolent felony approximately two years earlier), according to a 2017 University of Michigan study.                                                                , "There are lots of people who get convicted once and never get convicted again. The majority of people who go to prison don't go back," Bushway said. "How long does this record have to hang over their head?"                                                                                                                                 , The probability of unemployed men in their 30s having a criminal record isn't correlated to race — the chances are similar across white, Black and Hispanic jobless men, according to RAND.                                                                                                                                                     , However, this doesn't mean the labor experience is felt similarly across racial groups. That's because 35-year-old Black men are almost twice as likely as white men to be unemployed (a 9% unemployment rate versus 5%, respectively), according to the study. Black men are also much more likely than other groups to have a criminal record., The RAND study analyzed data from the National Longitudinal Survey of Youth, examining the experience of about 9,000 men from 1997 through 2017. The study defines unemployment as being without a job for four weeks or more over the past year.                                                                                               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                          , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                          , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                              , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hungary/interest-rate </td>
   <td style="text-align:left;"> 2022-02-22 21:12:00 </td>
   <td style="text-align:left;"> Hungary Hikes Key Interest Rate as Expected </td>
   <td style="text-align:left;"> The National Bank of Hungary raised its benchmark base rate by 50bps to 3.4 percent on February 22nd, the highest since October of 2013 matching market expectations. It was the ninth consecutive rate hike, as the central bank noted stronger than expected inflationary pressure during January and mounting Russia-Ukraine geopolitical tensions fuelled market uncertainty. Consumer prices rose 7.9 percent in January, the highest in almost 15 years and well above the central bank’s target of 2%-4%, driven by commodity, crop, and energy prices. Meanwhile, the MNB expects GDP to grow by 5% in 2022 as monthly indicators suggest a continuation of the recovery through  2022. Looking forward, the Monetary Council will continue the cycle of interest rate hikes until the outlook for inflation stabilizes at the central bank’s target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/netherlands/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-22 21:01:05 </td>
   <td style="text-align:left;"> Netherlands 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Netherlands 10 Year Government Bond Yeld increased to a 3-year high of 0.503% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/producer-prices-change </td>
   <td style="text-align:left;"> 2022-02-22 20:59:11 </td>
   <td style="text-align:left;"> Irish Wholesale Price Inflation Eases in January </td>
   <td style="text-align:left;"> Ireland’s wholesale prices rose by 3.5 percent from a year earlier in January of 2022, easing from the four-year high of 4.5 percent in the previous month. Prices rose at a slower rate for export sales (3.3 percent vs 4.3 percent in December 2021), while costs picked up for home sales (7.9 percent vs 5.9 percent). On a monthly basis, wholesale prices advanced by 0.1 percent, after remaining unchanged in the prior month. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-02-23 10:54:39 UTC +8

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
   <td style="text-align:left;"> 2022-02-23 10:54:09 </td>
   <td style="text-align:left;"> $SPY Above $433, and I’m buying $440 Calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:53:53 </td>
   <td style="text-align:left;"> $SPY these are about to print 🤩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:53:46 </td>
   <td style="text-align:left;"> $SPY potato’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:53:38 </td>
   <td style="text-align:left;"> $SPY 440 train coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:53:10 </td>
   <td style="text-align:left;"> $SPY run run run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:52:36 </td>
   <td style="text-align:left;"> $SPY anyway  to kick all the democrats  out. I&amp;#39;m simple just want 1.99 gas , watch sports w/o politics,  and pay under $20 for i bag of food. 
https://www.foxbusiness.com/politics/white-house-says-americans-should-expect-higher-energy-prices-amid-russia-ukraine-tensions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:52:27 </td>
   <td style="text-align:left;"> $SPY $vix will fold watch out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:52:24 </td>
   <td style="text-align:left;"> $SPY Bear Market SPY 396/329

When weekly falls below 50MA, its kinda of big deal.  Monthly,  Quarterly already rolled over. Any rallies are just gasp for air as this is drowning IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:52:22 </td>
   <td style="text-align:left;"> $SPY Lol China sanctioning US companies who sell arms to Taiwan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:52:18 </td>
   <td style="text-align:left;"> $SPY  Futures still green 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:52:17 </td>
   <td style="text-align:left;"> $SPY tomorrow is the day, I can feel it in my potatoes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:52:16 </td>
   <td style="text-align:left;"> Sell the rumor, buy the invasion. $SPY $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:52:09 </td>
   <td style="text-align:left;"> $SPY Went to the grocery store and they didn’t have any Choca Choca chip! Tf is going on Brandon??! I want that shit too! 👎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:52:07 </td>
   <td style="text-align:left;"> $SPY look guys there are a lot of sour grapes out tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:52:06 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $DWAC $SPY $TSLA orange man bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:51:38 </td>
   <td style="text-align:left;"> $SPY $BTC.X You idiots are long the internet scam coins, I am long the New Bitcoin which is vaccinated sperm! My 4X jabbed semen will make super soldier babies to defeat the Russians. You ANTI-VAXXERS and your cum can only make muggle babies, my wife and I will give birth to MEGATRON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:51:32 </td>
   <td style="text-align:left;"> Remember this $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:51:24 </td>
   <td style="text-align:left;"> $SPY When excessive put buying is the only bullish signal, well... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:51:05 </td>
   <td style="text-align:left;"> $SPY $DJIA IT BETTER FUCKING NOT ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:51:00 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:50:53 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:50:51 </td>
   <td style="text-align:left;"> $SPY hold onto your seatbelt, we going for a ride </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:50:50 </td>
   <td style="text-align:left;"> $SPY $QQQ the market doesn’t like this waiting around whats going to happen between russia and ukraine, i think the markets just want a resolution or even war, “sadly” for it to move on from this. what is going now, its uncertainty, thats why the market sucks. thats why i am not bullish now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:50:17 </td>
   <td style="text-align:left;"> $SPY Sanctions to include; 
- Vodka and orange juice will not be allowed to mix together in the same glass. 
- Nesting dolls will be permanently glued shut. 
- The proletariat will only be allowed to uprise once a month. 
$QQQ $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:50:11 </td>
   <td style="text-align:left;"> $SPY Watch for the pump tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:50:03 </td>
   <td style="text-align:left;"> $SPY FUD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:49:54 </td>
   <td style="text-align:left;"> $SPY could not break our resistance this morning.  The sellers took over to $426 target </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:49:29 </td>
   <td style="text-align:left;"> $SPY now looking at futures feels that I covered under pressure . Didn’t want to lose profits. Oh well cash is king ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:49:16 </td>
   <td style="text-align:left;"> $SPY $450 EOW when Russia withdraws its forrces amidst sanctions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:48:59 </td>
   <td style="text-align:left;"> $SPY 400 eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:48:24 </td>
   <td style="text-align:left;"> $SPY DIX fell below 45% for first time, GEX also went negative </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:47:41 </td>
   <td style="text-align:left;"> $SPY Very bearish short term. Let&amp;#39;s see what happens.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:47:37 </td>
   <td style="text-align:left;"> $SPY “Whenever you’re worried about position sizing it’s best just to ignore it, if you go all in then you’re only a 20 bagger away from retirement.” - Call_Me_Put </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:47:28 </td>
   <td style="text-align:left;"> $SPY whatcha doing dxy?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:47:27 </td>
   <td style="text-align:left;"> $SPY eh going down again for nothing, correction is boring </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:47:25 </td>
   <td style="text-align:left;"> $SPY red open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:47:16 </td>
   <td style="text-align:left;"> $SPY tomorrow get your options open baby and the day after short that bitch. too easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:46:56 </td>
   <td style="text-align:left;"> $SPY I don’t care which way it goes with my straddle, but…puts do pay better 💰🇷🇺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:46:53 </td>
   <td style="text-align:left;"> $SPY what a day 🌙 🍄🤩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:46:48 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:46:44 </td>
   <td style="text-align:left;"> $SPY Hold up $AMZN is doing share split </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:46:26 </td>
   <td style="text-align:left;"> $SPY I see a 10 dollar day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:45:58 </td>
   <td style="text-align:left;"> $SPY Likely bleed before Europe before 4280 test. Go long at 4280 if you’re brave. Me, I’ll keep shorting the pops. We are officially maintaining under the last line of defense at ~4350. This is not bullish. However, that doesn’t mean that we don’t pop, tomorrow. Need more liquidity in an almost completely illiquid environment. Bears will get their low test. Bulls will get their 50%. It’s not over yet. Just be well positioned for the limit down. It will come. If you are young, this is one of the most important moments of your life, financially speaking. We have reached the moment of truth where volatility will remain elevated for quite some time. Vix under 20 won’t be seen for months. How high will the vix go? Impossible to tell. But don’t short it until at least 80 and have a healthy account to back it up. Short oil? Not yet. Buy the 500 dip? Not yet. Sit on your hands unless you have enough money to speculate. It’s about to be much more wild than you’ve seen thus far. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:45:57 </td>
   <td style="text-align:left;"> $SPY Biden made it clear today in his speech - &amp;quot;Expect higher energy prices&amp;quot; 1) Biden dismantled XL pipeline 2) cancelled all licenses to drill on federal lands 3) begging OPEC and Russia to sell us more oil.  THEN he goes to blame Russia for the higher energy prices here.  Biden did this.  All of it.   $USO $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:45:39 </td>
   <td style="text-align:left;"> $SPY lol. Daily HnS lately feeling 2018ish. Crazy that was 3.5 years ago. All the other sell offs recovered so fast for years. Impressive to see this sustained selling. Wonder where the relief is? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:45:36 </td>
   <td style="text-align:left;"> $SPY Gonna bittersweet symphony my way to 440

https://www.youtube.com/watch?v=1lyu1KKwC74&amp;amp;list=RDMM&amp;amp;index=48 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:45:24 </td>
   <td style="text-align:left;"> $SPY is trending the last 24hrs across Twitter and StockTwits - looking for a strong push tmw. This dashboard allows you to track the trends across social and stay ahead of the movements👇 
 
https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=pw_20220222 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:45:21 </td>
   <td style="text-align:left;"> $SPY I got it ! Let’s have a standoff with Russia right quick 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:45:13 </td>
   <td style="text-align:left;"> $SPY futures always either are, or are nit, ripping. And we should tale solace in the consistency. 0.01 green? RIPPING! -4% red? NOT RIPPING! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:45:06 </td>
   <td style="text-align:left;"> $SPY okay we gapping down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:44:59 </td>
   <td style="text-align:left;"> $SPY Looks like S and P wants to hit 4,000 near term to complete an ABC move to the down side. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:44:38 </td>
   <td style="text-align:left;"> $SPY $QQQ Tom Lee interview today, did not mention anything about his face ripper rally for february… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:44:29 </td>
   <td style="text-align:left;"> $SPY dearish💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:44:01 </td>
   <td style="text-align:left;"> $SPY $DWAC Remember when the “experts” said Trump was going to get us into a war?  Good times! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:56 </td>
   <td style="text-align:left;"> $SPY @Stocktwits 😔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:56 </td>
   <td style="text-align:left;"> $SPY If Biden wants to see results then he should put a sanction on vodka and krokodil. Russians will not respond to anything else. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:54 </td>
   <td style="text-align:left;"> $SPY these are the type of retail traders we need liquidated before the end of 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:53 </td>
   <td style="text-align:left;"> S&amp;amp;P 500 Biggest Gainers &amp;amp; Losers for 02/22/22- $SPX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:51 </td>
   <td style="text-align:left;"> $SPY Why are democrats so scared of guns 🔫🤷‍♂️ When I went to high school in Florida the entire student parking lot we’re trucks with a gun rack and gun in the back window 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:48 </td>
   <td style="text-align:left;"> New Analysis: It is time to sell before things get worse? Or is this a golden opportunity? https://cracked.market/2022/02/it-is-time-to-sell-before-things-get-worse-or-is-this-a-golden-opportunity/ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:46 </td>
   <td style="text-align:left;"> latex6274de57b1d066e62e317d7c1f804271$. Don’t get too used to it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:42 </td>
   <td style="text-align:left;"> $SPY “The Fed should have a special meeting, right now, to end QE,” Summers told Bloomberg Television’s “Wall Street Week” with David Westin. “It is nothing short of preposterous that in an economy with 7.5% inflation, that in an economy with the tightest labor market we’ve seen in two generations, that the central bank is still as we speak growing its balance sheet.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:42 </td>
   <td style="text-align:left;"> $SPY head and shoulders everywhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:33 </td>
   <td style="text-align:left;"> $SPY what shitcoin should I buy that will x5 soon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:17 </td>
   <td style="text-align:left;"> $SPY o shit here comes Niagara Falls 🧞‍♂️🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:15 </td>
   <td style="text-align:left;"> $SPY update on my TA. Very bearish guys. Couple all of this with rate hikes, war tensions, inflation, covid, and so many stocks being overvalued. The tech sell-off does not appear to be bouncing anytime soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:43:15 </td>
   <td style="text-align:left;"> $SPY futes futin&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:42:54 </td>
   <td style="text-align:left;"> $SPY Putins reasoning is spooky similar to Hitlers reasoning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:42:42 </td>
   <td style="text-align:left;"> $SPY what are putins sanctions? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:42:38 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $DWAC $SPY $TSLA I know it’s wishful thinking. But I hope one day we can get to a point to where we’re not so focused on propaganda, wars, unlimited paper money, politics, etc. We still act so primitive towards one another. When we should be trying to understand one another more and wipe out corruption and evil. 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:42:28 </td>
   <td style="text-align:left;"> $SPY Forget Oil, Forget gas... If Putin stops all exotic metal exports.. - Dow 10k again... in 3 months.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:42:28 </td>
   <td style="text-align:left;"> $SPY ahhhhhh yah we found support we found support, now go up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:42:06 </td>
   <td style="text-align:left;"> $SPY Moon soon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:41:47 </td>
   <td style="text-align:left;"> $SPY Fuckin rip already so I can cash out these $VXX puts 

Come on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:41:45 </td>
   <td style="text-align:left;"> $SPY the theta decay+ losing 1 trading day, by time market opens your calls be down 20-40% even if it&amp;#39;s green overnight.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:41:43 </td>
   <td style="text-align:left;"> The chart below diagrams the pattern on State Street’s S&amp;amp;P 500 Index ETF ($SPY). The key feature of this pattern is that it demonstrates how the price action has no longer continued its upward trend. It fails to make a higher swing high. This sets the stage for the price to begin making lower swing lows, which are the key characteristic of downward trends. $SPX  
 
The coincidental timing of the indexes falling into correction territory with a completed head-and-shoulders pattern draws attention to the impact of a downward trend right now. Under the current state of investor concern, it wouldn’t take much for prices to continue trending lower toward bear market territory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:41:43 </td>
   <td style="text-align:left;"> $SPY I can’t stop laughing at the bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:41:06 </td>
   <td style="text-align:left;"> $SPY 

Sooooo you’re still distracted than? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:40:50 </td>
   <td style="text-align:left;"> $SPY $RUT $IWM 
I like. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:40:47 </td>
   <td style="text-align:left;"> $SPY Mooooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:40:41 </td>
   <td style="text-align:left;"> $SPY coiled like a rattlesnake somebody gonna get bite </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:40:38 </td>
   <td style="text-align:left;"> $SPY Damn it’s almost March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:40:36 </td>
   <td style="text-align:left;"> $SPY songoku told me to btd when spy drop from 480 to 470 now im behind wendys giving handies 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:40:17 </td>
   <td style="text-align:left;"> $SPY why would americans care about what is happening in Ukraine.  Most americans cannot even point Ukraine on the map. 
https://youtu.be/umpalMtQE50?t=56 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:40:05 </td>
   <td style="text-align:left;"> Every time you take a trade that&amp;#39;s not a part of your system, you simply disrespect all the hard you work you put in. FOLLOW YOUR PROCCESS  🙌 $SPY #PRESSIT $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:59 </td>
   <td style="text-align:left;"> These dips are gift to long term holders $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:55 </td>
   <td style="text-align:left;"> $SPY rip them futes downwards. Spy testing 007 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:49 </td>
   <td style="text-align:left;"> $SPY this is one I can&amp;#39;t call tonight my guess is bulls pull out for at least green open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:44 </td>
   <td style="text-align:left;"> $SPY their  is always rude DWAC site go post over their  you  will  find  your  kind </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA all it take is a little push. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:25 </td>
   <td style="text-align:left;"> $SPY Watching the 4 hour chart from here until morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:25 </td>
   <td style="text-align:left;"> $SPY how did sonic get banned again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:11 </td>
   <td style="text-align:left;"> $SPY wonder if market tanks while I sleep tonight ?🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:11 </td>
   <td style="text-align:left;"> $TDOC $DWAC $SPY  
 
Account Challenge Update:-  
Start Date: Feb 2, 2022  
Starting Balance: $1,800  
Current Balance: $89,637  
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
   
Watch out for next play👓 http://stock-options.topwinningroom.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:09 </td>
   <td style="text-align:left;"> $SPY emergencies act is fu#king awesome. They only go after the losers. I live in the tyrannical land of Canada and fully support this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:04 </td>
   <td style="text-align:left;"> $SPY btc tank8ng spy you next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:39:03 </td>
   <td style="text-align:left;"> $SPY Have the every other hour press release about russia invading stopped? 

I missed most of day but I am not seeing any </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:38:35 </td>
   <td style="text-align:left;"> $SPY well gapy down Wednesday I guess🤷🏻‍♂️😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:38:06 </td>
   <td style="text-align:left;"> $SPY 🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:38:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $BTC.X 

Thank the lord for Biden , his amazing vaccines, containing/eradicating the virus with his well executed plan (something trump couldn’t do), his push to get conservative CEOs to fix their supply chain issues and his strong arm stance to JPOW, curbing inflation. Not only this, but he also was able to stand up too and scare off Putin. 

What a blessing that Biden is in and Trump is out. 

Not to mention he has the best VP in the history of this nation at his side in Kamala Harris.

No more Republicans please. 
🙏🙌🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:38:00 </td>
   <td style="text-align:left;"> $SPY looks like it holding, can the bears strike and break the bull momentum? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:37:48 </td>
   <td style="text-align:left;"> $SPY so many  rude imbecile need to get  a life </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:37:43 </td>
   <td style="text-align:left;"> $SPY $DWAC 

https://mobile.twitter.com/RandPaul/status/1493946605942325250?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1493946605942325250%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fwww.infowars.com%2Fbreaking-news%2F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:37:42 </td>
   <td style="text-align:left;"> $SPY How does a person like moo get banned immediately after getting unbanned? He/she never says anything that’s fracking offensive lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:37:19 </td>
   <td style="text-align:left;"> $SPY ready for war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:37:14 </td>
   <td style="text-align:left;"> $SPY Queen Elizabeth is on her deathbed. Hope she doesn’t suffer, good bless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:36:40 </td>
   <td style="text-align:left;"> $SPY okay futues are not rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:36:40 </td>
   <td style="text-align:left;"> $SPY Futes MM be like: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:36:36 </td>
   <td style="text-align:left;"> $SPY bears 🐻 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:36:33 </td>
   <td style="text-align:left;"> $SPY parts of Ukraine probably remains independent and Russia will just take over other parts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:36:14 </td>
   <td style="text-align:left;"> $SPY bulls be like but muhhh charts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:36:03 </td>
   <td style="text-align:left;"> $SPY I think bears got shaken out today It was a Sharp V  
Embarrassing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:35:59 </td>
   <td style="text-align:left;"> $SPY can Ukraine bring down economy in United States?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:35:57 </td>
   <td style="text-align:left;"> $SPY 435  #WhosKnow???  #DojiCandle  Bounce to 443 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:35:56 </td>
   <td style="text-align:left;"> $SPY “look at the futes!! They’re rippppin” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:35:45 </td>
   <td style="text-align:left;"> $SPY man oh man . Weakest shit I’ve ever laid eyes on is these futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:35:37 </td>
   <td style="text-align:left;"> $SPY udder bull that sonicmerlin banned </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:35:17 </td>
   <td style="text-align:left;"> $SPY if you&amp;#39;re still a biden supporters in 2022 then you need to ask yourself &amp;quot;why am I such a c uck?&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:35:16 </td>
   <td style="text-align:left;"> $SPY The eyes of March gonna be up on us 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:34:42 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:34:30 </td>
   <td style="text-align:left;"> $SPY green to red tomorrow!! Maybe just red!! Time will only tell!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:34:21 </td>
   <td style="text-align:left;"> $SPY FUTES are …. ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:34:10 </td>
   <td style="text-align:left;"> $SPY a sell off to 360 is not such a bad thing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:34:07 </td>
   <td style="text-align:left;"> $CLOV i went on some side quests on $SPY and $TSLA but now im back to my back me true love $CLOV. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:34:07 </td>
   <td style="text-align:left;"> $SPY fuuutes rippin xD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:33:57 </td>
   <td style="text-align:left;"> $SPY Need capitulation for bottoms.....420 will test and a break will bottom us near 390-400. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:33:56 </td>
   <td style="text-align:left;"> $SPY 425 easy tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:33:49 </td>
   <td style="text-align:left;"> $SPY DIEEEE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:33:49 </td>
   <td style="text-align:left;"> $SPY Bulls want bears to forget about inflation and think about the war cause the war will blow over but inflation wont </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:33:36 </td>
   <td style="text-align:left;"> $SPY for the one time…futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:33:34 </td>
   <td style="text-align:left;"> $SPY bulls just don&amp;#39;t get it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:33:27 </td>
   <td style="text-align:left;"> $SPY Avg bull market reaches 115% and lasts 2-3 years, check.  The average bear market drops around 30% and takes about 9 months (if we don’t go into recession) that puts us around august. We are half way there folks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:33:15 </td>
   <td style="text-align:left;"> $SPY we have idiots, like truly stupid idiots in charge. That puppet in the oval office doesn&amp;#39;t know what day it his lack of knowledge is only overshadowed by Kamala&amp;#39;s dumb ass when she opens her noise hole. As if the crap with this inflation wasn&amp;#39;t bad enough, but now they tell us things are going to get bad...So let me get this straight. My tank of gas cost me $2 for premium 2 years ago. Now it&amp;#39;s 4.50 where I live. And you don&amp;#39;t see that as bad... Appearently it&amp;#39;s about to get bad. Smh. This is not your pure garden variety ineptitude. This is a new breed that hasn&amp;#39;t been named yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:33:11 </td>
   <td style="text-align:left;"> $SPY sure could use a keystone pipeline right now JS 😒 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:33:00 </td>
   <td style="text-align:left;"> $SPY demand zone moved to 425, you didn’t catch that did you and didn’t cover and bought more puts 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:33:00 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:32:53 </td>
   <td style="text-align:left;"> $SPY this war in the Ukraine is so important they decided to not cancel recess for the Senate because all work and no play makes us ineffective global leaders🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:32:41 </td>
   <td style="text-align:left;"> $SPY futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:32:28 </td>
   <td style="text-align:left;"> $SPY here for the futes rippin posts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:32:20 </td>
   <td style="text-align:left;"> $SPY booga booga, bears. Never bet against America. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:32:09 </td>
   <td style="text-align:left;"> $QQQ $SPY $ROKU $TSLA bears out here queefin bruh smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:31:44 </td>
   <td style="text-align:left;"> $SPY Weekly starting, below 50 descending to Fib at 4200. Bounce people are idiots, maybe at 4200, before NO.  Sure countertrend pullbacks, opportunity to short more.  Largest up days are in downtrends this is a historical market fact.  If 4200 breaks 3800 awaits and El Castigador makes bags more of money and money comes in many colors it is only green in the US. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:31:44 </td>
   <td style="text-align:left;"> $SPY Looks like I’ll be taking an L on $TQQQ long tomorrow. Thought PJ and PM traders didn’t know the sell button existed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:31:30 </td>
   <td style="text-align:left;"> REMEMBER:  ALL of this craziness and the fed is still buying assets and has rates at 0.  Have not even done the first rate hike Or stopped QE.  
 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:31:27 </td>
   <td style="text-align:left;"> $SPY make or break area </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:31:22 </td>
   <td style="text-align:left;"> $SPY But mommy I thought it was time to buy 

Sorry mommy I lost all your money 😢 

  🧞‍♂️ $QQQ $DIA $NDX $SPX  TRUE STORY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:31:10 </td>
   <td style="text-align:left;"> $SPY how are futures looking? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:31:08 </td>
   <td style="text-align:left;"> $SPY options expiring again tomorrow 😵‍💫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:31:01 </td>
   <td style="text-align:left;"> $QQQ $SPY papa pow, papa pow, the bulls fell down the well, come quick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:30:57 </td>
   <td style="text-align:left;"> $SPY watch it launch tomorrow 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:30:52 </td>
   <td style="text-align:left;"> $SPY Putin laughing his ass off right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:30:28 </td>
   <td style="text-align:left;"> $SPY let see if it hold here... at support line... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:30:14 </td>
   <td style="text-align:left;"> $SPY Ukrainian resorts got some great deals right now, just saying... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:30:06 </td>
   <td style="text-align:left;"> $SPY slaughtered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:30:04 </td>
   <td style="text-align:left;"> $SPY my weekly calls purchased to hedge my April puts 
👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:29:59 </td>
   <td style="text-align:left;"> $SPY Russia? 

Ok Cool 👍

Deep green by open Can’t wait to test 440 Wall cash session </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:29:48 </td>
   <td style="text-align:left;"> $qqq bottomed at the exact level of January 24th low.  ;)  
 
charts are more important than everything  
 
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:29:26 </td>
   <td style="text-align:left;"> $SPY i am over this dip, going long tomorrow yolo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:29:23 </td>
   <td style="text-align:left;"> $SPY Mommy I think we should buy it now 🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:29:12 </td>
   <td style="text-align:left;"> $SPY transitory fuckery </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:28:52 </td>
   <td style="text-align:left;"> $SPY I have a feeling biden knocked 2 rate hikes at least with today&amp;#39;s speech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:28:32 </td>
   <td style="text-align:left;"> $SPY  But Mommy is was up $17.50 after hours

🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣 🧞‍♂️🐝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:28:30 </td>
   <td style="text-align:left;"> $SPY 

&amp;#39;China&amp;#39;s going to be next&amp;#39;: #Trump says Putin&amp;#39;s #assault on #Ukraine #will embolden Xi to

Taiwan 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:28:18 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $DWAC $TSLA $SPY about that peace in the Middle East as well.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:27:37 </td>
   <td style="text-align:left;"> $SPY  Mommy make it go up mommy 🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:27:23 </td>
   <td style="text-align:left;"> $SPY guys stay positive. You can&amp;#39;t inflation with sanctions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:27:22 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ  https://finance.yahoo.com/news/legendary-investor-jeremy-grantham-sees-121600816.html?guccounter=1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:27:21 </td>
   <td style="text-align:left;"> $SPY very angry fake news bears trying to time dips… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:27:17 </td>
   <td style="text-align:left;"> $SPY sonic got banned again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:27:02 </td>
   <td style="text-align:left;"> $SPY Asian market ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:26:52 </td>
   <td style="text-align:left;"> $SPY  $3800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:26:37 </td>
   <td style="text-align:left;"> $SPY  x. But mommy I got crushed 

Like the  cockroach I am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:26:33 </td>
   <td style="text-align:left;"> $SPY y&amp;#39;all care about Ukraine only because they got them mail to order, hungry looking, broomstick women y&amp;#39;all call &amp;quot;hot&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:26:33 </td>
   <td style="text-align:left;"> $SPY moving as fast as a snail.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:26:31 </td>
   <td style="text-align:left;"> $SPY $QQQ Birth of the Antichrist priced in. We rise tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:26:13 </td>
   <td style="text-align:left;"> $SPY 

Dumpy dump at open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:26:13 </td>
   <td style="text-align:left;"> $SPY Guys, the rumor on this board is that shorts haven&amp;#39;t covered a single share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:26:03 </td>
   <td style="text-align:left;"> $AAPL $SPY All china stocks look to be pump and dumps. I&amp;#39;m guessing every time a stock IPOs they all buy calls and then cash out at the top after the quick run, because then you can spend the rest of the time printing naked shorted shares and get rich with ease </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:26:03 </td>
   <td style="text-align:left;"> $SPY Futs slow as molasses in winter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:25:53 </td>
   <td style="text-align:left;"> $SPY no one is attacking anyone, the only thing under attack is permabear feelings lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:25:51 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:25:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $DOW Wake up idiots, Russia just a distraction from the real menace: historic inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:25:15 </td>
   <td style="text-align:left;"> $HBAR $SPY $AMC    All that you need to know;. Shorts haven&amp;#39;t covered a single share:~~~~~~~~~ Check it out below 👇  
highly recommend everyone to follow them. 🚀     mostwinningchat.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:25:14 </td>
   <td style="text-align:left;"> $SPY $DWAC Jesus Lord help us 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:25:11 </td>
   <td style="text-align:left;"> The SPX is $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:25:10 </td>
   <td style="text-align:left;"> $SPY Like Tom Petty Said “Free Falling”

 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:25:00 </td>
   <td style="text-align:left;"> $SPY Putins not attacking the US, nATO response was simply this 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:24:16 </td>
   <td style="text-align:left;"> $SPY and just like that the Russia Ukraine headlines dwindle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:24:15 </td>
   <td style="text-align:left;"> $SPY oh yea </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:24:11 </td>
   <td style="text-align:left;"> $SPY Sanctions on russia will be majorly seen on Asian countries which are mostly dependent on gas as their prices are going to be high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:23:44 </td>
   <td style="text-align:left;"> $SPY Free Fallin   🧞‍♂️🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:23:42 </td>
   <td style="text-align:left;"> $SPY $440 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:23:14 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:23:09 </td>
   <td style="text-align:left;"> $SPY 
$vix might just freefall
Bulls: what do you think bears will say when this happens? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:23:07 </td>
   <td style="text-align:left;"> $SPY Biden is really taunting Russia to invade Ukraine. Would not be surprised to see a false flag in America in order to send US troops to fight Russia $GUSH $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:23:07 </td>
   <td style="text-align:left;"> $SPY Very Unstable      Watch out new bees 🐝     $DIA $QQQ  🐝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:23:05 </td>
   <td style="text-align:left;"> $SPY go to 420 cmon i need to put gas im my car in cali lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:22:55 </td>
   <td style="text-align:left;"> $SPY If the bulls think that the bears are done them, they are in for a rude awakening. They are just getting started. No one wants to pay more for their bag of groceries. Inflation is not going away anytime soon. Trade wisely. 🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:22:39 </td>
   <td style="text-align:left;"> $SPY who? You? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:22:37 </td>
   <td style="text-align:left;"> $SPY anyone know how severed the sanctions on Russia are at the moment or is it only on the two new new independent states </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:22:32 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $DWAC $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:22:11 </td>
   <td style="text-align:left;"> $SPY They just pumping futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:21:50 </td>
   <td style="text-align:left;"> $SPY bulls tomorrow b like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:21:41 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN AIRCRAFT CARRIER AT SOME POINT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:21:30 </td>
   <td style="text-align:left;"> $SPY nothing really matters 🌷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:21:12 </td>
   <td style="text-align:left;"> $SPY cash money! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:21:09 </td>
   <td style="text-align:left;"> Head and shoulders on $SPY &amp;amp; $DJIA descending triangle on $QQQ  &amp;amp; inverse head and shoulders on $SQQQ with a pennant on $UVXY charts say a crash is coming…are they right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:20:12 </td>
   <td style="text-align:left;"> S&amp;amp;P down $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:19:58 </td>
   <td style="text-align:left;"> $SPY Bulls ? Tomorrow night at this time I’ll be booking a nice vacation after tomorrows monster rally gains.  
 
Where is a nice place to go on a vacation ? Any ideas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:19:58 </td>
   <td style="text-align:left;"> $SPY congrats on all you have done this year..and its only February!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:19:53 </td>
   <td style="text-align:left;"> $SPY I speak for all Americans when I say we are ready to die to save Ukraine from the ineptitude of their sitcom star president with no political experience. Crash the economy? Of course. Draft? Hell yeah! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:19:41 </td>
   <td style="text-align:left;"> Every day I pick 2-5 stocks - the most undervalued stocks in AMEX, NYSE &amp;amp; NASDAQ to trade for the next trading day. Market participants are not perfectly rational in their judgments resulting in pricing irregularities and even predictable patterns in stock returns which could persist for short periods of time. I have developed mathematical and statistical techniques to exploit the temporary market inefficiencies for financial gains that beat the market. I am targeting a trading goal of 50% return by Dec 31 2022. In 2020 I gained 121%. In 2021 I gained 15%.Below is profit &amp;amp; loss from Friday&amp;#39;s picks. Keep these stocks on your watchlist for the next 1-5 days. Some of them may see huge gains in the next 1-5 days.        
$BKI $API $SPY $FAF $AMPL  
   
Details: https://www.youtube.com/watch?v=drA6Ywzm-sg 
NOTE: Below is P&amp;amp;L for one day only. This is my journey to achieve a cumulative 50% profit by Dec 21 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:19:19 </td>
   <td style="text-align:left;"> $SPY short squeeze mofos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:18:13 </td>
   <td style="text-align:left;"> $QQQ vix steady uptrend since beginning of February $UVXY $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:18:12 </td>
   <td style="text-align:left;"> $SPY when did this jump after hours? I&amp;#39;m still assuming we drop in the morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:18:02 </td>
   <td style="text-align:left;"> $SPY here we go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:17:59 </td>
   <td style="text-align:left;"> $SPY ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:17:39 </td>
   <td style="text-align:left;"> $SPY this will go over every bears head - 
You are not a player in this game. You are a helping hand 

Powell Pop I cannot wait to see the look on bears faces when they choke opex </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:17:37 </td>
   <td style="text-align:left;"> $ARKK $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:17:11 </td>
   <td style="text-align:left;"> $SPY just pulled up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:17:08 </td>
   <td style="text-align:left;"> $SPY any good answers as to why futures are up? Did I miss some good news while I was digging my bomb shelter 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:17:00 </td>
   <td style="text-align:left;"> $SPY lets just say I have only one long term left, and I am currently able to buy all my longs term back for 8-10% cheaper already. I saw it, and I acted quick... joe Biden does not deserve a market at ATHS, he deserves to be down as the worst president ever, and the market will show for it.  ill buy myself a boat load of long term plays in the coming months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:16:58 </td>
   <td style="text-align:left;"> $SPY just got word from a connect in Eastern Europe. It’s not clear when, but there is word of Russia build up of troops near Ukraine. Would watch carefully. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:16:52 </td>
   <td style="text-align:left;"> $AMC $GME $SNDL $SPY 

Ryan Cohen tweeted —&amp;gt; 🩳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:16:43 </td>
   <td style="text-align:left;"> $SPY  this market 👎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:16:40 </td>
   <td style="text-align:left;"> $SPY We need a Republican back in there! George W. Bush please come back! Best Market we ever had!!  -40%!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:16:27 </td>
   <td style="text-align:left;"> $SPY watch this and smile. It explains the stock market in 30 seconds 🍻

https://vm.tiktok.com/TTPdS26r8A/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:16:19 </td>
   <td style="text-align:left;"> $SPY Biden’s speech, pretty much said we are only here to defend. No war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:16:07 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:16:03 </td>
   <td style="text-align:left;"> WP $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:15:56 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
7.5% inflation 
 
and FED have everything under control...lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:15:37 </td>
   <td style="text-align:left;"> $SPY just want to let you all know I’m going. To Colorado for the week as my stonk vacation 
Btd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:15:34 </td>
   <td style="text-align:left;"> $SPY Bring a Republican back! We need George W. Bush’s market! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:15:16 </td>
   <td style="text-align:left;"> $SPY  question is where interest of us in to?

1) go to war against Russia with boots on the ground
2) go to war without boots on the ground 
3) take opportunity to put more sanctions and  push Russia  back in weapon race
4) shut the fuck up and keep nose out of this shit where we have no business 

for some reason option 4 is more attractive but what do i know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:15:10 </td>
   <td style="text-align:left;"> $SPY  $155 oil   🧞‍♂️😢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:14:59 </td>
   <td style="text-align:left;"> $SPY sell options dont buy them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:14:56 </td>
   <td style="text-align:left;"> $SPY going to 420.01 then load calls. Big run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:14:50 </td>
   <td style="text-align:left;"> $SPY $420 let’s go 👌🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:14:15 </td>
   <td style="text-align:left;"> $SPY: In no man&amp;#39;s land. Under 426, we most likely see 420 and then 417 level. If we can push back above 433, look for a retest of 436.5 resistance and then 440 level. Everything in between 426-433 is chop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:14:06 </td>
   <td style="text-align:left;"> $SPY i want lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:14:06 </td>
   <td style="text-align:left;"> $SPY $VIX Did Biden just send Millions of defense weapons to Ukraine only to leave it for Russia to take like he did in Afganistan? Can we be done with this POS Potus yet? Now he wants to inflate Gas prices and blame Russia for inflation. Its all a distraction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:14:01 </td>
   <td style="text-align:left;"> $SPY 

Nothing about the word - Violent, 
ever sounded bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:13:53 </td>
   <td style="text-align:left;"> $SPY How do I file a  lawsuit against the market ? Seems rigged. I have too much losses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:13:48 </td>
   <td style="text-align:left;"> $SPY Putin never did this under trump! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:13:35 </td>
   <td style="text-align:left;"> $SPY Comrade Tucker

&amp;quot;Treason against the United States, shall consist only in levying War against them, or in adhering to their Enemies, giving them Aid and Comfort.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:13:34 </td>
   <td style="text-align:left;"> $SPY  1% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:13:29 </td>
   <td style="text-align:left;"> $SPY jokes 

https://www.dailymail.co.uk/news/article-10540799/Emmanuel-Macrons-rivals-mock-summit-failure.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:13:10 </td>
   <td style="text-align:left;"> $SPY https://www.theonion.com/new-iphone-setting-reduces-eyestrain-with-black-text-on-1848564004 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:12:32 </td>
   <td style="text-align:left;"> $SPY hsi ripping faces, a precursor for the U.S.A baby! Shorts.run.for.cover </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:12:31 </td>
   <td style="text-align:left;"> $SPY imagine being assetless in an economy and inflation like this. These bears. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:12:13 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $DIA $DJIA  🧞‍♂️

2022 will be remembered by a bear market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:12:03 </td>
   <td style="text-align:left;"> $SPY we’re waiting Tom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:12:01 </td>
   <td style="text-align:left;"> $SPY my slvm puts today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:11:54 </td>
   <td style="text-align:left;"> $SPY Everyone selling is gonna wanna commit suicide a year from now .....just saying 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:11:54 </td>
   <td style="text-align:left;"> $SPY So many Bart Simpson haircuts on all these charts that bulls will be lucky if they can afford ramen for diner tomorrow  &amp;gt;=) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:11:52 </td>
   <td style="text-align:left;"> $SPY Hasbulla got drafted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:11:14 </td>
   <td style="text-align:left;"> $SPY I don&amp;#39;t think Putin cares about any sanctions.. He is rich and they have lot of oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:11:11 </td>
   <td style="text-align:left;"> $SPY well I guess it’s on now! Got his teeth cleaned! 😂🤣🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:11:06 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
7.5% inflation 
 
FED still increasing balance sheet 
FED still holding interest rates at 0% 
FED still printing Billions 
 
Not so good for poor folk and middle class. 
 
Rich people love it !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:10:53 </td>
   <td style="text-align:left;"> The SPX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:10:52 </td>
   <td style="text-align:left;"> $SPY $QQQ don’t stare at the 1 min chart all night bears. 🚀🚀🚀⛳️🏌🏾‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:10:43 </td>
   <td style="text-align:left;"> $SPY Ryan Cohen everybody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:10:42 </td>
   <td style="text-align:left;"> $SPY $TSLA is it a waka waka or what? 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:10:29 </td>
   <td style="text-align:left;"> $SPY Cramer said everything is ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:10:28 </td>
   <td style="text-align:left;"> $SPY next leg up ⬆️ 435-440 if it breaks above that ⬆️⬆️⬆️😁🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:10:19 </td>
   <td style="text-align:left;"> $SPY guys I&amp;#39;ve been pissed off since the all star weekend. How is kobe a baseline to crack top 10? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:10:10 </td>
   <td style="text-align:left;"> $SPY am I the only one here who’s still a teen? I feel like I keep arguing with Middle Aged men who are sexually frustrated (cough cough @PilotZee) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:09:55 </td>
   <td style="text-align:left;"> $SPY is like to hear from the Russian-Americans! What y’all think about this Ukraine invasion? There’s got to be a few Russians in the room? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:09:37 </td>
   <td style="text-align:left;"> $SPY soon bulls soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:09:34 </td>
   <td style="text-align:left;"> $SPY gonna keep dying, $SBSW going to $50 if rumor of Putin cutting metal exports true </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:09:27 </td>
   <td style="text-align:left;"> $SPY  http://www.b4signals.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:09:25 </td>
   <td style="text-align:left;"> $SPY   $3800 gap fill coming.  $SPX 🧞‍♂️ $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:09:22 </td>
   <td style="text-align:left;"> $SPY On the major green days you have to go with the most volatile stocks to make the most money. Tesla it is ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:09:11 </td>
   <td style="text-align:left;"> $SPY so Trump woukdve praised this and markets woukdve boomed 😂. Tells you how much Biden is making a big deal about this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:09:07 </td>
   <td style="text-align:left;"> $SPY Bulls got lucky today.  They still might have a chance to get out tomorrow before crash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:08:56 </td>
   <td style="text-align:left;"> $SPY Putan will make sure oil goes to $155 🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:08:46 </td>
   <td style="text-align:left;"> $SPY nothing to write home about but it’s looks better than it did   earlier today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:08:45 </td>
   <td style="text-align:left;"> $SPY printer go brrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:08:28 </td>
   <td style="text-align:left;"> $SPY do you guys think putin will do something to drive bitcoin down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:08:08 </td>
   <td style="text-align:left;"> $PLTR $ARKK $SPY $QQQ 

I’d love to know the reasoning of her selling out of $PLTR , I mean she was underwater right ? Was it people constantly bailing on her funds and she needs the $ , was it really that $TDOC is so low that she wants as much as she can get , is it because she doesn’t see $PLTR working out anymore ? I can’t see it being the latter with their growth and prospects , but it still doesn’t make sense why she wouldn’t sell something she’s in the $ on and not take a big loss . Weird all around </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:07:55 </td>
   <td style="text-align:left;"> $SPY what are some of the greatest opportunities out there which might really quickly and strongly if markets v-shape? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:07:41 </td>
   <td style="text-align:left;"> $SPY Putin meeting CEOs of mining companies..

Is Russia preparing sanctions on United States??? Cut exotic metal exports? Hmm.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:07:40 </td>
   <td style="text-align:left;"> $SPY Wall Street next!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:07:24 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMC $INDO &amp;quot;Shaking off the weak hands&amp;quot; is the most overused phrase on StockTwits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:07:04 </td>
   <td style="text-align:left;"> $SPY not sure how $6 a gallon gas is going to help anything. Glad I’m not in CA...........for like a billion more reasons </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:07:01 </td>
   <td style="text-align:left;"> $SPY I hope it stays up all night opens high I still hace 17k I wanted to load into puts 😫  don&amp;#39;t drop hard without me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:07:00 </td>
   <td style="text-align:left;"> $SPY If he wanted to hurt Putin and help Americans he’d let us pump our own oil.

Feels like they want high oil and gas prices to help push their new green deal. Gotta benefit those donors and special interests. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:06:49 </td>
   <td style="text-align:left;"> $SPY  Gap up in a bear market and see how fast it gets filled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:06:39 </td>
   <td style="text-align:left;"> $SPY bears trying so hard to make their opinions heard while bull just post a meme and go on with life </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:06:36 </td>
   <td style="text-align:left;"> $SPY futures want to rebound I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:06:36 </td>
   <td style="text-align:left;"> $SPY  another -$21.55 correction territory 

   🧞‍♂️👊🏻  $QQQ $DIA $NASDAQ $NDX  🪳

 Who wants to see in real time full blown 
                   ♠️  correction ♠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:06:21 </td>
   <td style="text-align:left;"> $SPY 420 support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:06:21 </td>
   <td style="text-align:left;"> $SPY we vibin today 🎉 

https://m.youtube.com/watch?v=pRpeEdMmmQ0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:06:20 </td>
   <td style="text-align:left;"> $SPY nothing like a joint to end the day off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:06:16 </td>
   <td style="text-align:left;"> $SPY putin has a gift for Biden tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:06:08 </td>
   <td style="text-align:left;"> $SPY there’s a violent bull run coming, don’t get left in the dust like 2020 💨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:06:07 </td>
   <td style="text-align:left;"> $SPY Shaking the weak hands </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:06:02 </td>
   <td style="text-align:left;"> $SPY we will retest lows of today tomorrow the question is do they hold or not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:05:59 </td>
   <td style="text-align:left;"> $SPY How long was Justice Ginsberg dead before they admitted it 🤷‍♂️ just say’n she gone ! 👑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-23 10:05:47 </td>
   <td style="text-align:left;"> $SPY 💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:50:50 </td>
   <td style="text-align:left;"> $SPY $QQQ the market doesn’t like this waiting around whats going to happen between russia and ukraine, i think the markets just want a resolution or even war, “sadly” for it to move on from this. what is going now, its uncertainty, thats why the market sucks. thats why i am not bullish now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:50:30 </td>
   <td style="text-align:left;"> $DWAC $TSLA $QQQ .. 
 
Account Challenge Update:-  
Start Date: Feb 2, 2022  
Starting Balance: $1,800  
Current Balance: $89,637  
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
   
Watch out for next play👓  https://www.discord.io/xEvE2Aatrp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:50:17 </td>
   <td style="text-align:left;"> $SPY Sanctions to include; 
- Vodka and orange juice will not be allowed to mix together in the same glass. 
- Nesting dolls will be permanently glued shut. 
- The proletariat will only be allowed to uprise once a month. 
$QQQ $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:47:27 </td>
   <td style="text-align:left;"> $QQQ what happened with the -5% bears talked about yesterday?😂😂😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:45:57 </td>
   <td style="text-align:left;"> $SPY Biden made it clear today in his speech - &amp;quot;Expect higher energy prices&amp;quot; 1) Biden dismantled XL pipeline 2) cancelled all licenses to drill on federal lands 3) begging OPEC and Russia to sell us more oil.  THEN he goes to blame Russia for the higher energy prices here.  Biden did this.  All of it.   $USO $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:44:38 </td>
   <td style="text-align:left;"> $SPY $QQQ Tom Lee interview today, did not mention anything about his face ripper rally for february… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:43:48 </td>
   <td style="text-align:left;"> New Analysis: It is time to sell before things get worse? Or is this a golden opportunity? https://cracked.market/2022/02/it-is-time-to-sell-before-things-get-worse-or-is-this-a-golden-opportunity/ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:41:04 </td>
   <td style="text-align:left;"> $QQQ anyone know of a broker that doesn&amp;#39;t intentionally mess up your options dates on 1099b for 2022? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:39:45 </td>
   <td style="text-align:left;"> $QQQ Fuck Biden. Why is my broker intentionally making errors with options dates on my 1099b. Something corrupt is going on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:39:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA all it take is a little push. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:39:04 </td>
   <td style="text-align:left;"> $OCGN $BTC.X $QQQ   All that you need to know;. Shorts haven&amp;#39;t covered a single share:~~~~~~~ Check it out below 👇  
highly recommend everyone to follow them. 🚀     mostwinningchat.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:38:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $BTC.X 

Thank the lord for Biden , his amazing vaccines, containing/eradicating the virus with his well executed plan (something trump couldn’t do), his push to get conservative CEOs to fix their supply chain issues and his strong arm stance to JPOW, curbing inflation. Not only this, but he also was able to stand up too and scare off Putin. 

What a blessing that Biden is in and Trump is out. 

Not to mention he has the best VP in the history of this nation at his side in Kamala Harris.

No more Republicans please. 
🙏🙌🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:32:09 </td>
   <td style="text-align:left;"> $QQQ $SPY $ROKU $TSLA bears out here queefin bruh smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:31:30 </td>
   <td style="text-align:left;"> REMEMBER:  ALL of this craziness and the fed is still buying assets and has rates at 0.  Have not even done the first rate hike Or stopped QE.  
 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:31:22 </td>
   <td style="text-align:left;"> $SPY But mommy I thought it was time to buy 

Sorry mommy I lost all your money 😢 

  🧞‍♂️ $QQQ $DIA $NDX $SPX  TRUE STORY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:31:04 </td>
   <td style="text-align:left;"> $QQQ $TQQQ NQ daily candle looking like this so far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:31:01 </td>
   <td style="text-align:left;"> $QQQ $SPY papa pow, papa pow, the bulls fell down the well, come quick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:29:48 </td>
   <td style="text-align:left;"> $QQQ 13;483 hits amd down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:29:48 </td>
   <td style="text-align:left;"> $qqq bottomed at the exact level of January 24th low.  ;)  
 
charts are more important than everything  
 
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:28:28 </td>
   <td style="text-align:left;"> $QQQ anyone else notice the market crashed at the same sharp rate &amp;amp; timing as omicron variant infections plummeted?  Is this all bullshit??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:27:22 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ  https://finance.yahoo.com/news/legendary-investor-jeremy-grantham-sees-121600816.html?guccounter=1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:26:31 </td>
   <td style="text-align:left;"> $SPY $QQQ Birth of the Antichrist priced in. We rise tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:26:17 </td>
   <td style="text-align:left;"> $QQQ Bears pwned permabulls this whole year. You think you have the balls to drag your testicles across every falling knife?! Do ya!?? Be smart out there yall I hope $DWAC tanks tomorrow I’m loaded with puts!! Let’s go Brandon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:25:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $DOW Wake up idiots, Russia just a distraction from the real menace: historic inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:25:03 </td>
   <td style="text-align:left;"> $QQQ same shit different time and reason ….. well done assholes .. speaking of assholes…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:23:07 </td>
   <td style="text-align:left;"> $SPY Very Unstable      Watch out new bees 🐝     $DIA $QQQ  🐝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:21:41 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN AIRCRAFT CARRIER AT SOME POINT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:21:09 </td>
   <td style="text-align:left;"> Head and shoulders on $SPY &amp;amp; $DJIA descending triangle on $QQQ  &amp;amp; inverse head and shoulders on $SQQQ with a pennant on $UVXY charts say a crash is coming…are they right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:18:13 </td>
   <td style="text-align:left;"> $QQQ vix steady uptrend since beginning of February $UVXY $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:16:03 </td>
   <td style="text-align:left;"> $QQQ lmao bears having been driving this down for 2 months.. u think u got some power bulls lmapopoooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:15:56 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
7.5% inflation 
 
and FED have everything under control...lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:12:36 </td>
   <td style="text-align:left;"> $DWAC $NVDA $QQQ Does anyone know any good Russia company stocks I can invest in ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:12:31 </td>
   <td style="text-align:left;"> $SPY imagine being assetless in an economy and inflation like this. These bears. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:12:13 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $DIA $DJIA  🧞‍♂️

2022 will be remembered by a bear market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:11:16 </td>
   <td style="text-align:left;"> $QQQ Bears on Stocktwits whether it’s looking good or bad for them….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:11:06 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
7.5% inflation 
 
FED still increasing balance sheet 
FED still holding interest rates at 0% 
FED still printing Billions 
 
Not so good for poor folk and middle class. 
 
Rich people love it !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:10:52 </td>
   <td style="text-align:left;"> $SPY $QQQ don’t stare at the 1 min chart all night bears. 🚀🚀🚀⛳️🏌🏾‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:10:04 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:08:08 </td>
   <td style="text-align:left;"> $PLTR $ARKK $SPY $QQQ 

I’d love to know the reasoning of her selling out of $PLTR , I mean she was underwater right ? Was it people constantly bailing on her funds and she needs the $ , was it really that $TDOC is so low that she wants as much as she can get , is it because she doesn’t see $PLTR working out anymore ? I can’t see it being the latter with their growth and prospects , but it still doesn’t make sense why she wouldn’t sell something she’s in the $ on and not take a big loss . Weird all around </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:06:55 </td>
   <td style="text-align:left;"> $QQQ LOL.
ANOTHER BANK CLOSURE - ATM BOARDED UP - MARKET SUPERBUBBLE WILL BURST -STOCK MARKET PLUNGES NEEDS QE
https://www.youtube.com/watch?v=dAQXLE7SjM8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:06:36 </td>
   <td style="text-align:left;"> $SPY  another -$21.55 correction territory 

   🧞‍♂️👊🏻  $QQQ $DIA $NASDAQ $NDX  🪳

 Who wants to see in real time full blown 
                   ♠️  correction ♠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:06:31 </td>
   <td style="text-align:left;"> $QQQ idk how anyone is bullish on this lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:04:39 </td>
   <td style="text-align:left;"> $QQQ short this POS on the any rip tomorrow. Bull trap incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:03:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $arkk $DJIA 

The world may not need natural gas or oil soon.  Nuclear fusion ( how the sun generates light and heat sustainably ) is becoming a real thing.

https://www.universal-sci.com/article/highest-ever-sustained-fusion-energy-output-by-jet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:03:23 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F $QQQ $DIA 🧞‍♂️🍿

FYI: S&amp;amp;P is -$21 away from full blown correction  haha ha ha haha 
We love crushing tiny teeny tiny cockroaches </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 10:00:34 </td>
   <td style="text-align:left;"> $BBIG $SPY $QQQ 
Futures saying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:59:35 </td>
   <td style="text-align:left;"> $SPY $QQQ fyi, just because you see some names that were pumped up with the feds help and now they are down 50% or more from their highs still doesnt mean they are oversold. these companies valuations are still insane with this haircut they got…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:59:34 </td>
   <td style="text-align:left;"> $QQQ daily, weekly, monthly.. it doesn&amp;#39;t matter at this point. All of my bearish indicators are hitting, it&amp;#39;s crazy that the moment of clarity is here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:59:34 </td>
   <td style="text-align:left;"> $SPY $QQQ 

My daddy will save us all once again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:57:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $TDOC Another extremely oversold name.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:56:36 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DJIA  
We might have a green day tomorrow 
 
Im hopeful 
 
Weekly update: 
Is it a buying opportunity for Rblx &amp;amp; NVDA?  
https://youtu.be/JStETvXu0vM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:55:21 </td>
   <td style="text-align:left;"> $QQQ Keep calm and stack 💵💵💵
https://youtu.be/5ue7aSPUfZ4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:54:19 </td>
   <td style="text-align:left;"> $QQQ $SPY tonight it’s the bears who are most likely gonna get faked out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:53:36 </td>
   <td style="text-align:left;"> $SPY $QQQ  pretty much sums up all traders here if you swap the word porn with trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:53:19 </td>
   <td style="text-align:left;"> $SPY For all the little cockroaches 🪳 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:52:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $SQQQ Problem with traders now is they’re so shortsighted after a 10% drop a 2 % correction happens and they think the market can only go up from there. The trend is your friend not the 1 minute chart. 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:50:58 </td>
   <td style="text-align:left;"> $SPY could retrace to 400/380 

$AMD $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:50:17 </td>
   <td style="text-align:left;"> $SPY $QQQ 
I might as well start flipping coins to trade. Forget the news. Everything is ran on Hopium. 🌬🌬🌬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:48:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA max leverage long on futures for the print of your life by the morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:48:16 </td>
   <td style="text-align:left;"> $SPY $QQQ Dump this sucker once and for all. It needs to retest highs of right before pandemic hit. Then we move higher 🔻🔻🔻🚽🚽🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:47:51 </td>
   <td style="text-align:left;"> $SPY If you can’t technically trade you suck 👊🏻🧞‍♂️

    $qqq $dia $nasdaq $djia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:43:44 </td>
   <td style="text-align:left;"> $SPY $QQQ let’s go apes. Puts about to print hardddd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:43:23 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Biden voters!! Accomplishments?? Let&amp;#39;s hear them!! I know you&amp;#39;ve got a few!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:42:49 </td>
   <td style="text-align:left;"> $QQQ $SPY $TQQQ miss the days when Futes would rip bigly and gap up 4/5 days a week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:42:36 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Another &amp;quot;turn around Tuesday&amp;quot; in the books. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:41:19 </td>
   <td style="text-align:left;"> $QQQ let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:40:26 </td>
   <td style="text-align:left;"> $SPY $QQQ This man must be stopped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:39:39 </td>
   <td style="text-align:left;"> $SPY Don’t get excited for $qqq and spy. MM will screw everyone with their premium collection. 😹 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:37:02 </td>
   <td style="text-align:left;"> $SPY $qqq bulls about to get super confused when it now tanks for “no reason.” Russia is over they will say. And rate hikes are priced they will tell everyone. 

But they don’t know it takes 3 months to price in liquidity shifts. We are halfway </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:37:02 </td>
   <td style="text-align:left;"> $QQQ $SPY $DOW    Too easy now! There is just no way these markets are going to get any upward momentum back! 

Puts the easy play and you WILL make huge money!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:35:21 </td>
   <td style="text-align:left;"> $QQQ If you guys didn’t see this coming a mile away when SLEEPY JOE was elected…your head needs examined! This markets in SERIOUS TROUBLE, This  Country is being destroyed 1 day at a time &amp;amp; THE MARKETS KNOW THIS!  

BIDEN IS DESTROYING EVERYTHING YOU DREAMED OF! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:34:41 </td>
   <td style="text-align:left;"> $SPY $QQQ everyone attacking trump for being weak on russia.. ya none of this bullshit happened 2016-2020 last time I checked. last time russia did something like this? oh ya 2014 under obama and biden. everyone acting like biden is so tough and standing up to putin, ya how bout those weak ass sanctions he came out with today. russia laughing. ill ask again, what is there to be bullish about NOW? 2016-2020 the world was peaceful. isis was gone. north korea stopped firing missiles. syria was in check. russia wasn’t at ukraines footstep. chinas economy was worse than ours. backed off from taiwan. illegal crossings were down at our southern border. countries didnt like what trump had to say, whoopty doo, grow a pair. now we are the laughing stock of the world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:34:24 </td>
   <td style="text-align:left;"> $QQQ not even close to trend yet.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:34:04 </td>
   <td style="text-align:left;"> $QQQ dayum whats goin on here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:32:13 </td>
   <td style="text-align:left;"> $QQQ NOOOO PLZ DONT DUMP YET I WANTED MORE PUTS AT 343 :’( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:31:07 </td>
   <td style="text-align:left;"> $SPY $QQQ who wins financially through EVERY conflict, during and post? 

AMERICA motherf***ers 🇺🇸 🚀🇺🇸🚀🇺🇸🚀

Bring on the “post war” rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:28:38 </td>
   <td style="text-align:left;"> $SPY $QQQ so if russia is only claiming the east regions in ukraine then why do they have troops surrounding the whole country? why arent they just in the eastern part only…? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:27:10 </td>
   <td style="text-align:left;"> $QQQ $spy  
 
big gap n go day tmrw war rally starts soon  
 
on a side note anyone find it funny how Russia always tries shit with the fed is about to raise rates? They don’t want us to crash their commodities market with a strong dollar swap lol  
 
losers gonna take the L </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:26:42 </td>
   <td style="text-align:left;"> $QQQ $SPY $VIX well it was a good run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:26:17 </td>
   <td style="text-align:left;"> $QQQ $SPY as someone who wants to be bullish I wouldn’t mind this opening red to gap fill then bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:25:14 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPX $SPY 

I feel comfortable with Biden.

Trump has shown he is very stupid and has the attention span and temper of a 2 year old.

The Russia situation would have been too much for the child to handle. 

Thank god Biden is in, and Trump is out 🇺🇸🙌👌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:23:25 </td>
   <td style="text-align:left;"> No matter what the market is doing you can make money on any given day. That&amp;#39;s the beauty of day trading and staying liquid. Plenty of opportunities. If not, you can just sit on your hands and observe while studying up and building a watchlist for the next day. It&amp;#39;s all about risk management, discipline, consistency, growing your account, having a plan and sticking to it. Let&amp;#39;s go! $INDO $IMPP $OCGN $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:23:07 </td>
   <td style="text-align:left;"> $QQQ Sell the rumor, buy the news = 2022.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:22:26 </td>
   <td style="text-align:left;"> $SPY $QQQ The bears definitely not having too much fun this evening by seeing how green the futures are </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:18:48 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:17:54 </td>
   <td style="text-align:left;"> $AAPL If NASDAQ 🐻Decline Continues then maybe a full year back to 3/2021 Lows
We shall see…. 
$AMD $QQQ $MSFT $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:17:47 </td>
   <td style="text-align:left;"> $SPY  $QQQ  Futures are green overnight 🎰  
 
FOMC March 16..   
  🎢  🤷🏻 
 
$tsla $sofi $upst </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:17:12 </td>
   <td style="text-align:left;"> $SPY $QQQ Gotta love the volatility.. hopefully you guys trimming profit up and down. Hope we see another big day tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:17:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 75003700. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:16:43 </td>
   <td style="text-align:left;"> $QQQ Letsssss go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:15:23 </td>
   <td style="text-align:left;"> $QQQ media just straight up forgot about the ukraine war lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:15:18 </td>
   <td style="text-align:left;"> $SPY $QQQ  you guys know why Biden didn&amp;#39;t slap big dick sanctions on Russia right? He can&amp;#39;t because of INFLATION. Imagine how much more out of control inflation would be if Russian oil/nat gas and semiconductors parts had sanctions.  Extremely bearish move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:13:27 </td>
   <td style="text-align:left;"> $QQQ $SPY $DOW 

Just keep loading weekly puts and cashing profits! RINSE &amp;amp; REPEAT! Hold a few for longer gains but THE DAILY AND WEEKLY PUT SINGLES will continue to add up FAST!

EASY MONEY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:09:43 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY $SPX 

Thank the lord for Biden , his amazing vaccines, containing/eradicating the virus with his well executed plan (something trump couldn’t do), his push to get conservative CEOs to fix their supply chain issues and his strong arm stance to JPOW, curbing inflation. Not only this, but he also was able to stand up too and scare off Putin. 

What a blessing that Biden is in and Trump is out. 

Not to mention he has the best VP in the history of this nation at his side in Kamala Harris.

No more Republicans please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:08:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Cup and Handle on Monthly Futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:07:52 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:07:23 </td>
   <td style="text-align:left;"> $UVXY $QQQ $MMAT $SAVA $TSLA My experience here has shown me that just like power or the corrupt and self centered financial system/racket which is a parasite on the economy, the stock market is not a CONTRIBUTOR to the useful economy but rather a PARASITE that feeds off of it and the world would be a better place without it. After all what are equities or options? Just shares of ownership in a company in exchange for $$$ to support its growth/expansion/survival. Or derivatives of it. Or derivatives of whatever the fuck it is of derivatives to the power n of something no one has idea about sometimes too... basically a fucking CASINO.
The same job is done by bank loans or VC capital and those sharks are very adept at pricing the potential of a company. This is why they won&amp;#39;t lend to your cousin George that is a deadbeat, but George can &amp;quot;invent&amp;quot; a company, do a &amp;quot;reverse-merger&amp;quot; listing like a spac and get millions... And still be a deadbeat that will spend all of it on hookers and coke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:06:08 </td>
   <td style="text-align:left;"> Live Trade Alert - $QQQ -  #Nasdaq 100 ETF  -  Double Bottom?? Now what? Check the video!
https://youtube.com/shorts/K5rSdW3omdU?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:04:25 </td>
   <td style="text-align:left;"> $QQQ some people here promote Biden repeatedly.  I want to say I will vote for trump if trump decide to be presidential candidate.  I want to see how these people become desperate did trump win.  Who cares this country anyway..  to be honest , surgery coating Biden only hurt Biden and this nation, helping trump… do you understand???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:03:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $SPX 

Republicans are truly not the brightest , they crash all the markets and then blame the democrats. 

Turn off faux news and do your own research guys. It’s called reality - not everything is a conspiracy theory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:01:17 </td>
   <td style="text-align:left;"> $QQQ $NVDA $AMD tomorrow should be a hell of a day. Keep pushing mfers!! I&amp;#39;m proud of you all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 09:00:31 </td>
   <td style="text-align:left;"> $SPY Market don’t go down forever neither you forever, that’s when you know market is unpredictable. Trade facts not fears $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:59:58 </td>
   <td style="text-align:left;"> $SPY $GOOGL $TSLA $QQQ $AMZN For all of you Traitor Trump fans, he would be the ultimate Putin doormat. (He is after all Putin&amp;#39;s c*ckholser.)  Remember this &amp;quot;meeting&amp;quot; with the Russians in the Oval Office no less after Russia interfered in the 2016 election to secure his &amp;quot;win.&amp;quot; Yeah. they must be laughing at how they pulled the wool over the eyes of America: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:59:31 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $TLT $GLD  
 
Stop insulting JDADDY with all this talk of &amp;quot;war&amp;quot;...he don&amp;#39;t appreciate it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:57:33 </td>
   <td style="text-align:left;"> I was bullish during the last correction in October .. and got out at my price target.
Unfortunately I don’t feel the same ♦️ about this current $spy $qqq correction but I maybe wrong but hopefully not. I’m waiting for a deeper pullback 

$IWM $DIA $XLK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:56:44 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:56:38 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $TLT $GLD  
 
So the FED has said it will go from printing $120 BILLION/mo in 2020/21 to printing $0 Billion by the middle of next month. 
 
hmmm...rising balance sheet says no. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:56:18 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $IWM Lol all these bears sweating now. Why would you chase a short down after it&amp;#39;s been beaten like a dead horse? Greedy greedy greedy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:55:53 </td>
   <td style="text-align:left;"> Dark pool after hours activity in 
 
$QQQ - $130M print 
$HYG - $200M print 
$TSLA - $166M print 
$TLT - $211M print 
$WDAY - $141M print 
 
#darkpool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:54:36 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA  
 
First close below 340 for QQQ since January low. Today&amp;#39;s bounce off the 334 level was expected but it will be short lived as we break through 334 and head to 320s in the coming days. RSI is not yet oversold and MACD has crossed firmly to the negative side.  
 
Easy on the BTD mode as you may end up bagholding very quickly :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:51:52 </td>
   <td style="text-align:left;"> $QQQ $SPY  mean they can gap it up sure i have no position but I’d much rather see them flush the bowl and lock it limit down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:51:14 </td>
   <td style="text-align:left;"> $AAPL $TSLA $BTC.X  $QQQ Risk management? …..Pshhh, if you aren’t taking out loans for options plays or betting your life savings like a degenerate gambler the. You are just a puss boy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:51:09 </td>
   <td style="text-align:left;"> $QQQ $SPY $SPX $BTC.X 

It’s rare we see a President do so many things right this early on in his term.

Biden, you magnificent beast.

Keep up the outstanding work, our economy is roaring. 

Takes notes - Conservatives 🇺🇸✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:50:43 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA  $10/ gallon soon

https://www.marketwatch.com/story/russia-ukraine-puts-10-u-s-inflation-on-radar-as-blackrock-repeats-central-banks-may-have-to-live-with-inflation-11645565763?siteid=yhoof2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:49:06 </td>
   <td style="text-align:left;"> $QQQ green days make the red days feel so lil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:48:14 </td>
   <td style="text-align:left;"> $QQQ $SPY $SPX $BTC.X 

Donald Trump could quite possibly be considered one of the WORST leaders in the history of the world. Let that sink in.

Thank the lord Biden is in, and Trump is out. Biden eradicated the virus with his beautiful executed plan, and now prevented a world war by scaring off Putin. Putin wanted no part of Joe’s Wraith so he decided to ride with Biden rather , instead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:47:57 </td>
   <td style="text-align:left;"> $QQQ doesn’t look like pump and dump crap to me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:47:38 </td>
   <td style="text-align:left;"> $amd  $nvda  $spy   $qqq  $TSla  
Advanced Micro Devices upgraded to outperform with a $150 price target at Bernstein 
A Wall Street analyst upgraded Advanced Micro Devices to a buy rating after 10 years on Tuesday, highlighting its growing market share, a strong portfolio of computer chips to rival that of Intel and a relatively cheap stock price. 
 
&amp;quot;This is not the AMD of a decade ago,&amp;quot; Bernstein Research analyst Stacy Rasgon said, lifting the brokerage&amp;#39;s rating on the company to &amp;quot;outperform&amp;quot; — its highest stock rating — from &amp;quot;market-perform&amp;quot;. 
 
https://seekingalpha.com/news/3802395-advanced-micro-devices-upgraded-at-bernstein-firm-sees-30-upside?mailingid=26788713&amp;amp;messageid=2900&amp;amp;serial=26788713.25205&amp;amp;utm_campaign=rta-stock-news&amp;amp;utm_content=link-1&amp;amp;utm_medium=email&amp;amp;utm_source=seeking_alpha&amp;amp;utm_term=26788713.25205 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:47:25 </td>
   <td style="text-align:left;"> $QQQ $SPY $BTC.X $SPX 

I feel comfortable with Biden.

Trump has shown he is very stupid and has the attention span and temper of a 2 year old.

The Russia situation would have been too much for the child to handle. 

Thank god Biden is in, and Trump is out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:46:21 </td>
   <td style="text-align:left;"> $QQQ bought calls at bottom only to have them go up and down. But the AH looks good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:43:46 </td>
   <td style="text-align:left;"> Even the cat is pissed about all the BS this guy throws on CNBC. 
Photo credit StockCats
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:40:52 </td>
   <td style="text-align:left;"> $QQQ $SPY  by April all the bears will be in hibernation cause we will be at ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:40:04 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $NDX … @MarkNewtonCMT great interview 👇🏻

https://twitter.com/yahoofinance/status/1494755380819279878?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:38:42 </td>
   <td style="text-align:left;"> $PANW Don&amp;#39;t be surprised to see a CYBER ATTACK. You can blame SLEEPY JOE 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:37:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $SPX $IWM  
 
bear&amp;#39;s ass be widening 
 
you always go long ATM at peak IV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:35:58 </td>
   <td style="text-align:left;"> $QQQ $SPY where my TA people at that know everything? Can’t seem to figure out what the market is wanting to do short term (hourly-4 hour chart) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:33:39 </td>
   <td style="text-align:left;"> $RBLX ==&amp;gt; SO GLAD I BOUGHT THE DIP ALL THE WAY... THAT WAS BOTTOM LADIES &amp;amp; GENTS.... BACK TO  $100 in a couple of weeks 🔥🚀🚀🚀 
. 
$QQQ  $SPY  $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:32:50 </td>
   <td style="text-align:left;"> $QQQ Russia invading Ukraine is a big news but China continues to invade neighboring countries and USA continues to stay silent. Double standards? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:31:59 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $SQQQ ;; Bullish after hours activity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:30:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA only 30% of all stocks are trading above the 200😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:28:38 </td>
   <td style="text-align:left;"> $QQQ Sucking out profit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:26:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA My unique perceptive of the market. https://youtu.be/6c25maDNS8c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:25:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM can someone please explain to me what goes through a bear&amp;#39;s head when they buy puts at the bottom? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:24:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $SMH $IWM fkk I&amp;#39;m feeling fomo already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:24:41 </td>
   <td style="text-align:left;"> Bulltards who YOLO&amp;#39;ed their entire account on $OCGN once max pain threshold is achieved in a few weeks.  $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:24:31 </td>
   <td style="text-align:left;"> $QQQ Don’t short America, I’m expecting an honest to god 345 tm at noon, I’m not selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:23:31 </td>
   <td style="text-align:left;"> $QQQ  Things will continue to go lower due to Economic factors.  If all you DIP buyers are jumping back in now. Good Luck! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:22:16 </td>
   <td style="text-align:left;"> $QQQ Ty for cheap stock prices put gamblers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:21:58 </td>
   <td style="text-align:left;"> $SPY $QQQ the market is drunk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:21:03 </td>
   <td style="text-align:left;"> $QQQ tomorrow will be a dead cat........ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:20:52 </td>
   <td style="text-align:left;"> $QQQ left left left right left </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:20:29 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F   🍒🍿🍒. $qqq $ndx 

I’m Sorry, technical traders talking around the street imminent $4000 is coming 

Just saying it’s truth 🧞‍♂️🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:19:13 </td>
   <td style="text-align:left;"> $SPY  weekend bears has been disappeared $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:18:39 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
Hey MEDIA SHEEPS!...you still consuming mainstream media and using their &amp;quot;war&amp;quot; narrative to explain markets moves? 
 
Stop!...DON&amp;#39;T DO THAT!!! 
 
Only worry about the FED and free money liquidity it provides to the financial markets. Make sure you can answer and explain the following AT MINIMUM. Then you just might have a chance to truly understand and be in sync with what REALLY moves the markets. 
 
Do you know when the FED is scheduled to end QE? 
Do you know the amount of liquidity they are removing from the market each month? 
Do you know when the first rate hike will be? 
Do you know how much the first rate hike will be? 
Do you know how many other rate hikes are priced into the market? 
Do you know how the FED will reduce it&amp;#39;s 9 TRILLION dollar balance sheet this year? 
ETC, ETC, ETC 
 
Don&amp;#39;t be a MEDIA SHEEP!...be a FED SHEEP!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:17:30 </td>
   <td style="text-align:left;"> $QQQ Maybe reclaim 340 tmr then go for 344. If not, it might back test 336-338 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:16:36 </td>
   <td style="text-align:left;"> $QQQ we are close to a bottom. Heres why. 

at the bottom in March 2020 it was like every segment on TV and everywhere you look its bad news. Almost like a little kid having a hissy fit. It sort of feels that way now. 

Inflation and crypto and war and rates and slowing growth and mid term elections and yield curves. 

Oh and this just in there is no effin way the fed raises rates 7 times in 9 months. I cant even believe reputable companies are spewing this crap.  

“Hey inflation is looking good after 87 rate hikes”

“Everyone is broke so prices have come way down” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:16:14 </td>
   <td style="text-align:left;"> Will dump a bunch of charts later. Reply to this with the ones you want if you like  
 
$QQQ $AAPL $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:15:32 </td>
   <td style="text-align:left;"> $QQQ Bears on here still talking shit as if they didn’t make a shit ton on puts and going short in the last week or so. It can’t drop 6 or 7 dollars every single day. Be humble, you should be in great shape from the gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:15:25 </td>
   <td style="text-align:left;"> $QQQ  bears are mad that they missed the bottom today and decided to hold. Now they are on here typing to make themselves feel better 👏🏻👏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:15:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM bears are absolutely fooked come tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:14:57 </td>
   <td style="text-align:left;"> $SPY $QQQ bears that arent hedged in futures are going to learn that they weren’t actually ready for the bear market this week. It’s okay. 2 more weeks before the real knife. Made a nice neckline on the daily though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:14:49 </td>
   <td style="text-align:left;"> $SPY $QQQ A reprieve from Jan low as Pres. Biden announces sanctions against Russia.  Sanctions were not so harsh so as to leave Putin with nothing to lose if he should act more aggressively.  This is a balanced approach.  Federal Reserve unlikely to hike 50 bp in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:09:10 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ there is a weird color on the futures.. it&amp;#39;s something I don&amp;#39;t recognize.. green? Da fuq? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:07:22 </td>
   <td style="text-align:left;"> $QQQ death cross? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:06:34 </td>
   <td style="text-align:left;"> $UVXY inverse head and shoulders and in a pennant breakout price is $35 bank on it 🧐 $SPY $QQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:04:38 </td>
   <td style="text-align:left;"> $QQQ Get your shorts now, just like the big boys. The only reason it’s up after hours is they pushed it higher on low volume to lock in the best price possible before we drop tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:03:17 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ if you guys aren&amp;#39;t buying dips. You are actually crazy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:02:50 </td>
   <td style="text-align:left;"> $ARKK $DJIA $QQQ The US just wants to get its hands on everything, even the shit on the moon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:02:40 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $DJIA  🧞‍♂️ Alert 🚨 

CNBC: Russia is invading Ukraine right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:02:10 </td>
   <td style="text-align:left;"> $QQQ Biden said: this is the beginning of Russia invasion …. Appears a long way to go… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 08:02:09 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-02-22 Trade Analysis Video: 
https://www.youtube.com/watch?v=MpErUr25ysM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:58:53 </td>
   <td style="text-align:left;"> Daily nasdaq $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/EVxE0pUt8qw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:58:41 </td>
   <td style="text-align:left;"> $QQQ I like it I like it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:57:48 </td>
   <td style="text-align:left;"> Pentagon expected to OK National Guard for DC truck convoys $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/pentagon-expected-to-ok-national-guard-for-dc-truck-convoys/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:57:43 </td>
   <td style="text-align:left;"> $AMZN $Tsla $qqq $spy World War 3 rally has begun!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:56:53 </td>
   <td style="text-align:left;"> $QQQ $SPY the power of desperation is incredible!

isn&amp;#39;t it crazy how much stamina these guys have calling the bottom literally every fucking day?

if we&amp;#39;re down it&amp;#39;s the bottom, if we&amp;#39;re up it&amp;#39;s a huge rally, futures down it&amp;#39;s a fluke, futures up it&amp;#39;s v shaped recovery.

yep I&amp;#39;m sure everything is oversold, strong Joe is gonna whip putin, and most importantly the FED is gonna print us out of this situation.

ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:56:52 </td>
   <td style="text-align:left;"> $QQQ Just dropped my pants in her again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:56:35 </td>
   <td style="text-align:left;"> $QQQ bears were so dramatic yet again… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:55:14 </td>
   <td style="text-align:left;"> $QQQ $SPY for fucksake can we not gap on a decent move for once </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:53:47 </td>
   <td style="text-align:left;"> $QQQ putin moving troops or something, he insider buys bitcoin before he does it and bitcoin was up 1500 bucks today -- dont overthink this AH move as u r crazy not to believe it -- market aint dumb and we are 3 hours into the move... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:52:45 </td>
   <td style="text-align:left;"> What a blessing to be able to trade $ROKU ⛳️🏌🏾‍♂️🐳🚨 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:52:34 </td>
   <td style="text-align:left;"> Stocks Drop On February 22 As Fed Jitters Rattle Investors https://mottcapitalmanagement.com/stocks-on-february-22-as-fed-jitters-rattle-investors/ $TSLA, $AMZN, $TWLO $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:52:20 </td>
   <td style="text-align:left;"> $QQQ 343 resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:52:05 </td>
   <td style="text-align:left;"> $SPY $QQQ

👀

Trump says Putin&amp;#39;s invasion plan was &amp;#39;GENIUS&amp;#39;, praises &amp;#39;savvy&amp;#39; move to send the &amp;#39;strongest peacekeeping force in the world&amp;#39; to take over Ukrainian breakaway regions and says U.S. could do the same at the southern border </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:51:38 </td>
   <td style="text-align:left;"> $QQQ $BTC.X imagine holding puts until the war is over lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:50:50 </td>
   <td style="text-align:left;"> $SPY $QQQ 

They will jack up ES &amp;amp; NQ after 8pm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:50:11 </td>
   <td style="text-align:left;"> $spy $qqq $uvxy $dia $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:49:49 </td>
   <td style="text-align:left;"> $QQQ going up after hours did the war end so fast? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:49:42 </td>
   <td style="text-align:left;"> $QQQ so why are we up again? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:48:42 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:46:54 </td>
   <td style="text-align:left;"> $SPY $QQQ 
I&amp;#39;m slowly losing the will to live in this market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:46:50 </td>
   <td style="text-align:left;"> $FB $PYPL $QQQ $SPY it was clear that dip buyers starting really stepping back in the market today thats why we were down premarket then pop at open then down by lunch and up by close again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:45:37 </td>
   <td style="text-align:left;"> $QQQ bad sign rallying this fast this soon. Red by open💦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:45:31 </td>
   <td style="text-align:left;"> $FB $PYPL  chances are, you wont get the shares at these after hours prices today, tomorrow highly likely short cover gap up premarket as i said without an escalation overnight the market are set for a violent reversal. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:45:01 </td>
   <td style="text-align:left;"> $SPY $QQQ if futures rally without gapping down tonight, good chance that the bottom is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:44:17 </td>
   <td style="text-align:left;"> $QQQ Pumping like my stepsis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:44:11 </td>
   <td style="text-align:left;"> $SPY I really don&amp;#39;t understand what is the point of these &amp;quot;1-2 day relief rallies.&amp;quot; Rip the freaking Band-Aid off so we can get on with it already. 
 
$QQQ $AMD $NVDA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:43:29 </td>
   <td style="text-align:left;"> $QQQ futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:42:53 </td>
   <td style="text-align:left;"> $QQQ calls before close was the move. If you didn’t close your puts after that move down… your gains will be gone by open tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:42:12 </td>
   <td style="text-align:left;"> $QQQ $SPY $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:39:30 </td>
   <td style="text-align:left;"> $SPY $QQQ 
I&amp;#39;ll be very honest, even though I dislike Trump, at least he wouldn&amp;#39;t put up with Putin&amp;#39;s bluff. Trump&amp;#39;s a crazy mofo who&amp;#39;ll do anything to win a war and you never fight with crazy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:39:16 </td>
   <td style="text-align:left;"> $AAPL $qqq $spy $MSFT  
if no more bs tonight and tomorrow, we should bounce pretty good after many days getting killed by nonsense! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:38:46 </td>
   <td style="text-align:left;"> $QQQ gotta give it up to the resilience of the human spirit. There are certainties on what&amp;#39;s going to happen with rate hikes and tapering looming as the economy shows a strong rebound. Inflation data suggests it&amp;#39;s a growing problem which the Feds have been pivoting continuously to more and more hawkish positions to deal with. Russian sanctions will take effect, NG prices to Europe and crude oil prices worldwide have spiked, compounding the inflation issue. 

Most earnings for the quarter are done, and have resulted in market caps being cut as forward revenues and outlooks are revised due to the end of easy money policies. It may be a struggle, but the correction has started and will continue at least for the next few months as the market slowly fades. There will eventually be a period of capitulation resulting in a stepper drop. There has been a lot of struggle to find direction and sympathy bounces here and there, but the downtrend has been confirmed with this lower dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:37:51 </td>
   <td style="text-align:left;"> $QQQ $SPY When Biden entered office, we were at $40/barrel. Now we’re over $90. Now he is telling us we’re going to feel even more pain due to protecting Ukraine’s border when we can’t protect our own. Putin has a plan and is executing and Biden is reacting from a position of weakness. Last time Putin took Crimea from Obama/ Biden. I wonder what he’s going to take this time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:37:13 </td>
   <td style="text-align:left;"> $QQQ don’t understand this market smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:33:43 </td>
   <td style="text-align:left;"> $SPY  $QQQ Dont see any news but big pump AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:31:18 </td>
   <td style="text-align:left;"> Economies worldwide will get very hot this spring.  Covid is done!  People will be traveling and going to restaurants and partying and spending. 
 
Putin will chill out. That situation will de-escalate. 
 
Stocks are cheap. they had their correction.  
 
I am getting bullish on $SPY and $QQQ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:31:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
So we’re buying “Uncertainty “?
I thought the markets don’t like Uncertainty. Is it a new trend?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:29:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA Ukraine situation and political positioning likely to get dicier. Trade carefully, keep stops tight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:27:40 </td>
   <td style="text-align:left;"> $QQQ WEVE GOTTA RISER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:26:54 </td>
   <td style="text-align:left;"> Our $SPY  is looking out to the horizon and sees 9-12  months out and sees a Sea of Red. 
 
We know this right?  No?  Hmmm.... 
 
Maybe when we slowly churn the 420&amp;#39;s and slide into the teens, things will be more acceptable for some? All of the catalysts for erosion are right before our noses and yet, the machine is doing a great job of powering the moves and holding fairly steady. 
 
Crazy times ahead and some deep dippers will be endured but hopefully, all of the bleeding is contained by a trip to the Emergency Room provided it isn&amp;#39;t full of those sick COVID patients who knew better to skip the vaccine! So many needless deaths and the ignorance is still alive and well.  Death??  No problemo! 
 
Oh man!  What else could go wrong???? 
 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:25:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $RUT

I’m highly doubtful that Russia will feel threatened enough to stop invading the Ukraine. They have other commie allies in the East. 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:25:07 </td>
   <td style="text-align:left;"> Stock futures inch higher after S&amp;amp;P 500 closes in correction

$SPY $QQQ $DJIA 

https://www.investing.com/indices/indices-futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:23:50 </td>
   <td style="text-align:left;"> Blinken cancels plans to meet with Russian counterpart https://www.billionaireclubcollc.com/blinken-cancels-plans-to-meet-with-russian-counterpart/ $SPY $QQQ $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:23:18 </td>
   <td style="text-align:left;"> $QQQ this circus is hilarious....not a word about monetary policy....complete smokescreen....I&amp;#39;ll play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:23:18 </td>
   <td style="text-align:left;"> $BCRX so in a perfect world earnings in the am will provide $16 - $16.50&amp;#39;s to scoop up in size as I&amp;#39;m locked and loaded with BP in my two accounts just for the &amp;quot;Incase&amp;quot; quick dip. Honestly don&amp;#39;t believe we&amp;#39;ll see much lower if it&amp;#39;s to be taken down as MM&amp;#39;s run stops. Bring it on gang, either way we&amp;#39;re sitting on a Volcano! 🌋🌋 $SPY $QQQ $XBI $LABU cooperate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:23:06 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $IWM $DJIA  Notice that EVERY time the sentiment has been this low ...the mkt BLASTS OFF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:22:33 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:22:12 </td>
   <td style="text-align:left;"> $SPY 440 tomorrow. $qqq $dia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:20:33 </td>
   <td style="text-align:left;"> $QQQ scale in the invasion is the new scale in the dip these days 🧐😉

$DIA  $spy $DIA $XBI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:20:00 </td>
   <td style="text-align:left;"> $PYPL director bought at 103.96 $sofi $tdoc $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:19:05 </td>
   <td style="text-align:left;"> $SPY $QQQ

Maxar satellite images show new Russian deployment in Belarus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:17:03 </td>
   <td style="text-align:left;"> The Latest: Canada sends more troops to eastern Europe $SPY $QQQ $CADEUR $CADUSD https://www.billionaireclubcollc.com/the-latest-canada-sends-more-troops-to-eastern-europe/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:16:14 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:16:03 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 75003700. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:14:17 </td>
   <td style="text-align:left;"> $QQQ double bottom rip show boutta happen $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:13:35 </td>
   <td style="text-align:left;"> $SPY $QQQ  👊🏻🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:13:22 </td>
   <td style="text-align:left;"> $SPY $UVXY $AAPL $WMT $QQQ 

HEADS-UP! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:13:21 </td>
   <td style="text-align:left;"> $SPY $QQQ Puts gains today 
All from the callout.
#gains #daytrade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:13:18 </td>
   <td style="text-align:left;"> $SPY $QQQ Lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:13:14 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DJIA $IWM  ++This in case you dont get it is ULTRA BULLISH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:12:49 </td>
   <td style="text-align:left;"> $SPX $SPY $DIA $DJIA $QQQ  👊🏻🧞‍♂️

Taking advantage of taking a profit right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:11:43 </td>
   <td style="text-align:left;"> $QQQ $SPY market treating this like it’s the start of WW3 but US not getting involved with military </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:11:19 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures up, looks like we are getting an overdue bounce tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:08:03 </td>
   <td style="text-align:left;"> $SPY $QQQ today’s SPY and NASDAQ 100 buys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:07:10 </td>
   <td style="text-align:left;"> $QQQ $SPY $SPX $BTC.X 

Compare Biden’s speech to what trump would have said..

“Putin is a very strong and handsome man, Russia is a very beautiful country, covfefe , inject bleach etc , etc , etc” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:06:53 </td>
   <td style="text-align:left;"> $QQQ hope you  bought the lows today ....  
 
tomorrow gonna be huge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:05:50 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.youtube.com/watch?v=n00gMkUI8Ug 
 
Tom Lee is one of those guys who make correct calls more often than incorrect calls for the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:03:08 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 2/22/2022 $SPY $XLF $QQQ $TSLA $MSOS https://www.chartguys.com/daily-market-videos/4143/bears-comfortable-for-now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:03:05 </td>
   <td style="text-align:left;"> $QQQ if we’re truly kicking off a rally here, targets are 342-346-353-same as before </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 07:00:33 </td>
   <td style="text-align:left;"> $TDOC bought more.

Beat earnings.

Year forecast is in line with expectations.

Huge growth happening. 

Any light volume manipulation to swoop shares has got me buying more. 

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:59:19 </td>
   <td style="text-align:left;"> $ROKU $qqq 366 DOLLAR CALLS FOR MARCH 7TH, LOOKING FOR 8% UPSIDE ON DAQ IN 10 DAYS.... .32C AVERAGE ... LAST BULL TRAP RUN COMING.
B4 MARCH KNIFE SHOW... GL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:59:17 </td>
   <td style="text-align:left;"> $QQQ $BTC.X $SPY $SPX $DJIA 

Nothing can stop the Biden markets. Not inflation, not war … NOTHING !!!!

Thank god for this man !!! 🇺🇸🙌🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:55:39 </td>
   <td style="text-align:left;"> $SPY $QQQ Day trader playground </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:54:57 </td>
   <td style="text-align:left;"> $QQQ Face Ripper Rally tommorow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:53:05 </td>
   <td style="text-align:left;"> Alert on $SPXS delivered today at 11:25AM CDT on 2/22/2022 🎯

We assume a minor pullback more today and tomorrow. Also expect more choppy price action in the coming days. With the Russian-Ukrainian conflict I assume more downside in the market. All my thoughts are opinions, not financial advice. 

Server link in the bio for winning alerts and for those eager to learn. 

$SQQQ $TQQQ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:51:53 </td>
   <td style="text-align:left;"> $QQQ technical analysis for tomorrow. 
 
https://youtu.be/PP1Fvk4oUng </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:51:01 </td>
   <td style="text-align:left;"> $SPY $QQQ 

President Zelensky has signed an order calling up reservists </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:47:38 </td>
   <td style="text-align:left;"> $QQQ $SPY $BTC abe blinken </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:47:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $LEH This market is making me reminisce the good ol’ days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:47:33 </td>
   <td style="text-align:left;"> Alert on $SQQQ delivered today at 10:40AM CDT on 2/22/2022 🎯

Server link in the bio for winning alerts and for those eager to $TQQQ $QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:46:47 </td>
   <td style="text-align:left;"> $QQQ Imagine u blame the President, war, or anything else for ur silly trading skills. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:46:21 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY $SPX $DJIA 

The CEO’s of your favorite companies responded poorly to the pandemic and that is why we are experiencing supply chain issues. 

Biden whipped these guys into shape. Got them to get their act together. What a blessing that Trump is out, and Biden is in🇺🇸

Keep it up Biden , you magnificent beast. 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:45:35 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY $SPX $DJIA 

Thank the lord for Biden , his amazing vaccines, containing/eradicating the virus with his well executed plan (something trump couldn’t do), his push to get conservative CEOs to fix their supply chain issues and his strong arm stance to JPOW, curbing inflation. Not only this, but he also was able to stand up too and scare off Putin. 

What a blessing that Biden is in and Trump is out. 

Not to mention he has the best VP in the history of this nation at his side in Kamala Harris.

No more Republicans please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:44:35 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY $SPX $DJIA 

It’s rare we see a President do so many things right this early on in his term.

Biden, you magnificent beast.

Keep up the outstanding work, our economy is roaring. 

Takes notes - Conservatives 🇺🇸✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:43:46 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Blinken says the meeting with Russia&amp;#39;s Lavrov has been cancelled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:43:39 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY $SPX $DJIA 

Thank god for the democrats.

If Trump and cronies were still in power at the White House - we’d be smack in the middle of a recession right now. 

Thank god one of the the most cruel and worst leaders in Donald Trump is out after only one term, and Biden is in. 

We are blessed 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:42:48 </td>
   <td style="text-align:left;"> $QQQ , $IWM 
Guys watch this video, classic crooked short selling, MM illegally creating synthetic shares under the “exempt” fraud…

https://youtu.be/JgVuD8d2E5o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:41:33 </td>
   <td style="text-align:left;"> $BTC.X $SPX $SPY $QQQ $DJIA 

Donald Trump could quite possibly be considered one of the WORST leaders in the history of the world. Let that sink in.

Thank the lord Biden is in, and Trump is out. Biden eradicated the virus with his beautiful executed plan, and now prevented a world war by scaring off Putin. Putin wanted no part of Joe’s Wraith so he decided to ride with Biden rather , instead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:40:47 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Looking for a true gem…MAXR

Maxar Technologies beat estimated earnings by 1242.86%, reporting an EPS of $0.94 versus an estimate of $0.07.

Plus 90% institutionally held. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:39:31 </td>
   <td style="text-align:left;"> $BTC.X $SPX $QQQ $SPY $DJIA 

The science behind the vaccines in Moderna’s , Pfizer’s and J&amp;amp;J’s Pipeline may just be some of the most ambitious and cutting edge processes we have ever seen in the history of the world. 

Incredible.

Thank god Trump is out, and Biden is in 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:38:48 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPX $SPY $DJIA 

Republicans are truly not the brightest , they crash all the markets and then blame the democrats. 

Turn off faux news and do your own research guys. It’s called reality - not everything is a conspiracy theory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:38:21 </td>
   <td style="text-align:left;"> A nervy balance for markets $QQQ $IWM $SPX https://talkmarkets.com/content/stocks--equities/a-nervy-balance-for-markets?post=345715 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:37:50 </td>
   <td style="text-align:left;"> $QQQ $NQ_F $TQQQ  is not what you want to see if you are short the NASD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:36:47 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Vladimir Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:36:46 </td>
   <td style="text-align:left;"> Will Russia’s Ukraine invasion push up oil prices, inflation?

https://www.latimes.com/politics/story/2022-02-22/how-much-u-s-economic-damage-will-putins-advances-in-ukraine-cause?_amp=true

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:36:18 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPX $SPY 

I feel comfortable with Biden.

Trump has shown he is very stupid and has the attention span and temper of a 2 year old.

The Russia situation would have been too much for the child to handle. 

Thank god Biden is in, and Trump is out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:35:39 </td>
   <td style="text-align:left;"> Jeremy Siegel: Fed inflation fight way more important to U.S. economy, markets than Russia-Ukraine

https://www.cnbc.com/2022/02/22/jeremy-siegel-fed-hike-more-important-to-us-economy-markets-than-russia-ukraine.html

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:34:50 </td>
   <td style="text-align:left;"> $QQQ wouldn’t be surprised if we gap up tomorrow or even finish only barely red. Of course, then we see another two days of sell offs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:32:32 </td>
   <td style="text-align:left;"> $QQQ daddy tom lee said we good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:32:20 </td>
   <td style="text-align:left;"> $QQQ powerful explosion on the territory of the Donetsk television center. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:32:08 </td>
   <td style="text-align:left;"> $QQQ $SPY we aren’t going head to head with Russia like a lot of you think and Biden just said so 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:31:43 </td>
   <td style="text-align:left;"> $QQQ US Secretly of State Blinken just cancelled his next week meeting with Russian foreign minister Levrov. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:29:56 </td>
   <td style="text-align:left;"> $QQQ $BTC.X $ETH.X   
&amp;quot;Russia wants to regulate crypto&amp;quot; = &amp;quot;Putin wants to buy Bitcoin.&amp;quot;  
 
&amp;quot;US want to regulate crypto&amp;quot; = &amp;quot;Biden wants to ban Bitcoin.&amp;quot; 
 
Imagine simping for Putin while calling yourself a &amp;quot;patriot&amp;quot;. Fuckin morons. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:29:56 </td>
   <td style="text-align:left;"> $SPY $QQQ Nobody likes war but the good news is that it seems like it will be a very quick war and the US won&amp;#39;t be sending any troops to Ukraine and Russia. Basically only the economy will only suffer in Russia while it is business as usual for rest of the world, I hope the market will stop overreacting to the current war news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:28:37 </td>
   <td style="text-align:left;"> $QQQ I see double bottom  
jan.- Today  
Nas100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:28:24 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $NDX … will Fed let inflation run wild &amp;amp; risk recession… cuz of Ukraine?

Asking for a friend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:28:20 </td>
   <td style="text-align:left;"> $UVXY $QQQ $SPY $SQQQ - US Secretary of State Antony Blinken has cancels Diplomatic Summit with Russia. Biden ordering more troops in Russia surrounding NATO member countries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:27:19 </td>
   <td style="text-align:left;"> $SPY $DWAC $Qqq

Imagine a president not even taking questions at a time like this.

True leadership.

SMH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:27:01 </td>
   <td style="text-align:left;"> $QQQ if the invasion had already happened last week we would have already bounced, instead we just bleed out for over a month with the threat of the invasion? 
 
MAKES NO FUCKING SENSE PEOPLE!!!! 
 
THIS IS A BUYING OPPORTUNITY!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:26:36 </td>
   <td style="text-align:left;"> $QQQ crazy how parabolic the market went over the last two years and people think this is organic especially with our economy shutdown and stagnant. The Feds are not on our side anymore and will be removing trillions from their balance sheet. We will probably correct to January 2021 levels in the next few weeks as inflation causes the Feds to accelerate their tightening. The Russian sanctions and conflict will cause energy prices to increase from NG to crude oil which will compound the inflation problem. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:24:45 </td>
   <td style="text-align:left;"> $QQQ for all the absolute dipshits saying that this is oversold @cal1928 

REJOICE I finally found the data you&amp;#39;ve needed to make your bull case! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:23:02 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DJIA $IWM  
 
I have never seen a more BULLISH time in the stock market than right NOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:22:50 </td>
   <td style="text-align:left;"> $BABA is this some collaborative effort between Brandon, Xi and Putin to fuck up the markets? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:22:32 </td>
   <td style="text-align:left;"> $QQQ Bull Market Incoming! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:22:22 </td>
   <td style="text-align:left;"> $QQQ sooner or later, our generation is facing a horrible time. The chart is actually predicting how the economy will be in the next 10 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:21:38 </td>
   <td style="text-align:left;"> $ARKK Poster child of the EV Tech &amp;amp; Crypto mania. I believe that this portfolio better represents the average Americans investment account or IRA account. The DOW is so old fashioned and many want to believe that we are on the cusp of flying to mars in electric space shuttles funded by Crypto Tokens like &amp;quot;SpaceCoin&amp;quot;. What a time to be alive. $TSLA $BTC.X $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:18:01 </td>
   <td style="text-align:left;"> $QQQ Trump and Putin need to hang more often </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:17:26 </td>
   <td style="text-align:left;"> $SPY $QQQ $IEF $SHY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:15:50 </td>
   <td style="text-align:left;"> $SPY $QQQ made some good plays today on the puts 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:15:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL Bottom line: Bulls got RUG PULLED by the smart money and they are the dumb money. Tonight Vladamir Putin will invade New York while the snow melts and King Kong will tear down the Empire State Building. SPY will gap down to 380 and allude the circuit breakers. My OTM puts will print with the MM&amp;#39;s SHORT positions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:13:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $TLT $UUP  
Nasdaq double bottom,  SPY and IWM higher lows?  
https://www.youtube.com/watch?v=Cxkh9YIo16A&amp;amp;feature=youtu.be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:12:55 </td>
   <td style="text-align:left;"> $QQQ This will be in the &amp;quot;shithouse&amp;quot; later this year if not sooner. More institutions are short as a hedge. If they&amp;#39;re uncertain, what makes you think the btd is still an absolute.

Shithouse is just a funny adjective. Comrade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:11:11 </td>
   <td style="text-align:left;"> $QQQ go back a month or two ago and look at the s&amp;amp;p 500 ETF and the NASDAQ QQQ ETF on the weekly chart. Anyone with half a brain and at least one working eyeball could chart that and see how hilariously high institutions pumped the stock market.  Even the major drop at the beginning of 2020 when the pandemic first happened was just a blip on the radar on the weekly chart. In fact all that did was drop to touch a major moving average and then continued on its upward trajectory twice as fast. The uptrend has been going on for years now and the pandemic drop was just a minor correction now we are looking at the tipping point for what could be a long-term bear market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:11:08 </td>
   <td style="text-align:left;"> $QQQ $SPY i hope tomorrow these Atleast open green so I can sell
My $VXX puts for some
Profit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:09:05 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

I added leap puts before the close in spite of that disgusting fake end of day pump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:08:53 </td>
   <td style="text-align:left;"> $ENPH to those lamenting our current President, things could be much worse. @Kornie7 $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:08:35 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM I&amp;#39;m still long, a little underwater.  
Dilemma - the market is re-testing Jan low...if I exit NOW, then I would be looking for a re-entry as the market is CURRENTLY in a &amp;quot;buy&amp;quot; zone (according to my analysis).  On pins and needles for the next few days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:08:01 </td>
   <td style="text-align:left;"> $QQQ my all in yolo 410c I grabbed after Biden speech were worthless. Wtf 😑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:05:02 </td>
   <td style="text-align:left;"> $SPY $QQQ Bottom line, the market is way oversold and currently the market is focusing too much on Russia and war rather than the strong fundamentals of the US economy. Once people realize that it is business as usual here in the US no matter what&amp;#39;s going on in Russia and Ukraine, we will see a massive rebound for this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:04:43 </td>
   <td style="text-align:left;"> $QQQ Pulling nads to day Pulling nads to day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:04:07 </td>
   <td style="text-align:left;"> $QQQ 443 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:03:36 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $NDX … no meeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:03:16 </td>
   <td style="text-align:left;"> $QQQ same s*** different month.  You could look at the weekly chart of these major indexes and see how overbought they have been. everyone who does even a little bit of technical analysis knows what it looks like... especially when using Fibonacci Bollinger bands.  So after they&amp;#39;ve pumped it sky high and it&amp;#39;s very clear that the stock market is inflated that&amp;#39;s when all of the crazy news comes out about the 50th variant of covid and oh no Russia&amp;#39;s going to war and oh no inflation and interest rates and oh no cry me a River there&amp;#39;s so many things happening all of a sudden coincidentally when the stock market is in super overbought territory and they use that negative rhetoric to fuel the sell off while the institutions have already loaded up their puts and profit on the way down while the majority of uneducated retail investors keep buying what they think is a dip or just hold their stocks and lose their value . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:02:59 </td>
   <td style="text-align:left;"> $QQQ Holding faster holding faster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 06:02:03 </td>
   <td style="text-align:left;"> $SPY   $QQQ 
 
With our comrade Vlad holding all the cards including the trump cards, it&amp;#39;s going to be hard to enjoy a winning hand. 
 
The Putin cancer has re- emerged much to our chagrin. But fear not, when Ukraine is firmly in his hands, it will likely be much worse as commerce and other financial issues cause that nasty chaos that we would rather avoid. 
 
He said, he wouldn&amp;#39;t invade and his tactics are working wonders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 05:58:34 </td>
   <td style="text-align:left;"> $SPY  $QQQ  $IWM  Weekly Elliot Wave market review.  Please enjoy; Cheers!  
https://youtu.be/I_ojG91wo0A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 05:58:16 </td>
   <td style="text-align:left;"> $qqq don’t get caught leaning in da 🐑.   Especially if this turns into 2nd half of 2011ish.  Bears maybe winning now.  But da 🐑 don’t care bear or bull.   All fooked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 05:55:25 </td>
   <td style="text-align:left;"> $QQQ wow I thought i was a choanocytes selling my puts when QQQ was down 1.5%looks like I’ll get to buy them back much cheaper. I shorted volatility instead. I still think tomorrow we may open green but fade. Thursday and Friday I believe will be more big red days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-23 05:54:49 </td>
   <td style="text-align:left;"> $SPY these sanctions are going fk us..  We already got supply issues,  now the tech sector is going get his harder. $QQQ  thanks Brandon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:46:32 </td>
   <td style="text-align:left;"> $MULN $FB $AAPL     All that you need to know;. Shorts haven&amp;#39;t covered a single share:~~~~~~ Check it out below 👇  
highly recommend everyone to follow them. 🚀     mostwinningchat.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:36:35 </td>
   <td style="text-align:left;"> $AMD $NVDA $AAPL thats the risk relying on Taiwan, don’t put all your eggs in one basket. INTC smart investing against to geopolitical risk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:32:35 </td>
   <td style="text-align:left;"> $AAPL buy the rumor sell the news. So when there’s bad news like a potential war should you sell the rumor and buy the news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:28:09 </td>
   <td style="text-align:left;"> $AMZN $AAPL Members made +$500in profits for the day with our Options Alerts of $AMZN , $WMT &amp;amp; $PFE within 30 minutes.

Please join our whatsup group 1 month free
chat.whatsapp.com/Lt2vyMfOQqB7Q4…

chat.whatsapp.com/LU8QOWTzFAr9r2… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:27:25 </td>
   <td style="text-align:left;"> $TDOC $AMD $FB $AAPL I&amp;#39;d like to invite you to make 300k starting with 500k....oh wait! Lol...don&amp;#39;t you hate those ads...jeez. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:26:03 </td>
   <td style="text-align:left;"> $AAPL $SPY All china stocks look to be pump and dumps. I&amp;#39;m guessing every time a stock IPOs they all buy calls and then cash out at the top after the quick run, because then you can spend the rest of the time printing naked shorted shares and get rich with ease </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:22:05 </td>
   <td style="text-align:left;"> $AAPL I guess the markets will be crashing the week.  Terible times coming.  Major losses coming.  How do we keep strong during this current crisis? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:21:20 </td>
   <td style="text-align:left;"> $AAPL $170 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:13:06 </td>
   <td style="text-align:left;"> $AAPL Closing chart on Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:08:01 </td>
   <td style="text-align:left;"> $AAPL $DWAC From Philip Elmer-DeWitt&amp;#39;s Apple 3.0 
&amp;quot;Truth Social is Trump-ing the App Store at #1. While the app’s debut resulted in nearly 500K left on the waitlist, President Trump once had 88.9M followers on Twitter. Free speech is what promotes the marketplace of ideas, but 500K on any social media platform is likely not enough to sustain compelling conversation.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:07:01 </td>
   <td style="text-align:left;"> $AAPL 👁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:06:08 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-20 Largest Trades Data: 
https://www.youtube.com/watch?v=2h5BxPQmOcM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:05:06 </td>
   <td style="text-align:left;"> $AAPL wow on watch for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 10:03:11 </td>
   <td style="text-align:left;"> $AAPL i hope its bloody all week latex442ca008e0e9403806381b25871a077dMU 93c 133%
@MommasOptions 
$AAPL 160p 100%+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:35:26 </td>
   <td style="text-align:left;"> $SPY $AAPL no less than 30 min after hours closes, futures are losing ground fast and Almost too eager to get back to the default red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:32:58 </td>
   <td style="text-align:left;"> Watch list for tomorrow part 1: $ZVIA $FUBO $CLOV $AAPL $PYPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:32:08 </td>
   <td style="text-align:left;"> $AAPL I have 170 shares now in 20 years think we will split a few more times? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:29:48 </td>
   <td style="text-align:left;"> $AAPL this will push to make a lower high. 4hr was oversold. Friday high needs to break. 170-171 is possible test in coming days. Still in a daily/weekly downtrend since ATH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:27:32 </td>
   <td style="text-align:left;"> Some of the BIGGEST options trades for today 
$AAPL $TSLA $FB $ROKU $SPY 
https://goldentrading.website/learn-how-to-trade-stocks-and-make-1000-a-day-make-money-while-you-sleep/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:26:02 </td>
   <td style="text-align:left;"> $AAPL what’s this green shit in AHs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:24:04 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG the bs bottom is over March is coming by April’s close to ATHs again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:23:42 </td>
   <td style="text-align:left;"> $AAPL call volume 🤔

$172 🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:18:29 </td>
   <td style="text-align:left;"> $AAPL Futers are ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:17:54 </td>
   <td style="text-align:left;"> $AAPL If NASDAQ 🐻Decline Continues then maybe a full year back to 3/2021 Lows
We shall see…. 
$AMD $QQQ $MSFT $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:15:44 </td>
   <td style="text-align:left;"> $AAPL About F N time...  Don&amp;#39;t trust futures though... BS!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:08:24 </td>
   <td style="text-align:left;"> $AAPL $PYPL $NVDA We alerted about this set up - could be a huge day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:08:03 </td>
   <td style="text-align:left;"> $AAPL $SPY  will this green in futures hold? Almost absolutely not. Barely green if green at all by open seems to be the expectation unless there’s another sell off magically around 3 am. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:05:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 09:01:46 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $167.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:58:18 </td>
   <td style="text-align:left;"> $AAPL  RIPPPPPPPPPPPPPPPPING FUTES💝💝🎁🎁💝💝💝💝🎁🎁💝💝💝💝💝💝💝💝💝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:57:55 </td>
   <td style="text-align:left;"> $TSLA $BABA $BIDU $AAPL 

Massive stock crash is near … Taiwan will be taken over by air and sea …. No missiles can stop destiny …. The seas and oceans know this , many bodies are about to sink to the bottom of the ocean 🌊 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:53:56 </td>
   <td style="text-align:left;"> $AAPL Waiting for 159-160. Hopefully going over $200 by q3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:51:14 </td>
   <td style="text-align:left;"> $AAPL $TSLA $BTC.X  $QQQ Risk management? …..Pshhh, if you aren’t taking out loans for options plays or betting your life savings like a degenerate gambler the. You are just a puss boy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:47:56 </td>
   <td style="text-align:left;"> 2/22 RECAP

✅ $SPY 425p 2/23 +200%

✅ $AAPL 160p 2/26 +40%

✅ $TDOC +13%

✅ $MULN +10%

✅ $KAVL +4% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:46:45 </td>
   <td style="text-align:left;"> $AAPL the fact.. you know, the world called Russia is a 🐻 🐻‍❄.   Just feed them 🍯.. They will quietly back in hibernation.  Hahahha.. 

Here kitty 😺 😍 ☺️  honey 🍯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:41:29 </td>
   <td style="text-align:left;"> $AAPL will se see $164.00 again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:40:20 </td>
   <td style="text-align:left;"> $AAPL Sleepy Joe’s severe sanctions were so punishing on Russia that their stock market rose 6.5% after Sleepy announced them 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣
Sleepy is F embarrassing !!!
$TSLA $AMZN $FB $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:32:31 </td>
   <td style="text-align:left;"> $AAPL we are good. No worry, keep buying.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:29:15 </td>
   <td style="text-align:left;"> $SPY I believe that Putin&amp;#39;s plan is to spread fear with the potential invasion of Ukraine in order to tank the U.S stock market and deal a huge blow to America.  It is working.  Sleepy Joe&amp;#39;s sanctions ain&amp;#39;t going to do shit to Putin.  It is up to INVESTORS AND INSTITUTIONS TO FOIL PUTIN&amp;#39;S PLAN and push this market to a new ATH.  We need the top companies stocks (FAANG + a few others) to pump this market and give a middle finger to Putin.  That is the American way.  $MU $NVDA $AMD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:28:16 </td>
   <td style="text-align:left;"> $AAPL PayPal exterminator amongst many others. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:26:23 </td>
   <td style="text-align:left;"> $AAPL Putin is an evil. Russia is a troublemaker. Kill Putin and destroy Russia. World will become peaceful. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:18:39 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
Hey MEDIA SHEEPS!...you still consuming mainstream media and using their &amp;quot;war&amp;quot; narrative to explain markets moves? 
 
Stop!...DON&amp;#39;T DO THAT!!! 
 
Only worry about the FED and free money liquidity it provides to the financial markets. Make sure you can answer and explain the following AT MINIMUM. Then you just might have a chance to truly understand and be in sync with what REALLY moves the markets. 
 
Do you know when the FED is scheduled to end QE? 
Do you know the amount of liquidity they are removing from the market each month? 
Do you know when the first rate hike will be? 
Do you know how much the first rate hike will be? 
Do you know how many other rate hikes are priced into the market? 
Do you know how the FED will reduce it&amp;#39;s 9 TRILLION dollar balance sheet this year? 
ETC, ETC, ETC 
 
Don&amp;#39;t be a MEDIA SHEEP!...be a FED SHEEP!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:16:14 </td>
   <td style="text-align:left;"> Will dump a bunch of charts later. Reply to this with the ones you want if you like  
 
$QQQ $AAPL $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:09:10 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ there is a weird color on the futures.. it&amp;#39;s something I don&amp;#39;t recognize.. green? Da fuq? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:07:27 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG load uppp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 08:04:19 </td>
   <td style="text-align:left;"> $UPST Some of you should consider how to use capital tax loss strategies with your investments / trading plan(s).  For example:  With this stock I sold a month ago for around this same price - took my hit.  Freed my capital up to invest / trade other stocks.  After 30 days has passed - I have gotten that tax loss secured and now can buy back in.  In this case - I sold for around the same price it is trading now.  In the mean time - I was able to make gains and invest in others - and now get back in to this with a capital loss secured.  If you plan it right - it can make a huge difference in your p/l.   
 
https://www.investopedia.com/articles/stocks/08/capital-losses.asp 
 
$SQ $AAPL $ABNB  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:59:37 </td>
   <td style="text-align:left;"> $SPY $AAPL $NVDA $MATIC.X $SOXL 
Train leaving  🚞💨💨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:51:02 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 47.8K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:50:06 </td>
   <td style="text-align:left;"> $AAPL BULLISH. $10 swing coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:48:20 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA $AAPL $BTC.X Russia, china, and N. Korea all bought the dip! Y’all got swindled by a fake war 🦍🦍🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:48:14 </td>
   <td style="text-align:left;"> $SPY about 6% of the SPY float is being loaned to short-sellers, highest since the election! This is a sign that the SMART MONEY has gone all-in short with me and betting on a retest of the March 2020 lows. 
 
Sorry bulls, looks like $AMD $AAPL and $NVDA will be in double digits by March... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:47:01 </td>
   <td style="text-align:left;"> $AAPL VR headset rumored to cost 2k.   First gen let&amp;#39;s say they sell 20 million units then 10 million units a year into foreseeable future.  This adds 2 billion to annual revenue w a nice additional boost for the first gen.  Sounds meager.  But then consider purchases to augment the headset experience, games and apps bought, ads sold, very hard to quantify and I&amp;#39;m not paid to do it or privy to the proper data but I&amp;#39;d guess Apple is counting on the lion&amp;#39;s share of the revenue coming from the peripherals, not the headset itself.  Let&amp;#39;s say 4x the revenue generated by the headset.  8 billion + 2 billion = 10 billion, or roughly 3.8% bump in annual revenue at the very very least.   Not bad but not great.  Who hates the numbers here and why? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:44:25 </td>
   <td style="text-align:left;"> $AAPL $SPY $PYPL $NVDA Nice productive day in OP land….
Are you in? If not, take advantage of our free month trial - it’s risk free - cancel anytime- we know you won’t want to🤷🏼‍♂️😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:39:16 </td>
   <td style="text-align:left;"> $AAPL $qqq $spy $MSFT  
if no more bs tonight and tomorrow, we should bounce pretty good after many days getting killed by nonsense! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:26:53 </td>
   <td style="text-align:left;"> Salesforce CEO Marc Benioff started as a 19-year-old Apple intern — here’s why he was hired and what he learned

$CRM $AAPL

https://www.cnbc.com/2022/02/22/salesforces-marc-benioff-what-i-learned-as-a-teenaged-apple-intern.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:23:06 </td>
   <td style="text-align:left;"> $AAPL Concerned Citizen 🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:22:43 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:18:58 </td>
   <td style="text-align:left;"> $AAPL calls over 165.50 for tmorw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:15:45 </td>
   <td style="text-align:left;"> $AAPL gap up with huge green open tomorrow. No more Ukraine support for shorts. Everything spelled out and no more surprises tomorrow. Gap up $170.00 squeeze or cover </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:13:41 </td>
   <td style="text-align:left;"> $SPY $MSFT $GOOG $AAPL  America always stands resolute, we are tough and we stand united. We will be 500+ years strong. Fuck anyone anti-America! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:13:22 </td>
   <td style="text-align:left;"> $SPY $UVXY $AAPL $WMT $QQQ 

HEADS-UP! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:10:44 </td>
   <td style="text-align:left;"> Standoff ends at Amsterdam Apple Store, hostage safe $AAPL https://www.billionaireclubcollc.com/standoff-ends-at-amsterdam-apple-store-hostage-safe/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:09:03 </td>
   <td style="text-align:left;"> $AAPL If you’re a Bear, Short, or just plain anti-American, keep scrolling.  You really want to send a message to Russia and Putin?  Let’s send the US markets back to ATHs.  They could care less about the new sanctions.  I guarantee they were closely watching the US markets today hoping for a huge selloff.  They are using the weakness in the markets from Covid and inflation to their advantage.  STOP doing exactly what they want by selling every little whisper of doom.  Losing this leverage will make a bigger impact than any of these sanctions.  💎 🚀 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:07:39 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $TQQQ $SOXL 
Hey 🤡🐻,  Zip it 🤐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:03:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:02:48 </td>
   <td style="text-align:left;"> $AAPL one more bounce then I&amp;#39;m going to short this again. Told yall it would go to 160 before the end of the month. The next drop won&amp;#39;t be as light as this one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 07:00:59 </td>
   <td style="text-align:left;"> $AAPL $AMD Weekly add to 2 of my favorite hoes 🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:58:34 </td>
   <td style="text-align:left;"> $AAPL price discovery is back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:55:58 </td>
   <td style="text-align:left;"> $AAPL The basement dummy wants to start WWIII - and won’t even take a question. 

What a worthless coward. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:53:46 </td>
   <td style="text-align:left;"> $AAPL technical analysis for tomorrow. 
 
https://youtu.be/t7vIB_oNE9A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:51:13 </td>
   <td style="text-align:left;"> $AAPL Stock Trading Ideas | 8 Trades executed, trade Profitability of 75% and Profit Factor of 7. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:48:39 </td>
   <td style="text-align:left;"> $AAPL Big buys after hours, bears haven’t covered, this Russia war fun will be done in a week same as the taliban fud that brought the market down for couple of weeks then Apple went up 40p. Probably trading around $190 before next earnings report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:43:45 </td>
   <td style="text-align:left;"> https://youtube.com/watch?v=JStETvXu0vM&amp;amp;feature=share
I own $googl , looking at $aapl and $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:36:46 </td>
   <td style="text-align:left;"> Apple’s AR/VR headset isn’t just a prototype anymore, sources say - Ars Technica $AAPL  https://apple.news/Aw_CClkjvTDakjZX_iw7CuA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:31:10 </td>
   <td style="text-align:left;"> $AAPL Nathan is big time Apple short, he gets off on shorting the market , just another gambling fool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:30:07 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-20 Largest Trades Data: 
https://www.youtube.com/watch?v=2h5BxPQmOcM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:29:30 </td>
   <td style="text-align:left;"> Comparison $SPCE $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:23:04 </td>
   <td style="text-align:left;"> $AAPL $170 by Friday 🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:19:28 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Broadcom Still Looking At Robust Demand Even As Tech Investor Enthusiasm Cools https://www.stck.pro/news/AAPL/23310146 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:16:34 </td>
   <td style="text-align:left;"> $SPY $SPX $AAPL   ichimokuuuu... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:15:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL Bottom line: Bulls got RUG PULLED by the smart money and they are the dumb money. Tonight Vladamir Putin will invade New York while the snow melts and King Kong will tear down the Empire State Building. SPY will gap down to 380 and allude the circuit breakers. My OTM puts will print with the MM&amp;#39;s SHORT positions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:14:11 </td>
   <td style="text-align:left;"> $AMD $AAPL $TSLA $AMD  
Holding on by a thread. Needs to hold lows. 
 
https://www.youtube.com/watch?v=Cxkh9YIo16A&amp;amp;feature=youtu.be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:12:49 </td>
   <td style="text-align:left;"> $AAPL Do you even understand the array of potential products and scope of the ecosystem AAPL presents going forward?  Forget about today&amp;#39;s lineup.  Just talking stuff in the pipeline - inestimably valuable.  To be bearish for even a millisecond here just give up.  Retire from stocks.  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:09:50 </td>
   <td style="text-align:left;"> $AABB $BTC.X $ETH.X $GLD $AAPL AABBG.X gold backed tokens are increasing with gold prices. BOOM TOWN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:05:22 </td>
   <td style="text-align:left;"> $AAPL 170 incoming.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:04:54 </td>
   <td style="text-align:left;"> $AAPL https://uk.finance.yahoo.com/amphtml/news/why-think-apple-share-price-165935100.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 06:03:28 </td>
   <td style="text-align:left;"> Several technical/sentiment/internal signs signaling that we are close to a bottom here.  The rally should be quite a ripper.  But may be a few days of chop yet ahead of us.    $SPY $QQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:57:35 </td>
   <td style="text-align:left;"> $NVCN  VS $AAPL , maybe NeoScam has a change to win the fight, has to be proven (lol): &amp;quot;nothing is for certain in life&amp;quot;, the CEO Fredericrook Colen said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:55:36 </td>
   <td style="text-align:left;"> $AAPL $DWAC this makes me wonder.... 

Why does apple currently support a platform that is exactly 180° opposite of what they stand for. Namely, freedom of speech, Americanism, and truth? 

What on earth are you thinking apple? You are allowing your own destruction?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:51:01 </td>
   <td style="text-align:left;"> New Peloton Lanebreak Similar To Video Game: Is It More Than Meets The Eye?  $PTON $AAPL $TSLA 

https://newsfilter.io/a/69ae2fcdebe2183639af6c83e0380ba1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:49:20 </td>
   <td style="text-align:left;"> $SPY Putin working hard to get rid of COVID.

*APPLE TO DROP CUSTOMER MASK MANDATE IN MOST RETAIL STORES $AAPL

covid over? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:48:48 </td>
   <td style="text-align:left;"> $AAPL Has been very technical off the Jan 24 low.  It still remains above that low and has now found some buyers around equal leg from the 2/9 peak.  We still favour more downside to take place, but while it is in the middle area, not liking to take new positions #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:42:07 </td>
   <td style="text-align:left;"> $AAPL hostage situation in Amsterdam at apple store </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:41:10 </td>
   <td style="text-align:left;"> * APPLE TO DROP CUSTOMER MASK MANDATE IN MOST RETAIL STORES 
 
* APPLE STORES ALSO PLANNING RETURN OF IN-PERSON CLASSES 
 
$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:39:45 </td>
   <td style="text-align:left;"> $AAPL today was such an overreaction. We are so oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:39:15 </td>
   <td style="text-align:left;"> $AAPL Alrighty then. Now we&amp;#39;ll see how much we&amp;#39;re down tomorrow. Isn&amp;#39;t this fun. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:36:22 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 190.8K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:32:54 </td>
   <td style="text-align:left;"> Going to send out my WATCHLIST later tonight! and my analysis. 
 
Would recommend FOLLOWING me.  
We caught $TSLA for 120%+ today and $AAPL for 30%+  
 
Giving this all out for FREE, don&amp;#39;t FOLLOW at your own risk :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:31:55 </td>
   <td style="text-align:left;"> $SMFL $AMD $PLTR $AAPL lets go SMFL reversal dont miss the gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:31:24 </td>
   <td style="text-align:left;"> $AAPL union woes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:29:25 </td>
   <td style="text-align:left;"> $AAPL back to $170 we go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:27:20 </td>
   <td style="text-align:left;"> $AAPL $180 eow, bears are f-cked 🚽💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:23:49 </td>
   <td style="text-align:left;"> $FB $AAPL $TSLA  
Giant snowball rolling down hill. Gaining speed.   
Nasdaq approaches death cross.   
 
Putin, telling the Ukraine to disarm.   
Its going to get worse before it gets better... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:23:41 </td>
   <td style="text-align:left;"> Going to be posting my Trades EVERY morning PRE-MARKET! FOLLOW AND WATCH. We caught $TSLA $AAPL for 100%+ on TSLA and 30%+ on AAPL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:21:48 </td>
   <td style="text-align:left;"> $AAPL $160 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:20:00 </td>
   <td style="text-align:left;"> $AAPL 
  
AAPL what a choppy start to the week of trading. Russia/Ukraine, Biden speech, general market sentiment. How are you guys feeling about the week ahead? I think we will continue to see stocks and the market move sideways and down a bit longer.  
  
I&amp;#39;m keeping a close eye on news and social sentiment - one of the best trading/investing indicators in this type of market. Check out this social sentiment dashboard with real-time feed of social momentum and market trends. It&amp;#39;s been super useful and helps me stay ahead of big moves.  
  
https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=pw_20220222 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:19:30 </td>
   <td style="text-align:left;"> Respect the downtrend, but don&amp;#39;t fear it, mitigate it with intraday/week scalps and swings.  
 
Today&amp;#39;s wrap sheet with 2 scalps on $AMZN, 2 scalps on $TQQQ, 1 short scalp $VXX, 1 long scalp $TGT and 1 loss. 1 long scalp $AAPL 
 
Never the right time to move to sidelines. You can trade with me folks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:19:25 </td>
   <td style="text-align:left;"> $UVXY $SPY $AAPL $MSFT - While markets fell today... in terms of percentage points, this was nothing big. Until QE ends in March, do not expect a real sell off. In fact, today&amp;#39;s 12PM rally is just all QE manipulation which we commonly call the Plunge Protection Team. A side note, the situation in Ukraine is far more tense than people realize because the issue isn&amp;#39;t about America fighting Russia, but rather Ukrainian military starting skirmishes directly with Russian military armed by the US which would be a spark in dry tinder. The conflict would escalate very fast. But, these recent market sell offs have little to do with Russia as it is with the US economic data which was on average far worse than expected, Fed rate hikes and tapering. I see a bear market starting, than the Fed reversing on their course, cutting rates, doubling on QE... and that my friends will be the beginning of hyper inflation and end the US economy and US dollar. We will see a run on the dollar within 2 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:19:22 </td>
   <td style="text-align:left;"> $SPY $AAPL $BABA Puts Day   
Gains from our Discord.  How you like that?  #whosebanking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:12:49 </td>
   <td style="text-align:left;"> $AAPL It will be interesting to see what the European powers have to say about the sanctions.  You can&amp;#39;t just turn off the Russian Oil supply without causing major inflation problems.  OPEC doesn&amp;#39;t have as much oil and it&amp;#39;s much harder to extract.  They need $80.00 + a barrel to make money.  Russia around $35.00.  Russia is making a ton of money oil under the Xiden Regime. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:11:40 </td>
   <td style="text-align:left;"> $AAPL open 166 is nice start </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:09:40 </td>
   <td style="text-align:left;"> $AAPL if we count AH&amp;#39;s $165, it had a green candle today, as the opening price was 164.98. This is one of those days i wish i wasnt exclusive to options, because 4 am buyers made BANK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:07:46 </td>
   <td style="text-align:left;"> $SPY Just because of the BS MM&amp;#39;s pull... Including the fkn crypto scam... I hope Putin invades overnight.
$QQQ $AAPL $DWAC $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:07:27 </td>
   <td style="text-align:left;"> $AAPL $170 end of week. $180 end of March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:06:06 </td>
   <td style="text-align:left;"> $AAPL 

I am starting to see this market is too tired of Big Bear Bully .. 

It has been almost two months of beating ..

This is time to put to bed .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:04:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $AAPL  A 20% run tomorrow will make up for this 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:04:09 </td>
   <td style="text-align:left;"> $AAPL MM’s should let this one squeeze tomorrow 🙏.  Let us get a nice Green Day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:02:39 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:02:32 </td>
   <td style="text-align:left;"> $SPY future was down a couple hundreds point since Friday! Is normal for it to bounce back a few hundreds point back up too. Watch tomrrow or Thursday it pop , those bought the dip your smart . $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:02:03 </td>
   <td style="text-align:left;"> $AAPL damn, lots of buyers today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:01:16 </td>
   <td style="text-align:left;"> Until there are bombs going off and people dying, this is all just a political stunt.  $SPY $QQQ $SOFI $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:01:15 </td>
   <td style="text-align:left;"> $AAPL run 10 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:00:40 </td>
   <td style="text-align:left;"> $GOOGL $AAPL $KO Only way to handle this market is to invest in the very best companies while they are on sale. https://markets.businessinsider.com/news/stocks/warren-buffett-berkshire-hathaway-blew-it-not-investing-google-stock-2020-1-1028845920 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:00:19 </td>
   <td style="text-align:left;"> $AAPL beautiful finish 👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:00:15 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Why Apple, Appian, and Lemonade Stocks Are Falling Tuesday https://www.stck.pro/news/AAPL/23306077 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 05:00:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 26.38%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:59:57 </td>
   <td style="text-align:left;"> $AAPL watch future bounce tomrrow lmao 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:59:38 </td>
   <td style="text-align:left;"> $AAPL tomrrow we run ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:58:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Once Apple closes below its 50 MA that will be the start of a real bear market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:58:29 </td>
   <td style="text-align:left;"> $AAPL Gotta hand it to Old Joe!  He inspires tremendous confidence!  In Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:58:25 </td>
   <td style="text-align:left;"> $AAPL oversold on 1hr and 4hr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:57:51 </td>
   <td style="text-align:left;"> $AAPL drop continues likely 
Means NASDAQ and Market goes lower 
$QQQ $SPY $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:56:05 </td>
   <td style="text-align:left;"> $AAPL this fucking market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:55:49 </td>
   <td style="text-align:left;"> $TSLA, $FB, $AAPL, $AMZN, $RBLX: Why Are Stocks Down Today? https://investorplace.com/2022/02/tsla-fb-aapl-amzn-rblx-why-are-stocks-down-today/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:55:03 </td>
   <td style="text-align:left;"> $SPY Apple and MSFT charts....all you need to see. Still not near their avg historical correction levels. No bottom till then $aapl $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:54:50 </td>
   <td style="text-align:left;"> $AAPL clear as day, couldn’t hold and a pump and dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:54:04 </td>
   <td style="text-align:left;"> $AAPL gas is 6 bucks in California way to go Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:52:59 </td>
   <td style="text-align:left;"> $DWAC settled for just over $9k on Calls. Puts did amazing this morning too. Add $SPY and $MSFT and I had a $39k day. Awesome!!! Still waiting on $AAPL to get their shit together. Might have to take the L on that one. Have a great weekend everyone ✌️🤑😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:52:56 </td>
   <td style="text-align:left;"> $AAPL Back to today&amp;#39;s  lows in one hour from mini rally. LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:52:20 </td>
   <td style="text-align:left;"> $AAPL Not a good finish so far.  Unfortunately not a good sign moving forward.  I really do like this Regime but I want the stock market to do well.  This is just total manufactured BS.  Sorry Xiden lovers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:52:18 </td>
   <td style="text-align:left;"> $AAPL They took it up and sold these exactly 

11:08am then selling 12:45p

Timing together

Feds Powell and Nancy including </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:51:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL looks like a bull trap bro! hahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:51:42 </td>
   <td style="text-align:left;"> $AAPL 💁 CLEAR WATER.

https://www.clearwaterclw.com/
They are doing everything they can as a new crypto to mark things off the road map. After only 4 days of being live $10,000 was collected and donated! https://www.wtnzfox43.com/story/45889714/clear-water-cryptocurrency-announces-its-official-corporate-support-of-charity-water
 It is now a little over  2 weeks old and has listed on Coingecko. Listing on CMC was applied for and will happen soon . 
This isn&amp;#39;t your ordinary crypto, for they are looking to solve some of our many problems with the lack of clean water provided to location without. As well as starting up a clean water company and provide a better choice then plastic when it comes to bottled water. 

Now, this is a new token and have a very low MC of $350k and circulated supply of 5bil. Everyone involved now is very early, SO DO PLENTY OF RESEARCH AND INVEST AT YOUR OWN RISK. 

THIS ISNT INVESTMENT ADVICE! USE THIS FOR  INFORMATIONAL PURPOSES ONLY. 
$CLEAR.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:50:19 </td>
   <td style="text-align:left;"> $AAPL likely a finish under 164. Sell calls as tomorrow is more uncertainty. Puts are the only guarantee at this point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:48:14 </td>
   <td style="text-align:left;"> $AAPL Sick of this OVERREACTION !!! US and Russia not at war lol ! Let&amp;#39;s move on ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:47:02 </td>
   <td style="text-align:left;"> $AAPL 

https://appleinsider.com/articles/22/02/22/apples-smart-fabric-research-points-to-wearable-tech-beyond-apple-watch-airpods </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:46:56 </td>
   <td style="text-align:left;"> $AAPL break 160 tmr and I&amp;#39;ma buy 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:45:51 </td>
   <td style="text-align:left;"> $AAPL bottom is probably going to fall out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:45:50 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AAPL $RBLX risk on, fuck it risk off. Percocet, molly percocet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:45:48 </td>
   <td style="text-align:left;"> $AAPL 

https://www.macrumors.com/2022/02/22/apple-ar-vr-headset-mass-production-fall/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:44:53 </td>
   <td style="text-align:left;"> $AAPL &amp;quot; Trump is currently praising Russia — the strategic US adversary — saying Putin’s move to annex parts of Ukraine is “genius” as he parrots Kremlin propaganda that the military invasion is peacekeeping.&amp;quot; 
 
Lap it up, Team MAGA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:44:00 </td>
   <td style="text-align:left;"> $AAPL Looks like sell the rip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:43:39 </td>
   <td style="text-align:left;"> $AAPL going down .30 increments in a minute </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:43:10 </td>
   <td style="text-align:left;"> $AAPL 

Fight inflation... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:41:56 </td>
   <td style="text-align:left;"> $AAPL AMERICA!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:41:28 </td>
   <td style="text-align:left;"> $AAPL 20 min left, somehow its still dancing around 165.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:41:19 </td>
   <td style="text-align:left;"> $AAPL how trump would’ve handled Pootin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:39:04 </td>
   <td style="text-align:left;"> $AAPL So too big to fail, waiting for that bailout lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:38:44 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:38:43 </td>
   <td style="text-align:left;"> Top Bearish Flow Today : 

$AAPL $TSLA $HYG $AMD $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:38:41 </td>
   <td style="text-align:left;"> 2/2

AGAIN Some interesting Bernstein charts on latex70b2b7292df6d1ce9c400480e0d3ef2aAMD ↗️

$AAPL $AMZN $INTC $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:38:25 </td>
   <td style="text-align:left;"> Top Bullish Flow Today : 

$AMZN $GOOGL $VIX $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:37:33 </td>
   <td style="text-align:left;"> $AAPL Apples earning report comes out 3-4. I expect a possible spike before then, perhaps a dump right when the market opens at 3-4? Buy the rumor, sell the news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:37:32 </td>
   <td style="text-align:left;"> Some interesting Bernstein charts on $AMD&amp;#39;s PC and server CPU ASP growth over the last few years. 
They upgraded to Outperform this morning.

$AAPL $AMZN $INTC $NVDA 

1/2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:34:24 </td>
   <td style="text-align:left;"> $AAPL Tom Lee about to tell us why markets are going higher on CNBC. $170 by eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:32:26 </td>
   <td style="text-align:left;"> $AAPL seems mm interest to close at 164.50.  Nothing to see here, keep buying that dip and thank you for your service. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:30:17 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (3:30pm)

⦿ $AAPL is up 0.3% in the last 5 mins. 

⦿ There are 22 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 9.1% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:30:03 </td>
   <td style="text-align:left;"> $AAPL Swinging AAPL 175c 3/18 exp toward appl event !! Down this much expect a nice run from these drop toward events ! $SPY .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:29:22 </td>
   <td style="text-align:left;"> $AAPL AH….Green. Biden boy done good for once. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:29:00 </td>
   <td style="text-align:left;"> $AAPL Could jump much higher after hours
***could*** </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:28:25 </td>
   <td style="text-align:left;"> $AAPL I would love a close above 166 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:28:15 </td>
   <td style="text-align:left;"> $AAPL this will be an exciting 30 mins!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:25:24 </td>
   <td style="text-align:left;"> $AAPL The sanctions are much more severe than expected... a good start! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:24:14 </td>
   <td style="text-align:left;"> $AAPL bought 165c on the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:23:26 </td>
   <td style="text-align:left;"> $AAPL you can pump this all you want. Same games all the time. I guess it take little Appl bust to turn around the whole market. But that 200ema will be touched regardless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:22:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Trump&amp;#39;s &amp;#39;Truth Social&amp;#39; is the #1 download on Apple&amp;#39;s app store </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:20:56 </td>
   <td style="text-align:left;"> $AAPL Keep rejecting $165.00 🍆🍆🍆Timmy keep pushing deeper and deeper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:20:07 </td>
   <td style="text-align:left;"> $AAPL will the stock crash because of the Russian invasion? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:19:27 </td>
   <td style="text-align:left;"> $AAPL little weary of this dumping eod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:19:25 </td>
   <td style="text-align:left;"> $AAPL sell the pop Boys. This is going to end with all of that price multiple added on nonsense like a &amp;quot;stock split&amp;quot; being removed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:18:46 </td>
   <td style="text-align:left;"> $AAPL is now 20% of my portfolio.  This just doesn&amp;#39;t loose this much...and when it does, she ROARS back.  172 within 15 trading days...maybe less.  Great opportunity.  Others parts of FAANG are under serious attack! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:17:01 </td>
   <td style="text-align:left;"> $AAPL $NVDA $PYPL Tomorrow could be a big green candle day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:13:52 </td>
   <td style="text-align:left;"> $AAPL 163.90 cancels upper targets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:13:24 </td>
   <td style="text-align:left;"> $AAPL 166.29-166.60 back in play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:13:17 </td>
   <td style="text-align:left;"> $AAPL Shoulda bought roku dkng was thinking to get some calls at open but missed! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:13:00 </td>
   <td style="text-align:left;"> $AAPL 

It’s time we stand up against the big Bad Bear Bully!

Fuck these Bear Bully!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:12:57 </td>
   <td style="text-align:left;"> $AAPL Who&amp;#39;s betting we close close to or above the high of the day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:11:58 </td>
   <td style="text-align:left;"> $AAPL Hope we see greeeeeen soon ! Yapping $$$$$ And tomorrow YAPPIER $$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:11:36 </td>
   <td style="text-align:left;"> $AAPL checkout $SWAV  🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:07:28 </td>
   <td style="text-align:left;"> $AAPL Notsmartatall32 Fred Hopson You blocked me because you said I was a Democrat- and misinterpreted you speak. You are acting like JOE- himself=dementia man- I spoke clearly about the possible risk for disdain for mfg of products in China. Grow up son! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:07:08 </td>
   <td style="text-align:left;"> $SNDL 

It would be smart for $AAPL &amp;amp; $AMZN to join forces to help legalize cannabis. 
Imagine they create their own farms and could ship on Prime!!! Or sell at your Hip Apple Stores!  Sundial may want to connect. Just saying….There is no stopping what the future wants. 

https://www.benzinga.com/markets/cannabis/22/02/25661968/apple-secretly-joined-amazon-in-advancing-commercial-cannabis-reform </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:07:05 </td>
   <td style="text-align:left;"> $AAPL Bye Bye Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:06:49 </td>
   <td style="text-align:left;"> $AAPL got a bad feeling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:06:43 </td>
   <td style="text-align:left;"> $SPY - market is up., b/c sanctions are not as hard as market thought? Lol.. such a 🐶 and 🐴 pony show… 

Thank you for the dip… $GOOG $TSLA $AAPL $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:06:22 </td>
   <td style="text-align:left;"> $SPY $AAPL cant wait for the fall. Mockery of a market, mockery of a president. Weak af. Russia will continue to test as will china. Biden is a wuss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:06:17 </td>
   <td style="text-align:left;"> $AAPL short Russia, not the U.S., Biden, or $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:06:17 </td>
   <td style="text-align:left;"> $GOOGL thank you joe for sanctioning crazy putin  ❤️❤️📈🚀🦍 $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:06:06 </td>
   <td style="text-align:left;"> $RMBL 
👆

STRONG BUY HERE 🚀🚀🚀🚀🚀

 $TSLA  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:05:18 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Russia And Ukraine: What It Means (And Doesn&amp;#39;t) For Your Portfolio https://www.stck.pro/news/AAPL/23305760 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:05:08 </td>
   <td style="text-align:left;"> $AAPL STILL RED 🤡🤡🤡🤡🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:04:44 </td>
   <td style="text-align:left;"> $QQQ $AAPL I ONLY SAVE THIS FOR SPECIAL OCCASIONS https://m.youtube.com/watch?v=9EcjWd-O4jI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:04:28 </td>
   <td style="text-align:left;"> HEADS up $tsla and $aapl lovers 

$aaon about to buck the whole market and come in positive today here 

Load a call for a brother. I&amp;#39;m long the bank on it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:04:01 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Futes and weekend wall street already ripping! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:03:47 </td>
   <td style="text-align:left;"> $AAPL The key is hold all your calls tomorrow for another nice bounce tomorrow $$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:03:24 </td>
   <td style="text-align:left;"> $AAPL Looks like Wall Street likes the sanctions $$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:03:01 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL this looks like it’s going to stick! Woooot! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:02:59 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Best investment money I ever spent.  Sometimes I troll the boards in an incognito window.  Yeeeesh I don&amp;#39;t know how you guys live with those ads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:02:32 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:02:24 </td>
   <td style="text-align:left;"> $NVDA $AAPL I stand with the U.S. and our California behemoths. Pro-Putin and un-American bears should fuck off and invest in RSX and SBRCY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:01:50 </td>
   <td style="text-align:left;"> $AAPL BULLISH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:01:43 </td>
   <td style="text-align:left;"> $SOFI sell this and buy $Tesla and $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:01:02 </td>
   <td style="text-align:left;"> $AAPL Joe could barely could read the short statement.  He messed a critical part of it (the part about Russian armies near Kiev?).  Luckily there wasn&amp;#39;t anything too extreme.  Russia controls oil (not OPEC) so it will be interesting to see how the sanction wars work out.  Russia can produce oil at a much lower cost than OPEC.  Also has more of it.  They could put OPEC out of business.  OPEC needs $80.00 + dollars a barrel.  Russia $30.00 + dollars a gallon.  The Xiden Regime should have never made more dependent on Foreign oil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 04:00:37 </td>
   <td style="text-align:left;"> $AAPL oil down means diminished fear imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:58:37 </td>
   <td style="text-align:left;"> $AAPL well hostage situation in apple store in Amsterdam </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:57:57 </td>
   <td style="text-align:left;"> $AAPL this is a nice intraday bullish advance with volume. Notice how much different than last weeks bullshit pumps? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:57:54 </td>
   <td style="text-align:left;"> $AAPL just sanctions nobody dying no war.... Market will turn green into close and greeeeeeener tomorrow... $$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:57:23 </td>
   <td style="text-align:left;"> $AAPL oil dropping?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:57:05 </td>
   <td style="text-align:left;"> $AMD $AAPL $MSFT $NET If Biden and the EU won&amp;#39;t sanction Russian energy, from a market&amp;#39;s point of view, who cares? Everything rally 
 
Of course, lets hope for minimal loss of human lives </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:56:57 </td>
   <td style="text-align:left;"> $AAPL lets go!!!’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:56:27 </td>
   <td style="text-align:left;"> $AAPL $AMZN $MSFT $QQQ $SPY Green markets in the next 20 minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:55:37 </td>
   <td style="text-align:left;"> $AAPL red to green weenie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:55:23 </td>
   <td style="text-align:left;"> $AAPL Down We Go…..  
                                  …... 
                                          …..  
                                                  …..  
                                                           🤭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:54:54 </td>
   <td style="text-align:left;"> $AAPL biden said fuck the bears.   He’s our man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:54:05 </td>
   <td style="text-align:left;"> $AAPL Russia is tops in Oil.  If that is turned off  by sanctions Oil and Gas prices will really sore.  Russia could put OPEC out of business. They have more Oil and it&amp;#39;s much easier to extract.  Russia can make money at $40.00 a barrel.  OPEC has to be over $80.00 a barrel. The Xiden Regime should have never made us more dependent on foreign Oil. Russia has made a killing on Oil under the Xiden Regime. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:54:01 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $TSLA 🚀🚀🚀🇺🇸🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:53:57 </td>
   <td style="text-align:left;"> $AAPL dam Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:53:14 </td>
   <td style="text-align:left;"> $AAPL   oil dropping, the scouts in oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:52:36 </td>
   <td style="text-align:left;"> $AAPL Timmy  lu   this is a dream come true.. THE prez IS  going to CHIINAA.. LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:52:09 </td>
   <td style="text-align:left;"> $AAPL last hour elevating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:51:42 </td>
   <td style="text-align:left;"> $AAPL 108 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:51:32 </td>
   <td style="text-align:left;"> $AAPL Ponu and the other pro-Putin bears can fuck off as far as I&amp;#39;m concerned. I hope those bitches get taken to the cleaners Bwahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:50:30 </td>
   <td style="text-align:left;"> $AAPL $QQQ TIME FOR A SUPER RAMP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:49:27 </td>
   <td style="text-align:left;"> $SPY $AAPL they will continue to take your money. All the way back down. This will sell off in a big way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:49:05 </td>
   <td style="text-align:left;"> $AAPL yeah bears I would be very worried right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:49:01 </td>
   <td style="text-align:left;"> $AAPL lower!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:48:58 </td>
   <td style="text-align:left;"> $AAPL https://www.dutchnews.nl/news/2022/02/armed-siege-underway-at-amsterdam-apple-store/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:48:39 </td>
   <td style="text-align:left;"> $AAPL he doesn’t care one camels shit about the U.S. people,he just proved it in his lame ass speech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:47:27 </td>
   <td style="text-align:left;"> $AAPL seriously we need to impeach this lose </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:46:44 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Lmaoooooooooo, Biden be like: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:46:11 </td>
   <td style="text-align:left;"> $AAPL Back down we go, not sure why any of yall are optimistic? We are in war times, idiots. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:44:17 </td>
   <td style="text-align:left;"> $AAPL that couldn’t hold 163 for anything. Fell back down like a waterfall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:43:51 </td>
   <td style="text-align:left;"> $AAPL well that was fun while it lasted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:43:18 </td>
   <td style="text-align:left;"> $AAPL Beijing Byden and Timmy Lu are joining forces against RUSSIA. This may not end well..💩💩 $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:42:15 </td>
   <td style="text-align:left;"> $MSFT this is holding the spy from tanking. Interesting to me $AAPL is getting beat up on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:42:13 </td>
   <td style="text-align:left;"> Invest with an outcome based approach on $AAPL. Accelerate gains by 8.6x and make up to 12.2% (33.2% annualized) on $AAPL through 07/15/2022.

Buy 3 $165 calls
Sell 3 $170 calls
Sell 1 $170 put
 7/15/22 expiration
https://o.oliveinvest.com/ruhs04 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:41:50 </td>
   <td style="text-align:left;"> $AAPL ¯\_(ツ)_/¯ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:41:46 </td>
   <td style="text-align:left;"> $SPY US foreign policy is so bad right now 😖 $AAPL $NVDA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:41:05 </td>
   <td style="text-align:left;"> $GOOGL they’re slowing down the drops on google I think we’re about to reverse just need sleepy joe to take crazy Putin and we’ll be good to go $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:39:58 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Huge rally last hour. Markets will close green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:39:56 </td>
   <td style="text-align:left;"> $AAPL TIME TO GROW NOW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:39:21 </td>
   <td style="text-align:left;"> $AAPL Back to open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:39:09 </td>
   <td style="text-align:left;"> $CCL $FB $AAPL $TSLA $MSFT 
 
  It’s going to get worse.  
 3 Russian Nuclear subs just surfaced </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:38:22 </td>
   <td style="text-align:left;"> $AAPL $MSFT Ole Joe did well there. Markets picked up as he spoke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:37:23 </td>
   <td style="text-align:left;"> $AAPL Biden = Lameness personified. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:37:04 </td>
   <td style="text-align:left;"> $AAPL red to green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:36:40 </td>
   <td style="text-align:left;"> $AAPL whats market reaction going to be with biden speech today. Thing worries me is we will defend ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:36:38 </td>
   <td style="text-align:left;"> $AAPL LOVE TRUMP. BUT SLEEPY JO DO A GOD JOB TODAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:36:07 </td>
   <td style="text-align:left;"> $AAPL the US should put into place sanctions that are crushing. I’m talking like N Korean type sanctions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:35:46 </td>
   <td style="text-align:left;"> $AAPL I’m going to go get stoned,fuck this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:35:39 </td>
   <td style="text-align:left;"> $AAPL BIDEN HATES AMERICAN ENERGY…😳😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:35:21 </td>
   <td style="text-align:left;"> $AAPL he was an absolute joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:35:10 </td>
   <td style="text-align:left;"> $AAPL In amsterdam there is a heist going on in one of your stores </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:35:09 </td>
   <td style="text-align:left;"> $AAPL Luckily no questions.  This is total theater and disaster.  Nothing has changed in Ukraine.  Those areas have been independent for a while and never accepted the post 2014 Ukrainian governments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:34:44 </td>
   <td style="text-align:left;"> $AAPL pretty insane that here we are looking at a crisis and Biden seems like a complete idiot. Took 80 minutes to come out to the press and sounded weak and foolish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:34:25 </td>
   <td style="text-align:left;"> $AAPL 

Biden can&amp;#39;t even say Putin&amp;#39;s name right. 🤦‍♂️🤦‍♂️🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:34:24 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:34:16 </td>
   <td style="text-align:left;"> $AAPL biden is such a badass.  Deliver script written for him, run off podium to nap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:33:43 </td>
   <td style="text-align:left;"> $AAPL Welp might as well buy shares unless Apple makes iKillBot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:33:27 </td>
   <td style="text-align:left;"> $AAPL why does Biden quickly leave and lock up like Willy Wonka? Hahahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:33:25 </td>
   <td style="text-align:left;"> $AAPL Biden not sleepy today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:33:22 </td>
   <td style="text-align:left;"> $AAPL that stupid fucker talked for 3 minutes and he was an hour and a half late,wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:32:51 </td>
   <td style="text-align:left;"> $AAPL fuck yes!!!!   Biden got their ass.  😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:32:32 </td>
   <td style="text-align:left;"> Full ChartingOptions Daily #ScanResults from February 4, 2022                      
                      
Identify ETF, Stock, and Crypto Information from our #ScanResults and get a glimpse of the content offered by ChartingOptions exclusive service.                       
                      
Some of the Tickers included:  $AAPL $ZNGA $QCOM $ATVI $XLV  
          
Join the COmmunity at chartingoptions.com/ 
 
https://docs.google.com/document/d/1WFjUauJAsH9OlJSTkqb646-jNepGAev04pQTR4oofHo/edit?usp=sharing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:31:59 </td>
   <td style="text-align:left;"> $AAPL 200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:31:55 </td>
   <td style="text-align:left;"> Rewriting the Rules of #5G with AMD EPYC™ Processor... - $AMD ↗️ Community

$AAPL $AMZN $INTC $NVDA 
How does @AMD #EPYC help communications service providers modernize their platforms to get more performance, more efficiently? Check out the latest blog from AMD CVP, Strategic Business Development Kumaran Siva to discover more:
 https://community.amd.com/t5/business/rewriting-the-rules-of-5g-with-amd-epyc-processors/ba-p/513402?utm_source=twitter&amp;amp;utm_medium=social&amp;amp;utm_campaign=mwc2022&amp;amp;utm_content=kumaranblog&amp;amp;utm_term=q1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:31:48 </td>
   <td style="text-align:left;"> $AAPL Who voted for this 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:31:34 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Its rally time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:31:27 </td>
   <td style="text-align:left;"> $AAPL this pump has volume bears, I’d be worried </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:30:40 </td>
   <td style="text-align:left;"> $AAPL Those areas of Ukraine have been separate for a while.  They support Russia.  They don&amp;#39;t support Ukraine post 2014. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:30:23 </td>
   <td style="text-align:left;"> Long $UVXY calls just got murdered. 

Call 911

$aaon $aapl $tsla $geico </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:30:08 </td>
   <td style="text-align:left;"> $AAPL Seems like a good distraction from Joe’s falling approval numbers. Biden knew this was coming when he stopped our energy independence. But he can’t cover up his weak leadership - which is a joke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:29:29 </td>
   <td style="text-align:left;"> $AAPL why don’t we take care of Putin like we did to Hussein or bin laden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:28:30 </td>
   <td style="text-align:left;"> $aapl are they buying to make this fuck look good?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:27:39 </td>
   <td style="text-align:left;"> $SPY $AAPL $ABNB Brandon&amp;#39;s on the Mic , someone should bushwack him..LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:27:03 </td>
   <td style="text-align:left;"> $AAPL let’s do a squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:26:18 </td>
   <td style="text-align:left;"> $AAPL Sanctions.   That&amp;#39;s it.  I hope so. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:25:49 </td>
   <td style="text-align:left;"> $AAPL LE PUMPE! LFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:25:39 </td>
   <td style="text-align:left;"> $AAPL great time to invade with that stupid fuck we have as a leader </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:25:29 </td>
   <td style="text-align:left;"> $AAPL 

Get him off the air </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:25:21 </td>
   <td style="text-align:left;"> $AAPL this fucking guy can’t even sound tough reading a script. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:25:18 </td>
   <td style="text-align:left;"> FORGET $TSLA OR $AAPL CONE HOME TO MONEY WOTH $AAON COOL BREEZES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:25:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Bridging the Black tech gap https://www.stck.pro/news/AAPL/23304695 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:25:00 </td>
   <td style="text-align:left;"> sentiment check $AAPL $TSLA $HD $XLE $CVX and oil getting sold today... sign of capitulation? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:24:57 </td>
   <td style="text-align:left;"> $AAPL the squirmish will short/     https://www.youtube.com/watch?v=MCKoub_8Y48 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:24:45 </td>
   <td style="text-align:left;"> $AAPL Thought some may find this information useful: https://youtu.be/b8FSRI7qD_8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:24:00 </td>
   <td style="text-align:left;"> $AAPL swinging here, lots of 170+ calls expiring this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-23 03:23:57 </td>
   <td style="text-align:left;"> $AAPL He started.  God Help Us! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:53:40 </td>
   <td style="text-align:left;"> $TSLA Fed will continue to destroy the stock market. Dip buyers think it&amp;#39;ll be like 2020, 2021 all over again. Not a single chance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:52:58 </td>
   <td style="text-align:left;"> $TSLA just quitcha bitchin and buy shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:52:06 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $DWAC $SPY $TSLA orange man bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:51:34 </td>
   <td style="text-align:left;"> $TSLA 

 I will be retaining two lawyers SEC &amp;amp; Stock experts to seek compensation for losses incurred due to SEC retaining 40m settlement for 3 yrs n failing to distribute them to shareholders (large position) in a timely matter during which stock has gained more than 22x if such distribution was available to reinvest at the time of the settlement - SEC failed to protect investors best interest !! 

Just to let @elonmusk know we are fighting back with him against the corrupt government!! 

~ Tesla Shareholders 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:50:55 </td>
   <td style="text-align:left;"> $TSLA next few  weeks this trash will trade over 20% from these levels#cathywoods#contrary indicator, tutes are looking for suckers to unload </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:50:30 </td>
   <td style="text-align:left;"> $DWAC $TSLA $QQQ .. 
 
Account Challenge Update:-  
Start Date: Feb 2, 2022  
Starting Balance: $1,800  
Current Balance: $89,637  
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
   
Watch out for next play👓  https://www.discord.io/xEvE2Aatrp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:49:32 </td>
   <td style="text-align:left;"> $TSLA don’t be fooled, I bought more in 2021 when it dipped after 900 and went down to around 535. I see the same pattern and will load up with only intention now of buy and hold no sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:49:24 </td>
   <td style="text-align:left;"> $TSLA Stocks regroup as investors hold their breath on Ukraine  
 
 
https://www.reuters.com/markets/europe/global-markets-wrapup-1-2022-02-23/ SINGAPORE, Feb 23 (Reuters) - 
 
 
 Asian stocks steadied on Wednesday and demand for safe-havens waned a little as investors regarded Russian troop movements near Ukraine and initial Western sanctions as leaving room to avoid a war, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:49:21 </td>
   <td style="text-align:left;"> $TSLA oh god not another Cathie wood purchase </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:48:22 </td>
   <td style="text-align:left;"> $TSLA $ARKK 

Cathy bought more TSLA lol 🤣🤣🤣, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:47:00 </td>
   <td style="text-align:left;"> Based on estimates for the next 5 years, $TSLA will show a very strong growth in EPS: 26.78% on average per year. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:45:48 </td>
   <td style="text-align:left;"> $TSLA anything under 900 is a gift 💝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:45:25 </td>
   <td style="text-align:left;"> $TSLA  
FXHedge 
@Fxhedgers 
· 
1h 
JAPAN PM KISHIDA: IMPOSES SANCTIONS ON RUSSIA OVER UKRAINE 
 
FREEZES ASSETS OF CERTAIN RUSSIAN INDIVIDUALS 
 
 PROHIBITS RUSSIAN ISSUE OF BONDS IN JAPAN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:45:04 </td>
   <td style="text-align:left;"> $TSLA | Tesla  Inc. $TSLA Proactive Strategies (TSLA) https://tinyurl.com/ybzz93xr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:44:58 </td>
   <td style="text-align:left;"> $TSLA Something just happened within the last thirty minutes because BTC is dumping all of the sudden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:44:22 </td>
   <td style="text-align:left;"> $TSLA 

If you read the entire story, the Germany factory may never get built and it’s all about water. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:42:38 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $DWAC $SPY $TSLA I know it’s wishful thinking. But I hope one day we can get to a point to where we’re not so focused on propaganda, wars, unlimited paper money, politics, etc. We still act so primitive towards one another. When we should be trying to understand one another more and wipe out corruption and evil. 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:42:09 </td>
   <td style="text-align:left;"> $TSLA $BIDU No tesla to be seen. https://pulse2.com/baidu-nasdaq-bidu-bringing-apollo-go-robotaxi-service-to-downtown-shenzhen/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:39:06 </td>
   <td style="text-align:left;"> $SOFI $TSLA $PHUN   All that you need to know;. Shorts haven&amp;#39;t covered a single share:~~~~~~~ Check it out below 👇  
highly recommend everyone to follow them. 🚀     mostwinningchat.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:37:09 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:36:33 </td>
   <td style="text-align:left;"> $AMC all smart apes closing positions and moving to $TSLA according to unconfirmed reports. Go green, go mean </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:36:01 </td>
   <td style="text-align:left;"> $TSLA did you know we can make money and provide clean water for all in need? 

$CLEAR.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:35:52 </td>
   <td style="text-align:left;"> $TSLA Sinks -4.1%. The 25-Feb-22 Option Straddle is Implying a ±3.8% Move in the Next 3 days https://tinyurl.com/yybt77jv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:35:39 </td>
   <td style="text-align:left;"> $TSLA The market will get over this in a few days.   Many people can&amp;#39;t even locate Ukraine on a map anyway. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:34:14 </td>
   <td style="text-align:left;"> $GOOGL $TSLA $SPCE $IPOF Space stocks are going to take off this summer. Google it. SpaceX rulz. https://www.fool.com/investing/general/2016/02/14/why-did-google-invest-1-billion-in-spacex.aspx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:34:07 </td>
   <td style="text-align:left;"> $CLOV i went on some side quests on $SPY and $TSLA but now im back to my back me true love $CLOV. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:32:35 </td>
   <td style="text-align:left;"> $TSLA  
https://www.stocktargetadvisor.com/blog/analysts-rate-tesla-inc-tslansd-with-a-buy-at-960-target/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:32:09 </td>
   <td style="text-align:left;"> $QQQ $SPY $ROKU $TSLA bears out here queefin bruh smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:30:31 </td>
   <td style="text-align:left;"> $tqqq $tsla $aal $wynn $dal  So expect another large drop IF/When some shots are fired.  Won&amp;#39;t last long.  Putin will take Eastern Ukraine quickly and NATO or the USA can&amp;#39;t/wont do shit about it.  Sanctions wont work as Germany and the rest of the European Nato woketards sold their soul to Russian oil/gas and the USA is producing way too little atm bc of Biden&amp;#39;s crack down on US oil production using taxes/regulations and outright bans.  Good news is the market will recover quickly, as no one will give a fuck after a few days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:30:31 </td>
   <td style="text-align:left;"> $TSLA Jim Cramer Move To Value, EARNINGS   https://www.youtube.com/watch?v=_f3YkmhjGdo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:29:53 </td>
   <td style="text-align:left;"> $TSLA More Insider selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:28:33 </td>
   <td style="text-align:left;"> $TSLA $SHOP $FB $NFLX 
heard reporters are tired of Ukraine 2014 old news 😂  
...they wanna talk something else tomorrow... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:28:18 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $DWAC $TSLA $SPY about that peace in the Middle East as well.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:27:30 </td>
   <td style="text-align:left;"> $BTC.X 5x your money with my call outs 💵💯😎👍🔥 $TSLA $FB $MSFT $TQQQ https://youtube.com/shorts/HdyutmsLkr8?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:27:22 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ  https://finance.yahoo.com/news/legendary-investor-jeremy-grantham-sees-121600816.html?guccounter=1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:27:16 </td>
   <td style="text-align:left;"> $TSLA Touched 810/61.80% support level. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:24:57 </td>
   <td style="text-align:left;"> $TSLA buy buy 👋🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:24:27 </td>
   <td style="text-align:left;"> $TSLA &amp;quot;Invasion&amp;quot; of Ukraine,  haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:24:09 </td>
   <td style="text-align:left;"> $TSLA sorry Elon, old man keeps traditional things.  No hi tech, Twitter, chat.. AI.. if you said 70s 80s .. Biden all over it. Hahahna. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:22:32 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $DWAC $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:21:50 </td>
   <td style="text-align:left;"> Tesla Motors&amp;#39;s Chief Financial Officer just disposed of 1,250 shares  https://www.conferencecalltranscripts.com/summary/?id=10480474 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:21:31 </td>
   <td style="text-align:left;"> $TSLA Today was the president day sale! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:19:18 </td>
   <td style="text-align:left;"> $TSLA huge opportunity tomorrow on this if you can buy in the morning! I’m glad to have load up on Option Calls before market closed today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:18:32 </td>
   <td style="text-align:left;"> $TSLA futures ripping.... 870+ mañana. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:17:43 </td>
   <td style="text-align:left;"> $BTC.X 5x your money with my call outs 💯🚀💵⬅️ $SHIB.X $ETH.X $MANA.X $TSLA https://youtube.com/shorts/bAt-L3tQGIk?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:17:42 </td>
   <td style="text-align:left;"> $TSLA people are still hoping for a split. Market is already &amp;quot;splitting&amp;quot; it for you. Or halving rather. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:16:25 </td>
   <td style="text-align:left;"> $TSLA  not rocket science , if you want to make money tomorrow it’s simple , buy Tesla.  
 
It’s oversold , massive 2 day rally incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:15:05 </td>
   <td style="text-align:left;"> $TSLA it’s time! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:10:59 </td>
   <td style="text-align:left;"> $TSLA I can’t wait for Tesla $500 after next split </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:10:42 </td>
   <td style="text-align:left;"> $SPY $TSLA is it a waka waka or what? 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:09:54 </td>
   <td style="text-align:left;"> $TSLA only on peacock-cock-cock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:07:24 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMC $INDO &amp;quot;Shaking off the weak hands&amp;quot; is the most overused phrase on StockTwits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:07:16 </td>
   <td style="text-align:left;"> $TSLA will buy again once it hits 500$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:07:00 </td>
   <td style="text-align:left;"> $TSLA Get ready for a violent rally tomorrow.  
 
When Tesla Moves She Moves !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:06:26 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-20 Largest Trades Data: 
https://www.youtube.com/watch?v=cc74tgjkv9E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:04:09 </td>
   <td style="text-align:left;"> $TSLA Stocktwits: Why This Popular Stock Will Continue to Grow 
 
https://utradea.com/positions/TSLA-Stocktwits-Why-This-Popular-Stock-Will-Continue-to-Grow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:03:11 </td>
   <td style="text-align:left;"> $AAPL i hope its bloody all week $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:01:05 </td>
   <td style="text-align:left;"> We absolutely destroyed $TSLA today with B4-Algo &amp;amp; Full trading system.. Both sides paid VERY well.  💰💰 
 
http://www.b4signals.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 10:00:49 </td>
   <td style="text-align:left;"> $SOFI I feel genuinely bad for the people who sold today. I made a similar mistake selling $TSLA in 2019 and it won’t happen again.

Hopefully this one becomes that once in a decade mistake you don’t make twice. Godspeed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:59:44 </td>
   <td style="text-align:left;"> $TSLA ➕ $AMD ↗️ = #GAMING in car!
Elon Musk: Tesla is working to make Steam video games work in its vehicles - Electrek

“A known chip leaker, Patrick Schur, posted a diagram of Tesla’s new gaming computer powered by the AMD Navi 23 GPU: https://electrek.co/2022/02/22/elon-musk-tesla-working-steam-video-games-work-in-vehicles/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:58:20 </td>
   <td style="text-align:left;"> $SPY $TSLA  saminamina waka waka, it’s time for Africa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:54:44 </td>
   <td style="text-align:left;"> $TSLA who knew this face was our very own @jccoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:54:27 </td>
   <td style="text-align:left;"> $SPY $msft $tsla my TD envelope said “sit before opening “ on the outside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:52:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $SQQQ Problem with traders now is they’re so shortsighted after a 10% drop a 2 % correction happens and they think the market can only go up from there. The trend is your friend not the 1 minute chart. 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:52:13 </td>
   <td style="text-align:left;"> Cathie Wood loads up on Tesla. She purchased 24,366 shares today

$TSLA $ARKK $ARKQ $ARKW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:52:04 </td>
   <td style="text-align:left;"> $TSLA [U-EV] Tesla announced that the production of 4680 cells has reached 1 million, and the 4680 version of Model Y will be delivered in the first quarter of 2022 at the earliest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:49:30 </td>
   <td style="text-align:left;"> $TSLA tesla dont need No stinking oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:48:58 </td>
   <td style="text-align:left;"> $TSLA this is possibly one of the funniest posts I’ve ever seen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:44:37 </td>
   <td style="text-align:left;"> $TSLA  
 
Tesla gets wrist slap from EPA for violating Clean Air Act - What are your thoughts on this? 
 
https://techcrunch.com/2022/02/22/tesla-gets-wrist-slap-from-epa-for-violating-clean-air-act/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:42:12 </td>
   <td style="text-align:left;"> $TSLA $LCID $FSR $GGPI $RIVN 

Those shorting EV are clearly behind the curve of understanding higher gas prices = higher EV demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:42:11 </td>
   <td style="text-align:left;"> $TSLA $TDOC $SPCE $OSTK $NVDA not gonna lie folks, after todays raping, I’m tempted to pick this shit up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:38:33 </td>
   <td style="text-align:left;"> $TSLA futs are reacting to something. However, have not seen any news out of Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:37:08 </td>
   <td style="text-align:left;"> $TSLA any bounce will get sold. Nobody with stable mind enter new positions until rate hikes and this conflict comes to logical conclusion. It just started with sanctions and escalating the situation. $AMZN . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:34:57 </td>
   <td style="text-align:left;"> $TSLA Made over 120k in this garbage on puts this year#junk# keep buying this trash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:34:35 </td>
   <td style="text-align:left;"> $ARKK latexbc7982474e6ddc038d6fe6661065c9acDWAC ss 4pts
$GME Long 1.5pts+

Live S </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:32:30 </td>
   <td style="text-align:left;"> $TSLA how many more splits do you think we will have in the next ten years? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:32:08 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-22 Options Analysis Video: 
https://www.youtube.com/watch?v=mZJ9OeIpTMg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:31:53 </td>
   <td style="text-align:left;"> $TSLA I think the Ruskies have initiated military ops because futs are dumping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:31:47 </td>
   <td style="text-align:left;"> $TSLA Cathie Wood = The new poor man&amp;#39;s Quantitative Easing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:31:04 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:30:58 </td>
   <td style="text-align:left;"> $TSLA open gaps need filled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:30:25 </td>
   <td style="text-align:left;"> $TSLA we going to the moooooon tomorrow!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:29:20 </td>
   <td style="text-align:left;"> $TSLA wow Cathie bought more Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:28:50 </td>
   <td style="text-align:left;"> $TSLA wonder if Elon will have bear barbecue as well as pig? Bears sure have kept me feed since $220 pre split </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:27:32 </td>
   <td style="text-align:left;"> Some of the BIGGEST options trades for today 
$AAPL $TSLA $FB $ROKU $SPY 
https://goldentrading.website/learn-how-to-trade-stocks-and-make-1000-a-day-make-money-while-you-sleep/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:26:20 </td>
   <td style="text-align:left;"> $TSLA those poor bears with Hopeium of breaking even since opening a short pre split 
All bears since October 2021 racking up loses and will never dig out. 
    Only long Bulls win with Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:26:16 </td>
   <td style="text-align:left;"> Arkk adding $TSLA $SHOP $ZM $RBLX PATH ZM SQ SE COIN TWLO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:25:58 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s keep buying this up, great sale. Best etf out there. 700$? Sure, prob won&amp;#39;t see it but definitely wont mind it. If u don&amp;#39;t have love, money won&amp;#39;t fix it. GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:22:47 </td>
   <td style="text-align:left;"> $TSLA    Hey bears and shorts: are you guys coming down to Austin for the GigaTexas GigaOpening GigaBBQ?    You should; you paid for it. heh heh heh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:21:28 </td>
   <td style="text-align:left;"> $SPY $TSLA HK opens comfortably green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:21:05 </td>
   <td style="text-align:left;"> $TSLA lets see $650 please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:20:56 </td>
   <td style="text-align:left;"> $TSLA congrats who bough like me the 802 bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:18:52 </td>
   <td style="text-align:left;"> $TSLA this guy has been a bear forever and some people never learn. This aged well 🤣
Those October puts long lost big. Maybe he got lucky and broke even buying more over $1,100
Life long bears probably lucky to break even </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:17:47 </td>
   <td style="text-align:left;"> $SPY  $QQQ  Futures are green overnight 🎰  
 
FOMC March 16..   
  🎢  🤷🏻 
 
$tsla $sofi $upst </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:16:50 </td>
   <td style="text-align:left;"> $TSLA hedge funds meme with fan base. Not worth more than $200. Eventually market will put this back where it belongs without a split. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:16:18 </td>
   <td style="text-align:left;"> $TSLA  BUY THE DIP ...AND LET RIP !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:14:39 </td>
   <td style="text-align:left;"> $SPY $BTC.X $ETH.X $TSLA $MATIC.X HAVE yall thought what happens once Biden runs out of sanctions in his playbook? What comes next? WWlll? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:13:14 </td>
   <td style="text-align:left;"> $TSLA bug day tomorrow $900 🤔💪🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:13:07 </td>
   <td style="text-align:left;"> $TSLA if oil is going to go through the roof then why is Tesla going down ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:11:27 </td>
   <td style="text-align:left;"> $Amzn $tsla $baba $shop

OTC is getting hot again, $WHSI has 3 monster catalysts, that will catapult this farther than any other OTC in 2021 or 2022.  Uplisting, new device launch and 30 minute segment promoting their new product, hosted by Kathy Ireland— production was already completed 2/8.  This HAS NOT RUN YET. You will not be chasing ta rip at this current SP.  There will be a point of deep regret when you wake up and it’s over 500% from this current SP and didn’t load this current level.  Check Top News Guide article for a great articulation.

https://topnewsguide.com/2022/02/16/wearable-health-solutions-otcmkts-whsi-technical-indicators-point-to-buy/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:07:50 </td>
   <td style="text-align:left;"> $TSLA enough said </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:07:23 </td>
   <td style="text-align:left;"> $UVXY $QQQ $MMAT $SAVA $TSLA My experience here has shown me that just like power or the corrupt and self centered financial system/racket which is a parasite on the economy, the stock market is not a CONTRIBUTOR to the useful economy but rather a PARASITE that feeds off of it and the world would be a better place without it. After all what are equities or options? Just shares of ownership in a company in exchange for $$$ to support its growth/expansion/survival. Or derivatives of it. Or derivatives of whatever the fuck it is of derivatives to the power n of something no one has idea about sometimes too... basically a fucking CASINO.
The same job is done by bank loans or VC capital and those sharks are very adept at pricing the potential of a company. This is why they won&amp;#39;t lend to your cousin George that is a deadbeat, but George can &amp;quot;invent&amp;quot; a company, do a &amp;quot;reverse-merger&amp;quot; listing like a spac and get millions... And still be a deadbeat that will spend all of it on hookers and coke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:04:37 </td>
   <td style="text-align:left;"> $TSLA wake me up at $1,400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:04:27 </td>
   <td style="text-align:left;"> $TSLA no Bueno. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:04:09 </td>
   <td style="text-align:left;"> $TSLA tomorrow is going to be a beautiful day. Ukraine is part of Russia. Putin is not dumb to destroy own country. All this is just fake politics. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:03:25 </td>
   <td style="text-align:left;"> $TSLA tape sped up before $100+ move incoming. Upside that is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:03:14 </td>
   <td style="text-align:left;"> $TSLA Minimum 5-10% move tmr? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:03:02 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-22 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=nJQGq5qXvXM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 09:01:40 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $860.0 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:59:58 </td>
   <td style="text-align:left;"> $SPY $GOOGL $TSLA $QQQ $AMZN For all of you Traitor Trump fans, he would be the ultimate Putin doormat. (He is after all Putin&amp;#39;s c*ckholser.)  Remember this &amp;quot;meeting&amp;quot; with the Russians in the Oval Office no less after Russia interfered in the 2016 election to secure his &amp;quot;win.&amp;quot; Yeah. they must be laughing at how they pulled the wool over the eyes of America: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:58:51 </td>
   <td style="text-align:left;"> $TSLA 930 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:58:38 </td>
   <td style="text-align:left;"> $TSLA  
*Walter Bloomberg 
@DeItaone 
· 
1h 
U.S. SATELLITE IMAGE COMPANY MAXAR SAYS NEW IMAGES SHOW NEW DEPLOYMENT IN BELARUS OF MORE THAN 100 VEHICLES, DOZENS OF TROOP TENTS 
 
MAXAR SAYS IMAGES SHOW HEAVY EQUIPMENT TRANSPORTERS IN WESTERN RUSSIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:57:55 </td>
   <td style="text-align:left;"> $TSLA $BABA $BIDU $AAPL 

Massive stock crash is near … Taiwan will be taken over by air and sea …. No missiles can stop destiny …. The seas and oceans know this , many bodies are about to sink to the bottom of the ocean 🌊 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:56:25 </td>
   <td style="text-align:left;"> $SPY Why do I feel like we are in an episode of family guy with the stock market reacting to every actions by Putin?  Are we americans or russians?  I want to see a new ATH tomorrow! $AMZN $GOOGL $MSFT $TSLA  
https://www.youtube.com/watch?v=CnZUsYcy6L8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:56:04 </td>
   <td style="text-align:left;"> $TSLA https://www.benzinga.com/node/25754907 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:55:53 </td>
   <td style="text-align:left;"> Dark pool after hours activity in 
 
$QQQ - $130M print 
$HYG - $200M print 
$TSLA - $166M print 
$TLT - $211M print 
$WDAY - $141M print 
 
#darkpool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:55:03 </td>
   <td style="text-align:left;"> $TSLA FYI Queen Elizabeth II alive, rumors of her death denied - https://bnonews.com/index.php/2022/02/queen-elizabeth-ii-alive-rumors-of-her-death-denied/ A rumor claiming that Queen Elizabeth II had died went viral on social media on Tuesday night, but a parliamentary official said there was no truth to the report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:53:48 </td>
   <td style="text-align:left;"> $TSLA Elon said wake up Jose.. you keep sleeping at 6. Hahahha.  I CLOCK ⏰️ at 12 said Elon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:52:22 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING!

Elon Musk in email to CNBC: “Biden has pointedly ignored Tesla at every turn and falsely stated to the public that GM leads the electric car industry, when in fact Tesla produced over 300,000 electric vehicles last quarter and GM produced 26.”

Elon Musk in a letter to SEC 
“ SEC is leaking information”

@elonmusk is fighting back!! 🚀

🙏🏻🐉🦅👀
At WAR — as in WAR !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:51:43 </td>
   <td style="text-align:left;"> $TSLA this market won&amp;#39;t be normal until all Tesla Fanboys and their cult leader are left in shambles. It&amp;#39;s the only way to set this market straight. Based on Elon&amp;#39;s recent accusations claiming the SEC is corrupt,  I suspect Musk most likely expects the DOJ may file criminal charges against him. It explains how he is recently attempting to distract his cult followers by claiming the SEC is persecuting him and make himself out to be some kind of martyr. You can&amp;#39;t make this shit up. Would not be the one holding shares when announcement is made. What a clown! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:51:14 </td>
   <td style="text-align:left;"> $AAPL $TSLA $BTC.X  $QQQ Risk management? …..Pshhh, if you aren’t taking out loans for options plays or betting your life savings like a degenerate gambler the. You are just a puss boy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:50:42 </td>
   <td style="text-align:left;"> $TSLA Musk shouldn’t be mad at Biden about paying more attention to the domestic legacy automakers. When the majority of tesla vehicles are bought and made in China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:50:32 </td>
   <td style="text-align:left;"> $TSLA remember last week it was $920 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:50:16 </td>
   <td style="text-align:left;"> $TSLA  Elon said the White House has “nothing to worry about “ he will do the right thing in regards to speaking at an event ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:49:57 </td>
   <td style="text-align:left;"> $TSLA Holders in this market lose daily. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:47:39 </td>
   <td style="text-align:left;"> $TSLA 

https://twitter.com/marketrebels/status/1496285283914076163?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:47:38 </td>
   <td style="text-align:left;"> $amd  $nvda  $spy   $qqq  $TSla  
Advanced Micro Devices upgraded to outperform with a $150 price target at Bernstein 
A Wall Street analyst upgraded Advanced Micro Devices to a buy rating after 10 years on Tuesday, highlighting its growing market share, a strong portfolio of computer chips to rival that of Intel and a relatively cheap stock price. 
 
&amp;quot;This is not the AMD of a decade ago,&amp;quot; Bernstein Research analyst Stacy Rasgon said, lifting the brokerage&amp;#39;s rating on the company to &amp;quot;outperform&amp;quot; — its highest stock rating — from &amp;quot;market-perform&amp;quot;. 
 
https://seekingalpha.com/news/3802395-advanced-micro-devices-upgraded-at-bernstein-firm-sees-30-upside?mailingid=26788713&amp;amp;messageid=2900&amp;amp;serial=26788713.25205&amp;amp;utm_campaign=rta-stock-news&amp;amp;utm_content=link-1&amp;amp;utm_medium=email&amp;amp;utm_source=seeking_alpha&amp;amp;utm_term=26788713.25205 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:46:40 </td>
   <td style="text-align:left;"> $MULN &amp;gt; $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:46:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $TSLA is 7.00. This indicates good health for $TSLA. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:45:55 </td>
   <td style="text-align:left;"> $TSLA so funny today on Tesla Twitter.  The echo chamber Tesla crew fighting amongst each other. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:45:54 </td>
   <td style="text-align:left;"> $TSLA Looking like these MM want to ride this up to kill weekly puts, let&amp;#39;s see what happens tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:45:47 </td>
   <td style="text-align:left;"> $SPY Listen up fools. Tom Lee and Cathie Woods are saying to BTMFD!! BTC to $100,000 and $TSLA to $3000!!! ATH right around the corner!!! 
*Satire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:45:43 </td>
   <td style="text-align:left;"> $MULN &amp;gt; $TSLA fact. I like Mullen style much better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:43:49 </td>
   <td style="text-align:left;"> $TSLA more bagholders tomorrow.  Let&amp;#39;s roll the dice again, Tesla Fancunts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:43:25 </td>
   <td style="text-align:left;"> $TSLA has had such shitty news pieces,nplus Ukraine and Russia.  And still hasn&amp;#39;t tanked the way ud think. Buying the blood is taking place I think </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:42:22 </td>
   <td style="text-align:left;"> $TSLA Elon Musk says the White House “has nothing to worry about” if they invited him to speak at an event😑😑😑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:41:53 </td>
   <td style="text-align:left;"> $TSLA does this mean Elon would cave 

Elon Musk accuses Biden of ignoring Tesla, but says he would ‘do the right thing’ if invited to White House </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:40:20 </td>
   <td style="text-align:left;"> $AAPL Sleepy Joe’s severe sanctions were so punishing on Russia that their stock market rose 6.5% after Sleepy announced them 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣
Sleepy is F embarrassing !!!
$TSLA $AMZN $FB $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:39:06 </td>
   <td style="text-align:left;"> $TSLA block option trades for 3dte are fairly balanced on both sides for directional non-combination plays. Nothing much to speak about </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:38:51 </td>
   <td style="text-align:left;"> $TSLA ohana omaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:38:01 </td>
   <td style="text-align:left;"> $TSLA lol they’re not letting it open below 200ma </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:37:55 </td>
   <td style="text-align:left;"> $TSLA blue 42 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:36:17 </td>
   <td style="text-align:left;"> $TSLA 3:36 am in Moscow.  Putin still asleep.  Check back later tonight his the response.  See you at 1:00am. More puts thqn calls for me. 300k to 100k. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:33:47 </td>
   <td style="text-align:left;"> $TSLA  
Mr. Wonderful Says Tesla Competitor Ford is a BUY and I Agree! $69 Billion Market Cap EV Manufacturer with BB QNX OS! 
 
Everything and more explained in (2/22/22) update video! https://youtu.be/Zv-LomxIq2U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:33:23 </td>
   <td style="text-align:left;"> $TSLA gap still needs to be filled at latexb89e50a2a5602c4a39bf22e0c8138492AMC 
$GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:26:19 </td>
   <td style="text-align:left;"> $HOOD this will be just like latex341502d112438dd4b3e877074b4b4cf9TSLA 
$GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:24:35 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #10 ticker with sweep activity where institutions are trading options urgently with 9.8K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:23:26 </td>
   <td style="text-align:left;"> $TSLA tmrw will be $860 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:22:35 </td>
   <td style="text-align:left;"> $TSLA Don’t look at those chart gaps at 410 and 230. Surely they won’t ever fill 😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:20:21 </td>
   <td style="text-align:left;"> $TSLA tomorrow will be a dead cat.......... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:18:58 </td>
   <td style="text-align:left;"> $TSLA
Still trading within the downtrend channel. Held $805 today. Below $805, we will see $783 (unlikely). On the upside, the resistance lines are $828, $837, $852, $878, $900. 
Crossing above 9 EMA of $878, is a bullish sign that will take us back to $900 and $946.
Happy trading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:18:39 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
Hey MEDIA SHEEPS!...you still consuming mainstream media and using their &amp;quot;war&amp;quot; narrative to explain markets moves? 
 
Stop!...DON&amp;#39;T DO THAT!!! 
 
Only worry about the FED and free money liquidity it provides to the financial markets. Make sure you can answer and explain the following AT MINIMUM. Then you just might have a chance to truly understand and be in sync with what REALLY moves the markets. 
 
Do you know when the FED is scheduled to end QE? 
Do you know the amount of liquidity they are removing from the market each month? 
Do you know when the first rate hike will be? 
Do you know how much the first rate hike will be? 
Do you know how many other rate hikes are priced into the market? 
Do you know how the FED will reduce it&amp;#39;s 9 TRILLION dollar balance sheet this year? 
ETC, ETC, ETC 
 
Don&amp;#39;t be a MEDIA SHEEP!...be a FED SHEEP!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:16:20 </td>
   <td style="text-align:left;"> $TSLA for the uneducated the market was waiting for Biden to speak to turn around. He was late and most sold puts early but great profits and better than holding puts overnight. The market unknown fear is over with Russia and Ukraine. Study history and hope you all took advantage and bought low today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:16:14 </td>
   <td style="text-align:left;"> Will dump a bunch of charts later. Reply to this with the ones you want if you like  
 
$QQQ $AAPL $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:15:58 </td>
   <td style="text-align:left;"> $TSLA .... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:14:43 </td>
   <td style="text-align:left;"> $TSLA F Biden! 

Just seen on the news some parts of the country now paying $5+ for gas. People will be pushed to Tesla, and many will just be screwed because they cannot afford a Tesla or ev car. I didn’t like Trump and what he did in the Middle East but liked him better then this clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:14:24 </td>
   <td style="text-align:left;"> $TSLA BREAKING: The layer of dust accumulated on cars parked within Tesla Austin facility diminished by .25 mm today due to high wind conditions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:10:43 </td>
   <td style="text-align:left;"> $TSLA about the sanctions - I have never heard about these Russian banks before. Probably some money laundering enterprises anyways. Bullish! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:10:12 </td>
   <td style="text-align:left;"> $TSLA we may finally get our +100 point day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:10:05 </td>
   <td style="text-align:left;"> $TSLA You can&amp;#39;t see what they are doing Bulls in after hours?!  Look at the bid spread and fills!  They are going to short this down tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:09:49 </td>
   <td style="text-align:left;"> $TSLA futures are green and VIX is now neutral </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:09:33 </td>
   <td style="text-align:left;"> $TSLA just hit 855 so I can break even lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:09:21 </td>
   <td style="text-align:left;"> $TSLA szechuan chicken feet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:08:36 </td>
   <td style="text-align:left;"> $TSLA kill all the Putin gas... using EV.. hahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:08:24 </td>
   <td style="text-align:left;"> $TSLA recent photo of Elon Musk.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:08:05 </td>
   <td style="text-align:left;"> $TSLA Elon vs. Putin. Hahah. No 👎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:07:29 </td>
   <td style="text-align:left;"> $TSLA those poor puts. Thanks to whoever bought mine I sold today. Puts melting and melting.
Always play opposite of everyone else </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:07:01 </td>
   <td style="text-align:left;"> $TSLA no
War this should be $900 plus tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:06:07 </td>
   <td style="text-align:left;"> $TSLA $SPY  there should be an option to view current holdings and past performance of posters on this app. Would reduce the shit talking from frustrated broke fools and keep the conversations intellectual and inspiring </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:05:59 </td>
   <td style="text-align:left;"> $TSLA we up up from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:04:30 </td>
   <td style="text-align:left;"> $TSLA Can someone tell me ; why on the news of fake war or Russia invasion to Ukraine has anything to do with TSLA 
1) Russia controls oil in that region 
2) Market sell of for EV for what? 
grow up! 
 
Hedge funds are greedy they want this more cheap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:04:19 </td>
   <td style="text-align:left;"> $UPST Some of you should consider how to use capital tax loss strategies with your investments / trading plan(s).  For example:  With this stock I sold a month ago for around this same price - took my hit.  Freed my capital up to invest / trade other stocks.  After 30 days has passed - I have gotten that tax loss secured and now can buy back in.  In this case - I sold for around the same price it is trading now.  In the mean time - I was able to make gains and invest in others - and now get back in to this with a capital loss secured.  If you plan it right - it can make a huge difference in your p/l.   
 
https://www.investopedia.com/articles/stocks/08/capital-losses.asp 
 
$SQ $AAPL $ABNB  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:04:13 </td>
   <td style="text-align:left;"> $TSLA bears should be nervous 😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:04:06 </td>
   <td style="text-align:left;"> $TSLA only bears posting are amateurs and got sucked in to FUD posts today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:04:01 </td>
   <td style="text-align:left;"> Insider Zachary Kirkhorn reports selling 1,250 shares of $TSLA for a total cost of $1,141,575.00 https://fintel.io/n/us/tsla/kirkhorn-zachary?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:03:53 </td>
   <td style="text-align:left;"> $TSLA 900 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:03:50 </td>
   <td style="text-align:left;"> $TSLA 📜 SEC Form 4: Kirkhorn Zachary sold $1,141,575 worth of shares (1,250 units at $913.26) as part of a pre-agreed trading plan, decreasing direct ownership by 2% to 56,084 units

https://quantisnow.com/i/2455524?utm_source=stocktwits

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:03:46 </td>
   <td style="text-align:left;"> $TSLA $GM that&amp;#39;s why Biden loves GM and forgot about tesla https://www.youtube.com/watch?v=PMGEkOIiVp4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:03:36 </td>
   <td style="text-align:left;"> $TSLA [15s. delayed] filed SEC form 4: Chief Financial Officer Kirkhorn Zachary: 
Disposed 1,250 of Common Stock at price $913.26 on 2022- https://s.flashalert.me/dii3FL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:03:23 </td>
   <td style="text-align:left;"> $TSLA 78 pe still too high...800 retest is warranted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 08:02:46 </td>
   <td style="text-align:left;"> latex1a1d876a6c73a640aafbb5e41348e654GME 
$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:59:52 </td>
   <td style="text-align:left;"> $TSLA TA doesn&amp;#39;t matter anymore you permabullllz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:59:20 </td>
   <td style="text-align:left;"> $TSLA bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:59:18 </td>
   <td style="text-align:left;"> $TSLA I hope you shorts bought puts at the close for a ride down to $600. LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:58:58 </td>
   <td style="text-align:left;"> $TSLA Easy lesson for bulls.... NEVER buy a stock who&amp;#39;s shares you can&amp;#39;t short on free brokers. Down to 700s tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:58:15 </td>
   <td style="text-align:left;"> $TSLA I still see too many retail idiots buying dips. The last crop of BTFDers will soon be selling lower like the previous one that stepped in at 950 and 1000. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:58:01 </td>
   <td style="text-align:left;"> $TSLA pop tomorrow then back to $700s? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:57:43 </td>
   <td style="text-align:left;"> $AMZN $Tsla $qqq $spy World War 3 rally has begun!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:56:35 </td>
   <td style="text-align:left;"> $TSLA just got blocked by some other person thinking this stock belongs up here and not at 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:56:25 </td>
   <td style="text-align:left;"> $TSLA where are you little monkey? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:54:48 </td>
   <td style="text-align:left;"> $TSLA I wonder if you know how they live in Texas bro? 
If you don&amp;#39;t work hard and you are rich then you really ought to go to Austin Texas! 
Drift! Drift! Drift! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:53:56 </td>
   <td style="text-align:left;"> $TSLA $TSLAQ getting a slap on the wrist for 3 years of violations of the Clean Air Act.  A whopping $250/day, that&amp;#39;ll show them! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:53:00 </td>
   <td style="text-align:left;"> $TSLA after hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:52:34 </td>
   <td style="text-align:left;"> Stocks Drop On February 22 As Fed Jitters Rattle Investors https://mottcapitalmanagement.com/stocks-on-february-22-as-fed-jitters-rattle-investors/ $TSLA, $AMZN, $TWLO $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:52:33 </td>
   <td style="text-align:left;"> $TSLA there should be an option to filter out bears. All that useless negativity from broke dumbfarks to mess with our zen. 

You short Elon, you short AI/EV and innovation/our future. As an AI scientist, you are then effectively insignificant and useless to me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:52:07 </td>
   <td style="text-align:left;"> $TSLA let’s do $860 tonight 🚀🚀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:52:00 </td>
   <td style="text-align:left;"> $TSLA time for a gap up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:49:09 </td>
   <td style="text-align:left;"> $TSLA 5% by end of the day tomorrow would be awesome </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:49:02 </td>
   <td style="text-align:left;"> $TSLA getting into buy zone for long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:48:20 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA $AAPL $BTC.X Russia, china, and N. Korea all bought the dip! Y’all got swindled by a fake war 🦍🦍🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:48:01 </td>
   <td style="text-align:left;"> $TSLA biggest discount in the Market!  Great leader and an inovative company......GO TIME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:47:56 </td>
   <td style="text-align:left;"> $TSLA arnold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:47:46 </td>
   <td style="text-align:left;"> $TSLA making a gap in AH, means we will go back tomorrow to close it. dont be happy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:47:31 </td>
   <td style="text-align:left;"> $TSLA poots at opening bell!!! Please pump it up some more!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:47:30 </td>
   <td style="text-align:left;"> $TSLA Typical pointless AH rally on no volume that will be sold into tomorrow morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:47:23 </td>
   <td style="text-align:left;"> $TSLA lifter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:47:17 </td>
   <td style="text-align:left;"> $TSLA 900 incoming baby . Bulls all the way . Those who take risk always win . Held thru the blood bath today to make huge gains  this week . 860 tomorrow and 900 by eod! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:47:11 </td>
   <td style="text-align:left;"> $TSLA lifting AH💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:47:01 </td>
   <td style="text-align:left;"> $TSLA lifted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:46:59 </td>
   <td style="text-align:left;"> $SPY $RSX $TSLA $ARKK $TLT the whole Russia-Ukraine pseudo drama is just a pretext for the markets to go one way or another right now, the real driver ultimately will be the draining of liquidity and end of #NIRP #ZIRP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:44:28 </td>
   <td style="text-align:left;"> $TSLA show me 535 in 2 weeks time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:44:11 </td>
   <td style="text-align:left;"> $SPY I really don&amp;#39;t understand what is the point of these &amp;quot;1-2 day relief rallies.&amp;quot; Rip the freaking Band-Aid off so we can get on with it already. 
 
$QQQ $AMD $NVDA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:42:51 </td>
   <td style="text-align:left;"> $TSLA I didn’t sell my $890
Call , good to hold? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:41:26 </td>
   <td style="text-align:left;"> $TSLA this company doesn&amp;#39;t even provide clean air for its employees. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:41:02 </td>
   <td style="text-align:left;"> $TSLA when everyone s looking one way. It’s time to look the other.   Get set 

https://youtu.be/ubgJwd_8h50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:40:48 </td>
   <td style="text-align:left;"> $TSLA Let the panic buying commence </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:39:50 </td>
   <td style="text-align:left;"> $TSLA 
VW Beetle had a 360° trailer hitch at the top of the car in the &amp;#39;70s for a camper
The Cybertruck needs this.

https://vm.tiktok.com/TTPdSYdr4h/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:39:21 </td>
   <td style="text-align:left;"> $TSLA https://www.teslarati.com/tesla-agrees-to-pay-275000-penalty-epa-violation-clean-air-act-settlement/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:39:13 </td>
   <td style="text-align:left;"> $TSLA any positive news and tesla rockets 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:39:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla gets wrist slap from EPA for violating Clean Air Act https://www.stck.pro/news/TSLA/23313068 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:39:06 </td>
   <td style="text-align:left;"> $TSLA  bought more AH .......Ready for my first GREEN DAY as a TESLA investor with my new TESLA family baby! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:38:29 </td>
   <td style="text-align:left;"> $BTC.X $TSLA Zelenskyy of Ukraine when Putin comes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:36:51 </td>
   <td style="text-align:left;"> $TSLA looking so bullishhhhh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:35:44 </td>
   <td style="text-align:left;"> $TSLA loaded more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:35:43 </td>
   <td style="text-align:left;"> $TSLA 2300 zimbabwe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:33:29 </td>
   <td style="text-align:left;"> $TSLA 

Buying the 200SMA even AH has been always my discipline in the Art of Trading! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:32:47 </td>
   <td style="text-align:left;"> $TSLA futes ripping!!!!! Let’s go!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:32:44 </td>
   <td style="text-align:left;"> $TSLA I still believe Ukraine has USSR nukes no matter how many Harvard testimonials the NPR has, one thing more dangerous than a nuke is one you don&amp;#39;t know about. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:30:59 </td>
   <td style="text-align:left;"> $TSLA we will rebound tomorrow and this week, people got way too scared today. Tesla is the greatest company on earth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:28:40 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/QdigJxC6lIE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:28:36 </td>
   <td style="text-align:left;"> $TSLA being generous. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:28:04 </td>
   <td style="text-align:left;"> $TSLA Russia vs NATO Ukraine nukes! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:26:28 </td>
   <td style="text-align:left;"> $TSLA Tesla and EPA reach a settlement after automaker’s Clean Air Act violations

https://www.cnbc.com/2022/02/22/tesla-and-epa-reach-a-settlement-after-clean-air-act-violations.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:26:00 </td>
   <td style="text-align:left;"> $TSLA anyone here thinking $604 is a possibility? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:25:32 </td>
   <td style="text-align:left;"> $TSLA if Tesla goes to 850 tomorrow, I’ll make 240k in profit. Wish me luck people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:24:42 </td>
   <td style="text-align:left;"> $TSLA BTC is soaring right now. ✅️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:22:47 </td>
   <td style="text-align:left;"> $TSLA First time it has been under the 200 EMA on the daily since June 3rd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:21:55 </td>
   <td style="text-align:left;"> $DWAC there will be no $twtr style &amp;quot;fake news&amp;quot; robot farms on truthsocial that is why it is taking so long, everyone is being &amp;quot;vetted&amp;quot; one by one only actual real people are allowed on #truthsocial $tsla waiting on Elon to join....... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:21:12 </td>
   <td style="text-align:left;"> $TSLA can we $1200 again ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:20:25 </td>
   <td style="text-align:left;"> $SHOP $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:19:45 </td>
   <td style="text-align:left;"> $SPY predictions for tomorrow’s open &amp;amp; close? Whoever gets it wrong is gheyy $TSLA $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:19:18 </td>
   <td style="text-align:left;"> $TSLA the rebound will be massive 😆🚀🌙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:18:17 </td>
   <td style="text-align:left;"> $TSLA just like Sunday night.. a little hope and then rug pulled. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:17:35 </td>
   <td style="text-align:left;"> $TSLA Anyone that didn’t sell at 1100 is just a greedy pig. Bulls make money bears make money pigs get slaughtered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:16:56 </td>
   <td style="text-align:left;"> $TSLA https://www.thestreet.com/investing/tesla-has-unearthed-a-new-golden-opportunity Tesla Has Unearthed a New Golden Opportunity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:15:11 </td>
   <td style="text-align:left;"> $TSLA $1000 by Friday, EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:07:56 </td>
   <td style="text-align:left;"> $SPY $TSLA all eyes on China now. We need HSI to be green today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:07:53 </td>
   <td style="text-align:left;"> $TSLA 

Putin puts threat will be met with massive US calls 🚀rendering them total garbage !! 

Standby !! 

🙏🏻🐉🦅😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:07:39 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $TQQQ $SOXL 
Hey 🤡🐻,  Zip it 🤐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:06:30 </td>
   <td style="text-align:left;"> $TSLA If you’re a Bear, Short, or just plain anti-American, keep scrolling.  You really want to send a message to Russia and Putin?  Let’s send the US markets back to ATH 🚀.  Russia could care less about the new sanctions.  I guarantee they were closely watching the US markets today hoping for a huge selloff.  They are using the weakness in the markets from Covid and inflation to their advantage.  STOP doing exactly what they want by selling every little whisper of doom.  Losing this leverage will make a bigger impact than any of these sanctions.  💎 🚀 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:04:55 </td>
   <td style="text-align:left;"> $TSLA did puten buy more Bitcoins🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:04:18 </td>
   <td style="text-align:left;"> $SPY just scheduled my visit for my 11th booster! 🙌🏽💋  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:04:06 </td>
   <td style="text-align:left;"> $TSLA earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:03:08 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 2/22/2022 $SPY $XLF $QQQ $TSLA $MSOS https://www.chartguys.com/daily-market-videos/4143/bears-comfortable-for-now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:02:43 </td>
   <td style="text-align:left;"> $TSLA futures are green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:02:34 </td>
   <td style="text-align:left;"> Unusual Options Activity: $TSLA is the #17 ticker with unusual activity from institutional traders with an average of 24% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:01:57 </td>
   <td style="text-align:left;"> $TSLA by far, the most overhyped colossal piece of shit stock where a portion of its shareholders get hard-ons from the CEO Jabba the Hut, aka Elon, posts random stupid crap on Twitter.  ...just had to get that out. Looking forward to seeing this drop bigly these upcoming months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 07:01:00 </td>
   <td style="text-align:left;"> $TSLA 500 easy by end of march </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:58:47 </td>
   <td style="text-align:left;"> $TDOC looks very close to $TSLA story. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:58:13 </td>
   <td style="text-align:left;"> $TSLA 

🐻 👀 

SWEEP 440 $TSLA 02/25/22 $790 puts for $11.70 

Spot: $819.44
Volume: 8,558
OI: 1,671
IV: 80.10%
Premium: $514.9k 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:58:11 </td>
   <td style="text-align:left;"> $TSLA mooooon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:57:20 </td>
   <td style="text-align:left;"> $TSLA AJ saz its a buy at 1300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:55:22 </td>
   <td style="text-align:left;"> $TSLA stocks are a piece of business and you own a piece of tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:55:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla and EPA reach a settlement after automaker&amp;#39;s Clean Air Act violations https://www.stck.pro/news/TSLA/23311376 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:54:34 </td>
   <td style="text-align:left;"> $TSLA zacks #1 tsla strong buy ! FYI all ! Good luck to all ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:53:27 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow. 
 
https://youtu.be/NlwQg2ZetCc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:50:51 </td>
   <td style="text-align:left;"> $TSLA bulls defended $800 really well,   Looks though like it may want to retest $790’one more time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:49:34 </td>
   <td style="text-align:left;"> $TSLA did it just break the uptrend it’s had since 2020🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:48:28 </td>
   <td style="text-align:left;"> $TSLA https://www.investing.com/news/stock-market-news/futures-slip-in-volatile-trade-as-ukraine-tensions-mount-2769016 correction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:46:19 </td>
   <td style="text-align:left;"> $TSLA looking at the chart it’s a bullish pentagon hexatron 60 day moving average square , futures over 6000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:46:04 </td>
   <td style="text-align:left;"> $TSLA 669 in disslexa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:44:35 </td>
   <td style="text-align:left;"> $TSLA Listen in... Today was as peak as fear gets. Also remember.... Markets are forward thinking and pricing sh1t in as we speak. If you&amp;#39;re short and/or you&amp;#39;re not covering or selling your puts now thinking things will just keep tanking forever, you deserve what&amp;#39;s coming!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:44:00 </td>
   <td style="text-align:left;"> Looking at the last year, $TSLA shows a very strong growth in Revenue. The Revenue has grown by 70.67%. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:43:42 </td>
   <td style="text-align:left;"> $TSLA 1100 paris </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:43:20 </td>
   <td style="text-align:left;"> $TSLA buyers, buyers and more buyers… green tomorrow red Thursday. Plays ready 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:42:01 </td>
   <td style="text-align:left;"> $TSLA added to my position today!! Will keep doing so at these levels! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:41:00 </td>
   <td style="text-align:left;"> $TSLA 880 tomorrow ez pz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:38:01 </td>
   <td style="text-align:left;"> $SPY $TSLA $FB Remember this guy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:37:22 </td>
   <td style="text-align:left;"> $TSLA Bear Flagging </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:30:42 </td>
   <td style="text-align:left;"> latex2579e83ae414eb98a47a2b3b78f407ba. For +1000$ wait 3 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:30:39 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-20 Largest Trades Data: 
https://www.youtube.com/watch?v=cc74tgjkv9E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:29:57 </td>
   <td style="text-align:left;"> Steam games + Tesla 👀👀👀 $TSLA sounds like a job for AMD $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:28:52 </td>
   <td style="text-align:left;"> $TSLA Tesla, prices are quickly back above $1,000. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:28:48 </td>
   <td style="text-align:left;"> $TSLA Too many 🤡s here😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:27:53 </td>
   <td style="text-align:left;"> $TSLA 

                    
                      🌝
                🚀 
             🚀
          🚀 
          🚀
              🚀
                     🚀
                              🚀
                                       🚀 
                                    🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:26:15 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:26:07 </td>
   <td style="text-align:left;"> latex330f0e18a437ab92af83f6471aa23571 this year this stock is going directly back to 400-450$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:25:18 </td>
   <td style="text-align:left;"> $TSLA  glitch on cnbc fast money showing Tesla at 870/share…🤔🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:24:41 </td>
   <td style="text-align:left;"> $DOGE.X $BTC.X $TSLA  tf was this shit 🚨 

✅✅✅🚨random ass website </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:23:55 </td>
   <td style="text-align:left;"> $TSLA tomorrow back to 850 opening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-23 06:23:44 </td>
   <td style="text-align:left;"> $TSLA here is where I’m ready to go long. What war? </td>
  </tr>
</tbody>
</table></div>

---
