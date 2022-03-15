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



Last Updated: 2022-03-15 11:03:48 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/china/unemployment-rate </td>
   <td style="text-align:left;"> 2022-03-15 10:19:00 </td>
   <td style="text-align:left;"> China Jobless Rate Highest in A Year </td>
   <td style="text-align:left;"> China's surveyed urban unemployment increased to 5.5 percent in January-February 2022 combined from 5.1 percent in December 2021, and an increase of 0.2 percentage points from the previous month. This was the highest jobless rate since February of 2021, as the jobless rate of the population aged 16-24 rose to 15.3 percent from 14.3 percent in the previous period. In the meantime, the surveyed unemployment rate in 31 large cities and towns went up to 5.4 percent from 5.1 percent. The average weekly working hours of employees in enterprises across the country declined to 46.7 hours from 47.8 hours in the prior period. From January to February of 2022, 1.63 million new jobs were created in cities and towns across the country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-03-15 10:15:00 </td>
   <td style="text-align:left;"> China Retail Sales Growth Tops Estimates </td>
   <td style="text-align:left;"> China's retail trade rose by 6.7 percent year-on-year in January-February 2022 combined, exceeding market estimates of 3 percent and accelerating sharply from 1.7 percent in the previous period. The latest reading marked the steepest expansion in retail sales since June last year, boosted by robust consumption during the Lunar New Year festival. Sales growth quickened for cosmetics (7% vs 2.5% in December), office supplies (11.1% vs 7.4%), telecoms (4.8% vs 0.3%), and oil products (25.6% vs 15.5%), while there were sharp rebounds in sales of garments (4.8% vs -2.3%), jewelry (19.5% vs -0.2%), home appliances (12.7% vs -6.0%), furniture (-6% vs -3.1%), and automobiles (3.9% vs -7.4%). At the same time, sales continued to grow for both building materials (6.2% vs 7.5%) and personal care(10.7% vs 18.8%). In 2021, retail sales rose 12.5 percent, a sharp rebound from a 3.9 percent drop in 2020, buoyed by sales of consumer goods excluding automobiles and online sales. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/fixed-asset-investment </td>
   <td style="text-align:left;"> 2022-03-15 10:11:05 </td>
   <td style="text-align:left;"> China Fixed Asset Investment Picks Up </td>
   <td style="text-align:left;"> China's fixed-asset investment rose by 12.2 percent year-on-year to CNY 5.08 trillion in January-February  2022 combined, easily beating market forecasts of 5 percent and after a 4.9 percent gain in 2021. Investment accelerated for  both public (14.1 percent vs 2.9 percent  in 2021) and private sectors (11.4 percent vs 7.0 percent). Among sub-industries, investment quickened for both the primary sector (8.8 percent vs 9.1 percent),  the secondary sector (19.6 percent vs 11.3 percent), and the tertiary industry (9.5 percnt vs 2.1 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 10:09:00 </td>
   <td style="text-align:left;"> Japanese Shares Gain as Govt Eyes Curb Lifting </td>
   <td style="text-align:left;"> The Nikkei 225 Index edged up 0.1% to around 25,330 while the broader Topix Index rose 0.7% to 1,825 on Tuesday, driven by gains in consumer-related stocks, as the Japanese government is considering lifting the Covid-19 quasi-state of emergency for 18 prefectures upon expiration next week amid falling cases. Gains in the consumer sector were led by Toyota (1.7%), Nissan (4.2%), Subaru (3.7%), Sony Group (1%), Oriental Land (1%), Snow Peak (9.5%), Asahi Group (3.5%) and Unicharm Corp (5.1%), among others. Elsewhere, a weak overnight session on Wall Street ahead of a key Federal Reserve meeting kept sentiment in check, leading to mixed trading in Japanese technology, financial and manufacturing stocks. Meanwhile, Inpex Corp dropped 7.7% along with other resource-related firms as commodity prices eased amid ongoing Russia-Ukraine peace talks and a coronavirus case surge in China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/03/15/china-russia-taiwan-ukraine-ripley-ebof-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-15 10:04:36 </td>
   <td style="text-align:left;"> Residents of Taipei on edge about China after Russia invades Ukraine - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/industrial-production </td>
   <td style="text-align:left;"> 2022-03-15 10:03:00 </td>
   <td style="text-align:left;"> China Industrial Output Growth Beats Estimates </td>
   <td style="text-align:left;"> China's industrial production rose by 7.5% yoy in January-February 2022 combined, exceeding market consensus of 3.9% and quickening from a 4.3% gain in the prior period. The latest figure came as the recovery in the economy had been better than expected in the first two months of the year, with both manufacturing and mining output accelerating while utilities production grew further. Among manufacturing, production grew faster for chemical raw material and chemical products (4.9% vs 1.2% in December), automobile (7.2% vs 2.8%), general equipment (5.0 percent vs 1.5 percent), agriculture and food processing industry (6.5 percent vs 5.7 percent), communication (12.7 percent vs 12.0 percent), and electricity and heat production and supply industries (6.8 percent vs 7.9 percent), while there was a rebound in output of both textiles (4.9 percent vs -2.4 percent) and non-metal minerals (1.3 percent vs -0.2 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/media/2022/03/15/russia-protester-interrupt-tv-reaction-yakov-kronrod-sot-ac360-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-15 09:46:17 </td>
   <td style="text-align:left;"> American in Moscow reveals how Russians reacted to protester on state TV - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/interest-rate </td>
   <td style="text-align:left;"> 2022-03-15 09:44:00 </td>
   <td style="text-align:left;"> RBA Monitors Factors Affecting Inflation </td>
   <td style="text-align:left;"> The Reserve Bank of Australia stayed prepared to be patient before lifting the cash rate as it keeps an eye of the various factors affecting inflation, minutes of its March meeting showed. The board said it was aware that inflation in Australia has picked up but  it was too early to conclude that it was sustainably within the target band.  "There were uncertainties about how persistent the pick-up in inflation would be given recent developments in global energy markets and ongoing supply-side problems," it added. Members acknowledged that the economic implications of the war in Ukraine depended on the scale and duration of the conflict and the nature of any second-round effects. On the GDP outlook, the Australian economy was expected to pick up further after the Omicron outbreak, supported by household and business balance sheets, a pipeline of construction work to be completed,  an expected recovery in business investment, and macroeconomic policy settings that  remained support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/white-house-tiktok-stars-putin-gas-prices </td>
   <td style="text-align:left;"> 2022-03-15 09:36:12 </td>
   <td style="text-align:left;"> White House drafts TikTok stars to blame Putin for rising gas prices </td>
   <td style="text-align:left;"> House Energy Committee member discusses solutions to high gas prices on 'The Evening Edit.'                                                                                                                                                                                                                                                                                                                                                                                                   , The Biden administration tapped teenage TikTok influencers last week to coordinate messaging on Russia’s invasion of Ukraine and blame Vladimir Putin for rising gas prices, according to a recording of a call between White House officials and the social media stars.                                                                                                                                                                                                                     , Days later, Ellie Zeiler, and 18-year-old with more than 10 million followers on TikTok, posted a video in which she aimed to answer the question, "Why is gas so expensive?"                                                                                                                                                                                                                                                                                                                 , "Why is gas so expensive, and why is the United States inflation rate at a four-time decade high?" she begins the video. "I had the opportunity to ask the White House why gas down the street is $7 and here’s what they said."                                                                                                                                                                                                                                                              , She said the first, "obvious reason," is that demand is going up as the COVID-19 pandemic winds down and people resume traveling.                                                                                                                                                                                                                                                                                                                                                             , "But the call was predominantly about Ukraine and Russia, so how does that relate?" she continued. "Russia is one of the top three producers of oil and it is actually their No. 1 revenue source. Now, with Putin starting this horrific fight between Ukraine and Russia, nobody wants to work with him and do international trade."                                                                                                                                                        , Zeiler was one of 30 TikTok stars to attend a March 10 Zoom meeting with White House officials and National Security Council staffers, the Washington Post reported last week. She posted her video Sunday.                                                                                                                                                                                                                                                                                   , DEMS PUSH PLAN TO TAX OIL COMPANIES' PROFITS, SEND CHECKS TO AMERICANS DURING RUSSIA-UKRAINE PRICE SPIKE                                                                                                                                                                                                                                                                                                                                                                                      , Gen-Z for Change, an organization of influencers involved in the meeting, tweeted Friday that the discussion focused on the U.S. government’s "strategic goals in Ukraine so we’re better able to debunk misinformation."                                                                                                                                                                                                                                                                     , "As a coalition that reaches half a billion people, we are grateful that the White House chooses to work with us to keep people informed," the group continued.                                                                                                                                                                                                                                                                                                                               , The Post also published a 51-minute recording of the call. Rob Flaherty, the White House director of digital strategy, told the TikTokers in the recording that the meeting would be similar to "a background call for reporters" and that he saw their reach as "a critically important avenue" to the American public.                                                                                                                                                                      , Ellie Zeiler, and 18-year-old with more than 10 million follower son TikTok, posted a video in which she aimed to answer the question, "Why is gas so expensive?" (TikTok/Ellie Zeiler)                                                                                                                                                                                                                                                                                                       , White House Press Secretary Jen Psaki also attended. Officials discussed the nuts and bolts of the state of the Russian invasion before delving into a question and answer portion.                                                                                                                                                                                                                                                                                                           , UKRAINE INVASION: ROCKET SLAMS INTO KYIV BUS, VIDEO SHOWS                                                                                                                                                                                                                                                                                                                                                                                                                                     , Zeiler had asked the officials specifically about inflation and what it means for the future of the country and for young people. Psaki fielded the question, attributing the inflation to several factors – supply chain issues, the pandemic and the rising cost of energy, which she initially conceded had begun its climb before Putin’s invasion of Ukraine. But when it came to gas prices, she singled out Putin specifically.                                                        , "It’s his actions, President Putin, that is prompting the rising gas prices," Psaki said in part of her lengthy response. "That is what is happening."                                                                                                                                                                                                                                                                                                                                        , After the meeting, Zeiler explained to the Post her reasoning for attending.                                                                                                                                                                                                                                                                                                                                                                                                                  , White House Press Secretary Jennifer Psaki speaks during the daily briefing in the Brady Briefing Room of the White House in Washington, DC, on January 21, 2022. (Photo by SAUL LOEB/AFP via Getty Images / Getty Images)                                                                                                                                                                                                                                                                    , "I’m here to relay the information in a more digestible manner to my followers," she told the paper. "I would consider myself a White House correspondent for Gen-Z."                                                                                                                                                                                                                                                                                                                         , UKRAINE WAR: DO SANCTIONS WORK? EXPERTS WEIGH IN                                                                                                                                                                                                                                                                                                                                                                                                                                              , Much of the 18-year-old’s other content involves dancing or posing in trendy outfits, and in her most recent video, she prank calls her dad by telling him she got accepted into Harvard.                                                                                                                                                                                                                                                                                                     , The White House’s TikToker meeting comes as Western leaders are struggling to battle the Kremlin’s messaging during Putin’s full-scale invasion of Ukraine, which he claims is a defensive "special military operation" to take out "neo-Nazis" and "drug addicts" who took over the government in Kyiv. Despite a large amount of evidence that Russian missiles and bombs have decimated civilian targets, including hospitals, Putin claims his troops are only attacking military targets., People cross a destroyed bridge as they evacuate the city of Irpin, northwest of Kyiv, during heavy shelling and bombing on March 5, 2022, 10 days after Russia launched a military in vasion on Ukraine. (Photo by ARIS MESSINIS/AFP via Getty Images / Getty Images)                                                                                                                                                                                                                        , Last week, for example, U.S. officials said Russian reports claiming to have found evidence that the U.S. Department of Defense was running laboratories researching biological weapons in Ukraine were "absurd," "preposterous" and amounted to "gaslighting."                                                                                                                                                                                                                               , But Russian state-owned media pointed to congressional testimony from Undersecretary of State for Political Affairs Victoria Nuland last week. She told the Senate Foreign Relations Committee that the U.S. was aware of "biological research facilities" in Ukraine and worried the Russian’s might compromise them.                                                                                                                                                                        , While she didn’t say anything about biological weapons, her response came after Sen. Marco Rubio, R-Florida, asked her whether Ukraine possessed any chemical or biological weapons.                                                                                                                                                                                                                                                                                                          , Last July, Politico reported that Biden was leaning into his two granddaughters, both in their 20s, to help hone his message toward youthful voters.                                                                                                                                                                                                                                                                                                                                          , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                   , "Anything digital he does is purely because his granddaughters tell him to," the outlet’s West Wing Playbook quoted a Democratic source as saying over the summer.                                                                                                                                                                                                                                                                                                                            , The White House did not immediately respond to requests for comment.                                                                                                                                                                                                                                                                                                                                                                                                                          , Fox News' Cameron Cawthorne contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/14/asia/aircraft-carrier-kitty-hawk-scrapping-history-intl-hnk-ml/index.html </td>
   <td style="text-align:left;"> 2022-03-15 09:29:08 </td>
   <td style="text-align:left;"> Kitty Hawk: US aircraft carrier, site of a 1972 race riot at sea, on way to scrapyard - CNN </td>
   <td style="text-align:left;"> Seoul, South Korea (CNN)It was once the biggest symbol of American military power in the Indo-Pacific, battle tested from Vietnam to the Persian Gulf and a survivor of a collision with a Soviet submarine.                                                                                                                                                                                                                                         , But the glory days of the former USS Kitty Hawk are over, and the retired supercarrier is on its final, 16,000-mile journey from Washington state to Texas, where it will be cut up and sold for scrap.                                                                                                                                                                                                                                              , International Shipbreaking Limited of Brownsville, Texas, bought the ship last year for less than a dollar from US Naval Sea Systems Command, which oversees the disposal of retired warships.                                                                                                                                                                                                                                                       , The 1,047-foot long, 252-foot wide carrier is too big to go through the Panama Canal, so in the coming months, Kitty Hawk will creep along the South American coastline and up through the Gulf of Mexico to its final destination.                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Launched in 1960 and named after the North Carolina area where the Wright Brothers first flew a powered airplane, Kitty Hawk served the US Navy for almost 50 years before it was decommissioned in 2009.                                                                                                                                                                                                                                            , Kitty Hawk was the last US aircraft carrier fueled by oil, a relic of an era before the arrival of nuclear-powered Nimitz-class ships.                                                                                                                                                                                                                                                                                                               , Soon, all that will remain is a storied and sometimes tumultuous history that spans the Vietnam War and the bulk of the Cold War, as well as societal upheaval and transformation back home.                                                                                                                                                                                                                                                         , A race riot and the Vietnam experience                                                                                                                                                                                                                                                                                                                                                                                                               , For a decade from the early 1960s, Kitty Hawk was a mainstay of the US force off the coast of Vietnam.                                                                                                                                                                                                                                                                                                                                               , At times, its aircraft flew more than 100 sorties a day over Vietnam from what was called Yankee Station, the area of the South China Sea where US naval vessels steamed to launch strikes against North Vietnamese and Viet Cong forces.                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The ship and its air wing were later awarded a Presidential Unit Citation -- an award honoring extraordinary heroism -- for its actions in Vietnam from December 1967 to June 1968, including supporting US and South Vietnamese forces during North Vietnam's Tet Offensive in the spring of 1968.                                                                                                                                                  , Kitty Hawk saw its last combat over Vietnam in 1972, but during its final mission the carrier became host to what congressional investigators later called "a sad chapter in the history of the Navy."                                                                                                                                                                                                                                               , Race riots erupted on the ship amid rising tensions, after its Vietnam deployment was extended following a port call in the Philippines, according to reports on the Naval History and Heritage Command website.                                                                                                                                                                                                                                     , The accounts of what precipitated the incident vary. Some say it was set off as Black sailors were investigated for a brawl in a Philippine bar the night before the deployment.                                                                                                                                                                                                                                                                     , Others say things snowballed after a Black sailor was denied an extra sandwich in the mess when a White sailor wasn't.                                                                                                                                                                                                                                                                                                                               , Whatever the cause, the violence was substantial.                                                                                                                                                                                                                                                                                                                                                                                                    , "The fighting spread rapidly throughout the ship, with bands of Blacks and Whites marauding through the decks and attacking each other with fists, chains, wrenches, and pipes," David Cortwright, now a director at the Kroc Institute at the University of Notre Dame, wrote in a 1990 article on Black resistance to the Vietnam War.                                                                                                             , The riot and racial tensions aboard the Kitty Hawk were certainly reflective of the stark racial inequality in US society at the time.                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Reports show Black sailors then made up less than 10% of the Kitty Hawk's crew of 4,500. And just five of its 348 officers were Black, according to one report from the Naval History Command.                                                                                                                                                                                                                                                       , A congressional report on the incident the night of October 12-13, 1972, said the brawl left 47 sailors injured, "all but 6 or 7 of them" White.                                                                                                                                                                                                                                                                                                     , And while that congressional investigation led to attempts by the military to address racial inequality, the subcommittee's report itself is littered with prejudicial language revealing just how deep racial bias in the US ran.                                                                                                                                                                                                                   , "The subcommittee is of the position that the riot on Kitty Hawk consisted of unprovoked assaults by a very few men, most of whom were below-average mental capacity, most of whom had been aboard for less than one year, and all of whom were Black. This group, as a whole, acted as 'thugs' which raises doubt as to whether they should ever have been accepted into military service in the first place," read the report's concluding summary.,                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Still, the incident, along with others on Navy ships, prompted the service's leaders to put new emphasis on programs started earlier by Adm. Elmo R. Zumwalt Jr., the then-chief of naval operations, aimed at improving race relations in the fleet.                                                                                                                                                                                                , As of December 31, 2020, Black sailors made up 17.6% of the service's active duty force, according to Navy statistics.                                                                                                                                                                                                                                                                                                                               , Women, the Soviet submarine and an intelligence coup                                                                                                                                                                                                                                                                                                                                                                                                 , Retired Capt. James Fanell said by the time he boarded the Kitty Hawk as an air wing intelligence officer in the '90s, the race riot was long forgotten.                                                                                                                                                                                                                                                                                             , "Most sailors afloat are not historians, so they are looking forward to the next port call or operation," he said.                                                                                                                                                                                                                                                                                                                                   , But in the '90s, another social issue was at the forefront -- the integration of women into the fleet.                                                                                                                                                                                                                                                                                                                                               , Fanell said when he first went to sea in 1987 on another carrier, the USS Coral Sea, there were no women aboard. "A decade later when we deployed on Kitty Hawk, I had eight female squadron and staff intelligence officers working for me -- out of 11 total positions. A pretty dramatic turnaround," he said.                                                                                                                                    , Women now make up more than 20% of the US Navy's active duty force.                                                                                                                                                                                                                                                                                                                                                                                  , In the years between the riot and the integration of women, Kitty Hawk was involved in a tense Cold War encounter with a nuclear-powered Soviet submarine that saw the US carrier come away with a piece of the sub stuck in its hull.                                                                                                                                                                                                               , In March 1984, the Kitty Hawk-led Battle Group Bravo was a focal point of the naval portion of the annual Team Spirit joint exercises with South Korea.                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Operating in open waters about midway between Japan and South Korea, the Kitty Hawk and its escorts had been playing what a Navy officer told the New York Times was a game of "cat and mouse" with the Soviet submarine, later determined to be K-314, a 5,000-ton Victor-class boat with a crew of about 90.                                                                                                                                       , US forces had tracked and "killed" -- or simulated their ability to sink -- the Soviet submarine 15 times in the days leading up to the collision, according to a report from the Naval History and Heritage Command.                                                                                                                                                                                                                                , The carrier group then started practicing "deception techniques" to lose its Soviet tracker, according to a 1989 report on naval accidents titled The Neptune Papers from Greenpeace/Institute for Policy Studies in Washington.                                                                                                                                                                                                                     , It worked to a degree.                                                                                                                                                                                                                                                                                                                                                                                                                               , Just after 10 p.m. on March 21, 1984, in trying to locate the carrier, the K-314 surfaced in its path.                                                                                                                                                                                                                                                                                                                                               , The Russian military website Top War gives the sub's side of what happened next.                                                                                                                                                                                                                                                                                                                                                                     , "The (K-314) commander ordered the start of an urgent dive to avoid a collision. Shortly after the start of the dive, the submarine felt a strong blow. After a few seconds -- a second powerful push. It was clear that the submarine did not have time to go to a safe depth, and it was hit by some of the American ships. As we learned later, it was a Kitty Hawk aircraft carrier."                                                            , The 5,000-ton Soviet sub was no match for the 80,000-ton US carrier is this collision, said Carl Schuster, a former US Navy intelligence officer who saw the Navy's report on the collision.                                                                                                                                                                                                                                                         , "Must have been scary as hell," he said.                                                                                                                                                                                                                                                                                                                                                                                                             , "Everyone on the Kitty Hawk expected the sub to go deep and were hoping to detect it on the other side," he said, noting that a carrier can't detect a sub in close proximity because of the noise of its propellers and the underwater pressure wave it generates.                                                                                                                                                                                  , "Instead, the (sub commander) apparently overestimated his distance from the carrier and didn't start to increase his depth until it was too late. So, he left a portion of one of his screws (propellers) in the carrier's hull," Schuster said.                                                                                                                                                                                                    , K-314 lost power and would later be towed to the Soviet port of Vladivostok.                                                                                                                                                                                                                                                                                                                                                                         , Kitty Hawk continued on under its own power and with a trophy of the Cold War -- that piece of the Soviet sub's screw -- embedded in its hull.                                                                                                                                                                                                                                                                                                       , Also stuck to the carrier's hull were tiles from the Soviet sub's anechoic coating, polymers that enable it to be quieter in the water. Some described this as an intelligence coup for the US military, and the Kitty Hawk crew touted it by temporarily painting a red submarine "victory mark" on the carrier's command center, the US Naval Institute said.                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The later years                                                                                                                                                                                                                                                                                                                                                                                                                                      , Kitty Hawk continued to be a vital part of the US Pacific Fleet for more than two decades after the Soviet submarine collision.                                                                                                                                                                                                                                                                                                                      , In the early 1990s, it would support US military operations in Somalia and act as the launch base for air strikes on Iraq, then ruled by Saddam Hussein.                                                                                                                                                                                                                                                                                             , In the summer of 1998, Kitty Hawk moved to Japan, with its home port at the naval base in Yokosuka, home to the US Navy's 7th Fleet, where it would spend 10 years as the US Navy's only aircraft carrier based outside of the continental United States.                                                                                                                                                                                            , But now there is no home for Kitty Hawk in the US.                                                                                                                                                                                                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                                                                                                      , James Melka, a boilerman on carrier in the '60s, led an effort by the Kitty Hawk Veterans Association to get the ship turned into a museum, like other carriers including the Intrepid in New York, the Midway and Hornet in California, the Yorktown in South Carolina, and the Hornet in Texas.                                                                                                                                                    , But the Navy rejected the idea in 2018, according to a report from United States Naval Institute (USNI) News.                                                                                                                                                                                                                                                                                                                                        , "Nobody's gonna know ... what a Kitty Hawk-class aircraft carrier was," Melka told USNI. "They'll just see pictures. They won't be able to see the actual ship and be able to walk on it."                                                                                                                                                                                                                                                           , Fanell said memories of the carrier will be kept alive by the hundreds of thousands of sailors who served on its decks.                                                                                                                                                                                                                                                                                                                              , "And I am just one sailor," he said. "Think of all the lives she touched and the memories created."                                                                                                                                                                                                                                                                                                                                                  , When the aircraft carrier's fate was sealed, Fanell sent a note to his former shipmates to remind them of their time together and what was about to be lost.                                                                                                                                                                                                                                                                                         , "(It's) really sad in a way to think of all those memories losing the one thing that linked us all together ... the USS Kitty Hawk," he wrote.                                                                                                                                                                                                                                                                                                       , "Life goes on and our memories fade away, just a bit faster when our ships are cut up for razor blades."                                                                                                                                                                                                                                                                                                                                             , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 09:22:27 </td>
   <td style="text-align:left;"> ASX Declines as Commodity, Tech Stocks Drag </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index fell 0.6% to around 7,100 on Tuesday, as Australian miners and energy firms dropped on easing commodity prices driven by the ongoing Russia-Ukraine peace talks and a coronavirus case surge in China. Prices of major Australian exports from iron ore, oil, copper to gold slumped overnight, dragging shares of firms including BHP Group (-3.8%), Fortescue Metals (-5.1%), Rio Tinto (-4%), Woodside Petroleum (-3%), Santos Ltd (-3.7%), OZ Minerals (-3.4%), Newcrest Mining (-1.9%) and Northern Star Resources (-2%). Australian technology stocks also tracked overnight weakness on the Nasdaq as investors braced for the upcoming Federal Reserve rate hike, with losses from Wisetech Global (-2.3%), Brainchip Holdings (-4%) and Nextdc ltd (-1.9%). Meanwhile, financial stocks resisted the negative trend amid rising global bond yields, with the “Big Four” banks each gaining more than 1%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/uks-boris-johnson-meets-oil-industry-leaders-discuss-energy-independence-amid-russia-ukraine-war </td>
   <td style="text-align:left;"> 2022-03-15 09:20:20 </td>
   <td style="text-align:left;"> UK’s Boris Johnson meets with oil industry leaders to discuss energy independence amid Russia-Ukraine war </td>
   <td style="text-align:left;"> TrustedSec founder and CEO Dave Kennedy provides insight on possible cyber warfare amid the Russia-Ukraine conflict on 'Kennedy.'                                                                                                                                                                                                                                 , British Prime Minister Boris Johnson met with oil and gas industry leaders on Monday to discuss his country’s energy security as it looks to move away from Russian hydrocarbons following Russian President Vladimir Putin’s invasion of Ukraine.                                                                                                                , Boris said the oil and gas industry has an important part to play in producing the energy needed to move away from Russian hydrocarbons and transition to sustainable energy.                                                                                                                                                                                     , "We’ll continue to back them in building up our domestic energy security, where neither the U.K. nor our allies can be blackmailed by the likes of Putin, and in accelerating some of the solutions we need to reach net-zero, from low-carbon hydrogen to carbon capture and storage," Johnson said.                                                             , At the roundtable meeting, Johnson and CEOs discussed increasing investment in the North Sea oil and gas industry and boosting the supply of domestic gas. Proposals included ways the U.K. can remove barriers facing investors and developers and help projects come online more quickly.                                                                       , DEMS PUSH PLAN TO TAX OIL COMPANIES' PROFITS, SEND CHECKS TO AMERICANS DURING RUSSIA-UKRAINE PRICE SPIKE                                                                                                                                                                                                                                                          , The U.K. said last week it would phase out oil imports from Russia, which account for around 8% of the country’s oil supply. The U.K.’s European allies are anticipated to have a tougher time weening themselves off Russia’s oil, given their great reliance on imports.                                                                                        , Britain's Prime Minister Boris Johnson leaves after the Commonwealth Service on Commonwealth Day at Westminster Abbey in London, Monday March 14, 2022.  (Yui Mok/PA via AP)                                                                                                                                                                                      , Monday’s roundtable meeting comes as other nations have been scrambled to overhaul their energy policies amid the war in Ukraine that has sent oil prices surging.                                                                                                                                                                                                , FILE: A general view shows an oil treatment plant in the Yarakta Oil Field, owned by Irkutsk Oil Company (INK), in Irkutsk Region, Russia March 10, 2019.  (REUTERS/Vasily Fedosenko)                                                                                                                                                                             , The Biden administration, meanwhile, has been slowly attempting to mend fences with traditional U.S. adversaries like Venezuela while forging ahead with green initiatives in the U.S.                                                                                                                                                                            , Speaking at a fundraiser focused on climate Monday night, Biden said the Russia-Ukraine war was "another reason why we have to get off our dependency on fossil fuels."                                                                                                                                                                                           , CLICK HERE TO READ MORE FROM FOX BUSINESS                                                                                                                                                                                                                                                                                                                         , "Imagine where we’d be right now if in fact, Europe was in fact energy free of fossil fuels," the president said.                                                                                                                                                                                                                                                 , Biden has been blaming Putin's invasion of Ukraine for high gas prices Americans are suffering, but prices had been rising for a year prior to that invasion. He authorized the release of 50 million barrels of oil from the National Strategic Reserve in November 2021 in an attempt to alleviate increasing gas prices, months before Russia invaded Ukraine. , He has yet to meet with American energy industry leaders despite suggesting that they, too, are to blame for surging pain at the pump.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/currency </td>
   <td style="text-align:left;"> 2022-03-15 09:18:38 </td>
   <td style="text-align:left;"> Chinese Yuan traded above 6.4 </td>
   <td style="text-align:left;"> The US Dollar exchange rate rose above 6.4 Chinese Yuan in the foreign exchange interbank market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/oil-falls-over-5-on-russia-ukraine-talk-hopes-china-lockdowns </td>
   <td style="text-align:left;"> 2022-03-15 09:15:15 </td>
   <td style="text-align:left;"> Oil falls over 5% on Russia-Ukraine talk hopes, China lockdowns </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines for March 14.                                                                                                                                                                                                                                                                                                             , NEW YORK - Oil prices fell more than 5% on Monday to the lowest in nearly two weeks amid hopes for progress toward a diplomatic end to Russia's invasion of Ukraine - a development that would boost global supplies - while a pandemic-linked travel ban in China cast doubt on demand.                                                                                 , Brent futures fell $5.77, or 5.1%, to settle at $106.90 a barrel, while U.S. West Texas Intermediate (WTI) crude fell $6.32, or 5.8%, to settle at $103.01.                                                                                                                                                                                                              , That was the lowest close for WTI since Feb. 28 and the lowest for Brent since March 1. Both benchmarks have surged since Russia's Feb. 24 invasion of Ukraine and are up roughly 36% so far this year.                                                                                                                                                                  , DEMS PUSH PLAN TO TAX OIL COMPANIES' PROFITS, SEND CHECKS TO AMERICANS DURING RUSSIA-UKRAINE PRICE SPIKE                                                                                                                                                                                                                                                                 , "Oil prices are reflecting a bearish sentiment drawn from expectations of positive developments in the latest round of Russia-Ukraine negotiations," said Kaushal Ramesh, an analyst at energy research provider Rystad Energy.                                                                                                                                          , Russian and Ukrainian delegations held a fourth round of talks on Monday - by video link rather than in person in neighboring Belarus as in the past - but no new progress was announced. Ukraine said it held the talks with Russia on a ceasefire, immediate withdrawal of troops and security guarantees despite the fatal shelling of a residential building in Kyiv., Oil prices fell more than 5% on Monday to the lowest in nearly two weeks amid hopes for progress toward a diplomatic end to Russia's invasion of Ukraine - a development that would boost global supplies - while a pandemic-linked travel ban in China ca                                                                                                               , Brent and WTI have logged their most volatile 30 days since June 2020.                                                                                                                                                                                                                                                                                                   , Analysts at energy consulting group EBW Analytics noted that "a renewed COVID outbreak in China is leading to rising shutdowns as Omicron spreads rapidly," which could reduce global energy demand since China is the world's largest importer of oil, liquefied natural gas and coal.                                                                                  , A northeastern Chinese province imposed a rare travel ban due to an Omicron outbreak.                                                                                                                                                                                                                                                                                    , Russia's output of oil and gas condensate rose to 11.12 million barrels per day (bpd) so far in March, two sources familiar with production data told Reuters, despite sanctions.                                                                                                                                                                                        , The United States has banned Russian oil imports and Britain said it would phase them out by the end of 2022. Russia is the world's top exporter of crude and oil products combined, shipping about 7 million bpd or 7% of global supplies.                                                                                                                              , HOW CAN GAS PRICES COME DOWN? THE FEDERAL GOVERNMENT AND STATES COULD HELP EASE PAIN AT THE PUMP                                                                                                                                                                                                                                                                         , A senior minister said British Prime Minister Boris Johnson was trying to persuade Saudi Arabia to boost oil output, while International Energy Agency (IEA) chief Fatih Birol urged oil-producing countries to pump more.                                                                                                                                               , European Union member states have agreed on a fourth package of sanctions against Russia, the office of the French EU presidency wrote on Twitter. It did not include Russian energy exports.                                                                                                                                                                            , "Energy traders quickly abandoned the crude trade after the next round of EU sanctions spared oil from Russian companies," said Edward Moya, senior market analyst at data and analytics firm OANDA.                                                                                                                                                                     , India indicated it could release more oil from national stocks.                                                                                                                                                                                                                                                                                                          , Indian officials also said New Delhi was considering a Russian offer to buy crude and other commodities at discounted prices via a rupee-rouble transaction.                                                                                                                                                                                                             , The United States has banned Russian oil imports and Britain said it would phase them out by the end of 2022. Russia is the world's top exporter of crude and oil products combined, shipping about 7 million bpd or 7% of global supplies. (REUTERS/Christian Hartmann)                                                                                                 , The United States needs to make a decision to wrap up a deal to salvage Iran's 2015 nuclear accord with world powers, the Iranian foreign ministry spokesperson said. Some feared talks might collapse, and 49 of 50 Republican U.S. senators said they would not back a new nuclear deal.                                                                               , Analysts said an agreement with Iran could add another 1 million bpd of oil supply to the market, but noted that would not be enough to offset declining supply from Russia.                                                                                                                                                                                             , The U.S. Federal Reserve is expected to start raising interest rates this week, which should boost the dollar. This could push down oil prices by making dollar-denominated oil more expensive for holders of foreign currencies.                                                                                                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                              , Crude stockpiles at the Cushing storage hub in Oklahoma rose last week for the first time this year, traders said, referring to a report from data provider Genscape. U.S. government data has shown stockpiles there falling for nine weeks in a row. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60745707?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-15 08:59:32 </td>
   <td style="text-align:left;"> Chip giant Arm set to axe 15% of its staff after deal fails </td>
   <td style="text-align:left;"> UK computer chip designer Arm Holdings has said it plans to cut up to 15% of its workforce.                                                                                                                                            , The redundancies have emerged just a month after the collapse of the firm's $40bn sale to US chipmaker Nvidia.                                                                                                                         , If the proposals go ahead most job losses would be in the UK and the US, the Cambridge-based company said.                                                                                                                             , Arm's chip designs are licensed to brands including Apple and Samsung and are used in most smart phones and other  products around the world.                                                                                          , Arm employs close to 6,400 people worldwide. The company said in a statement: "Like any business, Arm is continually reviewing its business plan to ensure the company has the right balance between opportunities and cost discipline., "Unfortunately, this process includes proposed redundancies across Arm's global workforce."                                                                                                                                            , Millions of technology products rely on computer chips but there are not enough currently being produced to meet demand.                                                                                                               , As sales of devices soared during the pandemic, stocks of chips plunged which has left manufacturers struggling to keep up with demand.                                                                                                , Arm's owner Softbank - the Japanese conglomerate which bought the UK company in 2016 for $32bn - had planned to sell the firm to Nvidia for $40bn.                                                                                     , However, last month SoftBank shelved the sale citing regulatory hurdles and said it would instead seek to list the company.                                                                                                            , In the blow to the UK, Softbank said its would list Arm on the Nasdaq stock exchange in the US.                                                                                                                                        , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                 , Cat Deeley and Edith Bowman are best friends - here is their story                                                                                                                                                                     , A failing witchfinder and his suspect find themselves on a hellish road trip...                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/chinese-stocks-plunge-covid-19-beijing-moscow-relationship </td>
   <td style="text-align:left;"> 2022-03-15 08:58:32 </td>
   <td style="text-align:left;"> Chinese stocks plunge on COVID-19 fears, concerns over Beijing and Moscow's relationship </td>
   <td style="text-align:left;"> Former Trump foreign policy adviser Walid Phares discusses Russia asking China for military and economic support.                                                                                                                                                                                                                                                     , Chinese stocks took a dive on Monday as the country combats its worst COVID-19 outbreak in two years and concerns grow over Beijing's close relationship with Moscow.                                                                                                                                                                                                 , The Hang Seng China Enterprises Index in Hong Kong closed down 7.15%, while the CSI 300 Index in Shanghai fell 3.01%.                                                                                                                                                                                                                                                 , Chinese stocks listed in the U.S. also spiraled. Alibaba fell 10.32%, JD.com closed down 10.52%, and Baidu dove 8.37%.                                                                                                                                                                                                                                                , Residents line up at a makeshift nucleic acid testing site during a mass testing for COVID-19 in Chaoyang district of Beijing, China March 14, 2022.  (REUTERS/Tingshu Wang)                                                                                                                                                                                          , China is dealing with its worst COVID-19 outbreak since the beginning of the pandemic. On Sunday, officials locked down Shenzen, a southern city of about 17.5 million near Hong Kong that serves as a vital tech and finance hub.                                                                                                                                    , CHINA'S NEW COVID LOCKDOWN HITS APPLE SUPPLIER, RAISING RISK OF HIGHER INFLATION                                                                                                                                                                                                                                                                                      , Changchun, a city of about nine million in northeastern China, went into lockdown on Friday.                                                                                                                                                                                                                                                                          , Beijing and Shanghai were also shutting down offices and residential areas where some COVID-19 cases cropped up.                                                                                                                                                                                                                                                      , Russia's President Vladimir Putin and his Chinese counterpart Xi Jinping pose during a meeting. (Alexei Druzhinin\TASS via Getty Images)                                                                                                                                                                                                                             , There are also fresh concerns about Beijing's cozy relationship with Moscow after reports came out Sunday that Russia has requested military assistance from China since Putin's invasion of Ukraine on Feb. 24.                                                                                                                                                      , "The national security adviser and our delegation raised directly and very clearly our concerns about the PRC’s support to Russia in the wake of the invasion, and the implications that any such support would have for the PRC’s relationship not only with us, but for its relationships around the world," State Department spokesman Ned Price warned on Monday. , A building damaged by shelling is lit by the sunset in Kharkiv, Ukraine, Friday, March 11, 2022.  (AP Photo/Andrew Marienko)                                                                                                                                                                                                                                          , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                               , China and Russia have both denied the reports, but White House National Security Adviser Jake Sullivan and senior Chinese foreign policy adviser Yang Jiechi met in Rome on Monday so that the U.S. could "convey very clearly our concerns," Price said.                                                                                                             , Russia has been hit by unprecedented sanctions and hundreds of major Western companies have fled the country after Putin invaded Ukraine.                                                                                                                                                                                                                             , The Associated Press contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/house-price-index-mom </td>
   <td style="text-align:left;"> 2022-03-15 08:52:00 </td>
   <td style="text-align:left;"> Australia Q4 Property Prices Rise More than Estimated </td>
   <td style="text-align:left;"> The Residential Property Price Index in Australia rose by 4.7 percent qoq in Q4 2021, above market consensus of 3.9 percent and after a 5.0 percent growth in Q3. This was the sixth straight quarter of growth in property prices, supported by record-low interest rates and strong demand.  The strongest quarterly price increases were recorded in Brisbane (9.6 percent), followed by Adelaide (6.8 percent), Hobart (6.5 percent), and Canberra (6.4 percent). Through the year to Q4, the index jumped to a record high of 23.7 percent, with Hobart, Canberra, Brisbane, Sydney, and Adelaide having the largest annual rise since the commencement of the series; while Melbourne had the largest annual rise since Q2 2010. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 08:43:47 </td>
   <td style="text-align:left;"> US Futures Rise Ahead of Key Fed Meeting </td>
   <td style="text-align:left;"> US stock futures rose slightly in Asian trade on Tuesday after a lackluster session on Wall Street, as investors braced for a key Federal Reserve policy decision and continued tracking developments  in Ukraine. Dow futures inched up 0.1%, S&amp;P 500 futures gained 0.2% and Nasdaq 100 futures advanced 0.4%. In regular trading on Monday, the Dow erased a 450 point gain to end flat, while the S&amp;P 500 and Nasdaq Composite fell 0.74% and 2.04%, respectively. The Fed is set to start a two-day policy meeting on Tuesday where it is widely expected to raise interest rates by 25 basis points to tame multi-decade high inflation. Investors will also be watching for adjustments to the economic outlook, the path of rates and the likely schedule of asset tapering given added uncertainty from the Russia-Ukraine war. Elsewhere, a lockdown in the Chinese city of Shenzhen also dampened sentiment, as production for major companies were halted in the key manufacturing and tech hub. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/treasury-yields-3-15-22 </td>
   <td style="text-align:left;"> 2022-03-15 08:34:13 </td>
   <td style="text-align:left;"> Treasury yields rebound to new multiyear highs </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines for March 14.                                                                                                                                                                                                                                                                                                     , Yields on U.S. government bonds have surged back to their highest levels since 2019, reflecting investors’ growing bets that Russia’s invasion of Ukraine won’t slow the momentum toward higher interest rates.                                                                                                                                                  , The yield on the benchmark 10-year U.S. Treasury note settled at 2.139%, up from 2.004% Friday and its highest close since June 2019.                                                                                                                                                                                                                            , Yields, which rise when bond prices fall, had climbed sharply over the first six weeks of the year as investors ratcheted up their expectations for interest-rate increases from the Federal Reserve. They then fell—with the 10-year yield settling as low as 1.722%—as Russia’s invasion sent cash flowing into safer assets.                                  , INVESTORS START BUYING UKRAINE, RUSSIA BONDS                                                                                                                                                                                                                                                                                                                     , But yields have rebounded over the past week, with investors increasingly nervous that the isolation of Russia will add to inflation by boosting commodity prices.                                                                                                                                                                                               , It is hard to say that recent developments "are not inflationary, given where commodity prices are," said Leah Traub, a portfolio manager at Lord Abbett.                                                                                                                                                                                                        , The Federal Reserve Building in downtown Washington DC, USA at night. HDR image. (iStock / iStock)                                                                                                                                                                                                                                                               , While some have thought that higher commodity prices could slow economic growth and therefore make the Fed cautious about raising interest rates, "our view is, that for the U.S., that the inflation impact will be higher than any negative impacts from growth," she said.                                                                                    , Highlighting the complexity of the current situation, Monday’s increase in yields came as hopes for negotiated settlement between Russia and Ukraine helped drive down oil prices. That was a sign that for many investors, a decline in commodities prices would still make it easier for the Fed to raise rates.                                               , Investors will gain further insight into the Fed’s thinking in a matter of days. The central bank is widely expected to raise short-term rates by a quarter of a percentage point on Wednesday. But it will also release its latest economic forecast and its so-called dot plot showing where individual officials expect rates to head over the next few years., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                      , As of Monday, interest-rate derivatives showed that traders think there is a nearly 70% chance that the Fed will raise rates to at least 1.75% this year, according to CME Group data—up from 31% a week ago and a return to roughly the same position from a month ago. The Fed’s current target for its benchmark rate is between 0% and 0.25%.                , Investors, though, are expecting the Fed to sharply slow down the pace of its rate increases next year, leaving short-term rates between around 2% and 2.5%. That is roughly the same peak they reached in the previous economic expansion.                                                                                                                      , Rising bond yields are likely to be disappointing to many investors, pushing up borrowing costs across the economy and giving investors few places to hide if they are nervous about holding riskier assets such as stocks.                                                                                                                                      , US treasury department sign in Washington, DC building facade (iStock / iStock)                                                                                                                                                                                                                                                                                  , This year has been particularly difficult because prices of both stocks and bonds have fallen, making it difficult for savers to earn positive returns regardless of their investment strategy.                                                                                                                                                                  , Of concern for investors, yields climbed Monday on Treasury inflation-protected securities, or TIPS, even more than they did on ordinary U.S. Treasurys, a development that often has a negative impact on stock prices.                                                                                                                                         , The yield on the 10-year Treasury inflation-protected security stood at minus 0.821% Monday afternoon, up from minus 0.978% Friday.                                                                                                                                                                                                                              , Investors pay close attention to TIPS yields because they are a proxy for real, or inflation-adjusted, bond yields, making them arguably a better measure of benchmark borrowing costs than nominal yields.                                                                                                                                                      , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                          , Echoing a pattern from earlier in the year, Monday’s increase in yields corresponded with a simultaneous decline in stocks valued largely for their future earnings potential, such as those in the technology sector. The ability to get higher risk-free returns from bonds generally makes such companies less appealing to investors.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/03/14/finland-president-sauli-niinisto-putin-talk-amanpour-intv-intl-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-15 08:11:03 </td>
   <td style="text-align:left;"> Finnish President: Putin's goal in Ukraine is not regime change - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/14/europe/ukraine-surrogate-babies-shelter-intl-cmd/index.html </td>
   <td style="text-align:left;"> 2022-03-15 07:55:10 </td>
   <td style="text-align:left;"> Underneath embattled Kyiv, surrogate babies of foreign parents shelter in a basement - CNN </td>
   <td style="text-align:left;"> Kyiv, Ukraine (CNN)The thunder of explosions occasionally rattles the basement that has become the temporary home to 21 babies of foreign parents born to Ukrainian surrogates.                                                                                                                                                                                                                 , The BioTexCom Center for Human Reproduction surrogacy center in Kyiv was moved to the concrete bunker on the first day of the Russian invasion nearly three weeks ago, to protect the babies from any incoming fire.                                                                                                                                                                            , But located just over nine miles from Irpin, a suburb that has been a target of a Russian onslaught, it is still far from safe -- making it difficult for the new parents, who are in countries such as Canada, Italy and China, to collect the babies.                                                                                                                                         , On Monday morning, a 30-year-old surrogate arrived at the makeshift clinic with the baby boy she delivered in hospital a week earlier. She was unable to hold back her tears as she handed baby Laurence over to the staff.                                                                                                                                                                     , "It is even harder that he is in a place where there is shelling," said the surrogate, who only wanted to use her first name, Victoria. "And when will his parents get to take him away because of it? It's really hard."                                                                                                                                                                       , Victoria was transferred from the maternity hospital to the surrogacy center in a van by a center staff member. The staffer drove at nearly 100 miles an hour across the city to try to lessen the chance of being hit by missiles, she said. As Victoria entered the building cradling the baby, she said she could hear the sound of Ukrainian anti-aircraft fire in the distance.            , Once inside the basement, there were three louder explosions, one of which brought down an incoming Russian cruise missile less than a mile away. Surveillance footage posted on social media shows a man walking along the street nearby when the intercepted missile fell. No one is believed to have been killed in the blast.                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                 , 'They had waited 20 years for their baby'                                                                                                                                                                                                                                                                                                                                                       , Baby Laurence's biological parents, who provided both the sperm and the egg for the pregnancy, live abroad. But it's unclear when they will be able to collect their son.                                                                                                                                                                                                                       , "They say they are coming," Victoria said. "(But) it's very hard with the paperwork at the moment. How (long) it's going to (take), nobody can tell."                                                                                                                                                                                                                                           , Victoria added that she kept Laurence's parents updated "until the last minute" before she handed the baby over to the surrogacy center. "And hopefully we will keep in touch, because (the situation is) very hard."                                                                                                                                                                           , Many countries around the world have strict rules on the practice of surrogacy, and some couples struggling to have a baby naturally have turned to Ukraine in recent years, where commercial surrogacy is not outlawed, and its clinics offer competitive prices compared with other countries.                                                                                                , Ihor Pechenoga, the doctor who helps to run the surrogacy center, said the women are paid between $17,500 and $25,000 for being a surrogate.                                                                                                                                                                                                                                                    , Victoria wanted to put the money toward a deposit on a house for her own family, which she has struggled to save for since giving birth to her own daughter at the age of 17. Her now-13-year-old daughter left Ukraine for Bulgaria when the war started, she said.                                                                                                                            , But after being hospitalized through most of her pregnancy with Laurence due to complications from pregnancy -- and facing what she describes as the trauma of giving up the baby she feels she has now bonded with -- Victoria said she would never do it again.                                                                                                                               , BioTexCom has paused the program because of the war, focusing on supporting the women who are currently pregnant, and getting the newborns safely out of the country. While the clinic can try to transport the infants to safer areas in the west of Ukraine, the new parents still have to pick up the babies inside the country for legal reasons -- and some are scared to cross the border.,                                                                                                                                                                                                                                                                                                                                                                                                 , "It all depends on the strength of the parents' desire," 51-year-old Pechenoga said. "I met with parents who came to Kyiv to pick up their baby; they had tears in their eyes. They had waited 20 years for their baby, (so) of course they came no matter what."                                                                                                                               , But there are also "couples who are afraid, because there is a war going on here, and a serious war," he said.                                                                                                                                                                                                                                                                                  , Six nannies are working at the clinic to feed and care for the 21 babies. They are becoming increasingly worried about the progress of the conflict, as the bombs land closer to the building. The babies can sense the fear and worry in the room, said one nanny, 37-year-old Antonina Yefimovich.                                                                                            , But the nannies have refused opportunities to leave Kyiv, because they don't want to abandon the children.                                                                                                                                                                                                                                                                                      , "I would go, (because) I have my own family, too. But we have no one to leave these babies with," said Yefimovich.                                                                                                                                                                                                                                                                              , Yefimovich's mother, husband and two daughters have already fled the city and are now more than 120 miles away.                                                                                                                                                                                                                                                                                 , "Of course, I'm worried about them," she said. "But I feel better because at least my mother and husband are there. They will take care of the children."                                                                                                                                                                                                                                       , These babies "can't be abandoned," she continued. "They're defenseless. They also need care. And we really hope that the parents will come and pick them up soon."                                                                                                                                                                                                                              , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/14/business/papa-johns-russia.html </td>
   <td style="text-align:left;"> 2022-03-15 06:14:12 </td>
   <td style="text-align:left;"> He’s American, He Oversees Papa John’s in Russia and He’s Staying - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Christopher Wynne’s company controls the franchise agreements for the 190 Papa John’s locations in the country. “At the end of the day, they appreciate a good pizza,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                 , By Julie Creswell                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Papa John’s International said last week that it was suspending all of its corporate operations in Russia, following in the footsteps of other high-profile American brands like McDonald’s and Starbucks.                                                                                                                                                                                                                                                                                                                                                                                                                      , However, the 190 Papa John’s restaurants in the country are still open and selling pizzas. And they have no plans to stop.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , These Papa John’s shops are primarily owned by Russians through a franchise agreement with a company controlled by Christopher Wynne, a Colorado native who has lived part time and worked in the country since the early 2000s. And even as the war with Ukraine continues and numerous global food brands and retailers suspend operations and stop selling goods in Russia, little has changed with his operation, said Mr. Wynne, 45.                                                                                                                                                                                       , “The best thing I can do as an individual is show compassion for the people, my employees, franchisees and customers without judging them because of the politicians in power,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                        , On the day in late February when Russia recognized two Ukraine provinces as independent, Mr. Wynne said, an anxiety blanketed the country since many Russians have friends and family in Ukraine. Nonetheless, “customers were showing up as usual,” he said.                                                                                                                                                                                                                                                                                                                                                                   , And despite various sanctions that have made international financial transactions exceedingly difficult, Mr. Wynne said, internal credit card payment systems and the internet still work normally.                                                                                                                                                                                                                                                                                                                                                                                                                             , “The vast majority of Russian people are very clearheaded and understand the dark gravity of the situation they’re in,” he said. “And, at the end of the day, they appreciate a good pizza.”                                                                                                                                                                                                                                                                                                                                                                                                                                    , Mr. Wynne, who has a home in Moscow, has plans to open 20 to 40 more restaurants in the country this year. He did acknowledge those plans could be derailed by two factors: a deep contraction in Russia’s economy — he noted that consumer confidence was very low as people lost their jobs — and any retaliatory move by the Russian government against American and European brands that have paused Russian operations.                                                                                                                                                                                                    , Mr. Wynne said he hoped his business, PJ Western, which had $59 million in revenues in 2020 and oversees the franchisees that employ 9,000 people, “will not fall in this category since the business continues to operate.”                                                                                                                                                                                                                                                                                                                                                                                                    , “But those which are closing will face increased scrutiny from the government,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Last week, President Vladimir V. Putin warned that the government could nationalize the assets of companies that had left Russia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Mr. Wynne has significant financial incentive to keep the restaurants open. The company he founded has various partners and investors, including Alex Ovechkin, the Washington Capitals hockey star, who has previously expressed support for Mr. Putin; the Finnish private-equity firm CapMan; and the Russian private-equity firm Baring Vostok. Its assets totaled $85 million, but it also had more than $88 million of short- and long-term debt, according to a 2021 filing with the Securities and Exchange Commission.                                                                                                 , Mr. Wynne’s history in Russia dates to the early 2000s. That’s when, after working to foster cooperation with nuclear nonproliferation as a contractor with the National Nuclear Security Administration in Washington, he moved to Moscow with $20,000 worth of used computers that he began to sell. In 2007, he had the opportunity to buy a stake in the Papa John’s pizza franchise in Russia, and he took it.                                                                                                                                                                                                             , He formed PJ Western and became the master franchisee for Papa John’s in the region, taking over four restaurants in Russia. The contract gives him the ability to sign subagreements that allow others to open their own Papa John’s restaurants in the area.                                                                                                                                                                                                                                                                                                                                                                  , Over the past 15 years, Papa John’s growth has been robust in Russia. Today, there are more than 190 stores in the country, and Mr. Wynne has started to expand to Poland and Germany. Last year, PJ Western sold its stores and now collects royalty payments from the franchisees in exchange for services like marketing, running the websites and handling the supply chain, Mr. Wynne said.                                                                                                                                                                                                                                , In the past two decades, one of the fastest and easiest ways for recognizable American brands to establish fast-food footholds in Russia has been through franchising. The decidedly capitalist, entrepreneur-driven model, used widely in the United States, was embraced in Russia as the country’s citizens, as well as individuals and groups from other countries, opened KFCs, Pizza Huts, Starbucks, Burger Kings and Papa John’s locations across the country.                                                                                                                                                          , Last week, though, as pressure intensified for food companies and restaurants to take a stance against Russia’s invasion of Ukraine, many announced they were pausing operations or temporarily closing restaurants in Russia. For McDonald’s, the decision to temporarily shut all restaurants, while difficult for a company that has operated in the region for 30 years, was logistically easier since it owns 84 percent of the 847 McDonald’s locations in Russia. (All 847 are closing, and McDonald’s told investors last week that it would spend $50 million a month on leases, employee salaries and other expenses.), For other fast-food chains, though, the move to suspend operational support is more symbolic than literal largely because of the franchising model.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , For instance, Restaurant Brands International said it was “suspending support” for the Russian market, but did not detail what that would mean for the 800 Burger Kings in Russia that are owned by franchisees. Media reports in 2019 said 550 Burger King restaurants in Russia were owned by an investment-based consortium led by the investment arm of the Russian state-owned VTB Bank. VTB’s website in Russia could not be accessed.                                                                                                                                                                                    , In a statement, Restaurant Brands International said: “We cannot speak on behalf of our franchisees. Regarding the business in Russia, we can confirm that we are in full compliance with all applicable sanctions.”                                                                                                                                                                                                                                                                                                                                                                                                            , Likewise, last week Yum Brands said it was shutting down the 70 company-owned KFC restaurants in Russia and completing an agreement to close 50 franchise-owned Pizza Hut restaurants, but it was unclear whether the remaining 900-plus KFC restaurants in Russia that are owned by franchisees would remain open. In 2018, Russian media reported that VTB was part of an investment consortium that had acquired 180 KFC restaurants. Yum Brands did not respond to an email seeking comment.                                                                                                                                , Rising concerns. Russia’s invasion on Ukraine has had a ripple effect across the globe, adding to the stock market’s woes and spooking investors. The conflict has already caused​​ dizzying spikes in energy prices, and could severely affect various countries and industries.                                                                                                                                                                                                                                                                                                                                                 , The cost of energy. Oil prices already were the highest since 2014, and they have continued to rise since the invasion.  Russia is the third-largest producer of oil, so more price increases are inevitable.                                                                                                                                                                                                                                                                                                                                                                                                                   , Gas supplies. Europe gets nearly 40 percent of its natural gas from Russia, and it is likely to be walloped with higher heating bills. Natural gas reserves are running low, and European leaders worry that Moscow could cut flows in response to the region’s support of Ukraine.                                                                                                                                                                                                                                                                                                                                             , Food prices. Russia is the world’s largest supplier of wheat; together, it and Ukraine account for nearly a quarter of total global exports. Countries like Egypt, which relies heavily on Russian wheat imports, are already looking for alternative suppliers.                                                                                                                                                                                                                                                                                                                                                                , Shortages of essential metals. The price of palladium, used in automotive exhaust systems and mobile phones, has been soaring amid fears that Russia, the world’s largest exporter of the metal, could be cut off from global markets. The price of nickel, another key Russian export, has also been rising.                                                                                                                                                                                                                                                                                                                   , Financial turmoil. Global banks are bracing for the effects of sanctions intended to restrict Russia’s access to foreign capital and limit its ability to process payments in dollars, euros and other currencies crucial for trade. Banks are also on alert for retaliatory cyberattacks by Russia.                                                                                                                                                                                                                                                                                                                            , Politics aside, the reluctance among the Russian-based franchisees to close their doors has much to do with the fact that they, not the parent corporation, have invested money and taken on significant financial risks in operating the stores. While the parent company may provide advertising dollars and strategy, and other support, the franchise owner is responsible for rent and electricity, construction costs to meet corporate standards, franchise fees or royalties, employee wages, and the food.                                                                                                             , So while temporarily closing restaurants in Russia may have little impact on the overall revenues or profits of big companies like Papa John’s or Yum Brands, it could mean financial ruin for these smaller operators.                                                                                                                                                                                                                                                                                                                                                                                                         , “These are Russian-owned businesses, owned primarily by Russians or Russian institutions, that don’t share our beliefs or requirements,” said Michael Seid, the founder of MSA Worldwide, a global franchise advisory firm. “The Russian franchisee has debt, has to pay the employees. They’re going to do what is in their best interest, and it will all get sorted out later.”                                                                                                                                                                                                                                              , In the two weeks after Russia invaded Ukraine, Mr. Wynne said, it was clear from his conversations that executives with Papa John’s in the United States were nervous. Last Wednesday, Papa John’s temporarily cut ties with Mr. Wynne’s business in Russia when it said it would no longer “provide operational, marketing or business support to the Russian market.”                                                                                                                                                                                                                                                         , “Our perspectives diverged fairly quickly,” Mr. Wynne said a day later in a Zoom interview from Milan, where he was visiting before he planned to return to Russia this week. “I have a perspective where my interest is first and foremost my employees and franchisees and keeping the lines of cultural exchange with the Russian people open,” Mr. Wynne said.                                                                                                                                                                                                                                                              , “Papa John’s is worried about the corporate and political winds that, on a day-to-day basis, I cannot focus on,” he added. (Mr. Wynne’s business interests go beyond Papa John’s. During the pandemic, he began a CBD business in Colorado.)                                                                                                                                                                                                                                                                                                                                                                                    , In an emailed statement, Papa John’s said it believed its decision to pause operations in Russia was “supported by the vast majority of our team members, franchisees, customers and communities around the globe.”                                                                                                                                                                                                                                                                                                                                                                                                             , Mr. Wynne’s wife is Russian, and the couple have a 2-year-old daughter. They have a farm in Colorado that they consider home, but still spend considerable time in Russia. While there, Mr. Wynne said, he spends his time during the week visiting Papa John’s locations “from Moscow to Siberia.” On the weekends, he goes fishing, takes family hikes in the hills outside Moscow and takes his daughter to the city’s playgrounds.                                                                                                                                                                                          , He said it “has never been my responsibility or right to comment about the politics in Russia,” instead focusing on the opportunities he believed his business gave to people in the country.                                                                                                                                                                                                                                                                                                                                                                                                                                   , “The current situation will increase the challenges we are faced with, but I believe that what we are doing is the right thing to do,” Mr. Wynne said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , While he prefers to focus on business rather than politics, geopolitics have affected his business operations over the years. In 2014, when the United States enacted sanctions on Russia after it illegally annexed Crimea, Mr. Wynne had to scramble to rework his supply chain system.                                                                                                                                                                                                                                                                                                                                       , “In 2013, about 92 percent of my supply chain was imported,” he said. After the sanctions were put in place, Mr. Wynne, whose company had previously funded construction of two fresh dough production facilities, added seven more and began working with Russian farmers and manufacturers to produce the tomatoes, mozzarella cheese and other ingredients he had imported.                                                                                                                                                                                                                                                  , “We switched to an entirely localized supply chain,” Mr. Wynne said. “The only thing we import is olives.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/14/stock-futures-rise-slightly-as-wall-street-awaits-fed-rate-hike-ukraine-developments.html </td>
   <td style="text-align:left;"> 2022-03-15 06:05:33 </td>
   <td style="text-align:left;"> Stock futures rise slightly as Wall Street awaits Fed rate hike, Ukraine developments </td>
   <td style="text-align:left;"> , U.S. stock futures rose slightly on Monday night as investors continue to monitor developments in the Russia-Ukraine conflict and get ready for a key Federal Reserve policy decision.                                                                                                                         , Dow Jones Industrial Average futures rose by 70 points, or 0.21%. S&amp;P 500 and Nasdaq 100 futures climbed 0.31% and 0.44%, respectively.                                                                                                                                                                        , Earlier in the day, the S&amp;P 500 declined 0.7%, while the tech-heavy Nasdaq Composite slid 2%. Both finished their seventh negative session in the past eight. Meanwhile, the Dow Jones Industrial Average finished flat after climbing as much as 450 points earlier in the day.                               , Investors watched the ongoing conflict between Russia and Ukraine, as both countries started a fresh round of ceasefire talks on Monday. Meanwhile, Russia is approaching a series of deadlines to make payments on its debt.                                                                                  , Elsewhere, officials from the United States and China met on Monday to discuss a range of challenges facing their bilateral relationship, including Russia's ongoing war in Ukraine.                                                                                                                           , "The market is jittery," said Gene Goldman, chief investment officer at Cetera Investment Management. "So much concern about the Russian invasion, inflation, and the Fed. With growing concerns of a bear market, investors have been skittish."                                                              , Still, he said he doesn't feel a bear market is in the cards, saying, "A pullback/correction becomes a bear market if a recession is likely. Fundamental data (labor, construction spending, PMIs, etc.) all support a solid economic base."                                                                   , Investors are anticipating an important rate hike from the Fed, after the central bank commences a two-day session on Tuesday that will signal a tightening of monetary policy. The central bank is widely expected to raise its target fed funds rate by a quarter percentage point from zero.                , Mounting inflationary concerns will weigh on the Fed meeting. A lockdown in China could worsen supply chain issues, after a surge in coronavirus cases suspended production in cities such as Shenzhen, a key manufacturing city. The Russia-Ukraine conflict had already led to a spike in commodities prices., "With both of these factors driving prices higher, the government has no choice but to increase rates to absorb the inflation that is accelerating," said Benjamin Tsai, president and managing partner at Wave Financial Group.                                                                               , There also will be adjustments to the economic outlook, projections for the future path of rates and likely a discussion about when the Fed can start reducing its bond portfolio holdings.                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/services-pmi </td>
   <td style="text-align:left;"> 2022-03-15 05:50:42 </td>
   <td style="text-align:left;"> New Zealand Services Sector Continues to Contract </td>
   <td style="text-align:left;"> The Business NZ Performance of Services Index in New Zealand rose to 48.6 in February of 2022 from an upwardly revised 46 in the prior month, marking the seventh straight contraction for the Kiwi services sector and well below the long-term average of 53.6. The sub-index of employment continued to contract (45 vs 47.2 in January), falling to its lowest level since May of 2020, while the delivery time level also fell (34.4 vs 43.4). On the other hand, growth took place for activity/sales (50.7 vs 44.6), and new orders/business (53.6 vs 41.2). BusinessNZ chief executive Kirk Hope said “the ongoing trend of contraction was given the current restrictions and interference many businesses in the services sector are experiencing at present.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/inflation-hitting-nonwhite-voters-hardest-democrats-2022-midterms-poll </td>
   <td style="text-align:left;"> 2022-03-15 05:20:42 </td>
   <td style="text-align:left;"> Inflation hitting nonwhite voters hardest, imperiling Democrats in 2022 midterms, new poll finds </td>
   <td style="text-align:left;"> FOX Business’ Larry Kudlow rips President Biden putting inflation blame on the Ukraine crisis.                                                                                                                                                                                                                                          , Nonwhite voters have been most impacted by inflation and their growing frustration poses a threat to Democrats ahead of the 2022 midterms, according to the findings of a recent poll.                                                                                                                                                  , The poll, published Monday by The Wall Street Journal, showed that around 35% of nonwhite voters – including Black, Hispanic, and Asian-American – reported inflation causing higher strain on their finances compared with less than a third of White voters.                                                                          , Gas prices are displayed at a gas station Friday, March 11, 2022, in Long Beach, Calif. (AP Photo/Ashley Landis)                                                                                                                                                                                                                        , Overall, nearly 60% of participants said inflation was causing them "major or minor financial strain." Some of them reportedly blamed President Biden’s actions to limit oil-and-gas drilling and pipelines in the U.S. for causing inflation.                                                                                          , Inflation hit a 40-year high in February, largely driven by higher gas prices. The consumer price index climbed nearly 8% on an annual basis, according to data released last week by the Bureau of Labor Statistics. Month over month, inflation rose 0.8%.                                                                            , CHINA'S NEW COVID LOCKDOWN HITS APPLE SUPPLIER, RAISING RISK OF HIGHER INFLATION                                                                                                                                                                                                                                                        , The growing resentment will have implications for Democrats going into the midterm polls. Democrats have traditionally relied on nonwhite voters as a solid voting bloc. But now many of these same nonwhite voters – Black, Hispanic, and Asian-American among them – say they think Republicans are better equipped to tame inflation., According to the U.S. Bureau of Labor Statistics, U.S. grocery prices increased an average of nearly 11 percent over last year.  (FNC)                                                                                                                                                                                                  , According to The Journal’s poll, 46% of Hispanic voters said they would "probably or definitely" vote for a Republican candidate for Congress over a Democrat, while Black voters who favored Democrats have dwindled by more than a third.                                                                                             , CLICK HERE TO READ FOX BUSINESS ON THE GO                                                                                                                                                                                                                                                                                               , Meanwhile, all voters reported inflation and rising prices being the top issue for them, ranking well ahead of the Russia-Ukraine crisis, immigration and border security, and the COVID-19 pandemic.                                                                                                                                   , To read more from The Wall Street Journal, click here.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 04:55:31 </td>
   <td style="text-align:left;"> Brazilian Stocks Close in the Red </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Ibovespa, closed 1.6% lower at 109,928 on Monday, led by sharp declines in stocks linked to commodities, especially those of agricultural goods and metals as investors monitored developments of the war in Ukraine and the lockdown status in Chinese cities. Locally, caution prevails ahead of the Copom meeting this week, with analysts expecting the central bank to announce a one percentage point hike, to 11.75%, amid persistent inflationary pressures. Meanwhile, Brazil's central bank financial markets' weekly survey for 2022 showed IPCA forecasts climbed to 6.45% from 5.65% a week earlier, the ninth straight week of increases. As a result, analysts also raised forecasts for the benchmark Selic rate, which should reach 12.75% by the end of 2022, compared to 12.25% in last week's survey. The estimate of economic growth for 2022 advanced to 0.49%, up from 0.42% a week ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 04:35:24 </td>
   <td style="text-align:left;"> Canadian Stocks Close Lower </td>
   <td style="text-align:left;"> Canada’s S&amp;P/TSX Composite Index closed 1.4% lower at 21,181 on Monday, extending the previous session’s losses, weighed down by lower commodity prices while investors monitored security negotiation talks between the Ukrainian and Russian delegations, which are set to continue tomorrow. A significant daily decline in oil prices pressured energy stocks to fall 4.5%, while lower metals dragged miners to fall 3.1%. On the other hand, stocks in the financial sector closed mostly in the green ahead of policy decisions by multiple central banks this week, including the Federal Reserve. Among individual stocks, Turquoise Hill shares jumped 31.9% after Anglo-Australian mining giant Rio Tinto offered to buy the remaining 49% stake of the Canadian miner for USD 2.7 billion, moving towards full ownership of a large copper and gold mine in Mongolia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/money/russia-debts-ruble-sanctions </td>
   <td style="text-align:left;"> 2022-03-15 04:27:26 </td>
   <td style="text-align:left;"> Russia threatens to pay foreign debts in devalued ruble amid crippling sanctions </td>
   <td style="text-align:left;"> Harry Yeh and Ken Mahoney react to Ukraine getting cryptocurrency donations and the EU voting on a proposed rule to ban bitcoin on 'Mornings with Maria.'                                                                                                                                                                    , Russia is threatening to pay off its foreign debts with its devalued ruble after major Russian banks were sanctioned, cutting them off from global financial markets, over Moscow's invasion of Ukraine.                                                                                                                     , Russia has to pay $117 million on two Eurobonds on Wednesday, Reuters reported.                                                                                                                                                                                                                                              , RUSSIA-UKRAINE WAR: CONGRESS EYES MIG-29 FIGHTER JET TRANSFER AS WHITE HOUSE PRESSURE POINT                                                                                                                                                                                                                                  , People walk past a currency exchange office screen displaying the exchange rates of U.S. Dollar and Euro to Russian Rubles in Moscow's downtown, Russia, Monday, Feb. 28, 2022. Moscow’s war on Ukraine and the ferocious financial backlash it’s unleashe                                                                   , In a Monday interview with state television, Russian Finance Minister Anton Siluanov said Moscow has asked Western banks to carry out the transaction. The sanctions have isolated Russian banks and frozen billions of dollars in gold and reserves, the news outlet reported.                                              , In addition, Russian banks have been banned from the SWIFT international payment network, which has hampered efforts to move money outside the country.                                                                                                                                                                      , "If we see complications with executing the order then on Tuesday we will prepare a relevant transfer order in the rouble equivalent," Siluanov said. "                                                                                                                                                                      , He called the freezing of the central bank and government's foreign currency accounts "a desire by several Western countries to organize an artificial default."                                                                                                                                                             , Ukrainian MP Sviatoslav Yurash talked with ‘America Reports’ about the situation in the region around Kyiv.                                                                                                                                                                                                                  , Since Russia's invasion of Ukraine, the ruble has plummeted to record lows and the sanctions have triggered an economic crisis not seen in the country since the 1991 fall of the Soviet Union.                                                                                                                              , On Monday, State Department spokesman Ned Price said there will be "consequences" for any country that supports Russia's military aspirations in Ukraine.                                                                                                                                                                    , Fox News foreign correspondent Trey Yingst joined 'Fox &amp; Friends Weekend' by phone from Ukraine to report the news of Brent Renaud's death.                                                                                                                                                                                  , CLICK HERE TO GET THE FOX NEWS APP                                                                                                                                                                                                                                                                                           , "We will not allow any country to compensate Russia for its losses," Ned Price told reporters. "We've made very clear that any country that would seek to attempt to bail Russia out of this economic, financial morass will be met with consequences. We will ensure that no country is able to get away with such a thing." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 04:08:00 </td>
   <td style="text-align:left;"> US Stocks End in Negative Territory </td>
   <td style="text-align:left;"> Major US stock indices closed lower on Monday, failing to hold early gains as investors weighed on continued volatility in commodity prices amid security negotiations between the Russian and Ukrainian delegations. The Dow erased its 450 point gain to close at 32,945, while the S&amp;P 500 and the Nasdaq fell 0.7% and 2%, respectively. Prospects of higher interest rates also kept sentiment subdued, as the US central bank is expected to raise its target fed funds rate by 25 basis points on Wednesday to tame inflation that is already running at multi-decade highs. Besides higher borrowing costs, stricter Covid-19 measures in China strengthened fears of input shortages for tech companies, dragging Apple (-2.7%), Intel (-3.1%), and NVIDIA (-3.5%) to close in the red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60741158?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-15 04:05:56 </td>
   <td style="text-align:left;"> All UK travel rules to end on Friday, says government </td>
   <td style="text-align:left;"> The transport secretary has confirmed that all remaining Covid travel measures will be scrapped.                                                                                                                                                                             , Currently, everyone travelling to the UK must complete a passenger locator form before they arrive.                                                                                                                                                                          , Travellers who are not fully vaccinated have to take a Covid test before departure, fill in the form, and book and pay for a PCR test after arriving.                                                                                                                        , Grant Shapps confirmed in a tweet that these rules will end at 04:00 on Friday.                                                                                                                                                                                              , His announcement means that passengers who are not fully vaccinated will no longer have to take Covid tests before and after travelling to the UK. The passenger locator form will no longer be necessary either.                                                            , People planning an overseas trip will still need to be aware of other countries' entry rules.                                                                                                                                                                                , Mr Shapps tweeted: "These changes are possible due to our vaccine rollout and mean greater freedom in time for Easter."                                                                                                                                                      , When any new Covid strains appear in the future, the government said its default approach would be to use "the least-stringent measures" for restricting travel.                                                                                                             , Its "Living with Covid" plan said new measures at the border would only be considered in "extreme circumstances".                                                                                                                                                            , It said the UKHSA would closely monitor the prevalence and spread of Covid variants.                                                                                                                                                                                         , Scotland and Wales have agreed to follow England in scrapping the remaining coronavirus border measures.                                                                                                                                                                     , But Welsh Health Minister Eluned Morgan said she was doing so "reluctantly" - and was "extremely disappointed" that testing requirements and the passenger location form were being ditched.                                                                                 , The Scottish government said consistency across the four nations was agreed because of the "negative impact of non-alignment on the tourism industry".                                                                                                                       , Testing requirements for fully-vaccinated arrivals into the UK were dropped in February.                                                                                                                                                                                     , The latest move was welcomed by some figures in the travel industry, which has campaigned for the remaining rules to be dropped so businesses can take full advantage of strong summer holiday demand.                                                                       , Tim Alderslade, chief executive of trade body Airlines UK, said: "Today's announcement sends a clear message to the world - the UK travel sector is back.                                                                                                                    , "With travellers returning to the UK no longer burdened by unnecessary forms and testing requirements, we can now look forward to the return to pre-Covid normality throughout the travel experience."                                                                       , A Virgin Atlantic spokesperson said: "The removal of all remaining UK travel restrictions is the final important step towards frictionless air travel, helping to further restore consumer confidence as we welcome more customers back to the skies this spring and summer. , "To uphold the experience of all travellers, it's vital that the UK Government works closely with industry to ensure the UK border is ready for increasing passengers, as international travel ramps up."                                                                    , Meanwhile, Eurostar's chief executive Jacques Damas said the easing of restrictions would help the cross-Channel train operator's recovery.                                                                                                                                  , "We hope and expect to see the UK's approach replicated across our other markets in the coming weeks," Mr Damas said.                                                                                                                                                        , However, as Covid restrictions recede, other headwinds for the aviation industry are appearing.                                                                                                                                                                              , The price of jet fuel has soared as a result of higher crude oil prices. This adds to cost pressures on airlines, although some have been protected by their hedging strategies, whereby they purchased fuel in advance at lower prices.                                     , On Friday, the chief executive of Heathrow airport, John Holland-Kaye, said the recovery of aviation remained "overshadowed by war and Covid uncertainty".                                                                                                                   , Businesses will also be keeping a careful eye on whether consumers' confidence to book is knocked by the war in Ukraine and rising household bills squeezing disposable incomes.                                                                                             , Air France-KLM and Ryanair have both recently warned air fares will rise.                                                                                                                                                                                                    , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                       , Cat Deeley and Edith Bowman are best friends - here is their story                                                                                                                                                                                                           , A failing witchfinder and his suspect find themselves on a hellish road trip...                                                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/lyft-uber-fuel-surcharge-high-gas-prices </td>
   <td style="text-align:left;"> 2022-03-15 03:57:41 </td>
   <td style="text-align:left;"> Lyft follows Uber in adding fuel surcharge due to high gas prices </td>
   <td style="text-align:left;"> D. Alexander Capital chief investment officer Larry Shover gives his take on U.S. oil imports on 'Making Money.'                                                                                                                                                        , Rideshare company Lyft has joined competitor Uber in announcing it will soon be charging customers a fuel surcharge to ease the pain of high gas prices on its drivers.                                                                                                 , Lyft logo displayed on a phone screen is seen in this illustration photo taken in Krakow, Poland on July 8, 2021. (Photo Illustration by Jakub Porzycki/NurPhoto via Getty Images) (Photo Illustration by Jakub Porzycki/NurPhoto via Getty Images / Getty Images)      , "We’ve been closely monitoring rising gas prices and their impact on our driver community," Lyft said in a statement to FOX Business.                                                                                                                                   , AMERICANS RECONSIDER DRIVING, SPENDING HABITS AND THEIR EMPLOYMENT AMID RECORD GAS PRICES                                                                                                                                                                               , "Driver earnings overall remain elevated compared to last year, but given the rapid rise in gas prices we’ll be asking riders to pay a temporary fuel surcharge, all of which will go to drivers," statement went on to say, adding, "We’ll share more details shortly.", Vehicles wait in line to refuel at a Costco gas station in the South of Downtown (SoDo) neighborhood of Seattle, Washington, U.S., on Wednesday, March 9, 2022.  (Photographer: Chona Kasinger/Bloomberg via Getty Images / Getty Images)                               , Uber made the same move last week, announcing that the cost of each Uber trip would be going up either 45 cents or 55 cents, and each Uber Eats order would increase by 35 cents or 45 cents depending on location.                                                     , Gas prices gradually rose over the past year before surging to record heights following Russia's invasion of Ukraine last month.                                                                                                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                             , According to Reuters, rideshare drivers have taken to social media complaining about the soaring price of gas and questioning whether it still made sense to continue working at their gigs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/china-would-face-consequences-if/story.aspx?guid={6D8BA6B9-ED74-4E2D-A3A6-890D73DBD708}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-15 03:46:06 </td>
   <td style="text-align:left;"> China would face 'consequences' if it helps Russia war against Ukraine, White House says - MarketWatch </td>
   <td style="text-align:left;"> China would face "consequences" if it helps Russia in its war against Ukraine, White House press secretary Jen Psaki told reporters on Monday. The Biden administration's warning came following a meeting between National Security Adviser Jake Sullivan and Yang Jiechi, a member of China's Politburo, in Rome. Psaki did not detail potential consequences. A White House statement said Sullivan in the meeting "raised a range of issues in U.S.-China relations, with substantial discussion of Russia's war against Ukraine."  , The head of the International Monetary Fund said Sunday that she expects a "deep recession" in Russia due to "unprecedented" sanctions by the West after its invasion of Ukraine, and that a Russian sovereign default remains a possibility.                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-15 03:42:35 </td>
   <td style="text-align:left;"> Brazil 10Y Bond Yield Extends Rally </td>
   <td style="text-align:left;"> Brazil’s 10-year government bond yield climbed to 12.9% in the third week of March, edging closer to the two-year high of 13.1% touched on early November as investors continued to assess inflation projections due to higher commodity prices ahead of the expected rate hike by the Central Bank of Brazil. The central bank is expected to increase the Selic rate on its March meeting this week, adding to the 875bps in rate hikes that took place since April last year. Meanwhile, Brazil’s federal government plans to announce a USD 32 billion stimulus program for public pension checks ahead of federal elections in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/elon-musk-spacex-tesla-inflation </td>
   <td style="text-align:left;"> 2022-03-15 03:38:37 </td>
   <td style="text-align:left;"> Elon Musk says SpaceX, Tesla facing 'significant' inflationary pressure </td>
   <td style="text-align:left;"> Yardeni Research President Ed Yardeni, Crossmark Global Investments CIO Bob Doll and Fieldpoint Private Chief Market Strategist Cameron Dawson discuss markets amid the war between Russia and Ukraine.                                                                                                                                                                 , SpaceX and Tesla CEO Elon Musk revealed in a Twitter thread that the two companies are facing "significant recent inflation pressure in raw materials and logistics."                                                                                                                                                                                                   , Musk's Sunday tweet comes as the consumer price index rose 7.9% in February from a year ago, marking the fastest increase since January 1982, when inflation hit 8.4%.                                                                                                                                                                                                  , The CPI — which measures a bevy of goods ranging from gasoline and health care to groceries and rents — jumped 0.8% in the one-month period from January. According to the New York Federal Reserve's Survey of Consumer Expectations, the median expectation is that the inflation rate will be up 6% one year from now, matching an 11-year-high recorded in November., Russia's invasion of Ukraine has also exacerbated the situation, with prices for commodities like metals climbing toward record highs.                                                                                                                                                                                                                                  , FEBRUARY INFLATION: WHERE ARE RISING PRICES HITTING AMERICANS THE HARDEST?                                                                                                                                                                                                                                                                                              , In a separate tweet, Musk advised his 77.8 million Twitter followers to own "physical things like a home or stock in companies you think make good products" rather than dollars when inflation is high.                                                                                                                                                                , The billionaire, who has been a proponent of cryptocurrencies, added that he still owns and will not sell his holdings in Bitcoin, Ethereum and Dogecoin.                                                                                                                                                                                                               , Musk has a net worth of $211.9 billion, per real-time tracking by Forbes.                                                                                                                                                                                                                                                                                               , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                             , An analysis by Moody's Analytics senior economist Ryan Sweet found that skyrocketing inflation rates are costing the average American household $296.45 in extra expenses.                                                                                                                                                                                              , Companies that have been forced to take action to combat inflation over the past several months include Rivian, Burger King, Domino's Pizza, Little Caesar's, WingStop, Kroger, Dollar Tree and more.                                                                                                                                                                   , Fox Business' Megan Henney contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60743592?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-15 03:27:04 </td>
   <td style="text-align:left;"> IMF: Ukraine economy could shrink as much as 35% </td>
   <td style="text-align:left;"> The Ukrainian economy could shrink by more than a third this year if the war with Russia continues, the International Monetary Fund said.                                                                                                                                                                                                      , The global lending body said the country is already facing a downturn of 10% due to the invasion, which has hit major cities, destroyed airports and precipitated a refugee crisis.                                                                                                                                                            , The IMF recently sent $1.4bn in emergency funds to Ukraine - the maximum allowed under its rules.                                                                                                                                                                                                                                              , Billions more will be needed, it said.                                                                                                                                                                                                                                                                                                         , The dire economic outlook for Ukraine was included in a report prepared before the emergency loan was approved last week. The estimates were calculated by looking at wartime economies in countries such as Lebanon, Iraq and Syria.                                                                                                          , "With the war ongoing, the situation remains extremely fluid, and any forecast is at this stage subject to massive uncertainty,"  the report said, predicting the economy could contract by between 25% to 35%.                                                                                                                                , It said the estimates in the report should be "seen as a bare minimum".                                                                                                                                                                                                                                                                        , In 2014 and 2015, Ukraine also suffered economic shock, with output falling 6.6% and 10% respectively, following Russia's annexation of Crimea.                                                                                                                                                                                                , But Ukraine's economy, which is heavily dependent on exports, expanded 3% last year, lifted by a record grain harvest. Output had been expected to grow another 3.6% in 2022.                                                                                                                                                                  , Now, the IMF said: "A deep recession and large reconstruction costs are to be expected, on the backdrop of a humanitarian crisis."                                                                                                                                                                                                             , For now, the government has prioritised defence and social spending and remained current on its foreign debt obligations, according to the 7 March report. Companies are still paying taxes and money is still flowing through its financial system, though many bank branches have shut and authorities have had to take emergency measures.  , The country is likely to struggle even more, the report warned.                                                                                                                                                                                                                                                                                , The IMF plans to set up tools to help its members send money to help Ukraine, which has already spent the equivalent of $1.4bn to service and repay the government's foreign debt since the start of the war, IMF officials said.                                                                                                              , In an interview with the BBC, the head of Ukraine's central bank Kyrylo Shevchenko said Russian assets frozen in foreign countries, as a result of sanctions, should be used to help rebuild the country.                                                                                                                                      , "The need for money will be huge," he told the BBC. "It could be fulfilled through loans and grants from multinational organisations and direct help from other countries. However, a large share of financing is needed to be obtained as a reparation from the aggressor, including funds that are currently frozen in our allied countries.", Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                                                                                         , Cat Deeley and Edith Bowman are best friends - here is their story                                                                                                                                                                                                                                                                             , A failing witchfinder and his suspect find themselves on a hellish road trip...                                                                                                                                                                                                                                                                , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/world-asia-china-60732486?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-15 03:10:02 </td>
   <td style="text-align:left;"> Ukraine crisis: US warns China against helping Russia </td>
   <td style="text-align:left;"> China will face consequences if it helps Russia evade sanctions in its invasion of Ukraine, the US says.                                                                                                                                                                                 , Unnamed US officials told multiple news outlets that China had signalled willingness to provide military assistance to Russia.                                                                                                                                                           , The Chinese foreign ministry accused the US of spreading disinformation. Russia denied asking Beijing for military help.                                                                                                                                                                 , The exchanges came before top US and Chinese officials met in Rome.                                                                                                                                                                                                                      , Media outlets, citing Washington officials, say that Russia has in recent days asked China specifically for military equipment, including drones.                                                                                                                                        , On Monday, the US warned allies that China had suggested it was open to a move to provide military and economic support, media reports said.                                                                                                                                             , The report came as US National Security Adviser Jake Sullivan met China's top diplomat, Yang Jiechi, for talks in Rome.                                                                                                                                                                  , "Mr Sullivan raised a range of issues in US-China relations, with substantial discussion of Russia's war against Ukraine," a readout of the meeting said. "They also underscored the importance of maintaining open lines of communication between the United States and China."         , In an earlier CNN interview, Mr Sullivan said the US was "communicating directly, privately to Beijing that there will absolutely be consequences for large-scale sanctions evasion efforts or support to Russia to backfill them".                                                      , "We will not allow that to go forward and allow there to be a lifeline to Russia from these economic sanctions from any country, anywhere in the world," he said.                                                                                                                        , He added that while the US believed China was aware that Russian leader Vladimir Putin was "planning something" before the invasion happened, Beijing "may not have understood the full extent of it".                                                                                   , "Because it's very possible that [Mr] Putin lied to them the same way that he lied to Europeans and others," Mr Sullivan said.                                                                                                                                                           , In response, a spokesman for the foreign ministry in Beijing, Zhao Lijian, said the US had "been spreading disinformation targeting China on the Ukraine issue, with malicious intentions".                                                                                              , Asked if he could clarify whether China had received a request for military help from Russia, Mr Zhao said this was "fake news" but did not deny it directly. He added that China's stance had always been consistent and that China was playing a constructive role in promoting talks. , President Putin's spokesman Dmitry Peskov said reports Russia had asked China for military assistance were not true.                                                                                                                                                                     , "Russia possesses its own independent potential to continue the operation. As we said, it is going according to plan and will be completed on time and in full," he said.                                                                                                                , State Department spokesman Ned Price said the US raised concerns with the Chinese delegation "directly and very clearly".                                                                                                                                                                , China has so far refrained from condemning Russia for the invasion and has said Moscow's "legitimate security concerns" should be taken seriously.                                                                                                                                       , When the United Nations General Assembly voted to condemn Russia's invasion earlier this month, China was one of 35 countries that abstained.                                                                                                                                            , But Beijing at the same time has expressed "unwavering support" for Ukraine's sovereignty. It has also called for peace and has said it is ready to help end the war through diplomacy. Several countries have urged China to do more to stop Russia's invasion.                         , The EU and US help Ukraine, China helps Russia; if that's how this goes, then it's a delineation that will make the war in Ukraine an even more consequential one.                                                                                                                       , The White House has decided to make public its claim just as President Biden's top security adviser is due to meet China's most senior diplomat. It appears to be a tactical move, to put pressure on China; presumably to either confirm or deny it.                                    , The bigger aim could be to try to make Xi Jinping weigh up the pros and cons to his current position of what was last week called a "rock solid" relationship with Moscow.                                                                                                               , Remember that it was just weeks ago, as the Winter Olympics opened in Beijing, that Presidents Xi and Putin declared a new alliance that had "no limit". Military aid could, clearly, be part of that.                                                                                   , But in the days after Russia's invasion China has condemned the UK, the US and others for giving weapons to Ukraine's military, saying they were adding "fuel to the fire".                                                                                                              , If the US intelligence assessment is correct and Beijing follows through on that request, then they too would be "adding fuel".                                                                                                                                                          , This video can not be played                                                                                                                                                                                                                                                             , Are you or your family in Ukraine? Please share your experience if it is safe to do so by emailing haveyoursay@bbc.co.uk.                                                                                                                                                                , Please include a contact number if you are willing to speak to a BBC journalist. You can also get in touch in the following ways:                                                                                                                                                        , If you are reading this page and can't see the form you will need to visit the mobile version of the BBC website to submit your question or comment or you can email us at HaveYourSay@bbc.co.uk. Please include your name, age and location with any submission.                        , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                                   , Cat Deeley and Edith Bowman are best friends - here is their story                                                                                                                                                                                                                       , A failing witchfinder and his suspect find themselves on a hellish road trip...                                                                                                                                                                                                          , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/jpmorgan-relaxes-mask-mandate-cnbc/story.aspx?guid={E79DABB6-03E3-43B9-AEEF-6F3C93E9FD4D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-15 03:04:59 </td>
   <td style="text-align:left;"> JPMorgan relaxes mask mandate: CNBC - MarketWatch </td>
   <td style="text-align:left;"> JPMorgan Chase &amp; Co. 
        JPM,
        +0.99%
       on Monday said masking in its corporate office buildings will be completely voluntary for both vaccinated and unvaccinated colleagues, effective immediately, according to an internal memo published by CNBC. The bank also said as of April 4 it will discontinue mandatory testing for the unvaccinated, as well as asking employees to report COVID-19 infections, in line with CDC guidance. The bank also said it would no longer solely hire vaccinated people as of April 4. Shares of JPMorgan Chase are up 0.7% in recent trades, compared to a dip of 0.1% by the Dow Jones Industrial Average. , The chief executive of Pfizer Inc. said Sunday that COVID-19 is not going to just go away in the coming years, and that fully vaccinated people will need a fourth shot later this year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/consortium-elliott-advanced-talks-buy-nielsen-holdings </td>
   <td style="text-align:left;"> 2022-03-15 03:04:13 </td>
   <td style="text-align:left;"> Consortium including Elliott in advanced talks to buy Nielsen Holdings </td>
   <td style="text-align:left;"> Yardeni Research President Ed Yardeni, Crossmark Global Investments CIO Bob Doll and Fieldpoint Private Chief Market Strategist Cameron Dawson discuss markets amid the war between Russia and Ukraine.                                                                                                                                                                                                                                              , A consortium of private-equity firms including Elliott Management Corp. is in advanced talks to buy TV-ratings company Nielsen Holdings PLC for about $15 billion including debt, according to people familiar with the matter.                                                                                                                                                                                                                      , UKRAINE - 2021/03/19: In this photo illustration, Nielsen Holdings logo is seen on a smartphone and a pc screen in the background. (Photo Illustration by Pavlo Gonchar/SOPA Images/LightRocket via Getty Images) (Photo Illustration by Pavlo Gonchar/SOPA Images/LightRocket via Getty Images / Getty Images)                                                                                                                                      , Financing talks with a number of banks are progressing and a takeover deal could be completed within weeks, the people said. There is no guarantee there will be a deal, as the talks could still fall apart.                                                                                                                                                                                                                                        , Should there be one, it would be substantial. Nielsen had a market value of $6.2 billion Monday morning and what is known as an enterprise value of more than $11 billion, given its hefty debt load of over $5 billion.                                                                                                                                                                                                                             , Other details, including potential price per share, couldn’t be learned.                                                                                                                                                                                                                                                                                                                                                                             , TD BANK JUST MADE ITS BIGGEST ACQUISITION EVER                                                                                                                                                                                                                                                                                                                                                                                                       , For years, Nielsen has been synonymous with measuring U.S. TV ratings, which provide audience estimates that networks use to sell commercial time and reassure advertisers they got what they paid for. But its hold has been loosening as streaming gains steam and traditional broadcast and cable TV lose viewers. While the New York-based company has introduced metrics for streaming in recent years, it is one of many players in that field., Nielsen’s shares haven’t performed well as a result. Closing Friday at $17.51, they are down from a high of more than $55 in 2016. They had been on a downward trend for several years when the pandemic’s arrival in early 2020 caused them to plummet. Though they have regained some ground, they are still trading just below where they were before Covid-19.                                                                                   , Elliott has owned a stake in Nielsen since 2018, when it called for the company to explore a sale. The following year, Nielsen said it would spin off part of its business to create two separate, public companies: Global Connect, a market-analytics operation that measures retail and consumer behavior, and the core media business.                                                                                                           , AUSTRALIA'S AGL ENERGY REJECTS $3.5 BILLION OFFER, INVESTORS EXPECT MORE                                                                                                                                                                                                                                                                                                                                                                             , In April 2020, Elliott entered into a settlement agreement with Nielsen in which the company agreed to add a director and form a finance committee on the board that would oversee strategic plans including the separation. Elliott had a roughly 13% economic interest in Nielsen at the time.                                                                                                                                                     , Global Connect was sold last year to private-equity firm Advent International Corp. for nearly $3 billion.                                                                                                                                                                                                                                                                                                                                           , Citrix headquarters in Santa Clara, California, U.S., on Wednesday, Jan. 19, 2022. Elliott Investment Management and Vista Equity Partners agreed to buy software-maker Citrix Systems Inc.. Photographer: David Paul Morris/Bloomberg via Getty Images ( David Paul Morris/Bloomberg via Getty Image / Getty Images)                                                                                                                                , Elliott has been increasingly active in private equity, with its private-equity arm, Evergreen Coast Capital Corp., in January agreeing along with a partner to buy cloud-computing company Citrix Systems Inc. for $16.5 billion including debt. It was the latest in a recent string of big leveraged buyouts as private-equity firms look to deploy mountains of cash they have accumulated.                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                          , Should a deal be completed, it would come as merger volume overall has slowed as a result of market volatility and Russia’s invasion of Ukraine. Global merger activity is down roughly 30% this year compared with the same period in 2021, with roughly $776 billion worth of deals announced, according to Dealogic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-futures-end-lower-us/story.aspx?guid={D2BAFE42-1C7E-4711-952F-A112B692AEFC}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-15 02:40:50 </td>
   <td style="text-align:left;"> Oil futures end lower as U.S. reportedly looks to Venezuela for supplies - MarketWatch </td>
   <td style="text-align:left;"> Oil futures finished lower Monday, on reports that the U.S. may reach a deal to lift sanctions on Venezuelan oil, which would help ease any losses from Russia following its invasion of Ukraine. Oil prices sold off early on peace talks between Russia and Ukraine, then bounced back a bit when it seemed those talks had little chance for success, said Phil Flynn, senior market analyst at The Price Futures Group. However, oil's loss was also linked to COVID-related shutdowns in China and reports that the U.S. is going to allow Venezuela to do some oil-for-debt swaps, in an attempt to get more oil on the market, he said. Flynn believes the Biden administration is desperate to do a deal with Venezuela because supplies of diesel fuel are at historically low levels. West Texas Intermediate crude for April delivery 
        CLJ22,
        -3.82%
       fell $6.32, or 5.8%, to settle at $103.01 a barrel on the New York Mercantile Exchange after trading as low as $99.76., Fully vaccinated people will need a fourth shot later in 2022, according to the head of Pfizer Inc., who said that COVID-19 is not going to just go away in the coming years.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60733390?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-15 02:37:22 </td>
   <td style="text-align:left;"> Petrol prices set to ease after hitting record highs </td>
   <td style="text-align:left;"> Petrol prices are likely to fall back from record levels due to the costs of wholesale fuel and global oil easing, UK motoring groups have said.                                                                                                                      , The average price for a litre of petrol hit £1.63 on Sunday after rising above £1.60 for the first time last week.                                                                                                                                                    , Diesel remained above £1.73 a litre, but the AA said "wild" pump prices should stabilise, unless global oil prices take off again.                                                                                                                                    , But MPs were told this was a "lull before the storm" of more price hikes.                                                                                                                                                                                             , Nathan Piper, head of oil and gas research at financial services company Investec, said consumers "need to get ready for what could be continued increases in fuel prices."                                                                                           , Russia's invasion of Ukraine sparked oil costs to surge worldwide.                                                                                                                                                                                                    , Mr Piper told the Treasury Committee: "If more stringent actions are imposed upon Russia, and five million barrels a day is truly taken out of the market, then oil prices would really have no ceiling."                                                             , He explained that the UK was roughly self-sufficient in petrol but imported much of its diesel.                                                                                                                                                                       , Two thirds of UK consumers use diesel so that it could see the biggest price increases at the pump, he said.                                                                                                                                                          , Dr Amrita Sen, director of research at Energy Aspects, told the committee that petrol prices could rise to around £2.40 a litre. And that diesel prices of "£2.50 - even closer to £3" were "definitely in the realms of possibility".                                , She said the UK could follow Germany in introducing rationing measures which have already seen BP and Shell reduce diesel wholesales to industry.                                                                                                                     , "If we need to rebuild stocks over the summer so that we have a buffer over the winter...it is industry that will need to be curtailed and that's where the first set of rationing will have to come in," she said.                                                   , Mr Piper said the only other option was for the government to release some of its stockpiles of petrol and crude oil.                                                                                                                                                 , "But it'll be industry that takes the brunt of any rationing initially," he said.                                                                                                                                                                                     , Meanwhile, the AA said filling up a typical 55-litre car tank now costs £89.90p on average, up from £68.57 a year ago.                                                                                                                                                , Oil prices soared after Russia invaded Ukraine, with the price of Brent crude oil - the global benchmark for prices - hitting a near 14-year high at one point.                                                                                                       , However, in the past few days, the price of oil has dropped as fears that the European Union would follow the US and Canada in banning Russian oil have eased.                                                                                                        , Brent crude fell as much as 8% to trade at $103.68 per barrel on Monday.                                                                                                                                                                                              , The RAC said drivers would have to stomach probably more rises this week, but added they "should soon get some respite from pump prices jumping by several pence a litre every day as oil and wholesale prices appear to have settled".                               , "The price hikes seen over the weekend are still a result of the oil price rise which began at the start of the month and peaked early last week at $137 a barrel," said RAC fuel spokesman Simon Williams.                                                           , "As the oil price has now fallen back, we should hopefully reach the peak and start to see prices going the other way to reflect the big drop in wholesale costs seen at the end of last week, subject to no further spikes in the barrel price this week."           , The reason higher prices at the pumps are likely to remain despite falling commodity prices is due to the way retailers buy the fuel and the time lag between purchasing at a certain price and then selling it on.                                                   , Yet, there is a concern some retailers might be reluctant to lower their prices for fear of being caught out if wholesale costs jump back up again.                                                                                                                   , Luke Bosdet, the AA's fuel price spokesman, said a 10.6p-a-litre slump in wholesale petrol costs on Wednesday and Thursday last week, followed by oil's fall in value, had produced "bizarre price anomalies".                                                        , "In one town this weekend, filling a tank at one forecourt was more than a pound cheaper than directly across the road at another," he said.                                                                                                                          , Mr Bosdet said weekends were the busiest time for forecourts and the rush by drivers to beat further potential price increases had pushed up demand, which had actually led to even higher prices at the pumps as stations had to resupply at a faster rate.          , Oil prices are mainly determined by the price of crude oil and the dollar exchange rate, as agreements are made in dollars.                                                                                                                                           , Russia is the third largest oil exporter and some Western countries, for example the US and Canada, decided to halt imports from the country in response to Russia's actions. It means demand for oil from other producers has increased, leading to increased prices., The UK only imports about 6% of oil from Russia, so is not as dependent on Russia for the commodity supply as other European countries are and has said it plans to phase it out.                                                                                     , It is, however, affected by the global shifts in price.                                                                                                                                                                                                               , But the price of Brent crude dropped in recent days, due to reduced fears of a European ban on Russian oil, and also partly due to speculation that extra supplies could come onto the market from Iran, Venezuela and the UAE.                                       , The conflict in Ukraine has led to concerns being raised by Western nations about where they get their energy from.                                                                                                                                                   , Energy Minister Greg Hands said the UK's transition to cleaner forms of energy production was "an issue of national security" and not just of decarbonisation.                                                                                                        , Speaking at an event in London, he said: "By switching to cheaper power generated in the UK, for the UK, we will ensure that we're not dependent on any unfriendly foreign country to keep our homes warm and lit."                                                   , However, Mr Hands acknowledged that the transition to cleaner energy sources would take time, and there was still a need to invest in domestic fossil fuel production.                                                                                                , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                , Cat Deeley and Edith Bowman are best friends - here is their story                                                                                                                                                                                                    , A failing witchfinder and his suspect find themselves on a hellish road trip...                                                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/china-covid-lockdown-apple-automakers-inflation </td>
   <td style="text-align:left;"> 2022-03-15 02:26:47 </td>
   <td style="text-align:left;"> China's new COVID lockdown hits Apple supplier, raising risk of higher inflation </td>
   <td style="text-align:left;"> Former deputy national security adviser KT McFarland discusses China and Russia’s recent partnership announcement that is potentially one of the greatest ‘threats’ to U.S. in history on ‘Fox Business Tonight.’                                                                                                                                                                                   , A spike in COVID-19 cases has prompted China to lock down two major cities, freezing production across a number of auto manufacturers and electronics factories – a move that threatens to further exacerbate the hottest inflation in four decades.                                                                                                                                                , Beijing imposed a seven-day lockdown of Shenzhen, a key port city sometimes referred to as the "Silicon Valley of China," as it pursues a zero-COVID strategy. Shenzhen is home to Foxconn, one of the Apple's biggest suppliers, as well as Tencent and Huawei.                                                                                                                                    , A janitor checks his phone outside closed shops in Huaqiangbei area, the world's biggest electronics market, in Shenzhen in south China's Guangdong province Monday, March 14, 2022. (Feature China/Future Publishing via Getty Images / Getty Images)                                                                                                                                              , Foxconn said Monday that it had suspended factory lines in Shenzhen because of the ban on nonessential work. The company did not immediately respond to a FOX Business request for comment, but a spokesperson told The Wall Street Journal that it plans to shift production to a different location in China that has not been affected by the latest restrictions.                               , WHERE ARE SURGING CONSUMER PRICES HITTING AMERICANS THE HARDEST?                                                                                                                                                                                                                                                                                                                                    , Chinese authorities reported 1,337 locally transmitted cases of coronavirus across dozens of mainland cities on Monday, an outbreak driven by the fast-spreading "stealth variant" of BA.2, a subvariant of omicron. Shenzhen reported 75 new cases; the lockdown affects roughly 17.5 million people who live in the city, which neighbors Hong Kong.                                              , The move could further inflame an already snarled global supply chain, which has contributed to the highest inflation in the U.S. since 1982. The Labor Department reported last week that consumer prices surged 7.9% in February from the previous year – driven in part by a shortage of electronics.                                                                                            , In this May 26, 2010 file photo, staff members work on the production line at the Foxconn complex in the southern Chinese city of Shenzhen, southern China.                                                                                                                                                                                                                                         , Foxconn's factory in Shenzhen produces iPhones, Macs and iPads. But more than half of iPhones are produced at a separate factory in the Henan province, according to a Bank of America research note published on Monday.                                                                                                                                                                           , "Apple/Foxconn have the ability to relocate production to other areas in the short term provided that there is not a significantly higher duration of lockdown," the Bank of America economists wrote. "An increased period of shutdowns can cause ripple effects at other components that can create a shortfall in production."                                                                   , Apple did not immediately respond to a request for comment.                                                                                                                                                                                                                                                                                                                                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                         , Another manufacturing hub hit by new lockdown measures is Changchun, located in the northeast part of the country. The restrictions have affected Volkswagen AG, which halted production at its vehicle and component plants in the city from Monday through Wednesday, as well as Toyota, which halted production at its plant on Monday and will resume once the government gives the green light. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60741161?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-15 02:21:38 </td>
   <td style="text-align:left;"> Putin changes law on leased jets to keep them flying </td>
   <td style="text-align:left;"> Russia has implemented a new law making it harder for foreign aircraft leasing companies to repossess their planes in the face of Western sanctions.                                                                                     , The new law will allow foreign jets to be registered in Russia "to ensure the uninterrupted functioning of activities in the field of civil aviation".                                                                                   , Russian airlines have 515 jets leased from abroad worth about $10bn (£7.7bn).                                                                                                                                                            , Foreign owners have until 28 March to get them back from Russian companies before sanctions kick in.                                                                                                                                     , The move comes after Bermuda and Ireland, where nearly all foreign-leased planes operating in Russia are registered, said they were suspending certificates of airworthiness for those aircraft.                                         , The measure, signed into law by President Vladimir Putin, could circumvent that by bringing registration and certification of safety within Russia's borders and use the foreign aircraft to fly domestic routes across the vast country., Since the invasion of Ukraine on 24 February, Western companies have been terminating leases and asking for planes to be returned.                                                                                                       , The majority of international air routes out of Russia are not being flown and many countries, including the UK, have banned Russia's national airline Aeroflot from flying in their airspace.                                           , Hundreds of foreign-owned aircraft remain in Russia. To comply with sanctions, leasing companies are trying to get them back. But that is looking highly unlikely.                                                                       , If Russia does hang onto these aircraft - collectively worth billions of dollars - they will be able to continue flying, in Russia and a handful of former Soviet republics at least.                                                    , But it's one thing to steal aircraft, it's quite another to keep them operating for any length of time.                                                                                                                                  , Airbus and Boeing cannot supply spare parts, so when something needs to be replaced it will have to be taken from another plane, or be manufactured by a third party.                                                                    , That has serious safety implications. It will also make it virtually impossible to insure those planes outside Russia. Servicing is also a concern - many aircraft are flown elsewhere for maintenance.                                  , And when the crisis is over there will be a huge bill to pay.                                                                                                                                                                            , If aircraft are not maintained properly, their value will plummet. So even if lessors get them back, they will demand compensation.                                                                                                      , International aviation is an international business, and you have to play by the rules.                                                                                                                                                  , Russia could decide to thumb its nose at the rest of the world now. But one day it will want to rejoin the club - and the conditions for rejoining could be very harsh.                                                                  , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                   , Cat Deeley and Edith Bowman are best friends - here is their story                                                                                                                                                                       , A failing witchfinder and his suspect find themselves on a hellish road trip...                                                                                                                                                          , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/business-confidence </td>
   <td style="text-align:left;"> 2022-03-15 02:21:27 </td>
   <td style="text-align:left;"> Brazil Business Confidence Extends Decline </td>
   <td style="text-align:left;"> The industry confidence indicator in Brazil fell by 0.4 points from the prior month to 55.4 in March of 2022, the lowest reading since April of 2021 but remaining above 50 for the 20th consecutive month, indicating that firms remain in a positive mood. Sentiment regarding the conditions of the Brazilian economy deteriorated (49.1 vs 48.9 in February), while that of respondents’ businesses improved (47.1 vs 46.1). At the same time, optimism for the next six months declined both for the Brazilian economy (54.4 vs 54.8) and respondents’ businesses (60.8 vs 61.4). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/14/heres-everything-the-fed-is-expected-to-do-at-its-meeting-this-week.html </td>
   <td style="text-align:left;"> 2022-03-15 02:21:18 </td>
   <td style="text-align:left;"> Here's everything the Federal Reserve is expected to do at its meeting this week </td>
   <td style="text-align:left;"> , The Federal Reserve this week faces the monumental challenge of starting to undo its massive economic help at a time when conditions are far from ideal.                                                                                                                                                                                                                                                                               , In the midst of a geopolitical crisis in Ukraine, an economy that is off to a slow start and a stock market in a state of tumult, the Fed is widely expected to start raising interest rates following the conclusion Wednesday of its two-day meeting.                                                                                                                                                                                , Those three elements pose a daunting challenge, but it's soaring inflation that the Fed will focus on most when its meeting starts Tuesday.                                                                                                                                                                                                                                                                                            , "The economic outlook supports the Fed's current plans to boost the federal funds rate in March and to begin to reduce their balance sheet over the summer," wrote David Kelly, chief global strategist for JPMorgan Funds. "However, there [are] a number of areas of uncertainty which should make them a little more cautious in tightening."                                                                                       , The Federal Open Market Committee meeting will be focusing on more than a solitary interest rate hike, however. There also will be adjustments to the economic outlook, projections for the future path of rates, and likely a discussion about when the central bank can start reducing its bond portfolio holdings.                                                                                                                  , Here's a look at how each will play out, according to the prevailing views on Wall Street:                                                                                                                                                                                                                                                                                                                                             , Markets have no doubt the Fed will enact an increase of a quarter-percentage point, or 25 basis points, at this meeting. Because the central bank generally doesn't like to surprise markets, that's almost certainly what will happen.                                                                                                                                                                                                , Where the committee goes from there, however, is hard to tell. Members will update their projections through the "dot plot" — in which each official plots one dot on a grid to show where they think rates will go this year, the following two years and the longer range.                                                                                                                                                           , "The '25' is a given. What matters most is what comes after," said Simona Mocuta, chief economist at State Street Global Advisors. "A lot can happen between now and the end of the year. The uncertainty is super high. The trade-offs have worsened considerably."                                                                                                                                                                   , Current pricing indicates the equivalent of seven total increases this year — or one at each meeting — a pace Mocuta thinks is too aggressive. However, traders are split evenly over whether the FOMC will hike by 25 or 50 basis points in May should inflation — currently at its highest level since the early 1980s — continue to push higher. A basis point is equal to 0.01%.                                                   , From a market perspective, the key assessment will be whether the hike is "dovish" — indicative of a cautious path ahead — or "hawkish," in which officials signal they are determined to keep raising rates to fight inflation even if there are some adverse effects on growth.                                                                                                                                                      , "We think the message around the rate hike has to be at least somewhat hawkish. The real question is whether the Fed is carefully hawkish or aggressively hawkish, and whether the meeting springs any surprises or not," wrote Krishna Guha, head of central bank strategy for Evercore ISI. "Our call is that the Fed will be carefully hawkish and will avoid springing any surprises that might add to uncertainty and volatility.", Regardless of exactly how it goes, the dot plot will see substantial revisions from the last update three months ago, in which members penciled in just three hikes this year and about six more over the next two years. The longer run, or terminal rate, also could get boosted up from the 2.5% projection.                                                                                                                        , The dot plot is part of the Summary of Economic Projections (SEP) , a table updated quarterly that also includes rough estimates for unemployment, gross domestic product and inflation.                                                                                                                                                                                                                                               , In December, the committee's median expectation for inflation, as gauged by its core preferred personal consumption expenditures price index, pointed to inflation in 2022 running at 2.7%. That figure obviously vastly underestimated the trajectory of inflation, which by February's core PCE reading is up 5.2% from a year ago.                                                                                                  , Wall Street economists expect the new inflation outlook to bump up the full-year estimate to about 4%, though gains in subsequent years are expected to move little from December's respective projections of 2.3% and 2.1%.                                                                                                                                                                                                           , Still, the sharp upward revision to the 2022 figure "should keep Fed officials focused on the need to respond to too-high inflation with tighter policy settings, especially against a backdrop of strong (if now more uncertain) growth and an historically tight labor market," Citigroup economist Andrew Hollenhorst wrote in a Monday note.                                                                                       , Economists figure there also will be adjustments to this year's outlook for GDP, which could be slowed by the war in Ukraine, explosive inflation and tightening in financial conditions. December's SEP pointed to GDP growth of 4% this year; Goldman Sachs recently lowered its full-year outlook to just 2.9%. The Atlanta Fed's GDPNow gauge is tracking first-quarter growth of just 0.5%.                                       , "The war has pushed the Fed staff's geopolitical risk index to the highest level since the Iraq War," Goldman economist David Mericle said in a note over the weekend. "It has already raised food and energy prices and it threatens to create new supply chain disruptions as well."                                                                                                                                                 , The Fed's December projection for unemployment this year was 3.5%, which could be tweaked lower considering the February rate was 3.8%.                                                                                                                                                                                                                                                                                                , Outside the questions over rates, inflation and growth, the Fed also is expected to discuss when it will start paring the bond holdings on its nearly $9 trillion balance sheet. To be sure, the central bank is not expected to take any firm action on this issue this week.                                                                                                                                                         , The bond-buying program, sometimes called quantitative easing, will wind down this month with a final round of $16.5 billion in mortgage-backed securities purchases. As that ends, the FOMC will start to chart the way it will allow the holdings to start reducing, a program sometimes conversely called quantitative tightening.                                                                                                  , "Balance sheet reduction will likely be discussed but increased uncertainty makes us think formal normalization principles will be announced in May or June," Citi's Hollenhorst said.                                                                                                                                                                                                                                                 , Most Wall Street estimates figure the Fed will allow about $100 billion in bond proceeds to roll off each month, rather than being reinvested in new bonds as is currently the case. That process is expected to start in the summer, and Fed Chair Jerome Powell likely will be asked to address it during his post-meeting news conference.                                                                                          , Powell's Q&amp;A with the press sometimes moves markets more than the actual post-meeting statement. Mocuta, the State Street economist, said given that Fed policy acts with a lag, generally considered to be six months to a year, Powell should focus more on the future rather than the present.                                                                                                                                      , "The question remains, where are you going to be in the middle of 2023?" she said. "How is inflation, how is growth going to look then? This is the reason I think the Fed should be more dovish and should communicate that."                                                                                                                                                                                                         , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                 , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                 , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                       , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                       , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                     , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-prices-settle-lower-initial/story.aspx?guid={4F6CC898-0AB8-4A62-BD57-DAA1D3837DE0}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-15 01:37:57 </td>
   <td style="text-align:left;"> Gold prices settle lower as 'initial shock' of Russian invasion wears off  - MarketWatch </td>
   <td style="text-align:left;"> Gold futures settled lower on Monday, with prices down a second straight session to their lowest finish since March 3. "It looks like precious metals, as well as other commodities, have got past their initial shock at Russia's invasion," Adrian Ash, director of research at BullionVault, told MarketWatch. The rally in most Western stock markets agrees that despite the "horror of Putin's campaign, this isn't [World War 3]. Not yet." April gold 
        GCJ22,
        -0.74%
       fell $24.20, or 1.2%, to settle at $1,960.80 an ounce. , Apple Inc. component supplier Foxconn Technology Co. will temporarily shut down its operations in Shenzhen, China, amid a surge in COVID-19 cases.                                                                                                                                                                                                                                                                                                                                                                                                            , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/oil-profit-tax-khanna-whitehouse-russia-ukraine-war </td>
   <td style="text-align:left;"> 2022-03-15 01:36:59 </td>
   <td style="text-align:left;"> Dems push plan to tax oil companies' profits, send checks to Americans during Russia-Ukraine price spike </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines for March 14.                                                                                                                                                                                                                                                                                                                                                                                               , Rep. Ro Khanna and Sen. Sheldon Whitehouse are pushing a bill they say will help bring relief from high gas prices to Americans – as energy industry critics argue it would do the exact opposite.                                                                                                                                                                                                                                                         , The proposal, which comes as Russia's war on Ukraine delivers a shock to global energy prices, is called the "Big Oil Windfall Profits Tax." According to Khanna, D-Calif., and Whitehouse, D-R.I., the bill would levy a tax on oil barrels sold by large producers "equal to 50 percent of the difference between the current price of a barrel of oil and the pre-pandemic average price per barrel between 2015 and 2019."                             , The money from that tax would be sent to consumers as a quarterly rebate, according to a description of the bill, with a cutoff for single people making $75,000 or more and families making $150,000 or more.                                                                                                                                                                                                                                             , WASHINGTON, DC - JUNE 29: Rep. Ro Khanna (D-CA) speaks at an "End Fossil Fuel" rally near the U.S. Capitol on June 29, 2021 in Washington, DC. Organized by Our Revolution, demonstrators called on Congress to take action in ending fossil fuel subsidie (Anna Moneymaker/Getty Images / Getty Images)                                                                                                                                                   , MANCHIN OPPOSES SARAN BLOOM RASKIN FOR FED OVER ENERGY COMMENTS, DASHING PROSPECTS OF BIDEN NOMINEE                                                                                                                                                                                                                                                                                                                                                        , "This is a bill to reduce gas prices and hold Big Oil accountable. As Russia’s invasion of Ukraine sends gas prices soaring, fossil fuel companies are raking in record profits," Khanna said. "These companies have made billions and used the profits to enrich their own shareholders while average Americans are hurting at the pump."                                                                                                                 , The tax would only affect to companies that extract over 300,000 barrels of oil per day, applying to oil extracted both domestically and worldwide, according to a press release from Khanna's office. That threshold would exempt "[s]maller companies accounting for roughly 70 percent of the domestic production… so oil giants like Exxon Mobil and Chevron cannot simply gouge consumers further without the threat of losing market share," it said., "We’ve seen this script before, and we cannot allow the fossil fuel industry to once again collect a massive windfall by taking advantage of an international crisis," Whitehouse said. A press release from Whitehouse and Khanna said the increase in gas prices, "is not justified by increases in the cost of domestic production, but is driven by international markets controlled by fossil fuel cartels."                                          , Sen. Sheldon Whitehouse, D-R.I., speaks during the confirmation hearing for Supreme Court nominee Amy Coney Barrett before the Senate Judiciary Committee, Tuesday, Oct. 13, 2020, on Capitol Hill in Washington. (AP Photo/Patrick Semansky)                                                                                                                                                                                                              , MANCHIN TO CHIEF ENERGY REGULATOR HOLDING UP NATURAL GAS PROJECTS: ‘DO YOUR DAMN JOB’                                                                                                                                                                                                                                                                                                                                                                      , Energy industry representatives, however, are pushing back against the proposal, arguing that it may have the exact opposite of its intended effect.                                                                                                                                                                                                                                                                                                       , "Policies like a so-called windfall profits tax are misguided and would likely backfire by further driving up energy costs for American families and businesses," American Exploration and Production Council CEO Anne Bradbury said.                                                                                                                                                                                                                      , "We believe that the solution to rising energy prices should be clear to our nation’s leaders: support domestic production of oil and natural gas and permit the pipelines and infrastructure needed to safely move energy to customers," Bradbury added.                                                                                                                                                                                                  , Oil well equipment on the Forth Berthold Indian Reservation near New Town, N.D. MHA Nation produces about a quarter of North Dakota's annual oil output. (Tyler Olson/FOX Business)                                                                                                                                                                                                                                                                        , "The American people are looking for solutions, not finger pointing," American Petroleum Institute senior vice president of policy, economics and regulatory affairs Frank Macchiarola said. "The price at the pump that Americans are currently paying is a function of increased demand and lagging supply combined with the geopolitical turmoil resulting from Russia’s aggression in Ukraine."                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                , Macchiarola added: "Lawmakers should focus on policies that increase US supply to help mitigate the situation rather than political grandstanding that does nothing but discourage investment at a time when it’s needed the most."                                                                                                                                                                                                                        , Energy industry insiders and advocates at the CERAWeek by S&amp;P Global conference in Houston last week repeatedly said the U.S. should move toward policies that encourage energy investment, in order to increase domestic production.                                                                                                                                                                                                                      , Sen. Lisa Murkwoski, R-Alaska, said President Biden needs to show tangible movement in that direction otherwise U.S. energy output won't increase anytime soon.                                                                                                                                                                                                                                                                                            , "The president needs to get up there, and not only say it, but then direct his secretary of the interior: Where's that five-year plan? Direct Secretary Granholm: Get these LNG export permits out the door," Murkowski said. "Let's move on this. So let's just not talk at an energy conference." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 01:32:00 </td>
   <td style="text-align:left;"> Wall Street Pares Early Gains </td>
   <td style="text-align:left;"> US stocks failed to maintain earlier gains and swung lower on Monday, as investors monitored the continued volatility in commodity prices amid security negotiations between the Russian and Ukrainian delegations. The Dow erased its 450 point gain, while the S&amp;P 500 and the Nasdaq were down 0.6% and 1.9%, respectively. In the latest developments, Russian forces allowed some of the people trapped in Mariupol to leave as negotiators from both countries paused peace talks until tomorrow, even though Russia intensified fighting in Kyiv overnight. Aside from Ukraine headlines, prospects of higher interest rates kept sentiment subdued. The US central bank is expected to raise its target fed funds rate by 25 basis points to tame inflation that is already running at multi-year highs. Investors will also keep an eye on new forecasts for rates, inflation and the economy, given the uncertainty from the Russia-Ukraine conflict. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/manchin-says-he-cant-support/story.aspx?guid={6748A8C7-A7EA-457B-A404-CF67969899A6}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-15 01:23:14 </td>
   <td style="text-align:left;"> Manchin says he can't support Biden Fed nominee Raskin - MarketWatch </td>
   <td style="text-align:left;"> Key Democratic Sen. Joe Manchin of West Virginia said in a statement on Monday that he's "unable to support" the nomination of Sarah Bloom Raskin by President Joe Biden to serve on the Federal Reserve's Board of Governors. "Her previous public statements have failed to satisfactorily address my concerns about the critical importance of financing an all-of-the-above energy policy to meet our nation's critical energy 
        XLE,
        -2.99%
       needs," said the statement, which was posted on Manchin's Twitter account., Men's suits have been officially banished from the basket of goods and services in the country that invented them.                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 01:12:00 </td>
   <td style="text-align:left;"> South African Stocks End at Over 2-Month Low </td>
   <td style="text-align:left;"> The JSE FTSE All Share index plunged 2.4% to close at 71,904 on Monday, its lowest since December 24th, dragged down by tech Naspers and its subsidiary Prosus, which owns a 29% stake in Tencent, following reports that the Chinese technology giant faces a potential record fine for violations of some central bank regulations by its WeChat Pay mobile network. At the same time, investors braced for the highly-anticipated Federal Reserve's meeting later in the week, at which the central bank is expected to raise rates for the first time since December 2018. Domestically, state-owned power utility Eskom has warned that the power system remains under constraint today and on Tuesday despite having recovered sufficiently to suspend all load shedding. On the corporate front, Absa, South Africa’s fourth-largest bank by market value, reported an almost threefold rise in its annual profit and a significant rebound in return on equity as credit impairments improved. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/14/stocks-making-the-biggest-moves-midday-alibaba-apple-and-more.html </td>
   <td style="text-align:left;"> 2022-03-15 01:07:50 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Alibaba, Apple, Robinhood and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                                                                                                     , Alibaba, Baidu, JD.com — Shares of the China-based companies fell after JPMorgan Chase downgraded the stocks to underweight. Their stocks tumbled more than 10%, 8% and 10%, respectively, amid a new shutdown in Shenzhen and renewed U.S. delisting fears.                                                                                                                                                                                                                    , Apple — The company's stock fell 2.7% as one of the its biggest suppliers in China said it would pause operations in Shenzhen amid a new Covid-19 lockdown. KeyBanc also reiterated its outperform rating on shares of the technology giants and said that iPhone demand remains strong.                                                                                                                                                                                        , Occidental Petroleum, Chevron – The energy companies fell 4% and 2.5% after analysts at Morgan Stanley downgraded the stocks to equal-weight from overweight. The bank noted that while both companies have outperformed peers in recent months, they currently offer less attractive relative valuations. Oil prices also moved lower Monday.                                                                                                                                  , Ford — Shares of the auto company dipped about 2% after Jefferies reiterated its hold rating and lowered its price target. The Wall Street firm slashed its price projection on Ford shares to $18 from $20, citing worries about "a stagflationary environment of higher input costs and continued supply constraints."                                                                                                                                                        , Tyson Foods — The poultry company's stock fell 2.4% after BMO Capital markets downgraded the it to market perform from outperform. BMO said it's concerned about "underlying fundamentals" in beef.                                                                                                                                                                                                                                                                             , Nike — Shares for the sports apparel giant tumbled 4%, furthering losses this year as geopolitical risks continue to weigh on the retailer. On Monday, UBS reiterated a buy rating for Nike, but analysts noted that its business in China is not recovering as fast as the firm expected. Last year, Chinese consumers boycotted the American company, after several companies in the West refused to source cotton from the Xinjiang province, calling out forced labor issues, Peloton — The at-home fitness stock lost more than 4% after Morgan Stanley initiated coverage of it with an equal weight rating, saying it lacks near-term visibility for Peloton. Still, it said it leans bullish as its price target of $32 implies about 50% upside.                                                                                                                                                                                                         , Papa John's — Shares rose more than 2% after Loop Capital reiterated its buy rating on the pizza chain. The firm said Papa John's comparable store sales accelerated and could "improve even further soon."                                                                                                                                                                                                                                                                     , Robinhood — Shares fell 3% after Goldman Sachs reiterated its neutral buy rating, citing market concerns about the company's "ability to grow the business and scale into proﬁtability." The company could be poised for re-rating if it can "translate its new product momentum into a return to revenue and user growth," the analysts wrote.                                                                                                                                 , Netflix — The streaming giant's stock fell nearly 3%, reaching its lowest level since March 2020. Netflix shares have struggled recently amid rising competition from other media companies.                                                                                                                                                                                                                                                                                    , — CNBC's Tanaya Macheel, Yun Li, Hannah Miao and Sarah Min contributed reporting                                                                                                                                                                                                                                                                                                                                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                          , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                          , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                              , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/world-europe-60736185?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-15 01:01:57 </td>
   <td style="text-align:left;"> Roman Abramovich: New evidence highlights corrupt deals </td>
   <td style="text-align:left;"> A BBC investigation has uncovered new evidence about the corrupt deals that made Roman Abramovich's fortune.                                                                                                                                                              , The Chelsea owner made billions after buying an oil company from the Russian government in a rigged auction in 1995.                                                                                                                                                      , Mr Abramovich paid around $250m (£190m) for Sibneft, before selling it back to the Russian government for $13bn in 2005.                                                                                                                                                  , His lawyers say there is no basis for alleging he has amassed very substantial wealth through criminality.                                                                                                                                                                , The Russian billionaire was sanctioned by the UK government last week because of his links to Russian President Vladimir Putin.                                                                                                                                           , Mr Abramovich's assets have been frozen and he has been disqualified as a director of Chelsea Football Club.                                                                                                                                                              , The Russian billionaire has already admitted in a UK court that he made corrupt payments to help get the Sibneft deal off the ground.                                                                                                                                     , He was being sued in London by his former business associate Boris Berezovsky in 2012.                                                                                                                                                                                    , Mr Abramovich won the case, but he described in court how the original Sibneft auction was rigged in his favour and how he gave Mr Berezovsky $10m to pay off a Kremlin official.                                                                                         , BBC Panorama has obtained a document that is thought to have been smuggled out of Russia.                                                                                                                                                                                 , The information was given to the programme by a confidential source, who says it was secretly copied from files held on Mr Abramovich by Russian law enforcement agencies.                                                                                                , The BBC cannot verify that, but checks with other sources in Russia have backed up many of the details in the five-page document.                                                                                                                                         , The document says that the Russian government was cheated out of $2.7bn in the Sibneft deal - a claim supported by a 1997 Russian parliamentary investigation. The document also says that the Russian authorities wanted to charge Mr Abramovich with fraud.             , It says: "The Dept. of Economic Crimes investigators came to the conclusion that if Abramovich could be brought to trial he would have faced accusations of fraud… by an organised criminal group."                                                                       , Watch Panorama                                                                                                                                                                                                                                                            , Roman Abramovich's Dirty Money is on BBC One, Monday 14 March, at 20:00 GMT and on BBCiPlayer afterwards                                                                                                                                                                  , Panorama tracked down Russia's former chief prosecutor, who investigated the deal in the 1990s.                                                                                                                                                                           , Yuri Skuratov did not know about the secret document, but he independently confirmed many of the details about the Sibneft sale.                                                                                                                                          , Mr Skuratov told the programme: "Basically, it was a fraudulent scheme, where those who took part in the privatisation formed one criminal group that allowed Abramovich and Berezovsky to trick the government and not pay the money that this company was really worth.", The document also suggests Mr Abramovich was protected by former Russian President Boris Yeltsin.                                                                                                                                                                         , It says law enforcement files on Mr Abramovich were moved to the Kremlin and that an investigation by Mr Skuratov was stopped by the president.                                                                                                                           , The document says: "Skuratov was preparing a criminal case for the confiscation of Sibneft on the basis of the investigation of its privatisation. The investigation was stopped by President Yeltsin … Skuratov was dismissed from his office."                          , Mr Skuratov was sacked after the release of a sex tape in 1999. He says it was a stitch-up to discredit him and his investigation.                                                                                                                                        , He said: "This whole thing was obviously political, because in my investigations I came very close to the family of Boris Yeltsin, including via this investigation of the Sibneft privatisation."                                                                        , Mr Abramovich remained in the Kremlin inner circle when Vladimir Putin came to power in 2000.                                                                                                                                                                             , The document contains details of another rigged auction two years later, involving a Russian oil company called Slavneft.                                                                                                                                                 , Mr Abramovich formed a partnership with another firm to buy Slavneft, but a rival Chinese company was planning to bid almost twice as much.                                                                                                                               , Many powerful people - from the Kremlin to the Russian parliament - would have stood to lose out if the Chinese won the auction.                                                                                                                                          , The document says that a member of the Chinese delegation was kidnapped when they arrived in Moscow for the auction.                                                                                                                                                      , "CNPC, Chinese company, a very strong competitor, had to withdraw from the auction after one of its representatives was kidnapped upon arrival at Moscow Airport and was released only after the company declared its withdrawal."                                        , The kidnapping story is backed up by independent sources who did not know about the document.                                                                                                                                                                             , Vladimir Milov was Russia's deputy energy minister in the run up to the Slavneft sale. He didn't comment on the kidnapping story, but he said senior political figures had already decided that Mr Abramovich's partnership would win the auction.                        , "I said, look, the Chinese want to come in and they want to pay a much bigger price. They say it doesn't matter, shut up, none of your business. It's already decided. Slavneft goes to Abramovich, the price is agreed. The Chinese will be dragged out somehow."        , There is no suggestion that Mr Abramovich knew anything about the kidnapping plot, or played any part in it.                                                                                                                                                              , His lawyers told the BBC the kidnap claim "is entirely unsubstantiated" and he has "no knowledge of such incident".                                                                                                                                                       , Different factions had been fighting for control of Slavneft and there was widespread opposition to the Chinese bid.                                                                                                                                                      , Whatever the reason for the Chinese withdrawal, Mr Abramovich's partnership had the only bid left on the table. And they bought Slavneft at a knockdown price.                                                                                                            , Mr Abramovich's lawyers say allegations of corruption in the Slavneft and Sibneft deals are false, and he denies he was protected by Mr Yeltsin.                                                                                                                          , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                    , Cat Deeley and Edith Bowman are best friends - here is their story                                                                                                                                                                                                        , A failing witchfinder and his suspect find themselves on a hellish road trip...                                                                                                                                                                                           , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/14/one-third-of-job-switchers-took-a-pay-cut-for-better-work-life-balance.html </td>
   <td style="text-align:left;"> 2022-03-15 01:01:19 </td>
   <td style="text-align:left;"> One-third of job switchers took a pay cut for better work-life balance. How to prepare to live on a lower salary </td>
   <td style="text-align:left;"> , As the Great Resignation continues, employees are rethinking salaries, work-life balance and flexibility in their new careers.                                                                                                                                                                                                                                                                                                                                                                                       , Some are willing to take a pay cut in exchange for a better schedule.                                                                                                                                                                                                                                                                                                                                                                                                                                                , One-third of workers who switched jobs during the pandemic took less pay in exchange for better work-life balance, according to a survey by Prudential. And about 20% of workers said they would take a 10% pay cut if it meant they could work for themselves or have better hours.                                                                                                                                                                                                                                 , Many workers also want job security and would trade higher pay to work for a company long-term. The survey found that 56% said they had or would consider prioritizing stability over a bigger salary.                                                                                                                                                                                                                                                                                                               , More from Invest in You:How a three-month paid sabbatical can help with employee retentionHow this small business founder pivoted her strategy during the pandemicFive things every entrepreneur should do when starting a company                                                                                                                                                                                                                                                                                   , That could also lead to less paid overtime. To be sure, many people who switched jobs have seen increases in take-home pay. A survey from The Conference Board found that about one-third of workers who left jobs during the pandemic are making 30% more in their new roles. However, about 27% who switched jobs said pay was the same or less in their new job.                                                                                                                                                  , Of course, taking a pay cut will directly affect your finances and may not be advisable right away, according to Tania Brown, an Atlanta-based certified financial planner and founder of FinanciallyConfidentMom.com.                                                                                                                                                                                                                                                                                               , If you're weighing a job where you will make less money, there are a few things you need to consider beforehand, she said.                                                                                                                                                                                                                                                                                                                                                                                           , First, ask yourself why you want to leave your current job, she said. Are you burned out? Will a different job or career be more fulfilling? Are you planning to move?                                                                                                                                                                                                                                                                                                                                               , Contemplating the answers to these questions will help ensure you don't make a rash decision you'll later regret, said Brown.                                                                                                                                                                                                                                                                                                                                                                                        , "Emotions have no logic, and you're trying to make a math decision based on emotion," Brown said. "It's just not going to turn out."                                                                                                                                                                                                                                                                                                                                                                                 , Additionally, if you're only a few months away from paying off debts or hitting a similar financial goal, you may want to hold off.                                                                                                                                                                                                                                                                                                                                                                                  , Plus, you may realize you don't want to leave your job, but instead would like more flexibility or a change in your role. If that is the case, now is a great time to ask for a different schedule, to take on different responsibilities or to try to introduce other flexibilities into your job, said Anita Samojednik, CEO of Paro, which provides accounting and finance solutions for businesses, focused on workers who do so-called mental tasks for a living — such as programmers, pharmacists and lawyers., She said she's seen many people dip their toes into freelancing in addition to a full-time job to test the waters of a new gig or becoming their own boss.                                                                                                                                                                                                                                                                                                                                                           , If you discover that switching jobs is truly what you want, then you have some math to do, Brown said.                                                                                                                                                                                                                                                                                                                                                                                                               , That includes a deep dive into your current budget to see if you can achieve your objectives on a smaller income.                                                                                                                                                                                                                                                                                                                                                                                                    , Brown suggests a trial period of a few months where you try to see if you can meet your goals on smaller take-home pay. That test run could help you decide if a pay cut is right for you.                                                                                                                                                                                                                                                                                                                           , You should also think about how making less will affect your long-term goals, Brown said. If you're saving up for a house or plan on having a baby, how will your new income change the timelines on those milestones? If it will take longer, is it worth it for you to wait?                                                                                                                                                                                                                                       , If you're part of a family, you should also consult the other members in your household before making your move. That means talking with your spouse and children about what changes would take place, such as fewer trips or less money for extra activities — and deciding if it works for everyone.                                                                                                                                                                                                               , "This has to be a family decision because your decision is impacting everyone in the household," said Brown.                                                                                                                                                                                                                                                                                                                                                                                                         , SIGN UP: Money 101 is an 8-week learning course to financial freedom, delivered weekly to your inbox. For the Spanish version Dinero 101, click here.                                                                                                                                                                                                                                                                                                                                                                , CHECK OUT: The 'old convention' for saving in retirement won't work anymore, expert says: Here's how to shift your strategy with Acorns+CNBC                                                                                                                                                                                                                                                                                                                                                                         , Disclosure: NBCUniversal and Comcast Ventures are investors in Acorns.                                                                                                                                                                                                                                                                                                                                                                                                                                               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                               , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                                     , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                                   , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 00:58:00 </td>
   <td style="text-align:left;"> Madrid Stocks Close at Near 2-Week High </td>
   <td style="text-align:left;"> The Ibex 35 index closed 1.1% up at 8,234 on Monday, its highest since March 2nd, as investors monitored developments around peace talks between Russia and Ukraine and awaited rate hike announcements by the US Fed and the Bank of England later in the week. On the corporate front, Spain’s technology and telecommunications sector and banks were among the top performers. Domestically, Spanish Prime Minister Pedro Sánchez on Sunday announced his government will roll out tax reliefs to alleviate the economic impact of Russia’s invasion war in Ukraine on the Spanish economy’s most affected industries, with plans to also speed up renewable energy projects. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/14/business/manchin-raskin-fed.html </td>
   <td style="text-align:left;"> 2022-03-15 00:53:54 </td>
   <td style="text-align:left;"> Manchin Won’t Support Raskin for the Federal Reserve - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Republicans had already opposed Sarah Bloom Raskin as the Federal Reserve’s top bank cop.                                                                                                                                                                                                                                                                                                                                                                       , By Emily Cochrane and Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                            , Senator Joe Manchin III, a key centrist Democrat, announced on Monday that he would not support Sarah Bloom Raskin for a top position on the Federal Reserve, potentially dooming her chances for confirmation as Republicans show little appetite for placing a supporter of stricter bank regulation into the powerful role.                                                                                                                                  , Without Republican support in the evenly divided Senate, Democrats need all 50 senators who caucus with their party to vote in favor of Ms. Raskin for her to become the Federal Reserve’s vice chair for supervision. Republicans have so far stonewalled her nomination in committee, raising concerns about her position on climate regulation and her work in the private sector.                                                                           , Mr. Manchin, a West Virginian who has close ties to the fossil fuel industry and has rejected much of President Biden’s climate agenda, cited her statements on climate and energy policy, and pointedly noted that the board “is not an institution that should politicize its critical decisions.”                                                                                                                                                            , “Her previous public statements have failed to satisfactorily address my concerns about the critical importance of financing an all-of-the-above energy policy to meet our nation’s critical energy needs,” Mr. Manchin said in a statement. “I have come to the conclusion that I am unable to support her nomination to serve as a member of the Federal Reserve Board.”                                                                                      , He added that “the Federal Reserve Board must remain hyper-focused on ending the inflation taxes hurting working families and getting more workers off the sidelines and back into the economy.”                                                                                                                                                                                                                                                                , Without his support, Ms. Raskin, a former Fed governor and Obama administration official, is unlikely to secure the votes needed to clear the Senate unless a Republican breaks ranks and votes to back her.                                                                                                                                                                                                                                                    , “Manchin’s decision is very likely to doom Raskin’s nomination,” Ian Katz, managing director at Capital Alpha Partners, wrote in reaction to the news. “We wouldn’t be surprised if Raskin withdraws in the next week or two — perhaps sooner.”                                                                                                                                                                                                                 , The White House vowed on Monday to press ahead with her nomination, with a spokesman emphasizing Ms. Raskin’s qualifications and outside support.                                                                                                                                                                                                                                                                                                               , “She has earned widespread support in the face of an unprecedented, baseless campaign led by oil and gas companies that sought to tarnish her distinguished career,” said the spokesman, Chris Meagher. “We are working to line up the bipartisan support that she deserves, so that she can be confirmed by the Senate for this important position.”                                                                                                           , Lawmakers on the Senate Banking Committee have been at loggerheads over Ms. Raskin’s nomination. Republicans have boycotted a hearing that would let committee Democrats advance an entire slate of key banking nominations, including the renomination of Jerome H. Powell, the Fed chair, over objections to Ms. Raskin’s selection.                                                                                                                          , Senator Patrick J. Toomey of Pennsylvania, the top Republican on the committee, emphasized his opposition to Ms. Raskin and her past comments on climate regulation in a statement on Monday.                                                                                                                                                                                                                                                                   , “As we’ve repeatedly said, Republican members of the Banking Committee are willing to vote on the other four Fed nominees,” Mr. Toomey said. Referring to Senator Sherrod Brown, Democrat of Ohio and the committee’s chair, he added, “I hope Chairman Brown will immediately move forward with scheduling a vote for this week.”                                                                                                                              , Republicans, in boycotting Ms. Raskin’s nomination, had specifically cited concerns about Ms. Raskin’s time on the board of directors of a financial technology firm. The company, Reserve Trust, secured a coveted account with the Fed — giving it access to services that it now prominently advertises — after Ms. Raskin reportedly called a central bank official to intervene on its behalf.                                                             , It is unclear how much Ms. Raskin’s involvement mattered in helping Reserve Trust secure the Fed account. But the episode has raised questions, because she previously worked at the Fed and because she made about $1.5 million from the stock she was given for her Reserve Trust work. Her own party regularly blasts the revolving door between regulators and financial firms.                                                                             , Republicans have demanded that Ms. Raskin provide more answers about what happened while she was on the company’s board, but she has largely said she cannot remember what happened, drawing lawmaker criticism. Mr. Toomey led his Republican colleagues in refusing to show up to vote on Ms. Raskin and the other Fed nominees until she provides more answers.                                                                                              , If she cannot secure all the Democratic votes, though, the issue is likely moot.                                                                                                                                                                                                                                                                                                                                                                                , “Now that it’s clear Sarah Bloom Raskin has no path to confirmation, it’s time for the Senate Banking Committee to proceed with the other four nominees, as committee Republicans have been pushing for weeks,” Senator Thom Tillis, Republican from North Carolina, wrote Monday on Twitter.                                                                                                                                                                   , Besides Mr. Powell, who goes by Jay, Mr. Biden has nominated Lael Brainard to be the Fed’s vice chair and two academic economists — Philip Jefferson and Lisa Cook — to be governors.                                                                                                                                                                                                                                                                           , “This effectively kills her nomination,” Tobin Marcus at Evercore ISI wrote after the news, adding that it “likely clears the way for Biden’s other Fed nominees — Jay Powell, Lael Brainard, Lisa Cook and Philip Jefferson — to advance and be confirmed.”                                                                                                                                                                                                    , The Senate has only ever confirmed one vice chair for supervision at the Fed, Randal K. Quarles, whom President Donald J. Trump nominated. Before Mr. Quarles, Daniel Tarullo, a Fed governor, unofficially served in the role for years. The position was created by the 2010 Dodd-Frank Act.                                                                                                                                                                  , The White House made it clear on Monday that it was still focused on finding Republican votes for Ms. Raskin’s nomination, and other prominent Democrats continued to hold out hope.                                                                                                                                                                                                                                                                            , “The way out is to get some Republicans to support her,” said Senator Elizabeth Warren of Massachusetts, who sits on the Banking Committee and has been a proponent of Ms. Raskin’s. “They all supported her the last two times she was nominated. She’s been at the Fed; she’s been at the Treasury.”                                                                                                                                                          , But the centrist Republican senators who might have been seen as likely sources of support for Ms. Raskin — including Senators Lisa Murkowski of Alaska and Susan Collins of Maine — said on Monday that they would not support her. Ms. Murkowski called her candidacy “flawed.” While Ms. Collins said she spoke to Ms. Raskin on Monday, she said “I think it is evident from Joe Manchin’s statement this morning that there is not a path forward for her.”, Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Resume Gains </td>
   <td style="text-align:left;"> The FTSE MIB index gained 1.7% to close at 23,427 on Monday, in line with its European peers, as investors monitored the developments of the security negotiations between Kyiv and Moscow, ahead of monetary policy decisions by major central banks this week. Banks and commodity-backed stocks led the gains in Milan, led by Buzzi Unicem (5%) and Bper Banca (4.1%), while energy shares fell nearly 1%, tracking lower oil prices. At the same time, Telecom Italia rallied 5% after the telecom said it would start formal talks with KKR &amp; Co. to assess and negotiate the private equity firm’s EUR 10.8 billion bid offer, nearly four months after the initial approach. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 00:47:00 </td>
   <td style="text-align:left;"> European Stocks Rally on Ceasefire Talks </td>
   <td style="text-align:left;"> All major European stock indices rose on Monday, with Germany’s DAX adding more than 2% and the pan-European Stoxx 600 gaining 1.2%, on comments from both Ukrainian and Russian ministers that peace talks are progressing well despite Russian forces continued their military operations. Also, oil markets extended losses from the previous week and were down more than 6%, easing inflation worries. Ukraine said it had begun hard talks with Russia on a ceasefire, immediate withdrawal of troops and security guarantees. On the data front, Germany’s monthly wholesale price inflation eased 0.6pp to 1.7% in February. Meanwhile, investors await interest rate decisions by the US Fed and the Bank of England later in the week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 00:46:00 </td>
   <td style="text-align:left;"> French Stocks extend Gain for Second Consecutive Session </td>
   <td style="text-align:left;"> The CAC 40 ended 1.75% higher to close at 6,369.94 on Monday, extending gains for the second consecutive session amid hopes of diplomatic resolution to the Russia-Ukraine conflict as both countries reported progress in peace talks yesterday. Financials and automotive led the gains with 36 out of 40 stocks ending in the green. Among the individual stocks, Alstom, which is most exposed to both Russia and Ukraine added 5.2%. Besides this, other top gainers included Essilor Luxottica (+4.17%); BNP Paribas (+4.04%); and Danone (+4.04%). On the other hand, Sanofi dragged by 0.7% after the pharmaceutical group reported failure of its AMEERA-3 trial in the treatment of advanced breast cancer while arms maker,Thales plunged by 2.14% as hopes of peace talks raised expectations of lower military spending. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-03-15 00:45:00 </td>
   <td style="text-align:left;"> UK Stocks Start the Week Higher </td>
   <td style="text-align:left;"> The FTSE 100 closed 0.6% higher at 7,195 on Monday, in line with its European peers, benefiting from optimism over “hard” cease-fire talks in between the Russian and Ukrainian delegations, while investors weighed on lower commodity prices. Banks and insurers were among the strongest performers, led by Lloyds (5.2%) and Barclays (5.4%), as traders anticipate higher interest rates among major central banks this week. The Bank of England is poised to deliver a 25bps rate hike to 0.75% on Wednesday, while the Federal Reserve is also expected to hike its main rate. On the other hand, Rio Tinto shares dropped 2.5% after proposing to buy the remaining of Canadian Turquoise Hill, while British American Tobacco (1.9%) edged lower after decreasing its FY22 guidance as a result of its planned exit from Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-03-15 00:29:00 </td>
   <td style="text-align:left;"> Brazilian Real Weakens </td>
   <td style="text-align:left;"> The Brazilian real weakened to 5.11 per USD from the 8-month high of 4.99 touched on March 10th, as investors continued to monitor commodity prices amid the war in Ukraine ahead of policy decisions by major central banks this week. New negotiation rounds between Russia and Ukraine eased commodity prices slightly bringing down expectations of improvements in the Brazilian terms of trade. Meanwhile, the Central Bank of Brazil is expected to raise the Selic rate by 100bps on Wednesday, adding to the 875bps in rate hikes that took place since April last year. At the same time, the Federal Reserve is also expected to raise interest rates this week to combat inflation that currently runs at multi-decade highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/jpmorgan-coronavirus-unvaccinated-april </td>
   <td style="text-align:left;"> 2022-03-15 00:10:54 </td>
   <td style="text-align:left;"> JPMorgan ending mandatory COVID tests, hiring ban for unvaccinated employees </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines for March 14.                                                                                                                                                                                                                                                                                                                                                                                                                                                          , JPMorgan Chase says it will end its hiring ban on unvaccinated individuals beginning April 4.                                                                                                                                                                                                                                                                                                                                                                                                                         , GOLDMAN SACHS BECOMES FIRST WALL ST. FIRM TO EXIT RUSSIA                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Mandatory COVID-19 testing for unvaccinated employees, asking employees to report coronavirus infections, and associated contact tracing and notifications will also be discontinued on April 4. In addition, masking in its corporate offices will also be optional for both vaccinated and unvaccinated employees effective immediately.                                                                                                                                                                            , "Across the U.S., as we continue to see cases decline, restrictions lifted and more flexibility with daily activities, we are learning to live with COVID as part of our new normal," the bank said in a memo to employees reviewed by FOX Business. "The virus has shifted to cause less severe illness, there is now a high level of vaccine immunity and natural immunity from infection, and we are once again enjoying the benefits and energy that comes with being together in the office on a regular basis." , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , JPMorgan emphasized that it will continue to offer voluntary testing through complimentary home testing kits, require responses to be entered into its Vaccine Record Tool, and keep its current isolation and quarantine guidelines in place. New York City employees must continue to meet the company's vaccination requirements until the city lifts its order.                                                                                                                                                   , JPMorgan will end its hiring ban on unvaccinated individuals beginning April 4. Mandatory COVID-19 testing for unvaccinated employees, asking employees to report coronavirus infections and associated contact tracing and notifications will also be dis (Reuters/Mike Segar/Files)                                                                                                                                                                                                                                 , In addition, the bank urged individuals who are sick with COVID or who show symptoms of any other contagious illness to avoid coming into the office and to exercise good judgment and common sense in deciding whether to notify colleagues who have been in close contact.                                                                                                                                                                                                                                          , "As we have from the start, we will continue to monitor developments closely and will be prepared to reintroduce practices and protocols when and where needed," the memo added. "For instance – masking requirements may return if there is another spike in cases, or a variant begins to spread that causes severe illness in the general population. But this will only happen based on strict criteria or if mandated by state or local government authorities."                                                 , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , JPMorgan Chase and Goldman Sachs began calling their employees back to the office on Feb. 1. Meanwhile, Citigroup and Wells Fargo are planning to start bringing employees back to the office in mid-March. JPMorgan, Citigroup and Wells Fargo have all previously announced plans to adopt a hybrid work model to give their employees flexibility.                                                                                                                                                                 , A Wells Fargo spokesperson told FOX Business that, upon its full return to the office, mask wearing will be optional for fully vaccinated employees unless local restrictions apply. Meanwhile, unvaccinated Wells Fargo employees will be required to undergo regular testing and wear a mask at all times unless eating, drinking or alone in an enclosed room. Wells Fargo employees in all customer-facing retail locations are required to wear a mask, regardless of vaccination status.                        , Morgan Stanley requires vaccines in the majority of its corporate offices. As a result, masking is optional. As for its wealth management branch offices, masking is no longer required for those who are vaccinated. Unvaccinated employees in its wealth management branch offices continue to test and wear masks unless otherwise mandated.                                                                                                                                                                       , Representatives for Goldman Sachs and Citigroup did not immediately return FOX Business' request for comment on whether they would follow JPMorgan's lead on easing masking and COVID-19 testing policies for unvaccinated individuals. Citigroup said in January it would terminate unvaccinated employees unless they were granted an exemption.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/academy-sports-outdoors-shares/story.aspx?guid={01D04000-EA39-4A14-81BA-2A9F7C4DFB4D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-14 23:59:18 </td>
   <td style="text-align:left;"> Academy Sports &amp; Outdoors shares jump after news it's headed for the S&amp;P Small Cap 600 Index - MarketWatch </td>
   <td style="text-align:left;"> Academy Sports &amp; Outdoors Inc. 
        ASO,
        +8.65%
       shares jumped nearly 10% on Monday after it was announced the retailer would join the S&amp;P Small Cap 600 Index 
        SML,
        -1.17%,
       effective prior to the opening of Wednesday trading. Academy Sports replaces Kraton Corp. 
        KRA,
        +0.02%,
       which is being acquired by DL Chemical Co., Ltd. Academy recently announced its expansion into new markets, including Virginia. Academy stock has run up 35.4% over the last year. The S&amp;P Small Cap 600 is down 8.7%. And the S&amp;P 500 index 
        SPX,
        -0.74%
       is up 6.6% for the period.
, A selloff from last week extends into Monday amid Covid-19 lockdowns and new regulatory threats.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/14/jpmorgan-rolls-back-covid-precautions-as-us-cases-drop.html </td>
   <td style="text-align:left;"> 2022-03-14 23:49:07 </td>
   <td style="text-align:left;"> JPMorgan rolls back Covid precautions including masking and mandatory testing as U.S. cases drop </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , JPMorgan Chase on Monday told its U.S. employees that the bank was rolling back several coronavirus precautions as cases continue to drop.                                                                                                                                                                                                                                                                                                                                                              , Wearing a mask at corporate buildings will be "completely voluntary" for workers starting today, regardless of their vaccination status, the bank said in the memo. Next month, the bank will stop mandatory testing for unvaccinated workers and will open up hiring to the unvaccinated, it added.                                                                                                                                                                                                    , Two years after sending employees home en masse in the early days of the pandemic, corporations are preparing for the return to office life. Coronavirus cases and hospitalizations across the U.S. have plummeted after reaching peaks during the winter, allowing governments to relax rules like requiring masks in public schools.                                                                                                                                                                  , JPMorgan said New York City employees are still covered by the local vaccine mandate, and workers will need to continue logging responses into the bank's vaccine program. Here is the full memo:                                                                                                                                                                                                                                                                                                       , Message from the Return to the Office Task Force                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Dear colleagues,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Across the U.S., as we continue to see cases decline, restrictions lifted and more flexibility with daily activities, we are learning to live with COVID as part of our new normal. The virus has shifted to cause less severe illness, there is now a high level of vaccine immunity and natural immunity from infection, and we are once again enjoying the benefits and energy that comes with being together in the office on a regular basis.                                                      , As we continue our journey to a sense of normalcy, we wanted to look ahead and let you know what to expect as it relates to our COVID health and safety guidelines.                                                                                                                                                                                                                                                                                                                                     , Maintaining a safe work environment and following local requirements will continue to be a priority. We will keep some of our practices and protocols in place along with our permanently improved air filtration and cleaning standards, namely:                                                                                                                                                                                                                                                       , This pandemic has reminded us of the impact infectious transmission can have on others. In the new normal, it is more important than ever that we each do our part to keep each other safe. So, if you are sick with COVID or have symptoms of any other illness that may be contagious, please do not come into the office. And if you do test positive for COVID, please exercise good judgement and common sense in deciding if colleagues with whom you've been in close contact would want to know., As we have from the start, we will continue to monitor developments closely and will be prepared to reintroduce practices and protocols when and where needed. For instance — masking requirements may return if there is another spike in cases, or a variant begins to spread that causes severe illness in the general population. But this will only happen based on strict criteria or if mandated by state or local government authorities.                                                       , In March of 2020, no one could have predicted the toll the pandemic would take on our communities, families and economy. We have learned new ways to work and have seen first hand how resilient we can be when we pull together as a team.                                                                                                                                                                                                                                                             , As we see our way out of the pandemic, thank you for being the team we could rely on no matter what.                                                                                                                                                                                                                                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-03-14 23:44:20 </td>
   <td style="text-align:left;"> US Natural Gas Eases on Milder Weather </td>
   <td style="text-align:left;"> US natural gas futures eased below $4.6 per million British thermal units in the third week of March, after climbing as high as $4.8 last week, amid weaker demand prospects and reports of rising output. The looming spring warmth is set to cause a sharp decrease in heating demand, with temperatures set to increase to exceptionally comfortable levels. Meanwhile, production is expected to come back online faster than previously expected, following freeze-offs in some natural gas wells over the weekend. Traders are now forecasting the first weekly net addition of natural gas to domestic inventories in the seven days ending March 25th, about a week earlier than usual. Elsewhere, signs of advances in Russia-Ukraine negotiations calmed fears about the possibility that Russia could halt supplies to Europe, releasing some pressure off of global natural gas markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lumber </td>
   <td style="text-align:left;"> 2022-03-14 23:28:00 </td>
   <td style="text-align:left;"> Lumber Prices Remain Under Pressure </td>
   <td style="text-align:left;"> Chicago lumber futures were trading below $1,400 per thousand board feet in the third trading week of March as investors unwound some long positions after a massive rally that drove prices to a 10-month high of $1,480 earlier this month. Still, the overall fundamental market situation remained bullish, with demand set to stay strong as the large US home builders make their purchases necessary for the looming spring construction season. On the supply side, investors grew concerned about further logistical disruptions as the fallout from the war in Ukraine continued to intensify. Markets were already facing shortages as Canada, a leading lumber supplier to the US, was hit by fire, flood and infestations of wood-boring beetles last year. Still, despite ongoing terrible supply chain disruptions, the output volumes at sawmills have recovered from the constraints of mid-2020 to end-2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-14 23:19:36 </td>
   <td style="text-align:left;"> Wall Street Regains Traction </td>
   <td style="text-align:left;"> US stocks started the third trading week of March on a mixed note but regained ground shortly after the opening on hopes for a diplomatic solution regarding the Russia-Ukraine war. The Dow rose over 400 points, or around 1%, while the S&amp;P 500 climbed 0.8% and the tech-heavy Nasdaq added about 0.1%. In the latest developments, Russian forces allowed some of the people trapped in Mariupol to leave as negotiators from both countries resumed peace talks even as Russia intensified fighting in Kyiv overnight. Aside from Ukraine headlines, prospects of higher interest rates kept sentiment subdued. The US central bank is expected to raise its target fed funds rate by 25 basis points from zero to tame inflation that is already running at multi-year highs. Investors will also keep an eye on new forecasts for rates, inflation and the economy, given the uncertainty from the Russia-Ukraine conflict. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-03-14 23:17:13 </td>
   <td style="text-align:left;"> Canadian Dollar Remains Above 3-Month Low </td>
   <td style="text-align:left;"> The Canadian dollar traded at the $1.27 level in the third week of March, above the three-month low of $1.29 touched on March 8th amid improved risk appetite and expectations of tighter monetary policy. Hopes of de-escalation of Russian attacks in Ukraine limited the momentum of the US dollar amid prospects of ceasefire talks in between both delegations. At the same time, strong labor figures in Canada from February strengthened projections of tighter policy by the Bank of Canada. The central bank hiked its target for the overnight rate by 25bps to 0.5%, the first hike since October 2018, and emphasized it will use its monetary policy tools to return inflation to the 2% target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/inflation-expectations </td>
   <td style="text-align:left;"> 2022-03-14 23:09:00 </td>
   <td style="text-align:left;"> US Inflation Expectations Back to Record High </td>
   <td style="text-align:left;"> US consumer inflation expectations for the year ahead increased again to 6% in February of 2022, the same as a record 6% in both December and November, and reversing some of January’s sharp declines. All the commodity price change expectations increased, namely for food (9.2%), gas (8.8%), medical care (9.6%), college education (9%) and rents (10.1%). Median home price expectations, on the other hand, declined (5.7%). Meanwhile, earnings growth expectations remained unchanged, while expectations about unemployment, perceived job loss, and job finding all improved and those for spending growth reached a new series high. Median three-year ahead inflation expectations also ticked up by 0.3 percentage point to 3.8%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-03-14 23:07:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Rises for 7th Day </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index went up 0.3% to 2,727 on Monday, its highest since December 14th, extending gains into a seventh straight session, as the capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, gained 110 points to 2,786. "Last week, average capesize spot rates surged 64% w/w as European traders source coal and other dry bulk commodities from further away distances to replace lost Russian supplies. We believe dry bulk spot rates will strengthen into 2Q22 due to coal and grain trade disruptions, increasing iron ore volumes from Brazil, and minor bulk trade growth," shipbroker Jefferies said. Meanwhile, the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, was down 95 points to 3,092 points; and the supramax index decreased 5 points to 2,934 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/nektars-stock-falls-44-after/story.aspx?guid={BAE8E40B-FB56-4516-B6D9-9D3034750122}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-14 23:04:59 </td>
   <td style="text-align:left;"> Nektar's stock falls 44% after experimental therapy fails to work in melanoma patients  - MarketWatch </td>
   <td style="text-align:left;"> Shares of Nektar Therapeutics Inc. 
        NKTR,
        -60.87%
       tumbled 44.7% in premarket trading on Monday after the company said a combination of its experimental therapy bempegaldesleukin in combination with Bristol Myers Squibb Co.'s 
        BMY,
        +0.54%
       Opdivo failed as a treatment for melanoma. The companies had tested the combination against Opdivo in a Phase 3 clinical trial as a first-line treatment for patients with previously untreated unresectable or metastatic melanoma. After discovering the combination did not meet the study's primary endpoints, they halted enrollment and unblinded the study. Nektar and Bristol are also evaluating bempegaldesleukin and Opdivo in patients with renal cell carcinoma and bladder cancer. Nektar's stock is down 21.3% since the start of the year, while the broader S&amp;P 500 
        SPX,
        -0.74%
       has dropped 11.8%. , The chief executive of Pfizer Inc. said Sunday that COVID-19 is not going to just go away in the coming years, and that fully vaccinated people will need a fourth shot later this year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/currency </td>
   <td style="text-align:left;"> 2022-03-14 22:50:00 </td>
   <td style="text-align:left;"> Russian Ruble Gains as Ukraine-Russia Talks Continue </td>
   <td style="text-align:left;"> The Russian ruble strengthened to below 115 per USD on Monday as diplomatic efforts to end the war continued. Ukraine said "hard" talks on a ceasefire, immediate withdrawal of troops and security guarantees with Russia were held although negotiations were paused until Tuesday. The ruble is still down about 40% since the Russian attack on Ukraine started amid a series of harsh Western sanctions, effectively cutting the country off from the global financial system and targeting its key public and private institutions. Amid these developments, the Bank of Russia has so far responded with a more than double policy rate hike to 20% and introduced a range of capital control measures to defend its currency from further depreciation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-03-14 22:45:37 </td>
   <td style="text-align:left;"> Brent Crude Falls Nearly 8% </td>
   <td style="text-align:left;"> Brent crude futures tumbled nearly 8% to as low as $104.2 per barrel on Monday, extending last week’s decline on hopes for a diplomatic solution to the Russia-Ukraine war while fresh lockdowns in China clouded the outlook for demand. Ukraine and Russia resumed talks on Monday even as Moscow intensified fighting in Kyiv overnight, providing some relief from supply concerns that have kept oil prices at multi-year highs. In addition to the bearish tone were surging coronavirus cases in China, which already led to new lockdowns and raised fears about slowing demand from the world’s largest crude oil importer. The international benchmark touched a 14-year high of $139.13 last week before reversing and closing the week sharply lower as traders assessed potential improvements to the supply outlook disrupted by Russia’s invasion of Ukraine and related sanctions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/svb-leerink-astrazenecas-lynparza-could/story.aspx?guid={5CFB36F0-5212-46CD-94C8-7A0EF4E6D22E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-14 22:42:33 </td>
   <td style="text-align:left;"> SVB Leerink: AstraZeneca's Lynparza could bring in $9.7 billion in sales by 2028 - MarketWatch </td>
   <td style="text-align:left;"> The Food and Drug Administration's approval on Friday of AstraZeneca's Lynparza as a treatment for some people with early-stage breast cancer could bring in $1.5 billion in annual revenue for the company. U.S.-listed shares of AstraZeneca 
        AZN,
        +0.15%
        AZN,
        +1.30%
       were up 1.5% in trading on Monday. SVB Leerink analyst Andrew Berens told investors in a note on Monday that he expects rapid adoption of the therapy among patients with germline BRCA-mutated HER2-negative high-risk early breast cancer who have previously received treatment. Lynparza is already approved as a treatment for ovarian cancer; it brought in $2.7 billion in revenue in 2022. Berens expects the drug to generate $9.7 billion in sales by 2028 when taking into account the breast-cancer approval and positive clinical data among prostate-cancer patients. AstraZeneca's stock is up 5.1% this year, while the S&amp;P 500 
        SPX,
        -0.74%
       has declined 11.8%. , Today, the U.S. and its allies are feeling the pain of trying to isolate Russia. But the postwar world order could enhance the benefits of globalization while marginalizing tyrants and their cronies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-14 22:41:05 </td>
   <td style="text-align:left;"> Oil Hits Two-Week Low </td>
   <td style="text-align:left;"> WTI crude futures tumbled over 8% to as low as $100.5 per barrel on Monday, a level not seen in almost two weeks on hopes for a diplomatic solution to the Russia-Ukraine war while the reimposition of fresh lockdowns in China clouded the outlook for demand. Ukraine and Russia resumed talks on Monday even as Moscow intensified fighting in Kyiv overnight, providing some relief from supply concerns that have kept oil prices at multi-year highs. In addition to the bearish tone were surging coronavirus cases in China, which already led to new lockdowns and raised fears about slowing demand from the world’s largest crude oil importer. The US crude benchmark touched a 14-year high of $130.5 last week before reversing and closing the week sharply lower as traders assessed potential improvements to the supply outlook disrupted by Russia’s invasion of Ukraine and related sanctions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-14 22:36:00 </td>
   <td style="text-align:left;"> Brazilian Stocks Move Lower </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Ibovespa, fell 0.8% to around 110,863 on Monday, led by sharp declines in stocks linked to commodities, especially iron ore and oil. At the same time, investors remain attentive to the effects of the war in Ukraine and the next steps of the US Federal Reserve, which may start to kick off the tightening cycle this week. Locally, caution prevails ahead of the Brazilian central bank Copom meeting on Wednesday, with analysts expecting the bank to announce a one percentage point hike, to 11.75%, amid persistent inflationary pressures. Meanwhile, Brazil's central bank financial markets' weekly survey for 2022 showed IPCA forecasts climbed to 6.45% from 5.65% a week earlier, the ninth straight week of increases. As a result, analysts also raised forecasts for the benchmark Selic rate, which should reach 12.75% by the end of 2022, compared to 12.25% in last week's survey. The estimate of economic growth for 2022 advanced to 0.49%, up from 0.42% a week ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/bloomberg-study-flags-lower-refinancing/story.aspx?guid={C88A833F-2228-4BC4-BB38-FF832AB112C1}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-14 22:33:11 </td>
   <td style="text-align:left;"> Bloomberg study flags lower refinancing approvals for African Americans by Wells Fargo  - MarketWatch </td>
   <td style="text-align:left;"> African American homeowners drew the lowest mortgage refinancing approval rate by lenders nationwide and also had the lowest number of applicants, according to a study in a Bloomberg article published Friday. Forty-seven percent of black homeowners who completed a refinance application with Wells Fargo 
        WFC,
        +2.87%
       in 2020 were approved, compared with 72% of white homeowners, according to an analysis of federal mortgage data by Bloomberg. JPMorgan Chase &amp; Co. 
        JPM,
        +0.99%
       approved 81% of refinancing applications from black homeowners and 90% from white home owners. Bank of America Corp. 
        BAC,
        +2.16%
       approved 66% of its black applicants and 78% of white applicants. Rocket Mortgage LLC 
        RKT,
        -6.25%
       OK'd 79% of black applicants and 86% of white ones applicants. Wells Fargo did not dispute the statistics reported by Bloomberg, but said it treats all potential borrowers the same and it's more selective  than other lenders. Wells Fargo also said an internal review of its 2020 refinancing decisions confirmed that additional, legitimate, credit-related factors were responsible for the differences, Bloomberg reported., Fully vaccinated people will need a fourth shot later in 2022, according to the head of Pfizer Inc., who said that COVID-19 is not going to just go away in the coming years.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/14/europe/ukraine-russia-mayor-protests-intl/index.html </td>
   <td style="text-align:left;"> 2022-03-14 22:08:42 </td>
   <td style="text-align:left;"> Russia is trying to install pro-Kremlin officials in occupied cities, but Ukrainians are fighting back - CNN </td>
   <td style="text-align:left;"> (CNN)Russia is facing new forms of resistance in the cities it has seized in Ukraine, where attempts to abduct and replace political leaders have been met with legal pushback and defiant public protests.                                                                                                        , Russian troops have detained the mayors of at least two regions, Ukrainian officials say, replacing one with a pro-Kremlin opposition member. Lawmakers in a third Russian-occupied city say the groundwork is being laid for a political coup.                                                                     , Despite overcoming significant Ukrainian military resistance to occupy the territories, attempts to oust local leaders have led to new difficulties for Moscow.                                                                                                                                                     , Ukraine's prosecutor general has opened a treason investigation into Galina Danilchenko, the newly installed mayor of Russian-occupied Melitopol in southeastern Ukraine, after the city's elected mayor, Ivan Fedorov, was arrested by armed men on Friday.                                                        , The move follows a plea on Sunday by the city's lawmakers for a criminal investigation of Danilchenko over what they called "the high crime of treason, for attempting to set up an occupying government in Melitopol."                                                                                             , The city council accused Danilchenko -- who is a former member of the city council, according to the Zaporizhzhia regional administration's website -- of dissolving the city government and transferring its powers to a People's Deputies Committee.                                                              , Danilchenko declared herself the local leader and immediately said in a televised address Sunday that "Russian TV channels" would begin broadcasting in the city, which has been occupied by Russia since the first days of the invasion.                                                                           , Her ascension was met by angry protests on Saturday, when several hundred people demonstrated outside the city hall, chanting "Freedom for the Mayor" and "Fedorov."                                                                                                                                                , The Russian-backed regional prosecutor of Luhansk, a separatist-controlled region nearly 300 miles from Melitopol, claimed the rationale for Fedorov's arrest was that he had committed terrorism offenses.                                                                                                         , A second mayor -- Yevhen Matveyev, the leader of Dniprorudne, a small city north of Melitopol -- was abducted by Russian troops on Sunday, according to Ukraine's Foreign Minister, Dmytro Kuleba.                                                                                                                  , "Today, Russian war criminals abducted another democratically elected Ukrainian mayor, head of Dniprorudne Yevhen Matveyev. Getting zero local support, invaders turn to terror. I call on all states &amp; international organizations to stop Russian terror against Ukraine and democracy," Kuleba tweeted on Sunday., CNN could not independently confirm the claim.                                                                                                                                                                                                                                                                      , And in the southern city of Kherson, a political battle is underway to prevent the occupied city from being transformed into a breakaway pro-Russian republic.                                                                                                                                                      , Ihor Kolykhaiev, Kherson's mayor, has said mass protests show that "Kherson is Ukraine" and insisted that he retains administrative control of the city.                                                                                                                                                            , Speaking in a video posted on Facebook on Sunday, Kolykhaiev said, "the city is living in a normal mode, the City Council is working, all the deputies are at work, all the utility establishments are up and running. Kherson mayor's office has a flag waving in the front. Kherson is Ukraine."                  , Kherson has been occupied by Russian forces since March 3. In recent days, at least one Kherson regional council official warned that occupation forces were laying the groundwork for the "Kherson People's Republic."                                                                                             , Earlier Sunday, hundreds of demonstrators flocked the streets of the Russian-occupied city to protest the suspected Russian plans. The mayor said it was a "a peaceful protest to show that the citizens' position is that Kherson is Ukraine."                                                                     , Alluding to reports of Russian political maneuvering, Kolykhaiev warned that there "seem to be behind-the-scenes talks held, and the people who want to change the political structure of our country and the south of Ukraine are trying to influence this situation."                                             , As Russian forces slowly encroach upon other major Ukrainian cities, the levels of defiance in occupied locations could signal a long and difficult battle for Moscow to consolidate political power, if it succeeds in its immediate military objectives.                                                          , Meanwhile, the humanitarian situation for Ukrainians in occupied cities continues to deteriorate.                                                                                                                                                                                                                   , Kolykhaiev said Kherson had been cut off from humanitarian aid and was running out of resources, less than two weeks into its occupation.                                                                                                                                                                           , He said the city "can't receive humanitarian cargo. Food is finishing in the stores, we are running out of gas, we only have diesel oil left at the gas stations. We are running out of medications and insulin."                                                                                                   , "Our main weapon is unity," he said.                                                                                                                                                                                                                                                                                , CNN's Tim Lister and Jonny Hallam contributed reporting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-14 22:01:30 </td>
   <td style="text-align:left;"> Toronto Stocks Extend Losses on Monday </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, edged lower on Monday, underperforming its global peers, as weakness in oil and gold prices dragged down heavyweight energy and mining stocks. Paring losses, financials and industrials rose above the flatline. On corporate news, Anglo-Australian mining giant Rio Tinto offered to buy the remaining 49% stake of Canada’s Turquoise Hill for $2.7 billion, moving towards full ownership of a large copper and gold mine in Mongolia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belarus/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-14 21:53:04 </td>
   <td style="text-align:left;"> Belarus Inflation Rate Slows to 9.99% in February </td>
   <td style="text-align:left;"> The annual inflation rate in Belarus eased to 9.99 percent in February of 2022 from 10.4 percent in the previous month amid a softer rise in prices of both food (11.4 percent vs 12 percent in January); and non-food products (8.6 percent vs 9.3 percent). Meanwhile, prices rose at a faster pace for services (9.4 percent vs 9.1 percent). On a monthly basis, consumer prices rose 1.6 percent, edging up from a 1.5 percent rise in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/14/business/economy/powell-fed-inflation-volcker.html </td>
   <td style="text-align:left;"> 2022-03-14 21:52:38 </td>
   <td style="text-align:left;"> Could Inflation Prompt Powell to Act Like Volcker? - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                             , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                              , The Federal Reserve is facing the fastest inflation most Americans have ever seen. Its chair says policymakers will do what it takes to tame prices.                                                                                                                                                                                                                                                                                                      , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                         , To Jerome H. Powell, the chair of the Federal Reserve, Paul Volcker is more than a predecessor. He is one of his professional heroes.                                                                                                                                                                                                                                                                                                                     , “I knew Paul Volcker,” Mr. Powell said during congressional testimony this month. “I think he was one of the great public servants of the era — the greatest economic public servant of the era.”                                                                                                                                                                                                                                                         , Now, if rapid inflation proves more stubborn than policymakers expect, Mr. Powell could find himself in a situation in which he must follow Mr. Volcker’s lead. The towering former Fed chair is best remembered for waging an aggressive — and painful — assault on the swift price increases that plagued America in the early 1980s.                                                                                                                   , Mr. Volcker’s Fed rolled out policies that pushed a key short-term interest rate to nearly 20 percent and sent unemployment soaring to nearly 11 percent in 1981. Car dealers mailed the Fed keys from unsold vehicles, builders sent two-by-fours from unbuilt houses and farmers drove tractors around the Fed building in Washington in protest. But the approach worked, killing off the rapid price inflation that had festered throughout the 1970s., Mr. Powell was asked this month if the Fed was prepared to do whatever it took to control inflation — even if it meant harming growth, as Mr. Volcker did.                                                                                                                                                                                                                                                                                                , “I hope that history will record that the answer to your question is yes,” the Fed chair replied.                                                                                                                                                                                                                                                                                                                                                         , Few, if any, economists think that the 2022 Fed will need to repeat Mr. Volcker’s policies to the same degree, in part because the central bank is taking action much more quickly. The Fed is expected to begin raising interest rates from near zero at its meeting this week, and is likely to signal that it expects to make a series of moves this year as it tries to cool down the economy and control inflation.                                  , Price increases had run high for more than a decade by the time Mr. Volcker became chair in 1979, making them a part of everyday lives. Shoppers expected prices to go up, businesses knew that, and both acted accordingly.                                                                                                                                                                                                                              , This time, inflation has been anemic for years (until recently), and most consumers and investors still expect costs to return to lower levels before long, survey and market data show. While inflation has been rapid for the past year, that is a comparatively short period and one that may not fuel the same kind of expectations for higher prices that bedeviled Mr. Volcker’s era.                                                               , And while today’s inflation is taking a bite out of household budgets, it is slower than in previous periods: While it rose to 7.9 percent in February, the fastest pace since 1982, it is still well below a peak of 14.6 percent in 1980. Economists expect price gains to begin moderating this year, rather than climbing to such high levels.                                                                                                        , But in other ways, the backdrop Mr. Powell faces is beginning to look eerily similar to the one Mr. Volcker confronted.                                                                                                                                                                                                                                                                                                                                   , Wages are increasing rapidly, and employers report raising prices to cover their bigger labor bills, posing the possibility of a more muted version of the wage-price spiral that helped keep inflation high during Mr. Volcker’s years.                                                                                                                                                                                                                  , Oil prices are climbing as Russia wages war on Ukraine, mirroring oil price shocks that rocked the economy in the years before Mr. Volcker’s ascent to the chair. The Arab oil embargo of 1973-74 and the Iranian revolution of 1979 both curtailed supply and sharply pushed up pump prices.                                                                                                                                                             , And geopolitical instability is fueling uncertainty about what will happen next, much as it did in the 1970s, when war raged in Vietnam.                                                                                                                                                                                                                                                                                                                  , “That’s the proper historical reference for what we’re trying not to replicate,” Mr. Powell said of the 1970s during separate remarks to Congress this month. “One of the things that is different now is that central banks — including the Fed — very squarely take responsibility for inflation.”                                                                                                                                                      , When inflation was taking off in the 1960s and 1970s, Fed officials bickered about how high to raise rates as they worried about hurting the labor market too much. Many economic historians now think that their reluctance to act more quickly allowed those price gains to become locked in until they required a more draconian response.                                                                                                             , “The one really big difference — huge difference, consequential difference — is that the Fed, and the country, lived through the 1970s,” Donald Kohn, a former Fed vice chair, said in an interview. “I think the Fed is determined not to let us get there.”                                                                                                                                                                                             , The inflation challenge facing Mr. Powell, who was renominated by President Biden for a second term as chair and is awaiting Senate confirmation, is the latest economic test that he has had to contend with during his tenure.                                                                                                                                                                                                                          , Mr. Powell, 69, began his first four years as Fed chair in early 2018. By that Christmas, the central bank’s campaign of steady rate increases intended to fend off inflation had collided with President Donald J. Trump’s trade war to send markets plummeting.                                                                                                                                                                                         , In 2019, Mr. Trump publicly pushed for lower rates and accosted Mr. Powell — whom the president had chosen to lead the central bank — in interviews and on Twitter, calling him a “bonehead,” an “enemy” and a golfer who could not putt.                                                                                                                                                                                                                 , Then came the onset of the pandemic in 2020, and Mr. Powell and his colleagues crossed red lines and upended norms to rescue markets and the economy. They averted a financial crisis, but 2021 brought with it a new challenge: rapid inflation.                                                                                                                                                                                                         , Now, critics are questioning whether the monetary help that Mr. Powell’s Fed unleashed to protect the pandemic-stricken economy — lowering rates to near zero and buying trillions of dollars in government bonds — combined with huge fiscal stimulus to supercharge demand and release an inflationary genie that could prove hard to trap.                                                                                                             , The Fed has already begun removing some of that support, stopping bond purchases and communicating plans to raise interest rates by a quarter-point this month and steadily throughout the rest of the year. Mortgage rates have already begun climbing in anticipation of those actions.                                                                                                                                                                 , But some are asking whether the Fed, which wanted to see full employment return before paring back its support, has been too slow to react to changing conditions.                                                                                                                                                                                                                                                                                        , This moment “represents a decade of economic experience in the late 1960s and 1970s, compressed into a year,” said Lawrence H. Summers, a former Treasury secretary who spent last year warning that inflation was going to take off as the government overstimulated the economy.                                                                                                                                                                        , What is inflation? Inflation is a loss of purchasing power over time, meaning your dollar will not go as far tomorrow as it did today. It is typically expressed as the annual change in prices for everyday goods and services such as food, furniture, apparel, transportation and toys.                                                                                                                                                                , What causes inflation? It can be the result of rising consumer demand. But inflation can also rise and fall based on developments that have little to do with economic conditions, such as limited oil production and supply chain problems.                                                                                                                                                                                                              , Where is inflation headed? Officials say they do not yet see evidence that rapid inflation is turning into a permanent feature of the economic landscape, even as prices rise very quickly. There are plenty of reasons to believe that the inflationary burst will fade, but some concerning signs suggest it may last.                                                                                                                                  , Is inflation bad? It depends on the circumstances. Fast price increases spell trouble, but moderate price gains can lead to higher wages and job growth.                                                                                                                                                                                                                                                                                                  , How does inflation affect the poor? Inflation can be especially hard to shoulder for poor households because they spend a bigger chunk of their budgets on necessities like food, housing and gas.                                                                                                                                                                                                                                                        , Can inflation affect the stock market? Rapid inflation typically spells trouble for stocks. Financial assets in general have historically fared badly during inflation booms, while tangible assets like houses have held their value better.                                                                                                                                                                                                             , “The question is: Is this the Fed’s Paul Volcker moment, or is this the Fed’s Arthur Burns moment?” he said.                                                                                                                                                                                                                                                                                                                                              , Mr. Burns preceded Mr. Volcker as Fed chair and was late to react to fast inflation, afraid of slowing the job market and hurting Republicans politically. Mr. Summers warned that so far, today’s situation looked more Burns than Volcker, because the Fed spent 2021 only slowly adjusting to the reality of inflation and is now planning to only steadily adjust policy.                                                                             , While White House and Fed officials had expected inflation to fade last year, optimistically labeling it “transitory,” their hopes were foiled as rapid consumer demand for couches, cars and other goods collided with pandemic-constrained supply chains. Price gains accelerated rather than slowing down.                                                                                                                                             , “Transitory” has now become a dirty word in policymaking circles. Though officials continue to predict that inflation will moderate, they acknowledge more clearly how uncertain that is.                                                                                                                                                                                                                                                                 , “We have never put our economy into a deep freeze and then defrosted it before,” said Megan Greene, a senior fellow at a Harvard Kennedy School center and chief global economist for the Kroll Institute. “And we haven’t had a war in continental Europe for a while.”                                                                                                                                                                                  , The war in Ukraine threatens to keep costs elevated for longer. Gas prices have already surged, lifting headline inflation as consumers pay more at the pump. Disruptions to supply chains — and shortages in Russian and Ukrainian exports like neon, palladium and wheat — could curtail car and food production and the transport of goods, exacerbating global shortages.                                                                             , Now, fresh coronavirus restrictions in Shanghai and Shenzhen, China, a major technology manufacturing hub and port city, are boosting the risk that supply chains remain roiled in the coming months. Those shocks from outside come when price pressures have already begun broadening to categories like rent, another development that could make inflation last.                                                                                      , It is not clear whether those factors will keep inflation drastically higher, but Fed officials will be watching warily.                                                                                                                                                                                                                                                                                                                                  , If the Fed has to raise interest rates to painful levels to cool off the economy and put a lid on prices, it could send financial markets tumbling, erasing stock and housing wealth. It could also slow wage increases and throw people out of jobs as companies retrench, curtailing investment and hiring.                                                                                                                                             , But Fed inaction — or under-action — would also carry risks. High prices that chip away at consumer buying power year after year would make it hard for families and businesses to plan for the future. They could especially hurt people who are out of work and living on savings, or the poor, who devote a big chunk of their budgets to necessities and have less room to cut back if costs get out of control.                                      , Mr. Volcker, Mr. Powell’s long-ago predecessor, one of his professional idols and — potentially, if things go wrong — his muse, died in 2019. But he had thoughts on the trade-off.                                                                                                                                                                                                                                                                       , Maintaining confidence that a dollar will be able to buy tomorrow what it can today “is a fundamental responsibility of monetary policy,” Mr. Volcker wrote in his 2018 memoir. “Once lost, the consequences can be severe and stability hard to restore.”                                                                                                                                                                                                , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/14/technology/personaltech/apple-iphone-se-review.html </td>
   <td style="text-align:left;"> 2022-03-14 21:47:26 </td>
   <td style="text-align:left;"> Apple iPhone SE Review: A Phone for the Anti-Consumer - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                           , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                            , Tech Fix                                                                                                                                                                                                                                                                                                                                                                                                                                                , Why spend more if you don’t have to? The new $430 iPhone meets all the criteria of what most of us need in a smartphone.                                                                                                                                                                                                                                                                                                                                , By Brian X. Chen                                                                                                                                                                                                                                                                                                                                                                                                                                        , Brian Chen, The Times’s personal tech columnist, has tested 30 iPhone models over the years, including this latest one.                                                                                                                                                                                                                                                                                                                                 , Apple has a new, cheaper iPhone arriving in stores on Friday that encapsulates the bare minimum of what we need in a smartphone. The latest iPhone SE has a bright screen, a zippy processor, a quality camera and robust battery life. It makes phone calls, too.                                                                                                                                                                                      , Yet for most of us, that won’t be enough.                                                                                                                                                                                                                                                                                                                                                                                                               , Year after year, the majority of customers gravitate toward more expensive iPhones that range from $700 to $1,100. Even though we get superfluous features we seldom use, a phone is more than just a phone for many of us. Instead, it’s an investment in how we expect to do work, stay entertained and connect with our loved ones. Some of us are even willing to go into debt for what’s become a status symbol.                                   , This is all to say that Apple’s budget iPhone SE is for a certain type of customer: the anti-consumer. You will probably want this $430 phone if you meet any of these criteria:                                                                                                                                                                                                                                                                        , You don’t care about whiz-bang features like ultrafast cellular speed.                                                                                                                                                                                                                                                                                                                                                                                  , You correctly recognize that smartphone technology has been around for so long that you should be paying less for it today.                                                                                                                                                                                                                                                                                                                             , You don’t care about what the number of camera lenses or pixels on a screen tells your friends and colleagues about your wealth.                                                                                                                                                                                                                                                                                                                        , You upgrade to a new phone only when you truly feel you need to.                                                                                                                                                                                                                                                                                                                                                                                        , In short, the latest iPhone is for those who just want a no-frills phone that works well for a reasonable price. If that’s you, here’s what you need to know about it.                                                                                                                                                                                                                                                                                  , For this budget iPhone, Apple took the best parts of its more expensive iPhones and squeezed them into the shell of an older iPhone with a home button and smaller screen.                                                                                                                                                                                                                                                                              , Let’s start with the highlights.                                                                                                                                                                                                                                                                                                                                                                                                                        , Like fancier iPhones, the new iPhone SE includes connectivity to 5G, the latest cellular network. In my tests of the device in the San Francisco Bay Area, 5G data speeds were up to 20 percent faster than 4G. That’s not mind-blowing, but it’s a nice feature to have as 5G networks become more widespread.                                                                                                                                         , The new iPhone also has the same computing processor as the more expensive iPhone 13 models. According to the speed-testing app Geekbench, the cheaper phone’s computing power was the same as the iPhone 13’s. That meant apps and games opened in a snap and ran smoothly.                                                                                                                                                                            , The iPhone SE’s battery was another strength. The phone’s previous generation from 2020 had a subpar battery that was depleted by around 7 p.m. each day. I found the new model has enough battery life to last until bedtime.                                                                                                                                                                                                                          , Just as important to know is what the new iPhone lacks compared with the fancier models. Here’s some good news: In my tests, the trade-offs were minor.                                                                                                                                                                                                                                                                                                 , One of the most notable omissions from the iPhone SE was compatibility with an ultrafast variant of 5G known as “millimeter wave.” This data connection, hyped by carriers like Verizon and AT&amp;T, can deliver speeds so fast that a feature-length movie can be downloaded in seconds.                                                                                                                                                                  , The problem is that 5G millimeter wave technology travels short distances and has trouble penetrating walls and obstacles. As a result, it’s rare to even find a connection. People who buy an iPhone SE probably won’t even know that it is missing.                                                                                                                                                                                                   , The more noticeable disadvantage of the latest iPhone is the camera. The fancy camera system on pricier iPhones has multiple lenses capable of capturing more light.                                                                                                                                                                                                                                                                                    , In my tests, the iPhone SE took clear and vibrant photos in daylight, but it didn’t do as well in more challenging lighting conditions. In a photo of my dogs on a shaded path, the iPhone SE produced an image with less detail and unnatural colors compared with the $700 iPhone 13 Mini. The iPhone SE camera also lacks the special night mode found on the fancier iPhones for taking photos in the dark. Using flash is always an option, though., The most obvious difference was the screen. The iPhone SE’s 4.7-inch screen felt constrained and looked dimmer compared with pricier iPhones, which have displays of 5.4 to 6.7 inches. This was probably the most distinguishing factor — if your eyesight isn’t great or if you spend lots of time streaming videos, you will probably prefer a bigger screen.                                                                                        , While there are some compromises when you spend less on a smartphone, the new iPhone delivers more than satisfying results. The $700-plus iPhones are better, but not 60 percent better.                                                                                                                                                                                                                                                                , It’s worth remembering that there are other strong phone contenders in the iPhone SE’s price range. Those include Google’s $400 Pixel 5A, which has different pros and cons. In my tests, the Google phone has a slightly larger screen and takes better photos in low light. But the Pixel phone wasn’t as fast as the iPhone SE, and it may not last as long because Google guarantees software updates for the device only until 2024.               , In the end, though, both phones excelled at doing what we need them to do — connect with the internet, place phone calls and take pictures — at a fraction of the price of their higher-end counterparts. In an era where the cost of just about everything seems to be skyrocketing, that’s something to celebrate.                                                                                                                                    , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/corn </td>
   <td style="text-align:left;"> 2022-03-14 21:44:00 </td>
   <td style="text-align:left;"> Corn Eases from 10-Month High </td>
   <td style="text-align:left;"> Chicago corn futures traded around $7.46 per bushel, closing on its 10-month high of $7.65 hit on March 11th, amid easing supply concerns. Traders hoped that corn supplies from the Black Sea region may resume amid hopes of progress in  peace talks between Russia and Ukraine, the two major exporters. Earlier in the month, corn prices rallied as Ukraine suspended commercial shipping at its ports after Russian forces invaded the country while Russia had to pause grain trade following West’s trade sanctions on Moscow. Meanwhile, the USDA in its March report, estimated 2021/22 global corn ending stocks at 302.2 million, down 0.9 million from last month’s projections as production increases in India partially offset the declines in Argentina and South Africa. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-14 21:41:00 </td>
   <td style="text-align:left;"> Wall Street Braces for Volatility </td>
   <td style="text-align:left;"> US stocks started the third trading week of March mainly mixed, with the Dow Jones adding over 100 points while the S&amp;P 500 and the tech-Nasdaq remained under pressure. Investors have been monitoring developments surrounding the war in Ukraine while refraining from placing big bets ahead of the Fed's meeting on Wednesday. The US central bank is expected to raise its target fed funds rate by 25 basis points from zero to tame inflation that is already running at multi-year highs. Investors will also keep an eye on new forecasts for rates, inflation and the economy, given the uncertainty from the Russia-Ukraine war. Meanwhile, headlines suggesting hopes for a diplomatic push for a ceasefire even as Russia intensified fighting in Kyiv overnight boosted appetite for riskier assets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-14 21:26:00 </td>
   <td style="text-align:left;"> Canada 10-Year Bond Yield Hits Highest Since 2018 </td>
   <td style="text-align:left;"> Canada’s 10-year government bond yield topped 2.1% in the third week of March, the highest in over four years, as expectations of higher interest rates continued to dent appetite for government debt. The Bank of Canada increased its target for the overnight rate by 25bps to 0.5%, the first hike since October 2018, reiterating it will use its monetary policy tools to return inflation to the 2% target. The Governing Council expects interest rates will need to rise further as the economy continues to expand and inflation pressures remain elevated. On top of that, February data from the Canadian labour market pointed to pre-pandemic unemployment levels, as net jobs added reached 17-month highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/balance-of-trade </td>
   <td style="text-align:left;"> 2022-03-14 21:16:00 </td>
   <td style="text-align:left;"> Russia Trade Surplus Widens Sharply in January </td>
   <td style="text-align:left;"> Russia's trade surplus widened to USD 21.17 billion in January of 2022, before the invasion of its neighbor Ukraine and West sanctions, from USD 9.03 billion in the corresponding month of the previous year. Exports surged 72 percent from a year earlier to USD 45.93 billion, boosted by sales to non-CIS (76.9 percent) and CIS countries (41.3 percent). Meanwhile, imports rose at a slower 40.1 percent to a 6-month low of USD 24.75 billion, on the back of purchases from non-CIS (40.6 percent) and CIS countries (36.3 percent). Several global brands and major companies from sectors ranging from technology to automotive and energy suspended their operations in Russia in response to the "special military operation" in its neighbor on February 24th. In March, Russia hit back at western sanctions by imposing an export ban on more than 200 products including telecoms, medical, vehicle, agricultural, and electrical equipment, until the end of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-14 20:58:53 </td>
   <td style="text-align:left;"> India 10Y Bond Yield Hovers Around 6.85% </td>
   <td style="text-align:left;"> Indian 10Y Bond yield hovered around 6.85%, not far from its 2-½-year high of 6.89% hit on February 3rd as investors continue to monitor persisting Russia-Ukraine tensions. On the domestic front, India’s inflation continued to rise to 6.07% in February, amid a surge in global commodity prices although the RBI has maintained a more dovish than expected monetary policy in contrast to hawkish stances by the BoE and the US Fed. Meanwhile, the central bank underwent a debt auction this month after canceling previous two sales, aligning with the Indian government’s record borrowing plan of USD 200 billion from April proposed in the Union budget. With the RBI reassuring a delayed monetary policy normalization, it is unlikely to return to the pandemic-era measures of bond purchases. Last year, the RBI bought 2.2 trillion rupees of debt before stopping its bond-purchase program in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/palladium </td>
   <td style="text-align:left;"> 2022-03-14 20:50:00 </td>
   <td style="text-align:left;"> Palladium Eases from Record Peak </td>
   <td style="text-align:left;"> Palladium futures traded around $2,400 an ounce, falling by more than 20% from it's all-time high of $3180 hit on March 8th amid easing supply concerns. Fears of export disruptions from Russia, the metal's top supplier waned temporarily as traders hoped progress in peace talks between Ukraine and Russia. Meanwhile, Russian mining giant Nornickel said that it has managed to secure alternative routes for its palladium deliveries even though it faced significant logistics constraints. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/russia-warns-western-companies-arrests-asset-seizures </td>
   <td style="text-align:left;"> 2022-03-14 20:47:18 </td>
   <td style="text-align:left;"> Russia warns Western companies of arrests, asset seizures over government criticism </td>
   <td style="text-align:left;"> Harry Yeh and Ken Mahoney react to Ukraine getting cryptocurrency donations and the EU voting on a proposed rule to ban bitcoin on 'Mornings with Maria.'                                                                                                                                                                                                                                              , Russian prosecutors have issued stern warnings to Western businesses operating in the country, threatening to arrest corporate leaders who criticize the Kremlin or to seize the assets of companies that pull out of the nation.                                                                                                                                                                      , Companies that received the warning include Coca-Cola, McDonald's, Procter and Gamble, IBM and Taco Bell owner Yum Brands, according to The Wall Street Journal, citing people familiar with the matter. The prosecutors also threatened to sue the companies and seize assets including trademarks.                                                                                                   , LIVE UPDATES: RUSSIA'S RELENTLESS BOMBING OF HOSPITALS, SCHOOLS CAUSES HORRIFIC CHILD DEATH TOLL                                                                                                                                                                                                                                                                                                       , The warnings have prompted some of the targeted companies to move executives out of Russia, the Journal reported. At least one company has limited communications between its Russian business and the rest of the company, citing concerns that emails or text messages between colleagues could be seized.                                                                                           , People enter a McDonald's restaurant in Moscow, Russia, April 24, 2018.  (Reuters/Tatyana Makeyeva/File Photo)                                                                                                                                                                                                                                                                                         , Since Russian President Vladimir Putin launched an invasion into Ukraine on Feb. 24, hundreds of Western companies have started to sever ties with Moscow under intense pressure from investors and consumers, as well as a barrage of sanctions from the U.S. and European Union. The pace has intensified in recent days as the unrelenting fighting in Ukraine spawns a massive humanitarian crisis., Putin has responded to the withdrawals by saying he favors a plan to "bring in outside management and then transfer these companies to those who want to work" if companies leave Russia.                                                                                                                                                                                                              , Many companies have said their decision to stop operations is temporary, while others blamed their departure on supply-chain disruptions caused by the sanctions. Others have pledged to leave permanently.                                                                                                                                                                                            , Russian President Vladimir Putin speaks as he attends the G20 summit via videoconference in Moscow, Russia, Saturday, Oct. 30, 2021.  (Evgeniy Paulin, Sputnik, Kremlin Pool Photo via AP / AP Newsroom)                                                                                                                                                                                               , Coca-Cola last week said it would suspend operations in Russia, which accounts for about 1% to 2% of its revenue. Yum Brands also said it would temporarily close its 70 KFC locations, in addition to signing an agreement with Pizza Hut to shut down business at 50 locations.                                                                                                                      , On top of that, there have been Wall Street banks including Goldman Sachs, retailers like Levi Strauss and tech companies including Apple that have pledged to pull back their business in the wake of the war. Exxon Mobil and BP have also made plans to exit from Moscow.                                                                                                                           , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                            , The White House has condemned efforts by Russia to nationalize businesses.                                                                                                                                                                                                                                                                                                                             , "Any lawless decision by Russia to seize the assets of these companies will ultimately result in even more economic pain for Russia," White House press secretary Jen Psaki tweeted last week. "It will compound the clear message to the global business community that Russia is not a safe place to invest and do business."  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-14 20:44:00 </td>
   <td style="text-align:left;"> South Africa Government Bond 10Y at 2-Year High </td>
   <td style="text-align:left;"> South Africa 10 Year Government Bond Yield was at 9.9%, remaining close to a near two-year high of 10.3% hit on March 8th, as investors continued to monitor developments around Russia-Ukraine talks and amid expectations of looming interest rate hikes due to strong inflationary pressures stemming from the war. The Federal Reserve is expected to kick off a tightening cycle on Wednesday after US inflation hit a fresh 40-year high of 7.9% in February. Locally, investors are now betting the South African Reserve Bank could have to respond to price pressures fueled by the rising oil price with a 50-basis-point hike. This is also a major threat to South Africa's fragile economic recovery along with domestic structural issues, in particular recurrent load-shedding across the country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/qatar/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-14 20:43:49 </td>
   <td style="text-align:left;"> Qatar Inflation Rate Continues to Slow </td>
   <td style="text-align:left;"> Annual inflation rate in Qatar eased for a second consecutive month to 3.99% in February of 2022 from 4.16% in January. Main upward pressure came from cost of recreation and culture (22.16%); food and beverages (6.92%); transport (4.94%); miscellaneous goods and services (3.33%); clothing and footwear (3.32%); housing and utilities (0.55%); education (0.48%); furniture and household equipment (0.41%) and communication (0.31%). On the other hand, prices fell for health (-3.09%) and restaurants and hotels (-2.45%). On a monthly basis, consumer prices fell 0.26%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/14/us-listed-china-shares-are-tumbling-again-with-alibaba-down-5percent.html </td>
   <td style="text-align:left;"> 2022-03-14 20:37:38 </td>
   <td style="text-align:left;"> U.S.- listed China shares are tumbling again with Alibaba down 9% </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                          , Shares of Chinese stocks listed in the U.S. are falling Monday as investors reassess their positions amid renewed delisting fears.                                                                                                                                                                                                                                                                       , Last week, the Securities and Exchange Commission identified five U.S.-listed American depositary receipts of Chinese companies that failed to comply with the Holding Foreign Companies Accountable Act, which led some Chinese companies' stocks to fall. ADRs are shares of non-U.S. firms traded on U.S. exchanges.                                                                                  , The act allows the SEC to delist and even ban companies from trading on U.S. exchanges if regulators cannot review company audits for three consecutive years. Yum China, BeiGene and Zai Lab, which recently filed annual reports with the agency, made the list.                                                                                                                                       , Big stock names including Alibaba, Baidu and JD.com fell more than 10%, 8%, and 10%, respectively, on Monday. Alibaba fell 12% last week and is down more than 34% since the start of the year, while Baidu plunged 14% and is down 27% year-to-date.                                                                                                                                                    , JPMorgan Chase analysts downgraded JD.com, Alibaba and Pinduoduo to underweight on Monday amid the sell-off.                                                                                                                                                                                                                                                                                             , "Due to rising geopolitical and macro risks, we believe a large number of global investors are in the process of reducing exposure to the China Internet sector, leading to significant fund outflows from the sector," the analysts wrote. "We believe Alibaba, as one of the most widely owned stocks within the China Internet sector, will continue to face stock selling pressure in the near term.", The Chinese market is down overall amid a new Covid-19 lockdown in Shenzhen, where many of the country's technology giants operate. Foxconn, one of Apple's biggest suppliers, shuttered operations in response. Apple's stock was trading down nearly 2% in premarket trading Monday.                                                                                                                   , Some investors are also beginning to weigh the implications of possible Chinese involvement in the war in Ukraine after several news outlets, including the Financial Times, reported that U.S. officials said Russia may have asked China for military help.                                                                                                                                            , — CNBC's Bob Pisani and Eustance Huang contributed to this report.                                                                                                                                                                                                                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/14/elon-musk-says-own-physical-things-when-inflation-is-high-but-hes-not-selling-his-crypto.html </td>
   <td style="text-align:left;"> 2022-03-14 20:10:43 </td>
   <td style="text-align:left;"> Elon Musk says own 'physical things' when inflation is high, but he's not selling his crypto </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                  , As inflation roars at a pace not seen in decades, Tesla CEO Elon Musk said to own physical assets over cash.                                                                                                                                                                                     , In a Musk tweet around midnight ET on Monday, the Tesla founder said: "As a general principle, for those looking for advice from this thread, it is generally better to own physical things like a home or stock in companies you think make good products, than dollars when inflation is high.", Even so, Musk said he is holding onto cryptocurrencies.                                                                                                                                                                                                                                          , "I still own &amp; won't sell my Bitcoin, Ethereum or Doge," he added.                                                                                                                                                                                                                               , The comments come as the consumer price index for February rose 7.9% from a year ago, the highest level since January 1982.                                                                                                                                                                      , Investors may turn to physical assets such as commodities during inflationary times, as inflation boosts the prices of those holdings.                                                                                                                                                           , Musk's comments on crypto briefly moved the price of bitcoin higher before the digital asset pared gains. Bitcoin was nearly flat at $38,940.47 by around 7:30 a.m. ET.                                                                                                                          , The price of bitcoin is down nearly 19% in 2022, according to CoinDesk data.                                                                                                                                                                                                                     , MicroStrategy CEO Michael Saylor earlier in the Twitter thread touted crypto as an inflation play.                                                                                                                                                                                               , "Weaker currencies will collapse, and the flight of capital from cash, debt, &amp; value stocks to scarce property like #bitcoin will intensify," Saylor said.                                                                                                                                       , The two CEOs are known as prominent figures in the crypto space, both having added bitcoin to their respective company's balance sheets. Musk's comments in the past have regularly moved the price of digital coins.                                                                            , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-14 20:10:00 </td>
   <td style="text-align:left;"> India Inflation Rate Above Forecasts </td>
   <td style="text-align:left;"> Annual inflation rate in India accelerated for a 5th straight month to 6.07% in February of 2022, the highest since June of 2021, and above market forecasts of 5.93%. Food inflation increased to 5.85%, the highest reading since November of 2020, with cost of oils and fats (16.44%), meat and fish (7.45%), and vegetables (6.13%) recording the biggest rises. Other upward pressure came from prices of fuel and light (8.37%), miscellaneous (6.52%), clothing and footwear (8.86%), housing (3.57%) and pan and tobacco (2.39%). The inflation stayed at the top of the Reserve Bank of India's target of 2%-6% for the second consecutive month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/luxembourg/gdp-growth </td>
   <td style="text-align:left;"> 2022-03-14 20:04:12 </td>
   <td style="text-align:left;"> Luxembourg GDP Growth Rate Steady </td>
   <td style="text-align:left;"> The economy of Luxembourg expanded by 0.5 percent quarter-over-quarter in the three months to December of 2021, following a downwardly revised 0.5 percent growth in the previous period and marking the sixth straight quarter without contracting. The main positive contributions came from robust rebounds in government expenditure (2.5 percent vs -0.2 percent in Q3) and gross capital formation (9.8 percent vs -4.8 percent). In contrast, household consumption fell marginally (-0.6 percent vs 2.0 percent) and net foreign demand was negative, as imports bounced back by 4.2 percent (vs -0.6 percent in Q3) and exports recovered at a slower 2.2 percent (vs -0.8 percent in Q3). On an annual basis, GDP rose 4.8 percent, the same as in the previous quarter after revisions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60734384?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-14 20:03:43 </td>
   <td style="text-align:left;"> Cost of living: Food boss says prices could rise by up to 15% </td>
   <td style="text-align:left;"> A leading food industry boss has warned that prices will spike as a result of the war in Ukraine.                                                                                                                                     , Ronald Kers, the boss of food firm 2 Sisters, told the BBC that the cost of food could rise by up to 15% this year.                                                                                                                   , He added that the price the company pays for chicken from the farm has jumped.                                                                                                                                                        , Top UK flour producer GR Wright &amp; Sons' has also warned its prices are "absolutely certain" to rise due to the conflict.                                                                                                              , Russia and Ukraine are some of the world's biggest suppliers of wheat and exports are expected to be affected by the war.                                                                                                             , In addition, the price of gas - which is used to heat greenhouses and to make fertiliser, which is essential to food production - has soared.                                                                                         , War in the region is likely to exacerbate prices that were already increasing during what has been described as a cost of living crisis, according to some experts.                                                                   , 2 Sisters employs more than 14,000 people in the UK and specialises in poultry and chilled foods.                                                                                                                                     , Its chief executive told the BBC's Today programme that it had already been forced to pay 50% more for chicken it receives from farms.                                                                                                , He suggested that if the war continues for months, "fundamentally it means as a country we may need to start importing less and producing more ourselves".                                                                            , "We need to work together with all supply chain partners to find a solution... it's a very complex issue."                                                                                                                            , Mr Kers also suggested that the UK's exit from the European Union had made matters more difficult, due to a bigger administrative burden for farmers and less alignment on rules with food companies on the continent.                , Meanwhile, David Wright, managing director of flour milling company GR Wright &amp; Sons', said that cost increases would "inevitably" be passed on to consumers.                                                                         , The firm, which has over 44% of the market share for the UK's bread mixes, said it was already struggling with soaring inflation before the conflict, with costs jumping by 30% between September and December.                       , "Now we have a similar increase [in price due to Ukraine], but instead of it taking four months it has taken two weeks," Mr Wright told BBC Breakfast.                                                                                , Each lorry load of wheat the firm buys costs now costs an extra £2,500, he said. With the company buying around 20 loads per day, it faces paying an extra £1m per month to keep the business running.                                , Though availability will not be an issue, Mr Wright said, he is "absolutely certain" that consumer prices will need to rise.                                                                                                          , "The price is so high so quickly that if you don't put the price of flour up, businesses will go out of business - it's as simple as that," he added.                                                                                 , The comments come shortly after the National Farmers Union (NFU) warned that food production could be hit, affecting the affordability of food in the shops for years.                                                                , In a letter to the government last week, it called for urgent help for farmers.                                                                                                                                                       , "The government must act now, with a clear signal that food security is a priority for the nation," the NFU said.                                                                                                                     , NFU president Minette Batters also told the BBC last week that the rising cost of producing fruit, vegetables and meat could cause farmers to make less at a time when the nation needs more.                                         , "I think the whole world has got to recognise that this is not something we've faced before, we are going to see wheat price inflation levels that have never happened," she said.                                                    , It suggested that farmers have been absorbing costs that have gone up so far.                                                                                                                                                         , This video can not be played                                                                                                                                                                                                          , UK feed wheat prices, for example, are already 39% up on March 2021 at £279.40 a tonne, according to the Agriculture and Horticulture Development Board (AHDB)                                                                        , Other organisations have warned that any costs passed on by food producers would hit those on the lowest incomes the hardest.                                                                                                         , Research from the Resolution Foundation think tank published on Monday suggests that the war in Ukraine could see another spike in the cost of living this autumn.                                                                    , It said that inflation, which tracks how the cost of living changes over time, could reach 10% for the poorest households, whose energy and food bills make up a bigger proportion of their budgets.                                  , James Smith, research director at the Resolution Foundation, called on the chancellor to protect poorest households the "biggest cost of living crisis Britain has faced in generations" at his upcoming spring statement on 23 March., The jump in oil prices since the beginning of the war in Ukraine has pushed up fuel prices, and the price of unleaded petrol hit another record high in the UK at the weekend.                                                        , The RAC said the average price of a litre of unleaded petrol hit 163.46p on Sunday, while diesel rose to 173.44p.                                                                                                                     , However, oil prices have fallen from their highs and the AA said that "wild" pump prices should stabilise or fall back this week, unless the price of oil takes off again.                                                            , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                , Cat Deeley and Edith Bowman are best friends - here is their story                                                                                                                                                                    , A failing witchfinder and his suspect find themselves on a hellish road trip...                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/latvia/balance-of-trade </td>
   <td style="text-align:left;"> 2022-03-14 19:50:00 </td>
   <td style="text-align:left;"> Latvia Trade Gap Widens in January </td>
   <td style="text-align:left;"> Latvia’s trade deficit widened to EUR 209.3 million in January of 2022 from EUR 105.6 million in the corresponding month of the previous year. It was the largest trade gap since October of 2021. Imports jumped by 30.6 percent on year to EUR 1577.8 million, driven by mineral products (180 percent); base metals and articles of base metals (69.7 percent) and products of the chemical and allied industries (48.5 percent). Purchases from the EU rose by 30 percent, while those from CIS countries jumped by 93.9 percent. At the same time, exports rose by a softer 26.7 percent to EUR 1,368.5 million, driven by wood and wood products, wood charcoal (41.3 percent); mineral products (110 percent); and base metals and articles of base metals (65.1 percent). Sales to EU countries advanced 39.7 percent, while those to CIS countries rose by 9.8 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/copper </td>
   <td style="text-align:left;"> 2022-03-14 19:49:39 </td>
   <td style="text-align:left;"> Copper Slips Below $4.5 from Record High </td>
   <td style="text-align:left;"> Copper futures slid to below $4.5 per pound from a record high above the $5-per-pound level hit the previous week, dragged down by demand concerns due to a renewed surge of Covid-19 inflections in China. Copper stocks held by the Shanghai Futures Exchange decreased by 9,100 mt from last Friday to 206,900 mt, a slower rate than those seen in the past weeks. In Europe however, supplies remain low as the market was mainly supplied by Russia. Elsewhere, the world's biggest producer Chile, recorded its lowest January output since 2011, with production sinking 15% compared to December and 7.5% from January 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/iron-ore </td>
   <td style="text-align:left;"> 2022-03-14 19:45:00 </td>
   <td style="text-align:left;"> Iron Ore Eases from 7-Month Peak </td>
   <td style="text-align:left;"> Prices for iron ore cargoes with a 63.5% iron content for delivery into Tianjin corrected to around $150 per tonne, moving away from a seven-month high of $159 hit earlier this month amid some technically-driven selling rather than a substantial change in sentiment. Fundamentals in the iron ore complex continue to be supported by expectations of increased demand from China and fears of further supply-chain disruptions on the heels of the Russian invasion of Ukraine. The world's top consumer China said it would renew its stimulus package for the infrastructure sector in the face of slowing economic growth. Still, Beijing has been signalling it would focus on stabilising prices after the state planner warned about iron ore trading speculation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/14/stocks-making-the-biggest-moves-in-the-premarket-alibaba-jdcom-occidental-petroleum-chevron-and-more.html </td>
   <td style="text-align:left;"> 2022-03-14 19:38:52 </td>
   <td style="text-align:left;"> Stocks making the biggest moves in the premarket: Alibaba, JD.com, Occidental Petroleum, Chevron and more </td>
   <td style="text-align:left;"> , Take a look at some of the biggest movers in the premarket:                                                                                                                                                                                                                                                                                                                                         , Alibaba (BABA), JD.com (JD) – The e-commerce stocks were among China-based companies taking a hard hit on concerns about U.S. delistings, as well as the impact of new Covid-19 outbreaks in the Chinese tech hub of Shenzhen. Alibaba fell 4.7% in the premarket while JD.com sank 5.1%.                                                                                                           , Occidental Petroleum (OXY), Chevron (CVX) – The energy stocks were downgraded to "equal-weight" from "overweight" at Morgan Stanley, which notes that both have outperformed peers in recent months and now offer less attractive relative valuations. Occidental fell 3.3% in the premarket while Chevron slid 2.4%. Both are also moving lower in step with the drop in crude prices this morning., Lockheed Martin (LMT) – The defense contractor's shares gained 1.6% in premarket trading after sources told Reuters that Germany would purchase up to 35 of Lockheed's F-35 fighter jets.                                                                                                                                                                                                           , Coupang (CPNG) – Softbank's Vision Fund sold $1 billion of its stake in the South Korean software company, according to a regulatory filing. The sale of 50 million shares still leaves the fund with 461.2 million Coupang shares. The stock slipped 1.2% in premarket trading.                                                                                                                    , Ford Motor (F) – Ford is forecasting a 12% drop in U.S. sales this year, according to a report in Automotive News, citing people present at a meeting with dealers. The publication said Ford has lost 100,000 units of production so far this year due to parts shortages. Despite that news, Ford added 1% in premarket action.                                                                   , Berkshire Hathaway (BRK.B) – Berkshire is urging the rejection of four shareholder proposals, including the replacement of Warren Buffett as chairman and a proposal that Berkshire report on its plans to handle climate risk. Berkshire added 1% in the premarket.                                                                                                                                , Rio Tinto (RIO) – Rio shares fell 2.9% in premarket trading after the mining company offered to buy the 49% of Canada's Turquoise Hill that it doesn't already own for about $2.7 billion. The price is a more than 32% premium to Turquoise Hill's Friday close.                                                                                                                                   , Tyson Foods (TSN) – The beef and poultry producer's stock slipped 1% in premarket action after BMO Capital Markets downgraded it to "market perform" from "outperform." BMO cites valuation, noting that Tyson has materially outperformed the S&amp;P 500 over the past year, as well as the potential for lower beef margins.                                                                         , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                              , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                              , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                    , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                    , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                  , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-14 19:37:00 </td>
   <td style="text-align:left;"> China 10Y Bond Yield Slips to Over 4-Week Low </td>
   <td style="text-align:left;"> China’s 10-Year Government Bond Yield fell below 2.80%, the lowest since February 10th, as local investors looked for safety assets and Bank of China monetary policy diverged further over other central banks. Shenzhen, China technology hub, has gone into a week-long lockdown intended to slow a Covid outbreak dragging down the major equity indexes. Meanwhile, traders see the PBOC see either a 10 bps or a 5bps cut in the medium term lending facility (MLF), and the injection of more stimulus on top of an expected roll-over of 100 billion yuan worth of MLFs, as the country faces faltering growth conditions, as well as its worst virus wave since March 2020. Earlier, data showed new loans fell more than expected last month, while credit growth was much weaker than anticipated. Elsewhere, the US has warned China of the consequences of helping Russia evade harsh economic and financial sanctions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-14 19:27:00 </td>
   <td style="text-align:left;"> 10-Year Treasury Yield Hits Highest Level Since July 2019 </td>
   <td style="text-align:left;"> The benchmark 10-year Treasury yield broke above 2.1%, a level not seen since July 2019, as investors anticipate a looming policy tightening cycle. The latest CPI data showed that the annual inflation rate in the US accelerated to 7.9% in February of 2022, the highest since January 1982. The hot inflation reading came on the heels of better-than-expected nonfarm payrolls numbers earlier this month while surging commodities prices added to inflationary pressures. While Fed Chair Jerome Powell pointed to a 25 basis point hike on March 16th, he opened the door for a more aggressive move if inflation does not abate as anticipated. Meanwhile, investors continued to monitor developments in the Russia-Ukraine crisis. Headlines suggesting hopes for a diplomatic push for a ceasefire even as Russia intensified fighting in Kyiv overnight have dented the appeal of safe-haven assets. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-03-15 11:04:05 UTC +8

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
   <td style="text-align:left;"> 2022-03-15 11:03:36 </td>
   <td style="text-align:left;"> $SPY Nifty 50 is RIPPING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:03:34 </td>
   <td style="text-align:left;"> $SPY yup even people in New York and Singapore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:03:21 </td>
   <td style="text-align:left;"> $T $MULN $SPY     All that you need to know. Shorts haven&amp;#39;t covered a single share; Check it out below 👇  
  
highly recommend everyone to follow them 🚀   sweepcast.stockmarketmovers.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:02:54 </td>
   <td style="text-align:left;"> $SPY Barron&amp;#39;s says markets will sell off 40% from the top, which was about $480 in SPY. 40% sell off means lows will ultimately be just below $300, maybe $280 area. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:02:39 </td>
   <td style="text-align:left;"> $SPY why does it always happen during triple witching .. March 2020 ring any bells? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:02:15 </td>
   <td style="text-align:left;"> $SPY so when the nickel market opens and the biggest short cant blow up, what do you think is going to happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:02:06 </td>
   <td style="text-align:left;"> $SPY Sell the drama (premium).

https://youtu.be/VQJp135efOY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:02:00 </td>
   <td style="text-align:left;"> $SPY i really dont get how some of you post here all day and night. I cant keep up. Yall dont have families? Friends? Errands? A job? Meetings? Hobbies? I think some of yall have a team working on one account because damn. All day/every day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:01:59 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $NASDAQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:01:29 </td>
   <td style="text-align:left;"> 🚨 TRADE IDEAS FOR TOMORROW 🚨 :

$SPY - CALLS ABOVE $420 &amp;amp; PUTS BELOW $415

$DDOG - CALLS ABOVE $122 &amp;amp; PUTS BELOW $116

$RH - CALLS ABOVE $334 &amp;amp; PUTS BELOW $320

$CAR - CALLS ABOVE $225 &amp;amp; PUTS BELOW $215

$TSLA - CALLS ABOVE $790 &amp;amp; PUTS BELOW $772

GOOD LUCK &amp;amp; ALWAYS TRADE SAFE 💎
FOLLOW ME HERE FOR MORE TRADE IDEAS 👈🏻 💎
https://stocktwits.com/r/thestocktraderhub </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:01:25 </td>
   <td style="text-align:left;"> $SPY $bcrx $qqq oh mfr Putin fking my stocks up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:01:04 </td>
   <td style="text-align:left;"> $SPY $FXI $BABA The majority of people in China don’t want to side with autocrats pushing imperialistic agendas. 

6 years ago Xi made a powerful statement which few remember. A shift towards a gradual/pragmatic deleveraging of debt in which local govts sell assets to pay it down. Primary focus being in the areas of shadow banking + peer to peer lending. Pessimists view this as capital capture but it’s a long bearish move that redistributes wealth from corporations back to people. In the short term it causes high unemployment which we have seen, along with statements of the CCP plans to redistribute wealth. This is the beginning of the end of the gerschenkron needs based model (prod/export based economy) shift in to a consumption based economy. This takes time + is still in its initial phases. It’s a difficult balancing act b/c it can cause civil unrest. Evidence to support this claim of his intent can be found in his desires to keep the Yuan weak

Xi Jinping 2016 translated quote - </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:00:44 </td>
   <td style="text-align:left;"> $SPY and this time it’s in Maryland 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:00:42 </td>
   <td style="text-align:left;"> $SPY raise your hand if you trust Biden and Kamala to lead us through this potential war? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:00:38 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:00:33 </td>
   <td style="text-align:left;"> $SPY The stupididy on this bored is astownding!!! 😪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:00:31 </td>
   <td style="text-align:left;"> $SPY me adding shares to my positions every 2 weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:00:18 </td>
   <td style="text-align:left;"> $SPY if Putin give up, would US remove all those sanctions right away over night?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 11:00:03 </td>
   <td style="text-align:left;"> $SPY THE ANTHOLOGY of *SHORTYMCFLY* 🙋‍♂️💥💦 
 
(I&amp;#39;ve tried so hard to warn ⚠️ Bulls but in the end it doesn&amp;#39;t really matter🎵🔊) - $FB $TSLA $AFRM $COUP etc AMC PYPL DOCU NFLX TDOC AAPL QQQ etc.. 🕯 
 
LAMBO CHRONICLES 😆🏎 
 
https://youtu.be/WNeLUngb-Xg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:59:32 </td>
   <td style="text-align:left;"> 💎**MARCH 15 WATCHLIST**💎

$SPY over $419.80📈 under $415.90📉

$AAPL over $151.53📈 under $150.36📉

$NVDA over $222.02📈  under $209.47📉

$AMZN over $2938.98📈 under $2823.58📉

*Dont be afraid to take the triggers, a SL will protect you* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:59:20 </td>
   <td style="text-align:left;"> $SPY so many little egos with multiple accounts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:59:05 </td>
   <td style="text-align:left;"> $SPY well India announced Saturday regarding a fairer gold and silver exchange that is not manipulated and more transparent. Signs of that could be that we also get better markets soon....well hopefully. Well wait. Actually no😂 the firms wanna kill you and I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:58:55 </td>
   <td style="text-align:left;"> $QQQ $SPY that’s their game. By the time you realize what’s happening you can’t sell so you average down and it keeps dumping lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:58:51 </td>
   <td style="text-align:left;"> $SPY Commodities were overheated.. markets will rotate towards tech.  SPY will jump too. 

Watch the action this week...it&amp;#39;ll be crazy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:58:38 </td>
   <td style="text-align:left;"> When Nasdaq decides to correct, get out of the way…true words👇🏻
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:58:36 </td>
   <td style="text-align:left;"> $SPY South Africa down 3%, and this sh*t never moves lol 😯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:58:27 </td>
   <td style="text-align:left;"> $SPY I’ve been decently accurate lately so here’s my next technical analysis just for the record:

We broke &amp;amp; closed below the 15min wedge &amp;amp; we’re at the bottom of the H&amp;amp;S from the last week or so.

410 would be an intense support level that would likely be the only thing stopping us from dropping below 400.

I believe we *should* get above 420 to see some recovery soon that sends us to 425-427 &amp;amp;  gives us another chance at breaking up and out of the downtrend BUT these are my downside levels and sentiment obviously is bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:58:20 </td>
   <td style="text-align:left;"> $SPY 0.25% interest rate will wreck the economy lmao bears come on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:57:58 </td>
   <td style="text-align:left;"> $SPY 😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:57:57 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:57:27 </td>
   <td style="text-align:left;"> $SPY lol HS went red a again what a trash market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:57:25 </td>
   <td style="text-align:left;"> $SPY 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:57:07 </td>
   <td style="text-align:left;"> $SPY can Powell really raise in this environment? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:57:06 </td>
   <td style="text-align:left;"> $ES_F $NASDAQ $NDX $DJIA $spy  🧞‍♂️😎

https://music.amazon.com/albums/B084WLWSLG?do=play&amp;amp;trackAsin=B084WH464R&amp;amp;ref=dm_sh_5robA3G2Bqwrjt1jC28fJubHp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:57:06 </td>
   <td style="text-align:left;"> $SPY $LIT 

Wow. I mean there was Billy Hwang who managed to lose $2B in a few weeks and then there is this Hong Kong “tycoon” who had $1.5B nickel short position just before nickel almost doubled in price. What is wrong with these crazy Asian gamblers? Should stick to Macau casinos. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:56:45 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:56:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX 
Got gold ? You may want too 
https://www.theburningplatform.com/2022/03/13/fiat-currencies-are-going-to-fail-spectacularly-lawrence-lepard/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:56:38 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:56:27 </td>
   <td style="text-align:left;"> $SPY Maybe if they were running a child sniffing orientation instead of the USA things would be better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:56:23 </td>
   <td style="text-align:left;"> $SPY Chinese pooping in their diaper again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:56:16 </td>
   <td style="text-align:left;"> $SPY don&amp;#39;t tell the bears 😜 they will just think manipulation and load more puts $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:56:07 </td>
   <td style="text-align:left;"> S&amp;amp;P 500 Biggest Gainers &amp;amp; Losers for 03/14/22- $SPX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:56:04 </td>
   <td style="text-align:left;"> $SPY us covid investors are nearly wiped out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:55:59 </td>
   <td style="text-align:left;"> $SPY unreal… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:55:49 </td>
   <td style="text-align:left;"> $SPY hard to justify saying oil is really that high. I mean it was around 80 a barrel before the pandemic so ill take 100 oil anyday till this war is over. Problem is gas companies are over pricing gas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:55:45 </td>
   <td style="text-align:left;"> $SPY a lot of stocks need a bounce to go lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:55:27 </td>
   <td style="text-align:left;"> $SPY damn hang seng recovered pretty fast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:55:20 </td>
   <td style="text-align:left;"> $SPY Putin now stealing other people&amp;#39;s property. Putin allows Russian airlines to fly $10 billion worth of foreign-owned planes domestically </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:55:18 </td>
   <td style="text-align:left;"> $SPY c&amp;#39;mon moo...I know you&amp;#39;re watching. Cash app me $100 $HuggieP and I won&amp;#39;t eat beef for the rest of the month. 

And I follow you so you can even DM it to me. 

Moo. In your hands is the power to save cows.  

Every minute I don&amp;#39;t get my ransom, is another minute closer to my next burger! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:55:14 </td>
   <td style="text-align:left;"> $SPY bears will definitely have a sleepless night! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:55:13 </td>
   <td style="text-align:left;"> $SPY pump and dump...rinse and repeat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:55:00 </td>
   <td style="text-align:left;"> $SPY  Russia got attacked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:54:50 </td>
   <td style="text-align:left;"> $SPY ex dividend is this Friday? Right ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:54:47 </td>
   <td style="text-align:left;"> US futures ripping 
 
i guess money rotating out of china and into IS 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:54:33 </td>
   <td style="text-align:left;"> $AMC $SPY Apes are mad they didn&amp;#39;t sell at $72 for life changing money and now they&amp;#39;re holding heavy bags as they walk out the front door because of gambling little Timmy&amp;#39;s college fund. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:54:25 </td>
   <td style="text-align:left;"> $SPY Flush it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:54:25 </td>
   <td style="text-align:left;"> $SPY I sure wish we still had CrossingTrends or The Shadow to show us the way in these dark times… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:54:23 </td>
   <td style="text-align:left;"> $SPY ⚡️⚡️⚡️ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:54:10 </td>
   <td style="text-align:left;"> $SPY in a way robinhood brought wealth to a million degens , bit they can still go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:54:04 </td>
   <td style="text-align:left;"> $SPY If you held puts overnight I&amp;#39;m just going to go ahead and advise you, money will be lost before you can even run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:54:02 </td>
   <td style="text-align:left;"> $SPY bears looking for easy money are angry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:53:52 </td>
   <td style="text-align:left;"> $DIDI DIdI car all electric to be launched soon  as June 2022 thru June 2023 .  added the dip .Book to value ratio can&amp;#39;t deny $TSLA $SPY 

https://cnevpost.com/2022/03/15/didi-reportedly-could-announce-car-making-plans-in-june/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:53:42 </td>
   <td style="text-align:left;"> $SPY wow HSI turn around , remarkable! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:53:33 </td>
   <td style="text-align:left;"> $SPY so the US market supposed to jump cz heng seng jump? fuckin bulltard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:52:57 </td>
   <td style="text-align:left;"> $SPY spy 430 tomorrow easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:52:54 </td>
   <td style="text-align:left;"> $SPY I can’t understand how people are happy about this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:52:40 </td>
   <td style="text-align:left;"> As I have been saying last 3 months !!! since no one has unlimited $$ to DCA  
 
DONT BUY THE DIPS ; BUY THE STRENGTH AFTER THE DIPS !! 
 
$sofi $upst $afrm $enph $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:52:36 </td>
   <td style="text-align:left;"> $SPY you know it&amp;#39;s been a rough market when someone says S&amp;amp;P futures are &amp;quot;ripping&amp;quot;, and it&amp;#39;s 0.39% up 😂

Rinse and repeat puts and calls, my friends. We&amp;#39;re in for a rollercoaster of 2022, maybe through 2023 if things get worse with consumer spending and Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:52:30 </td>
   <td style="text-align:left;"> $SPY White House press room is a bunch of participation trophy wannabes. No back bones in sight anymore. Russia is just the beginning of the takeovers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:52:08 </td>
   <td style="text-align:left;"> $SPY LOL China pump n dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:51:59 </td>
   <td style="text-align:left;"> $SPY seeing that its trending down still im gonna have to be patient with the calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:51:45 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:51:07 </td>
   <td style="text-align:left;"> $SPY when china goes down the bulls say it don&amp;#39;t  matter when up, they say to the moon, holy fuck they are dumb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:51:00 </td>
   <td style="text-align:left;"> $QQQ $SPY lol algos/people who are buying rn… smdh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:50:38 </td>
   <td style="text-align:left;"> $SPY 🥴 rigged game </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:50:38 </td>
   <td style="text-align:left;"> $SPY Green futures mean a Red day on the way. New normal! Get excited Bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:50:27 </td>
   <td style="text-align:left;"> $SPY I take cock q10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:50:05 </td>
   <td style="text-align:left;"> $SPY ™ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:50:05 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F China reports 5,280 new Covid cases, the highest daily count since the start of the pandemic.

At least 10 cities and counties have been locked down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:50:03 </td>
   <td style="text-align:left;"> $SPY I’m the only one who has consistently called the tops and bottoms here, banking everyday. If you know you know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:49:50 </td>
   <td style="text-align:left;"> $SPY We made money again! Those
who have been following me have been
making money consistently. Haters
spread hate but I have helped retailers
make money for free during past few
weeks when most were losing
If you missed my daily plans follow my
twitter @optionboys or if you want to
join my private group message me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:49:46 </td>
   <td style="text-align:left;"> $SPY worlds smallest rally starts tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:49:41 </td>
   <td style="text-align:left;"> Breaking: Elon Musk has deployed dozens of sharks with frick&amp;#39;n laser beams attached to their heads to take on the Russian Navy.  
 
$TSLA $SPY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:49:37 </td>
   <td style="text-align:left;"> $SPY is like the Hang Seng bounce!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:49:31 </td>
   <td style="text-align:left;"> $SPY 😄😄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:48:56 </td>
   <td style="text-align:left;"> $SPY futures are ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:48:46 </td>
   <td style="text-align:left;"> $SPY covid times </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:48:46 </td>
   <td style="text-align:left;"> $SPY The same futes ripping crowd forgot what happened Thursday night and last night already. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:48:45 </td>
   <td style="text-align:left;"> $SPY I’m gey </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:48:44 </td>
   <td style="text-align:left;"> $SPY tomorrow is a new day which can be different than any other day. Keep ur head up bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:48:26 </td>
   <td style="text-align:left;"> $SPY 450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:48:16 </td>
   <td style="text-align:left;"> $SPY what is the deal with these slow fades out of bull flags lately? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:48:09 </td>
   <td style="text-align:left;"> $SPY if you guys want the real pick, just bet against my raiders every division game this season. Easy money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:48:01 </td>
   <td style="text-align:left;"> $SPY $QQQ - We&amp;#39;re currently sitting on a volume shelf here - We snap this and we could really flush. OH! By the way, we&amp;#39;re down over 21% from the santa rally in 2020 (DEC 27)

Join to Discuss Stock/Options Community! https://bit.ly/StockChitChats </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:48:00 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Who cares if futes ripping I’m still down a fuckload lol. Must be near a bottom when I stop caring about futures I watch them all the time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:47:59 </td>
   <td style="text-align:left;"> $SPY  $AAPL $SNOW $ASAN $ABNB 
👇Futures now 😀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:47:57 </td>
   <td style="text-align:left;"> $SPY trump coddled with Putin and the cronies. He Doesn’t deserve to lead America. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:47:31 </td>
   <td style="text-align:left;"> $SPY not sure about anyone else, but I always come the spy page for a good laugh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:47:23 </td>
   <td style="text-align:left;"> $SPY BULLISH BULLS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:47:16 </td>
   <td style="text-align:left;"> $SPY same excitement as yesterday in futures lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:47:13 </td>
   <td style="text-align:left;"> $SPY  any russians in here? $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:47:02 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures continue to move higher, looks like it is hopeless for the bears tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:46:51 </td>
   <td style="text-align:left;"> $SPY Peep a Futes gaze with a stiffness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:46:42 </td>
   <td style="text-align:left;"> $SPY Another lower high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:46:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ ,,  $1800 into $40k in the last 30 days.. If you really want to make huge profits on trading then, Join this winning chat 🚀 amazing-room.is-great.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:46:24 </td>
   <td style="text-align:left;"> $ARKK bears are eating well $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:46:15 </td>
   <td style="text-align:left;"> $SPY You can&amp;#39;t look at this dude and tell me this isn&amp;#39;t the bullish damn thing you&amp;#39;ve ever seen.

https://www.goodnewsnetwork.org/hills-horseshoe-bat-found-after-40-years/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:45:56 </td>
   <td style="text-align:left;"> $SPY need to see oil under 90 for market to ease. Surprised its dropling after peppermint patties talk today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:45:54 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC Futures tanking. Did Joe Biden say something stupid again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:45:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA In a Joe Biden / Kamala Harris market there&amp;#39;s no Lambo, y&amp;#39;all are gonna have to wait until 2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:45:34 </td>
   <td style="text-align:left;"> $SPY I think Xi is trying to get $BABA cheap enough that he can personally just buy it all… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:45:31 </td>
   <td style="text-align:left;"> $SPY wouldnt be surprised with 4300 by wednesday morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:45:27 </td>
   <td style="text-align:left;"> $SPY Apes report the truth lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:45:25 </td>
   <td style="text-align:left;"> $SPY $420 was strong support level, might revisit it and see if it rejects it and goes lower or passes through. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:45:05 </td>
   <td style="text-align:left;"> $SPY. Oil coming has a lot of money in markets looking for a paper to go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:44:42 </td>
   <td style="text-align:left;"> $SPY why oil dropped $30. War is over?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:44:39 </td>
   <td style="text-align:left;"> $SPY 411 puts in the am! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:44:25 </td>
   <td style="text-align:left;"> $SPY now they hitting the other side of China </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:44:22 </td>
   <td style="text-align:left;"> $SPY Wait is 5% GDP a recession? lol bears come on $AAPL $AMZN $MSFT $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:44:21 </td>
   <td style="text-align:left;"> $SPY Zelensky has a meeting with congress, what a complete shit show Brandon is. Congress finally taking back congressional power in light of a weak administration. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:44:11 </td>
   <td style="text-align:left;"> $SPY what’s ever one is. Bullish about can some explain to me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:44:02 </td>
   <td style="text-align:left;"> $GME $AMC $SPY this won’t end badly at all

“California Public Employees’ Retirement System more than quadrupled investments in AMC Entertainment Holdings (ticker: AMC) and GameStop (GME)”

Let’s Diamond hand pensions on 401ks on these beauties

https://www.barrons.com/articles/amc-stock-gamestop-berkshire-hathaway-palantir-51645118789 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:43:52 </td>
   <td style="text-align:left;"> $SPY I can&amp;#39;t find anything bullish rn. I&amp;#39;ll wait to see what fed does. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:43:45 </td>
   <td style="text-align:left;"> $SPY Futes up with a quickness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:43:18 </td>
   <td style="text-align:left;"> $SPY I remember those limit down days 😁😁😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:43:11 </td>
   <td style="text-align:left;"> $SPY one of the most mentioned on 4chan over the last 7 days

Via topstonks.com/stocks/SPY?st_spy

#spy    #4chan  #investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:43:02 </td>
   <td style="text-align:left;"> $SPY $QQQ 

First downside target hits.

Neutral for now - likely to see more downside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:43:01 </td>
   <td style="text-align:left;"> $SPY buying US value at tomorrows close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:43:00 </td>
   <td style="text-align:left;"> $SPY May touch 410.00 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:43:00 </td>
   <td style="text-align:left;"> $SPY has a bad technical rating, but it does show a decent setup pattern. https://www.chartmill.com/stock/analyzer/stock/SPY?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:42:30 </td>
   <td style="text-align:left;"> $SPY I wish you all market returns as big as MrInvestorpro’s ego… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:42:28 </td>
   <td style="text-align:left;"> $SPY Bulls in denial...bulls in recession...bulls in depression...bulls on medication😂🤣😂at such a young age😟 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:42:24 </td>
   <td style="text-align:left;"> $SPY bulltards yesterday - “markets in china are selling off, that money will flow into the US markets”

ya that worked out well today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:42:18 </td>
   <td style="text-align:left;"> $SPY are we seriously doing this futes ripping this again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:41:53 </td>
   <td style="text-align:left;"> $SPY 428 open 432 closed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:41:44 </td>
   <td style="text-align:left;"> $SPY Futures mean nothing! Pre-market can erase all these gains in like 2 minutes! 🤣🤣💥💥💥💩💩💩💦💦💦💦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:41:32 </td>
   <td style="text-align:left;"> $SPY Every bit of news I hear about Russia-Ukraine conflict is just propaganda for Ukraine.  Even on Newsmax and other conservative networks.  Claiming that Russia is &amp;quot;indiscriminately&amp;quot; killing civilians and that they are orchestrating a genocide.   If Ukraine fighters are launching stinger missiles from residential areas, is that &amp;quot;indiscriminately&amp;quot; targeting civilians?  Ridiculous.   Such one-sided narratives, with absolutely ZERO effort to report from the perspective of the Russians. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:41:28 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:41:27 </td>
   <td style="text-align:left;"> $SPY 

I&amp;#39;m gonna tell you something, you, don&amp;#39;t want to hear.

https://youtu.be/MV_3Dpw-BRY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:41:14 </td>
   <td style="text-align:left;"> $SPY ahhh the FUTES RIPPING crew - how could I forget you 😆😂🙋‍♂️💦 
 
only thing to ripping is this beach bod beauty and WORTHLESS CALLS constantly headed for shredder 🚮💥😁 $COUP $AFRM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:41:13 </td>
   <td style="text-align:left;"> $SPY Jesus I was down huge on that, had to average down and was panicking thank goodness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:41:03 </td>
   <td style="text-align:left;"> $SPY hang send bounced substantially so far.  And talks with us and China are supposedly substantial.  Whatever that means </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:40:59 </td>
   <td style="text-align:left;"> $SPY some of the most powerful people on the planet had a long talk in a few different languages and now everything may be alright. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:40:52 </td>
   <td style="text-align:left;"> $SPY bulltards love china now

earlier today they hated china!!! 

hahahaa most of yall dont belong in the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:40:47 </td>
   <td style="text-align:left;"> $SPY As I said before we go to 410.00 before 430.00. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:40:42 </td>
   <td style="text-align:left;"> $SPY Bear market rallies are real, and aggressive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:40:13 </td>
   <td style="text-align:left;"> $SPY power moves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:40:12 </td>
   <td style="text-align:left;"> $SPY When Bill Maher and Trevor Noah start saying that Trump would have done a better job than Biden in this situation then you should probably start to listen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:40:08 </td>
   <td style="text-align:left;"> $SPY turns out a $7 trillion dollar bazooka can do a ton of damage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:39:36 </td>
   <td style="text-align:left;"> $SPY So what happens if JP Morgan goes under? Will there be a domino effect? 
JPMorgan is the largest counterparty of the nickel &amp;#39;big short&amp;#39; and is leading talks to contain the damage to the market: reports 
 
https://sports.yahoo.com/jpmorgan-largest-counterparty-nickel-big-124118257.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:39:33 </td>
   <td style="text-align:left;"> $SPY 

TMC - the metals company 🚀
- hedge against Inflation and Ukraine war! Best EV play is a commodity play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:39:27 </td>
   <td style="text-align:left;"> $SPY Germany coughs going up too haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:39:23 </td>
   <td style="text-align:left;"> $SPY $AAPL $TQQQ $SOXL $MSFT 
Futures Rrrrrrrrippping 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:39:18 </td>
   <td style="text-align:left;"> $SPY Mike Hawk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:39:00 </td>
   <td style="text-align:left;"> $SPY bulls Step back and take a look… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:38:33 </td>
   <td style="text-align:left;"> $SPY They&amp;#39;re going to give max pain to all shorts tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:38:13 </td>
   <td style="text-align:left;"> $SPY it’s done folks. It will be at least 1 year before most figure it out, but it’s done.. 
The sanctions alone exposed dangerous economic vulnerabilities for all nations.. Trust will be lost in dollars, bonds and foreign derived assets, and factions will divide what’s left…
If Spy is 500 by EOY your milk will cost $7 and gas around $12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:38:00 </td>
   <td style="text-align:left;"> Futures green overnight ;  another bull trap day coming tomorrow ; fake rally before the Wednesday FOMC :)  That why many smart people bought dips today to dump tomorrow 😂 while many will buy tomorrow 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:37:56 </td>
   <td style="text-align:left;"> $SPY too many people bought puts and shorted so it will pump, but then it will dump FOR REAL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:37:47 </td>
   <td style="text-align:left;"> $SPY out for the night can&amp;#39;t co.plain about 2200 bucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:37:42 </td>
   <td style="text-align:left;"> $SPY green is back $QQQ $SOXL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:37:34 </td>
   <td style="text-align:left;"> $SPY bulltards - “china markets have nothing to do with the US markets”

also bulltards - “china has strong economic data, this should help US markets tomorrow”

delusional and clueless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:37:31 </td>
   <td style="text-align:left;"> $SPY It&amp;#39;s time to go long again Bois. The Chinese have confirmed a bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:37:27 </td>
   <td style="text-align:left;"> $SPY bears dead

Futes EXPLODING !!!!

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:37:17 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC Futures ripping hard, did Joe Biden step down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:37:15 </td>
   <td style="text-align:left;"> $SPY There’s the pump… again. 😂✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:37:04 </td>
   <td style="text-align:left;"> $SPY war trade is getting old and tired </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:36:53 </td>
   <td style="text-align:left;"> $SPY so much shorting around 4175. One side will run out soon enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:36:41 </td>
   <td style="text-align:left;"> $SPY $XPEV $NIO from -12% to green, let’s goo! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:36:33 </td>
   <td style="text-align:left;"> $SPY 

At this point the Japanese have to be lying about their true inflation rate? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:36:20 </td>
   <td style="text-align:left;"> $SPY “I just want to sit on my ass and hope for handouts based on something that happened two centuries ago.” - Person that contributes nothing to society. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:36:18 </td>
   <td style="text-align:left;"> $TSLA oh boy... $SPY 
 
https://www.cosmopolitan.com/entertainment/celebs/a39417966/grimes-dating-whistleblower-chelsea-manning/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:36:15 </td>
   <td style="text-align:left;"> $SPY $DJIA $UVXY $LABD $USO U.S. to keep up economic pressure on Russia -Treasury&amp;#39;s Adeyemo

https://news.alertsandnews.com/u-s-to-keep-up-economic-pressure-on-russia-treasurys-adeyemo/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:36:03 </td>
   <td style="text-align:left;"> $SPY Why oil is down when China reported strong retail &amp;amp; industrial data. I am buying the oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:35:57 </td>
   <td style="text-align:left;"> $SPY oh the hang seng is suddenly fine...wow thats so amazing. Its a miracle. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:35:53 </td>
   <td style="text-align:left;"> $SPY why does this seem fake? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:35:37 </td>
   <td style="text-align:left;"> $SPY futessss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:35:32 </td>
   <td style="text-align:left;"> Futures moving higher $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:35:22 </td>
   <td style="text-align:left;"> $SPY futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:35:21 </td>
   <td style="text-align:left;"> $SPY overnight squeeze in full effect like usual </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:35:20 </td>
   <td style="text-align:left;"> $SPY fuck these right wing nuts defending Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:35:12 </td>
   <td style="text-align:left;"> $SPY gee, hope it goes up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:35:08 </td>
   <td style="text-align:left;"> $SPY oil is a fad 😂 just kidding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:34:52 </td>
   <td style="text-align:left;"> $SPY mooo this is ur bump unless I&amp;#39;m delayed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:34:37 </td>
   <td style="text-align:left;"> $SPY  on point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:34:32 </td>
   <td style="text-align:left;"> $SPY short that pop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:34:31 </td>
   <td style="text-align:left;"> $SPY Never bet against the USA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:34:27 </td>
   <td style="text-align:left;"> $SPY If Russia is so tought why is their market closed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:34:20 </td>
   <td style="text-align:left;"> $SPY $DJIA $USO $UVXY $LABD Treasury yields jump with focus on Fed rate decision

https://news.alertsandnews.com/treasury-yields-jump-with-focus-on-fed-rate-decision/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:34:20 </td>
   <td style="text-align:left;"> $SPY Strong economic data out of China tonight. 

HANG SENG TECH INDEX ERASES LOSS OF AS MUCH AS 7.2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:34:18 </td>
   <td style="text-align:left;"> $QQQ $SPY Hang Seng Tech Index erases 7.32% in losses. US futures firming. Long trade is shaping up nicely this evening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:34:14 </td>
   <td style="text-align:left;"> $SPY $ETH.X crank dat Soulja Boy so I can get back iiiiinnnnn!! Cheeeeepply </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:34:13 </td>
   <td style="text-align:left;"> $SPY Biden said &amp;quot;every inch&amp;quot; of NATO land.

What about the air space? 
 https://www.the-sun.com/news/4894561/russian-drone-shot-down-polish-airspace/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:33:59 </td>
   <td style="text-align:left;"> $SPY Hang Seng recovering nicely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:33:52 </td>
   <td style="text-align:left;"> $SPY flutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:33:51 </td>
   <td style="text-align:left;"> $SOFI Reverting back to my good luck profile photo.

Time to bring out the big guns.

$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:33:45 </td>
   <td style="text-align:left;"> $SPY thankgod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:33:35 </td>
   <td style="text-align:left;"> $SPY 🤣🤣 an hour ago bull said hsi have nothing to do with US, and now on China dick salivating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:33:33 </td>
   <td style="text-align:left;"> $spy     
 
had 12 direction changes today  !  
but resulted in only a -0.74% change for the day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:33:29 </td>
   <td style="text-align:left;"> $SPY lmao hang seng tech just pared 6% down and turned green. 😂 it happened in about an hour. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:33:29 </td>
   <td style="text-align:left;"> $GE $SPY $QQQ %$%  
$1800 into $40k in the last 30 days.. If you really want to make huge profits on trading then, Join this winning chat:   🚀 livetradingview.synergize.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:33:13 </td>
   <td style="text-align:left;"> $SPY 🍓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:33:03 </td>
   <td style="text-align:left;"> $SPY One more thing before I go to bed. I’m here mourning my money and I keep seeing this delusional fuck on the internet. This bitch thinks he is Mandela or something. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:32:48 </td>
   <td style="text-align:left;"> $SPY 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:32:43 </td>
   <td style="text-align:left;"> $SPY LET IT ALL GO TO HELL I DONT CARE ANYMORE !!!! I HOPE PUTIN BURNS THE LIBERAL CITIES HERE !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:32:38 </td>
   <td style="text-align:left;"> $SQQQ Still has room to the upside.  Rising wedge here.  My guess we&amp;#39;ll get a blow off top.  $IWM $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:32:35 </td>
   <td style="text-align:left;"> $SPY I don&amp;#39;t like war can we please have peace and invest and grow the planet together instead of destroying everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:32:10 </td>
   <td style="text-align:left;"> $SPY 
China implementation of sanctions against US companies manufacturing in China on the pretext of Covid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:32:06 </td>
   <td style="text-align:left;"> $SPY China and Japan don&amp;#39;t matter no one will ever learn this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:32:05 </td>
   <td style="text-align:left;"> $SPY why do I sense 440 incoming 🤔🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:31:47 </td>
   <td style="text-align:left;"> $SPY green as fuckkkk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:31:41 </td>
   <td style="text-align:left;"> $SPY TRUTH IS WITHOUT A REPUBLICAN POTUS WE WILL BECOME A SECOND WORLD COUNTRY AND NOBODY CARES SO YOU GET WHAT YOU DESERVE  !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:31:11 </td>
   <td style="text-align:left;"> Even with positive numbers coming out of China, Hang Seng is down over 1.50%. 

Trading at 2007 numbers, time machine back 15 years. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:31:10 </td>
   <td style="text-align:left;"> $SPY so hang seng is gonna go from down 5% to green? 

That’s like me saying this will go to 500 tomorrow. 

Lol jk

But 450 on the radar for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:31:01 </td>
   <td style="text-align:left;"> $SPY so all these stupid Chinese stocks are going to be up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:30:46 </td>
   <td style="text-align:left;"> $SPY $QQQ  DEATH CROSS in full effect </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:30:45 </td>
   <td style="text-align:left;"> $SPY holy shit the bullish china posts are stacking up and I went hard china calls today. Buy Blackrock TCHI if you like money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:30:45 </td>
   <td style="text-align:left;"> $SPY The last thing dems want to do right now is to tell their constituents to get a job. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:30:42 </td>
   <td style="text-align:left;"> $SPY 3 day settlement to single day

The Securities and Exchange Commission wants to shorten the time it takes to complete a stock trade, a change agency officials believe will reduce market risk, according to a proposal announced on Wednesday.

Right now, there is a two-day window between when a trade is agreed upon between a buyer and a seller and when the money and the stock in question change hands. The S.E.C. is proposing to cut that time in half, to one day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:30:24 </td>
   <td style="text-align:left;"> $SPY if anything needs banned it&amp;#39;s REDDIT lmfao.... careful what u fish for </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:30:16 </td>
   <td style="text-align:left;"> $SPY I told then Biden will ruin the market and they called me a rac!st. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:29:38 </td>
   <td style="text-align:left;"> $SPY lil death cross and a euro step </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:29:32 </td>
   <td style="text-align:left;"> $SPY so like August 1998 Russia could default on its debt. So who will be the next LTCM (hedge Fund) that needs help from the Fed this time around? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:29:32 </td>
   <td style="text-align:left;"> $SPY I filled up my truck last Sunday when WTI hit 130 a barrel...the price @ the pump was 3.99... WTI is presently trading @ 97.88 a barrel...Why the fk is the price at the pump 3.99 still when market spot price is down over 32 bucks a barrel?? where the fk is the US govt to call out price gouging nationwide...This country is already in hell you don&amp;#39;t have to wait for us to go to it... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:29:28 </td>
   <td style="text-align:left;"> $TTD / $SPY - VERY WEEK ON WEEKLY, LOOKING TO GO BELOW 200 MA. IF IT DOES THAT THEN WE COULD SEE NEW 52-WEEK LOWS. THIS COULD BE JUST ANOTHER TECH STOCK SLOWLY MELTING DOWN.
TARGET : $45 🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:29:12 </td>
   <td style="text-align:left;"> $SPY holy reversal batman!!!  look at HSI rip now!!!  their futes are green too!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:29:03 </td>
   <td style="text-align:left;"> $SPY vix is flying wow. lets get this limit down! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:29:02 </td>
   <td style="text-align:left;"> $SPY I miss McButz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:28:53 </td>
   <td style="text-align:left;"> $SPY futures ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:28:49 </td>
   <td style="text-align:left;"> $SPY I always thought Russians were tough, why is their market closed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:28:17 </td>
   <td style="text-align:left;"> $SPY Another pump for the dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:28:08 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:28:07 </td>
   <td style="text-align:left;"> $SPY 🔥🔥🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:28:02 </td>
   <td style="text-align:left;"> $SPY China selling hard so they can make sure and be apart of the next spy bull rally 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:27:52 </td>
   <td style="text-align:left;"> $SPY breakout to upside very soon in futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:27:51 </td>
   <td style="text-align:left;"> $AAPL $MSFT $SPY $DJIA china just cooked books , be careful trading in am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:27:50 </td>
   <td style="text-align:left;"> $BABA  why is everyone talking about secondary sanctions, Chinese COVID restrictions, and discounting the fact that Chinese tech operates in a climate of “wealth redistribution” and common prosperity?
They may make more money than Amazon, but the government has already made it clear it intends to give corporate profits away. Terrible investments. 

$jd $spy $bidu </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:27:39 </td>
   <td style="text-align:left;"> $SPY if nukes go off how much will a Bitcoin be? How much would an once of gold be? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:27:38 </td>
   <td style="text-align:left;"> $SPY I knew as soon as I saw this guy at the Hawaiian joint tonight, it was gonna be another 🦆🔪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:27:37 </td>
   <td style="text-align:left;"> $SPY 🥦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:27:21 </td>
   <td style="text-align:left;"> $SPY Pandemic Medicaid checks are about to run out. People are going to have to work… the horror! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:27:14 </td>
   <td style="text-align:left;"> China data blows expectations out of the water (if that is Real)  
 
*CHINA JAN.-FEB. INDUSTRIAL OUTPUT RISES 7.5% Y/Y; EST. 4.0% 
*CHINA JAN.-FEB. FIXED INVESTMENT RISES 12.2% Y/Y; EST. 5% 
*CHINA JAN.-FEB. RETAIL SALES RISE 6.7% Y/Y; EST. 3% 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:27:08 </td>
   <td style="text-align:left;"> $SPY Bought dirt cheap Didi calls with bear money today and now I&amp;#39;m seeing bullish Didi posts. Now that feels good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:27:07 </td>
   <td style="text-align:left;"> $BABA $NIO $SPY 

Congrats to buyers and holders. The 7 hours call ended between US and China, and confirmed that china will not help Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:27:02 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

How much of your net worth is in the stock market? Percentage wise I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:26:51 </td>
   <td style="text-align:left;"> $SPY .20% greeeeeen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:26:44 </td>
   <td style="text-align:left;"> $SPY This dude is a funny dude. Putin probably can’t wait to make an example out of him 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:26:30 </td>
   <td style="text-align:left;"> $SPY the year 2035, @OldFngGuy finally gets his 460 unlock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:26:20 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m glad.china is crashing. Serves them right. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:26:13 </td>
   <td style="text-align:left;"> $SPY After WW3 and the radiation levels subside he will come out of his bunker with a mask on and read the flash cards about the NWO digital currency. Bitcoin will flash crash to almost zero immediately. The real kicker is that you must have the new payment chip implanted under your skin…or else you get sent to the “concentration camp” aka “FEMA Detention Facility”. Where are the Wolverines when we need them the most?? God please save our souls from this endless worldly corruption no one deserves this. Red Dawn is happening… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:25:50 </td>
   <td style="text-align:left;"> $SPY 

👀 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:25:47 </td>
   <td style="text-align:left;"> $SPY futures are flying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:25:47 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:25:46 </td>
   <td style="text-align:left;"> $SPY $QQQ heres some from 1970. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:25:41 </td>
   <td style="text-align:left;"> $SPY Gimme a fkn break. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:24:51 </td>
   <td style="text-align:left;"> $SPY Oil under 100, time to fill up the truck 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:24:43 </td>
   <td style="text-align:left;"> $SPY RTS is RIPPING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:24:43 </td>
   <td style="text-align:left;"> $SPY prime example of the problem we have created. Brand new Escalade marked up 25k and other at the dealership are marked up 35k.   Gonna be bad when car bubble hits and many are upside down. Craziness out there !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:24:34 </td>
   <td style="text-align:left;"> $SPY I wonder if it’s only a short term interest rate raise in rates....if so that only means treasury bill (52 weeks and less) and of course the federal funds rate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:24:27 </td>
   <td style="text-align:left;"> $SPY LIMIT DOWN Just because he would&amp;#39;ve wanted too.. 🙏💯📉 $WWE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:24:26 </td>
   <td style="text-align:left;"> $SPY remember last year when our biggest worry was if cciv would go with lucid or blockbuster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:24:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Futures are flying !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:24:12 </td>
   <td style="text-align:left;"> $SPY Boy Biden leaving quite the legacy. Gave Rise to ISIS with Barry and world on fire, now this mess only one year in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:24:06 </td>
   <td style="text-align:left;"> $SPY is this where the bullish articles on china start pouring out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:24:00 </td>
   <td style="text-align:left;"> Indexes will get a good old fashioned hysterical run before May that will make most think we’re going back to “normal”then it’s pure shite May- October IMO. 

$SPY $QQQ $IWM $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:23:56 </td>
   <td style="text-align:left;"> $SPY Obviously we need Trump back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:23:52 </td>
   <td style="text-align:left;"> $SPY a MORTGAGE is a loan on your INCOME not your house…the house simply SECURES the loan…something to think about for all the new homeowners in the last 2 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:23:51 </td>
   <td style="text-align:left;"> $SPY China isn’t ripping it’s just green why are we celebrating? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:23:46 </td>
   <td style="text-align:left;"> $SPY This is twilight zone retardation,Victoria Nuland Foreign diplomat pleads with Israel to cut off Russian financial dealings,yet Russia is fighting against the Nazi factions inside Ukraine and the illegitimate government  Victoria Nuland helped install during the Obama/Biden administration in 2014.Does she even know history to be in such a prominent position?No wonder the world hates USA,we are ruled by phsychopaths,why would a Jewish woman try and convince other Jews to protect Nazi,s from annihilation?https://www.google.com/url?sa=t&amp;amp;source=web&amp;amp;rct=j&amp;amp;url=https://www.timesofisrael.com/us-official-warns-israel-dont-be-last-haven-for-dirty-money-fueling-putins-war/amp/&amp;amp;ved=2ahUKEwj1otn-hMf2AhWCjokEHdUQAt0Q0PADKAB6BAgiEAE&amp;amp;usg=AOvVaw2XiHozSoaSGSz2TFfDDpd_ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:23:38 </td>
   <td style="text-align:left;"> $SPY c&amp;#39;mon moo...I know you&amp;#39;re watching. Cash app me $100 $HuggieP and I won&amp;#39;t eat beef for the rest of the month. 

And I follow you so you can even DM it to me. 

Moo. In your hands is the power to save cows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:23:31 </td>
   <td style="text-align:left;"> $LTH Life time is a Lambo, beautiful amenities, beautiful women. Planet fitness is a Nissan Sentra. I buy thousands of shares everyday life time because it will yield me over 8 figures $PLNT $SPY $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:23:30 </td>
   <td style="text-align:left;"> $SPY thought with commodities down it would be more bullish. What are we following rn? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:23:25 </td>
   <td style="text-align:left;"> $SPY We could overthrow the FDA but you all are more obssessed with what kim and kanye are doing or mocking a random trans woman. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:23:18 </td>
   <td style="text-align:left;"> $SPY saw some influencer all up in arms about Saudi beheading terrorists and criminals today. Another day in the land of the free where idiots such as her and me can say whatever tf they want. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:23:18 </td>
   <td style="text-align:left;"> $SPY quad witching Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:23:03 </td>
   <td style="text-align:left;"> $SPY LMFAOOO what happened to @CrossingTrendsTA dude got shit on so hard he quit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:22:59 </td>
   <td style="text-align:left;"> $SPY bitcoin needs viagra </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:22:48 </td>
   <td style="text-align:left;"> $SPY looks like the home team didn&amp;#39;t show up tonight. Flat future...I like my odds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:22:30 </td>
   <td style="text-align:left;"> $SPY $SOXL $TQQQ $TSLA $AAPL 
Commodities Dripping 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:22:11 </td>
   <td style="text-align:left;"> $SPY LONG LIVE THE BAD GUY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:21:53 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:21:49 </td>
   <td style="text-align:left;"> $SPY CALLS were swollen today from MM 🥊💥🤕 .. bulls entire weekend excitement got REKT 😆📉 
 
BUT WAIT THERE&amp;#39;S MORE 😂 - PPI, RATE HIKES,  CHINA LOCKDOWNS,  ZELENSKY wildcard,  Iran deal etc..  - sigh PUTS SECURED♻️💰 since $480 
 
DIP BUYERS have been obliterated! ☠️😭🚮 (Tom Leech Lee/Cathie 12 Cats 🐈  Wood&amp;#39;s crew etc) $COUP $QQQ $AFRM $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:21:33 </td>
   <td style="text-align:left;"> $SPY $TSLA +13 post-market. Would like nothing more than a gap &amp;#39;n go tomorrow to trap the shorts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:21:16 </td>
   <td style="text-align:left;"> $SPY -700 hai </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:20:52 </td>
   <td style="text-align:left;"> $SPY Fun fact:  International law does not apply to mercenaries. 
It&amp;#39;s a war crime to kill a POW. 
Mercenaries are simply shot in the head when captured.  
Most redditors that go to the Ukraine to fight don&amp;#39;t realize this.  
It&amp;#39;s not a marvel movie or harry potter like they think. 
This redditor is trying to get back home after realizing it was not a super hero marvel movie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:20:35 </td>
   <td style="text-align:left;"> $SPY high oil pushing up the price of EV cars. You never save money. 

Once this whole thing shakes out and prices reset, both oil and ev will be a buy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:20:31 </td>
   <td style="text-align:left;"> $SPY moo, give me $100 and I won&amp;#39;t eat beef for the rest of the month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:20:29 </td>
   <td style="text-align:left;"> $SPY looks like the US and china came to some sort of a deal here. Maybe very good news. Or a whole bunch of covering. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:20:22 </td>
   <td style="text-align:left;"> $SPY futes fighting 

🇺🇸 Rally for razor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:20:18 </td>
   <td style="text-align:left;"> $SPY forget about China, my main WWE homie is gone.  RIP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:20:13 </td>
   <td style="text-align:left;"> $SPY oil is down 25% since its last 5 days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:20:00 </td>
   <td style="text-align:left;"> $SPY up 3% by sunrise unless we get some more good news, then we&amp;#39;ll be up 5%!!! Futures do not go down easy money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:19:46 </td>
   <td style="text-align:left;"> $SPY hang sank about to pull a V! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:19:42 </td>
   <td style="text-align:left;"> $SPY can&amp;#39;t  remember who I stole this from yesterday but I&amp;#39;m still laughing 🤣🤣🤣🤣🤭🤭🤭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:19:37 </td>
   <td style="text-align:left;"> $SPY China bouncing back a little, green or even morning then shortly after fed will be back on the slide </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:19:27 </td>
   <td style="text-align:left;"> $SPY from now on Russia is nothing more than a damp sock puppet of China, just as North Korea...
Great job, Mr Pu! (What an idiot!) $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:19:25 </td>
   <td style="text-align:left;"> $SPY can the fed raise rates 0.125 instead? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:19:23 </td>
   <td style="text-align:left;"> $SPY oil maybe a BTD opportunity 

https://twitter.com/zerohedge/status/1503555811892776960?s=20&amp;amp;t=yImMazfVHNsHyeFVjQGwRQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:19:22 </td>
   <td style="text-align:left;"> $SPY lol.... china ripping just means it is one step closer to being a global superpower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-15 10:19:14 </td>
   <td style="text-align:left;"> $SPY 🤣🤣 SonGoku 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 11:01:59 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $NASDAQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 11:01:25 </td>
   <td style="text-align:left;"> $SPY $bcrx $qqq oh mfr Putin fking my stocks up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:58:55 </td>
   <td style="text-align:left;"> $QQQ $SPY that’s their game. By the time you realize what’s happening you can’t sell so you average down and it keeps dumping lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:58:38 </td>
   <td style="text-align:left;"> When Nasdaq decides to correct, get out of the way…true words👇🏻
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:58:31 </td>
   <td style="text-align:left;"> $QQQ Crabish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:57:39 </td>
   <td style="text-align:left;"> Decision time $QQQ $NDX  
PS: Can&amp;#39;t rule out case count rise in China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:57:10 </td>
   <td style="text-align:left;"> $QQQ who is ready to open green tomorrow and finish deep red again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:56:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX 
Got gold ? You may want too 
https://www.theburningplatform.com/2022/03/13/fiat-currencies-are-going-to-fail-spectacularly-lawrence-lepard/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:54:47 </td>
   <td style="text-align:left;"> US futures ripping 
 
i guess money rotating out of china and into IS 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:51:00 </td>
   <td style="text-align:left;"> $QQQ $SPY lol algos/people who are buying rn… smdh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:50:53 </td>
   <td style="text-align:left;"> $QQQ Bitcoin Ripping! &amp;amp; Oil Dipping! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:50:07 </td>
   <td style="text-align:left;"> $QQQ We made money again! Those
who have been following me have been
making money consistently. Haters
spread hate but I have helped retailers
make money for free during past few
weeks when most were losing
If you missed my daily plans follow my
twitter @optionboys or if you want to
join my private group message me! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:50:07 </td>
   <td style="text-align:left;"> $QQQ China’s financial results don’t fix the current supply chain issues due to Covid. 
Dumb reflex reactions don’t hold up. 
This will be red in the morning. 
Deep red in the afternoon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:48:51 </td>
   <td style="text-align:left;"> $QQQ looks like futures traders just got their daily coke delivery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:48:28 </td>
   <td style="text-align:left;"> $QQQ futes don’t mean shit lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:48:01 </td>
   <td style="text-align:left;"> $SPY $QQQ - We&amp;#39;re currently sitting on a volume shelf here - We snap this and we could really flush. OH! By the way, we&amp;#39;re down over 21% from the santa rally in 2020 (DEC 27)

Join to Discuss Stock/Options Community! https://bit.ly/StockChitChats </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:48:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 83559600. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:48:00 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Who cares if futes ripping I’m still down a fuckload lol. Must be near a bottom when I stop caring about futures I watch them all the time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:47:13 </td>
   <td style="text-align:left;"> $SPY  any russians in here? $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:47:02 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures continue to move higher, looks like it is hopeless for the bears tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:46:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ ,,  $1800 into $40k in the last 30 days.. If you really want to make huge profits on trading then, Join this winning chat 🚀 amazing-room.is-great.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:45:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA In a Joe Biden / Kamala Harris market there&amp;#39;s no Lambo, y&amp;#39;all are gonna have to wait until 2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:43:02 </td>
   <td style="text-align:left;"> $SPY $QQQ 

First downside target hits.

Neutral for now - likely to see more downside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:38:29 </td>
   <td style="text-align:left;"> $QQQ 

TMC - the metals company - hedge against Inflation and Ukraine war! Best EV play is a commodity play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:38:00 </td>
   <td style="text-align:left;"> Futures green overnight ;  another bull trap day coming tomorrow ; fake rally before the Wednesday FOMC :)  That why many smart people bought dips today to dump tomorrow 😂 while many will buy tomorrow 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:37:59 </td>
   <td style="text-align:left;"> $QQQ Option to look at today.. 👀 👀  $350 Call for Wednesday, March 16. Roughly 1 Thousand dollars! 💰💰 Learn more on StockOrbit at https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:37:42 </td>
   <td style="text-align:left;"> $SPY green is back $QQQ $SOXL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:36:13 </td>
   <td style="text-align:left;"> $QQQ Current downswing only moved from 335 to 317 for 18 points. 
Previous downswings have been 30-50 points. 
There is at least 1 more big red day in this swing, and it’s likely to come tomorrow. 
308 is coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:34:18 </td>
   <td style="text-align:left;"> $QQQ $SPY Hang Seng Tech Index erases 7.32% in losses. US futures firming. Long trade is shaping up nicely this evening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:33:29 </td>
   <td style="text-align:left;"> $GE $SPY $QQQ %$%  
$1800 into $40k in the last 30 days.. If you really want to make huge profits on trading then, Join this winning chat:   🚀 livetradingview.synergize.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:33:23 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-03-14 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=Q9JQpIkUy8g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:32:38 </td>
   <td style="text-align:left;"> $SQQQ Still has room to the upside.  Rising wedge here.  My guess we&amp;#39;ll get a blow off top.  $IWM $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:30:46 </td>
   <td style="text-align:left;"> $SPY $QQQ  DEATH CROSS in full effect </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:29:37 </td>
   <td style="text-align:left;"> $QQQ Best entry I have ever had on a short and sold at 324 thinking bounce.  And once again found myself trading against the trend on a hope of repositioning into VIX opex and fomc.  It will fill the gap.  But not tommorrow.  Please dont be tommorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:27:50 </td>
   <td style="text-align:left;"> $QQQ hsi reversed up after positive data 
Rally bitches </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:27:14 </td>
   <td style="text-align:left;"> China data blows expectations out of the water (if that is Real)  
 
*CHINA JAN.-FEB. INDUSTRIAL OUTPUT RISES 7.5% Y/Y; EST. 4.0% 
*CHINA JAN.-FEB. FIXED INVESTMENT RISES 12.2% Y/Y; EST. 5% 
*CHINA JAN.-FEB. RETAIL SALES RISE 6.7% Y/Y; EST. 3% 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:27:02 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

How much of your net worth is in the stock market? Percentage wise I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:26:03 </td>
   <td style="text-align:left;"> $QQQ The rain just started today 🌧 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:25:46 </td>
   <td style="text-align:left;"> $SPY $QQQ heres some from 1970. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:25:44 </td>
   <td style="text-align:left;"> $QQQ we&amp;#39;ve had nothing but bearish action for 2 weeks of straight we&amp;#39;re in for a massive rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:24:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Futures are flying !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:24:00 </td>
   <td style="text-align:left;"> Indexes will get a good old fashioned hysterical run before May that will make most think we’re going back to “normal”then it’s pure shite May- October IMO. 

$SPY $QQQ $IWM $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:21:49 </td>
   <td style="text-align:left;"> $SPY CALLS were swollen today from MM 🥊💥🤕 .. bulls entire weekend excitement got REKT 😆📉 
 
BUT WAIT THERE&amp;#39;S MORE 😂 - PPI, RATE HIKES,  CHINA LOCKDOWNS,  ZELENSKY wildcard,  Iran deal etc..  - sigh PUTS SECURED♻️💰 since $480 
 
DIP BUYERS have been obliterated! ☠️😭🚮 (Tom Leech Lee/Cathie 12 Cats 🐈  Wood&amp;#39;s crew etc) $COUP $QQQ $AFRM $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:16:12 </td>
   <td style="text-align:left;"> The SMA Versus The EMA: Which One Is Better? 
 
https://www.chartlearning.com/2021/06/exponential-moving-average-simple.html 
 
$SPY $ES_F $QQQ $DIA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:12:04 </td>
   <td style="text-align:left;"> $QQQ probably you should have more covid ...especially in Eastern Europe...might just stop the war...how to fight if you are sick...suddenly covid might just be the saviour. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:11:58 </td>
   <td style="text-align:left;"> $QQQ What happens when the largest purchaser of securities (in history) leaves the market???  You revert to 2015 - 2016 levels.  NASDAQ at 4500 or lower.  Get ready. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:11:52 </td>
   <td style="text-align:left;"> Musk challenges Putin to ‘single combat’ over Ukraine, Russia responds: &amp;#39;Weakling&amp;#39; | Fox Business

Did Elon challenge Putin in a fight?

If I were to wager it would be on Putin, not because I like Putin but because Putin is a trained KGB killer.

There is no way Elon would last even 5 minutes with an ex KGB agent.

$TSLA $SPY $QQQ  https://www.foxbusiness.com/lifestyle/elon-musk-putin-single-combat-ukraine-russia-responds-little-devil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:11:09 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA   

https://apple.news/AwkHjCsY9Q1u2DlzI6Hf4GQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:10:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK If all my stocks would double that’d be, like, nice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:10:03 </td>
   <td style="text-align:left;"> $QQQ this covid sell down is a bit fast ...knowing the issues will be blown over in a few days...looking at the inflation data and the war instead.
Oil down is good at least covid seems to be helping in balancing the demand . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:09:25 </td>
   <td style="text-align:left;"> So the funny thing about more china lockdowns you would think it’s bearish but because it lowers oil demand a ton it’s bullish if oil tanks $USO  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:09:03 </td>
   <td style="text-align:left;"> $QQQ up or down im slowly adding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:08:57 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX  🧞‍♂️😎. 

https://apple.news/AVjleudStSn-UQMGf2OEFlA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:08:16 </td>
   <td style="text-align:left;"> $VXX $VIX $XLF $JPM $QQQ  
Fed Chair Jerome Powell news conference -Wednesday-  
Economic Events Calendar This Week     
https://www.financegreater.com/economiccalendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:08:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA It&amp;#39;d be nice to have some U.S. factories as a backup for when the sh*t hits the fan in China </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:07:28 </td>
   <td style="text-align:left;"> $BABA $NIO $LCID $QQQ hate on China all you want, but Chinese economy is going to save this market: 
https://www.cnbc.com/2022/03/15/chinas-retail-sales-industrial-data-soundly-beat-expectations.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:07:18 </td>
   <td style="text-align:left;"> $QQQ Russia + China &amp;gt; Biden Harris and Transgender Military </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:06:51 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX  🧞‍♂️😎. 

https://apple.news/At9LjjKVdRp-HeNrnHKxsMg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:06:32 </td>
   <td style="text-align:left;"> $QQQ bloodbath incoming tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:05:48 </td>
   <td style="text-align:left;"> $RIOT $SNAP $QQQ Account Challenge Update:-    
Start Date: Feb 5, 2022    
Starting Balance: $1,800    
Current Balance: $89,637    
Goal: $100,000 by end of March.   
Strategy: Swing Trade Options, Stocks    
     
Watch out for next play-------- technicalanalysis.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:05:43 </td>
   <td style="text-align:left;"> $SPY $QQQ I mean im down to just blame everything on biden like everyone else at this point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:05:18 </td>
   <td style="text-align:left;"> $QQQ confirmed cup and handle reversed.

Technical patterns don’t always pan out but the odds are in favor of significantly more downside. Still expecting a big rally before May 

$SPY  also with the reverse cup and handle, but not quite confirmed yet, small bounce off support but that may not last long if tech breaks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:05:04 </td>
   <td style="text-align:left;"> $SPY $QQQ China gonna take down global markets... 🇨🇳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:04:30 </td>
   <td style="text-align:left;"> $SPY $DWAC $QQQ  
 
White House using Tik Tok stars to blame Putin for high gas prices 
 
Welcome to North Korea folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:03:43 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX   🧞‍♂️😎. . .   

https://apple.news/AZSCRBKM9RqqDme08RmZfkg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:02:09 </td>
   <td style="text-align:left;"> $QQQ baba  tercent looking like a good buy soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:01:14 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX   🧞‍♂️😎. . . 

https://apple.news/AjEekL7m6TIWTIBK-rLPStw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:00:52 </td>
   <td style="text-align:left;"> $QQQ $SPY Just when you thought negative catalysts were over, well, another covid variant, we all know it’s pure Fud but we also know how the market will react. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:00:48 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL 

China announcing Shutdown of Apple factory just before Monday opening of the US market. This is not an accident or coincidence. Xi might have purchased a lot of puts to raise money for aiding Russia. This is not at all implausible. We are at stealth war. Don’t give in. Buy the US stocks and bonds. JMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 10:00:34 </td>
   <td style="text-align:left;"> $QQQ relentless selling on the hk side...pboc will probably announce something again ...to prob up the market ...as usual </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:59:36 </td>
   <td style="text-align:left;"> $QQQ had to bring out the big guns… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:59:34 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX   🧞‍♂️😎. 

https://apple.news/AcjodQJoVSXyRNw7zkiGESQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:58:40 </td>
   <td style="text-align:left;"> $DWAC $SPY $QQQ  
 
White House hires TikTok and Twitter personalities to push White House propaganda 
 
Isn&amp;#39;t that what dictators do? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:57:59 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX  🧞‍♂️. 

https://apple.news/Aqo8ynUZNQ6qXtPkzWYHfHA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:57:13 </td>
   <td style="text-align:left;"> $SPY either way... lower prices likely $QQQ $IWM  
we have gaps around 401 and 396 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:56:51 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F $QQQ $NDX  🧞‍♂️. 

https://apple.news/AxGRcMDUdRSy2oXwsk30Ifw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:56:26 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 
Dont miss the huge move up in gold / silver 
https://youtu.be/kqQMbMXr0aw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:55:46 </td>
   <td style="text-align:left;"> $SPY $QQQ The war will be over the moment China steps in. China will provide satellite support, smart bomb tech, hacking, and most importantly for Russia, underwater delivery systems used by US/NATO to deliver weapons to Kiev via Dnieper River. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:55:41 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX   🧞‍♂️

https://apple.news/AtZoAVlOLQnGmK7PcLBMfDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:54:51 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ ...anyone buying calls in this mess needs to have the inside of their skull scraped and thoroughly power washed.   Bonds and credit in free fall and now China&amp;#39;s fake COVID 3.0 to further disrupt the supply chain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:53:39 </td>
   <td style="text-align:left;"> $SPY $SQQQ $QQQ  Oil futures fell under $100, down from a high around $127 last week. A ~10% drop seemed to fuel a big run last week. Anyone who follows oil prices mind sharing if they believe this will make an impact tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:53:24 </td>
   <td style="text-align:left;"> $SPY $ARKK $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:50:53 </td>
   <td style="text-align:left;"> $QQQ fuck it, bring it down some more…. You think retail will sell, you bat shit crazy… we buy dips and eat bananas, they cheap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:50:50 </td>
   <td style="text-align:left;"> $QQQ same setup as Covid crash. The lowest close before the bull run was on March 16, 2020. Trend is about to change. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:50:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:50:47 </td>
   <td style="text-align:left;"> $QQQ $SPY no chill at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:49:36 </td>
   <td style="text-align:left;"> $SPY $QQQ In about 10 mins to an hour we should be getting extremely bad news.
Brace yourself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:49:31 </td>
   <td style="text-align:left;"> $QQQ We made money again!! Those
who have been following m e have been
making money consistently EVERYDAY. Haters spread hate but I have helped retailers make money for free during past few weeks when most were losing
If you missed my daily plans follow my
twitter @optionboys or if youwant to
join my private group message me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:49:14 </td>
   <td style="text-align:left;"> China Stocks getting smoked yet again $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:48:46 </td>
   <td style="text-align:left;"> $QQQ futes stopped rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:48:25 </td>
   <td style="text-align:left;"> $QQQ ain’t even bother saying anything positive for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:47:18 </td>
   <td style="text-align:left;"> $SPY $QQQ There was simply no reason for oil to run up to $120s, the world has a lot of oil. The US has a lot of oil and Saudi has a lot of oil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:46:46 </td>
   <td style="text-align:left;"> $QQQ wow nearly 2000 pts on the hsi...in 2 days ...sign of things to come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:46:00 </td>
   <td style="text-align:left;"> $SPY $QQQ Could really use more panic sellers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:45:47 </td>
   <td style="text-align:left;"> Oil is cratyerrriiiinnnggg $uso  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:44:19 </td>
   <td style="text-align:left;"> $SPY $QQQ oil is coming down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:43:33 </td>
   <td style="text-align:left;"> $QQQ We made money again! Those
who have been following me have been
making money consistently. Haters
spread hate but I have helped retailers
make money for free during past few
weeks when most were losing
If you missed my daily plans follow my
twitter @optionboys or if you want to
join my private group message me. (it&amp;#39;s
actually fairly cheap to join). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:42:04 </td>
   <td style="text-align:left;"> $QQQ wow oil price down because of covid again...haha...market really chaotic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:40:30 </td>
   <td style="text-align:left;"> $SPY $QQQ Chinese market down again? wtf... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:39:22 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I’m gonna end a perma bulls career tomorrow...🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:36:45 </td>
   <td style="text-align:left;"> $QQQ $SPY  Expected inflation down with crashing oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:34:11 </td>
   <td style="text-align:left;"> $TSLA pump $SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:33:49 </td>
   <td style="text-align:left;"> $SPY $QQQ prediction tomorrow.
bloodbath. if i’m wrong, shit on me all you want </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:33:33 </td>
   <td style="text-align:left;"> $CVX uh oh oil is getting fucked $SPY $XOM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:33:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA WE NEED MORE BING BONG 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:33:20 </td>
   <td style="text-align:left;"> $SPY $QQQ Hang Seng continues to crash, I think there are some anticipations that we will enforce some sanctions on China soon to punish them for helping Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:32:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 

It’s over... flush it, all of it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:32:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY talked to some ex military officers i work with...they said no western sanctions will stop russia...why?...there are literally over 3 billion people in china india pakistan etc that want to buy from them...they have billions of people that need thier energy,resources,  and food. World has changed those nations are industrialized and have cars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:30:38 </td>
   <td style="text-align:left;"> $SPY  … death cross 👇🏻🔮✅

$QQQ $IWM $DIA $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:30:28 </td>
   <td style="text-align:left;"> $QQQ $SPY So, the Heng Seng about to go full splash mountain.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:28:26 </td>
   <td style="text-align:left;"> $QQQ Leme guess, up now, down by morning or EOD tomorrow or EOW. Doesnt matter. Headed lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:28:09 </td>
   <td style="text-align:left;"> Market Volume Barometer 3-14-2022 
Sentiment: SKITTISH 
Volume: 12% 
Real Feel: SCORCHING 
Cycle: BEARISH II 
Portfolio: CASH 
Next Day Move: UP 
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/ 
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:26:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $SQQQ $SPXU $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:26:26 </td>
   <td style="text-align:left;"> $AAPL those with their portfolio bleeding to death, wondering what is safe  
 
Check out the article via @TipRanks below, makes a good bull case in 1 of the worst trading environments we&amp;#39;ve had in a while. 
 
$SPY $QQQ  
 
https://www.tipranks.com/news/article/apple-stock-safe-pick-amid-geopolitical-risks/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:26:24 </td>
   <td style="text-align:left;"> $SPY $QQQ  a lot of top wicks past hour. Tmrw should be interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:26:06 </td>
   <td style="text-align:left;"> $QQQ Bitcoin starting to jump  
 
Risk on for tomorrow 
 
May not be smart to stay short during potential ceasefire talks with oil prices already falling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:25:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Oil crashing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:21:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $$DJIA $ARKK 

It&amp;#39;s been 13 months!!!!!  

Growth stocks are utterly oversold. Soon things will change. Nothing lasts forever and we are long past the point when things should have changed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:18:12 </td>
   <td style="text-align:left;"> $QQQ Give this another 15-20 minutes and it will turn red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:18:09 </td>
   <td style="text-align:left;"> Daily Recap 187% total gains 
 
Top Gainers: 
$QQQ &amp;amp; $SPY 0dte puts closing over 100% each made by u.trhub.net/imderekd 
 
u.trhub.net/noob also got in a quick 29% gain SPY puts 
 
$PFE $53 calls 3/25exp opened at 1.08 - we&amp;#39;ll see where this goes. put in by u.trhub.net/dcharts 
(Not too late to get into this position) 
 
u.trhub.net/djbrod24 has a TGT $205 puts with 4/01exp, got in at $5.00 closed the day at 4% - STILL OPEN 
 
u.trhub.net/spoobysnax sold to open $ON vertical spread with $60/$55 puts  4/14exp going for a few week swing 
 
The #AI Alert bot got in some signals small winning signals today. u.trhub.net/trade+hub+ai+alerts 
 
linktr.ee/thetradehub </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:15:58 </td>
   <td style="text-align:left;"> $QQQ FTSE just turned red. Bad sign. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:13:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM life of a trader </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:13:26 </td>
   <td style="text-align:left;"> $QQQ 

318 to 340 game continues

Feedback welcome </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:11:23 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

Futes looking weak, like a 🐂....🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:09:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM We should have a bull rally following FOMC. I will not long anything overnight until then, when the market launches (assuming no global escalations). That&amp;#39;s my anticipation. Good luck, fellow traders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:07:33 </td>
   <td style="text-align:left;"> $SPY $QQQ always expect the unexpected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:06:51 </td>
   <td style="text-align:left;"> $QQQ .. I am guessing a few traders are watching that prior pivot low move that bottomed out on 2/24/22 at 318.26 (TradingView) .. (and which honestly did not necessarily amount to much in bigger picture)...?  Trap senses are going off... Imo = Find support/demand levels that have not been tested yet just below that prior pivot low as a potential temporary bounce .... at LEAST as a contingency/backup plan in case going long above the pivot low, or trying to take momentum for a decent move to downside. Big money likes to use pivot moves to trap bulls (w/ stops just below) .... AND bears trying to take a breakout to the downside (with the support level just below).. Truly is a casino as a TRADER... (I have seen these levels play out many times on many timeframes).... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:06:44 </td>
   <td style="text-align:left;"> $SPY  $DIA   $DJIA   $QQQ  $NASDAQ  ⭕️ 

    It’s time to shake these flees off 

             ♠️😎   🧞‍♂️    😎♠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:05:42 </td>
   <td style="text-align:left;"> $SPY $QQQ Didn’t hear a peep on COVID cases from China during 2020/2021, but now all of the sudden they’re shutting down factories and reporting cases? While we suffer from high oil prices and inflation? Interesting timing……. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:03:34 </td>
   <td style="text-align:left;"> $QQQ $SPY I am actually quite shocked at how clean the TA is. This is a clear downtrend. The chart is respecting the downtrend line and showing follow through, not much chop or fake outs . The underlying stocks are in very neat downtrends. I dont know what you bulls are seeing but its almost 100% clear to me we are headed to 200 week EMA on QQQ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:03:32 </td>
   <td style="text-align:left;"> $SPY $QQQ hmmm… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:03:05 </td>
   <td style="text-align:left;"> $TMC -worlds largest nickel reserves 🚀
“NICKEL PLAY is the BEST EV PLAY! “
-Nickel supply continue to diminish while its cost continue to go up! 
-Ukraine war and inflation make nickel crisis worst! $TSLA $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:02:57 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:02:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM 8:30 am tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:01:44 </td>
   <td style="text-align:left;"> $QQQ bottom&amp;#39;s close losers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:01:27 </td>
   <td style="text-align:left;"> $QQQ $SPY a lot of ‘death cross’ doom chatter goin on… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 09:00:13 </td>
   <td style="text-align:left;"> $QQQ $SPY  ==&amp;gt; WAR HAS NOTHING TO DO WITH INFLATION &amp;amp; ALL THE ECONOMIC MESS IN THIS COUNTRY.   FIRE THIS FUCKING GOVERNMENT...  WHAT A F*CKING JOKE!! 😷😷💀💀💀 
. 
$TSLA  $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:59:55 </td>
   <td style="text-align:left;"> $QQQ it’s dangerous to be a bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:59:23 </td>
   <td style="text-align:left;"> #TradeOfTheDay 
 
$CHPT $16 puts 3/18exp for 193% as stock closes -9.72% bringing nice gains for those who played puts before noon. played by u.trhub.net/shuby 
 
$MATX $110 calls 3/18exp for 133% MATX took off at market open closing +6.09% 
 
$QQQ $318 puts 3/14exp for 133% solid day for puts if you got in before noon. QQQ closed -1.92% 
 
$SPY $421 puts 3/14exp for 120% SPY closed -.73% 
 
linktr.ee/thetradehub </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:58:34 </td>
   <td style="text-align:left;"> $spy $qqq $sqqq $amd $fb
What is driving down the market besides inflation, money printed without a backup, war &amp;amp; covid?
The qqq bubble tech!
Maybe as they keep deflating we can finally find a bottom… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:58:15 </td>
   <td style="text-align:left;"> $QQQ tech will leave the bears in the dust </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:57:25 </td>
   <td style="text-align:left;"> $QQQ rtes at 2.14 means it considers inflation more of a problem than a recession </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:56:27 </td>
   <td style="text-align:left;"> $QQQ with 10 yr at 2.14, our only problem is inflation…we will see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:56:27 </td>
   <td style="text-align:left;"> $QQQ NASDAQ HERE IS THE MARKET WATCH FOR THE FOR THIS WEEK. ..PLEASE JOIN MY DISCORD CHANNEL  (FOR FREE )FROM MY HOME PAGE  FOR DAILY UPDATES, NEWS, TRADES, SHORT INTEREST INFORMATION WHICH I UPDATE DAILY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:56:24 </td>
   <td style="text-align:left;"> $NASDAQ $QQQ $SPY $DJIA 

AWESOME! Now Saudi Arabia wants to strengthen their ties with Xi because of our idiot-in-chief? So the rumor about them not picking up Biden’s call RE: oil must’ve been true… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:55:52 </td>
   <td style="text-align:left;"> $QQQ A pullback/correction becomes a bear market if a recession is likely. Fundamental data (labor, construction spending, PMIs, etc.) all support a solid economic base. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:55:41 </td>
   <td style="text-align:left;"> $QQQ i dont know about ya but im just loading the boat until Trump runs 2024! Thanks Biden aka the 🤡 for bring the market down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:54:54 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY what are we thinkin? Maybe a nice -5% in each tomorrow? 😁😁😁😁😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:54:06 </td>
   <td style="text-align:left;"> $QQQ Why up so much after hours with PPI🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:53:00 </td>
   <td style="text-align:left;"> $QQQ why are people bullish we are making new 52 week lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:51:50 </td>
   <td style="text-align:left;"> $QQQ PPI at 8:30AM will bring inflation back to the forefront. 
It’s going to be a nasty number. 
No support below 318.6. 
308 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:50:27 </td>
   <td style="text-align:left;"> $SPY  $NASDAQ  $NDX $QQQ $ES_F 

Hold on     We will make it rain again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:48:28 </td>
   <td style="text-align:left;"> $QQQ Invesco QQQ Trust Series 1 Option Alert: Apr 14 $360 Puts at the Ask: 8 vs 12053 OI🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:47:01 </td>
   <td style="text-align:left;"> $QQQ wildly bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:47:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 83559600. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:46:20 </td>
   <td style="text-align:left;"> $QQQ continuing to leg in on any dips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:44:54 </td>
   <td style="text-align:left;"> $QQQ perfectionism is so dangerous.  I exited my swing near 317 end of day.  I essential must make peace  with not collecting ever dollar on a swing  low to high.  It doesn’t fit my personality to stay the course because in that same timeframe there are about 3 to 4 other scalps in a 7 to 30 min timespan I am just as efficient at forecasting and executing.  I’ll still lament when it flys without me though but the game is to generate and keep income and that doesn’t require perfection. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:44:50 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:41:58 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWN 

Laughable that everyday futures are green and then the sell off during trading hours.   Complete joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:41:21 </td>
   <td style="text-align:left;"> $VXX Yall are always bitching about market manipulation when indices do nothing but go straight up and individual smaller and mid caps go straight down.

Well- if that&amp;#39;s the case...can&amp;#39;t manipulation go both fucking ways? 

I get it. Scare the heebies out of retail by declaring vxx new buys suspended.

Well what happens when institutions see retail sentiment this low and rug pulls bears? Rapidly selling off VXX on VIXPERATION. forcing over supply and sudden drop in demand  as retailers pile into short ETFs and puts across the market while all indices are at 3 month supports, and many ETFs such as XBI and ARKK are wicking below monthly supports after 1+years of absolutely redicilous selling pressure? Lowest rsi in their history? Lmao ..all while nobody can even buy the VXX dip 😂😂

I&amp;#39;m just bullshittin. I don&amp;#39;t believe manipulation is anywhere near the levels stock twinks seems to think its at..

But ya wanna bitch about manipulation when it fits your narrative ya?...
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:40:54 </td>
   <td style="text-align:left;"> $tsla $SPY $QQQ As WW3 are looming and I can’t fill my car for less than $90, I find comfort in knowing that nobody’s feelings got hurt on Twitter today and the only thing that really matters is we have a woman as Vice President. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:39:46 </td>
   <td style="text-align:left;"> Grab a Slice of QQQ While It’s Trading at a Discount $SPY $QQQ https://etfdb.com/etf-education-channel/grab-a-slice-of-qqq-while-its-trading-at-a-discount/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:39:12 </td>
   <td style="text-align:left;"> $QQQ i called the top, i’ll call the bottom for you guys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:39:07 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : Grab a Piece of QQQ While It&amp;#39;s Trading at a Discount https://www.stck.pro/news/QQQ/24397268 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:39:00 </td>
   <td style="text-align:left;"> $QQQ hope ccp china market dont fuck up again tonight, unbelievable ccp let their market crash like the russian </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:37:24 </td>
   <td style="text-align:left;"> $QQQ $SPY puts printed!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:35:39 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.cnn.com/2022/03/13/politics/biden-approval-gas-prices-ukraine/index.html 
 
Americans are happy with the way President Biden is handing the situations in Russia and Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:34:56 </td>
   <td style="text-align:left;"> $BTC.X only hope btc to 250k to save this market !!!$spy $ndx $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:34:14 </td>
   <td style="text-align:left;"> $QQQ found this from a post somewhere, quite interesting

“The Nasdaq moved toward its 40-month exponential moving average which provided a bottom for corrections in the past. The only corrections to break through that line are 2000, 2008, and 2020.

If the index returns to the trend line from the 2/10 high and the five-day trend line , that would mean a +1.64% gain for Tuesday.

The one-day trend line leads to a -3.29% decline.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:34:13 </td>
   <td style="text-align:left;"> $SPY $QQQ Elon is definitely a buy high sell low kind guy. He was pumping market when it was at all time highs. And now he says sell. #notaleader </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:33:22 </td>
   <td style="text-align:left;"> $QQQ I love 8pm - 6am when futures are green…then the pain starts around 601 and gets much worse until 4pm, every day, for months, and a LOT longer to go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:33:11 </td>
   <td style="text-align:left;"> $QQQ If the QQQ don&amp;#39;t bounce above $322 and hold tomorrow. Here is a play for you. Sell March 18, $300 calls, and help finance by selling $310.  Risk $178 to make over $800 for a single contract. Of course, the more contracts you buy, the more you risk but the more you will make if the trade works. This trade should work if the QQQ don&amp;#39;t get back and hold $322. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:32:28 </td>
   <td style="text-align:left;"> $GME https://www.reddit.com/r/Superstonk/comments/tea2c8/16_i_feel_something_spicy_coming/ $AMC $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:32:10 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-03-14 Options Analysis Video: 
https://www.youtube.com/watch?v=3TEm-BrTIhg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:31:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $BABA $NIO 
multiple videos from multiple news outlets … who’s the real hypocrite 🤥

https://mobile.twitter.com/imraansiddiqi/status/1497607326487826435?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1497607326487826435%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fd-3269678536654260914.ampproject.net%2F2202230359001%2Fframe.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:30:52 </td>
   <td style="text-align:left;"> $QQQ funniest video I’ve seen this year, and truly sums up our current state of affairs 

https://youtu.be/pTRoFkw1Vlw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:29:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $DWAC

Good news and bad news:
Good news is Year 1 is done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:28:02 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $NASDAQ $NDX  🧞‍♂️🤑🧞‍♂️

https://music.amazon.com/albums/B01CE4QF3K?do=play&amp;amp;trackAsin=B01CE4QICI&amp;amp;ref=dm_sh_twWGiwt6qtGujV0VFvxjYXJtR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:27:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA I was about to say, &amp;quot;Maybe next time don&amp;#39;t vote for a senile old dickweed.&amp;quot; but we all know no one actually voted for him. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:26:53 </td>
   <td style="text-align:left;"> $QQQ 1Y Chart looks brutal to be honest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:26:11 </td>
   <td style="text-align:left;"> $SPY $QQQ A new way to make money, just short whatever Cathie Wood is buying lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:25:19 </td>
   <td style="text-align:left;"> $QQQ Dax bleeding heavily now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:22:11 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Look at the RSI for the Nasdaq on the weekly time frame and tell me you’re not a buyer of stocks today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:20:40 </td>
   <td style="text-align:left;"> $QQQ Nikkei red, Dax red. Dow red. S&amp;amp;P red. 
Naz will be bleeding shortly. 
Sellers pumped the AH Trading to make their selling more lucrative tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:18:17 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY $IWM  
 
DO NOT sell at bottom, wait 40 MORE HOURS! 
 
We could see Morningstar any time! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:18:02 </td>
   <td style="text-align:left;"> $SPY and $QQQ looks like it&amp;#39;s going lower. https://youtu.be/RAnZ6kF14w8 https://youtu.be/RAnZ6kF14w8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:16:26 </td>
   <td style="text-align:left;"> $SPY You keep selling here I keep the buying machines going promise 

  🧞‍♂️🤑 $QQQ $NDX $DIA $SPX 🤑🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:16:04 </td>
   <td style="text-align:left;"> $SPY $QQQ The most encouraging sign is that oil prices seem to have peaked, lower oil prices are bullish for the economy and the stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:15:44 </td>
   <td style="text-align:left;"> US Government Bond Prices Dip as European Shares Rise https://www.billionaireclubcollc.com/us-government-bond-prices-dip-as-european-shares-rise/ $SPY $QQQ $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:14:43 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX  🧞‍♂️

There’s so much stuff to buy here it’s Ridiculous to figure out where to Allocate the funds to </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:13:52 </td>
   <td style="text-align:left;"> $SPY Bulls... kings of the AH session! 👏🏼👍🏻 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:13:40 </td>
   <td style="text-align:left;"> $QQQ This index is done. 
Same pattern every night. 
Futures pumped by big sellers and shorters. 
Market sold off hard after first hour of trading takes it higher. 
308 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:13:09 </td>
   <td style="text-align:left;"> $QQQ Interesting it could not hold SMA100 today. Very interesting. On watch. Could possibly bounce if it regains it. So if it does a weekly option scalp in the money calls for a $5 scalp for options expiring of March 16. If no bounce, then never mind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:13:01 </td>
   <td style="text-align:left;"> $TMC $DJIA $QQQ $IWM $SPY 

TMC - the metals company, has been my hedge against Ukraine war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:12:31 </td>
   <td style="text-align:left;"> $QQQ bull market is when you increase your money. Bear market is when you increase your positions. 

Stay the course. It’ll all go back up eventually. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:09:52 </td>
   <td style="text-align:left;"> $QQQ if we continue to sell off overnight and tomorrow then we will likely bottom with the Fed. If we bounce, the Fed will wreck this market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:08:56 </td>
   <td style="text-align:left;"> $QQQ Good TA concept to watch for tomorrow = will old support potentially becoming new resistance ...?  Depending on where we open tomorrow, from scalpers perspective I will be watching that 320-322 level above for a decent rejection OR breakdown... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:05:38 </td>
   <td style="text-align:left;"> $QQQ I love you, bears 
But I will just be buying every dip no matter what </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:05:05 </td>
   <td style="text-align:left;"> $TSLA $AMD $SPY $QQQ 

🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:03:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY First Joe Biden blamed corporate price gouging for inflation, then he pivoted and blamed Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:03:07 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-03-14 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=Q9JQpIkUy8g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:02:20 </td>
   <td style="text-align:left;"> $QQQ $SPY $DINI $IWM  
 
Elon musk challenges Vladimir Putin to a single combat: Who will win?  
  
Elon musk:   
Age: 50  
Height: 6&amp;#39;2  
Weight: 180lbs  
Martial Arts Skills: Jiujitsu  
  
Vlad Putin:  
Age: 64  
Height: 5&amp;#39;7  
Weight: 154lbs  
Martial Arts Skills: Taekwondo black belt  
  
Our pick: Putin by a slight edge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:01:59 </td>
   <td style="text-align:left;"> China Locks Down Langfang City Near Beijing Due to Covid $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:01:35 </td>
   <td style="text-align:left;"> $AMC  
 
futures green led by tech $QQQ 
 
WIN 
 
sitting on vwappy 
 
🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:01:33 </td>
   <td style="text-align:left;"> The last 6 times oil had a 50% deviation from the trend since 1970 there has been a recession. The only difference is that this time is the only time in America history where inflation is 10% and rates are still 0%. Paper assets are going to evaporate in 2022. $USO $SPY $QQQ $ARKK $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 08:01:22 </td>
   <td style="text-align:left;"> $SPY $QQQ Let the games begin 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:59:37 </td>
   <td style="text-align:left;"> Live updates: Ukraine says Russia forces retreat at Mariupol https://www.billionaireclubcollc.com/live-updates-ukraine-says-russia-forces-retreat-at-mariupol/ $DJIA $QQQ $SPY $DIA $DXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:59:24 </td>
   <td style="text-align:left;"> $TSLA awesome, another short opportunity. All the bulls celebrating their imaginary gains while market is closed 🤣
Say it w/ me- IDIOTS 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:58:22 </td>
   <td style="text-align:left;"> $ES_F bear flag out the gate. 

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:57:47 </td>
   <td style="text-align:left;"> $QQQ Down 3 days in a row. 334.99 | 331.27 | 324.4 | 319.07 |  https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:57:35 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AMD 

Me checking my portfolio everyday knowing it’s going to be a bloodbath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:52:30 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/LWBbuLvBLEE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:52:05 </td>
   <td style="text-align:left;"> $QQQ Pissed i didnt buy calls; didn&amp;#39;t realize this was the 3rd straight red day, no way in hell there will be a 4th off a 2% loss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:51:48 </td>
   <td style="text-align:left;"> $SPY mood all week.

$QQQ $UVXY $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:51:36 </td>
   <td style="text-align:left;"> S&amp;amp;P and Nasdaq Set Up For Big Loss Tomorrow $QQQ $SPX $DJI https://talkmarkets.com/content/stocks--equities/sp-and-nasdaq-set-up-for-big-loss-tomorrow?post=347948 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:50:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA waiting for putin to response to elon. I will pay , pay per view and make bets if they get into a ring!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:49:57 </td>
   <td style="text-align:left;"> $QQQ $AAPL $SCHD $NVDA buying all four and a few others tickers long term tomorrow. 20-30 year time horizon for me. Will continue to add. Most of you will be apart of the fomo when everything starts to run again. Market is forward looking and pricing most everything in (WW3 could change things but I think the media is just scaring most people). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:48:43 </td>
   <td style="text-align:left;"> $QQQ can this shit dump already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:45:05 </td>
   <td style="text-align:left;"> $QQQ Major tech city in China in COVID lockdown....👎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:44:57 </td>
   <td style="text-align:left;"> $QQQ this was overdone with aapl covid problems today.  Buying tomorrow am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:44:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $AAPL harvested crops returned with fruits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:41:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK When years start this badly they tend to end gladly (although global inflation, WWIII issues, and related crap might not follow suit). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:39:56 </td>
   <td style="text-align:left;"> Courageous even when you know there is a jail sentence waiting for doing this... hats off! 
 
$QQQ $SPY $AMD $AAPL $SOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:39:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $Vvix OH look! Futures ripping... 🙄 Stop me if you&amp;#39;ve seen this movie a few dozen x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:38:59 </td>
   <td style="text-align:left;"> UKRAINE’S PRESIDENT ZELENSKY: TALKS WITH RUSSIA WILL RESUME ON TUESDAY. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:38:20 </td>
   <td style="text-align:left;"> $SPY $QQQ From Bespoke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:37:22 </td>
   <td style="text-align:left;"> Nasdaq 100 Dips to New 2022 Low, S&amp;amp;P 500 at Risk as Death-Cross Flashes Bearish Signal https://www.billionaireclubcollc.com/nasdaq-100-dips-to-new-2022-low-sp-500-at-risk-as-death-cross-flashes-bearish-signal/ $SPY $DJIA $QQQ $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:37:07 </td>
   <td style="text-align:left;"> $SPY $QQQ Ascending triangle on futures uh-oh... turn around tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:36:13 </td>
   <td style="text-align:left;"> Real disposable income for Americans now down 9% yoy and much lower than the previous record low in 1974 the last time America was ravaged by inflation. Now the fed has to raise rates to fight inflation over 10%. The game is over folks. Buy &amp;amp; holders RIP. $ARKK $SPY $QQQ $GME $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:33:58 </td>
   <td style="text-align:left;"> $QQQ change speculative holds for good companies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:33:50 </td>
   <td style="text-align:left;"> $QQQ c&amp;#39;mon bears if you don&amp;#39;t play the bounce you&amp;#39;ll be silent again soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:33:37 </td>
   <td style="text-align:left;"> 12-month lows have expanded to over 1500 stocks. People who only go off $SPY and think the market has hardly corrected are kidding themselves. We have had an historical washout since February 2021. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:33:15 </td>
   <td style="text-align:left;"> $QQQ $SPY this decline will wipe out all Covid gains plus more. Time to get those stimulus checks back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:33:07 </td>
   <td style="text-align:left;"> $QQQ $spy the markets will rejoice when Biden is out of office </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:32:05 </td>
   <td style="text-align:left;"> $QQQ bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:32:03 </td>
   <td style="text-align:left;"> $QQQ $SPY imagine CNBC telling you this is just a small tiny correction this is worse than March 2020 this is a stock market crash we havent even had 1 rate hike yet and were crashing like 2018 when rate-hike-happy Powell was on a tirade. 20-30% more downside? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:32:02 </td>
   <td style="text-align:left;"> $SPY $QQQ you guys know the drill.by. now
 Green premarket= red.market hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:31:12 </td>
   <td style="text-align:left;"> $QQQ $SPY lots of new people will lose all their money. Fed built up confidence and will now crush these clowns that think they’re gonna be millionaires </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:30:05 </td>
   <td style="text-align:left;"> $SPY idiots say “priced in”…sub novice traders who start their strategy with Hopium. Don’t be that guy. When you think it can’t go any lower, it goes lower. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:29:47 </td>
   <td style="text-align:left;"> $QQQ $SPY you guys fail to understand valuations reached a level that should have never been. They’ll never return to those levels for a long long time so even buying now offers no upside and still plenty of downside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:29:14 </td>
   <td style="text-align:left;"> $AFRM Broke Support
Now who knows where bottom is 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:26:11 </td>
   <td style="text-align:left;"> SPDR S&amp;amp;P 500 ETF (ETF:   $SPY), ( $ARKK) – Has The Stock Market Found A Bottom? $DJIA $QQQ $VIX https://www.billionaireclubcollc.com/spdr-sp-500-etf-etfspy-arkk-has-the-stock-market-found-a-bottom/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:25:58 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Why sell the US equities? 

We the USA is the number one in military might (25 times more powerful than the next in ranking).

We the USA is the number one producer and exporter of agricultural and livestock products. 

We the USA has more untapped natural resources than any other country in the world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:25:38 </td>
   <td style="text-align:left;"> $QQQ $SPY bullshit stocks will decline over 95% and non bullshit stocks will decline around 70%. For reference bullshit = affirm and cloudfare, non bullshit = Microsoft and apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:23:17 </td>
   <td style="text-align:left;"> $QQQ that entire reversal today was set up overnight during the Globex (&amp;quot;Futes&amp;quot;) session... Those resistance levels were new.    .. and they turned price.  Caught my attention because this year .. I would say 95% or more of the time it is a level OUTSIDE the overnight Globex session ... so they are up to something Lol... this week will be  fun. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:22:34 </td>
   <td style="text-align:left;"> $QQQ 

@vogs21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:21:25 </td>
   <td style="text-align:left;"> $QYLD $NUSI $QQQ $NDX Been away due to getting food poisoning last week and trying to be patient for the FOMC meeting, per my plan since December.  Another month of holding back on buying the $1M worth of these high yield dividend ETFs saved me another 5% in equity.  
Trying to target $18.50 to get 13% yield.  Getting to the point where I’m almost ready to commit to the position, knowing the index can likely continue to drop.  This is strictly for my “annuity” like income stream for many years to come and different treatment/mentality than my regular trading/investing.  
Now, if Powell messes with me and does his .25 hike and typical “dovish speech” Wednesday, I may wait for the FOMC meeting minutes to come out in a few weeks for the real hawkish truth to come out.  Would mean giving up yet another dividend, but waiting for the rates to rise has been working for me so far.
Also, fully prepared for div to (possibly) drop to ~.16, but that’s still 10% yield. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:21:24 </td>
   <td style="text-align:left;"> $QQQ The oligarchs coming thru on the crypto boost. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:21:16 </td>
   <td style="text-align:left;"> Goldman Derivatives desk: Our GS-EQMOVE model estimates that the probability of a 5% down-move over a 1-month period is 11% while the options market is pricing in a 31% probability of a 5% down move over the next month. This suggests puts are more overvalued than any time over the past five years. 
 
$SPY $SPX $ES_F $QQQ $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:19:45 </td>
   <td style="text-align:left;"> $QQQ monthy. thinking that if we close below that 12yr resistance the way to 18yr R-turned-S is open. perfect date with pre-covid levels maybe in Nov? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:19:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $XLE 

Watching those who are bullish on the market right now is like watching the  degenerate gamblers in a Las Vegas Sands casino. 

The truly sad part?

Your odds at the Wynn might be better than your odds in the market this year. 

Just awesome. 

We are so screwed. 🤦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:17:15 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Bond people: DUH… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:15:30 </td>
   <td style="text-align:left;"> $TLT $SPY $QQQ  The market is going to crash and there is going to be a recession before the Fed even raises interest rates once. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:15:15 </td>
   <td style="text-align:left;"> $QQQ 

That’s a lot of 4,100’s at interesting increments. Couple 600’s, some 1,700’s… Criminal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:13:59 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Be calm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:12:54 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Look bulls, he’s back on your side enjoy the Crammer curse!!!🤣🤣🤣

https://www.cnbc.com/2022/03/14/cramer-says-stocks-may-bottom-sooner-than-expected-because-wall-street-is-so-negative.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:11:35 </td>
   <td style="text-align:left;"> $QQQ it&amp;#39;s a correction you pansies $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:11:23 </td>
   <td style="text-align:left;"> $QQQ lets see what papi powell does this week ... hoping for the best ! lol $DOW $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:10:02 </td>
   <td style="text-align:left;"> $QQQ Why don&amp;#39;t we see a flush yet? It&amp;#39;s usually the retail that causes the flush. Smart money sells it orderly. Possible explanations are retailers are way smarter than what the market assumes OR retail is bag holding huge and not ready to part with their shares, slowly accumulating while averaging down expecting a V reversal. Except, this time there&amp;#39;s no V reversal. It will be choppy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:09:25 </td>
   <td style="text-align:left;"> $QQQ    losers with PUTIN PUTS tonight 
 
already fcked AH....sleep tight HAHA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:08:34 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA $SQQQ  https://youtu.be/fJMpfUO_f-g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:07:51 </td>
   <td style="text-align:left;"> Cramer says stocks may bottom sooner than expected because Wall Street is so negative

$SPY $QQQ $IWM

https://www.cnbc.com/2022/03/14/cramer-says-stocks-may-bottom-sooner-than-expected-because-wall-street-is-so-negative.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:07:22 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA $SQQQ https://www.politico.eu/article/china-is-not-party-russia-war-on-ukraine-foreign-minister/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:06:07 </td>
   <td style="text-align:left;"> $BA orders flying in. $270 Price Targets. Go 🇺🇸 $QQQ $SPY the fed is in control. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:05:20 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I expect to see one final sucker pump from this market to trap last of the moronic buy the dip traders before we witness the dump of  a millennium... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:05:08 </td>
   <td style="text-align:left;"> $QQQ lol imagine nato loosing to the underdog nations </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:04:22 </td>
   <td style="text-align:left;"> $QQQ where are we </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:01:51 </td>
   <td style="text-align:left;"> $AMZN always bullish. $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:01:25 </td>
   <td style="text-align:left;"> $QQQ $SPY wasnt cramer pumping Chinese stocks for ages? Dude literally just said anyone in them “deserve their losses” rofl what a clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 07:00:27 </td>
   <td style="text-align:left;"> $SPY $QQQ what? We are moving into a new paradigm of stupidity and gaslighting. Inflation is good and massive government spending backed by money printing doesn&amp;#39;t cause it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:59:24 </td>
   <td style="text-align:left;"> $QQQ Weekly indicators are extremely oversold. 100ma offering support. Bounce around here before heading lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:59:00 </td>
   <td style="text-align:left;"> $SPY $QQQ common prosperity is the future </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:58:19 </td>
   <td style="text-align:left;"> $SPY $QQQ Watch what happens after 9pm tonight. News I&amp;#39;m hearing ain&amp;#39;t good. 
Stay tuned </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:58:17 </td>
   <td style="text-align:left;"> $DIA $SPY $AAPL $QQQ 

Earnings this week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:58:15 </td>
   <td style="text-align:left;"> $SPY $QQQ
The greatest wealth is made coming out of a bear mkt. This  is a tough market right now , you should be treading lightly and preserving capital. As a very experienced “short” trader , I have given some profits back over the last few weeks, it’s been that tricky/difficult. 
So what should you do ? 
A) hopefully you have stopped buying the dips 
B) trade smaller shares 
C ) it’s ok to step back and just observe the market without having to make a trade everyday .
D) Keep tight stops , the market always goes down much more quickly and intensely than when it goes up.
E) A strategy I have used  is to not trade the first hour. If you wait until 10:30-11:00 you can find plenty of intra day reversals during this time  without the risk of being whip sawed. 
F) Holding a position overnight for 3-5 
 days ( with smaller number of shares) will give you a better opportunity to have a winning trade than day trading , especially if you are shorting bc of the trend. 
G) Take profits!
GLTA!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:57:47 </td>
   <td style="text-align:left;"> $SPY $QQQ   
 
https://www.cnbc.com/2022/03/14/cramer-says-stocks-may-bottom-sooner-than-expected-because-wall-street-is-so-negative.html?&amp;amp;qsearchterm=cramer 
 
Jim Cramer thinks we are close to the bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:54:58 </td>
   <td style="text-align:left;"> $QQQ Bitcoin leading indicators now days. BTC flying right now. Tomorrow massive green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:54:10 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $IWM  
 
Literally nobody: 
 
USA: China will be helping russia!  
 
China: We are? Well... guess we are now, boy!  
 
Unbelievably stupid american government. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:53:46 </td>
   <td style="text-align:left;"> $SPY $QQQ The bears have suffered so much pretty much since March 2020, it is time for them to have a little bit of a fun and not going broke. In a long run the bulls still have the upper hand as long as the US economy continues to do well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:53:37 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA what&amp;#39;s with the afterhours pump? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:52:50 </td>
   <td style="text-align:left;"> $QQQ bears get greedy on a triple bottom extreme bearish sentiment. Hope yall closed your puts today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:51:53 </td>
   <td style="text-align:left;"> $QQQ buying puts on all the tech earnings coming up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:51:44 </td>
   <td style="text-align:left;"> $GFS tech name that holding up extremely well while the market flushes lower. If we are to see an oversold bounce in $QQQ this would be a main focus of mine. Holding above all key MAs &amp;amp; tightening. 
#IBDPartner @InvestorsBusinessDaily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:51:17 </td>
   <td style="text-align:left;"> This is so satisfying! $SPCE $ARKK $QQQ $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:50:39 </td>
   <td style="text-align:left;"> $QQQ futes rippin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:49:44 </td>
   <td style="text-align:left;"> $QQQ We made money again! Those who have been following me have been making money consistently. Haters spread hate but I have helped retailers make money for free during past few weeks when most were losing. If you missed my daily plans follow my twitter @optionboys or if you want to join my private group message me.(it’s actually fairly cheap to join) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:49:09 </td>
   <td style="text-align:left;"> $QQQ $200 by end of year, no doubt about it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:48:43 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $NVDA $TSLA CNBC talking douches all parrot that there is more room to the downside. Bottom is in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:48:11 </td>
   <td style="text-align:left;"> $TLT $TMF where all the clowns saying this would go up for the last 2 years when the market crashes. indices in a bear market and small caps are down 70-80% and 20 year blowing through march 2021 lows like its butter. 67% of stocks under 200ma on the NYSE. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:48:09 </td>
   <td style="text-align:left;"> $QQQ my June $335 puts just keep printing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:48:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM technical analysis for tomorrow. 
 
https://youtu.be/qjLvQX8itpM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:47:59 </td>
   <td style="text-align:left;"> ALL major bottoms come in the overnight session often when a session has closed at or near session lows 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:47:47 </td>
   <td style="text-align:left;"> $QQQ officially entered bear market! How could i go wrong with the puts that I opened at the close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:46:58 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Wen moon?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:46:41 </td>
   <td style="text-align:left;"> $BULZ $QQQ $TQQQ 2009 and 2018 monthly chart shows three new monthly lows created with the fourth month retesting the third month close. So far March is barely creating the new third month low. This means this week will see one final push lower to create new lows combining it with the weekly being close to oversold territory for the final bottom and nice bounce heading into April when market gets CPI report which may retest March close. History repeats its self and chart don’t lie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:46:02 </td>
   <td style="text-align:left;"> Surge in energy prices suggests high probability of recession 📉 
 
$SPY $IWM $QQQ $DJI $VIX 
 
#unitedtraders #news #stockmarket #stock #economy #recession </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:46:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 83559600. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:45:57 </td>
   <td style="text-align:left;"> NASDAQ 100 ($QQQ) Most Active during today $AAPL $AMD $JD $NVDA  
 
Learn more: https://www.finscreener.org/screener/most-active/stocks/nq100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:45:45 </td>
   <td style="text-align:left;"> Very Weird: What I personally do on days when the stock market is down $SPY $SPX $QQQ $VXX  
 
https://youtu.be/P8vGLeTXq18 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-15 06:45:27 </td>
   <td style="text-align:left;"> Every CEO &amp;quot;theres a lot of problems going on in the world and they arent going away any time soon. We are in an unprecedented time.&amp;quot; 
 
SP500 - rips parabolic on every little detail refusing to go any lower than 10% and every analyst says BTFD stocks go higher once fed raises rates 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 11:01:00 </td>
   <td style="text-align:left;"> $AAPL Oo China just created opportunities here. Probably should move manufacturing back to the 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:59:32 </td>
   <td style="text-align:left;"> 💎**MARCH 15 WATCHLIST**💎

$SPY over $419.80📈 under $415.90📉

$AAPL over $151.53📈 under $150.36📉

$NVDA over $222.02📈  under $209.47📉

$AMZN over $2938.98📈 under $2823.58📉

*Dont be afraid to take the triggers, a SL will protect you* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:56:16 </td>
   <td style="text-align:left;"> $SPY don&amp;#39;t tell the bears 😜 they will just think manipulation and load more puts $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:54:23 </td>
   <td style="text-align:left;"> $SPY ⚡️⚡️⚡️ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:54:14 </td>
   <td style="text-align:left;"> $AAPL almost down 20% from ATH... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:52:53 </td>
   <td style="text-align:left;"> $AAPL futes ticking up. NAZ dropped 25% from 16500 to 12500. Sell the rumor, buy the news Wednesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:52:14 </td>
   <td style="text-align:left;"> $AAPL Best room on the net! I&amp;#39;ve made over 35k by their alerts{~ free.stocktradingchat.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:48:57 </td>
   <td style="text-align:left;"> $AMD $AAPL $AMZN ;; 
 
$1800 into $40k in the last 30 days.. If you really want to make huge profits on trading then, Join this winning chat 🚀 amazing-room.is-great.net/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:47:59 </td>
   <td style="text-align:left;"> $SPY  $AAPL $SNOW $ASAN $ABNB 
👇Futures now 😀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:44:22 </td>
   <td style="text-align:left;"> $SPY Wait is 5% GDP a recession? lol bears come on $AAPL $AMZN $MSFT $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:40:36 </td>
   <td style="text-align:left;"> $AAPL This still has a long way to go down. Closer to 125 is where market bottoms. If US decides to sanction china because of their support for russia, 100 is not out of question. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:40:02 </td>
   <td style="text-align:left;"> $AAPL markets are to weak to stand on their own. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:39:23 </td>
   <td style="text-align:left;"> $SPY $AAPL $TQQQ $SOXL $MSFT 
Futures Rrrrrrrrippping 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:36:34 </td>
   <td style="text-align:left;"> $AMD $AAPL $AMZN $$$:- $1800 into $40k in the last 30 days.,. If you really want to make huge profits on trading then,, Join this winning chat: --  🚀 livetradingview.synergize.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:34:49 </td>
   <td style="text-align:left;"> $AAPL going to $130 ish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:30:59 </td>
   <td style="text-align:left;"> $PARA $AAPL I just tried watching Severance on AppleTV+. It was horribly boring and I turned it off after 20 mins. Apple desperately needs to acquire Paramount Global which consistently excellent, ongoing content. Content is king. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:29:58 </td>
   <td style="text-align:left;"> $AAPL Why This Apple Analyst Is Pessimistic About The 2022 Mobile Market 

https://newsfilter.io/a/408bffd6b66fb62226f57e89395e2447 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:27:51 </td>
   <td style="text-align:left;"> $AAPL $MSFT $SPY $DJIA china just cooked books , be careful trading in am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:26:56 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #1 stock that institutions are trading with 68.3K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:22:30 </td>
   <td style="text-align:left;"> $SPY $SOXL $TQQQ $TSLA $AAPL 
Commodities Dripping 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:19:23 </td>
   <td style="text-align:left;"> $AAPL any possibilities to recover the market like 2020 COVID time? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:19:06 </td>
   <td style="text-align:left;"> $AAPL what’s in store for us tomorrow? A slight Green Day? a 3-4% Green Day? Or another bleeder? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:10:44 </td>
   <td style="text-align:left;"> $AAPL if the market weakness continues this may go to sub 140. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:08:28 </td>
   <td style="text-align:left;"> $SPY China retail sales and industrial output well above expectations. And yeah there GDP is only gonna be 8% this year, lol bears $AAPL $NVDA $MSFT $NKE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:08:10 </td>
   <td style="text-align:left;"> $AAPL Held up support today. If closes below, $145 next stop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:05:18 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-14 Technical Analysis Video: 
https://www.youtube.com/watch?v=zpqXjKWpCME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:05:13 </td>
   <td style="text-align:left;"> $AAPL - Apple price target set at $215 at Tier1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:00:55 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $152.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 10:00:48 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL 

China announcing Shutdown of Apple factory just before Monday opening of the US market. This is not an accident or coincidence. Xi might have purchased a lot of puts to raise money for aiding Russia. This is not at all implausible. We are at stealth war. Don’t give in. Buy the US stocks and bonds. JMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:59:15 </td>
   <td style="text-align:left;"> $AAPL $138 is the bear case scenario </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:53:41 </td>
   <td style="text-align:left;"> $AAPL Globalization is great but need to expand and hedge more countries so we aren&amp;#39;t held hostage. We learned that with oil, now need to diversify manufacturing. Good to see this article after today: https://www.wsj.com/articles/apple-supplier-foxconn-in-talks-to-build-9-billion-factory-in-saudi-arabia-11647274349?mod=hp_lead_pos7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:53:24 </td>
   <td style="text-align:left;"> $SPY $ARKK $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:47:15 </td>
   <td style="text-align:left;"> $AAPL no one stepped up to fill your shoes; even with the last ditch efforts of stock splits. We understand you are still holding the weight of the market and it&amp;#39;s ok for you to sit down to take some weight off your shoulders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:39:22 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I’m gonna end a perma bulls career tomorrow...🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:37:07 </td>
   <td style="text-align:left;"> CNBC:  
Chartmaster sees more downside ahead for $AAPL  https://www.youtube.com/watch?v=FYMsfJue2zQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:34:31 </td>
   <td style="text-align:left;"> $SPY $ARKK $AAPL Hong Kong crashing wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:32:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 

It’s over... flush it, all of it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:32:06 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple: iPhone SE Could Drive Further Upside, Says Top Analyst https://www.stck.pro/news/AAPL/24399110 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:28:16 </td>
   <td style="text-align:left;"> $AAPL Is this a Chinese stock? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:26:26 </td>
   <td style="text-align:left;"> $AAPL those with their portfolio bleeding to death, wondering what is safe  
 
Check out the article via @TipRanks below, makes a good bull case in 1 of the worst trading environments we&amp;#39;ve had in a while. 
 
$SPY $QQQ  
 
https://www.tipranks.com/news/article/apple-stock-safe-pick-amid-geopolitical-risks/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:20:36 </td>
   <td style="text-align:left;"> $AAPL I just realized I don’t even pay attention to my own technical analysis—I feel like I’m always wrong on my TA and end up going the opposite route look at this shit why did I buy AAPL calls lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:18:41 </td>
   <td style="text-align:left;"> $AAPL this better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:18:00 </td>
   <td style="text-align:left;"> $AAPL has a very good Piotroski-F score of 8.00. This indicates great health and profitability. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:15:28 </td>
   <td style="text-align:left;"> $SPY $AMD $TSLA $AMZN &amp;amp; $AAPL  🧞‍♂️💎😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:13:10 </td>
   <td style="text-align:left;"> $AAPL i don’t see this company growing anymore. Their phones and laptops are max good… max good meaning they can’t become better. Most people just watch adult videos and email…also … samsung and Nokia will make a comeback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:11:23 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

Futes looking weak, like a 🐂....🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:09:12 </td>
   <td style="text-align:left;"> $AAPL Putin/Russia, sanctions, with China ~ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:05:42 </td>
   <td style="text-align:left;"> Watch list for tomorrow part 1: $AGRI $MULN $FB $CLX $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:03:40 </td>
   <td style="text-align:left;"> $MSFT $SPY $AAPL supports holding by a thread. Death cross seems to be in play here. One more bounce to test resistance and my whole portfolio goes short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:02:34 </td>
   <td style="text-align:left;"> $AAPL lets just say sales stall… but they do a 5% share buyback a year… the stock should go up 5% a year right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 09:00:13 </td>
   <td style="text-align:left;"> $AAPL Lol made a new low when the market &amp;quot;bottom&amp;quot; was already in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:59:55 </td>
   <td style="text-align:left;"> latexd1b8a31beb4e708ea7388c3a83615584BABA - 57% put flow 
$VXX - 53% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:55:05 </td>
   <td style="text-align:left;"> $AAPL Lets say apple sales stop growing but maintain the next income and buy back 5% of shares a year… the stock price will not crash right? It will stay the same or go up 5% a year?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:52:49 </td>
   <td style="text-align:left;"> $SPY $DWAC $AAPL $BTC.X The whole world economy collapsed in 2008 when Lehman Brothers went underwater.  One bank.  What will happen when two entire countries (Russia+Ukraine) goes underwater? 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:50:59 </td>
   <td style="text-align:left;"> $AAPL Apple: iPhone SE Could Drive Further Upside, Says Top Analyst https://www.tipranks.com/news/article/apple-iphone-se-could-drive-further-upside-says-top-analyst/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:48:21 </td>
   <td style="text-align:left;"> $AAPL Apple Option Alert: Fri $150 Puts Sweep (5) near the Ask: 232 vs 44710 OI; Earnings 4/27 After Close [est] 🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:47:40 </td>
   <td style="text-align:left;"> $SPY At any point this week if $ES_F falls below $4130 &amp;amp; $AAPL falls below $150 “and fails to get back above” that would be a strong sell signal in my opinion. Personally watching these levels closely… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:46:06 </td>
   <td style="text-align:left;"> $AAPL price target for tomorrow is $155 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:45:00 </td>
   <td style="text-align:left;"> $SPY $AAPL    🔈🧞‍♂️🔈  Hey 👋 $TSLA latex08396ae465a5c7fc43472cd711a99e93AAPL - 146 next stop on the way to 118

$CZR - 67 next stop on the way to 56

HODL? More like Here’s your L. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:40:28 </td>
   <td style="text-align:left;"> $AAPL This is just the beginning of a huge crash as they sold out with a $275 Billion deal for China to take over Apple technology and development. Wrong move cook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:39:13 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $SOXL $TQQQ 
Good time for longer-term investors to buy stocks. Historically, the S&amp;amp;P 500 tends to post impressive gains in the 12-month period following an initial close in a death cross. Based on the 53 times the index has closed in death-cross territory, the average gain over that span is 6.3%, according to Dow Jones Market Data.
🖕🤡 @magic_tape 
https://www.google.com/amp/s/www.barrons.com/amp/articles/stocks-death-cross-s-p-500-51647278854 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:36:04 </td>
   <td style="text-align:left;"> $AAPL when you think it can&amp;#39;t get any worse
..oh well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:36:00 </td>
   <td style="text-align:left;"> $SPY Fed still has 20billion to buy this month $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:34:56 </td>
   <td style="text-align:left;"> $AAPL buy under 120$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:34:04 </td>
   <td style="text-align:left;"> $SPY Economy needs a 0.25%, good for everyone $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:31:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $BABA $NIO 
multiple videos from multiple news outlets … who’s the real hypocrite 🤥

https://mobile.twitter.com/imraansiddiqi/status/1497607326487826435?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1497607326487826435%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fd-3269678536654260914.ampproject.net%2F2202230359001%2Fframe.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:28:17 </td>
   <td style="text-align:left;"> $AAPL Money printing machine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:26:17 </td>
   <td style="text-align:left;"> $AAPL $BABA $JD $NIO What does this mean for the Future of Apple dealing with China?  https://www.theinformation.com/articles/facing-hostile-chinese-authorities-apple-ceo-signed-275-billion-deal-with-them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:25:16 </td>
   <td style="text-align:left;"> $SPY Bottom is in but $AAPL just made a new low and is going lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:24:05 </td>
   <td style="text-align:left;"> $AAPL    We will see $147 again and it will pop back to $181 by next month.   I dont recall anyone doesn’t own some sort of apple products.   Come on its fucking APPLE.    It not amc or gamestop.   Steady and easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:24:03 </td>
   <td style="text-align:left;"> $AAPL love this at 140 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:22:23 </td>
   <td style="text-align:left;"> $SPY Apparently the bottom is in but $AAPL just broke it&amp;#39;s recent &amp;quot;bottom&amp;quot;. And is now considered in bearish territory on the daily. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:20:06 </td>
   <td style="text-align:left;"> Video for March 15th (part 3): $AMTX $JKS $YY $FOSL $AAPL  
 
Watch here: https://greatstockpix.com/march-15th-watch-list-video/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:16:08 </td>
   <td style="text-align:left;"> $AAPL only a clown won’t buy at this prices </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:15:34 </td>
   <td style="text-align:left;"> $AAPL what happened or where’s the news about the Apple Car? Seems like it only conveniently shows up when this thing is on a tear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:14:56 </td>
   <td style="text-align:left;"> $AAPL 150 will break this week mark it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:12:47 </td>
   <td style="text-align:left;"> $AAPL More downside this week. Closed under the 200 EMA for the first time this year. A good buying opportunity is coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:10:24 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL IQ Going parabolic! Thanks Geeenko Bahlobah! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:05:50 </td>
   <td style="text-align:left;"> $SOFI $SPY Starting to DCA soon. Sold all my SOFI shares at $20.29. $VTI Adding small chunks here as well in my Roth on each dip. Big caps $MSFT $AAPL need to drop a lot still imo before we see any bottom. Can’t go wrong with DCA in this market. Hope everyone bulls/bears have been doing good! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 08:00:55 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $152.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:59:56 </td>
   <td style="text-align:left;"> Received many questions from folks, all understandably anxious and frustrated, I&amp;#39;ll summarize my response here, the Stock market is not for everyone, 
I&amp;#39;ve been in the market for almost 2 decades, it is not a matter of luck, but the way you research and choose the stocks and transactions.   It is  
80% experience and skill, and 20% luck.   If you really knew how to navigate your way in the stock market, almost always you will be a winner, definitely you should diversify but make sure that you select stocks after thorough research and no one can do a better research than yourself, if you invest wisely here 
you wouldn&amp;#39;t care about market fluctuations and you can work not from home but you can WORK FROM THE BEACH actually 🙂 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:59:23 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL I’m going to try buying SPY shares using Rubles. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:58:44 </td>
   <td style="text-align:left;"> $AAPL 

Picked up calls before the close, this pig is due for a ahort term bounce.... however I still expect to see $120 before end of year... bulls your daddy bear needs a good pamp so he can re-load on cheap puts. If you do this for me, I won’t make it as painful on the way down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:57:48 </td>
   <td style="text-align:left;"> $AAPL Fund managers are sneak thief with the MM&amp;#39;S  lame stream media pushing FUD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:57:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL 
🤡 with puts wants the war to continue </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:56:58 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Market gonna market fam. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:56:02 </td>
   <td style="text-align:left;"> $HLTH COVID waves will come and go in the years to come. Vaccines will partially help, but breakthroughs will continue.  All oral antivirals from $PFE , $MRK or hopefully $GILD (one day) will only work if they are administered quickly after detection.  So, how can you detect quick, get a prescription and start taking medications ASAP?  Automation is the key: 
- get a molecular high precision test at home 
- if positive, press a button in the same app and have a quick online consultation  with a doctor that prescribes medications and send them to the pharmacy 
 
Which medical device manufacturing company is best equipped to achieve this level of automation?  CueHealth is. 
 
You know who need to acquire CueHealth? $AAPL , it will be a very complementary addition to their portfolio.  
 
https://www.youtube.com/watch?v=PqgaQ9WnJSI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:49:57 </td>
   <td style="text-align:left;"> $QQQ $AAPL $SCHD $NVDA buying all four and a few others tickers long term tomorrow. 20-30 year time horizon for me. Will continue to add. Most of you will be apart of the fomo when everything starts to run again. Market is forward looking and pricing most everything in (WW3 could change things but I think the media is just scaring most people). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:48:44 </td>
   <td style="text-align:left;"> $AAPL $AAPL - HEAVY TO THE PUT SIDE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:48:18 </td>
   <td style="text-align:left;"> $AAPL Apple Option Alert: Fri $150 Puts Sweep (5) near the Ask: 232 vs 44710 OI; Earnings 4/27 After Close [est] 🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:47:32 </td>
   <td style="text-align:left;"> $AAPL It&amp;#39;s a nasty environment right now. Over the years, it&amp;#39;s always been the best time to accumulate. Everyone walking around with dumb haircuts and feeling hopeless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:46:59 </td>
   <td style="text-align:left;"> Team $AAPL and Team $LCID to the moon. Let’s gooooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:44:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $AAPL harvested crops returned with fruits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:39:56 </td>
   <td style="text-align:left;"> Courageous even when you know there is a jail sentence waiting for doing this... hats off! 
 
$QQQ $SPY $AMD $AAPL $SOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:39:45 </td>
   <td style="text-align:left;"> $AAPL futures green right now, bears “futures don’t mean anything” but if they switch to red oh boy, futures blood red tanking tomorrow 😂 give it up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:39:43 </td>
   <td style="text-align:left;"> $AAPL I usually like this stock but it’s hard not to be bearish especially with foxconn news. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:36:16 </td>
   <td style="text-align:left;"> $AAPL Displaying some serious relative weakness. Seems to be foreshadowing what&amp;#39;s to come in the market. 135p July expiration. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:33:00 </td>
   <td style="text-align:left;"> $MULN This is a purpose built company for EVs.  Just like $TSLA.  That is the key... they don&amp;#39;t have to transition a massive manufacturing infrastructure from gas powered vehicles to EVs.   
 
$MULN is in great shape and with the potential of $AAPL investing or buying them out... this could get very exciting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:31:33 </td>
   <td style="text-align:left;"> $AAPL $145 so I can buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:31:19 </td>
   <td style="text-align:left;"> $AAPL lol let’s see $145 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:30:00 </td>
   <td style="text-align:left;"> $APPS partnership with $AAPL , news coming tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:29:41 </td>
   <td style="text-align:left;"> $AAPL Should hit $139 level and if that does not hold, $123 is where it becomes worth taking a look at it. Sell long calls if you own the stock, if you don&amp;#39;t buy puts. Recommended puts, $140 April 14 expiration. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:29:06 </td>
   <td style="text-align:left;"> $AAPL The Premarket and the weekends are the MM&amp;#39;s  best shorting tools, you lose 2 day a week going towards  your option expiration date and the Premarket price is rigged the minute it open. Average -1.02 % to -1.75 % drop during the first 3 minutes.. the SEC ignore this.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:28:55 </td>
   <td style="text-align:left;"> $AAPL every other tech stock is up ah and apple is barely at closing price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:23:55 </td>
   <td style="text-align:left;"> $GME $MULN $TSLA $AAPL  this make sense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:23:35 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X vs $AAPL $AMZN $MSFT  
 
Look at the Heatmap. It&amp;#39;s official! #Cryptos Like #Bitcoin and #Ethereum are out-performing the best #Stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:21:05 </td>
   <td style="text-align:left;"> $AAPL Biggest difference between Apple and Samsung isn&amp;#39;t technology, it&amp;#39;s the ability for Samsung to continue manufacturing goods without China where Apple has heavy dependence on China.  In a cold war, Samsung will outlast Apple if China were to stop making goods for Apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:18:16 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL 
Futures moves by Green core meme GIfs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:17:00 </td>
   <td style="text-align:left;"> $AAPL: The EPS has been growing by 22.14% on average over the past 5 years. This is a very strong growth. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:12:54 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Look bulls, he’s back on your side enjoy the Crammer curse!!!🤣🤣🤣

https://www.cnbc.com/2022/03/14/cramer-says-stocks-may-bottom-sooner-than-expected-because-wall-street-is-so-negative.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:12:45 </td>
   <td style="text-align:left;"> $AAPL ah market up, this stays parked and as soon as ah market goes down, this starts to move down of course. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:12:26 </td>
   <td style="text-align:left;"> $BABA $TCEHY $AAPL $SPY $TSLA 
Reallocating capitals to US stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:07:08 </td>
   <td style="text-align:left;"> $AAPL https://www.ped30.com/2022/03/14/apple-watch-counterpoint-2021/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:06:32 </td>
   <td style="text-align:left;"> $AAPL Futures mean ungotz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:05:20 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I expect to see one final sucker pump from this market to trap last of the moronic buy the dip traders before we witness the dump of  a millennium... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:03:34 </td>
   <td style="text-align:left;"> $AAPL who’s holding calls from Friday? Damn I’m getting hammered right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:01:51 </td>
   <td style="text-align:left;"> $AMZN always bullish. $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:01:41 </td>
   <td style="text-align:left;"> $AAPL 

Increased longtime position by 25% here at 150.25. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:01:27 </td>
   <td style="text-align:left;"> $AAPL futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 07:00:03 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:58:49 </td>
   <td style="text-align:left;"> .  
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:58:41 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $SOXL $TQQQ  
Futures so green  🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:58:17 </td>
   <td style="text-align:left;"> $DIA $SPY $AAPL $QQQ 

Earnings this week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:57:41 </td>
   <td style="text-align:left;"> Today&amp;#39;s overview of the SP500 $SPY market $AAPL $ORCL $FMC $BIIB  
 
Learn more: https://www.finscreener.org </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:53:57 </td>
   <td style="text-align:left;"> $AAPL If this hits 30 RSI on the daily.. mortgage the house. History doesn’t lie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:52:30 </td>
   <td style="text-align:left;"> $AAPL We made money again! Those who have been following me have been making money consistently. Haters spread hate but I have helped retailers make money for free during past few weeks when most were losing. If you missed my daily plans follow my twitter @optionboys or if  you want to join my private group message me.(it’s actually fairly cheap to join) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:50:43 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 66.6K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:50:14 </td>
   <td style="text-align:left;"> $AAPL Even Obama said that brandon is no good, you can go and check yourself the articles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:48:18 </td>
   <td style="text-align:left;"> $AAPL Very shrewd management team when it comes down to business, especially CEO Tim Cook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:46:58 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Wen moon?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:46:49 </td>
   <td style="text-align:left;"> $AAPL The European markets were today in big green. Finnland, border to Russia, achieved 3.9%. I think what we observe in US is a disgusting play of Wall Street. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:46:43 </td>
   <td style="text-align:left;"> $AAPL MM gone fishin’ 🎣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:46:09 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Chartmaster sees more downside ahead for Apple https://www.stck.pro/news/AAPL/24392453 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:45:57 </td>
   <td style="text-align:left;"> NASDAQ 100 ($QQQ) Most Active during today $AAPL $AMD $JD $NVDA  
 
Learn more: https://www.finscreener.org/screener/most-active/stocks/nq100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:45:20 </td>
   <td style="text-align:left;"> $SPY $AAPL $SOXL $TQQQ $TSLA 
Moooooooning tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:43:06 </td>
   <td style="text-align:left;"> $MULN maybe $AAPL Apple car? 🤩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:41:00 </td>
   <td style="text-align:left;"> $SPY $AAPL $BABA $TSLA Odds may happen sooner than expected. https://twitter.com/neuteredTweets/status/1503500855047344133?s=20&amp;amp;t=Kjpb6FUZBxKHokkQlwFB_Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:40:02 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $BABA Odd may happen sooner than expected. https://twitter.com/neuteredTweets/status/1503500855047344133?s=20&amp;amp;t=Kjpb6FUZBxKHokkQlwFB_Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:39:31 </td>
   <td style="text-align:left;"> $AAPL lmao pump it clowns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:38:38 </td>
   <td style="text-align:left;"> $AAPL pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:38:22 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl follow me on Twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:37:44 </td>
   <td style="text-align:left;"> $AAPL Voting for Biden was the most stupidest thing you could have ever done. There really is not excuse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:36:48 </td>
   <td style="text-align:left;"> $AAPL $LCID I can just imagine if FOMC decided to raise rate by 50 basis points or not at all, but the market is the market. Diamond hands here. 💎🔹🔷💍💎♦️💠🔶💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:35:37 </td>
   <td style="text-align:left;"> $AAPL $TSM are you fucking kidding? China signaled they are willing to help?  Fuck https://www.google.com/amp/s/amp.ft.com/content/52ea7aab-f8d1-46b6-9d66-18545c5ef9b9 $SPY $GLD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:35:30 </td>
   <td style="text-align:left;"> $AAPL 

P/e 20 on the card, lads. That&amp;#39;s a share price of about $121. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:34:36 </td>
   <td style="text-align:left;"> $AAPL Great day to block idiots especially the ones that are quiet most days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:34:13 </td>
   <td style="text-align:left;"> $AAPL happy happy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:33:51 </td>
   <td style="text-align:left;"> $AAPL rage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:33:18 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:32:59 </td>
   <td style="text-align:left;"> $AAPL Correct me if I&amp;#39;m wrong but before it continues up this is looking to fill the gap between July 1 and 2 of last year so approximation of $136 before it moves back up never to look back down again.? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:30:46 </td>
   <td style="text-align:left;"> $AAPL Trump will be back and Apple will hit 1000 a share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:28:36 </td>
   <td style="text-align:left;"> $SNAP $AAPL $FB $AAL $TLSA  yal know market will be renounce after the announce of FOMC this Wednesday rite? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:27:53 </td>
   <td style="text-align:left;"> $AAPL nearing a former buy zone $149.22 with true support at 145.91 

Worth watching </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:27:29 </td>
   <td style="text-align:left;"> Daily Market Recap for Monday 3/14/2022 for trending #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/3_mJIJbQCLs

$AMD $AAPL $TSLA $RBLX

Tech continues to lag. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:26:15 </td>
   <td style="text-align:left;"> Stock market is not for everyone  
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:25:16 </td>
   <td style="text-align:left;"> :) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:23:14 </td>
   <td style="text-align:left;"> $AAPL &amp;quot;SELL SELL SELL!&amp;quot;,  says the market but the contrarian investor says, &amp;quot;When the market is bearish, that is when I&amp;#39;m bullish.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:21:43 </td>
   <td style="text-align:left;"> $AAPL I have a small request.  Please pm me if you voted for Harris/Biden.  I want to send you a gift since we’re so much better off! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:18:53 </td>
   <td style="text-align:left;"> $AAPL 
⬆️⬆️⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:16:22 </td>
   <td style="text-align:left;"> $AAPL the real support is exactly $100 . period… just the facts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:16:02 </td>
   <td style="text-align:left;"> $AAPL We like looking for a decline further down, where buyers can enter at the blue box for a bounce.  We don’t like to sell it short this close to the blue box though, but we do like to buy it lower at the extreme area where buyers are waiting for a bounce.  #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:15:39 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:14:00 </td>
   <td style="text-align:left;"> He did not buy the dip and trying to explain, good luck 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:13:36 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMZN $ES_F . $QQQ  🧞‍♂️🤑. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:11:46 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $152.5 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:11:36 </td>
   <td style="text-align:left;"> $AAPL should be at 130 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:10:23 </td>
   <td style="text-align:left;"> $AAPL 138-140 then Moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:10:15 </td>
   <td style="text-align:left;"> $AAPL Keep pumping right into the rug pull it’ll Be way more epic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:05:15 </td>
   <td style="text-align:left;"> $AAPL got cheap 162.50c lottos. 🧑🏼‍🦯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:05:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Crossmark&amp;#39;s Victoria Fernandez explains her top stock picks: BAC, V, AAPL https://www.stck.pro/news/AAPL/24391672 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:04:52 </td>
   <td style="text-align:left;"> $AAPL jumping
In at $75 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:03:37 </td>
   <td style="text-align:left;"> S&amp;amp;P 500 $SPY most active stocks during last session $AAPL $AMD $F $BAC  
 
Learn more: https://www.finscreener.org/screener/most-active </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:02:21 </td>
   <td style="text-align:left;"> $AAPL $QQQ -- Apple Inc&amp;#39;s weekly chart shows a dip to trend support and the 50wma, and below the (2.0) LinReg channel.  I like this as a great candidate for a &amp;quot;NakedPut/CoveredCall&amp;quot; flipper.  See me in the DST Room for details on how to do this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 06:01:08 </td>
   <td style="text-align:left;"> $AAPL Added some Apples for a scalp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:59:03 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:56:44 </td>
   <td style="text-align:left;"> $AAPL Closed under the 200 day moving average   
 
No one could have seen this coming. 
https://share.trendspider.com/chart/AAPL/6682r8unkz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:52:41 </td>
   <td style="text-align:left;"> $PLTR $SPY $AAPL $AMD $NVDA 

The stock market outperformed under Trump and it continued until end of 2021…
Now we are seeing the Biden Era…

Biden cannot get his team member Manchin to vote for BBB bill…
But he is tried talking to PUTIN to stop the war…

Hey Biden first convince your teammate Manchin…later you can think about Putin… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:48:18 </td>
   <td style="text-align:left;"> $AAPL small gain but 100% is 100% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:47:27 </td>
   <td style="text-align:left;"> $BABA $TSLA $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:46:04 </td>
   <td style="text-align:left;"> $AMD $UPST $AAPL $NASDAQ  its amazing to think that covid distraction was so helpful to the market.  Who would have thought that the best returns of the century would come during a worldwide pandemic ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:41:20 </td>
   <td style="text-align:left;"> $AAPL Carter Worth on CNBC recommends SELL just now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:41:15 </td>
   <td style="text-align:left;"> $AAPL sorry can’t be bullish on apple where everyone just jumps in for 13 min into puts makes a buck and get out, same on the call side. Just a pure trading stock like a penny stock. Until, we see institutions start looking at it around 135 no touch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:37:36 </td>
   <td style="text-align:left;"> $AAPL 200 PT 🎯 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:37:23 </td>
   <td style="text-align:left;"> $AAPL: APPLE INC,  37.6812% PROFIT
https://oversight.pro/assets/uploaded_files/100_400_1625323321_1647250506_0.jpg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:36:06 </td>
   <td style="text-align:left;"> $AAPL another 50 points lower and I&amp;#39;m a buyer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:36:04 </td>
   <td style="text-align:left;"> $AAPL I expect some sort of bear burn announcement coming soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:35:30 </td>
   <td style="text-align:left;"> $AAPL taken down 0.75 after hours on virtually non existent volume. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:35:05 </td>
   <td style="text-align:left;"> $TSLA  Kick Vlads ass Elan   $AAPL $AMZN 🚀

$spy   $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:33:23 </td>
   <td style="text-align:left;"> $AAPL 
Added again today.. when everyone is selling you must be buying! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:32:38 </td>
   <td style="text-align:left;"> $AAPL FUNDAMENTALS ARE DEAD, Apple has proven how to make record breaking earnings during the pandemic ,but trading below the 200 day sma.. because of  THE UKRAINE 🇺🇦 CONFLICT .#.FJB .#.LGB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:32:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

I wanna see a 50% haircut tomorrow across the board </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:32:00 </td>
   <td style="text-align:left;"> $AAPL Holding puts till $138 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:32:00 </td>
   <td style="text-align:left;"> $TSLA  KICK HIS MUTHA FKN ASS ELAN 

$spy $aapl $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:30:13 </td>
   <td style="text-align:left;"> Stocks Are Now On The Cusp Of A Major Move Lower https://mottcapitalmanagement.com/stocks-are-now-on-the-cusp-of-a-major-move-lower/ $aapl $nvda $spy $qqq $dia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:29:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

I’m still speechless how we haven’t had a single limit down yet...😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:28:08 </td>
   <td style="text-align:left;"> only two stocks that&amp;#39;s relatively strong $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:27:00 </td>
   <td style="text-align:left;"> $AAPL When the sp500 falls behind the 200 sma we have had 50% gain the following year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:25:48 </td>
   <td style="text-align:left;"> $AAPL Cult stocks/ETF/INDEX stocks aren&amp;#39;t immune. Darts can go out of style too! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:25:24 </td>
   <td style="text-align:left;"> $TSLA $NVDA $GOOGL $AMZN $AAPL and Visla think I should  be fine longtern, Tesla scares me sometimes, have to sell one for capital gains from last year which one tough to pick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:24:45 </td>
   <td style="text-align:left;"> $AAPL clown show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:23:38 </td>
   <td style="text-align:left;"> $AAPL clowns on cnbc saying 138 is bottom. watch this be the bottom today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:22:38 </td>
   <td style="text-align:left;"> $AAPL 

Haven&amp;#39;t been in this one in a long time.  Could go lower of course but does anyone not believe this will see $200 again at some point?   

I&amp;#39;m watching. But buying yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:22:28 </td>
   <td style="text-align:left;"> $AAPL Who&amp;#39;s shorting the market?,  its weird how media tell people ,don&amp;#39;t panic and hold at the every same-theyre buddies are planning to dump shares..Sleepy joe won&amp;#39;t  say a darn thing. Unless he can blame it on  Trumf.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:21:35 </td>
   <td style="text-align:left;"> $AAPL Carter Worth has a downside Target of 138.00 
Very similar to my downside PT 137 - 133.35 low Target of 
133.35 👀Apple =38.2% Fibonacci from March 2020 lows to January 2022 ATH 
Market goes noticeably lower because It has further room to the downward downside👀 

$SPY $QQQ $AMD $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:21:20 </td>
   <td style="text-align:left;"> 4/4 

Carter charting $AAPL’s next move

$AMD ↗️ $AMZN $MSFT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:21:06 </td>
   <td style="text-align:left;"> 3/4 

Carter charting $AAPL’s next move

$AMD ↗️ $AMZN $MSFT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:20:44 </td>
   <td style="text-align:left;"> 2/4

Carter charting $AAPL’s next move

$AMD ↗️ $AMZN $MSFT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:20:26 </td>
   <td style="text-align:left;"> 1/4 Carter charting $AAPL’s next move

$AMD ↗️ $AMZN $MSFT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:18:36 </td>
   <td style="text-align:left;"> $AAPL 140 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:18:17 </td>
   <td style="text-align:left;"> $AAPL 135 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:18:00 </td>
   <td style="text-align:left;"> $FB 

Here you go! FACEBOOK REPRESENTS THE BOTTOM OD THE MARKET ! Today is it

$vxx $spy $qqq $AAPL    

FACEBOOK THE BOTTOMS IN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:15:59 </td>
   <td style="text-align:left;"> $BAND $AAPL Apple is going to $137, then the market can settle down with these 2% moves everyday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:15:46 </td>
   <td style="text-align:left;"> $AAPL everyone living under the Biden administration RN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:15:31 </td>
   <td style="text-align:left;"> $AAPL $160 tmmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:15:23 </td>
   <td style="text-align:left;"> $SPY excellent dip buy opp&amp;#39;s on $AAPL and $MSFT for permabulls

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:14:24 </td>
   <td style="text-align:left;"> $AAPL shafted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:14:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 8.00, indicating great health for $AAPL. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:11:30 </td>
   <td style="text-align:left;"> China 🇨🇳 Shutdown Spooks WS~

$AAPL $AMD ↗️ $NKE $QCOM $SBUX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:08:48 </td>
   <td style="text-align:left;"> $AAPL Snakes  wake up at 4:00 AM JUST TO be the first in line  to  SHORT THE PRE MARKET trading..BULLS ARE FCKED.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:06:14 </td>
   <td style="text-align:left;"> $AAPL Apple Inc. (NASDAQ:AAPL) – KeyBanc Remains Upbeat On Apple Citing iPhone SE 3; BofA, Piper Sandler See Limited Impact From China Lockdown

https://news.alertsandnews.com/apple-inc-nasdaqaapl-keybanc-remains-upbeat-on-apple-citing-iphone-se-3-bofa-piper-sandler-see-limited-impact-from-china-lockdown/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:03:24 </td>
   <td style="text-align:left;"> $AAPL supply issues out of China https://youtu.be/94xzLWDwzzQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:01:54 </td>
   <td style="text-align:left;"> $AAPL FoxxNews An CuckNBC are the biggest pushers of FUD in this current market.. they act like the all and powerful Oz is behind the sell-off $SPY this is a dumb money purge.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 05:00:37 </td>
   <td style="text-align:left;"> $AAPL From watchlist yesterday!🎉🤑
Free discord in bio! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:59:21 </td>
   <td style="text-align:left;"> $ENPH already after hours? Is 20:58 in UK, ehat happened? $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:56:33 </td>
   <td style="text-align:left;"> $AAPL Nice 10% on options earlier. Tomorrow should have a nice bounce day.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:54:59 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG $QQQ load upppp this dip is a joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:50:28 </td>
   <td style="text-align:left;"> $AAPL isn’t life great rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:50:13 </td>
   <td style="text-align:left;"> $AAPL 4 million dollar bid at $150, closest thing to that for resistance is at $155 at about 2 million </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:49:50 </td>
   <td style="text-align:left;"> $AAPL $142 and $147 next supports </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:48:54 </td>
   <td style="text-align:left;"> $SPY $AAPL $TQQQ $SOXL $TSLA 
Tonight or Tomorrow 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:48:12 </td>
   <td style="text-align:left;"> $AAPL Option Alert.. High Volume Options... 👀 👀  $150 Put for Friday, March 18. Roughly 25 Million dollars! 💰💰💰 MASSIVE MONEY 💰💰💰 Learn more on StockOrbit at https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:47:59 </td>
   <td style="text-align:left;"> $AAPL Option Alert.. High Volume Options... 👀 👀  latex121f080b8d1f77b357a2ba21475df17cAAPL March latexd09c5213f9f7f98d141c6fdd9f38fb83AAPL March latex455ca7ae7fddf47eee243f496486f493AAPL March latexc6f508bba014a7d5449a51c35f706453MULN March latexb674ee57035c8ac20ffd9957ba5e150eAAPL March latexa0fa1a5978832842ca51b250ae958791AAPL March latexde7a9490fb29d16d89ab5481977884efCOTY May latex7e7686b287d948696a118cb44e228aafCOTY May latex87d60b8e64b342d2bd802c53d36cd4c6AMD March latex5d6fc3401852847979f41ec2ffe9e50dAAPL March latex9c9e21fb735dedc6b43eae156fd8bda6BABA 430k (54% call/46% put)
$AMD 382k (54% call/46% put)

https://rooms.stocktwits.com/checkout/4560671/prod_Kpk7ezeIDS8ksT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:44:18 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $FB , $TSLA  🧞‍♂️🔈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:42:08 </td>
   <td style="text-align:left;"> Make $AAPL great again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:41:24 </td>
   <td style="text-align:left;"> $AAPL 

Look at the bright side of this slide. You know who is buying Apple?
Apple is buying Apple. The lower it goes the more they buy. 
(At least I sure hope they are) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:36:54 </td>
   <td style="text-align:left;"> $AAPL $C Chinese Stocks Are Really Cheap. Value Traps or Value? 

https://newsfilter.io/a/f58606a41d059b1ca228b3065527b64c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:36:54 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 399.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:35:46 </td>
   <td style="text-align:left;"> Pleasure as always, looking forward to tomorrow! Notable $SPY close under the inverted h/s on daily. $AAPL major support broken. Will see w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:35:04 </td>
   <td style="text-align:left;"> $AAPL hell of a daily candle. Hahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:33:23 </td>
   <td style="text-align:left;"> $AAPL  
 
The key support is broken, new low is coming... 
 
If you&amp;#39;d like to catch falling knife, not this one for sure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:32:21 </td>
   <td style="text-align:left;"> $AAPL Warning dumb money traders, The fund managers are manipulating the market to make everything look cheaper, after all, your money is lock into a losing position .. Try buying the dip with no money.. 🤡 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:32:18 </td>
   <td style="text-align:left;"> $AAPL all of the price action of every stock is manipulated and determined by MMs, WS. It’s criminal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:31:31 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ $IWM so many new investors that came in after covid lows have not experienced a bear market. Fiscal and monetary support inflated equities and valuations. QE ends tomorrow and rates will start rising to battle historic inflation. Market is repricing across the board </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:31:19 </td>
   <td style="text-align:left;"> $AAPL Yo gme running it up too lmfao 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:30:45 </td>
   <td style="text-align:left;"> $AAPL time for a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:30:08 </td>
   <td style="text-align:left;"> $AAPL $BABA on similar path due covid lockdown with 0 tolerance policy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:28:50 </td>
   <td style="text-align:left;"> $AAPL WRAP is next all aboard ride the train </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:28:22 </td>
   <td style="text-align:left;"> $SPY People fail to realize the last 3 years have been extraordinary for the Market 
I posted that a while ago
Look for yourself!

$QQQ $MSFT $AMD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:28:12 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MSFT Do you not understand that you are gaslighted with politics by the media and shills on Stocktwits? Only curmudgeons can’t speak to one another across the aisle. People that change the world work together </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:27:17 </td>
   <td style="text-align:left;"> $AAPL Streaks Above 200 DMA https://www.bespokepremium.com/interactive/posts/think-big-blog/aapl-streaks-above-200-dma 
 
In the post iPod era (October 2001), the current streak ranks as the 8th longest of consecutive closes above the 200-DMA.  Ironically, the current streak just moved into 8th place last week after it eclipsed the 193 trading day streak that ended two years ago yesterday at 193 trading days. 
 
The chart below shows historical streaks where $AAPL traded above its 200-DMA since the launch of the iPod.  Again, while 195 trading days may sound long, the current streak ranks nowhere close in length to the three-year streak that ended in May 2008, and the two-plus year streak that ended in 2011. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:26:54 </td>
   <td style="text-align:left;"> $AAPL it seems like even a .5% rate hike is more than priced in already. Todays drop was asinine really. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:26:42 </td>
   <td style="text-align:left;"> $JD HAS RULLED THE MARKET. $AMZN $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:25:58 </td>
   <td style="text-align:left;"> Thinking some Big news is coming… today’s price action was wacky… 

🚨 $SPY $QQQ $TSLA $AAPL $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:25:18 </td>
   <td style="text-align:left;"> $AAPL is giving China its tech after lobbying 236 Billion dollar development deal. This is going to tank w the chinese stocks $BABA $JD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:24:32 </td>
   <td style="text-align:left;"> $AAPL TIM It was a week ago people were looking forward to higher highs..you just dump the post split bags on the dumb money crowd. 🏳️‍🌈🏳️‍🌈🌧️⛈️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:23:43 </td>
   <td style="text-align:left;"> $AAPL realistically do u see it dipping down to $120? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:23:10 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MSFT If you are solely blaming Biden for issues in our economy, you probably find it harder to understand economics than shoving your head up your own butthole🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:21:51 </td>
   <td style="text-align:left;"> $AAPL omg it&amp;#39;s bottoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:17:28 </td>
   <td style="text-align:left;"> $SPY $aapl $googl $amzn $sqqq $uxxy yea boy chili dog just got my report card, looked at it all F’s took it to the teachers desk THROW SOME D’s on that bitch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:17:03 </td>
   <td style="text-align:left;"> $AAPL are my 18 162/165 debit spreads for this Friday….safe? Bahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:16:53 </td>
   <td style="text-align:left;"> $AAPL $AMZN $NFLX All that you need to know.., Shorts haven&amp;#39;t covered a single share:~~~~~~~~~ Check it out below! 👇  
  
highly recommend everyone to follow them.,,. 🚀 livetradingview.synergize.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:15:52 </td>
   <td style="text-align:left;"> PreMarket Prep Stock Of The Day: Berkshire Hathaway Rallies In Turbulent Market $BRK.B $AAPL https://www.benzinga.com/trading-ideas/technicals/22/03/26129591/premarket-prep-stock-of-the-day-berkshire-hathaway-rallies-in-turbulent-market#.Yi-iZr7BwWQ.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:13:33 </td>
   <td style="text-align:left;"> $AAPL What happened to the Soft landing from the FEDS?? What a load of sh! t 💩💩💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:12:51 </td>
   <td style="text-align:left;"> $AAPL Perfect touch of the 50 week MA today (last tested March 2020).   What are the chances of this being the low? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:12:28 </td>
   <td style="text-align:left;"> $aapl So it seems like 8.47 MILLION shares were sold in the dark pool today. Block. Fuck me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:12:20 </td>
   <td style="text-align:left;"> $SPY $QQQ. $AAPL 

Appl sitting on a major support line. Definitely a bounce tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:08:50 </td>
   <td style="text-align:left;"> $AAPL This week i believe we ll see bottom. Why? 
- Oversold badly, 32.49 on the daily and 42 on the weekly. Extremely oversold levels on a premium name not seen since 16th march 2020, thats right, pandemic low weekly RSI and last years Lows $116 RSI on the daily. 
-Sitting at 50 week MA.  Only time ever breached was due to fed tightening cycles, and fair to say the taper is now priced in.  
-PE @ 25. At 25 PE you get exposure to an already great business with tons of cash + Major new verticals coming, such as VR, AR, Health tech, Cars, Ads and silicon expansion. This is a company being priced at a premium below $amzn while having competency in the fields of $nvda , $fb , $tsla (future). So those companies have 50+ ratio except fb ofc lmao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:08:35 </td>
   <td style="text-align:left;"> $AAPL if no basing occurs here, lower 140s and upper 130s coming in the next few weeks, maybe even days.  Had some good returns day trading on $150 puts today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:08:23 </td>
   <td style="text-align:left;"> $AAPL no positive news 
which means Apple and Market go lower 
$QQQ $SPY $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:06:25 </td>
   <td style="text-align:left;"> $AAPL how big will the bounce be tomorrow? $155+? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:05:43 </td>
   <td style="text-align:left;"> $AAPL It closed 150.62.  The ST Ticker is not correct. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:04:19 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple&amp;#39;s privacy chief regretted creating its infamous ad-tracking tool after developers started using it in ways the tech giant didn&amp;#39;t intend, report says https://www.stck.pro/news/AAPL/24384404 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:04:13 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG $QQQ biggest bs drop ever!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:04:11 </td>
   <td style="text-align:left;"> Happy March 15th … 2 years since the shut down… to slow the spread…. Don’t worry Biden the 🤡 said he would build back better? Lol 

🤡 $SPY $QQQ $BTC.X $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:04:01 </td>
   <td style="text-align:left;"> $AAPL $150 survived. This is really good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:04:00 </td>
   <td style="text-align:left;"> $AAPL $TSLA $NVDA $MSFT $AMD  
 
Nasdaq again on support level, and for second time gettint to oversell level. Last time it was in 2019 and then 2020 followed by huge rally up. So i only wish, that FED on wednesday give some guidance and calm market panic. Otherwise we heading to very bad bad recession and sellofs :( Lord with us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:03:43 </td>
   <td style="text-align:left;"> latexbee1ead121375631ecbf80d6c6fa75baNIO (Vol: 112.22M) 
$AAPL (Vol: 105.80M) 
 
Alerts &amp;amp; Technical Analysis via tradethehalt.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:01:37 </td>
   <td style="text-align:left;"> $QQQ  $SPY $AAPL   I  think the FED wants to shave a least 25% from the 2 years gains so we still have like another 5 to 8 % to go down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:01:01 </td>
   <td style="text-align:left;"> $AAPL bear trap is fucking set.. im ready to see bear accounts exploded by the end of the week theres a time to be a bear and theres a time to be a bull and this week is the bulls week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:00:24 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 3/06 weekend update presented to members at elliottwave-forecast.com/ #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 04:00:03 </td>
   <td style="text-align:left;"> $AAPL bull traps on bull traps. What’s tomorrow? More bull traps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 03:59:28 </td>
   <td style="text-align:left;"> $AAPL look it’s Apple should come with new phone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 03:59:18 </td>
   <td style="text-align:left;"> $SBUX $V $MA $AAPL $WEN people are scared!!!! market is selling. I am holding, sellers will regret, holders will rejoice! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 03:57:32 </td>
   <td style="text-align:left;"> AAPL Aggressive Elevated Risk: Apple Inc $AAPL triggered at $150.40 on 14-Mar-22 EST http://dlvr.it/SLhCZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 03:57:26 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 03:57:07 </td>
   <td style="text-align:left;"> $AAPL 4hr view from the 2/27 weekend update. Calling for a move lower towards blue box area where buyers are expected to appear #elliottwave #trading #apple #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 03:57:05 </td>
   <td style="text-align:left;"> $AAPL: APPLE INC,  37.6812% PROFIT
https://oversight.pro/assets/uploaded_files/100_400_1625323321_1647250506_0.jpg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 03:54:49 </td>
   <td style="text-align:left;"> $AAPL told u poor bulls all day ISSA TRAP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 03:54:39 </td>
   <td style="text-align:left;"> $AAPL hold the line </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 03:54:31 </td>
   <td style="text-align:left;"> $AAPL $AMD $NVDA $TSLA  
 
ill start nibbling a bit but still too risky 
 
https://stocktwits.com/MeetJoeBlackBeard/message/428707223 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-15 03:54:10 </td>
   <td style="text-align:left;"> $AAPL hold the fucking line tim apple ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 11:01:59 </td>
   <td style="text-align:left;"> $TSLA bears and bulls, remember this is QUAD witching week. Sell OTM options don’t buy them. #notfinancialadvice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 11:01:29 </td>
   <td style="text-align:left;"> 🚨 TRADE IDEAS FOR TOMORROW 🚨 :

$SPY - CALLS ABOVE $420 &amp;amp; PUTS BELOW $415

$DDOG - CALLS ABOVE $122 &amp;amp; PUTS BELOW $116

$RH - CALLS ABOVE $334 &amp;amp; PUTS BELOW $320

$CAR - CALLS ABOVE $225 &amp;amp; PUTS BELOW $215

$TSLA - CALLS ABOVE $790 &amp;amp; PUTS BELOW $772

GOOD LUCK &amp;amp; ALWAYS TRADE SAFE 💎
FOLLOW ME HERE FOR MORE TRADE IDEAS 👈🏻 💎
https://stocktwits.com/r/thestocktraderhub </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 11:00:03 </td>
   <td style="text-align:left;"> $SPY THE ANTHOLOGY of *SHORTYMCFLY* 🙋‍♂️💥💦 
 
(I&amp;#39;ve tried so hard to warn ⚠️ Bulls but in the end it doesn&amp;#39;t really matter🎵🔊) - $FB $TSLA $AFRM $COUP etc AMC PYPL DOCU NFLX TDOC AAPL QQQ etc.. 🕯 
 
LAMBO CHRONICLES 😆🏎 
 
https://youtu.be/WNeLUngb-Xg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:58:07 </td>
   <td style="text-align:left;"> $VXX $TSLA $IXHL Start trading over 4 month ago and I lost $3K, Now I&amp;#39;ve made over $147K+ profits after join their chat room and using their alerts. Highly recommended! It&amp;#39;s free to join,, livetradingview.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:58:01 </td>
   <td style="text-align:left;"> $TSLA this is how we make our money ball stay focused it&amp;#39;s never smooth sailing some big chop out there but we&amp;#39;re not the only one that knows that😉 the eagle waits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:58:01 </td>
   <td style="text-align:left;"> I&amp;#39;m sure its a nice tour with Marty Walsh in my $TSLA factory near Austin. We do have to concern the issues of inflation and American innovation and job creation in Taxes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:56:59 </td>
   <td style="text-align:left;"> $MULN $BABA $TSLA $GME $AMC why the fuck Mullen&amp;#39;s bears think that we are going to sell. 
 
The short interest is 214% 
 
Why the fuck we are going to sell???🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:56:08 </td>
   <td style="text-align:left;"> $TSLA Elon mf will probably make a another poll 😭💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:55:16 </td>
   <td style="text-align:left;"> $TSLA futures looking bright let’s build a strong base together 💎💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:54:14 </td>
   <td style="text-align:left;"> $TSLA Tesla Motors, Inc. (NASDAQ:TSLA) – Is There A New Version Of Tesla’s Model Y Coming?

https://news.alertsandnews.com/tesla-motors-inc-nasdaqtsla-is-there-a-new-version-of-teslas-model-y-coming/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:53:52 </td>
   <td style="text-align:left;"> $DIDI DIdI car all electric to be launched soon  as June 2022 thru June 2023 .  added the dip .Book to value ratio can&amp;#39;t deny $TSLA $SPY 

https://cnevpost.com/2022/03/15/didi-reportedly-could-announce-car-making-plans-in-june/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:53:14 </td>
   <td style="text-align:left;"> $VXX $TSLA $LKNCY Account Challenge Update:-    
Start Date: Feb 5, 2022    
Starting Balance: $1,800    
Current Balance: $89,637    
Goal: $100,000 by end of March.   
Strategy: Swing Trade Options, Stocks    
     
Watch out for next play----- stock-opt-tradingchat.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:53:12 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/elonmusk/status/1503562377807077385?s=12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:51:37 </td>
   <td style="text-align:left;"> $TSLA China capitulating.  **BULLISH**       -breaking-  China&amp;#39;s top diplomat, Yang Jiechi, told Washington on Monday that Beijing regrets the war in Ukraine but will not stand for any attempts to &amp;quot;smear&amp;quot; China over its position, according to a readout from the Chinese side. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:51:01 </td>
   <td style="text-align:left;"> $TSLA 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:50:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $TSLA is 7.00. This indicates good health for $TSLA. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:49:41 </td>
   <td style="text-align:left;"> Breaking: Elon Musk has deployed dozens of sharks with frick&amp;#39;n laser beams attached to their heads to take on the Russian Navy.  
 
$TSLA $SPY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:48:00 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Who cares if futes ripping I’m still down a fuckload lol. Must be near a bottom when I stop caring about futures I watch them all the time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:46:51 </td>
   <td style="text-align:left;"> $TSLA good overview... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:46:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ ,,  $1800 into $40k in the last 30 days.. If you really want to make huge profits on trading then, Join this winning chat 🚀 amazing-room.is-great.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:45:54 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC Futures tanking. Did Joe Biden say something stupid again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:45:42 </td>
   <td style="text-align:left;"> $TSLA 

Bulls: I don’t care if it goes down $500 from highs, I’m not selling.

$TSLA AH: **Goes up $10**

Bulls: **goes ballistic** </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:44:53 </td>
   <td style="text-align:left;"> Today $TSLA shows SELL signal (TA) for short term. Technical analysis source: https://stockinvest.us/stock/TSLA?utm_source=stocktwits&amp;amp;utm_medium=autopost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:42:40 </td>
   <td style="text-align:left;"> $TSLA 

TMC - the metals company 🤑🤑🤑

- hedge against Inflation and Ukraine war! Best EV play is a commodity play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:42:16 </td>
   <td style="text-align:left;"> $KVGOF  
$TSLA $F #nickel #batterymetals
Meanwhile across the pond: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:41:50 </td>
   <td style="text-align:left;"> Equity Sentiment: $TSLA is the #5 stock that institutions are trading with 27.7K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:40:44 </td>
   <td style="text-align:left;"> $TSLA Why are so many people bullish here? I think Tesla in the next 5 years will go over $1500 but not tomorrow! I’m seeing people say it will go to $900, $1000, $1500 this week lol 😂 In the short term Tesla maybe even tomorrow will got to low $700’s even high $600’s. I won’t be surprised if it goes to $400–$500 short term expect this from Tesla we all know how volatile this stock really is! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:39:16 </td>
   <td style="text-align:left;"> $TSLA if someone can just take Putin out Tesla $3,000 by year end easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:37:17 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC Futures ripping hard, did Joe Biden step down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:37:14 </td>
   <td style="text-align:left;"> $TSLA $SNDL $1800 into $40k in the last 30 days!! If you really want to make huge profits on trading then....👇 technicalanalysis.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:36:40 </td>
   <td style="text-align:left;"> $TSLA whoever got them 900$ calls at 0.68 before close ya some lucky bastards… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:36:18 </td>
   <td style="text-align:left;"> $TSLA oh boy... $SPY 
 
https://www.cosmopolitan.com/entertainment/celebs/a39417966/grimes-dating-whistleblower-chelsea-manning/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:36:14 </td>
   <td style="text-align:left;"> $TSLA Best room on the net! I&amp;#39;ve made over 35k by their alerts&amp;#39; free.stocktradingchat.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:36:11 </td>
   <td style="text-align:left;"> $TSLA A rise of $13.61 in after hours… tells you the pot is cooking…. A hearty Meal will be served tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:34:25 </td>
   <td style="text-align:left;"> $SHIB.X $FJB.X $F $BP $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:33:26 </td>
   <td style="text-align:left;"> $TSLA 1400 please , easily achievable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:33:17 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-14 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=EO9WO6wl2_U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:29:51 </td>
   <td style="text-align:left;"> $MULN $DWAC $RIVN $USDT.X $TSLA somebody about to get roasted premarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:27:02 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

How much of your net worth is in the stock market? Percentage wise I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:26:22 </td>
   <td style="text-align:left;"> $TSLA nasdaq 10% up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:24:36 </td>
   <td style="text-align:left;"> $TSLA change my position to short.
Fucking hedges </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:24:10 </td>
   <td style="text-align:left;"> $LKNCY $T $TSLA $1800 into $40k in the last 30 days... If you really want to make huge profits on trading then.,, Join this winning chat:-   🚀 livetradingview.synergize.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:23:05 </td>
   <td style="text-align:left;"> $TSLA 

GENTLEMEN ....EHIS IS GETTING NASTY....SO GET READY:

This REALLY IS &amp;quot;Phase Two&amp;quot; of THEIR &amp;quot;Great Reset&amp;quot;. The fraud is no longer entertaining. The fear porn continues....and the rest of the world&amp;#39;s governments will &amp;quot;follow&amp;quot;....as they did the first time.  :  (

This from Yahoo News. China just locked down 51 million people because of an alleged &amp;quot;outbreak&amp;quot;. No one believes it nor should they.

However, China was &amp;quot;in bed&amp;quot; with Russia all along....including the 
attack on Ukraine.  This is going to get worse as will the markets. 

Seriously, protect your positions.

Best to all. :)

https://news.yahoo.com/china-orders-51-million-lockdown-124651019.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:22:55 </td>
   <td style="text-align:left;"> $TSLA I have $950 call expiring Friday…All smiles here ladies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:22:30 </td>
   <td style="text-align:left;"> $SPY $SOXL $TQQQ $TSLA $AAPL 
Commodities Dripping 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:22:12 </td>
   <td style="text-align:left;"> $TSLA is chinas supply chain issue / lockdown gonna be an issue here you think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:21:49 </td>
   <td style="text-align:left;"> $SPY CALLS were swollen today from MM 🥊💥🤕 .. bulls entire weekend excitement got REKT 😆📉 
 
BUT WAIT THERE&amp;#39;S MORE 😂 - PPI, RATE HIKES,  CHINA LOCKDOWNS,  ZELENSKY wildcard,  Iran deal etc..  - sigh PUTS SECURED♻️💰 since $480 
 
DIP BUYERS have been obliterated! ☠️😭🚮 (Tom Leech Lee/Cathie 12 Cats 🐈  Wood&amp;#39;s crew etc) $COUP $QQQ $AFRM $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:21:33 </td>
   <td style="text-align:left;"> $SPY $TSLA +13 post-market. Would like nothing more than a gap &amp;#39;n go tomorrow to trap the shorts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:19:31 </td>
   <td style="text-align:left;"> $TSLA $800 Tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:19:27 </td>
   <td style="text-align:left;"> $SPY from now on Russia is nothing more than a damp sock puppet of China, just as North Korea...
Great job, Mr Pu! (What an idiot!) $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:19:18 </td>
   <td style="text-align:left;"> $DIDI Getting in Car and EV business .This will be game changer $TSLA $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:19:00 </td>
   <td style="text-align:left;"> $TSLA hang sent recovering </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:18:22 </td>
   <td style="text-align:left;"> $TSLA shorts licking their chops seeing some green that will disappear very fast in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:16:09 </td>
   <td style="text-align:left;"> $TSLA  China &amp;amp; Russia are the new Nazi Germany &amp;amp; Japan in todays era </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:11:52 </td>
   <td style="text-align:left;"> Musk challenges Putin to ‘single combat’ over Ukraine, Russia responds: &amp;#39;Weakling&amp;#39; | Fox Business

Did Elon challenge Putin in a fight?

If I were to wager it would be on Putin, not because I like Putin but because Putin is a trained KGB killer.

There is no way Elon would last even 5 minutes with an ex KGB agent.

$TSLA $SPY $QQQ  https://www.foxbusiness.com/lifestyle/elon-musk-putin-single-combat-ukraine-russia-responds-little-devil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:09:23 </td>
   <td style="text-align:left;"> $TSLA HSI -8% in 2 days,  any effect? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:06:47 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC whenever I see liberals wearing a mask, I make fun of them until they cry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:06:07 </td>
   <td style="text-align:left;"> $TSLA https://www.cnbc.com/2022/03/15/chinas-retail-sales-industrial-data-soundly-beat-expectations.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:05:13 </td>
   <td style="text-align:left;"> $TSLA sorry guys, China is closed. Covid is back. Oh, nice AH pamp though, it’s going to add some excitement tomorrow lmafo

https://twitter.com/zerohedge/status/1503546236682575875?s=20&amp;amp;t=v1riycyIphBiUBxLNtapwA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:02:26 </td>
   <td style="text-align:left;"> $TSLA how many Teslas does Hertz have? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:02:11 </td>
   <td style="text-align:left;"> $TSLA If it breaks $743, $688 will be its next stop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 10:00:21 </td>
   <td style="text-align:left;"> $TSLA just when this thing looks destined for $500 Elon is going to pull out his dick. Space -x ipo can come anytime with Tesla shareholders getting first dibs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:59:38 </td>
   <td style="text-align:left;"> $TSLA easy to manipulate the price after hours with little volume. Wait for 9:30, the higher they pump premarket, the better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:59:15 </td>
   <td style="text-align:left;"> $TSLA half off soon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:58:31 </td>
   <td style="text-align:left;"> $LKNCY $T $TSLA Account Challenge Update:-    
Start Date: Feb 5, 2022    
Starting Balance: $1,800    
Current Balance: $89,637    
Goal: $100,000 by end of March.   
Strategy: Swing Trade Options, Stocks    
     
Watch out for next play------ technicalanalysis.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:58:06 </td>
   <td style="text-align:left;"> $TSLA $SPY $SHOP $ROKU $AMZN I have been saying these past few weeks... it will only get worse.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:54:14 </td>
   <td style="text-align:left;"> $GME $KODK $OPNT $AMC $TSLA 
Most Anticipated Earnings This Week   
https://www.financegreater.com/earningscalendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:54:14 </td>
   <td style="text-align:left;"> $TSLA ⚡

China Continues to Crash ⚡ 🔴 🔻 🔴 ⚡ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:52:59 </td>
   <td style="text-align:left;"> $BTC.X is this why Tesla shot up ? $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:52:17 </td>
   <td style="text-align:left;"> $TSLA who bought the fake pump after hours? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:50:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:46:45 </td>
   <td style="text-align:left;"> $TSLA wen green day fanboys?...🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:46:14 </td>
   <td style="text-align:left;"> $TSLA dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:44:18 </td>
   <td style="text-align:left;"> $TSLA We made money again! Those
who have been following me have been
making money consistently. Haters
spread hate but I have helped retailers
make money for free during past few
weeks when most were losing
If you missed my daily plans follow my
twitter  @optionboys or if you want to
join my private group message me. (it&amp;#39;s
actually fairly cheap to join) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:43:49 </td>
   <td style="text-align:left;"> $TSLA we are ripping!  Market is rigged. The opposite will happen this week since everyone things we are going to drop.  ATHs coming! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:42:31 </td>
   <td style="text-align:left;"> $TSLA wen hertz deal?...🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:42:27 </td>
   <td style="text-align:left;"> $TSLA I hope this whole shit burns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:42:23 </td>
   <td style="text-align:left;"> $BABA 

Bulls want to educate us (the stupid bears). Their lesson however, is l hopium with a hint of speculation. Our thesis is simple, real and rational. You hold a stock that you believe is a reflection of the performance of a company that shares profits with you, I believe you hold a piece of paper that has no financial claim to said company. The sooner you get this simple lesson, the sooner you crack your closed up brains to many possibilities. The stock is not the company. It never is. If the stock were the company, $TSLA will be $25 today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:42:09 </td>
   <td style="text-align:left;"> $TSLA Should have known… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:42:05 </td>
   <td style="text-align:left;"> $TSLA so yeah, that fake pamp AH, well done.. see you bulls tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:41:42 </td>
   <td style="text-align:left;"> Tesla China Deliveries: Weaker And More Important Than You Think $TSLA https://skr.ma/aG9DDUwtV1cYUKXE9 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:39:59 </td>
   <td style="text-align:left;"> $TSLA If there are more and more electric cars  the oil and gas prices will drop to below $30 and will be cheap to drive a gas car than electric </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:39:54 </td>
   <td style="text-align:left;"> $TSLA lmao, good one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:39:22 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I’m gonna end a perma bulls career tomorrow...🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:39:20 </td>
   <td style="text-align:left;"> $TSLA Voloridge Investment Management, Llc increased their holdings by 8,351%, one of the largest institutional increases this quarter https://www.insider-analysis.com/search_whales.php?ticker=TABLE_TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:38:40 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:37:06 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING! 

Elon Musk Gives US Labor Secretary a Tour of Tesla Giga Texas🤠🙌

🙏🏻🐉🦅 🤠 

https://www.tesmanian.com/blogs/tesmanian-blog/elon-musk-gives-labor-secretary-a-tour-at-tesla-giga-texas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:36:37 </td>
   <td style="text-align:left;"> $TSLA where’s Hertz at bruh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:36:01 </td>
   <td style="text-align:left;"> $TSLA people seem split on tsla, 50% bear, %50 retard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:35:46 </td>
   <td style="text-align:left;"> $TSLA XI XI no care about you teslatards 

https://twitter.com/zerohedge/status/1503544812301078534?s=20&amp;amp;t=tnidGmcBM_DOqpnlDu_WFA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:35:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC deport all liberals and bear to China, send them to slave camps until they love America </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:34:21 </td>
   <td style="text-align:left;"> The NADA show was suppose to be about Ozop Plus EV Warranties 

As an added and unexpected bonus the show seemed to focus on major problems that   $OZSC Ozop Energy Solutions NeoGrids, Battery Storage, &amp;amp; Solar will be solutions 🏆

Other solutions will be $TSLA Tesla’s Solar and Battery Storage as well as $FCEL Fuel Cell Hydrogen Power Plants 🏆

Must listen to this whole video and invest your life in these companies 😎

https://m.youtube.com/watch?v=4ohdZhtxFB4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:34:11 </td>
   <td style="text-align:left;"> $TSLA pump $SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:34:08 </td>
   <td style="text-align:left;"> $AMC $NIO $TSLA     Best room on the net!! I&amp;#39;ve made over 35k by their alerts...  insideranalysis.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:34:05 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-14 Daily Forecast Video: 
https://www.youtube.com/watch?v=uDAUaJGVq80 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:32:56 </td>
   <td style="text-align:left;"> $SPY crazy how this holds super green with world market falling in booooolishhhhh with $TSLA call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:32:53 </td>
   <td style="text-align:left;"> $TSLA even Trump was talking about Elon last night at his rally and Elon’s tweet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:32:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 

It’s over... flush it, all of it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:32:24 </td>
   <td style="text-align:left;"> $CEI $RIVN $FTCH $BABA or $TSLA Which is the best play long term? All seem to be at a big dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:31:14 </td>
   <td style="text-align:left;"> $SOFI I guess inflation is getting real. 4% hike on tuition.  Is all the schools going to increase their tuition? @POTUS Can you pause the inflation on the tuition? $LCID $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:31:09 </td>
   <td style="text-align:left;"> $SPY it’s actually quite amazing how well the overall indices have held up with so many tech stocks, including mega caps, dropping nearly 50% or more $FB $NFLX $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:30:04 </td>
   <td style="text-align:left;"> $TSLA Elon is the new Chuck Norris </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:29:15 </td>
   <td style="text-align:left;"> $MULN price closes:

✅ March 4th: $0.79 
✅ March 5/6th: weekend
✅ March 7th: $1.06
✅ March 8th: $1.24
✅ March 9th: $1.15
✅ March 10th: $1.07
✅ March 11th: $1.35
✅ March 12/13th: weekend
✅ March 13th: $1.77 

Higher lows! 🌋📈
$F $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:28:21 </td>
   <td style="text-align:left;"> $TSLA China wants all the smoke

https://twitter.com/zerohedge/status/1503531486514982919?s=20&amp;amp;t=tnidGmcBM_DOqpnlDu_WFA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:27:23 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC liberals have hijacked our government, they are destroying our country from the inside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:24:52 </td>
   <td style="text-align:left;"> $TSLA not a holder but thought you could use this here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:24:06 </td>
   <td style="text-align:left;"> $TSLA “if it hits 749 it will go to 750, and then back to 748…” 

“800 eod”

Last week “900 eod”

This market is shot. Buy and hold. Keep day trading aka gambling. 

“It will hit vwap and then it will go up or down”… wow 😮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:23:46 </td>
   <td style="text-align:left;"> $TSLA this is going to $700 tomorrow I don’t know why everyone here is so bullish. Short term it will fall hard! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:22:52 </td>
   <td style="text-align:left;"> $BOXL took a break from trolling pope and seen that Elon is being a straight savage on twitter right now and it’s absolutely hilarious $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:20:45 </td>
   <td style="text-align:left;"> $TSLA China&amp;#39;s zero-COVID policy put to the test amid multiple outbreaks driven by &amp;#39;stealth omicron&amp;#39; https://www.marketwatch.com/story/chinas-zero-covid-policy-put-to-the-test-amid-multiple-outbreaks-driven-by-stealth-omicron-01647304752?reflink=mw_share_twitter 
 
 Shenzhen locked down as China faces its worst surge since early 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:20:45 </td>
   <td style="text-align:left;"> $TSLA 

How long till Elon challenges Chelsea Manning to a fight?  Who wins? 

 https://www.thenews.com.pk/amp/940828-grimes-dating-chelsea-manning-after-second-breakup-with-elon-musk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:20:05 </td>
   <td style="text-align:left;"> $TSLA Elon has become way more likeable. The guy is ready to talk it out with his hands for Ukraine 👊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:19:58 </td>
   <td style="text-align:left;"> $TSLA I am afraid we may dip a little lower in the morning but can&amp;#39;t count out an afternoon bounce. This is set for a reversal but volume on Fed meeting day may be a little weak. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:19:52 </td>
   <td style="text-align:left;"> Bye $F choose $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:19:08 </td>
   <td style="text-align:left;"> $AMC $NIO $TSLA    All that you need to know. Shorts haven&amp;#39;t covered a single share;; Check it out below 👇  
  
highly recommend everyone to follow them. 🚀  insideranalysis.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:18:30 </td>
   <td style="text-align:left;"> $MULN 

Top SUV award beating out $TSLA Model Y and Rivian’s SUV ⚡️📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:17:20 </td>
   <td style="text-align:left;"> $TSLA I wouldn’t even pay $85 dollars for this dog sh*t </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:16:08 </td>
   <td style="text-align:left;"> $MULN let see if  the huge volume continue tomorrow! I just can&amp;#39;t wait till this becomes the next $TSLA, or even 1/10 of Tesla, I would be happy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:15:28 </td>
   <td style="text-align:left;"> $SPY $AMD $TSLA $AMZN &amp;amp; $AAPL  🧞‍♂️💎😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:15:18 </td>
   <td style="text-align:left;"> $TSLA  Can&amp;#39;t wait for back to back green DAYS with MASSSIVE gains.  MY $TSLA family we are due.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:15:12 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:14:02 </td>
   <td style="text-align:left;"> $SPX $TSLA $BABA $BIDU $ROKU  Bearish Market Continues - China Helping Putin - KREMLIN Cracks 
https://youtu.be/ySW7qnfYLGc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:14:02 </td>
   <td style="text-align:left;"> $TSLA 700 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:11:23 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

Futes looking weak, like a 🐂....🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:11:10 </td>
   <td style="text-align:left;"> $TSLA Will Wednesday be a finger or fist up the ass? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:10:11 </td>
   <td style="text-align:left;"> $SPY My Hero 🤣🤣🤣🤣 $NFLX $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:09:54 </td>
   <td style="text-align:left;"> $TSLA ignoring what’s going on in china wont help us and I’m bullish on this but bearish short term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:09:27 </td>
   <td style="text-align:left;"> $TSLA nice little pop at the end there, I wonder what&amp;#39;s going to happen tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:07:37 </td>
   <td style="text-align:left;"> $SPY $GME $AMC $IWM $TSLA CLOV 4 stocks patty’s week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:06:48 </td>
   <td style="text-align:left;"> $SPY $DWAC $TSLA If I were perhaps a low iQ individual I would say Joe Biden is very smart and a good president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:05:37 </td>
   <td style="text-align:left;"> $TSLA A guess.  You&amp;#39;ll see an upgrade with an increased target price by a respected analyst tomorrow morning, hence, the A/H move higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:03:37 </td>
   <td style="text-align:left;"> $TSLA Fair price is $300 no a penny more, and I&amp;#39;m being super generous. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:03:31 </td>
   <td style="text-align:left;"> $SPY $TSLA  💎🧞‍♂️💎 Hey 👋 $AMZN $NFLX 

   Hey all 👋         Just shake it off   🥂 

https://music.amazon.com/albums/B00OXE341G?do=play&amp;amp;trackAsin=B00OXE3GEG&amp;amp;ref=dm_sh_TqwVtiDhk5JgzKZ7MrBB4s95E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:03:29 </td>
   <td style="text-align:left;"> $TSLA $V   feels like stable coins at 8% are the safest play these days. 
Gemini, Block Fi or Celsius or spread it out with all 3. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:03:05 </td>
   <td style="text-align:left;"> $TMC -worlds largest nickel reserves 🚀
“NICKEL PLAY is the BEST EV PLAY! “
-Nickel supply continue to diminish while its cost continue to go up! 
-Ukraine war and inflation make nickel crisis worst! $TSLA $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:02:21 </td>
   <td style="text-align:left;"> $AMC $tsla $gme $sava $AMZN looks the big boys just got taken to a 11% woodshed in China... panic selling sure more tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:01:46 </td>
   <td style="text-align:left;"> $TSLA https://www.hitc.com/en-gb/2022/03/14/elon-musk-martial-arts/ Elon will dominate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:01:21 </td>
   <td style="text-align:left;"> $TSLA Even $SHOP is at a 22 P/E only this $tsla is still above 140 P/E in the entire market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:00:54 </td>
   <td style="text-align:left;"> $TSLA can anyone here explain why the pump AH? I don’t see any news! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 09:00:13 </td>
   <td style="text-align:left;"> $QQQ $SPY  ==&amp;gt; WAR HAS NOTHING TO DO WITH INFLATION &amp;amp; ALL THE ECONOMIC MESS IN THIS COUNTRY.   FIRE THIS FUCKING GOVERNMENT...  WHAT A F*CKING JOKE!! 😷😷💀💀💀 
. 
$TSLA  $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:59:40 </td>
   <td style="text-align:left;"> $TSLA Cramer says stocks may bottom sooner than expected because Wall Street is so negative. Okay so no bottom for a while huh? got it thanks Cramer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:58:54 </td>
   <td style="text-align:left;"> $TSLA why it soiked ah? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:58:16 </td>
   <td style="text-align:left;"> $TSLA  all I have to say is ELON IS FREAKING AWESOME! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:57:35 </td>
   <td style="text-align:left;"> latex936533a4619c9b6432c4c6d13454b51eBABA - 57% put flow 
$VXX - 53% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:51:43 </td>
   <td style="text-align:left;"> $TSLA Lol, Someone gave Elon some bad blow. Elon Musk challenges Vladimir Putin to single combat on Twitter: &amp;#39;Stakes are Ukraine&amp;#39;. https://www.usatoday.com/story/news/world/2022/03/14/elon-musk-putin-fight-ukraine/7036541001/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:51:35 </td>
   <td style="text-align:left;"> $TSLA Elon Musk Hints at Tesla Price Hikes Amid Sky-High Inflation

https://www.thestreet.com/investing/elon-musk-hints-at-tesla-price-hikes-amid-sky-high-inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:50:37 </td>
   <td style="text-align:left;"> $TSLA will be fun to watch tomorrow 
 
2 support levels &amp;gt;&amp;lt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:50:24 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Mar 25 $765 Puts at the Bid: 10 vs 231 OI; Earnings 4/25 After Close [est] 🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:50:04 </td>
   <td style="text-align:left;"> $TSLA $FB $MU $F $1800 into $40k in the last 30 days. If you really want to make huge profits on trading then,, Join this winning chat:~~~~🚀 best-optionminningchat.iblogger.org </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:49:03 </td>
   <td style="text-align:left;"> $TSLA $900 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:49:00 </td>
   <td style="text-align:left;"> $TSLA: The Revenue is expected to grow by 26.92% on average over the next 5 years. This is a very strong growth https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:48:55 </td>
   <td style="text-align:left;"> $TSLA let’s go back to 800. Stop playing around. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:48:53 </td>
   <td style="text-align:left;"> $TSLA  if China pulls a Russia on Taiwan, I wonder if Elon will respond to their aggression the same he has Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:48:35 </td>
   <td style="text-align:left;"> $TSLA BOTTOM IS $692 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:47:53 </td>
   <td style="text-align:left;"> $TSLA
Elon Musk 
challenged Putin to single combat over Ukraine
Let’s go 
Elon https://www.businessinsider.com/elon-musk-challenges-putin-single-combat-over-ukraine-2022-3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:46:47 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:46:24 </td>
   <td style="text-align:left;"> $tsla $SPY dug deep for this one 🙃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:46:08 </td>
   <td style="text-align:left;"> $TSLA  bull week incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:46:04 </td>
   <td style="text-align:left;"> $TSLA phew closed my puts today haha made $4k but didn&amp;#39;t get calls or anything this can bleed down again thou tomorrow this is clearly elons doing he knows spx 4000 happening and doesn&amp;#39;t want this to drop below 750 .... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:45:00 </td>
   <td style="text-align:left;"> $SPY $AAPL    🔈🧞‍♂️🔈  Hey 👋 $TSLA $AMZN 

https://music.amazon.com/albums/B006AKRY3K?do=play&amp;amp;trackAsin=B006AKRYP8&amp;amp;ref=dm_sh_EXyTuwbYCDpYP3HfzQ5mxF7fe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:43:35 </td>
   <td style="text-align:left;"> $SAVA $TSLA $LMND in this country only shorts , criminals and corrupted are making money .....Retails are Funds encouraging Innovative companies and R&amp;amp;D are getting hair cuts everyday .....Shame to America , where is the American dream ???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:43:17 </td>
   <td style="text-align:left;"> $TSLA Don&amp;#39;t worry,  there is so much more room to bleed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:42:40 </td>
   <td style="text-align:left;"> $AMC $AMAZ $SAVA $TSLA $GME wtf is going on here is the market so corrupt  that there is no chance of a rebound... will Gary shut down the PFOF dark pools before it’s too late ? The market is imploding. I am not selling but have lost my ass the past 4 months. Good luck to those holding on.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:41:27 </td>
   <td style="text-align:left;"> $TSLA  the smartest man alive!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:40:55 </td>
   <td style="text-align:left;"> $TSLA Might see $780 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:40:54 </td>
   <td style="text-align:left;"> $tsla $SPY $QQQ As WW3 are looming and I can’t fill my car for less than $90, I find comfort in knowing that nobody’s feelings got hurt on Twitter today and the only thing that really matters is we have a woman as Vice President. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:40:49 </td>
   <td style="text-align:left;"> $TSLA elon musk needs to run for president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:39:58 </td>
   <td style="text-align:left;"> $TSLA $760 OPEN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:39:13 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $SOXL $TQQQ 
Good time for longer-term investors to buy stocks. Historically, the S&amp;amp;P 500 tends to post impressive gains in the 12-month period following an initial close in a death cross. Based on the 53 times the index has closed in death-cross territory, the average gain over that span is 6.3%, according to Dow Jones Market Data.
🖕🤡 @magic_tape 
https://www.google.com/amp/s/www.barrons.com/amp/articles/stocks-death-cross-s-p-500-51647278854 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:34:17 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMC $GME This looks to me like there is some rough waters ahead for Wall Street. Kind of a “we warned you and we will not bail you out” type of things.  
 
Any Opinions? I’d love to hear em ‘ 
 
https://www.sec.gov/news/statement/tm-staff-statement-20220314 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:32:59 </td>
   <td style="text-align:left;"> $TSLA $AMZN $GOOG $GOOGL 

Here&amp;#39;s everything the Federal Reserve is expected to do at its meeting this week https://www.cnbc.com/2022/03/14/heres-everything-the-fed-is-expected-to-do-at-its-meeting-this-week.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard

Tesla will drop down to 100 per share … I’ll buy 500 shares there but not cheaper . Market dictates price … Amazon going lower , people not on google anymore they are on DUCK DUCK DUCK 🦆 GO 🚨🚨🚨🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:32:06 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-14 Options Analysis Video: 
https://www.youtube.com/watch?v=iuLwhbP5nOE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:32:03 </td>
   <td style="text-align:left;"> $TSLA had over 21.61M in Unusual Activity today with several large trades coming in, with a bearish sentiment. See more details on #Sweepcast.com #Stockstowatch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:29:08 </td>
   <td style="text-align:left;"> $TSLA I saw everyone posting about MULN on the tesla Stocktwits board so I sold all my shares Friday and bought in. Made 30% today while the dweebs at tesla lost 4%

Thank god for real companies and not frauds!!! $MULN to the moon!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:26:08 </td>
   <td style="text-align:left;"> $TSLA another city locked down in China lmfao 

https://twitter.com/zerohedge/status/1503520131363835907?s=20&amp;amp;t=BgnzQNsgoJ7y6njcyPoTSA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:25:52 </td>
   <td style="text-align:left;"> $SPY  China did its black swan thing, Putin did his black swan show, will Powell show his black swan surprise? $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:25:44 </td>
   <td style="text-align:left;"> $TSLA what caused the spike after hours? Any news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:24:53 </td>
   <td style="text-align:left;"> $TSLA $GOOGL https://apple.news/AxazfUgt0RyatFZmAgi_Pdg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:24:39 </td>
   <td style="text-align:left;"> $TSLA London Metal Exchange to resume nickel trading Wednesday https://www.marketwatch.com/story/london-market-exchange-to-resume-nickel-trading-wednesday-271647291880?reflink=mw_share_twitter Trading was halted March 8, the first time the LME had suspended a market since 1985 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:24:22 </td>
   <td style="text-align:left;"> $TSLA imagine you’re so battered that a 1.78% after hours “pump” makes you go ballistic. 🥴😵‍💫😆🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:23:47 </td>
   <td style="text-align:left;"> $TSLA anyone holding 900 calls for Friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:22:45 </td>
   <td style="text-align:left;"> $TSLA tomorrow we reclaim 800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:22:21 </td>
   <td style="text-align:left;"> $TSLA question for you buffoons when did AF price really  matter? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:22:11 </td>
   <td style="text-align:left;"> latex8c609f4f7da1a3a9a5936efac48fc5cfHUDA Long 1pt
$KSCP Long ~1pt

Liv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:21:04 </td>
   <td style="text-align:left;"> $TSLA   Today’s market was not “oversold”.    Just low … very low volume.   Most hedge fund leaders sold last week.   Look at the volume last week Monday vs. today.    Tesla will hit below support/resistance $720-750 this week.     Many MANY Europe countries sold their stuff last week.    With federal government raising interest rates for the 8th times, we will see a big drop on Wednesday.    Tomorrow will be only day that market might be green; if you see the opportunity, sell it and buy back later for the cheaper price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:20:40 </td>
   <td style="text-align:left;"> $DWAC $TSLA on deck..... the mother of  all housing crashes. 
 
“Freddie Mac’s weekly mortgage rate survey rate is standby for multiple news organizations to print their once-a-week mortgage rate color. The bigger problem is that Freddie’s survey headline often gives the wrong impression about where rates are and how they’ve been moving. Rates aren’t merely changing a lot from day to day, they’re changing multiple times per day in many recent occasions. The average lender is now definitively up and over 4.25% for the first time since early 2019. In other words, today’s rates are the highest in almost 3 years.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:19:14 </td>
   <td style="text-align:left;"> $TSLA . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:19:08 </td>
   <td style="text-align:left;"> $TSLA people get excited for the after hours trading....I&amp;#39;d be skeptical it holds but idk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:18:46 </td>
   <td style="text-align:left;"> $TSLA https://www.youtube.com/watch?v=dP_PvBYdRJg&amp;amp;ab_channel=CNBC reminder. follow buffet strat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:18:17 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY $IWM  
 
DO NOT sell at bottom, wait 40 MORE HOURS! 
 
We could see Morningstar any time! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:17:55 </td>
   <td style="text-align:left;"> $TSLA NASDAQ index sinks into bear market ahead of Fed meeting on interest rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:16:51 </td>
   <td style="text-align:left;"> $TSLA the last thing you want to do is hold money during a war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:16:51 </td>
   <td style="text-align:left;"> $TSLA time to  crush these cockey cokehead liberal trash bears tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:16:42 </td>
   <td style="text-align:left;"> $TSLA 850 tomorow or fall back down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:15:58 </td>
   <td style="text-align:left;"> $TMC I’m a DJ this thread tomorrow and invite all my $TSLA friends. Also, I will invite my pumper buddies from $GME $AMC  $BBY over to hangout. Drinks on me 🥂🕺🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:14:30 </td>
   <td style="text-align:left;"> $TSLA 7% day tomorrow or I’ll drink my own pee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:13:37 </td>
   <td style="text-align:left;"> $TSLA I don’t wanna hear that there’s no correlation to BTC and Tessie… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:13:24 </td>
   <td style="text-align:left;"> $TSLA this pamp will be crushed before the open.. that’s why I posted earlier to any Tesla bull to dump in AH.. probably didn’t listen .. have fun hodling bags tomorrow lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:13:01 </td>
   <td style="text-align:left;"> $ARKK when $TSLA goes down to $430 ark is going to $25 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:12:42 </td>
   <td style="text-align:left;"> $TGB 25k at ~1.98 avg.  Let&amp;#39;s get back to business.  Oversold markets, and now that many have forgotten about the draft, it will probably arrive.  Also bought my Tesla today, so take that 200lb of CU off the market.  Carvana Tesla sales have quadrupled the last couple weeks I&amp;#39;ve been shopping.  There were 30 pages of cars, and now there are just a few with dozens of pages of &amp;quot;purchase pending&amp;quot;.  On that note my $TSLA calls can also start printing at any time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:11:08 </td>
   <td style="text-align:left;"> $TSLA they been trying to bait in buyers last two days with the small pumps throughout day during  market hours. Hasn’t worked. So now they gonna trigger fomo pump ah on no news. I bought a call before close as a hedge to my put as it’s been clear they been trying to save/control this bleed. I expected it more premarket as it’s been doing only for institutions to start unloading 10 mins before market open. Oi on 750 puts is crazy high so MM gonna pull all the tricks out as this was for sure headed below 750 tomorrow at rate it’s been dropping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:10:24 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL IQ Going parabolic! Thanks Geeenko Bahlobah! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:10:24 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC Joe Biden should call Trump for leadership advice, futures would rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:09:31 </td>
   <td style="text-align:left;"> $TSLA any market that allows daily swings in market cap that Tesla goes through is corrupt. Plain and simple. Day traders enjoy the volatility and rake it in while it lasts. Remember when we were all concerned about the split killing volatility like it should have? I believe this is one of MMs biggest ATMs. I hope you get that one day pop again soon. They love to kill both sides during this extended bleed. 

That being said if 690 comes again i think worth a stab. Easy exit if breaks down but be the most logical trigger for extended rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:09:05 </td>
   <td style="text-align:left;"> $TSLA Do you guys realize that everyone that bought $760 end of day will be selling at open! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:08:10 </td>
   <td style="text-align:left;"> $TSLA 

10M shares traded in the first 75mins of trading session- that’s extremely high, huge dumping started with 150k PM then followed by massive dumping backed by Market Makers and liquidity providers (brokers- mistagging shares) providing the necessary number of shares via DP. The problem I’m sharing with all of you is becoming more aggressive and represents a crime /felony ! 

The failure of SEC to track &amp;amp; audit is massive and should concern every one !!! 

These financial crimes committed by criminal thugs HFs daily are ripping the market everyday , destroying investors confidence !!! 

Y’all should speak up - write to your representative at the circus 🎪 sorry I meant at the Congress !! 

Thx for considering !

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:07:42 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:07:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC futures tanking, did Joe Biden call the war a slight incursion again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:06:49 </td>
   <td style="text-align:left;"> $TSLA will be recognized by Biden soon!Biden’s secretary of labor had a 75 minute meeting with Elon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:05:34 </td>
   <td style="text-align:left;"> $TSLA 😩https://youtu.be/nJmkq8R5bhA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:05:05 </td>
   <td style="text-align:left;"> $TSLA $AMD $SPY $QQQ 

🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:05:04 </td>
   <td style="text-align:left;"> $TSLA Plenty of places to get aluminum. His tweet towards Putin has nothing to do with Tesla not getting aluminum from Russia anymore. Even without the tweet, I guarantee that Tesla was already planning on sourcing the aluminum elsewhere.  Nobody is doing business with Russia.  It&amp;#39;s irrelevant at this point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:04:36 </td>
   <td style="text-align:left;"> $TSLA puts=FUKD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:04:32 </td>
   <td style="text-align:left;"> $TSLA anyone into ESG? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:04:14 </td>
   <td style="text-align:left;"> $DWAC $XOM $TSLA  “A world that has been awash with free money under central bank policies to stem the full financial impact of 2008 and the Covid crisis looks more than a little vulnerable given how asset prices have been inflated and how debt levels have risen to new records.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:04:11 </td>
   <td style="text-align:left;"> $TSLA Musk on Twitter be like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:03:40 </td>
   <td style="text-align:left;"> $TSLA why is it going up after hours but my puts not moving?? LAFAO! 🤣😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:03:29 </td>
   <td style="text-align:left;"> $TSLA  
https://www.dailymail.co.uk/news/article-10610887/I-challenge-Vladimir-Putin-single-combat-Elon-Musk-tweets-wants-fight-strongman.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:02:53 </td>
   <td style="text-align:left;"> $TSLA 780! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:02:53 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-14 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=EO9WO6wl2_U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:02:48 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:02:44 </td>
   <td style="text-align:left;"> $TSLA why is it going up ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:02:09 </td>
   <td style="text-align:left;"> $NIO Going way up tomorrow morning maybe all day long ,all week long too. $TSLA back up to 780 ah&amp;#39;s.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:02:04 </td>
   <td style="text-align:left;"> $ARKK I wish Elon would demand Cathie take $TSLA out of her fund. It’s dragging the stock down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:01:27 </td>
   <td style="text-align:left;"> $TSLA why is everyone asking why up after hours..ask why it was down 4% during the day….same reason it’s up…some massive news coming in 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:00:54 </td>
   <td style="text-align:left;"> $TSLA HAHA what a joke- dumped off $5 in the last 5 minutes of AH. This will be down again tomorrow as usual. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:00:18 </td>
   <td style="text-align:left;"> $TSLA average wall street price target is 1400-1600 and the bears are so radically bearish that they rather bet this thing goes to 500 instead of riding the train up what’s gonna happen is when this roars back up bears will lose the gains they made on the way down so typical </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:00:13 </td>
   <td style="text-align:left;"> $TSLA what a fake ass pop lol… like I said earlier, see ya at $715 tomorrow! 🥱🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:00:12 </td>
   <td style="text-align:left;"> $TSLA party is over dump incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 08:00:07 </td>
   <td style="text-align:left;"> $TSLA tomorrow this will close below 740 and all the Tesla Fanboys would have disappeared. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:59:56 </td>
   <td style="text-align:left;"> Received many questions from folks, all understandably anxious and frustrated, I&amp;#39;ll summarize my response here, the Stock market is not for everyone, 
I&amp;#39;ve been in the market for almost 2 decades, it is not a matter of luck, but the way you research and choose the stocks and transactions.   It is  
80% experience and skill, and 20% luck.   If you really knew how to navigate your way in the stock market, almost always you will be a winner, definitely you should diversify but make sure that you select stocks after thorough research and no one can do a better research than yourself, if you invest wisely here 
you wouldn&amp;#39;t care about market fluctuations and you can work not from home but you can WORK FROM THE BEACH actually 🙂 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:59:48 </td>
   <td style="text-align:left;"> $SPY $XBI $TSLA $SOFI 

It&amp;#39;s amazing how shitty one President can be and the damage they can do to a market in such a small time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:59:42 </td>
   <td style="text-align:left;"> $TSLA have you guys not been paying attention? This is pumping bc retail buys in the AH &amp;amp; PM &amp;amp; people with actual money dump during trading hours. STFU about bullish, this is the darkest time in human history. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:59:36 </td>
   <td style="text-align:left;"> $TSLA theres no other path forward. This is the end game </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:59:24 </td>
   <td style="text-align:left;"> $TSLA awesome, another short opportunity. All the bulls celebrating their imaginary gains while market is closed 🤣
Say it w/ me- IDIOTS 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:59:23 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL I’m going to try buying SPY shares using Rubles. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:59:11 </td>
   <td style="text-align:left;"> $TSLA let’s see 800s first thing in the morning and a close of $850 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:58:54 </td>
   <td style="text-align:left;"> $TSLA Shorts!! Tesla +up 14.5 points in AH!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:58:32 </td>
   <td style="text-align:left;"> $TSLA we at 785? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:58:20 </td>
   <td style="text-align:left;"> $TSLA huge rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:58:05 </td>
   <td style="text-align:left;"> $TSLA 😔https://youtu.be/-X4uMf4NYfY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:57:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL 
🤡 with puts wants the war to continue </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:57:37 </td>
   <td style="text-align:left;"> $TSLA long 4.14 810c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:57:35 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AMD 

Me checking my portfolio everyday knowing it’s going to be a bloodbath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:57:25 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:57:19 </td>
   <td style="text-align:left;"> $TSLA many people out sick in Shanghai via wechat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:57:02 </td>
   <td style="text-align:left;"> $TSLA Tesla is gearing up to launch a 279-mile range version of the Tesla Model Y. The vehicle will feature an AWD powertrain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:56:58 </td>
   <td style="text-align:left;"> $TSLA yawn. If there was still QE, then maybe I would be concerned.  However, no more QE means no more 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:56:58 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Market gonna market fam. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:56:29 </td>
   <td style="text-align:left;"> $TSLA when Elon says he&amp;#39;s not selling. There is something breweries coming up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:56:15 </td>
   <td style="text-align:left;"> $TSLA what a pump!! Losers want to flex AH and dump on retail!!! Fuck you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:56:12 </td>
   <td style="text-align:left;"> $DWAC $dwac $tsla $fb $twtr $spce 
 i told you guys a long time ago we should have switched to app voting for everything a decade ago!!! from sports teams to congress, EVERYTHING decided INSTANTLY by EVERYONE lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:55:53 </td>
   <td style="text-align:left;"> $TSLA so my puts are fucked? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:55:44 </td>
   <td style="text-align:left;"> $TSLA haha pumps and dumps are not just penny stocks anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:55:10 </td>
   <td style="text-align:left;"> $TSLA $2,500 EOY MARK IT! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:55:08 </td>
   <td style="text-align:left;"> $TSLA aapl is buying tesla news everywhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:55:00 </td>
   <td style="text-align:left;"> $TSLA why is this moving upward ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:54:44 </td>
   <td style="text-align:left;"> $TSLA wow this market crazy 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:54:32 </td>
   <td style="text-align:left;"> $TSLA 10:1 Split lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:54:09 </td>
   <td style="text-align:left;"> $TSLA so much for the puts…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:53:54 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC If libs, Dems, socialist losers loved government control, hates free speech so much why not just move to China? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:53:32 </td>
   <td style="text-align:left;"> $TSLA new model Y?? https://www.foxnews.com/auto/new-mystery-tesla-model-y-epa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:53:15 </td>
   <td style="text-align:left;"> $TSLA HUGE NEWS 🤩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:52:43 </td>
   <td style="text-align:left;"> $TSLA Lol bears losing sleep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:52:39 </td>
   <td style="text-align:left;"> $TSLA it’s pumping 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:52:37 </td>
   <td style="text-align:left;"> $TSLA damn $785 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:52:27 </td>
   <td style="text-align:left;"> $TSLA why is this moving!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:52:25 </td>
   <td style="text-align:left;"> $TSLA Tesla starts releasing big Full Self-Driving Beta update  
 
https://electrek.co/2022/03/14/tesla-full-self-driving-fsd-beta-update-10-11/ via @FredericLambert  
 
Now Tesla has started pushing a new FSD Beta 10.11 update to its Early Access Program, and it is a significant one based on the release notes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:52:20 </td>
   <td style="text-align:left;"> $TSLA buy American 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:51:53 </td>
   <td style="text-align:left;"> $TSLA https://www.benzinga.com/news/22/03/26129085/is-there-a-new-version-of-teslas-model-y-coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:51:42 </td>
   <td style="text-align:left;"> $TSLA Wow... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:51:37 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:51:29 </td>
   <td style="text-align:left;"> $TSLA 815 and $888 by eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:51:01 </td>
   <td style="text-align:left;"> $TSLA 785$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA waiting for putin to response to elon. I will pay , pay per view and make bets if they get into a ring!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:46 </td>
   <td style="text-align:left;"> $TSLA they eating them 650$ puts alive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:40 </td>
   <td style="text-align:left;"> $TSLA its not pump and dump, something is coming . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:39 </td>
   <td style="text-align:left;"> $TSLA... decent volume for AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:34 </td>
   <td style="text-align:left;"> $TSLA Njce move after hours. Lfgo! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:33 </td>
   <td style="text-align:left;"> $TSLA $1,400 eoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:31 </td>
   <td style="text-align:left;"> $TSLA 

Lucky 7s again ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:31 </td>
   <td style="text-align:left;"> $TSLA NEWS? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:24 </td>
   <td style="text-align:left;"> $TSLA they burning everyone?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:21 </td>
   <td style="text-align:left;"> $TSLA $785.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:04 </td>
   <td style="text-align:left;"> $TSLA 786 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:50:04 </td>
   <td style="text-align:left;"> $TSLA wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:49:45 </td>
   <td style="text-align:left;"> $TSLA Keep that green going!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:49:21 </td>
   <td style="text-align:left;"> $TSLA is it nio crashing? What’s the news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:49:14 </td>
   <td style="text-align:left;"> $TSLA fuck, if this AH pump hold and my puts are toast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:49:10 </td>
   <td style="text-align:left;"> $TSLA Is there any news causing this ridiculous spike? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:49:09 </td>
   <td style="text-align:left;"> $TSLA whyyyy😂😂 what is this shit😂😂plummets the whole day just to recover half the losses at 7:30pm screw this market damn MM’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:48:58 </td>
   <td style="text-align:left;"> $DARE 
After hours $XBI, $TSLA, $BTC.X, $ETH.X are all rising in reversal. Tomorrow looking bullish for Dare and many others! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:48:46 </td>
   <td style="text-align:left;"> $TSLA ok now ppi excuse?😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:48:39 </td>
   <td style="text-align:left;"> $TSLA Bears might want to work on backup plan... May be buy some  $850 calls... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-15 07:48:37 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
</tbody>
</table></div>

---
