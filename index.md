---
output:
  html_document:
    keep_md: true
---

# Investment Analytics Portfolio

My portfolio exhibits some examples data analytics and financial modelling that I conduct in my daily workflows.

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

TBA:
[View the latest Economic Forecasts](/sample_page)

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



Last Updated: 2021-12-23 19:28:12 UTC +8

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
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/coronavirus-tally-global-cases-covid-19/story.aspx?guid={B1313535-F667-4DBC-861C-0D59DE18F310}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-23 19:14:56 </td>
   <td style="text-align:left;"> Coronavirus tally: Global cases of COVID-19 top 277 million and WHO chief argues for vaccines for all before boosters - MarketWatch </td>
   <td style="text-align:left;"> The global tally for the coronavirus-borne illness climbed above 277.2 million on Thursday, while the death toll edged above 5.37 million, according to data aggregated by Johns Hopkins University. The U.S. continues to lead the world with 51.5 million cases  and 812,069 deaths. The U.S. is averaging more than 1,300 deaths a day, according to a New York Times tracker, , and cases and hospitalizations are rising again, notably in the Northeast.  The head of the World Health Organization warned Wednesday that blanket booster programs in rich countries risk prolonging the world's battle with COVID-19 and said that "no country can boost its way out of the pandemic," the Associated Press reported. WHO Director-General Tedros Adhanom Ghebreyesus said the priority must be to reduce deaths and help all countries meet minimum vaccination targets that many still haven't reached. And he noted that "the vast majority of hospitalizations and deaths are in unvaccinated people, not unboosted people." 
India is second by cases after the U.S. at 34.8 million and has suffered 478,759 deaths. Brazil has second highest death toll at 618,091 and 22.2 million cases. In Europe, Russia has the most fatalities at 295,296 deaths, followed by the U.K. at 148,038., Amazon, Visa, Nordstrom, and AT&amp;T are among the stocks pegged to outperform the S&amp;P 500 next year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Ciara Linnane is MarketWatch's investing- and corporate-news editor. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 19:11:24 </td>
   <td style="text-align:left;"> US 10Y Treasury Note Yield Rebounds </td>
   <td style="text-align:left;"> The yield on the benchmark 10-year Treasury note climbed to 1.48% on Thursday, the highest in eleven days, as concerns about the omicron strain calmed ahead of key economic data, namely personal spending, durable goods orders, jobless claims, among others. After a South African study showed reduced omicron hospitalizations and severe cases, researchers in Scotland and at Imperial College of London also found lower hospitalization rates among omicron infections. Also, core prices for personal consumption expenditure are expected to have increased 0.4% mom in November, when data is released later in the day. Meanwhile, the White House said it was resuming talks with Democrat Senator Manchin about the spending bill “Build Back Better Act”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/23/politics/saudi-ballistic-missiles-china/index.html </td>
   <td style="text-align:left;"> 2021-12-23 19:00:09 </td>
   <td style="text-align:left;"> CNN Exclusive: US intel and satellite images show Saudi Arabia is now building its own ballistic missiles with help of China - CNNPolitics </td>
   <td style="text-align:left;"> Washington (CNN)US intelligence agencies have assessed that Saudi Arabia is now actively manufacturing its own ballistic missiles with the help of China, CNN has learned, a development that could have significant ripple effects across the Middle East and complicate the Biden administration's efforts to restrain the nuclear ambitions of Iran, the Saudis' top regional rival.                                                    , Saudi Arabia is known to have purchased ballistic missiles from China in the past but has never been able to build its own -- until now, according to three sources familiar with the latest intelligence. Satellite images obtained by CNN also suggest the Kingdom is currently manufacturing the weapons in at least one location.                                                                                                      , US officials at numerous agencies, including the National Security Council at the White House, have been briefed in recent months on classified intelligence revealing multiple large-scale transfers of sensitive ballistic missile technology between China and Saudi Arabia, according to two sources familiar with the latest assessments.                                                                                             , The Biden administration is now confronted with increasingly urgent questions about whether Saudi's ballistic missile advancements could dramatically change regional power dynamics and complicate efforts to expand the terms of a nuclear deal with Iran to include restraints on its own missile technology -- a goal shared by the US, Europe, Israel and Gulf countries.                                                             , Iran and Saudi Arabia are bitter enemies and it is unlikely Tehran will agree to stop making ballistic missiles if Saudi Arabia has begun manufacturing its own.                                                                                                                                                                                                                                                                           , "While significant attention has been focused on Iran's large ballistic missile program, Saudi Arabia's development and now production of ballistic missiles has not received the same level of scrutiny," Jeffrey Lewis, a weapons expert and professor at the Middlebury Institute of International Studies, told CNN.                                                                                                                   , "The domestic production of ballistic missiles by Saudi Arabia suggests that any diplomatic effort to control missile proliferation would need to involve other regional actors, like Saudi Arabia and Israel, that produce their own ballistic missiles," Lewis added.                                                                                                                                                                    , Any US response could also be complicated by diplomatic considerations with China, as the Biden administration seeks to reengage Beijing on several other high-priority policy issues, including climate, trade and the pandemic.                                                                                                                                                                                                          , "It's all a matter of calibration," a senior administration official told CNN.                                                                                                                                                                                                                                                                                                                                                             , The National Security Council and CIA declined to comment.                                                                                                                                                                                                                                                                                                                                                                                 , Asked if there have been any recent transfers of sensitive ballistic missile technology between China and Saudi Arabia, a spokesperson for China's Ministry of Foreign Affairs told CNN in a statement that the two countries are "comprehensive strategic partners" and "have maintained friendly cooperation in all fields, including in the field of military trade."                                                                   , "Such cooperation does not violate any international law and does not involve the proliferation of weapons of mass destruction," the statement said.                                                                                                                                                                                                                                                                                       , The Saudi Government and embassy in Washington did not respond to CNN's request for comment.                                                                                                                                                                                                                                                                                                                                               , New challenges for Biden                                                                                                                                                                                                                                                                                                                                                                                                                   , CNN first reported in 2019 that US intelligence agencies were aware that Saudi Arabia was collaborating with China to advance its ballistic missile program.                                                                                                                                                                                                                                                                               , The Trump administration did not initially disclose its knowledge of that classified intelligence to key members of Congress, infuriating Democrats who discovered it outside of regular US government channels and concluded it had been deliberately left out of a series of briefings where they say it should have been presented.                                                                                                     , That fueled Democratic criticism that the Trump administration was too soft on Saudi. Nuclear proliferation experts also say Trump's lack of response emboldened the Saudis to continue expanding their ballistic missile program.                                                                                                                                                                                                         , "Normally, the U.S. would have pressured Saudi Arabia not to pursue these capabilities, but the first indicators that the Saudis were pursuing these capabilities indigenously emerged during the Trump era. The Trump administration, to put it lightly, was not interested in bearing down on Riyadh over these issues," according to Ankit Panda, a nuclear policy and weapons expert at the Carnegie Endowment for International Peace., Some lawmakers have been briefed over the past few months on new intelligence about transfers of ballistic missile tech between Saudi Arabia and China, multiple sources told CNN.                                                                                                                                                                                                                                                         , The Biden administration is preparing to sanction some organizations involved in the transfers, sources told CNN, though some on Capitol Hill are concerned the White House is not willing to impose significant consequences on the Saudi government for its actions.                                                                                                                                                                     , Given the current state of negotiations with Iran, the Saudi missile program could make an already thorny problem even more difficult.                                                                                                                                                                                                                                                                                                     , "A robust Saudi missile program would introduce new challenges to constraining other missile programs in the region. To take just one example, Iran's missiles, which are a major concern to the U.S., would be more difficult to constrain in the future without parallel constraints on a growing Saudi program," Panda told CNN.                                                                                                        , 'First unambiguous evidence'                                                                                                                                                                                                                                                                                                                                                                                                               , New satellite images obtained by CNN indicate the Saudis are already manufacturing ballistic missiles at a site previously constructed with Chinese assistance, according to experts who analyzed the photos and sources who confirmed they reflect advancements that are consistent with the latest US intelligence assessments.                                                                                                          , Satellite photos taken by Planet, a commercial imaging company, between October 26 and November 9 show a burn operation occurred at a facility near Dawadmi, Saudi Arabia, according to researchers at the Middlebury Institute of International Studies, who told CNN this is "the first unambiguous evidence that the facility is operating to produce missiles."                                                                        ,                                                                                                                                                                                                                                                                                                                                                                                                                                            , "The key piece of evidence is that the facility is operating a 'burn pit' to dispose of solid-propellant leftover from the production of ballistic missiles," said Lewis, a weapons expert and professor at the Middlebury Institute of International Studies who reviewed the images.                                                                                                                                                     , "Casting rocket motors results in leftover propellant, which is an explosive hazard. Solid-propellant missile production facilities often have burn pits where leftover propellant can be disposed of by burning. Burn operations are, therefore, a strong signature that the facility is actively casting solid rocket motors," he added.                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                            , Still, little is known about the ballistic missiles that Saudi Arabia is building at this site, including important details like range and payload.                                                                                                                                                                                                                                                                                        , Considering the facility in question was built with Chinese assistance and new intelligence assessments showing Saudi Arabia has recently purchased sensitive ballistic missile technology from China, it is possible that the missiles being produced there are of Chinese design, according to Lewis.                                                                                                                                    , But there is also evidence Saudi Arabia has looked to other countries for help with developing a ballistic missile program in recent years, making it difficult to identify exactly which weapons system the Kingdom is now building at this facility, Lewis noted.                                                                                                                                                                        , CNN's Natasha Bertrand and Jeremy Herb contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 18:30:00 </td>
   <td style="text-align:left;"> BSE Sensex Extends Gains for Third Consecutive Session </td>
   <td style="text-align:left;"> The BSE Sensex ended 384.72 points or 0.68% higher to close at 57,315.28 on Thursday, tracking the upbeat mood in the global market and amid easing concerns over Omicron. Investors' sentiment was boosted after studies revealed that Omicron, although more infectious, has reduced risk of hospitalization and severe disease when compared to the Delta variant. Gains were led by banks, financials and technology. Among the individual stocks, Power Grid Corporation (+3.4%), Indian Tobacco Company( +2.48%), Bajaj Finance(+2.12%) and Infosys (+1.77%) were among the top gainers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/taiwan/retail-sales-annual </td>
   <td style="text-align:left;"> 2021-12-23 18:24:51 </td>
   <td style="text-align:left;"> Taiwan Retail Sales Rise for 3rd Straight Month </td>
   <td style="text-align:left;"> Retail sales in Taiwan rose 6.33 percent year-on-year in November of 2021, following a 6.65 percent increase in the previous month, pointing to the third consecutive monthly growth in retail activity. The most relevant contributions came from sales in general merchandise stores (7.31 percent vs 5.44 percent in October); retail trade not in stores or stalls (16.71 percent vs 19.02 percent); in e-commerce &amp; mail-order houses (20.73 percent vs 23.53 percent) Sales also rose for textiles &amp; clothing (12.65 percent vs 6.84 percent); in information and communications equipment &amp; electrical household appliances (18.99 percent vs 40.06 percent); food, beverages, and tobacco (6.91 percent vs 1.17 percent); and fuel &amp; related products (30.47 percent vs 31.91 percent). On a monthly basis, retail sales edged up 0.65 percent, slowing sharply from a 13.83 percent jump in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 18:23:34 </td>
   <td style="text-align:left;"> Italian Stocks Trade Higher on Thursday </td>
   <td style="text-align:left;"> The FTSE MIB extended yesterday’s gains by 0.2% to hover around 26,880 on Thursday, in line with its European peers, amid eased pandemic fears. Preliminary data from Scotland, England, and South Africa pointed to lower hospitalization rates for those infected with the Omicron variant when compared to the Delta variant. In the meantime, investors turn to Prime Minister Draghi’s speech this afternoon after his meeting with health authorities and ministers, in which the extent of restriction measures for the holiday season will be announced. On the corporate front, industrial stocks led the gains, driven by Cnh Industrial (1%) and Leonardo (0.9%). At the same time, Telecom Italia fell 0.6%, as main shareholders, including treasury owned CDP, discuss a revamp for the group after its third profit warning in 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/egypt/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 18:16:20 </td>
   <td style="text-align:left;"> Egypt EGX 30 Hits 21-month High </td>
   <td style="text-align:left;"> EGX 30 increased to a 21-month high of 11766 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/23/business/intel-china-apology-xinjiang-intl-hnk/index.html </td>
   <td style="text-align:left;"> 2021-12-23 18:10:00 </td>
   <td style="text-align:left;"> Intel apologizes in China after backlash over Xinjiang statement - CNN </td>
   <td style="text-align:left;"> Hong Kong (CNN)Intel has apologized in China following a backlash over a directive to suppliers not to source products or labor from the Xinjiang region.                                                                                                                        , The US chipmaker told suppliers in a letter dated December 2021 that it "is required to ensure our supply chain does not use any labor or source goods or services from the Xinjiang region" of China, citing government restrictions and questions from investors and customers., The company apologized on Thursday after the letter sparked controversy in China.                                                                                                                                                                                                , "Although our original intention was to ensure compliance with US laws, this letter has caused many questions and concerns among our cherished Chinese partners, which we deeply regret," the company said in a statement on Weibo, a Twitter-like service.                      , Human rights groups have repeatedly accused Beijing of detaining Uyghurs and other Muslim minority groups in Xinjiang in "re-education" camps and using them as forced labor, which they claim is part of global tech and retail supply chains, either directly or indirectly.   , Sanctions from the United States and other Western countries over Xinjiang have sparked a pushback from the Chinese government, which calls the camps "vocational training centers" designed to combat poverty and religious extremism.                                          , In an email to CNN Business, an Intel spokesperson said the company would continue to ensure its global sourcing complies with applicable laws and regulations in the United States and in other jurisdictions.                                                                  , "We issued a statement in China to address concerns raised by our stakeholders there regarding how we communicated certain legal requirements and policies with our global supplier network," it added.                                                                          , Intel's letter prompted a backlash on Chinese state and social media. People's Daily, the Communist Party's official newspaper, called the statement "absurd", adding that Intel is "biting the hand that feeds it."                                                             , Chinese pop star Wang Junkai, the brand ambassador for Intel Core, announced Wednesday that he had cut all ties with Intel over its statement, saying "national interests are above all else."                                                                                   , On Thursday, Zhao Lijian, a spokesperson for China's foreign ministry, said that "claims related to Xinjiang, such as forced labor" are "lies by US's anti-China forces."                                                                                                        , "We hope relevant businesses respect facts, distinguishing between right and wrong," he said.                                                                                                                                                                                    , — CNN's Beijing bureau contributed to this report.                                                                                                                                                                                                                               , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/taiwan/industrial-production </td>
   <td style="text-align:left;"> 2021-12-23 18:06:46 </td>
   <td style="text-align:left;"> Taiwan Industrial Output Growth at 3-Month High </td>
   <td style="text-align:left;"> Industrial output in Taiwan hiked 12.19 percent year-on-year in November of 2021, faster than an upwardly revised 11.60 percent rise in the previous month, snapping fourth straight months of faltering growth. It was also the fastest growth rate of industrial production since August, mainly driven by the manufacturing sector (13.13 percent vs 11.92 percent in October), while mining &amp; quarrying declined less (-1.25 percent vs -2.79 percent). On the other hand, output rose at a softer pace in utilities (2.56 percent vs 9.60 percent) and fell more sharply in water supply (-5.24 percent vs -3.58 percent). On a seasonally adjusted monthly basis, industrial production went up by 0.21 percent compared to an upwardly revised 0.51 percent gain in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/23/asia/kabul-passport-office-blast-intl/index.html </td>
   <td style="text-align:left;"> 2021-12-23 17:57:14 </td>
   <td style="text-align:left;"> Suicide bomber killed at Kabul passport office gate - CNN </td>
   <td style="text-align:left;"> A suicide bomber was killed at the gate of a passport office in the Afghan capital Kabul on Thursday, a government spokesman said, and several people were injured in the blast, according to unconfirmed reports., A spokesman for Afghanistan's interior ministry said the attacker was shot and killed while trying to enter the passport office premises.                                                                         , One member of the Taliban who was a witness told Reuters multiple people were injured, and the building and streets around the area were locked down by Taliban security forces.                                  , Large crowds of Afghans have been thronging outside the passport office in a bid to get travel documents in recent days after the service was restarted after weeks of suspension.                                , Officials said that Thursdays are reserved as a special day for Taliban officials to visit the passport office to make travel documents.                                                                          , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 17:57:00 </td>
   <td style="text-align:left;"> French Stocks Extend Gains </td>
   <td style="text-align:left;"> The CAC 40 Index extended gains by 0.2% to hover around the 7,060 level of Thursday, tracking Asian and American markets as pandemic concerns slightly waned. A study from South Africa indicated those infected with the Omicron variant showed a lower likelihood of hospitalization and death when compared to the Delta variant. On the corporate front, Airbus gained 0.8% following a EUR 10 billion contract with the French Ministry of the Armed Forces for the supply of 169 helicopters. At the same time, Engie gained 0.3% from the EUR 1.1 billion sale of its 11.5% stake at gas transmission network operator GRTgaz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/poland/unemployment-rate </td>
   <td style="text-align:left;"> 2021-12-23 17:55:31 </td>
   <td style="text-align:left;"> Polish Jobless Rate Falls Further to 20-Month Low </td>
   <td style="text-align:left;"> Poland’s unemployment rate edged down to 5.4 percent in November of 2021 from 5.5 percent in the previous month and in line with market expectations. It was the lowest jobless rate since March 2020, as the number of unemployed fell by 12 thousand to 899 thousand. A year earlier, the jobless rate was higher at 6.1 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 17:53:23 </td>
   <td style="text-align:left;"> France 10Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> France 10 Year Government Bond Yeld increased to a 4-week high of 0.101% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovenia/consumer-confidence </td>
   <td style="text-align:left;"> 2021-12-23 17:51:51 </td>
   <td style="text-align:left;"> Slovenia Consumer Confidence Improves in December </td>
   <td style="text-align:left;"> The consumer confidence in Slovenia increased to -24 in December of 2021 from -27 in November. Expectation over the next 12 months improved for the general economic situation in the country (-34 vs -41); savings (-9 vs -13); financial situation of the household (-17 vs -19); major purchases (-31 vs -32); and unemployment (22 vs 23). Last year, during the pandemic, the indicator was at a lower -29. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/business-confidence </td>
   <td style="text-align:left;"> 2021-12-23 17:44:56 </td>
   <td style="text-align:left;"> Italy Business Confidence Below Expectations </td>
   <td style="text-align:left;"> Manufacturing confidence in Italy was at 115.2 in December of 2021, easing from a downwardly revised 115.9 in the previous month and below market expectations of 115.3. Respondents’ assessment of manufacturing declined for expectations of future production (18.6 vs 19.6 in November), while improvements took place for order books (10.5 vs 10). At the same time, assessment of inventory levels rebounded (0.5 vs -0.9). The composite business index, combining surveys of manufacturing, retail, construction, and services, edged down to 113.1 from 114.8 in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/aluminum </td>
   <td style="text-align:left;"> 2021-12-23 17:36:17 </td>
   <td style="text-align:left;"> Aluminum Jumps to 8-Week High on Supply Worries </td>
   <td style="text-align:left;"> Aluminum futures jumped above $2,800 per tonne, the highest in near eight weeks boosted by worries over tight supplies. Non-ferrous production such as aluminum in Europe is again under pressure as electricity prices roared back to record levels. Also, latest data showed China's output of alumina, which is smelted to make aluminum, fell in November by 4.5% year-on-year to its lowest in 18 months as regions impose curbs on the aluminum raw material. Still, the price of aluminum remains about 10% below its 13-year high of $3,172 reached in mid-October, as supply disruptions connected to higher energy prices in China eased and aluminum ingot inventories have been falling at a slower pace as cargoes pile up at railway stations in Xinjiang and the major Chinese manufacturing province of Zhejiang is fighting a Covid-19 outbreak. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2021-12-23 17:34:00 </td>
   <td style="text-align:left;"> UK Natural Gas Slips from Record High </td>
   <td style="text-align:left;"> UK natural gas prices fell below 400 pence a therm on Thursday, sliding roughly 13% from a record 451.72 pence hit two sessions ago, as it tracked the Dutch contract lower amid reports that Gazprom’s customers in Europe had requested less gas and more US LNG tankers were crossing the Atlantic towards the continent. Two German natural gas importers assured Gazprom was meeting its contractual obligations, while Bloomberg reported that contracted supply limits for this year had already been reached. Earlier this week, prices had rallied to all-time highs bolstered by a combination of freezing temperatures and lower power output from alternative sources, which added to previous concerns about delays in the Nord Stream 2 pipeline approval and rising tensions in eastern Europe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/consumer-confidence </td>
   <td style="text-align:left;"> 2021-12-23 17:23:54 </td>
   <td style="text-align:left;"> Italy Consumer Confidence Higher than Expected </td>
   <td style="text-align:left;"> Consumer confidence in Italy edged higher to 117.7 in December of 2021 from 117.5 in the previous month and above market forecasts of 116.2, buoyed by more than EUR 7 billion of tax cuts set out on the government’s budget. Improvements were seen for the current (115.6 vs 115.2 in November), and personal (110.4 vs 110) subindices. On the other hand, sentiment deteriorated for the economic (139.6 vs 139.8) subindex, while consumers are less optimistic about the future (120.8 vs 121). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/austria/current-account </td>
   <td style="text-align:left;"> 2021-12-23 17:17:33 </td>
   <td style="text-align:left;"> Austria Current Account Surplus Narrows in Q3 </td>
   <td style="text-align:left;"> The current account surplus in Austria narrowed to EUR 0.95 billion in the third quarter of 2021 from EUR 2.29 billion a year earlier. The goods account swung to a deficit of EUR 0.08 billion compared to a surplus of EUR 0.94 billion a year ago, while the services surplus shrank to EUR 1.33 billion from EUR 2.20 billion. Meanwhile, the primary income gap narrowed to EUR 0.34 billion from EUR 0.42 billion and the secondary income account switched to a surplus of EUR 0.04 billion compared to a deficit of EUR 0.42 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/car-production </td>
   <td style="text-align:left;"> 2021-12-23 17:11:32 </td>
   <td style="text-align:left;"> UK Car Production Posts Weakest November Since 1984 </td>
   <td style="text-align:left;"> Car production in the UK fell 28.7% year-on-year to 75,756 units in November of 2021, the fifth consecutive month of decline and the worst November performance since 1984 as UK car makers continue to wrestle with the worldwide shortage of semiconductors. Production for both domestic and overseas markets declined, down -18.8% and -30.4% respectively, as 30,487 fewer cars rolled off factory lines. Exports accounted for more than 80% of all cars produced, reinforcing the need for smooth international trade, especially with the EU, as new customs controls with the bloc come into effect on 1 January 2022. Continuing the recent trend, British production of battery electric, plug-in hybrid and hybrid cars took a record share of production, accounting for around a third (32.7%) of all cars made in the month, and more than a quarter (25.5%) over the year-to-date. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2021-12-23 17:07:00 </td>
   <td style="text-align:left;"> EU Natural Gas Falls Over 13% from Record High </td>
   <td style="text-align:left;"> EU natural gas prices retreated for a second session to €156 per megawatt-hour on Thursday, erasing more than 13% since reaching a record high of €180.27 on Tuesday, amid reports that higher volumes of LNG are being shipped from the US to Europe and demand is slowing down. Out of 76 American LNG tankers in transit, 10 declared destinations in Europe, and another 20 were headed to the region, as the continent surpassed Asia as the top destination for US LNG exports this month. Meanwhile, media reports said the reversal in flows through the key Yamal-Europe pipeline was due to clients requesting less fuel, as contracted supply limits had been hit. Earlier this week, prices had rallied to all-time highs bolstered by a combination of freezing temperatures and lower power output from alternative sources, which added to previous concerns about delays in the Nord Stream 2 pipeline approval and rising tensions in eastern Europe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/fire-exxon-refinery-baytown-texas-houston-injuries </td>
   <td style="text-align:left;"> 2021-12-23 17:05:56 </td>
   <td style="text-align:left;"> Fire reported at ExxonMobil refinery in Baytown, Texas, near Houston; some injuries feared </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A "major industrial accident" at ExxonMobil's Baytown, Texas, plant near Houston may have resulted in four injuries, the Harris County sheriff said on Twitter early Friday.                                                                                                                                                                                                                                                                                                                                  , View of a fire at petrochemical company ExxonMobil's refinery near Houston in Baytown, Texas, U.S., December 23, 2021 in this still image obtained from social media video through a car window. Ansia Gobert via REUTERS (Ansia Gobert via REUTERS / Reuters Photos)                                                                                                                                                                                                                                         , ExxonMobil confirmed that a fire occurred at the facility, which houses a chemical plant and a 560,500-barrel-per-day oil refinery, according to Reuters. Baytown is about 26 miles east of downtown Houston.                                                                                                                                                                                                                                                                                                 , ExxonMobil provided the following statement.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , "A fire has occurred at the Baytown Refinery. Our fire teams are working to extinguish the fire. We are conducting personnel accounting. Our first priority remains the safety of people, including our employees, contractors and the surrounding community. As a precaution, we are beginning to conduct air quality monitoring at the site and fence line. We are cooperating with regulatory agencies. We deeply regret any disruption or inconvenience that this incident may have caused the community.", This is a developing story. Check back for updates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/30-year-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 17:05:14 </td>
   <td style="text-align:left;"> Japan 30Y Bond Yield Hits 8-week High </td>
   <td style="text-align:left;"> Japan 30 Year Government Bond Yeld increased to a 8-week high of 0.69% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/currency </td>
   <td style="text-align:left;"> 2021-12-23 16:55:50 </td>
   <td style="text-align:left;"> Chinese Yuan Moves Slightly Higher </td>
   <td style="text-align:left;"> The offshore yuan traded below 6.38 per US dollar on Thursday, moving marginally higher as trading activity moderated ahead of the year-end holidays. Meanwhile, market participants shifted their focus to whether the currency could sustain its recent strength next year, with traders dialing back long positions in the past two weeks amid concerns that authorities may rein in the currency’s recent gains. The People’s Bank of China’s official midpoint has been persistently softer than market expectations since mid-November. The central bank has also been increasing its foreign currency buying from banks, and hiked the foreign exchange reserve requirement ratio by 200 basis points to 9% effective Dec.15. Moreover, a former senior official in China’s foreign exchange regulator warned of yuan weakness in 2022 if economic data continues to disappoint. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2021-12-23 16:49:00 </td>
   <td style="text-align:left;"> Oil Falls after 2-Day Gain </td>
   <td style="text-align:left;"> Brent crude futures traded around $75 per barrel on Thursday, after rising in the previous two sessions as investors remained worried about the short-term demand outlook as more restrictions are being placed. More than 13 million people in the Chinese city of Xi'an have been ordered to stay at home as authorities attempt to tackle a Covid outbreak there. Still, recent studies suggested the omicron variant of Covid appears to be milder than previous strains. Meanwhile, EIA data showed US inventories fell by 4.72 million barrels, its fourth straight weekly draw and well above market estimates for a 2.75-million-barrel decline. Elsewhere, Natural gas prices in Europe surged to record highs as flows from a key Russian pipeline stopped, forcing some countries to boost electricity imports and burn oil to meet demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/currency </td>
   <td style="text-align:left;"> 2021-12-23 16:48:05 </td>
   <td style="text-align:left;"> Japanese Yen Weakens Despite Kuroda Remarks </td>
   <td style="text-align:left;"> The Japanese yen remained weak above 114 per US dollar on Thursday despite remarks from Bank of Japan governor Haruhiko Kuroda, who warned that a weak yen may be hurting households more than in the past, citing the country’s increasing reliance on more expensive raw material imports which push the cost of living up. However, he reiterated that overall, the benefits of a weak yen outweigh the drawbacks, including stronger exports and higher profits that companies earn overseas. Mr. Kuroda also recently commented that it was too early to consider normalizing monetary policy, bolstering the view that the Japanese central bank would lag behind other central banks in scaling back monetary stimulus. Moreover, prime minister Fumio Kishida said on Thursday he hoped the BOJ continues to make efforts to achieve its 2% inflation target, expressing desire for supportive monetary and fiscal policies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 16:46:37 </td>
   <td style="text-align:left;"> UK 10Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> UK 10 Year Government Bond Yeld increased to a 4-week high of 0.925% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 16:36:00 </td>
   <td style="text-align:left;"> Asian Shares Advance </td>
   <td style="text-align:left;"> Major bourses in Asia rose on Thursday following an upbeat mood on Wall Street, amid signs the omicron variant is less severe than previous strains, albeit more infectious. Shares in Japan led the rise, up for the 3rd straight session, with technology stocks extending gains from the prior session. In Hong Kong, shares of Chinese e-commerce titan JD.com plunged while Tencent surged after Tencent announced it will distribute the majority of its shares in e-commerce titan to its shareholders. The Shanghai Composite also rose, on reports that China Evergrande will engage with its creditors after its recent missed debt repayments. Still, more than 13 million people in the Chinese city of Xi'an have been ordered to stay at home as authorities attempt to tackle a Covid outbreak there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/stock-futures-12-23-2021 </td>
   <td style="text-align:left;"> 2021-12-23 16:27:26 </td>
   <td style="text-align:left;"> Stock futures trade higher to end the holiday-shortened week </td>
   <td style="text-align:left;"> Seaport Securities founder Teddy Weisberg and Revere Securities chief strategist Scott Fullman discuss the economic activity to look for going into the new year.                                                                                                                                                                                                                                                                                                                                                                                                                                                             , U.S. equity futures were trading higher Thursday morning in what will be the final trading day of the week.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The major futures indexes suggest a gain of 0.2% when the opening bell rings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , While it is a holiday-shortened week, equities will have a full trading session Thursday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The bond market will have a shortened trading session with the market closing at 2 p.m. ET.  There will be no trading in equities or U.S. Treasuries on Christmas Eve on Friday.                                                                                                                                                                                                                                                                                                                                                                                                                                              , Many world markets will be closed Friday in observance of Christmas.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , CLICK HERE FOR FOX BUSINESS' REAL-TIME CRYPTOCURRENCY PRICING DATA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , A slew of key economic reports are on deck Thursday morning as investors look to wrap up the week and begin their Christmas holiday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The Labor Department is out with its tally of new claims for unemployment benefits for last week. Expectations are for 205,000, little-changed from the previous week’s total of 206,000. Continuing claims, which track the total number of unemployed workers collecting benefits, are anticipated to slip by 25,000 to 1.82 million, which would be a second straight pandemic low.                                                                                                                                                                                                                                        , CONSUMER CONFIDENCE ROSY, BUT COVID, INFLATION REMAIN HEADWINDS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , At the same time the Commerce Department posts personal income and spending numbers for November. Economists surveyed by Refinitiv anticipate spending to rise 0.6% month-over-month. Personal income, meantime, is expected to edge up 0.4% after a 0.5% rise in October. Core personal consumption expenditures, which remove volatile food and energy prices, are also anticipated to jump 0.4% month-over-month in November. The year-over-year change in core PCE, which is the Federal Reserve’s preferred measure of inflation, is expected to shoot up to 4.5%, which would be the highest reading in almost 33 years., Other reports include readings on durable goods, new home sales and consumer sentiment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , In Europe, London's FTSE rose 0.2%, Germany's DAX added 0.4% and France's CAC gained 0.2%.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , In Asia, Tokyo's Nikkei 225 gained 0.8%, Hong Kong's Hang Seng edged 0.4% higher and China's Shanghai Composite index picked up 0.6%.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Stocks advanced Wednesday on Wall Street with encouraging reports about the potential impact of the omicron variant of coronavirus and stronger U.S. economic data.                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The S&amp;P 500 rose 1% to 4,696.56, the Nasdaq rose 1.2% to 15,521.89 and the Dow Jones Industrial Average rose 0.7% to 35,753.89.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , US ECONOMIC GROWTH REVISED UP TO 2.3% IN THIRD QUARTER, BUT STILL LAGGED PREVIOUS MONTHS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The Commerce Department on Wednesday said the U.S. economy grew at a 2.3% rate in the third quarter, slightly better than previously thought. But prospects for a solid rebound going forward are being clouded by the rapid spread of the latest variant of the coronavirus.                                                                                                                                                                                                                                                                                                                                                 , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , In other trading, U.S. benchmark crude oil lost 8 cents to $72.66 per barrel in electronic trading on the New York Mercantile Exchange. It jumped 2.3% on Wednesday. Brent crude, the basis for pricing international crude, fell 6 cents to $75.23 per barrel.                                                                                                                                                                                                                                                                                                                                                               , The Associated Press contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/23/jdcom-tanks-after-tencent-says-it-will-give-most-of-its-stake-to-shareholders.html </td>
   <td style="text-align:left;"> 2021-12-23 16:23:37 </td>
   <td style="text-align:left;"> JD.com tanks after Tencent says it will give away most of its stake in e-commerce giant to shareholders </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                        , JD.com plummeted Thursday after Tencent announced it will be giving most of its shares in the Chinese e-commerce giant away to its shareholders.                                                                                                                                                                                                       , Tencent said it will declare a one-time dividend in which it will distribute more than 457 million Class A ordinary shares of JD.com to shareholders, with a total value of approximately 127.7 billion Hong Kong dollars (about $16.37 billion).                                                                                                      , Tencent has investments in several companies, including other large Chinese internet companies like Meituan and Pinduoduo. While those investments have helped fuel growth, Blue Lotus Capital Advisors' Shawn Yang said they could also raise concerns about Tencent's size and influence.                                                            , "I think that basically it's Tencent's choice, right, to gradually reduce those shares and try to show to the public that you know … 'we're not that big as you think,'" Yang said. "That probably can reduce some of the concerns of its size and influence."                                                                                         , Beijing has been cracking down on China's domestic tech sector for months, citing concerns over potential monopolies and data security, slapping massive fines on companies like Alibaba and Meituan.                                                                                                                                                  , Yang said Tencent's move may have stemmed from a desire to deflect attention away from itself rather than JD's fundamentals. He explained JD's e-commerce business has been "very resilient" this year compared with competitors Pinduoduo and Alibaba.                                                                                                , In its Thursday filing, Tencent said part of its strategy includes investing in companies early to support development and to exit when they become "consistently capable of self-financing their future initiatives." Tencent said JD.com has reached that stage and that now is an "appropriate time" to distribute its stake among its shareholders., JD.com said in a separate release that Tencent's stake would fall from about 17% currently to around 2.3% after the move. It also said the two companies will continue to maintain their strategic partnership agreement.                                                                                                                              , Shares of JD.com in Hong Kong closed 7.02% lower. Tencent shares, on the other hand, surged 4.24%, bucking the overall trend among Chinese tech stocks listed in the city. The Hang Seng Tech index slipped 0.83% to 5,638.31.                                                                                                                         , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                 , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                 , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                       , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                       , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                     , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 16:17:00 </td>
   <td style="text-align:left;"> UK Stocks at Over 5-Week High </td>
   <td style="text-align:left;"> The FTSE 100 edged higher to six-week highs on Thursday, in line with its European peers, amid easing concerns about the omicron coronavirus variant, with air travel companies EasyJet and Wizz Air leading gains, while banks climbed 0.8% on the back of higher government bond yields. After a South African study showed reduced omicron hospitalizations and severe cases, researchers in Scotland and at Imperial College of London also found lower hospitalization rates among omicron infections. Traders also welcomed the approval by the US FDA of the new Pfizer antiviral COVID-19 pill for people aged 12 or above at risk of severe disease. On the data front, UK auto production slumped 28.7% yoy in November amid ongoing supply chain issues and the global semiconductor chip shortage. On corporate news, online bookmaker Flutter Entertainment rose almost 5% after announcing it would buy Italian peer Sisal for £1.62 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/23/china/xian-china-covid-lockdown-intl-hnk/index.html </td>
   <td style="text-align:left;"> 2021-12-23 16:14:27 </td>
   <td style="text-align:left;"> China Covid-19: Xi'an, city of 13 million people, goes into lockdown imn response to cluster - CNN </td>
   <td style="text-align:left;"> Hong Kong (CNN)On Tuesday, the central Chinese city of Xi'an recorded 52 new Covid-19 cases. By Wednesday, authorities had imposed strict lockdown measures on its estimated 13 million residents.                                                                                                                 , The sweeping restrictions, which prevent people from leaving their homes, come as the country braces for the Lunar New Year travel rush, followed by the 2022 Winter Olympics, due to begin in the capital Beijing on February 4.                                                                                  , Xi'an, an ancient city known internationally as the home of the 2,000-year-old Terracotta warriors sculptures, detected its first case connected to the latest outbreak at a quarantine hotel on December 9. The virus is believed to have then spread into the community via an infected hotel worker.            , Officials believe the cluster is linked to an inbound flight from Pakistan on December 4, where at least six passengers were found to have the Delta variant. So far, there have been no reported cases of the Omicron variant in Xi'an.                                                                           , Authorities moved swiftly, suspending schools and conducting mass testing for the entire city. Cases have continued to climb, however. Since December 9, the city has recorded a total of 206 cases. On Wednesday, authorities recorded 63 new locally transmitted cases, Xi'an's highest daily figure this month. ,                                                                                                                                                                                                                                                                                                                    , By noon on Wednesday, more than 30,000 people who were believed to have come into contact with a confirmed case were placed in government quarantine, according to state-run newspaper China Daily. That same day, the city imposed a strict lockdown until further notice for all residents.                      , Xi'an is now designated a "controlled area," China's second-highest category of lockdown -- meaning residents are banned from leaving their homes except for urgent cases like medical emergencies. Each household is only allowed to send one designated person out of the house to buy groceries every two days. , After the new restrictions were announced, families rushed to supermarkets to stock up on supplies before the lockdown went into effect at midnight, according to state-run tabloid the Global Times.                                                                                                              , Schools, public facilities and transport systems are also closed except for essential service providers like hospitals and supermarkets, according to the local government's announcement.                                                                                                                         ,                                                                                                                                                                                                                                                                                                                    , Xi'an is one level away from the highest lockdown category of "sealed area," in which residents are completely banned from leaving their homes, and groceries are delivered to their door.                                                                                                                         , This is only the fourth time a major Chinese city has been placed under the "controlled area" lockdown. Though previous outbreaks have seen similar restrictions, they are typically only applied to specific areas where infections are most prevalent -- not an entire city.                                     , The emergence of yet another outbreak has raised questions over the long-term viability of China's ambitious "zero-Covid" policy, which aims to eliminate the virus completely within the country's borders.                                                                                                       , Despite administering more than 2.7 billion doses of its homegrown vaccines, authorities have struggled with a number of fast-spreading outbreaks.                                                                                                                                                                 , The outbreak in Xi'an follows a Delta-driven outbreak in the summer; a September outbreak in Fujian province; an October outbreak that spread to more than half the country; then several clusters in Inner Mongolia in November, which have spread to Zhejiang province in recent weeks.                          , In the past week alone, in addition to Xi'an, cases have also been recorded in Henan province, Zhejiang province, Guangdong province, Guangxi autonomous region, and the cities of Beijing and Tianjin.                                                                                                            , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 16:14:00 </td>
   <td style="text-align:left;"> European Stocks Extend Gains on Thursday </td>
   <td style="text-align:left;"> European stocks traded slightly higher to two-week highs on Thursday, as concerns about the omicron strain faded. After a study out of South Africa suggested a reduced risk of hospitalization and severe disease of Omicron compared to delta, researchers in Scotland and at Imperial College of London also found lower hospitalization rates among omicron infections.  On the corporate front, Ryanair warned its losses this year could be more than double due to renewed travel restrictions in response to the spread of the Omicron. On the data front, German import prices surged by the most since 1974, while in the US December consumer confidence beat expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/gdp-growth </td>
   <td style="text-align:left;"> 2021-12-23 16:13:53 </td>
   <td style="text-align:left;"> Spain Q3 GDP Growth Revised Higher </td>
   <td style="text-align:left;"> Spain's quarterly economic growth was sharply revised higher to 2.6 percent in the third quarter of 2021, from a preliminary estimate of 2 percent. It was the steepest pace of expansion in a year. Household consumption climbed 1 percent (vs 5 percent in Q2) and public spending went up 0.5 percent (vs 0.8 percent in Q2). Meanwhile, net external demand contributed positively to the GDP as exports (7.1 percent) increased more than imports (2.2 percent). Also, fixed investment rose 1.2 percent (vs -3.2 percent in Q2). On a yearly basis, the economy grew by 3.4 percent, easing from a record 17.7 percent expansion in the previous period and compared to earlier estimates of 2.7 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/currency </td>
   <td style="text-align:left;"> 2021-12-23 16:12:59 </td>
   <td style="text-align:left;"> NZ Dollar Climbs on Improved Risk Sentiment </td>
   <td style="text-align:left;"> The New Zealand dollar climbed back above $0.68 on Thursday, bringing the week’s gains well north of 1% amid a more positive economic outlook and increased risk appetite among investors. Encouraging news around the omicron variant also lifted sentiment, including studies suggesting the virus is less severe than previously feared and the granting of emergency use authorization by the US FDA to Pfizer’s Covid pill. A milder than expected economic contraction in New Zealand also solidified expectations of further central bank monetary tightening. New Zealand’s economy shrank 3.7% in the third quarter, well below market expectations for a 4.5% contraction and central bank projection for a 7% decline. The Reserve Bank of New Zealand was among the first major central banks to begin policy normalization, with expectations that it will continue hiking that cash rate through until 2023. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/currency </td>
   <td style="text-align:left;"> 2021-12-23 16:01:39 </td>
   <td style="text-align:left;"> British Pound Hits 4-week High </td>
   <td style="text-align:left;"> GBPUSD increased to a 4-week high of 1.3373 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/currency </td>
   <td style="text-align:left;"> 2021-12-23 16:00:15 </td>
   <td style="text-align:left;"> Australian Dollar Hits 4-Week High </td>
   <td style="text-align:left;"> The Australian dollar hit a new 4-week high above $0.72 on Thursday, amid a more positive economic outlook and increased risk appetite among investors. Encouraging news around the omicron variant also lifted sentiment, including studies suggesting the virus is less severe than previously feared and the granting of emergency use authorization by the US FDA to Pfizer’s Covid pill. The aussie’s recent strength came despite central bank dovishness, with governor Philip Lowe reiterating in a recent speech that the Reserve Bank of Australia would keep interest rates at record low in 2022. Meanwhile, strong jobs data in Australia raised the likelihood that the central bank will wind down its pandemic-era stimulus early next year. The RBA is considering three options for its quantitative easing program ahead of its formal review next year, including ending its bond purchases as soon as February, governor Lowe said in a speech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 15:45:09 </td>
   <td style="text-align:left;"> UK Stock Futures Seen Near 6-Week High </td>
   <td style="text-align:left;"> FTSE 100 stock futures edged higher towards six-week highs on Thursday, in line with its European peers, amid easing concerns about the omicron coronavirus variant. After a South African study showed reduced omicron hospitalizations and severe cases, researchers in Scotland and at Imperial College of London also found lower hospitalization rates among omicron infections. Traders also welcomed the approval by the US FDA of the new Pfizer antiviral COVID-19 pill for people aged 12 or above at risk of severe disease. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 15:42:37 </td>
   <td style="text-align:left;"> China Stocks Drift Higher on Muted Rebound </td>
   <td style="text-align:left;"> The Shanghai Composite Index gained 0.57% to close at 3,643 while the tech-heavy Shenzhen Index rose 0.49% to 14,864 on Thursday, as Chinese companies staged a muted rebound after recent sell offs prompted by regulatory action from Beijing and Washington. However, gains were capped as investors continued monitoring Covid developments after the city of Xi’an ordered 13 million residents to stay at home as it dealt with rising cases. The new energy, aluminum, auto parts, coal and consumer staple groups were among the outperformers in the market. Some of the most notable gainers include Kweichow Moutai (3.52%), Shanxi Meijin (6.38%), Aluminum Corp (10%), Wuliangye Yibin (2.11%), China Three Gorges (5.5%), Cecep Solar (10%), Cecep Wind (10%) and Weichai Power (1.59%). Meanwhile, debt-laden China Evergrande Group said the committee helping steer its massive restructuring is deploying extensive resources to help contain risks and will engage with creditors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 15:36:00 </td>
   <td style="text-align:left;"> European Stocks Set to Open Higher </td>
   <td style="text-align:left;"> European stocks are set to open higher on Thursday, after a study out of South Africa suggested a reduced risk of hospitalization and severe disease of Omicron compared to delta. On the corporate front, Ryanair warned its losses this year could be more than double due to renewed travel restrictions in response to the spread of the Omicron. On the data front, German import prices surged by the most since 1974, while in the US December consumer confidence beat expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/currency </td>
   <td style="text-align:left;"> 2021-12-23 15:30:59 </td>
   <td style="text-align:left;"> Australian Dollar Hits 4-week High </td>
   <td style="text-align:left;"> AUDUSD increased to a 4-week high of 0.72235 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 15:29:01 </td>
   <td style="text-align:left;"> The SHANGHAI Index rose 0.57% </td>
   <td style="text-align:left;"> China Stock Market rose 21 points. Leading the gains are Aluminum Corporation of China (10.03%), Datang Intl (10.00%) and Huaneng (9.97%). Top losers were Kangmei Pharma (-5.05%), China Fortune (-1.85%) and Jinzhou Port (-1.73%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/bitcoin-price-12-23-2021 </td>
   <td style="text-align:left;"> 2021-12-23 15:27:12 </td>
   <td style="text-align:left;"> Bitcoin price slides below $49,000 </td>
   <td style="text-align:left;"> Pomp Investments founder Anthony Pompliano analyzes the ‘monetary and technology revolutions’ in bitcoin and other cryptocurrencies.                                                                                                                                                                                                                                                                                                                     , Bitcoin slipped below $48,000 early Thursday, after moving above that level in Tuesday's session.                                                                                                                                                                                                                                                                                                                                                        , Cryptocurrencies have come a long way in 2021, including becoming legal tender in El Salvador and some athletes are now asking to be paid in bitcoin.                                                                                                                                                                                                                                                                                                    , All this while on the way to an all-time high over $69,000.                                                                                                                                                                                                                                                                                                                                                                                              , CLICK HERE FOR FOX BUSINESS' REAL-TIME CRYPTOCURRENCY PRICING DATA                                                                                                                                                                                                                                                                                                                                                                                       , In November 2020, Pomp Investments founder Anthony Pompliano predicted that bitcoin would hit $100,000 in 2021.                                                                                                                                                                                                                                                                                                                                          , That hasn't happened yet but Pompliano told FOX Business' Liz Clayman he's still confident the cryptocurrency will be hitting a major milestone.                                                                                                                                                                                                                                                                                                         , "First of all, the year isn't over yet," Pompliano said. "We know at the end of the year bitcoin runs pretty significantly. Don't say it's over yet but a big move would have to occur for that to happen."                                                                                                                                                                                                                                              , "I definitely think we'll see six-figure bitcoin before the next leg of this bull market," he added.                                                                                                                                                                                                                                                                                                                                                     , WISDOMTREE TWEAKS BITCOIN ETF APPLICATION                                                                                                                                                                                                                                                                                                                                                                                                                , The topic of regulation has been mentioned throughout the past year.                                                                                                                                                                                                                                                                                                                                                                                     , "It's moving so quickly. To understand the technology is one big challenge and second, understanding exactly what the regulation should be," Pompliano said. "I generally think we have a lot of good faith actors, people who want to figure out what the right solutions are. What they want to do is encourage innovation they want to encourage economic prosperity and job creation in the U.S. but they also want to put some guidelines in place.", CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                  , Bitcoin is down fractionally this week, but up more than 104% over the past year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/denmark/gdp-growth </td>
   <td style="text-align:left;"> 2021-12-23 15:19:28 </td>
   <td style="text-align:left;"> Danish Q3 GDP Growth Revised Up to 1.1% </td>
   <td style="text-align:left;"> The Danish economy expanded by 1.1 percent on quarter in the three months to September of 2021, higher than a preliminary reading of a 0.9 percent expansion, but easing from a downwardly revised 2.1 percent growth in the previous period. It was the second straight quarter of expansion in the GDP, due to easing COVID-19 restrictions. Household consumption grew softer (2.4% vs 7.2% in Q2), while net external demand contributed positively to the GDP growth, as exports rose by 1.1 percent (vs -0.7% in Q2) and imports also increased 1.1%, slowing from a 3.4% rise in Q2. Meanwhile, both fixed investment (-0.6% vs 2.6% in Q2) and government spending (-4.5% vs 4.5% in Q2) contracted. Year-on-year, the economy advanced by 3.6 percent, slowing sharply from a downwardly revised 8.7 percent growth in the second quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2021-12-23 15:18:53 </td>
   <td style="text-align:left;"> Dollar Weakens on Improved Risk Sentiment </td>
   <td style="text-align:left;"> The dollar index traded around 96 on Thursday after falling about half a percent in the previous session, amid renewed optimism about the economy and increased risk appetite among investors. Equities, commodities and risk-sensitive currencies rallied against the dollar on Wednesday as investors adopted a more positive economic outlook, with upbeat consumer confidence levels and an upwardly revised estimate for US GDP. Encouraging news around the omicron variant also lifted sentiment, including a South African study suggesting the virus is less severe than previously feared and the granting of emergency use authorization by the US FDA to Pfizer’s Covid pill. Meanwhile, the White House said it is resuming talks on the Build Back Better bill with senator Joe Manchin, raising hopes for a large fiscal stimulus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/import-prices </td>
   <td style="text-align:left;"> 2021-12-23 15:13:00 </td>
   <td style="text-align:left;"> German Import Prices Rise the Most Since 1974 </td>
   <td style="text-align:left;"> Import prices in Germany soared 24.7 percent year-on-year in November of 2021, accelerating from a 21.7 percent rise in the previous month and above market expectations of 22.3 percent. It was the largest annual increase in import prices since October 1974, as energy cost jumped 159.5 percent, mainly due to higher prices for natural gas (270.9 percent), crude oil (100.4 percent) and mineral products (90.5 percent). Also, cost for imported intermediate goods rose 23 percent boosted by fertilizers and nitrogen compounds (144 percent), raw aluminum (+64.2%), pig iron, steel and ferro-alloys (60.2 percent) and plastics in primary forms (44.7 percent). Additional upward pressure came from consumer (5.3 percent) and capital goods (3.9 percent). On a monthly basis, import prices advanced 3 percent, also beating expectations of a 1.1 percent increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 15:01:19 </td>
   <td style="text-align:left;"> Italy 10Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> Italy 10 Year Government Bond Yeld increased to a 4-week high of 1.08% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 14:43:00 </td>
   <td style="text-align:left;"> China 10Y Bond Yield Hits 18-month Low </td>
   <td style="text-align:left;"> China 10 Year Government Bond Yield decreased to an 18-month low of 2.818% following the People’s Bank of China’s decision earlier this week to cut its one-year benchmark loan rate by 5bps, the first-rate cut in 20 months amid the downward pressure in the Chinese economic recovery. Meantime, an official with the country's top economic planner said that  China will continue implementing proactive fiscal policies and prudent monetary policies, as well as making good use of investment and consumption policy tools for steady economic growth next year. A string of measures will be taken to support reform, such as promoting market-based allocation of factors of production, deepening the mixed-ownership reform, and shortening the negative list for foreign investment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 14:38:00 </td>
   <td style="text-align:left;"> Japanese Shares Advance as Tech Stocks Lift </td>
   <td style="text-align:left;"> The Nikkei 225 Index climbed 0.83% to close at 28,798 while the broader Topix Index jumped 0.91% to 1,989 on Thursday, with technology stocks extending gains from the previous session, as investor sentiment was lifted by a strong overnight finish on Wall Street. Some of the top gainers include Lasertec (3%), Recruit Holdings (3.69%), Tokyo Electron (1.31%), Japan Data Science (21.29%), Kohoku Kogyo (16.37%), Sumco (2.14%) and Mitsui High Tec (5.31%). Meanwhile, Japan reported its first instance of community spread infection from the omicron variant on Wednesday. The negative development, however, was offset by signs of hope that the new variant is not as severe as previously feared. A South African study suggested a reduced risk of hospitalization and severe disease compared to the delta variant. Moreover, the US FDA granted emergency use authorization for Pfizer’s Covid treatment pill on Wednesday, the first oral antiviral drug cleared during the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/interest-rate </td>
   <td style="text-align:left;"> 2021-12-23 14:37:00 </td>
   <td style="text-align:left;"> Japan Economic Recovery to be Evident in 2022 </td>
   <td style="text-align:left;"> Japan's economic recovery is expected to become evident next year, as downward
pressure stemming from the impact of COVID-19 and supply-side constraints are likely to
wane and the government's new economic measures are projected to have positive effects, Bank of Japan (BOJ) Governor Haruhiko Kuroda said in a speech. "From a macroeconomic perspective, the coming year provides an opportunity to take large strides toward the post-pandemic era," he added. Regarding the yen's depreciation, Kuroda noted it generally pushes up Japan's economic activity. However, he acknowledged that a weak yen might have an increasingly negative impact on household income through price rises and on domestic retailers by pushing up import costs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59764069?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2021-12-23 14:32:54 </td>
   <td style="text-align:left;"> Joe Biden hails supply chain win but problems persist </td>
   <td style="text-align:left;"> US President Joe Biden has said government measures to tackle global supply chain issues have averted a pre-Christmas crisis.                                                                                                                                                     , He was speaking ahead of a meeting with officials and company bosses, including transportation giant FedEx.                                                                                                                                                                       , In June, he created a task force to address rising prices and shortages of goods caused by the pandemic.                                                                                                                                                                          , However, some business owners and industry experts say American firms are still facing supply problems.                                                                                                                                                                           , "The much-predicted crisis didn't occur," Mr Biden said ahead of a meeting with his Supply Chain Disruptions Task Force and corporate executives.                                                                                                                                 , He went on to say that shop shelves are stocked at 90% of their full capacity and deliveries are happening at a faster rate than before the pandemic: "Packages are moving, gifts are being delivered, shelves are not empty."                                                    , The meeting included the secretaries of Agriculture, Commerce, Labor and Transportation as well as National Economic Council Director Brian Deese and Port Envoy John Porcari.                                                                                                    , The chief executives of clothing retailer Gap, Kansas-based trucking company Yellow Corp and the American Association of Port Authorities also took part in the event.                                                                                                            , FedEx chief executive Fred Smith said "most of Santa Claus' products will be delivered to the consumers." but supply chain issues are "not all solved".                                                                                                                           , In October, the Biden administration pushed for round-the-clock operations at ports and called on the help of some of the country's biggest retailers, including Walmart and Target, to tackle a major backlog of goods.                                                          , In response the Port of Los Angeles in California said it would handle more goods at night after a similar move by nearby Long Beach port.                                                                                                                                        , The ports - which handle 40% of all cargo containers entering the US - had faced months of problems.                                                                                                                                                                              , Hailing the initiative as a success the White House has pointed to a record number of goods now moving faster through the ports, while waiting times for shipping containers has been cut in half.                                                                                , Last month, Walmart's chief executive Doug McMillon said he had seen a positive impact on the flow of goods.                                                                                                                                                                      , However, the ports are still grappling with a flood of empty shipping containers and the queue for container ships waiting to unload is about 90 vessels long.                                                                                                                    , Supply chain expert Megan Benger from business consultancy TMX told the BBC that although huge efforts have been made to address issues caused by the pandemic she still sees challenges ahead for global trading networks:                                                       , "The backlog of containers waiting to be unloaded has had a flow-on effect to the repositioning of empty containers back to export-oriented markets in Asia and other parts of the world. This further compounds the delays in getting products onto shelves in stores."          , Ms Benger also warned that the new strain of Covid-19 which is spreading around the world is set to have an impact on the global supply chain in the year ahead.                                                                                                                  , "While ongoing efforts to keep supply chains flowing are helping to ease the disruptions, we are also starting to see that the Omicron variant is leading to increasing restrictions globally. As such, we expect to see supply chain disruptions continuing into 2022," she said., This video can not be played                                                                                                                                                                                                                                                      , Which one will be given the tinsel crown?                                                                                                                                                                                                                                         , A Very British Scandal: A gripping new drama coming soon                                                                                                                                                                                                                          , © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 14:24:42 </td>
   <td style="text-align:left;"> ASX Climbs on Gold, Battery Materials Boost </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index climbed 0.31% to close at 7,388 on Thursday, extending the rebound from omicron-triggered sell offs for a third straight day, helped by gains in gold miners and producers of battery materials for electric carmakers. Fears around the omicron variant also receded following positive news developments, with countries such as the US and Australia ruling out lockdowns. Among the top gainers were gold and lithium explorers including Pilbara Minerals (2.93%), Newcrest Mining (1.05%), Mineral Resources (2.29%), Prospect Resources (5.88%), Evolution Mining (2.26%) and Regis Resources (4.32%). Meanwhile, Syrah Resources soared 23% after announcing a four-year deal to supply graphite materials to electric carmaker Tesla from its plant in the US state of Louisiana. Elsewhere, Bega Cheese dropped 10% after the company warned of a hit to its 2022 fiscal earnings from strong competition for dairy supply in Australia, high global prices and impact from the coronavirus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/23/european-stocks-seen-higher-on-signs-of-hope-about-omicron.html </td>
   <td style="text-align:left;"> 2021-12-23 14:24:06 </td>
   <td style="text-align:left;"> European stocks trade higher on signs of hope about omicron </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                , LONDON — European stocks traded slightly higher Thursday morning as traders looked to signs that the omicron coronavirus variant is not as severe as previously feared.                                                                                                                                                        , The pan-European Stoxx 600 index opened up 0.2%, with travel and leisure shares climbing 1.7% to lead the gains amid optimism over Covid.                                                                                                                                                                                      , Airline stocks were among the top performers, with British Airways parent company IAG and Hungarian budget carrier Wizz Air both up about 3%.                                                                                                                                                                                  , Investors reacted to a study out of South Africa — where the omicron strain was first discovered — suggesting a reduced risk of hospitalization and severe disease compared to delta.                                                                                                                                          , The study, which is not yet peer reviewed, found people diagnosed with omicron in South Africa from Oct. 1 to Nov. 3 were 80% less likely to be hospitalized than if they caught another variant in the same period.                                                                                                           , Experts say it is still too early to know for sure the severity of omicron, but the study offers hope that both the human and economic cost of the strain will not be as severe as initially feared. Omicron's rapid spread has led governments around the world to reimplement some Covid restrictions in a bid to contain it., More good news arrived Wednesday as the U.S. Centers for Disease Control and Prevention authorized an antiviral Covid pill from Pfizer for people aged 12 and above at risk of severe illness.                                                                                                                                 , These glimmers of hope have boosted global share markets. In Asia, stocks rose Thursday and stateside, stock futures were trading slightly higher.                                                                                                                                                                             , Investors also digested data showing that U.S. consumer confidence ticked up in December, despite fears over omicron.                                                                                                                                                                                                          , Back in Europe, Italian Prime Minister Mario Draghi on Wednesday suggested he would be willing to become the country's president, saying his government had laid the foundations for key work to continue.                                                                                                                     , In corporate news, Ryanair on Wednesday said it was more than doubling its forecast for full-year losses, citing the emergence of travel restrictions in several big markets due to the coronavirus. Ryanair                                                                                                                   , Looking at individual stocks, Germany's United Internet sunk toward the bottom of the Stoxx 600 Thursday, down 1.6% after news that CEO Ralph Dommermuth has increased his equity ownership of the firm to 50.1% but won't make a voluntary acquisition offer to shareholders.                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                               , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 14:11:34 </td>
   <td style="text-align:left;"> NZ Stocks Snap Three-Day Rally </td>
   <td style="text-align:left;"> The NZX 50 Index closed marginally lower by 0.02% at 12,863 on Thursday, snapping three straight days of gains as the market rebound from omicron-triggered sell offs took a breather. The trading day has been largely positive following a strong overnight session on Wall Street, but late selling on some index giants weighed on the market. The biggest index decliners were Restaurant Brands (-3.58%), Pacific Edge (-3.01%), NZX (-2.16%), Investore Property (-2.08%), Goodman Property (-1.73%) and Tourism Holdings (-1.67%). Meanwhile, healthcare product distributor Ebos Group jumped 1.61% after the company issued a large placement to fund the A$1.2 billion acquisition of a healthcare distribution business. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/singapore/food-inflation </td>
   <td style="text-align:left;"> 2021-12-23 14:06:26 </td>
   <td style="text-align:left;"> Singapore Food Prices Rise the Most in 16 Months </td>
   <td style="text-align:left;"> Food prices in Singapore increased by 1.9 percent year-on-year in November of 2021, the most since July 2020, after a 1.7 percent gain in the prior month. Within food excluding food servicing services, prics rose further for vegetables (6.8% vs 4.8% in October); milk, cheese &amp; eggs (2.3% vs 1.5%); meat (1.5% vs 1.1%); non-alcoholic beverages (1.1% vs 1.5%); oils &amp; fats (4.9% vs 4.8%); bread &amp; cereals  (1.8% vs 1.6%); and other food (1.7% vs 2.0%). In contrast, prices of sugar, preserves &amp; confectionery fell much faster (-1.6% vs -0.2%). Among food servicing services, prices continued to rise for all components: restaurant foods (1.1% vs 1.4%), fast-food (2.5% vs 2.3%), hawker food (1.8% vs 1.6%), and catered food (0.7% vs 0.7%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 13:46:04 </td>
   <td style="text-align:left;"> Indian Shares Climb on Financials, Tech Boost </td>
   <td style="text-align:left;"> The BSE Sensex and Nifty 50 indices each gained about 0.6% in early trade on Thursday, helped by gains in financial and technology stocks, as global risk sentiment improved after a study showed hospitalization risk from omicron was lower compared with the delta variant. The US FDA also granted emergency use authorization for Pfizer’s Covid treatment pill on Wednesday, the first oral antiviral drug cleared during the pandemic. Moreover, minutes from the Reserve Bank of India’s latest monetary policy meeting showed members suggested that some key areas of growth warrant continued policy support. Some of the top gainers include Bajaj Finance (1.9%), Birlasoft (4.1%), Infosys (1%), Wipro (1%), Tata Consultancy (0.4%) and HDFC Bank (0.3%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2021-12-23 13:38:09 </td>
   <td style="text-align:left;"> Gold Rises on Dollar Weakness </td>
   <td style="text-align:left;"> Gold firmed up above $1,800 an ounce on Thursday, after jumping almost 1% in the previous session, buoyed mainly by a weaker dollar. The US dollar index dropped on Wednesday amid renewed optimism about the economy despite the spread of the omicron variant. A South African study suggested reduced risk of hospitalization and severe disease in people infected with the new variant. The US FDA also granted emergency use authorization for Pfizer’s Covid treatment pill on Wednesday, the first oral antiviral drug cleared during the pandemic. These developments improved market sentiment, driving investors to position out of safe-haven dollar into riskier assets. A softer dollar makes gold less expensive for buyers holding non-US currencies, lifting its appeal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2021-12-23 13:07:26 </td>
   <td style="text-align:left;"> Brent Firms Up on Supply Tightness </td>
   <td style="text-align:left;"> Brent crude futures held above $75 per barrel on Thursday, hovering near 4-week highs after US crude stockpiles declined more than expected. US inventories fell by 4.72 million barrels, its fourth straight weekly draw and well above market estimates for a 2.75 million barrel decline. Tightness in supply has also been exacerbated by an energy crunch in Europe and supply disruptions in Africa. Natural gas prices in Europe surged to record highs as flows from a key Russian pipeline stopped, forcing some countries to boost electricity imports and burn oil to meet demand. In Libya, the National Oil Company said that production has been shut in several oilfields by members of the Petroleum Facilities Guard, while in Nigeria, Royal Dutch Shell halted crude shipments from the Forcados export terminal citing force majuere after the obstruction of a tanker path by a malfunctioning barge. Elsewhere, positive news developments around the omicron variant lifted market sentiment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/coincident-index </td>
   <td style="text-align:left;"> 2021-12-23 13:06:00 </td>
   <td style="text-align:left;"> Japan Coincident Index Posts 1st Rise in 4 Months </td>
   <td style="text-align:left;"> The index of coincident economic indicators in Japan, which consists of a range of data including factory output, employment, and retail sales, was at 89.8 in October 2021, compared with the flash figure of 89.9 and a final 88.7 a month earlier, which was the lowest reading since November 2020. The latest reading marked the first rise in the index in four months, as coronavirus-related disruptions eased. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/leading-economic-index </td>
   <td style="text-align:left;"> 2021-12-23 13:04:00 </td>
   <td style="text-align:left;"> Japan Leading Economic Index Revised Downward </td>
   <td style="text-align:left;"> The index of leading economic indicators in Japan, which is a gauge of the economy a few months ahead and is compiled using data such as job offers and consumer sentiment, was revised lower to 101.5 in October 2021, compared with a preliminary reading of 102.1, and after a final 100.2 a month earlier, which was the lowest figure in 7 months. This marked the highest level since July, amid a surge in vaccinations and easing supply-chain disruptions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/singapore/inflation-cpi </td>
   <td style="text-align:left;"> 2021-12-23 13:04:00 </td>
   <td style="text-align:left;"> Singapore Inflation Rate at Near 9-Year High </td>
   <td style="text-align:left;"> Singapore's annual inflation rate climbed to 3.8% in November 2021 from 3.2% in October and compared with market consensus of 3.35%, pointing to the highest figure since February 2013. Main upward pressure largely pressure came from cost of food (1.9% vs 1.7% in October); housing (3.1% vs 2.7%), mostly due to accommodation; healthcare (1.5% vs 1.7%), led by outpatient services and hospital services; transport (14.2% vs 11.1%), due to private transport; recreation &amp; culture (2% vs 2.1%), led by recreational &amp; cultural services; and education (1.6% vs 1.6%), led by tuition &amp; other fees. By contrast, declines were seen in cost of clothing (-6.6% vs -3.2%); communication (-1.2% vs -1.6%); and miscellaneous goods &amp; services (-0.1% vs -0.6%). Core consumer prices rose 1.6% yoy, the most since March 2019, compared with estimates and October's figure of 1.5%. On a monthly basis, consumer prices went up 1.0%, the most since February 2013, after a 0.3% gain in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2021-12-23 13:02:00 </td>
   <td style="text-align:left;"> Oil Holds Gains on US Stock Draw </td>
   <td style="text-align:left;"> WTI crude futures held above $72 per barrel on Thursday, hovering near 4-week highs after US crude stockpiles declined more than expected. US inventories fell by 4.72 million barrels, its fourth straight weekly draw and well above market estimates for a 2.75 million barrel decline. Tightness in supply has also been exacerbated by an energy crunch in Europe and supply disruptions in Africa. Natural gas prices in Europe surged to record highs as flows from a key Russian pipeline stopped, forcing some countries to boost electricity imports and burn oil to meet demand. In Libya, the National Oil Company said that production has been shut in several oilfields by members of the Petroleum Facilities Guard, while in Nigeria, Royal Dutch Shell halted crude shipments from the Forcados export terminal citing force majuere after the obstruction of a tanker path by a malfunctioning barge. Elsewhere, positive news developments around the omicron variant lifted market sentiment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/23/europe/natural-gas-green-hydrogen-fossil-fuel-lobbying-climate-cmd-intl/index.html </td>
   <td style="text-align:left;"> 2021-12-23 13:01:29 </td>
   <td style="text-align:left;"> Energy: The world is addicted to natural gas. Fossil fuel companies are fighting to keep it that way - CNN </td>
   <td style="text-align:left;"> (CNN)Imagine a world entirely free of fossil fuels. That's no longer such an abstract concept, as most of the everyday things we do can be powered by electricity -- driving a car, heating a home, charging a phone or computer -- and all that energy could come from sources like the wind, the sun and the natural movement of water.                                                                                                                                                   , For industries that need more oomph than solar or wind can offer -- like aviation, steel and concrete -- there's hydrogen. And it's everywhere.                                                                                                                                                                                                                                                                                                                                              , There's a lot of buzz and billions of dollars being poured into the hydrogen industry, but not all types of hydrogen are created equal. Hydrogen is the most abundant element on the planet, but it needs to be isolated from its source, and that in itself takes energy. At the moment, it's mostly derived from fossil fuels -- natural gas, coal and oil -- in what's called "gray" hydrogen. If the carbon-dioxide (CO2) emitted during production is captured, you get "blue" hydrogen., As governments around the world devise new energy strategies to rapidly remove the carbon from their economies, major fossil fuel companies are lobbying hard to keep blue hydrogen in the mix. In doing so, energy and climate experts say, they are locking in the global use of natural gas, a planet-warming fossil fuel, potentially for decades to come.                                                                                                                               , The most promising hydrogen for the climate is really the "green" sort, which is derived from water and is processed using 100% renewable energy, making it a potential zero-emissions power source. Green hydrogen is seen as a game-changing solution to emissions in the heaviest of industries, but it has a long way to go -- less than 1% of the world's hydrogen today is green, according to Fitch Ratings. The rest comes from fossil fuels.                                        , An analysis provided to CNN from the independent climate think tank InfluenceMap, which uses data to track the influence of business and finance on climate policy, found that several major fossil fuel companies are using the hydrogen hype to keep natural gas on the playing field, and that's having an impact on a crucial upcoming decision in the European Union.                                                                                                                   , The EU's 27 countries are so divided on the future role of natural gas that the bloc's executive arm, the European Commission, has for months failed to deliver what should be a simple list of energy sources that it considers sustainable.                                                                                                                                                                                                                                                , After several delays, the decision was again postponed on this week, as countries squabbled over whether gas -- as well as nuclear power -- should make the list, and whether they should be called "green" or "transitional" forms of energy.                                                                                                                                                                                                                                               , Earlier draft versions of the list -- known as the Sustainable Finance Taxonomy -- made no mention of gas or nuclear, a source close to the talks told CNN, and now EU officials are publicly saying they will almost certainly be included. That could allow natural gas operations to carry on with a green stamp of approval and unleash a wave of private investment and green recovery public funds to new projects.                                                                    , In an opinion piece for the website Euractiv, Greta Thunberg and follow climate activists described the list as "fake climate action."                                                                                                                                                                                                                                                                                                                                                       , Using a database of more than 350 of the world's largest companies, InfluenceMap identified a number of major fossil fuel companies that have been active in lobbying the EU on the sustainable fuels decision, as well as two other policies on gas and hydrogen. The three most active companies were Equinor, TotalEnergies and BP, the analysis concludes.                                                                                                                               , Gas industry associations representing some of the biggest fossil fuel companies operating in Europe are also arguing that natural gas in new projects could be blended with hydrogen -- including blue hydrogen -- to make it "cleaner." Vivek Parekh, an InfluenceMap analyst, described this lobbying to CNN as a "slow creep" of natural gas back into EU energy policy.                                                                                                                 , "The positions put out initially by the European Commission looked to push fossil gas infrastructure down the back road, and try to avoid it as much as possible," Parekh said.                                                                                                                                                                                                                                                                                                              , "But it looks like the gas industry -- after such a long fight -- has managed to weaken the sustainability criteria in its favor. And that essentially secures the role of fossil gas and its long-term energy future. This is in the European Union, which is supposed to be a policy leader when it comes to climate."                                                                                                                                                                     , The EU has one of the most ambitious climate plans in the world, with a goal enshrined in law to reduce emissions by 55% by 2030, from levels in 1990. Its policies tends to influence those in other parts of the world, making this decision particularly consequential.                                                                                                                                                                                                                   , Pascal Canfin, the EU lawmaker who chairs the bloc's powerful environment committee, said he was hopeful of a compromise to break the impasse. One proposal put forward, Canfin told CNN, is to include gas but impose a limit to how much carbon dioxide (CO2) new projects should be allowed to emit. Another could be to only allow new gas projects when they replace coal, and a "sunset clause" ending any new gas infrastructure as of December 31, 2030.                             , "So here are three key conditions under which you can define your design, the space where gas can be considered as useful for the transition, even if it's fossil," he said.                                                                                                                                                                                                                                                                                                                 , Equinor and TotalEnergies were among companies that campaigned against the proposed CO2 limit, according to InfluenceMap.                                                                                                                                                                                                                                                                                                                                                                    , Equinor -- which is investing in green hydrogen but also continues to drill for more oil and gas -- confirmed to CNN it had been engaging with the EU on the policy and said it would support the CO2 limit in electricity and heat projects, but that it would not in other circumstances, for example, new gas projects to help a region transition from coal.                                                                                                                             , "Like many member state governments we see natural gas as key to the EU's decarbonization efforts," the company said in a statement to CNN. It emphasized that natural gas can be "decarbonized" through carbon capture and storage.                                                                                                                                                                                                                                                         , But no technology that exists today can remove 100% of the CO2 from natural gas, and a landmark study on blue hydrogen from Cornell University in August showed that blue hydrogen, at the moment, emits 20% more than natural gas in the first place. That's partly because the greenhouse gas methane tends to leak in the carbon capture process.                                                                                                                                         , French company TotalEnergies did not comment on its position on the emissions limit, but said it was investing in both blue and green hydrogen. It argued natural gas is currently "the best option for providing the world with the energy it needs while combating global warming," and is even "a champion of energy transition."                                                                                                                                                         , BP did not reply to CNN's request for comment.                                                                                                                                                                                                                                                                                                                                                                                                                                               , A growing gas addiction                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Despite its clean-sounding name, natural gas is a major contributor to the climate crisis. It is made mostly of methane, a greenhouse gas more than 80 times more potent than carbon-dioxide in the short term. It surged in use in the '70s and took off in the '90s, when it was sold as a "bridge fuel" -- a cleaner alternative to coal and one that would eventually be dropped when renewable energy took off.                                                                         ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , But the world has become somewhat addicted to gas, and that "bridge" has become so long, governments are realizing they don't really know when and where it ends.                                                                                                                                                                                                                                                                                                                            , Global use of natural gas is at an all-time high, according to the International Energy Agency. In the EU, it's come down slightly since a 2010 peak, but not that much, and is still higher than levels in the '90s.                                                                                                                                                                                                                                                                        , The scale of growth in the EU is a clear sign that, even in Europe, gas isn't going anywhere soon.                                                                                                                                                                                                                                                                                                                                                                                           , Data from Global Energy Monitor (GEM) shows that at the end of 2020, there were around 17,000 kilometres (around 1,500 miles) of gas pipeline in development in the EU. That's 65 projects across 23 nations worth 72.6 billion euros ($81.8 billion). There were another 15.5 billion euros-worth of projects for liquified natural gas.                                                                                                                                                    , And, depending on how they are built, new natural gas projects tend to stick around for some time.                                                                                                                                                                                                                                                                                                                                                                                           , Greig Aitken, who manages GEM's Europe Gas Tracker, said that pipelines and the gas plants they serve typically have lifetimes of 30 to 40 years, warning that any new gas infrastructure will either lock in the fossil fuel and undermine the bloc's climate goals or force the projects to be abandoned.                                                                                                                                                                                  , "A tipping point has been reached, and there really should be no new commissioning of gas infrastructure from now given the timelines involved, unless companies and their financial backers actually welcome the idea of having stranded assets on their books," Aitken said.                                                                                                                                                                                                               , So where does that leave green hydrogen? The industry needs a windfall in funding to build more electrolyzers -- the machines needed to extract hydrogen from water -- as well as a huge increase in renewable energy sources.                                                                                                                                                                                                                                                               , A decision like the EU's on taxonomy could potentially mean money that could be going to green hydrogen is diverted to blue.                                                                                                                                                                                                                                                                                                                                                                 , But there is huge momentum. A new green hydrogen project appears to pop up somewhere in the world on a weekly basis, and even fossil fuel companies promoting blue hydrogen are beginning to look at green as well. The International Renewable Energy Agency says that green hydrogen could become cheaper than blue hydrogen by 2030 if -- and it's a big if -- the industry gets enough buy-in.                                                                                           , "Green hydrogen proves that the world has a clean, practical, implementable way out of global warming," said Andrew Forrest, whose company Fortescue Future Industries is investing heavily in green hydrogen.                                                                                                                                                                                                                                                                               , Forrest, an Australian who made his fortune from mining with the Fortescue Metals Group, is betting big on green hydrogen to not only decarbonize his company's entire mining operation, but also to transform Fortescue into a global renewables giant.                                                                                                                                                                                                                                     , To Forrest, all this talk about blending blue hydrogen into natural gas is a distraction. The energy transformation has to happen now, and not lock in yet another "bridge" fuel, he said.                                                                                                                                                                                                                                                                                                   , "Fossil fuel companies trying to tell the world that natural gas, blue hydrogen or gray hydrogen are a solution to climate change are lying," Forrest said.                                                                                                                                                                                                                                                                                                                                  , "Blue hydrogen, gray hydrogen, any type of hydrogen that is not green is dirty and uses fossil fuels to make it. It is like clean coal or cancer-free tobacco."                                                                                                                                                                                                                                                                                                                              , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/faa-seeks-engine-fixes-to-get-grounded-boeing-777s-back-in-service </td>
   <td style="text-align:left;"> 2021-12-23 12:55:09 </td>
   <td style="text-align:left;"> FAA seeks engine fixes to get grounded Boeing 777s back in service </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                               , The Federal Aviation Administration on Wednesday proposed fixes to prevent engine coverings from breaking apart on certain Boeing Co. 777 aircraft, as they did in a series of incidents including on a United Airlines jet over Colorado earlier this year.                                                                    , The proposed changes, which would allow the aircraft to return to service, are aimed at strengthening engine covers to prevent plane parts from detaching midair and striking aircraft or falling to the ground.                                                                                                                , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                     , That is what happened when a United 777’s engine failed shortly after takeoff from Denver in February: Its external cover, damaged by a broken fan blade, broke apart and metal components fell into yards in a nearby suburb. No one was injured and the flight landed safely.                                                 , The subset of Boeing 777 jets powered by Pratt &amp; Whitney engines were effectively grounded after that episode. The FAA ordered immediate inspections of the engine fan blades for cracks that could lead to more potential failures.                                                                                            , BOEING, AIRBUS URGE BIDEN ADMINISTRATION TO POSTPONE 5G ROLLOUT                                                                                                                                                                                                                                                                 , The FAA on Wednesday also proposed an enhanced inspection protocol for the fan blades used in the engines and other components, with specific corrective actions depending on the results.  Pratt &amp; Whitney, a unit of Raytheon Technologies Corp. , said in a written statement that such inspections are already under way.   , WASHINGTON (Feb. 22, 2021) — This image taken Feb. 22, 2021, shows the damage to the number 2 engine of United Airlines flight 328, a Boeing 777-200, following an engine failure incident. (NTSB photo) (NTSB)                                                                                                                 , United, the only U.S. carrier flying that type of plane, has 52 of the aircraft, some of which had been in storage at the time of the incident. The airline had hoped to resume flying the wide-body jets this summer, but a spokesman said Wednesday that the airline will be able to return them to its fleet early next year., United said the proposed changes were a "good outcome" for the industry. The airline said it has been working closely with the FAA, Boeing and Pratt &amp; Whitney, and many of its affected engines have already gone through the proposed inspections.                                                                            , Boeing said in a written statement that it supports the FAA’s guidance on inspection requirements and will work with its customers and with Pratt &amp; Whitney.                                                                                                                                                                    , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                         , The incident in Denver was the third of its kind in recent years. Another engine cover broke apart on a Japan Airlines Co. flight in late 2020, and a similar incident occurred on another United plane en route to Hawaii in early 2018.                                                                                       , Write to Alison Sider at alison.sider@wsj.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/business-leaders/elon-musks-share-selling-spree-tops-15-billion </td>
   <td style="text-align:left;"> 2021-12-23 12:03:16 </td>
   <td style="text-align:left;"> Elon Musk’s share-selling spree tops $15 billion </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                          , Elon Musk on Wednesday unloaded more Tesla Inc. stock, bringing the total value of his share sales to more than $15 billion since the billionaire last month began a string of such transactions.                                                                                                                                          , The sales came as Mr. Musk exercised more than 2.1 million Tesla stock options, according to regulatory filings late Wednesday. He sold more than 934,000 of the shares in the company he runs, valued at around $928.6 million, to cover tax withholdings, the disclosures state.                                                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                , The latest transactions are part of a plan Mr. Musk set on Sept. 14 to exercise options and sell shares. The options he’s exercised are part of a tranche of around 23 million vested stock options set to expire in August 2022. He has exercised about 21.3 million of those options.                                                    , Mr. Musk said Wednesday on Twitter before the filings became public, "There are still a few tranches left, but almost done."                                                                                                                                                                                                               , MUSK RIPS LIZ WARREN AFTER TWITTER SPAT: 'IF YOU COULD DIE BY IRONY, SHE WOULD BE DEAD'                                                                                                                                                                                                                                                    , After setting the stock plan, Mr. Musk last month polled Twitter users about whether he should sell 10% of his Tesla stock; those who voted on the social-media platform endorsed the idea. The chief executive began exercising Tesla stock options and selling shares in the company on Nov. 8.                                          , Mr. Musk held around 170.5 million Tesla shares when he posted the Twitter poll and pledged to sell 10% of those holdings. He has sold around 14.8 million shares so far, leaving him at least a little more than $2 million in stock sales short to meet his commitment. The precise number depends on how he defines his ownership stake., Exercising Tesla stock options has netted Mr. Musk more shares than he held at the time of the Twitter poll. His Tesla stock holdings now top 177 million shares.                                                                                                                                                                          , Mr. Musk has a net worth of around $261 billion, making him the richest person on the Bloomberg Billionaires Index. He also has sold some stock over recent weeks not related to the stock options.                                                                                                                                        , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                    , Tesla’s shares slumped after Mr. Musk began his selling last month. The stock, which closed up 7.49% on Wednesday at $1,008.87, is down more than 17% from the day Mr. Musk took the Twitter poll.                                                                                                                                         , Write to Meghan Bobrowsky at Meghan.Bobrowsky@wsj.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/22/asia/afghanistan-taliban-hunger-crisis-children-intl-hnk-dst/index.html </td>
   <td style="text-align:left;"> 2021-12-23 11:00:35 </td>
   <td style="text-align:left;"> Afghanistan hunger crisis: Children face starvation under Taliban rule - CNN </td>
   <td style="text-align:left;"> WARNING: SOME OF THE IMAGES AND VIDEO IN THIS STORY ARE DISTURBING                                                                                                                                                                                                                                                                                  ,  (CNN)Kamila is almost 3 years old, but she weighs just 11 pounds (5 kilograms). Her wrinkled skin sags off her skeletal limbs and stretches around her distended belly.                                                                                                                                                                            , Kamila has been malnourished for eight months now, says her grandmother Bilqis, as she attempts to soothe her in a sparse hospital ward filled with other emaciated children in Kandahar, southern Afghanistan.                                                                                                                                     , Too weak to cry, the little girl rubs her ears in pain.                                                                                                                                                                                                                                                                                             , "Her mother is sick and we are poor people," Bilqis says. "She tried to breastfeed her but had no milk to give."                                                                                                                                                                                                                                    , Kamila's family are among millions of Afghans struggling to survive severe food shortages during a harsh winter and economic crash. Rights organizations are pleading for more foreign aid, arguing the most vulnerable groups -- women and children -- are suffering.                                                                              , In a statement to CNN, the ruling Taliban acknowledged the country's "economic problems" -- but vehemently denied there was a crisis, calling such claims "fake."                                                                                                                                                                                   , "No one will starve cause there is no famine and the cities are full of food," said Taliban spokesperson Zabihullah Mujahid -- contradicting graphic images of starving children.                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                     , Even before the Taliban seized power in Afghanistan in August, poverty and food insecurity were widespread due to back-to-back droughts, economic decline, protracted conflict and the pandemic.                                                                                                                                                    , But three months after the takeover, the crisis has rapidly worsened. Billions of dollars of foreign development aid has dried up, depriving the country of money that had been propping up the economy, key services and aid workers.                                                                                                              , As winter sets in, nearly 23 million people -- more than half the population -- are facing extreme levels of hunger, according to the United Nations. At least a million children under 5 are at risk of dying from starvation.                                                                                                                     , Conditions are so bad that some hospitals, without money for fuel, have resorted to cutting down trees to heat patients' rooms, and aid groups warn the situation will only get worse if the international community doesn't act now.                                                                                                               , Desperate families sell everything                                                                                                                                                                                                                                                                                                                  , The unforgiving weather has exacerbated food shortages.                                                                                                                                                                                                                                                                                             , The vast majority of Afghans rely on agriculture for their livelihoods, but the country has lost 40% of its harvest this year to the drought, according to the World Food Programme (WFP). As food supplies dwindle, the cost of staples like wheat and bread have skyrocketed.                                                                     , "We only have water and bread -- sometimes we have it, but sometimes there's nothing to eat," said Musafer, a laborer and shopkeeper who goes by one name.                                                                                                                                                                                          , Earlier this month, he took his daughter to Ghor Provincial Hospital in the provincial capital Chagcharan.                                                                                                                                                                                                                                          , Razia is almost 3 years old, but her ribs and spine jut out with horrifying clarity as she buries her face in her mother's lap. This is her third hospital visit in just eight months -- and she's not getting better.                                                                                                                              , "There is no work, no income, no food to bring her," Musafer said. "Every time I see her I get upset."                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                     , Richard Trenchard, the Food and Agricultural Organization Representative in Afghanistan, described the situation as "disastrous" in a November statement.                                                                                                                                                                                           , "Every farmer we've spoken to has lost almost all of their crops this year, many were forced to sell their livestock, they have accumulated enormous debts and simply have no money," he said.                                                                                                                                                      , Before the Taliban's takeover, poverty had been common in many of the country's rural areas -- but now, middle class and urban residents have also been plunged into despair.                                                                                                                                                                       , Government workers and school principals -- many of whom have gone months without pay -- are among those queuing up for food rations and medical attention, the WFP warned. Across the country, families are selling their clothing, furniture, livestock -- sometimes even entire houses -- for food, the agency said in a news release.           ,                                                                                                                                                                                                                                                                                                                                                     , The risk of famine had once been restricted to rural areas -- but now, 10 out of 11 of Afghanistan's most densely populated urban areas are facing emergency levels of food insecurity, warned Deborah Lyons, head of the UN Assistance Mission in Afghanistan, in November.                                                                        , In internal displacement camps, some of the poorest families who have nothing left to sell resort to offering their daughters as child brides. It's the only way to keep their other children alive, several parents told CNN.                                                                                                                      , In the statement to CNN, Mujahid, the Taliban spokesperson, said Afghan people urgently need food and medical supplies.                                                                                                                                                                                                                             , He said the Taliban is "trying to increase this aid" and distribute it to the people, along with humanitarian groups.                                                                                                                                                                                                                               , Overwhelmed hospitals                                                                                                                                                                                                                                                                                                                               , Hospitals have been overwhelmed with starving patients, even as medical supplies and staffing run short.                                                                                                                                                                                                                                            , Afghanistan's nationwide health program had previously been financed by the World Bank -- but funding came to a halt in August, leaving 2,300 facilities without the means to buy medical supplies or pay salaries.                                                                                                                                 , By late September, most of those hospitals and clinics had closed, with fewer than one in five still open, according to a UN report.                                                                                                                                                                                                                , Before the Taliban takeover, there were 39 hospitals in Afghanistan that treated Covid-19; now, only three or four are still functioning, said Dr. Paul Spiegel from Johns Hopkins University, who has just returned from Afghanistan, as a consultant for the WFP.                                                                                 , The World Health Organization is among agencies that have resumed airlifting essential medical supplies to Afghanistan; the four shipments of supplies so far should cover 1.5 million patients, WHO said in November.                                                                                                                              , Meanwhile, the UN Development Programme provided $15 million to Afghanistan's health sector in November, helping pay wages to more than 23,000 health workers, according to a UN news release.                                                                                                                                                      , But many humanitarian workers and doctors on the ground warn it's not enough.                                                                                                                                                                                                                                                                       , At the Ghor Provincial Hospital, up to 100 mothers and children arrive each day seeking treatment for malnutrition -- as well as a host of other illnesses like measles, diarrhea, cold and flu, said Faziluhaq Farjad, head of the hospital's malnutrition ward.                                                                                   , These problems are all linked, he added -- malnourished mothers and children become more susceptible to illness and infection. Often they have to travel long distances to get to hospitals and arrive even weaker, he said.                                                                                                                        , But the hospital's supply of equipment and medicine is rapidly dwindling -- the malnutrition wing only has milk left to provide for its patients.                                                                                                                                                                                                   , "Almost 70% of the cases are severe and this is in the city -- imagine how bad the districts are," Farjad said. "If nobody pays attention it's going to get much worse."                                                                                                                                                                            , One of Farjad's patients, 1-year-old Nasrin, is so severely malnourished she's spent almost half her life in hospital, said her father, Abdul Rauf, who works as a laborer.                                                                                                                                                                         , "Every 20 days, every 10 days, we are at the hospital," Rauf said. "This is my life and we spend it like this."                                                                                                                                                                                                                                     , Calls for foreign aid                                                                                                                                                                                                                                                                                                                               , Foreign governments' efforts to choke the Taliban of funds are having the unintended effect of starving the Afghan people, say aid organizations, who are calling on donor countries to change their strategy.                                                                                                                                      , Spiegel, the doctor who visited Afghanistan for WFP, urged foreign countries to reconsider their move to freeze Afghan assets after the takeover, including funding for government-run hospitals.                                                                                                                                                   , "The US, UK, EU have to make some decisions quickly or its going to be too late and there's going to be a tremendous amount of unnecessary death," he said.                                                                                                                                                                                         , He acknowledged the desire of foreign governments to avoid legitimizing the Taliban and hold it to account but said the existing sanctions aren't nuanced enough.                                                                                                                                                                                   , "The goal of change is a good goal, but is it worth tens of thousands of deaths?" he said.                                                                                                                                                                                                                                                          , The European Union pledged a 1 billion euro ($1.12 billion) aid package in October, and the World Bank's board recently committed $280 million to the UN Children's Fund and the WFP. The United States has also contributed nearly $474 million in humanitarian aid -- separate from development aid -- this year.                                 , But even the international funds that have been pledged are just a fraction of Afghanistan's $9.5 billion frozen assets. And those funds are being channeled to international organizations already working in Afghanistan, according to statements from the US and EU governments -- meaning the money is not accessible to Afghan banks or public., A number of US lawmakers, largely Democrats, have also urged the Biden administration to release frozen Afghan funds to the UN as humanitarian assistance.                                                                                                                                                                                          , When pressed Monday about the impact of sanctions on Afghan civilians, Ned Price, spokesperson for the US State Department, said Washington had warned the Taliban before the takeover that seizing control would jeopardize foreign aid from the US and other countries.                                                                           , He said before the US can consider any future relationship with the ruling Taliban, the Islamist group must make certain human rights commitments, including forming an inclusive government. The US remains committed to assisting the Afghan people, Price said, pointing to the humanitarian aid provided so far.                                , Facing mounting pressure, the administration said Wednesday it would lift some restrictions on the type of aid humanitarian organizations can provide to Afghanistan, which will allow greater support for educational programs, including paying teachers' salaries.                                                                               ,                                                                                                                                                                                                                                                                                                                                                     , Martin Griffiths, the UN Emergency Relief Coordinator, said Afghanistan will not get through the winter on emergency aid alone.                                                                                                                                                                                                                     , "The need for liquidity and stabilization of the banking system is now urgent -- not only to save the lives of the Afghan people but also to enable humanitarian organizations to respond," he said in a statement on Sunday.                                                                                                                       , For Afghan families on the ground, there is nothing to do but wait for help to arrive. After 15 days of treatment, Nasrin was released from the hospital, weighing just over 14 pounds (6 kilograms). The family returned home, where there are four other hungry children waiting.                                                                 , "I ask the international community to help every poor person who are suffering from poverty and hunger," said Rauf, Nasrin's father. "If they don't help us, I will lose my kids."                                                                                                                                                                  , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 10:48:01 </td>
   <td style="text-align:left;"> Japanese Shares Gain on Easing Omicron Fears </td>
   <td style="text-align:left;"> The Nikkei 225 Index rose 0.3% towards 28,650 while the broader Topix Index edged up 0.4% to 1,980 on Thursday, with technology stocks extending gains from the previous session, as investor sentiment was lifted on easing fears around the omicron variant. The US FDA granted emergency use authorization for Pfizer’s Covid treatment pill on Wednesday, the first oral antiviral drug cleared during the pandemic. Some of the top gainers among technology firms include Lasertec (2.6%), Recruit Holdings (2.7%), Japan Data Science (9.8%),Kohoku Kogyo (6.5%), Sumco COrp (1.6%) and Mitsui High Tec (3.6%). Meanwhile, some of the market laggards were Hitachi (-3.5%), Eisai Co (-8.7%), Fronteo (-1.7%), Fast Retailing (-1%), Z Holdings (-0.9%) and Peptidream (-4.4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/foreign-bond-investment </td>
   <td style="text-align:left;"> 2021-12-23 10:23:18 </td>
   <td style="text-align:left;"> Japanese Bond Investors Decrease Foreign Holdings </td>
   <td style="text-align:left;"> Japanese investors turned net sellers of foreign bonds amid a safe-haven inflow into yen-denominated bonds, as domestic investors pulled capital out of foreign assets due to uncertainties around the omicron variant and the resulting currency risks. Japanese institutions also trimmed foreign bond holdings to search for higher yields and to narrow the mismatch of their assets and liabilities. Japanese investors sold a net foreign bonds worth 1,588.5 billion yen in the week ending Dec. 18, reversing from a net buying of 458.9 billion yen in the previous week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/foreign-stock-investment </td>
   <td style="text-align:left;"> 2021-12-23 09:59:54 </td>
   <td style="text-align:left;"> Foreign Outflow in Japanese Stocks Accelerates </td>
   <td style="text-align:left;"> Foreigners were net sellers of Japanese equities for a fifth straight week as investor positioning remained cautious amid fears surrounding the omicron variant and its impact on economic growth and inflation. The market also underwent wild fluctuations amid a succession of hawkish monetary policy announcements from major central banks. Foreigners sold stocks worth a net 841.3 billion yen in the week to Dec. 18, accelerating from a net selling worth 604.3 billion yen in the prior week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2021/12/21/afghanistan-starvation-coren-lead-intl-pkg-vpx.cnn </td>
   <td style="text-align:left;"> 2021-12-23 09:57:02 </td>
   <td style="text-align:left;"> Afghanistan on the brink of humanitarian catastrophe, UN says - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 09:21:35 </td>
   <td style="text-align:left;"> Australian Shares Extend Gains, Syrah Soars </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index climbed 0.2% towards 7,380 on Thursday, helped by gains in gold and other precious metals miners due to a surge in the underlying commodity prices. Fears around the omicron variant also receded following positive news developments, with countries such as the US and Australia ruling out lockdowns. Among the top gainers were gold and lithium explorers including Pilbara Minerals (1.4%), Newcrest Mining (0.7%), Evolution Mining (3.2%), Northern Star Resources (0.8%), Lake Resources (2.8%) and St Barbara (2.1%). Meanwhile, Syrah Resources soared 23% after announcing a four-year deal to supply graphite materials to electric carmaker Tesla from its plant in the US state of Louisiana. Elsewhere, Bega Cheese dropped 12% after the company warned of a hit to its 2022 fiscal earnings from strong competition for dairy supply in Australia, high global prices and impact from the coronavirus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 08:41:00 </td>
   <td style="text-align:left;"> US Futures Flat After Two-Day Recovery Rally </td>
   <td style="text-align:left;"> US stock futures were little changed on Thursday after climbing for a second day in the previous session, as market fears that the omicron variant would derail economic growth somewhat receded, with president Biden saying the US will not go back to lockdown. Dow Jones, S&amp;P 500 and Nasdaq 100 futures swung marginally to small gains and losses. All three major averages rallied on Wednesday following positive economic data that eased worries of omicron’s impact on the economy. Investors weighed upbeat consumer confidence levels and an upwardly revised estimate for domestic GDP. The FDA also granted emergency use authorization for Pfizer’s Covid pill on Wednesday, the first oral antiviral drug against the virus. Elsewhere, the White House said it is resuming talks on the massive Build Back Better bill with senator Manchin. All sectors gained, led by consumer cyclical, technology, real estate and healthcare stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/private-sector-credit </td>
   <td style="text-align:left;"> 2021-12-23 08:41:00 </td>
   <td style="text-align:left;"> Australia Private Credit Growth at 5-Month High </td>
   <td style="text-align:left;"> Private sector credit in Australia rose by 0.9 percent month-over-month in November 2021, accelerating from a 0.5 percent increase in the previous month. This was the strongest pace of expansion since June,  lifted by a strong pickup in credit for both business (1.6 percent vs 0.4 percent in October) and personal (0.6 percent vs flat reading). In addition, housing credit gained slightly faster (0.7 percent vs 0.6 percent). Through the year to November, private credit grew 6.6 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/politics/2021/12/22/mcconnell-asks-manchin-to-join-gop-raju-live-tsr-vpx.cnn </td>
   <td style="text-align:left;"> 2021-12-23 08:03:01 </td>
   <td style="text-align:left;"> McConnell is urging Manchin to join Republican Party - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/amazon-china-books-xi-jinping-reviews </td>
   <td style="text-align:left;"> 2021-12-23 07:16:29 </td>
   <td style="text-align:left;"> Amazon reportedly took down reviews of Chinese president's book after demands </td>
   <td style="text-align:left;"> Ronald Reagan Institute Director Roger Zakheim discusses Amazon reportedly partnering with China's propaganda arm in 2018, U.S. companies bending to the communist nation and the Bagram Air Base.                                                                                                                                                                                                                              , Retail giant Amazon reportedly scrubbed reviews of Chinese President Xi Jinping's book from one of its sites and helped promote other forms of propaganda.                                                                                                                                                                                                                                                                      , Reuters reported that Amazon received an "edict" from Beijing. A person familiar with the edict said a negative review of Xi's book prompted the bookseller to stop allowing any customer ratings and reviews in the country. Another person familiar with the story said, "I think the issue was anything under five stars." The company also partners with the state-owned firm China International Book Trading Corp (CIBTC)., Volume three of Xi's book was reportedly listed as a bestseller on China Books, an Amazon site created in partnership with an arm of the nation's propaganda apparatus. Although the project flopped financially, a person who has been involved with it described China Books as "a high-level photo-op."                                                                                                                      , Xi Jinping's "The Governance of China III" books, translated in English, are seen on sale in a bookstore Dec. 15, 2021, in Beijing, China. The book is part of a three-volume collection containing speeches and writings by Chinese President Xi Jinping.                                                                                                                                                                      , Despite its bestseller status, volume three of Xi's book recently showed a sales rank of 1,347,071 while another purported bestseller on COVID-19 ranked 10,654,483.                                                                                                                                                                                                                                                            , AMAZON SAYS IT 'WON'T SELL BOOKS THAT FRAME LGBTQ+ IDENTITY AS A MENTAL ILLNESS'                                                                                                                                                                                                                                                                                                                                                , Another book reportedly extols life in Xinjiang, the site of Uyghur persecution that the United States has designated a genocide.                                                                                                                                                                                                                                                                                               , Amazon.com offers Xi's book, "The Governance of China," with reviews from Facebook CEO Mark Zuckerberg and HuffPost.                                                                                                                                                                                                                                                                                                            , "I've also bought copies of this book for my colleagues," Zuckerberg said. "I want them to understand socialism with Chinese characteristics."                                                                                                                                                                                                                                                                                  , Logos of Amazon and Amazon Prime are pictured on vehicles outside the Amazon Fulfilment Centre in Altrincham, near Manchester, Britain, Nov. 26, 2021. (REUTERS/Carl Recine/File Photo) (Reuters Photos)                                                                                                                                                                                                                        , Another from BBC: "Certainly [President Xi] is working hard at being the confident father to the nation, developing an image which is much less constrained and technocratic than his immediate predecessors."                                                                                                                                                                                                                  , Amazon has indicated it seeks to be neutral on potentially problematic content. According to Reuters, a 2018 internal briefing showed the company noting "Ideological control and propaganda is the core of the toolkit for the communist party to achieve and maintain its success."                                                                                                                                           , AMAZON, CVS, WALGREENS TO LIMIT COVID-19 TEST PURCHASES                                                                                                                                                                                                                                                                                                                                                                         , The document added: "We are not making judgement on whether it is right or wrong."                                                                                                                                                                                                                                                                                                                                              , "As a bookseller, we believe that providing access to the written word and diverse perspectives is important," an Amazon spokesperson told FOX Business Wednesday. "That includes books that some may find objectionable, though we have policies governing which books can be listed for sale in every country and jurisdiction in which we operate."                                                                          , Chinese President Xi Jinping is seen in a video as people visit the Museum of the Communist Party of China Dec. 16, 2021, in Beijing, China. The museum was officially opened in June 2021. (Andrea Verdelli/Getty Images) (Getty Images)                                                                                                                                                                                       , The spokesperson maintained that Amazon's "relationship with CIBTC is entirely appropriate." CIBTC reportedly described their partnering as a "commercial relationship between two enterprises."                                                                                                                                                                                                                                , Last week's report raises questions about how tech giants like Amazon regulate content on a country-by-country basis. Twitter, for example, has encountered criticism for censoring former President Trump's tweets but allowing certain posts from Iran's Ayatollah Khamenei.                                                                                                                                                  , CLICK HERE TO GET FOX BUSINESS ON THE GO                                                                                                                                                                                                                                                                                                                                                                                        , Amazon also faced backlash earlier this year when it delisted conservative author Ryan T. Anderson's book, "When Harry Became Sally: Responding to the Transgender Moment." The book was published in 2018 and reached the top of the site's bestseller lists.                                                                                                                                                                  , "We carefully consider the content we make available in our stores, and we review our approach regularly," Amazon said, responding to a question from senators about why the book had originally been allowed on the site. "As described above, we have chosen not to sell books that frame LGBTQ+ identity as a mental illness." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/media/jimmy-johns-founder-inflation-match-fast-food-bill-minimum-wage </td>
   <td style="text-align:left;"> 2021-12-23 07:11:48 </td>
   <td style="text-align:left;"> Jimmy John’s founder predicts inflation will match fast food bill to minimum wage </td>
   <td style="text-align:left;"> Jimmy John Liautaud comments on the state of the economy in an interview with Fox News Digital.                                                                                                                                                                                               , The U.S. economy has been recently rocked by rising inflation and Jimmy John’s founder Jimmy John Liautaud predicted pricing will hit a new milestone in an interview with Fox News Digital.                                                                                                  , At Turning Point USA's AmericaFest, the sub shop dynamo pressed his confidence that inflation will spike the price of Americans' fast food bills to equal the minimum wage.                                                                                                                   , "This is coming," he said. "So if your minimum wage in New York is $17, that’s how much it’s going to be for lunch… I went to Arby’s and I got a 2 for $6, a shake, fries and that was $12.83 and that was in Illinois. So you’re right about there."                                         , JIMMY JOHN'S FOUNDER: ‘NO WAY’ SUB SHOP WOULD'VE BEEN SUCCESSFUL IN TODAY'S ECONOMY                                                                                                                                                                                                           , As inflation continues to trek higher, Liautaud explained why there’s no slowing it down.                                                                                                                                                                                                     , Jimmy John Liautaud addresses the state of the economy and shares the importance of entrepreneurship in America.                                                                                                                                                                              , "You cannot print $4 trillion, push it into the economy and have everything devalue," he said. "It is what it is. But you know what? As long as it’s run by the free market, I’m cool with it. Let the free market rocket… Get the government’s hands out of it."                             , In Biden’s economy today, Liautaud expressed there would be "no way" Jimmy John’s would’ve been able to get the start it did when first founded in 1983.                                                                                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                   , "No way I could’ve started Jimmy John’s in this climate," he said. "$52,000 wage for a manager and $15 an hour. It was a great idea, right? But who’s got all the money now? Jeff Bezos."                                                                                                     , Liautaud's American Dream transformed his first small shop built inside a two-car garage – where he served sandwiches for $2.10 apiece and Dixie cups of Coca-Cola for 25 cents – into a $3 billion company with 140,000 employees. Jimmy John’s now has more than 2,700 locations nationwide., CLICK HERE TO READ MORE ON FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/22/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2021-12-23 07:04:39 </td>
   <td style="text-align:left;"> Stock futures muted as market attempts to extend comeback rally to a third day </td>
   <td style="text-align:left;"> , Stock futures were little changed early Thursday morning following the second trading day in which equities climbed higher, as investors looked past earlier jitters about the spread of the omicron Covid variant.                                                                                                                                                                                                                                              , Futures contracts tied to the Dow Jones Industrial Average added 0.07%. S&amp;P 500 futures rose 0.06% and Nasdaq 100 futures were near the flatline.                                                                                                                                                                                                                                                                                                                , In regular trading, the Dow gained 0.7%, bringing its two-day rally to more than 800 points. The S&amp;P 500 climbed 1% to 4,696.56 and now sits 1% away from its record. The Nasdaq Composite climbed 1.2%. All three averages are on track to end the week higher.                                                                                                                                                                                                 , The rebound, which began Tuesday, follows a three-day losing streak for the major averages spurred by fears about the speed of the spread of the latest Covid-19 variant. It was the worst decline for the S&amp;P over a three-day period since September. For the Nasdaq, it was the worst three-day stretch since May.                                                                                                                                            , "December is a month where we're not supposed to see much volatility, but we have thanks to the omicron variant news," said Angelo Kourkafas, an investment strategist at Edward Jones. "The last two days we have seen a very strong rebound, and now we are actually within breathing distance of record highs. In our view this two-day rally reflects confidence that the economy will be able to successfully navigate the threat from the omicron variant.", Wall Street analysts are backing these global stocks to beat Big Tech next year                                                                                                                                                                                                                                                                                                                                                                                  , Hydrogen, chips and more: Fund managers and analysts name their top stocks for 2022                                                                                                                                                                                                                                                                                                                                                                              , Small-cap stocks could be ready to snap back in January led by these names, top strategist says                                                                                                                                                                                                                                                                                                                                                                  , Still, trading was relatively thin and is expected to continue to be so heading into the Christmas holiday.                                                                                                                                                                                                                                                                                                                                                      , Consumer discretionary and tech stocks were among the biggest gainers on the day Wednesday. Tesla shares jumped 7% after CEO Elon Musk said he's reached his goal of selling 10% of his shares for tax reasons.                                                                                                                                                                                                                                                  , On Wednesday the Food and Drug Administration granted emergency use authorization for Pfizer's Covid pill, the first oral antiviral drug against the virus. The drugmaker's shares gained about 1%.                                                                                                                                                                                                                                                              , Investors will get some key inflation data on Thursday, including prices for core personal consumption expenditures. Consumer sentiment numbers and jobless claims will also be released.                                                                                                                                                                                                                                                                        , — CNBC's Jesse Pound contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                      , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                 , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/media/kudlow-republicans-are-on-the-verge-of-historic-midterm-gains </td>
   <td style="text-align:left;"> 2021-12-23 06:53:23 </td>
   <td style="text-align:left;"> Kudlow: Republicans are on the verge of historic midterm gains </td>
   <td style="text-align:left;"> ‘Kudlow’ takes a look back at former President Trump’s historic tax cut.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Save America. Kill the bill. And tonight, I'm launching a new mantra: "Kill any new bills that may come next year."                                                                                                                                                                                                                                                                                                                                                                                                                                                           , But our supporters want unconditional surrender. No new bills that increase spending raise taxes, overregulate, destroy fossil fuels, and so forth. We are girding up for a New Year's battle. And just as our forces of good and "America first" whupped the wokes this year, we're getting ready to whup them again next year.                                                                                                                                                                                                                                              , Now, on a much happier note, today's the fourth anniversary of the signing of the Trump tax cuts which occurred on December 22, 2017. Here's a look at it: 3.2 trillion dollars in tax cuts for American families, including the doubling of the standard deduction and the doubling of the child tax credit. The typical family of four earning $75,000 will see an income tax cut of more than $2,000 – many much higher than that, slashing their tax bill in half.                                                                                                        , DEMOCRATS DESPERATE TO SAVE KEY PIECE OF BIDEN’S BIG SPENDING BILL                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , This was one of the most important pro-growth policies in the last 100 years. I equate them with the historic Reagan tax cuts of the 1980s, the JFK tax cuts of the 1960s, and the Harding-Coolidge-Mellon tax cuts of the 1920s. Each was followed by a massive prosperity wave.                                                                                                                                                                                                                                                                                             , Former Chair of Council of Economic Advisers Kevin Hassett joins ‘Kudlow’ to discuss Biden’s troubled economy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                , So did President Trump's historic tax cut. I don't care about all these left-wing critics, wokes, ankle-biters, and their constant nabobs of negativism. The facts – and I underscore the word "facts" – show that nearly every American benefited. But the blue-collar middle class and the lower-income brackets had much bigger benefits than the highest income earners. Average family incomes rose by a record pace. Unemployment sunk to 50-year lows with the biggest beneficiaries being African-Americans, Hispanics, and women. Poverty plunged. So did inequality., GOP SENATOR RIPS INTO PRESIDENT BIDEN’S TAX PLAN                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The animal spirits were back, America was competitive again globally, and businesses all around the world flocked here because of the new incentives created by the Trump tax cuts – big and small companies benefiting. Entrepreneurs benefited. Innovation benefited. Not only was economic growth strong, but because the supply side of the economy was boosted, there was virtually no inflation.                                                                                                                                                                        , The big government socialists never concede the actual facts. They lie a lot. It's because they suffer from the "Trump Derangement Syndrome." And they want to reverse everything he did even though his many achievements spurred prosperity at home and strength abroad. President Trump aimed at economic populism.                                                                                                                                                                                                                                                        , MANCHIN SUGGESTS TAX, POLICY CHANGES HE’D WANT IN BIDEN’S SPENDING BILL                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , He understood the blue-collar families across America. He turned the GOP into the party of working folks. It is sheer folly for the Biden Democrats to keep trying to overturn the Trump tax cuts. A tax cut reversal would sink the economy. And let’s not forget, accompanying the tax cuts was a massive program of federal deregulation that breathed new oxygen into the arteries of capitalism.                                                                                                                                                                         , Bill Hagerty, R-Tenn. argues Biden’s spending plan will poorly impact Americans amid inflation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , And it was Trump's deregulation that made America energy dominate. It was also Trump's tough-minded trade negotiations with China that made Americans realize that they are our enemies, not our allies. Here's Joe Biden trying to overturn every single thing Donald Trump did. And Biden’s reward: the worst one-year plunge in voter polls in history. Biden's presidency is in tatters. His transformational plan has been crushed. Republicans are on the verge of historic midterm gains.                                                                              , The backbone of GOP policies today essentially remains the Trump economic agenda. Add to that his southern border agenda.                                                                                                                                                                                                                                                                                                                                                                                                                                                     , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Biden's approach is sheer folly. Trump's approach was common sense wisdom and prosperity and growth, and jobs, and families.                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Save America. Kill the bill. Make the Trump tax cuts permanent. That's my riff.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , This article is adapted from Larry Kudlow's opening commentary on December 22, 2021  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 05:23:52 </td>
   <td style="text-align:left;"> Toronto Stocks Extend Gains for 2nd Session </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, rose 0.7% to close at 21,070 on Wednesday, tracking an upbeat sentiment in the US stock market. The energy and materials sectors led the gains on the back of higher oil and gold prices, while the healthcare sector finished 0.3% lower as pot producers' stocks weighed. Meantime, tech stocks rose 0.7%, with Dye &amp; Durham Ltd surging 11% after the IT service provider said it will buy Australia’s Link Administration Holdings Ltd for C$ 3.2 billion. On the earnings front, BlackBerry shed more than 5% erasing last session’s 4.2% rise after posting better-than-expected Q3 revenues. On the pandemic front, the federal government was mulling changes to its recently approved pandemic support bill in response to pleas from owners of small firms for assistance, as provincial governments reimposed restrictions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 05:13:46 </td>
   <td style="text-align:left;"> Brazilian Equities Fall As Omicron Concerns Linger </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, fell 0.3% to close at 105,175 on Wednesday, underperforming its international peers, and partially offsetting last session rebound, as concerns over the Omicron variant persist with more countries announcing restrictions to contain the advance of the Covid-19. Locally, Brazil's Congress on Tuesday approved the 2022 budget, sending it to be signed off by President Jair Bolsonaro. It foresees 4.9 billion reais in electoral funding ahead of next year's presidential vote, a reserve of 1.7 billion reais for the readjustment of police officers, in addition to setting the minimum wage at 1,210 reais. On the data front, Brazil's consumer confidence posted a slight recovery in December from the previous month as expectations for the economy improved. At the same time, Brazil recorded a current account deficit of $6.5 billion in November of 2021, the largest for the month since 2014, surpassing market expectations of $6.3 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stocks-end-higher-omicron-worries/story.aspx?guid={F19B0DB5-12A2-4999-A100-AF37EDFE0638}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-23 05:03:15 </td>
   <td style="text-align:left;"> Stocks end higher as omicron worries moderate - MarketWatch </td>
   <td style="text-align:left;"> Stocks ended higher for a second straight session Wednesday, extending a rebound from a three-day losing streak triggered by worries over the spread of the omicron variant of the coronavirus that causes COVID-19. The Dow Jones Industrial Average 
        DJIA,
        +0.74%
       rose around 261 points, or 0.7%, to end near 35,754, while the S&amp;P 500 
        SPX,
        +1.02%
       finished around 47 points higher, up 1%, near 4,697. The Nasdaq Composite 
        COMP,
        +1.18%
       rose around 181 points, or 1.2%, closing near 15,522., Blame it on an obscure rule. For the first time in a decade, there will be no stock market closure in observance of New Year's Day.                                                                                                                                                                                                                                                                                                                                                                                                                                                , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 05:01:00 </td>
   <td style="text-align:left;"> US Stocks Extend Rebound After Omicron Sell-Off </td>
   <td style="text-align:left;"> US stocks extended gains for the second session on Wednesday, with the Dow Jones climbing more than 250 points, the S&amp;P rising 1.0%, and the Nasdaq Composite jumping 1.2% buoyed by an improvement in risk appetite as traders turned more positive about global economic recovery despite the rise in Covid-19 cases. A new study showed infected individuals have up to 80% less probability of developing severe disease with the new strain, although results may be influenced by a higher current population immunity compared to last year. Among single stocks, Tesla climbed more than 7% after Elon Musk said in a podcast that he had reached his goal of selling 10% of his shares for tax reasons. Pfizer added 1% after its pill gained authorization from the Food and Drug Administration, it is the first antiviral drug against the virus for at-home use. On the data front, consumer confidence improved more than expected in December while existing home sales rose for the third month in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 04:30:15 </td>
   <td style="text-align:left;"> The Dow Jones Index is up by 0.56% </td>
   <td style="text-align:left;"> United States Stock Market is picking up 199 points. Gains are led by Caterpillar (1.73%), Microsoft (1.39%) and Home Depot (1.31%). Biggest losers are Nike (-0.89%), Travelers Companies (-0.56%) and Amgen (-0.24%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/carlyle-group-acquire-data-center-company/story.aspx?guid={20C05575-04D4-B545-7812-E92569FF9A72}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-23 04:26:00 </td>
   <td style="text-align:left;"> Carlyle Group to acquire data-center company Involta - MarketWatch </td>
   <td style="text-align:left;"> Carlyle Group Inc. 
        CG,
        +4.92%
       shares got an added boost in late trading Wednesday after the investment firm said it has agreed to buy data-center company Involta for an undisclosed amount. Carlyle shares rose 4.3% to $54.23, after being up about 3% before the announcement. Involta owns and operates 12 data centers in Arizona, Idaho, Iowa, Minnesota, Ohio, and Pennsylvania. “Involta has built a world-class platform with a demonstrated operating model for delivering high-quality service to customers in an increasingly complex, hybrid cloud-based world,” said Joshua Pang, head of digital infrastructure for Carlyle’s infrastruture group, in a statement. “We see significant opportunity for growth given the long-term secular demand drivers of data proliferation, digital connectivity, and the digitization of enterprise and institutional operating models.” Carlyle expects the transaction to close in the first quarter of 2022., Novavax Inc. shares were volatile in the extended session Wednesday after the biotech drug maker said initial data showed its COVID-19 vaccine booster showed immune responses against the omicron variant.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Wallace Witkowski came to MarketWatch from the Associated Press in New York, where he was a business reporter specializing in pharmaceutical companies. He previously reported for trade publications in covering the drug and medical-device industries back to 1998. Based in San Francisco, his focus is on U.S. equities. Follow Wally on Twitter at: @wmwitkowski. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-futures-end-higher-after/story.aspx?guid={521EDEB4-0694-495E-8638-AF9091E2F56B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-23 03:39:53 </td>
   <td style="text-align:left;"> Oil futures end higher after larger-than-expected drop in crude inventories - MarketWatch </td>
   <td style="text-align:left;"> Oil futures ended higher Wednesday after the Energy Information Administration reported a larger-than-expected drop in U.S. crude inventories. West Texas Intermediate crude for February delivery 
        CL00,
        +0.22%
        CLG22,
        +0.22%
       closed at $72.76 a barrel on the New York Mercantile Exchange, up $1.64, or 2.3%. The EIA said crude inventories fell by 4.7 million barrels in the week ended Dec. 17. Analysts surveyed by S&amp;P Global Platts had forecast a drop of 3.9 million barrels, while sources said the American Petroleum Institute late Tuesday reported that stocks had fallen by 3.7 million barrels., Blame it on an obscure rule. For the first time in a decade, there will be no stock market closure in observance of New Year's Day.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2021-12-23 03:36:23 </td>
   <td style="text-align:left;"> Oil Extends Rebound to Above $72.5 </td>
   <td style="text-align:left;"> WTI crude futures extended gains to above $72.5 per barrel on Wednesday, after jumping more than 3.5% in the previous session underpinned by a larger-than-expected draw in US crude inventories and an energy crunch in Europe. Also, a slight improvement in risk appetite as traders turned more positive about global economic recovery helped to boost the gains. The American Petroleum Institute reported on Tuesday that crude inventories fell by 3.67 million barrels last week, above market expectations of a 2.633 million decrease. At the same time, natural gas prices surged in Europe after Russia curbed flows, forcing some countries to boost electricity imports and burn oil to meet demand. Meanwhile, investors digested omicron updates after a new study showed infected individuals have up to 80% less probability of developing severe disease with the new strain, although results may be influenced by a higher current population immunity compared to last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/alibaba-stock-drops-china-regulator/story.aspx?guid={20C05575-04D4-B545-7811-8E4BA6214AE9}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-23 01:59:00 </td>
   <td style="text-align:left;"> Alibaba stock drops as China regulator reportedly suspends partnership - MarketWatch </td>
   <td style="text-align:left;"> Alibaba Group Holding Ltd. 
        BABA,
        -4.20%
       shares fell Wednesday following reports that China’s IT regulator disciplined the company for failing to report an open-source security vulnerability to the government. American depositary receipts of Alibaba dropped as much as 6% Wednesday, and were last down 3.8% at $118.35. On Wednesday, China’s Ministry of Industry and Information Technology suspended a partnership with Alibaba for six months alleging that Alibaba failed to promptly report bugs in the open-source logging platform Apache Log4j2 to government officials, according to media reports. About two weeks ago, reports surfaced that the software contained a bug that would allow remote hackers to make changes to target devices., Elon Musk said Tuesday he's met his goal of selling 10% of his stake in Tesla Inc., and criticized California for "overtaxation."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Wallace Witkowski came to MarketWatch from the Associated Press in New York, where he was a business reporter specializing in pharmaceutical companies. He previously reported for trade publications in covering the drug and medical-device industries back to 1998. Based in San Francisco, his focus is on U.S. equities. Follow Wally on Twitter at: @wmwitkowski. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2021-12-23 01:42:08 </td>
   <td style="text-align:left;"> Brazilian Real Rebounds From 8-Month Low </td>
   <td style="text-align:left;"> The Brazilian real traded around 5.69 per USD, after hitting an eight-month low of 5.7451 on December 21st, amid a slight improvement in risk appetite as traders turned more positive about global economic recovery despite the rise in Covid-19 cases, while a weaker dollar helped to sustain the currency gains. Domestically, Congress approved the 2022 budget, decreasing short-term uncertainties, while point to a very inflexible budget. Meanwhile, investors’ perception that the Brazilian economic recovery has begun to succumb to rising inflation and higher interest rates continues to weigh on the currency appeal. Domestically, the IBC-Br, considered as a monthly preview of GDP, shrank by 0.4% MoM in October, below expectations of a 0.2% decrease, and marking the third consecutive negative reading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/22/stocks-making-the-biggest-moves-midday-tesla-carmax-blackberry-more.html </td>
   <td style="text-align:left;"> 2021-12-23 01:34:16 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Tesla, CarMax, BlackBerry and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                             , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                                                                 , CarMax — CarMax shares fell 6.4% despite the used car retailer's better-than-expected quarterly report. The company posted earnings of $1.63 per share, 19 cents above the Refinitiv consensus estimate and revenue came in at $8.53 billion, $1 billion higher than expected.                                                                                                                                                              , Tesla — Tesla shares rallied 7.5% after CEO Elon Musk said he sold "enough stock" to reach his goal of offloading 10% of his shares. On Tuesday, Musk sold another 583,611 shares, bringing the total number of shares he has offloaded to 13.5 million.                                                                                                                                                                                    , BlackBerry — BlackBerry shares dropped 1.7% even after the company posted quarterly results on Tuesday that beat Wall Street expectations. The communications software maker posted a breakeven quarter on an adjusted basis, while analysts expected a loss of 7 cents per share, according to StreetAccount. However, current quarter forecasts for cybersecurity products fell shy of the StreetAccount consensus estimate.              , Caterpillar — Shares of the industrial giant gained 1.9% after Bernstein upgraded the company to an outperform rating. The firm said expectations are low for Caterpillar despite plenty of upside heading into 2022. "Although the slope of its secular growth trajectory remains an outstanding question, the cycle is calling CAT's name and the path is clearing for the stock to outperform over these next 12 months," the firm said. , Alibaba — Alibaba shares fell 4.2% after Atlantic Equities downgraded the Chinese e-commerce company's stock to a neutral rating from overweight. The firm was concerned Alibaba's shopping platforms will not improve performances in the near term.                                                                                                                                                                                       , Darden Restaurants — Darden Restaurants saw its shares rally 1.6% after it received an upgrade to a buy rating from hold from Stifel. The firm liked the Olive Garden-parent's upbeat quarterly results last week.                                                                                                                                                                                                                          , Williams-Sonoma — Shares of the home goods store rose 2.4% after Loop Capital Markets upgraded Williams-Sonoma to buy from hold. Loop said in a note to clients that the company could benefit from the return of people staying away from homes and offices.                                                                                                                                                                               , Coinbase — Shares of the crypto services firm added 2.8% after Oppenheimer named the company a top pick for 2022, betting that adoption of digital assets by investors will continue and provide attractive returns for long-term investors. The move also comes as the bitcoin price climbs higher. The two tend to trade in tandem because of Coinbase's reliance on trading fees.                                                        , Paychex — Paychex shares rose 5.5% after the payroll services company reported strong quarterly earnings. The company posted a profit of 91 cents per share on revenue of $1.11 billion. Analysts surveyed by StreetAccount expected earnings of 80 cents per share on revenue of $1.06 billion.                                                                                                                                            , — CNBC's Jesse Pound, Pippa Stevens and Tanaya Macheel contributed reporting                                                                                                                                                                                                                                                                                                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                            , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-extends-pause-student-loan/story.aspx?guid={F3E6227D-DDFD-406E-9DA8-F099738C9B8C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-23 01:32:53 </td>
   <td style="text-align:left;"> Biden extends pause on student loan payments until May 1 - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden on Wednesday said he's extending a pause on federal student loan repayments by an additional 90 days, meaning until May 1. Biden said in a statement that while the jobs recovery is "one of the strongest ever," millions of student loan borrowers are "still coping with the impacts of the pandemic and need some more time before resuming payments.", There's a real human cost to Manchin's threat to kill the Build Back Better bill.                                                                                                                                                                                                                                                                                             ,                                                                                                                                                                                                                                                                                                                                                                               , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 01:28:00 </td>
   <td style="text-align:left;"> Italian Shares Close Higher on Wednesday </td>
   <td style="text-align:left;"> The FTSE MIB closed 0.7% higher at 26,827.93 on Wednesday, tracking strong performances in US stock markets as investors await the new domestic restriction measures tomorrow. As the Omicron variant spreads in Italy, Prime Minister Mario Draghi is set to meet health authorities and ministers tomorrow to decide on the extent of pandemic-related restrictive measures to be implemented, aiming to prevent drastic lockdown measures as seen in other European countries. On the political front, Draghi signalled that he would be willing to become Italy’s president in January, a move that could trigger early parliamentary elections. On the corporate front, industrials led the gains with Cnh Industrial (2.7%) and Leonardo (2.4%). Also, Telecom Italia gained 1.9% following news that treasury owned CDP is discussing a revamp for the telecom, aiming to protect jobs and protect the group’s infrastructure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/currency </td>
   <td style="text-align:left;"> 2021-12-23 01:23:54 </td>
   <td style="text-align:left;"> Mexican Peso at Near 1-Month High </td>
   <td style="text-align:left;"> The Mexican peso traded around 20.75 per USD in the third week of December, the strongest since November 18th, amid a slight improvement in risk appetite as traders turned more positive about global economic recovery despite the rise in Covid-19 cases, while a weaker dollar and a rebound in oil prices helped to sustain the currency gains. Also, in its last meeting, the Mexican Central bank surprised the markets and hiked the borrowing costs by 50 bps to 5.5%, above expectations of 25 bps saying inflation risk balance has deteriorated, with both the headline inflation and the core inflation expectations for the next year increasing again, and the ones for the medium-term remaining above the target. Meanwhile, investors digested omicron updates after a new study showed infected individuals have up to 80% less probability of developing severe disease with the new strain, although results may be influenced by a higher current population immunity compared. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/fda-authorizes-pfizers-covid-19-antiviral/story.aspx?guid={7C2E4AB1-5803-43A9-9E8B-538569D5B507}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-23 01:23:13 </td>
   <td style="text-align:left;"> FDA authorizes Pfizer's COVID-19 antiviral for high-risk teens and adults - MarketWatch </td>
   <td style="text-align:left;"> Shares of Pfizer Inc. 
        PFE,
        +1.02%
       were up 1.6% in trading on Wednesday after the Food and Drug Administration authorized the company's COVID-19 antiviral, bringing to market the first at-home COVID-19 pill during the course of the pandemic. Pfizer's drug, Paxlovid, can be used to treat people who are at least 12 years old with confirmed mild or moderate cases of COVID-19 and are at high risk for disease progression. Patients should begin treatments within 5 days of the first symptoms; the treatment regimen consists of three tablets taken twice a day for five days. The emergency-use authorization is based on data from a clinical trial that found Paxlovid can reduce the risk of hospitalization and death by 88%. Pfizer's stock has gained 63.3% so far this year, while the broader S&amp;P 500 
        SPX,
        +1.02%
       is up 23.8%., Amazon, Visa, Nordstrom, and AT&amp;T are among the stocks pegged to outperform the S&amp;P 500 next year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 01:12:00 </td>
   <td style="text-align:left;"> South African Stocks End Slightly Higher </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index rose 0.3% to close at 71,359 on Wednesday, as investors continued to weigh the risk posed by the Omicron variant to the global economic growth and uncertainty around the US spending bill against some encouraging news about Covid-19 vaccine boosters. Locally, scientists said that COVID-19 cases appear to have peaked in South Africa's Gauteng province, one of the first places in the world where the Omicron variant surfaced, and the impact of surging infections has been less severe than previous waves. Meanwhile, President Biden said on Tuesday that he was considering lifting a travel ban he imposed last month on people traveling from South and seven other southern African countries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-59760366?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2021-12-23 01:03:11 </td>
   <td style="text-align:left;"> US safety body to probe Tesla on in-car gameplay </td>
   <td style="text-align:left;"> An investigation has been launched in the US into more than half a million Tesla cars that are equipped with touchscreens.                                                                           , It follows a complaint filed by a user who discovered he could play games while driving.                                                                                                             , The US National Highway Traffic Safety Administration (NHTSA) is looking into some 580,000 Tesla Models 3, S and X made from 2017 to the current day.                                                , Tesla has not yet responded to the investigation.                                                                                                                                                    , The feature under scrutiny is called Passenger Play, and it allows users to play games on their in-car touchscreen.                                                                                  , It does warn that playing while in motion is "only for passengers" and asks for confirmation of this before allowing gameplay.                                                                       , But the NHTSA noted that Passenger Play "may distract the driver and increase the risk of a crash".                                                                                                  , It added that the feature had been available since December 2020. Previously the game feature was only enabled when the vehicle was in Park mode.                                                    , Earlier this month the NHTSA reported that 3,142 road deaths in 2019 were attributed to distracted drivers.                                                                                          , Guidelines published by the agency in 2013 recommend that in-vehicle devices be designed so that they cannot be used by the driver "to perform inherently distracting secondary tasks while driving"., Last month, Tesla owner Vince Patton from Oregon spotted a video on YouTube which highlighted how Passenger Play could be used by drivers.                                                           , After testing it in a car park and finding he could indeed play several games while driving, he filed a complaint with the NHTSA, describing the feature as "recklessly negligent".                  , Earlier this month, Mercedes-Benz issued a recall for an issue caused by a computer configuration error that allowed drivers to browse the internet or watch television while the cars were moving.  , Which one will be given the tinsel crown?                                                                                                                                                            , A Very British Scandal: A gripping new drama coming soon                                                                                                                                             , © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 00:55:48 </td>
   <td style="text-align:left;"> London Stocks Extend Gains </td>
   <td style="text-align:left;"> The FTSE 100 rose 0.6% to close at 7,342 on Wednesday, in line with its European peers and extending gains for the second straight session, amid thin trading volumes ahead of Christmas, and a slight improvement in risk appetite as traders turned more positive about global economic recovery despite the rise in Covid-19 cases. Also, an upbeat sentiment in the US stock market helped to boost the gains at the end of the session. Meanwhile, investors digested omicron updates and domestic economic data. The British economy expanded 1.1% q-o-q in Q3, slightly less than expected, while business investment unexpectedly fell 2.5%. Regarding the omicron variant, a new study showed infected individuals have up to 80% less probability of developing severe disease with the new strain, although results may be influenced by a higher current population immunity compared to last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 00:47:00 </td>
   <td style="text-align:left;"> European Shares Close Higher after Choppy Session </td>
   <td style="text-align:left;"> European stock indices managed to close higher on Wednesday, extending gains from last session’s, lifted by upbeat sentiment in the US stock markets amid thin trading volumes. Earlier, stocks were mixed amid the ongoing uncertainty about the impact of the omicron variant in the economy. On the pandemic front, Austria will allow for some expectations of travel restrictions to minimize the impact on ski resorts, Portugal introduced new restrictions on the service sector for the holidays period, whilst France mulls extending vaccine mandate to workplaces. Meanwhile, ECB’s board member Isabel Schnaber said inflation will remain high for a certain period but it will ease through the course of 2022. On the data front, UK’s Q3 GDP final estimates showed a slower than expected expansion over the prior quarter, as investors prepare for the impact of the omicron variant in the final quarter of the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Close Higher on Wednesday </td>
   <td style="text-align:left;"> The CAC 40 Index jumped 1.2% to close at 7,051.67 on Wednesday, tracking higher equities from the United States, as investors welcomed better than expected US GDP data. The American GDP growth was revised higher to 2.3% on the quarter during Q3 2021, mostly driven by a higher reading for consumption expenditure. On the pandemic front, French government spokesman Gabriel Attal said restrictions will be heightened on Christmas and New Year’s festivities, in an attempt to prevent lockdowns as seen in the Netherlands. On the corporate front, Valneva climbed 6.1% after the laboratory published positive initial results for the phase 3 of its chikungunya vaccine. At the same time, Airbus (3.5%) and Safran (2.4%) lifted the aerospace sector. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/albania/interest-rate </td>
   <td style="text-align:left;"> 2021-12-23 00:38:00 </td>
   <td style="text-align:left;"> Albania Leaves Monetary Policy Unchanged </td>
   <td style="text-align:left;"> The Bank of Albania held its policy rate unchanged at 0.5% during its December 2021 meeting. The Bank’s Governor, Gent Sejko noted the growth in economic activity and decrease in the unemployment rate (11.3% in Q3) have been supported by the improving foreign environment, as well as by stimulating domestic economic policies. Meanwhile, Albanian consumer prices rose 3.1% year-on-year in November of 2021, mainly reflecting the effect of significant increases in food, oil and energy prices. Looking forward, it is expected that inflation will rise above the target in the coming months. At the same time, the overnight deposit rate remained at 0.1% and the overnight loan rate remained at 0.9%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 00:35:00 </td>
   <td style="text-align:left;"> Swiss 10Y Bond Yield Highest in 3-Weeks </td>
   <td style="text-align:left;"> The yield on the Swiss 10-year government bond rose to -0.22%, the highest in three weeks, as elevated risk sentiment pushed stocks and energy commodities higher, reducing the demand for safer sovereign debt instruments. A South African study downplaying the severity of the Omicron variant’s infections sparked optimism that economic activity may resume at higher levels in 2022. At the same time, daily coronavirus infections in Switzerland are declining for the first time since October. Regardless, the government furthered restriction measures on unvaccinated individuals to prevent the need of strict lockdowns. Last week, the Swiss National Bank kept its policy rate unchanged at -0.75%, maintaining its ultra-loose monetary policy and revising its GDP growth to 3.5% this year from 3%. The bank also committed to controlling the rise of the Franc against its trading partners, as the CHF-EUR hover at its highest level since July 2015. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2021-12-23 19:28:25 UTC +8

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
   <td style="text-align:left;"> 2021-12-23 19:26:19 </td>
   <td style="text-align:left;"> $SPY The media is killing the algos right now, and we can take advantage!   I bought into omicron news! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:25:55 </td>
   <td style="text-align:left;"> $SPY bands narrowing, flow increasing, it’s beginning to look allot like Christmas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:25:41 </td>
   <td style="text-align:left;"> $SPY wow, just wow 🚀🚀🚀 printing continues. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:25:23 </td>
   <td style="text-align:left;"> $SPY if we can break and hold new highs i am quite bullish until then show me it can hodl 470 level
Ps full day of trading today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:23:51 </td>
   <td style="text-align:left;"> $SPY https://www.cnbc.com/2021/12/23/omicron-variant-has-lower-risk-of-hospitalization-studies-suggest.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:23:05 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:22:11 </td>
   <td style="text-align:left;"> Travel experts are saying Wednesday and Thursday are going to be the busiest days for holiday travelers. Shake Shack seems to be aware of this fact and has plans to offer free fries to airline passengers who have had their flights delayed or canceled.

$ba $spy $luv $aal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:22:04 </td>
   <td style="text-align:left;"> $SPY $AMC $RCAT $SEAC $GRTX 

https://www.benzinga.com/node/24751966 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:20:11 </td>
   <td style="text-align:left;"> $SPY what time does market close today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:19:45 </td>
   <td style="text-align:left;"> $SPY next stop, 4800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:18:55 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:17:05 </td>
   <td style="text-align:left;"> $SPY $FB $META 

The Future is Zombie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:17:03 </td>
   <td style="text-align:left;"> $SPY FUTES ABD TUTES LOADING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:16:38 </td>
   <td style="text-align:left;"> $SPY guys I shouldn’t have shorted. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:13:38 </td>
   <td style="text-align:left;"> $SPY the bear puts the lotion on its skin or it gets the hose again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:12:53 </td>
   <td style="text-align:left;"> $SPY casino is open again today. However it’s only for a short time. It looks like green is going to win for the next few hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:12:40 </td>
   <td style="text-align:left;"> $SPY these reports at 8:30 will show the markets course of action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:12:30 </td>
   <td style="text-align:left;"> $SPY SOON 🤌🏻🤌🏻🤌🏻🤌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:11:16 </td>
   <td style="text-align:left;"> $SPY FUTES RIPPING!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:10:46 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:10:16 </td>
   <td style="text-align:left;"> $SPY Go short and wait. US debt passed GDP last year, and the Fed is adding billions monthly. Spooky action on low volume doesn&amp;#39;t mean much, this is going to turn fast on ANY catalyst. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:08:24 </td>
   <td style="text-align:left;"> $SPY 1%+ in the green today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:07:13 </td>
   <td style="text-align:left;"> $SPY SPY 2021-12-22 Trade Analysis Video: 
https://www.youtube.com/watch?v=taq_xuXYOQs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:06:56 </td>
   <td style="text-align:left;"> $SPY O ya she gon print

Theta is more than the contract 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:06:43 </td>
   <td style="text-align:left;"> $SPY …lookin forward to the Santa rally
Merry Christmas &amp;amp; GLTATraders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:05:45 </td>
   <td style="text-align:left;"> $SPY Performance chasing at its finest. Bring in the new year already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:05:10 </td>
   <td style="text-align:left;"> $SPY literally for all the bears out there major indexes always go up and always will. Will there be pullbacks/ drops absolutely but overall it will always go up why fight it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:04:18 </td>
   <td style="text-align:left;"> $SPY look very solid day 1%+ up today we should hit new all time high either by today after European close or tomorrow before us opening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:03:37 </td>
   <td style="text-align:left;"> $SPY wish I didn’t try to trade this week: literally a nonstop 4 day rally on nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 19:03:19 </td>
   <td style="text-align:left;"> $SPY GAP UP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:59:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA SCOTTIE PIPPEN 🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:58:42 </td>
   <td style="text-align:left;"> $SPY to all the know it all bears and bulls......
its been a Tie for 2 months......
go play in a corner.....
we are tired of hearing it......
Merry Xmas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:56:08 </td>
   <td style="text-align:left;"> $SPY …nice days ahead

https://stocktwits.com/Chief_Beachbum/message/420021211 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:55:01 </td>
   <td style="text-align:left;"> #SouthwesternEnergy Vs. #OccidentalPetroleum: Which Energy Stock Is A Better Buy? $OXY $SWN Also $SPY $XLE https://talkmarkets.com/content/commodities/southwestern-energy-vs-occidental-petroleum-which-energy-stock-is-a-better-buy?post=338832 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:54:44 </td>
   <td style="text-align:left;"> Check out our E-Book at Thrashcap.com for a basic overview of the financial markets and options trading! $SPY $QQQ $DIA $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:52:30 </td>
   <td style="text-align:left;"> A Peek Into The Markets: US Stock Futures Edge Higher Ahead Of Economic Data  $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/a-peek-into-the-markets-us-stock-futures-edge-higher-ahead-of-economic-data/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:52:12 </td>
   <td style="text-align:left;"> Can you share you returns, this year 2021? : options  $SPY https://www.billionaireclubcollc.com/can-you-share-you-returns-this-year-2021-options/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:51:46 </td>
   <td style="text-align:left;"> As predicted yesterday, $SPY broke free and heading to retest highs of 474. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:51:41 </td>
   <td style="text-align:left;"> 12.23 Day Trade Idea

The choice 1, 2, 3 means that in either direction strong conviction.

If price is already met over or under by 2 points then it is recommended no trigger. For an example, if MSFT is 337 by market open, and I have over 334 then it has already passed alert trigger by 3 points, which too much over the alerted price.

It is recommended to buy in the money or near the money on 0dte.

Remember to review your DD. Good luck on lotto Friday and place your own profit and loss stops.
$JD $MSFT $SPY $AAPL $NVDA

*JD UNDER 68.30(GAP DOWN FILL TO 66.30) #1 choice

*MSFT OVER 334, MSFT UNDEE 331.45 #2 choice

*SPY OVER 468.50, SPY UNDER 466.85 #3 choice

AAPL OVER 176.60, AAPL UNDER 174.60

NVDA 295.50, NVDA UNDER 291.50

JOIN TRIAL CHANNEL FOR 5 DAYS
https://t.me/+boyKMgL-eugzODY5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:49:55 </td>
   <td style="text-align:left;"> $SPY 

https://www.bloomberg.com/news/articles/2021-12-23/putin-praises-bank-of-russia-for-averting-turkish-style-crisis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:49:17 </td>
   <td style="text-align:left;"> $SPY just doesn’t stop going up… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:48:55 </td>
   <td style="text-align:left;"> $spy lately there are more angry ppl makes me more bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:48:30 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:48:27 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:48:11 </td>
   <td style="text-align:left;"> $SPY how long does it take to recalculate the price after the dividend, as to match the sp? Was it 30 days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:48:04 </td>
   <td style="text-align:left;"> $SPY $tsla $appl $amd $amc $fb
Again... Fear not. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:47:22 </td>
   <td style="text-align:left;"> $SPY Haven&amp;#39;t played any options in a week. I need my fix. Normal investing is boring AF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:47:20 </td>
   <td style="text-align:left;"> $SPY $PFE $GSK 

https://www.forbes.com/sites/lisakim/2021/12/22/omicron-is-less-likely-to-cause-hospitalization-and-develop-into-severe-disease-south-african-study-suggests/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:46:32 </td>
   <td style="text-align:left;"> $SPY hit 470 then come down to China town babeyyy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:46:31 </td>
   <td style="text-align:left;"> $SPY Calendar - 12.23.2021

Last day of the short week. Good luck out there! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:45:59 </td>
   <td style="text-align:left;"> $XLV broke out 2 weeks ago and might peak out near Fib 1.618 as it&amp;#39;s forming 3 white soldiers on the weekly before consolidating some weeks, respecting the channel since the March 2020 crash. Sector still bullish with the healthcare situation worldwide and so $XBI also has a bullish outlook heading into 2022, link to XBI chart: 
https://stocktwits.com/MLinv/message/419954238 
 
$IWM $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:45:54 </td>
   <td style="text-align:left;"> $SPY WHUT? I thought the Omicron is more contagious but doesn&amp;#39;t put as many in the hospital. Com&amp;#39;On Man...tell the truth here your precious stock market wants to know. LOL🤐🤐
https://www.msn.com/en-us/health/medical/us-hospitals-struggle-with-staffing-shortages-and-omicron-outbreaks/ar-AAS4Tsx?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:45:22 </td>
   <td style="text-align:left;"> $SPY bears about to get stung at open again i see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:44:08 </td>
   <td style="text-align:left;"> $spy good morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:44:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOXL Perhaps the issue, along with mid-term elections, that supports Tom Lee&amp;#39;s call for a rocky H1 &amp;#39;22. Expects gains in H2.

https://www.zerohedge.com/markets/markets-message-fed-will-go-too-far-slow-inflation-break-something </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:43:11 </td>
   <td style="text-align:left;"> $SPY futures pumping 🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:43:08 </td>
   <td style="text-align:left;"> $SPY Santa is real! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:42:30 </td>
   <td style="text-align:left;"> $SPY Designed and controlled.   
Steady climb on extremely low volume. 
Merry Xmas to ALL!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:41:42 </td>
   <td style="text-align:left;"> $SPY Have no fear Biden said Omicron is just more contagious...yet hospitals are full and now other counties are locking down. IS THIS A BUNCH OF MALARKY?????? We wouldn&amp;#39;t want to ruin the Christmas holiday with the actual truth🤣😂🤣
https://www.msn.com/en-us/news/world/china-covid-19-xi-an-city-of-13-million-people-goes-into-lockdown-imn-response-to-cluster/ar-AAS54PS?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:39:55 </td>
   <td style="text-align:left;"> $SPY i finally know the purpose of life
To be financial free, and no need work
Doesn&amp;#39;t matter 10k or 100k per month
Even 3k is enough!!! $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:39:41 </td>
   <td style="text-align:left;"> What Should You Invest in During the New Year? Investing Strategies for 2022 $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/what-should-you-invest-in-during-the-new-year-investing-strategies-for-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:38:02 </td>
   <td style="text-align:left;"> $SPY bull trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:36:37 </td>
   <td style="text-align:left;"> $SPY Over the next 10 weeks we&amp;#39;re going nearly straight up 10%.  If you read my posts Monday, you would have gotten in at the lows.  Don&amp;#39;t get cute, buy enough time, then don&amp;#39;t watch it every minute or you&amp;#39;re sure to screw it up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:34:01 </td>
   <td style="text-align:left;"> World shares extend gains in thin pre-Christmas trading $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/world-shares-extend-gains-in-thin-pre-christmas-trading/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:33:55 </td>
   <td style="text-align:left;"> $SPY let&amp;#39;s send spy to 30 pe
And make bagholder on next generation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:32:22 </td>
   <td style="text-align:left;"> $AMD on watch $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:32:20 </td>
   <td style="text-align:left;"> $SPY come on $SPY why you have to linger on them overnight bullish gamblers? They want affirmation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:31:54 </td>
   <td style="text-align:left;"> $SPY should buy more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:30:49 </td>
   <td style="text-align:left;"> $SPY will the printers go brrrrr today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:30:11 </td>
   <td style="text-align:left;"> $SPY If price moves up 1-2% today I’d be cautious about next week, Santa rally or not history shows the trend is a lot healthier when the price melts up a few dollars consistently rather than go up $8-10 3 and 4 days in a row. I’m not going to fight the trend but I’m not going to be naive either lol….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:29:48 </td>
   <td style="text-align:left;"> $SPY as you see there were tons of reasons to drop S&amp;amp;P500 in the past… 

📈📈🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:29:45 </td>
   <td style="text-align:left;"> $SPY the winter is coming bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:29:06 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:28:35 </td>
   <td style="text-align:left;"> $SPY Exxon Mobil Plant fire...not the first time at this plant
https://www.msn.com/en-us/news/crime/major-industrial-accident-in-texas-sheriffs-say/ar-AAS5cqk?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:27:41 </td>
   <td style="text-align:left;"> $SPY real price will come out soon; follow price targets.... stock.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:23:57 </td>
   <td style="text-align:left;"> $QQQ breakout time. One last day for the bulls before the bloodiest sell of in recent memory next week. We will be looking to start a short around 396.50-397 today $SPY $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:23:41 </td>
   <td style="text-align:left;"> $SPY pick up the momentum !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:22:55 </td>
   <td style="text-align:left;"> $SPY psst...hustling the hustlers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:22:29 </td>
   <td style="text-align:left;"> $SPY bigly launching tomorrow, they already know the numbers and vix will fall no matter what </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:22:17 </td>
   <td style="text-align:left;"> $SPY $TSLA: 100 years from now this post will be relevant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:20:48 </td>
   <td style="text-align:left;"> $SPY  more closures around the world 🌎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:20:14 </td>
   <td style="text-align:left;"> $SPY Tight wedge breakout coming soon ! Or breakdown ? Either way a nice move is coming ! Hopefully closer to the bell (9:30am) EST ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:06:29 </td>
   <td style="text-align:left;"> $SPY 

According to data from the U.S. Federal Reserve, commercial and
industrial (C&amp;amp;I) loans are up 1.9% in the fourth quarter-to-date at large banks.

Loans bad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:05:23 </td>
   <td style="text-align:left;"> $SPY  Bullish on a historic “Ave” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:05:13 </td>
   <td style="text-align:left;"> $SPY $DAX The biggest winner of Pfizer&amp;#39;s Pill is the $EURUSD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:01:32 </td>
   <td style="text-align:left;"> $SPY Remember 12/16, we may get a reversal bar similar to that. Shorts are waiting for confirmation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 18:00:57 </td>
   <td style="text-align:left;"> Economic Data Scheduled For Thursday $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/economic-data-scheduled-for-thursday-7/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:56:01 </td>
   <td style="text-align:left;"> Super wealthy $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:53:09 </td>
   <td style="text-align:left;"> $SPY ❤️❤️❤️❤️💥💥💥💥💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:52:17 </td>
   <td style="text-align:left;"> $SPY $NDX future of US markets lie with $DIS

The Mickey Mouse is a clear value trap in a defined downtrend. It seems we will grapple with the COVID 19 virus for a while more that will see it take down the mighty US markets once more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:50:00 </td>
   <td style="text-align:left;"> Besides having an excellent technical rating, $SPY also presents a decent setup pattern. https://www.chartmill.com/stock/analyzer/stock/SPY?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:49:05 </td>
   <td style="text-align:left;"> $GGPI $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:48:46 </td>
   <td style="text-align:left;"> $spy $dia $ndx $tsla my, my, my,…. New bullish catalyst entered the market for Tesla this morning. That explains the big jump at premarket opening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:48:18 </td>
   <td style="text-align:left;"> $SPY the inflation data in few hours forecast to be 4.5%  highest since 1980s . market reaction likely not friendly if higher..   i believe their was a reason  Bond Expert  Mohamed El-Erian was on CNBC all day yesterday. saying &amp;quot;Markets in 2022 will look very different, investors need to apply fundamentals ,  Fed is behind raising rates and is losing credibility. will have to react and raise rates&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:47:41 </td>
   <td style="text-align:left;"> $SPY we’ve knew for months omicron was bullshit hyped up by the media... endless scams by your own central bank supposedly looking after it’s own people, yeah right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:47:29 </td>
   <td style="text-align:left;"> $SPY a lot of post think market overvalued and they start to short it or buy puts this is not the way to trade and make money you need to know that the market work when 70% loss and 30% make money media is controlled by rich people be smart and stop reading the news and fallow the chart move and YES do opp what you believe is right  ( try this and i am 100% sure you will always make money like me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:45:57 </td>
   <td style="text-align:left;"> $SPY Anyone knows if the market gonna open on Monday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:45:27 </td>
   <td style="text-align:left;"> $SPY bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:44:07 </td>
   <td style="text-align:left;"> $SPY $QQQ latexf53efdbfd7c16ae0efd68dc766617892BABA 5% down today 
$JD 12% DOWN today 
 
no buyers, no shorts to squeeze, no catalysts, horrible news and pending lockdown, delistings, and buyback lockouts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:41:30 </td>
   <td style="text-align:left;"> $SPY ever since we closed lol let me guess. Not to shabby lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:40:57 </td>
   <td style="text-align:left;"> $SPY new ATH today 475 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:40:24 </td>
   <td style="text-align:left;"> $SPY same with burger king </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:40:12 </td>
   <td style="text-align:left;"> $SPY chipotle, overvalued </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:39:54 </td>
   <td style="text-align:left;"> $SPY Mcdonalds is trash food. Now its also expensive. they are going bankrupt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:39:37 </td>
   <td style="text-align:left;"> $SPY drop to 466 again so I can rinse and repeat 😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:38:01 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ Moving on to licensing. As you know, we have been in negotiations regarding the sale of our noncore portion of our IP patent portfolio. This process is taking much longer than we had hoped. And trust me, I share the frustration about the time line. Negotiations are very close to a conclusion, and we are literally down to the last few important items now. Both parties are working hard to get this finished, and we expect to reach a definitive agreement very soon. We will provide shareholders an update on progress in January.  shorts going be scrambling 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:37:38 </td>
   <td style="text-align:left;"> $SPY $32,700 on the day, thanks to. stock.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:37:16 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m all for helping people with unemployment, but a small fraction of the money was used for small business and individuals. The point is, the economy isn&amp;#39;t natural at the moment. So you can&amp;#39;t take these recent earnings at face value </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:35:52 </td>
   <td style="text-align:left;"> $SPY It&amp;#39;s not based on anything. It&amp;#39;s based on the FED buying junk bonds, and handing out unemployment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:35:02 </td>
   <td style="text-align:left;"> $SPY This is good news. Imagine going back to sort of normal again and not having to hear the word VIRUS every 3 minutes. 

https://www.washingtonpost.com/opinions/2021/12/22/new-generation-vaccines-spfn-variants/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:34:59 </td>
   <td style="text-align:left;"> $SPY The problem is the financial bubble in all other aspects of the economy that will lead to a liquidity crisis just like you saw with what covid caused </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:34:31 </td>
   <td style="text-align:left;"> $SPY Toys supposedly actually went down in latest CPI, -2.3%, but everywhere I look prices are ridiculously higher, Wal-Mart, Fred Meyer, Target.

Tech toys the most high.

I THINK, personal spending will be A NEGATIVE NUMBER .

Personal income? Not so sure. But it will make more sense to me to miss # since jobs report signaled weakness Nov.

Make no mistake, IF Powell walks back bond buying  or just keeps things same, it&amp;#39;s going to signal to Wall Street, inflation is winning the war.

Not good.

I also expect PCE # to miss, by quite a bit. 

Computers too, everyone got one, that includes retail and commercial side. 

Affects $AMD $NVDA 

Tesla will not see one dime from Hertz either. Musk got out for a reason, betting this quarter on a 2021 June bankrupt company re-propped up by investors is NOT the richest man in USA wah of doing things 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:33:42 </td>
   <td style="text-align:left;"> $SPY 
blah blah bIDeN blah blah dEmOcRaTeS blah blah deEp StAtE blah blah bRaNdOn…. Who am I?
An idiot! You guessed right! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:33:40 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ll buy some stocks, but I wouldn&amp;#39;t buy this garbage LMAO. You have decent luck with FB and GOOGL and MSFT and INTC but thats about it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:32:31 </td>
   <td style="text-align:left;"> $SPY It&amp;#39;s about logic, numbers, not your feelings. I have some feelings about the macro economy and how it can be better, but it doesn&amp;#39;t change the fact these stocks are as overvalued as the 2000 tech bubble disregarding risk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:32:14 </td>
   <td style="text-align:left;"> $SPY this board is boring at these times. I’m going to go get block by the $AMC, $GME, AND $BB crowd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:31:27 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $IWM US stocks rose midday Wednesday after consumer confidence came in higher than forecast for December and as third-quarter economic growth was revised higher, helping outweigh the continuing impact of the highly contagious omicron variant on investor sentiment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:30:55 </td>
   <td style="text-align:left;"> $SPY You can say anything besides your little feelings are hurt ? I understand its braindead money at the moment, but don&amp;#39;t act like this is cheap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:29:48 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:29:43 </td>
   <td style="text-align:left;"> $SPY lower highs and lower lows on the 4H, better hope Santa isn’t gonna scam </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:29:13 </td>
   <td style="text-align:left;"> $SPY mad the ending of spider man …WTF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:29:02 </td>
   <td style="text-align:left;"> $SPY My feelings wahh wahh I want it to go up forever wahhh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:28:39 </td>
   <td style="text-align:left;"> $SPY You treat this like it&amp;#39;s a game. You gonna cry because the market can go down? Lmao. I wouldn&amp;#39;t be saying this if the stocks were cheap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:28:00 </td>
   <td style="text-align:left;"> $SPY hoping to open at 471+ then on the road to new ath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:27:43 </td>
   <td style="text-align:left;"> $SPY Spending your year salary USD on pictures of cats. Real smart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:27:36 </td>
   <td style="text-align:left;"> $SPY 😂 It’s funny! You can tell by the comments who’s getting a lump of coal in their stocking today and who’s waking up to that shiny new BMX bike sitting next to the tree 🌲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:26:49 </td>
   <td style="text-align:left;"> $SPY tbh I was thinking this would be 3dollars up by now with all the hype n all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:26:24 </td>
   <td style="text-align:left;"> $SPY im saying $472+ EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:26:09 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/6NxcL6b-qWw follow me on YouTube to see how I trade options it’s definitely worth checking out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:25:16 </td>
   <td style="text-align:left;"> $SPY covid dip won&amp;#39;t happen till after the holidays we have green birthday candles for now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:25:15 </td>
   <td style="text-align:left;"> $SPY Good company doesn&amp;#39;t matter. The stock price is a whole different story </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:24:50 </td>
   <td style="text-align:left;"> $SPY Limit down 7%? You couldn&amp;#39;t sell your garbage fast enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:24:25 </td>
   <td style="text-align:left;"> $SPY We all know it dropped 40% in 30 days cause you were getting margin called </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:23:59 </td>
   <td style="text-align:left;"> $SPY Covid as an excuse for your overleveraged garbage. 2 months in you need trillions, give me a break </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:23:52 </td>
   <td style="text-align:left;"> Here we go 🚀 🚀🚀🚀 $TSLA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:23:26 </td>
   <td style="text-align:left;"> $SPY 475 should be playing at a stockmarket near you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:23:02 </td>
   <td style="text-align:left;"> $SPY look at the volume. you can&amp;#39;t afford it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:22:57 </td>
   <td style="text-align:left;"> $SPY Shorted calls ysday afternoon. I think we see a pullback. Long weekend with lot of risky headlines possible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:22:55 </td>
   <td style="text-align:left;"> $SPY $470 by open. That would be a yes! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:22:43 </td>
   <td style="text-align:left;"> $SPY 465 and then 470 and above </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:22:42 </td>
   <td style="text-align:left;"> $SPY apple and tesla is grossly overvalued in the hundreds of billions. crypto market? NFT market? liquidity will dissipate and you&amp;#39;ll be crying sorry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:22:12 </td>
   <td style="text-align:left;"> $SPY Earnings reports tomorrow before the markets open! @WinningAlerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:22:11 </td>
   <td style="text-align:left;"> $BB $SPY Futes ripping lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:21:40 </td>
   <td style="text-align:left;"> $SPY its not about how good the companies are doing, you raise the prices consecutively for no reason. no news. no contracts. nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:20:39 </td>
   <td style="text-align:left;"> $SPY futes ripping’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:19:38 </td>
   <td style="text-align:left;"> $SPY I’d like to call my dad J Powell for a lifeline </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:19:33 </td>
   <td style="text-align:left;"> $SPY acting like you have a clue when you needed trillions in stimulus to save your position </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:19:05 </td>
   <td style="text-align:left;"> $SPY all of a sudden the market is free money all you have to do is buy huh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:18:18 </td>
   <td style="text-align:left;"> $SPY hmm lets see itll keep going up for no reason or? what a bunch of clowns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:17:56 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:17:38 </td>
   <td style="text-align:left;"> $SPY bears make me laugh man. They are homeless for Christmas 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:17:00 </td>
   <td style="text-align:left;"> $SPY vol 8k. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:15:40 </td>
   <td style="text-align:left;"> $SPY $49,500 a day keeps the 9 to 5 away; Let&amp;#39;s go!! stock.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:15:00 </td>
   <td style="text-align:left;"> $SPY Omicron: Nature&amp;#39;s Vaccine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:14:14 </td>
   <td style="text-align:left;"> $SPY Shhhh we all buy puts if it go up real hard before tax season. Ask Elon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:12:41 </td>
   <td style="text-align:left;"> $SPY futes rippin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:12:04 </td>
   <td style="text-align:left;"> $SPY I bought these $470 puts and y’all tryna make me a liar. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:10:29 </td>
   <td style="text-align:left;"> $SPY Futes Rippin! Ahhh lets all go crazy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:10:03 </td>
   <td style="text-align:left;"> $SPY Oh Chit📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:09:18 </td>
   <td style="text-align:left;"> $SPY FUTES RIPPIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:08:16 </td>
   <td style="text-align:left;"> $SPY Join my discord.. it has made me. Absolutely nothin! How do you worth this thing anyhow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:08:13 </td>
   <td style="text-align:left;"> $SPY futes are finally ripping and all the sudden it’s dead quiet here ? Lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:06:45 </td>
   <td style="text-align:left;"> $SPY 

ATH Trolls. Resistance Trolls. Santa Rally Trolls. They all come to battle tomorrow! It’s about… to go… down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:06:20 </td>
   <td style="text-align:left;"> $SPY goodnight guys I love karaoke 💙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:06:12 </td>
   <td style="text-align:left;"> $SPY nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:05:07 </td>
   <td style="text-align:left;"> $SPY got me up all night constant thinking and big dreams </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:05:07 </td>
   <td style="text-align:left;"> $SPY &amp;amp; $TSLA  ( Three Black Crows ) Discussing How to Recognize a Sneaky Snake Strategy Break out,
72 views • Dec 22, 2021 Lets go Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:04:01 </td>
   <td style="text-align:left;"> $SPY Alright, I have finished capturing screen shots of everyone here. When your forecasts are wrong I fully intend to repost your comments and put them on blast because that is what my life’s great purpose has become. Lmao 

People these days lack creativity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:03:24 </td>
   <td style="text-align:left;"> $SPY got pumped Monday and put it all on spy long calls please don’t break me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:02:23 </td>
   <td style="text-align:left;"> $SPY slow rise to new all time high🤞🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 17:00:28 </td>
   <td style="text-align:left;"> $SPY &amp;quot;The implant, which costs 100 euros, will allow people to have their vaccine passports implanted to make them easily-scannable.&amp;quot;

Well Fuck You Sweden 🖕🇸🇪

https://www.insider.com/swedish-firm-under-skin-microchip-for-covid-19-passes-2021-12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:59:07 </td>
   <td style="text-align:left;"> $SPY Well will run to 4727 or even to 4750 today imo. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:58:50 </td>
   <td style="text-align:left;"> $SPY Tomorrow this with have highs and lows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:57:34 </td>
   <td style="text-align:left;"> S&amp;amp;P Futures
4,687.25
+1.25(+0.03%)
Dow Futures
35,657.00
+25.00(+0.07%)
Nasdaq Futures
16,152.00
-17.75(-0.11%)
Russell 2000 Futures
2,227.20
+7.90(+0.36%)

$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:57:16 </td>
   <td style="text-align:left;"> $SPY lol so now Amazon suddenly scares about fairness $AMZN 
https://www.cnbc.com/2021/12/22/covid-tests-amazon-limits-number-of-tests-you-can-buy.html?utm_content=Tech&amp;amp;utm_medium=Social&amp;amp;utm_source=Facebook#Echobox=1640183104 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:55:21 </td>
   <td style="text-align:left;"> $SPY futures getting weak. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:54:08 </td>
   <td style="text-align:left;"> $SPY the dow and small cap 🦾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:53:25 </td>
   <td style="text-align:left;"> $SPY she may come back down around 662 and retest again if she slides. I don’t think she ready to break 670 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:51:44 </td>
   <td style="text-align:left;"> $SPY One long look at futures and a few replies and now off to bed. I expect a light trading day but they could always surprise me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:51:35 </td>
   <td style="text-align:left;"> $SPY sliding on the water like a jet ski...lol karaoke is nothing happening tonight wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:51:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA SCOTTIE PIPPEN 🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:51:01 </td>
   <td style="text-align:left;"> $SPY freezing take: we don’t hit 500 until last month of 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:50:32 </td>
   <td style="text-align:left;"> $SPY I wanna interview some weird ass people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:48:03 </td>
   <td style="text-align:left;"> $SPY how much gold we actually have to support this money supply </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:47:09 </td>
   <td style="text-align:left;"> $SPY  $TSLA when  
this pumps we fly all way above aTH let me tell you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:46:27 </td>
   <td style="text-align:left;"> $SPY let’s say inflation report is really bad... does that cause a sell-off? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:44:38 </td>
   <td style="text-align:left;"> $SPY goin to jeweler bust the ap yeah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:43:39 </td>
   <td style="text-align:left;"> $spy momentum drops off when there’s long consolidation . The price drops to the next support. It’ll be back up soon though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:43:18 </td>
   <td style="text-align:left;"> $SPY lets go karaoke!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:43:10 </td>
   <td style="text-align:left;"> $SPY U-S-A,  U-S-A,  U-S-A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:42:31 </td>
   <td style="text-align:left;"> $SPY they waiting on inflation report in the morning..duh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:38:21 </td>
   <td style="text-align:left;"> $SPY probably not the best time of the day/night, but I am thinking on buying a 2010 s65 amg . Anyways , I think this goes up. Good luck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:33:37 </td>
   <td style="text-align:left;"> $SPY 🇺🇸🇺🇸🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:31:33 </td>
   <td style="text-align:left;"> $SPY small caps wants to fly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:31:21 </td>
   <td style="text-align:left;"> $SPY boring, one of the flattest nights </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:30:37 </td>
   <td style="text-align:left;"> $SPY she may fall hard coming out this consolidation. Or she will fly by 470. 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:30:28 </td>
   <td style="text-align:left;"> $SPY How @OldFngGuy got 8.5k followers is beyond me. Are you all lacking in father figures or what? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:28:49 </td>
   <td style="text-align:left;"> @OldFngGuy $SPY lmao this guy banned again? 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:28:31 </td>
   <td style="text-align:left;"> $QQQ $SPY futures flat just like yesterday; however, a dip at the open and a rip all day long!! LFG ATH!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:27:23 </td>
   <td style="text-align:left;"> $SPY $TSLA 

Robert Downey Jr. (net worth of $300 mill)
Elon Musk (net worth $261 bill) 

Similar public persona, New Iron Man in the MCU baby! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:25:39 </td>
   <td style="text-align:left;"> $SPY for day trading options go itm or 1 otm?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:21:45 </td>
   <td style="text-align:left;"> $SPY lol yall lack energy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:18:22 </td>
   <td style="text-align:left;"> $SPY $TSLA Y’all remember Elon symbolizing in Iron Man? 

https://youtu.be/DCyLOWfIrCU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:15:33 </td>
   <td style="text-align:left;"> $SPY $TSLA wait Elon said stock sales are “almost done” lmao. That man is rich. Metaphorically and Literally. Lets go $TSLA. Good thing you can hold $SPY up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:13:03 </td>
   <td style="text-align:left;"> $SPY &amp;quot;working on the weekend like usual&amp;quot;.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:12:04 </td>
   <td style="text-align:left;"> $SPY we can try karaoke on stocktwits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:11:24 </td>
   <td style="text-align:left;"> $SPY Puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:07:39 </td>
   <td style="text-align:left;"> $SPY wow, that is a really straight line of consolidation 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:06:19 </td>
   <td style="text-align:left;"> $SPY Day 3 👊🏻👊🏻👊🏻haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:05:29 </td>
   <td style="text-align:left;"> $SPY these vix crushes are just... idk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:03:21 </td>
   <td style="text-align:left;"> $SPY when i wake up spy will be over 470 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:02:52 </td>
   <td style="text-align:left;"> $SPY Time for bed after one last look at most likely slow moving futures. Final trading day this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:02:20 </td>
   <td style="text-align:left;"> $SPY Been sick for 3 days woke up make like $3.5k, went to bed, lost $3.5k. Oh, well, back to sleep more bottom feeding tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 16:01:59 </td>
   <td style="text-align:left;"> $SPY we love you Roddy rich 💙
https://m.youtube.com/watch?v=DtTj4TODL_U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:59:43 </td>
   <td style="text-align:left;"> $SPY Let’s pre-tesla fail Michael Burry the bit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:59:09 </td>
   <td style="text-align:left;"> $SPY what a joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:56:35 </td>
   <td style="text-align:left;"> $SPY get better guys lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:56:18 </td>
   <td style="text-align:left;"> $SPY can we be bullish really early tomorrow, then bearish towards the end of the day with 1% or more in either direction? 

Thank you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:55:54 </td>
   <td style="text-align:left;"> $SPY last time futures this flat was the covid drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:55:35 </td>
   <td style="text-align:left;"> $SPY are they really just gonna not address inflation and leave it as is over Christmas break?  Why are people so... obsequious? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:55:33 </td>
   <td style="text-align:left;"> $SPY $470+ EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:53:52 </td>
   <td style="text-align:left;"> $SPY rippity rip rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:50:51 </td>
   <td style="text-align:left;"> $TSLA she&amp;#39;s a dirty dancer, dancing for money 🎵📻  Tesla goes Tits up tomorrow! Call contracts are lactating 🐄, the same way $SPY  will be at or near $470 STRIKE PRICE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:48:17 </td>
   <td style="text-align:left;"> $SPY We secured SPY calls in the discord today for 400% gains. For more plays like this, join our discord, the link is in my profile </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:46:48 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ Bears are dead, keep this rolling tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:46:30 </td>
   <td style="text-align:left;"> $SPY how we doing guys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:44:37 </td>
   <td style="text-align:left;"> $SPY Omicron is the Best Thing to happen to humanity since the start of the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:42:50 </td>
   <td style="text-align:left;"> $SPY puts getting donkey fucked 😁💰💰 you live to see it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:41:33 </td>
   <td style="text-align:left;"> $SPY Joe’s getting a new dog he named “commander” (nicknamed Commie!? 
) because the first dog went crazy and started biting people. Took joe months to figure out this wasn’t going to work.  Seems normal. 
LETS GO BRANDON! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:41:30 </td>
   <td style="text-align:left;"> $SPY that horizontal line at 470 is back nothing suspicious there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:38:48 </td>
   <td style="text-align:left;"> $SPY feels good going to sleep knowing my calls will print :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:37:16 </td>
   <td style="text-align:left;"> $SPY no worries guys, I talked to Powell and he told me he will double the printing power by tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:36:04 </td>
   <td style="text-align:left;"> $SPY developed countries are getting 3rd and 4th and 5th boosters vaccine shots for covid , while poor countries are have not  even first vaccine . , such unequal distribution won’t end this pandemic.. but rather prolong and more variants will emerge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:35:27 </td>
   <td style="text-align:left;"> $SPY Damn it might go to 480+ on this stretch. Would like to see one more vix spike but don’t think that is going to happen now. guess I’ll be waiting until mid to Late January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:34:48 </td>
   <td style="text-align:left;"> $SPY why are tech futures red. Can I talk to the manager? Who is in charge here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:34:06 </td>
   <td style="text-align:left;"> $SPY $UVXY cant remember the last time I saw futures so flat.. everything priced perfectly in the market or is this the calm before a storm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:33:56 </td>
   <td style="text-align:left;"> $SPY tomorrow is a pamp day. the day after a major holiday is also a major pamp day. (monday). tuesday you prob will see a drop....get with the program, we know the drill.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:33:08 </td>
   <td style="text-align:left;"> Hard pass on new entries for tomorrow $SPY $DJIA $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:31:41 </td>
   <td style="text-align:left;"> $MRNA MRNA INVENTOR Robert Malone and Cardiologist Peter McCullough on OMICORN $SPY 

https://rumble.com/vr9kzs-dr.-robert-malone-and-dr.-peter-mccullough-omicron-variant.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:31:26 </td>
   <td style="text-align:left;"> $SPY flat like a pancake... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:31:21 </td>
   <td style="text-align:left;"> $SPY charge hospitals fees to the unvacinated.  Like Australia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:26:42 </td>
   <td style="text-align:left;"> $SPY long term spy is going to 290s 😘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:24:38 </td>
   <td style="text-align:left;"> $SPY we are the last one to understand the gravity of the situation, how badly it will impact to respond to an outbreak, because we don’t want lock down or quarantine and also want to control the spread , but there many among us still don’t believe the pandemic… and think it’s just a hoax … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:22:49 </td>
   <td style="text-align:left;"> $SPY $BABA $XBI $CEMI $CODX
China puts 13 million residents in lockdown ahead of Games
https://abcnews.go.com/Health/wireStory/china-puts-13-million-residents-lockdown-ahead-games-81910900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:18:08 </td>
   <td style="text-align:left;"> $SPY $JD $QQQ $DIA  
$BABA zero Covid policy…just the beginning…fresh off press!!  
BABA $60 coming soon!!  
JD low 20!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:15:49 </td>
   <td style="text-align:left;"> $SPY Biden  finds the money to keep this afloat.
https://mishtalk.com/economics/biden-wilts-under-progressive-pressure-extends-student-loan-repayment-pause </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:14:22 </td>
   <td style="text-align:left;"> $SPY Australia  charging the unvacinated.  Great  idea. Charge all the unvacinated  make them  pay. BUNCH of chickens. Making our ives miserable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:11:23 </td>
   <td style="text-align:left;"> $SPY Dont give a rat ass about what Omnicore news will bring this market  will go up higher as people have so much money in their pockets

Houses are bought off the market like candy

Cars are 5K above sticker

and why would companies not make money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:10:56 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ 

Futures so flat wtf? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:09:53 </td>
   <td style="text-align:left;"> $SPY  this is gonna fall hard.  It might open at 470$. But it’s gonna fall hard.  
1) unemployed numbers 
2) inflation talks 
3) long weekend (holiday) sell off 
4) early tax harvest sell offs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:09:43 </td>
   <td style="text-align:left;"> $SPY the permabulls justifying mega caps rallying 400% in 21 months are really great.  Just great stuff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:07:05 </td>
   <td style="text-align:left;"> Regardless $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:06:10 </td>
   <td style="text-align:left;"> $SPY  wrapping my kids gifts and still posting on ST is this my life ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:04:33 </td>
   <td style="text-align:left;"> $SPY usually there is a major market event about this time after natgas implodes. Look at your historical we are close to it if we are doomed to repeat boom and bust. (the American way). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:03:55 </td>
   <td style="text-align:left;"> $SPY easiest short I’ve ever seen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:02:44 </td>
   <td style="text-align:left;"> $SPY  someone put something strange in my eggnog </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 15:02:37 </td>
   <td style="text-align:left;"> $SPY $QQQ imma start loading up on qqq 420 calls for jan fuck it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:59:34 </td>
   <td style="text-align:left;"> $SPY low volume put grinder most likely for tomorrow.  Go spend some time with you family and hit the eggnog hard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:58:04 </td>
   <td style="text-align:left;"> $SPY China and Japan are green as fuck prepare yourself 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:57:45 </td>
   <td style="text-align:left;"> $SPY Ever tried a Pump n lettuce Sammich ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:56:44 </td>
   <td style="text-align:left;"> $SPY what is a good price for a used 2014 Mercedes Benz e350 sport rwd with 100k miles? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:55:38 </td>
   <td style="text-align:left;"> $SPY guess im.waiting on selling soybeans might sell es calls vix might start poppin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:54:54 </td>
   <td style="text-align:left;"> $SPY is there any benefit trading SPY over ES futures?  I find it so much more flexible trading futures and selling premium against my position over SPY.  I haven’t used SPY since learning the futures market.  So much more liquid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:52:09 </td>
   <td style="text-align:left;"> $SPY $QQQ dump or pump before long weekend unknown news🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:51:57 </td>
   <td style="text-align:left;"> $SPY I wonder what Crossingtrends new account is that dude made me so much money doing the exact opposite of whatever he said such a good indicator I think he got permanently banned for shilling his also program lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:49:32 </td>
   <td style="text-align:left;"> $SPY $qqq extremely bullish because market  always goes up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:47:28 </td>
   <td style="text-align:left;"> $SPY just stop already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:47:01 </td>
   <td style="text-align:left;"> $SPY is tomorrow a half day ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:45:45 </td>
   <td style="text-align:left;"> $SPY Looking forward to seeing what happens here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:45:33 </td>
   <td style="text-align:left;"> $SPY does the market close this Friday ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:43:57 </td>
   <td style="text-align:left;"> $SPY $AMC$GME blackberry As you know, we have been in negotiations regarding the sale of our non-core portion of our IP patent portfolio. This process is taking much longer than we had hoped. And trust me, I share the frustration about the time line. Negotiations are very close to a conclusion, and we are literally down to the last few important items now. Both parties are working hard to get this finished, and we expect to reach a definitive agreement very soon. We will provide shareholders an update on progress in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:39:25 </td>
   <td style="text-align:left;"> $SPY $TSLA Elephant has two sets of teeth. One for eating and one for world to see.
https://www.dailymail.co.uk/news/article-10337617/Elon-Musk-reportedly-secretly-living-12M-waterfront-estate-Austin.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:37:40 </td>
   <td style="text-align:left;"> $ES_F areas of interest for Thursday (12/23/21). 4657-4667 support area 1, 4648 support area 2, below that 4626 and 4616 targets. Opposite end, 4704-4714 resistance area 1, 4723 resistance area 2, 4745 and 4755 above targets. 
$ES_F #ES_F $SPY #SPY latexc47e27461683314834b1e34550c16059SPY hanging hammer perfectly setup past two days
$SNAP reversing off bottom 👌

Happy Holidays! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:35:01 </td>
   <td style="text-align:left;"> $CEMI 
$SPY $QQQ $XBI $XHE 
https://apnews.com/article/coronavirus-pandemic-joe-biden-health-jen-psaki-08ee41d8e7c0af1ad8b4dfb7b434ea61 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:32:36 </td>
   <td style="text-align:left;"> $SPY buncha naive bulls in here it feels like, sell signals for days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:32:10 </td>
   <td style="text-align:left;"> $SPY Does George Devore sound exactly like moo or is it just me? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:32:08 </td>
   <td style="text-align:left;"> $SPY 21 months and still, still going. Jesus h. Moo… stahp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:30:45 </td>
   <td style="text-align:left;"> $SPY Hi. I’m new any good tips for me? The reviews said to check out SPY thread. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:30:15 </td>
   <td style="text-align:left;"> $SPY China only 4K Covid deaths because they implement strict lockdowns! Meanwhile US 800k deaths because we care about money more than American lives! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:29:53 </td>
   <td style="text-align:left;"> $SPY how tf is this even legal??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:26:57 </td>
   <td style="text-align:left;"> $AMC $QQQ $SPY While the world is distracted, This is happening.  (I will post the info in the thread) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:26:33 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:26:33 </td>
   <td style="text-align:left;"> $SPY they better stop eating these rodents  and canine animals. It’s gross 🤮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:25:58 </td>
   <td style="text-align:left;"> $SPY bears about about to get their asshole torn &amp;amp; pumped full of cum. Stupid shit heads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:24:18 </td>
   <td style="text-align:left;"> $SPY dear god 21 months of this and they still won’t let it go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:21:14 </td>
   <td style="text-align:left;"> $SPY China would never lock down 13,000,000 people for no reason, it affect economy pretty bad . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:21:00 </td>
   <td style="text-align:left;"> $SPY futures 😌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:20:12 </td>
   <td style="text-align:left;"> $SPY Over 230k new daily cases in US… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:19:50 </td>
   <td style="text-align:left;"> $QQQ $SPY whats an effective muscle relaxer. Nothing controlled/CNS depressant like soma ( carisoprodol). Help plz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:16:50 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:16:30 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:16:22 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:15:11 </td>
   <td style="text-align:left;"> $SPY wtf??? Why did futures just dropped??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:14:36 </td>
   <td style="text-align:left;"> $SPY im drunk

🥴👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:13:57 </td>
   <td style="text-align:left;"> That’s a good one 😭 $SPY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:12:50 </td>
   <td style="text-align:left;"> $SPY how’s vix looking? can spy reach 475? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:12:38 </td>
   <td style="text-align:left;"> $SPY Is about 1.2% from ATH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-23 14:11:58 </td>
   <td style="text-align:left;"> $SPY Covid inflation yada yada 471 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 19:10:43 </td>
   <td style="text-align:left;"> $QQQ 400 next week I suppose…. Then massive blowoff run to 550-600 in 22’. Maybe bear market by 24’. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 18:59:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA SCOTTIE PIPPEN 🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 18:54:44 </td>
   <td style="text-align:left;"> Check out our E-Book at Thrashcap.com for a basic overview of the financial markets and options trading! $SPY $QQQ $DIA $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 18:52:30 </td>
   <td style="text-align:left;"> A Peek Into The Markets: US Stock Futures Edge Higher Ahead Of Economic Data  $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/a-peek-into-the-markets-us-stock-futures-edge-higher-ahead-of-economic-data/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 18:48:30 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 18:45:59 </td>
   <td style="text-align:left;"> $XLV broke out 2 weeks ago and might peak out near Fib 1.618 as it&amp;#39;s forming 3 white soldiers on the weekly before consolidating some weeks, respecting the channel since the March 2020 crash. Sector still bullish with the healthcare situation worldwide and so $XBI also has a bullish outlook heading into 2022, link to XBI chart: 
https://stocktwits.com/MLinv/message/419954238 
 
$IWM $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 18:44:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOXL Perhaps the issue, along with mid-term elections, that supports Tom Lee&amp;#39;s call for a rocky H1 &amp;#39;22. Expects gains in H2.

https://www.zerohedge.com/markets/markets-message-fed-will-go-too-far-slow-inflation-break-something </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 18:39:41 </td>
   <td style="text-align:left;"> What Should You Invest in During the New Year? Investing Strategies for 2022 $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/what-should-you-invest-in-during-the-new-year-investing-strategies-for-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 18:34:01 </td>
   <td style="text-align:left;"> World shares extend gains in thin pre-Christmas trading $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/world-shares-extend-gains-in-thin-pre-christmas-trading/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 18:33:00 </td>
   <td style="text-align:left;"> Possible low risk trading setup on $QQQ, buy stop entry @404.01.. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 18:23:57 </td>
   <td style="text-align:left;"> $QQQ breakout time. One last day for the bulls before the bloodiest sell of in recent memory next week. We will be looking to start a short around 396.50-397 today $SPY $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 18:00:57 </td>
   <td style="text-align:left;"> Economic Data Scheduled For Thursday $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/economic-data-scheduled-for-thursday-7/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 17:47:05 </td>
   <td style="text-align:left;"> $QQQ another inverse forming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 17:44:07 </td>
   <td style="text-align:left;"> $SPY $QQQ latexf53efdbfd7c16ae0efd68dc766617892BABA 5% down today 
$JD 12% DOWN today 
 
no buyers, no shorts to squeeze, no catalysts, horrible news and pending lockdown, delistings, and buyback lockouts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 17:42:18 </td>
   <td style="text-align:left;"> $XOS $NAKD $QQQ lulw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 17:38:01 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ Moving on to licensing. As you know, we have been in negotiations regarding the sale of our noncore portion of our IP patent portfolio. This process is taking much longer than we had hoped. And trust me, I share the frustration about the time line. Negotiations are very close to a conclusion, and we are literally down to the last few important items now. Both parties are working hard to get this finished, and we expect to reach a definitive agreement very soon. We will provide shareholders an update on progress in January.  shorts going be scrambling 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 17:32:18 </td>
   <td style="text-align:left;"> $QQQ sp rejected the previous resistance niiiiicely. Now we wait. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 17:31:59 </td>
   <td style="text-align:left;"> $QQQ for some reason, I can’t unsee this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 17:31:27 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $IWM US stocks rose midday Wednesday after consumer confidence came in higher than forecast for December and as third-quarter economic growth was revised higher, helping outweigh the continuing impact of the highly contagious omicron variant on investor sentiment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 17:23:52 </td>
   <td style="text-align:left;"> Here we go 🚀 🚀🚀🚀 $TSLA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 17:20:17 </td>
   <td style="text-align:left;"> $QQQ kinda weak pre market with all those dark pool buys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 17:18:21 </td>
   <td style="text-align:left;"> $QQQ 0.1% lfgggggggg haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 17:07:20 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 16:51:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA SCOTTIE PIPPEN 🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 16:44:02 </td>
   <td style="text-align:left;"> Bubble Update: Santa Claus Rally $QQQ $SPX https://talkmarkets.com/content/stocks--equities/bubble-update-santa-claus-rally?post=338811 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 16:28:31 </td>
   <td style="text-align:left;"> $QQQ $SPY futures flat just like yesterday; however, a dip at the open and a rip all day long!! LFG ATH!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 16:12:05 </td>
   <td style="text-align:left;"> $QQQ remember bears? Lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 15:52:56 </td>
   <td style="text-align:left;"> $qqq / $qqqj </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 15:46:48 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ Bears are dead, keep this rolling tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 15:18:08 </td>
   <td style="text-align:left;"> $SPY $JD $QQQ $DIA  
$BABA zero Covid policy…just the beginning…fresh off press!!  
BABA $60 coming soon!!  
JD low 20!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 15:10:56 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ 

Futures so flat wtf? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 15:02:37 </td>
   <td style="text-align:left;"> $SPY $QQQ imma start loading up on qqq 420 calls for jan fuck it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 14:52:09 </td>
   <td style="text-align:left;"> $SPY $QQQ dump or pump before long weekend unknown news🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 14:49:32 </td>
   <td style="text-align:left;"> $SPY $qqq extremely bullish because market  always goes up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 14:35:01 </td>
   <td style="text-align:left;"> $CEMI 
$SPY $QQQ $XBI $XHE 
https://apnews.com/article/coronavirus-pandemic-joe-biden-health-jen-psaki-08ee41d8e7c0af1ad8b4dfb7b434ea61 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 14:26:57 </td>
   <td style="text-align:left;"> $AMC $QQQ $SPY While the world is distracted, This is happening.  (I will post the info in the thread) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 14:20:32 </td>
   <td style="text-align:left;"> $QQQ Send it 400. Let’s ride these longs ALL the way 🔨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 14:20:14 </td>
   <td style="text-align:left;"> $QQQ everyone a damn bull here wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 14:20:11 </td>
   <td style="text-align:left;"> $qqq / $xlk     $aapl $MSFT  looks like we could see a melt up in the q&amp;#39;s for the next several weeks. aapl msft might be do for a breather. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 14:19:50 </td>
   <td style="text-align:left;"> $QQQ $SPY whats an effective muscle relaxer. Nothing controlled/CNS depressant like soma ( carisoprodol). Help plz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 14:16:50 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 14:13:07 </td>
   <td style="text-align:left;"> $QQQ $400 at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:57:12 </td>
   <td style="text-align:left;"> $QQQ  
Do any of you predict that Small Cap Indexes will outperform big tech in 2022? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:56:33 </td>
   <td style="text-align:left;"> $BX Absolutely remarkable morning star reversal and follow through on this beast...
$SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:48:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Some are asking for a correction?  Correction to where?  Given all the trillions in circulation, needing some place to land, that chart above this post IS correct. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:46:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $GOOG $AAPL  almost two years of straight up in SPY. 100% returns of lows.  No recession in 12 years. This is beyond crazy. A correction WILL come in 2022 and I don&amp;#39;t think it will be small. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:32:24 </td>
   <td style="text-align:left;"> $spy $qqq apple sales not closing this Q but moving to next.  Elon sells another M.  Both these can pressure indices </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:29:00 </td>
   <td style="text-align:left;"> Besides having an excellent technical rating, $QQQ also presents a decent setup pattern. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:22:55 </td>
   <td style="text-align:left;"> $DDOG I like this chart for a trip back to ATH. Calls over 185.
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:20:08 </td>
   <td style="text-align:left;"> Futures stunningly flat. Not moving at all. Means insane ripper tomorrow. no reason to sell. Don’t want to buy yet and have to close gap. 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:19:43 </td>
   <td style="text-align:left;"> $LLY I will be looking to go long over 270. Probably next week.
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:14:51 </td>
   <td style="text-align:left;"> $PANW Will be watching tomorrow as it is close to break ATH.
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:14:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN CANOES SHIPPIN OARS DIPPIN AND FLIPPIN SCOTTIE PIPPEN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 13:09:48 </td>
   <td style="text-align:left;"> $QQQ doge daddy will not provide the results to keep the cloud in the sky. Will provide useless Twatter. Non stop. Fraud. 
 https://www.reddit.com/r/Epic_Economics/comments/rmntd2/tesla_call_buying_shibby_investors/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:58:10 </td>
   <td style="text-align:left;"> $SPY $QQQ weak flutes... 
Beary Christmas! 🎅 🧸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:50:29 </td>
   <td style="text-align:left;"> $SPY Wow, mailed it in, 369 , I even hit the 363, yesterday few pennies short, now what? 

You&amp;#39;ll see. Probably benign but retail could take this up before retail takes it down Nonday, if you know what I mean pardner👍

444 espy real-real soon

&amp;quot;But I can&amp;#39;t put my money anywhere else&amp;quot;

Oh, you sure can and you better be ready to because better to make 1% interest than LOSE 25-50% invested in market.

Why don&amp;#39;t people get that ? 

$QQQ $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:46:49 </td>
   <td style="text-align:left;"> $TSLA   After reading, &amp;#39;These Kids&amp;#39; twice on two different posts ... I just TLDR&amp;#39;d it  lol      $GOOG  $MSFT  $SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:46:14 </td>
   <td style="text-align:left;"> 🚨 TRADE IDEAS FOR TOMORROW PART 1 🚨 :

$ACN - CALLS ABOVE $406 &amp;amp; PUTS BELOW $401

$PANW - CALLS ABOVE $557 &amp;amp; PUTS BELOW $550

$UNH - CALLS ABOVE $497 &amp;amp; PUTS BELOW $490

$QQQ - CALLS ABOVE $397 &amp;amp; PUTS BELOW $391

$COST - CALLS ABOVE $554 &amp;amp; PUTS BELOW $545

GOOD LUCK &amp;amp; ALWAYS TRADE SAFE 💎
FOLLOW ME HERE FOR MORE TRADE IDEAS 👈🏻 💎
www.thestocktraderhub.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:38:01 </td>
   <td style="text-align:left;"> Market Volume Barometer 12-22-2021
Sentiment: SKITTISH
Volume: -15%
Real Feel: FRIGID
Cycle: BEARISH II
Portfolio: CASH
Next Day Move: SIDEWAYS
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:35:50 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.cnbc.com/amp/2021/12/21/biden-says-fully-vaccinated-people-can-still-safely-celebrate-the-holidays-as-omicron-spreads.html 
 
If you are vaccinated then you can enjoy i this holiday without worrying anything. If you are unvaccinated though, you should isolate yourself and don’t go out to infect other people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:28:12 </td>
   <td style="text-align:left;"> The MACD: The Perfect All In One Indicator?

$QQQ $DWAC $NVDA $RIVN $PLUG

http://www.chartlearning.com/2021/07/what-is-MACD-stock-indicator-divergence.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:26:58 </td>
   <td style="text-align:left;"> $QQQ Every news channel 4,5,7,11,13 is non-stop about Omicron this, that, ICU, death, jab, booster, stay home &amp;amp; reject the unvaxed! Are they *trying* to crash the stock market? It&amp;#39;s not working. Everyone I know doesn&amp;#39;t give a shit about the damn virus anymore. ENOUGH already, seriously! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:15:08 </td>
   <td style="text-align:left;"> $SPY Anyone else buying nip bottles and scratch tickets on Christmas Eve at the 7-11 as thoughtful gifts this year? $AAPL $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:10:23 </td>
   <td style="text-align:left;"> $TSLA It would be fitting if the man with the ill advised haircut causes his stock, through ill advised comments, to also get a haircut. $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:10:03 </td>
   <td style="text-align:left;"> $SPY $QQQ Super wealthy are unloading and retails picking it up... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:04:58 </td>
   <td style="text-align:left;"> $SPY $QQQ  whole market breaking out tomorrow but the oversold growth stocks like $DIS $PYPL are getting the biggest push </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:02:54 </td>
   <td style="text-align:left;"> $QQQ guys! If you don’t have any cannabis stocks in your portfolio, I suggest you do it immediately!!!… doesn’t matter which ones, penny stocks, $TLRY $SNDL whatever! All of them are going to fly soon. I won’t go into detail, let’s just say, I know people in high places </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:00:25 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Goodnight Stocktwitters 😃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 12:00:01 </td>
   <td style="text-align:left;"> $QQQ $PTLO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:56:12 </td>
   <td style="text-align:left;"> $SPY $SPX $TSLA $QQQ $DIA  🧞‍♂️

I am just superstitious. 

The writings on the wall $4800.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:54:43 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM Russia will attac Ukraine just to claim back the city of Kiev, which is where the Russian history started. The current Russia without Kiev is like the Jews without Jerusalem, Taiwan without Beijing, Ireland without Northern Ireland Territory, and Greece without Istanbul </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:54:27 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $DJIA  🧞‍♂️

Joe Biden and Nancy Pelosi out partying with the stars

Merry Christmas 🎄 $4800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:49:10 </td>
   <td style="text-align:left;"> $BTC.X  $QQQ https://apple.news/ALTpgUEjIThyQW_Prv1w4Hg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:36:05 </td>
   <td style="text-align:left;"> Step No.1 of making money: 
 
Do not lose money= Do not buy Puts for $tsla even if you want to and it makes sense to do so.  
 
No.2 Make money  = buy more and more ITM $tsla calls.  
 
Your account after this 📈📈 
 
(this is not a financial advice of course, but you should definitely buy more calls if you want to print money.) 
 
$qqq $spy $amd $nvda are going to have Santa rally tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:33:59 </td>
   <td style="text-align:left;"> $FUBO Can a Fubro get to 50 likes?  Get even more tech and luxury in $TSLA latex495ff17f6262a4deb508f73b935b34eeQQQ: Needs 400+ for breakout 
$IWM: Look for push to 222 level next
Watch $AMD for big move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:24:23 </td>
   <td style="text-align:left;"> The one thing the Markets will teach you is you never know what Markets will do, every real Trader/Investor has been thru tough times, people who post &amp;amp; attack when things are not so happy are not really in the game.

Some of the best times are when you expect the worst. There is no way to time things &amp;amp; any of the GOATs will tell you that.

Take a break, get some air &amp;amp; dont worry about what happens tomorrow.  The hardest time to do what maybe best in Markets is when you feel like you want to break your screen :o)

ST is not the place to be if you&amp;#39;re looking for some sanity, $jd will be fine. WS just spent the past 6 months telling everyone to Buy it over $baba as it was &amp;quot;safer&amp;quot; &amp;amp; so cleaning out the sheep who trusted WS is a good thing

Looks like Xi wants to finish all that needs to be done prior to 2022 so,.. its a holiday week, enjoy it &amp;amp; dont let what is just a moment ruin whats really important, family, friends &amp;amp; your state of mind

$kweb $didi $qqq

 $JD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:24:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:16:33 </td>
   <td style="text-align:left;"> $AAPL take yall gains tomorrow on yall calls as options is getting expensive, and calls been making good gains this week. don&amp;#39;t be greedy, I do see it can drop so be careful bulls that includes $SPY  $QQQ  .. the drop could happen next week , lock gains on yall call !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:16:19 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Day trading ape while working a  9-5 job from home. 

Me at 9AM “Promise I’ll start actually doing work once the market opens” 

Me at 9:30AM “ehhh let’s just see how the market looks in the first 30 minutes”

Me at 12PM: after watching the market all day to this point, “I guess I’ll take a break and look for some scalp plays during lunch dip”

Me at 3PM: “Can’t work now it’s power hour baby, that email can wait until 4PM”

Me at 4PM: “Hmmm any AH runners?” *Puts off email for another 30 minutes*

Me at 8PM: Maybe I should focus on my to do list for tomorrow…. But then again I heard futes be ripping ???

Me at 3AM: spent all night scoping futes might as well wait until Germany opens to see some trends

Me at 4AM: back in at premarket scary hours, here we are again my old friend 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:13:45 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK 

I’m going to law school to make sure I put musk behind bars for fraud, lies and endless market manipulation. The muskrat will be prosecuted!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:12:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMC Who’s watching the new Matrix tonight? 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:05:35 </td>
   <td style="text-align:left;"> $QQQ: Either making lower highs, or we finally see this breakthrough. 398 resistance. Above that, 400 is breakout level to watch. Look for 390 to act as support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 11:04:24 </td>
   <td style="text-align:left;"> $SPY $QQQ  heading towards a huge supply zone tomorrow, wouldn’t be surprise if it’s a volatile day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:44:03 </td>
   <td style="text-align:left;"> $QQQ can we get 400 tomorrow?💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:37:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA Likely tomorrow the NASDAQ-100 tests downtrend resistance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:30:35 </td>
   <td style="text-align:left;"> $BTC.X everyone you should buy this it&amp;#39;s going to go way up. It&amp;#39;s going to go so hi up it will be crazy. Make lots of money and BUY NOW! $QQQ $AMZN $BRK.B </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:19:50 </td>
   <td style="text-align:left;"> $spy $aapl $QQQ 
Dont short the market now. Wait till they all hit new ATHs to short. Your chances will be a lot better to make money. Now is not the time to short the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:19:00 </td>
   <td style="text-align:left;"> $SPY bears waking up tomorrow to ATHs across $DJIA $QQQ $SPY $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:18:09 </td>
   <td style="text-align:left;"> $aapl If this is not V recovery, what can be.. 

There is no downside to this fed bull market. All bad news shrugged off. Stonks only go up.. It&amp;#39;s okay to be stupid if it makes me money in this market. $aapl to hit $180 tomorrow. 

$spy $qqq $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:14:39 </td>
   <td style="text-align:left;"> $AAPL There is. a good chance this is hitting $180 tomorrow. Grabbing the calls at open and will diamond hand them to $180 

$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:12:04 </td>
   <td style="text-align:left;"> $QQQ 

Let’s get that 400 this year….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:10:30 </td>
   <td style="text-align:left;"> $QQQ added 50k $SQQQ shares to my 45k position because something’s definitely not right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:08:48 </td>
   <td style="text-align:left;"> $QQQ hey </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:08:19 </td>
   <td style="text-align:left;"> $QQQ $400 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:07:48 </td>
   <td style="text-align:left;"> Hope everyone had a decent trading day. Was pretty slow $SEAC did not pan out, I was very intrigued with the news rarely do you see a micro cap merge with a large valued private company. Many sold the news today could get bounces but prob dead for now. Large cap craziness $TSLA $QQQ $UPST $AFRM. Just remember the largest bounces happen in the most bearish markets or panic times. I am remaining bearish into 2022. I will be happy too be wrong if next year we are higher then where we are on all of these indexes and large cap names </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:01:33 </td>
   <td style="text-align:left;"> $QQQ SpoOokY Real-Time 
Trade Action Opportunity Tracking Tool

Rolling Trade Action Opportunity
Trigger ALERT Range:
(394.76 / 384.99)

Logarithm (x+n)
Short Wavelength Plot 
Calibration UpDate

Last Finite Potential Well 
Measurement at: 393.95
For:
12/23/21 at 4:00AM EST Pre-Market

Developing Ad Interim Trade Action 
Opportunity Potentials:
Short-Term = SELL
Long Term = SELL

sWAV SpoOokY: 
DOES NOT!!!
FORECAST STOCK PRICE, 
OFFER BUY/SELL ADVICE, or 
RECOMMEND ANY STOCK for 
TRADE or INVESTMENT.   
SpoOokY is for:
EDUCATION and ENTERTAINMENT ONLY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 10:00:48 </td>
   <td style="text-align:left;"> $QQQ Quite literally a gigantic bullflag on the 3M (on Stocktwits) 

Dang </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:58:15 </td>
   <td style="text-align:left;"> $SPY charts aint lyin, party is almost over.. $QQQ your party has been over... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:51:07 </td>
   <td style="text-align:left;"> $IWM $SPY $QQQ Happy holidays! Protect yourself and your loved ones and get boosted. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:46:01 </td>
   <td style="text-align:left;"> $FUBO $TSLA $TWTR $QQQ Only 9 likes?  PAMP it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:40:39 </td>
   <td style="text-align:left;"> $SPY $QQQ . HOW I FEEL (watching the gains grow in my account). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:36:02 </td>
   <td style="text-align:left;"> $AAPL $QQQ PCE Inflation Data releasing tomorrow morning… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:31:47 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK 

So Elon blatantly lies in an interview to pump his stock up so that way he can sell at a higher price and instead of being punished for market manipulation he’s praised. What a joke this country has become where billionaires can get away with anything and money has become more important than morales. Eventually karma will catch up to Musk and I can’t wait to see that day, you reap what you sow and it will happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:25:52 </td>
   <td style="text-align:left;"> $QQQ based on history, big up move in January coming 🆙🆙🆙🆙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:25:44 </td>
   <td style="text-align:left;"> $QQQ $SPY futures are ripping!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:22:58 </td>
   <td style="text-align:left;"> $SPY BULLS I LOVE YA BUT I JUST PRAY U MAKE IT OUT UNSCATHED FROM THE UPCOMING RUGPULL. I WAS TRADING SINCE 1969 TRUST ME OK $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:22:00 </td>
   <td style="text-align:left;"> $QQQ has an excellent technical rating and also presents a decent setup pattern. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:21:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 
Normal hours tomorrow and no time off for New Years
https://www.marketwatch.com/story/merry-christmas-wall-street-but-theres-no-new-years-day-holiday-for-the-stock-market-this-yearheres-why-11640192753 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:12:17 </td>
   <td style="text-align:left;"> $QQQ direction confirmed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:09:28 </td>
   <td style="text-align:left;"> $QQQ $SPY the volume was dropping and it&amp;#39;s right before Christmas long weekend. In addition to this, jobless claim report is releasing. We&amp;#39;ve got another opportunity to buy more tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:08:23 </td>
   <td style="text-align:left;"> 5 Most-Heavily Traded ETFs of Fourth Quarter $UVXY $QQQ $SQQQ $SPY $XLF https://talkmarkets.com/content/etfs/5-most-heavily-traded-etfs-of-fourth-quarter?post=338768 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:07:15 </td>
   <td style="text-align:left;"> $qqq $aapl $spy 

Market is bullish. Stop buying puts for next 3 days. Market may run  much higher before you can short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:07:03 </td>
   <td style="text-align:left;"> $SPY $QQQ  who’s booking profit tomorrow to avoid long weekend uncertainty. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:05:02 </td>
   <td style="text-align:left;"> $SPY $TLT $QQQ friendly reminder from my broker. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:04:58 </td>
   <td style="text-align:left;"> $QQQ looking to re open puts end of January. Let this overstuffed pig fatten up a bit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 09:02:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $BABA $JD 
 
china across board de risking…dumping risk on shareholders…wow!! NOT criminal?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:59:52 </td>
   <td style="text-align:left;"> $QQQ https://youtu.be/mabh6tN1BoQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:57:25 </td>
   <td style="text-align:left;"> $AAPL To everyone who is wondering what will happen tomorrow -

Market will run up high. $aapl will lead the way and may hit $180 to print $180 calls. Grab your calls when you can tomorrow.

Market is insanely bullish right now. There is no reason for this market to be even a bit fearful. It has shrugged off every other reason. 

Sell your puts and move to calls asap if you want to be in the winning side. I&amp;#39;m saying what I&amp;#39;m seeing. No bias. 

$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:51:08 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM people are rushing into this market by the close of market today. Everyone is saying Santa Rally and people start to feel that it will be too late if they don’t get in now. People are expecting huge up tomorrow because the Christmas holiday is the next day. This is when the market is going down. Huge bull trap today, especially by the end of market close. No volume today and yesterday which means short can easily break through all resistance levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:50:49 </td>
   <td style="text-align:left;"> $AAPL After seeing today&amp;#39;s price action, I&amp;#39;m putting all my money on AAPL $175 calls tomorrow. $aapl will run to the moon and make me a millionaire in a day. 

$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:49:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $NVDA 

12/22 recap:

$1k -&amp;gt; $1m options challenge update 🚀

Day 11: 
- Initial: $1,000
- Current: $6,865 
- Target: $1,000,000 by Late Feb

Today was an easy day, one of those days where you come in with a plan and all you have to do is buy and sell and you can be on your way. 

Options challenge up to a cool 11/11 and the formula seems to be holding up. As usual compounding all gains with 99% accuracy. 

Will be interesting to play the Thursday Exp tomorrow, but I don’t doubt that we will get it done. 

A lot more peeps are following and joining in so feel free to do so, let’s prove what can be done by anyone, anywhere. 

More info to join: https://the-band-trades.square.site/

Updated chart ✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:48:57 </td>
   <td style="text-align:left;"> $QQQ The key takeaway from the Q3 GDP report is that the growth had a lot to do with the change in private inventories. Real final sales of domestic product, which excludes the change in private inventories, were up 0.1%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:48:54 </td>
   <td style="text-align:left;"> $SPY $aapl $qqq Never bet on bears in bull market. Puts won&amp;#39;t print, bears are weak. 

Be the bull, buy calls. MMs will work for you to print the calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:48:51 </td>
   <td style="text-align:left;"> For the die-hard option traders, a gr8 way to maximize profitability is to break down your option traders via a Journal.

TradesViz breaks ur trades down w/ respect to the greeks (IV delta etc) &amp;amp; OPEX. Breaks down where u r losing &amp;amp; winning.
$QQQ $SPY $TSLA $AAPL $NVDA

Join Free  👉 http://www.tradesviz.com

Sample Chart below
👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:46:20 </td>
   <td style="text-align:left;"> $QQQ isn’t there inflation data releasing tommrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:45:15 </td>
   <td style="text-align:left;"> $SPY $QQQ santa rallys are for the bulls. Never try to stop it. Jesus died on the cross for us bulls to have these gargantuan gains. Fuck you bears! Pieces if shit. Jesus hates you and forgives only us bulls, obviously. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:42:23 </td>
   <td style="text-align:left;"> $QQQ Last trading day before Christmas , Nasdaq up 9 of last 13 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:38:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL so pissed at team $PFE for missing the opportunity to have a COVID pill/Viagara combo.

ED and SARS cured in one pill smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:30:34 </td>
   <td style="text-align:left;"> $tsla $qqq $spy https://www.youtube.com/watch?v=ViWBBJtayzg&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:29:30 </td>
   <td style="text-align:left;"> $QQQ Covid, Covid, Covid - going Red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:24:10 </td>
   <td style="text-align:left;"> $SPY if there is going to be a Santa rally tomorrow this will open up very red $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:21:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $SPX $DJIA 

Hey remember buying those 450p ATM for 12/23?

Enjoy making emotional decisions and being poor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:18:00 </td>
   <td style="text-align:left;"> $QQQ calls are challenging. Usually on a day like this they would be up over 100% instead of up around 25%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:17:52 </td>
   <td style="text-align:left;"> Cramer says U.S. won’t need lockdowns to manage the omicron surge, and that’s good for stocks

$SPY $QQQ $DJIA $IWM

https://www.cnbc.com/2021/12/22/jim-cramer-on-omicron-us-wont-need-lockdowns-and-thats-good-for-stocks.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:16:31 </td>
   <td style="text-align:left;"> $QQQ $NQ_F thoughts on chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:15:45 </td>
   <td style="text-align:left;"> $QQQ vaccines stocks starts to rise again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:13:38 </td>
   <td style="text-align:left;"> $QQQ who’s buying the rip 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:11:05 </td>
   <td style="text-align:left;"> $QQQ $SPY FUTES. ARE. RIPPING. F J B!!! SANTA IS HEREEEEEEEEEEE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:09:54 </td>
   <td style="text-align:left;"> $QQQ That’s more than 100% from the entry. This is call is ITM and we still have one more week 🚀🚀
3–&amp;gt;6.7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:09:27 </td>
   <td style="text-align:left;"> $QQQ $SPY i trust my cat over futes and all signs point to dead cat bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:09:14 </td>
   <td style="text-align:left;"> Indices Shift To Trading Ranges $QQQ $IWM $SPX https://talkmarkets.com/content/stocks--equities/indices-shift-to-trading-ranges?post=338789 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:04:56 </td>
   <td style="text-align:left;"> $QQQ https://a.webull.com/ga6CRVPYdXzljrBjty sign up with my link and we both get 5 free stocks!- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 08:00:43 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX   🧞‍♂️🧑‍🎄

The Vix is closer to $16       👊🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:59:24 </td>
   <td style="text-align:left;"> $VIX The Vix gapping down tomorrow 

Caught up now in a “Death Spiral” 
                Close to $16 

   $spy $spx $qqq $dia   🧞‍♂️👊🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:56:53 </td>
   <td style="text-align:left;"> $QQQ Nasdaq McClellan Oscillator update - back above zero </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:56:11 </td>
   <td style="text-align:left;"> $ALLK $SPY $QQQ 

Just yolo’d 100 shares in a risk free fed driven market. We all know this will magically go back up and the headlines will be some bs short squeeze. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:55:05 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ FUTES FUTING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:49:39 </td>
   <td style="text-align:left;"> #Volatility Likely To Remain Elevated For The Balance Of Year $QQQ $TSLA $SPX $VIX https://talkmarkets.com/content/stocks--equities/volatility-likely-to-remain-elevated-for-the-balance-of-year?post=338786 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:49:08 </td>
   <td style="text-align:left;"> $QQQ past few weeks were brutal. More to come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:39:46 </td>
   <td style="text-align:left;"> The bottom is in??

$SPY $QQQ $SVIX $XOP $SPG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:37:08 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ Santa Rally starts the day AFTER Christmas, this is just pre cum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:36:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM What I learned from ST:

You must not speak in terms of probabilities. Doing so shows weakness. You must act like you know what the market is going to do at all times. Never use phrases like &amp;quot;it might do&amp;quot; something, or &amp;quot;it seems probable&amp;quot; to do something else. Using such nuance is for pussies and may lead you to trade small and think about what happens if you&amp;#39;re wrong, which you know you shouldn&amp;#39;t do you proud Stocktwits member you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:28:39 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $IWM $DIA   
 
Those who are around 28-35 years of age are in a unique situation.  Half of our developmental years (middle/high school) without the &amp;quot;smart&amp;quot;phone &amp;quot;technology&amp;quot;, and &amp;quot;social&amp;quot; media. 
 
And half of it with. 
 
No other generation will have had such an experience.   
 
And I&amp;#39;ve concluded that society would, in aggregate, be far better off without all these devices.  It&amp;#39;s really a regression of the human psyche, dressed up as &amp;quot;innovation&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:27:45 </td>
   <td style="text-align:left;"> $BABA It keeps hitting the 115s and sooner or later, it will buckle down and go lower.  Thank $QQQ as it&amp;#39;s holding all the Chinese stocks afloat.

Wonder what happens when $QQQ takes a nasty dive?  It&amp;#39;s holding unbelievably strong and just keeps marching higher and higher where as $KWEB is hitting lows consistently.

Tale of two worlds.  Wonder what Xi has in store for Thursday?  If only he and his cohorts remain quiet for a month or two, the sentiment will change. Until then, it&amp;#39;s the traders having a field day with the Chinese stocks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:27:08 </td>
   <td style="text-align:left;"> $QQQ NASI - a rare uptick today - it&amp;#39;s a start!  #bigopportunity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:25:27 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA FUTES fucking RIPPING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:25:14 </td>
   <td style="text-align:left;"> $QQQ 400
 https://www.interactivebrokers.com/mkt/?src=xiaowangY&amp;amp;url=%2Fcn%2Findex.php%3Ff%3D2359 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:25:14 </td>
   <td style="text-align:left;"> $QQQ I was waiting for this breakthrough all day long, finally it did it with decent volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:24:23 </td>
   <td style="text-align:left;"> $SPY $QQQ here comes the sad bears saying “no one will hold over the long weekend” 😂 y’all dumbasses say that every time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:22:39 </td>
   <td style="text-align:left;"> $AMC $QQQ $SPY I listen to Biden’s speech yesterday and then look at the stats in my area......things that make u go 🤔 hmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:22:18 </td>
   <td style="text-align:left;"> $ba $spy $qqq Boeing will be under pressure? More delays? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:20:24 </td>
   <td style="text-align:left;"> $QQQ Santa Rally is coming and confirmed. Will gap up tomorrow morning and look into buying 400 Call lotto, Price is above 255 days and broke through 393.18. Very Very </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:19:39 </td>
   <td style="text-align:left;"> $QQQ 1 more push please and thank you.  Then I switch from bullish to bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:16:51 </td>
   <td style="text-align:left;"> Most US Indices completed a morning star candlestick pattern yesterday, with follow through today. This is a bullish reversal candlestick pattern. $IWM $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:16:07 </td>
   <td style="text-align:left;"> Volatility Likely To Remain Elevated For The Balance of Year https://mottcapitalmanagement.com/volatility-likely-to-remain-elevated-for-the-balance-of-year/ $tsla $spy $qqq $vix $skew </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:09:57 </td>
   <td style="text-align:left;"> $MRNA long weekend ahead; god knows what ugly form COVId can take over 3 day period. With Christmas gatherings and the fast spread nature of omicron there will sure be crazy spike $spy $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:08:00 </td>
   <td style="text-align:left;"> Besides having an excellent technical rating, $QQQ also presents a decent setup pattern. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:07:49 </td>
   <td style="text-align:left;"> $spy $qqq with virus and long weekend I would be weary to hold long positions.  Spy could be under pressure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:06:42 </td>
   <td style="text-align:left;"> FUTURES RIPPING

THAT IS NOT SNOW SANTA IS SNORTING

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:06:04 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 12/22/2021 $SPY $XLF $QQQ $CCJ $TSLA https://www.chartguys.com/daily-market-videos/4087/what-happens-after-the-bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:04:05 </td>
   <td style="text-align:left;"> $QQQ there we go. I’m back to being happy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:03:57 </td>
   <td style="text-align:left;"> $SPY $qqq $dia $iwm
I am looking for freaking 2% tomorrow.
My math is always right $$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:02:18 </td>
   <td style="text-align:left;"> $QQQ watch for the lower high though. Longs will have to pray for a higher peak. If there is no Santa rally from here, I am a bear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 07:01:04 </td>
   <td style="text-align:left;"> $SPY $QQQ The next shoe to drop is Manchin agreeing to a modified BBB budget.  And he will.  At that precise point we rip to ATH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:58:43 </td>
   <td style="text-align:left;"> $spy $qqq $dia $iwm
Be fucking GREEDY.
we still have way more to go $$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:55:13 </td>
   <td style="text-align:left;"> $SPY latexc4a988d931d0248158a00adcc0594346$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:54:32 </td>
   <td style="text-align:left;"> $AMZN Watch market pop at 6pm and at around 9pm tonight
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:53:06 </td>
   <td style="text-align:left;"> $QQQ Do you see what I&amp;#39;m seeing?
https://share.trendspider.com/chart/QQQ/6682i4sf5x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:49:18 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:48:42 </td>
   <td style="text-align:left;"> $SPY $QQQ so omnicovid isn&amp;#39;t deadly thank goodness- oh wait, but it&amp;#39;s 70% more infectious and if you do get it you have to stay isolated for 14 days.? wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:47:27 </td>
   <td style="text-align:left;"> #Nasdaq100 Gains as Traders Seek Exposure to Risk-Assets on Santa Rally Hopes $QQQ $NDX https://talkmarkets.com/content/stocks--equities/nasdaq-100-gains-as-traders-seek-exposure-to-risk-assets-on-santa-rally-hopes?post=338782 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:43:50 </td>
   <td style="text-align:left;"> $SPY $QQQ when will bears understand infatuation is bullish? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:42:34 </td>
   <td style="text-align:left;"> $SPY QUADRUPLE TOP ON $470 IN PROCESS. WHOEVER CHASED THE TOP AND FOMOE&amp;#39;D INTO A BID SPOOFING ALGO MANIPULATED LOWEST-VOLUME-OF-THE-YEAR- INORGANIC SCAM RALLY WILL GET A TAUGHT A LESSON VERY SOON. TODAY WAS THE PERFECT DAY TO SELL THE DELUSIONAL PERMABULLS DEEP OTM CALLS CAUSE THEY&amp;#39;RE EUPHORIC BRAINS CAN&amp;#39;T PROCESS RATIONAL THOUGHT ANYMORE $QQQ $IWM $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:37:07 </td>
   <td style="text-align:left;"> $QQQ https://youtube.com/channel/UCS16RWxIEk4IGmbTKwS7AKQ 😶‍🌫️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:32:59 </td>
   <td style="text-align:left;"> $spy $qqq $iwm $tna Santa rally  coming now! If you want to know how to gain that much, pm me and I can invite you to the discord! ❤️❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:31:21 </td>
   <td style="text-align:left;"> $QQQ Prediction for eoy 2022 
My guess is 520 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:27:11 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPX $SPY Lets not get complacent, The stock market ended last week with a powerful rally which was a relief to many traders. Despite the ups and downs, on a weekly basis, it was not too bad a week, as the strong Friday close helped offset the losses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:18:36 </td>
   <td style="text-align:left;"> $tna $tza $djia $spy latex4440869ac2203c9b129d11abbe600d91tsla may dip in the morning but will reverse imminently. Hold them calls 💎 🙌  
 
$qqq $spy $nvda $nasdaq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:07:19 </td>
   <td style="text-align:left;"> $SPY         $spx          $qqq    🧞‍♂️🌀

Thank Goodness for Companies
like $PFE Pfizer  and like $TSLA  

To push us up and over $4800 on index level tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:05:52 </td>
   <td style="text-align:left;"> $AMZN $QQQ $SPY Lots of DARKPOOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:05:47 </td>
   <td style="text-align:left;"> $ROKU No ceilings. We ride 🐎👀
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:02:23 </td>
   <td style="text-align:left;"> $SPX $SPY $ES_F               $qqq $dia 

Tesla should push us up up up to $4800+ 🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 06:00:28 </td>
   <td style="text-align:left;"> $QQQ come on u gotta admit this one is pretty funny </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:59:00 </td>
   <td style="text-align:left;"> $SPY $QQQ
I either have Covid or the flu.  Have most of the symptoms except loss of taste and smell.  Caught it from my wife who only had a cough.  I had to explain to her that when a virus migrates from women to men, it mutates into something much much more severe.  Facts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:57:49 </td>
   <td style="text-align:left;"> $SPY $QQQ Have to feel bad for the bears lol, they actually thought this market was gonna fall apart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:56:01 </td>
   <td style="text-align:left;"> $QQQ $SPY if you want to solve the labor shortage issue… pull the rug, keep it pulled, and you’ll be amazed how many people go back to work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:54:59 </td>
   <td style="text-align:left;"> $QQQ ngl that end of the pump got me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:52:41 </td>
   <td style="text-align:left;"> $QQQ gaining on that 100% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:51:02 </td>
   <td style="text-align:left;"> $NVDA $TSLA $QQQ $SPY never working again!!! Just buy these and let them go way up! The market is allowing me to retire early and not have to worry about my horrible fucking boss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:50:45 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 537.5K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:50:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA If can’t copy Tesla, just copy Elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:50:16 </td>
   <td style="text-align:left;"> Santa came early! Shoutout to $SPY and $QQQ for giving us some awesome trades today! Once $TSLA got going, it was off to the races! Calls PRINTED (see below). $BVXV provided a setup nice and early for the day trade… almost 40% here. Then to top it all off, $MSFT Calls gave us 130%+. Onto the next! Stay blessed, and I’ll see you later! ✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:49:52 </td>
   <td style="text-align:left;"> $QQQ &amp;quot;who is the incremental buyer?&amp;quot;  this phrase is thrown around often and it is so stupid.  all day every day there are buyers and sellers in equal volume at the exact price you see on your screen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:47:50 </td>
   <td style="text-align:left;"> $QQQ top phrases used by newbie traders -- be on the lookout for these idiots:

1. red/green candles
2. puts/calls are printing
3. market makers are burning theta
4. bearish/bullish flag on the chart
5. head and shoulders, next leg down! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:41:02 </td>
   <td style="text-align:left;"> $QQQ IMO we will retest the highs and top of range around 415. 

Tomorrow shit lots of TQQQ expire in the money. Could rocket. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:40:37 </td>
   <td style="text-align:left;"> Stocks waver on Wall Street ahead of Christmas holiday $SPY $QQQ $DJIA  https://www.billionaireclubcollc.com/stocks-waver-on-wall-street-ahead-of-christmas-holiday/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:39:52 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ  WOW! 👏👏👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:38:06 </td>
   <td style="text-align:left;"> $SPY $QQQ futes rippin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:36:50 </td>
   <td style="text-align:left;"> $QQQ i hate when people use the wrong terms.  lots of people say &amp;quot;xyz is overvalued or undervalued&amp;quot;.  that&amp;#39;s BS.  XYZ is simply valued at the price you see on the screen and that valuation is subject to change in the future.

never forget that EVERY SINGLE DAY the exact same number of shares are bought as sold or vice versa.  doesn&amp;#39;t matter if things have been going up or down or left or right. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:34:52 </td>
   <td style="text-align:left;"> $QQQ $398+ Tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:34:51 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ  
 
Indices forming equal lows or lower lows with a VIX lower high is a powerful divergence. Now confirmed by 3 day thrust and VIX &amp;lt;20. To me this signals fresh ATH is the higher probability outcome for indices and likely imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:33:29 </td>
   <td style="text-align:left;"> Stocks waver in early going on Wall Street ahead of holiday $QQQ $DJIA $SPY  https://www.billionaireclubcollc.com/stocks-waver-in-early-going-on-wall-street-ahead-of-holiday/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:32:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Preliminary option volume of 31.9M today is 23% below recent average. Calls led puts 19.75M to 12.15M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:32:00 </td>
   <td style="text-align:left;"> $SPY “anonymity has no bearing on the performance of your option acct.” to test the theory we link the option account to a 3x inverse full options account that takes the opposite side of every SPY $IWM or $QQQ option order we place. The only slippage is the width of the spread. 

With a 5% win-loss percentage, we are bound to make money if we just keep trading like dog shit. 

In other words, deterministic ex post implementation requires that the same alternatives must be chosen irrespective of agents signals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:31:27 </td>
   <td style="text-align:left;"> $QQQ that last 15 minute melt up was suspect… 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:31:14 </td>
   <td style="text-align:left;"> $SPY $QQQ just woke up. Did I do this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:30:50 </td>
   <td style="text-align:left;"> $SPY $SPX $VXX $UVXY $QQQ

https://stocktipstips.substack.com
.
Tomorrows Economic Data Releases
-Personal Income/Spending 
-Durable Goods Orders
-Jobless Claims
- PCE Price Index
-New Home Sales
-Consumer Sentiment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:28:45 </td>
   <td style="text-align:left;"> So, uhhhh one way or the other, tomorrow&amp;#39;s gonna be kind of a big deal. *shrug emoji*

Hedged w/ SQQQ at the close, ready to rip it off if necessary.

$QQQ $SQQQ $TQQQ $ENPH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:26:26 </td>
   <td style="text-align:left;"> 🚀 My Bullseye Trade Still Has Room to Run to Big Resistance $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/%f0%9f%9a%80-my-bullseye-trade-still-has-room-to-run-to-big-resistance/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:25:10 </td>
   <td style="text-align:left;"> $QQQ $SPY god damn this market is hot right now! Nothing can or will stop it - NOTHING!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:24:19 </td>
   <td style="text-align:left;"> $177.44 give me $185
$AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:23:50 </td>
   <td style="text-align:left;"> $QQQ solid! Sold calls at close. Expecting a dip tomorrow before the long weekend. Then rip next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:22:35 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ 

https://seekingalpha.com/amp/article/4475662-own-apple-aapl-stock-through-berkshire-hathaway </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:21:48 </td>
   <td style="text-align:left;"> $tsla Reversal Confirmed, heading to new highs tomorrow 📈 📈 
$qqq $spy $amd $aapl Strong close today, congrats 🎊 Tomorrow will be big bull party 🎉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:21:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA  sell off tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:21:13 </td>
   <td style="text-align:left;"> $SPY $QQQ Still nervous we fall off. After all we have the greatest threat to a prosperous market…the great retard Joe Biden. He is a champ at f’n a good thing up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:20:37 </td>
   <td style="text-align:left;"> $SPY $QQQ I would usually trim more here on day 3 up but I am scared to sell too much.  This has rejected $470 13 times prior....we may see it just gap and bull rush over $470 and leave whoever is not in wishing they were.  🤔

Is it really going to reject $470 a 14th time.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:19:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Hope ya&amp;#39;ll boys took profits...it&amp;#39;s time to pay the piper tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:19:35 </td>
   <td style="text-align:left;"> $QQQ bears getting whoooppeeed out her </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:18:52 </td>
   <td style="text-align:left;"> $QQQ took a fat lotto 400 calls for tomorrow at .05 - hoping for an extension into tomorrow obviously </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:18:43 </td>
   <td style="text-align:left;"> $QQQ $SPY Economy built on massive debt and stock market purely driven by memes and on speculation. Sounds healthy &amp;amp; sustainable, nope! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:18:41 </td>
   <td style="text-align:left;"> $spy $qqq unvaccinated uninvited guest 
Outside and therefore Bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:18:15 </td>
   <td style="text-align:left;"> So to all the complainers about how Biden was ruining the market 4 days ago.  Is he now saving the market?  He must be the best Prez ever. You know the market collectively had only about 100 hours of real selling this entire year?  There are 8765.2 hours in the year by the way.  $QQQ $DIA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:17:33 </td>
   <td style="text-align:left;"> $QQQ Nasdaq at the top of the descending channel. What do you think, can we squeeze out one more day? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:16:46 </td>
   <td style="text-align:left;"> $SPY $QQQ We decided that anti vaxers need to not come. You have been uninvited. It’s patriotic to shine you on and bullish to protect the flock. Oh about that, you are fired! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:16:32 </td>
   <td style="text-align:left;"> $QQQ  I love how the fear and greed index shows &amp;quot;fear&amp;quot;.... Oh yeah... people seem scared shitless right now... LMAO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:15:41 </td>
   <td style="text-align:left;"> $QQQ closed above $393 &amp;amp;
$SPY above  $453 means we’re back in bullish business 💎🥳🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:15:20 </td>
   <td style="text-align:left;"> $SPY $QQQ not bad for a market that was on the verge of rolling over on Monday.  How many times have we seen this market about to fall of a cliff...seemingly....and buyers come in.   Every time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:15:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$113M to the BUY side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:14:53 </td>
   <td style="text-align:left;"> $spy well, as an independent, impartial enough to say be thankful for the Pres. - he is santa for saying he&amp;#39;ll get something done with Manchin and for getting a handle on omicron.  $qqq $pfe $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:14:13 </td>
   <td style="text-align:left;"> $MRNA $bntx Kill Bill the Prophet of Viruses: 
$spy $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:13:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:13:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:13:12 </td>
   <td style="text-align:left;"> $QQQ $396-$398 tomorrow is my PT hitting right into volume shelf. Now closed strong through 20SMA....  
 
https://share.trendspider.com/chart/QQQ/8130i182n6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:13:08 </td>
   <td style="text-align:left;"> $SPY $QQQ sorry anti vaxer but you are gone. Better not liable for you and your mothers foul germs. Uninvited to the party. I feel for you and your snot balls but We can’t be liable for your health loser </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:12:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ Is it worth it to trade tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:12:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 12/23 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:12:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 👉👏👏👏👍🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:12:02 </td>
   <td style="text-align:left;"> $QQQ 85.71% profitable trades here with a 6.15 profit factor. Check out the performance of the new signals on the chart by UltraAlgo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:11:13 </td>
   <td style="text-align:left;"> Congrats to my new trader on their first day.  See what happens when you listen?  $BB for 100% option trade and $QQQ for 300%   You just did better than most people did all year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:11:04 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Wow Biden market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:10:06 </td>
   <td style="text-align:left;"> $SPY $QQQ Uninvited Unvaccinated Guest List update Bullish! We can’t be your mother for you. Then you are fired. Goodbye Well He’s my next call sucker </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:10:04 </td>
   <td style="text-align:left;"> Absolutely MONSTER 2 day rally first 2.25% yesterday then ANOTHER 1.24% today when Pajama says  mind bender he means mind bender OH MY

Santa Claus rally not even officially started yet

$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:09:30 </td>
   <td style="text-align:left;"> $QQQ on the way to test 398-399 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:09:20 </td>
   <td style="text-align:left;"> $QQQ $SPY ive been telling my friends about the market and to consider investing everything into it. People do not need to work when we are this unbalanced and can just invest our life savings. Fucking idiot sheeps out there working hard while us bulls hardly work. Fuck off with your comments, I made more money than ever today with Tesla and my QQQ calls. Never - fucking - working - again!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:08:42 </td>
   <td style="text-align:left;"> $SPY do we get 4720 close in ES tomorrow ? You know what it means .. it means 4880-4920 in just following 2 weeks. $UVXY $DIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:08:32 </td>
   <td style="text-align:left;"> If you&amp;#39;ve missed the entire amazing year in the greatest market of all time you could&amp;#39;ve  just bought some wednesday $QQQ calls into the close just now and made 300-500%  2022 is now over. Quit now with a 300% gain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:07:18 </td>
   <td style="text-align:left;"> $SPY $QQQ  $AAPL Stocks are overvalued… it’s the end of the world… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:07:00 </td>
   <td style="text-align:left;"> Although the technical rating is only medium, $QQQ does present a nice setup opportunity. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:06:32 </td>
   <td style="text-align:left;"> This is why Hedge Funds use A.I. $QQQ price moved above its 50-day Moving Average. View odds of downtrend. https://srnk.us/go/3261316 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:06:19 </td>
   <td style="text-align:left;"> $QQQ @AptitudeFinancial  man is getting destroyed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:05:43 </td>
   <td style="text-align:left;"> $spy $QQQ who sold in fear last Friday or Monday. I got you future. No Santa Rally for you. More money coming 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:05:16 </td>
   <td style="text-align:left;"> $QQQ free profits at this point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:05:05 </td>
   <td style="text-align:left;"> $SPY $QQQ 

if we pump straight to $475 tomorrow I will believe in Santa. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:04:10 </td>
   <td style="text-align:left;"> $MRNA $bntx my friend Bill has a message for you: 3 months. He knows what‘s up: $spy $qqq $nvax HOHOHO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:03:51 </td>
   <td style="text-align:left;"> $QQQ there she blows! 400! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:03:48 </td>
   <td style="text-align:left;"> $QQQ Made more than enough money for the year.
Look forward to 2022.

No volume, and not limit up.
Fun game until its not.
Merry Christmas to all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:03:42 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:03:02 </td>
   <td style="text-align:left;"> $DWAC Thanks for voting for Biden guys, our economy would be dead without him. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:02:23 </td>
   <td style="text-align:left;"> &amp;#39;New York reports 28,924 new coronavirus cases, the biggest one-day increase on record, of which 17,221 are in New York City&amp;#39; -Tweet From BNO Newsroom 
 
$SPY $QQQ $MRNA $JNJ $PFE  
 
https://twitter.com/BNODesk/status/1473758441944530944 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:02:17 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ 

https://twitter.com/forbes/status/1473760388244283395?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:02:14 </td>
   <td style="text-align:left;"> $QQQ $SPY apes run this market now. We buy everything and hold. Shorts are bitch ass pussies. God damn today was a good day! Lets go bulls! Keep getting rich! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:01:39 </td>
   <td style="text-align:left;"> $SPY Thank god it closed. I was starting to get worried about getting assigned on my $QQQ short $395 C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:01:14 </td>
   <td style="text-align:left;"> $QQQ wow what a pump 🤘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:00:58 </td>
   <td style="text-align:left;"> Market wrap:
🔷 US indices closed higher on the day: 
$DJIA +0.7%, $SPX +1.0%, $QQQ +1.1%
🔷 #Gold (+0.9%) and #WTI (+2.4%) both rallied as well.
🔷 #AUD was the day&amp;#39;s strongest major currency; #JPY was the weakest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:00:52 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ

Wall Street wins again!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:00:49 </td>
   <td style="text-align:left;"> $QQQ breakout draweth nigh... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:00:32 </td>
   <td style="text-align:left;"> $SPY $QQQ Child’s Play. Volatility the Monday after expirations. Even if you tell them they don’t listen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 05:00:17 </td>
   <td style="text-align:left;"> $QQQ nice last minute push on low volume … love my QQQ bulls! You guys are the bestest !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:59:33 </td>
   <td style="text-align:left;"> $QQQ  Great job! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:59:30 </td>
   <td style="text-align:left;"> $QQQ $SPY  buy this dip too!! Buy it! Fuck omicron, fuck sick people and whatever they do to scare our market! Never work again, play the market! Fuck laborers!!! Were rich bitch!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:59:09 </td>
   <td style="text-align:left;"> $SPY $QQQ my kids schools are all closed again for covid lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:58:53 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:58:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $SMH $IHI ... Santa Claus Rally is real. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:58:22 </td>
   <td style="text-align:left;"> $QQQ don’t you love it when these new “Robinhood traders” try to come into the comments and act like they’re pros … go sit in the corner and update your Robinhood app, little boy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:57:34 </td>
   <td style="text-align:left;"> $QQQ i am happy to take all the money being given me but it is hard to feel like it is deserved -- oh well -- just more evidence why i NEVER short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:57:14 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 

2021 has been phenomenal year for WALL STREET BULL!

FREE TRILLIONS FROM JDADDY!!!

X-MAS RALLY!!!

RECORD BONUSES!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:56:53 </td>
   <td style="text-align:left;"> $QQQ never work again! Play the stock market! Fuck labor! Got that money on an imaginary rally bitches!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:56:50 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:56:34 </td>
   <td style="text-align:left;"> WELCOME SANTA

What took you so long? $SPY $QQQ #cuckoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:56:34 </td>
   <td style="text-align:left;"> $spy $qqq $dia $iwm
Love it. Way to go bulls
Tomorrow 2% $$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:56:27 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

SANTA BOUGHT CALLS!!!🎅 📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:56:26 </td>
   <td style="text-align:left;"> $QQQ $SPY WHAT THE FUCK IS GOIJG ON? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:56:24 </td>
   <td style="text-align:left;"> $QQQ The grind up never stops. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:55:38 </td>
   <td style="text-align:left;"> 4.00  entry to 14.00. One more day to go. $QQQ 380 calls. EXP tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:55:15 </td>
   <td style="text-align:left;"> $QQQ nasdaq shot up 100 points in an hour. Dont be fucking stoopid. Go in now! Buy the rip! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-23 04:54:33 </td>
   <td style="text-align:left;"> $QQQ Greedy motherfuckers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 19:23:38 </td>
   <td style="text-align:left;"> $AAPL I sold $177.50 covered calls expiring today now I’m going to lose the shares I’ve had for 10 years 😞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 19:20:31 </td>
   <td style="text-align:left;"> $AAPL does stock market close early today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 19:16:19 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL) – Apple Shuts 8 Shops Amid COVID-19 Resurgence: Report https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-apple-shuts-8-shops-amid-covid-19-resurgence-report/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 19:13:18 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 19:07:03 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-22 Trade Analysis Video: 
https://www.youtube.com/watch?v=B651JLQXFWc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 19:04:22 </td>
   <td style="text-align:left;"> Ticker: $AAPL
Buy: December 31, 2021 $177.50 Calls
Entry Price: $2.30 - $2.35
Exit Price: $3.24
Stop Loss: $2.02
Potential ROI: 41%
Estimated Hold Time: 13 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:56:36 </td>
   <td style="text-align:left;"> $AAPL 

https://www.bloomberg.com/news/articles/2021-12-23/intel-to-expand-in-france-germany-and-italy-in-comeback-effort </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:52:50 </td>
   <td style="text-align:left;"> $AAPL Just the beginning baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:52:43 </td>
   <td style="text-align:left;"> $AAPL Apple Shuts 8 Shops Amid COVID-19 Resurgence: Report 

https://newsfilter.io/a/1b0150e3143540803a1976cd541e0d00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:51:41 </td>
   <td style="text-align:left;"> 12.23 Day Trade Idea

The choice 1, 2, 3 means that in either direction strong conviction.

If price is already met over or under by 2 points then it is recommended no trigger. For an example, if MSFT is 337 by market open, and I have over 334 then it has already passed alert trigger by 3 points, which too much over the alerted price.

It is recommended to buy in the money or near the money on 0dte.

Remember to review your DD. Good luck on lotto Friday and place your own profit and loss stops.
$JD $MSFT $SPY $AAPL $NVDA

*JD UNDER 68.30(GAP DOWN FILL TO 66.30) #1 choice

*MSFT OVER 334, MSFT UNDEE 331.45 #2 choice

*SPY OVER 468.50, SPY UNDER 466.85 #3 choice

AAPL OVER 176.60, AAPL UNDER 174.60

NVDA 295.50, NVDA UNDER 291.50

JOIN TRIAL CHANNEL FOR 5 DAYS
https://t.me/+boyKMgL-eugzODY5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:43:36 </td>
   <td style="text-align:left;"> If you could only buy 1 OTM Call which would it be? 

$AAPL $200 

OR

$TSLA $1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:29:49 </td>
   <td style="text-align:left;"> $UBER $AAPL $TSLA 
search it &amp;quot;3q82dwzcRp&amp;quot; on Google and checkout the first link! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:28:23 </td>
   <td style="text-align:left;"> $TSLA $AAPL OMG we movin on up again 😂🤙🥂💰💰💰💰💰💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:22:37 </td>
   <td style="text-align:left;"> $AAPL LORD GAVE ME ANOOOTHER CHAANCE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:19:11 </td>
   <td style="text-align:left;"> $NEON wake up America!!! Read up on the lawsuit against Apple, Samsung. It could make Neonode become a tenbagger over night.
Beside that they have their touchless touch and gesture tech since a couple of years. Company about to turn around. Stock cheap - potential enorm
Zzzzzzzzzzzzzzz wake up!!!
Sell $TSLA and $AAPL and help US sky🚀 market cap only $140 million </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:17:01 </td>
   <td style="text-align:left;"> $AAPL Buy and sell, pump and dump, what a pleasure . Money money, money. 
I&amp;#39;m a 
r💲ch    B💲tch

Signature here: X_______________________________ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:06:12 </td>
   <td style="text-align:left;"> $AAPL and I don’t understand Apple, why can’t you, waiiiit forrrrr meeeeeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:03:00 </td>
   <td style="text-align:left;"> $AAPL 181 would change my fucking life today. LFG SANTA CUMMING AND HORNY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:02:59 </td>
   <td style="text-align:left;"> $AAPL 190 EOD! 185 calls to the moon! Ho ho ho! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 18:00:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 48 analysts. The buy consensus is at 83%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:52:38 </td>
   <td style="text-align:left;"> $AAPL 💥💥💥❤️❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:50:27 </td>
   <td style="text-align:left;"> $CABA CABA 20 to 30% possible reversal bounce  today. 400% cheaper from average target price, Bargain price. $BABA $AAPL $TSLA $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:45:05 </td>
   <td style="text-align:left;"> $AAPL it looks like it&amp;#39;s going to hit $177.8 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:44:36 </td>
   <td style="text-align:left;"> $AAPL $176.07 let’s go!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:38:07 </td>
   <td style="text-align:left;"> $AAPL as for calls expiring expiring EOD today, the open interest on the 177.5 is low relative to the 180s. MMs might not let it pass $180 but I believe if we see the indices green we have room to move up today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:30:53 </td>
   <td style="text-align:left;"> $AAPL trending - only stock I continue to buy &amp;amp; sell still lock in profits pump &amp;amp; dump for the win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:15:05 </td>
   <td style="text-align:left;"> $AAPL Warren buffet dumped a bunch of shares at levels like this.. be careful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:14:56 </td>
   <td style="text-align:left;"> $AAPL Be Carefull!!! 🚨 options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:06:08 </td>
   <td style="text-align:left;"> $AAPL Do $180 calls expire worthless? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:02:47 </td>
   <td style="text-align:left;"> $AAPL Simulated 180.0 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:02:19 </td>
   <td style="text-align:left;"> $AAPL we think calls here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 17:02:11 </td>
   <td style="text-align:left;"> $RKLY $AAPL $MDT Rockley Photonics is an Apple supplier and Medtronic strategic partner. Currently contracted with 16 companies which &amp;gt;60% of the wearables market. Look for their products in smart watches, fitness bands, and hospital clinical trials in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 16:37:57 </td>
   <td style="text-align:left;"> $AAPL 

Santa Uncle 
!!

Gift of Apple rally to 200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 16:32:18 </td>
   <td style="text-align:left;"> Anyone here bullish on $aapl?

Besides buying calls and shares, you can also write puts to get weekly / monthly income

I’ve done up a step by step guide to put writing on thinkorswim

Do take a look if it interest you 

Thank you

🟥 Thinkorswim tutorials : How To Sell Puts On TD Ameritrade Desktop
https://youtu.be/QSdaBXDQ04E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 16:31:24 </td>
   <td style="text-align:left;"> $AAPL 

All time high — SANTA gift

185 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 16:30:15 </td>
   <td style="text-align:left;"> $AAPL what&amp;#39;s it looking like Germany </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 16:24:41 </td>
   <td style="text-align:left;"> Ticker: $AAPL
Buy: December 31, 2021 $177.50 Calls
Entry Price: $2.30 - $2.35
Exit Price: $2.62
Stop Loss: $2.02
Potential ROI: 14%
Estimated Hold Time: 29 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 16:16:34 </td>
   <td style="text-align:left;"> $RBLX  $WIMI  $AAPL  What is the underlying technology logic behind the &amp;quot;meta-universe&amp;quot; that the giants are discussing in depth?

https://medium.com/@elyseewpryh67/what-is-the-underlying-technology-logic-behind-the-meta-universe-that-the-giants-are-discussing-3b9eaf84517a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 16:01:05 </td>
   <td style="text-align:left;"> $AAPL 181 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 15:48:55 </td>
   <td style="text-align:left;"> $AAPL $200 on the 31st </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 15:43:48 </td>
   <td style="text-align:left;"> $AAPL    

$185 EOY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 15:43:38 </td>
   <td style="text-align:left;"> $AAPL 

$200 heading for 

The next resistance line could be $180 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 15:34:06 </td>
   <td style="text-align:left;"> $GOOGL anyone that is long Google should be long $MSFT and $AAPL . Period 

$3,300 PT
$550 PT
$250 PT respectively </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 15:31:35 </td>
   <td style="text-align:left;"> $AAPL alright fellas, are we hitting $180 tmrw?? Like if u agree or comment if u think nah! Casino will be open soon 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 15:22:37 </td>
   <td style="text-align:left;"> Keeping $GRAB and $DIDI at the cost of parting from $AAPL 
Only time will tell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 14:20:11 </td>
   <td style="text-align:left;"> $qqq / $xlk     $aapl $MSFT  looks like we could see a melt up in the q&amp;#39;s for the next several weeks. aapl msft might be do for a breather. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 14:16:09 </td>
   <td style="text-align:left;"> $AAPL 

$185 EOY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 14:16:00 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 14:06:05 </td>
   <td style="text-align:left;"> $AAPL 

This is the next Apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 14:06:03 </td>
   <td style="text-align:left;"> $AAPL https://www.techradar.com/news/tim-cook-has-been-spotted-wearing-the-top-secret-apple-diabetes-device </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 14:03:21 </td>
   <td style="text-align:left;"> $AAPL Simulated 180.0 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:51:09 </td>
   <td style="text-align:left;"> $SPY holy fuck they filmed the new matrix with a iPhone camera $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:46:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $GOOG $AAPL  almost two years of straight up in SPY. 100% returns of lows.  No recession in 12 years. This is beyond crazy. A correction WILL come in 2022 and I don&amp;#39;t think it will be small. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:42:41 </td>
   <td style="text-align:left;"> $AAPL bullish as fuck 176 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:39:31 </td>
   <td style="text-align:left;"> SweepCast alerted: $AAPL with Unusual Options Activity Alerted on $175 CALL Expiring: 12-23-2021 worth 135K🐂 |🥇 Check out ➡️ SweepCast.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:36:11 </td>
   <td style="text-align:left;"> $AAPL If price actions stays over 175.84. Next levels of resistance are $178.17 &amp;amp; 181.14. Can see 185 next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:35:03 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-22 Trade Analysis Video: 
https://www.youtube.com/watch?v=B651JLQXFWc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:25:52 </td>
   <td style="text-align:left;"> $SPY $GOOG $AAPL $AMC $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:25:26 </td>
   <td style="text-align:left;"> $AAPL The last quarter was poor, I expect the next and next to be even worse, this company can&amp;#39;t innovate.  I expect the augmented tech to come out in five years.  Car 10-15, just CNBC bubble pumping currently </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:22:10 </td>
   <td style="text-align:left;"> $AAPL latexfa04fa0c847181209dfa862c409f473eTSLA - Tesla shares are trading higher after Elon Musk reached his goal to sell 10% of his Tesla stake. Calls above latexd90984e746364767ccd99f28696cbd5aAAPL- Morgan Stanley Sees Surprise Upside In Apple&amp;#39;s iPhone Production. Calls above latex82be9c47c2fe70a1a70b552297086697NFLX - stock above resistance line. Looking for calls above latex2915be587a417ac70ed75ab9cca07904ADBE - stock down on earnings. Trying to bounce back. Looking for calls above 568

$PYPL - stock has a lot of upside. Could be one of the top picks for santa rally. Calls above $192.5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:16:23 </td>
   <td style="text-align:left;"> SweepCast observed: $AAPL with Unusual Options Activity Alerted on $172.5 CALL Expiring: 12-23-2021 worth 36K🐂 https://www.sweepcast.com/optionflow?symbol=AAPL&amp;amp;name=CALL&amp;amp;strike=$172.5&amp;amp;type=SWEEP&amp;amp;pre=$36K&amp;amp;exp=12-23-2021 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:16:18 </td>
   <td style="text-align:left;"> ⏳📈💰 $AAPL - Apple Closes Another 7 US, Canada Stores As COVID-19 Cases Among Employees Rise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 13:05:30 </td>
   <td style="text-align:left;"> $AAPL stock analysis 
https://youtu.be/H8pd7_jDbqg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:59:00 </td>
   <td style="text-align:left;"> $AAPL is one of the better performing stocks in the Technology Hardware, Storage &amp;amp; Peripherals industry. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:58:17 </td>
   <td style="text-align:left;"> $AAPL $SPY $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:57:55 </td>
   <td style="text-align:left;"> $SPY Who&amp;#39;s yoloing? $AMD $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:57:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Closes Another 7 US, Canada Stores As COVID-19 Cases Among Employees Rise https://www.stck.pro/news/AAPL/20195046 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:39:57 </td>
   <td style="text-align:left;"> $AAPL entry break $176
Targeting $178-179+
Stops at $175
Ill play the $177.5 Calls 12/23 lotto
https://share.trendspider.com/chart/AAPL/11367ih5zxl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:39:51 </td>
   <td style="text-align:left;"> $AAPL all these negative bad bears are going to make me call ☎️ Krampus the great. Y’all going on the naughty list 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:21:08 </td>
   <td style="text-align:left;"> $AAPL 1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:15:08 </td>
   <td style="text-align:left;"> $SPY Anyone else buying nip bottles and scratch tickets on Christmas Eve at the 7-11 as thoughtful gifts this year? $AAPL $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:15:00 </td>
   <td style="text-align:left;"> $AAPL Futes flat.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:10:23 </td>
   <td style="text-align:left;"> $TSLA It would be fitting if the man with the ill advised haircut causes his stock, through ill advised comments, to also get a haircut. $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:08:03 </td>
   <td style="text-align:left;"> $AAPL They keep releasing bs after hours man 🤦🏽‍♂️ Hopefully it won’t affect tomorrows price action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:05:19 </td>
   <td style="text-align:left;"> $AAPL https://m.benzinga.com/article/24750421?utm_campaign=partner_feed&amp;amp;utm_source=TechInvestorNews&amp;amp;utm_medium=partner_feed&amp;amp;utm_content=site </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:05:16 </td>
   <td style="text-align:left;"> $AAPL Santa coming down my chimney now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:03:48 </td>
   <td style="text-align:left;"> $AAPL Santa Clause is coming tomorrow? 🎅🎅🎅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:02:33 </td>
   <td style="text-align:left;"> $AAPL Apple Closes Another 7 US, Canada Stores As COVID-19 Cases Among Employees Rise 

https://newsfilter.io/a/8082670e94873a045a4709689a33fe59 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 12:00:35 </td>
   <td style="text-align:left;"> $AAPL Guys be positive do you thinks the wild run it did in last one hr for going back ?? Tomorrow Apple is going to lift the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:59:33 </td>
   <td style="text-align:left;"> $AAPL can apple reach $200 in January?!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:56:36 </td>
   <td style="text-align:left;"> $AAPL I’m think we are going to $180 tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:41:36 </td>
   <td style="text-align:left;"> $AAPL $NVDA $RBLX 

https://newsfilter.io/articles/metaverse-fights-climate-crisis-413cb77de1f8b8b374aa93cac5b11e4d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:38:15 </td>
   <td style="text-align:left;"> The MACD: The Perfect All In One Indicator?

$TSLA $MRNA $AAPL $FUBO $GME 

https://www.chartlearning.com/2021/07/what-is-MACD-stock-indicator-divergence.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:34:48 </td>
   <td style="text-align:left;"> $AAPL Good night 172 see u in da Am bright n early 🙏🏻🤞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:33:03 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-22 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=jPyx5uZDRy4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:27:24 </td>
   <td style="text-align:left;"> $AAPL I did cover my short yesterday but am looking to get back in tomorrow... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:21:42 </td>
   <td style="text-align:left;"> $AAPL I don&amp;#39;t know the full backstory, but there may be of concern to some. https://twitter.com/cherthedev/status/1473726048353374208?t=RCF5vJ_Pz6YuSfT-vcPtng&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:20:00 </td>
   <td style="text-align:left;"> $AAPL took my profits. Happy trades and have a good holiday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:17:24 </td>
   <td style="text-align:left;"> $AAPL Reddit group in nothing before MMS don’t care them when it cones to FAANG Stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:16:33 </td>
   <td style="text-align:left;"> $AAPL take yall gains tomorrow on yall calls as options is getting expensive, and calls been making good gains this week. don&amp;#39;t be greedy, I do see it can drop so be careful bulls that includes $SPY  $QQQ  .. the drop could happen next week , lock gains on yall call !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:15:34 </td>
   <td style="text-align:left;"> Year is 2024: $BB  is 100$, $AAPL is 1000$, $HOOD is 100$ and so on...

But real OG $PLTR is still at 21$.

Literally WTF this stock is doing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:07:37 </td>
   <td style="text-align:left;"> $AAPL tomorrow 
what bulls want gap up to 177 then run to 179.
likely  gap up to 177 then sell down to 176  maybe lower.
if not sell off premarket 175 then climb to 176-177.
bears wants sell to 174.5 then flush down (nothing is indicating that would happen) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:02:55 </td>
   <td style="text-align:left;"> $AAPL what now?  9 tril?? 🤣💩🔥🔥🔥🔥  bulltards. Few. No floor. 
 #Apple #investing #madeinchina profits over people. 
 https://www.reddit.com/r/Epic_Economics/comments/rmltkh/apple_shuts_stores_bulls_say_triple_the_trillions/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:02:52 </td>
   <td style="text-align:left;"> $AAPL Simulated 180.0 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 11:00:30 </td>
   <td style="text-align:left;"> $AAPL I’m sorry but tm is gonna have to be blood red it MM dont wanna get over a hundred million shares called from them. I say we close at 169.99 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:59:30 </td>
   <td style="text-align:left;"> $AAPL Well done today boys and girls. I pitty the fool that shorts 🍎. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:58:09 </td>
   <td style="text-align:left;"> $AAPL 178+ possible tomorrow.. i think downtrend hits

Link in bio for free discord where i provide daily and pre mkt analysis with price targets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:58:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 7.00. This indicates good health for $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:57:34 </td>
   <td style="text-align:left;"> $TSLA $BTC.X $ETH.X $AAPL $PLTR 

Moonshot Money TOP 10 HOLDINGS (UPDATE)
https://youtu.be/kNOPA2E8ln4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:55:01 </td>
   <td style="text-align:left;"> $AAPL is always a buy… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:47:23 </td>
   <td style="text-align:left;"> $PINS chart looks decent support conquered.

Will start a position tomorrow.

$CLOV $TGLS $WISH $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:45:13 </td>
   <td style="text-align:left;"> $AA Goes noticeably Higher possibly to 67.00
Similar to 2018 Elliott Wave Moves however higher prices were hitting Peaks for AA in 2021 currently. 
The B peak “may”continue higher 10% possible to 67.00 if Market continues higher. We shall see. So far however 
AA has outperformed the $SPY MARKET
AA could continue to outperform Hot flashy stocks DKNG PTON that lost leadership in 2021 
AA is outperforming $FCX $CLF and even 
Technology  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:42:06 </td>
   <td style="text-align:left;"> $SMURF $AAPL $BTC.X $FB $SPY 

https://ca.finance.yahoo.com/news/ready-2022-metaverse-real-estate-201536572.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:41:53 </td>
   <td style="text-align:left;"> $AAPL  look at last report in Nov 4% oh my your smoked out if you even think its close to that now lmao Got Pootz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:40:02 </td>
   <td style="text-align:left;"> $AAPL Key News Update 
U.S. SEC rejects Apple bid to block shareholder proposal on forced labour 
https://www.reuters.com/article/apple-labour/u-s-sec-rejects-apple-bid-to-block-shareholder-proposal-on-forced-labour-letter-idUSKBN2J202T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:38:11 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMD $TSLA Lol all of tech is $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:37:27 </td>
   <td style="text-align:left;"> $AAPL https://www.bloomberg.com/news/articles/2021-12-22/apple-shuts-at-least-seven-stores-since-tuesday-amid-covid-surge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:37:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : SEC Denies Apple&amp;#39;s Bid To Block Shareholder Proposal On Forced Labor https://www.stck.pro/news/AAPL/20189502 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:36:09 </td>
   <td style="text-align:left;"> $TSLA $AAPL up again tomorrow 🙏🤙🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:34:16 </td>
   <td style="text-align:left;"> $AAPL night night bears. See you tomorrow! 😘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:33:08 </td>
   <td style="text-align:left;"> $SPY $IWM $AAPL $AMZN 
Germany will from Dec. 28 limit private gatherings to 10 people, shut nightclubs and require soccer matches to be played behind closed doors, DW.com reports.

Portugal will from Dec. 26 through at least Jan. 9 require bars and nightclubs to remain closed and the country will limit outdoor gatherings to 10 people per group on New Year’s Eve, the Guardian notes.

The Netherlands announced last Saturday a nationwide lockdown effective on Sunday, and all nonessential stores, bars and restaurants will be closed until Jan. 14, AP reports.

France and Austria tightened travel restrictions, while Paris canceled its New Year&amp;#39;s Eve firework celebration, per AP.

In Denmark, theaters, concert halls, amusement parks and museums have all closed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:31:26 </td>
   <td style="text-align:left;"> $BTC.X $SMURF $AAPL $FB $SPY 

https://www.cnbc.com/amp/2021/12/22/here-are-the-companies-building-the-metaverse-meta-roblox-epic.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:29:44 </td>
   <td style="text-align:left;"> $AAPL https://www.thestreet.com/apple/.amp/other-products/apple-stock-will-the-apple-car-be-the-ultimate-tesla-killer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:29:11 </td>
   <td style="text-align:left;"> $AAPL https://www.patentlyapple.com/patently-apple/2021/12/apple-won-44-patents-today-covering-future-smart-fabrics-for-clothing-apple-watch-bands-and-vehicle-upholstery-and-much-more.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:28:18 </td>
   <td style="text-align:left;"> $AAPL https://www.idropnews.com/rumors/apple-car-may-feature-futuristic-outer-display-and-advanced-warning-system/176357/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:19:50 </td>
   <td style="text-align:left;"> $spy $aapl $QQQ 
Dont short the market now. Wait till they all hit new ATHs to short. Your chances will be a lot better to make money. Now is not the time to short the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:18:44 </td>
   <td style="text-align:left;"> $AAPL https://invezz.com/news/2021/12/22/citi-analyst-explains-why-apple-stock-will-continue-to-rally-in-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:18:09 </td>
   <td style="text-align:left;"> $aapl If this is not V recovery, what can be.. 

There is no downside to this fed bull market. All bad news shrugged off. Stonks only go up.. It&amp;#39;s okay to be stupid if it makes me money in this market. $aapl to hit $180 tomorrow. 

$spy $qqq $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:15:10 </td>
   <td style="text-align:left;"> $AAPL PCE data going to derail this train that 100% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:14:39 </td>
   <td style="text-align:left;"> $AAPL There is. a good chance this is hitting $180 tomorrow. Grabbing the calls at open and will diamond hand them to $180 

$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:07:58 </td>
   <td style="text-align:left;"> $AAPL definitely bull tomorrow with the way it’s going after market. 180s babyyyyy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:04:51 </td>
   <td style="text-align:left;"> $SPY Reddit saying dump $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 10:04:36 </td>
   <td style="text-align:left;"> $AAPL 171.31 yesterdays open eod tomorrow or close to it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:44:00 </td>
   <td style="text-align:left;"> $AAPL hoping this news doesn’t affect the climb but you never know©️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:42:42 </td>
   <td style="text-align:left;"> $AAPL if you want to know what a textbook American power hour looks like…well, there you have it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:42:19 </td>
   <td style="text-align:left;"> $AAPL how many times this yr have we heard tech selloff. Only to rebound. After this new ATH. Let them drop tech for a few days to a week. But the ducking dip! It always rebounds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:40:25 </td>
   <td style="text-align:left;"> $AAPL 180 tomorrow gay bois </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:36:02 </td>
   <td style="text-align:left;"> $AAPL $QQQ PCE Inflation Data releasing tomorrow morning… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:35:59 </td>
   <td style="text-align:left;"> $AAPL $VENAR Desperate times call for deperate measures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:35:33 </td>
   <td style="text-align:left;"> $AAPL puts engaged </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:33:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : U.S. SEC rejects Apple bid to block shareholder proposal on forced labour -letter https://www.stck.pro/news/AAPL/20187154 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:19:55 </td>
   <td style="text-align:left;"> $AAPL am I going to lose my shares on these covered calls I’m selling that expire tomorrow? 😓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:19:05 </td>
   <td style="text-align:left;"> $AAPL $170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:17:42 </td>
   <td style="text-align:left;"> $SPY I don&amp;#39;t like this fed pumped bull market. But I know that the market will shrug off anything and will run higher closing the year with new ATHs. Just go along with what market does. 

Bulls are stupid, can&amp;#39;t rationalize with them. They are gonna pump all valuations to unsafe territories. Bears are needed in this market. It&amp;#39;s unfortunate that bears are weak. 

$aapl $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:14:38 </td>
   <td style="text-align:left;"> $AAPL please tell me if you think this will end under $177.50 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:12:17 </td>
   <td style="text-align:left;"> $SPY $AAPL    crunch wrap supreme pattern.   
watch out for the hot Gordita. has some kick to it.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:08:08 </td>
   <td style="text-align:left;"> $SPY $AAPL and $TSLA calls are going to print tmrw 😎💸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:07:52 </td>
   <td style="text-align:left;"> $SPY finally!  Two coherent responses to a post within stocktwits!  

See my post on $AAPL &amp;amp; $TSLA for context... 

Will I be right?  Yes....unequivocally... 

Will they be right (too)?  YES....UNEQUIVOCALLY!!! 

I&amp;#39;m still taking bets, but I had to highlight two RARE coherent responses; since they&amp;#39;re few &amp;amp; far between 😆😆😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:07:15 </td>
   <td style="text-align:left;"> $qqq $aapl $spy 

Market is bullish. Stop buying puts for next 3 days. Market may run  much higher before you can short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:02:52 </td>
   <td style="text-align:left;"> $AAPL Simulated 180.0 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 09:02:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-22 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=jPyx5uZDRy4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:59:56 </td>
   <td style="text-align:left;"> $SPY I will bet anybody on this site that both $AAPL and $TSLA are lower in December 2022, than December 2021... 

I&amp;#39;ll max out my bets at $10k (total).  Feel free to divy it up as you please... 👀🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:57:25 </td>
   <td style="text-align:left;"> $AAPL To everyone who is wondering what will happen tomorrow -

Market will run up high. $aapl will lead the way and may hit $180 to print $180 calls. Grab your calls when you can tomorrow.

Market is insanely bullish right now. There is no reason for this market to be even a bit fearful. It has shrugged off every other reason. 

Sell your puts and move to calls asap if you want to be in the winning side. I&amp;#39;m saying what I&amp;#39;m seeing. No bias. 

$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:57:00 </td>
   <td style="text-align:left;"> $AAPL: Volume is considerably higher in the last couple of days, which is what you like to see during a move up. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:56:30 </td>
   <td style="text-align:left;"> Unusual Option Alert on $AAPL $1,519,560 call block traded with latexb74f8547313f003da2afb804f6f0814eAAPL
$NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:48:54 </td>
   <td style="text-align:left;"> $SPY $aapl $qqq Never bet on bears in bull market. Puts won&amp;#39;t print, bears are weak. 

Be the bull, buy calls. MMs will work for you to print the calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:48:51 </td>
   <td style="text-align:left;"> For the die-hard option traders, a gr8 way to maximize profitability is to break down your option traders via a Journal.

TradesViz breaks ur trades down w/ respect to the greeks (IV delta etc) &amp;amp; OPEX. Breaks down where u r losing &amp;amp; winning.
$QQQ $SPY $TSLA $AAPL $NVDA

Join Free  👉 http://www.tradesviz.com

Sample Chart below
👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:48:23 </td>
   <td style="text-align:left;"> $SMURF $AAPL $FB $META $BTC.X 
Like if you believe these tickers will kill it next year as the metaverse becomes a reality. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:45:06 </td>
   <td style="text-align:left;"> $SPY $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:42:44 </td>
   <td style="text-align:left;"> $AAPL $200 eoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:42:05 </td>
   <td style="text-align:left;"> $AAPL Guys I really think it’s going to go past 180 maybe tomorrow like when it hits the 180 I think it’s going to go to 185 or 190 and then start dropping what do you think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:38:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL so pissed at team $PFE for missing the opportunity to have a COVID pill/Viagara combo.

ED and SARS cured in one pill smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:32:33 </td>
   <td style="text-align:left;"> $AAPL &amp;quot;Inflation is Spiking, So Investors Are Seeking Ways to Survive&amp;quot; - my latest article in NewsBreak - Mark R. Hake, CFA - bullish on AAPL https://original.newsbreak.com/@mark-hake-1587739/2467959613183-inflation-is-spiking-so-investors-are-seeking-ways-to-survive?s=influencer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:29:09 </td>
   <td style="text-align:left;"> $AAPL $180 tmrrw? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:28:46 </td>
   <td style="text-align:left;"> $SPY From the article, most will lose money but have a better chance at profits if using spreads. Check out my link For a free week of my spread selling alerts!  https://www.cnbc.com/2021/12/22/options-trading-activity-hits-record-powered-by-retail-investors.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard #options $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:26:28 </td>
   <td style="text-align:left;"> $AAPL almost 10M AH Volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:25:45 </td>
   <td style="text-align:left;"> $AAPL why is robinhood saying 172.99 ah? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:25:09 </td>
   <td style="text-align:left;"> $AAPL $1.54B total DP print AH again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:23:31 </td>
   <td style="text-align:left;"> $AAPL stock analysis is here. 

https://youtu.be/H8pd7_jDbqg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:21:58 </td>
   <td style="text-align:left;"> $AAPL why the fuck calls didn’t move much </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:15:06 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : SEC rejects Apple&amp;#39;s argument that it doesn&amp;#39;t try to silence workers after former employee disputed it https://www.stck.pro/news/AAPL/20184901 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:14:12 </td>
   <td style="text-align:left;"> $AAPL ATH again
https://shop.robindrip.com/collections/aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:14:04 </td>
   <td style="text-align:left;"> $AAPL JUST IN:

The SEC denied latex68d2439bf17f649505369dff942a9eafNVDA - 78% call flow
$AMD - 82% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 08:02:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-22 Trade Analysis Video: 
https://www.youtube.com/watch?v=B651JLQXFWc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:55:05 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ FUTES FUTING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:48:14 </td>
   <td style="text-align:left;"> $AAPL the year is 2030. You invested in good companies and your investments are paying off. 6 months ago you just bought a multi unit apartment complex. 20k in rent checks just hit your bank account. Life is good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:44:57 </td>
   <td style="text-align:left;"> $AAPL If we get strong futes, we could see $180+ tomorrow 🍎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:41:02 </td>
   <td style="text-align:left;"> $AAPL can we see 180 before Xmas? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:38:14 </td>
   <td style="text-align:left;"> $AMZN $AAPL $FB $TSLA 
Robinhood forces you to sell if your margin is near a defici, which makes sense not a problem. But why does it have to withdraw the borrowed funds instead of having the money there so when prices go back up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:37:16 </td>
   <td style="text-align:left;"> $AMZN $AAPL $NFLX $DIS 🟢 🆙 1.123% under this President?
Thank God for little favors. God Bless America!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:34:44 </td>
   <td style="text-align:left;"> $AAPL https://finviz.com/quote.ashx?t=AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:34:07 </td>
   <td style="text-align:left;"> $AAPL When investing, always keep an eye on the future disruptors. Xceptional business have uncanny habit to always come out ahead. Stay invested, nibble pullbacks &amp;amp; do not panic for long-term gains in Apple - https://youtu.be/btBGZB5Fak0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:32:06 </td>
   <td style="text-align:left;"> $AAPL 

Folks 

Tmw economic indicators 

Jobless Claims
Core Durable Goods
PCE
New Home Sales
Michigan Consumer Sentiment

It will be tough to predict tmw EOD PT today.

Just be calm and be safe.

I know tmw Jobless Claims will be ticked higher due to omicron concerns but thank god Biden blunted to halt worries by saying no shutdowns and more mass testing.

Core Durable won’t be factor for AAPL

PCE will be limited factor to AAPL.

Michigan Consumer Sentiment this was for the month of Dec. I expect it will be flat or less due to omicron concern.

Let see how it goes so far for tmw because a lot of people will be out for holidays - it will be less busy day tmw. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:29:30 </td>
   <td style="text-align:left;"> $AAPL can we get this to $180 this week? I sure hope so. But with exp Friday I doubt it. Fingers crossed. I want a new ATH maybe $185 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:28:14 </td>
   <td style="text-align:left;"> $AAPL 🌔🌕🌖🌗🌘🌙🌚🌑🌒🌝🌜🌛 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:25:27 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA FUTES fucking RIPPING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:23:52 </td>
   <td style="text-align:left;"> $AAPL 180
 https://www.interactivebrokers.com/mkt/?src=xiaowangY&amp;amp;url=%2Fcn%2Findex.php%3Ff%3D2359 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:22:14 </td>
   <td style="text-align:left;"> $AAPL nice job </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:17:09 </td>
   <td style="text-align:left;"> $SPY crypto and growth tech won&amp;#39;t be it at a 1% gdp plus higher rates $IWM $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:16:09 </td>
   <td style="text-align:left;"> $spy $aapl $msft $aapl. Man, I am just worried about number of COVId cases after Christmas.  Monday market open can be precarious stick with vaccines $mrna </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:15:04 </td>
   <td style="text-align:left;"> $AAPL If this breaks above $177.5 tomorrow, sell all your puts and convert them to aapl $180 calls. That&amp;#39;s when you know it will get to $180+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 07:12:06 </td>
   <td style="text-align:left;"> $AAPL https://www.cnbc.com/2021/12/22/citi-hikes-apple-price-target-sees-five-reasons-for-upside-in-2022.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:57:38 </td>
   <td style="text-align:left;"> @Goku617 remember I said earlier this month that they&amp;#39;d keep this below 180 $aapl. I think it&amp;#39;s staying below 180 then run up for earnings to the 3t mark </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:55:34 </td>
   <td style="text-align:left;"> $UVXY  🙋‍♀️ $VXX   dropped pretty hard after it sat in a narrow zone . Pays to btfd $TQQQ $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:54:25 </td>
   <td style="text-align:left;"> $AAPL So shorty….Let’s review… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:54:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 7.00. This indicates good health for $AAPL. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:50:53 </td>
   <td style="text-align:left;"> $SPY I don&amp;#39;t see how we drop to 1% Gdp in a year. They prob should already be at a 0.5% hike, lol but housing market going to see some volatility $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:48:44 </td>
   <td style="text-align:left;"> $AAPL  🍏🎄:  ❗️Alert❗️ Massive AfterHours Volume, 9.8 Million AAPL Shares have traded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:47:49 </td>
   <td style="text-align:left;"> $AAPL 
200 by Xmas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:46:29 </td>
   <td style="text-align:left;"> $SPY Why are some saying banks overvalued? $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:41:37 </td>
   <td style="text-align:left;"> $aapl The &amp;#39;beast is back - actually never left... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:40:55 </td>
   <td style="text-align:left;"> $AAPL Simulated 180.0 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:37:12 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : 2022 Looks Set For &amp;#39;Rose&amp;#39;s Income Garden&amp;#39; - Not SPY https://www.stck.pro/news/AAPL/20180337 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:34:23 </td>
   <td style="text-align:left;"> $AAPL if this breakout holds and the next week maintains above 180.  190 in February seems likely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:29:13 </td>
   <td style="text-align:left;"> $V  $ADBE $AAPL are simple. Just buy the dips. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:28:35 </td>
   <td style="text-align:left;"> $AAPL huge dark pool prints on aapl. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:25:01 </td>
   <td style="text-align:left;"> $SMURF $AAPL $FB $META $SPY 
These are my favorite stocks. All about metaverse.
Tomorrow is going to be exciting!
🚀🚀🚀🚀🚀💵💵💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:24:02 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL I&amp;#39;ve helped many followers complete the $10,000 to $100 challenge.  #humbleBrag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:23:31 </td>
   <td style="text-align:left;"> $AAPL how bears read charts 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:20:44 </td>
   <td style="text-align:left;"> $AAPL Bears 🐻 
Winter  🥶 just started - stay in your caves! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:19:33 </td>
   <td style="text-align:left;"> Best Growth Stocks To Buy Now? 3 Consumer Tech Names To Check Out $AAPL $QCOM $MU https://www.billionaireclubcollc.com/best-growth-stocks-to-buy-now-3-consumer-tech-names-to-check-out/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:16:23 </td>
   <td style="text-align:left;"> $AAPL 1.52M Dark Pool block printed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:15:48 </td>
   <td style="text-align:left;"> $AAPL latex2ded5a546aaf6498ded622dd39058620AAPL 172.50C @ 2.24 -&amp;gt; 3.15 (+41%) PT3 HIT 🔥
$NVDA 295C @ 2.81 -&amp;gt; 3.74 (+33%) PT1 HIT 🔥

Total W/L ratio today: 4/4🎯 
4 Wins, 0 Failed 

For the remainder of December, we will be posting the entire Patreon Watchlists on our Discord for FREE 🧀 (link in bio) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:06:17 </td>
   <td style="text-align:left;"> $NFLX Trading at the same high multiple for years. Been no earnings growth because costs outweigh growth at some point $AAPL $SPY $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:04:05 </td>
   <td style="text-align:left;"> $SPY nasdaq 13k $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:03:07 </td>
   <td style="text-align:left;"> $AAPL  This is, &amp;quot;The Battle of Britain&amp;quot;.  It&amp;#39;s Apple against the Luftwaffe.  The bears have light, twin engine bombers, when they need heavy, four engine bombers.  Goering lied, and Hitler&amp;#39;s Germany died.  Goering lost the Battle of Britain, he lost Dunkirk, and he lost the Battle of Stalingrad.  Hitler killed 84 of his generals, but he never killed Goering. 
Do not make the same mistake.  Kill your Goering stocks! 
BTW, AAPL is not one of them, because it&amp;#39;s more like a post-war investment in the future, which went parabolic.  This is like the beginning of the 1950&amp;#39;s, after the very real repression of the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:03:06 </td>
   <td style="text-align:left;"> $AAPL long term.   100% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:01:33 </td>
   <td style="text-align:left;"> $AAPL 178$ 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 06:00:31 </td>
   <td style="text-align:left;"> $AAPL Who think this has a chance of closing the year out at $185 or above. I saw earlier this year that a lot of people were saying it would be $200. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:56:54 </td>
   <td style="text-align:left;"> $AAPL 
Up &amp;amp; down, Good &amp;amp; Bad news one day.
Market down tomorrow, back to $ 172 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:53:00 </td>
   <td style="text-align:left;"> $AAPL Below $170 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:52:25 </td>
   <td style="text-align:left;"> $AAPL are they goin to let this run up to 180 tmrw?? 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:47:27 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Best Growth Stocks To Buy Now? 3 Consumer Tech Names To Check Out https://www.stck.pro/news/AAPL/20177397 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:46:19 </td>
   <td style="text-align:left;"> $AAPL she’s a thing of beauty. I expect AT LEAST a test of highs, but very well could smash through and up to 185. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:44:48 </td>
   <td style="text-align:left;"> $AAPL https://www.reuters.com/legal/litigation/us-sec-denies-apples-bid-dismiss-shareholder-proposal-concealment-clauses-2021-12-22/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:44:24 </td>
   <td style="text-align:left;"> latex57d3ac98e6e3d12d191eed1aec430824NVDA 713k (76% call/24% put)
$PFE 650k (76% call/24% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:40:09 </td>
   <td style="text-align:left;"> $AAPL Simulated 180.0 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:36:04 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 760.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:35:20 </td>
   <td style="text-align:left;"> $AAPL $SPY $AMD $MSFT $AMZN best economy ever! Best stonk market ever! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:35:18 </td>
   <td style="text-align:left;"> $AAPL Monthly chart with 9 and 20 period moving averages. Purely bullish price action. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:33:37 </td>
   <td style="text-align:left;"> $TSLA $AAPL Today was 1-2 punch, tomorrow is 3-4!  ABCD TO THE ROOF!!!!!! Both have near identical charts .  AAPL next week setup for 3T ball! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:32:08 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-22 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=jPyx5uZDRy4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:32:01 </td>
   <td style="text-align:left;"> $AAPL germany hold Apple 🍏🍏🍏🍏🍏🍏🍏🍏🍏❤❤❤❤❤❤ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:30:35 </td>
   <td style="text-align:left;"> $AAPL anyone got any articles about secret cook China deal that’s feeding them aapl tech to be used against the United States? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:28:20 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:27:42 </td>
   <td style="text-align:left;"> $AAPL $TSLA 

PCE data tomorrow and markets closed on Friday.

Going to be some profit taking and low volumes… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:27:10 </td>
   <td style="text-align:left;"> $SPY Tesla&amp;#39;s have so many issues and are near impossible to repair. Ford mustang is no brainer $IWM $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:26:56 </td>
   <td style="text-align:left;"> $AAPL money machine go brrrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:26:54 </td>
   <td style="text-align:left;"> $AAPL 
🍏
NASDAQ FUTURE AFTER HOURS GOING FOR POSITIVE A LOT. 

SURPRISES …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:25:59 </td>
   <td style="text-align:left;"> $SPY $IWM Interesting $AAPL $AAL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:25:32 </td>
   <td style="text-align:left;"> $AAPL are you my secret santa?😢 
give me $200 !🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:25:12 </td>
   <td style="text-align:left;"> $AAPL love you 🍎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:25:05 </td>
   <td style="text-align:left;"> $AAPL Those big boys buying 300,000 CALLs worth 27 million with out of the money and one day to extirpation  to keep this Gama Squeeze  going. Just do not get caught with your pants down tomorrow - those CALLs will expire. 
 
All mega caps are being pulled up via options, this not not a rally - its a manipulation and it will end very abruptly.  
 
I wonder what SEC is doing, market manipulation is so obvious  5 year old can see it, but for some reason they do not want to investigate anything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:24:39 </td>
   <td style="text-align:left;"> $AAPL someone said no1 banks with citi. Guess what a fet today that’s my bank! Thanks citi bank God bless &amp;amp; merry Xmas bulls &amp;amp; filthy bears too 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:24:37 </td>
   <td style="text-align:left;"> $TSLA Being first in the space means nothing anymore $AAPL $AMZN $WMT $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:24:19 </td>
   <td style="text-align:left;"> $177.44 give me $185
$AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:24:02 </td>
   <td style="text-align:left;"> $AAPL i love this stock
💍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:24:00 </td>
   <td style="text-align:left;"> $AAPL $DIS $TSLA ALL OP Wire and Chat plays PAID! Per usual, OP is STACKING!
Are YOU stacking massive gains? 
No excuse not to be! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:23:13 </td>
   <td style="text-align:left;"> $AAPL sold 70 of my $175 calls right before close. Kept 5 as lottos. Thanks for the money you little bitch shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:22:50 </td>
   <td style="text-align:left;"> $TSLA $AAPL ABSOLUTE Definitions of the San3Ta rally!  There aren&amp;#39;t better trading days than this...and tomorrow there is still some room!  Calls are the highest I&amp;#39;ve seen this year in 2 trading days....expecting a 300-400 dow open, 30-40 point S&amp;amp;P if not higher! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:22:35 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ 

https://seekingalpha.com/amp/article/4475662-own-apple-aapl-stock-through-berkshire-hathaway </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:21:48 </td>
   <td style="text-align:left;"> $tsla Reversal Confirmed, heading to new highs tomorrow 📈 📈 
$qqq $spy $amd $aapl Strong close today, congrats 🎊 Tomorrow will be big bull party 🎉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:21:32 </td>
   <td style="text-align:left;"> $AAPL 176+ tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:20:54 </td>
   <td style="text-align:left;"> $AAPL 

I going to say something…. I see $Aapl in $195 before FINAL YEARS. 
HAPPY HOLIDAYS &amp;amp; MERRY CHRISTMAS. FAMILY 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:20:32 </td>
   <td style="text-align:left;"> $AAPL  🍏🎄😎:   Sweet, Sweet, AAPL.  Be humble, be gracious, share your good fortune with someone in need this Christmas.  Until, tomorrow…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:20:21 </td>
   <td style="text-align:left;"> $AAPL wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:20:06 </td>
   <td style="text-align:left;"> $AAPL $170 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:19:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Hope ya&amp;#39;ll boys took profits...it&amp;#39;s time to pay the piper tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:18:50 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Omicron accounts for 290% of Covid cases in some parts of the U.S., CDC director says </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:18:16 </td>
   <td style="text-align:left;"> $MSFT $AAPL $AMZN $VIX vix collapsed to 18.68…. This rally is not head fake… it has legs … to continue tomorrow… gapping up. Looks like an early weeken 🥃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:17:24 </td>
   <td style="text-align:left;"> Most Active Options $AAPL $TSLA $PFE $NVDA $F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:17:00 </td>
   <td style="text-align:left;"> $AAPL $msft $goog $mu $qcom sleep better with these stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:16:40 </td>
   <td style="text-align:left;"> $AAPL 🍏 $175.95 ….#IToldYou. 

I Can’t Believe it. 

It’s a Big-Monster. 

Only can says “BRUTAL” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:16:36 </td>
   <td style="text-align:left;"> $SPY $AAPL $ES_F wow I called this 100% correct. The algos are following me. I don&amp;#39;t follow them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:15:54 </td>
   <td style="text-align:left;"> $AAPL $V $DIS let’s hope for more green bags my fellow bulls &amp;amp; call holders 👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:15:29 </td>
   <td style="text-align:left;"> $AAPL tomorrow $180 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:15:23 </td>
   <td style="text-align:left;"> $AAPL how do I know when to sell my call option 220$ March 18th .83¢ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:14:53 </td>
   <td style="text-align:left;"> $spy well, as an independent, impartial enough to say be thankful for the Pres. - he is santa for saying he&amp;#39;ll get something done with Manchin and for getting a handle on omicron.  $qqq $pfe $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:14:10 </td>
   <td style="text-align:left;"> $AAPL dang there really is a santa! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:13:22 </td>
   <td style="text-align:left;"> $AAPL But the 🤡🤡🤡 said we’re not breaking 175.00 today. 🤣😂🤣😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:12:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ Is it worth it to trade tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:12:30 </td>
   <td style="text-align:left;"> $AAPL what are the chances it hits 180+ tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:10:42 </td>
   <td style="text-align:left;"> $AAPL LETS GO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:10:21 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:09:22 </td>
   <td style="text-align:left;"> $AAPL he we’re going again! This time $190 is ATH! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:08:35 </td>
   <td style="text-align:left;"> $AAPL I REALLY need this to close under $177.50 tomorrow… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:08:25 </td>
   <td style="text-align:left;"> $AAPL aftermarket is still scorching! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:07:18 </td>
   <td style="text-align:left;"> $SPY $QQQ  $AAPL Stocks are overvalued… it’s the end of the world… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:07:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple&amp;#39;s supply chain issues could cost $2 billion, says Loup Ventures&amp;#39; Munster https://www.stck.pro/news/AAPL/20176235 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:06:54 </td>
   <td style="text-align:left;"> $AAPL wake this beast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:05:45 </td>
   <td style="text-align:left;"> $AAPL finished up 1.53% to $175.64 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:05:41 </td>
   <td style="text-align:left;"> $AAPL very nice close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:05:06 </td>
   <td style="text-align:left;"> $AAPL 🥰🥰🥰🥰🥰🥰🥰❤❤❤❤🧡🧡💋💋💋💋💞💞💞💞💘💘💘💘💘💘🙏🙏🙏🙏🙏👊👊🙏👊👊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:04:37 </td>
   <td style="text-align:left;"> $AAPL 3trillion market cap incoming gonna have bear meat on Christmas Day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:03:34 </td>
   <td style="text-align:left;"> $AAPL we should be trending! Let’s go bulls! $190 this time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:03:33 </td>
   <td style="text-align:left;"> $AAPL they’re keeping those baby bears quiet again I see 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:03:10 </td>
   <td style="text-align:left;"> $AAPL $180 by Dec 31 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:02:56 </td>
   <td style="text-align:left;"> TOP INFLOW TODAY :

$AAPL $BB latex62693d071ba712abaa70bf2cf7451672AMKR + Sidoti

RECAP 12/22 -Neg Comments:
$HUBS - Kerrisdale

Live Breaking trading news
www.openoutcrier.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:02:29 </td>
   <td style="text-align:left;"> $AAPL well if there were any bears here I would have a lot more to say but without their presence this is nothing more than a fucking circle jerk!  Haha! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:01:56 </td>
   <td style="text-align:left;"> $AAPL woo hoo.

Just sold the dipping at less loss which was ok because don’t want to waste premium for tmw. 

But overall I am looking good !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:01:42 </td>
   <td style="text-align:left;"> $AAPL Nice close 👍🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:01:37 </td>
   <td style="text-align:left;"> $AAPL just you wait until tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:01:20 </td>
   <td style="text-align:left;"> $AAPL 🍏EXCELLENT FINAL $175.64
AH $177. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:01:19 </td>
   <td style="text-align:left;"> $AAPL That was better than an UFC pay per view </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:01:05 </td>
   <td style="text-align:left;"> $AAPL A-m-a-z-i-n-g. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:00:55 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:00:42 </td>
   <td style="text-align:left;"> Santa Rally False Breakout 📉🔻🎅 
I loved the rally but now it’s fumes.
There’s no money into negative divergence, algos no it and so does Wall Street. Be careful.  

$SPY  $TSLA $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 05:00:38 </td>
   <td style="text-align:left;"> $AAPL muahahahaha thanks bears. Make 80% on my 75 contracts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-23 04:59:59 </td>
   <td style="text-align:left;"> $AAPL I loaded 100 180c expiry tomorrow. I’m ready for lotto Friday’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:25:47 </td>
   <td style="text-align:left;"> 13 days left till General Motors Silverado EV reveal in CES. GM’s flagship competitor to the Ford Lightning and Cybertruck is coming for the masses.

Last year CES event caused a major bullish run for GM. Start accumulating.

$GM $F $TSLA $RIVN $CHPT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:20:35 </td>
   <td style="text-align:left;"> $TSLA We have to face up to the datum that Tesla’s actual deliveries always beat the market’s predictions. 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:18:37 </td>
   <td style="text-align:left;"> $TSLA the higher it goes, the cheaper those 2023 puts are 😊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:17:33 </td>
   <td style="text-align:left;"> $TSLA so we seeing $,$100 or what today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:17:00 </td>
   <td style="text-align:left;"> $TSLA How much will we go up today? 👀👀

https://www.benzinga.com/amp/content/24750963 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:16:33 </td>
   <td style="text-align:left;"> $TSLA and another one... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:15:56 </td>
   <td style="text-align:left;"> $TSLA yes, and yes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:15:24 </td>
   <td style="text-align:left;"> $TSLA short at opening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:15:24 </td>
   <td style="text-align:left;"> Ticker: $TSLA
Buy: December 31, 2021 $1010.00 Calls
Entry Price: $33.00 - $33.05
Exit Price: $40.59
Stop Loss: $29.04
Potential ROI: 23%
Estimated Hold Time: 32 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:11:13 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Elon Musk offloads more Tesla shares for $15.4 billion in total, saying there&amp;#39;s still a few more chunks to go https://www.stck.pro/news/TSLA/20209945 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:11:05 </td>
   <td style="text-align:left;"> $TSLA is also expected to have cancelled 43% of this year&amp;#39;s sales which were fake it turns out 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:11:04 </td>
   <td style="text-align:left;"> $TSLA “…plus the options exercise stuff.” 
Elon Musk is not done selling as of yet. 
I’m still buying with every cent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:10:11 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:10:01 </td>
   <td style="text-align:left;"> $TSLA most retail &amp;quot;traders&amp;quot; and investors are totally confused now. They were absolutely unprepared for such &amp;quot; complex&amp;quot; situation as Elon&amp;#39;s September plan. 

But be sure, smart money are not confused at all. Cuz there is absolutely nothing complicated here. And all comments of Musk were accurate actually.

Smart money don&amp;#39;t post in Stocktwits and Twitter, they keep insight for themselves and just trade accordingly.  So, this confusion of retail gamblers doesn&amp;#39;t matter. The stock will go in the right direction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:09:40 </td>
   <td style="text-align:left;"> $TSLA The market will respond to it.  📈📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:09:02 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:08:14 </td>
   <td style="text-align:left;"> $TSLA https://electrek.co/2021/12/23/tesla-tsla-secures-graphite-anode-material-battery-production-offtake-deal/ 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:06:45 </td>
   <td style="text-align:left;"> $TSLA bears, where is my 600 premarket you were all saying yesterday after hours? 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:05:58 </td>
   <td style="text-align:left;"> $TSLA can we reach 1100 eod? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:01:21 </td>
   <td style="text-align:left;"> [Pre-market Analysis] December 23rd : pennystocks  $TSLA https://www.billionaireclubcollc.com/pre-market-analysis-december-23rd-pennystocks/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 19:00:08 </td>
   <td style="text-align:left;"> $TSLA Yesterday Elon already told us. 🚀🚀🚀$1100 is on the way, A Xmas gift 🎁 from Elon. 💰💰💰💰💰💰💰💰💰💰💰💰👈😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:59:15 </td>
   <td style="text-align:left;"> $TSLA Elon just owned all you shorts.  I guess I can see why shorts are so miserable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:59:07 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s a union getting clapped... Yesterday&amp;#39;s GEM
https://youtu.be/YpZ8MjLkkNs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:56:15 </td>
   <td style="text-align:left;"> $TSLA I’m loading the boat all day. Definitely stock split  news will be announced during the holidays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:56:14 </td>
   <td style="text-align:left;"> $TSLA 

Musk- “I’m done selling”

Yesterday - sells 1 million shares during the tweet pump 

WTF? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:56:09 </td>
   <td style="text-align:left;"> $TSLA will not be surprised when we pullback a bit short term but on the daily this thing is still oversold like crazy. January is going to be a fun month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:56:07 </td>
   <td style="text-align:left;"> $TSLA TOTAL RECALL!
JUST AS THE PROPHECY FORETOLD!
https://www.newsmax.com/newsfront/auto-safety-investigation-tesla-vehicles-games/2021/12/22/id/1049585/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:55:20 </td>
   <td style="text-align:left;"> $TSLA 

Shorts: But but Elon is not completely done selling…omg…I shorted cuz Tesla valuation is insane…bubble will pop

Longs: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:53:56 </td>
   <td style="text-align:left;"> $TSLA soo anyone know if that article claiming he sold again yesterday is legit ? Claiming his total is now 15.4 billion. If so than we might rally more than I thought short term. I already knew before big money was front running his sales with short positions making it seem more drastic than it was. There was a few big volume red candles yesterday so it would seem to make sense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:53:40 </td>
   <td style="text-align:left;"> $TSLA 

https://www.forbes.com/sites/teakvetenadze/2021/12/22/580000-tesla-vehicles-under-investigation-over-gaming-feature-regulators-warn-can-distract-drivers/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:53:20 </td>
   <td style="text-align:left;"> $TSLA ouch still selling $5billion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:53:05 </td>
   <td style="text-align:left;"> Beautiful start to the day so far 🔥

40% on $KTTA (top leading in volume so far)✅ 🔥

$ENSC Watchlist idea 25% pop ✅🔥

65% and market hasn’t opened yet💰 

Ww $ALLK $TSLA $AVCT later today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:52:17 </td>
   <td style="text-align:left;"> $TSLA Someone should tell Elizabeth Warren that if she&amp;#39;s interested in free money she should just invest in Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:50:46 </td>
   <td style="text-align:left;"> $TSLA far from over 1070-1075 up next. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:49:49 </td>
   <td style="text-align:left;"> $TSLA wake and bake to short some more cake once everyone realizes Elon hasn’t sold all his shares 💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:48:30 </td>
   <td style="text-align:left;"> $TSLA  I just see so much ROBUST GROWTH in TESLA! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:48:18 </td>
   <td style="text-align:left;"> $TSLA  very interesting 🤔 apparently those Twitter accounts steal content from Stocktwits selectively. I posted BS for testing and it wasn&amp;#39;t replicated, but postings full with incredible insight and eternal wisdom are getting copied immediately and posted in Twitter. 
Apparently some humans behind this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:48:04 </td>
   <td style="text-align:left;"> $SPY $tsla $appl $amd $amc $fb
Again... Fear not. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:47:34 </td>
   <td style="text-align:left;"> $TSLA unfortunately the market is closed tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:46:57 </td>
   <td style="text-align:left;"> $TSLA Elon supreme being 2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:46:55 </td>
   <td style="text-align:left;"> $TSLA we are flying :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:46:17 </td>
   <td style="text-align:left;"> $TSLA love waking up to this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:45:36 </td>
   <td style="text-align:left;"> $TSLA +480% 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:43:39 </td>
   <td style="text-align:left;"> $TSLA https://markets.businessinsider.com/news/stocks/elon-musk-tesla-stock-sales-almost-done-selling-stake-goal-2021-12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:43:36 </td>
   <td style="text-align:left;"> If you could only buy 1 OTM Call which would it be? 

$AAPL $200 

OR

$TSLA $1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:42:33 </td>
   <td style="text-align:left;"> $DOGE.X $COIN $TSLA $HOOD

What is Coinbase Custody?
Launched in 2018, Coinbase Custody offers clients access to the secure, institutional-grade offline storage solution that has been used by Coinbase’s exchange business since 2012. Coinbase Custody is an independent, NYDFS-regulated entity built on Coinbase’s crypto-first DNA, offering the most sophisticated and reliable custody solution in the world.

https://twitter.com/CoinbaseInsto/status/1470444809764491269?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:40:48 </td>
   <td style="text-align:left;"> $TSLA downside risk from here 30-40 bucks, upside reward 80 bucks (everything very short term, hours - days) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:39:55 </td>
   <td style="text-align:left;"> $SPY i finally know the purpose of life
To be financial free, and no need work
Doesn&amp;#39;t matter 10k or 100k per month
Even 3k is enough!!! $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:39:31 </td>
   <td style="text-align:left;"> $TSLA shit today looks bullish, oh well let&amp;#39;s make my profile pic proud lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:37:43 </td>
   <td style="text-align:left;"> A Peek Into The Markets: US Stock Futures Edge Higher Ahead Of Economic Data  $STNE $AVO $TSLA $BANR $NVAX 

https://newsfilter.io/a/1ac31f7064900b2f133e1f5b9a8bec35 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:37:21 </td>
   <td style="text-align:left;"> $TSLA 🚀🚀⚡️⚡️⚡️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:35:20 </td>
   <td style="text-align:left;"> $LIDR Velodyne Lidar Provides Perception Technology for ROBORACE Autonomous Racing Series 
Velodyne Official Lidar System Provider in Next Generation ROBORACE Vehicles  
https://apple.news/AKuLjEYjrSfqWMrFmOoTDkQ 
check out our news $TSLA $NEO $F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:35:19 </td>
   <td style="text-align:left;"> $TSLA https://brandequity.economictimes.indiatimes.com/news/business-of-brands/us-probing-whether-tesla-gaming-feature-poses-crash-risk/88451227 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:34:41 </td>
   <td style="text-align:left;"> $TSLA 
Elon musk 
Is one of the most Intelligent person in the world 🌎 ,
Tesla cars one of the best Existing electric cars!!! Y is not $3000 a stock? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:33:39 </td>
   <td style="text-align:left;"> One way of making passibe income is $BANK.X  
 
Check it out 
 
$CINU.X  $XRP.X  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:32:25 </td>
   <td style="text-align:left;"> $TSLA real price will come out soon; follow price targets, stock.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:29:58 </td>
   <td style="text-align:left;"> $TSLA China crash, India crash, us market is struggling (don&amp;#39;t be fooled by indexes) and at tesla its christmas, what a joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:29:49 </td>
   <td style="text-align:left;"> $UBER $AAPL $TSLA 
search it &amp;quot;3q82dwzcRp&amp;quot; on Google and checkout the first link! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:29:12 </td>
   <td style="text-align:left;"> $TSLA TSLA stock price, &amp;quot;There&amp;#39;s always instant torque&amp;quot;! Just like at 4:18 in the video! https://youtu.be/odAfC8JSX7o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:28:38 </td>
   <td style="text-align:left;"> Government spending as well as supply shocks have fueled inflation, but in recent weeks, crypto and commodities have done little to shield 🛡 investors. 

Consider another approach. 

$GLD $NVDA $UNG $TSLA #BTC

https://www.zerohedge.com/news/2021-12-23/proof-government-spending-causing-inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:28:23 </td>
   <td style="text-align:left;"> $TSLA $AAPL OMG we movin on up again 😂🤙🥂💰💰💰💰💰💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:26:15 </td>
   <td style="text-align:left;"> $TSLA short term sentiment apparently seems changed, probably turning bullish for day trading 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:26:09 </td>
   <td style="text-align:left;"> $TSLA TO THE MOON 

https://www.billionaireclubcollc.com/tesla-q4-sales-expected-to-jump-43-on-robust-december-deliveries-truecar-tesla-motors-tsla/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:25:45 </td>
   <td style="text-align:left;"> $TSLA you heard the man. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:24:59 </td>
   <td style="text-align:left;"> $TSLA thank fk i covered my 500 shares short TESLA a few days ago at 898 ... shortly after it moved up, then down, then up ... nice timing ... glta ... good health and trading to all ... what a drunk scam overpriced unregulated manipulated bs nonsense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:22:17 </td>
   <td style="text-align:left;"> $SPY $TSLA: 100 years from now this post will be relevant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:22:14 </td>
   <td style="text-align:left;"> $TSLA  Your bogey for today is $1069.00, BOOK IT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:21:00 </td>
   <td style="text-align:left;"> $TSLA $1100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:20:19 </td>
   <td style="text-align:left;"> $TSLA go go go go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:19:11 </td>
   <td style="text-align:left;"> $NEON wake up America!!! Read up on the lawsuit against Apple, Samsung. It could make Neonode become a tenbagger over night.
Beside that they have their touchless touch and gesture tech since a couple of years. Company about to turn around. Stock cheap - potential enorm
Zzzzzzzzzzzzzzz wake up!!!
Sell $TSLA and $AAPL and help US sky🚀 market cap only $140 million </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:18:27 </td>
   <td style="text-align:left;"> $TSLA we going to Sizzler 🎶🎶🎶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:18:17 </td>
   <td style="text-align:left;"> $TSLA Lol Squeezzze ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:15:07 </td>
   <td style="text-align:left;"> $TSLA very Bullish for 2022. After Elon sold 10% of his holdings Tesla above thy 100$ mark again 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:13:36 </td>
   <td style="text-align:left;"> $TSLA EOY deliveries will be wait for it !!!!!!
Excellent 😂😂😂, 🤑🤑🤑🤑🤑🤑 1200 coming don’t fight it just buy and hold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:12:33 </td>
   <td style="text-align:left;"> $NIO Come to $TSLA 
A chinese company will never be accepted in the US. Even if nio sells 1.000 000 cars the stock price won‘t pass 100$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:12:00 </td>
   <td style="text-align:left;"> $TSLA is one of the better performing stocks in the Automobiles industry. https://www.chartmill.com/stock/analyzer/stock/TSLA?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:11:27 </td>
   <td style="text-align:left;"> $TSLA WALLSTREETBETS ARMY MARCHING GET READY🔥🔥🔥🔥🔥💰💰💰💰🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:10:02 </td>
   <td style="text-align:left;"> $TSLA bears need to cover over the holiday weekend there can be so many positive catalyst that can come out especially since this has corrected over 20% to get this back to ATH .. if not by EOY its definitely gonna get there by earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:08:51 </td>
   <td style="text-align:left;"> Tesla Q4 Sales Expected To Jump 43% On Robust December Deliveries: TrueCar – Tesla Motors (TSLA) 
$TSLA $LCID $RIVN $GM $F https://www.billionaireclubcollc.com/tesla-q4-sales-expected-to-jump-43-on-robust-december-deliveries-truecar-tesla-motors-tsla/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:07:42 </td>
   <td style="text-align:left;"> Honestly don’t know why I haven’t done the big YOLO on $TSLA as often as I’m right on this stock I should be retired by now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:06:33 </td>
   <td style="text-align:left;"> $TSLA i mean yea wht else did you expect? Merry Christmas guys my account went brrrrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:05:44 </td>
   <td style="text-align:left;"> $TSLA wsb gonna blow this out the world 😳👁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:05:17 </td>
   <td style="text-align:left;"> $TSLA bears ready for ATH ? any news on CyberTruck will blow up shorts 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:04:27 </td>
   <td style="text-align:left;"> $TSLA 1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:04:19 </td>
   <td style="text-align:left;"> $TSLA 1100 and 1200 next week let’s get new highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:03:36 </td>
   <td style="text-align:left;"> $TSLA ok so maybe it&amp;#39;s not going to 975 at open, but sub 1010 is still possible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:03:25 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-22 Largest Trades Data: 
https://www.youtube.com/watch?v=P7puwI2wqB8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:02:35 </td>
   <td style="text-align:left;"> $TSLA run run run to 1200 by year end! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:01:53 </td>
   <td style="text-align:left;"> $TSLA Don&amp;#39;t forget to take profits along the way brothers and sisters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:01:44 </td>
   <td style="text-align:left;"> $SEAC $ALLK $TSLA $CEI $NKLA early morning movers https://youtu.be/R2ndFEg7NPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:01:42 </td>
   <td style="text-align:left;"> $TSLA never doubt Mr Bean, posted yesterday, it has just  hit 1027.93 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:00:47 </td>
   <td style="text-align:left;"> $TSLA Why did I sell early 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:00:19 </td>
   <td style="text-align:left;"> $TSLA Drama aside, Tesla is a momentum stock, says Canaccord&amp;#39;s Dorsheimer https://www.cnbc.com/video/2021/12/22/drama-aside-tesla-is-a-momentum-stock-says-canaccords-dorsheimer.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 18:00:16 </td>
   <td style="text-align:left;"> $TSLA Lol Short float ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:59:12 </td>
   <td style="text-align:left;"> $TSLA excited for January, the earning date, and the opening of two new gigafactory could be anytime. 
$ALLK Go go go ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:58:47 </td>
   <td style="text-align:left;"> $TSLA printing machine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:58:28 </td>
   <td style="text-align:left;"> $TSLA $1100 here we come 🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:58:06 </td>
   <td style="text-align:left;"> $TSLA can you imagine being short overnight? They are making people broke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:57:59 </td>
   <td style="text-align:left;"> Cathie Wood Loads Up Another $800K In This Chinese Tesla Rival Ahead Of Its Overseas Expansion – Tesla Motors (TSLA) $XPEV $LI  $TSLA $LCID $F https://www.billionaireclubcollc.com/cathie-wood-loads-up-another-800k-in-this-chinese-tesla-rival-ahead-of-its-overseas-expansion-tesla-motors-tsla/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:57:43 </td>
   <td style="text-align:left;"> $TSLA oh shit WSB is Here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:57:16 </td>
   <td style="text-align:left;"> $NKLA $TSLA $RIVN Heniff Transportation Signs LOI With The Intent To Purchase 100 Zero-Emission Trucks From Thompson Truck Centers And Nikola
Agreement includes an initial purchase or long-term lease of 10 battery-electric trucks
PR NEWSWIRE https://www.thestreet.com/press-releases/heniff-transportation-signs-loi-with-the-intent-to-purchase-100-zero-emission-trucks-from-thompson-truck-centers-and-nikola-15868929 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:56:43 </td>
   <td style="text-align:left;"> $TSLA Take us to Mars Mr. Musk - ahee. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:54:06 </td>
   <td style="text-align:left;"> $TSLA bears go to Xpeng/Li or Nio if you want to make money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:53:55 </td>
   <td style="text-align:left;"> $NKLA $PLUG $TSLA  The #RenewableHydrogen GREEN journey has started! 

Sattelschlepper GIANT trucks to move the huge #GreenHydrogen storage tanks Tastenkappe Ziffer 7Tastenkappe Ziffer 2Tastenkappe Ziffer 0 km across Spain to the plant we are building, a new 100% renewable facility to boost the #EnergyTransitionBatterieIm Wind flatterndes Blatt.
https://iberdrola.com/press-room/news/detail/storage-tanks-green-hydrogen-puertollano?utm_source=twitter&amp;amp;utm_medium=social&amp;amp;utm_campaign=hydrogenhttps://twitter.com/Iberdrola_En/status/1473628523910897664?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:53:54 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:53:37 </td>
   <td style="text-align:left;"> $TSLA ATTENTION!!! THIS IS FOR THE BEARS!!! 
I TOLD U ,LOL 1030-1050-1100$ INEVITABLE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:53:34 </td>
   <td style="text-align:left;"> $TSLA 

Holy crap! LOL 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:51:46 </td>
   <td style="text-align:left;"> $TSLA I’ve been trying to convert bears. It’s never worked, but now they have two jobs 🤣📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:51:31 </td>
   <td style="text-align:left;"> $TSLA Boys the target for today is still the gap created on December 9th at $1068.96,     MERRY CHRISTMAS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:51:28 </td>
   <td style="text-align:left;"> $TSLA bullish now. Gap was filled at 908. It did it’s job. Now to fill the gap at 1212 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:51:21 </td>
   <td style="text-align:left;"> $TSLA  Nuked Yogi on a stick. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:51:02 </td>
   <td style="text-align:left;"> $TSLA ram it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:50:55 </td>
   <td style="text-align:left;"> $TSLA Classic movement 📈📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:50:39 </td>
   <td style="text-align:left;"> $TSLA Honestly was not expecting this much momentum again but LFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:50:31 </td>
   <td style="text-align:left;"> $TSLA $NVDA $ALLK fly to the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:50:27 </td>
   <td style="text-align:left;"> $CABA CABA 20 to 30% possible reversal bounce  today. 400% cheaper from average target price, Bargain price. $BABA $AAPL $TSLA $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:50:22 </td>
   <td style="text-align:left;"> $TSLA 1100 seems more and More real as time goes by, as always anything can happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:49:21 </td>
   <td style="text-align:left;"> $BJDX buckle up! Dear apes! Join forces. We got a runner $AMC $GME $TSLA  🚀💰🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:49:21 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:49:19 </td>
   <td style="text-align:left;"> $TSLA Lol Deliveries 📦 ;p </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:49:07 </td>
   <td style="text-align:left;"> $TSLA I feel sorry for the Tesla shorties. 🤔 Ok I’m lyin, I really don’t. 🤣 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:48:46 </td>
   <td style="text-align:left;"> $spy $dia $ndx $tsla my, my, my,…. New bullish catalyst entered the market for Tesla this morning. That explains the big jump at premarket opening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:48:17 </td>
   <td style="text-align:left;"> $TSLA I hedged with put’s because my calls will more than replace whatever the loss is lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:47:38 </td>
   <td style="text-align:left;"> $TSLA shorts right now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:47:17 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:46:21 </td>
   <td style="text-align:left;"> $tsla $30open space for an easy to $1060 if Tesla gets over $1031 and holds. That’s a nice little lick with call options. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:46:06 </td>
   <td style="text-align:left;"> $TSLA Was was expecting them to hap it down but I was wrong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:45:40 </td>
   <td style="text-align:left;"> $TSLA Santa baby??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:45:19 </td>
   <td style="text-align:left;"> $TSLA $49,500 a day keeps the 9 to 5 away options.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:44:50 </td>
   <td style="text-align:left;"> $TSLA pretty simple here, Elon finished selling and sentiment is adjusted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:44:33 </td>
   <td style="text-align:left;"> $TSLA  To the MOON! OOGA BOOGA! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:43:21 </td>
   <td style="text-align:left;"> $TSLA i love this stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:42:13 </td>
   <td style="text-align:left;"> $TSLA shorts dont flame .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:41:15 </td>
   <td style="text-align:left;"> $TSLA bears it’s Christmas, just buy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:40:40 </td>
   <td style="text-align:left;"> $TSLA 1099.91 and this thing is heading to ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:40:20 </td>
   <td style="text-align:left;"> $TSLA well at least we saw 1025 today at pre market. He highest for today. 950 is the next thing today📉📉📉😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:40:06 </td>
   <td style="text-align:left;"> $TSLA  tsla moves 17billon in market cap on 77k thousand shares how is that legal? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:39:03 </td>
   <td style="text-align:left;"> $TSLA 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:37:05 </td>
   <td style="text-align:left;"> $TSLA this aged like fine wine. 
🎯🎯🎯🎯🎯🎯🎯🎯🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:36:41 </td>
   <td style="text-align:left;"> $TSLA Tesla Q4 Sales Expected To Jump 43% On Robust December Deliveries: TrueCar 

https://newsfilter.io/a/ca347210e28a4778cad9b49bf6f75aaf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:36:03 </td>
   <td style="text-align:left;"> $TSLA  1038.85 long to break 1073.25, What you looking for? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:35:41 </td>
   <td style="text-align:left;"> $TSLA you&amp;#39;re not gonna have another 7% so easy again today so calm down really 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:34:58 </td>
   <td style="text-align:left;"> $TSLA do we get another investigation from NHTSA today? Cuz the the stock is running pre mkt again.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:34:31 </td>
   <td style="text-align:left;"> $TSLA My dad said that a 5% gain is very likely today 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:34:28 </td>
   <td style="text-align:left;"> $TSLA Bears how are ur puts? $930 right? 🤣😆. You will never learn that no one shorts the BEAST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:33:32 </td>
   <td style="text-align:left;"> $TSLA nobody’s going to want to miss this may have some massive gaps up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:33:04 </td>
   <td style="text-align:left;"> $TSLA [Dec-23 985.00 Puts] Option volume Up +38800.00 % |  Volume: 14,393 vs 37 https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:32:40 </td>
   <td style="text-align:left;"> $TSLA wow broke It easy. This might go to $1100 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:32:35 </td>
   <td style="text-align:left;"> $tsla Woooo! Calm down big boy. That bull came out the gate before the gate was even opened all the way. 👀👀 
 
Save that energy for market’s open 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:32:24 </td>
   <td style="text-align:left;"> $TSLA  1026......lol possible by bell 1052 then after bell 1100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:32:15 </td>
   <td style="text-align:left;"> $TSLA How can this shit keep going up? Who keeps buying? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:32:09 </td>
   <td style="text-align:left;"> $TSLA 1025 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:31:59 </td>
   <td style="text-align:left;"> $TSLA MONSTER GAP UP TODAY !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:31:50 </td>
   <td style="text-align:left;"> $TSLA OCTOBER VIBEZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:31:41 </td>
   <td style="text-align:left;"> $TSLA Bears? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:31:05 </td>
   <td style="text-align:left;"> $TSLA Tesla is en Fuego!!! 🔥🔥🔥🔥🚀🚀🚀🚀🚀🚀🚀🎁🎁🎁🎁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:30:55 </td>
   <td style="text-align:left;"> $TSLA first rejection at resistance. This breaks. Watch out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:30:48 </td>
   <td style="text-align:left;"> $TSLA your puts are toast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:30:44 </td>
   <td style="text-align:left;"> $TSLA will open at 1040 🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:30:22 </td>
   <td style="text-align:left;"> $TSLA Musk admitting taking profits also, not all was for taxes, brother sold, board members sold, and people are now buying at those levels? hahahahaha stupidity on a whole new level </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:30:15 </td>
   <td style="text-align:left;"> $TSLA will at 1040 💦💦💦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:30:07 </td>
   <td style="text-align:left;"> $TSLA ... $1,022 currently 😸 ... can we finish at $1,050 ? - that would be awesome 🎁🎄🥂🍾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:30:06 </td>
   <td style="text-align:left;"> $TSLA the market is not even opened here... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:30:05 </td>
   <td style="text-align:left;"> $TSLA Left the screens early yesterday but what a day that was... up a nice 7%! Pre market looking good aswell... might get the $1050 today.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:29:19 </td>
   <td style="text-align:left;"> $TSLA TO ALL THE BEARS YOU GUYS ARE MORE THAN WELCOME TO JOIN THE ROCKET BEFORE THE SPLIT AND THE FACTORIES OPENING 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:28:52 </td>
   <td style="text-align:left;"> $TSLA posted yesterday right after mkt closed
It is aging well, right now 1022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:28:52 </td>
   <td style="text-align:left;"> $TSLA the fuck. It is running. Not stopping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:28:45 </td>
   <td style="text-align:left;"> $TSLA praying to hold till open. No dump at open plzzz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:28:28 </td>
   <td style="text-align:left;"> $TSLA open at $1050 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:28:13 </td>
   <td style="text-align:left;"> $TSLA my hands feels like it could slap the shit out of these tesla bears 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:27:43 </td>
   <td style="text-align:left;"> $TSLA is bringing the Santa today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:27:33 </td>
   <td style="text-align:left;"> $TSLA  🤣🤣🤣 bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:26:53 </td>
   <td style="text-align:left;"> $TSLA as the stock price goes up, more calls go into the money, the more MMs need to hedge the call positions. This is a very textbook example of a gamma squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:26:17 </td>
   <td style="text-align:left;"> $TSLA HAHAHAH I LOVE IT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:26:05 </td>
   <td style="text-align:left;"> $TSLA it won&amp;#39;t stop going up... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:25:52 </td>
   <td style="text-align:left;"> $TSLA if $1025 breaks that gap on the 4hr is $1070 👀👀🎅🏽🎄🎁🍾 let’s see if these $1050 calls print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:25:46 </td>
   <td style="text-align:left;"> $TSLA Doesn&amp;#39;t really matter where it goes today, but imho they will kill $980+ calls this Friday-- look at the open interest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:24:20 </td>
   <td style="text-align:left;"> $TSLA NICE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:24:04 </td>
   <td style="text-align:left;"> $TSLA what’s current pre market high? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:23:52 </td>
   <td style="text-align:left;"> Here we go 🚀 🚀🚀🚀 $TSLA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:23:46 </td>
   <td style="text-align:left;"> $TSLA my calls are... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:23:29 </td>
   <td style="text-align:left;"> $TSLA puts is the way today.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:22:28 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/I9D4ifGzndY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:22:17 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Analysts Offer Insights on Consumer Goods Companies: and Tesla (TSLA) https://www.stck.pro/news/TSLA/20205213 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:21:54 </td>
   <td style="text-align:left;"> $TSLA I THINK ELON WILL SELL SPACEX, AND INVEST  IN TESLA WHEN HE WILL GO WILD, AND OWN THE EVs CARS INDUSTRY, WITH 25K TESLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:21:49 </td>
   <td style="text-align:left;"> $TSLA here we go....1052 by bell.....then 1100........ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:21:40 </td>
   <td style="text-align:left;"> $TSLA ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:21:01 </td>
   <td style="text-align:left;"> $TSLA Hi Elon Fans!!!  Do your DD on this stock XCUR. you will understand what I am saying, BILL GATES own 5% of this company. check out yesterdays SEC Filings from GATES FRONTIER LLC!! 
https://d18rn0p25nwr6d.cloudfront.net/CIK-0001698530/485434e1-947c-4a3f-a21c-3f5336e1300c.pdf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:19:30 </td>
   <td style="text-align:left;"> $TSLA Going to print  bearish engulfing I bet today, have plenty of time on my puts so let&amp;#39;s see how this goes until EOY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:18:40 </td>
   <td style="text-align:left;"> $TSLA cybertruck is about as real as that marriage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:17:18 </td>
   <td style="text-align:left;"> $TSLA 1015 EOD 1050 easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:16:54 </td>
   <td style="text-align:left;"> $TSLA wheres our xmas present Elon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:16:47 </td>
   <td style="text-align:left;"> $TSLA it’s not gonna keep going down is it? There’s no way!!! 950 eod then open 1k tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:16:16 </td>
   <td style="text-align:left;"> $TSLA https://cleantechnica.com/2021/12/22/nasdaq-blog-tesla-is-the-worlds-top-high-growth-ai-stock/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:15:19 </td>
   <td style="text-align:left;"> $BTC.X holding that 33% drop like some pro bag holders $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:13:57 </td>
   <td style="text-align:left;"> $TSLA slap the ask </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:12:42 </td>
   <td style="text-align:left;"> $TSLA https://www.teslarati.com/tesla-cybertruck-foldable-seat-patent/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:11:41 </td>
   <td style="text-align:left;"> $TSLA if Elon was CEO the US he would only have to get his workers to vote for him to be elected in 2028, that&amp;#39;s if they don&amp;#39;t all shoot each other </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:11:38 </td>
   <td style="text-align:left;"> $TSLA let’s see $1100 + </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:10:34 </td>
   <td style="text-align:left;"> $TSLA LOL we just got a nice push. It’s actually up .6% now. That’s a recent change of $11. prob see 1050 if market sees green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:10:13 </td>
   <td style="text-align:left;"> $TSLA ATH before new year? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:07:15 </td>
   <td style="text-align:left;"> $TSLA Take me to the River </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:06:29 </td>
   <td style="text-align:left;"> $TSLA Woke up early to see the rockets 🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:06:11 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-22 Options Analysis Video: 
https://www.youtube.com/watch?v=V3xN4UmP8UE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:05:07 </td>
   <td style="text-align:left;"> $SPY &amp;amp; $TSLA  ( Three Black Crows ) Discussing How to Recognize a Sneaky Snake Strategy Break out,
72 views • Dec 22, 2021 Lets go Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:04:48 </td>
   <td style="text-align:left;"> $TSLA ripping! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:02:31 </td>
   <td style="text-align:left;"> $TSLA I thought were gapping up bulls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:02:20 </td>
   <td style="text-align:left;"> $TSLA Simulated 1015.0 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:01:58 </td>
   <td style="text-align:left;"> $TSLA dump begins in a few minutes till open at least. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 17:00:57 </td>
   <td style="text-align:left;"> $TSLA couldnt help myself. 880s was too good lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:56:53 </td>
   <td style="text-align:left;"> #Tesla Shares Rally As Musk Stock Sales &amp;quot;Almost Done&amp;quot; $TSLA Also $SPX https://talkmarkets.com/content/stocks--equities/tesla-shares-rally-as-musk-stock-sales-almost-done?post=338814 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:55:24 </td>
   <td style="text-align:left;"> GOOD MORNING, What i noticed on 5 minute time Frame on $TSLA yesterday ,, 1st 15 minutes reading them Candlestick patterns, this done on 5 minute Charted with @TrendSpider  held and showed room how to scalp a fast $322.00 in 2 minutes SNEAKY SNAKE Trading Strategy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:51:37 </td>
   <td style="text-align:left;"> $TSLA $1,014 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:50:12 </td>
   <td style="text-align:left;"> $TSLA Looks like another gap up, run up day.  Bullish engulfing candle on the weekly chart.  🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:47:58 </td>
   <td style="text-align:left;"> $TSLA Omicron is 420% less mild :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:47:09 </td>
   <td style="text-align:left;"> $SPY  $TSLA when  
this pumps we fly all way above aTH let me tell you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:45:18 </td>
   <td style="text-align:left;"> $TSLA Here we go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:43:22 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:41:42 </td>
   <td style="text-align:left;"> $TSLA updated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:41:31 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla Submits Documentation for German Factory – Report https://www.stck.pro/news/TSLA/20202733 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:38:19 </td>
   <td style="text-align:left;"> $TSLA shorts 🩳 have been lost so much money with Tesla and continue to do so since 2011. I’m not a finance advisor but will give you guys a final warning better cover now or much more painful in couple weeks…😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:36:52 </td>
   <td style="text-align:left;"> $TSLA everyone getting their rocks off to 1000 shares traded in Germany is a lunatic 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:28:08 </td>
   <td style="text-align:left;"> $TSLA wth futures not looking good , might be a bad day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:27:23 </td>
   <td style="text-align:left;"> $SPY $TSLA 

Robert Downey Jr. (net worth of $300 mill)
Elon Musk (net worth $261 bill) 

Similar public persona, New Iron Man in the MCU baby! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:25:43 </td>
   <td style="text-align:left;"> $TSLA $2400 by eoy 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:23:29 </td>
   <td style="text-align:left;"> $TSLA $945 close today :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:19:06 </td>
   <td style="text-align:left;"> $TSLA 
He is richest and will be richest forever till he is CEO of Tesla. He can buy pretty much anything.. He can make Billion dollar home like the Indian billionaire did. MSM is after him Because of this. He shd stop tweeting. Messing up with apple and FB. Wtf. 

https://www.forbes.com/sites/lisakim/2021/12/22/elon-musk-has-claimed-home-is-a-humble-50000-house-hes-reportedly-living-in-an-austin-mansion/?sh=3b9aba8d6a5c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:18:22 </td>
   <td style="text-align:left;"> $SPY $TSLA Y’all remember Elon symbolizing in Iron Man? 

https://youtu.be/DCyLOWfIrCU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:16:17 </td>
   <td style="text-align:left;"> $TSLA  $1013.82🔥💰💰💵💵🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:15:33 </td>
   <td style="text-align:left;"> $SPY $TSLA wait Elon said stock sales are “almost done” lmao. That man is rich. Metaphorically and Literally. Lets go $TSLA. Good thing you can hold $SPY up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:13:34 </td>
   <td style="text-align:left;"> $TSLA will we see 937? Hopefully we can fill the gap tmr to close my put. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:12:09 </td>
   <td style="text-align:left;"> $TSLA would for this to dip to 995 again and then rip to 1025,1040,1050,1067 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:10:28 </td>
   <td style="text-align:left;"> $TSLA 

What did I find tonight from the U. k.??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:08:05 </td>
   <td style="text-align:left;"> $TSLA ‘Almost done’: Elon Musk sells more Tesla shares; $15 billion sold in past 7 weeks
https://www.marketwatch.com/story/almost-done-elon-musk-sells-more-tesla-shares-15-billion-sold-in-past-7-weeks-11640233239 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:06:18 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-22 Daily Forecast Video: 
https://www.youtube.com/watch?v=VIQwh_-YtM4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:02:19 </td>
   <td style="text-align:left;"> $AMD $TSLA $NVDA  its thursday with jobless report and last trading day this week.traders will pick gains before xmas so awiat higher volatility and much more way down than up.but maybe Santa come today to stocks..ho ho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:01:40 </td>
   <td style="text-align:left;"> $TSLA $1,013.82 Frankfurt open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:01:22 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Credit Suisse Sticks to Their Hold Rating for Tesla (TSLA) https://www.stck.pro/news/TSLA/20202097 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:01:21 </td>
   <td style="text-align:left;"> $NAKD Old article very relevant information especially when we get all this out in the open so the shorts and bears can see how really screwed they are about to be. $TSLA ideas just for B2B... Which is a much larger and more consistent buyer in volume of EVs. Then your general public consumer... For now. https://qlcchain.medium.com/qlink-signs-cooperation-agreement-with-cenntro-automotive-group-partnering-in-blockchain-based-26221038997f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 16:00:58 </td>
   <td style="text-align:left;"> AT&amp;amp;T May Offer Investors a Gift That Goes Beyond its Juicy Dividend $TSLA #TSLA https://www.marketbeat.com/n/5002215/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:54:06 </td>
   <td style="text-align:left;"> $TSLA Elon musk exercised today more than 2million shares and sold less than half. He has been doing the same procedure since Nov/08 but since he has been exercising more than he has sold, he now owns more shares than before. Make the count and tell me your conclusions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:51:51 </td>
   <td style="text-align:left;"> $TSLA Funny how all the Bears where flapping them gums and poof ! They all disappeared.
Where did you go? Did you run away? Did you go back down into your moms basement?
You come out to wish us Bulls bad but what’s crazy is how stupid you must feel time and time again for doing what you are good at….being absolutely wrong all the time.
The stampede is coming, what the running of the Bulls begin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:50:51 </td>
   <td style="text-align:left;"> $TSLA she&amp;#39;s a dirty dancer, dancing for money 🎵📻  Tesla goes Tits up tomorrow! Call contracts are lactating 🐄, the same way $SPY  will be at or near $470 STRIKE PRICE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:49:31 </td>
   <td style="text-align:left;"> $TSLA Has anyone watched the movie ”American Psycho” I just keep on watching it cause it’s so good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:48:18 </td>
   <td style="text-align:left;"> latex33c6b6dde8c3233509bf0723670ff804 is the floor tomorrow. Any dip below that is short lived opportunity to load calls for the flight to the moon. We heading to 1020$ at least. 📈🚀💸💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:44:12 </td>
   <td style="text-align:left;"> $TSLA 
LETS GO BRANDON! $1100 BRRRRRRRRR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:42:48 </td>
   <td style="text-align:left;"> $TSLA $1,009.51 in Germany. Let’s open at $1050 tomorrow! 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:40:32 </td>
   <td style="text-align:left;"> $NOK did you know? $NOK has nearly the same one-year performance like $TSLA 👌🏻🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:38:03 </td>
   <td style="text-align:left;"> $BTC.X When you realize you would have been better off buying $TSLA stock for the past 2 years than bitcoin... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:36:34 </td>
   <td style="text-align:left;"> $TSLA current price in Germany market - (eur to Usd conversion is $1006.18) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:35:40 </td>
   <td style="text-align:left;"> $TSLA On Wed EOD everyone knew that another  2 days of Elon&amp;#39;s dumping were left. But overnight we learned, that only ONE dump day is left until Elon is really done

How do u think, it is bearish or bullish? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:33:59 </td>
   <td style="text-align:left;"> $TSLA let’s go 950 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:31:59 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/tesla-may-delivery-285k-cars-in-q4-2021-according-to-rbc-capital-markets?utm_source=dlvr.it&amp;amp;utm_medium=facebook&amp;amp;fbclid=IwAR0KOzWd_FB1l-94sfYs-ELIh27Egy9eahrnVE7huBwjML-u0wVQ0NYnntA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:30:30 </td>
   <td style="text-align:left;"> $TSLA Imagine being a pathetic bear on this rn. This will see 1100’s eoy MINIMUM. To all bears: Hope you’ll be bankrupt by christmas and not a good new year. Eat my shit 💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:28:00 </td>
   <td style="text-align:left;"> $TSLA looking like a $1,020 open possibly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:26:18 </td>
   <td style="text-align:left;"> $TSLA do not know why bears here . History shows Bears always lose </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:22:03 </td>
   <td style="text-align:left;"> $TSLA Why  Tesla is a story of Elon musk? Not a single FAANG talks about CEO and his actions. Elon Elon.. wtf.  He is a brilliant trader and world’s best stock advisors work for him. When do we see Tesla as a Tesla? Elon tweeted this.. Elon sold.. bought.. or said that.. or gonna do it.. gonna pump it.. this is cult.  Tesla is worth combined mc of top 10 automakers in the world. Okay f Elon goes silent on Twitter for 3 weeks this will tank $300 PTs. Stop fanboying Elon. He is smart and great. But Tesla itself has some catalysts coming up in JAN and FEb. No fucking person knows about supply chain impact. He will and want to be 1st trillionaire and he will
Pump. Competition is good for consumers. 2022 would be horrible for all mfg companies not just for car makers. No such thing vertical integration when u need batteries and  minerals. Everyone’s eyes are on it.  I am ready for another split in FEB. He needs money to pay off spaceX debt.  Some more selling is on the cards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:14:20 </td>
   <td style="text-align:left;"> $TSLA  🚀🤑👌 Q4 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:10:15 </td>
   <td style="text-align:left;"> $TSLA why are people still buying puts lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:10:00 </td>
   <td style="text-align:left;"> $TSLA personally? I’d like the stock to go down tomorrow. At another time I’ll want it to go up. It’s all just a game </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:07:46 </td>
   <td style="text-align:left;"> $PLUG Power the EV’s!!! Run out of $tsla lithium at 20% market adoption!!! 
 
50% EV’s by 2030 is the Goal!?!? 
 
https://www.westernjournal.com/bad-news-biden-electric-vehicle-market-may-doomed-due-one-rare-mineral/?utm_source=site&amp;amp;utm_medium=thescoop&amp;amp;utm_campaign=can&amp;amp;fbclid=IwAR17HTdQM0uIE-t-xaLLZyRNj-bDP1wLtWMGhzmRMoQ15ONlQOC-7j3RRwI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:04:40 </td>
   <td style="text-align:left;"> $TSLA 😂😂😂😂😂😂💀💀💀💀💀*ELON MUSK SELLS $928.6M WORTH OF TESLA SHARES $TSLA 

LMAO YALL THOUGHT HE WAS DONE ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:03:46 </td>
   <td style="text-align:left;"> $TSLA FYI

https://www.ls-tc.de/en/stock/tesla-motors-aktie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 15:01:36 </td>
   <td style="text-align:left;"> $TSLA $1,007.89 Frankfurt premarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:59:55 </td>
   <td style="text-align:left;"> $TSLA Frankfurt Bid is at 1011$ right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:57:31 </td>
   <td style="text-align:left;"> SweepCast alerted: $TSLA with Unusual Options Activity Alerted on $1000 CALL Expiring: 12-23-2021 worth 87K🐂 |🥇 Check out ➡️ SweepCast.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:56:59 </td>
   <td style="text-align:left;"> $TSLA I think it’s ups $57 in Frankfurt Germany pre-market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:56:52 </td>
   <td style="text-align:left;"> $TSLA he still has bags for you all don’t worry theres enough for everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:54:59 </td>
   <td style="text-align:left;"> $TSLA gap down on securities fraud </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:52:20 </td>
   <td style="text-align:left;"> $TSLA BING BONG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:51:43 </td>
   <td style="text-align:left;"> $TSLA went up $70 a day I excepted down $25 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:49:22 </td>
   <td style="text-align:left;"> $TSLA 
Correct me if I’m wrong but I think it’s up 7% in Frankfurt Germany pre-market can somebody confirm that please! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:49:22 </td>
   <td style="text-align:left;"> $TSLA pray for the calls🩸🩸🩸🩸 da fuk hope it wont gap down so much. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:47:17 </td>
   <td style="text-align:left;"> $TSLA Market Cap
1.013T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:46:55 </td>
   <td style="text-align:left;"> $TSLA musk committed fraud by talking about his « done selling » and still sold yesterday after the pump so, just drop SEC whistleblower https://www.sec.gov/tcr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:45:52 </td>
   <td style="text-align:left;"> $TSLA https://www.marketwatch.com/story/almost-done-elon-musk-sells-more-tesla-shares-15-billion-sold-in-past-7-weeks-11640233239?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:42:15 </td>
   <td style="text-align:left;"> $TSLA this thing is a beast.  Also guys listen up.  Triller is still available in a few Pre-IPO platforms, I am placing a link for Triller Pre-IPO access down below. I &amp;#39;ve used them a few times, they&amp;#39;ve behave well with me and ya!. Send them a message.
https://be4ipo.net/get-access/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:40:36 </td>
   <td style="text-align:left;"> $TSLA PT by March 🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:39:25 </td>
   <td style="text-align:left;"> $SPY latex2622252d4f4ad7f347592c5de4e6bdadSPY hanging hammer perfectly setup past two days
$SNAP reversing off bottom 👌

Happy Holidays! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:32:33 </td>
   <td style="text-align:left;"> $TSLA look like that “almost done” mean hes selling tomorrow. Gapdown?📉📉📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:31:29 </td>
   <td style="text-align:left;"> $TSLA One more day of sales to go for Elon.  After that - stock split.  I think 1500 by end of February is in the cards. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:31:15 </td>
   <td style="text-align:left;"> $TSLA people are so dumb he tweeted at 9/51am PST and 12:44pm PST clarifying the stock selling. It’s not some new information on which we gap down Imfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:30:45 </td>
   <td style="text-align:left;"> $GME $DJIA $TSLA $NVDA $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:25:15 </td>
   <td style="text-align:left;"> $TSLA Those futures are looking pretty good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:23:55 </td>
   <td style="text-align:left;"> My portfolio isn’t completely dedicated to making money. It’s a blend of capitalism meets altruism. A large chunk of it is designed around green energy and efficient energy solitons. Wind, solar, hydro are forms of energy but guess what so is money &amp;amp; human capital! $COUV $TSLA $WULF $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:21:38 </td>
   <td style="text-align:left;"> $TSLA $F $RIVN $LCID Ford is starting to get some of that EV market share... and the memes are a-comin&amp;#39;. What do you think is happening to Ford&amp;#39;s share price. They&amp;#39;re learning how to play that social sentiment game. Nice! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:20:35 </td>
   <td style="text-align:left;"> $TSLA https://t.me/+5ZaeQ_9n7HU4YzJh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:18:06 </td>
   <td style="text-align:left;"> $TSLA ????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:17:34 </td>
   <td style="text-align:left;"> $TSLA gap up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:12:09 </td>
   <td style="text-align:left;"> $TSLA he can&amp;#39;t sell anymore this year....know this next year only and possible closer to the expire which is September 22......know this.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:10:42 </td>
   <td style="text-align:left;"> $COUV my first bitcoin buy was at $19k. I’ll be here a while god willing. There’s no reason $BTC won’t see $500k plus per coin in the future. My first tesla buy $48. There’s no reason $TSLA won’t see $4k per share in the not so distant future. My first COUV buy was ¢.30 they’re no reason COUV won’t see $5 per share in the future. On the flip side I’ve lost some coin on nikola &amp;amp; workhorse. I don’t always win, but I always come out on top. At the end of the day YOU need to execute your own investment strategy, what ever that is! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:10:04 </td>
   <td style="text-align:left;"> $TSLA he clarified he still selling😂smh gap down at open 🩸📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:07:33 </td>
   <td style="text-align:left;"> $TSLA congrats on breaking 1000 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:07:09 </td>
   <td style="text-align:left;"> $TSLA Light @ end of tunnel

https://www.defenseone.com/technology/2021/12/us-army-creates-single-vaccine-effective-against-all-covid-sars-variants/360089/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:04:45 </td>
   <td style="text-align:left;"> $TSLA hows it looking overseas? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:04:35 </td>
   <td style="text-align:left;"> Tesla Is Top WallStreetBets Interest After Elon Musk Says Stock Sales &amp;#39;Almost Done&amp;#39;  $TSLA $SPY $BB $NVDA 

https://newsfilter.io/a/24ca3c137290e3fd79d442759982f960 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:04:24 </td>
   <td style="text-align:left;"> $TSLA after $1500 we split! Why to not to buy or hold? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-23 14:02:53 </td>
   <td style="text-align:left;"> $TSLA we rock$ roll tomorrow boys !!!! </td>
  </tr>
</tbody>
</table></div>

---
