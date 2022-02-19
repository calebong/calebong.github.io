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



Last Updated: 2022-02-19 08:52:03 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/nwg:ln </td>
   <td style="text-align:left;"> 2022-02-19 08:46:37 </td>
   <td style="text-align:left;"> Natwest Group PLC earnings above expectations at 0.04 USD </td>
   <td style="text-align:left;"> Natwest Group PLC (NWG) released earnings per share at 0.04 USD, compared to market expectations of 0.03 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/18/asia/north-korea-defectors-return-intl-hnk-dst/index.html </td>
   <td style="text-align:left;"> 2022-02-19 08:06:44 </td>
   <td style="text-align:left;"> Why North Korean defectors return to one of the world's most repressive regimes - CNN </td>
   <td style="text-align:left;"> Seoul, South Korea (CNN)He risked his life fleeing from one of the world's most repressive regimes, traversing a militarized stretch protected by barbed wire fences. Then a year later, he went back -- the way he came.                                                                                                                                     , More than one month since the man crossed the demilitarized zone from South to North Korea, much of his life in both countries remains a mystery -- as do his reasons for returning to the isolated nation ruled by Kim Jong Un.                                                                                                                              , South Korean media reported that the defector -- who hasn't been officially named, although fellow defectors say he was called Kim Woo-jeong in South Korea -- was a former gymnast who largely kept to himself. According to South Korean police, he was a construction worker in his 30s who earned money by doing manual labor.                            ,                                                                                                                                                                                                                                                                                                                                                               , The man's case is rare -- while more than 10,000 North Korean defectors have arrived in South Korea in the past decade, just 30 have returned home, where they face the prospect of being put into forced labor camps, according to official South Korean data.                                                                                               , But defectors and advocates say even if the man's rationale for leaving South Korea is unclear, the fact that some North Korean defectors are willing to return to one of the world's most politically isolated countries only highlights how challenging life can be in the South for North Koreans.                                                         , Why people defect                                                                                                                                                                                                                                                                                                                                             , Since the Korean War ended with an armistice in 1953, North and South Korea have been separated by an almost impenetrable border preventing anyone from crossing to the other side.                                                                                                                                                                           , Over subsequent decades, South Korea has modernized, becoming one of the world's richest and most technologically developed countries. Meanwhile, North Korea has become increasingly isolated, with citizens subject to widespread poverty and limited basic freedoms.                                                                                       , So it isn't hard to see why people may want to escape.                                                                                                                                                                                                                                                                                                        , Since 1998, more than 33,000 people have defected from North Korea to South Korea, according to South Korea's Unification Ministry. However, numbers have dwindled in recent years after Kim imposed even tougher border controls to prevent Covid inflows.                                                                                                   , On very rare occasions, defectors -- like the former gymnast -- manage to escape through the heavily guarded demilitarized zone separating North and South Korea. The vast majority, like defector Kang Chun-hyuk, flee over North Korea's lengthy border with China.                                                                                         , Kang's family made the trip in 1998 when he was 12 years old, before finally making it to South Korea a few years later.                                                                                                                                                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                               , In North Korea, Kang remembers barely having enough food to survive.                                                                                                                                                                                                                                                                                          , Sometimes, his family would make a single portion of dry noodles into a meal that would feed him and his parents for a week.                                                                                                                                                                                                                                  , "It wasn't worth going to school, so me and my classmates stole food like corn or potatoes," he said.                                                                                                                                                                                                                                                         , According to a survey of 3,000 people released this year by the North Korean Refugees Foundation, food shortages are one of the most common motivations for defection, with nearly 22% saying that was why they had defected. The most common reason given -- at 23% -- was that people didn't like being controlled or monitored by the North Korean regime. , Once they arrive in South Korea, there are measures in place to support them. Defectors undergo a compulsory, 12-week education session to help them adjust to life in their new home. They're given financial support and accommodation, and access to health care and employment services.                                                                  , But even so, life for defectors is often a struggle.                                                                                                                                                                                                                                                                                                          , Finding work and fitting in                                                                                                                                                                                                                                                                                                                                   , Before Kang Na-ra -- no relation to Kang Chun-hyuk -- defected in 2014 as a teenager, she thought her life in South Korea would mirror the K-dramas she watched in secret in the city of Chongjin.                                                                                                                                                            , But South Korea was a far cry from the romantic world she'd seen on screen.                                                                                                                                                                                                                                                                                   , Kang Na-ra's mother defected before her -- she does not want to say why -- but their life together in South Korea was not what she'd hoped.                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                               , Her mother worked long hours and was often away from home dancing in a North Korean defectors performing group to make ends meet. Although Kang Na-ra spoke the same language, she was lonely and had few friends in South Korea.                                                                                                                             , Another defector, who asked not to be named or further identified for fear of repercussions for his family remaining in North Korea, said he also struggled with culture shock when he defected a few years ago -- even bright and colorful signs and the abundance of English words used in language in South Korea made him feel uncomfortable.             , "You don't see things like that in North Korea," said the defector. "I didn't like many things in South Korea at first."                                                                                                                                                                                                                                      , He also said many defectors found it difficult to get a job.                                                                                                                                                                                                                                                                                                  , Statistics for 2020 released last year by South Korea's Unification Ministry found defectors had a higher unemployment rate than the general population, with 9.4% of defectors unemployed, compared with 4% of the general population in December 2020.                                                                                                      , "Getting a good job is important, but even South Koreans who are raised and educated here find it difficult to get a decent job," he said. "You can imagine how hard it can be for North Korean defectors."                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                               , Kang Chun-hyuk's family was given a flat by the government when they made it to South Korea in 2001 after three years in China. But his thick North Korean accent made it hard for him to fit in at school and he dropped out. He worked in manual labor until he was 25 years old, unsure if he would be able to ever do anything else.                      , For others, the struggle to adjust and find work can have deadly consequences. In 2019, North Korean defector Han Sang-ok was found dead in her apartment with her 6-year-old son after she failed to pay her bills for months.                                                                                                                               , A water meter inspector noticed a foul smell coming from the apartment and called the police, who found two heavily decomposed bodies and an empty fridge, leading the police officer to note starvation as the suspected cause of death.                                                                                                                     , Separation pains                                                                                                                                                                                                                                                                                                                                              , But not all defectors have dreams of a bright life in South Korea.                                                                                                                                                                                                                                                                                            , Kim Ryon-hui is a rare case of a defector who arrived almost by accident.                                                                                                                                                                                                                                                                                     , The 54-year-old, who lived a relatively upscale life in North Korea, went to China in 2011 to visit relatives and seek medical care for liver disease. But when she arrived, she found Chinese doctors wanted payment upfront.                                                                                                                                ,                                                                                                                                                                                                                                                                                                                                                               , Kim said a broker told her Chinese people often went to South Korea to earn money. So, she signed up for a journey to South Korea and left her North Korean passport with the broker group -- not realizing that meant she would never be able to return home.                                                                                                , Kim feels hostility from South Koreans, especially when North Korea's leader fires missiles. She told CNN she struggled to adapt to a capitalist society governed by market pressures and to understand what she sees as a dog-eat-dog world.                                                                                                                 , "It's like we're oil and South Korea is water, so we can't mix," she said.                                                                                                                                                                                                                                                                                    , That's a common sentiment for defectors. According to the North Korean Refugees Foundation survey, while most people are happy in South Korea because they can live a free life and earn relative to how much they work, many are unhappy with the level of intense competition.                                                                              ,                                                                                                                                                                                                                                                                                                                                                               , But the hardest part for Kim is the separation from her family. South Korean law prevents any communication with people in North Korea and South Koreans cannot travel there. Unless Kim sneaks back into North Korea, or the two Koreas reach a peace agreement, she has little chance of seeing her family again.                                           , Kim last saw her daughter when she was 17 -- now her daughter is 28. Kim is only able to communicate with her family through journalists who take letters and gifts for her to North Korea, but that hasn't been possible since North Korea closed its borders due to the Covid-19 pandemic in 2020.                                                          , "It's scary to be alone," she said. "When I see lights on in other apartments in the evening, I imagine families having dinner together. That's the saddest and loneliest feeling."                                                                                                                                                                           , Why defectors return                                                                                                                                                                                                                                                                                                                                          , Despite the difficulties of being in South Korea, the vast majority stay put. For most, that's because the benefits of staying in South Korea are far greater than the risks they face if they return.                                                                                                                                                        , Seo Jae-pyeong, the director of the Association of the North Korean Defectors, defected in 2001. In the 20 years he's lived in South Korea, he's only known one defector personally who returned to North Korea.                                                                                                                                              , She was a doctor with a family back in North Korea who didn't realize her brother was bringing her to South Korea, he said.                                                                                                                                                                                                                                   , "She didn't have a reason to defect and she couldn't get used to life in South Korea," Seo said.                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                               , He questioned how many of the 30 defectors who returned to North Korea had left of their own free will. He said some may have been blackmailed or kidnapped near the border between China and North Korea.                                                                                                                                                    , Others might have had major financial difficulties that left them with few other choices.                                                                                                                                                                                                                                                                     , Lee Na-kyung, a defector activist for single parents and people with disabilities from the North, said by the time many defectors arrive in South Korea they already have major debts to brokers who helped them cross the border.                                                                                                                            , Some defectors pay their government settlement money to the brokers, and then sink further into debt as they struggle to find work, according to Lee, who defected from North Korea in 2005 after her husband was framed for a crime she says he didn't commit.                                                                                               , For some, the hardship of life in South Korea doesn't meet their expectations. She knows of one man who was a high-ranking military officer in North Korea who could only find work in a junkyard in South Korea. "He said that he would rather die at home instead of dying as a junkman," she said.                                                         , What next?                                                                                                                                                                                                                                                                                                                                                    , A month after the gymnast Kim crossed back into North Korea, it's unclear whether he is still alive.                                                                                                                                                                                                                                                          , Although the South Korean military spotted him on surveillance footage crossing the barbed wires into the demilitarized zone, they failed to stop him, the South Korean military's Joint Chiefs of Staff chairman Won In-choul said in a briefing in January.                                                                                                 , He was seen four times on security camera on the south side of the border, and once after he crossed the Military Demarcation Line.                                                                                                                                                                                                                           , At one point, soldiers mistook him for a defector coming from the North. At another point, they went to find him. Later, they found no trace of him except a feather caught on a wire that they suspected had come from his puffer jacket.                                                                                                                    , There were "no unusual movements" of the North Korean military over the incident, South Korea's Defense Ministry spokesman Boo Seung-chan said last month at another briefing.                                                                                                                                                                                , And while North Korean state media has crowed about past defectors returning home, there has been no mention of last month's defector in state news publications.                                                                                                                                                                                             , For those in South Korea, it's a reminder that the country's policies to help defectors could still be improved. Last week, the South Korean government announced it was launching a new team to improve the safety of defectors, noting that despite its current efforts, some defectors were still "experiencing difficulties settling into our society."   , But defector advocates were dubious about how effective those new steps would be, pointing out that support measures are in place -- they just don't work.                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                               , Even defectors who appear to have successfully made their transition sometimes struggle with the pull back to North Korea.                                                                                                                                                                                                                                    , Two years after she defected, Kang Na-ra told her mother she wanted to go back. But she didn't want to risk her life after going through so much to get to South Korea.                                                                                                                                                                                       , Now Kang, 25, is a television personality and YouTuber with more than 300,000 subscribers who watch her clips about life in North Korea. Her income is unstable, but at least she's enjoying life.                                                                                                                                                            , "Still today, I wonder if I made the right decision," she said. "Life here is tough."                                                                                                                                                                                                                                                                         , Saeeun Park and Seoyeon Youn contributed to this story from Seoul, South Korea. </td>
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
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/02/18/joe-biden-putin-russia-ukraine-sot-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-19 06:45:22 </td>
   <td style="text-align:left;"> See Biden's warning to Putin from the White House - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/18/business/multinationals-in-ukraine-are-ready-for-a-conflict-but-staying-put.html </td>
   <td style="text-align:left;"> 2022-02-19 06:39:43 </td>
   <td style="text-align:left;"> Multinationals in Ukraine are ready for a conflict but staying put. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Despite warnings by Western leaders of an imminent Russian attack, U.S. and European companies say they see a low risk of an invasion.                                                                                                                                                                                                                                                                                                                                , By Liz Alderman and Melissa Eddy                                                                                                                                                                                                                                                                                                                                                                                                                                      , Big American and European companies operating on the ground in Ukraine said Friday that they had contingency plans at the ready in case of a Russian invasion but so far had not ordered the relocation of employees.                                                                                                                                                                                                                                                 , Even as Western leaders turned up warnings that President Vladimir V. Putin of Russia may order an attack on Ukraine, executives at the multinational companies, for the most part, don’t believe that Russian troops will actually follow through with a ground invasion, said Anna Derevyanko, the deputy director of the European Business Association.                                                                                                            , “Companies have put in place contingency plans, but they do not believe something terrible is going to happen,” said Ms. Derevyanko, whose association includes Nestlé, BASF, ArcelorMittal, Bayer and over 1,000 European firms that employ more than two million people in Ukraine.                                                                                                                                                                                 , “If you ask business people, they believe that a physical invasion is a low-risk scenario,” she added. “There is no sense of panic.”                                                                                                                                                                                                                                                                                                                                  , The prospect of cyberattacks, on the other hand, is more worrisome. Government websites, state-owned banks and parts of the nation’s infrastructure have battled online invasions byhackers, believed by Ukrainians to be Russians, looking to disable computers and steal data. European and American companies in Ukraine see digital attacks as one of the major threats they must deal with and have moved to strengthen their cybersecurity, Ms. Derevyanko said., The IT Ukraine Association, which includes local and international tech companies, such as Sigma Software and the video game giant Ubisoft, said that the industry’s presence in the country had grown steadily since Russia’s devastating invasion of Crimea in 2014.                                                                                                                                                                                                , Companies in the tech industry, now worth $6.8 billion, have plans to ensure the security and safety of their employees in the event of “emergencies” as part of their business strategy, the association said in a statement.                                                                                                                                                                                                                                        , “The Armed Forces of Ukraine have accumulated strength, gained combat experience and is ready to defend the country and its population,” the statement continued. In turn, it said, tech companies’ response plans  “are aimed at protecting talent and their business processes continuity.”                                                                                                                                                                         , More than 90 percent of the tech companies surveyed this month assessed the risk of an escalation of the conflict as low to medium, the association added, noting that none had prepared for a full relocation.                                                                                                                                                                                                                                                       , The American Chamber of Commerce in Ukraine said that its 633 members, which include 3M, Toyota and Citibank, continued to do business but had contingency plans to continue working in the event of an emergency.                                                                                                                                                                                                                                                    , A brewing conflict. Antagonism between Ukraine and Russia has been simmering since 2014, when the Russian military crossed into Ukrainian territory, annexing Crimea and whipping up a rebellion in the east. A tenuous cease-fire was reached in 2015, but peace has been elusive.                                                                                                                                                                                   , A spike in hostilities. Russia has been gradually building up forces near its border with Ukraine, and the Kremlin’s messaging toward its neighbor has hardened. Concern grew in late October, when Ukraine used an armed drone to attack a howitzer operated by Russian-backed separatists.                                                                                                                                                                          , Preventing an invasion. Russia called the strike a destabilizing act that violated the cease-fire agreement, raising fears of a new intervention in Ukraine. Since then, the United States, NATO and Russia have been engaged in a whirlwind of diplomacy aimed at averting that outcome.                                                                                                                                                                             , The Kremlin’s position. President Vladimir V. Putin of Russia, who has increasingly portrayed NATO’s eastward expansion as an existential threat to his country, said that Moscow’s growing military presence on the Ukrainian border was a response to Ukraine’s deepening partnership with the alliance.                                                                                                                                                            , Rising tension. Western countries have tried to maintain a dialogue with Moscow. But the Biden administration warned that the U.S. could throw its weight behind Ukraine in case of an invasion. France, Germany and Poland also warned Russia of consequences if it launched incursions into Ukraine.                                                                                                                                                                , Most of the member companies made their plans long ago but continue to update and review them, said Andy Hunder, president of the business association.                                                                                                                                                                                                                                                                                                               , Ms. Derevyanko, of the European Business Association, said that Ukraine was counting on continued foreign investment to help keep the economy stable. Multinationals are located around the country in agribusiness, pharmaceuticals, technology and logistics.                                                                                                                                                                                                       , Ukraine’s economy had only started to recover in recent years from a debilitating blow after Moscow in 2014 annexed Crimea, and pro-Russian rebels seized swathes of the eastern Donbas region in Ukraine. Since then, Western allies have seeded Ukraine and businesses operating there with over $48 billion in bilateral and multilateral economic support.                                                                                                        , This week, the United States pledged to strengthen Ukraine’s economy, after a statement by the Group of 7 industrial nations promising to do the same.                                                                                                                                                                                                                                                                                                                , “For now, companies are saying they plan to continue business as usual,” said Ms. Derevyanko. But the situation could yet grow complicated, especially if major seaports and airports are blocked, thwarting exports and dealing a further blow to the economy.                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-02-19 06:39:00 </td>
   <td style="text-align:left;"> Natural Gas Futures Drop ahead of Weekend </td>
   <td style="text-align:left;"> US natural gas futures swung between gains and losses to close 1% lower at $4.4 per million British thermal units on Friday, with the volatility being mainly driven by slight changes in weather forecasts for early March. The two-week weather outlook points to colder-than-usual temperatures but reports painted a mixed picture for the first days of March, with some forecasts seeing slightly milder weather. Also, investors continued to reassess the latest EIA inventory data, which came 3 billion cubic feet short (bcf) of market expectations at 190 bcf. The shortfall between current storage levels and the five-year average widened to 11.6%. On a weekly basis, the contract jumped 12.7%, rebounding from a 13.8% fall last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/18/business/media/allison-gollust-cnn-cuomo.html </td>
   <td style="text-align:left;"> 2022-02-19 06:30:12 </td>
   <td style="text-align:left;"> CNN’s Gollust Discussed Interview Topics With Gov. Cuomo, Probe Found - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                 , Supported by                                                                                                                                                                                                                                                                                                                                                                                  , An internal investigation found that a top executive, Allison Gollust, had extensive communications with then-Gov. Andrew Cuomo.                                                                                                                                                                                                                                                              , By Michael M. Grynbaum, John Koblin and Emily Steel                                                                                                                                                                                                                                                                                                                                           , On a Saturday in March 2020, as Covid-19 was invading the United States, Gov. Andrew M. Cuomo went on CNN for a live interview. Among other topics, he was asked about a possible government-enforced quarantine of New York that had been floated by President Donald J. Trump.                                                                                                              , It was a newsworthy topic, but its path onto viewers’ screens would turn out to be controversial — and highly consequential for the future of one of the world’s most powerful news networks.                                                                                                                                                                                                 , Before the interview, Governor Cuomo had told a senior CNN executive, Allison Gollust, about subjects that he’d like to be asked about on air, according to several people familiar with the matter. Ms. Gollust, CNN’s longtime chief of communications and marketing and a former top aide of the governor, passed along the topics to CNN producers and then reported back to the governor., “Done,” she wrote.                                                                                                                                                                                                                                                                                                                                                                            , On Tuesday, Ms. Gollust was forced to resign from CNN after an internal investigation found a trove of written communications between her and Governor Cuomo, including messages about the March 2020 appearance, the people said. Jeff Zucker, who at the time was CNN’s president, was aware of many of the communications between Ms. Gollust and the governor, the people said.           , The episode is the latest example of how closely entwined CNN’s leadership was with one of the country’s most prominent Democratic politicians.                                                                                                                                                                                                                                               , Producers and bookers for television news shows routinely talk with guests before their scheduled appearances and discuss questions and topics that are likely to come up on air. It is unusual, though, for a senior executive to be involved in that pre-interview process — especially when that executive previously worked for the person who’s being interviewed.                       , Risa Heller, a spokeswoman for Ms. Gollust, said the communications with the governor were appropriate. Ms. Gollust “in no way suggested that inclusion of these topics was a condition of the interview, nor did she suggest the interview should be limited to these subjects,” Ms. Heller said.                                                                                            , She added: “WarnerMedia relying on this everyday practice as justification for dismissing Allison demonstrates how ignorant they are of journalistic practices, and further proves that her dismissal is nothing more than retaliation.”                                                                                                                                                      , CNN, whose slogan is “the most trusted name in news,” is facing mounting questions about how its senior executives and its top-rated anchor — Chris Cuomo, the governor’s younger brother — steered coverage of Governor Cuomo, who resigned last summer.                                                                                                                                     , In a memo to employees this week, Jason Kilar, the chief executive of WarnerMedia, which is CNN’s parent company, wrote that Ms. Gollust was resigning after the internal investigation found unspecified “violations of company policies, including CNN’s news standards and practices,” by her, Mr. Zucker and Chris Cuomo.                                                                 , Her resignation was the latest blow to CNN, which was already reeling in the wake of Mr. Zucker’s abrupt ouster two weeks earlier. Mr. Zucker said he was leaving because he had failed to disclose a romantic relationship with Ms. Gollust.                                                                                                                                                 , The internal review, conducted by the law firm of Cravath Swaine &amp; Moore, began last fall with an examination of allegations of workplace misconduct against Chris Cuomo.                                                                                                                                                                                                                     , Mr. Zucker fired Mr. Cuomo in December, days after the network received a letter claiming that Mr. Cuomo had years earlier sexually assaulted a woman and that he later offered to air a flattering CNN segment about her employer. The woman perceived that as an effort to buy her silence. Mr. Cuomo has denied the allegations.                                                           , Mr. Cuomo also came under fire for having closely advised his brother on how to fend off a sexual misconduct scandal that ultimately forced the governor to resign.                                                                                                                                                                                                                           , After Mr. Cuomo’s departure from CNN, the Cravath review took on a life of its own, and it quickly upended the news network.                                                                                                                                                                                                                                                                  , Investigators learned that Mr. Zucker and Ms. Gollust, who had worked closely together on and off for more than two decades, were having a romantic affair that had not been disclosed to human resources or other executives at WarnerMedia.                                                                                                                                                 , The Cravath investigators also uncovered extensive written communications between Governor Cuomo and Ms. Gollust, who had briefly worked for the governor in late 2012 and early 2013, the people said.                                                                                                                                                                                       , It wasn’t clear what all of those communications were about.                                                                                                                                                                                                                                                                                                                                  , But investigators found messages during the pandemic in which Governor Cuomo informed Ms. Gollust about three specific subjects that he wanted to be covered during a March 28, 2020, appearance at CNN, the people said.                                                                                                                                                                     , They said those topics included his recent phone conversation with Mr. Trump and the effect of New York’s being placed under lockdown.                                                                                                                                                                                                                                                        , Ms. Gollust then sent messages to CNN staff requesting that the governor be asked about those subjects.                                                                                                                                                                                                                                                                                       , The Cravath lawyers reviewed broadcast transcripts that showed that the anchor asked about the subjects that Ms. Gollust had put forward, the people said.                                                                                                                                                                                                                                    , Ms. Heller, the spokeswoman for Ms. Gollust, said that Ms. Gollust “acted as the principal booker for Governor Cuomo during the early days of the pandemic” and that her role was “well known by the entire network.”                                                                                                                                                                         , It was unclear whether Mr. Zucker knew that Ms. Gollust passed on Governor Cuomo’s request about interview topics.                                                                                                                                                                                                                                                                            , A spokesman for WarnerMedia referred The New York Times to the memo that the company sent to employees on Tuesday night.                                                                                                                                                                                                                                                                      , The back-to-back exits of Mr. Zucker and Ms. Gollust have raised questions about the future direction of CNN.                                                                                                                                                                                                                                                                                 , WarnerMedia, which is owned by AT&amp;T, is set to be spun off and merged with Discovery Inc. in the coming months.                                                                                                                                                                                                                                                                               , WarnerMedia has tried to keep a lid on the internal drama, initially remaining tight-lipped about the circumstances of Mr. Zucker’s departure and then issuing a short, vaguely worded memo on Tuesday night about Ms. Gollust’s departure and unspecified journalistic lapses.                                                                                                               , Even in conversations with CNN staff, executives and newsroom leaders have been mostly mum, to the mounting frustration of the network’s journalists and other employees.                                                                                                                                                                                                                     , In a pair of Zoom meetings on Wednesday with CNN employees, Michael Bass and Ken Jautz, who stepped in as two of the network’s interim leaders after Mr. Zucker’s departure, said Ms. Gollust had committed serious violations of the network’s journalistic standards, four people who attended the virtual meetings said.                                                                   , WarnerMedia’s top communications official, Christy Haubegger, also said in a staff meeting that Ms. Gollust’s transgressions had “to do with the Cuomos,” three people said.                                                                                                                                                                                                                  , When employees pressed for more details, Ms. Haubegger said she was barred from saying more.                                                                                                                                                                                                                                                                                                  , “Actions were taken to defend the institution and the brand,” she said on the call.                                                                                                                                                                                                                                                                                                           , Ms. Haubegger urged CNN’s public relations team to try to focus public attention on the network’s journalism, including its foreign correspondents in Ukraine covering that country’s brewing conflict with Russia.                                                                                                                                                                           , The internal investigation’s findings are especially notable because CNN journalists have repeatedly attacked Fox News personalities like Sean Hannity for having an overly close relationship with Republican leaders, in particular Mr. Trump.                                                                                                                                              , Mr. Trump, in turn, repeatedly accused CNN of being a mouthpiece for Democrats.                                                                                                                                                                                                                                                                                                               , James B. Stewart contributed reporting.                                                                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 06:02:00 </td>
   <td style="text-align:left;"> Toronto Stocks End Week on Bitter Note </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, closed 0.8% lower at a three-week low of 21,008 on Friday, the third straight decline, amid a broad risk aversion due to escalating tensions in Ukraine. All sectors ended lower save for consumer cyclicals, with healthcare and energy leading losses. Reports that citizens in the self-proclaimed Donetsk People’s Republic were evacuating the region raised alarms about an imminent Russian invasion. Meanwhile, preliminary data for January pointed to a 2.4% rebound in retail trade, from a 1.8% decline in December. Also, Ottawa’s police arrested 21 protesters, including three organizers of the “Freedom Convoy” movement in the city center and began towing trucks out of the streets to put an end to a three-week blockade in front of the Prime Ministers’ office and the Parliament. On the earnings front, Air Canada reported a smaller quarterly loss on recovering holiday travel. On a weekly basis, the index shed 2.4%, snapping three consecutive weeks of gains. </td>
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
       shed 168 points, or 1.2% Friday, while shedding 1.8% for the week. , Our call of the day rattles off some dangerous trends by investors, such as believing that a U.S. stock bias reduces risk.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Joy Wiltermuth is a news editor and senior markets reporter based in San Francisco. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 04:32:00 </td>
   <td style="text-align:left;"> US Stocks Fall for 2nd Straight Week </td>
   <td style="text-align:left;"> US stocks closed lower for the third straight session on Friday, notching a second consecutive losing week as escalating tensions between Russia and Ukraine and concerns about the Fed's next steps dominated the session. Russian media said a car exploded near a government building in separatist-controlled Donetsk, and civilians were ordered to evacuate, heightening fears that Russia is planning to invade Ukraine. Meanwhile, St. Louis Fed Bullard warned that inflation could get out of control without rate hikes and Fed Bank of Cleveland President Loretta Mester said she supports hiking rates faster if needed. On corporate updates, BoA analysts reiterated their “underperform” rating on Intel’s stock, while Roku shares plunged 22% after quarterly revenues missed expectations and issued weak guidance. The Dow lost 234 points, S&amp;P 500 was down 0.7%, and Nasdaq ended 1.2% lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/18/politics/trump-giuliani-swalwell-january-6-lawsuit/index.html </td>
   <td style="text-align:left;"> 2022-02-19 04:31:13 </td>
   <td style="text-align:left;"> Judge says Trump could be culpable for January 6 and says lawsuits against the former President can proceed - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Civil lawsuits seeking to hold Donald Trump accountable for the January 6, 2021, insurrection can move forward in court, a federal judge said Friday in a ruling outlining how the former President could conceivably be responsible for inciting the attack on the US Capitol.                                                                                                                                                                                                                                                                                      , Trump's statements to his supporters before the riot "is the essence of civil conspiracy," Judge Amit Mehta wrote in a 112-page opinion, because Trump spoke about himself and rallygoers working "towards a common goal" of fighting and walking down Pennsylvania Avenue.                                                                                                                                                                                                                                                                                                , "The President's January 6 Rally Speech can reasonably be viewed as a call for collective action," Mehta said.                                                                                                                                                                                                                                                                                                                                                                                                                                                             , RELATED: Trump's legal woes deepen and could bring new political trouble                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Democratic members of the House and police officers who defended the US Capitol on January 6 sued Trump last year, claiming he prompted his supporters to attack. Friday, Mehta wrote that the three lawsuits could move to the evidence-gathering phase and toward a trial -- a major loss in court for Trump.                                                                                                                                                                                                                                                            , "To deny a President immunity from civil damages is no small step. The court well understands the gravity of its decision. But the alleged facts of this case are without precedent," Mehta wrote.                                                                                                                                                                                                                                                                                                                                                                         , "After all, the President's actions here do not relate to his duties of faithfully executing the laws, conducting foreign affairs, commanding the armed forces, or managing the Executive Branch," Mehta added. "They entirely concern his efforts to remain in office for a second term. These are unofficial acts, so the separation-of-powers concerns that justify the President's broad immunity are not present here."                                                                                                                                               , While he homed in on Trump's legal liability, the judge ruled in favor of three close allies to Trump who also spoke at the rally on January 6 -- his attorney Rudy Giuliani, his son Donald Trump Jr. and Republican Rep. Mo Brooks, saying he would dismiss the claims against them.                                                                                                                                                                                                                                                                                     , When the Senate failed to convict Trump last year in the impeachment proceedings examining his role in the attack, Minority Leader Mitch McConnell -- who voted against convicting Trump -- noted that "civil litigation" was an avenue through which Trump's conduct could be addressed.                                                                                                                                                                                                                                                                                  , Two of the lawsuits were brought by Democratic House members, while a third was filed by Capitol Police officers.                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The lawmakers allege that they were threatened by Trump and others as part of a conspiracy to stop the congressional session that would certify the 2020 presidential election on January 6, 2021, according to the complaints. They argue that Trump should bear responsibility for directing the assaults.                                                                                                                                                                                                                                                               , Trump's legal team is likely to appeal the decision, which was made at the trial-level DC District Court. Representatives for Trump didn't immediately respond to requests for comment.                                                                                                                                                                                                                                                                                                                                                                                    , Mehta's ruling on what he calls a "one-of-a-kind case" sets up a rare instance where the former President could face concrete consequences for the insurrection.                                                                                                                                                                                                                                                                                                                                                                                                           , But Mehta's opinion, essentially melting away the protections of the presidency and the First Amendment because of the context of Trump's speech and specific words and actions that day, could have further implications, including creating a new avenue to subpoena Trump and ask him questions and establishing where immunity for presidents ends.                                                                                                                                                                                                                    , At this time, there are no public indications that the Justice Department's criminal investigation into January 6, which includes several sets of conspiracy charges and a sedition case, has reached Trump. And after Republican lawmakers blocked Trump's impeachment conviction, the GOP has largely fallen back in line behind the former President. The two House Republicans now serving on the committee to investigate the insurrection have faced calls for their ouster from the party, and Trump may very well be Republicans' 2024 nominee for the White House., The decision, Friday, however, sets in motion a path to the judge weighing the factual allegations and evidence against Trump in the cases as well as possible civil trials months or years from now, where Trump is at the defense table.                                                                                                                                                                                                                                                                                                                                 , Lawyers for the Democratic lawmakers and police were elated with the ruling Friday, though they likely face a long road of additional court tangles ahead.                                                                                                                                                                                                                                                                                                                                                                                                                 , "Today is a major victory for the rule of law, and demonstrates just how important the courts are for ensuring accountability," said Joseph Sellers, who represents a group of Democratic members of Congress that was first to allege a civil conspiracy against Trump in court.                                                                                                                                                                                                                                                                                          , The NAACP, working alongside Sellers, also applauded the ruling, and the group's president Derrick Johnson called for accountability for Trump and the right-wing groups.                                                                                                                                                                                                                                                                                                                                                                                                  , Matthew Kaiser, a lawyer for Democratic Rep. Eric Swalwell, called it a "great ruling" to potentially be able to take Trump to trial.                                                                                                                                                                                                                                                                                                                                                                                                                                      , And Patrick Malone, representing the police officers, called it a victory for democracy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , "It's good to see that no one is above the law. Everyone should be held accountable for their actions," Malone's client, the Capitol Police Officer James Blassingame Jr., said in a statement.                                                                                                                                                                                                                                                                                                                                                                            , Role of Proud Boys and Oath Keepers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Mehta wrote that it's plausible the lawsuit could prove Trump entered into an agreement with far-right groups the Proud Boys and the Oath Keepers, who are criminally charged for conspiracy and also named in the lawsuit.                                                                                                                                                                                                                                                                                                                                                , The judge noted how Trump told the Proud Boys to "stand back and stand by" at a debate before the election, and that he likely was aware of the Oath Keepers attending his rallies and of violence planned because of his election loss.                                                                                                                                                                                                                                                                                                                                   , "It is reasonable to infer that the President knew that these were militia groups and that they were prepared to partake in violence for him," the judge said. "The President thus plausibly would have known that a call for violence would be carried out by militia groups and other supporters."                                                                                                                                                                                                                                                                       , The cases will proceed against the Oath Keepers organization and against Enrique Tarrio, the recently incarcerated leader of the Proud Boys. They sought to get the case dismissed but the judge concluded that the allegations -- of a conspiracy between Trump and the extremist groups and leaders -- were plausible enough to allow the litigation to move forward.                                                                                                                                                                                                    , Partial victory for other Trump allies                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Some of his allies who were named as co-defendants succeeded in getting the civil suits against them dismissed.                                                                                                                                                                                                                                                                                                                                                                                                                                                            , This includes his eldest son and his former attorney, who were named as defendants in some of the cases, but successfully argued that the lawsuits should be thrown out.                                                                                                                                                                                                                                                                                                                                                                                                   , The judge indicated he would also eventually dismiss the case against Brooks, an Alabama Republican.                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , They have all denied wrongdoing related to January 6.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , In the ruling, Mehta said the case against Brooks was weak enough that he would simply dismiss it if he asked him to do so, teeing up the congressman for a victory.                                                                                                                                                                                                                                                                                                                                                                                                       , "Brooks's remarks on January 6th were political speech protected by the First Amendment for which he cannot be subject to liability," Mehta wrote.                                                                                                                                                                                                                                                                                                                                                                                                                         , But Mehta on Friday sidestepped the question of whether Brooks should have been protected in the litigation by the Justice Department -- because, according to the congressman, he was acting in his official duties as an elected official when he spoke at the Trump rally before the riot.                                                                                                                                                                                                                                                                              , The Justice Department so far has refused to protect Brooks, a revealing position for the agency that is conducting its own sweeping investigation of January 6.                                                                                                                                                                                                                                                                                                                                                                                                           , The Department argued that Brooks' role at the rally was "campaign activity" and not related to his official duties.  Still, Brooks had asked Mehta to rule that he was acting as a government official and thus shield him from liability. Mehta said on Friday he would defer deciding on that issue.                                                                                                                                                                                                                                                                    , Judge: Giuliani conspired to peddle disinformation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Regarding Giuliani, the judge said "there is little doubt" that he "was involved in a conspiracy" to peddle disinformation about the 2020 election -- but that he couldn't be held liable for the laws at issue in this lawsuit.                                                                                                                                                                                                                                                                                                                                           , Democrats and police officers who filed the lawsuits "fall short" of establishing that Giuliani directly conspired to stop Congress from certifying the election on January 6 by force or intimidation, Mehta ruled.                                                                                                                                                                                                                                                                                                                                                       , Even though Giuliani spoke at the "Save America" rally before the riot, and told the crowd, "Let's have trial by combat," the judge ruled that those comments weren't strong enough to establish a conspiracy.                                                                                                                                                                                                                                                                                                                                                             , "Critically, Giuliani uttered no words that resembled a call to action. 'Trial by combat' was not accompanied by a direction to do anything," Mehta wrote, calling it "constitutionally protected speech," and pointing out that Giuliani didn't know Trump would direct his supporters to march on the Capitol.                                                                                                                                                                                                                                                           , The judge said the allegations against Trump Jr. were even weaker, and thus should be dismissed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , "The allegations against Trump Jr. are insufficient to make him a co-conspirator in a plan to disrupt Congress from performing its duties," Mehta wrote.                                                                                                                                                                                                                                                                                                                                                                                                                   , That situation was much different than Trump's -- who not only spoke about the crowd marching to the Capitol and fighting, but also failed to tell his rioting supporters to stand down as the violence unfolded. Instead, Trump criticized then-Vice President Mike Pence, presiding over the electoral college certification, on Twitter, 12 minutes into the attack.                                                                                                                                                                                                    , "When the President said to the crowd at the end of his remarks, 'We fight. We fight like hell and if you don't fight like hell, you're not going to have a country anymore,' moments before instructing them to march to the Capitol, the President's speech plausibly crossed the line into unprotected territory," Mehta wrote.                                                                                                                                                                                                                                         , This story has been updated with additional details.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , CNN's Jessica Schneider and Paula Reid contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/e:us </td>
   <td style="text-align:left;"> 2022-02-19 04:17:17 </td>
   <td style="text-align:left;"> ENI earnings above expectations at 1.33 USD </td>
   <td style="text-align:left;"> ENI (E) released earnings per share at 1.33 USD, compared to market expectations of 1.30 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/18/politics/national-archives-trump-department-of-justice/index.html </td>
   <td style="text-align:left;"> 2022-02-19 04:02:50 </td>
   <td style="text-align:left;"> National Archives acknowledges it found classified documents in boxes taken from Mar-a-Lago - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)The National Archives acknowledged Friday it has discussed with the Department of Justice that classified records were found in boxes at Mar-a-Lago after former President Donald Trump left office, according to a letter from Archivist David Ferriero to the House Oversight Committee.                                                                                                                                                                                                                    , The letter, released by the Archives Friday, also provided more detail on reports that Trump tore up records after being warned not to while he was President. That letter is among four that the Archives released Friday portraying the agency, which acts as the historical library for the federal government, as concerned on multiple fronts about the Trump administration's record-keeping practices.                                                                                                       , The Archives arranged for the transport of about 15 boxes of records from Trump's Florida resort last month after the agency sought them from the former President's team.                                                                                                                                                                                                                                                                                                                                          , "NARA has identified items marked as classified national security information within the boxes," Ferriero wrote, responding to a question from the House. "Because NARA identified classified information in the boxes, NARA staff has been in communication with the Department of Justice."                                                                                                                                                                                                                       , The Justice Department did not immediately respond to a request for comment. CNN previously reported that the Archives had asked the Justice Department to investigate Trump's handling of White House records.                                                                                                                                                                                                                                                                                                     , The Archives said in the Friday letter that it is "in the process of inventorying the contents of the boxes." That process is expected to be complete by February 25, Ferriero wrote.                                                                                                                                                                                                                                                                                                                               , Social media records                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The Archives also said in letters to Congress Friday that some social media records and messaging on apps used by White House staff weren't properly kept as official documents despite previous warnings to Trump officials.                                                                                                                                                                                                                                                                                       , Among the missing records mentioned are those associated with Trump's personal Twitter account, including deleted tweets. Ferriero wrote that the Archives had previously raised concerns that Trump's deleted tweets were not being captured and was "informed by White House officials that they [were], in fact, doing so."                                                                                                                                                                                      , But since the end of the administration, the Archives said it has "learned that the White House initially used a manual process to capture tweets that were deleted from @realDonaldTrump and @POTUS," rather than the suggested automated process.                                                                                                                                                                                                                                                                 , "Accordingly, we were unable to obtain a complete set of these Presidential records from the Trump Administration or Twitter. While we do have access to copies of deleted tweets collected by other non-governmental sources, we do not consider them as official Presidential records and cannot ensure the completeness of their captured account data," the letter states.                                                                                                                                      , The Archives noted that it may not have a complete set of Trump tweets that would include tweets deleted from the @realDonaldTrump account between the time he took office and April 2020.                                                                                                                                                                                                                                                                                                                          , "I am advising you that the Trump Administration did not fully capture, and therefore NARA did not receive, all of the Presidential records created by President Trump and White House staff that were posted on social media platforms," Ferriero wrote in separate letters to the House Oversight Committee and the Senate Homeland Security and Governmental Affairs Committee on Friday.                                                                                                                        , The Archives also noted that it "identified seven Twitter accounts that we think contain presidential record information, but were not captured by the Trump Administration."                                                                                                                                                                                                                                                                                                                                       , "These accounts belonged to Andrew Giuliani, Chad Gilmartin, Ivanka Trump, Kayleigh McEnany, Kellyanne Conway, Mark Meadows, and Peter Navarro. After the end of the administration, NARA obtained the publicly available tweets from these accounts in order to supplement its archival collection," the letter says.                                                                                                                                                                                              , The Archives also has asked Trump's representatives to search for additional records that may be missing from the government's collection, according to the letter.                                                                                                                                                                                                                                                                                                                                                 , In 2018, the Archives had asked a lawyer at the White House for more information about media reports at the time that Trump was tearing up documents, and that White House staff would tape them back together.                                                                                                                                                                                                                                                                                                     , But the problem continued, the Archives told the House committee on Friday.                                                                                                                                                                                                                                                                                                                                                                                                                                         , "The White House Counsel's Office indicated that they would address the matter," Ferriero wrote. "After the end of the Trump Administration, NARA learned that additional paper records that had been torn up by former President Trump were included in the records transferred to us. Although White House staff during the Trump Administration recovered and taped together some of the torn-up records, a number of other torn-up records that were transferred had not been reconstructed by the White House.", New York Democratic Rep. Carolyn Maloney, chair of the House Oversight Committee, said a statement Friday that the Archives' acknowledgments only deepen her concerns about the Trump administration's record-keeping habits.                                                                                                                                                                                                                                                                                       , "In response to my inquiry, the National Archives has confirmed that they informed DOJ of former President Trump's removal of classified material to Mar-a-Lago and that they identified additional records torn up by Mr. Trump even after the White House was warned this could violate the law," Maloney wrote.                                                                                                                                                                                                  , "The National Archives also confirmed that potentially many more Trump Administration records, including direct messages sent by senior officials on multiple social media platforms, are missing.  These new revelations deepen my concern about former President Trump's flagrant disregard for federal records laws and the potential impact on our historical record," she added.                                                                                                                               , A pattern of behavior                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The issues that have arisen related to Trump's presidential records since he left office follow a pattern of behavior that preceded his presidency and continued during his four-year term.                                                                                                                                                                                                                                                                                                                         , Running afoul of normal preservation procedures, the then-President would often tear up documents, drafts and memos after reading them and is said to have also periodically flushed papers down the toilet in the White House residence -- only to be discovered later when repairmen were summoned to fix the clogged toilets. Trump previously denied the allegations.                                                                                                                                           , Other times, the former President would task aides with carrying boxes of unread memos, articles and tweet drafts aboard the presidential aircraft for him to review and then tear to shreds.                                                                                                                                                                                                                                                                                                                       , Trump's handling of records both inside the White House and after his presidency could come under intense legal scrutiny in the coming months as congressional investigators look into the records transfer initiated by the Archives, but experts don't believe he will face criminal charges. More could potentially come to light in a spate of books about the Trump White House that are due for release this year by former White House aides and journalists who closely covered the administration.         , This story has been updated with additional reporting Friday.                                                                                                                                                                                                                                                                                                                                                                                                                                                       , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/18/your-money/inflation-mortgage-rates.html </td>
   <td style="text-align:left;"> 2022-02-19 03:57:22 </td>
   <td style="text-align:left;"> Interest Rates Are Rising. What If You Want a House?  - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                , Your Money                                                                                                                                                                                                                                                                                                                                                                                                                                  , A strange set of (you guessed it, pandemic-influenced) circumstances makes this a tough market to assess. Here are four questions and answers that can help.                                                                                                                                                                                                                                                                                , By Ron Lieber                                                                                                                                                                                                                                                                                                                                                                                                                               , It’s what you think you want most in the world. It costs more than nearly anything else you’ll ever buy. The price may have risen over $50,000 last year. And now, here you are, trying to figure out what the machinations of the Federal Reserve might mean for you and your home purchase.                                                                                                                                               , That’s hard, and I’m sorry. If it’s any consolation, professional prognosticators don’t know what’s going to happen next, either.                                                                                                                                                                                                                                                                                                           , “We know every forecast will be wrong,” said Douglas G. Duncan, senior vice president and chief economist for Fannie Mae.                                                                                                                                                                                                                                                                                                                   , One thing seems certain: The Fed is planning to raise the rates that banks charge one another for short-term loans. That will increase borrowing costs for all kinds of loans — although mortgages aren’t as directly connected to those increases as others.                                                                                                                                                                               , The Fed’s goal is to tamp down overall inflation, but the weird circumstances caused by the pandemic mean the housing market might not obey.                                                                                                                                                                                                                                                                                                , That means you’ll have to be flexible. So start with the knowable.                                                                                                                                                                                                                                                                                                                                                                          , There were double-digit percentage price increases last year on what is now, at the median, a $408,000 collection of new gypsum and sticks. (It’s $350,000 for existing homes.) Mortgage rates have already risen more than a percentage point off their record lows. And sales have jumped to start the year as many buyers tried to lock in a more attractive rate than what might be available in just a few months.                     , Now take some deep breaths. You have questions about what this means. These answers should help.                                                                                                                                                                                                                                                                                                                                            , The Fed sure seems like it’s going to raise rates next month. What’s going to happen to mortgages?                                                                                                                                                                                                                                                                                                                                          , Mortgage interest rates will probably rise before the year is over, from their current level of 3.92 percent. But it’s not just Fed rate increases in play here. There is an unusual action that may come from the central bank that could drive an increase.                                                                                                                                                                               ,  The federal government owns enormous bundles of home mortgages that live inside bonds, which it bought in recent years to stabilize the housing market and the overall economy.                                                                                                                                                                                                                                                            , The housing market is more than fine now, and the Federal Reserve wants out of those bonds sooner rather than later. If it sells too many too fast, however, it could flood the market and force bond prices down.                                                                                                                                                                                                                          , At that point, bankers trying to package and sell new bundles of mortgages would need those new bonds to pay more to investors so they’ll buy them. And in order for those bonds to pay more, homeowners will need to be paying higher interest rates on their mortgages.                                                                                                                                                                   , That is one likely scenario where mortgage rates would rise further this year.                                                                                                                                                                                                                                                                                                                                                              , OK, so mortgage rates may rise some more. Won’t prices fall at that point? (Please?)                                                                                                                                                                                                                                                                                                                                                        , Well, prices stopped growing as quickly as they had been when rates rose for a bit in 2018. Does that help? That could happen this time, too.                                                                                                                                                                                                                                                                                               , But … it might not. When you ask people about what they plan to pay if mortgage rates rise, as Andreas Fuster and Basit Zafar did for a paper they published early last year, the responses seemed surprising. The researchers asked what the prospective buyers would be willing to pay if mortgage rates were 6.5 percent instead of 4.5 percent.                                                                                         , The respondents’ price target was only 5 percent lower, on average. Nearly half didn’t change their figure at all.                                                                                                                                                                                                                                                                                                                          , That’s a sign there could still be a lot of competition among buyers, even with higher mortgage rates. Then again, that survey took place before consumers were so antsy about inflation driving up the costs of day-to-day living.                                                                                                                                                                                                         , So you’re saying this time is different?                                                                                                                                                                                                                                                                                                                                                                                                    , Yes — and no. The facts always change, even if economic, stock and housing market cycles are regular (if not predictable or consistently timed) events over our lifetime.                                                                                                                                                                                                                                                                   , And, oh, what a set of facts we have. A pandemic and the government response resulted in many people spending less on travel, commuting, clothes, student loan payments and entertainment.                                                                                                                                                                                                                                                  , That put extra money in the down payment accounts of those who didn’t lose their jobs or any income. At the same time, the mortgage bundles the Fed was buying helped lead to record-low mortgage rates.                                                                                                                                                                                                                                    , That made it easier to bid up house prices — just as lots of people sped up moving plans in search of more space to work at home and keep kids out of their hair. There was even more competition for available homes, and new homes took longer to build because of supply chain issues and labor shortages.                                                                                                                               , There’s more. Professional investors were buying homes — with the all-cash bids that most sellers prefer and most individual owners can’t match — as never before in 2021. According to Redfin, they accounted for 18.4 percent of the home purchases in the fourth quarter of 2021. In Southern and Western cities — like Atlanta, Charlotte, Miami, Orlando, Las Vegas and Phoenix — investors accounted for more than a quarter of sales., These institutional buyers are probably not done, either.                                                                                                                                                                                                                                                                                                                                                                                   , “It’s an absolutely terrible time to be a buyer,” said Sarah Ponder, a financial planner in Austin, Texas. There, the median home price has risen 30 percent in the past year, according to the city’s Board of Realtors.                                                                                                                                                                                                                   , Ms. Ponder, who specializes in helping real estate professionals and has already done five property transactions of her own in just 15 years of adulthood, pointed to one final X-factor: Folks her age may not know what rapidly rising interest rates do to one’s home-buying psyche.                                                                                                                                                     , “I’m part of an entire generation of people that are accustomed to low rates,” she said. “If and when it normalizes to longer-term averages, then people my age will be relatively unhappy.”                                                                                                                                                                                                                                                , Is there any reason for me to rush to figure all of this out?                                                                                                                                                                                                                                                                                                                                                                               , No, even if there has been a spike in purchases lately.                                                                                                                                                                                                                                                                                                                                                                                     , Ms. Ponder isn’t necessarily advising people to sit this market out, though she would prefer that people not stretch themselves financially. Financial planners — and lenders — generally want people to spend no more than 35 percent or so of their income on total housing costs. Most people should resist the temptation to push those boundaries; Ms. Ponder generally wants her clients well below them.                             , And remember: Mortgage math in a higher-interest-rate environment may not be truly horrible as long as a bank will still give you a loan.                                                                                                                                                                                                                                                                                                   , A 30-year fixed-rate mortgage of $300,000 has a $1,432 monthly payment if the interest rate is 4 percent, near its current levels. At 6 percent — which, to be clear, would be the highest rate in more than 13 years — the payment would be $1,799. An extra $367 a month is hardly pocket change, but it’s a sum that many people may still be able to squeeze out of a budget.                                                           , Still nervous? It’s worth remembering that playing along is not a requirement. Being a renter is not a disqualifier for life satisfaction. And in some circumstances, buying a home in an environment like this is a recipe for regret.                                                                                                                                                                                                     , “The most important thing is to make sure that you’re willing to stay at least five years,” said Daryl Fairweather, Redfin’s chief economist. “Whatever happens in the market, you should gain enough equity where when you sell, you’ll come out ahead, even after paying fees.”                                                                                                                                                           , So maybe this isn’t a beware moment just yet. But it’s certainly a bewary one.                                                                                                                                                                                                                                                                                                                                                              , “What I worry about is people starting to act irrational when trying to compete for a home that they don’t actually like,” Dr. Fairweather said. “The worst case is that you buy it and end up selling it in a year. If the market’s down, you could be in a really precarious position.”                                                                                                                                                   , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/white-house-says-russia-blame/story.aspx?guid={D9856C48-BAD2-45A3-B776-C0A6E0C930DE}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-19 03:56:07 </td>
   <td style="text-align:left;"> White House says Russia to blame for cyberattacks on Ukraine - MarketWatch </td>
   <td style="text-align:left;"> A Biden administration official on Friday put the blame on Russia for a cyberattack that hit Ukrainian banks earlier this week. "We believe that the Russian government is responsible for widescale cyberattacks on Ukrainian banks this week," Deputy National Security Advisor for Cyber and Emerging Technology Anne Neuberger told reporters., Clinton campaign lawyer Sussman, seeking dismissal of indictment by Durham, says the William Barr–appointed special counsel has 'plainly intended to politicize this case, inflame media coverage and taint the jury pool.'                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                   , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-post-losses/story.aspx?guid={27AB5D94-5BD2-48D4-9F07-AFAB28DA424C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-19 03:53:32 </td>
   <td style="text-align:left;"> U.S. oil futures post losses for the session and week - MarketWatch </td>
   <td style="text-align:left;"> Oil futures declined on Friday, widening their weekly loss to more than 2%. A potential of Iranian crude to the market has led to some "nervousness ahead of the march towards $100 a barrel," leading oil prices to their first negative week since mid-December, said Michael Hewson, chief market analyst at CMC Markets UK. West Texas Intermediate crude for March delivery 
        CLH22,
        -0.11%
       fell 69 cents, or nearly 0.8%, to settle at $91.07 a barrel on the New York Mercantile Exchange. For the week, the front-month contract lost 2.2%, FactSet data show.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Abbott Laboratories undefined said late Thursday it is voluntarily recalling powder baby formulas, including its best-selling Similac, made in one plant in Michigan after it received four consumer complaints related to the bacteria Cronobacter sakazakii or Salmonella Newport in infants who had consumed powder infant formula made in the factory. "During testing in our Sturgis, Mich., facility, we found evidence of Cronobacter sakazakii in the plant in non-product contact areas. We found no evidence of Salmonella Newport. This investigation is ongoing," Abbott said. "Importantly, no distributed product has tested positive for the presence of either of these bacteria, and we continue to test." Despite detecting no pathogens, the company is recalling powder formulas manufactured in the plant with an expiration of April 1, 2022 or after, it said. The recall does not affect Abbott liquid formulas, powder formulas, or nutrition products from other facilities, Abbott said. "We're taking this action so parents know they can trust us to meet our high standards, as well as theirs. We deeply regret the concern and inconvenience this situation will cause parents, caregivers and health care professionals," said Joe Manning, executive VP of nutritional products. Shares of Abbott edged higher in the extended session Thursday after ending the regular trading day down 2.5%., Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/18/politics/liz-cheney-primary-republican-reactions/index.html </td>
   <td style="text-align:left;"> 2022-02-19 03:39:29 </td>
   <td style="text-align:left;"> Liz Cheney primary prompts sharp GOP divide in Washington - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Republican lawmakers are starting to choose sides in the fight to defeat Rep. Liz Cheney in Wyoming, placing high-stakes bets in a divisive primary that is widely seen as a referendum on Donald Trump and cementing deep rifts in the GOP over the direction of the party.                                                                                                                                                                                                                                                                                                            , In an extraordinary move on Thursday, House Minority Leader Kevin McCarthy -- who has been under pressure from his right flank to put his political muscle behind ousting Cheney -- officially endorsed her primary foe Harriet Hageman, who is backed by Trump. Less than 24 hours later, House GOP Conference Chairwoman Elise Stefanik of New York, the No. 3 Republican who replaced Cheney in leadership, also threw her weight behind Hageman.                                                                                                                                          , "House Republicans were ready for a change when I took over as Conference Chair, and it's resoundingly clear that Wyoming families are too," Stefanik said in a statement Friday. "Liz Cheney abandoned her constituents to become a Far-Left Pelosi puppet. Liz sadly belongs in an MSNBC or CNN news chair, not in Congress representing Wyoming — a state that voted for President Trump by over forty points."                                                                                                                                                                            , It's unclear if House Minority Whip Steve Scalise, the No. 2 House Republican, will follow suit and wade into the race; his office did not return a request for comment. Rep. Tom Emmer of Minnesota, the head of the House GOP's campaign arm, reiterated to CNN earlier this month that the committee has an official policy of staying neutral in primaries.                                                                                                                                                                                                                               , But the hardline House Freedom Caucus is expected to join in on the effort to unseat Cheney, and across the Capitol, longtime Cheney rival Sen. Rand Paul of Kentucky has already endorsed Hageman.                                                                                                                                                                                                                                                                                                                                                                                           , Cheney has her own share of congressional allies in her corner, including Sen. Mitt Romney of Utah, who will be a special guest at a Cheney fundraiser next month, as well as retiring Rep. Adam Kinzinger of Illinois, who launched a PAC dedicated to boosting anti-Trump Republicans.                                                                                                                                                                                                                                                                                                      , Meanwhile, Senate Minority Leader Mitch McConnell and Sen. Lindsey Graham of South Carolina both donated to Cheney's reelection campaign, before she drew a primary challenger but after she voted to impeach Trump for inciting the January 6 insurrection. And McConnell came to Cheney's defense earlier this month after the Republican National Committee voted to censure her and Kinzinger for their roles on the House select committee investigating the Capitol attack; McConnell also voiced support for Cheney amid the first conservative-led effort to boot her from leadership., While the McCarthy-Cheney feud has been simmering for more than a year, it's still remarkable for leaders to meddle in primaries -- especially one involving an incumbent. Not to mention, McCarthy and Cheney were onetime allies who served on the same leadership team. And it's especially unusual to see the GOP pour energy and resources into a seat that is all but guaranteed to stay red in November.                                                                                                                                                                               , But Cheney's primary, which will take place this August, has become a proxy war in the battle over Trumpism and will be viewed as an early test of whether the former President still has a strong grip on the GOP. That's why members from both wings of the party are feeling the need to pick sides in the fight and make rare endorsements in a primary involving their colleague.                                                                                                                                                                                                        , Yet it's also a gamble, especially for GOP leaders: If Cheney defeats Hageman and comes back to Congress, it would be a major blow to McCarthy and Trump's allies. And not everyone in the party wants to see leadership involved, with some Republicans worried it could further expose divisions in their party and potentially undermine their efforts to win back the majority in November.                                                                                                                                                                                               , Some Republican lawmakers also warn that nationalizing the race could backfire.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , "It's a mistake to make this primary a referendum on loyalty to Trump," said one senior GOP lawmaker.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Others expressed doubt that the fresh batch of endorsements coming out of DC would move the needle in Wyoming.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , "Not a big surprise and am not sure what Kevin's endorsement will mean in Wyoming but maybe an endorsement from Pelosi for Hageman might offset it?" said Rep. Fred Upton of Michigan, who also voted to impeach Trump. "At the end of the day it will be the voters, not the outsiders that influence the final result."                                                                                                                                                                                                                                                                     , Ousting Cheney has its political benefits                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Despite the potential risks, endorsing Cheney's challenger has some immediate political benefits for McCarthy. Members of the Freedom Caucus were pressuring McCarthy to take action against Cheney, but the GOP leader rejected calls to kick her and Kinzinger out of the conference. Instead, McCarthy has settled on a strategy of working to oust her from Congress entirely -- an easy way to win points with Trump's allies, who will be crucial in any future speaker's bid.                                                                                                          , Stefanik, too, has faced some skepticism from conservatives who were wary of her moderate record. While Stefanik said she won't seek the conference chair position again, she could make a play for a different leadership post or a committee gavel if they win the majority. Backing Hageman could further boost her standing with conservatives; Stefanik also has a history of playing in primaries to elect Republican women.                                                                                                                                                            , Their endorsements, which could come with campaign checks and fundraisers, could provide a much-needed boost to Hageman's campaign coffers. So far, Hageman has struggled to outraise Cheney, who brought in $2 million compared to Hageman's $443,000 haul last quarter.                                                                                                                                                                                                                                                                                                                     , Among Cheney's critics, there's also hope that Hageman's support from powerful members of Congress could help consolidate the primary field and force the remaining anti-Cheney GOP candidates to drop out.                                                                                                                                                                                                                                                                                                                                                                                   , But when it comes to voters in Wyoming, it's unclear how much sway -- if any -- these endorsements will have. In fact, Cheney's allies say it will now enable her to run as the outsider looking to take on the DC swamp.                                                                                                                                                                                                                                                                                                                                                                     , Since receiving McCarthy's endorsement, Hageman has signaled she would support him for speaker.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , "My priority is to restore Wyoming's lone Congressional seat to the people of Wyoming and to represent their interests.  I look forward to working with Speaker McCarthy next Congress to clean up Nancy Pelosi's mess and hold the Biden Administration accountable to the American people," Hageman said in a statement provided to CNN.                                                                                                                                                                                                                                                    , In a sign that the Trump wing is nervous about Cheney's chances of victory, Trump and his allies have been pressing Wyoming's governor to change the state's laws to prevent Democrats from being able to vote in the Republican primary.                                                                                                                                                                                                                                                                                                                                                     , Not everyone in the GOP agrees it's the right move.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , "Trump Jr and others are making a mistake with all these attempts to change the voting law in WY. Seems to me that could backfire in a state that has a strong identity of individualism," the senior GOP lawmaker said. "Their efforts would better be spent communicating with voters about why the other candidate is good and Cheney is bad. And helping the other candidate raise money so she can run her own race."                                                                                                                                                                    , </td>
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
        -0.06%
       fell $2.20, or 0.1%, to settle at $1,899.80 an ounce after touching a high at $1,905 - the highest intraday level for a most-active contract since June of last year, FactSet data show. For the week, prices were up 3.1%, FactSet data show., Institutional investors haven't held such a small position in tech shares in more than a decade, according to a survey by Bank of America.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
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
        -0.11%
       was down 43 cents, or 0.5%, at $91.33 a barrel on the New York Mercantile Exchange., Institutional investors haven't held such a small position in tech shares in more than a decade, according to a survey by Bank of America.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/robocalling-telemarketer-facing-45-million-fine-fcc </td>
   <td style="text-align:left;"> 2022-02-19 02:00:28 </td>
   <td style="text-align:left;"> 'Robocalling telemarketer' facing record $45 million fine from FCC </td>
   <td style="text-align:left;"> Robocalls spike                                                                                                                                                                                                                                                                                                                                                                   , The Federal Communications Commission has proposed slapping a Florida company with a record $45 million fine for allegedly placing hundreds of thousands of illegal robocalls, the agency announced Friday.                                                                                                                                                                       , A man uses a cell phone. (AP Photo/Jenny Kane / AP Newsroom)                                                                                                                                                                                                                                                                                                                      , TEXAS AG PAXTON INVESTIGATING CHINESE APP TIKTOK OVER HUMAN AND DRUG SMUGGLING POSTS                                                                                                                                                                                                                                                                                              , Florida-based lead generator Interstate Brokers, which also does business as National Health Agents, stands accused of making telemarketing robocalls to 514,196 cell phones and 271 landlines without recipients' consent, in violation of the Telephone Consumer Protection Act.                                                                                                , FCC investigators reviewed 10,000 calls as part of its probe and based its proposed fine on the verified calls. Many of the numbers dialed were on the federal Do Not Call Registry, according to the agency.                                                                                                                                                                     , The seal of the Federal Communications Commission (FCC) is seen before an FCC meeting in Washington. (AP Photo/Jacquelyn Martin, File / AP Newsroom)                                                                                                                                                                                                                              , JUSTICE DEPARTMENT PROBING SUPPLY-CHAIN DISRUPTIONS, TARGETING COMPANIES EXPLOITING THE CRISIS TO CHARGE MORE                                                                                                                                                                                                                                                                     , One of the pre-recorded calls stated, "Many states’ opened enrollment options to combat the COVID-19 virus and our plans include telemedicine services that would allow you to see a doctor over the phone or a video that could treat common sickness like the cold and flu.  Give me a call back, at our phone number … and I can go over what is still available in your area.", According to the FCC, when consumers answered the calls, they were transferred to a call center where they were offered insurance products.                                                                                                                                                                                                                                       , A man uses his smartphone. (Photo by Robert Alexander/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                       , Interstate Brokers will have the opportunity to respond to the agency's allegations and provide evidence to defend itself before the commission makes a final determination regarding the company's alleged violations or fines. Gregory Robbins, who runs the company according to the FCC, offered no comment when reached by FOX Business.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/federal-reserve-stock-trading-rules-ethics-scandal </td>
   <td style="text-align:left;"> 2022-02-19 01:53:43 </td>
   <td style="text-align:left;"> Fed adopts strict stock-trading rules for its officials after ethics scandal </td>
   <td style="text-align:left;"> BMO Capital Markets chief investment strategist Brian Belski discusses his market outlook.                                                                                                                                                                                                                                                                                                                                                          , The Federal Reserve on Friday adopted a set of strict restrictions on trading by policymakers and other senior staffers in the wake of an ethics scandal that led to the resignation of three top officials and threatened to undermine the public perception of the U.S. central bank.                                                                                                                                                             , Under the new rules, senior Fed officials are barred from buying individual stocks or holding investments in individual bonds, agency securities, cryptocurrencies or foreign currencies. They will also be required to provide 45 days of non-retractable notice for purchases and sales of approved securities, like mutual funds, as well as obtain prior approval for such transactions and agree to hold the investments for at least one year., FED SIGNALS 'FASTER' INTEREST RATE LIFTOFF LIKELY AS INFLATION SOARS                                                                                                                                                                                                                                                                                                                                                                                , Purchases and sales will be prohibited during periods of "heightened financial market stress."                                                                                                                                                                                                                                                                                                                                                      , The rules take effect at the beginning of May. Officials covered by the new guidelines will have until May 1, 2023 to dispose of all impermissible holdings.                                                                                                                                                                                                                                                                                        , Federal Reserve Board Chair Jerome Powell testifies before Senate Banking, Housing, and Urban Affairs hearing to examine the Semiannual Monetary Policy Report to Congress, Thursday, July 15, 2021, on Capitol Hill in Washington.  (AP Photo/Jose Luis Magana / AP Newsroom)                                                                                                                                                                      , "The rules, which were first announced in October 2021, aim to support public confidence in the impartiality and integrity of the Committee's work by guarding against even the appearance of any conflict of interest," a Fed news release accompanying the rules said. "The Federal Reserve expects that additional staff will become subject to all or parts of these rules after the completion of further review and analysis."                , The Fed put the new regulations in place after two top officials – Robert Kaplan, president of the Federal Reserve Bank of Dallas, and Eric Rosengren, president of the Federal Reserve Bank of Boston – resigned following revelations that they bought and sold stocks and real estate-tied assets in early 2020 as the central bank undertook aggressive policy action to bolster the economy at the start of the COVID-19 pandemic.             , The Fed's departing vice chair, Richard Clarida, came under scrutiny shortly after that over a New York Times report that revealed he failed to initially disclose the extent of a financial transaction he made in early 2020, suggesting that he was actively trading just days before Chairman Jerome Powell suggested the central bank may swoop in to prop up in the economy.                                                                  , A man wearing a mask walks past the U.S. Federal Reserve building in Washington D.C., the United States, on April 29, 2020.  (Xinhua/Liu Jie via Getty Images / Getty Images)                                                                                                                                                                                                                                                                       , In the wake of the trading scandal, Powell acknowledged the U.S. central bank's current rules dictating what its officials are allowed to invest in and trade are "not adequate" and need to be updated.                                                                                                                                                                                                                                            , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                         , The rules previously banned senior officials from owning bank stocks, limited trading around monetary policy meetings and warned against any activity that could suggest a conflict of interest.                                                                                                                                                                                                                                                    , Still, some lawmakers want to see the U.S. central bank go further in limiting any possibility of conflict-of-interest violations.                                                                                                                                                                                                                                                                                                                  , Sen. Elizabeth Warren, for instance, has called on the Securities and Exchange Commission to investigate the Fed officials' trading to determine if it violated insider trading rules and had previously asked the central bank to disclose all ethics communications provided to officials in 2020 and 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/18/business/retirement-planning-money-social-security-medicare.html </td>
   <td style="text-align:left;"> 2022-02-19 01:44:08 </td>
   <td style="text-align:left;"> How to Transition Into Retirement - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , retiring                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Many older Americans like to ease into being an ex-worker — but you need to think carefully about just how to get there.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , By John F. Wasik                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Pat Sterner, who runs her own business consulting for nonprofits in Duluth, Minn., would love to retire and spend more time kayaking on Lake Superior. In the summer, she says, her neighbors “are always knocking” on her door to get her out.                                                                                                                                                                                                                                                                                                                                                             , But even though she would like to take on fewer clients, she’s not quite ready to close shop. “My kids laugh and say, ‘Are you really retiring?’” said Ms. Sterner, 66. “It’s a little nerve-racking. I’d like to leave the door cracked open.”                                                                                                                                                                                                                                                                                                                                                             , Ms. Sterner’s concerns — about having enough money, leaving the business she built — mirror those of millions who are close, but not quite ready, for full-stop retirement.                                                                                                                                                                                                                                                                                                                                                                                                                                 , For many, getting to retirement age is not a simple matter of giving two weeks’ notice. You may want to extend a career or wind down work life or a business. If you’re able, you may want to keep working until you are 70 (and beyond), when you will receive the largest possible Social Security payment.                                                                                                                                                                                                                                                                                               , These in-betweeners are slow-walk planning to arrive at the moment when they are not working anymore. What’s involved is a delicate jigsaw puzzle of decisions, nest egg bolstering and financial calculations. This transitory time also presents a meaningful time for reflection and short-term planning.                                                                                                                                                                                                                                                                                                , Roughly 55 million Americans are 65 and older now, with those born at the peak of the baby boom hitting that milestone age this year. As a combination of the pandemic, job dislocation, inflation and higher medical costs continues to sting retirees, millions are staying in the work force while they transition to full retirement. Whether you’ve already chosen your quit date or are mulling your options, there are several issues to consider.                                                                                                                                                   , The age at which you take Social Security is crucial for tax and investment portfolio planning, so run some numbers on benefits at various ages. The good news is that you won’t be taxed with a Social Security “earnings penalty” if you’re working and take benefits on or after age 66½, which is, for most people, what the Social Security Administration calls the full retirement age. Of course, you can begin to draw benefits anytime after age 62, but the earlier you retire, the lower the monthly payment.                                                                                   , The administration looks backward at your best earnings years and forward to the age you’ll be taking them to calculate your monthly check. While many financial advisers counsel their clients to wait as long as they can to pull the Social Security trigger, only a handful do. Some 5 percent of people surveyed last year by the asset manager Schroders said they took Social Security at 70, when the highest possible benefit is paid. That often leaves a gap to fill.                                                                                                                            , Keep in mind that Social Security gets complicated when you’re considering spousal benefits, which generally are as much as half of the other beneficiary’s primary insurance amount, or the amount one would receive at full retirement age. You can apply for the spousal benefit beginning at 62, or you can wait to apply later for a higher benefit. It’s also possible to draw a higher payment based on your own lifetime earnings record. You’ll need to run some numbers to see how to best maximize payments. Divorced people, under certain circumstances, may also qualify for spousal benefits., You also need to do some Medicare planning before you turn 65. There are a number of programs to know about, so spend some time on medicare.gov. Also note that Medicare premiums are tiered — there are six levels — and based on income: The more you make, the higher the premium. Your tax filing status also matters in the pricing.                                                                                                                                                                                                                                                                   , Of course, none of the parts of Medicare provide 100 percent coverage, but you can buy Medicare supplemental insurance, known as Medigap, through private insurers. Premiums vary widely, depending on how much of your out-of-pocket expenses you want to cover, your age and whether you smoke. Medicare Advantage plans also may cover some out-of-pocket expenses.                                                                                                                                                                                                                                      , At the very least, estimate your benefits and out-of-pocket insurance costs at various ages. You need to balance maximizing Social Security and tapping other savings to get to your desired hard-stop retirement date. Another key factor when doing Social Security planning: your health and longevity. Those who can wait to collect until 70 are typically in relatively good health and not faced with serious chronic illness.                                                                                                                                                                       , “A strong consideration is your family history and longevity,” says Nicole Strbich, a certified financial planner with Buckingham Advisors in Dayton, Ohio. “We incorporate Medicare planning with clients as part of their retirement conversation. Understanding the timing needed to apply for benefits and the expected costs — the anticipated rate of inflation for those costs — and the increased costs for higher-income individuals, are important components of a retirement plan.”                                                                                                              , Once you’ve run some numbers on Social Security and Medicare, you can create a timeline. Your employer may even help you with “phased” retirement programs, in which you gradually reduce your hours until a certain year.                                                                                                                                                                                                                                                                                                                                                                                  , Responding to a long-running trend of employees working past age 65, these programs embrace those who are not ready to fully retire. Although the over-65 labor force participation rate changes from year to year, it’s around 19 percent, compared with a historical average of nearly 17 percent, according to Bureau of Labor Statistics data.                                                                                                                                                                                                                                                          , The reasons for delaying retirement are myriad. In many professions, improved longevity means being able to work longer. Many find meaning from work, so they want to continue. Others may need to save more as guaranteed defined-benefit pensions have become the exception and not the rule. Many workers simply want to take advantage of the additional amount of annual catch-up money they can save in 401(k)-style plans.                                                                                                                                                                           , While phased retirement programs are increasingly desirable in the workplace, they are also rare. Only about 15 percent of employers offer some kind of phased retirement, with about 6 percent offering a formal program, according to the Society of Human Resources Management, although you may be able to negotiate a phased plan on your own.                                                                                                                                                                                                                                                         , Planning is essential. One of the first items Ms. Sterner in Minnesota reviewed with Sam Brownell, a chartered financial analyst with Stratus Wealth Advisors in Kensington, Md., was her income and expenses. “What are my expenses and how might they change?” was one of the first questions they needed to answer, and she’s still trying to answer it.                                                                                                                                                                                                                                                 , On the income side, she also needed to know, based on her annual spending, how her reduced income may require withdrawals from her SEP-IRA, a retirement plan for the self-employed.                                                                                                                                                                                                                                                                                                                                                                                                                        , Mr. Brownell (who is also her nephew) said a decision to wait until 70 was important since you’ll need to “look at your cash flow during that time. The increase in the Social Security benefits depends on the individual’s year of birth,” he said. “For example, if you were born after 1943 and you delay your benefits to age 70, your annual increase is 8 percent per year.”                                                                                                                                                                                                                         , Another piece of the transition is tax planning. Withdrawals from defined-contribution plans like SEP-IRAs and 401(k)s are taxable on the federal level, while pulling money out of a Roth IRA is not — if you’re at least 59½ and have kept the money in the account for at least five years.                                                                                                                                                                                                                                                                                                              , There’s also a tax wrinkle down the road with defined-contribution plans: The Internal Revenue Service requires that most people start taking money out at age 72 in required minimum distributions. That rule, however, doesn’t apply to qualified Roth withdrawals.                                                                                                                                                                                                                                                                                                                                       , Converting a conventional IRA to a Roth, which will generate a one-time tax bill from the I.R.S., might be in order, depending upon your income. Mr. Brownell recommended that workers consider this move well before retirement to save taxes down the road.                                                                                                                                                                                                                                                                                                                                               , “Roth converts may be paying lower federal income tax in their ‘cutting back’ years,” he added. Because of the tax hit with a Roth conversion, you will need to talk with your tax or financial planner, or run numbers on an online calculator, to see if it makes sense for you.                                                                                                                                                                                                                                                                                                                          , You can, of course, manage the transition yourself or get some professional help. Finding a fee-only certified financial planner is a good start. It’s possible to find a planner who will work for a flat fee or hourly rate. Don’t hire anyone who wants to sell you investment products.                                                                                                                                                                                                                                                                                                                 , Hands down, increasing your nest egg during your in-between time is always a good idea. For 2022, you can contribute $20,500 to your 401(k) or other defined-contribution plans. That’s $1,000 more than last year. People over 50 can add $6,500 in catch-up contributions.                                                                                                                                                                                                                                                                                                                                , More important, one of your key questions should be, “What do I truly want to do and how do I get there?” Whether you are envisioning partial or full retirement, it helps to have some specific goals. For Ms. Sterner, one of those goals is having more time to engage with her local network. “I have worked nationally and internationally my entire career,” she said. “I am finding huge enjoyment volunteering in my local community.”                                                                                                                                                              , Ultimately, your quality of life is the biggest factor. In Ms. Sterner’s case, that involves “managing my finances, so instead of wrangling clients I can be wrangling lake trout from my kayak.”                                                                                                                                                                                                                                                                                                                                                                                                           , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-19 01:42:00 </td>
   <td style="text-align:left;"> US 10Y Treasury Note Yield Dips </td>
   <td style="text-align:left;"> The yield on the benchmark 10-year Treasury note fell to 1.92% on Friday, as fears of imminent war returned after reports that citizens in the self-proclaimed Donetsk People’s Republic were evacuating the region. Also, Russian media said a car exploded near a government building in Donetsk. Meanwhile, investors continued to digest the prospects of tightening Federal Reserve monetary policy. St. Louis Fed President James Bullard repeated his call for Fed's strong action and Fed Bank of Cleveland President Loretta Mester said she supports hiking rates faster if needed. On a weekly basis, the 10-year Treasury note is set to end flat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/hassett-russia-knows-its-going-to-bear-a-heavy-cost-imposed-on-them-by-the-ukrainians </td>
   <td style="text-align:left;"> 2022-02-19 01:38:20 </td>
   <td style="text-align:left;"> Hassett: Russia knows it's going to bear 'heavy cost' imposed on them by Ukraine </td>
   <td style="text-align:left;"> Hoover Institute distinguished visiting fellow Kevin Hassett argues Russia 'kind of knows that it's going to bear a heavy cost that's imposed on them by the Ukrainians.'                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Hoover Institute distinguished visiting fellow Kevin Hassett joined "Cavuto: Coast to Coast" Friday to discuss the potential economic fallout from the intensifying Russia-Ukraine conflict, arguing Putin knows the country is "going to bear a heavy cost" imposed on them by Ukraine.                                                                                                                                                                                                                                                                                                                                          , KEVIN HASSETT: I think that basically Russia kind of knows that it's going to bear a heavy cost that's imposed on them by the Ukrainians, but that the West has decided to just stand down and let them do whatever they want over there... Everybody wants sanctions on Russia, and then Russia turned off the natural gas to Europe. And, you know, all that kind of stuff, you know, would drive up energy prices and give us a big negative economic shock.                                                                                                                                                                   , RUSSIA-UKRAINE: KYIV DOWNPLAYS CONCERNS OF AN INVASION AS SHELLING RAMPS UP: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , I think it's clear that that's not going to happen. And that's really, you know, a big risk for the Ukrainians because, you know, the Western leaders have said, no, we're not going to let Russia attacking Ukraine upset our economy. And so I don't think that the big market moves that we've seen as Ukraine has gotten closer and closer to conflict. I don't think that those are a signal that there's going to be a big negative economic shock. In fact, we used to talk about this decoupling thing where, you know, foreign policy is decoupled from the economy, and I think that'll be evident in this one as well. , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , WATCH THE FULL INTERVIEW BELOW:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Hoover Institute distinguished visiting fellow Kevin Hassett discusses the economic impact of the Russia-Ukraine conflict and the U.S. combatting inflation. </td>
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
   <td style="text-align:left;"> , Federal Reserve officials won't be able to trade a slew of assets including stocks and bonds — as well as cryptocurrencies — under new rules that became formal Friday.                                                                                                                                                                                                                                                                                 , Following up on regulations announced in October, the policymaking Federal Open Market Committee announced that most of the restrictions will take effect May 1.                                                                                                                                                                                                                                                                                        , The rules will cover FOMC members, regional bank presidents and a raft of other officials including staff officers, bond desk managers and Fed employees who regularly attend board meetings. They also extend to spouses and minor children.                                                                                                                                                                                                           , "The Federal Reserve expects that additional staff will become subject to all or parts of these rules after the completion of further review and analysis," a release announcing the rules stated.                                                                                                                                                                                                                                                      , The rules "aim to support public confidence in the impartiality and integrity of the Committee's work by guarding against even the appearance of any conflict of interest," the statement also said.                                                                                                                                                                                                                                                    , Central bank officials acted after disclosures last year that several senior Fed officials had been trading individual stocks and stock funds just before the time the central bank adopted sweeping measures aimed at boosting the economy in the early days of the Covid spread.                                                                                                                                                                      , Regional presidents Eric Rosengren of Boston and Robert Kaplan left their positions following the controversy.                                                                                                                                                                                                                                                                                                                                          , The announcement Friday extended the ban to cryptocurrencies like bitcoin, which were not mentioned in the original announcement in October.                                                                                                                                                                                                                                                                                                            , Under the regulations, officials still holding market positions will still have 12 months to shed prohibited positions. New Fed officials will have six months to do so.                                                                                                                                                                                                                                                                                , In the future, officials covered by the new rules must give 45 days' notice before making any permissible asset purchases, a restriction that will go into effect July 1. They then will have to hold those positions for at least a year and will be banned from any trading during "periods of heightened financial market stress." There is no set definition of the term, which will be determined by the Fed chair and the board's general counsel., Along with stocks, bonds and crypto, the ban extends to commodities, foreign currencies, sector index funds, derivatives, short positions and agency securities or using margin debt to buy assets.                                                                                                                                                                                                                                                     , Congress has been debating a measure that also will restrict its members from owning individual stocks, though it has not been adopted yet.                                                                                                                                                                                                                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/goldman-sachs-ceo-braces-above/story.aspx?guid={35FAC385-ADB4-4A4B-9C5F-68B5DE23D606}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-19 01:27:29 </td>
   <td style="text-align:left;"> Goldman Sachs CEO braces for above trend inflation - MarketWatch </td>
   <td style="text-align:left;"> This replaces an earlier item that incorrectly reported where the comments were made. It has been corrected.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Goldman Sachs Group Inc. 
        GS,
        -0.87%
       CEO David Solomon on Thursday said 2022 will mark a shift from low interest rates and tame inflation to tighter borrowing conditions and above-trend inflation. In his remarks at the Credit Suisse Financial Services Forum, Solomon updated financial targets the firm had laid out at its investor day in 2020. The bank now expects to book $350 billion in inflows in its asset management and wealth management by 2024, up from its earlier target of $250 billion. The firm is projecting 14% to 16% return on equity, up from its earlier target of greater than 13%. It's projecting $225 billion in gross alternatives fundraising by 2024 and greater than $10 billion in firmwide management fees. Shares of Goldman Sachs fell 0.4%., The winners and losers aren't so clear, as transitioning to EVs is costly and complicated.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-19 01:03:59 </td>
   <td style="text-align:left;"> UK Stocks See Worst Week Since November </td>
   <td style="text-align:left;"> The FTSE 100 reversed course during the session to close 0.3% lower at a two-week low of 7,515 on Friday, in line with its European peers, as fears of imminent war returned after reports that citizens in the self-proclaimed Donetsk People’s Republic were evacuating the region. Also, Russian media said a car exploded near a government building in Donetsk. At the same time, storm Eunice triggered red warnings in England, with record gusts of wind in parts of the country that have ripped the roof of the O2 arena and left tens of thousands of homes without power. Losses were limited by upbeat retail sales in January and strong earnings from warehousing specialist Segro. Among the worst performers, NatWest Group shed 2.4% after the bank beat estimates but lowered its annual cost-cutting target for the next two years. On the week, the FTSE 100 lost 2%, its worst week since late November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/18/business/devendra-banhart-thao-nguyen-tenille-janae-musicians-covid.html </td>
   <td style="text-align:left;"> 2022-02-19 01:00:15 </td>
   <td style="text-align:left;"> Devendra Banhart, Thao Nguyen and Tenille Ja’Nae on Being a Musician During Covid - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                     , Supported by                                                                                      , scratch                                                                                           , By Julia Rothman and Shaina Feinberg                                                              , Julia Rothman is an illustrator. Shaina Feinberg is a writer and filmmaker. Both live in Brooklyn., Advertisement </td>
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
       were trading lower Friday as investors monitored developments between Russia and Ukraine, with investors harboring fears of a war breaking out., Clinton campaign lawyer Sussman, seeking dismissal of indictment by Durham, says the William Barr–appointed special counsel has 'plainly intended to politicize this case, inflame media coverage and taint the jury pool.'                                                                                                                                                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
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
   <td style="text-align:left;"> , Truth Social, the former president’s hard-right alternative to Twitter, could open its doors next month. But as businesses go, outrage may not be the best moneymaker.                                                                                                                                                                                                                                                                                                                                 , Credit...Matt Chase                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , By Matthew Goldstein and Ryan Mac                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , For months, former President Donald J. Trump has promoted Truth Social, the soon-to-be-released flagship app of his fledging social media company, as a platform where free speech can thrive without the constraints imposed by Big Tech.                                                                                                                                                                                                                                                             , At least seven other social media companies have promised to do the same.                                                                                                                                                                                                                                                                                                                                                                                                                              , Gettr, a right-wing alternative to Twitter founded last year by a former adviser to Mr. Trump, bills itself as a haven from censorship. That’s similar to Parler — essentially another Twitter clone backed by Rebekah Mercer, a big donor to the Republican Party. MeWe and CloutHub are similar to Facebook, but with the pitch that they promote speech without restraint.                                                                                                                          , Truth Social was supposed to go live on Presidents’ Day, but the start date was recently pushed to March, though a limited test version was unveiled recently. A full rollout could be hampered by a regulatory investigation into a proposed merger of its parent company, the Trump Media &amp; Technology Group, with a publicly traded blank-check company.                                                                                                                                            , If and when it does open its doors, Mr. Trump’s app will be the newest — and most conspicuous — entrant in the tightly packed universe of social media companies that have cropped up in recent years, promising to build a parallel internet after Twitter, Facebook, Google and other mainstream platforms began to crack down on hate speech.                                                                                                                                                       , Millions of users have signed up for these so-called alt-tech or alternative platforms, attracted by the promise of a space untethered by what they consider censorship of conservative voices. The business case for these companies, though, has already proved to be wobbly.                                                                                                                                                                                                                        , “There is an audience and a market, but it is not huge,” said Shannon McGregor, a professor of journalism and media at the University of North Carolina who has studied social media platforms. “Most people don’t want a version of the internet where anything goes.”                                                                                                                                                                                                                                , Most alt-tech start-ups are chasing the same pool of users, many of whom might spend just a fraction of their social media time on politically partisan causes. Also, right-wing pundits who draw big audiences already have large, well-established online fan bases on mainstream social media, making them unlikely to completely switch to a new platform unless they’ve been iced out.                                                                                                            , And since most traditional Silicon Valley investors aren’t rushing to fund alt-tech, these companies’ growth depends on the small group of financial backers who invest in partisan causes.                                                                                                                                                                                                                                                                                                            , Rumble, which was founded in 2013 to compete with YouTube and is the oldest of these alternative social media companies, recently reported that its revenue nearly tripled over the past year. Still, for the first nine months of 2021, its revenue was less than $7 million. By comparison, YouTube made close to $9 billion in advertising revenue in its most recent quarter.                                                                                                                      , Alternative platforms claim to have signed up tens of millions of users. User numbers for most of these companies — or how they define users — are hard to verify as they are not often independently tracked. But they are unlikely to pose a serious competitive challenge to mainstream social media platforms, which have billions of users, experts said. For instance, there are more than 1.9 billion daily active users of Facebook and 211 million daily active users on Twitter who see ads. , Many people who claim to crave a social network that caters to their political cause often aren’t ready to abandon Twitter or Facebook, said Weiai Xu, an assistant professor of communications at the University of Massachusetts-Amherst. So the big platforms remain important vehicles for “partisan users” to get their messages out, Mr. Xu said.                                                                                                                                                , Gettr, Parler and Rumble have relied on Twitter to announce the signing of a new right-wing personality or influencer. Parler, for instance, used Twitter to post a link to an announcement that Melania Trump, the former first lady, was making its platform her “social media home.”                                                                                                                                                                                                                , Alternative social media companies mainly thrive off politics, said Mark Weinstein, the founder of MeWe, a platform with 20 million registered users that has positioned itself as an option to Facebook.                                                                                                                                                                                                                                                                                              , “The problem with Truth Social, Gettr and Parler is these are Twitter competitors and they are echo chambers for a narrow political spectrum,” said Mr. Weinstein. “Echo chambers don’t have broad appeal.”                                                                                                                                                                                                                                                                                            , Rather than pursue users for their political beliefs, MeWe is aiming at people who want to protect the privacy of their online postings, Mr. Weinstein said. MeWe’s basic offering is free, but it charges for certain subscription services. His start-up has raised $24 million from 100 investors.                                                                                                                                                                                                  , But since political causes drive the most engagement for alternative social media, most other platforms are quick to embrace such opportunities. This month, CloutHub, which has just four million registered users, said its platform could be used to raise money for the protesting truckers of Ottawa.                                                                                                                                                                                             , Mr. Trump wasn’t far behind. “Facebook and Big Tech are seeking to destroy the Freedom Convoy of Truckers,” he said in a statement. (Meta, the parent company of Facebook, said it removed several groups associated with the convoy for violating their rules.)                                                                                                                                                                                                                                       , Trump Media, Mr. Trump added, would let the truckers “communicate freely on Truth Social when we launch — coming very soon!”                                                                                                                                                                                                                                                                                                                                                                           , Of all the alt-tech sites, Mr. Trump’s venture may have the best chance of success if it launches, not just because of the former president’s star power but also because of its financial heft. In September, Trump Media agreed to merge with Digital World Acquisition, a blank-check or special purpose acquisition company that raised $300 million. The two entities have raised $1 billion from 36 investors in a private placement.                                                            , But none of that money can be tapped until regulators wrap up their inquiry into whether Digital World flouted securities regulations in planning its merger with Trump Media. In the meantime, Trump Media, currently valued at more than $10 billion based on Digital World’s stock price, is trying to hire people to build its platform.                                                                                                                                                           , It has brought on recruiters to reach out to former employees of Parler, according to documents seen by The Times. In screening questions, the recruiters sought to learn more about “social media outlets pitched as alternatives to Facebook/Twitter, like Parler and Gab,” and asked candidates if they thought Truth Social would run into challenges making money or moderating content on its platform.                                                                                          , Devin Nunes, the former California Republican congressman whom Mr. Trump picked to serve as chief executive of his company, declined requests for an interview.                                                                                                                                                                                                                                                                                                                                        , Rumble, the Toronto-based YouTube rival, has raised a relatively large amount of money from investors, including Peter Thiel, the billionaire venture capitalist and Trump supporter, and the venture fund of Mr. Thiel’s protégé J.D. Vance, who is running for a Senate seat from Ohio.                                                                                                                                                                                                              , Rumble is also planning to go public through a merger with a special-purpose acquisition company. SPACs are shell companies created solely for the purpose of merging with an operating entity. The deal, arranged by the Wall Street firm Cantor Fitzgerald, will give Rumble $400 million in cash and a $2.1 billion valuation.                                                                                                                                                                      , The site said in January that it had 39 million monthly active users, up from two million two years ago. It has struck various content deals, including one to provide video and streaming services to Truth Social. Representatives for Rumble did not respond to requests for comment.                                                                                                                                                                                                               , At least one other social media start-up is hoping to ride the former president’s popularity among conservatives to build its business. Gettr, which began on July 4 and is led by Jason Miller, the former Trump adviser, had hoped to land Mr. Trump before he decided to open his own venture. In January, Gettr advertised that it was the “place to watch” recent rallies by Mr. Trump.                                                                                                           , In a written statement, Mr. Miller said the former president was welcome “to join GETTR whenever he is ready.” The site claims to have five million users and a cash pile of tens of millions of dollars. In a recent interview, Mr. Miller denied a previous claim that Gettr had raised $75 million.                                                                                                                                                                                                 , Parler, the platform popular with Trump supporters, is still reeling from its role after the violent protests at the U.S. Capitol in January 2021 by thousands of angry fans of Mr. Trump. Downloads of Parler’s app plummeted 88 percent last year after Apple and Google removed it from their app stores and Amazon cut off web services after the riot, according to SensorTower, a digital analytics company.                                                                                     , Parler, which said in January that it had raised $20 million from investors, has since returned to the Apple Store. However, internal turmoil has continued. Last year, Parler fired John Matze, one of its founders, from his position as chief executive. Mr. Matze has said he was dismissed after a dispute with Ms. Mercer — the daughter of a wealthy hedge fund executive who is Parler’s main backer — over how to deal with extreme content posted on the platform.                           , Christina Cravens, a spokeswoman for Parler,  said the company had always “prohibited violent and inciting content” and had invested in “content moderation best practices.”                                                                                                                                                                                                                                                                                                                           , Moderating content will also be a challenge for Truth Social, whose main star, Mr. Trump, has not been able to post messages since early 2021, when Twitter and Facebook kicked him off their platforms for inciting violence tied to the outcome of the 2020 presidential election.                                                                                                                                                                                                                   , With Mr. Trump as its main poster, it was unclear if Truth Social would grow past subscribers who sign up simply to read the former president’s missives, Mr. Matze said.                                                                                                                                                                                                                                                                                                                              , “Trump is building a community that will fight for something or whatever he stands for that day,” he said. “This is not social media for friends and family to share pictures.”                                                                                                                                                                                                                                                                                                                        , Advertisement </td>
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
       has lost 7.2%., The winners and losers aren't so clear, as transitioning to EVs is costly and complicated.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-02-18 23:37:21 </td>
   <td style="text-align:left;"> Natural Gas Futures Gain Momentum </td>
   <td style="text-align:left;"> US natural gas futures gained some momentum to rise above the flatline on Friday, trading close to $4.6 per million British thermal units, as investors continued to digest the latest EIA inventory data. Although last week’s draw came 3 billion cubic feet short (bcf) of expectations at 190 bcf, the shortfall between current storage levels and the five-year average widened to 11.6%. At the same time, the two-week weather outlook points to colder-than-usual temperatures to as late as the first days of March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/existing-home-sales-rebound-record-low-inventory </td>
   <td style="text-align:left;"> 2022-02-18 23:18:01 </td>
   <td style="text-align:left;"> Existing home sales rebound, leaving record-low inventory </td>
   <td style="text-align:left;"> Garman Homes founder and CEO Alaina Money Garman discusses the housing market and what homeowners are looking for as the supply chain crisis rages on.                                                                                                                                                             , Existing home sales increased by 6.7% in January after a decline the month before, leaving record-low inventory as prices continue to climb, according to the latest data from the National Association of Realtors.                                                                                               , Homes sales rebounded in January, leaving record-low inventory.  (AP Photo/Michael Conroy, File / AP Newsroom)                                                                                                                                                                                                     , Sales of previously occupied homes were up in all regions last month, reaching a seasonally adjusted annual rate of 6.5 million after falling in December. The rebound left a record-low inventory of 860,000 unsold units by the end of January.                                                                  , "The inventory of homes on the market remains woefully depleted, and in fact is currently at an all-time low," said Lawrence Yun, NAR’s chief economist.                                                                                                                                                           , HOUSING INFLATION, SUPPLY CHAIN CREATE BUILDERS' PERFECT STORM                                                                                                                                                                                                                                                     , Buyers were also willing to shell out more to make a deal last month, with sales prices surging 15.4% year-over-year to $350,300. Yun points to rising interest rates as the reason behind the trend.                                                                                                              , A sale pending sign is displayed outside a residential home for sale in East Derry, New Hampshire.  (AP Photo/Charles Krupa, File / AP Newsroom)                                                                                                                                                                   , "Buyers were likely anticipating further rate increases and locking-in at the low rates, and investors added to overall demand with all-cash offers," he said. "Consequently, housing prices continue to move solidly higher."                                                                                     , FED SIGNALS ‘FASTER’ INTEREST RATE HIKES LIKELY AS INFLATION SOARS TO 40-YEAR HIGH                                                                                                                                                                                                                                 , The average rate for a 30-year fixed-rate mortgage is approaching 4% according to Freddie Mac's latest weekly numbers, reaching 3.96% – a high not seen since May 2019. Rising rates are adding further fuel to the trend of would-be buyers increasingly being priced out of the market at the lower price points., Last month, the percentage of first-time buyers responsible for sales dropped to 27%, down from 30% in December and down from 33% in January the year before according to the NAR.                                                                                                                                 , A man walks past open house signs in front of condominiums for sale in Santa Monica, California. (REUTERS/Lucy Nicholson / Reuters Photos)                                                                                                                                                                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                        , "There are more listings at the upper end – homes priced above $500,000 – compared to a year ago, which should lead to less hurried decisions by some buyers," Yun explained. "Clearly, more supply is needed at the lower-end of the market in order to achieve more equitable distribution of housing wealth." </td>
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

, Roughly 16,000 borrowers who were scammed by their schools will have their federal student loans discharged, resulting in $415 million in relief.                                                                                                                                                                                                                                                                                                                                            , Jacob Passy is a personal-finance reporter for MarketWatch and is based in New York. </td>
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
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/amc-ceo-adam-aron-donate-stock-charity </td>
   <td style="text-align:left;"> 2022-02-18 22:51:15 </td>
   <td style="text-align:left;"> AMC CEO Adam Aron to donate $1M in stock to charity </td>
   <td style="text-align:left;"> Here are your FOX Business headlines.                                                                                                                                                                                                                                                                     , AMC Entertainment CEO Adam Aron has announced plans to donate $1 million worth of his currently owned shares in the movie theater chain to charity.                                                                                                                                                       , AMC CEO TOUTS PROGRESS AS TURNAROUND CONTINUES                                                                                                                                                                                                                                                            , "I benefited greatly as retail investors have embraced AMC. That makes it time for me to step up and personally give back," Aron tweeted Friday. "Therefore, over the coming weeks, I will give away $1 million of my currently owned AMC shares, to be spread over a number of well respected charities.", In a follow-up tweet, Aron asked AMC investors which charities they think he should support.                                                                                                                                                                                                              , "We all know Twitter can be a funny and sarcastic public square. But $1 million is a lot of money, and there are real charities in real need," he said. "Serious replies to a serious question please."                                                                                                   , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                   , The announcement comes after Aron sold more than $40 million worth of AMC stock for estate planning purposes under a previously disclosed 10b51 plan. After officially completing the sale in January, Aron tweeted that he still owned or planned to vest in more than 2.3 million AMC shares.           , As of the time of publication, AMC shares are down about 29% year-to-date.  </td>
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
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/manchin-undecided-biden-federal-reserve-nominees </td>
   <td style="text-align:left;"> 2022-02-18 21:57:17 </td>
   <td style="text-align:left;"> Manchin undecided on Biden Fed nominees, adding to uncertainty on confirmation </td>
   <td style="text-align:left;"> FOX Business’ Edward Lawrence reports from the White House on Biden’s spending bill.                                                                                                                                                                                                                                                                                                                                                                            , Sen. Joe Manchin remains undecided on whether to support President Biden's nominees for the Federal Reserve, including Sarah Bloom Raskin, the controversial pick for a top regulatory post at the central bank.                                                                                                                                                                                                                                                , The West Virginia Democrat – who has been a fierce critic of the Federal Reserve's monetary policy amid the highest inflation in 40 years – told Bloomberg News that he is still reviewing the candidates.                                                                                                                                                                                                                                                      , "We had a conversation, and we will have more conversations," Manchin said of Raskin, whom he met with earlier this week. "I made no decisions on anybody."                                                                                                                                                                                                                                                                                                     , REP. JAMIE RASKIN REFUSED TO DISCLOSE HUGE STOCK PAYOUT FOR HIS WIFE, A BIDEN FED NOMINEE                                                                                                                                                                                                                                                                                                                                                                       , Manchin serves as a critical vote in the 50-50 Senate – particularly for Raskin, who is facing fierce and united pushback from Republicans.                                                                                                                                                                                                                                                                                                                     , "We’re just basically looking and reviewing everything and talking to my good friends here about all the different concerns people have," he said of the GOP opposition to Raskin.                                                                                                                                                                                                                                                                              , Republicans, led by Sen. Pat Toomey of Pennsylvania, have skewered Raskin because of her past remarks on climate regulations, but boycotted a key vote on her nomination in the Senate Banking Committee earlier this week because of her ties to a Colorado-based fintech company that received a Federal Reserve master account while she served on its board.                                                                                                , Sen. Joe Manchin, D-W.Va. speaks to reporters before a caucus meeting with fellow Senate Democrats on Capitol Hill Jan. 18, 2022 in Washington, D.C.  (Drew Angerer/Getty Images / Getty Images)                                                                                                                                                                                                                                                                , "Important questions about Ms. Raskin’s use of the ‘revolving door’ remain unanswered largely because of her repeated disingenuousness with the Committee," Toomey said in a statement on Tuesday.                                                                                                                                                                                                                                                              , Reserve Trust is the only fintech to hold a Fed master account.                                                                                                                                                                                                                                                                                                                                                                                                 , Access to Federal Reserve services is sought after by many fintechs and other nontraditional financial services companies, because there are a number of benefits, including the ability to borrow from the Fed's discount window and to earn interest from deposits at the central bank. Without a master account, nonbank financial institutions must partner with banks insured by the Federal Deposit Insurance Corp. in order to tap those services.       , Reserve Trust had its master account application denied in June 2017; one year later, the application was approved. Toomey has noted that Raskin phoned Kansas City Fed President Esther George to advocate for the fintech company.                                                                                                                                                                                                                            , SARAH BLOOM RASKIN GRILLED OVER CONTROVERSIAL CLIMATE REGULATORY VIEWS                                                                                                                                                                                                                                                                                                                                                                                          , The Kansas City Fed claims that its reversal in 2018 was not the result of Raskin’s call, but rather that of Reserve Trust's changed business model "and the Colorado Division of Banking reinterpreted the state’s law in a manner that meant RTC met the definition of a depository institution," the Fed bank said last week.                                                                                                                                , Republicans, who say they want more time to vet Raskin, do not suggest that Raskin’s actions were illegal. Rather, they consider it an example of the "revolving door" between politics and corporate interests in which former government officials use their connections and clout in government to later lobby on behalf of businesses for a payout.                                                                                                         , Sarah Bloom Raskin, nominee to be vice chairman for supervision and a member of the Federal Reserve Board of Governors, speaks before a Senate Banking, Housing and Urban Affairs Committee confirmation hearing on Capitol Hill on Feb. 3, 2022 in Washin (Ken Cedeno-Pool/Getty Images / Getty Images)                                                                                                                                                        , As vice chair for supervision, Raskin – a Duke University law professor who has held high-level jobs at both the Treasury Department and the Fed – would oversee annual stress tests that review bank safety and liquidity. Her nomination has been welcomed by progressive senators and advocacy groups, who think she will take a tougher stance against Wall Street than her predecessor, Randal Quarles, a Trump nominee who stepped down in late December. , Raskin served on the Fed's board from 2010 to 2014 and was tapped by former President Obama to serve as assistant Treasury secretary.                                                                                                                                                                                                                                                                                                                           , Dennis Gingold, co-founder and former chairman of the Reserve Trust company, said in a statement to Bloomberg News last week that Raskin had "no role whatsoever" in appealing the Kansas City Fed’s initial denial of the firm’s request for a master account. He added that Raskin’s "conduct was appropriate, ethical and correct in every respect."                                                                                                         , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                         , Banking Chair Sherrod Brown, D-Ohio, has refused to separate Raskin’s nomination from Biden’s other Federal Reserve picks, including the renomination of Jerome Powell as chair. The White House has indicated that it does not plan to withdraw Raskin's nomination.                                                                                                                                                                                           , "Sarah Bloom Raskin is one of the most qualified people to ever be nominated to serve on the Board of Governors of the Federal Reserve," the White House said in a statement. "Despite her qualifications, Senators Pat Toomey and Cynthia Lummis over the last several weeks have lobbed unfounded and unfair attacks at Raskin related to her time on the Board of Directors of Reserve Trust." </td>
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
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/deere-lifts-profit-view-price-hikes-strong-farm-equipment-demand </td>
   <td style="text-align:left;"> 2022-02-18 20:24:37 </td>
   <td style="text-align:left;"> Deere lifts profit view on price hikes, strong farm equipment demand </td>
   <td style="text-align:left;"> Surevest CEO Rob Luna and Banrion Capital Management founder Shana Orczyk Sissel provide insight on investing in the stock market on 'Making Money.'                                                                                                             , Deere &amp; Co raised its annual profit forecast on Friday, as the world's largest farm equipment maker expects a boost to margins from price hikes and solid demand for its tractors and combines.                                                                  , Shares in the Moline, Illinois-based company were up 1.3% at $385.58 in light premarket trading.                                                                                                                                                                 , Record grain prices have put more cash in farmers' pockets and spurred them to increase investments in agricultural machinery amid a tight labor market. The U.S. Department of Agriculture estimated net farm income to have risen 25% to $23.9 billion in 2021., Deere raised prices to combat rising shipping and supply chain costs, but that has not deterred demand, with the company's North American order books full for most of its large farm equipment in 2022.                                                         , "Looking ahead, we expect demand for farm and construction equipment to continue benefiting from strong fundamentals," Chief Executive John May said in a statement.                                                                                             , Deere forecast fiscal 2022 net income between $6.7 billion and $7.1 billion, up from its prior expectation of $6.5 billion to $7.0 billion.                                                                                                                      , Net sales from equipment operations rose about 6% to $8.53 billion for the first quarter ended Jan. 30.                                                                                                                                                          , Net income fell to $903 million or $2.92 per share from $1.22 billion or $3.87 per share a year earlier, as costs weighed.                                                                                                                                       , (Reporting by Abhijith Ganapavaram in Bengaluru; Editing by Ramakrishnan M.) </td>
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
   <td style="text-align:left;"> Thousands of Porsche and Volkswagen cars have been abandoned on a cargo ship after it caught fire in the Atlantic Ocean en route to the US.                                                                                                 , The ship, named Felicity Ace, was travelling from Emden in Germany before it caught ablaze off the coast of Portugal's Azores islands.                                                                                                      , German newspaper Handelsblatt reported the vessel was carrying 3,965 vehicles, which also included Audis, Lamborghinis and a small number of Bentleys.                                                                                      , The ship's crew have been rescued.                                                                                                                                                                                                          , Portugal's navy said no one was hurt by the fire, which broke out on Wednesday, and the 22 crew members were taken to a hotel after the navy, four merchant ships sailing in the area and the Portuguese Air Force completed the evacuation., "The owner of the ship Felicity Ace is in contact with the logistic agent in order to draw up a plan for the towing of the ship," the navy said in a statement.                                                                             , "So far, no source of pollution has been recorded."                                                                                                                                                                                         , According to Handelsblatt, an internal email from Volkswagen USA stated that the ship was carrying 3,965 vehicles of the VW, Porsche, Audi and Lamborghini brands.                                                                          , Volkswagen did not confirm the number of cars on board, but Porsche said it had about 1,100 of its models on the ship.                                                                                                                      , The company said it was "aware of an incident involving a third-party cargo ship transporting Volkswagen Group vehicles across the Atlantic".                                                                                               , Bentley confirmed that 189 of its cars were also onboard the ship.                                                                                                                                                                          , "We are working with the shipping company to find out further information," said a spokesman.                                                                                                                                               , The ship was travelling to a Volkswagen factory in Davisville, Rhode Island, according to the website Marine Traffic.                                                                                                                       , One customer tweeted to say his Porsche was on board the abandoned ship.                                                                                                                                                                    , How one ship triggered a global crisis...                                                                                                                                                                                                   , How has Instagram become the dominant force it is today?                                                                                                                                                                                    , How did one man's mistake make history?                                                                                                                                                                                                     , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
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
   <td style="text-align:left;"> https://www.cnn.com/2022/02/18/world/storm-eunice-landfall-weather-climate-intl-gbr/index.html </td>
   <td style="text-align:left;"> 2022-02-18 19:41:31 </td>
   <td style="text-align:left;"> Storm Eunice blows off rooftops with highest wind speeds on record in England - CNN </td>
   <td style="text-align:left;"> (CNN)Storm Eunice tore down rooftops and trees, crushed cars and sent planes skidding on London's runways as millions of people across the United Kingdom hunkered down at home to stay out of hurricane-strength winds.                                                                                                                                 , The UK Met Office expanded its rare "danger-to-life" weather alert on Friday morning to include most of the south of England and some of Wales, before Eunice picked up speed, killing two people in England, with winds as high as 122 miles per hours (mph) -- the fastest on record in the country. High wind speeds is what make wind storms intense. , A woman was killed in north London's Muswell Hill on Friday after a tree fell on her car, according to a statement from the London Fire Brigade.                                                                                                                                                                                                          , A man in his 50s was also killed on Friday while driving his car in Liverpool, according to a press release from Merseyside Police.                                                                                                                                                                                                                       , In Ireland, which is also experiencing strong winds from Eunice, a man in his late 60s was killed after being hit by a falling tree, the national police service, known as the Gardaí, confirmed to CNN.                                                                                                                                                  , The man, who has not been named, died in County Wexford, southeastern Ireland, and was pronounced dead at the scene.                                                                                                                                                                                                                                      , The storm has wreaked havoc, damaging buildings.                                                                                                                                                                                                                                                                                                          , Footage shared to social media showed the roof of London's O2 arena severely damaged by strong wind.                                                                                                                                                                                                                                                      , Large sections of the fabric roof were shredded and ripped off by the gusts, while the building was evacuated and closed.                                                                                                                                                                                                                                 , On its website, the 02 said an event at the venue Friday night would be rescheduled.                                                                                                                                                                                                                                                                      , "The safety of our visitors remains of paramount importance, and we will continue to assess the ongoing situation and act accordingly," the statement said.                                                                                                                                                                                               , Elsewhere, a CNN reporter witnessed part of a rooftop flying off a home in the southwestern London area of Surbiton. The roof crushed a car parked on the street.                                                                                                                                                                                         , Social media video showed a building housing lifeboats with part of its rooftop blown off at Sennen beach in the country of Cornwall, where strong winds were pushing waves above a seawall. Police in Cornwall and neighboring Devon said they had received high volumes of calls about flying debris, collapsed roofs and fallen trees.                 , Other video footage shared on Twitter showed a church spire in Somerset collapsing in high winds.                                                                                                                                                                                                                                                         , Residents around the UK also posted images on social media of collapsed fences and trees in roads.                                                                                                                                                                                                                                                        , Many homes were also left without power on Friday, including small pockets of London and larger areas of southern England.                                                                                                                                                                                                                                , As dozens of flights were canceled across London's major airports, more than 200,000 people tuned in to watch a live stream on YouTube of planes landing at London's Heathrow. The aircraft were seen battling strong gusts as they came into land, some of them wobbling mid-air, others skidding from side to side once they hit the runway.            , The video, on the Big Jet TV channel, was accompanied by comical commentary by presenter Jerry Dyer, who kept viewers entertained by offering words of encouragement to the pilots, at one point saying: "Come on mate, you can do it!"                                                                                                                   , British Airways said it was grounding a number of planes and expected "significant disruption," but that most flights would go ahead as planned.                                                                                                                                                                                                          , "Safety is our number one priority, and we're canceling a number of flights," British Airways said in a statement.                                                                                                                                                                                                                                        , The airline said it was looking at deploying larger aircraft where possible to better withstand the weather.                                                                                                                                                                                                                                              , Rail companies have urged customers to reconsider their plans, with blanket speed restrictions in place for most lines across the country.                                                                                                                                                                                                                , In a statement Friday, Network Rail warned of high winds blowing trees and other debris onto railway lines, which then block trains and cause delays and cancelations.                                                                                                                                                                                    , Authorities are expecting gusts to cause travel delays, power cuts and possible mobile phone coverage outages throughout Friday.                                                                                                                                                                                                                          , A sting jet could hit                                                                                                                                                                                                                                                                                                                                     , Meteorologists have also raised the possibility of a sting jet, the weather phenomenon which made the 1987 Great Storm so destructive and deadly. Eighteen people were killed in that storm and 15 million trees were blown down in winds that topped 100 mph.                                                                                            , A sting jet is a very narrow and concentrated blast of powerful, upper-level winds that can form inside powerful weather systems. It descends to the the Earth's surface and can last a few hours, potentially causing damage to life and property, according to CNN meteorologist Derek Van Dam.                                                         , "The 'sting' refers to the cloud formation it creates, which resembles a scorpion's stinger," he said.                                                                                                                                                                                                                                                    , Eunice is the second storm in a week for the UK after Storm Dudley battered parts of Scotland, northern England and Northern Ireland Wednesday, leaving thousands of homes without power. Those homes have since been reconnected.                                                                                                                        , Hannah Cloke, professor of Hydrology at Britain's University of Reading, urged people to stay home where possible.                                                                                                                                                                                                                                        , She said people should not to take the red alert "lightly," as the winds were likely to uproot trees and roof tiles.                                                                                                                                                                                                                                      , "If you're hit by one of those you will be seriously hurt or killed. Wind that strong will sweep people and vehicles off streets, and topple electricity lines," she said.                                                                                                                                                                                , A climate connection?                                                                                                                                                                                                                                                                                                                                     , There is little to suggest any link between human-made climate change and the frequency and intensity -- or windspeeds -- of storms in northern Europe at current levels of global warming.                                                                                                                                                               , But damage from windstorms are still getting worse because the rainfall associated with them is becoming more intense, a trend that many scientific studies do link to climate change. Sea level rise also plays a role.                                                                                                                                  , "With more intense rainfall and higher sea levels as human-caused climate change continues to heat the planet, flooding from coastal storm surges and prolonged deluges will worse still further when these rare, explosive storms hit us in a warmer world," Richard Allan, a climate scientists at the University of Reading, said in a statement.      , The Intergovernmental Panel on Climate Change warns that if global temperatures rise by 2 degrees Celsius, compared with levels before industrialization, then northern Europe would start to see an increase in the frequency of severe windstorms.                                                                                                      , Temperature rise is currently at around 1.1 degrees Celsius, according to conservative estimates. The world is on track for warming well above 2C, according to an analysis, which looked at governments' plans to cut greenhouse gas emissions at the COP26 climate talks last year.                                                                     , </td>
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
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/18/business/us-approves-smart-headlights.html </td>
   <td style="text-align:left;"> 2022-02-18 19:00:07 </td>
   <td style="text-align:left;"> U.S. Approval of Smart Headlights Has a Catch: They Can’t Be Too Bright - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                           , Supported by                                                                                                                                                                                                                                                                                                                                                                                            , Wheels                                                                                                                                                                                                                                                                                                                                                                                                  , Adaptive beam headlights continually reshape the light they throw to avoid blinding oncoming drivers.                                                                                                                                                                                                                                                                                                   , By Eric A. Taub                                                                                                                                                                                                                                                                                                                                                                                         , The federal government this week approved the use of adaptive driving beam headlights, bringing the United States in line with a standard that has been in place around the world for decades.                                                                                                                                                                                                          , The light technology gives drivers the ability to essentially drive with their high beams on all the time, while the beam continually reshapes itself to avoid blinding oncoming drivers. The ruling came with a caveat, however: The lights will have to be dimmer than those used in Europe, for example, owing to a standard set in the United States in the 1970s.                                  , The approval, on Tuesday from the National Highway Traffic Safety Administration, was given 18 months sooner than required by a section in the recently passed infrastructure act.                                                                                                                                                                                                                      , A.D.B. headlights have been available in virtually every country except the United States, where separate high and low beams have been the required standard. Manufacturers will soon be able to offer these advanced headlight systems to American drivers as well.                                                                                                                                    , However, the A.D.B. system allowed by the federal agency will not be identical to those used in the rest of the world. While the infrastructure bill called for the standard approved by the Society of Automotive Engineers, which is similar to the system used in most other countries, the agency modified it, citing in its 326-page rule a Supreme Court decision that gave it the right to do so., The problem, according to one lighting expert, is that while U.S. vehicles can soon be equipped with headlamps that use dynamically reshaping high beams to prevent glare, their light output still cannot exceed the standard set in the 1970s, which is a fraction of the light intensity allowed globally.                                                                                           , “Adaptive driving beam technology in the rest of the world can increase seeing and reduce glare to a greater degree than what NHTSA has specified,” said Daniel Stern, chief editor of Driving Vision News, a technical journal about global vehicle lighting and driver assistance systems.                                                                                                            , “The U.S. has left in place an ancient cap on high-beam intensity from the late 1970s,” Mr. Stern said. “It’s a regulatory island.”                                                                                                                                                                                                                                                                     , Given the length of the report, few have had the opportunity to digest its contents. Both General Motors and the Society of Automotive Engineers have reserved judgment on the new smart headlight rules.                                                                                                                                                                                               , Nor do carmakers that have already included deactivated A.D.B. lights in their vehicles yet know how or if the lights will meet the new government standard.                                                                                                                                                                                                                                            , “We’re encouraged by the fact that the ruling was made,” said Mark Dahncke, director of communications for Audi of America. “Now we’re evaluating the impact on our existing and future lighting systems. We look to make A.D.B. lighting available to our customers as soon as we can.”                                                                                                                , Advertisement </td>
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
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 18:19:00 </td>
   <td style="text-align:left;"> Italian Stocks Trade Higher </td>
   <td style="text-align:left;"> The FTSE MIB Index was 0.3% higher to trade around the 26,680 level on Friday, as investors welcomed corporate earnings results while monitoring geopolitical developments regarding the Ukraine crisis ahead of next week’s meeting between the US Secretary of State and Russian Foreign Minister. On the corporate front, financial stocks rebounded from losses in the previous session, carried by Banco Bpm (2.4%) and Banca Generali (1.5%). Meanwhile, Eni traded 1.1% higher after posting an adjusted net profit of EUR 4.74 billion in 2021 compared to a EUR 0.758 billion loss in 2020 for its strongest year since 2012, largely due to the rise in oil and gas prices during 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-18 18:17:00 </td>
   <td style="text-align:left;"> Oil Extends Losses, Set for 1st Weekly Drop this Year </td>
   <td style="text-align:left;"> WTI crude futures extended losses to below $90 per barrel on Friday and were headed for their first weekly decline since the third week of December, as the prospect of Iranian oil returning to the market outweighed fears of possible supply disruptions from a Russia-Ukraine conflict. Reuters reported that a deal to revive the 2015 Iran nuclear deal is taking shape, with a draft accord outlining a sequence of steps that would eventually lead to granting waivers on oil sanctions, and bring about 1 million barrels a day of oil back to the market. Meanwhile, investors remain at the mercy of a volatile and tense standoff in Ukraine. Analysts expect oil to hold in the $90 to $100 a barrel range despite the potential return of Iranian oil exports, as geopolitical uncertainties and a tight global market, driven by capacity constraints and demand recovery continue to keep energy prices elevated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/current-account </td>
   <td style="text-align:left;"> 2022-02-18 18:12:18 </td>
   <td style="text-align:left;"> Italy Current Account Surplus Shrinks in December </td>
   <td style="text-align:left;"> Italy’s current account surplus narrowed to EUR 4.399 billion in December of 2021 from EUR 7.500 billion in the corresponding month of the previous year. The goods surplus shrank to EUR 1.845 billion from EUR 6.804 billion and the primary income surplus went down to EUR 3.393 billion from EUR 3.714 billion. Also, the services gap widened to EUR 1.388 billion from EUR 0.459 billion while the secondary income account swung to a EUR 0.548 billion surplus from a EUR 2.560 billion gap. Considering full 2021, the current account surplus fell to EUR 58.180 billion from EUR 62.084 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/construction-output </td>
   <td style="text-align:left;"> 2022-02-18 18:06:11 </td>
   <td style="text-align:left;"> Euro Area Construction Output Falls in December </td>
   <td style="text-align:left;"> Construction output in the Euro Area fell 3.9% year-on-year in December of 2021, following an upwardly revised 0.4% rise in November. It is the biggest decrease in the construction sector since February 2021 amid the spread of the omicron variant in the end of 2021. Building activity sank 4.6% while civil engineering edged 0.7% higher. Considering the last three months of 2021, construction declined 0.2%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/18/technology/china-olympics-propaganda.html </td>
   <td style="text-align:left;"> 2022-02-18 18:00:34 </td>
   <td style="text-align:left;"> How China Uses Bots and Fake Twitter Accounts to Shape the Olympics - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The country’s propagandists have used a variety of tools online to promote a vision of the Games that is free of rancor or controversy.                                                                                                                                                                                                                                                                                                                                                                           , By Steven Lee Myers, Paul Mozur and Jeff Kao                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , This article is published with ProPublica, the nonprofit investigative newsroom.                                                                                                                                                                                                                                                                                                                                                                                                                                  , BEIJING — Inside the Potemkin village of China’s propaganda, the Winter Olympics have unfolded as an unalloyed success, a celebration of sports and political harmony that has obscured — critics say whitewashed — the country’s flaws and rights abuses.                                                                                                                                                                                                                                                        , At Beijing 2022, the hills are snowy, not brown as usual this time of year. A Uyghur skier is the symbol of national unity, the tennis player Peng Shuai just a curious spectator. Athletes and foreign journalists praise the polite volunteers and marvel at the high-speed trains and the robots that boil dumplings and mix drinks.                                                                                                                                                                           , While China’s control of what its domestic viewers and readers consume is well established, the country has spread its own version of the Games beyond its borders, with an arsenal of digital tools that are giving China’s narrative arguably greater reach and more subtlety than ever before.                                                                                                                                                                                                                 , With bots, fake accounts, genuine influencers and other tools, China has been able to selectively edit how the events have appeared, even outside the country, promoting everything that bolsters the official, feel-good story about the Winter Olympics and trying to smother whatever doesn’t.                                                                                                                                                                                                                 , “For the Chinese Communist Party, the Winter Olympics are inseparable from the broader political goal of building up the country’s national image,” said David Bandurski, director of the China Media Project, a monitoring organization. Referring to the country’s leader, he added: “This is what Xi Jinping has called ‘telling China’s story well.’”                                                                                                                                                         , On Twitter, which is banned in China, Chinese state media outlets and journalists, as well as diplomats, have tried to buff the image of the Games, raving about venues and cooing over the Olympic mascot.                                                                                                                                                                                                                                                                                                       , China has also sought to influence online discussions in more concealed ways. The New York Times and ProPublica identified a network of more than 3,000 inauthentic-looking Twitter accounts that appeared to be coordinating to promote the Olympics by sharing state media posts with identical comments, for instance. Such accounts tended to be recently created with very few followers, tweeted mostly reposts and nothing of their own, and appeared to operate solely to amplify official Chinese voices., Some of their efforts have centered on an account called Spicy Panda, which has been posting cartoons and videos to push back against calls for a boycott of the Olympics. In one cartoon, Spicy Panda accused the United States of wielding “its deceiving propaganda weapon to stain the Olympics.”                                                                                                                                                                                                             , The tweet was reposted 281 times, all by the fake-looking accounts, but received little other engagement, a strong indication that the network was mobilized to promote the message. Aside from the bursts of promotion, Spicy Panda’s posts about the Olympics received almost no attention.                                                                                                                                                                                                                     , An analysis of Spicy Panda’s supporters turned up 861 accounts — 90 percent of which were created after Dec. 1. The accounts’ first wave of coordinated posts pushed Beijing’s stance that Hong Kong’s legislative council elections were legitimate, though critics have called the vote a sham. Then the accounts turned their attention to the Olympics. (By Thursday, all but one of the accounts had been suspended, shortly after The Times and ProPublica asked Twitter about them.)                       , Spicy Panda appears to have a connection with iChongqing, a state media-linked multimedia platform based in Chongqing, a city in central China. The accounts that shared Spicy Panda’s posts often did the same with tweets by iChongqing’s account. IChongqing did not immediately respond to a request for comment.                                                                                                                                                                                             , Other botlike accounts promoted hashtags that seemed aimed at drowning out criticism of China, a hallmark of previous campaigns.                                                                                                                                                                                                                                                                                                                                                                                  , They promoted content under hashtags like #Beijing2022 and #TogetherForASharedFuture, this year’s official Olympic motto. Some accounts repeatedly posted tweets with identical wording, such as: “China’s hosting of the #Beijing2022 as scheduled has boosted the world’s confidence in defeating the pandemic.”                                                                                                                                                                                                , Twitter said in an emailed statement that it had suspended hundreds of the accounts identified by The Times and ProPublica for violations of its platform manipulation and spam policies. It said it was continuing to investigate the accounts’ links to state-backed information operations.                                                                                                                                                                                                                    , Even the Games’ official mascot, Bing Dwen Dwen, a cuddly panda in a suit of ice, has been the subject of an organized campaign on Twitter, according to Albert Zhang, a researcher at the Australian Strategic Policy Institute’s International Cyber Policy Center.                                                                                                                                                                                                                                             , Thousands of new or previously inactive accounts have helped the mascot go viral, he said — which China’s state media presented as evidence of the mascot’s popularity and, by extension, that of the Games.                                                                                                                                                                                                                                                                                                      , “If you want to push out a lot of content on something like the Beijing Olympics, this is an easy way to do it,” Mr. Zhang said. He added that the campaign now underway was like others sponsored by the Chinese state to push Beijing’s narrative on topics such as Covid-19 and the crackdown on Uyghur Muslims in Xinjiang.                                                                                                                                                                                   , The information space inside China is not unlike the elaborate measures that have created the “closed loop” that keeps athletes, journalists and other participants strictly segregated from the general public.                                                                                                                                                                                                                                                                                                  , Inside the “closed loop” of official propaganda, the state carefully curates almost anything ordinary Chinese people see or read. The effect has been an Olympics free of scandal or criticism or bad news.                                                                                                                                                                                                                                                                                                       , When the United States men’s hockey team played an overmatched Chinese team, the game was not shown on the main state television sports channel, CCTV 5, and the 8-0 defeat was mentioned only glancingly in news reports. A state media slide show devoted to the men’s figure skating competition conspicuously omitted the gold medalist, Nathan Chen of the United States.                                                                                                                                    , In Chinese footage of the Games, the mountains where many competitions are being held have been deftly framed to exclude the dry, brown slopes in the background, until Day 8 when a snowstorm covered them in a frosting of white.                                                                                                                                                                                                                                                                               , One of the biggest political stories of these Games has also unfolded outside China’s internet firewall: the appearance of Peng Shuai, the professional tennis player and three-time Olympian who created a furor when she accused a senior Communist Party leader of sexually assaulting her.                                                                                                                                                                                                                    , The president of the International Olympic Committee, Thomas Bach, met her for dinner, as he promised he would when the global outcry over her fate threatened to overshadow the Games. Ms. Peng has appeared at curling and figure skating, among other events. None of that was shown inside China, where all references to her accusations have been erased, including later statements attributed to her, saying she had been misunderstood.                                                                  , “It’s absolutely critical to understand that this is not just another narrative,” Mr. Bandurski of the China Media Project said of the Olympics. “It’s a narrative that implies widespread censorship and the manipulation of public opinion, which is actually policy.”                                                                                                                                                                                                                                          , Jack Stubbs, vice president of intelligence at Graphika, a social media monitoring company, said his firm had observed another Chinese propaganda network using foreign social media platforms.                                                                                                                                                                                                                                                                                                                   , The network has spread videos emphasizing the Olympics as environmentally friendly and crooning about strengthening Chinese-Russian ties, punctuated by President Vladimir V. Putin’s attendance at the opening ceremony.                                                                                                                                                                                                                                                                                         , China has defended its use of Twitter and Facebook, platforms that it bans at home. A foreign ministry spokeswoman, Hua Chunying, said last year that such sites were an “extra channel” to combat negative portrayals in the West.                                                                                                                                                                                                                                                                               , One American company, Vippi Media, based in New Jersey, signed a $300,000 contract with the consulate general of China in New York to help promote the Games, according to the company’s filing with the Justice Department under the Foreign Agents Registration Act.                                                                                                                                                                                                                                            , Under the contract, first reported by the research group Open Secrets, the company has been promoting the Games by recruiting “social media stars” to post on Instagram, YouTube and TikTok, the company’s founder, Vipinder Jaswal, said in a telephone interview.                                                                                                                                                                                                                                               , “They were very clear and I was very clear that it’s about the Olympics and the Olympics only, nothing to do with politics,” he said.                                                                                                                                                                                                                                                                                                                                                                             , Once the Games began, the drama of the sports themselves dominated attention. Protests over China’s human rights record have not materialized, as some activists hoped. On the contrary, many athletes have heaped praise.                                                                                                                                                                                                                                                                                        , “When you really meet the people here and talk to them,” Jenise Spiteri, the American snowboarder competing for Malta, said in a state media interview, “everyone has a very good heart.”                                                                                                                                                                                                                                                                                                                         , Spicy Panda tweeted a state media report about another American competitor, the freestyle skier Aaron Blunck. In remarks posted by the official China Daily newspaper, Mr. Blunck praised China’s Covid protocols.                                                                                                                                                                                                                                                                                                , “#AaronBlunck revealed the real China that is totally different from what some American media have said!” Spicy Panda’s post read.                                                                                                                                                                                                                                                                                                                                                                                , Steven Lee Myers reported from Beijing, Paul Mozur from Seoul, and Jeff Kao from New York. Claire Fu and John Liu contributed research.                                                                                                                                                                                                                                                                                                                                                                           , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/18/business/china-coronavirus-vaccines.html </td>
   <td style="text-align:left;"> 2022-02-18 18:00:33 </td>
   <td style="text-align:left;"> Why China Doesn’t Have an mRNA Vaccine for Covid - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                            , Supported by                                                                                                                                                                                                                                                                                                                                                                             , Beijing once said it had two mRNA shots within reach and ready for approval — one homemade and one produced by a foreign company. Today, neither is available.                                                                                                                                                                                                                           , By Alexandra Stevenson                                                                                                                                                                                                                                                                                                                                                                   , China has done everything in its power to keep the virus outside its borders and protect its people — almost.                                                                                                                                                                                                                                                                            , It has kept cases and deaths remarkably low through a “zero-Covid” strategy that has involved tracking and tracing every case, closed its borders and locked down cities of millions of people. It fostered domestic vaccines that allowed the country to carry out a massive inoculation effort.                                                                                        , But two years into the pandemic, China’s 1.4 billion people still don’t have access to one of the most effective coronavirus vaccines the world has to offer. Those vaccines use the breakthrough mRNA technology that was developed and approved in the West, and they have been embraced by dozens of countries.                                                                       , The effectiveness of Chinese vaccines has been in doubt — partly because they use a century-old method for inoculation. Last spring, the country said it would approve BioNTech, the German mRNA shot made in partnership with Pfizer. Months later, China said that it was also close to producing its own mRNA vaccine. Neither are available today.                                   , China’s lack of an mRNA shot — and its delay in approving a viable foreign option — has poked holes in Beijing’s victorious pandemic narrative and prompted experts to question whether the country’s go-it-alone approach is less triumphant than officials would have the world believe.                                                                                               , Under Xi Jinping, China’s top leader, the country has turned more inward, promoting self-reliance and championing development in areas like semiconductors and other technology.  The delay in recognizing a foreign mRNA vaccine now appears to be a part of that deeply political exercise.                                                                                            , China is so committed to competing with the United States and the West on science and technology that some in the scientific community say it is hard to imagine that the state hasn’t pulled out all the stops to develop a homegrown mRNA vaccine. That China has fallen behind on that front, and failed to approve a readily available foreign option, has left many experts baffled., “We don’t know how decisions are made nowadays in China, but a better vaccine would definitely help in maintaining a zero-Covid policy,” said Jin Dongyan, a virologist at the University of Hong Kong who has urged his peers in mainland China to approve the BioNTech vaccine.                                                                                                        , “They are presenting to the world that they are doing well in vaccine development,” he said of officials in Beijing. “And it would be embarrassing for them to show the opposite to the Chinese people.”                                                                                                                                                                                 , China says its virus policies, which include strict lockdowns, have prevented millions of people from getting sick. But as a consequence, scientists say, the population has not built up enough natural immunity to help fight severe infection, making reliable vaccines even more crucial. And there is slowly mounting pressure on the country to pursue a new approach.             , In recent months, officials have begun openly discussing the need to introduce better vaccine technology. “We should learn about the good things in other countries, such as mRNA vaccines,” Zhong Nanshan, China’s top respiratory scientist, said at a conference in December. “They have spent years on the research and managed to develop mRNA vaccines in just a few months.”      , China last week approved for emergency use a Covid-19 pill made by Pfizer called Paxlovid, a move that some experts said could help change Beijing’s pandemic strategy.                                                                                                                                                                                                                  , It wasn’t that long ago that China appeared ready to introduce an mRNA vaccine for Covid-19. Shanghai Fosun Pharmaceutical, BioNTech’s Chinese partner, told investors last year that regulators would approve its mRNA vaccine for use in China by July 2021. The company, which had conducted clinical trials in late 2020, said that it could make as many as a billion doses a year. , That optimism has since faded. Chinese authorities now say they are still reviewing documents in order to “make a final decision on the approval of our vaccine,” a spokeswoman for BioNTech said.                                                                                                                                                                                       , Fosun did not respond to a request for comment.                                                                                                                                                                                                                                                                                                                                          , The approval process for Sinopharm and Sinovac — which manufacture the vaccines that are available in China — looked much different. Chinese regulators changed the rules to allow both Chinese drugmakers to submit their trial data behind schedule. Sinopharm’s vaccine was approved a week after the company filed its application, in December 2020.                                , Vaccines from Sinovac and Sinopharm help prevent hospitalization and death, but their ability to reduce transmission with variants such as Omicron is still in question. Sinovac has shown to be only 51 percent effective against preventing symptomatic disease, according to scientists in Brazil. The World Health Organization said Sinopharm has an efficacy of 78 percent.        , Though the W.H.O. has signed off on both Chinese vaccines for emergency use, most Western governments favor mRNA technology.                                                                                                                                                                                                                                                             , As approval for BioNTech languished, China said that it was close to producing a homegrown mRNA shot called ARCoVax. Two private drugmakers and China’s Academy of Military Medical Sciences said they were preparing to make 200 million doses by October, a Communist Party newspaper reported in September.                                                                           , Had that happened, it would have been a remarkable achievement for China.                                                                                                                                                                                                                                                                                                                , Unlike traditional vaccines that use an inactivated virus to trigger a response by the immune system, mRNA vaccines use a genetic molecule that assists cells to make proteins that can set off an immune response in the body. This response creates antibodies that are then used to fight the virus.                                                                                  , The virus in the U.S. ​​As new cases continue to drop, governors in Washington and New Mexico became the latest state leaders to ease mask rules. Hawaii remains the only U.S. state with mask requirements that has not yet announced plans to relax them.                                                                                                                                , Vaccines and boosters. Although new federal data suggests that the effectiveness of booster shots wanes after about four months, the Biden administration is not planning to recommend fourth doses of the coronavirus vaccine anytime soon.                                                                                                                                             , Around the world. Global cases are dropping, but the W.H.O. said it is watching an Omicron subvariant that is on the rise. For an upcoming presidential election in South Korea, voters with coronavirus will have a 90-minute window to cast their ballots at polling stations.                                                                                                         , The first mRNA vaccines for the coronavirus were based on research conducted over decades by scientists in different parts of the world. It took the Western pharmaceutical companies Pfizer, BioNTech and Moderna just over a year to take those advances and apply them to a new kind of vaccine able to prevent serious illness and death from Covid-19.                              , The final version of the mRNA vaccines produced by Pfizer and Moderna came together with the help of a multibillion dollar program under the Trump administration called Operation Warp Speed. The Food and Drug Administration determined in 2020 that the BioNTech vaccine has an efficacy rate of 95 percent.                                                                         , “This is not trivial technology,” said John P. Moore, a virologist at Weill Cornell Medicine. “So trying to reverse engineer it from scratch is one of those things where you ask, ‘What could possibly go wrong?’”                                                                                                                                                                      , If China is pursing a program similar to Operation Warp Speed, it has not said anything about it publicly. One of the private companies helping to develop ARCoVax is Suzhou Abogen, a start-up founded in 2019 by a scientist who used to work at Moderna. Before the pandemic, Abogen was developing mRNA drugs for cancer, one of China’s biggest epidemics.                          , The other drugmaker, Walvax, is a publicly listed pharmaceutical group. The two companies’ partnership with the Chinese Academy of Military Medical Sciences suggests strong government backing, though Beijing has not mentioned an official collaboration.                                                                                                                             , Last year, the United States added the Chinese Academy of Military Medical Sciences to an entity list, a federal trade restriction list, accusing it of using biotechnology to support activities like “brain control weaponry.” The designation would make it difficult to export any final vaccine product it develops.                                                                , Researchers recently published the details of an initial trial of the ARCoVax vaccine involving 120 volunteers. They found it to be safe, and said it produced a moderate level of antibodies but caused more side effects, like fever, than the BioNTech shot.                                                                                                                          , Abogen and Walvax did not respond to requests for comment. A senior executive at Walvax told Reuters last month that it had recruited 28,000 people for a large, Phase 3 clinical trial. ARCoVax is also being tested as a booster.                                                                                                                                                      , One recent study showed that two doses of Sinovac boosted with an mRNA shot offered strong antibody protection against both the Delta and Omicron variants. But it is still unclear when the ARCoVax vaccine will be available in China.                                                                                                                                                 , And as the weeks go by, approval for BioNTech seems to grow more elusive.                                                                                                                                                                                                                                                                                                                , “It’s very difficult to predict actually when we will get approval,” said Sean Marett, chief business and commercial officer of BioNTech, speaking at a health care conference last month. “But China remains for us an extremely important market,” he added. “We’re very, very committed to it.”                                                                                       , Cao Li contributed research.                                                                                                                                                                                                                                                                                                                                                             , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mongolia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-18 17:57:45 </td>
   <td style="text-align:left;"> Mongolia Inflation Rate Highest Since 2012 </td>
   <td style="text-align:left;"> Mongolia’s annual inflation rate advanced to 14.6 percent in January of 2022 from 13.4 percent in the previous month. It was the highest reading since October 2012, as prices climbed for food &amp; beverages (21.3 percent vs 20.4 percent in December); transport (21.1 percent vs 21.6 percent); hotels &amp; restaurants (19.6 percent vs 19 percent); housing &amp; utilities (15.8 percent vs 15.3 percent); clothing &amp; footwear (9.6 percent vs 6.6 percent); and alcohol &amp; tobacco (7.8 percent vs 6.9 percent). On a monthly basis, consumer prices increased 2 percent, following a 2.1 percent rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-02-18 17:53:08 </td>
   <td style="text-align:left;"> Gold Eases, Still Set for Third Weekly Gain </td>
   <td style="text-align:left;"> Gold prices consolidated around the $1,890 mark on Friday as fears of escalating tensions involving Nato, Russia, and Ukraine eased after the US said it agreed to meet Russia next week. Still, the precious was on track for a third weekly advance as the Ukraine crisis gave bullion bulls extra momentum. At the same time, less hawkish signals from US Federal Reserve's last meeting minutes underpinned gold. The central bank said it would not raise interest rates yet but indicated a hike is on the way as soon as March, but it failed to provide any hints on a 50-basis points rate increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovenia/consumer-confidence </td>
   <td style="text-align:left;"> 2022-02-18 17:44:00 </td>
   <td style="text-align:left;"> Slovenia Consumer Morale Improves to 5-Month High </td>
   <td style="text-align:left;"> The consumer confidence in Slovenia increased to -21 in February of 2022 from -24 in the previous month. Expectations over the next 12 months improved for the general economic situation in the country (-21 vs -29 in January); savings (-14 vs -16) and financial situation of the household (-14 vs -21). At the same time, consumers were less downbeat about unemployment (19 vs 20). Meanwhile, sentiment deteriorated for major purchases (-31 vs -28). Last year, the indicator was also at -21. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 17:38:39 </td>
   <td style="text-align:left;"> French Shares Rebound on Friday </td>
   <td style="text-align:left;"> The CAC 40 Index was 0.4% higher to hover around the 6,970 level on Friday, rebounding from two consecutive sessions in the red amid a batch of strong earnings results and hopes of de-escalation in geopolitical tensions as US Secretary of State Blinken agreed to meet with Russian Foreign Minister Lavrov next week. Renault shares traded 2.6% higher after the automaker posted an operating margin of 3.6% for 2021, already exceeding its target set for 2023. Consequently, the group increased its margin target to 4% for 2022, despite the ongoing global shortage of semiconductors that cut its production by 500,000 vehicles. At the same time, Teleperformance gained 6% after announcing reached its 2022 financial targets one year in advance. On the other hand, Hermes dropped 4.7% from reporting slower sales growth during the fourth quarter of 2021, mostly due to capacity constraints on its leather goods and saddlery divisions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/currency </td>
   <td style="text-align:left;"> 2022-02-18 17:38:30 </td>
   <td style="text-align:left;"> Indian Rupee Strengthens to Over 1-Week High </td>
   <td style="text-align:left;"> The Indian rupee strengthened towards 74.7 per USD tracking a pause in dollar rally and a retreat in crude oil prices amid hopes of easing Russia-Ukraine tensions. Meanwhile, on the domestic front, India’s producer inflation came at a 4-month low of 12.96% in January while its consumer inflation rose to a 7-month high of 6.01%, topping Central Bank’s upper target of 2-6%. However, the RBI said that such a high figure should not create any panic as it is mostly due to a base effect while maintaining the interest rate at 4% for the 10th time in a row to support economic recovery from the health crisis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-18 17:29:36 </td>
   <td style="text-align:left;"> Treasury Yields Steady as US and Russia Set to Meet </td>
   <td style="text-align:left;"> The yield on the benchmark 10-year Treasury note steadied at 1.97% to end the week, amid a general improvement in risk appetite after US secretary of state Antony Blinken agreed to meet with Russian foreign minister Sergei Lavrov next week, easing some concerns about escalating geopolitical risks. Meanwhile, investors continue to digest prospects of tightening Federal Reserve monetary policy. St. Louis Fed President James Bullard repeated his call for Fed's strong action and Fed Bank of Cleveland President Loretta Mester said she supports hiking rates faster if needed. The Fed is set to start raising the fed funds rate next month although it is still unclear whether it will deliver a 25bps or a 50bps increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/poland/wage-growth </td>
   <td style="text-align:left;"> 2022-02-18 17:26:41 </td>
   <td style="text-align:left;"> Polish Corporate Wages Growth Ease </td>
   <td style="text-align:left;"> Poland’s corporate sector wages climbed by 9.5 percent year-on-year to an average of PLN 6064.2 in January of 2022, easing from an 11.2 increase in the prior month and below expectations of a 10.1 rise. On a monthly basis, wages fell by 9.7 percent, as is typically observed in the first month of the year. The figure compares to a 10.3 percent increase on the month during December of 2021. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-02-19 08:52:18 UTC +8

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
   <td style="text-align:left;"> 2022-02-19 08:52:06 </td>
   <td style="text-align:left;"> $SPY People already criticize the US for being imperialistic, so what&amp;#39;s the harm in actually doing it? I&amp;#39;ve never seen the value in allowing foreigners to have sovereign nations, we could literally have all of it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:51:54 </td>
   <td style="text-align:left;"> $SPY Legit still have a headache from how stressful trading was today

Time to hit the bars and relieve that stress

😎😎📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:51:49 </td>
   <td style="text-align:left;"> $SPY Instead of relying on &amp;quot;intelligence&amp;quot; based on reporters, why doesn&amp;#39;t Biden just pick up that phone and call Putin?   
Biden: Hey Putin, you attacking or what? 
Putin: I keep saying I&amp;#39;m not!  Unlike you, I&amp;#39;m protecting my border with MY military.  What about you? 
Biden:  Oh, we already lost war against Mexico.  They own our border.  
$UVXY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:51:34 </td>
   <td style="text-align:left;"> $SPY it seems Brandon is nostradumbass now, predicting hour of attack? See you on Tuesday, squeeze time 8 30am. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:51:28 </td>
   <td style="text-align:left;"> $SPY down almost as much in ah, than today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:51:04 </td>
   <td style="text-align:left;"> $SPY This dumpster fire better hold support or else. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:51:03 </td>
   <td style="text-align:left;"> $SPY need one more good pump so I can load puts on other stocks 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:50:54 </td>
   <td style="text-align:left;"> $SPY remember folks markets have two components, the P and the E. The E is doing fine, the P is what’s normalizing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:50:52 </td>
   <td style="text-align:left;"> $SPY Murderous cop of George Floyd got Biden elected and got the weakest prez ever. Horrible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:50:03 </td>
   <td style="text-align:left;"> $SPY 🔥🔥 Daily update on Russia invasion of Ukraine will eventually decay shock value when shit hits the fan. At this rate de-escalation will be more shocking - immediately prompting super V rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:49:44 </td>
   <td style="text-align:left;"> $SPY Not looking good, dumping all the way to the support line. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:49:35 </td>
   <td style="text-align:left;"> $SPY 3 day weekends suck I already feel the withdrawl. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:49:32 </td>
   <td style="text-align:left;"> $SPY EXAMPLE #3 OF NEW STOCKTWITS ACCOUNTABILITY BOT (SEE MY PROFILE FOR MORE INFO): 
 
stocksTrade4profits: 2022-02-11T16:01:21Z: $SPY buy the dip 
stocksTrade4profits: 2022-02-11T20:00:59Z: $SPY buy the dip 💎🚀🚀🚀 
stocksTrade4profits: 2022-02-14T17:30:34Z: $SPY buy the dips. 448 next target 
stocksTrade4profits: 2022-02-14T18:24:14Z: $SPY short it. I will buy the dip 💎💎💎 
stocksTrade4profits: 2022-02-14T19:17:23Z: $SPY buy the dip 🚀🚀 
stocksTrade4profits: 2022-02-15T01:25:57Z: $SPY keep shorting more 😂. I will buy the dip 🚀🚀🚀 
stocksTrade4profits: 2022-02-15T14:36:21Z: $SPY buy the dips here if any 
stocksTrade4profits: 2022-02-17T12:10:58Z: $SPY buy the dip.  Added few here 🚀🚀 
stocksTrade4profits: 2022-02-17T20:17:15Z: $SPY low volume sell off.   Buy the dip 💎🚀 
stocksTrade4profits: 2022-02-17T21:30:16Z: $SPY buy the dip 💎💎 
stocksTrade4profits: 2022-02-18T16:24:34Z: $SPY buy the dip 🚀🚀💎💎 
 
YIKES!!!!! DO NOT LISTEN TO THIS IDIOT! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:49:03 </td>
   <td style="text-align:left;"> $SPY the fun part… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:48:58 </td>
   <td style="text-align:left;"> $SPY I think problem with Eternals is it was more just social commentary than an actual superhero movie.  Like it took itself so seriously. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:48:38 </td>
   <td style="text-align:left;"> Also, I&amp;#39;m still waiting to see those weapons of mass destruction from 2003   $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:48:09 </td>
   <td style="text-align:left;"> $SPY In fact, when Trump tried to stop the Nordstream 2 pipeline, Germany&amp;#39;s Angela Merkel told him to stay out of their business.  Trump argued that the pipeline would give Russia too much political power in the region (because it would result in Russia providing the equivalent of nearly 80% of EU&amp;#39;s energy supply). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:47:42 </td>
   <td style="text-align:left;"> $SPY FUTES RIPPING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:47:41 </td>
   <td style="text-align:left;"> $SPY &amp;quot;Getting along with Russia is a good thing, not a bad thing.&amp;quot;  - President Donald J. Trump 
 
Man, I miss having a real, effective, competent, legitimate President. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:47:31 </td>
   <td style="text-align:left;"> $SPY index down 30$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:47:28 </td>
   <td style="text-align:left;"> $SPY i advise biden to send in all US troops for a suicide mission and invade russia and take out putin. This is the best option to lower inflation. Reset economy. Reset houses. Reset bonds and we start over. Fresh start without retail pigs. Hunter will lead the army front lines into russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:47:23 </td>
   <td style="text-align:left;"> $SPY Canadians and Americans who are upset with their governments need simply stop go to the bank, withdraw all their money, and spend just 1 week without working and without spending any money. When enough people choose to pause their participation in a society that is crushing them, they can crush it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:47:21 </td>
   <td style="text-align:left;"> $SPY $DWAC …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:47:19 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:47:12 </td>
   <td style="text-align:left;"> $SPY lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:47:08 </td>
   <td style="text-align:left;"> $SPY nice AH action. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:47:04 </td>
   <td style="text-align:left;"> $SPY Sub 400 plz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:46:29 </td>
   <td style="text-align:left;"> $SPY Notice how you don&amp;#39;t see Germany pounding their fists at Putin in front of a microphone and cameras. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:46:28 </td>
   <td style="text-align:left;"> $SPY if you do taxes now, how soon can we get our money? i need money. lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:46:19 </td>
   <td style="text-align:left;"> $SPY oh I had over hundred puts for this week.  And 5 digits in put spreads.  And yeah. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:46:08 </td>
   <td style="text-align:left;"> $SPY 2022 WILL REPEAT THIS !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:46:06 </td>
   <td style="text-align:left;"> $SPY - 97% off all board here acting like they are The new Michael Burry, predicting a major crash. 

Now Think about it😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:45:43 </td>
   <td style="text-align:left;"> $SPY damn who bought into the 3 days weekend lol? Are you able to enjoy the weekend? Lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:45:26 </td>
   <td style="text-align:left;"> $SPY So does this mean we aren’t getting the COVID tests Biden demanded back in December ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:45:21 </td>
   <td style="text-align:left;"> $SPY Hope bulls sold to save their remaining monies, more torture next week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:45:06 </td>
   <td style="text-align:left;"> $SPY I need another superhero movie to watch.  Eternals sucked.  Rewatched iron man 1.  Ridiculously good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:44:43 </td>
   <td style="text-align:left;"> $SPY Russia accounted for 26.9 percent of European Union crude oil imports and 41.1 percent of the natural gas imports in 2019, the last pre-pandemic year, Eurostat data shows. Russia is the single largest supplier of oil, the fuel most used in the EU&amp;#39;s final energy consumption </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:44:41 </td>
   <td style="text-align:left;"> $SPY Putin wants his bitch back (AKA) Trump 😂😂😂🖕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:44:39 </td>
   <td style="text-align:left;"> $SPY Last time MACD crossed over on monthly was March 2020.. make your own decision </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:44:24 </td>
   <td style="text-align:left;"> $SPY people going to start dying real soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:44:17 </td>
   <td style="text-align:left;"> $SPY peeps it&amp;#39;s the start to the weekend. Get the fuck off the screen and enjoy your time with the fam.  
 
By the way futures dont mean shit till  1 hour before market open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:44:12 </td>
   <td style="text-align:left;"> $SPY Gap up Monday when everyone realizes nobody gives a sh$t about some eastern Europe country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:44:07 </td>
   <td style="text-align:left;"> $SPY Been a busy week for me family! Will be back on  Tuesday in full force. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:44:05 </td>
   <td style="text-align:left;"> $SPY What’s the Chances Trump 
Wins in 2024? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:44:03 </td>
   <td style="text-align:left;"> $SPY Wonder how much Putin is paying the US government contractor IT guy to spy on the Biden White House.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:44:00 </td>
   <td style="text-align:left;"> $SPY DCA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:43:59 </td>
   <td style="text-align:left;"> $SPY Got some PUTS to hold over the weekend. Going to….. P-P-P- PRINT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:43:56 </td>
   <td style="text-align:left;"> $SPY What if Biden, Putin, and Ukraine are working together to get cheap stocks? What if we are all being played? What if there aren&amp;#39;t any soldiers at the border at all? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:43:50 </td>
   <td style="text-align:left;"> $SPY
Sellin rips. You&amp;#39;ll know when I&amp;#39;m done.

 https://youtu.be/7YvAYIJSSZY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:43:43 </td>
   <td style="text-align:left;"> $SPY  live look at the current market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:43:42 </td>
   <td style="text-align:left;"> $SPY $JNJ $PFE $MRNA  ain&amp;#39;t wrong &amp;quot;Canadians are too good natured. you were perfect victims for tyranny. The truckers alone cannot save you, ALL Canadians must join or your country is doomed&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:43:06 </td>
   <td style="text-align:left;"> $SPY ITS OVER FOR GAYSTREETBETS. THE ERA OF THEIR LOTTO CALLS IS OVER. NOW WE GO BACK TO THE OLD DAYS. MEGA DEPRESSION, RESET ECONOMY. RAISE RATES TO 15% on houses so owning. THE FED HAS TO RAISE RATES 10x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:43:02 </td>
   <td style="text-align:left;"> $SPY eh atleast I’m not the only one getting my ass kicked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:42:19 </td>
   <td style="text-align:left;"> $SPY futes are cashing hard!! Next week might be an absolute blood bath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:42:06 </td>
   <td style="text-align:left;"> $SPY you guys sound like 10 year olds talking about nukes from your keyboard like you know. 

God help humanity and all the life in earth if we were to ever go there again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:42:02 </td>
   <td style="text-align:left;"> $SPY has been a long time since I held a short over the weekend. Small position, but looks like this could really gape. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:42:02 </td>
   <td style="text-align:left;"> $SPY Maybe Jerome was like yo Biden market is gonna correct push this Ukraine shit so it&amp;#39;s not on our incompetence. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:41:48 </td>
   <td style="text-align:left;"> $SPY $BTC.X Good start but When will it apply to congress🤔🤔🤔

Fed approves rules banning its officials from trading stocks, bonds and crypto https://www.cnbc.com/2022/02/18/fed-approves-rules-banning-its-officials-from-trading-stocks-bonds-and-also-cryptocurrencies.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:41:33 </td>
   <td style="text-align:left;"> $SPY &amp;quot;everything is fine&amp;quot; - really? 
https://www.marketwatch.com/story/junk-bond-issuance-pauses-as-russia-threatens-ukraine-with-spreads-at-their-widest-level-in-a-year-11645230593?mod=mw_latestnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:40:48 </td>
   <td style="text-align:left;"> $SPY https://www.bitchute.com/video/9ZQxwTO3EahS/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:40:36 </td>
   <td style="text-align:left;"> $SPY BURN BURN BURN BURN IT ALL, THIS COUNTRY IS NO WHERE NEAR OTHER COUNTRIES. THE US IS NOW A THIRD WORLD COUNTRY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:40:33 </td>
   <td style="text-align:left;"> $SPY …. https://youtu.be/W0RyqnMTviQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:40:24 </td>
   <td style="text-align:left;"> $SPY Clear your mind and think correctly. If US didn&amp;#39;t fight north korea which only had 1-2 nukes. Why do you think they will fight russia which has thousands of nukes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:40:02 </td>
   <td style="text-align:left;"> $SPY 403  or 429 Bounce  #WhosKnow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:40:02 </td>
   <td style="text-align:left;"> $SPY I think we are undermining the amount of volatility coming. If you think 10 points up one day and then down the next is big, oh boy, get ready. Lots of money to be made, don’t F this up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:39:50 </td>
   <td style="text-align:left;"> $SPY its fcked up the cow gets banned during the time the market is actually going down.  @sonicmerlin  post bearish if youre still alive out there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:39:35 </td>
   <td style="text-align:left;"> $SPY - WE&amp;#39;RE ABOUT TO GO BELOW $430 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:39:24 </td>
   <td style="text-align:left;"> $SPY MF falling now, instead of regular hours, fortunately, I&amp;#39;m all in PUT, and I hold my positions.  
what a week we have. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:39:19 </td>
   <td style="text-align:left;"> latex54ef201a08506192562902ecf97dc739SPY for 120% 
$MU for 119% 
 
Traders: 
u.trhub.net/seesaw 
u.trhub.net/srushisfat 
 
linktr.ee/thetradehub 
 
Movement 
SPY closed -0.65% 
MU closed -3.13% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:39:05 </td>
   <td style="text-align:left;"> $SPY at some point every ticker is gonna be 70% down from ATH.

The spy will have rebalanced multiple times. And you’ll still be saying the markets overbought </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:38:43 </td>
   <td style="text-align:left;"> $SPY $QQQ lololol! Midterm paper for Philosophy 101... Can&amp;#39;t believe this is written by a college student!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:38:41 </td>
   <td style="text-align:left;"> $SPY News FUD still not as good as economy FUD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:38:34 </td>
   <td style="text-align:left;"> $SPY $AMC added another line to my chart. Not really a fan of lines but as we head into what “seems” like the ideal correction. We may see covid levels again. Ironically, the line on the right (which I added) is the second V run which goes into, go figure, elections. This is more of a big picture aspect, so ease on criticism. AMC will squeeze in this time, just my take. Lots of money to be made. I really do hope this is spot on. It’s a strong conviction I have. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:38:19 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ This could be the bottom but it’s definitely not the top. When you see this much red it’s time to load up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:38:18 </td>
   <td style="text-align:left;"> $SPY Biden isn’t the one amassing an invasion force on Ukraine’s borders. A lot of trumpanzees on here don’t seem to understand that so I thought I’d clear it up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:38:10 </td>
   <td style="text-align:left;"> $SPY $450 Calls scooped up for next month. Same old same old. Smells like China trade war nothing. Trumpy did you start this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:38:09 </td>
   <td style="text-align:left;"> $SPY when was the last time we heard something from dc or the talking heads that turned out the way they predicted? when the world is watching and waiting for the one thing to happen it rarely does. its just like the weather predictors they usually get it wrong and when so many are expecting the same thing in the markets it usually does not pan out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:38:01 </td>
   <td style="text-align:left;"> $SPY . https://youtu.be/W0RyqnMTviQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:37:59 </td>
   <td style="text-align:left;"> $SPY damn Daniel. Back at it again with the bear market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:37:56 </td>
   <td style="text-align:left;"> $SPY $JNJ $PFE $MRNA not gonna get out of this one so easily big boi crowds are building into the weekend despite &amp;#39;arrests&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:37:47 </td>
   <td style="text-align:left;"> $SPY Biden needs to go. Can’t stand him and this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:37:46 </td>
   <td style="text-align:left;"> $SPY Oldguy still missing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:37:43 </td>
   <td style="text-align:left;"> $SPY market propped up much to make someone look great during their term? 😆 Much worse times ahead. But at least we have no mean tweets. 🤭 True market values will be revealed soon enough. GL to all! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:37:35 </td>
   <td style="text-align:left;"> Ford Motor Company (NYSE: $F), SPDR S&amp;amp;P 500 ETF (ETF: $SPY) – What To Watch On Ford’s Chart After The Automaker Files For A Tesla-Like Feature https://www.billionaireclubcollc.com/ford-motor-company-nysef-spdr-sp-500-etf-etfspy-what-to-watch-on-fords-chart-after-the-automaker-files-for-a-tesla-like-feature/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:37:06 </td>
   <td style="text-align:left;"> $SPY Right wingers inside the US borders aren&amp;#39;t even patriots any longer. Just look at the posts here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:37:04 </td>
   <td style="text-align:left;"> $SPY me when people leave off Elite from my name </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:37:02 </td>
   <td style="text-align:left;"> $SPY Man who called 2020 crash: Huge event in 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:36:58 </td>
   <td style="text-align:left;"> Not lookin too good boys $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:36:56 </td>
   <td style="text-align:left;"> $SPY team 
USA “war fuck ya!!”
Russia “I’ve got nukes”
USA “oh no no, you’ve got too far now” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:36:55 </td>
   <td style="text-align:left;"> $SPY limit down Tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:36:54 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:36:26 </td>
   <td style="text-align:left;"> $SPY so are puts going to print Tuesday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:36:22 </td>
   <td style="text-align:left;"> $SPY what a week 🦘🦘🦘🦘
             🌬🍁🍁🍁🍁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:35:44 </td>
   <td style="text-align:left;"> $SPY news here &amp;gt; news on tv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:35:32 </td>
   <td style="text-align:left;"> $SPY Yung Putin Island Boi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:35:26 </td>
   <td style="text-align:left;"> $SPY can I not do advanced search on mobile app? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:35:21 </td>
   <td style="text-align:left;"> $SPY   The president is OBSESSED with Ukraine - why ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:35:13 </td>
   <td style="text-align:left;"> $BTC.X $SPY  
 
It comes to this time when what matters most is to own Bitcoin and not the price. And this will drive the price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:34:49 </td>
   <td style="text-align:left;"> $SPY O boy, Things r gettin uglier by the hour 😮‍💨😮‍💨😮‍💨🐻🐻✔️✔️📉📉💥💥💰💰💰🤠🤠🏜🏜😩😩😩🤧🤧🤧💫💫💀💀💀💀💀💀🔥🔥🔥🔥🙂🙂🙂🙂🙂🤫🤫🤫🤫🤫🤫🤫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:34:20 </td>
   <td style="text-align:left;"> $SPY why was the vix down today ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:33:46 </td>
   <td style="text-align:left;"> $SPY economy is going to buckle and earnings already showing true side of fake economy. Stocks will be annihilated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:33:38 </td>
   <td style="text-align:left;"> $SPY This is where I get my news 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:33:36 </td>
   <td style="text-align:left;"> $SPY we he don&amp;#39;t tell Putin this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:33:32 </td>
   <td style="text-align:left;"> $SPY War is simply a reason to sell off and bears gaining more control. It’s all about Fed and momentum. Just fall already, enough of this back and forth drama </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:33:21 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:33:13 </td>
   <td style="text-align:left;"> $SPY relief-rally tuesday, with boosted optimism monday🧨

My god puts are screwed😂 👏🏻remember: Pigs Get slaugthered. Sentiment way to bearish last 2 sessions. Thank you for The extremely cheap calls🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:33:04 </td>
   <td style="text-align:left;"> $SPY no one is going to war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:33:03 </td>
   <td style="text-align:left;"> $SPY brainard speaking must be fed week non stop one after another. https://www.msn.com/en-us/money/markets/brainard-says-its-appropriate-to-start-series-of-fed-hikes-in-march/ar-AAU2VgQ?ocid=uxbndlbing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:33:00 </td>
   <td style="text-align:left;"> $SPY Russia will finish military exercises on Sunday and just go home. He said it was military exercises. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:32:56 </td>
   <td style="text-align:left;"> $SPY girls want girls where I’m from </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:32:56 </td>
   <td style="text-align:left;"> $SPY We need some more anonymous sources getting quoted in the media like they did the past 5 years...  until then, I won&amp;#39;t believe it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:32:51 </td>
   <td style="text-align:left;"> $SPY Safety puts looking good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:32:48 </td>
   <td style="text-align:left;"> $SPY funny thing about the Fed’s trading ban today: 

“anybody who works for a financial institution is not only barred from trading individual stocks (without a committee clearance process) but anyone living under their roof is too. It makes no sense that some low level employee at JPMC is held to a higher standard of insider trading than a congressman.”

The current Fed trading ban doesn’t include family members. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:32:45 </td>
   <td style="text-align:left;"> $SPY $MRNA FDA exposed 

https://youtu.be/gsh_khmtMck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:32:43 </td>
   <td style="text-align:left;"> $SPY $JNJ $PFE $MRNA the crime rate in Ottawa was at 0 before these fellas arrived. locked n loaded ready to snuff out the women and children protesting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:32:41 </td>
   <td style="text-align:left;"> $SPY I3 day weekend more time to chill and buy on Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:32:40 </td>
   <td style="text-align:left;"> $SPY 

It keeps going down… 

https://youtu.be/FDePd-mHOL4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:32:27 </td>
   <td style="text-align:left;"> $SPY Alright guys what a day! Sorry for the delay still coming off the ISPO high. One of the Super Nova’s of the year. But Lets not forget them other big runners to ($CPTN, $ANGH, $FTK) its like today was take off day for everything! 😂 but recap video is in the learning lounge sorry havent posted one in a while just been busy and of course the new video is posted on the channel. I tell you what if today wasnt motivation enough for you the contest for the free stuff idk what will. But anyway lets get ready for tomorrow we got an extended weekend coming up so anything can happen be prepared! Oh yea that watchlist is up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:32:00 </td>
   <td style="text-align:left;"> $SPY everyone say a prayer for the people about to fight! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:31:58 </td>
   <td style="text-align:left;"> $SPY https://www.nytimes.com/live/2022/02/18/world/russia-ukraine-biden-putin bidens say war in coming days stock going under 430 on tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:31:51 </td>
   <td style="text-align:left;"> $SPY Option traders are the real mvps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:31:49 </td>
   <td style="text-align:left;"> $SPY hey everyone, be respectful. Real money is at stake here. Knock it off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:31:45 </td>
   <td style="text-align:left;"> $SPY expect a big bounce next week. But we were always going to re-test $431, it was inevitable. Stocks getting oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:31:41 </td>
   <td style="text-align:left;"> $SPY not sure anyone is rooting for war, just playing the market in front of you. pretty wild whats happening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:31:40 </td>
   <td style="text-align:left;"> $SPY so many conspiracy theories here lately.  Im bearish on you guys. Society has failed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:31:37 </td>
   <td style="text-align:left;"> $SPY this needs 0 geopolitical help to get to 400. US economy guarantees that. I would not wish war on anyone and hope Russia f&amp;#39;s off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:31:36 </td>
   <td style="text-align:left;"> $SPY Biden really need to stfu with his comments. He believes Russia will attack in coming day? Who cares what he believes? The Intel is what matters. I’m tired of this shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:31:32 </td>
   <td style="text-align:left;"> $SPY is it Tuesday yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:30:58 </td>
   <td style="text-align:left;"> $SPY I love how they said Trump would start world War 3. Looks like the the democrats are showing their true colors again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:30:45 </td>
   <td style="text-align:left;"> $spy be sideways too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:30:40 </td>
   <td style="text-align:left;"> $SPY don&amp;#39;t panic. panic is a bad thing and will get you to make bad trades.  panic is intense fear. like that time i saw red in my poo and got really scared.  but then i realized it was just red pepper flakes from the general Tso&amp;#39;s chicken i ate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:30:36 </td>
   <td style="text-align:left;"> 11.77% of insitutions would consider $SPY a core holding, constituting over 8% of their portfolio https://www.insider-analysis.com/search_whales.php?ticker=TABLE_SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:30:29 </td>
   <td style="text-align:left;"> $SPY Big players manipulated that bull run to get out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:30:20 </td>
   <td style="text-align:left;"> $SPY give me 420 come on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:29:52 </td>
   <td style="text-align:left;"> $SPY time to go long Again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:29:31 </td>
   <td style="text-align:left;"> $SPY if war doesn&amp;#39;t happen this weekend. Tuesday will be soon green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:29:13 </td>
   <td style="text-align:left;"> $SPY  
 
Pretty astonishing bears are rooting for war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:28:46 </td>
   <td style="text-align:left;"> $SPY What if Russia takes over Ukraine almost peacefully (with a little squirmish) over weekend? Is that Bearish or bullish to US? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:28:39 </td>
   <td style="text-align:left;"> $SPY over here in Charlotte area, mecklenburg county could be uplifting masks soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:28:14 </td>
   <td style="text-align:left;"> $SPY dementia Joe forgets which war he going to fight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:27:32 </td>
   <td style="text-align:left;"> Todays $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:27:26 </td>
   <td style="text-align:left;"> $SPY we could even see $442 next week but still have $430 in the books and below. The day traders will let this bleed slow. It’s easy money at this point. Best way to go about this opportunity is to quit your job and day trade deep ITM options on spy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:27:22 </td>
   <td style="text-align:left;"> $SPY  Boston lifting vaccine mandate. Leave it to Canada to liberate America </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:27:01 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ That&amp;#39;s a wrap for the week. More fear in AH after Biden spoke. Bulls and bears won&amp;#39;t rest well this long weekend as they will spend even more time watching the news. Got to save that mental strength for next week. Just hope we don&amp;#39;t go nuclear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:26:51 </td>
   <td style="text-align:left;"> $SPY Biden said there is only one way to stop this Russian aggression - get vaccinated 💉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:26:34 </td>
   <td style="text-align:left;"> $SPY we gapped up and then new lows what is this madness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:26:28 </td>
   <td style="text-align:left;"> $SPY people are crazy thinking this is going up next week. Why on earth would it? I get the market doesn’t make sense a lot but damn… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:26:17 </td>
   <td style="text-align:left;"> $SPY putin patiently waiting for Biden to give  the all clear so he can invade ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:25:59 </td>
   <td style="text-align:left;"> $SPY putin talking to brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:25:57 </td>
   <td style="text-align:left;"> $SPY 
ES_F wave (iv) could be at 4377 but while it&amp;#39;s above 4331 it can see the 4387-4400 area before another low in (v) of ((c)) of 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:25:57 </td>
   <td style="text-align:left;"> $SPY this weekend about to go slow af, Monday too. Smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:25:56 </td>
   <td style="text-align:left;"> $SPY im a delusional bull. I love uptrends but i sometimes love dumps even more bc my hedge puts become
money printer to buy all the stocks i want ¯\_(ツ)_/¯ 😵‍💫😵‍💫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:25:46 </td>
   <td style="text-align:left;"> $SPY S&amp;amp;P holding the 1 year moving average (261 days if you want to chart it - # of business days in the year) 
 
https://twitter.com/AndrewThrasher/status/1494764136252723205 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:25:33 </td>
   <td style="text-align:left;"> $SPY looks like a giant HS in daily. On its way down now ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:25:30 </td>
   <td style="text-align:left;"> $SPY going to war with Russia. Should test $420 January Lows. We break that, recession and bear market for years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:25:22 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:25:06 </td>
   <td style="text-align:left;"> $SPY plot twist this runs to 450+ Tuesday lol one can dream </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:25:05 </td>
   <td style="text-align:left;"> $SPY ATH s next week in order? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:24:48 </td>
   <td style="text-align:left;"> $SPY 🔥🔥 Next week will be lit. Don&amp;#39;t care which side - just bring back MEGA volatility. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:24:43 </td>
   <td style="text-align:left;"> $SPY ..., </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:24:37 </td>
   <td style="text-align:left;"> $SPY zoomed in. I prefer the big picture I have. If we open at $439, expect the week to finish down 3.5-4.0% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:24:31 </td>
   <td style="text-align:left;"> $SPY Russia regardless what happens this weekend, if positive will be knee jerk. We are going to test 420 again, I don’t know when. But it’s gonna happen in the next 60-90 days I’d imagine and certainly next 6 mo. Personally I just want to get it over with. If we have to go to 390 just do it already and get back to steady growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:24:14 </td>
   <td style="text-align:left;"> $SPY Let&amp;#39;s get a photoshoot of Biden with his shirt off riding a horse... just to troll Putin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:24:11 </td>
   <td style="text-align:left;"> $SPY nuclear bunkers are racist. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:24:07 </td>
   <td style="text-align:left;"> $SPY Pouring a Xanax out for everyone holding calls over the weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:24:02 </td>
   <td style="text-align:left;"> $SPY WEEKEND AT BIDENS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:52 </td>
   <td style="text-align:left;"> $SPY srs question, is options delta $$ just irrelevant now that the market moves irrelevant to where options would imply it to go? Been this way for months now IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:46 </td>
   <td style="text-align:left;"> $SPY finally some good news...jk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:45 </td>
   <td style="text-align:left;"> $SPY Gap up monday? Putin stops Putin around?? He just trying to remind the world that russia isn&amp;#39;t a punching bag. Pretty Simple he doesn&amp;#39;t want to crash his economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:39 </td>
   <td style="text-align:left;"> $SPY what a horrible human and cabinet. To be more focused on bs, and doing whatever they can to avoid focus upon the inflation created by his presidency….wow. I’m ashamed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:37 </td>
   <td style="text-align:left;"> $SPY Curiously interesting isn’t it. Borrowed from someone. Good old fashioned Bugle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:21 </td>
   <td style="text-align:left;"> $SPY I believe Putin is scared and will wait till next week before trying to invade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:19 </td>
   <td style="text-align:left;"> $QQQ $SPY ;; Bearish after hours activity. $TQQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:19 </td>
   <td style="text-align:left;"> $SPY That feel when you are short the market and then Michael Burry’s twitter rises from the grave: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:19 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F $VIX  
 
In the last 18 trading days, we have gotten 11 days with DIX prints &amp;gt;50%.  
 
Where my DIX friends at? 
 
----------- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:09 </td>
   <td style="text-align:left;"> $SPY 55% of account is in puts, however, I made some nibbles in quality names I like, but honestly looking to trim My nibbles after what I see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:03 </td>
   <td style="text-align:left;"> $SPY plot twist: Biden dumping economy to convert bears into bulls. 
Market goes down, bears buy, market goes back up, bears are now bulls. 

Bankrupt bulls now become bears. 

Rinse and repeat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:23:00 </td>
   <td style="text-align:left;"> $SPY Bitcoin disagrees </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:22:56 </td>
   <td style="text-align:left;"> $SPY prediction.. Russia invasion this weekend. Futures open down 5% Sunday evening. By 3am somehow(fed, blackrock) futures rally and markets open green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:22:54 </td>
   <td style="text-align:left;"> $SPY 385!🙈📉🐻🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:22:38 </td>
   <td style="text-align:left;"> $SPY yall not seeing this America wants this war........putin is smart he will back off so America has no reason to have the war.......putin showing he is the bad guy to do the good thing....public is watching..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:22:31 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/dxJHecyYBno any war between nato and russia will be the end. South America or China will rise to #1 while the rest of the world is destroyed. War can’t happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:22:15 </td>
   <td style="text-align:left;"> $SPY Topical and decent production value. https://youtu.be/LJNtfyq3TDE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:22:13 </td>
   <td style="text-align:left;"> $SPY Biden about to kick the shit outta some commies and stop the spread of communism and yet these bitch ass republicans still don’t like it…🤷🏻‍♂️😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:21:34 </td>
   <td style="text-align:left;"> $SPY if Putin doesnt invide what will Joe do ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:21:17 </td>
   <td style="text-align:left;"> $SPY yall not seeing this usa want this war.......wake up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:21:14 </td>
   <td style="text-align:left;"> $SPY I won&amp;#39;t be happy unless circuit breaker Tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:21:04 </td>
   <td style="text-align:left;"> $SPY next drop should be 425 if not that then 426.7899174200461 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:20:58 </td>
   <td style="text-align:left;"> $SPY this market is not getting a break </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:20:50 </td>
   <td style="text-align:left;"> $SPY this is probably gonna be fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:20:37 </td>
   <td style="text-align:left;"> $SPY Remember all the paid services and Gurus who said Jan was the bottom and we’re headed to $480 this month 😆🤡😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:20:26 </td>
   <td style="text-align:left;"> $SPY I propose we invade Russia while half of their armed forces are distracted in Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:53 </td>
   <td style="text-align:left;"> $SPY Feds pumping, Biden dumping. Who wins? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:53 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:47 </td>
   <td style="text-align:left;"> $SPY Notice peak volume on bottoms. 100% off covid low still. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:46 </td>
   <td style="text-align:left;"> $SPY from pandemic to ww3.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:44 </td>
   <td style="text-align:left;"> $SPY markets in turmoil $QQQ $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:44 </td>
   <td style="text-align:left;"> $SPY 🌈🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:37 </td>
   <td style="text-align:left;"> $SPY monday putin giving a speech..He will clarify on how bad bidens dementia has become </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:35 </td>
   <td style="text-align:left;"> $SPY $JNJ $PFE $MRNA People&amp;#39;s Republic of Canada live footage  https://www.youtube.com/watch?v=0lgioHvio9w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:31 </td>
   <td style="text-align:left;"> $QQQ $SPY The U.S. must have an excellent spy network in Russia which probably makes Putin paranoid. His future actions have been all called out so far, he can’t even surprise anyone. Either way whatever happens it’ll be quick - Russia invades and takes whatever they want in 24 hours. Or he back downs/signs some agreement. I hope it’s an exciting weekend to get this over with </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:16 </td>
   <td style="text-align:left;"> $SPY corporate high yields 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:12 </td>
   <td style="text-align:left;"> $SPY if Putin doesn&amp;#39;t invade at this point Biden is gonna catch the biggest L ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:19:00 </td>
   <td style="text-align:left;"> $SPY invading will crash this hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:18:52 </td>
   <td style="text-align:left;"> $SPY Needs to hold the line, or it&amp;#39;s going straight down to $425 and even retest the last low $421. Biden making sure to spook the market. Feds doing all they can to pump, Biden doing all he can to dump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:18:30 </td>
   <td style="text-align:left;"> $SPY the Russia Ukraine drama magically cured covid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:18:27 </td>
   <td style="text-align:left;"> $SPY lets goooo Brandon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:17:52 </td>
   <td style="text-align:left;"> $SPY plot twist: Ukraine invade Russia 
404 incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:17:48 </td>
   <td style="text-align:left;"> $SPY how screwed are we next week bulls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:17:34 </td>
   <td style="text-align:left;"> $SPY people will panic sell when the war starts, then we&amp;#39;ll move on to doom and despair about rates. The fed will raise lower than forecasted, Bullard did that for a reason. Student loans will be foregiven up to 10-20k, which means a round about stimulus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:17:16 </td>
   <td style="text-align:left;"> $ISPO Only today we have alerted:
Click /start

ISPO - alerted entry $34 
reached ▶️ $108 (+220% gain)

+ $ANGH, $NVCT and more!!!!!

🗣 High potential signals with ~85% win rate. 💰

✅ Daily Weekly watchlist
✅ Day &amp;amp; Swing trades
✅ Options Signals
✅ Crypto &amp;amp; NFTs
✅ Live Trading Sessions
✅ Education
✅ Growing Community of traders
and more....
$SPY 
&amp;quot;Your All in One Trading Group&amp;quot; 

JOIN US TODAY
1 week FREE TRIAL ▶️ see  /plans on telegram </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:17:11 </td>
   <td style="text-align:left;"> $SPY If the teleprompter said &amp;quot;Aliens are invading from Mars&amp;quot;... he would have read it with a straight face. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:17:01 </td>
   <td style="text-align:left;"> $SPY war rumors everyday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:16:59 </td>
   <td style="text-align:left;"> $SPY wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:16:38 </td>
   <td style="text-align:left;"> $SPY much bigger problem for the market then Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:16:18 </td>
   <td style="text-align:left;"> Money $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:16:18 </td>
   <td style="text-align:left;"> $SPY what is the MAX pain number ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:16:17 </td>
   <td style="text-align:left;"> $SPY

Two points down AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:15:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Every single night🐻📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:15:51 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:15:48 </td>
   <td style="text-align:left;"> $SPY What happens when you do yellow cake uranium lines @TraderLeibniz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:15:48 </td>
   <td style="text-align:left;"> $SPY $QQQ 

If there will be diplomatic progress over the weekend, it will jump like a compressed coil. We will be thankful to bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:15:47 </td>
   <td style="text-align:left;"> $SPY   $UVXY   war ! 

A lot of you are on the same page as the president 

😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:15:39 </td>
   <td style="text-align:left;"> $SPY War is gonna happen hodl and buy the dip bois </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:15:28 </td>
   <td style="text-align:left;"> $SPY $QQQ The NASDAQ-100 held support today. Potential still exists for a long term pennant structure to take place. Next week we get the answer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:15:23 </td>
   <td style="text-align:left;"> $SPY  Damn I wish markets were open tomorrow 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:15:22 </td>
   <td style="text-align:left;"> $SPY most stocks are down 1 to 2 percent after hours 
 
 You have 45 min to buy before Tuesday market GAPS up. You will make a easy 1-2 percent bonus on top of Tuesday gains.  
 
Scared money don’t make no money ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:15:08 </td>
   <td style="text-align:left;"> $SPY Damn I wish markets were open tomorrow 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:14:18 </td>
   <td style="text-align:left;"> This is Stocktwits all year long 😂😂😂

$spy $tsla $aapl $arkk $btc.x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:14:15 </td>
   <td style="text-align:left;"> $SPY $QQQ I&amp;#39;m thinking limit down Sunday evening. Nice little throwback to 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:13:51 </td>
   <td style="text-align:left;"> $SPY That last minute bull run at 1:30 just to get the markets going took money from me. It really looks like a meme market when the president delivers some pretty un surprising news and we drop back down to the new lows. Heres to Tuesday puts making up the money yall took. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:13:49 </td>
   <td style="text-align:left;"> $SPY so we are def gaping down on Tuesday by 20 pts on minis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:13:32 </td>
   <td style="text-align:left;"> $SPY Next week make or break…if that support breaks in 420’s…goodness it could get ugly ugly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:13:29 </td>
   <td style="text-align:left;"> $SPY no one is going to war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:13:18 </td>
   <td style="text-align:left;"> $SPY uh oh bear trap. When everyone shorts SPY. It becomes a massive $GME. Sheeeeet!!!!!
Thank you, Mr. President.  😡🤬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:13:10 </td>
   <td style="text-align:left;"> $SPY economy is going to buckle and earnings already showing true side of fake economy. Stocks will be annihilated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:12:31 </td>
   <td style="text-align:left;"> $vixy $spy $qqq $sqqq $kold
The market now: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:12:22 </td>
   <td style="text-align:left;"> $QQQ $SPY If you want to serve in the war, keep buying puts and pumping bearish next week. the wealthy will pump on you and force your assetless self into banckrupty under inflation. Perfect scheme for fresh bodies. Anyone that knows history knows how this goes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:12:12 </td>
   <td style="text-align:left;"> $SPY Putin knows Biden’s term is an opportunity he’s been waiting for. He would never try this shit with trump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:12:11 </td>
   <td style="text-align:left;"> $SPY How many degenerate gamblers will still try and buy options if nukes start flying?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:12:06 </td>
   <td style="text-align:left;"> This week’s performance on my small account. Traded options on $SPY $NVDA $TLT $GLD and $WMT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:11:48 </td>
   <td style="text-align:left;"> $SPY Rally Tuesday on-deck. 452 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:11:34 </td>
   <td style="text-align:left;"> $SPY what did Biden say, I took a nap, a bit longer than I should of😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:11:34 </td>
   <td style="text-align:left;"> $SPY Where did all of Ireland&amp;#39;s clowns go? Maybe they all came to stocktwits. 
https://nypost.com/2021/10/03/northern-ireland-suffers-clown-shortage-amid-covid-19-lockdown/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:11:34 </td>
   <td style="text-align:left;"> $DWAC $spy did not help .. full information included.
https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2789362 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:11:32 </td>
   <td style="text-align:left;"> $SPY Yo i just realized a lot of these bull bots where made around 2014-2015 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:11:20 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK 

OMG!!!😱 DR. BRRRRRRY💰IS BACK,

AND MORE BEARISH THAN EVER!!📉🩸

SH*T IS ABOUT TO GET REAL FANBOYS!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:11:19 </td>
   <td style="text-align:left;"> White House: Sanctions not intended to reduce Russia’s ability to supply energy $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/white-house-sanctions-not-intended-to-reduce-russias-ability-to-supply-energy/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:11:09 </td>
   <td style="text-align:left;"> $SPY G maxwell has committed suicide lol jk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:11:06 </td>
   <td style="text-align:left;"> $SPY My friend in the Russia said there&amp;#39;s something big coming for Kamala when she visits 👀👀👀😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:10:53 </td>
   <td style="text-align:left;"> $SPY if this weekend not war, massive rally coming the Tuesday 💯🤑🐇🐻🔫👽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:10:50 </td>
   <td style="text-align:left;"> $SPY I wonder what happens Tuesday when we’re back and there is still no war 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:10:26 </td>
   <td style="text-align:left;"> $SPY if war doesn&amp;#39;t happen this weekend. Tuesday will be soon green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:10:07 </td>
   <td style="text-align:left;"> 427 $SPY  Bounce Tuesday  #WhosKnow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:09:59 </td>
   <td style="text-align:left;"> $SPY so where did you get your Intel about russia invasion??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:09:53 </td>
   <td style="text-align:left;"> $SPY Biden doing the war dance trying to get $800 billion defense budget passed that includes $100+ billion in &amp;quot;green&amp;quot; initiatives.  That&amp;#39;s all this is about - getting money to his &amp;quot;people&amp;#39;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:09:43 </td>
   <td style="text-align:left;"> $SPY guys let’s talk about portfolio diversification. Are you equipped with $GLD &amp;amp; or $XLE ? &amp;amp; Many other choices out there. War will cause precious metals &amp;amp; Oil to climb 🧗‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:09:39 </td>
   <td style="text-align:left;"> $SPY Mountain training.. Always have an out.  Just like trading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:09:37 </td>
   <td style="text-align:left;"> $SPY it’s a shame moo died he’d love to be around to see this rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:09:35 </td>
   <td style="text-align:left;"> $TSLA Retail is so scared lol $SPY $PLTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:09:21 </td>
   <td style="text-align:left;"> $SPY 🤔 biden hires drag queen for department of energy .. sure these headlines are looking fantastic while biden tries to look tough infront of Putin to stop war  🤦‍♂️🤦‍♂️🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:09:06 </td>
   <td style="text-align:left;"> $VXX $SPY $ES_F $QQQ $VIX Trading vol in a constrained market:   
  
Our swings have  been all credit spreads, and have hit at 100% this  year.  Vol has made premium so inflated its too rich of a trade to pass on. Closed several on TSLA today. (actually one expired worthless from $4200 credit per contract)  
  
For day trading its simple vol trades correlating the index (futures or equity) with the velocity of  moves on the VXX  indicating future risk prices advancing or declining. (you can you use other similiar products if you like, they all provide you with the same information. So preference).  
  
 The Stoch (white line on bottom of each chart) will give a visual on the velocity of delta, which helps dictate price target on the trade.  It is the only indicator on both charts outside of price and volume. The variation on this trade is getting rid of stoch and just focus on VPA.  
  
Been a really nice market for both of these trading strategies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:08:59 </td>
   <td style="text-align:left;"> $SPY So after all this time the truth comes out. OFG is a fucking idiot 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:08:58 </td>
   <td style="text-align:left;"> $SPY still have an hour left to drop I’m on the treadmill now watching this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:08:47 </td>
   <td style="text-align:left;"> $SPY 

Let peace be with Ukrainian people… 

https://youtu.be/gPiTIhFQp3U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:08:20 </td>
   <td style="text-align:left;"> $SPY I love how they said Trump would start world War 3. Looks like the the democrats are showing their true colors again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:08:19 </td>
   <td style="text-align:left;"> $SPY where&amp;#39;s RAMBO when we need him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:08:19 </td>
   <td style="text-align:left;"> $SPY Russia will finish military exercises on Sunday and just go home. He said it was military exercises. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:08:17 </td>
   <td style="text-align:left;"> $SPY Option traders are the real mvps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:08:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK is this the end?  Bear market?  
Everyone losing money in stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:08:06 </td>
   <td style="text-align:left;"> $SPY Russia attacks soon. I believe Joe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:08:00 </td>
   <td style="text-align:left;"> $SPY next week news, Ukraine and Russia tension eases. I betting on the market going back up March 9th. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:07:59 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY  I have reasons to believe Potato Joe doesn&amp;#39;t even know he is a president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:07:54 </td>
   <td style="text-align:left;"> $SPY Market Recap: Friday, February 18, 2022 
 
If you like this newsletter, feel free to subscribe. It&amp;#39;s FREE, No Ads and you will only get one email per day after the market closes to make sense of what&amp;#39;s happening in markets 🙏 
 
https://marketcrier.com/markets/blog/market-digest/23322c2e-7ea2-4689-b6ed-5ca23f48f2ef </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:07:48 </td>
   <td style="text-align:left;"> $SPY red market? you ready? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:07:37 </td>
   <td style="text-align:left;"> $SPY is it 8pm yet. Fuck close this drama already! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:07:33 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://twitter.com/sspencer_smb/status/1494754795999092737?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1494754795999092737%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fembed.lih.kg%2Fframe%3Fu%3Dhttps3A2F2Ftwitter.com2Fsspencer_smb2Fstatus2F14947547959990927373Fs3D2026t3DGLj4vM-BBkDqAI4mCPnfTgh%3Db3c58e4d 
 
Too many people are shorting, we can have a massive short covering rally soon if we just have a little bit of a good news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:07:32 </td>
   <td style="text-align:left;"> $SPY futures are closed. But look at QQQ - down 0.64% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:07:24 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:07:19 </td>
   <td style="text-align:left;"> $SPY are we going to enter a bear market? Most likely yes.  Fed could still reverse course if inflation subsides.  Probably not gonna happen the first half of the year.  don’t catch a falling knife until Powell tells you to! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:07:17 </td>
   <td style="text-align:left;"> $SPY Moo is not wasting anytime catching up on all the posts he didnt do while being banned </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:56 </td>
   <td style="text-align:left;"> $SPY 💫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:54 </td>
   <td style="text-align:left;"> $SPY invasion will continue until inflation comes down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:49 </td>
   <td style="text-align:left;"> $SPY Russia just pulling back their bowstring before they release </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:43 </td>
   <td style="text-align:left;"> $SPY market correction happening still 12% to go down to hit correction territory of 20% from ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:36 </td>
   <td style="text-align:left;"> $SPY circuit breaker week finally next week.  Yay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:28 </td>
   <td style="text-align:left;"> $SPY “…enough is enough.” ie #justdoit #youwont #shitorgetoffthepot 

https://www.gzeromedia.com/ukrainians-offer-3600-view-on-russian-conflict </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:24 </td>
   <td style="text-align:left;"> $SPY Putin is 14548820X ahead of brandon and the nursing home </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:16 </td>
   <td style="text-align:left;"> $SPY 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:16 </td>
   <td style="text-align:left;"> $SPY market dumping ah fast and relentless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:14 </td>
   <td style="text-align:left;"> $SPY 

https://m.youtube.com/watch?v=n1XTArKHaEE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:07 </td>
   <td style="text-align:left;"> $SPY Russia and Ukraine are already at war in the break away region.  Why would Put 
 want to formally declare war? 
He&amp;#39;s simply sending his soliders disguised as Ukrainian separatists and push his agenda there. 

Idiots need to realize this is Bidens plan to blame Putin for the incoming crash. Typical Democrat strategy. . Blame others for your failures. Never accept fault. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:06:06 </td>
   <td style="text-align:left;"> $SPY live look at the Biden Intel war room </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:05:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA The War in Ukraine reminds me of the new Tesla factories: “any day now” but in reality never going to happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:05:09 </td>
   <td style="text-align:left;"> $SPY I love America, but I’ve got bent over enough to know when someones about to get futt bucked. Looking at Ukraine, unfortunately. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:04:39 </td>
   <td style="text-align:left;"> $SPY When you do anything to win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:04:35 </td>
   <td style="text-align:left;"> $SPY brandon found a new friend and advisor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:04:35 </td>
   <td style="text-align:left;"> $SPY here’s the Dow.  Just remember anything that happens to the Dow is going to be magnified in tech.  Why? Idk.  But I have it on good moothority. Moo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-19 08:04:34 </td>
   <td style="text-align:left;"> $SPY Where was Biden during China forceful takeover of Hongkong and their freedom and democracy?   Oh that&amp;#39;s right, CCP Agent Biden at work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:51:49 </td>
   <td style="text-align:left;"> $SPY Instead of relying on &amp;quot;intelligence&amp;quot; based on reporters, why doesn&amp;#39;t Biden just pick up that phone and call Putin?   
Biden: Hey Putin, you attacking or what? 
Putin: I keep saying I&amp;#39;m not!  Unlike you, I&amp;#39;m protecting my border with MY military.  What about you? 
Biden:  Oh, we already lost war against Mexico.  They own our border.  
$UVXY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:51:46 </td>
   <td style="text-align:left;"> $FUBO Earnings Wednesday.  One of the most heavily shorted names in any market, more shorted than AMC &amp;amp; GME.  Not sure if this is true of $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:49:35 </td>
   <td style="text-align:left;"> $QQQ looks quite dicey. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:44:47 </td>
   <td style="text-align:left;"> $SOS $QQQ $BTC.X $ETH.X $AMC Hydro powered crypto miner in United States. 🦧 🍌 🚀 Shorted by Hindenburg 😡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:44:01 </td>
   <td style="text-align:left;"> $QQQ if you think that the market is dropping because of this silly war, then you need to think twice. The market needs any reason to go down. no additional money to print and the hedge funds are selling everything. Once retailers lose all their savings, the hedge funds will jump again and buy everything at a very cheap price. I can bet now, if we were in a bull market and we had a similar fun (Russia-Ukraine) nobody will notice and media won&amp;#39;t talk every second about it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:41:19 </td>
   <td style="text-align:left;"> $QQQ yikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:41:16 </td>
   <td style="text-align:left;"> $MSFT I’m almost certain that Biden, Pelosi, and all the other dems shorted this market 🤔 mmmm how does Biden know what is inside Putins head 🤔 For full disclosure, I sold my puts earlier today for a sweet profit but puts are still the play for next week! 
 
WW3 coming? Stock market crash soon? $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:40:06 </td>
   <td style="text-align:left;"> $QQQ if recession comes, we can see SPY at 250 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:39:04 </td>
   <td style="text-align:left;"> $QQQ Brandon will crash the Stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:39:03 </td>
   <td style="text-align:left;"> $QQQ the end is near! Buy bitcoin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:38:47 </td>
   <td style="text-align:left;"> $QQQ Not looking good, but does not change the fact that I bought calls at close 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:38:43 </td>
   <td style="text-align:left;"> $SPY $QQQ lololol! Midterm paper for Philosophy 101... Can&amp;#39;t believe this is written by a college student!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:38:19 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ This could be the bottom but it’s definitely not the top. When you see this much red it’s time to load up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:37:12 </td>
   <td style="text-align:left;"> $QQQ too many bears, bought a YOLO call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:36:58 </td>
   <td style="text-align:left;"> Not lookin too good boys $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:35:22 </td>
   <td style="text-align:left;"> $QQQ 1.79 put/call ratio..insane...squeeze territory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:34:32 </td>
   <td style="text-align:left;"> $QQQ whats the opposite of stonk? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:31:44 </td>
   <td style="text-align:left;"> $QQQ let’s go Brandon! Dude is a stud lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:31:06 </td>
   <td style="text-align:left;"> $QQQ Fear everywhere is only a good thing as a scalper and an options seller... Had to scalp the globex bear trap today on Nazy quick bounce (a must trade), but I also sold the bottom 1/2 of the next &amp;#39;staggered&amp;#39; Iron Condor, right when price started reversing from the trap.  Was such a good bounce that I closed that position for a daytrade too.. until next week!   Wash, Rinse, Repeat...  (follow the math). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:30:12 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:28:54 </td>
   <td style="text-align:left;"> $QQQ we are about to lose even more covid traders soon. lol.  Gonna have to close those discords. lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:28:40 </td>
   <td style="text-align:left;"> $QQQ anyone who’s holding shares, are good no need to panic if u don’t need the money right away. Anyone holding calls or puts?? Well.. rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:27:01 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ That&amp;#39;s a wrap for the week. More fear in AH after Biden spoke. Bulls and bears won&amp;#39;t rest well this long weekend as they will spend even more time watching the news. Got to save that mental strength for next week. Just hope we don&amp;#39;t go nuclear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:23:19 </td>
   <td style="text-align:left;"> $QQQ $SPY ;; Bearish after hours activity. $TQQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:22:10 </td>
   <td style="text-align:left;"> $QQQ Russia will attack today at 2 pm, they will attack tomorrow, they will attack in a couple days after a big breakfast, they will attack next Monday after a restful weekend no they will attack before March black blah blah. Shut up Brandon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:21:45 </td>
   <td style="text-align:left;"> $QQQ In the cloud now.  Flat bottom should act as a magnet, $324 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:20:12 </td>
   <td style="text-align:left;"> $QQQ I like the OBV divergence here. Not what I would call “in free fall” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:19:44 </td>
   <td style="text-align:left;"> $SPY markets in turmoil $QQQ $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:19:31 </td>
   <td style="text-align:left;"> $QQQ $SPY The U.S. must have an excellent spy network in Russia which probably makes Putin paranoid. His future actions have been all called out so far, he can’t even surprise anyone. Either way whatever happens it’ll be quick - Russia invades and takes whatever they want in 24 hours. Or he back downs/signs some agreement. I hope it’s an exciting weekend to get this over with </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:15:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Every single night🐻📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:15:48 </td>
   <td style="text-align:left;"> $SPY $QQQ 

If there will be diplomatic progress over the weekend, it will jump like a compressed coil. We will be thankful to bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:15:39 </td>
   <td style="text-align:left;"> $QQQ $IWM Michael Burry back on Twitter 😈 https://youtu.be/HL9kaJZw8iw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:15:28 </td>
   <td style="text-align:left;"> $SPY $QQQ The NASDAQ-100 held support today. Potential still exists for a long term pennant structure to take place. Next week we get the answer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:15:26 </td>
   <td style="text-align:left;"> $QQQ Just bought 15 QQQ shares and will buy 15 every week until i have invested 100,000.00 about 20 weeks.   GLT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:14:15 </td>
   <td style="text-align:left;"> $SPY $QQQ I&amp;#39;m thinking limit down Sunday evening. Nice little throwback to 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:12:31 </td>
   <td style="text-align:left;"> $vixy $spy $qqq $sqqq $kold
The market now: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:12:22 </td>
   <td style="text-align:left;"> $QQQ $SPY If you want to serve in the war, keep buying puts and pumping bearish next week. the wealthy will pump on you and force your assetless self into banckrupty under inflation. Perfect scheme for fresh bodies. Anyone that knows history knows how this goes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:12:12 </td>
   <td style="text-align:left;"> $QQQ Russia is invading next week now, and if not next week the week after and if not that week the week after that..... Attack imminent for 2 months almost lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:11:20 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK 

OMG!!!😱 DR. BRRRRRRY💰IS BACK,

AND MORE BEARISH THAN EVER!!📉🩸

SH*T IS ABOUT TO GET REAL FANBOYS!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:11:19 </td>
   <td style="text-align:left;"> White House: Sanctions not intended to reduce Russia’s ability to supply energy $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/white-house-sanctions-not-intended-to-reduce-russias-ability-to-supply-energy/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:10:15 </td>
   <td style="text-align:left;"> $QQQ Pooootin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:09:46 </td>
   <td style="text-align:left;"> $QQQ This has been crushed in AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:09:06 </td>
   <td style="text-align:left;"> $VXX $SPY $ES_F $QQQ $VIX Trading vol in a constrained market:   
  
Our swings have  been all credit spreads, and have hit at 100% this  year.  Vol has made premium so inflated its too rich of a trade to pass on. Closed several on TSLA today. (actually one expired worthless from $4200 credit per contract)  
  
For day trading its simple vol trades correlating the index (futures or equity) with the velocity of  moves on the VXX  indicating future risk prices advancing or declining. (you can you use other similiar products if you like, they all provide you with the same information. So preference).  
  
 The Stoch (white line on bottom of each chart) will give a visual on the velocity of delta, which helps dictate price target on the trade.  It is the only indicator on both charts outside of price and volume. The variation on this trade is getting rid of stoch and just focus on VPA.  
  
Been a really nice market for both of these trading strategies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:08:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK is this the end?  Bear market?  
Everyone losing money in stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:07:33 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://twitter.com/sspencer_smb/status/1494754795999092737?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1494754795999092737%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fembed.lih.kg%2Fframe%3Fu%3Dhttps3A2F2Ftwitter.com2Fsspencer_smb2Fstatus2F14947547959990927373Fs3D2026t3DGLj4vM-BBkDqAI4mCPnfTgh%3Db3c58e4d 
 
Too many people are shorting, we can have a massive short covering rally soon if we just have a little bit of a good news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:05:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA The War in Ukraine reminds me of the new Tesla factories: “any day now” but in reality never going to happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:04:02 </td>
   <td style="text-align:left;"> $QQQ anyone else love watching the line drop
Down on the fast stochastics? It’s like ohhh Yeaa loosen up that booty hole </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:03:59 </td>
   <td style="text-align:left;"> $QQQ wait until the fake news the was ain&amp;#39;t happening Tuesday morning ..Cramer is sexy because he&amp;#39;s so hoents </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:03:31 </td>
   <td style="text-align:left;"> &amp;#39;BIG SHORT&amp;#39; MICHAEL BURRY REACTIVATES TWITTER ACCOUNT 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:03:30 </td>
   <td style="text-align:left;"> $QQQ how long till they start holding mandatory drafts again? I think the market is underestimating what War really means at these high levels. Leg is much much lower! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:02:34 </td>
   <td style="text-align:left;"> $QQQ ladies &amp;amp; gents...there will be an explosion on Tuesday and not in the Ukraine....the QQQ&amp;#39;s will explode higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:02:32 </td>
   <td style="text-align:left;"> $QQQ $SPY in my opinion, i dont think this economy is good at all because it was artificially pumped with trillions of dollars. i think we are going into a recession very soon with these rate hikes. the fed put us in a disaster. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:02:20 </td>
   <td style="text-align:left;"> $QQQ Nasdaq McClellan Oscillator not looking healthy... 
- negative MacD today first time in Feb. 
- MacD down-cross today...last occurrence early Jan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:01:54 </td>
   <td style="text-align:left;"> $SPY Biden failed at covid, failed at economy, failed with Hunter, failed with energy, failed with illegals, failed Afghanistan, and now he&amp;#39;s going to fail the world with Russia.  who voted for this loser?  $uvxy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:01:31 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Can the world afford to isolate Russia like North Korea ??

Let’s do that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:01:25 </td>
   <td style="text-align:left;"> $QQQ can we limit down next Tuesday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:01:06 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

The pooots will continue to print, solid work today bear brothers. 😎

🐻 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 08:00:46 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY $IWM - Gosh, these lunatics are actually pushing for war. Who’s gonna suffer? The people. Like always. The people always suffer and the leaders just kick back. Sad people protest vaccine mandates but not WWIII with Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:59:03 </td>
   <td style="text-align:left;"> $QQQ who the fuck voted for this idiot??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:58:20 </td>
   <td style="text-align:left;"> $spy $qqq bears will be going to war for me. The rich will get richer and they will take your money on this psyop to have fresh bodies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:57:16 </td>
   <td style="text-align:left;"> $QQQ downtrend firmly in place. once momo support cracks the americans will panic mania of selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:56:49 </td>
   <td style="text-align:left;"> $QQQ Death cross crystallizes in Nasdaq Composite on Friday for first time in 2 years, in a bearish sign for the stock market

https://www.marketwatch.com/story/death-cross-crystallizes-in-nasdaq-composite-on-friday-for-first-time-in-2-years-in-a-bearish-sign-for-the-stock-market-11645196858?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:56:05 </td>
   <td style="text-align:left;"> $TSLA Who has 900c and is iffy about them for next week? I will buy them from you after hours via cash app or zelle payment. $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:56:03 </td>
   <td style="text-align:left;"> $PL $SPY $QQQ  stocks outside the indexes have no floor. there is no bid. 🔮📉 long term bullish, short term bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:55:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY

Modern Monetary Theory accuracy is about as real as a pregnant man. 🐂💩

https://twitter.com/zerohedge/status/1494804013014999041?s=20&amp;amp;t=LHoiwTYY7q6ayH8MD9qh8Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:55:03 </td>
   <td style="text-align:left;"> $QQQ OH LOOK A FEW GREEN CANDLES 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:54:59 </td>
   <td style="text-align:left;"> $SPY &amp;quot;You don&amp;#39;t buy the dip before a 3 days holiday and Putin about to invade&amp;quot;
$SPY $QQQ $VIX $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:53:39 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ So the imbecile Biden spoke and the market tanked further after hours. Nothing new. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:53:00 </td>
   <td style="text-align:left;"> $SPY $QQQ enjoy your bath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:51:09 </td>
   <td style="text-align:left;"> $QQQ My current outlook: gap down Monday followed by a 2-3 day relief rally to ~350 on double-bottom potential, then the double bottom fails and we can probe 315 in early March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:49:59 </td>
   <td style="text-align:left;"> $SPY $QQQ 
 
https://www.youtube.com/watch?v=Ys5NlAoI2HA&amp;amp;t=150s 
 
Let&amp;#39;s see if we will get a big rally next week. The Russian situation is a big unknown but if there is no attack next week then I can see this market rallying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:48:51 </td>
   <td style="text-align:left;"> $qqq my portfolio is down 40% thanks to the likes of $nio $roku $gevo and $pltr - bought at wrong time and now I am stuck. Thankfully these are long term investments but this only shows that index funds are the way to go long run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:47:10 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL that wasn’t even that bad. Nice and controlled. How about a 2% down day? 3%?  You know they’re coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:46:15 </td>
   <td style="text-align:left;"> $SPX $SPY word from the grapevine $MS managers see SPX 4000 in 2022. $QQQ $IWM  Hold on to your hats </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:46:01 </td>
   <td style="text-align:left;"> Houston!  We have a problem up here. 
 
There seems to be a switch that we just can&amp;#39;t reach and it&amp;#39;s the one that controls the future of the $SPY and the $QQQ&amp;#39;s! 
 
Dammit Houston!  Can you see the 425&amp;#39;s and 420&amp;#39;s from down there on the SPY? 
 
 
$SPY   $QQQ  $VXX   signals aren&amp;#39;t too appealing at all as more $$$ mgrs just hit the SELL buttons. We may be near a crucial level where the floor opens up. Hmmmm..... tic tic tic.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:45:12 </td>
   <td style="text-align:left;"> $QQQ yo that 50 sma is getting real close to dropping below the 200. ooooooo if that happens it is gonna be PUT CITY!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:44:54 </td>
   <td style="text-align:left;"> $QQQ gotta love a nice +151% 0DTE put scalp to end the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:44:34 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ they are throwing the kitchen sink at these markets. War, inflation, rate hikes…

If you can’t take the pain, you don’t deserve the gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:44:03 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:43:58 </td>
   <td style="text-align:left;"> $QQQ Can&amp;#39;t wait to see the gap down Tuesday, -5% minimum.  Easily another 25% leg lower coming in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:43:51 </td>
   <td style="text-align:left;"> Draghi: EU sanctions on Russia should not target the energy sector $EURUSD $EURRUB $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/draghi-eu-sanctions-on-russia-should-not-target-the-energy-sector/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:43:45 </td>
   <td style="text-align:left;"> $QQQ Down 3 days in a row. 356.13 | 356.04 | 345.45 | 342.25 |  https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:43:06 </td>
   <td style="text-align:left;"> $ROKU $SPY $QQQ Trust fund kids and hedge bros are gonna pump this with me on you. The elites are never going to send their children to war. Bankrupt bears and apes will have to go. Keep pumping war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:41:43 </td>
   <td style="text-align:left;"> Fed could be back-tracking on rate hikes by 2024 $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/fed-could-be-back-tracking-on-rate-hikes-by-2024/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:41:30 </td>
   <td style="text-align:left;"> $QQQ We literally just stood idly by and watched when Putin invaded  &amp;amp; annexed Crimea. Only difference I see with Ukraine is the large political donations to Democrats from Ukrainian oligarchs &amp;amp; their family members getting board seats at gas companies. Thats all it takes to drag the remaining 330 million US citizens into a war with a nuclear power </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:41:28 </td>
   <td style="text-align:left;"> $QQQ who remembers that one time last night that the bulls said  “FuTeS aRe RiPpInG” 🤣🤣🤣🤣🔪🔪🔪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:40:08 </td>
   <td style="text-align:left;"> Russian official: Putin will announce important decision on Donbas on Sunday $SPY $QQQ $DJIA $EURRUB $USDRUB https://www.billionaireclubcollc.com/russian-official-putin-will-announce-important-decision-on-donbas-on-sunday/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:40:00 </td>
   <td style="text-align:left;"> $QQQ $SPY $500 to $500,000 challenge. One month. Short term options. No buying power after each day. Who wants to partake. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:39:59 </td>
   <td style="text-align:left;"> $QQQ this is my new favorite penny stock to short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:39:56 </td>
   <td style="text-align:left;"> $QQQ but but but blinken saved the market last night! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:39:42 </td>
   <td style="text-align:left;"> $SPY $QQQ Bulls know when the draft is coming. The elite are never gonna send their kids to war. This market gets pumped and all bears enlisted automatically. No trust fund for you bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:38:20 </td>
   <td style="text-align:left;"> $QQQ markets showing how much faith they have in our President Lmao . What a disaster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:37:55 </td>
   <td style="text-align:left;"> $ZM These are my three favorite beaten down Innovation stocks 
 
🔥 $ZM Zoom  ---&amp;gt;  Closing price: $126.96 
🔥 $DKNG DraftKings  ---&amp;gt;  Closing price: $17.29 
🔥 $FSLY Fastly  ---&amp;gt;  Closing price: $18.70 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:35:40 </td>
   <td style="text-align:left;"> $QQQ $340 was the first support line since today now it broke through and is about to test $339 again so it’s possible it will hit $338 and below, just giving off the info I’ve gathered off my trading strategy. (I’m using the head and shoulder objective rule) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:35:22 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ Per Abilene Paradox principle the results are never what one anticipates. The archduke of Austria was killed by a Serbian nationalist on some idle street in Sarajevo in 1914... and it started a domino effect that led to millions of dead and WW1. Likewise the attack on Fort Sumter in 1861 led to the worst war in the 19th century which saw such morbid improvements on previous conflicts as total warfare + trench warfare + bombings of civilians and urban combat, with 900k dead out of a US population of 31 million at the time, with 80% of young men of the South either wounded or dead by its end, a larger proportion than Russia suffered in WW2 in that demographic. Here a single mortar exchanged on the Ukraine frontline can lead to an all out nuclear war... be very afraid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:35:11 </td>
   <td style="text-align:left;"> $QQQ if war before Tuesday then $280 or else $330 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:35:08 </td>
   <td style="text-align:left;"> Don&amp;#39;t be fearful. $SPY $QQQ $DIA 

WEEKLY MARKET RECAP: Why Geopolitical Events Are Buying Opportunities
https://youtu.be/jy_mK8P7COY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:34:40 </td>
   <td style="text-align:left;"> $QQQ omg war is coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:34:29 </td>
   <td style="text-align:left;"> $QQQ I’m a big fan of bear markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:34:25 </td>
   <td style="text-align:left;"> $spy $qqq big brain print on diplomacy staring in your face and everyone is sheepish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:33:45 </td>
   <td style="text-align:left;"> $QQQ not surprised... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:33:09 </td>
   <td style="text-align:left;"> $QQQ $IWM $DOW $SPY 

If by this point after 1 month and 18 days into this bear market, you still can&amp;#39;t instead of every dip being bought, it is every rally being sold into and its all about rate hikes/quantitative tapering driven, then you will have a very expensive financial lesson coming your way. 
 
The war talk is a just an excuse to distract you from the market crash that is incoming as a result of failed US fed policy and government planning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:33:06 </td>
   <td style="text-align:left;"> $QQQ watching Mad Money doesn’t count as DD. You’ll be better informed by watching Power Rangers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:32:49 </td>
   <td style="text-align:left;"> $QQQ Imagine holding puts until tuesday. Go long or go wrong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:32:27 </td>
   <td style="text-align:left;"> $QQQ $SPY alright this is it media..spread Ukraine russia fud this weekend so we can cover our shorts next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:32:22 </td>
   <td style="text-align:left;"> $QQQ so many people here rooting against the president at time of conflict just because they voted for someone else. This country is doomed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:32:21 </td>
   <td style="text-align:left;"> $QQQ nobody respects Brandon. We need trump back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:31:34 </td>
   <td style="text-align:left;"> $QQQ $SPY chikibriki russian nation thank you putting for unlimited put printing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:30:35 </td>
   <td style="text-align:left;"> $QQQ $SPY it may jump 2% on war news before crashing 5% later

That’s how markets work 

Don’t call it manipulation when that happens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:30:04 </td>
   <td style="text-align:left;"> $QQQ haha imagine actually holding shares before close today how fcking stupid are you then? or just a pussy thinking from hopes and feelings....ofcourse it will tank this weekend, rates, SKY HIGH INFLATION AND WAR!!!! and you guys just hope it will go up go fcking learn the stock market or stay away or just keep doing what your doing suckers and pay my yacht!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:28:33 </td>
   <td style="text-align:left;"> $QQQ putin is not the problem here, usa and nato pumping fake news. Do your dd. Biden is a original clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:26:16 </td>
   <td style="text-align:left;"> $QQQ stop believing the FUD, even if there is a war it’s not going to crash our economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:25:20 </td>
   <td style="text-align:left;"> $FB  $SPY $QQQ how many pensions are now tied up in this trash down 50%???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:24:34 </td>
   <td style="text-align:left;"> $QQQ another 2b outflow. Puts up over 1000% and keep going. Love taking money from libtards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:23:59 </td>
   <td style="text-align:left;"> $QQQ why USA so scared of Russia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:23:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $RUT $IWM

🗓 Key date: Feb 24 🗓 

Russia meets with European leaders on that date.
-said Prez Biden: 
“If Russia takes military action before that date, it’ll be clear that they have slammed the door shut on diplomacy. They will have chosen war, and they will pay a steep price for doing so. Not only from the sanctions that we and our allies will impose on Russia, but the more outrage the world will visit upon them.”

Link: https://youtu.be/F8Hif-pgiKE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:23:28 </td>
   <td style="text-align:left;"> $NIO can PUTIN PLS INVADE $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:21:10 </td>
   <td style="text-align:left;"> Stocks fall again, handing Wall Street another losing week $SPY $QQQ $DJIA $DIA https://www.billionaireclubcollc.com/stocks-fall-again-handing-wall-street-another-losing-week/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:20:24 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ so if there is no war this weekend just like there was no war on Wednesday, and no war last weekend - how much longer can the “boy cry wolf”?

Seems like the markets have war heavily priced in right now… The car bombing didn’t even budge the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:19:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM better buy gold /silver 
https://youtu.be/4FQOWG26uho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:19:36 </td>
   <td style="text-align:left;"> Fed officials push back on rapid interest rate hikes $SPY $QQQ $DJIA $DIA $DXY https://www.billionaireclubcollc.com/fed-officials-push-back-on-rapid-interest-rate-hikes/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:18:56 </td>
   <td style="text-align:left;"> $SPY $QQQ another week goes by and still no war in Ukraine despite Biden saying every single week that there will be a war. The guy hates the stock market so much he conjures up invasion hoax to make stocks go down. LETS GOOO BRANDON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:18:06 </td>
   <td style="text-align:left;"> US equities struggle to the finish line in tough week $QQQ $DJIA $DIA $SPY https://www.billionaireclubcollc.com/us-equities-struggle-to-the-finish-line-in-tough-week/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:17:25 </td>
   <td style="text-align:left;"> $QQQ needs a 30% correction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:17:18 </td>
   <td style="text-align:left;"> $QQQ $SPY lucky I have puts, I was just trading the chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:16:25 </td>
   <td style="text-align:left;"> $QQQ $TQQQ  I would still like to understand how Russia’s relationship to Ukraine in any way impacts 100 US tech companies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:15:44 </td>
   <td style="text-align:left;"> Fed’s Williams: Sees a terminal rate of 2% to 2.5% by end of next year  $SPY $QQQ $DJIA $DIA https://www.billionaireclubcollc.com/feds-williams-sees-a-terminal-rate-of-2-to-2-5-by-end-of-next-year/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:14:32 </td>
   <td style="text-align:left;"> $QQQ $DIA $SPY  Biden will do this every week to try and destroy American wealth , and idiots vote democrat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:14:25 </td>
   <td style="text-align:left;"> $QQQ Bottoms and tops usually need to be filled. With uncertainty going into next week and with upcoming economic reports that will need to be priced in which means Wall Street algos will need to get the 334 wick filled from January and next wick to be filled is 328. Don’t forget the ema 50 soon to cross ema200 for more bearish trend. Look at the technicals from late 2018 when they crossed and the bottom wicks were filled. I will wait to add again at 330 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:13:58 </td>
   <td style="text-align:left;"> $QQQ Biden purposely makes the situation worse so when Russian declare no war get ready for a huge rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:12:43 </td>
   <td style="text-align:left;"> $SPY $QQQ All the Green days this past week have had below average volume. That means the smart money is not buying the &amp;quot;dip&amp;quot;. It was all retail buying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:12:40 </td>
   <td style="text-align:left;"> $QQQ ooooooooooo so scary.  Every year the market goes through an emotional downturn, followed by higher highs.... 
 
If you can stomach the worry, you&amp;#39;ll be fine in a few months... it always like this -- look back over time. 
 
Clearly, if you&amp;#39;re a day trader, this is very hard to stomach. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:12:17 </td>
   <td style="text-align:left;"> $QQQ $spy $uvxy IF THERE EVER WAS GOING TO BE A WAR THERE WOULDN&amp;#39;T BE NOTICE AND EVERYBODY TELLING YOU IT&amp;#39;S GOING TO HAPPEN.

Anybody with half a brain cell knows proper war strategy is for nobody to know anything, element of surprise etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:12:15 </td>
   <td style="text-align:left;"> Daily $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/dKSzSZ0xNGo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:12:02 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ brandon and his buddies are domestic terrorists that terrorize this country with: highest inflation in decades, highest unemployment in decades, highest crimes across major cities, high gas prices, pandemic, lockdowns, pseudo science, fake news, misinformation, society division, supply shortages, low manufacturing output, international policy failure and list goes on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:11:30 </td>
   <td style="text-align:left;"> The ugly price action continues in US stocks $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/the-ugly-price-action-continues-in-us-stocks/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:11:17 </td>
   <td style="text-align:left;"> $QQQ who’s ready for a face ripping rally next week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:10:12 </td>
   <td style="text-align:left;"> $SPY $QQQ why yall believing this bs war propaganda. Putain wont invade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:09:34 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-02-18 Daily Forecast Video: 
https://www.youtube.com/watch?v=hRyfsKc4-2I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:08:01 </td>
   <td style="text-align:left;"> $QQQ $SPY  Putin may just keep its action limited to Russian Donbas and not attack Kiev. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:06:50 </td>
   <td style="text-align:left;"> $QQQ I feel for anyone entering the market in 2022. 
Your likely to loose a bunch of money,  like the rest of us. 
 The worst year to enter in a long time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:06:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA You bears crack me up, u think that an invasion that&amp;#39;s been supposedly delayed so it doesn&amp;#39;t interfere with the OLYMPICS is actually gonna happen? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:06:25 </td>
   <td style="text-align:left;"> $QQQ $SPY the funny part is, a lot of you don’t know any different market. You only have experience with insanely overvalued pieces of shit that should’ve never been pumped so high. Now we’re normalizing and it looks like a crash but really it’s just the market telling us we were wrong to create so much artificial value. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:06:00 </td>
   <td style="text-align:left;"> $QQQ has a bad technical rating, but it does show a decent setup pattern. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:05:58 </td>
   <td style="text-align:left;"> I have said it for weeks.
Bullish on $BTC.X over 40K. 
40K and under?
$SQ $RBLX $COIN puts &amp;amp; $QQQ will be bearish too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:04:49 </td>
   <td style="text-align:left;"> $QQQ if russia attacks we wake up to 6% loss here, APPLE down AMZN down and MSFT down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:04:38 </td>
   <td style="text-align:left;"> $SPY $QQQ bears keep falling for this psyop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:03:49 </td>
   <td style="text-align:left;"> $SPY $QQQ going to lows of the day and the market isnt even open hahahahahahahahhaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:03:38 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.youtube.com/watch?v=wvRkV6DuZ7k 
 
Speaks like a real US President, if it were Trump it would be all about himself lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:03:01 </td>
   <td style="text-align:left;"> $QQQ $SPY wasn&amp;#39;t the invasion meant to have been this Weds? If we put the date forward every week for the rest of our lives maybe it will be true one day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:02:52 </td>
   <td style="text-align:left;"> $spy $qqq I’m coming for your fat foodies fighting with each other over Covid in the streets. I got a job for them. Defend Democracy for your stimulus. Bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:02:23 </td>
   <td style="text-align:left;"> $SPY that’s the trillionth DIX print above 45% this month but what’s more interesting is seeing GEX higher than yesterday. Everyone is now expecting a limit down. Limit downs come when everyone expects it. That’s not what a limit down is. Whatever downside we get next week I’d scale in. Just my .02 

$QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 07:01:34 </td>
   <td style="text-align:left;"> $SPY $QQQ  bulls  here are fake.. No sane person would buy while we&amp;#39;re in the start of an invasion, it&amp;#39;s gonna be bad, combine that with the rate hikes.. And we&amp;#39;re looking at an epic fall.

Bulls are just trying to get a little pump so they can short.. 😂

Get out while you can, no one wants to hold come next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:59:39 </td>
   <td style="text-align:left;"> $QQQ $SPY biden is hoping putin invades so he can have a scapegoat for this shitty economy and inflation problems </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:59:08 </td>
   <td style="text-align:left;"> $QQQ otherwise known as 78 weeks (18 months) of hell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:58:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $NVDA 
72 hours to travel from one boarder to another, 72 hours until Tuesday 
Pretty spot on if you ask me 
I smell…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:57:45 </td>
   <td style="text-align:left;"> $SPY $QQQ Ready for da nother 10 percent down boss. Lets go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:57:26 </td>
   <td style="text-align:left;"> $QQQ it will almost certainly drop another 12%. 300 coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:57:23 </td>
   <td style="text-align:left;"> $QQQ Biden might be trying some reverse psychology action on Putin $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:56:38 </td>
   <td style="text-align:left;"> $QQQ Seems like the only person who doesnt think Putin is going to invade Ukraine is:  
Putin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:56:18 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
Biden &amp;#39;Convinced&amp;#39; Putin Has Decided to Invade; Says Diplomacy Still Option 
 
https://www.investing.com/news/general/biden-convinced-putin-has-decided-to-invade-says-diplomacy-still-option-2767645 
 
A last warning by President Biden I guess if Putin wants a diplomatic solution. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:55:51 </td>
   <td style="text-align:left;"> $spy $qqq 
 
 
https://www.cnbc.com/2022/02/18/biden-believes-putin-has-decided-to-attack-ukraine-in-coming-days.html?__source=iosappshare%7Ccom.apple.UIKit.activity.PostToTwitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:54:39 </td>
   <td style="text-align:left;"> $QQQ Never in my 29 years have I seen a European country invade another, it’s really quite sad that so many people could stuff because of this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:54:29 </td>
   <td style="text-align:left;"> Dude 4K follower asked my opinion $PYPL &amp;amp; $AFRM. He was bullish 20 RSI whatever. Hated my comparison to Wheat, Silver, Gold. $QQQ still down after big tech beat -$FB. I always say this be careful of who you follow. We&amp;#39;re gonna find out who&amp;#39;s lucky only in bull markets or they have skill soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:53:53 </td>
   <td style="text-align:left;"> $QQQ all week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:53:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX 

My next week price targets.

1 - if attack happens this weekend, then spy opened @ 427 &amp;gt; 420 test during market hours next Monday, potentially breaking 420 support &amp;gt; 410&amp;gt; 400 … 

2 - no attack this weekend and Putin chooses diplomatic resolution, spy opens up at 438 , traces up to during market hours 446… 

3 - no attack &amp;amp; no diplomatic resolution… spy opens up at 432

👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:52:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $ROKU imagine being distracted from your family this weekend because you want to pump bearish and spam war. Instead of enjoying life you are plagued with desperation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:52:33 </td>
   <td style="text-align:left;"> $SPY this is getting UGLY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:51:36 </td>
   <td style="text-align:left;"> $SPY $QQQ  One Week after the Japanese attacked and DESTROYED Pearl Harbor! The market went back up!!!! This aint no 911 or Pearl Harbor. The truth is the market has priced in 7 rate hikes and a WAR with Russia! Im not trying to be a Bull here or a Bear, but we are about to have a face ripping roaring rally.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:51:30 </td>
   <td style="text-align:left;"> $QQQ $ARKK Cathie Wood is describing the flagship Innovation Fund as a &amp;quot;deep value portfolio&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:51:22 </td>
   <td style="text-align:left;"> $QQQ PERMABULLS TODAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:51:21 </td>
   <td style="text-align:left;"> $QQQ $SPY Ive been to Russia, they claimed all sorts of things we take as fact about their country are complete lies.  They told me it’s fine for people to be gay there and reports about them being persecuted is NATO propaganda.  Was disturbing to see brainwashing on that level but also changed my perspective on a lot of stuff...  Fwiw I doubt they go near Kyiv but I’d be shocked if they didn’t cross the border into those separatist republics by next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:51:07 </td>
   <td style="text-align:left;"> $QQQ $450.64 on Tuesday like if u agree </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:50:42 </td>
   <td style="text-align:left;"> $SPY $QQQ The Big BLUFF INVASION is 100% percent already baked IN  
🟢🟢🟢 Violent Rally comming soon 🦾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:49:39 </td>
   <td style="text-align:left;"> $SPY give me 429 next week. Should be a fun 4 day week 🏴‍☠️

$DIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:49:34 </td>
   <td style="text-align:left;"> $QQQ I think there’s a 91.69% chance we open -1% or worse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:49:34 </td>
   <td style="text-align:left;"> $QQQ The rich wants the market to fall.So they buy everything for cheap…… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:48:19 </td>
   <td style="text-align:left;"> $QQQ permabulls here want the war to finish over the weekend so it doesn’t interrupt their precious bull market don’t realize this is going down either way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:47:34 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ $NASDAQ 
Let’s go Brandon!!!
Now you lefty’s see what is happening!
The Left in this country is done!!
All you woke generation idiots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:47:34 </td>
   <td style="text-align:left;"> $SPY $QQQ sell off on no volume while index futures are closed. Pump war fear over weekend and pray. Bearish desperation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:47:17 </td>
   <td style="text-align:left;"> $SPY $QQQ Is supposed to be a long weekend for some celebration and now we have to worry about war 😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:47:11 </td>
   <td style="text-align:left;"> $QQQ no way sell off Tuesday to Ken from Citadel will fuck ur puts up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:47:10 </td>
   <td style="text-align:left;"> $QQQ bulls after they lose everything Tuesday 😹🥷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:47:04 </td>
   <td style="text-align:left;"> $dia $spy $iwm $qqq  $xle So annoying.  Why wouldnt Putin invade.  USA and Europe doing nothing at all militarily to dissuade him.  Literally, just saying take it if you want.  Grabbing land at this late stage in the global game is a major win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:46:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X risk off. Risk of recession if bear market accelerates. Smh, less than 2 years since the covid crash. Fuck you, Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:45:56 </td>
   <td style="text-align:left;"> $QQQ $SPY hopefully the invasion/war starts tonight and ends on Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:45:19 </td>
   <td style="text-align:left;"> $AMD $QQQ

My opinion doesn’t matter in the grand scheme of things but from the action so far in 2022, it is important to understand that the primary driver of the downtrend is not the threat of war. The war mind games are merely a catalyst. 

The uncertainty of the March decision is what is pinning stocks down. I can promise your that the relief rally from the “no war” news will also be sold off until the feds rate decision.

This is a sell the rumor ; buy the news event and so the real climb will only resume sometime after early April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:45:17 </td>
   <td style="text-align:left;"> $QQQ $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:44:11 </td>
   <td style="text-align:left;"> $SPY $QQQ a bunch of single men pumping war. Just to go to war themselves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:44:05 </td>
   <td style="text-align:left;"> $QQQ Growth stocks have reached semi sustainable range, it is time to get big Guys down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:43:48 </td>
   <td style="text-align:left;"> $FB $SPY $QQQ $MSFT Brandon confirmed we are going to war but market only down a BUCK! Dudes! The INVASION is 90 percent already BAKED IN!! Helloooooo? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:43:35 </td>
   <td style="text-align:left;"> $QQQ Nancy or Katherine or both at same time🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:43:04 </td>
   <td style="text-align:left;"> This week&amp;#39;s stock market analysis video has been published! 
 
📽️ https://www.youtube.com/watch?v=x0s4N5GqhcQ 
 
☑️Follow through selling in equities 
☑️Follow through buying in gold 
☑️VIX comfortable in the upper 20s 
 
Have a great weekend! 
 
$SPY $IWM $QQQ $VIX $TLT #stocks #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:42:42 </td>
   <td style="text-align:left;"> $SPY $QQQ 
I’m italian and watched live Biden’s talk. 

I think he’s really confused while Putin is a real strategist and won’t loose money with a war.

Scared about media manipulation and Brandon.

My portfolio tanked much more but I hope first no war for the Ukrainian people.

After all I’m bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:41:34 </td>
   <td style="text-align:left;"> $SPY $QQQ Qs selling off down .30% but it’s been slow ride down AH.  Still find it curious that Biden spoke after futures markets closed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:41:16 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:41:10 </td>
   <td style="text-align:left;"> $QQQ ouch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:38:57 </td>
   <td style="text-align:left;"> A well functioning stock market nowadays thanks to Fed:
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:38:22 </td>
   <td style="text-align:left;"> $QQQ nabbed puts into the close. Half the exposure from the shorts I printed earlier just in case I’m wrong. But the post Biden speech dump tells you must of what you need to know. 🪖⚠️💣🔻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:38:18 </td>
   <td style="text-align:left;"> $OCGN  hahaha 
$30 Target $$$$$
$spy $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:38:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $TQQQ $SQQQ ;; GREEN SUPPORT // RED RESISTANCE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:38:12 </td>
   <td style="text-align:left;"> $QQQ Nasdaq Composite Enters Death Cross, But Does it Matter?

https://www.thestreet.com/investing/nasdaq-death-cross </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:35:20 </td>
   <td style="text-align:left;"> $QQQ bears won, congratulations </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:34:42 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
There’s 0 doubt in my mind the earth is flat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:33:51 </td>
   <td style="text-align:left;"> $QQQ you guys just don&amp;#39;t get it.  This will continue to dump until midterm election campaigns begin.  Russia has NOTHING to do with it. 
 
The current administration has mismanaged monetary policy so badly that major corrections are needed.  The longer they draw this Russia thing out and the more they play up the threat, the more they can pretend Russia is the reason for the market&amp;#39;s poor performance and not their own bullshit policy mistakes.  Then, after a pullback to semi-sustainable levels, the markets can rebound during midterm campaigns and they can pretend they&amp;#39;re doing the right things again and get re-elected. 
 
Figure out the manipulation and you can make profit like me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:33:03 </td>
   <td style="text-align:left;"> I’m on it dude. I’m on… it. Would i do that for love? For Wall Street? To convey a message to the public? Yeah. Tell Michigan we’ll be OK. $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:31:27 </td>
   <td style="text-align:left;"> $QQQ 
...
https://www.nbcchicago.com/news/national-international/biden-convinced-putin-has-made-the-decision-to-invade-ukraine/2763985/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:30:39 </td>
   <td style="text-align:left;"> $ARKK $SHOP $TSLA $QQQ  Doom and gloom long weekend gonna be tough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:29:16 </td>
   <td style="text-align:left;"> $QQQ    

https://www.rt.com/russia/549924-lugansk-explosion-ukraine/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:29:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC Asia psyop is working on the markets with how bearish everyone is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:29:03 </td>
   <td style="text-align:left;"> $UVXY The war might start tonight and end by Monday night before markets open.  That&amp;#39;s why they chose a US/Canada long weekend.  EVERYONE  WINS!  
 
$SPX $QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:28:32 </td>
   <td style="text-align:left;"> $SPY what would you want them to say if they have to sell off the market for another 2 Trillions??... they have to come up with some bullshit stories when the covid scam no longer works!!!! $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:28:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 
Forget how shitty our president is and how corrupt this market is for a second. Forget that they have to find a headline to fit their narrative in order to control the market. This isn’t new. On a more serious note, I really feel for those living in Ukraine right now and all the families of the Russian soldiers who are just waiting on orders. The level of destruction if this moves forward will be tremendous. Watching the news and hearing about all the nuclear talk just gives me chills. I know this isn’t the first time but perhaps it’s because I’m a mother now it just hits me a little differently. Can you imagine being a parent and not knowing if you will be able to keep your child safe. At the moment, our problems of rising gas and food prices etc., seems so minuscule. Here we are crying about our calls and puts, stocks or whatever when other people are worrying about our lives. It’s stupid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:28:08 </td>
   <td style="text-align:left;"> $QQQ what y’all think will happen next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:27:54 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Jim C not to long was downing ARK Cathy Woods, this morning he was protecting her like a bag of money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:27:47 </td>
   <td style="text-align:left;"> $qqq $spy.   Folks, did you actually know that being a bull or bear isn’t morally good or bad and you don’t have to emotionally choose a side?    Trading is like passing or running to take what the defense gives you.   Be a good trader and take what the market gives you and stop being a loyal emotional wreck like the 90% of traders that fail.  This is a game, not a relationship.  Win the game. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:27:44 </td>
   <td style="text-align:left;"> $QQQ Get ready for the great chasm of a gap down Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:27:34 </td>
   <td style="text-align:left;"> $SPY $QQQ this is true dilemma. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:27:31 </td>
   <td style="text-align:left;"> $SPY $QQQ 

MAXAR SAYS LATEST IMAGES SHOW A LARGE, NEW HELICOPTER DEPLOYMENT (AT LEAST 50 HELICOPTERS) HAS ARRIVED AT LIDA AIRFIELD, IN NORTHWESTERN BELARUS

https://twitter.com/deitaone/status/1494799770115883008?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:27:13 </td>
   <td style="text-align:left;"> $SPY  $QQQ  $SPY   
WARNING: DELUSIONAL HOUSEWIFE DOUBLES DOWN ON -70% LOSING STRATEGY TO INCREASE LOSSES FOR NAIVE INVESTORS. 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:25:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL What ohhh NO !!! Everybody will throw is iphone in the toilet and never buy apple products on $AMZN and drink $KO because of war 😆😆😆.  …. Relax ! Enjoy weekend Green thusday 🟢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:25:01 </td>
   <td style="text-align:left;"> $SPY $QQQ Thanks to the US for protecting the whole world, we still have a relatively peaceful world. Without us, I can’t imagine how many bad things Russia and China would do to this world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:24:12 </td>
   <td style="text-align:left;"> $QQQ Is he talking about my long Position at 16k? Can someone ask? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:23:48 </td>
   <td style="text-align:left;"> $QQQ Information from a couple of weeks ago : Russia will invade in the next 48 hours

Information today: Russia will imvadeukraine in the next few days. 

Wheres the new information?. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:22:36 </td>
   <td style="text-align:left;"> $QQQ if you guys want another cold war the uk won&amp;#39;t be helping again that&amp;#39;s on you two </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:21:55 </td>
   <td style="text-align:left;"> $QQQ Whenever someone says, &amp;quot;the elites&amp;quot; I can&amp;#39;t help but think of this photo: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:21:55 </td>
   <td style="text-align:left;"> $SPY finally, a president I can get behind

$QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:21:34 </td>
   <td style="text-align:left;"> $QQQ the West is lost look at Canada, Europa. USA . China,Russia laugh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:21:34 </td>
   <td style="text-align:left;"> $QQQ why do we always need to poke our nose into this shit. Let focus on the USA for god sakes. Fuck Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:20:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $IWM 
Honestly, you know what, I’m sick and tired of seeing Biden every fucking day, Putin, just get it over with. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:20:34 </td>
   <td style="text-align:left;"> $QQQ 1 day chart has not look good in awhile. Ever since we broke the 2020 trend lines it’s been getting beat down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:20:16 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Joe Biden&amp;#39;s distraction and preoccupation of &amp;quot;war with Russia&amp;quot; is top-level BOOMER-CRINGE! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:19:58 </td>
   <td style="text-align:left;"> $QQQ Besides record Inflation, and everything else. 
Biden decides to threaten a Russian baddassssssssss. 
 
Maybe: Just Maybe. 
He should deal with the bigger crisis at home. 
You dunbb Fck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:19:55 </td>
   <td style="text-align:left;"> $SPY $QQQ unreal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:19:50 </td>
   <td style="text-align:left;"> $BTC.X biden &amp;quot;we have significant intelligence capabilities&amp;quot; wtf then walks away thanks for clarifying why you think war is imminent you dolt $SPY $QQQ $ETH.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:18:55 </td>
   <td style="text-align:left;"> $SPY $QQQ democrats know they are doomed so they will crush the market for all their friends to buy low. Same what happened with Bush. A drowning man with drag you down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:18:24 </td>
   <td style="text-align:left;"> $QQQ $SPY $DKNG $LCID buy the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:17:42 </td>
   <td style="text-align:left;"> $QQQ major sell off commit next week.. $SPY .. $TSLA $AAPL $AMZN … War is imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:16:55 </td>
   <td style="text-align:left;"> $QQQ elites run this world and don’t want peace. They push war propaganda and want order out of chaos. They want to reform a one world order after world war 3 breaks out and it’s sad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:16:29 </td>
   <td style="text-align:left;"> $QQQ $SPY Reporter: To be clear, you are convinced that  putin is going to invade ukraine, is that what you just said? 
Biden: Yes I did, yes 
Reporter: So is diplomacy off the table? 
Biden: No...(mumbling)...until he does diplomacy is a possibility 
Reporter: what reason do you have to believe he is planning to invade 
Biden: We have a significant intelligence capability, thank you very much (leaves) 
 
what a gigachad move honestly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:16:15 </td>
   <td style="text-align:left;"> $QQQ Let Biden present after AH. He spoke too early. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:15:58 </td>
   <td style="text-align:left;"> $UVXY $SPY $gld $qqq LOL they pumping so hard that there&amp;#39;s going to be war, that means for sure nothing will happen and Biden will take the credit for saving us! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:15:46 </td>
   <td style="text-align:left;"> $SPY how long russia’s invade plan work out the broader? $QQQ , can Russia move on with invasion or not? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:15:31 </td>
   <td style="text-align:left;"> Let&amp;#39;s get you ready for this week. Drop your chart request below $SPY $AAPL $QQQ $C $TSLA  #investing 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:15:29 </td>
   <td style="text-align:left;"> $QQQ Forget money for a minute, I pray for the people of Ukraine. I didn’t think anything would happen and it still might not but it’s not looks good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:15:14 </td>
   <td style="text-align:left;"> $SPY $QQQ Already saw this movie with Hoffman and De Niro </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:15:03 </td>
   <td style="text-align:left;"> $QQQ Biden is just a plain Moron </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:14:54 </td>
   <td style="text-align:left;"> $SPY $QQQ very soon you’ll never hear about Russia crap again and they’ll have something new. Maybe they’ll change it back to Covid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:14:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA Biden trying to do reverse psychology / 4D chess or something? 🤦🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:14:32 </td>
   <td style="text-align:left;"> $QQQ Biden wants to screw up the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:14:20 </td>
   <td style="text-align:left;"> $QQQ scaling into this market with a ton of cash is plain fun. Buy dividend stocks at all time highs? Fuck no I&amp;#39;m scaling into US and CAD tech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:14:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA at least 3 more years of this bs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:12:33 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ After what the President said, ignoring the dynamics and staying the course, as if all is fine is definitely madness, i believe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:11:55 </td>
   <td style="text-align:left;"> $SPY $QQQ this shit is beyond scripted. He knows if he said this during the market this would be at $490 rn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:11:52 </td>
   <td style="text-align:left;"> $SPY $QQQ After the Olympic, China is gonna set two drills in Taiwan Straight and South China Sea….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:11:44 </td>
   <td style="text-align:left;"> $QQQ its the year 2025, according to officials, putin wil invade ukraine in the coming days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:11:42 </td>
   <td style="text-align:left;"> $QQQ LFG brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:11:32 </td>
   <td style="text-align:left;"> $QQQ we have all been guilty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:10:39 </td>
   <td style="text-align:left;"> $SPY $QQQ Can&amp;#39;t believe some comments here, some are actually hoping for war and even hoping Putin bombing Ukraine and so they can make money on their puts/shorts. Do you know it could kill people? It would be some bloody and dirty money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:10:37 </td>
   <td style="text-align:left;"> $QQQ Biden wants war so bad I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:10:35 </td>
   <td style="text-align:left;"> $QQQ $SPY  what is the best thing to do when approval rating are rock bottom?? Go to war!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:09:54 </td>
   <td style="text-align:left;"> $QQQ $SPY Biden: War is imminent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:09:11 </td>
   <td style="text-align:left;"> $QQQ oh shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:09:10 </td>
   <td style="text-align:left;"> $SPY people cheering a potential nuclear war because it&amp;#39;s going to make their short positions &amp;amp; puts print is honestly sickening. $BTC $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:08:34 </td>
   <td style="text-align:left;"> $QQQ $BTC.X $DOW $DWAC If you hate Bill Gates, smash your PC and refuse to use any device that runs windows! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:08:19 </td>
   <td style="text-align:left;"> $spy $qqq anyone pumping war wants to get drafted to defend Ukraine. Never trading again if you act this way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:08:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $DWAC  $CFVI  starting to look more and more like another Democrat  lead Russia hoax </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:07:55 </td>
   <td style="text-align:left;"> $BB $SPY $DIA $QQQ if I were blackout fuckin drunk and took the podium— I’d still speak more cohesively than puppet sock Biden. what a fuckin mess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:07:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY I just want to personally thank Putin for making me money. All I need him to do is drop a bomb on ukraine and kick off the war this weekend and I will never have to work again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:07:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA Biden the anti-Donny Pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:07:15 </td>
   <td style="text-align:left;"> $QQQ ........and next week he&amp;#39;ll say I convinced Putin not to invade and saved everyone.....go fuck yourself Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:07:14 </td>
   <td style="text-align:left;"> $QQQ When Biden speaks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:06:55 </td>
   <td style="text-align:left;"> $SPY - $QQQ : </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:06:22 </td>
   <td style="text-align:left;"> $GOLD i personally think Biden shows strength in his candid and timely discussions on ukraine.   I hope diplomacy wins out.  More uncertainty and doubt is not what the world needs after covid. $SPY $QQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:06:21 </td>
   <td style="text-align:left;"> 🤡 Biden 
. 
It’s like they want Russia to invade..
$SPY $QQQ $TSLA $BTC.X $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:06:19 </td>
   <td style="text-align:left;"> $SPY $QQQ biden: they lie, we tell truth 🤡🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:06:15 </td>
   <td style="text-align:left;"> $DKNG $ROKU $SPY $QQQ $IWM  
 
https://www.financegreater.com/post/managing-a-bearish-market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:06:12 </td>
   <td style="text-align:left;"> $QQQ welp, seems earth will be obliterated after all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:06:03 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM  
 
The U.S. government likely created this war distraction rhetoric to provide a convenient scapegoat for the significant problems its people are facing at home with high inflation, looming recession, rate hikes, quantitative tapering and general civil unrest.   
 
This way, the U.S. government thinks it can direct all the internal discontentment towards an external enemy like in Orwell&amp;#39;s 1984, except...it&amp;#39;s not working and people are seeing through it :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:05:47 </td>
   <td style="text-align:left;"> $QQQ what a 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:05:46 </td>
   <td style="text-align:left;"> $QQQ he tells in every meeting the same. Inviting Ukraine. On 16th February no </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:05:45 </td>
   <td style="text-align:left;"> $QQQ we are not in a bull market anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:05:45 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Reporters talking shit in the background </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:05:41 </td>
   <td style="text-align:left;"> $QQQ Biden confirm Ukraine invasion is imminent..$280 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:05:35 </td>
   <td style="text-align:left;"> $SPY $QQQ take home message: we good, other guy bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:05:24 </td>
   <td style="text-align:left;"> $SPY $QQQ biden showed up a hour late and talked for 5 minutes to say “we are certain Russia will attack”…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:05:22 </td>
   <td style="text-align:left;"> $SPY $QQQ oh boy… 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:05:16 </td>
   <td style="text-align:left;"> $QQQ Biden is so full of shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:04:40 </td>
   <td style="text-align:left;"> $QQQ yall hear the reporters laugh at him when his earpiece started ringing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:04:29 </td>
   <td style="text-align:left;"> $QQQ $SPY welp looks like Brandon just doomed the Market… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:04:13 </td>
   <td style="text-align:left;"> $QQQ curling has save the world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:04:09 </td>
   <td style="text-align:left;"> $QQQ Biden the last thing you say is he’s going to invade 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:04:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $TQQQ $DIA 

Am not going to trust someone negotiating with talban in Qatar . And pulling out of Afghanistan like this and u think with this weak president u want to face Putin Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:04:02 </td>
   <td style="text-align:left;"> $QQQ Thank you Biden for this pos market. There goes my savings and Walt retirement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:04:01 </td>
   <td style="text-align:left;"> $QQQ oh shit Joe said too much... riiiiiiip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:03:58 </td>
   <td style="text-align:left;"> $QQQ Tank it Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:03:57 </td>
   <td style="text-align:left;"> $QQQ hahahahahhaha latexcf502321f905ab93b307c5a6f3926d9fDKNG PUTS on ER play 0.31➡️1.15 370% GAINS 🔥🤯

$TSLA CALLS 0.40➡️1.4 350% GAINS 🤑💵

OVER 700% GAINS IN ONE DAY 🙌

JOIN DISCORD LINK IN BIO 🕺

 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:03:29 </td>
   <td style="text-align:left;"> $SPY $QQQ LOL an hour late just for that?? The charade continues.  That was weak for put war bettors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-19 06:03:28 </td>
   <td style="text-align:left;"> $QQQ WW3 interrupted by curling, luckily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:49:56 </td>
   <td style="text-align:left;"> $S  $FB  $AAPL Earnings reports today before the markets open&amp;quot;  room.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:46:20 </td>
   <td style="text-align:left;"> $AAPL 
Biden SUX !! He’s propagating war with Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:45:05 </td>
   <td style="text-align:left;"> $AAPL $AMZN $MSFT  
If you really want to make a huge profit on stock trading. Then this community is for you &amp;gt; dsc.gg/stock_alerts 
 
#2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:38:09 </td>
   <td style="text-align:left;"> $AAPL come on get to 158 and then get your ass back to 175 !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:36:52 </td>
   <td style="text-align:left;"> $AAPL  who’s long through the long weekend? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:36:35 </td>
   <td style="text-align:left;"> $aapl its gonna be a nothing burger when this inevitably goes back above 170 after nothing happens over the weekend lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:31:51 </td>
   <td style="text-align:left;"> $AAPL $160.00. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:27:32 </td>
   <td style="text-align:left;"> $AAPL how to steal shares from retail 

Sell bulk of shares at market open and put pressure on price through the session , so every one keeps selling for loss in the down trend 

MM accumulates the at lower price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:25:22 </td>
   <td style="text-align:left;"> $AMZN $TSLA $AAPL
BIDEN: Only America has right to Bomb anywhere in the world.. Iraq, Afghanistan,Vietnam,Korea..
Only we can kill ppl.. and use our military..come to negotiation table just to hear that your demand will
Not be met.. when you come here for negotiations.. we will put u behind bars or kill u Putin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:23:01 </td>
   <td style="text-align:left;"> $AAPL Grocery List: buy apples with every paystub. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:20:01 </td>
   <td style="text-align:left;"> 📊 $AAPL 
🚀 94% Profitable 
🤖 AI-Driven Machine Learning 
🏆 SwingTradePro Strategy 
Join Our Premium Room For Live Trade Alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:19:54 </td>
   <td style="text-align:left;"> $AAPL $MSFT  - Get yourself some Apple $125 Puts for March 18th and MSFT Puts $200 for March 18th. You’ll thank me later. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:17:20 </td>
   <td style="text-align:left;"> $AAPL will see 170 Tuesday watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:14:18 </td>
   <td style="text-align:left;"> This is Stocktwits all year long 😂😂😂

$spy $tsla $aapl $arkk $btc.x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:10:49 </td>
   <td style="text-align:left;"> $VERB $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:08:09 </td>
   <td style="text-align:left;"> $AAPL under 160 next week - u better hope 158 holds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:07:59 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY  I have reasons to believe Potato Joe doesn&amp;#39;t even know he is a president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:04:47 </td>
   <td style="text-align:left;"> $AAPL fuck those dictators </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:04:19 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 08:00:46 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY $IWM - Gosh, these lunatics are actually pushing for war. Who’s gonna suffer? The people. Like always. The people always suffer and the leaders just kick back. Sad people protest vaccine mandates but not WWIII with Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:58:23 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #3 ticker with sweep activity where institutions are trading options urgently with 40.7K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:58:01 </td>
   <td style="text-align:left;"> $ROKU bulls are lucky this is not following the entire market or tech stocks like $AAPL going down a/h due to Russian tensions. This will definitely go down on Tuesday. Put/ls will print. 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:57:48 </td>
   <td style="text-align:left;"> $FB more blood coming.. sell ur stocks .. cash only.. $SPY $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:47:10 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL that wasn’t even that bad. Nice and controlled. How about a 2% down day? 3%?  You know they’re coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:41:52 </td>
   <td style="text-align:left;"> $AAPL maybe there’ll be a “buy the news” event when Russia invades. $DIS $ASO $GM $CRM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:41:14 </td>
   <td style="text-align:left;"> $NVDA $SOXL $AAPL $TSLA $ABNB 
👇  I am Fcking Selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:39:39 </td>
   <td style="text-align:left;"> $AAPL ha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:38:38 </td>
   <td style="text-align:left;"> $AAPL they have to bring it down those putz still holding it up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:34:25 </td>
   <td style="text-align:left;"> $AAPL are they taking it down to 155? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:27:16 </td>
   <td style="text-align:left;"> $AAPL down a full dollar ah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:25:08 </td>
   <td style="text-align:left;"> $SPY 24th boy blinken meeting with Russians $AMD $NVDA $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:20:29 </td>
   <td style="text-align:left;"> $AAPL https://www.idropnews.com/news/apple-partner-luxshare-invests-in-ev-production-as-apple-car-manufacturer-announcement-inches-closer/180526/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:19:42 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/UTAjOmBvaZE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:18:23 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOGL these 3 have put the indexes on their back the last 2 years. The only way the indexes roll over is if they fall. Safe money has been hiding out in these names. I’m long 2 of them and will buy all substantial dips if they come. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:13:05 </td>
   <td style="text-align:left;"> $PANW $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:11:11 </td>
   <td style="text-align:left;"> $AAPL you guys hated my targets when we traded above 175. I forgive you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:11:11 </td>
   <td style="text-align:left;"> $AAPL stock analysis based on today&amp;#39;s closing price 

#apple 

https://youtu.be/uOmNQuLhX4w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:10:56 </td>
   <td style="text-align:left;"> $AAPL held support so nothing to worry about </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:10:29 </td>
   <td style="text-align:left;"> $AAPL BURNNN BABY BURNNNN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:09:42 </td>
   <td style="text-align:left;"> $AAPL I’m so mad that I never follow my gut on anything. You could of looked at Bolsonaros eyes when he left his meeting with Putin this week and know that the invasion was taking place. I could tell just by his eyes. Hope he does it Wednesday so we can all get out of this mess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:09:31 </td>
   <td style="text-align:left;"> $AAPL - Ouch! After hours for almost every ticker is down. Looks like next week we move lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:09:30 </td>
   <td style="text-align:left;"> $SPY $AAPL $GOOG $AMZN $TSLA last ones without the monster sell offs. Will not be immune to the valuation crunch. Load up shorts while you can. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:08:47 </td>
   <td style="text-align:left;"> $SOFI $TSLA latexdc33c2aea54c8a4ba39ad9d66ff26bc5AAPL 170P @ 2.03&amp;gt;3.45 (+70%)  PT3🎯 
$MRNA  148C @ 2.09&amp;gt;3.3 (+58%)   PT2🔥 
MRNA 145P @ 1.6&amp;gt;2.46 (+54%) PT2🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:03:36 </td>
   <td style="text-align:left;"> $AAPL I knew that Anthony blinken meeting was complete bs. Should of followed my gut and listened to my sources on the ground. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 07:03:34 </td>
   <td style="text-align:left;"> $AAPL Where are all those Biden lovers? Kamala and her pearls and converse ain’t doing shit! True criminals man. Off with their heads! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:59:40 </td>
   <td style="text-align:left;"> $SPY $AMD $TSLA $AMC $AAPL Bring back my orange Daddy! He likes stonks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:59:02 </td>
   <td style="text-align:left;"> $AAPL how fickle is our market when one country doing something stupid can affect it this much? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:56:45 </td>
   <td style="text-align:left;"> $AAPL People selling AHrs. They don&amp;#39;t want to hold over the weekend with the Ukraine Bullshit going on. I don&amp;#39;t blame them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:55:05 </td>
   <td style="text-align:left;"> $AAPL There will not be a war, lol. The sheep followers are being roped in by the media again. How dumb.   
  
We still have an issue with inflation though, however it can be rectified with careful action. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:49:27 </td>
   <td style="text-align:left;"> $AAPL So yall bulls just gonna ignore this...?

https://m.investing.com/news/stock-market-news/iss-supports-apple-shareholder-proposal-on-forced-labor-2767616 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:49:15 </td>
   <td style="text-align:left;"> How DoorDash Became the Biggest Surprise of Earnings Season  $PTON $MSFT $AAPL $DASH $ZM 

https://newsfilter.io/a/0a68719d57f0bec6aa06d3f862815a03 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:46:23 </td>
   <td style="text-align:left;"> Intel $INTC Stock Sinks After Pat Gelsinger Details 4-Year Comeback Plan

$AAPL $TSLA $AMZN 

“The other problem, according to Rasgon, is that Intel faces risk in spending a lot of money while facing strong competition from the likes of $AMD and others. Rasgon said Intel’s data center guidance indicated that the company would “keep losing share for the next several years,” and he noted that Intel delayed Granite Rapids, a new Xeon CPU it said would provide “unquestioned leadership,” by one year to 2024. https://www.crn.com/news/components-peripherals/intel-stock-sinks-after-pat-gelsinger-details-4-year-comeback-plan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:46:15 </td>
   <td style="text-align:left;"> $AAPL $177 Tuesday, book it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:45:38 </td>
   <td style="text-align:left;"> $SPY $AAPL hammered puts. Second week into option trading. Figured now is a could time to leverage my long positions. Weird feeling - PUTs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:45:23 </td>
   <td style="text-align:left;"> $TQQQ $SPY $NASDAQ $AAPL Best just to sit on cash the next 8 to 12 months. We bout to go to war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:45:13 </td>
   <td style="text-align:left;"> $AAPL bankruptcy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:45:03 </td>
   <td style="text-align:left;"> $SPY $SOXL $TQQQ $AAPL $MSFT 
Today we hit last dip support of SPY $431.
Let’s see whether it will be broken with any bad Russian or Fed news during weekend.
If we broke, GAME OVER. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:40:27 </td>
   <td style="text-align:left;"> 2/22 Watch List.🪰

Part 1.🌚

1) $GENI 
2) $PLTK 
3) $AAPL 
4) $MGY 
5) $NTAP 

Forces Working.🪵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:36:29 </td>
   <td style="text-align:left;"> $AAPL $200 by end of the month. Wahoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:36:08 </td>
   <td style="text-align:left;"> $AAPL Weekly chart 
♦ Solid rejection at res zone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:34:00 </td>
   <td style="text-align:left;"> $AAPL is currently trading in the upper part of its 52 week range, outperforming the market. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:31:00 </td>
   <td style="text-align:left;"> $AAPL Reuters article literaly accusing apple of participating in slavery practices...no way they are literally trying to tank this stock.

https://www.msn.com/en-us/money/companies/iss-supports-apple-shareholder-proposal-on-forced </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:30:53 </td>
   <td style="text-align:left;"> $AAPL sold all. Situation becoming real. Everyone have great weekend. No upside until Putin declare victory or defeat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:30:10 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-18 Largest Trades Data: 
https://www.youtube.com/watch?v=gmS_wGOpdhM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:30:09 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG stop this American media bs!!! They don’t know wtf they saying and making the market crash over nothing!! Close your eyes in 6 months when all this bs is over will be at all time highs! Load up on these dips! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:28:32 </td>
   <td style="text-align:left;"> $SPY what would you want them to say if they have to sell off the market for another 2 Trillions??... they have to come up with some bullshit stories when the covid scam no longer works!!!! $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:28:30 </td>
   <td style="text-align:left;"> $AAPL sweet Jesus… News just said they flew in 50 helicopters and a Mobil hospital along the border 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:27:49 </td>
   <td style="text-align:left;"> $AAPL market has become short paradise. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:26:42 </td>
   <td style="text-align:left;"> $AAPL will Ukrainian President leave the country like Afghan man????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:26:26 </td>
   <td style="text-align:left;"> How will this affect the market? $AAPL in Uptrend: RSI indicator exits oversold zone. View odds for this and other indicators: https://srnk.us/go/3426367 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:26:07 </td>
   <td style="text-align:left;"> $AAPL How many BEARS are holding over the 3 day weekend??✋ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:25:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL What ohhh NO !!! Everybody will throw is iphone in the toilet and never buy apple products on $AMZN and drink $KO because of war 😆😆😆.  …. Relax ! Enjoy weekend Green thusday 🟢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:22:18 </td>
   <td style="text-align:left;"> $AAPL bulls are absolutely fd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:22:09 </td>
   <td style="text-align:left;"> $aapl ofc it tanks when the babboon in chief talks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:19:38 </td>
   <td style="text-align:left;"> $AAPL My decision is made I&amp;#39;m holding my shorts through the weekend 🤞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:19:37 </td>
   <td style="text-align:left;"> $AAPL My trading style be like...🤑🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:19:12 </td>
   <td style="text-align:left;"> $AAPL steady decline after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:17:42 </td>
   <td style="text-align:left;"> $QQQ major sell off commit next week.. $SPY .. $TSLA $AAPL $AMZN … War is imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:17:28 </td>
   <td style="text-align:left;"> $GOOGL dumb as Biden is trying to instigate a war fucking  idiot $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:15:31 </td>
   <td style="text-align:left;"> Let&amp;#39;s get you ready for this week. Drop your chart request below $SPY $AAPL $QQQ $C $TSLA  #investing 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:14:21 </td>
   <td style="text-align:left;"> $AAPL Biden saying “Putin has made the decision to invade” is basically saying GO FOR IT…. What a crock of shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:12:05 </td>
   <td style="text-align:left;"> $AAPL Stock Trading Ideas | 10 Trades executed, trade Profitability of 80%, and Profit Factor of 7. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:09:03 </td>
   <td style="text-align:left;"> $AAPL these idiots are making it so hard to play options. Only day trade… you can’t hold anything in this market, they flip flop too much these incompetent idiots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:07:38 </td>
   <td style="text-align:left;"> $UVXY   Is this true.  Russia ☠️☠️☠️🚀. $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:06:39 </td>
   <td style="text-align:left;"> $AAPL $MSFT $FB $AMZN Serious question...The Don would like to know what people here think is the downside in the markets if we see a low to moderate level of ground conflict in Russia.  Thanks in advance for your opinions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:06:21 </td>
   <td style="text-align:left;"> 🤡 Biden 
. 
It’s like they want Russia to invade..
$SPY $QQQ $TSLA $BTC.X $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:06:19 </td>
   <td style="text-align:left;"> $AAPL unloaded half for security. Expect major war over the weekend! Fuck Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:05:54 </td>
   <td style="text-align:left;"> $SPY WTF WAS THAT JOE!!! U LEFT IN 3 mins $AMD $NVDA $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:05:11 </td>
   <td style="text-align:left;"> $AAPL Biden left us with shit, these people are the most incompetent group of clowns I’ve ever seen. One day they’re invading the next day there’re not. At this point it’s just market manipulation and it’s becoming ridiculous. Watch now Tuesday they’ll say they have a meeting and then cancel it afterhours to Wednesday. It’s becoming overplayed. Just be real with us and quit the BS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:04:54 </td>
   <td style="text-align:left;"> $AAPL he absolutely has no idea what he’s saying lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:04:40 </td>
   <td style="text-align:left;"> $AAPL 

Biden is a joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:04:36 </td>
   <td style="text-align:left;"> $AAPL ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:03:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMD Every word he’s saying is on the teleprompter, and he said the term ‘war’ more than a handful of times.  These warhawk pos’s in this administration are such scum of the earth.

Putin literally has said nothing or done nothing to have done anything indicating an invasion, agreed to a meeting next week, and our president says “if he invaded before then, he will have shut the door on diplomacy.”  This is seriously sickening to watch him try and vilify a military drill.  It was PLANNED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:02:50 </td>
   <td style="text-align:left;"> $AAPL he&amp;#39;s already made his decisions people straight out of bidens mouth referring to putin. He&amp;#39;s already said he believes it&amp;#39;s imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:01:46 </td>
   <td style="text-align:left;"> $AAPL I’m getting sick and tired of weaving through this Russia BS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 06:01:16 </td>
   <td style="text-align:left;"> $AAPL FML </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:58:41 </td>
   <td style="text-align:left;"> $AAPL oh shit that means war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:57:27 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : ISS supports Apple shareholder proposal on forced labor https://www.stck.pro/news/AAPL/23114235 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:55:53 </td>
   <td style="text-align:left;"> $SPY I swear if this mfkr doesn&amp;#39;t either invade or goes home in the next 3 days........ 🙄
$QQQ $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:55:43 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
sorry to anyone following me but I am reposting this. people need to understand what is REALLY going on... 
  
  
&amp;quot;So sick of this bullshit &amp;quot;war with Russia&amp;quot; narrative to distract from the fact that the free money gig is up.  
  
FED pulling the plug on free money is the only thing that matters to the market!&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:55:03 </td>
   <td style="text-align:left;"> $SPY $AMD $AAPL $NVDA $TSLA 
Wheres joe? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:51:03 </td>
   <td style="text-align:left;"> $AAPL A trillion dollar company with a sub $200 stock? 
Give this thing a few years and its looking like a trillion dollar opportunity ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:50:34 </td>
   <td style="text-align:left;"> $AAPL 2 minute warning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:50:24 </td>
   <td style="text-align:left;"> NASDAQ Bubble  =another Down Leg  
$QQQ $AAPL $AMD $SPY $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:49:01 </td>
   <td style="text-align:left;"> $AAPL anyone think $175 calls print heavy next week? I have 23 and thinking of buying more Tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:45:11 </td>
   <td style="text-align:left;"> $AAPL  
https://www.stocktargetadvisor.com/blog/analysts-rates-apple-inc-aaplnsd-with-a-strong-buy-210-target/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:42:48 </td>
   <td style="text-align:left;"> $AAPL this is another buying opportunity! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:40:38 </td>
   <td style="text-align:left;"> $AAPL on Tuesday morning someone will lit some fire crackers in Ukraine and Bloomberg will report That the war has officially started </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:40:33 </td>
   <td style="text-align:left;"> $SPY  $QQQ $AAPL  
WARNING: RECKLESS HOUSEWIFE RACKS UP LOSSES OF -70% OR MORE FOR NAIVE INVESTORS 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:37:17 </td>
   <td style="text-align:left;"> $SPY $AMZN $AAPL latexbacb98a875e955024d85fddb79279b4fAAPL 135-140
$MSFT 240

And then we can talk about value in the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:35:23 </td>
   <td style="text-align:left;"> $AMD $AAPL $MSFT $TSLA It&amp;#39;s 4PM. Isn&amp;#39;t Biden suppose to be talking about Russia/Ukraine right now? Get off your ass Mr. President, give us the all important update </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:34:34 </td>
   <td style="text-align:left;"> $SPY Always remember 2 things, Traders at HFs aren&amp;#39;t using their own Money so selling out &amp;amp; getting back in is not a big deal, 2nd &amp;amp; most important, Wall St does not lead, they dont have courage so on a day like this they have no reason to take any risk, 
 
Retail can use that if they&amp;#39;re smart about it, we can move faster when we change out minds but if you expect WS to lead you think of $tsla &amp;amp; how many years is was stuck before WS really jumped in. 
 
Wall St&amp;#39;s motto is &amp;quot;Im scared, you go first&amp;quot; 
 
$aapl $amzn $baba </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:34:27 </td>
   <td style="text-align:left;"> $AAPL mother fuckers clearing options. Scammers should be investigated! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:33:42 </td>
   <td style="text-align:left;"> $AAPL hopefully this damn meeting doesn’t get delayed and all the calls get screwed over only to have a surprise makeup meeting next Saturday and a huge selloff Monday. Lol… but on a real note, the meeting next week is EXTREMELY bullish regardless of inflation. It sounds weird I know but it’ll see a huge bounce if we get anything positive out of that meeting so hoping and praying. I gotta stop doing these long term gamble plays and just stick to daily market reversals. I always go against my own rule but I think it’ll pay big so let’s see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:32:44 </td>
   <td style="text-align:left;"> $NVDA $TSLA $CRM $AAPL 
Biden better not F this shit up, and now that Xi &amp;amp; Putin loaded up they can qualm the war rhetoric </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:29:47 </td>
   <td style="text-align:left;"> $SPY This is why I don&amp;#39;t trust politics. If what Biden has to say is so important, to the point to has a conference, why wait until market closes? Who&amp;#39;s interest are they really looking out for? 🤔
$QQQ $AAPL $AMD $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:28:58 </td>
   <td style="text-align:left;"> $AAPL what’s the next catalyst to take down the market once this Russia shit is settled? That’s the next question. Seems like we have something new all the time for the last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:25:08 </td>
   <td style="text-align:left;"> You think Biden is going to crash the stock market going into President day weekend? …  
🤡
 $SPY $QQQ $BTC.X $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:23:59 </td>
   <td style="text-align:left;"> $TSLA $AAPL Is this biden? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:22:51 </td>
   <td style="text-align:left;"> $AAPL that&amp;#39;s a lonely looking podium </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:22:50 </td>
   <td style="text-align:left;"> Thank God the markets closed before #DementiaJoe speaks. Heaven help us with this pinhead running the free world! 🙏 
 
$AAPL $DJIA $QQQ $SPY $TSLA #Bidenflation #Ukraine #Biden #BidenIsAFailure #LiberalismIsTheRealPandemic #Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:20:38 </td>
   <td style="text-align:left;"> $AAPL $NVDA $PYPL Gonna gap up HUGE if no war… watch!

https://www.aljazeera.com/news/2022/2/18/g7-says-ready-for-serious-dialogue-with-russia-on-ukraine-live </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:18:20 </td>
   <td style="text-align:left;"> $AAPL This market is wild...Up, down, sideways, no one knows. Close your eyes and throw a dart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:17:14 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Inc falls as tension grips growth stocks – Key level(s) to watch https://www.stck.pro/news/AAPL/23113014 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:13:01 </td>
   <td style="text-align:left;"> $SPY $AAPL I&amp;#39;m about to just delete the app at this point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:11:56 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPL what a choppy day and week of trading. Fed, Russia/Ukraine, and a 3 day weekend coming up. It was tough, but I think things will rebound on Tuesday... unless we see some major event over the weekend. What are your thoughts? 
 
I&amp;#39;ll be enjoying some time off but keeping an eye on news social sentiment over the next few days. This will help guide my decisions when markets open next week. This is what I use to keep an eye on things, especially when markets are closed.  
 
https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=pw_20220218 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:11:14 </td>
   <td style="text-align:left;"> $AAPL is this 10 straight weeks now if no indexes green? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:10:19 </td>
   <td style="text-align:left;"> $AAPL ST Ticker is wrong. The closing price was 167.30. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:09:06 </td>
   <td style="text-align:left;"> $AAPL $NVDA $PYPL Put in the work!

https://www.instagram.com/reel/CaH-KCxDe9X/?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:08:50 </td>
   <td style="text-align:left;"> $AAPL  Hey!!!, don&amp;#39;t tell me it&amp;#39;s RAINING!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:07:32 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

THIS IS OUR MARKET NOW BULLS

🐻 HAVE 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:06:01 </td>
   <td style="text-align:left;"> Good day,good day indeed. Many scalp trades long and short vol trades completed. Long $AMZN from $3061 to $308 short $VXX twice on the day, 3 long $TQQQ scalps, $DIS and $AAPL scalps long as well.  
 
Everyone takes a drawdown, but this is how you stay active and mitigate the drawdowns with a defined trading plan 1/2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:05:01 </td>
   <td style="text-align:left;"> $AAPL YOLO 🙈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:04:40 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

I’m gonna hodl my poots may the fud be with us bears.

🐻 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:03:10 </td>
   <td style="text-align:left;"> $AAPL GG bears. We ll get you next week. Markets closed, no need to hate each other now! Happy presidents day to the American bros! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:02:21 </td>
   <td style="text-align:left;"> $aapl i dont give a fuck, this is a shakeout. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:01:40 </td>
   <td style="text-align:left;"> $AAPL I feel blessed I got a nice discount today. Always sleep sound with 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:01:12 </td>
   <td style="text-align:left;"> $AAPL switched to calls. I honestly think they’ll absolutely print next week. They’ll meet with Russia on Wednesday and this thing will rocket $15. I know it doesn’t make sense and it goes against inflation but this is how the markets reacting so you have to go with it not against it. I’d normally be bearish but bullish with Russia meeting next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 05:01:07 </td>
   <td style="text-align:left;"> $AAPL world coming to an end and not even a 1% down day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:59:20 </td>
   <td style="text-align:left;"> $AAPL Bear Byden strikes again, LOWER  lows Joe.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:59:16 </td>
   <td style="text-align:left;"> $BA if you haven&amp;#39;t yet go watch the documentary. It&amp;#39;s good. $AAPL $SPY $UAL $AAL https://youtu.be/vt-IJkUbAxY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:58:48 </td>
   <td style="text-align:left;"> “BREAKING: Sources tell @FoxBusiness @TheJusticeDept block-trading investigation initially focusing on big Wall Street firms NOT clients such as @citsecurities. Investigation will mirror a typical insider trading probe &amp;amp; spread to clients IF DOJ can show payoffs for info on trades~”

$AMD ↗️ $AAPL $TSLA $MSFT $AMZN  https://twitter.com/cgasparino/status/1494695082204803076?s=12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:57:34 </td>
   <td style="text-align:left;"> $AAPL man putz just holding rock solid, this close is gonna be strange, popcorn pls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:57:10 </td>
   <td style="text-align:left;"> $BA you should all watch it. Just came out. Fucking crazzzy. $SPY $AAPL $UAL $AAL  https://youtu.be/vt-IJkUbAxY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:54:16 </td>
   <td style="text-align:left;"> $AAPL LETS GOO!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:54:15 </td>
   <td style="text-align:left;"> $NNDM $PLTR my thesis is we won&amp;#39;t have any recovery until those shits like $AAPL and $MSFT show that they don&amp;#39;t really actually have any ability to grow much further and are struggling with supply chains and consumer demand...i think that will happen later this year... I do think it&amp;#39;s really stupid to be buying apple and Microsoft now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:52:52 </td>
   <td style="text-align:left;"> $AAPL Let&amp;#39;s Go Brandon, totally clue less president and a puppet in the hands of market manipulators. No one cares a F*ck on what Russia does. So STOP talking anything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:52:31 </td>
   <td style="text-align:left;"> $AAPL lol just absolutely crazy, algo doesn&amp;#39;t even know what to do.   Just now starting to close the putz holding it up.  Wheeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:48:50 </td>
   <td style="text-align:left;"> $Aapl $goog $fb $amzn $SPY Ever wonder why we keep getting the breaking news about Russia attack being more and more imminent?!  It’s almost like a script to push down stock values to help with inflation!  I mean how many times are they milking the same news?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:48:06 </td>
   <td style="text-align:left;"> $AAPL these final minutes are just going to be nuts!  Whee aaaaahhhhhh wheee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:47:46 </td>
   <td style="text-align:left;"> $aapl need a new fucking source of maxpain lmao because its clearly $167.5 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:47:46 </td>
   <td style="text-align:left;"> $AAPL 3 TRILLION  market cap and you&amp;#39;re still Fcking Sheep 🍆🍆🍆 run bulls run.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:47:16 </td>
   <td style="text-align:left;"> $AAPL trying to make everyone broke! Day traders win in these environments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:46:25 </td>
   <td style="text-align:left;"> $AAPL alright fellas I’m LOADED to the gills on calls for next week! Let’s rock! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:45:40 </td>
   <td style="text-align:left;"> $AAPL watch $168. That VWAP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:45:33 </td>
   <td style="text-align:left;"> $AAPL $spy a flat close back to opening burns everybody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:44:34 </td>
   <td style="text-align:left;"> $AAPL Carl&amp;#39;s Jr 🍔 yuumz ❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:44:10 </td>
   <td style="text-align:left;"> $GOOG $QQQ $AAPL That scumbag Brandon owns this market because he is weak. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:43:11 </td>
   <td style="text-align:left;"> $CLX wow.. this is moving. Looking forward to Tuesday..  guys in $AMD $AAPL .. share it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:42:46 </td>
   <td style="text-align:left;"> $BABA All we care about is the last 3 mins of the day 
 
$bb $jd $aapl $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:42:28 </td>
   <td style="text-align:left;"> $AAPL many CALLS will expire worthless .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:41:56 </td>
   <td style="text-align:left;"> $AAPL safest place to park your cash over the long weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:39:07 </td>
   <td style="text-align:left;"> $AAPL DAMN TIMMY  that HURT 🍆🍆🍆🍆How low can you go??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:38:05 </td>
   <td style="text-align:left;"> $AAPL death cross now at work. War FUD inbound. RIP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:37:25 </td>
   <td style="text-align:left;"> $AAPL move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:37:19 </td>
   <td style="text-align:left;"> $AAPL Rollercoaster 🎢 market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:36:36 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ we have multiple generations of money managers and traders who think a bear market lasts 6 months to a year.  All they know is buy the dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:36:16 </td>
   <td style="text-align:left;"> $AAPL so much fun! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:35:21 </td>
   <td style="text-align:left;"> $AAPL WTF TD AMERITRADE JUST SOLD ALL MY PUTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:34:22 </td>
   <td style="text-align:left;"> $AAPL bull trap ahahahhahahaaaa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:33:56 </td>
   <td style="text-align:left;"> $AAPL oh NOW it dips after I closed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:32:55 </td>
   <td style="text-align:left;"> $AAPL BUY THE DIP!!! When we’re in war with Russia maybe we can send an email to our family back in the states! 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:32:17 </td>
   <td style="text-align:left;"> $AAPL 🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:31:41 </td>
   <td style="text-align:left;"> $AAPL $SPY carbomb in Ukraine. Destabilization in progress. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:31:27 </td>
   <td style="text-align:left;"> $AAPL  Still one of the safest stocks to be in. 🍏🌴🦀🍸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:31:12 </td>
   <td style="text-align:left;"> $AAPL down 1% past month, Nasdaq? Even worse. Apple has remained resilient. Stop expecting bright green days when the market is down every other day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:30:46 </td>
   <td style="text-align:left;"> $AAPL the drop is going to be furious. if you bought into that pump...well... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:30:32 </td>
   <td style="text-align:left;"> $AAPL I GOT THAT NEW DRIP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:30:32 </td>
   <td style="text-align:left;"> $SPY $QQQ  
$AAPL double top/ ABC correction. lower prices should follow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:25:25 </td>
   <td style="text-align:left;"> $AAPL DUMP THIS POS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:25:08 </td>
   <td style="text-align:left;"> $AAPL makes me wanna Puke lmao. now guys i need some advice. PT next week? i thought we could see 172.5++ and i still think that. I wanna short some calls tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:24:44 </td>
   <td style="text-align:left;"> $AAPL the question is do we close at new lows or not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:24:41 </td>
   <td style="text-align:left;"> $AAPL. WTF  it never fail,  the minute I get BULLISH Timmy stick it to Me!🍆🍆🍆🍆🐖🐖🐖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:24:40 </td>
   <td style="text-align:left;"> $IWM  🤑🤑🤑🤑🤑🤑🤑🤑 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:24:16 </td>
   <td style="text-align:left;"> $AAPL scamsino 🎰 $SPY $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:24:12 </td>
   <td style="text-align:left;"> The good Old Rope a Dope right before the close... watch this fucking market crash 2% by 4pm... so annoyed. $AAPL $SPY $SQ $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:23:09 </td>
   <td style="text-align:left;"> $GOOGL this fat pig is fucking worthless piece of trash is getting slaughtered by Biden $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:23:06 </td>
   <td style="text-align:left;"> $AAPL this is fucking intense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:20:56 </td>
   <td style="text-align:left;"> $AAPL that whole rise was such BS. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:20:33 </td>
   <td style="text-align:left;"> $AAPL They took it to 166.19 then to 168.66 dow and then back to 168.66...that&amp;#39;s a lot of 6&amp;#39;s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:20:28 </td>
   <td style="text-align:left;"> $AAPL wait nvm guess it fialed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:19:32 </td>
   <td style="text-align:left;"> $AAPL $SPY 
IT&amp;#39;S GOING TO DUMP 
no wait it&amp;#39;s MOONING 
no wait it&amp;#39;s DRILLING 
aw man it&amp;#39;s BOUNCi 
nope it&amp;#39;s... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:17:36 </td>
   <td style="text-align:left;"> $AAPL let’s get this rally going!  Max pain is $170. Don’t see that but fun to watch! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:16:25 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL I knew it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:15:49 </td>
   <td style="text-align:left;"> $AAPL only FAANG not down is NFLX and chill. Guess that’s what the Ukrainians will be doing over the weekend? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:15:03 </td>
   <td style="text-align:left;"> $AABB $TSLA $AAPL $MSFT $AMD $AABB 911 MM Alerts next weeks going to be very interesting with all the catalysts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:13:53 </td>
   <td style="text-align:left;"> $AAPL about to make all of next week options worthless with this violent up/down whiplash action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:13:53 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMD is it me or did Biden say like 10 times Russia was invading? cause since he’s been in office the market has died. Not saying it’s his fault or anything…buttt kinda coincidental. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:12:23 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA y’all are queefin if you think this market is going any lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:11:33 </td>
   <td style="text-align:left;"> $AAPL  too obvious 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:11:01 </td>
   <td style="text-align:left;"> $AAPL - EOD sell the rip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:09:52 </td>
   <td style="text-align:left;"> $AAPL 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:09:43 </td>
   <td style="text-align:left;"> $MNDT $SPY $FCEL $AAPL it’s like the apocalypse happened and every died. So freaking quiet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:09:18 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Market will rally hard into the close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:08:08 </td>
   <td style="text-align:left;"> $M i hope no shorts are holding puts or havent covered yet over the three days weekend. That would be insane! $AAPL $AMZN $TSLA $MSFT 

Just cover and join her in bed you stud! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:06:42 </td>
   <td style="text-align:left;"> LOWER IS BETTER 

$AMD ↗️Ryzen 6000 vs $INTC Alder Lake Mobile performance:

Ryzen 6000 matches or increasingly beats Alder Lake in MT performance in at 70watts or below. (Credit @LinusTech)
#Ryzen #AMD #PCGaming

$AAPL $TSLA $BTC.x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:06:27 </td>
   <td style="text-align:left;"> $AAPL LMAO they’re tanking it 🤣 this is comical </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:05:56 </td>
   <td style="text-align:left;"> $AAPL $SPY  of this being a bull trap. So many games being played and manipulated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:05:52 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA $AAPL Guys, I need your help! My father is experiencing a huge security risk and his enemies are after him. Please send $BTC.X or I have cash app. My father thanks you all! 🤌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:05:11 </td>
   <td style="text-align:left;"> $AAPL that was a rapid little sell off in a minute dropping more than .30 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:04:58 </td>
   <td style="text-align:left;"> $UVXY $AAPL $MSFT $SPY $IWM - Plunge Protection Team sweeps up the mess yet again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:04:56 </td>
   <td style="text-align:left;"> $AAPL https://applepresale.com/?fbclid=PAAaaoLHfw8tVDoxwQW9WXcsEae6FsMZbbNTKD1ecgx7V9g2es3poqL1V_XCs_aem_AUwJzpPvVc8rSEX2B7t2HR0RATEWlmCKjHcpfxvUd8K6P4K_35Qm4KYd5rQkGyMZss-QHXGQ8OPDpTM_B77-Bc5tGn7CTJWA9FiQ0FU0MANuJI1888pO9sCk5fokR6KXwk4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:04:41 </td>
   <td style="text-align:left;"> $AAPL could close green by the crack of my ass, but she’ll be on sale soon enough. Lower highs and lower lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:04:12 </td>
   <td style="text-align:left;"> $SQ Apple destroyed this $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:03:44 </td>
   <td style="text-align:left;"> FACEBOOK BOTTOM IS IN, BUY OR REGRET IN A FEW WEEKS  
- OUTPERFORMING MOST TECH STOCKS AND NASDAQ TODAY  
- ORDER FLOW SHOWS MASSIVE BUYERS IN THE LOW TO MID $200&amp;#39;s  
- UNDER PRE-COVID LEVELS WHILE TRADING AT A PE OF 15, MOST UNDERVALUED TECH NAME IN THE SECTOR!  
  
$FB $AAPL $MSFT $QQQ $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:03:37 </td>
   <td style="text-align:left;"> $FB cue Warren Buffett to buy 5% of the company $BRK.A $BRK.B $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:03:05 </td>
   <td style="text-align:left;"> $AAPL here we go 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:02:34 </td>
   <td style="text-align:left;"> $SPY LAUGHING MY FUCKING ASS OFF!!!🤣🤣🤣🤑🤑🤑 $42K Day! Peace out bitches. I LOVE THIS MARKET!!! $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:02:21 </td>
   <td style="text-align:left;"> $AAPL Brandon gonna tank market u watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:00:29 </td>
   <td style="text-align:left;"> $AAPL 170 close..👀👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 04:00:23 </td>
   <td style="text-align:left;"> $NVDA $AAPL $TSLA Gonna be fun next week!
Get in on the action - Jordan or Emmitt?

https://instagram.com/stories/optionsplayers/2776579789298195606?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:59:43 </td>
   <td style="text-align:left;"> $AAPL Let&amp;#39;s get to today&amp;#39;s high bulls before we start getting all excited about a few upticks, shall we? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:59:15 </td>
   <td style="text-align:left;"> $SPY $AMZN $AAPL $TSLA $BTC.X 
   
 So the FED ends QE taper in less than one month?  
  
They ain&amp;#39;t tapering shit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:59:07 </td>
   <td style="text-align:left;"> @missnika $SPY This could be a potential start of a reversal. If it follows $WMT $AAPL $TSLA $UPST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:58:51 </td>
   <td style="text-align:left;"> $SOFI $AMZN $GOOGL $AAPL $MSFT … let’s go American innovation! Buy the dip and make America Rip! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:57:37 </td>
   <td style="text-align:left;"> $AAPL Sorry I just... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:57:29 </td>
   <td style="text-align:left;"> $AAPL White House says Russia to blame for cyberattacks on Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:56:49 </td>
   <td style="text-align:left;"> $AAPL going green for the day, and will eviscerate the bears! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:56:26 </td>
   <td style="text-align:left;"> $AAPL Going GREEN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:56:07 </td>
   <td style="text-align:left;"> $AAPL Going big baby! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:55:48 </td>
   <td style="text-align:left;"> $AAPL It&amp;#39;s hard to imaging rotating out of Apple for a lesser company </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:55:27 </td>
   <td style="text-align:left;"> $AAPL good god this is comical lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:55:06 </td>
   <td style="text-align:left;"> latex3d3a14f660cf9076193a3f71331b44c8$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:54:36 </td>
   <td style="text-align:left;"> $AAPL not holding over the three day off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:54:19 </td>
   <td style="text-align:left;"> $AAPL One more bounce please before close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:53:54 </td>
   <td style="text-align:left;"> $FB $NIO $TSLA $AAPL 

MeetKevin crashed the market when he sold everything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:53:28 </td>
   <td style="text-align:left;"> $AAPL Who voted for this idiot??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:52:19 </td>
   <td style="text-align:left;"> $AAPL Biden speaking at 4 must mean the news is so bad he doesn’t wanna tank this thing to 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:52:16 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:51:36 </td>
   <td style="text-align:left;"> $AAPL Biden speaks at 4...he&amp;#39;ll slip and say we&amp;#39;re going to war when he means we&amp;#39;re not going to war...🤣 what a goofball. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:51:27 </td>
   <td style="text-align:left;"> $AAPL now back down on what? Pump, dump, war is off, no it’s back on. This is manipulation on a market wide level. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:50:14 </td>
   <td style="text-align:left;"> $FB fishy 🎣 $FB $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:49:22 </td>
   <td style="text-align:left;"> $EVFM $FAMI $SNDL $TSLA $AAPL , EVFM short borrow fee at 121% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:48:41 </td>
   <td style="text-align:left;"> $AAPL nothing like a good 3:00 Dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:47:23 </td>
   <td style="text-align:left;"> World Of Women $NFT.X Collection Gets Media Deal With Reese Witherspoon’s Hello Sunshine: Here Are The Details – Apple ( $AAPL) $BTC.X $ETH.X https://www.billionaireclubcollc.com/world-of-women-nft-collection-gets-media-deal-with-reese-witherspoons-hello-sunshine-here-are-the-details-apple-aapl/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:47:22 </td>
   <td style="text-align:left;"> $AAPL close at $174 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:46:33 </td>
   <td style="text-align:left;"> $AAPL let’s close at $169. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:42:08 </td>
   <td style="text-align:left;"> $AAPL few things in life that are more retarded than what I just observed over the course of an hour. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:41:53 </td>
   <td style="text-align:left;"> $SPY Made easy 3,5k on calls. Was perfect entry, 433 strike! Took my profit at the resistance. As I said yesterday, it will flash at the open. And then reverse $TSLA $WMT $UPST $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:41:15 </td>
   <td style="text-align:left;"> $AAPL massive dump incoming!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:40:50 </td>
   <td style="text-align:left;"> $AAPL $SPY the markets have been nothing but a joke since the start of the year with this inconsistent wild swings on nothing at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:40:21 </td>
   <td style="text-align:left;"> $AAPL the pump before the dump! Option Killers!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:40:17 </td>
   <td style="text-align:left;"> https://www.investors.com/etfs-and-funds/sectors/sp500-companies-stockpile-1-trillion-cash-investors-want-it/

$AAPL $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:40:16 </td>
   <td style="text-align:left;"> $NFLX $FB $AAPL$MSFT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:40:00 </td>
   <td style="text-align:left;"> $AAPL closes sub 165... big ol dump and just an insane market.  Algo trying shake out the options.  The 170s support  dumping out before close.  Finally clear the path to sub 160 and the appropriate PT of 150.  Obvious signs of risk we are all taking on both sides, bears and bulls.  This is a pinneacle 40 years in the making.  Thank you Boomers! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:39:42 </td>
   <td style="text-align:left;"> $AAPL straight down lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:39:24 </td>
   <td style="text-align:left;"> $AAPL there we go 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:39:17 </td>
   <td style="text-align:left;"> $AAPL Putin and the Russian oligarchs bought that dip 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:38:44 </td>
   <td style="text-align:left;"> $AAPL the pump is almost all the time followed by the...you know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:38:09 </td>
   <td style="text-align:left;"> $AAPL round 2 of pounding coming up!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:38:09 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:37:40 </td>
   <td style="text-align:left;"> $AAPL When this and other great stocks snap back it will
be fast and furious. This war doesn’t affect us! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:37:22 </td>
   <td style="text-align:left;"> $AAPL If the &amp;quot;Market movers&amp;quot; know things a few days before the rest of us then why is the price moving like this?  
 
And the is an issue un itself ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:37:05 </td>
   <td style="text-align:left;"> $SPY $AMD $AAPL $TSLA 
 violent rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:36:18 </td>
   <td style="text-align:left;"> $M will announce a buyout offer
By amazon at earning. Similar to what happened to $KSS $AMC $AMZN  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:35:50 </td>
   <td style="text-align:left;"> $AMZN  — $2T in monthly options expire today.    That’s all $aapl $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:35:45 </td>
   <td style="text-align:left;"> $AAPL 🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:35:41 </td>
   <td style="text-align:left;"> $AAPL Had 30 Min Demand at 166.27. (Orange Zone). Had low of 166.20 and now trading over 168.50. Nice bounce of 1.5% 
 
Optionsforecast4u.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:34:53 </td>
   <td style="text-align:left;"> $AAPL don&amp;#39;t you ever talk about Apple Car.  That&amp;#39;s what you bring up when you&amp;#39;re out of ideas for rev growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:34:34 </td>
   <td style="text-align:left;"> $AAPL NBA back in town today at 1:30PM, NBA= nothing but apple, w/o big teck market can&amp;#39;t risa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:34:21 </td>
   <td style="text-align:left;"> $AAPL how many new patents? New Micro and Mini and complete new MAC?
Satellite Internet and Apple TV without cable? We are kind of interested in the release dates and growth of new markets ohh and you know, the thing! How much cash does AAPL have? It’s just math </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:34:17 </td>
   <td style="text-align:left;"> $AAPL 

It looks like Biden will announce meeting and ceasefire and etc soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:33:49 </td>
   <td style="text-align:left;"> $AAPL News Flash.... shorting AAPL is only good for day trades. Even when the market sank this stock barely fell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:33:43 </td>
   <td style="text-align:left;"> $AAPL who’s ready for this dump🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:32:41 </td>
   <td style="text-align:left;"> $AAPL dump will be swift. 3 day weekend, teetering on a cliff. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:32:08 </td>
   <td style="text-align:left;"> $SPY $AAPL can hold and sell Monday morning, might be lil pullback before close as usual. Just take some profits a long the way 🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:31:53 </td>
   <td style="text-align:left;"> $AAPL the theta whiplash on calls, unbelievable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:31:49 </td>
   <td style="text-align:left;"> $AAPL DUMP coming these guys have no clue </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:31:43 </td>
   <td style="text-align:left;"> $AAPL loaded up 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:31:41 </td>
   <td style="text-align:left;"> $AAPL that may be it then, gg bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:31:41 </td>
   <td style="text-align:left;"> $AAPL dumping at 3 pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:31:20 </td>
   <td style="text-align:left;"> $AAPL EVERYBODY LOAD UP TO SQUEEZE SHORTS! $$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:30:58 </td>
   <td style="text-align:left;"> $AAPL i called it.  $175 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:30:40 </td>
   <td style="text-align:left;"> $NVDA $AMD latex7e66ca3b4aa2f6c040b1cf408a7b8272$😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:30:27 </td>
   <td style="text-align:left;"> $AAPL about to flip the switch on Apple! Starting to look more bullish! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:30:26 </td>
   <td style="text-align:left;"> $AAPL yes!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:30:08 </td>
   <td style="text-align:left;"> $AAPL $FB $NFLX $TSLA $AMZN Pullback seems an opportunity to pick up undervalued Stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:29:48 </td>
   <td style="text-align:left;"> $AAPL dont let up.   Keep pounding them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:29:13 </td>
   <td style="text-align:left;"> $AAPL they wont be able to sit tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:29:08 </td>
   <td style="text-align:left;"> $AAPL they’re gonna dump this so hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:29:03 </td>
   <td style="text-align:left;"> $AAPL pounded bears!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:29:00 </td>
   <td style="text-align:left;"> $AAPL  True North $130 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-19 03:28:18 </td>
   <td style="text-align:left;"> Let&amp;#39;s go Brandon!! 

$AAPL $AMZN $FB $DIS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:48:45 </td>
   <td style="text-align:left;"> $TSLA fuck u putin and biden
2 biggest pieces of shit that ever walked on face of the  earth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:48:27 </td>
   <td style="text-align:left;"> $TSLA maybe tinker with some covered calls….maybe??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:46:57 </td>
   <td style="text-align:left;"> $TSLA sales will go down when people realize this car is ugly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:43:26 </td>
   <td style="text-align:left;"> $TSLA Oh boy here I go buying puts on this bloated P/E slog again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:42:36 </td>
   <td style="text-align:left;"> $TSLA I would fine with a good pop on Monday and exit. I’m sure Elon will tweet something positive over the weekend to get it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:35:44 </td>
   <td style="text-align:left;"> $TSLA what’s next after this breaks the 200ma? What realistic price could be the bottom? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:31:14 </td>
   <td style="text-align:left;"> $TSLA how is this not 600s by now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:31:04 </td>
   <td style="text-align:left;"> $TSLA called it last night!🤑🤑😈
Free discord in bio! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:30:15 </td>
   <td style="text-align:left;"> $TSLA hi. I’m jo Biden and I’ve been trying to destroy America for 50 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:29:45 </td>
   <td style="text-align:left;"> $TSLA fuck Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:27:58 </td>
   <td style="text-align:left;"> $TSLA One of the biggest mistakes people make is the psychological idea of trying to catch the exact bottom. When in reality, it would be better to see actual changes to the macro environment before adding. Even if it means missing the exact bottom. It&amp;#39;s better to miss the exact bottom and be in for a truly sustained bull run, then keep chasing the bottom when macro risk is through the roof. The result that most often occurs is dip buying to losses so many times that the leverage kills the persons liquidity to pt they get forced to take losses before any true reversal. Bears made this mistake for over a year trying to time the top, and now the bulls are doing the same. 

It&amp;#39;s this type of market action as to why I always day traded unless a total market crash. And always took long gains on extended bull runs. There are always cycles. The big concern should be that if the markets dive hard and inflation high, liquidity will shrink. Many have not experienced a true bear cycle. #patience </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:25:45 </td>
   <td style="text-align:left;"> $TSLA biz as usual at TESLA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:25:22 </td>
   <td style="text-align:left;"> $AMZN $TSLA $AAPL
BIDEN: Only America has right to Bomb anywhere in the world.. Iraq, Afghanistan,Vietnam,Korea..
Only we can kill ppl.. and use our military..come to negotiation table just to hear that your demand will
Not be met.. when you come here for negotiations.. we will put u behind bars or kill u Putin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:23:19 </td>
   <td style="text-align:left;"> $TSLA didn’t Biden predict wendsday this week last week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:22:59 </td>
   <td style="text-align:left;"> #Tesla Loses Top Electric Vehicle Spot In Consumer Reports 2022 Rankings: Which Ford EV Came Out On Top? $F $HMC $TM $TSLA https://talkmarkets.com/content/stocks--equities/tesla-loses-top-electric-vehicle-spot-in-consumer-reports-2022-rankings-which-ford-ev-came-out-on-top?post=345315 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:22:47 </td>
   <td style="text-align:left;"> $TSLA $1000 NEXT FRIDAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:20:04 </td>
   <td style="text-align:left;"> $TSLA Biden has become a liar Anand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:18:55 </td>
   <td style="text-align:left;"> $TSLA holding over these long unstable weeekend? Nooooo thx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:17:51 </td>
   <td style="text-align:left;"> $TSLA when this drops retail investors will be putting applications into McDonald’s like no tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:17:51 </td>
   <td style="text-align:left;"> $TSLA You know why Tesla is down ?  because Cathie bought back shares.  $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:15:47 </td>
   <td style="text-align:left;"> $TSLA questions for tesla owners

Ive heard mixed reports from people saying their tesla is amazing in snow and others who say its terrible.

All with all wheel drive soo which is it 🧐🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:14:18 </td>
   <td style="text-align:left;"> This is Stocktwits all year long 😂😂😂

$spy $tsla $aapl $arkk $btc.x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:12:34 </td>
   <td style="text-align:left;"> $TSLA SpaceX 10:1 split today could mean we are headed for X.com merger of all of Elon’s companies under one house, which in my view would be bullish and exciting for markets as SpaceX is the most sought after stock in the private markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:12:00 </td>
   <td style="text-align:left;"> $dwac $twtr $fb $tsla JFC!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:11:39 </td>
   <td style="text-align:left;"> $TSLA biden shorting the market.. fuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:11:20 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK 

OMG!!!😱 DR. BRRRRRRY💰IS BACK,

AND MORE BEARISH THAN EVER!!📉🩸

SH*T IS ABOUT TO GET REAL FANBOYS!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:11:16 </td>
   <td style="text-align:left;"> $TSLA $10 a gallon for gas, it&amp;#39;s going to get a lot of people thinking about buying a Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:10:30 </td>
   <td style="text-align:left;"> $WMT $AUPH $NVDA $SOFI $TSLA 

I wanna thank WMT for coming in clutch and providing this meal. You other 4 got raped my Joe Biden&amp;#39;s made up war in his head. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:09:35 </td>
   <td style="text-align:left;"> $TSLA Retail is so scared lol $SPY $PLTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:08:45 </td>
   <td style="text-align:left;"> latex44b37cec01380c5d060e810e0feb9d97 is to retouch 900$... Hope this war bullshit turn bullish on tesla via oil price skyrocket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:07:59 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY  I have reasons to believe Potato Joe doesn&amp;#39;t even know he is a president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:06:28 </td>
   <td style="text-align:left;"> $TSLA 

Hmm 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:05:53 </td>
   <td style="text-align:left;"> $TSLA The bar is low but if we could break even going into a long weekend I would call that a win. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:05:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA The War in Ukraine reminds me of the new Tesla factories: “any day now” but in reality never going to happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:05:31 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-18 Technical Analysis Video: 
https://www.youtube.com/watch?v=ORh0chDi75c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:04:26 </td>
   <td style="text-align:left;"> $TSLA this time pattern in Tesla is obvious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:02:11 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #4 ticker with sweep activity where institutions are trading options urgently with 33.8K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:01:46 </td>
   <td style="text-align:left;"> $TSLA so people dumping shares AH? 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:01:33 </td>
   <td style="text-align:left;"> $SPY long weekend hopefully won’t bring circuit breakers. Biden don’t do it $ARKK will go to $10 and $TSLA back $400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:01:06 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

The pooots will continue to print, solid work today bear brothers. 😎

🐻 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:00:36 </td>
   <td style="text-align:left;"> $TSLA Michael Burry just active his twitter account since last year Nov 😥😥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 08:00:22 </td>
   <td style="text-align:left;"> $TSLA BTW no US troops will be involved so chill all u doomsday worshippers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:59:58 </td>
   <td style="text-align:left;"> $TSLA might be a good time to open up a short-position </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:59:34 </td>
   <td style="text-align:left;"> $TSLA Invade so uncertainty out of the way.  Green days ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:58:35 </td>
   <td style="text-align:left;"> $TSLA stock market will be closed for long weekend but Giga Austin won’t. Hope to see more and more vehicles in the exit lot the next 72 hours! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:57:26 </td>
   <td style="text-align:left;"> $NIO $AMD $PLTR $SOFI $TSLA 
Back in biz 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:56:05 </td>
   <td style="text-align:left;"> $TSLA Who has 900c and is iffy about them for next week? I will buy them from you after hours via cash app or zelle payment. $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:55:35 </td>
   <td style="text-align:left;"> $TSLA wake up Tuesday to WW3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:54:59 </td>
   <td style="text-align:left;"> $SPY &amp;quot;You don&amp;#39;t buy the dip before a 3 days holiday and Putin about to invade&amp;quot;
$SPY $QQQ $VIX $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:54:29 </td>
   <td style="text-align:left;"> $TSLA 

https://apple.news/AqgmrQNsUSjChlDg9gdU-pw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:54:20 </td>
   <td style="text-align:left;"> $DWAC $twtr $fb $tsla ANOTHER ONE HOT OFF THE PRESS!!! 30 minutes ago!!  
 
https://twitter.com/EliseStefanik/status/1494814309658116101 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:54:08 </td>
   <td style="text-align:left;"> $TSLA Putin says he is about to give Tesla Fanboys the wedgie of their lives next Tuesday.  Torn undies and all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:53:39 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ So the imbecile Biden spoke and the market tanked further after hours. Nothing new. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:51:23 </td>
   <td style="text-align:left;"> $PYPL $FB $SOFI $TSLA All dips I’m waiting eagerly to buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:50:52 </td>
   <td style="text-align:left;"> $TSLA Mooooooooooooon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:48:35 </td>
   <td style="text-align:left;"> $TSLA lambo soon bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:41:14 </td>
   <td style="text-align:left;"> $NVDA $SOXL $AAPL $TSLA $ABNB 
👇  I am Fcking Selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:41:12 </td>
   <td style="text-align:left;"> $TSLA $FB musk and zuck sold a lot in 2021 did they get a tip? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:40:02 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:40:02 </td>
   <td style="text-align:left;"> $TSLA 😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:37:33 </td>
   <td style="text-align:left;"> $TSLA $50 dump on Tuesday! 90% certain! 💀🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:35:03 </td>
   <td style="text-align:left;"> $TSLA it’s so funny how WS don’t don’t their DD! No war is coming ass holes! Stop listening to Biden!he is asleep now anyway! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:34:15 </td>
   <td style="text-align:left;"> $TSLA How come there are NO new tesla car 🚗 models, no roadster, no semi, no cybertruck, no FSD,  and no control on Musk tweeting ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:32:09 </td>
   <td style="text-align:left;"> $TSLA President Biden on Friday said he believes Russian President Vladimir Putin has made up his mind to move forward with an invasion of Ukraine. 
 
&amp;quot;As of this moment I’m convinced he’s made the decision. We have reason to believe that,&amp;quot; Biden told reporters at the White House after delivering an update on the threat of a Russian invasion. 
 
&amp;quot;You are convinced President Putin is going to invade Ukraine. Is that what you just said a few moments ago?&amp;quot; a reporter asked moments later. 
 
&amp;quot;Yes, I did,&amp;quot; Biden said, adding that diplomacy was still on the table if Moscow chose to deescalate. 
 
Biden &amp;#39;convinced&amp;#39; Putin has decided to invade Ukraine https://thehill.com/homenews/administration/594979-biden-convinced-putin-has-decided-to-invade-ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:31:36 </td>
   <td style="text-align:left;"> $TSLA &amp;quot;You Did It Joe!&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:30:49 </td>
   <td style="text-align:left;"> $TSLA 🤚https://youtu.be/qp-vkb4PZLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:27:19 </td>
   <td style="text-align:left;"> Tesla Motors, Inc. (NASDAQ: $TSLA) – Tesla Has Made One Million Of Its New 4680 Battery Cells https://www.billionaireclubcollc.com/tesla-motors-inc-nasdaqtsla-tesla-has-made-one-million-of-its-new-4680-battery-cells/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:25:42 </td>
   <td style="text-align:left;"> $TSLA I love how they figured out Putin. “He decided “
Putin had a game plan from the beginning 
And it’s not a coincidence that it’s happening now during Brandon’s administration </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:25:39 </td>
   <td style="text-align:left;"> $TSLA You know the irony in all this, even if Putin standsdown I don&amp;#39;t think we&amp;#39;ll see substantial gains. The market is THAT rigged right now. It&amp;#39;s going to take major POSITIVE PR to get our 30%+ back. Ijs...

#truth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:25:08 </td>
   <td style="text-align:left;"> $SPY 24th boy blinken meeting with Russians $AMD $NVDA $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:24:53 </td>
   <td style="text-align:left;"> $TSLA 👍https://youtu.be/dBIJQJPH3b8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:21:04 </td>
   <td style="text-align:left;"> $TSLA How elegant of him to donate to a charity he owns. The 1% have been doing this shit for years, it’s a tax loophole.
I see value here, it’s not on the uptrends though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:20:11 </td>
   <td style="text-align:left;"> $TSLA interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:19:05 </td>
   <td style="text-align:left;"> $TSLA so if you bought in the $900s, do you get a free Tesla bag? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:18:21 </td>
   <td style="text-align:left;"> $TSLA https://cleantechnica.com/2022/02/18/hitler-memes-union-busting-red-pills-what-will-it-take-to-quit-elon-musk/ 

Looks like Elon is spot on. One of the smartest people in the world (Elon Musk) tells you something about yourself if you disagree. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:17:37 </td>
   <td style="text-align:left;"> $TSLA Elon supports freedom against Trudeau&amp;#39;s terrorist Nazi government. Go Tesla! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:17:34 </td>
   <td style="text-align:left;"> $TSLA whose holding puts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:15:35 </td>
   <td style="text-align:left;"> $TSLA hold you money. Things about to get really cheap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:15:25 </td>
   <td style="text-align:left;"> $TSLA You guys know this is a fake war right?! Biden is trying to be commander and chief and show some power…His ratings are in the gutter. Have a great weekend!!😊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:11:51 </td>
   <td style="text-align:left;"> $ENPH $AMRS $PLUG $TSLA https://finance.yahoo.com/news/the-economic-toll-if-russia-invades-ukraine-195719278.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:11:22 </td>
   <td style="text-align:left;"> $TSLA Biden believes Putin has decided to attack Ukraine in coming days https://cnb.cx/3HXUhoa  
 
 
We have reason to believe the Russian forces are planning and intend to attack Ukraine in the coming week, in the coming days,” Biden said in remarks at the White House. “We believe that they will target Ukraine’s capital, Kyiv, a city of 2.8 million innocent people.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:11:14 </td>
   <td style="text-align:left;"> $TSLA Not worried one bit. Keep dca bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:09:54 </td>
   <td style="text-align:left;"> $TSLA 

I hope I get BREAKING news soon so we can burn all these thugs short accounts !! 

Over 30% retracement over absolutely nothing but criminal manipulation sadly backed from the top !! 

The entire world is against the rising king Tesla — the shift of power is inbound !! Plz don’t chase dead horses $F $GM 

Standby ! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:09:30 </td>
   <td style="text-align:left;"> $SPY $AAPL $GOOG $AMZN $TSLA last ones without the monster sell offs. Will not be immune to the valuation crunch. Load up shorts while you can. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:08:47 </td>
   <td style="text-align:left;"> $SOFI $TSLA $SPY $NASDAQ $AAPL 

These Russia and Ukraine headlines are irritating for stock market. 

Market will do its thing. These geo political shit won’t cause any harm to stock market. It has more to do with commodities. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:05:33 </td>
   <td style="text-align:left;"> Elon Musk’s $5.7B donation sparks questions about giving $TSLA https://www.billionaireclubcollc.com/elon-musks-5-7b-donation-sparks-questions-about-giving/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:04:59 </td>
   <td style="text-align:left;"> $TSLA 3000 end of week 5000 end of month trust me bros i got a youtube channel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:03:42 </td>
   <td style="text-align:left;"> $TSLA Ever since polestar release their ad, tesla has been goin down , things are looking bad here $GGPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:01:09 </td>
   <td style="text-align:left;"> $SPY I want to know what Elon thinks of all this war FUD $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:01:04 </td>
   <td style="text-align:left;"> $TSLA getting dangerously close to hell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:00:39 </td>
   <td style="text-align:left;"> $TSLA 
https://www.cnbc.com/2021/11/17/samsung-panasonic-and-tesla-embracing-cobalt-free-batteries-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 07:00:17 </td>
   <td style="text-align:left;"> Tesla Loses Top Electric Vehicle Spot In Consumer Reports 2022 Rankings: Which Ford EV Came Out On Top?  $F $HMC $TM $TSLA 

https://newsfilter.io/a/653564279869ade74b0e9748e15856f3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:59:55 </td>
   <td style="text-align:left;"> $TSLA gary black is  just a pumper he probably had some calls to pump.

He started the bs rumour about the split in the 1100s and 1200s and was encouraging dumb retail sheep to buy at those levels.

He allso said factories will open in December, then January and now February. 

What a piece of shit cunt banchordd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:59:40 </td>
   <td style="text-align:left;"> $SPY $AMD $TSLA $AMC $AAPL Bring back my orange Daddy! He likes stonks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:58:24 </td>
   <td style="text-align:left;"> $TSLA stock split coming boys and girls. Get ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:55:20 </td>
   <td style="text-align:left;"> $TSLA  
FXHedge 
@Fxhedgers 
· 
2h 
PUTIN SIGNED A DECREE ON CALLING UP RESERVISTS FOR DUTY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:54:23 </td>
   <td style="text-align:left;"> $TSLA Giga Austin is not going to save you.  What good is a empty plant that can&amp;#39;t get parts due to supply chain issues.  Even Musk admitted that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:52:43 </td>
   <td style="text-align:left;"> $TSLA honestly…Tesla at these prices…I wish Cathie would sell 75% of everything she owns and load the freaking boat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:52:33 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/tesla-has-expanded-its-charging-network-in-mainland-china-to-over-1-100-superchargers 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:52:00 </td>
   <td style="text-align:left;"> $TSLA I kind of miss all the crazy EOD, EOW and EOY daily Bull price predictions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:51:27 </td>
   <td style="text-align:left;"> $TSLA well I guess we have another week of red coming next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:50:51 </td>
   <td style="text-align:left;"> $TSLA  this site is much better after you block the knuckle heads </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:50:37 </td>
   <td style="text-align:left;"> $TSLA 😔 wish I had extra money to scoop up these shares, not sure if we&amp;#39;ll ever see these levels again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:50:28 </td>
   <td style="text-align:left;"> $TSLA 🙄https://youtu.be/4FQOWG26uho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:47:47 </td>
   <td style="text-align:left;"> $TSLA mooon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:46:53 </td>
   <td style="text-align:left;"> $TSLA wanna give a shout out to Bulls that have bigger balls then me. Holding on a 3 day weekend with a chance of WW3 before the next open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:46:25 </td>
   <td style="text-align:left;"> $TSLA 

For heaven sake can this old man STFU 🤫!! Seriously — it’s humiliating just watching him treating public like fools !’ 

🙏🏻🐉🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:46:23 </td>
   <td style="text-align:left;"> Intel $INTC Stock Sinks After Pat Gelsinger Details 4-Year Comeback Plan

$AAPL $TSLA $AMZN 

“The other problem, according to Rasgon, is that Intel faces risk in spending a lot of money while facing strong competition from the likes of $AMD and others. Rasgon said Intel’s data center guidance indicated that the company would “keep losing share for the next several years,” and he noted that Intel delayed Granite Rapids, a new Xeon CPU it said would provide “unquestioned leadership,” by one year to 2024. https://www.crn.com/news/components-peripherals/intel-stock-sinks-after-pat-gelsinger-details-4-year-comeback-plan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:46:14 </td>
   <td style="text-align:left;"> $TSLA Wall Street is full of fucking idiots. Gas is about to be seven dollars a gallon and this stock is down proving that Wall Street is a bunch of fucking idiots. Fuck the man $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:45:39 </td>
   <td style="text-align:left;"> $TSLA I bought a few $600 puts for next week. Just incase the world is ending wanna have some spare cash for the end of times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:45:10 </td>
   <td style="text-align:left;"> $TSLA can’t bet on any stock rn. So fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:44:46 </td>
   <td style="text-align:left;"> $TSLA PUTS 🚨 let the hate flow 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:44:43 </td>
   <td style="text-align:left;"> $TSLA Biden won&amp;#39;t be reelected. He has single handedly destroyed this economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:42:47 </td>
   <td style="text-align:left;"> $TSLA moass coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:42:40 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:42:00 </td>
   <td style="text-align:left;"> $TSLA has a Profit Margin of 10.26%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:41:45 </td>
   <td style="text-align:left;"> $TSLA How in the hell can you be convinced Putin is going to invade AND THEN SAY DIPLOMACY IS STILL ON THE F-IN TABLE?!!!!!! Are you freakin&amp;#39; kidding me??? These mutha-fs are stringing the public along and playin&amp;#39; with our money at the same time. But you know what.... I got something for all of &amp;#39;em. It&amp;#39;s called HOLD!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:40:55 </td>
   <td style="text-align:left;"> $TSLA https://www.reuters.com/world/europe/biden-putin-has-decided-invade-ukraine-will-do-so-coming-days-2022-02-18/ Biden said on Friday he was convinced Russian President Vladimir Putin had made a decision to invade Ukraine, and though there was still room for diplomacy, he expected Russia to move on the country in the coming days. (Reuters) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:40:53 </td>
   <td style="text-align:left;"> $TSLA can&amp;#39;t wait until it breaks through the 200ma 🤓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:35:29 </td>
   <td style="text-align:left;"> $TSLA I love getting blocked by the fanboys &amp;amp; fangirls and soy boys when they get their feelings hurt when I am just making observations.  I maintain my observations by saying this will continue to lose market share. It is the order of things. The price cannot be supported by meme investors forever. The grownups are back in charge on the street for now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:34:54 </td>
   <td style="text-align:left;"> $TSLA Green to red move:  +1.20% to -2.37%  
 https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan&amp;amp;type=greentoredDaily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:34:07 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:33:31 </td>
   <td style="text-align:left;"> $TSLA  Biden?! Why doesn&amp;#39;t somebody stitch that  walking fkn corpse&amp;#39;s mouth shut ffs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:32:42 </td>
   <td style="text-align:left;"> $TSLA remember that Afghanistan withdraw 
They had a fabulous intel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:31:57 </td>
   <td style="text-align:left;"> $TSLA this will be over 1000 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:31:27 </td>
   <td style="text-align:left;"> $TSLA when stock split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:30:50 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-18 Largest Trades Data: 
https://www.youtube.com/watch?v=Oxh7gXgnPlk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:30:39 </td>
   <td style="text-align:left;"> $ARKK $SHOP $TSLA $QQQ  Doom and gloom long weekend gonna be tough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:29:55 </td>
   <td style="text-align:left;"> $TSLA What if the most epic short squeeze in Tesla history is in the works?  It feels possible if you look at Giga Austin, and the share price literally lower than a year ago! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:29:51 </td>
   <td style="text-align:left;"> $TSLA https://www.rt.com/russia/549342-putin-against-old-world-order/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:28:54 </td>
   <td style="text-align:left;"> $TSLA Biden says U.S. has reason to believe Russia has decided to invade Ukraine https://www.cbsnews.com/live-updates/ukraine-russia-biden-update-today-2022-02-18/ via @CBSPolitics CBS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:28:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 
Forget how shitty our president is and how corrupt this market is for a second. Forget that they have to find a headline to fit their narrative in order to control the market. This isn’t new. On a more serious note, I really feel for those living in Ukraine right now and all the families of the Russian soldiers who are just waiting on orders. The level of destruction if this moves forward will be tremendous. Watching the news and hearing about all the nuclear talk just gives me chills. I know this isn’t the first time but perhaps it’s because I’m a mother now it just hits me a little differently. Can you imagine being a parent and not knowing if you will be able to keep your child safe. At the moment, our problems of rising gas and food prices etc., seems so minuscule. Here we are crying about our calls and puts, stocks or whatever when other people are worrying about our lives. It’s stupid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:28:19 </td>
   <td style="text-align:left;"> $TSLA nikola tesla is looking down asking whatdafuck you do to my stock? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:27:19 </td>
   <td style="text-align:left;"> $AMC $GME $BTC.X $TSLA $ETH.X dont worry apes! Sleepy joe will protect us from Russia 🇷🇺 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:26:47 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA $SAVA... maybe it’s time to throw in the towel incompetent leadership corrupt sec market makers cheating retail inflation corruption in pains me to say this but maybe it’s time for a siesta keep a little in Fab 4 and just pull the other shit out. 401ks student accounts ira etc inv account just wait it out... vanguard is getting wrecked BR as well why they are still lending the till is beyond me... but rather keep my money and not feeds the bears anymore thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:26:45 </td>
   <td style="text-align:left;"> $TSLA If you think of a Tesla as an iPhone on wheels, and they are already now at a rate of 1.2 million Teslas/year, if each Tesla ($45,000) is 45X the times of an iPhone ($1,000), that&amp;#39;s like they are already producing 54 million iPhones/year.  This company will be the first $10 trillion company by 2025. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:25:56 </td>
   <td style="text-align:left;"> $TSLA, please this whole War with Russia will continue and part of the Administration plan to show the Power of NATO and a New World Order! Seems like just a stepping stone to gaining more Power with the Elitist. Once this begins, we will be witnessing some big changes on those chasing Global domination or Powers not yet imagined. IMO scary but how I see it! Also, wouldn&amp;#39;t be surprised if Putin and Xi Jinping are in communication on the other side. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:25:11 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:24:42 </td>
   <td style="text-align:left;"> $TSLA what’s wrong with sleepy guy. Why he keeps spreading bad news ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:23:27 </td>
   <td style="text-align:left;"> $TSLA Putin says fuck your calls next week Tesla Fanboys. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:23:11 </td>
   <td style="text-align:left;"> $TSLA Why don’t Russia try to better their economy instead of going on a war. I feel for the people living in that country and thankful to be living in US. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:22:08 </td>
   <td style="text-align:left;"> $TSLA doesn&amp;#39;t Tesla want to open a Giga in Russia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:21:26 </td>
   <td style="text-align:left;"> $DWAC $tsla $twtr $fb $cmcsa this will drop your stock if you are libtards https://www.foxnews.com/opinion/durham-probe-media-major-story-jonathan-turley </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:21:15 </td>
   <td style="text-align:left;"> $TSLA thought war was going to start Wednesday...this ish getting old....I hope nothing happens so 🤡 PhD&amp;#39;s are handed out to everyone making claims its gonna happen soon... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:21:13 </td>
   <td style="text-align:left;"> $TSLA Stock Trading Ideas | 10 Trades executed, trade Profitability of 90%, and Profit Factor of 15. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:20:56 </td>
   <td style="text-align:left;"> $SPY $TSLA $BTC.X 

Waited for 1 hour  then We learned 3 things in 4 minutes 

Biden can’t read Putin’s mind

Biden can think 

Biden can run away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:20:42 </td>
   <td style="text-align:left;"> $TSLA Don&amp;#39;t be misled.  Tesla is the most revolutionary company in history, and ACTUALLY profitable printing $4 billion of revenue every single quarter.  The 4680 cell will further blow up these profits, and they&amp;#39;re putting the final polishes on Austin, with Berlin to open by May.  Don&amp;#39;t miss buying into Tesla at this prices.  A hundred dollars up or down in 5 years will be pennies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:19:54 </td>
   <td style="text-align:left;"> $TSLA Another useless war and money spending fiasco. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:19:13 </td>
   <td style="text-align:left;"> $TSLA it’s best to buy vxx I fucking didn’t buy it. If market went down. It will sky rocket. I’m stupid. Spy would’ve gone down and truly vxx would’ve gone up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:18:44 </td>
   <td style="text-align:left;"> $TSLA https://www.bloomberg.com/news/articles/2022-02-18/lavrov-to-meet-blinken-next-week-u-s-says-ukraine-update?sref=pHyhiApD via @bpolitics  
 
Biden said he believes that President Vladimir Putin has decided to attack Ukraine and that an invasion -- including a strike on Kyiv -- could come within days.  
 
The U.S. said Russia has massed as many as 190,000 personnel – including troops, National Guard units and Russian-backed separatists – in and around Ukraine in what it called the most significant military mobilization since World War II.    (Bloomberg) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:17:42 </td>
   <td style="text-align:left;"> $QQQ major sell off commit next week.. $SPY .. $TSLA $AAPL $AMZN … War is imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:17:28 </td>
   <td style="text-align:left;"> $GOOGL dumb as Biden is trying to instigate a war fucking  idiot $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:17:05 </td>
   <td style="text-align:left;"> $TSLA $spy Biden is the only one who has stuff to hide in Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:16:21 </td>
   <td style="text-align:left;"> $TSLA this war crap is becoming baked in . No one is gonna care soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:16:01 </td>
   <td style="text-align:left;"> $TSLA would u be scared of Biden? World going to clean up with this idiot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:15:31 </td>
   <td style="text-align:left;"> Let&amp;#39;s get you ready for this week. Drop your chart request below $SPY $AAPL $QQQ $C $TSLA  #investing 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:15:23 </td>
   <td style="text-align:left;"> $TSLA ahhh relaxing 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:13:27 </td>
   <td style="text-align:left;"> $DWAC $tsla $twtr #hillaryforprison is trending #1 https://twitter.com/search?q=%23HillaryForPrison&amp;amp;src=trend_click&amp;amp;f=live&amp;amp;vertical=trends </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:13:14 </td>
   <td style="text-align:left;"> $TSLA  
zerohedge 
@zerohedge 
· 
9m 
*BIDEN SAYS CONVINCED THAT PUTIN HAS DECIDED TO INVADE UKRAINE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:12:59 </td>
   <td style="text-align:left;"> $TSLA After deleting Ukrain and whole stock market… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:11:16 </td>
   <td style="text-align:left;"> $TSLA Opening price on Tuesday? Thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:11:12 </td>
   <td style="text-align:left;"> $TSLA This is all a hoax, there is someone spreading propaganda and causing a conflict between ukrainian and russia. There is false news and false spread of information. I def believe Biden is part of it.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:11:09 </td>
   <td style="text-align:left;"> $TSLA Giga Austin likely has received its final permits and should open next week.  The 100+ cars on the recently cured parking lot appear to be the very first to be officially delivered, not test cars.  Congratulations to Tesla on opening Austin imminently! Huge achievement and 4680 structural battery pack Model Ys will be a revolution in manufacturing, further increasing Tesla&amp;#39;s already amazing margins. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:10:33 </td>
   <td style="text-align:left;"> $TSLA ok no war and we will open a mega factory in russia soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:10:17 </td>
   <td style="text-align:left;"> $TSLA P u T S 🚨🚨🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:08:38 </td>
   <td style="text-align:left;"> $TSLA $AMZN $GOOG $NVDA amazing how Brandon can only take 1 or 2 questions and start dosing off before his staff cuts the “conference”. FJB!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:07:41 </td>
   <td style="text-align:left;"> $TSLA Kim Un can beat Jose easier.. hahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:06:54 </td>
   <td style="text-align:left;"> $TSLA what.. the meeting over. Jose ran. Wow. Not like Trump hahhah fake news. Hahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:06:38 </td>
   <td style="text-align:left;"> $TSLA i’m suprised North Korea ain’t doing stupid shit… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:06:21 </td>
   <td style="text-align:left;"> 🤡 Biden 
. 
It’s like they want Russia to invade..
$SPY $QQQ $TSLA $BTC.X $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:06:14 </td>
   <td style="text-align:left;"> $TSLA just another &amp;quot;new enemy &amp;quot; to create fear since nobody is falling for the covid boogeyman man anymore. Just wait till thr Russia thing fizzles out thryll bring back &amp;quot;terrorism&amp;quot; threats to keep people choking on their propaganda.  Sick world full of LIARs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:05:56 </td>
   <td style="text-align:left;"> $TSLA Bro, Biden is complete shit like. This whole shit is planned out just like 9/11 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:05:56 </td>
   <td style="text-align:left;"> $TSLA who is buying in a war / recession </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:05:54 </td>
   <td style="text-align:left;"> $SPY WTF WAS THAT JOE!!! U LEFT IN 3 mins $AMD $NVDA $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:05:24 </td>
   <td style="text-align:left;"> $TSLA Biden convinced that Russia will invade Ukraine  . Biden still hold door open for diplomacy (Per Friday 02-18 WH speech) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:05:15 </td>
   <td style="text-align:left;"> $XELA 
I have two points to share with you. These points makes me confident about the real value of Exela. Please do your own DD. 

1) 
Par warned Shorts (see twit of Feb 15th👇🏼)

Par Chadha@par_chadha
43M+ $XELA shares borrowed by shorts; cost to borrow up 15x YTD (source: ORTEX). IMO huge risk to bet against the house with 90k+ shareholders. Reminds me of early days when shorts loved $TSLA for its debt etc.

See how the shorts lost when they persevered on shorting Tesla:

https://amp.cnn.com/cnn/2021/01/06/investing/tesla-shorts-losses-elon-musk-win/index.html
 
2) 
Jan 26, 2022
Par Chadha, Exela’s Executive Chairman, noted, 
“After deploying more than $400 million of capital in 2021 to substantially reduce debt and extend maturities, we are now deploying capital to unlock shareholder value for our large and growing shareholder base.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:04:31 </td>
   <td style="text-align:left;"> $TSLA When no one backs down, conflict is inevitable. Then, this snowballs into a shitshow. SMH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:04:19 </td>
   <td style="text-align:left;"> $TSLA president is shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:03:44 </td>
   <td style="text-align:left;"> https://youtube.com/watch?v=aOuqBc5hdZc&amp;amp;feature=share. Biden behind the podium on the verge of death $nio $tsla latex73430e44e6e85d0ed3e433b06539bc64DKNG PUTS on ER play 0.31➡️1.15 370% GAINS 🔥🤯

$TSLA CALLS 0.40➡️1.4 350% GAINS 🤑💵

OVER 700% GAINS IN ONE DAY 🙌

JOIN DISCORD LINK IN BIO 🕺

 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:01:12 </td>
   <td style="text-align:left;"> $NIO $TSLA $BTC.X $ETH.X for the dummies saying there isn’t going to be a war.. here’s the pretext for the invasions it’s going to happen along with rate hikes, which will directly crash the market. BANK ON IT! 

To the dummies sitting on bags here you go to @RockThem @dumrich @Megatrend1986 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:00:33 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-18 Options Analysis Video: 
https://www.youtube.com/watch?v=-nJxMReweXw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 06:00:08 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : TSLA Stock News: 6 Biggest Headlines That Tesla Investors Need to Know This Week https://www.stck.pro/news/TSLA/23114378 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:59:38 </td>
   <td style="text-align:left;"> $TSLA https://stockilluminati.com/tsla/miscellaneous.php the watchlist count only keeps going up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:59:13 </td>
   <td style="text-align:left;"> $TSLA coming days War </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:58:55 </td>
   <td style="text-align:left;"> $TSLA  
FXHedge 
@Fxhedgers 
· 
1h 
PUTIN SIGNED A DECREE ON CALLING UP RESERVISTS FOR DUTY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:58:10 </td>
   <td style="text-align:left;"> $TSLA Joe  ukraine launching massive attack.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:57:53 </td>
   <td style="text-align:left;"> $TSLA Biden speaking now! 
 
Watch live: Biden gives update on Russia-Ukraine conflict https://thehill.com/video/administration/594952-watch-live-biden-gives-updates-on-ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:57:00 </td>
   <td style="text-align:left;"> $TSLA Biden tanked the market today . Hunter prob bought a ton of tech calls for next week . Unbelievable these politicians people listen too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:56:59 </td>
   <td style="text-align:left;"> $TSLA After Hours is looking good! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:56:48 </td>
   <td style="text-align:left;"> $TSLA When do we witness this shed $300B in market cap in a single day? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:56:37 </td>
   <td style="text-align:left;"> $TSLA --&amp;gt;---&amp;gt;Watch live: Biden gives update on Russia-Ukraine conflict https://thehill.com/video/administration/594952-watch-live-biden-gives-updates-on-ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:56:12 </td>
   <td style="text-align:left;"> $TSLA Joe live https://www.youtube.com/watch?v=oNbDfAgyOmI&amp;amp;feature=youtu.be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:56:05 </td>
   <td style="text-align:left;"> $TSLA He speaks now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:55:53 </td>
   <td style="text-align:left;"> $SPY I swear if this mfkr doesn&amp;#39;t either invade or goes home in the next 3 days........ 🙄
$QQQ $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:55:49 </td>
   <td style="text-align:left;"> $TSLA market meltdown ahs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:55:43 </td>
   <td style="text-align:left;"> $TSLA clown show started </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:55:43 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
sorry to anyone following me but I am reposting this. people need to understand what is REALLY going on... 
  
  
&amp;quot;So sick of this bullshit &amp;quot;war with Russia&amp;quot; narrative to distract from the fact that the free money gig is up.  
  
FED pulling the plug on free money is the only thing that matters to the market!&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:55:37 </td>
   <td style="text-align:left;"> $TSLA 1.1 million views in 16 hours he says Tesla in the song and driving around a model S plaid. This is why Elon doesn’t spend on marketing https://youtu.be/e2AeKIzfQus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:55:03 </td>
   <td style="text-align:left;"> $SPY $AMD $AAPL $NVDA $TSLA 
Wheres joe? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:55:01 </td>
   <td style="text-align:left;"> $TSLA Get ready.. Sleepy Jose is peaking. Hahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:54:39 </td>
   <td style="text-align:left;"> $TSLA I am convinced by Tuesday, the Ruskies would have invaded the Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:54:04 </td>
   <td style="text-align:left;"> $TSLA is Tesla going to do another split ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:53:25 </td>
   <td style="text-align:left;"> $TSLA --&amp;gt;Watch live: Biden gives update on Russia-Ukraine conflict https://thehill.com/video/administration/594952-watch-live-biden-gives-updates-on-ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:53:10 </td>
   <td style="text-align:left;"> $TSLA sinking in 3 minutes. LET&amp;#39;S GO BRANDON! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:52:11 </td>
   <td style="text-align:left;"> $TSLA made 5k off you today my dear friend Tsla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:52:05 </td>
   <td style="text-align:left;"> $TSLA Retard Biden is 1 hour late… PLEASE BRING BACK TRUMP, I’M BEGGING ON MY KNEES AND SO DO MY STOCK HOLDINGS 😭😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:50:07 </td>
   <td style="text-align:left;"> $TSLA Looking increasingly likely that the Fed&amp;#39;s rate hike at the March 15-16 FOMC meeting will only be .25, not .5, with guidance that there will be only measured increases going forward.  Thus, only 15 more trading days till stocks should be relieved.  That, with Austin opening next week, and SpaceX 10:1 split announcement today, should keep the stock afloat amidst macro instability, at least in my view. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:49:43 </td>
   <td style="text-align:left;"> $TSLA How is this fool the president he is a hour late to the conference damn shame MORON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:46:53 </td>
   <td style="text-align:left;"> $TSLA Stock News: 6 Biggest Headlines That Tesla Investors Need to Know This Week https://investorplace.com/2022/02/tsla-stock-news-6-biggest-headlines-that-tesla-investors-need-to-know-this-week/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:45:24 </td>
   <td style="text-align:left;"> $TSLA (Pending!! keep the faith!) Watch live: Biden gives update on Russia-Ukraine conflict https://thehill.com/video/administration/594952-watch-live-biden-gives-updates-on-ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:44:35 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $TSLA is the #5 stock that institutions are trading over rolling 5 day window with 100.6K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:44:24 </td>
   <td style="text-align:left;"> $TSLA even being down 22.20%, I am still shorting ROKU. the valuation is a joke on a company with no moat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:43:52 </td>
   <td style="text-align:left;"> $AMC Biden must have gotten lost again…still waiting on the BS that spews out of his mouth on this Russia/ Ukraine issue. That is now our issue and since my $TSLA  calls have gotten destroyed so far because of it, it is now my issue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:43:07 </td>
   <td style="text-align:left;"> $TSLA bubble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:42:43 </td>
   <td style="text-align:left;"> $TSLA just short every thing in this market for the next 12 months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:41:26 </td>
   <td style="text-align:left;"> $TSLA WHEN BIDEN SPEAKING!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:39:26 </td>
   <td style="text-align:left;"> $TSLA 😒https://youtu.be/8X7Ng75e5gQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:37:17 </td>
   <td style="text-align:left;"> $SPY $AMZN latex0aa670a3a2178bab44028479a65a748eAAPL 135-140
$MSFT 240

And then we can talk about value in the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:35:25 </td>
   <td style="text-align:left;"> $TSLA 😬https://youtu.be/VkgxgrWFRDY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:35:23 </td>
   <td style="text-align:left;"> $AMD $AAPL $MSFT $TSLA It&amp;#39;s 4PM. Isn&amp;#39;t Biden suppose to be talking about Russia/Ukraine right now? Get off your ass Mr. President, give us the all important update </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:34:49 </td>
   <td style="text-align:left;"> $TSLA Dow sheds more than 200 points (Russia-Ukraine tensions roil markets) https://cnb.cx/3LI9CeP  Oanda’s Edward Moya said in a note Friday. “Wall Street will remain jittery until we see a major de-escalation.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:34:34 </td>
   <td style="text-align:left;"> $SPY Always remember 2 things, Traders at HFs aren&amp;#39;t using their own Money so selling out &amp;amp; getting back in is not a big deal, 2nd &amp;amp; most important, Wall St does not lead, they dont have courage so on a day like this they have no reason to take any risk, 
 
Retail can use that if they&amp;#39;re smart about it, we can move faster when we change out minds but if you expect WS to lead you think of $tsla &amp;amp; how many years is was stuck before WS really jumped in. 
 
Wall St&amp;#39;s motto is &amp;quot;Im scared, you go first&amp;quot; 
 
$aapl $amzn $baba </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:34:11 </td>
   <td style="text-align:left;"> $TSLA yikes they are blowing up pipelines in Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:32:44 </td>
   <td style="text-align:left;"> $NVDA $TSLA $CRM $AAPL 
Biden better not F this shit up, and now that Xi &amp;amp; Putin loaded up they can qualm the war rhetoric </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:31:00 </td>
   <td style="text-align:left;"> $TSLA  He bought over 1000 and where is he now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:30:02 </td>
   <td style="text-align:left;"> $TSLA 😉https://youtu.be/bRT5rVFuTew </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:29:27 </td>
   <td style="text-align:left;"> $TSLA Give me more PuTS! ⬅️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:29:17 </td>
   <td style="text-align:left;"> $TSLA Make America Fucked Again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:28:52 </td>
   <td style="text-align:left;"> latex7e660219024c7c374394b4ba12618216TSLA break above 890 for calls 
TSLA break below 875 for puts

AMD break above 114.5 for calls 
$AMD break below 113 for puts

SHOP break above 670 for calls 
SHOP break below 650 for puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:28:04 </td>
   <td style="text-align:left;"> $TSLA $F $AMZN   probly a good idea to just buy puts thru the end of 2022 while out Govt is putting on the Make America Suck Again show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:27:48 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/tesla-wins-lawsuit-against-the-designated-driver-who-claiming-faulty-brakes 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:27:34 </td>
   <td style="text-align:left;"> $TSLA So is biden speaking or what? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:27:25 </td>
   <td style="text-align:left;"> $TSLA --&amp;gt;Watch live: Biden gives update on Russia-Ukraine conflict https://thehill.com/video/administration/594952-watch-live-biden-gives-updates-on-ukraine  The Hill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:25:36 </td>
   <td style="text-align:left;"> $MULN It went down with overall automotive sector . Stock is not broken. It will reverse with $TSLA $FSR $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:25:08 </td>
   <td style="text-align:left;"> You think Biden is going to crash the stock market going into President day weekend? …  
🤡
 $SPY $QQQ $BTC.X $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:24:45 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $QCOM 

Have a wonderful weekend 
everyone!😃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:23:59 </td>
   <td style="text-align:left;"> $TSLA $AAPL Is this biden? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:23:46 </td>
   <td style="text-align:left;"> $TSLA 👋https://youtu.be/BcylaMgaM3A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:23:40 </td>
   <td style="text-align:left;"> $EPHE $TSLA $NIO $LCID $ARKK &amp;quot;New EV bill awaiting Duterte’s signature allows petrol pumps to become charging stations.&amp;quot; https://gulfnews.com/business/energy/will-elon-musks-tesla-byd-xpeng-nio-lucid-li-saic-catl-lg-chem-now-invest-in-the-philippines-1.1645017592328 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:22:50 </td>
   <td style="text-align:left;"> Thank God the markets closed before #DementiaJoe speaks. Heaven help us with this pinhead running the free world! 🙏 
 
$AAPL $DJIA $QQQ $SPY $TSLA #Bidenflation #Ukraine #Biden #BidenIsAFailure #LiberalismIsTheRealPandemic #Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:22:47 </td>
   <td style="text-align:left;"> $TSLA Austin factory may open up next week (Berlin factory later in 2022!)  Biden speech in a few Minutes! Monday is a stock holiday FYI (Washington Day) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:21:31 </td>
   <td style="text-align:left;"> $TSLA Called it🤑🤑
Free discord in bio! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:21:01 </td>
   <td style="text-align:left;"> $TSLA First Austin opens. Then Berlin.  Then 10:1 split in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:20:27 </td>
   <td style="text-align:left;"> latexcdb3ca6588a20cf0de2be49c5931ac44SNOW - 291 -&amp;gt; 273, Profit +6% 
$ROKU - 113 -&amp;gt;  103, Profit +8.8% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:20:01 </td>
   <td style="text-align:left;"> $TSLA I think people often forget this was a reverse split 5:1 and it&amp;#39;s still at $850!!! That&amp;#39;s insane! Whether you like them or not, that&amp;#39;s impressive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:19:14 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla Has Made One Million Of Its New 4680 Battery Cells https://www.stck.pro/news/TSLA/23113151 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:18:50 </td>
   <td style="text-align:left;"> $TSLA $LCID $FSR $GGPI

Ate those dips like cake 🎂 

But but but Putin, it’s BEEN priced in and if gas goes up EV DEMAND SOARS!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:18:08 </td>
   <td style="text-align:left;"> $TSLA bears are going to find out what payback is when Elon announces GigaTexas and GigaBerlin are finally open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:17:36 </td>
   <td style="text-align:left;"> $TSLA shorts want a missile or 2 to make some money jeez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:16:04 </td>
   <td style="text-align:left;"> $TSLA fuck war
Hopefully we can work this out in a peaceful way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:14:16 </td>
   <td style="text-align:left;"> $TSLA Tesla Has Made One Million Of Its New 4680 Battery Cells 

https://newsfilter.io/a/087efe1c4a1fa7cb8eb52cd5de153d02 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:14:07 </td>
   <td style="text-align:left;"> Finished the day with 8 Wins &amp;amp; 1 Loss: 
 
$TSLA - 850 puts at $3.78 went to $8.35 - Win 100%+ 
 
$SPY - 436 puts at $2.30 went to $3.36 - Win 
 
$TSLA - 850 puts at $4.55 went to $5.78 - Win 
 
$TSLA - 850 puts at $4.80 went to $13 - Win 200%+ 
 
$SPX - 4300 puts at $2.80 went to $3.20 - Win 
 
$SPX - 4300 puts at $2.75 went to $5.10 - Win 
 
$SPX - 4340 puts at $3.60 went to $11 - Win 200%+ 
 
$SPX - 4330 puts at $3.70 - Loss 
 
Great day. Great week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:13:38 </td>
   <td style="text-align:left;"> $TSLA still hovering about critical levels. One more bloody day can send it again under 800. But if you look to possible gains in next months (reversal back to critical 1xxxx levels) this is no brainer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:13:07 </td>
   <td style="text-align:left;"> $ARKK Its possible to like Cathie &amp;amp; see her flaws, if she took a year off of being in the press, threw out what doesn&amp;#39;t work &amp;amp; keep what does, she can get herself back on track. Shes smart but when you go on CNBC &amp;amp; tell everyone that you&amp;#39;re right &amp;amp; the Market is wrong its a double edged sword, The Market will prove you&amp;#39;re wrong &amp;amp; Wall St will eat your Lunch as well. 
 
One of the great Market Minds Bill Bernstein has a great take on it last year &amp;amp; he was spot on 
 
https://youtu.be/W8lvZjBmiOo?t=2544 
 
$coin $tsla $rblx $ark </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:12:43 </td>
   <td style="text-align:left;"> $TSLA what a crazy day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:12:04 </td>
   <td style="text-align:left;"> $SPY Bottle Water? $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:10:41 </td>
   <td style="text-align:left;"> $TSLA Ukraine starting To attack  Donbass .. Russia almost fo sure will protect civilians </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:09:55 </td>
   <td style="text-align:left;"> $SPY Possible we are seeing early signs saturation in EV market similar to what occurs with Solar/Green Stocks early 2021 as $TAN and similar began to erode while OIL/Energy outperformed.

This could mark a new era for $GM $F and while $TSLA will remain leader among all EVs for now. 

I see TECH becoming a BUY once we get through this strangulation from geopolitical pressures and uncertainty how FEDs will handle Federal Rates. 

I’m nearly certain they will approach with ease, only increasing by 2H 2022 if inflation continues to climb.  Their model has been adjusted to show peak by mid summer.

One more month of Hell, then maybe Russia, Feds, and COVID will all be in rear view mirror.  We will have fresh new assets and bargain buys.  Be hopeful 🍺🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:08:23 </td>
   <td style="text-align:left;"> $TSLA expecting at least 925 sometime next week. [840 calls go brr] </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:08:21 </td>
   <td style="text-align:left;"> $TSLA margin call 🐓🍭🍭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:07:58 </td>
   <td style="text-align:left;"> $TSLA Hold or else </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:07:32 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

THIS IS OUR MARKET NOW BULLS

🐻 HAVE 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:07:00 </td>
   <td style="text-align:left;"> $TSLA new alert coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:06:52 </td>
   <td style="text-align:left;"> $TSLA closed below 860 support… if this US-Russia-Ukraine shit doesn’t get better over the weekend TSLA will see 800 next week… went for a lotto PDS hold over the weekend let’s see what happens… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:06:38 </td>
   <td style="text-align:left;"> $TSLA  
 
TSLA what a choppy day and week of trading. Fed, Russia/Ukraine, and a 3 day weekend coming up. It was tough, but I think things will rebound on Tuesday... unless we see some major event over the weekend. What are your thoughts? 
 
I&amp;#39;ll be enjoying some time off but keeping an eye on news social sentiment over the next few days. This will help guide my decisions when markets open next week. This is what I use to keep an eye on things, especially when markets are closed.  
 
https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=pw_20220218 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:06:21 </td>
   <td style="text-align:left;"> $AUPH $TSLA $SOFI $NVDA $AMD 

Make sure to thank your President Monday for the great job he&amp;#39;s done so far🙄.  Markets are booming😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:06:18 </td>
   <td style="text-align:left;"> $TSLA has the white house live started? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:05:49 </td>
   <td style="text-align:left;"> $TSLA $1000 weekly calls next week 🙏🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:05:07 </td>
   <td style="text-align:left;"> $TSLA looks bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:04:40 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

I’m gonna hodl my poots may the fud be with us bears.

🐻 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:04:38 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s gooooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:04:30 </td>
   <td style="text-align:left;"> $TSLA Chairman  Xi says he aims for common prosperity probably doesn’t mean it, president Biden aims for common servitude probably does mean it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:04:24 </td>
   <td style="text-align:left;"> $TSLA Good day....next week will be better shorts. Let&amp;#39;s rip this down where it belongs! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:04:21 </td>
   <td style="text-align:left;"> $TSLA up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:04:18 </td>
   <td style="text-align:left;"> $TSLA .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:04:07 </td>
   <td style="text-align:left;"> $TSLA down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:04:02 </td>
   <td style="text-align:left;"> $TSLA nice profit on lotto calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:03:53 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:03:47 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-18 Technical Analysis Video: 
https://www.youtube.com/watch?v=ORh0chDi75c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:02:53 </td>
   <td style="text-align:left;"> $TSLA Biden and Putin muddyfellow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:02:25 </td>
   <td style="text-align:left;"> $ELF $RIDE $TSLA $SNAP  
 
Oh gosh, now we have PLUGS getting ready to talk at 4pm!!  That&amp;#39;s never good for the market!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:02:11 </td>
   <td style="text-align:left;"> $TSLA -&amp;gt;&amp;gt; Watch live: Biden gives update on Russia-Ukraine conflict https://thehill.com/video/administration/594952-watch-live-biden-gives-updates-on-ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:01:22 </td>
   <td style="text-align:left;"> $TSLA $SPY$SPX $GS  
Constrained  range across the markets is a windfall with extremely low risk using credit strategies.  
 
The other option is taking a long put/call and hoping you caught the right move. Much lower  probability. Holding GS short puts and just closed these two. The first one we opened for $205 credit on Wed, the second for $4200 per contract (that one expires worthless today). 
 
Since Jan has been our primary strategy, avoid drawdowns that way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:00:57 </td>
   <td style="text-align:left;"> $TSLA Gary Black 
@garyblack00 
· 
1h 
There appears to be a strong chance Austin (Tesla factory) opens next week.  $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:00:40 </td>
   <td style="text-align:left;"> $TSLA power Hour </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 05:00:19 </td>
   <td style="text-align:left;"> $TSLA President Brandon can’t keep Tesla down! President Brandon can’t! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 04:59:58 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 04:59:52 </td>
   <td style="text-align:left;"> $TSLA booooooum Its over bon 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 04:58:54 </td>
   <td style="text-align:left;"> $TSLA Invasion or not, it doesn&amp;#39;t change the North American Markets. Business still goes on... Biden propaganda has made markets RED. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 04:58:53 </td>
   <td style="text-align:left;"> $TSLA Got to love OILOILOIL sorrrry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 04:58:48 </td>
   <td style="text-align:left;"> $TSLA  got 15 shares at 840. It&amp;#39;s a good day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 04:58:48 </td>
   <td style="text-align:left;"> “BREAKING: Sources tell @FoxBusiness @TheJusticeDept block-trading investigation initially focusing on big Wall Street firms NOT clients such as @citsecurities. Investigation will mirror a typical insider trading probe &amp;amp; spread to clients IF DOJ can show payoffs for info on trades~”

$AMD ↗️ $AAPL $TSLA $MSFT $AMZN  https://twitter.com/cgasparino/status/1494695082204803076?s=12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 04:58:38 </td>
   <td style="text-align:left;"> $TSLA I can&amp;#39;t afford to lose another dime </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 04:58:22 </td>
   <td style="text-align:left;"> $TSLA 🙄https://youtu.be/oCS2HhKI-YQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 04:58:14 </td>
   <td style="text-align:left;"> $TSLA fcck this thing …… into close chop chop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-19 04:57:17 </td>
   <td style="text-align:left;"> $TSLA 
 
Shorts!! 
 Gary Black 
@garyblack00 
· 
1h 
There appears to be a strong chance Austin (Tesla factory) opens next week.  $tsla </td>
  </tr>
</tbody>
</table></div>

---
