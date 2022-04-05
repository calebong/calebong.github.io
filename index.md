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



Last Updated: 2022-04-05 09:37:40 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/copper </td>
   <td style="text-align:left;"> 2022-04-05 09:36:03 </td>
   <td style="text-align:left;"> Copper Hits 4-week High </td>
   <td style="text-align:left;"> Copper increased to a 4-week high of 4.802 USD/Lbs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-04-05 09:22:33 </td>
   <td style="text-align:left;"> Australia Shares Climb on Energy, Tech Boost </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index climbed 0.4% to around 7,544 on Tuesday, moving within 1% of its year-to-date high, led by gains in technology and energy stocks, while investors await the central bank’s interest rate decision later in the day. Australian technology stocks tracked an overnight rally on Wall Street, with strong gains from Xero (3.8%), Block Inc (6.5%), Wisetech Global (2.1%), Altium Ltd (2.6%) and Pexa Group (3.9%). Energy firms also advanced amid a rebound in oil prices, including Woodside Petroleum (3.3%), Santos Ltd (2.7%) and Beach Energy (2.4%). Meanwhile, iron ore miners and clean-energy related firms eased following a sharp run-up, with losses from BHP Group (-0.3%), Rio Tinto (-0.2%), Core Lithium (-1.9%), Lake Resources (-5.5%) and Lynas Rare Earth (-4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-05/boj-s-kuroda-characterizes-recent-yen-moves-as-somewhat-rapid?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-05 09:17:09 </td>
   <td style="text-align:left;"> BOJ’s Kuroda Characterizes Recent Yen Moves as Somewhat Rapid </td>
   <td style="text-align:left;"> Haruhiko Kuroda.                                                                                                                                                                                                           , Toru Fujioka                                                                                                                                                                                                               , Recent moves in Japan’s currency have been “somewhat rapid,” though a weak yen is still positive for the economy overall, Bank of Japan Governor Haruhiko Kuroda said during a regular policy update in parliament Tuesday., Kuroda said it was vital for foreign exchange levels to reflect economic fundamentals and that he would continue to watch movements in the market closely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-05/avalanche-of-bond-supply-pressures-rbi-to-stem-yield-shock?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-05 09:00:00 </td>
   <td style="text-align:left;"> Avalanche of Bond Supply Pressures RBI to Stem Yield Shock </td>
   <td style="text-align:left;"> Subhadip Sircar                                                                                                                                                                                                                                                                                                      , Traders in India are pinning their hopes on the central bank stepping in to manage bond-market liquidity at this week’s policy review as the market confronts record debt supply.                                                                                                                                    , The Reserve Bank of India faces the challenge of keeping bond yields in check as the government kicks off an unprecedented 14.31 trillion rupees ($190 billion) of annual borrowing in April. At the same time, surging oil prices threaten to accelerate inflation, putting pressure on policy makers to hike rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-05 08:57:49 </td>
   <td style="text-align:left;"> US Futures Muted After Tech-Led Rally </td>
   <td style="text-align:left;"> US stock futures were little changed in Asian trade on Tuesday after a technology-led rally on Wall Street. Futures contracts tied to the three major indexes drifted flat to slightly negative. The Nasdaq Composite jumped 1.9% in regular trading on Monday, while the S&amp;P 500 gained 0.8% and the Dow added 0.3%. Shares of Twitter surged 27.1% for its best day ever after Elon Musk disclosed a 9.2% passive stake in the social media company. Other mega-cap names advanced including Tesla (5.6%), Apple (2.4%), Amazon (2.9%), Microsoft (1.8%) and Alphabet (2%). US-listed Chinese firms also rallied after China’s securities watchdog proposed revising confidentiality rules involving offshore listings, clearing a legal hurdle to Sino-US cooperation on audit oversight. Meanwhile, sentiment remained clouded by the Russia-Ukraine war, with investors worried about potential new sanctions against Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/singapore/composite-pmi </td>
   <td style="text-align:left;"> 2022-04-05 08:51:45 </td>
   <td style="text-align:left;"> Singapore Private Sector Grows for 16th Month </td>
   <td style="text-align:left;"> The S&amp;P Global Singapore PMI rose to 52.9 in March 2022 from February's three-month low of 52.5, pointing to the 16th straight month of growth. Demand and output growth remained solid but decelerated, while both employment levels and buying activity declined. At the same time, the accumulation of backlogged work continued and at a solid rate. Longer suppliers’ delivery times were reported, mainly due to the COVID-19 pandemic, Ukraine war and manpower constraint. On inflation, input cost rose at a record pace, largely linked to  raw material, fuel and shipping costs.  Consequently, private sector firms continued to share these cost burdens with their clients, leading to the fastest increase of selling prices on record. Finally, sentiment turned pessimistic for the first time since August 2020, on geopolitical risks, the pandemic, and higher costs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/services-pmi </td>
   <td style="text-align:left;"> 2022-04-05 08:45:00 </td>
   <td style="text-align:left;"> Japan Services PMI Revised Higher </td>
   <td style="text-align:left;"> The au Jibun Bank Japan Flash Services PMI was at 49.4 in March 2022, compared with the preliminary estimate of 48.7 and a final of 44.2 in the prior month. The latest figure was the third straight month of contraction in the private sector but the softest pace in the sequence, amid the impact of easing COVID-19 restrictions, with new orders bouncing back for the first time in three months; while employment rose the most in five months. However, export orders shrank to the fastest rate since January 2021, reflecting renewed curbs across China and the Russia-Ukraine war. On inflation, input prices rose for 16 months, though the rate of inflation was broadly similar to that seen in February amid higher raw material costs. Meantime, the rate of charge inflation was slight as some firms offered discounts. Finally, sentiment hit its lowest since last August, due to worries about the impact of a resurgence in virus cases and the conflict in eastern Europe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/composite-pmi </td>
   <td style="text-align:left;"> 2022-04-05 08:39:00 </td>
   <td style="text-align:left;"> Japan Private Sector Rebounds </td>
   <td style="text-align:left;"> The au Jibun Bank Japan Composite PMI was at 50.3 in March 2022, compared with a flash reading of 49.3 and after a final 45.8 a month earlier. This marked the first growth in private sector activity since last December, amid  renewed rise in manufacturing output while services firms noted a much softer decline. New orders rose modestly for the fifth time in six months, and at the strongest pace in three months. Also, the rate of job creation reached a five-month high, with backlogs rising for the first time since December 2021, and at the fastest rate since June 2018. Firms in both sectors reported a further rapid rise in average cost burdens in March, with aggregate input prices rising at the sharpest pace since August 2008. Finally, sentiment dipped to the lowest since last August, amid concerns over the Russia-Ukraine war and a resurgence in COVID-19 cases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/services-pmi </td>
   <td style="text-align:left;"> 2022-04-05 08:20:00 </td>
   <td style="text-align:left;"> Ireland Services PMI Rises to 5-Month High </td>
   <td style="text-align:left;"> The AIB Ireland Services PMI increased to 63.4 in March from 61.8 a month earlier, pointing to the strongest growth in the sector since last October, and a faster expansion than the trend over the current 13-month sequence of increase. There was further strong growth in new business including exports, as demand improved with the continued reopening of markets, while employment rose at its fastest pace since August. On prices, input price inflation accelerated to the fastest since the survey began in 2000, due to higher labour, energy, fuel, insurance, and transport costs. Meanwhile, output cost inflation also rose at a record pace. Finally, business sentiment weakest since the start of 2021 due to the war in Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/inflation-cpi </td>
   <td style="text-align:left;"> 2022-04-05 08:19:42 </td>
   <td style="text-align:left;"> South Korea Inflation Rate Hits 10-Year High </td>
   <td style="text-align:left;"> Consumer prices in South Korea rose 4.1% in March 2022 from a year earlier, accelerating at the fastest pace in more than a decade, fueled by soaring energy and commodity prices due to the Ukraine crisis and adding pressure on the central bank ahead of its meeting next week. This also followed a 3.7% gain in February and came in higher than the 3.8% consensus forecast. Data showed that the cost of petroleum surged 31.2%, while that of electricity, gas and water rose 2.9%. Housing rentals and outdoor dining also jumped 2% and 6.6%, respectively. South Korea’s inflation has held above 3% since October, well in excess of the central bank’s 2% target, keeping the pressure on the Bank of Korea despite having raised interest rates three times since August to 1.25%. The BOK faces the challenge of controlling inflation without stifling growth at its meeting next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/04/us/new-york-asian-women-attacks-charges/index.html </td>
   <td style="text-align:left;"> 2022-04-05 08:09:02 </td>
   <td style="text-align:left;"> New York man indicted on multiple hate crime charges in attacks on 7 Asian women - CNN </td>
   <td style="text-align:left;"> (CNN)A man who allegedly assaulted seven Asian women over about a three hour period in New York City in late February has been indicted on multiple hate crime charges, the Manhattan District Attorney's Office announced Monday.                                                                                                                                                                        , Steven Zajonc, 28, is charged with six felony counts of third-degree assault as a hate crime and seven counts of second-degree aggravated harassment, a misdemeanor hate crime.                                                                                                                                                                                                                            , CNN has not been able to identify an attorney for Zajonc and has reached out to the Legal Aid Society to inquire whether its lawyers are representing him.                                                                                                                                                                                                                                                 , On February 27, Zajonc allegedly began a series of unprovoked attacks on the women on the east side of Manhattan, according to the district attorney's office.                                                                                                                                                                                                                                             , "These attacks on seven New York women, each fueled by anti-Asian hate, are yet another sobering reminder of the demonstrable fears AAPI communities, particularly AAPI women, in our City continue to face," District Attorney Alvin Bragg said in the release.                                                                                                                                           , "As alleged, within just three hours, Steven Zajonc selectively ambushed seven Asian women in separate assaults, some of which he struck from behind -- for no other reason than their perceived race. This indictment is a result of our collaboration with the NYPD's Hate Crimes Task Force, and critically, assistance from the brave witnesses and victims who came forward to stand up against hate.", Six victims were injured, including bleeding cuts and bruises to their faces, and one victim was knocked unconscious and treated for a concussion, according to prosecutors.                                                                                                                                                                                                                               , The victims ranged in age from 19 to 57, according to police information just after the attacks. At least two were treated at a hospital, according to police.                                                                                                                                                                                                                                             , No statements were made before the attacks, and there was no prior interaction between the victims and the assailant, police said.                                                                                                                                                                                                                                                                         , Hate crimes against Asians increased so much during the Covid-19 pandemic that the New York Police Department created an Asian Hate Crime Task Force.                                                                                                                                                                                                                                                      , The NYPD has recorded 158 incidents of hate crimes against Asians between March 8, 2020, and December 29, 2021. One victim, a 61-year-old woman, died from her injuries four months after being attacked by a man with a rock.                                                                                                                                                                             , The Manhattan District Attorney's Office says it has 27 open cases related to anti-Asian crimes.                                                                                                                                                                                                                                                                                                           , CNN's Theresa Waldrop, Kiely Westhoff and Mirna Alsharif contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/04/bear-market-rally-setting-stage-for-correction-morgan-stanley-warns.html </td>
   <td style="text-align:left;"> 2022-04-05 08:07:14 </td>
   <td style="text-align:left;"> 'Bear market rally' is setting stage for a correction, Morgan Stanley's Mike Wilson warns </td>
   <td style="text-align:left;"> , A major Wall Street firm is on correction watch.                                                                                                                                                                                              , Despite the latest market bounce, Morgan Stanley's Mike Wilson is bracing for an S&amp;P 500 decline of at least 13% between now and September.                                                                                                   , Wilson cited technical headwinds on CNBC's "Fast Money" on Monday.                                                                                                                                                                            , "It does have all the hallmarks of what I would call a bear market rally," said the firm's chief U.S. equity strategist and chief investment officer. "Things got oversold."                                                                  , He also singles out the tech-heavy Nasdaq, which rallied almost 2% on Monday. It's up more than 13% over the past three weeks.                                                                                                                , "The Nasdaq has run into resistance again here.... throwing back into the 200-day moving average," Wilson added. "It's a good time to remain defensive because, look, we're late cycle."                                                      , He has been worried the inflation surge and Federal Reserve's tightening policy increases recession risks. It could create an environment, according to Wilson, where stocks perform worse than bonds.                                        , "We don't think there's a recession this year. But maybe next year there could be one," Wilson said. "So, the markets are going to trade defensively."                                                                                        , Wilson, the market's biggest bear, believes the S&amp;P 500 will ultimately end the year at 4,400 — about a 9% drop from the index's all-time high hit on Jan. 4.                                                                                 , "We're doubling down on defensives," Wilson wrote in his Monday research note. "Growth is becoming the primary concern for equity investors rather than higher rates."                                                                        , Wilson's market playbook includes utilities, consumer staples and health care to outperform.                                                                                                                                                  , On "Fast Money" last winter, he also touted the merits of stock picks with defensive qualities and a burst below 4,000.                                                                                                                       , "I need something below 4,000 to get really constructive," said Wilson on Jan. 24. "I do think that'll happen."                                                                                                                               , Now, he's open to toning down his bearishness if the Fed doesn't raise rates as fast or as hard.                                                                                                                                              , "That's probably off the table given the inflation that's out there," noted Wilson. "But that would be a real elixir that would allow the markets to probably go a little bit further."                                                       , He also lists better-than-expected earnings as a potential upside wildcard. First quarter earnings season begins a week from Wednesdays.                                                                                                      , "If we're going to be wrong, it's going to be on earnings. It's not going to be because financial conditions loosen up again," Wilson said. "It's going to be because earnings don't disappoint as we're expecting as we go through the year.", Disclaimer                                                                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-05/shanghai-reports-record-13-354-covid-cases-for-monday?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-05 08:05:04 </td>
   <td style="text-align:left;"> Shanghai Covid Cases Top 13,000 as Millions Locked Down </td>
   <td style="text-align:left;"> Empty roads during a phased lockdown in Shanghai on April 4.                                                                                                                                                                                                                                                                                                          , Shanghai reported more than 13,000 daily Covid cases for the first time, as a sweeping lockdown of its 25 million residents and mass testing uncovered extensive spread of the highly infectious omicron variant.                                                                                                                                                     , The Chinese financial hub registered 13,354 local cases for Monday, up from 9,006 a day earlier and from near zero at the start of March, according to a local government statement. Of the total, 13,086 were asymptomatic infections. More than 12,600 cases were found among people in quarantine while the rest were uncovered during checks on high-risk groups.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/household-spending </td>
   <td style="text-align:left;"> 2022-04-05 07:42:00 </td>
   <td style="text-align:left;"> Japan Personal Spending Rises Less than Estimated </td>
   <td style="text-align:left;"> Household spending in Japan increased by 1.1% in real terms from the prior year in February 2022, below market forecasts of 2.7 percent and easing sharply from a 6.9% rise a month earlier which was the steepest pace in eight months. While expanding for the second straight month, the latest figure indicated that the consumer sector is facing growing headwinds from soaring prices, a weakening yen and the rapid spread of the Omicron variant. Spending on transport rose much softer (11.4% vs 32.2% in January), amid declines in consumption of food (-3.6 % vs 0.2%), furniture (-5.0% vs 2.8%), medical care (-0.9% vs 8.8%), housing (-5.3% vs 13.4%), clothing (-11.0% vs 5.9%), and education (-14.4% vs -3.9%). At the same time, spending on culture &amp; recreation grew faster (5.6% vs 4.8%), while there was a rebound in consumption of fuel, light &amp; water charges (1.9% vs -3.4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-04/oil-pushes-higher-on-specter-of-fresh-sanctions-against-russia?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-05 07:34:36 </td>
   <td style="text-align:left;"> Oil Extends Surge on Specter of Fresh Sanctions Against Russia </td>
   <td style="text-align:left;"> Jake Lloyd-Smith                                                                                                                                                                                                                                                                                               , Oil advanced for a second day as the U.S. and Europe prepared to impose a fresh wave of sanctions on Russia for alleged atrocities committed by its forces against civilians in Ukraine.                                                                                                                       , West Texas Intermediate pushed to near $105 a barrel in early Asian trading after closing 4% higher on Monday, the biggest gain in two weeks. Washington will announce additional measures this week, according to National Security Advisor Jake Sullivan, who said these may include further curbs on energy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/04/europe/ukrainian-teenage-refugee-budapest-school-intl/index.html </td>
   <td style="text-align:left;"> 2022-04-05 06:41:51 </td>
   <td style="text-align:left;"> Fleeing Ukraine alone, resourceful teenager persuades Hungarian school to take her in - CNN </td>
   <td style="text-align:left;"> Budapest, Hungary (CNN)It's a normal school day for students at the Korosi Baptist High School in Budapest, Hungary -- studying, presenting classwork, laughing with friends.                                                                                                                                              , Among them is 17-year-old Alla Renska, a tall girl with long blonde hair, carrying her hot pink backpack from class to class.                                                                                                                                                                                              , But Renska is no ordinary student, and she is no longer living an ordinary life -- or the life she envisioned just weeks ago.                                                                                                                                                                                              , Back then, Renska was studying for college exams in her home city of Kyiv, Ukraine, with plans to become an English and Turkish translator.                                                                                                                                                                                , Russia's invasion of Ukraine changed all that.                                                                                                                                                                                                                                                                             , "We heard explosions and our house was shaking," Renska tells CNN.                                                                                                                                                                                                                                                         , That's when her parents made the agonizing decision to send her to safety, out of the country.                                                                                                                                                                                                                             , She still can't believe how quickly her life has changed since the Russian invasion. "It's (the) 21st century, it's Ukraine, it's Europe, why?"                                                                                                                                                                            , Renska's parents arranged for her to stay with good friends in Hungary as they remained behind in Ukraine to care for her elderly grandmother, who is too frail to travel.                                                                                                                                                 , She packed quickly.                                                                                                                                                                                                                                                                                                        , "I will never forget that day," she says, recalling the crowds of people who were sheltering in the subway for protection from falling artillery. "Oh my God, so many people were there!"                                                                                                                                  , When Renska arrived at the train station, the crush of the crowd prevented her from saying goodbye to her father. She was shoved onto the train and that was it.                                                                                                                                                           , "I cried," Renska recalls, "maybe all night."                                                                                                                                                                                                                                                                              , Not long after the train left, an air raid siren sounded. Her father had to sleep in the station, not knowing if her train was safe. He wouldn't hear from her until she got to Hungary.                                                                                                                                   , Renska took few photos during the journey -- only ones showing a bleak landscape that she says matched how she felt.                                                                                                                                                                                                       , It was during the train journey that she decided to write an email to Korosi Baptist High School, one of Hungary's top schools.                                                                                                                                                                                            , She wrote about the war and explained what had happened to her. She also told them of her accomplishments.                                                                                                                                                                                                                 , "I won competitions in the history of Ukraine, the Ukrainian language and foreign literature," Renska wrote. "And I have already written three scientific papers at the Kyiv branch of the Small Academy of Sciences in 2020, 2021."                                                                                       , She ended her email with a plea, "I really want to go to school and continue studying!!! I kindly ask you to help me."                                                                                                                                                                                                     , She dated the letter, "The 10th day of the war in Ukraine."                                                                                                                                                                                                                                                                , And help they did.                                                                                                                                                                                                                                                                                                         , School officials launched an appeal among parents of the school community, raising about $90,000 to convert some spare shipping containers into dorm rooms with bedrooms, bathrooms, showers and a small kitchen outside the main school building.                                                                         , These containers are now where Renska sleeps and studies.                                                                                                                                                                                                                                                                  , She spends her days in classes and learning a new language -- Hungarian.                                                                                                                                                                                                                                                   , Nights are spent in the dorm room with a few other teenage girls who also recently fled Ukraine and were welcomed in by the school.                                                                                                                                                                                        , Renska says she likes living so close to the school and having the chance to meet other students from Ukraine.                                                                                                                                                                                                             , "In Ukraine I had an incredible class and wonderful teachers. And here are also extraordinary people," she says, adding that they are "wonderful people who have become my family."                                                                                                                                        , The principal of Korosi Baptist High School says it now has enough space to house 12 more students from Ukraine in the coming weeks.                                                                                                                                                                                       , The school has also provided the girls with a psychologist, a Russian woman, who helps them cope with the trauma they've experienced.                                                                                                                                                                                      , Despite that trauma, Renska says she tries to remain stoic.                                                                                                                                                                                                                                                                , "I try not to cry and I try to be strong because my parents, I know that when I cry it makes them feel not very good."                                                                                                                                                                                                     , That strength is on display when Renska video calls her parents. It's all smiles as she updates them on school and work.                                                                                                                                                                                                   , Her mother, Indira Renska, says that she cannot explain how she feels with her daughter so far away.                                                                                                                                                                                                                       , "It's too painful (to talk about),"  Indira says. "I love her very much. That she is safe now is the main (thing) for me."                                                                                                                                                                                                 , After the call ends and her mother hangs up, Renska's brave facade falters and she begins to cry.                                                                                                                                                                                                                          , "It's so unfair that I should be here and my parents there," she says.                                                                                                                                                                                                                                                     , Nonetheless, she is determined to stay optimistic.                                                                                                                                                                                                                                                                         , "I just would like a normal life," Renska says, believing that one day she will be able to return to Ukraine, where she can go back to making goofy videos with her friends, taking selfies and to playing the bandura, a classic Ukrainian instrument that has become a symbol of her country's fight for its existence.  , For now, she holds on to a photo her parents sent to her right after she left. It shows the first spring flower to push through the snow near her home.  A sign, they say, of brighter times to come.                                                                                                                      , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/construction-pmi </td>
   <td style="text-align:left;"> 2022-04-05 06:34:00 </td>
   <td style="text-align:left;"> Australia Construction PMI at 4-Month High </td>
   <td style="text-align:left;"> The Australia AiG Construction PMI increased by 3.1 points to 56.5 in March of 2022, from 53.4 in February and after a temporary contraction reported in December 2021-January 2022. The latest reading pointed to the second consecutive month of expansion in construction activity and at the fastest pace since last November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-04/vekselberg-yacht-seized-after-tip-from-ship-design-firm-manager?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-05 06:33:09 </td>
   <td style="text-align:left;"> Vekselberg Yacht Seized After Tip From Ship-Design Firm Manager </td>
   <td style="text-align:left;"> A Guardia Civil officer stands next to the Tango superyacht in Palma de Mallorca, Spain, on April 4.                                                                                                                                     , Photographer: Francisco Ubilla/AP Photo                                                                                                                                                                                                  , Erik Larson                                                                                                                                                                                                                              , It’s hard to keep a $90 million yacht a secret.                                                                                                                                                                                          , Viktor Vekselberg had his seized in Spain after U.S. authorities got crucial information from a manager at a company that helped the Russian billionaire and his wife design and purchase the 78-meter-long (256 feet) ship called Tango. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-04/tech-led-u-s-stock-climb-set-to-support-asia-open-markets-wrap </td>
   <td style="text-align:left;"> 2022-04-05 06:20:43 </td>
   <td style="text-align:left;"> Stocks Waver, Crude Rises Amid Tension Over Russia: Markets Wrap </td>
   <td style="text-align:left;"> Sunil Jagtiani                                                                                                                                                                                                                 , Stocks in Asia were mixed Tuesday and crude oil climbed as investors evaluated the prospect of tougher sanctions against Russia for alleged atrocities during its war in Ukraine.                                              , Shares rose in Australia but retreated in Japan and South Korea, where faster inflation added to the case for more interest-rate hikes. U.S. equity futures dipped after the technology sector bolstered Wall Street on Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-04/citi-said-to-pause-new-spac-issuance-as-sec-signals-crackdown?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-05 06:19:50 </td>
   <td style="text-align:left;"> Citi to Pause New SPAC Issuance as SEC Signals Crackdown </td>
   <td style="text-align:left;"> Gillian Tan                                                                                                                                                                                                                                                                               , Citigroup Inc. is among underwriters that have temporarily paused initial public offerings of new U.S. special purpose acquisition companies until they get more clarity on the potential legal risks posed by recently proposed rules, according to people with knowledge of the matter. , The New York-based bank is awaiting feedback from legal advisers regarding underwriter liability among other topics, said the people, who requested anonymity because the bank’s decision isn’t public. The firm has no plans to exit the business, some of the people said.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/04/business/1mdb-trial-roger-ng.html </td>
   <td style="text-align:left;"> 2022-04-05 06:06:37 </td>
   <td style="text-align:left;"> 1MBD Trial: Prosecutors Urge Conviction of Former Goldman Banker Roger Ng - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                               , The defense said the only evidence of involvement by Roger Ng, who is accused of receiving illegal kickbacks, was the testimony of Tim Leissner, a former Goldman partner who admitted on the stand to lying a lot.                                                                                                                                                                                         , By Matthew Goldstein                                                                                                                                                                                                                                                                                                                                                                                        , A federal prosecutor told jurors on Monday that they had received enough evidence to convict a former Goldman Sachs banker for his role in one of the biggest international money laundering and bribery schemes even without the testimony of the government’s star witness.                                                                                                                               , “You already know the defendant is guilty from other evidence in the case,” Alixandra E. Smith, an assistant U.S. attorney, said during the government’s closing argument in the trial of Roger Ng in federal court in Brooklyn.                                                                                                                                                                            , Mr. Ng is accused of receiving $35 million in illegal kickbacks from a scheme to steal billions of dollars from the once-big Malaysian sovereign wealth fund known as 1MDB.                                                                                                                                                                                                                                 , Over the course of the trial, Tim Leissner, a former Goldman partner who pleaded guilty and became the government’s star witness, emerged as a controversial figure, and it is not surprising federal prosecutors want the jury to not focus too much on his testimony.                                                                                                                                     , During six days of a grueling cross-examination he admitted to lying a lot in life. He was forced to admit to initially lying to federal agents, to his fellow partners at Goldman and to his wives and girlfriends.                                                                                                                                                                                        , But Ms. Smith said Mr. Leissner did not lie when he testified in federal court in Brooklyn to the key facts of the scheme, which was funded by a series of bond offerings that Goldman arranged for the 1MDB fund.                                                                                                                                                                                          , When it was time for Mr. Ng’s lawyer to present his closing arguments, he did not waste time calling out Mr. Leissner. The lawyer, Marc Agnifilo, said Mr. Leissner was a man who “will lie if it suits his interest.” He said that, despite what the prosecution had said, without Mr. Leissner’s testimony the government could not connect Mr. Ng to the conspiracy to steal billions from the 1MDB fund., “There is no evidence that connects Roger,” Mr. Agnifilo said. “There is not a dirty email. Not a bad text message.”                                                                                                                                                                                                                                                                                        , By contrast, Mr. Agnifilo said, the jury had seen text messages in which Mr. Leissner was instructed on whom to pay bribe money to by Jho Low, a flamboyant Malaysian businessman who was the architect of the scheme and is a fugitive believed to be living in China.                                                                                                                                     , Mr. Agnifilo said Mr. Leissner had lied to the jury just as he had done other times in his life.                                                                                                                                                                                                                                                                                                            , “It’s a lifetime of lying,” said Mr. Agnifilo. “This is lying on a rare level.”                                                                                                                                                                                                                                                                                                                             , Last week, the jury heard testimony from Mr. Ng’s wife, Hwee Bin Lim, who said the $35 million she and her husband received was the proceeds from a $6 million investment she made with Mr. Leissner’s second wife, Judy Chan.                                                                                                                                                                              , The defense has argued Mr. Ng and his wife had been unaware that some of the money Ms. Chan transferred to them had been looted from 1MDB. Mr. Leissner has acknowledged getting tens of millions of dollars in illicit proceeds in the scheme.                                                                                                                                                             , The case could go to the jury as soon as Tuesday afternoon.                                                                                                                                                                                                                                                                                                                                                 , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-04/rates-markets-are-watching-rba-for-signs-of-an-early-may-hike?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-05 06:05:42 </td>
   <td style="text-align:left;"> Rates Markets Are Watching RBA for Signs of an Early May Hike </td>
   <td style="text-align:left;"> Philip Lowe, governor of the Reserve Bank of Australia.                                                                                                                                                                                                                                                        , Garfield Clinton Reynolds                                                                                                                                                                                                                                                                                      , Bond investors will be scrutinizing Tuesday’s Reserve Bank of Australia meeting for any signs policy makers will start their tightening cycle next month rather than wait until June.                                                                                                                          , The odds of a hike in May have oscillated wildly in recent weeks, with futures now indicating the outcome is a coin toss, down from a more-than 70% probability just a week ago. They have been as low as 27% this year and as high as 140% -- the latter signifying the chance of more than just one increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/04/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-04-05 06:03:02 </td>
   <td style="text-align:left;"> Stock futures are flat in overnight trading after tech-led rally </td>
   <td style="text-align:left;"> , Stock futures were flat in overnight trading Monday after investors bought the dip in technology shares following recent weakness.                                                                                                                                                                               , Futures on the Dow Jones Industrial Average dipped 14 points. S&amp;P 500 futures were little changed, and Nasdaq 100 futures edged 0.1% lower.                                                                                                                                                                      , The overnight action followed a tech-led rally that saw the Nasdaq Composite rise 1.9%. Shares of Twitter surged 27% for its best day ever after Elon Musk disclosed a 9.2% passive stake in the social media company.                                                                                           , The blue-chip Dow rose about 100 points to begin the trading week, while the S&amp;P 500 advanced 0.8%, both posting their second straight day of gains.                                                                                                                                                             , "In the near-term, we believe indiscriminate selling has created attractive entry points, particularly into some high-growth-potential stocks," Tony DeSpirito, CIO of U.S. fundamental equities at BlackRock, said in a note.                                                                                   , The new quarter has kicked off after the major averages finished their worst quarter in two years. Investors are awaiting the Federal Reserve meeting minutes Wednesday for further clues on the central bank's rate-hike path. Meanwhile, the first-quarter corporate earnings season is set to begin next week., "Markets have been resilient given the war in Ukraine, continued price pressures, and uncertain global economic outlook, with investors' 'buy the dip' mentality driving equity returns," said Mark Hackett, Nationwide's chief of investment research.                                                          , Investors are also keeping an eye on oil prices amid the supply disruptions stemming from Russia's invasion of Ukraine. WTI crude jumped more than 4% and traded back above $100 a barrel Monday.                                                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-04/wrong-footed-day-traders-learn-the-dangers-of-fighting-the-boj?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-05 05:35:41 </td>
   <td style="text-align:left;"> Wrong-Footed Day Traders Learn the Dangers of Fighting the Bank of Japan </td>
   <td style="text-align:left;"> Masaki Kondo and                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Ruth Carson                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Bond vigilantes bowed to the might of the Bank of Japan last week but its historic market intervention also sent another cohort scrambling to cut their losses -- retail traders with record bullish bets on the yen.                                                                                                                                                                                                                                                              , Japan’s individual investors cut aggregate net-long positions on their home currency by 56.1 billion yen ($457 million) from near a record high during four days of BOJ intervention last week, according to a Bloomberg analysis of Tokyo Financial Exchange Inc. data. The central bank sent the yen spiraling to a near seven-year low after announcing an unlimited bond-buying spree, reinforcing its policy divergence with other major central banks that are raising rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/04/04/southern-ukraine-nearby-russian-assualt-cnn-crew-wedeman-pkg-lead-vpx.cnn </td>
   <td style="text-align:left;"> 2022-04-05 05:35:07 </td>
   <td style="text-align:left;"> Watch: CNN crew survives close call in area under Russian assault - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/04/business/colorado-steel-plant-russia-military-invs/index.html </td>
   <td style="text-align:left;"> 2022-04-05 04:49:21 </td>
   <td style="text-align:left;"> Colorado steel plant owner potentially supplying Russia's military draws criticism - CNN </td>
   <td style="text-align:left;"> (CNN)The steel mill that looms over low-slung neighborhoods in Pueblo, Colorado, is a rare bright spot for American manufacturing. Once part of the state's largest private employer, pumping out steel that was used to build rail lines across the Western US, it is now in the midst of a major expansion and recently became the world's first steel plant to run almost entirely on solar power.                                                                                                                       , But in the wake of the invasion of Ukraine, the steelworkers and their city are grappling with an unpleasant reality that is no longer easy to ignore: The mill is owned by a company that has been accused of potentially supplying steel to build Russian tanks and whose largest stakeholder is a close ally of Russian President Vladimir Putin.                                                                                                                                                                         , The plant, which still ranks among the largest employers in the small city of Pueblo, was bought in 2007 by Evraz, one of Russia's major steel-producing companies. Evraz's biggest shareholder is the oligarch Roman Abramovich, who was sanctioned by the United Kingdom, the European Union and Canada last month.                                                                                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , In announcing its sanctions, the UK government alleged that Abramovich controlled Evraz and that the company was "potentially supplying steel to the Russian military which may have been used in the production of tanks." Abramovich was involved in "destabilising Ukraine" through Evraz, the sanctions office wrote.                                                                                                                                                                                                    , Evraz, which owns several other steel plants in Oregon and Canada in addition to the Pueblo mill, has denied that it supplies the Russian military and tried to distance itself from Abramovich. But its stock fell by 90% from the beginning of the year before it was suspended from the London Stock Exchange in the wake of the invasion, and its entire board of directors quit. The company nearly defaulted on its debt last month due to a sanctions-related delay in a bond payment.                                , Evraz's North American subsidiary and its employees say the steel produced in the US is not going to Russia. The North American operation doesn't send money to the parent company, and its profits are reinvested in its US and Canadian operations, according to executives.                                                                                                                                                                                                                                               , But in recent years, the parent company's operations have resulted in billions of dollars in dividends that have largely gone to Abramovich and a handful of other Russian oligarchs. Advocates for Ukraine say they're distressed that the US hasn't followed its allies in sanctioning Abramovich, and that a figure with close ties to Putin still holds the largest stake in the company that owns the Pueblo mill.                                                                                                      , "There is no clean money among the oligarchs," said Marina Dubrova, the founder of Ukrainians of Colorado, a non-profit organization that has raised funds to send medical supplies to Ukraine. Even if he were to own a "half percent, even one-tenth of a percent" in the company, she argued, "Abramovich has to be sanctioned and his portion has to go to the highest bidder."                                                                                                                                          ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , So far, executives and local employees at the Pueblo plant say there has been no impact on their day-to-day job. But some workers are worried about whether that could change if more sanctions go into effect.                                                                                                                                                                                                                                                                                                              , "Just the uncertainty is scary, it's real scary," said Rique Lucero, a metallurgical technician who has worked at the plant for 14 years. "We wonder how the war is going to further affect us."                                                                                                                                                                                                                                                                                                                             , The Evraz situation is an example of how Russian investment in the West could be complicating sanctions: The company employs more than 1,600 people in the US, and the need to avoid job losses could make officials more cautious about sanctioning Abramovich, sanctions experts said.                                                                                                                                                                                                                                     , And the company also shows that the Russian elite's money in the US goes deeper than stereotypical luxury items -- even reaching a historic icon of American industry.                                                                                                                                                                                                                                                                                                                                                       , Most people think Russian "oligarchs have been putting their money primarily into these mega-mansions, these superyachts, high-end artwork, Ferraris, Maseratis," said Casey Michel, the author of a book on foreign investment in the US. But in addition to those flashy status symbols, he said, "there are so many other significant industries that are wide-open for all this oligarchic money."                                                                                                                       , A plant that 'built the American West'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Every hour, tons of recycled scrap metal are dropped into the Pueblo mill's massive furnace, with a deafening boom and an eruption of golden sparks. The metal is heated at about 3000 degrees Fahrenheit into white-hot, molten steel, then cooled and carefully rolled into rail, wire rod, rebar or pipe.                                                                                                                                                                                                                 , That transformation has been taking place here, in one form or another, since the mill was founded in 1881 as the first steel plant west of the Mississippi River.                                                                                                                                                                                                                                                                                                                                                           , Owned by the Colorado Fuel and Iron Company, which grew into Colorado's largest private employer, the mill attracted workers from around the world. At one point, 40 languages were spoken at the mill and its mines. It pumped out rail that stretched around the region, speeding migration across the sparsely settled Western US.                                                                                                                                                                                        , "This steel really built the American West," said Nick Gradisar, Pueblo's mayor, whose father and grandfather worked at the mill, and who worked there himself several summers during college. "It used to be that the fortunes of Pueblo rose and fell on the economics of the steel industry."                                                                                                                                                                                                                             , The city experienced the downside of that relationship when the price of steel crashed in the 1980s. Thousands of workers at the plant lost their jobs over several years, local leaders say.                                                                                                                                                                                                                                                                                                                                ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , After the downturn, the mill went through bankruptcy and was bought by an Oregon-based company. Evraz bought the parent company in 2007 for $2.3 billion, in what was at the time the largest ever Russian investment in the US.                                                                                                                                                                                                                                                                                             , According to the company's 2021 annual report, five percent of Evraz employees are in North America and about 16% of its revenue comes from its North American steel operation. Most of its other mills are in Russia and Kazakhstan.                                                                                                                                                                                                                                                                                        , As of February, Abramovich, a globe-trotting owner of the Chelsea soccer team who holds citizenship in at least two other countries, owned the largest stake in Evraz, at roughly 29%, according to the company. But the UK sanctions office argued that he effectively controls the company, which is publicly traded, along with his associates: Four other Russian oligarchs control another 38% of the company.                                                                                                          , Evraz has been a lucrative investment for Abramovich and other oligarchs. In 2021, according to its annual report, almost half of Evraz's profit went to paying out more than $1.5 billion in dividends to its shareholders -- two-thirds of which went to the five largest Russian shareholders. Evraz's financial performance in 2021 "made it possible to pay" such generous dividends, the company wrote in the annual report, citing numbers that included a big increase in earnings in its North American operations. ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Abramovich also has myriad investments in the US hidden through complicated networks of shell corporations and hedge funds, The New York Times reported last month. But his shares in Evraz are in his own name, as are two mansions he owns in Colorado ski towns. A spokesperson for Abramovich declined to comment about Evraz.                                                                                                                                                                                           , While the Pueblo mill now has far fewer employees than at its peak, it still puts out about half of all rail used in North America. And while it's no longer the biggest employer in the city, it's still the source of some of the best-paying blue-collar jobs in the region, local leaders say.                                                                                                                                                                                                                           , "Just about everyone that's a resident of Pueblo has had family that's worked out there," some going back four generations or more, said Jeff Shaw, president of the Pueblo Economic Development Corporation.                                                                                                                                                                                                                                                                                                                , How Russia's war could affect Colorado steel                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Most people in Pueblo don't really think of the mill as Russian-owned, according to interviews with city leaders and local residents. Instead of referring to it as Evraz, locals still call it CF&amp;I -- Colorado Fuel and Iron -- or just "The Mill."                                                                                                                                                                                                                                                                        , But the new ownership became impossible to ignore over the last few weeks, when Russia launched its invasion of Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                     , Chuck Perko, the president of one of the two United Steelworkers unions that represent workers at the plant, said he got "dozens of phone calls" about the potential impact in the days after the invasion and after the UK and EU governments announced sanctions against Abramovich.                                                                                                                                                                                                                                       , "Retirees are worried, will the company continue to exist, will their pensions stay solvent?" he said. "Families want to know, is my husband or wife going to have a job tomorrow?"                                                                                                                                                                                                                                                                                                                                          , In the weeks since, however, Perko said he hasn't seen any real impact on the Pueblo mill's operations. "I'm worried more about the people in Ukraine than I am about my people being affected by it," Perko added.                                                                                                                                                                                                                                                                                                          ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Evraz says it's business as usual in Pueblo. David Ferryman, the Evraz North America senior vice president who runs the Pueblo plant, said watching the war in Ukraine was "heartbreaking," but argued that critics of Evraz were painting any connection to Russia with "a broad brush."                                                                                                                                                                                                                                    , "We have our own CEO, we have our own board of directors ... we're about as American a company as it gets," said Ferryman, sitting in a room in the company's Pueblo office with walls covered in historic photos of the plant. "Those earnings stay here in North America, and they're invested into these facilities."                                                                                                                                                                                                     , The US government has not publicly explained why it hasn't targeted Abramovich with sanctions like the UK, EU and Canada. But Ukrainian President Volodymyr Zelensky asked President Biden in early March not to sanction Abramovich, who has acted as an unofficial go-between for Moscow and Kyiv, in order to allow him to play a role in the peace process, according to two sources with direct knowledge. The Wall Street Journal first reported Zelensky's request.                                                   , It's unclear how active or central Abramovich has been in the negotiations since then. A Kremlin spokesperson confirmed that Abramovich was involved in peace talks, and he was present at a meeting between the two sides in Istanbul last week.                                                                                                                                                                                                                                                                            , Treasury Department officials were examining sanctions on Abramovich that would exempt Evraz's US plants as part of a wide-ranging effort to limit economic fallout of new sanctions, the sources said. A Treasury spokesperson declined to comment about the potential of US sanctions on Abramovich, saying the department doesn't preview sanctions.                                                                                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , According to sanctions experts, if the US does sanction Abramovich, the Treasury Department would likely issue a license allowing the Pueblo and Portland steel mills to continue operating in order to avoid any impact on American employees.                                                                                                                                                                                                                                                                              , "If 1,000 Americans are going to lose their jobs, that could impact their decisions," said Charlie Steele, a former Treasury Department and Department of Justice official who worked on sanctions policy.                                                                                                                                                                                                                                                                                                                   , Even without US sanctions, the UK, EU and Canadian actions appear to have complicated Evraz's financial picture, between its stock being suspended from the London exchange and the near-miss in its bond payment. And the broader impact of sanctions can be unpredictable, especially if financial institutions decide they want to avoid the potential stigma of working with companies linked to Russia, experts said.                                                                                                   , Even if banks are allowed to work with the company, Steele said, "they might say, I'm not going to get within 100 miles of that."                                                                                                                                                                                                                                                                                                                                                                                            , Russian investment in America's industrial heartland                                                                                                                                                                                                                                                                                                                                                                                                                                                                         ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , While many major US businesses have expanded in Russia over the last two decades -- and are now cutting ties -- Evraz is a rare example of investment flowing in the opposite direction.                                                                                                                                                                                                                                                                                                                                     , There are a handful of other US steel plants in the country with ties to Russian oligarchs. NLMK, one of Russia's largest steel companies, owns plants in Pennsylvania and Indiana. And Severstal, another major Russian steel producer, bought several plants around the US, including in Mississippi and Michigan, before selling them in 2014 as tensions escalated over the invasion of Crimea.                                                                                                                          , Meanwhile, other proposals for Russian investment in US manufacturing have fallen through over the last decade, in some cases because of past sanctions -- including plans for factories in Louisiana and North Carolina.                                                                                                                                                                                                                                                                                                    , Most notably, in 2019, Russian aluminum company Rusal announced with great fanfare a $200 million investment to build an aluminum factory in eastern Kentucky, promising hundreds of new jobs in the economically struggling region. The investment came just months after the Trump administration lifted sanctions on Rusal -- which had previously been run by oligarch and Putin ally Oleg Deripaska -- amid an extensive lobbying campaign by the company.                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , But the Kentucky factory plan fell apart in recent years as Rusal backed out, leaving an empty greenfield and angry state legislators trying to claw back a $15 million taxpayer investment in the project.                                                                                                                                                                                                                                                                                                                  , By all accounts, Evraz has done the opposite. Workers say that their new owners have been far easier to work with than the previous, Oregon-based management, whose contentious relations with unions led to years of strikes and labor disputes. And they're thrilled with the new investments Evraz is making in Pueblo, which have led to a bevy of construction cranes stretching up into the sky around the plant.                                                                                                      , "Locally, Evraz has been a great partner," said Jerry Pacheco, the executive director of the Pueblo Urban Renewal Authority, which has helped fund the expansion.                                                                                                                                                                                                                                                                                                                                                            , The company is in the middle of building a new $700 million steel mill that will produce much longer segments of rail, helping them compete for contracts to build high-speed rail lines and other rail projects. The project is set to receive at least $84 million in public incentives from the city and state governments and the urban renewal authority, and potentially up to $118 million — with certain requirements including retaining jobs and paying higher property taxes in the future.                       , Evraz has invested more money into the Pueblo expansion in recent years than any capital project at its facilities around the world, according to the company's annual reports.                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ,  Evraz also just finished a solar power project that makes it the first steel plant in the world to be powered almost exclusively with solar power -- putting it on the cutting edge of green manufacturing. A sprawling field of solar panels now lies just beyond the historic mill buildings, swiveling to face the sun and stockpile the energy needed for the mill.                                                                                                                                                     , The public incentives were crucial in keeping Evraz in Pueblo: The company had been exploring the possibility of moving its operation to another state before city leaders agreed to kick in the funding, and Gradisar argued that the taxpayer money was well worth it. "Good jobs for blue-collar workers, those are hard to come by in this day and age," he said.                                                                                                                                                        , Moral dilemmas at an 'All-American' mill                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Like many communities across the US, Pueblo is stepping up to help Ukraine. The county sheriff donated unused body armor to the Ukrainian military. A boy scout troop held a fundraiser for Ukrainian scouts at the local Pizza Ranch. A new mural painted on the levee of the Arkansas River, which runs through the city, displays the colors of the Ukrainian flag and a sunflower, the country's national flower.                                                                                                        , But there's little public consternation or debate about Pueblo's close ties with a company accused of potentially supplying Russia's war effort.                                                                                                                                                                                                                                                                                                                                                                             , "It's not a big concern for me right now," Gradisar, the mayor, said of the Russian connection to the mill. He said he wanted to see stability at the plant: "Those are tough operations to operate and run, and you need to know what you're doing."                                                                                                                                                                                                                                                                        , "I've had people suggest to me we should seize the mill, whatever that means," Gradisar added. "I didn't even respond to that."                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Other Pueblans agree that they're not bothered by the Russian ownership. As she waited for a lunch table at Estela's Mill Stop Cafe, a popular Mexican joint around the corner from the Evraz offices, Carol Trujillo said she never thought of the company as Russian-owned before the latest string of headlines.                                                                                                                                                                                                          , "To us, it's All-American," she said of the mill, listing her relatives who had worked there over the years: uncles, aunts, a brother, her grandmother. "I don't think the ownership matters to what the people do here."                                                                                                                                                                                                                                                                                                    , Some officials in Canada have called on Evraz to divest from its steel mills there, to avoid any connection with the invasion of Ukraine. "That is actually the way out of this in terms of the balance between needing to support Ukraine and accepting those sanctions and protecting the employment and the ... livelihood of those workers," Sandra Masters, the mayor of Regina, Saskatchewan, which is home to a major Evraz plant, said last month.                                                                   , Perko, the union president, and several other steelworkers said they would be happy to see Abramovich's shares sold off, or the mill return to American ownership.                                                                                                                                                                                                                                                                                                                                                           , "We're fairly independent to the point that if something were to really happen, we could be ripped away from the parent company and run independently," Perko said.                                                                                                                                                                                                                                                                                                                                                          ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Some steelworkers said they've been feeling the moral dilemma of working for a company with ties to Russia. Daniel Duran, an accounting clerk who has been at the mill for five years after a string of nonunion, low-paying jobs in construction and at Walmart, said he loves working at Evraz, and credits the job for letting him give his four children a good life in Pueblo.                                                                                                                                          , "Honestly, this job has afforded me everything I have today," Duran said. "I have always thought of this place as being American hands forging US steel."                                                                                                                                                                                                                                                                                                                                                                    , But when he's turned on the news to see Ukrainian families fleeing Russian tanks, he said he's found himself getting emotional. "I have my own kids, so it makes it tough to sit there and see all this stuff going on and try turning a blind eye," he said.                                                                                                                                                                                                                                                                , Sitting in his empty union hall, a 100-year-old Mission Revival-style building with long cracks running up the walls, Perko said that watching the videos from Ukraine reminded him of his own family history: his grandmother fled the Soviet army as a refugee from Yugoslavia during World War II.                                                                                                                                                                                                                        , "I disdain what's going on over there," Perko said of Ukraine. "But my company is not Abramovich's company in my eyes -- and so it helps me sleep at night to know that we've got so much separation from the larger picture."                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , CNN's Drew Griffin, Scott Bronstein and Phil Mattingly contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/entertainment-arts-60985496?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-05 04:46:14 </td>
   <td style="text-align:left;"> Channel 4 privatisation to go ahead </td>
   <td style="text-align:left;"> The government has decided to go ahead with plans to privatise Channel 4.                                                                                                                                                                                                                                                               , A source said ministers believed public ownership was holding the broadcaster back "in the face of a rapidly changing media landscape".                                                                                                                                                                                                 , Plans for the sale, on which there has been a public consultation, will be included in May's Queen's Speech.                                                                                                                                                                                                                            , But Channel 4 called it "disappointing" that ministers had made their decision despite "significant public interest concerns" over privatisation.                                                                                                                                                                                       , Money made from the sale will be reinvested in a "creative dividend" to be shared among the TV industry, with some of it earmarked for independent production companies.                                                                                                                                                                , Channel 4, founded by Margaret Thatcher's Conservative government in 1982 to deliver programmes for under-served audiences, is funded by advertising but is publicly owned.                                                                                                                                                             , Culture Secretary Nadine Dorries said: "Channel 4 rightly holds a cherished place in British life and I want that to remain the case. I have come to the conclusion that government ownership is holding Channel 4 back from competing against streaming giants like Netflix and Amazon.                                                , "A change of ownership will give Channel 4 the tools and freedom to flourish and thrive as a public service broadcaster long into the future."                                                                                                                                                                                          , A government source said the channel would lose its "straitjacket" but retain its commitment to primetime news programming.                                                                                                                                                                                                             , When it was announced last year that the government was carrying out a consultation on privatising Channel 4, its bosses warned of "a real risk" to some of its programmes.                                                                                                                                                             , Responding to the announcement that the move was going ahead, a spokesperson for the broadcaster said: "With over 60,000 submissions to the government's public consultation, it is disappointing that today's announcement has been made without formally recognising the significant public interest concerns which have been raised.", They added that there needed to be a "lengthy legislative process and political debate", saying: "Channel 4 remains legally committed to its unique public-service remit.                                                                                                                                                               , "The focus for the organisation will be on how we can ensure we deliver the remit to both our viewers and the British creative economy across the whole of the UK."                                                                                                                                                                     , In 2019, Channel 4, which brought shows including Friends, Big Brother and Countdown to UK audiences, opened a base in Leeds, to operate alongside its London headquarters.                                                                                                                                                             , For Labour, shadow culture secretary Lucy Powell said: "Selling off Channel 4, which doesn't cost the taxpayer a penny anyway, to what is likely to be a foreign company, makes absolutely no sense. It will cost jobs and opportunities in the North and Yorkshire, and hit the wider British creative economy."                       , Liberal Democrat culture spokesman Jamie Stone said: "Occasionally, we as a country manage to magic up a world-renowned gem into being and Channel 4 is a perfect example. And yet this government seems hell-bent on trashing this uniquely British legacy and undermining jobs and investment in the creative sector."                , And SNP culture spokesman John Nicolson called the government's decision a "direct attack on an innovative broadcaster which produces independent, high-quality journalism".                                                                                                                                                            , What did Putin do before he came to power?                                                                                                                                                                                                                                                                                              , Life in the world's oldest town...                                                                                                                                                                                                                                                                                                      , Searching for Vladislav Surkov, key architect of the 'post truth' world                                                                                                                                                                                                                                                                 , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-04-05 04:30:00 </td>
   <td style="text-align:left;"> Brazilian Equities End Slightly Lower </td>
   <td style="text-align:left;"> The main Sao Paulo Index, Ibovespa, was down 0.2% to close at 121,286 on Monday, led by banks, retailers and giant Petrobras after the Brazilian government has lost its preferred candidates for both CEO and chairman of the board of the oil company. The government will now need to scramble to find suitable replacements for the two top spots at Petrobras just days before its April 13 annual shareholders' meeting. Meanwhile, the central bank’s so-called Focus survey, usually published every Monday, was not disclosed today by the bank due to disruptions caused by an indefinite workers' strike. At the same time, the prospect of further sanctions being imposed on Russia over its actions against Ukraine weighed on market sentiment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-05 04:22:56 </td>
   <td style="text-align:left;"> Wall Street Closes Higher on Tech Boost </td>
   <td style="text-align:left;"> The Dow finished Monday session 0.3% higher, while the S&amp;P 500 was up 0.8% and Nasdaq rose 1.9% as a surge in technology shares offset worries about new sanctions against Russia. Twitter gained as much as 27% after Elon Musk took a 9.2% stake in the company, while other mega-cap names such as Tesla, Meta, Amazon, Apple, and Microsoft rose more than 2%. Also, US-listed Chinese firms jumped after China’s securities watchdog proposed revising confidentiality rules involving offshore listings, clearing a legal hurdle to Sino-US cooperation on audit oversight. Still, sentiment remained clouded by the Russia-Ukraine war, with investors worried about new sanctions against Russia following mounting evidence of war crimes committed by its forces on the outskirts of Kyiv. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/carnival-corp-stock-gains-nearly/story.aspx?guid={2F5F949E-707D-4847-8F90-133FC5BCE85E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-05 04:19:38 </td>
   <td style="text-align:left;"> Carnival Corp. stock gains nearly 3% after cruise operator has busiest booking week ever - MarketWatch </td>
   <td style="text-align:left;"> Shares of Carnival Corp. 
        CCL,
        -1.55%
       rose nearly 3% in the extended session Monday after the cruise operator said that the week of March 28 was its busiest booking seven-day period ever. The week showed a "double-digit" increase from the previous record 7-day booking total, the company said, without further details. Twenty-two out of Carnival's 23 ships are back in year-around guest operations, Carnival said. Its final ship will return to service on May 2, and the company will have its newest ship in November and another new ship expected for 2023, it said. "By year-end 2022, Carnival will have more capacity sailing (as measured by ALBDs -- available lower berth days) than it was sailing in 2019," it said. Carnival stock ended the regular trading day down 1.6%.                                                                                                                                                                                                                                                             , The official list of symptoms of COVID-19 has been expanded in the UK, where cases are currently running at the highest level since the start of the pandemic. The National Health Service added nine new symptoms to the list of just three, including sore throat, fatigue and headache,as the Guardian reported. About1 in 13 people in the UK, or 4.9 million people, were estimated to have COVID in the week through March 26, up from 4.3 million the previous week. 
The U.S. is averaging 27,088 cases a day, according to a New York Times tracker, down 9% from two weeks ago. But cases are rising in states in the Northeast and South as the BA.2 omicron subvariant is spreading fast. The country is averaging 16,122 hospitalizations a day, down 27% from two weeks ago. The daily death toll has fallen below 700 to 649. 
 On a global basis, total cases rose above 491.4 million and total deaths are above 6.15 million, according to data aggregated by Johns Hopkins University, with the U.S. still leading the way with 80.1 million cases and 982,565 deaths., Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-04-05 04:04:00 </td>
   <td style="text-align:left;"> Canada Stocks End Near Record High </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, closed 0.6% up at 22,086 on Monday, just shy of its all-time high of 22,087 hit on March 29th, driven by gains in technology, energy and healthcare shares. Financials and industrials also advanced. Meanwhile, market sentiment was moderated by concerns about escalating tensions in Ukraine and the threat of fresh sanctions against Russia following mounting evidence of war crimes. Locally, the Bank of Canada's latest business survey showed a record number of Canadian businesses are facing capacity pressures amid intense labor shortages and ongoing supply chain difficulties, with many expecting significant wage and input price growth. A separate survey of consumer expectations found indicated short-term inflation expectations reached a record high, with consumers also anticipating inflation above target for the next two years, before easing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-announce-more-russia-sanctions/story.aspx?guid={D7503EBA-ADEA-4139-836C-37A79BA6FB38}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-05 03:30:54 </td>
   <td style="text-align:left;"> U.S. to announce more Russia sanctions this week, says Biden aide - MarketWatch </td>
   <td style="text-align:left;"> The U.S. will announce more sanctions against Russia "this week" over its invasion of Ukraine, President Joe Biden's National Security Adviser Jake Sullivan said Monday. Biden on Monday also called for a war crimes trial for Russian President Vladimir Putin, calling him "brutal" after reports of civilian massacres in Bucha, Ukraine. Briefing reporters at the White House, Sullivan said the next phase of the Russia-Ukraine conflict "may very well be protracted," and measured in months or longer.  , Orders for manufactured goods fell 0.5% in February, the Commerce Department said Monday.                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60990119?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-05 03:27:53 </td>
   <td style="text-align:left;"> Easter flight cancellations to continue for days </td>
   <td style="text-align:left;"> Airline EasyJet is expected to cancel more flights in the coming days due to high levels of staff absence.                                                                                                                                                                                              , Around 60 flights to and from the UK are likely to be grounded on Tuesday following 62 cancellations on Monday.                                                                                                                                                                                         , British Airways also cancelled 62 flights on Monday as travellers faced frustration on journeys ahead of Easter, the first holiday since the end of coronavirus travel restrictions.                                                                                                                    , EasyJet said staff absences were double their normal levels due to Covid.                                                                                                                                                                                                                               , It said it had decided to cancel more flights in advance "in order to give customers notice".                                                                                                                                                                                                           , "We are contacting customers directly and providing them with their options," it said.                                                                                                                                                                                                                  , "We expect to make similar levels of pre-emptive cancellations over the coming days, due to the ongoing high level of sickness."                                                                                                                                                                        , Covid-related absences are compounding staff shortages at airports and airlines. The industry is struggling to recruit staff quickly enough to meet resurgent passenger demand, after thousands of jobs were lost and many workers left the industry during the pandemic.                               , It's led to long delays at security and check-in at some airports, with travellers at Birmingham Airport complaining of "chaos" on Monday.                                                                                                                                                              , In Manchester passengers said they were trying to swap flights to avoid the ongoing disruption and queues.                                                                                                                                                                                              , Lesley Offley was due to fly to Austria with her family to celebrate her husband's 60th birthday on Tuesday.                                                                                                                                                                                            , But the 62-year-old from Surrey was told on Monday morning their Gatwick flight had been cancelled.                                                                                                                                                                                                     , "We've spent all morning unravelling all our travel plans for my husband's 60th birthday - first time we've attempted to travel since 2019 - and [I'm] completely fed up," she told the BBC.                                                                                                            , "It's been phone calls and emails all day, accommodation is lot more money so we've lost out there and we're still trying sort out the travel insurance.                                                                                                                                                , "We've re-booked for next week but I don't feel confident at all."                                                                                                                                                                                                                                      , On top of this, Ms Offley said they have been refused a refund on their parking booking because they cancelled less than 24 hours before they were due to park.                                                                                                                                         , John Strickland, director of transport consultancy JLS Consulting, said the situation for airlines was going to be "very difficult" over the next couple of months.                                                                                                                                     , "I think certainly the next month or two are going to be very difficult," he told the BBC's Wake Up To Money.                                                                                                                                                                                           , "We know that Manchester has said that passengers should expect queues for one to two hours for the next several weeks while they undertake additional training."                                                                                                                                       , According to the data firm Cirium, a total of 1,143 flights were cancelled to and from the UK in the week up to 3 April, with 382 of them grounded over the weekend.                                                                                                                                    , Cirium said British Airways cancelled 662 flights to and from the UK last week, while EasyJet cancelled 357.                                                                                                                                                                                            , British Airways took the decision two weeks ago to remove some flights, mostly short-haul routes, from its schedules until May.                                                                                                                                                                         , Aside from flight disruption, travellers hoping for an Easter getaway have also been affected by delays to the Eurotunnel and to ferry services.                                                                                                                                                        , Passengers who receive little or no notice about their cancelled flight, and ultimately arrive much later at their destination, may be entitled to extra compensation payments.                                                                                                                         , With many of the flights cancelled fewer than seven days before the scheduled departure, airlines are obliged to inform those affected of their rights - which can include putting them on a flight with a different carrier or getting a full refund.                                                  , Rory Boland of consumer group Which? said passengers affected on Monday may be entitled to at least £220 compensation to cover out of pocket costs, depending on the circumstances, and airlines should provide refreshments and accommodation as required while their customers await their new flight., Full details of the Civil Aviation Authority rules are here. A guide from Which? is here.                                                                                                                                                                                                               , What did Putin do before he came to power?                                                                                                                                                                                                                                                              , Life in the world's oldest town...                                                                                                                                                                                                                                                                      , Searching for Vladislav Surkov, key architect of the 'post truth' world                                                                                                                                                                                                                                 , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/04/climate-change-could-cost-us-2-trillion-each-year-by-2100-omb.html </td>
   <td style="text-align:left;"> 2022-04-05 02:50:04 </td>
   <td style="text-align:left;"> Climate change could cost U.S. $2 trillion each year by the end of the century, White House says </td>
   <td style="text-align:left;"> , Floods, drought, wildfires and hurricanes made worse by climate change could cost the U.S. federal budget about $2 trillion each year — a 7.1% loss in annual revenue — by the end of the century, the White House said in an assessment on Monday.                                                                                                                                                                                                                           , The analysis by the Office of Management and Budget, which administers the federal budget, also warned the U.S. government could spend an additional $25 billion to $128 billion each year in areas such as coastal disaster relief, flood insurance, crop insurance, health-care insurance, wildland fire suppression and flooding at federal facilities.                                                                                                                    , "The fiscal risk of climate change is immense," Candace Vahlsing, the OMB's associate director for climate, and Danny Yagan, its chief economist, wrote in a blog published on Monday.                                                                                                                                                                                                                                                                                        , "Climate change threatens communities and sectors across the country, including through floods, drought, extreme heat, wildfires, and hurricanes that affect the U.S. economy and the lives of everyday Americans," they wrote. "Future damages could dwarf current damages if greenhouse gas emissions continue unabated."                                                                                                                                                   , The news comes the same day as the United Nations' climate science panel's highly anticipated report, which warned that slashing global warming to 1.5 degrees Celsius above preindustrial levels will require greenhouse gas emissions to peak before 2025.                                                                                                                                                                                                                  , Read more about how businesses and consumers are fighting and adapting to climate change:                                                                                                                                                                                                                                                                                                                                                                                     , Empty canals, dead cotton fields: Arizona farmers are getting slammed by water cuts in the West                                                                                                                                                                                                                                                                                                                                                                               , ‘It’s now or never’: World’s top climate scientists issue ultimatum on critical temperature limit                                                                                                                                                                                                                                                                                                                                                                             , Map of nuclear power in the US: See where reactors are located                                                                                                                                                                                                                                                                                                                                                                                                                , This daughter and father founded a company to bury nuclear waste by drilling deep boreholes                                                                                                                                                                                                                                                                                                                                                                                   , The world has already warmed about 1.1 degrees Celsius above preindustrial levels and is on track to experience global temperature rise of 2.4 degrees Celsius by 2100.                                                                                                                                                                                                                                                                                                       , The OMB's analysis warned that intensifying wildfires could increase federal fire suppression costs by between $1.55 billion and $9.60 billion each year, representing an increase between 78% and 480% by the end of the century. Meanwhile, more frequent hurricanes could drive up annual spending on coastal-disaster response to between $22 billion and $94 billion by 2100.                                                                                            , Additionally, 12,000 federal buildings across the country could be flooded by 10 feet due to rising sea levels, with total replacement costs of more than $43.7 billion, the analysis said. That scenario would be on the high side, though. A 2021 report from the U.S. National Oceanic and Atmospheric Administration predicted a range of sea level rise in the U.S. between 0.6 meters (nearly two feet) and 2.2 meters (just over seven feet) by the end of the century., President Joe Biden last week released his 2023 budget proposal, which called for nearly $45 billion in new funding for climate change, clean energy and environmental justice programs. The budget, which includes an increase of nearly 60% in climate funding over the 2021 fiscal year, comes as Biden's core legislation to address climate change is stalled in Congress.                                                                                               , The climate portion of the $1.75 trillion House-passed bill, called the Build Back Better Act, would be the largest-ever federal clean energy investment and could help the U.S. get about halfway to the president's pledge to curb emissions in half by 2030, according to the nonpartisan analysis firm Rhodium Group.                                                                                                                                                     , Earlier this year, Biden said he would likely need break up the plan, but maintained that he believes Congress would still pass parts of it, including $555 billion in climate spending.                                                                                                                                                                                                                                                                                      , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/senate-republicans-unveil-bill-small-businesses-retail-investors </td>
   <td style="text-align:left;"> 2022-04-05 02:46:41 </td>
   <td style="text-align:left;"> Senate Republicans unveil bill to help small businesses, retail investors </td>
   <td style="text-align:left;"> Financial Services Committee member Rep. Warren Davidson, R-Ohio, discusses the economic impact of sanctions against Russia and the GOP's proposal to ramp up domestic energy production.                                                                                                                                                     , A group of Senate Republicans on Monday introduced a proposal to spur new business formations by encouraging companies to become publicly traded, tailoring regulations for small businesses and enhancing protection for retail investors.                                                                                                   , The bill – known as the JOBS Act 4.0 – represents the collective efforts of Senate Republicans to introduce 24 standalone bills that, among other things, could make it easier for small businesses to access capital and roll back certain regulations put into place in the wake of the 2008 financial crisis.                              , THESE STATES ROLLED BACK THEIR GASOLINE TAXES. OTHERS COULD FOLLOW                                                                                                                                                                                                                                                                            , It is intended to build on the bipartisan JOBS Act of 2012, which was signed into law by President Barack Obama 10 years ago this week.                                                                                                                                                                                                       , Sen. Pat Toomey questions Treasury Secretary Steven Mnuchin during a congressional hearing on Capitol Hill on Dec. 10, 2020. (Sarah Silbiger/The Washington Post via AP, Pool / AP Newsroom)                                                                                                                                                  , "The JOBS Act helped to revitalize interest in the public markets and spur economic growth, but it is clear significant work remains to be done to give retail investors access to higher returns and ensure American markets remain the deepest and most liquid in the world," Sen. Pat Toomey, R-Pa., said in a statement.                  , The new plan includes eight initiatives that are designed to encourage young firms to trade on public markets, where investors have the chance to earn the highest returns. It also contains provisions that Republicans say will reduce costs associated with seeking capital by "appropriately tailoring regulations for small businesses." , "Our work today seeks to accelerate economic growth and spur new business creation," said Sen. Kevin Cramer, R-N.D. "These bills create more access to capital for businesses on Main Street and in rural communities while repealing burdensome requirements inhibiting growth and innovation."                                              , COVID-19 insurance policies are increasingly joining passports and sunscreen as vacation staples, creating opportunities for insurers as more countries require mandatory coverage in case visitors fall ill from the coronavirus. (AP Photo/Mark Lennihan / AP Newsroom)                                                                     , The bill also attempts to enhance retail investor access to opportunities by preventing them from being excluded in certain situations. There are provisions in the bill that would boost investor protection and privacy and that would update outdated statutory and regulatory provisions.                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                   , The proposal has the support of several business groups, including the Small Business and Entrepreneurship Council and Americans for Prosperity, according to a release from the Republican lawmakers.                                                                                                                                        , Some ideas have already received bipartisan support, which they would require in order to become law as Democrats control both chambers of Congress and the White House. It is unclear if the bills could receive 60 votes in order to overcome a potential Democratic filibuster in the Senate.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/04/europe/russia-military-culture-brutality-intl/index.html </td>
   <td style="text-align:left;"> 2022-04-05 02:40:17 </td>
   <td style="text-align:left;"> In Russia's military, a culture of brutality runs deep - CNN </td>
   <td style="text-align:left;"> Lviv, Ukraine (CNN)The grotesque pictures emerging from the Kyiv suburb of Bucha are some of the strongest evidence yet of apparent war crimes by Russian forces in Ukraine: Dead civilians on the street, some with hands bound and shot execution-style, others apparently mowed down at random.                                                                                                                                                                                                                                 , For anyone who has followed Russian President Vladimir Putin's way of war, it's a depressingly familiar pattern. Russia's military has a culture of brutality and scorn for the laws of armed conflict that has been extensively documented in the past.                                                                                                                                                                                                                                                                           , "The history of Russia's military interventions -- be it in Ukraine or Syria, or its military campaign at home in Chechnya -- is tainted with blatant disregard for international humanitarian law," said Agnès Callamard, Amnesty International's Secretary General.                                                                                                                                                                                                                                                              , "The Russian military repeatedly flouted the laws of war by failing to protect civilians and even attacking them directly. Russian forces have launched indiscriminate attacks, used banned weapons and sometimes apparently deliberately targeted civilians and civilian objects -- a war crime."                                                                                                                                                                                                                                 , That statement, made less than a month before Russia's invasion of Ukraine, has proven sadly prophetic. In the opening weeks of the war, the international community reacted with horror as Ukrainian cities came under relentless Russian bombardment. Protected civilian infrastructure was hit, much as Russian aircraft once targeted Syrian schools and hospitals.                                                                                                                                                            , But the scenes unfolding in places like Bucha suggest an intimate kind of violence, something reminiscent of Russia's war in Chechnya.                                                                                                                                                                                                                                                                                                                                                                                             , During the second Chechen war -- which coincided with Putin's rise to power -- allegations also surfaced of widespread human-rights abuse by Russian troops. In 2000, to cite just one well-known incident, investigators with Human Rights Watch documented the summary execution of at least 60 civilians in two suburbs of Grozny, the capital of Chechnya.                                                                                                                                                                     , Locals unearthed mass graves in Chechnya; international officials made fact-finding trips to the region and made concerned statements about the reports of abuse and extrajudicial killings. Those statements did not stop Russia's military from grinding ahead with its ruthless pacification campaign.                                                                                                                                                                                                                          , Similar evidence of summary executions abounds in towns such as Bucha. A CNN team visited the basement of one building and saw the bodies of five men before they were removed by a Ukrainian team. An adviser to the Ukrainian interior minister, Anton Gerashchenko, told CNN that the five men had been tortured and executed by Russian soldiers.                                                                                                                                                                              , CNN cannot independently verify Gerashchenko's claims. But equally troubling is the alleged treatment of Ukrainian prisoners of war by Russian forces. The Ukrainian parliament's human rights ombudsman, Liudmyla Denisova, said Monday that Russia's treatment of prisoners of war violates the Geneva Conventions,  laying out a theoretical case for potential war crimes prosecutions.                                                                                                                                        , In a Facebook post on Monday, Denisova said that released Ukrainian soldiers have "told of the inhumane treatment of them by the Russian side: they were kept in a field, in a pit, in a garage. Periodically, one was taken out: beaten with rifle butts, shots fired next to their ear, intimidated."                                                                                                                                                                                                                            , CNN cannot independently verify Denisova's claims.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Igor Zhdanov, a correspondent for the Russian state propaganda outlet RT, posted videos on March 22 depicting Ukrainian prisoners of war being processed for "filtration" -- Zhdanov's choice of word -- after they were captured. The videos show masked Russians searching their captives for tattoos or insignia, which would supposedly show affiliation with nationalists or "neo-Nazi" groups that the Russians have cast as their main enemy in Ukraine.                                                                    , Zhdanov said in his post that Ukrainian POWs were being treated humanely. But his choice of words was ominous. During the war in Chechnya, Russian forces notoriously used so-called "filtration camps" used to separate civilians from rebel fighters. Legendary Russian investigative reporter Anna Politkovskaya gathered testimony from Chechen civilians detained in filtration centers, where detainees said they were held in pits and subjected to electric shock, beatings and ruthless interrogation.                    , Russian forces have also targeted local Ukrainian mayors for detention -- and in at least one case, Ukrainian officials say, an extrajudicial killing.                                                                                                                                                                                                                                                                                                                                                                             , "At the moment, 11 local mayors from Kyiv, Kherson, Mykolaiv and Donetsk regions are in Russian captivity," Ukrainian Deputy Prime Minister Iryna Vereshchuk said in a message posted on social media Sunday.  She said the Ukrainian government learnt Saturday that Olga Sukhenko, the mayor of Motyzhyn, a village in the Kyiv region, was killed in the custody of Russian forces.                                                                                                                                             , Ivan Fedorov, the mayor of the southern city of Melitopol -- who was detained by Russian forces but subsequently freed as part of a prisoner exchange -- said Russian forces occupying his city were appropriating local businesses, saying that the "situation is difficult, because Russian soldiers have declared themselves as authorities but of course, they don't care about people and their problems, they only care about taking the money from the businessmen, [and seizing] their businesses."                        , Long before the invasion of Ukraine, the Russian military had a reputation for a culture of cruelty. Russia has a hybrid manpower system of contract soldiers and conscripts. Although the Russian government claims to have made strides in professionalizing its forces, the country's military still has a brutal hazing system known as dedovshchina, a notorious tradition that encourages senior conscripts to beat, brutalize or even rape younger conscripts.                                                              , Putin recently announced a decree on spring conscription, fixing a target for 134,500 individuals to be called up into the Russian armed forces. The Russian President originally claimed that Russian conscripts would not take part in what Russia has euphemistically dubbed the "special military operation" in Ukraine. But the Russian Ministry of Defense subsequently acknowledged that draftees were fighting in Ukraine, and Ukrainian forces claim to have taken a considerable number of Russian conscripts prisoner.  , Ukrainian investigators are already launching criminal probes of alleged crimes by Russian forces as more areas are freed from Russian control -- particularly around Kyiv and the northern city of Chernihiv.                                                                                                                                                                                                                                                                                                                     , It will be days, or perhaps weeks, before we get a fuller picture of what happened in Bucha. But if the past is any guide, there is little hope that Russian perpetrators would be brought to justice.                                                                                                                                                                                                                                                                                                                             , CNN's Alex Hardie contributed to this report. CNN's Vasco Cotovio contributed reporting from Bucha, Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-futures-settle-higher-us/story.aspx?guid={A1A60C15-BE21-460C-990E-A61B28760584}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-05 02:35:54 </td>
   <td style="text-align:left;"> Oil futures settle higher, with U.S. prices back above the $100 mark - MarketWatch </td>
   <td style="text-align:left;"> Oil futures settled higher on Monday after posting their biggest weekly loss in about two years late last week, after the U.S. and International Energy Agency announced plans to release oil from emergency reserves. Oil prices have rebounded after last week's big declines, with U.S. prices recovering back above $100 a barrel, "in the wake of renewed calls for further sanctions against Russian oil and gas imports," said Michael Hewson, chief market analyst at CMC Markets UK. "This appears to be outweighing concerns over Chinese demand after the whole of Shanghai, a city of 25 [million] people, was put into a COVID lockdown." West Texas Intermediate crude for May delivery 
        CLK22,
        +1.65%
       rose $4.01, or 4%, to settle at $103.28 a barrel on the New York Mercantile Exchange. Prices on Friday settled below the $100, at the lowest finish since March 16., Shares of Twitter Inc. rocketed to their biggest single-day gain ever Monday, after it was disclosed that the "Technoking" of Tesla Inc., Elon Musk, had acquired a large stake in the social-media company.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/buttigieg-latest-biden-official-to-push-green-transition-as-gas-prices-soar </td>
   <td style="text-align:left;"> 2022-04-05 02:19:51 </td>
   <td style="text-align:left;"> Buttigieg latest Biden official to push green transition as gas prices soar </td>
   <td style="text-align:left;"> Piedmont Lithium president and CEO Keith Phillips anticipates future EV growth amid supply setbacks.                                                                                                                                                                           , Transportation Secretary Pete Buttigieg is the latest Biden administration official to push for a green energy transition as gas prices across America soar.                                                                                                                   , Buttigieg turned heads on Friday when he continued to push for Americans to purchase a new, electric car as their wallets take a hit from skyrocketing gas prices.                                                                                                             , The Transportation secretary said American citizens will still continue to feel the pressure of high fuel prices until the U.S. becomes a clean energy independent nation.                                                                                                     , OIL PRICES SLIGHTLY DIP AFTER BIDEN ANNOUNCES LARGEST-EVER OIL RESERVE RELEASE                                                                                                                                                                                                 , Transportation Secretary Pete Buttigieg speaks at the U.N. climate summit, in Glasgow, Scotland, Nov. 10, 2021. (AP Photo/Alberto Pezzali, File / AP Newsroom)                                                                                                                 , "Even if all of the oil we use in the U.S.A. were made in the U.S.A., the price of it is still subject to powers and dynamics outside of the U.S.A.," Buttigieg said.                                                                                                          , "Which means that until we achieve a form of energy independence that is based on clean energy created here at home, American citizens will still be vulnerable to wild price hikes like we are seeing right now," he continued.                                               , Buttigieg had previously touted the administration’s push to create electric vehicle infrastructure while saying Americans who move to electric cars will see savings on gas.                                                                                                  , The administration from the top-down has been pushing for a nationwide green transportation transition, with President Biden himself suggesting Americans buy electric vehicles to save on gas costs.                                                                          , Energy Secretary Jennifer Granholm (AP Photo/J. Scott Applewhite, File)                                                                                                                                                                                                        , Energy Secretary Jennifer Granholm – who was invested in an electric vehicle battery company for months after taking her job until she sold the shares – also said in May of last year that high gas prices would not be "affecting" Americans if they drove "an electric car.", The push for a green transition comes amid skyrocketing gas prices and rising inflation, as well as warnings against transitioning too quickly to a clean energy economy.                                                                                                      , CLICK HERE TO GET THE FOX NEWS APP                                                                                                                                                                                                                                             , Researchers at Rice University in Houston, Texas, previously warned that transitioning too quickly "risks destabilizing a global energy-food-water-human well-being nexus that, sufficiently perturbed, would likely delay energy transition efforts for decades."             , Additionally, critics of the Biden administration’s push for Americans to buy electric vehicles have blasted the messaging as out of touch, as electric vehicles are expensive and could be hard to afford or even find for a large number of Americans. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/ford-first-quarter-sales-fall </td>
   <td style="text-align:left;"> 2022-04-05 01:53:57 </td>
   <td style="text-align:left;"> Ford first-quarter sales fall </td>
   <td style="text-align:left;"> Frances Newton Stacy and Gary Kaltbaum provide insight on auto companies ramping up the push for electric vehicles as gas prices soar.                                                                                                                                        , Ford Motor Company saw a double-digit drop in total vehicle sales in the first quarter of 2022 as the automaker continues to grapple with persistent semiconductor chip shortages.                                                                                            , Ford reported total sales were down 17.1% in the first three months of 2022 with 432,132 units sold. (MAL FAIRCLOUGH/AFP via Getty Images / Getty Images)                                                                                                                     , Ford reported total sales were down 17.1% in the first three months of the year with 432,132 units sold. The total March sales of 159,328 were down 25.6% on the month from the year before.                                                                                  , FORD ‘CONFIDENT’ CAR PRICES, CHIP SHORTAGE WILL EASE THIS YEAR                                                                                                                                                                                                                , However, orders for new vehicles keep pouring in, with Ford dealerships taking a record 88,000 retail orders in March, up from 66,000 during the same month in 2021.                                                                                                          , Ford reported total sales were down 17.1% in the first three months of 2022 with 432,132 units sold. (iStock / iStock)                                                                                                                                                        , "While the global semiconductor chip shortage continues to create challenges, we saw an improvement in March sales, as in-transit inventory improved 74% over February," said Andrew Frick, vice president of sales, distribution and trucks.                                 , FORD MUSTAND AND CHEVROLET CAMARO PRODUCTION SUSPENDED                                                                                                                                                                                                                        , "F-Series had a record 50,000 new retail orders in March, while a record 41% of our overall retail sales came from previously placed orders," Frick explained, adding, "Ford is ready to deliver and positioned well for spring sales growth."                                , Ford reported total sales were down 17.1% in the first three months of 2022 with 432,132 units sold. (AP Photo/David Zalubowski / AP Newsroom)                                                                                                                                , Ford isn't alone in reporting lower sales in the first quarter, as the industry continues to battle ongoing supply chain woes since the beginning of the coronavirus pandemic.                                                                                                , Toyota and General Motors also reported double-digit declines in sales of 15% and 20%, respectively, in Q1.                                                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                   , However, not all car companies saw sales slow. Electric vehicle giant Tesla reported delivering 310,000 units in the first quarter of the year, up 68% from a year ago despite what CEO Elon Musk called "an exceptionally difficult quarter due to supply chain disruptions." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-end-higher-recoup/story.aspx?guid={A024FDC6-160F-43DB-80CC-2C3FD4B043BD}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-05 01:36:32 </td>
   <td style="text-align:left;"> Gold futures end higher to recoup a portion of recent losses - MarketWatch </td>
   <td style="text-align:left;"> Gold futures ended higher on Monday to recoup a portion of the 1.6% loss they suffered last week. Prices for the precious metal got a boost from the "ongoing worries about problematic price inflation that will likely get worse before it gets better," said Jim Wyckoff, senior analyst at Kitco.com. June gold 
        GCM22,
        +0.02%
       rose $10.30, or 0.5%, to settle at $1,934 an ounce.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The official list of symptoms of COVID-19 has been expanded in the UK, where cases are currently running at the highest level since the start of the pandemic. The National Health Service added nine new symptoms to the list of just three, including sore throat, fatigue and headache,as the Guardian reported. About1 in 13 people in the UK, or 4.9 million people, were estimated to have COVID in the week through March 26, up from 4.3 million the previous week. 
The U.S. is averaging 27,088 cases a day, according to a New York Times tracker, down 9% from two weeks ago. But cases are rising in states in the Northeast and South as the BA.2 omicron subvariant is spreading fast. The country is averaging 16,122 hospitalizations a day, down 27% from two weeks ago. The daily death toll has fallen below 700 to 649. 
 On a global basis, total cases rose above 491.4 million and total deaths are above 6.15 million, according to data aggregated by Johns Hopkins University, with the U.S. still leading the way with 80.1 million cases and 982,565 deaths., Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/maines-legal-adult-use-cannabis/story.aspx?guid={6357D5AC-DFFC-47EC-9C1A-97AB8E730C36}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-05 01:35:48 </td>
   <td style="text-align:left;"> Maine's legal adult use cannabis generates $65 million of economic activity in first year: Study - MarketWatch </td>
   <td style="text-align:left;"> The adult use cannabis market in Maine generated about $65 million in economic activity and 900 jobs in its first year, according to a study made public on Monday by Colby College's Laboratory for Economic Studies. Retail sales totaled about $58.5 million between October of 2020 and September 2021 and generated about $8.8 million in sales and excise tax revenue. Sales grew about ten times during the period to $10 million in September, 2021, from $1 million in the first month. The AdvisorShares Pure US Cannabis ETF 
        MSOS,
        -1.24%
       is up 0.5% on Monday, but down 17.5% this year, compared to a year-to-date loss of 7.4% by the Nasdaq.                                                                                                                                                                                                                                                                                                                                                                                                     , The official list of symptoms of COVID-19 has been expanded in the UK, where cases are currently running at the highest level since the start of the pandemic. The National Health Service added nine new symptoms to the list of just three, including sore throat, fatigue and headache,as the Guardian reported. About1 in 13 people in the UK, or 4.9 million people, were estimated to have COVID in the week through March 26, up from 4.3 million the previous week. 
The U.S. is averaging 27,088 cases a day, according to a New York Times tracker, down 9% from two weeks ago. But cases are rising in states in the Northeast and South as the BA.2 omicron subvariant is spreading fast. The country is averaging 16,122 hospitalizations a day, down 27% from two weeks ago. The daily death toll has fallen below 700 to 649. 
 On a global basis, total cases rose above 491.4 million and total deaths are above 6.15 million, according to data aggregated by Johns Hopkins University, with the U.S. still leading the way with 80.1 million cases and 982,565 deaths.,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60983561?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-05 01:15:17 </td>
   <td style="text-align:left;"> Cryptocurrency: UK Treasury to regulate some stablecoins </td>
   <td style="text-align:left;"> This video can not be played                                                                                                                                                                                                                    , The Treasury has announced that it will regulate some cryptocurrencies as part of a wider plan to make the UK a hub for digital payment companies.                                                                                              , So-called "stablecoins" will become recognised forms of payment to give people confidence in using digital currencies, it said.                                                                                                                 , Stablecoins are designed to have a stable value linked to traditional currencies or assets like gold.                                                                                                                                           , They are considered less volatile than cryptocurrencies such as Bitcoin.                                                                                                                                                                        , The Treasury also said it planned to consult on regulating a much wider range of digital currencies later this year, without saying which they might be.                                                                                        , Chancellor Rishi Sunak said: "We want to see the [cryptocurrency] businesses of tomorrow - and the jobs they create - here in the UK, and by regulating effectively we can give them the confidence they need to think and invest long-term."   , The Treasury has not yet confirmed which stablecoins will be regulated; well-known ones include Tether and Binance USD.                                                                                                                         , Stablecoins are currently used in the United States to facilitate trading, lending or borrowing of other digital assets.                                                                                                                        , However, they are not without controversy. Tether, a Hong Kong based company, has faced questions over its business practices and was fined $41m in 2021 by the US Commodities Futures Trading Commission for allegedly misstating its reserves., The UK's Treasury said regulating stablecoins would ensure they could be used "safely" by the public.                                                                                                                                           , Cryptocurrencies are virtual or digital currencies that can be traded or used to buy goods and services, although not many shops accept them yet and some countries have banned them altogether.                                                , They are exchanged via "peer-to-peer" transactions, meaning there are no banks or other third parties involved.                                                                                                                                 , Wild fluctuation in the value of some digital currencies has led regulators to warn they pose risks. However, they are increasingly going mainstream, with major financial companies now investing in them.                                     , Meanwhile, Tesla founder Elon Musk, the richest person in the world, has voiced his support for virtual currencies and said Bitcoin is a "good thing".                                                                                          , Separately, the Treasury said it will ask The Royal Mint to create a Non-Fungible Token (NFT) this summer.                                                                                                                                      , NFTs are assets in the digital world that can be bought and sold, but which have no tangible form of their own.                                                                                                                                 , The digital tokens, which emerged in 2014, can be thought of as certificates of ownership for virtual or physical assets. NFTs have a unique digital signature which means they cannot be copied or replicated.                                 , UK Financial Services Minister John Glen said the UK saw "enormous potential in crypto" and had a "detailed plan [for] harnessing the potential of blockchain and supporting the development of a world-best crypto ecosystem".                 , "What does the future of crypto here in the UK look like? No-one knows for sure," he said in a speech.                                                                                                                                          , "But we think that by making this country a hospitable place for crypto we can attract investment [and] generate swathes of new jobs."                                                                                                          , Regulators are racing to draw up rules to manage cryptocurrencies amid concern that their growing popularity could threaten established financial systems.                                                                                      , In December, the Bank of England's deputy governor said that while only about 0.1% of UK wealth was currently held as digital assets, that proportion was growing quickly.                                                                      , Sir Jon Cunliffe told the BBC that if the value of cryptocurrencies fell sharply, it could have a knock-on effect.                                                                                                                              , Meanwhile, the US is moving to craft regulations amid rising concern that the cryptocurrency industry is a haven for criminals.                                                                                                                 , The process of generating digital coins via banks of powerful computers, called mining, is also highly energy intensive. Recent research suggests Bitcoin now generates carbon emissions comparable to the country of Greece.                   , Mr Glen admitted there were concerns about the environmental impact and said the government "will be looking closely at energy usage associated with certain crypto-technologies".                                                              , What did Putin do before he came to power?                                                                                                                                                                                                      , Life in the world's oldest town...                                                                                                                                                                                                              , Searching for Vladislav Surkov, key architect of the 'post truth' world                                                                                                                                                                         , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/04/04/russia-troops-leave-ukraine-airport-strategy-focus-donbas-eaton-ip-sot-vpx.cnn </td>
   <td style="text-align:left;"> 2022-04-05 01:08:26 </td>
   <td style="text-align:left;"> Video: Satellite images indicate shift in Putin's strategy, retired Maj. Gen. Paul Eaton says  - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/business-leaders/elon-musk-tweet-twitter-purchase-shareholder </td>
   <td style="text-align:left;"> 2022-04-05 01:08:00 </td>
   <td style="text-align:left;"> Elon Musk tweets first words since becoming Twitter's largest shareholder </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines for April 4.                                                                                                                                                                                                                                                                       , Elon Musk tweeted his first words since news broke on Monday that he purchased a 9.2% stake in the social media company.                                                                                                                                                                                                          , STOCK FUTURES CAUTIOUS, OIL, GOLD LOWER, MEXICO SUSPENDS GAS SUBSIDY AS AMERICANS LOOK FOR DEALS                                                                                                                                                                                                                                  , "Oh hi lol," Musk, now Twitter’s largest shareholder, said in a tweet.                                                                                                                                                                                                                                                            , The Tesla CEO owns 73,486,938 shares of Twitter, according to the Securities and Exchange Commission, valued at $2.89 billion based on Friday's closing price.                                                                                                                                                                    , ELON MUSK PURCHASES STAKE IN TWITTER AFTER SLAMMING ITS APPROACH TO 'FREE SPEECH'                                                                                                                                                                                                                                                 , Musk’s purchase, which caused shares to spike by 25% in premarket trade, comes shortly after he criticized the social media platform for not upholding free speech.                                                                                                                                                               , Musk posted a Twitter poll in March questioning whether the platform allows users to speak freely.                                                                                                                                                                                                                                , INVESTMENT EXPERT ON ELON MUSK'S TWITTER STAKE: 'THIS IS SUCH A BALLER MOVE'                                                                                                                                                                                                                                                      , "Free speech is essential to a functioning democracy. Do you believe Twitter rigorously adheres to this principle?" he wrote.                                                                                                                                                                                                     , More than 70% of respondents said Twitter lacked a commitment to free speech, leading Musk to ask his more than 80 million followers, "What should be done?"                                                                                                                                                                      , He also said in another tweet last month that he is giving "serious thought" to creating a new social media platform.                                                                                                                                                                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                       , Twitter has come under fire in recent years for repeatedly censoring conservative viewpoints. The company locked the conservative satire site The Babylon Bee out of its Twitter account in March for jokingly awarding Biden administration official Dr. Rachel Levine a "Man of the Year" award. Levine is a transgender woman. , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                           , Twitter also blocked the sharing of links to a New York Post article revealing the contents of a laptop belonging to Hunter Biden. While critics derided the story as Russian disinformation at the time, both the New York Times and Washington Post have since acknowledged that the story was accurate.                        , FOX Business' Anders Hagstrom contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-04-05 00:49:00 </td>
   <td style="text-align:left;"> South African Stocks End Marginally Lower </td>
   <td style="text-align:left;"> The JSE FTSE All Share index closed marginally lower at 75,835 on Monday, as gains in commodity-linked stocks and tech companies were offset by losses in shares of banks and Mondi. At the same time, investors continued watching developments regarding the war in Ukraine, where hopes last week of a ceasefire have dissipated, while talks of more sanctions by the West nations on Russia over its invasion of Ukraine weighed. Meanwhile, the World Bank, which is hopeful about its new relationship with South Africa, said it would work with Eskom and Transnet to support projects that can improve South Africa’s investment potential. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-04-05 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Extend Gains </td>
   <td style="text-align:left;"> The CAC 40 ended 0.7% higher at 6,731 on Monday, extending gains for a second straight session, driven by shares of Valeo, Faurecia and Thales. On the opposite side, Axa, Societe Generale and Vinci were the biggest losers. Geopolitical tensions remained in the spotlight, with the EU discussing a new round of sanctions on Russia in response to multiple reports that Russian troops executed unarmed civilians in Ukrainian towns. Domestically, Emmanuel Macron is widely expected to win a second five-year term in France’s presidential election, whose first round will be held next Sunday, but far-right Marine Le Pen has surged over the past couple of weeks, aided by her patient focus on cost-of-living issues. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/04/stocks-making-the-biggest-moves-midday-twitter-starbucks-tesla-and-more.html </td>
   <td style="text-align:left;"> 2022-04-05 00:37:56 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Twitter, Starbucks, Tesla and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Twitter — The social media company soared 27.1% after a filing revealed that Elon Musk has taken a 9.2% passive stake in the firm worth about $2.9 billion. The purchase came weeks after the Tesla CEO polled his 80-plus million Twitter followers about whether the platform adheres to free speech principles. Musk also recently hinted at starting his own site. The move is sparking speculation among analysts that Musk could take a more active ownership in Twitter or even consider a takeover down the road., Tesla — Shares added 5.6% after Tesla reported first-quarter electric vehicle deliveries. The more than 310,000 vehicle deliveries marked a quarterly record, but slightly missed consensus Wall Street estimates. Most analysts attributed the miss to Covid shutdowns in Shanghai, where Tesla has a major factory.                                                                                                                                                                                                    , Starbucks — The coffee chain fell 3.7% following the suspension of its share repurchase program. The decision comes as Howard Schultz returns to the helm as CEO of the company and amid a greater union push from the firm's baristas.                                                                                                                                                                                                                                                                                  , JD.com, Netease, Alibaba, Tencent Music – U.S.-listed shares of Chinese companies rallied after China proposed revising confidentiality rules regarding audit oversight. The move could prevent those companies from being delisted in the U.S. JD.com jumped 7.1%, Netease rose 2.4%, Alibaba gained 6.6% and Tencent Music added 10.7%.                                                                                                                                                                                , Hertz — Shares of the rental car company surged 10.7% after Hertz announced a partnership with electric vehicle company Polestar. As part of the deal, Hertz will purchase up to 65,000 electric vehicles over the next five years, according to a news release.                                                                                                                                                                                                                                                         , Logitech — The stock rose 7% after Goldman Sachs upgraded the company to a "buy" from "neutral" and said it could see big gains from growing trends toward gaming and videoconferencing.                                                                                                                                                                                                                                                                                                                                 , Quest Diagnostics – Shares slipped 1.3% after Citi downgraded the diagnostic information services company to neutral from buy, due to uncertainty around its post-pandemic model. Citi cited Quest's margin outlook this and next year as well as heightened labor pressures and volume declines.                                                                                                                                                                                                                        , Baxter — Shares fell 4% after Goldman Sachs downgraded the stock to a sell rating from neutral. The firm said the call is due to Baxter's "over-indexing to headwind variables and numbers being at risk."                                                                                                                                                                                                                                                                                                               , Ollie's Bargain Outlet Holdings — The retail stock jumped 15.7% after Wells Fargo upgraded Ollie's to overweight from equal weight. Wells Fargo said that the stock could prove to be a "coiled spring" after the company has worked through its pandemic-era disruptions.                                                                                                                                                                                                                                               , — CNBC's Yun Li, Samantha Subin, Sarah Min, Jesse Pound and Tanaya Macheel contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-05 00:26:00 </td>
   <td style="text-align:left;"> Wall Street Rises on Tech Boost </td>
   <td style="text-align:left;"> The Dow pared early losses and crossed into positive territory in midday trading on Monday, while the S&amp;P 500 and Nasdaq outperformed as a surge in technology shares offset worries about more sanctions against Russia over its invasion of Ukraine. Twitter skyrocketed over 27% after Elon Musk took a 9.2% stake in the company, while other mega-cap names such as Tesla, Meta, Amazon, Apple, and Microsoft rose more than 1%. Also, US-listed Chinese firms jumped after China’s securities watchdog proposed revising confidentiality rules involving offshore listings, clearing a legal hurdle to Sino-US cooperation on audit oversight. Still, sentiment remained clouded by the Russia-Ukraine war, with investors worried about new sanctions against Russia following mounting evidence of war crimes committed by its forces on the outskirts of Kyiv. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/stock-market </td>
   <td style="text-align:left;"> 2022-04-05 00:20:00 </td>
   <td style="text-align:left;"> Russian Stocks Extend Rally </td>
   <td style="text-align:left;"> The MOEX Russia Index closed 1% higher at 2,787 on Monday, gaining for the fourth consecutive session, as investors evaluated talks of further Western sanctions against Moscow amid reports of war crimes in Ukraine. French President Emmanuel Macron said that a new round of sanctions targeting Russia was needed and that there were clear indications that Russian forces were responsible for the killings of civilians in the Ukrainian town of Bucha, while the German Defense Minister said the European Union must discuss banning the import of Russian gas. Banks led the gains in Moscow, as VTB shares jumped 9.5% and Sberbank followed to close 5.7% higher. The metallurgical sector also booked gains, led by  a 10.9% jump for Petropavlosk. Gazprom ended 0.2% higher, on par with the energy sector amid reports that the German government is in talks with private buyers for Gazprom’s assets in the country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/retail/new-balance-amplifying-long-standing-commitment-to-us-manufacturing </td>
   <td style="text-align:left;"> 2022-04-05 00:16:45 </td>
   <td style="text-align:left;"> New Balance amplifying 'long-standing commitment’ to US manufacturing </td>
   <td style="text-align:left;"> New Balance Athletics CEO Joe Preston discusses the impact of the 'supply chain crisis' and inflation on his company.                                                                                                                                    , Joe Preston, president &amp; CEO of New Balance Athletics, noted on Monday that his company has had a "long-standing commitment to domestic manufacturing" instead of relying on Asian countries, including Vietnam and China, like some of his competitors. , "We’ve been making product in the U.S. for years and we are the only athletic manufacturer that produces here in the states," Preston told "Varney &amp; Co." on Monday.                                                                                     , He noted that the company has five factories in the U.S., including two in Massachusetts and three in Maine.                                                                                                                                             , "One we just opened up last week. It’s a new facility," he continued, noting that the move led to the creation of 90 new jobs.                                                                                                                           , CALIFORNIA TRUCKING INDUSTRY LEADER WARNS WORKER SHORTAGE, SHIP BACKLOGS CREATING ‘PERFECT STORM’                                                                                                                                                        , "We’re going to bring that up to over 200 by the end of the year," he told host Stuart Varney.                                                                                                                                                           , The vast majority of shoes sold in the U.S. came from China before the onset of the coronavirus pandemic.                                                                                                                                                , Preston pointed out that with the current supply chain issues presented in the economy due to the pandemic inventory is "taking so much longer" to arrive to the United States, which is "obviously tying up cash."                                      , "So clearly I think other companies are seeing the need to onshore," he continued.                                                                                                                                                                       , Port of Los Angeles Executive Director Gene Seroka explains what should be expected and whether his port is already seeing the effects of the recent COVID-19 lockdowns in China. 
                                                                   , When asked if there are any signs that the supply chain "crisis" will ease in the near future, Preston responded by saying he doesn’t anticipate the situation will alleviate within the next six months.                                                , "Still today it is difficult to get containers," he told Varney. "It is difficult to get them into the ports."                                                                                                                                           , He pointed to the significant amount of ships that are waiting offshore and noted that once they get into the ports, getting the goods onto trucks is a challenge given the shortage of drivers in the U.S.                                              , The American Trucking Association has reported that there is a shortage of 80,000 truck drivers across the country.                                                                                                                                      , New Balance in Hong Kong. (Photo by Chukrut Budrul/SOPA Images/LightRocket via Getty Images / Getty Images)                                                                                                                                              , As it pertains to inflation, due to current macroeconomic factors, Preston noted that his company was forced to increase prices.                                                                                                                         , "We have selectively raised prices – we’ve had to," he told Varney, citing the higher cost of raw materials and the need to pay workers higher wages to attract and retain talent.                                                                       , He added that the current inflationary environment is "not hurting our demand."                                                                                                                                                                          , Joe Preston, president &amp; CEO of New Balance Athletics, notes his company has had a 'long-standing commitment to domestic manufacturing' instead of relying on Asian countries.                                                                           , "Last year we grew over 30%, it was up double digits over 2019," Preston said. "We’re a $4.4 billion company today and we’re seeing that momentum into 2022."                                                                                            , He added that his company could have "grown even more" had it not been for supply chain constraints.                                                                                                                                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                              , Inflation hit a fresh 40-year high in February with the consumer price index climbing 7.9% on an annual basis, according to data released last month by the Bureau of Labor Statistics. Month over month, inflation rose 0.8%.                           , Inflation data for March will be released next week. The February data, the latest data currently available, was taken before Russia's invasion of Ukraine, which pushed prices for some items higher.                                                   , CLICK HERE TO READ MORE ON FOX BUSINESS  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-04-05 00:05:00 </td>
   <td style="text-align:left;"> Ibex Ends Slightly Higher </td>
   <td style="text-align:left;"> The Ibex 35 reverted losses and managed to close 0.2% higher at 8,521 on Monday, extending gains for a second straight session, mainly boosted by shares of pharmaceuticals companies, namely Grifols, Rovi and PharmaMar. On the other hand, Mapfre, Endesa ,Red Eléctrica, Acerinox and ACS were the biggest laggards. Meanwhile, prospects of fresh sanctions against Russia amid reports of Russian atrocities on Ukraine, fuelled fears of further inflationary pressures, also weighing on global growth. Locally, Spanish Prime Minister Pedro Sanchez said that the government plans to invest €11 billion to develop microchips and semiconductors in an effort to repair its economy, which suffered more than most European peers from the pandemic and is under pressure again following Russia’s invasion of Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-04 23:56:00 </td>
   <td style="text-align:left;"> South Africa 10Y Bond Yield Remains Close to 1-Month Low </td>
   <td style="text-align:left;"> South Africa 10-Year Government Bond Yield was at 9.55%, close to its lowest in a month, after ratings agency Moody's revised South Africa's outlook to "stable" from "negative", saying the country's improved fiscal outlook would help the government stabilize its debt burden over the medium term. At the same time, downside economic risks due to the Ukraine conflict and the prospect of tougher sanctions against Russia boosted demand for safer debt instruments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-04-04 23:54:00 </td>
   <td style="text-align:left;"> European Shares Extend Gains </td>
   <td style="text-align:left;"> European equities rose for a second session on Monday, with the pan-European STOXX 600 and the DAX 30 adding 0.9% and 0.6%, respectively, driven by gains among technology and discretionary stocks. Still, sentiment remained clouded by the Russia-Ukraine war, with investors worried about new sanctions against Russia following mounting evidence of war crimes committed by its forces on the outskirts of Kyiv. Meanwhile, Germany’s February exports beat expectations, resulting in a higher-than-anticipated trade surplus of €11.5B. On the corporate front, German takeout company Delivery Hero jumped over 10% after launching a debt financing syndication equal to around $1.55 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-04-04 23:53:19 </td>
   <td style="text-align:left;"> Italian Stocks Close Muted </td>
   <td style="text-align:left;"> The FTSE MIB index reverted earlier losses to close marginally higher at 25,176 on Monday, carried by luxury goods and healthcare stocks while investors weighed on the possibility of further sanctions on Russia after footage of war crimes in Ukraine emerged over the weekend. The luxury goods sector in Milan tracked its counterparts in Europe and led the gains, driven by a 5% jump for Ferrari and 3.7% increase for Moncler. Also, higher demand for defense across Europe underpinned gains in the sector, as seen with a 2.7% increase for Leonardo shares. On the other hand, Telecom Italia closed 1.9% lower after the group signed a non-disclosure agreement with Italy’s state lender to potentially combine its fixed network assets with those of rival Open Fiber. The move indicated that the telecom’s boardroom is inclined to dismiss KKR &amp; Co’s EUR 33 billion takeover bid made in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/currency </td>
   <td style="text-align:left;"> 2022-04-04 23:25:00 </td>
   <td style="text-align:left;"> South African Rand Firms </td>
   <td style="text-align:left;"> The South African rand was trading higher at around 14.6 against USD, close to a five-month high of 14.5 hit on March 30th, amid higher precious metals prices and as markets welcomed Moody's revision of the country's outlook to "stable" from "negative". Also, expectations of continued tightening of monetary policy and a better economic outlook penciled by the South African Reserve Bank provided further support. The central bank raised interest rates by a further 25 bps on March 24th and signaled gradual normalization of the monetary policy through to 2024. At the same time, South Africa has seen a sustained return to improved economic growth, driven by higher commodity prices and a return to pre-pandemic conditions. Still, the prospect of a more hawkish Fed and uncertainty around the war capped gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/rating </td>
   <td style="text-align:left;"> 2022-04-04 23:17:00 </td>
   <td style="text-align:left;"> Moody’s Revises South Africa’s Rating Outlook to Stable </td>
   <td style="text-align:left;"> Moody’s Investors Service changed on April 1st 2022 South Africa’s sovereign credit rating outlook to stable from negative and affirmed the debt grade at ‘Ba2’, citing as the key driver behind the revision the improved fiscal outlook that raises the likelihood of the government's debt burden stabilizing over the medium term. The agency noted that South Africa's fiscal position has markedly recovered from the pandemic thanks to government's fiscal consolidation measures and positive external developments, in particular due to high commodity prices. Moody’s expects that the government will continue to pursue its fiscal consolidation strategy. Standard &amp; Poor's credit rating for South Africa stands at BB- with stable outlook. Fitch's credit rating for South Africa was last reported at BB- with stable outlook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60983553?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-04 23:16:29 </td>
   <td style="text-align:left;"> Kinder Surprise eggs recalled over salmonella link </td>
   <td style="text-align:left;"> Some Kinder Surprise chocolate eggs have been recalled over a link to 63 UK cases of salmonella mostly in young children.                                                                                                                                                                , The Food Standards Agency (FSA) said all the eggs affected had been made in the same factory in Belgium.                                                                                                                                                                                 , It advised people not to eat 20g or three-pack eggs with best before dates between 11 July and 7 October 2022.                                                                                                                                                                           , Chocolate-maker Ferrero said none of its Kinder products released for sale had tested positive for salmonella.                                                                                                                                                                           , "We take matters of food safety extremely seriously and we sincerely apologise for this matter," the firm said.                                                                                                                                                                          , No deaths have been reported but most of the 63 salmonella cases so far are among children aged five and under.                                                                                                                                                                          , More cases have reportedly been recorded in Europe, including Ireland, France, Germany, Sweden and the Netherlands.                                                                                                                                                                      , The FSA said Ferrero was voluntarily recalling the products as a precautionary measure and added it had received no complaints.                                                                                                                                                          , It said the firm was working closely with food safety authorities to identify the exact cause of the outbreak.                                                                                                                                                                           , Other products manufactured by Kinder are not believed to be affected, the FSA said.                                                                                                                                                                                                     , The agency said in an alert that investigations by public health bodies "found a link between reported cases of salmonella poisoning across the UK and a specific product produced by the Ferrero company".                                                                              , "We know that these particular products are popular with young children, especially as Easter approaches, so we would urge parents and guardians of children to check if any products already in their home are affected by this recall," said Tina Potter, head of incidents at the FSA., Dr Lesley Larkin, of the UK Heath Security Agency, said symptoms of salmonellosis, which can include diarrhoea, stomach cramps, nausea, vomiting and fever, "typically resolve themselves within a few days".                                                                            , She said symptoms could be more severe, especially in young children and those with weakened immune systems and anybody with concerns should contact their GP or call NHS 111.                                                                                                           , Salmonella can be spread from person to person, so Dr Larkin advised anyone with symptoms to wash their hands thoroughly and avoid handling other people's food.                                                                                                                         , What did Putin do before he came to power?                                                                                                                                                                                                                                               , Life in the world's oldest town...                                                                                                                                                                                                                                                       , Searching for Vladislav Surkov, key architect of the 'post truth' world                                                                                                                                                                                                                  , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/04/politics/joe-biden-bucha-russia-war-crimes/index.html </td>
   <td style="text-align:left;"> 2022-04-04 23:13:40 </td>
   <td style="text-align:left;"> Biden calls for war crimes trial after Bucha images surface - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)President Joe Biden on Monday said the atrocities allegedly committed by Russian forces in Bucha, Ukraine, are a "war crime" and called for a trial to take place against Russian President Vladimir Putin.                                                                                                                                                                                        , The US President did not, however, label the killings a "genocide" but said he was looking into additional sanctions against Russia.                                                                                                                                                                                                                                                                     , Biden said the images coming from Bucha warranted calling Putin a "war criminal," adding, "but we have to gather the information. We have to continue to provide Ukraine with the weapons they need to continue the fight and we have to get all the details so this can be an actual -- have a war crime trial."                                                                                        , White House national security adviser Jake Sullivan said later Monday that the US hasn't yet seen evidence of "systematic" killings that would warrant designating what's underway in Ukraine a genocide.                                                                                                                                                                                                , "Based on what we have seen so far -- we have seen atrocities. We have seen war crimes. We have not seen a level of systemic deprivation of life of the Ukrainian people to rise to the level of genocide," Sullivan said during a White House press briefing.                                                                                                                                           , But the images from Bucha, Sullivan said, underscore that "now is not the time for complacency," stressing the importance of ongoing US support for Ukraine. He said the administration is "working around the clock" to fulfill security assistance requests from Ukraine, detailing the US and allied response so far and hinting at forthcoming "additional military assistance in the coming days."  , "We expect additional new capabilities to be delivered in the near future. We can't always advertise what is being delivered out of deference to our allies and partners or for operational sensitivities, but we are moving with speed and efficiency to deliver," he added.                                                                                                                            , Sullivan also confirmed that the US will issue additional sanctions against Russia this week, saying that the administration is "coordinating with our allies and partners on what the exact parameters of that will be."                                                                                                                                                                                , The White House has declined to go into specifics of how Biden's call for a war crimes trial for Putin would move forward, with Sullivan saying the US would have to "consult with our allies and partners on what makes most sense as a mechanism."                                                                                                                                                     , Biden's assessment that the killings did not amount to a genocide put him at odds with that of Ukrainian President Volodymyr Zelensky, who used the term during an interview with CBS on Sunday.                                                                                                                                                                                                         , "This guy (Putin) is brutal and what's happening in Bucha is outrageous and everyone's seen it," Biden said.                                                                                                                                                                                                                                                                                             , Images released this weekend show civilian bodies strewn across a street following the withdrawal of Russian forces, and CNN reporters observed a mass grave in the town, with residents saying they believe at least 150 people are buried there.                                                                                                                                                       , The scenes out of the Kyiv suburb of Bucha have drawn international outrage, with Western leaders calling for war crimes investigations and fresh sanctions against Russia.                                                                                                                                                                                                                              , US Ambassador to the United Nations Linda Thomas-Greenfield is expected to call on the UN to suspend Russia from the Human Rights Council on Tuesday, which she'll be doing at the President's direction, White House press secretary Jen Psaki said during Monday's press briefing.                                                                                                                     , "He believes it's ludicrous for Russia to be a member of the Human Rights Council and certainly the ambassador spoke to this today ... and she will continue to make the case in her role when she returns to New York," Psaki said.                                                                                                                                                                     , US Secretary of State Antony Blinken said Sunday that the State Department would help document any attacks by Russian troops against Ukrainian civilians. NATO Secretary General Jens Stoltenberg called the deaths of civilians in Bucha a "brutality" and said "I strongly welcome" an investigation by International Criminal Court, which has opened an investigation into war crimes in Ukraine.    , The Russian Ministry of Defense claimed the extensive footage of dead civilians in Bucha was "fake" and that "not a single local resident suffered from any violent actions" during Russia's occupation of the town. "In the settlements of the Kiev region, Russian military personnel delivered and issued 452 tons of humanitarian aid to civilians," the ministry said in a statement.               , The Russian military, Sullivan said during the briefing, is "revising its war aims" in Ukraine, warning that the next phase of invasion could be "protracted" with Russia's aim being to "surround and overwhelm" east Ukraine.                                                                                                                                                                          , Sullivan said the White House has assessed that Russia will focus on defeating forces in Luhansk and Donetsk provinces and could potentially extend its force projection and presence deeper into Ukraine.                                                                                                                                                                                               , This story has been updated with comments from national security adviser Jake Sullivan and White House press secretary Jen Psaki.                                                                                                                                                                                                                                                                        , CNN's Kevin Liptak, Betsy Klein and Nikki Carvajal contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-04 23:12:59 </td>
   <td style="text-align:left;"> Swiss 10Y Bond Yield Eases from 2014-High </td>
   <td style="text-align:left;"> The yield on the Swiss 10-year government bond decreased to the 0.5% level from the 2014-high of 0.7% touched on March 30th, in line with lower European bond yields as sanctions risks with Russia and growth jitters heightened demand for safer debt instruments. At the same time, the Swiss National Bank increased the credit to sight accounts of commercial banks by CHF 5.7 billion on the week ending on April 1st in an effort to control the franc’s appreciation. In its March meeting, the SNB kept the benchmark rate unchanged at -0.75% and emphasized it will keep continue to curb the franc’s strengthening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/currency </td>
   <td style="text-align:left;"> 2022-04-04 23:06:26 </td>
   <td style="text-align:left;"> Aussie at Over 5-Month High </td>
   <td style="text-align:left;"> The Australian dollar firmed to $0.755 on Monday, a level not seen since October 29th of 2021, as traders braced for the RBA meeting this week. Although the Reserve Bank of Australia is not expected to move rates amid a pledge to stay patient on policy, investors will be watching for any hawkish cues. The Australian economy continued to show signs of strength in March, with job advertisements rising 0.4% to levels not seen since 2008 as inflation is forecasted to reach a 14-year high of 4.5% in Q1. Thus, analysts expect the RBA to begin raising interest rates in the 3rd quarter,but some put rate hike bets to as soon as June, catching up to the tightening cycle of the US Fed. The Aussie also benefited recently from stronger commodity prices given the country’s status as a net energy exporter and a major producer of other basic materials. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/bidens-tax-plan-income-rate-highest-world </td>
   <td style="text-align:left;"> 2022-04-04 22:48:33 </td>
   <td style="text-align:left;"> Biden's new tax plan would push top individual income rate to highest in developed world </td>
   <td style="text-align:left;"> Grover Norquist argues that the idea that this is only going to impact rich people is how the income tax was 'sold,' noting that 'all of these taxes are introduced and then moved right down to hit middle income Americans.'                                                                                                                                                , The U.S. would have the highest personal income tax rate in the developed world under the newest White House proposal that would dramatically raise the rates paid by well-off Americans.                                                                                                                                                                                     , The budget blueprint that President Biden unveiled last week includes several tax hikes on the ultra-wealthy and corporations that would push the top U.S. rates on both individual and corporate income to the highest level in the developed world, according to a new analysis published by the nonpartisan Tax Foundation.                                                , THESE STATES ROLLED BACK THEIR GASOLINE TAXES. OTHERS COULD FOLLOW                                                                                                                                                                                                                                                                                                            , The Biden team's proposal would raise the average top tax rate on personal income to 57.4%, the steepest rate in the 38-member Organization for Economic Co-operation and Development.                                                                                                                                                                                        , President Biden addresses the 76th Session of the U.N. General Assembly on Sept. 21, 2021 in New York City. (Timothy A. Clary-Pool/Getty Images / Getty Images)                                                                                                                                                                                                               , The president laid out a series of tax increases including a "Billionaire Minimum Income Tax" that would establish a 20% minimum tax on all U.S. households worth more than $100 million, or about 0.01% of Americans.                                                                                                                                                        , Under the proposal, the top sliver of U.S. households would be required to pay a tax rate of at least 20% on their full income, or the combination of wage income and whatever they made in unrealized gains. If a billionaire is not paying 20% on their income, they will owe a "top-up payment" that makes up the difference to meet the new minimum.                      , The White House projected that more than half the revenue generated by the tax would stem from the country's 700 billionaires.                                                                                                                                                                                                                                                , Night falls at the Capitol in Washington, Thursday, Dec. 2, 2021, with the deadline to fund the government approaching.  ( AP Photo/J. Scott Applewhite / AP Newsroom)                                                                                                                                                                                                        , Biden also proposed raising the corporate tax rate to 28% from 21% as part of his budget request and pitched a global minimum tax that's designed to crack down on offshore tax havens. Arizona Sen. Kyrsten Sinema has previously said that she will not support a corporate tax increase.                                                                                   , On top of that, the top marginal tax rate on ordinary income is already scheduled to increase from 37% to 39.6% in 2026 when parts of Republicans' 2017 tax law expire. Biden's budget also assumes that his massive spending bill – the Build Back Better plan – becomes law.                                                                                                , That plan included a slew of tax hikes including a 5% surcharge on modified adjusted gross income (MAGI) above $10 million, plus a 3% charge on MAGI above $25 million, for a total increase of 8% – which is equivalent to about a 9.1% tax rate on taxable income, the analysis shows.                                                                                      , The Internal Revenue Service (IRS) headquarters in Washington, D.C., U.S., on Friday, Feb. 25, 2022.  (Al Drago/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                    , The Build Back Better plan would also close provisions in the tax code that allow some wealthy taxpayers to avoid paying the 3.8% Medicare surtax on their earnings by strengthening a net investment income tax for anyone earning more than $400,000.                                                                                                                       , That means the top marginal tax rate on personal income at the federal level would rise as high as 51.4% in 2026, or roughly 52.5% on the basis of taxable income.                                                                                                                                                                                                            , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                   , That rate doesn't even factor in state income tax, which is paid by most Americans (just eight states do not tax income). The average top marginal state-local tax rate is about 6%, according to the Tax Foundation, which would mean the combined top tax rate on personal income would be around 57.4%. That's higher than any rate currently levied in a developed nation., Japan and Demark are currently tied among OECD nations for the highest top income tax, with a rate of 55.9%. They're followed by France (55.4%), Austria (55%) and Greece (54%).                                                                                                                                                                                              , The U.S. currently has a top combined rate of 42.9%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-says-hes-seeking-more/story.aspx?guid={9FCFB436-6587-48A3-A6F1-673BBE7190C7}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-04 22:46:04 </td>
   <td style="text-align:left;"> Biden says he's seeking more Russia sanctions as he calls for war crimes trial for Putin - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden on Monday said he is seeking to impose more sanctions on Russia, following the emergence of evidence of civilian executions in Ukraine. He also called for a war crimes trial for Russian President Vladimir Putin, telling reporters in Washington, "this guy is brutal." Reports of civilian massacres in Bucha, Ukraine, led to international condemnation from world leaders and pledges to ramp up economic measures against Russia.   , A paper co-authored by former U.S. Treasury Secretary Larry Summers argues a "super-tight" U.S. jobs market means it's unlikely the Federal Reserve will successfully engineer a soft landing.                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-04-04 22:42:05 </td>
   <td style="text-align:left;"> Heating Oil is up by 5.02% </td>
   <td style="text-align:left;"> Heating Oil increased 5.02% to 3.596 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-04-04 22:39:52 </td>
   <td style="text-align:left;"> Loonie Hovers Near 4-Month Highs </td>
   <td style="text-align:left;"> The Canadian dollar was changing hands around $1.248, closing in on its highest level since November 2021 on bets that the Bank of Canada will begin hiking its key interest rate in 50bps increments to tame inflation currently running at levels not seen since 1991. The central bank has not hiked by that magnitude since May 2000 while investors awaited the release of two Bank of Canada surveys that could offer clues on the inflation outlook. Lending further optimism to the bulls were elevated crude oil prices as Western nations' release of strategic reserves failed to eliminate supply worries. 
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2022-04-04 22:34:00 </td>
   <td style="text-align:left;"> Euro Weakens Toward 2-Year Low </td>
   <td style="text-align:left;"> The euro weakened further to below $1.10 in the first trading week of April, closing in on a nearly 2-year low of $1.0804 hit on March 7th, dragged down by concerns over the outlook of the bloc’s economy amid the war in Ukraine and surging inflation. The European Union plans to introduce fresh sanctions against Moscow following allegations of civilian massacres in the Ukrainian town of Bucha and leaders from Germany and Italy said the EU should debate ending Russian gas imports. Meanwhile, a survey showed investor morale in the Eurozone fell to its lowest level in nearly two years in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/04/uk-to-mint-its-own-nft-and-push-forward-with-crypto-regulation.html </td>
   <td style="text-align:left;"> 2022-04-04 22:32:57 </td>
   <td style="text-align:left;"> Britain announces plans to mint its own NFT as it looks to 'lead the way' in crypto </td>
   <td style="text-align:left;"> , LONDON — The U.K. government on Monday announced plans to mint its own non-fungible token, as part of a push toward becoming a "world leader" in the cryptocurrency space.                                                                                                                                                                                                                                                                           , Finance Minister Rishi Sunak has asked the Royal Mint — the government-owned company responsible for minting coins for the U.K. — to create and issue the NFT "by the summer," City Minister John Glen said at a fintech event in London. "There will be more details available very soon," he added.                                                                                                                                                , NFTs are digital assets that represent ownership of a virtual item like an artwork or video game avatar using blockchain, the technology that underpins many cryptocurrencies. They've gained a lot of traction over the past year thanks to increased adoption from celebrities and large corporations.                                                                                                                                             , The U.K.'s NFT initiative is part of a broader effort by the government to "lead the way" in crypto, according to Glen. The minister announced a number of steps the U.K. will take to bring digital assets under more regulatory scrutiny, including plans to:                                                                                                                                                                                      , "We shouldn't be thinking of regulation as a static, rigid thing," Glen said. "Instead, we should be thinking in terms of regulatory 'code' — like computer code — which we refine and rewrite when we need to."                                                                                                                                                                                                                                     , CNBC previously reported on the government's plans to unveil a regulatory framework for cryptoassets and stablecoins.                                                                                                                                                                                                                                                                                                                                , Stablecoins, cryptocurrencies that derive their value from sovereign currencies like the U.S dollar, are a fast-growing but controversial phenomena in the crypto world. Tether, the world's biggest stablecoin, has a circulating supply of more than $80 billion. But it's attracted criticism over a lack of transparency around the reserves that back the token. The government is now set to bring stablecoins into the U.K. regulatory system., Glen said the government was also "widening" its gaze to look at other aspects of crypto, including so-called Web3, a movement that proposes a more decentralized version of the internet built on blockchain technology.                                                                                                                                                                                                                            , "No one knows for sure yet how Web3 is going to look," Glen said. "But there's every chance that blockchain is going to be integral to its development."                                                                                                                                                                                                                                                                                             , "We want this country to be there leading from the front, seeking out the greatest economic opportunities."                                                                                                                                                                                                                                                                                                                                          , Mauricio Magaldi, global strategy director for crypto at the fintech consultancy 11:FS, took a skeptical view on the government's NFT plans. The decision "seems to be nothing more than a strategic PR-play," he said in an emailed comment. But "talk of the U.K. becoming a 'crypto hub' seems to hold much more promise," he added.                                                                                                              , Industry insiders have been calling for clarity about the U.K.'s position on crypto as policymakers around the world begin taking a closer look at the $2 trillion market.                                                                                                                                                                                                                                                                           , Last month, U.S. President Joe Biden signed an executive order urging government-wide coordination when it comes to regulating crypto. The move was seen as broadly positive for the sector.                                                                                                                                                                                                                                                         , Meanwhile, European Union lawmakers recently voted against measures that would have put the future of crypto mining at risk. However, they also passed new rules cracking down on anonymous crypto transfers.                                                                                                                                                                                                                                        , Back in the U.K., British regulators have taken a harsh tone on digital assets.                                                                                                                                                                                                                                                                                                                                                                      , The Financial Conduct Authority has shunned a vast majority of crypto firms applying to be registered with the watchdog, warning it's worried too many "financial crime red flags" are going unnoticed.                                                                                                                                                                                                                                              , Last week, the FCA extended a crucial deadline for crypto businesses on a temporary register — which includes Revolut and Copper — to obtain full authorization. Philip Hammond, the former U.K. finance minister, is an advisor to Copper.                                                                                                                                                                                                          , Several companies have been forced to wind down their U.K. crypto operations and move offshore after failing to make it onto the final register, including Blockchain.com, B2C2 and Wirex. Just 33 firms have been approved by the FCA.                                                                                                                                                                                                              , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                               , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                               , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                     , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                     , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                   , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/zimbabwe/interest-rate </td>
   <td style="text-align:left;"> 2022-04-04 22:22:00 </td>
   <td style="text-align:left;"> Zimbabwe Lifts Key Interest Rate to 80% </td>
   <td style="text-align:left;"> The Reserve Bank of Zimbabwe raised its overnight lending rate by 200bps to a record high of 80% during a monetary policy meeting held in April of 2022, citing the negative impact of the ongoing Russia-Ukraine conflict on domestic prices and the currency. The Committee was concerned with the escalation in annual inflation to 72.70% in March of 2022, from 66.11% in the prior month. The bank said that rising prices of oil, gas, fertilizers and other related products had the effect of increasing global inflation and inevitably had a negative impact on domestic costs of production and was destabilizing the foreign exchange market. The Zimbabwean dollar has lost nearly two-thirds of its value against the greenback since the last hike, in part due to monetary tightening in developed markets such as the US and the growing use of the greenback to pay for most transactions amid a lack of confidence in the local currency. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/factory-orders </td>
   <td style="text-align:left;"> 2022-04-04 22:14:00 </td>
   <td style="text-align:left;"> US Factory Orders Fall for 1st Time in 10 Months </td>
   <td style="text-align:left;"> Factory orders in the US declined by 0.5% month-over-month to $542 billion in February of 2022, the first decline since April last year as supply constraints and shortages of materials continue to weigh while consumer demand has been shifting from goods to services. Figures came in line with market forecasts. Orders for durable goods went down 2.1%, mainly due to transportation equipment (-5.3%). Other decreases were also seen in orders for machinery (-2.9%) and computers and electronic products (-1.1%). On the other hand, orders for for nondurable goods were up 1.2%. Excluding transportation, factory orders increased 0.4% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/bank-america-more-doubles-sustainable/story.aspx?guid={10BC44FC-2344-48D3-9EE2-EDDE4C8BBE62}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-04 22:12:32 </td>
   <td style="text-align:left;"> Bank of America more than doubles sustainable finance activity - MarketWatch </td>
   <td style="text-align:left;"> Bank of America Corp. 
        BAC,
        -0.17%
       said Monday it mobilized and deployed about $250 billion in sustainable finance activity for 2021, an all-time high and an increase of 140% over the year-ago figure of $105 billion. The effort comes after the bank set a goal in 2021 of $1.5 trillion by 2030 in sustainable finance. Paul Donofrio, vice chair of Bank of America, worked on the effort, along with Karen Fang, global head of sustainable finance. Shares of Bank of America fell 0.5% on Monday, compared to a drop of 0.3% by the Financial Select Sector SPDR ETF 
        XLF,
        -0.44%.
       , War in Ukraine, inflation and rising interest rates could combine to slow the pandemic recovery, Dimon warned in his annual letter                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-04-04 22:04:17 </td>
   <td style="text-align:left;"> Canada Stocks Edge Up on Monday </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, showed shy gains on Monday, not far from an all-time high of 22,087 hit on March 29th nonetheless, as miners and oil &amp; gas stocks received support from rising commodity prices. On corporate updates, Canadian miner Centerra Gold handed over the Kumtor gold mine to the Kyrgyz government ending a one-year legal conflict with the state government. On the data front, the value of building permits in Canada jumped 21% to a fresh record high of C$12.4B in February, with non-residential permits booming in BC and Quebec due to plans to build large hospitals. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-04-04 21:59:42 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Down for 8th Day </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index fell 2.1% to 2,307 points on Monday, its lowest since March 7th, extending losses for the eighth straight session, amid weakness across all its vessels segments. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, slumped 3.7% to 1,796 points; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, decreased 1.9% to 3,015 points. Among smaller vessels, the supramax index dropped 38 points to 2,717 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/sugar </td>
   <td style="text-align:left;"> 2022-04-04 21:53:00 </td>
   <td style="text-align:left;"> Sugar Futures Rise to 4-Week High </td>
   <td style="text-align:left;"> Sugar futures on ICE rose to $19.7 per pound in the beginning of April, the highest in four weeks, tracking a sharp rebound in crude oil prices. Energy price trends heavily influenced output projections in Brazil, with mills opting to use sugarcane to produce biofuels instead of raw sugar. Data from S&amp;P Global Commodity Insights indicated the Brazilian ethanol’s growing production premium to sugar reached 208 points in April. That is largely due to a 7.8% jump in ethanol prices and a 6.8% appreciation of the real against the dollar during March 10th to April 1st, while sugar futures only rose 1.4% in the same time period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-04-04 21:47:00 </td>
   <td style="text-align:left;"> Brazilian Equities Edge Down </td>
   <td style="text-align:left;"> The main Sao Paulo Index, Ibovespa, was down 0.5% to around 121,000 on Monday, led by heavyweight Petrobras, despite rising oil prices after Rodolfo Landim declined on Sunday a nomination to chair the board of state-run oil company to focus on his current role as president of Rio de Janeiro soccer club Flamengo. Petrobras' board reshuffle is taking place amid pressure from Brazilian President Jair Bolsonaro on the company to refrain from raising domestic fuel prices. Banks and retailers also posted significant losses, while miner Vale and steel companies gained, tracking rising iron ore prices. At the same time, the prospect of further sanctions being imposed on Russia over its actions against Ukraine weighed on market sentiment. Locally, the central bank’s so-called Focus survey, usually published every Monday, was not disclosed today by the bank due to disruptions caused by an indefinite workers' strike. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/ford-stock-falls-after-march/story.aspx?guid={C7B35709-C411-4047-BC6C-6C3E064217B1}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-04 21:46:51 </td>
   <td style="text-align:left;"> Ford stock falls after March vehicle sales drops nearly 26% from a year ago - MarketWatch </td>
   <td style="text-align:left;"> Shares of Ford Motor Co. 
        F,
        +0.06%
       fell 0.8% in morning trading, after the automaker said total March sales dropped 25.6% from a year ago to 159,328, but showed an increase from a month ago given improvements in production and inventory. The automaker also said retail orders at dealers rose 33% from a year ago to a record 88,000 orders in March. Within total vehicle sales, truck sales dropped 34.4% to 74,420 and SUVs fell 9.4% to 81,280, while electrified vehicles increased 16.9% to 13,772. Sales of Ford's best selling F-Series trucks fell 46.6% to 44,906 in March, sales of the Explorers, the best-selling SUV, dropped 35.9% to 16,915. Ford's stock has dropped 20.5% year to date, while shares of rival General Motors Co. 
        GM,
        +0.51%
       have shed 26.7% and the S&amp;P 500 
        SPX,
        +0.81%
       has lost 4.6%., Artists and groups who first made their mark decades ago, including the Beatles, are winning the streaming wars                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/miami-mayor-reveals-the-formula-for-his-citys-success-as-tech-hub </td>
   <td style="text-align:left;"> 2022-04-04 21:41:39 </td>
   <td style="text-align:left;"> Miami mayor reveals the formula for his city’s success as tech hub </td>
   <td style="text-align:left;"> Miami Mayor Francis Suarez argues that crypto is one major way that his city has 'completely leaned into innovation' and is being recongized for its technological achievements.                                                                                                                                                    , Miami Mayor Francis Suarez told "Mornings with Maria" on Monday that cryptocurrency is one of the ways his city has "completely leaned into innovation" and has put itself on the map as a major technology hub in America.                                                                                                         , Suarez made the comment as he revealed the formula for his city’s success as a technology hub ahead of the world’s largest Bitcoin conference that is being held in Miami starting on Wednesday.                                                                                                                                    , Bitcoin started the week trading down around $46,000, after gaining over the weekend ahead of the Bitcoin 2022 conference in Miami this week, which Suarez noted is "the largest crypto conference in the world."                                                                                                                   , "We are going to have 50,000 attendees and it’s going to be an economic development boom for our city, creating thousands of jobs and millions of dollars in economic incentives for our city," the Miami mayor told host Maria Bartiromo.                                                                                          , When Bartiromo asked Suarez why crypto has been important in terms of instituting it as part of the Miami economy, he responded by noting that "it’s part of our transitional brand from a city that was a great place to visit, a great place to retire, to what [the] Financial Times called "the most important city in America.", CLICK HERE FOR FOX BUSINESS' REAL-TIME CRYPTOCURRENCY PRICING DATA                                                                                                                                                                                                                                                                  , Francis Suarez, mayor of Miami, speaks during the Bitcoin 2021 conference in Miam. (Eva Marie Uzcategui/Bloomberg via Getty Images) (Eva Marie Uzcategui/Bloomberg via Getty Images / Getty Images)                                                                                                                                 , He noted that Miami was able to achieve that title "by keeping true to three simple rules," which includes keeping taxes as low as possible and increasing funding for the police.                                                                                                                                                  , Suarez noted that prioritizing safety has led to a reduction in homicides "last year by 23% and this year by close to 40%."                                                                                                                                                                                                         , He stressed that "leaning into innovation" is the third way Miami was able to put itself on the map as an important city.                                                                                                                                                                                                           , Miami Mayor Francis Suarez argues that crypto is one of the ways his city has 'completely leaned into innovation to take away this concept that there are other cities in America that are the technilogical hubs of our country.'                                                                                                  , "Crypto is one of the ways that we have completely leaned into innovation to take away this concept that there are other cities in America that are the technological hubs of our country," Suarez told Bartiromo.                                                                                                                  , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                         , "Because of that we have seen our venture capital increase by 200% year-over-year, and we’ve moved over a trillion dollars in assets under management companies to the city in just 16 months."                                                                                                                                     , CLICK HERE TO READ MORE ON FOX BUSINESS  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/money/ceo-pay-record-pandemic-recedes </td>
   <td style="text-align:left;"> 2022-04-04 21:36:01 </td>
   <td style="text-align:left;"> CEO pay heads for record as pandemic recedes </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines for April 4.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Pay increases for U.S. chief executives have gained steam, putting compensation on pace to set a record amid a tight labor market that is also driving pay higher for many of their workers.                                                                                                                                                                                                                                                                                                                                                                       , Median pay rose to $14.2 million last year for the leaders of S&amp;P 500 companies, up from a record $13.4 million for the same companies a year earlier, according to a Wall Street Journal analysis of pay data for more than half the index from MyLogIQ LLC.                                                                                                                                                                                                                                                                                                      , Most CEOs received a pay increase of 11% or more, and pay rose by at least 25% for nearly one-third of them. Pay fell for about a quarter of the CEOs, including Paycom Software Inc.’s Chad Richison, last year’s highest-paid S&amp;P 500 leader, whose pay fell to about $3 million from $211 million.                                                                                                                                                                                                                                                              , ELON MUSK PURCHASES STAKE IN TWITTER AFTER SLAMMING ITS APPROACH TO 'FREE SPEECH'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , In 2020, while CEO pay rose overall, nearly one-third of these executives had their total compensation decline from a year earlier, and many forfeited some pay during the pandemic.                                                                                                                                                                                                                                                                                                                                                                               , Pay for rank-and-file employees rose, too, last year but more slowly, as measured by the compensation figures the companies report for their median employee. Half the companies said pay for their median worker increased by 3.1% or less in 2021, and at one-third of companies, median employee pay declined year over year—broadly similar to prepandemic rates of change.                                                                                                                                                                                    , An employee prepares a package for shipment at the Amazon logistics centre in Suelzetal, eastern Germany, on Mai 12, 2021. (Ronny Hartmann/AFP / Getty Images)                                                                                                                                                                                                                                                                                                                                                                                                     , CEOs at roughly half the companies were paid at least 186 times what their median worker made in 2021, according to the Journal analysis. That is up from 166 times in the year before the pandemic and 156 times in 2018, the first year that nearly all S&amp;P 500 companies reported median employee pay.                                                                                                                                                                                                                                                          , The Securities and Exchange Commission requires companies to disclose how much their typical worker makes and how it compares with their chief executive’s compensation. The disclosure was mandated by the 2010 Dodd-Frank Act in the wake of the financial crisis as executive pay came under more scrutiny, and some investors called for better insight into how companies treated rank-and-file employees. More recently, some asset managers have put more weight on environmental, social and governance issues.                                            , BILLIONAIRE SUPERMARKET OWNER WARNS FOOD PRICES WILL 'CONTINUE TO RISE' FOR NEXT FEW MONTHS                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , At some large companies, the board’s compensation committees have expanded their scope beyond executive pay to that of the workforce generally, said Caitlin McSherry, director of investment stewardship at Neuberger Berman, which manages more than $460 billion. At the same time, investors have few tools to understand how companies pay workers.                                                                                                                                                                                                           , "It all comes back to thinking about the workforce in totality," Ms. McSherry said. "There aren’t too many disclosures out there that provide insight into workforce pay."                                                                                                                                                                                                                                                                                                                                                                                         , HOWARD SCHULTZ RETURNS TO STARBUCKS AS CEO AMID LABOR UPRISING                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Companies say the pay ratio is a blunt instrument that offers little meaningful insight, in part because businesses have a range of operational structures. Outsourcing low-wage work, for instance, can lift the employee median pay and make a company’s ratio lower. In addition, the SEC’s disclosure rule gives companies wide leeway in identifying median workers, making comparisons between companies more difficult. Executive pay also can be highly variable, with some companies making multiyear grants, leading to periodic spikes in the pay ratio., The seal of the U.S. Securities and Exchange Commission hangs on the wall at SEC headquarters (Reuters/Jonathan Ernst / Reuters Photos)                                                                                                                                                                                                                                                                                                                                                                                                                            , The widening gap between CEO pay and median worker pay comes amid a tight U.S. labor market, thrown askew as millions of people dropped out of the workforce during the pandemic. Executives at airlines, manufacturers, retailers and restaurants alike have talked about the struggles of finding and hiring enough workers in the U.S.                                                                                                                                                                                                                          , Businesses are competing for workers and raising wages. U.S. average hourly wages rose by about 4.9% for all workers in 2021, according to the U.S. Labor Department. The U.S. unemployment rate fell to 3.6% in March as employers added more than 400,000 jobs for the 11th month in a row.                                                                                                                                                                                                                                                                      , AMAZON CEO ANDY JASSY’S COMPENSATION VALUED AT $213 MILLION IN 2021                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The CEO compensation figures are reported by companies and include the value of stock awards at the time of grant, along with salary, cash bonuses, perks and some retirement-benefit increases. Equity awards, the value of which can rise or fall significantly after grant, accounted for the bulk of pay for the highest-paid CEOs in the Journal’s analysis. These awards typically vest, or become fully the executive’s, over several years and can be tied to performance targets.                                                                         , Discovery Inc.’s David Zaslav, at nearly $247 million, had the highest 2021 pay disclosed so far among the CEOs of S&amp;P 500 companies who served the full year. Mr. Zaslav’s pay was nearly 3,000 times the $82,964 that the company reported paying its median worker last year, up from a multiple of 1,511 in 2018.                                                                                                                                                                                                                                              , Discovery CEO David Zaslav speaks onstage during the Discovery, Inc. portion of the Discovery Communications Winter 2019 TCA Tour at the Langham Hotel on February 12, 2019, in Pasadena, California. (Amanda Edwards/Getty Images for Discovery)                                                                                                                                                                                                                                                                                                                  , Discovery says that much of Mr. Zaslav’s 2021 pay consists of stock-option awards tied to a new contract signed last year, and his pay excluding one-time awards would be 527 times the median worker’s. The media company’s share price would have to rise significantly for the options to be in the money. Mr. Zaslav is poised to run a bigger company when Discovery completes its merger with AT&amp;T Inc.’s WarnerMedia, which owns HBO and Warner Bros.                                                                                                       , The second-highest paid CEO so far in the S&amp;P 500 was Amazon.com Inc.’s Andy Jassy, who was awarded compensation valued at nearly $213 million, nearly all in restricted stock. That was nearly 6,500 times the median Amazon worker, who made $32,855 in 2021.                                                                                                                                                                                                                                                                                                    , TOYOTA IS STILL OUTSELLING GENERAL MOTORS IN 2022                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The online retailer, which has hired hundreds of thousands of workers as its business surged in the pandemic, has faced efforts to unionize some of its warehouses. The company said its average annual starting wage has risen to $18 an hour.Mr. Jassy took over for founder Jeff Bezos in July 2021, and won’t feature in the Journal’s full rankings later this spring because he was CEO less than a full year. Mr. Bezos continued to make about $1.7 million, almost entirely made up of company-paid security costs.                                       , Most of Mr. Jassy’s equity won’t vest for at least five years, and the award is structured to give him roughly the same number of shares each year, valued at $33 million to $35 million at recent share prices, after 2023, Amazon’s securities filing says. An Amazon spokesman called the award competitive with that of CEOs at other large companies.                                                                                                                                                                                                         , In this Dec. 5, 2019, file photo, AWS CEO Andy Jassy, discusses a new initiative with the NFL during AWS re:Invent 2019 in Las Vegas. (Isaac Brekken/AP Images for NFL / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                                              , Intel Corp. paid Pat Gelsinger, who rejoined the chip maker in the top spot in February 2021, compensation valued at nearly $179 million, or about 1,700 times the $104,400 pay of its median employee, a program manager in Malaysia.                                                                                                                                                                                                                                                                                                                             , Intel said Mr. Gelsinger’s pay reflected his experience, the challenge of transforming Intel and $50 million in compensation he gave up by leaving business software company VMware Inc. Excluding one-time payments, Mr. Gelsinger’s pay for 2021 was about 276 times that of the company’s median worker, Intel said in its annual proxy statement.                                                                                                                                                                                                              , JOB GROWTH JUMPS BY 431,000 IN MARCH: WHICH INDUSTRIES SAW THE BIGGEST PAYROLL GAINS?                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , As in recent years, some of the highest-paid CEOs of public companies weren’t running businesses in the S&amp;P 500 index.                                                                                                                                                                                                                                                                                                                                                                                                                                             , Private-equity giant KKR &amp; Co. reported paying co-CEOs Joseph Bae and Scott Nuttall compensation valued at $559.6 million and $523.1 million, respectively. The men took over last fall from company co-founders Henry Kravis and George Roberts. "The vast majority of the compensation is performance-based stock that will have to more than double in value for the stock awards to fully vest," a KKR spokeswoman said.                                                                                                                                       , One World Trade Center is reflected on the Goldman Sachs Group Inc. headquarters building in New York, U.S., on Wednesday, Oct. 12, 2016. (Photographer: Mark Kauzlarich/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                , Hollywood agency Endeavor Group Holdings Inc. reported paying Ari Emanuel compensation valued at more than $308 million last year, in part with an arrangement that carries no cap on the number of shares he could receive. The stock awards vest over several years. Endeavor declined to comment.                                                                                                                                                                                                                                                               , The Journal analysis included 325 CEOs at S&amp;P 500 companies with fiscal years ending after June 30 last year and reporting pay through April 1, using data from MyLogIQ, a research firm. Of those, 281 CEOs held the position for at least one full fiscal year.                                                                                                                                                                                                                                                                                                  , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Median employee pay, and the CEO pay ratios derived from them, are reported under Securities and Exchange Commission rules that give companies significant leeway on how they rank workers globally to identify the median employee. The pay for that median worker is then determined using the same rules that govern reported CEO pay. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-04 21:34:00 </td>
   <td style="text-align:left;"> S&amp;P 500, Nasdaq Rise on Tech Boost </td>
   <td style="text-align:left;"> The Dow opened Monday’s session mainly flat, while the S&amp;P 500 and Nasdaq outperformed as a surge in the shares of Twitter and US-China dual-listed companies offset worries about more sanctions against Russia over its invasion of Ukraine. Western nations could deliver another slew of economic sanctions on Russia, with French President Macron pushing for banning imports of Russian oil and coal, following mounting evidence of war crimes committed by its forces on the outskirts of Kyiv. Meanwhile, Twitter Inc surged over 20% after Elon Musk took a 9.2% stake in the company. Also, US-listed Chinese firms jumped after China’s securities watchdog proposed revising confidentiality rules involving offshore listings, clearing a legal hurdle to Sino-US cooperation on audit oversight. Still, concerns that rising inflation and higher interest rates will drag the nation’s economy into a recession have kept sentiment subdued. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/04/business/russia-energy-europe-sanctions/index.html </td>
   <td style="text-align:left;"> 2022-04-04 21:33:33 </td>
   <td style="text-align:left;"> Russian energy exports in focus as Europe plans new sanctions - CNN </td>
   <td style="text-align:left;"> London (CNN Business)European officials have signaled that they could sanction Russia's energy exports after images emerged of mass killings of civilians in Bucha, near the Ukrainian capital.                                                                                                                                                                                                       , Josep Borrell, the European Union's top diplomat, said in a statement Monday that the bloc was working as a "matter of urgency" on drawing up new sanctions against Russia. French President Macron said that he would support a total ban on Russian coal and oil exports to the European Union as soon as this week.                                                                                , Speaking to a French broadcaster, Macron said that there were "very clear signs" war crimes had been committed in Bucha and that, "it's pretty established that it's the Russian army" who is responsible for them.                                                                                                                                                                                   , "We can't let it slide. We must have sanctions that dissuade with what's happened there [in Bucha], what's happening at Mariupol," Macron said.                                                                                                                                                                                                                                                       , Europe has imposed punishing economic sanctions on Russia since President Vladimir Putin ordered the invasion of Ukraine in February. But oil and natural gas exports have so far been spared by the bloc — partly because of differences between member states that are heavily reliant on Russian energy and those wanting to move faster to strike at the heart of the Russian economy.            , But a block on Russia's gas exports would exacerbate soaring inflation in Europe's economies, and could tip Germany — Russia's biggest energy customer — and other countries into recession.                                                                                                                                                                                                          , "In the case of deliveries of Russian gas stopping, the situation would be aggravated," Deutsche Bank CEO Christian Sewing said in a statement. "A substantial recession in Germany could be hardly avoided."                                                                                                                                                                                         , Yet shocking scenes in Bucha over the weekend — a suburb of Kyiv that was until recently occupied by Russian forces — could persuade import-reliant countries to take the economic hit. The bodies of unarmed civilians were found strewn across roads, bound and shot. Russia has denied any involvement in the incident.                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                       , The stakes are high. The European Union imported nearly €100 billion ($110 billion) worth of Russian energy last year. Russia supplies about 40% of the bloc's imports of natural gas, and about 27% and 46% of its imported oil and coal respectively.                                                                                                                                               , EU leaders pledged to reduce consumption of Russian gas by 66% before the end of this year, and to break the bloc's dependence on Russian energy by 2027.                                                                                                                                                                                                                                             , Russian oil has already been banned by the United States and United Kingdom, and a wider de facto embargo has taken hold as banks, traders, shippers and insurance companies try to avoid falling foul of financial sanctions. The International Energy Agency says Russia could be forced to limit its production by 3 million barrels per day, starting this month, as it struggles to find buyers. , Some EU countries want the bloc to go further, and have been calling for a ban on Russian natural gas for weeks. One has just taken the step. Lithuania's Prime Minister Ingrida Šimonytė said in a tweet on Sunday that "from now and so on, Lithuania won't be consuming a cubic cm of toxic Russian gas."                                                                                          ,                                                                                                                                                                                                                                                                                                                                                                                                       , Germany has so far ruled out an immediate ban but a government minister said Sunday it must now be up for discussion.                                                                                                                                                                                                                                                                                 , "There has to be a response," she said. "Such crimes must not go unanswered," German Defense Minister Christine Lambrecht said in an interview with public broadcaster ARD.                                                                                                                                                                                                                           , Finance Minister Christian Lindne said Monday that Germany supports further sanctions on Russia but cutting off gas supplies was not possible right now.                                                                                                                                                                                                                                              , "We have to put more pressure on Putin and we have to isolate Russia, we have to cut all economic relationship to Russia but at the moment it's not possible to cut the gas supplies." Lindner told reporters in Luxembourg.                                                                                                                                                                          , "We need some time and so we have to differentiate between oil, coal and gas at the moment," he added.                                                                                                                                                                                                                                                                                                , Some fear that Hungary — another big buyer of Russian gas — could scupper any sanctions on energy. Polish Prime Minister Mateusz Morawiecki said Monday that he would try to "persuade" Viktor Orban, Hungary's newly re-elected prime minster and the closest EU leader to Putin, to support a block on gas imports.                                                                                 , "I call on the leaders of the European Union to act decisively, to implement actions that will finally break Putin's war machine and take its air," Morawiecki said.                                                                                                                                                                                                                                  , Last week, the United States tapped its strategic oil reserves, releasing 180 million barrels of oil into the global market, to help bring down gasoline prices and counter the reduction of Russian oil supplies. The IEA also agreed to release additional oil from its member countries at an emergency meeting on Friday.                                                                         , — Livvy Doherty, Chris Liakos, Joseph Ataman, Elias Lemercier, Anna Odzeniak, Niamh Kennedy, Inke Kappeler, James Frater and Mark Thompson contributed reporting.                                                                                                                                                                                                                                     , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/biden-budget-proposal-laughable-assumptions-tyler-goodspeed </td>
   <td style="text-align:left;"> 2022-04-04 21:32:06 </td>
   <td style="text-align:left;"> Biden's budget proposal rife with 'laughable assumptions': Former White House economist </td>
   <td style="text-align:left;"> Economist Tyler Goodspeed slams President Biden's proposed 2023 budget.                                                                                                                                                                                                                                                                                                                                                                        , Economist Tyler Goodspeed joined FOX Business' "Mornings with Maria" early Monday to discuss March's jobs report, soaring inflation, the possibility of an impending recession and President Biden's 2023 budget proposal. Goodspeed slammed the proposal for containing "laughable" economic assumptions that reach "far above consensus."                                                                                                    , REP. JASON SMITH SLAMS BIDEN'S BUDGET: THIS SPENDING IS ONLY GOING TO MAKE ‘LIVES WORSE’                                                                                                                                                                                                                                                                                                                                                       , TYLER GOODSPEED: As you noted, Maria, that was basically a four percent cut in defense spending proposed in the president's budget when you have eight percent inflation. In terms of the economic assumptions, look, they are so far above consensus on their expectations for GDP on their forecast for GDP, that is really going to flatter their deficit projections. They are so far behind in terms of where interest rates already are. , President Joe Biden speaks about the COVID-19 relief package in the State Dining Room of the White House, Monday, March 15, 2021, in Washington. (AP Photo/Patrick Semansky) (AP / AP Images)                                                                                                                                                                                                                                                  , That, again, is going to flatter their deficit projections. And then on the inflation front, they had inflation going back to the Fed's target basically in the fiscal year beginning October 1st of this year, and doing so with the unemployment rate remaining well below four percent. It just doesn't add up. Those are really, as I said, laughable assumptions.                                                                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                    , WATCH THE FULL INTERVIEW BELOW                                                                                                                                                                                                                                                                                                                                                                                                                 , Economist Tyler Goodspeed joins 'Mornings with Maria' to discuss President Biden's budget, March's jobs report and the possibility of a future recession. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2022-04-04 21:31:00 </td>
   <td style="text-align:left;"> UK Natural Gas Swings Lower </td>
   <td style="text-align:left;"> UK natural gas prices moderated to around 240 pence a therm, extending a downturn started with a 14% drop in the first session of April, as traders weighed prospects of warmer temperatures and steady Russian supplies. Also, the Kremlin had eased concerns over immediate supplies, saying “unfriendly” nations, such as the UK, could continue to pay in foreign currency until the end of the month or early May. Earlier, support came from worries over likely new sanctions on Russian energy imports, as Western leaders said reports of massacres that took place near Kyiv called for tougher action against Moscow. Russian natural gas makes up 3% of UK’s supplies, while Norway, the UK’s top supplier, unplanned outages at Norwegian gas fields continued to affect output. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/currency </td>
   <td style="text-align:left;"> 2022-04-04 21:12:17 </td>
   <td style="text-align:left;"> Turkish Lira Weakens </td>
   <td style="text-align:left;"> The Turkish lira fell to 14.7 per USD from the 2-week high of 14.5 touched on March 29th, as the possibility of further sanctions on Russia pressured the Turkish government’s fragile lira deposit protections scheme, while offering a worsened outlook for the country’s important tourism industry. Meanwhile, lower interest rates and surging energy costs lifted Turkey’s inflation rate to a 20 year high of 61.1% in March, while producer prices rose to a 27-year high of 115%. In its March meeting, the Central Bank of Turkey held its key borrowing costs steady for the third time since September in its March meeting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-04-04 20:54:00 </td>
   <td style="text-align:left;"> Brent Crude Rebounds in Volatile Trading </td>
   <td style="text-align:left;"> Brent crude futures rose to $107 per barrel in volatile trading on Monday, as tight supply and the possibility of more sanctions on Russia overshadowed a coordinated release of strategic reserves from consuming nations and a Covid-19 outbreak in China. The European Union is preparing to impose additional sanctions on Russia amid reports of civilians atrocities in Ukraine. Meanwhile, Saudi Aramco increased its Arab Light crude for next month’s shipments to Asia by $4.4 a barrel to a new record of $9.35. Last week, oil prices slumped about 13% after President Biden announced a release of up to 1 million barrels of oil a day for six months, and other countries including IEA members pledged to do the same. Elsewhere, the UN has brokered a 2-month truce between a Saudi-led coalition and the Houthi group for the first time in the 7-year conflict, which could normalize energy flows in the region. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/jamie-dimon-us-economy-risks-letter-shareholders </td>
   <td style="text-align:left;"> 2022-04-04 20:50:44 </td>
   <td style="text-align:left;"> Jamie Dimon warns US economy faces major risks from inflation, Russia-Ukraine war </td>
   <td style="text-align:left;"> JPMorgan Chase CEO joins ‘Mornings with Maria’ for a 3-part interview Tuesday at 6 am ET.                                                                                                                                                                                                                                                                                                              , JPMorgan Chase CEO Jamie Dimon warned in his annual shareholder letter that the U.S. economy faces a potential convergence of unprecedented risks in the year ahead that have him preparing for the worst.                                                                                                                                                                                             , Although the economy remains in good health, the head of the nation's largest bank said that the Russian war in Ukraine could collide with sky-high inflation and an increasingly hawkish Federal Reserve this year to slow growth and reshape the world for years to come.                                                                                                                            , FED RAISES INTEREST RATES FOR FIRST TIME IN 3 YEARS, PROJECTS 6 MORE HIKES AS INFLATION SURGES                                                                                                                                                                                                                                                                                                         , "They present completely different circumstances than what we’ve experienced in the past—and their confluence may dramatically increase the risks ahead," Dimon said. "While it is possible, and hopeful, that all of these events will have peaceful resolutions, we should prepare for the potential negative outcomes."                                                                             , JPMorgan Chase CEO Jamie Dimon speaks at the North America's Building Trades Unions (NABTU) 2019 legislative conference in Washington, U.S., April 9, 2019.  (Reuters / Reuters Photos)                                                                                                                                                                                                                , The outlook has shifted considerably since Dimon wrote the closely watched letter to shareholders last year in which he said an economic "Goldilocks moment" could last until 2023. At the time, the economy was on the upswing as vaccination rates increased, more Americans ventured out to shop, eat at restaurants and travel and the government approved another influx of federal relief money. , But since then, American consumers have confronted the fastest inflation spike since 1982 as the price of everyday goods including food, gasoline and cars surges higher.                                                                                                                                                                                                                              , Gas prices are advertised at over five dollars a gallon Monday, Feb. 28, 2022, in Los Angeles.  (AP Photo/Marcio Jose Sanchez / AP Newsroom)                                                                                                                                                                                                                                                           , "In hindsight, the medicine…was probably too much and lasted too long," Dimon wrote, referring to the trillions in pandemic-era stimulus measures that padded consumers' wallets and helped to keep businesses afloat.                                                                                                                                                                                 , The outbreak of the worst European conflict in decades has also roiled markets and threatened to push inflation even higher – in addition to creating a massive humanitarian crisis that has left more than 13,000 dead and millions displaced.                                                                                                                                                        , "Along with the unpredictability of war itself and the uncertainty surrounding global commodity supply chains, this makes for a potentially explosive situation," Dimon said.                                                                                                                                                                                                                          , Dimon said that he is not concerned about JPMorgan's direct exposure to Moscow – though he disclosed the company stands to lose about $1 billion "over time" from its businesses in Russia.                                                                                                                                                                                                            , In this Jan. 29, 2020 file photo, Federal Reserve Chair Jerome Powell pauses during a news conference in Washington. (AP Photo/Manuel Balce Ceneta, File / AP Newsroom)                                                                                                                                                                                                                                , Finally, the chief executive said that the Federal Reserve poses a risk to the economy, saying the central bank could move interest rates "significantly higher than the markets expect."                                                                                                                                                                                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                            , Fed policymakers began raising rates last month and have penciled in six, similarly sized increases this year. But officials have since suggested they could move more aggressively to tighten policy amid concerns the Fed waited too long to confront sky-high inflation.                                                                                                                            , "This process will cause lots of consternation and very volatile markets," Dimon added. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/gas-prices-april-4-2022 </td>
   <td style="text-align:left;"> 2022-04-04 20:47:09 </td>
   <td style="text-align:left;"> Gas prices could dip again this week despite uptick in oil prices, expert says </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines for April 4.                                                                                                                                                                                                                                                       , Prices at the pump could decline as much as nine cents this week if oil falls back under $100 per barrel and Russia's war on Ukraine doesn't intensify, according to an industry expert.                                                                                                                          , Patrick De Haan, head of petroleum analysis for GasBuddy, estimated Sunday that the national average for gasoline in the U.S. has the potential to dip another 4 to 9 cents per gallon in the week ahead.                                                                                                         , He told FOX Business that it's "more likely" that gas prices will fall if the price of oil stays under $100 a barrel.                                                                                                                                                                                             , But, "if oil stays under $105, they (gas prices) may still decline, though they won't fall as far," De Haan said.                                                                                                                                                                                                 , West Texas Intermediate futures traded at more than $103 a barrel.                                                                                                                                                                                                                                                , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                           , The national average price for a gallon of regular gasoline is $4.17 on Monday, down 5.4 cents compared to a week ago, according to GasBuddy's Monday data compiled from price reports covering more than 150,000 gas stations nationwide.                                                                        , A multitude of factors contributed to this decline, including surging coronavirus cases and the release of a million barrels of oil per day from the nation's strategic petroleum reserve, De Haan said in a blog post.                                                                                           , A man checks gas prices at a gas station in Buffalo Grove, Ill., Saturday, March 26, 2022.  (AP Photo/Nam Y. Huh / AP Newsroom)                                                                                                                                                                                   , "Oil prices fell last week as Covid cases in China surged, prompting restrictions on movements and hurting oil demand," De Haan said. "Meanwhile, President Biden’s announcement that the U.S. would be releasing 180 million barrels from the Strategic Petroleum Reserve caused an even further decline in oil.", This caused gas prices "in nearly all areas of the country to fall over the last week," he added.                                                                                                                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                       , If the price of oil hits and stays at $110 per barrel "that's when decreases stop and prices may start going up slightly," De Haan said.                                                                                                                                                                          , Currently, the national average is already 25.5 cents higher than it was a month ago and $1.31 per gallon higher than a year ago, according to GasBuddy data.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/building-permits </td>
   <td style="text-align:left;"> 2022-04-04 20:36:00 </td>
   <td style="text-align:left;"> Canada Building Permits Rise to a Record High </td>
   <td style="text-align:left;"> The total value of building permits in Canada rose 21.0 percent over the month to a record high of CAD 12.4 billion in February of 2022, rebounding from an upwardly revised 8.2 percent decline in the previous month, with British Columbia (+130.2 percent) leading the way. Construction intentions in the residential sector were up 9.8 percent, while the non-residential sector jumped 43.2 percent, driven mainly by large hospital permits in British Columbia and Quebec. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-04-04 20:31:00 </td>
   <td style="text-align:left;"> European Stocks Trim Early Losses </td>
   <td style="text-align:left;"> European stocks trimmed earlier losses and were trading mixed on Monday afternoon, with both Frankfurt’s DAX near the flatline and the pan-European up 0.4%, as healthcare stocks more than offset losses in industrials and banks. Investors were worried about new sanctions against Russia, motivated by reports of massacres near Kyiv, while the European Commission was already planning on closing existing loopholes and expanding the list of sanctioned individuals. On the data front, Germany’s February exports beat expectations, ending up with a higher-than-anticipated surplus of €11.5B, with the effects of sanctions against Moscow to be felt in March. Among the worst performers, Danish shipping giant Maersk erased 7% after the retirement announcement of the subsidiary APM Terminals’ CEO. On the other hand, German takeout company Delivery Hero surged more than 10% after announcing a €1.4 billion in debt financing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/04/many-americans-face-big-tax-bills-on-2021-unemployment-benefits.html </td>
   <td style="text-align:left;"> 2022-04-04 20:30:01 </td>
   <td style="text-align:left;"> Many Americans face big tax bills on 2021 unemployment benefits </td>
   <td style="text-align:left;"> , Many Americans who collected unemployment benefits in 2021 may be on the hook for big bills this tax season.                                                                                                                                                                                                                  , The federal government and most states treat unemployment benefits as taxable income.                                                                                                                                                                                                                                         , However, tax wasn't collected on about 60% of unemployment benefits paid in 2021, according to Andrew Stettner, an unemployment expert and senior fellow at progressive think tank The Century Foundation who analyzed U.S. Department of the Treasury data.                                                                  , Here's a look at more tax-planning news.                                                                                                                                                                                                                                                                                      , Here's another way to think about it: About 60% of people opted not to withhold tax on those benefits, he said.                                                                                                                                                                                                               , Approximately 25 million people received unemployment benefits in 2021.                                                                                                                                                                                                                                                       , Workers collected $325 billion in total benefits in 2021, Stettner said, citing Treasury data.                                                                                                                                                                                                                                , States, which administer the benefits, offer the option to withhold tax at a standard 10% rate. State governments reported just $13.3 billion of tax withholding — roughly 40% of the $32.5 billion that would have been collected if everyone opted to withhold tax, Stettner said.                                          , "On average, only 40% of people withheld their taxes, and 60% didn't withhold at all," Stettner said.                                                                                                                                                                                                                         , That's roughly the same share as in 2020, according to a separate The Century Foundation analysis.                                                                                                                                                                                                                            , However, there's a key difference — Congress authorized a federal tax break on up to $10,200 of benefits, per person, in 2020 as part of the American Rescue Plan, a pandemic relief law. Most states gave the break for states levies, too, or already exempt unemployment compensation and other income from tax.           , As a result, millions of people didn't owe tax on their 2020 benefits or owed a lesser amount of tax.                                                                                                                                                                                                                         , However, a tax break isn't available for 2021 benefits. That doesn't mean individuals will necessarily have to write a check to the IRS this tax season — some may get a lower tax refund. Even those who opted for the 10% withholding may owe some money if their annual income lands them in a higher marginal tax bracket., The deadline to file a 2021 income-tax return is Monday, April 18.                                                                                                                                                                                                                                                            , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/currency </td>
   <td style="text-align:left;"> 2022-04-04 20:27:00 </td>
   <td style="text-align:left;"> Indian Rupee Hits 5-Week High </td>
   <td style="text-align:left;"> The Indian rupee rose to a 5-week high of 75.5 per USD amid persistent selling of the US dollar by the exporters and upbeat domestic equities on back of improved risk appetite. Lending further support to the rupee were India’s record high merchandise exports and Gross GST collection data in 2021-22 fiscal year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-04-04 20:25:00 </td>
   <td style="text-align:left;"> Oil Bounces Back on Supply Concerns </td>
   <td style="text-align:left;"> WTI crude futures rose nearly 4% to trade above $103 a barrel on Monday as tight supply and the possibility of more sanctions on Russia more than offset a coordinated release of strategic reserves from consuming nations and a Covid-19 outbreak in China. The EU is preparing to impose additional sanctions on Russia amid reports of civilians atrocities in Ukraine. Meanwhile, Saudi Aramco increased its Arab Light crude for next month’s shipments to Asia by $4.4 a barrel to a new record of $9.35. Last week, oil prices slumped about 13% after President Biden announced a release of up to 1 million barrels of oil a day for six months, and other countries including IEA members pledged to do the same. Elsewhere, the UN has brokered a 2-month truce between a Saudi-led coalition and the Houthi group for the first time in the 7-year conflict, which could normalize energy flows in the region. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/jordan/gdp-growth-annual </td>
   <td style="text-align:left;"> 2022-04-04 20:13:30 </td>
   <td style="text-align:left;"> Jordan Economy Expands for the 4th Straight Quarter </td>
   <td style="text-align:left;"> The Gross Domestic Product (GDP) in Jordan expanded 2.60 percent in the fourth quarter of 2021 over the same quarter of the previous year. It was the fourth consecutive quarter of economic expansion, supported primarily by the construction sector (+6.1 percent), followed by the quarrying sector (+5.6 percent); transport, storage &amp; communications sector (+3.9 percent ) and the wholesale, retail trade, restaurants &amp; hotels Sector (+3.5 percent). Considering the whole 2021, the economy grew 2.2 percent compared to last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/04/technology/elon-musk-twitter.html </td>
   <td style="text-align:left;"> 2022-04-04 19:59:43 </td>
   <td style="text-align:left;"> Elon Musk Becomes Twitter’s Largest Shareholder - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The Tesla chief executive, who has been critical of Twitter’s content moderation policies, has bought 9.2 percent of the social media company.                                                                                                                                                                                                                                                                                                                                                                                           , By Mike Isaac and Lauren Hirsch                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , When Elon Musk mulled taking Tesla private in 2018, he posted on Twitter to tell the world about it. When he got stuck in traffic in 2016, he tweeted the idea of an underground tunnel system to alleviate “soul destroying” congestion. And when he challenged President Vladimir V. Putin of Russia to one-on-one combat last month, he broadcast it on Twitter.                                                                                                                                                                      , Now Mr. Musk is putting his money where he mouths off.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , On Monday, a regulatory filing with the Securities and Exchange Commission revealed that Mr. Musk, the billionaire chief executive of Tesla and SpaceX and the world’s wealthiest person, had bought a 9.2 percent stake in Twitter, the social media platform where he has over 80 million followers. The purchase appears to make Mr. Musk Twitter’s largest shareholder, ahead of the 8.8 percent stake owned by the mutual-fund company Vanguard and dwarfing the 2.3 percent stake of Jack Dorsey, Twitter’s former chief executive., Mr. Musk’s Twitter investment, which he has been accumulating since at least last month, was worth about $2.89 billion based on the closing price of the company’s stock on Friday. But by the end of Monday, after news of his buy-in sent Twitter’s share price soaring more than 27 percent, it was worth about $3.7 billion. The shares are a fraction of Mr. Musk’s reported $270 billion-plus net worth.                                                                                                                           , Despite his penchant for sharing everything on Twitter — from business ideas, insults and memes to, this past weekend, his experience at a famed Berlin nightclub — Mr. Musk was uncharacteristically mum on the purchase of the company’s shares, at least initially.                                                                                                                                                                                                                                                                   , “Oh hi lol” he tweeted on Monday without elaborating after news of his investment had spread across Twitter. Mr. Musk, 50, did not respond to a request for comment. Twitter declined to comment.                                                                                                                                                                                                                                                                                                                                        , Mr. Musk has bought into Twitter at a delicate time for the company, which is based in San Francisco. Mr. Dorsey stepped down as chief executive in November and plans to leave the company’s board when his term ends this year, after facing down an activist shareholder and grappling with criticism from lawmakers and regulators about free speech, censorship and toxic content.                                                                                                                                                  , Mr. Dorsey handed the reins to Parag Agrawal, Twitter’s chief technology officer, who cuts a lower profile in Silicon Valley than Mr. Dorsey did. Mr. Agrawal has reorganized the executive ranks of the company. He is also deeply interested in a “decentralized” version of Twitter, one of Mr. Dorsey’s last pet projects at the company.                                                                                                                                                                                            , Under that effort, Twitter would shift online power into the hands of its users and challenge behemoths like Meta, the owner of Facebook and Instagram. Twitter is funding an independent effort to build a so-called open protocol for social media, weaving cryptocurrency into its app, and opening up to developers who want to build custom features for Twitter.                                                                                                                                                                   , What exactly Mr. Musk plans to do with his Twitter stake is unclear. He has criticized the company in recent weeks for failing in his view to adhere to free speech principles, and he has argued that users should be allowed to choose the algorithms that select the tweets they see, or build their own, instead of relying on Twitter to curate posts.                                                                                                                                                                              , The idea was one Mr. Dorsey championed while leading Twitter. “The choice of which algorithm to use (or not) should be open to everyone,” he said last month in response to a tweet from Mr. Musk pushing for algorithms that outsiders can build for the platform.                                                                                                                                                                                                                                                                      , It is unclear whether Mr. Musk will ask — or be invited — to join Twitter’s board. He filed a securities document called a 13G filing, indicating that he planned for the investment to be passive and that he did not intend to pursue control of the company.                                                                                                                                                                                                                                                                          , But Wall Street has already started speculating that Mr. Musk could change the status of his investment, continue buying Twitter shares or even try to acquire the company outright.                                                                                                                                                                                                                                                                                                                                                     , “We would expect this passive stake as just the start of broader conversations with the Twitter board/management that could ultimately lead to an active stake and a potential more aggressive ownership role of Twitter,” Daniel Ives, an analyst at Wedbush Securities, said on Monday morning.                                                                                                                                                                                                                                        , Steven Davidoff Solomon, a professor at the School of Law at the University of California, Berkeley, said the filing lets Mr. Musk “sort of hide whatever intent he might have with respect to Twitter.” But, he added, filing as a “passive investor” with an actual intent to push for control by switching filing types is “fraudulent,” though rarely prosecuted and difficult to prove.                                                                                                                                             , Mr. Musk’s long and complicated personal relationship with Twitter has already gotten him in trouble, with his tweets about Tesla’s finances resulting in legal wranglings with the S.E.C.                                                                                                                                                                                                                                                                                                                                               , If Mr. Musk pushes for change at Twitter, he would not be the first agitated investor the company has had to contend with. The activist firm Elliott Management took a position in Twitter and called for Mr. Dorsey’s removal in 2020. It later struck a deal with Twitter that included a $1 billion investment from the private equity firm Silver Lake and brought on new board members, including Silver Lake’s co-chief executive, Egon Durban. Silver Lake teamed up with Mr. Musk in his efforts to take Tesla private.          , Mr. Musk’s list of other business ventures runs long. Beyond Tesla and SpaceX, he is the founder of the Boring Company, a tunnel construction services company. Adding a role to the list could irk Tesla shareholders. In the last two months of last year, Mr. Musk sold around $16 billion of Tesla stock, equivalent to roughly 10 percent of his stake in the electric vehicle company.                                                                                                                                             , Executives who have juggled media projects with other private endeavors have sometimes found themselves in politicians’ cross hairs. Former President Donald J. Trump, for example, took a dim view of Amazon because he disagreed with coverage in The Washington Post, which Jeff Bezos bought in 2013. Tesla is a large beneficiary of environmental credits, while SpaceX pursues government contracts.                                                                                                                              , For Mr. Musk, the investment may also raise the volume of noise that he faces on Twitter. Already on Monday, Twitter users were inundating the billionaire with requests for an edit button on the social media service and asking him to reinstate certain banned accounts.                                                                                                                                                                                                                                                             , Adam Satariano, Jack Ewing and Peter Eavis contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/currency </td>
   <td style="text-align:left;"> 2022-04-04 19:53:33 </td>
   <td style="text-align:left;"> Swiss Franc Eases from 3-Week High </td>
   <td style="text-align:left;"> The Swiss franc fell to 0.93 per USD from the three-week high of 0.923 touched on March 30th, amid further efforts to curb the rise of the franc by the Swiss National Bank. Sight deposits at the SNB rose by CHF 5.7 billion in the week ending on April 1st from the previous week. The move is widely seen as a proxy for the central bank’s foreign currency interventions, which increased its credit on sight accounts of commercial banks with freshly created francs in exchange for foreign currency. Following the Russian invasion of Ukraine, the safe-haven franc rose to a 7-year high against the euro. On the monetary policy front, the Swiss National Bank kept interest rates unchanged at -0.75% in its March meeting, despite doubling its year-end inflation forecast to 2.1%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/04/stocks-making-the-biggest-moves-in-the-premarket-twitter-tesla-starbucks-and-more-.html </td>
   <td style="text-align:left;"> 2022-04-04 19:42:58 </td>
   <td style="text-align:left;"> Stocks making the biggest moves in the premarket: Twitter, Tesla, Starbucks and more </td>
   <td style="text-align:left;"> , Take a look at some of the biggest movers in the premarket:                                                                                                                                                                                                                                                                                                                                                              , Twitter (TWTR) – Twitter shares soared 26.1% in the premarket after a Securities and Exchange Commission filing showed that Tesla CEO Elon Musk had taken a 9.2% passive stake in Twitter.                                                                                                                                                                                                                               , Tesla (TSLA) – Tesla delivered just over 310,000 vehicles during the first quarter, a record for the electric vehicle maker but below Wall Street consensus estimates. Tesla gained 1% in premarket trading.                                                                                                                                                                                                             , Starbucks (SBUX) – Starbucks has suspended its share repurchase program, in a move it says will allow it to invest in future growth for the coffee chain. The move comes as Howard Schultz returns for a third stint as CEO, replacing the retiring Kevin Johnson. Starbucks fell 2.3% in premarket action                                                                                                               , JPMorgan Chase (JPM) – In his annual letter to shareholders, CEO Jamie Dimon said the bank could face a potential loss of $1 billion from its exposure to Russian investments.                                                                                                                                                                                                                                           , JD.com (JD), Netease (NTES), Alibaba (BABA), Tencent Music (TME) – U.S.-listed China stocks are rallying in premarket trading after China proposed revising confidentiality rules regarding audit oversight. That could remove an obstacle to U.S.-China cooperation and prevent those companies from being delisted in the U.S. JD.com jumped 5.1%, Netease rose 3.9%, Alibaba gained 4.3% and Tencent Music added 5.2%., Hertz (HTZ) – The car rental company announced a new partnership that will see Hertz buy up to 65,000 electric vehicles from electric vehicle maker Polestar over the next five years. Hertz gained 2.3% in the premarket.                                                                                                                                                                                               , Novartis (NVS) – Novartis announced a reorganization of its business units in a move the Swiss drugmaker could save at least $1 billion annually by 2024. The new structure will integrate the drugmaker's pharmaceuticals and oncology businesses. Novartis rose 1% in premarket trading.                                                                                                                               , General Motors (GM) – Canada will announce investments today in two GM plants in the country, according to a source who spoke to Reuters. The amount of the investments, which includes support for one plant that will produce electric commercial vehicles, is unknown.                                                                                                                                                , Logitech (LOGI) – Logitech was upgraded to "buy" from "neutral" at Goldman Sachs, which is encouraged by the recent strong financial performance for the maker of computer mice, keyboards and other computer peripheral devices. Logitech jumped 4.3% in the premarket.                                                                                                                                                 , Crox (CROX) – The casual shoe maker's stock slid 1.9% in premarket trading after Loop Capital downgraded it to "hold" from "buy" and slashed the price target to $80 from $150. Loop said investor sentiment on the stock has shifted, putting it in the "COVID winner" category.                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-04 19:39:00 </td>
   <td style="text-align:left;"> US Stock Futures Seesaw </td>
   <td style="text-align:left;"> US stock futures swung between small gains and losses on Monday as investors focused on developments in Russia Ukraine war and on corporate news. Western nations could deliver another slew of economic sanctions on Russia, with French President Macron pushing for banning imports of Russian oil and coal, following mounting evidence of war crimes committed by its forces on the outskirts of Kyiv. Meanwhile, Twitter Inc. climbed as much as 26% in premarket trading after Elon Musk took a 9.2% stake in the company. Also, concerns that rising inflation and higher interest rates will drag the nation’s economy into a recession have kept sentiment subdued. Treasury yields inverted again on Friday, with the 2-year yield briefly exceeding the 10-year yield. Wall Street is coming off a winning session, with the Dow, S&amp;P 500, and Nasdaq posting gains on Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-04-04 19:35:11 </td>
   <td style="text-align:left;"> Heating Oil Pressured by Reserves Release </td>
   <td style="text-align:left;"> Heating oil futures were around $3.5 a gallon, almost 19% below a record high of $4.3 hit on March 9th, in tandem with lower oil prices, as the Biden administration announced a record release of up to 180 million barrels, or 1 million barrels a day, for about six months from its strategic reserves. Also, US distillate stockpiles which include diesel and heating oil rose by 1.394 million barrels in the week ended March 25th, compared to market expectations of a 1.55-million-barrel drop, data from the EIA Petroleum Status Report showed. Meanwhile, OPEC+ stuck to plans to add a modest 432,000 barrels a day of supply in May, despite western pressure on Saudi Arabia and the UAE to use their spare capacity to boost output further. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60979656?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-04 19:30:10 </td>
   <td style="text-align:left;"> Elon Musk snaps up $3bn Twitter stake </td>
   <td style="text-align:left;"> Elon Musk has taken a 9.2% stake in Twitter, according to a US securities filing.                                                                                                                                    , The news sent Twitter shares soaring about 25% in pre-market trading.                                                                                                                                                , The Tesla founder bought 73,486,938 Twitter shares on 14 March, according to the Securities and Exchange Commission.                                                                                                 , The stake is worth $2.89bn (£2.20bn), based on Twitter's closing price on Friday.                                                                                                                                    , The stake makes him one of the largest shareholders in the company and is more than four times the 2.25% holding of Twitter founder Jack Dorsey.                                                                     , Musk is a regular Twitter user with more than 80 million followers, although recently he said he is giving "serious thought" to building a new social media platform.                                                , Late last month Musk asked his followers whether they thought the social media platform encouraged free speech.                                                                                                      , "Free speech is essential to a functioning democracy. Do you believe Twitter rigorously adheres to this principle?"                                                                                                  , He then asked: "Is a new platform needed?"                                                                                                                                                                           , He regularly uses Twitter to share updates from the companies he owns - including SpaceX and Neuralink. He is also known for sharing memes, adding to his popularity among fans.                                     , But some posts have drawn controversy.                                                                                                                                                                               , Last year he tweeted in response to a claim, made by the head of the UN World Food Programme (WFP), that just 2% of Mr Musk's wealth could help to solve world hunger.                                               , In October, Mr Musk said he would sell $6bn in Tesla stock and donate it to the WFP, provided it could describe "exactly how $6bn will solve world hunger".                                                          , This video can not be played                                                                                                                                                                                         , Mr Musk saw the valuation of his Tesla car company surpass a market value of $1 trillion last autumn, making it the fifth such firm to reach the milestone, after Apple, Microsoft, Amazon and Google-owner Alphabet., Soon after he took to Twitter to ask users if he should sell a 10% stake in the electric carmaker.                                                                                                                   , More than 3.5 million Twitter users voted, with nearly 58% voting in favour of the share sale leading to Musk selling around $5bn (£3.7bn) of shares in the firm in November.                                        , What did Putin do before he came to power?                                                                                                                                                                           , Life in the world's oldest town...                                                                                                                                                                                   , Searching for Vladislav Surkov, key architect of the 'post truth' world                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/consumer-confidence </td>
   <td style="text-align:left;"> 2022-04-04 19:22:00 </td>
   <td style="text-align:left;"> Mexico Consumer Morale Rebounds </td>
   <td style="text-align:left;"> Consumer confidence in Mexico rose to 43.9 in March of 2022, picking up from the upwardly revised 43.5 in the previous month. There were improvements in the current assessment of households’ financial situation (49 vs 48 in February), future expectations of households’ financial situation (57.3 vs 56.6), and the current assessment of Mexico’s economy (39.1 vs 39). At the same time, the propensity to do major purchases rose significantly (26.4 vs 25). On the other hand, the gauge measuring future expectations of the Mexican economy decreased (47.4 vs 48). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/tin </td>
   <td style="text-align:left;"> 2022-04-04 19:12:00 </td>
   <td style="text-align:left;"> Tin Rally Gains Steam </td>
   <td style="text-align:left;"> Tin futures were trading above $44,000 per tonne in April, approaching a record high of $49,500 hit on March 8th, supported by rising demand from the electronics sector, where tin is used for circuit board manufacturing. On top of that, global production stagnated over the past decade due to a lack of investment by large miners while, more recently, coronavirus-induced lockdowns disrupted output, particularly in Indonesia and Malaysia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cyprus/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-04-04 18:53:58 </td>
   <td style="text-align:left;"> Cyprus Retail Sales Fall the Most in 13 Months </td>
   <td style="text-align:left;"> Retail sales growth in Cyprus fell 2 percent year-on-year in February of 2022, reversing from a 12.6 percent jump in the previous month. It was the sharpest decline in retail trade activity since January of 2021, as sales fell faster for food products (-6.7 percent vs -3.3 percent in January) and eased significantly for textiles and clothing (9 percent vs 145.8 percent); automotive fuel (9.7 percent vs 22.5 percent); electrical household appliances, furniture, lighting equipment, and construction equipment (0.8 percent vs 32.2 percent); and computers and telecommunications equipment, curtains, carpets, books, stationery, sporting equipment, toys, flowers, plants, watches, and jewellery (1.9 percent vs 37.1 percent). On a monthly basis, sales grew 0.6 percent, rebounding from a 29.5 percent decline in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rhodium </td>
   <td style="text-align:left;"> 2022-04-04 18:52:00 </td>
   <td style="text-align:left;"> Rhodium Eases, But Sentiment Remains Bullish </td>
   <td style="text-align:left;"> Rhodium futures were trading around $20,000 per troy ounce as investors unwound some recent long positions following a massive rally that drove them to an almost nine-month high of $22,200 in early March. Still, fundamentals in the rhodium complex continue to be supported by persistent concerns over the commodity's supply on the heels of Russia's invasion of Ukraine. Although South Africa is a significant source of rhodium at almost 60% of the world supply, Russia accounts for 10% of the global market. On top of that, the chip shortage in the car industry is set to ease, allowing the auto industry to resume normal levels of activity and drive a rebound in the production of catalytic converters. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-04-05 09:37:55 UTC +8

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
   <td style="text-align:left;"> 2022-04-05 09:37:25 </td>
   <td style="text-align:left;"> $SPY really underestimated bulls today, but thats okay. Tomorrow is a new day! Also ofg can suck my sack. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:37:08 </td>
   <td style="text-align:left;"> $SPY well at least it filled one gap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:37:05 </td>
   <td style="text-align:left;"> $SPY $QQQ why didn’t remy
Martin start? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:36:44 </td>
   <td style="text-align:left;"> $SPY They cannot guard the bigs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:35:50 </td>
   <td style="text-align:left;"> $SPY So Elon still buying stocks and y’all concerned about a bear market.. yea idk.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:35:37 </td>
   <td style="text-align:left;"> $SPY Nope.  You missed the boat.  In 2008 no one spoke about about bear market rallies. You suck.  We ain’t selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:35:35 </td>
   <td style="text-align:left;"> $SPY Elon please bring back Trump $twtr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:35:29 </td>
   <td style="text-align:left;"> $SPY last call for spicy nuggets I&amp;#39;m bouta gtfo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:35:04 </td>
   <td style="text-align:left;"> $SPY morgan stanley called the end of the bear rally, news flash tomorrow bulls are broke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:34:38 </td>
   <td style="text-align:left;"> $SPY ISSA FUTESSS PARTY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:34:38 </td>
   <td style="text-align:left;"> $SPY good night merlin 🧙‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:34:20 </td>
   <td style="text-align:left;"> Morgan Stanley saying &amp;quot;Bear Market Rally is now Over&amp;quot; -- I guess we will find out a Week from now if it was true $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:34:12 </td>
   <td style="text-align:left;"> $SPY Futes are wet 😎💃🕺🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:34:10 </td>
   <td style="text-align:left;"> $SPY SPY 2022-04-04 Daily Forecast Video: 
https://www.youtube.com/watch?v=-399P6zNqgQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:34:07 </td>
   <td style="text-align:left;"> $SPY NEW ARTICLE : Inversion Panic Is A False-Flag https://www.stck.pro/news/SPY/25631430 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:33:37 </td>
   <td style="text-align:left;"> $SPY Lowest trading volume day of the year (since Dec 2021). No biggie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:33:34 </td>
   <td style="text-align:left;"> $SPY Never believe MEDIA about what’s happening .. even BUCHA news it’s FAKE NEWS

https://mobile.twitter.com/mtracey/status/1510696054064398339?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1510696054064398339%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fwww.infowars.com%2F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:32:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $USO $UNG  I ain&amp;#39;t turning my Ac this summer  no matter how 🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:32:32 </td>
   <td style="text-align:left;"> $SPY looks like Courtney huh b @blancobull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:32:28 </td>
   <td style="text-align:left;"> $SPY I don’t think we are going much higher without another dovish interest rate hike by the FED. We might trade sideways until we find out the new CPI data. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:32:14 </td>
   <td style="text-align:left;"> $SPY Gosh, so many people here post so much uneducated futility fillers around here that provides no substantial value.  
 
What good has come about by referencing and dissecting an elaborate amount of nonessential data? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:32:10 </td>
   <td style="text-align:left;"> $SPY lol this &amp;quot; market &amp;quot;  has been destroyed and lost all credibility , we all know it ....pretty sad 😥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:32:09 </td>
   <td style="text-align:left;"> $SPY ayoooo wtf everybody Bitches and moans daily about dwac and now shits down 50% no wonder nobody talks about it anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:32:04 </td>
   <td style="text-align:left;"> $AMZN Ok yes it was amazon, had 82% of profits last quater from rivian stake. So that means this quarter with rivian plummet, they are going to have the biggest loss in company history $AAPL $NVDA $SPY $UBER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:31:59 </td>
   <td style="text-align:left;"> $SPY markets left me with no gamble here I hate that I love gambling lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:31:48 </td>
   <td style="text-align:left;"> $SPY If I had to pick Food pickers and producers over sick care system. I am eating sorry bout your sick care luck. Learn how to stay away from mcdys, hot pockets, and stop asking the strong to die for the weak. That sounds ignorant and bearish AF. Bullish AF is the way! THe less evolved are less evolved for a reason. Get evolved BTFD! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:31:40 </td>
   <td style="text-align:left;"> $SPY we don’t need to print the internet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:31:24 </td>
   <td style="text-align:left;"> $SPY I mean who wouldn’t wanna right b? @PurpleReign8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:31:20 </td>
   <td style="text-align:left;"> $SPY cold war 2.0 China and Russia are besties while India wants to play neutral like the US was in WW2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:31:15 </td>
   <td style="text-align:left;"> $SPY 

It’s looking pretty bad out there. When you crush the consumer, you crush the economy. That’s how it works in the consumption slash credit slash debt economy.  Protect your gains! 

https://twitter.com/DiMartinoBooth/status/1511018051193483276?s=20&amp;amp;t=_mgK7ZxrqXMCbYFwf7DYBg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:30:39 </td>
   <td style="text-align:left;"> $QQQ $SPY https://www.cnbc.com/2022/04/04/bear-market-rally-setting-stage-for-correction-morgan-stanley-warns.html?utm_term=Autofeed&amp;amp;utm_medium=Social&amp;amp;utm_content=Main&amp;amp;utm_source=Twitter#Echobox=1649117387 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:30:34 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m 26. Broke. In need of recyclable cans. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:30:00 </td>
   <td style="text-align:left;"> $SPY $DIA  Can you believe North Korea just thread in South Korea said if South Korea in Vegas North Korea gonna blow him up with a nuclear attack.   Wtf. $SPX $QQQ  

North Korean nuclear on South Korea 😂

Funny right when I hear word Nuclear I always thought Vix $VIX  huge gap up 
And spy a huge gap down. 

How things have changed in our life’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:29:35 </td>
   <td style="text-align:left;"> $SPY Look at me. You’re the captain now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:29:32 </td>
   <td style="text-align:left;"> $SPY my God what I&amp;#39;d give to be yalls age agian..again... especially knowing what I&amp;#39;ve learned...lucky Fs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:29:21 </td>
   <td style="text-align:left;"> $SPY Was it not $AMZN or google that had 84% of their quartley profits from rivian stake?? that means their base business models not all that great, and how bad are their earnings going to be with rivian plummenting? who can remind me which company it is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:29:11 </td>
   <td style="text-align:left;"> $SPY the people who are LITTERED in the streets of BUCHA are Russia sympathizers that got shot by AZOV Nazi Ukrainian battalions … they all wearing white bands and not blue 

https://mobile.twitter.com/RWApodcast/status/1510635133627514881?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1510635133627514881%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fwww.infowars.com%2F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:28:59 </td>
   <td style="text-align:left;"> $SPY Elon really buying twitter? Whatre the implications? What do I short? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:28:28 </td>
   <td style="text-align:left;"> $SPY holiday in hong kong national day ,es flat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:28:16 </td>
   <td style="text-align:left;"> $SPY end of globalization is bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:28:08 </td>
   <td style="text-align:left;"> $SPY Probably going to retire in June and just do consulting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:28:04 </td>
   <td style="text-align:left;"> $SPY congrats Hungary . U do u 👍and what happens? People vote for what makes sense (I’m not Hungarian love goulash tho) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:28:00 </td>
   <td style="text-align:left;"> $SPY steak or salmon every night cause Arnold told me to 
(Actually not that expensive either) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:27:54 </td>
   <td style="text-align:left;"> $TWTR instead of $DWAC we can support this full heartedly 

Let&amp;#39;s go Brandon 

$SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:27:42 </td>
   <td style="text-align:left;"> $SPY Kanas will win the NCAA National championship game. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:27:28 </td>
   <td style="text-align:left;"> $SPY New rule... if you rush the stage at a public event like the Oscars or a Chris Rock comedy show, you&amp;#39;re asking to get knocked out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:27:07 </td>
   <td style="text-align:left;"> $SPY Tesla without bitcoin or other investments is probably still unprofitable. Just two years ago they were still losing almost 10K per car. I don&amp;#39;t doubt costs for those cars have skyrocked in the last two years to say the least $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:26:04 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $AMZN $MSFT 

My thoughts on today&amp;#39;s mkt .... 

My Game Plan sent out Sunday morning focused on preparing for the coming earnings season and getting positioned in what I believe will be the winners and trying to avoid the losers. GOOGL is one name I wrote about as a stock I really like into earnings.

Tonight I&amp;#39;m sending out a blog to members titled &amp;quot;The Three Little Pigs&amp;quot;, where I break down three different tiers of tech/growth stocks, over 20 names. 

Which are in the brick house (strongest)  heading into earnings, and which reside in the other two houses.

For those yet to sign up, feel free to email me at jessielivermore1929@gmail.com 

?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:25:46 </td>
   <td style="text-align:left;"> $SPY futes creamin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:25:34 </td>
   <td style="text-align:left;"> $SPY everything is fine now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:25:30 </td>
   <td style="text-align:left;"> $SPY Muke Wilson and rhe rest of $MS  will make sure you are good and poor from expired puts before they actually pull money from the market. Don&amp;#39;t short 0DTE based on his &amp;quot;wisdom&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:24:50 </td>
   <td style="text-align:left;"> $SPY THere is nothing special about essential workers. You signed up for it stop whining. You are not more special then the fruit picker. Get over yourselves! LMA! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:24:48 </td>
   <td style="text-align:left;"> $SPY For real, going back to work in an office is a pay cut due to gas.  
 
Of I ran a company, I’d love to push all of my real estate, office supply, utilities, tech support, etc onto my employees by having them work from home. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:24:39 </td>
   <td style="text-align:left;"> $SPY we can do better..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:24:32 </td>
   <td style="text-align:left;"> $SPY we must work together..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:24:23 </td>
   <td style="text-align:left;"> $SPY Learn something new every day. 
 
Benjamin Franklin invented the Armonica.  Frank Zappa would have approved I am sure... 
 
https://www.youtube.com/watch?v=eEKlRUvk9zc&amp;amp;ab_channel=TorontoStar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:23:48 </td>
   <td style="text-align:left;"> $SPY BUCHA massacre is FAKE NEWS not even NEW YORK times can confirm it 

No mention of atrocities when they entered … but when AZOV Nazis enter “oh there are bodies everywhere “ 

https://mobile.twitter.com/MoonofA/status/1510635534321860611?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1510635534321860611%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fwww.infowars.com%2F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:23:47 </td>
   <td style="text-align:left;"> $SPY ODTE calls literally free money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:23:31 </td>
   <td style="text-align:left;"> $SPY No doubt in my mind Putin got one of those bad Russian Covid vaccines…He’s gone Full Retard lately… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:22:44 </td>
   <td style="text-align:left;"> $SPY I will never stop compounding blunts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:22:38 </td>
   <td style="text-align:left;"> $SPY magic green/EV stonks up again, works like a charm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:22:38 </td>
   <td style="text-align:left;"> $SPY 04:16: US TREASURY: RUSSIA WILL NOT BE ALLOWED TO PAY ITS BONDS WITH CASH IN US BANKS., 05.04.22
Not good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:22:28 </td>
   <td style="text-align:left;"> $SPY 

The moments TWOWS lives for❤️❤️❤️
Nothing beats helping a common man✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:22:19 </td>
   <td style="text-align:left;"> $SPY All that you need to know…, Shorts haven&amp;#39;t covered a single share,,, amazingchat.stockmarketsignal.online </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:22:05 </td>
   <td style="text-align:left;"> $SPY leftover tacos and Kansas,  for the W... btw il nothing about basketball...football season we gucci </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:21:01 </td>
   <td style="text-align:left;"> $SPY Wage slaves need to get back to the office to support commercial real estate and blow money on chicken fingers. 
 
I’m so glad I found a company that lets me work at home. I left the old company when they said they wanted me back in the office and now work for their competitor with more pay and work from home. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:20:48 </td>
   <td style="text-align:left;"> $SPY 
Rah, Rah Carolina-lina! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:20:45 </td>
   <td style="text-align:left;"> $XBI Relative outperformance wrt $SPY : </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:20:19 </td>
   <td style="text-align:left;"> $SPY News is getting stale af. I’ve heard enough about Ukraine and celebrities slapping each other. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:20:10 </td>
   <td style="text-align:left;"> $SPY my nuts are hung out. Bulls only have hopes and dreams. Fundamentals &amp;amp; technicals of this market says LOWER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:20:05 </td>
   <td style="text-align:left;"> $SPY When I dont print I eat cup noodles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:19:09 </td>
   <td style="text-align:left;"> $SPY Bulls this is your captain speaking. Time to return me to my ship ATH! https://www.youtube.com/watch?v=7fryGyqTJPU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:19:03 </td>
   <td style="text-align:left;"> $UVXY alerted to throw some cash here for the inevitable rug pull on this small market run. 

- $SPY had some great option scalps here and on $AMD today as well!

Still holding some $AMC shares. Couldn’t help it, gotta have fun sometimes!

Group recap below!!

Thanks for everyone who’s been joining, thankful for you all!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:19:00 </td>
   <td style="text-align:left;"> $SPY When I print I still get ramen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:18:53 </td>
   <td style="text-align:left;"> $SPY range bound. Now we go down. May be annoying and take a couple days but it should stay within 460-420 over this month and next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:18:52 </td>
   <td style="text-align:left;"> $SPY nobody workin anymore? Everyone just “trading” now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:18:15 </td>
   <td style="text-align:left;"> $SPY Dang we will elect a new president before this game starts! Let’s tip it off! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:17:56 </td>
   <td style="text-align:left;"> $SPY got letter from supplier today citing Ukraine and Russia raw materials disruptions causing another 8% hike on the 25th, third price hike in 4 months. Fuck me, at least got $spy calls for tomorrow to cover losses. Love selling fixed bids with variable inputs. Can’t go wrong….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:17:55 </td>
   <td style="text-align:left;"> $SPY Inflation makes me stay at home more than the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:17:51 </td>
   <td style="text-align:left;"> $SPY in a perfect world ( market) this would be at 420 already .  Will get there very soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:17:46 </td>
   <td style="text-align:left;"> $SPY $QQQ 
UNC better hope Kansas doesn’t shoot like they did in the first half of the semis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:17:22 </td>
   <td style="text-align:left;"> $DOGE.X $SPY $ATER    ~Best-room on the net!! I&amp;#39;ve made over 35K by their alerts..   most-winning-chatroom.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:17:14 </td>
   <td style="text-align:left;"> $SPY if i see another butterfly or diamond pattern from a bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:17:02 </td>
   <td style="text-align:left;"> $SPY 5200 more a year in inflation costs to average family. No joke America is in deep shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:16:49 </td>
   <td style="text-align:left;"> $SPY Time to go long oil 
Calls for the sanctions to target Russian energy exports — on which the EU heavily depends — have grown louder. In Italy, one of the EU countries most reliant on Russian gas, Enrico Letta, chief of the centre-left Democratic party, a junior partner in prime minister Mario Draghi’s national unity government, called for a “full oil and gas Russia embargo”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:16:39 </td>
   <td style="text-align:left;"> $SPY Went grocery shopping, threw items in my cart, checked the price and put them back on the shelf.  This will hurt companies bottom line so can&amp;#39;t wait for earnings!🤣😂🤣😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:16:36 </td>
   <td style="text-align:left;"> $SPY national championship game is going to be all Jayhswks. 

-4.5 KU ? Wow. That&amp;#39;s a bet to grab.

Almost as much of a sure thing as SPY deep diving tomorrow. 

Take KU , also bet on center McCormack to hit #s. 

Imo, hurry, 5 minutes to online thar bet $DKNG $CZR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:16:35 </td>
   <td style="text-align:left;"> $SPY same level where we got rejected twice feb-mar. There&amp;#39;s actually a chance we may revisit 440 soon.  Not to mention we had a freaky low volume day today. Compare that to other times when volume was significantly lower than avg... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:16:30 </td>
   <td style="text-align:left;"> $SPY Market flows from balance to imbalance in both directions.  Most of us have heard and know this, but now I have an indicator to prove it.  Here it is on $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:16:26 </td>
   <td style="text-align:left;"> $SPY yesir opens over 461 and runs to 465 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:16:22 </td>
   <td style="text-align:left;"> $SPY Prepare to have insane cooling costs this summer -- yall dont wanna chill on corporate waste, so gonna have to pump electric plants and make it worse to stay cool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:16:11 </td>
   <td style="text-align:left;"> $SPY $QQQ
Mardi Gras version of the National Anthem just didn’t work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:16:01 </td>
   <td style="text-align:left;"> $SPY Everytime an analyst says the Bear Market Rally is over, it shoots up 1 to 2 percent. If you&amp;#39;re bearish, probably wait until everyone is screaming buy before you short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:15:41 </td>
   <td style="text-align:left;"> $SPY IS THE VIX DOWN AGAIN ??????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:15:11 </td>
   <td style="text-align:left;"> $SPY Spy is higher than me rn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:14:39 </td>
   <td style="text-align:left;"> $SPY you know when you get an extra thick gummie it’s going to be a good night... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:13:32 </td>
   <td style="text-align:left;"> $SPY   
 
US SENATE MAJORITY LEADER SCHUMER: WE WANT ANOTHER SPENDING BILL FOR COVID AND UKRAINE. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:13:23 </td>
   <td style="text-align:left;"> $SPY With all of the talk about who is ALLOWED to weigh-in with their opinions about the Will Smith Chris Rock Oscars SLAP, I&amp;#39;ve decided that it is an issue to be discussed by MEN ONLY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:13:16 </td>
   <td style="text-align:left;"> $SPY if this doesn&amp;#39;t go down tomorrow I&amp;#39;ll do what&amp;#39;s right and post my mother in law&amp;#39;s phone number for people to complain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:13:07 </td>
   <td style="text-align:left;"> $SPY just sucks all the big dips are over with..no more cheap shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:13:04 </td>
   <td style="text-align:left;"> $SPY im addicted to.gambling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:12:56 </td>
   <td style="text-align:left;"> $SPY EuroZone is in a recession., we were saying they were teetering a few months ago.. and things have worsened quite quickly there since,, we believe china growth may not be all that true $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:12:47 </td>
   <td style="text-align:left;"> $SPY  sleepy tard to save a few Pennie’s with oil reserves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:12:23 </td>
   <td style="text-align:left;"> $SPY $BAC $JPM $MS $WFG what&amp;#39;s critical in inverted interest is 3month yield. We still have plenty of room there. Market is looking for a opening and ready to blow out. We going to see huge upside within this week. JPM CEO already fired a shot. 
Difference between financial hub like MS and conventional banking like BAC is going to be very clear soon. Hubs like MS are very agressive and prone to market   , where BAC conventional banking is strong with YOY growth with adaptation and ground base. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:12:15 </td>
   <td style="text-align:left;"> $SPY HOW LONG WILL THIS FLATLINE LAST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:12:12 </td>
   <td style="text-align:left;"> $SPY just fcking pump it already ffs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:12:08 </td>
   <td style="text-align:left;"> $SPY So  someone needs a $15  soap box and stocks go up ? And I&amp;#39;ve heard that a new EV battery costs more then the car ? Just like Gas ⛽️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:12:07 </td>
   <td style="text-align:left;"> $SPY Buckle up!! ⏳️📉🔥🐻
https://www.google.com/amp/s/www.businessinsider.com/russian-oligarch-says-next-steps-putin-invasion-of-baltic-countries-2022-4%3famp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:11:49 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $DJIA $QQQ  
 
War Criminal states accuse other War Criminal states of War Crimes. 
 
The human virus has grown out of control. Hopefully God will send a 100-mile wide asteroid this way to correct his mistake and eliminate this virus from the Universe before Musk and Bezos establish colonies on other planets.     
 
https://www.usatoday.com/story/news/politics/2022/04/04/ukraine-russia-invasion-live-updates/7265726001/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:11:37 </td>
   <td style="text-align:left;"> $SPY 
https://www.brecorder.com/news/40165057/japans-nikkei-falls-as-chip-shares-track-us-peers-lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:10:47 </td>
   <td style="text-align:left;"> $SPY  Bloomberg : Prices causing factory closures, half time working, even, energy shutting down factories and industrial manufacturing production.

Could be a fun one tomorrow, that PMI, you don&amp;#39;t think it could shock do you with running things up like you did today, bulls, noooo.

OH, even crazy  lithium prices causing probs for electric cars . Nothing&amp;#39;s insulated.  Shanghai is a something that will bring news every day shut down now. $LCID $GM

Tesla ER 20th should be a good one, for 777 ,  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:10:18 </td>
   <td style="text-align:left;"> $SPY When it comes to the war with Russia, WE IN THE WEST will fight to the LAST UKRAINIAN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:10:12 </td>
   <td style="text-align:left;"> $SPY I’m dedicating this gummie I’m about to munch to @LadyAmalthea12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:09:36 </td>
   <td style="text-align:left;"> $BRQS anyone use this at work? $AMZN $UPS $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:08:41 </td>
   <td style="text-align:left;"> $SPY S to the G </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:08:33 </td>
   <td style="text-align:left;"> $SPY last time when volume dried up on the rally...STUDY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:08:24 </td>
   <td style="text-align:left;"> $SPY A complete disgrace </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:08:13 </td>
   <td style="text-align:left;"> $SPY how does Hunter show his face in public after those videos? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:08:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB $GREE $AAPL  very motivational day in 
the 1 on 1’s playbook channel. Both plays went green if you scalped that’s beautiful I’m still holding on to a bunch ✅🏦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:07:57 </td>
   <td style="text-align:left;"> $SPY Japaneese boomers hoping to get 5c on the dollar inflation adjusted on their Nikkei investment from 1989. True story </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:07:27 </td>
   <td style="text-align:left;"> $SPY I hate it when bears worthless  puts make the board smell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:07:16 </td>
   <td style="text-align:left;"> $SPY Bears be smarter than the bulls,, start short selling not buying puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:07:14 </td>
   <td style="text-align:left;"> $SPY bro these futures are bullish asf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:06:49 </td>
   <td style="text-align:left;"> $SPY Yay! Nikkei! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:06:41 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:06:38 </td>
   <td style="text-align:left;"> $SPY unc getting the dub tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:06:24 </td>
   <td style="text-align:left;"> $SPY getting ready for the over night “fook you moo 🐮 pump” 😆 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:06:16 </td>
   <td style="text-align:left;"> $SPY Bucha massacre is fake news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:06:12 </td>
   <td style="text-align:left;"> $SPY?
 https://www.bitchute.com/video/lisdstePPaX7/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:05:52 </td>
   <td style="text-align:left;"> $SPY need a nuke please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:05:46 </td>
   <td style="text-align:left;"> $SPY so is Hunter Biden on video doing sex acts with underage women </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:05:40 </td>
   <td style="text-align:left;"> $SPY Japanese stock market right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:05:15 </td>
   <td style="text-align:left;"> $SPY 4 more hours. Fed pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:05:10 </td>
   <td style="text-align:left;"> $JMIA Destroy my puts please , I’m tired of winning. 🥷 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:05:05 </td>
   <td style="text-align:left;"> $SPY that $425-$437 zone at the neckline on the weekly chart is going to fill eventually, that I&amp;#39;m confident in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:05:03 </td>
   <td style="text-align:left;"> $SPY only thing this world understands is violence.....Def a V shaped recovery again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:05:01 </td>
   <td style="text-align:left;"> $SPY would there be any interest out there in seeing my portfolio? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:04:36 </td>
   <td style="text-align:left;"> $SPY Japan down 1.6% already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:04:31 </td>
   <td style="text-align:left;"> $SPY 

Gotta love these moments in my Small Account Challenge discord!❤️❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:04:04 </td>
   <td style="text-align:left;"> $ES_F: Defended 100 sma this morning and was able to power through 4560 resistance. The next big level to watch is 4580. We broke above this last week but then sold off the next 2 days. Expect some consolidation under 4580. As long as we hold 4540, these are buyable dips.  
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:03:46 </td>
   <td style="text-align:left;"> $SPY IT WOULD BE FUNNY  ,IF OUR MARKETS WOULD  DO THE SAME AS NIKKEI A COMPLETE REVERSAL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:03:34 </td>
   <td style="text-align:left;"> WE ARE NOW LIVE.🔥 #PRESSIT  
⚔️TRADE IDEAS LIVE STREAM  
👉IM GOING TO BREAK DOWN👇 
📈TRADE IDEAS 
🔫TRIGGERS  
🎯TARGETS  
🐲DRAGONS 
🌊FLOW  
💯SECTORS  
CLICK&amp;gt; https://us02web.zoom.us/j/87240523612 $SPY  $QQQ  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:03:30 </td>
   <td style="text-align:left;"> $SPY 

Lol

https://youtu.be/NwSVK2YmY5I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:03:18 </td>
   <td style="text-align:left;"> $SPY Good Luck with that !! 😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:03:15 </td>
   <td style="text-align:left;"> $spy So not only do they have the Angry racist like @PonySoldier buying  $DWAC but he thinks that Elon is on his team 😂 
 
Ok folks, dont tell him about the share price, he may have missed what happened today  
 
&amp;amp; people say the Cult are stupid, :o) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:03:09 </td>
   <td style="text-align:left;"> $SPY SPY $400 will be a balance trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:02:58 </td>
   <td style="text-align:left;"> $TWTR $TSLA $MULN $AMC $SPY 

In 1 hour I will be selecting the 10 winners. May God be with you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:02:15 </td>
   <td style="text-align:left;"> $SPY bears are coming out of hibernation with vengeance, the elevator cable might just snap and you will buy the shaft. Patience is the key…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:02:13 </td>
   <td style="text-align:left;"> $SPY so much for this imbecile and releasing oil reserves the price is going up .  The stupidity of this administration </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:01:55 </td>
   <td style="text-align:left;"> $SPY hope nasdaq down 500 points tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:01:27 </td>
   <td style="text-align:left;"> What do you prefer to live alone or live with others/family ? Sometimes you can live with others and still feel alone $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:00:59 </td>
   <td style="text-align:left;"> $SPY https://www.bitchute.com/video/lisdstePPaX7/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:00:53 </td>
   <td style="text-align:left;"> $SPY FUTURES READY like come on straight up from here you cannot miss it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:00:44 </td>
   <td style="text-align:left;"> $SPY heading much lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:00:35 </td>
   <td style="text-align:left;"> $SPY giving dummy’s a bad name since 2021 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:00:01 </td>
   <td style="text-align:left;"> $SPY If you are getting excited or upset on every trade then you are doing it wrong.....remain calm and have confidence in your strategy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 09:00:00 </td>
   <td style="text-align:left;"> $SPY tornadoes are bearish @FatmanEnterprises @hi_im_bruh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:59:58 </td>
   <td style="text-align:left;"> $SPY who&amp;#39;s ready for when that deadline needs to be met on mpg and they enact a way to tax vehicles that dont meet threshold and force people to switch. That&amp;#39;s the good ol Democrat way.... if they don&amp;#39;t comply you force it down throats till it is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:59:26 </td>
   <td style="text-align:left;"> $SPY hate that i.missed my short would of had a good scalp now I gotta sit and wait for next gamble 🎰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:59:04 </td>
   <td style="text-align:left;"> $SPY dang Nikkei just dumped 1%. Why? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:58:21 </td>
   <td style="text-align:left;"> $SPY WOW Is it just me or does everyone love shitting on bears now 

They are desperate at this point 1 by 1 squeezed. I can’t wait for tomorrow 
I can foresee many possible trades and it just so turns out THE DIP WAS A BUY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:57:37 </td>
   <td style="text-align:left;"> $SPY does anyone find the subscription to Bloomberg useful? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:57:29 </td>
   <td style="text-align:left;"> $SPY Dow futures yet to drop another 867 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:56:24 </td>
   <td style="text-align:left;"> S&amp;amp;P Futures 
4,572.25 
-5.50(-0.12%) 
Dow Futures 
34,779.00 
-50.00(-0.14%) 
Nasdaq Futures 
15,150.00 
-14.25(-0.09%) 
Russell 2000 Futures 
2,090.90 
-3.70(-0.18%) 
 
On the close Monday 
DJIA 
34921.88 
103.61 
0.30% 
NASDAQ 
14532.55 
271.05 
1.90% 
S&amp;amp;P 500 
4582.64 
36.78 
0.81% 
 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:55:38 </td>
   <td style="text-align:left;"> $SPY Nikkei taking a massive dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:55:37 </td>
   <td style="text-align:left;"> $SPY $qqq making money shorting last quarter was super hard even though successful. Shorting is rocket science. 
But now we make easy money for months. Just btd. Every dip. There will be a small correction at ath. Then we have a massive breakout after breakout </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:54:33 </td>
   <td style="text-align:left;"> On the close Monday 
DJI 
34921.88 
103.61 
0.30% 
NASDAQ 
14532.55 
271.05 
1.90% 
S&amp;amp;P 500 
4582.64 
36.78 
0.81% 
 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:54:31 </td>
   <td style="text-align:left;"> $spy So $dwac is the only stock where you can be shorting since $102 &amp;amp; get people asking how is your lost going? I mean wow,  
 
Takes a special kind of person who didn&amp;#39;t sell at $180 &amp;amp; then again at $102 a few weeks ago to asl Bears how they&amp;#39;re doing, what kind of person? a Trump person 
 
https://www.rollingstone.com/politics/politics-news/truth-social-trump-app-bombing-executives-quitting-1332552/ 
 
$twtr $fb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:54:29 </td>
   <td style="text-align:left;"> $SPY  it’s not real pump until $5+ overnight then erase all gains on strange foreign Fud 🔥✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:53:27 </td>
   <td style="text-align:left;"> $SPY any reverse splits here ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:52:28 </td>
   <td style="text-align:left;"> $SPY “You can achieve a lot if you are smart, but if you don’t have a good heart you won’t last very long.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:52:20 </td>
   <td style="text-align:left;"> Bear market rally $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:51:56 </td>
   <td style="text-align:left;"> $SPY do you realize that if all of your lines, patterns, indicator and brouhaha were bulletproof; everyone would be FILTHY RICH by now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:51:36 </td>
   <td style="text-align:left;"> $QQQ $spy seems like a massive rug pull tomorrow. I cannot believe how they played us all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:50:45 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR $DWAC $CFVI 

Yes sir! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:50:30 </td>
   <td style="text-align:left;"> $SPY are we dead yet bears? Can&amp;#39;t see how we aren&amp;#39;t after this Monday. R.I.P. bear market of 2022. Lasted a whopping month if that lol. You can&amp;#39;t convince me to start going long now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:50:26 </td>
   <td style="text-align:left;"> $SPY you wanna come to paradise? Matter of fact, you wanna come to pluto? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:50:03 </td>
   <td style="text-align:left;"> $SPY We are grinding (not roaring) toward a bear market .

That&amp;#39;s it, that&amp;#39;s the tweet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:49:22 </td>
   <td style="text-align:left;"> $SPY this might be a bearish diamond pattern. Oh shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:48:59 </td>
   <td style="text-align:left;"> $SPY just need patience. It will drop below 400

Sample pattern </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:48:38 </td>
   <td style="text-align:left;"> $SPY  SUCH BULLIES Literally affecting US companies to try to lower the exchange rate for the Ruble smfh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:48:34 </td>
   <td style="text-align:left;"> $SPY let’s see if we can break 460 if we get rejected I’m going bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:48:12 </td>
   <td style="text-align:left;"> $SPY i don&amp;#39;t see this falling bellow $400 tbh. We&amp;#39;ve entered bearish territory yet we&amp;#39;re still pumping away towards ATH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:47:38 </td>
   <td style="text-align:left;"> $SPY meanwhile in UK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:47:18 </td>
   <td style="text-align:left;"> $SPY $TWTR I think Elon is gonna take over Twitter fully within couple years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:47:05 </td>
   <td style="text-align:left;"> $CROX @JRTRADER23 ...You want a Bullish perspective....🤷‍♂️ I hate to say it because Crocs was one of the most overblown stock of this entire pump market but if it can get back over the red line this is a good formation building strength support after quite the retracement and gap fill....And at this level it is holding a major support area.... If that strength support breaks though it will go down even further but this is something to keep an eye on 🍀 $SPY $SCVL $NKE 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:47:02 </td>
   <td style="text-align:left;"> $SPY hope they don’t jerk my calls before I roll over to puts mañana my street wisdom tells me we get smidge of green tomorrow before lobby meeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:46:24 </td>
   <td style="text-align:left;"> $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:45:33 </td>
   <td style="text-align:left;"> $SPY anything after hitting $400 only </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:44:57 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR Welp, the T &amp;#39;n T explosive pump from Musk is vamos, back tomorrow to our regularly scheduled bear market rally killer.

Like I keep saying, &amp;quot;449.14 to 404.&amp;quot; It is happening, 460 is not happening in this climate, vice turns more and more, even, a twirl or two, as we squeeze Jamie Dimon &amp;amp; (bullish) banks company toward bad guidance for Q2, as they report next week &amp;amp; we&amp;#39;re 404 day before CPI, 11th, 1st day banks report, not so coincidentally.

And, when banks ho, everything goes. $IWM 

Do own DD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:44:28 </td>
   <td style="text-align:left;"> $SPY Looks bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:44:03 </td>
   <td style="text-align:left;"> $SPY ONE PERCENT GREEN TMRW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:43:57 </td>
   <td style="text-align:left;"> $SPY Just chill and wait for the right trades.... https://youtu.be/T3g9QUT_oP0?list=RDyoRpWEE-E0Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:43:30 </td>
   <td style="text-align:left;"> $SPY $SPX when the ALGOMUS SAYS, you must DO!  Its the ALGOMUS WAY! 04/01 dip buy to target 4575 completed 1 day.  Next stop 4518 then 4480, 10 day timeframe! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:43:16 </td>
   <td style="text-align:left;"> $SPY CALLS CALLS CALLS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:42:49 </td>
   <td style="text-align:left;"> $SPY all news is bullish!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:42:47 </td>
   <td style="text-align:left;"> $SPY. Fed president Harker right before FOMC mins. Pump up before the minutes??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:42:19 </td>
   <td style="text-align:left;"> $SPY spring break special $10/gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:41:38 </td>
   <td style="text-align:left;"> $SPY stock analysis based on today&amp;#39;s closing price 

https://youtu.be/r3jy0agFJZY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:41:18 </td>
   <td style="text-align:left;"> $SPY $AMC Good times 🥲😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:41:00 </td>
   <td style="text-align:left;"> $TSLA $SPY Shitting on bears like $NIO shits on its share holders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:40:49 </td>
   <td style="text-align:left;"> $IMPP  👈ripping. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:40:32 </td>
   <td style="text-align:left;"> $spy who do British people have such fucked up teeth? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:40:12 </td>
   <td style="text-align:left;"> Stay focused on your goals $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:40:04 </td>
   <td style="text-align:left;"> $SPY omg bears are y&amp;#39;all crazy or what lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:40:03 </td>
   <td style="text-align:left;"> $SPY bears are just so stupid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:40:02 </td>
   <td style="text-align:left;"> $SPY 50y mortgage coming, better buy your house early so you can pay it off before your kids die </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:39:28 </td>
   <td style="text-align:left;"> $TSLA $SPY shitting on bears all day everyday day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:39:14 </td>
   <td style="text-align:left;"> $SPY What fking economics  is this?  News of Supply Crude Oil Millions of barrels added yet it keeps going up  for new supply risk news 
 
 
I dont fking get it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:39:03 </td>
   <td style="text-align:left;"> $SPY This market is like watching Howard Stern make fun of people that don&amp;#39;t know any better. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:38:56 </td>
   <td style="text-align:left;"> $SPY $TWTR $TSLA  I&amp;#39;m coining the term &amp;quot;eshlong&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:37:38 </td>
   <td style="text-align:left;"> $SPY Computer driven &amp;#39;trading&amp;#39;.....LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:35:04 </td>
   <td style="text-align:left;"> $SPY jesus Elon really pumped the market ... props to him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:34:57 </td>
   <td style="text-align:left;"> $DIS this is how it works - you need new buyers to make the stock go up - if you zoom out 📉 those sure aren’t buyers and you clowns 🤡 now think with all this it’s still going back up 📈🤔😂😂😂😂😂😂😂😂😂 better sell your friends and family on pedo programming $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:34:17 </td>
   <td style="text-align:left;"> $SPY $qqq buy everything. We are pumping it to ath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:34:07 </td>
   <td style="text-align:left;"> $SPY $QQQ - hate it each week seems something holding this off 
 
from CPI, FED MINUTES and all the BS!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:33:27 </td>
   <td style="text-align:left;"> $SPY looks like nikkei might’ve bottomed around 27780 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:33:19 </td>
   <td style="text-align:left;"> $SPY 🖨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:33:09 </td>
   <td style="text-align:left;"> $SPY I AM GLAD WE DONT FOLLOW NIKKEI ON DOWN MOVES  
ONLY UP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:33:02 </td>
   <td style="text-align:left;"> $SPY does anyone have anything constructive and positive to say on here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:32:29 </td>
   <td style="text-align:left;"> $SPY everyone into gold, fine art, and land. The dollar is worthless and becomingnless so. Printing money doesn&amp;#39;t come without consequences. Why do you think there&amp;#39;s no housing inventory and the hedge funds own 1/7 of all single family homes. Wealth protection. Stocks not so much in the future. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:32:27 </td>
   <td style="text-align:left;"> $SPY  $TSLA  theres one thing these markets reward its persistence. Gotta give it to em </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:32:21 </td>
   <td style="text-align:left;"> $SPY Market closed Friday April 15th, only 4 days of trading during the week of CPI...https://www.nasdaq.com/market-activity/2022-stock-market-holiday-calendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:32:10 </td>
   <td style="text-align:left;"> $SPY as long as we don&amp;#39;t gap down past 0.70 I&amp;#39;m good. My buy order is for 0DTE puts that become 0.02 at that price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:32:03 </td>
   <td style="text-align:left;"> $SPY if this has the same % gains it did on March 15, 16, and 17 we will be at 483 by Thursday… not impossible since it just happened less than a month ago, and that ATH will act like a magnet at that point.

Realistic way it could happen: Market reacts to FOMC minutes positively, or the market reacts to some Ukraine war news positively, maybe the marijuana legalization bill could see some action in the senate soon? Who knows… 

Just as likely it could start to tumble, but I am having a hard time finding potential headlines that could lower sentiment beyond like nuclear war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:30:54 </td>
   <td style="text-align:left;"> $SPY everyone keeps saying Asia follows the US yet their week starts before ours. Hmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:30:40 </td>
   <td style="text-align:left;"> $SPY lost so much money with puts that I had to go back to my job at McDonald&amp;#39;s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:30:09 </td>
   <td style="text-align:left;"> $SPY 

I don&amp;#39;t have a dog in the fight but I think it might be the Jayhawks tonight! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:29:21 </td>
   <td style="text-align:left;"> $SPY does anyone know when the next market crash is?  I swear there are some that know but you don’t want to tell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:28:30 </td>
   <td style="text-align:left;"> $SPY $AAPL 

Very clear market faked retail out for the big drop and now ripping to new highs. Stay long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:28:25 </td>
   <td style="text-align:left;"> $SPY   I dont understand when Russia has everything Gas Wheat all the  lesser idiots say  we don&amp;#39;t buy from you  and put sanctions. 
 
 
Is that how economics work ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:28:05 </td>
   <td style="text-align:left;"> $TSLA $SPY $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:27:44 </td>
   <td style="text-align:left;"> $ES_F $SPX $SPY 04/01/22 dip buy to target 4575 has been filled.  Next target is 4518 and 4480 short $ES_F .  ALGOMUS KNOWS ALL! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:27:16 </td>
   <td style="text-align:left;"> $SPY in my humble opinion Powell should really be on trial after literally causing a genocide to bears 🐻 🐻 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:27:06 </td>
   <td style="text-align:left;"> $SPY OHH LOOK NIKKEI IS RALLYING AGAIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:26:32 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s dripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:26:04 </td>
   <td style="text-align:left;"> $SPY here we go again. Nado watch. @poorRichman30 @hi_im_bruh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:26:03 </td>
   <td style="text-align:left;"> $SPY 

Biden Administration says Putin has committed war crimes.  Is this true?   I&amp;#39;m curious. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:26:02 </td>
   <td style="text-align:left;"> $SPY 500 by June? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:25:47 </td>
   <td style="text-align:left;"> $SPY what are Elon and Buffet buying this quarter?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:25:42 </td>
   <td style="text-align:left;"> $TWTR conservatives now
Is the time to flip
Long on this and support Elon. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:25:40 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:25:31 </td>
   <td style="text-align:left;"> $SPY Anyone else in the market for a car right now and completely lost on what to do? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:25:09 </td>
   <td style="text-align:left;"> $DOGE.X $SPY $ATER      ~Best-room on the net!! I&amp;#39;ve made over 35K by their alerts..     most-winning-chatroom.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:25:06 </td>
   <td style="text-align:left;"> $SPY micheal burry back on twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:25:06 </td>
   <td style="text-align:left;"> $DOGE.X $SPY $ATER   ~$1800 into $40k in the last 30 days; If you really want to make huge profits on trading then;  Join this winning chat:.   winning-alerts-options.stockmarketmovers.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:24:31 </td>
   <td style="text-align:left;"> $SPY 

$5k to $650k journey of a TWOWS member!
A moment to be proud of!❤️❤️❤️
All trades verified in my Small Account Challenge discord!✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:24:19 </td>
   <td style="text-align:left;"> $SPY Bears about to get farted on again tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:24:12 </td>
   <td style="text-align:left;"> $SPY What it feels like watching btd bulls getting paid on here 😭😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:24:07 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR $DWAC $CFVI 

This is a PSA: 🚨 

I have a little poem I would love to share with you 

The bulls want a pump 

The bears want a dump 

When you put it all together, you get a thump

And lastly I want to say that I love Donald Trump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:23:39 </td>
   <td style="text-align:left;"> $SPY -3% day tomorrow because I LNOW DA WAE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:23:31 </td>
   <td style="text-align:left;"> Start thinking $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:23:30 </td>
   <td style="text-align:left;"> $SPY can’t wait for the flash crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:23:22 </td>
   <td style="text-align:left;"> $SPY yeah I’m officially in puts now!

https://youtu.be/zRikmXqiMBs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:22:53 </td>
   <td style="text-align:left;"> $SPY  $QQQ  $STUDY Neighbors don&amp;#39;t wave as much when your dog is doing a double-deuce in their front yard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:21:08 </td>
   <td style="text-align:left;"> $SPY what we’re witnessing is the most entitled dereliction of duty by central bankers across the world I have ever seen.  They’re front and center of a monster inflation wave and they absolutely refuse to acknowledge it, even though that’s half of the reason why they even exist.  The corruption is so systemic it’s disturbing me. Seriously </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:21:03 </td>
   <td style="text-align:left;"> $SPY Getting boring, need more FUD 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:20:27 </td>
   <td style="text-align:left;"> $SPY Any tik tok users? A lot of cool stuff on it.  But I clicked on some hot chicks.  Now every other page is some chick trying to get new onky fans clients.   

Had no idea they were only fans chicks lol.  Until I started creeping.  Now it’s like all of them lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:20:24 </td>
   <td style="text-align:left;"> Shanghai $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:20:21 </td>
   <td style="text-align:left;"> $SPY is very much in the middle area in medium time frame.  An area where buyers and sellers are fighting for direction.  We do not like to chase the long side, but prefer to wait for better opportunity lower where buyers can enter further down.       #elliottwave #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:19:27 </td>
   <td style="text-align:left;"> $SPY https://twitter.com/papitrumpo/status/1510442848503488514?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:19:07 </td>
   <td style="text-align:left;"> $SPY Seemed kind of like another bailout today to keep this cornered no exit cartel bid......LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:18:48 </td>
   <td style="text-align:left;"> $SPY #Putin cannot fire even 1 low yielding #nuclearweapon at @NATO territory, no matter if @NATO enters the #RussianUkrainianWar or not. The signs of intimidation in the @WhiteHouse from #PutinNukeThreats is embarrassing and sickening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:18:12 </td>
   <td style="text-align:left;"> $SPY Overall P/L

Etrade account +23.88%
TD account +3.66% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:18:08 </td>
   <td style="text-align:left;"> $SPY can you sell covered calls in a ROTH IRA? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:17:57 </td>
   <td style="text-align:left;"> $SPY the fed sold these kids out so old farts can keep their stocks and home prices up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:17:50 </td>
   <td style="text-align:left;"> $SPY tomorrow 1% down on open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:17:45 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY 

Market doing what It does best. Now that everyone was scared for the drop two weeks ago apple is going to rip to new highs. ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:17:42 </td>
   <td style="text-align:left;"> $SPY four seven zero inside April </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:17:40 </td>
   <td style="text-align:left;"> $SPY Point and laugh at the idiots trying to do $VIX TA! Laugh at them! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:17:09 </td>
   <td style="text-align:left;"> $SPY hate that I missed the short 
I think it will go down to 67 or 68 and the an algo bounce which will drive you nuts if your short and them I&amp;#39;ll short that bounce maybe if it gets back.to 78 80 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:17:04 </td>
   <td style="text-align:left;"> $SPY  this world is going to hell quick. WTF is wrong with people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:16:07 </td>
   <td style="text-align:left;"> $SPY $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:16:02 </td>
   <td style="text-align:left;"> $SPY honestly thought he’d stop but he’s ignoring the Japanese minister of finance.  Incredible does he think he’s untouchable? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:16:02 </td>
   <td style="text-align:left;"> $SPY red futes u know what that means 😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:16:02 </td>
   <td style="text-align:left;"> $SPY just think about it… $1 per company in the S&amp;amp;P… we are literally deep value territory rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:15:51 </td>
   <td style="text-align:left;"> $SPY IM STRAPPED TO THE TITTIES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:15:20 </td>
   <td style="text-align:left;"> Day Trading Watch List Video for April 5th: $SPY $GGPI $GREE $NEGG $LILM 
 
Watch here: https://greatstockpix.com/april-5th-watch-list-video/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:15:08 </td>
   <td style="text-align:left;"> $SPY $QQQ   
 
https://www.dailymail.co.uk/news/article-10391219/JP-Morgan-boss-Jamie-Dimon-says-economy-strong-year.html 
 
Jamie Dimon remains bullish on the US economy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:14:50 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:14:44 </td>
   <td style="text-align:left;"> $SPY I posted a Babylon bee joke about Putin flying planned parenthood flags in Ukraine and someone must have been offended because it got deleted.  Sorry to whoever reported me, it was just a joke! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:14:09 </td>
   <td style="text-align:left;"> $SPY 5 min chart. Just hit a trend line from 3/29 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:14:09 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:14:06 </td>
   <td style="text-align:left;"> $SPY elon bossed up heavy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:13:59 </td>
   <td style="text-align:left;"> $SPY Earnings start next week...... $NDQ $DJIA 
$qqq
I expect 🥶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:13:33 </td>
   <td style="text-align:left;"> $SPY Kids first......and last ride......$TRAN....LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:13:16 </td>
   <td style="text-align:left;"> $SPY got Sunday bear&amp;#39;s kids college fund... comin for the vacation fund next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:13:06 </td>
   <td style="text-align:left;"> $SPY the world is extremely small right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:12:51 </td>
   <td style="text-align:left;"> Trade ideas 💡 unlocked 🚀 $SPY  we will be live soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:12:37 </td>
   <td style="text-align:left;"> $SPY we are rallying to 500 get over it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:12:33 </td>
   <td style="text-align:left;"> $SPY 04/04/22 Price Action Analysis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:11:33 </td>
   <td style="text-align:left;"> $SPY Who ready for the next vix spike </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:10:56 </td>
   <td style="text-align:left;"> $SPY Stocks are double from our peak 2019 economy.. We aren&amp;#39;t in an economy like that anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:10:49 </td>
   <td style="text-align:left;"> $SPY biden releasing 1 million barrels a day is dumb, its just going to speculate oil higher.  Basically just stop fking with it and it’ll go back down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:10:45 </td>
   <td style="text-align:left;"> $SPY does anyone know owning Campbell soup stock is good when shit hits the fan ? I dont wanna own any popular stocks that these losers will hold and be bag holders for years crying at soup lines. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:10:09 </td>
   <td style="text-align:left;"> $SPY Bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:10:03 </td>
   <td style="text-align:left;"> $SPY @NATO and @WhiteHouse think defensive weapons and sanctions will prevent #Putin from committing #Genocide with impunity in #Ukraine. There is clearly a lack of #testosterone in western leadership… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:09:49 </td>
   <td style="text-align:left;"> Once under the 100MA $AMD always has trouble getting back above it being rejected multiple times. The 100MA needs to come down more and AMD should be building momentum, a greater pull back would confirm that. The 100MA should land around 125 before AMD breaks above it heading to 130/150. 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:09:48 </td>
   <td style="text-align:left;"> $SPY 

NYC mayor 

https://nypost.com/2022/04/04/nyc-woman-who-confronted-mayor-adams-on-toddler-mask-mandate-fired-from-city-job/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-05 08:09:23 </td>
   <td style="text-align:left;"> $SPY it’s not the only gap heavy rally but the one on the left had a long period of accumulation that I circled.  The one in the middle eventually sold off.  I almost got margin called out of that one actually.  Thank god it dropped back then.  Now we have the one on the right which is just floating in netherspace thanks to massive yen printing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:37:05 </td>
   <td style="text-align:left;"> $SPY $QQQ why didn’t remy
Martin start? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:34:20 </td>
   <td style="text-align:left;"> Morgan Stanley saying &amp;quot;Bear Market Rally is now Over&amp;quot; -- I guess we will find out a Week from now if it was true $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:32:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $USO $UNG  I ain&amp;#39;t turning my Ac this summer  no matter how 🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:30:39 </td>
   <td style="text-align:left;"> $QQQ $SPY https://www.cnbc.com/2022/04/04/bear-market-rally-setting-stage-for-correction-morgan-stanley-warns.html?utm_term=Autofeed&amp;amp;utm_medium=Social&amp;amp;utm_content=Main&amp;amp;utm_source=Twitter#Echobox=1649117387 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:30:00 </td>
   <td style="text-align:left;"> $SPY $DIA  Can you believe North Korea just thread in South Korea said if South Korea in Vegas North Korea gonna blow him up with a nuclear attack.   Wtf. $SPX $QQQ  

North Korean nuclear on South Korea 😂

Funny right when I hear word Nuclear I always thought Vix $VIX  huge gap up 
And spy a huge gap down. 

How things have changed in our life’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:21:56 </td>
   <td style="text-align:left;"> $QQQ aapl gaps up then sells off and gonna bring this down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:19:44 </td>
   <td style="text-align:left;"> $QQQ time to not pull a will smith and just chill…me in the mirror trying not to capitulate to sellibg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:18:16 </td>
   <td style="text-align:left;"> $QQQ 

1. WS terrified of rate hikes - No longer believe 6 is priced in 

2. Biden wants Putin on trial for War Crimes

3. US warns Russia will now intensify military operations 

Hope you didn’t buy EOD. Right on resistance. GL TO ALL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:17:46 </td>
   <td style="text-align:left;"> $SPY $QQQ 
UNC better hope Kansas doesn’t shoot like they did in the first half of the semis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:16:11 </td>
   <td style="text-align:left;"> $SPY $QQQ
Mardi Gras version of the National Anthem just didn’t work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:12:02 </td>
   <td style="text-align:left;"> $QQQ beartards, this is not 1929, 1999, nor 2007…do you know how big those bubbles were compared to where we are now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:11:49 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $DJIA $QQQ  
 
War Criminal states accuse other War Criminal states of War Crimes. 
 
The human virus has grown out of control. Hopefully God will send a 100-mile wide asteroid this way to correct his mistake and eliminate this virus from the Universe before Musk and Bezos establish colonies on other planets.     
 
https://www.usatoday.com/story/news/politics/2022/04/04/ukraine-russia-invasion-live-updates/7265726001/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:08:37 </td>
   <td style="text-align:left;"> $QQQ getting spicy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:08:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB $GREE $AAPL  very motivational day in 
the 1 on 1’s playbook channel. Both plays went green if you scalped that’s beautiful I’m still holding on to a bunch ✅🏦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:03:53 </td>
   <td style="text-align:left;"> $QQQ People saying to buy the dip. Fact: .30 is not a dip. Maybe 3-4 is a dip after a 7+ / +2% day. Buying right now would be the exact opposite of BTFD.  
 
Market euphoria is making people dumb again and MM&amp;#39;s are about to take that retail money all over again.  
 
How many times do you have to see the same movie to know what the ending is going to be? I know , I know, &amp;quot;scared money don&amp;#39;t make money&amp;quot;, but dumb money doesn&amp;#39;t make money either. 
 
Tomorrow should be entertaining. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 09:03:34 </td>
   <td style="text-align:left;"> WE ARE NOW LIVE.🔥 #PRESSIT  
⚔️TRADE IDEAS LIVE STREAM  
👉IM GOING TO BREAK DOWN👇 
📈TRADE IDEAS 
🔫TRIGGERS  
🎯TARGETS  
🐲DRAGONS 
🌊FLOW  
💯SECTORS  
CLICK&amp;gt; https://us02web.zoom.us/j/87240523612 $SPY  $QQQ  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:55:37 </td>
   <td style="text-align:left;"> $SPY $qqq making money shorting last quarter was super hard even though successful. Shorting is rocket science. 
But now we make easy money for months. Just btd. Every dip. There will be a small correction at ath. Then we have a massive breakout after breakout </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:51:36 </td>
   <td style="text-align:left;"> $QQQ $spy seems like a massive rug pull tomorrow. I cannot believe how they played us all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:43:54 </td>
   <td style="text-align:left;"> $LMT  $NOC  $RTX $QQQ  $BAWe&amp;#39;ve now committed more than $2.3 billion in assistance to Ukraine just since the beginning of this administration. Including more than 1.6 billion since Russia&amp;#39;s invasion. Unlike Presidential Drawdown, USAI is an authority under which the United States procures capabilities from industry rather than delivering equipment that is drawn down from our own stocks. That&amp;#39;s the difference here. So, this announcement represents the beginning of a contracting process that will provide these new capabilities. I would hasten to add that we are going to expedite that contracting process as fast as we can. I don&amp;#39;t have exact delivery or procurement dates today. But rest assured we&amp;#39;re going to be moving at as fast as we can. The U.S. also continues to work with its allies to identify and provide to the Ukrainians additional capabilities. And we&amp;#39;ll certainly utilize all available tools to support Ukraine&amp;#39;s armed forces as they fight bravely for the defense of their country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:42:35 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/eYoCCweFv_g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:40:11 </td>
   <td style="text-align:left;"> $QQQ tech demand </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:35:50 </td>
   <td style="text-align:left;"> $SMH Semis continue to show relative weakness: 
 
$SMH / $QQQ (daily): </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:34:17 </td>
   <td style="text-align:left;"> $SPY $qqq buy everything. We are pumping it to ath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:34:07 </td>
   <td style="text-align:left;"> $SPY $QQQ - hate it each week seems something holding this off 
 
from CPI, FED MINUTES and all the BS!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:31:16 </td>
   <td style="text-align:left;"> $QQQ reminds me of September 2007. Indexes hit new highs. If you old enough to remember what happened following 6 months... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:26:39 </td>
   <td style="text-align:left;"> $QQQ What comes up must come down! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:22:53 </td>
   <td style="text-align:left;"> $SPY  $QQQ  $STUDY Neighbors don&amp;#39;t wave as much when your dog is doing a double-deuce in their front yard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:17:45 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY 

Market doing what It does best. Now that everyone was scared for the drop two weeks ago apple is going to rip to new highs. ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:17:35 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:15:13 </td>
   <td style="text-align:left;"> $QQQ my portfolio is healing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:15:08 </td>
   <td style="text-align:left;"> $SPY $QQQ   
 
https://www.dailymail.co.uk/news/article-10391219/JP-Morgan-boss-Jamie-Dimon-says-economy-strong-year.html 
 
Jamie Dimon remains bullish on the US economy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:13:59 </td>
   <td style="text-align:left;"> $SPY Earnings start next week...... $NDQ $DJIA 
$qqq
I expect 🥶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:09:49 </td>
   <td style="text-align:left;"> Once under the 100MA $AMD always has trouble getting back above it being rejected multiple times. The 100MA needs to come down more and AMD should be building momentum, a greater pull back would confirm that. The 100MA should land around 125 before AMD breaks above it heading to 130/150. 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:09:17 </td>
   <td style="text-align:left;"> $QQQ  $187 during our peak economy in 2019. And yall thinking moon from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:07:23 </td>
   <td style="text-align:left;"> $SPY $SPX $IWM $DJI $QQQ $VIX Market Getting Ready to Make New Highs https://youtu.be/rLcIB5PngRs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 08:05:00 </td>
   <td style="text-align:left;"> Although the technical rating is only medium, $QQQ does present a nice setup opportunity. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:55:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD 
Watch and learn you uneducated swine! 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:54:15 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
 https://www.cnn.com/2022/04/03/politics/obama-biden-white-house-return/index.html 
 
Obama and President Biden are two of the greatest Presidents of all time, great things probably will happen when these two guys work together. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:54:02 </td>
   <td style="text-align:left;"> $SPY $QQQ will this trend continue tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:53:14 </td>
   <td style="text-align:left;"> $QQQ $SPY im the gayest bear you’ll ever meet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:48:26 </td>
   <td style="text-align:left;"> $SPY ...$UVXY $STUDY $AAPL $QQQ 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:47:07 </td>
   <td style="text-align:left;"> $SPY $QQQ We reduced short position again today to reduce risk and be able to be flexible. FANGs look like they can push higher (short term). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:44:47 </td>
   <td style="text-align:left;"> Watch list for tomorrow part 2: $FB $QQQ $IWM $FUBO $THCA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:44:10 </td>
   <td style="text-align:left;"> $QQQ I can totally understand big tech and companies with accelerating growth moving the markets higher but all these companies that are over valued and losing millions every year continuing to climb is just the most disturbing thing of all. This market is an everything rally and not about stock picking at this point. Companies are losing billions and under performing they own projections and yet money continues to flow in. It’s really the worse part of it all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:44:05 </td>
   <td style="text-align:left;"> $QQQ futures flatter than my girls ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:41:55 </td>
   <td style="text-align:left;"> $QQQ what’s everyone chart predictions for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:41:01 </td>
   <td style="text-align:left;"> $NVDA - $QQQ - $AMAT - $MRVL - $AMD 

Yet another Nvidia upgrade!

https://www.tipranks.com/news/article/nvidias-auto-software-opportunity-is-underappreciated-says-wells-fargo?utm_source=stck.pro&amp;amp;utm_medium=referral </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:38:17 </td>
   <td style="text-align:left;"> $QQQ $spy if the markets open green tomorrow i will give everyone who likes this post $900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:36:55 </td>
   <td style="text-align:left;"> $QQQ  strange oil goes up and qqq goes up. I guess it really is where else you gonna put your money! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:32:42 </td>
   <td style="text-align:left;"> $QQQ When SPY can be where QQQ is it&amp;#39;ll be great </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:30:55 </td>
   <td style="text-align:left;"> $QQQ ATH will be back sooner than we think. Prices of goods and services are ricing. It will reflect in earnings. Tech can quickly adapt to inflation by quickly adjusting prices. Other industries are slower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:29:22 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SPY $QQQ 

Tesla broke out the bull fake setup we discussed&amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:28:41 </td>
   <td style="text-align:left;"> $QQQ double top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:28:37 </td>
   <td style="text-align:left;"> $KWEB $JD $BABA $QQQ 

KWEB follow up&amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:28:36 </td>
   <td style="text-align:left;"> Stocks are rallying because of what an inverted yield curve says about the Fed and inflation, strategist says https://www.billionaireclubcollc.com/stocks-are-rallying-because-of-what-an-inverted-yield-curve-says-about-the-fed-and-inflation-strategist-says/ $SPY $QQQ $DJIA $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:27:56 </td>
   <td style="text-align:left;"> $JD $BABA $QQQ $SPY 

Broke out of the wedge&amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:27:32 </td>
   <td style="text-align:left;"> Daily Market Recap for Monday 4/4/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/EU7wmaWALrQ

$SPY $QQQ $IWM $TLT $UUP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:27:04 </td>
   <td style="text-align:left;"> $BABA $QQQ $SPY $AMZN 

Timely study&amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:26:39 </td>
   <td style="text-align:left;"> $SPY More upside coming. I get it, doesn’t make sense. But there is zero market fear right now. Soon, the greed will set in…I’m trust you know what to do $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:22:55 </td>
   <td style="text-align:left;"> $SPY haven’t bought a call in a week. Are they still paying out? How the calls doing? 

   . $AAPL $PYPL $NVDA $QQQ   ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:22:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $NDX 

yield Curve inversion shouldn’t be disrespected, but to be fare it’s a Scout indicator. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:18:53 </td>
   <td style="text-align:left;"> What do you think of this? $QQQ&amp;#39;s in Uptrend: Moving Average Convergence Divergence (MACD) Histogram just turned positive. View odds for this and other indicators: https://srnk.us/go/3552808 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:16:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $NQ_F 
Beginning of year vs now. stocks have reclaimed their highs as well as the SPY but the NSDQ is off very much. Did a possible reset happen here? I’m starting to think so. 1 idea stocks could double if the NSDQ hits 1600 highs again. Puts companies like AAPL at 250-300+. 
2nd idea the NSDQ has reached its high reason it would go above 15000 during trading sessions and stocks will fall to new lows which means we are trading the reset and stocks will soon fall from their new 52week highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:14:17 </td>
   <td style="text-align:left;"> $SPY it’s rolling over.  Nevertheless  $DIA $QQQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:12:08 </td>
   <td style="text-align:left;"> Thanks uncle Elon! $TWTR $TSLA $QQQ $BTC.X $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:10:01 </td>
   <td style="text-align:left;"> $SPY $QQQ IMO, the market will be range bound for two to three weeks before at least an 8-10% down move.  I will move to 100% cash if we get close to 4700. Better safe than sorry.  IMHO three possibilities have the highest chance of happening, with 1 having the highest chance and 3 the lowest:  
 
1- We reach 4700-4760 we pullback to 4300, and move up to 5300-5600 before a 20-30% decline .  
2- We reach 4700-4760 we selloff at least 20%.  
3- We move up to make all time highs without a decent pullback  then chances we come down close to Feb lows. 
 
$XBI is getting close to the big resistance at 99.  
 
Not bullish not bearish, for now baahhish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:09:39 </td>
   <td style="text-align:left;"> $QQQ road to 320 starting this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:09:27 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:09:12 </td>
   <td style="text-align:left;"> $QQQ wow who got their 2pt short filled AH on the low? That was extra </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:08:05 </td>
   <td style="text-align:left;"> $spy $qqq SP500 now 4.6% from all time highs.  Who knew raging inflation and war was so bullish.  Not complaining.  I’ll trade this left right, whichever way it goes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:06:26 </td>
   <td style="text-align:left;"> $QQQ  Seeing the lowest daily volumes since 1/10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:05:10 </td>
   <td style="text-align:left;"> $QQQ when you have no hope to get out of your job 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 07:04:55 </td>
   <td style="text-align:left;"> $QQQ what was that 367.11 candle? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:59:49 </td>
   <td style="text-align:left;"> $SPY MM bears played it cool today, they don&amp;#39;t need to sink in anything more while the bulls are pushing super hard $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:59:28 </td>
   <td style="text-align:left;"> $QQQ 300 low next month more than likely, right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:57:03 </td>
   <td style="text-align:left;"> $SPY $QQQ futes sitting patiently waiting for a pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:51:18 </td>
   <td style="text-align:left;"> $QQQ https://www.danniles.com/interviews/2022-04-01-cnbc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:50:17 </td>
   <td style="text-align:left;"> $QQQ https://www.youtube.com/watch?v=JW9hKpj-PsU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:44:23 </td>
   <td style="text-align:left;"> $PLTR x $SATL x SpaceX $QQQ $BA 

https://blog.palantir.com/edge-ai-in-space-93d793433a1e </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:43:48 </td>
   <td style="text-align:left;"> $PLTR Palantir x $SATL x SPACEX $QQQ $BA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:42:37 </td>
   <td style="text-align:left;"> Don&amp;#39;t Miss Finom Groups latest State of the Market video!  
 
-Every week, breaking down all the macro-market force factors from the economy to the quant data and everything in between!  
 
-Notes on $SPY $QQQ $WMT $AAPL and all manners of market breadth studies! What happens during midterm election years, rate hikes etc?  
https://www.youtube.com/watch?v=na5HWqwIrdA&amp;amp;t=9s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:41:48 </td>
   <td style="text-align:left;"> Rising Rates and Volatility are Features, Not Bugs: Top Trade Opportunities https://www.billionaireclubcollc.com/rising-rates-and-volatility-are-features-not-bugs-top-trade-opportunities/  $SPY $DJIA $QQQ $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:38:58 </td>
   <td style="text-align:left;"> $SPY. Buckle up

U.S. ECONOMIC DATA THIS WEEK:

*FACTORY ORDERS (MON.)
*TRADE BALANCE (TUES.)
*ISM SERVICES PMI (TUES.)
*FED FOMC MINUTES (WED.)
*JOBLESS CLAIMS (THURS.)

$DIA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:31:16 </td>
   <td style="text-align:left;"> $QQQ $ANY Down on bad pr up 100% only in ah. This is how sick the market is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:31:09 </td>
   <td style="text-align:left;"> $QQQ lowest volume for QQQ in 2022? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:27:22 </td>
   <td style="text-align:left;"> FTSE &amp;amp; DAX march towards key psychological levels https://www.billionaireclubcollc.com/ftse-dax-march-towards-key-psychological-levels/  $DJIA $DXY $VIX $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:26:32 </td>
   <td style="text-align:left;"> $SPY $QQQ Curious, those who trade with Stocktwits, what do you do when your account is suspended and you can’t login-not even able to access your funds? Crypto or Stocks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:26:20 </td>
   <td style="text-align:left;"> $PYPL  easy 25% drop here.  PayPal $QQQ $SPY  $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:23:54 </td>
   <td style="text-align:left;"> $AAPL $PYPL  I said PayPal will revisit $95 $SPY  $QQQ $SQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:22:35 </td>
   <td style="text-align:left;"> $qqq even worse than $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:22:15 </td>
   <td style="text-align:left;"> $QQQ $SPY when is the next rate hikes supposed to happen lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:20:48 </td>
   <td style="text-align:left;"> Yield Curve Inversion Signals Possible Recession https://www.billionaireclubcollc.com/yield-curve-inversion-signals-possible-recession/  $SPY $DJIA $QQQ $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:16:36 </td>
   <td style="text-align:left;"> $AAPL  kaboom $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:15:21 </td>
   <td style="text-align:left;"> $SPY $QQQ 

I hear jpow’s doing a drive by near moo’s place tonight...🖨🏎💨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:13:46 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Had to snipe a few bear cubs today with the boys today. @LiLduckboi_realbruh @PurpleReign8 @PierceC @blancobull @Mrbinks 

🐂 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:13:45 </td>
   <td style="text-align:left;"> $QQQ When does this finally go green again... feels like forever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:13:10 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:11:38 </td>
   <td style="text-align:left;"> $QQQ bears, at work </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:10:57 </td>
   <td style="text-align:left;"> $SPY $qqq if only we knew what is brewing.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:10:21 </td>
   <td style="text-align:left;"> $QQQ bears, looking in the mirror today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:08:53 </td>
   <td style="text-align:left;"> $QQQ bears, today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:07:43 </td>
   <td style="text-align:left;"> $FB tell me your trending without telling me you’re trending 😂 PT 1 Daily chart

#optiontrading #tradeidea #daytrade $SPY $QQQ $CRYPTO htt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:06:33 </td>
   <td style="text-align:left;"> $QQQ $SPY give me 2% down with a bearish engulfing candle lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 06:02:00 </td>
   <td style="text-align:left;"> Possible low risk trading setup on $QQQ, buy stop entry @371.84.. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:59:46 </td>
   <td style="text-align:left;"> $QQQ market is on crack again. Bunch of money losing companies rising </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:59:35 </td>
   <td style="text-align:left;"> $QQQ $SPY been hearing that volume has been weak in this run over past few weeks.  Does that look weak?   😂

Volume is fine, let’s see how the weak ends.   💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:58:18 </td>
   <td style="text-align:left;"> $QQQ tech will lead the way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:55:47 </td>
   <td style="text-align:left;"> $QQQ crypto rally commencing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:53:55 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 4/4/2022 $SPY $QQQ $CGC $TSLA $CCJ https://www.chartguys.com/daily-market-videos/4208/the-must-hold-key-level </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:52:42 </td>
   <td style="text-align:left;"> $spy $qqq https://www.youtube.com/watch?v=1trwj6LsiAc&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:50:39 </td>
   <td style="text-align:left;"> Elon Buys Twitter!!! https://www.youtube.com/watch?v=i6usjq-TUdI 
$spy $qqq $tsla $twtr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:49:39 </td>
   <td style="text-align:left;"> $SPY $UVXY $QQQ $IWM - How do you think the Fed will cover the decaying economy? 67% of Americans live paycheck to paycheck. Morgan Stanley stated today “the bear market rally is over” and expects equities to come down. I’m looking for the catalyst. There is always one event that starts the domino effect. I don’t think we understand just how much toxic debt and data were sitting on. While this article doesn’t show the gravity of the situation it’s far worse. People are suffering economically. It’s no wonder the Atlanta Fed was predicting a Q1 GDP of 0.1%. Something is going to give eventually but the question is what? Bond market? That’s a collective worry by analysts and economists. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:49:10 </td>
   <td style="text-align:left;"> $QQQ So is the plan to just let the bulls inflate their bags till Wednesdays FOMC? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:48:26 </td>
   <td style="text-align:left;"> $SPY $qqq very very bad news is coming. I hope it is not true. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:47:59 </td>
   <td style="text-align:left;"> $qqq YO goes up.  YO goes down.  N YO goes 🐑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:47:25 </td>
   <td style="text-align:left;"> Lowest volume for $QQQ so far in 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:46:55 </td>
   <td style="text-align:left;"> $QQQ Interesting to see how much the bozos on here over the weekend lost today. 
 
Always the same. 
 
LMFAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:45:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Ray needs to stfu! 🤬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:44:30 </td>
   <td style="text-align:left;"> $QQQ $SPY $AMZN $TSLA 

I realize this was posted in my chat room and not on the public board

Rainbow 🌈 Convergence. What got us into the mess is taking us out, the same moving averages that converged are reversing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:44:20 </td>
   <td style="text-align:left;"> $RBLX Inverted H&amp;amp;S’s Possibly🚀  
There is a chance for a larger move: 
$AMD $AAPL $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:44:10 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $DJIA $QQQ ---- 
 
Senile Joe has completely lost it. He already forgot that yesterday he declared that the ‘most dangerous person in the world’ was Putin, the day before it was Trump, and the day before that it was Tucker Carlson.  
 
Instead of passing judgment on everybody, maybe the dumb fuck should look at the mirror and assume responsibility for breaking every campaign promise he made in 2020, including reducing healthcare costs, securing the US border, and fighting drugs and crime.  
 
https://thehill.com/news/3258124-biden-rupert-murdoch-most-dangerous-man-in-the-world/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:43:56 </td>
   <td style="text-align:left;"> $QQQ congrats bulls. I’m a grumpy bear right now but I got till June. How much higher you bulls think we got till a big reversal? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:43:31 </td>
   <td style="text-align:left;"> $QQQ Tesla is pumping 10% a week and speculative companies with no profit ar running once again. I see just like that we&amp;#39;ve returned to euphoria </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:36:20 </td>
   <td style="text-align:left;"> $QQQ LETS GO!! 🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:33:19 </td>
   <td style="text-align:left;"> $QQQ i swore we were testing the lows soon. Fuk it longing it. Everything bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:30:07 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA lets see how far we can push this “buy the inversion” and “soft landing” 

Higher!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:26:56 </td>
   <td style="text-align:left;"> $AAPL $AMZN $QQQ Earning reports Today after the market open., stocknoptions-alerts.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:23:33 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:22:20 </td>
   <td style="text-align:left;"> $QQQ Target for ridiculous momentum on $NFE =  $56-$58 seems reasonable right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:21:29 </td>
   <td style="text-align:left;"> $PLTR only the beginning. Many people don’t know what they are up against. Total complete ecosystem. Their software is unreachable. $BA $RTX $QQQ $SNOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:21:20 </td>
   <td style="text-align:left;"> $SPY $QQQ You know the market is up when CNBC drags out Morgan Stanley&amp;#39;s permabear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:19:51 </td>
   <td style="text-align:left;"> Repeating my last tweet -&amp;gt; THE MARKET IS STRONG!!! 
IMHO, $SPX is poised for another run up. 
Wish I&amp;#39;d stayed long (see my 3/29 tweet -&amp;gt; I was wrong).  
Looking for an chance to re-buy $SPY $QQQ $IWM  
 
PSA - Don&amp;#39;t anticipate, just react and trade what is in front of you.  Also, insulting the market, and putting down people who are making money/profit (while you&amp;#39;re sitting on a loss) is not a good look. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:18:56 </td>
   <td style="text-align:left;"> $QQQ screw the proles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:18:13 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : RSP Takes in Nearly $1 Billion in March https://www.stck.pro/news/QQQ/25620421 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:17:32 </td>
   <td style="text-align:left;"> $SPX $QQQ $MSFT $AAPL $GOOG VIX not able to sustain and investor confidence building up as seen in the VIX chart... tells a compelling story of what lies ahead...Mega tech GARP holding the indexes... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:15:31 </td>
   <td style="text-align:left;"> $BTAI I could see this possibly doubling tomorrow. Pretty much only owned by institutions including blackrock and vanguard $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:15:11 </td>
   <td style="text-align:left;"> $QQQ think of humans as sort of a cornered animal.  they cannot keep up with inflation and they are increasingly desperate.  so in that environment they take excessive risk to try to keep up with the Joneses.  it is what it is.  until it isn&amp;#39;t.  can&amp;#39;t wait to watch it all unfold, be it up or down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:14:17 </td>
   <td style="text-align:left;"> $QQQ predictions for tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:12:40 </td>
   <td style="text-align:left;"> $QQQ $SPY  When will  situation like Sri Lanka  Will  happen here ???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:11:01 </td>
   <td style="text-align:left;"> $TSLA $SPY $DJIA $QQQ  
 
Tesla worth 63% more than it was just a little over a month ago. 
 
lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:10:59 </td>
   <td style="text-align:left;"> $SPY $QQQ once again - there&amp;#39;s nothing unusual about low volume in an up-trend on the indices. @Blue_Team_Inc  
 
https://twitter.com/hmeisler/status/1492499676578394113 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:08:38 </td>
   <td style="text-align:left;"> $SPY $QQQ Why arent the Traders on Fast Money CNBC ever held accountable for their HORRIFIC Market calls. Dan Nathan and Guy Adami and Tim Seymour, all said to FADE the rally 3 trading sessions ago.. And here we are today with none of these IDIOTS getting called out? lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:07:11 </td>
   <td style="text-align:left;"> $QQQ in the real world, where government calcs are not involved, inflation is easily around 35%. 
 
i dare some of you to book an airline flight 3 months out from now.  you literally won&amp;#39;t believe your eyes LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:05:31 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 
   
The best thing that can happen to America at this point is JPOW keeps interest rates at a ridiculous 0.25% while the financial assets and wealth of the richest Americans reach new ATH&amp;#39;s  
  
The whole time average Americans watch the rich get richer while they continue to struggle under double digit inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:05:24 </td>
   <td style="text-align:left;"> $QQQ guh 
https://www.youtube.com/watch?v=IM2T8bxccJE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:04:10 </td>
   <td style="text-align:left;"> $QQQ show me a bear in this market and I&amp;#39;ll show you a fool. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:02:02 </td>
   <td style="text-align:left;"> $SPY Confirmed on the daily chart, today’s rally was indeed the lowest $QQQ print of the year. 

Credit to Helene Meisler for the observation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:01:52 </td>
   <td style="text-align:left;"> $QQQ +3% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 05:01:05 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
The best thing that can happen to America at this point is JPOW keeps interest rates at a ridiculous 0.25% while the financial assets and wealth of the richest Americans reach new ATH&amp;#39;s 
 
The whole time average Americans watch as the rich get richer while they continue their struggle under double digit inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:57:08 </td>
   <td style="text-align:left;"> $SPY $QQQ  Look at that volume after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:56:48 </td>
   <td style="text-align:left;"> $SPY $QQQ gah anyone else doing their taxes this year.  ETrade changed their accounting for 2021, so that most of your short term GAINS end up getting piled into the 1099 “wash sale disallowed” column. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:55:26 </td>
   <td style="text-align:left;"> $QQQ $SPY Debt-based melt up alright ... convinced yet?  But what timeframe?  I was convinced of it in EARY 2020 and have only been more convinced since.  The dip that CONVENIENTLY started pretty much at very start of Q1 was a only a correction in the melt up.. The melt up that has been occurring beyond 2020, and really started in 2008 with QE (imho).  Also, I want another correction before we melt to the top!  Watch the 10yy curve .... that is your true &amp;quot;fear gauge&amp;quot; this time around.. This market will CRASH at some point... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:55:22 </td>
   <td style="text-align:left;"> $QQQ Most of the &amp;quot;innovation&amp;quot; here is never practical, and just wasteful use of our planets resources... so you have social media companies being called &amp;quot;technology&amp;quot; no, lets get real again $CCL $GS $JPM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:52:56 </td>
   <td style="text-align:left;"> $QQQ Markets are severely undervalued at the current price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:52:25 </td>
   <td style="text-align:left;"> $SPY $NASDAQ $QQQ  The Federal Reserves are public enemy number 1. They are literally destroying the world within our very own eyes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:52:15 </td>
   <td style="text-align:left;"> $SPY $QQQ A strong close. Investors start to realize that the US economy is doing great and the chances of a recession happening in the US are close to dead zero within the next few years. As long as the economy continues to grow strongly, stocks are going much higher no matter what the FED will do with the interest rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:51:28 </td>
   <td style="text-align:left;"> Stocks close higher, Twitter soars on news of Musk stake https://www.billionaireclubcollc.com/stocks-close-higher-twitter-soars-on-news-of-musk-stake/ $TWTR $TSLA $SPY $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:50:16 </td>
   <td style="text-align:left;"> Musk’s Lawyers Suggest a Rogue U.S. Agency is being Weaponized Against Him (SEC)  
 
 
Read: https://channelchek.com/news-channel/Is_the_SEC_conducting_Unfounded_Investigations_of_Elon_Musk 
 
 
$TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:49:53 </td>
   <td style="text-align:left;"> The Index Bubble Michael Burry Warned About. 
 
 
Read: https://channelchek.com/news-channel/Is_the_Index_Bubble_Michael_Burry_Warned_About_Still_Looming_ 
 
 
$SPY $ARKK $QQQ $SQQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:49:06 </td>
   <td style="text-align:left;"> Update on DWAC the Trump Media SPAC.... Just the Facts  
 
Read: https://channelchek.com/news-channel/Update_on_DWAC_the_Trump_Media_SPAC 
 
$DWAC $SPY $FB $TWTR $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:48:47 </td>
   <td style="text-align:left;"> Cathie Wood Says Benchmark Funds are Where the Risk Is  
 
Read:  https://channelchek.com/news-channel/Cathie_Wood_Says_Benchmark_Funds_are_Where_the_Risk_Is 
  
 
$ARKK $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:48:36 </td>
   <td style="text-align:left;"> AMC is Thinking Outside the Box Office and Diversifying 
 
Read: https://channelchek.com/news-channel/AMC_Theatres_CEO_Calls_Gold_Mining_Investment_Truly_Terrific_Opportunity 
 
 
$AMC $GME $QQQ $SPY $HYMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:48:03 </td>
   <td style="text-align:left;"> $QQQ some of you still think your opinion matters, which in and of itself is hysterical </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:48:03 </td>
   <td style="text-align:left;"> Peter Lynch Echoes Michael Burry’s Warning About Index Investments 
 
 
Read: https://www.channelchek.com/news-channel/Peter_Lynch_Echoes_Michael_Burrys_Warning_About_Index_Investments 
 
 
$SPY $QQQ $SQQQ $XLF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:46:05 </td>
   <td style="text-align:left;"> $SPY Two overpriced stocks make one look cheaper than the other, but both are expensive.  $uvxy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:45:40 </td>
   <td style="text-align:left;"> $QQQ  Back to 2020 levels before Covid-19 first hit  $216 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:45:27 </td>
   <td style="text-align:left;"> $QQQ where&amp;#39;s the volume? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:44:27 </td>
   <td style="text-align:left;"> There’s just NO better feeling than calls in a bull market 🚀🚀🚀🚀🚀🚀 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:44:18 </td>
   <td style="text-align:left;"> $QQQ Added long at 389. Still way too low. Looking for 400 by Wednesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:44:15 </td>
   <td style="text-align:left;"> $QQQ  i think people (beartards mostly) are majorly confused by interest rates/tapering.  the discount rate for out year earnings is NEVER the 10 year govt bond.  it is always much much much higher once you factor in the equity risk premium for a given business and the 10 year bond ends up being a rounding error in that calculation down at these levels.  if you are bearish because you think the 10 year might go higher from 2.4% post Fed taper and inflation persists, guess what, that is what the BULLS fully expect MIGHT happen too and they DON&amp;#39;T CARE.  In fact it is easy to argue it will make many market participants prefer the key constituents of the QQQ over many other stocks who rely on debt funding and can&amp;#39;t raise prices as easily and certainly over fixed income assets themselves.  also when the Fed raises short term rates the big cap tech stocks will make more money on their large cash balances.  In other words more fund flows will be in this direction, not away from it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:43:56 </td>
   <td style="text-align:left;"> $SPY $DIA $DAX $QQQ $NASDAQ Russia- Ukraine war, an escalation it seems. Oil shooting up again.

White House warns of potential Russian blitz on eastern Ukraine

https://thehill.com/news/administration/3258688-white-house-warns-of-potential-russian-blitz-on-eastern-ukraine/

Next Phase Of Ukraine War Could Last &amp;#39;Months Or Longer:&amp;#39; W.House
https://www.barrons.com/articles/next-phase-of-ukraine-war-could-last-months-or-longer-w-house-01649100608 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:43:25 </td>
   <td style="text-align:left;"> $QQQ $SPY nas down 2% in 4 days and up 2.05% in one day. Lol this market has become a joke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:42:18 </td>
   <td style="text-align:left;"> $QQQ lmao that was a good one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:40:37 </td>
   <td style="text-align:left;"> $QQQ for all you armchair henry kissingers -- the market is up 17% since the morning of the invasion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:39:55 </td>
   <td style="text-align:left;"> Jamie Dimon: ‘The Fed Should Not Worry About Volatile Markets Unless They Affect The Actual Economy’ https://www.billionaireclubcollc.com/jamie-dimon-the-fed-should-not-worry-about-volatile-markets-unless-they-affect-the-actual-economy/ $SPY $JPM $DJIA $QQQ $DXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:39:50 </td>
   <td style="text-align:left;"> $QQQ $SPY how are they never riots on Wall Street? Is it because most traders are priveledged? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:38:32 </td>
   <td style="text-align:left;"> Peak profit for the last 6 expired option alerts for $QQQ 193.95| 428.50| 321.09| 178.31| 20.42| 2.14| </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:38:30 </td>
   <td style="text-align:left;"> $QQQ Day trade🎉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:37:09 </td>
   <td style="text-align:left;"> $SPY $QQQ Did I miss some headline today? Or is this just standard &amp;quot;stonks only go up&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:36:53 </td>
   <td style="text-align:left;"> $QQQ no catalyst tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:36:48 </td>
   <td style="text-align:left;"> $QQQ for most of you the less you think the better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:36:26 </td>
   <td style="text-align:left;"> SPDR S&amp;amp;P 500 ETF (ETF: $SPY), PowerShares QQQ Trust, Series 1 (NASDAQ: $QQQ) – Markets Rise As Investors Await This Week’s Fed Minutes $DJIA https://www.billionaireclubcollc.com/spdr-sp-500-etf-etfspy-powershares-qqq-trust-series-1-nasdaqqqq-markets-rise-as-investors-await-this-weeks-fed-minutes/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:31:22 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears giving up all their gains from December to March because they got too greedy. Love it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:28:48 </td>
   <td style="text-align:left;"> $QQQ i have only been trading since 1984 or so but i believe the technical term for this is &amp;quot;bull market&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:28:10 </td>
   <td style="text-align:left;"> $QQQ got the 370 strikes exp this week ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:26:28 </td>
   <td style="text-align:left;"> $QQQ  Half of these stocks will never be profitable, being in the nasdaq  is worse than being in the SP -- you&amp;#39;ve got to have real profits to leave the nasdaq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:25:56 </td>
   <td style="text-align:left;"> $SPY $QQQ how did you all do today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:25:18 </td>
   <td style="text-align:left;"> $QQQ as soon as the stock market closed the junkies turned right to crypto and started taking them higher -- snort snort </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:23:55 </td>
   <td style="text-align:left;"> $SPY $QQQ It&amp;#39;s interesting there was a ton of bad news and everything gapped up regardless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:23:04 </td>
   <td style="text-align:left;"> $SPY $QQQ it is beautiful when you realize how big players just played us :)))) I think they are trying to engineer a soft landing and slow bleed for FOMC minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:22:52 </td>
   <td style="text-align:left;"> $QQQ 400 by may </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:22:16 </td>
   <td style="text-align:left;"> $QQQ bears trying hard to explain why their ass got whooped 🤡🤡🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:20:31 </td>
   <td style="text-align:left;"> $XLE $XLF $BAC $QQQ $DIA  
Most Anticipated Economic Events this Week  
 
https://www.financegreater.com/economiccalendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:19:38 </td>
   <td style="text-align:left;"> Stonks  
 
CAN 
 
NOT 
 
GO 
 
LOWER 
 
Like if you agree, comment if you need to be explained this. 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:19:07 </td>
   <td style="text-align:left;"> $QQQ lmao this is only up Becuase of elon musk. So when the index’s pull back next 2 days or rest of week they will just blame it on him. Easy pump and dump. Sell the news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:18:30 </td>
   <td style="text-align:left;"> $QQQ KWEB was up 7.65% -- QQQ cant even keep up with China?  come on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:17:33 </td>
   <td style="text-align:left;"> Markets Rise As Investors Await This Week&amp;#39;s Fed Minutes  $QQQ $SPY $DIA $PDD $BIDU 

https://newsfilter.io/a/8c9fea66178a4566022dc6face3b3328 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:17:18 </td>
   <td style="text-align:left;"> $TSLA  
Wanting to play that 1150 break tomorrow  
 
✅🚨FOLLOW for our signals DAILY🚨✅ 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:17:13 </td>
   <td style="text-align:left;"> $TQQQ Rock Chalk Jayhawks baby let&amp;#39;s goooo $SOXL $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:16:48 </td>
   <td style="text-align:left;"> $QQQ ok now you can explode back to $400 😮‍💨 372/370 spreads successful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:16:08 </td>
   <td style="text-align:left;"> $ES_F $SPY $NQ_F $QQQ we had indexes closing at the days highs, bullish week unfolding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:15:44 </td>
   <td style="text-align:left;"> JPMorgan Chase&amp;#39;s Jamie Dimon says the U.S. economy faces &amp;quot;unprecedented&amp;quot; risks

https://www.cbsnews.com/amp/news/jpmorgan-jamie-dimon-annual-shareholder-letter-2022-economy-risks/

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:15:41 </td>
   <td style="text-align:left;"> $SPY $QQQ 🖕🏼🖕🏼🖕🏼🖕🏼🖕🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:15:04 </td>
   <td style="text-align:left;"> $QQQ 

Or maybe Biden drops news tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:14:11 </td>
   <td style="text-align:left;"> $QQQ 

BIDEN NEWS tomorrow will be fun 💵💵

🤣🤣Calls 👉🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:13:09 </td>
   <td style="text-align:left;"> $QQQ sorry but this just doesn’t look bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:12:56 </td>
   <td style="text-align:left;"> $QQQ When I wasnovice I made a lot of mistakes 
then I came to know about thisC0mmunity.,, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:11:31 </td>
   <td style="text-align:left;"> $SPY Once again, market laughing at 25 bps hike.  JPOW is the real April 1 joke.  $uvxy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:10:34 </td>
   <td style="text-align:left;"> $QQQ Greed Index = 100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:10:27 </td>
   <td style="text-align:left;"> I&amp;#39;ll take that kind of outperformance today vs. $SPX $QQQ $DIA $SPY   You can trade with me folks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:10:23 </td>
   <td style="text-align:left;"> $QQQ Went deep on Netflix and Facebook calls on Friday, and sold them today.  Shifted to net short at close.  This rally is very sus.  Expecting some red tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:10:15 </td>
   <td style="text-align:left;"> $QQQ 370 incoming😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:09:45 </td>
   <td style="text-align:left;"> $QQQ i just realized that none of you know what u r talking about </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:09:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Eh..Oh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:09:24 </td>
   <td style="text-align:left;"> $QQQ This goes higher. People think it will go lower because it went so high today. Bear trap before hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:09:04 </td>
   <td style="text-align:left;"> $QQQ 

🤣🤣🤣🤣 yeah

 -4-6% days 

APRIL the new MAY ⚠️⚠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:09:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$900M to the SELL side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:08:20 </td>
   <td style="text-align:left;"> $QQQ damn good close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:07:56 </td>
   <td style="text-align:left;"> $QQQ no more -3 or -4% days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:07:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:07:27 </td>
   <td style="text-align:left;"> $QQQ have people completely lost their minds???  You have been warned </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:06:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:06:29 </td>
   <td style="text-align:left;"> $SPY $UPRO $QQQ S&amp;amp;P 500 rises to start week, Nasdaq gains 1.9% on tech comeback https://www.cnbc.com/2022/04/03/stock-market-futures-open-to-close-news.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:06:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 4/5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:06:10 </td>
   <td style="text-align:left;"> $QQQ After watching this today, I know the world is full of special people. Tomorrow is going to be entertaining though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:05:03 </td>
   <td style="text-align:left;"> Market wrap: 
🔷 US indices closed higher on the day:  
$DJIA +0.3%, $SPX +0.8%, $QQQ +1.9% 
🔷 #Gold (+0.6%) and #WTI (+4.3%) both traded higher on the day. 
🔷 #AUD and #NZD were the day&amp;#39;s strongest major currencies; #EUR was the weakest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:04:41 </td>
   <td style="text-align:left;"> $SPY Nice.  Good to know that Elon Musk can single handedly move the market by the trillions.  $uvxy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:04:03 </td>
   <td style="text-align:left;"> $QQQ same chart I posted earlier.  The accuracy though. I’m telling y’all traditional this or that isn’t it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:03:57 </td>
   <td style="text-align:left;"> $QQQ What a day!  We need more of $elon news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:03:38 </td>
   <td style="text-align:left;"> $QQQ QQQ Apr6 368C 910k ITM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:03:35 </td>
   <td style="text-align:left;"> $UVXY $QQQ $SPY $DJIA  Wow, vix goes down because Elon Fucking Musk buys a stake in twitter! LOL! Reality is USA recession coupled with continued inflation right around the corner. I call it Recessflation!  
 
https://www.marketwatch.com/story/u-s-economy-will-fall-into-a-recession-this-summer-as-inflation-eats-into-consumer-spending-former-fed-official-warns-11649101555?mod=mw_latestnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:02:54 </td>
   <td style="text-align:left;"> $QQQ war is over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:02:28 </td>
   <td style="text-align:left;"> $QQQ inflation is around 30% so buy stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:02:13 </td>
   <td style="text-align:left;"> $QQQ I cant wait to see open tomorrow after that bullish close. loaded up lotto $386 Wednesday calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:01:45 </td>
   <td style="text-align:left;"> $QQQ let me guess -3% tmr. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:01:13 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ Weak volume in both large cap indexes. Compare today&amp;#39;s to Fri.&amp;#39;s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:01:09 </td>
   <td style="text-align:left;"> Thanks uncle Elon! $TWTR $TSLA $BTC.X $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:01:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 83522400. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:00:55 </td>
   <td style="text-align:left;"> $QQQ a close like the last several weeks 😆 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:00:24 </td>
   <td style="text-align:left;"> $QQQ flyingggg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:00:05 </td>
   <td style="text-align:left;"> $TWTR $52.09 resistance $spy $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 04:00:02 </td>
   <td style="text-align:left;"> $QQQ now THIS is a bullish close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:59:57 </td>
   <td style="text-align:left;"> $QQQ what’s even going on with this market 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:59:56 </td>
   <td style="text-align:left;"> $WMT WTF is going on here ,should I follow-up tomorrow and sell calls.$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:59:14 </td>
   <td style="text-align:left;"> Live updates | 1,550 civilians evacuated from Mariupol https://www.billionaireclubcollc.com/live-updates-1550-civilians-evacuated-from-mariupol/ $SPY $QQQ $DJIA $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:58:46 </td>
   <td style="text-align:left;"> $QQQ This really going to move 2% every day huh? In either direction! Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:57:45 </td>
   <td style="text-align:left;"> $QQQ 📍📍📍 big boys won&amp;#39;t even let it touch vwap today... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:57:34 </td>
   <td style="text-align:left;"> $QQQ this is where the real gamblers hang out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:57:02 </td>
   <td style="text-align:left;"> $QQQ Good luck tomorrow bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:56:46 </td>
   <td style="text-align:left;"> $qqq going short here for a swing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:56:38 </td>
   <td style="text-align:left;"> $QQQ pin it 📍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:55:41 </td>
   <td style="text-align:left;"> $QQQ pamp it!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:54:41 </td>
   <td style="text-align:left;"> $QQQ $SPY Did I not say buy the inversion last week? :)) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:54:25 </td>
   <td style="text-align:left;"> $SPY $UVXY $QQQ  just to be clear, Bears forgot Friday was April Fools Day 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:53:53 </td>
   <td style="text-align:left;"> $MU $SPY $QQQ  Makes perfect sense to me.  Staying in DC for the entire session would be bad for the environment.  Article says she paid for the flights but be aware that WE PAY for the flights. 
 
https://nypost.com/2022/02/07/pelosi-spent-almost-500k-on-private-jets-since-october-2020/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:53:50 </td>
   <td style="text-align:left;"> $QQQ put spreads </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:53:15 </td>
   <td style="text-align:left;"> The bears are looking veeeerrryy restless - great sign for all of us call holders 🤣🤣🤣🚀🚀🚀🦅🇺🇸 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:53:07 </td>
   <td style="text-align:left;"> $AABB $FB $$SPY $QQQ $NFLX (5) Friday 911 MM signals and a hour ago the AABB mobile app on AAPL added a Spanish version. BOOM TOWN Coming!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:53:03 </td>
   <td style="text-align:left;"> $QQQ waiting for a confirmation breakout and hold of &amp;gt;373.  No rush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:52:51 </td>
   <td style="text-align:left;"> $QQQ Media and sleepy Joe pushing more and more for U.S. intervention in Ukraine. Trying to guilt trip everybody today with “genocide” picture (like we’ve never done that in Middle East 🙄). Only thing that could “save” Sleepy Joe’s presidency is shifting public opinion towards war! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:52:15 </td>
   <td style="text-align:left;"> $QQQ moneys printing 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:51:46 </td>
   <td style="text-align:left;"> $QQQ got some puts here for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:51:11 </td>
   <td style="text-align:left;"> $QQQ golden cross time? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:51:04 </td>
   <td style="text-align:left;"> $QQQ 

Sorry 🤣🤣🤣CALLS 

On news tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:50:12 </td>
   <td style="text-align:left;"> $QQQ Big Bob has a delicious CM sandwich with extra mayo waiting for you on Wednesday afternoon... Hope yall came hungry😋😋😋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:49:59 </td>
   <td style="text-align:left;"> NEW POST: Twitter and Elon Musk: No Regrets on My Part Whatsoever  https://marketchess.com/blog/view/twitter-elon-musk-no-regrets-on-my-part-whatsoever $QQQ $SPY $TSLA $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:49:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $AMZN $TSLA 

Morning star reversal pattern on the daily chart in QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:48:13 </td>
   <td style="text-align:left;"> $QQQ damn I’m a bull but I didn’t think we’d be this high today lol Let’s go to the moon 🚀🚀🚀 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:47:20 </td>
   <td style="text-align:left;"> $QQQ In the stock market, a Green Day without a follow through day Doesn’t mean anything… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:47:14 </td>
   <td style="text-align:left;"> $QQQ circuit breaker!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:46:32 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:44:38 </td>
   <td style="text-align:left;"> $TSLA $1200 EOW 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:43:52 </td>
   <td style="text-align:left;"> $QQQ yep 

⚠️⚠️MASSIVE SELL ORDERS ⚠️⚠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:43:00 </td>
   <td style="text-align:left;"> $QQQ as a single mother, I approve of this rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:42:49 </td>
   <td style="text-align:left;"> $QQQ are people still waiting for a dip today? 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:42:21 </td>
   <td style="text-align:left;"> $EBAY $QQQ normaly these run in tandem- the divergence from that trend is interesting 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:42:13 </td>
   <td style="text-align:left;"> $QQQ 

Poor hoodies buying rips 🤣🤣

⚠️⚠️360 retest tomorrow ⚠️⚠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:42:06 </td>
   <td style="text-align:left;"> $QQQ Bulls trying to muster up some more greed somewhere. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:41:29 </td>
   <td style="text-align:left;"> $QQQ 
Huge sell order ar L2 on many stock be careful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:41:20 </td>
   <td style="text-align:left;"> $QQQ $SPY low volume just means more buyers tomorrow....💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:41:14 </td>
   <td style="text-align:left;"> $QQQ gimme 369.420 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:39:59 </td>
   <td style="text-align:left;"> $QQQ we close +2% and I’ll turn my entire IRA into $UVXY 

pump it, bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:39:40 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AAPL Smart money is pumping so that they can dump before earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:39:40 </td>
   <td style="text-align:left;"> $QQQ stocks never go down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:39:25 </td>
   <td style="text-align:left;"> $QQQ anyone saying we are up for no reason please consider that market runs on time and price. Those are the only factors needed.  Right price right day, big move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:39:04 </td>
   <td style="text-align:left;"> $QQQ guess we&amp;#39;re heading to new highs despite no reason to do so. I&amp;#39;ll sit this out for now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:38:47 </td>
   <td style="text-align:left;"> $QQQ Bulls would have you believe everything that&amp;#39;s possible even someone from the future telling them different is PRICED IN... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:38:39 </td>
   <td style="text-align:left;"> $QQQ undoubtedly it’s a bear market rally … look at the chart … it’s so scary </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:38:26 </td>
   <td style="text-align:left;"> $QQQ 🏀 OFFICIAL ETF OF THE NCAA TOURNAMENT 🏀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:38:05 </td>
   <td style="text-align:left;"> $SPY $QQQ Low volume pumps today. Love it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:38:02 </td>
   <td style="text-align:left;"> $QQQ This is a penny stock now, right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:37:40 </td>
   <td style="text-align:left;"> $QQQ  VIX  getting complacent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:37:35 </td>
   <td style="text-align:left;"> $QQQ going to 375 u c$#k....😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:37:33 </td>
   <td style="text-align:left;"> $QQQ $XBI now for the real short covering. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:37:16 </td>
   <td style="text-align:left;"> $QQQ Margin calls gonna shoot this over 370 at the close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:37:14 </td>
   <td style="text-align:left;"> $QQQ up 2% for no reason... What a joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:36:44 </td>
   <td style="text-align:left;"> $QQQ I bought one put that&amp;#39;s why this is happening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:36:12 </td>
   <td style="text-align:left;"> $QQQ markets don’t need to make sense ( never has anyway) play the levels on the best days and forget the rest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:35:47 </td>
   <td style="text-align:left;"> $AAPL  Drew this chart a couple days ago I&amp;#39;m gonna go with you just hit the resistance line and this will be your last Green Day....$QQQ $SPY $TSLA $UVXY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-05 03:35:27 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA S&amp;amp;P 500 (SPY) Technical Analysis, Forecast, and Trade Ideas:  
https://www.youtube.com/watch?v=7L89BaU3LGk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 09:36:36 </td>
   <td style="text-align:left;"> latexfd357600e3472e25d72bf2baae97cdfeAMD ↗️

$AAPL $INTC $MSFT $DELL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 09:35:20 </td>
   <td style="text-align:left;"> $AAPL the run up is not done. Not a bear or bull. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 09:32:04 </td>
   <td style="text-align:left;"> $AMZN Ok yes it was amazon, had 82% of profits last quater from rivian stake. So that means this quarter with rivian plummet, they are going to have the biggest loss in company history $AAPL $NVDA $SPY $UBER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 09:30:48 </td>
   <td style="text-align:left;"> Apple $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 09:27:07 </td>
   <td style="text-align:left;"> $SPY Tesla without bitcoin or other investments is probably still unprofitable. Just two years ago they were still losing almost 10K per car. I don&amp;#39;t doubt costs for those cars have skyrocked in the last two years to say the least $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 09:26:04 </td>
   <td style="text-align:left;"> $SPY $AAPL latex0230fd878e71fe01a65fd625822398cdINTC): 00:17:41&amp;quot;, 
Buy Technology Vertical Put Option: Oracle Corporation ($ORCL): 00:18:59 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 09:23:10 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMD     ~Best-room on the net!! I&amp;#39;ve made over 35K by their alerts...   most-winning-chatroom.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 09:22:02 </td>
   <td style="text-align:left;"> $AAPL Return to latexadea693461a81df742415b6736c59c17AMD ↗️

$AAPL $AMZN $INTC $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 09:08:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB $GREE $AAPL  very motivational day in 
the 1 on 1’s playbook channel. Both plays went green if you scalped that’s beautiful I’m still holding on to a bunch ✅🏦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 09:03:34 </td>
   <td style="text-align:left;"> WE ARE NOW LIVE.🔥 #PRESSIT  
⚔️TRADE IDEAS LIVE STREAM  
👉IM GOING TO BREAK DOWN👇 
📈TRADE IDEAS 
🔫TRIGGERS  
🎯TARGETS  
🐲DRAGONS 
🌊FLOW  
💯SECTORS  
CLICK&amp;gt; https://us02web.zoom.us/j/87240523612 $SPY  $QQQ  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:56:17 </td>
   <td style="text-align:left;"> $PLUG $AAPL $NIO Account Challenge Update:-    
Start Date: March 1, 2022    
Starting Balance: $1,800    
Current Balance: $89,637    
Goal: $100,000 by end of April.   
Strategy: Swing Trade Options, Stocks    
     
Watch out for next play-- optionminning.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:46:24 </td>
   <td style="text-align:left;"> $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:45:25 </td>
   <td style="text-align:left;"> $MSFT $AMZN $NVDA $GOOG $AAPL  
Hello!  
 
The number of properties that are 30 or more days past due or in foreclosure reached approximately 1.95 million nationwide, while total U.S. foreclosure starts hit 25,000, up 541%🧨🚬 from the same time last year, Black Knight revealed. 
 
But back to pre-pandemic levels 
 
Nothing but a &amp;quot;soft landing&amp;quot;.  EU has likely begin its recession 
https://www.marketwatch.com/picks/mortgage-delinquencies-rose-for-the-first-time-in-9-months-heres-what-that-means-for-the-housing-market-01648863070 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:40:01 </td>
   <td style="text-align:left;"> $AAPL I was forced to upgrade today. I’m probably not the only one. More units at least. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:38:52 </td>
   <td style="text-align:left;"> $AAPL stock analysis based on today&amp;#39;s closing price 

https://youtu.be/FgZzl2vFjkk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:38:10 </td>
   <td style="text-align:left;"> $AAPL 😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:37:57 </td>
   <td style="text-align:left;"> $AAPL pullback after it hits 182/183 ish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:37:12 </td>
   <td style="text-align:left;"> $AAPL 
Timmy tine to fess up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:35:12 </td>
   <td style="text-align:left;"> $AAPL at the end of the day unless there is a specific news catalyst, it&amp;#39;s only when the algos are set and market makers want it to go above ATH that we will hit ATH.  The fact it ran like this when there was no new reason vs last week after it tanked just shows you how we just hope and pray mms are bulls on the day.  I got puts and calls.. let&amp;#39;s see what happens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:30:59 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMD      ~Best-room on the net!! I&amp;#39;ve made over 35K by their alerts...       most-winning-chatroom.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:30:56 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMD   ~$1800 into $40k in the last 30 days; If you really want to make huge profits on trading then;  Join this winning chat:..     winning-alerts-options.stockmarketmovers.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:28:30 </td>
   <td style="text-align:left;"> $SPY $AAPL 

Very clear market faked retail out for the big drop and now ripping to new highs. Stay long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:26:00 </td>
   <td style="text-align:left;"> $AAPL is currently showing a bull flag pattern! A bull flag pattern is a pull back after a strong rise up. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:17:45 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY 

Market doing what It does best. Now that everyone was scared for the drop two weeks ago apple is going to rip to new highs. ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:10:28 </td>
   <td style="text-align:left;"> $AAPL new highs tomorrow $NIO $CCL also looking bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:04:45 </td>
   <td style="text-align:left;"> $PONGF also Steve jobs worked for it

$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:03:30 </td>
   <td style="text-align:left;"> $AAPL its not growing, but priced like its doubling each year .. and that it will double each year for 30 yrs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:03:15 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-04 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=PjKTTHduVr8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:02:50 </td>
   <td style="text-align:left;"> $AAPL Puts starter today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:02:44 </td>
   <td style="text-align:left;"> $AAPL what a run! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 08:01:57 </td>
   <td style="text-align:left;"> $AAPL Option to look at... 👀 👀  $185.00 Call for Friday, June 17, 2022. Roughly 1 Million dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:55:33 </td>
   <td style="text-align:left;"> $ABC, $AAPL, $CTSH, buy signals, https://seekingalpha.com/instablog/250072-tom-lloyd/5715892-april-earnings-are-you-proactive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:48:38 </td>
   <td style="text-align:left;"> $AAPL somebody please put Hollywood in a straitjacket. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:48:26 </td>
   <td style="text-align:left;"> $SPY ...$UVXY $STUDY $AAPL $QQQ 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:47:20 </td>
   <td style="text-align:left;"> $AAPL nothing normal about this move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:46:32 </td>
   <td style="text-align:left;"> $AAPL am I the only one who sees the reverse head and shoulders on the quarter?  It&amp;#39;s not clean, but it is there.  $195 will come quick. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:41:44 </td>
   <td style="text-align:left;"> $AAPL @Pampitthandampit where you at fam we doing down yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:40:41 </td>
   <td style="text-align:left;"> $AAPL let’s goooo , stronger 

https://invescohood.com/apple-wants-to-be-your-bank/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:37:31 </td>
   <td style="text-align:left;"> $AAPL break 52 week highs tomorrow 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:36:57 </td>
   <td style="text-align:left;"> $AAPL 210. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:36:39 </td>
   <td style="text-align:left;"> $AAPL such a bullshit move today to crush all put premium. Literally does not give back any gains... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:35:45 </td>
   <td style="text-align:left;"> $SPY Watching $AAPL to see if it double tops to see how spy goes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:28:56 </td>
   <td style="text-align:left;"> Daily Market Recap for Monday 4/4/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/EU7wmaWALrQ

$AMD $AAPL $TSLA $RBLX
Tech pop and flop? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:22:55 </td>
   <td style="text-align:left;"> $SPY haven’t bought a call in a week. Are they still paying out? How the calls doing? 

   . $AAPL $PYPL $NVDA $QQQ   ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:21:07 </td>
   <td style="text-align:left;"> $SPY I can average down on puts like you did on your calls. That’s all $AAPL $PYPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:20:16 </td>
   <td style="text-align:left;"> $AAPL tippy tippy top 🔝 . Get it 😂 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:19:55 </td>
   <td style="text-align:left;"> $AAPL please go higher I want to make sure I time my purchase with the tippy top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:17:01 </td>
   <td style="text-align:left;"> $AAPL Ordinary folks barely able to afford weekly gas and groceries  
 
But somehow they will all be buying 1200 $ iphones ?  
 
Lmao waiting for Q2 earnings oh man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:14:29 </td>
   <td style="text-align:left;"> $AAPL I hope this makes an ATH - will make that fall after Q1 #s all that more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:13:57 </td>
   <td style="text-align:left;"> $AAPL Bought at $178, stop loss at $177! This is near all time high! Too risky to hold unless you are day trading! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:10:30 </td>
   <td style="text-align:left;"> $AAPL top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:03:23 </td>
   <td style="text-align:left;"> $AAPL MUD PACKERS STOCK DID WELL TODAY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 07:03:13 </td>
   <td style="text-align:left;"> $AAPL Not far from its all time high price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:59:16 </td>
   <td style="text-align:left;"> $AAPL  Closing chart on Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:56:43 </td>
   <td style="text-align:left;"> Our Unusual Options Platform Alerted: $AAPL with our scanner on $180 CALL Expiring: 05-20-2022 worth 33K🐂   Get Ahead Of The Move with SweepCast &amp;amp; Learn more about it on our profile today!🏆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:55:49 </td>
   <td style="text-align:left;"> $AAPL $MSFT $BRK.A $BRK.B be fearful when others are greedy …. Clear greed right here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:51:32 </td>
   <td style="text-align:left;"> $AAPL new highs this week? Sheesh! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:48:02 </td>
   <td style="text-align:left;"> $SPY $aapl frontloaded for 30% drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:47:15 </td>
   <td style="text-align:left;"> latex1703ce9ed8c5e794384812b4611207c4SPY puts scalped. Who had calls from Friday? SPY closed +0.86% 
 
$TWTR double calls 4/08exp $50 calls for totaling over 50% looks like daddy Elon was behind this pump 
 
$AAPL 4/14exp $180/$182.5 calls currently up 21%  
 
The #AI bot had some downtime this morning, but managed to fire off a few solid signals with $GBS being the top banger closed almost +68% today after IRB approval for it&amp;#39;s glucose clinical trial. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:46:24 </td>
   <td style="text-align:left;"> $AAPL Love this stock! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:42:37 </td>
   <td style="text-align:left;"> Don&amp;#39;t Miss Finom Groups latest State of the Market video!  
 
-Every week, breaking down all the macro-market force factors from the economy to the quant data and everything in between!  
 
-Notes on $SPY $QQQ $WMT latexe23de5da8967901b0e24a9ee65482a21AMZN 52 
 
Ford 4 
GM 6 
Toyota 10 
 
$TSLA 234 😆😆😆😆😆😆😆 
 
Nothing wrong with this picture eh&amp;#39;?  &amp;quot;They&amp;#39;re more than a car company.&amp;quot;   
 
Your own CEO said the stock was &amp;quot;too expensive&amp;quot; -- BEFORE THE SPLIT -- a thousand percent ago..   
 
When this bubble pops -- AND IT WILL -- TSLA will be one of the worst hit tickers in the history of the stock market...  I GUARANTEE IT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:41:11 </td>
   <td style="text-align:left;"> $TWTR 

$200 imminent on democracy 

$TSLA $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:39:09 </td>
   <td style="text-align:left;"> $AAPL BIDEN REPORTEDLY GRAVELY CONCERNED, “RUSSIAN TROOPS NOT EXERCISING COVID DISTANCING ???AND WEARING OF MASKS”.  ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:36:32 </td>
   <td style="text-align:left;"> $CSIQ $sol $fslr $AAPL $tsla csiq - Canadian Solarabout to blow the roof off this joint - easy 25-50% within a year .. double within 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:28:52 </td>
   <td style="text-align:left;"> $DIS check out JXN, fwd p/e 2.16, fwd eps 20.00. Jackson Financial, thank me later. 👍🏻 $AAPL $WFC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:28:25 </td>
   <td style="text-align:left;"> $JPM $WMT $AAPL J P Morgan Chase &amp;amp; Co (NYSE:JPM), Apple Inc. (NASDAQ:AAPL) – Could The Rise Of Fintech Create The Need For Bank Mergers? JPMorgan Chase CEO Jamie Dimon Weighs In

https://news.alertsandnews.com/j-p-morgan-chase-co-nysejpm-apple-inc-nasdaqaapl-could-the-rise-of-fintech-create-the-need-for-bank-mergers-jpmorgan-chase-ceo-jamie-dimon-weighs-in/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:27:11 </td>
   <td style="text-align:left;"> $AAPL VIX down, AAPL keeps going. 180 likely but maybe a pullback within the week for profit taking. Where my perma bears at? 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:25:09 </td>
   <td style="text-align:left;"> $AAPL back on track..$180 Thursday and $210 by the end of April! Yes, I said it!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:25:04 </td>
   <td style="text-align:left;"> $TWTR 

We going to $200 fellas 

Musk next project 

$SPY $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:24:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:23:54 </td>
   <td style="text-align:left;"> $AAPL $PYPL  I said PayPal will revisit $95 $SPY  $QQQ $SQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:22:36 </td>
   <td style="text-align:left;"> $AAPL 🤮💰🙌🥳🎉🥂🤙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:22:00 </td>
   <td style="text-align:left;"> $AAPL, $INTU and $FTNT are the top gainers in the Nasdaq 100 for the day. https://www.chartmill.com/stock/stock-screener?v=3&amp;amp;f=ind_20&amp;amp;s=pt&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_top_Nasdaq_100_gainers&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:21:29 </td>
   <td style="text-align:left;"> $QCOM $AAPL  Flip a coin up or down $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:20:53 </td>
   <td style="text-align:left;"> $AAPL $QCOM   O o. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:20:09 </td>
   <td style="text-align:left;"> $AAPL 200 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 06:16:36 </td>
   <td style="text-align:left;"> $AAPL  kaboom latexc16e9f151b270a85098a3d8f6fd2ddf9BRCC - 91% call flow 
$BABA - 95% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:58:59 </td>
   <td style="text-align:left;"> $AAPL appl you cheap h0re you better outperform 😡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:58:33 </td>
   <td style="text-align:left;"> $SPY exhaustion via $aapl we need good news to rip higher, so those calls print huge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:57:19 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : 4 Top Stock Trades for Tuesday: AAPL, IWM, JMIA, DWAC https://www.stck.pro/news/AAPL/25621275 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:52:23 </td>
   <td style="text-align:left;"> 1 $AAPL a day keeps the losses at bay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:51:42 </td>
   <td style="text-align:left;"> $msft $aapl $goog https://www.youtube.com/watch?v=H0V6_VgPUjU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:48:41 </td>
   <td style="text-align:left;"> $AAPL ol faithful always put a smile on our face </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:46:57 </td>
   <td style="text-align:left;"> $AAPL thanks for cheap puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:44:20 </td>
   <td style="text-align:left;"> $RBLX Inverted H&amp;amp;S’s Possibly🚀  
There is a chance for a larger move: 
$AMD $AAPL $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:40:52 </td>
   <td style="text-align:left;"> $AAPL anyone else get absolutely destroyed holding puts over the weekend? Haha today was absolutely horseshit. Good thing I never go in too large but holy hell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:40:48 </td>
   <td style="text-align:left;"> Business Model Changes Make Apple a More Interesting Investment -- article I ghost-wrote for @investorplace https://investorplace.com/2022/04/business-model-changes-make-aapl-stock-a-more-interesting-investment/ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:39:27 </td>
   <td style="text-align:left;"> $AAPL gg bears. Fleeced again by the beach ball under water we call the spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:38:52 </td>
   <td style="text-align:left;"> $AAPL Option to look at... 👀 👀  $185.00 Call for Friday, June 17, 2022. Roughly 1 Million dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:37:29 </td>
   <td style="text-align:left;"> $AAPL W.H.O. SUSPECTS, “MOST DEATHS IN UKRAINE RELATED TO COVID SYMPTOMS”.  ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:34:06 </td>
   <td style="text-align:left;"> $GOOG $AMZN $AAPL $NVDA $MSFT  
Money saved isn&amp;#39;t &amp;quot;moving&amp;quot; &amp;amp; inflation can begin to move savings held by the public or a hidden tax on savings. 
 
Inflation &amp;quot;winners&amp;quot; are Government w/HIGH public sector debt.  
 
Inflation is a tax on savings  
Inflation is a tax on creditors  
Inflation is a benefit to debtors (like the government) hence can the Fed inflate some of the debt away?  
 
Lastly, inflation currently is transferring wealth from creditors to debtors.  
 
Soft landing here we come? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:26:56 </td>
   <td style="text-align:left;"> $AAPL $AMZN $QQQ Earning reports Today after the market open., stocknoptions-alerts.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:26:49 </td>
   <td style="text-align:left;"> $AAPL highly recommend everyone to  follow them.. stockstradingalerts.is-best.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:22:47 </td>
   <td style="text-align:left;"> $AAPL Some of you really believe bears and their analysis? Most of them think that to short a stock is when you buy a put option lmaoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:17:32 </td>
   <td style="text-align:left;"> $SPX $QQQ $MSFT $AAPL $GOOG VIX not able to sustain and investor confidence building up as seen in the VIX chart... tells a compelling story of what lies ahead...Mega tech GARP holding the indexes... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:17:08 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Why Metaverse Stocks Flew High Today https://www.stck.pro/news/AAPL/25620439 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:16:31 </td>
   <td style="text-align:left;"> $AAPL this is my favorite quote by me “ it’s easier to catch a runner than to catch a falling knife 🔪”  we going to 180 fam the algo showing us what big money is expecting ✅🍀💚 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:11:29 </td>
   <td style="text-align:left;"> $SPY Once again, Americans foolishly underestimating the new variant that even China can&amp;#39;t contain under strict lockdowns. At least be somewhat prepared, if you get the new type.. you will understand exactly what i mean. Its not like the first and second ones were we got the sniffles for a few days,, this will drain all your energy for like 2 weeks. no joke, and will kill you if you dont have someone to take care of you $AMZN $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:06:15 </td>
   <td style="text-align:left;"> $AMZN $AAPL $NFLX $GOOG $FB  WHOOOAAAA, who&amp;#39;s listening.  https://finance.yahoo.com/news/ray-dalio-were-going-to-have-is-a-period-of-stagflation-135935874.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:04:31 </td>
   <td style="text-align:left;"> $AAPL the fact this is up 2.4% today alone makes my head hurt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:01:46 </td>
   <td style="text-align:left;"> $AAPL 4/14 175 puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 05:01:45 </td>
   <td style="text-align:left;"> $AAPL Is this ever going to break the ath? Its teasing it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:59:07 </td>
   <td style="text-align:left;"> $AAPL to be the first $3.0T market cap, and at this rate, quick. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:54:11 </td>
   <td style="text-align:left;"> $VPLM $TWTR I wonder if ELON MUSK is interested in owning all Voice over internet protocols? A very INTERESTING development! $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:54:06 </td>
   <td style="text-align:left;"> $AAPL ATH by Friday??🤩🍏🍏🍏✅✅✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:52:01 </td>
   <td style="text-align:left;"> $AAPL seeing 180 plus tommorow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:51:28 </td>
   <td style="text-align:left;"> $AAPL The bears 🐻 still not getting the market. No hope for them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:50:43 </td>
   <td style="text-align:left;"> $aapl bring it already! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:50:00 </td>
   <td style="text-align:left;"> $AAPL .....&amp;quot;This will never break $50...100...150...180.......???&amp;quot;  
 
DON&amp;#39;T BE THAT GUY! 
 
.P. Morgan analyst Samik Chatterjee raised his target for the stock price from $180 to.......... $210.             
            
Morgan Stanley raises PT from $164  to............ $200.          
          
Citi raises target to............ $200. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:48:09 </td>
   <td style="text-align:left;"> $SPY Just stay patient, all the CEOs are selling here. You&amp;#39;ll be able to get back in at 2020 levels. Don&amp;#39;t get sucked into the meme hype before the fed starts unloading and hiking --- Yes we will 100% be in recession by October, but we don&amp;#39;t know how deep that will be $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:47:33 </td>
   <td style="text-align:left;"> $AAPL $TSLA $TWTR 
 It looks like Elon thinks he’s above the law and is really looking to test the SEC. 

Elon Musk thumbs his nose at the SEC again with Twitter stake https://www.cnbc.com/2022/04/04/elon-musk-thumbs-his-nose-at-the-sec-again-with-twitter-stake.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:42:41 </td>
   <td style="text-align:left;"> Have almost $800k now in $TSLA . Have $1 mill in $aapl . Not selling a single share of either. $googl 3rd biggest position </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:42:00 </td>
   <td style="text-align:left;"> $MULN  only $AAPL  need cargo fleet vans !!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:40:06 </td>
   <td style="text-align:left;"> $AAPL  Likely to see a decline in revenue </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:39:58 </td>
   <td style="text-align:left;"> $SPY everything feels toppy, $AAPL sitting at ATH, $TSLA sitting at ATH, it&amp;#39;s all ready for a bounce down &amp;amp; for short sellers to step in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:38:52 </td>
   <td style="text-align:left;"> $AAPL  Dude how&amp;#39;s it going down there?.....STAY DOWN BITCH! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:37:33 </td>
   <td style="text-align:left;"> $AAPL funny how ppl said we will see 165 Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:36:10 </td>
   <td style="text-align:left;"> $TWTR 

$100 imminent 

$TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:34:14 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-04 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=PjKTTHduVr8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:33:44 </td>
   <td style="text-align:left;"> $TWTR $AAPL $TSLA  $AMD $AMZN  
Carnival CCL just blasted off in after hours !!!    OMG!  news it beats all historical bookings and predictions show record earnings on deck next QTR.  Freakin easy double!!!’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:31:46 </td>
   <td style="text-align:left;"> $TSLA Tesla calls. Huge pay day 🤑🤑🤑💵💵💵✅✅🚀🚀🚀 $SPY $AAPL $AMD $NVDA get ready for next BIG play   🤣🤣🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:29:39 </td>
   <td style="text-align:left;"> $AAPL NO JOKE…BIDEN JUST SAID, “GLOBAL WARMING CAUSES GUNS TO DISCHARGE ITSELF”…??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:21:23 </td>
   <td style="text-align:left;"> latex564b53b3c110db34f333dad7f1715837AAPL Still has you beat! 
 
NOW I DIDN&amp;#39;T SAY BEST STOCK TO BUY! 
 
✅🚨FOLLOW for our signals DAILY🚨✅ 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:21:00 </td>
   <td style="text-align:left;"> Looking at the yearly performance, $AAPL did better than 90% of all other stocks. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:19:32 </td>
   <td style="text-align:left;"> $AAPL $TWTR $BB 

Nice day from this group! 

AAPL - +2.12% 
TWTR - +27%
BB - +4% 

Holding AAPL calls +140% ✅
Missed TWTR didn’t want to chase
Holding BB 7.00 calls ✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:12:48 </td>
   <td style="text-align:left;"> Lets get $AAPL back in the 180s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:12:06 </td>
   <td style="text-align:left;"> $SPY Definitely could tel bankers were throwing loads of cash into the index&amp;#39;s today. Banks are gonna end up being to &amp;quot;Tech Heavy&amp;quot; --- $GS is gonna make gains in a hedge $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:11:07 </td>
   <td style="text-align:left;"> Peak profit for the last 6 expired option alerts for $AAPL 610.14| 416.13| 35.90| 271.08| 76.47| 8.45| </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:10:51 </td>
   <td style="text-align:left;"> $AAPL  
TIME TO GO! 
 
💰FOLLOW US FOR SIGNALS💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:08:37 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:05:44 </td>
   <td style="text-align:left;"> $RH / $SPY / $AAPL - CALLS PRINTED WELL, LOOKING FOR CONTINUATION TOMORROW 

CONGRATS TO OUR FOLLOWERS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:04:30 </td>
   <td style="text-align:left;"> $AAPL come on 220 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:03:18 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Stock Back in Headlines on Business Venture Updates https://www.stck.pro/news/AAPL/25616950 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:03:05 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SPY $AAPL It was hard and devastating for others battle Bulls! I&amp;#39;m glad that all those cocky guys learned a lesson today! Moment of silence for small Bulls which acc&amp;#39;s was wiped out. Maybe they will have chance to comeback. We will be happy to join us! Cya tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:03:00 </td>
   <td style="text-align:left;"> $AAPL Bears will claim victory because AAPL close .05 off the HOD. 🤣🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:02:31 </td>
   <td style="text-align:left;"> $AAPL everytime you see the &amp;quot;BAT&amp;quot;......

I&amp;#39;m telling ya. 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:02:30 </td>
   <td style="text-align:left;"> $SPY Inflated Market -- fed continuing to buy let&amp;#39;s go!! $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:02:25 </td>
   <td style="text-align:left;"> $AAPL good close on this! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:01:41 </td>
   <td style="text-align:left;"> $AAPL morning gap up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 04:00:45 </td>
   <td style="text-align:left;"> $TSLA $AAPL latex6b699c0e30882d2047f484983a11e502NVDA  
$AAPL  
 
They are the ones moving the market right now! 
 
💰FOLLOW to WIN💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:59:29 </td>
   <td style="text-align:left;"> $AAPL close the market up green
Again Excellent day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:56:42 </td>
   <td style="text-align:left;"> $AAPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:56:13 </td>
   <td style="text-align:left;"> Most Traded Contracts

$AAPL 08 April $180 Call
$TWTR 08 April $50 Call
$AAPL 08 April $177.50 Call
$AAPL 08 April $175 Put
$TWTR April $50 Call
$AMD 08 April $110 Call
$TSLA 08 April $1200 Call
$AAPL 08 April $182.50 Call
$AAPL 08 April $175 Call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:55:07 </td>
   <td style="text-align:left;"> $AAPL has surpassed 1 million option contracts traded today. 61% of those contracts are calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:54:56 </td>
   <td style="text-align:left;"> $AAPL fed Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:53:59 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SPY $AAPL Cmon Bulls! Power 5 min!!! Remember the times of your losses because of those beasts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:53:09 </td>
   <td style="text-align:left;"> $TSLA $AAPL $FTNT I feel like a genius today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:52:52 </td>
   <td style="text-align:left;"> $AAPL can anyone elaborate on apples potential subscription service this year? 🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:51:52 </td>
   <td style="text-align:left;"> $TSLA $GME $AMC $AAPL 

$GMBL 10 more minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:51:31 </td>
   <td style="text-align:left;"> $AAPL on tech mode hahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:50:36 </td>
   <td style="text-align:left;"> $AAPL Winners win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:50:24 </td>
   <td style="text-align:left;"> $AAPL getting angry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:50:08 </td>
   <td style="text-align:left;"> $AAPL I keep adding to my $185 calls ! I’m gonna Roll them all to June! 💪🏼🚀🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:50:04 </td>
   <td style="text-align:left;"> $AAPL 

Apple come on $180. 

For close. 
you Can Do It….🍏🍏🔝🆙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:48:44 </td>
   <td style="text-align:left;"> $AAPL WS wants $200. Easy money! $$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:48:38 </td>
   <td style="text-align:left;"> $AAPL flow is looking bearish on unusualwhales </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:48:14 </td>
   <td style="text-align:left;"> $TSLA $SPY $MSFT $AAPL $DWAC today was kinda awesome overall. Seemed to have actually bet in the right direction on all my day trades and swings for once 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:47:10 </td>
   <td style="text-align:left;"> $AAPL April14 $180Cs heating up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:46:59 </td>
   <td style="text-align:left;"> $TWTR Robinhood halts Twitter trading 

$SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:46:01 </td>
   <td style="text-align:left;"> $AABB $DWAC $TWTR $AAPL $TSLA $AABB new $AAPL app Spanis version added. (5) 911 MM signals Friday. BIG NEWS ON DECK!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:45:40 </td>
   <td style="text-align:left;"> $AAPL Do NOT be afraid to short or at these levels </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:42:38 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Bears settle in for new levels and new highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:41:04 </td>
   <td style="text-align:left;"> $AAPL so it&amp;#39;s up from pre market, huh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:40:21 </td>
   <td style="text-align:left;"> $AAPL 
This one’s funny. Apple is cutting back production of iPhones by millions and it goes up. I’m glad, but wary </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:39:45 </td>
   <td style="text-align:left;"> $AAPL how we feeling bears?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:39:40 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AAPL Smart money is pumping so that they can dump before earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:39:30 </td>
   <td style="text-align:left;"> $AAPL Going to study up on some LEAP Puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:38:14 </td>
   <td style="text-align:left;"> $AAPL 12 days higher - consolidate - then wham Trout across the face. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:35:47 </td>
   <td style="text-align:left;"> $AAPL  Drew this chart a couple days ago I&amp;#39;m gonna go with you just hit the resistance line and this will be your last Green Day....$QQQ $SPY $TSLA $UVXY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:34:47 </td>
   <td style="text-align:left;"> $AAPL keep her going few more dollars for a new 52 week high….
Luvmyapple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:34:17 </td>
   <td style="text-align:left;"> $AAPL @Chark careful who you follow on this app. I post a chart and a timeframe and this guy just starts to hate. Blocked me after pointing the obvious. Not all TA the same! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:34:14 </td>
   <td style="text-align:left;"> $SPY for the loss porn people,  
 
Whats the most you have lost in a day? 
 
Me: $115k 
 
$QQQ $TSLA $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:32:14 </td>
   <td style="text-align:left;"> $AAPL how is this still going up! Literally half the volume and trash market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:31:56 </td>
   <td style="text-align:left;"> $AAPL went down for no reason on Friday and floating back up for similar reasons; none. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:31:19 </td>
   <td style="text-align:left;"> $SPY tesla will be the least popular Ev in 5 years $AAPL $TSLA $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:31:15 </td>
   <td style="text-align:left;"> $TSLA going down rest of the week lol 😂 $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:30:28 </td>
   <td style="text-align:left;"> $AAPL rug pull soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:29:38 </td>
   <td style="text-align:left;"> $AAPL Couldn&amp;#39;t think of a better short, every product line should be tanking over the next few years and AppStore slowing with the pandemic&amp;#39;s end...Not to mention any regulatory black swans </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:28:52 </td>
   <td style="text-align:left;"> $AAPL https://finance.yahoo.com/amphtml/news/apple-aapl-top-ranked-growth-145002974.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:28:48 </td>
   <td style="text-align:left;"> $AAPL plus this was dropping after they said they were going to expand apple pay and it shook goldman affirm and other stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:27:58 </td>
   <td style="text-align:left;"> $AAPL moving as discussed, congrats. I have a few position hedging these shares! Here a quick video $study https://youtu.be/RaL6QfAqoXE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:27:38 </td>
   <td style="text-align:left;"> $AAPL new ath Inc we needed to dip and consolidate they calling for 200 soon enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:27:16 </td>
   <td style="text-align:left;"> $AAPL greedy fucking pigs 🐷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:26:30 </td>
   <td style="text-align:left;"> $AAPL $ISPO is the move , god bless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:25:57 </td>
   <td style="text-align:left;"> $AAPL the 3pm bots are clearly friendly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:25:32 </td>
   <td style="text-align:left;"> $AAPL 180 tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:24:29 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Brandon at afterparty! Give us power close in last 36 min! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:24:12 </td>
   <td style="text-align:left;"> $AAPL more puts set to fill when it reaches 179 ho babu </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:23:16 </td>
   <td style="text-align:left;"> Business Model Changes Make Apple a More Interesting Investment -- article I ghost-wrote for @investorplace https://investorplace.com/2022/04/business-model-changes-make-aapl-stock-a-more-interesting-investment/ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:23:08 </td>
   <td style="text-align:left;"> $AMD $120 tommrow? More upside than $TSLA $TWTR $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:22:57 </td>
   <td style="text-align:left;"> $AAPL 

Where are all the bearish comments from them clown from Friday. When it was dipping I was loading up calls. If I listen to those clowns I will only loose money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:22:49 </td>
   <td style="text-align:left;"> $TWTR SHE gonna runnnnnnnnn 🍞 🏃‍♀️ 🏃‍♂️ 

$TSLA $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:21:43 </td>
   <td style="text-align:left;"> $AAPL push that baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:21:23 </td>
   <td style="text-align:left;"> $AAPL watch for break out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:20:26 </td>
   <td style="text-align:left;"> $AAPL  Double top intraday.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:20:13 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $VUZI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:19:51 </td>
   <td style="text-align:left;"> $AAPL I want to swing 180 call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:19:14 </td>
   <td style="text-align:left;"> $AAPL somethings about to happen, never sits idle this long… hasn’t really done anything since shortly after market open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:16:30 </td>
   <td style="text-align:left;"> $AAPL mud-packers unite! buy the dips--eat well too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:16:09 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN All what i&amp;#39;ve bought in morning i&amp;#39;ve sold! Thank you for stubborness Bears! But battle still on so i might get and leave it overnight 
$AAPL Long@ 177.61 Target 180.22 Stop Loss 171.00 
Sold on 178.00 
 
Adding more $AAPL Long Exp04/08 @ 177.68 /0.15 Target 185.50 Stop Loss 172.34 
Sold on 178.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:14:26 </td>
   <td style="text-align:left;"> $SPY 3-4 CNBC has Sara Eisen so she&amp;#39;s always good to take things lower w/ her voice so, lets see 
 
$aapl $amzn $qqq $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:13:03 </td>
   <td style="text-align:left;"> $SPY $AAPL $VIX summer trading starting early this year.…be careful with theta </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:12:58 </td>
   <td style="text-align:left;"> $GOOGL happy with today we should be opening Above $2900 tomorrow $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:12:57 </td>
   <td style="text-align:left;"> $TSLA $AMZN $AAPL $SPY and officially i&amp;#39;m out of $SPY for today! 
$SPY  Long@ 454.55  Target 465.47 Stop Loss 449.54 
Sold on 456.95 
Adding more $SPY Long Exp04/08 @ 455.19 /1.66 Target 462.33 Stop Loss 451.91 
Sold on 456.91 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:12:33 </td>
   <td style="text-align:left;"> $AAPL its a mud-packer day! Will it last? or stink? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:12:02 </td>
   <td style="text-align:left;"> $AAPL more AAPL call flow on Sep22 180C and short dated 180C calls weekly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:11:03 </td>
   <td style="text-align:left;"> $AAPL $AAPL 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:09:02 </td>
   <td style="text-align:left;"> $AAPL $FB so much more room to go up from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:07:46 </td>
   <td style="text-align:left;"> $TSLA Just saying, the Shanghai lockdown COULD be longer than you think. 

Michigan: 80 days , March 24 to June 12. 

Shanghai&amp;#39;s on Day 8 of a much more populace city with a country leader who has a much stricter than USA policy called 

&amp;quot;Zero Covid Policy.&amp;quot; 

This is what I&amp;#39;m trying to say Shanghai&amp;#39;s population density is much more condensed than Michigan so, stay tuned....

$SPY $AAPL $SOXL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:07:10 </td>
   <td style="text-align:left;"> $AMZN easy money $SPY $NIO $AAPL $ROKU 💵🚀🔥 

LYYNNKK in BIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:06:43 </td>
   <td style="text-align:left;"> Apple given $185.00 PT by UBS Group AG. https://www.marketbeat.com/r/1742046 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:04:26 </td>
   <td style="text-align:left;"> $AAPL $spy $qqq cmon guys!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:02:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $GOOG $TWTR  ---POWA HOWA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:02:40 </td>
   <td style="text-align:left;"> $AAPL     Great…and remember, Calls dominate at 180. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:01:52 </td>
   <td style="text-align:left;"> $AAPL BIDEN LEAVES SOUTHERN BORDER OPEN FOR ANY AND ALL CRIMINALS…??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:00:33 </td>
   <td style="text-align:left;"> $TSLA Best comparing duration for longest lockdown state of USA to China&amp;#39;s now province stricken, Shanghai, 25 million people, so our #1, Michigan, 80 days, I&amp;#39;d say, Shanghai lockdown COULD go longer....

One can hypothesize NY state&amp;#39;s population density best mimics Shanghai&amp;#39;s where a 15,000/day (give or takeca few thousand a day, depends on scarcity car parts, Covid rules, etc.)

So... that will, or, could, you have to decide your own time-frame thatva much stricter than the USA &amp;quot;Zero-Covid Policy&amp;quot; allows Tesla factory to start up again 
$SPY $MSFT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:00:23 </td>
   <td style="text-align:left;"> $TSLA $SPY $AAPL $AMZN Bears cover your ears! 
Adding more $GOOG Long Exp04/08 @ 2864.70 /30.30 Target 2880 Stop Loss 2760.99 
Sold on 2870.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 03:00:16 </td>
   <td style="text-align:left;"> WTF...Russia are using $AAPL Macbooks as armor??  
 
Although, it looks like the bullet did not go thru but it was taken off of a dead Russian. 
 
Therefore, is the moral of the story not to get into a gunfight, if you do, then carry a Macbook??  
 
I would not carry my $DELL to a gun fight - just aluminum &amp;amp; plastic!!! 
 
https://twitter.com/BVasylchenko/status/1511002153506246667 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:58:07 </td>
   <td style="text-align:left;"> $AAPL    🍏 up on low volume today.  Not sure if that’s good or bad ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:57:41 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL  
$GOOG Long@ 2867.51 Target 2947.66 Stop Loss 2785.33 
Sold on 2871.00 taking this baby home! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:51:58 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL I dont know what to do Bears in this situation to cry for you, or hug you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:51:25 </td>
   <td style="text-align:left;"> Apple, IBD Stock Of The Day, Ripe For Another Potential Buy Point https://www.investors.com/research/ibd-stock-of-the-day/apple-stock-ripe-for-another-buy-point/ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:51:17 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ $AMD 
67 days of total lockdown for NY during Covid -19. 
Shanghai best compares populace-wise to NY, density, etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:51:08 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Top Stock Trades for the Week of April 4, 2022 https://www.stck.pro/news/AAPL/25613814 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:50:59 </td>
   <td style="text-align:left;"> $AAPL  This is just beginning an Elliott wave 4 down &amp;amp; will pullback imminently. Use your stops. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:50:22 </td>
   <td style="text-align:left;"> Check out my short video on a solid dividend stock to diversify your portfolio! Pays a monthly divy too! 😄 Thanks for giving the channel a shot! Wishing everyone the best! 
$SPY $AAPL $TSLA 

https://youtu.be/MuFSt5LlN_E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:49:54 </td>
   <td style="text-align:left;"> $TSLA $AAPL $SPY $AMZN I know we up! But damn!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:49:41 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT 🔥🔥🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:49:41 </td>
   <td style="text-align:left;"> Some top tech sector flow coming in above ask 
 
$AAPL - $7.4M put sweep 
$INTU - $1M call sweep 
$TWTR - $698K call sweep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:49:31 </td>
   <td style="text-align:left;"> $AAPL Power Hour! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:48:37 </td>
   <td style="text-align:left;"> $SPY Just wanted to provide some official information for how long the Shanghai lockfown could continue, it&amp;#39;s Day 8 today, started March 28.

Looked at states and I&amp;#39;ll just sample size and couple: 

#1 Michigan is with 10M people, locked downed 80 days, March 24 til June 12

#7 New York is best emulator of Shanghai&amp;#39;s population: 20M people .
New York lockdown March 24-May 28.

Now not saying Shanghai&amp;#39;s lockdown, of 25M people goes that long,  but, it could, companies like.....

$AAPL &amp;amp; $TSLA car plant in Shanghai 1st on my Don&amp;#39;t-Buy-This list of stocks
$SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:48:19 </td>
   <td style="text-align:left;"> $AAPL 18ema/50ema cross on 30min super super close, lets do this...179.50 print show me the money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:46:03 </td>
   <td style="text-align:left;"> $AAPL Q2 is a demand side/revenue miss...just remember that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:45:48 </td>
   <td style="text-align:left;"> $AAPL 200 please …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:45:35 </td>
   <td style="text-align:left;"> $AAPL choppy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:45:23 </td>
   <td style="text-align:left;"> $AAPL I love Apples 🍏🔥🔥🔥 
follow me @wizard 

www.personafi.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:44:27 </td>
   <td style="text-align:left;"> $AAPL go 175 so i can add again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:44:22 </td>
   <td style="text-align:left;"> $TWTR omg 226million shares traded 😍 😳 

$TSLA $AAPL $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:41:05 </td>
   <td style="text-align:left;"> $AAPL YUM YUM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:39:49 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-04 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=PjKTTHduVr8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:39:48 </td>
   <td style="text-align:left;"> $NNDM don&amp;#39;t ya think nndm reached out to aaple and working  with them.  I can be almost 50% certain that nndm reached out to Apple 🍎  $aapl , Sean patterson repeats Apple many times in his conversation.  Aaple is the top of the lead generation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:39:27 </td>
   <td style="text-align:left;"> Looking to see if $AAPL breaks up higher from this bull flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:39:21 </td>
   <td style="text-align:left;"> $AAPL bears… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:38:51 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SPY $AAPL Check out those calls Bears they were against your positions 
 
Adding more $TSLA Long Exp04/08 @ 1103.63 /23.40 Target 1200 Stop Loss 1080.41. 
Sold on 1148.96 
Adding more $FB Long Exp04/08 @ 232.59 /1.50 Target 237.50 Stop Loss 229.10 
Sold on 233.48 
Adding more $AMZN Long Exp04/08 @ 3327.00 /40.50 Target 3400 Stop Loss 3219.55 
Sold on 3345.65 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:37:33 </td>
   <td style="text-align:left;"> $LLL $AAPL $IMPP target price $30     squeeze imperial p </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:37:23 </td>
   <td style="text-align:left;"> $AABB $DWAC $TWTR $TSLA $AAPL Friday $AABB (5) 911 market maker ALERTS. 3-4 billion uncovered &amp;#39;&amp;#39;naked short&amp;#39;&amp;#39; shares! https://www.reddit.com/r/aabbstock/comments/tqr9w9/aabb_revenue_streams_and_deliverables/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:34:42 </td>
   <td style="text-align:left;"> $AAPL $SPY melt up mode. ( I’m tired, want to leave, but don’t want to leave). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:32:44 </td>
   <td style="text-align:left;"> #Apple Still Channel-Bound $AAPL https://talkmarkets.com/content/stocks--equities/apple-still-channel-bound?post=350355 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:32:19 </td>
   <td style="text-align:left;"> $AAPL 15M TF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:30:37 </td>
   <td style="text-align:left;"> $AAPL push past 178 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:29:33 </td>
   <td style="text-align:left;"> Trump&amp;#39;s Social Media Venture Abruptly Loses Key Officials; Sparks Concerns  $AAPL $DWAC $FB $GOOG $GOOGL 

https://newsfilter.io/a/472d4f531640bb7736eb6f7d526f4f47 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:29:21 </td>
   <td style="text-align:left;"> $AAPL nice volume td 👏.  All you need to know 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:27:51 </td>
   <td style="text-align:left;"> J P Morgan Chase &amp;amp; Co (NYSE: $JPM), Apple Inc. (NASDAQ: $AAPL) – Could The Rise Of Fintech Create The Need For Bank Mergers? JPMorgan Chase CEO Jamie Dimon Weighs In https://www.billionaireclubcollc.com/j-p-morgan-chase-co-nysejpm-apple-inc-nasdaqaapl-could-the-rise-of-fintech-create-the-need-for-bank-mergers-jpmorgan-chase-ceo-jamie-dimon-weighs-in/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:26:22 </td>
   <td style="text-align:left;"> $AAPL 18ema/50ema cross set up on the 30min time frame is a must watch. Lets see if the cross occurs before end of close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:24:38 </td>
   <td style="text-align:left;"> This is amazing! What do you think? $AAPL&amp;#39;s 10-day Moving Average moved above its 50-day Moving Average on March 28, 2022. View odds for this and other indicators: https://srnk.us/go/3552075 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:23:57 </td>
   <td style="text-align:left;"> ( $DWAC), Apple Inc. (NASDAQ: $AAPL) – Trump’s Social Media Venture Abruptly Loses Key Officials; Sparks Concerns https://www.billionaireclubcollc.com/dwac-apple-inc-nasdaqaapl-trumps-social-media-venture-abruptly-loses-key-officials-sparks-concerns/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:21:21 </td>
   <td style="text-align:left;"> $AAPL 30min chart shows an ascending triangle formed by the AD , target is 179.50 for this swing trade set up. Calls should be pumping near power hour </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:19:19 </td>
   <td style="text-align:left;"> Check Out What Whales Are Doing With  $AAPL https://www.billionaireclubcollc.com/check-out-what-whales-are-doing-with-aapl-2/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:18:00 </td>
   <td style="text-align:left;"> $AAPL has a Profit Margin of 26.58%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:16:52 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMZN  Real-time Alerting, Scanning, Analysis, &amp;amp; Artificially Intelligent Idea Generation Tools for Active Traders, Investors, &amp;amp; Money Managers. Innovating since 2003.  
 
Connect with Trade Idea (25% off) : bit.ly/3DCHFkUi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:15:50 </td>
   <td style="text-align:left;"> $AAPL Could The Rise Of Fintech Create The Need For Bank Mergers? JPMorgan Chase CEO Jamie Dimon Weighs In https://t.co/pbU6gpdmC1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:15:03 </td>
   <td style="text-align:left;"> $TSLA $AMZN latexd74cab976df6ee4d0e1088202cdc70c4FB   Long@ 231.52  Target 235.86 Stop Loss 217.95 
Sold on 232.06 
$AMZN Long@ 3327.62 Target 3410.09 Stop Loss 3274.44 
Sold on 3335.52 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:15:02 </td>
   <td style="text-align:left;"> $AAPL would not be surprised investor are moving money to $TSLA lol. Where is Tim? Need to pump lol 😂 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:14:33 </td>
   <td style="text-align:left;"> Could The Rise Of Fintech Create The Need For Bank Mergers? JPMorgan Chase CEO Jamie Dimon Weighs In  $JPM $WMT $AAPL 

https://newsfilter.io/a/7da67c451f8a80e99010d1a32d49faac </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:14:29 </td>
   <td style="text-align:left;"> Could The Rise Of Fintech Create The Need For Bank Mergers? JPMorgan Chase CEO Jamie Dimon Weighs In $JPM $WMT $AAPL https://benzinga.com/z/26456039#.Yks1Ma2jO1E.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:13:32 </td>
   <td style="text-align:left;"> $SPY Watching Apple for  Niagara falls $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:13:02 </td>
   <td style="text-align:left;"> $AAPL power hour today gonna b like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:12:48 </td>
   <td style="text-align:left;"> $AAPL $FB apple and Facebook looks very bullish. Tomorrow we are hitting the skies! What you bears talking about!? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:12:43 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Bears dont hope for Christmas close today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:11:58 </td>
   <td style="text-align:left;"> $aapl  i dont know buty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:11:43 </td>
   <td style="text-align:left;"> $AAPL will soon hit 6. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:11:35 </td>
   <td style="text-align:left;"> $AAPL seems like $TSLA is taking all the investors money from Apple today lol 😂 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:11:21 </td>
   <td style="text-align:left;"> $aapl bounce time 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:10:15 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AMZN $AAPL top Trending </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:10:14 </td>
   <td style="text-align:left;"> $AAPL #fjb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:10:10 </td>
   <td style="text-align:left;"> $AAPL short this crap to hell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:07:23 </td>
   <td style="text-align:left;"> $AABB $GME $AMC $AAPL $DKNG  
 
the AABB bAABBoon and ape cages have opened!!!! 
 
 
ABB bAABBoon and sore cages have opened!!!$DKNG! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:07:19 </td>
   <td style="text-align:left;"> $AAPL please pump apple to get us more gainz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:06:56 </td>
   <td style="text-align:left;"> $TSLA Elon pump going to surpass $AAPL in market cap lol. Tim time to pump lol 😂 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:06:42 </td>
   <td style="text-align:left;"> $AAPL nasdaq stalling at 14500.  So goes apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:06:27 </td>
   <td style="text-align:left;"> $AAPL shares of apple or shares of spy? 🧐🧐🧐🧐🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 02:00:46 </td>
   <td style="text-align:left;"> $AAPL They’re just fucking calls and puts now. Win win for the MM’s. Just screw retail over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 01:56:35 </td>
   <td style="text-align:left;"> $AAPL just chugging along... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 01:52:57 </td>
   <td style="text-align:left;"> 10 Information Technology Stocks Whale Activity In Todays Session https://www.billionaireclubcollc.com/10-information-technology-stocks-whale-activity-in-todays-session-11/ $AMD $AAPL $MSFT $ZS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 01:51:51 </td>
   <td style="text-align:left;"> $NVDA $TSLA $AAPL $GOOG $SHOP 
Bullish AF. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 01:50:36 </td>
   <td style="text-align:left;"> “Pensando’s chips are an increasingly important part of #data center design, as it becomes impossible to simply throw larger numbers of processors at demanding computing tasks. 
As regular chips scale up, the networking connections become a bottleneck~

$AAPL $INTC $MSFT $NVDA 

$AMD to acquire Pensando for networking tech - Protocol https://www.protocol.com/bulletins/amd-acquire-pensando-networking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 01:49:48 </td>
   <td style="text-align:left;"> $AAPL Rando on Reddit 
&amp;quot;I say S-4 drops today. Trump and Musk work hand in hand to bring truth and free speech back to the world and force the lefties to look at all the destruction they were playing a part of while beating them back with a very large stick! 💯🇺🇸💪. 🚀🚀🚀🚀🚀🚀&amp;quot; lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 01:48:02 </td>
   <td style="text-align:left;"> $TWTR imagine not entering Musk 3rd project, free speech before $100, lol

$TSLA $NVDA $AMD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-05 01:47:58 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:36:53 </td>
   <td style="text-align:left;"> $TSLA big lost for puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:36:35 </td>
   <td style="text-align:left;"> $TWTR $TSLA $AMC $GME it’s lit 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:35:34 </td>
   <td style="text-align:left;"> $F $TSLA Ford Mustang Mach-E EV Sales Jump Sequentially In March, Even As Numbers For Gas-Powered Version Drop 

https://newsfilter.io/a/83cde3570bd842e973357675200e4de2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:34:04 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-04 Daily Forecast Video: 
https://www.youtube.com/watch?v=C6er1kFYNEE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:32:51 </td>
   <td style="text-align:left;"> $TSLA and no one says Really ? What a Pump Scam </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:27:54 </td>
   <td style="text-align:left;"> $TWTR instead of $DWAC we can support this full heartedly 

Let&amp;#39;s go Brandon 

$SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:27:07 </td>
   <td style="text-align:left;"> $SPY Tesla without bitcoin or other investments is probably still unprofitable. Just two years ago they were still losing almost 10K per car. I don&amp;#39;t doubt costs for those cars have skyrocked in the last two years to say the least $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:26:45 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/fohsISRBGhU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:26:24 </td>
   <td style="text-align:left;"> Blatant securities fraud in plain sight $TSLA $CLPT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:26:17 </td>
   <td style="text-align:left;"> $TSLA All that you need to know…, Shorts haven&amp;#39;t covered a single share., amazingchat.stockmarketsignal.online </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:26:16 </td>
   <td style="text-align:left;"> $TSLA I have 25 calls ends 4/8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:26:04 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $AMZN $MSFT 

My thoughts on today&amp;#39;s mkt .... 

My Game Plan sent out Sunday morning focused on preparing for the coming earnings season and getting positioned in what I believe will be the winners and trying to avoid the losers. GOOGL is one name I wrote about as a stock I really like into earnings.

Tonight I&amp;#39;m sending out a blog to members titled &amp;quot;The Three Little Pigs&amp;quot;, where I break down three different tiers of tech/growth stocks, over 20 names. 

Which are in the brick house (strongest)  heading into earnings, and which reside in the other two houses.

For those yet to sign up, feel free to email me at jessielivermore1929@gmail.com 

?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:24:56 </td>
   <td style="text-align:left;"> $TSLA bears I’m warning you.. ppl that know more then us are betting on a large move up by 4/14.. betting around 50.5 million.. Glad I have calls.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:23:43 </td>
   <td style="text-align:left;"> $JMIA $PPGH $TSLA Account Challenge Update:-    
Start Date: March 1, 2022    
Starting Balance: $1,800    
Current Balance: $89,637    
Goal: $100,000 by end of April.   
Strategy: Swing Trade Options, Stocks    
     
Watch out for next play------ optionminning.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:23:10 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMD     ~Best-room on the net!! I&amp;#39;ve made over 35K by their alerts...   most-winning-chatroom.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:20:34 </td>
   <td style="text-align:left;"> $TSLA Elon Musk&amp;#39;s First Poll After Buying Twitter Stake: &amp;#39;Do We Want An Edit Button?&amp;#39; 

https://newsfilter.io/a/c6045eab0549e2558c63de6006522e1b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:19:25 </td>
   <td style="text-align:left;"> $TWTR we&amp;#39;re gonna be rich people 

$TSLA next project </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:18:35 </td>
   <td style="text-align:left;"> $TSLA a dollar might just fuck your main bitch,
That’s just how I feel. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:18:07 </td>
   <td style="text-align:left;"> $TSLA Buy all the EV companies that includes RIVN, NIO and more.. This administration is not going to encourage more drilling. I think our days of drilling for oil is over. This administration doesn&amp;#39;t want to be middle-east of oil for Europe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:17:45 </td>
   <td style="text-align:left;"> $TSLA any word on Tesla semi ? Possible wireless charging ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:17:01 </td>
   <td style="text-align:left;"> $TSLA really is unstoppable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:16:45 </td>
   <td style="text-align:left;"> $TSLA $1100 candle close really paid thank you Elon. Called it out on BETA DISCORD LINK IN BIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:16:00 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/xBI_M6VkDy0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:15:21 </td>
   <td style="text-align:left;"> $TSLA I think what we are all forgetting, is anyone who doesn’t like Tesla…has a tiny penis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:14:22 </td>
   <td style="text-align:left;"> $TSLA All that you need to know…, Shorts haven&amp;#39;t covered a single share, amazingchat.stockmarketsignal.online </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:13:53 </td>
   <td style="text-align:left;"> $TSLA at 2:36 today somebody bought a 36 million dollar call (850 strike) expiring 4/14/2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:13:01 </td>
   <td style="text-align:left;"> $TSLA jesus wth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:10:47 </td>
   <td style="text-align:left;"> $SPY  Bloomberg : Prices causing factory closures, half time working, even, energy shutting down factories and industrial manufacturing production.

Could be a fun one tomorrow, that PMI, you don&amp;#39;t think it could shock do you with running things up like you did today, bulls, noooo.

OH, even crazy  lithium prices causing probs for electric cars . Nothing&amp;#39;s insulated.  Shanghai is a something that will bring news every day shut down now. $LCID $GM

Tesla ER 20th should be a good one, for 777 ,  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:07:30 </td>
   <td style="text-align:left;"> $TSLA  Congrat bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:06:59 </td>
   <td style="text-align:left;"> $TSLA $AMD $SNAP $SQ the watchlist PRINTTTTEDDDD today. Unreal plays on the intraday option scalps. Join the discord for freeeee. Link in bio! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:06:22 </td>
   <td style="text-align:left;"> $TSLA Hillary is going to jail </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:04:44 </td>
   <td style="text-align:left;"> $TSLA looking good for a big drop tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:04:36 </td>
   <td style="text-align:left;"> $NIO can someone confirm if Elon bought 25% of $NIO today???!!! $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:04:30 </td>
   <td style="text-align:left;"> $TSLA strong morning dip….then back up again. Rinse &amp;amp; repeat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:04:10 </td>
   <td style="text-align:left;"> $TSLA https://youtube.com/shorts/xHAoCGFJ44E?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:04:06 </td>
   <td style="text-align:left;"> $TSLA this is also an insurance company </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:04:04 </td>
   <td style="text-align:left;"> $TSLA $ARKK 

Dumb question - but I’ve been wondering… when Cathie sells, it’s because she’s “a fiduciary,” right?  But what I don’t completely understand is if she’s a fiduciary, how come she invests in so many borderline type companies in the ARK funds?  I mean, why not buy and hold Tesla?  Would that not be a more profitable long term strategy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:03:32 </td>
   <td style="text-align:left;"> $TSLA 1200$ sell or hold?🤔🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:02:58 </td>
   <td style="text-align:left;"> $TWTR $TSLA $MULN $AMC $SPY 

In 1 hour I will be selecting the 10 winners. May God be with you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:02:54 </td>
   <td style="text-align:left;"> $TSLA quite is difference from yesterday with the crazy bears spouting how bad today was going to be.  Nice to hear nothing but crickets from them now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 09:01:36 </td>
   <td style="text-align:left;"> $MULN Im riding $TSLA  cash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:59:58 </td>
   <td style="text-align:left;"> $TSLA Cathy selling cause of bearish? Or portfolio rebalance? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:59:22 </td>
   <td style="text-align:left;"> $TSLA do it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:59:00 </td>
   <td style="text-align:left;"> $TSLA are my weekly 1150 calls done going up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:56:22 </td>
   <td style="text-align:left;"> $TSLA 1200 tomorrow let’s go bitches </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:56:21 </td>
   <td style="text-align:left;"> $TWTR $BTC.X $DOGE.X $TSLA 

⏳💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:54:24 </td>
   <td style="text-align:left;"> $TWTR $TSLA this man is about to rearrange twitter for fun 😂🤣 I think something wild is about to happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:54:14 </td>
   <td style="text-align:left;"> $TWTR is the new $TSLA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:52:27 </td>
   <td style="text-align:left;"> $TSLA $300 end of month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:51:56 </td>
   <td style="text-align:left;"> $TSLA so many catalysts have this stock running , I can’t keep up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:50:47 </td>
   <td style="text-align:left;"> $TSLA how elon will feel after being charged with securities fraud </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:50:45 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR $DWAC $CFVI 

Yes sir! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:50:33 </td>
   <td style="text-align:left;"> $TSLA please help me friends </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:50:19 </td>
   <td style="text-align:left;"> $TWTR $TSLA 
Daddy has spoken to the people. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:49:37 </td>
   <td style="text-align:left;"> $TSLA feel this will do ath before CPI next week. And run up again after CPI sell off. What do you all think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:49:17 </td>
   <td style="text-align:left;"> $TSLA possible another week off consolidation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:49:10 </td>
   <td style="text-align:left;"> $TSLA setting up to start running out the gate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:48:54 </td>
   <td style="text-align:left;"> $TSLA CYBERTRUCK APRIL 7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:48:24 </td>
   <td style="text-align:left;"> $TSLA I’m out sold all remaining positions - can’t wait to find an entry point again in a few weeks/months just feels overextended. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:47:10 </td>
   <td style="text-align:left;"> $TSLA TESLA SEMI APRIL 7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:46:47 </td>
   <td style="text-align:left;"> $TCBP ***BACK UP THE TRUCK ON TCBP!**

LOW FLOAT IPO FROM FEB- Opened at $4.50 sold down to .88 by underwriters with warrants at $4.25.

Scotland purchase 4.5 million shares along with Rennaisance Capital 4.5 million shares

Just look st the chart..ready to gain 500%

$TWTR $TSLA have Elon...TCBP will gain more

$BABA $JD gain on China potentially easing accounting standards 

Loading TCBP!!!  At $1.45 Easily Going to $5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:46:16 </td>
   <td style="text-align:left;"> $TSLA What’s up Doc? Wile E Coyote’s example how Bears feel Today and Will tomorrow. LOL….

https://youtu.be/OHmJ_t2EneM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:45:41 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s okay to play both side when it comes to options trading. However, I&amp;#39;ve learnt that never ever stand in front of the train ESPECIALLY TSLA. You&amp;#39;ll get wreck. It&amp;#39;s straight up loss porn if you bet against it. You bears know damn well there also upcoming catalysts. I mean why? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:45:16 </td>
   <td style="text-align:left;"> $TSLA 2k EOY! &amp;lt;3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:44:57 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR Welp, the T &amp;#39;n T explosive pump from Musk is vamos, back tomorrow to our regularly scheduled bear market rally killer.

Like I keep saying, &amp;quot;449.14 to 404.&amp;quot; It is happening, 460 is not happening in this climate, vice turns more and more, even, a twirl or two, as we squeeze Jamie Dimon &amp;amp; (bullish) banks company toward bad guidance for Q2, as they report next week &amp;amp; we&amp;#39;re 404 day before CPI, 11th, 1st day banks report, not so coincidentally.

And, when banks ho, everything goes. $IWM 

Do own DD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:44:30 </td>
   <td style="text-align:left;"> $TSLA about to drop😂😂😂📉🕳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:43:23 </td>
   <td style="text-align:left;"> $PPGH $JMIA $TSLA $SOS Account Challenge Update:-    
Start Date: March 1, 2022    
Starting Balance: $1,800    
Current Balance: $89,637    
Goal: $100,000 by end of April.   
Strategy: Swing Trade Options, Stocks    
     
Watch out for next play------ optionminning.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:43:04 </td>
   <td style="text-align:left;"> $TSLA $1200! at Tanagra! DARMOK! When the walls fell! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:41:40 </td>
   <td style="text-align:left;"> $TSLA FRIDAY WILL BE HISTORIC 15 - 20 % EASY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:41:28 </td>
   <td style="text-align:left;"> $TSLA Lol Shorts , how did you do today? Did ya take option B? ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:41:26 </td>
   <td style="text-align:left;"> $TSLA 

https://twitter.com/burggrabenh/status/1510763372509384712?s=24&amp;amp;t=G6eZBL3mSGgYWOE4B7gCLw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:41:20 </td>
   <td style="text-align:left;"> $TSLA this thing dropped about $4 right at the last couple minutes before 8 pm. was there news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:41:00 </td>
   <td style="text-align:left;"> $TSLA $SPY Shitting on bears like $NIO shits on its share holders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:39:28 </td>
   <td style="text-align:left;"> $TSLA $SPY shitting on bears all day everyday day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:38:56 </td>
   <td style="text-align:left;"> $SPY $TWTR $TSLA  I&amp;#39;m coining the term &amp;quot;eshlong&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:38:39 </td>
   <td style="text-align:left;"> $TSLA now I just buy some of this every few days without even checking the charts or timing it. Too busy with other things and it will be fine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:38:03 </td>
   <td style="text-align:left;"> $TSLA stock analysis based on today&amp;#39;s closing  price 

https://youtu.be/_FyVijyw2Pw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:37:14 </td>
   <td style="text-align:left;"> $TWTR $TSLA elon should buy something way cooler like $GME or $AMC thatd be way more fun for EVERYONE, him, retail, sec, shorts, everyone would have loads of fun all of a sudden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:36:36 </td>
   <td style="text-align:left;"> latex42126d21f125c97a98a0c78dced7bb33NNOX 12c 129%
@MommasOptions 
$ATER 3c 444% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:35:07 </td>
   <td style="text-align:left;"> $TSLA $TWTR All the Youtube Guru&amp;#39;s say Twtr is not a buy and will resend  it always does after a huge gap up!  looking for retest of 40- 45 area tomorrow. Massive Profit taking on a stock that Constantley BLEEDS THE NUMBERS EVEN AT IT&amp;#39;S BEST HEIGHTS!   
On the Flip side $DWAC should Flip to the upside $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:35:00 </td>
   <td style="text-align:left;"> $TSLA this going up or down tomorrow? Down 5 bucks after hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:34:53 </td>
   <td style="text-align:left;"> $RIDE $CHTR $TSLA $LCID $GOEV 
Russia’s killing spree in Ukraine will have long lasting effects well after they withdraw. Sanctions will never be lifted. The world is now a different place. We will all be driving EV’s soon enough. Won’t have a choice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:34:43 </td>
   <td style="text-align:left;"> $TSLA  we call this,  absorption </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:34:10 </td>
   <td style="text-align:left;"> $TSLA easily gap down tomorrow rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:32:27 </td>
   <td style="text-align:left;"> $SPY  $TSLA  theres one thing these markets reward its persistence. Gotta give it to em </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:32:07 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-04 Chart Analysis Video: 
https://www.youtube.com/watch?v=FjJEEbazujM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:31:09 </td>
   <td style="text-align:left;"> $TSLA unfn believable 🤦‍♂️

Nothing stopping this from seeing ATH’s…even after big delivery miss yesterday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:30:59 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMD      ~Best-room on the net!! I&amp;#39;ve made over 35K by their alerts...       most-winning-chatroom.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:30:57 </td>
   <td style="text-align:left;"> $TSLA Twitter news gave a nice boost to Tesla stock otherwise it would have gone down a little. He knows how to distract bears from real news. LOL . Love hime </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:30:56 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMD   ~$1800 into $40k in the last 30 days; If you really want to make huge profits on trading then;  Join this winning chat:..     winning-alerts-options.stockmarketmovers.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:30:44 </td>
   <td style="text-align:left;"> $TSLA  Below is the unusual SweepCast activity that I mentioned in my last post. sweepcast.com/ #stockstowatch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:30:44 </td>
   <td style="text-align:left;"> $TSLA 1200 TOMORROW 💎🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:30:40 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:30:22 </td>
   <td style="text-align:left;"> $TSLA we welcome all dips wit open arms </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:29:54 </td>
   <td style="text-align:left;"> $TSLA so bullish Elon sells Tesla for Twitter. This should be up 10% over 100b market cap WTF IS WRONGWITH THIS STOCK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:29:24 </td>
   <td style="text-align:left;"> $TSLA Great Bullish Setup!! The stock had a broken resistance level after retesting this highlighted zone with a big green candle and huge volume. he RSI has supported an uptrend. sweepcast.com/ #stockstowatch $TWTR, $LULU, $U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:29:21 </td>
   <td style="text-align:left;"> $TSLA It gave a nice entry in the morning around $1170. Can&amp;#39;t add anymore ,tapped out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:28:25 </td>
   <td style="text-align:left;"> $TSLA tesla bear saying something good about Elon🧐🧐🧐🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:28:20 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $900.00 Call for Thursday, April 14, 2022. Roughly 27 Million dollars! 💰💰💰 MASSIVE MONEY 💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:28:17 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $1200.00 Call for Friday, April 29, 2022. Roughly 1 Million dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:28:05 </td>
   <td style="text-align:left;"> $TSLA $SPY $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:28:03 </td>
   <td style="text-align:left;"> $TSLA 
 
BTFD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:26:29 </td>
   <td style="text-align:left;"> $TSLA institutes are about to drop shares if that Shanghai factory stays closed all week but who knows maybe Tesla might go green on the news 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:26:12 </td>
   <td style="text-align:left;"> $TSLA keep &amp;#39;em comin... 😈🔥🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:25:14 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:24:11 </td>
   <td style="text-align:left;"> $TSLA The only way this drops is if people start selling their shares. Hold everything. Sell nothing and up we go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:24:07 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR $DWAC $CFVI 

This is a PSA: 🚨 

I have a little poem I would love to share with you 

The bulls want a pump 

The bears want a dump 

When you put it all together, you get a thump

And lastly I want to say that I love Donald Trump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:23:07 </td>
   <td style="text-align:left;"> $TWTR bruh this but tesla gonna soar maybe new ath $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:22:34 </td>
   <td style="text-align:left;"> $TSLA manifest ATH TESLA! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:22:34 </td>
   <td style="text-align:left;"> $TSLA why having the worst bearish after an “overextended day” tomorrow when you can start it today 😳😁
Thank “trader Musk” for it😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:22:25 </td>
   <td style="text-align:left;"> $TSLA Cathy trimmed her bush today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:22:05 </td>
   <td style="text-align:left;"> $TSLA death to all bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:21:38 </td>
   <td style="text-align:left;"> $TSLA oh I didn&amp;#39;t buy twtr yet... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:21:11 </td>
   <td style="text-align:left;"> $TSLA What a bloodbath for the bears.  They&amp;#39;ve been warned for a while now.  Silly bears. 
 
....they never learn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:21:01 </td>
   <td style="text-align:left;"> $TSLA It doesn&amp;#39;t matter what retail bulls and bears think however convincing the argument ... Real impact is made only by institutions who can affect stock price... so who cares on what u think of how overinflated the P/E is, cars produced, tesla  accidents and other low quality opinions when institutional investors could care less.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:20:40 </td>
   <td style="text-align:left;"> $TSLA 1250 by 9:30 tomorrow, 600 by 2:30 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:20:26 </td>
   <td style="text-align:left;"> $TSLA ath tomorrow!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:20:06 </td>
   <td style="text-align:left;"> $TSLA $750 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:19:26 </td>
   <td style="text-align:left;"> $TSLA 1,250 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:18:11 </td>
   <td style="text-align:left;"> $TSLA I Cathie woods is be the biggest joke on wallstreet... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:16:58 </td>
   <td style="text-align:left;"> $TSLA  if one bear says futures are red i&amp;#39;ll get the best night sleep ever!!! please ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:16:36 </td>
   <td style="text-align:left;"> $XBI $TSLA ... I hate train wrecks, musk is moderate visionary, top 1 mgmr... fight putin, put me in musk sling, moon bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:16:21 </td>
   <td style="text-align:left;"> $TSLA what’s going on with the all chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:15:56 </td>
   <td style="text-align:left;"> $MVST $TSLA&amp;#39;s Elon Musk will have 9.2% equity of MVST soon. &amp;quot;MUSK&amp;quot; is very similar to &amp;quot;MVST.&amp;quot; There are &amp;quot;M&amp;quot; and &amp;quot;S&amp;quot;! Maybe $MS&amp;#39;s Jonas is acting like Bear but the result will be x100 soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:14:42 </td>
   <td style="text-align:left;"> $TSLA Tesla is luxury car company. And they need to sell more than 10 million luxury cars annually to match the current average SP P/E ratio. Come on this is not a $1k iphone you can change every year. Do your math bulls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:14:35 </td>
   <td style="text-align:left;"> $TSLA Elon’s great but to many idiot democrat liberals buy his cars. That’s why I would never buy one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:14:00 </td>
   <td style="text-align:left;"> Measured over the past 5 years, $TSLA shows a very strong growth in EPS. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:13:51 </td>
   <td style="text-align:left;"> $TSLA this is going to be bears on a 1% dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:12:12 </td>
   <td style="text-align:left;"> $TSLA I still can’t believe I’m seeing BEARS in here lmaooooo 
 
If they thought today was bad. All week us BULLS are partying !!!  
 
Tomorrow is going to be Mortal Kombat “finish him “for the bears. All time high will be taken out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:10:50 </td>
   <td style="text-align:left;"> $TSLA live look at Tesla bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:08:30 </td>
   <td style="text-align:left;"> $TSLA Congrats Bulls! Eat 💩 Bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:07:44 </td>
   <td style="text-align:left;"> $TWTR Okay Twitter is now officially a new meme stock along with $TSLA, $GME, and $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:04:58 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $150.00 Put for Friday, December 16, 2022. Roughly 171 Thousand dollars! 💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:04:45 </td>
   <td style="text-align:left;"> $TSLA Tesla earnings on 4/20 I see what he did there 💨 🚀👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:04:22 </td>
   <td style="text-align:left;"> $TSLA 

Tesla’s first quarter sales show the EV revolution could be upon us!! 

🙏🏻🐉🦅

https://apple.news/A9QBwBQCpRnOeY03f39Noww </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:04:14 </td>
   <td style="text-align:left;"> $TSLA tomorrow, this will give back today&amp;#39;s gains. Shanghai factory to remain closed until further notice. Covid infections have surpassed 10,000 in Shanghai for the first time. Good luck, lemmings!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:04:03 </td>
   <td style="text-align:left;"> $TWTR  
$TSLA  
 
There’s a lot more opportunity in selling technology like TWTR than selling cars and Elon knows that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:03:49 </td>
   <td style="text-align:left;"> $RBLX LONGS AND SHORTS. The company just filed the CEO’s comp plan. Go see for yourself. He gets ZERO vest of 750,000 shares unless the stock has average of 90 days above $165 between now and March 2 2023. 

SO less than 12 months from now the stock has to be above $165 for 3 of those. That’s more than a TRIPLE from here… I don’t know how this doesn’t rocket… huge huge huge long. $TSLA Musk got paid the same way. Guess where the stock went mofos? So f’n long here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:01:58 </td>
   <td style="text-align:left;"> $TSLA love this stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:01:37 </td>
   <td style="text-align:left;"> $TWTR $TSLA you know why people love Elon? Cause he makes them rich. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 08:00:12 </td>
   <td style="text-align:left;"> $TSLA 

Bills are getting paid this month baby🔥🔥
🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:59:56 </td>
   <td style="text-align:left;"> $TSLA Here is the Chart Bulls 🔎 
 
Breakout or Breakdown from here !? 📈📉 
- 
https://discord.com/invite/uQ5UXZW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:59:51 </td>
   <td style="text-align:left;"> $tsla $lCID $rivn $dwac $nio $ GGPI  Polestar coming ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:59:35 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:59:07 </td>
   <td style="text-align:left;"> $TSLA ELONA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:58:09 </td>
   <td style="text-align:left;"> $CEI hmmm latexc99ca6b551e2a0b315cd0677a69d69f8LCID
$NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:54:43 </td>
   <td style="text-align:left;"> $TSLA play the short attempts....your probability of winning goes up the faster this does. So just play a defensive strategy and dont hold when spot you chose ended up just a headfake to higher. That is how you try to short this run for a correction scalp. You dont decide when it comes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:54:20 </td>
   <td style="text-align:left;"> $TSLA Hmmm “Biggest party ever” What better of a place to announce the production of the Cybertruck at Austin opening 🤔🤔🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:52:52 </td>
   <td style="text-align:left;"> $TSLA Does anybody (but Meet Kevin) have enough TSLA shares? I&amp;#39;ve been buying steadily for what seems a month (including this AM at $ 1078). Got the dry powder for a dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:52:28 </td>
   <td style="text-align:left;"> Camber Energy Investors Overwhelm Tesla Bulls In ‘March Madness’ Competition https://www.billionaireclubcollc.com/camber-energy-investors-overwhelm-tesla-bulls-in-march-madness-competition-2/ $CEI $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:49:31 </td>
   <td style="text-align:left;"> $TSLA beat estimates on production despite global shortage issues, opened Berlin, announced split, Austin party Thursday!!! ATH&amp;#39;S INCOMING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:49:03 </td>
   <td style="text-align:left;"> $TSLA shout out to @cellojoe for telling me I wouldn’t feel good for having calls over this past weekend. Shame on you!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:46:59 </td>
   <td style="text-align:left;"> $TSLA just remember it is totally okay to emote your feelings and reasoning on the board. Just remember to dont include them into your trading. Today the super stubborn and logical bear traders lost a ton continually believing a cool off was due. Everyone shldve dropped bearish positions at 1100 and if didnt catch a bull scalp and were trying to catch a cool off made the mistake of trusting reason over the obvious push algo on play literally all day. This stock has killed many logical bulls and bears. 

Dont be a hypocrite either. You have no issues when the ridiculous swing goes your way but its criminal if it doesnt. I see bulls and bears do this regularly. Lets just face it....it is a illegal and corrupt. Reality is there was no logical reason for any of it. Got to be disciplined and open minded to learn. It was clear on charts break 1100 and 1175 is your next shot. As soon as they snapped back you had to trust tape not logic.  Just some friendly tips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:46:18 </td>
   <td style="text-align:left;"> $TWTR $TSLA how’s this work 

“The SEC mandates that anyone who acquires more than 5% of a company’s common shares disclose their holdings within 10 calendar days. Musk signed his filing 21 days after March 14.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:46:16 </td>
   <td style="text-align:left;"> Stock Market Recap ! $TSLA Price Targets! $1200 is that you playa? https://youtu.be/Zgn1XSTZZz8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:46:08 </td>
   <td style="text-align:left;"> $TSLA twitter took all the delivery gains today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:45:04 </td>
   <td style="text-align:left;"> $TSLA bears are disgusting and they all deserve to lose their stupid puts. Disgusting wow. They were out in full force this weekend. 

Your puts are shot. There’s no
Chance. And yes, it can keep going up. Stupid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:42:20 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/YeB4YT-gDrc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:42:18 </td>
   <td style="text-align:left;"> #WallStreetBets Top Stock Mentions Today #WSB  (NFA)             
$GME $TWTR $TSLA $AMD $PLTR  
            
financials.fyi/sentiment/reddit/wallstreetbets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:41:33 </td>
   <td style="text-align:left;"> Peak profit for the last 6 expired option alerts for $TSLA 519.07| 6.10| 7.14| 138.55| 110.04| 309.40| </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:41:32 </td>
   <td style="text-align:left;"> $TSLA BIGGEST PARTY ON EARTH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:39:52 </td>
   <td style="text-align:left;"> $TSLA so is there a split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:39:44 </td>
   <td style="text-align:left;"> $TSLA TESLA Stock Price  Prediction and Analysis for Tuesday  April 5
https://youtu.be/Cl678Hm33Og </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:38:46 </td>
   <td style="text-align:left;"> $TWTR $TSLA 

I am a TSLA bull but honestly don’t get this TWTR rally. 

TSLA will continue going up, possibly near or even above ATH soon. 

But, Elon has a 10% stake in TWTR, so what?? 

Just saying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:38:25 </td>
   <td style="text-align:left;"> $SPY $TSLA #sec </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:38:03 </td>
   <td style="text-align:left;"> $TSLA musk made sure to announce twitter holding today over ten days late to manipulate this stock. His brother must be selling shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:38:00 </td>
   <td style="text-align:left;"> $NFLX, $TSLA and $HPQ are the top gainers in the S&amp;amp;P500 for the day. https://www.chartmill.com/stock/stock-screener?v=3&amp;amp;f=ind_22&amp;amp;s=pt&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_top_S&amp;amp;P500_gainers&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:37:14 </td>
   <td style="text-align:left;"> $TSLA if this hits $117” tomorrow i will give everyone who likes this post $950 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:37:11 </td>
   <td style="text-align:left;"> $TWTR gap up then halt up

$TSLA 2.0 Inc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:36:15 </td>
   <td style="text-align:left;"> $TSLA I am a bear and I have to say the after hour price action does not mean anything right now. But if it were the bulls they would be saying someone knows sth.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:36:02 </td>
   <td style="text-align:left;"> $TSLA Michael burry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:35:49 </td>
   <td style="text-align:left;"> $TSLA How about that Mark Spiefel&amp;#39;s rant on Zerohedge a few days ago how do they sleep? Oh I get it he us betting his investors money not his so he remains ultra bearish he tells his clients 1 day I will be wait just stay with me just like Gordon Johnson LoL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:35:34 </td>
   <td style="text-align:left;"> $TSLA 

Seriously !

🙏🏻🐉🦅

https://youtube.com/shorts/J6amXyPugoU?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:34:05 </td>
   <td style="text-align:left;"> $TSLA can we get a dip prior to Giga Austin? Cyber Truck update? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:33:29 </td>
   <td style="text-align:left;"> $tsla $LCID $RIVN  $nio $xpev $ GGPI Real Global EV coming ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:33:13 </td>
   <td style="text-align:left;"> $TSLA now your telsa will tweet you when it&amp;#39;s ready to go for a drive, have it&amp;#39;s oil changed or slides into your wife&amp;#39;s dms. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:32:55 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/fSCzbjgRaQw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:31:48 </td>
   <td style="text-align:left;"> $GGPI $TSLA 100k vs @PolestarCars 65K

Can’t beat up Tesla now but @PolestarCars catching them up very fast in only 2 years 😉 

$GGPI + @PolestarCars = $PSNY soon on Nasdaq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:31:41 </td>
   <td style="text-align:left;"> $TSLA some of these bears sound like they are on the verge of a mental breakdown lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:30:30 </td>
   <td style="text-align:left;"> $TSLA If you are still saying bearish stuff today, you are basically the worst actor I&amp;#39;ve ever seen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:29:22 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SPY $QQQ 

Tesla broke out the bull fake setup we discussed&amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:28:56 </td>
   <td style="text-align:left;"> Daily Market Recap for Monday 4/4/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/EU7wmaWALrQ

$AMD $AAPL latex89efbf92803f818a4d0eae6d3102a3b3$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:26:09 </td>
   <td style="text-align:left;"> $TSLA acquiring enough shares to make himself the majority shareholder of Twitter was not to prove some point. He is probably entering into some sort of settlement agreement with the SEC to avoid prosecution for the securities fraud stunt he pulled back in November - December 2021. In exchange, he has to step down as Tesla&amp;#39;s CEO. He will most likely take over Twitter once he is no longer with Tesla. imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:25:55 </td>
   <td style="text-align:left;"> $TSLA wait until auto giants like GM, Ford, Toyota, ETC&amp;#39; 
Are going to come out with EV&amp;#39;s and better ones than tesla, oh that&amp;#39;s gonna be a bummer to the ELON cult  
 
Can&amp;#39;t wait </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:25:09 </td>
   <td style="text-align:left;"> ⚠️Big Video 
 
* $MULN hires a $TSLA employee news 
* $FERN unknown news coming soon 
* $ILUS FULL Breakdown of the PR/Q&amp;amp;A all in one! 
* More at the end 
 
👉(https://youtu.be/pRIrVY-c4mA)👈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:22:53 </td>
   <td style="text-align:left;"> $TWTR $200

$TSLA 2.0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:20:43 </td>
   <td style="text-align:left;"> $CYN $TSLA could buyout cyngn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:20:43 </td>
   <td style="text-align:left;"> $TSLA for now I&amp;#39;m short/bearish. Can switch to being long above 1150. Only problem is if it gaps above 1150 and doesn&amp;#39;t retest, then shorts can get squeezed up to 1170+ maybe.

(Long term bullish) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:20:21 </td>
   <td style="text-align:left;"> $TSLA CYBERTRUCK news on thursday ... ELON defiantly has something up his sleeve </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:19:29 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/hprYSsfyQFw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:19:28 </td>
   <td style="text-align:left;"> $TSLA looking good I don&amp;#39;t have any doubts this taps 1200 soon at least. Huge play called today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:19:20 </td>
   <td style="text-align:left;"> $TSLA what would you Tesla Fanboys do if Musk decided to step down as CEO of Tesla? I am curious.  Would you still keep all of your shares of Tesla or sell a portion? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:19:13 </td>
   <td style="text-align:left;"> $TSLA RSI going to be pinned all week  
 
all time high for RSI is 95.34 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:18:14 </td>
   <td style="text-align:left;"> $TSLA Tesla is definitely a bubble. However the technicals don&amp;#39;t seem to care </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:17:16 </td>
   <td style="text-align:left;"> $TSLA weekly chart 😁🚀🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:15:26 </td>
   <td style="text-align:left;"> $TSLA the last all time high before 1243 was 1124 and before that around 900, when new all time highs have been created historically with Tesla they show no recognition for the previous all time high ,no resistance.Check the chart.Therefore I don&amp;#39;t see much point setting sell orders at specific prices ,but rather just keeping a general feelnin the stock day to day.Right now it&amp;#39;s very strong bullish still. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:15:07 </td>
   <td style="text-align:left;"> $TSLA 

Man that 4/20 can bring 69 surprises or so !! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:14:30 </td>
   <td style="text-align:left;"> $TSLA Small bears don&amp;#39;t get it. It&amp;#39;s big bears that are mostly buying now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:12:29 </td>
   <td style="text-align:left;"> $TSLA stock is HOT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:12:08 </td>
   <td style="text-align:left;"> Thanks uncle Elon! $TWTR $TSLA $QQQ $BTC.X $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:10:39 </td>
   <td style="text-align:left;"> $TSLA TSLA Sneaky Snake Trading Strategy,,, Technical Analysis on TSLA  https://www.youtube.com/watch?v=xTcHDhqe75s&amp;amp;t=1s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:10:26 </td>
   <td style="text-align:left;"> $TSLA will it just sail through 1243 like it means nothing or will there be resistance ,will there be significant resistance at 1200 ,it doesn&amp;#39;t seem to be slowing down yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:08:39 </td>
   <td style="text-align:left;"> I guarantee this guy kills himself when this is over $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:08:27 </td>
   <td style="text-align:left;"> $TSLA ill be honest i would never expected this. The tape read sell the news all over it last week. Not even a real beat on deliveries and extended china shutdown. Its just straight baffling to me the pace they are rallying the stock. I dont understand the rush but is what it is and cant fight algos. 1175 is your possible short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:07:58 </td>
   <td style="text-align:left;"> $TSLA crazy if buying here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:06:38 </td>
   <td style="text-align:left;"> $TSLA 

No payroll tax this quarter should she higher operating / profit margin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:06:35 </td>
   <td style="text-align:left;"> $TSLA tulip mania !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:05:58 </td>
   <td style="text-align:left;"> $TSLA does Tesla still plan on opening factory in Austin this week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:05:51 </td>
   <td style="text-align:left;"> $TSLA Drop to $500 already you POS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:05:31 </td>
   <td style="text-align:left;"> $DOGE.X latexcd593abe76daf47d0742338c4e520155NFLX 380 -&amp;gt; 393.52. If above 398, then 409 
$JMIA 10.48 -&amp;gt; 12.2. If above 12.39, then 13.3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:04:23 </td>
   <td style="text-align:left;"> German $TSLA cars are also garbage! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:04:14 </td>
   <td style="text-align:left;"> $TWTR How many of you over at $DWAC  reactivated your Twitter account today? 

Asking for a friend $TSLA $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:04:06 </td>
   <td style="text-align:left;"> $TSLA Hertz said Monday it will purchase 65,000 electric vehicles from upstart Tesla rival Polestar. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 07:00:08 </td>
   <td style="text-align:left;"> $TSLA  You ever wonder why did elon musk move Earnings announcement from 4/26 to 4/20 ??? Because we&amp;#39;re going higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:59:32 </td>
   <td style="text-align:left;"> ⭐️ $TSLA Momentum Alert   
🚀 Increase from alert: +35.46% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:59:02 </td>
   <td style="text-align:left;"> $TSLA Red to Green move:  -1.11%  to +5.13% https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan&amp;amp;type=redtogreenDaily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:58:59 </td>
   <td style="text-align:left;"> $TSLA You had a once in a lifetime market break to buy and hold in the 690s, if you missed that shot and are now whining about the pe ratio and decide now to short because of this current run... you deserve everything that is coming to you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:58:19 </td>
   <td style="text-align:left;"> $TSLA Ukraine became irrelevant so we get our money back now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:58:18 </td>
   <td style="text-align:left;"> $TSLA 1208+ tomorrow or Wednesday. Before we shoot for 1300 after giga Austin and ER. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:57:38 </td>
   <td style="text-align:left;"> $NIO $TSLA $XPEV $F $BYDDF real BEV’s on the roads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:56:28 </td>
   <td style="text-align:left;"> $TSLA barely hitting mainstream https://youtu.be/UDE9zmCMlxA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:54:40 </td>
   <td style="text-align:left;"> $TSLA …What’s Up Homie! 🦇👊🏿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:53:19 </td>
   <td style="text-align:left;"> $TSLA if we continue to squeeze, we might just get a split </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:53:07 </td>
   <td style="text-align:left;"> $TSLA big news coming thursday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:51:47 </td>
   <td style="text-align:left;"> $TSLA right now market is in state of disbelief, so higher we go 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:50:39 </td>
   <td style="text-align:left;"> $TSLA Another split, Another split!!!!!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:50:38 </td>
   <td style="text-align:left;"> $TSLA 5:1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:50:25 </td>
   <td style="text-align:left;"> $TSLA when do we expect the split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:50:01 </td>
   <td style="text-align:left;"> $TSLA lets go split!  10:1? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:49:40 </td>
   <td style="text-align:left;"> $ANY tomorrow Gamma squeeze!!! 🚀 $TWTR $TSLA $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:49:37 </td>
   <td style="text-align:left;"> $TSLA 1134 support check in the am if we don&amp;#39;t open over 1150 then next stop 1180 for tomorrow  
1200 wed 
1243-1300 Thursday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:48:30 </td>
   <td style="text-align:left;"> $TSLA based on my model we will drop 9.74% tomorrow. That would start a 27.2% sell off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:47:54 </td>
   <td style="text-align:left;"> $TSLA the institutions just started adding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:47:44 </td>
   <td style="text-align:left;"> $SPI BUY NOW!  
 
$TSLA is buying batteries from $SPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:47:37 </td>
   <td style="text-align:left;"> $TSLA If bitty can break 50k tonight tessie going to open over 1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:47:22 </td>
   <td style="text-align:left;"> $TSLA Tsunami of Pain days ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:46:45 </td>
   <td style="text-align:left;"> $TSLA $1250 eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:46:08 </td>
   <td style="text-align:left;"> $TSLA Bearish on Tesla in April? Before earnings after 80% production increase and board meeting about stock split? Please bears do some homework. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:45:30 </td>
   <td style="text-align:left;"> $TSLA calls to 1170 then DUMP IT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:44:34 </td>
   <td style="text-align:left;"> $TSLA day 9:38 am spring Mmm tasty lefty hits a triple. GO Padres! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:43:23 </td>
   <td style="text-align:left;"> $TSLA 6% what is this? Gains for ants? 

Bring the paaaaaaain! 10% daily or bust! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:43:21 </td>
   <td style="text-align:left;"> $TSLA where the dude that dropped 35k on 1070 puts for weekend swing expecting it to turn to 100k today ? 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:42:23 </td>
   <td style="text-align:left;"> latex0ee330c3c973f58a9814e3e6258fcd89AMZN 52 
 
Ford 4 
GM 6 
Toyota 10 
 
$TSLA 234 😆😆😆😆😆😆😆 
 
Nothing wrong with this picture eh&amp;#39;?  &amp;quot;They&amp;#39;re more than a car company.&amp;quot;   
 
Your own CEO said the stock was &amp;quot;too expensive&amp;quot; -- BEFORE THE SPLIT -- a thousand percent ago..   
 
When this bubble pops -- AND IT WILL -- TSLA will be one of the worst hit tickers in the history of the stock market...  I GUARANTEE IT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:41:50 </td>
   <td style="text-align:left;"> $TSLA shitting on bears like shitting in the bowl. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:41:11 </td>
   <td style="text-align:left;"> $TWTR 

$200 imminent on democracy 

$TSLA $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:37:35 </td>
   <td style="text-align:left;"> $TWTR  
$TSLA  
 
Lot more opportunity with TWTR vs TSLA.  Plus no supply chain issues here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:37:02 </td>
   <td style="text-align:left;"> $CEI Benzinga bullish bracket. Sign in and vote. Bring $TSLA past 18 months profit to $CEI before it&amp;#39;s too late. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:36:58 </td>
   <td style="text-align:left;"> $TSLA $1420 end of week mark it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:36:38 </td>
   <td style="text-align:left;"> ‘We’re Not A Cathie Wood Part Two’: Insights From Sylvia Jablonski, The New CEO At Defiance ETFs https://www.billionaireclubcollc.com/were-not-a-cathie-wood-part-two-insights-from-sylvia-jablonski-the-new-ceo-at-defiance-etfs/  $TSLA $XPEV $BYDDY $LI $COIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:36:32 </td>
   <td style="text-align:left;"> $CSIQ $sol $fslr $AAPL $tsla csiq - Canadian Solarabout to blow the roof off this joint - easy 25-50% within a year .. double within 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:36:28 </td>
   <td style="text-align:left;"> $TSLA 720 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:36:01 </td>
   <td style="text-align:left;"> $TSLA but bears TOLD ME SO that this will go to $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:35:18 </td>
   <td style="text-align:left;"> $Tsla $LCID $Rivin $nio $GGPI Polestar coming ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:35:14 </td>
   <td style="text-align:left;"> $TWTR pssst.... Hey bears... Elon held through 2 $TSLA splits before he was pretty much &amp;quot;forced&amp;quot; to sell.

Go back to your racist af $DWAC platform </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:35:04 </td>
   <td style="text-align:left;"> $TSLA When stocktwits IPO? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:34:46 </td>
   <td style="text-align:left;"> $AMC They tried so hard to keep it from breaking the wedge but here we are. $gme $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:34:32 </td>
   <td style="text-align:left;"> $TSLA Tesla killing it against all odds. COVID shutdowns, material shortages… still rockin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:33:54 </td>
   <td style="text-align:left;"> $TWTR oooo yeah Elon $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:33:09 </td>
   <td style="text-align:left;"> $TSLA oh me oh my!  I listened to the bears on here and will be missing my rent!  Again! 
 
On a serious note--the chart was looking bearish, but I&amp;#39;m pleasantly surprised with the reaction to meeting delivery expectations while every other car company appears to have missed significantly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:33:08 </td>
   <td style="text-align:left;"> $TSLA long over/short under 1128 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:30:55 </td>
   <td style="text-align:left;"> $GGPI    
Great news today, but rest assumed this is only the start! Remember the impact from when the hertz deal with $TSLA was announced?  
https://youtu.be/1QBJHN61nUY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:30:29 </td>
   <td style="text-align:left;"> $TSLA Everyone should keep reposting. Because this is really going to be the catalyst imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:30:16 </td>
   <td style="text-align:left;"> $TSLA if Tesla made a dildo, you guys would would have it up your ass by the weekend. Fucking sheep. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:30:01 </td>
   <td style="text-align:left;"> $TSLA 
An enormous bullish risk reversal looks to be closing in the 4/14 expiry at 850 strike:
-1200 of the 850 puts are being bought back to close for $68k
-1200 of the 850 calls are selling to  close for $36MM 

At the same time, another bullish risk reversal looks to be opening in the 5/20 expiry at 1150 strike:
-short the 1150 puts to collect $11.8MM in premium
-long the 1150 calls for $11.8MM premium </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:29:39 </td>
   <td style="text-align:left;"> $TSLA price prediction after earnings report beat? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:28:55 </td>
   <td style="text-align:left;"> $TSLA Do you haters know your truly want to love Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:28:52 </td>
   <td style="text-align:left;"> $DIS check out JXN, fwd p/e 2.16, fwd eps 20.00. Jackson Financial, thank me later. 👍🏻 $AAPL $WFC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:28:18 </td>
   <td style="text-align:left;"> $TSLA Just want to get all the haters off my feed sorry everybody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:27:59 </td>
   <td style="text-align:left;"> $TSLA Levels Plotted ✅ 
 
With earnings on 4/20 we could see a pullback tomorrow &amp;amp; then a pre earnings run up after 📈 
 
https://discord.com/invite/uQ5UXZW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:27:54 </td>
   <td style="text-align:left;"> $TSLA let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:27:23 </td>
   <td style="text-align:left;"> $TSLA This is just the beginning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:27:04 </td>
   <td style="text-align:left;"> $TSLA Going to be huge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:26:38 </td>
   <td style="text-align:left;"> $TSLA Don’t bet against the cyber rodeo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:26:21 </td>
   <td style="text-align:left;"> $TSLA can&amp;#39;t wait for the day that all these little Elon fanboys realize how much of a choad Elon is. My buddy has a Tesla and it&amp;#39;s a giant piece of shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:25:16 </td>
   <td style="text-align:left;"> $TSLA The New Tesla(Polestar) is Coming. Hertz Global to Buy 65,000 Electric Vehicles From Swiss Carmaker Polestar(GGPI)🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:25:14 </td>
   <td style="text-align:left;"> $PHUN https://t.me/phunpham/29716
What about all this $TSLA talk?  Does Elon really have the power to change $TWTR and would $DWAC then just be the home for the fringe elements of the conservative movement, they had their chance to bury Twitter and waited too long unless the talk of a merger comes to fruition. I’m still waiting to see how Phunware ties all these groups together and hoping I can hold on long enough, stuff’s happening pretty fast now though so shouldn’t be long now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:24:28 </td>
   <td style="text-align:left;"> $TSLA up (3) Gordy’s today plus Austin coming up this Thursday too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:23:45 </td>
   <td style="text-align:left;"> $AMC this better shoot up. I gotta move the gains into $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:22:47 </td>
   <td style="text-align:left;"> $TSLA up over $18K today. Thank you teslaaaa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:22:45 </td>
   <td style="text-align:left;"> $TSLA another banging day let’s freaking go bulls!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:22:24 </td>
   <td style="text-align:left;"> $TWTR shorts have to cover before close 🔥🚀 $TSLA $AMC $GME 

TWITTER WILL BE THE BEST GAMMA SQUEEZE EVER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:22:14 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m selling a cyberquad for kids HTX area lmk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:21:35 </td>
   <td style="text-align:left;"> $NIO $BABA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:21:06 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:21:04 </td>
   <td style="text-align:left;"> $TSLA $TLRY Start trading over 5 month ago and i lost all of money, Now I&amp;#39;ve made over $450K+ profits after join their chat room and using their alerts. Highly recommended,,It&amp;#39;s free joining🚀  
livetradingviewalart.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-05 06:21:03 </td>
   <td style="text-align:left;"> $TSLA   Wednesday after fed minutes tsla pulls back or roars </td>
  </tr>
</tbody>
</table></div>

---
